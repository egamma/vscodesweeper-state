# Top issues by theme — roblourens

Experimental themed view of [the flat ranking](roblourens.md); themes assigned by the review engine. Rank/score are the lane-wide values. Generated 2026-07-18 13:06 UTC.

## Bugs

### Agent control (59)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | [#285141](https://github.com/microsoft/vscode/issues/285141) | Copilot chat always defaults to Agent mode (and doesn't remember the last selected mode) | 28 | correctness | 2/6 Unverified | 100 | — | — |
| 8 | [#285951](https://github.com/microsoft/vscode/issues/285951) | GitHub Copilot frequently stalls at "Working" after editing previous prompt | 1 | freeze | 2/6 Unverified | 35 | — | — |
| 15 | [#283328](https://github.com/microsoft/vscode/issues/283328) | No stop button to interrupt agent | 3 | correctness | 6/6 Confirmed | 24 | — | `npm run implement -- --issue 283328` |
| 21 | [#296890](https://github.com/microsoft/vscode/issues/296890) | Agent mode: sending message mid-response sometimes forks session into two parallel agents, causing conflicting edits and JSONL corruption | 0 | data-loss | 4/6 Traced | 19 | — | `npm run implement -- --issue 296890` |
| 41 | [#299357](https://github.com/microsoft/vscode/issues/299357) | VS Code v1.110 and Copilot Chat v0.38.0 issue - GitHub Copilot Chat is stuck in "Ask" mode | 1 | correctness | 2/6 Unverified | 9 | — | — |
| 46 | [#305121](https://github.com/microsoft/vscode/issues/305121) | Copilot repeatedly gives text responses instead of performing code edits (loops on "reply one" / "proceed") AI says 'implemented' without doing anything | 3 | correctness | 3/6 Plausible | 8 | — | — |
| 67 | [#292165](https://github.com/microsoft/vscode/issues/292165) | Agent incorrectly states that the command was canceled | 0 | correctness | 3/6 Plausible | 6 | — | — |
| 76 | [#323274](https://github.com/microsoft/vscode/issues/323274) | Copilot Chat: switching from Agent to Plan mode mid-conversation auto-injects \"Start implementation\" and begins executing | 1 | correctness | 5/6 Source-confirmed | 5 | — | — |
| 80 | [#281577](https://github.com/microsoft/vscode/issues/281577) | "I fixed the issue" when in Ask mode | 0 | correctness | — | 5 | — | `npm run implement -- --issue 281577` |
| 93 | [#290123](https://github.com/microsoft/vscode/issues/290123) | Agent claims to be running commands, but nothing happens | 0 | correctness | 3/6 Plausible | 4 | — | — |
| 119 | [#316956](https://github.com/microsoft/vscode/issues/316956) | Chat with Claude "files changed" is stuck | 1 | correctness | 2/6 Unverified | 3 | — | — |
| 124 | [#258219](https://github.com/microsoft/vscode/issues/258219) | Toggle chat mode command works when dropdown is disabled | 0 | papercut | 5/6 Source-confirmed | 3 | yes | `npm run implement -- --issue 258219` |
| 158 | [#295543](https://github.com/microsoft/vscode/issues/295543) | Canceling the context of the currently resolved matter in the VS Code Copilot Pro chat | 0 | none | 3/6 Plausible | 2 | — | — |
| 159 | [#299313](https://github.com/microsoft/vscode/issues/299313) | Steering issue / double agent session in the same chat | 0 | correctness | 3/6 Plausible | 2 | — | `npm run implement -- --issue 299313` |
| 161 | [#303468](https://github.com/microsoft/vscode/issues/303468) | Infinite Loop | 0 | none | 3/6 Plausible | 2 | — | — |
| 162 | [#304754](https://github.com/microsoft/vscode/issues/304754) | Rambling on. | 0 | correctness | 3/6 Plausible | 2 | — | `npm run implement -- --issue 304754` |
| 168 | [#320471](https://github.com/microsoft/vscode/issues/320471) | Copilot stuck | 0 | correctness | 3/6 Plausible | 2 | — | `npm run implement -- --issue 320471` |
| 179 | [#300081](https://github.com/microsoft/vscode/issues/300081) | Stalling | 1 | none | 3/6 Plausible | 1 | — | — |
| 214 | [#300790](https://github.com/microsoft/vscode/issues/300790) | Endless reasoning, hallucinations | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 215 | [#300958](https://github.com/microsoft/vscode/issues/300958) | the work keeps being interrupted | 0 | none | 3/6 Plausible | 1 | — | — |
| 216 | [#301469](https://github.com/microsoft/vscode/issues/301469) | Claude Agent Mode stuck in Thinking step | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 217 | [#301489](https://github.com/microsoft/vscode/issues/301489) | Chat entered loop | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 221 | [#304665](https://github.com/microsoft/vscode/issues/304665) | Copilot Chat 在即使打开了 autopilot 的情况下也不操作代码，并且生成的 response 中隐藏了真正有用的信息 | 0 | none | 3/6 Plausible | 1 | — | — |
| 224 | [#305627](https://github.com/microsoft/vscode/issues/305627) | Response stuck in a loop in agent mode | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 225 | [#305932](https://github.com/microsoft/vscode/issues/305932) | Forever loop in chat, session list shows Failed. | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 226 | [#306017](https://github.com/microsoft/vscode/issues/306017) | Copilot does not realize it's in ask mode | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 227 | [#306657](https://github.com/microsoft/vscode/issues/306657) | Simple Task Taking Forever To Finish | 0 | none | 3/6 Plausible | 1 | — | — |
| 230 | [#308542](https://github.com/microsoft/vscode/issues/308542) | not able to reset/stop agent | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 233 | [#312400](https://github.com/microsoft/vscode/issues/312400) | agent mistakenly things it is in ask mode | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 239 | [#316051](https://github.com/microsoft/vscode/issues/316051) | Copilot Chat Agent uses wrong session/file context when multiple chat sessions are active | 0 | correctness | 4/6 Traced | 1 | — | `npm run implement -- --issue 316051` |
| 253 | [#324979](https://github.com/microsoft/vscode/issues/324979) | Agent believes tools are disabled after usage budget runs out, and doesn't recover when budget is restored | 0 | correctness | 3/6 Plausible | 1 | — | `npm run implement -- --issue 324979` |
| 289 | [#275451](https://github.com/microsoft/vscode/issues/275451) | Ask mode sometimes thinks it can edit | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 275451` |
| 312 | [#293335](https://github.com/microsoft/vscode/issues/293335) | agent未执行完任务就结束了 | 0 | none | 3/6 Plausible | 0 | — | — |
| 314 | [#295743](https://github.com/microsoft/vscode/issues/295743) | Stalled on asking questions for 10 minutes without completing nor timeouting | 0 | none | 3/6 Plausible | 0 | — | — |
| 318 | [#301083](https://github.com/microsoft/vscode/issues/301083) | Yes, Ok, The end. infinite loop | 0 | none | 3/6 Plausible | 0 | — | — |
| 319 | [#301106](https://github.com/microsoft/vscode/issues/301106) | Grok Code Fast trapped in weird hallucination loop | 0 | none | — | 0 | — | — |
| 321 | [#301309](https://github.com/microsoft/vscode/issues/301309) | Agent has forgotten it has tools? | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 324 | [#301642](https://github.com/microsoft/vscode/issues/301642) | Too long answer | 0 | none | 3/6 Plausible | 0 | — | — |
| 325 | [#301725](https://github.com/microsoft/vscode/issues/301725) | Repeating Similar information many times. | 0 | none | 3/6 Plausible | 0 | — | — |
| 328 | [#301818](https://github.com/microsoft/vscode/issues/301818) | "it" word repeated non-stop in reasoning | 0 | none | 3/6 Plausible | 0 | — | — |
| 330 | [#302249](https://github.com/microsoft/vscode/issues/302249) | Sub agent keeps getting stuck | 0 | freeze | 3/6 Plausible | 0 | — | — |
| 333 | [#302369](https://github.com/microsoft/vscode/issues/302369) | Agent vs Plan modes mix up on multiple chats | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 339 | [#303111](https://github.com/microsoft/vscode/issues/303111) | Agent looped whith "done" reccursive into and infinite loop | 0 | none | 3/6 Plausible | 0 | — | — |
| 340 | [#303112](https://github.com/microsoft/vscode/issues/303112) | Agent looped whith "done" reccursive into and infinite loop | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 341 | [#303113](https://github.com/microsoft/vscode/issues/303113) | Agent looped whith "done" reccursive into and infinite loop | 0 | none | 3/6 Plausible | 0 | — | — |
| 343 | [#303378](https://github.com/microsoft/vscode/issues/303378) | Agent was looping over the same information | 0 | none | 3/6 Plausible | 0 | — | — |
| 348 | [#305044](https://github.com/microsoft/vscode/issues/305044) | Over and Over again | 0 | none | — | 0 | — | — |
| 349 | [#305046](https://github.com/microsoft/vscode/issues/305046) | Copilot Chat Agent alway make fake response | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 350 | [#305134](https://github.com/microsoft/vscode/issues/305134) | Not able to complete the request | 0 | none | 3/6 Plausible | 0 | — | — |
| 359 | [#312343](https://github.com/microsoft/vscode/issues/312343) | Todo lists are intermittently (but frequently) left incomplete | 0 | visual | 3/6 Plausible | 0 | — | — |
| 363 | [#313144](https://github.com/microsoft/vscode/issues/313144) | Agent mode stops before completing tasks with Claude Sonnet 4.6, logs show Unknown content_block type 'text' | 0 | papercut | 2/6 Unverified | 0 | — | — |
| 378 | [#317827](https://github.com/microsoft/vscode/issues/317827) | Agent window: other modes should be disabled in sub agent if it is not supported | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 317827` |
| 382 | [#318924](https://github.com/microsoft/vscode/issues/318924) | Copilot resumes chat when it should not | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 318924` |
| 386 | [#320463](https://github.com/microsoft/vscode/issues/320463) | "steering" the agent during execution dumped the entire session into the comment | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 320463` |
| 396 | [#324083](https://github.com/microsoft/vscode/issues/324083) | Agents: forked session stuck when making edits+asking question | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 324083` |
| 400 | [#325287](https://github.com/microsoft/vscode/issues/325287) | Copilot Chat — Agent mode silently active despite Ask mode selected | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 401 | [#325290](https://github.com/microsoft/vscode/issues/325290) | Copilot Chat — Agent mode silently active despite Ask mode selected | 0 | none | 3/6 Plausible | 0 | — | — |
| 404 | [#325432](https://github.com/microsoft/vscode/issues/325432) | [security] GitHib Copilot cannot be stopped or canceled | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 407 | [#325884](https://github.com/microsoft/vscode/issues/325884) | Agent Host: editing a steering message when it's in a pending state causes all versions to be sent | 0 | correctness | — | 0 | — | `npm run implement -- --issue 325884` |

### Tool invocation (67)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2 | [#271711](https://github.com/microsoft/vscode/issues/271711) | Failed to apply code block: Response contained no choices. | 16 | correctness | 4/6 Traced | 71 | — | `npm run implement -- --issue 271711` |
| 17 | [#284959](https://github.com/microsoft/vscode/issues/284959) | Copilot silently corrupts long attached files | 0 | correctness | 5/6 Source-confirmed | 22 | — | `npm run implement -- --issue 284959` |
| 29 | [#313037](https://github.com/microsoft/vscode/issues/313037) | [Error] [GitHub.copilot-chat] unhandlederror-ENOENT: no such file or directory, open '<REDACTED: user-file-path>' | 0 | correctness | 3/6 Plausible | 15 | — | `npm run implement -- --issue 313037` |
| 31 | [#314858](https://github.com/microsoft/vscode/issues/314858) | AgentHost: Terminal tool calls with confirmation are shown twice | 1 | visual | 6/6 Confirmed | 14 | — | `npm run implement -- --issue 314858` |
| 34 | [#295655](https://github.com/microsoft/vscode/issues/295655) | Spawn UNKNOWN in Search/Chat | 0 | correctness | 6/6 Confirmed | 12 | — | `npm run implement -- --issue 295655` |
| 35 | [#304931](https://github.com/microsoft/vscode/issues/304931) | Copilot Chat extension constantly referencing non-existent github/issue_read | 5 | papercut | 5/6 Source-confirmed | 10 | — | — |
| 39 | [#293430](https://github.com/microsoft/vscode/issues/293430) | GitHub Copilot `file_search` glob with `\**\` (backslash double-star) produces partial or no results where `/**/` succeeds | 0 | correctness | 4/6 Traced | 10 | — | `npm run implement -- --issue 293430` |
| 43 | [#319858](https://github.com/microsoft/vscode/issues/319858) | Agent tool `read/problems` on Windows is sensitive to drive letter case. Not stable enough. | 0 | correctness | 5/6 Source-confirmed | 9 | — | `npm run implement -- --issue 319858` |
| 55 | [#298393](https://github.com/microsoft/vscode/issues/298393) | Critical bug: Unauthorized file/folder deletion by auto-editing agent caused data loss | 0 | data-loss | 3/6 Plausible | 8 | — | — |
| 56 | [#258246](https://github.com/microsoft/vscode/issues/258246) | Chat list_code_usages for .NET: Cannot read properties of undefined (reading 'find') | 1 | correctness | 3/6 Plausible | 7 | — | `npm run implement -- --issue 258246` |
| 57 | [#313029](https://github.com/microsoft/vscode/issues/313029) | Support for agent plugin repos without the `.git` preffix | 1 | correctness | 5/6 Source-confirmed | 7 | yes | `npm run implement -- --issue 313029` |
| 65 | [#280809](https://github.com/microsoft/vscode/issues/280809) | The response from model isn't translated to tool invocation | 0 | correctness | 3/6 Plausible | 6 | — | `npm run implement -- --issue 280809` |
| 66 | [#292064](https://github.com/microsoft/vscode/issues/292064) | #changes variable goes missing when sending to new chat | 0 | correctness | 6/6 Confirmed | 6 | — | `npm run implement -- --issue 292064` |
| 73 | [#307605](https://github.com/microsoft/vscode/issues/307605) | # reference picker should prioritize the active document at the top of the suggestion list | 2 | papercut | 5/6 Source-confirmed | 5 | — | `npm run implement -- --issue 307605` |
| 81 | [#283200](https://github.com/microsoft/vscode/issues/283200) | Agent misses user edits - EditedFileEvents missing | 0 | correctness | 3/6 Plausible | 5 | — | `npm run implement -- --issue 283200` |
| 87 | [#262604](https://github.com/microsoft/vscode/issues/262604) | Contributed Chat Participants don't work in Web Extensions | 0 | correctness | 6/6 Confirmed | 4 | — | `npm run implement -- --issue 262604` |
| 88 | [#270607](https://github.com/microsoft/vscode/issues/270607) | Can't attach an SVG to have the agent edit it | 0 | correctness | 5/6 Source-confirmed | 4 | yes | `npm run implement -- --issue 270607` |
| 89 | [#284340](https://github.com/microsoft/vscode/issues/284340) | Tool call not logged in chat debug view after summarization happens | 0 | correctness | 6/6 Confirmed | 4 | — | `npm run implement -- --issue 284340` |
| 90 | [#285326](https://github.com/microsoft/vscode/issues/285326) | In agent mode, recognize uppercase filenames as lowercase filenames. | 0 | correctness | 3/6 Plausible | 4 | — | `npm run implement -- --issue 285326` |
| 94 | [#298472](https://github.com/microsoft/vscode/issues/298472) | PreToolUse 'continue' blocks tool but doesn't terminate loop | 0 | correctness | 5/6 Source-confirmed | 4 | — | `npm run implement -- --issue 298472` |
| 96 | [#300583](https://github.com/microsoft/vscode/issues/300583) | SubagentStart, UserPromptSubmit, and SubagentStop hooks don't have `transcript_path` in their input | 0 | correctness | 5/6 Source-confirmed | 4 | — | `npm run implement -- --issue 300583` |
| 99 | [#305994](https://github.com/microsoft/vscode/issues/305994) | execution_subagent doesn't have skill context | 0 | correctness | 5/6 Source-confirmed | 4 | — | `npm run implement -- --issue 305994` |
| 101 | [#311867](https://github.com/microsoft/vscode/issues/311867) | Plan->Agent doesnt give permissions to edit code | 0 | correctness | 2/6 Unverified | 4 | — | — |
| 104 | [#319541](https://github.com/microsoft/vscode/issues/319541) | Agents window: MCP tools are listed/startable but execution fails with "No MCP client found for tool ID" | 0 | correctness | 3/6 Plausible | 4 | — | `npm run implement -- --issue 319541` |
| 116 | [#304839](https://github.com/microsoft/vscode/issues/304839) | Agent file problems | 1 | papercut | 2/6 Unverified | 3 | — | — |
| 117 | [#313857](https://github.com/microsoft/vscode/issues/313857) | copilot tools are mismatched, selective filtering is partially broken with custom toolsets and tool names do not match | 1 | correctness | 3/6 Plausible | 3 | — | `npm run implement -- --issue 313857` |
| 118 | [#316783](https://github.com/microsoft/vscode/issues/316783) | vscode_listCodeUsages reports 0 usages to Copilot if a user invoked find all references is invoked | 1 | correctness | 5/6 Source-confirmed | 3 | — | `npm run implement -- --issue 316783` |
| 135 | [#283224](https://github.com/microsoft/vscode/issues/283224) | Canceled mcp tool shows "Canceled: canceled" | 1 | visual | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 283224` |
| 141 | [#325523](https://github.com/microsoft/vscode/issues/325523) | Copilot chat shows ignored-files troubleshooting text in grep search tool completion UI | 1 | visual | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 325523` |
| 148 | [#242930](https://github.com/microsoft/vscode/issues/242930) | Powershell extension activated for a chat terminal command | 0 | papercut | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 242930` |
| 153 | [#287844](https://github.com/microsoft/vscode/issues/287844) | Copilot Agent create_file fails on NTFS data drive (D:) but works on C:\ and Dev Drive (ReFS) | 0 | correctness | 3/6 Plausible | 2 | — | `npm run implement -- --issue 287844` |
| 156 | [#289826](https://github.com/microsoft/vscode/issues/289826) | Agent: Search subagent isn't finding what I need chain of failures | 0 | correctness | 3/6 Plausible | 2 | — | `npm run implement -- --issue 289826` |
| 166 | [#312976](https://github.com/microsoft/vscode/issues/312976) | Copilot CLI with worktree mode made local changes | 0 | correctness | 6/6 Confirmed | 2 | — | `npm run implement -- --issue 312976` |
| 170 | [#324907](https://github.com/microsoft/vscode/issues/324907) | Copilot Agent built-in list_dir returns unbounded output for large directories and freezes/poisons the chat session | 0 | freeze | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 324907` |
| 198 | [#252133](https://github.com/microsoft/vscode/issues/252133) | RangeError [ERR_CHILD_PROCESS_STDIO_MAXBUFFER]: stdout maxBuffer length exceeded | 0 | papercut | 2/6 Unverified | 1 | — | — |
| 204 | [#284304](https://github.com/microsoft/vscode/issues/284304) | Subagent spawned by subagent inherits root tools by default, not the spawner's tools | 0 | correctness | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 284304` |
| 206 | [#292095](https://github.com/microsoft/vscode/issues/292095) | Permission to read prompt file already attached? | 0 | correctness | 3/6 Plausible | 1 | — | `npm run implement -- --issue 292095` |
| 209 | [#296172](https://github.com/microsoft/vscode/issues/296172) | Tool picker live-syncs to running agent session | 0 | correctness | 3/6 Plausible | 1 | — | `npm run implement -- --issue 296172` |
| 213 | [#299106](https://github.com/microsoft/vscode/issues/299106) | File got deleted despite denying the tool call | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 237 | [#313330](https://github.com/microsoft/vscode/issues/313330) | Race between replace_string_in_file and terminal commands in chat | 0 | correctness | 3/6 Plausible | 1 | — | `npm run implement -- --issue 313330` |
| 246 | [#317706](https://github.com/microsoft/vscode/issues/317706) | Agents app: Shows different set of available agents/skills etc. within the same workspace | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 256 | [#325280](https://github.com/microsoft/vscode/issues/325280) | Copilot creates a file twice in the same turn | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 263 | [#325825](https://github.com/microsoft/vscode/issues/325825) | Configure Tools selection still does not persist in VS Code 1.128.0 | 0 | correctness | 2/6 Unverified | 1 | — | — |
| 264 | [#326041](https://github.com/microsoft/vscode/issues/326041) | AH: agent edit does not show in a dirty file in the editor | 0 | correctness | — | 1 | — | `npm run implement -- --issue 326041` |
| 265 | [#326153](https://github.com/microsoft/vscode/issues/326153) | Duplicate groups and tools appear in the model's available tool list. After the 1.129.0 upgrade, third-party plugins cannot correctly register tool sets, causing entire batches of tools to be hidden and unselectable. | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 285 | [#251118](https://github.com/microsoft/vscode/issues/251118) | Chat: Inline context doesn't work inside parens | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 251118` |
| 291 | [#283649](https://github.com/microsoft/vscode/issues/283649) | Extension tools should require confirmation by default if prepareInvocation is not implemented | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 283649` |
| 292 | [#286277](https://github.com/microsoft/vscode/issues/286277) | Large pasted content in Copilot Chat silently dropped - message appears empty to AI | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 316 | [#299757](https://github.com/microsoft/vscode/issues/299757) | Agent Plugins: 404 error when fetching marketplace.json from awesome-copilot repo | 0 | papercut | 2/6 Unverified | 0 | — | — |
| 320 | [#301220](https://github.com/microsoft/vscode/issues/301220) | Locked `Explore.agent.md` frontmatter appears editable using `Configure Tools...` but actually isn't | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 301220` |
| 323 | [#301582](https://github.com/microsoft/vscode/issues/301582) | create_file tool corrupts file content for Go files | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 338 | [#303074](https://github.com/microsoft/vscode/issues/303074) | "Allow All Commands" not work in chat session | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 303074` |
| 345 | [#304888](https://github.com/microsoft/vscode/issues/304888) | Inconsistency in tools definition for Copilot in VSCode and GitHub Copilot CLI | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 304888` |
| 346 | [#304936](https://github.com/microsoft/vscode/issues/304936) | I have to modify my agents to allow them to use tools | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 304936` |
| 351 | [#305143](https://github.com/microsoft/vscode/issues/305143) | GPT-5.3 Codex does not call any tools | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 352 | [#305638](https://github.com/microsoft/vscode/issues/305638) | 无法读取文件内容 | 0 | none | 3/6 Plausible | 0 | — | — |
| 362 | [#313092](https://github.com/microsoft/vscode/issues/313092) | GPT 5.5 doesn't detect agent changes properly | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 313092` |
| 365 | [#313222](https://github.com/microsoft/vscode/issues/313222) | validatePipeline Copilot agent tool fails with "No such remote 'origin'" when git remote is named differently | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 313222` |
| 366 | [#313323](https://github.com/microsoft/vscode/issues/313323) | agents: Workspace Trust Dialog is not shown | 0 | correctness | 2/6 Unverified | 0 | — | `npm run implement -- --issue 313323` |
| 370 | [#316243](https://github.com/microsoft/vscode/issues/316243) | Copilot CLI agent panel: CWD silently inherited from active terminal, not from open workspace | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 371 | [#316983](https://github.com/microsoft/vscode/issues/316983) | Bug: "tools: Tool names must be unique" Error when using Claude Sonnet 4.5 or 4.6 in Plan, Ask and Agent modes with the VSCode tool enabled | 0 | correctness | 4/6 Traced | 0 | yes | `npm run implement -- --issue 316983` |
| 373 | [#317270](https://github.com/microsoft/vscode/issues/317270) | Killing hidden terminals trigger model call | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 377 | [#317771](https://github.com/microsoft/vscode/issues/317771) | [BUG] No results returned for the `fileSearch` tool when querying a network drive, works fine when ommited | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 317771` |
| 381 | [#318872](https://github.com/microsoft/vscode/issues/318872) | Copilot Chat debug file logging omits per-turn events for empty-window chat sessions | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 385 | [#320418](https://github.com/microsoft/vscode/issues/320418) | Copilot CLI: `create` tool hangs indefinitely for paths outside the workspace | 0 | freeze | 5/6 Source-confirmed | 0 | — | — |
| 388 | [#320635](https://github.com/microsoft/vscode/issues/320635) | Claude Sonnet 4.x Request Failed: 400 Tool names must be unique (bug, workaround) | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 320635` |
| 402 | [#325381](https://github.com/microsoft/vscode/issues/325381) | Copilot agent regex search returns zero results for files outside workspace root | 0 | correctness | 4/6 Traced | 0 | — | `npm run implement -- --issue 325381` |

### Performance freezes (17)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 4 | [#281743](https://github.com/microsoft/vscode/issues/281743) | Copilot chat makes vscode unresponsive | 2 | freeze | 2/6 Unverified | 45 | — | `npm run implement -- --issue 281743` |
| 7 | [#271740](https://github.com/microsoft/vscode/issues/271740) | Freeze on "Summarizing conversation history" | 3 | freeze | — | 35 | — | `npm run implement -- --issue 271740` |
| 13 | [#308769](https://github.com/microsoft/vscode/issues/308769) | Copilot causing my VS Code to periodically freeze making it very hard to use | 4 | freeze | 3/6 Plausible | 30 | — | — |
| 19 | [#299174](https://github.com/microsoft/vscode/issues/299174) | A running Copilot agent results in high CPU usage (> 70% CPU time spent on "Recalculate style") | 4 | perf | 3/6 Plausible | 19 | — | `npm run implement -- --issue 299174` |
| 37 | [#261512](https://github.com/microsoft/vscode/issues/261512) | copilot chat session unresponsive | 2 | correctness | 3/6 Plausible | 10 | — | `npm run implement -- --issue 261512` |
| 38 | [#291821](https://github.com/microsoft/vscode/issues/291821) | GitHub Copilot Chat causes severe performance degradation in VSCode and system | 0 | perf | 3/6 Plausible | 10 | — | — |
| 42 | [#286250](https://github.com/microsoft/vscode/issues/286250) | Kicking off multiple agent sessions sometimes leads to freezing or delay in agent sessions list | 0 | correctness | 3/6 Plausible | 9 | — | `npm run implement -- --issue 286250` |
| 53 | [#293537](https://github.com/microsoft/vscode/issues/293537) | Files and Editors frozen when Agent is working | 0 | freeze | 3/6 Plausible | 8 | — | `npm run implement -- --issue 293537` |
| 62 | [#291282](https://github.com/microsoft/vscode/issues/291282) | Having too many "un-kept" file changes in previous AI Chat sessions eventually causes the UI to lock-up entirely at least once per minute and 100% of the time on focus | 1 | freeze | 3/6 Plausible | 6 | — | — |
| 113 | [#286611](https://github.com/microsoft/vscode/issues/286611) | Slow chat switching- keep ChatModel in memory for a bit | 1 | perf | 5/6 Source-confirmed | 3 | — | `npm run implement -- --issue 286611` |
| 167 | [#315314](https://github.com/microsoft/vscode/issues/315314) | Hydrating large chat session items block renderer during startup | 0 | perf | 6/6 Confirmed | 2 | — | `npm run implement -- --issue 315314` |
| 229 | [#308200](https://github.com/microsoft/vscode/issues/308200) | Chat is unresponsive | 0 | none | 3/6 Plausible | 1 | — | — |
| 238 | [#315357](https://github.com/microsoft/vscode/issues/315357) | Unresponsive | 0 | none | 3/6 Plausible | 1 | — | — |
| 262 | [#325715](https://github.com/microsoft/vscode/issues/325715) | Performance | 0 | none | 3/6 Plausible | 1 | — | — |
| 327 | [#301788](https://github.com/microsoft/vscode/issues/301788) | Copilot Chat pending changes makes vscode slow | 0 | perf | 3/6 Plausible | 0 | — | — |
| 374 | [#317319](https://github.com/microsoft/vscode/issues/317319) | GitHub Copilot Chat is repeatedly attributed in extension host unresponsive profiles during agent sessions on Windows; hottest frames include tokenCount, baseMessageTokenCount, and _getFinalElementTree | 0 | perf | 3/6 Plausible | 0 | — | `npm run implement -- --issue 317319` |
| 398 | [#324330](https://github.com/microsoft/vscode/issues/324330) | Start the agent host process earlier (prewarm) so local sessions appear quickly on window startup | 0 | perf | — | 0 | — | `npm run implement -- --issue 324330` |

### Chat history (46)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 5 | [#301793](https://github.com/microsoft/vscode/issues/301793) | Copilot Chat history is completely lost after saving an "Untitled Workspace" as a .code-workspace file | 7 | data-loss | 5/6 Source-confirmed | 40 | — | `npm run implement -- --issue 301793` |
| 9 | [#283714](https://github.com/microsoft/vscode/issues/283714) | Past chat sessions can't be opened after transitioning to a multi-root workspace | 10 | correctness | 2/6 Unverified | 32 | — | `npm run implement -- --issue 283714` |
| 14 | [#326241](https://github.com/microsoft/vscode/issues/326241) | Renderer crashes at fixed native offset (+0x90e8a8e) opening workspaces whose chat/agent-sessions state references a malformed (truncated) transcript — regression in 1.129.0 | 2 | crash | 2/6 Unverified | 26 | — | — |
| 18 | [#307348](https://github.com/microsoft/vscode/issues/307348) | Chat session permanently unloadable after VS Code killed mid-response (TypeError: Cannot read properties of undefined (reading 'response')) | 0 | data-loss | 5/6 Source-confirmed | 22 | — | `npm run implement -- --issue 307348` |
| 20 | [#308369](https://github.com/microsoft/vscode/issues/308369) | Copilot Chat session history intermittently disappears, causing loss of long-running context | 2 | correctness | 3/6 Plausible | 19 | — | — |
| 28 | [#312610](https://github.com/microsoft/vscode/issues/312610) | [critical] new GitHub Copilot sessions never appear in list and are irretrievable if Copilot enabled after workspace opened | 1 | data-loss | 3/6 Plausible | 15 | — | `npm run implement -- --issue 312610` |
| 30 | [#299231](https://github.com/microsoft/vscode/issues/299231) | Unable to open a specific conversation after clicking | 1 | correctness | 5/6 Source-confirmed | 14 | — | `npm run implement -- --issue 299231` |
| 32 | [#324959](https://github.com/microsoft/vscode/issues/324959) | Copilot Chat: All previous session history silently lost after upgrade (.json → .jsonl format migration not performed) | 1 | data-loss | 3/6 Plausible | 12 | — | `npm run implement -- --issue 324959` |
| 40 | [#306277](https://github.com/microsoft/vscode/issues/306277) | Deleting a session doesn't seem to do anything | 0 | correctness | 2/6 Unverified | 10 | — | `npm run implement -- --issue 306277` |
| 48 | [#279112](https://github.com/microsoft/vscode/issues/279112) | GitHub Copilot Chat incorrectly includes model enablement text in chat history | 0 | correctness | 3/6 Plausible | 8 | — | `npm run implement -- --issue 279112` |
| 51 | [#290866](https://github.com/microsoft/vscode/issues/290866) | Lost messages in AI chat | 0 | data-loss | 3/6 Plausible | 8 | — | — |
| 54 | [#296663](https://github.com/microsoft/vscode/issues/296663) | `ChatTitleProvider#provideChatTitle` which passes in `context: vscode.ChatContext,` does not include the `chatSessionItem` | 0 | correctness | 5/6 Source-confirmed | 8 | — | `npm run implement -- --issue 296663` |
| 60 | [#317453](https://github.com/microsoft/vscode/issues/317453) | AgentHost: Opening AH chat session in vscode should open the same session | 0 | correctness | — | 7 | — | `npm run implement -- --issue 317453` |
| 63 | [#321290](https://github.com/microsoft/vscode/issues/321290) | Chat session marked empty and hidden while Copilot transcript/edit state remain intact | 1 | data-loss | 3/6 Plausible | 6 | — | `npm run implement -- --issue 321290` |
| 75 | [#297871](https://github.com/microsoft/vscode/issues/297871) | PAST CHATS ARE MISSING - HAVE BEEN FOR 2 WEEKS. PLEASE FIX IT. | 1 | correctness | 2/6 Unverified | 5 | — | — |
| 97 | [#303061](https://github.com/microsoft/vscode/issues/303061) | /COMPACT caused the plan chat session to get deleted | 0 | data-loss | 2/6 Unverified | 4 | — | — |
| 109 | [#295693](https://github.com/microsoft/vscode/issues/295693) | GitHub Copilot Chat History Not Persisting Despite Enabled Settings | 2 | none | 3/6 Plausible | 3 | — | — |
| 125 | [#281223](https://github.com/microsoft/vscode/issues/281223) | Background/Cloud chats are not restored in sidebar after reload/restart | 0 | correctness | 3/6 Plausible | 3 | — | `npm run implement -- --issue 281223` |
| 130 | [#313236](https://github.com/microsoft/vscode/issues/313236) | Some chat sessions are emptied out, but remain in history and in workspaceStorage | 0 | correctness | 3/6 Plausible | 3 | — | `npm run implement -- --issue 313236` |
| 151 | [#275408](https://github.com/microsoft/vscode/issues/275408) | Most recent Codex session shows persistent loading indicator in chat sessions view | 0 | visual | 3/6 Plausible | 2 | — | `npm run implement -- --issue 275408` |
| 157 | [#295377](https://github.com/microsoft/vscode/issues/295377) | Thinking titles are sometimes not saved | 0 | correctness | 3/6 Plausible | 2 | — | `npm run implement -- --issue 295377` |
| 202 | [#280544](https://github.com/microsoft/vscode/issues/280544) | Agent sessions: recent sessions list flashes on first open of chat view | 0 | visual | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 280544` |
| 205 | [#286093](https://github.com/microsoft/vscode/issues/286093) | Agent sessions - recent list update before session is loaded | 0 | visual | 3/6 Plausible | 1 | — | `npm run implement -- --issue 286093` |
| 211 | [#297276](https://github.com/microsoft/vscode/issues/297276) | UI Rendering Issue: Chat sessions and history are not updating in real-time in the new Agent Sessions sidebar | 0 | correctness | 2/6 Unverified | 1 | — | — |
| 212 | [#297788](https://github.com/microsoft/vscode/issues/297788) | Adding the Workspace's chatSessions folder to the workspace prevents chat sessions from loading | 0 | correctness | 2/6 Unverified | 1 | — | — |
| 218 | [#301777](https://github.com/microsoft/vscode/issues/301777) | Codexとの会話履歴が復元できない | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 220 | [#303759](https://github.com/microsoft/vscode/issues/303759) | Chat history disappears ONLY when I click or open another tab on VS Code | 0 | none | 3/6 Plausible | 1 | — | — |
| 242 | [#316380](https://github.com/microsoft/vscode/issues/316380) | Unable to Permanently Delete Archived AI Agent Conversations in VS Code Chat | 0 | papercut | 3/6 Plausible | 1 | — | — |
| 250 | [#322566](https://github.com/microsoft/vscode/issues/322566) | Renamed chat session title reverts to auto-generated name on reopen (1.126.0) | 0 | correctness | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 322566` |
| 261 | [#325673](https://github.com/microsoft/vscode/issues/325673) | Agent host: Delete... on a Claude session doesn't delete the SDK transcript — session resurrects on next list refresh | 0 | correctness | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 325673` |
| 317 | [#299967](https://github.com/microsoft/vscode/issues/299967) | Failed to open chat session: Cannot read properties of undefined (reading 'match') | 0 | correctness | 6/6 Confirmed | 0 | — | — |
| 329 | [#302013](https://github.com/microsoft/vscode/issues/302013) | When submitting a copilot chat request one or more new vscode windows open and begin processing an old copilot chat session that was already complete. | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 332 | [#302348](https://github.com/microsoft/vscode/issues/302348) | Can not leave session started by agentSessionWelcomePage | 0 | correctness | 6/6 Confirmed | 0 | — | — |
| 342 | [#303185](https://github.com/microsoft/vscode/issues/303185) | Sessions: Checkout button fails with error on cloud agent chat | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 355 | [#308833](https://github.com/microsoft/vscode/issues/308833) | Editing chats doesn't work properly | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 308833` |
| 357 | [#312306](https://github.com/microsoft/vscode/issues/312306) | Copilot Chat session appeared to reset/crash during multi-step documentation workflow | 0 | none | 3/6 Plausible | 0 | — | — |
| 358 | [#312308](https://github.com/microsoft/vscode/issues/312308) | Agents: Multiple issues > General/Sessions/Sub-sessions/PR Review | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 361 | [#313034](https://github.com/microsoft/vscode/issues/313034) | Github Copilot Session Error | 0 | data-loss | 2/6 Unverified | 0 | — | — |
| 383 | [#319599](https://github.com/microsoft/vscode/issues/319599) | message sent to local CLI with editor chat will create two session entries | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 319599` |
| 390 | [#320731](https://github.com/microsoft/vscode/issues/320731) | VS Code Error: "Error serializing chat session for storage" | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 391 | [#322521](https://github.com/microsoft/vscode/issues/322521) | Session disappears from session list | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 322521` |
| 394 | [#323679](https://github.com/microsoft/vscode/issues/323679) | Session file corrupted: negative data.tokensRemoved rejected by SDK ("Number must be greater than or equal to 0") | 0 | data-loss | — | 0 | — | `npm run implement -- --issue 323679` |
| 395 | [#323811](https://github.com/microsoft/vscode/issues/323811) | New chat sessions always leak | 0 | perf | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 323811` |
| 399 | [#324662](https://github.com/microsoft/vscode/issues/324662) | Copilot Chat history item silently fails to load when chatSessions JSONL is missing but session-store.db has transcript | 0 | papercut | 4/6 Traced | 0 | — | `npm run implement -- --issue 324662` |
| 405 | [#325474](https://github.com/microsoft/vscode/issues/325474) | TypeError: .pendingRequests[0].request.message.parts: Converting circular structure to JSON | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 325474` |
| 406 | [#325822](https://github.com/microsoft/vscode/issues/325822) | Critical: Chat session data lost when computer sleeps - Data loss + Financial loss | 0 | data-loss | 3/6 Plausible | 0 | — | — |

### Debugging launch (73)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 6 | [#278109](https://github.com/microsoft/vscode/issues/278109) | Debugger completions from debug adapter are not highlighting | 22 | visual | 5/6 Source-confirmed | 38 | — | `npm run implement -- --issue 278109` |
| 27 | [#88617](https://github.com/microsoft/vscode/issues/88617) | onDebugInitialConfigurations activation event causes extensions to load when pressing F5 to run other projects | 0 | perf | 5/6 Source-confirmed | 16 | — | `npm run implement -- --issue 88617` |
| 33 | [#275018](https://github.com/microsoft/vscode/issues/275018) | Changing default profile to bash on macOS does not update run_in_terminal prompt | 0 | correctness | 5/6 Source-confirmed | 12 | — | `npm run implement -- --issue 275018` |
| 36 | [#209116](https://github.com/microsoft/vscode/issues/209116) | Problems tab errors claim background preLaunchTask has errors | 2 | correctness | 5/6 Source-confirmed | 10 | — | `npm run implement -- --issue 209116` |
| 44 | [#66801](https://github.com/microsoft/vscode/issues/66801) | Input variables only work with one configuration in a compound launch config | 11 | correctness | 5/6 Source-confirmed | 8 | — | `npm run implement -- --issue 66801` |
| 47 | [#175872](https://github.com/microsoft/vscode/issues/175872) | setBreakpoints is called with sourceModified:false when source is dirty and new breakpoint is added | 0 | correctness | 5/6 Source-confirmed | 8 | yes | `npm run implement -- --issue 175872` |
| 70 | [#150083](https://github.com/microsoft/vscode/issues/150083) | When Debug: Inline Values is set together with Word wrap, breakpoints are not correctly focused | 3 | correctness | 2/6 Unverified | 5 | — | — |
| 71 | [#235168](https://github.com/microsoft/vscode/issues/235168) | Debugger hover doesn't work with parenthesized expressions | 3 | papercut | 5/6 Source-confirmed | 5 | yes | `npm run implement -- --issue 235168` |
| 72 | [#172108](https://github.com/microsoft/vscode/issues/172108) | Document Content Providers are being passed URI-unescaped paths when invoked through the DAP | 2 | correctness | 5/6 Source-confirmed | 5 | — | `npm run implement -- --issue 172108` |
| 77 | [#246811](https://github.com/microsoft/vscode/issues/246811) | Debug restart missing call to `onDidTerminateDebugSession` | 0 | correctness | 5/6 Source-confirmed | 5 | — | `npm run implement -- --issue 246811` |
| 83 | [#176795](https://github.com/microsoft/vscode/issues/176795) | Variables within a configuration snippet defined in package.json file are not being allowed | 2 | correctness | 5/6 Source-confirmed | 4 | — | `npm run implement -- --issue 176795` |
| 84 | [#95423](https://github.com/microsoft/vscode/issues/95423) | ${file} - must be the current opened file, but points to the name of output pane | 1 | correctness | 5/6 Source-confirmed | 4 | — | `npm run implement -- --issue 95423` |
| 107 | [#136187](https://github.com/microsoft/vscode/issues/136187) | Extension provided tasks are not recognized in workspace settings file only in .vscode/launch.json (for instance) | 4 | correctness | 5/6 Source-confirmed | 3 | yes | `npm run implement -- --issue 136187` |
| 108 | [#237414](https://github.com/microsoft/vscode/issues/237414) | Debug sessions become unresponsive after a failed 'restart' request | 2 | correctness | 5/6 Source-confirmed | 3 | yes | `npm run implement -- --issue 237414` |
| 110 | [#187440](https://github.com/microsoft/vscode/issues/187440) | F5 starts debugging when inactive, but refreshes the page when active | 1 | correctness | 5/6 Source-confirmed | 3 | yes | `npm run implement -- --issue 187440` |
| 112 | [#238279](https://github.com/microsoft/vscode/issues/238279) | Hovering over an expression with a `!` (like `foo!.bar`) while debugging does not evaluate the expression | 1 | papercut | 5/6 Source-confirmed | 3 | yes | `npm run implement -- --issue 238279` |
| 120 | [#135432](https://github.com/microsoft/vscode/issues/135432) | Debugger: runInTerminal request fails if the path has "ł" character in it | 0 | correctness | 3/6 Plausible | 3 | — | `npm run implement -- --issue 135432` |
| 121 | [#139764](https://github.com/microsoft/vscode/issues/139764) | Build does not wait for files to save | 0 | correctness | 5/6 Source-confirmed | 3 | yes | `npm run implement -- --issue 139764` |
| 122 | [#150465](https://github.com/microsoft/vscode/issues/150465) | Issue with encoding output in terminal | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 123 | [#239770](https://github.com/microsoft/vscode/issues/239770) | Alter an expression breakpoint deletes log message | 0 | correctness | 5/6 Source-confirmed | 3 | — | `npm run implement -- --issue 239770` |
| 133 | [#202204](https://github.com/microsoft/vscode/issues/202204) | Debug toolbar can be hidden by window resize | 2 | visual | 2/6 Unverified | 2 | — | — |
| 142 | [#122775](https://github.com/microsoft/vscode/issues/122775) | Call Stack bounces when short-lived second requests start/stop | 0 | papercut | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 122775` |
| 143 | [#129532](https://github.com/microsoft/vscode/issues/129532) | Disassembly view: not possible to set instruction breakpoint with keyboard | 0 | correctness | 2/6 Unverified | 2 | — | — |
| 144 | [#143991](https://github.com/microsoft/vscode/issues/143991) | DAP - Terminate Request is not sent for "Attach" Configurations | 0 | correctness | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 143991` |
| 145 | [#162965](https://github.com/microsoft/vscode/issues/162965) | The representation of a variable introspected in the Debug Console can be clipped on VSCode. | 0 | visual | 3/6 Plausible | 2 | — | — |
| 146 | [#171238](https://github.com/microsoft/vscode/issues/171238) | Regression: debugger cannot attach to a child process | 0 | correctness | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 171238` |
| 171 | [#129425](https://github.com/microsoft/vscode/issues/129425) | Chosen user-settings debug launch configuration not remembered | 2 | papercut | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 129425` |
| 172 | [#130083](https://github.com/microsoft/vscode/issues/130083) | Selecting text from debug console history view is really hard | 2 | papercut | 2/6 Unverified | 1 | — | — |
| 173 | [#204391](https://github.com/microsoft/vscode/issues/204391) | Debug Console filter with Go is difficult to use and inaccurate | 2 | papercut | 3/6 Plausible | 1 | — | — |
| 174 | [#249889](https://github.com/microsoft/vscode/issues/249889) | Debug hover tooltip too small | 2 | papercut | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 249889` |
| 175 | [#140980](https://github.com/microsoft/vscode/issues/140980) | Debug targets that don't exist in launch.json | 1 | papercut | 4/6 Traced | 1 | yes | `npm run implement -- --issue 140980` |
| 176 | [#210854](https://github.com/microsoft/vscode/issues/210854) | Changing lettercase of directory causes unbound breakpoints as VSCode does not refresh path | 1 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 210854` |
| 177 | [#225594](https://github.com/microsoft/vscode/issues/225594) | `Load More Stack Frames` renders poorly when horizontalScrolling enabled | 1 | visual | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 225594` |
| 178 | [#229888](https://github.com/microsoft/vscode/issues/229888) | [Bug] OS-Level Launch Configuration Not Behaving As Expected | 1 | correctness | 2/6 Unverified | 1 | — | — |
| 181 | [#85290](https://github.com/microsoft/vscode/issues/85290) | Debugging should handle identical sources in sourceReference better | 0 | correctness | 4/6 Traced | 1 | — | `npm run implement -- --issue 85290` |
| 182 | [#117554](https://github.com/microsoft/vscode/issues/117554) | When processing setBreakpoints response treat undefined source.path the same as undefined source | 0 | correctness | 4/6 Traced | 1 | yes | `npm run implement -- --issue 117554` |
| 183 | [#128744](https://github.com/microsoft/vscode/issues/128744) | DAP ContinuedEvent with allThreadsContinued=true causes selected debug session to change | 0 | papercut | 4/6 Traced | 1 | — | `npm run implement -- --issue 128744` |
| 184 | [#131502](https://github.com/microsoft/vscode/issues/131502) | Source code downloaded via the debuggers sourceRequest creates lots of duplicate open files across debug sessions | 0 | papercut | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 131502` |
| 185 | [#153480](https://github.com/microsoft/vscode/issues/153480) | Stopping debug while pre-launch task runs causes popups | 0 | papercut | 3/6 Plausible | 1 | — | `npm run implement -- --issue 153480` |
| 186 | [#156351](https://github.com/microsoft/vscode/issues/156351) | Confusing dialog for contributed launch configs when errors occur | 0 | papercut | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 156351` |
| 187 | [#156842](https://github.com/microsoft/vscode/issues/156842) | Restarting a Debug Adapter doesn't reset the Visual Studio Interface | 0 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 156842` |
| 188 | [#164957](https://github.com/microsoft/vscode/issues/164957) | "Load More Stack Frames" is incorrectly displayed after debug adapter has sent the full stack | 0 | visual | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 164957` |
| 189 | [#171446](https://github.com/microsoft/vscode/issues/171446) | Problems pane gives incorrect advice about `launch.json`. | 0 | correctness | 2/6 Unverified | 1 | — | — |
| 190 | [#180488](https://github.com/microsoft/vscode/issues/180488) | DAP error response handling is confusing and inconsistent | 0 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 180488` |
| 191 | [#196009](https://github.com/microsoft/vscode/issues/196009) | DebugAdapterTracker not working in web extensions | 0 | correctness | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 196009` |
| 192 | [#196206](https://github.com/microsoft/vscode/issues/196206) | 'Disconnect' option doesn't show in Call-Stack Session in debugger | 0 | visual | 2/6 Unverified | 1 | — | — |
| 193 | [#204841](https://github.com/microsoft/vscode/issues/204841) | saving the .code-workspace resets the currently selected launch config from that file | 0 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 204841` |
| 194 | [#243477](https://github.com/microsoft/vscode/issues/243477) | Variables/Watch 'F2' for 'Set Value' is broken | 0 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 243477` |
| 195 | [#244875](https://github.com/microsoft/vscode/issues/244875) | Stopping hanging hot restart in Flutter breaks F5 start debugging key | 0 | correctness | 4/6 Traced | 1 | yes | `npm run implement -- --issue 244875` |
| 196 | [#247340](https://github.com/microsoft/vscode/issues/247340) | Some active breakpoints can be removed only from the Breakpoints menu | 0 | visual | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 247340` |
| 247 | [#318362](https://github.com/microsoft/vscode/issues/318362) | debug configuration doesn't restore to last selected after Reload Window(Remote SSH, multi-repo .code-workspace) | 0 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 318362` |
| 266 | [#145923](https://github.com/microsoft/vscode/issues/145923) | Up arrow in python debug console does not work as expected after using "Evaluate in Debug Console" | 1 | papercut | 2/6 Unverified | 0 | — | — |
| 267 | [#126257](https://github.com/microsoft/vscode/issues/126257) | function "setBreakPointsRequest" in the Debug Adapter is triggered to much | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 126257` |
| 268 | [#131655](https://github.com/microsoft/vscode/issues/131655) | [UI/UX] problem with disassembly page. | 0 | visual | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 131655` |
| 269 | [#144211](https://github.com/microsoft/vscode/issues/144211) | Debugger does not respect supportsDelayedStackTraceLoading false | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 144211` |
| 270 | [#144532](https://github.com/microsoft/vscode/issues/144532) | JavaScript Debug Console mangles output that includes both CSS and Object specifiers | 0 | visual | 3/6 Plausible | 0 | — | — |
| 271 | [#152639](https://github.com/microsoft/vscode/issues/152639) | Duplicate entries in edit breakpoint and related submenus | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 152639` |
| 272 | [#153469](https://github.com/microsoft/vscode/issues/153469) | Debug fails to show debug toolbar and toggle status bar color | 0 | visual | 3/6 Plausible | 0 | — | — |
| 273 | [#154866](https://github.com/microsoft/vscode/issues/154866) | Expand object in debug panel messes up with scroll top | 0 | papercut | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 154866` |
| 274 | [#161242](https://github.com/microsoft/vscode/issues/161242) | Dead debug state | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 161242` |
| 275 | [#166183](https://github.com/microsoft/vscode/issues/166183) | Wrong session restored after main window closed while another instance was running in debugger | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 166183` |
| 276 | [#174488](https://github.com/microsoft/vscode/issues/174488) | Annoying warnings in launch.json for configs that don't apply to current platform. | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 174488` |
| 277 | [#174972](https://github.com/microsoft/vscode/issues/174972) | Run to Cursor and Add to Watch available in JSON settings file context menu | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 174972` |
| 278 | [#186561](https://github.com/microsoft/vscode/issues/186561) | Copying text from the debug console doesn't work quite right | 0 | papercut | 2/6 Unverified | 0 | — | — |
| 279 | [#206056](https://github.com/microsoft/vscode/issues/206056) | CSS for debug icons applies to TreeItem inline commands | 0 | visual | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 206056` |
| 280 | [#208289](https://github.com/microsoft/vscode/issues/208289) | MultiProvider is not supported for registerDebugConfigurationProvider Dynamic | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 208289` |
| 281 | [#224676](https://github.com/microsoft/vscode/issues/224676) | Call-site sometimes off-screen when clicking thru (Python) call stack | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 282 | [#224685](https://github.com/microsoft/vscode/issues/224685) | "Copy Call Stack" in Debug uses the wrong path separator when debugging cross platform | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 224685` |
| 283 | [#241262](https://github.com/microsoft/vscode/issues/241262) | Debug Hover Widget Height Is Computed Inconsistently | 0 | visual | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 241262` |
| 284 | [#241638](https://github.com/microsoft/vscode/issues/241638) | Inconsistent Debug Console Hover Styling: list.hoverBackground Applies, but list.hoverForeground Does Not | 0 | visual | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 241638` |
| 334 | [#302390](https://github.com/microsoft/vscode/issues/302390) | Debug Console: text selection is lost when scrolling up (virtualized list resets selection) | 0 | papercut | 4/6 Traced | 0 | — | `npm run implement -- --issue 302390` |
| 367 | [#313736](https://github.com/microsoft/vscode/issues/313736) | Call Stack visual selection can remain on previous thread after per-thread step, despite activeStackItem changing | 0 | visual | 4/6 Traced | 0 | — | `npm run implement -- --issue 313736` |
| 392 | [#323141](https://github.com/microsoft/vscode/issues/323141) | Debug Play button can be hidden by making the view container to small | 0 | visual | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 323141` |

### Chat readiness (60)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 10 | [#298878](https://github.com/microsoft/vscode/issues/298878) | Copilot chat extension failed to initialize: "Chat took too long to get ready" error | 10 | correctness | 3/6 Plausible | 32 | — | — |
| 12 | [#285598](https://github.com/microsoft/vscode/issues/285598) | GitHub Copilot continually restarts extension host; chat prompt does not produce anything, and deletes chat debug history | 0 | freeze | 3/6 Plausible | 31 | — | `npm run implement -- --issue 285598` |
| 49 | [#279551](https://github.com/microsoft/vscode/issues/279551) | Failed to get a response. Please try again. | 0 | correctness | 3/6 Plausible | 8 | — | `npm run implement -- --issue 279551` |
| 85 | [#288615](https://github.com/microsoft/vscode/issues/288615) | Chat took too long to get ready | 1 | correctness | 3/6 Plausible | 4 | — | — |
| 91 | [#288546](https://github.com/microsoft/vscode/issues/288546) | Chat took too long to get ready | 0 | perf | 3/6 Plausible | 4 | — | — |
| 102 | [#313448](https://github.com/microsoft/vscode/issues/313448) | AI tools Copilot Chat and Codex doesn't work with this newest version. | 0 | none | 3/6 Plausible | 4 | — | — |
| 103 | [#318161](https://github.com/microsoft/vscode/issues/318161) | critical issue | 0 | data-loss | 3/6 Plausible | 4 | — | — |
| 106 | [#325167](https://github.com/microsoft/vscode/issues/325167) | github copilot chat broken | 0 | correctness | 3/6 Plausible | 4 | — | `npm run implement -- --issue 325167` |
| 131 | [#322755](https://github.com/microsoft/vscode/issues/322755) | [Error] [GitHub.copilot-chat] unhandlederror-t.with is not a function | 0 | correctness | 5/6 Source-confirmed | 3 | — | `npm run implement -- --issue 322755` |
| 132 | [#325711](https://github.com/microsoft/vscode/issues/325711) | [Bug] Claude agent SDK crashes with "Error during execution" in Copilot Chat (VS Code 1.127.0, Electron 42 / Node 24) | 0 | correctness | 4/6 Traced | 3 | — | `npm run implement -- --issue 325711` |
| 152 | [#286284](https://github.com/microsoft/vscode/issues/286284) | 'fetch failed' with no 'try again' | 0 | papercut | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 286284` |
| 154 | [#288005](https://github.com/microsoft/vscode/issues/288005) | Agent mode crashes | 0 | none | 3/6 Plausible | 2 | — | — |
| 155 | [#288301](https://github.com/microsoft/vscode/issues/288301) | Chat took too long to get ready | 0 | none | 3/6 Plausible | 2 | — | — |
| 163 | [#305100](https://github.com/microsoft/vscode/issues/305100) | Copilot is not working at all in MAC | 0 | none | 3/6 Plausible | 2 | — | — |
| 164 | [#305553](https://github.com/microsoft/vscode/issues/305553) | Some invalid str issue came in copilot | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 165 | [#307910](https://github.com/microsoft/vscode/issues/307910) | VS Code Insiders keeps crashing | 0 | freeze | 3/6 Plausible | 2 | — | — |
| 169 | [#324141](https://github.com/microsoft/vscode/issues/324141) | Extension host crashed due to GitHub Copilot Chat | 0 | crash | 3/6 Plausible | 2 | — | — |
| 180 | [#324004](https://github.com/microsoft/vscode/issues/324004) | Copilot not working | 1 | none | 3/6 Plausible | 1 | — | — |
| 200 | [#265248](https://github.com/microsoft/vscode/issues/265248) | Empty chat view after disabling copilot chat extension | 0 | visual | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 265248` |
| 207 | [#295160](https://github.com/microsoft/vscode/issues/295160) | Stuck in activating | 0 | none | 3/6 Plausible | 1 | — | — |
| 208 | [#295389](https://github.com/microsoft/vscode/issues/295389) | Opening Copilot Chat after crash leads to error. | 0 | correctness | 2/6 Unverified | 1 | — | — |
| 219 | [#303083](https://github.com/microsoft/vscode/issues/303083) | VSCode crash while using claude agent | 0 | crash | 3/6 Plausible | 1 | — | — |
| 222 | [#304703](https://github.com/microsoft/vscode/issues/304703) | Copilot causes all extensions to crash after connection drop | 0 | freeze | 3/6 Plausible | 1 | — | — |
| 228 | [#307419](https://github.com/microsoft/vscode/issues/307419) | VS Code asks to restart | 0 | freeze | 3/6 Plausible | 1 | — | — |
| 236 | [#313326](https://github.com/microsoft/vscode/issues/313326) | CoPilot, Stopped Working | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 243 | [#317190](https://github.com/microsoft/vscode/issues/317190) | "Copilot failed to get ready" | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 245 | [#317586](https://github.com/microsoft/vscode/issues/317586) | Blank | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 249 | [#320726](https://github.com/microsoft/vscode/issues/320726) | My AI FROM VS CODE  IS NOT WORKING | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 252 | [#324884](https://github.com/microsoft/vscode/issues/324884) | не работает чат | 0 | none | 3/6 Plausible | 1 | — | — |
| 254 | [#325034](https://github.com/microsoft/vscode/issues/325034) | Coplit crashing with out of memory - The window terminated unexpectedly (reason: 'oom', code: '-536870904') | 0 | crash | 3/6 Plausible | 1 | — | `npm run implement -- --issue 325034` |
| 257 | [#325489](https://github.com/microsoft/vscode/issues/325489) | not generating responses | 0 | none | 3/6 Plausible | 1 | — | — |
| 258 | [#325490](https://github.com/microsoft/vscode/issues/325490) | not generating responses | 0 | none | 3/6 Plausible | 1 | — | — |
| 259 | [#325518](https://github.com/microsoft/vscode/issues/325518) | copilot chat çalışmıyor | 0 | none | 3/6 Plausible | 1 | — | — |
| 286 | [#254332](https://github.com/microsoft/vscode/issues/254332) | hung up spinning | 0 | none | 3/6 Plausible | 0 | — | — |
| 293 | [#287579](https://github.com/microsoft/vscode/issues/287579) | Chat took too long to get ready | 0 | perf | 3/6 Plausible | 0 | — | — |
| 294 | [#287641](https://github.com/microsoft/vscode/issues/287641) | Chat took too long to get ready | 0 | none | — | 0 | — | — |
| 295 | [#287774](https://github.com/microsoft/vscode/issues/287774) | Chat took too long to get ready | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 296 | [#287810](https://github.com/microsoft/vscode/issues/287810) | Chat took too long to get ready | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 297 | [#288017](https://github.com/microsoft/vscode/issues/288017) | Chat took too long to get ready | 0 | none | 3/6 Plausible | 0 | — | — |
| 298 | [#288098](https://github.com/microsoft/vscode/issues/288098) | Chat took too long to get ready | 0 | perf | 3/6 Plausible | 0 | — | — |
| 299 | [#288099](https://github.com/microsoft/vscode/issues/288099) | Chat took too long to get ready | 0 | none | 3/6 Plausible | 0 | — | — |
| 300 | [#288525](https://github.com/microsoft/vscode/issues/288525) | Chat took too long to get ready | 0 | none | 3/6 Plausible | 0 | — | — |
| 301 | [#288543](https://github.com/microsoft/vscode/issues/288543) | Chat took too long to get ready | 0 | perf | 3/6 Plausible | 0 | — | — |
| 302 | [#288544](https://github.com/microsoft/vscode/issues/288544) | Chat took too long to get ready | 0 | perf | 3/6 Plausible | 0 | — | — |
| 303 | [#288744](https://github.com/microsoft/vscode/issues/288744) | Chat took too long to get ready | 0 | none | 3/6 Plausible | 0 | — | — |
| 304 | [#289113](https://github.com/microsoft/vscode/issues/289113) | Chat took too long to get ready | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 305 | [#289884](https://github.com/microsoft/vscode/issues/289884) | Chat took too long to get ready | 0 | perf | 3/6 Plausible | 0 | — | — |
| 308 | [#291783](https://github.com/microsoft/vscode/issues/291783) | Chat took too long to get ready | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 309 | [#291857](https://github.com/microsoft/vscode/issues/291857) | Chat took too long to get ready | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 310 | [#291858](https://github.com/microsoft/vscode/issues/291858) | Chat took too long to get ready | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 313 | [#293803](https://github.com/microsoft/vscode/issues/293803) | Silent failure | 0 | none | 3/6 Plausible | 0 | — | — |
| 315 | [#299704](https://github.com/microsoft/vscode/issues/299704) | Build failed: Copilot Chat Sanity Test timeout | 0 | correctness | — | 0 | — | `npm run implement -- --issue 299704` |
| 322 | [#301522](https://github.com/microsoft/vscode/issues/301522) | vscode use copilot chat get an error "vaildate string length" efftected can not promt. | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 335 | [#302636](https://github.com/microsoft/vscode/issues/302636) | it is showing error | 0 | none | 3/6 Plausible | 0 | — | — |
| 336 | [#302686](https://github.com/microsoft/vscode/issues/302686) | Copilot Chat is not openning on VSC | 0 | none | 3/6 Plausible | 0 | — | — |
| 353 | [#306609](https://github.com/microsoft/vscode/issues/306609) | Copilot CLI non-responsive | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 354 | [#307214](https://github.com/microsoft/vscode/issues/307214) | i have this installed and it fails to work | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 364 | [#313202](https://github.com/microsoft/vscode/issues/313202) | Chat took too long to get ready | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 369 | [#315872](https://github.com/microsoft/vscode/issues/315872) | Copilot chat stalling when invoking an agent defined in a web extension | 0 | crash | 3/6 Plausible | 0 | — | `npm run implement -- --issue 315872` |
| 403 | [#325420](https://github.com/microsoft/vscode/issues/325420) | Gihtub copilot chat not activating | 0 | none | 3/6 Plausible | 0 | — | — |

### Chat rendering (34)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 11 | [#263499](https://github.com/microsoft/vscode/issues/263499) | Split individual chat response parts to list rows | 2 | perf | 5/6 Source-confirmed | 32 | — | `npm run implement -- --issue 263499` |
| 26 | [#274099](https://github.com/microsoft/vscode/issues/274099) | Chat scrolling behavior should be improved | 1 | visual | — | 16 | — | `npm run implement -- --issue 274099` |
| 45 | [#246523](https://github.com/microsoft/vscode/issues/246523) | scroll behavior is not smooth sometimes | 6 | papercut | 6/6 Confirmed | 8 | — | `npm run implement -- --issue 246523` |
| 50 | [#289346](https://github.com/microsoft/vscode/issues/289346) | Chat markdown rendering of numbered lists is misleading | 0 | visual | 5/6 Source-confirmed | 8 | yes | `npm run implement -- --issue 289346` |
| 52 | [#292277](https://github.com/microsoft/vscode/issues/292277) | Content mismatch between Chat view and Accessible View (Alt+F2) with HTML and special characters:A11y_Visual Studio Code_Editor_Infor and relationship | 0 | correctness | 3/6 Plausible | 8 | — | `npm run implement -- --issue 292277` |
| 58 | [#282825](https://github.com/microsoft/vscode/issues/282825) | Agent sessions: Sometimes, chat input box won't let me delete characters | 0 | correctness | 3/6 Plausible | 7 | — | `npm run implement -- --issue 282825` |
| 59 | [#316501](https://github.com/microsoft/vscode/issues/316501) | [Error] unhandlederror-[DisposableResizeObserver(ChatListItemRenderer.itemHeight)] ResizeObserver loop compl... | 0 | papercut | 6/6 Confirmed | 7 | — | `npm run implement -- --issue 316501` |
| 64 | [#274428](https://github.com/microsoft/vscode/issues/274428) | Chat response: revealing the last output sometimes stuck | 0 | visual | 6/6 Confirmed | 6 | — | `npm run implement -- --issue 274428` |
| 82 | [#299296](https://github.com/microsoft/vscode/issues/299296) | Failed to render content: ModelService: Cannot add model because it already exists! | 0 | correctness | 5/6 Source-confirmed | 5 | — | `npm run implement -- --issue 299296` |
| 98 | [#303648](https://github.com/microsoft/vscode/issues/303648) | Chat renderer: subagent file edit indicator duplicated, replaces code blocks in main agent output | 0 | correctness | 2/6 Unverified | 4 | — | — |
| 100 | [#306385](https://github.com/microsoft/vscode/issues/306385) | empty code block renderings | 0 | visual | 2/6 Unverified | 4 | — | `npm run implement -- --issue 306385` |
| 105 | [#322943](https://github.com/microsoft/vscode/issues/322943) | PHP Nowdoc syntax misinterpreted when labels contain UTF8 | 0 | visual | 5/6 Source-confirmed | 4 | — | `npm run implement -- --issue 322943` |
| 111 | [#212853](https://github.com/microsoft/vscode/issues/212853) | Can't click on links in streaming chat response | 1 | papercut | 5/6 Source-confirmed | 3 | — | `npm run implement -- --issue 212853` |
| 114 | [#294965](https://github.com/microsoft/vscode/issues/294965) | Copilot Chat: code fenced example code snippet disappearing | 1 | visual | 2/6 Unverified | 3 | — | — |
| 127 | [#291169](https://github.com/microsoft/vscode/issues/291169) | Testing: Approve tool result overflows container | 0 | visual | 2/6 Unverified | 3 | — | `npm run implement -- --issue 291169` |
| 128 | [#291170](https://github.com/microsoft/vscode/issues/291170) | Testing: Subagent thinking part includes repeated text | 0 | visual | 3/6 Plausible | 3 | — | `npm run implement -- --issue 291170` |
| 129 | [#302115](https://github.com/microsoft/vscode/issues/302115) | Reloading changes image presentation | 0 | visual | 3/6 Plausible | 3 | — | `npm run implement -- --issue 302115` |
| 160 | [#300625](https://github.com/microsoft/vscode/issues/300625) | Input/output confirmation cuts off text | 0 | visual | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 300625` |
| 197 | [#248911](https://github.com/microsoft/vscode/issues/248911) | UI Flicker Observed During Image Rendering in VS Code Copilot Extension | 0 | visual | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 248911` |
| 210 | [#297248](https://github.com/microsoft/vscode/issues/297248) | Fix Duplicate Labels in GitHub Copilot Agent Selector for Plan Modes | 0 | visual | 2/6 Unverified | 1 | — | — |
| 232 | [#311917](https://github.com/microsoft/vscode/issues/311917) | [Error] potential listener LEAK — textModel / codeBlockPart (chat code block rendering) | 0 | perf | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 311917` |
| 241 | [#316371](https://github.com/microsoft/vscode/issues/316371) | The floating text covers the button, and moving your mouse slightly to the left or right causes the button to flash. | 0 | visual | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 316371` |
| 244 | [#317345](https://github.com/microsoft/vscode/issues/317345) | Bad hiding behavior of pickers in toolbar | 0 | visual | 4/6 Traced | 1 | — | `npm run implement -- --issue 317345` |
| 287 | [#258342](https://github.com/microsoft/vscode/issues/258342) | `Chat: Show Chats` command doesn't respect Chat in Editor | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 258342` |
| 288 | [#264816](https://github.com/microsoft/vscode/issues/264816) | File attachments not rendered correctly | 0 | visual | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 264816` |
| 290 | [#282923](https://github.com/microsoft/vscode/issues/282923) | Code Tab doesn't scroll up or down. | 0 | papercut | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 282923` |
| 306 | [#291172](https://github.com/microsoft/vscode/issues/291172) | Testing: Subagent list items have visually clipped focus outline | 0 | visual | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 291172` |
| 307 | [#291373](https://github.com/microsoft/vscode/issues/291373) | Chat thinking output displaying 4 backticks 'broke' chat for a second | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 291373` |
| 311 | [#292155](https://github.com/microsoft/vscode/issues/292155) | Reviewed x files appears after subagent? | 0 | visual | 3/6 Plausible | 0 | — | — |
| 326 | [#301757](https://github.com/microsoft/vscode/issues/301757) | Copilot Tool Selector Closes When Scrolling | 0 | papercut | 2/6 Unverified | 0 | — | — |
| 356 | [#309941](https://github.com/microsoft/vscode/issues/309941) | Bad chat loading rendering | 0 | visual | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 309941` |
| 360 | [#312673](https://github.com/microsoft/vscode/issues/312673) | `chatagent` language mode reports false-positive "File not found" warnings for in-page Markdown anchor links | 0 | papercut | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 312673` |
| 372 | [#316997](https://github.com/microsoft/vscode/issues/316997) | [Bug] Incomplete Sanitization in searchIntent.ts: Unescaped Backtick Breaks Markdown Table Cell in Copilot Search Results | 0 | papercut | 4/6 Traced | 0 | yes | `npm run implement -- --issue 316997` |
| 387 | [#320476](https://github.com/microsoft/vscode/issues/320476) | mermaid block in Agents Window chat renders as `[Object object]` | 0 | visual | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 320476` |

### Remote workspaces (12)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 16 | [#324081](https://github.com/microsoft/vscode/issues/324081) | Agent window SSH does not work well with keys | 3 | correctness | 3/6 Plausible | 23 | — | `npm run implement -- --issue 324081` |
| 25 | [#259754](https://github.com/microsoft/vscode/issues/259754) | Multi-Root Workspaces: glob and file search not working | 5 | correctness | 2/6 Unverified | 16 | — | — |
| 68 | [#307358](https://github.com/microsoft/vscode/issues/307358) | Copilot Chat not working in Remote-SSH | 0 | correctness | 2/6 Unverified | 6 | — | — |
| 134 | [#111143](https://github.com/microsoft/vscode/issues/111143) | Ctrl+click on `file:` link in Debug Console in devcontainer opens host filesystem instead | 1 | correctness | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 111143` |
| 137 | [#301798](https://github.com/microsoft/vscode/issues/301798) | Agent mode intermittently discards successful Claude responses after API success on Remote SSH (stop hook returns shouldContinue=false with no reason) | 1 | correctness | 3/6 Plausible | 2 | — | — |
| 147 | [#213520](https://github.com/microsoft/vscode/issues/213520) | Git - VS Code Cannot Push to Git via SSH | 0 | correctness | — | 2 | — | — |
| 368 | [#313759](https://github.com/microsoft/vscode/issues/313759) | Lost conection to device | 0 | none | — | 0 | — | — |
| 376 | [#317727](https://github.com/microsoft/vscode/issues/317727) | Agents Window requires a workspace folder to work | 0 | correctness | 2/6 Unverified | 0 | — | `npm run implement -- --issue 317727` |
| 380 | [#318604](https://github.com/microsoft/vscode/issues/318604) | AgentHost: Remote session stops updating after connection change | 0 | correctness | — | 0 | — | `npm run implement -- --issue 318604` |
| 384 | [#319929](https://github.com/microsoft/vscode/issues/319929) | Windows-style absolute paths still flagged as outside of workspace in GitHub Copilot | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 319929` |
| 393 | [#323468](https://github.com/microsoft/vscode/issues/323468) | Agents Window: Switching workspace doesn't switch branch picker | 0 | correctness | — | 0 | — | `npm run implement -- --issue 323468` |
| 397 | [#324249](https://github.com/microsoft/vscode/issues/324249) | Copilot Chat session is lost after VS Code crash only when workspace is opened via \\wsl.localhost on Windows (no Remote-WSL) | 0 | correctness | 3/6 Plausible | 0 | — | — |

### Models summarization (22)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 23 | [#286822](https://github.com/microsoft/vscode/issues/286822) | GitHub Copilot more likely to summarize converation when switching to Agent mode | 1 | correctness | 4/6 Traced | 18 | — | `npm run implement -- --issue 286822` |
| 61 | [#273185](https://github.com/microsoft/vscode/issues/273185) | Conversation History Summarization. | 1 | none | — | 6 | — | — |
| 69 | [#323641](https://github.com/microsoft/vscode/issues/323641) | Agent-mode workspace directory tree is injected ahead of the cached prefix and breaks BYOK Anthropic prompt caching | 0 | perf | 5/6 Source-confirmed | 6 | — | `npm run implement -- --issue 323641` |
| 74 | [#260188](https://github.com/microsoft/vscode/issues/260188) | Copilot Chat: chat summarization makes broken and bad edits | 1 | correctness | 6/6 Confirmed | 5 | — | `npm run implement -- --issue 260188` |
| 78 | [#264861](https://github.com/microsoft/vscode/issues/264861) | Refuses to analyse attached text files | 0 | correctness | 6/6 Confirmed | 5 | — | — |
| 92 | [#289218](https://github.com/microsoft/vscode/issues/289218) | GitHub Copilot removes custom prompt during summarization | 0 | correctness | 3/6 Plausible | 4 | — | — |
| 95 | [#299566](https://github.com/microsoft/vscode/issues/299566) | PreCompact does not trigger off of `/compact` | 0 | correctness | 5/6 Source-confirmed | 4 | — | `npm run implement -- --issue 299566` |
| 115 | [#301311](https://github.com/microsoft/vscode/issues/301311) | Copilot Chat responded in Korean to a question written in Chinese | 1 | correctness | 3/6 Plausible | 3 | — | — |
| 126 | [#288637](https://github.com/microsoft/vscode/issues/288637) | both gpt-5 and gpt5-mini remove code proposing patches | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 139 | [#316133](https://github.com/microsoft/vscode/issues/316133) | Custom subagent model allowlist/order is ignored; subagents run on Claude Sonnet 4.6 even when Sonnet is not in the configured model list | 1 | correctness | 3/6 Plausible | 2 | — | `npm run implement -- --issue 316133` |
| 140 | [#319794](https://github.com/microsoft/vscode/issues/319794) | Reasoning/thinking parameters not forwarded to extension-contributed model providers | 1 | correctness | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 319794` |
| 149 | [#264416](https://github.com/microsoft/vscode/issues/264416) | Custom instructions sometimes removed during summarization | 0 | correctness | 3/6 Plausible | 2 | — | `npm run implement -- --issue 264416` |
| 150 | [#275218](https://github.com/microsoft/vscode/issues/275218) | Anthropic BYOK leaves incomplete sentence before tool call | 0 | visual | 3/6 Plausible | 2 | — | `npm run implement -- --issue 275218` |
| 203 | [#283561](https://github.com/microsoft/vscode/issues/283561) | Tweak/disable thinking for GPT models and inline chat | 0 | correctness | 2/6 Unverified | 1 | — | `npm run implement -- --issue 283561` |
| 234 | [#313019](https://github.com/microsoft/vscode/issues/313019) | Error when using gemini api as openai compaitable provider for vscode insiders. | 0 | correctness | — | 1 | — | — |
| 248 | [#318887](https://github.com/microsoft/vscode/issues/318887) | Erro de compactação mesmo em projeto pequenoi, não executa mais nada | 0 | none | — | 1 | — | — |
| 255 | [#325149](https://github.com/microsoft/vscode/issues/325149) | Agent Mode fails with GitHub Enterprise auth - "thinking" forever / TypeError: terminated | 0 | correctness | 4/6 Traced | 1 | — | `npm run implement -- --issue 325149` |
| 337 | [#302695](https://github.com/microsoft/vscode/issues/302695) | Russian languge broke LLM | 0 | none | 3/6 Plausible | 0 | — | — |
| 344 | [#304068](https://github.com/microsoft/vscode/issues/304068) | Working with UTF-8 and languages with diacritics | 0 | none | 3/6 Plausible | 0 | — | — |
| 375 | [#317500](https://github.com/microsoft/vscode/issues/317500) | Language model per-model settings are saved to the wrong provider group when multiple groups share the same vendor | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 379 | [#318408](https://github.com/microsoft/vscode/issues/318408) | Selected model in a session isn't always preserved on Reload | 0 | correctness | 4/6 Traced | 0 | — | `npm run implement -- --issue 318408` |
| 389 | [#320716](https://github.com/microsoft/vscode/issues/320716) | Many other languages in non-sensical response from Copilot | 0 | correctness | 3/6 Plausible | 0 | — | — |

### Other (17)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 3 | [#258281](https://github.com/microsoft/vscode/issues/258281) | *Destructive* shortcut keys override standard text file operations (Ctrl+N rejects changes) | 9 | data-loss | 5/6 Source-confirmed | 69 | — | `npm run implement -- --issue 258281` |
| 22 | [#304902](https://github.com/microsoft/vscode/issues/304902) | Severe: GitHub Copilot v1.113 removes LLM embedded Markdown YAML blocks from chat output | 0 | correctness | 2/6 Unverified | 19 | — | — |
| 24 | [#312351](https://github.com/microsoft/vscode/issues/312351) | Handoff doesn't work | 5 | correctness | 3/6 Plausible | 17 | — | — |
| 79 | [#281476](https://github.com/microsoft/vscode/issues/281476) | Chat editors have mutating `editor.resource` property | 0 | correctness | 5/6 Source-confirmed | 5 | — | `npm run implement -- --issue 281476` |
| 86 | [#206854](https://github.com/microsoft/vscode/issues/206854) | Debug console is very slow with a single long line | 0 | freeze | 5/6 Source-confirmed | 4 | yes | `npm run implement -- --issue 206854` |
| 136 | [#291494](https://github.com/microsoft/vscode/issues/291494) | Chat took too long to get ready | 1 | correctness | 3/6 Plausible | 2 | — | — |
| 138 | [#302974](https://github.com/microsoft/vscode/issues/302974) | Changing Agent in new conversations overrides previous/currently running chats | 1 | correctness | 3/6 Plausible | 2 | — | — |
| 199 | [#254102](https://github.com/microsoft/vscode/issues/254102) | Missing Code suggestion in "Ask" mode while using Claude Sonnet | 0 | visual | 3/6 Plausible | 1 | — | — |
| 201 | [#270016](https://github.com/microsoft/vscode/issues/270016) | Selected launch option changes when more than one source exists and either changes | 0 | papercut | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 270016` |
| 223 | [#304901](https://github.com/microsoft/vscode/issues/304901) | Still garbage! | 0 | none | 3/6 Plausible | 1 | — | — |
| 231 | [#311599](https://github.com/microsoft/vscode/issues/311599) | issue with almost everything | 0 | none | 3/6 Plausible | 1 | — | — |
| 235 | [#313233](https://github.com/microsoft/vscode/issues/313233) | ## Bug Report: Command Prefix `/explain` Not Recognized | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 240 | [#316368](https://github.com/microsoft/vscode/issues/316368) | stop working after update | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 251 | [#323156](https://github.com/microsoft/vscode/issues/323156) | [Error] unhandlederror-Unknown LanguageModelIgnoredFileProvider | 0 | correctness | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 323156` |
| 260 | [#325664](https://github.com/microsoft/vscode/issues/325664) | "Open View" quick access: filtering by container name is case-sensitive | 0 | correctness | 5/6 Source-confirmed | 1 | — | — |
| 331 | [#302278](https://github.com/microsoft/vscode/issues/302278) | bugs | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 347 | [#304997](https://github.com/microsoft/vscode/issues/304997) | nothing happened | 0 | correctness | 3/6 Plausible | 0 | — | — |

## Feature requests

### Agent runtime (15)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | [#265496](https://github.com/microsoft/vscode/issues/265496) | Add support in vscode for Agent Client Protocol (ACP) | 324 | active | 100 | `npm run implement -- --issue 265496` |
| 2 | [#317380](https://github.com/microsoft/vscode/issues/317380) | AgentHost: WSL and Dev Containers support | 112 | active | 47 | `npm run implement -- --issue 317380` |
| 7 | [#297666](https://github.com/microsoft/vscode/issues/297666) | Add Computer Use / Desktop Automation Support to GitHub Copilot | 45 | backlog-candidate | 16 | `npm run implement -- --issue 297666` |
| 12 | [#276546](https://github.com/microsoft/vscode/issues/276546) | Keep system awake during agent actions | 33 | backlog-candidate | 10 | — |
| 13 | [#288048](https://github.com/microsoft/vscode/issues/288048) | Live Subagents Panel | 28 | backlog-candidate | 10 | `npm run implement -- --issue 288048` |
| 14 | [#288752](https://github.com/microsoft/vscode/issues/288752) | CCR should support skills | 26 | dormant | 9 | `npm run implement -- --issue 288752` |
| 40 | [#317591](https://github.com/microsoft/vscode/issues/317591) | Allow local models in Agents mode | 7 | active | 4 | — |
| 45 | [#313164](https://github.com/microsoft/vscode/issues/313164) | agents: ssh ProxyCommand | 7 | backlog-candidate | 3 | `npm run implement -- --issue 313164` |
| 77 | [#303575](https://github.com/microsoft/vscode/issues/303575) | Add install URI / deep link support for agent plugin marketplaces | 5 | active | 1 | — |
| 92 | [#286547](https://github.com/microsoft/vscode/issues/286547) | running (multiple) background agents using the copilot chat | 1 | backlog-candidate | 1 | `npm run implement -- --issue 286547` |
| 112 | [#324276](https://github.com/microsoft/vscode/issues/324276) | AgentHost: Support resuming errored sessions | 0 | active | 1 | `npm run implement -- --issue 324276` |
| 150 | [#317492](https://github.com/microsoft/vscode/issues/317492) | Introduce built-in Visual Studio agents to Visual Studio Code | 1 | active | 0 | `npm run implement -- --issue 317492` |
| 202 | [#305333](https://github.com/microsoft/vscode/issues/305333) | AHP: Cloud agent support | 0 | active | 0 | `npm run implement -- --issue 305333` |
| 223 | [#317675](https://github.com/microsoft/vscode/issues/317675) | Support Anthropic and OpenAI native skills/plugin ecosystem | 0 | active | 0 | `npm run implement -- --issue 317675` |
| 236 | [#325915](https://github.com/microsoft/vscode/issues/325915) | Feature: first-class Grok Build CLI agent in Copilot Chat (SuperGrok `grok login`, not API-key-only) | 0 | active | 0 | — |

### Chat context (20)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 3 | [#259374](https://github.com/microsoft/vscode/issues/259374) | Make Copilot Chat View searchable | 101 | backlog-candidate | 21 | `npm run implement -- --issue 259374` |
| 9 | [#260220](https://github.com/microsoft/vscode/issues/260220) | Copilot Chat: Search excludes files and folders that are in .gitignore | 42 | backlog-candidate | 13 | `npm run implement -- --issue 260220` |
| 18 | [#254027](https://github.com/microsoft/vscode/issues/254027) | Copilot chat history should support full‑text search across all chat messages, not just conversation titles | 24 | backlog-candidate | 8 | `npm run implement -- --issue 254027` |
| 19 | [#301174](https://github.com/microsoft/vscode/issues/301174) | Add #chatHistory tool `vscode-copilot-chat` so the agent can use, search, ground, get insights from prior chat sessions | 19 | active | 8 | `npm run implement -- --issue 301174` |
| 39 | [#265184](https://github.com/microsoft/vscode/issues/265184) | Support for Uploading and Analyzing More File Formats in Copilot Chat Agent (e.g., Excel, PDF) | 12 | backlog-candidate | 4 | `npm run implement -- --issue 265184` |
| 46 | [#314377](https://github.com/microsoft/vscode/issues/314377) | Chat: configurable time, weekday, and timezone in date context | 7 | backlog-candidate | 3 | `npm run implement -- --issue 314377` |
| 83 | [#251857](https://github.com/microsoft/vscode/issues/251857) | Support arbitrary URI schemes in `workbench.action.chat.attachFile` | 2 | backlog-candidate | 1 | `npm run implement -- --issue 251857` |
| 89 | [#255142](https://github.com/microsoft/vscode/issues/255142) | Allow to disable project context in ask mode | 1 | dormant | 1 | `npm run implement -- --issue 255142` |
| 90 | [#265841](https://github.com/microsoft/vscode/issues/265841) | Unable to drag image into chat prompt | 1 | backlog-candidate | 1 | `npm run implement -- --issue 265841` |
| 94 | [#317688](https://github.com/microsoft/vscode/issues/317688) | Make extension logs/output available to LLMs | 1 | backlog-candidate | 1 | `npm run implement -- --issue 317688` |
| 102 | [#259146](https://github.com/microsoft/vscode/issues/259146) | Alias @ to # in Chat input to reference context | 0 | backlog-candidate | 1 | `npm run implement -- --issue 259146` |
| 108 | [#283955](https://github.com/microsoft/vscode/issues/283955) | Allow exporting flattened view for LLM's text response and toolcall results | 0 | backlog-candidate | 1 | `npm run implement -- --issue 283955` |
| 111 | [#321103](https://github.com/microsoft/vscode/issues/321103) | Copilot Chat sends full active file even when implicit context is disabled | 0 | active | 1 | `npm run implement -- --issue 321103` |
| 181 | [#259144](https://github.com/microsoft/vscode/issues/259144) | Adding context in Chat using vscode-copilot-chat repo adds a ton of unnecessary symbols | 0 | dormant | 0 | `npm run implement -- --issue 259144` |
| 182 | [#267103](https://github.com/microsoft/vscode/issues/267103) | Copilot context-aware of recent file changes and edits | 0 | backlog-candidate | 0 | `npm run implement -- --issue 267103` |
| 184 | [#270381](https://github.com/microsoft/vscode/issues/270381) | Raise or make configurable the hard 200-result cap in Copilot’s grep_search | 0 | backlog-candidate | 0 | — |
| 194 | [#299143](https://github.com/microsoft/vscode/issues/299143) | Being able to select multi-root workspace folder in chat | 0 | backlog-candidate | 0 | `npm run implement -- --issue 299143` |
| 200 | [#303031](https://github.com/microsoft/vscode/issues/303031) | Allow Copilot Chat to scroll back and read earlier messages in the current session | 0 | active | 0 | `npm run implement -- --issue 303031` |
| 219 | [#317108](https://github.com/microsoft/vscode/issues/317108) | vscode_listCodeUsages reports incomplete results to Copilot without a mechanism to warn it the results are incomplete | 0 | active | 0 | `npm run implement -- --issue 317108` |
| 231 | [#323823](https://github.com/microsoft/vscode/issues/323823) | Ambient context in editor window sessions | 0 | active | 0 | `npm run implement -- --issue 323823` |

### Debug data views (39)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 4 | [#177733](https://github.com/microsoft/vscode/issues/177733) | Watch variable window not wrapping lines | 101 | backlog-candidate | 19 | `npm run implement -- --issue 177733` |
| 15 | [#155597](https://github.com/microsoft/vscode/issues/155597) | Allow users to choose which editor to use for editing variable binary data | 65 | backlog-candidate | 8 | — |
| 16 | [#101791](https://github.com/microsoft/vscode/issues/101791) | Allow DAP progress notifications to be shown more prominently than the status bar | 51 | backlog-candidate | 8 | `npm run implement -- --issue 101791` |
| 20 | [#61298](https://github.com/microsoft/vscode/issues/61298) | Show Timestamp while Debugging | 44 | backlog-candidate | 7 | `npm run implement -- --issue 61298` |
| 27 | [#48810](https://github.com/microsoft/vscode/issues/48810) | Does the watch view support auto completions? | 33 | backlog-candidate | 5 | `npm run implement -- --issue 48810` |
| 30 | [#236477](https://github.com/microsoft/vscode/issues/236477) | Debug: Search inside collapsed nodes | 26 | backlog-candidate | 5 | `npm run implement -- --issue 236477` |
| 36 | [#140752](https://github.com/microsoft/vscode/issues/140752) | Extension API to Access ExceptionWidget (or ZoneWidget) | 35 | backlog-candidate | 4 | — |
| 51 | [#209369](https://github.com/microsoft/vscode/issues/209369) | Disassembly window cannot be themed. | 21 | backlog-candidate | 2 | `npm run implement -- --issue 209369` |
| 52 | [#138237](https://github.com/microsoft/vscode/issues/138237) | Disassembly editor is not getting closed automatically after debug session ended | 20 | backlog-candidate | 2 | `npm run implement -- --issue 138237` |
| 58 | [#129762](https://github.com/microsoft/vscode/issues/129762) | Disassembly View: Milestone 2 | 9 | backlog-candidate | 2 | `npm run implement -- --issue 129762` |
| 68 | [#171548](https://github.com/microsoft/vscode/issues/171548) | Disassembly view: context menus | 8 | backlog-candidate | 1 | — |
| 71 | [#150161](https://github.com/microsoft/vscode/issues/150161) | Add context menu contribution point to Watch Variables Pane | 6 | backlog-candidate | 1 | — |
| 72 | [#166854](https://github.com/microsoft/vscode/issues/166854) | Drag'n'drop code in Debug Watch list | 6 | backlog-candidate | 1 | `npm run implement -- --issue 166854` |
| 78 | [#175770](https://github.com/microsoft/vscode/issues/175770) | Disassembly View: Add text field to go to specific instruction | 3 | backlog-candidate | 1 | `npm run implement -- --issue 175770` |
| 86 | [#134452](https://github.com/microsoft/vscode/issues/134452) | Support global evaluation that requires a file for context | 1 | backlog-candidate | 1 | `npm run implement -- --issue 134452` |
| 98 | [#209677](https://github.com/microsoft/vscode/issues/209677) | Inline editing of debug variables | 0 | backlog-candidate | 1 | `npm run implement -- --issue 209677` |
| 115 | [#105888](https://github.com/microsoft/vscode/issues/105888) | Line height setting consistency | 3 | backlog-candidate | 0 | `npm run implement -- --issue 105888` |
| 118 | [#110067](https://github.com/microsoft/vscode/issues/110067) | Implement Debugger Modules View | 2 | backlog-candidate | 0 | `npm run implement -- --issue 110067` |
| 119 | [#127776](https://github.com/microsoft/vscode/issues/127776) | Call stack decoration: consider using background color and not a decoration | 2 | backlog-candidate | 0 | `npm run implement -- --issue 127776` |
| 120 | [#129538](https://github.com/microsoft/vscode/issues/129538) | Disassembly view: support keyboard navigation | 2 | backlog-candidate | 0 | `npm run implement -- --issue 129538` |
| 123 | [#205821](https://github.com/microsoft/vscode/issues/205821) | Option to auto-expand groups in variables panel while debugging | 2 | backlog-candidate | 0 | `npm run implement -- --issue 205821` |
| 128 | [#140719](https://github.com/microsoft/vscode/issues/140719) | C symbol names are not displayed in the Disassembly view | 1 | backlog-candidate | 0 | `npm run implement -- --issue 140719` |
| 129 | [#148125](https://github.com/microsoft/vscode/issues/148125) | Support DAP's ValueFormat for formatting values in variables list | 1 | backlog-candidate | 0 | `npm run implement -- --issue 148125` |
| 134 | [#179742](https://github.com/microsoft/vscode/issues/179742) | Provide a global context menu to auto expand lazy variables | 1 | backlog-candidate | 0 | `npm run implement -- --issue 179742` |
| 137 | [#205142](https://github.com/microsoft/vscode/issues/205142) | usability: callstack UI should not scroll | 1 | dormant | 0 | `npm run implement -- --issue 205142` |
| 139 | [#226412](https://github.com/microsoft/vscode/issues/226412) | Watch expressions should allow LSP or debugger to remove inner whitespaces | 1 | backlog-candidate | 0 | `npm run implement -- --issue 226412` |
| 140 | [#229008](https://github.com/microsoft/vscode/issues/229008) | Adopt new call stack widget for exceptions | 1 | backlog-candidate | 0 | `npm run implement -- --issue 229008` |
| 156 | [#62277](https://github.com/microsoft/vscode/issues/62277) | Surface the 'origin and 'presentationHint' attributes of a Source in the Loaded Scripts Explorer | 0 | backlog-candidate | 0 | `npm run implement -- --issue 62277` |
| 160 | [#126694](https://github.com/microsoft/vscode/issues/126694) | Register a quickAccessProvider for debug sources | 0 | backlog-candidate | 0 | `npm run implement -- --issue 126694` |
| 166 | [#158724](https://github.com/microsoft/vscode/issues/158724) | Have UI expose data in VariablePresentationHint | 0 | backlog-candidate | 0 | `npm run implement -- --issue 158724` |
| 168 | [#163080](https://github.com/microsoft/vscode/issues/163080) | Support nesting threads in the debugger | 0 | backlog-candidate | 0 | `npm run implement -- --issue 163080` |
| 169 | [#178308](https://github.com/microsoft/vscode/issues/178308) | Debug view: Sort "Paused on ..." threads to the top | 0 | backlog-candidate | 0 | `npm run implement -- --issue 178308` |
| 171 | [#189037](https://github.com/microsoft/vscode/issues/189037) | Allow extension link detection to run on exception popups | 0 | backlog-candidate | 0 | `npm run implement -- --issue 189037` |
| 174 | [#214824](https://github.com/microsoft/vscode/issues/214824) | Debugger UX should show stack for current thread instead of a treeview with all threads | 0 | backlog-candidate | 0 | `npm run implement -- --issue 214824` |
| 176 | [#224432](https://github.com/microsoft/vscode/issues/224432) | Finalize viewcontainer menu contribution | 0 | backlog-candidate | 0 | `npm run implement -- --issue 224432` |
| 177 | [#226194](https://github.com/microsoft/vscode/issues/226194) | Scroll lists by page | 0 | backlog-candidate | 0 | `npm run implement -- --issue 226194` |
| 178 | [#227169](https://github.com/microsoft/vscode/issues/227169) | Add debug window context menu contribution points | 0 | backlog-candidate | 0 | `npm run implement -- --issue 227169` |
| 225 | [#318859](https://github.com/microsoft/vscode/issues/318859) | Don’t collapse 3rd-party stack frames (or at least not as aggressively) | 0 | active | 0 | `npm run implement -- --issue 318859` |
| 233 | [#325812](https://github.com/microsoft/vscode/issues/325812) | Cannot set value in Watch by double click | 0 | active | 0 | `npm run implement -- --issue 325812` |

### Chat sessions (17)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 5 | [#305818](https://github.com/microsoft/vscode/issues/305818) | Detect, surface, and recover orphaned Copilot Chat sessions from moved/renamed/deleted workspaces | 47 | backlog-candidate | 18 | — |
| 11 | [#301414](https://github.com/microsoft/vscode/issues/301414) | Shared Copilot Chat history across multiple workspaces/projects | 33 | backlog-candidate | 12 | `npm run implement -- --issue 301414` |
| 24 | [#324409](https://github.com/microsoft/vscode/issues/324409) | chat: make maximum persisted sessions a user-configurable setting | 11 | backlog-candidate | 6 | `npm run implement -- --issue 324409` |
| 25 | [#285106](https://github.com/microsoft/vscode/issues/285106) | Unified management for persisted Copilot Chat history across different workspace contexts | 9 | backlog-candidate | 6 | `npm run implement -- --issue 285106` |
| 44 | [#255894](https://github.com/microsoft/vscode/issues/255894) | Ability to share chat threads | 10 | backlog-candidate | 3 | `npm run implement -- --issue 255894` |
| 62 | [#261975](https://github.com/microsoft/vscode/issues/261975) | Terminals sessions should not be deleted when starting a new conversation | 2 | backlog-candidate | 2 | `npm run implement -- --issue 261975` |
| 63 | [#284013](https://github.com/microsoft/vscode/issues/284013) | Restore last chat session improvements | 0 | backlog-candidate | 2 | `npm run implement -- --issue 284013` |
| 95 | [#325504](https://github.com/microsoft/vscode/issues/325504) | Allow chats to be moved between workspaces | 1 | backlog-candidate | 1 | — |
| 96 | [#326268](https://github.com/microsoft/vscode/issues/326268) | Support import, export, and backup of Chat sessions across workspaces in VSCode Copilot | 1 | active | 1 | — |
| 148 | [#309200](https://github.com/microsoft/vscode/issues/309200) | Save and Resume Copilot Chat Sessions | 1 | active | 0 | — |
| 154 | [#322538](https://github.com/microsoft/vscode/issues/322538) | Please add a Don't ask again to the confirmation dialog when I delete a session | 1 | active | 0 | `npm run implement -- --issue 322538` |
| 183 | [#268111](https://github.com/microsoft/vscode/issues/268111) | Add API / command for showing a specific local chat session | 0 | backlog-candidate | 0 | `npm run implement -- --issue 268111` |
| 193 | [#298639](https://github.com/microsoft/vscode/issues/298639) | Agent Sessions: sessions sidebar in editor-hosted chat | 0 | active | 0 | — |
| 203 | [#306054](https://github.com/microsoft/vscode/issues/306054) | Cannot Delete Chats -- Archiving them is unnacceptable as the only option, both should be a option, and Delete should not masquerade as Archive | 0 | active | 0 | — |
| 209 | [#310621](https://github.com/microsoft/vscode/issues/310621) | Resume copilot conversation from cli into VSCode | 0 | active | 0 | `npm run implement -- --issue 310621` |
| 222 | [#317481](https://github.com/microsoft/vscode/issues/317481) | Feature Request: [Chronicle] Surface chat session titles and deep-links in standup/search output | 0 | active | 0 | `npm run implement -- --issue 317481` |
| 229 | [#319666](https://github.com/microsoft/vscode/issues/319666) | Feature Request: Add a confirmation dialog to the "Archive/Clear" button in Copilot Chat | 0 | active | 0 | — |

### Debug launch (31)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 6 | [#53557](https://github.com/microsoft/vscode/issues/53557) | Shared properties in launch.json | 149 | backlog-candidate | 16 | `npm run implement -- --issue 53557` |
| 23 | [#151299](https://github.com/microsoft/vscode/issues/151299) | Change the "Run and Debug" View's "Play" icon to a "Connect" icon when an Attach Mode Configuration is Selected | 35 | backlog-candidate | 6 | `npm run implement -- --issue 151299` |
| 26 | [#77138](https://github.com/microsoft/vscode/issues/77138) | ability to get/set currently selected debug configuration | 34 | backlog-candidate | 5 | `npm run implement -- --issue 77138` |
| 32 | [#243751](https://github.com/microsoft/vscode/issues/243751) | Add `Run Without Debug` button in `Run and Debug` Activity Bar | 26 | backlog-candidate | 5 | `npm run implement -- --issue 243751` |
| 42 | [#225483](https://github.com/microsoft/vscode/issues/225483) | Debug view per debug session | 27 | backlog-candidate | 3 | `npm run implement -- --issue 225483` |
| 49 | [#169813](https://github.com/microsoft/vscode/issues/169813) | Compound launch configuration: add abiliity to ignore preLaunchTask of launch configurations. | 22 | backlog-candidate | 2 | `npm run implement -- --issue 169813` |
| 55 | [#68123](https://github.com/microsoft/vscode/issues/68123) | Specify terminal group for integrated terminal in launch configuration | 16 | backlog-candidate | 2 | `npm run implement -- --issue 68123` |
| 56 | [#117326](https://github.com/microsoft/vscode/issues/117326) | Allow moving the floating debug.toolbar everywhere | 12 | backlog-candidate | 2 | `npm run implement -- --issue 117326` |
| 57 | [#167921](https://github.com/microsoft/vscode/issues/167921) | Debug attach - launch.json pickProcess command launches before preLaunchTask | 10 | backlog-candidate | 2 | `npm run implement -- --issue 167921` |
| 65 | [#215988](https://github.com/microsoft/vscode/issues/215988) | "Cannot set property activeDebugSession of #<Object> which has only a getter" when trying to change active debug session | 11 | backlog-candidate | 1 | `npm run implement -- --issue 215988` |
| 70 | [#207356](https://github.com/microsoft/vscode/issues/207356) | Create Compound Debug Launches Dynamically | 7 | backlog-candidate | 1 | `npm run implement -- --issue 207356` |
| 73 | [#109083](https://github.com/microsoft/vscode/issues/109083) | vscode.debug.startDebugging should support named automatic (dynamic) and global (user settings) debug configurations | 5 | dormant | 1 | `npm run implement -- --issue 109083` |
| 74 | [#132058](https://github.com/microsoft/vscode/issues/132058) | `debug.startDebugging()` can't find configuration from `.code-workspace` file | 5 | backlog-candidate | 1 | `npm run implement -- --issue 132058` |
| 75 | [#137327](https://github.com/microsoft/vscode/issues/137327) | Debugging on OSX with iTerm as external terminal creates a new window each time | 5 | backlog-candidate | 1 | `npm run implement -- --issue 137327` |
| 76 | [#165165](https://github.com/microsoft/vscode/issues/165165) | Support custom "reverse requests" from debug adapters | 5 | backlog-candidate | 1 | `npm run implement -- --issue 165165` |
| 116 | [#221595](https://github.com/microsoft/vscode/issues/221595) | Support selecting debug configuration providers using ‘when’ clause | 3 | backlog-candidate | 0 | `npm run implement -- --issue 221595` |
| 127 | [#120163](https://github.com/microsoft/vscode/issues/120163) | Debug: show welcome when while not debugging even if launch.json present | 1 | backlog-candidate | 0 | `npm run implement -- --issue 120163` |
| 131 | [#158471](https://github.com/microsoft/vscode/issues/158471) | Command to substitute variables from launch config should also get workspaceFolder as an argument | 1 | backlog-candidate | 0 | `npm run implement -- --issue 158471` |
| 132 | [#176520](https://github.com/microsoft/vscode/issues/176520) | Support debug adapter server over WebSockets (similar to DebugAdapterServer) | 1 | backlog-candidate | 0 | `npm run implement -- --issue 176520` |
| 133 | [#178138](https://github.com/microsoft/vscode/issues/178138) | Not clear how to share attribute definitions between "attach" and "launch" configurations | 1 | backlog-candidate | 0 | `npm run implement -- --issue 178138` |
| 138 | [#218897](https://github.com/microsoft/vscode/issues/218897) | Option to automatically change the debug toolbar's selected active session when launching a new debug session | 1 | dormant | 0 | `npm run implement -- --issue 218897` |
| 149 | [#310020](https://github.com/microsoft/vscode/issues/310020) | Feature Request: Allow customization of debug terminal split layout in compounds (launch.json) | 1 | backlog-candidate | 0 | — |
| 157 | [#74671](https://github.com/microsoft/vscode/issues/74671) | Allow debugger contributions to specify filenames as well as languages to be default debugger | 0 | backlog-candidate | 0 | `npm run implement -- --issue 74671` |
| 162 | [#132595](https://github.com/microsoft/vscode/issues/132595) | [Live Share: Guest initiated debugging] You don't have an extension for debugging ..... | 0 | backlog-candidate | 0 | `npm run implement -- --issue 132595` |
| 164 | [#150663](https://github.com/microsoft/vscode/issues/150663) | Continue improving "Run and Debug" experience | 0 | backlog-candidate | 0 | `npm run implement -- --issue 150663` |
| 165 | [#158575](https://github.com/microsoft/vscode/issues/158575) | Add "Disconnect single session" command | 0 | backlog-candidate | 0 | `npm run implement -- --issue 158575` |
| 173 | [#204441](https://github.com/microsoft/vscode/issues/204441) | internalConsole does not work for "attach" mode | 0 | dormant | 0 | — |
| 179 | [#230413](https://github.com/microsoft/vscode/issues/230413) | Let compound launch configs be the default | 0 | backlog-candidate | 0 | `npm run implement -- --issue 230413` |
| 210 | [#310704](https://github.com/microsoft/vscode/issues/310704) | Change colour of status bar while attached to running process when broken on exception/breakpoint | 0 | active | 0 | `npm run implement -- --issue 310704` |
| 226 | [#318896](https://github.com/microsoft/vscode/issues/318896) | Add "Debug: On Errors" | 0 | active | 0 | `npm run implement -- --issue 318896` |
| 228 | [#319193](https://github.com/microsoft/vscode/issues/319193) | Unable to change "debug.activeStackItem" | 0 | backlog-candidate | 0 | `npm run implement -- --issue 319193` |

### Breakpoints and stepping (23)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 8 | [#102236](https://github.com/microsoft/vscode/issues/102236) | Add support for SteppingGranularity in the UI | 91 | backlog-candidate | 14 | `npm run implement -- --issue 102236` |
| 22 | [#88227](https://github.com/microsoft/vscode/issues/88227) | Ability to drag and drop breakpoints | 40 | backlog-candidate | 6 | `npm run implement -- --issue 88227` |
| 29 | [#195151](https://github.com/microsoft/vscode/issues/195151) | Support Data Breakpoints across sessions | 31 | backlog-candidate | 5 | `npm run implement -- --issue 195151` |
| 43 | [#204007](https://github.com/microsoft/vscode/issues/204007) | Visual Studio Code should support 'Force Run to Cursor' | 12 | backlog-candidate | 3 | `npm run implement -- --issue 204007` |
| 48 | [#137953](https://github.com/microsoft/vscode/issues/137953) | Break all processes when one process breaks (mult-target debugging) | 26 | backlog-candidate | 2 | `npm run implement -- --issue 137953` |
| 50 | [#136792](https://github.com/microsoft/vscode/issues/136792) | Allow Run To Cursor to start debug session | 21 | backlog-candidate | 2 | — |
| 53 | [#194366](https://github.com/microsoft/vscode/issues/194366) | Applying Multiple Breakpoints to lines of code | 20 | backlog-candidate | 2 | `npm run implement -- --issue 194366` |
| 79 | [#215944](https://github.com/microsoft/vscode/issues/215944) | Breakpoint classes have no property for triggered breakpoints | 3 | backlog-candidate | 1 | `npm run implement -- --issue 215944` |
| 113 | [#153833](https://github.com/microsoft/vscode/issues/153833) | Allow (modifier)+click for "step in target" | 5 | backlog-candidate | 0 | `npm run implement -- --issue 153833` |
| 114 | [#166450](https://github.com/microsoft/vscode/issues/166450) | Debugging: Support single-thread execution requests | 4 | backlog-candidate | 0 | `npm run implement -- --issue 166450` |
| 117 | [#103330](https://github.com/microsoft/vscode/issues/103330) | Improve debug actions for multi-target debugging | 2 | backlog-candidate | 0 | `npm run implement -- --issue 103330` |
| 122 | [#189445](https://github.com/microsoft/vscode/issues/189445) | Cursor moves to breakpoint when Debug: Focus Editor On Break is turned off | 2 | dormant | 0 | `npm run implement -- --issue 189445` |
| 126 | [#111670](https://github.com/microsoft/vscode/issues/111670) | Consider adding a clear condition option | 1 | backlog-candidate | 0 | `npm run implement -- --issue 111670` |
| 135 | [#181794](https://github.com/microsoft/vscode/issues/181794) | Vscode Sets breakpoint in both sessions in multicore debugging with single Debug Configuration | 1 | backlog-candidate | 0 | `npm run implement -- --issue 181794` |
| 136 | [#204010](https://github.com/microsoft/vscode/issues/204010) | Show log-point message in decoration | 1 | backlog-candidate | 0 | `npm run implement -- --issue 204010` |
| 155 | [#21122](https://github.com/microsoft/vscode/issues/21122) | When using Run to Cursor, then there is no inline instruction pointer decoration | 0 | backlog-candidate | 0 | `npm run implement -- --issue 21122` |
| 158 | [#88158](https://github.com/microsoft/vscode/issues/88158) | Provide a way to debug extensions to hint syntax for advanced breakpoints | 0 | backlog-candidate | 0 | `npm run implement -- --issue 88158` |
| 159 | [#119481](https://github.com/microsoft/vscode/issues/119481) | Data breakpoints: support modifying current breakpoint access type | 0 | backlog-candidate | 0 | `npm run implement -- --issue 119481` |
| 161 | [#129571](https://github.com/microsoft/vscode/issues/129571) | Instruction breakpoints can not be disabled | 0 | backlog-candidate | 0 | — |
| 163 | [#135105](https://github.com/microsoft/vscode/issues/135105) | Different breakpoint marker for unverified breakpoint before debug session start | 0 | backlog-candidate | 0 | `npm run implement -- --issue 135105` |
| 167 | [#160373](https://github.com/microsoft/vscode/issues/160373) | completion on breakpoint remove all items | 0 | backlog-candidate | 0 | `npm run implement -- --issue 160373` |
| 170 | [#185814](https://github.com/microsoft/vscode/issues/185814) | Adopt `GlyphMarginWidget`s | 0 | backlog-candidate | 0 | `npm run implement -- --issue 185814` |
| 180 | [#238804](https://github.com/microsoft/vscode/issues/238804) | addBreakpoints not working for Instruction or Data breakpoints | 0 | backlog-candidate | 0 | — |

### Chat controls (22)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 10 | [#308198](https://github.com/microsoft/vscode/issues/308198) | Feature Request: Add a setting to configure the default agent (Agent/Plan/Ask) for new chat sessions | 33 | backlog-candidate | 13 | `npm run implement -- --issue 308198` |
| 47 | [#291238](https://github.com/microsoft/vscode/issues/291238) | Feature Request: Add setting to configure default chat mode | 5 | active | 3 | — |
| 64 | [#286724](https://github.com/microsoft/vscode/issues/286724) | Chat: support an action to send a chat request and clear widget | 0 | backlog-candidate | 2 | `npm run implement -- --issue 286724` |
| 81 | [#318097](https://github.com/microsoft/vscode/issues/318097) | Extension API: expose a stable public command to open the agent chat panel with a pre-filled query | 3 | backlog-candidate | 1 | `npm run implement -- --issue 318097` |
| 87 | [#251196](https://github.com/microsoft/vscode/issues/251196) | Add ⚙ icon to custom mode for editing | 1 | dormant | 1 | `npm run implement -- --issue 251196` |
| 88 | [#254679](https://github.com/microsoft/vscode/issues/254679) | Enable save participants for files during edit sessions | 1 | backlog-candidate | 1 | `npm run implement -- --issue 254679` |
| 91 | [#280648](https://github.com/microsoft/vscode/issues/280648) | Allow dragging chat editors to the chat panel | 1 | active | 1 | `npm run implement -- --issue 280648` |
| 101 | [#255124](https://github.com/microsoft/vscode/issues/255124) | Panel chat gear dropdown should have hints on hover | 0 | backlog-candidate | 1 | `npm run implement -- --issue 255124` |
| 104 | [#275616](https://github.com/microsoft/vscode/issues/275616) | Keystrokes for GitHub Copilot "Continue to iterate" prompt Continue/Pause options. | 0 | active | 1 | `npm run implement -- --issue 275616` |
| 145 | [#302363](https://github.com/microsoft/vscode/issues/302363) | [Feature Request] vscode.dev mobile-optimized view for Agent Mode supervision | 1 | active | 0 | `npm run implement -- --issue 302363` |
| 185 | [#275888](https://github.com/microsoft/vscode/issues/275888) | Let me hide Ask & Edit modes | 0 | dormant | 0 | `npm run implement -- --issue 275888` |
| 186 | [#276603](https://github.com/microsoft/vscode/issues/276603) | Clicking Try Again on a failed request should clear the error and resend the last network request to the model | 0 | backlog-candidate | 0 | `npm run implement -- --issue 276603` |
| 192 | [#292000](https://github.com/microsoft/vscode/issues/292000) | Claude Agent - Auto-expand the plan while in plan mode | 0 | backlog-candidate | 0 | `npm run implement -- --issue 292000` |
| 196 | [#301076](https://github.com/microsoft/vscode/issues/301076) | Auto-run project initialisation on first session start instead of requiring /init manually | 0 | active | 0 | `npm run implement -- --issue 301076` |
| 198 | [#301688](https://github.com/microsoft/vscode/issues/301688) | feat: display agent name in chat list (overview) | 0 | active | 0 | `npm run implement -- --issue 301688` |
| 205 | [#309209](https://github.com/microsoft/vscode/issues/309209) | Add Collapsible Copilot Chat Input (Thin Status Bar Mode) | 0 | active | 0 | — |
| 216 | [#312399](https://github.com/microsoft/vscode/issues/312399) | Add keyboard shortcut to be able to choose custom agents. | 0 | active | 0 | `npm run implement -- --issue 312399` |
| 218 | [#316946](https://github.com/microsoft/vscode/issues/316946) | [Copilot Chat] Feature request: Mobile companion experience for monitoring and refining in-progress chat / agent sessions | 0 | active | 0 | `npm run implement -- --issue 316946` |
| 220 | [#317195](https://github.com/microsoft/vscode/issues/317195) | Notify when Copilot agent sessions need attention or finish | 0 | active | 0 | `npm run implement -- --issue 317195` |
| 230 | [#320724](https://github.com/microsoft/vscode/issues/320724) | Show Current Git Branch in AI Agent Window | 0 | active | 0 | — |
| 235 | [#325830](https://github.com/microsoft/vscode/issues/325830) | Subagents UX in editor window | 0 | active | 0 | `npm run implement -- --issue 325830` |
| 237 | [#325935](https://github.com/microsoft/vscode/issues/325935) | Disable .copilot folder creation | 0 | active | 0 | `npm run implement -- --issue 325935` |

### Debug console (21)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 17 | [#201772](https://github.com/microsoft/vscode/issues/201772) | Allow "Debug Console" editors | 34 | backlog-candidate | 8 | `npm run implement -- --issue 201772` |
| 21 | [#185904](https://github.com/microsoft/vscode/issues/185904) | feature request: structured logging console | 42 | backlog-candidate | 7 | `npm run implement -- --issue 185904` |
| 28 | [#169498](https://github.com/microsoft/vscode/issues/169498) | Debug output collapsing and expading | 33 | backlog-candidate | 5 | `npm run implement -- --issue 169498` |
| 31 | [#241338](https://github.com/microsoft/vscode/issues/241338) | Allow extension to modify "Debug Console" contents | 26 | backlog-candidate | 5 | `npm run implement -- --issue 241338` |
| 33 | [#233676](https://github.com/microsoft/vscode/issues/233676) | Highlight all found text in DEBUG console | 25 | backlog-candidate | 5 | `npm run implement -- --issue 233676` |
| 34 | [#34026](https://github.com/microsoft/vscode/issues/34026) | Debug console link detection issues | 21 | backlog-candidate | 5 | `npm run implement -- --issue 34026` |
| 37 | [#94937](https://github.com/microsoft/vscode/issues/94937) | Truncate and copy large values from the debug console | 26 | backlog-candidate | 4 | `npm run implement -- --issue 94937` |
| 38 | [#202340](https://github.com/microsoft/vscode/issues/202340) | Feature: Debug console filters in settings.json | 23 | backlog-candidate | 4 | `npm run implement -- --issue 202340` |
| 54 | [#11462](https://github.com/microsoft/vscode/issues/11462) | Debug console architecture | 16 | backlog-candidate | 2 | `npm run implement -- --issue 11462` |
| 66 | [#30065](https://github.com/microsoft/vscode/issues/30065) | Language services should be able to provide debug console IntelliSense | 8 | backlog-candidate | 1 | `npm run implement -- --issue 30065` |
| 67 | [#142922](https://github.com/microsoft/vscode/issues/142922) | Debug Console Filter is a bit confusing | 8 | backlog-candidate | 1 | `npm run implement -- --issue 142922` |
| 69 | [#187784](https://github.com/microsoft/vscode/issues/187784) | No way to copy full value from debugger console (repl) | 7 | backlog-candidate | 1 | `npm run implement -- --issue 187784` |
| 82 | [#216701](https://github.com/microsoft/vscode/issues/216701) | Debug console doesn't appear on Restart (Ctrl+Shift+F5) | 2 | backlog-candidate | 1 | `npm run implement -- --issue 216701` |
| 93 | [#316090](https://github.com/microsoft/vscode/issues/316090) | Multi process logging / perf tracing | 1 | active | 1 | `npm run implement -- --issue 316090` |
| 97 | [#169798](https://github.com/microsoft/vscode/issues/169798) | When in debug REPL, tab key changes focus instead of indents | 0 | backlog-candidate | 1 | `npm run implement -- --issue 169798` |
| 121 | [#173520](https://github.com/microsoft/vscode/issues/173520) | Please Let Debug Console Consistent With Editor | 2 | backlog-candidate | 0 | `npm run implement -- --issue 173520` |
| 125 | [#100868](https://github.com/microsoft/vscode/issues/100868) | Debug console: introduce ctrl + up / down to focus output | 1 | backlog-candidate | 0 | `npm run implement -- --issue 100868` |
| 130 | [#148413](https://github.com/microsoft/vscode/issues/148413) | View multiple debug consoles side by side in editor areas | 1 | backlog-candidate | 0 | — |
| 172 | [#197803](https://github.com/microsoft/vscode/issues/197803) | debug console stylings and features, better log-row separation | 0 | dormant | 0 | `npm run implement -- --issue 197803` |
| 175 | [#220083](https://github.com/microsoft/vscode/issues/220083) | js debug chrome debug console dumps large error where in Chrome it's been truncated | 0 | backlog-candidate | 0 | — |
| 206 | [#309229](https://github.com/microsoft/vscode/issues/309229) | Allow capturing stderr from DebugAdapterExecutable and routing it to an OutputChannel | 0 | backlog-candidate | 0 | `npm run implement -- --issue 309229` |

### Tool guardrails (36)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 35 | [#263279](https://github.com/microsoft/vscode/issues/263279) | Agent Mode: Disable tools by default besides core tools | 14 | backlog-candidate | 5 | `npm run implement -- --issue 263279` |
| 80 | [#273325](https://github.com/microsoft/vscode/issues/273325) | Subagents: Limit read/write access to specific file globs | 3 | backlog-candidate | 1 | `npm run implement -- --issue 273325` |
| 99 | [#233035](https://github.com/microsoft/vscode/issues/233035) | Validate tool input in vscode | 0 | backlog-candidate | 1 | `npm run implement -- --issue 233035` |
| 100 | [#247926](https://github.com/microsoft/vscode/issues/247926) | Pass LanguageModelChat to tools | 0 | backlog-candidate | 1 | `npm run implement -- --issue 247926` |
| 103 | [#271669](https://github.com/microsoft/vscode/issues/271669) | Improve autoFix setting implementation | 0 | backlog-candidate | 1 | `npm run implement -- --issue 271669` |
| 105 | [#276145](https://github.com/microsoft/vscode/issues/276145) | Remove intent detection from agentic ask | 0 | active | 1 | `npm run implement -- --issue 276145` |
| 106 | [#280260](https://github.com/microsoft/vscode/issues/280260) | Copilot Agents Don't Install Dependencies via Proper Commands | 0 | backlog-candidate | 1 | `npm run implement -- --issue 280260` |
| 110 | [#305313](https://github.com/microsoft/vscode/issues/305313) | AHP: Tool call result confirmation | 0 | active | 1 | `npm run implement -- --issue 305313` |
| 142 | [#266397](https://github.com/microsoft/vscode/issues/266397) | Support tool calling responses for @github requests via platform agent in VSCode | 1 | backlog-candidate | 0 | `npm run implement -- --issue 266397` |
| 143 | [#283774](https://github.com/microsoft/vscode/issues/283774) | Nudge users towards new session as context gets full | 1 | dormant | 0 | `npm run implement -- --issue 283774` |
| 147 | [#307547](https://github.com/microsoft/vscode/issues/307547) | `runSubagent` tool not available to custom agents invoked as subagents (nested subagent invocation broken) | 1 | backlog-candidate | 0 | `npm run implement -- --issue 307547` |
| 151 | [#317777](https://github.com/microsoft/vscode/issues/317777) | Add "Update All Plugins" command — installed plugins have no manual update path | 1 | active | 0 | — |
| 152 | [#320745](https://github.com/microsoft/vscode/issues/320745) | Expose LM tool enabled or disabled status | 1 | active | 0 | `npm run implement -- --issue 320745` |
| 153 | [#321600](https://github.com/microsoft/vscode/issues/321600) | Github Copilot Access to Notifications | 1 | backlog-candidate | 0 | `npm run implement -- --issue 321600` |
| 187 | [#280055](https://github.com/microsoft/vscode/issues/280055) | Orchestrator "learns" to use unauthorized subAgents -> Restrict which Subagents can be used by runSubagent | 0 | backlog-candidate | 0 | — |
| 188 | [#280734](https://github.com/microsoft/vscode/issues/280734) | Allow canceling fetch call on the tool call itself | 0 | backlog-candidate | 0 | `npm run implement -- --issue 280734` |
| 189 | [#283650](https://github.com/microsoft/vscode/issues/283650) | Improve agent behavior when certain tools are disabled | 0 | backlog-candidate | 0 | `npm run implement -- --issue 283650` |
| 190 | [#284085](https://github.com/microsoft/vscode/issues/284085) | Enable runSubagent to accept user feedback | 0 | backlog-candidate | 0 | `npm run implement -- --issue 284085` |
| 191 | [#290730](https://github.com/microsoft/vscode/issues/290730) | No indication in subagent that intervention is needed | 0 | backlog-candidate | 0 | `npm run implement -- --issue 290730` |
| 195 | [#301044](https://github.com/microsoft/vscode/issues/301044) | Feature request: Add newChat option to agent handoffs and a command to invoke prompt files programmatically | 0 | active | 0 | `npm run implement -- --issue 301044` |
| 197 | [#301143](https://github.com/microsoft/vscode/issues/301143) | Title: onDidRequestToolApproval event for Chat/Language Model extensions | 0 | active | 0 | — |
| 199 | [#301697](https://github.com/microsoft/vscode/issues/301697) | GitHub Copilot - Agent Yaml - Handoff Feature Requests | 0 | active | 0 | `npm run implement -- --issue 301697` |
| 201 | [#303479](https://github.com/microsoft/vscode/issues/303479) | Looping again | 0 | active | 0 | — |
| 204 | [#308686](https://github.com/microsoft/vscode/issues/308686) | Add Agent Time/Audit Guardrails To Prevent Long Iteration Loops In Copilot Chat | 0 | backlog-candidate | 0 | `npm run implement -- --issue 308686` |
| 207 | [#310530](https://github.com/microsoft/vscode/issues/310530) | VSCode Agentic app - Choose start branch | 0 | active | 0 | `npm run implement -- --issue 310530` |
| 208 | [#310535](https://github.com/microsoft/vscode/issues/310535) | VSCode Agentic app - askquestions | 0 | active | 0 | — |
| 211 | [#310723](https://github.com/microsoft/vscode/issues/310723) | copilot: delegation mode (only final response in context) | 0 | active | 0 | `npm run implement -- --issue 310723` |
| 213 | [#311318](https://github.com/microsoft/vscode/issues/311318) | Agent ignored explicit single-terminal instruction and executed repeated multi-terminal Git command bursts | 0 | active | 0 | `npm run implement -- --issue 311318` |
| 214 | [#312289](https://github.com/microsoft/vscode/issues/312289) | chat/subagent: Provide API to control default expanded state of subagent content parts | 0 | active | 0 | `npm run implement -- --issue 312289` |
| 215 | [#312314](https://github.com/microsoft/vscode/issues/312314) | Agent Hooks dont work when Windows Powershell is restricted on workstation | 0 | active | 0 | `npm run implement -- --issue 312314` |
| 217 | [#312686](https://github.com/microsoft/vscode/issues/312686) | Copilot Chat auto-steers In Progress on new message instead of queueing to To Do | 0 | active | 0 | — |
| 224 | [#317926](https://github.com/microsoft/vscode/issues/317926) | Support pausing & resuming Copilot in agent mode | 0 | backlog-candidate | 0 | — |
| 227 | [#319113](https://github.com/microsoft/vscode/issues/319113) | Safety Report: AI Coding Extensions Lack Enforceable Guardrails — AWS Account Destroyed | 0 | active | 0 | `npm run implement -- --issue 319113` |
| 232 | [#324054](https://github.com/microsoft/vscode/issues/324054) | Copilot agent continues after file edit before user selects Keep or Undo | 0 | active | 0 | `npm run implement -- --issue 324054` |
| 238 | [#325986](https://github.com/microsoft/vscode/issues/325986) | Feedback vedr. VS Code AI – Credits og fejlrettelser | 0 | active | 0 | — |
| 239 | [#326094](https://github.com/microsoft/vscode/issues/326094) | Charging for Failed Tool Calls | 0 | active | 0 | — |

### Model settings (15)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 41 | [#295150](https://github.com/microsoft/vscode/issues/295150) | Default model for compaction | 6 | backlog-candidate | 4 | `npm run implement -- --issue 295150` |
| 59 | [#301152](https://github.com/microsoft/vscode/issues/301152) | Add `model` field to Copilot agent hook inputs | 6 | backlog-candidate | 2 | `npm run implement -- --issue 301152` |
| 60 | [#312316](https://github.com/microsoft/vscode/issues/312316) | Add model name completion with @ | 5 | active | 2 | `npm run implement -- --issue 312316` |
| 61 | [#320346](https://github.com/microsoft/vscode/issues/320346) | Allow configuring a separate (cheaper) model for context compaction (/compact) | 4 | active | 2 | — |
| 84 | [#263293](https://github.com/microsoft/vscode/issues/263293) | Change between models with hotkeys | 2 | backlog-candidate | 1 | `npm run implement -- --issue 263293` |
| 85 | [#293631](https://github.com/microsoft/vscode/issues/293631) | Add agent identifier to Copilot Chat hook parameters | 2 | active | 1 | `npm run implement -- --issue 293631` |
| 107 | [#282207](https://github.com/microsoft/vscode/issues/282207) | Specify GitHub Copilot LLM specifically for summarizing conversation history | 0 | dormant | 1 | `npm run implement -- --issue 282207` |
| 109 | [#289220](https://github.com/microsoft/vscode/issues/289220) | GitHub Copilot summarization strategy setting to truncate earliest conversation | 0 | active | 1 | — |
| 124 | [#308121](https://github.com/microsoft/vscode/issues/308121) | Support additionalContext output in PreCompact hook | 2 | active | 0 | `npm run implement -- --issue 308121` |
| 141 | [#247426](https://github.com/microsoft/vscode/issues/247426) | Feature Request: Introduce `modelDescriptionHook` for Dynamic Tool Descriptions | 1 | backlog-candidate | 0 | `npm run implement -- --issue 247426` |
| 144 | [#296469](https://github.com/microsoft/vscode/issues/296469) | Dynamic Cross-Model Agent Delegation in Copilot: Let one LLM (e.g. Claude Opus) intelligently call sub-agents on other models (Gemini, GPT, etc.) | 1 | active | 0 | `npm run implement -- --issue 296469` |
| 146 | [#302440](https://github.com/microsoft/vscode/issues/302440) | Expose conversation/session metadata (for example UUID) to custom agents, prompts, and tools | 1 | active | 0 | `npm run implement -- --issue 302440` |
| 212 | [#311035](https://github.com/microsoft/vscode/issues/311035) | We need more settings for modifying SystemPrompts and ReminderPrompts. | 0 | active | 0 | `npm run implement -- --issue 311035` |
| 221 | [#317203](https://github.com/microsoft/vscode/issues/317203) | Agents App: Show what model the subagents are using when you hover on it | 0 | active | 0 | `npm run implement -- --issue 317203` |
| 234 | [#325824](https://github.com/microsoft/vscode/issues/325824) | Support selecting different harnesses per multi-chat in the Agents window | 0 | active | 0 | `npm run implement -- --issue 325824` |
