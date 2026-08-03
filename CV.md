## Recent activity (last 12 months)

*Auto-generated weekly from commit history · updated 2026-08-03*

I've been building a full-stack crypto algo trading platform (Summit) with AI-driven copy trading, a live copylab dashboard, and an LLM recommendation engine. On the firmware side, I developed a feature-rich mouse and keyboard emulation firmware for ESP32-S3 (j-uni-hid) and a Windows kernel-mode input filter driver (input-driver). I also conducted extensive research on crypto price prediction models (crypto-model-research), iterating on MoE architectures and productionizing ONNX ensembles. Across the board, I worked on a file-tagging utility for Windows Explorer (intag2), an Android TTS engine with multiple models (j-tts-android), and an on-device LLM agent with phone-use capabilities (ozwil-android). I refined my CV generation pipeline (jamminroot) and maintained various automation tools, trading bots, and personal projects.
> **2026 Aug**
>
> - **Summit copy trading platform expansion** *(summit)* — Built the copylab module with live exposure maps, AI grouping, leverage profiles, and an LLM recommendation system for wallet selection.

> **2026 Jul**
>
> - **Crypto model productionization** *(crypto-model-research)* — Productionized the champion 13-feature model, validated forward-testing with 77-90% win rate, and exported the ensemble to ONNX for Summit integration.
> - **Intag2 v2.5 release and metadata fixes** *(intag2)* — Shipped version 2.5 with Vorbis comment support for audio files, fixed uninstall and metadata write errors, and improved CI workflows.
> - **New trading strategies for freqtrade** *(freqtrade_startegies)* — Developed pack-relative and BTC-relative reversion strategies, adding diversification to the 15m strategy portfolio.

> **2026 Jun**
>
> - **CV generation pipeline overhaul** *(jamminroot)* — Reworked the CV generation pipeline with importance tags, heatmap visualization, and a skills section; added dry-run mode and LLM voice enforcement.
> - **Jolt scenario engine and input gate** *(jolt)* — Built the scenario engine with typed actions, input gate, and interception support; added conditions, rules, and sound actions.
> - **EWO dip-buy strategy development** *(freqtrade_startegies)* — Created a series of EwoDip15m strategies with trend regimes, DCA averaging, and forward-testing documentation.

> **2026 May**
>
> - **j-uni-hid v13 firmware development** *(j-uni-hid)* — Developed v13 with fire-and-forget emitting, USB HID events, and an 8x8 matrix variant for the ESP32-S3.
> - **Input driver v1.2 and integration tests** *(input-driver)* — Released v1.2 with library predicates, event type masks, and a full integration-test runner covering all driver capabilities.
> - **J-TTS Android engine refactoring** *(j-tts-android)* — Removed deprecated TTS engines, integrated F5-TTS and sherpa-onnx, added pitch control, and implemented Russian text normalisation (RuNorm).
> - **MEMU3 YOLO and bow/flick features** *(MEMU3)* — Reworked YOLO inference to DirectML, added closed-loop tracking flick with bezier motion, and improved the debug overlay.
> - **Jamminroot CV PDF and project cards** *(jamminroot)* — Added a CV PDF with project cards, pulse line charts, and heatmap; restructured the README and workflow rebase retries.
> - **Biscuit firmware update** *(biscuit)* — Added Knowledge Base app, FB2 reader, screensaver folder, and Mesh Chat fixes to the xteink 4 firmware.

> **2026 Apr**
>
> - **j-uni-hid v13s8x8 draft** *(j-uni-hid)* — Drafted a new firmware variant (v13s8x8) and fixed a dying issue in the v13 build.
> - **Intag2 changelog and desktop.ini fix** *(intag2)* — Fixed changelog generation and preserved existing desktop.ini entries when writing folder metadata.
> - **MEMU3 aim assist and debug overlay** *(MEMU3)* — Added HP aim scaling with YOLO bbox, momentum dampening, and a separate debug window; implemented runtime fallback to USB-HID.
> - **Papyrix map app and knowledge base** *(papyrix)* — Built a map app with tile viewer and region selection, a Knowledge Base with taxonomy browser, and added FB2 encoding support.
> - **FlClash XHTTP transport** *(FlClash)* — Added XHTTP transport support via a rebased Mihomo fork and re-exposed proxied APIs.
> - **Crypto model attention investigation** *(crypto-model-research)* — Investigated attention mechanisms; three experiments all below baseline due to MPS limitations.

> **2026 Mar**
>
> - **j-uni-hid v12 and v13 introduction** *(j-uni-hid)* — Introduced v12 (dual-core) and v13 (USB) firmware variants.
> - **MEMU3 overlay rewrite and autofire** *(MEMU3)* — Rewrote the overlay to D3D11+D2D+DComp, added linger mode, autofire, HID click emulation, and YOLO model integration.
> - **Ozwil Android sub-agent architecture** *(ozwil-android)* — Rewrote the sub-agent system with session-based delegation, tool routing, and auto-delegation when the main model refuses; added model presets and wake processing.
> - **Ozwil API backend setup** *(ozwil-api)* — Set up the ASP.NET Core backend with Docker healthcheck, tool safety rails, and initial Ozwil app configuration.
> - **Papyrix map app and PDF conversion** *(papyrix)* — Rewrote the MapApp UI for landscape, added PDF/DjVu to XTCH conversion, and fixed FB2 encoding support.
> - **Blackboard launcher UI overhaul** *(blackboard-launcher)* — Overhauled the backdrop with swipe navigation, added status bar control, and fixed drawing reliability for Onyx e-ink.
> - **Crypto model MoE experiments** *(crypto-model-research)* — Ran extensive experiments with Split MoE gates, Top-1 Sparse MoE, and snapshot ensembles; benchmarked 6 variants and updated the production bundle.

> **2026**
>
> - **Poker CV pipeline development** *(poker-cv)* — Built a computer vision pipeline for online poker platforms, achieving 99% hand detection and 97.8% board card accuracy.
> - **Intag2 CI and MS Store publishing** *(intag2)* — Set up CI pipelines for MS Store publishing, fixed CLI and metadata issues, and added auto-updating changelog.
> - **Jaxon code intelligence engine** *(jaxon)* — Built a graph-based code intelligence engine with LSP integration, dead code detection, and multi-language parser support.
> - **TelePilot n8n nodes maintenance** *(n8n-nodes-telepilot-2)* — Fixed auth race conditions, CI retry logic, and upgraded n8n test version for the Telegram n8n integration.
> - **YOLO labeler tool** *(yolo-labeler)* — Created a simple on-host YOLO labeler with multi-select mark mode and entry deletion.
> - **Dotfiles and Neovim config** *(.dotfiles)* — Set up chezmoi-managed dotfiles with Neovim 0.11+ config, treesitter, LSP, and secret detection pre-commit hook.
> - **MEMU3 and pAssistant updates** *(MEMU3)* — Polished MEMU3 with mode persistence and status window fixes; maintained pAssistant with summarization and error logging.

> **2025**
>
> - **Freqtrade Telegram multi-bot** *(freqtrade-tg-multibot)* — Built a Telegram bot for monitoring multiple freqtrade instances, with daily profit calculations and bot authentication.
> - **pAssistant content aggregation and summarization** *(pAssistant)* — Maintained a Telegram content aggregator with summarization, repost indices, and multi-target sending.
> - **Trading strategy development** *(freqtrade_startegies)* — Developed and backtested multiple trading strategies (PMAX, EMA, pattern-based) for freqtrade, optimizing parameters and win rates.
> - **Auto-claude autonomous coding agent** *(auto-claude)* — Built an autonomous AI coding agent with worktree management, squash merging, git rules, and task ID tracking.
> - **j-uni-hid v10 and v11 firmware** *(j-uni-hid)* — Developed multiple firmware versions (v10 USB touch, v11 BLE) with touch, mouse, and swipe support for ESP32.
> - **MEMU3 early HID and YOLO work** *(MEMU3)* — Initial work on USB HID mouse movement, rate limiting, and aim assistant integration.
> - **Freqtrade monitor Flutter app** *(freqtrade_monitor)* — Built a Flutter mobile app for monitoring freqtrade bots with winrate charts, glassy cards, and import-export.

> **2024**
>
> - **pAssistant and intag maintenance** *(pAssistant)* — Maintained the Telegram bot with error handling, forwarding, and logging improvements.
> - **Intag README updates** *(intag)* — Updated the README for the Windows Explorer file-tagging utility.
