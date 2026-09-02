# VS Code Sweeper — Adoption

[← Home](index.html) · 19328 issues reviewed · generated 2026-09-02 13:06 UTC

## Funnel

- **Issues reviewed:** 19328
- **Close proposals:** 2553 (13% of reviewed)
- **Acted on (closed):** 631 (25% of proposals)
- **2nd-reviewed before the close:** 105 confirmed · 33 disputed · 4 unverifiable · 489 never 2nd-reviewed — the verify lanes are newer than most of these closes; the split fills in from here
- **Closed with the sweeper's comment:** 324 (51% of acted-on) — 288 verbatim, 20 inside a longer comment, 16 edited
- **Likely fixed instead:** 72 (11% of acted-on) — closed as `completed` without the sweeper's comment on a non-implemented-on-main proposal; not claimed as adoption (71 of the 306 own-wording closes fall here — those comments weren't passed over, the close had a different cause)
- **Still awaiting action:** 1922 open close proposals
- **Reversals (reopened after a close):** 1 — 0 after a close that used the sweeper's comment

_Close proposals count the whole corpus (1946 of the 19328 reviewed issues have since closed). The dashboard's `propose-close` card counts only the 1922 still open — closed records move to its ✔ closed view._

## Who acted on proposals

| User | Closures | With sweeper comment |
| --- | --- | --- |
| alexdima | 114 | 107 (94%) |
| justschen | 107 | 54 (50%) |
| vs-code-engineering | 50 | 0 (0%) |
| roblourens | 40 | 17 (43%) |
| hediet | 35 | 35 (100%) |
| lramos15 | 33 | 0 (0%) |
| kycutler | 30 | 14 (47%) |
| dmitrivMS | 26 | 0 (0%) |
| chrmarti | 20 | 19 (95%) |
| sbatten | 16 | 16 (100%) |
| benibenj | 15 | 10 (67%) |
| deepak1556 | 13 | 0 (0%) |
| aeschli | 12 | 11 (92%) |
| sandy081 | 12 | 0 (0%) |
| (unattributed) | 9 | 0 (0%) |
| egamma | 9 | 9 (100%) |
| lszomoru | 9 | 8 (89%) |
| mrleemurray | 7 | 5 (71%) |
| vritant24 | 7 | 3 (43%) |
| joshspicer | 6 | 0 (0%) |
| TylerLeonhardt | 6 | 6 (100%) |
| karthiknadig | 5 | 2 (40%) |
| pwang347 | 5 | 3 (60%) |
| bhavyaus | 4 | 4 (100%) |
| meganrogge | 4 | 0 (0%) |
| alexr00 | 3 | 0 (0%) |
| dbaeumer | 3 | 1 (33%) |
| benvillalobos | 2 | 0 (0%) |
| connor4312 | 2 | 0 (0%) |
| AbhaySanthani-tekframeworks | 1 | 0 (0%) |
| aiday-mar | 1 | 0 (0%) |
| AndrewStopchenko-SO | 1 | 0 (0%) |
| babakzarrinbal | 1 | 0 (0%) |
| BladeJoe | 1 | 0 (0%) |
| BobVul | 1 | 0 (0%) |
| bryanchen-d | 1 | 0 (0%) |
| coder-free | 1 | 0 (0%) |
| danwilhelm | 1 | 0 (0%) |
| DavidLangworthy | 1 | 0 (0%) |
| dileepyavan | 1 | 0 (0%) |
| DonJayamanne | 1 | 0 (0%) |
| dustintran333 | 1 | 0 (0%) |
| JMS-1 | 1 | 0 (0%) |
| jruales | 1 | 0 (0%) |
| Mapalmeira | 1 | 0 (0%) |
| monolithed | 1 | 0 (0%) |
| na2co3-ftw | 1 | 0 (0%) |
| Prasanna-2005 | 1 | 0 (0%) |
| romalpani | 1 | 0 (0%) |
| sanket-bhalerao | 1 | 0 (0%) |
| SimonSiefke | 1 | 0 (0%) |
| steven8274 | 1 | 0 (0%) |
| Tanishq-JM | 1 | 0 (0%) |
| trent-abc | 1 | 0 (0%) |
| ulugbekna | 1 | 0 (0%) |
| xgtxdzh | 1 | 0 (0%) |

## sweeper-fix skill adoption

Draft PRs opened with the sweeper-fix skill, discovered by `reconcile`'s seeded-by-marker search, against the corpus-wide agent-fixable pool of 1783 reviewed fix specs. As current as the last reconcile run.

| User | Agent-fixable pool | Skill PRs | Open | Merged |
| --- | --- | --- | --- | --- |
| alexdima | 63 | 2 | 2 | — |
| benibenj | 41 | 1 | — | 1 |

## Independent verification — the 2nd review

_A blinded second review of duplicate / implemented-on-main close proposals. "Disputed" is a dispute to read, not a proven error. Coverage counts open proposals; stale stamps are excluded from the mix._

- **duplicate:** 627 of 627 open proposals verified · 107 closed unverified
- **implemented-on-main:** 527 of 527 open proposals verified · 97 closed unverified
- **Verdict mix:** 869 confirmed (28 with the fix unreleased) · 393 disputed · 34 unverifiable

| 2nd-review verdict | Still open | Closed since | Reopened after a close |
| --- | --- | --- | --- |
| confirmed | 764 | 104 | 1 |
| disputed | 360 | 33 | 0 |
| unverifiable | 30 | 4 | 0 |

### Closed despite a dispute

| Issue | Closed | Who acted | 2nd-review evidence |
| --- | --- | --- | --- |
| [#277300](https://github.com/microsoft/vscode/issues/277300) Google Authentication stopped working in 1.106 | 2026-08-31 | chrmarti | A is a concrete 1.106 regression breaking Google OAuth token refresh with 'unable to get issuer certificate'; B only tracks rollout/telemetry of the experimental http.systemCertificatesNode setting, and completing it needn't fix A. |
| [#130172](https://github.com/microsoft/vscode/issues/130172) Proxy Credentials Popup not showing | 2026-08-31 | chrmarti | Commit adds proxy basic-auth lookup for extension-host requests via proxy-agent, but node and browser RequestService — the path settings sync uses — explicitly return undefined, so the reported missing sync credentials prompt persists. |
| [#292795](https://github.com/microsoft/vscode/issues/292795) "Invalid String Length" in Copilot Chat | 2026-08-31 | chrmarti | A reports 'Invalid String Length' with no images, attachments, or tool output involved and says model/mode is irrelevant; B's root cause is base64 image/binary payloads inlined into session JSONL — shared symptom, unestablished shared trigger. |
| [#299324](https://github.com/microsoft/vscode/issues/299324) Sorry, there was a network error. Please try again later. Request id: 836774d3-2064-4706-8d01-947d2a4d2cd0  Reason: Please check your firewall rules and network connection then try again. Error Code: net::ERR_HTTP2_PROTOCOL_ERROR: [object Object]. | 2026-08-31 | chrmarti | Both are symptom-only auto-reports of a generic ERR_HTTP2_PROTOCOL_ERROR on different OSes (Linux vs Windows) and extension versions; an environment-dependent network/proxy failure string alone establishes no shared root cause. |
| [#300513](https://github.com/microsoft/vscode/issues/300513) CoPilot Chat 0.39.0 is incompatible with latest VSCode 1.111.0 | 2026-08-31 | chrmarti | Different release pairings a cycle apart — B is Copilot Chat 0.38.0 against VS Code 1.110, A is 0.39.0 against 1.111 — so resolving B's version-gate mismatch would not cover A's later recurrence. |
| [#301098](https://github.com/microsoft/vscode/issues/301098) When reopening VS Code, recent chat sessions can’t be opened. | 2026-08-31 | chrmarti | Both share the symptom of a chat session not opening, but A's is transient after restarting a remote SSH window and self-heals in days, while B's persists for one specific local session across reinstall/re-auth. |
| [#303402](https://github.com/microsoft/vscode/issues/303402) Remote SSH workspace paths are handled locally in Copilot Chat UI mode, causing repeated tool failures and renderer overload | 2026-08-31 | chrmarti | B is Windows-host backslash mangling of the workspace path causing 'outside of workspace' errors and false-success writes; A is macOS-host ENOENT on correct POSIX paths plus a retry loop overloading the renderer. |
| [#328438](https://github.com/microsoft/vscode/issues/328438) Generate Commit Message not working | 2026-08-29 | dmitrivMS | Both are bare 'commit message generation produces nothing' reports on different builds (1.131.0 vs 1.130.0) with no logs, errors, or Copilot state, so no shared root cause is established beyond an identical symptom. |
| [#329339](https://github.com/microsoft/vscode/issues/329339) Commit generation personalized instruction doesn't work | 2026-08-29 | dmitrivMS | B fails with promptFiltered specifically on Japanese-language instruction text; A fails with an unprocessable-entity error on a plain ASCII English instruction — different failure signatures and triggers, not one shared root cause. |
| [#330831](https://github.com/microsoft/vscode/issues/330831) Modern UI: Some panel parts use Sidebar colors instead of Panel colors | 2026-08-28 | na2co3-ftw | The commit adds a chat customization migration hint (settings, command, storage key); it touches no paneHeader.css or modern-UI theming code, so it cannot address panel parts using sideBar color tokens. |
| [#327578](https://github.com/microsoft/vscode/issues/327578) Chats system model: New chat button position changes, resulting into annoying behavior | 2026-08-27 | romalpani | gate: the cited canonical #329321 is closed — a duplicate close would strand the report (re-review, not close) |
| [#312110](https://github.com/microsoft/vscode/issues/312110) PendingMigrationError: navigator is now a global in nodejs thrown during module load on remote VS Code server,   causing repeated renderer crashes and Remote SSH disconnections | 2026-08-27 | chrmarti | Same PendingMigrationError signature, but different offending code: A is the bundled Copilot extension touching navigator at top-level module load on the remote server; B is the Remote-SSH extension's own bundle locally — separate fixes. |
| [#331641](https://github.com/microsoft/vscode/issues/331641) J0t.clearMarks is not a function | 2026-08-27 | vs-code-engineering | Only a shared minified symptom string; neither report gives a trigger or stack, and they run different extension/VS Code builds (0.35.3/1.107.1 vs 0.48.1/1.111.0), so identical minified 'J0t' does not establish one root cause. |
| [#326199](https://github.com/microsoft/vscode/issues/326199) VS Code does not connect to tunnel after updating | 2026-08-27 | alexdima | A fails with an explicit 'Client refused: version mismatch' handshake rejection after a client-only update, whereas B updated the tunnel service first and fails with an unexplained WebSocket 1006 close — different failure mechanisms. |
| [#231128](https://github.com/microsoft/vscode/issues/231128) font ligatures that span several textmate scopes assume the font settings of last character (last component of the composite symbol) | 2026-08-27 | alexdima | B asks for a setting to suppress ligatures inside constructs like strings for readability; A reports miscolored glyphs when a ligature straddles two scopes — implementing B's opt-out wouldn't fix A's tokenization/coloring defect. |
| [#329741](https://github.com/microsoft/vscode/issues/329741) Black Screen after 10 minutes | 2026-08-27 | deepak1556 | gate: the cited canonical #261660 is closed — a duplicate close would strand the report (re-review, not close) |
| [#323592](https://github.com/microsoft/vscode/issues/323592) Agents window: "New Chat" button is a no-op from within a current session | 2026-08-26 | justschen | B documents debounce/queueing flakiness from rapid clicks plus a no-op when already on an empty New Chat; A is a no-op while inside an existing active session — different trigger state, not a shown shared cause. |
| [#327257](https://github.com/microsoft/vscode/issues/327257) Copilot Chat: file links render as broken vscode-file:// URIs instead of workspace paths | 2026-08-26 | justschen | A reports backtick content resolving to a malformed vscode-file://…/workbench.html app URI that navigates nowhere; B requests replacing optimistic symbol linkification with explicit path anchors — a design change, not that URI-resolution defect. |
| [#295956](https://github.com/microsoft/vscode/issues/295956) Right-to-Left Text Direction for some languages | 2026-08-26 | justschen | gate: open PR #314365 references the issue — someone may be fixing it; closing as duplicate is not safe |
| [#295731](https://github.com/microsoft/vscode/issues/295731) Preserve pasted screenshots in Copilot chat across IDE restarts / session reloads | 2026-08-26 | justschen | Commit only persists attachments of the empty/untitled draft input (chatSessionIsEmpty) via a separate storage memento; it does not restore images in an existing chat session's transcript, nor add the requested per-chat clear/disable persistence settings. |
| [#288926](https://github.com/microsoft/vscode/issues/288926) "Retry" removes attached context | 2026-08-26 | justschen | The diff only hoists accessor.get calls before awaits to avoid a disposed-accessor error in the retry action; it never touches request variables/attachments, so the reported loss of pinned context on retry is unaddressed. |
| [#288574](https://github.com/microsoft/vscode/issues/288574) Expanding thinking block scrolls down a bunch, scroll should be stable | 2026-08-26 | justschen | The diff only retimes auto-scroll-to-bottom inside the thinking part's own scrollable during streaming; it never anchors the outer chat list's scroll position when the user toggles expansion, the reported trigger. |
| [#286231](https://github.com/microsoft/vscode/issues/286231) Terminal inline chat has `Unknown variable type` reference | 2026-08-26 | justschen | The diff only appends the variable name to the fallback label for diagnostics; the reference still falls into the 'Unknown variable type' branch, so the reported inline-chat rendering defect remains. |
| [#284142](https://github.com/microsoft/vscode/issues/284142) Chat View Lacks Smooth Scrolling for Long Responses | 2026-08-26 | justschen | A asks for manual navigation fixes (tiny scrollbar, arrow keys jumping between prompt turns instead of scrolling); B reports auto-scroll during streaming mispositioning and stalling — different mechanisms, fixing B leaves A's keyboard/scrollbar problems. |
| [#282664](https://github.com/microsoft/vscode/issues/282664) "Start Impl" btn seems home grown | 2026-08-26 | justschen | Commit only re-plumbs plan approval to a vscode_reviewPlan tool and renames action labels; no change to the split-button's rendering, alignment, or hover-target width the report describes. |
| [#280525](https://github.com/microsoft/vscode/issues/280525) Chat response thinking is not aligning vertically in the center | 2026-08-26 | justschen | Diff is a broad thinking-UI redesign (fade masks, connector, left padding, scroll caching); nothing addresses the reported asymmetric top/bottom spacing from markdown paragraph bottom margins in the collapsed preview line. |
| [#265795](https://github.com/microsoft/vscode/issues/265795) Please Fix Shared Input and History Across Multiple Copilot Chat Sessions | 2026-08-26 | justschen | Commit only scopes up/down input history per session id; it does nothing about the report's primary defect that typed input appears simultaneously in all chat sessions. |
| [#253296](https://github.com/microsoft/vscode/issues/253296) Slight vertical jump when editing chat message | 2026-08-26 | justschen | Commit fixes an input-disposal bug and removes a hover-offset rule; neither addresses the ~5px vertical shift of a chat message when entering edit mode as reported. |
| [#252501](https://github.com/microsoft/vscode/issues/252501) Clicking to edit a copilot message flickers for ~1 frame | 2026-08-26 | justschen | Diff guards focus-outside firing while another request is already being edited and fixes inputContainer teardown on finishing edit; neither covers the reported one-frame flicker when first clicking a message to edit. |
| [#306236](https://github.com/microsoft/vscode/issues/306236) Incorrect Minimap Vertical Size | 2026-08-25 | alexdima | A reports minimap 'fit' mis-sizing constantly on any tab switch with no repro; B requires a specific trigger chain — opening then closing the terminal panel from a larger file — so the defects aren't clearly the same. |
| [#236365](https://github.com/microsoft/vscode/issues/236365) "Undo" history lost after "Save as". | 2026-08-25 | alexdima | A's body describes a plain Ctrl+S on a 180MB CSV leaving a degenerate undo stack (blank file ↔ final state), not B's Save As discarding an otherwise intact undo/redo buffer. |
| [#318485](https://github.com/microsoft/vscode/issues/318485) Replying to a past conversation results in "Input item ID does not belong to this connection: | 2026-08-19 | vs-code-engineering | A is a deterministic conversation-state bug ('Input item ID does not belong to this connection' when replying to a past chat), reproducible across retries and models — outside B's stated scope of transient/service-side request failures. |
| [#330728](https://github.com/microsoft/vscode/issues/330728) fix: filter discovered pre-existing session in session config integration tests (build fix for vscode-engineering#3607) | 2026-08-16 | sandy081 | Commit serializes AgentPluginManager cache loading; it never touches sessionConfig.integrationTest.ts's root/sessionAdded predicate, so the discovered PRE_EXISTING_SESSION_URI notification race the issue reports remains unfiltered. |

_The 393 disputed proposals are listed on the [dashboard](dashboard.html#q=verify%3Arefuted) — the link lands pre-filtered; each ✗ badge carries the verifier's evidence._

## Reversals — reopened after a close

| Issue | Reopened | Reversed close used | Who had acted |
| --- | --- | --- | --- |
| [#255890](https://github.com/microsoft/vscode/issues/255890) When you activate a source code chunk it scrolls to the top. | 2026-07-28 (closed again since) | none | justschen |

## All closures since review — context

| Review verdict | Closed |
| --- | --- |
| keep-open | 757 |
| propose-close | 631 |
| needs-info | 428 |
| route-to-area | 130 |

| Close reason | Closed |
| --- | --- |
| completed | 1005 |
| not_planned | 677 |
| duplicate | 252 |
| not_found | 12 |

## Acceptance by close reason

| Reason | Proposals | Acted on | Acceptance | With sweeper comment | Likely fixed instead |
| --- | --- | --- | --- | --- | --- |
| duplicate | 821 | 194 | 24% | 96 | 19 |
| implemented on main | 730 | 206 | 28% | 133 | — |
| as-designed | 295 | 70 | 24% | 45 | 14 |
| question | 248 | 29 | 12% | 9 | 10 |
| out-of-scope | 173 | 36 | 21% | 7 | 7 |
| not-reproducible | 135 | 25 | 19% | 8 | 8 |
| off-topic | 57 | 16 | 28% | 4 | 5 |
| caused-by-extension | 41 | 41 | 100% | 17 | 9 |
| extension-candidate | 29 | 8 | 28% | 2 | — |
| other | 21 | 5 | 24% | 3 | — |
| invalid | 3 | 1 | 33% | 0 | — |

_Only the propose-close funnel is claimed as a sweeper outcome; other closures are context._
