# Top issues by theme — meganrogge

Experimental themed view of [the flat ranking](meganrogge.md); themes assigned by the review engine. Rank/score are the lane-wide values. Generated 2026-08-02 13:38 UTC.

## Bugs

### Task execution and variables (64)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | [#187955](https://github.com/microsoft/vscode/issues/187955) | Incorrect $PATH order in task shell | 15 | correctness | 5/6 Source-confirmed | 100 | — | — |
| 4 | [#214931](https://github.com/microsoft/vscode/issues/214931) | Quotes around paths with spaces are not honored when running tasks | 9 | correctness | 5/6 Source-confirmed | 46 | yes | — |
| 9 | [#160891](https://github.com/microsoft/vscode/issues/160891) | Incorrect Command Variable Resolution in tasks.json if task type is 'process' | 8 | correctness | 5/6 Source-confirmed | 35 | — | — |
| 10 | [#169821](https://github.com/microsoft/vscode/issues/169821) | VS Code is still adding `/d /c` to task commands | 10 | correctness | 5/6 Source-confirmed | 31 | — | — |
| 12 | [#255503](https://github.com/microsoft/vscode/issues/255503) | Unable to abandon task with ${input} variable type command | 3 | correctness | 5/6 Source-confirmed | 29 | — | — |
| 16 | [#239581](https://github.com/microsoft/vscode/issues/239581) | Input variables from user tasks are not working when no folder or workspace is opened | 8 | correctness | 2/6 Unverified | 23 | — | — |
| 17 | [#178577](https://github.com/microsoft/vscode/issues/178577) | terminal.integrated.env.linux.PATH and terminal.integrated.env.osx.PATH settings break tasks | 3 | correctness | 4/6 Traced | 22 | — | — |
| 23 | [#93001](https://github.com/microsoft/vscode/issues/93001) | resolving multiple tasks with type npm and same script fails | 4 | correctness | 5/6 Source-confirmed | 18 | yes | — |
| 33 | [#176277](https://github.com/microsoft/vscode/issues/176277) | tasks.json npm script does not work with arguments on Mac | 2 | correctness | 5/6 Source-confirmed | 15 | yes | — |
| 35 | [#236657](https://github.com/microsoft/vscode/issues/236657) | "command" content interpretation broken in tasks.json, possible arg tokenization problem? | 0 | correctness | 2/6 Unverified | 15 | — | — |
| 49 | [#226471](https://github.com/microsoft/vscode/issues/226471) | Cannot run dynamically-created shell tasks when a workspace folder is not opened | 0 | correctness | 5/6 Source-confirmed | 13 | yes | — |
| 50 | [#261630](https://github.com/microsoft/vscode/issues/261630) | `npm.scriptRunner` auto-detection fails in subdirectories; defaults to npm instead of pnpm/yarn/bun | 0 | correctness | 5/6 Source-confirmed | 13 | — | — |
| 59 | [#172865](https://github.com/microsoft/vscode/issues/172865) | npm.packageManager=auto ignores task's cwd | 1 | correctness | 5/6 Source-confirmed | 12 | — | — |
| 63 | [#235142](https://github.com/microsoft/vscode/issues/235142) | Task command hangs and doesn't recognize completion of detached processes | 2 | correctness | 4/6 Traced | 11 | — | — |
| 64 | [#225317](https://github.com/microsoft/vscode/issues/225317) | 1.92 broke my exension "The task '<task name>' is already active" | 1 | correctness | 4/6 Traced | 11 | — | — |
| 70 | [#176670](https://github.com/microsoft/vscode/issues/176670) | Error message complaining about build task | 4 | papercut | 5/6 Source-confirmed | 10 | yes | — |
| 72 | [#170101](https://github.com/microsoft/vscode/issues/170101) | npm.packageManager=auto incorrectly assumes yarn as package manager for running tasks | 1 | correctness | 5/6 Source-confirmed | 10 | — | — |
| 83 | [#158976](https://github.com/microsoft/vscode/issues/158976) | VSCode Task or .csproj PostBuild event using the "reg" command does not work | 0 | correctness | 3/6 Plausible | 9 | — | — |
| 90 | [#169381](https://github.com/microsoft/vscode/issues/169381) | Input variables quoted incorrectly | 1 | correctness | 5/6 Source-confirmed | 8 | yes | — |
| 99 | [#171943](https://github.com/microsoft/vscode/issues/171943) | Using npm as the preferred package manager. Found multiple lockfiles | 6 | papercut | 4/6 Traced | 7 | — | — |
| 100 | [#181302](https://github.com/microsoft/vscode/issues/181302) | Custom task shell executable doesn't work | 1 | correctness | 2/6 Unverified | 7 | — | — |
| 105 | [#248733](https://github.com/microsoft/vscode/issues/248733) | tasks with dependencies do not show prompt to restart/ terminate, do not respect `instanceLimit` | 0 | correctness | 5/6 Source-confirmed | 7 | yes | — |
| 114 | [#157041](https://github.com/microsoft/vscode/issues/157041) | Programmatically running a task in VS Code Web ignores `dependsOn` tasks | 0 | correctness | 5/6 Source-confirmed | 6 | yes | — |
| 115 | [#158615](https://github.com/microsoft/vscode/issues/158615) | "Run VS Code outside the Developer Command Prompt" instructions fail if opened file's basename and/or dirname contains space characters | 0 | correctness | 4/6 Traced | 6 | yes | — |
| 116 | [#159465](https://github.com/microsoft/vscode/issues/159465) | VSCode uses yarn to run npm tasks | 0 | correctness | 3/6 Plausible | 6 | — | — |
| 117 | [#187661](https://github.com/microsoft/vscode/issues/187661) | C# Dev Kit: None of the ShellQuoting values work in all cases to run dotnet build command using ShellExecution | 0 | correctness | 4/6 Traced | 6 | — | — |
| 118 | [#211851](https://github.com/microsoft/vscode/issues/211851) | Task doesn't execute bash commands in background (with &) | 0 | correctness | 4/6 Traced | 6 | — | — |
| 119 | [#213928](https://github.com/microsoft/vscode/issues/213928) | Terminal fails to launch on Task Rerun with "A native exception occurred during launch (args as a string is not supported on unix.)." | 0 | correctness | 2/6 Unverified | 6 | — | — |
| 123 | [#266487](https://github.com/microsoft/vscode/issues/266487) | Running task terminal left open after extension host reload | 0 | correctness | 4/6 Traced | 6 | — | — |
| 124 | [#270585](https://github.com/microsoft/vscode/issues/270585) | Task commands retrieved from a command won't be recognized as absolute | 0 | correctness | 5/6 Source-confirmed | 6 | — | — |
| 129 | [#96643](https://github.com/microsoft/vscode/issues/96643) | Tasks (and TaskExecutions) are not === in the onDid(Start\|End)Task callbacks. | 1 | correctness | 2/6 Unverified | 5 | — | — |
| 133 | [#170937](https://github.com/microsoft/vscode/issues/170937) | Support `runOn` with `folderOpen` when adding folder to workspace | 0 | correctness | 5/6 Source-confirmed | 5 | yes | — |
| 136 | [#194084](https://github.com/microsoft/vscode/issues/194084) | `task.json` -> `options.env` not working of `${env:VAR}` expansion | 0 | correctness | 5/6 Source-confirmed | 5 | yes | — |
| 150 | [#154146](https://github.com/microsoft/vscode/issues/154146) | The pseudo terminal's name cannot be changed for custom task provider | 0 | correctness | 5/6 Source-confirmed | 4 | — | — |
| 151 | [#164791](https://github.com/microsoft/vscode/issues/164791) | Variable substitution in tasks.json doesn't work for custom tasks provided by extension | 0 | correctness | 4/6 Traced | 4 | yes | — |
| 152 | [#165256](https://github.com/microsoft/vscode/issues/165256) | tasks: empty arguments are not properly passed to the command | 0 | correctness | 5/6 Source-confirmed | 4 | yes | — |
| 155 | [#208350](https://github.com/microsoft/vscode/issues/208350) | Tasks using command variables don't run in split terminals | 0 | correctness | 4/6 Traced | 4 | — | — |
| 176 | [#142796](https://github.com/microsoft/vscode/issues/142796) | Task that runs on folderOpen also always opens new terminal | 0 | papercut | 4/6 Traced | 3 | — | — |
| 177 | [#157957](https://github.com/microsoft/vscode/issues/157957) | Visual Studio Code launch can't find custom prelaunch task | 0 | papercut | 5/6 Source-confirmed | 3 | — | — |
| 178 | [#165292](https://github.com/microsoft/vscode/issues/165292) | Incorrect errors shown when launching in remote container (Codespaces) | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 189 | [#303807](https://github.com/microsoft/vscode/issues/303807) | In a multi-root workspace, all user tasks are injected into request context multiple times (for each workspace folder) | 0 | papercut | 5/6 Source-confirmed | 3 | yes | — |
| 192 | [#306723](https://github.com/microsoft/vscode/issues/306723) | The terminal title for a workspace-scoped task in a multi-root workspace shows a misleading folder suffix | 0 | papercut | 5/6 Source-confirmed | 3 | yes | — |
| 198 | [#173842](https://github.com/microsoft/vscode/issues/173842) | Task with empty command does not terminate | 0 | papercut | 5/6 Source-confirmed | 2 | — | — |
| 199 | [#179952](https://github.com/microsoft/vscode/issues/179952) | RunTask command lists duplicate tasks when a filter is applied | 0 | correctness | 5/6 Source-confirmed | 2 | yes | — |
| 202 | [#234358](https://github.com/microsoft/vscode/issues/234358) | Task API for `ShellExecutionOptions.env` type does not support `undefined` values | 0 | papercut | 5/6 Source-confirmed | 2 | yes | — |
| 206 | [#301063](https://github.com/microsoft/vscode/issues/301063) | Zephyr - Build Process Hangs on Subsequent Builds After First Successful Run in VSCode | 0 | none | 3/6 Plausible | 2 | — | — |
| 222 | [#82623](https://github.com/microsoft/vscode/issues/82623) | "There are task errors" while typing in tasks.json | 0 | papercut | 5/6 Source-confirmed | 1 | yes | — |
| 223 | [#91436](https://github.com/microsoft/vscode/issues/91436) | Task instanceLimit doesn't work when depending on long running tasks | 0 | correctness | 2/6 Unverified | 1 | — | — |
| 226 | [#159135](https://github.com/microsoft/vscode/issues/159135) | Some global properties in tasks.json don't  take effect | 0 | papercut | 5/6 Source-confirmed | 1 | yes | — |
| 230 | [#177550](https://github.com/microsoft/vscode/issues/177550) | npm scripts do not run in integrated terminal when it has init script for cmd and powershell | 0 | none | — | 1 | — | — |
| 234 | [#186018](https://github.com/microsoft/vscode/issues/186018) | TaskProvider not working when Remoting via SSH | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 258 | [#316388](https://github.com/microsoft/vscode/issues/316388) | Agents App: `Error: there is no registered task type 'cppbuild'.` | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 267 | [#158764](https://github.com/microsoft/vscode/issues/158764) | Parallel tasks with INPUT selection does not run all tasks. | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 268 | [#158940](https://github.com/microsoft/vscode/issues/158940) | Live preview extension contributed task does not include the "Task" tab description | 0 | papercut | 5/6 Source-confirmed | 0 | yes | — |
| 269 | [#174791](https://github.com/microsoft/vscode/issues/174791) | Tasks interfering despite sequence order | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 272 | [#187746](https://github.com/microsoft/vscode/issues/187746) | tasks.json: Operating system specific properties can't be combined with the dependsOn property | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 275 | [#193268](https://github.com/microsoft/vscode/issues/193268) | Tasks should add a new line before the VS Code format message if it's not at the start of a line | 0 | visual | 5/6 Source-confirmed | 0 | yes | — |
| 277 | [#213825](https://github.com/microsoft/vscode/issues/213825) | Run Task command silently does nothing in serverless | 0 | papercut | 5/6 Source-confirmed | 0 | yes | — |
| 282 | [#248759](https://github.com/microsoft/vscode/issues/248759) | Sidebar "Run" Button Fails with command not found: npm on Linux (works on macOS) | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 284 | [#250457](https://github.com/microsoft/vscode/issues/250457) | Tasks.json hover show broken path | 0 | visual | 3/6 Plausible | 0 | — | — |
| 298 | [#298101](https://github.com/microsoft/vscode/issues/298101) | ${workspaceFolderBasename} does not resolve in projectPath | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 308 | [#307773](https://github.com/microsoft/vscode/issues/307773) | `workbench.action.tasks.runTask` or `Terminal` > `Run Task...` > `Configure Task` will force `tasks.json` file to be formatted in `JSON` format will cause all comments in the `tasks: []` to disappear | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 326 | [#319246](https://github.com/microsoft/vscode/issues/319246) | Running Tasks badge remains after task termination in Dev Container | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 327 | [#320669](https://github.com/microsoft/vscode/issues/320669) | Tasks cannot run MSIX-packaged pwsh | 0 | correctness | 4/6 Traced | 0 | — | — |

### Agent terminal integration (63)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2 | [#301804](https://github.com/microsoft/vscode/issues/301804) | Copilot Agent run_in_terminal fails with ENOPRO: No file system provider found in GitHub Codespaces | 7 | correctness | 2/6 Unverified | 79 | — | — |
| 3 | [#275625](https://github.com/microsoft/vscode/issues/275625) | run_in_terminal tool missed the first char in sending a command into git bash terminal | 9 | correctness | 3/6 Plausible | 53 | — | — |
| 15 | [#293859](https://github.com/microsoft/vscode/issues/293859) | Agent fails to monitor background terminal state, causing redundant re-deployment | 0 | correctness | 3/6 Plausible | 24 | — | — |
| 18 | [#292878](https://github.com/microsoft/vscode/issues/292878) | Not waiting terminal finish and new command cancel the last command | 0 | correctness | 3/6 Plausible | 22 | — | — |
| 20 | [#283507](https://github.com/microsoft/vscode/issues/283507) | run_in_terminal fails with Oh My Zsh RPS1 (right-side prompt) - returns only prompt instead of command output CAUSE FOUND | 1 | correctness | 4/6 Traced | 19 | — | — |
| 21 | [#307166](https://github.com/microsoft/vscode/issues/307166) | Copilot cannot read the output of `node -v` | 1 | correctness | 5/6 Source-confirmed | 19 | yes | — |
| 25 | [#284159](https://github.com/microsoft/vscode/issues/284159) | Copilot Agent adds Cyrillic 'с' prefix to commands when chatting in Ukrainian/Russian | 1 | correctness | 3/6 Plausible | 18 | — | — |
| 26 | [#287648](https://github.com/microsoft/vscode/issues/287648) | opus kills its own terminal requests by trying to wait for them | 1 | correctness | 3/6 Plausible | 18 | — | — |
| 31 | [#288104](https://github.com/microsoft/vscode/issues/288104) | @terminal with #terminalLastCommand did not work | 0 | correctness | 3/6 Plausible | 17 | — | — |
| 34 | [#279327](https://github.com/microsoft/vscode/issues/279327) | [Copilot] Agent always uses pwsh but grabs args list from default terminal profile. | 1 | correctness | 2/6 Unverified | 15 | — | — |
| 36 | [#270810](https://github.com/microsoft/vscode/issues/270810) | Terminal tool misuses double quotes in bash (eg. history expansion), especially when running python | 0 | correctness | 5/6 Source-confirmed | 15 | yes | — |
| 37 | [#271902](https://github.com/microsoft/vscode/issues/271902) | Investigate SIGINT from PromptInputModel being incorrectly used in chat terminal tool result | 0 | correctness | 2/6 Unverified | 15 | — | — |
| 40 | [#303785](https://github.com/microsoft/vscode/issues/303785) | Terminal tool output shows up in multiple places and is confusing | 0 | visual | 3/6 Plausible | 15 | — | — |
| 42 | [#316120](https://github.com/microsoft/vscode/issues/316120) | [CRITICAL - Data Loss] Copilot agent bypasses WSL sandbox and deletes user home directory due to Windows/WSL quoting failure | 1 | data-loss | 3/6 Plausible | 14 | — | — |
| 43 | [#259088](https://github.com/microsoft/vscode/issues/259088) | Run in terminal: Confirmation edited command disappears when you scroll it out of view and back in | 0 | correctness | 2/6 Unverified | 14 | — | — |
| 45 | [#290065](https://github.com/microsoft/vscode/issues/290065) | Opening Terminal from an agent confirm-input flow doesn't show all output | 0 | visual | 3/6 Plausible | 14 | — | — |
| 53 | [#271391](https://github.com/microsoft/vscode/issues/271391) | Copilot cannot "see" contents of `Pseudoterminal`s created for `CustomExecution` | 0 | correctness | 4/6 Traced | 13 | — | — |
| 55 | [#306490](https://github.com/microsoft/vscode/issues/306490) | bg terminal fails to start in other directory | 0 | correctness | 3/6 Plausible | 13 | — | — |
| 60 | [#291445](https://github.com/microsoft/vscode/issues/291445) | Terminal timeout shouldn't count when waiting for user input | 0 | correctness | — | 12 | — | — |
| 68 | [#274803](https://github.com/microsoft/vscode/issues/274803) | 1.106.x - Github Copilot run_in_terminal - fails to capture output when the terminal uses some fancy plugins or PS1 (e.g. zsh and aws plugin) (worked in VS Code 1.103) | 0 | correctness | 3/6 Plausible | 11 | — | — |
| 71 | [#286847](https://github.com/microsoft/vscode/issues/286847) | Copilot setting focus to terminal ruins experience when terminal is also in right pane | 3 | papercut | 3/6 Plausible | 10 | — | — |
| 80 | [#253271](https://github.com/microsoft/vscode/issues/253271) | Agent mode does not use correct path syntax for git bash on windows | 1 | correctness | 4/6 Traced | 9 | — | — |
| 91 | [#309502](https://github.com/microsoft/vscode/issues/309502) | RunInTerminalTool` ignores `automationProfile` and incorrectly merges terminal settings on Windows | 1 | correctness | 5/6 Source-confirmed | 8 | yes | — |
| 96 | [#303496](https://github.com/microsoft/vscode/issues/303496) | Copilot has no information on the terminal shell and will always send bash commands to fish | 0 | correctness | 2/6 Unverified | 8 | — | — |
| 107 | [#287552](https://github.com/microsoft/vscode/issues/287552) | Chat: `chat.tools.terminal.autoApprove` is not resource scoped | 0 | correctness | 5/6 Source-confirmed | 7 | yes | — |
| 113 | [#296037](https://github.com/microsoft/vscode/issues/296037) | Terminal script execution fails due to heredoc/simplified command logic | 1 | correctness | 3/6 Plausible | 6 | — | — |
| 122 | [#264727](https://github.com/microsoft/vscode/issues/264727) | Terminal tool call UI doesn't serialize language | 0 | visual | 3/6 Plausible | 6 | — | — |
| 127 | [#306165](https://github.com/microsoft/vscode/issues/306165) | Skipping terminal tool call results in model trying to run the terminal tool once again | 0 | papercut | 5/6 Source-confirmed | 6 | — | — |
| 128 | [#309796](https://github.com/microsoft/vscode/issues/309796) | Terminal approval UI is missing slashes (on windows) | 0 | visual | 5/6 Source-confirmed | 6 | yes | — |
| 130 | [#263590](https://github.com/microsoft/vscode/issues/263590) | Run in terminal should prefer winget over install scripts | 1 | papercut | 3/6 Plausible | 5 | — | — |
| 131 | [#264789](https://github.com/microsoft/vscode/issues/264789) | Agent can't find existing terminal running background watch task | 1 | papercut | 3/6 Plausible | 5 | — | — |
| 149 | [#314197](https://github.com/microsoft/vscode/issues/314197) | Terminal sometimes does not show output preview | 1 | visual | 3/6 Plausible | 4 | — | — |
| 159 | [#275037](https://github.com/microsoft/vscode/issues/275037) | Terminal approval: Windows path in WSL context | 0 | visual | 6/6 Confirmed | 4 | — | — |
| 163 | [#286994](https://github.com/microsoft/vscode/issues/286994) | GitHub Copilot mostly pays attention on `zoxide` command and in result gives incorrent answers on `#terminalLastCommand` attachment, regardless of AI provider | 0 | correctness | 5/6 Source-confirmed | 4 | — | — |
| 168 | [#314069](https://github.com/microsoft/vscode/issues/314069) | Agent got confused about special characters in output | 0 | correctness | 6/6 Confirmed | 4 | — | — |
| 170 | [#315694](https://github.com/microsoft/vscode/issues/315694) | bad quoting can cause terminal to hang | 0 | correctness | 2/6 Unverified | 4 | — | — |
| 173 | [#249444](https://github.com/microsoft/vscode/issues/249444) | Issue with GitHub Copilot in VS Code when using Git Bash on Windows | 2 | papercut | 6/6 Confirmed | 3 | — | — |
| 193 | [#316375](https://github.com/microsoft/vscode/issues/316375) | First copilot command always fails | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 203 | [#268777](https://github.com/microsoft/vscode/issues/268777) | Problem: not aware of entering properly into a docker container | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 208 | [#314081](https://github.com/microsoft/vscode/issues/314081) | Hitting the stop button between terminal prompts doesn't result in the command getting killed | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 211 | [#316981](https://github.com/microsoft/vscode/issues/316981) | run in terminal - Terminal content misses line | 0 | correctness | 6/6 Confirmed | 2 | — | — |
| 212 | [#316996](https://github.com/microsoft/vscode/issues/316996) | [Bug] Incomplete Sanitization in conversationFeature.ts: Double-Escaping Bug Allows Shell Argument Injection in Git Commit Message | 0 | correctness | 5/6 Source-confirmed | 2 | — | — |
| 215 | [#319413](https://github.com/microsoft/vscode/issues/319413) | chat reacts when terminal task is still going | 0 | papercut | 5/6 Source-confirmed | 2 | — | — |
| 246 | [#275290](https://github.com/microsoft/vscode/issues/275290) | Agent gets distracted by extra terminal context | 0 | correctness | 6/6 Confirmed | 1 | — | — |
| 249 | [#304279](https://github.com/microsoft/vscode/issues/304279) | Claude subagent describes commands as `undefined` | 0 | visual | 2/6 Unverified | 1 | — | — |
| 264 | [#323202](https://github.com/microsoft/vscode/issues/323202) | terminal.integrated.cwd:${fileDirname} confuses copilot | 0 | correctness | 5/6 Source-confirmed | 1 | yes | — |
| 265 | [#327521](https://github.com/microsoft/vscode/issues/327521) | Copilot agent terminal commands falsely time out while command has already completed | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 291 | [#288635](https://github.com/microsoft/vscode/issues/288635) | Investigate sed flexible delimiters | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 292 | [#290952](https://github.com/microsoft/vscode/issues/290952) | "tool simplified the command" with preprended space seems unnecessary | 0 | papercut | 2/6 Unverified | 0 | — | — |
| 294 | [#295620](https://github.com/microsoft/vscode/issues/295620) | Copilot with Claude models fails to handle backticks with gh | 0 | correctness | 4/6 Traced | 0 | — | — |
| 296 | [#296026](https://github.com/microsoft/vscode/issues/296026) | Summarisation of terminal output witholds key information from agent | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 297 | [#296641](https://github.com/microsoft/vscode/issues/296641) | run_in_terminal: timeout description says 'optional' but it's in the required array | 0 | papercut | 2/6 Unverified | 0 | — | — |
| 299 | [#300116](https://github.com/microsoft/vscode/issues/300116) | Agent using gh CLI always opens alt buffer | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 300 | [#302310](https://github.com/microsoft/vscode/issues/302310) | Duplicate terminal command message | 0 | visual | 3/6 Plausible | 0 | — | — |
| 302 | [#304555](https://github.com/microsoft/vscode/issues/304555) | Copilot Chat: child_process ENOPRO when file:// URIs are passed to commands | 0 | correctness | 4/6 Traced | 0 | yes | — |
| 306 | [#307642](https://github.com/microsoft/vscode/issues/307642) | VS Code Copilot Fails to access codespaces terminal on liveshare | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 311 | [#312363](https://github.com/microsoft/vscode/issues/312363) | RunInTerminalTool hangs forever when trackIdleOnPrompt is stuck in Executing state | 0 | freeze | 2/6 Unverified | 0 | — | — |
| 313 | [#313601](https://github.com/microsoft/vscode/issues/313601) | Flaky: chat.runInTerminal 'non-zero exit code is reported' | 0 | correctness | 6/6 Confirmed | 0 | — | — |
| 314 | [#314064](https://github.com/microsoft/vscode/issues/314064) | Got an external terminal from the agent | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 315 | [#314092](https://github.com/microsoft/vscode/issues/314092) | Scripts in package.json not checked for auto approve | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 318 | [#314212](https://github.com/microsoft/vscode/issues/314212) | Agent unable to read large truncated output | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 319 | [#316222](https://github.com/microsoft/vscode/issues/316222) | Run in terminal sync mode returns stale `^C` in Remote-SSH Windows/PowerShell | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 320 | [#316995](https://github.com/microsoft/vscode/issues/316995) | [Bug] Improper Encoding in Copilot Git Commit Message Sanitizer — Double-Escaping Allows Shell Argument Injection | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |

### Chat and agent UI (32)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 5 | [#283328](https://github.com/microsoft/vscode/issues/283328) | No stop button to interrupt agent | 3 | correctness | 6/6 Confirmed | 46 | — | — |
| 13 | [#321432](https://github.com/microsoft/vscode/issues/321432) | Agent turn hangs indefinitely when a streaming response stalls (no idle timeout in messagesApi/responsesApi SSE read loop) | 1 | freeze | 6/6 Confirmed | 28 | — | — |
| 22 | [#301249](https://github.com/microsoft/vscode/issues/301249) | Chat questions don't scroll | 0 | visual | 3/6 Plausible | 19 | — | — |
| 54 | [#293495](https://github.com/microsoft/vscode/issues/293495) | Missing "continue in background" button | 0 | correctness | 5/6 Source-confirmed | 13 | — | — |
| 56 | [#306948](https://github.com/microsoft/vscode/issues/306948) | Sessions: Unable to edit commit message | 0 | correctness | 2/6 Unverified | 13 | — | — |
| 69 | [#294584](https://github.com/microsoft/vscode/issues/294584) | Agent "AskQuestion" user defined option not selectable | 0 | correctness | 2/6 Unverified | 11 | — | — |
| 76 | [#275074](https://github.com/microsoft/vscode/issues/275074) | Terminal tool: horizontal scrollbar visible even when not needed | 0 | visual | 6/6 Confirmed | 10 | — | — |
| 85 | [#291011](https://github.com/microsoft/vscode/issues/291011) | Chat terminal: some command doesn't have expand/collapse button | 0 | visual | 3/6 Plausible | 9 | — | — |
| 110 | [#297735](https://github.com/microsoft/vscode/issues/297735) | Terminal inline chat model picker is not vertically centered | 0 | visual | — | 7 | — | — |
| 126 | [#301424](https://github.com/microsoft/vscode/issues/301424) | Sessions: seeing terminal error popping up when working with multiple sessions on `vscode` | 0 | correctness | 5/6 Source-confirmed | 6 | yes | — |
| 139 | [#280819](https://github.com/microsoft/vscode/issues/280819) | No vertical scrollbar for longer terminal outputs in panel chat | 0 | papercut | 5/6 Source-confirmed | 5 | — | — |
| 140 | [#285700](https://github.com/microsoft/vscode/issues/285700) | Completed terminal commands in bg sessions have odd padding | 0 | visual | 3/6 Plausible | 5 | — | — |
| 142 | [#308046](https://github.com/microsoft/vscode/issues/308046) | Async terminal shows "@terminal /explain" header | 0 | visual | 3/6 Plausible | 5 | — | — |
| 143 | [#308918](https://github.com/microsoft/vscode/issues/308918) | "retry" on async terminal steering message causes it to rerender incorrectly | 0 | visual | 5/6 Source-confirmed | 5 | yes | — |
| 160 | [#275076](https://github.com/microsoft/vscode/issues/275076) | Terminal: voice chat and ghost text collide | 0 | visual | 3/6 Plausible | 4 | — | — |
| 161 | [#280735](https://github.com/microsoft/vscode/issues/280735) | [inline chat] terminal preview clipped when paired with error "Sorry, no response was returned!" | 0 | visual | 3/6 Plausible | 4 | — | — |
| 164 | [#291008](https://github.com/microsoft/vscode/issues/291008) | Chat terminal: cannot copy output from expanded output window via ctrl + c or right click | 0 | papercut | 5/6 Source-confirmed | 4 | — | — |
| 165 | [#297277](https://github.com/microsoft/vscode/issues/297277) | Model name trimmed in terminal inline chat despite lots of horizontal space | 0 | visual | 5/6 Source-confirmed | 4 | — | — |
| 185 | [#256050](https://github.com/microsoft/vscode/issues/256050) | Add close button to terminal inline chat | 0 | papercut | 3/6 Plausible | 3 | — | — |
| 188 | [#295116](https://github.com/microsoft/vscode/issues/295116) | Inline terminal sometimes does not take full available width | 0 | visual | 3/6 Plausible | 3 | — | — |
| 207 | [#309480](https://github.com/microsoft/vscode/issues/309480) | Chat in editor hides ask_questions interface when tab is hidden | 0 | correctness | 4/6 Traced | 2 | — | — |
| 213 | [#318223](https://github.com/microsoft/vscode/issues/318223) | [Error] unhandlederror-Cannot register two commands with the same id: workbench.action.chat.openNewChatSessi... | 0 | correctness | 2/6 Unverified | 2 | — | — |
| 218 | [#328231](https://github.com/microsoft/vscode/issues/328231) | [Error] unhandlederror-command 'workbench.action.chat.openPlan' not found | 0 | correctness | 6/6 Confirmed | 2 | — | — |
| 237 | [#221609](https://github.com/microsoft/vscode/issues/221609) | Inline terminal chat is too small when response comes in | 0 | visual | 6/6 Confirmed | 1 | — | — |
| 248 | [#302164](https://github.com/microsoft/vscode/issues/302164) | Invalid tip shown on Claude | 0 | papercut | 3/6 Plausible | 1 | — | — |
| 262 | [#321632](https://github.com/microsoft/vscode/issues/321632) | Chat: system notification XML tags rendered raw in conversation | 0 | visual | 2/6 Unverified | 1 | — | — |
| 283 | [#250402](https://github.com/microsoft/vscode/issues/250402) | Chat continues progress in background when sending empty message. | 0 | papercut | 2/6 Unverified | 0 | — | — |
| 295 | [#295960](https://github.com/microsoft/vscode/issues/295960) | The scroll bar and active item indicator are rendered on top of the terminal inline chat suggest | 0 | visual | 5/6 Source-confirmed | 0 | — | — |
| 301 | [#304137](https://github.com/microsoft/vscode/issues/304137) | Active vs inactive selection in ask_questions | 0 | visual | 5/6 Source-confirmed | 0 | yes | — |
| 304 | [#306043](https://github.com/microsoft/vscode/issues/306043) | Bad styling for "The command opened the alternate buffer" | 0 | visual | 4/6 Traced | 0 | — | — |
| 305 | [#307292](https://github.com/microsoft/vscode/issues/307292) | Terminal confirmation disclaimer renders as KaTeX math when path contains `$` | 0 | visual | 5/6 Source-confirmed | 0 | yes | — |
| 330 | [#322164](https://github.com/microsoft/vscode/issues/322164) | special paste hotkey conflict within chat input | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |

### Terminal suggestions (36)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 6 | [#282541](https://github.com/microsoft/vscode/issues/282541) | zsh themes that use `RPROMPT` seem to break suggest feature of integrated terminal | 1 | correctness | 5/6 Source-confirmed | 38 | yes | — |
| 8 | [#286207](https://github.com/microsoft/vscode/issues/286207) | terminal integrated suggest inserts wrong text when tab is pressed due to latency | 2 | correctness | 4/6 Traced | 36 | — | — |
| 27 | [#290109](https://github.com/microsoft/vscode/issues/290109) | Terminal Quick Suggestions popup window overflows with the text editor | 1 | visual | 5/6 Source-confirmed | 18 | — | — |
| 38 | [#284877](https://github.com/microsoft/vscode/issues/284877) | Terminal suggest making terminal input laggy | 0 | perf | 6/6 Confirmed | 15 | — | — |
| 44 | [#264737](https://github.com/microsoft/vscode/issues/264737) | Terminal suggestions feel slow to appear over remote | 0 | perf | 3/6 Plausible | 14 | — | — |
| 51 | [#264741](https://github.com/microsoft/vscode/issues/264741) | Can't get suggestions after clearing the terminal | 0 | correctness | 6/6 Confirmed | 13 | — | — |
| 52 | [#267297](https://github.com/microsoft/vscode/issues/267297) | Terminal suggestions dont match when pressing tab | 0 | correctness | 3/6 Plausible | 13 | — | — |
| 67 | [#244491](https://github.com/microsoft/vscode/issues/244491) | Terminal QuickFix Provider and Command with arguments fail. | 0 | correctness | 5/6 Source-confirmed | 11 | yes | — |
| 74 | [#272371](https://github.com/microsoft/vscode/issues/272371) | Terminal completions do not show files within `.venv` | 0 | correctness | 3/6 Plausible | 10 | — | — |
| 75 | [#273732](https://github.com/microsoft/vscode/issues/273732) | Terminal suggest hijacks listing files | 0 | correctness | 6/6 Confirmed | 10 | — | — |
| 77 | [#277778](https://github.com/microsoft/vscode/issues/277778) | Terminal Intellisense missing completions when using `zsh-autosuggestions` | 0 | correctness | 3/6 Plausible | 10 | — | — |
| 78 | [#281631](https://github.com/microsoft/vscode/issues/281631) | Suggestions show up when trying to write path | 0 | correctness | 3/6 Plausible | 10 | — | — |
| 106 | [#262314](https://github.com/microsoft/vscode/issues/262314) | Terminal suggest: git branch -D doesn't play nice with `/` char | 0 | correctness | 3/6 Plausible | 7 | — | — |
| 109 | [#293219](https://github.com/microsoft/vscode/issues/293219) | Intellisense suggestion on command line, when accepted, just gets appended to command instead of replacing the snippet that prompted it | 0 | correctness | 3/6 Plausible | 7 | — | — |
| 112 | [#277288](https://github.com/microsoft/vscode/issues/277288) | Terminal autocomplete menu is partially offscreen when window is narrow | 1 | visual | 5/6 Source-confirmed | 6 | yes | — |
| 121 | [#243771](https://github.com/microsoft/vscode/issues/243771) | sometimes when the terminal is wrapped, suggestions aren't provided | 0 | correctness | 5/6 Source-confirmed | 6 | — | — |
| 125 | [#275023](https://github.com/microsoft/vscode/issues/275023) | Terminal Completion is not place to fit in the window and not render above the current line | 0 | visual | 5/6 Source-confirmed | 6 | — | — |
| 132 | [#167617](https://github.com/microsoft/vscode/issues/167617) | Terminal quick fixes often don't work on Linux | 0 | correctness | 3/6 Plausible | 5 | — | — |
| 138 | [#280363](https://github.com/microsoft/vscode/issues/280363) | Terminal Intellisense breaks with PowerShell when using Starship | 0 | correctness | 5/6 Source-confirmed | 5 | yes | — |
| 154 | [#196606](https://github.com/microsoft/vscode/issues/196606) | Terminal quick fix should go away when a command is run | 0 | visual | 5/6 Source-confirmed | 4 | yes | — |
| 156 | [#224553](https://github.com/microsoft/vscode/issues/224553) | terminal integration proposal replaces the original input | 0 | correctness | 6/6 Confirmed | 4 | — | — |
| 175 | [#286124](https://github.com/microsoft/vscode/issues/286124) | Terminal & Windows: Git Bash shows infinite loading when clicking “Show Suggestions” | 1 | correctness | 3/6 Plausible | 3 | — | — |
| 183 | [#240139](https://github.com/microsoft/vscode/issues/240139) | Terminal suggest: fig generator completions often complain about the executable not existing | 0 | correctness | 6/6 Confirmed | 3 | — | — |
| 184 | [#241858](https://github.com/microsoft/vscode/issues/241858) | CDPATH suggestions do not work well with ZSH auto completion | 0 | correctness | 5/6 Source-confirmed | 3 | — | — |
| 186 | [#275347](https://github.com/microsoft/vscode/issues/275347) | Chat: Insert into Terminal should not auto trigger Suggestion | 0 | papercut | 5/6 Source-confirmed | 3 | yes | — |
| 204 | [#286068](https://github.com/microsoft/vscode/issues/286068) | Terminal suggest status doesn't respect keybindings customizations | 0 | papercut | 5/6 Source-confirmed | 2 | yes | — |
| 229 | [#176684](https://github.com/microsoft/vscode/issues/176684) | Terminal quick fix for creating PR results in branch name with extra padding | 0 | papercut | 2/6 Unverified | 1 | — | — |
| 245 | [#264750](https://github.com/microsoft/vscode/issues/264750) | Odd text show for `mkdir` terminal suggestion on windows | 0 | visual | 6/6 Confirmed | 1 | — | — |
| 253 | [#310196](https://github.com/microsoft/vscode/issues/310196) | clearing terminal input will remove icons | 0 | visual | 3/6 Plausible | 1 | — | — |
| 260 | [#318402](https://github.com/microsoft/vscode/issues/318402) | Terminal suggest completes incorrectly when text is wrapped | 0 | correctness | 4/6 Traced | 1 | — | — |
| 286 | [#264749](https://github.com/microsoft/vscode/issues/264749) | Powershell file suggestions don't automatically when typing | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 287 | [#267221](https://github.com/microsoft/vscode/issues/267221) | cd prefix simplification isn't handling absolute paths | 0 | papercut | 4/6 Traced | 0 | yes | — |
| 290 | [#287781](https://github.com/microsoft/vscode/issues/287781) | Investigate why SI warning shows when rich is enabled | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 312 | [#312431](https://github.com/microsoft/vscode/issues/312431) | Completion of PowerShell parameters in terminal doesn't work | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 332 | [#325452](https://github.com/microsoft/vscode/issues/325452) | Terminal quick fix icon overlaps left side bar | 0 | visual | 5/6 Source-confirmed | 0 | yes | — |
| 336 | [#326920](https://github.com/microsoft/vscode/issues/326920) | Terminal suggest spawns runaway bash processes when npm/yarn package.json lookup reaches / | 0 | perf | 5/6 Source-confirmed | 0 | yes | — |

### Terminal UI and lifecycle (41)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 7 | [#320220](https://github.com/microsoft/vscode/issues/320220) | Integrated terminal freezes when pasting plain text copied from LibreOffice on Linux | 1 | freeze | 6/6 Confirmed | 37 | — | — |
| 19 | [#167643](https://github.com/microsoft/vscode/issues/167643) | Setting icon and color in createTerminal API no longer works correctly | 6 | correctness | 6/6 Confirmed | 21 | — | — |
| 24 | [#316246](https://github.com/microsoft/vscode/issues/316246) | Mouse drag stops working in tmux session when the terminal window is moved to a New Window | 3 | correctness | 5/6 Source-confirmed | 18 | — | — |
| 41 | [#267796](https://github.com/microsoft/vscode/issues/267796) | Add horizontal tab bar for terminals in a standalone window | 2 | correctness | 5/6 Source-confirmed | 14 | — | — |
| 47 | [#301378](https://github.com/microsoft/vscode/issues/301378) | Terminal colours wrong from ANSI sequence | 0 | visual | 5/6 Source-confirmed | 14 | — | — |
| 48 | [#190749](https://github.com/microsoft/vscode/issues/190749) | Restored terminals in editor area don't restore the current working directory from the previous session. | 2 | correctness | 5/6 Source-confirmed | 13 | yes | — |
| 58 | [#317970](https://github.com/microsoft/vscode/issues/317970) | Long terminal tab title (set via OSC sequence) overflows into the panel action buttons in single-tab mode | 3 | visual | 6/6 Confirmed | 12 | — | — |
| 62 | [#205254](https://github.com/microsoft/vscode/issues/205254) | parentTerminal doesn't always work | 2 | correctness | 5/6 Source-confirmed | 11 | — | — |
| 73 | [#186862](https://github.com/microsoft/vscode/issues/186862) | Terminal tabs are re-rendered several times on start up | 0 | perf | 3/6 Plausible | 10 | — | — |
| 95 | [#287059](https://github.com/microsoft/vscode/issues/287059) | Workspace folder name integrated terminal title not preserved on window reload | 0 | correctness | 5/6 Source-confirmed | 8 | yes | — |
| 102 | [#186866](https://github.com/microsoft/vscode/issues/186866) | SIngle terminal tabs is re-rendered several times on start up | 0 | perf | 2/6 Unverified | 7 | — | — |
| 120 | [#238073](https://github.com/microsoft/vscode/issues/238073) | terminal.integrated.defaultLocation: editor makes it impossible to open a normal 'pane' terminal as well | 0 | correctness | 5/6 Source-confirmed | 6 | yes | — |
| 134 | [#171835](https://github.com/microsoft/vscode/issues/171835) | Integrated console seems lead to a long delay when executing C/C++ code | 0 | perf | 3/6 Plausible | 5 | — | — |
| 135 | [#183268](https://github.com/microsoft/vscode/issues/183268) | Some Mac keyboard shortcuts does not work in the new Terminal Editor after being moved with `workbench.action.moveEditorTo<Side>Group` until the terminal editor has been unfocused and focused again | 0 | correctness | 2/6 Unverified | 5 | — | — |
| 137 | [#234602](https://github.com/microsoft/vscode/issues/234602) | icon is not colored correctly for failing task terminal | 0 | visual | 6/6 Confirmed | 5 | — | — |
| 141 | [#298203](https://github.com/microsoft/vscode/issues/298203) | "before all" hook in "Terminal" smoke test flaky | 0 | papercut | 3/6 Plausible | 5 | — | — |
| 145 | [#192689](https://github.com/microsoft/vscode/issues/192689) | {sequence} in terminal title doesn't result in same title as in other terminals | 2 | correctness | 2/6 Unverified | 4 | — | — |
| 146 | [#182979](https://github.com/microsoft/vscode/issues/182979) | Terminal panel overwrites `terminalEditorActive` context key when a terminal editor is present | 1 | correctness | 2/6 Unverified | 4 | — | — |
| 148 | [#312970](https://github.com/microsoft/vscode/issues/312970) | terminal progress display overflow | 1 | visual | 5/6 Source-confirmed | 4 | — | — |
| 172 | [#327279](https://github.com/microsoft/vscode/issues/327279) | Terminal tab actions become unresponsive during frequent OSC title updates | 0 | papercut | 5/6 Source-confirmed | 4 | — | — |
| 190 | [#305551](https://github.com/microsoft/vscode/issues/305551) | rerun action icon disappear after use it once time | 0 | papercut | 3/6 Plausible | 3 | — | — |
| 191 | [#305990](https://github.com/microsoft/vscode/issues/305990) | Terminal in editor area prevents new tabs from opening in the expected editor group | 0 | papercut | 4/6 Traced | 3 | — | — |
| 194 | [#317672](https://github.com/microsoft/vscode/issues/317672) | Bash terminal skips first character of input | 0 | papercut | 3/6 Plausible | 3 | — | — |
| 196 | [#122650](https://github.com/microsoft/vscode/issues/122650) | When touching the button on touch screan, The terminal pannel show new terminal with flashing drop-down menu . | 0 | visual | 3/6 Plausible | 2 | — | — |
| 210 | [#316597](https://github.com/microsoft/vscode/issues/316597) | Terminal name overflows. | 0 | visual | 5/6 Source-confirmed | 2 | — | — |
| 214 | [#319200](https://github.com/microsoft/vscode/issues/319200) | Restored terminal in editor area sometimes uses working directory from another workspace | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 241 | [#232488](https://github.com/microsoft/vscode/issues/232488) | Hovering warning icon in terminal tab is difficult to action | 0 | papercut | 5/6 Source-confirmed | 1 | — | — |
| 244 | [#252464](https://github.com/microsoft/vscode/issues/252464) | UI glitch when terminal is in secondary sidebar and env variables overridden | 0 | visual | 3/6 Plausible | 1 | — | — |
| 247 | [#299380](https://github.com/microsoft/vscode/issues/299380) | Unable to space / backspace in Factory - Droid terminal | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 250 | [#306544](https://github.com/microsoft/vscode/issues/306544) | Focus Terminal does not fully render sudo password prompt text | 0 | visual | — | 1 | — | — |
| 254 | [#311557](https://github.com/microsoft/vscode/issues/311557) | [Error] potential listener LEAK — terminal/decorationAddon | 0 | perf | 5/6 Source-confirmed | 1 | yes | — |
| 256 | [#314066](https://github.com/microsoft/vscode/issues/314066) | Terminal death recovery doesn't work | 0 | correctness | 6/6 Confirmed | 1 | — | — |
| 259 | [#318254](https://github.com/microsoft/vscode/issues/318254) | OSC52 unsupported in `code serve-web` | 0 | correctness | 5/6 Source-confirmed | 1 | — | — |
| 274 | [#191369](https://github.com/microsoft/vscode/issues/191369) | Terminal title on Windows may not change when switched shortly after creating | 0 | papercut | 4/6 Traced | 0 | — | — |
| 293 | [#295159](https://github.com/microsoft/vscode/issues/295159) | Splitting a terminal window will open the terminal in the main workbench window, not the terminal window | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 303 | [#305733](https://github.com/microsoft/vscode/issues/305733) | VS Code hangs when running recursive grep with ERE pattern in integrated terminal on macOS | 0 | freeze | 3/6 Plausible | 0 | — | — |
| 310 | [#310738](https://github.com/microsoft/vscode/issues/310738) | Terminal Session Initialization Race Condition | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 317 | [#314204](https://github.com/microsoft/vscode/issues/314204) | Extra height when terminal prompts for input | 0 | visual | 3/6 Plausible | 0 | — | — |
| 322 | [#317081](https://github.com/microsoft/vscode/issues/317081) | gh auth login - doesn't show Focus Terminal | 0 | papercut | 5/6 Source-confirmed | 0 | — | — |
| 325 | [#318853](https://github.com/microsoft/vscode/issues/318853) | I can't see the terminal | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 337 | [#327517](https://github.com/microsoft/vscode/issues/327517) | Text inside tooltip is cut off | 0 | visual | 5/6 Source-confirmed | 0 | — | — |

### Problem matching (17)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 11 | [#150285](https://github.com/microsoft/vscode/issues/150285) | `$msCompile` problem matcher has issues with wrapped lines | 8 | correctness | 4/6 Traced | 29 | — | — |
| 29 | [#295523](https://github.com/microsoft/vscode/issues/295523) | Unresponsive window with problem matcher errors | 0 | freeze | 6/6 Confirmed | 18 | — | — |
| 30 | [#194501](https://github.com/microsoft/vscode/issues/194501) | Problem matcher only matches on restored PTY | 1 | correctness | 6/6 Confirmed | 17 | — | — |
| 65 | [#149912](https://github.com/microsoft/vscode/issues/149912) | applyTo: closedDocuments and a custom owner caused errors to leak/persist | 0 | correctness | 5/6 Source-confirmed | 11 | yes | — |
| 66 | [#240869](https://github.com/microsoft/vscode/issues/240869) | Terminal output wrapping breaks ProblemMatcher matching. | 0 | correctness | 5/6 Source-confirmed | 11 | — | — |
| 81 | [#149673](https://github.com/microsoft/vscode/issues/149673) | The "$tsc-webpack-watch" from "amodio.tsl-problem-matcher" problem matcher does match, but doesn't mark the task as failed | 0 | correctness | 5/6 Source-confirmed | 9 | — | — |
| 82 | [#157096](https://github.com/microsoft/vscode/issues/157096) | problemMatcher with multiple patterns doesn't work | 0 | correctness | 5/6 Source-confirmed | 9 | — | — |
| 87 | [#183262](https://github.com/microsoft/vscode/issues/183262) | Multiline problem-matcher with empty line breaks when re-run in same terminal | 4 | correctness | 4/6 Traced | 8 | — | — |
| 89 | [#119824](https://github.com/microsoft/vscode/issues/119824) | Problems from main vscode build or extensions build can be shown, not both when a file is closed | 2 | correctness | 4/6 Traced | 8 | — | — |
| 225 | [#156720](https://github.com/microsoft/vscode/issues/156720) | Wrong Path of Files Listed Under "Problems" Tab | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 228 | [#174008](https://github.com/microsoft/vscode/issues/174008) | Task problemMatcher with fileLocation method set to "search" only seems to work for background task | 0 | correctness | 5/6 Source-confirmed | 1 | yes | — |
| 232 | [#179361](https://github.com/microsoft/vscode/issues/179361) | Background task problem matcher does not show all problems | 0 | correctness | 5/6 Source-confirmed | 1 | yes | — |
| 239 | [#228742](https://github.com/microsoft/vscode/issues/228742) | 'search' option in fileLocation of problemMatcher for Task does not work in Remote Development | 0 | correctness | 5/6 Source-confirmed | 1 | yes | — |
| 266 | [#149137](https://github.com/microsoft/vscode/issues/149137) | Problem matcher network path bug | 0 | correctness | 4/6 Traced | 0 | — | — |
| 270 | [#175097](https://github.com/microsoft/vscode/issues/175097) | Task beginsPattern does not work | 0 | correctness | 4/6 Traced | 0 | — | — |
| 271 | [#184523](https://github.com/microsoft/vscode/issues/184523) | Problems are not always generated when running tasks | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 333 | [#326083](https://github.com/microsoft/vscode/issues/326083) | Task problem matching inconsistency across task runs? | 0 | correctness | 3/6 Plausible | 0 | — | — |

### Accessibility and speech (63)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 14 | [#147190](https://github.com/microsoft/vscode/issues/147190) | [Accessibility] Audio Cues doesn't work in web editor | 0 | correctness | 2/6 Unverified | 27 | — | — |
| 28 | [#245146](https://github.com/microsoft/vscode/issues/245146) | Misalignment between VoiceOver focus and Keyboard focus in VS Code | 0 | correctness | 6/6 Confirmed | 18 | — | — |
| 39 | [#292277](https://github.com/microsoft/vscode/issues/292277) | Content mismatch between Chat view and Accessible View (Alt+F2) with HTML and special characters:A11y_Visual Studio Code_Editor_Infor and relationship | 0 | correctness | 3/6 Plausible | 15 | — | — |
| 79 | [#189784](https://github.com/microsoft/vscode/issues/189784) | [Accessibility] problems.decorations.enabled setting must equally benefit screen reader users | 1 | correctness | 5/6 Source-confirmed | 9 | yes | — |
| 86 | [#303918](https://github.com/microsoft/vscode/issues/303918) | Speech to text unexpectedly undoes user edits in chat sidebar | 0 | correctness | 5/6 Source-confirmed | 9 | — | — |
| 92 | [#241055](https://github.com/microsoft/vscode/issues/241055) | Accessibility MacOS: Pressing a routing button over a character in editor does not move the cursor | 0 | correctness | 3/6 Plausible | 8 | — | — |
| 97 | [#303602](https://github.com/microsoft/vscode/issues/303602) | Duplicated condition in accessibility signal property change detection - lastValueOnLine never checked | 0 | correctness | 5/6 Source-confirmed | 8 | — | — |
| 98 | [#304396](https://github.com/microsoft/vscode/issues/304396) | Accessible editor does not announce initial value unless focused | 0 | correctness | 5/6 Source-confirmed | 8 | yes | — |
| 103 | [#192706](https://github.com/microsoft/vscode/issues/192706) | Large contents in Editor causes VoiceOver to lag significantly while typing | 0 | perf | 3/6 Plausible | 7 | — | — |
| 108 | [#291274](https://github.com/microsoft/vscode/issues/291274) | Screen reader continuously announces terminal timing output when Copilot runs a build-like command in VS Code:A11y_Visuual studio code_Screen reader | 0 | correctness | 5/6 Source-confirmed | 7 | — | — |
| 111 | [#305969](https://github.com/microsoft/vscode/issues/305969) | Go to Repeating Prompt with Each Character Typed When Using a Screen Reader | 2 | papercut | 5/6 Source-confirmed | 6 | yes | — |
| 144 | [#250060](https://github.com/microsoft/vscode/issues/250060) | Accessibility: Monaco Editor Progress Bar Violates "4.1.2 Name, Role, Value" Requirement | 4 | papercut | 2/6 Unverified | 4 | — | — |
| 147 | [#307703](https://github.com/microsoft/vscode/issues/307703) | Settings view Shift+Tab jumps focus back to editor unexpectedly | 1 | papercut | 6/6 Confirmed | 4 | — | — |
| 157 | [#237085](https://github.com/microsoft/vscode/issues/237085) | [Accessibility, Mouse]: When navigating with the mouse, the content in the editor is not reported to the screen reader. | 0 | correctness | — | 4 | — | — |
| 158 | [#239362](https://github.com/microsoft/vscode/issues/239362) | [Accessibility] Cannot read multi diff content in Source Control Graph View | 0 | correctness | 5/6 Source-confirmed | 4 | yes | — |
| 166 | [#298061](https://github.com/microsoft/vscode/issues/298061) | Go to Line/Column - no line number in edit box | 0 | papercut | 3/6 Plausible | 4 | — | — |
| 167 | [#298064](https://github.com/microsoft/vscode/issues/298064) | Edit in accessible view sometimes opens too small | 0 | visual | 3/6 Plausible | 4 | — | — |
| 169 | [#314779](https://github.com/microsoft/vscode/issues/314779) | Customizations list: Tab into list does not visibly focus first entry | 0 | papercut | 2/6 Unverified | 4 | — | — |
| 174 | [#192090](https://github.com/microsoft/vscode/issues/192090) | alt+f2 does not open the terminal accessible view on linux | 1 | papercut | 2/6 Unverified | 3 | — | — |
| 179 | [#196854](https://github.com/microsoft/vscode/issues/196854) | [Accessibility] word-by-word keyboard navigation does not work in Output View | 0 | correctness | 2/6 Unverified | 3 | — | — |
| 182 | [#237087](https://github.com/microsoft/vscode/issues/237087) | [Accessibility, Mouse]: When using the mouse to navigate a menu, the content behind the menu is reported to the screen reader. | 0 | papercut | 3/6 Plausible | 3 | — | — |
| 187 | [#280911](https://github.com/microsoft/vscode/issues/280911) | Command Palette closes unexpectedly with VoiceOver enabled on VS Code Web | 0 | correctness | 5/6 Source-confirmed | 3 | yes | — |
| 197 | [#145109](https://github.com/microsoft/vscode/issues/145109) | orca talking excessively when triggering problem view. | 0 | papercut | 3/6 Plausible | 2 | — | — |
| 200 | [#181798](https://github.com/microsoft/vscode/issues/181798) | punctuation echo issues under MacOS | 0 | papercut | 3/6 Plausible | 2 | — | — |
| 201 | [#198612](https://github.com/microsoft/vscode/issues/198612) | Code cannot be read and edited using a screen reader in Android web version of VS code. | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 205 | [#296612](https://github.com/microsoft/vscode/issues/296612) | `editor.action.accessibilityHelpConfigureKeybindings` no longer works from Accessibility Help with Alt+K | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 209 | [#316415](https://github.com/microsoft/vscode/issues/316415) | ARIA attributes "aria-label" are not valid for the element <body> with implicit ARIA role "generic" violates WCAG 2.1 SC 4.1.2 Name, Role, Value (Level A) | 0 | papercut | 4/6 Traced | 2 | yes | — |
| 216 | [#320381](https://github.com/microsoft/vscode/issues/320381) | Keyboard navigation is blocked between “Resources” expandable control and “Views and more actions” using VO navigation (Ctrl+Option keys):A11y_VS code_VoiceOver | 0 | papercut | 3/6 Plausible | 2 | — | — |
| 219 | [#175282](https://github.com/microsoft/vscode/issues/175282) | [Accessibility] Do not use title attribute when labeling buttons | 1 | papercut | 2/6 Unverified | 1 | — | — |
| 220 | [#204300](https://github.com/microsoft/vscode/issues/204300) | [Accessibility] Copilot generated commit message is not read aloud | 1 | papercut | 5/6 Source-confirmed | 1 | yes | — |
| 221 | [#211684](https://github.com/microsoft/vscode/issues/211684) | Accessibility: "Show All Symbols" command doesn't speak file names and paths | 1 | papercut | 5/6 Source-confirmed | 1 | yes | — |
| 224 | [#105559](https://github.com/microsoft/vscode/issues/105559) | Windows Magnifier not following active menuitem | 0 | papercut | 3/6 Plausible | 1 | — | — |
| 231 | [#178674](https://github.com/microsoft/vscode/issues/178674) | narrator and NVDA does not report process manager list item names in Visual Studio Code | 0 | correctness | 2/6 Unverified | 1 | — | — |
| 233 | [#180793](https://github.com/microsoft/vscode/issues/180793) | VS Code: on using the keys control + right/left keys and moving to next line the information of moving to next line is not read | 0 | papercut | 3/6 Plausible | 1 | — | — |
| 235 | [#201999](https://github.com/microsoft/vscode/issues/201999) | The extensions list should have the ARIA listbox role; not the list role | 0 | papercut | 5/6 Source-confirmed | 1 | yes | — |
| 236 | [#211082](https://github.com/microsoft/vscode/issues/211082) | Accessible view: pressing the "Menu" key breaks all context menus and accessible view | 0 | correctness | 5/6 Source-confirmed | 1 | yes | — |
| 238 | [#228599](https://github.com/microsoft/vscode/issues/228599) | Consider how we might improve navigation to chat response content for screen reader users | 0 | papercut | — | 1 | — | — |
| 240 | [#229478](https://github.com/microsoft/vscode/issues/229478) | Screen reader is not announcing control name present in top menu navigation and left navigation on hovering with mouse in mouse tracking on mode:A11y_Visual Studio Code Client_Home screen_ScreenReader | 0 | papercut | 3/6 Plausible | 1 | — | — |
| 242 | [#237136](https://github.com/microsoft/vscode/issues/237136) | {Linked:Bug9528439} NVDA/JAWS is not announcing the state expand/collapse for the pick model button: A11y_VS Code_Copilot Chat_Screen Reader | 0 | papercut | 2/6 Unverified | 1 | — | — |
| 243 | [#248606](https://github.com/microsoft/vscode/issues/248606) | Screen reader repeats last word twice at end of line and on empty lines with Ctrl+Arrow | 0 | correctness | 4/6 Traced | 1 | — | — |
| 251 | [#307696](https://github.com/microsoft/vscode/issues/307696) | User confirmation feedback audio is sometimes not heard in terminal | 0 | papercut | 4/6 Traced | 1 | — | — |
| 252 | [#309620](https://github.com/microsoft/vscode/issues/309620) | Agents: initial session list focus shows no indication | 0 | visual | 2/6 Unverified | 1 | — | — |
| 257 | [#314777](https://github.com/microsoft/vscode/issues/314777) | Accessibility: Notification Dialogue with toolbar violates  WCAG 4.1.2 Name , Role, Value  "SC 4.1.2 Name, Role, Value (Level A)" | 0 | papercut | 5/6 Source-confirmed | 1 | yes | — |
| 261 | [#321616](https://github.com/microsoft/vscode/issues/321616) | Accessibility: Built-in VSCode webviews fails for Name, Role, Value (Level A) SC 4.1.2 (WCAG 2.2) | 0 | none | 3/6 Plausible | 1 | — | — |
| 263 | [#321656](https://github.com/microsoft/vscode/issues/321656) | Accessibility: Built-in VSCode webviews  fails with WCAG 2.1 SC 2.4.2 Page Titled (Level A) - Missing <title> element in <head> element | 0 | papercut | 4/6 Traced | 1 | yes | — |
| 276 | [#210062](https://github.com/microsoft/vscode/issues/210062) | #accessibility in Github Copilot chat: Screenreader announces all copilot's path references and links as URL encoded file paths | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 278 | [#223405](https://github.com/microsoft/vscode/issues/223405) | Only one changed variable gets announced by screen reader | 0 | papercut | 5/6 Source-confirmed | 0 | yes | — |
| 279 | [#227484](https://github.com/microsoft/vscode/issues/227484) | Custom controls need to provide proper textual name, role, and state information | 0 | papercut | 5/6 Source-confirmed | 0 | — | — |
| 280 | [#227508](https://github.com/microsoft/vscode/issues/227508) | Tooltips Missing Name and Role Information | 0 | papercut | 4/6 Traced | 0 | yes | — |
| 285 | [#256761](https://github.com/microsoft/vscode/issues/256761) | Install button should be first tab stop on extension page | 0 | papercut | 5/6 Source-confirmed | 0 | yes | — |
| 288 | [#269609](https://github.com/microsoft/vscode/issues/269609) | Terminal dictation while typing overlaps text | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 289 | [#284843](https://github.com/microsoft/vscode/issues/284843) | {Linked:Bug9576466}There is no feedback message is provided after clicking on copy button: A11y_VSCode_Usability. | 0 | papercut | 2/6 Unverified | 0 | — | — |
| 307 | [#307704](https://github.com/microsoft/vscode/issues/307704) | Cannot navigate to full list of deprecated extensions via Tab key | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 309 | [#309621](https://github.com/microsoft/vscode/issues/309621) | Find session flow is really not accessible | 0 | papercut | 5/6 Source-confirmed | 0 | — | — |
| 316 | [#314168](https://github.com/microsoft/vscode/issues/314168) | Agents app modals have unexpected tab behavior in MacOS | 0 | papercut | 5/6 Source-confirmed | 0 | — | — |
| 323 | [#318700](https://github.com/microsoft/vscode/issues/318700) | Focus is lost after interacting with "Auto Update" checkbox using keyboard:A11y_VisualStudioCode_Extensions_Keyboard | 0 | papercut | 5/6 Source-confirmed | 0 | yes | — |
| 324 | [#318719](https://github.com/microsoft/vscode/issues/318719) | The Expand/Collapse control does not respond to a single number voice command:A11y_VisualStudioCode_Usable | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 328 | [#321143](https://github.com/microsoft/vscode/issues/321143) | Smoke Test Failure: sidebar has no accessibility violations | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 329 | [#321958](https://github.com/microsoft/vscode/issues/321958) | Accessibility: Child items/dropdown menu items inside a view fails for  WCAG 2.2 , SC 4.1.2 Name, Role, Value (Level A) | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 331 | [#324732](https://github.com/microsoft/vscode/issues/324732) | Menu items in Explore section are missing indexing information for screen reader users:A11y_Visual Studio Code Client_Editor_Screen Reader | 0 | papercut | 4/6 Traced | 0 | yes | — |
| 334 | [#326546](https://github.com/microsoft/vscode/issues/326546) | NVDA Stops Reading After Opening a File or Folder from Within VSCode, or Closing the Dialog | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 335 | [#326572](https://github.com/microsoft/vscode/issues/326572) | VS Code Speech cannot stop playback for long GitHub Copilot Chat responses | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 338 | [#328541](https://github.com/microsoft/vscode/issues/328541) | Chat continuous listening stops accepting speech after first segment when text is edited (macOS) | 0 | correctness | 3/6 Plausible | 0 | — | — |

### Shell profiles and environment (14)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 32 | [#233618](https://github.com/microsoft/vscode/issues/233618) | VSCode trying to update WSL on launch for literally no reason | 10 | papercut | 5/6 Source-confirmed | 15 | yes | — |
| 61 | [#172099](https://github.com/microsoft/vscode/issues/172099) | Variables `relativeFile` and `relativeFileDirname` use backslashes in WSL when used in keyboard shortcuts | 3 | correctness | 5/6 Source-confirmed | 11 | — | — |
| 94 | [#285428](https://github.com/microsoft/vscode/issues/285428) | Opening new terminals in the editor area seemingly cannot figure out ${fileDirname} | 0 | correctness | 5/6 Source-confirmed | 8 | yes | — |
| 101 | [#230160](https://github.com/microsoft/vscode/issues/230160) | [macOS] Custom terminal not found on first launch | 1 | correctness | 4/6 Traced | 7 | — | — |
| 104 | [#195768](https://github.com/microsoft/vscode/issues/195768) | Terminal profile default discovery isn't working as expected | 0 | correctness | 5/6 Source-confirmed | 7 | yes | — |
| 162 | [#286974](https://github.com/microsoft/vscode/issues/286974) | Terminal tabs description/title using cwdFolder shows folder incorrectly in WSL | 0 | visual | 5/6 Source-confirmed | 4 | yes | — |
| 171 | [#326670](https://github.com/microsoft/vscode/issues/326670) | "getWslProfiles" blocks main thread via synchronous "CreateProcessW" | 0 | perf | 4/6 Traced | 4 | — | — |
| 180 | [#214547](https://github.com/microsoft/vscode/issues/214547) | Windows: WSL prompt option only shows in terminal add menu if you add another terminal | 0 | papercut | 4/6 Traced | 3 | yes | — |
| 181 | [#224749](https://github.com/microsoft/vscode/issues/224749) | It's not possible to set any Terminal Profile | 0 | papercut | 5/6 Source-confirmed | 3 | yes | — |
| 227 | [#160336](https://github.com/microsoft/vscode/issues/160336) | Connecting via code-server shows the cwd in the terminal tab incorrectly | 0 | visual | 4/6 Traced | 1 | yes | — |
| 255 | [#312745](https://github.com/microsoft/vscode/issues/312745) | VSCode ignores "chat.tools.terminal.terminalProfile.windows" setting initially | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 273 | [#188312](https://github.com/microsoft/vscode/issues/188312) | Terminal tab home CWD is not handled correctly in remote workspaces | 0 | visual | 5/6 Source-confirmed | 0 | yes | — |
| 281 | [#233884](https://github.com/microsoft/vscode/issues/233884) | Vscode doesn't respect the login shell on MacOS | 0 | correctness | 4/6 Traced | 0 | yes | — |
| 321 | [#317007](https://github.com/microsoft/vscode/issues/317007) | [Bug] Incomplete Sanitization in terminalProfileQuickpick.ts: Args Without Spaces Bypass All Sanitization in Profile Description | 0 | papercut | 5/6 Source-confirmed | 0 | — | — |

### Debugging and editor focus (8)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 46 | [#291642](https://github.com/microsoft/vscode/issues/291642) | Debug disassembly view infinite scrolling does not work after navigating to second frame | 0 | correctness | 5/6 Source-confirmed | 14 | — | — |
| 57 | [#175202](https://github.com/microsoft/vscode/issues/175202) | Debug with f5 never starts and caused extraneous extension activation | 3 | correctness | 5/6 Source-confirmed | 12 | — | — |
| 84 | [#225613](https://github.com/microsoft/vscode/issues/225613) | `cursorTop` and `cursorBottom` (Command+UP/DOWN) occasionally stop working in source editors | 0 | correctness | 6/6 Confirmed | 9 | — | — |
| 88 | [#200259](https://github.com/microsoft/vscode/issues/200259) | Widget navigation steals editor focus | 4 | papercut | 3/6 Plausible | 8 | — | — |
| 93 | [#258698](https://github.com/microsoft/vscode/issues/258698) | Did not add a launch.json with debug config. | 0 | correctness | 6/6 Confirmed | 8 | — | — |
| 153 | [#169166](https://github.com/microsoft/vscode/issues/169166) | Multi-Process Debugger isn't working on VSC 1.74 | 0 | correctness | 5/6 Source-confirmed | 4 | — | — |
| 195 | [#204391](https://github.com/microsoft/vscode/issues/204391) | Debug Console filter with Go is difficult to use and inaccurate | 2 | papercut | 3/6 Plausible | 2 | — | — |
| 217 | [#322732](https://github.com/microsoft/vscode/issues/322732) | Cannot copy selected log fragment from Debug Console on macOS | 0 | papercut | 5/6 Source-confirmed | 2 | yes | — |

## Feature requests

### Task configuration (21)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 2 | [#36769](https://github.com/microsoft/vscode/issues/36769) | Support envfile for tasks.json | 154 | backlog-candidate | 32 | — |
| 4 | [#27157](https://github.com/microsoft/vscode/issues/27157) | PreLaunchTask: support passing parameters from configuration to preLaunchTask | 94 | backlog-candidate | 19 | — |
| 5 | [#309447](https://github.com/microsoft/vscode/issues/309447) | Feature Request: Allow `task.allowAutomaticTasks` to be set at the workspace level | 31 | backlog-candidate | 17 | — |
| 10 | [#289870](https://github.com/microsoft/vscode/issues/289870) | Support an envFromInput field in launch.json | 23 | backlog-candidate | 12 | — |
| 11 | [#251006](https://github.com/microsoft/vscode/issues/251006) | Feature Request:  tasks get inputs from nodejs or shell | 28 | backlog-candidate | 11 | — |
| 20 | [#285427](https://github.com/microsoft/vscode/issues/285427) | Reference folder task in multi-root workspace | 22 | backlog-candidate | 8 | — |
| 30 | [#171837](https://github.com/microsoft/vscode/issues/171837) | Add prelaunch Command as well for launch configuration | 21 | backlog-candidate | 6 | — |
| 31 | [#132767](https://github.com/microsoft/vscode/issues/132767) | Support `dependsOn` programmatically in the vscode.Task API | 31 | backlog-candidate | 5 | — |
| 32 | [#71461](https://github.com/microsoft/vscode/issues/71461) | Task input parameters from showOpenDialog | 22 | backlog-candidate | 5 | — |
| 36 | [#99276](https://github.com/microsoft/vscode/issues/99276) | Tasks: Pick folder for user tasks in multi-root-workspaces | 30 | dormant | 4 | — |
| 45 | [#309661](https://github.com/microsoft/vscode/issues/309661) | YAML support for VSCode tasks | 10 | active | 3 | — |
| 46 | [#139937](https://github.com/microsoft/vscode/issues/139937) | Add arguments property to npm tasks | 8 | backlog-candidate | 3 | — |
| 51 | [#73748](https://github.com/microsoft/vscode/issues/73748) | Be able disable task detection from tasks.json or override tasks execution | 12 | dormant | 2 | — |
| 72 | [#68397](https://github.com/microsoft/vscode/issues/68397) | More flexible input variables: Multiple values & labels | 8 | backlog-candidate | 1 | — |
| 75 | [#76415](https://github.com/microsoft/vscode/issues/76415) | Allow for configuration files in .devcontainer | 3 | backlog-candidate | 1 | — |
| 85 | [#73840](https://github.com/microsoft/vscode/issues/73840) | New revealProblems property in task presentation options is missing from the API | 1 | backlog-candidate | 1 | — |
| 118 | [#246159](https://github.com/microsoft/vscode/issues/246159) | Unify variable substitution features in tasks, mcp, and debug | 0 | backlog-candidate | 1 | — |
| 141 | [#306748](https://github.com/microsoft/vscode/issues/306748) | Feature Request: Prompt inputs for all dependent tasks at launch | 0 | active | 1 | — |
| 150 | [#83021](https://github.com/microsoft/vscode/issues/83021) | OS specific properties in Tasks.json to overwrite build shell doen't work | 0 | dormant | 0 | — |
| 151 | [#93149](https://github.com/microsoft/vscode/issues/93149) | Make extension defined task types work in code-workspace files | 0 | backlog-candidate | 0 | — |
| 185 | [#276044](https://github.com/microsoft/vscode/issues/276044) | Tasks misses basic editor support | 0 | dormant | 0 | — |

### Terminal management (26)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 3 | [#252647](https://github.com/microsoft/vscode/issues/252647) | Integrated terminal tabs on the top or bottom | 44 | backlog-candidate | 26 | — |
| 13 | [#266038](https://github.com/microsoft/vscode/issues/266038) | requesting terminal icon and terminal color control via launch.json | 23 | backlog-candidate | 10 | — |
| 19 | [#140261](https://github.com/microsoft/vscode/issues/140261) | terminal.integrated.defaultProfile and terminal.integrated.automationProfile behaves differently | 28 | backlog-candidate | 8 | — |
| 23 | [#237004](https://github.com/microsoft/vscode/issues/237004) | terminal title supports branch variable | 20 | backlog-candidate | 7 | — |
| 24 | [#323231](https://github.com/microsoft/vscode/issues/323231) | Let extensions change a terminal tab's icon and color after it is created | 9 | backlog-candidate | 7 | — |
| 27 | [#165040](https://github.com/microsoft/vscode/issues/165040) | Set profile to have custom number of terminals at the same time by default | 24 | backlog-candidate | 6 | — |
| 33 | [#150938](https://github.com/microsoft/vscode/issues/150938) | Add nvm support | 18 | backlog-candidate | 5 | — |
| 58 | [#151284](https://github.com/microsoft/vscode/issues/151284) | Dragging terminals tabs should group and ungroup them | 4 | active | 2 | — |
| 60 | [#162950](https://github.com/microsoft/vscode/issues/162950) | Terminal quick fix API | 2 | backlog-candidate | 2 | — |
| 63 | [#251105](https://github.com/microsoft/vscode/issues/251105) | Select Default Profile (terminal) doesn't work for projects with terminal specified | 1 | active | 2 | — |
| 73 | [#183354](https://github.com/microsoft/vscode/issues/183354) | Support `when` clause for `terminal.profiles` contribution point | 5 | backlog-candidate | 1 | — |
| 81 | [#187853](https://github.com/microsoft/vscode/issues/187853) | Truncate long terminal command lines by default | 2 | backlog-candidate | 1 | — |
| 82 | [#292816](https://github.com/microsoft/vscode/issues/292816) | integrated Terminal on vscode that supports kitty protocol so I can use ctrl+enter shortcut on kiro cli without sending prompt | 2 | active | 1 | — |
| 84 | [#317917](https://github.com/microsoft/vscode/issues/317917) | Add setting to suppress terminal context menu when mouse reporting is active | 2 | backlog-candidate | 1 | — |
| 89 | [#214242](https://github.com/microsoft/vscode/issues/214242) | Add context menu item to relaunch terminals with extra environment info | 1 | backlog-candidate | 1 | — |
| 99 | [#326909](https://github.com/microsoft/vscode/issues/326909) | Allow grouping terminal profiles into nested submenus | 1 | backlog-candidate | 1 | — |
| 105 | [#194149](https://github.com/microsoft/vscode/issues/194149) | Make terminal tab toolbar configurable | 0 | backlog-candidate | 1 | — |
| 107 | [#232657](https://github.com/microsoft/vscode/issues/232657) | Explore terminal quick fixes based on selection | 0 | backlog-candidate | 1 | — |
| 108 | [#233354](https://github.com/microsoft/vscode/issues/233354) | Support file icons similar to treeview item icon path in terminal icon path | 0 | backlog-candidate | 1 | — |
| 158 | [#173134](https://github.com/microsoft/vscode/issues/173134) | Support command variables in a terminal profile's env property | 0 | backlog-candidate | 0 | — |
| 165 | [#199449](https://github.com/microsoft/vscode/issues/199449) | Allow cwd to be implicitly determined for terminal commit message quickfix | 0 | dormant | 0 | — |
| 189 | [#286741](https://github.com/microsoft/vscode/issues/286741) | Add xonsh shell profile discovery | 0 | active | 0 | — |
| 191 | [#290834](https://github.com/microsoft/vscode/issues/290834) | Explore associating recognized shells with an icon that changes | 0 | active | 0 | — |
| 204 | [#315252](https://github.com/microsoft/vscode/issues/315252) | Clear Terminal "before that line" | 0 | active | 0 | — |
| 208 | [#323243](https://github.com/microsoft/vscode/issues/323243) | Allow extensions to create terminals adjacent to a parent terminal without splitting | 0 | backlog-candidate | 0 | — |
| 209 | [#324422](https://github.com/microsoft/vscode/issues/324422) | Pseudoterminal plugins do not have a way to get the users cwd picked in a multi-root workspace | 0 | backlog-candidate | 0 | — |

### Task execution (19)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 6 | [#6209](https://github.com/microsoft/vscode/issues/6209) | isWatching/background task as preLaunchTask in launch.json | 61 | dormant | 15 | — |
| 14 | [#28235](https://github.com/microsoft/vscode/issues/28235) | Provide Task Runner viewlet | 37 | dormant | 9 | — |
| 15 | [#70283](https://github.com/microsoft/vscode/issues/70283) | errors in dependsOn background tasks do not prevent subsequent tasks from executing | 35 | dormant | 9 | — |
| 16 | [#119868](https://github.com/microsoft/vscode/issues/119868) | Npm Scripts view not available if package.json located only in nested folder | 32 | backlog-candidate | 9 | — |
| 25 | [#47265](https://github.com/microsoft/vscode/issues/47265) | Launch task directly into split terminal | 30 | backlog-candidate | 6 | — |
| 26 | [#87845](https://github.com/microsoft/vscode/issues/87845) | Improve task debugging by giving more context | 28 | backlog-candidate | 6 | — |
| 37 | [#184047](https://github.com/microsoft/vscode/issues/184047) | Display disabled tasks in Run Build Task... menu | 20 | backlog-candidate | 4 | — |
| 44 | [#167283](https://github.com/microsoft/vscode/issues/167283) | Expose User tasks and all task commands in vscode Web | 20 | backlog-candidate | 3 | — |
| 52 | [#153903](https://github.com/microsoft/vscode/issues/153903) | Automatically Run task does not wait for postCreateCommand in a Dev Container | 10 | backlog-candidate | 2 | — |
| 54 | [#70118](https://github.com/microsoft/vscode/issues/70118) | default run task | 8 | dormant | 2 | — |
| 76 | [#299227](https://github.com/microsoft/vscode/issues/299227) | Make npm scripts panel order consider directory depth | 3 | active | 1 | — |
| 78 | [#68767](https://github.com/microsoft/vscode/issues/68767) | Restart task fails if task already completed | 2 | dormant | 1 | — |
| 101 | [#40515](https://github.com/microsoft/vscode/issues/40515) | Tasks with target = TaskScope.Global as the scope do not show up in task picker UI | 0 | dormant | 1 | — |
| 104 | [#174579](https://github.com/microsoft/vscode/issues/174579) | Background Task With No Output Never Completes | 0 | dormant | 1 | — |
| 144 | [#92978](https://github.com/microsoft/vscode/issues/92978) | Report task execution result in onDidEndTask | 1 | backlog-candidate | 0 | — |
| 153 | [#144246](https://github.com/microsoft/vscode/issues/144246) | Indicate if Task Exited for both dependency tasks | 0 | backlog-candidate | 0 | — |
| 156 | [#157112](https://github.com/microsoft/vscode/issues/157112) | Add support for running custom tasks in VS Code Web | 0 | dormant | 0 | — |
| 180 | [#260659](https://github.com/microsoft/vscode/issues/260659) | Only provide task output from `beginsPattern` when possible | 0 | dormant | 0 | — |
| 181 | [#264387](https://github.com/microsoft/vscode/issues/264387) | Always runs 'compile' task in vscode-copilot-chat repo when other build tasks are running | 0 | dormant | 0 | — |

### Terminal suggestions (28)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 7 | [#285640](https://github.com/microsoft/vscode/issues/285640) | Terminal suggest doesn't get content from the actual terminal session. | 21 | backlog-candidate | 15 | — |
| 35 | [#224505](https://github.com/microsoft/vscode/issues/224505) | terminal completion provider extension API | 0 | active | 5 | — |
| 39 | [#240240](https://github.com/microsoft/vscode/issues/240240) | Terminal suggest: Support configuring fig specs | 4 | backlog-candidate | 4 | — |
| 40 | [#210983](https://github.com/microsoft/vscode/issues/210983) | Terminal suggest snippets | 3 | backlog-candidate | 4 | — |
| 62 | [#233232](https://github.com/microsoft/vscode/issues/233232) | Terminal suggest: Contextually aware suggestions after git status | 1 | backlog-candidate | 2 | — |
| 64 | [#282578](https://github.com/microsoft/vscode/issues/282578) | Tweak terminal suggest setting to be off by default for certain problematic configs | 1 | backlog-candidate | 2 | — |
| 90 | [#237981](https://github.com/microsoft/vscode/issues/237981) | Terminal suggest: Handle paths on git bash | 1 | dormant | 1 | — |
| 98 | [#324297](https://github.com/microsoft/vscode/issues/324297) | Search-based file-path autocomplete for the terminal | 1 | backlog-candidate | 1 | — |
| 110 | [#234353](https://github.com/microsoft/vscode/issues/234353) | Terminal suggest: Support resolving environment variables in directories | 0 | backlog-candidate | 1 | — |
| 111 | [#239019](https://github.com/microsoft/vscode/issues/239019) | arguments suggested for mkdir command seems to be invalid | 0 | backlog-candidate | 1 | — |
| 112 | [#239244](https://github.com/microsoft/vscode/issues/239244) | Explore showing history in the suggest widget | 0 | backlog-candidate | 1 | — |
| 113 | [#240088](https://github.com/microsoft/vscode/issues/240088) | Terminal suggest: Properly support paths with spaces in them | 0 | backlog-candidate | 1 | — |
| 114 | [#240236](https://github.com/microsoft/vscode/issues/240236) | Terminal suggest: Support resolving completion items and pull in pwsh command help | 0 | backlog-candidate | 1 | — |
| 115 | [#241975](https://github.com/microsoft/vscode/issues/241975) | Very large set of details in terminal suggestions for `Where-object` | 0 | dormant | 1 | — |
| 116 | [#241996](https://github.com/microsoft/vscode/issues/241996) | No terminal suggestions for quoted paths o | 0 | backlog-candidate | 1 | — |
| 119 | [#252001](https://github.com/microsoft/vscode/issues/252001) | Allow tasks to be run via terminal suggest | 0 | backlog-candidate | 1 | — |
| 123 | [#264752](https://github.com/microsoft/vscode/issues/264752) | Git commit suggestions in terminal aren't very useful without expansion | 0 | backlog-candidate | 1 | — |
| 124 | [#273582](https://github.com/microsoft/vscode/issues/273582) | Terminal suggest: Support path completions without the ./ | 0 | backlog-candidate | 1 | — |
| 133 | [#284820](https://github.com/microsoft/vscode/issues/284820) | Terminal suggest works with `docker-compose` but not `docker compose` | 0 | backlog-candidate | 1 | — |
| 173 | [#239155](https://github.com/microsoft/vscode/issues/239155) | terminal suggest: truncate beginning of long filepaths since they are all the same | 0 | backlog-candidate | 0 | — |
| 175 | [#241828](https://github.com/microsoft/vscode/issues/241828) | Accepting a completion should trigger suggest automatically | 0 | backlog-candidate | 0 | — |
| 176 | [#241960](https://github.com/microsoft/vscode/issues/241960) | The completions should show up if I use `sudo` | 0 | backlog-candidate | 0 | — |
| 177 | [#241968](https://github.com/microsoft/vscode/issues/241968) | `i` should be marked as an alias of `install` | 0 | backlog-candidate | 0 | — |
| 178 | [#241976](https://github.com/microsoft/vscode/issues/241976) | Support alternative suggest mode (insert/replace) for terminal suggestions | 0 | backlog-candidate | 0 | — |
| 182 | [#264747](https://github.com/microsoft/vscode/issues/264747) | Provide better suggestions for 'man' | 0 | dormant | 0 | — |
| 187 | [#283496](https://github.com/microsoft/vscode/issues/283496) | Better granularity/configuration options for the "Terminal integrated Suggest" feature | 0 | active | 0 | — |
| 188 | [#286440](https://github.com/microsoft/vscode/issues/286440) | Do not show selectionMode in terminal suggest toolbar when quick suggestions are disabled | 0 | backlog-candidate | 0 | — |
| 195 | [#296543](https://github.com/microsoft/vscode/issues/296543) | Smarter command line options UI (contextual options for tools like 'head' and 'python') | 0 | active | 0 | — |

### Problem matching (15)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 8 | [#61497](https://github.com/microsoft/vscode/issues/61497) | Task Manager: provide the ability to reuse custom problem matchers | 58 | backlog-candidate | 13 | — |
| 12 | [#205993](https://github.com/microsoft/vscode/issues/205993) | Support hyperlinks in problem matchers of task output | 34 | backlog-candidate | 10 | — |
| 18 | [#9635](https://github.com/microsoft/vscode/issues/9635) | Problem matchers for error messages that span multiple lines | 28 | backlog-candidate | 8 | — |
| 22 | [#59337](https://github.com/microsoft/vscode/issues/59337) | Extend tasks API to allow programmatic problem matching | 25 | dormant | 7 | — |
| 28 | [#77214](https://github.com/microsoft/vscode/issues/77214) | Have a command that clears all problems that are from tasks. | 23 | dormant | 6 | — |
| 50 | [#58980](https://github.com/microsoft/vscode/issues/58980) | Relative problem paths don't take `cwd` into account | 12 | backlog-candidate | 2 | — |
| 57 | [#164751](https://github.com/microsoft/vscode/issues/164751) | Please document how problem matcher problems are cleared | 6 | backlog-candidate | 2 | — |
| 59 | [#61140](https://github.com/microsoft/vscode/issues/61140) | Problem matchers should restore problems on close | 2 | dormant | 2 | — |
| 74 | [#55253](https://github.com/microsoft/vscode/issues/55253) | Problem matchers should support creating related diagnostic information | 4 | dormant | 1 | — |
| 77 | [#60851](https://github.com/microsoft/vscode/issues/60851) | Open next build error file+line based on regex parsing of build output. | 2 | backlog-candidate | 1 | — |
| 79 | [#73186](https://github.com/microsoft/vscode/issues/73186) | Regex pattern to clear all problems of a task owner | 2 | backlog-candidate | 1 | — |
| 143 | [#29562](https://github.com/microsoft/vscode/issues/29562) | Selection of problem matcher is not very intuitive when running a task | 3 | dormant | 0 | — |
| 145 | [#151962](https://github.com/microsoft/vscode/issues/151962) | Support SGR ANSI escape sequence in problem matcher messages | 1 | backlog-candidate | 0 | — |
| 154 | [#149175](https://github.com/microsoft/vscode/issues/149175) | Problems without column information are always shown as column 1,1 | 0 | dormant | 0 | — |
| 168 | [#210560](https://github.com/microsoft/vscode/issues/210560) | msCompile problem matcher does not match note: lines which are important for context | 0 | dormant | 0 | — |

### Agent terminal integration (34)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 9 | [#274550](https://github.com/microsoft/vscode/issues/274550) | Revisit terminal tool running background terminals UX | 18 | active | 13 | — |
| 38 | [#254429](https://github.com/microsoft/vscode/issues/254429) | Attach a terminal as context | 6 | backlog-candidate | 4 | — |
| 41 | [#261975](https://github.com/microsoft/vscode/issues/261975) | Terminals sessions should not be deleted when starting a new conversation | 2 | backlog-candidate | 4 | — |
| 42 | [#289657](https://github.com/microsoft/vscode/issues/289657) | GitHub Copilot Agent cannot execute commands in WSL/bash terminals - only PowerShell supported | 2 | active | 4 | — |
| 43 | [#290977](https://github.com/microsoft/vscode/issues/290977) | Easier way to clean up leftover terminals from chat sessions | 2 | backlog-candidate | 4 | — |
| 47 | [#288566](https://github.com/microsoft/vscode/issues/288566) | Allow agent to push a terminal into the background | 1 | active | 3 | — |
| 48 | [#291240](https://github.com/microsoft/vscode/issues/291240) | Chat terminal streaming - rendering suggestion | 0 | active | 3 | — |
| 66 | [#257673](https://github.com/microsoft/vscode/issues/257673) | Long bg commands or tasks without begins/ends patterns might be considered idle when they're not | 0 | backlog-candidate | 2 | — |
| 67 | [#275286](https://github.com/microsoft/vscode/issues/275286) | Provide way to go from terminal chat back to chat | 0 | backlog-candidate | 2 | — |
| 68 | [#282933](https://github.com/microsoft/vscode/issues/282933) | Agent confused by SSH key login prompt on command line | 0 | backlog-candidate | 2 | — |
| 69 | [#288567](https://github.com/microsoft/vscode/issues/288567) | Prompt tweaks around terminal isBackground description | 0 | active | 2 | — |
| 70 | [#288572](https://github.com/microsoft/vscode/issues/288572) | Explore a setting that launches all runInTerminal terminals in background | 0 | active | 2 | — |
| 92 | [#291175](https://github.com/microsoft/vscode/issues/291175) | Testing: Terminal part in subagent does not have scrollbar rendered | 1 | dormant | 1 | — |
| 96 | [#305725](https://github.com/microsoft/vscode/issues/305725) | auto-deny output to dev null | 1 | active | 1 | — |
| 121 | [#259562](https://github.com/microsoft/vscode/issues/259562) | Run in terminal: Leverage child process monitoring as hint for whether commands are done | 0 | backlog-candidate | 1 | — |
| 122 | [#263996](https://github.com/microsoft/vscode/issues/263996) | Merge the task tool into the terminal tool | 0 | active | 1 | — |
| 125 | [#274013](https://github.com/microsoft/vscode/issues/274013) | Check edits setting in CommandLineFileWriteAnalyzer | 0 | active | 1 | — |
| 126 | [#275036](https://github.com/microsoft/vscode/issues/275036) | Applying inline chat V2 styles to terminal | 0 | backlog-candidate | 1 | — |
| 127 | [#275220](https://github.com/microsoft/vscode/issues/275220) | Should terminal auto approve use the tool approval UI? | 0 | backlog-candidate | 1 | — |
| 128 | [#275352](https://github.com/microsoft/vscode/issues/275352) | Widget doesn't line break on words | 0 | dormant | 1 | — |
| 129 | [#275390](https://github.com/microsoft/vscode/issues/275390) | Make it easy to copy command output button in terminal tool output | 0 | backlog-candidate | 1 | — |
| 130 | [#276756](https://github.com/microsoft/vscode/issues/276756) | Explore removing most default false rules from terminal auto approve | 0 | active | 1 | — |
| 131 | [#282783](https://github.com/microsoft/vscode/issues/282783) | Terminal tool: Detect paths in command lines for common tools | 0 | backlog-candidate | 1 | — |
| 132 | [#284302](https://github.com/microsoft/vscode/issues/284302) | Allow MDM to prevent modifying list of allow/denied commands for chat auto-approval | 0 | active | 1 | — |
| 134 | [#287867](https://github.com/microsoft/vscode/issues/287867) | Support addressable terminal selections in chat | 0 | active | 1 | — |
| 135 | [#291111](https://github.com/microsoft/vscode/issues/291111) | Consider making the in-chat terminal header element sticky when scrolling super long code | 0 | backlog-candidate | 1 | — |
| 136 | [#291607](https://github.com/microsoft/vscode/issues/291607) | Add option to allow specific inline environment variables | 0 | active | 1 | — |
| 139 | [#297672](https://github.com/microsoft/vscode/issues/297672) | Expose terminal enumeration APIs for safe automation gating before kill-all actions | 0 | active | 1 | — |
| 186 | [#276906](https://github.com/microsoft/vscode/issues/276906) | rm `run_task` in favor of an execute strategy on `run_in_terminal` | 0 | dormant | 0 | — |
| 192 | [#291079](https://github.com/microsoft/vscode/issues/291079) | Run in terminal code block presenters  don't have same features as normal code blocks | 0 | backlog-candidate | 0 | — |
| 200 | [#300269](https://github.com/microsoft/vscode/issues/300269) | expose open terminal UI even when terminal command is collapsed | 0 | active | 0 | — |
| 202 | [#308616](https://github.com/microsoft/vscode/issues/308616) | Running benchmark results in a lot of checking terminal output | 0 | backlog-candidate | 0 | — |
| 203 | [#314080](https://github.com/microsoft/vscode/issues/314080) | No progress shown between terminal prompts | 0 | backlog-candidate | 0 | — |
| 205 | [#316307](https://github.com/microsoft/vscode/issues/316307) | Use artifacts for background terminals to improve accessibilty and stability | 0 | active | 0 | — |

### Accessibility and voice (42)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 17 | [#224921](https://github.com/microsoft/vscode/issues/224921) | Vimium or Vim easymotion like keyboard navigation for the whole UI | 35 | backlog-candidate | 8 | — |
| 21 | [#269246](https://github.com/microsoft/vscode/issues/269246) | [Accessibility] Expose lines numbers so that Windows 11 Voice access is able to see them for navigation | 20 | backlog-candidate | 8 | — |
| 29 | [#175986](https://github.com/microsoft/vscode/issues/175986) | Allow VS Code extensions to trigger audio cues | 22 | backlog-candidate | 6 | — |
| 34 | [#184357](https://github.com/microsoft/vscode/issues/184357) | [Accessibility]: Make syntax highlight accessible to screen reader users via a speech scheme | 17 | backlog-candidate | 5 | — |
| 49 | [#302997](https://github.com/microsoft/vscode/issues/302997) | VS Code Speech: Add right click to read aloud selected text | 0 | active | 3 | — |
| 56 | [#145204](https://github.com/microsoft/vscode/issues/145204) | Introduce Sound Theme, similar like Product Icon Themes | 7 | backlog-candidate | 2 | — |
| 71 | [#292577](https://github.com/microsoft/vscode/issues/292577) | Experimental: Keybinding Action Confirmation & ARIA Announcement System (opt-in) | 0 | backlog-candidate | 2 | — |
| 80 | [#97154](https://github.com/microsoft/vscode/issues/97154) | Use contentEditable for our hidden accessibility textArea | 2 | dormant | 1 | — |
| 83 | [#301431](https://github.com/microsoft/vscode/issues/301431) | Improve Chat Read-Aloud (Text-to-Speech) Controls in VS Code Chat: Start Position, Navigation, Speed Control, and Visible-Text-Only Reading | 2 | backlog-candidate | 1 | — |
| 87 | [#166472](https://github.com/microsoft/vscode/issues/166472) | [Accessibility] Add an option to allow Alt+F5 to jump to the next --word-diff instead of the whole line | 1 | backlog-candidate | 1 | — |
| 88 | [#180176](https://github.com/microsoft/vscode/issues/180176) | [Accessibility]: Consider replacing audioCues.lineHasInlineSuggestion with less distruptive lower-pitch sound | 1 | backlog-candidate | 1 | — |
| 91 | [#265744](https://github.com/microsoft/vscode/issues/265744) | Have voice input in command palette/ settings search | 1 | dormant | 1 | — |
| 93 | [#292578](https://github.com/microsoft/vscode/issues/292578) | Experimental: Double-Press Keybindings (single vs double-tap) (opt-in) | 1 | backlog-candidate | 1 | — |
| 94 | [#293535](https://github.com/microsoft/vscode/issues/293535) | Make message queueing screen reader friendly | 1 | active | 1 | — |
| 102 | [#168746](https://github.com/microsoft/vscode/issues/168746) | [Accessibility] Word wrap does not work in diff view (F7 and Shift+F7) | 0 | backlog-candidate | 1 | — |
| 103 | [#171755](https://github.com/microsoft/vscode/issues/171755) | Code lens is not accessible via screen reader | 0 | active | 1 | — |
| 106 | [#219138](https://github.com/microsoft/vscode/issues/219138) | Accessibility:  "Dark high contrast theme" cursor disappears and stops blinking after a time | 0 | dormant | 1 | — |
| 109 | [#233844](https://github.com/microsoft/vscode/issues/233844) | Tab With Problems - Improve Accessibility for Colorblind People | 0 | backlog-candidate | 1 | — |
| 117 | [#242617](https://github.com/microsoft/vscode/issues/242617) | add active editor state information to editor's text area aria label | 0 | dormant | 1 | — |
| 120 | [#254835](https://github.com/microsoft/vscode/issues/254835) | When using macOS with the VoiceOver screen reader, moving word-by-word across a sign character causes the word to be spoken twice | 0 | backlog-candidate | 1 | — |
| 137 | [#292587](https://github.com/microsoft/vscode/issues/292587) | [Feature Request] User-Contributed Accessibility Help System | 0 | backlog-candidate | 1 | — |
| 146 | [#180049](https://github.com/microsoft/vscode/issues/180049) | [Accessibility]: Support filtering symbol types in Document Sylbol View | 1 | backlog-candidate | 0 | — |
| 147 | [#209683](https://github.com/microsoft/vscode/issues/209683) | consider how to make `when` clauses more discoverable for keyboard users | 1 | dormant | 0 | — |
| 149 | [#320820](https://github.com/microsoft/vscode/issues/320820) | Voice input should mute mic routing to other apps (e.g. Teams) while active | 1 | active | 0 | — |
| 152 | [#140950](https://github.com/microsoft/vscode/issues/140950) | Spacing out the buttons in action bar [Accessibility] | 0 | backlog-candidate | 0 | — |
| 155 | [#153722](https://github.com/microsoft/vscode/issues/153722) | Provide speech feedback when commenting or uncommenting a line. | 0 | backlog-candidate | 0 | — |
| 159 | [#174359](https://github.com/microsoft/vscode/issues/174359) | Add expand/collapse audio cues | 0 | dormant | 0 | — |
| 160 | [#181139](https://github.com/microsoft/vscode/issues/181139) | Accessibility: Make Tab key focus restricted to the currently open view | 0 | dormant | 0 | — |
| 161 | [#185565](https://github.com/microsoft/vscode/issues/185565) | Accessibility: Cannot turn off audio cues on a language level | 0 | backlog-candidate | 0 | — |
| 162 | [#189374](https://github.com/microsoft/vscode/issues/189374) | Git - Add audio cues for sync changes operation | 0 | backlog-candidate | 0 | — |
| 163 | [#195413](https://github.com/microsoft/vscode/issues/195413) | indicate the number of available completions in inline completions accessible view aria label | 0 | dormant | 0 | — |
| 164 | [#199126](https://github.com/microsoft/vscode/issues/199126) | [Accessibility] Preserve last position in the Copilot Chat response list view | 0 | dormant | 0 | — |
| 166 | [#204258](https://github.com/microsoft/vscode/issues/204258) | Configurable Position for Accessibility-Related Text Notifications in Code Editor | 0 | dormant | 0 | — |
| 169 | [#217810](https://github.com/microsoft/vscode/issues/217810) | Settings editor should have Accessibility TOC entry | 0 | backlog-candidate | 0 | — |
| 170 | [#226092](https://github.com/microsoft/vscode/issues/226092) | [Accessibility] Support audio cue for commented range | 0 | dormant | 0 | — |
| 174 | [#239997](https://github.com/microsoft/vscode/issues/239997) | consider adding a progressive sound for applying edits | 0 | dormant | 0 | — |
| 183 | [#273164](https://github.com/microsoft/vscode/issues/273164) | include extra info in `aria-description` instead of `aria-label` | 0 | active | 0 | — |
| 184 | [#274211](https://github.com/microsoft/vscode/issues/274211) | Signature help doesn't provide enough information for a screenreader user, at least in languages supporting overloads | 0 | dormant | 0 | — |
| 197 | [#297501](https://github.com/microsoft/vscode/issues/297501) | In High contrast themes and in screen reader mode, we should set `accessibility.chat.showCheckmarks:true` by default | 0 | backlog-candidate | 0 | — |
| 201 | [#307697](https://github.com/microsoft/vscode/issues/307697) | Allow customizing the media sound for user confirmation prompts | 0 | backlog-candidate | 0 | — |
| 207 | [#322749](https://github.com/microsoft/vscode/issues/322749) | VS Code Speech: Right click to read aloud FROM SPECIFIC LOCATION in the response | 0 | backlog-candidate | 0 | — |
| 210 | [#328083](https://github.com/microsoft/vscode/issues/328083) | Bring back voice.md to onboarding banner once there's backend support | 0 | active | 0 | — |

### Chat and agent UX (14)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 65 | [#300574](https://github.com/microsoft/vscode/issues/300574) | Consider expanding set of tips for Copilot CLI and Claude Agent | 1 | backlog-candidate | 2 | — |
| 95 | [#298997](https://github.com/microsoft/vscode/issues/298997) | Add UI for right time right place tips | 1 | active | 1 | — |
| 97 | [#309506](https://github.com/microsoft/vscode/issues/309506) | Should the model be encouraged to use a small subagent for multi-stage inputs? | 1 | active | 1 | — |
| 100 | [#328486](https://github.com/microsoft/vscode/issues/328486) | add support in omni-chat to run vscode commands | 1 | active | 1 | — |
| 138 | [#296258](https://github.com/microsoft/vscode/issues/296258) | Copilot circumvents file exclusions | 0 | active | 1 | — |
| 142 | [#311382](https://github.com/microsoft/vscode/issues/311382) | Expose a dedicated environment variable for agents | 0 | active | 1 | — |
| 179 | [#256117](https://github.com/microsoft/vscode/issues/256117) | Have the agent add breakpoints | 0 | dormant | 0 | — |
| 190 | [#289465](https://github.com/microsoft/vscode/issues/289465) | Introduce model pick action item hide feature | 0 | active | 0 | — |
| 193 | [#291972](https://github.com/microsoft/vscode/issues/291972) | add a command to copy the most recent chat response text | 0 | active | 0 | — |
| 194 | [#294700](https://github.com/microsoft/vscode/issues/294700) | play confetti when a user takes a tip action | 0 | active | 0 | — |
| 196 | [#297128](https://github.com/microsoft/vscode/issues/297128) | Automate kicking off workflows for verification steps | 0 | active | 0 | — |
| 198 | [#299569](https://github.com/microsoft/vscode/issues/299569) | Move chat fork tip to be in session | 0 | active | 0 | — |
| 199 | [#299806](https://github.com/microsoft/vscode/issues/299806) | Enhance /generate-release-notes to apply `on-release-notes` labels automatically | 0 | active | 0 | — |
| 206 | [#316502](https://github.com/microsoft/vscode/issues/316502) | Reintroduce find/grep/tree compression with smart summarization | 0 | active | 0 | — |

### Other (11)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | [#93772](https://github.com/microsoft/vscode/issues/93772) | Provide a "focus-follow-mouse" setting | 345 | backlog-candidate | 100 | — |
| 53 | [#118230](https://github.com/microsoft/vscode/issues/118230) | Add "Copy Value" to the context menu in the Debug Console. | 9 | dormant | 2 | — |
| 55 | [#142922](https://github.com/microsoft/vscode/issues/142922) | Debug Console Filter is a bit confusing | 8 | backlog-candidate | 2 | — |
| 61 | [#225417](https://github.com/microsoft/vscode/issues/225417) | support finding matches in the debug console's output | 1 | dormant | 2 | — |
| 86 | [#80820](https://github.com/microsoft/vscode/issues/80820) | "editor font zoom" does not persist | 1 | dormant | 1 | — |
| 140 | [#300089](https://github.com/microsoft/vscode/issues/300089) | UI Space | 0 | active | 1 | — |
| 148 | [#240241](https://github.com/microsoft/vscode/issues/240241) | Terminal suggest: Support lazy loading of fig specs via an index | 1 | backlog-candidate | 0 | — |
| 157 | [#159174](https://github.com/microsoft/vscode/issues/159174) | Find Dialogue | 0 | backlog-candidate | 0 | — |
| 167 | [#209137](https://github.com/microsoft/vscode/issues/209137) | Consider notebook status `window.title` property | 0 | active | 0 | — |
| 171 | [#226716](https://github.com/microsoft/vscode/issues/226716) | The find widget should be more like the find widget in the terminal | 0 | dormant | 0 | — |
| 172 | [#227009](https://github.com/microsoft/vscode/issues/227009) | Support reverse search in tree find | 0 | dormant | 0 | — |
