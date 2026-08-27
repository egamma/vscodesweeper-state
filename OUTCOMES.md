# VS Code Sweeper — Adoption

[← Home](index.html) · 18797 issues reviewed · generated 2026-08-27 11:17 UTC

## Funnel

- **Issues reviewed:** 18797
- **Close proposals:** 2617 (14% of reviewed)
- **Acted on (closed):** 497 (19% of proposals)
- **2nd-reviewed before the close:** 43 confirmed · 4 disputed · 2 unverifiable · 448 never 2nd-reviewed — the verify lanes are newer than most of these closes; the split fills in from here
- **Closed with the sweeper's comment:** 247 (50% of acted-on) — 211 verbatim, 20 inside a longer comment, 16 edited
- **Likely fixed instead:** 58 (12% of acted-on) — closed as `completed` without the sweeper's comment on a non-implemented-on-main proposal; not claimed as adoption (57 of the 249 own-wording closes fall here — those comments weren't passed over, the close had a different cause)
- **Still awaiting action:** 2120 open close proposals
- **Reversals (reopened after a close):** 1 — 0 after a close that used the sweeper's comment

_Close proposals count the whole corpus (1575 of the 18797 reviewed issues have since closed). The dashboard's `propose-close` card counts only the 2120 still open — closed records move to its ✔ closed view._

## Who acted on proposals

| User | Closures | With sweeper comment |
| --- | --- | --- |
| alexdima | 104 | 99 (95%) |
| justschen | 68 | 29 (43%) |
| vs-code-engineering | 41 | 0 (0%) |
| roblourens | 39 | 17 (44%) |
| hediet | 35 | 35 (100%) |
| lramos15 | 32 | 0 (0%) |
| kycutler | 30 | 14 (47%) |
| dmitrivMS | 17 | 0 (0%) |
| sbatten | 16 | 16 (100%) |
| aeschli | 12 | 11 (92%) |
| sandy081 | 12 | 0 (0%) |
| deepak1556 | 10 | 0 (0%) |
| vritant24 | 7 | 3 (43%) |
| (unattributed) | 6 | 0 (0%) |
| TylerLeonhardt | 6 | 6 (100%) |
| benibenj | 5 | 1 (20%) |
| joshspicer | 5 | 0 (0%) |
| karthiknadig | 5 | 2 (40%) |
| pwang347 | 5 | 3 (60%) |
| bhavyaus | 4 | 4 (100%) |
| lszomoru | 4 | 4 (100%) |
| dbaeumer | 3 | 1 (33%) |
| alexr00 | 2 | 0 (0%) |
| egamma | 2 | 2 (100%) |
| meganrogge | 2 | 0 (0%) |
| mrleemurray | 2 | 0 (0%) |
| aiday-mar | 1 | 0 (0%) |
| AndrewStopchenko-SO | 1 | 0 (0%) |
| babakzarrinbal | 1 | 0 (0%) |
| benvillalobos | 1 | 0 (0%) |
| BladeJoe | 1 | 0 (0%) |
| bryanchen-d | 1 | 0 (0%) |
| coder-free | 1 | 0 (0%) |
| connor4312 | 1 | 0 (0%) |
| danwilhelm | 1 | 0 (0%) |
| DavidLangworthy | 1 | 0 (0%) |
| dileepyavan | 1 | 0 (0%) |
| DonJayamanne | 1 | 0 (0%) |
| dustintran333 | 1 | 0 (0%) |
| jruales | 1 | 0 (0%) |
| Mapalmeira | 1 | 0 (0%) |
| Prasanna-2005 | 1 | 0 (0%) |
| sanket-bhalerao | 1 | 0 (0%) |
| SimonSiefke | 1 | 0 (0%) |
| steven8274 | 1 | 0 (0%) |
| Tanishq-JM | 1 | 0 (0%) |
| trent-abc | 1 | 0 (0%) |
| ulugbekna | 1 | 0 (0%) |
| xgtxdzh | 1 | 0 (0%) |

## sweeper-fix skill adoption

Draft PRs opened with the sweeper-fix skill, discovered by `reconcile`'s seeded-by-marker search, against the corpus-wide agent-fixable pool of 1747 reviewed fix specs. As current as the last reconcile run.

| User | Agent-fixable pool | Skill PRs | Open | Merged |
| --- | --- | --- | --- | --- |
| alexdima | 62 | 2 | 2 | — |
| benibenj | 41 | 1 | — | 1 |

## Independent verification — the 2nd review

_A blinded second review of duplicate / implemented-on-main close proposals. "Disputed" is a dispute to read, not a proven error. Coverage counts open proposals; stale stamps are excluded from the mix._

- **duplicate:** 657 of 657 open proposals verified · 107 closed unverified
- **implemented-on-main:** 559 of 559 open proposals verified · 97 closed unverified
- **Verdict mix:** 846 confirmed (28 with the fix unreleased) · 385 disputed · 34 unverifiable

| 2nd-review verdict | Still open | Closed since | Reopened after a close |
| --- | --- | --- | --- |
| confirmed | 802 | 43 | 1 |
| disputed | 381 | 4 | 0 |
| unverifiable | 32 | 2 | 0 |

### Closed despite a dispute

| Issue | Closed | Who acted | 2nd-review evidence |
| --- | --- | --- | --- |
| [#306236](https://github.com/microsoft/vscode/issues/306236) Incorrect Minimap Vertical Size | 2026-08-25 | alexdima | A reports minimap 'fit' mis-sizing constantly on any tab switch with no repro; B requires a specific trigger chain — opening then closing the terminal panel from a larger file — so the defects aren't clearly the same. |
| [#236365](https://github.com/microsoft/vscode/issues/236365) "Undo" history lost after "Save as". | 2026-08-25 | alexdima | A's body describes a plain Ctrl+S on a 180MB CSV leaving a degenerate undo stack (blank file ↔ final state), not B's Save As discarding an otherwise intact undo/redo buffer. |
| [#318485](https://github.com/microsoft/vscode/issues/318485) Replying to a past conversation results in "Input item ID does not belong to this connection: | 2026-08-19 | vs-code-engineering | A is a deterministic conversation-state bug ('Input item ID does not belong to this connection' when replying to a past chat), reproducible across retries and models — outside B's stated scope of transient/service-side request failures. |
| [#330728](https://github.com/microsoft/vscode/issues/330728) fix: filter discovered pre-existing session in session config integration tests (build fix for vscode-engineering#3607) | 2026-08-16 | sandy081 | Commit serializes AgentPluginManager cache loading; it never touches sessionConfig.integrationTest.ts's root/sessionAdded predicate, so the discovered PRE_EXISTING_SESSION_URI notification race the issue reports remains unfiltered. |

_The 385 disputed proposals are listed on the [dashboard](dashboard.html#q=verify%3Arefuted) — the link lands pre-filtered; each ✗ badge carries the verifier's evidence._

## Reversals — reopened after a close

| Issue | Reopened | Reversed close used | Who had acted |
| --- | --- | --- | --- |
| [#255890](https://github.com/microsoft/vscode/issues/255890) When you activate a source code chunk it scrolls to the top. | 2026-07-28 | none | justschen |

## All closures since review — context

| Review verdict | Closed |
| --- | --- |
| keep-open | 610 |
| propose-close | 497 |
| needs-info | 380 |
| route-to-area | 88 |

| Close reason | Closed |
| --- | --- |
| completed | 794 |
| not_planned | 600 |
| duplicate | 174 |
| not_found | 7 |

## Acceptance by close reason

| Reason | Proposals | Acted on | Acceptance | With sweeper comment | Likely fixed instead |
| --- | --- | --- | --- | --- | --- |
| duplicate | 794 | 137 | 17% | 57 | 15 |
| implemented on main | 726 | 170 | 23% | 109 | — |
| as-designed | 284 | 59 | 21% | 40 | 10 |
| question | 240 | 26 | 11% | 8 | 9 |
| caused-by-extension | 214 | 40 | 19% | 16 | 9 |
| not-reproducible | 133 | 21 | 16% | 6 | 6 |
| out-of-scope | 116 | 18 | 16% | 4 | 4 |
| off-topic | 57 | 14 | 25% | 2 | 5 |
| extension-candidate | 30 | 6 | 20% | 2 | — |
| other | 21 | 5 | 24% | 3 | — |
| invalid | 2 | 1 | 50% | 0 | — |

_Only the propose-close funnel is claimed as a sweeper outcome; other closures are context._
