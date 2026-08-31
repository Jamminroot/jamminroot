## Recent activity (last 12 months)

*Auto-generated weekly from commit history · updated 2026-08-31*

I built the core of a SaaS crypto algo trading platform (summit), adding follow management, strategy catalog, and email authentication. Simultaneously, I developed firmware for USB HID devices (j-uni-hid) and a Windows input filter driver (input-driver). On the research side, I continuously refined a crypto price prediction model (crypto-model-research), running audits and discarding hypotheses. I also worked on multiple secondary projects: an Android TTS engine (j-tts-android), an on-device LLM with phone automation (ozwil-android), a file-tagging utility for Windows Explorer (intag2), and an agentic worker framework (agent-harness). Additionally, I built a poker computer vision pipeline (poker-cv), a trading strategy repository (freqtrade_startegies), and maintained Telegram bot infrastructure (freqtrade-tg-multibot). The year also saw the start of a minimal AutoHotKey alternative (jolt) and a graph-powered code intelligence engine (jaxon). Across these projects, I worked on full-stack features, firmware, driver development, machine learning research, and infrastructure.
> **2026 Aug**
>
> - **SaaS crypto algo trading platform** *(summit)* — Built follow management features including interactive exit simulator, open position tracking, and costs. Reworked strategy catalog with exchange suitability filters and per-follow history. Added email authentication and admin backfill.
> - **Crypto price prediction model research** *(crypto-model-research)* — Conducted a full audit of the model pipeline, discarding several hypotheses (HMM state features, isotonic sizing) and keeping Mondrian conformal gates. Prepared refit runbooks and drift monitoring tooling.
> - **Windows Explorer file-tagging utility** *(intag2)* — Fixed settings persistence, Explorer refresh, and backdrop fallback. Added Vorbis comment writing for audio files.
> - **Agentic worker framework** *(agent-harness)* — Built workspace-aware Telegram threading, memory management with hybrid retrieval, and a graphical control room. Added tenant interaction channels and resource registration.

> **2026 Jul**
>
> - **File-tagging utility maintenance** *(intag2)* — Collapsed the two-stage release into a single workflow, fixed metadata write failures, and added Vorbis comment support for ogg files.
> - **Crypto trading strategy development** *(freqtrade_startegies)* — Added pack-relative reversion and BTC-relative reversion strategies, with forward testing and documentation.

> **2026 Jun**
>
> - **Personal CV automation** *(jamminroot)* — Enhanced the CV generation pipeline with LLM-based timeline, improved heatmap and project cards, and added dry-run mode.
> - **Trading strategy iteration** *(freqtrade_startegies)* — Developed multiple EwoDip and reversion strategies, documented forward test results, and tuned parameters.
> - **Minimal AutoHotKey alternative** *(jolt)* — Built the scenario engine with typed actions, input gates, and Interception support. Added conditions, rules, and sound actions.

> **2026 May**
>
> - **USB HID firmware for ESP32-S3** *(j-uni-hid)* — Added fire-and-forget emitting and an 8x8 matrix variant. Introduced platformio support.
> - **Windows input filter driver** *(input-driver)* — Built a KMDF driver for keyboard and mouse capture and injection. Added event filtering, hardware ID matching, and integration tests.
> - **Android TTS engine with multiple models** *(j-tts-android)* — Integrated VITS, Piper, and F5-TTS engines. Added pitch control, text normalisation with RuNorm, and background TTS with core pinning.
> - **File-tagging utility updates** *(intag2)* — Fixed desktop.ini encoding for non-ASCII characters and added PDF support to the context menu.
> - **Computer vision assist tool** *(MEMU3)* — Switched YOLO inference to DirectML, added bow/flick feature with tracking, and improved the debug overlay.

> **2026 Apr**
>
> - **USB HID firmware iteration** *(j-uni-hid)* — Drafted a new firmware variant and fixed USB disconnection issues.
> - **File-tagging utility fixes** *(intag2)* — Fixed changelog generation and preserved existing desktop.ini entries when writing folder metadata.
> - **E-reader firmware with maps and knowledge base** *(papyrix)* — Added Knowledge Base and Map applications, optimised the map renderer, and improved FB2 encoding support.
> - **Computer vision assist updates** *(MEMU3)* — Added HP aim scaling, YOLO confidence threshold UI, and runtime fallback to USB-HID.

> **2026 Mar**
>
> - **USB HID firmware advancement** *(j-uni-hid)* — Introduced dual-core and USB variants of the firmware.
> - **On-device LLM with phone automation** *(ozwil-android)* — Rewrote the sub-agent architecture with session-based delegation and tool calling. Added background service, wake processing, and model presets.
> - **E-reader firmware enhancements** *(papyrix)* — Rewritten the Map app UI for landscape, added PDF/DjVu conversion, and fixed encoding issues.
> - **Computer vision assist improvements** *(MEMU3)* — Rewrote the overlay to D3D11, added linger and autofire modes, and persisted state across restarts.

> **2026**
>
> - **Pet research on poker computer vision** *(poker-cv)* — Developed a pipeline for card detection, hand reconstruction, and log validation from video. Achieved high accuracy for hero cards and board cards.
> - **Graph-powered code intelligence engine** *(jaxon)* — Added language support for C++, Go, Rust, and Svelte. Implemented dead code detection, LSP integration, and incremental sync.
> - **Neovim dotfiles** *(.dotfiles)* — Migrated to Neovim 0.11 API, added secret detection pre-commit hook, and fixed treesitter and LSP configurations.

> **2025**
>
> - **Telegram bot for multi-bot management** *(freqtrade-tg-multibot)* — Built a web application with Docker support, improved Telegram authentication, and refined profit calculations.
> - **Autonomous AI coding tool** *(auto-claude)* — Added squash-merge, completion tracking, and Git rules system. Improved the UI with task ID and worktree management.
> - **Crypto trading strategy development** *(freqtrade_startegies)* — Developed and optimized multiple strategies (e.g., SimpleEMA, MinimalPMAX) with backtesting and parameter tuning.
> - **Computer vision assist tool** *(MEMU3)* — Started the project with USB HID mouse event rate limiting and YOLO model integration.

> **2024**
>
> - **Telegram assistant bot** *(pAssistant)* — Built a Telegram bot with multi-target sending, summarization, and error handling. Refactored settings and logging.
