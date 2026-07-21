# Top issues by theme — chrmarti

Experimental themed view of [the flat ranking](chrmarti.md); themes assigned by the review engine. Rank/score are the lane-wide values. Generated 2026-07-21 15:48 UTC.

## Bugs

### Extension installation (9)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | [#34385](https://github.com/microsoft/vscode/issues/34385) | XHR Failed on trying to install plugins via Visual Studio code | 108 | correctness | 2/6 Unverified | 100 | — | — |
| 15 | [#277300](https://github.com/microsoft/vscode/issues/277300) | Google Authentication stopped working in 1.106 | 2 | correctness | 2/6 Unverified | 8 | — | — |
| 37 | [#301087](https://github.com/microsoft/vscode/issues/301087) | Cannot install Copilot Chat extension: "End of central directory record signature not found" (zip/VSIX error) in Codespaces | 1 | correctness | — | 4 | — | — |
| 90 | [#90900](https://github.com/microsoft/vscode/issues/90900) | Warning in package.json when specifying icon without https repository | 5 | papercut | 2/6 Unverified | 1 | — | `npm run implement -- --issue 90900` |
| 152 | [#60669](https://github.com/microsoft/vscode/issues/60669) | `extensions/extension-editing/src/extensionLinter.ts` does not respect `repository` shorthand in package.json | 1 | papercut | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 60669` |
| 256 | [#299929](https://github.com/microsoft/vscode/issues/299929) | All of a sudden the whole VS code extensions got refreshed on their own. | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 261 | [#300488](https://github.com/microsoft/vscode/issues/300488) | Extension Signature Verification Failed: GitHub Copilot Chat | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 284 | [#305558](https://github.com/microsoft/vscode/issues/305558) | I can't install any extention | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 299 | [#311976](https://github.com/microsoft/vscode/issues/311976) | Unable to activate an extension | 0 | none | 3/6 Plausible | 0 | — | — |

### Performance and crashes (20)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2 | [#312110](https://github.com/microsoft/vscode/issues/312110) | PendingMigrationError: navigator is now a global in nodejs thrown during module load on remote VS Code server,   causing repeated renderer crashes and Remote SSH disconnections | 3 | crash | 4/6 Traced | 28 | — | `npm run implement -- --issue 312110` |
| 3 | [#300132](https://github.com/microsoft/vscode/issues/300132) | The rg process uses a huge amount of CPU. | 8 | perf | 3/6 Plausible | 24 | — | — |
| 5 | [#312925](https://github.com/microsoft/vscode/issues/312925) | VS Code crashes (code 5) with Remote SSH + Copilot Chat codebase indexing on M1 | 9 | crash | 3/6 Plausible | 20 | — | `npm run implement -- --issue 312925` |
| 23 | [#298401](https://github.com/microsoft/vscode/issues/298401) | After updating to the latest version of VS Code, the coding process has become extremely laggy, and memory usage spikes dramatically. | 7 | none | — | 5 | — | — |
| 25 | [#300855](https://github.com/microsoft/vscode/issues/300855) | Failed to load native module: pty.node | 4 | correctness | — | 5 | — | — |
| 32 | [#311227](https://github.com/microsoft/vscode/issues/311227) | Remote window crashes with code 4 on reopen; PTY restore fails and Copilot Chat throws `PendingMigrationError` | 0 | crash | 3/6 Plausible | 5 | — | — |
| 38 | [#311239](https://github.com/microsoft/vscode/issues/311239) | GitHub copilot Chat makes a helper renderer eating memory all the way up till crash | 1 | crash | 3/6 Plausible | 4 | — | — |
| 51 | [#313208](https://github.com/microsoft/vscode/issues/313208) | crash and oom | 1 | crash | 3/6 Plausible | 3 | — | — |
| 101 | [#296452](https://github.com/microsoft/vscode/issues/296452) | VS code UI slows down when Copilot generates code | 1 | perf | 3/6 Plausible | 1 | — | — |
| 144 | [#301851](https://github.com/microsoft/vscode/issues/301851) | TypeScript hangs and crashes trying to parse JavaScript files | 0 | freeze | 3/6 Plausible | 1 | — | — |
| 174 | [#269004](https://github.com/microsoft/vscode/issues/269004) | Maximum call stack size exceeded | 0 | none | 3/6 Plausible | 0 | — | — |
| 238 | [#296109](https://github.com/microsoft/vscode/issues/296109) | Claude Code Crashes & VS Code Crashes Requiring restart | 0 | crash | 3/6 Plausible | 0 | — | — |
| 257 | [#299957](https://github.com/microsoft/vscode/issues/299957) | Critical performance issues with Copilot Chat – Credits wasted due to freezing | 0 | freeze | 3/6 Plausible | 0 | — | — |
| 259 | [#300056](https://github.com/microsoft/vscode/issues/300056) | Unusably slow | 0 | none | — | 0 | — | — |
| 260 | [#300112](https://github.com/microsoft/vscode/issues/300112) | New version took a long time to load when asking via Copilot | 0 | none | 3/6 Plausible | 0 | — | — |
| 269 | [#301751](https://github.com/microsoft/vscode/issues/301751) | latest mandatory update march 14 regressed when many files are open | 0 | none | 3/6 Plausible | 0 | — | — |
| 276 | [#303371](https://github.com/microsoft/vscode/issues/303371) | Regression: Extension Host (Code 6) crash on macOS after updating to 26.4 | 0 | crash | 2/6 Unverified | 0 | — | — |
| 278 | [#303477](https://github.com/microsoft/vscode/issues/303477) | Cannot find module '/home/cdsw/.vscode-server/extensions/github.copilot-chat-0.39.2/dist/tikTokenizerWorker.js' | 0 | papercut | 2/6 Unverified | 0 | — | — |
| 279 | [#303739](https://github.com/microsoft/vscode/issues/303739) | Copilot crashes on CNB.cool docker workspaces | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 290 | [#306659](https://github.com/microsoft/vscode/issues/306659) | Copilot performance degraded significantly. | 0 | none | 3/6 Plausible | 0 | — | — |

### Copilot service errors (102)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 4 | [#292795](https://github.com/microsoft/vscode/issues/292795) | "Invalid String Length" in Copilot Chat | 10 | correctness | 2/6 Unverified | 21 | — | — |
| 11 | [#298592](https://github.com/microsoft/vscode/issues/298592) | Can't open new Codex session | 8 | correctness | — | 10 | — | — |
| 24 | [#299513](https://github.com/microsoft/vscode/issues/299513) | issue with claude code in github copilot | 4 | correctness | 5/6 Source-confirmed | 5 | — | — |
| 26 | [#293540](https://github.com/microsoft/vscode/issues/293540) | Claude Opus 4.6 "Sorry, no reponse was returned" | 3 | correctness | 3/6 Plausible | 5 | — | — |
| 42 | [#294693](https://github.com/microsoft/vscode/issues/294693) | Chat took too long to respond error message | 0 | correctness | 3/6 Plausible | 4 | — | `npm run implement -- --issue 294693` |
| 48 | [#287567](https://github.com/microsoft/vscode/issues/287567) | Github copilot chat not working | 1 | correctness | 3/6 Plausible | 3 | — | `npm run implement -- --issue 287567` |
| 61 | [#293594](https://github.com/microsoft/vscode/issues/293594) | Sorry, your request failed. Please try again.  Copilot Request id: 7be4f12f-ba3e-4ec4-b037-4a5004ae53f5  Reason: Error on conversation request. Check the log for more details. | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 62 | [#307073](https://github.com/microsoft/vscode/issues/307073) | Simple request returned with mgt.clearMarks is not a function | 0 | none | — | 3 | — | — |
| 76 | [#283014](https://github.com/microsoft/vscode/issues/283014) | Request timeout after 60000ms | 0 | correctness | 3/6 Plausible | 2 | — | `npm run implement -- --issue 283014` |
| 77 | [#285115](https://github.com/microsoft/vscode/issues/285115) | Copilot Freezing on "working..." | 0 | none | 3/6 Plausible | 2 | — | — |
| 78 | [#286729](https://github.com/microsoft/vscode/issues/286729) | Network error: ERR_SSL_PROTOCOL_ERROR | 0 | none | 3/6 Plausible | 2 | — | — |
| 96 | [#287785](https://github.com/microsoft/vscode/issues/287785) | Sorry, your request failed. Please try again. | 1 | none | — | 1 | — | — |
| 97 | [#288168](https://github.com/microsoft/vscode/issues/288168) | Chat took too long to get ready | 1 | perf | 3/6 Plausible | 1 | — | `npm run implement -- --issue 288168` |
| 98 | [#288380](https://github.com/microsoft/vscode/issues/288380) | Chat took too long to get ready | 1 | perf | 3/6 Plausible | 1 | — | — |
| 99 | [#289029](https://github.com/microsoft/vscode/issues/289029) | A temporary solution to solve "Chat took too long to get ready", and hope this can be fixed. | 1 | none | — | 1 | — | — |
| 102 | [#297634](https://github.com/microsoft/vscode/issues/297634) | Interrupted by network errors while network is connected | 1 | none | 3/6 Plausible | 1 | — | — |
| 103 | [#297784](https://github.com/microsoft/vscode/issues/297784) | Subject: CRITICAL BUG: Copilot Opus 4.6 repeatedly fails on new file creation and drains credits | 1 | none | — | 1 | — | — |
| 104 | [#298811](https://github.com/microsoft/vscode/issues/298811) | Chat took too long to get ready. | 1 | none | 3/6 Plausible | 1 | — | — |
| 105 | [#300705](https://github.com/microsoft/vscode/issues/300705) | Remote Index Unavailable | 1 | none | 3/6 Plausible | 1 | — | — |
| 108 | [#305120](https://github.com/microsoft/vscode/issues/305120) | False network error. | 1 | none | 3/6 Plausible | 1 | — | — |
| 109 | [#305515](https://github.com/microsoft/vscode/issues/305515) | Copilotの応答が表示されない | 1 | correctness | 3/6 Plausible | 1 | — | — |
| 111 | [#307086](https://github.com/microsoft/vscode/issues/307086) | Request Failed: 400 | 1 | none | 3/6 Plausible | 1 | — | — |
| 112 | [#307122](https://github.com/microsoft/vscode/issues/307122) | No Response! | 1 | none | 3/6 Plausible | 1 | — | — |
| 147 | [#307089](https://github.com/microsoft/vscode/issues/307089) | Freguent "Timed out reading request body" error | 0 | none | — | 1 | — | — |
| 148 | [#307496](https://github.com/microsoft/vscode/issues/307496) | error | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 179 | [#283893](https://github.com/microsoft/vscode/issues/283893) | erver error. Stream terminated | 0 | none | 3/6 Plausible | 0 | — | — |
| 180 | [#283961](https://github.com/microsoft/vscode/issues/283961) | Server error | 0 | none | 3/6 Plausible | 0 | — | — |
| 181 | [#284016](https://github.com/microsoft/vscode/issues/284016) | 502s and 504s | 0 | none | — | 0 | — | — |
| 182 | [#284646](https://github.com/microsoft/vscode/issues/284646) | failed to get a response. Please try again message | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 185 | [#285135](https://github.com/microsoft/vscode/issues/285135) | Poor Analysis | 0 | none | 3/6 Plausible | 0 | — | — |
| 186 | [#285771](https://github.com/microsoft/vscode/issues/285771) | Lost in a loop | 0 | none | — | 0 | — | — |
| 187 | [#286515](https://github.com/microsoft/vscode/issues/286515) | Error on conversation request | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 188 | [#286874](https://github.com/microsoft/vscode/issues/286874) | Reason: Server error: 500 - Unrecoverable error have to clear context | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 189 | [#287033](https://github.com/microsoft/vscode/issues/287033) | error 500 | 0 | none | 3/6 Plausible | 0 | — | — |
| 191 | [#287144](https://github.com/microsoft/vscode/issues/287144) | Copilot travado | 0 | none | 3/6 Plausible | 0 | — | — |
| 192 | [#287167](https://github.com/microsoft/vscode/issues/287167) | Sorry, your request failed. Please try again. | 0 | none | 3/6 Plausible | 0 | — | — |
| 193 | [#287233](https://github.com/microsoft/vscode/issues/287233) | copilot stop to work after some time | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 194 | [#287628](https://github.com/microsoft/vscode/issues/287628) | Chat took too long to get ready | 0 | none | 3/6 Plausible | 0 | — | — |
| 195 | [#287629](https://github.com/microsoft/vscode/issues/287629) | Chat took too long to get ready | 0 | none | 3/6 Plausible | 0 | — | — |
| 196 | [#287732](https://github.com/microsoft/vscode/issues/287732) | bad request | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 197 | [#287962](https://github.com/microsoft/vscode/issues/287962) | socket hang up | 0 | none | 3/6 Plausible | 0 | — | — |
| 198 | [#287992](https://github.com/microsoft/vscode/issues/287992) | Chat took too long to get ready | 0 | none | 3/6 Plausible | 0 | — | — |
| 199 | [#288080](https://github.com/microsoft/vscode/issues/288080) | Chat took too long to get ready | 0 | none | 3/6 Plausible | 0 | — | — |
| 202 | [#288406](https://github.com/microsoft/vscode/issues/288406) | Sorry, there was a network error. Please try again later. | 0 | none | 3/6 Plausible | 0 | — | — |
| 203 | [#288554](https://github.com/microsoft/vscode/issues/288554) | Chat took too long to get ready | 0 | perf | 3/6 Plausible | 0 | — | — |
| 204 | [#289123](https://github.com/microsoft/vscode/issues/289123) | Copilet takes very long time to respond | 0 | none | 3/6 Plausible | 0 | — | — |
| 205 | [#289196](https://github.com/microsoft/vscode/issues/289196) | Error | 0 | none | 3/6 Plausible | 0 | — | — |
| 206 | [#289303](https://github.com/microsoft/vscode/issues/289303) | request failed invalid json format | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 207 | [#289418](https://github.com/microsoft/vscode/issues/289418) | Error on conversation request | 0 | none | 3/6 Plausible | 0 | — | — |
| 208 | [#289574](https://github.com/microsoft/vscode/issues/289574) | Not able to initialize chat | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 209 | [#289765](https://github.com/microsoft/vscode/issues/289765) | error 500 | 0 | none | 3/6 Plausible | 0 | — | — |
| 210 | [#289796](https://github.com/microsoft/vscode/issues/289796) | Chat took too long to get ready | 0 | none | 3/6 Plausible | 0 | — | — |
| 211 | [#290030](https://github.com/microsoft/vscode/issues/290030) | Chat took too long to get ready | 0 | none | 3/6 Plausible | 0 | — | — |
| 213 | [#290923](https://github.com/microsoft/vscode/issues/290923) | Chat took too long to get ready | 0 | none | 3/6 Plausible | 0 | — | — |
| 214 | [#291186](https://github.com/microsoft/vscode/issues/291186) | Won't be able to chat | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 216 | [#291612](https://github.com/microsoft/vscode/issues/291612) | Copilot: tokenization issue | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 217 | [#291675](https://github.com/microsoft/vscode/issues/291675) | Refuse to provide information | 0 | none | — | 0 | — | — |
| 218 | [#291733](https://github.com/microsoft/vscode/issues/291733) | Prompt keeps failing | 0 | none | 3/6 Plausible | 0 | — | — |
| 219 | [#292039](https://github.com/microsoft/vscode/issues/292039) | error | 0 | none | 3/6 Plausible | 0 | — | — |
| 220 | [#292648](https://github.com/microsoft/vscode/issues/292648) | Constant request failed error. | 0 | none | — | 0 | — | — |
| 221 | [#292670](https://github.com/microsoft/vscode/issues/292670) | Constant Reason: Request Failed: 400 | 0 | none | — | 0 | — | — |
| 222 | [#292716](https://github.com/microsoft/vscode/issues/292716) | I HAVE 300MBPS INTERNET CONECTION AND I GET NETWORG ERRORR | 0 | none | 3/6 Plausible | 0 | — | — |
| 224 | [#292897](https://github.com/microsoft/vscode/issues/292897) | [object Object] in network error message | 0 | visual | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 292897` |
| 225 | [#292976](https://github.com/microsoft/vscode/issues/292976) | Chat took too long to get ready | 0 | none | 3/6 Plausible | 0 | — | — |
| 226 | [#293061](https://github.com/microsoft/vscode/issues/293061) | Fix Stream Disconnection Error When Using Codex with GitHub Copilot Pro+ Subscription | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 227 | [#293391](https://github.com/microsoft/vscode/issues/293391) | Not returning an actual response | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 228 | [#293593](https://github.com/microsoft/vscode/issues/293593) | Sorry, your request failed. Please try again.  Copilot Request id: 7be4f12f-ba3e-4ec4-b037-4a5004ae53f5  Reason: Error on conversation request. Check the log for more details. | 0 | none | 3/6 Plausible | 0 | — | — |
| 231 | [#295319](https://github.com/microsoft/vscode/issues/295319) | error chat | 0 | none | 3/6 Plausible | 0 | — | — |
| 232 | [#295424](https://github.com/microsoft/vscode/issues/295424) | Error Code: net::ERR_CONNECTION_CLOSED | 0 | none | 3/6 Plausible | 0 | — | — |
| 236 | [#296016](https://github.com/microsoft/vscode/issues/296016) | net::ERR_CONNECTION_TIMED_OUT: [object Object]. | 0 | papercut | 2/6 Unverified | 0 | — | — |
| 237 | [#296020](https://github.com/microsoft/vscode/issues/296020) | Reason: Request Failed: 400 | 0 | none | 3/6 Plausible | 0 | — | — |
| 239 | [#296339](https://github.com/microsoft/vscode/issues/296339) | request body is not valid json error | 0 | none | — | 0 | — | — |
| 241 | [#296605](https://github.com/microsoft/vscode/issues/296605) | Requests failing with Code SIGKILL | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 242 | [#296673](https://github.com/microsoft/vscode/issues/296673) | It is impossible to use, too many errors | 0 | none | — | 0 | — | — |
| 243 | [#296834](https://github.com/microsoft/vscode/issues/296834) | Lost server connection. | 0 | none | 3/6 Plausible | 0 | — | — |
| 244 | [#296987](https://github.com/microsoft/vscode/issues/296987) | Opus 4.6 cant create a prompt. process times out | 0 | none | 3/6 Plausible | 0 | — | — |
| 246 | [#297679](https://github.com/microsoft/vscode/issues/297679) | alwaysfails with the issue on long run in between analysis and consumes more of premin=um availability without any results | 0 | none | 3/6 Plausible | 0 | — | — |
| 247 | [#298162](https://github.com/microsoft/vscode/issues/298162) | 网络错误 | 0 | none | 3/6 Plausible | 0 | — | — |
| 248 | [#298398](https://github.com/microsoft/vscode/issues/298398) | 网络错误，但是没有出现重试按钮。 | 0 | none | 3/6 Plausible | 0 | — | — |
| 249 | [#298455](https://github.com/microsoft/vscode/issues/298455) | Chat won't load | 0 | none | — | 0 | — | — |
| 250 | [#298725](https://github.com/microsoft/vscode/issues/298725) | Github Copilot Chat is not working | 0 | none | 3/6 Plausible | 0 | — | — |
| 251 | [#298847](https://github.com/microsoft/vscode/issues/298847) | Can not load anything | 0 | none | 3/6 Plausible | 0 | — | — |
| 252 | [#298868](https://github.com/microsoft/vscode/issues/298868) | Timed out reading request body. Try again, or use a smaller request size.","code":"user_request_timeout"}} | 0 | none | — | 0 | — | — |
| 258 | [#300010](https://github.com/microsoft/vscode/issues/300010) | Connection Reset: [object Object] when making large diffs | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 300010` |
| 262 | [#300666](https://github.com/microsoft/vscode/issues/300666) | sometimes chat is not responding | 0 | none | 3/6 Plausible | 0 | — | — |
| 263 | [#300879](https://github.com/microsoft/vscode/issues/300879) | Neywork issue with perfectly working network | 0 | none | — | 0 | — | — |
| 265 | [#301425](https://github.com/microsoft/vscode/issues/301425) | Opus 4.6 keeps failing | 0 | none | — | 0 | — | — |
| 266 | [#301448](https://github.com/microsoft/vscode/issues/301448) | Sorry, no response was returned. | 0 | none | — | 0 | — | — |
| 267 | [#301477](https://github.com/microsoft/vscode/issues/301477) | Never reposnds to any chat! | 0 | none | 3/6 Plausible | 0 | — | — |
| 268 | [#301548](https://github.com/microsoft/vscode/issues/301548) | Chat doesnt answer | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 273 | [#302444](https://github.com/microsoft/vscode/issues/302444) | Duplicate File Creation Causes Network Error and Final Failure | 0 | none | 3/6 Plausible | 0 | — | — |
| 285 | [#305783](https://github.com/microsoft/vscode/issues/305783) | Doesnt work | 0 | none | 3/6 Plausible | 0 | — | — |
| 288 | [#305981](https://github.com/microsoft/vscode/issues/305981) | Connection to AI just ... stopped. | 0 | none | 3/6 Plausible | 0 | — | — |
| 293 | [#308022](https://github.com/microsoft/vscode/issues/308022) | Gettting CopilotToken fails | 0 | papercut | 2/6 Unverified | 0 | — | `npm run implement -- --issue 308022` |
| 294 | [#310102](https://github.com/microsoft/vscode/issues/310102) | Getting "Retried with Autopilot" messages with autopilot disabled | 0 | papercut | 2/6 Unverified | 0 | — | — |
| 297 | [#311235](https://github.com/microsoft/vscode/issues/311235) | CTRL+I failure. | 0 | none | — | 0 | — | — |
| 298 | [#311406](https://github.com/microsoft/vscode/issues/311406) | wrong | 0 | none | 3/6 Plausible | 0 | — | — |
| 301 | [#312374](https://github.com/microsoft/vscode/issues/312374) | Wbt.clearMarks is not a function | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 302 | [#312637](https://github.com/microsoft/vscode/issues/312637) | QUITTER! | 0 | none | 3/6 Plausible | 0 | — | — |
| 305 | [#315412](https://github.com/microsoft/vscode/issues/315412) | Copilot Chat does not recover from transient outbound failures (host suspend / EAI_AGAIN); silent token refresh leaves UI stuck until   window reload | 0 | correctness | 4/6 Traced | 0 | — | `npm run implement -- --issue 315412` |
| 311 | [#322258](https://github.com/microsoft/vscode/issues/322258) | error message | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 317 | [#326631](https://github.com/microsoft/vscode/issues/326631) | [Error] [GitHub.copilot-chat] unhandlederror-Cannot read properties of undefined (reading 'start') | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 326631` |

### Proxy and certificates (36)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 6 | [#267199](https://github.com/microsoft/vscode/issues/267199) | ERR_HTTP2_PROTOCOL_ERROR | 8 | correctness | 3/6 Plausible | 20 | — | `npm run implement -- --issue 267199` |
| 7 | [#173861](https://github.com/microsoft/vscode/issues/173861) | Proxy agent patch prevents extensions from re-using HTTP connections | 15 | perf | 5/6 Source-confirmed | 16 | — | `npm run implement -- --issue 173861` |
| 12 | [#299324](https://github.com/microsoft/vscode/issues/299324) | Sorry, there was a network error. Please try again later. Request id: 836774d3-2064-4706-8d01-947d2a4d2cd0  Reason: Please check your firewall rules and network connection then try again. Error Code: net::ERR_HTTP2_PROTOCOL_ERROR: [object Object]. | 3 | correctness | — | 10 | — | — |
| 17 | [#187716](https://github.com/microsoft/vscode/issues/187716) | "unable to get local issuer certificate" attempting to install extensions into dev container by code-server on dev container build | 10 | correctness | — | 7 | — | — |
| 18 | [#174279](https://github.com/microsoft/vscode/issues/174279) | All extension network traffic breaks when system proxy settings are changed | 6 | correctness | 5/6 Source-confirmed | 7 | — | `npm run implement -- --issue 174279` |
| 20 | [#278872](https://github.com/microsoft/vscode/issues/278872) | Regression: TLS/remote devcontainer features broken in VS Code 1.106 (works in 1.105) | 0 | correctness | 2/6 Unverified | 7 | — | — |
| 29 | [#94148](https://github.com/microsoft/vscode/issues/94148) | Investigate setting Electron's proxy from user setting | 0 | correctness | 2/6 Unverified | 5 | — | — |
| 30 | [#259467](https://github.com/microsoft/vscode/issues/259467) | MCP code exchange request not going through due to proxy | 0 | correctness | 6/6 Confirmed | 5 | — | `npm run implement -- --issue 259467` |
| 35 | [#131836](https://github.com/microsoft/vscode/issues/131836) | Self-signed certificate error when installing Python support in WSL in spite of custom root certificate correctly installed in WSL | 1 | correctness | 3/6 Plausible | 4 | — | — |
| 39 | [#239872](https://github.com/microsoft/vscode/issues/239872) | Error when installing extensions when using HTTP proxy | 0 | correctness | 5/6 Source-confirmed | 4 | yes | `npm run implement -- --issue 239872` |
| 40 | [#245971](https://github.com/microsoft/vscode/issues/245971) | Can't Use "Publish Branch" Feature When Using SOCKS5 Proxy | 0 | correctness | 5/6 Source-confirmed | 4 | — | — |
| 41 | [#284098](https://github.com/microsoft/vscode/issues/284098) | Error while fetching extensions. Failed to fetch | 0 | correctness | 3/6 Plausible | 4 | — | — |
| 52 | [#247003](https://github.com/microsoft/vscode/issues/247003) | vscode/proxy-agent uses untrusted certificates on macOS | 0 | correctness | 5/6 Source-confirmed | 3 | — | `npm run implement -- --issue 247003` |
| 68 | [#44941](https://github.com/microsoft/vscode/issues/44941) | Proxy parameters are ignored and user-settings are missing a proxy-bypass option | 0 | correctness | 2/6 Unverified | 2 | — | — |
| 69 | [#91183](https://github.com/microsoft/vscode/issues/91183) | Cannot load any extensions in extensions marketplace in visual studio code on imac catalina | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 70 | [#101297](https://github.com/microsoft/vscode/issues/101297) | Stuck while trying to install plugins in WSL using corporate proxy | 0 | correctness | 2/6 Unverified | 2 | — | — |
| 71 | [#112272](https://github.com/microsoft/vscode/issues/112272) | can't connect to extensions marketplace | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 72 | [#167015](https://github.com/microsoft/vscode/issues/167015) | Disabling Proxy support does not disable proxy agent redirection | 0 | correctness | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 167015` |
| 73 | [#196630](https://github.com/microsoft/vscode/issues/196630) | Vscode cannot access extensions marketplace when http.proxy contains user credentials | 0 | correctness | 2/6 Unverified | 2 | — | — |
| 91 | [#81999](https://github.com/microsoft/vscode/issues/81999) | The result of proxyResolver.request is wrong | 2 | correctness | 4/6 Traced | 1 | — | `npm run implement -- --issue 81999` |
| 116 | [#132026](https://github.com/microsoft/vscode/issues/132026) | Cannot connect to the extensions marketplace | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 117 | [#241683](https://github.com/microsoft/vscode/issues/241683) | Failure to use code.cmd --install-extension <valid extension id> behind authenticating proxy server | 0 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 241683` |
| 134 | [#291999](https://github.com/microsoft/vscode/issues/291999) | GitHub Copilot Connection Pool Issue with Forticlient VPN | 0 | none | — | 1 | — | — |
| 138 | [#294835](https://github.com/microsoft/vscode/issues/294835) | 1.109.2 proxy broken | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 146 | [#304247](https://github.com/microsoft/vscode/issues/304247) | Azure sign-in and Cosmos DB connection fail on macOS 26 (Tahoe) with PacProxyAgent crash | 0 | correctness | 2/6 Unverified | 1 | — | — |
| 154 | [#71228](https://github.com/microsoft/vscode/issues/71228) | http.systemCertificates requires window reload | 0 | papercut | 3/6 Plausible | 0 | — | `npm run implement -- --issue 71228` |
| 155 | [#82369](https://github.com/microsoft/vscode/issues/82369) | Extension proxy doe not tunnel https to http | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 158 | [#130172](https://github.com/microsoft/vscode/issues/130172) | Proxy Credentials Popup not showing | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 162 | [#172886](https://github.com/microsoft/vscode/issues/172886) | The Hosts file is not applied in the network proxy. | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 164 | [#185634](https://github.com/microsoft/vscode/issues/185634) | Pass http.proxyAuthorization in extension requests | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 185634` |
| 169 | [#239919](https://github.com/microsoft/vscode/issues/239919) | Unable to log in due to using HTTP proxy | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 239919` |
| 235 | [#295998](https://github.com/microsoft/vscode/issues/295998) | Cannot connect to marketplace | 0 | none | 3/6 Plausible | 0 | — | — |
| 254 | [#299729](https://github.com/microsoft/vscode/issues/299729) | After noProxy is configured, the request fails. | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 307 | [#319745](https://github.com/microsoft/vscode/issues/319745) | VS Code crashes on startup with TypeError when http.noProxy is a string | 0 | crash | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 319745` |
| 316 | [#326185](https://github.com/microsoft/vscode/issues/326185) | http.noProxy config not work for agent host when request BYOK model | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 326185` |
| 318 | [#326765](https://github.com/microsoft/vscode/issues/326765) | High CPU usage (infinite loop) When Incorrect Proxy URL is Set | 0 | perf | 4/6 Traced | 0 | — | `npm run implement -- --issue 326765` |

### Remote Copilot activation (37)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 8 | [#299322](https://github.com/microsoft/vscode/issues/299322) | Copilot 0.38.0 Extension - "Chat failed to load..." error after 1.110 Update | 11 | correctness | 3/6 Plausible | 15 | — | — |
| 9 | [#318711](https://github.com/microsoft/vscode/issues/318711) | Regression in VS Code 1.122.0: Remote Extension Host WebSocket repeatedly disconnects in WSL, breaking all AI extensions (Copilot, Kilo, etc.) | 4 | freeze | 2/6 Unverified | 13 | — | — |
| 10 | [#283560](https://github.com/microsoft/vscode/issues/283560) | "Chat took too long to get ready" - Remote setups (WSL, Dev Containers, Remote SSH) | 3 | correctness | 6/6 Confirmed | 13 | — | `npm run implement -- --issue 283560` |
| 13 | [#299818](https://github.com/microsoft/vscode/issues/299818) | Critical Error 400: Unsupported value 'xhigh' for model 'gpt-5-mini-2025-08-07' (ARM64/WSL) | 5 | correctness | 2/6 Unverified | 9 | — | — |
| 19 | [#282332](https://github.com/microsoft/vscode/issues/282332) | No Copilot Models in Model List - Insiders | 1 | correctness | 2/6 Unverified | 7 | — | — |
| 49 | [#287763](https://github.com/microsoft/vscode/issues/287763) | Github copilot not working for vs code with wsl project | 1 | correctness | 2/6 Unverified | 3 | — | — |
| 54 | [#275480](https://github.com/microsoft/vscode/issues/275480) | Can not enable the copilot chat in the vscode | 0 | correctness | 2/6 Unverified | 3 | — | — |
| 55 | [#279548](https://github.com/microsoft/vscode/issues/279548) | New Copilot BYOK does not allow remote connections | 0 | correctness | 3/6 Plausible | 3 | — | `npm run implement -- --issue 279548` |
| 57 | [#288737](https://github.com/microsoft/vscode/issues/288737) | Endless crashing on ARM Debian | 0 | crash | 3/6 Plausible | 3 | — | — |
| 58 | [#289888](https://github.com/microsoft/vscode/issues/289888) | VSCode.dev: Chat took too long to get ready. Please ensure you are signed in to GitHub and that the extension GitHub.copilot-chat is installed and enabled. | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 59 | [#290127](https://github.com/microsoft/vscode/issues/290127) | Chat took too long to get ready. Please ensure you are signed in to GitHub and that the extension GitHub.copilot-chat is installed and enabled. | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 75 | [#274673](https://github.com/microsoft/vscode/issues/274673) | Copilot Chat does not load/takes very long to load models on remote | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 79 | [#287984](https://github.com/microsoft/vscode/issues/287984) | Chat took too long to get ready | 0 | perf | 3/6 Plausible | 2 | — | — |
| 80 | [#288350](https://github.com/microsoft/vscode/issues/288350) | Chat took too long to get ready | 0 | perf | 3/6 Plausible | 2 | — | `npm run implement -- --issue 288350` |
| 81 | [#288542](https://github.com/microsoft/vscode/issues/288542) | Language model unavailable | 0 | none | 3/6 Plausible | 2 | — | — |
| 82 | [#289551](https://github.com/microsoft/vscode/issues/289551) | Github Copilot fails to "get ready". | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 83 | [#289610](https://github.com/microsoft/vscode/issues/289610) | extension GitHub.copilot-chat is installed and enabled | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 84 | [#291470](https://github.com/microsoft/vscode/issues/291470) | when using [CHAT] for Dev Container, returns "Language model unavailble" | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 88 | [#299689](https://github.com/microsoft/vscode/issues/299689) | High CPU after update: cpptools repeatedly retries LanguageModelProxy model resolution in Remote-WSL extension host | 0 | perf | 5/6 Source-confirmed | 2 | — | `npm run implement -- --issue 299689` |
| 89 | [#316127](https://github.com/microsoft/vscode/issues/316127) | Copilot chat doesn't work over remotes | 0 | correctness | 3/6 Plausible | 2 | — | `npm run implement -- --issue 316127` |
| 122 | [#277268](https://github.com/microsoft/vscode/issues/277268) | GitHub Copilot Chat - False Disabled Status Icon in WSL | 0 | visual | 3/6 Plausible | 1 | — | — |
| 125 | [#285786](https://github.com/microsoft/vscode/issues/285786) | WSL copilot | 0 | correctness | 2/6 Unverified | 1 | — | — |
| 129 | [#288068](https://github.com/microsoft/vscode/issues/288068) | Chat took too long to get ready | 0 | none | 2/6 Unverified | 1 | — | — |
| 130 | [#288205](https://github.com/microsoft/vscode/issues/288205) | copilot doenst work | 0 | none | 3/6 Plausible | 1 | — | — |
| 131 | [#289686](https://github.com/microsoft/vscode/issues/289686) | Chat took too long to get ready | 0 | none | 3/6 Plausible | 1 | — | — |
| 132 | [#289729](https://github.com/microsoft/vscode/issues/289729) | Copilot suddenly stopped working | 0 | none | 3/6 Plausible | 1 | — | — |
| 135 | [#292652](https://github.com/microsoft/vscode/issues/292652) | extension not working | 0 | none | 3/6 Plausible | 1 | — | — |
| 140 | [#298966](https://github.com/microsoft/vscode/issues/298966) | Chat history not visible in Copilot Chat panel after restart (Remote-WSL, v1.109) | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 143 | [#301437](https://github.com/microsoft/vscode/issues/301437) | Always show me "Language model unavailable" | 0 | none | 3/6 Plausible | 1 | — | — |
| 150 | [#320600](https://github.com/microsoft/vscode/issues/320600) | Copilot Chat activation delayed 80-120s in WSL remote due to `onDidChangeSessions` IPC proxy latency | 0 | perf | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 320600` |
| 151 | [#325306](https://github.com/microsoft/vscode/issues/325306) | Chat cannot be activated in SSH. | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 271 | [#302064](https://github.com/microsoft/vscode/issues/302064) | Chat took too long to get ready. Please ensure you are signed in to GitHub and that the extension GitHub.copilot-chat is installed and enabled. Click restart to try again if this issue persists. | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 281 | [#303982](https://github.com/microsoft/vscode/issues/303982) | copilot model thinking level selection not visible in WSL | 0 | papercut | 4/6 Traced | 0 | — | — |
| 287 | [#305978](https://github.com/microsoft/vscode/issues/305978) | can not use copilot in wsl | 0 | none | 3/6 Plausible | 0 | — | — |
| 303 | [#314384](https://github.com/microsoft/vscode/issues/314384) | GitHub Copilot Language model unavailable | 0 | none | — | 0 | — | — |
| 304 | [#314547](https://github.com/microsoft/vscode/issues/314547) | Unable to enumerate GHCP Models | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 314547` |
| 314 | [#325770](https://github.com/microsoft/vscode/issues/325770) | GitHub Copilot Chat reports "Language model unavailable". | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |

### Merge conflict tooling (16)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 14 | [#107821](https://github.com/microsoft/vscode/issues/107821) | Git conflict resolution "accept both changes" deletes lines not related with the conflict | 1 | data-loss | 5/6 Source-confirmed | 9 | yes | `npm run implement -- --issue 107821` |
| 21 | [#137324](https://github.com/microsoft/vscode/issues/137324) | Merge Conflict incorrectly removing conflict markers | 5 | correctness | 5/6 Source-confirmed | 6 | — | — |
| 36 | [#271374](https://github.com/microsoft/vscode/issues/271374) | Code Review: "Illegal value for `line`" error after CCR in SCM | 1 | correctness | 5/6 Source-confirmed | 4 | yes | `npm run implement -- --issue 271374` |
| 45 | [#179872](https://github.com/microsoft/vscode/issues/179872) | "Accept all Current/Incoming" does not work when selecting multiple files (in Source Control Tab) | 5 | correctness | 6/6 Confirmed | 3 | — | `npm run implement -- --issue 179872` |
| 53 | [#252097](https://github.com/microsoft/vscode/issues/252097) | Accept all current/incoming doesn't do anything | 0 | correctness | 3/6 Plausible | 3 | — | `npm run implement -- --issue 252097` |
| 74 | [#257247](https://github.com/microsoft/vscode/issues/257247) | Extended git conflict markers are not handled correctly | 0 | correctness | 5/6 Source-confirmed | 2 | yes | `npm run implement -- --issue 257247` |
| 92 | [#169923](https://github.com/microsoft/vscode/issues/169923) | Merge conflict: save the file when choosing "accept all" | 2 | papercut | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 169923` |
| 94 | [#134370](https://github.com/microsoft/vscode/issues/134370) | Git - Merge Conflict - Accept All Incoming/Current - Multiple Repositories | 1 | correctness | 4/6 Traced | 1 | — | `npm run implement -- --issue 134370` |
| 157 | [#123721](https://github.com/microsoft/vscode/issues/123721) | Git conflict resolution Accept Current Change "ignores" addition of a single empty line | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 123721` |
| 159 | [#130454](https://github.com/microsoft/vscode/issues/130454) | [Bug] `"merge-conflict.diffViewPosition": "Below"` opens multiple diff editors | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 130454` |
| 161 | [#169601](https://github.com/microsoft/vscode/issues/169601) | merge-conflict extension cannot handler '<<<<<<<<' conflict tag | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 169601` |
| 163 | [#184519](https://github.com/microsoft/vscode/issues/184519) | Can't resolve conflict of submodule checksum file | 0 | correctness | 4/6 Traced | 0 | — | `npm run implement -- --issue 184519` |
| 166 | [#194377](https://github.com/microsoft/vscode/issues/194377) | Can not accept current file in Git view | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 167 | [#203580](https://github.com/microsoft/vscode/issues/203580) | No merge conflict codelenses in vscode.dev | 0 | correctness | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 203580` |
| 172 | [#248533](https://github.com/microsoft/vscode/issues/248533) | Accept all incoming or current changes for merge conflicts requires manual file saving and staging and does not work on .bin files | 0 | correctness | 4/6 Traced | 0 | — | — |
| 282 | [#304684](https://github.com/microsoft/vscode/issues/304684) | Generate Commit Message succeeds in DevContainer but does not populate SCM input box | 0 | correctness | 4/6 Traced | 0 | — | `npm run implement -- --issue 304684` |

### Agent tools and paths (23)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 16 | [#293768](https://github.com/microsoft/vscode/issues/293768) | `chat.agentFilesLocations`, `chat.promptFilesLocations`, and `chat.agentSkillsLocations` resolve custom paths on remote host instead of local host during Remote SSH sessions | 2 | correctness | 5/6 Source-confirmed | 8 | yes | `npm run implement -- --issue 293768` |
| 22 | [#303491](https://github.com/microsoft/vscode/issues/303491) | `Chat: Install Plugin From Source` passes a raw Windows path to git when connected via WSL Remote, instead of translating it to a `/mnt/c/...` path. | 1 | correctness | 6/6 Confirmed | 6 | — | — |
| 27 | [#284417](https://github.com/microsoft/vscode/issues/284417) | Copilot attempts writing files in windows format on linux remote host via ssh | 2 | correctness | 4/6 Traced | 5 | — | `npm run implement -- --issue 284417` |
| 28 | [#301167](https://github.com/microsoft/vscode/issues/301167) | chat.pluginLocations: absolute paths and tilde (~/) paths not resolved in Remote WSL | 2 | correctness | 5/6 Source-confirmed | 5 | — | — |
| 44 | [#320500](https://github.com/microsoft/vscode/issues/320500) | Command risk assessment not shown in AHP prompts | 0 | correctness | — | 4 | — | `npm run implement -- --issue 320500` |
| 56 | [#286534](https://github.com/microsoft/vscode/issues/286534) | Chat edits on local machine for a remote workspace | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 64 | [#291143](https://github.com/microsoft/vscode/issues/291143) | Cannot edit file in WSL UI using Agent mode | 1 | correctness | — | 2 | — | — |
| 67 | [#323579](https://github.com/microsoft/vscode/issues/323579) | Sandboxed file read fails on linux (sdk-based) | 1 | correctness | 6/6 Confirmed | 2 | — | `npm run implement -- --issue 323579` |
| 107 | [#304399](https://github.com/microsoft/vscode/issues/304399) | Copilot ripgrep EACCES error | 1 | correctness | 3/6 Plausible | 1 | — | — |
| 127 | [#286268](https://github.com/microsoft/vscode/issues/286268) | "Illegal argument" received when trying to delegate task with @cli | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 139 | [#295667](https://github.com/microsoft/vscode/issues/295667) | Network disruptions cause subagents to hang forever | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 149 | [#317531](https://github.com/microsoft/vscode/issues/317531) | Copilot chat in agent mode doesn't properly detect that a command has finished | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 245 | [#297231](https://github.com/microsoft/vscode/issues/297231) | The copilot extension cannot create a file | 0 | none | 3/6 Plausible | 0 | — | — |
| 253 | [#299236](https://github.com/microsoft/vscode/issues/299236) | Copilot did not add the code it said it added | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 255 | [#299889](https://github.com/microsoft/vscode/issues/299889) | In WSL, Export Chat as Zip default location fails: attempts to write to a Windows-like version of the actual path that doesn't exist | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 299889` |
| 264 | [#301253](https://github.com/microsoft/vscode/issues/301253) | replace_string_in_file / create_file tools fail with "File does not exist" on Remote SSH (NFS UNC paths) | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 274 | [#302547](https://github.com/microsoft/vscode/issues/302547) | When referencing memories in "Plan" mode it sometimes provides a relative path to the file instead of absolute path when working in Codespaces | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 277 | [#303402](https://github.com/microsoft/vscode/issues/303402) | Remote SSH workspace paths are handled locally in Copilot Chat UI mode, causing repeated tool failures and renderer overload | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 303402` |
| 280 | [#303757](https://github.com/microsoft/vscode/issues/303757) | Copilot CLI broken in Remote SSH (Fedora 43 x86_64) due to missing pty.node | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 286 | [#305907](https://github.com/microsoft/vscode/issues/305907) | Claude CLI Error: | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 291 | [#307061](https://github.com/microsoft/vscode/issues/307061) | the cmd line you generated just disappear | 0 | none | 3/6 Plausible | 0 | — | — |
| 296 | [#311165](https://github.com/microsoft/vscode/issues/311165) | Subject: Codex session handling in VS Code is broken and unacceptable | 0 | none | — | 0 | — | — |
| 300 | [#312185](https://github.com/microsoft/vscode/issues/312185) | The files created by the Copilot Agent in remote mode do not exist on file system | 0 | correctness | 3/6 Plausible | 0 | — | — |

### Chat state and UI (20)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 43 | [#302900](https://github.com/microsoft/vscode/issues/302900) | Copilot Chat silently stopped persisting conversation state; full session lost after VS Code crash | 0 | data-loss | 3/6 Plausible | 4 | — | — |
| 46 | [#297843](https://github.com/microsoft/vscode/issues/297843) | Fix "Directory Already Exists" Error When Re-adding a Plugin Marketplace Repository in GitHub Copilot | 3 | correctness | 2/6 Unverified | 3 | — | — |
| 63 | [#318485](https://github.com/microsoft/vscode/issues/318485) | Replying to a past conversation results in "Input item ID does not belong to this connection: | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 87 | [#298835](https://github.com/microsoft/vscode/issues/298835) | chat sessions | 0 | correctness | 2/6 Unverified | 2 | — | — |
| 115 | [#312549](https://github.com/microsoft/vscode/issues/312549) | Linux (Snap) + Copilot Chat cannot type Chinese with IBus (can paste Chinese only) | 1 | correctness | 5/6 Source-confirmed | 1 | yes | `npm run implement -- --issue 312549` |
| 119 | [#255613](https://github.com/microsoft/vscode/issues/255613) | How many times do I have to reject a suggestion before it stops suggesting it in exactly the same place? | 0 | papercut | 3/6 Plausible | 1 | — | `npm run implement -- --issue 255613` |
| 123 | [#281465](https://github.com/microsoft/vscode/issues/281465) | Undoing a next rename suggestion proposes the same rename refactoring | 0 | papercut | 6/6 Confirmed | 1 | — | `npm run implement -- --issue 281465` |
| 128 | [#287240](https://github.com/microsoft/vscode/issues/287240) | VS Code windows glitches, full restart required | 0 | visual | 3/6 Plausible | 1 | — | — |
| 175 | [#272279](https://github.com/microsoft/vscode/issues/272279) | NES proposal on backspacing | 0 | papercut | 6/6 Confirmed | 0 | — | `npm run implement -- --issue 272279` |
| 176 | [#276240](https://github.com/microsoft/vscode/issues/276240) | When Copilot Code Review (CCR) no-ops, there's no notice to user as to why | 0 | papercut | — | 0 | — | `npm run implement -- --issue 276240` |
| 178 | [#283150](https://github.com/microsoft/vscode/issues/283150) | Incorrect Copilot documentation | 0 | papercut | — | 0 | — | `npm run implement -- --issue 283150` |
| 212 | [#290657](https://github.com/microsoft/vscode/issues/290657) | Elicitation does work as expected | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 290657` |
| 223 | [#292892](https://github.com/microsoft/vscode/issues/292892) | Code Review - doesn't well work with Claude | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 292892` |
| 229 | [#293595](https://github.com/microsoft/vscode/issues/293595) | When using Remote SSH, the Claude agent session is not saved. | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 233 | [#295533](https://github.com/microsoft/vscode/issues/295533) | `"chat.editing.explainChanges.enabled": true,` the tooltips still visible after i click on keep button. | 0 | papercut | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 295533` |
| 272 | [#302074](https://github.com/microsoft/vscode/issues/302074) | my chats are visible to another user | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 289 | [#306323](https://github.com/microsoft/vscode/issues/306323) | agent mode chats keep collapsing | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 292 | [#307423](https://github.com/microsoft/vscode/issues/307423) | Chat input box on welcome page gets broken when sidebar is opened | 0 | visual | 3/6 Plausible | 0 | — | — |
| 295 | [#310714](https://github.com/microsoft/vscode/issues/310714) | When updating VSC if one window has an ongoing copilot session only that window is re-opened when VSC restarts after update | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 310714` |
| 310 | [#321821](https://github.com/microsoft/vscode/issues/321821) | [Codespaces] Copilot agent sessions and chat history lost when Codespace resumes from sleep | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 321821` |

### Remote development lifecycle (17)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 34 | [#271012](https://github.com/microsoft/vscode/issues/271012) | Copy and paste does not work between projects opened in dev containers | 2 | correctness | 4/6 Traced | 4 | — | `npm run implement -- --issue 271012` |
| 100 | [#292780](https://github.com/microsoft/vscode/issues/292780) | "Add Dev Container Configuration Files" defaults to an image that does not exist | 1 | correctness | — | 1 | — | — |
| 118 | [#254743](https://github.com/microsoft/vscode/issues/254743) | postCreateCommand is non-interactive on Windows, but interactive on Linux vscode | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 121 | [#277148](https://github.com/microsoft/vscode/issues/277148) | Opening Remote Explorer view opens Docker Desktop | 0 | papercut | 3/6 Plausible | 1 | — | `npm run implement -- --issue 277148` |
| 124 | [#284909](https://github.com/microsoft/vscode/issues/284909) | Unable to open multiple folders within the same container | 0 | none | 3/6 Plausible | 1 | — | — |
| 126 | [#286164](https://github.com/microsoft/vscode/issues/286164) | Remote host extension repeatedly restarting | 0 | none | — | 1 | — | — |
| 145 | [#302071](https://github.com/microsoft/vscode/issues/302071) | Endlessly installing extensions on WSL2 #280336 | 0 | correctness | 3/6 Plausible | 1 | — | `npm run implement -- --issue 302071` |
| 173 | [#259282](https://github.com/microsoft/vscode/issues/259282) | [Dev Containers] Windows SSH Key forward not working | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 259282` |
| 177 | [#277754](https://github.com/microsoft/vscode/issues/277754) | Default worktree location has no write permission in dev container | 0 | correctness | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 277754` |
| 183 | [#284850](https://github.com/microsoft/vscode/issues/284850) | Error when use Dev Containers | 0 | none | — | 0 | — | — |
| 184 | [#284874](https://github.com/microsoft/vscode/issues/284874) | Reconnect issue | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 190 | [#287092](https://github.com/microsoft/vscode/issues/287092) | Debug breakpoints error | 0 | none | — | 0 | — | — |
| 230 | [#293759](https://github.com/microsoft/vscode/issues/293759) | Copilot tools block Python execution in Dev Containers (even though python works) | 0 | none | — | 0 | — | — |
| 275 | [#303210](https://github.com/microsoft/vscode/issues/303210) | Python installation issues | 0 | none | — | 0 | — | — |
| 306 | [#316738](https://github.com/microsoft/vscode/issues/316738) | git-lfs required for vscode repo in devcontainer | 0 | papercut | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 316738` |
| 309 | [#321118](https://github.com/microsoft/vscode/issues/321118) | Dev Containers remain running when using Remote SSH after closing VS Code or using “Close Remote Connection” | 0 | none | — | 0 | — | — |
| 315 | [#325771](https://github.com/microsoft/vscode/issues/325771) | Devcontainer hangs on starting docker desktop | 0 | correctness | 3/6 Plausible | 0 | — | `npm run implement -- --issue 325771` |

### Editor workbench polish (13)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 93 | [#309741](https://github.com/microsoft/vscode/issues/309741) | Can't disable the new experimentalOnboarding welcomePage | 2 | papercut | 2/6 Unverified | 1 | — | — |
| 95 | [#243112](https://github.com/microsoft/vscode/issues/243112) | Code snippet editor has many editor features that are not working | 1 | papercut | 5/6 Source-confirmed | 1 | — | `npm run implement -- --issue 243112` |
| 113 | [#310707](https://github.com/microsoft/vscode/issues/310707) | search highlight barely visible | 1 | visual | 5/6 Source-confirmed | 1 | — | — |
| 114 | [#311092](https://github.com/microsoft/vscode/issues/311092) | Diff viewer rendering breaks on sending a chat message while it is open | 1 | visual | 3/6 Plausible | 1 | — | `npm run implement -- --issue 311092` |
| 153 | [#92312](https://github.com/microsoft/vscode/issues/92312) | Welcome -> Interface Overview Screen - Title Text for the first two features (Search & File explorer) Needs to change/swap | 1 | visual | 2/6 Unverified | 0 | — | — |
| 156 | [#105935](https://github.com/microsoft/vscode/issues/105935) | Interactive playground eats arrow keys | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 160 | [#165222](https://github.com/microsoft/vscode/issues/165222) | Nitpicking: Editor playground is not consistent regarding case for tip blocks | 0 | papercut | 2/6 Unverified | 0 | — | — |
| 165 | [#190278](https://github.com/microsoft/vscode/issues/190278) | Editor Playground | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 168 | [#204719](https://github.com/microsoft/vscode/issues/204719) | Insider release: 'Experimental editor' shows two different color when select the text | 0 | visual | 5/6 Source-confirmed | 0 | yes | `npm run implement -- --issue 204719` |
| 170 | [#242429](https://github.com/microsoft/vscode/issues/242429) | Playground scroll is locked | 0 | correctness | — | 0 | — | — |
| 308 | [#321077](https://github.com/microsoft/vscode/issues/321077) | Hide "Run and Debug" panel title when Activity Bar width is narrow | 0 | visual | 3/6 Plausible | 0 | — | — |
| 312 | [#323257](https://github.com/microsoft/vscode/issues/323257) | iOS-devices are no longer shown/selectable | 0 | none | — | 0 | — | — |
| 313 | [#325000](https://github.com/microsoft/vscode/issues/325000) | Dropping a URL into the editor from Firefox requires holding shift | 0 | papercut | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 325000` |

### Other (25)

| # | Issue | Title | 👍 | Severity | Rating | Score | Auto-fix | Implement |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 31 | [#301679](https://github.com/microsoft/vscode/issues/301679) | Copilot agent terminal commands in VS Code Insiders + WSL intermittently terminate with exit codes 130 / 1 | 0 | correctness | 2/6 Unverified | 5 | — | — |
| 33 | [#312145](https://github.com/microsoft/vscode/issues/312145) | Remote SSH: Copilot/agent plugin discovery fails with PendingMigrationError: navigator is now a global in nodejs on VS Code 1.117.0 | 0 | correctness | 5/6 Source-confirmed | 5 | — | — |
| 47 | [#300513](https://github.com/microsoft/vscode/issues/300513) | CoPilot Chat 0.39.0 is incompatible with latest VSCode 1.111.0 | 3 | none | — | 3 | — | — |
| 50 | [#302367](https://github.com/microsoft/vscode/issues/302367) | Serious issue | 1 | freeze | 3/6 Plausible | 3 | — | — |
| 60 | [#290350](https://github.com/microsoft/vscode/issues/290350) | Chat not possible with GitHub Copilot | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 65 | [#298696](https://github.com/microsoft/vscode/issues/298696) | Lagging & micro-freezing | 1 | perf | 3/6 Plausible | 2 | — | — |
| 66 | [#308639](https://github.com/microsoft/vscode/issues/308639) | Copilot Chat fails on macOS arm64 with Electron fetcher: “Cannot convert argument to a ByteString … char 65279 (U+FEFF)” (regression between 1.110.1 and 1.115.0) | 1 | correctness | 2/6 Unverified | 2 | — | — |
| 85 | [#293448](https://github.com/microsoft/vscode/issues/293448) | Copilot stops before responding | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 86 | [#293449](https://github.com/microsoft/vscode/issues/293449) | Copilot stops before responding | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 106 | [#302955](https://github.com/microsoft/vscode/issues/302955) | Could not delegate to Copilot CLI | 1 | correctness | 3/6 Plausible | 1 | — | — |
| 110 | [#306731](https://github.com/microsoft/vscode/issues/306731) | Cannot find tikTokenizerWorker.js when using @vscode | 1 | correctness | 3/6 Plausible | 1 | — | — |
| 120 | [#275850](https://github.com/microsoft/vscode/issues/275850) | Switching to Insiders or back to stable in codespaces should handle chat extension properly | 0 | correctness | 3/6 Plausible | 1 | — | `npm run implement -- --issue 275850` |
| 133 | [#291341](https://github.com/microsoft/vscode/issues/291341) | Request failed | 0 | none | 3/6 Plausible | 1 | — | — |
| 136 | [#293472](https://github.com/microsoft/vscode/issues/293472) | Gemini X never works | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 137 | [#293604](https://github.com/microsoft/vscode/issues/293604) | too slow and hang | 0 | none | 3/6 Plausible | 1 | — | — |
| 141 | [#299643](https://github.com/microsoft/vscode/issues/299643) | didnt work | 0 | none | 3/6 Plausible | 1 | — | — |
| 142 | [#301098](https://github.com/microsoft/vscode/issues/301098) | When reopening VS Code, recent chat sessions can’t be opened. | 0 | correctness | 6/6 Confirmed | 1 | — | — |
| 171 | [#243482](https://github.com/microsoft/vscode/issues/243482) | Support re-using HTTP connections with `keepAlive` in Proxy agent | 0 | papercut | 5/6 Source-confirmed | 0 | — | `npm run implement -- --issue 243482` |
| 200 | [#288239](https://github.com/microsoft/vscode/issues/288239) | Simultaneous Conflict: GitHub Copilot Modifies Sensitive Files While OS Prompts for Confirmation | 0 | none | 3/6 Plausible | 0 | — | — |
| 201 | [#288308](https://github.com/microsoft/vscode/issues/288308) | Chat took too long to get ready | 0 | none | 3/6 Plausible | 0 | — | — |
| 215 | [#291563](https://github.com/microsoft/vscode/issues/291563) | Chat took too long to get ready | 0 | none | 3/6 Plausible | 0 | — | — |
| 234 | [#295924](https://github.com/microsoft/vscode/issues/295924) | Copilot Chat stuck at "getting chat ready" on Remote SSH with ulimit -v restriction (WASM OOM) | 0 | correctness | 6/6 Confirmed | 0 | — | — |
| 240 | [#296371](https://github.com/microsoft/vscode/issues/296371) | It was just too much for the tool to analyze | 0 | none | 3/6 Plausible | 0 | — | — |
| 270 | [#301846](https://github.com/microsoft/vscode/issues/301846) | The Copilot extension broke my development environment. | 0 | none | 3/6 Plausible | 0 | — | — |
| 283 | [#304942](https://github.com/microsoft/vscode/issues/304942) | Missing commands | 0 | none | 3/6 Plausible | 0 | — | — |

## Feature requests

### Dev containers (13)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | [#236565](https://github.com/microsoft/vscode/issues/236565) | [CLI] code devcontainer as subcommand for code CLI | 115 | backlog-candidate | 100 | `npm run implement -- --issue 236565` |
| 7 | [#287765](https://github.com/microsoft/vscode/issues/287765) | Add security settings to deny dangerous devcontainer configurations | 8 | active | 7 | — |
| 24 | [#285463](https://github.com/microsoft/vscode/issues/285463) | Feature Request: Automatically detect Docker binary in Linuxbrew default path | 2 | dormant | 1 | — |
| 27 | [#305794](https://github.com/microsoft/vscode/issues/305794) | agentPlugins with devcontainer story | 1 | active | 1 | `npm run implement -- --issue 305794` |
| 52 | [#302494](https://github.com/microsoft/vscode/issues/302494) | Import ssh config automatically in devcontainer | 0 | active | 0 | — |
| 56 | [#309561](https://github.com/microsoft/vscode/issues/309561) | Feature Request: Remove/reduce "noisy" devcontainer warnings when updating Docker Desktop | 0 | active | 0 | — |
| 60 | [#317971](https://github.com/microsoft/vscode/issues/317971) | VSCode should allow opening a devcontainer by cloning instead of mounting a local clone | 0 | active | 0 | — |
| 61 | [#319243](https://github.com/microsoft/vscode/issues/319243) | Custom models disappear when opening a Dev Container | 0 | active | 0 | `npm run implement -- --issue 319243` |
| 62 | [#319741](https://github.com/microsoft/vscode/issues/319741) | An easy way to disable credential sharing to dev containers | 0 | active | 0 | — |
| 64 | [#322522](https://github.com/microsoft/vscode/issues/322522) | Clone Repository in Container Volume list previously cloned repositories | 0 | active | 0 | — |
| 66 | [#325616](https://github.com/microsoft/vscode/issues/325616) | Feature request: User-level default Docker volume mounts for Dev Containers | 0 | active | 0 | — |
| 67 | [#325947](https://github.com/microsoft/vscode/issues/325947) | .gitignore_global doesn't work in devcontainers | 0 | active | 0 | — |
| 68 | [#326800](https://github.com/microsoft/vscode/issues/326800) | When using dev containers, copilot uses `~/.copilot` within the container | 0 | active | 0 | — |

### Proxy and certificates (12)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 2 | [#12588](https://github.com/microsoft/vscode/issues/12588) | Extension proxy support | 109 | backlog-candidate | 68 | — |
| 16 | [#185135](https://github.com/microsoft/vscode/issues/185135) | "self signed certificate in certificate chain" while attempting to install an extension via command line | 1 | backlog-candidate | 2 | `npm run implement -- --issue 185135` |
| 19 | [#228696](https://github.com/microsoft/vscode/issues/228696) | Change the global `fetch` available in local extension hosts to be the one from Electron | 0 | backlog-candidate | 2 | `npm run implement -- --issue 228696` |
| 20 | [#96247](https://github.com/microsoft/vscode/issues/96247) | Show notification when certificate verification fails | 4 | backlog-candidate | 1 | `npm run implement -- --issue 96247` |
| 23 | [#200464](https://github.com/microsoft/vscode/issues/200464) | Add bypass proxy setting | 2 | backlog-candidate | 1 | — |
| 28 | [#167852](https://github.com/microsoft/vscode/issues/167852) | Hard coding of Username and password in VS code passthrough Proxy. | 0 | backlog-candidate | 1 | `npm run implement -- --issue 167852` |
| 29 | [#185098](https://github.com/microsoft/vscode/issues/185098) | Add proxy support to `http2` requests in the extension host | 0 | backlog-candidate | 1 | `npm run implement -- --issue 185098` |
| 37 | [#86223](https://github.com/microsoft/vscode/issues/86223) | Proxy configuration doesn't allow URLs with port number AND pac files | 0 | dormant | 0 | — |
| 38 | [#147595](https://github.com/microsoft/vscode/issues/147595) | getSystemProxyURI does not support NO_PROXY env variable | 0 | backlog-candidate | 0 | `npm run implement -- --issue 147595` |
| 40 | [#201192](https://github.com/microsoft/vscode/issues/201192) | Investigate importing CAs from SystemRootCertificates.keychain | 0 | backlog-candidate | 0 | `npm run implement -- --issue 201192` |
| 57 | [#310124](https://github.com/microsoft/vscode/issues/310124) | Extension host proxy support does not cover http2.connect() paths; patched tls.connect still allows direct target DNS/connect instead of proxy tunnel | 0 | backlog-candidate | 0 | — |
| 65 | [#325600](https://github.com/microsoft/vscode/issues/325600) | Third-party extensions cannot configure TLS CA verification — structural disparity with BYOK | 0 | active | 0 | `npm run implement -- --issue 325600` |

### Copilot chat reliability (8)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 3 | [#298406](https://github.com/microsoft/vscode/issues/298406) | Add Remote Control Support to GitHub Copilot Chat | 42 | active | 53 | — |
| 9 | [#307193](https://github.com/microsoft/vscode/issues/307193) | Chat does not sync between different machines | 4 | active | 6 | `npm run implement -- --issue 307193` |
| 12 | [#293784](https://github.com/microsoft/vscode/issues/293784) | auto try again | 2 | active | 3 | — |
| 14 | [#308310](https://github.com/microsoft/vscode/issues/308310) | Support Node Fetch HTTP Cache in Copilot Chat | 0 | active | 3 | `npm run implement -- --issue 308310` |
| 32 | [#288094](https://github.com/microsoft/vscode/issues/288094) | When Copilot Chat Errors, it should RETRY instead of haltung | 0 | dormant | 1 | — |
| 43 | [#288470](https://github.com/microsoft/vscode/issues/288470) | Chat took too long to get ready | 0 | dormant | 0 | — |
| 49 | [#295256](https://github.com/microsoft/vscode/issues/295256) | Power save block on active chat session should have an indicator | 0 | active | 0 | `npm run implement -- --issue 295256` |
| 55 | [#308823](https://github.com/microsoft/vscode/issues/308823) | Copilot Chat: SSE stream inactivity timeout (60s) should be configurable — causing mid-stream failures under backend congestion | 0 | active | 0 | — |

### Git conflict resolution (9)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 4 | [#72976](https://github.com/microsoft/vscode/issues/72976) | Source Control: "Accept All Incoming" for "deleted by them" should delete the file from working copy and stage the change | 27 | dormant | 14 | `npm run implement -- --issue 72976` |
| 11 | [#133088](https://github.com/microsoft/vscode/issues/133088) | merge-conflict: Add compare {current,incoming} to original | 9 | backlog-candidate | 3 | `npm run implement -- --issue 133088` |
| 21 | [#90800](https://github.com/microsoft/vscode/issues/90800) | Key binding condition for "is merging conflicts"? | 2 | dormant | 1 | — |
| 22 | [#102857](https://github.com/microsoft/vscode/issues/102857) | Git - Bulk merge conflict resolving issue on large files | 2 | backlog-candidate | 1 | `npm run implement -- --issue 102857` |
| 25 | [#84620](https://github.com/microsoft/vscode/issues/84620) | Git Merge Resolve Dialog | 1 | dormant | 1 | `npm run implement -- --issue 84620` |
| 26 | [#186091](https://github.com/microsoft/vscode/issues/186091) | auto jump to first conflict when open file from source control panel | 1 | backlog-candidate | 1 | `npm run implement -- --issue 186091` |
| 30 | [#250857](https://github.com/microsoft/vscode/issues/250857) | git merge conflict: if you right click on a file and accept all incoming changes, or accept all current changes, the file should be staged | 0 | dormant | 1 | `npm run implement -- --issue 250857` |
| 35 | [#208492](https://github.com/microsoft/vscode/issues/208492) | git conflicts - highlight for the base for diff3 conflict format | 1 | backlog-candidate | 0 | `npm run implement -- --issue 208492` |
| 39 | [#182839](https://github.com/microsoft/vscode/issues/182839) | editor.action.marker.next ignores Git conflicts | 0 | backlog-candidate | 0 | `npm run implement -- --issue 182839` |

### Remote environments (7)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 5 | [#299383](https://github.com/microsoft/vscode/issues/299383) | Copilot: Support firewalled or airgapped remote machines via SSH | 9 | backlog-candidate | 12 | `npm run implement -- --issue 299383` |
| 8 | [#310166](https://github.com/microsoft/vscode/issues/310166) | Agents app support for remote SSH-like development environments | 5 | active | 7 | — |
| 17 | [#277875](https://github.com/microsoft/vscode/issues/277875) | Disable all extensions on remote | 1 | active | 2 | `npm run implement -- --issue 277875` |
| 18 | [#121805](https://github.com/microsoft/vscode/issues/121805) | "Reopen folder using..." should use a more dedicated ux solution, not notifications | 0 | backlog-candidate | 2 | `npm run implement -- --issue 121805` |
| 33 | [#292758](https://github.com/microsoft/vscode/issues/292758) | Enable copilot in remote not having internet connection. | 0 | active | 1 | — |
| 50 | [#301078](https://github.com/microsoft/vscode/issues/301078) | Include remote execution context in Copilot's <environment_info> | 0 | active | 0 | `npm run implement -- --issue 301078` |
| 54 | [#306021](https://github.com/microsoft/vscode/issues/306021) | Copilot Continue back to Local missing | 0 | active | 0 | `npm run implement -- --issue 306021` |

### Copilot agents (8)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 6 | [#300366](https://github.com/microsoft/vscode/issues/300366) | Add Worktree and Workspace Isolation Modes to GitHub Copilot (Similar to GitHub Copilot CLI) | 11 | active | 9 | `npm run implement -- --issue 300366` |
| 13 | [#300314](https://github.com/microsoft/vscode/issues/300314) | Add Built-in "Review" Agent Mode to GitHub Copilot | 0 | active | 3 | `npm run implement -- --issue 300314` |
| 31 | [#277830](https://github.com/microsoft/vscode/issues/277830) | Adopt `ICompletionsFetchService` for completions | 0 | active | 1 | `npm run implement -- --issue 277830` |
| 44 | [#289694](https://github.com/microsoft/vscode/issues/289694) | Inline Change Explanations | 0 | backlog-candidate | 0 | `npm run implement -- --issue 289694` |
| 48 | [#292597](https://github.com/microsoft/vscode/issues/292597) | Consider removing apply-in-editor | 0 | active | 0 | `npm run implement -- --issue 292597` |
| 51 | [#301903](https://github.com/microsoft/vscode/issues/301903) | Sessions: QoL enhancements | 0 | active | 0 | `npm run implement -- --issue 301903` |
| 59 | [#317131](https://github.com/microsoft/vscode/issues/317131) | Agent app should expose the full Copilot CLI command surface and provide VS Code–level UI depth over it | 0 | active | 0 | `npm run implement -- --issue 317131` |
| 63 | [#320300](https://github.com/microsoft/vscode/issues/320300) | Allow Risk Assessment model calls to route to non-copilot endpoints | 0 | active | 0 | `npm run implement -- --issue 320300` |

### SCM code review (5)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 10 | [#277212](https://github.com/microsoft/vscode/issues/277212) | Code review: Allow reviewing stacked commits and vs base branch | 0 | dormant | 4 | `npm run implement -- --issue 277212` |
| 34 | [#298646](https://github.com/microsoft/vscode/issues/298646) | Customize Code Review Model in Source Control | 0 | active | 1 | — |
| 42 | [#270409](https://github.com/microsoft/vscode/issues/270409) | Git - Initiate code review from commit in graph | 0 | backlog-candidate | 0 | `npm run implement -- --issue 270409` |
| 45 | [#289928](https://github.com/microsoft/vscode/issues/289928) | Feature: Register github.copilot.chat.review.patches command | 0 | active | 0 | — |
| 58 | [#310807](https://github.com/microsoft/vscode/issues/310807) | Feature Request: Allow user prompt files / skills / custom instructions to drive the SCM "Review Changes" button | 0 | active | 0 | — |

### Editor input UX (4)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 15 | [#56759](https://github.com/microsoft/vscode/issues/56759) | Feature Request: Enable valueSelection for InputBox | 8 | backlog-candidate | 2 | — |
| 36 | [#71025](https://github.com/microsoft/vscode/issues/71025) | Enabled Text-Highlighting and Copying in Playground | 0 | dormant | 0 | — |
| 41 | [#207982](https://github.com/microsoft/vscode/issues/207982) | There should be a prompt when clicking on the codelens(command) in the read-only editor | 0 | backlog-candidate | 0 | `npm run implement -- --issue 207982` |
| 53 | [#302736](https://github.com/microsoft/vscode/issues/302736) | Add package metadata hover support for pnpm-workspace.yaml catalog entries | 0 | active | 0 | `npm run implement -- --issue 302736` |

### Workspace mobility (2)

| # | Issue | Title | 👍 | Signal | Score | Implement |
| --- | --- | --- | --- | --- | --- | --- |
| 46 | [#289972](https://github.com/microsoft/vscode/issues/289972) | multi device folders in workspace | 0 | active | 0 | — |
| 47 | [#292049](https://github.com/microsoft/vscode/issues/292049) | There is no android or ios application to install VS Code - Tauri | 0 | active | 0 | — |
