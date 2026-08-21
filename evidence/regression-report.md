> Preserved snapshot of `out/regression/regression-report.md`, generated
> 2026-08-20 — the current review prompt (after the 2026-08-15 fixedRelease
> change) re-reviewing a 20-issue mixed sample and diffing each verdict against
> that record's baseline review. Linked from the blog post as an illustration
> of the prompt regression check; `out/` is gitignored, this copy is durable.

# Regression report

- Target: `microsoft/vscode` · baseline `egamma/vscodesweeper-state@state`
- Engine: per-record baseline engine
- Sample: 20 (mix) · checkout=yes

| # | triage b→n | label b→n | conf b→n | autofix b→n |
|---|-----------|-----------|----------|-------------|
| 127 | keep-open | none | **0.95→0.96** | false |
| 586 | propose-close | none | **0.94→0.93** | false |
| 139538 | keep-open | none | **0.85→0.92** | false |
| 164929 | keep-open | none | **0.82→0.89** | **true→false** |
| 188594 | keep-open | none | **0.8→0.88** | false |
| 209017 | propose-close | *as-designed | **0.94→0.9** | false |
| 228796 | keep-open | none | **0.85→0.78** | false |
| 243868 | needs-info | info-needed | **0.78→0.88** | false |
| 258246 | keep-open | none | **0.72→0.84** | false |
| 273677 | needs-info | info-needed | **0.8→0.84** | false |
| 283382 | keep-open | none | **0.85→0.9** | false |
| 288598 | needs-info | info-needed | **0.78→0.94** | false |
| 297261 | **keep-open→route-to-area** | **none→bug** | **0.82→0.92** | true |
| 302257 | keep-open | none | **0.6→0.9** | false |
| 305100 | **needs-info→propose-close** | **info-needed→none** | **0.82→0.91** | false |
| 312278 | keep-open | none | **0.85→0.94** | **true→false** |
| 318100 | propose-close | ***not-reproducible→none** | **0.82→0.96** | false |
| 318766 | keep-open | none | **0.85→0.93** | false |
| 324224 | needs-info | info-needed | **0.78→0.82** | false |
| 328356 | propose-close | *duplicate | **0.99→0.98** | false |

## Summary

- Compared: 20/20
- Decision flips — triage: **2** (297261, 305100)
- Label flips: **3** (297261, 305100, 318100)
- autoFixable flips: **2** (164929, 312278)
- Confidence noise floor (steady-decision issues): mean ±0.079, max ±0.300
  — treat confidence moves under this as noise, not signal.

_Proposal-only regression check. Decision flips warrant reading the record reasoning to judge improvement vs regression._
