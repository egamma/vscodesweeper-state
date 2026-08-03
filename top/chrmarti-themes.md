# Top issues by theme — chrmarti

Experimental themed view of [the flat ranking](chrmarti.md); themes assigned by the review engine. Rank/score are the lane-wide values. Generated 2026-08-03 15:26 UTC.

## Bugs

### Proxy and certificates (47)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | [#34385](https://github.com/microsoft/vscode/issues/34385) | XHR Failed on trying to install plugins via Visual Studio code | 108 | correctness | 3/6 Plausible | 100 | — | — |
| 6 | [#267199](https://github.com/microsoft/vscode/issues/267199) | ERR_HTTP2_PROTOCOL_ERROR | 8 | correctness | 6/6 Confirmed | 20 | — | — |
| 7 | [#173861](https://github.com/microsoft/vscode/issues/173861) | Proxy agent patch prevents extensions from re-using HTTP connections | 15 | perf | 5/6 Source-confirmed | 15 | — | — |
| 11 | [#299324](https://github.com/microsoft/vscode/issues/299324) | Sorry, there was a network error. Please try again later. Request id: 836774d3-2064-4706-8d01-947d2a4d2cd0  Reason: Please check your firewall rules and network connection then try again. Error Code: net::ERR_HTTP2_PROTOCOL_ERROR: [object Object]. | 3 | correctness | 3/6 Plausible | 10 | — | — |
| 19 | [#187716](https://github.com/microsoft/vscode/issues/187716) | "unable to get local issuer certificate" attempting to install extensions into dev container by code-server on dev container build | 10 | correctness | 3/6 Plausible | 7 | — | — |
| 20 | [#174279](https://github.com/microsoft/vscode/issues/174279) | All extension network traffic breaks when system proxy settings are changed | 6 | correctness | 5/6 Source-confirmed | 7 | — | — |
| 24 | [#131836](https://github.com/microsoft/vscode/issues/131836) | Self-signed certificate error when installing Python support in WSL in spite of custom root certificate correctly installed in WSL | 1 | correctness | 3/6 Plausible | 6 | — | — |
| 32 | [#94148](https://github.com/microsoft/vscode/issues/94148) | Investigate setting Electron's proxy from user setting | 0 | correctness | 2/6 Unverified | 5 | — | — |
| 33 | [#259467](https://github.com/microsoft/vscode/issues/259467) | MCP code exchange request not going through due to proxy | 0 | correctness | 3/6 Plausible | 5 | — | — |
| 34 | [#278872](https://github.com/microsoft/vscode/issues/278872) | Regression: TLS/remote devcontainer features broken in VS Code 1.106 (works in 1.105) | 0 | correctness | 3/6 Plausible | 5 | — | — |
| 40 | [#239872](https://github.com/microsoft/vscode/issues/239872) | Error when installing extensions when using HTTP proxy | 0 | correctness | 4/6 Traced | 4 | yes | — |
| 41 | [#245971](https://github.com/microsoft/vscode/issues/245971) | Can't Use "Publish Branch" Feature When Using SOCKS5 Proxy | 0 | correctness | 5/6 Source-confirmed | 4 | — | — |
| 56 | [#247003](https://github.com/microsoft/vscode/issues/247003) | vscode/proxy-agent uses untrusted certificates on macOS | 0 | correctness | 5/6 Source-confirmed | 3 | — | — |
| 75 | [#44941](https://github.com/microsoft/vscode/issues/44941) | Proxy parameters are ignored and user-settings are missing a proxy-bypass option | 0 | correctness | 2/6 Unverified | 2 | — | — |
| 77 | [#101297](https://github.com/microsoft/vscode/issues/101297) | Stuck while trying to install plugins in WSL using corporate proxy | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 78 | [#112272](https://github.com/microsoft/vscode/issues/112272) | can't connect to extensions marketplace | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 79 | [#167015](https://github.com/microsoft/vscode/issues/167015) | Disabling Proxy support does not disable proxy agent redirection | 0 | correctness | 5/6 Source-confirmed | 2 | yes | — |
| 80 | [#196630](https://github.com/microsoft/vscode/issues/196630) | Vscode cannot access extensions marketplace when http.proxy contains user credentials | 0 | correctness | 2/6 Unverified | 2 | — | — |
| 88 | [#291999](https://github.com/microsoft/vscode/issues/291999) | GitHub Copilot Connection Pool Issue with Forticlient VPN | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 93 | [#81999](https://github.com/microsoft/vscode/issues/81999) | The result of proxyResolver.request is wrong | 2 | correctness | 5/6 Source-confirmed | 1 | — | — |
| 102 | [#305120](https://github.com/microsoft/vscode/issues/305120) | False network error. | 1 | none | 3/6 Plausible | 1 | — | — |
| 110 | [#132026](https://github.com/microsoft/vscode/issues/132026) | Cannot connect to the extensions marketplace | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 111 | [#241683](https://github.com/microsoft/vscode/issues/241683) | Failure to use code.cmd --install-extension <valid extension id> behind authenticating proxy server | 0 | correctness | 5/6 Source-confirmed | 1 | — | — |
| 112 | [#243482](https://github.com/microsoft/vscode/issues/243482) | Support re-using HTTP connections with `keepAlive` in Proxy agent | 0 | perf | 5/6 Source-confirmed | 1 | — | — |
| 115 | [#269210](https://github.com/microsoft/vscode/issues/269210) | ERR_SSL_BAD_RECORD_MAC_ALERT | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 131 | [#294835](https://github.com/microsoft/vscode/issues/294835) | 1.109.2 proxy broken | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 141 | [#304247](https://github.com/microsoft/vscode/issues/304247) | Azure sign-in and Cosmos DB connection fail on macOS 26 (Tahoe) with PacProxyAgent crash | 0 | correctness | 2/6 Unverified | 1 | — | — |
| 151 | [#121224](https://github.com/microsoft/vscode/issues/121224) | Document that http.proxy also configures Electron | 1 | papercut | — | 0 | — | — |
| 154 | [#71228](https://github.com/microsoft/vscode/issues/71228) | http.systemCertificates requires window reload | 0 | papercut | 5/6 Source-confirmed | 0 | — | — |
| 155 | [#82217](https://github.com/microsoft/vscode/issues/82217) | Clarify that proxy settings are only applied to extensions | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 156 | [#82369](https://github.com/microsoft/vscode/issues/82369) | Extension proxy doe not tunnel https to http | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 161 | [#172886](https://github.com/microsoft/vscode/issues/172886) | The Hosts file is not applied in the network proxy. | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 163 | [#185634](https://github.com/microsoft/vscode/issues/185634) | Pass http.proxyAuthorization in extension requests | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 168 | [#239919](https://github.com/microsoft/vscode/issues/239919) | Unable to log in due to using HTTP proxy | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 197 | [#288406](https://github.com/microsoft/vscode/issues/288406) | Sorry, there was a network error. Please try again later. | 0 | papercut | 2/6 Unverified | 0 | — | — |
| 220 | [#292897](https://github.com/microsoft/vscode/issues/292897) | [object Object] in network error message | 0 | papercut | 2/6 Unverified | 0 | — | — |
| 229 | [#295424](https://github.com/microsoft/vscode/issues/295424) | Error Code: net::ERR_CONNECTION_CLOSED | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 233 | [#296016](https://github.com/microsoft/vscode/issues/296016) | net::ERR_CONNECTION_TIMED_OUT: [object Object]. | 0 | papercut | 2/6 Unverified | 0 | — | — |
| 240 | [#298162](https://github.com/microsoft/vscode/issues/298162) | 网络错误 | 0 | none | 3/6 Plausible | 0 | — | — |
| 241 | [#298398](https://github.com/microsoft/vscode/issues/298398) | 网络错误，但是没有出现重试按钮。 | 0 | none | 3/6 Plausible | 0 | — | — |
| 245 | [#299729](https://github.com/microsoft/vscode/issues/299729) | After noProxy is configured, the request fails. | 0 | correctness | 4/6 Traced | 0 | — | — |
| 249 | [#300010](https://github.com/microsoft/vscode/issues/300010) | Connection Reset: [object Object] when making large diffs | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 283 | [#312574](https://github.com/microsoft/vscode/issues/312574) | proxy not connect | 0 | none | — | 0 | — | — |
| 284 | [#314337](https://github.com/microsoft/vscode/issues/314337) | Sorry, there was a network error. Please try again later. Request id: 0764d44e-fc46-42d5-88ed-f96fb7f5e4ce  Reason: Please check your firewall rules and network connection then try again. Error Code: net::ERR_SSL_PROTOCOL_ERROR. | 0 | none | 3/6 Plausible | 0 | — | — |
| 287 | [#319745](https://github.com/microsoft/vscode/issues/319745) | VS Code crashes on startup with TypeError when http.noProxy is a string | 0 | crash | 5/6 Source-confirmed | 0 | yes | — |
| 296 | [#326185](https://github.com/microsoft/vscode/issues/326185) | http.noProxy config not work for agent host when request BYOK model | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 298 | [#326765](https://github.com/microsoft/vscode/issues/326765) | High CPU usage (infinite loop) When Incorrect Proxy URL is Set | 0 | perf | 3/6 Plausible | 0 | — | — |

### Remote workspaces (49)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2 | [#312925](https://github.com/microsoft/vscode/issues/312925) | VS Code crashes (code 5) with Remote SSH + Copilot Chat codebase indexing on M1 | 9 | crash | 3/6 Plausible | 30 | — | — |
| 3 | [#312110](https://github.com/microsoft/vscode/issues/312110) | PendingMigrationError: navigator is now a global in nodejs thrown during module load on remote VS Code server,   causing repeated renderer crashes and Remote SSH disconnections | 3 | crash | 5/6 Source-confirmed | 29 | — | — |
| 9 | [#283560](https://github.com/microsoft/vscode/issues/283560) | "Chat took too long to get ready" - Remote setups (WSL, Dev Containers, Remote SSH) | 3 | correctness | 6/6 Confirmed | 13 | — | — |
| 12 | [#301167](https://github.com/microsoft/vscode/issues/301167) | chat.pluginLocations: absolute paths and tilde (~/) paths not resolved in Remote WSL | 3 | correctness | 5/6 Source-confirmed | 10 | — | — |
| 13 | [#299818](https://github.com/microsoft/vscode/issues/299818) | Critical Error 400: Unsupported value 'xhigh' for model 'gpt-5-mini-2025-08-07' (ARM64/WSL) | 5 | correctness | 4/6 Traced | 9 | — | — |
| 15 | [#300855](https://github.com/microsoft/vscode/issues/300855) | Failed to load native module: pty.node | 4 | correctness | 2/6 Unverified | 8 | — | — |
| 16 | [#318711](https://github.com/microsoft/vscode/issues/318711) | Regression in VS Code 1.122.0: Remote Extension Host WebSocket repeatedly disconnects in WSL, breaking all AI extensions (Copilot, Kilo, etc.) | 4 | freeze | 3/6 Plausible | 8 | — | — |
| 18 | [#293768](https://github.com/microsoft/vscode/issues/293768) | `chat.agentFilesLocations`, `chat.promptFilesLocations`, and `chat.agentSkillsLocations` resolve custom paths on remote host instead of local host during Remote SSH sessions | 2 | correctness | 5/6 Source-confirmed | 8 | yes | — |
| 30 | [#284417](https://github.com/microsoft/vscode/issues/284417) | Copilot attempts writing files in windows format on linux remote host via ssh | 2 | correctness | 5/6 Source-confirmed | 5 | yes | — |
| 35 | [#311227](https://github.com/microsoft/vscode/issues/311227) | Remote window crashes with code 4 on reopen; PTY restore fails and Copilot Chat throws `PendingMigrationError` | 0 | crash | 3/6 Plausible | 5 | — | — |
| 36 | [#312145](https://github.com/microsoft/vscode/issues/312145) | Remote SSH: Copilot/agent plugin discovery fails with PendingMigrationError: navigator is now a global in nodejs on VS Code 1.117.0 | 0 | correctness | 3/6 Plausible | 5 | — | — |
| 37 | [#271012](https://github.com/microsoft/vscode/issues/271012) | Copy and paste does not work between projects opened in dev containers | 2 | correctness | 5/6 Source-confirmed | 4 | — | — |
| 44 | [#286164](https://github.com/microsoft/vscode/issues/286164) | Remote host extension repeatedly restarting | 0 | crash | 3/6 Plausible | 4 | — | — |
| 49 | [#316127](https://github.com/microsoft/vscode/issues/316127) | Copilot chat doesn't work over remotes | 0 | correctness | 3/6 Plausible | 4 | — | — |
| 53 | [#287763](https://github.com/microsoft/vscode/issues/287763) | Github copilot not working for vs code with wsl project | 1 | correctness | 2/6 Unverified | 3 | — | — |
| 61 | [#286534](https://github.com/microsoft/vscode/issues/286534) | Chat edits on local machine for a remote workspace | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 68 | [#291143](https://github.com/microsoft/vscode/issues/291143) | Cannot edit file in WSL UI using Agent mode | 1 | correctness | 3/6 Plausible | 2 | — | — |
| 69 | [#292780](https://github.com/microsoft/vscode/issues/292780) | "Add Dev Container Configuration Files" defaults to an image that does not exist | 1 | correctness | — | 2 | — | — |
| 74 | [#323579](https://github.com/microsoft/vscode/issues/323579) | Sandboxed file read fails on linux (sdk-based) | 1 | correctness | 3/6 Plausible | 2 | — | — |
| 82 | [#279341](https://github.com/microsoft/vscode/issues/279341) | [error] TypeError: The "readableStream" argument must be an instance of ReadableStream. Received an instance of ReadableStream | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 83 | [#284909](https://github.com/microsoft/vscode/issues/284909) | Unable to open multiple folders within the same container | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 87 | [#291470](https://github.com/microsoft/vscode/issues/291470) | when using [CHAT] for Dev Container, returns "Language model unavailble" | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 91 | [#299689](https://github.com/microsoft/vscode/issues/299689) | High CPU after update: cpptools repeatedly retries LanguageModelProxy model resolution in Remote-WSL extension host | 0 | perf | 2/6 Unverified | 2 | — | — |
| 100 | [#300705](https://github.com/microsoft/vscode/issues/300705) | Remote Index Unavailable | 1 | none | 3/6 Plausible | 1 | — | — |
| 117 | [#277148](https://github.com/microsoft/vscode/issues/277148) | Opening Remote Explorer view opens Docker Desktop | 0 | papercut | 3/6 Plausible | 1 | — | — |
| 133 | [#298966](https://github.com/microsoft/vscode/issues/298966) | Chat history not visible in Copilot Chat panel after restart (Remote-WSL, v1.109) | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 139 | [#302071](https://github.com/microsoft/vscode/issues/302071) | Endlessly installing extensions on WSL2 #280336 | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 140 | [#303477](https://github.com/microsoft/vscode/issues/303477) | Cannot find module '/home/cdsw/.vscode-server/extensions/github.copilot-chat-0.39.2/dist/tikTokenizerWorker.js' | 0 | correctness | 2/6 Unverified | 1 | — | — |
| 145 | [#320600](https://github.com/microsoft/vscode/issues/320600) | Copilot Chat activation delayed 80-120s in WSL remote due to `onDidChangeSessions` IPC proxy latency | 0 | perf | 4/6 Traced | 1 | — | — |
| 146 | [#325306](https://github.com/microsoft/vscode/issues/325306) | Chat cannot be activated in SSH. | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 171 | [#254743](https://github.com/microsoft/vscode/issues/254743) | postCreateCommand is non-interactive on Windows, but interactive on Linux vscode | 0 | none | 3/6 Plausible | 0 | — | — |
| 172 | [#259282](https://github.com/microsoft/vscode/issues/259282) | [Dev Containers] Windows SSH Key forward not working | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 175 | [#277754](https://github.com/microsoft/vscode/issues/277754) | Default worktree location has no write permission in dev container | 0 | correctness | 6/6 Confirmed | 0 | — | — |
| 179 | [#284850](https://github.com/microsoft/vscode/issues/284850) | Error when use Dev Containers | 0 | freeze | — | 0 | — | — |
| 180 | [#284874](https://github.com/microsoft/vscode/issues/284874) | Reconnect issue | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 182 | [#285786](https://github.com/microsoft/vscode/issues/285786) | WSL copilot | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 225 | [#293595](https://github.com/microsoft/vscode/issues/293595) | When using Remote SSH, the Claude agent session is not saved. | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 231 | [#295924](https://github.com/microsoft/vscode/issues/295924) | Copilot Chat stuck at "getting chat ready" on Remote SSH with ulimit -v restriction (WASM OOM) | 0 | correctness | 6/6 Confirmed | 0 | — | — |
| 246 | [#299889](https://github.com/microsoft/vscode/issues/299889) | In WSL, Export Chat as Zip default location fails: attempts to write to a Windows-like version of the actual path that doesn't exist | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 261 | [#302547](https://github.com/microsoft/vscode/issues/302547) | When referencing memories in "Plan" mode it sometimes provides a relative path to the file instead of absolute path when working in Codespaces | 0 | papercut | 4/6 Traced | 0 | — | — |
| 263 | [#303402](https://github.com/microsoft/vscode/issues/303402) | Remote SSH workspace paths are handled locally in Copilot Chat UI mode, causing repeated tool failures and renderer overload | 0 | correctness | 6/6 Confirmed | 0 | — | — |
| 264 | [#303739](https://github.com/microsoft/vscode/issues/303739) | Copilot crashes on CNB.cool docker workspaces | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 265 | [#303757](https://github.com/microsoft/vscode/issues/303757) | Copilot CLI broken in Remote SSH (Fedora 43 x86_64) due to missing pty.node | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 281 | [#312185](https://github.com/microsoft/vscode/issues/312185) | The files created by the Copilot Agent in remote mode do not exist on file system | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 289 | [#321118](https://github.com/microsoft/vscode/issues/321118) | Dev Containers remain running when using Remote SSH after closing VS Code or using “Close Remote Connection” | 0 | correctness | — | 0 | — | — |
| 290 | [#321821](https://github.com/microsoft/vscode/issues/321821) | [Codespaces] Copilot agent sessions and chat history lost when Codespace resumes from sleep | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 295 | [#325771](https://github.com/microsoft/vscode/issues/325771) | Devcontainer hangs on starting docker desktop | 0 | correctness | — | 0 | — | — |
| 299 | [#326800](https://github.com/microsoft/vscode/issues/326800) | When using dev containers, copilot uses `~/.copilot` within the container | 0 | correctness | 4/6 Traced | 0 | — | — |
| 300 | [#328295](https://github.com/microsoft/vscode/issues/328295) | Detached Agents window does not expose MCP servers from Remote (WSL) extension host | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |

### Performance and crashes (20)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 4 | [#300132](https://github.com/microsoft/vscode/issues/300132) | The rg process uses a huge amount of CPU. | 8 | perf | 5/6 Source-confirmed | 24 | — | — |
| 10 | [#298401](https://github.com/microsoft/vscode/issues/298401) | After updating to the latest version of VS Code, the coding process has become extremely laggy, and memory usage spikes dramatically. | 7 | perf | 2/6 Unverified | 10 | — | — |
| 26 | [#311239](https://github.com/microsoft/vscode/issues/311239) | GitHub copilot Chat makes a helper renderer eating memory all the way up till crash | 1 | crash | 6/6 Confirmed | 6 | — | — |
| 55 | [#313208](https://github.com/microsoft/vscode/issues/313208) | crash and oom | 1 | crash | 3/6 Plausible | 3 | — | — |
| 63 | [#288737](https://github.com/microsoft/vscode/issues/288737) | Endless crashing on ARM Debian | 0 | crash | 3/6 Plausible | 3 | — | — |
| 70 | [#298696](https://github.com/microsoft/vscode/issues/298696) | Lagging & micro-freezing | 1 | perf | 3/6 Plausible | 2 | — | — |
| 99 | [#296452](https://github.com/microsoft/vscode/issues/296452) | VS code UI slows down when Copilot generates code | 1 | perf | 3/6 Plausible | 1 | — | — |
| 114 | [#269004](https://github.com/microsoft/vscode/issues/269004) | Maximum call stack size exceeded | 0 | none | 3/6 Plausible | 1 | — | — |
| 122 | [#287240](https://github.com/microsoft/vscode/issues/287240) | VS Code windows glitches, full restart required | 0 | visual | 3/6 Plausible | 1 | — | — |
| 138 | [#301851](https://github.com/microsoft/vscode/issues/301851) | TypeScript hangs and crashes trying to parse JavaScript files | 0 | perf | 3/6 Plausible | 1 | — | — |
| 147 | [#327309](https://github.com/microsoft/vscode/issues/327309) | 1.130 version extension host crash in Arch Linux | 0 | crash | 3/6 Plausible | 1 | — | — |
| 235 | [#296109](https://github.com/microsoft/vscode/issues/296109) | Claude Code Crashes & VS Code Crashes Requiring restart | 0 | crash | 3/6 Plausible | 0 | — | — |
| 248 | [#299957](https://github.com/microsoft/vscode/issues/299957) | Critical performance issues with Copilot Chat – Credits wasted due to freezing | 0 | freeze | 3/6 Plausible | 0 | — | — |
| 250 | [#300056](https://github.com/microsoft/vscode/issues/300056) | Unusably slow | 0 | none | 3/6 Plausible | 0 | — | — |
| 251 | [#300112](https://github.com/microsoft/vscode/issues/300112) | New version took a long time to load when asking via Copilot | 0 | freeze | 3/6 Plausible | 0 | — | — |
| 258 | [#301751](https://github.com/microsoft/vscode/issues/301751) | latest mandatory update march 14 regressed when many files are open | 0 | none | 3/6 Plausible | 0 | — | — |
| 262 | [#303371](https://github.com/microsoft/vscode/issues/303371) | Regression: Extension Host (Code 6) crash on macOS after updating to 26.4 | 0 | crash | 5/6 Source-confirmed | 0 | — | — |
| 273 | [#306659](https://github.com/microsoft/vscode/issues/306659) | Copilot performance degraded significantly. | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 277 | [#310714](https://github.com/microsoft/vscode/issues/310714) | When updating VSC if one window has an ongoing copilot session only that window is re-opened when VSC restarts after update | 0 | correctness | 4/6 Traced | 0 | — | — |
| 292 | [#324760](https://github.com/microsoft/vscode/issues/324760) | Extension host terminated unexpectedly 3 times within the last 5 minutes. | 0 | crash | 3/6 Plausible | 0 | — | — |

### Copilot chat readiness (111)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 5 | [#292795](https://github.com/microsoft/vscode/issues/292795) | "Invalid String Length" in Copilot Chat | 10 | correctness | 2/6 Unverified | 21 | — | — |
| 8 | [#299322](https://github.com/microsoft/vscode/issues/299322) | Copilot 0.38.0 Extension - "Chat failed to load..." error after 1.110 Update | 11 | correctness | 3/6 Plausible | 15 | — | — |
| 17 | [#293540](https://github.com/microsoft/vscode/issues/293540) | Claude Opus 4.6 "Sorry, no reponse was returned" | 3 | correctness | — | 8 | — | — |
| 23 | [#300513](https://github.com/microsoft/vscode/issues/300513) | CoPilot Chat 0.39.0 is incompatible with latest VSCode 1.111.0 | 3 | correctness | 3/6 Plausible | 6 | — | — |
| 25 | [#282332](https://github.com/microsoft/vscode/issues/282332) | No Copilot Models in Model List - Insiders | 1 | correctness | 2/6 Unverified | 6 | — | — |
| 28 | [#299513](https://github.com/microsoft/vscode/issues/299513) | issue with claude code in github copilot | 4 | correctness | 5/6 Source-confirmed | 5 | yes | — |
| 45 | [#288542](https://github.com/microsoft/vscode/issues/288542) | Language model unavailable | 0 | correctness | 3/6 Plausible | 4 | — | — |
| 46 | [#293604](https://github.com/microsoft/vscode/issues/293604) | too slow and hang | 0 | correctness | 3/6 Plausible | 4 | — | — |
| 47 | [#294693](https://github.com/microsoft/vscode/issues/294693) | Chat took too long to respond error message | 0 | correctness | 3/6 Plausible | 4 | — | — |
| 48 | [#302900](https://github.com/microsoft/vscode/issues/302900) | Copilot Chat silently stopped persisting conversation state; full session lost after VS Code crash | 0 | data-loss | 3/6 Plausible | 4 | — | — |
| 58 | [#274673](https://github.com/microsoft/vscode/issues/274673) | Copilot Chat does not load/takes very long to load models on remote | 0 | perf | 4/6 Traced | 3 | yes | — |
| 59 | [#275480](https://github.com/microsoft/vscode/issues/275480) | Can not enable the copilot chat in the vscode | 0 | correctness | 2/6 Unverified | 3 | — | — |
| 62 | [#288350](https://github.com/microsoft/vscode/issues/288350) | Chat took too long to get ready | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 64 | [#289551](https://github.com/microsoft/vscode/issues/289551) | Github Copilot fails to "get ready". | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 65 | [#290350](https://github.com/microsoft/vscode/issues/290350) | Chat not possible with GitHub Copilot | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 66 | [#318485](https://github.com/microsoft/vscode/issues/318485) | Replying to a past conversation results in "Input item ID does not belong to this connection: | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 67 | [#287567](https://github.com/microsoft/vscode/issues/287567) | Github copilot chat not working | 1 | none | 3/6 Plausible | 2 | — | — |
| 71 | [#298811](https://github.com/microsoft/vscode/issues/298811) | Chat took too long to get ready. | 1 | correctness | 3/6 Plausible | 2 | — | — |
| 73 | [#307086](https://github.com/microsoft/vscode/issues/307086) | Request Failed: 400 | 1 | correctness | 2/6 Unverified | 2 | — | — |
| 84 | [#285115](https://github.com/microsoft/vscode/issues/285115) | Copilot Freezing on "working..." | 0 | none | 3/6 Plausible | 2 | — | — |
| 85 | [#289686](https://github.com/microsoft/vscode/issues/289686) | Chat took too long to get ready | 0 | perf | 3/6 Plausible | 2 | — | — |
| 86 | [#289888](https://github.com/microsoft/vscode/issues/289888) | VSCode.dev: Chat took too long to get ready. Please ensure you are signed in to GitHub and that the extension GitHub.copilot-chat is installed and enabled. | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 89 | [#293449](https://github.com/microsoft/vscode/issues/293449) | Copilot stops before responding | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 90 | [#298835](https://github.com/microsoft/vscode/issues/298835) | chat sessions | 0 | correctness | 3/6 Plausible | 2 | — | — |
| 97 | [#288380](https://github.com/microsoft/vscode/issues/288380) | Chat took too long to get ready | 1 | perf | 3/6 Plausible | 1 | — | — |
| 98 | [#289029](https://github.com/microsoft/vscode/issues/289029) | A temporary solution to solve "Chat took too long to get ready", and hope this can be fixed. | 1 | correctness | — | 1 | — | — |
| 103 | [#305515](https://github.com/microsoft/vscode/issues/305515) | Copilotの応答が表示されない | 1 | correctness | 3/6 Plausible | 1 | — | — |
| 105 | [#308639](https://github.com/microsoft/vscode/issues/308639) | Copilot Chat fails on macOS arm64 with Electron fetcher: “Cannot convert argument to a ByteString … char 65279 (U+FEFF)” (regression between 1.110.1 and 1.115.0) | 1 | correctness | 2/6 Unverified | 1 | — | — |
| 116 | [#275850](https://github.com/microsoft/vscode/issues/275850) | Switching to Insiders or back to stable in codespaces should handle chat extension properly | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 118 | [#277268](https://github.com/microsoft/vscode/issues/277268) | GitHub Copilot Chat - False Disabled Status Icon in WSL | 0 | visual | 3/6 Plausible | 1 | — | — |
| 119 | [#278838](https://github.com/microsoft/vscode/issues/278838) | VSCode Insier + Github Copilot | 0 | correctness | 2/6 Unverified | 1 | — | — |
| 120 | [#283014](https://github.com/microsoft/vscode/issues/283014) | Request timeout after 60000ms | 0 | papercut | 2/6 Unverified | 1 | — | — |
| 123 | [#287984](https://github.com/microsoft/vscode/issues/287984) | Chat took too long to get ready | 0 | papercut | 3/6 Plausible | 1 | — | — |
| 124 | [#288205](https://github.com/microsoft/vscode/issues/288205) | copilot doenst work | 0 | none | 3/6 Plausible | 1 | — | — |
| 125 | [#289729](https://github.com/microsoft/vscode/issues/289729) | Copilot suddenly stopped working | 0 | none | 3/6 Plausible | 1 | — | — |
| 126 | [#290127](https://github.com/microsoft/vscode/issues/290127) | Chat took too long to get ready. Please ensure you are signed in to GitHub and that the extension GitHub.copilot-chat is installed and enabled. | 0 | papercut | 3/6 Plausible | 1 | — | — |
| 127 | [#292033](https://github.com/microsoft/vscode/issues/292033) | Chat took too long to get ready. Please ensure you are signed in to GitHub and that the extension GitHub.copilot-chat is installed and enabled.  always | 0 | none | 3/6 Plausible | 1 | — | — |
| 128 | [#293448](https://github.com/microsoft/vscode/issues/293448) | Copilot stops before responding | 0 | none | 3/6 Plausible | 1 | — | — |
| 129 | [#293472](https://github.com/microsoft/vscode/issues/293472) | Gemini X never works | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 130 | [#293594](https://github.com/microsoft/vscode/issues/293594) | Sorry, your request failed. Please try again.  Copilot Request id: 7be4f12f-ba3e-4ec4-b037-4a5004ae53f5  Reason: Error on conversation request. Check the log for more details. | 0 | none | 3/6 Plausible | 1 | — | — |
| 134 | [#300846](https://github.com/microsoft/vscode/issues/300846) | Claude Opus 4.6 constantly hangs | 0 | none | 3/6 Plausible | 1 | — | — |
| 135 | [#301098](https://github.com/microsoft/vscode/issues/301098) | When reopening VS Code, recent chat sessions can’t be opened. | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 136 | [#301437](https://github.com/microsoft/vscode/issues/301437) | Always show me "Language model unavailable" | 0 | none | — | 1 | — | — |
| 137 | [#301448](https://github.com/microsoft/vscode/issues/301448) | Sorry, no response was returned. | 0 | correctness | — | 1 | — | — |
| 152 | [#287785](https://github.com/microsoft/vscode/issues/287785) | Sorry, your request failed. Please try again. | 1 | papercut | 2/6 Unverified | 0 | — | — |
| 153 | [#288168](https://github.com/microsoft/vscode/issues/288168) | Chat took too long to get ready | 1 | papercut | 3/6 Plausible | 0 | — | — |
| 177 | [#283893](https://github.com/microsoft/vscode/issues/283893) | erver error. Stream terminated | 0 | none | 3/6 Plausible | 0 | — | — |
| 178 | [#284646](https://github.com/microsoft/vscode/issues/284646) | failed to get a response. Please try again message | 0 | none | 3/6 Plausible | 0 | — | — |
| 181 | [#285135](https://github.com/microsoft/vscode/issues/285135) | Poor Analysis | 0 | none | 3/6 Plausible | 0 | — | — |
| 183 | [#286515](https://github.com/microsoft/vscode/issues/286515) | Error on conversation request | 0 | none | 3/6 Plausible | 0 | — | — |
| 184 | [#286874](https://github.com/microsoft/vscode/issues/286874) | Reason: Server error: 500 - Unrecoverable error have to clear context | 0 | correctness | — | 0 | — | — |
| 185 | [#287033](https://github.com/microsoft/vscode/issues/287033) | error 500 | 0 | none | 3/6 Plausible | 0 | — | — |
| 187 | [#287144](https://github.com/microsoft/vscode/issues/287144) | Copilot travado | 0 | none | 3/6 Plausible | 0 | — | — |
| 188 | [#287167](https://github.com/microsoft/vscode/issues/287167) | Sorry, your request failed. Please try again. | 0 | correctness | 2/6 Unverified | 0 | — | — |
| 189 | [#287233](https://github.com/microsoft/vscode/issues/287233) | copilot stop to work after some time | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 190 | [#287628](https://github.com/microsoft/vscode/issues/287628) | Chat took too long to get ready | 0 | papercut | 2/6 Unverified | 0 | — | — |
| 191 | [#287629](https://github.com/microsoft/vscode/issues/287629) | Chat took too long to get ready | 0 | papercut | 2/6 Unverified | 0 | — | — |
| 192 | [#287630](https://github.com/microsoft/vscode/issues/287630) | Chat took too long to get ready | 0 | papercut | 2/6 Unverified | 0 | — | — |
| 193 | [#287760](https://github.com/microsoft/vscode/issues/287760) | Request Timeout | 0 | none | 3/6 Plausible | 0 | — | — |
| 194 | [#287992](https://github.com/microsoft/vscode/issues/287992) | Chat took too long to get ready | 0 | none | 3/6 Plausible | 0 | — | — |
| 196 | [#288308](https://github.com/microsoft/vscode/issues/288308) | Chat took too long to get ready | 0 | none | 3/6 Plausible | 0 | — | — |
| 198 | [#288470](https://github.com/microsoft/vscode/issues/288470) | Chat took too long to get ready | 0 | perf | 3/6 Plausible | 0 | — | — |
| 199 | [#288554](https://github.com/microsoft/vscode/issues/288554) | Chat took too long to get ready | 0 | perf | 3/6 Plausible | 0 | — | — |
| 200 | [#288711](https://github.com/microsoft/vscode/issues/288711) | Chat took too long to get ready | 0 | none | 3/6 Plausible | 0 | — | — |
| 201 | [#288973](https://github.com/microsoft/vscode/issues/288973) | Chat took too long to get ready | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 202 | [#289123](https://github.com/microsoft/vscode/issues/289123) | Copilet takes very long time to respond | 0 | none | 3/6 Plausible | 0 | — | — |
| 203 | [#289303](https://github.com/microsoft/vscode/issues/289303) | request failed invalid json format | 0 | correctness | — | 0 | — | — |
| 204 | [#289418](https://github.com/microsoft/vscode/issues/289418) | Error on conversation request | 0 | none | 3/6 Plausible | 0 | — | — |
| 205 | [#289574](https://github.com/microsoft/vscode/issues/289574) | Not able to initialize chat | 0 | none | 3/6 Plausible | 0 | — | — |
| 206 | [#289796](https://github.com/microsoft/vscode/issues/289796) | Chat took too long to get ready | 0 | none | 3/6 Plausible | 0 | — | — |
| 207 | [#289879](https://github.com/microsoft/vscode/issues/289879) | Chat took too long to get ready | 0 | papercut | 2/6 Unverified | 0 | — | — |
| 208 | [#290030](https://github.com/microsoft/vscode/issues/290030) | Chat took too long to get ready | 0 | none | 3/6 Plausible | 0 | — | — |
| 210 | [#290842](https://github.com/microsoft/vscode/issues/290842) | Chat took too long to get ready | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 211 | [#290923](https://github.com/microsoft/vscode/issues/290923) | Chat took too long to get ready | 0 | none | 3/6 Plausible | 0 | — | — |
| 212 | [#291186](https://github.com/microsoft/vscode/issues/291186) | Won't be able to chat | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 214 | [#291612](https://github.com/microsoft/vscode/issues/291612) | Copilot: tokenization issue | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 215 | [#291675](https://github.com/microsoft/vscode/issues/291675) | Refuse to provide information | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 216 | [#291733](https://github.com/microsoft/vscode/issues/291733) | Prompt keeps failing | 0 | none | 3/6 Plausible | 0 | — | — |
| 217 | [#292039](https://github.com/microsoft/vscode/issues/292039) | error | 0 | none | 3/6 Plausible | 0 | — | — |
| 218 | [#292648](https://github.com/microsoft/vscode/issues/292648) | Constant request failed error. | 0 | none | 3/6 Plausible | 0 | — | — |
| 221 | [#292976](https://github.com/microsoft/vscode/issues/292976) | Chat took too long to get ready | 0 | perf | 3/6 Plausible | 0 | — | — |
| 223 | [#293391](https://github.com/microsoft/vscode/issues/293391) | Not returning an actual response | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 224 | [#293500](https://github.com/microsoft/vscode/issues/293500) | IT's not working | 0 | none | 3/6 Plausible | 0 | — | — |
| 227 | [#294114](https://github.com/microsoft/vscode/issues/294114) | Github copilot non si connette | 0 | none | 3/6 Plausible | 0 | — | — |
| 228 | [#295319](https://github.com/microsoft/vscode/issues/295319) | error chat | 0 | none | 3/6 Plausible | 0 | — | — |
| 234 | [#296020](https://github.com/microsoft/vscode/issues/296020) | Reason: Request Failed: 400 | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 236 | [#296371](https://github.com/microsoft/vscode/issues/296371) | It was just too much for the tool to analyze | 0 | none | 3/6 Plausible | 0 | — | — |
| 237 | [#296605](https://github.com/microsoft/vscode/issues/296605) | Requests failing with Code SIGKILL | 0 | none | 3/6 Plausible | 0 | — | — |
| 238 | [#296834](https://github.com/microsoft/vscode/issues/296834) | Lost server connection. | 0 | none | 3/6 Plausible | 0 | — | — |
| 242 | [#298725](https://github.com/microsoft/vscode/issues/298725) | Github Copilot Chat is not working | 0 | none | 3/6 Plausible | 0 | — | — |
| 243 | [#298847](https://github.com/microsoft/vscode/issues/298847) | Can not load anything | 0 | none | 3/6 Plausible | 0 | — | — |
| 252 | [#300208](https://github.com/microsoft/vscode/issues/300208) | Missing raw chat response stream from websocket | 0 | papercut | 5/6 Source-confirmed | 0 | — | — |
| 254 | [#300666](https://github.com/microsoft/vscode/issues/300666) | sometimes chat is not responding | 0 | none | 3/6 Plausible | 0 | — | — |
| 256 | [#301477](https://github.com/microsoft/vscode/issues/301477) | Never reposnds to any chat! | 0 | none | 3/6 Plausible | 0 | — | — |
| 257 | [#301548](https://github.com/microsoft/vscode/issues/301548) | Chat doesnt answer | 0 | none | 3/6 Plausible | 0 | — | — |
| 259 | [#301846](https://github.com/microsoft/vscode/issues/301846) | The Copilot extension broke my development environment. | 0 | none | 3/6 Plausible | 0 | — | — |
| 267 | [#304942](https://github.com/microsoft/vscode/issues/304942) | Missing commands | 0 | none | 3/6 Plausible | 0 | — | — |
| 268 | [#305783](https://github.com/microsoft/vscode/issues/305783) | Doesnt work | 0 | none | 3/6 Plausible | 0 | — | — |
| 269 | [#305907](https://github.com/microsoft/vscode/issues/305907) | Claude CLI Error: | 0 | none | 3/6 Plausible | 0 | — | — |
| 270 | [#305910](https://github.com/microsoft/vscode/issues/305910) | Error | 0 | none | 3/6 Plausible | 0 | — | — |
| 271 | [#305981](https://github.com/microsoft/vscode/issues/305981) | Connection to AI just ... stopped. | 0 | none | 3/6 Plausible | 0 | — | — |
| 272 | [#306323](https://github.com/microsoft/vscode/issues/306323) | agent mode chats keep collapsing | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 275 | [#308022](https://github.com/microsoft/vscode/issues/308022) | Gettting CopilotToken fails | 0 | papercut | — | 0 | — | — |
| 276 | [#310102](https://github.com/microsoft/vscode/issues/310102) | Getting "Retried with Autopilot" messages with autopilot disabled | 0 | papercut | 2/6 Unverified | 0 | — | — |
| 278 | [#311235](https://github.com/microsoft/vscode/issues/311235) | CTRL+I failure. | 0 | none | 3/6 Plausible | 0 | — | — |
| 279 | [#311406](https://github.com/microsoft/vscode/issues/311406) | wrong | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 282 | [#312374](https://github.com/microsoft/vscode/issues/312374) | Wbt.clearMarks is not a function | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 285 | [#314544](https://github.com/microsoft/vscode/issues/314544) | Severe Latency and Recurring 401 Auth Errors in GitHub Copilot | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 286 | [#315412](https://github.com/microsoft/vscode/issues/315412) | Copilot Chat does not recover from transient outbound failures (host suspend / EAI_AGAIN); silent token refresh leaves UI stuck until   window reload | 0 | correctness | 4/6 Traced | 0 | — | — |
| 294 | [#325770](https://github.com/microsoft/vscode/issues/325770) | GitHub Copilot Chat reports "Language model unavailable". | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 297 | [#326631](https://github.com/microsoft/vscode/issues/326631) | [Error] [GitHub.copilot-chat] unhandlederror-Cannot read properties of undefined (reading 'start') | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |

### Merge conflict SCM (15)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 14 | [#107821](https://github.com/microsoft/vscode/issues/107821) | Git conflict resolution "accept both changes" deletes lines not related with the conflict | 1 | data-loss | 5/6 Source-confirmed | 9 | yes | — |
| 22 | [#137324](https://github.com/microsoft/vscode/issues/137324) | Merge Conflict incorrectly removing conflict markers | 5 | correctness | 5/6 Source-confirmed | 6 | yes | — |
| 51 | [#179872](https://github.com/microsoft/vscode/issues/179872) | "Accept all Current/Incoming" does not work when selecting multiple files (in Source Control Tab) | 5 | correctness | 3/6 Plausible | 3 | — | — |
| 57 | [#252097](https://github.com/microsoft/vscode/issues/252097) | Accept all current/incoming doesn't do anything | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 81 | [#257247](https://github.com/microsoft/vscode/issues/257247) | Extended git conflict markers are not handled correctly | 0 | correctness | 5/6 Source-confirmed | 2 | yes | — |
| 95 | [#134370](https://github.com/microsoft/vscode/issues/134370) | Git - Merge Conflict - Accept All Incoming/Current - Multiple Repositories | 1 | correctness | 5/6 Source-confirmed | 1 | yes | — |
| 109 | [#123721](https://github.com/microsoft/vscode/issues/123721) | Git conflict resolution Accept Current Change "ignores" addition of a single empty line | 0 | correctness | 5/6 Source-confirmed | 1 | yes | — |
| 148 | [#169923](https://github.com/microsoft/vscode/issues/169923) | Merge conflict: save the file when choosing "accept all" | 2 | papercut | 4/6 Traced | 0 | yes | — |
| 158 | [#130454](https://github.com/microsoft/vscode/issues/130454) | [Bug] `"merge-conflict.diffViewPosition": "Below"` opens multiple diff editors | 0 | papercut | 5/6 Source-confirmed | 0 | yes | — |
| 160 | [#169601](https://github.com/microsoft/vscode/issues/169601) | merge-conflict extension cannot handler '<<<<<<<<' conflict tag | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 162 | [#184519](https://github.com/microsoft/vscode/issues/184519) | Can't resolve conflict of submodule checksum file | 0 | correctness | 4/6 Traced | 0 | — | — |
| 165 | [#194377](https://github.com/microsoft/vscode/issues/194377) | Can not accept current file in Git view | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 166 | [#203580](https://github.com/microsoft/vscode/issues/203580) | No merge conflict codelenses in vscode.dev | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 170 | [#248533](https://github.com/microsoft/vscode/issues/248533) | Accept all incoming or current changes for merge conflicts requires manual file saving and staging and does not work on .bin files | 0 | correctness | 5/6 Source-confirmed | 0 | — | — |
| 266 | [#304684](https://github.com/microsoft/vscode/issues/304684) | Generate Commit Message succeeds in DevContainer but does not populate SCM input box | 0 | correctness | 4/6 Traced | 0 | — | — |

### Copilot agent tools (25)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 21 | [#301679](https://github.com/microsoft/vscode/issues/301679) | Copilot agent terminal commands in VS Code Insiders + WSL intermittently terminate with exit codes 130 / 1 | 1 | correctness | 3/6 Plausible | 7 | — | — |
| 27 | [#298592](https://github.com/microsoft/vscode/issues/298592) | Can't open new Codex session | 8 | none | — | 5 | — | — |
| 31 | [#303491](https://github.com/microsoft/vscode/issues/303491) | `Chat: Install Plugin From Source` passes a raw Windows path to git when connected via WSL Remote, instead of translating it to a `/mnt/c/...` path. | 1 | correctness | — | 5 | — | — |
| 38 | [#271374](https://github.com/microsoft/vscode/issues/271374) | Code Review: "Illegal value for `line`" error after CCR in SCM | 1 | correctness | 5/6 Source-confirmed | 4 | yes | — |
| 42 | [#281465](https://github.com/microsoft/vscode/issues/281465) | Undoing a next rename suggestion proposes the same rename refactoring | 0 | correctness | 5/6 Source-confirmed | 4 | — | — |
| 72 | [#302955](https://github.com/microsoft/vscode/issues/302955) | Could not delegate to Copilot CLI | 1 | correctness | 2/6 Unverified | 2 | — | — |
| 92 | [#320500](https://github.com/microsoft/vscode/issues/320500) | Command risk assessment not shown in AHP prompts | 0 | visual | 5/6 Source-confirmed | 2 | — | — |
| 101 | [#304399](https://github.com/microsoft/vscode/issues/304399) | Copilot ripgrep EACCES error | 1 | correctness | 3/6 Plausible | 1 | — | — |
| 113 | [#255613](https://github.com/microsoft/vscode/issues/255613) | How many times do I have to reject a suggestion before it stops suggesting it in exactly the same place? | 0 | papercut | 5/6 Source-confirmed | 1 | — | — |
| 121 | [#286268](https://github.com/microsoft/vscode/issues/286268) | "Illegal argument" received when trying to delegate task with @cli | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 132 | [#295667](https://github.com/microsoft/vscode/issues/295667) | Network disruptions cause subagents to hang forever | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 142 | [#307061](https://github.com/microsoft/vscode/issues/307061) | the cmd line you generated just disappear | 0 | correctness | 2/6 Unverified | 1 | — | — |
| 144 | [#317531](https://github.com/microsoft/vscode/issues/317531) | Copilot chat in agent mode doesn't properly detect that a command has finished | 0 | correctness | 3/6 Plausible | 1 | — | — |
| 173 | [#272279](https://github.com/microsoft/vscode/issues/272279) | NES proposal on backspacing | 0 | papercut | 6/6 Confirmed | 0 | — | — |
| 174 | [#276240](https://github.com/microsoft/vscode/issues/276240) | When Copilot Code Review (CCR) no-ops, there's no notice to user as to why | 0 | papercut | 5/6 Source-confirmed | 0 | yes | — |
| 195 | [#288239](https://github.com/microsoft/vscode/issues/288239) | Simultaneous Conflict: GitHub Copilot Modifies Sensitive Files While OS Prompts for Confirmation | 0 | none | 3/6 Plausible | 0 | — | — |
| 209 | [#290657](https://github.com/microsoft/vscode/issues/290657) | Elicitation does work as expected | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 219 | [#292892](https://github.com/microsoft/vscode/issues/292892) | Code Review - doesn't well work with Claude | 0 | correctness | — | 0 | — | — |
| 222 | [#293061](https://github.com/microsoft/vscode/issues/293061) | Fix Stream Disconnection Error When Using Codex with GitHub Copilot Pro+ Subscription | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 226 | [#293759](https://github.com/microsoft/vscode/issues/293759) | Copilot tools block Python execution in Dev Containers (even though python works) | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 230 | [#295533](https://github.com/microsoft/vscode/issues/295533) | `"chat.editing.explainChanges.enabled": true,` the tooltips still visible after i click on keep button. | 0 | visual | 5/6 Source-confirmed | 0 | yes | — |
| 239 | [#297231](https://github.com/microsoft/vscode/issues/297231) | The copilot extension cannot create a file | 0 | none | 3/6 Plausible | 0 | — | — |
| 244 | [#299236](https://github.com/microsoft/vscode/issues/299236) | Copilot did not add the code it said it added | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 255 | [#301253](https://github.com/microsoft/vscode/issues/301253) | replace_string_in_file / create_file tools fail with "File does not exist" on Remote SSH (NFS UNC paths) | 0 | correctness | 5/6 Source-confirmed | 0 | yes | — |
| 260 | [#302444](https://github.com/microsoft/vscode/issues/302444) | Duplicate File Creation Causes Network Error and Final Failure | 0 | none | 3/6 Plausible | 0 | — | — |

### Editor and onboarding (18)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 29 | [#277300](https://github.com/microsoft/vscode/issues/277300) | Google Authentication stopped working in 1.106 | 2 | correctness | 2/6 Unverified | 5 | — | — |
| 94 | [#309741](https://github.com/microsoft/vscode/issues/309741) | Can't disable the new experimentalOnboarding welcomePage | 2 | papercut | 2/6 Unverified | 1 | — | — |
| 96 | [#243112](https://github.com/microsoft/vscode/issues/243112) | Code snippet editor has many editor features that are not working | 1 | papercut | 4/6 Traced | 1 | — | — |
| 106 | [#310707](https://github.com/microsoft/vscode/issues/310707) | search highlight barely visible | 1 | visual | 3/6 Plausible | 1 | — | — |
| 107 | [#311092](https://github.com/microsoft/vscode/issues/311092) | Diff viewer rendering breaks on sending a chat message while it is open | 1 | visual | 3/6 Plausible | 1 | — | — |
| 108 | [#312549](https://github.com/microsoft/vscode/issues/312549) | Linux (Snap) + Copilot Chat cannot type Chinese with IBus (can paste Chinese only) | 1 | correctness | 5/6 Source-confirmed | 1 | — | — |
| 150 | [#92312](https://github.com/microsoft/vscode/issues/92312) | Welcome -> Interface Overview Screen - Title Text for the first two features (Search & File explorer) Needs to change/swap | 1 | visual | 2/6 Unverified | 0 | — | — |
| 157 | [#105935](https://github.com/microsoft/vscode/issues/105935) | Interactive playground eats arrow keys | 0 | papercut | 4/6 Traced | 0 | yes | — |
| 159 | [#165222](https://github.com/microsoft/vscode/issues/165222) | Nitpicking: Editor playground is not consistent regarding case for tip blocks | 0 | papercut | 2/6 Unverified | 0 | — | — |
| 164 | [#190278](https://github.com/microsoft/vscode/issues/190278) | Editor Playground | 0 | papercut | 3/6 Plausible | 0 | — | — |
| 167 | [#204719](https://github.com/microsoft/vscode/issues/204719) | Insider release: 'Experimental editor' shows two different color when select the text | 0 | visual | 5/6 Source-confirmed | 0 | yes | — |
| 169 | [#242429](https://github.com/microsoft/vscode/issues/242429) | Playground scroll is locked | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 176 | [#283150](https://github.com/microsoft/vscode/issues/283150) | Incorrect Copilot documentation | 0 | none | — | 0 | — | — |
| 186 | [#287092](https://github.com/microsoft/vscode/issues/287092) | Debug breakpoints error | 0 | none | — | 0 | — | — |
| 274 | [#307423](https://github.com/microsoft/vscode/issues/307423) | Chat input box on welcome page gets broken when sidebar is opened | 0 | visual | 3/6 Plausible | 0 | — | — |
| 288 | [#321077](https://github.com/microsoft/vscode/issues/321077) | Hide "Run and Debug" panel title when Activity Bar width is narrow | 0 | visual | 3/6 Plausible | 0 | — | — |
| 291 | [#323257](https://github.com/microsoft/vscode/issues/323257) | iOS-devices are no longer shown/selectable | 0 | none | — | 0 | — | — |
| 293 | [#325000](https://github.com/microsoft/vscode/issues/325000) | Dropping a URL into the editor from Firefox requires holding shift | 0 | papercut | 5/6 Source-confirmed | 0 | — | — |

### Extension marketplace (11)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 39 | [#301087](https://github.com/microsoft/vscode/issues/301087) | Cannot install Copilot Chat extension: "End of central directory record signature not found" (zip/VSIX error) in Codespaces | 1 | correctness | 2/6 Unverified | 4 | — | — |
| 43 | [#284098](https://github.com/microsoft/vscode/issues/284098) | Error while fetching extensions. Failed to fetch | 0 | correctness | 3/6 Plausible | 4 | — | — |
| 50 | [#90900](https://github.com/microsoft/vscode/issues/90900) | Warning in package.json when specifying icon without https repository | 5 | correctness | 3/6 Plausible | 3 | — | — |
| 52 | [#297843](https://github.com/microsoft/vscode/issues/297843) | Fix "Directory Already Exists" Error When Re-adding a Plugin Marketplace Repository in GitHub Copilot | 3 | correctness | 2/6 Unverified | 3 | — | — |
| 76 | [#91183](https://github.com/microsoft/vscode/issues/91183) | Cannot load any extensions in extensions marketplace in visual studio code on imac catalina | 0 | correctness | 2/6 Unverified | 2 | — | — |
| 104 | [#306731](https://github.com/microsoft/vscode/issues/306731) | Cannot find tikTokenizerWorker.js when using @vscode | 1 | correctness | 2/6 Unverified | 1 | — | — |
| 149 | [#60669](https://github.com/microsoft/vscode/issues/60669) | `extensions/extension-editing/src/extensionLinter.ts` does not respect `repository` shorthand in package.json | 1 | papercut | 5/6 Source-confirmed | 0 | — | — |
| 232 | [#295998](https://github.com/microsoft/vscode/issues/295998) | Cannot connect to marketplace | 0 | none | 3/6 Plausible | 0 | — | — |
| 247 | [#299929](https://github.com/microsoft/vscode/issues/299929) | All of a sudden the whole VS code extensions got refreshed on their own. | 0 | correctness | 3/6 Plausible | 0 | — | — |
| 253 | [#300488](https://github.com/microsoft/vscode/issues/300488) | Extension Signature Verification Failed: GitHub Copilot Chat | 0 | none | 3/6 Plausible | 0 | — | — |
| 280 | [#311976](https://github.com/microsoft/vscode/issues/311976) | Unable to activate an extension | 0 | none | 3/6 Plausible | 0 | — | — |

### Other (4)

| # | Issue | Title | 👍 | Severity | Rating | Score | Agent-fixable | Draft PR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 54 | [#302367](https://github.com/microsoft/vscode/issues/302367) | Serious issue | 1 | freeze | 3/6 Plausible | 3 | — | — |
| 60 | [#279548](https://github.com/microsoft/vscode/issues/279548) | New Copilot BYOK does not allow remote connections | 0 | correctness | 3/6 Plausible | 3 | — | — |
| 143 | [#307496](https://github.com/microsoft/vscode/issues/307496) | error | 0 | correctness | 2/6 Unverified | 1 | — | — |
| 213 | [#291562](https://github.com/microsoft/vscode/issues/291562) | Chat took too long to get ready | 0 | papercut | 2/6 Unverified | 0 | — | — |

## Feature requests

### Dev containers (13)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | [#236565](https://github.com/microsoft/vscode/issues/236565) | [CLI] code devcontainer as subcommand for code CLI | 116 | backlog-candidate | 100 | — |
| 7 | [#287765](https://github.com/microsoft/vscode/issues/287765) | Add security settings to deny dangerous devcontainer configurations | 8 | dormant | 9 | — |
| 23 | [#285463](https://github.com/microsoft/vscode/issues/285463) | Feature Request: Automatically detect Docker binary in Linuxbrew default path | 2 | dormant | 1 | — |
| 26 | [#305794](https://github.com/microsoft/vscode/issues/305794) | agentPlugins with devcontainer story | 1 | active | 1 | — |
| 52 | [#302494](https://github.com/microsoft/vscode/issues/302494) | Import ssh config automatically in devcontainer | 0 | active | 0 | — |
| 56 | [#309561](https://github.com/microsoft/vscode/issues/309561) | Feature Request: Remove/reduce "noisy" devcontainer warnings when updating Docker Desktop | 0 | active | 0 | — |
| 60 | [#316738](https://github.com/microsoft/vscode/issues/316738) | git-lfs required for vscode repo in devcontainer | 0 | active | 0 | — |
| 62 | [#317971](https://github.com/microsoft/vscode/issues/317971) | VSCode should allow opening a devcontainer by cloning instead of mounting a local clone | 0 | active | 0 | — |
| 64 | [#319741](https://github.com/microsoft/vscode/issues/319741) | An easy way to disable credential sharing to dev containers | 0 | active | 0 | — |
| 66 | [#322522](https://github.com/microsoft/vscode/issues/322522) | Clone Repository in Container Volume list previously cloned repositories | 0 | active | 0 | — |
| 68 | [#325616](https://github.com/microsoft/vscode/issues/325616) | Feature request: User-level default Docker volume mounts for Dev Containers | 0 | active | 0 | — |
| 69 | [#325947](https://github.com/microsoft/vscode/issues/325947) | .gitignore_global doesn't work in devcontainers | 0 | active | 0 | — |
| 71 | [#328067](https://github.com/microsoft/vscode/issues/328067) | Automatically try open in devcontainer when .devcontainer config is detected | 0 | active | 0 | — |

### Copilot agents (12)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 2 | [#298406](https://github.com/microsoft/vscode/issues/298406) | Add Remote Control Support to GitHub Copilot Chat | 42 | active | 52 | — |
| 4 | [#300366](https://github.com/microsoft/vscode/issues/300366) | Add Worktree and Workspace Isolation Modes to GitHub Copilot (Similar to GitHub Copilot CLI) | 11 | active | 14 | — |
| 12 | [#293784](https://github.com/microsoft/vscode/issues/293784) | auto try again | 2 | active | 3 | — |
| 19 | [#308310](https://github.com/microsoft/vscode/issues/308310) | Support Node Fetch HTTP Cache in Copilot Chat | 0 | active | 2 | — |
| 31 | [#277830](https://github.com/microsoft/vscode/issues/277830) | Adopt `ICompletionsFetchService` for completions | 0 | dormant | 1 | — |
| 32 | [#288094](https://github.com/microsoft/vscode/issues/288094) | When Copilot Chat Errors, it should RETRY instead of haltung | 0 | dormant | 1 | — |
| 49 | [#295256](https://github.com/microsoft/vscode/issues/295256) | Power save block on active chat session should have an indicator | 0 | active | 0 | — |
| 51 | [#301903](https://github.com/microsoft/vscode/issues/301903) | Sessions: QoL enhancements | 0 | active | 0 | — |
| 55 | [#308823](https://github.com/microsoft/vscode/issues/308823) | Copilot Chat: SSE stream inactivity timeout (60s) should be configurable — causing mid-stream failures under backend congestion | 0 | active | 0 | — |
| 59 | [#311165](https://github.com/microsoft/vscode/issues/311165) | Subject: Codex session handling in VS Code is broken and unacceptable | 0 | active | 0 | — |
| 61 | [#317131](https://github.com/microsoft/vscode/issues/317131) | Agent app should expose the full Copilot CLI command surface and provide VS Code–level UI depth over it | 0 | active | 0 | — |
| 65 | [#320300](https://github.com/microsoft/vscode/issues/320300) | Allow Risk Assessment model calls to route to non-copilot endpoints | 0 | active | 0 | — |

### Proxy and certificates (13)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 3 | [#12588](https://github.com/microsoft/vscode/issues/12588) | Extension proxy support | 109 | backlog-candidate | 48 | — |
| 15 | [#96247](https://github.com/microsoft/vscode/issues/96247) | Show notification when certificate verification fails | 4 | backlog-candidate | 2 | — |
| 18 | [#228696](https://github.com/microsoft/vscode/issues/228696) | Change the global `fetch` available in local extension hosts to be the one from Electron | 0 | backlog-candidate | 2 | — |
| 22 | [#200464](https://github.com/microsoft/vscode/issues/200464) | Add bypass proxy setting | 2 | backlog-candidate | 1 | — |
| 25 | [#185135](https://github.com/microsoft/vscode/issues/185135) | "self signed certificate in certificate chain" while attempting to install an extension via command line | 1 | backlog-candidate | 1 | — |
| 28 | [#167852](https://github.com/microsoft/vscode/issues/167852) | Hard coding of Username and password in VS code passthrough Proxy. | 0 | backlog-candidate | 1 | — |
| 29 | [#185098](https://github.com/microsoft/vscode/issues/185098) | Add proxy support to `http2` requests in the extension host | 0 | backlog-candidate | 1 | — |
| 38 | [#86223](https://github.com/microsoft/vscode/issues/86223) | Proxy configuration doesn't allow URLs with port number AND pac files | 0 | dormant | 0 | — |
| 39 | [#130172](https://github.com/microsoft/vscode/issues/130172) | Proxy Credentials Popup not showing | 0 | backlog-candidate | 0 | — |
| 40 | [#147595](https://github.com/microsoft/vscode/issues/147595) | getSystemProxyURI does not support NO_PROXY env variable | 0 | backlog-candidate | 0 | — |
| 42 | [#201192](https://github.com/microsoft/vscode/issues/201192) | Investigate importing CAs from SystemRootCertificates.keychain | 0 | backlog-candidate | 0 | — |
| 57 | [#310124](https://github.com/microsoft/vscode/issues/310124) | Extension host proxy support does not cover http2.connect() paths; patched tls.connect still allows direct target DNS/connect instead of proxy tunnel | 0 | backlog-candidate | 0 | — |
| 67 | [#325600](https://github.com/microsoft/vscode/issues/325600) | Third-party extensions cannot configure TLS CA verification — structural disparity with BYOK | 0 | active | 0 | — |

### Remote connectivity (8)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 5 | [#299383](https://github.com/microsoft/vscode/issues/299383) | Copilot: Support firewalled or airgapped remote machines via SSH | 9 | backlog-candidate | 12 | — |
| 8 | [#310166](https://github.com/microsoft/vscode/issues/310166) | Agents app support for remote SSH-like development environments | 5 | active | 7 | — |
| 16 | [#277875](https://github.com/microsoft/vscode/issues/277875) | Disable all extensions on remote | 1 | active | 2 | — |
| 33 | [#292758](https://github.com/microsoft/vscode/issues/292758) | Enable copilot in remote not having internet connection. | 0 | active | 1 | — |
| 50 | [#301078](https://github.com/microsoft/vscode/issues/301078) | Include remote execution context in Copilot's <environment_info> | 0 | active | 0 | — |
| 54 | [#306021](https://github.com/microsoft/vscode/issues/306021) | Copilot Continue back to Local missing | 0 | active | 0 | — |
| 63 | [#319243](https://github.com/microsoft/vscode/issues/319243) | Custom models disappear when opening a Dev Container | 0 | active | 0 | — |
| 70 | [#327726](https://github.com/microsoft/vscode/issues/327726) | WSL support in GitHub APP | 0 | active | 0 | — |

### Merge conflicts (10)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 6 | [#72976](https://github.com/microsoft/vscode/issues/72976) | Source Control: "Accept All Incoming" for "deleted by them" should delete the file from working copy and stage the change | 27 | dormant | 11 | — |
| 11 | [#133088](https://github.com/microsoft/vscode/issues/133088) | merge-conflict: Add compare {current,incoming} to original | 9 | backlog-candidate | 3 | — |
| 20 | [#90800](https://github.com/microsoft/vscode/issues/90800) | Key binding condition for "is merging conflicts"? | 2 | dormant | 1 | — |
| 21 | [#102857](https://github.com/microsoft/vscode/issues/102857) | Git - Bulk merge conflict resolving issue on large files | 2 | backlog-candidate | 1 | — |
| 24 | [#84620](https://github.com/microsoft/vscode/issues/84620) | Git Merge Resolve Dialog | 1 | dormant | 1 | — |
| 27 | [#133589](https://github.com/microsoft/vscode/issues/133589) | Improve Buttons in SVC Conflict Resolution | 0 | backlog-candidate | 1 | — |
| 30 | [#250857](https://github.com/microsoft/vscode/issues/250857) | git merge conflict: if you right click on a file and accept all incoming changes, or accept all current changes, the file should be staged | 0 | dormant | 1 | — |
| 35 | [#186091](https://github.com/microsoft/vscode/issues/186091) | auto jump to first conflict when open file from source control panel | 1 | backlog-candidate | 0 | — |
| 36 | [#208492](https://github.com/microsoft/vscode/issues/208492) | git conflicts - highlight for the base for diff3 conflict format | 1 | backlog-candidate | 0 | — |
| 41 | [#182839](https://github.com/microsoft/vscode/issues/182839) | editor.action.marker.next ignores Git conflicts | 0 | backlog-candidate | 0 | — |

### Workspace continuity (2)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 9 | [#307193](https://github.com/microsoft/vscode/issues/307193) | Chat does not sync between different machines | 4 | active | 6 | — |
| 47 | [#289972](https://github.com/microsoft/vscode/issues/289972) | multi device folders in workspace | 0 | dormant | 0 | — |

### Code review workflow (7)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 10 | [#277212](https://github.com/microsoft/vscode/issues/277212) | Code review: Allow reviewing stacked commits and vs base branch | 0 | dormant | 4 | — |
| 13 | [#300314](https://github.com/microsoft/vscode/issues/300314) | Add Built-in "Review" Agent Mode to GitHub Copilot | 0 | active | 3 | — |
| 34 | [#298646](https://github.com/microsoft/vscode/issues/298646) | Customize Code Review Model in Source Control | 0 | active | 1 | — |
| 44 | [#270409](https://github.com/microsoft/vscode/issues/270409) | Git - Initiate code review from commit in graph | 0 | backlog-candidate | 0 | — |
| 45 | [#289694](https://github.com/microsoft/vscode/issues/289694) | Inline Change Explanations | 0 | backlog-candidate | 0 | — |
| 46 | [#289928](https://github.com/microsoft/vscode/issues/289928) | Feature: Register github.copilot.chat.review.patches command | 0 | dormant | 0 | — |
| 58 | [#310807](https://github.com/microsoft/vscode/issues/310807) | Feature Request: Allow user prompt files / skills / custom instructions to drive the SCM "Review Changes" button | 0 | active | 0 | — |

### Extension UI APIs (5)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 14 | [#56759](https://github.com/microsoft/vscode/issues/56759) | Feature Request: Enable valueSelection for InputBox | 8 | backlog-candidate | 2 | — |
| 17 | [#121805](https://github.com/microsoft/vscode/issues/121805) | "Reopen folder using..." should use a more dedicated ux solution, not notifications | 0 | backlog-candidate | 2 | — |
| 37 | [#71025](https://github.com/microsoft/vscode/issues/71025) | Enabled Text-Highlighting and Copying in Playground | 0 | dormant | 0 | — |
| 43 | [#207982](https://github.com/microsoft/vscode/issues/207982) | There should be a prompt when clicking on the codelens(command) in the read-only editor | 0 | backlog-candidate | 0 | — |
| 53 | [#302736](https://github.com/microsoft/vscode/issues/302736) | Add package metadata hover support for pnpm-workspace.yaml catalog entries | 0 | active | 0 | — |

### Other (1)

| # | Issue | Title | 👍 | Signal | Score | Draft PR |
| --- | --- | --- | --- | --- | --- | --- |
| 48 | [#292049](https://github.com/microsoft/vscode/issues/292049) | There is no android or ios application to install VS Code - Tauri | 0 | active | 0 | — |
