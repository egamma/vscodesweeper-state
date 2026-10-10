# vscodesweeper-state

State repository for [vscodesweeper](https://github.com/egamma/vscodesweeper) — a proposal-only issue-review tool for microsoft/vscode and a small family of related repositories.

## What is here

- **`state` branch** — the review ledger: one Markdown record per reviewed issue under `records/<owner>/<repo>/items/<n>.md` (YAML frontmatter with the verdict, then evidence, reasoning and the proposed comment), plus `meta/sweep-log.jsonl`, one line per nightly run.
- **`main` branch** — the published artifacts: the JSON data contracts the VS Code team's internal tooling (vscode-tools) renders (`targets.json`, `index-<repo>.json`, `report-adoption[-<repo>].json`, `report-verdicts.json`), the public review policy under `policy/`, the agent skills under `skill/` with their getting-started page, and frozen evidence snapshots under `evidence/`.

The dashboard and report pages that used to be served from this repository's GitHub Pages site retired on 2026-10-10; their paths serve a short notice. The surface is now vscode-tools, which is team-internal.

## How to read a record

The frontmatter carries the verdict (`triageAction`, `proposedLabel`, `closeReason`, `confidence`, `agentReadiness`), the freshness hashes the sweeper re-reviews on, and the lifecycle stamps added after the review (whether and how the issue was closed, whether the proposed comment was used, the independent second review of a close proposal). The sections below it hold the evidence, the reasoning and the proposed comment.

Nothing here is applied to any reviewed repository automatically. A verdict is a proposal; every outward action is a human maintainer's, under their own identity.

Feedback on a verdict: open an issue here with the [feedback form](https://github.com/egamma/vscodesweeper-state/issues/new?template=feedback.yml) — plain item numbers only, never issue links.
