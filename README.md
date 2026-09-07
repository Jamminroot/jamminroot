## .NET Software Developer, TechLead at Deeplay.io.

### What a time to be alive!

#### [@jamminroot (telegram)](https://t.me/jamminroot), [Dmitrii Chichuk (LinkedIn)](https://linkedin.com/in/dchichuk)

Feel free to reach out!

<!-- ACTIVITY-SUMMARY-START -->
## Recent activity (last 12 months)

*Auto-generated weekly from commit history · updated 2026-09-07*

Built and reworked the core of the Summit crypto algo-trading platform, adding algorithmic copy-trading features, a calm-liquidity rebalancing system, and backtesting infrastructure. Investigated and fixed execution fallbacks, wallet-group vetoes, and Hyperliquid pair resolution.

Developed two new firmware variants for the j-uni-hid ESP32-S3 project (v12 dual-core, v13 USB HID), and shipped a Windows input filter/injection driver (KMDF) with event-level block, integration tests, and a library for high-level control. Also maintained the j-tts-android app, adding new TTS engines (F5-TTS, GPT-SoVITS scaffold) and pitch/speed controls.

Researched crypto price prediction models in the crypto-model-research project, conducting a systematic audit of 11 models, discarding a dozen speculative features, and building a unified benchmark. Refined the Sunflower browser-in-browser project with human-input planning, font-pack handling, and deploy infrastructure.

Iterated on the intag2 Windows Explorer tagging tool, fixing settings persistence, adding Ogg Vorbis comment support, and overhauling CI/CD pipelines. Also worked on the OzWil Android LLM app, rewriting sub-agent architecture and adding KV cache reuse, and the agent-harness Rust project, introducing tenant workspaces, Telegram Secretary, and a graphical control panel.
<!-- ACTIVITY-SUMMARY-END -->

<img src="https://raw.githubusercontent.com/Jamminroot/Jamminroot/master/cards/charts.svg" alt="Activity charts">

<img src="https://raw.githubusercontent.com/Jamminroot/Jamminroot/master/cards/projects.svg" alt="Project cards">

<!-- ACTIVITY-TIMELINE-START -->
> **2026 Sep**
>
> - **Summit backtest and configurator** *(summit)* — Built a backtest configurator and signal rebalance system with calm-liquidity baskets and paper-only signals for the SaaS crypto algo-trading platform.
> - **Sunflower browser-in-browser fixes** *(sunflower)* — Fixed font-pack building, proxy password handling, and unlaunchable profiles in the browser-in-a-browser project.

> **2026 Aug**
>
> - **Summit copy-trading features** *(summit)* — Reworked the copy-trading system: added honest cost estimates, trailing exit sliders, interactive exit simulators, and position peak backfill.
> - **Summit rebalance wallet groups** *(summit)* — Implemented wallet-group veto persistence and calm-liquidity backtest replay on hourly bars for the algo-trading platform.
> - **Crypto model research audit** *(crypto-model-research)* — Conducted a systematic model audit: unified stack protocol sweep, discarded a dozen speculative features, and built a frozen benchmark for the price prediction project.
> - **Intag2 fixes and Vorbis support** *(intag2)* — Fixed settings persistence, Explorer refresh issues, and added Vorbis comment writing for audio files in the Windows file-tagging tool.
> - **Sunflower human input planning** *(sunflower)* — Built gesture-based movement planning, permission prompt handling, and font-pack deployment in the browser-in-a-browser project.
> - **Agent-harness workspace isolation** *(agent-harness)* — Added tenant workspaces, data streams, a graphical Mini App control room, and Telegram Secretary with role-aware controls to the agentic worker project.

> **2026 Jul**
>
> - **Summit rebalance and follows work** *(summit)* — Refined the rebalance system with per-signal fanout and calm-liquidity silence handling, and improved the follows pages with exchange account management.
> - **Freqtrade strategy additions** *(freqtrade_startegies)* — Added several new trading strategies: pack-relative reversion variants and a broad 50-pair universe champion, with forward-tested documentation.

> **2026 Jun**
>
> - **CV automation improvements** *(jamminroot)* — Reworked the CV generation pipeline: added LLM voice enforcement, skills section, and team/throughput metrics to the PDF output.
> - **Jolt hotkey conditions** *(jolt)* — Extended the minimal AutoHotKey alternative with condition evaluation, stateless themes, sound actions, and a debug log.

> **2026 May**
>
> - **J-uni-hid v13 firmware** *(j-uni-hid)* — Developed v13 firmware variant for ESP32-S3 with fire-and-forget event emitting and an 8x8 matrix configuration.
> - **Input driver library and tests** *(input-driver)* — Built a library with start/stop event delivery, an integration-test runner covering all documented capabilities, and relaxed SDDL for the KMDF input driver.
> - **J-TTS Android engine integration** *(j-tts-android)* — Integrated multiple TTS engines including F5-TTS, GPT-SoVITS, and sherpa-onnx with per-voice downloading, plus pitch control for VITS engines.
> - **MEMU3 YOLO inference changes** *(MEMU3)* — Switched GPU inference from CUDA to DirectML, added closed-loop tracking flick and user-input compensation in the computer vision project.
> - **Biscuit firmware expansion** *(biscuit)* — Added a knowledge base app, FB2 reader, screensaver folder, and Mesh Chat fixes to the e-ink device firmware.
> - **CV PDF generation** *(jamminroot)* — Generated CV PDF with pulse charts and project cards, and refined the LLM coverage pipeline for mandatory repos.

> **2026 Apr**
>
> - **J-uni-hid v13 variant and fixes** *(j-uni-hid)* — Drafted a new 8x8 matrix firmware variant and fixed disconnect issues in the v13 USB HID firmware.
> - **Intag2 PDF support and CI** *(intag2)* — Added .pdf to supported file extensions for context menu and fixed changelog generation in the release workflow.
> - **MEMU3 overlay and autofire** *(MEMU3)* — Rewrote the overlay to D3D11+D2D, added HP aim scaling and trigger gate on per-target YOLO confidence, and USB-HID fallback.
> - **FlClash XHTTP support** *(FlClash)* — Added XHTTP transport support and bumped Clash.Meta to re-expose proxy APIs.
> - **Papyrix map and home screen** *(papyrix)* — Added map app with tile viewer, knowledge base with taxonomy browser, and icon-based home screen to the e-ink firmware fork.

> **2026 Mar**
>
> - **J-uni-hid v12 firmware** *(j-uni-hid)* — Developed v12 dual-core firmware variant for the ESP32-S3 HID device.
> - **OzWil Android sub-agent architecture** *(ozwil-android)* — Rewrote the sub-agent architecture with session-based delegation, added KV cache reuse, and built a questionnaire-based model recommendation wizard.
> - **Blackboard launcher overhaul** *(blackboard-launcher)* — Overhauled the E-ink note-taking launcher: redesigned backdrop, added swipe page navigation, and fixed drawing lifecycle issues.
> - **J-tts-android initial engine work** *(j-tts-android)* — Began initial TTS engine integration with contextual homograph disambiguation, endpoint calibration, and session caching.

> **2026 Feb**
>
> - **Intag2 CI pipeline restructuring** *(intag2)* — Restructured CI/CD pipelines for manual triggering and automatic tagging, fixed Store submission issues with PowerShell REST API rewrite.
> - **Jaxon code intelligence engine** *(jaxon)* — Added LSP integration, dead code detection for interface implementations, and incremental sync with freshness detection to the code intelligence engine.
> - **Neovim dotfile configuration** *(.dotfiles)* — Set up a full Neovim IDE configuration with LSP, treesitter, pre-commit hooks, and OSC 52 clipboard for remote sessions.
> - **YOLO labeler creation** *(yolo-labeler)* — Built a fast on-host YOLO labeler with multi-select mark mode, flexible YAML resolution, and Ctrl+Delete entry deletion.

> **2026**
>
> - **Summit core and copy-trading** *(summit)* — Continued major work on the Summit algo-trading platform: built copy-trading features, rebalance systems, and algorithmic strategy catalog throughout the year.
> - **J-uni-hid firmware development** *(j-uni-hid)* — Developed multiple firmware versions (v9-v13) for ESP32-S3 with BLE, USB touch, and performance mode features.
> - **Crypto model research** *(crypto-model-research)* — Conducted extensive model research with a catalog of 11 models, unified protocol, and live-drift monitoring throughout the year.
> - **OzWil Android app** *(ozwil-android)* — Built and refined the on-device LLM app with phone-use capabilities, sub-agent delegation, and multiple model support.
> - **Intag2 and Intag tagging tools** *(intag2)* — Maintained the Windows Explorer file-tagging tools with metadata support, CI improvements, and Microsoft Store submission fixes.
> - **Agent-harness Rust project** *(agent-harness)* — Developed the JAW agentic worker with Telegram integration, memory retrieval, and a graphical control panel.
> - **N8n nodes and automations** *(n8n-nodes-telepilot-2)* — Fixed auth race conditions, upgraded CI, and added album trigger for Telegram node in n8n.

> **2025**
>
> - **Poker CV pet project** *(poker-cv)* — Built computer vision pipeline for online poker: hand detection, log reconstruction, and CV recovery module.
> - **Freqtrade bot ecosystem** *(freqtrade-tg-multibot)* — Developed multi-bot Telegram management with Docker support, daily profit calculations, and authentication handling.
> - **Auto-Claude multi-session AI** *(auto-claude)* — Implemented Git rules system, squash-merge completion tracking, and task ID management for the autonomous AI coding tool.
> - **Android TTS and assistant tools** *(pAssistant)* — Maintained the personal Telegram assistant and pAssistant2 with summarization, image dedup, and multi-target sending.
> - **Trading strategy development** *(freqtrade_startegies)* — Developed and optimized numerous trading strategies with backtesting and parameter tuning throughout the year.
> - **J-tts-android initial release** *(j-tts-android)* — Initial TTS evaluation engine release with Vosk, Silero, and Piper engines for Russian speech synthesis.
> - **N8n nodes and telepilot** *(n8n-nodes-telepilot-2)* — Initial deployment setup and Alpine Linux support for Telegram integration nodes.
<!-- ACTIVITY-TIMELINE-END -->

[**Download CV (PDF)**](https://raw.githubusercontent.com/Jamminroot/Jamminroot/master/cards/cv.pdf)
