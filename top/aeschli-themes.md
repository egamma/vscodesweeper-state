# Top issues by theme — aeschli

Experimental themed view of [the flat ranking](aeschli.md); themes assigned by the review engine. Rank/score are the lane-wide values. Generated 2026-08-02 12:47 UTC.

## Bugs

### Remote connectivity (19)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | [#157275](https://github.com/microsoft/vscode/issues/157275) | Unable to connect to VS Code server: Error in request - ENOENT /run/user/1000/vscode-ipc-*.sock | 28 | correctness | 5/6 Source-confirmed | 100 | yes | — |
| 5 | [#298221](https://github.com/microsoft/vscode/issues/298221) | Cannot reconnect in WSL window after hibernation | 9 | correctness | 4/6 Traced | 62 | — | — |
| 6 | [#316459](https://github.com/microsoft/vscode/issues/316459) | Remote-WSL 0.104.3 fails with `navigator is now a global in nodejs` / `PendingMigrationError`, then WebSocket 1006 when connecting to WSL | 4 | correctness | 6/6 Confirmed | 37 | — | — |
| 25 | [#193603](https://github.com/microsoft/vscode/issues/193603) | [wsl] Can't run `code .` when offline and VS Code got updated | 3 | correctness | 3/6 Plausible | 12 | — | — |
| 26 | [#265301](https://github.com/microsoft/vscode/issues/265301) | When WSL is closed / crashes, all open instances of VSCode have to be closed completely - reload window and attempting to reconnect fails | 2 | correctness | 3/6 Plausible | 12 | — | — |
| 44 | [#269702](https://github.com/microsoft/vscode/issues/269702) | Unable to run code from wsl1 | 0 | correctness | 3/6 Plausible | 8 | — | — |
| 58 | [#292355](https://github.com/microsoft/vscode/issues/292355) | The file read error while using the vscode with wsl. | 0 | correctness | 3/6 Plausible | 6 | — | — |
| 59 | [#320045](https://github.com/microsoft/vscode/issues/320045) | Error: VSCode Server fails, if update fails to download | 0 | correctness | 3/6 Plausible | 6 | — | — |
| 67 | [#188134](https://github.com/microsoft/vscode/issues/188134) | Inconsistent naming for WSL projects in right-click taskbar menu | 1 | visual | 4/6 Traced | 4 | yes | — |
| 68 | [#197637](https://github.com/microsoft/vscode/issues/197637) | '--no-proxy-server' command line argument does not work | 1 | correctness | 5/6 Source-confirmed | 4 | yes | — |
| 69 | [#209601](https://github.com/microsoft/vscode/issues/209601) | code serve web --server-base-path PWA app does not include base path | 1 | correctness | 5/6 Source-confirmed | 4 | yes | — |
| 70 | [#236348](https://github.com/microsoft/vscode/issues/236348) | `vscode://vscode-remote/wsl+<distro>/path/to/file` des not use already open window | 1 | correctness | 5/6 Source-confirmed | 4 | — | — |
| 73 | [#123421](https://github.com/microsoft/vscode/issues/123421) | Couldn't open two folders with almost equal names, except for capitalization on Windows via SSH | 0 | correctness | 5/6 Source-confirmed | 4 | yes | — |
| 74 | [#164638](https://github.com/microsoft/vscode/issues/164638) | Server process leaks after closing VS Code with Remote Tunnel Access On | 0 | correctness | — | 4 | — | — |
| 103 | [#270650](https://github.com/microsoft/vscode/issues/270650) | Copilot Agent prompts fail when chat.useNestedAgentsMdFiles is enabled with SSH FS folders | 0 | correctness | 5/6 Source-confirmed | 2 | — | — |
| 146 | [#318088](https://github.com/microsoft/vscode/issues/318088) | VS Code removes existing WSL server before successfully downloading new version, causing permanent WSL connection failure if network is blocked | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 162 | [#167742](https://github.com/microsoft/vscode/issues/167742) | [remote tunnels] no notification shows up | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 167 | [#187046](https://github.com/microsoft/vscode/issues/187046) | [wsl] Crash when launching from wsl with `--verbose` | 0 | crash | 4/6 Traced | 0 | yes | — |
| 192 | [#307368](https://github.com/microsoft/vscode/issues/307368) | Remote tunnel connection broken after each update | 0 | correctness | 6/6 Confirmed | 0 | — | — |

### Linked editing (13)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2 | [#180156](https://github.com/microsoft/vscode/issues/180156) | [linked editing] Linked editing stops syncing on quick edits | 30 | correctness | 5/6 Source-confirmed | 93 | — | — |
| 3 | [#184829](https://github.com/microsoft/vscode/issues/184829) | JSX Linked Editing not working with Vim extension | 21 | correctness | 5/6 Source-confirmed | 73 | yes | — |
| 4 | [#208276](https://github.com/microsoft/vscode/issues/208276) | [linked rename] Linked Editing does't work well | 16 | correctness | 5/6 Source-confirmed | 72 | yes | — |
| 40 | [#247235](https://github.com/microsoft/vscode/issues/247235) | Deleting JSX tag name and then typing a different tag name doesn't update closing tag | 0 | correctness | 5/6 Source-confirmed | 9 | yes | — |
| 80 | [#140868](https://github.com/microsoft/vscode/issues/140868) | [linked editing] stops when tag name gets empty and end tag is on same line | 4 | papercut | 5/6 Source-confirmed | 3 | yes | — |
| 85 | [#216626](https://github.com/microsoft/vscode/issues/216626) | Deleting lines when editor.linkedEditing is enabled leads to inconsistent results | 1 | correctness | 4/6 Traced | 3 | yes | — |
| 119 | [#92964](https://github.com/microsoft/vscode/issues/92964) | [rename on type] option-delete and pasting creates 2 undo stops | 0 | papercut | 4/6 Traced | 1 | yes | — |
| 120 | [#93006](https://github.com/microsoft/vscode/issues/93006) | [rename on type] strange behavior with auto indent in closing tag | 0 | correctness | 4/6 Traced | 1 | yes | — |
| 123 | [#127521](https://github.com/microsoft/vscode/issues/127521) | [linked editing] does not work right after enter | 0 | papercut | 3/6 Plausible | 1 | — | — |
| 156 | [#93872](https://github.com/microsoft/vscode/issues/93872) | [rename on type] feedback incorrect after Rename | 0 | visual | 4/6 Traced | 0 | — | — |
| 157 | [#110580](https://github.com/microsoft/vscode/issues/110580) | [rename on type] stops when composing characters | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 166 | [#184985](https://github.com/microsoft/vscode/issues/184985) | Manual linked editing doesn't seem to work | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 171 | [#239351](https://github.com/microsoft/vscode/issues/239351) | Renaming paired tags doesn't work if you clear the tag completely | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |

### Plans and handoffs (13)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 7 | [#311802](https://github.com/microsoft/vscode/issues/311802) | Start implementation posts into current Plan session instead of handing off to implementation | 5 | correctness | 2/6 Unverified | 36 | — | — |
| 23 | [#323728](https://github.com/microsoft/vscode/issues/323728) | slash command blocks input - Copilot Chat with Agent Host, Claude Agent SDK | 0 | correctness | 6/6 Confirmed | 13 | — | — |
| 39 | [#312195](https://github.com/microsoft/vscode/issues/312195) | Unwanted code insertion during analysis only mode | 1 | correctness | 3/6 Plausible | 9 | — | — |
| 62 | [#296255](https://github.com/microsoft/vscode/issues/296255) | Chat Handoff should not change when switching mode | 1 | correctness | 2/6 Unverified | 5 | — | — |
| 71 | [#299044](https://github.com/microsoft/vscode/issues/299044) | [Plan Mode] Claude Sonnet 4.6 executes tool calls instead of outputting text-only plan | 1 | correctness | 3/6 Plausible | 4 | — | — |
| 81 | [#243110](https://github.com/microsoft/vscode/issues/243110) | "Insert At Cursor" should be disabled when no text editor is opened | 2 | papercut | 5/6 Source-confirmed | 3 | yes | — |
| 86 | [#286555](https://github.com/microsoft/vscode/issues/286555) | Switching to a competed session with handoff (like Plan) doesn't show handoffs | 1 | correctness | — | 3 | — | — |
| 89 | [#285754](https://github.com/microsoft/vscode/issues/285754) | Unable to prevent GitHub Copilot from editing files. | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 104 | [#272988](https://github.com/microsoft/vscode/issues/272988) | Agent handoffs: prompt should not overriden existing chat input text | 0 | papercut | 5/6 Source-confirmed | 2 | yes | — |
| 109 | [#295976](https://github.com/microsoft/vscode/issues/295976) | "Proceed from plan" section missing when session is reopened | 0 | papercut | 3/6 Plausible | 2 | — | — |
| 110 | [#299185](https://github.com/microsoft/vscode/issues/299185) | Error when trying to save a plan | 0 | correctness | 4/6 Traced | 2 | — | — |
| 135 | [#283179](https://github.com/microsoft/vscode/issues/283179) | When clicking "Apply edits" file gets create with wrong name/location | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 137 | [#290423](https://github.com/microsoft/vscode/issues/290423) | Chat references show literal "Unknown variable type" placeholder | 0 | visual | 2/6 Unverified | 1 | — | — |

### Instructions and prompts (36)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 8 | [#286920](https://github.com/microsoft/vscode/issues/286920) | GitHub Copilot doesn't reflect usage of custom prompt | 0 | correctness | 3/6 Plausible | 29 | — | — |
| 9 | [#277934](https://github.com/microsoft/vscode/issues/277934) | GitHub Copilot fails to process workspace when multiple identical copilot-instructions.md files are present | 7 | correctness | 4/6 Traced | 27 | yes | — |
| 11 | [#292933](https://github.com/microsoft/vscode/issues/292933) | Copilot Chat's LLM tools ignore copilot-instructions.md more often than they follow them. | 3 | correctness | 3/6 Plausible | 27 | — | — |
| 16 | [#304903](https://github.com/microsoft/vscode/issues/304903) | Problems pane constantly re-evaluates frontmatter diagnostics for custom agent/instruction/skill/prompt files — excessive CPU and memory | 3 | perf | — | 19 | — | — |
| 18 | [#290178](https://github.com/microsoft/vscode/issues/290178) | prompts-diagnostics-provider reports valid relative links as "File not found" in copilot-instructions.md | 1 | correctness | 5/6 Source-confirmed | 16 | yes | — |
| 20 | [#304101](https://github.com/microsoft/vscode/issues/304101) | User-level .instructions.md files with applyTo "**" discovered but not automatically included in chat requests | 0 | correctness | 2/6 Unverified | 15 | — | — |
| 35 | [#285308](https://github.com/microsoft/vscode/issues/285308) | *.instructions.md not read automatically, files not navigated | 0 | correctness | 3/6 Plausible | 10 | — | — |
| 41 | [#252789](https://github.com/microsoft/vscode/issues/252789) | Lose custom instructions I retry after a window reload | 0 | correctness | 5/6 Source-confirmed | 9 | — | — |
| 43 | [#325244](https://github.com/microsoft/vscode/issues/325244) | Agent Mode (Copilot CLI) should have access to global user-level instructions (like Chat's memory/environment.md) | 1 | correctness | 3/6 Plausible | 8 | — | — |
| 45 | [#275344](https://github.com/microsoft/vscode/issues/275344) | Can't actually save prompt from `/savePrompt` with a manual save | 0 | correctness | 3/6 Plausible | 8 | — | — |
| 50 | [#316838](https://github.com/microsoft/vscode/issues/316838) | Copilot Instructions are Ignored | 1 | correctness | 3/6 Plausible | 7 | — | — |
| 51 | [#305876](https://github.com/microsoft/vscode/issues/305876) | chat.promptFilesLocations ordering ignored | 0 | correctness | 5/6 Source-confirmed | 7 | — | — |
| 53 | [#276227](https://github.com/microsoft/vscode/issues/276227) | Weird Prompt file linting error: No link definition found | 1 | papercut | 5/6 Source-confirmed | 6 | yes | — |
| 78 | [#305545](https://github.com/microsoft/vscode/issues/305545) | Latest Copilot release causes Extreme HIGH CPU usage | 0 | perf | 3/6 Plausible | 4 | — | — |
| 90 | [#292095](https://github.com/microsoft/vscode/issues/292095) | Permission to read prompt file already attached? | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 102 | [#267828](https://github.com/microsoft/vscode/issues/267828) | Dragging a prompt file in to chat behaves as if I invoked it | 0 | correctness | 4/6 Traced | 2 | — | — |
| 105 | [#276773](https://github.com/microsoft/vscode/issues/276773) | Filename case-sensitivity in discovery of AGENTS.md files isn't consistent | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 106 | [#279464](https://github.com/microsoft/vscode/issues/279464) | The completions in the front matter is influenced by the space after the `:` | 0 | papercut | 5/6 Source-confirmed | 2 | yes | — |
| 107 | [#281799](https://github.com/microsoft/vscode/issues/281799) | Chat: Custom instruction causes fetch and Allow dialog | 0 | papercut | 3/6 Plausible | 2 | — | — |
| 108 | [#286877](https://github.com/microsoft/vscode/issues/286877) | Rendering code blocks that include `// filepath:` is buggy. | 0 | correctness | 5/6 Source-confirmed | 2 | — | — |
| 112 | [#308571](https://github.com/microsoft/vscode/issues/308571) | Fails to load my instructions.md file | 0 | none | 3/6 Plausible | 2 | — | — |
| 113 | [#318701](https://github.com/microsoft/vscode/issues/318701) | chat.instructionsFilesLocations: applyTo frontmatter changes not reflected until VS Code restart (stale cache) | 0 | correctness | 4/6 Traced | 2 | — | — |
| 118 | [#303254](https://github.com/microsoft/vscode/issues/303254) | Repeated custom-agent rescans emit endless parse errors/diagnostics for cross-tool .agent.md files | 1 | papercut | 4/6 Traced | 1 | — | — |
| 142 | [#305180](https://github.com/microsoft/vscode/issues/305180) | VS code (1.113) stopped showing me `user profile` prompt files from my UserData on windows | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 144 | [#308367](https://github.com/microsoft/vscode/issues/308367) | prompts-diagnostics-provider: false "File not found" errors for existing .md links in multi-root workspace | 0 | papercut | 3/6 Plausible | 1 | — | — |
| 148 | [#323094](https://github.com/microsoft/vscode/issues/323094) | AGENTS.md discovery still runs `rg --no-ignore --follow` over the whole tree (regression sibling of #304676) | 0 | perf | 4/6 Traced | 1 | — | — |
| 151 | [#328122](https://github.com/microsoft/vscode/issues/328122) | Chat customization discovery fires batches of ~30 concurrent full-workspace rg enumerations with --no-ignore --follow, cancelled and re-fired in a loop (1.131.0) | 0 | perf | 6/6 Confirmed | 1 | — | — |
| 175 | [#275338](https://github.com/microsoft/vscode/issues/275338) | `/savePrompt` should more clearly reveal created prompt | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 178 | [#280995](https://github.com/microsoft/vscode/issues/280995) | prompt file (slash command) won't use intended agent if run with "run in new chat" | 0 | correctness | — | 0 | — | — |
| 182 | [#294543](https://github.com/microsoft/vscode/issues/294543) | GPT models always read every instruction file | 0 | papercut | 2/6 Unverified | 0 | — | — |
| 184 | [#299288](https://github.com/microsoft/vscode/issues/299288) | Agent uses web fetch tool to access instructions | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 185 | [#299480](https://github.com/microsoft/vscode/issues/299480) | Does not load copilot-instructions.md | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 187 | [#300113](https://github.com/microsoft/vscode/issues/300113) | Personal CLAUDE.md is attached even though its empty | 0 | papercut | 4/6 Traced | 0 | — | — |
| 189 | [#305375](https://github.com/microsoft/vscode/issues/305375) | User prompt triggers "allow reading external file" | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 194 | [#318005](https://github.com/microsoft/vscode/issues/318005) | Customizations loader doesn't validate path or available file system provider | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 201 | [#328517](https://github.com/microsoft/vscode/issues/328517) | All prompts starting with / are highlighted | 0 | visual | 5/6 Source-confirmed | 0 | — | — |

### Agents and subagents (16)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 10 | [#312256](https://github.com/microsoft/vscode/issues/312256) | bug: Custom agents duplicated in agent picker when same name exists in both org-synced and local paths | 5 | correctness | 5/6 Source-confirmed | 27 | yes | — |
| 12 | [#317276](https://github.com/microsoft/vscode/issues/317276) | Custom agent selection silently reverts to generic Agent mid-session; chat dropdown still shows the stale (correct) selection while the runtime has switched | 3 | correctness | 5/6 Source-confirmed | 26 | — | — |
| 36 | [#321765](https://github.com/microsoft/vscode/issues/321765) | Custom agent frontmatter is not automatically loaded on VSCode startup. | 0 | correctness | 3/6 Plausible | 10 | — | — |
| 46 | [#311329](https://github.com/microsoft/vscode/issues/311329) | Custom subagent resolves to model outside its configured model list | 0 | correctness | 4/6 Traced | 8 | — | — |
| 49 | [#312254](https://github.com/microsoft/vscode/issues/312254) | Agents: Plan doesn't show up as a custom agent type | 1 | correctness | 3/6 Plausible | 7 | — | — |
| 77 | [#289206](https://github.com/microsoft/vscode/issues/289206) | runSubagent picks the wrong subagent | 0 | correctness | — | 4 | — | — |
| 79 | [#320993](https://github.com/microsoft/vscode/issues/320993) | Agents Window: Custom agents disappear from dropdown after sending a message | 0 | correctness | 3/6 Plausible | 4 | — | — |
| 82 | [#318422](https://github.com/microsoft/vscode/issues/318422) | Duplicate Copilot agents shown when contributed by both VS Code extension and Copilot CLI plugin | 2 | papercut | 6/6 Confirmed | 3 | — | — |
| 91 | [#315032](https://github.com/microsoft/vscode/issues/315032) | Subagent fails to resolve custom OAI model although available for main agent | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 111 | [#306644](https://github.com/microsoft/vscode/issues/306644) | Subagents are not being discovered | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 138 | [#291094](https://github.com/microsoft/vscode/issues/291094) | custom agent model - unexpected fallback to Auto when model is unavailable | 0 | correctness | — | 1 | — | — |
| 145 | [#311567](https://github.com/microsoft/vscode/issues/311567) | [Possible Regression] Custom agent MCP tools not available when invoked as sub-agent via Task tool | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 180 | [#289427](https://github.com/microsoft/vscode/issues/289427) | Agent doesn't use enough subagents when research/tasks can be done parallel | 0 | none | — | 0 | — | — |
| 181 | [#290762](https://github.com/microsoft/vscode/issues/290762) | Custom Agents: Models in defined in custom agent do not lead to different models showing in models picker, should they? | 0 | none | — | 0 | — | — |
| 190 | [#306285](https://github.com/microsoft/vscode/issues/306285) | Custom Agent selection spontaneously resets to default when plugin auto update is enabled | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 198 | [#323929](https://github.com/microsoft/vscode/issues/323929) | Custom agents disappear and reappear in v1.126 | 0 | correctness | 3/6 Plausible | 0 | — | — |

### Tools skills and plugins (21)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 13 | [#267413](https://github.com/microsoft/vscode/issues/267413) | When using user defined tool sets shows wrong count | 5 | visual | 5/6 Source-confirmed | 25 | — | — |
| 15 | [#306227](https://github.com/microsoft/vscode/issues/306227) | Copilot Agent Skill Validation Conflicts with "skill" Language ID (Cadence SKILL Programming Language) | 4 | correctness | 5/6 Source-confirmed | 23 | yes | — |
| 22 | [#302181](https://github.com/microsoft/vscode/issues/302181) | Skills duplication when 'Agent Skills Location' overlaps with 'Plugin Locations' | 0 | visual | 3/6 Plausible | 13 | — | — |
| 24 | [#325670](https://github.com/microsoft/vscode/issues/325670) | Skills don't always show as completions in agents window | 0 | correctness | 5/6 Source-confirmed | 13 | — | — |
| 30 | [#288698](https://github.com/microsoft/vscode/issues/288698) | Tool picker doesn't work properly when editing a prompt | 0 | correctness | 5/6 Source-confirmed | 11 | yes | — |
| 42 | [#291746](https://github.com/microsoft/vscode/issues/291746) | AI Agent Skills cannot read symbolic links | 0 | correctness | 3/6 Plausible | 9 | — | — |
| 52 | [#305994](https://github.com/microsoft/vscode/issues/305994) | execution_subagent doesn't have skill context | 0 | correctness | 5/6 Source-confirmed | 7 | — | — |
| 54 | [#314020](https://github.com/microsoft/vscode/issues/314020) | chat plugins: Claude-format plugin frontmatter (rules `paths`, agents `tools`/`model`) is not transformed when installed via marketplace or pluginLocations | 1 | correctness | 4/6 Traced | 6 | — | — |
| 55 | [#256906](https://github.com/microsoft/vscode/issues/256906) | Tool Picker has all tools enabled, but Add Context shows old tools list | 0 | correctness | 3/6 Plausible | 6 | — | — |
| 56 | [#260556](https://github.com/microsoft/vscode/issues/260556) | Configure tools... action should respect the tools I configured in my markdown file | 0 | papercut | 5/6 Source-confirmed | 6 | yes | — |
| 57 | [#282750](https://github.com/microsoft/vscode/issues/282750) | Remember workspace specific tool disablement | 0 | correctness | — | 6 | — | — |
| 140 | [#297587](https://github.com/microsoft/vscode/issues/297587) | Tool descriptions don't mention any languages | 0 | papercut | — | 1 | — | — |
| 141 | [#301382](https://github.com/microsoft/vscode/issues/301382) | "Skipping duplicate agent skill name" log spam | 0 | papercut | 2/6 Unverified | 1 | — | — |
| 147 | [#319702](https://github.com/microsoft/vscode/issues/319702) | Clicking on "Plugins" in Agents window opens generic customizations view instead of Plugins view | 0 | correctness | — | 1 | — | — |
| 176 | [#275525](https://github.com/microsoft/vscode/issues/275525) | Invalid autocomplete options in tools array | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 177 | [#275628](https://github.com/microsoft/vscode/issues/275628) | Every tool is selected after reloading if I open the tools list too early during startup | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 179 | [#285872](https://github.com/microsoft/vscode/issues/285872) | Custom Agent references multiple tools using 'search' | 0 | correctness | 4/6 Traced | 0 | — | — |
| 183 | [#298131](https://github.com/microsoft/vscode/issues/298131) | Tools frontmatter on do not work with toolsets that have mcp tools. Only built in work | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 188 | [#302865](https://github.com/microsoft/vscode/issues/302865) | Hooks not getting invoked from plugins installed from agentplugins marketplace | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 191 | [#307149](https://github.com/microsoft/vscode/issues/307149) | Skill triggers external file allow dialog | 0 | papercut | 4/6 Traced | 0 | — | — |
| 193 | [#308887](https://github.com/microsoft/vscode/issues/308887) | Chat/Configure Tools/Update Tools disables OK button, unless fold tool | 0 | papercut | 3/6 Plausible | 0 | — | — |

### HTML and styles (36)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 14 | [#169117](https://github.com/microsoft/vscode/issues/169117) | [html] "Cannot redeclare block-scoped variable" in script type module | 5 | correctness | 5/6 Source-confirmed | 23 | yes | — |
| 27 | [#126507](https://github.com/microsoft/vscode/issues/126507) | [scss] map value override => identifier expected | 6 | correctness | 5/6 Source-confirmed | 11 | — | — |
| 28 | [#137938](https://github.com/microsoft/vscode/issues/137938) | [html] "Auto Closing Tags" adds unnecessary tags in some cases with prettier-vscode | 2 | correctness | 4/6 Traced | 11 | — | — |
| 38 | [#184666](https://github.com/microsoft/vscode/issues/184666) | Toggle line comment doesn't work for multiple lines in CSS | 2 | correctness | 5/6 Source-confirmed | 9 | — | — |
| 60 | [#79631](https://github.com/microsoft/vscode/issues/79631) | [html] don't validate custom event handlers as JavaScript | 11 | papercut | 5/6 Source-confirmed | 5 | yes | [draft PR](https://github.com/egamma/vscode/pull/1) |
| 65 | [#189156](https://github.com/microsoft/vscode/issues/189156) | [scss] Cannot open `.scss` files using `@use` import syntax | 0 | correctness | 3/6 Plausible | 5 | — | — |
| 66 | [#233806](https://github.com/microsoft/vscode/issues/233806) | [html] False error of inline Javascript in HTML | 0 | correctness | 5/6 Source-confirmed | 5 | yes | — |
| 76 | [#267871](https://github.com/microsoft/vscode/issues/267871) | [html] problem range in embedded content needs to be limited to embedded range. | 0 | correctness | 5/6 Source-confirmed | 4 | yes | — |
| 84 | [#71091](https://github.com/microsoft/vscode/issues/71091) | [html] bracket matching in strings | 1 | visual | 5/6 Source-confirmed | 3 | — | — |
| 94 | [#272091](https://github.com/microsoft/vscode/issues/272091) | [html] Auto-complete in embedded JavaScript does not work when no space is present | 1 | papercut | 4/6 Traced | 2 | — | — |
| 95 | [#71813](https://github.com/microsoft/vscode/issues/71813) | [css] highlighting not working for some transition properties | 0 | visual | 4/6 Traced | 2 | yes | — |
| 98 | [#149667](https://github.com/microsoft/vscode/issues/149667) | [scss] don't autocomplete in comments | 0 | papercut | 4/6 Traced | 2 | — | — |
| 101 | [#245579](https://github.com/microsoft/vscode/issues/245579) | [scss] "Follow link" on `@use`/`@import` statements with absolute paths not working with node_modules. | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 116 | [#144767](https://github.com/microsoft/vscode/issues/144767) | [scss] variables in @media parsing | 1 | papercut | 3/6 Plausible | 1 | — | — |
| 117 | [#227452](https://github.com/microsoft/vscode/issues/227452) | [scss] inbuild sass/scss extension shows error that is none | 1 | papercut | 4/6 Traced | 1 | — | — |
| 121 | [#111025](https://github.com/microsoft/vscode/issues/111025) | [html] HTML line wrapping on paste occurs before auto-indenting | 0 | correctness | 4/6 Traced | 1 | — | — |
| 122 | [#111760](https://github.com/microsoft/vscode/issues/111760) | [html] handle HTML-escaped characters in JavaScript attribute properties | 0 | correctness | 5/6 Source-confirmed | 1 | yes | — |
| 126 | [#145701](https://github.com/microsoft/vscode/issues/145701) | [css] Inconsistent results when formatting range/selection | 0 | correctness | 4/6 Traced | 1 | — | — |
| 127 | [#169900](https://github.com/microsoft/vscode/issues/169900) | [scss] Display a wrong selector preview when using sibling combinators in SCSS, Less | 0 | visual | 5/6 Source-confirmed | 1 | — | — |
| 129 | [#210303](https://github.com/microsoft/vscode/issues/210303) | [html] Format does not work if script tag parameters do not have quotes | 0 | correctness | 4/6 Traced | 1 | — | — |
| 131 | [#225545](https://github.com/microsoft/vscode/issues/225545) | [html] Relative links don't work with <base> element | 0 | correctness | 4/6 Traced | 1 | yes | — |
| 132 | [#227764](https://github.com/microsoft/vscode/issues/227764) | [html] highlighting does not detect end script tag in string literals | 0 | correctness | 5/6 Source-confirmed | 1 | — | — |
| 133 | [#236215](https://github.com/microsoft/vscode/issues/236215) | [css] `:after' suggested inside comment | 0 | papercut | 5/6 Source-confirmed | 1 | — | — |
| 153 | [#77923](https://github.com/microsoft/vscode/issues/77923) | [html] auto close tags being inserted before its html content | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 154 | [#78893](https://github.com/microsoft/vscode/issues/78893) | [html] autoclose not working properly with multicursor | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 155 | [#78978](https://github.com/microsoft/vscode/issues/78978) | [css] SCSS/SASS Auto Intellisense doesn't work after last entry | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 158 | [#135849](https://github.com/microsoft/vscode/issues/135849) | [html] Unexpected "Declaration or statement expected" in HTML code | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 159 | [#156656](https://github.com/microsoft/vscode/issues/156656) | [html] Duplicate double quotes are inserted for HTML attributes when working over SSH | 0 | papercut | 4/6 Traced | 0 | — | — |
| 160 | [#160987](https://github.com/microsoft/vscode/issues/160987) | [scss] Wrongly shown selector in SCSS | 0 | papercut | — | 0 | — | — |
| 161 | [#163649](https://github.com/microsoft/vscode/issues/163649) | [less] support `each` in keyframes | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 163 | [#172233](https://github.com/microsoft/vscode/issues/172233) | [css] missing colon causes error to be placed on next rule | 0 | papercut | — | 0 | — | — |
| 164 | [#173086](https://github.com/microsoft/vscode/issues/173086) | [html] format on paste removes whitespace | 0 | papercut | — | 0 | — | — |
| 168 | [#188623](https://github.com/microsoft/vscode/issues/188623) | [html] Links with fragment can't be Ctrl+clicked | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 169 | [#213628](https://github.com/microsoft/vscode/issues/213628) | [html] Formatting Breaks with Space Between Commented Lines in Script Tag | 0 | papercut | 4/6 Traced | 0 | — | — |
| 174 | [#269346](https://github.com/microsoft/vscode/issues/269346) | [html] Incorrect onclick attribute Parsing | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 200 | [#327353](https://github.com/microsoft/vscode/issues/327353) | When editor.formatOnSave is true, inserts unwanted spaces in CSS tailwind classes like focus: | 0 | correctness | 3/6 Plausible | 0 | — | — |

### Workbench interface (16)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 17 | [#325658](https://github.com/microsoft/vscode/issues/325658) | Creating a Profile from a default Template won't save. | 0 | correctness | 6/6 Confirmed | 17 | — | — |
| 63 | [#306812](https://github.com/microsoft/vscode/issues/306812) | White flash when reloading window & using Dark theme | 1 | visual | 4/6 Traced | 5 | — | — |
| 75 | [#189129](https://github.com/microsoft/vscode/issues/189129) | [themes] Theme is getting switched on switching profiles | 0 | correctness | 3/6 Plausible | 4 | — | — |
| 87 | [#182627](https://github.com/microsoft/vscode/issues/182627) | Recent entry URL can get too large for Windows jumplist | 0 | correctness | 4/6 Traced | 3 | yes | — |
| 88 | [#243826](https://github.com/microsoft/vscode/issues/243826) | theme-seti overrides langauge extension icons by file extension, not by language | 0 | visual | 5/6 Source-confirmed | 3 | — | — |
| 92 | [#149478](https://github.com/microsoft/vscode/issues/149478) | Some keyboard shortcuts ignored in Safari/vscode.dev | 2 | papercut | 5/6 Source-confirmed | 2 | — | — |
| 93 | [#184679](https://github.com/microsoft/vscode/issues/184679) | Fuzzy search not working well in Recent Folders quickpick in 1.79.0 | 1 | papercut | 5/6 Source-confirmed | 2 | — | — |
| 96 | [#115672](https://github.com/microsoft/vscode/issues/115672) | Twisties appear only after the view has loaded for the view | 0 | visual | 3/6 Plausible | 2 | — | — |
| 114 | [#319919](https://github.com/microsoft/vscode/issues/319919) | workbench.colorTheme getting wiped when switching profiles | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 125 | [#142373](https://github.com/microsoft/vscode/issues/142373) | `Recently opened` project names get changed randomly | 0 | visual | 3/6 Plausible | 1 | — | — |
| 150 | [#326826](https://github.com/microsoft/vscode/issues/326826) | [Error] unhandlederror-Problems parsing file icons file: , Closing brace expected, Closing brace expected | 0 | correctness | 5/6 Source-confirmed | 1 | — | — |
| 165 | [#177363](https://github.com/microsoft/vscode/issues/177363) | The material icons of folders in the HTML files are not displayed. Did anyone have such a problem? | 0 | visual | 3/6 Plausible | 0 | — | — |
| 170 | [#227484](https://github.com/microsoft/vscode/issues/227484) | Custom controls need to provide proper textual name, role, and state information | 0 | papercut | 5/6 Source-confirmed | 0 | — | — |
| 173 | [#255388](https://github.com/microsoft/vscode/issues/255388) | Wrong file icon rendering in Files & Folders picker | 0 | visual | 2/6 Unverified | 0 | — | — |
| 197 | [#321461](https://github.com/microsoft/vscode/issues/321461) | agent window updates UI in multiple stages | 0 | visual | 3/6 Plausible | 0 | — | — |
| 199 | [#325667](https://github.com/microsoft/vscode/issues/325667) | Migrate prompts does not use the vs code native scroll bar | 0 | visual | 2/6 Unverified | 0 | — | — |

### Code folding (14)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 19 | [#194806](https://github.com/microsoft/vscode/issues/194806) | [folding] Editor expands when a folding provider comes in with delay | 2 | visual | 5/6 Source-confirmed | 15 | yes | — |
| 29 | [#245849](https://github.com/microsoft/vscode/issues/245849) | [folding] folding gets messed up after Copilot edits a file | 1 | correctness | 3/6 Plausible | 11 | — | — |
| 34 | [#132784](https://github.com/microsoft/vscode/issues/132784) | [folding] Newlines created by Insert Line Above command get sucked into previous code fold | 1 | correctness | 2/6 Unverified | 10 | — | — |
| 37 | [#165266](https://github.com/microsoft/vscode/issues/165266) | [folidng] python ranges unfold when the folding ranges are coming late | 2 | correctness | 5/6 Source-confirmed | 9 | yes | — |
| 47 | [#324163](https://github.com/microsoft/vscode/issues/324163) | Agentic AI ruins folding / collapsing | 0 | correctness | 3/6 Plausible | 8 | — | — |
| 61 | [#201431](https://github.com/microsoft/vscode/issues/201431) | [folding] Manual folding range not useful after copy-paste | 1 | papercut | 5/6 Source-confirmed | 5 | — | — |
| 72 | [#75726](https://github.com/microsoft/vscode/issues/75726) | [folding] folding indicators missing for folded code | 0 | correctness | 3/6 Plausible | 4 | — | — |
| 97 | [#122657](https://github.com/microsoft/vscode/issues/122657) | [folding] region ranges not restored when editor is opened the first time. | 0 | correctness | 4/6 Traced | 2 | — | — |
| 100 | [#192775](https://github.com/microsoft/vscode/issues/192775) | [folding] Imports are not collapsed added first | 0 | papercut | 4/6 Traced | 2 | yes | — |
| 130 | [#215958](https://github.com/microsoft/vscode/issues/215958) | [folding] pasting over collapsed blocks leaves random lines collapsed | 0 | visual | 4/6 Traced | 1 | — | — |
| 136 | [#289224](https://github.com/microsoft/vscode/issues/289224) | vscode corrupts source code when toggling comments on folded regions | 0 | none | — | 1 | — | — |
| 152 | [#46654](https://github.com/microsoft/vscode/issues/46654) | [folding] Fold block comments scrolls editor | 0 | papercut | 5/6 Source-confirmed | 0 | — | — |
| 172 | [#246388](https://github.com/microsoft/vscode/issues/246388) | Git: deletion marker in the gutter disappears when folding adjacent regions | 0 | visual | 5/6 Source-confirmed | 0 | yes | — |
| 195 | [#319286](https://github.com/microsoft/vscode/issues/319286) | [folding] Format large file unfold all code | 0 | correctness | 3/6 Plausible | 0 | — | — |

### JSON and settings (12)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 21 | [#326018](https://github.com/microsoft/vscode/issues/326018) | Settings schema shows valid color customization properties as invalid | 3 | correctness | 6/6 Confirmed | 14 | — | — |
| 31 | [#45207](https://github.com/microsoft/vscode/issues/45207) | [json] External schemas referenced from schema not updated | 3 | correctness | 4/6 Traced | 10 | — | — |
| 32 | [#327228](https://github.com/microsoft/vscode/issues/327228) | `npm view --json` returns an array since npm 12 and breaks hover metadata in package.json | 2 | correctness | 5/6 Source-confirmed | 10 | — | — |
| 33 | [#328165](https://github.com/microsoft/vscode/issues/328165) | Bug in Settings / workbench.colorCustomizations | 2 | correctness | 6/6 Confirmed | 10 | — | — |
| 48 | [#42679](https://github.com/microsoft/vscode/issues/42679) | [json] schema Validation/Intellisense very slow when JSON deep and Schema Complex | 3 | perf | — | 7 | — | — |
| 64 | [#167939](https://github.com/microsoft/vscode/issues/167939) | "editor.inlineSuggest.enabled" add extra quote when using tab in a "workbench.colorCustomizations" settings | 0 | correctness | 2/6 Unverified | 5 | — | — |
| 83 | [#43195](https://github.com/microsoft/vscode/issues/43195) | [json] launch.json completion for "type" does not include expected values | 1 | correctness | — | 3 | — | — |
| 99 | [#184904](https://github.com/microsoft/vscode/issues/184904) | [json] Schema changes not reflected if schema file has jsonc extension. | 0 | correctness | 5/6 Source-confirmed | 2 | yes | — |
| 115 | [#109141](https://github.com/microsoft/vscode/issues/109141) | [json] symlink prevents JSON schema from updating validation | 1 | papercut | 4/6 Traced | 1 | — | — |
| 124 | [#136645](https://github.com/microsoft/vscode/issues/136645) | [json] Explorer Outline view shows wrong int values when viewing JSON document | 0 | correctness | 5/6 Source-confirmed | 1 | — | — |
| 128 | [#189802](https://github.com/microsoft/vscode/issues/189802) | [json] validation not working for a large enough number | 0 | correctness | 4/6 Traced | 1 | — | — |
| 149 | [#326140](https://github.com/microsoft/vscode/issues/326140) | Package.json dependency metadata lookup; slow with PNPM | 0 | perf | 5/6 Source-confirmed | 1 | — | — |

### Other (5)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 134 | [#280873](https://github.com/microsoft/vscode/issues/280873) | bad api doc continuations for rust | 0 | papercut | 2/6 Unverified | 1 | — | — |
| 139 | [#291496](https://github.com/microsoft/vscode/issues/291496) | GPT-5-Codex (Preview) runaway halucinations and obstinate disobediance. | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 143 | [#306240](https://github.com/microsoft/vscode/issues/306240) | Github Copilot warnings | 0 | papercut | 3/6 Plausible | 1 | — | — |
| 186 | [#300066](https://github.com/microsoft/vscode/issues/300066) | Not working | 0 | none | 3/6 Plausible | 0 | — | — |
| 196 | [#319586](https://github.com/microsoft/vscode/issues/319586) | This is the current issue i am facing as vs code is lagging a lot | 0 | perf | 3/6 Plausible | 0 | — | — |

## Feature requests

### Language platform (15)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | [#50140](https://github.com/microsoft/vscode/issues/50140) | Support syntax highlighting with tree-sitter | 738 | backlog-candidate | 100 | — |
| 19 | [#242156](https://github.com/microsoft/vscode/issues/242156) | Add basic toml support | 53 | backlog-candidate | 7 | — |
| 27 | [#216](https://github.com/microsoft/vscode/issues/216) | [grammars] provide alternative to TextMate grammars | 50 | backlog-candidate | 5 | — |
| 67 | [#97063](https://github.com/microsoft/vscode/issues/97063) | [semantic] proposals for new standard semantic token types | 7 | backlog-candidate | 2 | — |
| 103 | [#327247](https://github.com/microsoft/vscode/issues/327247) | Support DocumentSymbolProvider in CustomTextEditor | 4 | active | 1 | — |
| 108 | [#192144](https://github.com/microsoft/vscode/issues/192144) | VSCode client libraries have invalid exports | 2 | backlog-candidate | 1 | — |
| 138 | [#326782](https://github.com/microsoft/vscode/issues/326782) | Add support for CSV files | 3 | active | 0 | — |
| 157 | [#327506](https://github.com/microsoft/vscode/issues/327506) | [semantic] Add a `parameter` semantic token modifier | 2 | backlog-candidate | 0 | — |
| 175 | [#128565](https://github.com/microsoft/vscode/issues/128565) | [semantic highlighting] Source language suffix should be added to semantic token fallback scopes when looked up | 1 | backlog-candidate | 0 | — |
| 199 | [#41320](https://github.com/microsoft/vscode/issues/41320) | [xml] add on enter rules | 0 | backlog-candidate | 0 | — |
| 224 | [#94269](https://github.com/microsoft/vscode/issues/94269) | [semantic tokens] provide code assist for tokenModifiers | 0 | backlog-candidate | 0 | — |
| 267 | [#197881](https://github.com/microsoft/vscode/issues/197881) | [languages] contribution point `languages` provide the ability to extends | 0 | backlog-candidate | 0 | — |
| 271 | [#227697](https://github.com/microsoft/vscode/issues/227697) | LSP DocumentColor Refresh Request | 0 | backlog-candidate | 0 | — |
| 281 | [#252011](https://github.com/microsoft/vscode/issues/252011) | Allow Diagnostic providers to enrich AI-driven fix workflows with context via an optional method | 0 | backlog-candidate | 0 | — |
| 344 | [#318363](https://github.com/microsoft/vscode/issues/318363) | LSP Format Code support CLI | 0 | backlog-candidate | 0 | — |

### JSON language support (48)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 2 | [#155379](https://github.com/microsoft/vscode/issues/155379) | [json] support meta-schema features | 357 | backlog-candidate | 33 | — |
| 8 | [#98724](https://github.com/microsoft/vscode/issues/98724) | [json] JSONSchema draft 2019-09 support | 147 | backlog-candidate | 13 | — |
| 14 | [#165219](https://github.com/microsoft/vscode/issues/165219) | [json] Support json-schema draft 2020-12 | 107 | backlog-candidate | 10 | — |
| 18 | [#236814](https://github.com/microsoft/vscode/issues/236814) | [json] Automatically Escape Pasted Text in JSON string | 58 | backlog-candidate | 7 | — |
| 29 | [#224581](https://github.com/microsoft/vscode/issues/224581) | [json] colorize string literals based on language information coming from schemas | 34 | backlog-candidate | 5 | — |
| 52 | [#251315](https://github.com/microsoft/vscode/issues/251315) | Support JSON schema draft 2020-12 | 4 | active | 3 | — |
| 56 | [#69545](https://github.com/microsoft/vscode/issues/69545) | [json] add commas automatically | 26 | backlog-candidate | 2 | — |
| 57 | [#124393](https://github.com/microsoft/vscode/issues/124393) | [json] show number of children in JSON arrays | 25 | backlog-candidate | 2 | — |
| 58 | [#74943](https://github.com/microsoft/vscode/issues/74943) | [json] Override/disable json-schema for package.json | 24 | backlog-candidate | 2 | — |
| 59 | [#26289](https://github.com/microsoft/vscode/issues/26289) | [json] use the schemastore catalog | 23 | backlog-candidate | 2 | — |
| 68 | [#76505](https://github.com/microsoft/vscode/issues/76505) | [json] format on save should remove last trailing comma in JSON with json-language-features | 18 | backlog-candidate | 1 | — |
| 70 | [#24869](https://github.com/microsoft/vscode/issues/24869) | [json] option to format code with leading commas | 17 | backlog-candidate | 1 | — |
| 71 | [#139752](https://github.com/microsoft/vscode/issues/139752) | [json] Local JSON schemas should find each other based on their id fields | 17 | backlog-candidate | 1 | — |
| 72 | [#11828](https://github.com/microsoft/vscode/issues/11828) | [json] validation doesn't work offline | 16 | backlog-candidate | 1 | — |
| 73 | [#42758](https://github.com/microsoft/vscode/issues/42758) | [json] improve property suggestions with oneOf | 15 | backlog-candidate | 1 | — |
| 77 | [#54248](https://github.com/microsoft/vscode/issues/54248) | [json] package.json: complete package versions from scopes or private registries | 13 | backlog-candidate | 1 | — |
| 88 | [#230136](https://github.com/microsoft/vscode/issues/230136) | [json] Add support for extensions associating JSON schemas with documents dynamically (via API) | 7 | backlog-candidate | 1 | — |
| 91 | [#138546](https://github.com/microsoft/vscode/issues/138546) | [json] open definition in JSON document to navigate to the schema definition | 5 | backlog-candidate | 1 | — |
| 120 | [#44135](https://github.com/microsoft/vscode/issues/44135) | [json] schema fileMatch for all *.json files in root folder | 5 | backlog-candidate | 0 | — |
| 123 | [#81782](https://github.com/microsoft/vscode/issues/81782) | [json] allow $ref in confiuguration schemas | 4 | backlog-candidate | 0 | — |
| 127 | [#139538](https://github.com/microsoft/vscode/issues/139538) | [json] support references in schema associations | 4 | backlog-candidate | 0 | — |
| 132 | [#42786](https://github.com/microsoft/vscode/issues/42786) | [json] Automatically add required fields to object | 3 | backlog-candidate | 0 | — |
| 151 | [#208647](https://github.com/microsoft/vscode/issues/208647) | [jsonl] Support `JSON` formatter in `JSONL` | 2 | backlog-candidate | 0 | — |
| 163 | [#69546](https://github.com/microsoft/vscode/issues/69546) | [json] add colon automatically | 1 | backlog-candidate | 0 | — |
| 164 | [#71115](https://github.com/microsoft/vscode/issues/71115) | [json] Provide support for highlighting the source of the error in json files rather than highlighting the entire file | 1 | backlog-candidate | 0 | — |
| 171 | [#116540](https://github.com/microsoft/vscode/issues/116540) | [json] support link on $ref for external references | 1 | backlog-candidate | 0 | — |
| 172 | [#117013](https://github.com/microsoft/vscode/issues/117013) | [json] NPM package for vscode-json-languageserver not sync'd with VSCode releases | 1 | backlog-candidate | 0 | — |
| 174 | [#120629](https://github.com/microsoft/vscode/issues/120629) | [json] Pick part of JSON schema with more matching properties | 1 | backlog-candidate | 0 | — |
| 181 | [#227592](https://github.com/microsoft/vscode/issues/227592) | [json] Intellisense doesn't suggest objects as a possibility when next to string enums | 1 | backlog-candidate | 0 | — |
| 198 | [#40604](https://github.com/microsoft/vscode/issues/40604) | [json] suggest used values when property name has already been used | 0 | backlog-candidate | 0 | — |
| 204 | [#47197](https://github.com/microsoft/vscode/issues/47197) | [json] completion has bad replacement span, overwrites comment | 0 | backlog-candidate | 0 | — |
| 206 | [#53454](https://github.com/microsoft/vscode/issues/53454) | [json] don't suggest top level snippet if there's already an object | 0 | backlog-candidate | 0 | — |
| 230 | [#105998](https://github.com/microsoft/vscode/issues/105998) | [json] Format selection doesn't fix indentation | 0 | backlog-candidate | 0 | — |
| 231 | [#109984](https://github.com/microsoft/vscode/issues/109984) | [json] UI for anyOf settings tooltips needs improvement | 0 | backlog-candidate | 0 | — |
| 232 | [#110794](https://github.com/microsoft/vscode/issues/110794) | [json] no IntelliSense when all-optional branch matches | 0 | backlog-candidate | 0 | — |
| 245 | [#125147](https://github.com/microsoft/vscode/issues/125147) | [json] Add enumSortText for JSON schemas | 0 | backlog-candidate | 0 | — |
| 247 | [#127226](https://github.com/microsoft/vscode/issues/127226) | [json] create diagnostics text out of markdownDeprecationMessage | 0 | dormant | 0 | — |
| 248 | [#128971](https://github.com/microsoft/vscode/issues/128971) | [json] create links for values of format `uri-reference` | 0 | backlog-candidate | 0 | — |
| 249 | [#135552](https://github.com/microsoft/vscode/issues/135552) | [json editing] don't remove the comments of the next property node when removing first property | 0 | backlog-candidate | 0 | — |
| 259 | [#155101](https://github.com/microsoft/vscode/issues/155101) | [json] Show key value pairs of JSON Array in `Outline` view | 0 | backlog-candidate | 0 | — |
| 261 | [#175090](https://github.com/microsoft/vscode/issues/175090) | [json] warn if a color that requires opacity doesn't set it | 0 | backlog-candidate | 0 | — |
| 268 | [#209023](https://github.com/microsoft/vscode/issues/209023) | [json] Provide a way to disable the json-validation contribution point of a specific extension (e.g. ESLint) | 0 | backlog-candidate | 0 | — |
| 269 | [#219855](https://github.com/microsoft/vscode/issues/219855) | [json] allow to override & replace existing schemas | 0 | backlog-candidate | 0 | — |
| 272 | [#228528](https://github.com/microsoft/vscode/issues/228528) | [json] builtin json formatter doesn't support format-on-paste | 0 | backlog-candidate | 0 | — |
| 276 | [#249624](https://github.com/microsoft/vscode/issues/249624) | [json] JSON Schema anyOf error reporting is misleading | 0 | backlog-candidate | 0 | — |
| 284 | [#252610](https://github.com/microsoft/vscode/issues/252610) | expose the `jsonSchemaRegistry` in the extension API | 0 | backlog-candidate | 0 | — |
| 306 | [#269250](https://github.com/microsoft/vscode/issues/269250) | [json] show a notification when retrying to load a schema fails | 0 | backlog-candidate | 0 | — |
| 326 | [#284339](https://github.com/microsoft/vscode/issues/284339) | Allow .json files to support comments when a specific comment line is at the top of the file. | 0 | backlog-candidate | 0 | — |

### Themes and icons (39)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 3 | [#12493](https://github.com/microsoft/vscode/issues/12493) | [icon-themes] Support for globs in file associations (Icon themes) | 361 | backlog-candidate | 25 | — |
| 5 | [#20652](https://github.com/microsoft/vscode/issues/20652) | [themes] different themes for different filetypes | 301 | backlog-candidate | 21 | — |
| 6 | [#32813](https://github.com/microsoft/vscode/issues/32813) | [theming] Access theme's colors programmatically | 290 | backlog-candidate | 21 | — |
| 7 | [#25986](https://github.com/microsoft/vscode/issues/25986) | [theming] Separate workbench theme and syntax theme | 193 | backlog-candidate | 14 | — |
| 12 | [#32579](https://github.com/microsoft/vscode/issues/32579) | [themes] Disable Italic Option Feature Request | 150 | backlog-candidate | 11 | — |
| 15 | [#44026](https://github.com/microsoft/vscode/issues/44026) | [theming] customize file icons in settings | 97 | backlog-candidate | 7 | — |
| 24 | [#271485](https://github.com/microsoft/vscode/issues/271485) | Reconsider adding settings for preferred icon theme for light and dark modes | 35 | backlog-candidate | 6 | — |
| 41 | [#92736](https://github.com/microsoft/vscode/issues/92736) | [themes] Allow gradients along with colors | 45 | backlog-candidate | 3 | — |
| 48 | [#200451](https://github.com/microsoft/vscode/issues/200451) | [themes] globally change saturation and contrast | 28 | backlog-candidate | 3 | — |
| 50 | [#263108](https://github.com/microsoft/vscode/issues/263108) | Surface the vscode://schemas/color-theme schema to allow for programmatic use | 24 | backlog-candidate | 3 | — |
| 61 | [#188989](https://github.com/microsoft/vscode/issues/188989) | [themes] mark favorites themes | 23 | backlog-candidate | 2 | — |
| 64 | [#56855](https://github.com/microsoft/vscode/issues/56855) | [themes] Allow custom variables and references in workbench color customizations section | 19 | backlog-candidate | 2 | — |
| 75 | [#45963](https://github.com/microsoft/vscode/issues/45963) | [icon themes] Expose API to provide a dynamic icon theme. | 14 | backlog-candidate | 1 | — |
| 76 | [#72945](https://github.com/microsoft/vscode/issues/72945) | [themes] Support for hue, saturation, lightness (HSL) color codes for theming | 14 | backlog-candidate | 1 | — |
| 110 | [#305685](https://github.com/microsoft/vscode/issues/305685) | Using "Toggle between Light/Dark Themes" resets theme | 2 | active | 1 | — |
| 122 | [#78758](https://github.com/microsoft/vscode/issues/78758) | [themes] Show extension info in Preferences: Color Theme panel | 4 | backlog-candidate | 0 | — |
| 125 | [#105247](https://github.com/microsoft/vscode/issues/105247) | [theme] allow variables in the color theme definition file | 4 | backlog-candidate | 0 | — |
| 130 | [#28299](https://github.com/microsoft/vscode/issues/28299) | [theme] Request the feature: "editor.lineHighlightForeground". | 3 | backlog-candidate | 0 | — |
| 134 | [#62637](https://github.com/microsoft/vscode/issues/62637) | [theme] inspect tool for workbench colors | 3 | backlog-candidate | 0 | — |
| 143 | [#74342](https://github.com/microsoft/vscode/issues/74342) | [themes] Allow to set a background color for settings / webview editors | 2 | backlog-candidate | 0 | — |
| 146 | [#101556](https://github.com/microsoft/vscode/issues/101556) | [themes] 'Generate Color Theme From Current Settings' omits semantic token settings | 2 | dormant | 0 | — |
| 147 | [#103109](https://github.com/microsoft/vscode/issues/103109) | [theming] token type hierarchy to the 'Developer: Inspect Editor Tokens and Scopes' command | 2 | backlog-candidate | 0 | — |
| 148 | [#177650](https://github.com/microsoft/vscode/issues/177650) | [icon-themes] explore using attribute selectors to allow name patterns and simplify implementation | 2 | backlog-candidate | 0 | — |
| 150 | [#188594](https://github.com/microsoft/vscode/issues/188594) | [themes] support non-HEX formats in color customizations | 2 | backlog-candidate | 0 | — |
| 156 | [#305166](https://github.com/microsoft/vscode/issues/305166) | Support for native, context-aware File and Folder Icons (JetBrains-style) | 2 | active | 0 | — |
| 173 | [#119047](https://github.com/microsoft/vscode/issues/119047) | [themes] use both English and UI language to search color theme names | 1 | backlog-candidate | 0 | — |
| 195 | [#318198](https://github.com/microsoft/vscode/issues/318198) | Default themes should not include markdown suffix | 1 | active | 0 | — |
| 217 | [#84486](https://github.com/microsoft/vscode/issues/84486) | [themes] provide command to change theme | 0 | backlog-candidate | 0 | — |
| 219 | [#86308](https://github.com/microsoft/vscode/issues/86308) | [themes] Minimal icon theme should use icon font | 0 | backlog-candidate | 0 | — |
| 234 | [#111616](https://github.com/microsoft/vscode/issues/111616) | [theme icons] Include color class in ThemeIcon.asClassName() | 0 | backlog-candidate | 0 | — |
| 235 | [#117437](https://github.com/microsoft/vscode/issues/117437) | [product icon themes] No fallback for using icon contribution point | 0 | backlog-candidate | 0 | — |
| 236 | [#117822](https://github.com/microsoft/vscode/issues/117822) | [product icon themes] theme icons support for vscode.show(Information\|Warning\|Error)Message | 0 | backlog-candidate | 0 | — |
| 253 | [#145677](https://github.com/microsoft/vscode/issues/145677) | [themes] Preserve my search for theme search in marketplace | 0 | backlog-candidate | 0 | — |
| 273 | [#228977](https://github.com/microsoft/vscode/issues/228977) | [themes] support sematic colorization for 'excludedCode' | 0 | backlog-candidate | 0 | — |
| 279 | [#250444](https://github.com/microsoft/vscode/issues/250444) | Add a custom icon for prompt, chat mode and instruction files | 0 | backlog-candidate | 0 | — |
| 301 | [#266685](https://github.com/microsoft/vscode/issues/266685) | Add support for SVGs for product icons | 0 | backlog-candidate | 0 | — |
| 337 | [#304880](https://github.com/microsoft/vscode/issues/304880) | Individual project theming | 0 | active | 0 | — |
| 346 | [#319847](https://github.com/microsoft/vscode/issues/319847) | Feature request: Panel-specific themes in VS Code / Copilot | 0 | backlog-candidate | 0 | — |
| 350 | [#323840](https://github.com/microsoft/vscode/issues/323840) | Expose themeVariables of the built-in mermaid-markdown-features extension in user settings | 0 | active | 0 | — |

### Editor folding (56)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 4 | [#3352](https://github.com/microsoft/vscode/issues/3352) | [folding] Collapse ending brace to the same line | 308 | backlog-candidate | 22 | — |
| 16 | [#128912](https://github.com/microsoft/vscode/issues/128912) | [folding] Allow to fold all method bodies | 81 | backlog-candidate | 7 | — |
| 21 | [#40338](https://github.com/microsoft/vscode/issues/40338) | [folding] configure initial collapse state | 85 | backlog-candidate | 6 | — |
| 22 | [#130250](https://github.com/microsoft/vscode/issues/130250) | [folding] Show number of lines folded | 64 | backlog-candidate | 6 | — |
| 26 | [#63972](https://github.com/microsoft/vscode/issues/63972) | [folding] Move line up/down should skip over folded regions or folded sections | 70 | backlog-candidate | 5 | — |
| 32 | [#33449](https://github.com/microsoft/vscode/issues/33449) | [folding] Automatic function/method folding | 57 | backlog-candidate | 4 | — |
| 33 | [#16082](https://github.com/microsoft/vscode/issues/16082) | [folding] retain folded state on copy/paste | 53 | backlog-candidate | 4 | — |
| 34 | [#36002](https://github.com/microsoft/vscode/issues/36002) | [folding] allow defining folding regions in user settings and/or extensions | 53 | backlog-candidate | 4 | — |
| 36 | [#272740](https://github.com/microsoft/vscode/issues/272740) | [folding] [json] Show number of collapsed array/object items | 25 | backlog-candidate | 4 | — |
| 44 | [#70794](https://github.com/microsoft/vscode/issues/70794) | [folding] custom folding text for folded ranges | 38 | backlog-candidate | 3 | — |
| 46 | [#24515](https://github.com/microsoft/vscode/issues/24515) | [folding] Folding HTML tags should hide the closing tag. | 35 | backlog-candidate | 3 | — |
| 49 | [#208368](https://github.com/microsoft/vscode/issues/208368) | [folding] fold only code | 24 | backlog-candidate | 3 | — |
| 53 | [#134911](https://github.com/microsoft/vscode/issues/134911) | [folding] Add `unfold level [number]` | 29 | backlog-candidate | 2 | — |
| 54 | [#31966](https://github.com/microsoft/vscode/issues/31966) | [folding] show comment first line for folded sections | 28 | backlog-candidate | 2 | — |
| 55 | [#60670](https://github.com/microsoft/vscode/issues/60670) | [folding] show folding actions at the end of folding range as well | 28 | backlog-candidate | 2 | — |
| 65 | [#58658](https://github.com/microsoft/vscode/issues/58658) | [folding] go to region command | 18 | backlog-candidate | 2 | — |
| 69 | [#19690](https://github.com/microsoft/vscode/issues/19690) | [folding] show folding lines | 17 | backlog-candidate | 1 | — |
| 78 | [#59657](https://github.com/microsoft/vscode/issues/59657) | [folding] clicking on on line number of folded line should select full folding range | 13 | backlog-candidate | 1 | — |
| 79 | [#64721](https://github.com/microsoft/vscode/issues/64721) | [folding] Preview folded content on hover | 13 | backlog-candidate | 1 | — |
| 80 | [#85783](https://github.com/microsoft/vscode/issues/85783) | [folding] add command unfold block comments | 13 | backlog-candidate | 1 | — |
| 82 | [#75819](https://github.com/microsoft/vscode/issues/75819) | [folding] Fold current level | 9 | backlog-candidate | 1 | — |
| 83 | [#91600](https://github.com/microsoft/vscode/issues/91600) | [folding] pressing Enter in collapsed region should add new line outside region | 9 | backlog-candidate | 1 | — |
| 85 | [#29155](https://github.com/microsoft/vscode/issues/29155) | [folding] Allow to show amount of lines folded | 8 | backlog-candidate | 1 | — |
| 86 | [#54631](https://github.com/microsoft/vscode/issues/54631) | [folding] Add keyboard shortcut to jump between #region and #endregion | 7 | backlog-candidate | 1 | — |
| 87 | [#78004](https://github.com/microsoft/vscode/issues/78004) | [folding] When you cut a collapsed code block it should stays collapsed when you paste/drop it. | 7 | backlog-candidate | 1 | — |
| 89 | [#72422](https://github.com/microsoft/vscode/issues/72422) | [folding] selecting first line of folded range does not select full folded range | 6 | backlog-candidate | 1 | — |
| 118 | [#48556](https://github.com/microsoft/vscode/issues/48556) | [folding] fold all but comments | 6 | backlog-candidate | 0 | — |
| 124 | [#83458](https://github.com/microsoft/vscode/issues/83458) | [folding] Improve #region support: make it look like Visual Studio IDE | 4 | backlog-candidate | 0 | — |
| 128 | [#190879](https://github.com/microsoft/vscode/issues/190879) | [folding] Folding is clickable on the whole foldable region in the gutter | 4 | backlog-candidate | 0 | — |
| 131 | [#38149](https://github.com/microsoft/vscode/issues/38149) | [folding] Hover can show region description on `#endregion` | 3 | backlog-candidate | 0 | — |
| 133 | [#55252](https://github.com/microsoft/vscode/issues/55252) | [folding] provide non-selection aware fold level command | 3 | backlog-candidate | 0 | — |
| 136 | [#91293](https://github.com/microsoft/vscode/issues/91293) | [folding] context menu on expand/collapse arrow | 3 | backlog-candidate | 0 | — |
| 140 | [#43840](https://github.com/microsoft/vscode/issues/43840) | [folding] Code folding does not respect multi-cursor | 2 | backlog-candidate | 0 | — |
| 142 | [#71712](https://github.com/microsoft/vscode/issues/71712) | [folding] Distinctly highlight corresponding `#endregion` for `#region X` comments | 2 | backlog-candidate | 0 | — |
| 162 | [#67340](https://github.com/microsoft/vscode/issues/67340) | [folding] Show tooltip on hovering collapse markers | 1 | backlog-candidate | 0 | — |
| 165 | [#72684](https://github.com/microsoft/vscode/issues/72684) | [folding] Option to show both fold/unfold controls on mouseover only | 1 | backlog-candidate | 0 | — |
| 166 | [#74360](https://github.com/microsoft/vscode/issues/74360) | [folding] Fold All in selection | 1 | backlog-candidate | 0 | — |
| 167 | [#77861](https://github.com/microsoft/vscode/issues/77861) | [folding] Preserve folded ranges on revert | 1 | backlog-candidate | 0 | — |
| 168 | [#83250](https://github.com/microsoft/vscode/issues/83250) | [folding] Auto re-fold a region after the cursor leaves it. | 1 | backlog-candidate | 0 | — |
| 177 | [#174959](https://github.com/microsoft/vscode/issues/174959) | [folding] Allow us to know if a region is folded or not | 1 | backlog-candidate | 0 | — |
| 180 | [#204200](https://github.com/microsoft/vscode/issues/204200) | [folding] Add Code Folding Actions to the Undo Stack | 1 | backlog-candidate | 0 | — |
| 184 | [#265661](https://github.com/microsoft/vscode/issues/265661) | Support for FoldingRangeProviders that don't disable indentation based folding | 1 | backlog-candidate | 0 | — |
| 194 | [#313192](https://github.com/microsoft/vscode/issues/313192) | Folding Strategy: Brackets | 1 | active | 0 | — |
| 200 | [#42287](https://github.com/microsoft/vscode/issues/42287) | [folding] Allow folding block comment that starts in the middle of the line | 0 | backlog-candidate | 0 | — |
| 202 | [#46708](https://github.com/microsoft/vscode/issues/46708) | [folding] blocked while language server is starting up | 0 | backlog-candidate | 0 | — |
| 205 | [#52103](https://github.com/microsoft/vscode/issues/52103) | [folding] unfold when pressing enter on last line | 0 | backlog-candidate | 0 | — |
| 222 | [#88627](https://github.com/microsoft/vscode/issues/88627) | [folding] seperate color for line numbers at collapsed row | 0 | backlog-candidate | 0 | — |
| 225 | [#95156](https://github.com/microsoft/vscode/issues/95156) | [folding] mode to have region based folding only | 0 | backlog-candidate | 0 | — |
| 228 | [#103445](https://github.com/microsoft/vscode/issues/103445) | [python] Add #region and #endregion to python autocomplete | 0 | backlog-candidate | 0 | — |
| 238 | [#119625](https://github.com/microsoft/vscode/issues/119625) | [folding] Hover over the folding indicator to mention Alt and Shift | 0 | backlog-candidate | 0 | — |
| 242 | [#123979](https://github.com/microsoft/vscode/issues/123979) | [folding]  highlight folding range when hovering over the collapse button | 0 | backlog-candidate | 0 | — |
| 257 | [#147526](https://github.com/microsoft/vscode/issues/147526) | [folding] Increase number of foldable regions | 0 | backlog-candidate | 0 | — |
| 280 | [#251674](https://github.com/microsoft/vscode/issues/251674) | Support folding in instruction file | 0 | backlog-candidate | 0 | — |
| 309 | [#269857](https://github.com/microsoft/vscode/issues/269857) | [folding] Do not collapse imports when navigating to an error in the imports section | 0 | backlog-candidate | 0 | — |
| 353 | [#327466](https://github.com/microsoft/vscode/issues/327466) | Feature Request: Allow folding single physical lines that are soft-wrapped via wordWrap | 0 | active | 0 | — |
| 355 | [#328395](https://github.com/microsoft/vscode/issues/328395) | copy selected text but Ignore the folding part | 0 | active | 0 | — |

### Web language tooling (71)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 9 | [#26338](https://github.com/microsoft/vscode/issues/26338) | [html] Javascript intellisense in inline scripts from external references | 126 | backlog-candidate | 12 | — |
| 11 | [#28459](https://github.com/microsoft/vscode/issues/28459) | [css] Use CSS custom properties imported via @import | 155 | backlog-candidate | 11 | — |
| 13 | [#165207](https://github.com/microsoft/vscode/issues/165207) | [css] Add new CSS color functions | 115 | backlog-candidate | 11 | — |
| 17 | [#47331](https://github.com/microsoft/vscode/issues/47331) | [html][css] Investigate cross css/html, multi file support | 72 | backlog-candidate | 7 | — |
| 28 | [#163967](https://github.com/microsoft/vscode/issues/163967) | [css] Custom aliases in CSS file resolution | 47 | backlog-candidate | 5 | — |
| 40 | [#25898](https://github.com/microsoft/vscode/issues/25898) | [html] provide translations of tag documentation | 48 | backlog-candidate | 3 | — |
| 43 | [#66053](https://github.com/microsoft/vscode/issues/66053) | [css][html] SVG language support | 44 | backlog-candidate | 3 | — |
| 45 | [#58315](https://github.com/microsoft/vscode/issues/58315) | [html] Automatically delete HTML closing tag when converting to self-closing tag | 36 | backlog-candidate | 3 | — |
| 60 | [#85828](https://github.com/microsoft/vscode/issues/85828) | [css] Support for SVG 2 CSS Properties | 23 | backlog-candidate | 2 | — |
| 62 | [#166944](https://github.com/microsoft/vscode/issues/166944) | [css] Please add an option to switch to using line-by-line comments | 22 | backlog-candidate | 2 | — |
| 63 | [#36280](https://github.com/microsoft/vscode/issues/36280) | [html] JSON edit support inside HTML document / script tag with type="application/json" | 20 | backlog-candidate | 2 | — |
| 66 | [#114115](https://github.com/microsoft/vscode/issues/114115) | [html] support imports in embedded JavaScript | 15 | backlog-candidate | 2 | — |
| 74 | [#31141](https://github.com/microsoft/vscode/issues/31141) | [html] provide rename for embedded JavaScript | 14 | backlog-candidate | 1 | — |
| 81 | [#140698](https://github.com/microsoft/vscode/issues/140698) | [html] Improve `html.autoCreateQuotes` to handle manually typed quotes | 10 | backlog-candidate | 1 | — |
| 84 | [#162030](https://github.com/microsoft/vscode/issues/162030) | [css] CSS custom property completions | 9 | backlog-candidate | 1 | — |
| 92 | [#164744](https://github.com/microsoft/vscode/issues/164744) | [scss] Sass modules intellisense when using @use at-rules. | 5 | backlog-candidate | 1 | — |
| 104 | [#214871](https://github.com/microsoft/vscode/issues/214871) | [css] look for variables in all open documents | 3 | backlog-candidate | 1 | — |
| 107 | [#325315](https://github.com/microsoft/vscode/issues/325315) | CSS IntelliSense: Allow completion matching on CSS values as well as property names | 3 | backlog-candidate | 1 | — |
| 119 | [#60489](https://github.com/microsoft/vscode/issues/60489) | [html] proper support of XHTML | 6 | backlog-candidate | 0 | — |
| 121 | [#62333](https://github.com/microsoft/vscode/issues/62333) | [css] Add @media and @supports to CSS breadcrumbs | 4 | backlog-candidate | 0 | — |
| 126 | [#131494](https://github.com/microsoft/vscode/issues/131494) | [scss] Hover hint doesn't support SCSS Interpolation syntax | 4 | backlog-candidate | 0 | — |
| 135 | [#77011](https://github.com/microsoft/vscode/issues/77011) | [css] Shorthand properties: show label for each value in hover | 3 | backlog-candidate | 0 | — |
| 139 | [#43365](https://github.com/microsoft/vscode/issues/43365) | [css] propose ids used in other selectors | 2 | dormant | 0 | — |
| 141 | [#57469](https://github.com/microsoft/vscode/issues/57469) | [html] Support SCSS in HTML with <style type="text/scss"> | 2 | backlog-candidate | 0 | — |
| 144 | [#86763](https://github.com/microsoft/vscode/issues/86763) | [scss] add parameter hints | 2 | backlog-candidate | 0 | — |
| 145 | [#89850](https://github.com/microsoft/vscode/issues/89850) | [html] HTML breadcrumbs don't work right when optional end tags omitted | 2 | backlog-candidate | 0 | — |
| 149 | [#181935](https://github.com/microsoft/vscode/issues/181935) | [html] Allow renaming images using F2 | 2 | backlog-candidate | 0 | — |
| 158 | [#12787](https://github.com/microsoft/vscode/issues/12787) | [html] closing </script> tag is not proposed | 1 | backlog-candidate | 0 | — |
| 159 | [#44612](https://github.com/microsoft/vscode/issues/44612) | [razor] comment out razor code with @* *@ | 1 | backlog-candidate | 0 | — |
| 160 | [#54638](https://github.com/microsoft/vscode/issues/54638) | [scss] Add "Go to or peek defintion" for imported mixins and variables for SCSS files | 1 | backlog-candidate | 0 | — |
| 161 | [#66148](https://github.com/microsoft/vscode/issues/66148) | [html] code complete for href anchors | 1 | backlog-candidate | 0 | — |
| 169 | [#86765](https://github.com/microsoft/vscode/issues/86765) | [scss] provide hover for scss functions | 1 | backlog-candidate | 0 | — |
| 170 | [#111133](https://github.com/microsoft/vscode/issues/111133) | [css] Support for CSS3 speech properties voice-family, voice-pitch, voice-range and voice-stress | 1 | backlog-candidate | 0 | — |
| 176 | [#128716](https://github.com/microsoft/vscode/issues/128716) | [html] propose `charset="UTF-8"` `target="_blank"` and `rel="stylesheet"` | 1 | backlog-candidate | 0 | — |
| 179 | [#202417](https://github.com/microsoft/vscode/issues/202417) | [css] Outline doesn't show @layer | 1 | backlog-candidate | 0 | — |
| 196 | [#6829](https://github.com/microsoft/vscode/issues/6829) | [css] show all variable definitions for Go To definition | 0 | backlog-candidate | 0 | — |
| 197 | [#7757](https://github.com/microsoft/vscode/issues/7757) | [css] Support <angle> units icon in CSS | 0 | backlog-candidate | 0 | — |
| 201 | [#43111](https://github.com/microsoft/vscode/issues/43111) | [css] Lab colors and other CSS Color Module Level 4 features | 0 | dormant | 0 | — |
| 203 | [#47192](https://github.com/microsoft/vscode/issues/47192) | [html] propose html 4 properties (cellPadding ...) | 0 | backlog-candidate | 0 | — |
| 208 | [#59445](https://github.com/microsoft/vscode/issues/59445) | [html] support less syntax in html file | 0 | backlog-candidate | 0 | — |
| 209 | [#62569](https://github.com/microsoft/vscode/issues/62569) | [scss] rename not working for placeholder selectors | 0 | backlog-candidate | 0 | — |
| 210 | [#66703](https://github.com/microsoft/vscode/issues/66703) | [css] support IE10 repeat syntax | 0 | backlog-candidate | 0 | — |
| 211 | [#68548](https://github.com/microsoft/vscode/issues/68548) | [html] [custom data] allow to give custom HTML tags/attributes a higher completion rank | 0 | backlog-candidate | 0 | — |
| 212 | [#77582](https://github.com/microsoft/vscode/issues/77582) | [css][html] Publish language servers modules on npm | 0 | backlog-candidate | 0 | — |
| 213 | [#79141](https://github.com/microsoft/vscode/issues/79141) | [css] Add support for CSS @supports selector() function | 0 | backlog-candidate | 0 | — |
| 214 | [#79439](https://github.com/microsoft/vscode/issues/79439) | [css] code completion for gradient functions | 0 | backlog-candidate | 0 | — |
| 215 | [#81352](https://github.com/microsoft/vscode/issues/81352) | [html] Jump to after next opening HTML tag | 0 | backlog-candidate | 0 | — |
| 216 | [#83835](https://github.com/microsoft/vscode/issues/83835) | [css] support css-variable completion in calc | 0 | backlog-candidate | 0 | — |
| 218 | [#86187](https://github.com/microsoft/vscode/issues/86187) | [scss] provide hover information for at-rules | 0 | dormant | 0 | — |
| 220 | [#86488](https://github.com/microsoft/vscode/issues/86488) | [scss] references for all SASS functions/at-rules | 0 | backlog-candidate | 0 | — |
| 221 | [#86764](https://github.com/microsoft/vscode/issues/86764) | [css] hover for property values | 0 | backlog-candidate | 0 | — |
| 226 | [#96834](https://github.com/microsoft/vscode/issues/96834) | [html] No values suggested for `autocapitalize` | 0 | backlog-candidate | 0 | — |
| 227 | [#97949](https://github.com/microsoft/vscode/issues/97949) | [html] don't let '/' trigger a suggest in embedded JavaScript | 0 | backlog-candidate | 0 | — |
| 229 | [#105298](https://github.com/microsoft/vscode/issues/105298) | [html] Add value proposals for rel attribute | 0 | backlog-candidate | 0 | — |
| 233 | [#111016](https://github.com/microsoft/vscode/issues/111016) | [html] move mdn link to the right | 0 | backlog-candidate | 0 | — |
| 239 | [#120040](https://github.com/microsoft/vscode/issues/120040) | [html] suggestions for media | 0 | backlog-candidate | 0 | — |
| 246 | [#126733](https://github.com/microsoft/vscode/issues/126733) | [css] Color picker for css variables | 0 | backlog-candidate | 0 | — |
| 250 | [#142402](https://github.com/microsoft/vscode/issues/142402) | Tags for properties contribution is missing from completion | 0 | backlog-candidate | 0 | — |
| 251 | [#142946](https://github.com/microsoft/vscode/issues/142946) | [css] Allow extensions to choose to use whether to use CSS default data provider | 0 | backlog-candidate | 0 | — |
| 252 | [#144730](https://github.com/microsoft/vscode/issues/144730) | [html] allow to turn off closing tags when not needed | 0 | backlog-candidate | 0 | — |
| 254 | [#145702](https://github.com/microsoft/vscode/issues/145702) | [css] Support format on type | 0 | backlog-candidate | 0 | — |
| 255 | [#145883](https://github.com/microsoft/vscode/issues/145883) | [html] don't show closing element proposal as first entry if element is already closed later | 0 | backlog-candidate | 0 | — |
| 256 | [#147483](https://github.com/microsoft/vscode/issues/147483) | [css] Enable drop image into css to insert url | 0 | backlog-candidate | 0 | — |
| 258 | [#151319](https://github.com/microsoft/vscode/issues/151319) | [html] `html.autoCreateQuotes` is not instant | 0 | backlog-candidate | 0 | — |
| 260 | [#163742](https://github.com/microsoft/vscode/issues/163742) | [html] Ignore html tag in sticky scroll and outline | 0 | backlog-candidate | 0 | — |
| 262 | [#175807](https://github.com/microsoft/vscode/issues/175807) | [html] Path completion isn’t working with the `srcset` attribute | 0 | backlog-candidate | 0 | — |
| 264 | [#185999](https://github.com/microsoft/vscode/issues/185999) | [css] add clamp() math function | 0 | backlog-candidate | 0 | — |
| 266 | [#189875](https://github.com/microsoft/vscode/issues/189875) | Workspace files dropped and pasted into CSS file should be automatically formatted | 0 | dormant | 0 | — |
| 270 | [#224977](https://github.com/microsoft/vscode/issues/224977) | [css] allow to overtype the semicolon | 0 | backlog-candidate | 0 | — |
| 275 | [#242999](https://github.com/microsoft/vscode/issues/242999) | [html] Filter <link> path suggestion by file type | 0 | backlog-candidate | 0 | — |
| 277 | [#249690](https://github.com/microsoft/vscode/issues/249690) | [html] Rename Symbol doesn't work on attribute names | 0 | backlog-candidate | 0 | — |

### Custom agents (36)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 10 | [#251251](https://github.com/microsoft/vscode/issues/251251) | Feature Request: Add Temperature for Custom Agent Profiles | 84 | backlog-candidate | 12 | — |
| 23 | [#295755](https://github.com/microsoft/vscode/issues/295755) | Feature Request: Support Branch Selection for Organization‑Level Copilot Agents | 40 | backlog-candidate | 6 | — |
| 39 | [#313546](https://github.com/microsoft/vscode/issues/313546) | Support reasoning effort configuration in custom .agent.md files | 14 | active | 4 | — |
| 51 | [#263279](https://github.com/microsoft/vscode/issues/263279) | Agent Mode: Disable tools by default besides core tools | 14 | backlog-candidate | 3 | — |
| 95 | [#309043](https://github.com/microsoft/vscode/issues/309043) | Agents: Add model_reasoning_effort to custom agents and prompts. | 5 | active | 1 | — |
| 100 | [#275981](https://github.com/microsoft/vscode/issues/275981) | [Feedback] [Plan Mode] Confusing UX for "Open in Editor" option and .prompt.md file extension | 4 | backlog-candidate | 1 | — |
| 102 | [#281116](https://github.com/microsoft/vscode/issues/281116) | Feature Request: Allow handsoff with resetting context window for custom agent | 4 | backlog-candidate | 1 | — |
| 109 | [#287947](https://github.com/microsoft/vscode/issues/287947) | Implement built-in agents from Copilot CLI to Copilot Chat | 2 | backlog-candidate | 1 | — |
| 111 | [#279185](https://github.com/microsoft/vscode/issues/279185) | Save as Custom Agent from Tools Window | 1 | backlog-candidate | 1 | — |
| 112 | [#286358](https://github.com/microsoft/vscode/issues/286358) | Enhanced Support for Agent-Associated Files in VS Code Copilot Chat | 1 | backlog-candidate | 1 | — |
| 113 | [#255124](https://github.com/microsoft/vscode/issues/255124) | Panel chat gear dropdown should have hints on hover | 0 | backlog-candidate | 1 | — |
| 114 | [#272732](https://github.com/microsoft/vscode/issues/272732) | agent files: support variables | 0 | dormant | 1 | — |
| 115 | [#277547](https://github.com/microsoft/vscode/issues/277547) | Add icons to Agents | 0 | backlog-candidate | 1 | — |
| 117 | [#311920](https://github.com/microsoft/vscode/issues/311920) | Agent profiles and namespacing for Copilot custom agents | 0 | active | 1 | — |
| 186 | [#275082](https://github.com/microsoft/vscode/issues/275082) | Agent Handoffs: Improve editing experience | 1 | dormant | 0 | — |
| 187 | [#277432](https://github.com/microsoft/vscode/issues/277432) | plan agent: Improve open editor handoff | 1 | backlog-candidate | 0 | — |
| 190 | [#281791](https://github.com/microsoft/vscode/issues/281791) | GitHub Copilot agents should remember models on a per-agent basis. | 1 | backlog-candidate | 0 | — |
| 192 | [#298928](https://github.com/microsoft/vscode/issues/298928) | Copilot Fix ignores extension-provided code.target and code actions, generating incorrect fixes | 1 | active | 0 | — |
| 283 | [#252552](https://github.com/microsoft/vscode/issues/252552) | Support human facing comments in custom chat mode files | 0 | backlog-candidate | 0 | — |
| 291 | [#256007](https://github.com/microsoft/vscode/issues/256007) | Chat - Apply in Editor feedback | 0 | backlog-candidate | 0 | — |
| 292 | [#256486](https://github.com/microsoft/vscode/issues/256486) | Add a `contexts` field to the .md metadata for a custom chat mode | 0 | dormant | 0 | — |
| 299 | [#261697](https://github.com/microsoft/vscode/issues/261697) | Feature Request: Customizable continuous actions per chat mode file | 0 | backlog-candidate | 0 | — |
| 313 | [#275053](https://github.com/microsoft/vscode/issues/275053) | Agent file editing - missing potential fix | 0 | backlog-candidate | 0 | — |
| 314 | [#275888](https://github.com/microsoft/vscode/issues/275888) | Let me hide Ask & Edit modes | 0 | dormant | 0 | — |
| 318 | [#277735](https://github.com/microsoft/vscode/issues/277735) | Agent: Prompts should not persist tool/model selection after chat response | 0 | active | 0 | — |
| 323 | [#280684](https://github.com/microsoft/vscode/issues/280684) | Selecting tools for custom agent always opens the md file | 0 | dormant | 0 | — |
| 331 | [#294640](https://github.com/microsoft/vscode/issues/294640) | Feature Request: Add Optional "response_structure" Field to .agent.md Files (Custom Agents) | 0 | active | 0 | — |
| 334 | [#300411](https://github.com/microsoft/vscode/issues/300411) | runSubagent - more parameters, e.g. for model and tools | 0 | active | 0 | — |
| 338 | [#306717](https://github.com/microsoft/vscode/issues/306717) | Chat: add 'tiers' frontmatter and 'tier' parameter to runSubagent for semantic model tier routing | 0 | active | 0 | — |
| 341 | [#312528](https://github.com/microsoft/vscode/issues/312528) | Create Copilot Chat settings for setting a global Custom Agent as default Agent | 0 | active | 0 | — |
| 342 | [#314388](https://github.com/microsoft/vscode/issues/314388) | Runtime errors when prompt/agent references model or agent that doesn't exist | 0 | active | 0 | — |
| 343 | [#315593](https://github.com/microsoft/vscode/issues/315593) | Allow to change models for Custom agents inside Agent Plugin | 0 | active | 0 | — |
| 348 | [#320641](https://github.com/microsoft/vscode/issues/320641) | Copilot Agent Host: SDK Driven Agents/Skills/etc | 0 | active | 0 | — |
| 351 | [#325177](https://github.com/microsoft/vscode/issues/325177) | Agent Mode md file is not visible similar to Ask and Plan modes | 0 | active | 0 | — |
| 352 | [#325318](https://github.com/microsoft/vscode/issues/325318) | Profiles: Specify default profile per-machine | 0 | active | 0 | — |
| 354 | [#328089](https://github.com/microsoft/vscode/issues/328089) | Copilot chat feedback | 0 | active | 0 | — |

### Tools and skills (28)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 20 | [#251515](https://github.com/microsoft/vscode/issues/251515) | Support Storing Toolset Files Directly Within the Workspace | 44 | backlog-candidate | 7 | — |
| 31 | [#301181](https://github.com/microsoft/vscode/issues/301181) | Distribute Skills and Instructions from Organization Repositories | 20 | active | 5 | — |
| 93 | [#288502](https://github.com/microsoft/vscode/issues/288502) | Skills should support tools references and enforce them in system prompt | 5 | dormant | 1 | — |
| 98 | [#251747](https://github.com/microsoft/vscode/issues/251747) | Enable Auto-Attach for MCP Prompts / Embedded Resources | 4 | active | 1 | — |
| 101 | [#277433](https://github.com/microsoft/vscode/issues/277433) | add a code execution tool | 4 | backlog-candidate | 1 | — |
| 116 | [#304721](https://github.com/microsoft/vscode/issues/304721) | Support contributing agent skill folders with supporting files from extensions | 0 | active | 1 | — |
| 129 | [#251603](https://github.com/microsoft/vscode/issues/251603) | Issue: GitHub Copilot toolsets.jsonc file not syncing across devices | 4 | backlog-candidate | 0 | — |
| 154 | [#296829](https://github.com/microsoft/vscode/issues/296829) | Per-agent auto-approve for terminal commands in custom agents (.agent.md) | 2 | active | 0 | — |
| 155 | [#298713](https://github.com/microsoft/vscode/issues/298713) | Support loading agent skills from packages | 2 | active | 0 | — |
| 183 | [#259183](https://github.com/microsoft/vscode/issues/259183) | Enable workspace-scoped tool sets | 1 | backlog-candidate | 0 | — |
| 193 | [#312279](https://github.com/microsoft/vscode/issues/312279) | Let me / multiple skills in one message | 1 | backlog-candidate | 0 | — |
| 278 | [#250421](https://github.com/microsoft/vscode/issues/250421) | Reconsider `languageModelToolSets` validation Notifications | 0 | backlog-candidate | 0 | — |
| 295 | [#259972](https://github.com/microsoft/vscode/issues/259972) | Show Built-in Tools at the bottom, collapsed or in a seperate tab | 0 | backlog-candidate | 0 | — |
| 296 | [#259973](https://github.com/microsoft/vscode/issues/259973) | Allow MCP Servers in non-agent mode | 0 | dormant | 0 | — |
| 297 | [#260214](https://github.com/microsoft/vscode/issues/260214) | Agent: Expose tool to run prompts controlled by the agent | 0 | backlog-candidate | 0 | — |
| 305 | [#269134](https://github.com/microsoft/vscode/issues/269134) | Tool references in prompts: support `extensionId/*` | 0 | backlog-candidate | 0 | — |
| 308 | [#269828](https://github.com/microsoft/vscode/issues/269828) | Render counts next to collapsed toolsets | 0 | backlog-candidate | 0 | — |
| 311 | [#273813](https://github.com/microsoft/vscode/issues/273813) | Running a prompt without having the tools installed should show a warning in chat | 0 | backlog-candidate | 0 | — |
| 316 | [#276105](https://github.com/microsoft/vscode/issues/276105) | Lots of tools I didn't choose in my tool set | 0 | backlog-candidate | 0 | — |
| 324 | [#282241](https://github.com/microsoft/vscode/issues/282241) | Use the `#tool:fullReferenceName` syntax in the chat input | 0 | active | 0 | — |
| 327 | [#284627](https://github.com/microsoft/vscode/issues/284627) | Allow agent skill scripts to retrieve the workspace root/workspace file | 0 | active | 0 | — |
| 329 | [#290272](https://github.com/microsoft/vscode/issues/290272) | Skill changes in skill.md don’t apply until VS Code restart or new chat session | 0 | dormant | 0 | — |
| 333 | [#297651](https://github.com/microsoft/vscode/issues/297651) | [FEATURE REQUEST]: Include Copilot Chat Tools in Settings Sync | 0 | active | 0 | — |
| 335 | [#301490](https://github.com/microsoft/vscode/issues/301490) | Plugin-installed skill resource files not accessible to search tools (grep_search, file_search, semantic_search) | 0 | backlog-candidate | 0 | — |
| 336 | [#303777](https://github.com/microsoft/vscode/issues/303777) | Support skill-scoped hooks (on-load) in SKILL.md | 0 | active | 0 | — |
| 339 | [#311874](https://github.com/microsoft/vscode/issues/311874) | Inline Skill Picker with Fuzzy Search while typing in Chat | 0 | active | 0 | — |
| 340 | [#312179](https://github.com/microsoft/vscode/issues/312179) | Allow folders with skills shipped via extensions to be read without user confirmations | 0 | active | 0 | — |
| 345 | [#319321](https://github.com/microsoft/vscode/issues/319321) | Feature Request: Presaved MCP Toolsets / Named Presets for Context-Aware Tool Activation | 0 | active | 0 | — |

### Prompts and instructions (39)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 30 | [#270160](https://github.com/microsoft/vscode/issues/270160) | Add support for full-match patterns relative to workspace root for Copilot Instructions `applyTo` pattern | 26 | backlog-candidate | 5 | — |
| 38 | [#288838](https://github.com/microsoft/vscode/issues/288838) | [Feature Request] Add frontmatter option to open .prompt.md files in a new chat session | 23 | backlog-candidate | 4 | — |
| 90 | [#262876](https://github.com/microsoft/vscode/issues/262876) | [prompts] One-Click install of Copilot Instructions / Prompts from private Github repos | 6 | backlog-candidate | 1 | — |
| 94 | [#291685](https://github.com/microsoft/vscode/issues/291685) | Make sharing of copilot instructions, skills etc globally easy for organizations | 5 | active | 1 | — |
| 99 | [#255196](https://github.com/microsoft/vscode/issues/255196) | Copilot instructions in multi-root should apply per folder | 4 | backlog-candidate | 1 | — |
| 105 | [#291311](https://github.com/microsoft/vscode/issues/291311) | Agent mode does not reference instruction files after reading a file outside its initial context. | 3 | active | 1 | — |
| 106 | [#307369](https://github.com/microsoft/vscode/issues/307369) | chat.agentFilesLocations and chat.agentSkillsLocations should support glob/wildcard patterns | 3 | active | 1 | — |
| 137 | [#284849](https://github.com/microsoft/vscode/issues/284849) | Support for Custom Attributes in `.prompt.md` YAML Front Matter | 3 | backlog-candidate | 0 | — |
| 152 | [#278850](https://github.com/microsoft/vscode/issues/278850) | Prompts and instructions aren't syncing if non-default profile is used | 2 | backlog-candidate | 0 | — |
| 153 | [#280091](https://github.com/microsoft/vscode/issues/280091) | Support for `${userHome}` variable in `chat.promptFilesLocations` setting | 2 | backlog-candidate | 0 | — |
| 185 | [#267596](https://github.com/microsoft/vscode/issues/267596) | Feature: Toggle custom Copilot instructions per chat session | 1 | backlog-candidate | 0 | — |
| 191 | [#297210](https://github.com/microsoft/vscode/issues/297210) | Prompt files should allow me to select latest model with wildcard | 1 | backlog-candidate | 0 | — |
| 282 | [#252530](https://github.com/microsoft/vscode/issues/252530) | Make `security.promptForPromptProtocolHandling` a real setting and an allow list | 0 | backlog-candidate | 0 | — |
| 285 | [#253048](https://github.com/microsoft/vscode/issues/253048) | Copilot Coding Agent doesn't create copilot-instructions.md without help | 0 | backlog-candidate | 0 | — |
| 286 | [#253201](https://github.com/microsoft/vscode/issues/253201) | Support comments in header section | 0 | backlog-candidate | 0 | — |
| 287 | [#253498](https://github.com/microsoft/vscode/issues/253498) | Using the same link again should do file validation before I accept it | 0 | backlog-candidate | 0 | — |
| 288 | [#253515](https://github.com/microsoft/vscode/issues/253515) | Support `content` instead of `url` for vscode:chat-* links | 0 | backlog-candidate | 0 | — |
| 289 | [#253517](https://github.com/microsoft/vscode/issues/253517) | More options when opening vscode:chat-prompt links in VS Code | 0 | backlog-candidate | 0 | — |
| 293 | [#257285](https://github.com/microsoft/vscode/issues/257285) | Users need to be guided to make a proper instruction file | 0 | dormant | 0 | — |
| 294 | [#258425](https://github.com/microsoft/vscode/issues/258425) | A better way to manage prompts/instructions/agents with the same name. | 0 | backlog-candidate | 0 | — |
| 298 | [#260672](https://github.com/microsoft/vscode/issues/260672) | Instructions: Allow filtering instructions to specific modes | 0 | dormant | 0 | — |
| 302 | [#266750](https://github.com/microsoft/vscode/issues/266750) | "inherit" instructions in profiles | 0 | backlog-candidate | 0 | — |
| 303 | [#267086](https://github.com/microsoft/vscode/issues/267086) | Support cursor rules | 0 | backlog-candidate | 0 | — |
| 304 | [#268330](https://github.com/microsoft/vscode/issues/268330) | Add ability to create Chatmode/Prompt from current chat | 0 | backlog-candidate | 0 | — |
| 307 | [#269564](https://github.com/microsoft/vscode/issues/269564) | Allow to import prompt/instruction/modes file via `vscode` link for files that need authentication | 0 | backlog-candidate | 0 | — |
| 310 | [#273615](https://github.com/microsoft/vscode/issues/273615) | Enable Ctrl+Click on slash commands in chat input to open prompt file | 0 | backlog-candidate | 0 | — |
| 312 | [#273815](https://github.com/microsoft/vscode/issues/273815) | Allow prompts to run in without any instruction files | 0 | backlog-candidate | 0 | — |
| 315 | [#275979](https://github.com/microsoft/vscode/issues/275979) | Prompt file type detection should be case-insensitive | 0 | dormant | 0 | — |
| 317 | [#276633](https://github.com/microsoft/vscode/issues/276633) | Clarify order of custom agent, workspace instructions, and user instructions in context | 0 | backlog-candidate | 0 | — |
| 319 | [#278111](https://github.com/microsoft/vscode/issues/278111) | [prompts] add a command to improve a prompt | 0 | backlog-candidate | 0 | — |
| 320 | [#279184](https://github.com/microsoft/vscode/issues/279184) | Provide the ability to disable extension specific instructions in agent mode | 0 | backlog-candidate | 0 | — |
| 321 | [#279367](https://github.com/microsoft/vscode/issues/279367) | Support substitution variables in prompt files | 0 | backlog-candidate | 0 | — |
| 322 | [#280624](https://github.com/microsoft/vscode/issues/280624) | [prompts] fill in default content for new files created with `New File` | 0 | backlog-candidate | 0 | — |
| 325 | [#283149](https://github.com/microsoft/vscode/issues/283149) | Unable to specify line numbers when providing file context in prompt files | 0 | backlog-candidate | 0 | — |
| 328 | [#288703](https://github.com/microsoft/vscode/issues/288703) | Support regex matching in custom copilot instruction injection | 0 | backlog-candidate | 0 | — |
| 330 | [#290374](https://github.com/microsoft/vscode/issues/290374) | Extend Profile Isolation to AI Configuration Files (Copilot Instructions, AGENTS.md, Prompts) | 0 | active | 0 | — |
| 332 | [#295894](https://github.com/microsoft/vscode/issues/295894) | per-model(s) instruction files | 0 | active | 0 | — |
| 347 | [#319981](https://github.com/microsoft/vscode/issues/319981) | there is no slash-br | 0 | backlog-candidate | 0 | — |
| 349 | [#322506](https://github.com/microsoft/vscode/issues/322506) | [Feature Request] Allow configuring Copilot agent/skill/instruction discovery paths via settings | 0 | active | 0 | — |

### Remote development (14)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 42 | [#179152](https://github.com/microsoft/vscode/issues/179152) | Add support for remote development on Windows Sandbox | 45 | backlog-candidate | 3 | — |
| 47 | [#127587](https://github.com/microsoft/vscode/issues/127587) | [remote] Prefer to open a file in an existing window even when that window is connected to a remote with that file opened | 29 | backlog-candidate | 3 | — |
| 96 | [#316209](https://github.com/microsoft/vscode/issues/316209) | No port forwarding for "code serve-web" when accessed from another machine | 5 | active | 1 | — |
| 97 | [#221851](https://github.com/microsoft/vscode/issues/221851) | [wsl] Use curl instead of wget to download VS Code server | 4 | backlog-candidate | 1 | — |
| 178 | [#187027](https://github.com/microsoft/vscode/issues/187027) | [wsl] support undo after deleting directory | 1 | backlog-candidate | 0 | — |
| 182 | [#240063](https://github.com/microsoft/vscode/issues/240063) | Please add HTTPS support for serve-web | 1 | backlog-candidate | 0 | — |
| 188 | [#278102](https://github.com/microsoft/vscode/issues/278102) | [wsl] Pipe to `code -` does not work in WSL | 1 | backlog-candidate | 0 | — |
| 237 | [#117849](https://github.com/microsoft/vscode/issues/117849) | [remote cli] support opening `file` URIs | 0 | backlog-candidate | 0 | — |
| 240 | [#121799](https://github.com/microsoft/vscode/issues/121799) | [remote][connection] Allow offline editing in Remote-WSL | 0 | dormant | 0 | — |
| 263 | [#185775](https://github.com/microsoft/vscode/issues/185775) | [wsl] Automatically give vscode wsl sh scripts +x | 0 | backlog-candidate | 0 | — |
| 265 | [#189692](https://github.com/microsoft/vscode/issues/189692) | [wsl] Option to start new window in WSL from File menu | 0 | backlog-candidate | 0 | — |
| 274 | [#238498](https://github.com/microsoft/vscode/issues/238498) | [wsl] bring back "Reopen Folder in WSL" to the remote menu | 0 | backlog-candidate | 0 | — |
| 290 | [#254361](https://github.com/microsoft/vscode/issues/254361) | [WSL] Add server installation `dnf install wget` for Fedora | 0 | backlog-candidate | 0 | — |
| 300 | [#262129](https://github.com/microsoft/vscode/issues/262129) | "open with code" automatically with wsl vscode server | 0 | backlog-candidate | 0 | — |

### Other (9)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 25 | [#28080](https://github.com/microsoft/vscode/issues/28080) | [decorations] Support hover decorations over the line numbers (i.e. gutter) | 72 | backlog-candidate | 5 | — |
| 35 | [#105487](https://github.com/microsoft/vscode/issues/105487) | [cli] specify command that runs on window open | 44 | backlog-candidate | 4 | — |
| 37 | [#274545](https://github.com/microsoft/vscode/issues/274545) | [npm] package.json dependency autocomplete: autocomplete all versions | 23 | backlog-candidate | 4 | — |
| 189 | [#279302](https://github.com/microsoft/vscode/issues/279302) | [folder] Add empty line automatically | 1 | backlog-candidate | 0 | — |
| 207 | [#56719](https://github.com/microsoft/vscode/issues/56719) | [npm] hover should show relevant latest version | 0 | backlog-candidate | 0 | — |
| 223 | [#91086](https://github.com/microsoft/vscode/issues/91086) | [npm] load description/homepage from referenced node module version | 0 | backlog-candidate | 0 | — |
| 241 | [#123615](https://github.com/microsoft/vscode/issues/123615) | [api][commands] Open new window and a file | 0 | dormant | 0 | — |
| 243 | [#123987](https://github.com/microsoft/vscode/issues/123987) | [html] allow to configure html formatter for other languages | 0 | backlog-candidate | 0 | — |
| 244 | [#124577](https://github.com/microsoft/vscode/issues/124577) | [api] Give access to recently opened workspaces: `vscode.getRecentlyOpened` | 0 | backlog-candidate | 0 | — |
