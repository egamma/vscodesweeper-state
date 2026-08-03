# Top issues by theme — bhavyaus

Experimental themed view of [the flat ranking](bhavyaus.md); themes assigned by the review engine. Rank/score are the lane-wide values. Generated 2026-08-03 15:25 UTC.

## Bugs

### Model response failures (9)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | [#253126](https://github.com/microsoft/vscode/issues/253126) | Meta: Sorry, no response was returned | 93 | correctness | 6/6 Confirmed | 100 | — | — |
| 2 | [#321432](https://github.com/microsoft/vscode/issues/321432) | Agent turn hangs indefinitely when a streaming response stalls (no idle timeout in messagesApi/responsesApi SSE read loop) | 1 | freeze | 6/6 Confirmed | 5 | — | — |
| 6 | [#312581](https://github.com/microsoft/vscode/issues/312581) | Copilot Chat Agent: "response hit the length limit" abruptly stops with no continue option | 2 | correctness | 6/6 Confirmed | 2 | — | — |
| 9 | [#281023](https://github.com/microsoft/vscode/issues/281023) | Very early hit on response length limit | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 12 | [#304924](https://github.com/microsoft/vscode/issues/304924) | Claude models error out with "Sorry, no response returned" only in one workspace | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 14 | [#325091](https://github.com/microsoft/vscode/issues/325091) | frontier_llm refusal for Claude Fable 5 results in an error | 0 | correctness | 4/6 Traced | 2 | — | — |
| 26 | [#322138](https://github.com/microsoft/vscode/issues/322138) | GitHub Copilot "Invalid `signature` in `thinking` block" error | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 28 | [#325440](https://github.com/microsoft/vscode/issues/325440) | Fable 5 dies and loops on Autopilot forever. | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 69 | [#328171](https://github.com/microsoft/vscode/issues/328171) | failed to get ready leaves user without a course of action | 0 | correctness | 3/6 Plausible | 0 | — | — |

### Memory tools (7)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 3 | [#323167](https://github.com/microsoft/vscode/issues/323167) | Memory tool corrupts files via recursive self-duplication (str_replace/insert re-injects the entire file body many times) | 0 | data-loss | 5/6 Source-confirmed | 5 | yes | — |
| 7 | [#309245](https://github.com/microsoft/vscode/issues/309245) | `vscode/memory` tool never provisioned for GPT-5.4 — deterministic absence in both main chat and agent contexts | 1 | correctness | 2/6 Unverified | 2 | — | — |
| 13 | [#322625](https://github.com/microsoft/vscode/issues/322625) | Memory str_replace tool silently drops large newString values (coerces to string "undefined") | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 16 | [#308575](https://github.com/microsoft/vscode/issues/308575) | Session memory files not automatically listed in user prompt (sessionMemory) after creation | 1 | correctness | 5/6 Source-confirmed | 1 | yes | — |
| 24 | [#300804](https://github.com/microsoft/vscode/issues/300804) | Copilot user memory never used | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 27 | [#325438](https://github.com/microsoft/vscode/issues/325438) | Copilot global memory not syncing across devices for same user | 0 | correctness | — | 1 | — | — |
| 68 | [#327600](https://github.com/microsoft/vscode/issues/327600) | Memory tool: user memory is never auto-loaded when the memories directory is a junction/symlink (strict FileType check) | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |

### Todo and plans (13)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 4 | [#325446](https://github.com/microsoft/vscode/issues/325446) | Plan Mode export wastes AI credits by invoking an agent to copy existing text into an editor tab | 1 | correctness | 5/6 Source-confirmed | 4 | — | — |
| 10 | [#282301](https://github.com/microsoft/vscode/issues/282301) | Todo list appears to be cleared when resuming after stopping agent | 0 | correctness | — | 2 | — | — |
| 15 | [#307820](https://github.com/microsoft/vscode/issues/307820) | Copilot Chat todo list never updating | 1 | correctness | 3/6 Plausible | 1 | — | — |
| 44 | [#276587](https://github.com/microsoft/vscode/issues/276587) | Restore/Undo last message doesn't update todos | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 45 | [#280824](https://github.com/microsoft/vscode/issues/280824) | Model doesn't check all the todo items even it has finished them | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 51 | [#286805](https://github.com/microsoft/vscode/issues/286805) | `Proceed from Plan` options persist when cloud agent is working | 0 | visual | 4/6 Traced | 0 | — | — |
| 52 | [#297354](https://github.com/microsoft/vscode/issues/297354) | Store plans isn't clickable | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 53 | [#299858](https://github.com/microsoft/vscode/issues/299858) | stale checklist | 0 | none | 3/6 Plausible | 0 | — | — |
| 54 | [#300115](https://github.com/microsoft/vscode/issues/300115) | plan mode broken | 0 | none | 3/6 Plausible | 0 | — | — |
| 56 | [#302927](https://github.com/microsoft/vscode/issues/302927) | To Do Tool items show unchecked on reload until you expand thinking block | 0 | visual | 3/6 Plausible | 0 | — | — |
| 57 | [#304922](https://github.com/microsoft/vscode/issues/304922) | trying to render todo widget nukes chat input | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 60 | [#318467](https://github.com/microsoft/vscode/issues/318467) | Todos: Background todo agent creates completed todos during plan agent runs | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 67 | [#326082](https://github.com/microsoft/vscode/issues/326082) | Agent Host: TODO tool doesn't show any UI | 0 | visual | 3/6 Plausible | 0 | — | — |

### Tool routing (8)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 5 | [#311420](https://github.com/microsoft/vscode/issues/311420) | Copilot custom agent handoff can keep the previous agent active instead of switching to the target agent | 2 | correctness | 5/6 Source-confirmed | 3 | — | — |
| 11 | [#290738](https://github.com/microsoft/vscode/issues/290738) | Github copilot default enables specific tools for agent mode. | 0 | correctness | 5/6 Source-confirmed | 2 | — | — |
| 17 | [#324113](https://github.com/microsoft/vscode/issues/324113) | Virtual tool grouping silently drops tools mid-session; error blames the user ("currently disabled by the user") | 1 | correctness | 5/6 Source-confirmed | 1 | — | — |
| 25 | [#302100](https://github.com/microsoft/vscode/issues/302100) | Something's wrong with a tool. | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 48 | [#284508](https://github.com/microsoft/vscode/issues/284508) | `@vscode refresh preview` has non-functional button | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 58 | [#307817](https://github.com/microsoft/vscode/issues/307817) | Background compaction can replay tool invocations and duplicate side effects | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 59 | [#313520](https://github.com/microsoft/vscode/issues/313520) | Bug: `todo` tool not available to subAgents even when explicitly provided via frontmatter | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 61 | [#321932](https://github.com/microsoft/vscode/issues/321932) | Argument 0 must be a buffer source | 0 | correctness | 3/6 Plausible | 0 | — | — |

### Welcome walkthroughs (11)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 8 | [#278803](https://github.com/microsoft/vscode/issues/278803) | Welcome: Applying inline style violates the following Content Security Policy directive | 0 | correctness | 5/6 Source-confirmed | 2 | yes | — |
| 18 | [#225977](https://github.com/microsoft/vscode/issues/225977) | All content read as expanded in walkthrough for SR users | 0 | correctness | 5/6 Source-confirmed | 1 | — | — |
| 19 | [#273900](https://github.com/microsoft/vscode/issues/273900) | Welcome: copilot images are outdated | 0 | visual | — | 1 | — | — |
| 29 | [#250253](https://github.com/microsoft/vscode/issues/250253) | Accessibility: Walkthrough Page Titles Violate "1.3.1 Info and Relationships" Requirement | 1 | papercut | 5/6 Source-confirmed | 0 | yes | — |
| 32 | [#228910](https://github.com/microsoft/vscode/issues/228910) | Messy underlining and icon clipping in Start section of Welcome page | 0 | visual | 4/6 Traced | 0 | yes | — |
| 33 | [#232292](https://github.com/microsoft/vscode/issues/232292) | Extension packs with only 1 walkthrough should open on that walkthrough registration | 0 | papercut | 4/6 Traced | 0 | yes | — |
| 34 | [#239255](https://github.com/microsoft/vscode/issues/239255) | Visual Studio Code doesn't show translated walkthrough strings until restarting app or reloading window | 0 | correctness | 4/6 Traced | 0 | — | — |
| 35 | [#243755](https://github.com/microsoft/vscode/issues/243755) | Scroll state should not be shared between walkthrough steps | 0 | papercut | 5/6 Source-confirmed | 0 | yes | — |
| 36 | [#247130](https://github.com/microsoft/vscode/issues/247130) | The bold text inside a walkthrough description is not being read out or shown in the accessible view exactly as is | 0 | papercut | 5/6 Source-confirmed | 0 | yes | — |
| 37 | [#247149](https://github.com/microsoft/vscode/issues/247149) | Links inside a VSCode Walkthrough description are not displayed in VS Code accessible view | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 40 | [#273317](https://github.com/microsoft/vscode/issues/273317) | Walkthrough pops up after creating a devcontainer | 0 | papercut | 4/6 Traced | 0 | — | — |

### Workspace creation (5)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 21 | [#284514](https://github.com/microsoft/vscode/issues/284514) | new workspace with `.` char | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 22 | [#287943](https://github.com/microsoft/vscode/issues/287943) | #new did not create a new project using gpt-5 mini | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 30 | [#258544](https://github.com/microsoft/vscode/issues/258544) | #new should identify when not in agent mode | 1 | papercut | 3/6 Plausible | 0 | — | — |
| 46 | [#283173](https://github.com/microsoft/vscode/issues/283173) | @workspace new slash command loads a new workspace on codespaces | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 64 | [#323891](https://github.com/microsoft/vscode/issues/323891) | #new doesn't work with new Copilot AHP in insiders build | 0 | correctness | 3/6 Plausible | 0 | — | — |

### Chat UI rendering (8)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 23 | [#293168](https://github.com/microsoft/vscode/issues/293168) | Context Window widget displays 100% usage with nominator greater than denominator | 0 | visual | 5/6 Source-confirmed | 1 | yes | — |
| 38 | [#266993](https://github.com/microsoft/vscode/issues/266993) | Chat Open File in Editor doesn't directly open file | 0 | correctness | 4/6 Traced | 0 | — | — |
| 39 | [#270654](https://github.com/microsoft/vscode/issues/270654) | Keyboard shortcut strings are sometimes formatted strangely in Copilot responses | 0 | visual | — | 0 | — | — |
| 41 | [#275201](https://github.com/microsoft/vscode/issues/275201) | "Working" is not shown while a web search is happening | 0 | papercut | — | 0 | — | — |
| 42 | [#275203](https://github.com/microsoft/vscode/issues/275203) | Web search is broken up mid-sentence by blockquotes | 0 | visual | 3/6 Plausible | 0 | — | — |
| 43 | [#275699](https://github.com/microsoft/vscode/issues/275699) | Chat widget edit sessions and todo widget not restored when moved to new window or editor | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 47 | [#284504](https://github.com/microsoft/vscode/issues/284504) | Open the file that edits get applied to if active editor is welcome page | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 49 | [#284509](https://github.com/microsoft/vscode/issues/284509) | @vscode participant is slow 🐌 | 0 | perf | 3/6 Plausible | 0 | — | — |

### Anthropic caching (4)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 20 | [#275218](https://github.com/microsoft/vscode/issues/275218) | Anthropic BYOK leaves incomplete sentence before tool call | 0 | visual | 5/6 Source-confirmed | 1 | — | — |
| 55 | [#300312](https://github.com/microsoft/vscode/issues/300312) | claude agent throws execution errors when Anthropic > Context Editing: Mode is enabled | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 62 | [#323642](https://github.com/microsoft/vscode/issues/323642) | Cache breakpoint re-anchoring rewrites (instead of extends) the BYOK Anthropic prompt cache in long agent sessions | 0 | perf | 4/6 Traced | 0 | — | — |
| 63 | [#323668](https://github.com/microsoft/vscode/issues/323668) | Per-session VSCODE_TARGET_SESSION_LOG template variable sits inside the cached system prefix and cold-busts BYOK Anthropic prompt caching | 0 | perf | 5/6 Source-confirmed | 0 | yes | — |

### Compaction accounting (3)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 65 | [#324526](https://github.com/microsoft/vscode/issues/324526) | No AIC cost associated with /compact runs | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 66 | [#324528](https://github.com/microsoft/vscode/issues/324528) | Model used by Auto does not show when /compact is run | 0 | visual | 3/6 Plausible | 0 | — | — |
| 70 | [#328459](https://github.com/microsoft/vscode/issues/328459) | Background compaction / truncation appears broken in AHP | 0 | freeze | 6/6 Confirmed | 0 | — | — |

### Other (2)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 31 | [#275412](https://github.com/microsoft/vscode/issues/275412) | I was expecting diagnostics telling me `https` in `https://google.com` shouldn't be included | 1 | papercut | 5/6 Source-confirmed | 0 | yes | — |
| 50 | [#285464](https://github.com/microsoft/vscode/issues/285464) | Claude Haiku 4.5 caught in an endless loop of errors. | 0 | correctness | 3/6 Plausible | 0 | — | — |

## Feature requests

### Session continuity (7)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | [#287170](https://github.com/microsoft/vscode/issues/287170) | Option for Copilot handoff buttons to force a new chat session to avoid context rot | 19 | active | 100 | — |
| 6 | [#302124](https://github.com/microsoft/vscode/issues/302124) | Sessions: Context and codebase understanding is not transferred between sessions on the same repository | 0 | active | 24 | — |
| 12 | [#325449](https://github.com/microsoft/vscode/issues/325449) | Plan Mode silently discards the comprehensive plan when exporting for a separate implementation session | 1 | active | 11 | — |
| 13 | [#282687](https://github.com/microsoft/vscode/issues/282687) | Maintain /Plan mode todo list after adding a new message to the chat | 2 | dormant | 10 | — |
| 21 | [#315248](https://github.com/microsoft/vscode/issues/315248) | Changing from PLAN mode to Agent Mode (Start Implementation) should compact the conversation | 1 | active | 5 | — |
| 24 | [#323207](https://github.com/microsoft/vscode/issues/323207) | Render a stale session warning when a user resumes session | 0 | active | 3 | — |
| 33 | [#296370](https://github.com/microsoft/vscode/issues/296370) | Session memory should persist when forking or sending to new chat | 0 | backlog-candidate | 0 | — |

### Tool discovery (6)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 2 | [#321462](https://github.com/microsoft/vscode/issues/321462) | [AHP/CLI:COGS] Client Side Tool Search & Tools Grouping Service | 0 | active | 47 | — |
| 8 | [#255860](https://github.com/microsoft/vscode/issues/255860) | VSCode chat participant is not aware of commands from extensions | 2 | backlog-candidate | 21 | — |
| 16 | [#322784](https://github.com/microsoft/vscode/issues/322784) | [AHP/CLI:COGS] Tools Grouping Service (Virtual Tools) | 0 | active | 10 | — |
| 25 | [#260360](https://github.com/microsoft/vscode/issues/260360) | Adopt codesearch for @vscode chat agent | 0 | backlog-candidate | 2 | — |
| 36 | [#299240](https://github.com/microsoft/vscode/issues/299240) | Convert @vscode chat participant to an ask-vscode skill | 0 | active | 0 | — |
| 40 | [#323191](https://github.com/microsoft/vscode/issues/323191) | Optimized tool selection breaks Deepseek cache | 0 | active | 0 | — |

### Prompt control (4)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 3 | [#319331](https://github.com/microsoft/vscode/issues/319331) | Please provide a way to override the system prompt, so we can reduce credit waste | 8 | backlog-candidate | 42 | — |
| 9 | [#320198](https://github.com/microsoft/vscode/issues/320198) | Auto model selection should allow restricting to certain models | 3 | backlog-candidate | 16 | — |
| 10 | [#291992](https://github.com/microsoft/vscode/issues/291992) | Enable users passing in custom system prompt for CAPI/BYOK models | 1 | dormant | 13 | — |
| 39 | [#322782](https://github.com/microsoft/vscode/issues/322782) | [AHP/CLI] Claude Opus 4.7 / 4.8 Alt Prompt | 0 | active | 0 | — |

### Memory management (6)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 4 | [#318131](https://github.com/microsoft/vscode/issues/318131) | memory-tool invoked even though Copilot chat memory is disabled. | 6 | active | 34 | — |
| 7 | [#323174](https://github.com/microsoft/vscode/issues/323174) | Agent auto-persists referenceable/feature-specific knowledge into always-loaded global memory, inflating per-turn context cost | 0 | active | 24 | — |
| 18 | [#307617](https://github.com/microsoft/vscode/issues/307617) | Agent memory files are not reverted when restoring checkpoints or editing previous messages | 1 | active | 6 | — |
| 20 | [#273751](https://github.com/microsoft/vscode/issues/273751) | Add Memory Feature to GitHub Copilot with VS Code Sync Directory Support | 1 | backlog-candidate | 5 | — |
| 26 | [#297363](https://github.com/microsoft/vscode/issues/297363) | Memory picker lacks connection to chat widget | 0 | backlog-candidate | 1 | — |
| 34 | [#296846](https://github.com/microsoft/vscode/issues/296846) | Adding support for deleting individual or multiple memory files at a time | 0 | active | 0 | — |

### Walkthrough experience (4)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 5 | [#212819](https://github.com/microsoft/vscode/issues/212819) | Provide a command to reset the completed steps of a walkthrough | 24 | backlog-candidate | 32 | — |
| 17 | [#287614](https://github.com/microsoft/vscode/issues/287614) | Update Copilot getting started | 0 | dormant | 9 | — |
| 19 | [#241767](https://github.com/microsoft/vscode/issues/241767) | Localise media paths in walkthroughs | 1 | backlog-candidate | 5 | — |
| 27 | [#228007](https://github.com/microsoft/vscode/issues/228007) | Expose Walkthrough Media in Accessible view. | 0 | backlog-candidate | 0 | — |

### Project scaffolding (2)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 11 | [#134651](https://github.com/microsoft/vscode/issues/134651) | Add "new folder" option -- to make starting a new project easier. | 5 | backlog-candidate | 12 | — |
| 30 | [#284506](https://github.com/microsoft/vscode/issues/284506) | Agent could suggest to preview the site I am creating using simple browser | 0 | backlog-candidate | 0 | — |

### Context costs (4)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 14 | [#321551](https://github.com/microsoft/vscode/issues/321551) | Bug: Prompt cache expires during active agent sessions, causing 10x cost spikes on gaps > 5 min | 1 | backlog-candidate | 10 | — |
| 23 | [#318361](https://github.com/microsoft/vscode/issues/318361) | Support percentage-based and/or per-model context summarization thresholds | 1 | backlog-candidate | 3 | — |
| 37 | [#321299](https://github.com/microsoft/vscode/issues/321299) | # [Tokenomics] Agent system prompt and tool schemas are written for humans | 0 | active | 0 | — |
| 38 | [#322775](https://github.com/microsoft/vscode/issues/322775) | [AHP/CLI:COGS] Anthropic Extended Cache (1hr TTL) | 0 | active | 0 | — |

### Agent planning (3)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 15 | [#262767](https://github.com/microsoft/vscode/issues/262767) | UX to delegate specific TODOs to coding agent | 0 | backlog-candidate | 10 | — |
| 22 | [#318245](https://github.com/microsoft/vscode/issues/318245) | Add “Save to Workspace” action for Copilot-generated plan files | 1 | active | 5 | — |
| 28 | [#283171](https://github.com/microsoft/vscode/issues/283171) | Agent mode with existing files | 0 | backlog-candidate | 0 | — |

### Chat interface (3)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 31 | [#284551](https://github.com/microsoft/vscode/issues/284551) | Support unified Chat Input Notification Widget | 0 | backlog-candidate | 0 | — |
| 32 | [#292677](https://github.com/microsoft/vscode/issues/292677) | Extend upgrade status widget to paid skus | 0 | dormant | 0 | — |
| 35 | [#298981](https://github.com/microsoft/vscode/issues/298981) | New Chat Shows Agent Prompts of Custom Agent | 0 | active | 0 | — |

### Other (1)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 29 | [#283720](https://github.com/microsoft/vscode/issues/283720) | Show icon instead of talking about the icon | 0 | backlog-candidate | 0 | — |
