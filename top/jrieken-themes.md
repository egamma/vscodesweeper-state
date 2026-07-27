# Top issues by theme — jrieken

Experimental themed view of [the flat ranking](jrieken.md); themes assigned by the review engine. Rank/score are the lane-wide values. Generated 2026-07-27 21:48 UTC.

## Bugs

### Editor disposal errors (8)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | [#210947](https://github.com/microsoft/vscode/issues/210947) | AbstractContextKeyService has been disposed | 1 | correctness | 5/6 Source-confirmed | 100 | — | `npm run implement -- --issue 210947` |
| 6 | [#310777](https://github.com/microsoft/vscode/issues/310777) | [Error] unhandlederror-AbstractContextKeyService has been disposed | 0 | correctness | 5/6 Source-confirmed | 44 | yes | `npm run implement -- --issue 310777` |
| 30 | [#144562](https://github.com/microsoft/vscode/issues/144562) | Assertion Failed: argument is undefined or null | 0 | correctness | 4/6 Traced | 5 | yes | `npm run implement -- --issue 144562` |
| 54 | [#154758](https://github.com/microsoft/vscode/issues/154758) | Error: unknown text editor | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 154758` |
| 55 | [#160573](https://github.com/microsoft/vscode/issues/160573) | WebSocket is not open: readyState 3 (CLOSED) | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 160573` |
| 56 | [#161063](https://github.com/microsoft/vscode/issues/161063) | Cannot read properties of null (reading 'startLineNumber') | 0 | correctness | 4/6 Traced | 0 | yes | `npm run implement -- --issue 161063` |
| 58 | [#187457](https://github.com/microsoft/vscode/issues/187457) | file:///c%<REDACTED: user-file-path> <REDACTED: user-file-path> does not exist and can not be deleted | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 187457` |
| 62 | [#212720](https://github.com/microsoft/vscode/issues/212720) | Illegal value for lineNumber | 0 | correctness | 2/6 Unverified | 0 | — | — |

### Suggest and completions (23)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2 | [#240244](https://github.com/microsoft/vscode/issues/240244) | Setting `editor.suggest.localityBonus` is not used | 10 | correctness | 5/6 Source-confirmed | 93 | yes | `npm run implement -- --issue 240244` |
| 7 | [#134013](https://github.com/microsoft/vscode/issues/134013) | Code completion unexpectedly consumes closing paren (from auto-closing-brackets) that was inserted automatically when `(` triggered code completion | 2 | correctness | 5/6 Source-confirmed | 35 | — | `npm run implement -- --issue 134013` |
| 8 | [#251013](https://github.com/microsoft/vscode/issues/251013) | Incorrect `editor.suggest.showWords` replacements for completion items if an LSP response takes too long | 0 | correctness | 6/6 Confirmed | 30 | — | `npm run implement -- --issue 251013` |
| 11 | [#246857](https://github.com/microsoft/vscode/issues/246857) | Markdown inside of CompletionItem documentation does not wrap text in code block | 1 | visual | 5/6 Source-confirmed | 25 | yes | `npm run implement -- --issue 246857` |
| 13 | [#188162](https://github.com/microsoft/vscode/issues/188162) | Completion list is not filtered correctly when typing a number after a hyphen | 1 | correctness | 5/6 Source-confirmed | 17 | yes | `npm run implement -- --issue 188162` |
| 20 | [#262227](https://github.com/microsoft/vscode/issues/262227) | The json editor stops completing values after the character `+` is used | 1 | correctness | 5/6 Source-confirmed | 10 | yes | `npm run implement -- --issue 262227` |
| 23 | [#108150](https://github.com/microsoft/vscode/issues/108150) | Inconsistencies with Trigger (full) completions when (incomplete) completions are already active | 0 | correctness | 3/6 Plausible | 8 | — | — |
| 29 | [#295537](https://github.com/microsoft/vscode/issues/295537) | Icons in autocomplete are not scaled when font-size is changed by user | 1 | visual | 5/6 Source-confirmed | 5 | yes | `npm run implement -- --issue 295537` |
| 31 | [#217387](https://github.com/microsoft/vscode/issues/217387) | Language type icon overriding file autocompletion | 0 | visual | 5/6 Source-confirmed | 5 | yes | `npm run implement -- --issue 217387` |
| 33 | [#272090](https://github.com/microsoft/vscode/issues/272090) | Suggest triggers when deleting code | 0 | papercut | 5/6 Source-confirmed | 5 | — | `npm run implement -- --issue 272090` |
| 34 | [#187779](https://github.com/microsoft/vscode/issues/187779) | Suggest widget gets orphaned in editor | 0 | visual | 6/6 Confirmed | 4 | yes | `npm run implement -- --issue 187779` |
| 38 | [#245401](https://github.com/microsoft/vscode/issues/245401) | When the UI is zoomed in (higher than 100% level) the autocomplete tooltip sometimes completely covers the code I'm writing | 0 | visual | 6/6 Confirmed | 3 | — | `npm run implement -- --issue 245401` |
| 41 | [#236980](https://github.com/microsoft/vscode/issues/236980) | suggestion widget focus ,but can't use page down or ↓,it can't work nomally | 1 | papercut | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 236980` |
| 44 | [#110069](https://github.com/microsoft/vscode/issues/110069) | Suggestion details shown on the left of suggestion list hide text and cursor | 0 | visual | — | 1 | — | — |
| 47 | [#160951](https://github.com/microsoft/vscode/issues/160951) | Accepting completion with multiline edits makes editor scroll jump higher | 0 | visual | 4/6 Traced | 1 | — | `npm run implement -- --issue 160951` |
| 49 | [#170491](https://github.com/microsoft/vscode/issues/170491) | VSCode does not remember the size of the suggest widget when the size is reset with double click | 0 | papercut | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 170491` |
| 50 | [#187147](https://github.com/microsoft/vscode/issues/187147) | fuzzyScore boostFullMatch:false incorrect when pattern ends with uppercase | 0 | correctness | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 187147` |
| 51 | [#234588](https://github.com/microsoft/vscode/issues/234588) | Not displaying completion items with empty string text labels | 0 | correctness | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 234588` |
| 52 | [#284229](https://github.com/microsoft/vscode/issues/284229) | Unexpected sort in completions | 0 | papercut | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 284229` |
| 53 | [#316100](https://github.com/microsoft/vscode/issues/316100) | The Auto Completion Just Gets In The Way. | 0 | none | 3/6 Plausible | 1 | — | — |
| 59 | [#196665](https://github.com/microsoft/vscode/issues/196665) | Cannot read properties of undefined (reading 'completion') | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 196665` |
| 60 | [#196666](https://github.com/microsoft/vscode/issues/196666) | Cannot read properties of undefined (reading 'tooltip') | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 196666` |
| 65 | [#276677](https://github.com/microsoft/vscode/issues/276677) | Top suggestion item unclickable when IntelliSense list reaches top of editor window | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 276677` |

### Chat editing (6)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 3 | [#312810](https://github.com/microsoft/vscode/issues/312810) | [Error] [GitHub.copilot-chat] unhandlederror-Response stream has been closed | 0 | correctness | 5/6 Source-confirmed | 60 | — | `npm run implement -- --issue 312810` |
| 9 | [#313179](https://github.com/microsoft/vscode/issues/313179) | Copilot chat showing file changes makes whole vscode slow | 0 | perf | 3/6 Plausible | 29 | — | — |
| 12 | [#312380](https://github.com/microsoft/vscode/issues/312380) | [Error] unhandlederror-Cannot access a disposed editing session | 0 | correctness | 5/6 Source-confirmed | 21 | yes | `npm run implement -- --issue 312380` |
| 14 | [#254884](https://github.com/microsoft/vscode/issues/254884) | Edits toolbar goes on top of Open Merge Editor blue button | 0 | visual | 5/6 Source-confirmed | 17 | — | `npm run implement -- --issue 254884` |
| 22 | [#315085](https://github.com/microsoft/vscode/issues/315085) | Ctrl+I shortcut (Inline Chat) defaults to Sidebar Chat after first use of Chat View | 1 | none | 5/6 Source-confirmed | 9 | — | — |
| 43 | [#247046](https://github.com/microsoft/vscode/issues/247046) | Accessible diff view become blank after accepting the change that agent made | 0 | visual | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 247046` |

### Editor performance (4)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 4 | [#227892](https://github.com/microsoft/vscode/issues/227892) | [regression] Increased typing lag with many word separators | 1 | freeze | 5/6 Source-confirmed | 54 | — | `npm run implement -- --issue 227892` |
| 25 | [#167788](https://github.com/microsoft/vscode/issues/167788) | Weird overcaching of code for extension host | 1 | correctness | 4/6 Traced | 7 | — | `npm run implement -- --issue 167788` |
| 39 | [#260083](https://github.com/microsoft/vscode/issues/260083) | [172] potential listener LEAK detected, having 202 listeners already. MOST frequent listener (28): | 0 | perf | 5/6 Source-confirmed | 3 | yes | `npm run implement -- --issue 260083` |
| 57 | [#174557](https://github.com/microsoft/vscode/issues/174557) | Invoking deltaDecorations recursively could lead to leaking decorations. | 0 | correctness | 2/6 Unverified | 0 | — | `npm run implement -- --issue 174557` |

### Formatting triggers (5)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 5 | [#238052](https://github.com/microsoft/vscode/issues/238052) | Format on save is aborted when interacting with the editor | 5 | correctness | 5/6 Source-confirmed | 47 | yes | `npm run implement -- --issue 238052` |
| 17 | [#245002](https://github.com/microsoft/vscode/issues/245002) | Vim write (:w) does not invoke Python Black 'editor.formatOnSave' on Mac | 0 | correctness | 5/6 Source-confirmed | 12 | yes | `npm run implement -- --issue 245002` |
| 28 | [#237684](https://github.com/microsoft/vscode/issues/237684) | VSCode claims no JSON formatter installed, but 5 seconds later formats the document just fine | 1 | papercut | 5/6 Source-confirmed | 5 | yes | `npm run implement -- --issue 237684` |
| 46 | [#139968](https://github.com/microsoft/vscode/issues/139968) | When characters are typed at a rapid rate, textDocument/onTypeFormatting fails to fire | 0 | papercut | 4/6 Traced | 1 | — | `npm run implement -- --issue 139968` |
| 64 | [#247651](https://github.com/microsoft/vscode/issues/247651) | Cannot use tab as the trigger character for "format on type" | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 247651` |

### Workspace edits (7)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 10 | [#163929](https://github.com/microsoft/vscode/issues/163929) | Renames returning empty placeholders are not handled correctly | 2 | correctness | 4/6 Traced | 26 | — | `npm run implement -- --issue 163929` |
| 15 | [#182573](https://github.com/microsoft/vscode/issues/182573) | Workspace edit createFile with overwrite deletes file completely on undo | 0 | data-loss | 5/6 Source-confirmed | 15 | yes | `npm run implement -- --issue 182573` |
| 16 | [#194117](https://github.com/microsoft/vscode/issues/194117) | Cannot undo file deletions from a WorkspaceEdit | 0 | correctness | 5/6 Source-confirmed | 15 | — | `npm run implement -- --issue 194117` |
| 32 | [#246720](https://github.com/microsoft/vscode/issues/246720) | Difference in UI between `vscode.workspace.applyEdit(isRefactoring: true)` with 1 edit vs >1 edit | 0 | papercut | 4/6 Traced | 5 | — | `npm run implement -- --issue 246720` |
| 35 | [#197315](https://github.com/microsoft/vscode/issues/197315) | API: WorkspaceEdit definition documentation does not match behavior | 0 | correctness | 5/6 Source-confirmed | 4 | — | `npm run implement -- --issue 197315` |
| 42 | [#172463](https://github.com/microsoft/vscode/issues/172463) | WorkspaceEdit API didn't delete the created folder when undo. | 0 | correctness | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 172463` |
| 48 | [#161987](https://github.com/microsoft/vscode/issues/161987) | WorkspaceEdit: confirmation preview does not reflect the create content | 0 | correctness | 2/6 Unverified | 1 | — | — |

### Inlay hints (5)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 21 | [#231728](https://github.com/microsoft/vscode/issues/231728) | Inlay hint flicker when adding/removing whitespace around it | 0 | visual | 5/6 Source-confirmed | 10 | — | `npm run implement -- --issue 231728` |
| 24 | [#239534](https://github.com/microsoft/vscode/issues/239534) | Single character change triggers 3 'textDocument/inlayHint' request in Python | 0 | perf | 5/6 Source-confirmed | 8 | yes | `npm run implement -- --issue 239534` |
| 27 | [#193443](https://github.com/microsoft/vscode/issues/193443) | Disposed language status item comes back if modified after disposing | 0 | correctness | 5/6 Source-confirmed | 6 | yes | `npm run implement -- --issue 193443` |
| 37 | [#213330](https://github.com/microsoft/vscode/issues/213330) | VSCode does not honor LSP-advertised capabilities when displaying inlay hints menu | 0 | visual | 5/6 Source-confirmed | 3 | yes | `npm run implement -- --issue 213330` |
| 40 | [#186604](https://github.com/microsoft/vscode/issues/186604) | Inconsistent dropping of problem markers | 1 | papercut | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 186604` |

### Extension host APIs (5)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 26 | [#156281](https://github.com/microsoft/vscode/issues/156281) | Throwing exceptions across extension host RPC boundaries doesn't preserve Error.name | 1 | none | 2/6 Unverified | 6 | — | — |
| 36 | [#109106](https://github.com/microsoft/vscode/issues/109106) | Use safer test for Location in argument processor | 0 | correctness | 5/6 Source-confirmed | 3 | — | `npm run implement -- --issue 109106` |
| 45 | [#124820](https://github.com/microsoft/vscode/issues/124820) | Proposed API checks fail due to nullExtensionDescription when symlinks (`npm link`) is used (doc needed?) | 0 | correctness | 4/6 Traced | 1 | — | `npm run implement -- --issue 124820` |
| 61 | [#202163](https://github.com/microsoft/vscode/issues/202163) | `languages.match` doesn't work for notebook cell documents in document close events | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 202163` |
| 63 | [#213395](https://github.com/microsoft/vscode/issues/213395) | document 'bicep-extsrc:br%<REDACTED: user-file-path>%<REDACTED: user-file-path> %28private-endpoint%3A0.4.1%29?br%3Amcr.microsoft.com%2Fbicep%2Favm%2Fres%2Fnetwork%2Fprivate-endpoint%3A0.4.1#main.bicep' NOT found | 0 | correctness | 4/6 Traced | 0 | — | `npm run implement -- --issue 213395` |

### Other (2)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 18 | [#242956](https://github.com/microsoft/vscode/issues/242956) | Suggest widget height for fewer than twelve items is calculated incorrectly | 0 | visual | 5/6 Source-confirmed | 11 | — | `npm run implement -- --issue 242956` |
| 19 | [#299369](https://github.com/microsoft/vscode/issues/299369) | CTL+CLICK to open files not working | 0 | none | 2/6 Unverified | 11 | — | — |

## Feature requests

### Language providers (3)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | [#115354](https://github.com/microsoft/vscode/issues/115354) | No way to ensure an extension is prioritized as a rename provider in a language | 33 | dormant | 100 | `npm run implement -- --issue 115354` |
| 13 | [#193416](https://github.com/microsoft/vscode/issues/193416) | Various providers (and LSP messages) that are passed a position should be passed a range instead. | 2 | dormant | 4 | `npm run implement -- --issue 193416` |
| 22 | [#246141](https://github.com/microsoft/vscode/issues/246141) | Could `vscode.executeFormatDocumentProvider` and friends stop after the first provider? | 0 | dormant | 1 | `npm run implement -- --issue 246141` |

### Completion behavior (7)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 2 | [#155738](https://github.com/microsoft/vscode/issues/155738) | Support CompletionList.isIncomplete=true on empty lists (or at least, clearly document current behaviour) | 11 | dormant | 29 | `npm run implement -- --issue 155738` |
| 4 | [#168329](https://github.com/microsoft/vscode/issues/168329) | Filter completion client-side even if the LSP returns incomplete results | 6 | dormant | 21 | `npm run implement -- --issue 168329` |
| 5 | [#147830](https://github.com/microsoft/vscode/issues/147830) | CompletionList.isIncomplete=true results in showing "stale" results when typing quickly due to cancelled requests | 2 | dormant | 16 | `npm run implement -- --issue 147830` |
| 9 | [#110193](https://github.com/microsoft/vscode/issues/110193) | Add option to hide the "suggestion window" when press key left or right [old pattern] | 3 | dormant | 6 | `npm run implement -- --issue 110193` |
| 16 | [#86734](https://github.com/microsoft/vscode/issues/86734) | Disambiguate quickSuggestion from editor.action.triggerSuggest | 1 | dormant | 2 | `npm run implement -- --issue 86734` |
| 20 | [#53959](https://github.com/microsoft/vscode/issues/53959) | Counter-intuitive "editor.suggestSelection" behavior when completion is "kept open" | 0 | dormant | 1 | `npm run implement -- --issue 53959` |
| 23 | [#190172](https://github.com/microsoft/vscode/issues/190172) | Autocomplete is too aggressive in its default setting | 0 | dormant | 0 | `npm run implement -- --issue 190172` |

### Terminal environments (1)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 3 | [#152862](https://github.com/microsoft/vscode/issues/152862) | A change in VScode makes it confusing for a user to switch the to a different PowerShell environment in the Integrated Terminal. | 10 | dormant | 22 | `npm run implement -- --issue 152862` |

### Extension APIs (3)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 6 | [#110459](https://github.com/microsoft/vscode/issues/110459) | Make API commands simpler to consume | 6 | dormant | 14 | `npm run implement -- --issue 110459` |
| 7 | [#72831](https://github.com/microsoft/vscode/issues/72831) | FileSystemWatcher fires events to extensions before text documents are updated | 0 | dormant | 9 | `npm run implement -- --issue 72831` |
| 15 | [#139702](https://github.com/microsoft/vscode/issues/139702) | file://// URL not recognised | 0 | dormant | 3 | — |

### Editor interface (4)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 8 | [#174677](https://github.com/microsoft/vscode/issues/174677) | Zen Mode | 2 | active | 7 | — |
| 17 | [#87531](https://github.com/microsoft/vscode/issues/87531) | [Feature Request] Create collapsed and expanded elements in tooltips | 0 | dormant | 2 | — |
| 19 | [#246047](https://github.com/microsoft/vscode/issues/246047) | Move "Add Context..." dialogue closer to the button | 0 | dormant | 2 | `npm run implement -- --issue 246047` |
| 24 | [#192092](https://github.com/microsoft/vscode/issues/192092) | Would it be possible and interesting to group some menus? | 0 | dormant | 0 | `npm run implement -- --issue 192092` |

### Inlay hints (2)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 12 | [#265980](https://github.com/microsoft/vscode/issues/265980) | The number of Inlay hints is limited | 0 | active | 6 | `npm run implement -- --issue 265980` |
| 18 | [#165009](https://github.com/microsoft/vscode/issues/165009) | Feature: identify Inlay Hints text (e.g. info in tooltip) | 0 | dormant | 2 | `npm run implement -- --issue 165009` |

### Extension management (1)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 11 | [#111669](https://github.com/microsoft/vscode/issues/111669) | Extension bisect unable to find 2 bad extensions | 0 | dormant | 6 | `npm run implement -- --issue 111669` |

### Copilot editing (1)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 10 | [#241290](https://github.com/microsoft/vscode/issues/241290) | [Feature Request] Enable Pinpoint Changes in GitHub Copilot Edits and Agent Mode | 1 | dormant | 6 | `npm run implement -- --issue 241290` |

### Diagnostics and problems (2)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 14 | [#143435](https://github.com/microsoft/vscode/issues/143435) | Line numbers in the Problems windows not easy to read when it comes to cells | 2 | dormant | 3 | `npm run implement -- --issue 143435` |
| 21 | [#192189](https://github.com/microsoft/vscode/issues/192189) | Ability to disable diagnostics etc. from certain sources | 0 | dormant | 1 | `npm run implement -- --issue 192189` |
