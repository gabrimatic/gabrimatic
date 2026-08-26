<p align="center">
  <img src="assets/gabrimatic-banner-1500x500.png" alt="@Gabrimatic banner" width="100%">
</p>

# Hi, I'm Soroush

Mobile engineer and tech lead. I ship across Android, iOS, web, and desktop. Native Android and iOS came first; Flutter has been part of my production work since 2019.

At **[Affinidi](https://www.affinidi.com/)**, I work on the Internet of Trust: verifiable credentials, DIDComm, an agentic AI trust gateway, and Dart SDKs. At **[City-Flock](https://www.city-flock.de/en)**, I build a community safety app that matches people travelling in the same direction to make everyday journeys safer.

Most evenings, I build local LLM tools: MLX experiments, on-device voice, terminal tools, and small systems that keep inference close to the machine.

![Flutter](https://img.shields.io/badge/-Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/-Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![Swift](https://img.shields.io/badge/-Swift-FA7343?style=flat-square&logo=swift&logoColor=white)
![Kotlin](https://img.shields.io/badge/-Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![MLX](https://img.shields.io/badge/-MLX-000000?style=flat-square&logo=apple&logoColor=white)
![macOS](https://img.shields.io/badge/-macOS-000000?style=flat-square&logo=apple&logoColor=white)

## What I Build

### On-device AI

- **[local-whisper](https://github.com/gabrimatic/local-whisper)** - on-device voice transcription with grammar correction and TTS for private voice workflows.
- **[ocr-capture](https://github.com/gabrimatic/ocr-capture)** - select any screen region, get the text on your clipboard. Apple Vision OCR, fully on-device.
- **eyra** - real-time screen analysis with voice interaction. It routes between models when the task changes. Not public yet.
- **[kokoro-mlx](https://github.com/gabrimatic/kokoro-mlx)** - Kokoro-82M text-to-speech running on-device via MLX.
- **[qwen3-asr-mlx](https://github.com/gabrimatic/qwen3-asr-mlx)** - Qwen3-ASR speech-to-text running on-device via MLX.
- **[threadstone](https://github.com/gabrimatic/threadstone)** - offline terminal chat for local LLMs. Multiple instances, no dependencies.
- **[personal_ollama_cli](https://github.com/gabrimatic/personal_ollama_cli)** - terminal sessions for local Ollama models, with context and persistence.

### Flutter & Dart

- **[restart_app](https://github.com/gabrimatic/restart_app)** - restart Flutter apps from one call across Android, iOS, Web, macOS, Linux, and Windows.
- **[passes_box](https://github.com/gabrimatic/passes_box)** - offline password manager with AES-256 and biometric auth. No network path.
- **[otp_auth](https://github.com/gabrimatic/otp_auth)** - HOTP and TOTP one-time passwords for Dart.
- **[ollama_flutter_gui](https://github.com/gabrimatic/ollama_flutter_gui)** - Flutter Web GUI for local Ollama models.
- **[graphql_fragment_builder](https://github.com/gabrimatic/graphql_fragment_builder)** - type-safe GraphQL fragment and query builder for Dart.
- **[persian_datetimepickers](https://github.com/gabrimatic/persian_datetimepickers)** - Persian and Gregorian date/time pickers.
- **[center_the_widgets](https://github.com/gabrimatic/center_the_widgets)** - keeps mobile-first layouts readable on web and large screens.
- **[flutter_chrome_extension](https://github.com/gabrimatic/flutter_chrome_extension)** - Chrome extension built with Flutter Web.
- **[more packages](https://pub.dev/publishers/gabrimatic.info/packages)**

### Agents & MCP

- **[tmux-mcp](https://github.com/gabrimatic/tmux-mcp)** - tmux-backed MCP server that gives AI agents a persistent, human-attachable terminal.
- **[mcp-web-search-tool](https://github.com/gabrimatic/mcp-web-search-tool)** - MCP server that lets AI models search the web in real time ([demo](https://youtu.be/6jAnjJSCL30)).
- **[mcp-prose-memory](https://github.com/gabrimatic/mcp-prose-memory)** - MCP server for persistent memory with JSON storage and atomic fact operations.
- **[copilot-goal-system](https://github.com/gabrimatic/copilot-goal-system)** - goal mode for GitHub Copilot CLI: persisted state, drift blocking, proof-based completion.
- **[agent-flight-recorder](https://github.com/gabrimatic/agent-flight-recorder)** - black-box recorder for coding-agent code changes.

## Upstream

Fixes I've landed in the tools I build on.

Merged into **[flutter/flutter](https://github.com/flutter/flutter/pulls?q=is%3Apr+author%3Agabrimatic+is%3Amerged)**:

- [#185789](https://github.com/flutter/flutter/pull/185789) - tolerate floating-point rounding in the `paintImage` center-slice assertion
- [#186993](https://github.com/flutter/flutter/pull/186993) - fix the `NestedScrollView` example crash when switching desktop tabs
- [#186348](https://github.com/flutter/flutter/pull/186348) - support custom `BoxBorder` animation in `BoxDecoration`
- [#185791](https://github.com/flutter/flutter/pull/185791) - recognize `package:stack_trace` async-gap markers as asynchronous suspension
- [#185793](https://github.com/flutter/flutter/pull/185793) - fix an OverlayPortal owner-mismatch crash inside deferred-mount parents like Table
- [#185875](https://github.com/flutter/flutter/pull/185875) - stop the Cubic transform looping on out-of-range input
- [#186116](https://github.com/flutter/flutter/pull/186116) - fix semantics order for nested Text.rich spans
- [#186329](https://github.com/flutter/flutter/pull/186329) - disable spell check for obscured text

On 26 August 2026, [#185789](https://github.com/flutter/flutter/pull/185789) reached the tip of Flutter's `master` branch. The official repository homepage showed `gabrimatic` as its latest contributor; the temporary state is preserved in [two independent web archives](https://gabrimatic.github.io/flutter-sdk-contributions/).

Merged into **[warpdotdev/warp](https://github.com/warpdotdev/warp/pulls?q=is%3Apr+author%3Agabrimatic+is%3Amerged)**:

- [#10174](https://github.com/warpdotdev/warp/pull/10174) - forward CLI agent env vars into WSL
- [#10178](https://github.com/warpdotdev/warp/pull/10178) - reserve titlebar space for window controls

## Now

*Updated July 2026.*

- Building safer digital identity at **[Affinidi](https://www.affinidi.com/)** and safer everyday journeys at **[City-Flock](https://www.city-flock.de/en)**
- Building local AI tools around MLX, voice, and on-device inference
- Maintaining Flutter and Dart packages on [pub.dev](https://pub.dev/publishers/gabrimatic.info/packages)
- Keeping [gabrimatic.info](https://gabrimatic.info) as the public home for the work

## Connect

[![Website](https://img.shields.io/badge/-gabrimatic.info-FF5722?style=flat-square&logo=About.me&logoColor=white)](https://gabrimatic.info)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/gabrimatic)
[![Twitter](https://img.shields.io/badge/-@gabrimatic-000000?style=flat-square&logo=x&logoColor=white)](https://twitter.com/gabrimatic)
[![Medium](https://img.shields.io/badge/-@gabrimatic-12100E?style=flat-square&logo=medium&logoColor=white)](https://medium.com/@gabrimatic)
[![pub.dev](https://img.shields.io/badge/-pub.dev-02569B?style=flat-square&logo=dart&logoColor=white)](https://pub.dev/publishers/gabrimatic.info/packages)
[![Gists](https://img.shields.io/badge/-Gists-181717?style=flat-square&logo=github&logoColor=white)](https://gist.github.com/gabrimatic)
[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/gabrimatic)

## Beyond code

- Photography, mostly when I leave the keyboard.
- Worked in bookstores for two years. Books stayed with me.
- Cinema. Film theory and storytelling.
