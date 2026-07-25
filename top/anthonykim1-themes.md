# Top issues by theme — anthonykim1

Experimental themed view of [the flat ranking](anthonykim1.md); themes assigned by the review engine. Rank/score are the lane-wide values. Generated 2026-07-25 19:06 UTC.

## Bugs

### Terminal rendering (71)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | [#286742](https://github.com/microsoft/vscode/issues/286742) | Terminal Font Ligatures stopped working in version 1.108 | 24 | correctness | 2/6 Unverified | 100 | — | — |
| 10 | [#311614](https://github.com/microsoft/vscode/issues/311614) | Integrated terminal rendering becomes corrupted after macOS lock/unlock | 8 | visual | 6/6 Confirmed | 27 | — | `npm run implement -- --issue 311614` |
| 11 | [#308421](https://github.com/microsoft/vscode/issues/308421) | Black background after space in terminal | 7 | visual | 4/6 Traced | 27 | — | `npm run implement -- --issue 308421` |
| 17 | [#274816](https://github.com/microsoft/vscode/issues/274816) | Terminal keeps scrolling up when typing, leaving a mostly blank panel. | 3 | correctness | 5/6 Source-confirmed | 23 | — | `npm run implement -- --issue 274816` |
| 18 | [#299442](https://github.com/microsoft/vscode/issues/299442) | Terminal font broken on latest stable | 8 | visual | 5/6 Source-confirmed | 21 | yes | `npm run implement -- --issue 299442` |
| 25 | [#288682](https://github.com/microsoft/vscode/issues/288682) | Terminal rendering corruption on macOS Apple Silicon - GPU acceleration workaround ineffective | 6 | visual | 5/6 Source-confirmed | 19 | — | `npm run implement -- --issue 288682` |
| 26 | [#283335](https://github.com/microsoft/vscode/issues/283335) | Terminal Sticky Scroll causes incorrect screen size detection for scrolling | 1 | correctness | 5/6 Source-confirmed | 19 | — | `npm run implement -- --issue 283335` |
| 27 | [#308717](https://github.com/microsoft/vscode/issues/308717) | Terminal cursor disappears, outputs raw ANSI, after running (TUI?) scripts | 1 | correctness | 3/6 Plausible | 19 | — | — |
| 47 | [#286989](https://github.com/microsoft/vscode/issues/286989) | Font sharpening for the remote terminal of vscode on the windows platform | 3 | visual | 2/6 Unverified | 15 | — | — |
| 75 | [#286952](https://github.com/microsoft/vscode/issues/286952) | Corrupted console output | 0 | correctness | 3/6 Plausible | 9 | — | — |
| 85 | [#303488](https://github.com/microsoft/vscode/issues/303488) | Terminal briefly shows as completely white with a sad face in the corner when switching back to VS Code after using another app for a while | 1 | visual | 5/6 Source-confirmed | 8 | — | `npm run implement -- --issue 303488` |
| 89 | [#289431](https://github.com/microsoft/vscode/issues/289431) | Terminal output duplication after expanding collapsed output (...) blocks | 0 | visual | 3/6 Plausible | 8 | — | — |
| 92 | [#301378](https://github.com/microsoft/vscode/issues/301378) | Terminal colours wrong from ANSI sequence | 0 | visual | 5/6 Source-confirmed | 8 | — | — |
| 93 | [#304431](https://github.com/microsoft/vscode/issues/304431) | Regression: integrated terminal renders visual cursor at right edge while input position remains correct when running Emacs app inside PowerShell | 0 | visual | 3/6 Plausible | 8 | — | `npm run implement -- --issue 304431` |
| 129 | [#244411](https://github.com/microsoft/vscode/issues/244411) | Emoji as First Character in Terminal Output Causes Display Issue | 1 | visual | 6/6 Confirmed | 5 | — | — |
| 148 | [#288830](https://github.com/microsoft/vscode/issues/288830) | Terminal font becomes bold after deleting and recreating terminal on macOS | 0 | visual | 3/6 Plausible | 5 | — | — |
| 149 | [#308514](https://github.com/microsoft/vscode/issues/308514) | zsh shell terminal goes blank after sometimes | 0 | visual | 3/6 Plausible | 5 | — | — |
| 158 | [#235816](https://github.com/microsoft/vscode/issues/235816) | Highlighted line in terminal moving with resizing the window | 2 | visual | 6/6 Confirmed | 4 | — | `npm run implement -- --issue 235816` |
| 164 | [#235776](https://github.com/microsoft/vscode/issues/235776) | Terminal toggle size to content width vertical scroll bar is in wrong position | 0 | visual | 5/6 Source-confirmed | 4 | — | `npm run implement -- --issue 235776` |
| 174 | [#287983](https://github.com/microsoft/vscode/issues/287983) | OpenType font features (such as alternate characters) not working in the integrated terminal | 0 | correctness | 6/6 Confirmed | 4 | — | — |
| 178 | [#316790](https://github.com/microsoft/vscode/issues/316790) | Random chartacter on each command | 0 | correctness | 5/6 Source-confirmed | 4 | — | — |
| 180 | [#130995](https://github.com/microsoft/vscode/issues/130995) | Blank space above integrated terminal when using decimal value for window.zoomLevel | 2 | visual | 5/6 Source-confirmed | 3 | yes | `npm run implement -- --issue 130995` |
| 182 | [#274296](https://github.com/microsoft/vscode/issues/274296) | Font Ligatures do not work in terminal when gpuAcceleration is on | 2 | visual | 3/6 Plausible | 3 | — | `npm run implement -- --issue 274296` |
| 183 | [#316547](https://github.com/microsoft/vscode/issues/316547) | Integrated terminal leaves stale colored rendering artifacts | 2 | visual | 3/6 Plausible | 3 | — | — |
| 185 | [#237507](https://github.com/microsoft/vscode/issues/237507) | Several color defaults that "need transparency" are opaque | 1 | visual | 5/6 Source-confirmed | 3 | — | `npm run implement -- --issue 237507` |
| 193 | [#133962](https://github.com/microsoft/vscode/issues/133962) | Terminal toggle size to content width acts unexpectedly wrt viewport dimensions, scroll bar and padding | 0 | visual | — | 3 | — | — |
| 200 | [#236328](https://github.com/microsoft/vscode/issues/236328) | Terminal size is wrong | 0 | visual | 3/6 Plausible | 3 | — | `npm run implement -- --issue 236328` |
| 201 | [#240296](https://github.com/microsoft/vscode/issues/240296) | Resuming after OS suspend can cause sticky scroll to not work correctly until hovered | 0 | visual | 5/6 Source-confirmed | 3 | yes | `npm run implement -- --issue 240296` |
| 202 | [#242712](https://github.com/microsoft/vscode/issues/242712) | Line wrapping in terminal search | 0 | visual | 5/6 Source-confirmed | 3 | yes | `npm run implement -- --issue 242712` |
| 207 | [#280025](https://github.com/microsoft/vscode/issues/280025) | Task terminal sticky scroll bug after being cleared | 0 | visual | 5/6 Source-confirmed | 3 | — | `npm run implement -- --issue 280025` |
| 209 | [#280819](https://github.com/microsoft/vscode/issues/280819) | No vertical scrollbar for longer terminal outputs in panel chat | 0 | papercut | 5/6 Source-confirmed | 3 | — | `npm run implement -- --issue 280819` |
| 210 | [#281461](https://github.com/microsoft/vscode/issues/281461) | shellIntegration.ps1 caused Python Debugger with Garbled Text | 0 | visual | 5/6 Source-confirmed | 3 | yes | `npm run implement -- --issue 281461` |
| 211 | [#288689](https://github.com/microsoft/vscode/issues/288689) | Integrated Terminal: Extra 3 Lines Scroll When Using `less` with `-M` Flag | 0 | papercut | 3/6 Plausible | 3 | — | `npm run implement -- --issue 288689` |
| 213 | [#300192](https://github.com/microsoft/vscode/issues/300192) | The xterm.js dimensions error is a key finding - it suggests the terminal renderer is broken   specifically on macOS 26 + Electron 39. | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 214 | [#301317](https://github.com/microsoft/vscode/issues/301317) | Is there a problem with the scrolling in this terminal? Why do I just press one scroll down and go straight to the end | 0 | none | 3/6 Plausible | 3 | — | — |
| 216 | [#307152](https://github.com/microsoft/vscode/issues/307152) | terminal shows garbage | 0 | visual | 3/6 Plausible | 3 | — | — |
| 217 | [#317423](https://github.com/microsoft/vscode/issues/317423) | AgentHost: characters rendered incorrectly in htop | 0 | visual | 6/6 Confirmed | 3 | — | `npm run implement -- --issue 317423` |
| 218 | [#317451](https://github.com/microsoft/vscode/issues/317451) | Weird terminal sizing when open in two clients | 0 | visual | 3/6 Plausible | 3 | — | `npm run implement -- --issue 317451` |
| 244 | [#235777](https://github.com/microsoft/vscode/issues/235777) | Terminal toggle size to content width lacks horizontal scroll bar | 0 | visual | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 235777` |
| 251 | [#274576](https://github.com/microsoft/vscode/issues/274576) | Scroll bar issue | 0 | none | 3/6 Plausible | 2 | — | — |
| 253 | [#282708](https://github.com/microsoft/vscode/issues/282708) | Vite Terminal Output Looks Broken | 0 | visual | 3/6 Plausible | 2 | — | `npm run implement -- --issue 282708` |
| 255 | [#288121](https://github.com/microsoft/vscode/issues/288121) | Termial font edge render incorrectly since 1.108 | 0 | visual | 3/6 Plausible | 2 | — | — |
| 259 | [#309150](https://github.com/microsoft/vscode/issues/309150) | Whitespace in the PowerShell input is rendered in a different colour from the background. | 0 | visual | 3/6 Plausible | 2 | — | `npm run implement -- --issue 309150` |
| 265 | [#317310](https://github.com/microsoft/vscode/issues/317310) | Terminal'de metinler bozuluyor | 0 | visual | 3/6 Plausible | 2 | — | — |
| 267 | [#317969](https://github.com/microsoft/vscode/issues/317969) | Terminal renders as solid color blocks after switching macOS Spaces; text becomes visible only when selected | 0 | visual | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 317969` |
| 270 | [#214389](https://github.com/microsoft/vscode/issues/214389) | Integrated Terminal Distorts Text Upon Restart After Being Terminated | 1 | visual | 6/6 Confirmed | 1 | — | `npm run implement -- --issue 214389` |
| 283 | [#224403](https://github.com/microsoft/vscode/issues/224403) | Cloud (☁️) emoji not rendering in terminal or editor on macOS Monterey 12.3.1 | 0 | visual | 6/6 Confirmed | 1 | — | `npm run implement -- --issue 224403` |
| 288 | [#239853](https://github.com/microsoft/vscode/issues/239853) | ligatures starting with a pipe in the terminal only render correctly if selected | 0 | visual | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 239853` |
| 304 | [#309160](https://github.com/microsoft/vscode/issues/309160) | Terminal: Missing devicePixelRatio listener causes misalignment on zoom | 0 | visual | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 309160` |
| 313 | [#317739](https://github.com/microsoft/vscode/issues/317739) | The last printed message which is not ended with newline character is being disappeared when we relogin the system in ubuntu | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 326 | [#323233](https://github.com/microsoft/vscode/issues/323233) | 长时间运行，电脑夜间不关机，早上打开，命令行窗口内容看不到了 | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 327 | [#323925](https://github.com/microsoft/vscode/issues/323925) | Red lines appeared with recent versions | 0 | visual | 3/6 Plausible | 1 | — | — |
| 331 | [#326585](https://github.com/microsoft/vscode/issues/326585) | Terminal renders badly in light mode with gpu acceleration | 0 | visual | 6/6 Confirmed | 1 | — | — |
| 352 | [#239251](https://github.com/microsoft/vscode/issues/239251) | Terminal resizing/repainting issue when using Zellij | 0 | visual | 3/6 Plausible | 0 | — | — |
| 370 | [#297326](https://github.com/microsoft/vscode/issues/297326) | Integrated terminal: flag emoji overlaps following space cell ("🇬🇧 to" looks like "🇬🇧to") | 0 | visual | 4/6 Traced | 0 | — | `npm run implement -- --issue 297326` |
| 371 | [#297498](https://github.com/microsoft/vscode/issues/297498) | Prompt restoration cursor position gets a bit messed up | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 297498` |
| 373 | [#299759](https://github.com/microsoft/vscode/issues/299759) | Text garbled | 0 | visual | 3/6 Plausible | 0 | — | — |
| 379 | [#306379](https://github.com/microsoft/vscode/issues/306379) | Resizing after terminating CLI session gives weird terminal output | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 306379` |
| 392 | [#312815](https://github.com/microsoft/vscode/issues/312815) | Terminal color changes (via OSC 10/11/12 sequences) do not persist correctly | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 312815` |
| 393 | [#313420](https://github.com/microsoft/vscode/issues/313420) | 终端渲染异常 | 0 | none | 3/6 Plausible | 0 | — | — |
| 398 | [#315497](https://github.com/microsoft/vscode/issues/315497) | Integrated Terminal: Backspace fails to remove multibyte UTF-8 characters from input buffer in Docker (Full characters remain as ghost bytes) | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 399 | [#315782](https://github.com/microsoft/vscode/issues/315782) | Integrated Terminal: GPU texture cache residue under memory pressure | 0 | visual | 3/6 Plausible | 0 | — | — |
| 400 | [#315910](https://github.com/microsoft/vscode/issues/315910) | Integrated terminal restores incorrect height when VS Code is launched via code command in fullscreen | 0 | visual | 4/6 Traced | 0 | — | `npm run implement -- --issue 315910` |
| 408 | [#317488](https://github.com/microsoft/vscode/issues/317488) | Terminal penceresinde metinler genişliğine uyum sağlamıyor | 0 | none | 3/6 Plausible | 0 | — | — |
| 409 | [#317513](https://github.com/microsoft/vscode/issues/317513) | Terminal Console text distortion | 0 | visual | 3/6 Plausible | 0 | — | — |
| 413 | [#318853](https://github.com/microsoft/vscode/issues/318853) | I can't see the terminal | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 425 | [#322583](https://github.com/microsoft/vscode/issues/322583) | sticky scroll in terminal has a bug when inside another terminal | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 436 | [#324559](https://github.com/microsoft/vscode/issues/324559) | terminal tool rendering bug - wrapped text pushes status code out of view | 0 | visual | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 324559` |
| 437 | [#324560](https://github.com/microsoft/vscode/issues/324560) | terminal tool resize doesn't resize like it does in the actual terminal | 0 | visual | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 324560` |
| 438 | [#324562](https://github.com/microsoft/vscode/issues/324562) | some terminal tools are rendered in multiple parts? | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 324562` |
| 447 | [#325743](https://github.com/microsoft/vscode/issues/325743) | Toggle maximized terminal causes codex to render glitches | 0 | visual | 4/6 Traced | 0 | yes | `npm run implement -- --issue 325743` |

### Process lifecycle (47)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2 | [#242891](https://github.com/microsoft/vscode/issues/242891) | Killing tasks does not actually kill them | 22 | correctness | 2/6 Unverified | 74 | — | — |
| 5 | [#210792](https://github.com/microsoft/vscode/issues/210792) | Persistent error : Could not find pty on pty host | 19 | correctness | 3/6 Plausible | 47 | — | `npm run implement -- --issue 210792` |
| 19 | [#223553](https://github.com/microsoft/vscode/issues/223553) | Node process in terminal not killed when VSCode is closed (Windows) | 7 | correctness | 3/6 Plausible | 21 | — | `npm run implement -- --issue 223553` |
| 35 | [#314132](https://github.com/microsoft/vscode/issues/314132) | Panel closes immediately | 4 | correctness | 2/6 Unverified | 16 | — | — |
| 40 | [#250956](https://github.com/microsoft/vscode/issues/250956) | Integrated terminal in remote SSH freezes frequently when any command has a large output | 0 | freeze | 3/6 Plausible | 16 | — | — |
| 52 | [#282433](https://github.com/microsoft/vscode/issues/282433) | Integrated terminal on macOS freezes permanently after running a program that segfaults — Crashpad fatal error kills PTY host | 0 | freeze | 5/6 Source-confirmed | 14 | — | `npm run implement -- --issue 282433` |
| 62 | [#245187](https://github.com/microsoft/vscode/issues/245187) | Multitudes of conhost zombies | 3 | perf | 3/6 Plausible | 11 | — | — |
| 63 | [#234393](https://github.com/microsoft/vscode/issues/234393) | Codes Crashes after about 15 Minutes | 1 | crash | 6/6 Confirmed | 11 | — | `npm run implement -- --issue 234393` |
| 67 | [#236403](https://github.com/microsoft/vscode/issues/236403) | [Remote-SSH Bug]: `rejected promise not handled within 1 second: CodeExpectedError: Could not find pty 7 on pty host` | 0 | correctness | 3/6 Plausible | 11 | — | — |
| 69 | [#309782](https://github.com/microsoft/vscode/issues/309782) | Infinite marker re-registration loop in clearAllMarkers causes UnresponsiveSampleError | 0 | freeze | 5/6 Source-confirmed | 10 | yes | `npm run implement -- --issue 309782` |
| 70 | [#318863](https://github.com/microsoft/vscode/issues/318863) | getCwd() on macOS invokes lsof on every terminal command, generating many syscalls per invocation | 0 | perf | 5/6 Source-confirmed | 10 | yes | `npm run implement -- --issue 318863` |
| 87 | [#285998](https://github.com/microsoft/vscode/issues/285998) | Terminal sessions do not execute when using preLaunchTask | 0 | correctness | 3/6 Plausible | 8 | — | — |
| 91 | [#292823](https://github.com/microsoft/vscode/issues/292823) | new ssh terminal session lost | 0 | correctness | 3/6 Plausible | 8 | — | — |
| 100 | [#196483](https://github.com/microsoft/vscode/issues/196483) | Relaunch terminal hides terminal after reloading window | 1 | correctness | 2/6 Unverified | 7 | — | — |
| 104 | [#276610](https://github.com/microsoft/vscode/issues/276610) | Promise memory leak when creating terminal (frontend) | 0 | perf | 5/6 Source-confirmed | 7 | — | `npm run implement -- --issue 276610` |
| 131 | [#300017](https://github.com/microsoft/vscode/issues/300017) | Git Bash terminal crashes on startup when shellIntegration is enabled (VS Code 1.110.0) | 1 | crash | 3/6 Plausible | 5 | — | — |
| 137 | [#189431](https://github.com/microsoft/vscode/issues/189431) | Persistent background terminals (`hideFromUser = true`, `isTransient = false`) are killed on window reload | 0 | correctness | 5/6 Source-confirmed | 5 | yes | `npm run implement -- --issue 189431` |
| 175 | [#292810](https://github.com/microsoft/vscode/issues/292810) | Vs code terminal process incorrect behaviour | 0 | correctness | 3/6 Plausible | 4 | — | — |
| 196 | [#206735](https://github.com/microsoft/vscode/issues/206735) | `Vscode.Window.onDidCloseTerminal` not invoked even terminal is halted in a specific case | 0 | correctness | 5/6 Source-confirmed | 3 | yes | `npm run implement -- --issue 206735` |
| 198 | [#227936](https://github.com/microsoft/vscode/issues/227936) | Closing a terminal that was reopen in a new window doesn't dispose the terminal object | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 227 | [#316884](https://github.com/microsoft/vscode/issues/316884) | Terminal failing to launch: conpty exception and missing pcwutl.dll after update to v1.120 | 1 | correctness | 3/6 Plausible | 2 | — | — |
| 231 | [#326770](https://github.com/microsoft/vscode/issues/326770) | code is not running in terminal | 1 | none | 3/6 Plausible | 2 | — | — |
| 232 | [#91905](https://github.com/microsoft/vscode/issues/91905) | Awaiting Terminal processId never returns value on Windows | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 233 | [#92868](https://github.com/microsoft/vscode/issues/92868) | Terminal doesn't flush all line data before firing onExit | 0 | correctness | 2/6 Unverified | 2 | — | — |
| 261 | [#311849](https://github.com/microsoft/vscode/issues/311849) | VS Code Integrated Terminal Fails to Launch (ConPTY / winpty error in corporate VM) | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 276 | [#173842](https://github.com/microsoft/vscode/issues/173842) | Task with empty command does not terminate | 0 | papercut | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 173842` |
| 277 | [#185369](https://github.com/microsoft/vscode/issues/185369) | Delayed pty host startup can cause terminal service connection state to stay connecting | 0 | papercut | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 185369` |
| 285 | [#235575](https://github.com/microsoft/vscode/issues/235575) | "Do you want to terminate the active terminal session?" on close for background terminals | 0 | papercut | 6/6 Confirmed | 1 | — | `npm run implement -- --issue 235575` |
| 292 | [#269748](https://github.com/microsoft/vscode/issues/269748) | spawn xterm ENOENT | 0 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 269748` |
| 297 | [#298534](https://github.com/microsoft/vscode/issues/298534) | There are unexpected ghost processes after closing VSCode | 0 | papercut | 3/6 Plausible | 1 | — | — |
| 298 | [#301063](https://github.com/microsoft/vscode/issues/301063) | Zephyr - Build Process Hangs on Subsequent Builds After First Successful Run in VSCode | 0 | none | 3/6 Plausible | 1 | — | `npm run implement -- --issue 301063` |
| 303 | [#307701](https://github.com/microsoft/vscode/issues/307701) | Terminal freezes after pressing Ctrl+C in Git Bash | 0 | freeze | 3/6 Plausible | 1 | — | — |
| 305 | [#312697](https://github.com/microsoft/vscode/issues/312697) | Renaming sessions started from copilot cli has no effect | 0 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 312697` |
| 341 | [#185881](https://github.com/microsoft/vscode/issues/185881) | Restarting the pty host will sometimes dispose of the new processes | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 185881` |
| 342 | [#186067](https://github.com/microsoft/vscode/issues/186067) | Terminal revive is storing sessions where nothing occurs | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 186067` |
| 344 | [#188747](https://github.com/microsoft/vscode/issues/188747) | ptyHost starts when there is only a terminal renderer | 0 | perf | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 188747` |
| 345 | [#191737](https://github.com/microsoft/vscode/issues/191737) | Split terminal hangs when streaming output over remote connection | 0 | freeze | 3/6 Plausible | 0 | — | — |
| 347 | [#222062](https://github.com/microsoft/vscode/issues/222062) | In code-server, disconnected processes eventually block forever on stdout/stderr PTY buffer | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 222062` |
| 366 | [#286990](https://github.com/microsoft/vscode/issues/286990) | Etimedout with powershell execution | 0 | none | 3/6 Plausible | 0 | — | — |
| 421 | [#320893](https://github.com/microsoft/vscode/issues/320893) | open terminal in editor area is shared between vscode instances | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 422 | [#322091](https://github.com/microsoft/vscode/issues/322091) | Terminal is no longer available. | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 426 | [#322673](https://github.com/microsoft/vscode/issues/322673) | Cannot launch conpty) | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 429 | [#324200](https://github.com/microsoft/vscode/issues/324200) | Integrated terminal enters inconsistent state after restart: "Restart Terminal" warnings, xterm.js Cannot read properties of undefined (reading 'dimensions'), terminal shortcuts intermittently stop working | 0 | correctness | 4/6 Traced | 0 | — | — |
| 445 | [#325325](https://github.com/microsoft/vscode/issues/325325) | Terminal not open | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 449 | [#326512](https://github.com/microsoft/vscode/issues/326512) | Crashes sometimes when terminal is displaying, and it losts some changes on settings, and also losts login status | 0 | crash | 3/6 Plausible | 0 | — | — |
| 450 | [#326514](https://github.com/microsoft/vscode/issues/326514) | terminal problem | 0 | none | 3/6 Plausible | 0 | — | — |
| 455 | [#327229](https://github.com/microsoft/vscode/issues/327229) | Terminal fails to launch due to outdated libnode.so dependency on Linux | 0 | correctness | 2/6 Unverified | 0 | — | — |

### Input and shortcuts (39)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 3 | [#126209](https://github.com/microsoft/vscode/issues/126209) | Missed key presses and jumpy cursor in terminal when working remotely with high latency | 42 | correctness | 5/6 Source-confirmed | 65 | — | `npm run implement -- --issue 126209` |
| 4 | [#285769](https://github.com/microsoft/vscode/issues/285769) | The shortcut for "Toggle terminal" now inserts "`" in the editor instead of toggling the terminal | 12 | correctness | 6/6 Confirmed | 50 | — | — |
| 7 | [#286828](https://github.com/microsoft/vscode/issues/286828) | Shortcut for Terminal in Linux no longer works correctly for non-default US keyboards | 9 | correctness | 6/6 Confirmed | 34 | — | — |
| 9 | [#275625](https://github.com/microsoft/vscode/issues/275625) | run_in_terminal tool missed the first char in sending a command into git bash terminal | 9 | correctness | 3/6 Plausible | 30 | — | `npm run implement -- --issue 275625` |
| 21 | [#272927](https://github.com/microsoft/vscode/issues/272927) | Unreliable middle-mouse-button paste in integrated terminal on Linux | 2 | correctness | 5/6 Source-confirmed | 21 | — | `npm run implement -- --issue 272927` |
| 22 | [#320220](https://github.com/microsoft/vscode/issues/320220) | Integrated terminal freezes when pasting plain text copied from LibreOffice on Linux | 1 | freeze | 6/6 Confirmed | 21 | — | `npm run implement -- --issue 320220` |
| 58 | [#287137](https://github.com/microsoft/vscode/issues/287137) | Pasting multiline in terminal when more than 1k characters in version 1.108.0 gets mangled | 1 | correctness | 5/6 Source-confirmed | 12 | — | `npm run implement -- --issue 287137` |
| 59 | [#292969](https://github.com/microsoft/vscode/issues/292969) | Up arrow in PowerShell terminals types the wrong command | 1 | correctness | 3/6 Plausible | 12 | — | `npm run implement -- --issue 292969` |
| 60 | [#299515](https://github.com/microsoft/vscode/issues/299515) | Cmd+C with no selection leaks bare "c" into TUI input on 1.110.0 (selection path works) | 0 | correctness | 2/6 Unverified | 12 | — | — |
| 74 | [#262468](https://github.com/microsoft/vscode/issues/262468) | Ctrl+C not working to end a process in external cmd.exe terminal | 0 | correctness | 5/6 Source-confirmed | 9 | — | — |
| 81 | [#290572](https://github.com/microsoft/vscode/issues/290572) | KeyboardInterrupt seen in terminal when launching python debugger | 4 | papercut | 5/6 Source-confirmed | 8 | — | `npm run implement -- --issue 290572` |
| 82 | [#270158](https://github.com/microsoft/vscode/issues/270158) | [Bug] IME fails in Integrated Terminal when "Screen Reader Optimized" mode is active | 2 | correctness | 6/6 Confirmed | 8 | — | `npm run implement -- --issue 270158` |
| 97 | [#157233](https://github.com/microsoft/vscode/issues/157233) | Integrated terminal: Inserting X selections requires precise mouse positioning | 4 | correctness | 5/6 Source-confirmed | 7 | yes | `npm run implement -- --issue 157233` |
| 101 | [#276999](https://github.com/microsoft/vscode/issues/276999) | Dragging-n-dropping a file with tilde in the name into terminal | 1 | correctness | 5/6 Source-confirmed | 7 | — | `npm run implement -- --issue 276999` |
| 184 | [#209670](https://github.com/microsoft/vscode/issues/209670) | Terminal is zoomed in and out to be very large or small with the mouse wheel while holding Ctrl | 1 | correctness | 5/6 Source-confirmed | 3 | yes | `npm run implement -- --issue 209670` |
| 192 | [#100225](https://github.com/microsoft/vscode/issues/100225) | Data corruptted when pasting large JSON in the terminal (or via sendText) | 0 | correctness | 5/6 Source-confirmed | 3 | yes | `npm run implement -- --issue 100225` |
| 205 | [#272233](https://github.com/microsoft/vscode/issues/272233) | Powershell 7 Ctrl + G from Terminal fails for paths with space | 0 | correctness | 5/6 Source-confirmed | 3 | yes | `npm run implement -- --issue 272233` |
| 212 | [#295255](https://github.com/microsoft/vscode/issues/295255) | Option + left-mouse click causes screen to go blank in interactive programs (like pagers, e.g. less), making copy/paste tedious | 0 | papercut | 5/6 Source-confirmed | 3 | — | — |
| 241 | [#202410](https://github.com/microsoft/vscode/issues/202410) | Aux window: xterm mouse tracking is broken in aux windows | 0 | correctness | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 202410` |
| 242 | [#208680](https://github.com/microsoft/vscode/issues/208680) | VS Code freezes when printing unicode characters in Powershell | 0 | freeze | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 208680` |
| 282 | [#221407](https://github.com/microsoft/vscode/issues/221407) | sudo reboot now shows the characters I typed in zsh for the password via remote SSH | 0 | correctness | 2/6 Unverified | 1 | — | — |
| 295 | [#289841](https://github.com/microsoft/vscode/issues/289841) | VSCode Compatibility Issue: Auto-copy on selection when OneNote is running | 0 | papercut | 3/6 Plausible | 1 | — | — |
| 299 | [#302059](https://github.com/microsoft/vscode/issues/302059) | IME composition text stops even if there is a lot of space in terminal | 0 | correctness | 3/6 Plausible | 1 | — | `npm run implement -- --issue 302059` |
| 308 | [#314769](https://github.com/microsoft/vscode/issues/314769) | PowerShell in Integrated  Terminal: Ctrl+Spacebar not working when shell integration is disabled | 0 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 314769` |
| 323 | [#322425](https://github.com/microsoft/vscode/issues/322425) | Terminal prompt for SSH passphrase auto-submits input when terminal is focused after prompt appears | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 335 | [#141563](https://github.com/microsoft/vscode/issues/141563) | AltGr keypress makes me press Home twice in Terminal for effect. | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 141563` |
| 336 | [#144894](https://github.com/microsoft/vscode/issues/144894) | Some keys like "[" (left bracket) still not working in terminal (German keyboard layout) | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 144894` |
| 338 | [#182301](https://github.com/microsoft/vscode/issues/182301) | Cursor Movement by Option+Click inside folded tmux line on Remote SSH makes vscode server hang | 0 | freeze | 3/6 Plausible | 0 | — | — |
| 356 | [#258071](https://github.com/microsoft/vscode/issues/258071) | "m" appears when trying to run a command while another is in progress in powershell | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 258071` |
| 368 | [#291985](https://github.com/microsoft/vscode/issues/291985) | Bug: Enabled terminal.integrated.altClickMovesCursor alters entire Windows 11 system behavior for Ctrl-C hotkey | 0 | none | 2/6 Unverified | 0 | — | — |
| 374 | [#300494](https://github.com/microsoft/vscode/issues/300494) | Vscode can not recognize  the command + V operation and tab operation to switch lang | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 381 | [#307696](https://github.com/microsoft/vscode/issues/307696) | User confirmation feedback audio is sometimes not heard in terminal | 0 | papercut | 4/6 Traced | 0 | — | `npm run implement -- --issue 307696` |
| 383 | [#308205](https://github.com/microsoft/vscode/issues/308205) | [Mac] Unable to input a backslash in the terminal using the fish shell with a Japanese keyboard | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 308205` |
| 391 | [#312749](https://github.com/microsoft/vscode/issues/312749) | Can't copy text in integrated terminal on Safari (Code Server Web on VM) | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 312749` |
| 404 | [#317053](https://github.com/microsoft/vscode/issues/317053) | move focus to terminal now I cannot enter text into terminal input | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 317053` |
| 412 | [#318294](https://github.com/microsoft/vscode/issues/318294) | Integrated terminal inserts Fcitx candidate selection number into shell input on Linux | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 417 | [#319800](https://github.com/microsoft/vscode/issues/319800) | VSCode + Fish Shell + MacOS: cmd+c & cmd+v not working for copy/paste | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 423 | [#322350](https://github.com/microsoft/vscode/issues/322350) | Toggle Terminal Panel Shortcut disappear/ Does not Work | 0 | papercut | 2/6 Unverified | 0 | — | — |
| 424 | [#322582](https://github.com/microsoft/vscode/issues/322582) | Typed Text Doesn't Show Up in Separate Terminal Window When Main Window is Minimized | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 322582` |

### Agent terminal tools (59)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 6 | [#301804](https://github.com/microsoft/vscode/issues/301804) | Copilot Agent run_in_terminal fails with ENOPRO: No file system provider found in GitHub Codespaces | 7 | correctness | 2/6 Unverified | 45 | — | — |
| 8 | [#286781](https://github.com/microsoft/vscode/issues/286781) | chat stuck waiting for terminal | 0 | freeze | — | 32 | — | — |
| 24 | [#325635](https://github.com/microsoft/vscode/issues/325635) | `chat.tools.terminal.autoApprove` does not work for `npm exec -- ...` commands | 1 | correctness | 5/6 Source-confirmed | 20 | yes | `npm run implement -- --issue 325635` |
| 31 | [#313847](https://github.com/microsoft/vscode/issues/313847) | AgentHost: Terminal shows previous command output until done | 0 | visual | 6/6 Confirmed | 18 | — | `npm run implement -- --issue 313847` |
| 39 | [#324059](https://github.com/microsoft/vscode/issues/324059) | AutoApprove rules are not honored under Default Approvals for terminal commands | 1 | correctness | 3/6 Plausible | 16 | — | `npm run implement -- --issue 324059` |
| 42 | [#313037](https://github.com/microsoft/vscode/issues/313037) | [Error] [GitHub.copilot-chat] unhandlederror-ENOENT: no such file or directory, open '<REDACTED: user-file-path>' | 0 | correctness | 5/6 Source-confirmed | 16 | yes | `npm run implement -- --issue 313037` |
| 43 | [#313038](https://github.com/microsoft/vscode/issues/313038) | [Error] [GitHub.copilot-chat] unhandlederror-ENOENT: no such file or directory, copyfile '<REDACTED: user-file-path>/.vscode/exten... | 0 | correctness | — | 16 | — | `npm run implement -- --issue 313038` |
| 44 | [#323570](https://github.com/microsoft/vscode/issues/323570) | Make sure default vscode terminal auto approve rules are migrated. | 0 | correctness | 3/6 Plausible | 16 | — | `npm run implement -- --issue 323570` |
| 49 | [#317106](https://github.com/microsoft/vscode/issues/317106) | Terminal Tool output not displayed | 0 | correctness | 3/6 Plausible | 15 | — | `npm run implement -- --issue 317106` |
| 50 | [#317652](https://github.com/microsoft/vscode/issues/317652) | No output was produced by the command | 0 | correctness | — | 15 | — | `npm run implement -- --issue 317652` |
| 61 | [#321823](https://github.com/microsoft/vscode/issues/321823) | Local is still available through agent handoff | 0 | correctness | 2/6 Unverified | 12 | — | — |
| 65 | [#307166](https://github.com/microsoft/vscode/issues/307166) | Copilot cannot read the output of `node -v` | 1 | correctness | 5/6 Source-confirmed | 11 | yes | `npm run implement -- --issue 307166` |
| 66 | [#317558](https://github.com/microsoft/vscode/issues/317558) | Copilot agent "Failed to retrieve command output" with Oh My Posh + zsh on macOS | 1 | correctness | 4/6 Traced | 11 | — | `npm run implement -- --issue 317558` |
| 71 | [#323726](https://github.com/microsoft/vscode/issues/323726) | Agents, /code-review command conflicts with Claude Agent SDK | 0 | correctness | 4/6 Traced | 10 | — | `npm run implement -- --issue 323726` |
| 73 | [#285926](https://github.com/microsoft/vscode/issues/285926) | Agent unable to read terminal | 2 | correctness | 3/6 Plausible | 9 | — | `npm run implement -- --issue 285926` |
| 80 | [#324601](https://github.com/microsoft/vscode/issues/324601) | agent not reading from attached session in quick chat | 0 | correctness | 6/6 Confirmed | 9 | — | `npm run implement -- --issue 324601` |
| 83 | [#314918](https://github.com/microsoft/vscode/issues/314918) | Chat: Run command approval prompt truncates command | 2 | correctness | 5/6 Source-confirmed | 8 | yes | `npm run implement -- --issue 314918` |
| 90 | [#290065](https://github.com/microsoft/vscode/issues/290065) | Opening Terminal from an agent confirm-input flow doesn't show all output | 0 | visual | 3/6 Plausible | 8 | — | `npm run implement -- --issue 290065` |
| 95 | [#316588](https://github.com/microsoft/vscode/issues/316588) | Agents Window: permission prompt for writing files outside workspace never appears, causing silent hang | 0 | correctness | 3/6 Plausible | 8 | — | `npm run implement -- --issue 316588` |
| 96 | [#323016](https://github.com/microsoft/vscode/issues/323016) | Agent copilot terminal snapshots can be the only remaining execution record, and misreport edited commands | 0 | correctness | 5/6 Source-confirmed | 8 | yes | `npm run implement -- --issue 323016` |
| 108 | [#316949](https://github.com/microsoft/vscode/issues/316949) | Agent Host Terminal: Multiline shell command run line by line | 0 | correctness | 3/6 Plausible | 7 | — | `npm run implement -- --issue 316949` |
| 110 | [#321772](https://github.com/microsoft/vscode/issues/321772) | Running /analyze-prompt with Agent Host is not able to run the command `chatCustomizationsEvaluations.analyzePrompt` | 0 | correctness | 3/6 Plausible | 7 | — | `npm run implement -- --issue 321772` |
| 115 | [#308584](https://github.com/microsoft/vscode/issues/308584) | Visual Studio Code Agents (Preview) should gracefully handle PowerShell shell fallback on Windows | 2 | correctness | 3/6 Plausible | 6 | — | `npm run implement -- --issue 308584` |
| 124 | [#314926](https://github.com/microsoft/vscode/issues/314926) | `Prompt input` merging command output with command. | 0 | correctness | 3/6 Plausible | 6 | — | `npm run implement -- --issue 314926` |
| 150 | [#311422](https://github.com/microsoft/vscode/issues/311422) | Using compaction twice in a row in Copilot CLI results in error | 0 | correctness | 6/6 Confirmed | 5 | — | `npm run implement -- --issue 311422` |
| 151 | [#311723](https://github.com/microsoft/vscode/issues/311723) | Copilot extension crashes for a folder with large number of files | 0 | crash | 3/6 Plausible | 5 | — | — |
| 153 | [#316282](https://github.com/microsoft/vscode/issues/316282) | Copilot CLI session fails in detached HEAD state due to incorrect branch selection | 0 | correctness | 5/6 Source-confirmed | 5 | yes | `npm run implement -- --issue 316282` |
| 154 | [#316960](https://github.com/microsoft/vscode/issues/316960) | Agent host terminal: Can't exit nano | 0 | correctness | 3/6 Plausible | 5 | — | `npm run implement -- --issue 316960` |
| 155 | [#316976](https://github.com/microsoft/vscode/issues/316976) | Agent Host Terminal: Streaming output rendering buggy in chat pane | 0 | visual | 6/6 Confirmed | 5 | — | `npm run implement -- --issue 316976` |
| 159 | [#320884](https://github.com/microsoft/vscode/issues/320884) | Claude CLI lags when scrolling after VS Code update, text copy unavailable in standalone window | 2 | none | 3/6 Plausible | 4 | — | — |
| 160 | [#307176](https://github.com/microsoft/vscode/issues/307176) | TUI `Shift+Enter` causes SEND request instead of newline | 1 | papercut | 5/6 Source-confirmed | 4 | — | — |
| 162 | [#316791](https://github.com/microsoft/vscode/issues/316791) | Agents App: git commit hangs when commit signing (gpg.format=ssh) is enabled due to missing GIT_ASKPASS environment variable | 1 | freeze | 5/6 Source-confirmed | 4 | — | `npm run implement -- --issue 316791` |
| 260 | [#311404](https://github.com/microsoft/vscode/issues/311404) | pwsh changes to cmd in tab title when copilot CLI launched | 0 | visual | 3/6 Plausible | 2 | — | `npm run implement -- --issue 311404` |
| 262 | [#312607](https://github.com/microsoft/vscode/issues/312607) | Can't "buffer" terminal commands anymore | 0 | correctness | 6/6 Confirmed | 2 | — | `npm run implement -- --issue 312607` |
| 263 | [#314069](https://github.com/microsoft/vscode/issues/314069) | Agent got confused about special characters in output | 0 | correctness | 6/6 Confirmed | 2 | — | `npm run implement -- --issue 314069` |
| 301 | [#304071](https://github.com/microsoft/vscode/issues/304071) | Chat: Terminal Input/Output boxes dissappear when I click them | 0 | visual | 3/6 Plausible | 1 | — | `npm run implement -- --issue 304071` |
| 306 | [#314059](https://github.com/microsoft/vscode/issues/314059) | model and multiplier not showing in Agents app with Copilot CLI | 0 | visual | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 314059` |
| 307 | [#314564](https://github.com/microsoft/vscode/issues/314564) | Copilot | 0 | papercut | 3/6 Plausible | 1 | — | — |
| 310 | [#316274](https://github.com/microsoft/vscode/issues/316274) | AHS session getting stuck in terminal tool call | 0 | freeze | 3/6 Plausible | 1 | — | `npm run implement -- --issue 316274` |
| 312 | [#316996](https://github.com/microsoft/vscode/issues/316996) | [Bug] Incomplete Sanitization in conversationFeature.ts: Double-Escaping Bug Allows Shell Argument Injection in Git Commit Message | 0 | correctness | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 316996` |
| 320 | [#321541](https://github.com/microsoft/vscode/issues/321541) | AHP: Background terminal causes agent response to never finish | 0 | correctness | 3/6 Plausible | 1 | — | `npm run implement -- --issue 321541` |
| 380 | [#307002](https://github.com/microsoft/vscode/issues/307002) | Copilot Chat creating new terminal for every new command - Openrouter Models | 0 | none | 3/6 Plausible | 0 | — | — |
| 394 | [#314177](https://github.com/microsoft/vscode/issues/314177) | Certain models don't show multiplier badge | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 314177` |
| 395 | [#314212](https://github.com/microsoft/vscode/issues/314212) | Agent unable to read large truncated output | 0 | correctness | 2/6 Unverified | 0 | — | `npm run implement -- --issue 314212` |
| 396 | [#314264](https://github.com/microsoft/vscode/issues/314264) | chat.tools.terminal.autoApproveWorkspaceNpmScripts does not auto-approve npm scripts defined in workspace subfolders | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 314264` |
| 397 | [#314630](https://github.com/microsoft/vscode/issues/314630) | Agents: Long terminal names expand past the viewport and cause buttons to go missing | 0 | visual | 4/6 Traced | 0 | — | `npm run implement -- --issue 314630` |
| 402 | [#316904](https://github.com/microsoft/vscode/issues/316904) | AgentHost: Unnecessary tool details | 0 | visual | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 316904` |
| 403 | [#317041](https://github.com/microsoft/vscode/issues/317041) | Chat terminals are nowhere to be found | 0 | papercut | 4/6 Traced | 0 | — | `npm run implement -- --issue 317041` |
| 405 | [#317129](https://github.com/microsoft/vscode/issues/317129) | Queued messages disappear for Copilot CLI | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 317129` |
| 406 | [#317133](https://github.com/microsoft/vscode/issues/317133) | Web fetch tool not rendering correctly | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 317133` |
| 407 | [#317134](https://github.com/microsoft/vscode/issues/317134) | Create and edit file looks odd in Copilot CLI | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 317134` |
| 414 | [#319472](https://github.com/microsoft/vscode/issues/319472) | Get  --ozone-platform found error when launching agent host on linux | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 319472` |
| 418 | [#319856](https://github.com/microsoft/vscode/issues/319856) | Default Approvals do not prompt for subsequent send_to_terminal inputs after starting an interactive shell, allowing destructive commands without confirmation | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 319856` |
| 433 | [#324459](https://github.com/microsoft/vscode/issues/324459) | Chat asks to read a file after I've explicitly attached a chat session | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 324459` |
| 434 | [#324467](https://github.com/microsoft/vscode/issues/324467) | Typing `#sessions:` doesn't work | 0 | correctness | 4/6 Traced | 0 | yes | `npm run implement -- --issue 324467` |
| 435 | [#324468](https://github.com/microsoft/vscode/issues/324468) | Icon for session context chip gone after reload | 0 | visual | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 324468` |
| 439 | [#324605](https://github.com/microsoft/vscode/issues/324605) | inconsistent/nonexistent sessions picker | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 324605` |
| 440 | [#324616](https://github.com/microsoft/vscode/issues/324616) | Session attaching needs to work in the Agents Window | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 324616` |
| 444 | [#325208](https://github.com/microsoft/vscode/issues/325208) | Agent host terminal preview is missing scrollbar | 0 | visual | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 325208` |

### Terminal API (36)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 12 | [#316556](https://github.com/microsoft/vscode/issues/316556) | shellIntegration.executeCommand() read() stream never ends for multi-line commands on Linux/bash | 0 | correctness | 5/6 Source-confirmed | 26 | — | — |
| 30 | [#308254](https://github.com/microsoft/vscode/issues/308254) | [Unhandled Error] potential listener LEAK detected, popular | 0 | perf | 5/6 Source-confirmed | 18 | yes | `npm run implement -- --issue 308254` |
| 36 | [#308890](https://github.com/microsoft/vscode/issues/308890) | Incorrect command line argument quoting/escaping in `extHostTerminalShellIntegration.ts` | 2 | correctness | 5/6 Source-confirmed | 16 | — | `npm run implement -- --issue 308890` |
| 77 | [#301191](https://github.com/microsoft/vscode/issues/301191) | [Regression] [Unhandled Error] Cannot read properties of undefined (reading 'dimensions') | 0 | correctness | 2/6 Unverified | 9 | — | `npm run implement -- --issue 301191` |
| 79 | [#324548](https://github.com/microsoft/vscode/issues/324548) | [Error] unhandlederror-cannot add a decoration for a command {} with no marker | 0 | correctness | 5/6 Source-confirmed | 9 | — | `npm run implement -- --issue 324548` |
| 123 | [#248799](https://github.com/microsoft/vscode/issues/248799) | mac / zsh: onDidEndTerminalShellExecution event never fires for second executeCommand | 0 | correctness | 3/6 Plausible | 6 | — | `npm run implement -- --issue 248799` |
| 147 | [#283096](https://github.com/microsoft/vscode/issues/283096) | Error activating the extension in tests of another extension | 0 | freeze | 5/6 Source-confirmed | 5 | yes | `npm run implement -- --issue 283096` |
| 161 | [#307703](https://github.com/microsoft/vscode/issues/307703) | Settings view Shift+Tab jumps focus back to editor unexpectedly | 1 | papercut | 6/6 Confirmed | 4 | — | `npm run implement -- --issue 307703` |
| 220 | [#321748](https://github.com/microsoft/vscode/issues/321748) | Terminal auto-approval fails for git diff -- <path> despite "git diff" allow rule | 0 | correctness | 5/6 Source-confirmed | 3 | — | `npm run implement -- --issue 321748` |
| 221 | [#325545](https://github.com/microsoft/vscode/issues/325545) | Terminal Environment popup is clipped when content exceeds available height and action buttons become inaccessible | 0 | visual | 4/6 Traced | 3 | yes | `npm run implement -- --issue 325545` |
| 234 | [#124584](https://github.com/microsoft/vscode/issues/124584) | Terminal.creationOptions API shows default options in remotes | 0 | correctness | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 124584` |
| 235 | [#125389](https://github.com/microsoft/vscode/issues/125389) | Remote terminals don't respect strictEnv | 0 | correctness | 2/6 Unverified | 2 | — | — |
| 271 | [#226878](https://github.com/microsoft/vscode/issues/226878) | No events fired for a restored terminal | 1 | correctness | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 226878` |
| 278 | [#190974](https://github.com/microsoft/vscode/issues/190974) | env.shell API should not be the empty string on start up | 0 | correctness | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 190974` |
| 279 | [#206920](https://github.com/microsoft/vscode/issues/206920) | tmux thinks terminal is less wide in terminal window | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 289 | [#240288](https://github.com/microsoft/vscode/issues/240288) | ShellType API does not detect `gitbash` on windows | 0 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 240288` |
| 317 | [#320042](https://github.com/microsoft/vscode/issues/320042) | In the server version of VSCode, the menu item is missing in the upper-right corner of the new terminal window | 0 | none | — | 1 | — | — |
| 318 | [#320938](https://github.com/microsoft/vscode/issues/320938) | Cmd+ Enter produce "Cannot read properties of undefined (reading 'execCode') | 0 | correctness | — | 1 | — | — |
| 319 | [#321159](https://github.com/microsoft/vscode/issues/321159) | Terminal: glyphs overlap / are too close with Iosevka on Linux (WebGL renderer) | 0 | visual | 3/6 Plausible | 1 | — | `npm run implement -- --issue 321159` |
| 321 | [#321632](https://github.com/microsoft/vscode/issues/321632) | Chat: system notification XML tags rendered raw in conversation | 0 | visual | 2/6 Unverified | 1 | — | `npm run implement -- --issue 321632` |
| 333 | [#197387](https://github.com/microsoft/vscode/issues/197387) | terminal confirm on exit dialog appears when no child process running after reload | 1 | papercut | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 197387` |
| 334 | [#119103](https://github.com/microsoft/vscode/issues/119103) | Type ahead should turn off temporarily when it fails on a line | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 119103` |
| 337 | [#165816](https://github.com/microsoft/vscode/issues/165816) | _sendLineData can freeze the renderer for seconds for very long lines | 0 | freeze | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 165816` |
| 339 | [#183349](https://github.com/microsoft/vscode/issues/183349) | terminalTextSelected context key is false when text is selected in the active terminal but is not focused | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 183349` |
| 348 | [#228992](https://github.com/microsoft/vscode/issues/228992) | Terminal message displays Gibberish upon creation by window.createTerminal() API randomly | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 228992` |
| 372 | [#297506](https://github.com/microsoft/vscode/issues/297506) | awrit didn't load | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 297506` |
| 376 | [#302233](https://github.com/microsoft/vscode/issues/302233) | github.copilot.chat.cli.terminalLinks.enabled needs auth to show up in the Settings? | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 302233` |
| 382 | [#307704](https://github.com/microsoft/vscode/issues/307704) | Cannot navigate to full list of deprecated extensions via Tab key | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 307704` |
| 384 | [#309553](https://github.com/microsoft/vscode/issues/309553) | Opening external terminal using shortcut doesn't focus the terminal | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 309553` |
| 386 | [#311323](https://github.com/microsoft/vscode/issues/311323) | gemini-cli not reflected in terminal title | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 311323` |
| 387 | [#311324](https://github.com/microsoft/vscode/issues/311324) | Terminal title changes in unexpected ways | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 311324` |
| 388 | [#311421](https://github.com/microsoft/vscode/issues/311421) | Gemini CLI title remains "node" in Bash on Fedora | 0 | papercut | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 311421` |
| 389 | [#311424](https://github.com/microsoft/vscode/issues/311424) | Codex in Bash on Fedora leaves node as its title | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 311424` |
| 390 | [#312696](https://github.com/microsoft/vscode/issues/312696) | copilot --resume uses the old name of the session | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 312696` |
| 401 | [#316222](https://github.com/microsoft/vscode/issues/316222) | Run in terminal sync mode returns stale `^C` in Remote-SSH Windows/PowerShell | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 316222` |
| 411 | [#317823](https://github.com/microsoft/vscode/issues/317823) | Terminal env var ⚠ notification truncated overlapped by terminal | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 317823` |

### Environment and cwd (45)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 13 | [#200777](https://github.com/microsoft/vscode/issues/200777) | Preserve terminal cwd when reviving process | 4 | correctness | 5/6 Source-confirmed | 25 | yes | `npm run implement -- --issue 200777` |
| 15 | [#207521](https://github.com/microsoft/vscode/issues/207521) | If a URI contains an authority component, then the path component must either be empty or begin with a slash ("/") character | 10 | correctness | 2/6 Unverified | 23 | — | — |
| 20 | [#212508](https://github.com/microsoft/vscode/issues/212508) | After updating to version 1.89 my $HOME path is incorrect. And not able to change it. | 6 | correctness | 5/6 Source-confirmed | 21 | — | — |
| 29 | [#277958](https://github.com/microsoft/vscode/issues/277958) | GitHub.copilot-chat incorrectly contributing Windows PATH components to Linux terminal (via Remote-SSH) | 3 | correctness | 5/6 Source-confirmed | 18 | yes | `npm run implement -- --issue 277958` |
| 37 | [#240539](https://github.com/microsoft/vscode/issues/240539) | \ path separators are interpreted as escape sequences when HOME is set in bash terminal | 1 | correctness | 5/6 Source-confirmed | 16 | — | `npm run implement -- --issue 240539` |
| 41 | [#285729](https://github.com/microsoft/vscode/issues/285729) | Problem in VS Code task with -Command parameter | 0 | correctness | 3/6 Plausible | 16 | — | — |
| 56 | [#280104](https://github.com/microsoft/vscode/issues/280104) | terminal profile can't resolve `${workspaceFolder}` in vscode remote workspaces | 0 | correctness | 5/6 Source-confirmed | 13 | — | `npm run implement -- --issue 280104` |
| 57 | [#289922](https://github.com/microsoft/vscode/issues/289922) | Terminal being opened in wrong directory in multi-root workspace | 2 | correctness | 3/6 Plausible | 12 | — | `npm run implement -- --issue 289922` |
| 64 | [#236401](https://github.com/microsoft/vscode/issues/236401) | remote-cli `code` command works in bash, but zsh or tmux | 1 | correctness | 5/6 Source-confirmed | 11 | — | `npm run implement -- --issue 236401` |
| 72 | [#142520](https://github.com/microsoft/vscode/issues/142520) | Opening a terminal in Multi-root workspace appends cwd option for new terminal. | 4 | correctness | 5/6 Source-confirmed | 9 | — | `npm run implement -- --issue 142520` |
| 84 | [#319266](https://github.com/microsoft/vscode/issues/319266) | VS Code's terminal fails to load PowerShell modules yet they successfully load in Windows Terminal (PowerShell 7+) | 2 | correctness | 6/6 Confirmed | 8 | — | — |
| 94 | [#309032](https://github.com/microsoft/vscode/issues/309032) | Integrated terminal on Windows can start with stale PATH and fail to resolve npm while standalone PowerShell works | 0 | correctness | — | 8 | — | — |
| 112 | [#172099](https://github.com/microsoft/vscode/issues/172099) | Variables `relativeFile` and `relativeFileDirname` use backslashes in WSL when used in keyboard shortcuts | 3 | correctness | 5/6 Source-confirmed | 6 | — | `npm run implement -- --issue 172099` |
| 116 | [#189166](https://github.com/microsoft/vscode/issues/189166) | Cannot launch new terminals in multi-root workspace on a remote machine unless 'terminal.integrated.cwd' is unset | 1 | correctness | 5/6 Source-confirmed | 6 | — | `npm run implement -- --issue 189166` |
| 126 | [#205013](https://github.com/microsoft/vscode/issues/205013) | VSCode terminal seems to construct environment in a strange way | 2 | correctness | 4/6 Traced | 5 | — | `npm run implement -- --issue 205013` |
| 127 | [#257333](https://github.com/microsoft/vscode/issues/257333) | Script ran from task no longer finds module in cwd | 2 | correctness | 3/6 Plausible | 5 | — | `npm run implement -- --issue 257333` |
| 128 | [#224140](https://github.com/microsoft/vscode/issues/224140) | Slashes in `terminal.integrated.cwd` converted to backslashes on Linux remote host and Windows host | 1 | correctness | 5/6 Source-confirmed | 5 | — | `npm run implement -- --issue 224140` |
| 134 | [#81231](https://github.com/microsoft/vscode/issues/81231) | Remote terminals don't resolve variables when restored on startup | 0 | correctness | 2/6 Unverified | 5 | — | — |
| 135 | [#167969](https://github.com/microsoft/vscode/issues/167969) | Tasks use Windows instead of WSL env on WSL | 0 | correctness | 5/6 Source-confirmed | 5 | yes | `npm run implement -- --issue 167969` |
| 136 | [#168195](https://github.com/microsoft/vscode/issues/168195) | Remote SSH incorrectly strips empty but defined environment variables from shell environment | 0 | correctness | 3/6 Plausible | 5 | — | `npm run implement -- --issue 168195` |
| 138 | [#192462](https://github.com/microsoft/vscode/issues/192462) | New terminal not opening in default project path in remote connection | 0 | correctness | 5/6 Source-confirmed | 5 | — | `npm run implement -- --issue 192462` |
| 140 | [#230425](https://github.com/microsoft/vscode/issues/230425) | Cannot set working directory when opening a new terminal when using vscode remotes (WSL and SSH) | 0 | correctness | 3/6 Plausible | 5 | — | `npm run implement -- --issue 230425` |
| 144 | [#258173](https://github.com/microsoft/vscode/issues/258173) | Split terminal with inherited paths does not work when starting from a WSL terminal | 0 | correctness | 4/6 Traced | 5 | yes | `npm run implement -- --issue 258173` |
| 152 | [#314381](https://github.com/microsoft/vscode/issues/314381) | Integrated terminals can inherit env vars from a previously opened repository/session | 0 | correctness | 4/6 Traced | 5 | — | `npm run implement -- --issue 314381` |
| 176 | [#298314](https://github.com/microsoft/vscode/issues/298314) | Integrated terminal loses PATH in tcsh when Copilot/Copilot Chat are forced to UI via `remote.extensionKind` | 0 | correctness | 3/6 Plausible | 4 | — | — |
| 194 | [#151715](https://github.com/microsoft/vscode/issues/151715) | Extension variables are not expanded in integrated terminal profiles | 0 | correctness | 5/6 Source-confirmed | 3 | yes | `npm run implement -- --issue 151715` |
| 195 | [#199417](https://github.com/microsoft/vscode/issues/199417) | dragging terminals between windows sometimes fails | 0 | correctness | 3/6 Plausible | 3 | — | `npm run implement -- --issue 199417` |
| 228 | [#320063](https://github.com/microsoft/vscode/issues/320063) | "Open New External Terminal" does not correctly work with GNOME's default terminal emulator `ptyxis` . Fails to open window  that is navigated to the directory | 1 | correctness | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 320063` |
| 287 | [#236404](https://github.com/microsoft/vscode/issues/236404) | Devcontainers ignores terminal profile settings from settings.json when opening local integrated terminal | 0 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 236404` |
| 300 | [#302261](https://github.com/microsoft/vscode/issues/302261) | Terminal Issue: terminal.integrated.automationProfile.windows does not respect "env" object | 0 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 302261` |
| 328 | [#324001](https://github.com/microsoft/vscode/issues/324001) | Pressing new terminal in new terminal window leads to terminal in wrong location | 0 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 324001` |
| 332 | [#327454](https://github.com/microsoft/vscode/issues/327454) | Environment variables from the first VS Code launch carry over to later windows | 0 | correctness | 5/6 Source-confirmed | 1 | — | — |
| 351 | [#236398](https://github.com/microsoft/vscode/issues/236398) | Clicking URLs in terminal while connecting are opened only after connecting | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 236398` |
| 360 | [#262544](https://github.com/microsoft/vscode/issues/262544) | Task with process option prepends workspace directory | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 262544` |
| 363 | [#285153](https://github.com/microsoft/vscode/issues/285153) | Network proxy setting not inherit when start vscode from desktop launcher bar icon on Ubuntu. | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 415 | [#319552](https://github.com/microsoft/vscode/issues/319552) | Windows: PowerShell Store detection throws ENOENT when scanning %LOCALAPPDATA%\Microsoft\WindowsApps | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 319552` |
| 416 | [#319624](https://github.com/microsoft/vscode/issues/319624) | environment variables ( in linux ) not fetching from all sources in extension development | 0 | none | 3/6 Plausible | 0 | — | — |
| 419 | [#320120](https://github.com/microsoft/vscode/issues/320120) | Powershell doesn't open correctly for Next.js app router files | 0 | correctness | 6/6 Confirmed | 0 | — | — |
| 442 | [#324748](https://github.com/microsoft/vscode/issues/324748) | `ELECTRON_GET_USE_PROXY` excluded from integrated terminal environments | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 324748` |
| 451 | [#326576](https://github.com/microsoft/vscode/issues/326576) | VS Code launches `wsl.exe -l -q` in a visible console window on systems without WSL installed | 0 | visual | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 326576` |
| 452 | [#326905](https://github.com/microsoft/vscode/issues/326905) | Module not found error in Output panel when running Python script via Remote SSH, despite successful execution in the integrated terminal | 0 | none | — | 0 | — | — |
| 454 | [#327100](https://github.com/microsoft/vscode/issues/327100) | When running C++ code, VS Code automatically navigates to the MinGW bin directory to run it | 0 | none | — | 0 | — | — |
| 457 | [#327349](https://github.com/microsoft/vscode/issues/327349) | macOS terminal cwd detection mis-parses lsof output when an open file path contains "cwd" | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 327349` |
| 458 | [#327443](https://github.com/microsoft/vscode/issues/327443) | New shells always show warning icons | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 459 | [#327472](https://github.com/microsoft/vscode/issues/327472) | "Environment changes relaunch" doesn't work | 0 | none | 3/6 Plausible | 0 | — | — |

### Shell integration (46)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 14 | [#187185](https://github.com/microsoft/vscode/issues/187185) | Shell integration breaks prompt when using Fish shell with Tide prompt | 12 | correctness | 5/6 Source-confirmed | 24 | yes | `npm run implement -- --issue 187185` |
| 16 | [#269581](https://github.com/microsoft/vscode/issues/269581) | sed: command not found shows up when opening gitbash terminal | 3 | correctness | 5/6 Source-confirmed | 23 | yes | `npm run implement -- --issue 269581` |
| 23 | [#293127](https://github.com/microsoft/vscode/issues/293127) | VS code integrated Terminal Line Continuation not working (Powershell) #269107 | 0 | correctness | 4/6 Traced | 21 | — | `npm run implement -- --issue 293127` |
| 33 | [#269741](https://github.com/microsoft/vscode/issues/269741) | Shell integration is lost when ps1 activate script are ran twice | 0 | correctness | 5/6 Source-confirmed | 17 | — | `npm run implement -- --issue 269741` |
| 38 | [#283151](https://github.com/microsoft/vscode/issues/283151) | Terminal Shell Integration requires update for newer PowerShell 7.4+ ConstrainedLanguage AUDIT mode | 1 | correctness | 5/6 Source-confirmed | 16 | — | `npm run implement -- --issue 283151` |
| 45 | [#289100](https://github.com/microsoft/vscode/issues/289100) | VS Code Shell Integration Breaks PSReadLine History Navigation in PowerShell Terminal | 5 | correctness | 3/6 Plausible | 15 | — | — |
| 54 | [#232741](https://github.com/microsoft/vscode/issues/232741) | terminal history does not work or gets wrong version of fish_history - Linux Snap | 3 | correctness | 5/6 Source-confirmed | 13 | — | — |
| 55 | [#250764](https://github.com/microsoft/vscode/issues/250764) | onDidEndTerminalShellExecution not received for commands that contain newlines | 0 | correctness | 5/6 Source-confirmed | 13 | — | `npm run implement -- --issue 250764` |
| 68 | [#254724](https://github.com/microsoft/vscode/issues/254724) | Shell integration fails with command sequences and hangs with sleep commands | 0 | correctness | 5/6 Source-confirmed | 10 | — | — |
| 88 | [#287181](https://github.com/microsoft/vscode/issues/287181) | Activate.ps1 messes up shell integration exit code | 0 | correctness | 5/6 Source-confirmed | 8 | yes | `npm run implement -- --issue 287181` |
| 99 | [#288972](https://github.com/microsoft/vscode/issues/288972) | Dead keys broken in terminal with US International keyboard when shell integration is enabled | 3 | correctness | 3/6 Plausible | 7 | — | `npm run implement -- --issue 288972` |
| 102 | [#293758](https://github.com/microsoft/vscode/issues/293758) | Shell integration breaks grml-zsh-config by setting ZDOTDIR | 1 | correctness | 5/6 Source-confirmed | 7 | — | `npm run implement -- --issue 293758` |
| 105 | [#282352](https://github.com/microsoft/vscode/issues/282352) | Code suggestions in the terminal do not work properly in the zsh environment | 0 | correctness | 3/6 Plausible | 7 | — | `npm run implement -- --issue 282352` |
| 111 | [#151105](https://github.com/microsoft/vscode/issues/151105) | Some shells don't remember history | 4 | papercut | 5/6 Source-confirmed | 6 | — | `npm run implement -- --issue 151105` |
| 114 | [#303608](https://github.com/microsoft/vscode/issues/303608) | No output was produced by the command with zsh right-prompt. #298175 | 2 | correctness | 3/6 Plausible | 6 | — | — |
| 118 | [#248561](https://github.com/microsoft/vscode/issues/248561) | `terminal.shellIntegration.env.value.PATH` uses wrong separators for `git bash` | 1 | correctness | 5/6 Source-confirmed | 6 | — | `npm run implement -- --issue 248561` |
| 119 | [#263193](https://github.com/microsoft/vscode/issues/263193) | Shell integration doesn't work in Kali Linux's default bash setup | 1 | correctness | 6/6 Confirmed | 6 | — | `npm run implement -- --issue 263193` |
| 130 | [#245607](https://github.com/microsoft/vscode/issues/245607) | In fish, can't make shell integration and starship both work at the same time | 1 | correctness | 5/6 Source-confirmed | 5 | — | `npm run implement -- --issue 245607` |
| 132 | [#318347](https://github.com/microsoft/vscode/issues/318347) | chat.tools.terminal.autoApprove (and related terminal tool auto-approval) does not match inner commands when the command line uses common wrappers (timeout, bash -c, env, sudo time, etc.) | 1 | correctness | 5/6 Source-confirmed | 5 | yes | `npm run implement -- --issue 318347` |
| 139 | [#214909](https://github.com/microsoft/vscode/issues/214909) | Terminal does not detect failure in activated environments when activated using PS1 script | 0 | correctness | 5/6 Source-confirmed | 5 | yes | `npm run implement -- --issue 214909` |
| 142 | [#245260](https://github.com/microsoft/vscode/issues/245260) | ShellIntegration-bash is not properly escaping windows paths | 0 | correctness | 5/6 Source-confirmed | 5 | yes | `npm run implement -- --issue 245260` |
| 145 | [#258457](https://github.com/microsoft/vscode/issues/258457) | Shell integration not working correctly for `Pseudoterminal` | 0 | correctness | 5/6 Source-confirmed | 5 | yes | `npm run implement -- --issue 258457` |
| 157 | [#171137](https://github.com/microsoft/vscode/issues/171137) | Terminal - vscode.dev - remote tunnels - No shell integration in default terminal that is opened | 2 | correctness | 3/6 Plausible | 4 | — | `npm run implement -- --issue 171137` |
| 163 | [#169407](https://github.com/microsoft/vscode/issues/169407) | Exit code isn't handled correctly in fish shell integration | 0 | correctness | 5/6 Source-confirmed | 4 | yes | `npm run implement -- --issue 169407` |
| 167 | [#263504](https://github.com/microsoft/vscode/issues/263504) | Restored integrated terminal sessions not using workspace profile | 0 | correctness | 5/6 Source-confirmed | 4 | — | `npm run implement -- --issue 263504` |
| 168 | [#266489](https://github.com/microsoft/vscode/issues/266489) | Shell integration fails with set -u | 0 | correctness | 6/6 Confirmed | 4 | — | `npm run implement -- --issue 266489` |
| 171 | [#275029](https://github.com/microsoft/vscode/issues/275029) | Terminal Completion: `commandLine` context sometimes includes the shell indicator and the working directory | 0 | correctness | 5/6 Source-confirmed | 4 | — | `npm run implement -- --issue 275029` |
| 172 | [#286505](https://github.com/microsoft/vscode/issues/286505) | Fish integration `__vsc_nonce` is broken | 0 | correctness | 5/6 Source-confirmed | 4 | — | — |
| 237 | [#170868](https://github.com/microsoft/vscode/issues/170868) | Adapt the bash of busybox. | 0 | correctness | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 170868` |
| 239 | [#183972](https://github.com/microsoft/vscode/issues/183972) | Nonce does not appear to work on fish shell | 0 | correctness | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 183972` |
| 268 | [#226891](https://github.com/microsoft/vscode/issues/226891) | `onDidChangeTerminalShellIntegration` fired twice on terminal creation without `reason` property | 2 | papercut | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 226891` |
| 275 | [#323975](https://github.com/microsoft/vscode/issues/323975) | shellIntegration.ps1 Script digital signatures do not match file hashes | 1 | papercut | 3/6 Plausible | 1 | — | — |
| 340 | [#184940](https://github.com/microsoft/vscode/issues/184940) | Shell integration run recent command shows an error when run in a remote | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 349 | [#233845](https://github.com/microsoft/vscode/issues/233845) | Bash shellIntegration: error messages when running with `set -u` | 0 | papercut | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 233845` |
| 353 | [#241855](https://github.com/microsoft/vscode/issues/241855) | Bash env doesn't update on first `unset` | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 241855` |
| 354 | [#241951](https://github.com/microsoft/vscode/issues/241951) | Shell Type not resolving properly | 0 | correctness | 4/6 Traced | 0 | yes | `npm run implement -- --issue 241951` |
| 355 | [#245657](https://github.com/microsoft/vscode/issues/245657) | Hover from terminal warning icon clips `Show Environment Contribution` statusbar option | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 245657` |
| 358 | [#260373](https://github.com/microsoft/vscode/issues/260373) | Continuation prompt not handled properly in python shell integration script | 0 | visual | 4/6 Traced | 0 | yes | `npm run implement -- --issue 260373` |
| 359 | [#260376](https://github.com/microsoft/vscode/issues/260376) | New line is not being detected in prompt input model for Python shell integration | 0 | papercut | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 260376` |
| 364 | [#286188](https://github.com/microsoft/vscode/issues/286188) | Fish run recent command messed up when commands ran with Copilot | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 286188` |
| 367 | [#287037](https://github.com/microsoft/vscode/issues/287037) | Confusing OSC-8 vs. working hyperlink behavior. | 0 | correctness | 6/6 Confirmed | 0 | — | — |
| 377 | [#302280](https://github.com/microsoft/vscode/issues/302280) | Copilot says shell integration is set up correctly, but tool call says it's not | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 302280` |
| 430 | [#324392](https://github.com/microsoft/vscode/issues/324392) | Shell integration: executeCommand().read() stream and onDidEndTerminalShellExecution both permanently silent (zero data) for certain multi-line / subshell command shapes | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 432 | [#324453](https://github.com/microsoft/vscode/issues/324453) | shellIntegration.executeCommand().read() stream yields no data for commands containing emoji on Windows/PowerShell | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 448 | [#325913](https://github.com/microsoft/vscode/issues/325913) | Bash shell integration: PROMPT_COMMAND array entries from other profile scripts get misreported as the current command | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 325913` |
| 456 | [#327238](https://github.com/microsoft/vscode/issues/327238) | Terminal bell sounds on every prompt when Shell Integration is enabled (OSC 633 BEL terminator appears to trigger bell) | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 327238` |

### Links and search (23)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 28 | [#242371](https://github.com/microsoft/vscode/issues/242371) | Support local hyperlink ansi escapes in the integrated terminal | 5 | correctness | 2/6 Unverified | 18 | — | — |
| 46 | [#211443](https://github.com/microsoft/vscode/issues/211443) | OSC 8 terminal hyperlinks don't work properly in Remote - WSL | 4 | correctness | 5/6 Source-confirmed | 15 | yes | `npm run implement -- --issue 211443` |
| 53 | [#212109](https://github.com/microsoft/vscode/issues/212109) | Parentheses `()` and square brackets `[]` in file names can break terminal links (eg. next.js dynamic file paths) | 3 | correctness | 5/6 Source-confirmed | 13 | — | `npm run implement -- --issue 212109` |
| 76 | [#301043](https://github.com/microsoft/vscode/issues/301043) | Terminal search, incorrect result | 0 | correctness | 3/6 Plausible | 9 | — | — |
| 113 | [#296608](https://github.com/microsoft/vscode/issues/296608) | Error when searching after opening file by clicking link in terminal with line number | 2 | correctness | 5/6 Source-confirmed | 6 | yes | `npm run implement -- --issue 296608` |
| 117 | [#212334](https://github.com/microsoft/vscode/issues/212334) | Terminal file link detection can't detect paths containing spaces | 1 | correctness | 5/6 Source-confirmed | 6 | — | `npm run implement -- --issue 212334` |
| 122 | [#230365](https://github.com/microsoft/vscode/issues/230365) | Terminal search gives up after only 1000 search highlights | 0 | correctness | 3/6 Plausible | 6 | — | `npm run implement -- --issue 230365` |
| 179 | [#241646](https://github.com/microsoft/vscode/issues/241646) | Blue hyperlink when hovering over link in terminal does not work | 3 | papercut | 5/6 Source-confirmed | 3 | — | `npm run implement -- --issue 241646` |
| 199 | [#233131](https://github.com/microsoft/vscode/issues/233131) | Terminal: failed link detection on WSL filesystem when wordSeparators contains slashes | 0 | correctness | 4/6 Traced | 3 | — | `npm run implement -- --issue 233131` |
| 215 | [#303101](https://github.com/microsoft/vscode/issues/303101) | Terminal link detection includes Chinese period (。) as part of URL | 0 | papercut | 3/6 Plausible | 3 | — | `npm run implement -- --issue 303101` |
| 222 | [#273097](https://github.com/microsoft/vscode/issues/273097) | Terminal link hover stopped being a link | 2 | papercut | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 273097` |
| 245 | [#244698](https://github.com/microsoft/vscode/issues/244698) | Terminal Links highlight correct link but open incorrect one | 0 | correctness | 6/6 Confirmed | 2 | — | `npm run implement -- --issue 244698` |
| 248 | [#261897](https://github.com/microsoft/vscode/issues/261897) | Find and Search/Find in Files with selection from Terminal doesn't do regex escaping | 0 | papercut | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 261897` |
| 290 | [#248342](https://github.com/microsoft/vscode/issues/248342) | Terminal path linking weirdness with dotnet build | 0 | papercut | 3/6 Plausible | 1 | — | `npm run implement -- --issue 248342` |
| 314 | [#318254](https://github.com/microsoft/vscode/issues/318254) | OSC52 unsupported in `code serve-web` | 0 | correctness | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 318254` |
| 315 | [#318709](https://github.com/microsoft/vscode/issues/318709) | Terminal local file links are mis-tokenized around CJK punctuation | 0 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 318709` |
| 322 | [#322078](https://github.com/microsoft/vscode/issues/322078) | Ctrl-Clicking a link in the terminal opens the file path on the line above instead | 0 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 322078` |
| 362 | [#279614](https://github.com/microsoft/vscode/issues/279614) | Mousing over content after OSC 633 resurrects OSC 8 tooltip hover (ie, hyperlink tooltips are re-appearing when they shouldn't) | 0 | papercut | 2/6 Unverified | 0 | — | — |
| 369 | [#297309](https://github.com/microsoft/vscode/issues/297309) | CTRL-F freezes terminal with large history on initial search | 0 | freeze | 4/6 Traced | 0 | — | `npm run implement -- --issue 297309` |
| 375 | [#302224](https://github.com/microsoft/vscode/issues/302224) | `plan.md` and other relative paths not getting underlined (but still clickable) | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 302224` |
| 385 | [#310171](https://github.com/microsoft/vscode/issues/310171) | File links in terminal behave incorrectly when the file contains unicode characters | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 310171` |
| 428 | [#323833](https://github.com/microsoft/vscode/issues/323833) | Terminal search fails to find visible string, highlights persist | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 431 | [#324440](https://github.com/microsoft/vscode/issues/324440) | Got a big search bar. | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 324440` |

### Tasks and commands (25)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 34 | [#242351](https://github.com/microsoft/vscode/issues/242351) | Terminal zoom with mouse wheel conflicts with scrolling | 4 | correctness | 5/6 Source-confirmed | 16 | — | `npm run implement -- --issue 242351` |
| 51 | [#95021](https://github.com/microsoft/vscode/issues/95021) | Task terminal truncates long/quick output. | 6 | correctness | 4/6 Traced | 14 | — | `npm run implement -- --issue 95021` |
| 98 | [#87843](https://github.com/microsoft/vscode/issues/87843) | Pseudoterminal handleInput does not catch Terminal.sendText | 3 | correctness | 3/6 Plausible | 7 | — | `npm run implement -- --issue 87843` |
| 107 | [#303668](https://github.com/microsoft/vscode/issues/303668) | Terminal: Run Active File In Active Terminal fails when folder name contains a "~" | 0 | correctness | 5/6 Source-confirmed | 7 | yes | `npm run implement -- --issue 303668` |
| 166 | [#252447](https://github.com/microsoft/vscode/issues/252447) | Re-running all task mixes up the original terminal tab order | 0 | visual | — | 4 | — | `npm run implement -- --issue 252447` |
| 169 | [#270585](https://github.com/microsoft/vscode/issues/270585) | Task commands retrieved from a command won't be recognized as absolute | 0 | correctness | 5/6 Source-confirmed | 4 | — | — |
| 173 | [#286640](https://github.com/microsoft/vscode/issues/286640) | c++ debugging issue | 0 | none | 3/6 Plausible | 4 | — | — |
| 189 | [#295891](https://github.com/microsoft/vscode/issues/295891) | VS Code after version 1.107.1 breaks PowerShell Intellisense | 1 | correctness | 6/6 Confirmed | 3 | — | — |
| 208 | [#280363](https://github.com/microsoft/vscode/issues/280363) | Terminal Intellisense breaks with PowerShell when using Starship | 0 | correctness | 5/6 Source-confirmed | 3 | yes | `npm run implement -- --issue 280363` |
| 230 | [#326138](https://github.com/microsoft/vscode/issues/326138) | "Run C/C++ File" fails in PowerShell if path has spaces (missing & call operator) | 1 | none | — | 2 | — | — |
| 236 | [#125824](https://github.com/microsoft/vscode/issues/125824) | The exitCode in onDidEndTaskProcess event callback is 0 when user hits Ctrl-C on the task. | 0 | correctness | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 125824` |
| 240 | [#199466](https://github.com/microsoft/vscode/issues/199466) | Aux window terminals have messed up cursor blinking | 0 | visual | 3/6 Plausible | 2 | — | `npm run implement -- --issue 199466` |
| 243 | [#230233](https://github.com/microsoft/vscode/issues/230233) | Terminal search highlights update really slowly | 0 | papercut | 6/6 Confirmed | 2 | — | `npm run implement -- --issue 230233` |
| 254 | [#285724](https://github.com/microsoft/vscode/issues/285724) | Windo CMD Terminal Auto Open | 0 | none | 3/6 Plausible | 2 | — | — |
| 286 | [#235670](https://github.com/microsoft/vscode/issues/235670) | Run Recent Command does not cover multi-line Python REPL commands | 0 | correctness | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 235670` |
| 291 | [#258693](https://github.com/microsoft/vscode/issues/258693) | Slight flash of suggestion details in python repl | 0 | visual | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 258693` |
| 302 | [#306092](https://github.com/microsoft/vscode/issues/306092) | IndentationError when executing nested for-loops via “Run Selection/Line in Python Terminal” | 0 | correctness | — | 1 | — | — |
| 357 | [#258688](https://github.com/microsoft/vscode/issues/258688) | Some suggestion syntax highlighting missing in repl suggestions | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 258688` |
| 365 | [#286465](https://github.com/microsoft/vscode/issues/286465) | New task is created when one already exists from folder | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 286465` |
| 420 | [#320742](https://github.com/microsoft/vscode/issues/320742) | command 'python.execInTerminal-icon' not found | 0 | none | 3/6 Plausible | 0 | — | — |
| 427 | [#323254](https://github.com/microsoft/vscode/issues/323254) | Unterminated String Literal | 0 | none | 3/6 Plausible | 0 | — | — |
| 441 | [#324694](https://github.com/microsoft/vscode/issues/324694) | Failed task terminal title is not red when active/focus | 0 | visual | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 324694` |
| 443 | [#325086](https://github.com/microsoft/vscode/issues/325086) | Incorrect terminal output length in Python while using input() | 0 | none | 3/6 Plausible | 0 | — | — |
| 446 | [#325424](https://github.com/microsoft/vscode/issues/325424) | Problem with COM port selection | 0 | none | — | 0 | — | — |
| 453 | [#326939](https://github.com/microsoft/vscode/issues/326939) | Type: Bug  Extension: Microsoft C/C++ (ms-vscode.cpptools) 1.32.2  Environment: - VS Code: 1.129.1 - Commit: 8a7abeba6e03ea3af87bfbce9a1b7e48fed567b8 - macOS: 26.5.2 (Build 25F84) - Architecture: Apple Silicon / arm64 - Compiler: Apple clang++ - Debugger c | 0 | none | — | 0 | — | — |

### Other (68)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 32 | [#317578](https://github.com/microsoft/vscode/issues/317578) | Delayed Python environment auto-activation can corrupt active terminal input | 2 | correctness | 5/6 Source-confirmed | 17 | — | `npm run implement -- --issue 317578` |
| 48 | [#293399](https://github.com/microsoft/vscode/issues/293399) | "Cannot launch a terminal process in an empty workspace" restriction is problematic | 2 | correctness | 5/6 Source-confirmed | 15 | yes | `npm run implement -- --issue 293399` |
| 78 | [#320947](https://github.com/microsoft/vscode/issues/320947) | Copilot Chat add extra characters to terminal commands | 0 | correctness | 5/6 Source-confirmed | 9 | yes | `npm run implement -- --issue 320947` |
| 86 | [#279177](https://github.com/microsoft/vscode/issues/279177) | Possible memory leak in debounce | 0 | perf | 5/6 Source-confirmed | 8 | yes | `npm run implement -- --issue 279177` |
| 103 | [#240709](https://github.com/microsoft/vscode/issues/240709) | PATH variable in PowerShell profile missing paths | 0 | correctness | 3/6 Plausible | 7 | — | `npm run implement -- --issue 240709` |
| 106 | [#295086](https://github.com/microsoft/vscode/issues/295086) | Very long terminal titles | 0 | visual | 2/6 Unverified | 7 | — | `npm run implement -- --issue 295086` |
| 109 | [#319058](https://github.com/microsoft/vscode/issues/319058) | Shell integration for fish breaks command status code return | 0 | correctness | 5/6 Source-confirmed | 7 | — | `npm run implement -- --issue 319058` |
| 120 | [#270437](https://github.com/microsoft/vscode/issues/270437) | Bad terminal history navigation after terminal clear command | 1 | visual | 2/6 Unverified | 6 | — | — |
| 121 | [#288356](https://github.com/microsoft/vscode/issues/288356) | win32 input mode has modifiers only scrolling to bottom | 1 | correctness | 2/6 Unverified | 6 | — | — |
| 125 | [#215617](https://github.com/microsoft/vscode/issues/215617) | Long prompt text with shell integration causes "ghost" text display in the VSCode bash terminal | 3 | visual | 5/6 Source-confirmed | 5 | — | `npm run implement -- --issue 215617` |
| 133 | [#320589](https://github.com/microsoft/vscode/issues/320589) | WSL terminal: opencode CLI Chinese output garbled on copy-paste | 1 | correctness | 2/6 Unverified | 5 | — | — |
| 141 | [#232258](https://github.com/microsoft/vscode/issues/232258) | Powershell 7 Ctrl + G from Terminal fails for paths with space | 0 | correctness | 5/6 Source-confirmed | 5 | — | `npm run implement -- --issue 232258` |
| 143 | [#250916](https://github.com/microsoft/vscode/issues/250916) | Terminal is extremely sluggish when using fish shell with `fish-async-prompt` extension | 0 | perf | 3/6 Plausible | 5 | — | `npm run implement -- --issue 250916` |
| 146 | [#265274](https://github.com/microsoft/vscode/issues/265274) | Task commandline and respective arguments should be escaped and quoted better | 0 | correctness | — | 5 | — | `npm run implement -- --issue 265274` |
| 156 | [#307601](https://github.com/microsoft/vscode/issues/307601) | Daily terminal relaunch warning for Git auth provider on Windows | 3 | papercut | 4/6 Traced | 4 | — | `npm run implement -- --issue 307601` |
| 165 | [#237517](https://github.com/microsoft/vscode/issues/237517) | Incorrect TerminalShellExecution exit code | 0 | correctness | 5/6 Source-confirmed | 4 | — | `npm run implement -- --issue 237517` |
| 170 | [#272967](https://github.com/microsoft/vscode/issues/272967) | Make behavior of "Show integrated terminal" more closely match "Create new terminal" in multi-root workspace | 0 | correctness | — | 4 | — | — |
| 177 | [#314698](https://github.com/microsoft/vscode/issues/314698) | Terminal is missing last line | 0 | visual | 3/6 Plausible | 4 | — | `npm run implement -- --issue 314698` |
| 181 | [#169264](https://github.com/microsoft/vscode/issues/169264) | zsh HISTFILE Hardcoded after #168396 fix | 2 | correctness | 5/6 Source-confirmed | 3 | — | `npm run implement -- --issue 169264` |
| 186 | [#239296](https://github.com/microsoft/vscode/issues/239296) | Console stacktraces when resizing window/pane using fish shell and tide prompt | 1 | papercut | 3/6 Plausible | 3 | — | `npm run implement -- --issue 239296` |
| 187 | [#285762](https://github.com/microsoft/vscode/issues/285762) | Sticky scroll showing in git diff editor | 1 | visual | 3/6 Plausible | 3 | — | `npm run implement -- --issue 285762` |
| 188 | [#291679](https://github.com/microsoft/vscode/issues/291679) | Cursor in the middle of terminal path | 1 | papercut | 3/6 Plausible | 3 | — | `npm run implement -- --issue 291679` |
| 190 | [#306387](https://github.com/microsoft/vscode/issues/306387) | Weird gap before first prompt in the terminal. | 1 | visual | 3/6 Plausible | 3 | — | `npm run implement -- --issue 306387` |
| 191 | [#315281](https://github.com/microsoft/vscode/issues/315281) | Extreme input lag and terminal stuttering on i9 processor during C programming. | 1 | perf | 3/6 Plausible | 3 | — | — |
| 197 | [#209234](https://github.com/microsoft/vscode/issues/209234) | Terminal in Floating Window Does Not Echo Characters in Real Time When Remotely Connected | 0 | correctness | 3/6 Plausible | 3 | — | `npm run implement -- --issue 209234` |
| 203 | [#244867](https://github.com/microsoft/vscode/issues/244867) | Exception when running multiple terminal commands | 0 | correctness | 3/6 Plausible | 3 | — | `npm run implement -- --issue 244867` |
| 204 | [#271975](https://github.com/microsoft/vscode/issues/271975) | Terminal is still showing `node` is process title, despite being finished | 0 | visual | 5/6 Source-confirmed | 3 | yes | `npm run implement -- --issue 271975` |
| 206 | [#274135](https://github.com/microsoft/vscode/issues/274135) | renaming top terminal UI | 0 | visual | 5/6 Source-confirmed | 3 | yes | `npm run implement -- --issue 274135` |
| 219 | [#321556](https://github.com/microsoft/vscode/issues/321556) | "Relaunch Terminal" and other actions are hidden when notification message is too long | 0 | visual | 5/6 Source-confirmed | 3 | yes | `npm run implement -- --issue 321556` |
| 223 | [#160687](https://github.com/microsoft/vscode/issues/160687) | Console cursor atop shell path + showing password as shell name | 1 | visual | 3/6 Plausible | 2 | — | — |
| 224 | [#239404](https://github.com/microsoft/vscode/issues/239404) | disable terminal tab hover, unusable in portrait mode monitor | 1 | visual | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 239404` |
| 225 | [#281851](https://github.com/microsoft/vscode/issues/281851) | left-click drag selection in tmux fails in New Terminal in New Window | 1 | correctness | 6/6 Confirmed | 2 | — | — |
| 226 | [#287714](https://github.com/microsoft/vscode/issues/287714) | Reverse search in zsh not working when EDITOR env variable is set to vim | 1 | correctness | 2/6 Unverified | 2 | — | — |
| 229 | [#324910](https://github.com/microsoft/vscode/issues/324910) | Terminal title overlaps with action buttons when panel is moved to the side and tabs are collapsed | 1 | visual | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 324910` |
| 238 | [#174486](https://github.com/microsoft/vscode/issues/174486) | VS Code reports incorrect size of the terminal until the terminal is manually resized | 0 | correctness | 4/6 Traced | 2 | — | `npm run implement -- --issue 174486` |
| 246 | [#247549](https://github.com/microsoft/vscode/issues/247549) | Cannot interact with hover produced by Terminal warning | 0 | papercut | 4/6 Traced | 2 | — | `npm run implement -- --issue 247549` |
| 247 | [#258716](https://github.com/microsoft/vscode/issues/258716) | Needed python file open to trigger activation of extension to make completions show up in the terminal | 0 | correctness | 3/6 Plausible | 2 | — | `npm run implement -- --issue 258716` |
| 249 | [#262726](https://github.com/microsoft/vscode/issues/262726) | *First* integrated Git Bash terminal does not load Specified rcfile | 0 | correctness | 3/6 Plausible | 2 | — | `npm run implement -- --issue 262726` |
| 250 | [#272779](https://github.com/microsoft/vscode/issues/272779) | zsh + starship `ctrl+k` doesn't show prompt | 0 | visual | 3/6 Plausible | 2 | — | `npm run implement -- --issue 272779` |
| 252 | [#275380](https://github.com/microsoft/vscode/issues/275380) | Chat Terminal Widget - Some of terminal input is sometimes unexpectedly shown together with terminal output | 0 | visual | 3/6 Plausible | 2 | — | `npm run implement -- --issue 275380` |
| 256 | [#289326](https://github.com/microsoft/vscode/issues/289326) | Facing difficulties in terminal | 0 | visual | 3/6 Plausible | 2 | — | — |
| 257 | [#292325](https://github.com/microsoft/vscode/issues/292325) | Terminal Issues On Codespace | 0 | visual | 3/6 Plausible | 2 | — | `npm run implement -- --issue 292325` |
| 258 | [#297146](https://github.com/microsoft/vscode/issues/297146) | Terminal startup noise not suppressible via Settings UI or `accessibility.verbosity` namespace — impacts screen reader users | 0 | papercut | 4/6 Traced | 2 | — | `npm run implement -- --issue 297146` |
| 264 | [#316945](https://github.com/microsoft/vscode/issues/316945) | powershell tool assumes PowerShell 6+ (pwsh.exe) — fails silently on machines with only Windows PowerShell 5.1 | 0 | correctness | 3/6 Plausible | 2 | — | `npm run implement -- --issue 316945` |
| 266 | [#317672](https://github.com/microsoft/vscode/issues/317672) | Bash terminal skips first character of input | 0 | papercut | 3/6 Plausible | 2 | — | — |
| 269 | [#94081](https://github.com/microsoft/vscode/issues/94081) | Confusion about how EnvironmentVariableCollection handles multiple extensions changing the same variable | 1 | correctness | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 94081` |
| 272 | [#243417](https://github.com/microsoft/vscode/issues/243417) | [Shell Integration Error] bash: vsc_aa_env: bad array subscript | 1 | papercut | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 243417` |
| 273 | [#311326](https://github.com/microsoft/vscode/issues/311326) | codex not reflected in terminal title | 1 | papercut | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 311326` |
| 274 | [#317754](https://github.com/microsoft/vscode/issues/317754) | Terminal cursor/rendering glitch causes cursor to appear before end of prompt/path | 1 | visual | 3/6 Plausible | 1 | — | — |
| 280 | [#208880](https://github.com/microsoft/vscode/issues/208880) | Random crashes when quickly printing many millions of lines in terminal | 0 | crash | 6/6 Confirmed | 1 | — | `npm run implement -- --issue 208880` |
| 281 | [#211387](https://github.com/microsoft/vscode/issues/211387) | Terminal animations break link detection in integrated terminal | 0 | correctness | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 211387` |
| 284 | [#231313](https://github.com/microsoft/vscode/issues/231313) | Custom HISTFILE not being honored | 0 | correctness | 5/6 Source-confirmed | 1 | — | — |
| 293 | [#271284](https://github.com/microsoft/vscode/issues/271284) | VSCode occupies all my folders in PATH environment variable, so I got folder access denied when delete these folder | 0 | papercut | 3/6 Plausible | 1 | — | — |
| 294 | [#275598](https://github.com/microsoft/vscode/issues/275598) | Shell Integration unwanted characters in files | 0 | correctness | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 275598` |
| 296 | [#294007](https://github.com/microsoft/vscode/issues/294007) | Terminal size calculation is not correct | 0 | correctness | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 294007` |
| 309 | [#315998](https://github.com/microsoft/vscode/issues/315998) | Terminal window disappears or appears in fragments | 0 | visual | 3/6 Plausible | 1 | — | — |
| 311 | [#316385](https://github.com/microsoft/vscode/issues/316385) | In the Git Bash terminal, pressing Ctrl+click on a folder does not focus on the correct folder in File Explorer. | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 316 | [#319825](https://github.com/microsoft/vscode/issues/319825) | Terminal detail popup missing vertical scrollbar, bottom content & hidden buttons cannot be clicked | 0 | visual | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 319825` |
| 324 | [#322739](https://github.com/microsoft/vscode/issues/322739) | VS Code Integrated Terminal Python REPL not showing stdout / output disappears | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 325 | [#322796](https://github.com/microsoft/vscode/issues/322796) | Changing from dark -> light with TUI CLI makes text difficult to see | 0 | visual | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 322796` |
| 329 | [#324914](https://github.com/microsoft/vscode/issues/324914) | Terminal cursor is sometimes positioned near the beginning of the prompt instead of at the end | 0 | visual | 3/6 Plausible | 1 | — | — |
| 330 | [#325227](https://github.com/microsoft/vscode/issues/325227) | Fish Shell Tab Completion Not Work | 0 | correctness | 3/6 Plausible | 1 | — | `npm run implement -- --issue 325227` |
| 343 | [#186353](https://github.com/microsoft/vscode/issues/186353) | Lost terminals during double reload | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 186353` |
| 346 | [#209374](https://github.com/microsoft/vscode/issues/209374) | OSC hyperlinks are not restored properly on reconnect | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 209374` |
| 350 | [#236313](https://github.com/microsoft/vscode/issues/236313) | In Terminal view, the 'Next/Previous Match' search function conflicts with the redirection triggered by Ctrl+Left Click. | 0 | papercut | 4/6 Traced | 0 | — | `npm run implement -- --issue 236313` |
| 361 | [#275143](https://github.com/microsoft/vscode/issues/275143) | Border offset error on clicking the pill of terminal command attached | 0 | visual | 4/6 Traced | 0 | yes | `npm run implement -- --issue 275143` |
| 378 | [#304555](https://github.com/microsoft/vscode/issues/304555) | Copilot Chat: child_process ENOPRO when file:// URIs are passed to commands | 0 | correctness | 4/6 Traced | 0 | yes | `npm run implement -- --issue 304555` |
| 410 | [#317557](https://github.com/microsoft/vscode/issues/317557) | Task runner display scrambled | 0 | visual | 3/6 Plausible | 0 | — | — |

## Feature requests

### Shell integration (12)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | [#321763](https://github.com/microsoft/vscode/issues/321763) | tcsh/csh shell integration | 56 | backlog-candidate | 100 | `npm run implement -- --issue 321763` |
| 3 | [#90696](https://github.com/microsoft/vscode/issues/90696) | Support tmux control mode (-CC flag) | 89 | backlog-candidate | 43 | `npm run implement -- --issue 90696` |
| 11 | [#323164](https://github.com/microsoft/vscode/issues/323164) | Make sure Python auto activation work with agent host | 0 | active | 16 | `npm run implement -- --issue 323164` |
| 17 | [#317789](https://github.com/microsoft/vscode/issues/317789) | Improve Agent Host shell integration and command detection parity | 0 | active | 10 | `npm run implement -- --issue 317789` |
| 32 | [#286146](https://github.com/microsoft/vscode/issues/286146) | bug: Native support for fish shell in Copilot Chat: Multiline command handling and terminal stability | 1 | backlog-candidate | 4 | `npm run implement -- --issue 286146` |
| 36 | [#239631](https://github.com/microsoft/vscode/issues/239631) | Add tcshell, xonsh as shell type | 4 | active | 3 | `npm run implement -- --issue 239631` |
| 38 | [#277454](https://github.com/microsoft/vscode/issues/277454) | Wait for shell integration to be ready when opening new terminal via API | 1 | active | 3 | — |
| 44 | [#311045](https://github.com/microsoft/vscode/issues/311045) | Mac, Linux) Look into better way of identifying Codex and other shell types | 1 | backlog-candidate | 2 | `npm run implement -- --issue 311045` |
| 45 | [#311046](https://github.com/microsoft/vscode/issues/311046) | Add more AI CLIs as shell type | 1 | backlog-candidate | 2 | `npm run implement -- --issue 311046` |
| 51 | [#316713](https://github.com/microsoft/vscode/issues/316713) | Shell integration cannot be enabled for executable "/app/bin/host-spawn" and args undefined | 0 | active | 2 | `npm run implement -- --issue 316713` |
| 62 | [#174537](https://github.com/microsoft/vscode/issues/174537) | Support HISTTIMEFORMAT in bash shell integration | 0 | backlog-candidate | 0 | `npm run implement -- --issue 174537` |
| 67 | [#258587](https://github.com/microsoft/vscode/issues/258587) | Terminal Chat Participant should know about shell version | 0 | backlog-candidate | 0 | `npm run implement -- --issue 258587` |

### Environment handling (9)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 2 | [#47816](https://github.com/microsoft/vscode/issues/47816) | Use fresh environment block on new terminals in Windows | 123 | backlog-candidate | 95 | `npm run implement -- --issue 47816` |
| 13 | [#185200](https://github.com/microsoft/vscode/issues/185200) | Allow EnvironmentVariableCollection to unset variables | 14 | backlog-candidate | 10 | `npm run implement -- --issue 185200` |
| 15 | [#299940](https://github.com/microsoft/vscode/issues/299940) | Integrated terminal never reflects updated PATH/env; previous issues closed as not planned / not reproducible | 0 | active | 10 | `npm run implement -- --issue 299940` |
| 21 | [#227467](https://github.com/microsoft/vscode/issues/227467) | API to expose the shell's actual environment to extensions | 4 | backlog-candidate | 8 | `npm run implement -- --issue 227467` |
| 24 | [#325546](https://github.com/microsoft/vscode/issues/325546) | Integrated terminal requires manual restart on every VS Code startup | 1 | active | 6 | `npm run implement -- --issue 325546` |
| 25 | [#192943](https://github.com/microsoft/vscode/issues/192943) | Terminal profile settings not reflected in terminals created using VSCode API | 0 | backlog-candidate | 5 | `npm run implement -- --issue 192943` |
| 52 | [#104154](https://github.com/microsoft/vscode/issues/104154) | Allow blocked environment variables through if they're included explicitly in terminal launch configs | 1 | backlog-candidate | 1 | `npm run implement -- --issue 104154` |
| 61 | [#119984](https://github.com/microsoft/vscode/issues/119984) | EnvironmentVariableCollection in remote vs local terminals | 0 | backlog-candidate | 0 | `npm run implement -- --issue 119984` |
| 81 | [#318381](https://github.com/microsoft/vscode/issues/318381) | Add a setting to not resolve shell configuration and not inherit environment from cli | 0 | active | 0 | `npm run implement -- --issue 318381` |

### Terminal layout (8)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 4 | [#318095](https://github.com/microsoft/vscode/issues/318095) | [feat] Allow Terminal in panel and Secondary Side Bar simultaneously | 17 | active | 42 | `npm run implement -- --issue 318095` |
| 12 | [#318570](https://github.com/microsoft/vscode/issues/318570) | Allow Terminal views in both Secondary Side Bar and bottom Panel simultaneously | 5 | active | 12 | — |
| 40 | [#326096](https://github.com/microsoft/vscode/issues/326096) | [Terminal] Manually restart action | 1 | active | 3 | `npm run implement -- --issue 326096` |
| 60 | [#314002](https://github.com/microsoft/vscode/issues/314002) | Auto-rename integrated terminal based on Claude (or other chat) session name | 0 | active | 1 | — |
| 80 | [#313100](https://github.com/microsoft/vscode/issues/313100) | Provide a configurable way to show or hide external CLI sessions | 0 | backlog-candidate | 0 | `npm run implement -- --issue 313100` |
| 86 | [#324686](https://github.com/microsoft/vscode/issues/324686) | Split terminal | 0 | active | 0 | `npm run implement -- --issue 324686` |
| 89 | [#325352](https://github.com/microsoft/vscode/issues/325352) | `terminalIsOpen` includes hidden extension terminals, making terminal keybindings unreliable | 0 | active | 0 | `npm run implement -- --issue 325352` |
| 93 | [#326808](https://github.com/microsoft/vscode/issues/326808) | [Feature Request] Preserve CLI Tool Sessions (Claude Code, Codex CLI, etc.) Across WSL Reconnection After Sleep/Hibernate | 0 | active | 0 | — |

### Input and interaction (7)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 5 | [#279026](https://github.com/microsoft/vscode/issues/279026) | Add drag-and-drop support for multiple files in the terminal | 20 | backlog-candidate | 40 | `npm run implement -- --issue 279026` |
| 26 | [#286896](https://github.com/microsoft/vscode/issues/286896) | Support win32-input-mode in terminal | 0 | active | 5 | `npm run implement -- --issue 286896` |
| 37 | [#317917](https://github.com/microsoft/vscode/issues/317917) | Add setting to suppress terminal context menu when mouse reporting is active | 2 | backlog-candidate | 3 | `npm run implement -- --issue 317917` |
| 48 | [#168192](https://github.com/microsoft/vscode/issues/168192) | Terminal can essentially become bricked after pressing ctrl+s | 0 | backlog-candidate | 2 | `npm run implement -- --issue 168192` |
| 50 | [#302645](https://github.com/microsoft/vscode/issues/302645) | Add config for linkActivationModifier and prevent link following when any other modifiers are down | 0 | active | 2 | `npm run implement -- --issue 302645` |
| 74 | [#302333](https://github.com/microsoft/vscode/issues/302333) | Let CLI know about IME composition started | 0 | active | 0 | `npm run implement -- --issue 302333` |
| 75 | [#302689](https://github.com/microsoft/vscode/issues/302689) | Restore previous Ctrl Shift C behavior | 0 | active | 0 | `npm run implement -- --issue 302689` |

### Agent orchestration (19)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 7 | [#288327](https://github.com/microsoft/vscode/issues/288327) | Consider auto approving of file writes to /tmp | 14 | active | 37 | `npm run implement -- --issue 288327` |
| 9 | [#315193](https://github.com/microsoft/vscode/issues/315193) | AHP/Copilot attachments enablement | 0 | active | 27 | `npm run implement -- --issue 315193` |
| 14 | [#309414](https://github.com/microsoft/vscode/issues/309414) | File write detected `/dev/null` | 4 | backlog-candidate | 10 | `npm run implement -- --issue 309414` |
| 16 | [#315191](https://github.com/microsoft/vscode/issues/315191) | AHP/Copilot: rich terminal UI integration | 0 | active | 10 | `npm run implement -- --issue 315191` |
| 18 | [#323969](https://github.com/microsoft/vscode/issues/323969) | Track session-reference attachment support across chat session types | 0 | active | 10 | `npm run implement -- --issue 323969` |
| 22 | [#302109](https://github.com/microsoft/vscode/issues/302109) | Sessions: Terminal and command output is not visible when the agent runs commands, showing "The terminal is no longer available" | 0 | active | 8 | `npm run implement -- --issue 302109` |
| 23 | [#323970](https://github.com/microsoft/vscode/issues/323970) | Track full session porting for Continue in Agent Host | 0 | active | 7 | `npm run implement -- --issue 323970` |
| 27 | [#317634](https://github.com/microsoft/vscode/issues/317634) | Experiment where worktree option lead to agents app suggestion | 0 | active | 5 | `npm run implement -- --issue 317634` |
| 28 | [#326766](https://github.com/microsoft/vscode/issues/326766) | Terminal auto-approval parity for agent host + make CLI/SDK the source of truth | 0 | active | 5 | `npm run implement -- --issue 326766` |
| 71 | [#287636](https://github.com/microsoft/vscode/issues/287636) | enable adding running py scripts with "python3 script.py ..." to be allow listed | 0 | active | 0 | `npm run implement -- --issue 287636` |
| 72 | [#288337](https://github.com/microsoft/vscode/issues/288337) | Ctrl/cmd+v should paste image data into copilot CLI | 0 | active | 0 | `npm run implement -- --issue 288337` |
| 73 | [#297622](https://github.com/microsoft/vscode/issues/297622) | Allow agent/chat to access images in the terminal | 0 | active | 0 | `npm run implement -- --issue 297622` |
| 77 | [#309290](https://github.com/microsoft/vscode/issues/309290) | Non-agent host Copilot CLI Async terminals don't resume the session | 0 | backlog-candidate | 0 | `npm run implement -- --issue 309290` |
| 82 | [#322876](https://github.com/microsoft/vscode/issues/322876) | Auto-resume Copilot CLI sessions that are in terminals in editor tabs | 0 | active | 0 | `npm run implement -- --issue 322876` |
| 83 | [#324136](https://github.com/microsoft/vscode/issues/324136) | Agent Host: bring back granular "sticky" terminal auto-approve controls (allow for session / always allow exact command line) | 0 | active | 0 | `npm run implement -- --issue 324136` |
| 84 | [#324350](https://github.com/microsoft/vscode/issues/324350) | Terminal gaps for AI agent orchestration workflows (scriptability, output read-back, session persistence) | 0 | active | 0 | `npm run implement -- --issue 324350` |
| 85 | [#324615](https://github.com/microsoft/vscode/issues/324615) | I should be able to drag and drop sessions into the chat editor | 0 | active | 0 | `npm run implement -- --issue 324615` |
| 87 | [#324824](https://github.com/microsoft/vscode/issues/324824) | Provide way to stop running command in agent host copilot | 0 | active | 0 | `npm run implement -- --issue 324824` |
| 91 | [#325539](https://github.com/microsoft/vscode/issues/325539) | Extend `chat.tools.terminal.autoApprove` to deny tool calls | 0 | active | 0 | `npm run implement -- --issue 325539` |

### Tasks and suggestions (10)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 8 | [#285427](https://github.com/microsoft/vscode/issues/285427) | Reference folder task in multi-root workspace | 22 | backlog-candidate | 27 | `npm run implement -- --issue 285427` |
| 20 | [#249479](https://github.com/microsoft/vscode/issues/249479) | Support multiple LSP based completion provider | 1 | backlog-candidate | 9 | `npm run implement -- --issue 249479` |
| 33 | [#250368](https://github.com/microsoft/vscode/issues/250368) | Smart task suggestion depending on user's project setup | 0 | dormant | 4 | `npm run implement -- --issue 250368` |
| 34 | [#258837](https://github.com/microsoft/vscode/issues/258837) | Snippets not showing up in terminal | 0 | dormant | 4 | `npm run implement -- --issue 258837` |
| 39 | [#324297](https://github.com/microsoft/vscode/issues/324297) | Search-based file-path autocomplete for the terminal | 1 | backlog-candidate | 3 | `npm run implement -- --issue 324297` |
| 41 | [#252001](https://github.com/microsoft/vscode/issues/252001) | Allow tasks to be run via terminal suggest | 0 | backlog-candidate | 3 | `npm run implement -- --issue 252001` |
| 47 | [#158120](https://github.com/microsoft/vscode/issues/158120) | Trivial pollution of workbench.action.terminal.runRecentCommand list | 0 | backlog-candidate | 2 | `npm run implement -- --issue 158120` |
| 53 | [#178994](https://github.com/microsoft/vscode/issues/178994) | `terminal.goToRecentDirectory` is not shell-aware | 1 | backlog-candidate | 1 | `npm run implement -- --issue 178994` |
| 68 | [#258672](https://github.com/microsoft/vscode/issues/258672) | Auto imports don't work in python repl | 0 | dormant | 0 | `npm run implement -- --issue 258672` |
| 88 | [#324989](https://github.com/microsoft/vscode/issues/324989) | Feature Request: Add an interactive Inline Command History Search/Filter UI for Integrated Terminal | 0 | active | 0 | — |

### Links and paths (9)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 29 | [#231446](https://github.com/microsoft/vscode/issues/231446) | Allow terminal links to be opened in a web browser | 4 | backlog-candidate | 4 | `npm run implement -- --issue 231446` |
| 30 | [#96941](https://github.com/microsoft/vscode/issues/96941) | Support /mnt WSL links in windows not using Remote WSL | 2 | backlog-candidate | 4 | — |
| 31 | [#216853](https://github.com/microsoft/vscode/issues/216853) | Copy a link from integrated terminal via context menu | 2 | backlog-candidate | 4 | `npm run implement -- --issue 216853` |
| 35 | [#301517](https://github.com/microsoft/vscode/issues/301517) | Allow opening `file://` URI externaly on Ctrl+Click in the terminal | 0 | active | 4 | — |
| 55 | [#154917](https://github.com/microsoft/vscode/issues/154917) | support reveal in finder when focus terminal | 0 | dormant | 1 | `npm run implement -- --issue 154917` |
| 57 | [#214615](https://github.com/microsoft/vscode/issues/214615) | MSYS/Cygwin paths are not supported as terminal links | 0 | backlog-candidate | 1 | `npm run implement -- --issue 214615` |
| 66 | [#233353](https://github.com/microsoft/vscode/issues/233353) | Git output containing .../ file links should be linkified | 0 | backlog-candidate | 0 | `npm run implement -- --issue 233353` |
| 69 | [#272212](https://github.com/microsoft/vscode/issues/272212) | Support terminal file line number jump for claude code and codex diff code | 0 | backlog-candidate | 0 | `npm run implement -- --issue 272212` |
| 90 | [#325473](https://github.com/microsoft/vscode/issues/325473) | Terminal file links should resolve relative paths using the terminal's current working directory | 0 | active | 0 | — |

### Terminal presentation (14)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 42 | [#267359](https://github.com/microsoft/vscode/issues/267359) | Surface terminal progress sequence results in first class UI | 0 | backlog-candidate | 3 | `npm run implement -- --issue 267359` |
| 43 | [#292550](https://github.com/microsoft/vscode/issues/292550) | Support text blink attribute in terminal | 1 | active | 2 | `npm run implement -- --issue 292550` |
| 49 | [#290919](https://github.com/microsoft/vscode/issues/290919) | Support terminal color scheme reporting | 0 | active | 2 | `npm run implement -- --issue 290919` |
| 54 | [#55718](https://github.com/microsoft/vscode/issues/55718) | API to retrieve a dimensions from a given Terminal instance | 0 | backlog-candidate | 1 | `npm run implement -- --issue 55718` |
| 56 | [#162336](https://github.com/microsoft/vscode/issues/162336) | Terminal hover positioning is unfriendly | 0 | backlog-candidate | 1 | `npm run implement -- --issue 162336` |
| 58 | [#294247](https://github.com/microsoft/vscode/issues/294247) | Support OSC 99 notifications | 0 | active | 1 | `npm run implement -- --issue 294247` |
| 63 | [#198116](https://github.com/microsoft/vscode/issues/198116) | Explore quick fixes and command decoration being attached to the previous command (with help of sticky scroll) | 0 | backlog-candidate | 0 | `npm run implement -- --issue 198116` |
| 64 | [#223356](https://github.com/microsoft/vscode/issues/223356) | Show terminal selection in scroll bar/overview ruler | 0 | backlog-candidate | 0 | `npm run implement -- --issue 223356` |
| 65 | [#231188](https://github.com/microsoft/vscode/issues/231188) | Feature request: Contribution point for context menus in shell integration command decorations | 0 | backlog-candidate | 0 | `npm run implement -- --issue 231188` |
| 70 | [#286194](https://github.com/microsoft/vscode/issues/286194) | Support decimal/floating-point values for terminal.integrated.fontSize | 0 | active | 0 | `npm run implement -- --issue 286194` |
| 76 | [#307697](https://github.com/microsoft/vscode/issues/307697) | Allow customizing the media sound for user confirmation prompts | 0 | backlog-candidate | 0 | `npm run implement -- --issue 307697` |
| 78 | [#309345](https://github.com/microsoft/vscode/issues/309345) | Feature Request: Make "Terminal: Toggle Size to Content Width" persistent | 0 | active | 0 | `npm run implement -- --issue 309345` |
| 79 | [#312565](https://github.com/microsoft/vscode/issues/312565) | Integrated terminal fails to open when Arabic character joiner is registered before xterm.open() | 0 | active | 0 | — |
| 92 | [#326506](https://github.com/microsoft/vscode/issues/326506) | Add "Scroll By Page" choice for terminal pane | 0 | active | 0 | `npm run implement -- --issue 326506` |

### Other (5)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 6 | [#239470](https://github.com/microsoft/vscode/issues/239470) | Kitty terminal support on macOS | 48 | backlog-candidate | 39 | `npm run implement -- --issue 239470` |
| 10 | [#70444](https://github.com/microsoft/vscode/issues/70444) | TerminalOptions.waitOnExit API | 24 | backlog-candidate | 25 | `npm run implement -- --issue 70444` |
| 19 | [#327326](https://github.com/microsoft/vscode/issues/327326) | API: Provide a stable terminal session ID across window reloads | 5 | backlog-candidate | 9 | `npm run implement -- --issue 327326` |
| 46 | [#326151](https://github.com/microsoft/vscode/issues/326151) | Support writing to the local clipboard from Dev Containers and Remote SSH sessions | 1 | active | 2 | `npm run implement -- --issue 326151` |
| 59 | [#304417](https://github.com/microsoft/vscode/issues/304417) | changes made in terminal | 0 | active | 1 | `npm run implement -- --issue 304417` |
