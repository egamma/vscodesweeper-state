# Top issues by theme — rzhao271

Experimental themed view of [the flat ranking](rzhao271.md); themes assigned by the review engine. Rank/score are the lane-wide values. Generated 2026-07-26 13:49 UTC.

## Bugs

### Crashes and filesystem (13)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | [#165016](https://github.com/microsoft/vscode/issues/165016) | VSCode becomes laggy after using it for some time (macOS Ventura) | 70 | freeze | 3/6 Plausible | 100 | — | — |
| 6 | [#195196](https://github.com/microsoft/vscode/issues/195196) | VS Code in Linux freezes when copying file name from file dialog and pasting it into the editor | 2 | freeze | 6/6 Confirmed | 5 | — | `npm run implement -- --issue 195196` |
| 56 | [#235868](https://github.com/microsoft/vscode/issues/235868) | Changing Product Icon Theme crashes watcher.node on Linux | 0 | crash | 3/6 Plausible | 1 | — | — |
| 61 | [#256355](https://github.com/microsoft/vscode/issues/256355) | ENOENT: no such file or directory, uv_cwd | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 94 | [#143978](https://github.com/microsoft/vscode/issues/143978) | Exception when opening an empty test resolver window in OSS | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 103 | [#167934](https://github.com/microsoft/vscode/issues/167934) | EOL says elsewhere modified but no modication was ever done | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 167934` |
| 118 | [#207538](https://github.com/microsoft/vscode/issues/207538) | Same crash when deleteing files thru vscode's explorer, like #91902 | 0 | crash | 3/6 Plausible | 0 | — | — |
| 124 | [#211212](https://github.com/microsoft/vscode/issues/211212) | Process Explorer and `code --status` show all remote server Memory as 0 | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 211212` |
| 127 | [#214101](https://github.com/microsoft/vscode/issues/214101) | Code-oss Crashes | 0 | crash | 3/6 Plausible | 0 | — | — |
| 153 | [#244835](https://github.com/microsoft/vscode/issues/244835) | ERR InstantiationService has been disposed: Error: InstantiationService has been disposed | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 244835` |
| 166 | [#277161](https://github.com/microsoft/vscode/issues/277161) | My computer get slow once I open VS code | 0 | perf | 3/6 Plausible | 0 | — | — |
| 171 | [#286941](https://github.com/microsoft/vscode/issues/286941) | EMFILE: too many open files, open | 0 | none | 3/6 Plausible | 0 | — | — |
| 183 | [#327308](https://github.com/microsoft/vscode/issues/327308) | [Error] unhandlederror-command 'workbench.userDataSync.actions.turnOn' not found | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 327308` |

### Locale and input (6)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2 | [#96041](https://github.com/microsoft/vscode/issues/96041) | unable to input chinese character | 21 | correctness | 6/6 Confirmed | 16 | — | `npm run implement -- --issue 96041` |
| 21 | [#173749](https://github.com/microsoft/vscode/issues/173749) | Sets LANG environment variable to wrong value | 0 | correctness | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 173749` |
| 23 | [#198402](https://github.com/microsoft/vscode/issues/198402) | Code OSS resets locale arg after update | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 28 | [#188015](https://github.com/microsoft/vscode/issues/188015) | touch keyboard come up behavior | 4 | papercut | 4/6 Traced | 1 | yes | `npm run implement -- --issue 188015` |
| 53 | [#212493](https://github.com/microsoft/vscode/issues/212493) | code-insiders crashing with Russian language pack | 0 | crash | 3/6 Plausible | 1 | — | — |
| 57 | [#237663](https://github.com/microsoft/vscode/issues/237663) | How to fix Microsoft Visual studio code, language pack issue from English to French at first launch. | 0 | correctness | 6/6 Confirmed | 1 | — | `npm run implement -- --issue 237663` |

### Install and update (17)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 3 | [#207664](https://github.com/microsoft/vscode/issues/207664) | Can't upgrade on Debian 12.5: "Connection failed" to packages.microsoft.com | 19 | correctness | 2/6 Unverified | 12 | — | — |
| 4 | [#139634](https://github.com/microsoft/vscode/issues/139634) | `code` CLI still opens duplicate VSCode instance in the macOS dock | 30 | papercut | 5/6 Source-confirmed | 9 | — | `npm run implement -- --issue 139634` |
| 5 | [#161586](https://github.com/microsoft/vscode/issues/161586) | Close, minimize and maximize buttons missing on macOS after using the restart to update option | 11 | visual | 3/6 Plausible | 7 | — | `npm run implement -- --issue 161586` |
| 13 | [#326580](https://github.com/microsoft/vscode/issues/326580) | Linux desktop entry bypasses /usr/bin/code wrapper and causes extension initialization failures | 0 | none | — | 3 | — | — |
| 15 | [#133041](https://github.com/microsoft/vscode/issues/133041) | MacOS CLI prof-startup results in hanging program | 2 | freeze | 4/6 Traced | 2 | yes | `npm run implement -- --issue 133041` |
| 18 | [#255581](https://github.com/microsoft/vscode/issues/255581) | VS Code deb package overriding commented out `vscode.sources` | 2 | correctness | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 255581` |
| 25 | [#241636](https://github.com/microsoft/vscode/issues/241636) | Lifecycle Management VSCode snap to core24 ::  Java 21 applications crashing when run from inside VSCode | 0 | crash | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 241636` |
| 26 | [#250274](https://github.com/microsoft/vscode/issues/250274) | Downloaded file will not open in when VS Code is already running | 0 | correctness | 3/6 Plausible | 2 | — | `npm run implement -- --issue 250274` |
| 51 | [#197704](https://github.com/microsoft/vscode/issues/197704) | VSCode forgets all opened documents after update | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 58 | [#238300](https://github.com/microsoft/vscode/issues/238300) | Can't Install Latest VS Code: Dependency Issues with .deb Package | 0 | correctness | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 238300` |
| 75 | [#236132](https://github.com/microsoft/vscode/issues/236132) | RPM %post scriplet deletes /usr/local/bin/code | 1 | papercut | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 236132` |
| 77 | [#316356](https://github.com/microsoft/vscode/issues/316356) | Hidden PowerShell spawned during update check to terminate dllhost.exe processes | 1 | papercut | 2/6 Unverified | 0 | — | — |
| 139 | [#229020](https://github.com/microsoft/vscode/issues/229020) | `xdg-open <folder>` opens folder in VSCode instead of file browser since Ubuntu 24 | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 141 | [#230406](https://github.com/microsoft/vscode/issues/230406) | VSCode opens automatically when I plug in a mass storage device or click on "open with File Manager" (dolphin) | 0 | none | 2/6 Unverified | 0 | — | — |
| 144 | [#234320](https://github.com/microsoft/vscode/issues/234320) | Can't launch additional windows via `code` from cli. | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 167 | [#284669](https://github.com/microsoft/vscode/issues/284669) | Debian package on Chromebook continuously opens files | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 178 | [#311260](https://github.com/microsoft/vscode/issues/311260) | Settings lost after update | 0 | none | 3/6 Plausible | 0 | — | — |

### Font rendering (18)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 7 | [#223483](https://github.com/microsoft/vscode/issues/223483) | Unicode: 🖍️ renders but ✏️ fails | 0 | visual | 5/6 Source-confirmed | 4 | — | — |
| 8 | [#199765](https://github.com/microsoft/vscode/issues/199765) | Font weight incorrectly applied using Iosevka font | 5 | correctness | 2/6 Unverified | 3 | — | — |
| 10 | [#240774](https://github.com/microsoft/vscode/issues/240774) | Font renders badly on light background with Experimental GPU Acceleration enabled | 2 | visual | 5/6 Source-confirmed | 3 | — | `npm run implement -- --issue 240774` |
| 17 | [#231128](https://github.com/microsoft/vscode/issues/231128) | font ligatures that span several textmate scopes assume the font settings of last character (last component of the composite symbol) | 2 | visual | 5/6 Source-confirmed | 2 | — | — |
| 36 | [#286048](https://github.com/microsoft/vscode/issues/286048) | Fonts Ligatures are not working | 2 | none | 3/6 Plausible | 1 | — | `npm run implement -- --issue 286048` |
| 37 | [#228347](https://github.com/microsoft/vscode/issues/228347) | Font Rendering Bug Report: Misalignment of Unicode ` ̂` (U+00302) when using the JuliaMono font | 1 | visual | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 228347` |
| 54 | [#221246](https://github.com/microsoft/vscode/issues/221246) | Vertical font hinting bug solution | 0 | visual | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 221246` |
| 59 | [#247516](https://github.com/microsoft/vscode/issues/247516) | font is not reflected when updated in vscode setting | 0 | correctness | 3/6 Plausible | 1 | — | `npm run implement -- --issue 247516` |
| 112 | [#200799](https://github.com/microsoft/vscode/issues/200799) | "editor.fontLigatures" is invalid for Italic fonts | 0 | none | 3/6 Plausible | 0 | — | `npm run implement -- --issue 200799` |
| 117 | [#207255](https://github.com/microsoft/vscode/issues/207255) | Incorrect editor.fontFamily causes VSCode and the host OS to hang on Linux | 0 | freeze | 4/6 Traced | 0 | yes | `npm run implement -- --issue 207255` |
| 120 | [#208412](https://github.com/microsoft/vscode/issues/208412) | Font does not remain changed (Fonte não permanece alterada) | 0 | none | 3/6 Plausible | 0 | — | — |
| 125 | [#213282](https://github.com/microsoft/vscode/issues/213282) | Bolded font is not detected for custom font family | 0 | none | 2/6 Unverified | 0 | — | — |
| 126 | [#213440](https://github.com/microsoft/vscode/issues/213440) | [Bug] Emoji/Full-width chars are not measured against font | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 213440` |
| 140 | [#229108](https://github.com/microsoft/vscode/issues/229108) | Font Height is different than it should be | 0 | visual | 3/6 Plausible | 0 | — | — |
| 173 | [#293502](https://github.com/microsoft/vscode/issues/293502) | Ligatures show as blank | 0 | visual | 3/6 Plausible | 0 | — | — |
| 177 | [#308705](https://github.com/microsoft/vscode/issues/308705) | Font weight not Applicable | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 180 | [#316939](https://github.com/microsoft/vscode/issues/316939) | fontface generation not context relevant | 0 | none | 3/6 Plausible | 0 | — | — |
| 182 | [#321344](https://github.com/microsoft/vscode/issues/321344) | italic fonts are totally broken in ≥ v1.123 | 0 | visual | 3/6 Plausible | 0 | — | — |

### Settings editor (81)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 12 | [#286191](https://github.com/microsoft/vscode/issues/286191) | Bad settings search results | 0 | correctness | 5/6 Source-confirmed | 3 | — | `npm run implement -- --issue 286191` |
| 16 | [#156635](https://github.com/microsoft/vscode/issues/156635) | Slow to populate the Terminal > Integrated > Tabs: Default Icon dropdown | 2 | perf | 2/6 Unverified | 2 | — | — |
| 20 | [#270019](https://github.com/microsoft/vscode/issues/270019) | Settings editor jumps/resets scrolling | 1 | visual | 2/6 Unverified | 2 | — | `npm run implement -- --issue 270019` |
| 30 | [#145589](https://github.com/microsoft/vscode/issues/145589) | Settings editor scrolls a little when I switch to it | 3 | papercut | 3/6 Plausible | 1 | — | `npm run implement -- --issue 145589` |
| 31 | [#139175](https://github.com/microsoft/vscode/issues/139175) | Can't delete row from setting | 2 | papercut | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 139175` |
| 32 | [#141546](https://github.com/microsoft/vscode/issues/141546) | Outline is empty when using Split JSON mode for settings editor | 2 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 141546` |
| 34 | [#162596](https://github.com/microsoft/vscode/issues/162596) | Settings UI shows no warning (and possibly an incorrect value) when an invalid enum is in settings.json | 2 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 162596` |
| 35 | [#226071](https://github.com/microsoft/vscode/issues/226071) | Unable to pass `target: Workspace`  to `workbench.action.openSettings2` command | 2 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 226071` |
| 38 | [#232467](https://github.com/microsoft/vscode/issues/232467) | Error window when accessing Settings | 1 | freeze | 3/6 Plausible | 1 | — | — |
| 39 | [#268860](https://github.com/microsoft/vscode/issues/268860) | Settings: Opening settings editor with a filter will render settings twice | 1 | perf | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 268860` |
| 40 | [#307703](https://github.com/microsoft/vscode/issues/307703) | Settings view Shift+Tab jumps focus back to editor unexpectedly | 1 | papercut | 6/6 Confirmed | 1 | — | `npm run implement -- --issue 307703` |
| 41 | [#42692](https://github.com/microsoft/vscode/issues/42692) | searching for "IntelliSense" or "completions" doesn't provide expected result | 0 | papercut | 4/6 Traced | 1 | — | — |
| 43 | [#139453](https://github.com/microsoft/vscode/issues/139453) | iPad: Can't search for settings | 0 | papercut | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 139453` |
| 45 | [#145079](https://github.com/microsoft/vscode/issues/145079) | [Codespaces] machine-overridable, experimental setting changes its value when the focus changes | 0 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 145079` |
| 47 | [#167787](https://github.com/microsoft/vscode/issues/167787) | Settings editor scrolls when checking box | 0 | visual | 4/6 Traced | 1 | yes | `npm run implement -- --issue 167787` |
| 48 | [#168680](https://github.com/microsoft/vscode/issues/168680) | Settings editor dropdown is still visible after closing editor | 0 | visual | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 168680` |
| 52 | [#200169](https://github.com/microsoft/vscode/issues/200169) | Smoke test failure: settings editor | 0 | papercut | — | 1 | — | `npm run implement -- --issue 200169` |
| 55 | [#226728](https://github.com/microsoft/vscode/issues/226728) | `SettingsEditor2` shows progress when opening raw settings file | 0 | visual | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 226728` |
| 60 | [#247715](https://github.com/microsoft/vscode/issues/247715) | Settings Editor fails to find a setting with simple substring search | 0 | correctness | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 247715` |
| 63 | [#282762](https://github.com/microsoft/vscode/issues/282762) | Settings window doesn't scroll down enough | 0 | visual | 3/6 Plausible | 1 | — | — |
| 64 | [#297779](https://github.com/microsoft/vscode/issues/297779) | Settings editor keyboard issues | 0 | papercut | 3/6 Plausible | 1 | — | `npm run implement -- --issue 297779` |
| 73 | [#212467](https://github.com/microsoft/vscode/issues/212467) | Redundant `Open Workspace` button appears after `Preferences: Open Workspace Settings (JSON)` | 1 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 212467` |
| 74 | [#235852](https://github.com/microsoft/vscode/issues/235852) | Settings editor search quality epic | 1 | none | — | 0 | — | `npm run implement -- --issue 235852` |
| 76 | [#246026](https://github.com/microsoft/vscode/issues/246026) | Settings Search returning options that have no clear relation to the search | 1 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 246026` |
| 79 | [#78243](https://github.com/microsoft/vscode/issues/78243) | String Settings UI: Multiple edits loses data on Save | 0 | papercut | 4/6 Traced | 0 | yes | `npm run implement -- --issue 78243` |
| 80 | [#104130](https://github.com/microsoft/vscode/issues/104130) | Warn when 'add item' will override an existing value? | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 104130` |
| 81 | [#104261](https://github.com/microsoft/vscode/issues/104261) | Value sometimes lost when trying to add item to settings array | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 104261` |
| 82 | [#106577](https://github.com/microsoft/vscode/issues/106577) | Clicking on settings checkboxes sometimes dropped after changing another setting | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 83 | [#107714](https://github.com/microsoft/vscode/issues/107714) | Tabbing when a setting is selected is jumping back to the setting | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 107714` |
| 90 | [#133963](https://github.com/microsoft/vscode/issues/133963) | Settings editor flickers | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 133963` |
| 91 | [#134592](https://github.com/microsoft/vscode/issues/134592) | markdownDescriptions/markdownEnumDescriptions don't remove ## in settings.json hover | 0 | visual | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 134592` |
| 95 | [#146896](https://github.com/microsoft/vscode/issues/146896) | Setting checkboxes for object boolean values has no focus or active style | 0 | visual | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 146896` |
| 96 | [#149489](https://github.com/microsoft/vscode/issues/149489) | Settings UI list is on top of focus indicator | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 149489` |
| 97 | [#153580](https://github.com/microsoft/vscode/issues/153580) | Delay when switching between settings sections | 0 | perf | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 153580` |
| 101 | [#165175](https://github.com/microsoft/vscode/issues/165175) | Switching between User and Workspace settings often selects a different entry | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 165175` |
| 104 | [#172552](https://github.com/microsoft/vscode/issues/172552) | removing `editor.defaultFormatter` with "Settings" shows red error popup | 0 | papercut | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 172552` |
| 105 | [#174844](https://github.com/microsoft/vscode/issues/174844) | Unable to select settings UI boolean setting descriptions | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 174844` |
| 106 | [#180007](https://github.com/microsoft/vscode/issues/180007) | Strange behavior in settings screen | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 180007` |
| 107 | [#183503](https://github.com/microsoft/vscode/issues/183503) | Settings editor: focus border is cut off | 0 | visual | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 183503` |
| 108 | [#194391](https://github.com/microsoft/vscode/issues/194391) | Settings editor object widget screen cheese | 0 | visual | 2/6 Unverified | 0 | — | `npm run implement -- --issue 194391` |
| 111 | [#199410](https://github.com/microsoft/vscode/issues/199410) | Settings Editor isn't updated until focused | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 199410` |
| 114 | [#204312](https://github.com/microsoft/vscode/issues/204312) | Searching accessibility.voice.keywordActivation setting shows something else | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 115 | [#206329](https://github.com/microsoft/vscode/issues/206329) | Warning tooltips hidden behind bottom panel | 0 | visual | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 206329` |
| 116 | [#207218](https://github.com/microsoft/vscode/issues/207218) | Release notes - clicking on a setting link open setting as a new tab in current editor group | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 207218` |
| 119 | [#207806](https://github.com/microsoft/vscode/issues/207806) | settings files.exclude does not recognize .vscode folder | 0 | none | 5/6 Source-confirmed | 0 | — | — |
| 121 | [#208683](https://github.com/microsoft/vscode/issues/208683) | Can delete another entry while adding entry to object widget in Settings editor | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 208683` |
| 128 | [#214340](https://github.com/microsoft/vscode/issues/214340) | `launch` setting UI is bugged for the workspace tab | 0 | papercut | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 214340` |
| 129 | [#221358](https://github.com/microsoft/vscode/issues/221358) | undo not working in settings search input when i paste some text | 0 | papercut | 4/6 Traced | 0 | — | `npm run implement -- --issue 221358` |
| 131 | [#222170](https://github.com/microsoft/vscode/issues/222170) | Deprecated settings do not show in settings UI even when configured by the user | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 132 | [#226761](https://github.com/microsoft/vscode/issues/226761) | Clicking the link in the description of `window.experimentalControlOverlay` doesn't go to the linked issue | 0 | papercut | 2/6 Unverified | 0 | — | `npm run implement -- --issue 226761` |
| 133 | [#227238](https://github.com/microsoft/vscode/issues/227238) | Zoom : The left commonly used section tree view content gets disappear when viewing the page at 200% browser zoom and a 1280-pixel viewport width. | 0 | visual | 4/6 Traced | 0 | — | `npm run implement -- --issue 227238` |
| 134 | [#227263](https://github.com/microsoft/vscode/issues/227263) | [Accessibility] Tooltips under user settings for extensions missing aria attributes. | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 227263` |
| 137 | [#227528](https://github.com/microsoft/vscode/issues/227528) | Content Lacks Proper Heading Markup | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 227528` |
| 138 | [#227532](https://github.com/microsoft/vscode/issues/227532) | [Accessibility] Remove unnecessary role="tree", role="treeitem" and related aria-aatributes of tree structure in Settings. | 0 | papercut | 4/6 Traced | 0 | — | `npm run implement -- --issue 227532` |
| 143 | [#234246](https://github.com/microsoft/vscode/issues/234246) | Settings Editor Synchronization Error | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 145 | [#234476](https://github.com/microsoft/vscode/issues/234476) | Settings Defaults gets very confused when updating extensions. | 0 | correctness | 4/6 Traced | 0 | — | `npm run implement -- --issue 234476` |
| 146 | [#235755](https://github.com/microsoft/vscode/issues/235755) | js-debug terminal icon surrounded by $() in Settings editor | 0 | visual | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 235755` |
| 148 | [#237496](https://github.com/microsoft/vscode/issues/237496) | User settings UI does not update when configuration changes | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 149 | [#241433](https://github.com/microsoft/vscode/issues/241433) | JSON schema validation of settings.json does not work with `"workbench.settings.useSplitJSON": true` | 0 | correctness | 4/6 Traced | 0 | — | `npm run implement -- --issue 241433` |
| 150 | [#241814](https://github.com/microsoft/vscode/issues/241814) | Settings search "moving selection" vs. "move selection" | 0 | papercut | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 241814` |
| 151 | [#241881](https://github.com/microsoft/vscode/issues/241881) | Support checkboxes for boolean object values | 0 | visual | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 241881` |
| 152 | [#241973](https://github.com/microsoft/vscode/issues/241973) | Inconsistent use of `Experimental` tag in Settings | 0 | papercut | 4/6 Traced | 0 | yes | `npm run implement -- --issue 241973` |
| 154 | [#244944](https://github.com/microsoft/vscode/issues/244944) | Settings UI shifts when switching to and from it | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 244944` |
| 155 | [#245323](https://github.com/microsoft/vscode/issues/245323) | Folder settings label not vertically aligned | 0 | visual | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 245323` |
| 156 | [#248032](https://github.com/microsoft/vscode/issues/248032) | Python Environment setting is not showing when searched | 0 | papercut | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 248032` |
| 157 | [#250159](https://github.com/microsoft/vscode/issues/250159) | Settings search not matching across title + description | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 250159` |
| 158 | [#250756](https://github.com/microsoft/vscode/issues/250756) | [LEAKED DISPOSABLE] in settings editor | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 159 | [#251714](https://github.com/microsoft/vscode/issues/251714) | [LEAKED DISPOSABLE]: selectbox custom markdown | 0 | freeze | 2/6 Unverified | 0 | — | — |
| 160 | [#257270](https://github.com/microsoft/vscode/issues/257270) | Settings UI eats escape, preventing hiding of notifications | 0 | papercut | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 257270` |
| 162 | [#272465](https://github.com/microsoft/vscode/issues/272465) | Warning in dev console: Settings not included in settingsLayout.ts: github.copilot.chat.agent.terminal.allowList, github.copilot.chat.agent.terminal.denyList | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 272465` |
| 163 | [#272480](https://github.com/microsoft/vscode/issues/272480) | Support showing longer setting descriptions in the UI | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 272480` |
| 164 | [#275792](https://github.com/microsoft/vscode/issues/275792) | Resetting various settings can delete comments from settings.json file | 0 | papercut | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 275792` |
| 165 | [#275861](https://github.com/microsoft/vscode/issues/275861) | Unable to reset deprecated setting in the UI | 0 | visual | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 275861` |
| 168 | [#286123](https://github.com/microsoft/vscode/issues/286123) | Settings panel has overlapping settings | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 286123` |
| 170 | [#286430](https://github.com/microsoft/vscode/issues/286430) | Settings editor does not show default values for object settings | 0 | visual | — | 0 | — | `npm run implement -- --issue 286430` |
| 172 | [#293244](https://github.com/microsoft/vscode/issues/293244) | `Esc` doesn't play well with search bar in new settings view | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 293244` |
| 174 | [#295100](https://github.com/microsoft/vscode/issues/295100) | Feature Request: Visual indicator for language-specific setting overrides | 0 | visual | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 295100` |
| 175 | [#301462](https://github.com/microsoft/vscode/issues/301462) | [UX]: Settings menu does not indicate when user settings are overridden by settings.json files in a multi-root workspace | 0 | visual | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 301462` |
| 176 | [#304299](https://github.com/microsoft/vscode/issues/304299) | When scrolling through Settings using the mouse wheel, the Settings window loses focus | 0 | papercut | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 304299` |
| 179 | [#311928](https://github.com/microsoft/vscode/issues/311928) | Settings UI shows undefined for default values in nested configuration keys | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 181 | [#320735](https://github.com/microsoft/vscode/issues/320735) | Settings UI disagrees with actual value for application-scoped setting | 0 | correctness | 4/6 Traced | 0 | — | `npm run implement -- --issue 320735` |

### Emmet expansion (32)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 9 | [#119736](https://github.com/microsoft/vscode/issues/119736) | Emmet JSX HTML abbreviations suggested inside `style` tag | 3 | correctness | 5/6 Source-confirmed | 3 | — | `npm run implement -- --issue 119736` |
| 11 | [#168997](https://github.com/microsoft/vscode/issues/168997) | Emmet completions interfering with Fast Arrow completions | 1 | correctness | 5/6 Source-confirmed | 3 | — | `npm run implement -- --issue 168997` |
| 14 | [#61474](https://github.com/microsoft/vscode/issues/61474) | Expanding emmet abbreviations inside JSX inline functions not working | 2 | correctness | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 61474` |
| 24 | [#233969](https://github.com/microsoft/vscode/issues/233969) | Emmet class expansions retain period in .erb files | 0 | correctness | 4/6 Traced | 2 | — | `npm run implement -- --issue 233969` |
| 27 | [#51537](https://github.com/microsoft/vscode/issues/51537) | Emmet too active in files such as JSX, TSX, and PHP | 6 | papercut | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 51537` |
| 29 | [#126012](https://github.com/microsoft/vscode/issues/126012) | Emmet wrap abbreviation behaviour change in JSX | 3 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 126012` |
| 42 | [#66126](https://github.com/microsoft/vscode/issues/66126) | Emmet toggle comment not working correctly for jsx | 0 | correctness | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 66126` |
| 44 | [#141253](https://github.com/microsoft/vscode/issues/141253) | Emmet breaks with cryptic error message in files that cannot be parsed | 0 | correctness | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 141253` |
| 46 | [#156075](https://github.com/microsoft/vscode/issues/156075) | [Emmet] per-language "Trigger expansion on tab" | 0 | correctness | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 156075` |
| 49 | [#172182](https://github.com/microsoft/vscode/issues/172182) | Emmet extension is getting activate even when no editor is opened | 0 | papercut | 4/6 Traced | 1 | — | `npm run implement -- --issue 172182` |
| 62 | [#266654](https://github.com/microsoft/vscode/issues/266654) | Emmet abbreviations not working when parent element contains inline style | 0 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 266654` |
| 66 | [#104259](https://github.com/microsoft/vscode/issues/104259) | Problem with including markdown as language for Emmet | 2 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 104259` |
| 67 | [#126242](https://github.com/microsoft/vscode/issues/126242) | Custom emmet snippets and issues with template languages | 1 | papercut | 3/6 Plausible | 0 | — | — |
| 68 | [#139553](https://github.com/microsoft/vscode/issues/139553) | Emmet JSX Intellisense doesn't appear when directly next to a closing parentheses | 1 | papercut | 4/6 Traced | 0 | — | `npm run implement -- --issue 139553` |
| 69 | [#157738](https://github.com/microsoft/vscode/issues/157738) | Emmet snippets autocomplete stops midway | 1 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 157738` |
| 70 | [#161431](https://github.com/microsoft/vscode/issues/161431) | Square brackets break Emmet in TypeScript files | 1 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 161431` |
| 71 | [#167497](https://github.com/microsoft/vscode/issues/167497) | Custom Emmet snippets wrap selected text incorrectly | 1 | correctness | 4/6 Traced | 0 | — | `npm run implement -- --issue 167497` |
| 72 | [#174327](https://github.com/microsoft/vscode/issues/174327) | STOP auto adding space after colon on css properties | 1 | papercut | 3/6 Plausible | 0 | — | — |
| 78 | [#45368](https://github.com/microsoft/vscode/issues/45368) | Emmet completions disappear when using bem in the presence of other snippets | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 89 | [#132725](https://github.com/microsoft/vscode/issues/132725) | Emmet with percentage unit does not trigger in CSS-in-JS | 0 | papercut | 4/6 Traced | 0 | — | `npm run implement -- --issue 132725` |
| 92 | [#136532](https://github.com/microsoft/vscode/issues/136532) | Emmet for Yandex BEM doesn't work in JSX | 0 | correctness | 4/6 Traced | 0 | — | `npm run implement -- --issue 136532` |
| 93 | [#142978](https://github.com/microsoft/vscode/issues/142978) | vs code snippet + emmet in js | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 98 | [#156830](https://github.com/microsoft/vscode/issues/156830) | Emmet wrapWithAbbreviation expands the selection when used within JSX attributes | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 156830` |
| 102 | [#167563](https://github.com/microsoft/vscode/issues/167563) | Emmet doesn't work in html documents containing R code | 0 | papercut | 5/6 Source-confirmed | 0 | — | — |
| 109 | [#197890](https://github.com/microsoft/vscode/issues/197890) | Emmet command from snippets.json doesn't show up in intellisense and fails to expand abbreviation | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 113 | [#203285](https://github.com/microsoft/vscode/issues/203285) | "Emmet: Update Tag" selects and updates the wrong tag. | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 203285` |
| 122 | [#208836](https://github.com/microsoft/vscode/issues/208836) | Emmet inconsistent behavior in html for php files | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 130 | [#221548](https://github.com/microsoft/vscode/issues/221548) | Improve HTML writing experience with Emmet | 0 | papercut | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 221548` |
| 135 | [#227329](https://github.com/microsoft/vscode/issues/227329) | Emmet Wrap with fragments do not work at all | 0 | none | 3/6 Plausible | 0 | — | — |
| 136 | [#227444](https://github.com/microsoft/vscode/issues/227444) | Emmet dot snippet is triggered after quotes | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 227444` |
| 142 | [#233078](https://github.com/microsoft/vscode/issues/233078) | Emmet wrap with abbreviation reindents content when used with `pre` | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 233078` |
| 147 | [#237053](https://github.com/microsoft/vscode/issues/237053) | Emmet: Wrap with Abbreviation text on its own new line not working | 0 | correctness | 4/6 Traced | 0 | yes | `npm run implement -- --issue 237053` |

### Window chrome (10)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 19 | [#245785](https://github.com/microsoft/vscode/issues/245785) | Window Controls are Overlaying Menu Bar with RTL OS Locale | 1 | visual | 6/6 Confirmed | 2 | — | `npm run implement -- --issue 245785` |
| 33 | [#149478](https://github.com/microsoft/vscode/issues/149478) | Some keyboard shortcuts ignored in Safari/vscode.dev | 2 | papercut | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 149478` |
| 50 | [#194240](https://github.com/microsoft/vscode/issues/194240) | Command center is hard to find without name | 0 | papercut | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 194240` |
| 65 | [#300404](https://github.com/microsoft/vscode/issues/300404) | Extending VSCode over 2 monitors on Windows cuases rendering issues | 0 | visual | 3/6 Plausible | 1 | — | — |
| 84 | [#127488](https://github.com/microsoft/vscode/issues/127488) | Focus stolen from Iframe search | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 127488` |
| 85 | [#127490](https://github.com/microsoft/vscode/issues/127490) | iframe find highlights look out of place | 0 | visual | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 127490` |
| 88 | [#129856](https://github.com/microsoft/vscode/issues/129856) | Simple split editor should show the full file path in an editor tab tooltip | 0 | papercut | 4/6 Traced | 0 | yes | `npm run implement -- --issue 129856` |
| 99 | [#160518](https://github.com/microsoft/vscode/issues/160518) | Command palette and customize layout hide behind the WCO | 0 | visual | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 160518` |
| 110 | [#198570](https://github.com/microsoft/vscode/issues/198570) | PWA interferes with rendering the WCO on Windows 11 | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 198570` |
| 123 | [#209844](https://github.com/microsoft/vscode/issues/209844) | Website release notes do not load on my iPad | 0 | visual | 3/6 Plausible | 0 | — | — |

### Other (6)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 22 | [#195352](https://github.com/microsoft/vscode/issues/195352) | Integration test failure | 0 | crash | 3/6 Plausible | 2 | — | `npm run implement -- --issue 195352` |
| 86 | [#127521](https://github.com/microsoft/vscode/issues/127521) | [linked editing] does not work right after enter | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 127521` |
| 87 | [#129605](https://github.com/microsoft/vscode/issues/129605) | Required fields aren't being validated | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 129605` |
| 100 | [#161199](https://github.com/microsoft/vscode/issues/161199) | HTML intellisense not filtering on partial text but CSS is | 0 | papercut | 4/6 Traced | 0 | — | `npm run implement -- --issue 161199` |
| 161 | [#258416](https://github.com/microsoft/vscode/issues/258416) | can't copy selection | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 169 | [#286240](https://github.com/microsoft/vscode/issues/286240) | `Copy Breadcrumb Path` doesn't do anything when you're not focused on a symbol | 0 | papercut | 6/6 Confirmed | 0 | — | `npm run implement -- --issue 286240` |

## Feature requests

### Settings scopes profiles (10)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | [#58038](https://github.com/microsoft/vscode/issues/58038) | Settings editor not showing inherited values in workspace scope | 96 | dormant | 100 | `npm run implement -- --issue 58038` |
| 5 | [#167286](https://github.com/microsoft/vscode/issues/167286) | Use quickpick with search and toggles to toggle the setting value per language | 21 | backlog-candidate | 20 | `npm run implement -- --issue 167286` |
| 23 | [#282830](https://github.com/microsoft/vscode/issues/282830) | Link to edit a global setting from a non-default profile opens wrong settings.json file | 0 | backlog-candidate | 4 | `npm run implement -- --issue 282830` |
| 29 | [#145712](https://github.com/microsoft/vscode/issues/145712) | For language-specific settings, modified settings should be shown first | 1 | dormant | 3 | `npm run implement -- --issue 145712` |
| 38 | [#57330](https://github.com/microsoft/vscode/issues/57330) | Settings UI lacks concept of inherited default value | 0 | backlog-candidate | 2 | `npm run implement -- --issue 57330` |
| 43 | [#102146](https://github.com/microsoft/vscode/issues/102146) | Open remote settings GUI when extension executes workbench.action.openSettings with query in remote session | 2 | backlog-candidate | 1 | `npm run implement -- --issue 102146` |
| 65 | [#57370](https://github.com/microsoft/vscode/issues/57370) | Settings decoration: Modified in Folder | 0 | dormant | 0 | `npm run implement -- --issue 57370` |
| 73 | [#141462](https://github.com/microsoft/vscode/issues/141462) | Disable extension action on setting and make setting read only when it is overridden | 0 | backlog-candidate | 0 | `npm run implement -- --issue 141462` |
| 82 | [#218079](https://github.com/microsoft/vscode/issues/218079) | Show the source of an entry as a separate column | 0 | backlog-candidate | 0 | `npm run implement -- --issue 218079` |
| 84 | [#249546](https://github.com/microsoft/vscode/issues/249546) | Filter settings that applies to all profiles | 0 | dormant | 0 | `npm run implement -- --issue 249546` |

### Settings value widgets (8)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 2 | [#22917](https://github.com/microsoft/vscode/issues/22917) | `editor.fontFamily` in settings should suggest list of available monospace fonts | 52 | backlog-candidate | 37 | — |
| 7 | [#128355](https://github.com/microsoft/vscode/issues/128355) | Support font family picker in settings | 12 | dormant | 15 | — |
| 16 | [#56834](https://github.com/microsoft/vscode/issues/56834) | Show file picker for 'path' string settings | 6 | backlog-candidate | 6 | `npm run implement -- --issue 56834` |
| 24 | [#106041](https://github.com/microsoft/vscode/issues/106041) | setting UI: support color settings | 6 | backlog-candidate | 3 | `npm run implement -- --issue 106041` |
| 35 | [#233032](https://github.com/microsoft/vscode/issues/233032) | Allow settings with object widgets to configure labels for `item`/`value` | 2 | backlog-candidate | 2 | `npm run implement -- --issue 233032` |
| 37 | [#280595](https://github.com/microsoft/vscode/issues/280595) | Add item settings UI should offer suggestions | 1 | backlog-candidate | 2 | `npm run implement -- --issue 280595` |
| 75 | [#178850](https://github.com/microsoft/vscode/issues/178850) | Some way to provide an enum of suggested values, but still allow any value | 0 | backlog-candidate | 0 | `npm run implement -- --issue 178850` |
| 79 | [#199858](https://github.com/microsoft/vscode/issues/199858) | I want to set font file names or filepaths into `editor.fontFamily` | 0 | backlog-candidate | 0 | `npm run implement -- --issue 199858` |

### Settings editing actions (9)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 3 | [#131390](https://github.com/microsoft/vscode/issues/131390) | [FR] Option to open the `settings.json` to the side when opening the settings UI editor | 39 | backlog-candidate | 34 | `npm run implement -- --issue 131390` |
| 6 | [#215608](https://github.com/microsoft/vscode/issues/215608) | "A setting has changed that requires a restart to take effect." needs more info | 11 | backlog-candidate | 17 | `npm run implement -- --issue 215608` |
| 22 | [#259670](https://github.com/microsoft/vscode/issues/259670) | Terminal auto approve settings editor integration | 0 | backlog-candidate | 4 | `npm run implement -- --issue 259670` |
| 36 | [#240177](https://github.com/microsoft/vscode/issues/240177) | Settings UI: Insert settings in alphabetical order | 1 | backlog-candidate | 2 | `npm run implement -- --issue 240177` |
| 40 | [#188776](https://github.com/microsoft/vscode/issues/188776) | Settings UI: Right click on setting should behave the same as click on ⚙️ | 0 | backlog-candidate | 2 | `npm run implement -- --issue 188776` |
| 44 | [#58021](https://github.com/microsoft/vscode/issues/58021) | new settings UI: possible to undo a setting change? | 1 | backlog-candidate | 1 | `npm run implement -- --issue 58021` |
| 76 | [#194113](https://github.com/microsoft/vscode/issues/194113) | Use Code Actions For "Edit" In settings.json | 0 | backlog-candidate | 0 | `npm run implement -- --issue 194113` |
| 81 | [#218078](https://github.com/microsoft/vscode/issues/218078) | Show removed entries in the settings editor | 0 | backlog-candidate | 0 | `npm run implement -- --issue 218078` |
| 86 | [#295101](https://github.com/microsoft/vscode/issues/295101) | Feature Request: 'Edit in settings.json' shortcut from Settings GUI | 0 | active | 0 | `npm run implement -- --issue 295101` |

### Settings navigation (9)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 4 | [#70589](https://github.com/microsoft/vscode/issues/70589) | Settings UI is overwhelming for extensions with lots of settings | 25 | backlog-candidate | 29 | `npm run implement -- --issue 70589` |
| 32 | [#272077](https://github.com/microsoft/vscode/issues/272077) | Improve Settings Navigation with Grouping and Breadcrumb Navigation | 0 | active | 3 | `npm run implement -- --issue 272077` |
| 50 | [#148810](https://github.com/microsoft/vscode/issues/148810) | Add filter to select box inside settings UI. | 1 | backlog-candidate | 1 | `npm run implement -- --issue 148810` |
| 54 | [#235785](https://github.com/microsoft/vscode/issues/235785) | Allow for subtraction in Settings editor search queries | 1 | backlog-candidate | 1 | `npm run implement -- --issue 235785` |
| 57 | [#52815](https://github.com/microsoft/vscode/issues/52815) | Add settings editor commands to focus next and previous settings | 0 | backlog-candidate | 1 | `npm run implement -- --issue 52815` |
| 77 | [#197882](https://github.com/microsoft/vscode/issues/197882) | The focused setting should remain in view after clicking "Clear Settings Search Input" | 0 | backlog-candidate | 0 | `npm run implement -- --issue 197882` |
| 83 | [#245199](https://github.com/microsoft/vscode/issues/245199) | Settings editor: allow a query that combines `id` and `tag` | 0 | backlog-candidate | 0 | `npm run implement -- --issue 245199` |
| 85 | [#253338](https://github.com/microsoft/vscode/issues/253338) | Unintuitive how to use ai search in settings view | 0 | backlog-candidate | 0 | `npm run implement -- --issue 253338` |
| 87 | [#317420](https://github.com/microsoft/vscode/issues/317420) | Add search/filter functionality to utility model settings | 0 | active | 0 | `npm run implement -- --issue 317420` |

### Extension settings presentation (7)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 8 | [#191807](https://github.com/microsoft/vscode/issues/191807) | Settings UI doesn't respect custom `title` for extension configuration option | 8 | active | 14 | `npm run implement -- --issue 191807` |
| 18 | [#115409](https://github.com/microsoft/vscode/issues/115409) | Settings editor: Support .enabled to hide other settings in the namespace by convention | 4 | backlog-candidate | 5 | `npm run implement -- --issue 115409` |
| 39 | [#183634](https://github.com/microsoft/vscode/issues/183634) | Show the extension details (instead of just the title) in extension's settings | 0 | backlog-candidate | 2 | `npm run implement -- --issue 183634` |
| 60 | [#176402](https://github.com/microsoft/vscode/issues/176402) | Settings editor doesn't support settings with very long descriptions well like terminal.integrated.commandsToSkipShell | 0 | backlog-candidate | 1 | `npm run implement -- --issue 176402` |
| 61 | [#217810](https://github.com/microsoft/vscode/issues/217810) | Settings editor should have Accessibility TOC entry | 0 | backlog-candidate | 1 | `npm run implement -- --issue 217810` |
| 63 | [#287559](https://github.com/microsoft/vscode/issues/287559) | Provide special UI treatment for security warnings in settings editor/json | 0 | backlog-candidate | 1 | — |
| 78 | [#198690](https://github.com/microsoft/vscode/issues/198690) | Configuration/Settings examples do not show in the settings view for extensions | 0 | backlog-candidate | 0 | `npm run implement -- --issue 198690` |

### Settings JSON editor (11)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 9 | [#269824](https://github.com/microsoft/vscode/issues/269824) | Support naming settings.json as settings.jsonc (and others) | 5 | backlog-candidate | 13 | `npm run implement -- --issue 269824` |
| 10 | [#132921](https://github.com/microsoft/vscode/issues/132921) | Show underline warning in settings JSON file when value matches default | 9 | backlog-candidate | 11 | `npm run implement -- --issue 132921` |
| 13 | [#68386](https://github.com/microsoft/vscode/issues/68386) | Split JSON settings editor discussion issue | 13 | backlog-candidate | 7 | — |
| 20 | [#205207](https://github.com/microsoft/vscode/issues/205207) | Adding support for the uniqueKeys vocabulary in settings.json validation | 6 | backlog-candidate | 4 | `npm run implement -- --issue 205207` |
| 30 | [#235915](https://github.com/microsoft/vscode/issues/235915) | vscode settings.json improvement | 1 | backlog-candidate | 3 | `npm run implement -- --issue 235915` |
| 34 | [#140130](https://github.com/microsoft/vscode/issues/140130) | Show all options in settings.json hovers | 2 | backlog-candidate | 2 | `npm run implement -- --issue 140130` |
| 47 | [#131343](https://github.com/microsoft/vscode/issues/131343) | [Bugs] Issues in new json settings editor | 1 | backlog-candidate | 1 | — |
| 48 | [#140131](https://github.com/microsoft/vscode/issues/140131) | Allow ctrl+click/go to definition to work in settings.json split editor | 1 | backlog-candidate | 1 | `npm run implement -- --issue 140131` |
| 49 | [#140171](https://github.com/microsoft/vscode/issues/140171) | Provide quick fix for deprecated settings in json | 1 | backlog-candidate | 1 | `npm run implement -- --issue 140171` |
| 59 | [#165589](https://github.com/microsoft/vscode/issues/165589) | indicate default settings in the settings.json. | 0 | backlog-candidate | 1 | `npm run implement -- --issue 165589` |
| 80 | [#215941](https://github.com/microsoft/vscode/issues/215941) | Support for command URIs in JSON schema hover cards | 0 | backlog-candidate | 0 | `npm run implement -- --issue 215941` |

### Workbench editor behavior (6)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 11 | [#134336](https://github.com/microsoft/vscode/issues/134336) | Restore all windows when closing them all at once | 7 | backlog-candidate | 10 | `npm run implement -- --issue 134336` |
| 19 | [#110766](https://github.com/microsoft/vscode/issues/110766) | Allow an output to go into full-screen mode | 2 | backlog-candidate | 5 | `npm run implement -- --issue 110766` |
| 33 | [#74342](https://github.com/microsoft/vscode/issues/74342) | [themes] Allow to set a background color for settings / webview editors | 2 | backlog-candidate | 2 | `npm run implement -- --issue 74342` |
| 51 | [#180429](https://github.com/microsoft/vscode/issues/180429) | Allow editor cursor blinking rate to match rate provided by the OS | 1 | backlog-candidate | 1 | `npm run implement -- --issue 180429` |
| 52 | [#202918](https://github.com/microsoft/vscode/issues/202918) | "Feature Request"_VScode "GO" Menu doesn't have "Go to matching pair" | 1 | backlog-candidate | 1 | `npm run implement -- --issue 202918` |
| 62 | [#247247](https://github.com/microsoft/vscode/issues/247247) | can the fullscreen mode AT LEAST display a button to exit fullscreen mode? | 0 | dormant | 1 | `npm run implement -- --issue 247247` |

### Emmet language support (9)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 12 | [#62910](https://github.com/microsoft/vscode/issues/62910) | emmet.includeLanguages for one to many mapping | 15 | active | 8 | `npm run implement -- --issue 62910` |
| 17 | [#64032](https://github.com/microsoft/vscode/issues/64032) | Emmet support for custom HTML tags / attributes | 11 | backlog-candidate | 5 | `npm run implement -- --issue 64032` |
| 46 | [#128038](https://github.com/microsoft/vscode/issues/128038) | Add support for implicit tag names | 1 | backlog-candidate | 1 | `npm run implement -- --issue 128038` |
| 56 | [#49588](https://github.com/microsoft/vscode/issues/49588) | [Emmet] Include should be more like DocumentSelector | 0 | backlog-candidate | 1 | `npm run implement -- --issue 49588` |
| 67 | [#110663](https://github.com/microsoft/vscode/issues/110663) | Missing language IDs for Emmet supported languages | 0 | backlog-candidate | 0 | — |
| 68 | [#117507](https://github.com/microsoft/vscode/issues/117507) | Add json schema for emmet snippets file | 0 | backlog-candidate | 0 | `npm run implement -- --issue 117507` |
| 69 | [#120521](https://github.com/microsoft/vscode/issues/120521) | Enable Emmet abbreviations in `.js` files for CSS-in-JS (object syntax) | 0 | backlog-candidate | 0 | `npm run implement -- --issue 120521` |
| 70 | [#125813](https://github.com/microsoft/vscode/issues/125813) | Please enable emmet.action.updateImageSize in pug. | 0 | backlog-candidate | 0 | `npm run implement -- --issue 125813` |
| 71 | [#137260](https://github.com/microsoft/vscode/issues/137260) | Scope Emmet custom snippets to their respective workspaces | 0 | backlog-candidate | 0 | `npm run implement -- --issue 137260` |

### Linux packaging integration (7)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 14 | [#144969](https://github.com/microsoft/vscode/issues/144969) | Linux: Ship RPM packages for EL8/EL9 alongside EL7 | 11 | backlog-candidate | 7 | — |
| 15 | [#82425](https://github.com/microsoft/vscode/issues/82425) | Support for RHEL 8 in FIPS mode | 8 | backlog-candidate | 6 | `npm run implement -- --issue 82425` |
| 28 | [#286143](https://github.com/microsoft/vscode/issues/286143) | Implement Flatpak portals and an official Flatpak on Flathub | 2 | backlog-candidate | 3 | `npm run implement -- --issue 286143` |
| 31 | [#168389](https://github.com/microsoft/vscode/issues/168389) | Add direct download link for GNU x64/arm builds | 0 | dormant | 3 | `npm run implement -- --issue 168389` |
| 53 | [#207027](https://github.com/microsoft/vscode/issues/207027) | RHEL 8/9 fapolicyd Installation Suggestion | 1 | backlog-candidate | 1 | `npm run implement -- --issue 207027` |
| 55 | [#243211](https://github.com/microsoft/vscode/issues/243211) | [Enhancement] When `(Get-Command code).Path` is set as the value of `$Env:EDITOR`, it doesn't support `systemctl edit`. | 1 | dormant | 1 | `npm run implement -- --issue 243211` |
| 66 | [#93046](https://github.com/microsoft/vscode/issues/93046) | Snap: Register code as an editor in Debian with update-alternatives | 0 | backlog-candidate | 0 | `npm run implement -- --issue 93046` |

### Emmet editing actions (6)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 21 | [#235923](https://github.com/microsoft/vscode/issues/235923) | Emmet Balance for JSON and YAML | 5 | backlog-candidate | 4 | — |
| 25 | [#40096](https://github.com/microsoft/vscode/issues/40096) | Wrap with abbreviation history | 5 | backlog-candidate | 3 | `npm run implement -- --issue 40096` |
| 27 | [#195111](https://github.com/microsoft/vscode/issues/195111) | Enable accepting an Emmet abbreviation suggestion without expanding it | 3 | backlog-candidate | 3 | `npm run implement -- --issue 195111` |
| 45 | [#119811](https://github.com/microsoft/vscode/issues/119811) | when clause contexts for emmet editing | 1 | backlog-candidate | 1 | `npm run implement -- --issue 119811` |
| 58 | [#128124](https://github.com/microsoft/vscode/issues/128124) | [FR] `editor.emmet.action.updateTag` fragment support | 0 | dormant | 1 | `npm run implement -- --issue 128124` |
| 72 | [#139331](https://github.com/microsoft/vscode/issues/139331) | Emmet: update tag | 0 | backlog-candidate | 0 | — |

### Other (6)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 26 | [#45363](https://github.com/microsoft/vscode/issues/45363) | Settings editor should search known keys in object type settings | 3 | backlog-candidate | 3 | `npm run implement -- --issue 45363` |
| 41 | [#239038](https://github.com/microsoft/vscode/issues/239038) | Font Cleartype | 0 | dormant | 2 | `npm run implement -- --issue 239038` |
| 42 | [#94034](https://github.com/microsoft/vscode/issues/94034) | Search for ignored sync settings or extensions | 2 | dormant | 1 | `npm run implement -- --issue 94034` |
| 64 | [#68184](https://github.com/microsoft/vscode/issues/68184) | Support comments in UI editors (settings and keyboard shortcuts) | 1 | backlog-candidate | 0 | `npm run implement -- --issue 68184` |
| 74 | [#142720](https://github.com/microsoft/vscode/issues/142720) | Custom editor group contributions.configuration | 0 | backlog-candidate | 0 | `npm run implement -- --issue 142720` |
| 88 | [#325046](https://github.com/microsoft/vscode/issues/325046) | Feature Request: Official remote MCP server for core VS Code documentation (code.visualstudio.com) | 0 | active | 0 | `npm run implement -- --issue 325046` |
