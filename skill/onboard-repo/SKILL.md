---
name: onboard-repo
description: Author a new sweep-target's review-item.md + vision.md fork for this repo (vscodesweeper). Use when the user wants to add a repository target, onboard a repo to the sweeper, or create a review-prompt fork. Takes the target as <owner>/<name>.
---

# Onboard a repository target

You are inside the vscodesweeper repo. The user names a target repository
(`<owner>/<name>` — ask if it wasn't provided). Your job is to author its
review-prompt fork and vision doc, validate them, and leave a PR-ready
working tree. Full human-facing context: `docs/family-repo-onboarding.md`;
design rationale: `plans/family-sweep-plan.md`.

**Step 0 — prerequisites (check BEFORE any authoring work):**

- You are at the vscodesweeper repo root (`package.json` with name
  `vscodesweeper`; `prompts/review-item.md` exists). If not, stop and say so.
- Dependencies are installed: if `node_modules/` is missing, run
  `npm install` first — `npm run lint-prompts` and `npm run check` need it.
- Node satisfies the repo's pin (`.nvmrc` — Node 24): check `node --version`;
  if it mismatches, tell the user to `nvm use` before continuing.
- `gh` is authenticated (`gh auth status`): the introspection probes and the
  `--live` lint are read-only but authenticated. If it fails, ask the user to
  sign in rather than degrading to guesswork — every repo-specific claim must
  come from a live probe.

Then execute the authoring recipe below, and ALWAYS finish with the
validation loop — do not stop at file creation:

1. `npm run lint-prompts -- --target <owner>/<name> --live` — fix structural
   failures (hard requirements); triage live-label warnings (advisory).
2. `npm run check` — the same rules run in CI; must be green.
3. One dry-run review: `npm run review -- --target <owner>/<name>
   --issue <any-open-issue> --dry-run` (add the target to `config.json`
   `repos` first — `{ "experimental": true }` unless the user says this is a
   full enrollment). While the label evidence from step 1 is still on
   screen, also record the repo's canonical waiting-on-reporter label in the
   same entry: `"needsInfoLabel": "<label>"` — omit it entirely when the repo
   has no such convention (no waiting-on-reporter label in its triage; a
   label that is applied but retired manually still counts). The vscode-tools apply
   capability (Apply & close / Request info under the clicking maintainer's
   own identity) defaults ON for published repos — record `"apply": false`
   only when the repo's owners decline it. Both fields publish to
   `targets.json` as advisory intent for hosts; the host write allowlist
   stays a separate reviewed change there.
4. Produce the introspection evidence summary (per mechanic: the live probe
   that proved it) for the PR description, and remind the user of the gates a
   PR does NOT clear by itself: maintainer calibration and — for family
   repos — the VS Code leadership enrollment OK.

## The authoring recipe

You are authoring the vscodesweeper review-prompt fork for <owner>/<name>
(a VS Code-family repository). Work strictly from evidence; every
repo-specific claim you write must come from a live probe you ran, and the
probes are read-only — you never mutate any repository.

1. BASE: Start from prompts/review-item.md (or the closest existing fork
   under prompts/repos/ if one is a nearer sibling). Adapt by DELETION:
   remove mechanisms the target repo does not have; keep the calibration
   language verbatim wherever the mechanism carries over; add new sections
   only for mechanisms the target actually has.

2. INTROSPECT <owner>/<name> (read-only, cite everything):
   - Full label inventory with descriptions (gh api .../labels --paginate):
     which closing/`*`-labels exist, type labels, whether the area taxonomy
     is small enough to enumerate in the prompt, platform labels, and any
     GitHub default-label residue to ban.
   - Closing mechanics — VERIFY EMPIRICALLY, config lies: does
     .github/commands.json exist, and does the triage bot actually act?
     Sample recently closed `*`-labeled issues (timeline API: who labeled,
     who closed, did a bot comment?) and search commenter:app/... for bot
     activity. This decides label-driven vs manual closes and whether any
     slash command works.
   - Workflows (.github/workflows/): the info-needed closer's closeDays,
     feedback flows (comment-only vs AUTO-closing — decides whether the
     sweeper may ever propose staleness closes), triage stampers.
   - Issue policy docs: the repo wiki (triage/issue-management pages are
     authoritative; a reporting-a-bug page defines the needs-info asks),
     issue templates and config.yml (routing map, support channel).
   - Topology: sibling trackers, transfer-vs-refile practice, upstream
     dependencies; sample real closes to see what maintainers actually do.
   - Lifecycle: verification/test-plan labels, umbrella/process labels,
     milestone usage, release/version format (for fixedRelease guidance).

3. CONSTRAINTS: The OUTPUT CONTRACT JSON-shape block must stay byte-identical
   to the vscode prompt's (`npm run lint-prompts` and test/prompts.test.ts
   enforce this), and the shared invariant lines must survive (never invent
   labels, keep-open default, the fixedSha rule, conservative closing).
   autoFixable is ALWAYS false for a repo without an enrolled fix lane.
   Rewrite every worked example repo-flavored. Open the file with a
   provenance comment: base, sources, verification date.

4. VISION: Draft vision.md from public sources only (roadmap values, README,
   design docs, release notes), three layers (values & guardrails / durable
   themes / current priorities). Mark quotability per layer, mark inferred
   layers as inferred for the repo's team to correct, and add the
   maintenance note (vision is not part of policyHash today).

5. VALIDATE: npm run lint-prompts -- --target <owner>/<name> --live must be
   clean, and npm run check must pass; run a --dry-run review against one
   open issue of the target; summarize your introspection evidence per
   mechanic for the PR description.

Deliverables: prompts/repos/<owner>/<name>/review-item.md + vision.md, plus
the evidence summary. Do not edit prompts/review-item.md, the schema, or any
other repo's fork.
