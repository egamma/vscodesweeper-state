# Top issues by theme — aiday-mar

Experimental themed view of [the flat ranking](aiday-mar.md); themes assigned by the review engine. Rank/score are the lane-wide values. Generated 2026-07-06 16:02 UTC.

## Bugs

### Copy and paste behavior (12)

| # | Issue | Title | 👍 | Severity | Score | Auto-fix |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | [#252371](https://github.com/microsoft/vscode/issues/252371) | Copy and paste not working | 107 | correctness | 100 | — |
| 2 | [#299786](https://github.com/microsoft/vscode/issues/299786) | paste is slow with copilot | 24 | perf | 37 | — |
| 8 | [#239500](https://github.com/microsoft/vscode/issues/239500) | Copy-paste does not work randomly | 5 | correctness | 8 | — |
| 18 | [#286892](https://github.com/microsoft/vscode/issues/286892) | Multiple cursors empty copy does not paste in line above | 0 | correctness | 3 | yes |
| 25 | [#249508](https://github.com/microsoft/vscode/issues/249508) | Can't copy the whole line if there is a null character in it. When trying to copy the entire line, only the part before the null character is copied. | 2 | correctness | 2 | yes |
| 35 | [#293314](https://github.com/microsoft/vscode/issues/293314) | Copy Paste Not Working with Keyboard | 0 | correctness | 2 | — |
| 48 | [#246719](https://github.com/microsoft/vscode/issues/246719) | Copying with empty selection clears the clipboard when editor.emptySelectionClipboard=false in Web mode | 1 | correctness | 1 | yes |
| 66 | [#274154](https://github.com/microsoft/vscode/issues/274154) | copy text, delete text, pastes different text that is now in the location where old text was | 0 | correctness | 1 | — |
| 117 | [#230320](https://github.com/microsoft/vscode/issues/230320) | Pasting a large amount of content in a json file will leave the cursor in the middle of the pasted content | 0 | correctness | 0 | — |
| 132 | [#243932](https://github.com/microsoft/vscode/issues/243932) | `editor.action.clipboardCopyAction` command no longer works | 0 | correctness | 0 | — |
| 150 | [#269442](https://github.com/microsoft/vscode/issues/269442) | Copying can replace new lines with another char | 0 | papercut | 0 | — |
| 163 | [#294190](https://github.com/microsoft/vscode/issues/294190) | Reverse lines should preserve single-line selection | 0 | papercut | 0 | yes |

### Auto indentation rules (66)

| # | Issue | Title | 👍 | Severity | Score | Auto-fix |
| --- | --- | --- | --- | --- | --- | --- |
| 3 | [#243100](https://github.com/microsoft/vscode/issues/243100) | Automatic indentation doesn't work well with C/C++ | 22 | correctness | 16 | — |
| 4 | [#43244](https://github.com/microsoft/vscode/issues/43244) | Incorrect indentation for single line if/for/while/etc, multiline chaining statements etc | 45 | none | 11 | — |
| 7 | [#125261](https://github.com/microsoft/vscode/issues/125261) | Leading whitespace before bracket/brace should not be automatically removed | 21 | correctness | 8 | yes |
| 9 | [#63388](https://github.com/microsoft/vscode/issues/63388) | Indent/Outdent with tab key does not honor editor.autoIndent=false | 13 | correctness | 6 | — |
| 13 | [#241370](https://github.com/microsoft/vscode/issues/241370) | Incorrect indentation after C multi-line comment blocks | 5 | correctness | 4 | — |
| 15 | [#184700](https://github.com/microsoft/vscode/issues/184700) | Alignment is incorrectly replaced by tabs | 6 | correctness | 3 | — |
| 16 | [#240882](https://github.com/microsoft/vscode/issues/240882) | Indentation on pasting with multiple lines of code not working as expected | 3 | correctness | 3 | yes |
| 21 | [#57197](https://github.com/microsoft/vscode/issues/57197) | Identation rules are broken | 3 | correctness | 2 | — |
| 22 | [#178334](https://github.com/microsoft/vscode/issues/178334) | Weird code indentation C++ | 2 | correctness | 2 | — |
| 23 | [#224569](https://github.com/microsoft/vscode/issues/224569) | Auto indent when move line up or down | 2 | correctness | 2 | — |
| 30 | [#255500](https://github.com/microsoft/vscode/issues/255500) | Reindent Lines doesn't work when the line has no initial indent | 1 | correctness | 2 | yes |
| 31 | [#223606](https://github.com/microsoft/vscode/issues/223606) | Auto indent issue: Lua multiline quotes `[[...]]` conflict with #210641 which removes brackets before passing text to indent rules | 0 | correctness | 2 | — |
| 32 | [#256037](https://github.com/microsoft/vscode/issues/256037) | Auto indent is wrong when adding brackets sometimes | 0 | correctness | 2 | — |
| 36 | [#174667](https://github.com/microsoft/vscode/issues/174667) | Wrong indent level after `break;` in a switch statement PHP | 6 | papercut | 1 | — |
| 37 | [#221574](https://github.com/microsoft/vscode/issues/221574) | Copy paste indent | 4 | papercut | 1 | — |
| 38 | [#187944](https://github.com/microsoft/vscode/issues/187944) | `editor.detectIndentation` produces incorrect values for empty files when `editor.insertSpaces` is `true` | 3 | correctness | 1 | yes |
| 39 | [#111265](https://github.com/microsoft/vscode/issues/111265) | Typing } changes the indentation (autoIndent "none" doesn't work) | 2 | correctness | 1 | yes |
| 44 | [#213598](https://github.com/microsoft/vscode/issues/213598) | Move Line Up and Move Line Down breaks indentation in Javascript/Typescript files | 1 | correctness | 1 | — |
| 46 | [#241011](https://github.com/microsoft/vscode/issues/241011) | Moving a line down in Go code messes up indentation in VS Code | 1 | correctness | 1 | — |
| 47 | [#245610](https://github.com/microsoft/vscode/issues/245610) | Alt Down Arrow to move */ comment is reformatting code | 1 | correctness | 1 | — |
| 49 | [#247477](https://github.com/microsoft/vscode/issues/247477) | incorrect append double slash text while onEnter called | 1 | correctness | 1 | — |
| 50 | [#278311](https://github.com/microsoft/vscode/issues/278311) | Auto-indent mangles JSON files due to URL misinterpretation | 1 | correctness | 1 | — |
| 51 | [#285222](https://github.com/microsoft/vscode/issues/285222) | `editor.autoIndentOnPaste` doesn't work if the initial line is already correctly indented | 1 | correctness | 1 | yes |
| 53 | [#61510](https://github.com/microsoft/vscode/issues/61510) | VS Code changes indention of current line | 0 | correctness | 1 | — |
| 54 | [#188246](https://github.com/microsoft/vscode/issues/188246) | incorrect indentation detection | 0 | correctness | 1 | — |
| 55 | [#219821](https://github.com/microsoft/vscode/issues/219821) | Indent using spaces function does not convert tabs to spaces in mixed indentation text content | 0 | none | 1 | — |
| 58 | [#244880](https://github.com/microsoft/vscode/issues/244880) | Bug with auto-indent rule: "onEnterRules" + "indentOutdent" + "AppendText" do not insert indentation and string at the END as expected. | 0 | correctness | 1 | yes |
| 60 | [#250722](https://github.com/microsoft/vscode/issues/250722) | C# wrong extra indentation in latest release | 0 | correctness | 1 | — |
| 67 | [#276614](https://github.com/microsoft/vscode/issues/276614) | auto-indenting and line spacing issues | 0 | correctness | 1 | — |
| 69 | [#287498](https://github.com/microsoft/vscode/issues/287498) | PHP autoindent behavior is broken (since 1.108) | 0 | correctness | 1 | — |
| 77 | [#88638](https://github.com/microsoft/vscode/issues/88638) | Moving lines of code up and down breaks indentation | 2 | papercut | 0 | — |
| 79 | [#227594](https://github.com/microsoft/vscode/issues/227594) | Extra Space Added When Inserting New Line in HTML Document with Ctrl+Enter | 2 | papercut | 0 | — |
| 81 | [#176982](https://github.com/microsoft/vscode/issues/176982) | Json sort command does not honor indentation with tabs | 1 | correctness | 0 | — |
| 83 | [#209019](https://github.com/microsoft/vscode/issues/209019) | Wrong indentation when editing text block in Python | 1 | papercut | 0 | — |
| 84 | [#218255](https://github.com/microsoft/vscode/issues/218255) | jsx auto indentation not corrent | 1 | papercut | 0 | — |
| 85 | [#221362](https://github.com/microsoft/vscode/issues/221362) | BUG: `Move line down` command doesnt preserve indentation | 1 | papercut | 0 | — |
| 86 | [#223308](https://github.com/microsoft/vscode/issues/223308) | Wrong auto-indentation in typescript when pasting | 1 | papercut | 0 | — |
| 87 | [#242029](https://github.com/microsoft/vscode/issues/242029) | Something Wrong with the Auto Indent? | 1 | papercut | 0 | — |
| 90 | [#309962](https://github.com/microsoft/vscode/issues/309962) | "detect indentation" has precedence over "change tab display size" | 1 | papercut | 0 | — |
| 92 | [#29589](https://github.com/microsoft/vscode/issues/29589) | Auto indent on pasting does not satisfy indentation for braces in JS/TS | 0 | correctness | 0 | — |
| 93 | [#85781](https://github.com/microsoft/vscode/issues/85781) | JavaScript: Improve indentation on insert with trailing newline | 0 | none | 0 | — |
| 97 | [#174044](https://github.com/microsoft/vscode/issues/174044) | Latest update broke automatic whitespace | 0 | correctness | 0 | yes |
| 98 | [#174484](https://github.com/microsoft/vscode/issues/174484) | Indentations of curly braces becomes wrong after moving a current line up or down | 0 | correctness | 0 | — |
| 102 | [#193875](https://github.com/microsoft/vscode/issues/193875) | Nested for statements in JavaScript breaks in wrong indention | 0 | papercut | 0 | — |
| 105 | [#199050](https://github.com/microsoft/vscode/issues/199050) | Unexpected indentation added on new line if a string contains a '{' | 0 | correctness | 0 | — |
| 106 | [#199223](https://github.com/microsoft/vscode/issues/199223) | Using 'function' in a Lua string causes wrong indentation | 0 | papercut | 0 | yes |
| 107 | [#199846](https://github.com/microsoft/vscode/issues/199846) | Auto indent for Ruby language's block is not performed If a string include "#" is used as the method argument. | 0 | papercut | 0 | — |
| 108 | [#202942](https://github.com/microsoft/vscode/issues/202942) | Wrong indent detected with PHP comments | 0 | papercut | 0 | — |
| 109 | [#204435](https://github.com/microsoft/vscode/issues/204435) | on-enter rule not applying on reload | 0 | correctness | 0 | — |
| 110 | [#209521](https://github.com/microsoft/vscode/issues/209521) | [Bug]: Incorrect indentation when object nested inline on the same line as parent object | 0 | correctness | 0 | — |
| 111 | [#209537](https://github.com/microsoft/vscode/issues/209537) | [Bug]: Incorrect outdentation when several closing braces are found on the same line | 0 | correctness | 0 | — |
| 112 | [#209539](https://github.com/microsoft/vscode/issues/209539) | [Bug]: Incorrect indentation when there is text before the closing brace | 0 | papercut | 0 | — |
| 114 | [#219242](https://github.com/microsoft/vscode/issues/219242) | moving lines up and down causes formatting corruption | 0 | correctness | 0 | — |
| 115 | [#221444](https://github.com/microsoft/vscode/issues/221444) | Minor indentation inconsistency - trimAutoWhitespace - difference between tab and shift-tab | 0 | papercut | 0 | yes |
| 116 | [#227218](https://github.com/microsoft/vscode/issues/227218) | Bad line move indentation adjustment | 0 | correctness | 0 | — |
| 119 | [#232125](https://github.com/microsoft/vscode/issues/232125) | Shortcuts for auto indentation not working | 0 | correctness | 0 | — |
| 120 | [#233700](https://github.com/microsoft/vscode/issues/233700) | Unexpected indentation | 0 | correctness | 0 | — |
| 122 | [#234925](https://github.com/microsoft/vscode/issues/234925) | When using alt+up/down arrow to move code, indentation does not apply | 0 | correctness | 0 | — |
| 125 | [#236138](https://github.com/microsoft/vscode/issues/236138) | Incorrect indentation for TypeScript opening curly brace | 0 | papercut | 0 | — |
| 128 | [#240023](https://github.com/microsoft/vscode/issues/240023) | Indent/unindent reformats code when I don't want it to | 0 | correctness | 0 | — |
| 133 | [#244021](https://github.com/microsoft/vscode/issues/244021) | Auto-indent of switch-case is idiotic | 0 | correctness | 0 | — |
| 136 | [#248227](https://github.com/microsoft/vscode/issues/248227) | PHP Autoindent is stupid | 0 | papercut | 0 | — |
| 140 | [#251676](https://github.com/microsoft/vscode/issues/251676) | Moving Row Using ALT + Up/Down Arrow Key Cause an Issue with the Code Indentation | 0 | correctness | 0 | — |
| 152 | [#275676](https://github.com/microsoft/vscode/issues/275676) | bad auto-indenting | 0 | papercut | 0 | — |
| 155 | [#282400](https://github.com/microsoft/vscode/issues/282400) | auto indent error | 0 | papercut | 0 | — |
| 165 | [#299080](https://github.com/microsoft/vscode/issues/299080) | JS: Incorrect indentation after comment line | 0 | papercut | 0 | — |

### IME and international input (16)

| # | Issue | Title | 👍 | Severity | Score | Auto-fix |
| --- | --- | --- | --- | --- | --- | --- |
| 6 | [#96041](https://github.com/microsoft/vscode/issues/96041) | unable to input chinese character | 21 | correctness | 9 | — |
| 20 | [#244096](https://github.com/microsoft/vscode/issues/244096) | Duplicated Last Character when Typing Korean in VSCode with Windows 11 and New IME | 4 | correctness | 2 | — |
| 27 | [#271715](https://github.com/microsoft/vscode/issues/271715) | Incorrect text input when using multi-cursor with Japanese IME | 2 | correctness | 2 | — |
| 28 | [#181138](https://github.com/microsoft/vscode/issues/181138) | Japanese IME recomposition broken in Windows Desktop App & Firefox + vscode.dev | 1 | correctness | 2 | — |
| 29 | [#229606](https://github.com/microsoft/vscode/issues/229606) | ASCII characters should not be part of the editing undo/redo stack | 1 | correctness | 2 | — |
| 33 | [#282790](https://github.com/microsoft/vscode/issues/282790) | IME composition corrupts text during multi-cursor editing | 0 | correctness | 2 | — |
| 68 | [#282276](https://github.com/microsoft/vscode/issues/282276) | In Firefox, an extra keystroke is required when replacing text in the editor | 0 | correctness | 1 | — |
| 95 | [#148356](https://github.com/microsoft/vscode/issues/148356) | `bs` character show when press backspace | 0 | visual | 0 | — |
| 103 | [#194902](https://github.com/microsoft/vscode/issues/194902) | Substitution performed when accepting a Kanji conversion of Japanese input method | 0 | correctness | 0 | — |
| 130 | [#243334](https://github.com/microsoft/vscode/issues/243334) | When pressing the kana input button twice in succession on a Mac and trying to convert characters, the number of selected characters increases. | 0 | correctness | 0 | — |
| 131 | [#243844](https://github.com/microsoft/vscode/issues/243844) | Inserting backslash on Japanese romaji keyboard conflicts with keyboard shortcut for triggering inline suggestion | 0 | papercut | 0 | — |
| 134 | [#245972](https://github.com/microsoft/vscode/issues/245972) | Mac US International Keyboard auto closing quotes not working | 0 | correctness | 0 | yes |
| 137 | [#248467](https://github.com/microsoft/vscode/issues/248467) | Autocompletion doesn't work to hyperlink Korean title | 0 | correctness | 0 | — |
| 148 | [#268442](https://github.com/microsoft/vscode/issues/268442) | Weird bug when closing the auto quotation double quotes in any HTML file | 0 | papercut | 0 | — |
| 169 | [#310362](https://github.com/microsoft/vscode/issues/310362) | can not input chinese on arm64 version | 0 | correctness | 0 | — |
| 172 | [#320074](https://github.com/microsoft/vscode/issues/320074) | IME: Duplicate text appears after converting Japanese input when moving caret before conversion | 0 | correctness | 0 | — |

### Hover widget behavior (15)

| # | Issue | Title | 👍 | Severity | Score | Auto-fix |
| --- | --- | --- | --- | --- | --- | --- |
| 10 | [#232226](https://github.com/microsoft/vscode/issues/232226) | All <span> tags in hover have a 4px bottom margin which causes nested spans to have stacking bottom margins | 21 | visual | 5 | — |
| 24 | [#236745](https://github.com/microsoft/vscode/issues/236745) | editorHoverVisible keybinding condition does not work | 2 | correctness | 2 | yes |
| 41 | [#245728](https://github.com/microsoft/vscode/issues/245728) | [Annoyance] when selecting code, tooltips can overlap over text I'm selecting. | 2 | papercut | 1 | — |
| 78 | [#105302](https://github.com/microsoft/vscode/issues/105302) | Hover not showing on inline decorations | 2 | papercut | 0 | — |
| 80 | [#167781](https://github.com/microsoft/vscode/issues/167781) | Pressing cmd with hover open does not  peek symbol | 1 | papercut | 0 | — |
| 82 | [#178184](https://github.com/microsoft/vscode/issues/178184) | Difference in hover sequence results between run-time and test-time | 1 | correctness | 0 | yes |
| 88 | [#248246](https://github.com/microsoft/vscode/issues/248246) | Hover on top of file goes away when cursor moves to click on + and - buttons | 1 | papercut | 0 | — |
| 96 | [#152474](https://github.com/microsoft/vscode/issues/152474) | Elements inside a gitlens hover appear to jiggle | 0 | visual | 0 | — |
| 100 | [#185223](https://github.com/microsoft/vscode/issues/185223) | Quick info quick fixes text flashes when moving mouse over it | 0 | visual | 0 | — |
| 101 | [#188878](https://github.com/microsoft/vscode/issues/188878) | Can't hover on top few pixels of editor | 0 | papercut | 0 | yes |
| 151 | [#271597](https://github.com/microsoft/vscode/issues/271597) | Tooltip overlaps scrollbar/gutter when sidebars are hidden | 0 | visual | 0 | yes |
| 154 | [#275822](https://github.com/microsoft/vscode/issues/275822) | Double follow link when hovering link in markdown file | 0 | visual | 0 | yes |
| 162 | [#292466](https://github.com/microsoft/vscode/issues/292466) | Verbose Hover: the increase/decrease (+/-) buttons jump to top/bottom with no reason | 0 | visual | 0 | yes |
| 164 | [#297791](https://github.com/microsoft/vscode/issues/297791) | Editor Hover Widget background opacity is too low (editorHoverWidget.background) | 0 | visual | 0 | — |
| 167 | [#302541](https://github.com/microsoft/vscode/issues/302541) | Hover popup disappears sometimes when I try to move my mouse inside it | 0 | papercut | 0 | — |

### Selection and cursor movement (14)

| # | Issue | Title | 👍 | Severity | Score | Auto-fix |
| --- | --- | --- | --- | --- | --- | --- |
| 11 | [#204193](https://github.com/microsoft/vscode/issues/204193) | Editor.cursorSurroundingLines broken with update to 1.86 | 17 | papercut | 4 | — |
| 26 | [#261958](https://github.com/microsoft/vscode/issues/261958) | [iPadOS] Cannot select text in GitHub Codespaces editor (Safari/Chrome) | 2 | correctness | 2 | — |
| 42 | [#251735](https://github.com/microsoft/vscode/issues/251735) | Screen doesn't automatically scroll when using mouse to select text if the status bar is disabled. | 2 | papercut | 1 | yes |
| 43 | [#205887](https://github.com/microsoft/vscode/issues/205887) | Column selection is reset when selecting with arrow keys | 1 | correctness | 1 | yes |
| 45 | [#225916](https://github.com/microsoft/vscode/issues/225916) | Surrounding with brackets doesn’t work in some cases | 1 | correctness | 1 | — |
| 94 | [#117255](https://github.com/microsoft/vscode/issues/117255) | Move Line Up/Down alters selection | 0 | papercut | 0 | yes |
| 99 | [#178075](https://github.com/microsoft/vscode/issues/178075) | De-indentation breaks pair autoclosing | 0 | correctness | 0 | yes |
| 121 | [#234758](https://github.com/microsoft/vscode/issues/234758) | Right-clicking injected text caused funny selection | 0 | visual | 0 | — |
| 126 | [#239200](https://github.com/microsoft/vscode/issues/239200) | Character under block cursor within a selection results in that character missing from sticky scroll | 0 | visual | 0 | yes |
| 129 | [#240740](https://github.com/microsoft/vscode/issues/240740) | Can you change the mobile line? | 0 | correctness | 0 | — |
| 135 | [#247607](https://github.com/microsoft/vscode/issues/247607) | Selection is not preserved when variable line hight kicks in | 0 | visual | 0 | — |
| 149 | [#268738](https://github.com/microsoft/vscode/issues/268738) | Typing when cursor is obscured behind sticky scroll does not reveal when typing | 0 | papercut | 0 | — |
| 159 | [#284279](https://github.com/microsoft/vscode/issues/284279) | Stupidly difficult to select text from the beginning of line; cursor icon inconsistent with behavior | 0 | papercut | 0 | — |
| 160 | [#284610](https://github.com/microsoft/vscode/issues/284610) | Horizontal scrollbar persists even when overflowing line is fixed | 0 | visual | 0 | yes |

### Color and inline decorators (7)

| # | Issue | Title | 👍 | Severity | Score | Auto-fix |
| --- | --- | --- | --- | --- | --- | --- |
| 14 | [#292858](https://github.com/microsoft/vscode/issues/292858) | Colour picker ranges are not tracked correctly on document edits, resulting in corrupt edits | 3 | correctness | 4 | yes |
| 19 | [#287011](https://github.com/microsoft/vscode/issues/287011) | Decoration not applied to diff editors when "fontWeight" decoration is set | 0 | correctness | 3 | yes |
| 40 | [#238564](https://github.com/microsoft/vscode/issues/238564) | Braces colouring is off inside Dart multiline strings | 2 | visual | 1 | — |
| 91 | [#319934](https://github.com/microsoft/vscode/issues/319934) | Markdown `editor.colorDecorators: false` not honored on startup; likely race condition | 1 | visual | 0 | — |
| 104 | [#195606](https://github.com/microsoft/vscode/issues/195606) | [Bug] Color picker broken if monaco-editor is inside shadow dom | 0 | correctness | 0 | — |
| 124 | [#235912](https://github.com/microsoft/vscode/issues/235912) | Flicker of many color decorations when deleting | 0 | visual | 0 | yes |
| 156 | [#282485](https://github.com/microsoft/vscode/issues/282485) | Make default color decorator be followed only by string or empty space before determining if its a color | 0 | papercut | 0 | yes |

### Accessibility and screen readers (11)

| # | Issue | Title | 👍 | Severity | Score | Auto-fix |
| --- | --- | --- | --- | --- | --- | --- |
| 17 | [#245146](https://github.com/microsoft/vscode/issues/245146) | Misalignment between VoiceOver focus and Keyboard focus in VS Code | 0 | correctness | 3 | — |
| 34 | [#284320](https://github.com/microsoft/vscode/issues/284320) | Accessibility: Editor content stuck scrolled to the right | 0 | correctness | 2 | — |
| 52 | [#294263](https://github.com/microsoft/vscode/issues/294263) | VoiceOver on MacOS stops reading the code editor after jumping to the end of a long code file | 1 | correctness | 1 | — |
| 56 | [#241055](https://github.com/microsoft/vscode/issues/241055) | Accessibility MacOS: Pressing a routing button over a character in editor does not move the cursor | 0 | correctness | 1 | — |
| 57 | [#241058](https://github.com/microsoft/vscode/issues/241058) | Accessibility MacOS: Braille display positions wrong when uparrowing from a blank line to one with contents. | 0 | correctness | 1 | — |
| 65 | [#274014](https://github.com/microsoft/vscode/issues/274014) | Accessibility: Editor stops announcing file contents to Voice Over after reaching the end of the file | 0 | correctness | 1 | — |
| 76 | [#316018](https://github.com/microsoft/vscode/issues/316018) | voice over and braille display on mac os | 0 | correctness | 1 | — |
| 113 | [#218320](https://github.com/microsoft/vscode/issues/218320) | Accessible Hover View/Help contains yellow rectangles for certain whitespace characters like &nbsp, &emsp etc. | 0 | visual | 0 | — |
| 145 | [#258559](https://github.com/microsoft/vscode/issues/258559) | edit context and rich screen reader context has weird focusing | 0 | visual | 0 | — |
| 146 | [#267144](https://github.com/microsoft/vscode/issues/267144) | CTRL+G regression is back for Screen Reader Users in Insiders build | 0 | correctness | 0 | yes |
| 171 | [#319725](https://github.com/microsoft/vscode/issues/319725) | vscode and voice over mac os | 0 | correctness | 0 | — |

### Variable line heights and rendering (10)

| # | Issue | Title | 👍 | Severity | Score | Auto-fix |
| --- | --- | --- | --- | --- | --- | --- |
| 70 | [#288873](https://github.com/microsoft/vscode/issues/288873) | Line breaks incorrectly when variable font size | 0 | visual | 1 | — |
| 71 | [#295163](https://github.com/microsoft/vscode/issues/295163) | Advanced line wrapping causes horizontal scrolling if decorations are used | 0 | visual | 1 | — |
| 72 | [#295179](https://github.com/microsoft/vscode/issues/295179) | Custom line heights should only affect the view line | 0 | visual | 1 | — |
| 73 | [#296249](https://github.com/microsoft/vscode/issues/296249) | [regression] Coloured brackets very laggy | 0 | perf | 1 | — |
| 74 | [#298249](https://github.com/microsoft/vscode/issues/298249) | Whitespace rendered at incorrect height when using variable line heights and font sizes | 0 | visual | 1 | — |
| 141 | [#253260](https://github.com/microsoft/vscode/issues/253260) | Perf: changeLineHeights leads to long tasks on a decently sized file | 0 | perf | 0 | — |
| 142 | [#253436](https://github.com/microsoft/vscode/issues/253436) | Moving lines causes rendering to flash | 0 | visual | 0 | — |
| 166 | [#301893](https://github.com/microsoft/vscode/issues/301893) | Function name, and first line in function overlap when Editor: Line Height != 0, and tokenColors:fontSize are used | 0 | visual | 0 | — |
| 168 | [#305658](https://github.com/microsoft/vscode/issues/305658) | Text with small custom font size is rendered below expected position | 0 | visual | 0 | — |
| 170 | [#314457](https://github.com/microsoft/vscode/issues/314457) | [P1] UI Bug: Input 'jumps' at certain zoom levels | 0 | visual | 0 | — |

### Other (21)

| # | Issue | Title | 👍 | Severity | Score | Auto-fix |
| --- | --- | --- | --- | --- | --- | --- |
| 5 | [#236828](https://github.com/microsoft/vscode/issues/236828) | 🚨 Stop adding comment when enter is pressed | 5 | correctness | 10 | yes |
| 12 | [#210436](https://github.com/microsoft/vscode/issues/210436) | setting `editor.autoClosingBrackets` to `beforeWhitespace` no longer works | 5 | correctness | 4 | — |
| 59 | [#245055](https://github.com/microsoft/vscode/issues/245055) | "CTRL + DEL" keyboard shortcut not working as expected and deleting comments | 0 | correctness | 1 | yes |
| 61 | [#255637](https://github.com/microsoft/vscode/issues/255637) | CTRL + Key commands don't work well on Android with physical keyboard. Deleting a piece of text crashes the browser | 0 | crash | 1 | — |
| 62 | [#259145](https://github.com/microsoft/vscode/issues/259145) | deleteWordRight handles 1 whitespace differently from 2 whitespace | 0 | correctness | 1 | yes |
| 63 | [#262473](https://github.com/microsoft/vscode/issues/262473) | When the content of a text file is large, case conversion freezes | 0 | freeze | 1 | — |
| 64 | [#268896](https://github.com/microsoft/vscode/issues/268896) | Editor focus conflict after first layout | 0 | correctness | 1 | yes |
| 75 | [#303452](https://github.com/microsoft/vscode/issues/303452) | Hebrew content are shown correctly in VScode editor, but not in other view. | 0 | visual | 1 | — |
| 89 | [#249958](https://github.com/microsoft/vscode/issues/249958) | Line comment toggling does not work when line comment starts with a whitespace | 1 | correctness | 0 | — |
| 118 | [#231280](https://github.com/microsoft/vscode/issues/231280) | Error in console when mouse move out of the browser | 0 | papercut | 0 | yes |
| 123 | [#234947](https://github.com/microsoft/vscode/issues/234947) | Checked Render whitespace is not shown when the Vscode is initialised at start | 0 | visual | 0 | — |
| 127 | [#239285](https://github.com/microsoft/vscode/issues/239285) | Mouse not changing to line cursor on text hover. | 0 | visual | 0 | — |
| 138 | [#250072](https://github.com/microsoft/vscode/issues/250072) | Minimap overlaps content by the width of the vertical scrollbar | 0 | visual | 0 | yes |
| 139 | [#250313](https://github.com/microsoft/vscode/issues/250313) | Word-wrap Alt-Z does not work with emojis. | 0 | visual | 0 | — |
| 143 | [#254382](https://github.com/microsoft/vscode/issues/254382) | The column number calculation in the status bar has issues when meeting the full-width characters and emoji characters | 0 | correctness | 0 | yes |
| 144 | [#254424](https://github.com/microsoft/vscode/issues/254424) | Mousewheel Zoom is extremely slow on zoomLevel 1 | 0 | papercut | 0 | yes |
| 147 | [#268272](https://github.com/microsoft/vscode/issues/268272) | Certain buttons are unresponsive in Chrome after monaco-editor version 0.53 | 0 | correctness | 0 | — |
| 153 | [#275754](https://github.com/microsoft/vscode/issues/275754) | Deleting a tab character using backspace doesn't work. | 0 | correctness | 0 | yes |
| 157 | [#283286](https://github.com/microsoft/vscode/issues/283286) | Cannot read properties of undefined (reading 'getModelColumnOfViewPosition') | 0 | correctness | 0 | yes |
| 158 | [#283293](https://github.com/microsoft/vscode/issues/283293) | Cannot read properties of undefined (reading 'getViewLineContent') | 0 | crash | 0 | yes |
| 161 | [#287753](https://github.com/microsoft/vscode/issues/287753) | memory leak related to `domStylesheets` | 0 | perf | 0 | — |

## Feature requests

### Color picker and decorators (9)

| # | Issue | Title | 👍 | Signal | Score |
| --- | --- | --- | --- | --- | --- |
| 1 | [#140899](https://github.com/microsoft/vscode/issues/140899) | Add support for palettes/named colors in the color picker | 62 | backlog-candidate | 100 |
| 12 | [#282673](https://github.com/microsoft/vscode/issues/282673) | Add a setting for color picker to parse ARGB instead of RGBA | 26 | backlog-candidate | 56 |
| 13 | [#139840](https://github.com/microsoft/vscode/issues/139840) | Use modern (CSS color level 4) syntax for colors in the color picker | 27 | backlog-candidate | 52 |
| 17 | [#144036](https://github.com/microsoft/vscode/issues/144036) | Feature Request: Add way of getting all the color presentations in a specific range of a document in the vscode API | 31 | backlog-candidate | 36 |
| 41 | [#199944](https://github.com/microsoft/vscode/issues/199944) | Color picker is far too wide and does not remember when I resize it smaller | 2 | backlog-candidate | 13 |
| 52 | [#31637](https://github.com/microsoft/vscode/issues/31637) | [Feature] Color Picker: Keyboard accessibility | 0 | backlog-candidate | 6 |
| 53 | [#304445](https://github.com/microsoft/vscode/issues/304445) | Add regex filtering for color decorators (editor.colorDecorators) | 0 | backlog-candidate | 6 |
| 60 | [#107491](https://github.com/microsoft/vscode/issues/107491) | Selecting 2 color values and changing them both with color picker | 1 | dormant | 3 |
| 62 | [#227697](https://github.com/microsoft/vscode/issues/227697) | LSP DocumentColor Refresh Request | 0 | backlog-candidate | 3 |

### Font size and line height decorations (8)

| # | Issue | Title | 👍 | Signal | Score |
| --- | --- | --- | --- | --- | --- |
| 2 | [#66468](https://github.com/microsoft/vscode/issues/66468) | Shrink empty lines | 72 | backlog-candidate | 99 |
| 32 | [#263545](https://github.com/microsoft/vscode/issues/263545) | Allow configuring font family, font size and line height via syntactic tokens | 6 | active | 18 |
| 34 | [#237095](https://github.com/microsoft/vscode/issues/237095) | Support Line decoration editor offset retrieval | 10 | backlog-candidate | 16 |
| 36 | [#286157](https://github.com/microsoft/vscode/issues/286157) | Default semantic token styles do not honour custom line heights or font sizes from TextMate themes | 0 | backlog-candidate | 15 |
| 48 | [#286296](https://github.com/microsoft/vscode/issues/286296) | Support decorations that hide characters | 2 | backlog-candidate | 8 |
| 58 | [#256046](https://github.com/microsoft/vscode/issues/256046) | Adopting variable font sizes in `createDecorationsCollection` code | 1 | dormant | 4 |
| 66 | [#249967](https://github.com/microsoft/vscode/issues/249967) | Apply decoration lineHeight on all affected lines after line wrapping | 0 | backlog-candidate | 2 |
| 84 | [#287118](https://github.com/microsoft/vscode/issues/287118) | Make semantic tokens work with font size and line height | 0 | backlog-candidate | 0 |

### Sticky scroll (8)

| # | Issue | Title | 👍 | Signal | Score |
| --- | --- | --- | --- | --- | --- |
| 3 | [#238568](https://github.com/microsoft/vscode/issues/238568) | Allow multiple lines per StickyScroll entry | 37 | backlog-candidate | 93 |
| 5 | [#168428](https://github.com/microsoft/vscode/issues/168428) | Consider a sticky scroll provider API | 48 | backlog-candidate | 89 |
| 6 | [#187834](https://github.com/microsoft/vscode/issues/187834) | [Feature]: Add editor decorations to sticky scroll lines | 42 | backlog-candidate | 78 |
| 18 | [#208406](https://github.com/microsoft/vscode/issues/208406) | Option for sticky scroll to prioritize inner blocks | 14 | backlog-candidate | 33 |
| 35 | [#317702](https://github.com/microsoft/vscode/issues/317702) | Sticky Scroll doesn't handle multi-line function headers | 3 | backlog-candidate | 16 |
| 44 | [#245302](https://github.com/microsoft/vscode/issues/245302) | [Sticky Scroll] If a function consist of multiline arguments, sticky the function also multiline | 6 | backlog-candidate | 11 |
| 78 | [#248486](https://github.com/microsoft/vscode/issues/248486) | Add code to make the cursor always appear below the editor sticky scroll (especially on cursor jump) | 0 | dormant | 0 |
| 80 | [#253608](https://github.com/microsoft/vscode/issues/253608) | Make sticky scroll take into account line heights when the cursor moves | 0 | dormant | 0 |

### Multiple cursors and move lines (3)

| # | Issue | Title | 👍 | Signal | Score |
| --- | --- | --- | --- | --- | --- |
| 4 | [#106502](https://github.com/microsoft/vscode/issues/106502) | Multiple Cursors - Preserve Case | 56 | backlog-candidate | 90 |
| 24 | [#11809](https://github.com/microsoft/vscode/issues/11809) | Move line up/down should support multiple cursors | 14 | backlog-candidate | 21 |
| 39 | [#249132](https://github.com/microsoft/vscode/issues/249132) | Avoid copying a single empty line into the Clipboard | 4 | backlog-candidate | 14 |

### Indentation and formatting (26)

| # | Issue | Title | 👍 | Signal | Score |
| --- | --- | --- | --- | --- | --- |
| 7 | [#66235](https://github.com/microsoft/vscode/issues/66235) | Allow more powerful onEnterRules for cursor alignment | 48 | backlog-candidate | 74 |
| 10 | [#40115](https://github.com/microsoft/vscode/issues/40115) | indent back to line start after enter newline and press up | 45 | backlog-candidate | 69 |
| 11 | [#67678](https://github.com/microsoft/vscode/issues/67678) | Auto-indent on closing brace | 42 | backlog-candidate | 64 |
| 16 | [#86467](https://github.com/microsoft/vscode/issues/86467) | Trailing comma-aware move line up/down | 28 | backlog-candidate | 40 |
| 19 | [#208985](https://github.com/microsoft/vscode/issues/208985) | Declarative treesitter-based indentation rules | 12 | backlog-candidate | 31 |
| 20 | [#84763](https://github.com/microsoft/vscode/issues/84763) | Make "move line" command to work contextually | 21 | backlog-candidate | 30 |
| 21 | [#209805](https://github.com/microsoft/vscode/issues/209805) | Allow users to define their own indentation rules within the settings | 8 | dormant | 23 |
| 22 | [#16998](https://github.com/microsoft/vscode/issues/16998) | Add SmartIndent capability | 14 | backlog-candidate | 22 |
| 25 | [#17281](https://github.com/microsoft/vscode/issues/17281) | Add support for capture groups in onEnterRules | 12 | dormant | 21 |
| 27 | [#294080](https://github.com/microsoft/vscode/issues/294080) | Feature request: command to adjust space-based indentation width, without a formatter | 5 | active | 20 |
| 28 | [#201600](https://github.com/microsoft/vscode/issues/201600) | Enter custom tab size from the UI | 14 | backlog-candidate | 19 |
| 30 | [#19847](https://github.com/microsoft/vscode/issues/19847) | Explore using formatters for indentation adjustment when formatters are available | 11 | backlog-candidate | 18 |
| 33 | [#236296](https://github.com/microsoft/vscode/issues/236296) | Strip characters from `"onEnterRules"` string | 4 | backlog-candidate | 17 |
| 42 | [#228286](https://github.com/microsoft/vscode/issues/228286) | Disabling "Use Tab Stops" should be respected in more indentation contexts | 4 | backlog-candidate | 12 |
| 46 | [#50952](https://github.com/microsoft/vscode/issues/50952) | onEnterRules should be multi-line aware | 5 | dormant | 10 |
| 49 | [#34621](https://github.com/microsoft/vscode/issues/34621) | Unify indentation and formatting APIs | 5 | backlog-candidate | 6 |
| 57 | [#209939](https://github.com/microsoft/vscode/issues/209939) | Add option to trim trailing whitespaces only at the end of lines that contain code | 1 | dormant | 4 |
| 64 | [#251101](https://github.com/microsoft/vscode/issues/251101) | Add onType rules similar to onEnter rules | 1 | dormant | 2 |
| 68 | [#11322](https://github.com/microsoft/vscode/issues/11322) | Remove whitespace and indent to the right spot when the line has more whitespace than necessary | 1 | backlog-candidate | 1 |
| 69 | [#29669](https://github.com/microsoft/vscode/issues/29669) | auto indenting issues with C# files | 1 | backlog-candidate | 1 |
| 70 | [#73559](https://github.com/microsoft/vscode/issues/73559) | Cannot set embedded language indentation rules | 1 | backlog-candidate | 1 |
| 71 | [#201732](https://github.com/microsoft/vscode/issues/201732) | Indent instead of de-indent when soft wrapping long lines in signatures | 0 | dormant | 1 |
| 72 | [#209006](https://github.com/microsoft/vscode/issues/209006) | Edit language configuration files for C++ in order to indent after if/for/while statement with no brace | 0 | backlog-candidate | 1 |
| 75 | [#100667](https://github.com/microsoft/vscode/issues/100667) | Alt+Backspace to delete previous character without smart indentation-aware deletion | 0 | backlog-candidate | 0 |
| 76 | [#171040](https://github.com/microsoft/vscode/issues/171040) | Automatic enter indentation in offside folding languages | 0 | dormant | 0 |
| 81 | [#277764](https://github.com/microsoft/vscode/issues/277764) | Option to not replace aligning spaces during indentation by Tab | 0 | backlog-candidate | 0 |

### Bidi and input method support (3)

| # | Issue | Title | 👍 | Signal | Score |
| --- | --- | --- | --- | --- | --- |
| 8 | [#65648](https://github.com/microsoft/vscode/issues/65648) | Bidi text edit support | 43 | backlog-candidate | 73 |
| 50 | [#229647](https://github.com/microsoft/vscode/issues/229647) | Undo stacks are not granular enough for Korean | 2 | backlog-candidate | 6 |
| 63 | [#254835](https://github.com/microsoft/vscode/issues/254835) | When using macOS with the VoiceOver screen reader, moving word-by-word across a sign character causes the word to be spoken twice | 0 | backlog-candidate | 3 |

### Hover widget (12)

| # | Issue | Title | 👍 | Signal | Score |
| --- | --- | --- | --- | --- | --- |
| 9 | [#247250](https://github.com/microsoft/vscode/issues/247250) | Diagnostics hover sort and clarity | 25 | backlog-candidate | 71 |
| 14 | [#133587](https://github.com/microsoft/vscode/issues/133587) | Allow pinning hover popovers (datatips) | 31 | backlog-candidate | 50 |
| 26 | [#232685](https://github.com/microsoft/vscode/issues/232685) | Test and iterate on TS expandable hover apis | 1 | backlog-candidate | 21 |
| 31 | [#151763](https://github.com/microsoft/vscode/issues/151763) | when hovers are not sticky, alt/opt key should make them temporarily sticky | 7 | backlog-candidate | 18 |
| 51 | [#203767](https://github.com/microsoft/vscode/issues/203767) | click to expect the hover display information to be dynamically updated without refreshing the hover. | 1 | active | 6 |
| 54 | [#241730](https://github.com/microsoft/vscode/issues/241730) | Feedback on experimental expandable hover API | 1 | dormant | 5 |
| 56 | [#205737](https://github.com/microsoft/vscode/issues/205737) | Adopt Editor Hover for "Revert Change" action | 1 | dormant | 4 |
| 61 | [#85196](https://github.com/microsoft/vscode/issues/85196) | LCD: greyscale rendering in editor hover | 0 | backlog-candidate | 3 |
| 65 | [#211063](https://github.com/microsoft/vscode/issues/211063) | Verbose Hover: Hover jumps when there is not enough space | 0 | backlog-candidate | 2 |
| 74 | [#239704](https://github.com/microsoft/vscode/issues/239704) | Hover should scroll when copying with mouse and going out of hover widget | 0 | backlog-candidate | 1 |
| 82 | [#281922](https://github.com/microsoft/vscode/issues/281922) | Make showing delay take precedence over hiding delay | 0 | active | 0 |
| 83 | [#281925](https://github.com/microsoft/vscode/issues/281925) | Apply the hover.hidingDelay to when hover.sticky is false | 0 | active | 0 |

### Syntax highlighting and tokenization (5)

| # | Issue | Title | 👍 | Signal | Score |
| --- | --- | --- | --- | --- | --- |
| 23 | [#284742](https://github.com/microsoft/vscode/issues/284742) | [BUG]: VSCode incorrect syntax highlighting problem | 1 | backlog-candidate | 22 |
| 29 | [#225179](https://github.com/microsoft/vscode/issues/225179) | Python: Improved Bracket Pair Detection for strings that contain `{{` | 4 | backlog-candidate | 19 |
| 43 | [#214857](https://github.com/microsoft/vscode/issues/214857) | lineHighlightBorder should frame all warped line | 6 | backlog-candidate | 11 |
| 45 | [#261241](https://github.com/microsoft/vscode/issues/261241) | Accessibility Issue: "Tokenization is skipped..." | 4 | backlog-candidate | 11 |
| 73 | [#233558](https://github.com/microsoft/vscode/issues/233558) | Zooming types syntax highlighting doesn't look good | 0 | dormant | 1 |

### Other (10)

| # | Issue | Title | 👍 | Signal | Score |
| --- | --- | --- | --- | --- | --- |
| 15 | [#207579](https://github.com/microsoft/vscode/issues/207579) | Refactor preview is missing checkboxes on groups | 23 | backlog-candidate | 50 |
| 37 | [#236218](https://github.com/microsoft/vscode/issues/236218) | Expose the current editor overtype state | 7 | backlog-candidate | 14 |
| 38 | [#255818](https://github.com/microsoft/vscode/issues/255818) | Exploration: prompt completions in panel and inline chat | 5 | backlog-candidate | 14 |
| 40 | [#210437](https://github.com/microsoft/vscode/issues/210437) | option for `editor.autoClosingBrackets` to not auto-close if there's a syntax error in the file | 6 | backlog-candidate | 13 |
| 47 | [#284243](https://github.com/microsoft/vscode/issues/284243) | [Feature] : Add “Open in Integrated Terminal” option to editor tab context menu | 0 | dormant | 9 |
| 55 | [#198122](https://github.com/microsoft/vscode/issues/198122) | Rethink how z-index is assigned within the editor | 1 | backlog-candidate | 4 |
| 59 | [#236191](https://github.com/microsoft/vscode/issues/236191) | Overtype Mode: backspace should insert spaces in its stead | 2 | dormant | 3 |
| 67 | [#279415](https://github.com/microsoft/vscode/issues/279415) | Scrolling through long single line files is terrible. | 0 | backlog-candidate | 2 |
| 77 | [#191648](https://github.com/microsoft/vscode/issues/191648) | Should json sort on save also apply to JsonL | 0 | backlog-candidate | 0 |
| 79 | [#251277](https://github.com/microsoft/vscode/issues/251277) | Function of shortcut key of block comment in c/c++ not strong enough | 0 | dormant | 0 |
