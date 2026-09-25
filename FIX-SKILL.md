# The sweeper-implement skill

Let an agent implement a sweeper-reviewed fix for one of your `microsoft/vscode` issues — from your own checkout, under your own identity, as a draft PR you own.

## What the sweeper did for you

The sweeper reviewed the open `microsoft/vscode` backlog with a source checkout and marked the issues an agent can take on — **agent-ready** — each with a **brief** written while tracing the issue. Two tiers: *implement* (the review did the diagnosis; the skill goes straight to the change) and *plan first* (the goal is clear but a design or diagnosis is open; the companion sweeper-plan skill writes the plan with you first, and nothing is implemented until you approve it). Your issues are on the [dashboard](https://egamma.github.io/vscodesweeper-state/dashboard.html)’s *Agent-ready* tab, ranked by value, and every brief is inspectable there before you run anything.

## Using it

**No setup:** the skills ship in the vscode repo itself (`.github/skills/sweeper-implement/` and `.github/skills/sweeper-plan/`), so an up-to-date checkout already has it — just pull a recent `main`. Then, from your vscode checkout, paste the prompt the *Copy prompt* button put on your clipboard — the skill invocation plus the reviewed spec, readable and editable before you send it:

```
Implement microsoft/vscode issue #262104 using the sweeper-implement skill.

Reviewed fix spec (edit freely — the skill re-checks the live gates and treats this as your intent):
<the record's fix brief>
Likely files: …
Validation: …
```

Editing the spec is fine — the skill implements your version and still runs every gate; the bare first line alone also works.

## What to expect

- **Live gates first** — refuses closed / security-labeled / not-agent-ready issues and issues that already have an open PR; warns when the issue changed since its review.
- **The brief, or a plan you approve** — a *ready to implement* record works straight from the review's brief; a *plan first* record starts with `/sweeper-plan <n>`: it puts the open decisions to you, writes the plan to `.sweeper/plans/issue-<n>.md` (git-excluded) and stops — open it in your editor, edit freely, then run `/sweeper-implement <n>` in the same session to implement it.
- **The change + tests, validated against the brief or plan** — every Behavior statement maps to a test (fails before, passes after) and the diff is checked against its boundary before you see it.
- **You approve the changes** — review them in your editor; nothing is pushed until you say go.
- **A draft PR you own** — `<you>/fix-<n>`, `Fixes #n`, a "seeded by" link to the record, the plan (or the brief) in a collapsed block. You flip it to ready — or close it.

## Troubleshooting

- Skill doesn't trigger → say "sweeper-implement skill" explicitly; restart Copilot CLI after the checkout gains the skill (skills load at session start).
- "Not agent-ready" refusal → the review found no brief to work from; check the record for what it concluded instead.
- Skill not found → check the checkout has `.github/skills/sweeper-implement/SKILL.md` (pull a recent `main`); on an older checkout, copy [the generated SKILL.md](https://egamma.github.io/vscodesweeper-state/skill/sweeper-implement/SKILL.md) into `~/.copilot/skills/sweeper-implement/` or `~/.claude/skills/sweeper-implement/`.

_sweeper-implement skill v7 · generated 2026-09-25 10:31 UTC._
