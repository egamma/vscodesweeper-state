# Top issues by theme — jrieken

Experimental themed view of [the flat ranking](jrieken.md); themes assigned by the review engine. Rank/score are the lane-wide values. Generated 2026-08-03 15:36 UTC.

## Bugs

### Extension API lifecycle (18)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | [#210947](https://github.com/microsoft/vscode/issues/210947) | AbstractContextKeyService has been disposed | 1 | correctness | 5/6 Source-confirmed | 100 | — | — |
| 5 | [#310777](https://github.com/microsoft/vscode/issues/310777) | [Error] unhandlederror-AbstractContextKeyService has been disposed | 0 | correctness | 5/6 Source-confirmed | 44 | yes | — |
| 6 | [#312810](https://github.com/microsoft/vscode/issues/312810) | [Error] [GitHub.copilot-chat] unhandlederror-Response stream has been closed | 0 | correctness | 5/6 Source-confirmed | 41 | yes | — |
| 11 | [#312380](https://github.com/microsoft/vscode/issues/312380) | [Error] unhandlederror-Cannot access a disposed editing session | 0 | correctness | 5/6 Source-confirmed | 21 | yes | — |
| 25 | [#156281](https://github.com/microsoft/vscode/issues/156281) | Throwing exceptions across extension host RPC boundaries doesn't preserve Error.name | 1 | none | 2/6 Unverified | 6 | — | — |
| 26 | [#193443](https://github.com/microsoft/vscode/issues/193443) | Disposed language status item comes back if modified after disposing | 0 | correctness | 5/6 Source-confirmed | 6 | yes | — |
| 29 | [#144562](https://github.com/microsoft/vscode/issues/144562) | Assertion Failed: argument is undefined or null | 0 | correctness | 4/6 Traced | 5 | yes | — |
| 35 | [#109106](https://github.com/microsoft/vscode/issues/109106) | Use safer test for Location in argument processor | 0 | correctness | 5/6 Source-confirmed | 3 | — | — |
| 38 | [#260083](https://github.com/microsoft/vscode/issues/260083) | [172] potential listener LEAK detected, having 202 listeners already. MOST frequent listener (28): | 0 | perf | 5/6 Source-confirmed | 3 | yes | — |
| 44 | [#124820](https://github.com/microsoft/vscode/issues/124820) | Proposed API checks fail due to nullExtensionDescription when symlinks (`npm link`) is used (doc needed?) | 0 | correctness | 4/6 Traced | 1 | — | — |
| 53 | [#154758](https://github.com/microsoft/vscode/issues/154758) | Error: unknown text editor | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 54 | [#160573](https://github.com/microsoft/vscode/issues/160573) | WebSocket is not open: readyState 3 (CLOSED) | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 55 | [#161063](https://github.com/microsoft/vscode/issues/161063) | Cannot read properties of null (reading 'startLineNumber') | 0 | correctness | 4/6 Traced | 0 | yes | — |
| 56 | [#174557](https://github.com/microsoft/vscode/issues/174557) | Invoking deltaDecorations recursively could lead to leaking decorations. | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 57 | [#187457](https://github.com/microsoft/vscode/issues/187457) | file:///c%<REDACTED: user-file-path> <REDACTED: user-file-path> does not exist and can not be deleted | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 60 | [#202163](https://github.com/microsoft/vscode/issues/202163) | `languages.match` doesn't work for notebook cell documents in document close events | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 61 | [#212720](https://github.com/microsoft/vscode/issues/212720) | Illegal value for lineNumber | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 62 | [#213395](https://github.com/microsoft/vscode/issues/213395) | document 'bicep-extsrc:br%<REDACTED: user-file-path>%<REDACTED: user-file-path> %28private-endpoint%3A0.4.1%29?br%3Amcr.microsoft.com%2Fbicep%2Favm%2Fres%2Fnetwork%2Fprivate-endpoint%3A0.4.1#main.bicep' NOT found | 0 | correctness | 4/6 Traced | 0 | — | — |

### Suggest and completions (24)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2 | [#240244](https://github.com/microsoft/vscode/issues/240244) | Setting `editor.suggest.localityBonus` is not used | 10 | correctness | 5/6 Source-confirmed | 93 | yes | — |
| 7 | [#134013](https://github.com/microsoft/vscode/issues/134013) | Code completion unexpectedly consumes closing paren (from auto-closing-brackets) that was inserted automatically when `(` triggered code completion | 2 | correctness | 5/6 Source-confirmed | 35 | — | — |
| 8 | [#251013](https://github.com/microsoft/vscode/issues/251013) | Incorrect `editor.suggest.showWords` replacements for completion items if an LSP response takes too long | 0 | correctness | 6/6 Confirmed | 30 | — | — |
| 10 | [#246857](https://github.com/microsoft/vscode/issues/246857) | Markdown inside of CompletionItem documentation does not wrap text in code block | 1 | visual | 5/6 Source-confirmed | 25 | yes | — |
| 12 | [#188162](https://github.com/microsoft/vscode/issues/188162) | Completion list is not filtered correctly when typing a number after a hyphen | 1 | correctness | 5/6 Source-confirmed | 17 | yes | — |
| 17 | [#242956](https://github.com/microsoft/vscode/issues/242956) | Suggest widget height for fewer than twelve items is calculated incorrectly | 0 | visual | 5/6 Source-confirmed | 11 | — | — |
| 19 | [#262227](https://github.com/microsoft/vscode/issues/262227) | The json editor stops completing values after the character `+` is used | 1 | correctness | 5/6 Source-confirmed | 10 | yes | — |
| 21 | [#108150](https://github.com/microsoft/vscode/issues/108150) | Inconsistencies with Trigger (full) completions when (incomplete) completions are already active | 0 | correctness | 3/6 Plausible | 8 | — | — |
| 28 | [#295537](https://github.com/microsoft/vscode/issues/295537) | Icons in autocomplete are not scaled when font-size is changed by user | 1 | visual | 5/6 Source-confirmed | 5 | yes | — |
| 30 | [#217387](https://github.com/microsoft/vscode/issues/217387) | Language type icon overriding file autocompletion | 0 | visual | 5/6 Source-confirmed | 5 | yes | — |
| 32 | [#272090](https://github.com/microsoft/vscode/issues/272090) | Suggest triggers when deleting code | 0 | papercut | 5/6 Source-confirmed | 5 | — | — |
| 33 | [#187779](https://github.com/microsoft/vscode/issues/187779) | Suggest widget gets orphaned in editor | 0 | visual | 6/6 Confirmed | 4 | yes | — |
| 37 | [#245401](https://github.com/microsoft/vscode/issues/245401) | When the UI is zoomed in (higher than 100% level) the autocomplete tooltip sometimes completely covers the code I'm writing | 0 | visual | 6/6 Confirmed | 3 | — | — |
| 40 | [#236980](https://github.com/microsoft/vscode/issues/236980) | suggestion widget focus ,but can't use page down or ↓,it can't work nomally | 1 | papercut | 5/6 Source-confirmed | 2 | yes | — |
| 43 | [#110069](https://github.com/microsoft/vscode/issues/110069) | Suggestion details shown on the left of suggestion list hide text and cursor | 0 | visual | — | 1 | — | — |
| 46 | [#160951](https://github.com/microsoft/vscode/issues/160951) | Accepting completion with multiline edits makes editor scroll jump higher | 0 | visual | 4/6 Traced | 1 | — | — |
| 48 | [#170491](https://github.com/microsoft/vscode/issues/170491) | VSCode does not remember the size of the suggest widget when the size is reset with double click | 0 | papercut | 5/6 Source-confirmed | 1 | yes | — |
| 49 | [#187147](https://github.com/microsoft/vscode/issues/187147) | fuzzyScore boostFullMatch:false incorrect when pattern ends with uppercase | 0 | correctness | 5/6 Source-confirmed | 1 | — | — |
| 50 | [#234588](https://github.com/microsoft/vscode/issues/234588) | Not displaying completion items with empty string text labels | 0 | correctness | 5/6 Source-confirmed | 1 | — | — |
| 51 | [#284229](https://github.com/microsoft/vscode/issues/284229) | Unexpected sort in completions | 0 | papercut | 5/6 Source-confirmed | 1 | — | — |
| 52 | [#316100](https://github.com/microsoft/vscode/issues/316100) | The Auto Completion Just Gets In The Way. | 0 | none | 3/6 Plausible | 1 | — | — |
| 58 | [#196665](https://github.com/microsoft/vscode/issues/196665) | Cannot read properties of undefined (reading 'completion') | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 59 | [#196666](https://github.com/microsoft/vscode/issues/196666) | Cannot read properties of undefined (reading 'tooltip') | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 64 | [#276677](https://github.com/microsoft/vscode/issues/276677) | Top suggestion item unclickable when IntelliSense list reaches top of editor window | 0 | papercut | 3/6 Plausible | 0 | — | — |

### Editor performance (3)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 3 | [#227892](https://github.com/microsoft/vscode/issues/227892) | [regression] Increased typing lag with many word separators | 1 | freeze | 5/6 Source-confirmed | 54 | — | — |
| 23 | [#313179](https://github.com/microsoft/vscode/issues/313179) | Copilot chat showing file changes makes whole vscode slow | 0 | perf | 3/6 Plausible | 8 | — | — |
| 24 | [#167788](https://github.com/microsoft/vscode/issues/167788) | Weird overcaching of code for extension host | 1 | correctness | 4/6 Traced | 7 | — | — |

### Formatting triggers (5)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 4 | [#238052](https://github.com/microsoft/vscode/issues/238052) | Format on save is aborted when interacting with the editor | 5 | correctness | 5/6 Source-confirmed | 47 | yes | — |
| 16 | [#245002](https://github.com/microsoft/vscode/issues/245002) | Vim write (:w) does not invoke Python Black 'editor.formatOnSave' on Mac | 0 | correctness | 5/6 Source-confirmed | 12 | yes | — |
| 27 | [#237684](https://github.com/microsoft/vscode/issues/237684) | VSCode claims no JSON formatter installed, but 5 seconds later formats the document just fine | 1 | papercut | 5/6 Source-confirmed | 5 | yes | — |
| 45 | [#139968](https://github.com/microsoft/vscode/issues/139968) | When characters are typed at a rapid rate, textDocument/onTypeFormatting fails to fire | 0 | papercut | 4/6 Traced | 1 | — | — |
| 63 | [#247651](https://github.com/microsoft/vscode/issues/247651) | Cannot use tab as the trigger character for "format on type" | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |

### Workspace edits (7)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 9 | [#163929](https://github.com/microsoft/vscode/issues/163929) | Renames returning empty placeholders are not handled correctly | 2 | correctness | 4/6 Traced | 26 | — | — |
| 14 | [#182573](https://github.com/microsoft/vscode/issues/182573) | Workspace edit createFile with overwrite deletes file completely on undo | 0 | data-loss | 5/6 Source-confirmed | 15 | yes | — |
| 15 | [#194117](https://github.com/microsoft/vscode/issues/194117) | Cannot undo file deletions from a WorkspaceEdit | 0 | correctness | 5/6 Source-confirmed | 15 | — | — |
| 31 | [#246720](https://github.com/microsoft/vscode/issues/246720) | Difference in UI between `vscode.workspace.applyEdit(isRefactoring: true)` with 1 edit vs >1 edit | 0 | papercut | 4/6 Traced | 5 | — | — |
| 34 | [#197315](https://github.com/microsoft/vscode/issues/197315) | API: WorkspaceEdit definition documentation does not match behavior | 0 | correctness | 5/6 Source-confirmed | 4 | — | — |
| 41 | [#172463](https://github.com/microsoft/vscode/issues/172463) | WorkspaceEdit API didn't delete the created folder when undo. | 0 | correctness | 5/6 Source-confirmed | 2 | yes | — |
| 47 | [#161987](https://github.com/microsoft/vscode/issues/161987) | WorkspaceEdit: confirmation preview does not reflect the create content | 0 | correctness | 2/6 Unverified | 1 | — | — |

### Editor navigation (3)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 13 | [#254884](https://github.com/microsoft/vscode/issues/254884) | Edits toolbar goes on top of Open Merge Editor blue button | 0 | visual | 5/6 Source-confirmed | 17 | — | — |
| 18 | [#299369](https://github.com/microsoft/vscode/issues/299369) | CTL+CLICK to open files not working | 0 | none | 2/6 Unverified | 11 | — | — |
| 42 | [#247046](https://github.com/microsoft/vscode/issues/247046) | Accessible diff view become blank after accepting the change that agent made | 0 | visual | 5/6 Source-confirmed | 2 | yes | — |

### Inlay hints (3)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 20 | [#231728](https://github.com/microsoft/vscode/issues/231728) | Inlay hint flicker when adding/removing whitespace around it | 0 | visual | 5/6 Source-confirmed | 10 | — | — |
| 22 | [#239534](https://github.com/microsoft/vscode/issues/239534) | Single character change triggers 3 'textDocument/inlayHint' request in Python | 0 | perf | 5/6 Source-confirmed | 8 | yes | — |
| 36 | [#213330](https://github.com/microsoft/vscode/issues/213330) | VSCode does not honor LSP-advertised capabilities when displaying inlay hints menu | 0 | visual | 5/6 Source-confirmed | 3 | yes | — |

### Other (1)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 39 | [#186604](https://github.com/microsoft/vscode/issues/186604) | Inconsistent dropping of problem markers | 1 | papercut | 5/6 Source-confirmed | 2 | — | — |

## Feature requests

### Provider coordination (6)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | [#115354](https://github.com/microsoft/vscode/issues/115354) | No way to ensure an extension is prioritized as a rename provider in a language | 33 | dormant | 100 | — |
| 6 | [#110459](https://github.com/microsoft/vscode/issues/110459) | Make API commands simpler to consume | 6 | dormant | 14 | — |
| 7 | [#72831](https://github.com/microsoft/vscode/issues/72831) | FileSystemWatcher fires events to extensions before text documents are updated | 0 | dormant | 9 | — |
| 14 | [#193416](https://github.com/microsoft/vscode/issues/193416) | Various providers (and LSP messages) that are passed a position should be passed a range instead. | 2 | dormant | 4 | — |
| 22 | [#192189](https://github.com/microsoft/vscode/issues/192189) | Ability to disable diagnostics etc. from certain sources | 0 | dormant | 1 | — |
| 23 | [#246141](https://github.com/microsoft/vscode/issues/246141) | Could `vscode.executeFormatDocumentProvider` and friends stop after the first provider? | 0 | dormant | 1 | — |

### Suggest behavior (7)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 2 | [#155738](https://github.com/microsoft/vscode/issues/155738) | Support CompletionList.isIncomplete=true on empty lists (or at least, clearly document current behaviour) | 11 | dormant | 29 | — |
| 4 | [#168329](https://github.com/microsoft/vscode/issues/168329) | Filter completion client-side even if the LSP returns incomplete results | 6 | dormant | 21 | — |
| 5 | [#147830](https://github.com/microsoft/vscode/issues/147830) | CompletionList.isIncomplete=true results in showing "stale" results when typing quickly due to cancelled requests | 2 | dormant | 16 | — |
| 9 | [#110193](https://github.com/microsoft/vscode/issues/110193) | Add option to hide the "suggestion window" when press key left or right [old pattern] | 3 | dormant | 6 | — |
| 17 | [#86734](https://github.com/microsoft/vscode/issues/86734) | Disambiguate quickSuggestion from editor.action.triggerSuggest | 1 | dormant | 2 | — |
| 21 | [#53959](https://github.com/microsoft/vscode/issues/53959) | Counter-intuitive "editor.suggestSelection" behavior when completion is "kept open" | 0 | dormant | 1 | — |
| 24 | [#190172](https://github.com/microsoft/vscode/issues/190172) | Autocomplete is too aggressive in its default setting | 0 | dormant | 0 | — |

### Workbench presentation (4)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 8 | [#174677](https://github.com/microsoft/vscode/issues/174677) | Zen Mode | 2 | active | 7 | — |
| 15 | [#143435](https://github.com/microsoft/vscode/issues/143435) | Line numbers in the Problems windows not easy to read when it comes to cells | 2 | dormant | 3 | — |
| 18 | [#87531](https://github.com/microsoft/vscode/issues/87531) | [Feature Request] Create collapsed and expanded elements in tooltips | 0 | dormant | 2 | — |
| 25 | [#192092](https://github.com/microsoft/vscode/issues/192092) | Would it be possible and interesting to group some menus? | 0 | dormant | 0 | — |

### Inlay hints (2)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 12 | [#265980](https://github.com/microsoft/vscode/issues/265980) | The number of Inlay hints is limited | 0 | active | 6 | — |
| 19 | [#165009](https://github.com/microsoft/vscode/issues/165009) | Feature: identify Inlay Hints text (e.g. info in tooltip) | 0 | dormant | 2 | — |

### Chat context UX (3)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 10 | [#241290](https://github.com/microsoft/vscode/issues/241290) | [Feature Request] Enable Pinpoint Changes in GitHub Copilot Edits and Agent Mode | 1 | dormant | 6 | — |
| 13 | [#315085](https://github.com/microsoft/vscode/issues/315085) | Ctrl+I shortcut (Inline Chat) defaults to Sidebar Chat after first use of Chat View | 1 | active | 5 | — |
| 20 | [#246047](https://github.com/microsoft/vscode/issues/246047) | Move "Add Context..." dialogue closer to the button | 0 | dormant | 2 | — |

### Other (3)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 3 | [#152862](https://github.com/microsoft/vscode/issues/152862) | A change in VScode makes it confusing for a user to switch the to a different PowerShell environment in the Integrated Terminal. | 10 | dormant | 22 | — |
| 11 | [#111669](https://github.com/microsoft/vscode/issues/111669) | Extension bisect unable to find 2 bad extensions | 0 | dormant | 6 | — |
| 16 | [#139702](https://github.com/microsoft/vscode/issues/139702) | file://// URL not recognised | 0 | dormant | 3 | — |
