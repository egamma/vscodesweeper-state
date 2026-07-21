# Top issues by theme — meganrogge

Experimental themed view of [the flat ranking](meganrogge.md); themes assigned by the review engine. Rank/score are the lane-wide values. Generated 2026-07-21 08:08 UTC.

## Bugs

### Task execution (58)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | [#187955](https://github.com/microsoft/vscode/issues/187955) | Incorrect $PATH order in task shell | 15 | correctness | 5/6 Source-confirmed | 100 | — | `npm run implement -- --issue 187955` |
| 4 | [#214931](https://github.com/microsoft/vscode/issues/214931) | Quotes around paths with spaces are not honored when running tasks | 9 | correctness | 5/6 Source-confirmed | 46 | yes | `npm run implement -- --issue 214931` |
| 9 | [#160891](https://github.com/microsoft/vscode/issues/160891) | Incorrect Command Variable Resolution in tasks.json if task type is 'process' | 8 | correctness | 5/6 Source-confirmed | 35 | — | `npm run implement -- --issue 160891` |
| 10 | [#169821](https://github.com/microsoft/vscode/issues/169821) | VS Code is still adding `/d /c` to task commands | 10 | correctness | 5/6 Source-confirmed | 31 | — | `npm run implement -- --issue 169821` |
| 11 | [#255503](https://github.com/microsoft/vscode/issues/255503) | Unable to abandon task with ${input} variable type command | 3 | correctness | 5/6 Source-confirmed | 30 | — | `npm run implement -- --issue 255503` |
| 15 | [#239581](https://github.com/microsoft/vscode/issues/239581) | Input variables from user tasks are not working when no folder or workspace is opened | 8 | correctness | 2/6 Unverified | 24 | — | — |
| 17 | [#178577](https://github.com/microsoft/vscode/issues/178577) | terminal.integrated.env.linux.PATH and terminal.integrated.env.osx.PATH settings break tasks | 3 | correctness | 4/6 Traced | 22 | — | `npm run implement -- --issue 178577` |
| 23 | [#93001](https://github.com/microsoft/vscode/issues/93001) | resolving multiple tasks with type npm and same script fails | 4 | correctness | 5/6 Source-confirmed | 18 | yes | `npm run implement -- --issue 93001` |
| 35 | [#176277](https://github.com/microsoft/vscode/issues/176277) | tasks.json npm script does not work with arguments on Mac | 2 | correctness | 5/6 Source-confirmed | 15 | yes | `npm run implement -- --issue 176277` |
| 36 | [#236657](https://github.com/microsoft/vscode/issues/236657) | "command" content interpretation broken in tasks.json, possible arg tokenization problem? | 0 | correctness | 2/6 Unverified | 15 | — | — |
| 50 | [#226471](https://github.com/microsoft/vscode/issues/226471) | Cannot run dynamically-created shell tasks when a workspace folder is not opened | 0 | correctness | 5/6 Source-confirmed | 13 | yes | `npm run implement -- --issue 226471` |
| 51 | [#261630](https://github.com/microsoft/vscode/issues/261630) | `npm.scriptRunner` auto-detection fails in subdirectories; defaults to npm instead of pnpm/yarn/bun | 0 | correctness | 5/6 Source-confirmed | 13 | — | — |
| 61 | [#172865](https://github.com/microsoft/vscode/issues/172865) | npm.packageManager=auto ignores task's cwd | 1 | correctness | 5/6 Source-confirmed | 12 | — | — |
| 65 | [#235142](https://github.com/microsoft/vscode/issues/235142) | Task command hangs and doesn't recognize completion of detached processes | 2 | correctness | 4/6 Traced | 11 | — | `npm run implement -- --issue 235142` |
| 66 | [#225317](https://github.com/microsoft/vscode/issues/225317) | 1.92 broke my exension "The task '<task name>' is already active" | 1 | correctness | 4/6 Traced | 11 | — | `npm run implement -- --issue 225317` |
| 72 | [#176670](https://github.com/microsoft/vscode/issues/176670) | Error message complaining about build task | 4 | papercut | 5/6 Source-confirmed | 10 | yes | `npm run implement -- --issue 176670` |
| 74 | [#170101](https://github.com/microsoft/vscode/issues/170101) | npm.packageManager=auto incorrectly assumes yarn as package manager for running tasks | 1 | correctness | 5/6 Source-confirmed | 10 | — | `npm run implement -- --issue 170101` |
| 84 | [#158976](https://github.com/microsoft/vscode/issues/158976) | VSCode Task or .csproj PostBuild event using the "reg" command does not work | 0 | correctness | 3/6 Plausible | 9 | — | — |
| 93 | [#169381](https://github.com/microsoft/vscode/issues/169381) | Input variables quoted incorrectly | 1 | correctness | 5/6 Source-confirmed | 8 | yes | `npm run implement -- --issue 169381` |
| 102 | [#171943](https://github.com/microsoft/vscode/issues/171943) | Using npm as the preferred package manager. Found multiple lockfiles | 6 | papercut | 4/6 Traced | 7 | — | `npm run implement -- --issue 171943` |
| 103 | [#181302](https://github.com/microsoft/vscode/issues/181302) | Custom task shell executable doesn't work | 1 | correctness | 2/6 Unverified | 7 | — | — |
| 108 | [#248733](https://github.com/microsoft/vscode/issues/248733) | tasks with dependencies do not show prompt to restart/ terminate, do not respect `instanceLimit` | 0 | correctness | 5/6 Source-confirmed | 7 | — | `npm run implement -- --issue 248733` |
| 117 | [#157041](https://github.com/microsoft/vscode/issues/157041) | Programmatically running a task in VS Code Web ignores `dependsOn` tasks | 0 | correctness | 5/6 Source-confirmed | 6 | yes | `npm run implement -- --issue 157041` |
| 119 | [#159465](https://github.com/microsoft/vscode/issues/159465) | VSCode uses yarn to run npm tasks | 0 | correctness | 3/6 Plausible | 6 | — | — |
| 120 | [#187661](https://github.com/microsoft/vscode/issues/187661) | C# Dev Kit: None of the ShellQuoting values work in all cases to run dotnet build command using ShellExecution | 0 | correctness | 4/6 Traced | 6 | — | `npm run implement -- --issue 187661` |
| 121 | [#211851](https://github.com/microsoft/vscode/issues/211851) | Task doesn't execute bash commands in background (with &) | 0 | correctness | 4/6 Traced | 6 | — | — |
| 122 | [#213928](https://github.com/microsoft/vscode/issues/213928) | Terminal fails to launch on Task Rerun with "A native exception occurred during launch (args as a string is not supported on unix.)." | 0 | correctness | 2/6 Unverified | 6 | — | — |
| 127 | [#270585](https://github.com/microsoft/vscode/issues/270585) | Task commands retrieved from a command won't be recognized as absolute | 0 | correctness | 5/6 Source-confirmed | 6 | — | `npm run implement -- --issue 270585` |
| 134 | [#96643](https://github.com/microsoft/vscode/issues/96643) | Tasks (and TaskExecutions) are not === in the onDid(Start\|End)Task callbacks. | 1 | correctness | 2/6 Unverified | 5 | — | — |
| 137 | [#170937](https://github.com/microsoft/vscode/issues/170937) | Support `runOn` with `folderOpen` when adding folder to workspace | 0 | correctness | 5/6 Source-confirmed | 5 | yes | `npm run implement -- --issue 170937` |
| 140 | [#194084](https://github.com/microsoft/vscode/issues/194084) | `task.json` -> `options.env` not working of `${env:VAR}` expansion | 0 | correctness | 5/6 Source-confirmed | 5 | yes | `npm run implement -- --issue 194084` |
| 141 | [#234358](https://github.com/microsoft/vscode/issues/234358) | Task API for `ShellExecutionOptions.env` type does not support `undefined` values | 0 | correctness | 5/6 Source-confirmed | 5 | yes | `npm run implement -- --issue 234358` |
| 156 | [#154146](https://github.com/microsoft/vscode/issues/154146) | The pseudo terminal's name cannot be changed for custom task provider | 0 | correctness | 5/6 Source-confirmed | 4 | — | `npm run implement -- --issue 154146` |
| 157 | [#164791](https://github.com/microsoft/vscode/issues/164791) | Variable substitution in tasks.json doesn't work for custom tasks provided by extension | 0 | correctness | 4/6 Traced | 4 | yes | `npm run implement -- --issue 164791` |
| 158 | [#165256](https://github.com/microsoft/vscode/issues/165256) | tasks: empty arguments are not properly passed to the command | 0 | correctness | 5/6 Source-confirmed | 4 | yes | `npm run implement -- --issue 165256` |
| 161 | [#208350](https://github.com/microsoft/vscode/issues/208350) | Tasks using command variables don't run in split terminals | 0 | correctness | 4/6 Traced | 4 | — | `npm run implement -- --issue 208350` |
| 180 | [#142796](https://github.com/microsoft/vscode/issues/142796) | Task that runs on folderOpen also always opens new terminal | 0 | papercut | 4/6 Traced | 3 | — | `npm run implement -- --issue 142796` |
| 181 | [#157957](https://github.com/microsoft/vscode/issues/157957) | Visual Studio Code launch can't find custom prelaunch task | 0 | papercut | 5/6 Source-confirmed | 3 | — | `npm run implement -- --issue 157957` |
| 193 | [#303807](https://github.com/microsoft/vscode/issues/303807) | In a multi-root workspace, all user tasks are injected into request context multiple times (for each workspace folder) | 0 | papercut | 5/6 Source-confirmed | 3 | yes | `npm run implement -- --issue 303807` |
| 201 | [#173842](https://github.com/microsoft/vscode/issues/173842) | Task with empty command does not terminate | 0 | papercut | 6/6 Confirmed | 2 | — | `npm run implement -- --issue 173842` |
| 202 | [#179952](https://github.com/microsoft/vscode/issues/179952) | RunTask command lists duplicate tasks when a filter is applied | 0 | correctness | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 179952` |
| 224 | [#82623](https://github.com/microsoft/vscode/issues/82623) | "There are task errors" while typing in tasks.json | 0 | papercut | — | 1 | — | `npm run implement -- --issue 82623` |
| 225 | [#91436](https://github.com/microsoft/vscode/issues/91436) | Task instanceLimit doesn't work when depending on long running tasks | 0 | correctness | 2/6 Unverified | 1 | — | `npm run implement -- --issue 91436` |
| 227 | [#159135](https://github.com/microsoft/vscode/issues/159135) | Some global properties in tasks.json don't  take effect | 0 | papercut | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 159135` |
| 234 | [#186018](https://github.com/microsoft/vscode/issues/186018) | TaskProvider not working when Remoting via SSH | 0 | correctness | 3/6 Plausible | 1 | — | `npm run implement -- --issue 186018` |
| 258 | [#316388](https://github.com/microsoft/vscode/issues/316388) | Agents App: `Error: there is no registered task type 'cppbuild'.` | 0 | correctness | 2/6 Unverified | 1 | — | — |
| 266 | [#158764](https://github.com/microsoft/vscode/issues/158764) | Parallel tasks with INPUT selection does not run all tasks. | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 267 | [#158940](https://github.com/microsoft/vscode/issues/158940) | Live preview extension contributed task does not include the "Task" tab description | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 158940` |
| 268 | [#174791](https://github.com/microsoft/vscode/issues/174791) | Tasks interfering despite sequence order | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 174791` |
| 271 | [#187746](https://github.com/microsoft/vscode/issues/187746) | tasks.json: Operating system specific properties can't be combined with the dependsOn property | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 187746` |
| 276 | [#213825](https://github.com/microsoft/vscode/issues/213825) | Run Task command silently does nothing in serverless | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 213825` |
| 281 | [#248759](https://github.com/microsoft/vscode/issues/248759) | Sidebar "Run" Button Fails with command not found: npm on Linux (works on macOS) | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 248759` |
| 283 | [#250457](https://github.com/microsoft/vscode/issues/250457) | Tasks.json hover show broken path | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 250457` |
| 297 | [#298101](https://github.com/microsoft/vscode/issues/298101) | ${workspaceFolderBasename} does not resolve in projectPath | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 307 | [#307773](https://github.com/microsoft/vscode/issues/307773) | `workbench.action.tasks.runTask` or `Terminal` > `Run Task...` > `Configure Task` will force `tasks.json` file to be formatted in `JSON` format will cause all comments in the `tasks: []` to disappear | 0 | papercut | 5/6 Source-confirmed | 0 | — | — |
| 314 | [#314092](https://github.com/microsoft/vscode/issues/314092) | Scripts in package.json not checked for auto approve | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 314092` |
| 324 | [#319246](https://github.com/microsoft/vscode/issues/319246) | Running Tasks badge remains after task termination in Dev Container | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 325 | [#320669](https://github.com/microsoft/vscode/issues/320669) | Tasks cannot run MSIX-packaged pwsh | 0 | correctness | 4/6 Traced | 0 | — | `npm run implement -- --issue 320669` |

### Agent terminal tools (65)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2 | [#301804](https://github.com/microsoft/vscode/issues/301804) | Copilot Agent run_in_terminal fails with ENOPRO: No file system provider found in GitHub Codespaces | 7 | correctness | 2/6 Unverified | 80 | — | — |
| 3 | [#275625](https://github.com/microsoft/vscode/issues/275625) | run_in_terminal tool missed the first char in sending a command into git bash terminal | 9 | correctness | 3/6 Plausible | 54 | — | `npm run implement -- --issue 275625` |
| 5 | [#283328](https://github.com/microsoft/vscode/issues/283328) | No stop button to interrupt agent | 3 | correctness | 6/6 Confirmed | 46 | — | `npm run implement -- --issue 283328` |
| 13 | [#321432](https://github.com/microsoft/vscode/issues/321432) | Agent turn hangs indefinitely when a streaming response stalls (no idle timeout in messagesApi/responsesApi SSE read loop) | 1 | freeze | 6/6 Confirmed | 28 | — | `npm run implement -- --issue 321432` |
| 16 | [#293859](https://github.com/microsoft/vscode/issues/293859) | Agent fails to monitor background terminal state, causing redundant re-deployment | 0 | correctness | 3/6 Plausible | 24 | — | `npm run implement -- --issue 293859` |
| 18 | [#292878](https://github.com/microsoft/vscode/issues/292878) | Not waiting terminal finish and new command cancel the last command | 0 | correctness | 3/6 Plausible | 22 | — | — |
| 20 | [#283507](https://github.com/microsoft/vscode/issues/283507) | run_in_terminal fails with Oh My Zsh RPS1 (right-side prompt) - returns only prompt instead of command output CAUSE FOUND | 1 | correctness | 4/6 Traced | 20 | — | `npm run implement -- --issue 283507` |
| 21 | [#307166](https://github.com/microsoft/vscode/issues/307166) | Copilot cannot read the output of `node -v` | 1 | correctness | 5/6 Source-confirmed | 20 | yes | `npm run implement -- --issue 307166` |
| 24 | [#284159](https://github.com/microsoft/vscode/issues/284159) | Copilot Agent adds Cyrillic 'с' prefix to commands when chatting in Ukrainian/Russian | 1 | correctness | 3/6 Plausible | 18 | — | `npm run implement -- --issue 284159` |
| 25 | [#287648](https://github.com/microsoft/vscode/issues/287648) | opus kills its own terminal requests by trying to wait for them | 1 | correctness | 3/6 Plausible | 18 | — | `npm run implement -- --issue 287648` |
| 30 | [#288104](https://github.com/microsoft/vscode/issues/288104) | @terminal with #terminalLastCommand did not work | 0 | correctness | 3/6 Plausible | 17 | — | — |
| 31 | [#279327](https://github.com/microsoft/vscode/issues/279327) | [Copilot] Agent always uses pwsh but grabs args list from default terminal profile. | 1 | correctness | 2/6 Unverified | 16 | — | — |
| 33 | [#303785](https://github.com/microsoft/vscode/issues/303785) | Terminal tool output shows up in multiple places and is confusing | 0 | visual | 3/6 Plausible | 16 | — | `npm run implement -- --issue 303785` |
| 37 | [#270810](https://github.com/microsoft/vscode/issues/270810) | Terminal tool misuses double quotes in bash (eg. history expansion), especially when running python | 0 | correctness | 5/6 Source-confirmed | 15 | yes | `npm run implement -- --issue 270810` |
| 38 | [#271902](https://github.com/microsoft/vscode/issues/271902) | Investigate SIGINT from PromptInputModel being incorrectly used in chat terminal tool result | 0 | correctness | 2/6 Unverified | 15 | — | — |
| 42 | [#316120](https://github.com/microsoft/vscode/issues/316120) | [CRITICAL - Data Loss] Copilot agent bypasses WSL sandbox and deletes user home directory due to Windows/WSL quoting failure | 1 | data-loss | 3/6 Plausible | 14 | — | `npm run implement -- --issue 316120` |
| 43 | [#259088](https://github.com/microsoft/vscode/issues/259088) | Run in terminal: Confirmation edited command disappears when you scroll it out of view and back in | 0 | correctness | 2/6 Unverified | 14 | — | — |
| 45 | [#271391](https://github.com/microsoft/vscode/issues/271391) | Copilot cannot "see" contents of `Pseudoterminal`s created for `CustomExecution` | 0 | correctness | 4/6 Traced | 14 | — | `npm run implement -- --issue 271391` |
| 47 | [#306490](https://github.com/microsoft/vscode/issues/306490) | bg terminal fails to start in other directory | 0 | correctness | 3/6 Plausible | 14 | — | `npm run implement -- --issue 306490` |
| 54 | [#291445](https://github.com/microsoft/vscode/issues/291445) | Terminal timeout shouldn't count when waiting for user input | 0 | correctness | — | 13 | — | `npm run implement -- --issue 291445` |
| 56 | [#293495](https://github.com/microsoft/vscode/issues/293495) | Missing "continue in background" button | 0 | correctness | 5/6 Source-confirmed | 13 | — | `npm run implement -- --issue 293495` |
| 58 | [#317672](https://github.com/microsoft/vscode/issues/317672) | Bash terminal skips first character of input | 0 | correctness | — | 13 | — | — |
| 70 | [#274803](https://github.com/microsoft/vscode/issues/274803) | 1.106.x - Github Copilot run_in_terminal - fails to capture output when the terminal uses some fancy plugins or PS1 (e.g. zsh and aws plugin) (worked in VS Code 1.103) | 0 | correctness | 3/6 Plausible | 11 | — | `npm run implement -- --issue 274803` |
| 73 | [#286847](https://github.com/microsoft/vscode/issues/286847) | Copilot setting focus to terminal ruins experience when terminal is also in right pane | 3 | papercut | 3/6 Plausible | 10 | — | `npm run implement -- --issue 286847` |
| 81 | [#253271](https://github.com/microsoft/vscode/issues/253271) | Agent mode does not use correct path syntax for git bash on windows | 1 | correctness | 4/6 Traced | 9 | — | `npm run implement -- --issue 253271` |
| 86 | [#290065](https://github.com/microsoft/vscode/issues/290065) | Opening Terminal from an agent confirm-input flow doesn't show all output | 0 | visual | 3/6 Plausible | 9 | — | `npm run implement -- --issue 290065` |
| 88 | [#303496](https://github.com/microsoft/vscode/issues/303496) | Copilot has no information on the terminal shell and will always send bash commands to fish | 0 | correctness | 2/6 Unverified | 9 | — | `npm run implement -- --issue 303496` |
| 94 | [#309502](https://github.com/microsoft/vscode/issues/309502) | RunInTerminalTool` ignores `automationProfile` and incorrectly merges terminal settings on Windows | 1 | correctness | 5/6 Source-confirmed | 8 | yes | `npm run implement -- --issue 309502` |
| 110 | [#287552](https://github.com/microsoft/vscode/issues/287552) | Chat: `chat.tools.terminal.autoApprove` is not resource scoped | 0 | correctness | 5/6 Source-confirmed | 7 | yes | `npm run implement -- --issue 287552` |
| 114 | [#263590](https://github.com/microsoft/vscode/issues/263590) | Run in terminal should prefer winget over install scripts | 1 | papercut | 3/6 Plausible | 6 | — | `npm run implement -- --issue 263590` |
| 116 | [#296037](https://github.com/microsoft/vscode/issues/296037) | Terminal script execution fails due to heredoc/simplified command logic | 1 | correctness | 3/6 Plausible | 6 | — | `npm run implement -- --issue 296037` |
| 125 | [#264727](https://github.com/microsoft/vscode/issues/264727) | Terminal tool call UI doesn't serialize language | 0 | visual | 3/6 Plausible | 6 | — | `npm run implement -- --issue 264727` |
| 130 | [#306165](https://github.com/microsoft/vscode/issues/306165) | Skipping terminal tool call results in model trying to run the terminal tool once again | 0 | papercut | 5/6 Source-confirmed | 6 | — | `npm run implement -- --issue 306165` |
| 131 | [#309796](https://github.com/microsoft/vscode/issues/309796) | Terminal approval UI is missing slashes (on windows) | 0 | visual | 5/6 Source-confirmed | 6 | yes | `npm run implement -- --issue 309796` |
| 132 | [#314069](https://github.com/microsoft/vscode/issues/314069) | Agent got confused about special characters in output | 0 | correctness | 6/6 Confirmed | 6 | — | `npm run implement -- --issue 314069` |
| 133 | [#315694](https://github.com/microsoft/vscode/issues/315694) | bad quoting can cause terminal to hang | 0 | freeze | 6/6 Confirmed | 6 | — | `npm run implement -- --issue 315694` |
| 135 | [#264789](https://github.com/microsoft/vscode/issues/264789) | Agent can't find existing terminal running background watch task | 1 | papercut | 3/6 Plausible | 5 | — | `npm run implement -- --issue 264789` |
| 162 | [#224553](https://github.com/microsoft/vscode/issues/224553) | terminal integration proposal replaces the original input | 0 | correctness | 6/6 Confirmed | 4 | — | `npm run implement -- --issue 224553` |
| 165 | [#275037](https://github.com/microsoft/vscode/issues/275037) | Terminal approval: Windows path in WSL context | 0 | visual | 6/6 Confirmed | 4 | — | `npm run implement -- --issue 275037` |
| 169 | [#286994](https://github.com/microsoft/vscode/issues/286994) | GitHub Copilot mostly pays attention on `zoxide` command and in result gives incorrent answers on `#terminalLastCommand` attachment, regardless of AI provider | 0 | correctness | 5/6 Source-confirmed | 4 | — | `npm run implement -- --issue 286994` |
| 177 | [#249444](https://github.com/microsoft/vscode/issues/249444) | Issue with GitHub Copilot in VS Code when using Git Bash on Windows | 2 | papercut | 6/6 Confirmed | 3 | — | `npm run implement -- --issue 249444` |
| 190 | [#275347](https://github.com/microsoft/vscode/issues/275347) | Chat: Insert into Terminal should not auto trigger Suggestion | 0 | papercut | 5/6 Source-confirmed | 3 | yes | `npm run implement -- --issue 275347` |
| 197 | [#316375](https://github.com/microsoft/vscode/issues/316375) | First copilot command always fails | 0 | correctness | 3/6 Plausible | 3 | — | `npm run implement -- --issue 316375` |
| 205 | [#268777](https://github.com/microsoft/vscode/issues/268777) | Problem: not aware of entering properly into a docker container | 0 | correctness | 3/6 Plausible | 2 | — | `npm run implement -- --issue 268777` |
| 208 | [#301063](https://github.com/microsoft/vscode/issues/301063) | Zephyr - Build Process Hangs on Subsequent Builds After First Successful Run in VSCode | 0 | none | 3/6 Plausible | 2 | — | — |
| 210 | [#314081](https://github.com/microsoft/vscode/issues/314081) | Hitting the stop button between terminal prompts doesn't result in the command getting killed | 0 | correctness | 3/6 Plausible | 2 | — | `npm run implement -- --issue 314081` |
| 213 | [#316981](https://github.com/microsoft/vscode/issues/316981) | run in terminal - Terminal content misses line | 0 | correctness | 6/6 Confirmed | 2 | — | `npm run implement -- --issue 316981` |
| 246 | [#275290](https://github.com/microsoft/vscode/issues/275290) | Agent gets distracted by extra terminal context | 0 | correctness | 6/6 Confirmed | 1 | — | `npm run implement -- --issue 275290` |
| 248 | [#302164](https://github.com/microsoft/vscode/issues/302164) | Invalid tip shown on Claude | 0 | papercut | 3/6 Plausible | 1 | — | `npm run implement -- --issue 302164` |
| 249 | [#304279](https://github.com/microsoft/vscode/issues/304279) | Claude subagent describes commands as `undefined` | 0 | visual | 2/6 Unverified | 1 | — | `npm run implement -- --issue 304279` |
| 250 | [#306544](https://github.com/microsoft/vscode/issues/306544) | Focus Terminal does not fully render sudo password prompt text | 0 | visual | — | 1 | — | `npm run implement -- --issue 306544` |
| 253 | [#310196](https://github.com/microsoft/vscode/issues/310196) | clearing terminal input will remove icons | 0 | visual | 3/6 Plausible | 1 | — | `npm run implement -- --issue 310196` |
| 291 | [#290952](https://github.com/microsoft/vscode/issues/290952) | "tool simplified the command" with preprended space seems unnecessary | 0 | papercut | 2/6 Unverified | 0 | — | `npm run implement -- --issue 290952` |
| 293 | [#295620](https://github.com/microsoft/vscode/issues/295620) | Copilot with Claude models fails to handle backticks with gh | 0 | correctness | — | 0 | — | `npm run implement -- --issue 295620` |
| 295 | [#296026](https://github.com/microsoft/vscode/issues/296026) | Summarisation of terminal output witholds key information from agent | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 296026` |
| 296 | [#296641](https://github.com/microsoft/vscode/issues/296641) | run_in_terminal: timeout description says 'optional' but it's in the required array | 0 | papercut | 2/6 Unverified | 0 | — | `npm run implement -- --issue 296641` |
| 298 | [#300116](https://github.com/microsoft/vscode/issues/300116) | Agent using gh CLI always opens alt buffer | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 300116` |
| 301 | [#304555](https://github.com/microsoft/vscode/issues/304555) | Copilot Chat: child_process ENOPRO when file:// URIs are passed to commands | 0 | none | — | 0 | — | — |
| 305 | [#307642](https://github.com/microsoft/vscode/issues/307642) | VS Code Copilot Fails to access codespaces terminal on liveshare | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 309 | [#310738](https://github.com/microsoft/vscode/issues/310738) | Terminal Session Initialization Race Condition | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 310 | [#312363](https://github.com/microsoft/vscode/issues/312363) | RunInTerminalTool hangs forever when trackIdleOnPrompt is stuck in Executing state | 0 | freeze | 2/6 Unverified | 0 | — | `npm run implement -- --issue 312363` |
| 312 | [#313601](https://github.com/microsoft/vscode/issues/313601) | Flaky: chat.runInTerminal 'non-zero exit code is reported' | 0 | correctness | 6/6 Confirmed | 0 | — | `npm run implement -- --issue 313601` |
| 313 | [#314064](https://github.com/microsoft/vscode/issues/314064) | Got an external terminal from the agent | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 314064` |
| 318 | [#316222](https://github.com/microsoft/vscode/issues/316222) | Run in terminal sync mode returns stale `^C` in Remote-SSH Windows/PowerShell | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 316222` |
| 321 | [#317081](https://github.com/microsoft/vscode/issues/317081) | gh auth login - doesn't show Focus Terminal | 0 | papercut | — | 0 | — | `npm run implement -- --issue 317081` |

### Terminal suggest (26)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 6 | [#282541](https://github.com/microsoft/vscode/issues/282541) | zsh themes that use `RPROMPT` seem to break suggest feature of integrated terminal | 1 | correctness | 5/6 Source-confirmed | 38 | yes | `npm run implement -- --issue 282541` |
| 7 | [#286207](https://github.com/microsoft/vscode/issues/286207) | terminal integrated suggest inserts wrong text when tab is pressed due to latency | 2 | correctness | 4/6 Traced | 37 | — | `npm run implement -- --issue 286207` |
| 26 | [#290109](https://github.com/microsoft/vscode/issues/290109) | Terminal Quick Suggestions popup window overflows with the text editor | 1 | visual | 5/6 Source-confirmed | 18 | — | `npm run implement -- --issue 290109` |
| 32 | [#284877](https://github.com/microsoft/vscode/issues/284877) | Terminal suggest making terminal input laggy | 0 | perf | 6/6 Confirmed | 16 | — | `npm run implement -- --issue 284877` |
| 44 | [#264737](https://github.com/microsoft/vscode/issues/264737) | Terminal suggestions feel slow to appear over remote | 0 | perf | 3/6 Plausible | 14 | — | `npm run implement -- --issue 264737` |
| 52 | [#264741](https://github.com/microsoft/vscode/issues/264741) | Can't get suggestions after clearing the terminal | 0 | correctness | 6/6 Confirmed | 13 | — | `npm run implement -- --issue 264741` |
| 53 | [#267297](https://github.com/microsoft/vscode/issues/267297) | Terminal suggestions dont match when pressing tab | 0 | correctness | 3/6 Plausible | 13 | — | `npm run implement -- --issue 267297` |
| 55 | [#293157](https://github.com/microsoft/vscode/issues/293157) | Terminal suggest widget missing symbol icon color matchings | 0 | visual | 5/6 Source-confirmed | 13 | — | `npm run implement -- --issue 293157` |
| 76 | [#272371](https://github.com/microsoft/vscode/issues/272371) | Terminal completions do not show files within `.venv` | 0 | correctness | 3/6 Plausible | 10 | — | `npm run implement -- --issue 272371` |
| 77 | [#273732](https://github.com/microsoft/vscode/issues/273732) | Terminal suggest hijacks listing files | 0 | correctness | 6/6 Confirmed | 10 | — | `npm run implement -- --issue 273732` |
| 79 | [#277778](https://github.com/microsoft/vscode/issues/277778) | Terminal Intellisense missing completions when using `zsh-autosuggestions` | 0 | correctness | 3/6 Plausible | 10 | — | `npm run implement -- --issue 277778` |
| 80 | [#281631](https://github.com/microsoft/vscode/issues/281631) | Suggestions show up when trying to write path | 0 | correctness | 3/6 Plausible | 10 | — | `npm run implement -- --issue 281631` |
| 109 | [#262314](https://github.com/microsoft/vscode/issues/262314) | Terminal suggest: git branch -D doesn't play nice with `/` char | 0 | correctness | 3/6 Plausible | 7 | — | `npm run implement -- --issue 262314` |
| 115 | [#277288](https://github.com/microsoft/vscode/issues/277288) | Terminal autocomplete menu is partially offscreen when window is narrow | 1 | visual | 5/6 Source-confirmed | 6 | yes | `npm run implement -- --issue 277288` |
| 124 | [#243771](https://github.com/microsoft/vscode/issues/243771) | sometimes when the terminal is wrapped, suggestions aren't provided | 0 | correctness | 5/6 Source-confirmed | 6 | — | `npm run implement -- --issue 243771` |
| 128 | [#275023](https://github.com/microsoft/vscode/issues/275023) | Terminal Completion is not place to fit in the window and not render above the current line | 0 | visual | 2/6 Unverified | 6 | — | `npm run implement -- --issue 275023` |
| 143 | [#280363](https://github.com/microsoft/vscode/issues/280363) | Terminal Intellisense breaks with PowerShell when using Starship | 0 | correctness | 6/6 Confirmed | 5 | yes | `npm run implement -- --issue 280363` |
| 152 | [#298535](https://github.com/microsoft/vscode/issues/298535) | Workaround for `Ctrl+Space` inputting `"` and missing .NET completions in PowerShell 5.1 | 1 | papercut | — | 4 | — | — |
| 179 | [#286124](https://github.com/microsoft/vscode/issues/286124) | Terminal & Windows: Git Bash shows infinite loading when clicking “Show Suggestions” | 1 | correctness | 3/6 Plausible | 3 | — | `npm run implement -- --issue 286124` |
| 187 | [#240139](https://github.com/microsoft/vscode/issues/240139) | Terminal suggest: fig generator completions often complain about the executable not existing | 0 | correctness | 6/6 Confirmed | 3 | — | `npm run implement -- --issue 240139` |
| 188 | [#241858](https://github.com/microsoft/vscode/issues/241858) | CDPATH suggestions do not work well with ZSH auto completion | 0 | correctness | 5/6 Source-confirmed | 3 | — | `npm run implement -- --issue 241858` |
| 206 | [#286068](https://github.com/microsoft/vscode/issues/286068) | Terminal suggest status doesn't respect keybindings customizations | 0 | papercut | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 286068` |
| 245 | [#264750](https://github.com/microsoft/vscode/issues/264750) | Odd text show for `mkdir` terminal suggestion on windows | 0 | visual | 6/6 Confirmed | 1 | — | `npm run implement -- --issue 264750` |
| 260 | [#318402](https://github.com/microsoft/vscode/issues/318402) | Terminal suggest completes incorrectly when text is wrapped | 0 | correctness | 4/6 Traced | 1 | — | `npm run implement -- --issue 318402` |
| 285 | [#264749](https://github.com/microsoft/vscode/issues/264749) | Powershell file suggestions don't automatically when typing | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 264749` |
| 311 | [#312431](https://github.com/microsoft/vscode/issues/312431) | Completion of PowerShell parameters in terminal doesn't work | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 312431` |

### Terminal workbench (27)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 8 | [#320220](https://github.com/microsoft/vscode/issues/320220) | Integrated terminal freezes when pasting plain text copied from LibreOffice on Linux | 1 | freeze | 6/6 Confirmed | 37 | — | `npm run implement -- --issue 320220` |
| 22 | [#316246](https://github.com/microsoft/vscode/issues/316246) | Mouse drag stops working in tmux session when the terminal window is moved to a New Window | 3 | correctness | 5/6 Source-confirmed | 19 | — | `npm run implement -- --issue 316246` |
| 40 | [#267796](https://github.com/microsoft/vscode/issues/267796) | Add horizontal tab bar for terminals in a standalone window | 2 | correctness | 5/6 Source-confirmed | 14 | — | `npm run implement -- --issue 267796` |
| 60 | [#317970](https://github.com/microsoft/vscode/issues/317970) | Long terminal tab title (set via OSC sequence) overflows into the panel action buttons in single-tab mode | 3 | visual | 4/6 Traced | 12 | — | — |
| 62 | [#301378](https://github.com/microsoft/vscode/issues/301378) | Terminal colours wrong from ANSI sequence | 0 | none | — | 12 | — | — |
| 75 | [#186862](https://github.com/microsoft/vscode/issues/186862) | Terminal tabs are re-rendered several times on start up | 0 | perf | 3/6 Plausible | 10 | — | `npm run implement -- --issue 186862` |
| 78 | [#275074](https://github.com/microsoft/vscode/issues/275074) | Terminal tool: horizontal scrollbar visible even when not needed | 0 | visual | 6/6 Confirmed | 10 | — | `npm run implement -- --issue 275074` |
| 97 | [#285428](https://github.com/microsoft/vscode/issues/285428) | Opening new terminals in the editor area seemingly cannot figure out ${fileDirname} | 0 | correctness | 5/6 Source-confirmed | 8 | yes | `npm run implement -- --issue 285428` |
| 98 | [#287059](https://github.com/microsoft/vscode/issues/287059) | Workspace folder name integrated terminal title not preserved on window reload | 0 | correctness | 5/6 Source-confirmed | 8 | yes | `npm run implement -- --issue 287059` |
| 105 | [#186866](https://github.com/microsoft/vscode/issues/186866) | SIngle terminal tabs is re-rendered several times on start up | 0 | perf | 2/6 Unverified | 7 | — | — |
| 123 | [#238073](https://github.com/microsoft/vscode/issues/238073) | terminal.integrated.defaultLocation: editor makes it impossible to open a normal 'pane' terminal as well | 0 | correctness | 5/6 Source-confirmed | 6 | yes | `npm run implement -- --issue 238073` |
| 136 | [#167617](https://github.com/microsoft/vscode/issues/167617) | Terminal quick fixes often don't work on Linux | 0 | correctness | 3/6 Plausible | 5 | — | `npm run implement -- --issue 167617` |
| 139 | [#183268](https://github.com/microsoft/vscode/issues/183268) | Some Mac keyboard shortcuts does not work in the new Terminal Editor after being moved with `workbench.action.moveEditorTo<Side>Group` until the terminal editor has been unfocused and focused again | 0 | correctness | 2/6 Unverified | 5 | — | — |
| 142 | [#234602](https://github.com/microsoft/vscode/issues/234602) | icon is not colored correctly for failing task terminal | 0 | visual | 6/6 Confirmed | 5 | — | `npm run implement -- --issue 234602` |
| 150 | [#192689](https://github.com/microsoft/vscode/issues/192689) | {sequence} in terminal title doesn't result in same title as in other terminals | 2 | correctness | 2/6 Unverified | 4 | — | — |
| 151 | [#182979](https://github.com/microsoft/vscode/issues/182979) | Terminal panel overwrites `terminalEditorActive` context key when a terminal editor is present | 1 | correctness | 2/6 Unverified | 4 | — | — |
| 160 | [#196606](https://github.com/microsoft/vscode/issues/196606) | Terminal quick fix should go away when a command is run | 0 | visual | 5/6 Source-confirmed | 4 | yes | `npm run implement -- --issue 196606` |
| 194 | [#305551](https://github.com/microsoft/vscode/issues/305551) | rerun action icon disappear after use it once time | 0 | papercut | 3/6 Plausible | 3 | — | `npm run implement -- --issue 305551` |
| 195 | [#305990](https://github.com/microsoft/vscode/issues/305990) | Terminal in editor area prevents new tabs from opening in the expected editor group | 0 | papercut | 4/6 Traced | 3 | — | `npm run implement -- --issue 305990` |
| 199 | [#122650](https://github.com/microsoft/vscode/issues/122650) | When touching the button on touch screan, The terminal pannel show new terminal with flashing drop-down menu . | 0 | visual | 3/6 Plausible | 2 | — | — |
| 212 | [#316597](https://github.com/microsoft/vscode/issues/316597) | Terminal name overflows. | 0 | visual | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 316597` |
| 241 | [#232488](https://github.com/microsoft/vscode/issues/232488) | Hovering warning icon in terminal tab is difficult to action | 0 | papercut | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 232488` |
| 254 | [#311557](https://github.com/microsoft/vscode/issues/311557) | [Error] potential listener LEAK — terminal/decorationAddon | 0 | perf | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 311557` |
| 256 | [#314066](https://github.com/microsoft/vscode/issues/314066) | Terminal death recovery doesn't work | 0 | correctness | 6/6 Confirmed | 1 | — | `npm run implement -- --issue 314066` |
| 259 | [#318254](https://github.com/microsoft/vscode/issues/318254) | OSC52 unsupported in `code serve-web` | 0 | correctness | 3/6 Plausible | 1 | — | `npm run implement -- --issue 318254` |
| 330 | [#325452](https://github.com/microsoft/vscode/issues/325452) | Terminal quick fix icon overlaps left side bar | 0 | visual | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 325452` |
| 333 | [#326181](https://github.com/microsoft/vscode/issues/326181) | terminal getting scrolled up | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 326181` |

### Problem matchers (16)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 12 | [#150285](https://github.com/microsoft/vscode/issues/150285) | `$msCompile` problem matcher has issues with wrapped lines | 8 | correctness | 4/6 Traced | 29 | — | `npm run implement -- --issue 150285` |
| 28 | [#295523](https://github.com/microsoft/vscode/issues/295523) | Unresponsive window with problem matcher errors | 0 | freeze | 6/6 Confirmed | 18 | — | `npm run implement -- --issue 295523` |
| 29 | [#194501](https://github.com/microsoft/vscode/issues/194501) | Problem matcher only matches on restored PTY | 1 | correctness | 6/6 Confirmed | 17 | — | `npm run implement -- --issue 194501` |
| 67 | [#149912](https://github.com/microsoft/vscode/issues/149912) | applyTo: closedDocuments and a custom owner caused errors to leak/persist | 0 | correctness | 5/6 Source-confirmed | 11 | yes | `npm run implement -- --issue 149912` |
| 68 | [#240869](https://github.com/microsoft/vscode/issues/240869) | Terminal output wrapping breaks ProblemMatcher matching. | 0 | correctness | 5/6 Source-confirmed | 11 | — | — |
| 82 | [#149673](https://github.com/microsoft/vscode/issues/149673) | The "$tsc-webpack-watch" from "amodio.tsl-problem-matcher" problem matcher does match, but doesn't mark the task as failed | 0 | correctness | 6/6 Confirmed | 9 | — | `npm run implement -- --issue 149673` |
| 83 | [#157096](https://github.com/microsoft/vscode/issues/157096) | problemMatcher with multiple patterns doesn't work | 0 | correctness | 5/6 Source-confirmed | 9 | — | `npm run implement -- --issue 157096` |
| 90 | [#183262](https://github.com/microsoft/vscode/issues/183262) | Multiline problem-matcher with empty line breaks when re-run in same terminal | 4 | correctness | 4/6 Traced | 8 | — | `npm run implement -- --issue 183262` |
| 92 | [#119824](https://github.com/microsoft/vscode/issues/119824) | Problems from main vscode build or extensions build can be shown, not both when a file is closed | 2 | correctness | 4/6 Traced | 8 | — | `npm run implement -- --issue 119824` |
| 229 | [#174008](https://github.com/microsoft/vscode/issues/174008) | Task problemMatcher with fileLocation method set to "search" only seems to work for background task | 0 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 174008` |
| 233 | [#179361](https://github.com/microsoft/vscode/issues/179361) | Background task problem matcher does not show all problems | 0 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 179361` |
| 239 | [#228742](https://github.com/microsoft/vscode/issues/228742) | 'search' option in fileLocation of problemMatcher for Task does not work in Remote Development | 0 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 228742` |
| 265 | [#149137](https://github.com/microsoft/vscode/issues/149137) | Problem matcher network path bug | 0 | correctness | 4/6 Traced | 0 | — | `npm run implement -- --issue 149137` |
| 269 | [#175097](https://github.com/microsoft/vscode/issues/175097) | Task beginsPattern does not work | 0 | correctness | 4/6 Traced | 0 | — | `npm run implement -- --issue 175097` |
| 270 | [#184523](https://github.com/microsoft/vscode/issues/184523) | Problems are not always generated when running tasks | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 332 | [#326083](https://github.com/microsoft/vscode/issues/326083) | Task problem matching inconsistency across task runs? | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 326083` |

### Accessibility (58)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 14 | [#147190](https://github.com/microsoft/vscode/issues/147190) | [Accessibility] Audio Cues doesn't work in web editor | 0 | correctness | 2/6 Unverified | 27 | — | — |
| 27 | [#245146](https://github.com/microsoft/vscode/issues/245146) | Misalignment between VoiceOver focus and Keyboard focus in VS Code | 0 | correctness | 6/6 Confirmed | 18 | — | `npm run implement -- --issue 245146` |
| 39 | [#292277](https://github.com/microsoft/vscode/issues/292277) | Content mismatch between Chat view and Accessible View (Alt+F2) with HTML and special characters:A11y_Visual Studio Code_Editor_Infor and relationship | 0 | correctness | 3/6 Plausible | 15 | — | `npm run implement -- --issue 292277` |
| 41 | [#189784](https://github.com/microsoft/vscode/issues/189784) | [Accessibility] problems.decorations.enabled setting must equally benefit screen reader users | 1 | correctness | 5/6 Source-confirmed | 14 | — | `npm run implement -- --issue 189784` |
| 95 | [#241055](https://github.com/microsoft/vscode/issues/241055) | Accessibility MacOS: Pressing a routing button over a character in editor does not move the cursor | 0 | correctness | 3/6 Plausible | 8 | — | `npm run implement -- --issue 241055` |
| 100 | [#303602](https://github.com/microsoft/vscode/issues/303602) | Duplicated condition in accessibility signal property change detection - lastValueOnLine never checked | 0 | correctness | 5/6 Source-confirmed | 8 | — | `npm run implement -- --issue 303602` |
| 101 | [#304396](https://github.com/microsoft/vscode/issues/304396) | Accessible editor does not announce initial value unless focused | 0 | correctness | 5/6 Source-confirmed | 8 | yes | `npm run implement -- --issue 304396` |
| 106 | [#192706](https://github.com/microsoft/vscode/issues/192706) | Large contents in Editor causes VoiceOver to lag significantly while typing | 0 | perf | 3/6 Plausible | 7 | — | `npm run implement -- --issue 192706` |
| 111 | [#291274](https://github.com/microsoft/vscode/issues/291274) | Screen reader continuously announces terminal timing output when Copilot runs a build-like command in VS Code:A11y_Visuual studio code_Screen reader | 0 | correctness | 5/6 Source-confirmed | 7 | — | `npm run implement -- --issue 291274` |
| 113 | [#305969](https://github.com/microsoft/vscode/issues/305969) | Go to Repeating Prompt with Each Character Typed When Using a Screen Reader | 2 | papercut | 5/6 Source-confirmed | 6 | yes | `npm run implement -- --issue 305969` |
| 149 | [#250060](https://github.com/microsoft/vscode/issues/250060) | Accessibility: Monaco Editor Progress Bar Violates "4.1.2 Name, Role, Value" Requirement | 4 | papercut | 2/6 Unverified | 4 | — | — |
| 153 | [#307703](https://github.com/microsoft/vscode/issues/307703) | Settings view Shift+Tab jumps focus back to editor unexpectedly | 1 | papercut | 3/6 Plausible | 4 | — | `npm run implement -- --issue 307703` |
| 163 | [#237085](https://github.com/microsoft/vscode/issues/237085) | [Accessibility, Mouse]: When navigating with the mouse, the content in the editor is not reported to the screen reader. | 0 | correctness | — | 4 | — | — |
| 164 | [#239362](https://github.com/microsoft/vscode/issues/239362) | [Accessibility] Cannot read multi diff content in Source Control Graph View | 0 | correctness | 5/6 Source-confirmed | 4 | yes | `npm run implement -- --issue 239362` |
| 172 | [#298061](https://github.com/microsoft/vscode/issues/298061) | Go to Line/Column - no line number in edit box | 0 | papercut | 3/6 Plausible | 4 | — | `npm run implement -- --issue 298061` |
| 173 | [#298064](https://github.com/microsoft/vscode/issues/298064) | Edit in accessible view sometimes opens too small | 0 | visual | 3/6 Plausible | 4 | — | `npm run implement -- --issue 298064` |
| 174 | [#314779](https://github.com/microsoft/vscode/issues/314779) | Customizations list: Tab into list does not visibly focus first entry | 0 | papercut | 3/6 Plausible | 4 | — | `npm run implement -- --issue 314779` |
| 175 | [#321134](https://github.com/microsoft/vscode/issues/321134) | Focus moves to static option list items but no visible focus indicator is present:A11y_VisualStudioCode_Improved UI for MCP elicitation_Keyboard | 0 | visual | 5/6 Source-confirmed | 4 | yes | `npm run implement -- --issue 321134` |
| 178 | [#192090](https://github.com/microsoft/vscode/issues/192090) | alt+f2 does not open the terminal accessible view on linux | 1 | papercut | 2/6 Unverified | 3 | — | — |
| 183 | [#196854](https://github.com/microsoft/vscode/issues/196854) | [Accessibility] word-by-word keyboard navigation does not work in Output View | 0 | correctness | 2/6 Unverified | 3 | — | — |
| 186 | [#237087](https://github.com/microsoft/vscode/issues/237087) | [Accessibility, Mouse]: When using the mouse to navigate a menu, the content behind the menu is reported to the screen reader. | 0 | papercut | 3/6 Plausible | 3 | — | `npm run implement -- --issue 237087` |
| 191 | [#280911](https://github.com/microsoft/vscode/issues/280911) | Command Palette closes unexpectedly with VoiceOver enabled on VS Code Web | 0 | correctness | 5/6 Source-confirmed | 3 | yes | `npm run implement -- --issue 280911` |
| 200 | [#145109](https://github.com/microsoft/vscode/issues/145109) | orca talking excessively when triggering problem view. | 0 | papercut | 3/6 Plausible | 2 | — | — |
| 203 | [#181798](https://github.com/microsoft/vscode/issues/181798) | punctuation echo issues under MacOS | 0 | papercut | 3/6 Plausible | 2 | — | `npm run implement -- --issue 181798` |
| 204 | [#198612](https://github.com/microsoft/vscode/issues/198612) | Code cannot be read and edited using a screen reader in Android web version of VS code. | 0 | correctness | 3/6 Plausible | 2 | — | `npm run implement -- --issue 198612` |
| 207 | [#296612](https://github.com/microsoft/vscode/issues/296612) | `editor.action.accessibilityHelpConfigureKeybindings` no longer works from Accessibility Help with Alt+K | 0 | correctness | 3/6 Plausible | 2 | — | `npm run implement -- --issue 296612` |
| 211 | [#316415](https://github.com/microsoft/vscode/issues/316415) | ARIA attributes "aria-label" are not valid for the element <body> with implicit ARIA role "generic" violates WCAG 2.1 SC 4.1.2 Name, Role, Value (Level A) | 0 | papercut | 4/6 Traced | 2 | yes | `npm run implement -- --issue 316415` |
| 218 | [#320381](https://github.com/microsoft/vscode/issues/320381) | Keyboard navigation is blocked between “Resources” expandable control and “Views and more actions” using VO navigation (Ctrl+Option keys):A11y_VS code_VoiceOver | 0 | papercut | 3/6 Plausible | 2 | — | `npm run implement -- --issue 320381` |
| 221 | [#175282](https://github.com/microsoft/vscode/issues/175282) | [Accessibility] Do not use title attribute when labeling buttons | 1 | papercut | 3/6 Plausible | 1 | — | `npm run implement -- --issue 175282` |
| 222 | [#204300](https://github.com/microsoft/vscode/issues/204300) | [Accessibility] Copilot generated commit message is not read aloud | 1 | papercut | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 204300` |
| 223 | [#211684](https://github.com/microsoft/vscode/issues/211684) | Accessibility: "Show All Symbols" command doesn't speak file names and paths | 1 | papercut | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 211684` |
| 232 | [#178674](https://github.com/microsoft/vscode/issues/178674) | narrator and NVDA does not report process manager list item names in Visual Studio Code | 0 | correctness | 2/6 Unverified | 1 | — | — |
| 235 | [#201999](https://github.com/microsoft/vscode/issues/201999) | The extensions list should have the ARIA listbox role; not the list role | 0 | papercut | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 201999` |
| 236 | [#211082](https://github.com/microsoft/vscode/issues/211082) | Accessible view: pressing the "Menu" key breaks all context menus and accessible view | 0 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 211082` |
| 238 | [#228599](https://github.com/microsoft/vscode/issues/228599) | Consider how we might improve navigation to chat response content for screen reader users | 0 | papercut | — | 1 | — | `npm run implement -- --issue 228599` |
| 240 | [#229478](https://github.com/microsoft/vscode/issues/229478) | Screen reader is not announcing control name present in top menu navigation and left navigation on hovering with mouse in mouse tracking on mode:A11y_Visual Studio Code Client_Home screen_ScreenReader | 0 | papercut | 3/6 Plausible | 1 | — | `npm run implement -- --issue 229478` |
| 242 | [#237136](https://github.com/microsoft/vscode/issues/237136) | {Linked:Bug9528439} NVDA/JAWS is not announcing the state expand/collapse for the pick model button: A11y_VS Code_Copilot Chat_Screen Reader | 0 | papercut | 2/6 Unverified | 1 | — | `npm run implement -- --issue 237136` |
| 243 | [#248606](https://github.com/microsoft/vscode/issues/248606) | Screen reader repeats last word twice at end of line and on empty lines with Ctrl+Arrow | 0 | correctness | 4/6 Traced | 1 | — | `npm run implement -- --issue 248606` |
| 251 | [#307696](https://github.com/microsoft/vscode/issues/307696) | User confirmation feedback audio is sometimes not heard in terminal | 0 | papercut | 3/6 Plausible | 1 | — | `npm run implement -- --issue 307696` |
| 252 | [#309620](https://github.com/microsoft/vscode/issues/309620) | Agents: initial session list focus shows no indication | 0 | visual | 2/6 Unverified | 1 | — | `npm run implement -- --issue 309620` |
| 257 | [#314777](https://github.com/microsoft/vscode/issues/314777) | Accessibility: Notification Dialogue with toolbar violates  WCAG 4.1.2 Name , Role, Value  "SC 4.1.2 Name, Role, Value (Level A)" | 0 | papercut | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 314777` |
| 261 | [#321616](https://github.com/microsoft/vscode/issues/321616) | Accessibility: Built-in VSCode webviews fails for Name, Role, Value (Level A) SC 4.1.2 (WCAG 2.2) | 0 | none | 3/6 Plausible | 1 | — | — |
| 263 | [#321656](https://github.com/microsoft/vscode/issues/321656) | Accessibility: Built-in VSCode webviews  fails with WCAG 2.1 SC 2.4.2 Page Titled (Level A) - Missing <title> element in <head> element | 0 | papercut | 4/6 Traced | 1 | yes | `npm run implement -- --issue 321656` |
| 275 | [#210062](https://github.com/microsoft/vscode/issues/210062) | #accessibility in Github Copilot chat: Screenreader announces all copilot's path references and links as URL encoded file paths | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 277 | [#223405](https://github.com/microsoft/vscode/issues/223405) | Only one changed variable gets announced by screen reader | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 223405` |
| 278 | [#227484](https://github.com/microsoft/vscode/issues/227484) | Custom controls need to provide proper textual name, role, and state information | 0 | papercut | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 227484` |
| 279 | [#227508](https://github.com/microsoft/vscode/issues/227508) | Tooltips Missing Name and Role Information | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 227508` |
| 284 | [#256761](https://github.com/microsoft/vscode/issues/256761) | Install button should be first tab stop on extension page | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 256761` |
| 288 | [#284843](https://github.com/microsoft/vscode/issues/284843) | {Linked:Bug9576466}There is no feedback message is provided after clicking on copy button: A11y_VSCode_Usability. | 0 | papercut | 2/6 Unverified | 0 | — | — |
| 306 | [#307704](https://github.com/microsoft/vscode/issues/307704) | Cannot navigate to full list of deprecated extensions via Tab key | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 307704` |
| 308 | [#309621](https://github.com/microsoft/vscode/issues/309621) | Find session flow is really not accessible | 0 | correctness | — | 0 | — | `npm run implement -- --issue 309621` |
| 315 | [#314168](https://github.com/microsoft/vscode/issues/314168) | Agents app modals have unexpected tab behavior in MacOS | 0 | papercut | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 314168` |
| 322 | [#318700](https://github.com/microsoft/vscode/issues/318700) | Focus is lost after interacting with "Auto Update" checkbox using keyboard:A11y_VisualStudioCode_Extensions_Keyboard | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 318700` |
| 323 | [#318719](https://github.com/microsoft/vscode/issues/318719) | The Expand/Collapse control does not respond to a single number voice command:A11y_VisualStudioCode_Usable | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 318719` |
| 326 | [#321143](https://github.com/microsoft/vscode/issues/321143) | Smoke Test Failure: sidebar has no accessibility violations | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 321143` |
| 327 | [#321958](https://github.com/microsoft/vscode/issues/321958) | Accessibility: Child items/dropdown menu items inside a view fails for  WCAG 2.2 , SC 4.1.2 Name, Role, Value (Level A) | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 329 | [#324732](https://github.com/microsoft/vscode/issues/324732) | Menu items in Explore section are missing indexing information for screen reader users:A11y_Visual Studio Code Client_Editor_Screen Reader | 0 | papercut | 4/6 Traced | 0 | yes | `npm run implement -- --issue 324732` |
| 334 | [#326546](https://github.com/microsoft/vscode/issues/326546) | NVDA Stops Reading After Opening a File or Folder from Within VSCode, or Closing the Dialog | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 326546` |

### Terminal profiles (20)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 19 | [#167643](https://github.com/microsoft/vscode/issues/167643) | Setting icon and color in createTerminal API no longer works correctly | 6 | correctness | 6/6 Confirmed | 21 | — | `npm run implement -- --issue 167643` |
| 34 | [#233618](https://github.com/microsoft/vscode/issues/233618) | VSCode trying to update WSL on launch for literally no reason | 10 | papercut | 5/6 Source-confirmed | 15 | yes | `npm run implement -- --issue 233618` |
| 49 | [#190749](https://github.com/microsoft/vscode/issues/190749) | Restored terminals in editor area don't restore the current working directory from the previous session. | 2 | correctness | 5/6 Source-confirmed | 13 | yes | `npm run implement -- --issue 190749` |
| 64 | [#205254](https://github.com/microsoft/vscode/issues/205254) | parentTerminal doesn't always work | 2 | correctness | 5/6 Source-confirmed | 11 | — | `npm run implement -- --issue 205254` |
| 104 | [#230160](https://github.com/microsoft/vscode/issues/230160) | [macOS] Custom terminal not found on first launch | 1 | correctness | 4/6 Traced | 7 | — | `npm run implement -- --issue 230160` |
| 107 | [#195768](https://github.com/microsoft/vscode/issues/195768) | Terminal profile default discovery isn't working as expected | 0 | correctness | 5/6 Source-confirmed | 7 | yes | `npm run implement -- --issue 195768` |
| 168 | [#286974](https://github.com/microsoft/vscode/issues/286974) | Terminal tabs description/title using cwdFolder shows folder incorrectly in WSL | 0 | visual | 5/6 Source-confirmed | 4 | yes | `npm run implement -- --issue 286974` |
| 176 | [#326670](https://github.com/microsoft/vscode/issues/326670) | "getWslProfiles" blocks main thread via synchronous "CreateProcessW" | 0 | perf | 4/6 Traced | 4 | — | `npm run implement -- --issue 326670` |
| 184 | [#214547](https://github.com/microsoft/vscode/issues/214547) | Windows: WSL prompt option only shows in terminal add menu if you add another terminal | 0 | papercut | 4/6 Traced | 3 | yes | `npm run implement -- --issue 214547` |
| 185 | [#224749](https://github.com/microsoft/vscode/issues/224749) | It's not possible to set any Terminal Profile | 0 | papercut | 5/6 Source-confirmed | 3 | yes | `npm run implement -- --issue 224749` |
| 196 | [#306723](https://github.com/microsoft/vscode/issues/306723) | The terminal title for a workspace-scoped task in a multi-root workspace shows a misleading folder suffix | 0 | papercut | 5/6 Source-confirmed | 3 | yes | `npm run implement -- --issue 306723` |
| 216 | [#319200](https://github.com/microsoft/vscode/issues/319200) | Restored terminal in editor area sometimes uses working directory from another workspace | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 228 | [#160336](https://github.com/microsoft/vscode/issues/160336) | Connecting via code-server shows the cwd in the terminal tab incorrectly | 0 | visual | 4/6 Traced | 1 | yes | `npm run implement -- --issue 160336` |
| 244 | [#252464](https://github.com/microsoft/vscode/issues/252464) | UI glitch when terminal is in secondary sidebar and env variables overridden | 0 | visual | 3/6 Plausible | 1 | — | `npm run implement -- --issue 252464` |
| 255 | [#312745](https://github.com/microsoft/vscode/issues/312745) | VSCode ignores "chat.tools.terminal.terminalProfile.windows" setting initially | 0 | none | — | 1 | — | — |
| 264 | [#323202](https://github.com/microsoft/vscode/issues/323202) | terminal.integrated.cwd:${fileDirname} confuses copilot | 0 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 323202` |
| 272 | [#188312](https://github.com/microsoft/vscode/issues/188312) | Terminal tab home CWD is not handled correctly in remote workspaces | 0 | visual | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 188312` |
| 273 | [#191369](https://github.com/microsoft/vscode/issues/191369) | Terminal title on Windows may not change when switched shortly after creating | 0 | papercut | 4/6 Traced | 0 | — | `npm run implement -- --issue 191369` |
| 280 | [#233884](https://github.com/microsoft/vscode/issues/233884) | Vscode doesn't respect the login shell on MacOS | 0 | correctness | 4/6 Traced | 0 | yes | `npm run implement -- --issue 233884` |
| 320 | [#317007](https://github.com/microsoft/vscode/issues/317007) | [Bug] Incomplete Sanitization in terminalProfileQuickpick.ts: Args Without Spaces Bypass All Sanitization in Profile Description | 0 | papercut | 5/6 Source-confirmed | 0 | — | — |

### Editor and debug (16)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 46 | [#291642](https://github.com/microsoft/vscode/issues/291642) | Debug disassembly view infinite scrolling does not work after navigating to second frame | 0 | correctness | 5/6 Source-confirmed | 14 | — | — |
| 48 | [#306948](https://github.com/microsoft/vscode/issues/306948) | Sessions: Unable to edit commit message | 0 | correctness | 2/6 Unverified | 14 | — | `npm run implement -- --issue 306948` |
| 59 | [#175202](https://github.com/microsoft/vscode/issues/175202) | Debug with f5 never starts and caused extraneous extension activation | 3 | correctness | 5/6 Source-confirmed | 12 | — | `npm run implement -- --issue 175202` |
| 63 | [#172099](https://github.com/microsoft/vscode/issues/172099) | Variables `relativeFile` and `relativeFileDirname` use backslashes in WSL when used in keyboard shortcuts | 3 | correctness | 5/6 Source-confirmed | 11 | — | `npm run implement -- --issue 172099` |
| 85 | [#225613](https://github.com/microsoft/vscode/issues/225613) | `cursorTop` and `cursorBottom` (Command+UP/DOWN) occasionally stop working in source editors | 0 | correctness | 6/6 Confirmed | 9 | — | — |
| 91 | [#200259](https://github.com/microsoft/vscode/issues/200259) | Widget navigation steals editor focus | 4 | papercut | 3/6 Plausible | 8 | — | `npm run implement -- --issue 200259` |
| 96 | [#258698](https://github.com/microsoft/vscode/issues/258698) | Did not add a launch.json with debug config. | 0 | correctness | 6/6 Confirmed | 8 | — | `npm run implement -- --issue 258698` |
| 138 | [#171835](https://github.com/microsoft/vscode/issues/171835) | Integrated console seems lead to a long delay when executing C/C++ code | 0 | perf | 3/6 Plausible | 5 | — | — |
| 159 | [#169166](https://github.com/microsoft/vscode/issues/169166) | Multi-Process Debugger isn't working on VSC 1.74 | 0 | correctness | 5/6 Source-confirmed | 4 | — | `npm run implement -- --issue 169166` |
| 198 | [#204391](https://github.com/microsoft/vscode/issues/204391) | Debug Console filter with Go is difficult to use and inaccurate | 2 | papercut | 3/6 Plausible | 2 | — | — |
| 219 | [#322732](https://github.com/microsoft/vscode/issues/322732) | Cannot copy selected log fragment from Debug Console on macOS | 0 | papercut | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 322732` |
| 226 | [#156720](https://github.com/microsoft/vscode/issues/156720) | Wrong Path of Files Listed Under "Problems" Tab | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 289 | [#287781](https://github.com/microsoft/vscode/issues/287781) | Investigate why SI warning shows when rich is enabled | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 287781` |
| 290 | [#288635](https://github.com/microsoft/vscode/issues/288635) | Investigate sed flexible delimiters | 0 | correctness | — | 0 | — | `npm run implement -- --issue 288635` |
| 302 | [#305733](https://github.com/microsoft/vscode/issues/305733) | VS Code hangs when running recursive grep with ERE pattern in integrated terminal on macOS | 0 | freeze | 3/6 Plausible | 0 | — | — |
| 337 | [#326761](https://github.com/microsoft/vscode/issues/326761) | Key to copy text from Debug Console different from Termal | 0 | none | — | 0 | — | — |

### Chat interaction (30)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 57 | [#301249](https://github.com/microsoft/vscode/issues/301249) | Chat questions don't scroll | 0 | visual | 6/6 Confirmed | 13 | — | `npm run implement -- --issue 301249` |
| 71 | [#294584](https://github.com/microsoft/vscode/issues/294584) | Agent "AskQuestion" user defined option not selectable | 0 | correctness | 2/6 Unverified | 11 | — | — |
| 89 | [#303918](https://github.com/microsoft/vscode/issues/303918) | Speech to text unexpectedly undoes user edits in chat sidebar | 0 | correctness | 5/6 Source-confirmed | 9 | — | `npm run implement -- --issue 303918` |
| 99 | [#297735](https://github.com/microsoft/vscode/issues/297735) | Terminal inline chat model picker is not vertically centered | 0 | visual | — | 8 | — | `npm run implement -- --issue 297735` |
| 144 | [#280819](https://github.com/microsoft/vscode/issues/280819) | No vertical scrollbar for longer terminal outputs in panel chat | 0 | papercut | 5/6 Source-confirmed | 5 | — | `npm run implement -- --issue 280819` |
| 147 | [#308046](https://github.com/microsoft/vscode/issues/308046) | Async terminal shows "@terminal /explain" header | 0 | visual | 3/6 Plausible | 5 | — | `npm run implement -- --issue 308046` |
| 148 | [#308918](https://github.com/microsoft/vscode/issues/308918) | "retry" on async terminal steering message causes it to rerender incorrectly | 0 | visual | 3/6 Plausible | 5 | — | `npm run implement -- --issue 308918` |
| 166 | [#275076](https://github.com/microsoft/vscode/issues/275076) | Terminal: voice chat and ghost text collide | 0 | visual | 3/6 Plausible | 4 | — | `npm run implement -- --issue 275076` |
| 167 | [#280735](https://github.com/microsoft/vscode/issues/280735) | [inline chat] terminal preview clipped when paired with error "Sorry, no response was returned!" | 0 | visual | 3/6 Plausible | 4 | — | `npm run implement -- --issue 280735` |
| 170 | [#291008](https://github.com/microsoft/vscode/issues/291008) | Chat terminal: cannot copy output from expanded output window via ctrl + c or right click | 0 | papercut | 5/6 Source-confirmed | 4 | — | `npm run implement -- --issue 291008` |
| 171 | [#297277](https://github.com/microsoft/vscode/issues/297277) | Model name trimmed in terminal inline chat despite lots of horizontal space | 0 | visual | 5/6 Source-confirmed | 4 | — | `npm run implement -- --issue 297277` |
| 189 | [#256050](https://github.com/microsoft/vscode/issues/256050) | Add close button to terminal inline chat | 0 | papercut | 3/6 Plausible | 3 | — | `npm run implement -- --issue 256050` |
| 192 | [#295116](https://github.com/microsoft/vscode/issues/295116) | Inline terminal sometimes does not take full available width | 0 | visual | 3/6 Plausible | 3 | — | — |
| 209 | [#309480](https://github.com/microsoft/vscode/issues/309480) | Chat in editor hides ask_questions interface when tab is hidden | 0 | correctness | 4/6 Traced | 2 | — | `npm run implement -- --issue 309480` |
| 217 | [#319413](https://github.com/microsoft/vscode/issues/319413) | chat reacts when terminal task is still going | 0 | papercut | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 319413` |
| 220 | [#326034](https://github.com/microsoft/vscode/issues/326034) | Voice mode: manually typed text is dropped when turning on voice mode in a new chat | 0 | correctness | 6/6 Confirmed | 2 | — | `npm run implement -- --issue 326034` |
| 262 | [#321632](https://github.com/microsoft/vscode/issues/321632) | Chat: system notification XML tags rendered raw in conversation | 0 | visual | 2/6 Unverified | 1 | — | `npm run implement -- --issue 321632` |
| 282 | [#250402](https://github.com/microsoft/vscode/issues/250402) | Chat continues progress in background when sending empty message. | 0 | papercut | 2/6 Unverified | 0 | — | — |
| 287 | [#269609](https://github.com/microsoft/vscode/issues/269609) | Terminal dictation while typing overlaps text | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 269609` |
| 294 | [#295960](https://github.com/microsoft/vscode/issues/295960) | The scroll bar and active item indicator are rendered on top of the terminal inline chat suggest | 0 | visual | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 295960` |
| 299 | [#302310](https://github.com/microsoft/vscode/issues/302310) | Duplicate terminal command message | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 302310` |
| 300 | [#304137](https://github.com/microsoft/vscode/issues/304137) | Active vs inactive selection in ask_questions | 0 | visual | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 304137` |
| 303 | [#306043](https://github.com/microsoft/vscode/issues/306043) | Bad styling for "The command opened the alternate buffer" | 0 | visual | 4/6 Traced | 0 | — | `npm run implement -- --issue 306043` |
| 304 | [#307292](https://github.com/microsoft/vscode/issues/307292) | Terminal confirmation disclaimer renders as KaTeX math when path contains `$` | 0 | visual | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 307292` |
| 316 | [#314204](https://github.com/microsoft/vscode/issues/314204) | Extra height when terminal prompts for input | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 314204` |
| 317 | [#314212](https://github.com/microsoft/vscode/issues/314212) | Agent unable to read large truncated output | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 314212` |
| 328 | [#322164](https://github.com/microsoft/vscode/issues/322164) | special paste hotkey conflict within chat input | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 322164` |
| 331 | [#325709](https://github.com/microsoft/vscode/issues/325709) | Can't select text in questions widget's question | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 325709` |
| 335 | [#326572](https://github.com/microsoft/vscode/issues/326572) | VS Code Speech cannot stop playback for long GitHub Copilot Chat responses | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 326572` |
| 336 | [#326705](https://github.com/microsoft/vscode/issues/326705) | "On-device speech-to-text model failed to load: Load model from ... failed:Protobuf parsing failed." (linux) | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 326705` |

### Other (21)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 69 | [#244491](https://github.com/microsoft/vscode/issues/244491) | Terminal QuickFix Provider and Command with arguments fail. | 0 | correctness | 5/6 Source-confirmed | 11 | yes | `npm run implement -- --issue 244491` |
| 87 | [#291011](https://github.com/microsoft/vscode/issues/291011) | Chat terminal: some command doesn't have expand/collapse button | 0 | visual | 3/6 Plausible | 9 | — | `npm run implement -- --issue 291011` |
| 112 | [#293219](https://github.com/microsoft/vscode/issues/293219) | Intellisense suggestion on command line, when accepted, just gets appended to command instead of replacing the snippet that prompted it | 0 | correctness | 3/6 Plausible | 7 | — | — |
| 118 | [#158615](https://github.com/microsoft/vscode/issues/158615) | "Run VS Code outside the Developer Command Prompt" instructions fail if opened file's basename and/or dirname contains space characters | 0 | correctness | 4/6 Traced | 6 | yes | `npm run implement -- --issue 158615` |
| 126 | [#266487](https://github.com/microsoft/vscode/issues/266487) | Running task terminal left open after extension host reload | 0 | correctness | 4/6 Traced | 6 | — | `npm run implement -- --issue 266487` |
| 129 | [#301424](https://github.com/microsoft/vscode/issues/301424) | Sessions: seeing terminal error popping up when working with multiple sessions on `vscode` | 0 | correctness | 3/6 Plausible | 6 | — | `npm run implement -- --issue 301424` |
| 145 | [#285700](https://github.com/microsoft/vscode/issues/285700) | Completed terminal commands in bg sessions have odd padding | 0 | visual | 3/6 Plausible | 5 | — | `npm run implement -- --issue 285700` |
| 146 | [#298203](https://github.com/microsoft/vscode/issues/298203) | "before all" hook in "Terminal" smoke test flaky | 0 | papercut | 3/6 Plausible | 5 | — | `npm run implement -- --issue 298203` |
| 154 | [#312970](https://github.com/microsoft/vscode/issues/312970) | terminal progress display overflow | 1 | visual | 5/6 Source-confirmed | 4 | — | `npm run implement -- --issue 312970` |
| 155 | [#314197](https://github.com/microsoft/vscode/issues/314197) | Terminal sometimes does not show output preview | 1 | visual | 3/6 Plausible | 4 | — | `npm run implement -- --issue 314197` |
| 182 | [#165292](https://github.com/microsoft/vscode/issues/165292) | Incorrect errors shown when launching in remote container (Codespaces) | 0 | correctness | 3/6 Plausible | 3 | — | `npm run implement -- --issue 165292` |
| 214 | [#316996](https://github.com/microsoft/vscode/issues/316996) | [Bug] Incomplete Sanitization in conversationFeature.ts: Double-Escaping Bug Allows Shell Argument Injection in Git Commit Message | 0 | correctness | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 316996` |
| 215 | [#318223](https://github.com/microsoft/vscode/issues/318223) | [Error] unhandlederror-Cannot register two commands with the same id: workbench.action.chat.openNewChatSessi... | 0 | correctness | 2/6 Unverified | 2 | — | — |
| 230 | [#176684](https://github.com/microsoft/vscode/issues/176684) | Terminal quick fix for creating PR results in branch name with extra padding | 0 | papercut | 2/6 Unverified | 1 | — | — |
| 231 | [#177550](https://github.com/microsoft/vscode/issues/177550) | npm scripts do not run in integrated terminal when it has init script for cmd and powershell | 0 | none | — | 1 | — | — |
| 237 | [#221609](https://github.com/microsoft/vscode/issues/221609) | Inline terminal chat is too small when response comes in | 0 | visual | 6/6 Confirmed | 1 | — | `npm run implement -- --issue 221609` |
| 247 | [#299380](https://github.com/microsoft/vscode/issues/299380) | Unable to space / backspace in Factory - Droid terminal | 0 | correctness | 2/6 Unverified | 1 | — | — |
| 274 | [#193268](https://github.com/microsoft/vscode/issues/193268) | Tasks should add a new line before the VS Code format message if it's not at the start of a line | 0 | visual | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 193268` |
| 286 | [#267221](https://github.com/microsoft/vscode/issues/267221) | cd prefix simplification isn't handling absolute paths | 0 | papercut | 4/6 Traced | 0 | yes | `npm run implement -- --issue 267221` |
| 292 | [#295159](https://github.com/microsoft/vscode/issues/295159) | Splitting a terminal window will open the terminal in the main workbench window, not the terminal window | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 295159` |
| 319 | [#316995](https://github.com/microsoft/vscode/issues/316995) | [Bug] Improper Encoding in Copilot Git Commit Message Sanitizer — Double-Escaping Allows Shell Argument Injection | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 316995` |

## Feature requests

### Keyboard navigation (6)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | [#93772](https://github.com/microsoft/vscode/issues/93772) | Provide a "focus-follow-mouse" setting | 345 | backlog-candidate | 100 | `npm run implement -- --issue 93772` |
| 18 | [#224921](https://github.com/microsoft/vscode/issues/224921) | Vimium or Vim easymotion like keyboard navigation for the whole UI | 35 | backlog-candidate | 8 | `npm run implement -- --issue 224921` |
| 94 | [#292578](https://github.com/microsoft/vscode/issues/292578) | Experimental: Double-Press Keybindings (single vs double-tap) (opt-in) | 1 | backlog-candidate | 1 | `npm run implement -- --issue 292578` |
| 155 | [#159174](https://github.com/microsoft/vscode/issues/159174) | Find Dialogue | 0 | backlog-candidate | 0 | `npm run implement -- --issue 159174` |
| 169 | [#226716](https://github.com/microsoft/vscode/issues/226716) | The find widget should be more like the find widget in the terminal | 0 | dormant | 0 | `npm run implement -- --issue 226716` |
| 170 | [#227009](https://github.com/microsoft/vscode/issues/227009) | Support reverse search in tree find | 0 | dormant | 0 | `npm run implement -- --issue 227009` |

### Task configuration (30)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 2 | [#36769](https://github.com/microsoft/vscode/issues/36769) | Support envfile for tasks.json | 154 | backlog-candidate | 32 | `npm run implement -- --issue 36769` |
| 5 | [#309447](https://github.com/microsoft/vscode/issues/309447) | Feature Request: Allow `task.allowAutomaticTasks` to be set at the workspace level | 31 | backlog-candidate | 17 | `npm run implement -- --issue 309447` |
| 11 | [#251006](https://github.com/microsoft/vscode/issues/251006) | Feature Request:  tasks get inputs from nodejs or shell | 28 | backlog-candidate | 11 | `npm run implement -- --issue 251006` |
| 14 | [#28235](https://github.com/microsoft/vscode/issues/28235) | Provide Task Runner viewlet | 37 | dormant | 9 | `npm run implement -- --issue 28235` |
| 15 | [#70283](https://github.com/microsoft/vscode/issues/70283) | errors in dependsOn background tasks do not prevent subsequent tasks from executing | 35 | dormant | 9 | `npm run implement -- --issue 70283` |
| 16 | [#119868](https://github.com/microsoft/vscode/issues/119868) | Npm Scripts view not available if package.json located only in nested folder | 32 | backlog-candidate | 9 | `npm run implement -- --issue 119868` |
| 21 | [#285427](https://github.com/microsoft/vscode/issues/285427) | Reference folder task in multi-root workspace | 22 | backlog-candidate | 8 | `npm run implement -- --issue 285427` |
| 24 | [#99276](https://github.com/microsoft/vscode/issues/99276) | Tasks: Pick folder for user tasks in multi-root-workspaces | 30 | dormant | 7 | `npm run implement -- --issue 99276` |
| 27 | [#87845](https://github.com/microsoft/vscode/issues/87845) | Improve task debugging by giving more context | 28 | backlog-candidate | 6 | `npm run implement -- --issue 87845` |
| 32 | [#132767](https://github.com/microsoft/vscode/issues/132767) | Support `dependsOn` programmatically in the vscode.Task API | 31 | backlog-candidate | 5 | `npm run implement -- --issue 132767` |
| 33 | [#71461](https://github.com/microsoft/vscode/issues/71461) | Task input parameters from showOpenDialog | 22 | backlog-candidate | 5 | `npm run implement -- --issue 71461` |
| 37 | [#184047](https://github.com/microsoft/vscode/issues/184047) | Display disabled tasks in Run Build Task... menu | 20 | backlog-candidate | 4 | `npm run implement -- --issue 184047` |
| 45 | [#139937](https://github.com/microsoft/vscode/issues/139937) | Add arguments property to npm tasks | 8 | backlog-candidate | 3 | `npm run implement -- --issue 139937` |
| 51 | [#73748](https://github.com/microsoft/vscode/issues/73748) | Be able disable task detection from tasks.json or override tasks execution | 12 | dormant | 2 | `npm run implement -- --issue 73748` |
| 54 | [#309661](https://github.com/microsoft/vscode/issues/309661) | YAML support for VSCode tasks | 9 | active | 2 | — |
| 55 | [#70118](https://github.com/microsoft/vscode/issues/70118) | default run task | 8 | dormant | 2 | `npm run implement -- --issue 70118` |
| 72 | [#68397](https://github.com/microsoft/vscode/issues/68397) | More flexible input variables: Multiple values & labels | 8 | backlog-candidate | 1 | `npm run implement -- --issue 68397` |
| 76 | [#299227](https://github.com/microsoft/vscode/issues/299227) | Make npm scripts panel order consider directory depth | 3 | active | 1 | `npm run implement -- --issue 299227` |
| 78 | [#68767](https://github.com/microsoft/vscode/issues/68767) | Restart task fails if task already completed | 2 | dormant | 1 | `npm run implement -- --issue 68767` |
| 100 | [#40515](https://github.com/microsoft/vscode/issues/40515) | Tasks with target = TaskScope.Global as the scope do not show up in task picker UI | 0 | dormant | 1 | `npm run implement -- --issue 40515` |
| 103 | [#174579](https://github.com/microsoft/vscode/issues/174579) | Background Task With No Output Never Completes | 0 | dormant | 1 | `npm run implement -- --issue 174579` |
| 117 | [#246159](https://github.com/microsoft/vscode/issues/246159) | Unify variable substitution features in tasks, mcp, and debug | 0 | backlog-candidate | 1 | `npm run implement -- --issue 246159` |
| 140 | [#306748](https://github.com/microsoft/vscode/issues/306748) | Feature Request: Prompt inputs for all dependent tasks at launch | 0 | active | 1 | `npm run implement -- --issue 306748` |
| 143 | [#92978](https://github.com/microsoft/vscode/issues/92978) | Report task execution result in onDidEndTask | 1 | backlog-candidate | 0 | `npm run implement -- --issue 92978` |
| 148 | [#83021](https://github.com/microsoft/vscode/issues/83021) | OS specific properties in Tasks.json to overwrite build shell doen't work | 0 | dormant | 0 | `npm run implement -- --issue 83021` |
| 149 | [#93149](https://github.com/microsoft/vscode/issues/93149) | Make extension defined task types work in code-workspace files | 0 | backlog-candidate | 0 | `npm run implement -- --issue 93149` |
| 151 | [#144246](https://github.com/microsoft/vscode/issues/144246) | Indicate if Task Exited for both dependency tasks | 0 | backlog-candidate | 0 | `npm run implement -- --issue 144246` |
| 178 | [#260659](https://github.com/microsoft/vscode/issues/260659) | Only provide task output from `beginsPattern` when possible | 0 | dormant | 0 | `npm run implement -- --issue 260659` |
| 179 | [#264387](https://github.com/microsoft/vscode/issues/264387) | Always runs 'compile' task in vscode-copilot-chat repo when other build tasks are running | 0 | dormant | 0 | `npm run implement -- --issue 264387` |
| 184 | [#276044](https://github.com/microsoft/vscode/issues/276044) | Tasks misses basic editor support | 0 | dormant | 0 | `npm run implement -- --issue 276044` |

### Terminal profiles (24)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 3 | [#252647](https://github.com/microsoft/vscode/issues/252647) | Integrated terminal tabs on the top or bottom | 44 | backlog-candidate | 26 | `npm run implement -- --issue 252647` |
| 13 | [#266038](https://github.com/microsoft/vscode/issues/266038) | requesting terminal icon and terminal color control via launch.json | 23 | backlog-candidate | 10 | `npm run implement -- --issue 266038` |
| 20 | [#140261](https://github.com/microsoft/vscode/issues/140261) | terminal.integrated.defaultProfile and terminal.integrated.automationProfile behaves differently | 28 | backlog-candidate | 8 | `npm run implement -- --issue 140261` |
| 23 | [#323231](https://github.com/microsoft/vscode/issues/323231) | Let extensions change a terminal tab's icon and color after it is created | 9 | backlog-candidate | 8 | `npm run implement -- --issue 323231` |
| 25 | [#237004](https://github.com/microsoft/vscode/issues/237004) | terminal title supports branch variable | 20 | backlog-candidate | 7 | `npm run implement -- --issue 237004` |
| 28 | [#165040](https://github.com/microsoft/vscode/issues/165040) | Set profile to have custom number of terminals at the same time by default | 24 | backlog-candidate | 6 | `npm run implement -- --issue 165040` |
| 34 | [#150938](https://github.com/microsoft/vscode/issues/150938) | Add nvm support | 18 | backlog-candidate | 5 | `npm run implement -- --issue 150938` |
| 59 | [#151284](https://github.com/microsoft/vscode/issues/151284) | Dragging terminals tabs should group and ungroup them | 4 | active | 2 | `npm run implement -- --issue 151284` |
| 64 | [#251105](https://github.com/microsoft/vscode/issues/251105) | Select Default Profile (terminal) doesn't work for projects with terminal specified | 1 | active | 2 | `npm run implement -- --issue 251105` |
| 73 | [#183354](https://github.com/microsoft/vscode/issues/183354) | Support `when` clause for `terminal.profiles` contribution point | 5 | backlog-candidate | 1 | `npm run implement -- --issue 183354` |
| 81 | [#187853](https://github.com/microsoft/vscode/issues/187853) | Truncate long terminal command lines by default | 2 | backlog-candidate | 1 | `npm run implement -- --issue 187853` |
| 82 | [#292816](https://github.com/microsoft/vscode/issues/292816) | integrated Terminal on vscode that supports kitty protocol so I can use ctrl+enter shortcut on kiro cli without sending prompt | 2 | active | 1 | — |
| 84 | [#317917](https://github.com/microsoft/vscode/issues/317917) | Add setting to suppress terminal context menu when mouse reporting is active | 2 | backlog-candidate | 1 | `npm run implement -- --issue 317917` |
| 89 | [#214242](https://github.com/microsoft/vscode/issues/214242) | Add context menu item to relaunch terminals with extra environment info | 1 | backlog-candidate | 1 | `npm run implement -- --issue 214242` |
| 104 | [#194149](https://github.com/microsoft/vscode/issues/194149) | Make terminal tab toolbar configurable | 0 | backlog-candidate | 1 | `npm run implement -- --issue 194149` |
| 107 | [#233354](https://github.com/microsoft/vscode/issues/233354) | Support file icons similar to treeview item icon path in terminal icon path | 0 | backlog-candidate | 1 | `npm run implement -- --issue 233354` |
| 156 | [#173134](https://github.com/microsoft/vscode/issues/173134) | Support command variables in a terminal profile's env property | 0 | backlog-candidate | 0 | `npm run implement -- --issue 173134` |
| 182 | [#274200](https://github.com/microsoft/vscode/issues/274200) | Terminal tab title: Show "~" instead of $HOME | 0 | active | 0 | `npm run implement -- --issue 274200` |
| 188 | [#286741](https://github.com/microsoft/vscode/issues/286741) | Add xonsh shell profile discovery | 0 | active | 0 | `npm run implement -- --issue 286741` |
| 190 | [#290834](https://github.com/microsoft/vscode/issues/290834) | Explore associating recognized shells with an icon that changes | 0 | active | 0 | `npm run implement -- --issue 290834` |
| 203 | [#315252](https://github.com/microsoft/vscode/issues/315252) | Clear Terminal "before that line" | 0 | active | 0 | `npm run implement -- --issue 315252` |
| 206 | [#318853](https://github.com/microsoft/vscode/issues/318853) | I can't see the terminal | 0 | active | 0 | — |
| 208 | [#323243](https://github.com/microsoft/vscode/issues/323243) | Allow extensions to create terminals adjacent to a parent terminal without splitting | 0 | backlog-candidate | 0 | `npm run implement -- --issue 323243` |
| 209 | [#324422](https://github.com/microsoft/vscode/issues/324422) | Pseudoterminal plugins do not have a way to get the users cwd picked in a multi-root workspace | 0 | backlog-candidate | 0 | `npm run implement -- --issue 324422` |

### Debug and launch (9)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 4 | [#27157](https://github.com/microsoft/vscode/issues/27157) | PreLaunchTask: support passing parameters from configuration to preLaunchTask | 94 | backlog-candidate | 24 | `npm run implement -- --issue 27157` |
| 6 | [#6209](https://github.com/microsoft/vscode/issues/6209) | isWatching/background task as preLaunchTask in launch.json | 61 | dormant | 15 | `npm run implement -- --issue 6209` |
| 10 | [#289870](https://github.com/microsoft/vscode/issues/289870) | Support an envFromInput field in launch.json | 23 | backlog-candidate | 12 | `npm run implement -- --issue 289870` |
| 26 | [#47265](https://github.com/microsoft/vscode/issues/47265) | Launch task directly into split terminal | 30 | backlog-candidate | 6 | `npm run implement -- --issue 47265` |
| 31 | [#171837](https://github.com/microsoft/vscode/issues/171837) | Add prelaunch Command as well for launch configuration | 21 | backlog-candidate | 6 | `npm run implement -- --issue 171837` |
| 53 | [#118230](https://github.com/microsoft/vscode/issues/118230) | Add "Copy Value" to the context menu in the Debug Console. | 9 | dormant | 2 | `npm run implement -- --issue 118230` |
| 56 | [#142922](https://github.com/microsoft/vscode/issues/142922) | Debug Console Filter is a bit confusing | 8 | backlog-candidate | 2 | `npm run implement -- --issue 142922` |
| 62 | [#225417](https://github.com/microsoft/vscode/issues/225417) | support finding matches in the debug console's output | 1 | dormant | 2 | `npm run implement -- --issue 225417` |
| 177 | [#256117](https://github.com/microsoft/vscode/issues/256117) | Have the agent add breakpoints | 0 | dormant | 0 | `npm run implement -- --issue 256117` |

### Terminal suggest (29)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 7 | [#285640](https://github.com/microsoft/vscode/issues/285640) | Terminal suggest doesn't get content from the actual terminal session. | 21 | backlog-candidate | 15 | `npm run implement -- --issue 285640` |
| 36 | [#224505](https://github.com/microsoft/vscode/issues/224505) | terminal completion provider extension API | 0 | active | 5 | `npm run implement -- --issue 224505` |
| 39 | [#240240](https://github.com/microsoft/vscode/issues/240240) | Terminal suggest: Support configuring fig specs | 4 | backlog-candidate | 4 | `npm run implement -- --issue 240240` |
| 40 | [#210983](https://github.com/microsoft/vscode/issues/210983) | Terminal suggest snippets | 3 | backlog-candidate | 4 | `npm run implement -- --issue 210983` |
| 63 | [#233232](https://github.com/microsoft/vscode/issues/233232) | Terminal suggest: Contextually aware suggestions after git status | 1 | backlog-candidate | 2 | `npm run implement -- --issue 233232` |
| 65 | [#282578](https://github.com/microsoft/vscode/issues/282578) | Tweak terminal suggest setting to be off by default for certain problematic configs | 1 | backlog-candidate | 2 | `npm run implement -- --issue 282578` |
| 90 | [#237981](https://github.com/microsoft/vscode/issues/237981) | Terminal suggest: Handle paths on git bash | 1 | dormant | 1 | — |
| 91 | [#240241](https://github.com/microsoft/vscode/issues/240241) | Terminal suggest: Support lazy loading of fig specs via an index | 1 | backlog-candidate | 1 | `npm run implement -- --issue 240241` |
| 99 | [#324297](https://github.com/microsoft/vscode/issues/324297) | Search-based file-path autocomplete for the terminal | 1 | backlog-candidate | 1 | `npm run implement -- --issue 324297` |
| 109 | [#234353](https://github.com/microsoft/vscode/issues/234353) | Terminal suggest: Support resolving environment variables in directories | 0 | backlog-candidate | 1 | `npm run implement -- --issue 234353` |
| 110 | [#239019](https://github.com/microsoft/vscode/issues/239019) | arguments suggested for mkdir command seems to be invalid | 0 | backlog-candidate | 1 | `npm run implement -- --issue 239019` |
| 111 | [#239244](https://github.com/microsoft/vscode/issues/239244) | Explore showing history in the suggest widget | 0 | backlog-candidate | 1 | `npm run implement -- --issue 239244` |
| 112 | [#240088](https://github.com/microsoft/vscode/issues/240088) | Terminal suggest: Properly support paths with spaces in them | 0 | backlog-candidate | 1 | `npm run implement -- --issue 240088` |
| 113 | [#240236](https://github.com/microsoft/vscode/issues/240236) | Terminal suggest: Support resolving completion items and pull in pwsh command help | 0 | backlog-candidate | 1 | `npm run implement -- --issue 240236` |
| 114 | [#241975](https://github.com/microsoft/vscode/issues/241975) | Very large set of details in terminal suggestions for `Where-object` | 0 | dormant | 1 | `npm run implement -- --issue 241975` |
| 115 | [#241996](https://github.com/microsoft/vscode/issues/241996) | No terminal suggestions for quoted paths o | 0 | backlog-candidate | 1 | `npm run implement -- --issue 241996` |
| 118 | [#252001](https://github.com/microsoft/vscode/issues/252001) | Allow tasks to be run via terminal suggest | 0 | backlog-candidate | 1 | `npm run implement -- --issue 252001` |
| 122 | [#264752](https://github.com/microsoft/vscode/issues/264752) | Git commit suggestions in terminal aren't very useful without expansion | 0 | backlog-candidate | 1 | `npm run implement -- --issue 264752` |
| 123 | [#273582](https://github.com/microsoft/vscode/issues/273582) | Terminal suggest: Support path completions without the ./ | 0 | backlog-candidate | 1 | `npm run implement -- --issue 273582` |
| 132 | [#284820](https://github.com/microsoft/vscode/issues/284820) | Terminal suggest works with `docker-compose` but not `docker compose` | 0 | backlog-candidate | 1 | `npm run implement -- --issue 284820` |
| 171 | [#239155](https://github.com/microsoft/vscode/issues/239155) | terminal suggest: truncate beginning of long filepaths since they are all the same | 0 | backlog-candidate | 0 | `npm run implement -- --issue 239155` |
| 173 | [#241828](https://github.com/microsoft/vscode/issues/241828) | Accepting a completion should trigger suggest automatically | 0 | backlog-candidate | 0 | `npm run implement -- --issue 241828` |
| 174 | [#241960](https://github.com/microsoft/vscode/issues/241960) | The completions should show up if I use `sudo` | 0 | backlog-candidate | 0 | `npm run implement -- --issue 241960` |
| 175 | [#241968](https://github.com/microsoft/vscode/issues/241968) | `i` should be marked as an alias of `install` | 0 | backlog-candidate | 0 | `npm run implement -- --issue 241968` |
| 176 | [#241976](https://github.com/microsoft/vscode/issues/241976) | Support alternative suggest mode (insert/replace) for terminal suggestions | 0 | backlog-candidate | 0 | `npm run implement -- --issue 241976` |
| 180 | [#264747](https://github.com/microsoft/vscode/issues/264747) | Provide better suggestions for 'man' | 0 | dormant | 0 | `npm run implement -- --issue 264747` |
| 186 | [#283496](https://github.com/microsoft/vscode/issues/283496) | Better granularity/configuration options for the "Terminal integrated Suggest" feature | 0 | active | 0 | `npm run implement -- --issue 283496` |
| 187 | [#286440](https://github.com/microsoft/vscode/issues/286440) | Do not show selectionMode in terminal suggest toolbar when quick suggestions are disabled | 0 | backlog-candidate | 0 | `npm run implement -- --issue 286440` |
| 194 | [#296543](https://github.com/microsoft/vscode/issues/296543) | Smarter command line options UI (contextual options for tools like 'head' and 'python') | 0 | active | 0 | `npm run implement -- --issue 296543` |

### Problem matchers (16)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 8 | [#61497](https://github.com/microsoft/vscode/issues/61497) | Task Manager: provide the ability to reuse custom problem matchers | 58 | backlog-candidate | 13 | `npm run implement -- --issue 61497` |
| 12 | [#205993](https://github.com/microsoft/vscode/issues/205993) | Support hyperlinks in problem matchers of task output | 34 | backlog-candidate | 10 | `npm run implement -- --issue 205993` |
| 17 | [#59337](https://github.com/microsoft/vscode/issues/59337) | Extend tasks API to allow programmatic problem matching | 25 | dormant | 9 | `npm run implement -- --issue 59337` |
| 19 | [#9635](https://github.com/microsoft/vscode/issues/9635) | Problem matchers for error messages that span multiple lines | 28 | backlog-candidate | 8 | `npm run implement -- --issue 9635` |
| 29 | [#77214](https://github.com/microsoft/vscode/issues/77214) | Have a command that clears all problems that are from tasks. | 23 | dormant | 6 | `npm run implement -- --issue 77214` |
| 50 | [#58980](https://github.com/microsoft/vscode/issues/58980) | Relative problem paths don't take `cwd` into account | 12 | backlog-candidate | 2 | `npm run implement -- --issue 58980` |
| 58 | [#164751](https://github.com/microsoft/vscode/issues/164751) | Please document how problem matcher problems are cleared | 6 | backlog-candidate | 2 | `npm run implement -- --issue 164751` |
| 60 | [#61140](https://github.com/microsoft/vscode/issues/61140) | Problem matchers should restore problems on close | 2 | dormant | 2 | `npm run implement -- --issue 61140` |
| 74 | [#55253](https://github.com/microsoft/vscode/issues/55253) | Problem matchers should support creating related diagnostic information | 4 | dormant | 1 | `npm run implement -- --issue 55253` |
| 77 | [#60851](https://github.com/microsoft/vscode/issues/60851) | Open next build error file+line based on regex parsing of build output. | 2 | backlog-candidate | 1 | `npm run implement -- --issue 60851` |
| 79 | [#73186](https://github.com/microsoft/vscode/issues/73186) | Regex pattern to clear all problems of a task owner | 2 | backlog-candidate | 1 | `npm run implement -- --issue 73186` |
| 85 | [#73840](https://github.com/microsoft/vscode/issues/73840) | New revealProblems property in task presentation options is missing from the API | 1 | backlog-candidate | 1 | `npm run implement -- --issue 73840` |
| 142 | [#29562](https://github.com/microsoft/vscode/issues/29562) | Selection of problem matcher is not very intuitive when running a task | 3 | dormant | 0 | `npm run implement -- --issue 29562` |
| 144 | [#151962](https://github.com/microsoft/vscode/issues/151962) | Support SGR ANSI escape sequence in problem matcher messages | 1 | backlog-candidate | 0 | `npm run implement -- --issue 151962` |
| 152 | [#149175](https://github.com/microsoft/vscode/issues/149175) | Problems without column information are always shown as column 1,1 | 0 | dormant | 0 | `npm run implement -- --issue 149175` |
| 166 | [#210560](https://github.com/microsoft/vscode/issues/210560) | msCompile problem matcher does not match note: lines which are important for context | 0 | dormant | 0 | `npm run implement -- --issue 210560` |

### Agent terminal automation (32)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 9 | [#274550](https://github.com/microsoft/vscode/issues/274550) | Revisit terminal tool running background terminals UX | 18 | active | 13 | `npm run implement -- --issue 274550` |
| 38 | [#254429](https://github.com/microsoft/vscode/issues/254429) | Attach a terminal as context | 6 | backlog-candidate | 4 | `npm run implement -- --issue 254429` |
| 41 | [#261975](https://github.com/microsoft/vscode/issues/261975) | Terminals sessions should not be deleted when starting a new conversation | 2 | backlog-candidate | 4 | `npm run implement -- --issue 261975` |
| 42 | [#289657](https://github.com/microsoft/vscode/issues/289657) | GitHub Copilot Agent cannot execute commands in WSL/bash terminals - only PowerShell supported | 2 | active | 4 | `npm run implement -- --issue 289657` |
| 43 | [#290977](https://github.com/microsoft/vscode/issues/290977) | Easier way to clean up leftover terminals from chat sessions | 2 | backlog-candidate | 4 | `npm run implement -- --issue 290977` |
| 46 | [#288566](https://github.com/microsoft/vscode/issues/288566) | Allow agent to push a terminal into the background | 1 | active | 3 | `npm run implement -- --issue 288566` |
| 47 | [#288572](https://github.com/microsoft/vscode/issues/288572) | Explore a setting that launches all runInTerminal terminals in background | 0 | active | 3 | `npm run implement -- --issue 288572` |
| 48 | [#291240](https://github.com/microsoft/vscode/issues/291240) | Chat terminal streaming - rendering suggestion | 0 | active | 3 | `npm run implement -- --issue 291240` |
| 61 | [#162950](https://github.com/microsoft/vscode/issues/162950) | Terminal quick fix API | 2 | backlog-candidate | 2 | `npm run implement -- --issue 162950` |
| 67 | [#257673](https://github.com/microsoft/vscode/issues/257673) | Long bg commands or tasks without begins/ends patterns might be considered idle when they're not | 0 | backlog-candidate | 2 | `npm run implement -- --issue 257673` |
| 69 | [#282933](https://github.com/microsoft/vscode/issues/282933) | Agent confused by SSH key login prompt on command line | 0 | backlog-candidate | 2 | — |
| 70 | [#288567](https://github.com/microsoft/vscode/issues/288567) | Prompt tweaks around terminal isBackground description | 0 | active | 2 | `npm run implement -- --issue 288567` |
| 93 | [#291175](https://github.com/microsoft/vscode/issues/291175) | Testing: Terminal part in subagent does not have scrollbar rendered | 1 | active | 1 | `npm run implement -- --issue 291175` |
| 97 | [#305725](https://github.com/microsoft/vscode/issues/305725) | auto-deny output to dev null | 1 | active | 1 | `npm run implement -- --issue 305725` |
| 106 | [#232657](https://github.com/microsoft/vscode/issues/232657) | Explore terminal quick fixes based on selection | 0 | backlog-candidate | 1 | `npm run implement -- --issue 232657` |
| 120 | [#259562](https://github.com/microsoft/vscode/issues/259562) | Run in terminal: Leverage child process monitoring as hint for whether commands are done | 0 | backlog-candidate | 1 | `npm run implement -- --issue 259562` |
| 121 | [#263996](https://github.com/microsoft/vscode/issues/263996) | Merge the task tool into the terminal tool | 0 | active | 1 | `npm run implement -- --issue 263996` |
| 126 | [#275220](https://github.com/microsoft/vscode/issues/275220) | Should terminal auto approve use the tool approval UI? | 0 | backlog-candidate | 1 | `npm run implement -- --issue 275220` |
| 128 | [#275390](https://github.com/microsoft/vscode/issues/275390) | Make it easy to copy command output button in terminal tool output | 0 | backlog-candidate | 1 | `npm run implement -- --issue 275390` |
| 129 | [#276756](https://github.com/microsoft/vscode/issues/276756) | Explore removing most default false rules from terminal auto approve | 0 | active | 1 | `npm run implement -- --issue 276756` |
| 130 | [#282783](https://github.com/microsoft/vscode/issues/282783) | Terminal tool: Detect paths in command lines for common tools | 0 | backlog-candidate | 1 | `npm run implement -- --issue 282783` |
| 131 | [#284302](https://github.com/microsoft/vscode/issues/284302) | Allow MDM to prevent modifying list of allow/denied commands for chat auto-approval | 0 | active | 1 | `npm run implement -- --issue 284302` |
| 133 | [#287867](https://github.com/microsoft/vscode/issues/287867) | Support addressable terminal selections in chat | 0 | active | 1 | `npm run implement -- --issue 287867` |
| 135 | [#291607](https://github.com/microsoft/vscode/issues/291607) | Add option to allow specific inline environment variables | 0 | active | 1 | `npm run implement -- --issue 291607` |
| 138 | [#297672](https://github.com/microsoft/vscode/issues/297672) | Expose terminal enumeration APIs for safe automation gating before kill-all actions | 0 | active | 1 | `npm run implement -- --issue 297672` |
| 141 | [#311382](https://github.com/microsoft/vscode/issues/311382) | Expose a dedicated environment variable for agents | 0 | active | 1 | — |
| 163 | [#199449](https://github.com/microsoft/vscode/issues/199449) | Allow cwd to be implicitly determined for terminal commit message quickfix | 0 | dormant | 0 | `npm run implement -- --issue 199449` |
| 185 | [#276906](https://github.com/microsoft/vscode/issues/276906) | rm `run_task` in favor of an execute strategy on `run_in_terminal` | 0 | dormant | 0 | `npm run implement -- --issue 276906` |
| 199 | [#300269](https://github.com/microsoft/vscode/issues/300269) | expose open terminal UI even when terminal command is collapsed | 0 | active | 0 | `npm run implement -- --issue 300269` |
| 201 | [#308616](https://github.com/microsoft/vscode/issues/308616) | Running benchmark results in a lot of checking terminal output | 0 | backlog-candidate | 0 | `npm run implement -- --issue 308616` |
| 202 | [#314080](https://github.com/microsoft/vscode/issues/314080) | No progress shown between terminal prompts | 0 | backlog-candidate | 0 | `npm run implement -- --issue 314080` |
| 204 | [#316307](https://github.com/microsoft/vscode/issues/316307) | Use artifacts for background terminals to improve accessibilty and stability | 0 | active | 0 | `npm run implement -- --issue 316307` |

### Accessibility support (24)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 22 | [#269246](https://github.com/microsoft/vscode/issues/269246) | [Accessibility] Expose lines numbers so that Windows 11 Voice access is able to see them for navigation | 20 | backlog-candidate | 8 | `npm run implement -- --issue 269246` |
| 35 | [#184357](https://github.com/microsoft/vscode/issues/184357) | [Accessibility]: Make syntax highlight accessible to screen reader users via a speech scheme | 17 | backlog-candidate | 5 | `npm run implement -- --issue 184357` |
| 71 | [#292577](https://github.com/microsoft/vscode/issues/292577) | Experimental: Keybinding Action Confirmation & ARIA Announcement System (opt-in) | 0 | backlog-candidate | 2 | `npm run implement -- --issue 292577` |
| 80 | [#97154](https://github.com/microsoft/vscode/issues/97154) | Use contentEditable for our hidden accessibility textArea | 2 | dormant | 1 | `npm run implement -- --issue 97154` |
| 87 | [#166472](https://github.com/microsoft/vscode/issues/166472) | [Accessibility] Add an option to allow Alt+F5 to jump to the next --word-diff instead of the whole line | 1 | backlog-candidate | 1 | `npm run implement -- --issue 166472` |
| 95 | [#293535](https://github.com/microsoft/vscode/issues/293535) | Make message queueing screen reader friendly | 1 | active | 1 | `npm run implement -- --issue 293535` |
| 101 | [#168746](https://github.com/microsoft/vscode/issues/168746) | [Accessibility] Word wrap does not work in diff view (F7 and Shift+F7) | 0 | backlog-candidate | 1 | `npm run implement -- --issue 168746` |
| 102 | [#171755](https://github.com/microsoft/vscode/issues/171755) | Code lens is not accessible via screen reader | 0 | active | 1 | `npm run implement -- --issue 171755` |
| 105 | [#219138](https://github.com/microsoft/vscode/issues/219138) | Accessibility:  "Dark high contrast theme" cursor disappears and stops blinking after a time | 0 | dormant | 1 | `npm run implement -- --issue 219138` |
| 108 | [#233844](https://github.com/microsoft/vscode/issues/233844) | Tab With Problems - Improve Accessibility for Colorblind People | 0 | backlog-candidate | 1 | `npm run implement -- --issue 233844` |
| 116 | [#242617](https://github.com/microsoft/vscode/issues/242617) | add active editor state information to editor's text area aria label | 0 | dormant | 1 | `npm run implement -- --issue 242617` |
| 119 | [#254835](https://github.com/microsoft/vscode/issues/254835) | When using macOS with the VoiceOver screen reader, moving word-by-word across a sign character causes the word to be spoken twice | 0 | backlog-candidate | 1 | `npm run implement -- --issue 254835` |
| 136 | [#292587](https://github.com/microsoft/vscode/issues/292587) | [Feature Request] User-Contributed Accessibility Help System | 0 | backlog-candidate | 1 | `npm run implement -- --issue 292587` |
| 145 | [#180049](https://github.com/microsoft/vscode/issues/180049) | [Accessibility]: Support filtering symbol types in Document Sylbol View | 1 | backlog-candidate | 0 | `npm run implement -- --issue 180049` |
| 146 | [#209683](https://github.com/microsoft/vscode/issues/209683) | consider how to make `when` clauses more discoverable for keyboard users | 1 | dormant | 0 | `npm run implement -- --issue 209683` |
| 150 | [#140950](https://github.com/microsoft/vscode/issues/140950) | Spacing out the buttons in action bar [Accessibility] | 0 | backlog-candidate | 0 | `npm run implement -- --issue 140950` |
| 158 | [#181139](https://github.com/microsoft/vscode/issues/181139) | Accessibility: Make Tab key focus restricted to the currently open view | 0 | dormant | 0 | `npm run implement -- --issue 181139` |
| 161 | [#195413](https://github.com/microsoft/vscode/issues/195413) | indicate the number of available completions in inline completions accessible view aria label | 0 | dormant | 0 | `npm run implement -- --issue 195413` |
| 162 | [#199126](https://github.com/microsoft/vscode/issues/199126) | [Accessibility] Preserve last position in the Copilot Chat response list view | 0 | dormant | 0 | `npm run implement -- --issue 199126` |
| 164 | [#204258](https://github.com/microsoft/vscode/issues/204258) | Configurable Position for Accessibility-Related Text Notifications in Code Editor | 0 | dormant | 0 | `npm run implement -- --issue 204258` |
| 167 | [#217810](https://github.com/microsoft/vscode/issues/217810) | Settings editor should have Accessibility TOC entry | 0 | backlog-candidate | 0 | `npm run implement -- --issue 217810` |
| 181 | [#273164](https://github.com/microsoft/vscode/issues/273164) | include extra info in `aria-description` instead of `aria-label` | 0 | active | 0 | `npm run implement -- --issue 273164` |
| 183 | [#274211](https://github.com/microsoft/vscode/issues/274211) | Signature help doesn't provide enough information for a screenreader user, at least in languages supporting overloads | 0 | dormant | 0 | `npm run implement -- --issue 274211` |
| 196 | [#297501](https://github.com/microsoft/vscode/issues/297501) | In High contrast themes and in screen reader mode, we should set `accessibility.chat.showCheckmarks:true` by default | 0 | backlog-candidate | 0 | `npm run implement -- --issue 297501` |

### Speech and audio (15)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 30 | [#175986](https://github.com/microsoft/vscode/issues/175986) | Allow VS Code extensions to trigger audio cues | 22 | backlog-candidate | 6 | `npm run implement -- --issue 175986` |
| 49 | [#302997](https://github.com/microsoft/vscode/issues/302997) | VS Code Speech: Add right click to read aloud selected text | 0 | active | 3 | `npm run implement -- --issue 302997` |
| 57 | [#145204](https://github.com/microsoft/vscode/issues/145204) | Introduce Sound Theme, similar like Product Icon Themes | 7 | backlog-candidate | 2 | `npm run implement -- --issue 145204` |
| 83 | [#301431](https://github.com/microsoft/vscode/issues/301431) | Improve Chat Read-Aloud (Text-to-Speech) Controls in VS Code Chat: Start Position, Navigation, Speed Control, and Visible-Text-Only Reading | 2 | backlog-candidate | 1 | `npm run implement -- --issue 301431` |
| 88 | [#180176](https://github.com/microsoft/vscode/issues/180176) | [Accessibility]: Consider replacing audioCues.lineHasInlineSuggestion with less distruptive lower-pitch sound | 1 | backlog-candidate | 1 | `npm run implement -- --issue 180176` |
| 92 | [#265744](https://github.com/microsoft/vscode/issues/265744) | Have voice input in command palette/ settings search | 1 | dormant | 1 | `npm run implement -- --issue 265744` |
| 147 | [#320820](https://github.com/microsoft/vscode/issues/320820) | Voice input should mute mic routing to other apps (e.g. Teams) while active | 1 | active | 0 | — |
| 153 | [#153722](https://github.com/microsoft/vscode/issues/153722) | Provide speech feedback when commenting or uncommenting a line. | 0 | backlog-candidate | 0 | `npm run implement -- --issue 153722` |
| 157 | [#174359](https://github.com/microsoft/vscode/issues/174359) | Add expand/collapse audio cues | 0 | dormant | 0 | `npm run implement -- --issue 174359` |
| 159 | [#185565](https://github.com/microsoft/vscode/issues/185565) | Accessibility: Cannot turn off audio cues on a language level | 0 | backlog-candidate | 0 | `npm run implement -- --issue 185565` |
| 160 | [#189374](https://github.com/microsoft/vscode/issues/189374) | Git - Add audio cues for sync changes operation | 0 | backlog-candidate | 0 | `npm run implement -- --issue 189374` |
| 168 | [#226092](https://github.com/microsoft/vscode/issues/226092) | [Accessibility] Support audio cue for commented range | 0 | dormant | 0 | `npm run implement -- --issue 226092` |
| 172 | [#239997](https://github.com/microsoft/vscode/issues/239997) | consider adding a progressive sound for applying edits | 0 | dormant | 0 | `npm run implement -- --issue 239997` |
| 200 | [#307697](https://github.com/microsoft/vscode/issues/307697) | Allow customizing the media sound for user confirmation prompts | 0 | backlog-candidate | 0 | `npm run implement -- --issue 307697` |
| 207 | [#322749](https://github.com/microsoft/vscode/issues/322749) | VS Code Speech: Right click to read aloud FROM SPECIFIC LOCATION in the response | 0 | backlog-candidate | 0 | `npm run implement -- --issue 322749` |

### Web workspaces (4)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 44 | [#167283](https://github.com/microsoft/vscode/issues/167283) | Expose User tasks and all task commands in vscode Web | 20 | backlog-candidate | 3 | `npm run implement -- --issue 167283` |
| 52 | [#153903](https://github.com/microsoft/vscode/issues/153903) | Automatically Run task does not wait for postCreateCommand in a Dev Container | 10 | backlog-candidate | 2 | `npm run implement -- --issue 153903` |
| 75 | [#76415](https://github.com/microsoft/vscode/issues/76415) | Allow for configuration files in .devcontainer | 3 | backlog-candidate | 1 | — |
| 154 | [#157112](https://github.com/microsoft/vscode/issues/157112) | Add support for running custom tasks in VS Code Web | 0 | dormant | 0 | `npm run implement -- --issue 157112` |

### Chat experience (17)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 66 | [#300574](https://github.com/microsoft/vscode/issues/300574) | Consider expanding set of tips for Copilot CLI and Claude Agent | 1 | backlog-candidate | 2 | `npm run implement -- --issue 300574` |
| 68 | [#275286](https://github.com/microsoft/vscode/issues/275286) | Provide way to go from terminal chat back to chat | 0 | backlog-candidate | 2 | `npm run implement -- --issue 275286` |
| 96 | [#298997](https://github.com/microsoft/vscode/issues/298997) | Add UI for right time right place tips | 1 | active | 1 | `npm run implement -- --issue 298997` |
| 98 | [#309506](https://github.com/microsoft/vscode/issues/309506) | Should the model be encouraged to use a small subagent for multi-stage inputs? | 1 | active | 1 | `npm run implement -- --issue 309506` |
| 124 | [#274013](https://github.com/microsoft/vscode/issues/274013) | Check edits setting in CommandLineFileWriteAnalyzer | 0 | active | 1 | `npm run implement -- --issue 274013` |
| 125 | [#275036](https://github.com/microsoft/vscode/issues/275036) | Applying inline chat V2 styles to terminal | 0 | backlog-candidate | 1 | `npm run implement -- --issue 275036` |
| 127 | [#275352](https://github.com/microsoft/vscode/issues/275352) | Widget doesn't line break on words | 0 | dormant | 1 | `npm run implement -- --issue 275352` |
| 134 | [#291111](https://github.com/microsoft/vscode/issues/291111) | Consider making the in-chat terminal header element sticky when scrolling super long code | 0 | backlog-candidate | 1 | `npm run implement -- --issue 291111` |
| 137 | [#296258](https://github.com/microsoft/vscode/issues/296258) | Copilot circumvents file exclusions | 0 | active | 1 | `npm run implement -- --issue 296258` |
| 189 | [#289465](https://github.com/microsoft/vscode/issues/289465) | Introduce model pick action item hide feature | 0 | active | 0 | `npm run implement -- --issue 289465` |
| 191 | [#291079](https://github.com/microsoft/vscode/issues/291079) | Run in terminal code block presenters  don't have same features as normal code blocks | 0 | backlog-candidate | 0 | `npm run implement -- --issue 291079` |
| 192 | [#291972](https://github.com/microsoft/vscode/issues/291972) | add a command to copy the most recent chat response text | 0 | active | 0 | `npm run implement -- --issue 291972` |
| 193 | [#294700](https://github.com/microsoft/vscode/issues/294700) | play confetti when a user takes a tip action | 0 | active | 0 | `npm run implement -- --issue 294700` |
| 195 | [#297128](https://github.com/microsoft/vscode/issues/297128) | Automate kicking off workflows for verification steps | 0 | active | 0 | `npm run implement -- --issue 297128` |
| 197 | [#299569](https://github.com/microsoft/vscode/issues/299569) | Move chat fork tip to be in session | 0 | active | 0 | `npm run implement -- --issue 299569` |
| 198 | [#299806](https://github.com/microsoft/vscode/issues/299806) | Enhance /generate-release-notes to apply `on-release-notes` labels automatically | 0 | active | 0 | `npm run implement -- --issue 299806` |
| 205 | [#316502](https://github.com/microsoft/vscode/issues/316502) | Reintroduce find/grep/tree compression with smart summarization | 0 | active | 0 | `npm run implement -- --issue 316502` |

### Other (3)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 86 | [#80820](https://github.com/microsoft/vscode/issues/80820) | "editor font zoom" does not persist | 1 | dormant | 1 | `npm run implement -- --issue 80820` |
| 139 | [#300089](https://github.com/microsoft/vscode/issues/300089) | UI Space | 0 | active | 1 | `npm run implement -- --issue 300089` |
| 165 | [#209137](https://github.com/microsoft/vscode/issues/209137) | Consider notebook status `window.title` property | 0 | active | 0 | `npm run implement -- --issue 209137` |
