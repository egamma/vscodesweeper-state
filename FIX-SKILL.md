# The sweeper-fix skill

Let an agent implement a sweeper-reviewed fix for one of your `microsoft/vscode` issues — from your own checkout, under your own identity, as a draft PR you own.

## What the sweeper did for you

The sweeper reviewed the open `microsoft/vscode` backlog with a source checkout and marked the issues an agent can fix — each with a **fix spec** written while tracing the defect. Your ranked list is on [your top-issues page](https://egamma.github.io/vscodesweeper-state/index.html) (filter: *agent-fixable*), and every spec is inspectable there before you run anything.

## Using it

**No setup:** the skill ships in the vscode repo itself (`.github/skills/sweeper-fix/`), so an up-to-date checkout already has it — just pull a recent `main`. Then, from your vscode checkout, paste the prompt the *Copy prompt* button put on your clipboard — the skill invocation plus the reviewed spec, readable and editable before you send it:

```
Fix microsoft/vscode issue #262104 using the sweeper-fix skill.

Reviewed fix spec (edit freely — the skill re-checks the live gates and treats this as your intent):
<the record's fix brief>
Likely files: …
Validation: …
```

Editing the spec is fine — the skill implements your version and still runs every gate; the bare first line alone also works.

## What to expect

- **Live gates first** — refuses closed / security-labeled / not-agent-fixable issues and issues that already have an open PR; warns when the issue changed since its review.
- **The fix + a test** — the review's validation becomes a regression test (fails before, passes after).
- **You approve the diff** — nothing is pushed until you say go.
- **A draft PR you own** — `<you>/fix-<n>`, `Fixes #n`, a "seeded by" link to the record. You flip it to ready — or close it.

## Troubleshooting

- Skill doesn't trigger → say "sweeper-fix skill" explicitly; restart Copilot CLI after the checkout gains the skill (skills load at session start).
- "Not agent-fixable" refusal → the review found no safe fix spec; check the record for what it concluded instead.
- Skill not found → check the checkout has `.github/skills/sweeper-fix/SKILL.md` (pull a recent `main`); on an older checkout, copy [the generated SKILL.md](https://egamma.github.io/vscodesweeper-state/skill/sweeper-fix/SKILL.md) into `~/.copilot/skills/sweeper-fix/` or `~/.claude/skills/sweeper-fix/`.

_sweeper-fix skill v4 · generated 2026-08-21 09:08 UTC._
