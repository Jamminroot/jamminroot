## .NET Software Developer, TechLead at Deeplay.io.

### What a time to be alive!

#### [@jamminroot (telegram)](https://t.me/jamminroot), [Dmitrii Chichuk (LinkedIn)](https://linkedin.com/in/dchichuk)

Feel free to reach out!

<!-- ACTIVITY-SUMMARY-START -->
## Recent activity (last 12 months)

*Auto-generated weekly from commit history · updated 2026-07-20*

Built the core of Summit, a SaaS crypto algo-trading platform with AI/ML twists — strategy groups & variants, a quorum-based voting system with LLM experts, evaluation benchmarking, and admin tooling. Also developed j-uni-hid, a feature-rich mouse/keyboard emulation firmware for ESP32-S3, and input-driver, a Windows WDK input filter/injection driver. Researched crypto price prediction models in Python, building and forward-testing a champion ensemble with 77-90% win rate. Maintained a portfolio of personal projects: poker CV pipeline for online platforms, Windows Explorer file-tagging utility intag2, Android TTS engine j-tts-android with multiple model backends, and the ozwil Android app for on-device LLM with phone-use capabilities. Iterated on the CV generation toolchain jamminroot, refining timeline extraction, heatmap visualization, and PDF rendering. Work spanned C#, C++, C, Python, Kotlin, TypeScript, and Dart across systems programming, machine learning, mobile development, and infrastructure automation.
<!-- ACTIVITY-SUMMARY-END -->

<img src="https://raw.githubusercontent.com/Jamminroot/Jamminroot/master/cards/charts.svg" alt="Activity charts">

<img src="https://raw.githubusercontent.com/Jamminroot/Jamminroot/master/cards/projects.svg" alt="Project cards">

<!-- ACTIVITY-TIMELINE-START -->
> **2026 Jul**
>
> - **Strategy groups and quorum voting** *(summit)* — Built strategy groups with Guided/Standard variants, a quorum-based voting system with LLM expert integration and categorical voting, evaluation benchmarking frontend and backend, and admin UI improvements.
> - **Crypto price prediction model research** *(crypto-model-research)* — Productionized a 13-feature champion model ensemble with 77-90% forward-tested win rate, integrated ONNX export for Summit, and ran experiments with enriched features and PnL surrogate objectives.
> - **Trading strategy development** *(freqtrade_startegies)* — Developed and forward-tested multiple 15m trading strategies including pack-relative reversion and BTC-relative-strength reversion variants with strong OOS performance.

> **2026 Jun**
>
> - **CV generation toolchain** *(jamminroot)* — Refined the CV generation pipeline: added LLM model override, enforced first-person voice, excluded archived repos, split Deeplay roles, and improved heatmap and timeline rendering.
> - **Minimal AutoHotKey alternative** *(jolt)* — Built a scenario engine with typed actions, input gate, interception support, conditions, rules, stateless themes, and sound actions for a minimal AutoHotKey alternative.
> - **Trading strategy development** *(freqtrade_startegies)* — Developed EwoDip15m strategy variants with DCA averaging, trend regime guards, and broad 50-pair universe champion with strong forward-test results.

> **2026 May**
>
> - **USB HID firmware development** *(j-uni-hid)* — Developed v13 firmware variant with 8x8 matrix support, fire-and-forget USB HID emitting, and PlatformIO integration for the ESP32-S3 mouse/keyboard emulation project.
> - **Windows input driver library** *(input-driver)* — Added push-style event delivery with JidStartListener/JidStopListener, integration-test runner covering all documented capabilities, and per-event Block support with library predicates.
> - **Android TTS engine development** *(j-tts-android)* — Integrated multiple TTS engines including sherpa-onnx, TeraTTS, and F5-TTS; added pitch control, question/exclamation intonation sliders, RuNorm text normalization, and background processing optimizations.
> - **Aim assist and overlay work** *(MEMU3)* — Refactored YOLO inference to DirectML EP, added bow/flick tracking with bezier motion and user-input compensation, and improved debug overlay and configuration persistence.
> - **E-ink reader firmware update** *(biscuit)* — Added Knowledge Base app, FB2 reader, screensaver folder, and Mesh Chat fixes to the expanded biscuit firmware for xteink 4.

> **2026 Apr**
>
> - **USB HID firmware iteration** *(j-uni-hid)* — Drafted new v13s8x8 firmware variant and fixed USB disconnect issues in the v13 ESP32-S3 HID firmware.
> - **E-ink reader firmware development** *(papyrix)* — Added Map app with region selection and tile viewer, Knowledge Base app with taxonomy browser, FB2 encoding fixes, and optimized map renderer for Apple Silicon.
> - **Proxy client update** *(FlCLash)* — Added XHTTP transport support via rebased mihomo and re-exposed ProxiesWithProviders/GetProxyNameList APIs.
> - **Aim assist improvements** *(MEMU3)* — Added HP aim scaling with YOLO body bbox, debug overlay in separate window, and runtime fallback from Interception to USB-HID.

> **2026 Mar**
>
> - **On-device LLM Android app** *(ozwil-android)* — Rewrote sub-agent architecture with session-based delegation and tool execution pipeline, added setup wizard, KV cache reuse, background service architecture, and multiple model support including Qwen and LFM.
> - **Crypto price prediction model research** *(crypto-model-research)* — Ran extensive experiments with MoE architectures, FFT frequency decomposition for gate routing, and multi-horizon regression; achieved champion ensemble with 0.8617 val_sqs.
> - **Aim assist and overlay rewrite** *(MEMU3)* — Rewrote overlay to D3D11+D2D+DComp, added status window, autofire, HID click emulation, YOLO model integration, and restricted aim assist to focused window.
> - **E-ink launcher development** *(blackboard-launcher)* — Built a simple Android launcher for E-ink readers centered around note-taking, with backdrop overhaul, swipe page navigation, and status bar control.

> **2026 Feb**
>
> - **Windows file-tagging utility** *(intag2)* — Added .pdf support to context menu, restructured CI pipelines for manual triggering and auto-drafting releases, fixed MS Store publishing workflow with PowerShell REST API, and added CLI for reading properties.
> - **Neovim dotfiles configuration** *(.dotfiles)* — Set up initial Neovim config with full IDE setup, migrated LSP config to vim.lsp.config for Neovim 0.11+, added pre-commit hook for secret detection, and fixed treesitter and telescope compatibility.
> - **Code intelligence engine** *(jaxon)* — Added LSP integration for language-server-powered code analysis, index freshness detection with automatic incremental sync, and expanded framework coverage for DI registration and dead code detection.
> - **YOLO labeler tool** *(yolo-labeler)* — Built a simple on-host YOLO labeler with multi-select mark mode, Ctrl+Delete entry deletion, and flexible yaml resolution.
> - **Telegram automation node** *(n8n-nodes-telepilot-2)* — Fixed auth race condition, upgraded n8n CI test version, added retry logic for npm install, and added new album trigger.

> **2026 Jan**
>
> - **Poker CV pipeline development** *(poker-cv)* — Implemented generator-based recovery, interpreter integration to video player, CvRecovery module for poker state validation, and achieved 99% hand detection and 97.8% board card accuracy.
> - **Touch event visualization tool** *(tasker)* — Improved UX with direct launch, completed status, and touch event visualization on sensor charts.
> - **USB HID firmware iteration** *(j-uni-hid)* — Fixed graceful COM restart in the ESP32-S3 HID firmware.

> **2025**
>
> - **USB HID firmware development** *(j-uni-hid)* — Developed v10-v13 firmware variants for ESP32-S3 with USB touch, BLE support, self-reporting, performance profiles, and Android compatibility fixes.
> - **Autonomous AI coding tool** *(auto-claude)* — Added squash-merge functionality, completion tracking, Git rules system, and task ID management to the autonomous multi-session AI coding tool.
> - **Telegram bot monitoring** *(freqtrade-tg-multibot)* — Built a Telegram bot for monitoring multiple Freqtrade instances with daily profit calculations, authentication, and Docker deployment.
> - **Freqtrade monitoring app** *(freqtrade_monitor)* — Developed a Flutter app for monitoring Freqtrade instances with glassy cards, winrate bar charts, expandable cards, and import-export functionality.
> - **Telegram automation assistant** *(pAssistant)* — Added summarization, multi-target sending, image deduplication, and redirection rework to the Telegram automation assistant.
> - **Trading strategy development** *(freqtrade_startegies)* — Developed and refined multiple trading strategies including Fenix5m, botman, and ns531_pat_fixed35 with optimized parameters and backtesting.
> - **Content collector tool** *(jContentCollector)* — Built a Telegram content collector with ad filtering, webhook support, and ignored channels.
> - **n8n Claude Code node** *(n8n-nodes-claudecode)* — Migrated to Claude Agent SDK, added Haiku model support, and fixed abort controller cleanup.

> **2024**
>
> - **Telegram automation assistant** *(pAssistant)* — Maintained the Telegram automation assistant with logging improvements, forwarding bug fixes, and minor refactoring.
> - **Asio server test** *(apollo_server)* — Initial work on an Asio-based C++ server.
<!-- ACTIVITY-TIMELINE-END -->

[**Download CV (PDF)**](https://raw.githubusercontent.com/Jamminroot/Jamminroot/master/cards/cv.pdf)
