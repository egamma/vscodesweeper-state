# Top issues by theme — vritant24

Experimental themed view of [the flat ranking](vritant24.md); themes assigned by the review engine. Rank/score are the lane-wide values. Generated 2026-07-27 15:52 UTC.

## Bugs

### Context and tokens (10)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | [#313458](https://github.com/microsoft/vscode/issues/313458) | Copilot Chat local models do not populate Context Window usage even when backend usage and model limits are available | 15 | correctness | 5/6 Source-confirmed | 100 | — | `npm run implement -- --issue 313458` |
| 2 | [#313715](https://github.com/microsoft/vscode/issues/313715) | Copilot Chat does not show correct context window size on local Ollama models. | 7 | correctness | 5/6 Source-confirmed | 43 | — | — |
| 4 | [#318211](https://github.com/microsoft/vscode/issues/318211) | [Insiders] BYOK not showing reasoning tokens in chat | 10 | correctness | 2/6 Unverified | 39 | — | — |
| 7 | [#299907](https://github.com/microsoft/vscode/issues/299907) | Limited context size (33k) for Ollama Models | 2 | correctness | 5/6 Source-confirmed | 29 | yes | `npm run implement -- --issue 299907` |
| 10 | [#319037](https://github.com/microsoft/vscode/issues/319037) | Custom Endpoint Models (Messages API) Never Send `thinking` Parameter | 4 | correctness | 5/6 Source-confirmed | 20 | yes | `npm run implement -- --issue 319037` |
| 19 | [#322216](https://github.com/microsoft/vscode/issues/322216) | Copilot Chat BYOK `vendor: openai` appears to ignore `maxInputTokens` and `maxOutputTokens` | 0 | correctness | 5/6 Source-confirmed | 8 | — | `npm run implement -- --issue 322216` |
| 25 | [#325197](https://github.com/microsoft/vscode/issues/325197) | "Error: No lowest priority node found (path: iie) at lxt" when having too little "maxInputTokens" | 1 | correctness | 6/6 Confirmed | 4 | — | — |
| 48 | [#311705](https://github.com/microsoft/vscode/issues/311705) | Copilot Chat with Ollama/BYOK uses nominal context_length for prompt budgeting and drops token usage in the context widget | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 311705` |
| 54 | [#316402](https://github.com/microsoft/vscode/issues/316402) | The max context of OpenRouter Model is wrong, it should be 1M. | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 316402` |
| 62 | [#321761](https://github.com/microsoft/vscode/issues/321761) | "Reserved for response" ignores `maxOutputTokens` for extension-contributed models (hard-coded to 8192) | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 321761` |

### Provider availability (10)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 3 | [#317255](https://github.com/microsoft/vscode/issues/317255) | Copilot Chat Sanity Test unable to resolve Copilot utility chat model | 0 | correctness | 3/6 Plausible | 41 | — | `npm run implement -- --issue 317255` |
| 15 | [#326389](https://github.com/microsoft/vscode/issues/326389) | 1.129.0 Regression: BYOK (ollama extension provider) fails without login | 0 | correctness | 5/6 Source-confirmed | 11 | — | `npm run implement -- --issue 326389` |
| 18 | [#327078](https://github.com/microsoft/vscode/issues/327078) | BYO LLM blocked when you cannot use Copilot | 0 | correctness | 5/6 Source-confirmed | 9 | — | — |
| 30 | [#320617](https://github.com/microsoft/vscode/issues/320617) | [Regression] [Error] [GitHub.copilot-chat] unhandlederror-fetch failed — byokContribution.fetchKnownModelList | 0 | correctness | 2/6 Unverified | 3 | — | — |
| 36 | [#317414](https://github.com/microsoft/vscode/issues/317414) | [VS Code 1.120+] onDidChangeLanguageModelChatInformation EventEmitter presence causes all LM providers to collapse into Azure | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 43 | [#320537](https://github.com/microsoft/vscode/issues/320537) | BYOK dialog shows up, despite being signed in | 0 | visual | 3/6 Plausible | 1 | — | `npm run implement -- --issue 320537` |
| 67 | [#324245](https://github.com/microsoft/vscode/issues/324245) | BYOK: Can't use local model when VS Code Window is started without internet | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 324245` |
| 69 | [#324755](https://github.com/microsoft/vscode/issues/324755) | Anthropic Provider not showing in Linux | 0 | none | 3/6 Plausible | 0 | — | — |
| 71 | [#325186](https://github.com/microsoft/vscode/issues/325186) | Sending a chat when not signed in has an unhelpful error message | 0 | papercut | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 325186` |
| 73 | [#325216](https://github.com/microsoft/vscode/issues/325216) | "No provider registered" log spam | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 325216` |

### Endpoint protocol compatibility (23)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 5 | [#322728](https://github.com/microsoft/vscode/issues/322728) | Custom BYOK endpoint: "Sorry, no response was returned" when empty tool_calls: [] on content deltas | 6 | correctness | 5/6 Source-confirmed | 38 | yes | `npm run implement -- --issue 322728` |
| 6 | [#324335](https://github.com/microsoft/vscode/issues/324335) | GitHub Copilot "Response Contained No Choices" Using BYOK - Ollama, OpenRouter.ai | 1 | correctness | 4/6 Traced | 33 | — | `npm run implement -- --issue 324335` |
| 8 | [#287533](https://github.com/microsoft/vscode/issues/287533) | xAI API not working for BYOK | 2 | correctness | 3/6 Plausible | 28 | — | `npm run implement -- --issue 287533` |
| 11 | [#319122](https://github.com/microsoft/vscode/issues/319122) | Error with model azure foundry gtp. nano etc, this models send temperature to 01. | 3 | correctness | 5/6 Source-confirmed | 19 | — | — |
| 12 | [#320727](https://github.com/microsoft/vscode/issues/320727) | Incorrect Authorization header for apiKey in Custom Endpoint (BYOK) scenarios | 2 | correctness | 5/6 Source-confirmed | 18 | — | `npm run implement -- --issue 320727` |
| 24 | [#251019](https://github.com/microsoft/vscode/issues/251019) | BYOK timeout for ollama models | 0 | correctness | 4/6 Traced | 5 | — | `npm run implement -- --issue 251019` |
| 28 | [#298873](https://github.com/microsoft/vscode/issues/298873) | Custom models did not properly using think method (kimi2.5, glm5) | 0 | correctness | 5/6 Source-confirmed | 3 | — | — |
| 29 | [#320236](https://github.com/microsoft/vscode/issues/320236) | Copilot System prompt always trips Azure OpenAI Jailbreak filter | 0 | correctness | 3/6 Plausible | 3 | — | `npm run implement -- --issue 320236` |
| 32 | [#322299](https://github.com/microsoft/vscode/issues/322299) | Bug: Custom endpoint crashes with "No lowest priority node found" under context limits and silently ignores plain-text apiKey | 0 | correctness | 4/6 Traced | 2 | yes | `npm run implement -- --issue 322299` |
| 34 | [#324620](https://github.com/microsoft/vscode/issues/324620) | Failed to get response from AI model when testing Cerebras extension | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 35 | [#327597](https://github.com/microsoft/vscode/issues/327597) | kimi-k2.7-code generates tool_use IDs that block subsequent requests to Anthropic with HTTP 400 | 0 | correctness | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 327597` |
| 37 | [#317503](https://github.com/microsoft/vscode/issues/317503) | BYOK to GHCP throws an error (GPT 5.3 Codex model) | 0 | correctness | 3/6 Plausible | 1 | — | `npm run implement -- --issue 317503` |
| 38 | [#317534](https://github.com/microsoft/vscode/issues/317534) | BYOK Azure Foundry /responses fails with invalid input type (input[n].type) | 0 | correctness | 2/6 Unverified | 1 | — | — |
| 44 | [#322520](https://github.com/microsoft/vscode/issues/322520) | Issues with using output from models of Custom Endpoint | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 45 | [#323653](https://github.com/microsoft/vscode/issues/323653) | local model via byok in endless loop | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 56 | [#318101](https://github.com/microsoft/vscode/issues/318101) | Improve Azure OpenAI URL Handling in the BYOK Provider | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 318101` |
| 59 | [#319886](https://github.com/microsoft/vscode/issues/319886) | Ollama gemma model  Copilot adapter layer | 0 | none | 3/6 Plausible | 0 | — | — |
| 66 | [#323172](https://github.com/microsoft/vscode/issues/323172) | BYOK CustomEndpoint Model only thinks, cannot parse or strip `delta.reasoning` | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 323172` |
| 75 | [#325436](https://github.com/microsoft/vscode/issues/325436) | BYOK custom endpoint (Responses API) sends truncated input to servers that do not store responses | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 325436` |
| 76 | [#326527](https://github.com/microsoft/vscode/issues/326527) | gpt-5.6 BYOK fails | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 326527` |
| 77 | [#326597](https://github.com/microsoft/vscode/issues/326597) | Extension-contributed language model providers lose historical thinking needed for vLLM preserve_thinking | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 326597` |
| 79 | [#326914](https://github.com/microsoft/vscode/issues/326914) | Agent Host BYOK doubles customendpoint URL path → 404 | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 80 | [#327212](https://github.com/microsoft/vscode/issues/327212) | Chat custom endpoint: API key stored with trailing newline, causing 403 on all requests | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 327212` |

### Model routing settings (7)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 9 | [#323699](https://github.com/microsoft/vscode/issues/323699) | GitHub-managed custom model with Vision enabled is exposed as Tools-only and rejects image attachments | 5 | correctness | 3/6 Plausible | 22 | — | `npm run implement -- --issue 323699` |
| 13 | [#326554](https://github.com/microsoft/vscode/issues/326554) | Auto Mode Router overrides an explicitly selected BYOK model with a Copilot model | 2 | correctness | 3/6 Plausible | 18 | — | — |
| 20 | [#322408](https://github.com/microsoft/vscode/issues/322408) | setModelConfiguration write per-model settings to the wrong provider group when multiple groups share the same vendor | 0 | correctness | 2/6 Unverified | 8 | — | — |
| 21 | [#326797](https://github.com/microsoft/vscode/issues/326797) | Agent/Ask/Plan not switching properly with customendpoint BYOK model | 1 | correctness | 3/6 Plausible | 7 | — | `npm run implement -- --issue 326797` |
| 42 | [#319180](https://github.com/microsoft/vscode/issues/319180) | BYOK Custom Endpoint: 模型选择器修改思考力度后不生效，settings 字段不会自动创建 | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 58 | [#319131](https://github.com/microsoft/vscode/issues/319131) | Copilot agent model settings silently ignored when model ID format doesn't match internal ID — falls back to system default with no warning | 0 | papercut | 4/6 Traced | 0 | — | `npm run implement -- --issue 319131` |
| 70 | [#325069](https://github.com/microsoft/vscode/issues/325069) | Custom chat model settings collide when multiple providers expose the same model id | 0 | correctness | 4/6 Traced | 0 | — | `npm run implement -- --issue 325069` |

### Model picker management (14)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 14 | [#312908](https://github.com/microsoft/vscode/issues/312908) | Chat model picker hides BYOK models when their `metadata.id` collides with another vendor's model | 0 | correctness | 5/6 Source-confirmed | 13 | — | `npm run implement -- --issue 312908` |
| 23 | [#326344](https://github.com/microsoft/vscode/issues/326344) | agent 窗口缺少自定义模型 | 1 | correctness | 3/6 Plausible | 5 | — | `npm run implement -- --issue 326344` |
| 27 | [#326538](https://github.com/microsoft/vscode/issues/326538) | Language Models panel mixes LLM providers and chat session agents, appearing as confusing duplicates | 1 | visual | 3/6 Plausible | 3 | — | — |
| 31 | [#318748](https://github.com/microsoft/vscode/issues/318748) | Custom endpoint language models display id instead of name in model picker | 0 | visual | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 318748` |
| 39 | [#318415](https://github.com/microsoft/vscode/issues/318415) | BYOK UI: Group name should appear in UI of `Manage Language Models` | 0 | visual | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 318415` |
| 40 | [#318417](https://github.com/microsoft/vscode/issues/318417) | BYOK UI: Last model should not be selected after removing BYOK models | 0 | visual | 3/6 Plausible | 1 | — | `npm run implement -- --issue 318417` |
| 46 | [#264959](https://github.com/microsoft/vscode/issues/264959) | Live editing OAI Compatible setting doesn't reflect changes in model picker | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 264959` |
| 51 | [#315615](https://github.com/microsoft/vscode/issues/315615) | Models Management: Configure does nothing | 0 | papercut | 2/6 Unverified | 0 | — | `npm run implement -- --issue 315615` |
| 52 | [#315837](https://github.com/microsoft/vscode/issues/315837) | Models Management: Rendering Issues | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 315837` |
| 57 | [#318408](https://github.com/microsoft/vscode/issues/318408) | Selected model in a session isn't always preserved on Reload | 0 | correctness | 4/6 Traced | 0 | — | `npm run implement -- --issue 318408` |
| 61 | [#321663](https://github.com/microsoft/vscode/issues/321663) | Expanding model picker jumps in sessions window | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 321663` |
| 63 | [#322436](https://github.com/microsoft/vscode/issues/322436) | Double Copilot sections appear in manage models view | 0 | visual | 3/6 Plausible | 0 | — | `npm run implement -- --issue 322436` |
| 78 | [#326602](https://github.com/microsoft/vscode/issues/326602) | Clicking migrate on Ollama deprectaed setting leads to an error | 0 | papercut | 4/6 Traced | 0 | — | `npm run implement -- --issue 326602` |
| 81 | [#327460](https://github.com/microsoft/vscode/issues/327460) | Chat Languages Models missing | 0 | correctness | 3/6 Plausible | 0 | — | — |

### Tools and schemas (10)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 16 | [#320145](https://github.com/microsoft/vscode/issues/320145) | Tools without `inputSchema` send requests to OpenAI-compatible endpoints with `parameters` field omitted | 1 | correctness | 5/6 Source-confirmed | 9 | yes | `npm run implement -- --issue 320145` |
| 17 | [#320926](https://github.com/microsoft/vscode/issues/320926) | JSON Schema format for defining tools does not conform to OpenAI's specification | 0 | correctness | 5/6 Source-confirmed | 9 | yes | `npm run implement -- --issue 320926` |
| 22 | [#322731](https://github.com/microsoft/vscode/issues/322731) | Copilot chat Tools definition context bloat | 0 | visual | 5/6 Source-confirmed | 7 | yes | `npm run implement -- --issue 322731` |
| 49 | [#313520](https://github.com/microsoft/vscode/issues/313520) | Bug: `todo` tool not available to subAgents even when explicitly provided via frontmatter | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 313520` |
| 50 | [#314968](https://github.com/microsoft/vscode/issues/314968) | Copilot does not support MCP within local Ollama | 0 | none | 3/6 Plausible | 0 | — | — |
| 55 | [#317054](https://github.com/microsoft/vscode/issues/317054) | model duplicating todo tool text outside tool | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 317054` |
| 60 | [#321196](https://github.com/microsoft/vscode/issues/321196) | BYOK Responses API path does not stream `apply_patch` argument deltas to the tool UI | 0 | visual | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 321196` |
| 65 | [#323102](https://github.com/microsoft/vscode/issues/323102) | Copilot Chat: agent request crashes with "Cannot read properties of undefined (reading 'type')" in countToolTokens when a tool input schema uses top-level JSON-Schema if/then (BYOK / custom model) | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 323102` |
| 68 | [#324509](https://github.com/microsoft/vscode/issues/324509) | Background todo agent experiment silently disables `manage_todo_list`, breaking custom instructions and workflows | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 324509` |
| 74 | [#325425](https://github.com/microsoft/vscode/issues/325425) | Subagents fail with Ollama BYOK models: missing thought_signature | 0 | correctness | 3/6 Plausible | 0 | — | — |

### Todo agents (5)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 41 | [#318467](https://github.com/microsoft/vscode/issues/318467) | Todos: Background todo agent creates completed todos during plan agent runs | 0 | correctness | 3/6 Plausible | 1 | — | `npm run implement -- --issue 318467` |
| 47 | [#299858](https://github.com/microsoft/vscode/issues/299858) | stale checklist | 0 | none | 3/6 Plausible | 0 | — | — |
| 53 | [#315911](https://github.com/microsoft/vscode/issues/315911) | Background todo creates completed todo items immediately | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 315911` |
| 64 | [#322561](https://github.com/microsoft/vscode/issues/322561) | Agent Todos aren't showing as done | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 72 | [#325210](https://github.com/microsoft/vscode/issues/325210) | Todos in Copilot Chat | 0 | none | 3/6 Plausible | 0 | — | — |

### Other (2)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 26 | [#315165](https://github.com/microsoft/vscode/issues/315165) | Copilot rate-limit / monthly quota warnings shown when using a local model with byok | 1 | visual | 2/6 Unverified | 3 | — | `npm run implement -- --issue 315165` |
| 33 | [#322399](https://github.com/microsoft/vscode/issues/322399) | [Error] unhandlederror-ModelService: Cannot add model because it already exists! | 0 | correctness | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 322399` |

## Feature requests

### Custom model providers (9)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | [#318545](https://github.com/microsoft/vscode/issues/318545) | Support BYOK/Custom Models for Inline Code Completions | 153 | backlog-candidate | 100 | `npm run implement -- --issue 318545` |
| 2 | [#263535](https://github.com/microsoft/vscode/issues/263535) | Copilot Autocomplete with local / custom models | 190 | backlog-candidate | 86 | `npm run implement -- --issue 263535` |
| 3 | [#308442](https://github.com/microsoft/vscode/issues/308442) | Feature Request: Native LM Studio Integration (like Ollama) | 74 | backlog-candidate | 44 | `npm run implement -- --issue 308442` |
| 4 | [#319968](https://github.com/microsoft/vscode/issues/319968) | Feature request: Optional model discovery for customendpoint with OpenRouter or OpenAI-compatible providers | 36 | backlog-candidate | 22 | `npm run implement -- --issue 319968` |
| 10 | [#322688](https://github.com/microsoft/vscode/issues/322688) | Allow Copilot Chat to be proxied by endpoint. | 18 | backlog-candidate | 6 | `npm run implement -- --issue 322688` |
| 12 | [#325237](https://github.com/microsoft/vscode/issues/325237) | Better Custom Endpoint BYOK | 12 | backlog-candidate | 5 | `npm run implement -- --issue 325237` |
| 27 | [#268094](https://github.com/microsoft/vscode/issues/268094) | Enable discoverability of language model BYOK providers | 0 | backlog-candidate | 1 | — |
| 32 | [#278822](https://github.com/microsoft/vscode/issues/278822) | Azure AI Foundry BYOK provider | 0 | active | 0 | `npm run implement -- --issue 278822` |
| 48 | [#325844](https://github.com/microsoft/vscode/issues/325844) | Feature request: Support bring-your-own-model (BYO) routers (e.g. OpenRouter Fusion Router) | 0 | active | 0 | `npm run implement -- --issue 325844` |

### Provider compatibility (12)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 5 | [#322067](https://github.com/microsoft/vscode/issues/322067) | GitHub Copilot's BYOK feature supports passing custom parameters (e.g. `thinking.type`) | 29 | backlog-candidate | 13 | `npm run implement -- --issue 322067` |
| 6 | [#318540](https://github.com/microsoft/vscode/issues/318540) | Pass a session ID when using BYOM with OpenRouter. | 24 | backlog-candidate | 9 | `npm run implement -- --issue 318540` |
| 7 | [#318181](https://github.com/microsoft/vscode/issues/318181) | Support for xAI SuperGrok/SuperGrok Heavy OAuth with BYOK. | 22 | backlog-candidate | 9 | `npm run implement -- --issue 318181` |
| 18 | [#319099](https://github.com/microsoft/vscode/issues/319099) | [BYOM]: Models use Anthropic messages API  can not specify custom reasoning effort field path. | 6 | backlog-candidate | 2 | `npm run implement -- --issue 319099` |
| 25 | [#318967](https://github.com/microsoft/vscode/issues/318967) | BYOK Messages API incompatible with Vertex AI Anthropic endpoints | 1 | backlog-candidate | 1 | — |
| 28 | [#323110](https://github.com/microsoft/vscode/issues/323110) | BYOK Azure OpenAI: hardcoded temperature=0.1 breaks all GPT-5 reasoning models (not a transient failure, see #260506) | 0 | active | 1 | `npm run implement -- --issue 323110` |
| 30 | [#321372](https://github.com/microsoft/vscode/issues/321372) | Add support `extra_query` 、`extra_body` and `extra_headers ` for the custom endpoint AI model | 1 | active | 0 | `npm run implement -- --issue 321372` |
| 37 | [#317642](https://github.com/microsoft/vscode/issues/317642) | Add reasoning effort support for google byok models | 0 | active | 0 | — |
| 39 | [#319277](https://github.com/microsoft/vscode/issues/319277) | BYOK Azure provider: Support Anthropic-format deployments on Azure AI Services | 0 | active | 0 | `npm run implement -- --issue 319277` |
| 43 | [#324489](https://github.com/microsoft/vscode/issues/324489) | new endpoint /v1/responses | 0 | active | 0 | `npm run implement -- --issue 324489` |
| 44 | [#324961](https://github.com/microsoft/vscode/issues/324961) | BYOK PDF support requires a hardcoded model family | 0 | active | 0 | `npm run implement -- --issue 324961` |
| 49 | [#325906](https://github.com/microsoft/vscode/issues/325906) | Azure BYOM gpt-5.6-luna is capped at 256K context despite 1,050K Foundry context window | 0 | active | 0 | `npm run implement -- --issue 325906` |

### Model picker control (8)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 8 | [#266950](https://github.com/microsoft/vscode/issues/266950) | Restore local model selection (ability to disable models) in VS Code Copilot Chat | 11 | backlog-candidate | 8 | `npm run implement -- --issue 266950` |
| 9 | [#320345](https://github.com/microsoft/vscode/issues/320345) | Autodetect models | 19 | backlog-candidate | 7 | `npm run implement -- --issue 320345` |
| 22 | [#312960](https://github.com/microsoft/vscode/issues/312960) | Hide Claude Opus 4.7 in Model Picker (Unavailable Featured Models, Upgrade to Copilot Pro+) | 2 | active | 2 | — |
| 23 | [#288015](https://github.com/microsoft/vscode/issues/288015) | Model dropdown improvements | 1 | active | 2 | `npm run implement -- --issue 288015` |
| 29 | [#320260](https://github.com/microsoft/vscode/issues/320260) | BYOK "selectedCompletionModel" Bug | 1 | active | 0 | — |
| 34 | [#311999](https://github.com/microsoft/vscode/issues/311999) | BYOK for Manage Language Models - default should be not shown | 0 | backlog-candidate | 0 | `npm run implement -- --issue 311999` |
| 36 | [#317420](https://github.com/microsoft/vscode/issues/317420) | Add search/filter functionality to utility model settings | 0 | active | 0 | `npm run implement -- --issue 317420` |
| 45 | [#325455](https://github.com/microsoft/vscode/issues/325455) | vscode.lm — Add model visibility (hide/show) APIs | 0 | active | 0 | `npm run implement -- --issue 325455` |

### Routing and defaults (3)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 11 | [#324890](https://github.com/microsoft/vscode/issues/324890) | Utility model routing should follow the selected BYOK/local model, not only a global setting | 9 | backlog-candidate | 6 | `npm run implement -- --issue 324890` |
| 40 | [#319560](https://github.com/microsoft/vscode/issues/319560) | Fallback model selection into vscode | 0 | backlog-candidate | 0 | `npm run implement -- --issue 319560` |
| 42 | [#320715](https://github.com/microsoft/vscode/issues/320715) | enable user to set default model for Agent/Chat | 0 | active | 0 | `npm run implement -- --issue 320715` |

### Agent and CLI parity (6)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 13 | [#325738](https://github.com/microsoft/vscode/issues/325738) | Agents Window over SSH: BYOK unsupported + agent-host version mismatch blocks usage | 7 | active | 5 | `npm run implement -- --issue 325738` |
| 14 | [#308269](https://github.com/microsoft/vscode/issues/308269) | Copilot CLI: Support BYOK Model Providers | 5 | backlog-candidate | 5 | `npm run implement -- --issue 308269` |
| 20 | [#320056](https://github.com/microsoft/vscode/issues/320056) | Allow custom endpoint models for VS Code Copilot CLI sessions | 4 | active | 2 | — |
| 41 | [#319992](https://github.com/microsoft/vscode/issues/319992) | Continue without Sign In for Agents Window | 0 | active | 0 | — |
| 46 | [#325729](https://github.com/microsoft/vscode/issues/325729) | runSubagent BYOK Custom Endpoint model naming | 0 | active | 0 | `npm run implement -- --issue 325729` |
| 51 | [#327477](https://github.com/microsoft/vscode/issues/327477) | Agent mode needs BYOK/provider parity with Chat mode. | 0 | active | 0 | `npm run implement -- --issue 327477` |

### Usage and metadata (3)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 15 | [#320147](https://github.com/microsoft/vscode/issues/320147) | Show token cost metadata for BYOK models | 11 | backlog-candidate | 4 | `npm run implement -- --issue 320147` |
| 24 | [#255286](https://github.com/microsoft/vscode/issues/255286) | Language Model API doesn't allow system prompt | 1 | active | 1 | `npm run implement -- --issue 255286` |
| 33 | [#293306](https://github.com/microsoft/vscode/issues/293306) | Extending the stream for BYOK to include usage data | 0 | backlog-candidate | 0 | `npm run implement -- --issue 293306` |

### BYOK configuration (7)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 17 | [#322545](https://github.com/microsoft/vscode/issues/322545) | Using env variable for BYOK configuration does not work | 3 | backlog-candidate | 3 | `npm run implement -- --issue 322545` |
| 19 | [#318762](https://github.com/microsoft/vscode/issues/318762) | apiKeyHelper for BYOK Copilot Chat | 4 | backlog-candidate | 2 | `npm run implement -- --issue 318762` |
| 21 | [#323658](https://github.com/microsoft/vscode/issues/323658) | Feature Request: Auto-encrypt apiKey on save, group-level defaults, and auto-discover models for BYOK (chatLanguageModels.json) | 4 | backlog-candidate | 2 | `npm run implement -- --issue 323658` |
| 26 | [#326434](https://github.com/microsoft/vscode/issues/326434) | Add a supported non interactive CLI for provisioning BYOK model secrets into VS Code SecretStorage | 1 | active | 1 | `npm run implement -- --issue 326434` |
| 31 | [#322124](https://github.com/microsoft/vscode/issues/322124) | Add BYOK settings to Group Policies | 1 | active | 0 | `npm run implement -- --issue 322124` |
| 47 | [#325811](https://github.com/microsoft/vscode/issues/325811) | VSCode Chat add support for dynamic and changing APIKeys for some endpoints | 0 | active | 0 | — |
| 50 | [#327455](https://github.com/microsoft/vscode/issues/327455) | Can't update API key if I don't have more than one provider | 0 | backlog-candidate | 0 | `npm run implement -- --issue 327455` |

### Other (3)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 16 | [#320823](https://github.com/microsoft/vscode/issues/320823) | Add documentation for BYOK Custom Endpoint | 4 | active | 4 | `npm run implement -- --issue 320823` |
| 35 | [#315331](https://github.com/microsoft/vscode/issues/315331) | Consider adding Streamer mode for Copilot Chat | 0 | backlog-candidate | 0 | `npm run implement -- --issue 315331` |
| 38 | [#318612](https://github.com/microsoft/vscode/issues/318612) | BG Todo tool disablement | 0 | active | 0 | `npm run implement -- --issue 318612` |
