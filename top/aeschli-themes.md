# Top issues by theme — aeschli

Experimental themed view of [the flat ranking](aeschli.md); themes assigned by the review engine. Rank/score are the lane-wide values. Generated 2026-07-03 20:55 UTC.

## Bugs

### WSL and remote connectivity (19)

| # | Issue | Title | 👍 | Severity | Score | Auto-fix |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | [#157275](https://github.com/microsoft/vscode/issues/157275) | Unable to connect to VS Code server: Error in request - ENOENT /run/user/1000/vscode-ipc-*.sock | 28 | correctness | 100 | yes |
| 5 | [#298221](https://github.com/microsoft/vscode/issues/298221) | Cannot reconnect in WSL window after hibernation | 9 | correctness | 64 | — |
| 6 | [#316459](https://github.com/microsoft/vscode/issues/316459) | Remote-WSL 0.104.3 fails with `navigator is now a global in nodejs` / `PendingMigrationError`, then WebSocket 1006 when connecting to WSL | 4 | correctness | 38 | — |
| 25 | [#193603](https://github.com/microsoft/vscode/issues/193603) | [wsl] Can't run `code .` when offline and VS Code got updated | 3 | correctness | 12 | — |
| 26 | [#265301](https://github.com/microsoft/vscode/issues/265301) | When WSL is closed / crashes, all open instances of VSCode have to be closed completely - reload window and attempting to reconnect fails | 2 | correctness | 12 | — |
| 41 | [#269702](https://github.com/microsoft/vscode/issues/269702) | Unable to run code from wsl1 | 0 | correctness | 8 | — |
| 54 | [#320045](https://github.com/microsoft/vscode/issues/320045) | Error: VSCode Server fails, if update fails to download | 0 | correctness | 7 | — |
| 61 | [#292355](https://github.com/microsoft/vscode/issues/292355) | The file read error while using the vscode with wsl. | 0 | correctness | 6 | — |
| 71 | [#188134](https://github.com/microsoft/vscode/issues/188134) | Inconsistent naming for WSL projects in right-click taskbar menu | 1 | visual | 4 | yes |
| 72 | [#197637](https://github.com/microsoft/vscode/issues/197637) | '--no-proxy-server' command line argument does not work | 1 | correctness | 4 | yes |
| 73 | [#209601](https://github.com/microsoft/vscode/issues/209601) | code serve web --server-base-path PWA app does not include base path | 1 | correctness | 4 | yes |
| 75 | [#236348](https://github.com/microsoft/vscode/issues/236348) | `vscode://vscode-remote/wsl+<distro>/path/to/file` des not use already open window | 1 | correctness | 4 | — |
| 76 | [#121799](https://github.com/microsoft/vscode/issues/121799) | [remote][connection] Allow offline editing in Remote-WSL | 0 | correctness | 4 | — |
| 77 | [#123421](https://github.com/microsoft/vscode/issues/123421) | Couldn't open two folders with almost equal names, except for capitalization on Windows via SSH | 0 | correctness | 4 | yes |
| 78 | [#164638](https://github.com/microsoft/vscode/issues/164638) | Server process leaks after closing VS Code with Remote Tunnel Access On | 0 | correctness | 4 | — |
| 149 | [#318088](https://github.com/microsoft/vscode/issues/318088) | VS Code removes existing WSL server before successfully downloading new version, causing permanent WSL connection failure if network is blocked | 0 | correctness | 1 | — |
| 166 | [#167742](https://github.com/microsoft/vscode/issues/167742) | [remote tunnels] no notification shows up | 0 | correctness | 0 | — |
| 171 | [#187046](https://github.com/microsoft/vscode/issues/187046) | [wsl] Crash when launching from wsl with `--verbose` | 0 | crash | 0 | yes |
| 199 | [#307368](https://github.com/microsoft/vscode/issues/307368) | Remote tunnel connection broken after each update | 0 | correctness | 0 | — |

### Linked editing and rename (13)

| # | Issue | Title | 👍 | Severity | Score | Auto-fix |
| --- | --- | --- | --- | --- | --- | --- |
| 2 | [#180156](https://github.com/microsoft/vscode/issues/180156) | [linked editing] Linked editing stops syncing on quick edits | 30 | correctness | 94 | — |
| 3 | [#184829](https://github.com/microsoft/vscode/issues/184829) | JSX Linked Editing not working with Vim extension | 21 | correctness | 73 | yes |
| 4 | [#208276](https://github.com/microsoft/vscode/issues/208276) | [linked rename] Linked Editing does't work well | 16 | correctness | 72 | yes |
| 37 | [#247235](https://github.com/microsoft/vscode/issues/247235) | Deleting JSX tag name and then typing a different tag name doesn't update closing tag | 0 | correctness | 9 | yes |
| 84 | [#140868](https://github.com/microsoft/vscode/issues/140868) | [linked editing] stops when tag name gets empty and end tag is on same line | 4 | papercut | 3 | yes |
| 90 | [#216626](https://github.com/microsoft/vscode/issues/216626) | Deleting lines when editor.linkedEditing is enabled leads to inconsistent results | 1 | correctness | 3 | yes |
| 123 | [#92964](https://github.com/microsoft/vscode/issues/92964) | [rename on type] option-delete and pasting creates 2 undo stops | 0 | papercut | 1 | — |
| 126 | [#127521](https://github.com/microsoft/vscode/issues/127521) | [linked editing] does not work right after enter | 0 | papercut | 1 | — |
| 159 | [#93006](https://github.com/microsoft/vscode/issues/93006) | [rename on type] strange behavior with auto indent in closing tag | 0 | visual | 0 | — |
| 160 | [#93872](https://github.com/microsoft/vscode/issues/93872) | [rename on type] feedback incorrect after Rename | 0 | visual | 0 | yes |
| 161 | [#110580](https://github.com/microsoft/vscode/issues/110580) | [rename on type] stops when composing characters | 0 | correctness | 0 | yes |
| 170 | [#184985](https://github.com/microsoft/vscode/issues/184985) | Manual linked editing doesn't seem to work | 0 | correctness | 0 | yes |
| 175 | [#239351](https://github.com/microsoft/vscode/issues/239351) | Renaming paired tags doesn't work if you clear the tag completely | 0 | correctness | 0 | yes |

### Plan and handoff sessions (13)

| # | Issue | Title | 👍 | Severity | Score | Auto-fix |
| --- | --- | --- | --- | --- | --- | --- |
| 7 | [#311802](https://github.com/microsoft/vscode/issues/311802) | Start implementation posts into current Plan session instead of handing off to implementation | 5 | correctness | 37 | — |
| 30 | [#295976](https://github.com/microsoft/vscode/issues/295976) | "Proceed from plan" section missing when session is reopened | 0 | correctness | 11 | — |
| 36 | [#312195](https://github.com/microsoft/vscode/issues/312195) | Unwanted code insertion during analysis only mode | 1 | correctness | 9 | — |
| 42 | [#275344](https://github.com/microsoft/vscode/issues/275344) | Can't actually save prompt from `/savePrompt` with a manual save | 0 | correctness | 8 | — |
| 56 | [#296255](https://github.com/microsoft/vscode/issues/296255) | Chat Handoff should not change when switching mode | 1 | correctness | 6 | — |
| 65 | [#299044](https://github.com/microsoft/vscode/issues/299044) | [Plan Mode] Claude Sonnet 4.6 executes tool calls instead of outputting text-only plan | 1 | correctness | 5 | — |
| 91 | [#286555](https://github.com/microsoft/vscode/issues/286555) | Switching to a competed session with handoff (like Plan) doesn't show handoffs | 1 | correctness | 3 | — |
| 106 | [#267828](https://github.com/microsoft/vscode/issues/267828) | Dragging a prompt file in to chat behaves as if I invoked it | 0 | correctness | 2 | — |
| 108 | [#272988](https://github.com/microsoft/vscode/issues/272988) | Agent handoffs: prompt should not overriden existing chat input text | 0 | papercut | 2 | yes |
| 113 | [#299185](https://github.com/microsoft/vscode/issues/299185) | Error when trying to save a plan | 0 | correctness | 2 | — |
| 138 | [#283179](https://github.com/microsoft/vscode/issues/283179) | When clicking "Apply edits" file gets create with wrong name/location | 0 | correctness | 1 | — |
| 180 | [#275338](https://github.com/microsoft/vscode/issues/275338) | `/savePrompt` should more clearly reveal created prompt | 0 | papercut | 0 | — |
| 183 | [#280995](https://github.com/microsoft/vscode/issues/280995) | prompt file (slash command) won't use intended agent if run with "run in new chat" | 0 | correctness | 0 | — |

### Copilot instructions and prompt files (22)

| # | Issue | Title | 👍 | Severity | Score | Auto-fix |
| --- | --- | --- | --- | --- | --- | --- |
| 8 | [#286920](https://github.com/microsoft/vscode/issues/286920) | GitHub Copilot doesn't reflect usage of custom prompt | 0 | correctness | 30 | — |
| 9 | [#277934](https://github.com/microsoft/vscode/issues/277934) | GitHub Copilot fails to process workspace when multiple identical copilot-instructions.md files are present | 7 | correctness | 28 | yes |
| 11 | [#292933](https://github.com/microsoft/vscode/issues/292933) | Copilot Chat's LLM tools ignore copilot-instructions.md more often than they follow them. | 3 | correctness | 28 | — |
| 16 | [#304903](https://github.com/microsoft/vscode/issues/304903) | Problems pane constantly re-evaluates frontmatter diagnostics for custom agent/instruction/skill/prompt files — excessive CPU and memory | 3 | perf | 20 | — |
| 19 | [#303564](https://github.com/microsoft/vscode/issues/303564) | Instructions included with every user message | 1 | perf | 17 | — |
| 20 | [#290178](https://github.com/microsoft/vscode/issues/290178) | prompts-diagnostics-provider reports valid relative links as "File not found" in copilot-instructions.md | 1 | correctness | 16 | yes |
| 22 | [#304101](https://github.com/microsoft/vscode/issues/304101) | User-level .instructions.md files with applyTo "**" discovered but not automatically included in chat requests | 0 | correctness | 15 | — |
| 29 | [#285308](https://github.com/microsoft/vscode/issues/285308) | *.instructions.md not read automatically, files not navigated | 0 | correctness | 11 | — |
| 38 | [#252789](https://github.com/microsoft/vscode/issues/252789) | Lose custom instructions I retry after a window reload | 0 | correctness | 9 | — |
| 49 | [#316838](https://github.com/microsoft/vscode/issues/316838) | Copilot Instructions are Ignored | 1 | correctness | 7 | — |
| 55 | [#276227](https://github.com/microsoft/vscode/issues/276227) | Weird Prompt file linting error: No link definition found | 1 | papercut | 6 | yes |
| 107 | [#270650](https://github.com/microsoft/vscode/issues/270650) | Copilot Agent prompts fail when chat.useNestedAgentsMdFiles is enabled with SSH FS folders | 0 | correctness | 2 | — |
| 109 | [#276773](https://github.com/microsoft/vscode/issues/276773) | Filename case-sensitivity in discovery of AGENTS.md files isn't consistent | 0 | correctness | 2 | — |
| 110 | [#281799](https://github.com/microsoft/vscode/issues/281799) | Chat: Custom instruction causes fetch and Allow dialog | 0 | papercut | 2 | — |
| 115 | [#308571](https://github.com/microsoft/vscode/issues/308571) | Fails to load my instructions.md file | 0 | none | 2 | — |
| 116 | [#318701](https://github.com/microsoft/vscode/issues/318701) | chat.instructionsFilesLocations: applyTo frontmatter changes not reflected until VS Code restart (stale cache) | 0 | correctness | 2 | — |
| 145 | [#305180](https://github.com/microsoft/vscode/issues/305180) | VS code (1.113) stopped showing me `user profile` prompt files from my UserData on windows | 0 | correctness | 1 | — |
| 147 | [#308367](https://github.com/microsoft/vscode/issues/308367) | prompts-diagnostics-provider: false "File not found" errors for existing .md links in multi-root workspace | 0 | papercut | 1 | yes |
| 151 | [#323094](https://github.com/microsoft/vscode/issues/323094) | AGENTS.md discovery still runs `rg --no-ignore --follow` over the whole tree (regression sibling of #304676) | 0 | perf | 1 | — |
| 189 | [#294543](https://github.com/microsoft/vscode/issues/294543) | GPT models always read every instruction file | 0 | papercut | 0 | — |
| 192 | [#299480](https://github.com/microsoft/vscode/issues/299480) | Does not load copilot-instructions.md | 0 | correctness | 0 | — |
| 194 | [#300113](https://github.com/microsoft/vscode/issues/300113) | Personal CLAUDE.md is attached even though its empty | 0 | papercut | 0 | — |

### Custom agents and plugins (23)

| # | Issue | Title | 👍 | Severity | Score | Auto-fix |
| --- | --- | --- | --- | --- | --- | --- |
| 10 | [#312256](https://github.com/microsoft/vscode/issues/312256) | bug: Custom agents duplicated in agent picker when same name exists in both org-synced and local paths | 5 | correctness | 28 | — |
| 12 | [#317276](https://github.com/microsoft/vscode/issues/317276) | Custom agent selection silently reverts to generic Agent mid-session; chat dropdown still shows the stale (correct) selection while the runtime has switched | 3 | correctness | 27 | — |
| 14 | [#306227](https://github.com/microsoft/vscode/issues/306227) | Copilot Agent Skill Validation Conflicts with "skill" Language ID (Cadence SKILL Programming Language) | 4 | correctness | 24 | yes |
| 31 | [#321765](https://github.com/microsoft/vscode/issues/321765) | Custom agent frontmatter is not automatically loaded on VSCode startup. | 0 | correctness | 11 | — |
| 45 | [#311329](https://github.com/microsoft/vscode/issues/311329) | Custom subagent resolves to model outside its configured model list | 0 | correctness | 8 | — |
| 48 | [#312254](https://github.com/microsoft/vscode/issues/312254) | Agents: Plan doesn't show up as a custom agent type | 1 | correctness | 7 | — |
| 57 | [#314020](https://github.com/microsoft/vscode/issues/314020) | chat plugins: Claude-format plugin frontmatter (rules `paths`, agents `tools`/`model`) is not transformed when installed via marketplace or pluginLocations | 1 | correctness | 6 | — |
| 62 | [#323728](https://github.com/microsoft/vscode/issues/323728) | slash command blocks input - Copilot Chat with Agent Host, Claude Agent SDK | 0 | correctness | 6 | — |
| 81 | [#289206](https://github.com/microsoft/vscode/issues/289206) | runSubagent picks the wrong subagent | 0 | correctness | 4 | — |
| 87 | [#318422](https://github.com/microsoft/vscode/issues/318422) | Duplicate Copilot agents shown when contributed by both VS Code extension and Copilot CLI plugin | 2 | papercut | 3 | — |
| 96 | [#315032](https://github.com/microsoft/vscode/issues/315032) | Subagent fails to resolve custom OAI model although available for main agent | 0 | correctness | 3 | — |
| 114 | [#306644](https://github.com/microsoft/vscode/issues/306644) | Subagents are not being discovered | 0 | correctness | 2 | — |
| 118 | [#320993](https://github.com/microsoft/vscode/issues/320993) | Agents Window: Custom agents disappear from dropdown after sending a message | 0 | correctness | 2 | — |
| 141 | [#291094](https://github.com/microsoft/vscode/issues/291094) | custom agent model - unexpected fallback to Auto when model is unavailable | 0 | correctness | 1 | — |
| 148 | [#311567](https://github.com/microsoft/vscode/issues/311567) | [Possible Regression] Custom agent MCP tools not available when invoked as sub-agent via Task tool | 0 | correctness | 1 | — |
| 150 | [#319702](https://github.com/microsoft/vscode/issues/319702) | Clicking on "Plugins" in Agents window opens generic customizations view instead of Plugins view | 0 | correctness | 1 | — |
| 185 | [#289427](https://github.com/microsoft/vscode/issues/289427) | Agent doesn't use enough subagents when research/tasks can be done parallel | 0 | none | 0 | — |
| 186 | [#290762](https://github.com/microsoft/vscode/issues/290762) | Custom Agents: Models in defined in custom agent do not lead to different models showing in models picker, should they? | 0 | none | 0 | — |
| 188 | [#294230](https://github.com/microsoft/vscode/issues/294230) | Docs: Clarify agent identifier in custom agents handoffs documentation | 0 | papercut | 0 | — |
| 195 | [#302865](https://github.com/microsoft/vscode/issues/302865) | Hooks not getting invoked from plugins installed from agentplugins marketplace | 0 | correctness | 0 | — |
| 197 | [#306285](https://github.com/microsoft/vscode/issues/306285) | Custom Agent selection spontaneously resets to default when plugin auto update is enabled | 0 | papercut | 0 | — |
| 205 | [#321461](https://github.com/microsoft/vscode/issues/321461) | agent window updates UI in multiple stages | 0 | visual | 0 | — |
| 209 | [#323929](https://github.com/microsoft/vscode/issues/323929) | Custom agents disappear and reappear in v1.126 | 0 | correctness | 0 | — |

### Tools and skills configuration (20)

| # | Issue | Title | 👍 | Severity | Score | Auto-fix |
| --- | --- | --- | --- | --- | --- | --- |
| 13 | [#267413](https://github.com/microsoft/vscode/issues/267413) | When using user defined tool sets shows wrong count | 5 | visual | 26 | — |
| 18 | [#292260](https://github.com/microsoft/vscode/issues/292260) | Notebook tools added without being enabled by the user | 1 | correctness | 17 | — |
| 39 | [#291746](https://github.com/microsoft/vscode/issues/291746) | AI Agent Skills cannot read symbolic links | 0 | correctness | 9 | — |
| 43 | [#302181](https://github.com/microsoft/vscode/issues/302181) | Skills duplication when 'Agent Skills Location' overlaps with 'Plugin Locations' | 0 | papercut | 8 | — |
| 44 | [#305876](https://github.com/microsoft/vscode/issues/305876) | chat.promptFilesLocations ordering ignored | 0 | correctness | 8 | yes |
| 50 | [#321758](https://github.com/microsoft/vscode/issues/321758) | Customizations: Built-in skills are readonly with agents host | 1 | papercut | 7 | — |
| 51 | [#282750](https://github.com/microsoft/vscode/issues/282750) | Remember workspace specific tool disablement | 0 | correctness | 7 | — |
| 52 | [#288698](https://github.com/microsoft/vscode/issues/288698) | Tool picker doesn't work properly when editing a prompt | 0 | correctness | 7 | — |
| 53 | [#305994](https://github.com/microsoft/vscode/issues/305994) | execution_subagent doesn't have skill context | 0 | correctness | 7 | — |
| 59 | [#256906](https://github.com/microsoft/vscode/issues/256906) | Tool Picker has all tools enabled, but Add Context shows old tools list | 0 | correctness | 6 | — |
| 60 | [#260556](https://github.com/microsoft/vscode/issues/260556) | Configure tools... action should respect the tools I configured in my markdown file | 0 | papercut | 6 | yes |
| 112 | [#297587](https://github.com/microsoft/vscode/issues/297587) | Tool descriptions don't mention any languages | 0 | papercut | 2 | — |
| 144 | [#301382](https://github.com/microsoft/vscode/issues/301382) | "Skipping duplicate agent skill name" log spam | 0 | papercut | 1 | — |
| 146 | [#306240](https://github.com/microsoft/vscode/issues/306240) | Github Copilot warnings | 0 | papercut | 1 | — |
| 181 | [#275525](https://github.com/microsoft/vscode/issues/275525) | Invalid autocomplete options in tools array | 0 | papercut | 0 | — |
| 182 | [#275628](https://github.com/microsoft/vscode/issues/275628) | Every tool is selected after reloading if I open the tools list too early during startup | 0 | correctness | 0 | yes |
| 190 | [#298131](https://github.com/microsoft/vscode/issues/298131) | Tools frontmatter on do not work with toolsets that have mcp tools. Only built in work | 0 | correctness | 0 | — |
| 200 | [#308887](https://github.com/microsoft/vscode/issues/308887) | Chat/Configure Tools/Update Tools disables OK button, unless fold tool | 0 | papercut | 0 | — |
| 202 | [#319160](https://github.com/microsoft/vscode/issues/319160) | Inconsistent tool list syntax between "Configure Tools..." CodeLens and tools icon for custom agents | 0 | papercut | 0 | — |
| 206 | [#323036](https://github.com/microsoft/vscode/issues/323036) | Skills in user dir do not show up in the chat input | 0 | — | 0 | — |

### HTML language features (23)

| # | Issue | Title | 👍 | Severity | Score | Auto-fix |
| --- | --- | --- | --- | --- | --- | --- |
| 15 | [#169117](https://github.com/microsoft/vscode/issues/169117) | [html] "Cannot redeclare block-scoped variable" in script type module | 5 | correctness | 23 | yes |
| 24 | [#273226](https://github.com/microsoft/vscode/issues/273226) | [html] completions: better handle unclosed string literals | 0 | correctness | 14 | — |
| 27 | [#137938](https://github.com/microsoft/vscode/issues/137938) | [html] "Auto Closing Tags" adds unnecessary tags in some cases with prettier-vscode | 2 | correctness | 11 | — |
| 63 | [#79631](https://github.com/microsoft/vscode/issues/79631) | [html] don't validate custom event handlers as JavaScript | 11 | papercut | 5 | yes |
| 69 | [#233806](https://github.com/microsoft/vscode/issues/233806) | [html] False error of inline Javascript in HTML | 0 | correctness | 5 | yes |
| 74 | [#229357](https://github.com/microsoft/vscode/issues/229357) | [html] Vscode detect wrong scope for script with type=module | 1 | correctness | 4 | yes |
| 80 | [#267871](https://github.com/microsoft/vscode/issues/267871) | [html] problem range in embedded content needs to be limited to embedded range. | 0 | correctness | 4 | yes |
| 89 | [#71091](https://github.com/microsoft/vscode/issues/71091) | [html] bracket matching in strings | 1 | visual | 3 | — |
| 92 | [#171153](https://github.com/microsoft/vscode/issues/171153) | [html] validation error on JavaScript block comment with arrow in HTML script | 0 | correctness | 3 | yes |
| 98 | [#272091](https://github.com/microsoft/vscode/issues/272091) | [html] Auto-complete in embedded JavaScript does not work when no space is present | 1 | papercut | 2 | — |
| 124 | [#111025](https://github.com/microsoft/vscode/issues/111025) | [html] HTML line wrapping on paste occurs before auto-indenting | 0 | correctness | 1 | — |
| 125 | [#111760](https://github.com/microsoft/vscode/issues/111760) | [html] handle HTML-escaped characters in JavaScript attribute properties | 0 | correctness | 1 | yes |
| 132 | [#210303](https://github.com/microsoft/vscode/issues/210303) | [html] Format does not work if script tag parameters do not have quotes | 0 | correctness | 1 | — |
| 134 | [#225545](https://github.com/microsoft/vscode/issues/225545) | [html] Relative links don't work with <base> element | 0 | correctness | 1 | yes |
| 135 | [#227764](https://github.com/microsoft/vscode/issues/227764) | [html] highlighting does not detect end script tag in string literals | 0 | correctness | 1 | — |
| 155 | [#77923](https://github.com/microsoft/vscode/issues/77923) | [html] auto close tags being inserted before its html content | 0 | correctness | 0 | — |
| 156 | [#78893](https://github.com/microsoft/vscode/issues/78893) | [html] autoclose not working properly with multicursor | 0 | correctness | 0 | — |
| 162 | [#135849](https://github.com/microsoft/vscode/issues/135849) | [html] Unexpected "Declaration or statement expected" in HTML code | 0 | correctness | 0 | yes |
| 163 | [#156656](https://github.com/microsoft/vscode/issues/156656) | [html] Duplicate double quotes are inserted for HTML attributes when working over SSH | 0 | papercut | 0 | — |
| 168 | [#173086](https://github.com/microsoft/vscode/issues/173086) | [html] format on paste removes whitespace | 0 | papercut | 0 | — |
| 172 | [#188623](https://github.com/microsoft/vscode/issues/188623) | [html] Links with fragment can't be Ctrl+clicked | 0 | correctness | 0 | — |
| 173 | [#213628](https://github.com/microsoft/vscode/issues/213628) | [html] Formatting Breaks with Space Between Commented Lines in Script Tag | 0 | papercut | 0 | — |
| 178 | [#269346](https://github.com/microsoft/vscode/issues/269346) | [html] Incorrect onclick attribute Parsing | 0 | correctness | 0 | yes |

### CSS and SCSS language features (18)

| # | Issue | Title | 👍 | Severity | Score | Auto-fix |
| --- | --- | --- | --- | --- | --- | --- |
| 17 | [#126507](https://github.com/microsoft/vscode/issues/126507) | [scss] map value override => identifier expected | 6 | correctness | 17 | — |
| 35 | [#184666](https://github.com/microsoft/vscode/issues/184666) | Toggle line comment doesn't work for multiple lines in CSS | 2 | correctness | 9 | — |
| 46 | [#129487](https://github.com/microsoft/vscode/issues/129487) | [css] Wrong selector specificity values with :where | 4 | correctness | 7 | — |
| 68 | [#189156](https://github.com/microsoft/vscode/issues/189156) | [scss] Cannot open `.scss` files using `@use` import syntax | 0 | correctness | 5 | — |
| 70 | [#119290](https://github.com/microsoft/vscode/issues/119290) | [scss] SCSS Validator doesn't like brackets | 2 | correctness | 4 | — |
| 99 | [#71813](https://github.com/microsoft/vscode/issues/71813) | [css] highlighting not working for some transition properties | 0 | visual | 2 | yes |
| 102 | [#149667](https://github.com/microsoft/vscode/issues/149667) | [scss] don't autocomplete in comments | 0 | papercut | 2 | — |
| 105 | [#245579](https://github.com/microsoft/vscode/issues/245579) | [scss] "Follow link" on `@use`/`@import` statements with absolute paths not working with node_modules. | 0 | correctness | 2 | — |
| 120 | [#144767](https://github.com/microsoft/vscode/issues/144767) | [scss] variables in @media parsing | 1 | papercut | 1 | — |
| 121 | [#227452](https://github.com/microsoft/vscode/issues/227452) | [scss] inbuild sass/scss extension shows error that is none | 1 | papercut | 1 | — |
| 129 | [#145701](https://github.com/microsoft/vscode/issues/145701) | [css] Inconsistent results when formatting range/selection | 0 | correctness | 1 | — |
| 130 | [#169900](https://github.com/microsoft/vscode/issues/169900) | [scss] Display a wrong selector preview when using sibling combinators in SCSS, Less | 0 | visual | 1 | — |
| 136 | [#236215](https://github.com/microsoft/vscode/issues/236215) | [css] `:after' suggested inside comment | 0 | papercut | 1 | — |
| 154 | [#74068](https://github.com/microsoft/vscode/issues/74068) | [css] Wrong selector specificity values with :nth-child(even) and :nth-child(odd) | 0 | — | 0 | — |
| 157 | [#78978](https://github.com/microsoft/vscode/issues/78978) | [css] SCSS/SASS Auto Intellisense doesn't work after last entry | 0 | correctness | 0 | — |
| 164 | [#160987](https://github.com/microsoft/vscode/issues/160987) | [scss] Wrongly shown selector in SCSS | 0 | papercut | 0 | — |
| 165 | [#163649](https://github.com/microsoft/vscode/issues/163649) | [less] support `each` in keyframes | 0 | papercut | 0 | — |
| 167 | [#172233](https://github.com/microsoft/vscode/issues/172233) | [css] missing colon causes error to be placed on next rule | 0 | papercut | 0 | — |

### Folding (16)

| # | Issue | Title | 👍 | Severity | Score | Auto-fix |
| --- | --- | --- | --- | --- | --- | --- |
| 21 | [#194806](https://github.com/microsoft/vscode/issues/194806) | [folding] Editor expands when a folding provider comes in with delay | 2 | visual | 15 | yes |
| 23 | [#266597](https://github.com/microsoft/vscode/issues/266597) | editor.removeManualFoldingRanges should support empty selection | 1 | correctness | 14 | yes |
| 28 | [#245849](https://github.com/microsoft/vscode/issues/245849) | [folding] folding gets messed up after Copilot edits a file | 1 | correctness | 11 | — |
| 33 | [#132784](https://github.com/microsoft/vscode/issues/132784) | [folding] Newlines created by Insert Line Above command get sucked into previous code fold | 1 | correctness | 10 | — |
| 34 | [#165266](https://github.com/microsoft/vscode/issues/165266) | [folidng] python ranges unfold when the folding ranges are coming late | 2 | correctness | 9 | yes |
| 40 | [#324163](https://github.com/microsoft/vscode/issues/324163) | Agentic AI ruins folding / collapsing | 0 | correctness | 9 | — |
| 58 | [#75726](https://github.com/microsoft/vscode/issues/75726) | [folding] folding indicators missing for folded code | 0 | correctness | 6 | — |
| 64 | [#201431](https://github.com/microsoft/vscode/issues/201431) | [folding] Manual folding range not useful after copy-paste | 1 | papercut | 5 | — |
| 101 | [#122657](https://github.com/microsoft/vscode/issues/122657) | [folding] region ranges not restored when editor is opened the first time. | 0 | correctness | 2 | — |
| 104 | [#192775](https://github.com/microsoft/vscode/issues/192775) | [folding] Imports are not collapsed added first | 0 | papercut | 2 | yes |
| 133 | [#215958](https://github.com/microsoft/vscode/issues/215958) | [folding] pasting over collapsed blocks leaves random lines collapsed | 0 | visual | 1 | — |
| 139 | [#289224](https://github.com/microsoft/vscode/issues/289224) | vscode corrupts source code when toggling comments on folded regions | 0 | none | 1 | — |
| 152 | [#41538](https://github.com/microsoft/vscode/issues/41538) | [folding] "Select all Occurrences" bug | 0 | — | 0 | — |
| 153 | [#46654](https://github.com/microsoft/vscode/issues/46654) | [folding] Fold block comments scrolls editor | 0 | papercut | 0 | — |
| 176 | [#246388](https://github.com/microsoft/vscode/issues/246388) | Git: deletion marker in the gutter disappears when folding adjacent regions | 0 | visual | 0 | yes |
| 203 | [#319286](https://github.com/microsoft/vscode/issues/319286) | [folding] Format large file unfold all code | 0 | correctness | 0 | — |

### JSON schema and validation (8)

| # | Issue | Title | 👍 | Severity | Score | Auto-fix |
| --- | --- | --- | --- | --- | --- | --- |
| 32 | [#45207](https://github.com/microsoft/vscode/issues/45207) | [json] External schemas referenced from schema not updated | 3 | correctness | 10 | — |
| 47 | [#42679](https://github.com/microsoft/vscode/issues/42679) | [json] schema Validation/Intellisense very slow when JSON deep and Schema Complex | 3 | perf | 7 | — |
| 67 | [#167939](https://github.com/microsoft/vscode/issues/167939) | "editor.inlineSuggest.enabled" add extra quote when using tab in a "workbench.colorCustomizations" settings | 0 | correctness | 5 | — |
| 88 | [#43195](https://github.com/microsoft/vscode/issues/43195) | [json] launch.json completion for "type" does not include expected values | 1 | correctness | 3 | — |
| 103 | [#184904](https://github.com/microsoft/vscode/issues/184904) | [json] Schema changes not reflected if schema file has jsonc extension. | 0 | correctness | 2 | yes |
| 119 | [#109141](https://github.com/microsoft/vscode/issues/109141) | [json] symlink prevents JSON schema from updating validation | 1 | papercut | 1 | — |
| 127 | [#136645](https://github.com/microsoft/vscode/issues/136645) | [json] Explorer Outline view shows wrong int values when viewing JSON document | 0 | correctness | 1 | — |
| 131 | [#189802](https://github.com/microsoft/vscode/issues/189802) | [json] validation not working for a large enough number | 0 | correctness | 1 | — |

### Copilot performance and reliability (12)

| # | Issue | Title | 👍 | Severity | Score | Auto-fix |
| --- | --- | --- | --- | --- | --- | --- |
| 82 | [#290814](https://github.com/microsoft/vscode/issues/290814) | broken copilot | 0 | none | 4 | — |
| 83 | [#305545](https://github.com/microsoft/vscode/issues/305545) | Latest Copilot release causes Extreme HIGH CPU usage | 0 | perf | 4 | — |
| 95 | [#285754](https://github.com/microsoft/vscode/issues/285754) | Unable to prevent GitHub Copilot from editing files. | 0 | correctness | 3 | — |
| 142 | [#291496](https://github.com/microsoft/vscode/issues/291496) | GPT-5-Codex (Preview) runaway halucinations and obstinate disobediance. | 0 | correctness | 1 | — |
| 143 | [#292095](https://github.com/microsoft/vscode/issues/292095) | Permission to read prompt file already attached? | 0 | papercut | 1 | — |
| 187 | [#293458](https://github.com/microsoft/vscode/issues/293458) | Didn't do anything | 0 | none | 0 | — |
| 191 | [#299288](https://github.com/microsoft/vscode/issues/299288) | Agent uses web fetch tool to access instructions | 0 | correctness | 0 | — |
| 193 | [#300066](https://github.com/microsoft/vscode/issues/300066) | Not working | 0 | none | 0 | — |
| 196 | [#305375](https://github.com/microsoft/vscode/issues/305375) | User prompt triggers "allow reading external file" | 0 | papercut | 0 | — |
| 198 | [#307149](https://github.com/microsoft/vscode/issues/307149) | Skill triggers external file allow dialog | 0 | papercut | 0 | — |
| 204 | [#319586](https://github.com/microsoft/vscode/issues/319586) | This is the current issue i am facing as vs code is lagging a lot | 0 | data-loss | 0 | — |
| 208 | [#323765](https://github.com/microsoft/vscode/issues/323765) | "Try Again" in Chat does not allow selection of new model | 0 | correctness | 0 | — |

### Other (22)

| # | Issue | Title | 👍 | Severity | Score | Auto-fix |
| --- | --- | --- | --- | --- | --- | --- |
| 66 | [#306812](https://github.com/microsoft/vscode/issues/306812) | White flash when reloading window & using Dark theme | 1 | visual | 5 | — |
| 79 | [#189129](https://github.com/microsoft/vscode/issues/189129) | [themes] Theme is getting switched on switching profiles | 0 | correctness | 4 | — |
| 85 | [#149478](https://github.com/microsoft/vscode/issues/149478) | Some keyboard shortcuts ignored in Safari/vscode.dev | 2 | none | 3 | — |
| 86 | [#243110](https://github.com/microsoft/vscode/issues/243110) | "Insert At Cursor" should be disabled when no text editor is opened | 2 | papercut | 3 | yes |
| 93 | [#182627](https://github.com/microsoft/vscode/issues/182627) | Recent entry URL can get too large for Windows jumplist | 0 | correctness | 3 | yes |
| 94 | [#243826](https://github.com/microsoft/vscode/issues/243826) | theme-seti overrides langauge extension icons by file extension, not by language | 0 | visual | 3 | — |
| 97 | [#184679](https://github.com/microsoft/vscode/issues/184679) | Fuzzy search not working well in Recent Folders quickpick in 1.79.0 | 1 | papercut | 2 | — |
| 100 | [#115672](https://github.com/microsoft/vscode/issues/115672) | Twisties appear only after the view has loaded for the view | 0 | visual | 2 | — |
| 111 | [#286877](https://github.com/microsoft/vscode/issues/286877) | Rendering code blocks that include `// filepath:` is buggy. | 0 | correctness | 2 | — |
| 117 | [#319919](https://github.com/microsoft/vscode/issues/319919) | workbench.colorTheme getting wiped when switching profiles | 0 | correctness | 2 | — |
| 122 | [#303254](https://github.com/microsoft/vscode/issues/303254) | Repeated custom-agent rescans emit endless parse errors/diagnostics for cross-tool .agent.md files | 1 | papercut | 1 | — |
| 128 | [#142373](https://github.com/microsoft/vscode/issues/142373) | `Recently opened` project names get changed randomly | 0 | visual | 1 | — |
| 137 | [#280873](https://github.com/microsoft/vscode/issues/280873) | bad api doc continuations for rust | 0 | papercut | 1 | — |
| 140 | [#290423](https://github.com/microsoft/vscode/issues/290423) | Chat references show literal "Unknown variable type" placeholder | 0 | visual | 1 | — |
| 158 | [#86299](https://github.com/microsoft/vscode/issues/86299) | [themes] IconTheme doesn't work with spaces in names | 0 | correctness | 0 | — |
| 169 | [#177363](https://github.com/microsoft/vscode/issues/177363) | The material icons of folders in the HTML files are not displayed. Did anyone have such a problem? | 0 | visual | 0 | — |
| 174 | [#227484](https://github.com/microsoft/vscode/issues/227484) | Custom controls need to provide proper textual name, role, and state information | 0 | papercut | 0 | — |
| 177 | [#255388](https://github.com/microsoft/vscode/issues/255388) | Wrong file icon rendering in Files & Folders picker | 0 | visual | 0 | — |
| 179 | [#269406](https://github.com/microsoft/vscode/issues/269406) | Automatic synchronization with Windows High Contrast mode | 0 | — | 0 | yes |
| 184 | [#285872](https://github.com/microsoft/vscode/issues/285872) | Custom Agent references multiple tools using 'search' | 0 | correctness | 0 | — |
| 201 | [#318005](https://github.com/microsoft/vscode/issues/318005) | Customizations loader doesn't validate path or available file system provider | 0 | correctness | 0 | — |
| 207 | [#323130](https://github.com/microsoft/vscode/issues/323130) | The command panel contains content of deleted files | 0 | — | 0 | — |

## Feature requests

### Syntax and grammar engines (4)

| # | Issue | Title | 👍 | Signal | Score |
| --- | --- | --- | --- | --- | --- |
| 1 | [#50140](https://github.com/microsoft/vscode/issues/50140) | Support syntax highlighting with tree-sitter | 736 | backlog-candidate | 100 |
| 17 | [#242156](https://github.com/microsoft/vscode/issues/242156) | Add basic toml support | 53 | backlog-candidate | 10 |
| 26 | [#216](https://github.com/microsoft/vscode/issues/216) | [grammars] provide alternative to TextMate grammars | 50 | backlog-candidate | 7 |
| 277 | [#197881](https://github.com/microsoft/vscode/issues/197881) | [languages] contribution point `languages` provide the ability to extends | 0 | backlog-candidate | 0 |

### JSON language support (47)

| # | Issue | Title | 👍 | Signal | Score |
| --- | --- | --- | --- | --- | --- |
| 2 | [#155379](https://github.com/microsoft/vscode/issues/155379) | [json] support meta-schema features | 357 | backlog-candidate | 43 |
| 8 | [#98724](https://github.com/microsoft/vscode/issues/98724) | [json] JSONSchema draft 2019-09 support | 147 | backlog-candidate | 16 |
| 13 | [#165219](https://github.com/microsoft/vscode/issues/165219) | [json] Support json-schema draft 2020-12 | 107 | backlog-candidate | 14 |
| 16 | [#236814](https://github.com/microsoft/vscode/issues/236814) | [json] Automatically Escape Pasted Text in JSON string | 58 | backlog-candidate | 10 |
| 30 | [#224581](https://github.com/microsoft/vscode/issues/224581) | [json] colorize string literals based on language information coming from schemas | 34 | backlog-candidate | 6 |
| 54 | [#69545](https://github.com/microsoft/vscode/issues/69545) | [json] add commas automatically | 26 | backlog-candidate | 3 |
| 55 | [#124393](https://github.com/microsoft/vscode/issues/124393) | [json] show number of children in JSON arrays | 25 | backlog-candidate | 3 |
| 56 | [#74943](https://github.com/microsoft/vscode/issues/74943) | [json] Override/disable json-schema for package.json | 24 | backlog-candidate | 3 |
| 62 | [#251315](https://github.com/microsoft/vscode/issues/251315) | Support JSON schema draft 2020-12 | 4 | active | 3 |
| 63 | [#26289](https://github.com/microsoft/vscode/issues/26289) | [json] use the schemastore catalog | 23 | backlog-candidate | 2 |
| 64 | [#36280](https://github.com/microsoft/vscode/issues/36280) | [html] JSON edit support inside HTML document / script tag with type="application/json" | 20 | backlog-candidate | 2 |
| 67 | [#76505](https://github.com/microsoft/vscode/issues/76505) | [json] format on save should remove last trailing comma in JSON with json-language-features | 18 | backlog-candidate | 2 |
| 69 | [#42758](https://github.com/microsoft/vscode/issues/42758) | [json] improve property suggestions with oneOf | 15 | backlog-candidate | 2 |
| 71 | [#230136](https://github.com/microsoft/vscode/issues/230136) | [json] Add support for extensions associating JSON schemas with documents dynamically (via API) | 7 | backlog-candidate | 2 |
| 74 | [#24869](https://github.com/microsoft/vscode/issues/24869) | [json] option to format code with leading commas | 17 | backlog-candidate | 1 |
| 75 | [#11828](https://github.com/microsoft/vscode/issues/11828) | [json] validation doesn't work offline | 16 | backlog-candidate | 1 |
| 93 | [#138546](https://github.com/microsoft/vscode/issues/138546) | [json] open definition in JSON document to navigate to the schema definition | 5 | backlog-candidate | 1 |
| 126 | [#44135](https://github.com/microsoft/vscode/issues/44135) | [json] schema fileMatch for all *.json files in root folder | 5 | backlog-candidate | 0 |
| 127 | [#96120](https://github.com/microsoft/vscode/issues/96120) | [json] support setting schema associations at runtime | 5 | backlog-candidate | 0 |
| 130 | [#81782](https://github.com/microsoft/vscode/issues/81782) | [json] allow $ref in confiuguration schemas | 4 | backlog-candidate | 0 |
| 133 | [#139538](https://github.com/microsoft/vscode/issues/139538) | [json] support references in schema associations | 4 | backlog-candidate | 0 |
| 136 | [#42786](https://github.com/microsoft/vscode/issues/42786) | [json] Automatically add required fields to object | 3 | backlog-candidate | 0 |
| 155 | [#208647](https://github.com/microsoft/vscode/issues/208647) | [jsonl] Support `JSON` formatter in `JSONL` | 2 | backlog-candidate | 0 |
| 166 | [#71115](https://github.com/microsoft/vscode/issues/71115) | [json] Provide support for highlighting the source of the error in json files rather than highlighting the entire file | 1 | backlog-candidate | 0 |
| 174 | [#116540](https://github.com/microsoft/vscode/issues/116540) | [json] support link on $ref for external references | 1 | backlog-candidate | 0 |
| 175 | [#117013](https://github.com/microsoft/vscode/issues/117013) | [json] NPM package for vscode-json-languageserver not sync'd with VSCode releases | 1 | backlog-candidate | 0 |
| 177 | [#120629](https://github.com/microsoft/vscode/issues/120629) | [json] Pick part of JSON schema with more matching properties | 1 | backlog-candidate | 0 |
| 185 | [#227592](https://github.com/microsoft/vscode/issues/227592) | [json] Intellisense doesn't suggest objects as a possibility when next to string enums | 1 | backlog-candidate | 0 |
| 204 | [#40604](https://github.com/microsoft/vscode/issues/40604) | [json] suggest used values when property name has already been used | 0 | backlog-candidate | 0 |
| 212 | [#47197](https://github.com/microsoft/vscode/issues/47197) | [json] completion has bad replacement span, overwrites comment | 0 | backlog-candidate | 0 |
| 215 | [#53454](https://github.com/microsoft/vscode/issues/53454) | [json] don't suggest top level snippet if there's already an object | 0 | backlog-candidate | 0 |
| 240 | [#105998](https://github.com/microsoft/vscode/issues/105998) | [json] Format selection doesn't fix indentation | 0 | backlog-candidate | 0 |
| 241 | [#109984](https://github.com/microsoft/vscode/issues/109984) | [json] UI for anyOf settings tooltips needs improvement | 0 | backlog-candidate | 0 |
| 242 | [#110794](https://github.com/microsoft/vscode/issues/110794) | [json] no IntelliSense when all-optional branch matches | 0 | backlog-candidate | 0 |
| 254 | [#125147](https://github.com/microsoft/vscode/issues/125147) | [json] Add enumSortText for JSON schemas | 0 | backlog-candidate | 0 |
| 256 | [#127226](https://github.com/microsoft/vscode/issues/127226) | [json] create diagnostics text out of markdownDeprecationMessage | 0 | dormant | 0 |
| 257 | [#128971](https://github.com/microsoft/vscode/issues/128971) | [json] create links for values of format `uri-reference` | 0 | backlog-candidate | 0 |
| 258 | [#135552](https://github.com/microsoft/vscode/issues/135552) | [json editing] don't remove the comments of the next property node when removing first property | 0 | backlog-candidate | 0 |
| 269 | [#155101](https://github.com/microsoft/vscode/issues/155101) | [json] Show key value pairs of JSON Array in `Outline` view | 0 | backlog-candidate | 0 |
| 271 | [#175090](https://github.com/microsoft/vscode/issues/175090) | [json] warn if a color that requires opacity doesn't set it | 0 | backlog-candidate | 0 |
| 278 | [#209023](https://github.com/microsoft/vscode/issues/209023) | [json] Provide a way to disable the json-validation contribution point of a specific extension (e.g. ESLint) | 0 | backlog-candidate | 0 |
| 279 | [#219855](https://github.com/microsoft/vscode/issues/219855) | [json] allow to override & replace existing schemas | 0 | backlog-candidate | 0 |
| 282 | [#228528](https://github.com/microsoft/vscode/issues/228528) | [json] builtin json formatter doesn't support format-on-paste | 0 | backlog-candidate | 0 |
| 287 | [#249624](https://github.com/microsoft/vscode/issues/249624) | [json] JSON Schema anyOf error reporting is misleading | 0 | backlog-candidate | 0 |
| 295 | [#252610](https://github.com/microsoft/vscode/issues/252610) | expose the `jsonSchemaRegistry` in the extension API | 0 | backlog-candidate | 0 |
| 315 | [#269250](https://github.com/microsoft/vscode/issues/269250) | [json] show a notification when retrying to load a schema fails | 0 | backlog-candidate | 0 |
| 336 | [#284339](https://github.com/microsoft/vscode/issues/284339) | Allow .json files to support comments when a specific comment line is at the top of the file. | 0 | backlog-candidate | 0 |

### Theming and icons (44)

| # | Issue | Title | 👍 | Signal | Score |
| --- | --- | --- | --- | --- | --- |
| 3 | [#12493](https://github.com/microsoft/vscode/issues/12493) | [icon-themes] Support for globs in file associations (Icon themes) | 361 | backlog-candidate | 32 |
| 5 | [#20652](https://github.com/microsoft/vscode/issues/20652) | [themes] different themes for different filetypes | 301 | backlog-candidate | 28 |
| 6 | [#32813](https://github.com/microsoft/vscode/issues/32813) | [theming] Access theme's colors programmatically | 290 | backlog-candidate | 28 |
| 7 | [#25986](https://github.com/microsoft/vscode/issues/25986) | [theming] Separate workbench theme and syntax theme | 193 | backlog-candidate | 18 |
| 12 | [#32579](https://github.com/microsoft/vscode/issues/32579) | [themes] Disable Italic Option Feature Request | 150 | backlog-candidate | 14 |
| 14 | [#26128](https://github.com/microsoft/vscode/issues/26128) | [theming] Allow theming workbench fonts | 141 | backlog-candidate | 13 |
| 18 | [#44026](https://github.com/microsoft/vscode/issues/44026) | [theming] customize file icons in settings | 97 | backlog-candidate | 9 |
| 22 | [#271485](https://github.com/microsoft/vscode/issues/271485) | Reconsider adding settings for preferred icon theme for light and dark modes | 35 | backlog-candidate | 8 |
| 41 | [#92736](https://github.com/microsoft/vscode/issues/92736) | [themes] Allow gradients along with colors | 45 | backlog-candidate | 4 |
| 46 | [#200451](https://github.com/microsoft/vscode/issues/200451) | [themes] globally change saturation and contrast | 28 | backlog-candidate | 4 |
| 57 | [#263108](https://github.com/microsoft/vscode/issues/263108) | Surface the vscode://schemas/color-theme schema to allow for programmatic use | 24 | backlog-candidate | 3 |
| 59 | [#188989](https://github.com/microsoft/vscode/issues/188989) | [themes] mark favorites themes | 23 | backlog-candidate | 3 |
| 61 | [#97063](https://github.com/microsoft/vscode/issues/97063) | [semantic] proposals for new standard semantic token types | 7 | backlog-candidate | 3 |
| 65 | [#56855](https://github.com/microsoft/vscode/issues/56855) | [themes] Allow custom variables and references in workbench color customizations section | 19 | backlog-candidate | 2 |
| 77 | [#45963](https://github.com/microsoft/vscode/issues/45963) | [icon themes] Expose API to provide a dynamic icon theme. | 14 | backlog-candidate | 1 |
| 78 | [#72945](https://github.com/microsoft/vscode/issues/72945) | [themes] Support for hue, saturation, lightness (HSL) color codes for theming | 14 | backlog-candidate | 1 |
| 97 | [#105247](https://github.com/microsoft/vscode/issues/105247) | [theme] allow variables in the color theme definition file | 4 | backlog-candidate | 1 |
| 114 | [#305685](https://github.com/microsoft/vscode/issues/305685) | Using "Toggle between Light/Dark Themes" resets theme | 2 | active | 1 |
| 129 | [#78758](https://github.com/microsoft/vscode/issues/78758) | [themes] Show extension info in Preferences: Color Theme panel | 4 | backlog-candidate | 0 |
| 134 | [#28299](https://github.com/microsoft/vscode/issues/28299) | [theme] Request the feature: "editor.lineHighlightForeground". | 3 | backlog-candidate | 0 |
| 138 | [#62637](https://github.com/microsoft/vscode/issues/62637) | [theme] inspect tool for workbench colors | 3 | backlog-candidate | 0 |
| 147 | [#74342](https://github.com/microsoft/vscode/issues/74342) | [themes] Allow to set a background color for settings / webview editors | 2 | backlog-candidate | 0 |
| 150 | [#101556](https://github.com/microsoft/vscode/issues/101556) | [themes] 'Generate Color Theme From Current Settings' omits semantic token settings | 2 | dormant | 0 |
| 151 | [#103109](https://github.com/microsoft/vscode/issues/103109) | [theming] token type hierarchy to the 'Developer: Inspect Editor Tokens and Scopes' command | 2 | backlog-candidate | 0 |
| 152 | [#177650](https://github.com/microsoft/vscode/issues/177650) | [icon-themes] explore using attribute selectors to allow name patterns and simplify implementation | 2 | backlog-candidate | 0 |
| 154 | [#188594](https://github.com/microsoft/vscode/issues/188594) | [themes] support non-HEX formats in color customizations | 2 | backlog-candidate | 0 |
| 159 | [#305166](https://github.com/microsoft/vscode/issues/305166) | Support for native, context-aware File and Folder Icons (JetBrains-style) | 2 | active | 0 |
| 178 | [#128565](https://github.com/microsoft/vscode/issues/128565) | [semantic highlighting] Source language suffix should be added to semantic token fallback scopes when looked up | 1 | backlog-candidate | 0 |
| 198 | [#318198](https://github.com/microsoft/vscode/issues/318198) | Default themes should not include markdown suffix | 1 | active | 0 |
| 202 | [#26130](https://github.com/microsoft/vscode/issues/26130) | [theming] Theming for workbench icons | 0 | dormant | 0 |
| 203 | [#38145](https://github.com/microsoft/vscode/issues/38145) | [icons] allow name specific root folder icons | 0 | dormant | 0 |
| 226 | [#84486](https://github.com/microsoft/vscode/issues/84486) | [themes] provide command to change theme | 0 | backlog-candidate | 0 |
| 228 | [#86308](https://github.com/microsoft/vscode/issues/86308) | [themes] Minimal icon theme should use icon font | 0 | backlog-candidate | 0 |
| 234 | [#94269](https://github.com/microsoft/vscode/issues/94269) | [semantic tokens] provide code assist for tokenModifiers | 0 | backlog-candidate | 0 |
| 244 | [#111616](https://github.com/microsoft/vscode/issues/111616) | [theme icons] Include color class in ThemeIcon.asClassName() | 0 | backlog-candidate | 0 |
| 245 | [#117437](https://github.com/microsoft/vscode/issues/117437) | [product icon themes] No fallback for using icon contribution point | 0 | backlog-candidate | 0 |
| 246 | [#117822](https://github.com/microsoft/vscode/issues/117822) | [product icon themes] theme icons support for vscode.show(Information\|Warning\|Error)Message | 0 | backlog-candidate | 0 |
| 263 | [#145677](https://github.com/microsoft/vscode/issues/145677) | [themes] Preserve my search for theme search in marketplace | 0 | backlog-candidate | 0 |
| 284 | [#228977](https://github.com/microsoft/vscode/issues/228977) | [themes] support sematic colorization for 'excludedCode' | 0 | backlog-candidate | 0 |
| 290 | [#250444](https://github.com/microsoft/vscode/issues/250444) | Add a custom icon for prompt, chat mode and instruction files | 0 | backlog-candidate | 0 |
| 310 | [#266685](https://github.com/microsoft/vscode/issues/266685) | Add support for SVGs for product icons | 0 | backlog-candidate | 0 |
| 347 | [#304880](https://github.com/microsoft/vscode/issues/304880) | Individual project theming | 0 | active | 0 |
| 357 | [#319847](https://github.com/microsoft/vscode/issues/319847) | Feature request: Panel-specific themes in VS Code / Copilot | 0 | backlog-candidate | 0 |
| 360 | [#323840](https://github.com/microsoft/vscode/issues/323840) | Expose themeVariables of the built-in mermaid-markdown-features extension in user settings | 0 | active | 0 |

### Code folding (58)

| # | Issue | Title | 👍 | Signal | Score |
| --- | --- | --- | --- | --- | --- |
| 4 | [#3352](https://github.com/microsoft/vscode/issues/3352) | [folding] Collapse ending brace to the same line | 308 | backlog-candidate | 28 |
| 19 | [#128912](https://github.com/microsoft/vscode/issues/128912) | [folding] Allow to fold all method bodies | 81 | backlog-candidate | 9 |
| 21 | [#40338](https://github.com/microsoft/vscode/issues/40338) | [folding] configure initial collapse state | 85 | backlog-candidate | 8 |
| 24 | [#63972](https://github.com/microsoft/vscode/issues/63972) | [folding] Move line up/down should skip over folded regions or folded sections | 70 | backlog-candidate | 7 |
| 25 | [#130250](https://github.com/microsoft/vscode/issues/130250) | [folding] Show number of lines folded | 64 | backlog-candidate | 7 |
| 32 | [#33449](https://github.com/microsoft/vscode/issues/33449) | [folding] Automatic function/method folding | 57 | backlog-candidate | 5 |
| 33 | [#16082](https://github.com/microsoft/vscode/issues/16082) | [folding] retain folded state on copy/paste | 53 | backlog-candidate | 5 |
| 34 | [#36002](https://github.com/microsoft/vscode/issues/36002) | [folding] allow defining folding regions in user settings and/or extensions | 53 | backlog-candidate | 5 |
| 37 | [#272740](https://github.com/microsoft/vscode/issues/272740) | [folding] [json] Show number of collapsed array/object items | 25 | backlog-candidate | 5 |
| 44 | [#70794](https://github.com/microsoft/vscode/issues/70794) | [folding] custom folding text for folded ranges | 38 | backlog-candidate | 4 |
| 47 | [#208368](https://github.com/microsoft/vscode/issues/208368) | [folding] fold only code | 24 | backlog-candidate | 4 |
| 49 | [#24515](https://github.com/microsoft/vscode/issues/24515) | [folding] Folding HTML tags should hide the closing tag. | 35 | backlog-candidate | 3 |
| 51 | [#134911](https://github.com/microsoft/vscode/issues/134911) | [folding] Add `unfold level [number]` | 29 | backlog-candidate | 3 |
| 52 | [#31966](https://github.com/microsoft/vscode/issues/31966) | [folding] show comment first line for folded sections | 28 | backlog-candidate | 3 |
| 53 | [#60670](https://github.com/microsoft/vscode/issues/60670) | [folding] show folding actions at the end of folding range as well | 28 | backlog-candidate | 3 |
| 66 | [#58658](https://github.com/microsoft/vscode/issues/58658) | [folding] go to region command | 18 | backlog-candidate | 2 |
| 68 | [#19690](https://github.com/microsoft/vscode/issues/19690) | [folding] show folding lines | 17 | backlog-candidate | 2 |
| 80 | [#59657](https://github.com/microsoft/vscode/issues/59657) | [folding] clicking on on line number of folded line should select full folding range | 13 | backlog-candidate | 1 |
| 81 | [#64721](https://github.com/microsoft/vscode/issues/64721) | [folding] Preview folded content on hover | 13 | backlog-candidate | 1 |
| 82 | [#85783](https://github.com/microsoft/vscode/issues/85783) | [folding] add command unfold block comments | 13 | backlog-candidate | 1 |
| 84 | [#75819](https://github.com/microsoft/vscode/issues/75819) | [folding] Fold current level | 9 | backlog-candidate | 1 |
| 85 | [#91600](https://github.com/microsoft/vscode/issues/91600) | [folding] pressing Enter in collapsed region should add new line outside region | 9 | backlog-candidate | 1 |
| 87 | [#29155](https://github.com/microsoft/vscode/issues/29155) | [folding] Allow to show amount of lines folded | 8 | backlog-candidate | 1 |
| 88 | [#54631](https://github.com/microsoft/vscode/issues/54631) | [folding] Add keyboard shortcut to jump between #region and #endregion | 7 | backlog-candidate | 1 |
| 89 | [#78004](https://github.com/microsoft/vscode/issues/78004) | [folding] When you cut a collapsed code block it should stays collapsed when you paste/drop it. | 7 | backlog-candidate | 1 |
| 90 | [#48556](https://github.com/microsoft/vscode/issues/48556) | [folding] fold all but comments | 6 | backlog-candidate | 1 |
| 91 | [#72422](https://github.com/microsoft/vscode/issues/72422) | [folding] selecting first line of folded range does not select full folded range | 6 | backlog-candidate | 1 |
| 98 | [#190879](https://github.com/microsoft/vscode/issues/190879) | [folding] Folding is clickable on the whole foldable region in the gutter | 4 | backlog-candidate | 1 |
| 131 | [#83458](https://github.com/microsoft/vscode/issues/83458) | [folding] Improve #region support: make it look like Visual Studio IDE | 4 | backlog-candidate | 0 |
| 135 | [#38149](https://github.com/microsoft/vscode/issues/38149) | [folding] Hover can show region description on `#endregion` | 3 | backlog-candidate | 0 |
| 137 | [#55252](https://github.com/microsoft/vscode/issues/55252) | [folding] provide non-selection aware fold level command | 3 | backlog-candidate | 0 |
| 140 | [#91293](https://github.com/microsoft/vscode/issues/91293) | [folding] context menu on expand/collapse arrow | 3 | backlog-candidate | 0 |
| 144 | [#43840](https://github.com/microsoft/vscode/issues/43840) | [folding] Code folding does not respect multi-cursor | 2 | backlog-candidate | 0 |
| 146 | [#71712](https://github.com/microsoft/vscode/issues/71712) | [folding] Distinctly highlight corresponding `#endregion` for `#region X` comments | 2 | backlog-candidate | 0 |
| 164 | [#67340](https://github.com/microsoft/vscode/issues/67340) | [folding] Show tooltip on hovering collapse markers | 1 | backlog-candidate | 0 |
| 167 | [#72684](https://github.com/microsoft/vscode/issues/72684) | [folding] Option to show both fold/unfold controls on mouseover only | 1 | backlog-candidate | 0 |
| 168 | [#74360](https://github.com/microsoft/vscode/issues/74360) | [folding] Fold All in selection | 1 | backlog-candidate | 0 |
| 170 | [#77861](https://github.com/microsoft/vscode/issues/77861) | [folding] Preserve folded ranges on revert | 1 | backlog-candidate | 0 |
| 171 | [#83250](https://github.com/microsoft/vscode/issues/83250) | [folding] Auto re-fold a region after the cursor leaves it. | 1 | backlog-candidate | 0 |
| 180 | [#174959](https://github.com/microsoft/vscode/issues/174959) | [folding] Allow us to know if a region is folded or not | 1 | backlog-candidate | 0 |
| 183 | [#204200](https://github.com/microsoft/vscode/issues/204200) | [folding] Add Code Folding Actions to the Undo Stack | 1 | backlog-candidate | 0 |
| 184 | [#212599](https://github.com/microsoft/vscode/issues/212599) | [folding] Remove manual folding range should only remove most inner folding range | 1 | backlog-candidate | 0 |
| 188 | [#265661](https://github.com/microsoft/vscode/issues/265661) | Support for FoldingRangeProviders that don't disable indentation based folding | 1 | backlog-candidate | 0 |
| 192 | [#279302](https://github.com/microsoft/vscode/issues/279302) | [folder] Add empty line automatically | 1 | backlog-candidate | 0 |
| 197 | [#313192](https://github.com/microsoft/vscode/issues/313192) | Folding Strategy: Brackets | 1 | active | 0 |
| 208 | [#42287](https://github.com/microsoft/vscode/issues/42287) | [folding] Allow folding block comment that starts in the middle of the line | 0 | backlog-candidate | 0 |
| 210 | [#46708](https://github.com/microsoft/vscode/issues/46708) | [folding] blocked while language server is starting up | 0 | backlog-candidate | 0 |
| 214 | [#52103](https://github.com/microsoft/vscode/issues/52103) | [folding] unfold when pressing enter on last line | 0 | backlog-candidate | 0 |
| 231 | [#88627](https://github.com/microsoft/vscode/issues/88627) | [folding] seperate color for line numbers at collapsed row | 0 | backlog-candidate | 0 |
| 232 | [#88915](https://github.com/microsoft/vscode/issues/88915) | [folding] Support for toggle fold/unfold recursively | 0 | dormant | 0 |
| 235 | [#95156](https://github.com/microsoft/vscode/issues/95156) | [folding] mode to have region based folding only | 0 | backlog-candidate | 0 |
| 238 | [#103445](https://github.com/microsoft/vscode/issues/103445) | [python] Add #region and #endregion to python autocomplete | 0 | backlog-candidate | 0 |
| 248 | [#119625](https://github.com/microsoft/vscode/issues/119625) | [folding] Hover over the folding indicator to mention Alt and Shift | 0 | backlog-candidate | 0 |
| 251 | [#123979](https://github.com/microsoft/vscode/issues/123979) | [folding]  highlight folding range when hovering over the collapse button | 0 | backlog-candidate | 0 |
| 259 | [#139676](https://github.com/microsoft/vscode/issues/139676) | [folding] functioning example available — navigate to previous/next line on same folding level | 0 | dormant | 0 |
| 267 | [#147526](https://github.com/microsoft/vscode/issues/147526) | [folding] Increase number of foldable regions | 0 | backlog-candidate | 0 |
| 291 | [#251674](https://github.com/microsoft/vscode/issues/251674) | Support folding in instruction file | 0 | backlog-candidate | 0 |
| 318 | [#269857](https://github.com/microsoft/vscode/issues/269857) | [folding] Do not collapse imports when navigating to an error in the imports section | 0 | backlog-candidate | 0 |

### Custom agents and skills (65)

| # | Issue | Title | 👍 | Signal | Score |
| --- | --- | --- | --- | --- | --- |
| 9 | [#251251](https://github.com/microsoft/vscode/issues/251251) | Feature Request: Add Temperature for Custom Agent Profiles | 84 | backlog-candidate | 16 |
| 20 | [#251515](https://github.com/microsoft/vscode/issues/251515) | Support Storing Toolset Files Directly Within the Workspace | 44 | backlog-candidate | 9 |
| 27 | [#295755](https://github.com/microsoft/vscode/issues/295755) | Feature Request: Support Branch Selection for Organization‑Level Copilot Agents | 40 | backlog-candidate | 7 |
| 40 | [#301181](https://github.com/microsoft/vscode/issues/301181) | Distribute Skills and Instructions from Organization Repositories | 18 | active | 5 |
| 48 | [#263279](https://github.com/microsoft/vscode/issues/263279) | Agent Mode: Disable tools by default besides core tools | 14 | backlog-candidate | 4 |
| 95 | [#288502](https://github.com/microsoft/vscode/issues/288502) | Skills should support tools references and enforce them in system prompt | 5 | active | 1 |
| 101 | [#251747](https://github.com/microsoft/vscode/issues/251747) | Enable Auto-Attach for MCP Prompts / Embedded Resources | 4 | active | 1 |
| 104 | [#277433](https://github.com/microsoft/vscode/issues/277433) | add a code execution tool | 4 | backlog-candidate | 1 |
| 105 | [#281116](https://github.com/microsoft/vscode/issues/281116) | Feature Request: Allow handsoff with resetting context window for custom agent | 4 | backlog-candidate | 1 |
| 110 | [#310436](https://github.com/microsoft/vscode/issues/310436) | Restrict skills to specific agents | 3 | active | 1 |
| 111 | [#313546](https://github.com/microsoft/vscode/issues/313546) | Support reasoning effort configuration in custom .agent.md files | 3 | active | 1 |
| 112 | [#287947](https://github.com/microsoft/vscode/issues/287947) | Implement built-in agents from Copilot CLI to Copilot Chat | 2 | backlog-candidate | 1 |
| 113 | [#296829](https://github.com/microsoft/vscode/issues/296829) | Per-agent auto-approve for terminal commands in custom agents (.agent.md) | 2 | active | 1 |
| 115 | [#277432](https://github.com/microsoft/vscode/issues/277432) | plan agent: Improve open editor handoff | 1 | backlog-candidate | 1 |
| 116 | [#279185](https://github.com/microsoft/vscode/issues/279185) | Save as Custom Agent from Tools Window | 1 | backlog-candidate | 1 |
| 117 | [#286358](https://github.com/microsoft/vscode/issues/286358) | Enhanced Support for Agent-Associated Files in VS Code Copilot Chat | 1 | backlog-candidate | 1 |
| 121 | [#272732](https://github.com/microsoft/vscode/issues/272732) | agent files: support variables | 0 | dormant | 1 |
| 122 | [#277547](https://github.com/microsoft/vscode/issues/277547) | Add icons to Agents | 0 | backlog-candidate | 1 |
| 123 | [#304721](https://github.com/microsoft/vscode/issues/304721) | Support contributing agent skill folders with supporting files from extensions | 0 | active | 1 |
| 124 | [#311920](https://github.com/microsoft/vscode/issues/311920) | Agent profiles and namespacing for Copilot custom agents | 0 | active | 1 |
| 142 | [#309043](https://github.com/microsoft/vscode/issues/309043) | Agents: Add model_reasoning_effort to custom agents and prompts. | 3 | active | 0 |
| 158 | [#298713](https://github.com/microsoft/vscode/issues/298713) | Support loading agent skills from packages | 2 | active | 0 |
| 187 | [#259183](https://github.com/microsoft/vscode/issues/259183) | Enable workspace-scoped tool sets | 1 | backlog-candidate | 0 |
| 190 | [#275082](https://github.com/microsoft/vscode/issues/275082) | Agent Handoffs: Improve editing experience | 1 | dormant | 0 |
| 193 | [#281791](https://github.com/microsoft/vscode/issues/281791) | GitHub Copilot agents should remember models on a per-agent basis. | 1 | backlog-candidate | 0 |
| 194 | [#297210](https://github.com/microsoft/vscode/issues/297210) | Prompt files should allow me to select latest model with wildcard | 1 | backlog-candidate | 0 |
| 195 | [#298928](https://github.com/microsoft/vscode/issues/298928) | Copilot Fix ignores extension-provided code.target and code actions, generating incorrect fixes | 1 | active | 0 |
| 196 | [#312279](https://github.com/microsoft/vscode/issues/312279) | Let me / multiple skills in one message | 1 | backlog-candidate | 0 |
| 289 | [#250421](https://github.com/microsoft/vscode/issues/250421) | Reconsider `languageModelToolSets` validation Notifications | 0 | backlog-candidate | 0 |
| 292 | [#252011](https://github.com/microsoft/vscode/issues/252011) | Allow Diagnostic providers to enrich AI-driven fix workflows with context via an optional method | 0 | backlog-candidate | 0 |
| 296 | [#253048](https://github.com/microsoft/vscode/issues/253048) | Copilot Coding Agent doesn't create copilot-instructions.md without help | 0 | backlog-candidate | 0 |
| 302 | [#256486](https://github.com/microsoft/vscode/issues/256486) | Add a `contexts` field to the .md metadata for a custom chat mode | 0 | dormant | 0 |
| 305 | [#259972](https://github.com/microsoft/vscode/issues/259972) | Show Built-in Tools at the bottom, collapsed or in a seperate tab | 0 | backlog-candidate | 0 |
| 306 | [#259973](https://github.com/microsoft/vscode/issues/259973) | Allow MCP Servers in non-agent mode | 0 | dormant | 0 |
| 307 | [#260214](https://github.com/microsoft/vscode/issues/260214) | Agent: Expose tool to run prompts controlled by the agent | 0 | backlog-candidate | 0 |
| 309 | [#261697](https://github.com/microsoft/vscode/issues/261697) | Feature Request: Customizable continuous actions per chat mode file | 0 | backlog-candidate | 0 |
| 311 | [#266750](https://github.com/microsoft/vscode/issues/266750) | "inherit" instructions in profiles | 0 | backlog-candidate | 0 |
| 314 | [#269134](https://github.com/microsoft/vscode/issues/269134) | Tool references in prompts: support `extensionId/*` | 0 | backlog-candidate | 0 |
| 320 | [#273813](https://github.com/microsoft/vscode/issues/273813) | Running a prompt without having the tools installed should show a warning in chat | 0 | backlog-candidate | 0 |
| 322 | [#275053](https://github.com/microsoft/vscode/issues/275053) | Agent file editing - missing potential fix | 0 | backlog-candidate | 0 |
| 325 | [#276105](https://github.com/microsoft/vscode/issues/276105) | Lots of tools I didn't choose in my tool set | 0 | backlog-candidate | 0 |
| 326 | [#276633](https://github.com/microsoft/vscode/issues/276633) | Clarify order of custom agent, workspace instructions, and user instructions in context | 0 | backlog-candidate | 0 |
| 327 | [#277735](https://github.com/microsoft/vscode/issues/277735) | Agent: Prompts should not persist tool/model selection after chat response | 0 | active | 0 |
| 329 | [#279184](https://github.com/microsoft/vscode/issues/279184) | Provide the ability to disable extension specific instructions in agent mode | 0 | backlog-candidate | 0 |
| 333 | [#280684](https://github.com/microsoft/vscode/issues/280684) | Selecting tools for custom agent always opens the md file | 0 | dormant | 0 |
| 334 | [#282241](https://github.com/microsoft/vscode/issues/282241) | Use the `#tool:fullReferenceName` syntax in the chat input | 0 | active | 0 |
| 337 | [#284627](https://github.com/microsoft/vscode/issues/284627) | Allow agent skill scripts to retrieve the workspace root/workspace file | 0 | active | 0 |
| 338 | [#288703](https://github.com/microsoft/vscode/issues/288703) | Support regex matching in custom copilot instruction injection | 0 | backlog-candidate | 0 |
| 339 | [#290272](https://github.com/microsoft/vscode/issues/290272) | Skill changes in skill.md don’t apply until VS Code restart or new chat session | 0 | active | 0 |
| 340 | [#290374](https://github.com/microsoft/vscode/issues/290374) | Extend Profile Isolation to AI Configuration Files (Copilot Instructions, AGENTS.md, Prompts) | 0 | active | 0 |
| 341 | [#294640](https://github.com/microsoft/vscode/issues/294640) | Feature Request: Add Optional "response_structure" Field to .agent.md Files (Custom Agents) | 0 | active | 0 |
| 342 | [#295894](https://github.com/microsoft/vscode/issues/295894) | per-model(s) instruction files | 0 | active | 0 |
| 343 | [#297651](https://github.com/microsoft/vscode/issues/297651) | [FEATURE REQUEST]: Include Copilot Chat Tools in Settings Sync | 0 | active | 0 |
| 344 | [#300411](https://github.com/microsoft/vscode/issues/300411) | runSubagent - more parameters, e.g. for model and tools | 0 | active | 0 |
| 345 | [#301490](https://github.com/microsoft/vscode/issues/301490) | Plugin-installed skill resource files not accessible to search tools (grep_search, file_search, semantic_search) | 0 | backlog-candidate | 0 |
| 346 | [#303777](https://github.com/microsoft/vscode/issues/303777) | Support skill-scoped hooks (on-load) in SKILL.md | 0 | active | 0 |
| 348 | [#306568](https://github.com/microsoft/vscode/issues/306568) | runSubagent ignores "agents" config by omitting "agentName" parameter | 0 | active | 0 |
| 349 | [#306717](https://github.com/microsoft/vscode/issues/306717) | Chat: add 'tiers' frontmatter and 'tier' parameter to runSubagent for semantic model tier routing | 0 | active | 0 |
| 350 | [#311874](https://github.com/microsoft/vscode/issues/311874) | Inline Skill Picker with Fuzzy Search while typing in Chat | 0 | active | 0 |
| 351 | [#312179](https://github.com/microsoft/vscode/issues/312179) | Allow folders with skills shipped via extensions to be read without user confirmations | 0 | active | 0 |
| 352 | [#312528](https://github.com/microsoft/vscode/issues/312528) | Create Copilot Chat settings for setting a global Custom Agent as default Agent | 0 | active | 0 |
| 353 | [#314388](https://github.com/microsoft/vscode/issues/314388) | Runtime errors when prompt/agent references model or agent that doesn't exist | 0 | active | 0 |
| 355 | [#315593](https://github.com/microsoft/vscode/issues/315593) | Allow to change models for Custom agents inside Agent Plugin | 0 | active | 0 |
| 356 | [#319321](https://github.com/microsoft/vscode/issues/319321) | Feature Request: Presaved MCP Toolsets / Named Presets for Context-Aware Tool Activation | 0 | active | 0 |
| 359 | [#320641](https://github.com/microsoft/vscode/issues/320641) | Copilot Agent Host: SDK Driven Agents/Skills/etc | 0 | active | 0 |

### CSS and SCSS support (41)

| # | Issue | Title | 👍 | Signal | Score |
| --- | --- | --- | --- | --- | --- |
| 10 | [#28459](https://github.com/microsoft/vscode/issues/28459) | [css] Use CSS custom properties imported via @import | 155 | backlog-candidate | 15 |
| 11 | [#165207](https://github.com/microsoft/vscode/issues/165207) | [css] Add new CSS color functions | 115 | backlog-candidate | 15 |
| 23 | [#47331](https://github.com/microsoft/vscode/issues/47331) | [html][css] Investigate cross css/html, multi file support | 72 | backlog-candidate | 7 |
| 29 | [#163967](https://github.com/microsoft/vscode/issues/163967) | [css] Custom aliases in CSS file resolution | 47 | backlog-candidate | 6 |
| 43 | [#66053](https://github.com/microsoft/vscode/issues/66053) | [css][html] SVG language support | 44 | backlog-candidate | 4 |
| 58 | [#85828](https://github.com/microsoft/vscode/issues/85828) | [css] Support for SVG 2 CSS Properties | 23 | backlog-candidate | 3 |
| 60 | [#166944](https://github.com/microsoft/vscode/issues/166944) | [css] Please add an option to switch to using line-by-line comments | 22 | backlog-candidate | 3 |
| 86 | [#162030](https://github.com/microsoft/vscode/issues/162030) | [css] CSS custom property completions | 9 | backlog-candidate | 1 |
| 94 | [#164744](https://github.com/microsoft/vscode/issues/164744) | [scss] Sass modules intellisense when using @use at-rules. | 5 | backlog-candidate | 1 |
| 106 | [#100217](https://github.com/microsoft/vscode/issues/100217) | [scss] Support completion/intellisense of SCSS/SASS variables & mixins | 3 | backlog-candidate | 1 |
| 107 | [#214871](https://github.com/microsoft/vscode/issues/214871) | [css] look for variables in all open documents | 3 | backlog-candidate | 1 |
| 128 | [#62333](https://github.com/microsoft/vscode/issues/62333) | [css] Add @media and @supports to CSS breadcrumbs | 4 | backlog-candidate | 0 |
| 132 | [#131494](https://github.com/microsoft/vscode/issues/131494) | [scss] Hover hint doesn't support SCSS Interpolation syntax | 4 | backlog-candidate | 0 |
| 139 | [#77011](https://github.com/microsoft/vscode/issues/77011) | [css] Shorthand properties: show label for each value in hover | 3 | backlog-candidate | 0 |
| 143 | [#43365](https://github.com/microsoft/vscode/issues/43365) | [css] propose ids used in other selectors | 2 | dormant | 0 |
| 148 | [#86763](https://github.com/microsoft/vscode/issues/86763) | [scss] add parameter hints | 2 | backlog-candidate | 0 |
| 162 | [#54638](https://github.com/microsoft/vscode/issues/54638) | [scss] Add "Go to or peek defintion" for imported mixins and variables for SCSS files | 1 | backlog-candidate | 0 |
| 169 | [#74664](https://github.com/microsoft/vscode/issues/74664) | [css] Color picker for rgba() function in CSS | 1 | backlog-candidate | 0 |
| 172 | [#86765](https://github.com/microsoft/vscode/issues/86765) | [scss] provide hover for scss functions | 1 | backlog-candidate | 0 |
| 173 | [#111133](https://github.com/microsoft/vscode/issues/111133) | [css] Support for CSS3 speech properties voice-family, voice-pitch, voice-range and voice-stress | 1 | backlog-candidate | 0 |
| 182 | [#202417](https://github.com/microsoft/vscode/issues/202417) | [css] Outline doesn't show @layer | 1 | backlog-candidate | 0 |
| 199 | [#6822](https://github.com/microsoft/vscode/issues/6822) | [css/less/scss] var should be a suggestion in intellisense | 0 | dormant | 0 |
| 200 | [#6829](https://github.com/microsoft/vscode/issues/6829) | [css] show all variable definitions for Go To definition | 0 | backlog-candidate | 0 |
| 201 | [#7757](https://github.com/microsoft/vscode/issues/7757) | [css] Support <angle> units icon in CSS | 0 | backlog-candidate | 0 |
| 209 | [#43111](https://github.com/microsoft/vscode/issues/43111) | [css] Lab colors and other CSS Color Module Level 4 features | 0 | dormant | 0 |
| 218 | [#62569](https://github.com/microsoft/vscode/issues/62569) | [scss] rename not working for placeholder selectors | 0 | backlog-candidate | 0 |
| 219 | [#66703](https://github.com/microsoft/vscode/issues/66703) | [css] support IE10 repeat syntax | 0 | backlog-candidate | 0 |
| 221 | [#77582](https://github.com/microsoft/vscode/issues/77582) | [css][html] Publish language servers modules on npm | 0 | backlog-candidate | 0 |
| 222 | [#79141](https://github.com/microsoft/vscode/issues/79141) | [css] Add support for CSS @supports selector() function | 0 | backlog-candidate | 0 |
| 223 | [#79439](https://github.com/microsoft/vscode/issues/79439) | [css] code completion for gradient functions | 0 | backlog-candidate | 0 |
| 225 | [#83835](https://github.com/microsoft/vscode/issues/83835) | [css] support css-variable completion in calc | 0 | backlog-candidate | 0 |
| 227 | [#86187](https://github.com/microsoft/vscode/issues/86187) | [scss] provide hover information for at-rules | 0 | dormant | 0 |
| 229 | [#86488](https://github.com/microsoft/vscode/issues/86488) | [scss] references for all SASS functions/at-rules | 0 | backlog-candidate | 0 |
| 255 | [#126733](https://github.com/microsoft/vscode/issues/126733) | [css] Color picker for css variables | 0 | backlog-candidate | 0 |
| 261 | [#142946](https://github.com/microsoft/vscode/issues/142946) | [css] Allow extensions to choose to use whether to use CSS default data provider | 0 | backlog-candidate | 0 |
| 264 | [#145702](https://github.com/microsoft/vscode/issues/145702) | [css] Support format on type | 0 | backlog-candidate | 0 |
| 266 | [#147483](https://github.com/microsoft/vscode/issues/147483) | [css] Enable drop image into css to insert url | 0 | backlog-candidate | 0 |
| 274 | [#185999](https://github.com/microsoft/vscode/issues/185999) | [css] add clamp() math function | 0 | backlog-candidate | 0 |
| 276 | [#189875](https://github.com/microsoft/vscode/issues/189875) | Workspace files dropped and pasted into CSS file should be automatically formatted | 0 | dormant | 0 |
| 280 | [#224977](https://github.com/microsoft/vscode/issues/224977) | [css] allow to overtype the semicolon | 0 | backlog-candidate | 0 |
| 281 | [#227697](https://github.com/microsoft/vscode/issues/227697) | LSP DocumentColor Refresh Request | 0 | backlog-candidate | 0 |

### HTML language support (34)

| # | Issue | Title | 👍 | Signal | Score |
| --- | --- | --- | --- | --- | --- |
| 15 | [#26338](https://github.com/microsoft/vscode/issues/26338) | [html] Javascript intellisense in inline scripts from external references | 125 | backlog-candidate | 12 |
| 35 | [#25898](https://github.com/microsoft/vscode/issues/25898) | [html] provide translations of tag documentation | 48 | backlog-candidate | 5 |
| 45 | [#58315](https://github.com/microsoft/vscode/issues/58315) | [html] Automatically delete HTML closing tag when converting to self-closing tag | 36 | backlog-candidate | 4 |
| 70 | [#114115](https://github.com/microsoft/vscode/issues/114115) | [html] support imports in embedded JavaScript | 15 | backlog-candidate | 2 |
| 76 | [#31141](https://github.com/microsoft/vscode/issues/31141) | [html] provide rename for embedded JavaScript | 14 | backlog-candidate | 1 |
| 83 | [#140698](https://github.com/microsoft/vscode/issues/140698) | [html] Improve `html.autoCreateQuotes` to handle manually typed quotes | 10 | backlog-candidate | 1 |
| 125 | [#60489](https://github.com/microsoft/vscode/issues/60489) | [html] proper support of XHTML | 6 | backlog-candidate | 0 |
| 145 | [#57469](https://github.com/microsoft/vscode/issues/57469) | [html] Support SCSS in HTML with <style type="text/scss"> | 2 | backlog-candidate | 0 |
| 149 | [#89850](https://github.com/microsoft/vscode/issues/89850) | [html] HTML breadcrumbs don't work right when optional end tags omitted | 2 | backlog-candidate | 0 |
| 153 | [#181935](https://github.com/microsoft/vscode/issues/181935) | [html] Allow renaming images using F2 | 2 | backlog-candidate | 0 |
| 160 | [#12787](https://github.com/microsoft/vscode/issues/12787) | [html] closing </script> tag is not proposed | 1 | backlog-candidate | 0 |
| 161 | [#44612](https://github.com/microsoft/vscode/issues/44612) | [razor] comment out razor code with @* *@ | 1 | backlog-candidate | 0 |
| 163 | [#66148](https://github.com/microsoft/vscode/issues/66148) | [html] code complete for href anchors | 1 | backlog-candidate | 0 |
| 179 | [#128716](https://github.com/microsoft/vscode/issues/128716) | [html] propose `charset="UTF-8"` `target="_blank"` and `rel="stylesheet"` | 1 | backlog-candidate | 0 |
| 205 | [#41134](https://github.com/microsoft/vscode/issues/41134) | [html] extract class name to css file | 0 | dormant | 0 |
| 206 | [#41206](https://github.com/microsoft/vscode/issues/41206) | [html] code completion replaces text after cursor | 0 | backlog-candidate | 0 |
| 211 | [#47192](https://github.com/microsoft/vscode/issues/47192) | [html] propose html 4 properties (cellPadding ...) | 0 | backlog-candidate | 0 |
| 213 | [#49210](https://github.com/microsoft/vscode/issues/49210) | [html-templating] easy way to inherite advanced html features | 0 | dormant | 0 |
| 217 | [#59445](https://github.com/microsoft/vscode/issues/59445) | [html] support less syntax in html file | 0 | backlog-candidate | 0 |
| 220 | [#68548](https://github.com/microsoft/vscode/issues/68548) | [html] [custom data] allow to give custom HTML tags/attributes a higher completion rank | 0 | backlog-candidate | 0 |
| 224 | [#81352](https://github.com/microsoft/vscode/issues/81352) | [html] Jump to after next opening HTML tag | 0 | backlog-candidate | 0 |
| 236 | [#96834](https://github.com/microsoft/vscode/issues/96834) | [html] No values suggested for `autocapitalize` | 0 | backlog-candidate | 0 |
| 237 | [#97949](https://github.com/microsoft/vscode/issues/97949) | [html] don't let '/' trigger a suggest in embedded JavaScript | 0 | backlog-candidate | 0 |
| 239 | [#105298](https://github.com/microsoft/vscode/issues/105298) | [html] Add value proposals for rel attribute | 0 | backlog-candidate | 0 |
| 243 | [#111016](https://github.com/microsoft/vscode/issues/111016) | [html] move mdn link to the right | 0 | backlog-candidate | 0 |
| 249 | [#120040](https://github.com/microsoft/vscode/issues/120040) | [html] suggestions for media | 0 | backlog-candidate | 0 |
| 252 | [#123987](https://github.com/microsoft/vscode/issues/123987) | [html] allow to configure html formatter for other languages | 0 | backlog-candidate | 0 |
| 262 | [#144730](https://github.com/microsoft/vscode/issues/144730) | [html] allow to turn off closing tags when not needed | 0 | backlog-candidate | 0 |
| 265 | [#145883](https://github.com/microsoft/vscode/issues/145883) | [html] don't show closing element proposal as first entry if element is already closed later | 0 | backlog-candidate | 0 |
| 268 | [#151319](https://github.com/microsoft/vscode/issues/151319) | [html] `html.autoCreateQuotes` is not instant | 0 | backlog-candidate | 0 |
| 270 | [#163742](https://github.com/microsoft/vscode/issues/163742) | [html] Ignore html tag in sticky scroll and outline | 0 | backlog-candidate | 0 |
| 272 | [#175807](https://github.com/microsoft/vscode/issues/175807) | [html] Path completion isn’t working with the `srcset` attribute | 0 | backlog-candidate | 0 |
| 286 | [#242999](https://github.com/microsoft/vscode/issues/242999) | [html] Filter <link> path suggestion by file type | 0 | backlog-candidate | 0 |
| 288 | [#249690](https://github.com/microsoft/vscode/issues/249690) | [html] Rename Symbol doesn't work on attribute names | 0 | backlog-candidate | 0 |

### Prompt and instruction files (36)

| # | Issue | Title | 👍 | Signal | Score |
| --- | --- | --- | --- | --- | --- |
| 31 | [#270160](https://github.com/microsoft/vscode/issues/270160) | Add support for full-match patterns relative to workspace root for Copilot Instructions `applyTo` pattern | 26 | backlog-candidate | 6 |
| 39 | [#288838](https://github.com/microsoft/vscode/issues/288838) | [Feature Request] Add frontmatter option to open .prompt.md files in a new chat session | 23 | backlog-candidate | 5 |
| 72 | [#291685](https://github.com/microsoft/vscode/issues/291685) | Make sharing of copilot instructions, skills etc globally easy for organizations | 5 | active | 2 |
| 92 | [#262876](https://github.com/microsoft/vscode/issues/262876) | [prompts] One-Click install of Copilot Instructions / Prompts from private Github repos | 6 | backlog-candidate | 1 |
| 100 | [#251603](https://github.com/microsoft/vscode/issues/251603) | Issue: GitHub Copilot toolsets.jsonc file not syncing across devices | 4 | backlog-candidate | 1 |
| 102 | [#255196](https://github.com/microsoft/vscode/issues/255196) | Copilot instructions in multi-root should apply per folder | 4 | backlog-candidate | 1 |
| 103 | [#275981](https://github.com/microsoft/vscode/issues/275981) | [Feedback] [Plan Mode] Confusing UX for "Open in Editor" option and .prompt.md file extension | 4 | backlog-candidate | 1 |
| 108 | [#291311](https://github.com/microsoft/vscode/issues/291311) | Agent mode does not reference instruction files after reading a file outside its initial context. | 3 | active | 1 |
| 109 | [#307369](https://github.com/microsoft/vscode/issues/307369) | chat.agentFilesLocations and chat.agentSkillsLocations should support glob/wildcard patterns | 3 | active | 1 |
| 118 | [#255124](https://github.com/microsoft/vscode/issues/255124) | Panel chat gear dropdown should have hints on hover | 0 | backlog-candidate | 1 |
| 119 | [#256007](https://github.com/microsoft/vscode/issues/256007) | Chat - Apply in Editor feedback | 0 | backlog-candidate | 1 |
| 141 | [#284849](https://github.com/microsoft/vscode/issues/284849) | Support for Custom Attributes in `.prompt.md` YAML Front Matter | 3 | backlog-candidate | 0 |
| 156 | [#278850](https://github.com/microsoft/vscode/issues/278850) | Prompts and instructions aren't syncing if non-default profile is used | 2 | backlog-candidate | 0 |
| 157 | [#280091](https://github.com/microsoft/vscode/issues/280091) | Support for `${userHome}` variable in `chat.promptFilesLocations` setting | 2 | backlog-candidate | 0 |
| 189 | [#267596](https://github.com/microsoft/vscode/issues/267596) | Feature: Toggle custom Copilot instructions per chat session | 1 | backlog-candidate | 0 |
| 293 | [#252530](https://github.com/microsoft/vscode/issues/252530) | Make `security.promptForPromptProtocolHandling` a real setting and an allow list | 0 | backlog-candidate | 0 |
| 294 | [#252552](https://github.com/microsoft/vscode/issues/252552) | Support human facing comments in custom chat mode files | 0 | backlog-candidate | 0 |
| 297 | [#253201](https://github.com/microsoft/vscode/issues/253201) | Support comments in header section | 0 | backlog-candidate | 0 |
| 298 | [#253498](https://github.com/microsoft/vscode/issues/253498) | Using the same link again should do file validation before I accept it | 0 | backlog-candidate | 0 |
| 299 | [#253515](https://github.com/microsoft/vscode/issues/253515) | Support `content` instead of `url` for vscode:chat-* links | 0 | backlog-candidate | 0 |
| 300 | [#253517](https://github.com/microsoft/vscode/issues/253517) | More options when opening vscode:chat-prompt links in VS Code | 0 | backlog-candidate | 0 |
| 303 | [#257285](https://github.com/microsoft/vscode/issues/257285) | Users need to be guided to make a proper instruction file | 0 | dormant | 0 |
| 304 | [#258425](https://github.com/microsoft/vscode/issues/258425) | A better way to manage prompts/instructions/agents with the same name. | 0 | backlog-candidate | 0 |
| 308 | [#260672](https://github.com/microsoft/vscode/issues/260672) | Instructions: Allow filtering instructions to specific modes | 0 | dormant | 0 |
| 312 | [#267086](https://github.com/microsoft/vscode/issues/267086) | Support cursor rules | 0 | backlog-candidate | 0 |
| 313 | [#268330](https://github.com/microsoft/vscode/issues/268330) | Add ability to create Chatmode/Prompt from current chat | 0 | backlog-candidate | 0 |
| 316 | [#269564](https://github.com/microsoft/vscode/issues/269564) | Allow to import prompt/instruction/modes file via `vscode` link for files that need authentication | 0 | backlog-candidate | 0 |
| 319 | [#273615](https://github.com/microsoft/vscode/issues/273615) | Enable Ctrl+Click on slash commands in chat input to open prompt file | 0 | backlog-candidate | 0 |
| 323 | [#275888](https://github.com/microsoft/vscode/issues/275888) | Let me hide Ask & Edit modes | 0 | dormant | 0 |
| 324 | [#275979](https://github.com/microsoft/vscode/issues/275979) | Prompt file type detection should be case-insensitive | 0 | dormant | 0 |
| 328 | [#278111](https://github.com/microsoft/vscode/issues/278111) | [prompts] add a command to improve a prompt | 0 | backlog-candidate | 0 |
| 330 | [#279367](https://github.com/microsoft/vscode/issues/279367) | Support substitution variables in prompt files | 0 | backlog-candidate | 0 |
| 331 | [#279464](https://github.com/microsoft/vscode/issues/279464) | The completions in the front matter is influenced by the space after the `:` | 0 | dormant | 0 |
| 332 | [#280624](https://github.com/microsoft/vscode/issues/280624) | [prompts] fill in default content for new files created with `New File` | 0 | backlog-candidate | 0 |
| 335 | [#283149](https://github.com/microsoft/vscode/issues/283149) | Unable to specify line numbers when providing file context in prompt files | 0 | backlog-candidate | 0 |
| 354 | [#315240](https://github.com/microsoft/vscode/issues/315240) | Default `editor.linkedEditing` to true | 0 | backlog-candidate | 0 |

### WSL and remote development (14)

| # | Issue | Title | 👍 | Signal | Score |
| --- | --- | --- | --- | --- | --- |
| 42 | [#179152](https://github.com/microsoft/vscode/issues/179152) | Add support for remote development on Windows Sandbox | 45 | backlog-candidate | 4 |
| 50 | [#127587](https://github.com/microsoft/vscode/issues/127587) | [remote] Prefer to open a file in an existing window even when that window is connected to a remote with that file opened | 29 | backlog-candidate | 3 |
| 96 | [#316209](https://github.com/microsoft/vscode/issues/316209) | No port forwarding for "code serve-web" when accessed from another machine | 5 | active | 1 |
| 99 | [#221851](https://github.com/microsoft/vscode/issues/221851) | [wsl] Use curl instead of wget to download VS Code server | 4 | backlog-candidate | 1 |
| 120 | [#262129](https://github.com/microsoft/vscode/issues/262129) | "open with code" automatically with wsl vscode server | 0 | backlog-candidate | 1 |
| 181 | [#187027](https://github.com/microsoft/vscode/issues/187027) | [wsl] support undo after deleting directory | 1 | backlog-candidate | 0 |
| 186 | [#240063](https://github.com/microsoft/vscode/issues/240063) | Please add HTTPS support for serve-web | 1 | backlog-candidate | 0 |
| 191 | [#278102](https://github.com/microsoft/vscode/issues/278102) | [wsl] Pipe to `code -` does not work in WSL | 1 | backlog-candidate | 0 |
| 247 | [#117849](https://github.com/microsoft/vscode/issues/117849) | [remote cli] support opening `file` URIs | 0 | backlog-candidate | 0 |
| 273 | [#185775](https://github.com/microsoft/vscode/issues/185775) | [wsl] Automatically give vscode wsl sh scripts +x | 0 | backlog-candidate | 0 |
| 275 | [#189692](https://github.com/microsoft/vscode/issues/189692) | [wsl] Option to start new window in WSL from File menu | 0 | backlog-candidate | 0 |
| 283 | [#228781](https://github.com/microsoft/vscode/issues/228781) | `code serve-web` ignores the `--enable-proposed-api` flag | 0 | backlog-candidate | 0 |
| 285 | [#238498](https://github.com/microsoft/vscode/issues/238498) | [wsl] bring back "Reopen Folder in WSL" to the remote menu | 0 | backlog-candidate | 0 |
| 301 | [#254361](https://github.com/microsoft/vscode/issues/254361) | [WSL] Add server installation `dnf install wget` for Fedora | 0 | backlog-candidate | 0 |

### Other (17)

| # | Issue | Title | 👍 | Signal | Score |
| --- | --- | --- | --- | --- | --- |
| 28 | [#28080](https://github.com/microsoft/vscode/issues/28080) | [decorations] Support hover decorations over the line numbers (i.e. gutter) | 72 | backlog-candidate | 6 |
| 36 | [#105487](https://github.com/microsoft/vscode/issues/105487) | [cli] specify command that runs on window open | 44 | backlog-candidate | 5 |
| 38 | [#274545](https://github.com/microsoft/vscode/issues/274545) | [npm] package.json dependency autocomplete: autocomplete all versions | 23 | backlog-candidate | 5 |
| 73 | [#192144](https://github.com/microsoft/vscode/issues/192144) | VSCode client libraries have invalid exports | 2 | backlog-candidate | 2 |
| 79 | [#54248](https://github.com/microsoft/vscode/issues/54248) | [json] package.json: complete package versions from scopes or private registries | 13 | backlog-candidate | 1 |
| 165 | [#69546](https://github.com/microsoft/vscode/issues/69546) | [json] add colon automatically | 1 | backlog-candidate | 0 |
| 176 | [#119047](https://github.com/microsoft/vscode/issues/119047) | [themes] use both English and UI language to search color theme names | 1 | backlog-candidate | 0 |
| 207 | [#41320](https://github.com/microsoft/vscode/issues/41320) | [xml] add on enter rules | 0 | backlog-candidate | 0 |
| 216 | [#56719](https://github.com/microsoft/vscode/issues/56719) | [npm] hover should show relevant latest version | 0 | backlog-candidate | 0 |
| 230 | [#86764](https://github.com/microsoft/vscode/issues/86764) | [css] hover for property values | 0 | backlog-candidate | 0 |
| 233 | [#91086](https://github.com/microsoft/vscode/issues/91086) | [npm] load description/homepage from referenced node module version | 0 | backlog-candidate | 0 |
| 250 | [#123615](https://github.com/microsoft/vscode/issues/123615) | [api][commands] Open new window and a file | 0 | dormant | 0 |
| 253 | [#124577](https://github.com/microsoft/vscode/issues/124577) | [api] Give access to recently opened workspaces: `vscode.getRecentlyOpened` | 0 | backlog-candidate | 0 |
| 260 | [#142402](https://github.com/microsoft/vscode/issues/142402) | Tags for properties contribution is missing from completion | 0 | backlog-candidate | 0 |
| 317 | [#269828](https://github.com/microsoft/vscode/issues/269828) | Render counts next to collapsed toolsets | 0 | backlog-candidate | 0 |
| 321 | [#273815](https://github.com/microsoft/vscode/issues/273815) | Allow prompts to run in without any instruction files | 0 | backlog-candidate | 0 |
| 358 | [#319981](https://github.com/microsoft/vscode/issues/319981) | there is no slash-br | 0 | backlog-candidate | 0 |
