# The fix-issue skill

Let an agent implement a sweeper-reviewed fix for one of your `microsoft/vscode` issues — from your own checkout, under your own identity, as a draft PR you own.

## What the sweeper did for you

The sweeper reviewed the open `microsoft/vscode` backlog with a source checkout and marked the issues an agent can fix — each with a **fix spec** written while tracing the defect. Your ranked list is on [your top-issues page](https://egamma.github.io/vscodesweeper-state/index.html) (filter: *agent-fixable*), and every spec is inspectable there before you run anything.

## Using it

**One-time setup (interim):** until the skill lands in the vscode repo's `.github/skills/` (PR pending; then no install at all), copy [the generated SKILL.md](https://egamma.github.io/vscodesweeper-state/skill/fix-issue/SKILL.md) into `~/.copilot/skills/fix-issue/SKILL.md` or `~/.claude/skills/fix-issue/SKILL.md`. Then, from your vscode checkout, ask your agent:

```
Fix microsoft/vscode issue #262104 using the vscodesweeper fix-issue skill.
```

The *Copy fix prompt* button on the dashboard/top pages copies exactly this line for the row's issue.

## What to expect

- **Live gates first** — refuses closed / security-labeled / not-agent-fixable issues and issues that already have an open PR; warns when the issue changed since its review.
- **The fix + a test** — the review's validation becomes a regression test (fails before, passes after).
- **You approve the diff** — nothing is pushed until you say go.
- **A draft PR you own** — `<you>/fix-<n>`, `Fixes #n`, a "seeded by" link to the record. You flip it to ready — or close it.

## Troubleshooting

- Skill doesn't trigger → say "fix-issue skill" explicitly; restart Copilot CLI after the checkout gains the skill (skills load at session start).
- "Not agent-fixable" refusal → the review found no safe fix spec; check the record for what it concluded instead.
- Pre-merge testing → copy [the generated SKILL.md](https://egamma.github.io/vscodesweeper-state/skill/fix-issue/SKILL.md) into `~/.copilot/skills/fix-issue/` or `~/.claude/skills/fix-issue/`.

_fix-issue skill v1 · generated 2026-08-01 16:53 UTC._
