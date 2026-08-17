## Recent activity (last 12 months)

*Auto-generated weekly from commit history · updated 2026-08-17*

I've been deeply focused on two major projects. First, building Summit—a full SaaS crypto algo-trading platform with AI and neural-network components—where I've been working across the entire stack: the trading engine, risk management, onboarding, admin panels, charting, and a Telegram-based auth flow. The recent weeks saw a large refactor of the guard/protection system, consolidating risk settings into a universal catalogue, adding account-wide loss budgets, and giving strategies their own timing overrides. Second, I've been developing J-UNI-HID, a feature-rich mouse and keyboard emulation firmware for the ESP32-S3, pushing through multiple firmware variants (v10–v13) with USB/BLE hybrid support, touch on Android, and mouse on macOS. On the side, I've contributed to the input-driver project—a Windows KMDF input filter driver for capture and injection—and to crypto-model-research, where I've been iterating on a price-prediction model, moving from experiment tracking to forward-testing and ONNX deployment. Other notable work includes revamping the Intag2 file-tagging utility for Windows Explorer with Vorbis comments and CI/CD pipeline fixes, building out the OzWil Android app (an LLM with phone-use capabilities) with sub-agent tool execution and model routing, and tangentially maintaining projects like J-TTS Android (multi-engine TTS), poker-cv (computer vision for poker hand detection), and the jamminroot meta-repo (CV generation pipeline).
> **2026 Aug**
>
> - **Trading platform risk and onboarding** *(summit)* — Refactored the guard/protection system into a universal catalogue; added account-wide loss budgeting and strategy-level timing overrides; built risk slider onboarding and Telegram-based sign-in flow.
> - **Distributed agent worker tooling** *(agent-harness)* — Built a macOS personal agent with UI tree reading, screenshot capture, device control, and Screen Recording permissions—runs as a login agent.

> **2026 Jul**
>
> - **Price prediction model productionization** *(crypto-model-research)* — Forward-tested and validated a 13-feature champion model achieving 77-90% WR; exported the Split-MoE ensemble to ONNX for integration with Summit.
> - **File tagging utility for Windows Explorer** *(intag2)* — Added Vorbis comment writing for .ogg/.oga/.opus files; fixed silent metadata write failures and shell extension uninstall paths; collapsed CI into single workflow and bumped version to 2.5.

> **2026 Jun**
>
> - **CV generation pipeline automation** *(jamminroot)* — Revised the CV-generation pipeline with first-person voice enforcement, LLM model override support, and improved PDF output with skills section and role breakdowns.
> - **Lightweight input automation tool** *(jolt)* — Built a minimal AutoHotKey alternative with a scenario engine, rule-based conditions, stateless themes, sound actions, and Interception support for input gate.

> **2026 May**
>
> - **Firmware variants for ESP32-S3** *(j-uni-hid)* — Pushed v13 firmware with fire-and-forget USB HID events and 8x8 matrix variant; fixed DC disconnection and added graceful COM restart for the dual-core v12 release.
> - **Windows input filter driver** *(input-driver)* — Released v1.2.2 of the KMDF input driver with an integration-test runner, push-style event delivery API, and SDDL relaxation for Interactive Users.
> - **Multi-engine Android TTS app** *(j-tts-android)* — Added pitch and speed sliders, question/exclamation intonation control, wired Vosk + Silero with endpoint quality tuning, and integrated TeraTTS and Piper engines with Kotlin G2P.

> **2026 Apr**
>
> - **E-ink reader custom firmware** *(papyrix)* — Added Knowledge Base, Map app, and FB2 encoding support to the Papyrix fork; optimized map rendering for Apple Silicon and built tile and book processing scripts.
> - **VR aim-assist and overlay tool** *(MEMU3)* — Reworked the aim-assist module with YOLO confidence thresholds, DirectML GPU inference, and USB-HID fallback; rewrote overlay using D3D11 + DComp.

> **2026 Mar**
>
> - **LLM phone-use agent app** *(ozwil-android)* — Rewrote the sub-agent architecture with session-based delegation and tool execution; added model routing strategies, questionnaire-based setup wizard, and background service with wake detection.
> - **Crypto price model experiments** *(crypto-model-research)* — Ran 11+ experiments including FFT frequency decomposition for MoE gates, snapshot ensembles, and variable selection—split up/down MoE gates became the new champion.
> - **Knowledge base and map features for e-reader** *(papyrix)* — Added FB2 encoding support (windows-1251/KOI8-R), context menu for file deletion, and a landscape Map app with tile viewer and region selection.

> **2026 Feb**
>
> - **Windows file tagging utility v2 release** *(intag2)* — Prepared v2.4–2.5 releases with MS Store CI pipeline, CLI support, folder tag editing, and PDF context menu support; restructured CI workflows for manual triggering and auto-drafting releases.
> - **Graph-powered code intelligence engine** *(jaxon)* — Added LSP integration for language-server-powered analysis, incremental index sync, expanded DI registration detection, and dead code analysis for C++, Go, Rust, and Svelte.
> - **Neovim dotfiles and secret management** *(.dotfiles)* — Set up a full Neovim IDE configuration with LSP, Treesitter, Mason, and telescope; added pre-commit hooks for secret detection and SSH key management via chezmoi.
> - **Telegram bot n8n node fixes** *(n8n-nodes-telepilot-2)* — Fixed auth race conditions, upgraded CI to n8n 2.8.3, and added a new album trigger for the Telegram pilot node.

> **2026 Jan**
>
> - **Firmware v11 for ESP32-S3** *(j-uni-hid)* — Developed v11 firmware with self-reporting, configurable performance profiles, safe BLE pairing, and reduced heat via throttling; fixed Android reconnect and touch jitter issues.
> - **Poker hand detection via computer vision** *(poker-cv)* — Built a CV pipeline for online poker platforms; achieved 99% hand detection and 97.8% board card accuracy with state recovery, log reconstruction, and validation metrics.
> - **Telegram bot for Claude Code** *(n8n-nodes-claudecode)* — Migrated to the Claude Agent SDK, added Haiku model support, and fixed abort controller cleanup for the n8n Claude Code node.

> **2025**
>
> - **Trading bot monitoring and strategies** *(freqtrade-tg-multibot)* — Worked on a Telegram-based multi-bot monitoring dashboard for Freqtrade—improved authentication, daily profit calculations, and Docker/web deployment setup.
> - **Telegram content collector and multi-target sending** *(pAssistant)* — Maintained a Telegram automation tool; added multi-target channel sending for separating memes and news, image deduplication, and summarization features for repost indices.
> - **Auto-coding agent with git workflow automation** *(auto-claude)* — Built an autonomous multi-session AI coding agent; implemented squash merging, git rules system, task ID tracking, and completion detection across worktrees.
> - **Trading strategies development and optimization** *(freqtrade_startegies)* — Developed multiple cryptocurrency trading strategies (EwoDip15m series, PackRelReversion15m, BtcRelReversion15m) with backtesting and forward-test results achieving 73-78% win rates.

> **2024**
>
> - **Telegram bot foundations and refactoring** *(pAssistant)* — Continued maintenance on the Telegram assistant bot—added content forwarding fixes, session state handling, and minor refactoring across the pipeline.
