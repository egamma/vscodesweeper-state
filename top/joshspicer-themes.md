# Top issues by theme — joshspicer

Experimental themed view of [the flat ranking](joshspicer.md); themes assigned by the review engine. Rank/score are the lane-wide values. Generated 2026-07-26 06:28 UTC.

## Bugs

### Remote SSH reliability (44)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | [#317348](https://github.com/microsoft/vscode/issues/317348) | SSH to windows host: VS Code Server failed to start | 9 | correctness | 2/6 Unverified | 100 | — | — |
| 5 | [#309064](https://github.com/microsoft/vscode/issues/309064) | Window keeps closing after ssh connection | 5 | crash | 3/6 Plausible | 50 | — | — |
| 7 | [#326093](https://github.com/microsoft/vscode/issues/326093) | VSCode cannot open SSH workspace | 1 | correctness | 2/6 Unverified | 47 | — | — |
| 16 | [#249861](https://github.com/microsoft/vscode/issues/249861) | Restoring multiple SSH workspaces fails when restoring more than one workspace | 2 | correctness | 6/6 Confirmed | 32 | — | `npm run implement -- --issue 249861` |
| 17 | [#280104](https://github.com/microsoft/vscode/issues/280104) | terminal profile can't resolve `${workspaceFolder}` in vscode remote workspaces | 0 | correctness | 5/6 Source-confirmed | 32 | — | `npm run implement -- --issue 280104` |
| 18 | [#212410](https://github.com/microsoft/vscode/issues/212410) | remote extension host terminated unexpectedly | 2 | crash | 3/6 Plausible | 31 | — | — |
| 19 | [#324188](https://github.com/microsoft/vscode/issues/324188) | Remote SSH:  oom Issue in versions newer than 1.120.0 when connected via ssh | 2 | perf | 3/6 Plausible | 30 | — | `npm run implement -- --issue 324188` |
| 21 | [#317635](https://github.com/microsoft/vscode/issues/317635) | unable to ssh connect to server's workspace after the most recent update | 3 | correctness | 3/6 Plausible | 29 | — | — |
| 25 | [#274774](https://github.com/microsoft/vscode/issues/274774) | Remote SSH connection fails to reconnect after system sleep or network connection change | 0 | correctness | 3/6 Plausible | 26 | — | — |
| 30 | [#249446](https://github.com/microsoft/vscode/issues/249446) | Multiple remote connections fail after VSCode update | 1 | correctness | — | 23 | — | — |
| 41 | [#283833](https://github.com/microsoft/vscode/issues/283833) | Remote Host WSL Disconnect | 0 | correctness | — | 19 | — | — |
| 43 | [#306357](https://github.com/microsoft/vscode/issues/306357) | Preferences: Open User Settings (JSON) opens in a new local window instead of the current Remote SSH window (regression in 1.99) | 2 | correctness | 4/6 Traced | 18 | — | `npm run implement -- --issue 306357` |
| 44 | [#268314](https://github.com/microsoft/vscode/issues/268314) | vscode keeps recursively asking me for my password | 0 | correctness | 3/6 Plausible | 18 | — | — |
| 52 | [#317445](https://github.com/microsoft/vscode/issues/317445) | Agents view fails to connect to SSH hosts using ProxyJump, while main editor's SSH works | 1 | correctness | 5/6 Source-confirmed | 14 | — | `npm run implement -- --issue 317445` |
| 56 | [#325872](https://github.com/microsoft/vscode/issues/325872) | VS Code Remote Server Update: Incomplete node_modules Installation | 0 | correctness | 3/6 Plausible | 14 | — | `npm run implement -- --issue 325872` |
| 59 | [#286384](https://github.com/microsoft/vscode/issues/286384) | Opening recent folder via SSH fails without arcane magic | 1 | none | — | 13 | — | — |
| 71 | [#212449](https://github.com/microsoft/vscode/issues/212449) | Pty Host Issue since latest update (VSCode 1.89.1), SSH and Remote development functionality is broken | 0 | correctness | 3/6 Plausible | 12 | — | — |
| 75 | [#298908](https://github.com/microsoft/vscode/issues/298908) | Remote Explorer is acting strange. | 0 | correctness | 2/6 Unverified | 12 | — | — |
| 81 | [#282771](https://github.com/microsoft/vscode/issues/282771) | Remote SSH connect timeout possibly due to Workspace Security Prompt | 0 | correctness | 3/6 Plausible | 11 | — | `npm run implement -- --issue 282771` |
| 85 | [#256201](https://github.com/microsoft/vscode/issues/256201) | VSCode Remote SSH Server Running On Port 8000 Blocking Other Apps | 1 | correctness | 2/6 Unverified | 10 | — | — |
| 96 | [#236668](https://github.com/microsoft/vscode/issues/236668) | SSH agent forwarding breaks when I open a workspace. | 0 | correctness | 3/6 Plausible | 9 | — | — |
| 101 | [#283032](https://github.com/microsoft/vscode/issues/283032) | After upgrading to the latest version 1.107.0, WSL cannot be connected normally via SSH | 0 | none | — | 9 | — | — |
| 104 | [#294893](https://github.com/microsoft/vscode/issues/294893) | SSH connection is reconnecting state | 2 | none | — | 8 | — | — |
| 106 | [#318914](https://github.com/microsoft/vscode/issues/318914) | Remote SSH: Connection times out in VS Code while terminal SSH works — macOS Tahoe, Insiders 1.122.0 | 1 | correctness | — | 8 | — | — |
| 110 | [#325534](https://github.com/microsoft/vscode/issues/325534) | Agent view and SSH-Connections | 1 | correctness | 3/6 Plausible | 7 | — | — |
| 111 | [#325647](https://github.com/microsoft/vscode/issues/325647) | Agents window: SSH fails with "no matching host key format" on hosts using OpenSSH host certificates | 1 | correctness | 5/6 Source-confirmed | 7 | — | `npm run implement -- --issue 325647` |
| 168 | [#313143](https://github.com/microsoft/vscode/issues/313143) | SSH connection | 0 | correctness | 3/6 Plausible | 3 | — | `npm run implement -- --issue 313143` |
| 188 | [#320422](https://github.com/microsoft/vscode/issues/320422) | Remote-SSH 0.107.1 breaks on macOS due to Unix socket path exceeding 104-char limit | 0 | correctness | — | 2 | — | — |
| 193 | [#323392](https://github.com/microsoft/vscode/issues/323392) | retrieval of remote server fails | 0 | none | — | 2 | — | — |
| 198 | [#327087](https://github.com/microsoft/vscode/issues/327087) | VS Code SSH problem | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 227 | [#270617](https://github.com/microsoft/vscode/issues/270617) | VS Code looks for local paths during remote sessions | 0 | none | — | 0 | — | — |
| 237 | [#284926](https://github.com/microsoft/vscode/issues/284926) | vscode auto-upgrade messes up ssh connection everytime it activates at the background. | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 252 | [#294336](https://github.com/microsoft/vscode/issues/294336) | VSCode Server is being downloaded in all remote sessions after upgrading VS Code to a new version | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 257 | [#296929](https://github.com/microsoft/vscode/issues/296929) | Doesn't respond when running on ssh | 0 | none | 3/6 Plausible | 0 | — | — |
| 264 | [#302120](https://github.com/microsoft/vscode/issues/302120) | The workbench failed to connect to the server (Error: exception was thrown by handler. exception: failed to start vs code remote server.) | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 269 | [#310952](https://github.com/microsoft/vscode/issues/310952) | ssh: Refused to connect to unsupported server | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 270 | [#312303](https://github.com/microsoft/vscode/issues/312303) | Remote connection locks other windows | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 275 | [#314065](https://github.com/microsoft/vscode/issues/314065) | vscode remote-cli ssh executable does NOT accept --user-data-dir switch | 0 | papercut | 5/6 Source-confirmed | 0 | — | — |
| 295 | [#317487](https://github.com/microsoft/vscode/issues/317487) | Backgrounded VSCode window throttles integrated terminal and Remote-SSH processes on Windows | 0 | perf | 3/6 Plausible | 0 | — | — |
| 308 | [#320713](https://github.com/microsoft/vscode/issues/320713) | SSH reconnection asks for passphrase even when SSH agent is present | 0 | none | — | 0 | — | — |
| 316 | [#322556](https://github.com/microsoft/vscode/issues/322556) | WSL2 Remote-SSH: "Failed to set up dynamic port forwarding over SSH" (works correctly <= 1.122.1) | 0 | correctness | — | 0 | — | — |
| 320 | [#324870](https://github.com/microsoft/vscode/issues/324870) | [Agents window] prompts for SSH key passphrase despite `PubkeyAuthentication no` | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 324870` |
| 322 | [#325721](https://github.com/microsoft/vscode/issues/325721) | Agent host SSH: 'Update Server' is a silent no-op (or downgrades) while update API lags the desktop rollout — protocol-version deadlock with no recovery path | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 325721` |
| 330 | [#327469](https://github.com/microsoft/vscode/issues/327469) | SSH session fails to connect with "uname is not recognized as a name or cmdlet" when connecting to Windows 11 host | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 327469` |

### Chat session state (53)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2 | [#320335](https://github.com/microsoft/vscode/issues/320335) | Can't turn on Chat Session Sync (`chat.sessionSync.enabled`) | 4 | correctness | 5/6 Source-confirmed | 59 | — | `npm run implement -- --issue 320335` |
| 15 | [#288269](https://github.com/microsoft/vscode/issues/288269) | Incorrect `Sessions in progress` | 0 | correctness | 3/6 Plausible | 34 | — | `npm run implement -- --issue 288269` |
| 20 | [#302887](https://github.com/microsoft/vscode/issues/302887) | Renamed chat reverts when chat is selected from sessions | 0 | correctness | 6/6 Confirmed | 30 | — | — |
| 23 | [#261708](https://github.com/microsoft/vscode/issues/261708) | Broken chat history after working with a single chat in both view and editor | 0 | correctness | 3/6 Plausible | 28 | — | `npm run implement -- --issue 261708` |
| 26 | [#286250](https://github.com/microsoft/vscode/issues/286250) | Kicking off multiple agent sessions sometimes leads to freezing or delay in agent sessions list | 0 | correctness | 6/6 Confirmed | 26 | — | `npm run implement -- --issue 286250` |
| 32 | [#318956](https://github.com/microsoft/vscode/issues/318956) | GHCP Renaming Sessions Appears to have a bug | 2 | correctness | 4/6 Traced | 22 | — | `npm run implement -- --issue 318956` |
| 33 | [#286797](https://github.com/microsoft/vscode/issues/286797) | Different cloud session titles in Agent Sessions vs chat tab | 0 | correctness | 5/6 Source-confirmed | 22 | yes | `npm run implement -- --issue 286797` |
| 38 | [#314799](https://github.com/microsoft/vscode/issues/314799) | [BUG] Workspaces: Github Copilot chat session history disappeared after adding a folder to workspace then restarting VSCode | 2 | data-loss | 6/6 Confirmed | 20 | — | — |
| 47 | [#285198](https://github.com/microsoft/vscode/issues/285198) | Copilot Conversation Unintentionally Erased | 0 | data-loss | 3/6 Plausible | 17 | — | — |
| 55 | [#316929](https://github.com/microsoft/vscode/issues/316929) | Copilot Chat: chat session deletion is intermittent | 0 | correctness | 3/6 Plausible | 14 | — | — |
| 60 | [#281655](https://github.com/microsoft/vscode/issues/281655) | Agent Sessions: onDidChangeChatSessionItems not firing on refresh | 0 | perf | 2/6 Unverified | 13 | — | `npm run implement -- --issue 281655` |
| 61 | [#288297](https://github.com/microsoft/vscode/issues/288297) | Chat sessions shows duplicated cloud session | 0 | visual | 3/6 Plausible | 13 | — | `npm run implement -- --issue 288297` |
| 62 | [#291426](https://github.com/microsoft/vscode/issues/291426) | Codex sessions still appear in sessions list after uninstalling Codex | 0 | correctness | 5/6 Source-confirmed | 13 | — | `npm run implement -- --issue 291426` |
| 64 | [#307565](https://github.com/microsoft/vscode/issues/307565) | Session History List Disappears, Making Previous Sessions Inaccessible | 0 | correctness | 5/6 Source-confirmed | 13 | — | `npm run implement -- --issue 307565` |
| 69 | [#316393](https://github.com/microsoft/vscode/issues/316393) | Chat renaming not persisting | 1 | correctness | 5/6 Source-confirmed | 12 | yes | `npm run implement -- --issue 316393` |
| 92 | [#281223](https://github.com/microsoft/vscode/issues/281223) | Background/Cloud chats are not restored in sidebar after reload/restart | 0 | correctness | 5/6 Source-confirmed | 10 | — | `npm run implement -- --issue 281223` |
| 103 | [#296749](https://github.com/microsoft/vscode/issues/296749) | cant open my chat session | 3 | none | 3/6 Plausible | 8 | — | — |
| 109 | [#322884](https://github.com/microsoft/vscode/issues/322884) | Occasionally, chat sessions won't open | 1 | correctness | 3/6 Plausible | 7 | — | — |
| 125 | [#282345](https://github.com/microsoft/vscode/issues/282345) | Cloud agent titles between session list and chat title don't match | 0 | visual | 3/6 Plausible | 6 | — | `npm run implement -- --issue 282345` |
| 133 | [#269039](https://github.com/microsoft/vscode/issues/269039) | Duplicate Claude Code sessions | 0 | visual | 3/6 Plausible | 5 | — | `npm run implement -- --issue 269039` |
| 177 | [#288430](https://github.com/microsoft/vscode/issues/288430) | Two unread session for one remove session | 0 | visual | 3/6 Plausible | 2 | — | `npm run implement -- --issue 288430` |
| 179 | [#291525](https://github.com/microsoft/vscode/issues/291525) | Remote session doesn't show the prompt I typed | 0 | correctness | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 291525` |
| 183 | [#317478](https://github.com/microsoft/vscode/issues/317478) | Chat session cannot be opened - log/transcript missing an initial entry | 0 | correctness | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 317478` |
| 194 | [#325731](https://github.com/microsoft/vscode/issues/325731) | cannot rename session name | 0 | none | 3/6 Plausible | 2 | — | — |
| 207 | [#292776](https://github.com/microsoft/vscode/issues/292776) | Incorrect previous cloud session is opened after delegation | 0 | correctness | 3/6 Plausible | 1 | — | `npm run implement -- --issue 292776` |
| 220 | [#319863](https://github.com/microsoft/vscode/issues/319863) | Setting `chat.sessionSync.enabled` didn't update info hover until I restarted | 0 | papercut | 4/6 Traced | 1 | — | `npm run implement -- --issue 319863` |
| 230 | [#275280](https://github.com/microsoft/vscode/issues/275280) | Chat session picker: Custom agent doesn't appear from non-main branch | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 275280` |
| 232 | [#281165](https://github.com/microsoft/vscode/issues/281165) | Unpredictable mode/model when cmd+n from an existing session | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 281165` |
| 236 | [#284196](https://github.com/microsoft/vscode/issues/284196) | Implementing a plan leads to unhelpful session title | 0 | papercut | 2/6 Unverified | 0 | — | — |
| 240 | [#288122](https://github.com/microsoft/vscode/issues/288122) | Session Initializing… message won't dissappear from VSC UI for abandoned job | 0 | visual | 4/6 Traced | 0 | — | `npm run implement -- --issue 288122` |
| 242 | [#289391](https://github.com/microsoft/vscode/issues/289391) | Chat session name is way off | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 289391` |
| 249 | [#292425](https://github.com/microsoft/vscode/issues/292425) | Agent Sessions: Archiving the current session doesn't reset when its currently active | 0 | papercut | 2/6 Unverified | 0 | — | `npm run implement -- --issue 292425` |
| 267 | [#309300](https://github.com/microsoft/vscode/issues/309300) | serializing chat session for storage | 0 | data-loss | 2/6 Unverified | 0 | — | — |
| 268 | [#310586](https://github.com/microsoft/vscode/issues/310586) | Copilot Chat sessions in a window with no folder/workspace open do not show local sessions from folder workspaces, despite docs saying the list shows all sessions across workspaces | 0 | correctness | 4/6 Traced | 0 | — | `npm run implement -- --issue 310586` |
| 271 | [#312694](https://github.com/microsoft/vscode/issues/312694) | Chat session widget gets stuck after going back | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 312694` |
| 274 | [#314048](https://github.com/microsoft/vscode/issues/314048) | Very long session description | 0 | visual | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 314048` |
| 279 | [#314297](https://github.com/microsoft/vscode/issues/314297) | Unscrapped prompt leaked into the session title | 0 | correctness | 4/6 Traced | 0 | — | `npm run implement -- --issue 314297` |
| 282 | [#315161](https://github.com/microsoft/vscode/issues/315161) | RangeError: Invalid string length when serializing Copilot chat session | 0 | data-loss | 2/6 Unverified | 0 | — | — |
| 283 | [#315315](https://github.com/microsoft/vscode/issues/315315) | copilot chat session errors | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 284 | [#315763](https://github.com/microsoft/vscode/issues/315763) | How did I get a new session grouped under `unknown` in the agents window? | 0 | visual | 4/6 Traced | 0 | — | `npm run implement -- --issue 315763` |
| 287 | [#316345](https://github.com/microsoft/vscode/issues/316345) | Session records that cannot be deleted come from codex and claude code plug-ins. | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 288 | [#316406](https://github.com/microsoft/vscode/issues/316406) | Copilot chats in history get lost randomly | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 289 | [#316562](https://github.com/microsoft/vscode/issues/316562) | Copilot cannot restore session memory | 0 | data-loss | 2/6 Unverified | 0 | — | — |
| 294 | [#317061](https://github.com/microsoft/vscode/issues/317061) | Copilot Chat Conversation Title Will Not Persist | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 298 | [#317930](https://github.com/microsoft/vscode/issues/317930) | Error serializing chat session for storage. | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 301 | [#319278](https://github.com/microsoft/vscode/issues/319278) | Chat: Custom session titles are lost after extension update / index rebuild | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 305 | [#319757](https://github.com/microsoft/vscode/issues/319757) | Session time stamp off by 9 hours (Redmond time instead of local time?) | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 319757` |
| 306 | [#320373](https://github.com/microsoft/vscode/issues/320373) | Agent Window: constant errors from old sessions | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 320373` |
| 313 | [#321469](https://github.com/microsoft/vscode/issues/321469) | orphaned agent window session created when marked done too early | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 321469` |
| 325 | [#326320](https://github.com/microsoft/vscode/issues/326320) | Renaming Copilot Chat Sessions Doesn't Stick | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 326320` |
| 326 | [#326732](https://github.com/microsoft/vscode/issues/326732) | Failed to import session from cloud | 0 | none | 3/6 Plausible | 0 | — | — |
| 327 | [#327364](https://github.com/microsoft/vscode/issues/327364) | [Bug] `chat.sessionSync.enabled` cannot be enabled in `1.131.0-insider`, due to purported organisation-instituted restrictions, despite no organisational accounts added. | 0 | correctness | 6/6 Confirmed | 0 | — | — |
| 328 | [#327396](https://github.com/microsoft/vscode/issues/327396) | Cloud Session Sync | 0 | correctness | 4/6 Traced | 0 | — | `npm run implement -- --issue 327396` |

### Repository and worktree (7)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 3 | [#279679](https://github.com/microsoft/vscode/issues/279679) | Failed to find pull request | 1 | correctness | 4/6 Traced | 57 | — | `npm run implement -- --issue 279679` |
| 97 | [#259724](https://github.com/microsoft/vscode/issues/259724) | Coding agent integration tries to create changes on a PR that doesn't exist | 0 | correctness | 3/6 Plausible | 9 | — | `npm run implement -- --issue 259724` |
| 127 | [#286936](https://github.com/microsoft/vscode/issues/286936) | checkout not checking out correct repo | 0 | correctness | — | 6 | — | `npm run implement -- --issue 286936` |
| 145 | [#325817](https://github.com/microsoft/vscode/issues/325817) | Agents Window: non-sensical auto-generated worktree & branch names | 0 | correctness | 2/6 Unverified | 5 | — | — |
| 276 | [#314142](https://github.com/microsoft/vscode/issues/314142) | agents app, package-lock generation causes large line change count that doesn't show in changes | 0 | visual | 4/6 Traced | 0 | — | `npm run implement -- --issue 314142` |
| 281 | [#315035](https://github.com/microsoft/vscode/issues/315035) | Github Copilot confused by file states and user prompted with "Failed to save XY: The content of the file is newer" | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 315035` |
| 293 | [#316940](https://github.com/microsoft/vscode/issues/316940) | Agent Host Incorrectly Constructs Git Worktree Path, Creating Directory in Wrong Location | 0 | correctness | 4/6 Traced | 0 | yes | `npm run implement -- --issue 316940` |

### Agent delegation flow (23)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 6 | [#292398](https://github.com/microsoft/vscode/issues/292398) | Can't delegate to agent from TODO lightbulb | 6 | correctness | 2/6 Unverified | 48 | — | — |
| 11 | [#296407](https://github.com/microsoft/vscode/issues/296407) | Loop of delegating plan to background agent | 0 | correctness | 3/6 Plausible | 38 | — | `npm run implement -- --issue 296407` |
| 13 | [#270672](https://github.com/microsoft/vscode/issues/270672) | Remote agent picks incorrect repo from workspace with multiple repos | 3 | correctness | 4/6 Traced | 34 | yes | `npm run implement -- --issue 270672` |
| 24 | [#289632](https://github.com/microsoft/vscode/issues/289632) | Bug: Cloud agent handoff fail (GHE or account-related) | 0 | correctness | 3/6 Plausible | 27 | — | — |
| 54 | [#300618](https://github.com/microsoft/vscode/issues/300618) | cloud delegation fail from codespaces | 0 | correctness | 3/6 Plausible | 14 | — | — |
| 67 | [#293258](https://github.com/microsoft/vscode/issues/293258) | `@cloud Start implementation` triggered a Cloud Agent session on the wrong repo! | 2 | correctness | 4/6 Traced | 12 | — | `npm run implement -- --issue 293258` |
| 77 | [#282283](https://github.com/microsoft/vscode/issues/282283) | Background agent assignment failed | 2 | correctness | 3/6 Plausible | 11 | — | — |
| 78 | [#303677](https://github.com/microsoft/vscode/issues/303677) | "Delegate to cloud agent" uses wrong branch | 1 | correctness | 5/6 Source-confirmed | 11 | — | `npm run implement -- --issue 303677` |
| 89 | [#276758](https://github.com/microsoft/vscode/issues/276758) | Tried to apply changes but they were pulled from the wrong repo | 0 | correctness | 3/6 Plausible | 10 | — | `npm run implement -- --issue 276758` |
| 91 | [#280180](https://github.com/microsoft/vscode/issues/280180) | Delegate to Copilot is confused when its meant to focus on suggested next steps after a task | 0 | correctness | 3/6 Plausible | 10 | — | `npm run implement -- --issue 280180` |
| 113 | [#290975](https://github.com/microsoft/vscode/issues/290975) | no agent listed post sendoff | 0 | visual | 6/6 Confirmed | 7 | — | `npm run implement -- --issue 290975` |
| 151 | [#295599](https://github.com/microsoft/vscode/issues/295599) | Cloud agent does not work with GHE account | 0 | correctness | 3/6 Plausible | 4 | — | `npm run implement -- --issue 295599` |
| 152 | [#296899](https://github.com/microsoft/vscode/issues/296899) | Delegate to cloud agent always creates a PR to main/master, ignoring the currently checked-out branch | 0 | correctness | 5/6 Source-confirmed | 4 | yes | `npm run implement -- --issue 296899` |
| 175 | [#280925](https://github.com/microsoft/vscode/issues/280925) | Delegate to cloud doesn't work | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 176 | [#281798](https://github.com/microsoft/vscode/issues/281798) | deligate to cloud fails | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 180 | [#296289](https://github.com/microsoft/vscode/issues/296289) | Handoffs deletes previous conversion and context | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 209 | [#297057](https://github.com/microsoft/vscode/issues/297057) | Cloud exectution used old chat history instead of plan mode prompt. | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 212 | [#307235](https://github.com/microsoft/vscode/issues/307235) | Copilot Chat randomly switched to Cloud Agent | 0 | correctness | 3/6 Plausible | 1 | — | `npm run implement -- --issue 307235` |
| 216 | [#311551](https://github.com/microsoft/vscode/issues/311551) | [Error] chatagenterror-Failed to find pull request #605 after delegation. | 0 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 311551` |
| 273 | [#313643](https://github.com/microsoft/vscode/issues/313643) | [Agents] Checkout seems to mix up repositories | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 291 | [#316677](https://github.com/microsoft/vscode/issues/316677) | Agents window: after delegating to a Cloud session, it appears that nothing happened | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 316677` |
| 292 | [#316869](https://github.com/microsoft/vscode/issues/316869) | Agents: New session defaults to the wrong branch | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 316869` |
| 323 | [#325732](https://github.com/microsoft/vscode/issues/325732) | Copilot Agents fails to start sessions with `GitHubLoginFailed` and `Timed out waiting for session commit` | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 325732` |

### Remote tunnels and web (8)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 8 | [#312113](https://github.com/microsoft/vscode/issues/312113) | Remote Tunnels: 401 Unauthorized with Microsoft Account - "Anonymous has scopes []" | 1 | correctness | 5/6 Source-confirmed | 46 | — | `npm run implement -- --issue 312113` |
| 37 | [#308839](https://github.com/microsoft/vscode/issues/308839) | WebSocket close with status code 1006) | 2 | correctness | 3/6 Plausible | 20 | — | — |
| 129 | [#310887](https://github.com/microsoft/vscode/issues/310887) | Remote SSH + Remote Tunnel = Failed tunnel on wrong machine | 0 | correctness | 4/6 Traced | 6 | — | `npm run implement -- --issue 310887` |
| 144 | [#322248](https://github.com/microsoft/vscode/issues/322248) | Remote tunnel gets enabled but hangs on start. | 0 | papercut | 3/6 Plausible | 5 | — | — |
| 147 | [#172743](https://github.com/microsoft/vscode/issues/172743) | Cannot Continue On from Tunnels in vscode.dev to Codespaces | 0 | correctness | 3/6 Plausible | 4 | — | `npm run implement -- --issue 172743` |
| 148 | [#239529](https://github.com/microsoft/vscode/issues/239529) | When using "Open File on Remote From" the code lines selected are not preserved | 0 | papercut | 5/6 Source-confirmed | 4 | yes | `npm run implement -- --issue 239529` |
| 225 | [#244043](https://github.com/microsoft/vscode/issues/244043) | Support `downloadExtensionsLocally` in bulk extension install APIs, when in remote | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 244043` |
| 226 | [#253053](https://github.com/microsoft/vscode/issues/253053) | Devcontainer creation fails | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 253053` |

### Agent window UX (48)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 9 | [#314342](https://github.com/microsoft/vscode/issues/314342) | cli.js Automatically opening when running Agent | 4 | correctness | 2/6 Unverified | 44 | — | — |
| 86 | [#312254](https://github.com/microsoft/vscode/issues/312254) | Agents: Plan doesn't show up as a custom agent type | 1 | correctness | 3/6 Plausible | 10 | — | `npm run implement -- --issue 312254` |
| 87 | [#325319](https://github.com/microsoft/vscode/issues/325319) | Discarding changes doesn't work in Agents Window | 1 | correctness | 4/6 Traced | 10 | — | `npm run implement -- --issue 325319` |
| 88 | [#275077](https://github.com/microsoft/vscode/issues/275077) | Creating a Claude Code session from the Agent Sessions view has a "no such agent" error | 0 | correctness | 3/6 Plausible | 10 | — | `npm run implement -- --issue 275077` |
| 94 | [#290949](https://github.com/microsoft/vscode/issues/290949) | Send to agent appears shortly after typing in agent sessions/command center | 0 | visual | 2/6 Unverified | 10 | — | `npm run implement -- --issue 290949` |
| 95 | [#291160](https://github.com/microsoft/vscode/issues/291160) | Agent Status toggle applies to all windows | 0 | correctness | 5/6 Source-confirmed | 10 | yes | `npm run implement -- --issue 291160` |
| 102 | [#286591](https://github.com/microsoft/vscode/issues/286591) | bad button UI for background agent confirmation | 0 | visual | 3/6 Plausible | 9 | — | `npm run implement -- --issue 286591` |
| 105 | [#304943](https://github.com/microsoft/vscode/issues/304943) | `code-insiders --sessions` sometimes opens VS Code instead of Sessions App | 1 | correctness | 3/6 Plausible | 8 | — | `npm run implement -- --issue 304943` |
| 114 | [#311200](https://github.com/microsoft/vscode/issues/311200) | Clicking a row in "customizations" doesn't open that item | 0 | correctness | 6/6 Confirmed | 7 | — | `npm run implement -- --issue 311200` |
| 116 | [#313815](https://github.com/microsoft/vscode/issues/313815) | Agents app customizations editor is blank after swapping back and forth between modal and window view | 0 | visual | 3/6 Plausible | 7 | — | `npm run implement -- --issue 313815` |
| 126 | [#286316](https://github.com/microsoft/vscode/issues/286316) | Chat input - accepting changes shifts the input | 0 | visual | 3/6 Plausible | 6 | — | `npm run implement -- --issue 286316` |
| 130 | [#321320](https://github.com/microsoft/vscode/issues/321320) | Cannot manage agents in the new agents panel | 0 | none | 3/6 Plausible | 6 | — | — |
| 131 | [#313025](https://github.com/microsoft/vscode/issues/313025) | `openManagementEditor` doesn't respect `workbench.editor.useModal: "off"` | 2 | papercut | 2/6 Unverified | 5 | — | — |
| 150 | [#291735](https://github.com/microsoft/vscode/issues/291735) | Delegate button shows background/cloud options when not in a git repository | 0 | papercut | 4/6 Traced | 4 | yes | `npm run implement -- --issue 291735` |
| 153 | [#302661](https://github.com/microsoft/vscode/issues/302661) | Flicker in search bar in new window | 0 | visual | 5/6 Source-confirmed | 4 | — | `npm run implement -- --issue 302661` |
| 154 | [#304187](https://github.com/microsoft/vscode/issues/304187) | troubleshoot built in skill does not show in sessions window | 0 | correctness | 2/6 Unverified | 4 | — | `npm run implement -- --issue 304187` |
| 155 | [#315431](https://github.com/microsoft/vscode/issues/315431) | Copilot Agents (Insiders): "Mark as Done" no-op when session state is missing/stale | 0 | papercut | 4/6 Traced | 4 | — | `npm run implement -- --issue 315431` |
| 156 | [#284738](https://github.com/microsoft/vscode/issues/284738) | Background Session - fix delegation dialog buttons | 1 | visual | 3/6 Plausible | 3 | — | `npm run implement -- --issue 284738` |
| 163 | [#280990](https://github.com/microsoft/vscode/issues/280990) | My assignments not working | 0 | none | 3/6 Plausible | 3 | — | — |
| 167 | [#309437](https://github.com/microsoft/vscode/issues/309437) | Confusing flow when trying to configure customizations from the Agents app | 0 | papercut | 6/6 Confirmed | 3 | — | `npm run implement -- --issue 309437` |
| 181 | [#315202](https://github.com/microsoft/vscode/issues/315202) | CustomizationItemProvider.provideChatSessionCustomizations called multiple times by the aiCustomizationItemsModel | 0 | perf | 2/6 Unverified | 2 | — | `npm run implement -- --issue 315202` |
| 182 | [#316194](https://github.com/microsoft/vscode/issues/316194) | Agents app changes broken | 0 | correctness | 4/6 Traced | 2 | yes | `npm run implement -- --issue 316194` |
| 190 | [#321505](https://github.com/microsoft/vscode/issues/321505) | Menu bar not visible | 0 | none | 3/6 Plausible | 2 | — | — |
| 191 | [#321635](https://github.com/microsoft/vscode/issues/321635) | [Error] unhandlederror-Native addon "runtime" not found for linuxmusl-x64. Tried:   <REDACTED: user-file-pat... | 0 | correctness | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 321635` |
| 204 | [#287852](https://github.com/microsoft/vscode/issues/287852) | Artifacts sometimes don't open in agent view | 0 | correctness | 3/6 Plausible | 1 | — | `npm run implement -- --issue 287852` |
| 206 | [#291091](https://github.com/microsoft/vscode/issues/291091) | The expand button on the "Working" group tab in the cloud agents chat panel is non-functional. | 0 | correctness | 3/6 Plausible | 1 | — | `npm run implement -- --issue 291091` |
| 215 | [#309434](https://github.com/microsoft/vscode/issues/309434) | Can't get back to the list in Agent Customizations by clicking list entry | 0 | papercut | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 309434` |
| 217 | [#312836](https://github.com/microsoft/vscode/issues/312836) | Agents scope selector should always show `select folder` | 0 | papercut | 4/6 Traced | 1 | yes | `npm run implement -- --issue 312836` |
| 251 | [#293435](https://github.com/microsoft/vscode/issues/293435) | Agent title controls not looking good in certain theme configs | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 293435` |
| 254 | [#295525](https://github.com/microsoft/vscode/issues/295525) | Can not click dropdownlist after "move chat into New window" in chat session | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 295525` |
| 258 | [#297258](https://github.com/microsoft/vscode/issues/297258) | Focus not properly rendered on the last item in the list of Chat Customisations | 0 | visual | 2/6 Unverified | 0 | — | `npm run implement -- --issue 297258` |
| 262 | [#297529](https://github.com/microsoft/vscode/issues/297529) | weird escape behavior when command palette and modal | 0 | papercut | 4/6 Traced | 0 | — | `npm run implement -- --issue 297529` |
| 263 | [#297530](https://github.com/microsoft/vscode/issues/297530) | chat customizations is not keyboard focusable at all | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 297530` |
| 265 | [#303364](https://github.com/microsoft/vscode/issues/303364) | Delegation options linger after taking action on plan | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 303364` |
| 266 | [#307413](https://github.com/microsoft/vscode/issues/307413) | Command Center bar getting autoselected when vs code starts | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 278 | [#314168](https://github.com/microsoft/vscode/issues/314168) | Agents app modals have unexpected tab behavior in MacOS | 0 | papercut | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 314168` |
| 285 | [#315772](https://github.com/microsoft/vscode/issues/315772) | Agents `changes` tab lists files from parent git repo with poor UI | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 315772` |
| 297 | [#317768](https://github.com/microsoft/vscode/issues/317768) | "New Session" button doesn't work | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 302 | [#319343](https://github.com/microsoft/vscode/issues/319343) | Entries are getting cut off in Agent Customizations view | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 319343` |
| 303 | [#319375](https://github.com/microsoft/vscode/issues/319375) | Clicking on customizations in Agents window doesn't take me to the specific customization | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 319375` |
| 309 | [#320811](https://github.com/microsoft/vscode/issues/320811) | Agents: Folder/worktree picker menu always shows Folder as selected | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 320811` |
| 311 | [#321322](https://github.com/microsoft/vscode/issues/321322) | Chat Customization: last items in lists are clipped and not visible | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 321322` |
| 314 | [#321470](https://github.com/microsoft/vscode/issues/321470) | cannot ctrl+f to find in settings json within agents window | 0 | correctness | 4/6 Traced | 0 | — | `npm run implement -- --issue 321470` |
| 315 | [#321579](https://github.com/microsoft/vscode/issues/321579) | agent app customization view is cutoff | 0 | visual | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 321579` |
| 317 | [#324107](https://github.com/microsoft/vscode/issues/324107) | Agent window session in a new worktree doesn't open editor in the worktree location immediately | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 318 | [#324142](https://github.com/microsoft/vscode/issues/324142) | Overview isn't highlighted in Agent Customizations | 0 | visual | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 324142` |
| 321 | [#325059](https://github.com/microsoft/vscode/issues/325059) | Cannot select 'New Session' from command palette when viewing a file full screen in Agents Window | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 325059` |
| 329 | [#327453](https://github.com/microsoft/vscode/issues/327453) | AI agent | 0 | correctness | 3/6 Plausible | 0 | — | — |

### Customizations and policy (22)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 10 | [#280720](https://github.com/microsoft/vscode/issues/280720) | `chat.tools.eligibleForAutoApproval` setting doesn't work with tools from extensions | 1 | correctness | 5/6 Source-confirmed | 40 | yes | `npm run implement -- --issue 280720` |
| 39 | [#245540](https://github.com/microsoft/vscode/issues/245540) | Disable the dependency extension installation | 0 | correctness | 3/6 Plausible | 20 | — | `npm run implement -- --issue 245540` |
| 40 | [#281128](https://github.com/microsoft/vscode/issues/281128) | Disable custom agents when agent mode is disabled via policy | 0 | correctness | 2/6 Unverified | 20 | — | `npm run implement -- --issue 281128` |
| 57 | [#317324](https://github.com/microsoft/vscode/issues/317324) | Warning about restricted AI features shows up even with chat.disableAIFeatures=true | 6 | papercut | 5/6 Source-confirmed | 13 | yes | `npm run implement -- --issue 317324` |
| 70 | [#319926](https://github.com/microsoft/vscode/issues/319926) | enabledPlugins is too strict | 1 | correctness | 2/6 Unverified | 12 | — | — |
| 146 | [#298915](https://github.com/microsoft/vscode/issues/298915) | [Settings] Lost configuration key or its description for `chat.commandCenter.enabled` | 1 | papercut | 2/6 Unverified | 4 | — | — |
| 159 | [#297399](https://github.com/microsoft/vscode/issues/297399) | "Browse MCP Servers" opens marketplace in background and doesn't dismiss the modal | 1 | papercut | 5/6 Source-confirmed | 3 | yes | `npm run implement -- --issue 297399` |
| 165 | [#290958](https://github.com/microsoft/vscode/issues/290958) | non-merged agent.md files aren't shown as cloud custom agent | 0 | papercut | 2/6 Unverified | 3 | — | — |
| 173 | [#315405](https://github.com/microsoft/vscode/issues/315405) | Copilot CLI session provider keeps refreshing/logging when CLI is disabled by org policy | 1 | papercut | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 315405` |
| 185 | [#318576](https://github.com/microsoft/vscode/issues/318576) | Agents window: couldn't disable built-in Github mcp server in agents customization. | 0 | papercut | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 318576` |
| 186 | [#318980](https://github.com/microsoft/vscode/issues/318980) | npm run export-policy-data is not reliable | 0 | correctness | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 318980` |
| 189 | [#320427](https://github.com/microsoft/vscode/issues/320427) | AI Customizations impacting harnesses they should not | 0 | correctness | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 320427` |
| 200 | [#254526](https://github.com/microsoft/vscode/issues/254526) | Policy parser does not support `markdownDescription` | 0 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 254526` |
| 205 | [#290956](https://github.com/microsoft/vscode/issues/290956) | new agent requires reload | 0 | correctness | — | 1 | — | `npm run implement -- --issue 290956` |
| 260 | [#297290](https://github.com/microsoft/vscode/issues/297290) | Customization editor: Unable to see the last line of the editor | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 297290` |
| 261 | [#297397](https://github.com/microsoft/vscode/issues/297397) | New customization works differently in modal vs command | 0 | correctness | — | 0 | — | `npm run implement -- --issue 297397` |
| 272 | [#313493](https://github.com/microsoft/vscode/issues/313493) | Enterprise-managed MCP server tools silently disappear after network transition — no automatic token re-acquisition | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 313493` |
| 277 | [#314155](https://github.com/microsoft/vscode/issues/314155) | "list Plugins 1 item" read before reading the actual list content? | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 314155` |
| 286 | [#316285](https://github.com/microsoft/vscode/issues/316285) | Agents: Slash commands from local Agent Plugin autocomplete correctly but fail to load prompt file content | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 316285` |
| 296 | [#317681](https://github.com/microsoft/vscode/issues/317681) | [REGRESSION] Agent Customizations panel displays all skills as "SKILL / SKILL.md" instead of skill names (v0.50.2026052009) | 0 | visual | 3/6 Plausible | 0 | — | — |
| 299 | [#318005](https://github.com/microsoft/vscode/issues/318005) | Customizations loader doesn't validate path or available file system provider | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 318005` |
| 304 | [#319461](https://github.com/microsoft/vscode/issues/319461) | Error messages pop up as I search for plugs in Agents Customizations with managed settings enabled | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 319461` |

### Performance and crashes (16)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 12 | [#295023](https://github.com/microsoft/vscode/issues/295023) | I am getting 4gig core.node.* dumps under my ID | 0 | crash | 6/6 Confirmed | 35 | — | — |
| 14 | [#310384](https://github.com/microsoft/vscode/issues/310384) | VS Code's C:\Users\username\AppData\Roaming\Code\WebStorage\2\CacheStorage folder grows indefinitely and has currently reached over 30GB. | 1 | perf | 5/6 Source-confirmed | 34 | — | — |
| 28 | [#302366](https://github.com/microsoft/vscode/issues/302366) | Remote development becomes extremely laggy when editing files on a remote server | 1 | perf | 3/6 Plausible | 24 | — | — |
| 34 | [#317866](https://github.com/microsoft/vscode/issues/317866) | Multiple vcode server services running after SSH connection. | 0 | perf | — | 22 | — | — |
| 36 | [#312596](https://github.com/microsoft/vscode/issues/312596) | Performance degradation in Diff Editor due to forced reflows during scrolling | 2 | perf | 5/6 Source-confirmed | 21 | — | `npm run implement -- --issue 312596` |
| 76 | [#318635](https://github.com/microsoft/vscode/issues/318635) | Agent Window - Developer Reload Window kills all sessions | 0 | data-loss | 3/6 Plausible | 12 | — | `npm run implement -- --issue 318635` |
| 107 | [#250674](https://github.com/microsoft/vscode/issues/250674) | Remote Extension Host Terminated Unexpectedly When Not Connected to the Internet | 0 | correctness | 3/6 Plausible | 8 | — | — |
| 108 | [#296096](https://github.com/microsoft/vscode/issues/296096) | UI Crash/State Deletion in Plan Mode | 0 | correctness | 5/6 Source-confirmed | 8 | yes | `npm run implement -- --issue 296096` |
| 119 | [#314775](https://github.com/microsoft/vscode/issues/314775) | VS Code leaks TCP connections to Ollama endpoint via SSH tunnel, causing silent task failures | 1 | correctness | 3/6 Plausible | 6 | — | — |
| 143 | [#318383](https://github.com/microsoft/vscode/issues/318383) | Can't exit when "Cannot reconnect. Please reload the window." dialogue shown | 0 | correctness | 4/6 Traced | 5 | — | `npm run implement -- --issue 318383` |
| 169 | [#318665](https://github.com/microsoft/vscode/issues/318665) | VS Code window keep crashing | 0 | crash | 3/6 Plausible | 3 | — | — |
| 170 | [#318678](https://github.com/microsoft/vscode/issues/318678) | Afer update newer VS code, it always report  terminated unexpectedly | 0 | crash | 3/6 Plausible | 3 | — | — |
| 174 | [#263528](https://github.com/microsoft/vscode/issues/263528) | Resizing chat session editors is choppy | 0 | perf | 3/6 Plausible | 2 | — | `npm run implement -- --issue 263528` |
| 213 | [#307586](https://github.com/microsoft/vscode/issues/307586) | long preparing process | 0 | none | 3/6 Plausible | 1 | — | — |
| 221 | [#320916](https://github.com/microsoft/vscode/issues/320916) | Remote connection locks other windows | 0 | none | — | 1 | — | — |
| 324 | [#325852](https://github.com/microsoft/vscode/issues/325852) | Agents window: renderer SIGTRAP crash after remote agent-host reconnect storms (4× same stack in 14h); streaming turn left permanently blank after reconnect | 0 | crash | 3/6 Plausible | 0 | — | `npm run implement -- --issue 325852` |

### Chat editor UX (30)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 48 | [#236302](https://github.com/microsoft/vscode/issues/236302) | Command Center should shrink when not enough space | 1 | visual | 5/6 Source-confirmed | 16 | yes | `npm run implement -- --issue 236302` |
| 50 | [#281476](https://github.com/microsoft/vscode/issues/281476) | Chat editors have mutating `editor.resource` property | 0 | correctness | 5/6 Source-confirmed | 15 | — | `npm run implement -- --issue 281476` |
| 79 | [#264608](https://github.com/microsoft/vscode/issues/264608) | 'Coding agent encountered an error' not displayed in chat session editor | 0 | correctness | 3/6 Plausible | 11 | — | `npm run implement -- --issue 264608` |
| 80 | [#277278](https://github.com/microsoft/vscode/issues/277278) | Delegate to cloud can't open chat editor | 0 | correctness | 3/6 Plausible | 11 | — | `npm run implement -- --issue 277278` |
| 98 | [#261493](https://github.com/microsoft/vscode/issues/261493) | Chat in Editor should have same background as chat in panel | 0 | visual | 5/6 Source-confirmed | 9 | — | `npm run implement -- --issue 261493` |
| 100 | [#270067](https://github.com/microsoft/vscode/issues/270067) | chat sessions: active response handler is unable to make file edits | 0 | correctness | 3/6 Plausible | 9 | — | `npm run implement -- --issue 270067` |
| 124 | [#282120](https://github.com/microsoft/vscode/issues/282120) | Hide `Apply Changes to Workspace` button if there are no changes | 0 | visual | 2/6 Unverified | 6 | — | `npm run implement -- --issue 282120` |
| 128 | [#291415](https://github.com/microsoft/vscode/issues/291415) | I always get the "chat request in progress ..." notification when trying to close a specific workspace | 0 | papercut | 3/6 Plausible | 6 | — | `npm run implement -- --issue 291415` |
| 141 | [#314779](https://github.com/microsoft/vscode/issues/314779) | Customizations list: Tab into list does not visibly focus first entry | 0 | papercut | 2/6 Unverified | 5 | — | `npm run implement -- --issue 314779` |
| 178 | [#290862](https://github.com/microsoft/vscode/issues/290862) | Open inline chat should be disabled when it cannot be opened | 0 | papercut | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 290862` |
| 201 | [#258600](https://github.com/microsoft/vscode/issues/258600) | Coding agent session content changes during scroll | 0 | visual | 3/6 Plausible | 1 | — | `npm run implement -- --issue 258600` |
| 214 | [#308944](https://github.com/microsoft/vscode/issues/308944) | Unable to use Copilot/Local in multiple Chat Editors | 0 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 308944` |
| 229 | [#273451](https://github.com/microsoft/vscode/issues/273451) | Opening chat session from PR description creates full chat editor | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 273451` |
| 231 | [#281060](https://github.com/microsoft/vscode/issues/281060) | unable to stop cloud agent from chat in editor window | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 281060` |
| 233 | [#281166](https://github.com/microsoft/vscode/issues/281166) | Prompt md: continue in ... icon color is reversed | 0 | visual | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 281166` |
| 234 | [#281344](https://github.com/microsoft/vscode/issues/281344) | `View Extension` cutoff when hovering over `Cloud Agent` title in chat output | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 281344` |
| 238 | [#286245](https://github.com/microsoft/vscode/issues/286245) | Handoff shows "continue in cloud" twice | 0 | visual | 2/6 Unverified | 0 | — | `npm run implement -- --issue 286245` |
| 239 | [#286805](https://github.com/microsoft/vscode/issues/286805) | `Proceed from Plan` options persist when cloud agent is working | 0 | visual | 4/6 Traced | 0 | — | `npm run implement -- --issue 286805` |
| 241 | [#288909](https://github.com/microsoft/vscode/issues/288909) | Quick chat overflows actions out of view when model has a long name | 0 | visual | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 288909` |
| 243 | [#290600](https://github.com/microsoft/vscode/issues/290600) | Mismatch between cloud session changed files in chat output vs review | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 290600` |
| 244 | [#290783](https://github.com/microsoft/vscode/issues/290783) | Can't right click in command center after enabling "Agent Quick Input" | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 290783` |
| 245 | [#291015](https://github.com/microsoft/vscode/issues/291015) | Sessions do not load in agent-sessions welcome view without internet | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 291015` |
| 246 | [#291457](https://github.com/microsoft/vscode/issues/291457) | Welcome view closes my MRU picker | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 291457` |
| 247 | [#291519](https://github.com/microsoft/vscode/issues/291519) | Agent status changes bg-color on debug | 0 | visual | 2/6 Unverified | 0 | — | — |
| 250 | [#292999](https://github.com/microsoft/vscode/issues/292999) | Quick access: leading '<' included in search/filter and "Send to agent" when using Sessions shortcut | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 292999` |
| 253 | [#294547](https://github.com/microsoft/vscode/issues/294547) | Clicking on the Unread filter in Command Center filters in all opened VS Code windows | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 294547` |
| 256 | [#296816](https://github.com/microsoft/vscode/issues/296816) | Turning local agent into background agent makes it disappear (=archived) if there are still open questions / answers to give | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 296816` |
| 310 | [#321188](https://github.com/microsoft/vscode/issues/321188) | `Detected unusual line terminators` should not pop up when cursoring through search results | 0 | papercut | 4/6 Traced | 0 | — | `npm run implement -- --issue 321188` |
| 312 | [#321420](https://github.com/microsoft/vscode/issues/321420) | Selecting 200K context size for Claude Sonnet 4.6 has maxPromptTokens: 936000 (1M) | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 319 | [#324691](https://github.com/microsoft/vscode/issues/324691) | [vsCode GithubCoplit extension] Cancel Loop | 0 | none | 3/6 Plausible | 0 | — | — |

### Copilot CLI agents (15)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 49 | [#301977](https://github.com/microsoft/vscode/issues/301977) | Claude pickers unexpected | 1 | visual | — | 15 | — | — |
| 53 | [#299564](https://github.com/microsoft/vscode/issues/299564) | Claude input pickers should not be one single action item | 0 | visual | 5/6 Source-confirmed | 14 | — | `npm run implement -- --issue 299564` |
| 72 | [#263312](https://github.com/microsoft/vscode/issues/263312) | Coding Agent in VS Code dies permanently when you delete the branch it's working on | 0 | correctness | 3/6 Plausible | 12 | — | `npm run implement -- --issue 263312` |
| 73 | [#286255](https://github.com/microsoft/vscode/issues/286255) | background agent 'illegal argument' when a notebook is open | 0 | correctness | 2/6 Unverified | 12 | — | `npm run implement -- --issue 286255` |
| 84 | [#304856](https://github.com/microsoft/vscode/issues/304856) | Github Copilot Chat is not live-updated with integrated terminal with Github Copilot CLI | 0 | correctness | 3/6 Plausible | 11 | — | `npm run implement -- --issue 304856` |
| 90 | [#277557](https://github.com/microsoft/vscode/issues/277557) | element id for copilot on my behalf throws error | 0 | correctness | 3/6 Plausible | 10 | — | `npm run implement -- --issue 277557` |
| 99 | [#264187](https://github.com/microsoft/vscode/issues/264187) | "acceptResponseProgress: Adding progress to a completed response" fired repeatedly in multi-turn claude code session | 0 | correctness | 3/6 Plausible | 9 | — | `npm run implement -- --issue 264187` |
| 142 | [#315314](https://github.com/microsoft/vscode/issues/315314) | Hydrating large chat session items block renderer during startup | 0 | perf | 3/6 Plausible | 5 | — | `npm run implement -- --issue 315314` |
| 161 | [#263486](https://github.com/microsoft/vscode/issues/263486) | Coding Agent Session Log does not show MCP server name | 0 | papercut | 3/6 Plausible | 3 | — | `npm run implement -- --issue 263486` |
| 184 | [#317609](https://github.com/microsoft/vscode/issues/317609) | New Copilot CLI Update is Terrible | 0 | none | 3/6 Plausible | 2 | — | — |
| 196 | [#326548](https://github.com/microsoft/vscode/issues/326548) | codex chat is not loading | 0 | none | — | 2 | — | — |
| 197 | [#326835](https://github.com/microsoft/vscode/issues/326835) | Agent Sessions: session terminates instead of waiting when a sub-agent is launched | 0 | correctness | 3/6 Plausible | 2 | — | `npm run implement -- --issue 326835` |
| 228 | [#272115](https://github.com/microsoft/vscode/issues/272115) | Suggest widget in Copilot CLI session editor shows ... what? | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 272115` |
| 248 | [#291990](https://github.com/microsoft/vscode/issues/291990) | Copilot CLI shim (copilot.ps1) fails to find npm-installed binary on Windows when both are in PATH | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 291990` |
| 280 | [#314752](https://github.com/microsoft/vscode/issues/314752) | Copilot CLI session cannot be opened in Chat when historical permission.requested events are validated against the current schema | 0 | correctness | 4/6 Traced | 0 | yes | `npm run implement -- --issue 314752` |

### Other (64)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 4 | [#306924](https://github.com/microsoft/vscode/issues/306924) | [Unhandled Error] command 'workbench.action.chat.openNewChatSessionExternal.openai-codex' not found | 5 | correctness | 2/6 Unverified | 53 | — | — |
| 22 | [#243235](https://github.com/microsoft/vscode/issues/243235) | BadInstallScript Result | 2 | correctness | — | 29 | — | — |
| 27 | [#287100](https://github.com/microsoft/vscode/issues/287100) | Remote CLI server env settings conflict with user and custom env | 0 | correctness | 3/6 Plausible | 26 | — | `npm run implement -- --issue 287100` |
| 29 | [#315144](https://github.com/microsoft/vscode/issues/315144) | Agents: MCP servers get interrupted | 0 | correctness | 3/6 Plausible | 24 | — | `npm run implement -- --issue 315144` |
| 31 | [#318689](https://github.com/microsoft/vscode/issues/318689) | Agent window: Workspace and MCP servers get lost | 2 | correctness | 3/6 Plausible | 22 | — | `npm run implement -- --issue 318689` |
| 35 | [#251364](https://github.com/microsoft/vscode/issues/251364) | Chinese path encoding issue | 3 | correctness | 3/6 Plausible | 21 | — | — |
| 42 | [#294077](https://github.com/microsoft/vscode/issues/294077) | copilot via remote ssh use read_file failed | 0 | correctness | 3/6 Plausible | 19 | — | — |
| 45 | [#280816](https://github.com/microsoft/vscode/issues/280816) | Agents are limited over SSH | 0 | correctness | 2/6 Unverified | 18 | — | — |
| 46 | [#281913](https://github.com/microsoft/vscode/issues/281913) | Agent sessions: creating new cloud session is lagging | 0 | freeze | 3/6 Plausible | 17 | — | `npm run implement -- --issue 281913` |
| 51 | [#286360](https://github.com/microsoft/vscode/issues/286360) | Background agent action is not working for new users | 1 | correctness | 3/6 Plausible | 14 | — | — |
| 58 | [#269158](https://github.com/microsoft/vscode/issues/269158) | Cloud Agent stop button (cancel button) and cancellation is not handled properly | 1 | correctness | 3/6 Plausible | 13 | — | `npm run implement -- --issue 269158` |
| 63 | [#296177](https://github.com/microsoft/vscode/issues/296177) | Fix Error When Selecting WSL Projects in Chat Session Window | 0 | correctness | 3/6 Plausible | 13 | — | — |
| 65 | [#308595](https://github.com/microsoft/vscode/issues/308595) | Administrator mode doesn't show up in search bar like earlier | 0 | visual | 5/6 Source-confirmed | 13 | — | `npm run implement -- --issue 308595` |
| 66 | [#323883](https://github.com/microsoft/vscode/issues/323883) | SSH connection not working | 0 | correctness | 3/6 Plausible | 13 | — | — |
| 68 | [#316537](https://github.com/microsoft/vscode/issues/316537) | Open in agents fails to recognize WSL2 | 2 | correctness | 5/6 Source-confirmed | 12 | — | `npm run implement -- --issue 316537` |
| 74 | [#298286](https://github.com/microsoft/vscode/issues/298286) | Changes to what gets installed | 0 | correctness | 5/6 Source-confirmed | 12 | yes | `npm run implement -- --issue 298286` |
| 82 | [#283106](https://github.com/microsoft/vscode/issues/283106) | Local session not cleared after delegating to background with changes | 0 | correctness | — | 11 | — | `npm run implement -- --issue 283106` |
| 83 | [#293233](https://github.com/microsoft/vscode/issues/293233) | returning a `requestHandler` in `ChatSessionContentProvider#provideChatSessionContent` doesn't fire | 0 | correctness | 5/6 Source-confirmed | 11 | — | `npm run implement -- --issue 293233` |
| 93 | [#285363](https://github.com/microsoft/vscode/issues/285363) | Migrating changes infinite loop | 0 | correctness | 3/6 Plausible | 10 | — | — |
| 112 | [#327009](https://github.com/microsoft/vscode/issues/327009) | Agent Mode: Cant view diffs in WSL | 1 | correctness | 4/6 Traced | 7 | — | `npm run implement -- --issue 327009` |
| 115 | [#311559](https://github.com/microsoft/vscode/issues/311559) | [Error] chatagenterror-Open a GitHub repository to use the cloud agent. | 0 | papercut | 4/6 Traced | 7 | yes | `npm run implement -- --issue 311559` |
| 117 | [#317750](https://github.com/microsoft/vscode/issues/317750) | vscode server does not install in ssh with this new version | 0 | correctness | 2/6 Unverified | 7 | — | — |
| 118 | [#323974](https://github.com/microsoft/vscode/issues/323974) | The vscode server is not installing on my cluster | 0 | none | 3/6 Plausible | 7 | — | — |
| 120 | [#316712](https://github.com/microsoft/vscode/issues/316712) | Agent SSH connection fails on Windows target due to Unix-only probe (uname -s) | 1 | correctness | 5/6 Source-confirmed | 6 | — | `npm run implement -- --issue 316712` |
| 121 | [#317554](https://github.com/microsoft/vscode/issues/317554) | VS Code Installing Alpine Server on RHEL and Ubuntu | 1 | correctness | — | 6 | — | — |
| 122 | [#247443](https://github.com/microsoft/vscode/issues/247443) | SSH connection times out frequently after disconnection. | 0 | none | — | 6 | — | — |
| 123 | [#276444](https://github.com/microsoft/vscode/issues/276444) | A shared background process terminated unexpectedly.(Please help me to solve this problem!) | 0 | correctness | 3/6 Plausible | 6 | — | `npm run implement -- --issue 276444` |
| 132 | [#265170](https://github.com/microsoft/vscode/issues/265170) | Chat remote session diff editor opens empty | 0 | correctness | 3/6 Plausible | 5 | — | `npm run implement -- --issue 265170` |
| 134 | [#270185](https://github.com/microsoft/vscode/issues/270185) | Can't set remote.SSH.serverInstallPath to path with @ symbol | 0 | none | — | 5 | — | — |
| 135 | [#282074](https://github.com/microsoft/vscode/issues/282074) | Closing window with running Cloud session triggers confirm dialog | 0 | papercut | 2/6 Unverified | 5 | — | — |
| 136 | [#286536](https://github.com/microsoft/vscode/issues/286536) | Remote access is not loading extensions and file browsing taking long time | 0 | none | 3/6 Plausible | 5 | — | — |
| 137 | [#288989](https://github.com/microsoft/vscode/issues/288989) | Opening a file on remote takes a long time | 0 | perf | 3/6 Plausible | 5 | — | — |
| 138 | [#291316](https://github.com/microsoft/vscode/issues/291316) | Chat buttons next to command center steal pointer events from window title | 0 | papercut | 5/6 Source-confirmed | 5 | yes | `npm run implement -- --issue 291316` |
| 139 | [#291604](https://github.com/microsoft/vscode/issues/291604) | Cant Connect Via SSH to my Nvidia jetson | 0 | none | — | 5 | — | — |
| 140 | [#313700](https://github.com/microsoft/vscode/issues/313700) | Copilot Chat fails on Remote SSH (Linux) with missing pty.node, causing extension host crash | 0 | crash | 2/6 Unverified | 5 | — | — |
| 149 | [#289335](https://github.com/microsoft/vscode/issues/289335) | Agent Status Menu: Can't open context menu to toggle visibility | 0 | papercut | 4/6 Traced | 4 | — | `npm run implement -- --issue 289335` |
| 157 | [#296940](https://github.com/microsoft/vscode/issues/296940) | AI Customizations Editor: List gets cropped | 1 | visual | 2/6 Unverified | 3 | — | — |
| 158 | [#296942](https://github.com/microsoft/vscode/issues/296942) | AI Customizations Editor: Can't expand/collapse sections uisng the keyboard | 1 | papercut | 5/6 Source-confirmed | 3 | yes | `npm run implement -- --issue 296942` |
| 160 | [#224233](https://github.com/microsoft/vscode/issues/224233) | Installation error when home directory is read-only | 0 | papercut | 3/6 Plausible | 3 | — | — |
| 162 | [#271235](https://github.com/microsoft/vscode/issues/271235) | file.bin attachment on every Launched coding agent task in Chat | 0 | papercut | 3/6 Plausible | 3 | — | `npm run implement -- --issue 271235` |
| 164 | [#286117](https://github.com/microsoft/vscode/issues/286117) | Cloud sessions often do not appear for me (multi root workspace) | 0 | papercut | 3/6 Plausible | 3 | — | `npm run implement -- --issue 286117` |
| 166 | [#307366](https://github.com/microsoft/vscode/issues/307366) | Signed into multiple GH accounts | 0 | correctness | 3/6 Plausible | 3 | — | `npm run implement -- --issue 307366` |
| 171 | [#323551](https://github.com/microsoft/vscode/issues/323551) | starting new remote session has no models | 0 | correctness | 3/6 Plausible | 3 | — | `npm run implement -- --issue 323551` |
| 172 | [#242420](https://github.com/microsoft/vscode/issues/242420) | ssh config wrong when adding reverse proxy ssh | 1 | none | — | 2 | — | — |
| 187 | [#320217](https://github.com/microsoft/vscode/issues/320217) | They allow the russians into your VM. | 0 | none | 3/6 Plausible | 2 | — | — |
| 192 | [#322748](https://github.com/microsoft/vscode/issues/322748) | ChatSessionItem.iconPath is not serialized — extension session items always show codicon-terminal in Sessions list | 0 | correctness | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 322748` |
| 195 | [#326095](https://github.com/microsoft/vscode/issues/326095) | Code Execution Permission Error in latest vscode | 0 | correctness | 6/6 Confirmed | 2 | — | — |
| 199 | [#209188](https://github.com/microsoft/vscode/issues/209188) | Using a vscode:// link with ?new-window or ?reuse-window still hijacks existing window | 0 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 209188` |
| 202 | [#275566](https://github.com/microsoft/vscode/issues/275566) | Code Lense: Delegate to agent appears weirdly | 0 | visual | 3/6 Plausible | 1 | — | `npm run implement -- --issue 275566` |
| 203 | [#281953](https://github.com/microsoft/vscode/issues/281953) | Incorrect stable version of npm packages | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 208 | [#293542](https://github.com/microsoft/vscode/issues/293542) | package search form keeps resetting query terms | 0 | papercut | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 293542` |
| 210 | [#301889](https://github.com/microsoft/vscode/issues/301889) | Constantly loses connection; cannot reconnect without password entered three times | 0 | none | — | 1 | — | — |
| 211 | [#305883](https://github.com/microsoft/vscode/issues/305883) | Render Whitespace toggle in View menu shows as checked by default but doesn't actually render whitespace | 0 | visual | 2/6 Unverified | 1 | — | — |
| 218 | [#313943](https://github.com/microsoft/vscode/issues/313943) | remote window could not work properly! | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 219 | [#317963](https://github.com/microsoft/vscode/issues/317963) | 项目信息，skill全部丢失 | 0 | none | 3/6 Plausible | 1 | — | — |
| 222 | [#320952](https://github.com/microsoft/vscode/issues/320952) | Flaky unit test | 0 | papercut | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 320952` |
| 223 | [#325394](https://github.com/microsoft/vscode/issues/325394) | aka.ms/vscode-continue-chat-in no longer links to | 0 | papercut | 6/6 Confirmed | 1 | — | `npm run implement -- --issue 325394` |
| 224 | [#226963](https://github.com/microsoft/vscode/issues/226963) | The "add dev container files" quick pick can remove the item you want | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 226963` |
| 235 | [#282656](https://github.com/microsoft/vscode/issues/282656) | Delegating to Cloud/Background does not work in `Edit` mode | 0 | correctness | — | 0 | — | `npm run implement -- --issue 282656` |
| 255 | [#295553](https://github.com/microsoft/vscode/issues/295553) | Error when switching to background session | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 295553` |
| 259 | [#297261](https://github.com/microsoft/vscode/issues/297261) | Restart server duplicated in Context menu | 0 | visual | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 297261` |
| 290 | [#316590](https://github.com/microsoft/vscode/issues/316590) | Application is clashing | 0 | data-loss | 3/6 Plausible | 0 | — | — |
| 300 | [#318234](https://github.com/microsoft/vscode/issues/318234) | `apply_patch` adds an extra leading space when replacing an indented line | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 318234` |
| 307 | [#320579](https://github.com/microsoft/vscode/issues/320579) | agent method | 0 | none | 3/6 Plausible | 0 | — | — |

## Feature requests

### Remote SSH (12)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | [#318997](https://github.com/microsoft/vscode/issues/318997) | Remote agent sessions started via UI running in the background (detach VSCode) | 20 | backlog-candidate | 100 | `npm run implement -- --issue 318997` |
| 2 | [#282410](https://github.com/microsoft/vscode/issues/282410) | Request for a low-resource default configuration for VS Code Remote-SSH in shared environments | 22 | backlog-candidate | 80 | `npm run implement -- --issue 282410` |
| 3 | [#200524](https://github.com/microsoft/vscode/issues/200524) | SSH Host File - Grouping several servers | 34 | backlog-candidate | 77 | `npm run implement -- --issue 200524` |
| 5 | [#242505](https://github.com/microsoft/vscode/issues/242505) | SSH-Download Progress Bar | 22 | backlog-candidate | 72 | `npm run implement -- --issue 242505` |
| 26 | [#285437](https://github.com/microsoft/vscode/issues/285437) | Wayland display forwarding for SSH remotes | 2 | dormant | 8 | — |
| 42 | [#326232](https://github.com/microsoft/vscode/issues/326232) | Restore Remote-SSH support for 32-bit ARM Linux (armv7l) targets | 3 | active | 5 | — |
| 47 | [#295227](https://github.com/microsoft/vscode/issues/295227) | Slow remote development (over SSH) startup because of server updates | 1 | active | 4 | — |
| 61 | [#292476](https://github.com/microsoft/vscode/issues/292476) | Do not auto-install Github Copilot on Remote | 0 | active | 2 | `npm run implement -- --issue 292476` |
| 66 | [#319573](https://github.com/microsoft/vscode/issues/319573) | Please suppress modal dialogs for connection problems | 0 | active | 2 | `npm run implement -- --issue 319573` |
| 86 | [#235120](https://github.com/microsoft/vscode/issues/235120) | Remote SSH: Participant is not aware of the SSH remotes I have setup/configured in VS Code | 0 | backlog-candidate | 0 | `npm run implement -- --issue 235120` |
| 128 | [#322765](https://github.com/microsoft/vscode/issues/322765) | ssh sessions to multiple remote hosts with synced view | 0 | active | 0 | — |
| 132 | [#325146](https://github.com/microsoft/vscode/issues/325146) | Remote-SSH: Avoid connection reconnects on workspace change | 0 | active | 0 | — |

### Agent customization (21)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 4 | [#301181](https://github.com/microsoft/vscode/issues/301181) | Distribute Skills and Instructions from Organization Repositories | 20 | active | 74 | `npm run implement -- --issue 301181` |
| 12 | [#264631](https://github.com/microsoft/vscode/issues/264631) | Centralized agent customization UI | 0 | active | 15 | `npm run implement -- --issue 264631` |
| 14 | [#313321](https://github.com/microsoft/vscode/issues/313321) | Add estimated token cost for customization files | 3 | backlog-candidate | 12 | `npm run implement -- --issue 313321` |
| 31 | [#313828](https://github.com/microsoft/vscode/issues/313828) | Improve the UI experience of the Customizations menu | 0 | active | 8 | `npm run implement -- --issue 313828` |
| 43 | [#322506](https://github.com/microsoft/vscode/issues/322506) | [Feature Request] Allow configuring Copilot agent/skill/instruction discovery paths via settings | 0 | active | 5 | `npm run implement -- --issue 322506` |
| 48 | [#323267](https://github.com/microsoft/vscode/issues/323267) | AI: Show the VS Code extension that introduced each MCP server, tool, agent, skill, instruction, and plugin | 1 | active | 4 | `npm run implement -- --issue 323267` |
| 57 | [#304146](https://github.com/microsoft/vscode/issues/304146) | Chat customization: promote the built-in Github MCP server | 0 | active | 3 | `npm run implement -- --issue 304146` |
| 59 | [#253336](https://github.com/microsoft/vscode/issues/253336) | Cloud agent should respect my instructions | 0 | active | 2 | `npm run implement -- --issue 253336` |
| 76 | [#304175](https://github.com/microsoft/vscode/issues/304175) | Apply/try action from the customization | 0 | active | 1 | `npm run implement -- --issue 304175` |
| 77 | [#304847](https://github.com/microsoft/vscode/issues/304847) | Add ability to hide extension contributed agents / customizations from Customizations window | 0 | active | 1 | `npm run implement -- --issue 304847` |
| 97 | [#297262](https://github.com/microsoft/vscode/issues/297262) | Chat customisations search should be able to search across all customistations | 0 | active | 0 | `npm run implement -- --issue 297262` |
| 98 | [#297366](https://github.com/microsoft/vscode/issues/297366) | Integrate plugin management to the new Chat Customization dialog | 0 | active | 0 | `npm run implement -- --issue 297366` |
| 99 | [#297402](https://github.com/microsoft/vscode/issues/297402) | Suggestion- all config editors in same modal | 0 | active | 0 | `npm run implement -- --issue 297402` |
| 100 | [#298144](https://github.com/microsoft/vscode/issues/298144) | Show when customizations are extension-contributed | 0 | active | 0 | `npm run implement -- --issue 298144` |
| 101 | [#298145](https://github.com/microsoft/vscode/issues/298145) | Customizations window should offer "Generate workspace instructions" when missing | 0 | active | 0 | `npm run implement -- --issue 298145` |
| 103 | [#310708](https://github.com/microsoft/vscode/issues/310708) | Rename skill scopes to Repo/Local and add unified checkbox UI for skill placement | 0 | active | 0 | `npm run implement -- --issue 310708` |
| 104 | [#312544](https://github.com/microsoft/vscode/issues/312544) | Improve the AI Customizations editor with a structured front matter preview and raw edit toggle | 0 | active | 0 | — |
| 107 | [#313320](https://github.com/microsoft/vscode/issues/313320) | Show customization token usage in context window widget | 0 | backlog-candidate | 0 | `npm run implement -- --issue 313320` |
| 125 | [#322263](https://github.com/microsoft/vscode/issues/322263) | Copilot : Allow extensions to register custom sections in the Agent Customizations panel | 0 | active | 0 | `npm run implement -- --issue 322263` |
| 126 | [#322650](https://github.com/microsoft/vscode/issues/322650) | Native customization surface for rule packs and instructions | 0 | active | 0 | — |
| 130 | [#323266](https://github.com/microsoft/vscode/issues/323266) | AI Chat: Add on/off toggles in the Customizations view to enable/disable each MCP server, tool, agent, skill, instruction, and plugin | 0 | active | 0 | `npm run implement -- --issue 323266` |

### Enterprise policy (23)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 6 | [#314414](https://github.com/microsoft/vscode/issues/314414) | Enforce `extensions.allowed` policy from the Remote (Server) side during Remote - SSH sessions | 25 | backlog-candidate | 66 | `npm run implement -- --issue 314414` |
| 7 | [#312764](https://github.com/microsoft/vscode/issues/312764) | Support all settings via JSON in a Group Policy (GPO) | 22 | backlog-candidate | 58 | `npm run implement -- --issue 312764` |
| 9 | [#306934](https://github.com/microsoft/vscode/issues/306934) | Add "Disable AI Features" to enterprise policy | 4 | active | 17 | `npm run implement -- --issue 306934` |
| 15 | [#239798](https://github.com/microsoft/vscode/issues/239798) | Show a warning notification if a policy setting cannot be applied | 2 | backlog-candidate | 11 | `npm run implement -- --issue 239798` |
| 16 | [#269610](https://github.com/microsoft/vscode/issues/269610) | Allow granular auto-approval settings for Copilot Chat tools | 1 | active | 11 | — |
| 35 | [#284302](https://github.com/microsoft/vscode/issues/284302) | Allow MDM to prevent modifying list of allow/denied commands for chat auto-approval | 0 | active | 7 | `npm run implement -- --issue 284302` |
| 37 | [#286454](https://github.com/microsoft/vscode/issues/286454) | Allow users to request feature access from VS Code | 0 | dormant | 7 | `npm run implement -- --issue 286454` |
| 38 | [#279672](https://github.com/microsoft/vscode/issues/279672) | Setup GHE.com URL with GPO | 2 | dormant | 6 | `npm run implement -- --issue 279672` |
| 44 | [#318188](https://github.com/microsoft/vscode/issues/318188) | Is there any way to completely remove the Agent App? | 3 | active | 4 | `npm run implement -- --issue 318188` |
| 45 | [#251844](https://github.com/microsoft/vscode/issues/251844) | Add "Admin Contact Info" policy | 1 | dormant | 4 | `npm run implement -- --issue 251844` |
| 50 | [#251161](https://github.com/microsoft/vscode/issues/251161) | Put user into restricted mode when policy error occurs | 0 | backlog-candidate | 4 | `npm run implement -- --issue 251161` |
| 54 | [#319382](https://github.com/microsoft/vscode/issues/319382) | Plugins disabled by enterprise policy should indicate reason | 1 | active | 3 | `npm run implement -- --issue 319382` |
| 69 | [#151948](https://github.com/microsoft/vscode/issues/151948) | Allow extensions to contribute Group Policy | 1 | backlog-candidate | 1 | `npm run implement -- --issue 151948` |
| 71 | [#251231](https://github.com/microsoft/vscode/issues/251231) | Auto-document enterprise policy keys | 0 | backlog-candidate | 1 | `npm run implement -- --issue 251231` |
| 78 | [#314103](https://github.com/microsoft/vscode/issues/314103) | Disabled model by organization still appears the in model list | 0 | active | 1 | `npm run implement -- --issue 314103` |
| 87 | [#266114](https://github.com/microsoft/vscode/issues/266114) | Enable VS Code to auto-install extensions via policy and support auto-installation of MCP servers | 0 | backlog-candidate | 0 | `npm run implement -- --issue 266114` |
| 89 | [#280739](https://github.com/microsoft/vscode/issues/280739) | `chat.tools.eligibleForAutoApproval` schema validation rejects legacy tool names | 0 | active | 0 | `npm run implement -- --issue 280739` |
| 92 | [#284379](https://github.com/microsoft/vscode/issues/284379) | Enterprise-Managed VS Code with Extensions Marketplace | 0 | dormant | 0 | — |
| 96 | [#295044](https://github.com/microsoft/vscode/issues/295044) | Add an enterprise policy to accept JSON settings | 0 | active | 0 | `npm run implement -- --issue 295044` |
| 105 | [#312841](https://github.com/microsoft/vscode/issues/312841) | Add a warning when a policy is set but it's value does not parse | 0 | backlog-candidate | 0 | `npm run implement -- --issue 312841` |
| 112 | [#316410](https://github.com/microsoft/vscode/issues/316410) | Implement a policy-settings mechanism for approving/blocking agent market-places | 0 | active | 0 | — |
| 124 | [#321991](https://github.com/microsoft/vscode/issues/321991) | policy: surface managed-settings projection warnings in diagnostics | 0 | active | 0 | `npm run implement -- --issue 321991` |
| 127 | [#322651](https://github.com/microsoft/vscode/issues/322651) | Org-managed policy distribution and audit | 0 | active | 0 | `npm run implement -- --issue 322651` |

### Cloud delegation (20)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 8 | [#291817](https://github.com/microsoft/vscode/issues/291817) | Implement Cloud Agent Tasks API | 1 | active | 32 | `npm run implement -- --issue 291817` |
| 13 | [#292702](https://github.com/microsoft/vscode/issues/292702) | Steering / queued messages for Cloud agents | 0 | active | 13 | `npm run implement -- --issue 292702` |
| 20 | [#267716](https://github.com/microsoft/vscode/issues/267716) | feature request: more flexibility with send to remote agent | 1 | active | 10 | `npm run implement -- --issue 267716` |
| 27 | [#256592](https://github.com/microsoft/vscode/issues/256592) | Ability to send to Coding Agent from prompt files | 0 | dormant | 8 | `npm run implement -- --issue 256592` |
| 28 | [#262767](https://github.com/microsoft/vscode/issues/262767) | UX to delegate specific TODOs to coding agent | 0 | backlog-candidate | 8 | `npm run implement -- --issue 262767` |
| 29 | [#275502](https://github.com/microsoft/vscode/issues/275502) | Copilot Cloud Agent output needs a revamp | 0 | backlog-candidate | 8 | `npm run implement -- --issue 275502` |
| 30 | [#296642](https://github.com/microsoft/vscode/issues/296642) | Different cloud and background options when delegating from local vs new empty chat | 0 | active | 8 | `npm run implement -- --issue 296642` |
| 32 | [#276759](https://github.com/microsoft/vscode/issues/276759) | there doesn't seem to be any way to kick off the CI for changes in CCA | 0 | backlog-candidate | 7 | `npm run implement -- --issue 276759` |
| 33 | [#280676](https://github.com/microsoft/vscode/issues/280676) | Option to keep history when delegating to background agent | 0 | dormant | 7 | `npm run implement -- --issue 280676` |
| 34 | [#280689](https://github.com/microsoft/vscode/issues/280689) | Cloud session should have more prominent link to the PR | 0 | dormant | 7 | `npm run implement -- --issue 280689` |
| 39 | [#299840](https://github.com/microsoft/vscode/issues/299840) | Plan mode → Cloud implementation handoff sends generated summary, not the actual plan | 2 | backlog-candidate | 6 | — |
| 55 | [#286035](https://github.com/microsoft/vscode/issues/286035) | Ensure context (screenshots, divs, highlighted lines) from VSCode Cloud Agent is attached to PR comments | 0 | active | 3 | `npm run implement -- --issue 286035` |
| 60 | [#282818](https://github.com/microsoft/vscode/issues/282818) | Agent sessions: Allow Continue in/Delegate to create multiple agents | 0 | dormant | 2 | `npm run implement -- --issue 282818` |
| 65 | [#302107](https://github.com/microsoft/vscode/issues/302107) | Sessions: Cloud agent activity on GitHub.com (PR creation, review comments, follow-up commits) is not reflected in the originating session | 0 | active | 2 | `npm run implement -- --issue 302107` |
| 73 | [#282667](https://github.com/microsoft/vscode/issues/282667) | Add an 'open in codespace' button to coding agent sessions | 0 | dormant | 1 | `npm run implement -- --issue 282667` |
| 74 | [#287968](https://github.com/microsoft/vscode/issues/287968) | Add Multiplier to Model Selection When Session Target is Set to Background | 0 | dormant | 1 | — |
| 88 | [#266476](https://github.com/microsoft/vscode/issues/266476) | Improve handoff workflow between cloud and local chat sessions | 0 | active | 0 | `npm run implement -- --issue 266476` |
| 91 | [#283617](https://github.com/microsoft/vscode/issues/283617) | Cloud agent to continue after VS Code is closed | 0 | backlog-candidate | 0 | `npm run implement -- --issue 283617` |
| 94 | [#288193](https://github.com/microsoft/vscode/issues/288193) | Open PR as default artifact for WIP cloud agents | 0 | dormant | 0 | `npm run implement -- --issue 288193` |
| 106 | [#313116](https://github.com/microsoft/vscode/issues/313116) | Codespace integration for session creation: auto-create or connect & host agent server | 0 | backlog-candidate | 0 | `npm run implement -- --issue 313116` |

### Agent workspaces (15)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 10 | [#264555](https://github.com/microsoft/vscode/issues/264555) | Agent sessions support for multi-root workspaces | 0 | active | 16 | `npm run implement -- --issue 264555` |
| 11 | [#282109](https://github.com/microsoft/vscode/issues/282109) | Agent sessions: support empty workspaces | 0 | active | 16 | `npm run implement -- --issue 282109` |
| 41 | [#316241](https://github.com/microsoft/vscode/issues/316241) | Copilot CLI agent panel: "Files" tab should show full workspace file tree, not only git-changed files | 0 | active | 6 | — |
| 52 | [#291714](https://github.com/microsoft/vscode/issues/291714) | Support starting cloud sessions for a specific repository in multi-repo workspaces | 0 | active | 4 | — |
| 68 | [#322981](https://github.com/microsoft/vscode/issues/322981) | Feature Request: Isolated local sandboxes for parallel Copilot Chat operations | 0 | active | 2 | `npm run implement -- --issue 322981` |
| 79 | [#316157](https://github.com/microsoft/vscode/issues/316157) | [Agents App] No visible indicator when working inside a worktree | 0 | active | 1 | `npm run implement -- --issue 316157` |
| 80 | [#316591](https://github.com/microsoft/vscode/issues/316591) | Feature request: Work on current branch instead of creating new agent branches | 0 | active | 1 | — |
| 85 | [#325803](https://github.com/microsoft/vscode/issues/325803) | AgentHost: Support "Remote Repositories" | 0 | active | 1 | `npm run implement -- --issue 325803` |
| 102 | [#304822](https://github.com/microsoft/vscode/issues/304822) | We need Local Harness in SessionsCustomizationHarnessService | 0 | active | 0 | — |
| 111 | [#316162](https://github.com/microsoft/vscode/issues/316162) | [Agents App] Users assume they must merge to main to preview/test worktree changes | 0 | active | 0 | `npm run implement -- --issue 316162` |
| 120 | [#319551](https://github.com/microsoft/vscode/issues/319551) | Support workspaces in Visual Studio Code Agents app. | 0 | active | 0 | — |
| 122 | [#321685](https://github.com/microsoft/vscode/issues/321685) | Agents window: Allow customization of branch name prefix for worktree branches | 0 | active | 0 | `npm run implement -- --issue 321685` |
| 123 | [#321727](https://github.com/microsoft/vscode/issues/321727) | Agents window ("Open in Agents"): preserve source subfolder as working directory when a session uses worktree isolation (monorepo) | 0 | active | 0 | `npm run implement -- --issue 321727` |
| 131 | [#323521](https://github.com/microsoft/vscode/issues/323521) | Repository placeholder on repository picker | 0 | active | 0 | `npm run implement -- --issue 323521` |
| 134 | [#326521](https://github.com/microsoft/vscode/issues/326521) | Copilot Chat (Agents): allow starting a new chat with no workspace folder context | 0 | active | 0 | `npm run implement -- --issue 326521` |

### Chat extension APIs (9)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 18 | [#325507](https://github.com/microsoft/vscode/issues/325507) | Public API to observe agent/subagent chat session lifecycle & status from an extension | 0 | active | 11 | `npm run implement -- --issue 325507` |
| 21 | [#289467](https://github.com/microsoft/vscode/issues/289467) | Give me control over empty state URI resolution in ChatContent Provider | 0 | active | 10 | `npm run implement -- --issue 289467` |
| 22 | [#295713](https://github.com/microsoft/vscode/issues/295713) | API proposal: Allow ChatSessionContentProvider to provide a checkpoint handler | 0 | backlog-candidate | 10 | `npm run implement -- --issue 295713` |
| 51 | [#289469](https://github.com/microsoft/vscode/issues/289469) | Allow me to redirect a URI to another URI in the Content Provider | 0 | active | 4 | `npm run implement -- --issue 289469` |
| 53 | [#319204](https://github.com/microsoft/vscode/issues/319204) | [Feature Request] `LanguageModelChatProvider`: allow providers to grey out excluded message turns in the chat UI | 1 | active | 3 | `npm run implement -- --issue 319204` |
| 62 | [#294246](https://github.com/microsoft/vscode/issues/294246) | Let me provide my own resource Uri in the ChatSessionContentProvider API | 0 | active | 2 | `npm run implement -- --issue 294246` |
| 83 | [#319722](https://github.com/microsoft/vscode/issues/319722) | Extension API to programmatically delete chat sessions | 0 | active | 1 | `npm run implement -- --issue 319722` |
| 118 | [#318855](https://github.com/microsoft/vscode/issues/318855) | Chat session observation API for extension-owned evaluation and tooling | 0 | active | 0 | `npm run implement -- --issue 318855` |
| 133 | [#325827](https://github.com/microsoft/vscode/issues/325827) | Support registration of external agents via Extension API in the agents view | 0 | active | 0 | `npm run implement -- --issue 325827` |

### Agents window (10)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 17 | [#317895](https://github.com/microsoft/vscode/issues/317895) | [insiders] Agent window Local agent: MCP config not synced & BYOK custom model not supported | 0 | active | 11 | `npm run implement -- --issue 317895` |
| 49 | [#325133](https://github.com/microsoft/vscode/issues/325133) | Agents window should support the same local Copilot agent harness as the Chat view | 1 | active | 4 | `npm run implement -- --issue 325133` |
| 56 | [#292430](https://github.com/microsoft/vscode/issues/292430) | Use agent status to indicate Copilot availability | 0 | backlog-candidate | 3 | `npm run implement -- --issue 292430` |
| 64 | [#298599](https://github.com/microsoft/vscode/issues/298599) | Support multi-instance supervision and 24h scheduled autonomous workflows in Copilot | 0 | active | 2 | — |
| 82 | [#319395](https://github.com/microsoft/vscode/issues/319395) | Copilot Chat - Emphasis on Agent | 0 | active | 1 | `npm run implement -- --issue 319395` |
| 84 | [#325486](https://github.com/microsoft/vscode/issues/325486) | [Vscode Agents] Need Speech-to-Text support in Agents window | 0 | active | 1 | `npm run implement -- --issue 325486` |
| 95 | [#293459](https://github.com/microsoft/vscode/issues/293459) | ✨ Show agent status when command center is disabled | 0 | active | 0 | `npm run implement -- --issue 293459` |
| 109 | [#316159](https://github.com/microsoft/vscode/issues/316159) | [Agents App] "New session" feels like "start over" — parallelism is undiscoverable | 0 | active | 0 | `npm run implement -- --issue 316159` |
| 110 | [#316160](https://github.com/microsoft/vscode/issues/316160) | [Agents App] Sub-session (plus button) creates confusion — expected new session, got nested conversation | 0 | active | 0 | `npm run implement -- --issue 316160` |
| 121 | [#321622](https://github.com/microsoft/vscode/issues/321622) | agents window | 0 | active | 0 | — |

### Session organization (15)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 19 | [#319989](https://github.com/microsoft/vscode/issues/319989) | Delete Claude session types in chat | 3 | active | 10 | — |
| 23 | [#311413](https://github.com/microsoft/vscode/issues/311413) | Plan mode is not easily discoverable | 0 | active | 10 | `npm run implement -- --issue 311413` |
| 24 | [#320556](https://github.com/microsoft/vscode/issues/320556) | Batch delete the copilot chat of the current project | 3 | active | 9 | — |
| 25 | [#321182](https://github.com/microsoft/vscode/issues/321182) | Agents window : Improve Conversation Organization with Tags | 0 | backlog-candidate | 9 | `npm run implement -- --issue 321182` |
| 36 | [#286171](https://github.com/microsoft/vscode/issues/286171) | Archive handling for background/cloud sessions | 0 | active | 7 | `npm run implement -- --issue 286171` |
| 58 | [#313971](https://github.com/microsoft/vscode/issues/313971) | ✨ Add "regenerate title(using llm)" action for copilot chat session | 0 | active | 3 | `npm run implement -- --issue 313971` |
| 63 | [#296115](https://github.com/microsoft/vscode/issues/296115) | Nav bar growth affordance | 0 | active | 2 | `npm run implement -- --issue 296115` |
| 67 | [#320912](https://github.com/microsoft/vscode/issues/320912) | Feature Request: Sync chat history between VS Code IDE Chat and Agents view | 0 | active | 2 | `npm run implement -- --issue 320912` |
| 81 | [#319106](https://github.com/microsoft/vscode/issues/319106) | Dates on chat sessions | 0 | active | 1 | — |
| 93 | [#284391](https://github.com/microsoft/vscode/issues/284391) | Background sessions: allow to rename | 0 | dormant | 0 | `npm run implement -- --issue 284391` |
| 114 | [#317705](https://github.com/microsoft/vscode/issues/317705) | Trim the existing Copilot Chat session | 0 | active | 0 | `npm run implement -- --issue 317705` |
| 115 | [#317993](https://github.com/microsoft/vscode/issues/317993) | Agents App: Allow me to search for text within the chat history | 0 | active | 0 | `npm run implement -- --issue 317993` |
| 116 | [#318170](https://github.com/microsoft/vscode/issues/318170) | Agent Mode does not load past GHCP CLI sessions | 0 | active | 0 | `npm run implement -- --issue 318170` |
| 117 | [#318552](https://github.com/microsoft/vscode/issues/318552) | Allow pinning/unpinning Copilot Chat sessions from within the session itself | 0 | active | 0 | `npm run implement -- --issue 318552` |
| 119 | [#319074](https://github.com/microsoft/vscode/issues/319074) | Chat: Unsent (draft) input should not surface when navigating back to the session list | 0 | active | 0 | — |

### Diff application (3)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 40 | [#282122](https://github.com/microsoft/vscode/issues/282122) | Expect `Apply Changes to Workspace` to then close file diff and hide worktree | 0 | dormant | 6 | `npm run implement -- --issue 282122` |
| 46 | [#260226](https://github.com/microsoft/vscode/issues/260226) | Explore layouts for Chat session + Multi File Diff | 1 | active | 4 | `npm run implement -- --issue 260226` |
| 72 | [#281370](https://github.com/microsoft/vscode/issues/281370) | No Apply Changes button in multi diff editor for cloud sessions | 0 | backlog-candidate | 1 | `npm run implement -- --issue 281370` |

### Other (6)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 70 | [#226896](https://github.com/microsoft/vscode/issues/226896) | Should we add a docs link to the `.github/dependabot.yml`? | 0 | dormant | 1 | `npm run implement -- --issue 226896` |
| 75 | [#292407](https://github.com/microsoft/vscode/issues/292407) | Add Delegate action on todos in editor | 0 | active | 1 | `npm run implement -- --issue 292407` |
| 90 | [#281156](https://github.com/microsoft/vscode/issues/281156) | Background agent should not show retry/thumbsup/down | 0 | dormant | 0 | — |
| 108 | [#313444](https://github.com/microsoft/vscode/issues/313444) | Improve Quick Access Search Bar UI/UX | 0 | active | 0 | `npm run implement -- --issue 313444` |
| 113 | [#316613](https://github.com/microsoft/vscode/issues/316613) | Make the default code theme button and highlight darker/grayish shade. | 0 | active | 0 | — |
| 129 | [#323132](https://github.com/microsoft/vscode/issues/323132) | New Sessions / Agents handoff model picker does not show registered external language models | 0 | active | 0 | `npm run implement -- --issue 323132` |
