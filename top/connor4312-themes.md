# Top issues by theme — connor4312

Experimental themed view of [the flat ranking](connor4312.md); themes assigned by the review engine. Rank/score are the lane-wide values. Generated 2026-07-20 19:45 UTC.

## Bugs

### Debugging workflows (61)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | [#278108](https://github.com/microsoft/vscode/issues/278108) | Debugger completion filters out matching items | 24 | correctness | 5/6 Source-confirmed | 100 | — | `npm run implement -- --issue 278108` |
| 2 | [#280933](https://github.com/microsoft/vscode/issues/280933) | Debugger has races and can show "Paused on Entry" shown for continued threads | 22 | correctness | 5/6 Source-confirmed | 95 | yes | `npm run implement -- --issue 280933` |
| 4 | [#296948](https://github.com/microsoft/vscode/issues/296948) | Hovering in a debug session intermittently shows the language hover instead of the debug hover | 11 | correctness | 5/6 Source-confirmed | 64 | — | `npm run implement -- --issue 296948` |
| 15 | [#248825](https://github.com/microsoft/vscode/issues/248825) | TreeError [DebugRepl] Tree input not set | 1 | correctness | 2/6 Unverified | 23 | — | — |
| 30 | [#286322](https://github.com/microsoft/vscode/issues/286322) | Disassembly view doesn’t show symbol labels even though debugger returns them | 3 | correctness | 5/6 Source-confirmed | 13 | — | `npm run implement -- --issue 286322` |
| 35 | [#296237](https://github.com/microsoft/vscode/issues/296237) | Error 'Unable to lauch browser: "Unable to attach to browser"' after every update | 1 | correctness | 5/6 Source-confirmed | 12 | — | `npm run implement -- --issue 296237` |
| 40 | [#291642](https://github.com/microsoft/vscode/issues/291642) | Debug disassembly view infinite scrolling does not work after navigating to second frame | 0 | correctness | 5/6 Source-confirmed | 11 | — | — |
| 50 | [#250116](https://github.com/microsoft/vscode/issues/250116) | Wrong/previous version of the extension is still used for debugger features after Install From VSIX... and Restart Extension | 1 | correctness | 5/6 Source-confirmed | 9 | — | `npm run implement -- --issue 250116` |
| 72 | [#278130](https://github.com/microsoft/vscode/issues/278130) | Pressing `F5` doesn't capture the active file for `${file}` immediately sometimes resulting in launching the wrong file | 0 | correctness | 5/6 Source-confirmed | 7 | — | `npm run implement -- --issue 278130` |
| 78 | [#322463](https://github.com/microsoft/vscode/issues/322463) | Completions not sent after every character in debug console | 1 | correctness | 5/6 Source-confirmed | 6 | yes | `npm run implement -- --issue 322463` |
| 79 | [#272410](https://github.com/microsoft/vscode/issues/272410) | Exception Breakpoints don't honor BreakpointMode | 0 | correctness | 5/6 Source-confirmed | 6 | yes | `npm run implement -- --issue 272410` |
| 82 | [#294963](https://github.com/microsoft/vscode/issues/294963) | Vscode crashes on ending / restarting nodejs targt | 0 | crash | 3/6 Plausible | 6 | — | `npm run implement -- --issue 294963` |
| 84 | [#299723](https://github.com/microsoft/vscode/issues/299723) | Inconsistent breakpoint behavior | 0 | correctness | 5/6 Source-confirmed | 6 | yes | `npm run implement -- --issue 299723` |
| 85 | [#318553](https://github.com/microsoft/vscode/issues/318553) | Run and debug view feels kind of broken on small views | 0 | visual | 6/6 Confirmed | 6 | — | `npm run implement -- --issue 318553` |
| 86 | [#228054](https://github.com/microsoft/vscode/issues/228054) | Cannot debug my extension, reaches breakpoint but hangs there. | 1 | freeze | 6/6 Confirmed | 5 | — | `npm run implement -- --issue 228054` |
| 113 | [#320061](https://github.com/microsoft/vscode/issues/320061) | Debugger not executing test anymore when using workbench.action.terminal.kill | 0 | correctness | 2/6 Unverified | 4 | — | — |
| 116 | [#242057](https://github.com/microsoft/vscode/issues/242057) | Pretty print for debugging appears in all editors when debugging | 1 | visual | 6/6 Confirmed | 3 | — | `npm run implement -- --issue 242057` |
| 119 | [#204173](https://github.com/microsoft/vscode/issues/204173) | VSCode .js Debugger Does Not Respect Glob Negations | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 120 | [#209587](https://github.com/microsoft/vscode/issues/209587) | TreeError [DebugRepl] Tree element not found: [object Object] | 0 | correctness | 5/6 Source-confirmed | 3 | yes | `npm run implement -- --issue 209587` |
| 121 | [#224056](https://github.com/microsoft/vscode/issues/224056) | Cannot read properties of undefined (reading 'size') | 0 | correctness | 4/6 Traced | 3 | yes | `npm run implement -- --issue 224056` |
| 123 | [#250087](https://github.com/microsoft/vscode/issues/250087) | node debug clobbers breakpoints if a transpiled asset already exists | 0 | correctness | 6/6 Confirmed | 3 | — | `npm run implement -- --issue 250087` |
| 140 | [#249889](https://github.com/microsoft/vscode/issues/249889) | Debug hover tooltip too small | 2 | papercut | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 249889` |
| 149 | [#246841](https://github.com/microsoft/vscode/issues/246841) | Debugger UI still does not close after stopping debug session (bug introduced in 1.86) | 0 | correctness | 2/6 Unverified | 2 | — | — |
| 154 | [#268456](https://github.com/microsoft/vscode/issues/268456) | Copy selection from Debug console | 0 | correctness | 4/6 Traced | 2 | — | — |
| 155 | [#270016](https://github.com/microsoft/vscode/issues/270016) | Selected launch option changes when more than one source exists and either changes | 0 | papercut | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 270016` |
| 160 | [#273896](https://github.com/microsoft/vscode/issues/273896) | Debug Console Focus and Display Persistence | 0 | papercut | 3/6 Plausible | 2 | — | — |
| 170 | [#294596](https://github.com/microsoft/vscode/issues/294596) | [FR] Allow callStackDown and callStackUp keyboard shortcuts to move through virtual environment | 0 | correctness | 4/6 Traced | 2 | yes | `npm run implement -- --issue 294596` |
| 177 | [#322448](https://github.com/microsoft/vscode/issues/322448) | Stepping sometimes causes focus to pass to another thread | 0 | correctness | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 322448` |
| 181 | [#219091](https://github.com/microsoft/vscode/issues/219091) | Have to click "stop" action multiple times | 1 | papercut | 3/6 Plausible | 1 | — | `npm run implement -- --issue 219091` |
| 182 | [#261498](https://github.com/microsoft/vscode/issues/261498) | No hover delay while debugging | 1 | papercut | 3/6 Plausible | 1 | — | `npm run implement -- --issue 261498` |
| 183 | [#71145](https://github.com/microsoft/vscode/issues/71145) | Debug: Server ready action pattern should have validation | 0 | papercut | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 71145` |
| 184 | [#131502](https://github.com/microsoft/vscode/issues/131502) | Source code downloaded via the debuggers sourceRequest creates lots of duplicate open files across debug sessions | 0 | papercut | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 131502` |
| 185 | [#144115](https://github.com/microsoft/vscode/issues/144115) | runTest is not honoring the launchArg '--new-window' | 0 | papercut | 3/6 Plausible | 1 | — | — |
| 188 | [#231490](https://github.com/microsoft/vscode/issues/231490) | debug.onDidChangeActiveDebugSession not always fired when active session implicitly changes after old active session terminated | 0 | correctness | 4/6 Traced | 1 | yes | `npm run implement -- --issue 231490` |
| 190 | [#239645](https://github.com/microsoft/vscode/issues/239645) | `stopAll` in compound launch.json should show default action as stop, not disconnect | 0 | papercut | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 239645` |
| 191 | [#240641](https://github.com/microsoft/vscode/issues/240641) | Debug hover now is offset at the start of the full expression - far from pointer | 0 | papercut | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 240641` |
| 192 | [#242033](https://github.com/microsoft/vscode/issues/242033) | vscode API - debug - start debugging | 0 | papercut | 6/6 Confirmed | 1 | — | `npm run implement -- --issue 242033` |
| 194 | [#250700](https://github.com/microsoft/vscode/issues/250700) | Attach by Process ID / PickProcess fails to enumerate | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 198 | [#276096](https://github.com/microsoft/vscode/issues/276096) | Debug API: `vscode.debug.breakpoints` returns duplicate breakpoints for the same line after deleting code blocks | 0 | correctness | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 276096` |
| 199 | [#277391](https://github.com/microsoft/vscode/issues/277391) | Delay before starting npm script in debug terminal | 0 | papercut | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 277391` |
| 213 | [#302390](https://github.com/microsoft/vscode/issues/302390) | Debug Console: text selection is lost when scrolling up (virtualized list resets selection) | 0 | papercut | 4/6 Traced | 1 | — | `npm run implement -- --issue 302390` |
| 214 | [#303498](https://github.com/microsoft/vscode/issues/303498) | Cannot debug Typescript with Angular's `servePath` option | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 239 | [#181165](https://github.com/microsoft/vscode/issues/181165) | unable to debug extensions in Codespaces for the web | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 181165` |
| 240 | [#186538](https://github.com/microsoft/vscode/issues/186538) | Unable to debug extensions in Codespaces desktop | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 186538` |
| 241 | [#192968](https://github.com/microsoft/vscode/issues/192968) | Debug hover sometimes positioned incorrectly | 0 | visual | 2/6 Unverified | 0 | — | — |
| 243 | [#212313](https://github.com/microsoft/vscode/issues/212313) | Logpoints printed twice when debugging VS Code | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 212313` |
| 245 | [#237234](https://github.com/microsoft/vscode/issues/237234) | No hint shown when hovering over type in debugger variables view | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 237234` |
| 246 | [#238055](https://github.com/microsoft/vscode/issues/238055) | angular breakpoints unreliable after navigating away from the angular application | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 253 | [#250942](https://github.com/microsoft/vscode/issues/250942) | DEBUG CONSOLE - does not match file paths with ANSI escape sequences. | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 250942` |
| 255 | [#255906](https://github.com/microsoft/vscode/issues/255906) | Variable substitution in enum properties of `launch.json` causes un-suppressable warnings | 0 | papercut | 4/6 Traced | 0 | — | `npm run implement -- --issue 255906` |
| 258 | [#262887](https://github.com/microsoft/vscode/issues/262887) | javascript debugger local file in chrome: unable to connect port 9222 | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 263 | [#272058](https://github.com/microsoft/vscode/issues/272058) | Editor hover is instant when debugging? | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 272058` |
| 277 | [#287054](https://github.com/microsoft/vscode/issues/287054) | Issue with NODE_OPTIONS in the devconatiner when Debug Auto Attach is enabled | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 282 | [#292292](https://github.com/microsoft/vscode/issues/292292) | Unable to move debug toolbar | 0 | papercut | 4/6 Traced | 0 | — | `npm run implement -- --issue 292292` |
| 287 | [#297413](https://github.com/microsoft/vscode/issues/297413) | It looks like a browser is already running ... | 0 | none | 3/6 Plausible | 0 | — | — |
| 294 | [#305208](https://github.com/microsoft/vscode/issues/305208) | When multiple Node debug sessions start concurrently, some sessions remain RUNNING after process exit (WSL / Dev Container) | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 305208` |
| 295 | [#305906](https://github.com/microsoft/vscode/issues/305906) | Debug adapter crashing extension host | 0 | papercut | 4/6 Traced | 0 | yes | `npm run implement -- --issue 305906` |
| 302 | [#310130](https://github.com/microsoft/vscode/issues/310130) | Cannot reload extension debugging because of: `Skill must provide a name.` error | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 305 | [#312216](https://github.com/microsoft/vscode/issues/312216) | Debugging copilot extension: ` WARNING: Processing source-maps of wasm://wasm/0002f80e took longer than 11000 ms` | 0 | perf | 3/6 Plausible | 0 | — | `npm run implement -- --issue 312216` |
| 317 | [#323066](https://github.com/microsoft/vscode/issues/323066) | VS Code debugger console prints %j literally for Node console.log format strings | 0 | correctness | 6/6 Confirmed | 0 | — | `npm run implement -- --issue 323066` |
| 326 | [#325972](https://github.com/microsoft/vscode/issues/325972) | Line not in focus during (C/C++) Debugging | 0 | papercut | 3/6 Plausible | 0 | — | — |

### Agent plugin lifecycle (24)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 3 | [#298701](https://github.com/microsoft/vscode/issues/298701) | Copilot Chat Agent Plugins can't be installed when project inside WSL | 1 | correctness | 2/6 Unverified | 66 | — | `npm run implement -- --issue 298701` |
| 31 | [#301570](https://github.com/microsoft/vscode/issues/301570) | Agent plugin recommendation notification appears when no recommended plugins are available | 0 | correctness | 2/6 Unverified | 13 | — | — |
| 39 | [#302312](https://github.com/microsoft/vscode/issues/302312) | Agent Plugins: README from remote agent plugins do not render in detail view | 2 | correctness | — | 11 | — | `npm run implement -- --issue 302312` |
| 48 | [#302181](https://github.com/microsoft/vscode/issues/302181) | Skills duplication when 'Agent Skills Location' overlaps with 'Plugin Locations' | 0 | visual | 3/6 Plausible | 10 | — | `npm run implement -- --issue 302181` |
| 68 | [#302515](https://github.com/microsoft/vscode/issues/302515) | Uninstalling a MCP server/hooks that were installed by a plugin | 0 | correctness | 6/6 Confirmed | 8 | — | `npm run implement -- --issue 302515` |
| 77 | [#307478](https://github.com/microsoft/vscode/issues/307478) | Plugin hooks can't invoke relative bundled scripts | 2 | correctness | 5/6 Source-confirmed | 6 | yes | `npm run implement -- --issue 307478` |
| 100 | [#307481](https://github.com/microsoft/vscode/issues/307481) | Reloading vscode-insiders is uninstalling azure agentplugin | 1 | correctness | 3/6 Plausible | 4 | — | `npm run implement -- --issue 307481` |
| 101 | [#312638](https://github.com/microsoft/vscode/issues/312638) | Installing plugin from custom marketplace fails as local git clone isn't updated | 1 | correctness | 5/6 Source-confirmed | 4 | yes | `npm run implement -- --issue 312638` |
| 102 | [#319926](https://github.com/microsoft/vscode/issues/319926) | enabledPlugins is too strict | 1 | correctness | 2/6 Unverified | 4 | — | — |
| 141 | [#318422](https://github.com/microsoft/vscode/issues/318422) | Duplicate Copilot agents shown when contributed by both VS Code extension and Copilot CLI plugin | 2 | papercut | 6/6 Confirmed | 2 | — | `npm run implement -- --issue 318422` |
| 172 | [#307203](https://github.com/microsoft/vscode/issues/307203) | chat.hookFilesLocations: rejects UNC/absolute paths inconsistently vs chat.pluginLocations + hooks inside agent plugins should be auto-discovered | 0 | papercut | 5/6 Source-confirmed | 2 | — | — |
| 212 | [#302350](https://github.com/microsoft/vscode/issues/302350) | Hooks in hooks.json fail to trigger when bundled within an Agent Plugin | 0 | correctness | 2/6 Unverified | 1 | — | — |
| 216 | [#304472](https://github.com/microsoft/vscode/issues/304472) | Allow me to uninstall a plugin | 0 | papercut | 3/6 Plausible | 1 | — | `npm run implement -- --issue 304472` |
| 223 | [#311589](https://github.com/microsoft/vscode/issues/311589) | Newly added plugins not visible after marketplace update due to stale GitHub cache | 0 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 311589` |
| 224 | [#312584](https://github.com/microsoft/vscode/issues/312584) | Agent Plugins: marketplace plugin detail view renders blank body for valid README | 0 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 312584` |
| 228 | [#318589](https://github.com/microsoft/vscode/issues/318589) | MCP servers for custom agents from copilot CLI don't start | 0 | correctness | 3/6 Plausible | 1 | — | `npm run implement -- --issue 318589` |
| 229 | [#318982](https://github.com/microsoft/vscode/issues/318982) | Agent plugin marketplace mangles SSH `source.url` when user is not `git` (breaks GHE / self-hosted) | 0 | correctness | 4/6 Traced | 1 | — | `npm run implement -- --issue 318982` |
| 236 | [#326166](https://github.com/microsoft/vscode/issues/326166) | Plugins hooks on devcontainers can't call upon plugin location | 0 | correctness | 4/6 Traced | 1 | — | `npm run implement -- --issue 326166` |
| 289 | [#299539](https://github.com/microsoft/vscode/issues/299539) | Agent plugins: Unnecessary separator | 0 | visual | — | 0 | — | `npm run implement -- --issue 299539` |
| 296 | [#306285](https://github.com/microsoft/vscode/issues/306285) | Custom Agent selection spontaneously resets to default when plugin auto update is enabled | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 308 | [#315347](https://github.com/microsoft/vscode/issues/315347) | Spurious 'this workspace requires agent plugin' notification with Claude model (local) | 0 | papercut | 2/6 Unverified | 0 | — | `npm run implement -- --issue 315347` |
| 309 | [#316303](https://github.com/microsoft/vscode/issues/316303) | Agent Plugin Marketplace: support plugins that re-declare the same root path | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 316303` |
| 310 | [#317173](https://github.com/microsoft/vscode/issues/317173) | AgentPlugin not recognized as installed although it's installed | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 317173` |
| 314 | [#322805](https://github.com/microsoft/vscode/issues/322805) | Agent customization for local continues to attempt to download old plugins from source after they have been uninstalled | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 322805` |

### Chat edits and diffs (52)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 5 | [#256329](https://github.com/microsoft/vscode/issues/256329) | GitHub Copilot Chat diff UI does not wrap deleted (red) lines, as it does added (green) lines, when word wrap is enabled | 29 | visual | — | 63 | — | `npm run implement -- --issue 256329` |
| 17 | [#274657](https://github.com/microsoft/vscode/issues/274657) | GitHub Copilot repeatedly combines lines and cannot indent correctly in code edits. | 1 | correctness | 3/6 Plausible | 21 | — | `npm run implement -- --issue 274657` |
| 18 | [#313703](https://github.com/microsoft/vscode/issues/313703) | Opening a chat session can silently dirty editor buffers and cause data loss | 0 | data-loss | 5/6 Source-confirmed | 21 | — | `npm run implement -- --issue 313703` |
| 33 | [#272364](https://github.com/microsoft/vscode/issues/272364) | Agent: create_file creates \n-broken files | 1 | correctness | 3/6 Plausible | 12 | — | `npm run implement -- --issue 272364` |
| 41 | [#299027](https://github.com/microsoft/vscode/issues/299027) | View all edits throws Unexpected type when a CustomTextEditorProvider is the active editor | 0 | correctness | 5/6 Source-confirmed | 11 | — | `npm run implement -- --issue 299027` |
| 42 | [#309680](https://github.com/microsoft/vscode/issues/309680) | Agent mode create_file produces corrupted Go files due to race between empty file creation and gopls workspace/didCreateFiles | 3 | correctness | 5/6 Source-confirmed | 10 | — | `npm run implement -- --issue 309680` |
| 51 | [#276838](https://github.com/microsoft/vscode/issues/276838) | Copilot writes to wrong location at C:\f\ | 1 | correctness | 2/6 Unverified | 9 | — | — |
| 53 | [#292211](https://github.com/microsoft/vscode/issues/292211) | Agent: Accepting changes from old session reverts files to earlier state, losing subsequent work | 1 | data-loss | 6/6 Confirmed | 9 | — | `npm run implement -- --issue 292211` |
| 56 | [#283069](https://github.com/microsoft/vscode/issues/283069) | Multi replace tool failed in inline chat | 0 | correctness | 2/6 Unverified | 9 | — | — |
| 57 | [#289294](https://github.com/microsoft/vscode/issues/289294) | Wrong diff is shown after git pull during session | 0 | correctness | 6/6 Confirmed | 9 | — | `npm run implement -- --issue 289294` |
| 58 | [#296064](https://github.com/microsoft/vscode/issues/296064) | Keep, Undo, Restore NOT WORKING | 0 | freeze | 6/6 Confirmed | 9 | — | `npm run implement -- --issue 296064` |
| 65 | [#264138](https://github.com/microsoft/vscode/issues/264138) | claude 4 - non stop broken code (JS) | 0 | correctness | 3/6 Plausible | 8 | — | — |
| 67 | [#297585](https://github.com/microsoft/vscode/issues/297585) | Rename tool implementation unavailable to Codex | 0 | correctness | 2/6 Unverified | 8 | — | `npm run implement -- --issue 297585` |
| 80 | [#272671](https://github.com/microsoft/vscode/issues/272671) | subsequent replace_string_in_file corrupt the file | 0 | correctness | 3/6 Plausible | 6 | — | `npm run implement -- --issue 272671` |
| 81 | [#289094](https://github.com/microsoft/vscode/issues/289094) | Incorrect warning "The model wants to edit files outside of your workspace" (if using symlinks?) | 0 | correctness | 3/6 Plausible | 6 | — | `npm run implement -- --issue 289094` |
| 83 | [#299028](https://github.com/microsoft/vscode/issues/299028) | Copilot inline review toolbar (Keep/Undo/Toggle Diff) and "View all edits" support for CustomTextEditorProvider-backed documents | 0 | correctness | — | 6 | — | `npm run implement -- --issue 299028` |
| 89 | [#272468](https://github.com/microsoft/vscode/issues/272468) | Pressing ‘Keep’ floods active editor with clipboard spam and corrupts file contents and sometime kinda freezes VS Code | 0 | correctness | 3/6 Plausible | 5 | — | `npm run implement -- --issue 272468` |
| 90 | [#288637](https://github.com/microsoft/vscode/issues/288637) | both gpt-5 and gpt5-mini remove code proposing patches | 0 | correctness | 3/6 Plausible | 5 | — | — |
| 97 | [#292807](https://github.com/microsoft/vscode/issues/292807) | Constant popup of "Diff Algorithm has stopped after 5000 ms" when running a agent session | 2 | papercut | 6/6 Confirmed | 4 | — | `npm run implement -- --issue 292807` |
| 105 | [#270772](https://github.com/microsoft/vscode/issues/270772) | Files and code not generating by agent. vs code version 1.105.0 | 0 | correctness | 3/6 Plausible | 4 | — | `npm run implement -- --issue 270772` |
| 118 | [#303827](https://github.com/microsoft/vscode/issues/303827) | Copilot Chat shows +0/-0 and no diff for file edits, even though changes are applied | 1 | visual | 4/6 Traced | 3 | — | `npm run implement -- --issue 303827` |
| 126 | [#276353](https://github.com/microsoft/vscode/issues/276353) | Checkpoint restoration only reverts first file when multiple files modified across separate requests | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 128 | [#282434](https://github.com/microsoft/vscode/issues/282434) | Local sessions: keeping edits needs 2 "Keep" to clear the edits | 0 | correctness | 6/6 Confirmed | 3 | — | `npm run implement -- --issue 282434` |
| 135 | [#290959](https://github.com/microsoft/vscode/issues/290959) | Agent sessions diff decoration doesn't disappear after undoing some changes | 0 | visual | 3/6 Plausible | 3 | — | `npm run implement -- --issue 290959` |
| 153 | [#260840](https://github.com/microsoft/vscode/issues/260840) | [GHCP] - undo button should not revert previously accepted changes in the session | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 159 | [#272803](https://github.com/microsoft/vscode/issues/272803) | Copilot creates and removes .yaml file upon finishing request when no workspace is open | 0 | correctness | 3/6 Plausible | 2 | — | `npm run implement -- --issue 272803` |
| 161 | [#275069](https://github.com/microsoft/vscode/issues/275069) | Editor scrambled after ctrl+z during edit session | 0 | correctness | 3/6 Plausible | 2 | — | `npm run implement -- --issue 275069` |
| 162 | [#275080](https://github.com/microsoft/vscode/issues/275080) | "Open Changes in Diff Editor" button doesn't work in Claude Code CLI | 0 | correctness | 6/6 Confirmed | 2 | — | `npm run implement -- --issue 275080` |
| 163 | [#279817](https://github.com/microsoft/vscode/issues/279817) | Leading slash character to file path while applying changes | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 166 | [#287616](https://github.com/microsoft/vscode/issues/287616) | Whole file is marked as AI edited | 0 | correctness | 3/6 Plausible | 2 | — | `npm run implement -- --issue 287616` |
| 174 | [#309197](https://github.com/microsoft/vscode/issues/309197) | Agent started accessing local files as web urls file:/// | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 175 | [#315310](https://github.com/microsoft/vscode/issues/315310) | Copilot applied changes without "accept/undo" button | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 196 | [#254172](https://github.com/microsoft/vscode/issues/254172) | Duplicate entries in edits list | 0 | correctness | — | 1 | — | `npm run implement -- --issue 254172` |
| 202 | [#281733](https://github.com/microsoft/vscode/issues/281733) | `apply_patch` fails to replace the whole contet of files | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 204 | [#289046](https://github.com/microsoft/vscode/issues/289046) | Indicates that the code of the entire file was edited by the agent, even though only parts were changed. In addition: Unexpected +0 changes count (shows in the chat) for files that did receive changes from the agent | 0 | correctness | 3/6 Plausible | 1 | — | `npm run implement -- --issue 289046` |
| 205 | [#291097](https://github.com/microsoft/vscode/issues/291097) | Typing in the diff editor from an agent edited file does weird stuff | 0 | correctness | 3/6 Plausible | 1 | — | `npm run implement -- --issue 291097` |
| 215 | [#303653](https://github.com/microsoft/vscode/issues/303653) | After Keep still all edits are shown | 0 | correctness | 3/6 Plausible | 1 | — | `npm run implement -- --issue 303653` |
| 218 | [#307576](https://github.com/microsoft/vscode/issues/307576) | Keep/Undo widget sits over code text | 0 | visual | 4/6 Traced | 1 | — | `npm run implement -- --issue 307576` |
| 221 | [#311213](https://github.com/microsoft/vscode/issues/311213) | Agent mode "Undo" button does not revert file changes | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 226 | [#315496](https://github.com/microsoft/vscode/issues/315496) | File closes automatically after accepting Copilot changes, causing loss of context (especially problematic for non‑Git files) | 0 | papercut | 3/6 Plausible | 1 | — | — |
| 249 | [#241856](https://github.com/microsoft/vscode/issues/241856) | File is shown as changed even after undo-ing the step that changed the file | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 241856` |
| 264 | [#275081](https://github.com/microsoft/vscode/issues/275081) | Edits not always tracked from Claude Code CLI | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 275081` |
| 265 | [#275384](https://github.com/microsoft/vscode/issues/275384) | Undoing the edit by `/savePrompt` leaves behind blank untitled file | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 275384` |
| 266 | [#275517](https://github.com/microsoft/vscode/issues/275517) | Undo claims that three files are changed although only one is | 0 | papercut | 2/6 Unverified | 0 | — | `npm run implement -- --issue 275517` |
| 270 | [#277029](https://github.com/microsoft/vscode/issues/277029) | Chat Agent: Pressing "keep" restores deleted files that previously had modifications | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 277029` |
| 271 | [#278226](https://github.com/microsoft/vscode/issues/278226) | lack of horizontal slider when code is marked (red) for removal | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 278226` |
| 276 | [#286451](https://github.com/microsoft/vscode/issues/286451) | Agent: Special characters made file un-editable for Opus | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 286451` |
| 280 | [#289650](https://github.com/microsoft/vscode/issues/289650) | Working set +0 -0 after rerunning a prompt | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 289650` |
| 284 | [#293750](https://github.com/microsoft/vscode/issues/293750) | Plan with Gemin 3 Pro -> Implement with gpt-5.1-codex-mini doesn't work since `replace_string_in_file` is used | 0 | correctness | 4/6 Traced | 0 | — | `npm run implement -- --issue 293750` |
| 288 | [#299276](https://github.com/microsoft/vscode/issues/299276) | [BUG] Copilot creates garbled files whenever it uses the `create_file` tool | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 301 | [#308366](https://github.com/microsoft/vscode/issues/308366) | applyPatchTool: original content leaks through when trailing newline counts differ | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 308366` |
| 307 | [#314055](https://github.com/microsoft/vscode/issues/314055) | Deleted files are coming back again and again | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 314055` |

### MCP tool integration (42)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 6 | [#245905](https://github.com/microsoft/vscode/issues/245905) | MCP Server Configuration: predefined variables (workspaceFolder, workspaceFolderBasename, selectedText) fail to resolve | 14 | correctness | 5/6 Source-confirmed | 54 | yes | `npm run implement -- --issue 245905` |
| 19 | [#290063](https://github.com/microsoft/vscode/issues/290063) | MCP: structuredContent in tool result overrides content[].text sent to model | 5 | correctness | 5/6 Source-confirmed | 20 | — | `npm run implement -- --issue 290063` |
| 29 | [#323908](https://github.com/microsoft/vscode/issues/323908) | Starting MCP servers block starting sessions | 0 | perf | 6/6 Confirmed | 14 | — | `npm run implement -- --issue 323908` |
| 34 | [#279280](https://github.com/microsoft/vscode/issues/279280) | CLI `--add-mcp` JSON argument loses quotes when called from PowerShell via `code.cmd` | 1 | correctness | 5/6 Source-confirmed | 12 | yes | `npm run implement -- --issue 279280` |
| 38 | [#290763](https://github.com/microsoft/vscode/issues/290763) | uvx not found when trying to start MCP server although available in the terminal | 2 | correctness | 6/6 Confirmed | 11 | — | `npm run implement -- --issue 290763` |
| 44 | [#288140](https://github.com/microsoft/vscode/issues/288140) | MCP tools incorrectly marked as "User disabled" when multiple VS Code windows connect to same SSE server | 1 | correctness | 3/6 Plausible | 10 | — | `npm run implement -- --issue 288140` |
| 61 | [#308766](https://github.com/microsoft/vscode/issues/308766) | Unsupported MCP protocol version: 2025-03-26 | 0 | correctness | 5/6 Source-confirmed | 9 | yes | `npm run implement -- --issue 308766` |
| 62 | [#318939](https://github.com/microsoft/vscode/issues/318939) | VS Code does not terminate active MCP sessions on exit | 0 | correctness | 3/6 Plausible | 9 | — | — |
| 87 | [#325618](https://github.com/microsoft/vscode/issues/325618) | Regression: Copilot Chat MCP fails on Dataverse server due to strict tool schema validation (array parameter missing items) | 1 | correctness | 5/6 Source-confirmed | 5 | yes | `npm run implement -- --issue 325618` |
| 91 | [#289129](https://github.com/microsoft/vscode/issues/289129) | MCP HTTP Client Encoding Query String Parameters | 0 | correctness | 4/6 Traced | 5 | yes | `npm run implement -- --issue 289129` |
| 110 | [#283642](https://github.com/microsoft/vscode/issues/283642) | sequentialthinking mcp no longer works with update | 0 | correctness | 5/6 Source-confirmed | 4 | yes | `npm run implement -- --issue 283642` |
| 115 | [#324993](https://github.com/microsoft/vscode/issues/324993) | MCP tools and vscode.lm.registerTool tools silently dropped in Agent mode on Remote SSH host (regression of #317992, still broken in 1.128) | 0 | correctness | 5/6 Source-confirmed | 4 | — | `npm run implement -- --issue 324993` |
| 150 | [#253508](https://github.com/microsoft/vscode/issues/253508) | MCP model access is not synced | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 158 | [#272420](https://github.com/microsoft/vscode/issues/272420) | MCP: programmatically registered MCP server don't get roots set from client | 0 | correctness | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 272420` |
| 178 | [#324172](https://github.com/microsoft/vscode/issues/324172) | Local stdio MCP server: initial `availableDeferredTools` list omits many registered tools with no signal that they exist | 0 | correctness | 3/6 Plausible | 2 | — | `npm run implement -- --issue 324172` |
| 179 | [#324992](https://github.com/microsoft/vscode/issues/324992) | MCP tool names collide when multiple servers report the same serverInfo.name, producing unstable _2/_3 prefixes | 0 | correctness | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 324992` |
| 195 | [#251725](https://github.com/microsoft/vscode/issues/251725) | MCP `resources/read` doesn't support multiple Resources in result | 0 | correctness | 2/6 Unverified | 1 | — | — |
| 197 | [#274606](https://github.com/microsoft/vscode/issues/274606) | HTTP MCP Server URL Configuration Fails to Preserve Percent-Encoded Slashes (%2F) in Path | 0 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 274606` |
| 210 | [#297794](https://github.com/microsoft/vscode/issues/297794) | `${workspaceFolder}` not resolvable in MCP configuration | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 211 | [#301690](https://github.com/microsoft/vscode/issues/301690) | Tool conflict between MCP and built-in tools | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 220 | [#310803](https://github.com/microsoft/vscode/issues/310803) | copilot mcp tools selection cross session | 0 | correctness | 4/6 Traced | 1 | — | `npm run implement -- --issue 310803` |
| 232 | [#321662](https://github.com/microsoft/vscode/issues/321662) | MCP tool input validation rejects anyOf schemas - blocks Union-typed parameters | 0 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 321662` |
| 256 | [#257665](https://github.com/microsoft/vscode/issues/257665) | Virtual Tools should not disable mentioned tools | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 257665` |
| 268 | [#276111](https://github.com/microsoft/vscode/issues/276111) | Missing tool embeddings | 0 | correctness | 4/6 Traced | 0 | — | `npm run implement -- --issue 276111` |
| 269 | [#276196](https://github.com/microsoft/vscode/issues/276196) | # GitHub Copilot Chat Cannot Reference MCP Servers with Special Characters Using # Notation | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 276196` |
| 272 | [#280614](https://github.com/microsoft/vscode/issues/280614) | Tools picker: MCP server entry checking state is not persisted if server is not started | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 280614` |
| 273 | [#280623](https://github.com/microsoft/vscode/issues/280623) | Github MCP server: Changing settings does not directly update tools | 0 | papercut | — | 0 | — | `npm run implement -- --issue 280623` |
| 278 | [#287801](https://github.com/microsoft/vscode/issues/287801) | MCP prompt arguments cannot reliably accept binary file data | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 287801` |
| 281 | [#292014](https://github.com/microsoft/vscode/issues/292014) | GLM is deeply confused by the file-based tool responses | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 292014` |
| 285 | [#294056](https://github.com/microsoft/vscode/issues/294056) | MCPs that need to be started for a given prompt are auto-enabled | 0 | correctness | — | 0 | — | `npm run implement -- --issue 294056` |
| 291 | [#302394](https://github.com/microsoft/vscode/issues/302394) | MCP Streamable HTTP client does not send cookies, breaking ARR affinity on multi-instance Azure App Service | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 302394` |
| 292 | [#303695](https://github.com/microsoft/vscode/issues/303695) | MCP: "Failed to parse message: ''" warning from empty SSE priming frames | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 303695` |
| 293 | [#303696](https://github.com/microsoft/vscode/issues/303696) | GitHub tool calls often show TypeError in Output | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 303696` |
| 306 | [#313209](https://github.com/microsoft/vscode/issues/313209) | MCP server CodeLens actions are missing | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 311 | [#318893](https://github.com/microsoft/vscode/issues/318893) | removeDangerousEnvVariables gap - Strongest argument. Every other spawn path in VS Code strips NODE_OPTIONS/LD_PRELOAD/DEBUG. MCP is the sole omission. This is objectively a bug, not a design decision. | 0 | papercut | 4/6 Traced | 0 | — | `npm run implement -- --issue 318893` |
| 312 | [#318984](https://github.com/microsoft/vscode/issues/318984) | VSCode GitHub Copilot Chat Local Agent Mode crashes when MCP server uses JSON Schema draft-2020-12 features | 0 | crash | 4/6 Traced | 0 | — | `npm run implement -- --issue 318984` |
| 318 | [#323357](https://github.com/microsoft/vscode/issues/323357) | Copilot Chat /compact triggers MCP server startup (unexpected side effect) | 0 | papercut | 4/6 Traced | 0 | — | `npm run implement -- --issue 323357` |
| 319 | [#323809](https://github.com/microsoft/vscode/issues/323809) | Agent host MCP servers do not start automatically | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 323809` |
| 321 | [#323990](https://github.com/microsoft/vscode/issues/323990) | Copilot Chat: first invocation of a remote MCP tool fails with "Cannot read properties of undefined (reading 'invoke')" | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 323990` |
| 322 | [#324145](https://github.com/microsoft/vscode/issues/324145) | Wrong tool used in chat input when multiple MCP servers expose the same tool name | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 324145` |
| 328 | [#326440](https://github.com/microsoft/vscode/issues/326440) | AHP initialize failed: rpc error -32005: Client offered protocol versions [0.4.0], none of which are compatible with this server's version 0.6.0 (server accepts ^0.6.0) | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 326440` |
| 330 | [#326622](https://github.com/microsoft/vscode/issues/326622) | Cannot find uvx when launching MCP comming from agents Plugin | 0 | correctness | 3/6 Plausible | 0 | — | — |

### Performance and crashes (15)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 7 | [#313040](https://github.com/microsoft/vscode/issues/313040) | [Error] [GitHub.copilot-chat] unhandlederror-ENOENT: no such file or directory, copyfile '<REDACTED: user-file-path>/.vscode\exten... | 0 | correctness | 5/6 Source-confirmed | 47 | yes | `npm run implement -- --issue 313040` |
| 22 | [#266716](https://github.com/microsoft/vscode/issues/266716) | Copilot OOM (Node.js) | 0 | crash | 6/6 Confirmed | 16 | — | `npm run implement -- --issue 266716` |
| 59 | [#298325](https://github.com/microsoft/vscode/issues/298325) | Searching for "******************:" freezes vscode in flutter. | 0 | freeze | 3/6 Plausible | 9 | — | — |
| 75 | [#311712](https://github.com/microsoft/vscode/issues/311712) | [Error] unhandlederror-Potential working copy LEAK detected, having 513 working copies already. Most frequen... | 0 | perf | 5/6 Source-confirmed | 7 | — | `npm run implement -- --issue 311712` |
| 94 | [#309905](https://github.com/microsoft/vscode/issues/309905) | [Unhandled Error] potential listener LEAK detected, popular | 0 | perf | 5/6 Source-confirmed | 5 | — | `npm run implement -- --issue 309905` |
| 95 | [#316428](https://github.com/microsoft/vscode/issues/316428) | [Regression] [Error] [GitHub.copilot-chat] unhandlederror-InstantiationService has been disposed | 0 | correctness | 3/6 Plausible | 5 | — | `npm run implement -- --issue 316428` |
| 96 | [#318012](https://github.com/microsoft/vscode/issues/318012) | [Error] [GitHub.copilot-chat] unhandlederror-Error fetching embeddings: 422 | 0 | correctness | 3/6 Plausible | 5 | — | `npm run implement -- --issue 318012` |
| 138 | [#314403](https://github.com/microsoft/vscode/issues/314403) | [Error] unhandlederror-PerfSampleError: by <<renderer>> in io#workbench.desktop.main.js:414:15968 | 0 | perf | 5/6 Source-confirmed | 3 | yes | `npm run implement -- --issue 314403` |
| 173 | [#307910](https://github.com/microsoft/vscode/issues/307910) | VS Code Insiders keeps crashing | 0 | freeze | 3/6 Plausible | 2 | — | — |
| 217 | [#306389](https://github.com/microsoft/vscode/issues/306389) | Crash Report when Compacting | 0 | crash | 3/6 Plausible | 1 | — | — |
| 222 | [#311549](https://github.com/microsoft/vscode/issues/311549) | [Error] unhandlederror-Illegal state: service accessor is only valid during the invocation of its target met... | 0 | correctness | 2/6 Unverified | 1 | — | — |
| 234 | [#324549](https://github.com/microsoft/vscode/issues/324549) | [Error] unhandlederror-Cannot read properties of null (reading 'node') | 0 | correctness | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 324549` |
| 298 | [#306434](https://github.com/microsoft/vscode/issues/306434) | Failed to fetch AutoMode token: token is undefined after fetch attempt. | 0 | none | 2/6 Unverified | 0 | — | — |
| 299 | [#306842](https://github.com/microsoft/vscode/issues/306842) | GIT error across ALL my VS Code instances, triggering all at once | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 306842` |
| 315 | [#322939](https://github.com/microsoft/vscode/issues/322939) | CLI seems to have problems loading diagnostics | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 322939` |

### Workbench UI rendering (15)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 8 | [#263499](https://github.com/microsoft/vscode/issues/263499) | Split individual chat response parts to list rows | 2 | perf | 5/6 Source-confirmed | 46 | — | `npm run implement -- --issue 263499` |
| 23 | [#286397](https://github.com/microsoft/vscode/issues/286397) | Duplicate code printed below correct code in same code block | 0 | correctness | 3/6 Plausible | 16 | — | — |
| 36 | [#246523](https://github.com/microsoft/vscode/issues/246523) | scroll behavior is not smooth sometimes | 6 | papercut | 6/6 Confirmed | 11 | — | `npm run implement -- --issue 246523` |
| 88 | [#253419](https://github.com/microsoft/vscode/issues/253419) | Terminal suggest is behind copilot edit widget | 0 | visual | 3/6 Plausible | 5 | — | `npm run implement -- --issue 253419` |
| 98 | [#273251](https://github.com/microsoft/vscode/issues/273251) | "Copy All" from the chat window does not include the outputs from MCP / extension tools | 1 | correctness | 5/6 Source-confirmed | 4 | yes | `npm run implement -- --issue 273251` |
| 111 | [#293892](https://github.com/microsoft/vscode/issues/293892) | Rendering glitch in tool approval | 0 | visual | 3/6 Plausible | 4 | — | `npm run implement -- --issue 293892` |
| 124 | [#267464](https://github.com/microsoft/vscode/issues/267464) | Profile output becomes unresponsive after search | 0 | freeze | 3/6 Plausible | 3 | — | — |
| 130 | [#286316](https://github.com/microsoft/vscode/issues/286316) | Chat input - accepting changes shifts the input | 0 | visual | 2/6 Unverified | 3 | — | `npm run implement -- --issue 286316` |
| 134 | [#290925](https://github.com/microsoft/vscode/issues/290925) | Diff views in hover are not sized properly | 0 | visual | 3/6 Plausible | 3 | — | `npm run implement -- --issue 290925` |
| 137 | [#302205](https://github.com/microsoft/vscode/issues/302205) | Session hover card overlaps with window controls | 0 | visual | 3/6 Plausible | 3 | — | `npm run implement -- --issue 302205` |
| 146 | [#237314](https://github.com/microsoft/vscode/issues/237314) | Error messages are cut off when they appear after long code blocks that require horizontal scrolling | 0 | visual | 4/6 Traced | 2 | — | `npm run implement -- --issue 237314` |
| 152 | [#260111](https://github.com/microsoft/vscode/issues/260111) | Seeing translation errors in notebook snapshot in Window log | 0 | papercut | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 260111` |
| 165 | [#285364](https://github.com/microsoft/vscode/issues/285364) | With minimap disabled, copilot keep/undo changes view bleeds into scrollbar | 0 | visual | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 285364` |
| 186 | [#195478](https://github.com/microsoft/vscode/issues/195478) | Anoying notification when no workspace opened | 0 | papercut | 3/6 Plausible | 1 | — | `npm run implement -- --issue 195478` |
| 250 | [#246878](https://github.com/microsoft/vscode/issues/246878) | Accessible View for Copilot Agent: show file changes as one-liner instead of entire diff | 0 | papercut | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 246878` |

### Remote tunnels and hosts (25)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 9 | [#324081](https://github.com/microsoft/vscode/issues/324081) | Agent window SSH does not work well with keys | 3 | correctness | 3/6 Plausible | 33 | — | `npm run implement -- --issue 324081` |
| 24 | [#315841](https://github.com/microsoft/vscode/issues/315841) | Deadlock in extension host activation blocks tunnels auth | 0 | freeze | 6/6 Confirmed | 16 | — | `npm run implement -- --issue 315841` |
| 25 | [#212410](https://github.com/microsoft/vscode/issues/212410) | remote extension host terminated unexpectedly | 2 | crash | 3/6 Plausible | 15 | — | — |
| 32 | [#322565](https://github.com/microsoft/vscode/issues/322565) | Tunnels stuck in "Starting Remote tunnel" and not installed as service | 0 | correctness | 5/6 Source-confirmed | 13 | — | — |
| 43 | [#298748](https://github.com/microsoft/vscode/issues/298748) | tunnel service does not persist after reboot on MacOS | 2 | correctness | 5/6 Source-confirmed | 10 | yes | `npm run implement -- --issue 298748` |
| 46 | [#278150](https://github.com/microsoft/vscode/issues/278150) | Code server will detect the prerequisitions incorrectly when "\$ORIGIN" is in "$LD_LIBRARY_PATH" | 0 | correctness | 5/6 Source-confirmed | 10 | yes | `npm run implement -- --issue 278150` |
| 54 | [#293800](https://github.com/microsoft/vscode/issues/293800) | Remote Tunnels fails to open workspace when path contains Chinese(non-ascii) characters. | 1 | correctness | 4/6 Traced | 9 | — | `npm run implement -- --issue 293800` |
| 103 | [#246732](https://github.com/microsoft/vscode/issues/246732) | Port forwarding address doesn't work for one specific port with ERR_SSL_PROTOCOL_ERROR | 0 | correctness | 3/6 Plausible | 4 | — | — |
| 131 | [#287592](https://github.com/microsoft/vscode/issues/287592) | DevTunnels No funciona. No es posible compartir el puerto donde se ejencuta LiveServer. | 0 | correctness | 3/6 Plausible | 3 | — | `npm run implement -- --issue 287592` |
| 142 | [#257972](https://github.com/microsoft/vscode/issues/257972) | CLI upgrade requires manual restart of system service | 1 | correctness | 2/6 Unverified | 2 | — | — |
| 145 | [#207669](https://github.com/microsoft/vscode/issues/207669) | VS Code Remote Tunnel don't load PHP files | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 147 | [#237797](https://github.com/microsoft/vscode/issues/237797) | Failed to connect to the remote extension host server. (Error: CodeError(AsyncPipeFailed(Os { code: 2, kind: NotFound, message: "No such file or directory" })) | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 151 | [#253643](https://github.com/microsoft/vscode/issues/253643) | Unable to setup multiple ports to forward | 0 | correctness | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 253643` |
| 157 | [#271837](https://github.com/microsoft/vscode/issues/271837) | Port Forwarding | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 187 | [#228407](https://github.com/microsoft/vscode/issues/228407) | Unable to connect to tunnel after code update | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 219 | [#310726](https://github.com/microsoft/vscode/issues/310726) | CLI for tunnels not accepting GitHub PATs for unclear reasons | 0 | correctness | 4/6 Traced | 1 | — | `npm run implement -- --issue 310726` |
| 225 | [#313586](https://github.com/microsoft/vscode/issues/313586) | Could not parse status output: "Running tunnel CLI\nstatus Spawning: /Applications/Visual Studio Code - Insiders.app/Contents/Resources/app/bin/code-tunnel-insiders tunnel status\nstatus exit(91494): + null" | 0 | correctness | 3/6 Plausible | 1 | — | `npm run implement -- --issue 313586` |
| 231 | [#321555](https://github.com/microsoft/vscode/issues/321555) | port forwarding issues | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 235 | [#325537](https://github.com/microsoft/vscode/issues/325537) | sub-comand code serve-web fail | 0 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 325537` |
| 262 | [#270577](https://github.com/microsoft/vscode/issues/270577) | CLI: Avoid asking the user to update server, if they specify a VS Code version in URL, in vscode.dev | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 270577` |
| 300 | [#307368](https://github.com/microsoft/vscode/issues/307368) | Remote tunnel connection broken after each update | 0 | correctness | 6/6 Confirmed | 0 | — | — |
| 313 | [#319297](https://github.com/microsoft/vscode/issues/319297) | Remote Tunnel: status stuck on Connecting after successful startup | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 323 | [#324261](https://github.com/microsoft/vscode/issues/324261) | SSH session stuck on client tools | 0 | freeze | 6/6 Confirmed | 0 | — | `npm run implement -- --issue 324261` |
| 324 | [#325152](https://github.com/microsoft/vscode/issues/325152) | Port forwarding not working | 0 | crash | 3/6 Plausible | 0 | — | — |
| 329 | [#326523](https://github.com/microsoft/vscode/issues/326523) | Local file attachments do not work in remote Agent Host sessions | 0 | correctness | — | 0 | — | `npm run implement -- --issue 326523` |

### Chat session state (26)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 10 | [#307348](https://github.com/microsoft/vscode/issues/307348) | Chat session permanently unloadable after VS Code killed mid-response (TypeError: Cannot read properties of undefined (reading 'response')) | 0 | data-loss | 5/6 Source-confirmed | 32 | — | `npm run implement -- --issue 307348` |
| 12 | [#296890](https://github.com/microsoft/vscode/issues/296890) | Agent mode: sending message mid-response sometimes forks session into two parallel agents, causing conflicting edits and JSONL corruption | 0 | data-loss | 4/6 Traced | 27 | — | `npm run implement -- --issue 296890` |
| 13 | [#307439](https://github.com/microsoft/vscode/issues/307439) | Copilot Chat: Unresponsive, stale "pending edits" persist when files are edited outside the session | 5 | correctness | — | 24 | — | — |
| 16 | [#308730](https://github.com/microsoft/vscode/issues/308730) | GIthub Copilot Chat session cannot be reopened from Sessions list due to malformed chatSessions JSONL (missing base record / BOM parse error) | 0 | correctness | 4/6 Traced | 23 | — | `npm run implement -- --issue 308730` |
| 27 | [#314556](https://github.com/microsoft/vscode/issues/314556) | Chat session persistence inlines image and tool binary data as base64, causing unbounded session growth | 0 | perf | 5/6 Source-confirmed | 15 | — | `npm run implement -- --issue 314556` |
| 28 | [#320428](https://github.com/microsoft/vscode/issues/320428) | missing active doc context in AHP sessions | 0 | correctness | 6/6 Confirmed | 15 | — | `npm run implement -- --issue 320428` |
| 52 | [#291282](https://github.com/microsoft/vscode/issues/291282) | Having too many "un-kept" file changes in previous AI Chat sessions eventually causes the UI to lock-up entirely at least once per minute and 100% of the time on focus | 1 | freeze | 3/6 Plausible | 9 | — | — |
| 60 | [#304443](https://github.com/microsoft/vscode/issues/304443) | copilot-cli sessions trigger save right on startup | 0 | perf | 5/6 Source-confirmed | 9 | — | `npm run implement -- --issue 304443` |
| 66 | [#282335](https://github.com/microsoft/vscode/issues/282335) | multiple chats with different modes cause overwrite of mode | 0 | correctness | 3/6 Plausible | 8 | — | `npm run implement -- --issue 282335` |
| 93 | [#302814](https://github.com/microsoft/vscode/issues/302814) | Chat hangs when Copilot chat is installed without being signed in | 0 | freeze | 3/6 Plausible | 5 | — | `npm run implement -- --issue 302814` |
| 106 | [#271409](https://github.com/microsoft/vscode/issues/271409) | VS Code Froze + Crashed, Cannot Access Previous Copilot Chats | 0 | data-loss | 3/6 Plausible | 4 | — | `npm run implement -- --issue 271409` |
| 109 | [#281434](https://github.com/microsoft/vscode/issues/281434) | Cannot start two draft chats in the agent session | 0 | correctness | 2/6 Unverified | 4 | — | — |
| 127 | [#280786](https://github.com/microsoft/vscode/issues/280786) | Edited request is not availabe in chat editor history | 0 | papercut | 3/6 Plausible | 3 | — | `npm run implement -- --issue 280786` |
| 129 | [#285504](https://github.com/microsoft/vscode/issues/285504) | Pressing up doesn't put the last message into the chat input | 0 | papercut | 3/6 Plausible | 3 | — | `npm run implement -- --issue 285504` |
| 139 | [#315314](https://github.com/microsoft/vscode/issues/315314) | Hydrating large chat session items block renderer during startup | 0 | perf | 6/6 Confirmed | 3 | — | `npm run implement -- --issue 315314` |
| 164 | [#282338](https://github.com/microsoft/vscode/issues/282338) | 'Error reading chat session file copilotcli' on launch | 0 | papercut | 2/6 Unverified | 2 | — | `npm run implement -- --issue 282338` |
| 167 | [#287755](https://github.com/microsoft/vscode/issues/287755) | Chat took too long to get ready | 0 | perf | 2/6 Unverified | 2 | — | — |
| 180 | [#325631](https://github.com/microsoft/vscode/issues/325631) | Session shows as input needed when using browser tools with bypass approvals | 0 | visual | — | 2 | — | `npm run implement -- --issue 325631` |
| 206 | [#292313](https://github.com/microsoft/vscode/issues/292313) | the unproperly interupt of stable model | 0 | none | 3/6 Plausible | 1 | — | — |
| 230 | [#321185](https://github.com/microsoft/vscode/issues/321185) | Agent Host sessions not restored on restart when chat.restoreLastPanelSession is true: possible AH lazy registration race (awaiting activation but missing new AH path) , bodyVersion":"" | 0 | correctness | 6/6 Confirmed | 1 | — | `npm run implement -- --issue 321185` |
| 237 | [#326450](https://github.com/microsoft/vscode/issues/326450) | Restore Checkpoint not working with AH session | 0 | correctness | 6/6 Confirmed | 1 | — | `npm run implement -- --issue 326450` |
| 238 | [#326474](https://github.com/microsoft/vscode/issues/326474) | Agent Host input box missing fuzzy file search (e.g. '#roadma' → roadmap.md) | 0 | correctness | — | 1 | — | `npm run implement -- --issue 326474` |
| 274 | [#280999](https://github.com/microsoft/vscode/issues/280999) | Message reappears after checkpoint | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 280999` |
| 316 | [#322990](https://github.com/microsoft/vscode/issues/322990) | Agent Host client tool hangs after active client removal; browser click invoked with empty args | 0 | freeze | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 322990` |
| 320 | [#323860](https://github.com/microsoft/vscode/issues/323860) | Copilot AHP - message bug | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 323860` |
| 327 | [#326244](https://github.com/microsoft/vscode/issues/326244) | Agent window: steering messages pollute other chat forks | 0 | correctness | — | 0 | — | `npm run implement -- --issue 326244` |

### Testing results (26)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 11 | [#318548](https://github.com/microsoft/vscode/issues/318548) | Link provider runs for test results diff view, but not test results output view | 6 | correctness | 5/6 Source-confirmed | 27 | — | — |
| 20 | [#266048](https://github.com/microsoft/vscode/issues/266048) | A large number of test output events cause hangs in the VS Code UI | 1 | freeze | 6/6 Confirmed | 19 | — | `npm run implement -- --issue 266048` |
| 21 | [#307197](https://github.com/microsoft/vscode/issues/307197) | runTests tool fails to find tests that run fine in "C# Dev Kit - Test Explorer" | 0 | correctness | 3/6 Plausible | 17 | — | `npm run implement -- --issue 307197` |
| 49 | [#326263](https://github.com/microsoft/vscode/issues/326263) | hovering over run buttons sometimes moves the gutter and prevents test run buttons from working | 3 | papercut | 3/6 Plausible | 9 | — | `npm run implement -- --issue 326263` |
| 63 | [#264581](https://github.com/microsoft/vscode/issues/264581) | Modifying the location of any test (TestController API) causes all other test in the file to snap back to their original locations ignoring unsaved changes | 2 | correctness | 4/6 Traced | 8 | — | `npm run implement -- --issue 264581` |
| 71 | [#238241](https://github.com/microsoft/vscode/issues/238241) | Test Run completion takes very long on many tests (after `RunHandler` is completed) | 0 | perf | 5/6 Source-confirmed | 7 | — | `npm run implement -- --issue 238241` |
| 112 | [#294223](https://github.com/microsoft/vscode/issues/294223) | Markdown code blocks don't render correctly in Test Results pane | 0 | visual | 5/6 Source-confirmed | 4 | yes | `npm run implement -- --issue 294223` |
| 117 | [#243469](https://github.com/microsoft/vscode/issues/243469) | Test Peek Output Window and Test Results Tab don't support file links. | 1 | papercut | 4/6 Traced | 3 | — | `npm run implement -- --issue 243469` |
| 122 | [#245927](https://github.com/microsoft/vscode/issues/245927) | Testing extension gets the same test included twice in case of debugging 1 test | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 148 | [#238060](https://github.com/microsoft/vscode/issues/238060) | Testing setting `testing.automaticallyOpenTestResults` doesn't seem to work | 0 | papercut | 3/6 Plausible | 2 | — | — |
| 156 | [#270374](https://github.com/microsoft/vscode/issues/270374) | Linkified path in Test Results panel converts to windows path in WSL | 0 | correctness | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 270374` |
| 171 | [#305619](https://github.com/microsoft/vscode/issues/305619) | Copilot doesn't see python test discovery errors (pytest) | 0 | correctness | 4/6 Traced | 2 | — | `npm run implement -- --issue 305619` |
| 193 | [#250549](https://github.com/microsoft/vscode/issues/250549) | Test Results panel doesn't support horizontal scrolling with two-finger swipe gesture | 0 | papercut | 6/6 Confirmed | 1 | — | `npm run implement -- --issue 250549` |
| 233 | [#323294](https://github.com/microsoft/vscode/issues/323294) | Flaky unit test: McpStdioStateHandler sigterm after grace | 0 | papercut | 6/6 Confirmed | 1 | yes | `npm run implement -- --issue 323294` |
| 242 | [#209622](https://github.com/microsoft/vscode/issues/209622) | Test Coverage Reading | 0 | correctness | 4/6 Traced | 0 | — | `npm run implement -- --issue 209622` |
| 244 | [#235106](https://github.com/microsoft/vscode/issues/235106) | Test filter is hard to follow | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 235106` |
| 247 | [#239302](https://github.com/microsoft/vscode/issues/239302) | Test coverage shows incorrect coverage margin decorations when filtered | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 239302` |
| 248 | [#241441](https://github.com/microsoft/vscode/issues/241441) | Test error decoration glitch when zoomed in | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 241441` |
| 251 | [#249457](https://github.com/microsoft/vscode/issues/249457) | "Clear all Results" is rather slow (20s?) and blocks the UI when there are a lot of tests | 0 | freeze | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 249457` |
| 254 | [#251594](https://github.com/microsoft/vscode/issues/251594) | Actual column in test results is hidden behind test list when test results tab is on the right side | 0 | visual | 4/6 Traced | 0 | yes | `npm run implement -- --issue 251594` |
| 260 | [#268397](https://github.com/microsoft/vscode/issues/268397) | Test results show incorrect validation state after repeated continuous runs | 0 | visual | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 268397` |
| 261 | [#270173](https://github.com/microsoft/vscode/issues/270173) | Select All functionality does not work in Test Panel | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 270173` |
| 297 | [#306367](https://github.com/microsoft/vscode/issues/306367) | Failures when running tests for a newly-created extension project in a folder with spaces in the name | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 303 | [#311056](https://github.com/microsoft/vscode/issues/311056) | When running tests, the pill icon background is rotating along with it's glyph | 0 | visual | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 311056` |
| 304 | [#311677](https://github.com/microsoft/vscode/issues/311677) | Very Slow Test Run | 0 | none | 3/6 Plausible | 0 | — | — |
| 325 | [#325292](https://github.com/microsoft/vscode/issues/325292) | Markdown test failure messages clip long unbreakable text in Test Results view — cannot wrap, scroll, or configure | 0 | visual | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 325292` |

### Chat approvals and input (27)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 14 | [#277667](https://github.com/microsoft/vscode/issues/277667) | October 2025 release breaks GitHub Copilot `Ctrl+Y` "Keep" shortcut. | 2 | correctness | 3/6 Plausible | 23 | — | `npm run implement -- --issue 277667` |
| 37 | [#279219](https://github.com/microsoft/vscode/issues/279219) | optimizing tool selection: no lowest priority node found | 2 | correctness | — | 11 | — | — |
| 45 | [#317320](https://github.com/microsoft/vscode/issues/317320) | Ctrl+backspace discards ALL Chat changes instead of deleting word (when text prompt is empty) | 1 | data-loss | 5/6 Source-confirmed | 10 | — | — |
| 47 | [#290738](https://github.com/microsoft/vscode/issues/290738) | Github copilot default enables specific tools for agent mode. | 0 | correctness | 4/6 Traced | 10 | — | `npm run implement -- --issue 290738` |
| 55 | [#262771](https://github.com/microsoft/vscode/issues/262771) | Styling mismatch between terminal and general auto approve messages | 0 | visual | 3/6 Plausible | 9 | — | — |
| 64 | [#301600](https://github.com/microsoft/vscode/issues/301600) | queue and steer hotkey tips are backwards | 1 | correctness | 2/6 Unverified | 8 | — | `npm run implement -- --issue 301600` |
| 73 | [#282024](https://github.com/microsoft/vscode/issues/282024) | Investigate global auto approve policy not working properly | 0 | correctness | 3/6 Plausible | 7 | — | `npm run implement -- --issue 282024` |
| 108 | [#277960](https://github.com/microsoft/vscode/issues/277960) | Editing a sensitive file yields a huge confirm dialog | 0 | visual | 3/6 Plausible | 4 | — | `npm run implement -- --issue 277960` |
| 125 | [#269033](https://github.com/microsoft/vscode/issues/269033) | Inline chat for a chat session model picker does not apply to delegated sessions | 0 | papercut | 4/6 Traced | 3 | — | `npm run implement -- --issue 269033` |
| 132 | [#289019](https://github.com/microsoft/vscode/issues/289019) | "Allow for ..." should approve other calls that match in the parallel tool calls | 0 | papercut | 5/6 Source-confirmed | 3 | — | `npm run implement -- --issue 289019` |
| 133 | [#289580](https://github.com/microsoft/vscode/issues/289580) | Allow and stop reviewing result should be preserved as choice in dropdown | 0 | papercut | 2/6 Unverified | 3 | — | — |
| 136 | [#300625](https://github.com/microsoft/vscode/issues/300625) | Input/output confirmation cuts off text | 0 | visual | 5/6 Source-confirmed | 3 | yes | `npm run implement -- --issue 300625` |
| 143 | [#264977](https://github.com/microsoft/vscode/issues/264977) | Low maxInputTokens gives no lowest priority node found error | 1 | papercut | 3/6 Plausible | 2 | — | `npm run implement -- --issue 264977` |
| 144 | [#277743](https://github.com/microsoft/vscode/issues/277743) | Chat: Add actual path for "model wants to edit files outside of your workspace" | 1 | papercut | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 277743` |
| 168 | [#291067](https://github.com/microsoft/vscode/issues/291067) | Auto-approval information not viewable with screenreader | 0 | papercut | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 291067` |
| 169 | [#293485](https://github.com/microsoft/vscode/issues/293485) | Prompted every time I close a window | 0 | papercut | 6/6 Confirmed | 2 | — | `npm run implement -- --issue 293485` |
| 200 | [#280545](https://github.com/microsoft/vscode/issues/280545) | Duplicate URIs when approving URL pattern | 0 | visual | 2/6 Unverified | 1 | — | — |
| 203 | [#286390](https://github.com/microsoft/vscode/issues/286390) | No stop button available while terminal runs | 0 | visual | 3/6 Plausible | 1 | — | `npm run implement -- --issue 286390` |
| 207 | [#296172](https://github.com/microsoft/vscode/issues/296172) | Tool picker live-syncs to running agent session | 0 | correctness | 3/6 Plausible | 1 | — | `npm run implement -- --issue 296172` |
| 209 | [#297564](https://github.com/microsoft/vscode/issues/297564) | Steering/queing UI feel very jumpy | 0 | visual | 3/6 Plausible | 1 | — | `npm run implement -- --issue 297564` |
| 257 | [#257667](https://github.com/microsoft/vscode/issues/257667) | Make agent talk less about tools they need to activate | 0 | papercut | — | 0 | — | `npm run implement -- --issue 257667` |
| 259 | [#266284](https://github.com/microsoft/vscode/issues/266284) | Extremely large prompts are completely removed, along with the system prompt. | 0 | correctness | 4/6 Traced | 0 | — | `npm run implement -- --issue 266284` |
| 267 | [#275893](https://github.com/microsoft/vscode/issues/275893) | Chat confirmation buttons should be a toolbar for accessibility | 0 | papercut | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 275893` |
| 279 | [#288201](https://github.com/microsoft/vscode/issues/288201) | "add ___ to chat" doesn't work when chat hasn't been previously opened | 0 | correctness | — | 0 | — | `npm run implement -- --issue 288201` |
| 283 | [#292391](https://github.com/microsoft/vscode/issues/292391) | very large sensitive file confirmation | 0 | papercut | — | 0 | — | `npm run implement -- --issue 292391` |
| 286 | [#295635](https://github.com/microsoft/vscode/issues/295635) | Cmd+enter to approve tool call should work if focus is anywhere in chat view | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 295635` |
| 290 | [#301297](https://github.com/microsoft/vscode/issues/301297) | Can't exit out of modal with Esc | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 301297` |

### CLI and environment (7)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 70 | [#214896](https://github.com/microsoft/vscode/issues/214896) | Quoting issue with command sent to the terminal | 0 | correctness | 5/6 Source-confirmed | 7 | — | — |
| 99 | [#300594](https://github.com/microsoft/vscode/issues/300594) | Git fatal: destination path error due to Windows long paths in Extensions view | 1 | correctness | 3/6 Plausible | 4 | — | `npm run implement -- --issue 300594` |
| 114 | [#321729](https://github.com/microsoft/vscode/issues/321729) | Workspace becomes invalid after running Copilot CLI | 0 | correctness | 3/6 Plausible | 4 | — | `npm run implement -- --issue 321729` |
| 176 | [#316355](https://github.com/microsoft/vscode/issues/316355) | 工作空间异常 | 0 | none | 3/6 Plausible | 2 | — | — |
| 189 | [#239382](https://github.com/microsoft/vscode/issues/239382) | thread 'main' panicked at src/bin/code/main.rs:47:14:..(openssl.cnf incompatibility with system) | 0 | crash | 4/6 Traced | 1 | yes | `npm run implement -- --issue 239382` |
| 201 | [#281052](https://github.com/microsoft/vscode/issues/281052) | CLI crashes when running update with VS Code installed | 0 | crash | 2/6 Unverified | 1 | — | `npm run implement -- --issue 281052` |
| 227 | [#317609](https://github.com/microsoft/vscode/issues/317609) | New Copilot CLI Update is Terrible | 0 | none | 3/6 Plausible | 1 | — | — |

### Other (10)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 26 | [#286455](https://github.com/microsoft/vscode/issues/286455) | documentSelector `json` for LSP-Connection will spam `textDocument/didOpen\|didClose` request for all `package.json` | 0 | perf | 5/6 Source-confirmed | 15 | yes | `npm run implement -- --issue 286455` |
| 69 | [#304439](https://github.com/microsoft/vscode/issues/304439) | Copilot Chat: File editing tools and MCP tool calls produce mojibake when strings contain Unicode characters | 1 | correctness | 3/6 Plausible | 7 | — | `npm run implement -- --issue 304439` |
| 74 | [#286415](https://github.com/microsoft/vscode/issues/286415) | Claude Opus fails to parse schema definitions correctly | 0 | correctness | 2/6 Unverified | 7 | — | `npm run implement -- --issue 286415` |
| 76 | [#251592](https://github.com/microsoft/vscode/issues/251592) | MCP servers removed from extension still show up in VS Code | 2 | correctness | 2/6 Unverified | 6 | — | — |
| 92 | [#291640](https://github.com/microsoft/vscode/issues/291640) | Debug disassembly view sometimes assumes a single contiguous memory space despite instructionReference changes | 0 | correctness | 5/6 Source-confirmed | 5 | — | `npm run implement -- --issue 291640` |
| 104 | [#248435](https://github.com/microsoft/vscode/issues/248435) | Debug on cwd path with exclamation mark and space will fail on second try (when terminal is CWD) | 0 | correctness | 5/6 Source-confirmed | 4 | yes | `npm run implement -- --issue 248435` |
| 107 | [#273893](https://github.com/microsoft/vscode/issues/273893) | Unable to create launch configuration file | 0 | correctness | 2/6 Unverified | 4 | — | — |
| 208 | [#296319](https://github.com/microsoft/vscode/issues/296319) | Persistent suggestions about already-committed changes from different branches | 0 | correctness | 3/6 Plausible | 1 | — | `npm run implement -- --issue 296319` |
| 252 | [#250457](https://github.com/microsoft/vscode/issues/250457) | Tasks.json hover show broken path | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 250457` |
| 275 | [#282407](https://github.com/microsoft/vscode/issues/282407) | Empty stuck diff decorations | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 282407` |

## Feature requests

### MCP configuration (58)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | [#265496](https://github.com/microsoft/vscode/issues/265496) | Add support in vscode for Agent Client Protocol (ACP) | 324 | active | 100 | `npm run implement -- --issue 265496` |
| 23 | [#311001](https://github.com/microsoft/vscode/issues/311001) | Agent Plugins: Add support for "userConfig" to inject inputs into MCP configs. | 9 | backlog-candidate | 4 | `npm run implement -- --issue 311001` |
| 28 | [#252792](https://github.com/microsoft/vscode/issues/252792) | Support Anthropic DXT Format For Packaging &  Installing MCPs | 10 | dormant | 3 | `npm run implement -- --issue 252792` |
| 29 | [#308961](https://github.com/microsoft/vscode/issues/308961) | VSCode MCP Task Compliance - Terrible UX | 8 | active | 3 | `npm run implement -- --issue 308961` |
| 37 | [#251459](https://github.com/microsoft/vscode/issues/251459) | Allow Extensions to Register In-Process MCP Servers via In-Memory Transport | 6 | dormant | 2 | `npm run implement -- --issue 251459` |
| 39 | [#300714](https://github.com/microsoft/vscode/issues/300714) | Allow disabling AI tools and MCPs provided by extensions | 5 | active | 2 | — |
| 40 | [#243940](https://github.com/microsoft/vscode/issues/243940) | MCP: Customize descriptions for server/tools via mcp.json | 4 | dormant | 2 | `npm run implement -- --issue 243940` |
| 41 | [#251747](https://github.com/microsoft/vscode/issues/251747) | Enable Auto-Attach for MCP Prompts / Embedded Resources | 4 | active | 2 | `npm run implement -- --issue 251747` |
| 43 | [#291004](https://github.com/microsoft/vscode/issues/291004) | MCP Resources Not Accessible to AI Agents - Breaking Intended Use Cases | 3 | backlog-candidate | 2 | `npm run implement -- --issue 291004` |
| 44 | [#296596](https://github.com/microsoft/vscode/issues/296596) | MCP gateway: UX for enabling/disabling tools per session | 1 | active | 2 | `npm run implement -- --issue 296596` |
| 46 | [#315190](https://github.com/microsoft/vscode/issues/315190) | AHP/Copilot: builtin GH MCP server | 0 | active | 2 | `npm run implement -- --issue 315190` |
| 60 | [#317697](https://github.com/microsoft/vscode/issues/317697) | Support headersHelper in MCP config | 4 | backlog-candidate | 1 | `npm run implement -- --issue 317697` |
| 62 | [#250074](https://github.com/microsoft/vscode/issues/250074) | Can't use both env and envFile for MCP server configuration | 3 | backlog-candidate | 1 | `npm run implement -- --issue 250074` |
| 66 | [#246039](https://github.com/microsoft/vscode/issues/246039) | Adding an MCP Server from a private NPM doesn't work | 2 | backlog-candidate | 1 | `npm run implement -- --issue 246039` |
| 68 | [#296598](https://github.com/microsoft/vscode/issues/296598) | MCP gateway: Support MCP elicitations | 2 | active | 1 | `npm run implement -- --issue 296598` |
| 86 | [#245909](https://github.com/microsoft/vscode/issues/245909) | MCP support substitutions as command line args | 0 | dormant | 1 | `npm run implement -- --issue 245909` |
| 92 | [#259973](https://github.com/microsoft/vscode/issues/259973) | Allow MCP Servers in non-agent mode | 0 | dormant | 1 | `npm run implement -- --issue 259973` |
| 94 | [#272000](https://github.com/microsoft/vscode/issues/272000) | api: allow mcp extensions to provide a static manifest of metadata | 0 | active | 1 | `npm run implement -- --issue 272000` |
| 95 | [#278301](https://github.com/microsoft/vscode/issues/278301) | MCP: Encourage that MCP servers are installed via marketplace | 0 | backlog-candidate | 1 | `npm run implement -- --issue 278301` |
| 96 | [#278708](https://github.com/microsoft/vscode/issues/278708) | Parallel MCP tools execution triggers multiple oauth logins | 0 | backlog-candidate | 1 | `npm run implement -- --issue 278708` |
| 97 | [#280530](https://github.com/microsoft/vscode/issues/280530) | Ask for a whole metadata of MCP server tool in VS Code API (such as `vscode.lm.tools`) | 0 | backlog-candidate | 1 | `npm run implement -- --issue 280530` |
| 100 | [#305331](https://github.com/microsoft/vscode/issues/305331) | AHP: MCP server configuration | 0 | active | 1 | `npm run implement -- --issue 305331` |
| 130 | [#244064](https://github.com/microsoft/vscode/issues/244064) | Enhance scoping for MCP severs | 1 | dormant | 0 | `npm run implement -- --issue 244064` |
| 131 | [#244166](https://github.com/microsoft/vscode/issues/244166) | MCP: support server sessions connections per-edit session | 1 | active | 0 | `npm run implement -- --issue 244166` |
| 133 | [#266105](https://github.com/microsoft/vscode/issues/266105) | MCP server configurations should be an options map | 1 | dormant | 0 | `npm run implement -- --issue 266105` |
| 138 | [#319330](https://github.com/microsoft/vscode/issues/319330) | Tool virtualization should fully support large MCP servers (100s of tools) via semantic lazy-loading | 1 | active | 0 | `npm run implement -- --issue 319330` |
| 172 | [#244978](https://github.com/microsoft/vscode/issues/244978) | Unified MCP Server Management UI | 0 | dormant | 0 | — |
| 173 | [#245176](https://github.com/microsoft/vscode/issues/245176) | MCP: Clarify the server execution context | 0 | dormant | 0 | `npm run implement -- --issue 245176` |
| 174 | [#246049](https://github.com/microsoft/vscode/issues/246049) | MCP: Expose current git remote as root | 0 | backlog-candidate | 0 | `npm run implement -- --issue 246049` |
| 175 | [#247604](https://github.com/microsoft/vscode/issues/247604) | MCP: Allow the user to dismiss tool usage warning | 0 | dormant | 0 | `npm run implement -- --issue 247604` |
| 176 | [#247968](https://github.com/microsoft/vscode/issues/247968) | MCP client should validate tool descriptions for prompt injections and freeze them. | 0 | dormant | 0 | `npm run implement -- --issue 247968` |
| 177 | [#248969](https://github.com/microsoft/vscode/issues/248969) | MCP: Make it easy for MCP server devs continuously test/benchmark in VS Code | 0 | backlog-candidate | 0 | `npm run implement -- --issue 248969` |
| 178 | [#250461](https://github.com/microsoft/vscode/issues/250461) | Show MCP sampling using on registry page | 0 | dormant | 0 | `npm run implement -- --issue 250461` |
| 180 | [#251559](https://github.com/microsoft/vscode/issues/251559) | Extension API Request: Query and Control MCP Servers and Tools via VS Code Extension API | 0 | backlog-candidate | 0 | `npm run implement -- --issue 251559` |
| 181 | [#251576](https://github.com/microsoft/vscode/issues/251576) | Feature Request: Enhanced Tool Information Display in MCP Configuration | 0 | backlog-candidate | 0 | `npm run implement -- --issue 251576` |
| 182 | [#251726](https://github.com/microsoft/vscode/issues/251726) | Support MCP Debugging with any command (e.g. `bun`, `deno`, `pnpm run server.ts`) | 0 | backlog-candidate | 0 | `npm run implement -- --issue 251726` |
| 183 | [#251741](https://github.com/microsoft/vscode/issues/251741) | Add C++ Debugging to MCP development mode | 0 | backlog-candidate | 0 | `npm run implement -- --issue 251741` |
| 190 | [#261578](https://github.com/microsoft/vscode/issues/261578) | on mcp.json make it easy to see exposed tools from a server | 0 | dormant | 0 | `npm run implement -- --issue 261578` |
| 201 | [#278164](https://github.com/microsoft/vscode/issues/278164) | Need better way to invoke MCP prompt | 0 | backlog-candidate | 0 | `npm run implement -- --issue 278164` |
| 202 | [#278201](https://github.com/microsoft/vscode/issues/278201) | Add an easy way for me to extend an MCP definition contributed by an extension | 0 | dormant | 0 | `npm run implement -- --issue 278201` |
| 203 | [#279704](https://github.com/microsoft/vscode/issues/279704) | Figure out a way to advertise MCP servers contributed by extensions without such a high cost of tokens | 0 | active | 0 | `npm run implement -- --issue 279704` |
| 205 | [#280203](https://github.com/microsoft/vscode/issues/280203) | agent doesn't try re-calling failed MCP | 0 | dormant | 0 | `npm run implement -- --issue 280203` |
| 207 | [#280734](https://github.com/microsoft/vscode/issues/280734) | Allow canceling fetch call on the tool call itself | 0 | backlog-candidate | 0 | `npm run implement -- --issue 280734` |
| 210 | [#283422](https://github.com/microsoft/vscode/issues/283422) | Allow specifying MCP server for `Chat › Tools: Eligible For Auto Approval` configuration | 0 | backlog-candidate | 0 | `npm run implement -- --issue 283422` |
| 212 | [#285623](https://github.com/microsoft/vscode/issues/285623) | Enhanced MCP Tool Response Handling with File Artifacts in Custom Agent Flow | 0 | active | 0 | `npm run implement -- --issue 285623` |
| 213 | [#286033](https://github.com/microsoft/vscode/issues/286033) | Add MCP-Apps-like Support for Extensions Using Language Model Tools in GitHub Copilot | 0 | active | 0 | — |
| 214 | [#287197](https://github.com/microsoft/vscode/issues/287197) | Agent: Allow MCP servers to extend default code search tools | 0 | backlog-candidate | 0 | `npm run implement -- --issue 287197` |
| 219 | [#296597](https://github.com/microsoft/vscode/issues/296597) | MCP gateway: De-duplicate MCP servers from Claude's own config | 0 | active | 0 | `npm run implement -- --issue 296597` |
| 226 | [#302562](https://github.com/microsoft/vscode/issues/302562) | Stale output from MCP tool / App in chat window | 0 | active | 0 | — |
| 229 | [#306247](https://github.com/microsoft/vscode/issues/306247) | Feature Request: UI or wildcard/grouping support for `chat.tools.urls.autoApprove` to reduce settings.json clutter | 0 | active | 0 | — |
| 234 | [#309641](https://github.com/microsoft/vscode/issues/309641) | Feature Request: Lazy inject MCP into agent only when the extension skill is invoked | 0 | active | 0 | — |
| 235 | [#311595](https://github.com/microsoft/vscode/issues/311595) | Add `requestTimeout` option for MCP server tool calls | 0 | active | 0 | `npm run implement -- --issue 311595` |
| 238 | [#316751](https://github.com/microsoft/vscode/issues/316751) | Why does MCP require npx on the host; shouldn't it run in the devcontainer? | 0 | active | 0 | — |
| 239 | [#318559](https://github.com/microsoft/vscode/issues/318559) | Feature Request: Idle Timeout for MCP Servers | 0 | backlog-candidate | 0 | `npm run implement -- --issue 318559` |
| 240 | [#323913](https://github.com/microsoft/vscode/issues/323913) | Feature Request: Per-agent MCP server scoping to reduce context overhead | 0 | active | 0 | `npm run implement -- --issue 323913` |
| 241 | [#324049](https://github.com/microsoft/vscode/issues/324049) | Allow Repository inheritence of MCP Servers like Skills | 0 | active | 0 | `npm run implement -- --issue 324049` |
| 242 | [#325653](https://github.com/microsoft/vscode/issues/325653) | Per-agent MCP server scoping via optional "agents" field in mcp.json | 0 | active | 0 | — |
| 244 | [#326376](https://github.com/microsoft/vscode/issues/326376) | Render Data Agent MCP Embedded Resource Queries in Chat Responses | 0 | active | 0 | `npm run implement -- --issue 326376` |

### Debug sessions (31)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 2 | [#53557](https://github.com/microsoft/vscode/issues/53557) | Shared properties in launch.json | 149 | backlog-candidate | 16 | `npm run implement -- --issue 53557` |
| 7 | [#101791](https://github.com/microsoft/vscode/issues/101791) | Allow DAP progress notifications to be shown more prominently than the status bar | 51 | backlog-candidate | 8 | `npm run implement -- --issue 101791` |
| 9 | [#197287](https://github.com/microsoft/vscode/issues/197287) | Investigate debug visualization extension points | 21 | dormant | 8 | `npm run implement -- --issue 197287` |
| 13 | [#77138](https://github.com/microsoft/vscode/issues/77138) | ability to get/set currently selected debug configuration | 34 | backlog-candidate | 5 | `npm run implement -- --issue 77138` |
| 22 | [#116109](https://github.com/microsoft/vscode/issues/116109) | Investigate debug UI for highly concurrent languages | 11 | dormant | 4 | `npm run implement -- --issue 116109` |
| 25 | [#225483](https://github.com/microsoft/vscode/issues/225483) | Debug view per debug session | 27 | backlog-candidate | 3 | `npm run implement -- --issue 225483` |
| 27 | [#124280](https://github.com/microsoft/vscode/issues/124280) | Provide a smart run/debug command for loose files | 12 | backlog-candidate | 3 | `npm run implement -- --issue 124280` |
| 30 | [#321839](https://github.com/microsoft/vscode/issues/321839) | Add setting to enable automatically focusing newly created debug session | 8 | backlog-candidate | 3 | `npm run implement -- --issue 321839` |
| 31 | [#136792](https://github.com/microsoft/vscode/issues/136792) | Allow Run To Cursor to start debug session | 21 | backlog-candidate | 2 | — |
| 34 | [#63813](https://github.com/microsoft/vscode/issues/63813) | terminal stays open after process exit | 12 | active | 2 | `npm run implement -- --issue 63813` |
| 55 | [#137327](https://github.com/microsoft/vscode/issues/137327) | Debugging on OSX with iTerm as external terminal creates a new window each time | 5 | backlog-candidate | 1 | `npm run implement -- --issue 137327` |
| 56 | [#165165](https://github.com/microsoft/vscode/issues/165165) | Support custom "reverse requests" from debug adapters | 5 | backlog-candidate | 1 | `npm run implement -- --issue 165165` |
| 79 | [#283011](https://github.com/microsoft/vscode/issues/283011) | Make it easy to use Emulate a focused page when debugging Code OSS | 1 | backlog-candidate | 1 | `npm run implement -- --issue 283011` |
| 99 | [#288806](https://github.com/microsoft/vscode/issues/288806) | Improvements to the `Run and Debug: Network` panel | 0 | active | 1 | `npm run implement -- --issue 288806` |
| 107 | [#103330](https://github.com/microsoft/vscode/issues/103330) | Improve debug actions for multi-target debugging | 2 | backlog-candidate | 0 | `npm run implement -- --issue 103330` |
| 108 | [#110067](https://github.com/microsoft/vscode/issues/110067) | Implement Debugger Modules View | 2 | backlog-candidate | 0 | `npm run implement -- --issue 110067` |
| 112 | [#239533](https://github.com/microsoft/vscode/issues/239533) | Allow controlling default stop/disconnect when using debugger | 2 | dormant | 0 | `npm run implement -- --issue 239533` |
| 115 | [#136384](https://github.com/microsoft/vscode/issues/136384) | Expose preRestartTask | 1 | backlog-candidate | 0 | `npm run implement -- --issue 136384` |
| 117 | [#146401](https://github.com/microsoft/vscode/issues/146401) | Profile 2 things at once | 1 | backlog-candidate | 0 | — |
| 119 | [#176282](https://github.com/microsoft/vscode/issues/176282) | Auto-attach remote session | 1 | backlog-candidate | 0 | `npm run implement -- --issue 176282` |
| 125 | [#210304](https://github.com/microsoft/vscode/issues/210304) | Add a preRestartCommand / command equivalents of debug lifecycle hooks | 1 | dormant | 0 | `npm run implement -- --issue 210304` |
| 127 | [#229008](https://github.com/microsoft/vscode/issues/229008) | Adopt new call stack widget for exceptions | 1 | backlog-candidate | 0 | `npm run implement -- --issue 229008` |
| 161 | [#210990](https://github.com/microsoft/vscode/issues/210990) | API to provide a terminal for use with `run-in-terminal` request | 0 | dormant | 0 | `npm run implement -- --issue 210990` |
| 179 | [#250902](https://github.com/microsoft/vscode/issues/250902) | Debug Toolbar missing project in command center | 0 | backlog-candidate | 0 | `npm run implement -- --issue 250902` |
| 187 | [#255629](https://github.com/microsoft/vscode/issues/255629) | Option to disable auto-pause in external Konsole for C# debugger | 0 | backlog-candidate | 0 | — |
| 191 | [#263870](https://github.com/microsoft/vscode/issues/263870) | Enable Text Wrapping in Run and Debug Window | 0 | backlog-candidate | 0 | `npm run implement -- --issue 263870` |
| 196 | [#274078](https://github.com/microsoft/vscode/issues/274078) | Consider adding variablesReference to VSCodeDebugProtocol.EvaluateArguments | 0 | dormant | 0 | `npm run implement -- --issue 274078` |
| 204 | [#280143](https://github.com/microsoft/vscode/issues/280143) | Give extension the ability to know where the current debug session is stopped | 0 | dormant | 0 | `npm run implement -- --issue 280143` |
| 206 | [#280617](https://github.com/microsoft/vscode/issues/280617) | Support actioning session widgets that require input in the session hover | 0 | dormant | 0 | `npm run implement -- --issue 280617` |
| 208 | [#281209](https://github.com/microsoft/vscode/issues/281209) | Allow to investigate stack traces in VS Code Insiders by using source maps | 0 | active | 0 | `npm run implement -- --issue 281209` |
| 221 | [#297374](https://github.com/microsoft/vscode/issues/297374) | Support CDP connections | 0 | active | 0 | `npm run implement -- --issue 297374` |

### Chat edits (35)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 3 | [#295212](https://github.com/microsoft/vscode/issues/295212) | Setting to make side by side diff view the default for changes made by copilot | 43 | backlog-candidate | 15 | `npm run implement -- --issue 295212` |
| 5 | [#262495](https://github.com/microsoft/vscode/issues/262495) | Remove the 'Keep' button in Chat Agent mode and use standard save behavior | 25 | backlog-candidate | 13 | `npm run implement -- --issue 262495` |
| 17 | [#279040](https://github.com/microsoft/vscode/issues/279040) | Allow to use `applyEdit` w/ AI-review UI from tools and also refactorings | 11 | backlog-candidate | 5 | `npm run implement -- --issue 279040` |
| 45 | [#284013](https://github.com/microsoft/vscode/issues/284013) | Restore last chat session improvements | 0 | backlog-candidate | 2 | `npm run implement -- --issue 284013` |
| 67 | [#287715](https://github.com/microsoft/vscode/issues/287715) | Ability to add Copilot-targeted comments on diffs | 2 | active | 1 | `npm run implement -- --issue 287715` |
| 69 | [#298746](https://github.com/microsoft/vscode/issues/298746) | Add deleteFile tool | 2 | active | 1 | `npm run implement -- --issue 298746` |
| 73 | [#252762](https://github.com/microsoft/vscode/issues/252762) | Cannot copy code that the AI wants to remove | 1 | active | 1 | `npm run implement -- --issue 252762` |
| 74 | [#254679](https://github.com/microsoft/vscode/issues/254679) | Enable save participants for files during edit sessions | 1 | backlog-candidate | 1 | `npm run implement -- --issue 254679` |
| 75 | [#265914](https://github.com/microsoft/vscode/issues/265914) | Chat: Support managing tool approvals via command palette | 1 | dormant | 1 | `npm run implement -- --issue 265914` |
| 76 | [#267779](https://github.com/microsoft/vscode/issues/267779) | Edits should be presented in order | 1 | active | 1 | `npm run implement -- --issue 267779` |
| 77 | [#280648](https://github.com/microsoft/vscode/issues/280648) | Allow dragging chat editors to the chat panel | 1 | active | 1 | `npm run implement -- --issue 280648` |
| 88 | [#247901](https://github.com/microsoft/vscode/issues/247901) | Add a "disable" option on tool confirmations | 0 | dormant | 1 | `npm run implement -- --issue 247901` |
| 89 | [#250423](https://github.com/microsoft/vscode/issues/250423) | MCP resource templates need better UI | 0 | backlog-candidate | 1 | `npm run implement -- --issue 250423` |
| 90 | [#250442](https://github.com/microsoft/vscode/issues/250442) | MCP sample confirmation should reuse LM confirmation logic | 0 | dormant | 1 | `npm run implement -- --issue 250442` |
| 91 | [#253787](https://github.com/microsoft/vscode/issues/253787) | Auto confirm for MCP tool call in extension using 'vscode.lm.tools' APIs | 0 | dormant | 1 | `npm run implement -- --issue 253787` |
| 93 | [#266067](https://github.com/microsoft/vscode/issues/266067) | Chat: Invalid/failed tool calls are never shown to the user | 0 | backlog-candidate | 1 | `npm run implement -- --issue 266067` |
| 135 | [#275098](https://github.com/microsoft/vscode/issues/275098) | Difficult to review output - allow summarization? | 1 | dormant | 0 | `npm run implement -- --issue 275098` |
| 184 | [#251886](https://github.com/microsoft/vscode/issues/251886) | github.copilot-chat/panel.action.vote should include model | 0 | backlog-candidate | 0 | `npm run implement -- --issue 251886` |
| 185 | [#253367](https://github.com/microsoft/vscode/issues/253367) | When I haven't set up Copilot in the empty profile, Configure Models Access gives me an empty quick pick | 0 | backlog-candidate | 0 | `npm run implement -- --issue 253367` |
| 186 | [#254879](https://github.com/microsoft/vscode/issues/254879) | Multiple edits to the same file should just be rendered as one | 0 | backlog-candidate | 0 | `npm run implement -- --issue 254879` |
| 189 | [#256912](https://github.com/microsoft/vscode/issues/256912) | [Sampling] Display sampling request to users in chat before sent out | 0 | dormant | 0 | `npm run implement -- --issue 256912` |
| 192 | [#265788](https://github.com/microsoft/vscode/issues/265788) | Add Table of Contents Outline to GitHub Copilot Chat Debug View for Quick Navigation | 0 | dormant | 0 | `npm run implement -- --issue 265788` |
| 194 | [#268585](https://github.com/microsoft/vscode/issues/268585) | Add option to `replaceAll` occurances in multi_replace_string tool | 0 | backlog-candidate | 0 | `npm run implement -- --issue 268585` |
| 197 | [#275106](https://github.com/microsoft/vscode/issues/275106) | Workspace/Session/Global approval view is not very clear | 0 | backlog-candidate | 0 | `npm run implement -- --issue 275106` |
| 200 | [#277665](https://github.com/microsoft/vscode/issues/277665) | Require manual accepting of Copilot Edits | 0 | backlog-candidate | 0 | — |
| 209 | [#281417](https://github.com/microsoft/vscode/issues/281417) | Feature Request From Claude: Add replace_file_contents tool for Copilot Chat agent mode | 0 | active | 0 | `npm run implement -- --issue 281417` |
| 211 | [#284672](https://github.com/microsoft/vscode/issues/284672) | UI: Keep/Undo buttons in chat pane should only impact changes from that thread | 0 | backlog-candidate | 0 | `npm run implement -- --issue 284672` |
| 215 | [#288581](https://github.com/microsoft/vscode/issues/288581) | Chat session trust degradation system | 0 | dormant | 0 | — |
| 216 | [#289320](https://github.com/microsoft/vscode/issues/289320) | Improve Performance of Session History Tooltip in GitHub Copilot Session List | 0 | active | 0 | — |
| 217 | [#293217](https://github.com/microsoft/vscode/issues/293217) | Enable word wrap for tool invocation parameters in GitHub Copilot Chat | 0 | active | 0 | `npm run implement -- --issue 293217` |
| 218 | [#295560](https://github.com/microsoft/vscode/issues/295560) | Approval UI needs to be friction-less to use | 0 | active | 0 | `npm run implement -- --issue 295560` |
| 222 | [#300042](https://github.com/microsoft/vscode/issues/300042) | Steering obliterates applied patch from GPT-5.4 | 0 | active | 0 | — |
| 227 | [#304539](https://github.com/microsoft/vscode/issues/304539) | Copilot Chat "Keep/Discard" creates unsafe state for vibe-coding workflows | 0 | active | 0 | — |
| 230 | [#307349](https://github.com/microsoft/vscode/issues/307349) | Chat session history entry silently unresponsive with no recovery path when session fails to deserialize | 0 | active | 0 | `npm run implement -- --issue 307349` |
| 233 | [#308032](https://github.com/microsoft/vscode/issues/308032) | Customizations window target should default to my current session | 0 | backlog-candidate | 0 | `npm run implement -- --issue 308032` |

### Editor platform (13)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 4 | [#321151](https://github.com/microsoft/vscode/issues/321151) | Make extensions trusted publishers configurable, to optionally include Microsoft, GitHub and Open AI in delayed auto-update | 30 | backlog-candidate | 13 | `npm run implement -- --issue 321151` |
| 6 | [#155597](https://github.com/microsoft/vscode/issues/155597) | Allow users to choose which editor to use for editing variable binary data | 65 | backlog-candidate | 8 | — |
| 11 | [#200270](https://github.com/microsoft/vscode/issues/200270) | Do not autoplay videos in release notes | 35 | backlog-candidate | 6 | `npm run implement -- --issue 200270` |
| 24 | [#251315](https://github.com/microsoft/vscode/issues/251315) | Support JSON schema draft 2020-12 | 4 | active | 4 | `npm run implement -- --issue 251315` |
| 71 | [#130880](https://github.com/microsoft/vscode/issues/130880) | Allow key bindings to work on tree view items | 1 | dormant | 1 | `npm run implement -- --issue 130880` |
| 83 | [#181555](https://github.com/microsoft/vscode/issues/181555) | Proposal: add tagged template literal support for `vscode.l10n` | 0 | backlog-candidate | 1 | `npm run implement -- --issue 181555` |
| 87 | [#246159](https://github.com/microsoft/vscode/issues/246159) | Unify variable substitution features in tasks, mcp, and debug | 0 | backlog-candidate | 1 | `npm run implement -- --issue 246159` |
| 120 | [#184172](https://github.com/microsoft/vscode/issues/184172) | API to access the product configuration | 1 | dormant | 0 | `npm run implement -- --issue 184172` |
| 144 | [#141473](https://github.com/microsoft/vscode/issues/141473) | Auto save behaviour might be unexpected here | 0 | dormant | 0 | `npm run implement -- --issue 141473` |
| 151 | [#185814](https://github.com/microsoft/vscode/issues/185814) | Adopt `GlyphMarginWidget`s | 0 | backlog-candidate | 0 | `npm run implement -- --issue 185814` |
| 162 | [#212802](https://github.com/microsoft/vscode/issues/212802) | Show sticky inline items for list items when horizontal scrolling is enabled | 0 | backlog-candidate | 0 | `npm run implement -- --issue 212802` |
| 170 | [#236308](https://github.com/microsoft/vscode/issues/236308) | Please improve the default style of the checkbox to make it more consistent with the custom theme style and keep the same theme appearance style. | 0 | backlog-candidate | 0 | `npm run implement -- --issue 236308` |
| 193 | [#268369](https://github.com/microsoft/vscode/issues/268369) | Resolving to the current workspace root in the workspace config file. | 0 | backlog-candidate | 0 | `npm run implement -- --issue 268369` |

### Debug inspection (16)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 8 | [#201772](https://github.com/microsoft/vscode/issues/201772) | Allow "Debug Console" editors | 34 | backlog-candidate | 8 | `npm run implement -- --issue 201772` |
| 14 | [#236477](https://github.com/microsoft/vscode/issues/236477) | Debug: Search inside collapsed nodes | 26 | backlog-candidate | 5 | `npm run implement -- --issue 236477` |
| 18 | [#94937](https://github.com/microsoft/vscode/issues/94937) | Truncate and copy large values from the debug console | 26 | backlog-candidate | 4 | `npm run implement -- --issue 94937` |
| 19 | [#284771](https://github.com/microsoft/vscode/issues/284771) | Syntax highlighting in the Disassembly view | 21 | backlog-candidate | 4 | `npm run implement -- --issue 284771` |
| 33 | [#18058](https://github.com/microsoft/vscode/issues/18058) | Evaluate selected expression on hover while debugging? | 15 | backlog-candidate | 2 | `npm run implement -- --issue 18058` |
| 42 | [#279795](https://github.com/microsoft/vscode/issues/279795) | Debug Hover: Node filter for objects | 4 | backlog-candidate | 2 | `npm run implement -- --issue 279795` |
| 48 | [#30065](https://github.com/microsoft/vscode/issues/30065) | Language services should be able to provide debug console IntelliSense | 8 | backlog-candidate | 1 | `npm run implement -- --issue 30065` |
| 49 | [#249932](https://github.com/microsoft/vscode/issues/249932) | Disassembly Viewer: disassemble by specified function/line | 8 | backlog-candidate | 1 | `npm run implement -- --issue 249932` |
| 50 | [#187784](https://github.com/microsoft/vscode/issues/187784) | No way to copy full value from debugger console (repl) | 7 | backlog-candidate | 1 | `npm run implement -- --issue 187784` |
| 84 | [#209677](https://github.com/microsoft/vscode/issues/209677) | Inline editing of debug variables | 0 | backlog-candidate | 1 | `npm run implement -- --issue 209677` |
| 101 | [#134455](https://github.com/microsoft/vscode/issues/134455) | Consider a "test-adapter-protocol" that maps onto the new testing APIs | 5 | dormant | 0 | `npm run implement -- --issue 134455` |
| 110 | [#205821](https://github.com/microsoft/vscode/issues/205821) | Option to auto-expand groups in variables panel while debugging | 2 | backlog-candidate | 0 | `npm run implement -- --issue 205821` |
| 121 | [#206101](https://github.com/microsoft/vscode/issues/206101) | A way to open a file in hex editor from Terminal | 1 | backlog-candidate | 0 | `npm run implement -- --issue 206101` |
| 171 | [#241766](https://github.com/microsoft/vscode/issues/241766) | [Enhancement] In Watch panel: ability to see value on hover? | 0 | dormant | 0 | `npm run implement -- --issue 241766` |
| 198 | [#276268](https://github.com/microsoft/vscode/issues/276268) | Bug Report: Incorrect Copy Behavior for Array/Object Values in JavaScript Debug Terminal | 0 | dormant | 0 | — |
| 243 | [#325902](https://github.com/microsoft/vscode/issues/325902) | Regex support for the debug console filter | 0 | backlog-candidate | 0 | `npm run implement -- --issue 325902` |

### Testing explorer (37)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 10 | [#303308](https://github.com/microsoft/vscode/issues/303308) | Test results panel vertical/horizontal splitting | 24 | backlog-candidate | 7 | `npm run implement -- --issue 303308` |
| 15 | [#205915](https://github.com/microsoft/vscode/issues/205915) | [SUGGESTION] Test Explorer is able to be grouped | 24 | backlog-candidate | 5 | `npm run implement -- --issue 205915` |
| 20 | [#126932](https://github.com/microsoft/vscode/issues/126932) | Support for "related code" in tests | 16 | dormant | 4 | `npm run implement -- --issue 126932` |
| 38 | [#283358](https://github.com/microsoft/vscode/issues/283358) | Running tests should incrementally increase coverage rather than clearing coverage from other tests | 5 | backlog-candidate | 2 | `npm run implement -- --issue 283358` |
| 47 | [#158254](https://github.com/microsoft/vscode/issues/158254) | Allow not automatically saving files when running a test | 16 | backlog-candidate | 1 | `npm run implement -- --issue 158254` |
| 51 | [#133338](https://github.com/microsoft/vscode/issues/133338) | Add code lens option/alternative for native testing | 6 | backlog-candidate | 1 | `npm run implement -- --issue 133338` |
| 52 | [#137737](https://github.com/microsoft/vscode/issues/137737) | Add a command to run/debug tests with the current filter from anywhere | 6 | backlog-candidate | 1 | `npm run implement -- --issue 137737` |
| 59 | [#243468](https://github.com/microsoft/vscode/issues/243468) | Allow additional data (besides duration, such as memory usage) to be recorded against tests and shown in the test runner | 4 | dormant | 1 | `npm run implement -- --issue 243468` |
| 65 | [#227924](https://github.com/microsoft/vscode/issues/227924) | Persisted files associated with a test run | 2 | backlog-candidate | 1 | `npm run implement -- --issue 227924` |
| 72 | [#134452](https://github.com/microsoft/vscode/issues/134452) | Support global evaluation that requires a file for context | 1 | backlog-candidate | 1 | `npm run implement -- --issue 134452` |
| 80 | [#297962](https://github.com/microsoft/vscode/issues/297962) | Provide a way for custom test sessions to be re-run with commands like "Rerun last session" | 1 | active | 1 | `npm run implement -- --issue 297962` |
| 103 | [#130874](https://github.com/microsoft/vscode/issues/130874) | Test UI: Ability to `preserveFocus` when running tests | 4 | backlog-candidate | 0 | — |
| 104 | [#139224](https://github.com/microsoft/vscode/issues/139224) | [Test UI] Support Update | 4 | backlog-candidate | 0 | `npm run implement -- --issue 139224` |
| 106 | [#133198](https://github.com/microsoft/vscode/issues/133198) | [Test UI] [Feature Request] Allow message for skipped() test function | 3 | backlog-candidate | 0 | `npm run implement -- --issue 133198` |
| 109 | [#184444](https://github.com/microsoft/vscode/issues/184444) | Test Explorer: Sort tests by name | 2 | active | 0 | `npm run implement -- --issue 184444` |
| 111 | [#206139](https://github.com/microsoft/vscode/issues/206139) | [Testing API Feature] Add a new api in TestRun to reset test item to its initial state (unknown, not run) | 2 | backlog-candidate | 0 | `npm run implement -- --issue 206139` |
| 113 | [#319500](https://github.com/microsoft/vscode/issues/319500) | option to remove the "Run with Coverage" right click menu item on tests | 2 | backlog-candidate | 0 | `npm run implement -- --issue 319500` |
| 116 | [#141272](https://github.com/microsoft/vscode/issues/141272) | Testing API: allow extension to control sort-order of `TestController`s it contributes | 1 | backlog-candidate | 0 | `npm run implement -- --issue 141272` |
| 118 | [#146799](https://github.com/microsoft/vscode/issues/146799) | Make test message be able to toggle between 'verbose' and 'simple' mode. | 1 | backlog-candidate | 0 | `npm run implement -- --issue 146799` |
| 122 | [#206573](https://github.com/microsoft/vscode/issues/206573) | Add "discover" action in the test tree | 1 | backlog-candidate | 0 | `npm run implement -- --issue 206573` |
| 123 | [#207877](https://github.com/microsoft/vscode/issues/207877) | Testing API > Tags Feedback | 1 | backlog-candidate | 0 | `npm run implement -- --issue 207877` |
| 124 | [#208500](https://github.com/microsoft/vscode/issues/208500) | Allow to stop a test run from the location where I started it | 1 | dormant | 0 | `npm run implement -- --issue 208500` |
| 126 | [#210509](https://github.com/microsoft/vscode/issues/210509) | [Testing] Coverage API Issues: Monorepo & Accumulation | 1 | dormant | 0 | `npm run implement -- --issue 210509` |
| 129 | [#237106](https://github.com/microsoft/vscode/issues/237106) | Configure coverage testing profile | 1 | dormant | 0 | — |
| 145 | [#143331](https://github.com/microsoft/vscode/issues/143331) | [Test UX]: testing time is confusing when running in parallel | 0 | dormant | 0 | `npm run implement -- --issue 143331` |
| 146 | [#150010](https://github.com/microsoft/vscode/issues/150010) | Testing: regarding to refreshHandler | 0 | backlog-candidate | 0 | `npm run implement -- --issue 150010` |
| 150 | [#182788](https://github.com/microsoft/vscode/issues/182788) | Support data driven unit tests in the vscode test runner | 0 | dormant | 0 | `npm run implement -- --issue 182788` |
| 153 | [#187777](https://github.com/microsoft/vscode/issues/187777) | Allow test output to be moved to the editor | 0 | backlog-candidate | 0 | `npm run implement -- --issue 187777` |
| 154 | [#188305](https://github.com/microsoft/vscode/issues/188305) | Test UI should surface continuous run on gutter test icon | 0 | dormant | 0 | `npm run implement -- --issue 188305` |
| 157 | [#195920](https://github.com/microsoft/vscode/issues/195920) | Long/multiline test failure messages are not all readable when using actual/expected diff | 0 | dormant | 0 | `npm run implement -- --issue 195920` |
| 159 | [#203254](https://github.com/microsoft/vscode/issues/203254) | Provide API for skipped ranges in test coverage | 0 | dormant | 0 | `npm run implement -- --issue 203254` |
| 160 | [#207557](https://github.com/microsoft/vscode/issues/207557) | Test API: test run profiles - workspace folder scope? | 0 | dormant | 0 | `npm run implement -- --issue 207557` |
| 163 | [#218252](https://github.com/microsoft/vscode/issues/218252) | Missing theme variables for test coverage highlight background | 0 | backlog-candidate | 0 | — |
| 166 | [#225462](https://github.com/microsoft/vscode/issues/225462) | Suggest: Test Explorer exists by default, but off | 0 | dormant | 0 | `npm run implement -- --issue 225462` |
| 188 | [#256324](https://github.com/microsoft/vscode/issues/256324) | We should show test progress inline inside chat | 0 | dormant | 0 | `npm run implement -- --issue 256324` |
| 195 | [#271567](https://github.com/microsoft/vscode/issues/271567) | In the Test Explorer View, pressing Escape should clear the current filter | 0 | backlog-candidate | 0 | `npm run implement -- --issue 271567` |
| 223 | [#300416](https://github.com/microsoft/vscode/issues/300416) | Support passing a skip reason on TestRun.skipped() | 0 | backlog-candidate | 0 | `npm run implement -- --issue 300416` |

### CLI remote (12)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 21 | [#246885](https://github.com/microsoft/vscode/issues/246885) | auto-clean old versions remote ssh server | 13 | dormant | 4 | `npm run implement -- --issue 246885` |
| 26 | [#231029](https://github.com/microsoft/vscode/issues/231029) | Can no longer install VS Code Server on machines that have no internet access | 19 | dormant | 3 | `npm run implement -- --issue 231029` |
| 36 | [#93241](https://github.com/microsoft/vscode/issues/93241) | Should we use namespacing in the CLI | 8 | backlog-candidate | 2 | `npm run implement -- --issue 93241` |
| 57 | [#184646](https://github.com/microsoft/vscode/issues/184646) | .vscode\cli\ ignores portable mode | 5 | active | 1 | `npm run implement -- --issue 184646` |
| 148 | [#168389](https://github.com/microsoft/vscode/issues/168389) | Add direct download link for GNU x64/arm builds | 0 | dormant | 0 | `npm run implement -- --issue 168389` |
| 149 | [#173558](https://github.com/microsoft/vscode/issues/173558) | Support OpenRC in tunnel service instsall | 0 | backlog-candidate | 0 | `npm run implement -- --issue 173558` |
| 155 | [#191861](https://github.com/microsoft/vscode/issues/191861) | Add `--github-auth` to serve-web | 0 | backlog-candidate | 0 | `npm run implement -- --issue 191861` |
| 156 | [#193328](https://github.com/microsoft/vscode/issues/193328) | allow opening previous projects from terminal like `code -p linux` instead of passing the full path | 0 | backlog-candidate | 0 | `npm run implement -- --issue 193328` |
| 164 | [#219328](https://github.com/microsoft/vscode/issues/219328) | Recognize paths with ~ on Windows | 0 | backlog-candidate | 0 | `npm run implement -- --issue 219328` |
| 165 | [#222404](https://github.com/microsoft/vscode/issues/222404) | Add `code --help -a` | 0 | dormant | 0 | `npm run implement -- --issue 222404` |
| 167 | [#229498](https://github.com/microsoft/vscode/issues/229498) | `Turn on Remote Tunnel Access` account view could show suggestions for accounts to authenticate with | 0 | dormant | 0 | `npm run implement -- --issue 229498` |
| 231 | [#307623](https://github.com/microsoft/vscode/issues/307623) | [Feature Request] CLI API for external tool integration (read workspace, extensions, settings) | 0 | backlog-candidate | 0 | `npm run implement -- --issue 307623` |

### Agent plugins (9)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 58 | [#314940](https://github.com/microsoft/vscode/issues/314940) | Support plugin dependencies for vscode chat marketplaces | 5 | backlog-candidate | 1 | `npm run implement -- --issue 314940` |
| 136 | [#300197](https://github.com/microsoft/vscode/issues/300197) | [Feature Request]Allow extension authors to include plugin installation from any desired location | 1 | backlog-candidate | 0 | `npm run implement -- --issue 300197` |
| 220 | [#297366](https://github.com/microsoft/vscode/issues/297366) | Integrate plugin management to the new Chat Customization dialog | 0 | active | 0 | `npm run implement -- --issue 297366` |
| 224 | [#302030](https://github.com/microsoft/vscode/issues/302030) | AI should know about agent plugins & help to install them | 0 | active | 0 | `npm run implement -- --issue 302030` |
| 225 | [#302033](https://github.com/microsoft/vscode/issues/302033) | Unclear how to install npm plugin | 0 | backlog-candidate | 0 | `npm run implement -- --issue 302033` |
| 228 | [#304758](https://github.com/microsoft/vscode/issues/304758) | Feature request: icon field in agent plugin plugin.json | 0 | active | 0 | `npm run implement -- --issue 304758` |
| 232 | [#307985](https://github.com/microsoft/vscode/issues/307985) | Plugin agent discovery: support filesystem-based auto-discovery of .agent.md files | 0 | active | 0 | — |
| 236 | [#315307](https://github.com/microsoft/vscode/issues/315307) | Add skill for creating plugins | 0 | backlog-candidate | 0 | `npm run implement -- --issue 315307` |
| 237 | [#315902](https://github.com/microsoft/vscode/issues/315902) | Expose Update Plugins/Marketplace in Customization UI | 0 | active | 0 | `npm run implement -- --issue 315902` |

### Breakpoints stepping (13)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 53 | [#252294](https://github.com/microsoft/vscode/issues/252294) | Handle 'removed' BreakpointEvent for instruction breakpoints | 6 | backlog-candidate | 1 | `npm run implement -- --issue 252294` |
| 54 | [#253211](https://github.com/microsoft/vscode/issues/253211) | Support Instruction Breakpoints in the VS Code API | 6 | backlog-candidate | 1 | `npm run implement -- --issue 253211` |
| 61 | [#215944](https://github.com/microsoft/vscode/issues/215944) | Breakpoint classes have no property for triggered breakpoints | 3 | backlog-candidate | 1 | `npm run implement -- --issue 215944` |
| 63 | [#282251](https://github.com/microsoft/vscode/issues/282251) | Allow Ctrl and Shift select functions when deleting breakpoints | 3 | backlog-candidate | 1 | `npm run implement -- --issue 282251` |
| 102 | [#153833](https://github.com/microsoft/vscode/issues/153833) | Allow (modifier)+click for "step in target" | 5 | backlog-candidate | 0 | `npm run implement -- --issue 153833` |
| 128 | [#230705](https://github.com/microsoft/vscode/issues/230705) | Can't create Breakpoint with custom mode from extension | 1 | backlog-candidate | 0 | `npm run implement -- --issue 230705` |
| 134 | [#274072](https://github.com/microsoft/vscode/issues/274072) | Add debug relate menu contribution points | 1 | dormant | 0 | `npm run implement -- --issue 274072` |
| 137 | [#304764](https://github.com/microsoft/vscode/issues/304764) | Expose `mode` property on breakpoint classes to match DAP 1.65 `BreakpointMode` support | 1 | active | 0 | — |
| 141 | [#119481](https://github.com/microsoft/vscode/issues/119481) | Data breakpoints: support modifying current breakpoint access type | 0 | backlog-candidate | 0 | `npm run implement -- --issue 119481` |
| 143 | [#140845](https://github.com/microsoft/vscode/issues/140845) | Proposal: pin specific thread(s) when debugging | 0 | dormant | 0 | `npm run implement -- --issue 140845` |
| 168 | [#232931](https://github.com/microsoft/vscode/issues/232931) | Conditional breakpoint is not being hit with source-mapped TypeScript variables in VSCode | 0 | backlog-candidate | 0 | `npm run implement -- --issue 232931` |
| 169 | [#233302](https://github.com/microsoft/vscode/issues/233302) | node debugger also connects to externally executed node scripts | 0 | dormant | 0 | `npm run implement -- --issue 233302` |
| 199 | [#277217](https://github.com/microsoft/vscode/issues/277217) | Add inline "Run to Cursor" icons during debugging sessions | 0 | backlog-candidate | 0 | `npm run implement -- --issue 277217` |

### Other (20)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 12 | [#272887](https://github.com/microsoft/vscode/issues/272887) | Parallel callstacks | 22 | backlog-candidate | 6 | `npm run implement -- --issue 272887` |
| 16 | [#263279](https://github.com/microsoft/vscode/issues/263279) | Agent Mode: Disable tools by default besides core tools | 14 | backlog-candidate | 5 | `npm run implement -- --issue 263279` |
| 32 | [#138237](https://github.com/microsoft/vscode/issues/138237) | Disassembly editor is not getting closed automatically after debug session ended | 20 | backlog-candidate | 2 | `npm run implement -- --issue 138237` |
| 35 | [#123879](https://github.com/microsoft/vscode/issues/123879) | Debugger: Smart Step Into | 9 | dormant | 2 | `npm run implement -- --issue 123879` |
| 64 | [#290498](https://github.com/microsoft/vscode/issues/290498) | Support linking paths/URIs in the exception popup window | 3 | backlog-candidate | 1 | `npm run implement -- --issue 290498` |
| 70 | [#314079](https://github.com/microsoft/vscode/issues/314079) | Install agent plugin specific version or provide branch name | 2 | active | 1 | `npm run implement -- --issue 314079` |
| 78 | [#281911](https://github.com/microsoft/vscode/issues/281911) | Cached MCP tool list is used for contributed MCP server despite different arguments for starting the process | 1 | dormant | 1 | `npm run implement -- --issue 281911` |
| 81 | [#304269](https://github.com/microsoft/vscode/issues/304269) | Support discovering and installing agent skills from `.well-known` skill indices | 1 | active | 1 | `npm run implement -- --issue 304269` |
| 82 | [#308818](https://github.com/microsoft/vscode/issues/308818) | Persistent prompts about starting and trusting MCP servers | 1 | active | 1 | `npm run implement -- --issue 308818` |
| 85 | [#244814](https://github.com/microsoft/vscode/issues/244814) | Tests that are hidden by default | 0 | backlog-candidate | 1 | `npm run implement -- --issue 244814` |
| 98 | [#283955](https://github.com/microsoft/vscode/issues/283955) | Allow exporting flattened view for LLM's text response and toolcall results | 0 | backlog-candidate | 1 | `npm run implement -- --issue 283955` |
| 105 | [#33861](https://github.com/microsoft/vscode/issues/33861) | introduce "pathMapping" as a more powerful replacement for "remoteRoot/localRoot" | 3 | dormant | 0 | `npm run implement -- --issue 33861` |
| 114 | [#134409](https://github.com/microsoft/vscode/issues/134409) | Add a description to a vscode.TestTag | 1 | backlog-candidate | 0 | `npm run implement -- --issue 134409` |
| 132 | [#265433](https://github.com/microsoft/vscode/issues/265433) | Be smarter about errors from edits | 1 | dormant | 0 | `npm run implement -- --issue 265433` |
| 139 | [#321202](https://github.com/microsoft/vscode/issues/321202) | agent-host: AHP Client UI Library | 1 | active | 0 | `npm run implement -- --issue 321202` |
| 140 | [#71177](https://github.com/microsoft/vscode/issues/71177) | No clue that server ready action is running | 0 | backlog-candidate | 0 | `npm run implement -- --issue 71177` |
| 142 | [#126694](https://github.com/microsoft/vscode/issues/126694) | Register a quickAccessProvider for debug sources | 0 | backlog-candidate | 0 | `npm run implement -- --issue 126694` |
| 147 | [#158575](https://github.com/microsoft/vscode/issues/158575) | Add "Disconnect single session" command | 0 | backlog-candidate | 0 | `npm run implement -- --issue 158575` |
| 152 | [#186319](https://github.com/microsoft/vscode/issues/186319) | [Feature] Debug Hovers Are Not Resizable | 0 | backlog-candidate | 0 | `npm run implement -- --issue 186319` |
| 158 | [#203240](https://github.com/microsoft/vscode/issues/203240) | Allow Extensions to contribute to DebugHoverContext/DebugWatchContext | 0 | backlog-candidate | 0 | `npm run implement -- --issue 203240` |
