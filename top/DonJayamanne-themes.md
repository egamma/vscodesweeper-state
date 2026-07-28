# Top issues by theme — DonJayamanne

Experimental themed view of [the flat ranking](DonJayamanne.md); themes assigned by the review engine. Rank/score are the lane-wide values. Generated 2026-07-28 07:17 UTC.

## Bugs

### Enterprise and auth (9)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | [#304075](https://github.com/microsoft/vscode/issues/304075) | Copilot CLI Session (Agent Mode) fails with GHE | 5 | correctness | 5/6 Source-confirmed | 100 | yes | `npm run implement -- --issue 304075` |
| 2 | [#316511](https://github.com/microsoft/vscode/issues/316511) | Support Github Enterprise with Copilot CLI | 7 | correctness | 6/6 Confirmed | 75 | — | — |
| 4 | [#314053](https://github.com/microsoft/vscode/issues/314053) | Copilot CLI (handsoff) from VS Code fails with "model_not_supported" error since 1.119 | 4 | correctness | 5/6 Source-confirmed | 68 | — | — |
| 22 | [#294935](https://github.com/microsoft/vscode/issues/294935) | Background agents fail without error when Copilot CLI is disabled via policy | 0 | correctness | 3/6 Plausible | 29 | — | `npm run implement -- --issue 294935` |
| 24 | [#302626](https://github.com/microsoft/vscode/issues/302626) | Copilot CLI session failing in VSCode OSS | 2 | correctness | 3/6 Plausible | 27 | — | `npm run implement -- --issue 302626` |
| 66 | [#307252](https://github.com/microsoft/vscode/issues/307252) | Copilot CLI does not prompt user to login if they are unauthenticated | 0 | correctness | — | 11 | — | `npm run implement -- --issue 307252` |
| 100 | [#295901](https://github.com/microsoft/vscode/issues/295901) | Improve messaging when users arent signed in at Copiot CLI entry points | 0 | papercut | — | 5 | — | `npm run implement -- --issue 295901` |
| 108 | [#319662](https://github.com/microsoft/vscode/issues/319662) | CopilotCLISession "Failed to fetch models: 403" in devcontainer despite successful auth | 0 | correctness | 3/6 Plausible | 4 | — | — |
| 174 | [#296122](https://github.com/microsoft/vscode/issues/296122) | Copilot CLI upgrade version issue | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 296122` |

### Diffs and changes (12)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 3 | [#320292](https://github.com/microsoft/vscode/issues/320292) | Agent Window: Applying patches hangs forever | 0 | freeze | 5/6 Source-confirmed | 70 | — | `npm run implement -- --issue 320292` |
| 29 | [#194917](https://github.com/microsoft/vscode/issues/194917) | compare with saved not working | 2 | correctness | 5/6 Source-confirmed | 24 | — | `npm run implement -- --issue 194917` |
| 61 | [#198460](https://github.com/microsoft/vscode/issues/198460) | Cloud Changes causes data loss.  Should notify before applying changes. | 1 | data-loss | 3/6 Plausible | 11 | — | — |
| 78 | [#312976](https://github.com/microsoft/vscode/issues/312976) | Copilot CLI with worktree mode made local changes | 0 | correctness | 3/6 Plausible | 9 | — | `npm run implement -- --issue 312976` |
| 95 | [#312988](https://github.com/microsoft/vscode/issues/312988) | Copilot CLI sometimes shows no diff information in Sessions view | 0 | correctness | 3/6 Plausible | 6 | — | `npm run implement -- --issue 312988` |
| 106 | [#311411](https://github.com/microsoft/vscode/issues/311411) | [Copilot CLI] change isolation mode does not work in an established session | 0 | correctness | — | 4 | — | `npm run implement -- --issue 311411` |
| 132 | [#295508](https://github.com/microsoft/vscode/issues/295508) | Agent sessions list still has pending changes after everything is applied | 0 | visual | 3/6 Plausible | 2 | — | `npm run implement -- --issue 295508` |
| 137 | [#314222](https://github.com/microsoft/vscode/issues/314222) | Previous AI suggested edits won't go away | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 143 | [#321301](https://github.com/microsoft/vscode/issues/321301) | AI overwriting local file with remote | 0 | none | 3/6 Plausible | 2 | — | — |
| 167 | [#293315](https://github.com/microsoft/vscode/issues/293315) | Git diff colors in scrollbar render incorrectly in VS Code Dark (Experimental Dark) theme | 0 | visual | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 293315` |
| 186 | [#308365](https://github.com/microsoft/vscode/issues/308365) | NoChangeError message has broken ToolName interpolation and typo | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 197 | [#316104](https://github.com/microsoft/vscode/issues/316104) | Copilot changes/diff pane polluted with tons of files, no "Keep" or "Undo" available for them | 0 | correctness | 3/6 Plausible | 0 | — | — |

### Session lifecycle (18)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 6 | [#300191](https://github.com/microsoft/vscode/issues/300191) | Sessions with Codex are set as "unread sessions" | 6 | papercut | 3/6 Plausible | 65 | — | `npm run implement -- --issue 300191` |
| 10 | [#317183](https://github.com/microsoft/vscode/issues/317183) | Agents: Steering brings me to the new session screen | 1 | correctness | 6/6 Confirmed | 52 | — | `npm run implement -- --issue 317183` |
| 17 | [#312793](https://github.com/microsoft/vscode/issues/312793) | [Error] unhandlederror-Session file is corrupted (line 1452: data.compactionTokensUsed.input: Required) | 0 | correctness | 2/6 Unverified | 34 | — | — |
| 18 | [#319726](https://github.com/microsoft/vscode/issues/319726) | Failed to open chat session: Illegal argument: character must be non-negative | 0 | correctness | 5/6 Source-confirmed | 34 | yes | `npm run implement -- --issue 319726` |
| 30 | [#315692](https://github.com/microsoft/vscode/issues/315692) | Agents - session file is corrupted error | 0 | correctness | 3/6 Plausible | 24 | — | `npm run implement -- --issue 315692` |
| 31 | [#313317](https://github.com/microsoft/vscode/issues/313317) | [Agents] Forking a conversation includes the last sent messages | 0 | correctness | 2/6 Unverified | 23 | — | `npm run implement -- --issue 313317` |
| 46 | [#321484](https://github.com/microsoft/vscode/issues/321484) | sessions missing in list from today - they "re-appear" if you click New Session" | 1 | correctness | 3/6 Plausible | 16 | — | `npm run implement -- --issue 321484` |
| 47 | [#304538](https://github.com/microsoft/vscode/issues/304538) | Issues initiating CLI chats from new welcome (duplicate sessions, missing model picker) | 0 | correctness | 3/6 Plausible | 16 | — | `npm run implement -- --issue 304538` |
| 53 | [#308647](https://github.com/microsoft/vscode/issues/308647) | [Copilot CLI] Failed to load chat session | 0 | correctness | 2/6 Unverified | 15 | — | — |
| 72 | [#308473](https://github.com/microsoft/vscode/issues/308473) | Copilot CLI sessions no longer appear in the chat sidebar/history for single-prompt usage | 1 | correctness | 3/6 Plausible | 9 | — | — |
| 109 | [#324115](https://github.com/microsoft/vscode/issues/324115) | delegated from copilot session to cloud disappeared from UI | 0 | correctness | 3/6 Plausible | 4 | — | `npm run implement -- --issue 324115` |
| 114 | [#303877](https://github.com/microsoft/vscode/issues/303877) | Sessions App: Deleting a Fork conversation deletes work tree of original conversation | 0 | data-loss | 3/6 Plausible | 3 | — | `npm run implement -- --issue 303877` |
| 133 | [#296823](https://github.com/microsoft/vscode/issues/296823) | Copilot chat window not accessible any more because of `Unknown event type: "session.mode_changed"` | 0 | correctness | 2/6 Unverified | 2 | — | — |
| 161 | [#272620](https://github.com/microsoft/vscode/issues/272620) | CLI sessions are sorted by creation time instead of last update time | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 272620` |
| 187 | [#311405](https://github.com/microsoft/vscode/issues/311405) | "cancelled error" in output after clicking on a copilot cli session from the sessions history | 0 | correctness | 4/6 Traced | 0 | — | `npm run implement -- --issue 311405` |
| 193 | [#313818](https://github.com/microsoft/vscode/issues/313818) | Vscode Agents insider  — "Mark as Done" cannot close the tab | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 313818` |
| 201 | [#322521](https://github.com/microsoft/vscode/issues/322521) | Session disappears from session list | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 322521` |
| 203 | [#323501](https://github.com/microsoft/vscode/issues/323501) | Thinking effort not remembered for Copilot CLI | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 323501` |

### Model selection (16)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 7 | [#314211](https://github.com/microsoft/vscode/issues/314211) | Copilot keeps reverting back to Auto in VS Code Agents | 4 | correctness | 3/6 Plausible | 65 | — | `npm run implement -- --issue 314211` |
| 11 | [#317276](https://github.com/microsoft/vscode/issues/317276) | Custom agent selection silently reverts to generic Agent mid-session; chat dropdown still shows the stale (correct) selection while the runtime has switched | 3 | correctness | 5/6 Source-confirmed | 51 | — | `npm run implement -- --issue 317276` |
| 44 | [#311243](https://github.com/microsoft/vscode/issues/311243) | No edit pills for gpt models | 0 | visual | 6/6 Confirmed | 17 | — | `npm run implement -- --issue 311243` |
| 45 | [#317268](https://github.com/microsoft/vscode/issues/317268) | Copilot CLI BYOK chat history cannot display | 0 | correctness | 3/6 Plausible | 17 | — | — |
| 49 | [#319740](https://github.com/microsoft/vscode/issues/319740) | Agents window model randomly changes | 1 | correctness | — | 15 | — | — |
| 54 | [#309205](https://github.com/microsoft/vscode/issues/309205) | Copilot CLI: Claude Code Agents not visible in Copilot CLI | 0 | correctness | 3/6 Plausible | 15 | — | `npm run implement -- --issue 309205` |
| 90 | [#299578](https://github.com/microsoft/vscode/issues/299578) | Model Picker dissappears in CLI if you are mid session | 1 | visual | 4/6 Traced | 6 | yes | `npm run implement -- --issue 299578` |
| 121 | [#322267](https://github.com/microsoft/vscode/issues/322267) | 🐛 Bug: VS Code Agent Browser uses unsupported Model Claude Haiku 4.5 (WSL environment) | 0 | correctness | 2/6 Unverified | 3 | — | — |
| 135 | [#312787](https://github.com/microsoft/vscode/issues/312787) | Model picker has wrong state for 1-2 seconds after reload | 0 | visual | 6/6 Confirmed | 2 | — | `npm run implement -- --issue 312787` |
| 152 | [#307449](https://github.com/microsoft/vscode/issues/307449) | After running Copilot CLI in Agent mode, it is not able to switch to Plan mode | 0 | papercut | 3/6 Plausible | 1 | — | — |
| 153 | [#315816](https://github.com/microsoft/vscode/issues/315816) | Agent mode fails to process a prompt | 0 | papercut | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 315816` |
| 154 | [#325174](https://github.com/microsoft/vscode/issues/325174) | Agents window says no model available when a workspace is not selected | 0 | visual | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 325174` |
| 172 | [#295939](https://github.com/microsoft/vscode/issues/295939) | Background agent model picker not respecting hidden models | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 191 | [#312830](https://github.com/microsoft/vscode/issues/312830) | Model picker doesn't lock preference until message is sent | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 312830` |
| 204 | [#324995](https://github.com/microsoft/vscode/issues/324995) | Using Rubber Duck agent switches model in model picker | 0 | correctness | — | 0 | — | `npm run implement -- --issue 324995` |
| 206 | [#326941](https://github.com/microsoft/vscode/issues/326941) | Chat: a fallback/automatic model (Auto) is persisted into session/draft input-state as if user-selected | 0 | papercut | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 326941` |

### Notebook UI (29)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 5 | [#168807](https://github.com/microsoft/vscode/issues/168807) | Cell collapse doesn't persist between VSC sessions | 10 | correctness | 5/6 Source-confirmed | 65 | yes | `npm run implement -- --issue 168807` |
| 28 | [#295047](https://github.com/microsoft/vscode/issues/295047) | Keeps loading on "Retrieving Notebook Summary" | 0 | freeze | 3/6 Plausible | 25 | — | — |
| 36 | [#289225](https://github.com/microsoft/vscode/issues/289225) | its stuck on retrieving notebook summary for 2 queries | 0 | freeze | 3/6 Plausible | 20 | — | — |
| 50 | [#133761](https://github.com/microsoft/vscode/issues/133761) | A second instance of a notebook is opened when debugging with two editor groups | 0 | correctness | 2/6 Unverified | 15 | — | — |
| 57 | [#206007](https://github.com/microsoft/vscode/issues/206007) | Kernel picker spinner never stops | 6 | visual | 4/6 Traced | 14 | yes | `npm run implement -- --issue 206007` |
| 59 | [#263949](https://github.com/microsoft/vscode/issues/263949) | [Loc]Strings of "Switch/Edit Slide Type", "Add /Edit Cell Tags" and "Mark Cell as Parameters" in drop-down menu of "..."are not translated. | 0 | correctness | — | 14 | — | `npm run implement -- --issue 263949` |
| 65 | [#260053](https://github.com/microsoft/vscode/issues/260053) | Notebook Kernel API tests:  cell execute command takes arguments | 0 | correctness | 3/6 Plausible | 11 | — | `npm run implement -- --issue 260053` |
| 68 | [#119727](https://github.com/microsoft/vscode/issues/119727) | Cell tabs stops and keyboard navigation issues | 0 | correctness | 3/6 Plausible | 10 | — | `npm run implement -- --issue 119727` |
| 81 | [#162018](https://github.com/microsoft/vscode/issues/162018) | Cell context menu should use NotebookCell as context like the cell toolbar | 0 | correctness | 5/6 Source-confirmed | 8 | yes | `npm run implement -- --issue 162018` |
| 91 | [#165629](https://github.com/microsoft/vscode/issues/165629) | [Notebooks] - "go to most recently failed cell" still in toolbar after restarting kernel and clearing outputs | 0 | visual | 5/6 Source-confirmed | 6 | — | `npm run implement -- --issue 165629` |
| 98 | [#270722](https://github.com/microsoft/vscode/issues/270722) | CMD-W closes figure and jupyter notebook | 0 | papercut | 6/6 Confirmed | 5 | — | `npm run implement -- --issue 270722` |
| 99 | [#295673](https://github.com/microsoft/vscode/issues/295673) | Can't highlight while scrolling in Jupyter notebooks | 0 | correctness | 3/6 Plausible | 5 | — | `npm run implement -- --issue 295673` |
| 102 | [#124529](https://github.com/microsoft/vscode/issues/124529) | command not working in NotebookCellStatusBarItemProvider | 0 | correctness | 5/6 Source-confirmed | 4 | — | `npm run implement -- --issue 124529` |
| 103 | [#125119](https://github.com/microsoft/vscode/issues/125119) | Bad resize behavior crowed status bar | 0 | visual | 5/6 Source-confirmed | 4 | yes | `npm run implement -- --issue 125119` |
| 104 | [#231226](https://github.com/microsoft/vscode/issues/231226) | revertAndCloseActiveEditor doesn't work on notebooks | 0 | correctness | 5/6 Source-confirmed | 4 | — | `npm run implement -- --issue 231226` |
| 105 | [#236291](https://github.com/microsoft/vscode/issues/236291) | Cell toolbars are not correct on newly opened notebook | 0 | visual | 3/6 Plausible | 4 | — | — |
| 111 | [#205285](https://github.com/microsoft/vscode/issues/205285) | Notebook Kernel API tests failed | 0 | correctness | 6/6 Confirmed | 3 | — | `npm run implement -- --issue 205285` |
| 124 | [#125227](https://github.com/microsoft/vscode/issues/125227) | Hand mouse pointer is shown when drag and drop is disabled | 0 | visual | 6/6 Confirmed | 2 | — | `npm run implement -- --issue 125227` |
| 146 | [#227982](https://github.com/microsoft/vscode/issues/227982) | Notebook Diff Editor layout issues when cells have a horizontal scrollbar | 0 | visual | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 227982` |
| 147 | [#242478](https://github.com/microsoft/vscode/issues/242478) | No empty cell hint "Select language, or fill with template ..." in notebook files. | 0 | visual | 6/6 Confirmed | 1 | — | `npm run implement -- --issue 242478` |
| 149 | [#292792](https://github.com/microsoft/vscode/issues/292792) | setTextDocumentLanguage for notebook cells | 0 | papercut | 6/6 Confirmed | 1 | — | `npm run implement -- --issue 292792` |
| 155 | [#180080](https://github.com/microsoft/vscode/issues/180080) | Notebook cell language selection UI doesn't use custom language icons | 0 | visual | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 180080` |
| 156 | [#211092](https://github.com/microsoft/vscode/issues/211092) | Copy cell down should preserve the view state of the cell | 0 | papercut | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 211092` |
| 157 | [#226909](https://github.com/microsoft/vscode/issues/226909) | Change rendered text in readonly markdown code to not include `or p;ress enter to edit` | 0 | papercut | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 226909` |
| 158 | [#229486](https://github.com/microsoft/vscode/issues/229486) | Should cell input lose focus when hidden lines are expanded? | 0 | papercut | — | 0 | — | `npm run implement -- --issue 229486` |
| 163 | [#282721](https://github.com/microsoft/vscode/issues/282721) | Notebook diff editor doesn't preserve scroll position when switching to another tab and then back | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 282721` |
| 165 | [#289161](https://github.com/microsoft/vscode/issues/289161) | Kernel wont detect | 0 | none | 3/6 Plausible | 0 | — | — |
| 170 | [#294567](https://github.com/microsoft/vscode/issues/294567) | Keeps saying "Detecting Kernels" in a ipynb | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 188 | [#311773](https://github.com/microsoft/vscode/issues/311773) | Se queda pegado el kernel | 0 | none | 3/6 Plausible | 0 | — | — |

### Terminal environment (20)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 8 | [#286553](https://github.com/microsoft/vscode/issues/286553) | Copilot Chat extension corrupts remote $PATH on Linux by injecting Windows-style path with semicolon | 2 | correctness | 6/6 Confirmed | 63 | — | `npm run implement -- --issue 286553` |
| 14 | [#293310](https://github.com/microsoft/vscode/issues/293310) | Terminal command edits are silently ignored when using Claude Agent SDK (works correctly with regular Copilot) | 0 | correctness | 5/6 Source-confirmed | 42 | yes | `npm run implement -- --issue 293310` |
| 64 | [#306171](https://github.com/microsoft/vscode/issues/306171) | Terminal commands hang indefinitely in Local/Copilot CLI | 1 | correctness | 3/6 Plausible | 11 | — | `npm run implement -- --issue 306171` |
| 80 | [#316791](https://github.com/microsoft/vscode/issues/316791) | Agents App: git commit hangs when commit signing (gpg.format=ssh) is enabled due to missing GIT_ASKPASS environment variable | 1 | correctness | 5/6 Source-confirmed | 8 | — | `npm run implement -- --issue 316791` |
| 85 | [#297829](https://github.com/microsoft/vscode/issues/297829) | Open Worktree context menu items no-op for Copilot CLI sessions from terminal | 0 | correctness | 6/6 Confirmed | 7 | — | `npm run implement -- --issue 297829` |
| 101 | [#309032](https://github.com/microsoft/vscode/issues/309032) | Integrated terminal on Windows can start with stale PATH and fail to resolve npm while standalone PowerShell works | 0 | papercut | 3/6 Plausible | 5 | — | — |
| 116 | [#308847](https://github.com/microsoft/vscode/issues/308847) | Windows-style path separators/backslashes used in chat pane when connected to Linux server | 0 | correctness | 4/6 Traced | 3 | yes | `npm run implement -- --issue 308847` |
| 118 | [#315766](https://github.com/microsoft/vscode/issues/315766) | agent sessions window: uv not working | 0 | correctness | 3/6 Plausible | 3 | — | `npm run implement -- --issue 315766` |
| 130 | [#293910](https://github.com/microsoft/vscode/issues/293910) | Environment variables leak into launced program | 0 | correctness | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 293910` |
| 139 | [#317542](https://github.com/microsoft/vscode/issues/317542) | Terminal ui | 0 | none | 3/6 Plausible | 2 | — | — |
| 166 | [#291990](https://github.com/microsoft/vscode/issues/291990) | Copilot CLI shim (copilot.ps1) fails to find npm-installed binary on Windows when both are in PATH | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 291990` |
| 173 | [#296080](https://github.com/microsoft/vscode/issues/296080) | Terminal flickers when moving between Copilot CLI response options | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 296080` |
| 180 | [#299201](https://github.com/microsoft/vscode/issues/299201) | `copilot` calls itself recursively due to bug in `$PATH` normalization | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 299201` |
| 181 | [#299600](https://github.com/microsoft/vscode/issues/299600) | CLI session isolation: Confusing to have two identical folder icons | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 299600` |
| 182 | [#299618](https://github.com/microsoft/vscode/issues/299618) | github.copilot.chat.cli.branchSupport.enabled doesn't have immediate effect | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 299618` |
| 183 | [#299627](https://github.com/microsoft/vscode/issues/299627) | Copilot CLI: Misleading worktree icon and hover text, no visual distinction between worktree/workspace sessions | 0 | papercut | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 299627` |
| 190 | [#312760](https://github.com/microsoft/vscode/issues/312760) | Copilot CLI writes outside of workspace without asking | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 312760` |
| 192 | [#312850](https://github.com/microsoft/vscode/issues/312850) | copilot CLI asked for tool output permissions | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 312850` |
| 194 | [#314875](https://github.com/microsoft/vscode/issues/314875) | Copilot CLI agent: all tools fail when CWD is a WSL path (\\wsl.localhost\...) | 0 | correctness | 6/6 Confirmed | 0 | — | — |
| 196 | [#315781](https://github.com/microsoft/vscode/issues/315781) | GitHub-cli session gets automatically moved under parent git directory | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 315781` |

### Chat UI errors (18)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 9 | [#321265](https://github.com/microsoft/vscode/issues/321265) | Chat Sessions smoke test crashes the extension host on Windows (heap corruption in @github/copilot runtime.node) | 0 | crash | 2/6 Unverified | 54 | — | `npm run implement -- --issue 321265` |
| 38 | [#293255](https://github.com/microsoft/vscode/issues/293255) | Issues in copilot chat Claude agent UI | 0 | correctness | 3/6 Plausible | 19 | — | `npm run implement -- --issue 293255` |
| 55 | [#314692](https://github.com/microsoft/vscode/issues/314692) | Attachments not working properly in the Chat | 0 | correctness | 3/6 Plausible | 15 | — | `npm run implement -- --issue 314692` |
| 79 | [#319002](https://github.com/microsoft/vscode/issues/319002) | [Error] [GitHub.copilot-chat] unhandlederror-Cannot read properties of null (reading 'value') | 0 | correctness | 5/6 Source-confirmed | 9 | yes | `npm run implement -- --issue 319002` |
| 86 | [#311327](https://github.com/microsoft/vscode/issues/311327) | Button segment height inconsistent | 0 | visual | 2/6 Unverified | 7 | — | `npm run implement -- --issue 311327` |
| 87 | [#311708](https://github.com/microsoft/vscode/issues/311708) | [Error] unhandlederror-potential listener LEAK detected, popular — textModel / chatEditingModifiedNotebookEntry | 0 | perf | 5/6 Source-confirmed | 7 | yes | `npm run implement -- --issue 311708` |
| 89 | [#295267](https://github.com/microsoft/vscode/issues/295267) | Pasted image experience across agent types | 1 | visual | 3/6 Plausible | 6 | — | `npm run implement -- --issue 295267` |
| 93 | [#309858](https://github.com/microsoft/vscode/issues/309858) | bug report | 0 | none | 3/6 Plausible | 6 | — | — |
| 96 | [#316444](https://github.com/microsoft/vscode/issues/316444) | [Error] [GitHub.copilot-chat] unhandlederror-Response stream has been closed | 0 | correctness | 5/6 Source-confirmed | 6 | yes | `npm run implement -- --issue 316444` |
| 107 | [#318225](https://github.com/microsoft/vscode/issues/318225) | [Error] unhandlederror-The specified module could not be found. \\?\\extensions\copilot\node_modules\@github... | 0 | correctness | 5/6 Source-confirmed | 4 | — | `npm run implement -- --issue 318225` |
| 119 | [#316429](https://github.com/microsoft/vscode/issues/316429) | [Regression] [Error] [GitHub.copilot-chat] unhandlederror-This operation was aborted | 0 | papercut | 5/6 Source-confirmed | 3 | — | `npm run implement -- --issue 316429` |
| 120 | [#317055](https://github.com/microsoft/vscode/issues/317055) | [Regression] [Error] [GitHub.copilot-chat] unhandlederror-Assertion Failed: Argument is `undefined` or `null`. | 0 | correctness | 5/6 Source-confirmed | 3 | — | `npm run implement -- --issue 317055` |
| 123 | [#326632](https://github.com/microsoft/vscode/issues/326632) | [Error] [GitHub.copilot-chat] unhandlederror-Error in extension github.copilot-chat: FAILED to handle event: Cannot read propertie... | 0 | correctness | 5/6 Source-confirmed | 3 | — | `npm run implement -- --issue 326632` |
| 141 | [#318776](https://github.com/microsoft/vscode/issues/318776) | [Regression] [Error] unhandlederror-Cannot read properties of undefined (reading 'uri') | 0 | correctness | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 318776` |
| 189 | [#312338](https://github.com/microsoft/vscode/issues/312338) | builtInExtensionsEnabledWithAutoUpdates causes copilot-chat to have two conflicting versions, crashing chat initialization | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 195 | [#315606](https://github.com/microsoft/vscode/issues/315606) | Selecting Input from Chat Chat Input Editor updates the UI in another Chat Input Editor | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 315606` |
| 200 | [#322469](https://github.com/microsoft/vscode/issues/322469) | Chat view cannot correctly render inline code containing a command with arguments | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 322469` |
| 207 | [#326947](https://github.com/microsoft/vscode/issues/326947) | Agents window: chat response not rendered even though the data was returned (UI stops updating mid-stream; a window resize recovers it) | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 326947` |

### Background delegation (15)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 12 | [#296407](https://github.com/microsoft/vscode/issues/296407) | Loop of delegating plan to background agent | 0 | correctness | 3/6 Plausible | 48 | — | `npm run implement -- --issue 296407` |
| 25 | [#296186](https://github.com/microsoft/vscode/issues/296186) | Clicking continue in background to start implementation of copilot agent plan causes session to disappear | 1 | correctness | 5/6 Source-confirmed | 27 | — | `npm run implement -- --issue 296186` |
| 34 | [#282393](https://github.com/microsoft/vscode/issues/282393) | Background agent: Apply changed files should change state after I applied once | 0 | correctness | 3/6 Plausible | 20 | — | `npm run implement -- --issue 282393` |
| 39 | [#286360](https://github.com/microsoft/vscode/issues/286360) | Background agent action is not working for new users | 1 | correctness | 3/6 Plausible | 18 | — | — |
| 40 | [#291401](https://github.com/microsoft/vscode/issues/291401) | Implementation handoff uses summary instead of actual plan file | 1 | correctness | 3/6 Plausible | 18 | — | `npm run implement -- --issue 291401` |
| 41 | [#309284](https://github.com/microsoft/vscode/issues/309284) | Agents: thread can disappear immediately while background agent keeps running and editing the workspace | 1 | correctness | 3/6 Plausible | 17 | — | `npm run implement -- --issue 309284` |
| 58 | [#309637](https://github.com/microsoft/vscode/issues/309637) | Agents: Parallel back-ground tasks are executed sequential | 1 | correctness | 3/6 Plausible | 14 | — | `npm run implement -- --issue 309637` |
| 70 | [#324789](https://github.com/microsoft/vscode/issues/324789) | /compact doesnt seem to work in AH | 0 | correctness | 3/6 Plausible | 10 | — | `npm run implement -- --issue 324789` |
| 84 | [#293169](https://github.com/microsoft/vscode/issues/293169) | Background agent does not work | 0 | none | 3/6 Plausible | 7 | — | — |
| 94 | [#311207](https://github.com/microsoft/vscode/issues/311207) | "Plan approved" then it just stopped | 0 | correctness | 3/6 Plausible | 6 | — | `npm run implement -- --issue 311207` |
| 134 | [#302968](https://github.com/microsoft/vscode/issues/302968) | why cloud agent | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 164 | [#284749](https://github.com/microsoft/vscode/issues/284749) | No option to migrate/copy changes when delegating from an untitled prompt file | 0 | correctness | — | 0 | — | `npm run implement -- --issue 284749` |
| 176 | [#296825](https://github.com/microsoft/vscode/issues/296825) | Background agent fails, but does not output error message in UI | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 296825` |
| 177 | [#296828](https://github.com/microsoft/vscode/issues/296828) | Background agents keep trying to read `plan.md` that does not exist in my project | 0 | papercut | 2/6 Unverified | 0 | — | — |
| 179 | [#296891](https://github.com/microsoft/vscode/issues/296891) | Delegating from background worktree doesn't take changes from worktree | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 296891` |

### Tools and MCP (16)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 15 | [#317460](https://github.com/microsoft/vscode/issues/317460) | Agents Window: MCP server contributed by extension is not available | 0 | correctness | 4/6 Traced | 35 | — | `npm run implement -- --issue 317460` |
| 27 | [#325670](https://github.com/microsoft/vscode/issues/325670) | Skills don't always show as completions in agents window | 0 | correctness | 5/6 Source-confirmed | 26 | — | `npm run implement -- --issue 325670` |
| 32 | [#313437](https://github.com/microsoft/vscode/issues/313437) | Feature request: Support `#tool:todo` and `#tool:vscode/askQuestions` when delegating session to Copilot CLI | 0 | none | — | 22 | — | `npm run implement -- --issue 313437` |
| 33 | [#314412](https://github.com/microsoft/vscode/issues/314412) | Copilot CLI: new session fails immediately — missing `github-context.yaml` sidekick agent file in extension bundle | 1 | correctness | 2/6 Unverified | 21 | — | — |
| 42 | [#327216](https://github.com/microsoft/vscode/issues/327216) | Slash commands (e.g. /chronicle, plugin skills) not listed in AHP until first message — regression | 1 | correctness | 5/6 Source-confirmed | 17 | — | `npm run implement -- --issue 327216` |
| 75 | [#304201](https://github.com/microsoft/vscode/issues/304201) | Copilot CLI: Hook creation doesn't work e2e | 0 | correctness | 3/6 Plausible | 9 | — | `npm run implement -- --issue 304201` |
| 82 | [#309118](https://github.com/microsoft/vscode/issues/309118) | Agents App: Fetched web content empty | 0 | visual | 3/6 Plausible | 8 | — | `npm run implement -- --issue 309118` |
| 128 | [#292609](https://github.com/microsoft/vscode/issues/292609) | Sampling MCP requests and user consent | 0 | none | 3/6 Plausible | 2 | — | — |
| 138 | [#316266](https://github.com/microsoft/vscode/issues/316266) | MCP stdio servers pointing to a batch file on Windows cause two issues | 0 | papercut | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 316266` |
| 142 | [#319606](https://github.com/microsoft/vscode/issues/319606) | [Regression] [Error] [GitHub.copilot-chat] listen ENOTSUP — operation not supported on socket (MCP server start) | 0 | correctness | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 319606` |
| 144 | [#325671](https://github.com/microsoft/vscode/issues/325671) | "VS Code Synced Data" shows in slash completions | 0 | visual | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 325671` |
| 184 | [#300869](https://github.com/microsoft/vscode/issues/300869) | .copilot MCP confits not loaded in Copilot CLI | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 300869` |
| 198 | [#316285](https://github.com/microsoft/vscode/issues/316285) | Agents: Slash commands from local Agent Plugin autocomplete correctly but fail to load prompt file content | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 316285` |
| 202 | [#323389](https://github.com/microsoft/vscode/issues/323389) | Copilot SDK API calls for commands do not seem to end up in events.jsonl | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 323389` |
| 205 | [#326416](https://github.com/microsoft/vscode/issues/326416) | Agent host: unwanted implicit repo attachments | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 326416` |
| 209 | [#327338](https://github.com/microsoft/vscode/issues/327338) | Delays starting Copilot Agent Host sessions in VS Code and Copilot CLI sessions in terminal | 0 | perf | 3/6 Plausible | 0 | — | `npm run implement -- --issue 327338` |

### Notebook editing (27)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 16 | [#314579](https://github.com/microsoft/vscode/issues/314579) | Copilot->Claude often claims to edit a notebook but fails | 2 | correctness | 3/6 Plausible | 34 | — | `npm run implement -- --issue 314579` |
| 35 | [#286144](https://github.com/microsoft/vscode/issues/286144) | GitHub Copilot Chat unable to adjust code in Jupyter Notebooks | 0 | none | 3/6 Plausible | 20 | — | — |
| 43 | [#166161](https://github.com/microsoft/vscode/issues/166161) | Issue with "reopen editor with" -> Jupyter notebook | 0 | correctness | 4/6 Traced | 17 | — | `npm run implement -- --issue 166161` |
| 51 | [#285902](https://github.com/microsoft/vscode/issues/285902) | Copilot Chat fails in Jupyter Notebook with “Unsupported kind 'markdown'” when Notebook Alternative Format is set to markdown | 0 | correctness | 5/6 Source-confirmed | 15 | yes | `npm run implement -- --issue 285902` |
| 52 | [#286255](https://github.com/microsoft/vscode/issues/286255) | background agent 'illegal argument' when a notebook is open | 0 | correctness | 2/6 Unverified | 15 | — | `npm run implement -- --issue 286255` |
| 60 | [#304551](https://github.com/microsoft/vscode/issues/304551) | Notebook cell content landed in chat | 0 | correctness | 3/6 Plausible | 13 | — | `npm run implement -- --issue 304551` |
| 62 | [#296284](https://github.com/microsoft/vscode/issues/296284) | Copilot Review appears to do nothing in a Jupyter Notebook | 1 | correctness | 4/6 Traced | 11 | yes | `npm run implement -- --issue 296284` |
| 63 | [#301184](https://github.com/microsoft/vscode/issues/301184) | Edit notebook tools not working | 1 | correctness | 3/6 Plausible | 11 | — | `npm run implement -- --issue 301184` |
| 69 | [#286061](https://github.com/microsoft/vscode/issues/286061) | Jupyter Notebook cell rendering becomes vertically misaligned after Copilot Chat edits | 0 | visual | 2/6 Unverified | 10 | — | — |
| 71 | [#305970](https://github.com/microsoft/vscode/issues/305970) | Notebook too large and copilot fails to write into them? | 1 | correctness | 3/6 Plausible | 9 | — | — |
| 73 | [#235870](https://github.com/microsoft/vscode/issues/235870) | Git Diff Viewer Fails After Updating Images in Markdown Cells | 0 | freeze | 6/6 Confirmed | 9 | — | `npm run implement -- --issue 235870` |
| 74 | [#297116](https://github.com/microsoft/vscode/issues/297116) | Agent edits cause the notebook model to become corrupt | 0 | correctness | 3/6 Plausible | 9 | — | `npm run implement -- --issue 297116` |
| 110 | [#327473](https://github.com/microsoft/vscode/issues/327473) | Why does the built-in AI agent tool, edit_notebook_file, often fail to edit, meaning it executes but doesn't make any changes? However, it never has any problems when editing a brand new notebook. | 0 | correctness | 5/6 Source-confirmed | 4 | — | `npm run implement -- --issue 327473` |
| 112 | [#287886](https://github.com/microsoft/vscode/issues/287886) | agent thinks the edits went through when they didn't when doing jupyter notebook cell operations | 0 | correctness | 5/6 Source-confirmed | 3 | yes | `npm run implement -- --issue 287886` |
| 117 | [#314367](https://github.com/microsoft/vscode/issues/314367) | Notebook read_cell_output tool reports "output is too big" for any output size | 0 | correctness | 2/6 Unverified | 3 | — | — |
| 125 | [#235871](https://github.com/microsoft/vscode/issues/235871) | Save Jupyter notebook failed if the .ipynb extension was removed in the save filename dialog box | 0 | correctness | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 235871` |
| 126 | [#273192](https://github.com/microsoft/vscode/issues/273192) | Creating an Jupyter notebook resulted in an empty notebook with no content | 0 | correctness | 3/6 Plausible | 2 | — | `npm run implement -- --issue 273192` |
| 127 | [#288252](https://github.com/microsoft/vscode/issues/288252) | Edit mode not making changes to notebook in the followup prompts | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 136 | [#313473](https://github.com/microsoft/vscode/issues/313473) | Jupyter is Shit inside Vscode | 0 | none | 3/6 Plausible | 2 | — | — |
| 148 | [#264499](https://github.com/microsoft/vscode/issues/264499) | Notebook NES: Stuck in previous edit | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 162 | [#281034](https://github.com/microsoft/vscode/issues/281034) | Chat Agent (Opus 4.5) doesn't show changes made to notebooks | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 281034` |
| 168 | [#293883](https://github.com/microsoft/vscode/issues/293883) | Generated Jupyter Notebook is 'backwards' - the cells are in the reverse order | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 293883` |
| 171 | [#294578](https://github.com/microsoft/vscode/issues/294578) | Copilot Chat attaches to prior notebook edits and shows Keep diff on manual cells when reopening long chat | 0 | visual | 3/6 Plausible | 0 | — | — |
| 175 | [#296202](https://github.com/microsoft/vscode/issues/296202) | Copilot will not make edits to notebook | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 178 | [#296849](https://github.com/microsoft/vscode/issues/296849) | AI Agent isn't changing cells in Jupyter notebook | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 185 | [#307415](https://github.com/microsoft/vscode/issues/307415) | Cannot read jupyter outputs in vscode running R kernel. | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 208 | [#327293](https://github.com/microsoft/vscode/issues/327293) | Notebook editor shows stale cell source during Copilot notebook edits | 0 | correctness | 3/6 Plausible | 0 | — | — |

### Other (29)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 13 | [#313372](https://github.com/microsoft/vscode/issues/313372) | [Agents] Forked sessions do not use the default approval settings | 0 | correctness | 5/6 Source-confirmed | 47 | yes | `npm run implement -- --issue 313372` |
| 19 | [#314576](https://github.com/microsoft/vscode/issues/314576) | copilot_getNotebookSummary needs a freaking timeout and clear error | 1 | freeze | 5/6 Source-confirmed | 31 | yes | `npm run implement -- --issue 314576` |
| 20 | [#309461](https://github.com/microsoft/vscode/issues/309461) | Copilot CLI session log lists wrong github branch | 0 | correctness | 6/6 Confirmed | 31 | — | `npm run implement -- --issue 309461` |
| 21 | [#315144](https://github.com/microsoft/vscode/issues/315144) | Agents: MCP servers get interrupted | 0 | correctness | 3/6 Plausible | 31 | — | `npm run implement -- --issue 315144` |
| 23 | [#281471](https://github.com/microsoft/vscode/issues/281471) | Run & Debug toolbar disappears | 0 | correctness | 3/6 Plausible | 28 | — | `npm run implement -- --issue 281471` |
| 26 | [#316588](https://github.com/microsoft/vscode/issues/316588) | Agents Window: permission prompt for writing files outside workspace never appears, causing silent hang | 0 | correctness | 3/6 Plausible | 27 | — | `npm run implement -- --issue 316588` |
| 37 | [#307655](https://github.com/microsoft/vscode/issues/307655) | Agents: /plan can be partially used in a new session | 0 | correctness | 3/6 Plausible | 20 | — | `npm run implement -- --issue 307655` |
| 48 | [#318126](https://github.com/microsoft/vscode/issues/318126) | Copilot CLI session errors out when opened via the Copilot Chat extension | 0 | correctness | 3/6 Plausible | 16 | — | `npm run implement -- --issue 318126` |
| 56 | [#316282](https://github.com/microsoft/vscode/issues/316282) | Copilot CLI session fails in detached HEAD state due to incorrect branch selection | 0 | correctness | 5/6 Source-confirmed | 15 | yes | `npm run implement -- --issue 316282` |
| 67 | [#309471](https://github.com/microsoft/vscode/issues/309471) | Copilot CLI does not follow '**' instructions | 0 | correctness | 3/6 Plausible | 11 | — | `npm run implement -- --issue 309471` |
| 76 | [#306059](https://github.com/microsoft/vscode/issues/306059) | Subagents not rendered correctly for copilot-cli in sessions app | 0 | visual | 2/6 Unverified | 9 | — | `npm run implement -- --issue 306059` |
| 77 | [#311717](https://github.com/microsoft/vscode/issues/311717) | Agents: Plan file not shown in session artifacts panel | 0 | correctness | 3/6 Plausible | 9 | — | `npm run implement -- --issue 311717` |
| 83 | [#316401](https://github.com/microsoft/vscode/issues/316401) | Agents App: Allow me to edit queued prompts | 0 | papercut | 3/6 Plausible | 8 | — | `npm run implement -- --issue 316401` |
| 88 | [#327754](https://github.com/microsoft/vscode/issues/327754) | Custom instructions not applied to remote AH | 0 | correctness | 5/6 Source-confirmed | 7 | yes | `npm run implement -- --issue 327754` |
| 92 | [#236329](https://github.com/microsoft/vscode/issues/236329) | Notebook: Cannot move a markdown cell that is in edit mode | 0 | papercut | 5/6 Source-confirmed | 6 | yes | `npm run implement -- --issue 236329` |
| 97 | [#322939](https://github.com/microsoft/vscode/issues/322939) | CLI seems to have problems loading diagnostics | 0 | correctness | 6/6 Confirmed | 6 | — | `npm run implement -- --issue 322939` |
| 113 | [#299527](https://github.com/microsoft/vscode/issues/299527) | Background agent permissions did not show for file outside of workspace | 0 | correctness | 3/6 Plausible | 3 | — | `npm run implement -- --issue 299527` |
| 115 | [#305571](https://github.com/microsoft/vscode/issues/305571) | Sessions: Terminal command approvals set at the workspace settings level do not get respected | 0 | correctness | 2/6 Unverified | 3 | — | — |
| 122 | [#323592](https://github.com/microsoft/vscode/issues/323592) | Agents window: "New Chat" button is a no-op from within a current session | 0 | correctness | 5/6 Source-confirmed | 3 | — | — |
| 129 | [#293091](https://github.com/microsoft/vscode/issues/293091) | The menu bar after the last update got changed into a burger menu and cannot be set back to normal (menu bar visibility is set up as classic)) | 0 | visual | 3/6 Plausible | 2 | — | — |
| 131 | [#294262](https://github.com/microsoft/vscode/issues/294262) | Change all occurrences doesn't work unless the Find menu is empty | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 140 | [#318690](https://github.com/microsoft/vscode/issues/318690) | When editing a GitHub Actions YAML file, strings that no longer exist are flagged as errors. | 0 | none | 3/6 Plausible | 2 | — | — |
| 145 | [#168675](https://github.com/microsoft/vscode/issues/168675) | Debugging untitled file in IW shows unbound breakpoints | 0 | correctness | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 168675` |
| 150 | [#299966](https://github.com/microsoft/vscode/issues/299966) | When connecting Copilot CLI from ghotty to vscode, the editor trancates all the text | 0 | visual | 3/6 Plausible | 1 | — | — |
| 151 | [#305911](https://github.com/microsoft/vscode/issues/305911) | When I selected part of the code, there were some problems when I expanded the selected range by sliding the mouse wheel | 0 | none | 3/6 Plausible | 1 | — | — |
| 159 | [#245893](https://github.com/microsoft/vscode/issues/245893) | Text to speech very verbose | 0 | papercut | 4/6 Traced | 0 | yes | `npm run implement -- --issue 245893` |
| 160 | [#265851](https://github.com/microsoft/vscode/issues/265851) | Extension API: Text Document Content Change Inconsistency | 0 | correctness | — | 0 | — | `npm run implement -- --issue 265851` |
| 169 | [#294381](https://github.com/microsoft/vscode/issues/294381) | "Selection changed" log spam | 0 | perf | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 294381` |
| 199 | [#321308](https://github.com/microsoft/vscode/issues/321308) | 每次都大返 | 0 | none | 3/6 Plausible | 0 | — | — |

## Feature requests

### Notebook editing (8)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | [#192371](https://github.com/microsoft/vscode/issues/192371) | Enable support for notebooks at the "select language" mode | 35 | backlog-candidate | 100 | `npm run implement -- --issue 192371` |
| 3 | [#237074](https://github.com/microsoft/vscode/issues/237074) | Support Notebook Cell Level metadata such as Freeze/protect cell / skip execution/collapsed | 38 | active | 85 | `npm run implement -- --issue 237074` |
| 4 | [#235784](https://github.com/microsoft/vscode/issues/235784) | "Clear All Output" is greyed out and doesn't clear execution count unless output is available | 19 | dormant | 65 | `npm run implement -- --issue 235784` |
| 31 | [#226767](https://github.com/microsoft/vscode/issues/226767) | Only clicking on the icon expands collapsed cells, not the entire sash. | 0 | dormant | 3 | `npm run implement -- --issue 226767` |
| 33 | [#299457](https://github.com/microsoft/vscode/issues/299457) | Copilot can not edit plain json for `.jpynb` notebooks | 0 | active | 2 | — |
| 44 | [#264432](https://github.com/microsoft/vscode/issues/264432) | Polish Cross Cell Notebook NES experience | 0 | dormant | 0 | `npm run implement -- --issue 264432` |
| 51 | [#310360](https://github.com/microsoft/vscode/issues/310360) | UI: Separate "Delete Cell" icon from "More Actions" menu in Notebooks. | 0 | active | 0 | `npm run implement -- --issue 310360` |
| 58 | [#318348](https://github.com/microsoft/vscode/issues/318348) | Make the notebook's scrollbar resizable | 0 | active | 0 | `npm run implement -- --issue 318348` |

### Agent sessions (8)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 2 | [#276243](https://github.com/microsoft/vscode/issues/276243) | Agents View: support deletion of sessions | 13 | active | 97 | `npm run implement -- --issue 276243` |
| 6 | [#298712](https://github.com/microsoft/vscode/issues/298712) | Cannot edit messages in Claude Agent or Copilot CLI chat sessions | 0 | backlog-candidate | 45 | `npm run implement -- --issue 298712` |
| 8 | [#295834](https://github.com/microsoft/vscode/issues/295834) | Help users get started with + manage parallel agent sessions | 0 | active | 28 | `npm run implement -- --issue 295834` |
| 14 | [#300498](https://github.com/microsoft/vscode/issues/300498) | No pencil icon to rename Copilot CLI or Claude Agent sessions | 0 | active | 17 | `npm run implement -- --issue 300498` |
| 20 | [#301267](https://github.com/microsoft/vscode/issues/301267) | Support creating a new CLI session with the same folder/worktree | 0 | backlog-candidate | 13 | `npm run implement -- --issue 301267` |
| 49 | [#309027](https://github.com/microsoft/vscode/issues/309027) | Create new session from current worktree | 0 | active | 0 | `npm run implement -- --issue 309027` |
| 50 | [#309290](https://github.com/microsoft/vscode/issues/309290) | Non-agent host Copilot CLI Async terminals don't resume the session | 0 | backlog-candidate | 0 | `npm run implement -- --issue 309290` |
| 56 | [#313745](https://github.com/microsoft/vscode/issues/313745) | [Copilot-Chat] Support to Coninue cloud session in local | 0 | backlog-candidate | 0 | `npm run implement -- --issue 313745` |

### Workspace context (9)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 5 | [#321651](https://github.com/microsoft/vscode/issues/321651) | Support actual multi-root folder context with SDK/AHP harness | 0 | active | 49 | `npm run implement -- --issue 321651` |
| 17 | [#302658](https://github.com/microsoft/vscode/issues/302658) | Copilot CLI: can’t easily open a file in a worktree that was not modified by the agent. | 0 | active | 14 | `npm run implement -- --issue 302658` |
| 21 | [#275657](https://github.com/microsoft/vscode/issues/275657) | CCA: show context pill of the chat delegated from | 0 | active | 12 | `npm run implement -- --issue 275657` |
| 22 | [#300473](https://github.com/microsoft/vscode/issues/300473) | Show worktree / workspace picker in more agent scenarios | 0 | backlog-candidate | 11 | `npm run implement -- --issue 300473` |
| 23 | [#315192](https://github.com/microsoft/vscode/issues/315192) | External CLI session discovery in AHP/Copilot in VS Code window | 0 | active | 9 | `npm run implement -- --issue 315192` |
| 30 | [#323458](https://github.com/microsoft/vscode/issues/323458) | Multi-root: Pick workspace folder of the selected file/text when starting a new chat | 0 | active | 5 | `npm run implement -- --issue 323458` |
| 45 | [#287709](https://github.com/microsoft/vscode/issues/287709) | For Background Agents, let me choose the branch name. For important for tracking tickets. | 0 | active | 0 | — |
| 47 | [#299713](https://github.com/microsoft/vscode/issues/299713) | CLI session isolation: show name of worktree | 0 | active | 0 | `npm run implement -- --issue 299713` |
| 53 | [#313100](https://github.com/microsoft/vscode/issues/313100) | Provide a configurable way to show or hide external CLI sessions | 0 | backlog-candidate | 0 | `npm run implement -- --issue 313100` |

### Copilot CLI integration (10)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 7 | [#314806](https://github.com/microsoft/vscode/issues/314806) | Support `COPILOT_HOME` env var to relocate Copilot home directory. | 3 | active | 38 | `npm run implement -- --issue 314806` |
| 11 | [#256182](https://github.com/microsoft/vscode/issues/256182) | Improve copilot-setup-steps for better coding agent runs | 2 | active | 23 | — |
| 15 | [#293726](https://github.com/microsoft/vscode/issues/293726) | Improve Copilot CLI integration (terminal/editor) | 0 | backlog-candidate | 16 | `npm run implement -- --issue 293726` |
| 24 | [#323325](https://github.com/microsoft/vscode/issues/323325) | `~/.copilot/` folder ignores portable mode | 2 | active | 8 | `npm run implement -- --issue 323325` |
| 25 | [#296087](https://github.com/microsoft/vscode/issues/296087) | When Copilot CLI in terminal is ready for input, focuses the diff but not the terminal | 0 | active | 8 | `npm run implement -- --issue 296087` |
| 32 | [#296089](https://github.com/microsoft/vscode/issues/296089) | Unclear how to reopen diff from Copilot CLI in terminal | 0 | active | 2 | `npm run implement -- --issue 296089` |
| 35 | [#308263](https://github.com/microsoft/vscode/issues/308263) | Copilot CLI: No discard changes option? | 0 | backlog-candidate | 2 | `npm run implement -- --issue 308263` |
| 42 | [#323795](https://github.com/microsoft/vscode/issues/323795) | expose /btw from the Copilot CLI | 0 | active | 1 | `npm run implement -- --issue 323795` |
| 46 | [#296885](https://github.com/microsoft/vscode/issues/296885) | Notifying user when Copilot CLI terminal is waiting for user response via chat UI | 0 | backlog-candidate | 0 | `npm run implement -- --issue 296885` |
| 57 | [#316103](https://github.com/microsoft/vscode/issues/316103) | Allow calling Copilot CLI from extension | 0 | active | 0 | `npm run implement -- --issue 316103` |

### Agent tooling (7)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 9 | [#312053](https://github.com/microsoft/vscode/issues/312053) | AgentHost: Drive TODOs UI | 1 | backlog-candidate | 24 | `npm run implement -- --issue 312053` |
| 10 | [#300579](https://github.com/microsoft/vscode/issues/300579) | Debug events snapshot for Copilot CLI and Claude Agent | 3 | backlog-candidate | 23 | `npm run implement -- --issue 300579` |
| 12 | [#300574](https://github.com/microsoft/vscode/issues/300574) | Consider expanding set of tips for Copilot CLI and Claude Agent | 1 | backlog-candidate | 23 | `npm run implement -- --issue 300574` |
| 18 | [#308561](https://github.com/microsoft/vscode/issues/308561) | Agents app: Document skip vs migrate changes behavior | 0 | active | 14 | `npm run implement -- --issue 308561` |
| 19 | [#280691](https://github.com/microsoft/vscode/issues/280691) | Background agent does not check for problems after finishing task | 0 | backlog-candidate | 13 | `npm run implement -- --issue 280691` |
| 26 | [#308979](https://github.com/microsoft/vscode/issues/308979) | Agents app: support tool inspection/config | 1 | active | 7 | — |
| 48 | [#306090](https://github.com/microsoft/vscode/issues/306090) | Copilot CLI: Allow tool confirmations for specific arguments | 0 | backlog-candidate | 0 | `npm run implement -- --issue 306090` |

### Chat diagnostics (8)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 16 | [#296642](https://github.com/microsoft/vscode/issues/296642) | Different cloud and background options when delegating from local vs new empty chat | 0 | active | 15 | `npm run implement -- --issue 296642` |
| 27 | [#294637](https://github.com/microsoft/vscode/issues/294637) | You should be able to attach files that aren't in the workspace | 1 | active | 6 | `npm run implement -- --issue 294637` |
| 28 | [#309219](https://github.com/microsoft/vscode/issues/309219) | Chat artifacts settings don't support workspace settings | 0 | active | 6 | `npm run implement -- --issue 309219` |
| 29 | [#312784](https://github.com/microsoft/vscode/issues/312784) | No way to see what model Auto resolves to in debug logs | 1 | backlog-candidate | 5 | `npm run implement -- --issue 312784` |
| 36 | [#312781](https://github.com/microsoft/vscode/issues/312781) | Model used doesn't show on hover in auto mode as it does for VS Code agent | 0 | backlog-candidate | 2 | `npm run implement -- --issue 312781` |
| 37 | [#315807](https://github.com/microsoft/vscode/issues/315807) | No model upgrade story for Copilot CLI | 0 | active | 2 | `npm run implement -- --issue 315807` |
| 54 | [#313505](https://github.com/microsoft/vscode/issues/313505) | Anonymising tables for Co-pilot plotting inputs | 0 | active | 0 | `npm run implement -- --issue 313505` |
| 55 | [#313509](https://github.com/microsoft/vscode/issues/313509) | Chat Debug: Add ability to filter by call type (tool calls vs internal agent calls) | 0 | active | 0 | `npm run implement -- --issue 313509` |

### Editor surfaces (6)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 34 | [#300729](https://github.com/microsoft/vscode/issues/300729) | Keep secondary sidebar maximized when opening primary sidebar | 0 | active | 2 | `npm run implement -- --issue 300729` |
| 38 | [#316820](https://github.com/microsoft/vscode/issues/316820) | API: expose Explorer view selection to extensions (read + change event) | 0 | active | 2 | `npm run implement -- --issue 316820` |
| 40 | [#293553](https://github.com/microsoft/vscode/issues/293553) | Code highlighting doesn't have option for Kusto (KQL) | 0 | active | 1 | — |
| 41 | [#312364](https://github.com/microsoft/vscode/issues/312364) | Indicador ficheros modificados | 0 | active | 1 | — |
| 43 | [#227999](https://github.com/microsoft/vscode/issues/227999) | Support for Inline Diff view in addition to Side by Side | 0 | dormant | 0 | `npm run implement -- --issue 227999` |
| 52 | [#312054](https://github.com/microsoft/vscode/issues/312054) | Multi-file Editor for arbitrary files  (continuous scroll editing) | 0 | active | 0 | `npm run implement -- --issue 312054` |

### Other (2)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 13 | [#311413](https://github.com/microsoft/vscode/issues/311413) | Plan mode is not easily discoverable | 0 | active | 18 | `npm run implement -- --issue 311413` |
| 39 | [#292049](https://github.com/microsoft/vscode/issues/292049) | There is no android or ios application to install VS Code - Tauri | 0 | active | 1 | — |
