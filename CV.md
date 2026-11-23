## Recent activity (last 12 months)

*Auto-generated weekly from commit history · updated 2026-11-23*

I've been deeply involved in building and refining a SaaS crypto algo trading platform called Summit, which incorporates AI and neural network components. The work spans the full stack: wallet-group management, LLM-based judge systems for quorum and sentiment analysis, copy trading infrastructure, and a calm-liquidity rebalancing signal. I also maintain a feature-rich USB HID firmware project (j-uni-hid) for ESP32-S3, covering mouse, keyboard, and touch emulation across multiple firmware variants, and developed a Windows kernel-mode input filter driver (input-driver) for capture and injection.

Alongside the primary projects, I've been working on an agentic worker framework (agent-harness) in Rust, adding chat windows, peer-to-peer node networking, speech cascades, and Android VPN integration. The crypto-model-research project involved systematic experimentation with price prediction models, including conformal prediction, drift monitoring, and a unified protocol for model ranking. I also built a computer vision pipeline for online poker (poker-cv), achieving high hand and card detection accuracy through iterative refinement.

On the tooling side, I extended the Windows file-tagging utility intag2 with Matroska/WebM tag writing, DPI-aware UI scaling, and MS Store CI/CD. The sunflower project is a browser-in-a-browser system with container orchestration, font management, and anti-fingerprinting measures. I also worked on an Android TTS engine (j-tts-android) with multiple model backends, pitch control, and Russian language support, and an on-device LLM app (ozwil-android) with sub-agent delegation, tool routing, and wake-word processing.
> **2026 Nov**
>
> - **Agentic worker framework** *(agent-harness)* — Built a chat window with model picker, thread management, and terminal integration; added peer-to-peer node networking with signed admission, speech cascades, and Android VPN support.

> **2026 Oct**
>
> - **Summit platform development** *(summit)* — Fixed wallet-group scheduled proposal execution and admin wallet notifications; improved auth session persistence and scanner performance by skipping already-evaluated lanes.
> - **YOLO labeler updates** *(yolo-labeler)* — Added validator features, constraint highlighting, label transparency, and quality-of-life improvements for the on-host labeling tool.

> **2026 Sep**
>
> - **Summit LLM and copy trading** *(summit)* — Implemented a System One judge seat for quorum and sentiment, provider capabilities for seat placement, and calm-liquidity rebalancing signals; fixed copy trading floor and discovery logic.
> - **Sunflower browser-in-browser** *(sunflower)* — Added font pack management, anti-fingerprinting measures, human-like movement planning, and container orchestration with tenant delegation and permission prompt handling.
> - **Intag2 file tagging** *(intag2)* — Added Matroska/WebM tag writing, XMP support for WebP, DPI-aware UI scaling, and context menu support for Ogg and Matroska audio files.

> **2026 Aug**
>
> - **Crypto model research** *(crypto-model-research)* — Conducted systematic model cataloging with unified protocol ranking, drift monitoring, and refit runbooks; discarded several hypotheses and kept conformal prediction and side-specific cuts.
> - **Summit rebalancing and follows** *(summit)* — Built calm-liquidity backtest replay, paper-only signal, and account share management; fixed rebalancing floor silencing and wallet-group veto logic.

> **2026 Jul**
>
> - **Trading strategies** *(freqtrade_startegies)* — Added pack-relative and BTC-relative reversion strategies with forward-test documentation, and EWO dip-buy variants with DCA averaging and trend regime guards.

> **2026 Jun**
>
> - **CV automation and dotfiles** *(jamminroot)* — Refined the CV generation pipeline with LLM guidance, importance tagging, and project cards; added pulse line charts and heatmap visualization.
> - **Jolt input automation** *(jolt)* — Built a minimal AutoHotKey alternative with interception support, scenario engine, conditions, rules, and stateless themes.

> **2026 May**
>
> - **USB HID firmware** *(j-uni-hid)* — Developed v13 firmware with fire-and-forget USB HID events and 8x8 matrix variant; fixed dying/disconnect issues.
> - **Input driver development** *(input-driver)* — Built a working KMDF input filter driver for capture and injection; added push-style event delivery, integration tests, and per-event blocking with library predicates.
> - **Android TTS engine** *(j-tts-android)* — Added question/exclamation intonation sliders, pitch control, multiple TTS engine scaffolds (F5-TTS, GPT-SoVITS, Fish-Speech), and RuNorm text normalization.
> - **MEMU3 mouse emulation** *(MEMU3)* — Switched YOLO inference to DirectML, added bow/flick tracking with bezier motion and user-input compensation, and implemented runtime fallback between Interception and USB-HID.

> **2026 Apr**
>
> - **USB HID firmware v13** *(j-uni-hid)* — Drafted new firmware variant v13s8x8 and fixed dying/disconnect issues in the v13 line.
> - **Papyrix e-ink firmware** *(papyrix)* — Added Map app with tile viewer, Knowledge Base with taxonomy browser, FB2 encoding fixes, and map renderer optimization for Apple Silicon.
> - **FlClash proxy client** *(FlCLash)* — Added XHTTP transport support via rebased mihomo and fixed CI build for submodule dependencies.

> **2026 Mar**
>
> - **Ozwil Android LLM app** *(ozwil-android)* — Rewrote sub-agent architecture with session-based delegation, tool routing strategies, and model keep-alive; added setup wizard, KV cache reuse, and background service architecture.
> - **MEMU3 overlay and modes** *(MEMU3)* — Rewrote overlay to D3D11+D2D+DComp, added status window, linger mode, autofire, and YOLO model integration; restricted aim assist to focused window.
> - **Papyrix map and knowledge base** *(papyrix)* — Added Map app with landscape UI, scale bar, and physical button mapping; implemented Knowledge Base with section-jump navigation and FB2 encoding support.

> **2026 Feb**
>
> - **Intag2 CI/CD and MS Store** *(intag2)* — Restructured release pipelines, fixed MS Store publish workflow with PowerShell REST API, and added PDF support to context menu.
> - **Jaxon code intelligence** *(jaxon)* — Added LSP integration, index freshness detection, DI registration detection, and expanded language support to C++, Go, Rust, and Svelte.
> - **Dotfiles and Neovim config** *(.dotfiles)* — Set up Neovim config with full IDE, LSP, treesitter, and pre-commit hook for secret detection.
> - **Telepilot n8n nodes** *(n8n-nodes-telepilot-2)* — Fixed auth race condition, upgraded CI test version, and added album trigger for the Telegram n8n node fork.

> **2026 Jan**
>
> - **Poker CV pipeline** *(poker-cv)* — Achieved high hand and card detection accuracy through iterative refinement; added pipeline smoke tests, interpreter integration, and log reconstruction for validation.
> - **Intag2 metadata support** *(intag2)* — Added support for additional metadata properties and privacy policy for Microsoft Store submission.
> - **Tasker Android app** *(tasker)* — Improved UX with direct launch, completed status, and touch event visualization on sensor charts.

> **2025**
>
> - **Summit platform foundation** *(summit)* — Continued building the crypto algo trading platform with LLM-based judge systems, copy trading, and wallet-group management.
> - **USB HID firmware evolution** *(j-uni-hid)* — Developed multiple firmware variants (v9-v13) for ESP32-S3 with BLE, USB touch, mouse emulation, and performance throttling.
> - **Agentic worker framework** *(agent-harness)* — Built the initial agentic worker framework with chat, tool execution, and peer-to-peer networking.
> - **Crypto model research** *(crypto-model-research)* — Conducted extensive experimentation with price prediction models, including conformal prediction and drift monitoring.
> - **Auto-claude development** *(auto-claude)* — Built autonomous multi-session AI coding tool with squash merging, git rules system, and task management.
> - **Trading strategies and bots** *(freqtrade_startegies)* — Developed and refined multiple trading strategies with backtesting and optimization.
> - **Telegram bot infrastructure** *(freqtrade-tg-multibot)* — Built multi-bot Telegram monitoring and control system with authentication and profit tracking.
> - **Android TTS engine** *(j-tts-android)* — Started the Android TTS project with multiple engine backends and Russian language support.
> - **MEMU3 mouse emulation** *(MEMU3)* — Initial development of mouse and keyboard emulation with YOLO-based aim assist and USB-HID support.

> **2024**
>
> - **Telegram bot development** *(pAssistant)* — Built a Telegram assistant bot with summarization, image deduplication, and multi-target sending capabilities.
> - **Trading bot monitoring** *(freqtrade_monitor)* — Developed a Flutter-based monitoring app for trading bots with charts, cards, and import-export functionality.
> - **ChatGPT Telegram bot** *(chatgpt_telegram_net)* — Maintained a .NET-based ChatGPT Telegram bot with updates.
