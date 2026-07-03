## .NET Software Developer, TechLead at Deeplay.io.

### What a time to be alive!

#### [@jamminroot (telegram)](https://t.me/jamminroot), [Dmitrii Chichuk (LinkedIn)](https://linkedin.com/in/dchichuk)

Feel free to reach out!

<!-- ACTIVITY-SUMMARY-START -->
## Recent activity (last 12 months)

*Auto-generated weekly from commit history · updated 2026-07-03*

I've been deep in Summit, a SaaS crypto algo trading platform with AI/neural-network integration — building out mobile responsive shells with Telegram miniapp support, implementing server-authoritative 2FA and session-inactivity locks, adding per-user follow capabilities with balance-relative sizing and order-type controls, enriching backtests with BTC market-regime context and funding-fee modeling, and introducing strategy-level comment fields and LLM token-cost estimates. On the embedded side, I've evolved the j-uni-hid firmware through multiple revisions (v9–v13) for ESP32-S3, adding features like dual-core support, BLE/USB hybrid operation, self-reporting stats, safe serial prints, and a matrix variant, while also building out the companion input-driver Windows WDK kernel driver with event filtering, block predicates, and integration-test coverage.

Alongside these core vectors, I ran a structured research campaign on crypto price-prediction models — over 300 experiments exploring sparse MoE gates, cross-pair features, snapshot ensembles, and temperature scaling to push past the 0.78 F1 ceiling. I built an Android TTS engine supporting multiple Russian voices with pitch control, Vosk/Silero endpointing, and RuNorm rule-based text normalisation. I also reworked the intag2 Windows file-tagging utility with CLI support, MS Store CI/CD pipelines, and Unicode metadata handling, and I overhauled the ozwil-android on-device LLM agent with sub-agent delegation strategies, KV-cache reuse, and model setup wizards. Smaller but notable efforts include a Neovim config migration to the 0.11 API, a YOLO labeler with batch mark mode, and a MynePro e-ink launcher with gesture navigation.
<!-- ACTIVITY-SUMMARY-END -->

<img src="https://raw.githubusercontent.com/Jamminroot/Jamminroot/master/cards/charts.svg" alt="Activity charts">

<img src="https://raw.githubusercontent.com/Jamminroot/Jamminroot/master/cards/projects.svg" alt="Project cards">

<!-- ACTIVITY-TIMELINE-START -->
> **2026 Jul**
>
> - **Summit trading platform — 2FA, follows, backtests** *(summit)* — Built server-authoritative 2FA with session-inactivity lock, per-user follow capabilities with balance-relative sizing, backtest funding-fee modeling, BTC market-regime context, and strategy comment fields.
> - **Summit — mobile shell and Telegram integration** *(summit)* — Implemented a responsive mobile shell with bottom nav and Telegram WebApp SDK, simplified the miniapp UI, and added auto card layout for dense data tables.
> - **Freqtrade strategy variants** *(freqtrade_startegies)* — Added BTC-relative and pack-relative reversion strategies plus a broad EWO dip-buy variant across 50 pairs, all with documented forward-test results.

> **2026 Jun**
>
> - **Summit — notifications, sidebar, engine polish** *(summit)* — Added rich Telegram trade notification cards, an auto-hide sidebar mode, color-coded backtest metrics, EWO-fidelity DSL infrastructure, and fixed the two-tier trailing stop and strategy editing bugs.
> - **jolt — minimal AHK alternative** *(jolt)* — Built a scenario engine with typed actions, input gating, and Interception support; added conditions, stateless themes, and debug logging.
> - **CV generator improvements** *(jamminroot)* — Refined the auto-CV pipeline: added dry-run preview, skills section, team/throughput metrics, and enforced consistent voice in LLM output.

> **2026 May**
>
> - **j-uni-hid firmware — v13 release** *(j-uni-hid)* — Released firmware v13 with fire-and-forget events, USB HID improvements, and an 8x8 matrix variant with PlatformIO build support.
> - **input-driver — library and integration tests** *(input-driver)* — Added push-style event delivery with JidStartListener/JidStopListener, per-event block predicates, and a full integration-test runner covering all documented capabilities.
> - **j-tts-android — engine overhaul** *(j-tts-android)* — Replaced multiple TTS engines: dropped Piper/eSpeak NG, added TeraTTS and sherpa-onnx Russian voices, F5-TTS scaffold, question/exclamation intonation sliders, and forced commercial-distribution-clean licensing.
> - **intag2 — Unicode metadata fix** *(intag2)* — Fixed desktop.ini writing to UTF-16 LE for correct non-ASCII rendering in Explorer.
> - **MEMU3 — YOLO inference and bow/flick work** *(MEMU3)* — Switched GPU inference from CUDA to DirectML, refactored YOLO class handling, and reworked the bow/flick system with bezier motion, user-input compensation, and closed-loop tracking.
> - **CV generator — pulse charts and project cards** *(jamminroot)* — Added project cards with pulse-line charts to the README, smoothed Catmull-Rom curves, and improved heatmap rendering with empty-week slots.

> **2026 Apr**
>
> - **Summit — authentication and session security** *(summit)* — Implemented server-authoritative session inactivity lock with PIN/2FA/logout, fixed 2FA field name bug, and added admin reset of user stats.
> - **j-uni-hid — v13 WIP and bugfixes** *(j-uni-hid)* — Drafted the v13s8x8 firmware variant and fixed a device disconnection issue in the earlier v13 build.
> - **MEMU3 — aim assist and overlay refinement** *(MEMU3)* — Added HP-scaling aim, YOLO confidence threshold UI, debug overlay window, and runtime fallback from Interception to USB-HID.
> - **papyrix — map app and knowledge base** *(papyrix)* — Added a full-map app with region selection and tile viewer, a knowledge base app with taxonomy browser, and optimised the map renderer for Apple Silicon.

> **2026 Mar**
>
> - **Summit — LLM token costs and backtest management** *(summit)* — Added per-signal LLM token/cost estimates, backtest run deletion and collapse of identical re-runs, and BTC market-regime context for quorum signals.
> - **crypto-model-research — MoE experiments** *(crypto-model-research)* — Ran 300+ experiments on crypto price-prediction models, achieving a 0.7817 F1 with split MoE gates, snapshot ensembles, cross-pair BTC/ETH features, and temperature scaling.
> - **ozwil-android — sub-agent architecture** *(ozwil-android)* — Rewrote the sub-agent delegation system with session-based routing, tool-call validation, setup wizard, KV-cache reuse, and persistent model keep-alive.
> - **MEMU3 — status window and persistence** *(MEMU3)* — Rewrote the overlay with D3D11/D2D/DComp, added a status window, persisted mode and autofire state across restarts, and restricted aim assist to the focused window.
> - **blackboard-launcher — gesture navigation** *(blackboard-launcher)* — Overhauled the backdrop with swipe page navigation, status bar control, and improved Onyx SDK drawing reliability.

> **2026 Feb**
>
> - **intag2 — CI/CD and MS Store pipeline** *(intag2)* — Built a robust MS Store submission pipeline with PowerShell REST API, split CI into discrete workflows, added auto-changelog generation, and fixed folder property setting via CLI.
> - **jaxon — code intelligence engine** *(jaxon)* — Added LSP integration, DI registration detection, dead-code analysis, and multi-language parsers (C++, Go, Rust, Svelte); shipped incremental sync and force-reindex flags.
> - **n8n-nodes-telepilot-2 — auth fixes** *(n8n-nodes-telepilot-2)* — Fixed authentication race conditions, resolved CI test failures from n8n version bumps, and added an album trigger.
> - **yolo-labeler — batch mark mode** *(yolo-labeler)* — Added multi-select mark mode for batch delete and label clearing, Ctrl+Delete deletion, and flexible yaml resolution.
> - **.dotfiles — Neovim 0.11 migration** *(.dotfiles)* — Migrated LSP configuration to vim.lsp.config for Neovim 0.11, added OSC 52 clipboard support, and fixed treesitter parser installation.

> **2026 Jan**
>
> - **poker-cv — recovery and validation modules** *(poker-cv)* — Implemented generator-based hand recovery, CV pipeline with blinds/board-card detection, interpreter visualisation widget, and comprehensive codebase refactoring.
> - **tasker — touch visualisation** *(tasker)* — Added touch event visualisation on sensor charts and improved UX with direct launch and completed status indicators.

> **2025**
>
> - **Summit — foundational platform build** *(summit)* — Built the core SaaS crypto algo trading platform with AI/NN twis, including engine infrastructure, strategy templates, and telegram bot integration.
> - **j-uni-hid — firmware through v11** *(j-uni-hid)* — Developed multiple firmware generations (v4–v11): dual-core support, BLE/USB touch, mouse emulation, self-reporting, safe serial, device profiles, and throttled power modes.
> - **ozwil-android — initial LLM app scaffold** *(ozwil-android)* — Scaffolded the on-device LLM app with background service, tool-calling capability, and wake-word detection.
> - **j-tts-android — early TTS work** *(j-tts-android)* — Began Android TTS implementation with Piper eSpeak NG, Vosk/Silero endpointing, and accent dictionaries.
> - **auto-claude — multi-session AI coding** *(auto-claude)* — Built a multi-session AI coding assistant with git worktree management, squash merging, task-ID tracking, and Git rules configuration.
> - **freqtrade-tg-multibot — Telegram monitoring** *(freqtrade-tg-multibot)* — Developed a Telegram bot for monitoring multiple Freqtrade instances, with daily profit calculation and authentication handling.
> - **freqtrade_monitor — Flutter dashboard** *(freqtrade_monitor)* — Built a Flutter dashboard for Freqtrade with glassy cards, winrate bar charts, import-export settings, and dark UI.

> **2024**
>
> - **Summit — initial prototype** *(summit)* — Started the Summit crypto trading platform prototype, establishing the core architecture and telegram integration.
> - **pAssistant — Telegram automation tooling** *(pAssistant)* — Built a Telegram automation tool with summarization, image duplicate detection, and multi-target message routing.
> - **freqtrade_strats — strategy optimizations** *(freqtrade_strats)* — Optimised several Freqtrade trading strategies with custom indicators and leverage management.
<!-- ACTIVITY-TIMELINE-END -->

[**Download CV (PDF)**](https://raw.githubusercontent.com/Jamminroot/Jamminroot/master/cards/cv.pdf)
