# Top issues by theme — vritant24

Experimental themed view of [the flat ranking](vritant24.md); themes assigned by the review engine. Rank/score are the lane-wide values. Generated 2026-08-02 14:02 UTC.

## Bugs

### Context and token accounting (10)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | [#313458](https://github.com/microsoft/vscode/issues/313458) | Copilot Chat local models do not populate Context Window usage even when backend usage and model limits are available | 15 | correctness | 5/6 Source-confirmed | 100 | — | — |
| 3 | [#318211](https://github.com/microsoft/vscode/issues/318211) | [Insiders] BYOK not showing reasoning tokens in chat | 10 | correctness | 2/6 Unverified | 39 | — | — |
| 6 | [#299907](https://github.com/microsoft/vscode/issues/299907) | Limited context size (33k) for Ollama Models | 2 | correctness | 5/6 Source-confirmed | 29 | yes | — |
| 20 | [#322216](https://github.com/microsoft/vscode/issues/322216) | Copilot Chat BYOK `vendor: openai` appears to ignore `maxInputTokens` and `maxOutputTokens` | 0 | correctness | 5/6 Source-confirmed | 8 | — | — |
| 23 | [#322731](https://github.com/microsoft/vscode/issues/322731) | Copilot chat Tools definition context bloat | 0 | visual | 5/6 Source-confirmed | 7 | yes | — |
| 26 | [#325197](https://github.com/microsoft/vscode/issues/325197) | "Error: No lowest priority node found (path: iie) at lxt" when having too little "maxInputTokens" | 1 | correctness | 6/6 Confirmed | 4 | — | — |
| 33 | [#322299](https://github.com/microsoft/vscode/issues/322299) | Bug: Custom endpoint crashes with "No lowest priority node found" under context limits and silently ignores plain-text apiKey | 0 | correctness | 4/6 Traced | 2 | yes | — |
| 50 | [#311705](https://github.com/microsoft/vscode/issues/311705) | Copilot Chat with Ollama/BYOK uses nominal context_length for prompt budgeting and drops token usage in the context widget | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 56 | [#316402](https://github.com/microsoft/vscode/issues/316402) | The max context of OpenRouter Model is wrong, it should be 1M. | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 63 | [#321761](https://github.com/microsoft/vscode/issues/321761) | "Reserved for response" ignores `maxOutputTokens` for extension-contributed models (hard-coded to 8192) | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |

### Model discovery and management (19)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2 | [#317255](https://github.com/microsoft/vscode/issues/317255) | Copilot Chat Sanity Test unable to resolve Copilot utility chat model | 0 | correctness | 3/6 Plausible | 41 | — | — |
| 8 | [#323699](https://github.com/microsoft/vscode/issues/323699) | GitHub-managed custom model with Vision enabled is exposed as Tools-only and rejects image attachments | 5 | correctness | 3/6 Plausible | 22 | — | — |
| 13 | [#312908](https://github.com/microsoft/vscode/issues/312908) | Chat model picker hides BYOK models when their `metadata.id` collides with another vendor's model | 0 | correctness | 5/6 Source-confirmed | 13 | — | — |
| 14 | [#328149](https://github.com/microsoft/vscode/issues/328149) | Lost Access to my other model providers, no longer see OpenCode and any other provider only Copilot | 0 | correctness | 3/6 Plausible | 13 | — | — |
| 24 | [#326344](https://github.com/microsoft/vscode/issues/326344) | agent 窗口缺少自定义模型 | 1 | correctness | 3/6 Plausible | 5 | — | — |
| 28 | [#326538](https://github.com/microsoft/vscode/issues/326538) | Language Models panel mixes LLM providers and chat session agents, appearing as confusing duplicates | 1 | visual | 3/6 Plausible | 3 | — | — |
| 32 | [#318748](https://github.com/microsoft/vscode/issues/318748) | Custom endpoint language models display id instead of name in model picker | 0 | visual | 5/6 Source-confirmed | 2 | — | — |
| 34 | [#322399](https://github.com/microsoft/vscode/issues/322399) | [Error] unhandlederror-ModelService: Cannot add model because it already exists! | 0 | correctness | 5/6 Source-confirmed | 2 | — | — |
| 38 | [#317414](https://github.com/microsoft/vscode/issues/317414) | [VS Code 1.120+] onDidChangeLanguageModelChatInformation EventEmitter presence causes all LM providers to collapse into Azure | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 40 | [#318415](https://github.com/microsoft/vscode/issues/318415) | BYOK UI: Group name should appear in UI of `Manage Language Models` | 0 | visual | 5/6 Source-confirmed | 1 | yes | — |
| 41 | [#318417](https://github.com/microsoft/vscode/issues/318417) | BYOK UI: Last model should not be selected after removing BYOK models | 0 | visual | 3/6 Plausible | 1 | — | — |
| 53 | [#315615](https://github.com/microsoft/vscode/issues/315615) | Models Management: Configure does nothing | 0 | papercut | 2/6 Unverified | 0 | — | — |
| 54 | [#315837](https://github.com/microsoft/vscode/issues/315837) | Models Management: Rendering Issues | 0 | visual | 3/6 Plausible | 0 | — | — |
| 64 | [#322436](https://github.com/microsoft/vscode/issues/322436) | Double Copilot sections appear in manage models view | 0 | visual | 3/6 Plausible | 0 | — | — |
| 70 | [#324755](https://github.com/microsoft/vscode/issues/324755) | Anthropic Provider not showing in Linux | 0 | none | 3/6 Plausible | 0 | — | — |
| 74 | [#325216](https://github.com/microsoft/vscode/issues/325216) | "No provider registered" log spam | 0 | papercut | 5/6 Source-confirmed | 0 | yes | — |
| 78 | [#326602](https://github.com/microsoft/vscode/issues/326602) | Clicking migrate on Ollama deprectaed setting leads to an error | 0 | papercut | 4/6 Traced | 0 | — | — |
| 80 | [#327460](https://github.com/microsoft/vscode/issues/327460) | Chat Languages Models missing | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 81 | [#327644](https://github.com/microsoft/vscode/issues/327644) | [Chat Model Picker] Duplicate 'copilot' group in the model list | 0 | visual | 5/6 Source-confirmed | 0 | — | — |

### API response compatibility (18)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 4 | [#322728](https://github.com/microsoft/vscode/issues/322728) | Custom BYOK endpoint: "Sorry, no response was returned" when empty tool_calls: [] on content deltas | 6 | correctness | 5/6 Source-confirmed | 38 | yes | — |
| 5 | [#324335](https://github.com/microsoft/vscode/issues/324335) | GitHub Copilot "Response Contained No Choices" Using BYOK - Ollama, OpenRouter.ai | 1 | correctness | 4/6 Traced | 33 | — | — |
| 7 | [#287533](https://github.com/microsoft/vscode/issues/287533) | xAI API not working for BYOK | 2 | correctness | 3/6 Plausible | 28 | — | — |
| 9 | [#319037](https://github.com/microsoft/vscode/issues/319037) | Custom Endpoint Models (Messages API) Never Send `thinking` Parameter | 4 | correctness | 5/6 Source-confirmed | 20 | yes | — |
| 10 | [#319122](https://github.com/microsoft/vscode/issues/319122) | Error with model azure foundry gtp. nano etc, this models send temperature to 01. | 3 | correctness | 5/6 Source-confirmed | 18 | — | — |
| 29 | [#320236](https://github.com/microsoft/vscode/issues/320236) | Copilot System prompt always trips Azure OpenAI Jailbreak filter | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 35 | [#324620](https://github.com/microsoft/vscode/issues/324620) | Failed to get response from AI model when testing Cerebras extension | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 36 | [#327597](https://github.com/microsoft/vscode/issues/327597) | kimi-k2.7-code generates tool_use IDs that block subsequent requests to Anthropic with HTTP 400 | 0 | correctness | 5/6 Source-confirmed | 2 | yes | — |
| 37 | [#328418](https://github.com/microsoft/vscode/issues/328418) | BYOK via Github Copilot Chat - 400 error on max-completion-token | 0 | correctness | 6/6 Confirmed | 2 | — | — |
| 39 | [#317503](https://github.com/microsoft/vscode/issues/317503) | BYOK to GHCP throws an error (GPT 5.3 Codex model) | 0 | correctness | 6/6 Confirmed | 1 | — | — |
| 45 | [#322520](https://github.com/microsoft/vscode/issues/322520) | Issues with using output from models of Custom Endpoint | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 46 | [#323653](https://github.com/microsoft/vscode/issues/323653) | local model via byok in endless loop | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 47 | [#328422](https://github.com/microsoft/vscode/issues/328422) | LanguageModelError - NotFound | 0 | correctness | 6/6 Confirmed | 1 | — | — |
| 61 | [#319886](https://github.com/microsoft/vscode/issues/319886) | Ollama gemma model  Copilot adapter layer | 0 | none | 3/6 Plausible | 0 | — | — |
| 67 | [#323172](https://github.com/microsoft/vscode/issues/323172) | BYOK CustomEndpoint Model only thinks, cannot parse or strip `delta.reasoning` | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 75 | [#325425](https://github.com/microsoft/vscode/issues/325425) | Subagents fail with Ollama BYOK models: missing thought_signature | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 76 | [#325436](https://github.com/microsoft/vscode/issues/325436) | BYOK custom endpoint (Responses API) sends truncated input to servers that do not store responses | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 77 | [#326597](https://github.com/microsoft/vscode/issues/326597) | Extension-contributed language model providers lose historical thinking needed for vLLM preserve_thinking | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |

### Model routing and persistence (4)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 12 | [#326554](https://github.com/microsoft/vscode/issues/326554) | Auto Mode Router overrides an explicitly selected BYOK model with a Copilot model | 2 | correctness | 3/6 Plausible | 18 | — | — |
| 22 | [#326797](https://github.com/microsoft/vscode/issues/326797) | Agent/Ask/Plan not switching properly with customendpoint BYOK model | 1 | correctness | 3/6 Plausible | 7 | — | — |
| 59 | [#318408](https://github.com/microsoft/vscode/issues/318408) | Selected model in a session isn't always preserved on Reload | 0 | correctness | 4/6 Traced | 0 | — | — |
| 60 | [#319131](https://github.com/microsoft/vscode/issues/319131) | Copilot agent model settings silently ignored when model ID format doesn't match internal ID — falls back to system default with no warning | 0 | papercut | 4/6 Traced | 0 | — | — |

### Provider access and availability (10)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 11 | [#320727](https://github.com/microsoft/vscode/issues/320727) | Incorrect Authorization header for apiKey in Custom Endpoint (BYOK) scenarios | 2 | correctness | 5/6 Source-confirmed | 18 | — | — |
| 16 | [#326389](https://github.com/microsoft/vscode/issues/326389) | 1.129.0 Regression: BYOK (ollama extension provider) fails without login | 0 | correctness | 5/6 Source-confirmed | 11 | — | — |
| 19 | [#327078](https://github.com/microsoft/vscode/issues/327078) | BYO LLM blocked when you cannot use Copilot | 0 | correctness | 5/6 Source-confirmed | 9 | — | — |
| 25 | [#251019](https://github.com/microsoft/vscode/issues/251019) | BYOK timeout for ollama models | 0 | correctness | 4/6 Traced | 5 | — | — |
| 27 | [#315165](https://github.com/microsoft/vscode/issues/315165) | Copilot rate-limit / monthly quota warnings shown when using a local model with byok | 1 | visual | 2/6 Unverified | 3 | — | — |
| 30 | [#320617](https://github.com/microsoft/vscode/issues/320617) | [Regression] [Error] [GitHub.copilot-chat] unhandlederror-fetch failed — byokContribution.fetchKnownModelList | 0 | correctness | 2/6 Unverified | 3 | — | — |
| 31 | [#328228](https://github.com/microsoft/vscode/issues/328228) | Running Azure Foundry BYOK causes Github pro+ account limit enforcement | 0 | correctness | 6/6 Confirmed | 3 | — | — |
| 44 | [#320537](https://github.com/microsoft/vscode/issues/320537) | BYOK dialog shows up, despite being signed in | 0 | visual | 3/6 Plausible | 1 | — | — |
| 68 | [#324245](https://github.com/microsoft/vscode/issues/324245) | BYOK: Can't use local model when VS Code Window is started without internet | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 72 | [#325186](https://github.com/microsoft/vscode/issues/325186) | Sending a chat when not signed in has an unhelpful error message | 0 | papercut | 5/6 Source-confirmed | 0 | — | — |

### Tool calling and schemas (6)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 17 | [#320145](https://github.com/microsoft/vscode/issues/320145) | Tools without `inputSchema` send requests to OpenAI-compatible endpoints with `parameters` field omitted | 1 | correctness | 5/6 Source-confirmed | 9 | yes | — |
| 18 | [#320926](https://github.com/microsoft/vscode/issues/320926) | JSON Schema format for defining tools does not conform to OpenAI's specification | 0 | correctness | 5/6 Source-confirmed | 9 | yes | — |
| 52 | [#314968](https://github.com/microsoft/vscode/issues/314968) | Copilot does not support MCP within local Ollama | 0 | none | 3/6 Plausible | 0 | — | — |
| 57 | [#317054](https://github.com/microsoft/vscode/issues/317054) | model duplicating todo tool text outside tool | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 62 | [#321196](https://github.com/microsoft/vscode/issues/321196) | BYOK Responses API path does not stream `apply_patch` argument deltas to the tool UI | 0 | visual | 5/6 Source-confirmed | 0 | — | — |
| 66 | [#323102](https://github.com/microsoft/vscode/issues/323102) | Copilot Chat: agent request crashes with "Cannot read properties of undefined (reading 'type')" in countToolTokens when a tool input schema uses top-level JSON-Schema if/then (BYOK / custom model) | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |

### Model identity and settings (8)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 21 | [#322408](https://github.com/microsoft/vscode/issues/322408) | setModelConfiguration write per-model settings to the wrong provider group when multiple groups share the same vendor | 0 | correctness | 2/6 Unverified | 8 | — | — |
| 43 | [#319180](https://github.com/microsoft/vscode/issues/319180) | BYOK Custom Endpoint: 模型选择器修改思考力度后不生效，settings 字段不会自动创建 | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 48 | [#264959](https://github.com/microsoft/vscode/issues/264959) | Live editing OAI Compatible setting doesn't reflect changes in model picker | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 58 | [#318101](https://github.com/microsoft/vscode/issues/318101) | Improve Azure OpenAI URL Handling in the BYOK Provider | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 71 | [#325069](https://github.com/microsoft/vscode/issues/325069) | Custom chat model settings collide when multiple providers expose the same model id | 0 | correctness | 4/6 Traced | 0 | — | — |
| 79 | [#326914](https://github.com/microsoft/vscode/issues/326914) | Agent Host BYOK doubles customendpoint URL path → 404 | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 82 | [#328055](https://github.com/microsoft/vscode/issues/328055) | Agent host can't list model in different custom endpoints but model have same id | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 83 | [#328277](https://github.com/microsoft/vscode/issues/328277) | Changing the reasoning effort causes overwrite of provider entry in chatLanguageModels.json | 0 | data-loss | 5/6 Source-confirmed | 0 | — | — |

### Todos and subagents (6)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 42 | [#318467](https://github.com/microsoft/vscode/issues/318467) | Todos: Background todo agent creates completed todos during plan agent runs | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 51 | [#313520](https://github.com/microsoft/vscode/issues/313520) | Bug: `todo` tool not available to subAgents even when explicitly provided via frontmatter | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 55 | [#315911](https://github.com/microsoft/vscode/issues/315911) | Background todo creates completed todo items immediately | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 65 | [#322561](https://github.com/microsoft/vscode/issues/322561) | Agent Todos aren't showing as done | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 69 | [#324509](https://github.com/microsoft/vscode/issues/324509) | Background todo agent experiment silently disables `manage_todo_list`, breaking custom instructions and workflows | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 73 | [#325210](https://github.com/microsoft/vscode/issues/325210) | Todos in Copilot Chat | 0 | none | 3/6 Plausible | 0 | — | — |

### Other (2)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 15 | [#327994](https://github.com/microsoft/vscode/issues/327994) | Agent Bug | 0 | correctness | 6/6 Confirmed | 12 | — | — |
| 49 | [#299858](https://github.com/microsoft/vscode/issues/299858) | stale checklist | 0 | none | 3/6 Plausible | 0 | — | — |

## Feature requests

### Inline completion models (2)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | [#318545](https://github.com/microsoft/vscode/issues/318545) | Support BYOK/Custom Models for Inline Code Completions | 153 | backlog-candidate | 100 | — |
| 2 | [#263535](https://github.com/microsoft/vscode/issues/263535) | Copilot Autocomplete with local / custom models | 190 | backlog-candidate | 87 | — |

### Provider integrations (6)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 3 | [#308442](https://github.com/microsoft/vscode/issues/308442) | Feature Request: Native LM Studio Integration (like Ollama) | 74 | backlog-candidate | 44 | — |
| 8 | [#318181](https://github.com/microsoft/vscode/issues/318181) | Support for xAI SuperGrok/SuperGrok Heavy OAuth with BYOK. | 22 | backlog-candidate | 9 | — |
| 30 | [#278822](https://github.com/microsoft/vscode/issues/278822) | Azure AI Foundry BYOK provider | 0 | active | 0 | — |
| 37 | [#319277](https://github.com/microsoft/vscode/issues/319277) | BYOK Azure provider: Support Anthropic-format deployments on Azure AI Services | 0 | active | 0 | — |
| 40 | [#324489](https://github.com/microsoft/vscode/issues/324489) | new endpoint /v1/responses | 0 | active | 0 | — |
| 45 | [#325844](https://github.com/microsoft/vscode/issues/325844) | Feature request: Support bring-your-own-model (BYO) routers (e.g. OpenRouter Fusion Router) | 0 | active | 0 | — |

### Model discovery controls (7)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 4 | [#319968](https://github.com/microsoft/vscode/issues/319968) | Feature request: Optional model discovery for customendpoint with OpenRouter or OpenAI-compatible providers | 36 | backlog-candidate | 22 | — |
| 9 | [#266950](https://github.com/microsoft/vscode/issues/266950) | Restore local model selection (ability to disable models) in VS Code Copilot Chat | 11 | backlog-candidate | 8 | — |
| 10 | [#320345](https://github.com/microsoft/vscode/issues/320345) | Autodetect models | 19 | backlog-candidate | 7 | — |
| 22 | [#288015](https://github.com/microsoft/vscode/issues/288015) | Model dropdown improvements | 1 | active | 2 | — |
| 25 | [#268094](https://github.com/microsoft/vscode/issues/268094) | Enable discoverability of language model BYOK providers | 0 | backlog-candidate | 1 | — |
| 32 | [#311999](https://github.com/microsoft/vscode/issues/311999) | BYOK for Manage Language Models - default should be not shown | 0 | backlog-candidate | 0 | — |
| 34 | [#317420](https://github.com/microsoft/vscode/issues/317420) | Add search/filter functionality to utility model settings | 0 | active | 0 | — |

### Agent and CLI parity (6)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 5 | [#318578](https://github.com/microsoft/vscode/issues/318578) | Use Agents Window without signing in | 30 | backlog-candidate | 19 | — |
| 14 | [#325738](https://github.com/microsoft/vscode/issues/325738) | Agents Window over SSH: BYOK unsupported + agent-host version mismatch blocks usage | 7 | active | 5 | — |
| 15 | [#308269](https://github.com/microsoft/vscode/issues/308269) | Copilot CLI: Support BYOK Model Providers | 5 | backlog-candidate | 5 | — |
| 20 | [#320056](https://github.com/microsoft/vscode/issues/320056) | Allow custom endpoint models for VS Code Copilot CLI sessions | 4 | active | 2 | — |
| 43 | [#325729](https://github.com/microsoft/vscode/issues/325729) | runSubagent BYOK Custom Endpoint model naming | 0 | active | 0 | — |
| 47 | [#327477](https://github.com/microsoft/vscode/issues/327477) | Agent mode needs BYOK/provider parity with Chat mode. | 0 | active | 0 | — |

### Endpoint customization (11)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 6 | [#322067](https://github.com/microsoft/vscode/issues/322067) | GitHub Copilot's BYOK feature supports passing custom parameters (e.g. `thinking.type`) | 29 | backlog-candidate | 13 | — |
| 7 | [#318540](https://github.com/microsoft/vscode/issues/318540) | Pass a session ID when using BYOM with OpenRouter. | 24 | backlog-candidate | 9 | — |
| 11 | [#322688](https://github.com/microsoft/vscode/issues/322688) | Allow Copilot Chat to be proxied by endpoint. | 18 | backlog-candidate | 6 | — |
| 13 | [#325237](https://github.com/microsoft/vscode/issues/325237) | Better Custom Endpoint BYOK | 12 | backlog-candidate | 5 | — |
| 17 | [#320823](https://github.com/microsoft/vscode/issues/320823) | Add documentation for BYOK Custom Endpoint | 4 | active | 4 | — |
| 18 | [#316794](https://github.com/microsoft/vscode/issues/316794) | Support custom headers or stable chat session identifiers for BYOK/OpenAI-compatible model providers | 6 | active | 3 | — |
| 26 | [#323110](https://github.com/microsoft/vscode/issues/323110) | BYOK Azure OpenAI: hardcoded temperature=0.1 breaks all GPT-5 reasoning models (not a transient failure, see #260506) | 0 | active | 1 | — |
| 28 | [#321372](https://github.com/microsoft/vscode/issues/321372) | Add support `extra_query` 、`extra_body` and `extra_headers ` for the custom endpoint AI model | 1 | active | 0 | — |
| 35 | [#317642](https://github.com/microsoft/vscode/issues/317642) | Add reasoning effort support for google byok models | 0 | active | 0 | — |
| 41 | [#324961](https://github.com/microsoft/vscode/issues/324961) | BYOK PDF support requires a hardcoded model family | 0 | active | 0 | — |
| 48 | [#327976](https://github.com/microsoft/vscode/issues/327976) | Add max_tokens as allowed modelOption | 0 | active | 0 | — |

### Model routing defaults (4)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 12 | [#324890](https://github.com/microsoft/vscode/issues/324890) | Utility model routing should follow the selected BYOK/local model, not only a global setting | 9 | backlog-candidate | 6 | — |
| 27 | [#320260](https://github.com/microsoft/vscode/issues/320260) | BYOK "selectedCompletionModel" Bug | 1 | active | 0 | — |
| 38 | [#319560](https://github.com/microsoft/vscode/issues/319560) | Fallback model selection into vscode | 0 | backlog-candidate | 0 | — |
| 39 | [#320715](https://github.com/microsoft/vscode/issues/320715) | enable user to set default model for Agent/Chat | 0 | active | 0 | — |

### Usage and costs (2)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 16 | [#320147](https://github.com/microsoft/vscode/issues/320147) | Show token cost metadata for BYOK models | 11 | backlog-candidate | 4 | — |
| 31 | [#293306](https://github.com/microsoft/vscode/issues/293306) | Extending the stream for BYOK to include usage data | 0 | backlog-candidate | 0 | — |

### Secrets and policy (6)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 19 | [#322545](https://github.com/microsoft/vscode/issues/322545) | Using env variable for BYOK configuration does not work | 3 | backlog-candidate | 3 | — |
| 21 | [#323658](https://github.com/microsoft/vscode/issues/323658) | Feature Request: Auto-encrypt apiKey on save, group-level defaults, and auto-discover models for BYOK (chatLanguageModels.json) | 4 | backlog-candidate | 2 | — |
| 24 | [#326434](https://github.com/microsoft/vscode/issues/326434) | Add a supported non interactive CLI for provisioning BYOK model secrets into VS Code SecretStorage | 1 | active | 1 | — |
| 29 | [#322124](https://github.com/microsoft/vscode/issues/322124) | Add BYOK settings to Group Policies | 1 | active | 0 | — |
| 44 | [#325811](https://github.com/microsoft/vscode/issues/325811) | VSCode Chat add support for dynamic and changing APIKeys for some endpoints | 0 | active | 0 | — |
| 46 | [#327455](https://github.com/microsoft/vscode/issues/327455) | Can't update API key if I don't have more than one provider | 0 | backlog-candidate | 0 | — |

### Language model APIs (2)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 23 | [#255286](https://github.com/microsoft/vscode/issues/255286) | Language Model API doesn't allow system prompt | 1 | active | 1 | — |
| 42 | [#325455](https://github.com/microsoft/vscode/issues/325455) | vscode.lm — Add model visibility (hide/show) APIs | 0 | active | 0 | — |

### Chat privacy controls (2)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 33 | [#315331](https://github.com/microsoft/vscode/issues/315331) | Consider adding Streamer mode for Copilot Chat | 0 | backlog-candidate | 0 | — |
| 36 | [#318612](https://github.com/microsoft/vscode/issues/318612) | BG Todo tool disablement | 0 | active | 0 | — |
