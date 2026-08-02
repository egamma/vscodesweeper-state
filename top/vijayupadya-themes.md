# Top issues by theme — vijayupadya

Experimental themed view of [the flat ranking](vijayupadya.md); themes assigned by the review engine. Rank/score are the lane-wide values. Generated 2026-08-02 14:01 UTC.

## Bugs

### Model providers and picker (15)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | [#313458](https://github.com/microsoft/vscode/issues/313458) | Copilot Chat local models do not populate Context Window usage even when backend usage and model limits are available | 15 | correctness | 5/6 Source-confirmed | 100 | — | — |
| 3 | [#318211](https://github.com/microsoft/vscode/issues/318211) | [Insiders] BYOK not showing reasoning tokens in chat | 10 | correctness | 2/6 Unverified | 39 | — | — |
| 6 | [#326554](https://github.com/microsoft/vscode/issues/326554) | Auto Mode Router overrides an explicitly selected BYOK model with a Copilot model | 2 | correctness | 3/6 Plausible | 18 | — | — |
| 10 | [#296999](https://github.com/microsoft/vscode/issues/296999) | VS Code displaying unexpected context window size for Gemini models | 0 | correctness | 3/6 Plausible | 16 | — | — |
| 13 | [#312908](https://github.com/microsoft/vscode/issues/312908) | Chat model picker hides BYOK models when their `metadata.id` collides with another vendor's model | 0 | correctness | 5/6 Source-confirmed | 13 | — | — |
| 21 | [#317104](https://github.com/microsoft/vscode/issues/317104) | Testing with responses API leads to ZDP error | 0 | correctness | 4/6 Traced | 8 | — | — |
| 22 | [#296713](https://github.com/microsoft/vscode/issues/296713) | [BYOK Agent Mode] Gemini 3.1 Pro returns 400 "Function call is missing a thought_signature" — OpenAI-compatible client strips required field | 2 | correctness | 5/6 Source-confirmed | 7 | yes | — |
| 28 | [#326385](https://github.com/microsoft/vscode/issues/326385) | Google AI Studio API key models not working / missing "Google AI Studio" suffix after latest update | 1 | correctness | 3/6 Plausible | 5 | — | — |
| 60 | [#317503](https://github.com/microsoft/vscode/issues/317503) | BYOK to GHCP throws an error (GPT 5.3 Codex model) | 0 | correctness | 6/6 Confirmed | 1 | — | — |
| 111 | [#316970](https://github.com/microsoft/vscode/issues/316970) | The custom model is under empty category name | 0 | visual | 4/6 Traced | 0 | — | — |
| 112 | [#316974](https://github.com/microsoft/vscode/issues/316974) | API Key is not recognized | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 115 | [#318101](https://github.com/microsoft/vscode/issues/318101) | Improve Azure OpenAI URL Handling in the BYOK Provider | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 118 | [#324755](https://github.com/microsoft/vscode/issues/324755) | Anthropic Provider not showing in Linux | 0 | none | 3/6 Plausible | 0 | — | — |
| 121 | [#326602](https://github.com/microsoft/vscode/issues/326602) | Clicking migrate on Ollama deprectaed setting leads to an error | 0 | papercut | 4/6 Traced | 0 | — | — |
| 123 | [#327644](https://github.com/microsoft/vscode/issues/327644) | [Chat Model Picker] Duplicate 'copilot' group in the model list | 0 | visual | 5/6 Source-confirmed | 0 | — | — |

### Gemini model reliability (14)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2 | [#282138](https://github.com/microsoft/vscode/issues/282138) | Gemini Pro 3: Server error. Stream terminated when used after other models in the same conversation | 7 | correctness | — | 63 | — | — |
| 4 | [#286650](https://github.com/microsoft/vscode/issues/286650) | gemini 3 pro constantly crashing | 3 | correctness | 3/6 Plausible | 29 | — | — |
| 8 | [#279353](https://github.com/microsoft/vscode/issues/279353) | Gemini 3 model mostly not working in GHE - invalid_request body | 1 | correctness | — | 16 | — | — |
| 16 | [#278444](https://github.com/microsoft/vscode/issues/278444) | O novo modelo Gemini 3 Pro está MUITO LENTO | 0 | perf | 3/6 Plausible | 10 | — | — |
| 29 | [#288898](https://github.com/microsoft/vscode/issues/288898) | error api gemini linking | 0 | none | 3/6 Plausible | 5 | — | — |
| 30 | [#315099](https://github.com/microsoft/vscode/issues/315099) | Copilot + Gemini 3.1 Pro keeps stopping | 0 | correctness | 3/6 Plausible | 5 | — | — |
| 32 | [#278212](https://github.com/microsoft/vscode/issues/278212) | Gemini 3 Pro not working | 1 | correctness | 3/6 Plausible | 4 | — | — |
| 35 | [#301444](https://github.com/microsoft/vscode/issues/301444) | Gemini Error | 0 | none | 3/6 Plausible | 4 | — | — |
| 42 | [#286929](https://github.com/microsoft/vscode/issues/286929) | Gemini 3 Flash loops | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 49 | [#296473](https://github.com/microsoft/vscode/issues/296473) | Gemini 3.1 Pro got stuck in cycle in the Plan mode | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 52 | [#300658](https://github.com/microsoft/vscode/issues/300658) | Gemini 3.1 Pro (Preview) ended long response with infinite loop of "Bye.\nDone." | 0 | papercut | 3/6 Plausible | 1 | — | — |
| 64 | [#259909](https://github.com/microsoft/vscode/issues/259909) | Gemini 2.5 Pro repeats the same thing infinitely | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 74 | [#284295](https://github.com/microsoft/vscode/issues/284295) | Gemini 3 Pro (preview) infinite loop | 0 | none | 3/6 Plausible | 0 | — | — |
| 91 | [#300497](https://github.com/microsoft/vscode/issues/300497) | Unexpected Gemini Pro 3.1 response: chain-of-thought leakage and repeated dot output | 0 | correctness | 3/6 Plausible | 0 | — | — |

### Chat rendering (10)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 5 | [#286647](https://github.com/microsoft/vscode/issues/286647) | Copilot Chat always rendering malformed, duplicated code blocks | 0 | correctness | 6/6 Confirmed | 29 | — | — |
| 19 | [#284650](https://github.com/microsoft/vscode/issues/284650) | SQL code blocks "leak" in "Ask" mode for Gemini Pro 3 (Preview) | 0 | visual | 3/6 Plausible | 8 | — | — |
| 24 | [#286762](https://github.com/microsoft/vscode/issues/286762) | GitHub Copilot link shimmering during output generation. | 0 | visual | 3/6 Plausible | 7 | — | — |
| 25 | [#280399](https://github.com/microsoft/vscode/issues/280399) | Folder name flickering in agent mode output | 0 | visual | 3/6 Plausible | 6 | — | — |
| 33 | [#279231](https://github.com/microsoft/vscode/issues/279231) | Bad formatting | 0 | visual | 3/6 Plausible | 4 | — | — |
| 48 | [#295972](https://github.com/microsoft/vscode/issues/295972) | Answer is not showing | 0 | none | 3/6 Plausible | 1 | — | — |
| 66 | [#272828](https://github.com/microsoft/vscode/issues/272828) | Chat response: consistently render code as Code | 0 | visual | 3/6 Plausible | 0 | — | — |
| 68 | [#273080](https://github.com/microsoft/vscode/issues/273080) | Chat response: inconsistent rendering of file labels | 0 | visual | 3/6 Plausible | 0 | — | — |
| 69 | [#275149](https://github.com/microsoft/vscode/issues/275149) | Ugly rendering of quota exceeded option | 0 | visual | 2/6 Unverified | 0 | — | — |
| 99 | [#309941](https://github.com/microsoft/vscode/issues/309941) | Bad chat loading rendering | 0 | visual | 4/6 Traced | 0 | yes | — |

### Chat linkification (39)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 7 | [#272350](https://github.com/microsoft/vscode/issues/272350) | GPT-5-Codex (Preview) produces invalid links to project files in its outputs | 2 | visual | 6/6 Confirmed | 17 | — | — |
| 11 | [#297792](https://github.com/microsoft/vscode/issues/297792) | GitHub Copilot adds incorrect links in the in-chat conversation. | 0 | correctness | 4/6 Traced | 14 | — | — |
| 14 | [#280686](https://github.com/microsoft/vscode/issues/280686) | Unable to open file resource from chat output | 0 | correctness | 3/6 Plausible | 11 | — | — |
| 15 | [#293492](https://github.com/microsoft/vscode/issues/293492) | Copilot chat links do not load successfully | 0 | correctness | 3/6 Plausible | 11 | — | — |
| 26 | [#280523](https://github.com/microsoft/vscode/issues/280523) | Ranges reported as by the model do not match the file | 0 | papercut | 3/6 Plausible | 6 | — | — |
| 27 | [#280547](https://github.com/microsoft/vscode/issues/280547) | File path and line number linkification - markdown links not rendered in the plan | 0 | visual | 3/6 Plausible | 6 | — | — |
| 36 | [#283156](https://github.com/microsoft/vscode/issues/283156) | Discussing file protocol triggers odd non-functional explorer buttons to show up | 1 | visual | 5/6 Source-confirmed | 3 | yes | — |
| 38 | [#275716](https://github.com/microsoft/vscode/issues/275716) | InlineCodeSymbolLinkifier hangs | 0 | perf | 3/6 Plausible | 3 | — | — |
| 39 | [#291291](https://github.com/microsoft/vscode/issues/291291) | Clear links aren't getting linkified in agent response | 0 | papercut | 5/6 Source-confirmed | 3 | yes | — |
| 41 | [#272848](https://github.com/microsoft/vscode/issues/272848) | Chat response: render files and symbols consistently | 1 | papercut | 3/6 Plausible | 2 | — | — |
| 44 | [#268745](https://github.com/microsoft/vscode/issues/268745) | Wrapped chat symbol links don't look great | 0 | visual | 4/6 Traced | 1 | yes | — |
| 45 | [#280552](https://github.com/microsoft/vscode/issues/280552) | File path and line number linkification - clicking on a selection link should open the editor with a selection | 0 | papercut | 5/6 Source-confirmed | 1 | — | — |
| 46 | [#287022](https://github.com/microsoft/vscode/issues/287022) | Broken link in chat | 0 | visual | 3/6 Plausible | 1 | — | — |
| 47 | [#291301](https://github.com/microsoft/vscode/issues/291301) | Chat links to files can't be opened | 0 | correctness | 2/6 Unverified | 1 | — | — |
| 50 | [#296810](https://github.com/microsoft/vscode/issues/296810) | Agents ignore fileLinkification instructions — produce absolute Windows paths that break on click | 0 | correctness | 4/6 Traced | 1 | — | — |
| 53 | [#302518](https://github.com/microsoft/vscode/issues/302518) | terminal command was linkified | 0 | papercut | 3/6 Plausible | 1 | — | — |
| 63 | [#229572](https://github.com/microsoft/vscode/issues/229572) | disambiguate links in chat with the same name | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 65 | [#260307](https://github.com/microsoft/vscode/issues/260307) | Only some tests are getting linkified in chat response | 0 | visual | 3/6 Plausible | 0 | — | — |
| 67 | [#273002](https://github.com/microsoft/vscode/issues/273002) | Wrong file links in responses | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 70 | [#275950](https://github.com/microsoft/vscode/issues/275950) | Files are not linkified in chat response | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 71 | [#277125](https://github.com/microsoft/vscode/issues/277125) | Unrelated symbol linked to in list | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 72 | [#277596](https://github.com/microsoft/vscode/issues/277596) | Chat: Make linkification for URLs found in subagents | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 73 | [#283612](https://github.com/microsoft/vscode/issues/283612) | Do not link-ify `\r` and `\r\n` in chat | 0 | visual | 3/6 Plausible | 0 | — | — |
| 75 | [#285999](https://github.com/microsoft/vscode/issues/285999) | When paragraphs start with a link they're added on their own line | 0 | visual | 3/6 Plausible | 0 | — | — |
| 76 | [#286478](https://github.com/microsoft/vscode/issues/286478) | Copilot sending backtick followed by a number is always seen as vscodecontentref | 0 | visual | 3/6 Plausible | 0 | — | — |
| 77 | [#286980](https://github.com/microsoft/vscode/issues/286980) | Thinking block summary should linkify appropriately | 0 | visual | 5/6 Source-confirmed | 0 | yes | — |
| 78 | [#287016](https://github.com/microsoft/vscode/issues/287016) | Broken link in chat | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 79 | [#289921](https://github.com/microsoft/vscode/issues/289921) | Bad links in chat | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 80 | [#292163](https://github.com/microsoft/vscode/issues/292163) | Bad link in chat | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 81 | [#294074](https://github.com/microsoft/vscode/issues/294074) | Broken link in chat | 0 | visual | 3/6 Plausible | 0 | — | — |
| 83 | [#294734](https://github.com/microsoft/vscode/issues/294734) | Chat Linkification: when I click on `proxy.ts:22-27` I expect line 27 to be highlighted too | 0 | papercut | 5/6 Source-confirmed | 0 | yes | — |
| 84 | [#294946](https://github.com/microsoft/vscode/issues/294946) | Broken chat link | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 85 | [#295451](https://github.com/microsoft/vscode/issues/295451) | File hyper link dosent navigate to the file | 0 | none | 3/6 Plausible | 0 | — | — |
| 87 | [#298830](https://github.com/microsoft/vscode/issues/298830) | Linkification: code references with line numbers are not clickable. | 0 | papercut | 2/6 Unverified | 0 | — | — |
| 89 | [#299903](https://github.com/microsoft/vscode/issues/299903) | Linkification broken in gpt-5.4 | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 90 | [#299904](https://github.com/microsoft/vscode/issues/299904) | Random codespans get linkified | 0 | papercut | 5/6 Source-confirmed | 0 | — | — |
| 92 | [#301648](https://github.com/microsoft/vscode/issues/301648) | Empty linkified symbols for 'file://' | 0 | visual | 4/6 Traced | 0 | yes | — |
| 97 | [#309195](https://github.com/microsoft/vscode/issues/309195) | Absolute paths to file links are wrong in chat panel | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 108 | [#314740](https://github.com/microsoft/vscode/issues/314740) | chat links navigate to lib.dom file | 0 | papercut | 3/6 Plausible | 0 | — | — |

### Agent tools and execution (13)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 9 | [#291761](https://github.com/microsoft/vscode/issues/291761) | Copilot Chat gets stuck in an infinite loop in Plan mode | 1 | correctness | 3/6 Plausible | 16 | — | — |
| 20 | [#314010](https://github.com/microsoft/vscode/issues/314010) | Bug: Tools that work in custom agents (local) and in Copilot CLI (default agent), break when both are combined | 0 | correctness | 3/6 Plausible | 8 | — | — |
| 23 | [#284615](https://github.com/microsoft/vscode/issues/284615) | SubAgents that are created with Gemini 3 Pro model are not getting any tools | 0 | correctness | 3/6 Plausible | 7 | — | — |
| 34 | [#292560](https://github.com/microsoft/vscode/issues/292560) | Agent do some task always discontinue | 0 | none | 3/6 Plausible | 4 | — | — |
| 37 | [#321277](https://github.com/microsoft/vscode/issues/321277) | Coding agent wasting credits when waiting on command completion | 1 | papercut | 3/6 Plausible | 3 | — | — |
| 51 | [#298891](https://github.com/microsoft/vscode/issues/298891) | Sorry, your request failed. Please try again. | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 82 | [#294728](https://github.com/microsoft/vscode/issues/294728) | Copilot stuck in a loop and constantly sending messages | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 86 | [#297187](https://github.com/microsoft/vscode/issues/297187) | [Severe Bug] Tool execution completely broken: Workspace access blocked & models output raw JSON instead of running tools | 0 | none | 3/6 Plausible | 0 | — | — |
| 88 | [#299858](https://github.com/microsoft/vscode/issues/299858) | stale checklist | 0 | none | 3/6 Plausible | 0 | — | — |
| 95 | [#306291](https://github.com/microsoft/vscode/issues/306291) | Prompted to approve reading external directory when doing troubleshooting | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 107 | [#313520](https://github.com/microsoft/vscode/issues/313520) | Bug: `todo` tool not available to subAgents even when explicitly provided via frontmatter | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 110 | [#315950](https://github.com/microsoft/vscode/issues/315950) | Gemini 3.1 Pro (Preview) bypassed VS Code tools and used the terminal | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 119 | [#325210](https://github.com/microsoft/vscode/issues/325210) | Todos in Copilot Chat | 0 | none | 3/6 Plausible | 0 | — | — |

### Chronicle analytics (10)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 12 | [#317358](https://github.com/microsoft/vscode/issues/317358) | Chronicle SQL: Error rate trending up as rollout scales (17% → 27%) | 0 | correctness | — | 14 | — | — |
| 17 | [#312292](https://github.com/microsoft/vscode/issues/312292) | Chronicle: local schema description drifted from actual SQLite data | 0 | correctness | 2/6 Unverified | 9 | — | — |
| 40 | [#311430](https://github.com/microsoft/vscode/issues/311430) | Chronicle:tips missing edit signals? | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 57 | [#312275](https://github.com/microsoft/vscode/issues/312275) | Chronicle analysis counts subagent sessions as single-turn usage | 0 | correctness | — | 1 | — | — |
| 58 | [#313640](https://github.com/microsoft/vscode/issues/313640) | Chronicle: schema description divergences — truncation marker and tool_name values | 0 | correctness | — | 1 | — | — |
| 100 | [#311428](https://github.com/microsoft/vscode/issues/311428) | Chronicle session count does not seem correct | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 101 | [#311484](https://github.com/microsoft/vscode/issues/311484) | Chronicle incorrectly logging things as 'Done' | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 103 | [#312272](https://github.com/microsoft/vscode/issues/312272) | Chronicle: Follow-up queries without `/chronicle` no longer have sql tool access | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 104 | [#312278](https://github.com/microsoft/vscode/issues/312278) | execution_subagent internal "Execution query:" framing leaks into session turn logs | 0 | papercut | 5/6 Source-confirmed | 0 | yes | — |
| 105 | [#312891](https://github.com/microsoft/vscode/issues/312891) | `/chronicle` may not include empty workspace sessions | 0 | correctness | 4/6 Traced | 0 | — | — |

### Agent debug logs (13)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 43 | [#316190](https://github.com/microsoft/vscode/issues/316190) | Agent Debug Logs stats resets | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 54 | [#304265](https://github.com/microsoft/vscode/issues/304265) | Agent Debug Logs "Export is not supported by the current provider" | 0 | papercut | 2/6 Unverified | 1 | — | — |
| 55 | [#304309](https://github.com/microsoft/vscode/issues/304309) | Only seeing 'Load Hooks' event types for claude | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 56 | [#307803](https://github.com/microsoft/vscode/issues/307803) | Agent Debug Logs does not show Import/Export controls on latest VS Code and Copilot Chat | 0 | none | 3/6 Plausible | 1 | — | — |
| 59 | [#314224](https://github.com/microsoft/vscode/issues/314224) | ChatDebugFileLogger fails on Windows: EINVAL mkdir for path with trailing ':' (copilotcli:) | 0 | correctness | 5/6 Source-confirmed | 1 | yes | — |
| 61 | [#325559](https://github.com/microsoft/vscode/issues/325559) | Log Panel: Instructions and hook discovery stuck at the bottom | 0 | visual | 3/6 Plausible | 1 | — | — |
| 93 | [#302211](https://github.com/microsoft/vscode/issues/302211) | Chat agent debug log view: Response contains tools call as well | 0 | visual | — | 0 | — | — |
| 94 | [#304311](https://github.com/microsoft/vscode/issues/304311) | Not seeing hooks in agent debug logs | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 106 | [#313122](https://github.com/microsoft/vscode/issues/313122) | Agent debug log does not show logs for auto mode request | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 109 | [#315798](https://github.com/microsoft/vscode/issues/315798) | chat debug view UI changes drastically when moved to another group | 0 | visual | 5/6 Source-confirmed | 0 | — | — |
| 117 | [#321439](https://github.com/microsoft/vscode/issues/321439) | No Agent Debug logs for Agent host sessions | 0 | correctness | — | 0 | — | — |
| 120 | [#325556](https://github.com/microsoft/vscode/issues/325556) | Switching back to Log Panel does not restore it | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 124 | [#327865](https://github.com/microsoft/vscode/issues/327865) | Chat agent debug logging settings (`github.copilot.chat.agentDebugLog.*`) are undiscoverable in Settings search | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |

### Other (10)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 18 | [#318346](https://github.com/microsoft/vscode/issues/318346) | Copilot autocomplete suppresses/breaks TypeScript IntelliSense and auto-import suggestions until Copilot suggestions are snoozed | 1 | correctness | 6/6 Confirmed | 8 | — | — |
| 31 | [#321248](https://github.com/microsoft/vscode/issues/321248) | Breadcrumb shows unwanted bottom border in light themes | 0 | visual | 5/6 Source-confirmed | 5 | yes | — |
| 62 | [#325595](https://github.com/microsoft/vscode/issues/325595) | Markdown language server unresponsive with large file | 0 | perf | 3/6 Plausible | 1 | — | — |
| 96 | [#308213](https://github.com/microsoft/vscode/issues/308213) | Export Chat truncates file to 0 bytes when disk is full instead of failing gracefully | 0 | data-loss | 5/6 Source-confirmed | 0 | yes | — |
| 98 | [#309554](https://github.com/microsoft/vscode/issues/309554) | Ordering is wrong from active session to other tab | 0 | visual | 3/6 Plausible | 0 | — | — |
| 102 | [#311630](https://github.com/microsoft/vscode/issues/311630) | Sessions should be sorted by date | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 113 | [#317178](https://github.com/microsoft/vscode/issues/317178) | Session Sync: Use the current Copilot account for API requests | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 114 | [#317671](https://github.com/microsoft/vscode/issues/317671) | Terminal session in separate window always opens as blank vs code window when relaunching vs code | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 116 | [#319634](https://github.com/microsoft/vscode/issues/319634) | Update to 1.122.1 Breaks Terminal / pty-host connection | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 122 | [#327461](https://github.com/microsoft/vscode/issues/327461) | "Try Again" for Github Copilot | 0 | correctness | 3/6 Plausible | 0 | — | — |

## Feature requests

### Model provider support (8)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | [#325738](https://github.com/microsoft/vscode/issues/325738) | Agents Window over SSH: BYOK unsupported + agent-host version mismatch blocks usage | 7 | active | 100 | — |
| 2 | [#283948](https://github.com/microsoft/vscode/issues/283948) | Support for Gemini Multimodal Capabilities in VS Code Copilot | 17 | backlog-candidate | 82 | — |
| 6 | [#315741](https://github.com/microsoft/vscode/issues/315741) | Add ability to specify reasoning effort for Gemini BYOK models | 0 | backlog-candidate | 15 | — |
| 7 | [#303360](https://github.com/microsoft/vscode/issues/303360) | Thinking configuration support for Gemini | 1 | backlog-candidate | 14 | — |
| 11 | [#320260](https://github.com/microsoft/vscode/issues/320260) | BYOK "selectedCompletionModel" Bug | 1 | active | 10 | — |
| 17 | [#295943](https://github.com/microsoft/vscode/issues/295943) | Feature Request: Add file deletion tool support for non-OpenAI models in agent mode | 0 | active | 3 | — |
| 28 | [#316972](https://github.com/microsoft/vscode/issues/316972) | Shortcut to open the model json file from the language models view | 0 | active | 0 | — |
| 31 | [#325455](https://github.com/microsoft/vscode/issues/325455) | vscode.lm — Add model visibility (hide/show) APIs | 0 | active | 0 | — |

### Telemetry and usage (5)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 3 | [#317187](https://github.com/microsoft/vscode/issues/317187) | Token usage always shows 0 for models added via LanguageModelChatProvider extension API | 7 | active | 53 | — |
| 15 | [#299637](https://github.com/microsoft/vscode/issues/299637) | Add skills invocation in OTel instrumentation | 0 | active | 5 | — |
| 18 | [#287573](https://github.com/microsoft/vscode/issues/287573) | Expand coverage of conversation.repetition.detected to cancelled requests | 0 | backlog-candidate | 2 | — |
| 23 | [#311186](https://github.com/microsoft/vscode/issues/311186) | Include `USAGE_CACHE_READ_INPUT_TOKENS` in log file output | 0 | active | 0 | — |
| 24 | [#312276](https://github.com/microsoft/vscode/issues/312276) | Chronicle: session_refs table is always empty — ref tracking only fires for MCP tools and Copilot terminal spans | 0 | backlog-candidate | 0 | — |

### Code link navigation (5)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 4 | [#283273](https://github.com/microsoft/vscode/issues/283273) | VS Code does not open file paths with line numbers in plain text (.log) files | 0 | dormant | 20 | — |
| 20 | [#276768](https://github.com/microsoft/vscode/issues/276768) | Model based symbol and line linkification | 0 | backlog-candidate | 0 | — |
| 21 | [#292598](https://github.com/microsoft/vscode/issues/292598) | Code snippets in chat should have go to location | 0 | active | 0 | — |
| 22 | [#295917](https://github.com/microsoft/vscode/issues/295917) | chat references never lead to exact code locations that chat intended to reference, but lead to definitions instead | 0 | active | 0 | — |
| 25 | [#313533](https://github.com/microsoft/vscode/issues/313533) | Support explicit `[\`symbolName\`](path/to/file.py)` symbol links and deprecate optimistic backtick matching | 0 | backlog-candidate | 0 | — |

### Chat session management (3)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 5 | [#326268](https://github.com/microsoft/vscode/issues/326268) | Support import, export, and backup of Chat sessions across workspaces in VSCode Copilot | 1 | active | 16 | — |
| 8 | [#308964](https://github.com/microsoft/vscode/issues/308964) | Copilot Chat should support cross-device cloud conversation memory for repository workflows | 1 | active | 14 | — |
| 30 | [#323539](https://github.com/microsoft/vscode/issues/323539) | Discoverability of #session | 0 | backlog-candidate | 0 | — |

### Agent debugging tools (8)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 9 | [#299323](https://github.com/microsoft/vscode/issues/299323) | Render images in Agent Debug Panel | 0 | active | 14 | — |
| 10 | [#294590](https://github.com/microsoft/vscode/issues/294590) | Add Flowchart Visualization for GitHub Copilot Agent Session Flows | 1 | active | 10 | — |
| 13 | [#302218](https://github.com/microsoft/vscode/issues/302218) | Chat agent debug log view: Exported logs are very verbose and not for human consumption | 1 | backlog-candidate | 9 | — |
| 14 | [#301862](https://github.com/microsoft/vscode/issues/301862) | `Chat agent debug logs viewer` not helpful when finding out why a request did not work | 0 | active | 9 | — |
| 16 | [#304809](https://github.com/microsoft/vscode/issues/304809) | Agent Debug: Troubleshooting scenarios | 0 | active | 5 | — |
| 19 | [#306675](https://github.com/microsoft/vscode/issues/306675) | Session debug should contain the raw request sent to the LLM | 0 | active | 2 | — |
| 32 | [#325562](https://github.com/microsoft/vscode/issues/325562) | Log Panel: Allow clicking `error` in AHP log to filter to errors | 0 | backlog-candidate | 0 | — |
| 33 | [#325572](https://github.com/microsoft/vscode/issues/325572) | Log Panel: Allow filtering AHP Log for content | 0 | backlog-candidate | 0 | — |

### Chronicle workflows (2)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 26 | [#314086](https://github.com/microsoft/vscode/issues/314086) | /chronicle:standup empty on Monday | 0 | backlog-candidate | 0 | — |
| 29 | [#320640](https://github.com/microsoft/vscode/issues/320640) | Add /chronicle command set to Agent Host | 0 | active | 0 | — |

### Other (2)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 12 | [#325334](https://github.com/microsoft/vscode/issues/325334) | Mermaid built-in extension point to register further icons . | 1 | active | 10 | — |
| 27 | [#314569](https://github.com/microsoft/vscode/issues/314569) | Adopt staged rollouts for safer feature releases | 0 | active | 0 | — |
