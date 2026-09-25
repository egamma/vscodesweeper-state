# The sweeper agent skills

Two skills, `sweeper-plan` and `sweeper-implement`, let an agent take on a sweeper-reviewed `microsoft/vscode` issue — from your own checkout, under your own identity, ending in a draft PR you own.

## What the sweeper did for you

The sweeper reviewed the open `microsoft/vscode` backlog with a source checkout and marked the issues an agent can take on — **agent-ready** — each with a **brief** written while tracing the issue. The review also sets the tier, and the tier picks the skill:

- **Ready to implement** — the review did the diagnosis (confirmed defect, bounded change, a named validation). `sweeper-implement` goes straight from the brief to the change.
- **Ready to plan** — the goal is clear but a design or diagnosis is open (the brief lists the open decisions). `sweeper-plan` writes the plan with you first; nothing is implemented until you hand the plan to `sweeper-implement`.

Your issues are on the [dashboard](https://egamma.github.io/vscodesweeper-state/dashboard.html)’s *Agent-ready* tab, ranked by value, and every brief is inspectable there before you run anything.

## Using them

**No setup:** both skills ship in the vscode repo itself (`.github/skills/sweeper-implement/` and `.github/skills/sweeper-plan/`), so an up-to-date checkout already has them — just pull a recent `main`. Run them from your vscode checkout, in Copilot Chat (agent mode), the Agents window, or Copilot CLI.

### Ready to implement → `/sweeper-implement <n>`

The *Implement* button in vscode-tools copies the skill call (`/sweeper-implement <n>`) — paste it into Copilot Chat, the Agents window or Copilot CLI, from your vscode checkout; its *Copy full prompt* puts the call plus the reviewed brief on your clipboard, readable and editable before you send it:

```
Implement microsoft/vscode issue #262104 using the sweeper-implement skill.

Reviewed fix spec (edit freely — the skill re-checks the live gates and treats this as your intent):
<the record's fix brief>
Likely files: …
Validation: …
```

Editing the brief is fine — the skill implements your version and still runs every gate; the bare first line alone also works.

### Ready to plan → `/sweeper-plan <n>`, then `/sweeper-implement <n>`

The *Plan* button copies `/sweeper-plan <n>` (its *Copy full prompt* adds the brief):

```
Plan microsoft/vscode issue #262105 using the sweeper-plan skill.
```

1. `sweeper-plan` re-checks the live gates, asks you the review's open decisions in chat, writes `.sweeper/plans/issue-<n>.md` (git-excluded, never committed) and **stops**. It writes no code.
2. Open the plan in your editor and edit it freely — its Behavior statements are what the change will be validated against.
3. Run `/sweeper-implement <n>` **in the same session**: running it is your approval. The skill reads the plan as you left it (a plan from another session or worktree isn't visible), asks only if an edit contradicts an answered decision, and implements.

## What to expect from `sweeper-implement`

- **Live gates first** — refuses closed / security-labeled / not-agent-ready issues and issues that already have an open PR; warns when the issue changed since its review; on a *plan* record without a plan file it refuses and points you at `/sweeper-plan`.
- **The change + tests, validated against the brief or plan** — every Behavior statement maps to a test (fails before, passes after) and the diff is checked against its boundary before you see it.
- **You approve the changes** — in your editor's diff view (Source Control, or the Agents window's Changes pane); nothing is pasted into chat, nothing is pushed until you say go.
- **A draft PR you own** — opened by the skill (not the editor's Create PR button, which would miss the sweeper's markers): `<you>/fix-<n>`, `Fixes #n`, a "seeded by" link to the record, the plan or brief in a collapsed block. You flip it to ready — or close it.

## Troubleshooting

- Skill doesn't trigger → name it explicitly ("sweeper-implement skill" / "sweeper-plan skill"); restart Copilot CLI after the checkout gains them (skills load at session start).
- "Not agent-ready" refusal → the review found no brief to work from; check the record for what it concluded instead.
- "Needs a plan first" refusal → a *plan* record reached `sweeper-implement` without a plan file in this checkout; run `/sweeper-plan <n>` first, in the same session.
- Skills not found → check the checkout has `.github/skills/sweeper-implement/SKILL.md` and `.github/skills/sweeper-plan/SKILL.md` (pull a recent `main`); on an older checkout, copy the generated [sweeper-implement](https://egamma.github.io/vscodesweeper-state/skill/sweeper-implement/SKILL.md) and [sweeper-plan](https://egamma.github.io/vscodesweeper-state/skill/sweeper-plan/SKILL.md) SKILL.md files into `~/.copilot/skills/<name>/` or `~/.claude/skills/<name>/`.

_sweeper agent skills v7 · generated 2026-09-25 13:50 UTC._
