# Top issues by theme — alexr00

Experimental themed view of [the flat ranking](alexr00.md); themes assigned by the review engine. Rank/score are the lane-wide values. Generated 2026-07-25 20:48 UTC.

## Bugs

### Tree refresh state (7)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | [#192055](https://github.com/microsoft/vscode/issues/192055) | TreeView reveal creates a race condition with `TreeDataProvider#getChildren` | 2 | correctness | 5/6 Source-confirmed | 100 | — | `npm run implement -- --issue 192055` |
| 4 | [#283655](https://github.com/microsoft/vscode/issues/283655) | view/item/context command argument is undefined if treeview is in the middle of a refresh | 0 | correctness | 5/6 Source-confirmed | 55 | yes | `npm run implement -- --issue 283655` |
| 7 | [#233056](https://github.com/microsoft/vscode/issues/233056) | TreeView: MaxCallStackError - Nesting | 0 | crash | 5/6 Source-confirmed | 43 | — | `npm run implement -- --issue 233056` |
| 17 | [#307375](https://github.com/microsoft/vscode/issues/307375) | bug: treeView: drag-and-drop does not work when the tree view is initially empty | 1 | correctness | 5/6 Source-confirmed | 18 | yes | `npm run implement -- --issue 307375` |
| 36 | [#153982](https://github.com/microsoft/vscode/issues/153982) | Events and registered commands on TreeView are unreliable when refreshing treeview | 0 | correctness | 5/6 Source-confirmed | 3 | yes | `npm run implement -- --issue 153982` |
| 48 | [#323659](https://github.com/microsoft/vscode/issues/323659) | bug: TreeView selection becomes corrupted when a context key update changes item context menu visibility | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 323659` |
| 49 | [#324042](https://github.com/microsoft/vscode/issues/324042) | On 'manageCheckboxStateManually', refreshing node with new checkbox state flips all parent checkbox states recursively | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 324042` |

### Tree interaction rendering (4)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2 | [#307350](https://github.com/microsoft/vscode/issues/307350) | visual: TreeView items without icons shift parent indentation | 1 | visual | 5/6 Source-confirmed | 55 | — | `npm run implement -- --issue 307350` |
| 11 | [#171550](https://github.com/microsoft/vscode/issues/171550) | Focused item in tree is never unfocused | 0 | correctness | 5/6 Source-confirmed | 28 | yes | `npm run implement -- --issue 171550` |
| 14 | [#262542](https://github.com/microsoft/vscode/issues/262542) | Multi select behaves strangely on tree views | 0 | correctness | 6/6 Confirmed | 25 | — | `npm run implement -- --issue 262542` |
| 18 | [#126964](https://github.com/microsoft/vscode/issues/126964) | Tree item focus should avoid jumping when tree items change | 2 | papercut | 5/6 Source-confirmed | 16 | — | `npm run implement -- --issue 126964` |

### Remote explorer dialogs (5)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 3 | [#232950](https://github.com/microsoft/vscode/issues/232950) | DONT auto list all sub-directory during selecting folder in Remote connection | 0 | correctness | 6/6 Confirmed | 55 | — | `npm run implement -- --issue 232950` |
| 16 | [#286936](https://github.com/microsoft/vscode/issues/286936) | checkout not checking out correct repo | 0 | correctness | — | 20 | — | `npm run implement -- --issue 286936` |
| 31 | [#321903](https://github.com/microsoft/vscode/issues/321903) | Menu "Open File..." error | 0 | papercut | 3/6 Plausible | 7 | — | — |
| 42 | [#320899](https://github.com/microsoft/vscode/issues/320899) | the issue of showing previous projects and folders on remote explorer | 0 | papercut | 3/6 Plausible | 2 | — | — |
| 47 | [#320384](https://github.com/microsoft/vscode/issues/320384) | Simple file dialog - change the name when creating a new folder | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 320384` |

### Editor responsiveness (5)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 6 | [#254543](https://github.com/microsoft/vscode/issues/254543) | Slow typing in medium sized ts file | 0 | perf | 6/6 Confirmed | 47 | — | `npm run implement -- --issue 254543` |
| 8 | [#99356](https://github.com/microsoft/vscode/issues/99356) | `getTokenInformationAtPosition` API causes too much traffic and blocks the renderer process | 0 | perf | 4/6 Traced | 42 | — | `npm run implement -- --issue 99356` |
| 25 | [#250479](https://github.com/microsoft/vscode/issues/250479) | color flashes when opening a file | 1 | visual | 3/6 Plausible | 8 | — | `npm run implement -- --issue 250479` |
| 26 | [#250506](https://github.com/microsoft/vscode/issues/250506) | Incomplete highlighting after switching themes | 1 | visual | 4/6 Traced | 8 | — | `npm run implement -- --issue 250506` |
| 34 | [#156838](https://github.com/microsoft/vscode/issues/156838) | Multiple comment decorations rendered when word wrap is turned on | 0 | visual | 5/6 Source-confirmed | 4 | yes | `npm run implement -- --issue 156838` |

### Syntax highlighting grammars (11)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 9 | [#221571](https://github.com/microsoft/vscode/issues/221571) | Wrong syntax coloring in PHP with string 'AND [' | 3 | visual | 5/6 Source-confirmed | 37 | — | `npm run implement -- --issue 221571` |
| 19 | [#176044](https://github.com/microsoft/vscode/issues/176044) | Markdown: wrong unexpected Bracket in bash code block | 0 | visual | 2/6 Unverified | 14 | — | — |
| 21 | [#239671](https://github.com/microsoft/vscode/issues/239671) | `Content-Type: application/json` caused the lint error for ```sh ``` block for markdown(.md) file | 0 | visual | 4/6 Traced | 11 | — | `npm run implement -- --issue 239671` |
| 23 | [#266686](https://github.com/microsoft/vscode/issues/266686) | CSS properties inside a layer nested inside a selector produce a syntax error when using SCSS but works fine with CSS. | 0 | visual | 5/6 Source-confirmed | 10 | — | — |
| 24 | [#273107](https://github.com/microsoft/vscode/issues/273107) | PHP language scope in embedded PHP code is incorrectly exited after the first quotation mark | 0 | visual | 5/6 Source-confirmed | 9 | — | `npm run implement -- --issue 273107` |
| 28 | [#178955](https://github.com/microsoft/vscode/issues/178955) | Syntax highlighting for JavaScript in HTML file breaks when "if" is on the same line as closing tag | 1 | visual | 4/6 Traced | 7 | — | `npm run implement -- --issue 178955` |
| 29 | [#129400](https://github.com/microsoft/vscode/issues/129400) | Syntax highlighting stops in minified code | 0 | visual | 5/6 Source-confirmed | 7 | — | `npm run implement -- --issue 129400` |
| 30 | [#244605](https://github.com/microsoft/vscode/issues/244605) | Regex Tree Sitter: Look around expressions not colored correctly | 0 | visual | 5/6 Source-confirmed | 7 | — | `npm run implement -- --issue 244605` |
| 33 | [#135234](https://github.com/microsoft/vscode/issues/135234) | Bug of recognizing a JavaScript comment instead of URL | 0 | visual | 4/6 Traced | 6 | — | `npm run implement -- --issue 135234` |
| 40 | [#326547](https://github.com/microsoft/vscode/issues/326547) | Bad Syntax highlighting for BASH scripts | 0 | none | 3/6 Plausible | 3 | — | `npm run implement -- --issue 326547` |
| 43 | [#185641](https://github.com/microsoft/vscode/issues/185641) | Perl syntax highlighting bug with embedded JavaScript | 0 | visual | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 185641` |

### Tree sitter highlighting (5)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 10 | [#246413](https://github.com/microsoft/vscode/issues/246413) | Comment toggling doesn't work when using Treesitter | 0 | correctness | 6/6 Confirmed | 29 | — | `npm run implement -- --issue 246413` |
| 22 | [#254313](https://github.com/microsoft/vscode/issues/254313) | No highlight in template string if enabled preferTreeSitter.typescript in Abyss color theme | 0 | visual | 5/6 Source-confirmed | 10 | yes | `npm run implement -- --issue 254313` |
| 37 | [#247984](https://github.com/microsoft/vscode/issues/247984) | Enabling Tree Sitter removes minty fields in builtInExtensionsCG.ts | 0 | visual | 5/6 Source-confirmed | 3 | — | `npm run implement -- --issue 247984` |
| 45 | [#250481](https://github.com/microsoft/vscode/issues/250481) | Ghost text - incorrect coloring using treesitter | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 250481` |
| 46 | [#250488](https://github.com/microsoft/vscode/issues/250488) | Syntax highlighting feels slower | 0 | perf | 3/6 Plausible | 0 | — | `npm run implement -- --issue 250488` |

### Tree view performance (2)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 12 | [#250024](https://github.com/microsoft/vscode/issues/250024) | Significant VSCodeVim performance slowdowns tied to visible size of another extension's static TreeView | 1 | perf | 4/6 Traced | 27 | — | `npm run implement -- --issue 250024` |
| 15 | [#324355](https://github.com/microsoft/vscode/issues/324355) | TreeView scrolling performance degradation caused by MenuService with heavy context menus | 1 | perf | 5/6 Source-confirmed | 24 | — | `npm run implement -- --issue 324355` |

### PR comment context (3)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 20 | [#282583](https://github.com/microsoft/vscode/issues/282583) | PRs are auto attached as context | 0 | papercut | — | 12 | — | `npm run implement -- --issue 282583` |
| 35 | [#254632](https://github.com/microsoft/vscode/issues/254632) | Filter comments only accepts filenames and not repo relative paths | 0 | papercut | 5/6 Source-confirmed | 4 | — | `npm run implement -- --issue 254632` |
| 39 | [#320371](https://github.com/microsoft/vscode/issues/320371) | implicit PR attachment shows when PR is already attached | 0 | visual | — | 3 | — | `npm run implement -- --issue 320371` |

### Other (7)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 5 | [#197377](https://github.com/microsoft/vscode/issues/197377) | workspaceFolder variable substitution in launch.json or tasks.json should use URI for virtual filesystems | 0 | correctness | 5/6 Source-confirmed | 49 | — | `npm run implement -- --issue 197377` |
| 13 | [#182034](https://github.com/microsoft/vscode/issues/182034) | Right Overflow | 0 | correctness | 2/6 Unverified | 25 | — | — |
| 27 | [#245861](https://github.com/microsoft/vscode/issues/245861) | NPM notification endless loop | 0 | papercut | 5/6 Source-confirmed | 8 | yes | `npm run implement -- --issue 245861` |
| 32 | [#67966](https://github.com/microsoft/vscode/issues/67966) | List references: transition from history to results is not smooth | 0 | visual | 3/6 Plausible | 6 | — | — |
| 38 | [#261553](https://github.com/microsoft/vscode/issues/261553) | RuntimeError: memory access out of bounds when using Copilot chat | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 41 | [#188823](https://github.com/microsoft/vscode/issues/188823) | SVGs don't seem to work for `iconPath` in `QuickPickItem` | 0 | papercut | 4/6 Traced | 2 | — | `npm run implement -- --issue 188823` |
| 44 | [#210670](https://github.com/microsoft/vscode/issues/210670) | Restarting extensions messes the script order in npm scripts pane in the folder side bar. | 0 | visual | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 210670` |

## Feature requests

### Syntax highlighting (13)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | [#50140](https://github.com/microsoft/vscode/issues/50140) | Support syntax highlighting with tree-sitter | 738 | backlog-candidate | 100 | `npm run implement -- --issue 50140` |
| 2 | [#243405](https://github.com/microsoft/vscode/issues/243405) | Pre-optimize all TM grammars for performance | 74 | backlog-candidate | 19 | `npm run implement -- --issue 243405` |
| 3 | [#210475](https://github.com/microsoft/vscode/issues/210475) | Explore using tree sitter for syntax highlighting | 65 | backlog-candidate | 17 | `npm run implement -- --issue 210475` |
| 37 | [#292065](https://github.com/microsoft/vscode/issues/292065) | Add Syntax Highlighting Support for TOML Configuration Files in VS Code | 7 | active | 1 | — |
| 40 | [#206192](https://github.com/microsoft/vscode/issues/206192) | Show Comments in TextMate Scope Inspector | 4 | backlog-candidate | 1 | `npm run implement -- --issue 206192` |
| 56 | [#141632](https://github.com/microsoft/vscode/issues/141632) | Consider adopting a new ini grammar | 1 | dormant | 0 | `npm run implement -- --issue 141632` |
| 59 | [#202915](https://github.com/microsoft/vscode/issues/202915) | Consider finding a new HTML grammar: URL with double slashes within an onclick element highlighted as a code comment | 1 | backlog-candidate | 0 | `npm run implement -- --issue 202915` |
| 61 | [#243338](https://github.com/microsoft/vscode/issues/243338) | Add a grammar for js doc: {@link ...} doesn't get color in jsdoc with tree sitter | 1 | backlog-candidate | 0 | `npm run implement -- --issue 243338` |
| 65 | [#145097](https://github.com/microsoft/vscode/issues/145097) | Consider using a new grammar for Groovy: Failed to highlight multi-lined regexp in Groovy code | 0 | backlog-candidate | 0 | `npm run implement -- --issue 145097` |
| 81 | [#225246](https://github.com/microsoft/vscode/issues/225246) | CSHTML Razor syntax highlighting suboptimal | 0 | backlog-candidate | 0 | `npm run implement -- --issue 225246` |
| 83 | [#236924](https://github.com/microsoft/vscode/issues/236924) | Consider finding a new XML syntax highlighting grammar | 0 | backlog-candidate | 0 | `npm run implement -- --issue 236924` |
| 84 | [#261438](https://github.com/microsoft/vscode/issues/261438) | Consider adopting a new Python grammar | 0 | backlog-candidate | 0 | `npm run implement -- --issue 261438` |
| 89 | [#274290](https://github.com/microsoft/vscode/issues/274290) | Find a new shaders grammar: HLSL's "StructuredBuffer" keyword is not getting syntax highlighting | 0 | backlog-candidate | 0 | `npm run implement -- --issue 274290` |

### Ports and tunnels (6)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 4 | [#100222](https://github.com/microsoft/vscode/issues/100222) | Support reverse tunnel | 144 | backlog-candidate | 15 | `npm run implement -- --issue 100222` |
| 17 | [#310930](https://github.com/microsoft/vscode/issues/310930) | Stabilize `vscode.proposed.tunnels` API: enabling named portless tunnel aliases for AI-assisted devcontainer workflows | 24 | backlog-candidate | 4 | `npm run implement -- --issue 310930` |
| 41 | [#115616](https://github.com/microsoft/vscode/issues/115616) | Provide extension API to exclude ports from forwarding | 0 | backlog-candidate | 1 | `npm run implement -- --issue 115616` |
| 53 | [#320086](https://github.com/microsoft/vscode/issues/320086) | Make status bar `Forwarded Ports` toggleable | 2 | active | 0 | `npm run implement -- --issue 320086` |
| 54 | [#320338](https://github.com/microsoft/vscode/issues/320338) | For port forwarding in WSL, use `localhost` rather than an internet address or `192.168`. | 2 | backlog-candidate | 0 | `npm run implement -- --issue 320338` |
| 55 | [#124582](https://github.com/microsoft/vscode/issues/124582) | User forwarded port has the first request TTFB too high | 1 | dormant | 0 | `npm run implement -- --issue 124582` |

### Tree view APIs (21)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 5 | [#97190](https://github.com/microsoft/vscode/issues/97190) | Provide some richer (optional) UI for custom tree views | 127 | backlog-candidate | 13 | `npm run implement -- --issue 97190` |
| 6 | [#88219](https://github.com/microsoft/vscode/issues/88219) | API to programatically expand/collapse tree view | 56 | dormant | 6 | `npm run implement -- --issue 88219` |
| 8 | [#161753](https://github.com/microsoft/vscode/issues/161753) | TreeView search/filter input & api for customization | 43 | backlog-candidate | 6 | `npm run implement -- --issue 161753` |
| 12 | [#90005](https://github.com/microsoft/vscode/issues/90005) | Allow to reveal an empty TreeView programmatically | 40 | backlog-candidate | 4 | `npm run implement -- --issue 90005` |
| 15 | [#188259](https://github.com/microsoft/vscode/issues/188259) | Allow contributing to the context menu in the TreeView's empty space | 27 | backlog-candidate | 4 | `npm run implement -- --issue 188259` |
| 16 | [#170248](https://github.com/microsoft/vscode/issues/170248) | TreeView.selection does not contain focused but not highlighted items | 25 | backlog-candidate | 4 | `npm run implement -- --issue 170248` |
| 18 | [#286332](https://github.com/microsoft/vscode/issues/286332) | VS Code Feature Request: Extension API: Control Tree Item Expansion During Drag Operations | 23 | backlog-candidate | 4 | `npm run implement -- --issue 286332` |
| 22 | [#254411](https://github.com/microsoft/vscode/issues/254411) | Add setting to show tree view item icons without hover effect in Activity Bar | 22 | backlog-candidate | 3 | `npm run implement -- --issue 254411` |
| 24 | [#48754](https://github.com/microsoft/vscode/issues/48754) | Allow programatically un-selecting an item in a contributed tree | 21 | active | 3 | `npm run implement -- --issue 48754` |
| 28 | [#157408](https://github.com/microsoft/vscode/issues/157408) | Add `selectionGroup` to TreeItem to allow for multiselect restrictions | 20 | backlog-candidate | 2 | `npm run implement -- --issue 157408` |
| 29 | [#92176](https://github.com/microsoft/vscode/issues/92176) | API to collapse custom tree items | 14 | backlog-candidate | 2 | `npm run implement -- --issue 92176` |
| 30 | [#107183](https://github.com/microsoft/vscode/issues/107183) | Add a new right-aligned "description" property to TreeItems | 13 | backlog-candidate | 2 | `npm run implement -- --issue 107183` |
| 35 | [#153936](https://github.com/microsoft/vscode/issues/153936) | Allow limited set of markdown in TreeView#message | 9 | backlog-candidate | 1 | `npm run implement -- --issue 153936` |
| 36 | [#175270](https://github.com/microsoft/vscode/issues/175270) | FR: Allow extension views to be defined as a fixed height. | 8 | backlog-candidate | 1 | `npm run implement -- --issue 175270` |
| 42 | [#81757](https://github.com/microsoft/vscode/issues/81757) | API to toggle between flat tree (list) and tree for custom view | 4 | backlog-candidate | 0 | `npm run implement -- --issue 81757` |
| 45 | [#163043](https://github.com/microsoft/vscode/issues/163043) | New "initialSize" does not allow to fit the content | 3 | backlog-candidate | 0 | `npm run implement -- --issue 163043` |
| 63 | [#325080](https://github.com/microsoft/vscode/issues/325080) | Tree View API: allow extensions to control item indentation/icon-twistie alignment (TreeViewOptions.indentation) | 1 | active | 0 | `npm run implement -- --issue 325080` |
| 76 | [#186299](https://github.com/microsoft/vscode/issues/186299) | Consider to bubble up partially checked state | 0 | backlog-candidate | 0 | `npm run implement -- --issue 186299` |
| 97 | [#315186](https://github.com/microsoft/vscode/issues/315186) | Extension API: how to retrieve focused view ID during keybinding command execution? | 0 | backlog-candidate | 0 | `npm run implement -- --issue 315186` |
| 100 | [#323192](https://github.com/microsoft/vscode/issues/323192) | Expose reveal scroll-alignment to the TreeView API (and an Explorer/SCM "reveal with context" option) | 0 | backlog-candidate | 0 | `npm run implement -- --issue 323192` |
| 101 | [#324498](https://github.com/microsoft/vscode/issues/324498) | Add option for manual handling of collapsibleState similar to manageCheckboxStateManually | 0 | backlog-candidate | 0 | — |

### Variable substitution (8)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 7 | [#92854](https://github.com/microsoft/vscode/issues/92854) | Variable substitution with environment - allow for fallback to default | 56 | backlog-candidate | 6 | `npm run implement -- --issue 92854` |
| 11 | [#64358](https://github.com/microsoft/vscode/issues/64358) | consider to allow for variable substitution in the inputs section | 57 | dormant | 4 | `npm run implement -- --issue 64358` |
| 13 | [#140056](https://github.com/microsoft/vscode/issues/140056) | There should be a way in the vscode API to resolve configuration variables | 35 | backlog-candidate | 4 | `npm run implement -- --issue 140056` |
| 21 | [#242153](https://github.com/microsoft/vscode/issues/242153) | Allow using custom variables in setting values | 25 | backlog-candidate | 3 | `npm run implement -- --issue 242153` |
| 26 | [#84982](https://github.com/microsoft/vscode/issues/84982) | Allow detail option on task input pickString | 24 | backlog-candidate | 2 | `npm run implement -- --issue 84982` |
| 27 | [#180830](https://github.com/microsoft/vscode/issues/180830) | [Feature Request] Add predefined variable with separator for environment variable PATH (also PYTHONPATH, CLASSPATH etc.) | 24 | backlog-candidate | 2 | `npm run implement -- --issue 180830` |
| 49 | [#315594](https://github.com/microsoft/vscode/issues/315594) | `npm.scriptRunner` should support deno | 3 | backlog-candidate | 0 | `npm run implement -- --issue 315594` |
| 99 | [#319309](https://github.com/microsoft/vscode/issues/319309) | Allow extensions to contribute and read resolvable variables from the workbench, Take #42 | 0 | backlog-candidate | 0 | — |

### File dialogs (12)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 14 | [#202367](https://github.com/microsoft/vscode/issues/202367) | Fuzzy Search in Open File/Open Folder simple dialogs | 33 | backlog-candidate | 4 | `npm run implement -- --issue 202367` |
| 25 | [#210991](https://github.com/microsoft/vscode/issues/210991) | Add a setting for changing the default path for "Open Folder" to be current open folder, not parent dir | 20 | active | 3 | `npm run implement -- --issue 210991` |
| 43 | [#158994](https://github.com/microsoft/vscode/issues/158994) | Improvements to creating folders via simple picker | 4 | backlog-candidate | 0 | `npm run implement -- --issue 158994` |
| 48 | [#186511](https://github.com/microsoft/vscode/issues/186511) | `files.simpleDialog` should be able to create paths | 3 | backlog-candidate | 0 | `npm run implement -- --issue 186511` |
| 51 | [#154350](https://github.com/microsoft/vscode/issues/154350) | Simple file picker: Add quick pick matching | 2 | dormant | 0 | `npm run implement -- --issue 154350` |
| 66 | [#145656](https://github.com/microsoft/vscode/issues/145656) | File name seems to be lost when navigating directories | 0 | backlog-candidate | 0 | `npm run implement -- --issue 145656` |
| 73 | [#176613](https://github.com/microsoft/vscode/issues/176613) | Add a way back to OS file dialog from simple file dialog when possible | 0 | backlog-candidate | 0 | `npm run implement -- --issue 176613` |
| 74 | [#183403](https://github.com/microsoft/vscode/issues/183403) | Have a way to show only workspace relative path | 0 | backlog-candidate | 0 | `npm run implement -- --issue 183403` |
| 77 | [#186637](https://github.com/microsoft/vscode/issues/186637) | Simple file dialog: support multi-select | 0 | backlog-candidate | 0 | `npm run implement -- --issue 186637` |
| 86 | [#264140](https://github.com/microsoft/vscode/issues/264140) | The "save as" popup dialog's behavior does not align with the primary side bar's Folders | 0 | backlog-candidate | 0 | `npm run implement -- --issue 264140` |
| 91 | [#275985](https://github.com/microsoft/vscode/issues/275985) | File > Open Folder > "Hide dot files" doesn't hide hidden folders in Windows | 0 | backlog-candidate | 0 | `npm run implement -- --issue 275985` |
| 98 | [#317729](https://github.com/microsoft/vscode/issues/317729) | Support ~ in files.dialog.defaultPath | 0 | active | 0 | `npm run implement -- --issue 317729` |

### Chat agents (8)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 19 | [#271104](https://github.com/microsoft/vscode/issues/271104) | Chat: Support contributable chat context resources | 3 | active | 4 | `npm run implement -- --issue 271104` |
| 23 | [#314845](https://github.com/microsoft/vscode/issues/314845) | [Proposal] Contextual guidance assistant & API proposal template | 22 | backlog-candidate | 3 | `npm run implement -- --issue 314845` |
| 62 | [#322987](https://github.com/microsoft/vscode/issues/322987) | Feature Request: Automated PR comment listener with Copilot triage and agentic resolution | 1 | backlog-candidate | 0 | `npm run implement -- --issue 322987` |
| 85 | [#263349](https://github.com/microsoft/vscode/issues/263349) | Can't tell I cancelled session from chat sessions view | 0 | backlog-candidate | 0 | `npm run implement -- --issue 263349` |
| 87 | [#264940](https://github.com/microsoft/vscode/issues/264940) | No way to read full text in coding agent card | 0 | backlog-candidate | 0 | `npm run implement -- --issue 264940` |
| 92 | [#290872](https://github.com/microsoft/vscode/issues/290872) | Cloud Session: Checkout and Apply still show when checking out the branch | 0 | active | 0 | `npm run implement -- --issue 290872` |
| 94 | [#302393](https://github.com/microsoft/vscode/issues/302393) | Allow tool confirmations for specific arguments | 0 | backlog-candidate | 0 | `npm run implement -- --issue 302393` |
| 95 | [#306268](https://github.com/microsoft/vscode/issues/306268) | Show all approved command with arguments even though the command tool is approved completely | 0 | backlog-candidate | 0 | `npm run implement -- --issue 306268` |

### Comments workflow (24)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 20 | [#151950](https://github.com/microsoft/vscode/issues/151950) | Workbench decorations for files with comments | 37 | backlog-candidate | 3 | `npm run implement -- --issue 151950` |
| 32 | [#282681](https://github.com/microsoft/vscode/issues/282681) | Filter out 'outdated' comments | 12 | backlog-candidate | 2 | `npm run implement -- --issue 282681` |
| 34 | [#147251](https://github.com/microsoft/vscode/issues/147251) | Allow comment UI to be triggered via a clickable icon in the gutter | 10 | backlog-candidate | 1 | `npm run implement -- --issue 147251` |
| 38 | [#160197](https://github.com/microsoft/vscode/issues/160197) | Comments: Go to Next Comment Thread *in Files* | 5 | backlog-candidate | 1 | `npm run implement -- --issue 160197` |
| 39 | [#197939](https://github.com/microsoft/vscode/issues/197939) | Let extensions configure the "Start Discussion" for new comments | 5 | backlog-candidate | 1 | `npm run implement -- --issue 197939` |
| 44 | [#192129](https://github.com/microsoft/vscode/issues/192129) | Provide diff view inside comment card to preview suggested edits | 4 | backlog-candidate | 0 | `npm run implement -- --issue 192129` |
| 46 | [#171166](https://github.com/microsoft/vscode/issues/171166) | Add a notion of pending / draft state to code review comments | 3 | dormant | 0 | `npm run implement -- --issue 171166` |
| 50 | [#131420](https://github.com/microsoft/vscode/issues/131420) | Add context key for when comments are visible | 2 | dormant | 0 | `npm run implement -- --issue 131420` |
| 52 | [#206898](https://github.com/microsoft/vscode/issues/206898) | Add context menu to comments in comments panel to un/resolve conversation | 2 | backlog-candidate | 0 | `npm run implement -- --issue 206898` |
| 57 | [#144850](https://github.com/microsoft/vscode/issues/144850) | Explore cell level commenting in notebooks | 1 | backlog-candidate | 0 | `npm run implement -- --issue 144850` |
| 58 | [#201131](https://github.com/microsoft/vscode/issues/201131) | Include reactor information in comment reaction information | 1 | backlog-candidate | 0 | `npm run implement -- --issue 201131` |
| 64 | [#110391](https://github.com/microsoft/vscode/issues/110391) | Reveal comments in diff editor when navigating with the keyboard | 0 | backlog-candidate | 0 | `npm run implement -- --issue 110391` |
| 67 | [#151533](https://github.com/microsoft/vscode/issues/151533) | Context menu for comment threads | 0 | backlog-candidate | 0 | `npm run implement -- --issue 151533` |
| 68 | [#153494](https://github.com/microsoft/vscode/issues/153494) | Copy vscode.dev Link for modified documents | 0 | backlog-candidate | 0 | `npm run implement -- --issue 153494` |
| 69 | [#153562](https://github.com/microsoft/vscode/issues/153562) | Expose hiding/showing all comments in context menu of gutter | 0 | backlog-candidate | 0 | `npm run implement -- --issue 153562` |
| 70 | [#168431](https://github.com/microsoft/vscode/issues/168431) | Progress location for comments | 0 | dormant | 0 | `npm run implement -- --issue 168431` |
| 72 | [#169737](https://github.com/microsoft/vscode/issues/169737) | Allow extensions to set the body of the new comment editor | 0 | dormant | 0 | `npm run implement -- --issue 169737` |
| 75 | [#185551](https://github.com/microsoft/vscode/issues/185551) | Flicker When Opening A File/Diff From A PR | 0 | backlog-candidate | 0 | `npm run implement -- --issue 185551` |
| 78 | [#196582](https://github.com/microsoft/vscode/issues/196582) | Comments sync/resume is flaky and has unexpected UX | 0 | backlog-candidate | 0 | `npm run implement -- --issue 196582` |
| 79 | [#204484](https://github.com/microsoft/vscode/issues/204484) | API to find the active comment thread | 0 | backlog-candidate | 0 | `npm run implement -- --issue 204484` |
| 80 | [#207402](https://github.com/microsoft/vscode/issues/207402) | Display outdated comments differently in the Comments view | 0 | backlog-candidate | 0 | `npm run implement -- --issue 207402` |
| 82 | [#226092](https://github.com/microsoft/vscode/issues/226092) | [Accessibility] Support audio cue for commented range | 0 | dormant | 0 | `npm run implement -- --issue 226092` |
| 88 | [#266727](https://github.com/microsoft/vscode/issues/266727) | Ctrl+click to Collaps all discuss thread in editor | 0 | backlog-candidate | 0 | `npm run implement -- --issue 266727` |
| 90 | [#275360](https://github.com/microsoft/vscode/issues/275360) | Clone a repro when opening a PR | 0 | backlog-candidate | 0 | `npm run implement -- --issue 275360` |

### File decorations (2)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 31 | [#182098](https://github.com/microsoft/vscode/issues/182098) | Support setting a badge-only color in file decorations | 13 | backlog-candidate | 2 | `npm run implement -- --issue 182098` |
| 33 | [#135591](https://github.com/microsoft/vscode/issues/135591) | Support codicons in file decorations | 10 | backlog-candidate | 2 | `npm run implement -- --issue 135591` |

### Other (7)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 9 | [#209652](https://github.com/microsoft/vscode/issues/209652) | [Feature request] Native VS Code support for GitHub Alerts | 43 | backlog-candidate | 6 | `npm run implement -- --issue 209652` |
| 10 | [#109919](https://github.com/microsoft/vscode/issues/109919) | getLanguageConfiguration() API method is missing | 38 | backlog-candidate | 5 | `npm run implement -- --issue 109919` |
| 47 | [#174941](https://github.com/microsoft/vscode/issues/174941) | Git - extension API gives repository remotes with aliases | 3 | backlog-candidate | 0 | `npm run implement -- --issue 174941` |
| 60 | [#225611](https://github.com/microsoft/vscode/issues/225611) | Add quick fix for npm vulnerabilities | 1 | backlog-candidate | 0 | `npm run implement -- --issue 225611` |
| 71 | [#168963](https://github.com/microsoft/vscode/issues/168963) | Feature Request: Support collapsible markdown | 0 | backlog-candidate | 0 | — |
| 93 | [#292379](https://github.com/microsoft/vscode/issues/292379) | Custom editors: Allow setting different priorities for edit/diff/merge | 0 | backlog-candidate | 0 | `npm run implement -- --issue 292379` |
| 96 | [#307845](https://github.com/microsoft/vscode/issues/307845) | Add an option to disable cursor to the end when opening a file in remote. | 0 | active | 0 | `npm run implement -- --issue 307845` |
