# Top issues by theme — aiday-mar

Experimental themed view of [the flat ranking](aiday-mar.md); themes assigned by the review engine. Rank/score are the lane-wide values. Generated 2026-08-03 15:10 UTC.

## Bugs

### Clipboard and paste (12)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | [#252371](https://github.com/microsoft/vscode/issues/252371) | Copy and paste not working | 107 | correctness | 6/6 Confirmed | 100 | — | — |
| 2 | [#299786](https://github.com/microsoft/vscode/issues/299786) | paste is slow with copilot | 24 | perf | 6/6 Confirmed | 26 | — | — |
| 7 | [#239500](https://github.com/microsoft/vscode/issues/239500) | Copy-paste does not work randomly | 5 | correctness | 3/6 Plausible | 8 | — | — |
| 16 | [#286892](https://github.com/microsoft/vscode/issues/286892) | Multiple cursors empty copy does not paste in line above | 0 | correctness | 5/6 Source-confirmed | 3 | yes | — |
| 23 | [#249508](https://github.com/microsoft/vscode/issues/249508) | Can't copy the whole line if there is a null character in it. When trying to copy the entire line, only the part before the null character is copied. | 2 | correctness | 5/6 Source-confirmed | 2 | yes | — |
| 34 | [#293314](https://github.com/microsoft/vscode/issues/293314) | Copy Paste Not Working with Keyboard | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 36 | [#221574](https://github.com/microsoft/vscode/issues/221574) | Copy paste indent | 4 | papercut | — | 1 | — | — |
| 47 | [#246719](https://github.com/microsoft/vscode/issues/246719) | Copying with empty selection clears the clipboard when editor.emptySelectionClipboard=false in Web mode | 1 | correctness | 5/6 Source-confirmed | 1 | yes | — |
| 67 | [#274154](https://github.com/microsoft/vscode/issues/274154) | copy text, delete text, pastes different text that is now in the location where old text was | 0 | correctness | 5/6 Source-confirmed | 1 | — | — |
| 114 | [#230320](https://github.com/microsoft/vscode/issues/230320) | Pasting a large amount of content in a json file will leave the cursor in the middle of the pasted content | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 128 | [#243932](https://github.com/microsoft/vscode/issues/243932) | `editor.action.clipboardCopyAction` command no longer works | 0 | correctness | 6/6 Confirmed | 0 | — | — |
| 144 | [#269442](https://github.com/microsoft/vscode/issues/269442) | Copying can replace new lines with another char | 0 | papercut | 3/6 Plausible | 0 | — | — |

### Indentation rules (66)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 3 | [#243100](https://github.com/microsoft/vscode/issues/243100) | Automatic indentation doesn't work well with C/C++ | 22 | correctness | 5/6 Source-confirmed | 16 | — | — |
| 4 | [#43244](https://github.com/microsoft/vscode/issues/43244) | Incorrect indentation for single line if/for/while/etc, multiline chaining statements etc | 45 | none | — | 11 | — | — |
| 6 | [#125261](https://github.com/microsoft/vscode/issues/125261) | Leading whitespace before bracket/brace should not be automatically removed | 21 | correctness | 5/6 Source-confirmed | 8 | yes | — |
| 9 | [#63388](https://github.com/microsoft/vscode/issues/63388) | Indent/Outdent with tab key does not honor editor.autoIndent=false | 13 | correctness | 5/6 Source-confirmed | 6 | yes | — |
| 11 | [#184700](https://github.com/microsoft/vscode/issues/184700) | Alignment is incorrectly replaced by tabs | 6 | correctness | 5/6 Source-confirmed | 4 | — | — |
| 12 | [#241370](https://github.com/microsoft/vscode/issues/241370) | Incorrect indentation after C multi-line comment blocks | 5 | correctness | 5/6 Source-confirmed | 4 | — | — |
| 14 | [#240882](https://github.com/microsoft/vscode/issues/240882) | Indentation on pasting with multiple lines of code not working as expected | 3 | correctness | 5/6 Source-confirmed | 3 | yes | — |
| 19 | [#57197](https://github.com/microsoft/vscode/issues/57197) | Identation rules are broken | 3 | correctness | 4/6 Traced | 2 | — | — |
| 20 | [#178334](https://github.com/microsoft/vscode/issues/178334) | Weird code indentation C++ | 2 | correctness | 5/6 Source-confirmed | 2 | — | — |
| 21 | [#224569](https://github.com/microsoft/vscode/issues/224569) | Auto indent when move line up or down | 2 | correctness | 5/6 Source-confirmed | 2 | — | — |
| 28 | [#255500](https://github.com/microsoft/vscode/issues/255500) | Reindent Lines doesn't work when the line has no initial indent | 1 | correctness | 5/6 Source-confirmed | 2 | yes | — |
| 29 | [#223606](https://github.com/microsoft/vscode/issues/223606) | Auto indent issue: Lua multiline quotes `[[...]]` conflict with #210641 which removes brackets before passing text to indent rules | 0 | correctness | 5/6 Source-confirmed | 2 | — | — |
| 30 | [#256037](https://github.com/microsoft/vscode/issues/256037) | Auto indent is wrong when adding brackets sometimes | 0 | correctness | — | 2 | — | — |
| 35 | [#174667](https://github.com/microsoft/vscode/issues/174667) | Wrong indent level after `break;` in a switch statement PHP | 6 | papercut | 5/6 Source-confirmed | 1 | — | — |
| 37 | [#187944](https://github.com/microsoft/vscode/issues/187944) | `editor.detectIndentation` produces incorrect values for empty files when `editor.insertSpaces` is `true` | 3 | correctness | 5/6 Source-confirmed | 1 | yes | — |
| 38 | [#111265](https://github.com/microsoft/vscode/issues/111265) | Typing } changes the indentation (autoIndent "none" doesn't work) | 2 | correctness | 5/6 Source-confirmed | 1 | yes | — |
| 43 | [#213598](https://github.com/microsoft/vscode/issues/213598) | Move Line Up and Move Line Down breaks indentation in Javascript/Typescript files | 1 | correctness | 5/6 Source-confirmed | 1 | — | — |
| 45 | [#241011](https://github.com/microsoft/vscode/issues/241011) | Moving a line down in Go code messes up indentation in VS Code | 1 | correctness | 5/6 Source-confirmed | 1 | — | — |
| 46 | [#245610](https://github.com/microsoft/vscode/issues/245610) | Alt Down Arrow to move */ comment is reformatting code | 1 | correctness | 5/6 Source-confirmed | 1 | — | — |
| 48 | [#247477](https://github.com/microsoft/vscode/issues/247477) | incorrect append double slash text while onEnter called | 1 | correctness | 2/6 Unverified | 1 | — | — |
| 49 | [#278311](https://github.com/microsoft/vscode/issues/278311) | Auto-indent mangles JSON files due to URL misinterpretation | 1 | correctness | 2/6 Unverified | 1 | — | — |
| 50 | [#285222](https://github.com/microsoft/vscode/issues/285222) | `editor.autoIndentOnPaste` doesn't work if the initial line is already correctly indented | 1 | correctness | 5/6 Source-confirmed | 1 | yes | — |
| 52 | [#324412](https://github.com/microsoft/vscode/issues/324412) | Sticky scroll indentationModel doesn't work if no line is present after the indented block | 1 | correctness | 5/6 Source-confirmed | 1 | yes | — |
| 53 | [#325904](https://github.com/microsoft/vscode/issues/325904) | Doubling of indentation when pasting code. | 1 | correctness | 6/6 Confirmed | 1 | — | — |
| 56 | [#61510](https://github.com/microsoft/vscode/issues/61510) | VS Code changes indention of current line | 0 | correctness | 2/6 Unverified | 1 | — | — |
| 57 | [#188246](https://github.com/microsoft/vscode/issues/188246) | incorrect indentation detection | 0 | correctness | 5/6 Source-confirmed | 1 | yes | — |
| 58 | [#219821](https://github.com/microsoft/vscode/issues/219821) | Indent using spaces function does not convert tabs to spaces in mixed indentation text content | 0 | none | — | 1 | — | — |
| 61 | [#244880](https://github.com/microsoft/vscode/issues/244880) | Bug with auto-indent rule: "onEnterRules" + "indentOutdent" + "AppendText" do not insert indentation and string at the END as expected. | 0 | correctness | 5/6 Source-confirmed | 1 | yes | — |
| 62 | [#250722](https://github.com/microsoft/vscode/issues/250722) | C# wrong extra indentation in latest release | 0 | correctness | 5/6 Source-confirmed | 1 | — | — |
| 68 | [#276614](https://github.com/microsoft/vscode/issues/276614) | auto-indenting and line spacing issues | 0 | correctness | 4/6 Traced | 1 | — | — |
| 70 | [#287498](https://github.com/microsoft/vscode/issues/287498) | PHP autoindent behavior is broken (since 1.108) | 0 | correctness | 5/6 Source-confirmed | 1 | — | — |
| 77 | [#88638](https://github.com/microsoft/vscode/issues/88638) | Moving lines of code up and down breaks indentation | 2 | papercut | 5/6 Source-confirmed | 0 | — | — |
| 80 | [#176982](https://github.com/microsoft/vscode/issues/176982) | Json sort command does not honor indentation with tabs | 1 | correctness | 2/6 Unverified | 0 | — | — |
| 82 | [#209019](https://github.com/microsoft/vscode/issues/209019) | Wrong indentation when editing text block in Python | 1 | papercut | 5/6 Source-confirmed | 0 | — | — |
| 83 | [#218255](https://github.com/microsoft/vscode/issues/218255) | jsx auto indentation not corrent | 1 | papercut | 3/6 Plausible | 0 | — | — |
| 84 | [#221362](https://github.com/microsoft/vscode/issues/221362) | BUG: `Move line down` command doesnt preserve indentation | 1 | papercut | 5/6 Source-confirmed | 0 | — | — |
| 85 | [#223308](https://github.com/microsoft/vscode/issues/223308) | Wrong auto-indentation in typescript when pasting | 1 | papercut | 4/6 Traced | 0 | — | — |
| 86 | [#242029](https://github.com/microsoft/vscode/issues/242029) | Something Wrong with the Auto Indent? | 1 | papercut | 3/6 Plausible | 0 | — | — |
| 89 | [#309962](https://github.com/microsoft/vscode/issues/309962) | "detect indentation" has precedence over "change tab display size" | 1 | papercut | — | 0 | — | — |
| 91 | [#29589](https://github.com/microsoft/vscode/issues/29589) | Auto indent on pasting does not satisfy indentation for braces in JS/TS | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 92 | [#85781](https://github.com/microsoft/vscode/issues/85781) | JavaScript: Improve indentation on insert with trailing newline | 0 | none | — | 0 | — | — |
| 96 | [#174044](https://github.com/microsoft/vscode/issues/174044) | Latest update broke automatic whitespace | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 97 | [#174484](https://github.com/microsoft/vscode/issues/174484) | Indentations of curly braces becomes wrong after moving a current line up or down | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 98 | [#178075](https://github.com/microsoft/vscode/issues/178075) | De-indentation breaks pair autoclosing | 0 | correctness | 4/6 Traced | 0 | yes | — |
| 100 | [#193875](https://github.com/microsoft/vscode/issues/193875) | Nested for statements in JavaScript breaks in wrong indention | 0 | papercut | 4/6 Traced | 0 | — | — |
| 102 | [#199050](https://github.com/microsoft/vscode/issues/199050) | Unexpected indentation added on new line if a string contains a '{' | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 103 | [#199223](https://github.com/microsoft/vscode/issues/199223) | Using 'function' in a Lua string causes wrong indentation | 0 | papercut | 5/6 Source-confirmed | 0 | yes | — |
| 104 | [#199846](https://github.com/microsoft/vscode/issues/199846) | Auto indent for Ruby language's block is not performed If a string include "#" is used as the method argument. | 0 | papercut | 5/6 Source-confirmed | 0 | — | — |
| 105 | [#202942](https://github.com/microsoft/vscode/issues/202942) | Wrong indent detected with PHP comments | 0 | papercut | 4/6 Traced | 0 | — | — |
| 106 | [#204435](https://github.com/microsoft/vscode/issues/204435) | on-enter rule not applying on reload | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 107 | [#209521](https://github.com/microsoft/vscode/issues/209521) | [Bug]: Incorrect indentation when object nested inline on the same line as parent object | 0 | correctness | — | 0 | — | — |
| 108 | [#209537](https://github.com/microsoft/vscode/issues/209537) | [Bug]: Incorrect outdentation when several closing braces are found on the same line | 0 | correctness | — | 0 | — | — |
| 109 | [#209539](https://github.com/microsoft/vscode/issues/209539) | [Bug]: Incorrect indentation when there is text before the closing brace | 0 | papercut | — | 0 | — | — |
| 112 | [#221444](https://github.com/microsoft/vscode/issues/221444) | Minor indentation inconsistency - trimAutoWhitespace - difference between tab and shift-tab | 0 | papercut | 5/6 Source-confirmed | 0 | yes | — |
| 113 | [#227218](https://github.com/microsoft/vscode/issues/227218) | Bad line move indentation adjustment | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 116 | [#232125](https://github.com/microsoft/vscode/issues/232125) | Shortcuts for auto indentation not working | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 117 | [#233700](https://github.com/microsoft/vscode/issues/233700) | Unexpected indentation | 0 | correctness | — | 0 | — | — |
| 119 | [#234925](https://github.com/microsoft/vscode/issues/234925) | When using alt+up/down arrow to move code, indentation does not apply | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 121 | [#236138](https://github.com/microsoft/vscode/issues/236138) | Incorrect indentation for TypeScript opening curly brace | 0 | papercut | 5/6 Source-confirmed | 0 | — | — |
| 124 | [#240023](https://github.com/microsoft/vscode/issues/240023) | Indent/unindent reformats code when I don't want it to | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 129 | [#244021](https://github.com/microsoft/vscode/issues/244021) | Auto-indent of switch-case is idiotic | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 132 | [#248227](https://github.com/microsoft/vscode/issues/248227) | PHP Autoindent is stupid | 0 | papercut | 5/6 Source-confirmed | 0 | — | — |
| 136 | [#251676](https://github.com/microsoft/vscode/issues/251676) | Moving Row Using ALT + Up/Down Arrow Key Cause an Issue with the Code Indentation | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 146 | [#275676](https://github.com/microsoft/vscode/issues/275676) | bad auto-indenting | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 149 | [#282400](https://github.com/microsoft/vscode/issues/282400) | auto indent error | 0 | papercut | 5/6 Source-confirmed | 0 | — | — |
| 156 | [#299080](https://github.com/microsoft/vscode/issues/299080) | JS: Incorrect indentation after comment line | 0 | papercut | 3/6 Plausible | 0 | — | — |

### IME and input (21)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 5 | [#96041](https://github.com/microsoft/vscode/issues/96041) | unable to input chinese character | 21 | correctness | 6/6 Confirmed | 9 | — | — |
| 18 | [#244096](https://github.com/microsoft/vscode/issues/244096) | Duplicated Last Character when Typing Korean in VSCode with Windows 11 and New IME | 4 | correctness | 3/6 Plausible | 2 | — | — |
| 25 | [#271715](https://github.com/microsoft/vscode/issues/271715) | Incorrect text input when using multi-cursor with Japanese IME | 2 | correctness | 5/6 Source-confirmed | 2 | — | — |
| 26 | [#181138](https://github.com/microsoft/vscode/issues/181138) | Japanese IME recomposition broken in Windows Desktop App & Firefox + vscode.dev | 1 | correctness | 3/6 Plausible | 2 | — | — |
| 27 | [#229606](https://github.com/microsoft/vscode/issues/229606) | ASCII characters should not be part of the editing undo/redo stack | 1 | correctness | 5/6 Source-confirmed | 2 | — | — |
| 31 | [#282790](https://github.com/microsoft/vscode/issues/282790) | IME composition corrupts text during multi-cursor editing | 0 | correctness | 5/6 Source-confirmed | 2 | — | — |
| 63 | [#255637](https://github.com/microsoft/vscode/issues/255637) | CTRL + Key commands don't work well on Android with physical keyboard. Deleting a piece of text crashes the browser | 0 | crash | 6/6 Confirmed | 1 | — | — |
| 69 | [#282276](https://github.com/microsoft/vscode/issues/282276) | In Firefox, an extra keystroke is required when replacing text in the editor | 0 | correctness | 4/6 Traced | 1 | — | — |
| 76 | [#303452](https://github.com/microsoft/vscode/issues/303452) | Hebrew content are shown correctly in VScode editor, but not in other view. | 0 | visual | 3/6 Plausible | 1 | — | — |
| 126 | [#243334](https://github.com/microsoft/vscode/issues/243334) | When pressing the kana input button twice in succession on a Mac and trying to convert characters, the number of selected characters increases. | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 127 | [#243844](https://github.com/microsoft/vscode/issues/243844) | Inserting backslash on Japanese romaji keyboard conflicts with keyboard shortcut for triggering inline suggestion | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 130 | [#245972](https://github.com/microsoft/vscode/issues/245972) | Mac US International Keyboard auto closing quotes not working | 0 | correctness | 4/6 Traced | 0 | yes | — |
| 133 | [#248467](https://github.com/microsoft/vscode/issues/248467) | Autocompletion doesn't work to hyperlink Korean title | 0 | correctness | 6/6 Confirmed | 0 | — | — |
| 139 | [#254382](https://github.com/microsoft/vscode/issues/254382) | The column number calculation in the status bar has issues when meeting the full-width characters and emoji characters | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 143 | [#268442](https://github.com/microsoft/vscode/issues/268442) | Weird bug when closing the auto quotation double quotes in any HTML file | 0 | papercut | 4/6 Traced | 0 | — | — |
| 147 | [#275754](https://github.com/microsoft/vscode/issues/275754) | Deleting a tab character using backspace doesn't work. | 0 | correctness | 6/6 Confirmed | 0 | — | — |
| 159 | [#310362](https://github.com/microsoft/vscode/issues/310362) | can not input chinese on arm64 version | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 161 | [#320074](https://github.com/microsoft/vscode/issues/320074) | IME: Duplicate text appears after converting Japanese input when moving caret before conversion | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 163 | [#324435](https://github.com/microsoft/vscode/issues/324435) | Japanese IME reconversion at caret (no selection) duplicates committed text with EditContext | 0 | correctness | 6/6 Confirmed | 0 | — | — |
| 165 | [#325744](https://github.com/microsoft/vscode/issues/325744) | [macOS IME] Typing decimal numbers may produce "1。2" instead of "1.2" | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 167 | [#328546](https://github.com/microsoft/vscode/issues/328546) | Snippet setion quickly closes | 0 | correctness | 3/6 Plausible | 0 | — | — |

### Hover widgets (13)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 8 | [#232226](https://github.com/microsoft/vscode/issues/232226) | All <span> tags in hover have a 4px bottom margin which causes nested spans to have stacking bottom margins | 21 | visual | 2/6 Unverified | 7 | — | — |
| 22 | [#236745](https://github.com/microsoft/vscode/issues/236745) | editorHoverVisible keybinding condition does not work | 2 | correctness | 5/6 Source-confirmed | 2 | yes | — |
| 78 | [#105302](https://github.com/microsoft/vscode/issues/105302) | Hover not showing on inline decorations | 2 | papercut | 4/6 Traced | 0 | — | — |
| 79 | [#167781](https://github.com/microsoft/vscode/issues/167781) | Pressing cmd with hover open does not  peek symbol | 1 | papercut | 5/6 Source-confirmed | 0 | — | — |
| 81 | [#178184](https://github.com/microsoft/vscode/issues/178184) | Difference in hover sequence results between run-time and test-time | 1 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 87 | [#248246](https://github.com/microsoft/vscode/issues/248246) | Hover on top of file goes away when cursor moves to click on + and - buttons | 1 | papercut | 3/6 Plausible | 0 | — | — |
| 94 | [#123448](https://github.com/microsoft/vscode/issues/123448) | Reserve some space to the right of the hover to be able to grab the scrollbar | 0 | papercut | 6/6 Confirmed | 0 | — | — |
| 95 | [#152474](https://github.com/microsoft/vscode/issues/152474) | Elements inside a gitlens hover appear to jiggle | 0 | visual | 3/6 Plausible | 0 | — | — |
| 99 | [#185223](https://github.com/microsoft/vscode/issues/185223) | Quick info quick fixes text flashes when moving mouse over it | 0 | visual | 3/6 Plausible | 0 | — | — |
| 110 | [#218320](https://github.com/microsoft/vscode/issues/218320) | Accessible Hover View/Help contains yellow rectangles for certain whitespace characters like &nbsp, &emsp etc. | 0 | visual | 3/6 Plausible | 0 | — | — |
| 145 | [#271597](https://github.com/microsoft/vscode/issues/271597) | Tooltip overlaps scrollbar/gutter when sidebars are hidden | 0 | visual | 5/6 Source-confirmed | 0 | yes | — |
| 148 | [#275822](https://github.com/microsoft/vscode/issues/275822) | Double follow link when hovering link in markdown file | 0 | visual | 5/6 Source-confirmed | 0 | yes | — |
| 154 | [#292466](https://github.com/microsoft/vscode/issues/292466) | Verbose Hover: the increase/decrease (+/-) buttons jump to top/bottom with no reason | 0 | visual | 5/6 Source-confirmed | 0 | yes | — |

### Color decorations (10)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 13 | [#292858](https://github.com/microsoft/vscode/issues/292858) | Colour picker ranges are not tracked correctly on document edits, resulting in corrupt edits | 3 | correctness | 5/6 Source-confirmed | 4 | yes | — |
| 33 | [#287011](https://github.com/microsoft/vscode/issues/287011) | Decoration not applied to diff editors when "fontWeight" decoration is set | 0 | correctness | 5/6 Source-confirmed | 2 | — | — |
| 40 | [#238564](https://github.com/microsoft/vscode/issues/238564) | Braces colouring is off inside Dart multiline strings | 2 | visual | 4/6 Traced | 1 | — | — |
| 54 | [#327077](https://github.com/microsoft/vscode/issues/327077) | [Bug] Color swatch briefly displays in settings before vanishing | 1 | correctness | 6/6 Confirmed | 1 | — | — |
| 55 | [#327430](https://github.com/microsoft/vscode/issues/327430) | Color picker dimisses on its own when mouse is outside while still dragging | 1 | correctness | 5/6 Source-confirmed | 1 | — | — |
| 74 | [#296249](https://github.com/microsoft/vscode/issues/296249) | [regression] Coloured brackets very laggy | 0 | perf | 5/6 Source-confirmed | 1 | — | — |
| 90 | [#319934](https://github.com/microsoft/vscode/issues/319934) | Markdown `editor.colorDecorators: false` not honored on startup; likely race condition | 1 | visual | 5/6 Source-confirmed | 0 | — | — |
| 101 | [#195606](https://github.com/microsoft/vscode/issues/195606) | [Bug] Color picker broken if monaco-editor is inside shadow dom | 0 | correctness | 4/6 Traced | 0 | — | — |
| 120 | [#235912](https://github.com/microsoft/vscode/issues/235912) | Flicker of many color decorations when deleting | 0 | visual | 5/6 Source-confirmed | 0 | yes | — |
| 150 | [#282485](https://github.com/microsoft/vscode/issues/282485) | Make default color decorator be followed only by string or empty space before determining if its a color | 0 | papercut | 5/6 Source-confirmed | 0 | yes | — |

### Accessibility focus (9)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 15 | [#245146](https://github.com/microsoft/vscode/issues/245146) | Misalignment between VoiceOver focus and Keyboard focus in VS Code | 0 | correctness | 6/6 Confirmed | 3 | — | — |
| 32 | [#284320](https://github.com/microsoft/vscode/issues/284320) | Accessibility: Editor content stuck scrolled to the right | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 51 | [#294263](https://github.com/microsoft/vscode/issues/294263) | VoiceOver on MacOS stops reading the code editor after jumping to the end of a long code file | 1 | correctness | 3/6 Plausible | 1 | — | — |
| 60 | [#241055](https://github.com/microsoft/vscode/issues/241055) | Accessibility MacOS: Pressing a routing button over a character in editor does not move the cursor | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 66 | [#274014](https://github.com/microsoft/vscode/issues/274014) | Accessibility: Editor stops announcing file contents to Voice Over after reaching the end of the file | 0 | correctness | 6/6 Confirmed | 1 | — | — |
| 140 | [#258559](https://github.com/microsoft/vscode/issues/258559) | edit context and rich screen reader context has weird focusing | 0 | visual | — | 0 | — | — |
| 141 | [#267144](https://github.com/microsoft/vscode/issues/267144) | CTRL+G regression is back for Screen Reader Users in Insiders build | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 160 | [#319725](https://github.com/microsoft/vscode/issues/319725) | vscode and voice over mac os | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 162 | [#323492](https://github.com/microsoft/vscode/issues/323492) | Extreme lag when VoiceOver is active | 0 | perf | 5/6 Source-confirmed | 0 | — | — |

### Selection and cursor (9)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 24 | [#261958](https://github.com/microsoft/vscode/issues/261958) | [iPadOS] Cannot select text in GitHub Codespaces editor (Safari/Chrome) | 2 | correctness | 3/6 Plausible | 2 | — | — |
| 41 | [#251735](https://github.com/microsoft/vscode/issues/251735) | Screen doesn't automatically scroll when using mouse to select text if the status bar is disabled. | 2 | papercut | 5/6 Source-confirmed | 1 | yes | — |
| 42 | [#205887](https://github.com/microsoft/vscode/issues/205887) | Column selection is reset when selecting with arrow keys | 1 | correctness | 5/6 Source-confirmed | 1 | — | — |
| 93 | [#117255](https://github.com/microsoft/vscode/issues/117255) | Move Line Up/Down alters selection | 0 | papercut | 5/6 Source-confirmed | 0 | yes | — |
| 118 | [#234758](https://github.com/microsoft/vscode/issues/234758) | Right-clicking injected text caused funny selection | 0 | visual | 4/6 Traced | 0 | — | — |
| 123 | [#239285](https://github.com/microsoft/vscode/issues/239285) | Mouse not changing to line cursor on text hover. | 0 | visual | 6/6 Confirmed | 0 | — | — |
| 131 | [#247607](https://github.com/microsoft/vscode/issues/247607) | Selection is not preserved when variable line hight kicks in | 0 | visual | — | 0 | — | — |
| 152 | [#284279](https://github.com/microsoft/vscode/issues/284279) | Stupidly difficult to select text from the beginning of line; cursor icon inconsistent with behavior | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 155 | [#294190](https://github.com/microsoft/vscode/issues/294190) | Reverse lines should preserve single-line selection | 0 | papercut | 5/6 Source-confirmed | 0 | yes | — |

### Line layout (13)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 59 | [#234947](https://github.com/microsoft/vscode/issues/234947) | Checked Render whitespace is not shown when the Vscode is initialised at start | 0 | visual | 2/6 Unverified | 1 | — | — |
| 71 | [#288873](https://github.com/microsoft/vscode/issues/288873) | Line breaks incorrectly when variable font size | 0 | visual | 5/6 Source-confirmed | 1 | — | — |
| 72 | [#295163](https://github.com/microsoft/vscode/issues/295163) | Advanced line wrapping causes horizontal scrolling if decorations are used | 0 | visual | 5/6 Source-confirmed | 1 | — | — |
| 73 | [#295179](https://github.com/microsoft/vscode/issues/295179) | Custom line heights should only affect the view line | 0 | visual | 5/6 Source-confirmed | 1 | — | — |
| 75 | [#298249](https://github.com/microsoft/vscode/issues/298249) | Whitespace rendered at incorrect height when using variable line heights and font sizes | 0 | visual | — | 1 | — | — |
| 122 | [#239200](https://github.com/microsoft/vscode/issues/239200) | Character under block cursor within a selection results in that character missing from sticky scroll | 0 | visual | 5/6 Source-confirmed | 0 | yes | — |
| 125 | [#240740](https://github.com/microsoft/vscode/issues/240740) | Can you change the mobile line? | 0 | correctness | — | 0 | — | — |
| 134 | [#250072](https://github.com/microsoft/vscode/issues/250072) | Minimap overlaps content by the width of the vertical scrollbar | 0 | visual | 5/6 Source-confirmed | 0 | yes | — |
| 135 | [#250313](https://github.com/microsoft/vscode/issues/250313) | Word-wrap Alt-Z does not work with emojis. | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 153 | [#284610](https://github.com/microsoft/vscode/issues/284610) | Horizontal scrollbar persists even when overflowing line is fixed | 0 | visual | 5/6 Source-confirmed | 0 | yes | — |
| 157 | [#301893](https://github.com/microsoft/vscode/issues/301893) | Function name, and first line in function overlap when Editor: Line Height != 0, and tokenColors:fontSize are used | 0 | visual | 3/6 Plausible | 0 | — | — |
| 158 | [#305658](https://github.com/microsoft/vscode/issues/305658) | Text with small custom font size is rendered below expected position | 0 | visual | 4/6 Traced | 0 | — | — |
| 164 | [#324758](https://github.com/microsoft/vscode/issues/324758) | Native EditContext: focusing the editor scrolls natively-scrolling ancestors (missing the textarea path's scroll-preservation guard) | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |

### Editor performance (2)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 64 | [#262473](https://github.com/microsoft/vscode/issues/262473) | When the content of a text file is large, case conversion freezes | 0 | freeze | 5/6 Source-confirmed | 1 | — | — |
| 137 | [#253260](https://github.com/microsoft/vscode/issues/253260) | Perf: changeLineHeights leads to long tasks on a decently sized file | 0 | perf | — | 0 | — | — |

### Move line commands (2)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 111 | [#219242](https://github.com/microsoft/vscode/issues/219242) | moving lines up and down causes formatting corruption | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 138 | [#253436](https://github.com/microsoft/vscode/issues/253436) | Moving lines causes rendering to flash | 0 | visual | 6/6 Confirmed | 0 | — | — |

### Other (10)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 10 | [#204193](https://github.com/microsoft/vscode/issues/204193) | Editor.cursorSurroundingLines broken with update to 1.86 | 17 | papercut | 5/6 Source-confirmed | 4 | — | — |
| 17 | [#210436](https://github.com/microsoft/vscode/issues/210436) | setting `editor.autoClosingBrackets` to `beforeWhitespace` no longer works | 5 | correctness | 4/6 Traced | 2 | — | — |
| 39 | [#227594](https://github.com/microsoft/vscode/issues/227594) | Extra Space Added When Inserting New Line in HTML Document with Ctrl+Enter | 2 | papercut | 4/6 Traced | 1 | — | — |
| 44 | [#225916](https://github.com/microsoft/vscode/issues/225916) | Surrounding with brackets doesn’t work in some cases | 1 | correctness | 5/6 Source-confirmed | 1 | — | — |
| 65 | [#268896](https://github.com/microsoft/vscode/issues/268896) | Editor focus conflict after first layout | 0 | correctness | 4/6 Traced | 1 | yes | — |
| 88 | [#249958](https://github.com/microsoft/vscode/issues/249958) | Line comment toggling does not work when line comment starts with a whitespace | 1 | correctness | — | 0 | — | — |
| 115 | [#231280](https://github.com/microsoft/vscode/issues/231280) | Error in console when mouse move out of the browser | 0 | papercut | 5/6 Source-confirmed | 0 | yes | — |
| 142 | [#268272](https://github.com/microsoft/vscode/issues/268272) | Certain buttons are unresponsive in Chrome after monaco-editor version 0.53 | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 151 | [#283286](https://github.com/microsoft/vscode/issues/283286) | Cannot read properties of undefined (reading 'getModelColumnOfViewPosition') | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 166 | [#328449](https://github.com/microsoft/vscode/issues/328449) | Mermaid preview fails | 0 | correctness | 3/6 Plausible | 0 | — | — |

## Feature requests

### Color tooling (10)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 2 | [#140899](https://github.com/microsoft/vscode/issues/140899) | Add support for palettes/named colors in the color picker | 62 | backlog-candidate | 100 | — |
| 12 | [#282673](https://github.com/microsoft/vscode/issues/282673) | Add a setting for color picker to parse ARGB instead of RGBA | 26 | backlog-candidate | 55 | — |
| 13 | [#139840](https://github.com/microsoft/vscode/issues/139840) | Use modern (CSS color level 4) syntax for colors in the color picker | 27 | backlog-candidate | 52 | — |
| 18 | [#144036](https://github.com/microsoft/vscode/issues/144036) | Feature Request: Add way of getting all the color presentations in a specific range of a document in the vscode API | 31 | backlog-candidate | 36 | — |
| 31 | [#324835](https://github.com/microsoft/vscode/issues/324835) | Please add native support for Color Identifiers | 12 | backlog-candidate | 19 | — |
| 42 | [#199944](https://github.com/microsoft/vscode/issues/199944) | Color picker is far too wide and does not remember when I resize it smaller | 2 | backlog-candidate | 13 | — |
| 49 | [#31637](https://github.com/microsoft/vscode/issues/31637) | [Feature] Color Picker: Keyboard accessibility | 0 | backlog-candidate | 8 | — |
| 52 | [#304445](https://github.com/microsoft/vscode/issues/304445) | Add regex filtering for color decorators (editor.colorDecorators) | 0 | backlog-candidate | 6 | — |
| 57 | [#227697](https://github.com/microsoft/vscode/issues/227697) | LSP DocumentColor Refresh Request | 0 | backlog-candidate | 4 | — |
| 60 | [#107491](https://github.com/microsoft/vscode/issues/107491) | Selecting 2 color values and changing them both with color picker | 1 | dormant | 3 | — |

### Editor commands (10)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | [#66468](https://github.com/microsoft/vscode/issues/66468) | Shrink empty lines | 72 | backlog-candidate | 100 | — |
| 6 | [#106502](https://github.com/microsoft/vscode/issues/106502) | Multiple Cursors - Preserve Case | 56 | backlog-candidate | 90 | — |
| 17 | [#86467](https://github.com/microsoft/vscode/issues/86467) | Trailing comma-aware move line up/down | 28 | backlog-candidate | 40 | — |
| 20 | [#84763](https://github.com/microsoft/vscode/issues/84763) | Make "move line" command to work contextually | 21 | backlog-candidate | 30 | — |
| 24 | [#11809](https://github.com/microsoft/vscode/issues/11809) | Move line up/down should support multiple cursors | 14 | backlog-candidate | 22 | — |
| 38 | [#236218](https://github.com/microsoft/vscode/issues/236218) | Expose the current editor overtype state | 7 | backlog-candidate | 14 | — |
| 39 | [#249132](https://github.com/microsoft/vscode/issues/249132) | Avoid copying a single empty line into the Clipboard | 4 | backlog-candidate | 14 | — |
| 56 | [#209939](https://github.com/microsoft/vscode/issues/209939) | Add option to trim trailing whitespaces only at the end of lines that contain code | 1 | dormant | 4 | — |
| 59 | [#236191](https://github.com/microsoft/vscode/issues/236191) | Overtype Mode: backspace should insert spaces in its stead | 2 | dormant | 3 | — |
| 79 | [#251277](https://github.com/microsoft/vscode/issues/251277) | Function of shortcut key of block comment in c/c++ not strong enough | 0 | dormant | 0 | — |

### Indentation rules (23)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 3 | [#66235](https://github.com/microsoft/vscode/issues/66235) | Allow more powerful onEnterRules for cursor alignment | 48 | backlog-candidate | 97 | — |
| 10 | [#40115](https://github.com/microsoft/vscode/issues/40115) | indent back to line start after enter newline and press up | 45 | backlog-candidate | 69 | — |
| 11 | [#67678](https://github.com/microsoft/vscode/issues/67678) | Auto-indent on closing brace | 42 | backlog-candidate | 64 | — |
| 19 | [#208985](https://github.com/microsoft/vscode/issues/208985) | Declarative treesitter-based indentation rules | 12 | backlog-candidate | 31 | — |
| 21 | [#17281](https://github.com/microsoft/vscode/issues/17281) | Add support for capture groups in onEnterRules | 12 | dormant | 27 | — |
| 22 | [#209805](https://github.com/microsoft/vscode/issues/209805) | Allow users to define their own indentation rules within the settings | 8 | dormant | 23 | — |
| 25 | [#16998](https://github.com/microsoft/vscode/issues/16998) | Add SmartIndent capability | 14 | backlog-candidate | 22 | — |
| 28 | [#294080](https://github.com/microsoft/vscode/issues/294080) | Feature request: command to adjust space-based indentation width, without a formatter | 5 | active | 20 | — |
| 30 | [#201600](https://github.com/microsoft/vscode/issues/201600) | Enter custom tab size from the UI | 14 | backlog-candidate | 19 | — |
| 33 | [#19847](https://github.com/microsoft/vscode/issues/19847) | Explore using formatters for indentation adjustment when formatters are available | 11 | backlog-candidate | 18 | — |
| 36 | [#236296](https://github.com/microsoft/vscode/issues/236296) | Strip characters from `"onEnterRules"` string | 4 | backlog-candidate | 17 | — |
| 43 | [#228286](https://github.com/microsoft/vscode/issues/228286) | Disabling "Use Tab Stops" should be respected in more indentation contexts | 4 | backlog-candidate | 12 | — |
| 47 | [#50952](https://github.com/microsoft/vscode/issues/50952) | onEnterRules should be multi-line aware | 5 | dormant | 10 | — |
| 50 | [#34621](https://github.com/microsoft/vscode/issues/34621) | Unify indentation and formatting APIs | 5 | backlog-candidate | 6 | — |
| 64 | [#251101](https://github.com/microsoft/vscode/issues/251101) | Add onType rules similar to onEnter rules | 1 | dormant | 2 | — |
| 68 | [#11322](https://github.com/microsoft/vscode/issues/11322) | Remove whitespace and indent to the right spot when the line has more whitespace than necessary | 1 | backlog-candidate | 1 | — |
| 69 | [#29669](https://github.com/microsoft/vscode/issues/29669) | auto indenting issues with C# files | 1 | backlog-candidate | 1 | — |
| 70 | [#73559](https://github.com/microsoft/vscode/issues/73559) | Cannot set embedded language indentation rules | 1 | backlog-candidate | 1 | — |
| 71 | [#201732](https://github.com/microsoft/vscode/issues/201732) | Indent instead of de-indent when soft wrapping long lines in signatures | 0 | dormant | 1 | — |
| 72 | [#209006](https://github.com/microsoft/vscode/issues/209006) | Edit language configuration files for C++ in order to indent after if/for/while statement with no brace | 0 | backlog-candidate | 1 | — |
| 75 | [#100667](https://github.com/microsoft/vscode/issues/100667) | Alt+Backspace to delete previous character without smart indentation-aware deletion | 0 | backlog-candidate | 0 | — |
| 76 | [#171040](https://github.com/microsoft/vscode/issues/171040) | Automatic enter indentation in offside folding languages | 0 | dormant | 0 | — |
| 81 | [#277764](https://github.com/microsoft/vscode/issues/277764) | Option to not replace aligning spaces during indentation by Tab | 0 | backlog-candidate | 0 | — |

### Accessibility and input (4)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 4 | [#65648](https://github.com/microsoft/vscode/issues/65648) | Bidi text edit support | 43 | backlog-candidate | 95 | — |
| 54 | [#229647](https://github.com/microsoft/vscode/issues/229647) | Undo stacks are not granular enough for Korean | 2 | backlog-candidate | 4 | — |
| 58 | [#254835](https://github.com/microsoft/vscode/issues/254835) | When using macOS with the VoiceOver screen reader, moving word-by-word across a sign character causes the word to be spoken twice | 0 | backlog-candidate | 4 | — |
| 63 | [#327767](https://github.com/microsoft/vscode/issues/327767) | Spelling mistake correection for non keywords | 0 | backlog-candidate | 3 | — |

### Sticky scroll (8)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 5 | [#238568](https://github.com/microsoft/vscode/issues/238568) | Allow multiple lines per StickyScroll entry | 37 | backlog-candidate | 92 | — |
| 7 | [#168428](https://github.com/microsoft/vscode/issues/168428) | Consider a sticky scroll provider API | 48 | backlog-candidate | 89 | — |
| 8 | [#187834](https://github.com/microsoft/vscode/issues/187834) | [Feature]: Add editor decorations to sticky scroll lines | 42 | backlog-candidate | 78 | — |
| 16 | [#208406](https://github.com/microsoft/vscode/issues/208406) | Option for sticky scroll to prioritize inner blocks | 14 | backlog-candidate | 43 | — |
| 37 | [#317702](https://github.com/microsoft/vscode/issues/317702) | Sticky Scroll doesn't handle multi-line function headers | 3 | backlog-candidate | 15 | — |
| 45 | [#245302](https://github.com/microsoft/vscode/issues/245302) | [Sticky Scroll] If a function consist of multiline arguments, sticky the function also multiline | 6 | backlog-candidate | 11 | — |
| 78 | [#248486](https://github.com/microsoft/vscode/issues/248486) | Add code to make the cursor always appear below the editor sticky scroll (especially on cursor jump) | 0 | dormant | 0 | — |
| 80 | [#253608](https://github.com/microsoft/vscode/issues/253608) | Make sticky scroll take into account line heights when the cursor moves | 0 | dormant | 0 | — |

### Hover interactions (11)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 9 | [#247250](https://github.com/microsoft/vscode/issues/247250) | Diagnostics hover sort and clarity | 25 | backlog-candidate | 70 | — |
| 14 | [#133587](https://github.com/microsoft/vscode/issues/133587) | Allow pinning hover popovers (datatips) | 31 | backlog-candidate | 50 | — |
| 29 | [#232685](https://github.com/microsoft/vscode/issues/232685) | Test and iterate on TS expandable hover apis | 1 | backlog-candidate | 20 | — |
| 34 | [#151763](https://github.com/microsoft/vscode/issues/151763) | when hovers are not sticky, alt/opt key should make them temporarily sticky | 7 | backlog-candidate | 18 | — |
| 51 | [#203767](https://github.com/microsoft/vscode/issues/203767) | click to expect the hover display information to be dynamically updated without refreshing the hover. | 1 | active | 6 | — |
| 53 | [#241730](https://github.com/microsoft/vscode/issues/241730) | Feedback on experimental expandable hover API | 1 | dormant | 5 | — |
| 62 | [#85196](https://github.com/microsoft/vscode/issues/85196) | LCD: greyscale rendering in editor hover | 0 | backlog-candidate | 3 | — |
| 65 | [#211063](https://github.com/microsoft/vscode/issues/211063) | Verbose Hover: Hover jumps when there is not enough space | 0 | backlog-candidate | 2 | — |
| 74 | [#239704](https://github.com/microsoft/vscode/issues/239704) | Hover should scroll when copying with mouse and going out of hover widget | 0 | backlog-candidate | 1 | — |
| 82 | [#281922](https://github.com/microsoft/vscode/issues/281922) | Make showing delay take precedence over hiding delay | 0 | active | 0 | — |
| 83 | [#281925](https://github.com/microsoft/vscode/issues/281925) | Apply the hover.hidingDelay to when hover.sticky is false | 0 | active | 0 | — |

### Rendering and decorations (12)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 23 | [#263545](https://github.com/microsoft/vscode/issues/263545) | Allow configuring font family, font size and line height via syntactic tokens | 6 | active | 23 | — |
| 26 | [#284742](https://github.com/microsoft/vscode/issues/284742) | [BUG]: VSCode incorrect syntax highlighting problem | 1 | backlog-candidate | 21 | — |
| 27 | [#237095](https://github.com/microsoft/vscode/issues/237095) | Support Line decoration editor offset retrieval | 10 | backlog-candidate | 20 | — |
| 40 | [#286157](https://github.com/microsoft/vscode/issues/286157) | Default semantic token styles do not honour custom line heights or font sizes from TextMate themes | 0 | backlog-candidate | 14 | — |
| 44 | [#214857](https://github.com/microsoft/vscode/issues/214857) | lineHighlightBorder should frame all warped line | 6 | backlog-candidate | 11 | — |
| 46 | [#261241](https://github.com/microsoft/vscode/issues/261241) | Accessibility Issue: "Tokenization is skipped..." | 4 | backlog-candidate | 11 | — |
| 48 | [#286296](https://github.com/microsoft/vscode/issues/286296) | Support decorations that hide characters | 2 | backlog-candidate | 10 | — |
| 55 | [#198122](https://github.com/microsoft/vscode/issues/198122) | Rethink how z-index is assigned within the editor | 1 | backlog-candidate | 4 | — |
| 61 | [#256046](https://github.com/microsoft/vscode/issues/256046) | Adopting variable font sizes in `createDecorationsCollection` code | 1 | dormant | 3 | — |
| 66 | [#249967](https://github.com/microsoft/vscode/issues/249967) | Apply decoration lineHeight on all affected lines after line wrapping | 0 | backlog-candidate | 2 | — |
| 73 | [#233558](https://github.com/microsoft/vscode/issues/233558) | Zooming types syntax highlighting doesn't look good | 0 | dormant | 1 | — |
| 84 | [#287118](https://github.com/microsoft/vscode/issues/287118) | Make semantic tokens work with font size and line height | 0 | backlog-candidate | 0 | — |

### Language intelligence (4)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 32 | [#225179](https://github.com/microsoft/vscode/issues/225179) | Python: Improved Bracket Pair Detection for strings that contain `{{` | 4 | backlog-candidate | 19 | — |
| 35 | [#255818](https://github.com/microsoft/vscode/issues/255818) | Exploration: prompt completions in panel and inline chat | 5 | backlog-candidate | 18 | — |
| 41 | [#210437](https://github.com/microsoft/vscode/issues/210437) | option for `editor.autoClosingBrackets` to not auto-close if there's a syntax error in the file | 6 | backlog-candidate | 13 | — |
| 77 | [#191648](https://github.com/microsoft/vscode/issues/191648) | Should json sort on save also apply to JsonL | 0 | backlog-candidate | 0 | — |

### Other (2)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 15 | [#207579](https://github.com/microsoft/vscode/issues/207579) | Refactor preview is missing checkboxes on groups | 23 | backlog-candidate | 50 | — |
| 67 | [#279415](https://github.com/microsoft/vscode/issues/279415) | Scrolling through long single line files is terrible. | 0 | backlog-candidate | 2 | — |
