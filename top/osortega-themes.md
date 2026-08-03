# Top issues by theme — osortega

Experimental themed view of [the flat ranking](osortega.md); themes assigned by the review engine. Rank/score are the lane-wide values. Generated 2026-08-03 15:49 UTC.

## Bugs

### Search performance (24)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | [#183480](https://github.com/microsoft/vscode/issues/183480) | "Search files by name" is slow when using remote | 48 | perf | 5/6 Source-confirmed | 100 | — | — |
| 3 | [#193927](https://github.com/microsoft/vscode/issues/193927) | Repeated searches leaves orphaned, unkillable rg processes | 9 | perf | 3/6 Plausible | 35 | — | — |
| 5 | [#305544](https://github.com/microsoft/vscode/issues/305544) | 1.113.0 regression: unbounded ripgrep processes freeze macOS when worktrees exist | 4 | freeze | 6/6 Confirmed | 23 | — | — |
| 8 | [#308315](https://github.com/microsoft/vscode/issues/308315) | High CPU usage with vscode/resources/app/node_modules/@vscode/ripgrep/bin/rg | 3 | perf | 3/6 Plausible | 16 | — | — |
| 11 | [#244376](https://github.com/microsoft/vscode/issues/244376) | node_modules\@vscode\ripgrep\bin\rg is taking a lot of resources | 2 | perf | 3/6 Plausible | 15 | — | — |
| 13 | [#322454](https://github.com/microsoft/vscode/issues/322454) | The window terminated unexpectedly reason: 'oom', code: '-536870904' | 2 | crash | 3/6 Plausible | 12 | — | — |
| 18 | [#282852](https://github.com/microsoft/vscode/issues/282852) | rg heavy disk I/O usage, rg does not like brackets and is too greedy | 1 | perf | 5/6 Source-confirmed | 10 | — | — |
| 26 | [#267441](https://github.com/microsoft/vscode/issues/267441) | The new versions 1.104 and 1.104.1 lead to CPU usage reaching 80% to 100%. | 0 | perf | 3/6 Plausible | 9 | — | — |
| 45 | [#325919](https://github.com/microsoft/vscode/issues/325919) | Agents renderer OOM: unbounded workspaceFileCount telemetry search materializes every file | 0 | crash | 5/6 Source-confirmed | 6 | yes | — |
| 50 | [#127621](https://github.com/microsoft/vscode/issues/127621) | Explore improving search performance to support high `maxResults` | 0 | perf | 5/6 Source-confirmed | 5 | — | — |
| 57 | [#98514](https://github.com/microsoft/vscode/issues/98514) | Search error: ENAMETOOLONG | 2 | correctness | 5/6 Source-confirmed | 4 | yes | — |
| 63 | [#229131](https://github.com/microsoft/vscode/issues/229131) | When I use the search function, I get stuck | 0 | perf | — | 4 | — | — |
| 65 | [#261428](https://github.com/microsoft/vscode/issues/261428) | Memory Leak in File Search (Ctrl+P) with Large Projects (1M+ Files) | 0 | perf | 4/6 Traced | 4 | — | — |
| 109 | [#234314](https://github.com/microsoft/vscode/issues/234314) | Find & Replace in Files => Very Slow on Mac | 1 | perf | 3/6 Plausible | 2 | — | — |
| 151 | [#224248](https://github.com/microsoft/vscode/issues/224248) | search error | 0 | correctness | 5/6 Source-confirmed | 1 | yes | — |
| 155 | [#239280](https://github.com/microsoft/vscode/issues/239280) | Search progress goes forever after pasting a large string into search view | 0 | visual | 5/6 Source-confirmed | 1 | — | — |
| 173 | [#307001](https://github.com/microsoft/vscode/issues/307001) | High CPU usage: Infinite loop of rg (ripgrep) processes spawned when opening a folder with square brackets [] in its name | 0 | freeze | 3/6 Plausible | 1 | — | — |
| 174 | [#307429](https://github.com/microsoft/vscode/issues/307429) | certain regexp became really really slow in the newest version | 0 | none | 3/6 Plausible | 1 | — | — |
| 181 | [#320819](https://github.com/microsoft/vscode/issues/320819) | VSCode RG.exe verses VSCode Insiders RG activity | 0 | perf | 3/6 Plausible | 1 | — | — |
| 193 | [#166390](https://github.com/microsoft/vscode/issues/166390) | Sluggish scrolling in search view when there are many results in one file | 0 | freeze | 5/6 Source-confirmed | 0 | — | — |
| 249 | [#287711](https://github.com/microsoft/vscode/issues/287711) | Searching leads to - "System error occured (ENAMETOOLONG spawn)" | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 277 | [#303718](https://github.com/microsoft/vscode/issues/303718) | When there are too many issues, after entering text to search, it gets stuck on this interface | 0 | freeze | 3/6 Plausible | 0 | — | — |
| 323 | [#321737](https://github.com/microsoft/vscode/issues/321737) | Quick search (%) is sluggish during typing | 0 | perf | 4/6 Traced | 0 | yes | — |
| 349 | [#327682](https://github.com/microsoft/vscode/issues/327682) | Cancelled ripgrep text searches can remain pending indefinitely waiting for child process close | 0 | freeze | 5/6 Source-confirmed | 0 | — | — |

### Search replace (18)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2 | [#20467](https://github.com/microsoft/vscode/issues/20467) | search in files focus resets when line changed | 49 | correctness | 6/6 Confirmed | 50 | — | — |
| 28 | [#282773](https://github.com/microsoft/vscode/issues/282773) | Search / Replace does not work if I use undo and try again | 0 | correctness | 5/6 Source-confirmed | 9 | yes | — |
| 80 | [#166437](https://github.com/microsoft/vscode/issues/166437) | Replace in files is buggy when multiple changes are made on same line of code | 1 | correctness | 5/6 Source-confirmed | 3 | yes | — |
| 89 | [#248209](https://github.com/microsoft/vscode/issues/248209) | Search Replace: Cursor does not move to next match when replace string starts with a newline followed by search string | 0 | correctness | 5/6 Source-confirmed | 3 | yes | — |
| 108 | [#181000](https://github.com/microsoft/vscode/issues/181000) | Search & Replace is behaving strange for readonly files | 1 | correctness | 5/6 Source-confirmed | 2 | yes | — |
| 130 | [#291979](https://github.com/microsoft/vscode/issues/291979) | [BUG] Replace count in the Search panel is wrong | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 137 | [#48063](https://github.com/microsoft/vscode/issues/48063) | Search and replace across files corrupts files with CR line endings | 1 | correctness | 5/6 Source-confirmed | 1 | — | — |
| 146 | [#196684](https://github.com/microsoft/vscode/issues/196684) | Specific inputs cause replacing single instance in Search View to skip selection past the next instance | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 159 | [#259650](https://github.com/microsoft/vscode/issues/259650) | Search and replace across files scrolls poorly | 0 | papercut | 4/6 Traced | 1 | — | — |
| 187 | [#107806](https://github.com/microsoft/vscode/issues/107806) | New search results cleared after search-and-replace operation finishes | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 188 | [#153522](https://github.com/microsoft/vscode/issues/153522) | Replacing with capture groups writes the first match's values to all matches in that line | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 192 | [#164929](https://github.com/microsoft/vscode/issues/164929) | Search & Replace exclude deleted files by default | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 194 | [#166635](https://github.com/microsoft/vscode/issues/166635) | Undo search/replace leaves 'replace all' button greyed | 0 | papercut | 5/6 Source-confirmed | 0 | — | — |
| 202 | [#184081](https://github.com/microsoft/vscode/issues/184081) | Disable global replace all if all files are readonly | 0 | papercut | 5/6 Source-confirmed | 0 | yes | — |
| 211 | [#197278](https://github.com/microsoft/vscode/issues/197278) | `replaceActive` context key is not set | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 213 | [#201045](https://github.com/microsoft/vscode/issues/201045) | Replace in files global command should move focus | 0 | papercut | 5/6 Source-confirmed | 0 | yes | — |
| 232 | [#233418](https://github.com/microsoft/vscode/issues/233418) | File Search/Replace replacing multiple times (incorrectly) when double-clicking | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 319 | [#320370](https://github.com/microsoft/vscode/issues/320370) | Global Find and Replace，Replace error without open file editor | 0 | none | 3/6 Plausible | 0 | — | — |

### Session lifecycle (55)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 4 | [#283514](https://github.com/microsoft/vscode/issues/283514) | Allow to rename local chat sessions | 1 | correctness | 6/6 Confirmed | 24 | — | — |
| 15 | [#319416](https://github.com/microsoft/vscode/issues/319416) | Chat sessions disappear from sidebar list when switching between them | 2 | visual | 6/6 Confirmed | 11 | — | — |
| 19 | [#309663](https://github.com/microsoft/vscode/issues/309663) | Agents: New cloud session disappears | 1 | correctness | 6/6 Confirmed | 10 | — | — |
| 21 | [#288269](https://github.com/microsoft/vscode/issues/288269) | Incorrect `Sessions in progress` | 0 | correctness | 3/6 Plausible | 10 | — | — |
| 30 | [#317807](https://github.com/microsoft/vscode/issues/317807) | Copilot sessions missing | 2 | correctness | 3/6 Plausible | 8 | — | — |
| 32 | [#327639](https://github.com/microsoft/vscode/issues/327639) | Agent Sessions sidebar: per-session status freezes for Copilot CLI sessions (both directions); mark-as-read and rename inert | 1 | correctness | 6/6 Confirmed | 8 | — | — |
| 34 | [#294822](https://github.com/microsoft/vscode/issues/294822) | GitHub Copilot Chat History Not Saving in Specific Project | 0 | correctness | 3/6 Plausible | 8 | — | — |
| 44 | [#284230](https://github.com/microsoft/vscode/issues/284230) | Agent sessions keeps asking for input even when not needed after restart | 0 | correctness | 5/6 Source-confirmed | 6 | — | — |
| 46 | [#316994](https://github.com/microsoft/vscode/issues/316994) | Copilot Chat title rename reverts | 3 | papercut | 4/6 Traced | 5 | yes | — |
| 49 | [#313334](https://github.com/microsoft/vscode/issues/313334) | Unable to Rename Copilot Discussions | 1 | correctness | 6/6 Confirmed | 5 | — | — |
| 66 | [#281521](https://github.com/microsoft/vscode/issues/281521) | Copilot status bar hover flickers while agent is running | 0 | visual | 2/6 Unverified | 4 | — | — |
| 67 | [#281655](https://github.com/microsoft/vscode/issues/281655) | Agent Sessions: onDidChangeChatSessionItems not firing on refresh | 0 | perf | 2/6 Unverified | 4 | — | — |
| 68 | [#288297](https://github.com/microsoft/vscode/issues/288297) | Chat sessions shows duplicated cloud session | 0 | visual | 3/6 Plausible | 4 | — | — |
| 71 | [#291426](https://github.com/microsoft/vscode/issues/291426) | Codex sessions still appear in sessions list after uninstalling Codex | 0 | correctness | 5/6 Source-confirmed | 4 | — | — |
| 74 | [#328188](https://github.com/microsoft/vscode/issues/328188) | Local chat session missing from Sessions list after Windows restart | 0 | correctness | 5/6 Source-confirmed | 4 | — | — |
| 75 | [#328357](https://github.com/microsoft/vscode/issues/328357) | Agent session is gone | 0 | correctness | 3/6 Plausible | 4 | — | — |
| 82 | [#311256](https://github.com/microsoft/vscode/issues/311256) | Archiving and unarchiving session breaks it | 1 | correctness | 5/6 Source-confirmed | 3 | — | — |
| 100 | [#282726](https://github.com/microsoft/vscode/issues/282726) | Agent session says it's in progress when it's not | 0 | visual | 2/6 Unverified | 3 | — | — |
| 106 | [#325403](https://github.com/microsoft/vscode/issues/325403) | Chat session suddenly missing and failed | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 125 | [#280459](https://github.com/microsoft/vscode/issues/280459) | Long description for local session | 0 | visual | 3/6 Plausible | 2 | — | — |
| 166 | [#286093](https://github.com/microsoft/vscode/issues/286093) | Agent sessions - recent list update before session is loaded | 0 | visual | 6/6 Confirmed | 1 | — | — |
| 167 | [#286117](https://github.com/microsoft/vscode/issues/286117) | Cloud sessions often do not appear for me (multi root workspace) | 0 | papercut | 3/6 Plausible | 1 | — | — |
| 168 | [#288430](https://github.com/microsoft/vscode/issues/288430) | Two unread session for one remove session | 0 | visual | 3/6 Plausible | 1 | — | — |
| 169 | [#289908](https://github.com/microsoft/vscode/issues/289908) | Cloud sessions show the wrong follow up messages in chat | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 180 | [#319948](https://github.com/microsoft/vscode/issues/319948) | Renaming a CLI-originated session in chat history causes it to disappear | 0 | correctness | 6/6 Confirmed | 1 | — | — |
| 183 | [#327029](https://github.com/microsoft/vscode/issues/327029) | Agents window: sessions hang silently mid-turn, no error (subagent deselection stall / unanswered permission prompts) | 0 | freeze | 2/6 Unverified | 1 | — | — |
| 250 | [#288122](https://github.com/microsoft/vscode/issues/288122) | Session Initializing… message won't dissappear from VSC UI for abandoned job | 0 | visual | 4/6 Traced | 0 | — | — |
| 255 | [#289391](https://github.com/microsoft/vscode/issues/289391) | Chat session name is way off | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 257 | [#289914](https://github.com/microsoft/vscode/issues/289914) | Cloud chat sessions show duplicated messages | 0 | visual | 2/6 Unverified | 0 | — | — |
| 261 | [#291015](https://github.com/microsoft/vscode/issues/291015) | Sessions do not load in agent-sessions welcome view without internet | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 263 | [#291060](https://github.com/microsoft/vscode/issues/291060) | Sessions list does not seem to be keyboard accessible | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 265 | [#291161](https://github.com/microsoft/vscode/issues/291161) | Agent sessions filtering is very annoying when filtering multiple providers | 0 | papercut | — | 0 | — | — |
| 269 | [#292776](https://github.com/microsoft/vscode/issues/292776) | Incorrect previous cloud session is opened after delegation | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 278 | [#304855](https://github.com/microsoft/vscode/issues/304855) | Sessions: Local folder unexpectedly added to list after interacting with cloud sessions | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 279 | [#307760](https://github.com/microsoft/vscode/issues/307760) | Archiving sessions in slow | 0 | perf | 5/6 Source-confirmed | 0 | — | — |
| 298 | [#314983](https://github.com/microsoft/vscode/issues/314983) | Chat attachments break when switchin sessions | 0 | correctness | — | 0 | — | — |
| 299 | [#316345](https://github.com/microsoft/vscode/issues/316345) | Session records that cannot be deleted come from codex and claude code plug-ins. | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 304 | [#316984](https://github.com/microsoft/vscode/issues/316984) | Sessions sections are missing expansion state indication | 0 | visual | 5/6 Source-confirmed | 0 | yes | — |
| 310 | [#317475](https://github.com/microsoft/vscode/issues/317475) | Detached Copilot/Agent sessions persist after clearing all storage | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 317 | [#319930](https://github.com/microsoft/vscode/issues/319930) | Global chat session list missing sessions | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 318 | [#319946](https://github.com/microsoft/vscode/issues/319946) | synced sessions not appearing on my other machine | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 321 | [#321483](https://github.com/microsoft/vscode/issues/321483) | Agents sessions -- code review (ccr?) seem to show as new sessions | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 325 | [#322009](https://github.com/microsoft/vscode/issues/322009) | Chats in history might change order and seem to (or truly) disappear and reappear | 0 | visual | 4/6 Traced | 0 | — | — |
| 329 | [#323126](https://github.com/microsoft/vscode/issues/323126) | Dragging in the sessions list says attach file as context | 0 | visual | 4/6 Traced | 0 | — | — |
| 330 | [#323144](https://github.com/microsoft/vscode/issues/323144) | Sessions: folders[0].gitRepository access throws TypeError when a session workspace has no folders | 0 | crash | 5/6 Source-confirmed | 0 | — | — |
| 331 | [#323226](https://github.com/microsoft/vscode/issues/323226) | High idle CPU: PR-icon model thrash in Chat Sessions list (create/dispose churn) | 0 | perf | — | 0 | — | — |
| 335 | [#323525](https://github.com/microsoft/vscode/issues/323525) | overly aggressive matching for searching chat sessions | 0 | visual | 4/6 Traced | 0 | — | — |
| 337 | [#323877](https://github.com/microsoft/vscode/issues/323877) | GitHub Copilot Chat Session history Doesn't Appear on First Switch | 0 | none | 3/6 Plausible | 0 | — | — |
| 340 | [#325448](https://github.com/microsoft/vscode/issues/325448) | Session disappears from pinned list, then reappears randomly | 0 | visual | 6/6 Confirmed | 0 | — | — |
| 341 | [#326026](https://github.com/microsoft/vscode/issues/326026) | Pinned Chats section doesn't exist after pinning first chat in Agents window until reload | 0 | correctness | — | 0 | — | — |
| 343 | [#326599](https://github.com/microsoft/vscode/issues/326599) | Agents mode: sessions get "stuck" and session history renders blank when switching between sessions | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 345 | [#327073](https://github.com/microsoft/vscode/issues/327073) | Chat Sessions panel: multi-select + Delete only removes one session instead of all selected | 0 | correctness | — | 0 | — | — |
| 348 | [#327611](https://github.com/microsoft/vscode/issues/327611) | Duplicate entries for cloud sessions | 0 | papercut | 6/6 Confirmed | 0 | — | — |
| 350 | [#327977](https://github.com/microsoft/vscode/issues/327977) | GitHub Copilot big issue | 0 | papercut | 5/6 Source-confirmed | 0 | — | — |
| 352 | [#328370](https://github.com/microsoft/vscode/issues/328370) | Chat history items do not take the max width of the chat into account | 0 | visual | 5/6 Source-confirmed | 0 | — | — |

### Search scope (33)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 7 | [#169017](https://github.com/microsoft/vscode/issues/169017) | `search.maxResults` does not affect how many results are found/highlighted | 17 | correctness | 5/6 Source-confirmed | 16 | — | — |
| 9 | [#249197](https://github.com/microsoft/vscode/issues/249197) | findFiles doesn't find newly added files in a virtual workspace | 2 | correctness | 6/6 Confirmed | 16 | — | — |
| 10 | [#328102](https://github.com/microsoft/vscode/issues/328102) | `grep_search.includePattern` still silently fails for backslash workspace-root prefixes on Windows | 0 | correctness | 5/6 Source-confirmed | 16 | — | — |
| 14 | [#328287](https://github.com/microsoft/vscode/issues/328287) | GitHub Copilot `grep_search` returns files outside `includePattern` when they are open in an editor | 0 | correctness | 5/6 Source-confirmed | 12 | yes | — |
| 24 | [#319364](https://github.com/microsoft/vscode/issues/319364) | Workspace search "files to include" always filters to "Only search in open editors" regardless of selection | 2 | correctness | 3/6 Plausible | 9 | — | — |
| 29 | [#328292](https://github.com/microsoft/vscode/issues/328292) | GitHub Copilot `file_search` and `grep_search` support an undocumented workspace-folder-name scope prefix, and reject a wrong one silently | 0 | correctness | 5/6 Source-confirmed | 9 | — | — |
| 41 | [#179203](https://github.com/microsoft/vscode/issues/179203) | vscode.workspace.findFiles returns nothing if executed early in extension startup | 2 | correctness | 5/6 Source-confirmed | 6 | — | — |
| 42 | [#277714](https://github.com/microsoft/vscode/issues/277714) | Global search doesn't always look in open editors anymore | 2 | correctness | 3/6 Plausible | 6 | — | — |
| 47 | [#249859](https://github.com/microsoft/vscode/issues/249859) | VS Code Search Shows Results from Files of a Previous Git Branch | 2 | correctness | 3/6 Plausible | 5 | — | — |
| 48 | [#243533](https://github.com/microsoft/vscode/issues/243533) | Search results appear for excluded files when file is opened | 1 | correctness | 5/6 Source-confirmed | 5 | yes | — |
| 95 | [#273517](https://github.com/microsoft/vscode/issues/273517) | In a multi-folder project, if a folder name contains glob characters, it cannot be added to the Include/Exclude list. | 0 | correctness | 5/6 Source-confirmed | 3 | — | — |
| 96 | [#275007](https://github.com/microsoft/vscode/issues/275007) | "files to include" doesn't work with folder names containing glob characters | 0 | correctness | 5/6 Source-confirmed | 3 | — | — |
| 107 | [#194701](https://github.com/microsoft/vscode/issues/194701) | Search fails in folders having curly brackets groups in folder name (ie. '/{{cookiecutter.package_name}}') | 2 | correctness | 5/6 Source-confirmed | 2 | yes | — |
| 110 | [#252509](https://github.com/microsoft/vscode/issues/252509) | Search only in Open Editors issue | 1 | correctness | 5/6 Source-confirmed | 2 | yes | — |
| 112 | [#287097](https://github.com/microsoft/vscode/issues/287097) | Search does not work in workspaces having names | 1 | correctness | 5/6 Source-confirmed | 2 | yes | — |
| 117 | [#232482](https://github.com/microsoft/vscode/issues/232482) | Search does not find pattern in closed files | 0 | correctness | 5/6 Source-confirmed | 2 | — | — |
| 121 | [#250750](https://github.com/microsoft/vscode/issues/250750) | Search not always searching in open files outside of work folder | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 136 | [#326577](https://github.com/microsoft/vscode/issues/326577) | Searching in files in WSL does not work generally | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 144 | [#192995](https://github.com/microsoft/vscode/issues/192995) | Search path multiple patterns not working | 0 | correctness | 5/6 Source-confirmed | 1 | yes | — |
| 161 | [#263244](https://github.com/microsoft/vscode/issues/263244) | "Workspace folder does not exist: ." if trailing "." in "files to exclude" | 0 | papercut | 5/6 Source-confirmed | 1 | — | — |
| 197 | [#175063](https://github.com/microsoft/vscode/issues/175063) | Search results come from all the folders in the workspace when the `files to include` is an aliased folder | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 208 | [#189359](https://github.com/microsoft/vscode/issues/189359) | search results return much less than search.maxResults with sibling clause | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 217 | [#210850](https://github.com/microsoft/vscode/issues/210850) | `Searn only in Opened Editors` and `files to include` doesn't support filename with special characters | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 220 | [#214274](https://github.com/microsoft/vscode/issues/214274) | `baseUri` of `exclude` in `findTextInFiles` and `findFiles2` is ignored | 0 | correctness | 4/6 Traced | 0 | — | — |
| 230 | [#226861](https://github.com/microsoft/vscode/issues/226861) | `vscode.ExcludeSettingOptions.None` does not seem to work | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 231 | [#227026](https://github.com/microsoft/vscode/issues/227026) | Infinite loading when filesystem has no registered provider | 0 | freeze | 5/6 Source-confirmed | 0 | yes | — |
| 233 | [#234206](https://github.com/microsoft/vscode/issues/234206) | github.dev search options no longer work | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 239 | [#260035](https://github.com/microsoft/vscode/issues/260035) | Search not working on in-memory file systems | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 242 | [#265630](https://github.com/microsoft/vscode/issues/265630) | File Search does not work when using the cache with glob patterns and sortByScore | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 251 | [#288522](https://github.com/microsoft/vscode/issues/288522) | Search only searches files that were recently opened, not all opened files | 0 | none | 3/6 Plausible | 0 | — | — |
| 333 | [#323391](https://github.com/microsoft/vscode/issues/323391) | Search "Files to Include" behaves incorrectly when workspace root and nested file patterns are specified together | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 334 | [#323505](https://github.com/microsoft/vscode/issues/323505) | Search in folder does not work | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 347 | [#327468](https://github.com/microsoft/vscode/issues/327468) | ADO code-search endpoint override is workspace-scoped while authenticated requests use it | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |

### Agent welcome (39)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 16 | [#290922](https://github.com/microsoft/vscode/issues/290922) | Can't use back button after creating agent session from welcome | 0 | correctness | 2/6 Unverified | 11 | — | — |
| 17 | [#293270](https://github.com/microsoft/vscode/issues/293270) | Back behavior in new welcome session is unexpected | 0 | correctness | 3/6 Plausible | 11 | — | — |
| 22 | [#290989](https://github.com/microsoft/vscode/issues/290989) | Picking a folder in a welcome view does not work the second time | 0 | correctness | 3/6 Plausible | 10 | — | — |
| 36 | [#308101](https://github.com/microsoft/vscode/issues/308101) | command-p "agent " cancels out of file search, pulls up agent commands | 2 | correctness | 5/6 Source-confirmed | 7 | — | — |
| 38 | [#290965](https://github.com/microsoft/vscode/issues/290965) | Several weird things when opening welcome view after having been in a chat | 1 | correctness | 6/6 Confirmed | 7 | — | — |
| 70 | [#290154](https://github.com/microsoft/vscode/issues/290154) | Smoke test failures related to agent sessions welcome | 0 | correctness | 2/6 Unverified | 4 | — | — |
| 72 | [#295863](https://github.com/microsoft/vscode/issues/295863) | Welcome page and chat open one first open | 0 | visual | 3/6 Plausible | 4 | — | — |
| 93 | [#261493](https://github.com/microsoft/vscode/issues/261493) | Chat in Editor should have same background as chat in panel | 0 | visual | 5/6 Source-confirmed | 3 | — | — |
| 102 | [#292571](https://github.com/microsoft/vscode/issues/292571) | Installing extension auto closes welcome page | 0 | papercut | 5/6 Source-confirmed | 3 | yes | — |
| 103 | [#296783](https://github.com/microsoft/vscode/issues/296783) | Welcome Page: The "Other Models" menu renders incorrectly the first time you open it | 0 | visual | 3/6 Plausible | 3 | — | — |
| 113 | [#291110](https://github.com/microsoft/vscode/issues/291110) | 'codex' should be hidden as chat target in welcome view | 1 | correctness | 4/6 Traced | 2 | — | — |
| 128 | [#291149](https://github.com/microsoft/vscode/issues/291149) | Agent Sessions Welcome View stealing focus | 0 | papercut | 3/6 Plausible | 2 | — | — |
| 131 | [#297752](https://github.com/microsoft/vscode/issues/297752) | Copilot Chat Plan Mode: Questions Not Rendered and Stuck State (Renderer Error) | 0 | correctness | 6/6 Confirmed | 2 | — | — |
| 171 | [#292980](https://github.com/microsoft/vscode/issues/292980) | Welcome tab shows only background sessions when opening new window | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 244 | [#281344](https://github.com/microsoft/vscode/issues/281344) | `View Extension` cutoff when hovering over `Cloud Agent` title in chat output | 0 | visual | 3/6 Plausible | 0 | — | — |
| 245 | [#284196](https://github.com/microsoft/vscode/issues/284196) | Implementing a plan leads to unhelpful session title | 0 | papercut | 2/6 Unverified | 0 | — | — |
| 258 | [#290941](https://github.com/microsoft/vscode/issues/290941) | Jank in options when switching modes (welcome or iput) | 0 | visual | 3/6 Plausible | 0 | — | — |
| 259 | [#290961](https://github.com/microsoft/vscode/issues/290961) | Skeleton view doesnt show on new welcome | 0 | visual | 2/6 Unverified | 0 | — | — |
| 260 | [#290998](https://github.com/microsoft/vscode/issues/290998) | Agent Session Welcome: Product name header wrapped with overlap after resizing | 0 | visual | 2/6 Unverified | 0 | — | — |
| 262 | [#291054](https://github.com/microsoft/vscode/issues/291054) | Opening model picker doesn't restore chat view | 0 | visual | 3/6 Plausible | 0 | — | — |
| 266 | [#291457](https://github.com/microsoft/vscode/issues/291457) | Welcome view closes my MRU picker | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 267 | [#291508](https://github.com/microsoft/vscode/issues/291508) | [Unhandled Error] Cannot read properties of undefined (reading 'length') | 0 | crash | 3/6 Plausible | 0 | — | — |
| 268 | [#291610](https://github.com/microsoft/vscode/issues/291610) | Dropdowns in welcome arent sticky if you navigate away | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 271 | [#293048](https://github.com/microsoft/vscode/issues/293048) | Agent-sessions view unexpected views/UI | 0 | visual | 3/6 Plausible | 0 | — | — |
| 274 | [#297805](https://github.com/microsoft/vscode/issues/297805) | Using chat welcome view: "Measuring item node that is not in DOM!" | 0 | visual | 5/6 Source-confirmed | 0 | — | — |
| 275 | [#298158](https://github.com/microsoft/vscode/issues/298158) | Cannot drag and drop folders into prompt area in welcome page | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 280 | [#308936](https://github.com/microsoft/vscode/issues/308936) | Agents app errors | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 281 | [#308944](https://github.com/microsoft/vscode/issues/308944) | Unable to use Copilot/Local in multiple Chat Editors | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 282 | [#309620](https://github.com/microsoft/vscode/issues/309620) | Agents: initial session list focus shows no indication | 0 | visual | 2/6 Unverified | 0 | — | — |
| 283 | [#309621](https://github.com/microsoft/vscode/issues/309621) | Find session flow is really not accessible | 0 | papercut | 5/6 Source-confirmed | 0 | — | — |
| 284 | [#311994](https://github.com/microsoft/vscode/issues/311994) | Agents: File attachment is rendered as plain text once session starts | 0 | visual | 3/6 Plausible | 0 | — | — |
| 300 | [#316954](https://github.com/microsoft/vscode/issues/316954) | Empty workspace picker drop-down | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 301 | [#316955](https://github.com/microsoft/vscode/issues/316955) | Files view not updated when switching workspace for new session | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 312 | [#318423](https://github.com/microsoft/vscode/issues/318423) | "with" button in agents view broken | 0 | papercut | 6/6 Confirmed | 0 | — | — |
| 313 | [#318775](https://github.com/microsoft/vscode/issues/318775) | Cursor focus stays in editor when actually in sidebar (Holding ctrl to remove word) | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 327 | [#322393](https://github.com/microsoft/vscode/issues/322393) | Chat Session Approvals: Moving mouse to click on approval button in a pop-over removes the pop-over | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 332 | [#323245](https://github.com/microsoft/vscode/issues/323245) | Clicking editor in split view scrolls far away | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 344 | [#326911](https://github.com/microsoft/vscode/issues/326911) | language mode becomes invalid | 0 | none | 3/6 Plausible | 0 | — | — |
| 354 | [#328507](https://github.com/microsoft/vscode/issues/328507) | Chat scroll indicator doesn't go to short last message | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |

### Cloud agents (39)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 20 | [#277335](https://github.com/microsoft/vscode/issues/277335) | 403 from cloud agent | 0 | correctness | 3/6 Plausible | 10 | — | — |
| 27 | [#274647](https://github.com/microsoft/vscode/issues/274647) | Chat: Delegate to agent ignores attached plan document | 0 | correctness | 3/6 Plausible | 9 | — | — |
| 37 | [#316690](https://github.com/microsoft/vscode/issues/316690) | Agents: Sessions fail to create | 2 | correctness | 2/6 Unverified | 7 | — | — |
| 69 | [#289769](https://github.com/microsoft/vscode/issues/289769) | Cloud agent does not create PR in correct repository | 0 | correctness | 3/6 Plausible | 4 | — | — |
| 73 | [#316979](https://github.com/microsoft/vscode/issues/316979) | No Host after disconnecting from tunnel | 0 | correctness | 6/6 Confirmed | 4 | — | — |
| 79 | [#282283](https://github.com/microsoft/vscode/issues/282283) | Background agent assignment failed | 2 | correctness | 3/6 Plausible | 3 | — | — |
| 92 | [#259724](https://github.com/microsoft/vscode/issues/259724) | Coding agent integration tries to create changes on a PR that doesn't exist | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 99 | [#282671](https://github.com/microsoft/vscode/issues/282671) | Background agent shows changed file two times | 0 | visual | 2/6 Unverified | 3 | — | — |
| 101 | [#285363](https://github.com/microsoft/vscode/issues/285363) | Migrating changes infinite loop | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 104 | [#324539](https://github.com/microsoft/vscode/issues/324539) | agents: New Chat lags then hangs | 0 | freeze | 6/6 Confirmed | 3 | — | — |
| 105 | [#324957](https://github.com/microsoft/vscode/issues/324957) | [Regression] [Error] unhandlederror-Sign in to GitHub to use the Cloud Agent. | 0 | correctness | 5/6 Source-confirmed | 3 | — | — |
| 126 | [#281361](https://github.com/microsoft/vscode/issues/281361) | Mismatch in background agent changed file count after migrating changes to worktree | 0 | visual | 3/6 Plausible | 2 | — | — |
| 127 | [#282672](https://github.com/microsoft/vscode/issues/282672) | Changed file from background agent show with full file path | 0 | visual | 3/6 Plausible | 2 | — | — |
| 132 | [#316967](https://github.com/microsoft/vscode/issues/316967) | Session didn't detect the tunnel going offline | 0 | correctness | 6/6 Confirmed | 2 | — | — |
| 133 | [#317089](https://github.com/microsoft/vscode/issues/317089) | Agents app shouldn't show any input until there is definitely a host | 0 | visual | 3/6 Plausible | 2 | — | — |
| 135 | [#324973](https://github.com/microsoft/vscode/issues/324973) | [Error] [GitHub.copilot-chat] unhandlederror-Task API request failed: 403 | 0 | correctness | 5/6 Source-confirmed | 2 | — | — |
| 164 | [#282074](https://github.com/microsoft/vscode/issues/282074) | Closing window with running Cloud session triggers confirm dialog | 0 | papercut | 2/6 Unverified | 1 | — | — |
| 170 | [#291735](https://github.com/microsoft/vscode/issues/291735) | Delegate button shows background/cloud options when not in a git repository | 0 | papercut | 4/6 Traced | 1 | yes | — |
| 176 | [#316634](https://github.com/microsoft/vscode/issues/316634) | [Error] unhandlederror-command 'github.codespaces.activate' not found | 0 | correctness | — | 1 | — | — |
| 177 | [#316958](https://github.com/microsoft/vscode/issues/316958) | Files are readonly | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 179 | [#318370](https://github.com/microsoft/vscode/issues/318370) | Redirect page cannot be reached | 0 | visual | 5/6 Source-confirmed | 1 | — | — |
| 256 | [#289902](https://github.com/microsoft/vscode/issues/289902) | Reviewing TypeScript changes from a Cloud sessions mixes up the language server | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 264 | [#291104](https://github.com/microsoft/vscode/issues/291104) | pulling from main ends up in edit session | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 272 | [#296548](https://github.com/microsoft/vscode/issues/296548) | Cloud agent fails to show repo picker in empty workspace | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 273 | [#296891](https://github.com/microsoft/vscode/issues/296891) | Delegating from background worktree doesn't take changes from worktree | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 302 | [#316963](https://github.com/microsoft/vscode/issues/316963) | Signing in... stays when I cancel the auth flow | 0 | visual | 5/6 Source-confirmed | 0 | yes | — |
| 305 | [#317084](https://github.com/microsoft/vscode/issues/317084) | Agents web experience is difficult to set up | 0 | correctness | 6/6 Confirmed | 0 | — | — |
| 306 | [#317098](https://github.com/microsoft/vscode/issues/317098) | No hosts showing up in agents web experience | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 307 | [#317121](https://github.com/microsoft/vscode/issues/317121) | Hit Authorization error in agents web workbench | 0 | correctness | 6/6 Confirmed | 0 | — | — |
| 308 | [#317124](https://github.com/microsoft/vscode/issues/317124) | Agents web: ongoing session should display disconnected after tunnel host is killed. | 0 | correctness | — | 0 | — | — |
| 309 | [#317313](https://github.com/microsoft/vscode/issues/317313) | Agents window: still prompted to commit and delegate even after selecting a new cloud GitHub repository | 0 | papercut | 5/6 Source-confirmed | 0 | — | — |
| 314 | [#319129](https://github.com/microsoft/vscode/issues/319129) | Copilot Sessions right-pane (Files) disappears immediately on first message when workspace root is a non-repo multi-root folder | 0 | correctness | 4/6 Traced | 0 | yes | — |
| 316 | [#319406](https://github.com/microsoft/vscode/issues/319406) | Clicking apply twice in the cloud model leads to errors | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 324 | [#321887](https://github.com/microsoft/vscode/issues/321887) | Agents "Changes" view does not show diff | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 326 | [#322355](https://github.com/microsoft/vscode/issues/322355) | Cloud agent not making code changes | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 328 | [#322426](https://github.com/microsoft/vscode/issues/322426) | Agent host + welcome window starts a session but doesn't reveal it | 0 | correctness | — | 0 | — | — |
| 339 | [#324691](https://github.com/microsoft/vscode/issues/324691) | [vsCode GithubCoplit extension] Cancel Loop | 0 | none | 3/6 Plausible | 0 | — | — |
| 346 | [#327371](https://github.com/microsoft/vscode/issues/327371) | Cloud Session in Agents Window to Editor Window is broken | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 351 | [#328230](https://github.com/microsoft/vscode/issues/328230) | fix: wait for transient SQLite locks in ExternalIngestIndex (fixes #328227) | 0 | correctness | 6/6 Confirmed | 0 | — | — |

### Search matching (18)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 25 | [#250617](https://github.com/microsoft/vscode/issues/250617) | Find in selection finds no results with multipline lines selected | 0 | correctness | 6/6 Confirmed | 9 | — | — |
| 53 | [#271544](https://github.com/microsoft/vscode/issues/271544) | Searching across files with regex has incorrect and inconsistent handling of CRLF line endings | 0 | correctness | 5/6 Source-confirmed | 5 | — | — |
| 62 | [#299365](https://github.com/microsoft/vscode/issues/299365) | "$$n" doesn't replace by literal "$n" in Regex replace (Workspace search only) | 1 | correctness | 5/6 Source-confirmed | 4 | — | — |
| 84 | [#170529](https://github.com/microsoft/vscode/issues/170529) | Search with regular expression ignores match whole word | 0 | correctness | 5/6 Source-confirmed | 3 | yes | — |
| 85 | [#172882](https://github.com/microsoft/vscode/issues/172882) | Replace in files doesn't work as expected with match containing newline | 0 | correctness | 5/6 Source-confirmed | 3 | — | — |
| 86 | [#191571](https://github.com/microsoft/vscode/issues/191571) | Match Whole Words modifier has no effect for ipynb | 0 | correctness | 5/6 Source-confirmed | 3 | yes | — |
| 97 | [#280939](https://github.com/microsoft/vscode/issues/280939) | Regression in Search: Literal Search Misses Matches That Regex Finds | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 116 | [#175794](https://github.com/microsoft/vscode/issues/175794) | Find in files: Inconsistent search results when using regex and whole word matching | 0 | correctness | 5/6 Source-confirmed | 2 | yes | — |
| 122 | [#252756](https://github.com/microsoft/vscode/issues/252756) | Couldn't find result when useing regex in closed file | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 139 | [#247141](https://github.com/microsoft/vscode/issues/247141) | [Bug] “Transform to” actions don't function on text selected inside the Monaco F&R modal. | 1 | papercut | 5/6 Source-confirmed | 1 | — | — |
| 145 | [#195165](https://github.com/microsoft/vscode/issues/195165) | Quick search is showing results without full match | 0 | correctness | 4/6 Traced | 1 | yes | — |
| 158 | [#254868](https://github.com/microsoft/vscode/issues/254868) | Regex search highlights wrong text in results list | 0 | visual | 3/6 Plausible | 1 | — | — |
| 190 | [#160577](https://github.com/microsoft/vscode/issues/160577) | Regex parse error: missing terminating ] for character class | 0 | papercut | 5/6 Source-confirmed | 0 | yes | — |
| 198 | [#177747](https://github.com/microsoft/vscode/issues/177747) | Notebook Search: regex enabled on default toggle state | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 209 | [#190848](https://github.com/microsoft/vscode/issues/190848) | search match case not working for notebooks | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 226 | [#224477](https://github.com/microsoft/vscode/issues/224477) | Cannot use `\p{sc=...}` and lookahead/lookbehind simultaneously in the search panel with regular expressions | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 243 | [#277880](https://github.com/microsoft/vscode/issues/277880) | editor.find.loop set to false not respected in larger files | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 336 | [#323747](https://github.com/microsoft/vscode/issues/323747) | Uppercase characters break search in files by seemingly imposing case sensitivity | 0 | correctness | 3/6 Plausible | 0 | — | — |

### Web workbench (20)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 33 | [#145647](https://github.com/microsoft/vscode/issues/145647) | Firefox: blank page opening vscode.dev | 0 | correctness | 3/6 Plausible | 8 | — | — |
| 35 | [#242069](https://github.com/microsoft/vscode/issues/242069) | Backspace does not remove empty lines in vscode.dev, duplicates words, and causes cursor jumping. | 2 | correctness | 3/6 Plausible | 7 | — | — |
| 40 | [#239568](https://github.com/microsoft/vscode/issues/239568) | vscode.dev - The request is blocked. | 4 | correctness | 5/6 Source-confirmed | 6 | — | — |
| 54 | [#296541](https://github.com/microsoft/vscode/issues/296541) | vscode.dev freezes with "Brisk Boost" chrome extension installed | 0 | freeze | — | 5 | — | — |
| 64 | [#254620](https://github.com/microsoft/vscode/issues/254620) | On github.dev the export changes is making wrong diff header | 0 | correctness | — | 4 | — | — |
| 118 | [#238365](https://github.com/microsoft/vscode/issues/238365) | Wrong Keyboard Layout and ignored settings - happens on `vscode.dev` | 0 | correctness | 5/6 Source-confirmed | 2 | yes | — |
| 119 | [#246368](https://github.com/microsoft/vscode/issues/246368) | Extensions Preview in detail tab. CORS errors for images(eg. png, gift, etc) | 0 | visual | 5/6 Source-confirmed | 2 | — | — |
| 138 | [#176177](https://github.com/microsoft/vscode/issues/176177) | vscode.dev PWA Icon size on Windows 11 is too small | 1 | visual | 4/6 Traced | 1 | — | — |
| 150 | [#209123](https://github.com/microsoft/vscode/issues/209123) | VSCode Web - Safari - File drag and drop in explorer panel | 0 | visual | 2/6 Unverified | 1 | — | — |
| 154 | [#235453](https://github.com/microsoft/vscode/issues/235453) | Opening a folder in `vscode.dev` with a domain (i.e. *.com) as its name through Remote Tunnels returns a “blocked” page | 0 | correctness | 6/6 Confirmed | 1 | — | — |
| 201 | [#180833](https://github.com/microsoft/vscode/issues/180833) | Firefox: Files in menu items (such as explorer) are opened on mouseup, not onclick | 0 | papercut | 5/6 Source-confirmed | 0 | — | — |
| 205 | [#186453](https://github.com/microsoft/vscode/issues/186453) | Infinite modal from vscode.dev | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 207 | [#188944](https://github.com/microsoft/vscode/issues/188944) | "Turn on Cloud Changes" in vscode.dev does nothing once user signs in | 0 | papercut | 4/6 Traced | 0 | — | — |
| 212 | [#197826](https://github.com/microsoft/vscode/issues/197826) | vscode.dev cannot catch the symbols input when using the Nordic keyboard with AltGr key. | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 218 | [#213143](https://github.com/microsoft/vscode/issues/213143) | Safari 14 no longer able to load vscode.dev, affecting shipped WebKit of macOS 11 and iOS 15 | 0 | none | — | 0 | — | — |
| 219 | [#213153](https://github.com/microsoft/vscode/issues/213153) | tmLanguage.json changes do not appear without resetting browser cache | 0 | none | 3/6 Plausible | 0 | — | — |
| 222 | [#218053](https://github.com/microsoft/vscode/issues/218053) | [Error] Blocked script execution in... | 0 | papercut | 4/6 Traced | 0 | — | — |
| 224 | [#223285](https://github.com/microsoft/vscode/issues/223285) | vscode.dev - does not show images hosted on user-images.githubusercontent.com | 0 | visual | 3/6 Plausible | 0 | — | — |
| 237 | [#238361](https://github.com/microsoft/vscode/issues/238361) | `vscode.workspace.fs.copy` does not copy folders properly on github.dev | 0 | correctness | 4/6 Traced | 0 | — | — |
| 254 | [#288955](https://github.com/microsoft/vscode/issues/288955) | [BUG]: Virtual Keyboard Issue When Scrolling On Editor | 0 | papercut | 5/6 Source-confirmed | 0 | yes | — |

### Search results UI (55)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 52 | [#259720](https://github.com/microsoft/vscode/issues/259720) | Unable to open file error when there are two same name workspace in a project & Open search result in editor | 0 | correctness | 5/6 Source-confirmed | 5 | — | — |
| 55 | [#328427](https://github.com/microsoft/vscode/issues/328427) | [Error] unhandlederror-TreeError [SearchView] Tree element not found: [object Object] | 0 | correctness | 5/6 Source-confirmed | 5 | yes | — |
| 56 | [#94705](https://github.com/microsoft/vscode/issues/94705) | Search does not respect `workbench.editor.revealIfOpen` | 2 | correctness | 5/6 Source-confirmed | 4 | — | — |
| 58 | [#106209](https://github.com/microsoft/vscode/issues/106209) | Line highlight on search results doesn't work | 1 | visual | 5/6 Source-confirmed | 4 | yes | — |
| 59 | [#175369](https://github.com/microsoft/vscode/issues/175369) | Preserve Case toggle in Search does not react correctly to keyboard events | 1 | correctness | 5/6 Source-confirmed | 4 | yes | — |
| 60 | [#258997](https://github.com/microsoft/vscode/issues/258997) | After querying in Chinese and clicking on the results, some entries will be removed from the list. | 1 | correctness | 6/6 Confirmed | 4 | — | — |
| 61 | [#276326](https://github.com/microsoft/vscode/issues/276326) | Search: line number should be wider for coherent preview | 1 | visual | 5/6 Source-confirmed | 4 | yes | — |
| 76 | [#206284](https://github.com/microsoft/vscode/issues/206284) | Quick search: flicker when typing | 3 | visual | 5/6 Source-confirmed | 3 | — | — |
| 77 | [#206511](https://github.com/microsoft/vscode/issues/206511) | Search pane: F4 after editing should visit the next search entry | 3 | papercut | 5/6 Source-confirmed | 3 | — | — |
| 78 | [#154348](https://github.com/microsoft/vscode/issues/154348) | Unable to use outline with search editor | 2 | correctness | 2/6 Unverified | 3 | — | — |
| 81 | [#257639](https://github.com/microsoft/vscode/issues/257639) | right-to-left display in search mode | 1 | visual | 5/6 Source-confirmed | 3 | — | — |
| 87 | [#242474](https://github.com/microsoft/vscode/issues/242474) | Following link from Jasmine testing framework breaks search | 0 | correctness | 5/6 Source-confirmed | 3 | yes | — |
| 88 | [#246714](https://github.com/microsoft/vscode/issues/246714) | Search Editor Progress Bar disappears when switching to another editor and back | 0 | visual | 5/6 Source-confirmed | 3 | yes | — |
| 90 | [#249015](https://github.com/microsoft/vscode/issues/249015) | Maximum call stack size exceeded | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 98 | [#282041](https://github.com/microsoft/vscode/issues/282041) | Very large line numbers show up in AI search results | 0 | visual | 5/6 Source-confirmed | 3 | — | — |
| 111 | [#262483](https://github.com/microsoft/vscode/issues/262483) | Search tab starts iterating over results on its own | 1 | papercut | 3/6 Plausible | 2 | — | — |
| 114 | [#303430](https://github.com/microsoft/vscode/issues/303430) | Grouping choice and sorting choice not reflected in pickers | 1 | correctness | — | 2 | — | — |
| 120 | [#250189](https://github.com/microsoft/vscode/issues/250189) | Bug in global search field | 0 | papercut | 5/6 Source-confirmed | 2 | — | — |
| 124 | [#276896](https://github.com/microsoft/vscode/issues/276896) | Search Editor tab labels don't reload correctly | 0 | visual | 5/6 Source-confirmed | 2 | yes | — |
| 140 | [#261789](https://github.com/microsoft/vscode/issues/261789) | keyword suggestion message overrides search results count | 1 | visual | 5/6 Source-confirmed | 1 | — | — |
| 141 | [#115953](https://github.com/microsoft/vscode/issues/115953) | Search: Arrow navigation broken | 0 | papercut | 5/6 Source-confirmed | 1 | yes | — |
| 147 | [#198159](https://github.com/microsoft/vscode/issues/198159) | Broken full-page search result navigation for multiple folder directories of the same name in a workspace | 0 | correctness | 5/6 Source-confirmed | 1 | yes | — |
| 148 | [#201720](https://github.com/microsoft/vscode/issues/201720) | Abnormal syntax highlight for Perl in Search Editor ("search.action.openNewEditor") | 0 | visual | 3/6 Plausible | 1 | — | — |
| 149 | [#208199](https://github.com/microsoft/vscode/issues/208199) | Focused search buttons border color update | 0 | visual | 5/6 Source-confirmed | 1 | yes | — |
| 152 | [#224863](https://github.com/microsoft/vscode/issues/224863) | Search highlight not cleared sometimes | 0 | visual | 6/6 Confirmed | 1 | yes | — |
| 153 | [#225315](https://github.com/microsoft/vscode/issues/225315) | Search Editor Progress Bar Animates Endlessly After Search Completed (intermittent) | 0 | visual | 5/6 Source-confirmed | 1 | yes | — |
| 162 | [#270519](https://github.com/microsoft/vscode/issues/270519) | The search results cannot be copied in a tree structure | 0 | papercut | 5/6 Source-confirmed | 1 | — | — |
| 163 | [#273693](https://github.com/microsoft/vscode/issues/273693) | Untitled-1 Tab Automatically Created After Opening File from Search Results | 0 | papercut | 3/6 Plausible | 1 | — | — |
| 172 | [#301832](https://github.com/microsoft/vscode/issues/301832) | Search pane compacts folders despite "explorer.compactFolders": false in settings | 0 | correctness | 5/6 Source-confirmed | 1 | — | — |
| 175 | [#307908](https://github.com/microsoft/vscode/issues/307908) | Display "Search => Open in Editor" | 0 | visual | 3/6 Plausible | 1 | — | — |
| 185 | [#226869](https://github.com/microsoft/vscode/issues/226869) | References to "Default search behavior" are confusing | 1 | papercut | 5/6 Source-confirmed | 0 | — | — |
| 186 | [#67068](https://github.com/microsoft/vscode/issues/67068) | Find in files in non-existent folder highlights wrong input field on error | 0 | visual | 5/6 Source-confirmed | 0 | yes | — |
| 191 | [#162157](https://github.com/microsoft/vscode/issues/162157) | Search tree - selected item should be kept in the viewport | 0 | visual | 5/6 Source-confirmed | 0 | yes | — |
| 195 | [#169322](https://github.com/microsoft/vscode/issues/169322) | Search editor context lines is ambiguous and doesn't appear to be accessible to screen readers | 0 | papercut | 5/6 Source-confirmed | 0 | yes | — |
| 196 | [#169323](https://github.com/microsoft/vscode/issues/169323) | Search editor can randomize the result order and also the file count(?) when changing the context lines | 0 | visual | 4/6 Traced | 0 | — | — |
| 200 | [#180539](https://github.com/microsoft/vscode/issues/180539) | TreeError [SearchView] Unknown compressed tree node | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 203 | [#184192](https://github.com/microsoft/vscode/issues/184192) | order of search results swaps on notebook open | 0 | visual | 5/6 Source-confirmed | 0 | — | — |
| 204 | [#184348](https://github.com/microsoft/vscode/issues/184348) | Search Editor peek support for notebook search | 0 | correctness | 4/6 Traced | 0 | — | — |
| 206 | [#188557](https://github.com/microsoft/vscode/issues/188557) | Closed notebook search: opening the notebook at a result might not scroll properly to it | 0 | visual | 3/6 Plausible | 0 | — | — |
| 214 | [#203386](https://github.com/microsoft/vscode/issues/203386) | Open-notebook search results not appearing correctly on re-opening notebook | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 216 | [#204608](https://github.com/microsoft/vscode/issues/204608) | The Context does not set hasSearchResult when searching directly in the SearchEditor | 0 | papercut | 5/6 Source-confirmed | 0 | yes | — |
| 223 | [#221495](https://github.com/microsoft/vscode/issues/221495) | Search editor shows the wrong results when running multiple | 0 | correctness | 6/6 Confirmed | 0 | — | — |
| 225 | [#224043](https://github.com/microsoft/vscode/issues/224043) | "Notebook Find Filters" button shows in search when no notebook is active | 0 | papercut | 5/6 Source-confirmed | 0 | — | — |
| 234 | [#234285](https://github.com/microsoft/vscode/issues/234285) | Quick search does not retain search term when moving to view | 0 | papercut | 5/6 Source-confirmed | 0 | yes | — |
| 235 | [#234803](https://github.com/microsoft/vscode/issues/234803) | Invalid outline in search editor | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 236 | [#235210](https://github.com/microsoft/vscode/issues/235210) | Clear Search Results also clears the filter unexpectedly | 0 | papercut | 5/6 Source-confirmed | 0 | yes | — |
| 238 | [#251528](https://github.com/microsoft/vscode/issues/251528) | Regression: findMatch Foreground colors break RTL text | 0 | visual | 5/6 Source-confirmed | 0 | yes | — |
| 240 | [#261170](https://github.com/microsoft/vscode/issues/261170) | Option to disable search highlighting from updating PRIMARY selection (Linux/X11 & Wayland) | 0 | papercut | 5/6 Source-confirmed | 0 | — | — |
| 241 | [#265119](https://github.com/microsoft/vscode/issues/265119) | AI Search has no empty state for no results | 0 | visual | 4/6 Traced | 0 | — | — |
| 246 | [#284493](https://github.com/microsoft/vscode/issues/284493) | Copilot search feedback: "setupWthProvider" | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 247 | [#284496](https://github.com/microsoft/vscode/issues/284496) | Tree loses focus when expanding "github copilot results" | 0 | papercut | 4/6 Traced | 0 | — | — |
| 248 | [#284498](https://github.com/microsoft/vscode/issues/284498) | Copy All doesn't work for AI search | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 276 | [#301773](https://github.com/microsoft/vscode/issues/301773) | Search: Mode reuseEditor doesn't take you to the correct line in the source code editor after you make changes in the source code editor | 0 | correctness | 4/6 Traced | 0 | — | — |
| 342 | [#326302](https://github.com/microsoft/vscode/issues/326302) | [accessibility] [regression]: screen reader cannot announce results while navigating between results in search box | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 353 | [#328433](https://github.com/microsoft/vscode/issues/328433) | fix: guard notebook match selection against unmaterialized tree element (fixes #328427) | 0 | papercut | 5/6 Source-confirmed | 0 | — | — |

### Agent mobile (13)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 83 | [#316762](https://github.com/microsoft/vscode/issues/316762) | Agents App: Crashes when I click on an mp4 file in my Files List | 1 | crash | 3/6 Plausible | 3 | — | — |
| 286 | [#313339](https://github.com/microsoft/vscode/issues/313339) | Agents Mobile: "Use AI Features" Button Shown in Accounts Menu When Already Signed In | 0 | visual | 3/6 Plausible | 0 | — | — |
| 287 | [#313341](https://github.com/microsoft/vscode/issues/313341) | Agents Mobile: Sort Button Uses Wrong Icon (Filter) in Sessions List | 0 | visual | 5/6 Source-confirmed | 0 | yes | — |
| 288 | [#313343](https://github.com/microsoft/vscode/issues/313343) | Agents Mobile: Sessions List Uses Sidebar Icon Instead of Overlay-Appropriate Icon | 0 | visual | 5/6 Source-confirmed | 0 | — | — |
| 289 | [#313344](https://github.com/microsoft/vscode/issues/313344) | Agents Mobile: Tapping "Rediscover Hosts" Dismisses the Hosts Overlay | 0 | papercut | — | 0 | — | — |
| 290 | [#313345](https://github.com/microsoft/vscode/issues/313345) | Agents Mobile: Non-Functional Pill Grab Bar at Top of Host Selection Widget | 0 | visual | — | 0 | — | — |
| 291 | [#313347](https://github.com/microsoft/vscode/issues/313347) | Agents Mobile: Attach Context Button Does Nothing | 0 | correctness | — | 0 | — | — |
| 292 | [#313349](https://github.com/microsoft/vscode/issues/313349) | Agents Mobile: Action Bar Below Agent Turn Has No Spacing and Copy Icon Overlaps Text | 0 | visual | 3/6 Plausible | 0 | — | — |
| 293 | [#313351](https://github.com/microsoft/vscode/issues/313351) | Agents Mobile: Cannot Rename a Session | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 294 | [#313352](https://github.com/microsoft/vscode/issues/313352) | Agents Mobile: Long Press on Session List Opens Activity Bar Configuration Menu Instead of Context Menu | 0 | correctness | 4/6 Traced | 0 | — | — |
| 295 | [#313353](https://github.com/microsoft/vscode/issues/313353) | Agents Mobile: Tapping Session Title Gives Feedback But Does Nothing | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 296 | [#313354](https://github.com/microsoft/vscode/issues/313354) | Agents Mobile: Cannot Paste into Input Box — Long Press Triggers Wrong Element's Context Menu | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 297 | [#313358](https://github.com/microsoft/vscode/issues/313358) | Agents Mobile: Flashing Blue Dot Next to Cursor in Input Box | 0 | visual | 3/6 Plausible | 0 | — | — |

### Search APIs (6)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 210 | [#195772](https://github.com/microsoft/vscode/issues/195772) | The `vscode.proposed.findTextInFiles.d.ts` proposal isn't self-contained | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 215 | [#204179](https://github.com/microsoft/vscode/issues/204179) | Docs mistake: `FindTextInFilesOptions.useDefaultExcludes` defaults to false, not true. | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 221 | [#214290](https://github.com/microsoft/vscode/issues/214290) | Expected pattern to be a non-empty string | 0 | papercut | 5/6 Source-confirmed | 0 | yes | — |
| 227 | [#226720](https://github.com/microsoft/vscode/issues/226720) | `FileSearchProviderOptions#session` should not be `undefined` | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 228 | [#226736](https://github.com/microsoft/vscode/issues/226736) | Docs for `FileSearchProviderOptions.folderOptions.useIgnoreFiles` are wrong | 0 | papercut | 5/6 Source-confirmed | 0 | — | — |
| 229 | [#226737](https://github.com/microsoft/vscode/issues/226737) | Properties of `FileSearchProviderOptions` should be marked `readonly` | 0 | papercut | 5/6 Source-confirmed | 0 | yes | — |

### Other (34)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 6 | [#323841](https://github.com/microsoft/vscode/issues/323841) | In Paste Confirmation Dialog: "Cancel" Still Pastes, and "Paste" Pastes Twice | 5 | correctness | 2/6 Unverified | 22 | — | — |
| 12 | [#249635](https://github.com/microsoft/vscode/issues/249635) | TextModel got disposed before DiffEditorWidget model got reset | 1 | correctness | 5/6 Source-confirmed | 14 | yes | — |
| 23 | [#295655](https://github.com/microsoft/vscode/issues/295655) | Spawn UNKNOWN in Search/Chat | 0 | correctness | 6/6 Confirmed | 10 | — | — |
| 31 | [#318704](https://github.com/microsoft/vscode/issues/318704) | Error - Failed during initial scan: Could not find ripgrep binary in ZooCode extension after update vscode | 2 | none | — | 8 | — | — |
| 39 | [#286250](https://github.com/microsoft/vscode/issues/286250) | Kicking off multiple agent sessions sometimes leads to freezing or delay in agent sessions list | 0 | correctness | 6/6 Confirmed | 7 | — | — |
| 43 | [#236455](https://github.com/microsoft/vscode/issues/236455) | ERR [189] potential listener LEAK detected, having 248 listeners already. MOST frequent listener (33) | 1 | perf | 5/6 Source-confirmed | 6 | — | — |
| 51 | [#246399](https://github.com/microsoft/vscode/issues/246399) | Cannot read properties of undefined (reading 'hasNode') | 0 | correctness | 2/6 Unverified | 5 | — | — |
| 91 | [#253791](https://github.com/microsoft/vscode/issues/253791) | The search function often fails to find anything | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 94 | [#264640](https://github.com/microsoft/vscode/issues/264640) | Local changes not shown in diff view | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 115 | [#320566](https://github.com/microsoft/vscode/issues/320566) | Roo Code on Win11 - Codebase Indexing "Error - Failed during initial scan: Could not find ripgrep binary" | 1 | none | — | 2 | — | — |
| 123 | [#274104](https://github.com/microsoft/vscode/issues/274104) | Searching files for "termservi" gives bad first result | 0 | papercut | 3/6 Plausible | 2 | — | — |
| 129 | [#291415](https://github.com/microsoft/vscode/issues/291415) | I always get the "chat request in progress ..." notification when trying to close a specific workspace | 0 | papercut | 3/6 Plausible | 2 | — | — |
| 134 | [#324710](https://github.com/microsoft/vscode/issues/324710) | VS Code crashes on pasting to the workspace search field | 0 | crash | 3/6 Plausible | 2 | — | — |
| 142 | [#130992](https://github.com/microsoft/vscode/issues/130992) | Debugger fails with SyntaxError when using an external directory for TypeScript (outDir) | 0 | correctness | 5/6 Source-confirmed | 1 | yes | — |
| 143 | [#191157](https://github.com/microsoft/vscode/issues/191157) | Recently opened project has the same name | 0 | visual | 4/6 Traced | 1 | — | — |
| 156 | [#248173](https://github.com/microsoft/vscode/issues/248173) | F4 breaks in search view after deleting result | 0 | correctness | 5/6 Source-confirmed | 1 | yes | — |
| 157 | [#251780](https://github.com/microsoft/vscode/issues/251780) | Implement Searching Bar as Overlay | 0 | visual | 6/6 Confirmed | 1 | — | — |
| 160 | [#261001](https://github.com/microsoft/vscode/issues/261001) | Search Editor: typing on "files to include" does not respect the "Search on Type" setting | 0 | correctness | 5/6 Source-confirmed | 1 | yes | — |
| 165 | [#282434](https://github.com/microsoft/vscode/issues/282434) | Local sessions: keeping edits needs 2 "Keep" to clear the edits | 0 | correctness | 6/6 Confirmed | 1 | — | — |
| 178 | [#318355](https://github.com/microsoft/vscode/issues/318355) | In Agents sidebar, Allow buttons push session list down, causing misclicks on Done | 0 | correctness | 5/6 Source-confirmed | 1 | — | — |
| 182 | [#326647](https://github.com/microsoft/vscode/issues/326647) | [Error] unhandlederror-acceptResponseProgress: Adding progress to a completed response | 0 | correctness | 5/6 Source-confirmed | 1 | — | — |
| 184 | [#327121](https://github.com/microsoft/vscode/issues/327121) | GitHub Copilot Chat intermittently displays the Claude Code chat interface | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 189 | [#158294](https://github.com/microsoft/vscode/issues/158294) | Multiselect selecting extra elements | 0 | correctness | 4/6 Traced | 0 | — | — |
| 199 | [#179915](https://github.com/microsoft/vscode/issues/179915) | notebook search: output matches not disappearing when dismissed | 0 | visual | 5/6 Source-confirmed | 0 | — | — |
| 252 | [#288569](https://github.com/microsoft/vscode/issues/288569) | Disabling Search on Type still allows search results to be updated when editing files containing results | 0 | papercut | 5/6 Source-confirmed | 0 | — | — |
| 253 | [#288692](https://github.com/microsoft/vscode/issues/288692) | There's a naming collision: both `ChatContextKeys.chatSessionType` (line 65) and `ChatContextKeys.agentSessionType` (line 103) use the same context key string `'chatSessionType'`. This creates ambiguity and can lead to unexpected behavior. The `agentSessionType` export should use a different key string, such as `'agentSessionType'`. | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 270 | [#292796](https://github.com/microsoft/vscode/issues/292796) | GHPR asking for GHE auth when opening a remote repo even though there is no open GHE repo | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 285 | [#312881](https://github.com/microsoft/vscode/issues/312881) | Truncation in sessions lists can hide deleted line counts | 0 | visual | 5/6 Source-confirmed | 0 | yes | — |
| 303 | [#316969](https://github.com/microsoft/vscode/issues/316969) | /merge isn't a recognized slash command | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 311 | [#317851](https://github.com/microsoft/vscode/issues/317851) | TitleBarAccountWidget leak | 0 | perf | 2/6 Unverified | 0 | — | — |
| 315 | [#319290](https://github.com/microsoft/vscode/issues/319290) | Formatting is off when rendering CCA session | 0 | visual | — | 0 | — | — |
| 320 | [#321073](https://github.com/microsoft/vscode/issues/321073) | vscode error | 0 | none | 3/6 Plausible | 0 | — | — |
| 322 | [#321580](https://github.com/microsoft/vscode/issues/321580) | An anonymous background process is running in the Task Manager. | 0 | perf | 3/6 Plausible | 0 | — | — |
| 338 | [#324061](https://github.com/microsoft/vscode/issues/324061) | Agents: forking a session in a group does not add the new session to that group | 0 | correctness | 3/6 Plausible | 0 | — | — |

## Feature requests

### Search scope and filters (10)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | [#20530](https://github.com/microsoft/vscode/issues/20530) | Search: target particular set of files | 357 | backlog-candidate | 100 | — |
| 5 | [#26574](https://github.com/microsoft/vscode/issues/26574) | Find in Files "files to include" override .gitignore | 92 | backlog-candidate | 25 | — |
| 16 | [#242757](https://github.com/microsoft/vscode/issues/242757) | "Find all" with "occurrences to exclude" | 25 | backlog-candidate | 10 | — |
| 22 | [#50638](https://github.com/microsoft/vscode/issues/50638) | Cannot exclude root folders while searching | 20 | dormant | 7 | — |
| 23 | [#255091](https://github.com/microsoft/vscode/issues/255091) | Add option to exclude search with git submodules | 21 | backlog-candidate | 6 | — |
| 49 | [#304477](https://github.com/microsoft/vscode/issues/304477) | search.exclude does not work for "Go to Symbol in Workspace" | 1 | active | 1 | — |
| 90 | [#284501](https://github.com/microsoft/vscode/issues/284501) | changing exclude files for search with copilot suggestions | 0 | dormant | 0 | — |
| 99 | [#319112](https://github.com/microsoft/vscode/issues/319112) | workbench.action.findInFiles: accept file URIs to bypass argv-length limits | 0 | active | 0 | — |
| 107 | [#323820](https://github.com/microsoft/vscode/issues/323820) | Ability to limit search to within the current function scope | 0 | active | 0 | — |
| 114 | [#327568](https://github.com/microsoft/vscode/issues/327568) | Can only search for the content of the opened file. | 0 | active | 0 | — |

### Find and replace workflows (11)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 2 | [#14836](https://github.com/microsoft/vscode/issues/14836) | Add "find all occurences" in the current file feature | 231 | backlog-candidate | 66 | — |
| 3 | [#11688](https://github.com/microsoft/vscode/issues/11688) | Feature request: 'Ignore comments' checkbox in the 'Find' dialog | 194 | backlog-candidate | 39 | — |
| 4 | [#93031](https://github.com/microsoft/vscode/issues/93031) | Replace in search Editor | 118 | backlog-candidate | 35 | — |
| 9 | [#47783](https://github.com/microsoft/vscode/issues/47783) | Command - Undo Replace All | 66 | backlog-candidate | 15 | — |
| 30 | [#35337](https://github.com/microsoft/vscode/issues/35337) | Add control to open file shown in "replace preview" editor when performing project-wide find/replace | 10 | dormant | 3 | — |
| 55 | [#194931](https://github.com/microsoft/vscode/issues/194931) | Find and Replace in closed notebook search | 0 | dormant | 1 | — |
| 59 | [#243578](https://github.com/microsoft/vscode/issues/243578) | 'Next Result' in document should be higher priority than 'Next Result' in search panel | 0 | dormant | 1 | — |
| 70 | [#64311](https://github.com/microsoft/vscode/issues/64311) | Search: find, replace input boxes miss scrollbar | 0 | dormant | 0 | — |
| 74 | [#174977](https://github.com/microsoft/vscode/issues/174977) | Add option to not focus next search result | 0 | backlog-candidate | 0 | — |
| 75 | [#174982](https://github.com/microsoft/vscode/issues/174982) | No Search Diff editor for Notebooks | 0 | dormant | 0 | — |
| 117 | [#328447](https://github.com/microsoft/vscode/issues/328447) | Warn when replacement string already exists in target files during global Search & Replace | 0 | active | 0 | — |

### Web URI handling (10)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 6 | [#256181](https://github.com/microsoft/vscode/issues/256181) | Feature Request: Mobile-Friendly Layout for vscode.dev | 41 | backlog-candidate | 24 | — |
| 11 | [#228421](https://github.com/microsoft/vscode/issues/228421) | Make URI Handlers available for vscode.dev | 31 | backlog-candidate | 14 | — |
| 12 | [#203169](https://github.com/microsoft/vscode/issues/203169) | Undocumented feature "Turn on Cloud Changes…" is visible | 38 | dormant | 13 | — |
| 25 | [#140684](https://github.com/microsoft/vscode/issues/140684) | Web: Allow non-repository, non-filesystem temporary folders | 21 | backlog-candidate | 5 | — |
| 34 | [#135784](https://github.com/microsoft/vscode/issues/135784) | [PWA] Register vscode.dev as file handler for well-supported file types | 9 | backlog-candidate | 2 | — |
| 39 | [#289467](https://github.com/microsoft/vscode/issues/289467) | Give me control over empty state URI resolution in ChatContent Provider | 0 | active | 2 | — |
| 43 | [#163593](https://github.com/microsoft/vscode/issues/163593) | Custom URLs for non-theme extensions | 5 | backlog-candidate | 1 | — |
| 62 | [#289469](https://github.com/microsoft/vscode/issues/289469) | Allow me to redirect a URI to another URI in the Content Provider | 0 | active | 1 | — |
| 76 | [#177856](https://github.com/microsoft/vscode/issues/177856) | shared links to azure repos notebooks do not open to specified location | 0 | backlog-candidate | 0 | — |
| 77 | [#178204](https://github.com/microsoft/vscode/issues/178204) | vscode.dev: Support routes in PWA applications | 0 | backlog-candidate | 0 | — |

### Search APIs and providers (11)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 7 | [#59921](https://github.com/microsoft/vscode/issues/59921) | Stabilize TextSearchProvider API | 35 | active | 18 | — |
| 8 | [#73524](https://github.com/microsoft/vscode/issues/73524) | Stabilize FileSearchProvider API | 42 | active | 16 | — |
| 19 | [#285492](https://github.com/microsoft/vscode/issues/285492) | Feature Request: Add workspace-relative variant of ${resultsFiles} for search commands | 27 | backlog-candidate | 9 | — |
| 24 | [#59924](https://github.com/microsoft/vscode/issues/59924) | Stabilize findTextInFiles API | 10 | backlog-candidate | 6 | — |
| 28 | [#48674](https://github.com/microsoft/vscode/issues/48674) | Revamp findFiles | 2 | backlog-candidate | 4 | — |
| 29 | [#241853](https://github.com/microsoft/vscode/issues/241853) | Search Service: Add support for finding folders | 2 | backlog-candidate | 4 | — |
| 46 | [#210692](https://github.com/microsoft/vscode/issues/210692) | Search API Work Summary | 3 | dormant | 1 | — |
| 81 | [#205762](https://github.com/microsoft/vscode/issues/205762) | In debug mode `findfiles2` could print out why it skipped a particular file that matched the pattern | 0 | dormant | 0 | — |
| 82 | [#226734](https://github.com/microsoft/vscode/issues/226734) | Consider to support streaming for file search results | 0 | dormant | 0 | — |
| 83 | [#226755](https://github.com/microsoft/vscode/issues/226755) | How should bad/stale providers be handled? | 0 | dormant | 0 | — |
| 84 | [#234294](https://github.com/microsoft/vscode/issues/234294) | Feature Request: Expose findWidget Actions State via API | 0 | backlog-candidate | 0 | — |

### Search history persistence (6)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 10 | [#23099](https://github.com/microsoft/vscode/issues/23099) | Add dropdown for search input history | 59 | backlog-candidate | 14 | — |
| 14 | [#263436](https://github.com/microsoft/vscode/issues/263436) | Find history does not work as a most recent stack | 24 | backlog-candidate | 12 | — |
| 20 | [#176183](https://github.com/microsoft/vscode/issues/176183) | Add option to persist search UI settings | 26 | backlog-candidate | 8 | — |
| 57 | [#208651](https://github.com/microsoft/vscode/issues/208651) | Quick search - provide history | 0 | backlog-candidate | 1 | — |
| 69 | [#191104](https://github.com/microsoft/vscode/issues/191104) | Consider persisting results for quick search | 1 | backlog-candidate | 0 | — |
| 109 | [#324221](https://github.com/microsoft/vscode/issues/324221) | Autocomplete/autosuggest of previous searches in the file search | 0 | active | 0 | — |

### Search matching syntax (7)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 13 | [#241525](https://github.com/microsoft/vscode/issues/241525) | Feature request: Fuzzy search files including file path | 32 | backlog-candidate | 13 | — |
| 15 | [#230337](https://github.com/microsoft/vscode/issues/230337) | Support for search engines | 35 | backlog-candidate | 10 | — |
| 26 | [#158546](https://github.com/microsoft/vscode/issues/158546) | need region support in code-search formate file | 25 | backlog-candidate | 4 | — |
| 27 | [#75265](https://github.com/microsoft/vscode/issues/75265) | Global regex search with "Not matching character" doesn't match newline | 13 | backlog-candidate | 4 | — |
| 58 | [#243122](https://github.com/microsoft/vscode/issues/243122) | Bug: Arabic search fails to find words without diacritics (Tashkeel) | 0 | dormant | 1 | — |
| 94 | [#305116](https://github.com/microsoft/vscode/issues/305116) | Quick Open (Ctrl+P) file search returns too many irrelevant results due to letter-level fuzzy matching | 0 | active | 0 | — |
| 112 | [#327250](https://github.com/microsoft/vscode/issues/327250) | Support boolean AND/OR/NOT search in the Search view | 0 | backlog-candidate | 0 | — |

### Agent session management (16)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 17 | [#276243](https://github.com/microsoft/vscode/issues/276243) | Agents View: support deletion of sessions | 13 | active | 10 | — |
| 21 | [#319415](https://github.com/microsoft/vscode/issues/319415) | Copilot CLI sessions don't appear in the Agents window session list | 2 | active | 8 | — |
| 32 | [#264555](https://github.com/microsoft/vscode/issues/264555) | Agent sessions support for multi-root workspaces | 0 | active | 3 | — |
| 33 | [#282109](https://github.com/microsoft/vscode/issues/282109) | Agent sessions: support empty workspaces | 0 | active | 3 | — |
| 41 | [#312094](https://github.com/microsoft/vscode/issues/312094) | Chat Sessions panel: allow user-defined groups or folders | 0 | active | 2 | — |
| 50 | [#313107](https://github.com/microsoft/vscode/issues/313107) | Agents: Consider surfacing pinned sessions at the top | 1 | backlog-candidate | 1 | — |
| 51 | [#317738](https://github.com/microsoft/vscode/issues/317738) | Agents app: sessions housekeeping | 1 | active | 1 | — |
| 92 | [#289538](https://github.com/microsoft/vscode/issues/289538) | In progress sessions cannot be renamed in sessions view | 0 | active | 0 | — |
| 97 | [#313108](https://github.com/microsoft/vscode/issues/313108) | Agents: Provide a way to group completed sessions by workspace | 0 | backlog-candidate | 0 | — |
| 98 | [#315960](https://github.com/microsoft/vscode/issues/315960) | "Tuck away" old CCA Sessions in vscode windows | 0 | active | 0 | — |
| 100 | [#319199](https://github.com/microsoft/vscode/issues/319199) | Chat: add a setting to suppress or delay the sessions list hover preview | 0 | active | 0 | — |
| 101 | [#320241](https://github.com/microsoft/vscode/issues/320241) | Ghost session cannot be removed | 0 | active | 0 | — |
| 102 | [#320781](https://github.com/microsoft/vscode/issues/320781) | selectable sort order for copilot chat sessions | 0 | active | 0 | — |
| 103 | [#321491](https://github.com/microsoft/vscode/issues/321491) | agents window -- ability to sort `Done` sessions by "most recently marked done" | 0 | active | 0 | — |
| 110 | [#324839](https://github.com/microsoft/vscode/issues/324839) | Feature Request: Add setting to hide the recent sessions list in the Chat panel | 0 | active | 0 | — |
| 111 | [#327097](https://github.com/microsoft/vscode/issues/327097) | Feature Request: Allow filtering/hiding chat sessions by specific agent/provider | 0 | active | 0 | — |

### Search results view (15)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 18 | [#152518](https://github.com/microsoft/vscode/issues/152518) | Find/Search inputs: Allow setting input font, like in SCM. | 28 | backlog-candidate | 9 | — |
| 37 | [#201719](https://github.com/microsoft/vscode/issues/201719) | Consider redesign of Search Editor ("search.action.openNewEditor") | 0 | dormant | 2 | — |
| 44 | [#194044](https://github.com/microsoft/vscode/issues/194044) | Search Editor: Add keybinding for double-click action, e.g. to open to the side | 3 | backlog-candidate | 1 | — |
| 47 | [#234501](https://github.com/microsoft/vscode/issues/234501) | The font of global search bar and search bar should be a monospace font. | 2 | dormant | 1 | — |
| 53 | [#64328](https://github.com/microsoft/vscode/issues/64328) | Wasted space in the multiline search input | 0 | backlog-candidate | 1 | — |
| 54 | [#67397](https://github.com/microsoft/vscode/issues/67397) | Support filter on type should in search tree | 0 | backlog-candidate | 1 | — |
| 68 | [#155874](https://github.com/microsoft/vscode/issues/155874) | File Decorations for Search Folders | 1 | backlog-candidate | 0 | — |
| 71 | [#127038](https://github.com/microsoft/vscode/issues/127038) | Add "Show all results" button when hitting maxResults | 0 | dormant | 0 | — |
| 72 | [#163590](https://github.com/microsoft/vscode/issues/163590) | "Collapse other results" button in search view context menu | 0 | backlog-candidate | 0 | — |
| 78 | [#191683](https://github.com/microsoft/vscode/issues/191683) | Experience when having a lot of matches | 0 | dormant | 0 | — |
| 79 | [#192012](https://github.com/microsoft/vscode/issues/192012) | Add option to turn off rich content notebook search results | 0 | dormant | 0 | — |
| 80 | [#197634](https://github.com/microsoft/vscode/issues/197634) | Search: Support tree type navigation and find widget | 0 | dormant | 0 | — |
| 87 | [#284495](https://github.com/microsoft/vscode/issues/284495) | Remember Copilot Results expand state | 0 | dormant | 0 | — |
| 88 | [#284497](https://github.com/microsoft/vscode/issues/284497) | Copilot Search: Improve tree label | 0 | dormant | 0 | — |
| 89 | [#284499](https://github.com/microsoft/vscode/issues/284499) | AI Results are rendered differently | 0 | dormant | 0 | — |

### File navigation search (5)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 31 | [#125871](https://github.com/microsoft/vscode/issues/125871) | Resolve file with same name as folder as index | 8 | backlog-candidate | 3 | — |
| 35 | [#208840](https://github.com/microsoft/vscode/issues/208840) | File quick open does not match exact file paths in multi-root workspace | 4 | backlog-candidate | 2 | — |
| 45 | [#201842](https://github.com/microsoft/vscode/issues/201842) | Cache the list of files for "Go to file" / "Quick open" / "Search files by name" | 3 | backlog-candidate | 1 | — |
| 56 | [#203949](https://github.com/microsoft/vscode/issues/203949) | Search: allow multi-select and open in editor | 0 | backlog-candidate | 1 | — |
| 73 | [#164905](https://github.com/microsoft/vscode/issues/164905) | Starving extension host can block file navigation | 0 | backlog-candidate | 0 | — |

### Cloud agent workflow (16)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 36 | [#257289](https://github.com/microsoft/vscode/issues/257289) | scoping of CCA (copilot coding agent) tasks | 1 | active | 2 | — |
| 38 | [#275502](https://github.com/microsoft/vscode/issues/275502) | Copilot Cloud Agent output needs a revamp | 0 | backlog-candidate | 2 | — |
| 40 | [#292702](https://github.com/microsoft/vscode/issues/292702) | Steering / queued messages for Cloud agents | 0 | active | 2 | — |
| 48 | [#260225](https://github.com/microsoft/vscode/issues/260225) | Support generating `copilot-setup-steps.yml` @osortega | 2 | active | 1 | — |
| 60 | [#253583](https://github.com/microsoft/vscode/issues/253583) | Deeplinking from Coding Agent back into VS Code | 0 | backlog-candidate | 1 | — |
| 63 | [#289905](https://github.com/microsoft/vscode/issues/289905) | Allow the user to open the PR from the agent list entry context menu | 0 | dormant | 1 | — |
| 65 | [#292392](https://github.com/microsoft/vscode/issues/292392) | Open associated workspace / repo with recent session | 0 | dormant | 1 | — |
| 66 | [#313114](https://github.com/microsoft/vscode/issues/313114) | Agents: Provide option to pin entire workspaces | 0 | backlog-candidate | 1 | — |
| 67 | [#326520](https://github.com/microsoft/vscode/issues/326520) | Copilot Chat (Agents): folder picker defaults to alphabetically first repository in multi-repo workspace, no way to prefer workspace root | 0 | active | 1 | — |
| 85 | [#281370](https://github.com/microsoft/vscode/issues/281370) | No Apply Changes button in multi diff editor for cloud sessions | 0 | backlog-candidate | 0 | — |
| 93 | [#292407](https://github.com/microsoft/vscode/issues/292407) | Add Delegate action on todos in editor | 0 | dormant | 0 | — |
| 96 | [#311027](https://github.com/microsoft/vscode/issues/311027) | Agents: Surface the handoff between Agent app and the PR | 0 | backlog-candidate | 0 | — |
| 104 | [#321941](https://github.com/microsoft/vscode/issues/321941) | Agents: Showing irrelevant changes when created a branch from non main branch | 0 | active | 0 | — |
| 113 | [#327384](https://github.com/microsoft/vscode/issues/327384) | Cloud Session should be able to check out into a work tree. | 0 | active | 0 | — |
| 115 | [#327608](https://github.com/microsoft/vscode/issues/327608) | Cloud Session: There is no way to mark cloud session PR as ready to review | 0 | active | 0 | — |
| 116 | [#327945](https://github.com/microsoft/vscode/issues/327945) | Ability to show the parent git folder name for git worktree sessions | 0 | active | 0 | — |

### Chat and agent UX (10)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 42 | [#317658](https://github.com/microsoft/vscode/issues/317658) | Agents: Make mobile links clickable | 0 | active | 2 | — |
| 52 | [#321726](https://github.com/microsoft/vscode/issues/321726) | Request for search in chat | 1 | active | 1 | — |
| 61 | [#287614](https://github.com/microsoft/vscode/issues/287614) | Update Copilot getting started | 0 | dormant | 1 | — |
| 64 | [#291963](https://github.com/microsoft/vscode/issues/291963) | Auto send chats from new welcome page after opening workspace | 0 | dormant | 1 | — |
| 86 | [#284492](https://github.com/microsoft/vscode/issues/284492) | Copilot search input should be natural language and not text search properties | 0 | dormant | 0 | — |
| 91 | [#289208](https://github.com/microsoft/vscode/issues/289208) | Increase sign in awareness from new welcome chat | 0 | dormant | 0 | — |
| 95 | [#309614](https://github.com/microsoft/vscode/issues/309614) | Agents: No indication of screenreader mode | 0 | backlog-candidate | 0 | — |
| 105 | [#322004](https://github.com/microsoft/vscode/issues/322004) | Global, local-device search across Copilot Chat conversations | 0 | active | 0 | — |
| 106 | [#322715](https://github.com/microsoft/vscode/issues/322715) | Agent adjacent scratchpad. | 0 | active | 0 | — |
| 108 | [#324148](https://github.com/microsoft/vscode/issues/324148) | Feature Request: Compare two AI chat / agent sessions and show the agent flow differences | 0 | active | 0 | — |
