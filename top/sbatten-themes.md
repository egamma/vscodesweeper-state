# Top issues by theme — sbatten

Experimental themed view of [the flat ranking](sbatten.md); themes assigned by the review engine. Rank/score are the lane-wide values. Generated 2026-07-26 07:23 UTC.

## Bugs

### Windows and recents (4)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | [#137638](https://github.com/microsoft/vscode/issues/137638) | VSCode opens the wrong folder in Windows 10 start menu when there are folders with the same name | 0 | correctness | 4/6 Traced | 100 | yes | `npm run implement -- --issue 137638` |
| 3 | [#117037](https://github.com/microsoft/vscode/issues/117037) | Files open in wrong window | 1 | correctness | 3/6 Plausible | 86 | — | `npm run implement -- --issue 117037` |
| 31 | [#196054](https://github.com/microsoft/vscode/issues/196054) | recent project menu on small window is too wide | 0 | papercut | 4/6 Traced | 9 | — | `npm run implement -- --issue 196054` |
| 54 | [#170799](https://github.com/microsoft/vscode/issues/170799) | 'Open recent' menu takes up full width of the window when it contains an entry with very long path | 0 | visual | 4/6 Traced | 0 | yes | `npm run implement -- --issue 170799` |

### Workspace trust (12)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2 | [#122293](https://github.com/microsoft/vscode/issues/122293) | Workspace Trust - Workspace file save location very slow to be added to workspace trust | 1 | perf | 3/6 Plausible | 97 | — | `npm run implement -- --issue 122293` |
| 8 | [#126636](https://github.com/microsoft/vscode/issues/126636) | Workspace Trust - Restricted mode causes test failures | 8 | papercut | — | 52 | — | `npm run implement -- --issue 126636` |
| 10 | [#200682](https://github.com/microsoft/vscode/issues/200682) | Connecting to Live Share session causes NPE in workspace trust subsystem | 2 | correctness | 4/6 Traced | 49 | yes | `npm run implement -- --issue 200682` |
| 22 | [#170442](https://github.com/microsoft/vscode/issues/170442) | Trusted domain dialog in web doesn't return focus to previously clicked element when canceled. | 0 | papercut | 4/6 Traced | 24 | — | `npm run implement -- --issue 170442` |
| 24 | [#124182](https://github.com/microsoft/vscode/issues/124182) | Workspace Trust - Extension Development Host | 1 | correctness | 4/6 Traced | 21 | — | `npm run implement -- --issue 124182` |
| 35 | [#172212](https://github.com/microsoft/vscode/issues/172212) | Clicking anywhere hides modal dialog about untrusted link | 0 | papercut | 3/6 Plausible | 8 | — | `npm run implement -- --issue 172212` |
| 40 | [#316859](https://github.com/microsoft/vscode/issues/316859) | MCP workspace configuration processed in Restricted Mode — Workspace Trust boundary violation | 0 | none | 2/6 Unverified | 5 | — | — |
| 41 | [#125093](https://github.com/microsoft/vscode/issues/125093) | Trust: dialogs should listen to changes | 0 | correctness | 5/6 Source-confirmed | 4 | yes | `npm run implement -- --issue 125093` |
| 49 | [#127614](https://github.com/microsoft/vscode/issues/127614) | Trusted uris: added uri should be focused | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 127614` |
| 50 | [#131746](https://github.com/microsoft/vscode/issues/131746) | Workspace trust header shadow doesn't show up if you tab through file | 0 | visual | 4/6 Traced | 0 | yes | `npm run implement -- --issue 131746` |
| 53 | [#170664](https://github.com/microsoft/vscode/issues/170664) | Workspace Trust - icon on the status bar cannot be pinned and always resets the state after a restart | 0 | papercut | 5/6 Source-confirmed | 0 | — | — |
| 59 | [#197989](https://github.com/microsoft/vscode/issues/197989) | Workspace Trust - Untrusted files don't open in the same window via Open Recent | 0 | correctness | 4/6 Traced | 0 | — | `npm run implement -- --issue 197989` |

### Menus and dropdowns (19)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 4 | [#300048](https://github.com/microsoft/vscode/issues/300048) | Keine Menüoptionen verfügbar! | 0 | correctness | 3/6 Plausible | 86 | — | `npm run implement -- --issue 300048` |
| 5 | [#143826](https://github.com/microsoft/vscode/issues/143826) | dropdown button sometimes doesn't respond after being toggled | 0 | correctness | 2/6 Unverified | 62 | — | — |
| 6 | [#210410](https://github.com/microsoft/vscode/issues/210410) | editor/title/run doesn't always switch the default action when selected from dropdown | 3 | papercut | 5/6 Source-confirmed | 59 | — | `npm run implement -- --issue 210410` |
| 9 | [#201613](https://github.com/microsoft/vscode/issues/201613) | Alt Shortcuts Don't Work Properly With Top Activity Bar | 0 | visual | 5/6 Source-confirmed | 51 | — | `npm run implement -- --issue 201613` |
| 12 | [#206365](https://github.com/microsoft/vscode/issues/206365) | Menubar disappears, wrong fullscreen detection | 0 | correctness | 5/6 Source-confirmed | 45 | yes | `npm run implement -- --issue 206365` |
| 14 | [#309403](https://github.com/microsoft/vscode/issues/309403) | Delayed readyness of the VScode menus after reloading window | 0 | none | 3/6 Plausible | 40 | — | — |
| 17 | [#317715](https://github.com/microsoft/vscode/issues/317715) | VSCode menu is behind editing window | 1 | none | 3/6 Plausible | 37 | — | — |
| 18 | [#110594](https://github.com/microsoft/vscode/issues/110594) | Mouse positions influences initial selection on menus | 4 | papercut | 5/6 Source-confirmed | 34 | yes | `npm run implement -- --issue 110594` |
| 27 | [#105559](https://github.com/microsoft/vscode/issues/105559) | Windows Magnifier not following active menuitem | 0 | papercut | 3/6 Plausible | 12 | — | `npm run implement -- --issue 105559` |
| 32 | [#99121](https://github.com/microsoft/vscode/issues/99121) | Custom menus should absorb keystrokes and dismiss if not mnemonic (letter) | 0 | papercut | 4/6 Traced | 8 | yes | `npm run implement -- --issue 99121` |
| 33 | [#154258](https://github.com/microsoft/vscode/issues/154258) | Menu appears below quick pick | 0 | visual | 2/6 Unverified | 8 | — | `npm run implement -- --issue 154258` |
| 34 | [#160894](https://github.com/microsoft/vscode/issues/160894) | `Auto Save` menu state not updated properly (vscode-web) | 0 | visual | 5/6 Source-confirmed | 8 | yes | `npm run implement -- --issue 160894` |
| 36 | [#148158](https://github.com/microsoft/vscode/issues/148158) | Prevent menu selection from static mouse hover | 0 | papercut | 5/6 Source-confirmed | 5 | yes | `npm run implement -- --issue 148158` |
| 37 | [#157545](https://github.com/microsoft/vscode/issues/157545) | Hover indication can stuck on multiple submenu options in main menu | 0 | visual | 4/6 Traced | 5 | yes | `npm run implement -- --issue 157545` |
| 42 | [#144216](https://github.com/microsoft/vscode/issues/144216) | Cannot open menu via shortcut when activity bar is hidden | 0 | correctness | 4/6 Traced | 4 | yes | `npm run implement -- --issue 144216` |
| 51 | [#133143](https://github.com/microsoft/vscode/issues/133143) | Prevent custom menu dismissal when being updated on startup | 0 | papercut | 2/6 Unverified | 0 | — | — |
| 58 | [#179235](https://github.com/microsoft/vscode/issues/179235) | Menu is getting stale | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 179235` |
| 60 | [#200487](https://github.com/microsoft/vscode/issues/200487) | vscode menus become disabled | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 61 | [#211646](https://github.com/microsoft/vscode/issues/211646) | Certain Edit menus should not be active without a selection (macOS) | 0 | papercut | 4/6 Traced | 0 | — | `npm run implement -- --issue 211646` |

### Agent tooling (4)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 7 | [#239129](https://github.com/microsoft/vscode/issues/239129) | vscode is not respecting users choice to not be part of the experiments. | 0 | correctness | 3/6 Plausible | 59 | — | — |
| 15 | [#292154](https://github.com/microsoft/vscode/issues/292154) | switchAgent tool is pretty frustrating with 5.2 codex | 1 | papercut | 3/6 Plausible | 39 | — | `npm run implement -- --issue 292154` |
| 25 | [#291694](https://github.com/microsoft/vscode/issues/291694) | switch_agent -> Plan overly called for seemingly unambigous prompt: Add HELLO to HELLO.txt. | 0 | correctness | 4/6 Traced | 18 | — | `npm run implement -- --issue 291694` |
| 43 | [#317274](https://github.com/microsoft/vscode/issues/317274) | Intent service returns decode_failed due to malformed JSON | 0 | papercut | 3/6 Plausible | 4 | — | `npm run implement -- --issue 317274` |

### Dialogs and widgets (7)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 11 | [#114662](https://github.com/microsoft/vscode/issues/114662) | Dialogs should have max height | 1 | visual | 2/6 Unverified | 45 | — | — |
| 19 | [#153267](https://github.com/microsoft/vscode/issues/153267) | Cannot right click on command palette-like panels | 1 | papercut | 5/6 Source-confirmed | 31 | yes | `npm run implement -- --issue 153267` |
| 29 | [#190038](https://github.com/microsoft/vscode/issues/190038) | layout or display issue | 0 | visual | 4/6 Traced | 12 | yes | `npm run implement -- --issue 190038` |
| 30 | [#174900](https://github.com/microsoft/vscode/issues/174900) | Quick Pick: Images in the tooltip confuse the layout | 0 | visual | 3/6 Plausible | 9 | — | `npm run implement -- --issue 174900` |
| 46 | [#175890](https://github.com/microsoft/vscode/issues/175890) | v1.76 ZoneWidget right-click context is affected by sash and scrollbar | 0 | papercut | 5/6 Source-confirmed | 3 | — | `npm run implement -- --issue 175890` |
| 47 | [#128233](https://github.com/microsoft/vscode/issues/128233) | Custom dialog removes leading whitespace from lines | 0 | visual | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 128233` |
| 52 | [#165454](https://github.com/microsoft/vscode/issues/165454) | Context widgets are not aware of Window Controls Overlay (WCO) | 0 | visual | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 165454` |

### Views and panels (8)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 13 | [#140647](https://github.com/microsoft/vscode/issues/140647) | Activity bar activity indicator is `1px` but configured as `2px` | 0 | visual | 6/6 Confirmed | 44 | — | `npm run implement -- --issue 140647` |
| 16 | [#183055](https://github.com/microsoft/vscode/issues/183055) | Terminal panel layout wrong at certain sizes | 0 | visual | 3/6 Plausible | 38 | — | — |
| 20 | [#147394](https://github.com/microsoft/vscode/issues/147394) | Unable to drag views to reorder or move to different pane | 0 | correctness | 3/6 Plausible | 27 | — | `npm run implement -- --issue 147394` |
| 21 | [#198540](https://github.com/microsoft/vscode/issues/198540) | "View: Show GitHub" keyboard shortcut focuses wrong activity view | 0 | papercut | 5/6 Source-confirmed | 27 | — | `npm run implement -- --issue 198540` |
| 39 | [#176142](https://github.com/microsoft/vscode/issues/176142) | Activitybar input gets captured by file explorer | 0 | correctness | 3/6 Plausible | 5 | — | — |
| 55 | [#171119](https://github.com/microsoft/vscode/issues/171119) | Hidden panels create actions that are disposed of on startup | 0 | perf | 4/6 Traced | 0 | yes | `npm run implement -- --issue 171119` |
| 56 | [#171187](https://github.com/microsoft/vscode/issues/171187) | Reset Menu doesn't show up when all items are visible, even if some are hidden by default | 0 | papercut | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 171187` |
| 57 | [#178078](https://github.com/microsoft/vscode/issues/178078) | ViewPane saveState is not called before view is disposed | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 178078` |

### Remote sessions (3)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 23 | [#196206](https://github.com/microsoft/vscode/issues/196206) | 'Disconnect' option doesn't show in Call-Stack Session in debugger | 0 | visual | 2/6 Unverified | 24 | — | — |
| 44 | [#320549](https://github.com/microsoft/vscode/issues/320549) | Remote connection locks other windows, no2 | 0 | papercut | 3/6 Plausible | 4 | — | — |
| 48 | [#122609](https://github.com/microsoft/vscode/issues/122609) | Full remote label only shown for the current remote | 0 | visual | 4/6 Traced | 0 | — | `npm run implement -- --issue 122609` |

### Platform integration (3)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 26 | [#192847](https://github.com/microsoft/vscode/issues/192847) | env.machineId will return vmware adapter's mac | 0 | correctness | 4/6 Traced | 16 | yes | `npm run implement -- --issue 192847` |
| 28 | [#119913](https://github.com/microsoft/vscode/issues/119913) | Custom file save dialog keyboard shortcuts inconsistent with macOS | 0 | papercut | 4/6 Traced | 12 | — | `npm run implement -- --issue 119913` |
| 62 | [#298499](https://github.com/microsoft/vscode/issues/298499) | Microsoft (Windows) Store info for VS Code and VS Code Insiders are stale and missing info | 0 | papercut | — | 0 | — | `npm run implement -- --issue 298499` |

### Runtime errors (2)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 38 | [#175501](https://github.com/microsoft/vscode/issues/175501) | Uncaught TypeError: Z.reject is not a function | 0 | correctness | 4/6 Traced | 5 | — | `npm run implement -- --issue 175501` |
| 45 | [#173508](https://github.com/microsoft/vscode/issues/173508) | Cannot read properties of undefined (reading 'uri') | 0 | papercut | 2/6 Unverified | 3 | — | — |

## Feature requests

### Layout controls (4)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | [#174616](https://github.com/microsoft/vscode/issues/174616) | Allow adjusting search text box width in title bar to accommodate long path and file names. | 69 | backlog-candidate | 100 | `npm run implement -- --issue 174616` |
| 6 | [#204250](https://github.com/microsoft/vscode/issues/204250) | Allow for sidebar panes to collapse downwards | 5 | dormant | 8 | `npm run implement -- --issue 204250` |
| 12 | [#171032](https://github.com/microsoft/vscode/issues/171032) | Command Center does not work well with default window title | 1 | active | 6 | — |
| 29 | [#206685](https://github.com/microsoft/vscode/issues/206685) | Toggle between minimal / default size for VS Code sidebar and last custom size. | 0 | dormant | 0 | `npm run implement -- --issue 206685` |

### Workspace trust (7)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 3 | [#126311](https://github.com/microsoft/vscode/issues/126311) | Workspace Trust - Declared Untrusted Folders | 48 | backlog-candidate | 80 | `npm run implement -- --issue 126311` |
| 9 | [#289899](https://github.com/microsoft/vscode/issues/289899) | Don't ask to enable workspace trust in system folders and temp directories | 0 | dormant | 7 | `npm run implement -- --issue 289899` |
| 19 | [#204893](https://github.com/microsoft/vscode/issues/204893) | Allow globally disabling extensions from withinn an untrusted workspace | 0 | dormant | 2 | `npm run implement -- --issue 204893` |
| 21 | [#174823](https://github.com/microsoft/vscode/issues/174823) | Workspace Trust - should be made accessible more easily. | 0 | backlog-candidate | 1 | `npm run implement -- --issue 174823` |
| 25 | [#125098](https://github.com/microsoft/vscode/issues/125098) | Trust editor: should allow multi-select of folders from the dialog | 0 | backlog-candidate | 0 | `npm run implement -- --issue 125098` |
| 26 | [#152003](https://github.com/microsoft/vscode/issues/152003) | VirtualFileSystem Workspace Trust API | 0 | backlog-candidate | 0 | `npm run implement -- --issue 152003` |
| 30 | [#291933](https://github.com/microsoft/vscode/issues/291933) | Default Trusted folders on various platforms | 0 | backlog-candidate | 0 | `npm run implement -- --issue 291933` |

### Menus and commands (6)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 4 | [#208482](https://github.com/microsoft/vscode/issues/208482) | Allow icons in menus | 39 | dormant | 72 | `npm run implement -- --issue 208482` |
| 10 | [#1792](https://github.com/microsoft/vscode/issues/1792) | Proposal: Add mnemonics to context menu items | 5 | active | 6 | `npm run implement -- --issue 1792` |
| 11 | [#55440](https://github.com/microsoft/vscode/issues/55440) | Disable undo menu item when there is no more history available | 4 | backlog-candidate | 6 | `npm run implement -- --issue 55440` |
| 13 | [#207492](https://github.com/microsoft/vscode/issues/207492) | Extension-contributable top-level menus | 3 | dormant | 5 | `npm run implement -- --issue 207492` |
| 20 | [#107068](https://github.com/microsoft/vscode/issues/107068) | Add support for new `editor.renderWhitespace` in the View menu | 1 | backlog-candidate | 1 | — |
| 27 | [#172387](https://github.com/microsoft/vscode/issues/172387) | Terminal ... menu doesn't promote action when there's only one action | 0 | active | 0 | `npm run implement -- --issue 172387` |

### Release quality (4)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 5 | [#314803](https://github.com/microsoft/vscode/issues/314803) | Feature request: Improve release-readiness traceability from pull requests to Stable | 14 | backlog-candidate | 28 | `npm run implement -- --issue 314803` |
| 14 | [#314317](https://github.com/microsoft/vscode/issues/314317) | Proposal: Stable Preview channel + first-class feature gates for progressive rollout | 1 | active | 4 | `npm run implement -- --issue 314317` |
| 32 | [#314601](https://github.com/microsoft/vscode/issues/314601) | Introduce a structured regression reporting channel for the Insiders build | 0 | active | 0 | — |
| 33 | [#314606](https://github.com/microsoft/vscode/issues/314606) | Telemetry-based quality gates for Stable release promotion | 0 | active | 0 | `npm run implement -- --issue 314606` |

### Extension APIs (4)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 7 | [#145696](https://github.com/microsoft/vscode/issues/145696) | Expose checkbox in extension dialog API | 3 | backlog-candidate | 8 | `npm run implement -- --issue 145696` |
| 8 | [#185362](https://github.com/microsoft/vscode/issues/185362) | Allow extensions to opt-out of having a "contextualTitle" for a view | 5 | backlog-candidate | 7 | `npm run implement -- --issue 185362` |
| 24 | [#117822](https://github.com/microsoft/vscode/issues/117822) | [product icon themes] theme icons support for vscode.show(Information\|Warning\|Error)Message | 0 | backlog-candidate | 0 | `npm run implement -- --issue 117822` |
| 28 | [#180582](https://github.com/microsoft/vscode/issues/180582) | Proposal: Canonical URI identity provider | 0 | dormant | 0 | `npm run implement -- --issue 180582` |

### Chat models (6)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 15 | [#276145](https://github.com/microsoft/vscode/issues/276145) | Remove intent detection from agentic ask | 0 | active | 4 | `npm run implement -- --issue 276145` |
| 17 | [#308013](https://github.com/microsoft/vscode/issues/308013) | Web search tool is never used | 0 | backlog-candidate | 3 | `npm run implement -- --issue 308013` |
| 18 | [#314971](https://github.com/microsoft/vscode/issues/314971) | Add visibility/hidden flag to LanguageModelChatInformation to control Model Picker disclosure | 1 | active | 2 | — |
| 22 | [#296243](https://github.com/microsoft/vscode/issues/296243) | Handle rate limit errors more gracefully | 0 | active | 1 | `npm run implement -- --issue 296243` |
| 23 | [#315079](https://github.com/microsoft/vscode/issues/315079) | Improve communication for continuation options based on past usage | 0 | backlog-candidate | 1 | `npm run implement -- --issue 315079` |
| 31 | [#314032](https://github.com/microsoft/vscode/issues/314032) | LLM Chat completions being used  for UI decoration / title generation/ Progress Messages | 0 | active | 0 | `npm run implement -- --issue 314032` |

### Other (2)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 2 | [#61793](https://github.com/microsoft/vscode/issues/61793) | MSIX installer | 81 | backlog-candidate | 99 | `npm run implement -- --issue 61793` |
| 16 | [#164014](https://github.com/microsoft/vscode/issues/164014) | window.zoomLevel causing blurry canvas | 3 | backlog-candidate | 3 | `npm run implement -- --issue 164014` |
