## .NET Software Developer, TechLead at Deeplay.io.

### What a time to be alive!

#### [@jamminroot (telegram)](https://t.me/jamminroot), [Dmitrii Chichuk (LinkedIn)](https://linkedin.com/in/dchichuk)

Feel free to reach out!

<!-- ACTIVITY-SUMMARY-START -->
## Recent activity (last 12 months)

*Auto-generated weekly from commit history · updated 2026-10-12*

I built and iterated on Summit, a SaaS crypto algo trading platform with AI and neural network components, focusing on wallet group management, LLM-based judge systems for quorum and sentiment, rebalance strategies, and follows features. I also developed j-uni-hid, a feature-rich mouse and keyboard emulation firmware for ESP32-S3, progressing through multiple versions with USB HID, BLE, and performance improvements. Additionally, I created input-driver, a Windows kernel-level input filter driver for capture and injection, with a library API and integration tests.

In parallel, I conducted extensive research on crypto price prediction models in crypto-model-research, building a unified evaluation protocol, drift monitoring, and conformal prediction experiments. I worked on agent-harness, an agentic worker framework in Rust, integrating Mattermost, defining agent schemas, and building a web UI. I also developed sunflower, a browser-in-browser system with container management, human input simulation, and font delivery.

Other projects include j-tts-android, a TTS app with multiple engine support and Russian language features; ozwil-android, an on-device LLM with phone capabilities; poker-cv, a computer vision pipeline for online poker; and intag2, a Windows file tagging utility with metadata writing and UI improvements. I also maintained various automation tools, dotfiles, and CI pipelines.
<!-- ACTIVITY-SUMMARY-END -->

<img src="https://raw.githubusercontent.com/Jamminroot/Jamminroot/master/cards/charts.svg" alt="Activity charts">

<img src="https://raw.githubusercontent.com/Jamminroot/Jamminroot/master/cards/projects.svg" alt="Project cards">

<!-- ACTIVITY-TIMELINE-START -->
> **2026 Oct**
>
> - **Wallet groups and auth improvements** *(summit)* — Built scheduled wallet group resize proposals and extended session persistence; improved scanner performance by skipping already-evaluated lanes.
> - **YOLO labeler updates** *(yolo-labeler)* — Added validator functionality and general updates to the on-host YOLO labeling tool.

> **2026 Sep**
>
> - **LLM judge system and wallet limits** *(summit)* — Implemented System One judge seats for quorum and sentiment, provider capabilities for seat placement, and wallet group limit defaults.
> - **Agentic worker Mattermost integration** *(agent-harness)* — Built Mattermost connector with channel directory, REST API access, and background sync; defined schema for nodes, providers, and agents.
> - **File tagging UI and format support** *(intag2)* — Added user zoom level, window resizing, Matroska and WebP tag writing, and DPI-aware UI scaling.
> - **Browser management and font delivery** *(sunflower)* — Implemented font packs as mounted volumes, browser claiming, proxy password handling, and exit probing for launches.
> - **Labeling tool enhancements** *(yolo-labeler)* — Added label transparency, mosaic view, RMB zoom, and constraint highlighting.

> **2026 Aug**
>
> - **Rebalance and follows features** *(summit)* — Developed calm-liquidity backtest replay, interactive exit simulator, honest cost tracking, and position backfill from candles.
> - **Crypto price model research** *(crypto-model-research)* — Conducted model catalog rebuild, drift monitoring, conformal prediction experiments, and Summit validation report response.
> - **Agent architecture and UI development** *(agent-harness)* — Built agent memory, notification system, workspace editing, admin page, and preset-first web UI with hybrid memory.
> - **Settings persistence and Explorer integration** *(intag2)* — Fixed settings persistence, Explorer refresh, and backdrop fallback; improved metadata write error handling.
> - **Deploy and human input simulation** *(sunflower)* — Implemented human-like movement planning, gesture-to-action translation, permission prompt answering, and TLS termination on PVE.

> **2026 Jul**
>
> - **Audio metadata writing and uninstall fix** *(intag2)* — Added Vorbis comments for Ogg/Opus files and fixed shell extension removal from GUI uninstall path.
> - **New trading strategies** *(freqtrade_startegies)* — Added pack-relative and BTC-relative reversion strategies, and EWO dip-buy variants with DCA averaging.

> **2026 Jun**
>
> - **CV pipeline and heatmap development** *(jamminroot)* — Built automated CV generation pipeline with LLM guidance, heatmap visualization, and project cards with pulse charts.
> - **AutoHotKey alternative development** *(jolt)* — Created scenario engine with typed actions, input gate, interception support, conditions, rules, and stateless themes.
> - **Strategy research and optimization** *(freqtrade_startegies)* — Developed EwoDip15m leveraged dip-buy strategy and documented forward-test results.

> **2026 May**
>
> - **Firmware v13 with USB HID improvements** *(j-uni-hid)* — Implemented fire-and-forget event emission for USB HID, added 8x8 matrix variant, and fixed disconnection issues.
> - **Windows input filter driver library** *(input-driver)* — Built push-style event delivery API, integration test runner, and per-event blocking with library predicates.
> - **Android TTS engine expansion** *(j-tts-android)* — Added F5-TTS, GPT-SoVITS, Fish-Speech scaffolds, pitch control, Piper TTS via Kotlin G2P, and RuNorm text normalisation.
> - **Aim assist and YOLO inference updates** *(MEMU3)* — Switched GPU inference to DirectML, added bow/flick tracking with user-input compensation, and debug overlay.
> - **E-reader firmware enhancements** *(biscuit)* — Added Knowledge Base app, FB2 reader with encoding support, screensaver folder, and Mesh Chat fixes.
> - **CV automation and workflow improvements** *(jamminroot)* — Refined CV generation with importance tags, heatmap weekly rows, and workflow rebase retries.

> **2026**
>
> - **Firmware iterations v10-v12** *(j-uni-hid)* — Developed dual-core v12 and USB v13 firmware, added new devices, BLE improvements, and self-reporting features.
> - **Computer vision for online poker** *(poker-cv)* — Built CV pipeline for poker state recovery, hand detection, board card accuracy, and log reconstruction for validation.
> - **On-device LLM with phone capabilities** *(ozwil-android)* — Implemented sub-agent delegation, tool routing strategies, model keep-alive, and setup wizard for offline LLM on Android.
> - **File tagging feature expansion** *(intag2)* — Added PDF support, metadata properties, Microsoft Store publishing pipeline, and desktop.ini encoding fixes.
> - **E-reader custom firmware** *(papyrix)* — Added Map app with tile viewer, Knowledge Base with taxonomy browser, FB2 encoding support, and PDF/DjVu conversion.
> - **E-ink launcher for note-taking** *(blackboard-launcher)* — Built Android launcher with backdrop overhaul, swipe navigation, status bar control, and Onyx SDK integration.

> **2025**
>
> - **Firmware v11 and earlier versions** *(j-uni-hid)* — Developed v11 firmware with USB touch, BLE profiles, performance modes, and Android reconnect fixes.
> - **Autonomous AI coding tool** *(auto-claude)* — Built multi-session AI coding assistant with git rules system, squash merging, worktree management, and task ID tracking.
> - **Trading strategy development** *(freqtrade_startegies)* — Created and optimized numerous trading strategies with pattern confirmation, leverage settings, and backtesting.
> - **Telegram bot for trading** *(freqtrade-tg-multibot)* — Developed Telegram bot with web application, Docker support, daily profit calculations, and authentication handling.
> - **Telegram assistant bot** *(pAssistant)* — Built multi-target sending, summarization, image deduplication, and redirection features for a Telegram bot.
> - **n8n Telegram nodes** *(n8n-nodes-telepilot-2)* — Maintained n8n community nodes for Telegram, fixed auth race conditions, added album trigger, and improved CI.

> **2024**
>
> - **Telegram bot initial development** *(pAssistant)* — Started Telegram assistant bot with message forwarding, logging, and error handling.
<!-- ACTIVITY-TIMELINE-END -->

[**Download CV (PDF)**](https://raw.githubusercontent.com/Jamminroot/Jamminroot/master/cards/cv.pdf)
