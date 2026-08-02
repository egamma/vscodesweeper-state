# Top issues by theme — amunger

Experimental themed view of [the flat ranking](amunger.md); themes assigned by the review engine. Rank/score are the lane-wide values. Generated 2026-08-02 12:54 UTC.

## Bugs

### Notebook lifecycle (11)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | [#246710](https://github.com/microsoft/vscode/issues/246710) | Hangs forever showing the dialog: "Saving editors with unsaved changes is taking a bit longer...." | 5 | freeze | 3/6 Plausible | 100 | — | — |
| 2 | [#268346](https://github.com/microsoft/vscode/issues/268346) | Kernel disposed because Notebook was closed or Cell was Deleted, when in fact notebook wasn't closed and cell wasn't deleted | 0 | correctness | 3/6 Plausible | 80 | — | — |
| 20 | [#265910](https://github.com/microsoft/vscode/issues/265910) | Saving 7MB notebook takes more than 1 minute | 1 | perf | 3/6 Plausible | 18 | — | — |
| 26 | [#191052](https://github.com/microsoft/vscode/issues/191052) | Inactive notebook editor does not indicate dirty state in this case | 0 | visual | 4/6 Traced | 7 | yes | — |
| 29 | [#211730](https://github.com/microsoft/vscode/issues/211730) | Saving notebook files should happen on extension host by default | 1 | none | — | 5 | — | — |
| 41 | [#210795](https://github.com/microsoft/vscode/issues/210795) | Duplicate untitled notebook is opened | 0 | visual | 3/6 Plausible | 3 | — | — |
| 47 | [#226744](https://github.com/microsoft/vscode/issues/226744) | vscode.dev workbench doesn't allow not saving a file with simple file dialog | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 57 | [#191053](https://github.com/microsoft/vscode/issues/191053) | Multiple untitled notebook editors with same name but different associated path do not distinguish | 0 | visual | 5/6 Source-confirmed | 0 | yes | — |
| 67 | [#234137](https://github.com/microsoft/vscode/issues/234137) | Calling openNotebookDocument with hidden notebook URI creates another untitled*.ipynb with same URI | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 85 | [#321385](https://github.com/microsoft/vscode/issues/321385) | VS Code does not reload modified .ipynb files when stored on external drives and edited on another machine | 0 | correctness | 4/6 Traced | 0 | — | — |
| 87 | [#324300](https://github.com/microsoft/vscode/issues/324300) | Bad UX when auto-save is on (all but "off") | 0 | papercut | 4/6 Traced | 0 | — | — |

### Output rendering (18)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 3 | [#235796](https://github.com/microsoft/vscode/issues/235796) | Re-opening a notebook results in failure to render output with the right renderer | 5 | correctness | 3/6 Plausible | 75 | — | — |
| 10 | [#249176](https://github.com/microsoft/vscode/issues/249176) | Copying notebook HTML output not working for some keyboard shortcuts. | 0 | correctness | 6/6 Confirmed | 30 | — | — |
| 14 | [#228857](https://github.com/microsoft/vscode/issues/228857) | Many output bugs when printing to both STDOUT and STDERR; "There are more than 500 outputs" | 0 | correctness | 4/6 Traced | 24 | — | — |
| 21 | [#254563](https://github.com/microsoft/vscode/issues/254563) | Notebook Cell outputs getting duplicated | 0 | correctness | 3/6 Plausible | 15 | — | — |
| 24 | [#243524](https://github.com/microsoft/vscode/issues/243524) | Latex rendering not working as expected in Python notebook | 0 | correctness | 5/6 Source-confirmed | 10 | yes | — |
| 27 | [#174409](https://github.com/microsoft/vscode/issues/174409) | File links in the error renderer are incorrect | 1 | papercut | 5/6 Source-confirmed | 6 | yes | — |
| 30 | [#223820](https://github.com/microsoft/vscode/issues/223820) | Visual issue when running apache_beam interactive_runner | 1 | visual | 5/6 Source-confirmed | 5 | yes | — |
| 34 | [#190086](https://github.com/microsoft/vscode/issues/190086) | notebook.output.wordWrap does not seem to affect outputs from all Magics | 2 | papercut | 5/6 Source-confirmed | 4 | yes | — |
| 37 | [#257118](https://github.com/microsoft/vscode/issues/257118) | Markdown Code Fences in Notebook Markdown Cells Lack Proper Background Highlighting | 0 | visual | 5/6 Source-confirmed | 4 | yes | — |
| 51 | [#246123](https://github.com/microsoft/vscode/issues/246123) | Internal HTML links jump to the wrong place after clearing output | 0 | correctness | 5/6 Source-confirmed | 2 | — | — |
| 58 | [#191577](https://github.com/microsoft/vscode/issues/191577) | Copy image output is quite slow | 0 | perf | 5/6 Source-confirmed | 0 | yes | — |
| 59 | [#191688](https://github.com/microsoft/vscode/issues/191688) | Current active presentation type is incorrect after changing display style 1st image. | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 61 | [#211069](https://github.com/microsoft/vscode/issues/211069) | Problem rendering in notebooks should use default VS Code workbench font | 0 | visual | 4/6 Traced | 0 | yes | — |
| 70 | [#235780](https://github.com/microsoft/vscode/issues/235780) | javascript output with </script> can close scripts | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 71 | [#236853](https://github.com/microsoft/vscode/issues/236853) | JSON rendering: Crashing on arrays | 0 | correctness | — | 0 | — | — |
| 72 | [#236854](https://github.com/microsoft/vscode/issues/236854) | JSON rendering: Losing syntax coloring after certain size | 0 | visual | 3/6 Plausible | 0 | — | — |
| 78 | [#278657](https://github.com/microsoft/vscode/issues/278657) | Clicking on path in exception traceback shows error on remote Windows | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 84 | [#321289](https://github.com/microsoft/vscode/issues/321289) | Notebook output Font Size/Family are not correct | 0 | visual | 5/6 Source-confirmed | 0 | yes | — |

### Performance and stability (13)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 4 | [#211112](https://github.com/microsoft/vscode/issues/211112) | Large notebook trigger very many leak warnings | 0 | perf | 5/6 Source-confirmed | 61 | — | — |
| 9 | [#224924](https://github.com/microsoft/vscode/issues/224924) | Notebooks check object leaks smoketest failure | 0 | perf | 6/6 Confirmed | 31 | — | — |
| 11 | [#212229](https://github.com/microsoft/vscode/issues/212229) | Uncaught TypeError: Cannot read properties of undefined (reading 'element') | 0 | correctness | 5/6 Source-confirmed | 29 | yes | — |
| 12 | [#259983](https://github.com/microsoft/vscode/issues/259983) | Maximum call stack size exceeded | 0 | crash | 4/6 Traced | 28 | — | — |
| 15 | [#324857](https://github.com/microsoft/vscode/issues/324857) | Intermittent Jupyter Interactive Window Hangs and Extension Host Instability After VS Code Update to 1.127.0 | 0 | none | 3/6 Plausible | 23 | — | — |
| 16 | [#314134](https://github.com/microsoft/vscode/issues/314134) | [Error] unhandlederror-Cannot read properties of null (reading 'domNode') | 0 | crash | 5/6 Source-confirmed | 22 | — | — |
| 19 | [#309922](https://github.com/microsoft/vscode/issues/309922) | [Unhandled Error] potential listener LEAK detected, popular — notebook/codeCellRunToolbar / menuService | 0 | perf | 5/6 Source-confirmed | 20 | yes | — |
| 33 | [#324550](https://github.com/microsoft/vscode/issues/324550) | [Error] unhandlederror-model index out of range 67 (cellCount: 37) | 0 | correctness | 5/6 Source-confirmed | 5 | — | — |
| 38 | [#311022](https://github.com/microsoft/vscode/issues/311022) | [Error] unhandlederror-potential listener LEAK detected, popular | 0 | papercut | 5/6 Source-confirmed | 4 | yes | — |
| 39 | [#177850](https://github.com/microsoft/vscode/issues/177850) | Resizing notebooks locks up the UI thread | 0 | freeze | 3/6 Plausible | 3 | — | — |
| 43 | [#311711](https://github.com/microsoft/vscode/issues/311711) | [Error] unhandlederror-potential listener LEAK detected, popular — onDidChangeExecution / executionStatusBarItemController (note | 0 | perf | 5/6 Source-confirmed | 3 | yes | — |
| 53 | [#260088](https://github.com/microsoft/vscode/issues/260088) | [169] potential listener LEAK detected, having 183 listeners already. MOST frequent listener (8): | 0 | papercut | 4/6 Traced | 1 | — | — |
| 62 | [#211274](https://github.com/microsoft/vscode/issues/211274) | Notebook editor can take a long time to open | 0 | freeze | 3/6 Plausible | 0 | — | — |

### Scrolling and layout (11)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 5 | [#251347](https://github.com/microsoft/vscode/issues/251347) | Notebook Outputs flicker and slow scrolling | 0 | perf | 3/6 Plausible | 59 | — | — |
| 8 | [#239146](https://github.com/microsoft/vscode/issues/239146) | Scrolling in notebooks sucks user back to particular output | 4 | correctness | 3/6 Plausible | 35 | — | — |
| 31 | [#207180](https://github.com/microsoft/vscode/issues/207180) | misalignment on border of markdown cell | 0 | visual | 3/6 Plausible | 5 | — | — |
| 32 | [#207547](https://github.com/microsoft/vscode/issues/207547) | Clicking on an output and using Up/Down arrows scrolls through cells of another notebook | 0 | correctness | 5/6 Source-confirmed | 5 | yes | — |
| 35 | [#240391](https://github.com/microsoft/vscode/issues/240391) | Jump-scrolling after search | 1 | papercut | 5/6 Source-confirmed | 4 | — | — |
| 44 | [#157059](https://github.com/microsoft/vscode/issues/157059) | Input box does not render correctly after word wrap | 0 | visual | 3/6 Plausible | 2 | — | — |
| 45 | [#177848](https://github.com/microsoft/vscode/issues/177848) | Scrollable output scroll bar should use default cursor | 0 | papercut | 3/6 Plausible | 2 | — | — |
| 52 | [#200981](https://github.com/microsoft/vscode/issues/200981) | Notebooks scroll annoyingly | 0 | papercut | 3/6 Plausible | 1 | — | — |
| 55 | [#177851](https://github.com/microsoft/vscode/issues/177851) | Find in notebooks makes the notebook global scroll bar scroll when scrolling a cell output's scrollbar | 0 | papercut | 4/6 Traced | 0 | — | — |
| 56 | [#178371](https://github.com/microsoft/vscode/issues/178371) | Output and editor scroll at the same time on Safari | 0 | visual | 3/6 Plausible | 0 | — | — |
| 86 | [#323775](https://github.com/microsoft/vscode/issues/323775) | The right-side panel blocks context menu | 0 | visual | 3/6 Plausible | 0 | — | — |

### Accessibility and localization (5)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 6 | [#283001](https://github.com/microsoft/vscode/issues/283001) | The 'More actions' control cannot be accessed using voice commands such as Show number, Click, Focus, or Move to within the code editor pane.: A11y_VSCode_VoiceAccess | 0 | correctness | 6/6 Confirmed | 53 | — | — |
| 36 | [#251043](https://github.com/microsoft/vscode/issues/251043) | Accessible diff viewer up/down focuses out of accessible diff view | 0 | correctness | 5/6 Source-confirmed | 4 | yes | — |
| 65 | [#231505](https://github.com/microsoft/vscode/issues/231505) | Chinese not fully supported. | 0 | none | — | 0 | — | — |
| 68 | [#235426](https://github.com/microsoft/vscode/issues/235426) | Can barely make out interactive window export icon on standard density monitor | 0 | visual | — | 0 | — | — |
| 82 | [#320851](https://github.com/microsoft/vscode/issues/320851) | Delete Cell button is not accessible using arrow key navigation in notebook toolbar:A11y_Visual Studio Code Jupyter Extensions_Home_Keyboard | 0 | papercut | 5/6 Source-confirmed | 0 | yes | — |

### Chat and agents (9)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 7 | [#314579](https://github.com/microsoft/vscode/issues/314579) | Copilot->Claude often claims to edit a notebook but fails | 2 | correctness | 3/6 Plausible | 52 | — | — |
| 22 | [#319237](https://github.com/microsoft/vscode/issues/319237) | Agents: Session token expiration disrupts agent sessions | 0 | correctness | 3/6 Plausible | 12 | — | — |
| 28 | [#317735](https://github.com/microsoft/vscode/issues/317735) | Pylance errors from chat virtual documents | 0 | correctness | 5/6 Source-confirmed | 6 | — | — |
| 42 | [#254541](https://github.com/microsoft/vscode/issues/254541) | Cant close text box after code is generated | 0 | papercut | 3/6 Plausible | 3 | — | — |
| 74 | [#258301](https://github.com/microsoft/vscode/issues/258301) | inline chat pushes cell content out of cell view | 0 | visual | 3/6 Plausible | 0 | — | — |
| 75 | [#258703](https://github.com/microsoft/vscode/issues/258703) | Inline chat breaks when you ask it to edit a cell outside of the viewport, then scroll around | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 77 | [#270046](https://github.com/microsoft/vscode/issues/270046) | pressing ctrl+enter while focused on notebook inline chat should keep focus in the chat | 0 | papercut | 4/6 Traced | 0 | yes | — |
| 81 | [#320210](https://github.com/microsoft/vscode/issues/320210) | Notebook Generate ignores extension-contributed chatInstructions | 0 | correctness | 6/6 Confirmed | 0 | — | — |
| 88 | [#327470](https://github.com/microsoft/vscode/issues/327470) | runNotebookCell a cell that generates audio takes up a lot of context | 0 | perf | 4/6 Traced | 0 | yes | — |

### Cell editing and commands (10)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 13 | [#325990](https://github.com/microsoft/vscode/issues/325990) | vs.commands.executeCommand("vscode.executeCodeActionProvider") loses keepWhitespace field from SnippetTextEdits | 0 | correctness | 5/6 Source-confirmed | 26 | yes | — |
| 17 | [#120370](https://github.com/microsoft/vscode/issues/120370) | Can not select text in markdown cell | 6 | papercut | 5/6 Source-confirmed | 21 | — | — |
| 46 | [#197952](https://github.com/microsoft/vscode/issues/197952) | Jupyter cell line numbers don't match error message line numbers | 0 | papercut | 6/6 Confirmed | 2 | — | — |
| 48 | [#232753](https://github.com/microsoft/vscode/issues/232753) | arrow navigation diff view will go to prev/next cell | 0 | correctness | 5/6 Source-confirmed | 2 | yes | — |
| 50 | [#240436](https://github.com/microsoft/vscode/issues/240436) | DocumentDropEditProvider does not work with notebooks | 0 | correctness | 5/6 Source-confirmed | 2 | — | — |
| 54 | [#284327](https://github.com/microsoft/vscode/issues/284327) | monaco editor should disable line-number manipulating API | 0 | visual | 5/6 Source-confirmed | 1 | yes | — |
| 63 | [#225980](https://github.com/microsoft/vscode/issues/225980) | Cannot move cell when change the window.zoomLevel | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 76 | [#269221](https://github.com/microsoft/vscode/issues/269221) | diff is always +0 -0 for notebook edits | 0 | visual | 3/6 Plausible | 0 | — | — |
| 80 | [#298205](https://github.com/microsoft/vscode/issues/298205) | Format Cell not work | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 83 | [#321157](https://github.com/microsoft/vscode/issues/321157) | Notebook: "Run Cells In Section" (notebook.section.runCells) does nothing when invoked via keybinding | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |

### Variables and symbols (4)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 18 | [#210704](https://github.com/microsoft/vscode/issues/210704) | Code symbols in Notebook outline is not when the text in a code cell is updated | 0 | correctness | 5/6 Source-confirmed | 20 | yes | — |
| 60 | [#203067](https://github.com/microsoft/vscode/issues/203067) | Persist variable expansion state through variable update events in notebook variables view | 0 | visual | 5/6 Source-confirmed | 0 | yes | — |
| 66 | [#233917](https://github.com/microsoft/vscode/issues/233917) | variables view is not working as expected | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 73 | [#244390](https://github.com/microsoft/vscode/issues/244390) | Notebook Variables displays large number keys incorrectly | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |

### Interactive window and REPL (7)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 23 | [#160442](https://github.com/microsoft/vscode/issues/160442) | De-Indent code on paste into IW code cell | 4 | papercut | 3/6 Plausible | 11 | — | — |
| 25 | [#269627](https://github.com/microsoft/vscode/issues/269627) | Line breaks for multi-line comments in Markdown cells are broken (interactive Python) | 1 | correctness | 3/6 Plausible | 9 | — | — |
| 40 | [#187616](https://github.com/microsoft/vscode/issues/187616) | Scrollback position toggle in Interactive Window | 0 | papercut | 4/6 Traced | 3 | yes | — |
| 49 | [#238603](https://github.com/microsoft/vscode/issues/238603) | Dragging and dropping cells in Python REPL does not work. | 0 | visual | 5/6 Source-confirmed | 2 | yes | — |
| 64 | [#229737](https://github.com/microsoft/vscode/issues/229737) | repl multi-line input shrinks to 1 line after reloading editor | 0 | visual | 5/6 Source-confirmed | 0 | yes | — |
| 69 | [#235427](https://github.com/microsoft/vscode/issues/235427) | Actives disappear when focusing between a notebook, interactive window and native REPL | 0 | visual | 3/6 Plausible | 0 | — | — |
| 79 | [#283718](https://github.com/microsoft/vscode/issues/283718) | Copilot in REPL: Cursor up/down affects last cell instead of navigating chat history | 0 | papercut | 3/6 Plausible | 0 | — | — |

## Feature requests

### Notebook extension APIs (3)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | [#311289](https://github.com/microsoft/vscode/issues/311289) | API: Allow access to the notebook editor scroll state | 26 | backlog-candidate | 100 | — |
| 27 | [#208864](https://github.com/microsoft/vscode/issues/208864) | Support cell output toolbar contribution | 0 | dormant | 0 | — |
| 28 | [#209137](https://github.com/microsoft/vscode/issues/209137) | Consider notebook status `window.title` property | 0 | active | 0 | — |

### Interactive window and REPL (5)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 2 | [#127998](https://github.com/microsoft/vscode/issues/127998) | Interactive Window at the bottom of the screen | 24 | backlog-candidate | 25 | — |
| 3 | [#183350](https://github.com/microsoft/vscode/issues/183350) | Show outputs below cells during interactive sessions | 23 | backlog-candidate | 25 | — |
| 10 | [#154983](https://github.com/microsoft/vscode/issues/154983) | API request - Support interactive window natively | 2 | dormant | 7 | — |
| 22 | [#225736](https://github.com/microsoft/vscode/issues/225736) | Allow multi-select for REPL / interactive window | 1 | backlog-candidate | 1 | — |
| 33 | [#254752](https://github.com/microsoft/vscode/issues/254752) | API for kernel selection in REPL editors (SetReplKernelAffinity) | 0 | dormant | 0 | — |

### Output layout and scrolling (8)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 4 | [#175295](https://github.com/microsoft/vscode/issues/175295) | A "tight layout" mode that reduces vertical spacing | 18 | backlog-candidate | 24 | — |
| 7 | [#190426](https://github.com/microsoft/vscode/issues/190426) | Set output height limit and scrolling for non-text stream outputs | 10 | active | 12 | — |
| 8 | [#228927](https://github.com/microsoft/vscode/issues/228927) | Making all the code-cell outputs scrollable | 7 | backlog-candidate | 10 | — |
| 13 | [#204961](https://github.com/microsoft/vscode/issues/204961) | Custom keybindings for scrolling notebook cell output into view and for scrolling inside the focussed cell output | 5 | backlog-candidate | 4 | — |
| 19 | [#130287](https://github.com/microsoft/vscode/issues/130287) | Controlling vertical space between output elements. | 2 | backlog-candidate | 2 | — |
| 21 | [#174917](https://github.com/microsoft/vscode/issues/174917) | Notebook cells should be resizable | 1 | dormant | 1 | — |
| 24 | [#325786](https://github.com/microsoft/vscode/issues/325786) | Make notebook cell output item limit (500) configurable via setting | 0 | active | 1 | — |
| 31 | [#238214](https://github.com/microsoft/vscode/issues/238214) | Jupyter Notebook: Affordance to display cell output of long cells | 0 | backlog-candidate | 0 | — |

### Output rendering (3)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 5 | [#203725](https://github.com/microsoft/vscode/issues/203725) | LaTeX not rendering in cell text/html encoded outputs when embedded inside html | 9 | backlog-candidate | 16 | — |
| 6 | [#118833](https://github.com/microsoft/vscode/issues/118833) | Notebook output must support more ANSI sequences | 3 | backlog-candidate | 14 | — |
| 37 | [#326331](https://github.com/microsoft/vscode/issues/326331) | feature: webview without service workers | 0 | active | 0 | — |

### Notebook chat context (6)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 9 | [#259904](https://github.com/microsoft/vscode/issues/259904) | "allow for session" in notebook inline chat should allow for that notebook until it is closed | 0 | dormant | 8 | — |
| 12 | [#283947](https://github.com/microsoft/vscode/issues/283947) | Include extension info in chat session export | 0 | active | 5 | — |
| 14 | [#283950](https://github.com/microsoft/vscode/issues/283950) | Include vscode settings in artifacts produced by chat session export | 0 | active | 4 | — |
| 32 | [#251629](https://github.com/microsoft/vscode/issues/251629) | reference large interactive cell outputs in chat | 0 | dormant | 0 | — |
| 34 | [#283206](https://github.com/microsoft/vscode/issues/283206) | Auto-include Interactive Window cell output in context | 0 | dormant | 0 | — |
| 35 | [#283715](https://github.com/microsoft/vscode/issues/283715) | Include variable shape info when asking agent to make edits | 0 | dormant | 0 | — |

### Variable inspection (4)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 11 | [#166296](https://github.com/microsoft/vscode/issues/166296) | Notebook "variable provider" API | 1 | backlog-candidate | 7 | — |
| 16 | [#208865](https://github.com/microsoft/vscode/issues/208865) | Support filtering in builtin notebook variable view | 0 | dormant | 3 | — |
| 17 | [#209153](https://github.com/microsoft/vscode/issues/209153) | Notebook Variable View not expaned by default | 0 | backlog-candidate | 3 | — |
| 23 | [#204031](https://github.com/microsoft/vscode/issues/204031) | Don't link the variable viewer to just notebooks | 0 | dormant | 1 | — |

### Notebook accessibility (6)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 15 | [#189362](https://github.com/microsoft/vscode/issues/189362) | [Accessibility] Display cell index number in Accessible View for Jupyter Notebook output | 3 | backlog-candidate | 3 | — |
| 20 | [#195581](https://github.com/microsoft/vscode/issues/195581) | [Accessibility] Accessible View does not get dynamically updated in Jupyter Notebook cell output | 1 | backlog-candidate | 2 | — |
| 25 | [#188535](https://github.com/microsoft/vscode/issues/188535) | Allow navigation between output cells in notebooks in the accessible view | 0 | dormant | 0 | — |
| 26 | [#202615](https://github.com/microsoft/vscode/issues/202615) | indicate when action appears/ status changes to screen reader users | 0 | dormant | 0 | — |
| 29 | [#209138](https://github.com/microsoft/vscode/issues/209138) | Include more notebook toolbar actions in accessibility help dialog | 0 | backlog-candidate | 0 | — |
| 30 | [#211288](https://github.com/microsoft/vscode/issues/211288) | notebook progress accessibility signal refinement suggestions | 0 | dormant | 0 | — |

### Cell editing and identity (2)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 18 | [#230736](https://github.com/microsoft/vscode/issues/230736) | Support Ghost Cells In Notebooks - Insert Cells In Edit Mode | 0 | active | 3 | — |
| 36 | [#325910](https://github.com/microsoft/vscode/issues/325910) | Display Jupyter Cell ID | 0 | active | 0 | — |
