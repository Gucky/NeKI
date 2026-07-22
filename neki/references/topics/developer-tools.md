# Developer Tools

Third-party reading leads collected from NeKI sources. The links may be useful perspectives, but are not vetted recommendations or authoritative API guidance. NeKI publishes routing metadata, not the linked articles' text.

**Scope:** Git, command-line work, debugging, automation, and practical developer workflows.

- Last collected: `2026-07-22T21:56:49Z`
- Indexed links shown: **1011**

## Direct-source reading

- [Use 'git mv' to record filename case changes in Git – Ole Begemann](https://oleb.net/2025/git-mv-case-change) — Ole Begemann · article catalogue
  **Published:** `2025-12-16T17:11:22Z`
  **NeKI brief:** Demonstrates that case-only filename changes on case-insensitive filesystems need an explicit git mv so Git records the rename. The two-stage workaround is a compact diagnostic for apparently ignored path changes.
- [Tracking renamed files in Git – Ole Begemann](https://oleb.net/2025/git-file-renaming) — Ole Begemann · article catalogue
  **Published:** `2025-12-15T15:51:35Z`
  **NeKI brief:** Explains when git mv preserves rename history and when Git's similarity detection is sufficient, using concrete repository examples. It helps choose a transparent rename workflow instead of relying on index heuristics.
- [Proxyman iOS Debugging - Capture HTTPS and Mock API Responses](https://fatbobman.com/en/posts/using-proxyman-to-intercept-and-simulate-iphone-app-network-requests) — Fatbobman · article catalogue
  **Published:** `2025-03-19T14:30:00.000Z`
  **NeKI brief:** Shows using Proxyman to capture HTTPS traffic, install certificates, map local responses, and mock APIs. Use it to reproduce network scenarios without changing a production server.
- [Why you should keep your git commits small and meaningful – Donny Wals](https://www.donnywals.com/why-you-should-keep-your-git-commits-small-and-meaningful) — Donny Wals · article catalogue
  **Published:** `2025-02-19T16:00:18+00:00`
  **NeKI brief:** Small commits preserve reviewable intent and make rollback or bisecting practical, though overly fragmented history can obscure a feature's cohesive change.
- [Hardcore Debugging](https://blog.jacobstechtavern.com/p/hardcore-debugging) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2025-01-13T17:15:57.444Z`
  **NeKI brief:** Presents a systematic debugging workflow that moves from symptom reproduction through instrumentation, hypothesis testing, and minimized evidence, helping engineers isolate root causes rather than repeatedly patching visible failures.
- [Typefully - Say Goodbye to the Hassles of Social Media Posting](https://fatbobman.com/en/posts/typefully-say-goodbye-to-the-hassles-of-social-media-posting) — Fatbobman · article catalogue
  **Published:** `2024-12-04T00:12:00.000Z`
  **NeKI brief:** Typefully's workflow demonstrates composing text editing, scheduling, and service integration into a focused product. Follow it for a concrete example of separating domain actions from platform-specific publishing APIs.
- [THE CRASH IS A LIE](https://blog.jacobstechtavern.com/p/what-is-a-crash) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2024-11-04T17:15:56.192Z`
  **NeKI brief:** Treat a crash as a diagnostic signal from the runtime, kernel, or app termination path rather than a single failure category. Capture symbolicated reports, distinguish memory and assertion failures from watchdog termination, and reproduce the triggering lifecycle or concurrency conditions before changing code.
- [Connecting your git repository with a remote server – Donny Wals](https://www.donnywals.com/connecting-your-git-repository-with-a-remote-server) — Donny Wals · article catalogue
  **Published:** `2024-01-18T15:52:44+00:00`
  **NeKI brief:** Adding a remote links local history to a shared server endpoint, but authentication, branch tracking, and push scope must be verified before collaboration begins.
- [Understanding and resolving merge conflicts – Donny Wals](https://www.donnywals.com/understanding-and-resolving-merge-conflicts) — Donny Wals · article catalogue
  **Published:** `2024-01-10T11:03:22+00:00`
  **NeKI brief:** Merge conflicts are resolved by reconstructing intended changes around a shared base, then testing the combined behavior instead of mechanically accepting one side.
- [Git basics for iOS developers – Donny Wals](https://www.donnywals.com/git-basics-for-ios-developers) — Donny Wals · article catalogue
  **Published:** `2024-01-03T15:45:31+00:00`
  **NeKI brief:** Git fundamentals frame commits, branches, and history as recoverable experiments, helping iOS teams isolate feature work before integration and release.
- [Handling multiple git SSH keys](https://www.polpiella.dev/handling-multiple-git-ssh-keys) — Pol Piella · article catalogue
  **Published:** `2022-09-27T00:00:00.000Z`
  **NeKI brief:** Multiple Git SSH keys are selected through host aliases and explicit configuration. The guide is useful for separating personal and work identities, while keeping private key material outside repositories and build logs.
- [Quick guide on Charles Proxy for iOS development](https://tanaschita.com/tools-charles-proxy-for-ios-guide) — Tanaschita · article catalogue
  **NeKI brief:** Shows Charles as an inspection and fault-injection proxy for simulator or device traffic, including trusted certificates for HTTPS, session views, request/response inspection, and simulated slow networking. Use it to diagnose transport behavior while keeping proxy trust confined to development.
- [Introduction to bash scripting for iOS developers](https://tanaschita.com/20231023-bash-scripting-for-ios-devs) — Tanaschita · article catalogue
  **NeKI brief:** Bash scripting examples automate repeatable iOS development tasks outside Xcode. The useful boundary is treating arguments, exit codes and environment variables as a stable tool contract rather than a shell-only convenience.
- [Handling Storyboard Merge Conflicts](https://martiancraft.com/blog/2018/02/handling-storyboard-merge-conflicts) — MartianCraft · article catalogue
  **NeKI brief:** Storyboard XML conflicts are resolved by understanding scene and constraint identifiers, then checking the rendered graph rather than blindly accepting textual hunks. The workflow reduces broken navigation and Auto Layout relationships after parallel UI edits.

## Newsletter and related leads

- [ImplementedSE-0525Safe loading API for `RawSpan`](https://github.com/apple/swift-evolution/blob/main/proposals/0525-rawspan-safe-loading-api.md) — SwiftLee Weekly · Issue 323 — Source repository · Topics: Architecture · Developer Tools · Swift
  **Published:** `2026-07-21T14:05:55.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0525Safe loading API for `RawSpan`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [MistKit](https://github.com/brightdigit/MistKit) — iOS Dev Tools · iOS Dev Tools: MistKit, Swift Scribe, cmux — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2026-07-16T16:45:11.086Z`
  **NeKI brief:** MistKit packages CloudKit Web Services access for server-side Swift and command-line tools, separating backend automation from Apple's client frameworks. Useful when a service needs CloudKit data without running inside an iOS app.
- [Swift Scribe](https://github.com/FluidInference/swift-scribe) — iOS Dev Tools · iOS Dev Tools: MistKit, Swift Scribe, cmux — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `2026-07-16T16:45:11.086Z`
  **NeKI brief:** Swift Scribe combines local microphone transcription with on-device summarization on current Apple OS releases, without external dependencies. Useful for evaluating a privacy-preserving speech pipeline and its deployment-version constraints.
- [cmux](https://github.com/manaflow-ai/cmux) — iOS Dev Tools · iOS Dev Tools: MistKit, Swift Scribe, cmux — Source repository · Topics: AI Development · Developer Tools · Product Design
  **Published:** `2026-07-16T16:45:11.086Z`
  **NeKI brief:** cmux is a Ghostty-based macOS terminal organized around vertical tabs, notifications, and programmable agent workflows. Useful for evaluating a terminal layout that keeps multiple coding-agent sessions visible and actionable.
- [agent-browser](https://github.com/vercel-labs/agent-browser) — iOS Dev Tools · iOS Dev Tools: MistKit, Swift Scribe, cmux — Source repository · Topics: Developer Tools · Product Design
  **Published:** `2026-07-16T16:45:11.086Z`
  **NeKI brief:** agent-browser exposes browser automation through a CLI designed for AI agents, giving scripts navigation, interaction, and inspection primitives. Useful for comparing deterministic command workflows with bespoke browser-control integrations.
- [Swift Bits: My Top Xcode CI Environment Variables](https://antongubarenko.substack.com/p/swift-bits-my-top-xcode-ci-environment) — Those Who Swift · Issue 275 — Article · Topics: Developer Tools · Swift · Xcode
  **Published:** `2026-07-15`
  **NeKI brief:** Collects Xcode-related environment variables that can make CI jobs more predictable and diagnosable. Follow it when hardening build scripts, while checking each variable against the project's Xcode version and the behavior of its hosted runners.
- [Fastlane alternative - Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — SwiftLee Weekly · Issue 322 — Source repository · Topics: CI/CD & Automation · Developer Tools
  **Published:** `2026-07-14T14:06:22.000Z`
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [TourKit](https://github.com/rampatra/TourKit) — iOS Dev Tools · iOS Dev Tools: TourKit, MockingKit, MemoryMap — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2026-07-09T16:30:20.398Z`
  **NeKI brief:** TourKit implements Apple-style onboarding tours for Mac and iPhone apps, providing guided highlights over application UI. Useful when a product needs contextual feature discovery instead of a sequence of static introduction screens.
- [MockingKit](https://github.com/danielsaidi/MockingKit) — iOS Dev Tools · iOS Dev Tools: TourKit, MockingKit, MemoryMap — Source repository · Topics: Dependency Injection · Developer Tools · Swift
  **Published:** `2026-07-09T16:30:20.398Z`
  **NeKI brief:** MockingKit generates or supplies mock implementations for Swift protocols and classes, reducing hand-written test doubles. Useful for isolating collaborators while comparing generated convenience against explicit, behavior-focused test seams.
- [MemoryMap](https://github.com/naftaly/MemoryMap) — iOS Dev Tools · iOS Dev Tools: TourKit, MockingKit, MemoryMap — Source repository · Topics: Developer Tools · Persistence & Synchronisation · Swift
  **Published:** `2026-07-09T16:30:20.398Z`
  **NeKI brief:** MemoryMap persists plain-old-data Swift structs through memory-mapped files, emphasizing efficient access and crash-resilient storage. Useful for large fixed-layout local data where serialized object graphs would add unnecessary overhead.
- [QuotaWarmer](https://github.com/bcanozgur/quota-warmer) — iOS Dev Tools · iOS Dev Tools: TourKit, MockingKit, MemoryMap — Source repository · Topics: Developer Tools
  **Published:** `2026-07-09T16:30:20.398Z`
  **NeKI brief:** QuotaWarmer monitors Claude Code and Codex CLI quota windows from a macOS menu bar app and sends scheduled warmups. Useful for examining automation around rate-limit windows, with clear policy and account-usage implications.
- [cctop](https://cctop.app/) — iOS Dev Tools · iOS Dev Tools: TourKit, MockingKit, MemoryMap — Article · Topics: AI Development · Developer Tools · macOS & AppKit
  **Published:** `2026-07-09T16:30:20.398Z`
  **NeKI brief:** cctop is a macOS menu-bar utility for monitoring and managing Claude Code sessions. It is useful for keeping agent activity visible during development, especially when several terminal sessions compete for attention.
- [Lidless](https://github.com/nghialuong/Lidless) — iOS Dev Tools · iOS Dev Tools: TourKit, MockingKit, MemoryMap — Source repository · Topics: Developer Tools · macOS & AppKit · Personal Essays
  **Published:** `2026-07-09T16:30:20.398Z`
  **NeKI brief:** Lidless keeps a Mac running with its lid closed, targeting unattended coding-agent workflows from the menu bar. Useful for evaluating laptop clamshell automation while considering thermal, power, and security trade-offs.
- [Debugging Notes on Two SwiftUI Animation Bugs](https://fatbobman.com/en/posts/debugging-notes-on-two-swiftui-animation-bugs) — SwiftLee Weekly · Issue 331 — Article · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2026-07-07T14:05:55.000Z`
  **NeKI brief:** Uses two concrete SwiftUI animation failures to show how declarative animation can obscure causality. Follow it when a transition or state-driven animation misbehaves and you need diagnostic observations that reveal the framework behaviour rather than only a workaround.
- [AcceptedSE-0513API to get the path to the current executable](https://github.com/apple/swift-evolution/blob/main/proposals/0513-commandline-executablepath.md) — SwiftLee Weekly · Issue 331 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2026-07-07T14:05:55.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0513API to get the path to the current executable. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Swift Algorithms & Data Structures](https://waynewbishop.github.io/swift-algorithms) — Fatbobman’s Swift Weekly · Issue 143 — Article · Topics: AI Development · Developer Tools · Swift
  **Published:** `2026-07-06T12:03:13.020Z`
  **NeKI brief:** Collects Swift algorithms and data-structure examples in runnable form, making it useful for comparing standard-library techniques, complexity trade-offs, and interview-style implementations before introducing custom utilities.
- [SiteKit](https://github.com/FlineDev/SiteKit) — iOS Dev Tools · iOS Dev Tools: Apple App Store Scraper, SideScreen, SiteKit — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `2026-07-02T19:03:32.109Z`
  **NeKI brief:** SiteKit is an AI-first static-site generator implemented in Swift, turning structured project input into web output. Useful for exploring a native Swift publishing pipeline rather than adding a JavaScript toolchain.
- [Mimir](https://github.com/erayendes/mimir) — iOS Dev Tools · iOS Dev Tools: Apple App Store Scraper, SideScreen, SiteKit — Source repository · Topics: AI Development · Developer Tools
  **Published:** `2026-07-02T19:03:32.109Z`
  **NeKI brief:** Mimir tracks AI coding-assistant usage limits in the macOS menu bar for services such as Claude and Codex. Useful for monitoring multiple quota sources without repeatedly opening provider dashboards.
- [OpenUsage](https://github.com/robinebers/openusage) — iOS Dev Tools · iOS Dev Tools: Apple App Store Scraper, SideScreen, SiteKit — Source repository · Topics: AI Development · App Distribution & Store Operations · Developer Tools
  **Published:** `2026-07-02T19:03:32.109Z`
  **NeKI brief:** OpenUsage presents subscription and usage information in an open-source desktop utility, helping users see where recurring services are being consumed. Useful as a reference for local usage aggregation and transparent cost awareness.
- [BLEUnlock](https://github.com/ts1/BLEUnlock) — iOS Dev Tools · iOS Dev Tools: Apple App Store Scraper, SideScreen, SiteKit — Source repository · Topics: Developer Tools · macOS & AppKit
  **Published:** `2026-07-02T19:03:32.109Z`
  **NeKI brief:** BLEUnlock uses Bluetooth LE proximity devices such as an iPhone or Apple Watch to lock and unlock a Mac. Useful for studying a practical CoreBluetooth-to-macOS security workflow and its trust-boundary limitations.
- [Atoll](https://github.com/Ebullioscopic/Atoll) — iOS Dev Tools · iOS Dev Tools: Apple App Store Scraper, SideScreen, SiteKit — Source repository · Topics: Developer Tools
  **Published:** `2026-07-02T19:03:32.109Z`
  **NeKI brief:** Atoll recreates a Dynamic-Island-style surface for macOS, exposing transient status and interaction affordances around the display cutout area. Useful for experimenting with unobtrusive desktop status UI and window positioning.
- [ImplementedSE-0528`Continuation` — Safe and Performant Async Continuations](https://github.com/apple/swift-evolution/blob/main/proposals/0528-noncopyable-continuation.md) — SwiftLee Weekly · Issue 330 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2026-06-30T14:07:37.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0528`Continuation` — Safe and Performant Async Continuations. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0534Opt-in exact matching for version identifiers with build metadata](https://github.com/apple/swift-evolution/blob/main/proposals/0534-swiftpm-exact-literal-version-matching.md) — SwiftLee Weekly · Issue 330 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2026-06-30T14:07:37.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0534Opt-in exact matching for version identifiers with build metadata. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [patch-swift](https://github.com/patch-release/patch-swift) — Fatbobman’s Swift Weekly · Issue 142 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2026-06-29T12:03:26.222Z`
  **NeKI brief:** patch-swift explores compiling Swift to WebAssembly and hot-updating views through dynamic replacement and serializable descriptions. Use it to study the toolchain and runtime constraints behind a SwiftUI-like web update model.
- [Your iOS Builds Deserve Better](https://go.macstadium.com/build-faster-with-orka) — iOS Dev Weekly · Issue 756 — Article · Topics: Developer Tools
  **Published:** `26th June 2026`
  **NeKI brief:** MacStadium's Orka overview describes API- and CLI-driven Apple-silicon virtual machines for CI, testing, and agent workflows. Use it to evaluate elastic macOS capacity against cost, isolation, Kubernetes integration, and reproducible build requirements.
- [Footprint](https://github.com/naftaly/Footprint) — iOS Dev Tools · iOS Dev Tools: Footprint, ZMarkupParser, Lettera — Source repository · Topics: Apple Platform Ecosystem · Developer Career & Practice · Developer Tools
  **Published:** `2026-06-18T16:02:35.381Z`
  **NeKI brief:** Footprint exposes app and system memory pressure as normal, warning, urgent, critical, and terminal states, with a 500-ms heartbeat and AsyncStream updates. SwiftUI modifiers let an app adapt before memory warnings arrive too late.
- [ZMarkupParser](https://github.com/ZhgChgLi/ZMarkupParser) — iOS Dev Tools · iOS Dev Tools: Footprint, ZMarkupParser, Lettera — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `2026-06-18T16:02:35.381Z`
  **NeKI brief:** A pure-Swift HTML-to-NSAttributedString parser that repairs malformed markup, supports custom tags and styles, and can render, strip, or select content. Its thread-safe implementation and performance report make it a concrete alternative to Foundation HTML parsing.
- [Drafty](https://www.brrai.nz/products/drafty) — iOS Dev Tools · iOS Dev Tools: Footprint, ZMarkupParser, Lettera — Article · Topics: Developer Tools
  **Published:** `2026-06-18T16:02:35.381Z`
  **NeKI brief:** Drafty is a writing workspace designed to help turn rough ideas into organized text. It is relevant as a lightweight product-writing tool, but evaluate its export, privacy, and collaboration behavior before adopting it for project documentation.
- [Build a Swift Terminal Developer Toolkit with TUIkit](https://www.youtube.com/watch?v=hqDurFnEJs8) — Those Who Swift · Issue 271 — Video · Topics: Developer Tools · Swift · UIKit
  **Published:** `2026-06-18`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Stop configuring MCPs in every AI app](https://www.mcp-beast.ai/mac-app-ios-developers) — SwiftLee Weekly · Issue 328 — Article · Topics: AI Development · Developer Tools · Persistence & Synchronisation
  **Published:** `2026-06-16T14:06:32.000Z`
  **NeKI brief:** Explores centralizing MCP configuration so multiple AI clients can share one setup. Use it when reducing repeated tool registration across development environments, while reviewing credential handling and client-specific capability differences.
- [Release 4.0.0 · AvdLee/SwiftUI-Agent-Skill](https://github.com/AvdLee/SwiftUI-Agent-Skill/releases/tag/4.0.0) — SwiftLee Weekly · Issue 328 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2026-06-16T14:06:32.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Release 4.0.0 · AvdLee/SwiftUI-Agent-Skill. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Skill](https://github.com/superwall/skills) — Fatbobman’s Swift Weekly · Issue 140 — Source repository · Topics: AI Development · Developer Tools
  **Published:** `2026-06-15T12:03:17.597Z`
  **NeKI brief:** Superwall Skills packages Apple developer-update summaries and an assistant-facing skill for fast onboarding. Use it when an agent needs curated WWDC context, while verifying implementation decisions against official session or API sources.
- [iOS/MacOS: Apple Beta Doc Retriever](https://github.com/0Itsuki0/iOS-MacOS_AppleBetaDocRetriever) — Fatbobman’s Swift Weekly · Issue 140 — Source repository · Topics: Developer Tools
  **Published:** `2026-06-15T12:03:17.597Z`
  **NeKI brief:** AppleBetaDocRetriever collects iOS and macOS beta documentation for offline or searchable reference. Use it when beta APIs change quickly and you need a local comparison aid, while treating Apple's live documentation as authoritative.
- [Container 1.0](https://github.com/apple/container) — Fatbobman’s Swift Weekly · Issue 140 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2026-06-15T12:03:17.597Z`
  **NeKI brief:** Apple Container provides container tooling for macOS development environments. Use it when isolating builds or services on Apple Silicon, while checking runtime constraints and image compatibility before replacing existing VM or CI workflows.
- [EnableMacosAI](https://github.com/SkyBlue997/enableMacosAI) — Fatbobman’s Swift Weekly · Issue 140 — Source repository · Topics: AI Development · Developer Tools · macOS & AppKit
  **Published:** `2026-06-15T12:03:17.597Z`
  **NeKI brief:** EnableMacosAI documents a workaround for making Apple Intelligence features available in unsupported macOS environments. Treat it as experimental configuration research, not a supported deployment approach or substitute for official eligibility requirements.
- [Active ReviewSE-0516`Iterable`](https://github.com/apple/swift-evolution/blob/main/proposals/0516-borrowing-sequence.md) — SwiftLee Weekly · Issue 327 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools · Swift
  **Published:** `2026-06-09T21:59:45.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0516`Iterable`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [A Vision for Networking in Swift](https://github.com/swiftlang/swift-evolution/blob/main/visions/networking.md) — Fatbobman’s Swift Weekly · Issue 139 — Source repository · Topics: Apple Platform Ecosystem · Networking · Swift
  **Published:** `2026-06-09T12:03:24.234Z`
  **NeKI brief:** Swift's networking vision analyzes overlapping responsibilities among URLSession, Network.framework, SwiftNIO, and related clients. Follow it when designing an abstraction that should align with the language ecosystem's planned consolidation.
- [Swift HTTP API Proposal](https://github.com/apple/swift-http-api-proposal) — Fatbobman’s Swift Weekly · Issue 139 — Source repository · Topics: Apple Platform Ecosystem · Networking · Swift
  **Published:** `2026-06-09T12:03:24.234Z`
  **NeKI brief:** The Swift HTTP API proposal explores a common foundation for HTTP types and behavior across client and server libraries. Use it to track interoperable networking direction before committing a new cross-library adapter.
- [Task Names in Swift ConcurrencyName Swift tasks for clearer debugging and profilingArtem Novichkov](https://artemnovichkov.com/blog/task-names-in-swift-concurrency?ref=createwithswift.com) — Create with Swift · Issue 110 — Article · Topics: Concurrency · Performance · Swift
  **Published:** `2026-06-06T14:00:23.000Z`
  **NeKI brief:** Explains naming tasks in Swift concurrency and how names aid debugging and observability. Follow it when tracing asynchronous work, while keeping names descriptive and avoiding assumptions that labels change scheduling, isolation, or cancellation semantics.
- [SwiftTUI](https://snopia.net/en/blog/introducing-swifttui) — iOS Dev Weekly · Issue 753 — Article · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `5th June 2026`
  **NeKI brief:** Presents swifttui for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Simtime](https://github.com/MobAI-App/simtime) — iOS Dev Tools · iOS Dev Tools: Simtime, Sparkle 2, SwiftINI — Source repository · Topics: AI Development · Developer Tools · Personal Essays
  **Published:** `2026-06-04T17:01:58.905Z`
  **NeKI brief:** Simtime changes the wall clock perceived by an already-running iOS Simulator app, supporting freeze, jump, scale, and reset without rebuilding. Useful for deterministic testing of time-dependent UI, caches, and scheduled work.
- [Sparkle 2](https://github.com/sparkle-project/Sparkle) — iOS Dev Tools · iOS Dev Tools: Simtime, Sparkle 2, SwiftINI — Source repository · Topics: Developer Tools
  **Published:** `2026-06-04T17:01:58.905Z`
  **NeKI brief:** Sparkle provides signed software-update delivery for macOS applications, including feed handling and installer integration. Useful for studying a mature update channel and the security responsibilities around release signatures and keys.
- [SwiftINI](https://github.com/jaywcjlove/SwiftINI) — iOS Dev Tools · iOS Dev Tools: Simtime, Sparkle 2, SwiftINI — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2026-06-04T17:01:58.905Z`
  **NeKI brief:** SwiftINI parses and serializes INI configuration files in Swift, providing a small format-specific layer instead of treating configuration as untyped text. Useful for command-line tools or legacy settings that need round-tripping.
- [Windows Terminal](https://github.com/microsoft/terminal) — iOS Dev Tools · iOS Dev Tools: Simtime, Sparkle 2, SwiftINI — Source repository · Topics: Developer Tools · Swift
  **Published:** `2026-06-04T17:01:58.905Z`
  **NeKI brief:** Windows Terminal combines modern terminal tabs, panes, profiles, and rendering with the original Windows console host. Useful as a cross-platform terminal reference when agent or build workflows span Windows environments.
- [SwiftBar](https://github.com/swiftbar/SwiftBar) — iOS Dev Tools · iOS Dev Tools: Simtime, Sparkle 2, SwiftINI — Source repository · Topics: Developer Tools · macOS & AppKit · Swift
  **Published:** `2026-06-04T17:01:58.905Z`
  **NeKI brief:** SwiftBar turns shell scripts into macOS menu-bar items, using script output to define labels, menus, and refresh behavior. Useful for lightweight developer dashboards without building a dedicated native status application.
- [DockDoor](https://github.com/ejbills/DockDoor) — iOS Dev Tools · iOS Dev Tools: Simtime, Sparkle 2, SwiftINI — Source repository · Topics: Developer Tools · Swift
  **Published:** `2026-06-04T17:01:58.905Z`
  **NeKI brief:** DockDoor adds macOS window peeking, alternate-tab behavior, and related desktop navigation enhancements. Useful for examining how a menu-bar utility can improve window switching while staying outside application code.
- [Open Caffeine](https://github.com/sapsaldog/open-caffeine) — iOS Dev Tools · iOS Dev Tools: Simtime, Sparkle 2, SwiftINI — Source repository · Topics: Developer Tools · macOS & AppKit · Swift
  **Published:** `2026-06-04T17:01:58.905Z`
  **NeKI brief:** Open Caffeine prevents a Mac from sleeping through a small menu-bar control. Useful for inspecting a minimal, reversible power-management utility used during long builds, demos, or unattended local jobs.
- [BarDict](https://github.com/TokinoyuushaLink/BarDict) — iOS Dev Tools · iOS Dev Tools: Simtime, Sparkle 2, SwiftINI — Source repository · Topics: Developer Tools · Hardware & Devices · Objective-C & Cocoa
  **Published:** `2026-06-04T17:01:58.905Z`
  **NeKI brief:** BarDict is a macOS menu-bar dictionary application supporting MDX and MDD resources. Useful for evaluating offline dictionary lookup and packaged language assets in a compact AppKit-style utility.
- [Xcsift](https://github.com/ldomaradzki/xcsift) — Fatbobman’s Swift Weekly · Issue 138 — Source repository · Topics: AI Development · Developer Tools · Testing
  **Published:** `2026-06-01T12:04:47.860Z`
  **NeKI brief:** xcsift condenses xcodebuild output so coding agents receive actionable build and test diagnostics instead of full verbose logs. Use it when agent context windows are consumed by compiler noise rather than failures requiring repair.
- [Replacing Bash with Swift in an AI Harness](https://alejandromp.com/development/blog/replacing-bash-with-swift-in-an-ai-harness) — iOS Dev Weekly · Issue 752 — Article · Topics: AI Development · Developer Tools · Swift
  **Published:** `29th May 2026`
  **NeKI brief:** Replaces shell orchestration with Swift in an AI harness, showing how typed process control and platform APIs can improve portability while adding implementation overhead.
- [SwiftScript](https://github.com/Cocoanetics/SwiftScript) — Fatbobman’s Swift Weekly · Issue 137 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `2026-05-25T12:03:50.192Z`
  **NeKI brief:** SwiftScript is an experimental embeddable interpreter that parses and executes Swift ASTs with SwiftSyntax rather than invoking swiftc. Use it to study interpreter architecture and dynamic scripting trade-offs in a Swift-hosted environment.
- [AcceptedSE-0530Async Result Support](https://github.com/apple/swift-evolution/blob/main/proposals/0530-async-result-support.md) — SwiftLee Weekly · Issue 324 — Source repository · Topics: AI Development · Concurrency · Swift
  **Published:** `2026-05-19T14:04:54.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0530Async Result Support. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [VibeChard](https://github.com/Maples7/VibeChard) — Fatbobman’s Swift Weekly · Issue 136 — Source repository · Topics: AI Development · Developer Tools · Xcode
  **Published:** `2026-05-18T12:01:58.375Z`
  **NeKI brief:** VibeChard addresses parallel Xcode-agent builds colliding in DerivedData, module caches, SwiftPM caches, and Simulator state. Use it when concurrent automation needs isolated build environments rather than simply increasing worker count.
- [SwiftSafeUI](https://github.com/BaherTamer/SwiftSafeUI) — iOS Dev Tools · iOS Dev Tools: SwiftSafeUI, Northstar, Ezscreenshots — Source repository · Topics: Developer Career & Practice · Developer Tools · Swift
  **Published:** `2026-05-14T16:15:24.123Z`
  **NeKI brief:** SwiftSafeUI wraps deprecated SwiftUI APIs behind compatibility-aware modifiers, views, and environment values. The repository demonstrates how to centralize availability branching so newer OS APIs are selected automatically while older deployment targets keep working.
- [TaskMenu](https://github.com/crazytan/TaskMenu) — iOS Dev Tools · iOS Dev Tools: SwiftSafeUI, Northstar, Ezscreenshots — Source repository · Topics: Developer Career & Practice · Developer Tools · macOS & AppKit
  **Published:** `2026-05-14T16:15:24.123Z`
  **NeKI brief:** TaskMenu surfaces Google Tasks in a native macOS menu-bar application. Useful for examining a small API-backed desktop client that keeps task capture accessible without maintaining a full windowed workspace.
- [Dropshit](https://github.com/iamsumanp/Dropshit) — iOS Dev Tools · iOS Dev Tools: SwiftSafeUI, Northstar, Ezscreenshots — Source repository · Topics: Developer Tools
  **Published:** `2026-05-14T16:15:24.123Z`
  **NeKI brief:** Dropshit accepts files and folders dropped anywhere on the macOS screen, providing a lightweight drag-and-drop utility. Useful for exploring global drop targets and desktop-level workflow shortcuts outside a document app.
- [WatchLink](https://github.com/tareksabry1337/WatchLink) — Fatbobman’s Swift Weekly · Issue 135 — Source repository · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `2026-05-11T12:02:41.178Z`
  **NeKI brief:** WatchLink explores Watch connectivity over ordinary network protocols, allowing the peer to be an iPhone, Android device, or other IP endpoint. Use it when a watch feature should not depend on a proprietary phone-pairing transport.
- [ios-build-verify](https://github.com/vermont42/ios-build-verify) — iOS Dev Weekly · Issue 750 — Source repository · Topics: Accessibility · Developer Tools · Testing
  **Published:** `8th May 2026`
  **NeKI brief:** Provides a command-line verifier for iOS build artifacts and project settings. Use it in CI to catch invalid configurations early, while reviewing its checks against your signing, SDK, and reproducibility requirements.
- [Swift Concurrency Agent Skill](https://github.com/AvdLee/Swift-Concurrency-Agent-Skill) — SwiftLee Weekly · Issue 322 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2026-05-05T14:09:40.000Z`
  **NeKI brief:** Provides focused agent guidance for Swift concurrency work. Use it to give coding agents project-relevant rules around isolation, Sendable boundaries, and async tests before they propose or edit concurrent Swift code.
- [ImplementedSE-0524Add `withTemporaryAllocation` using `Output(Raw)Span`](https://github.com/apple/swift-evolution/blob/main/proposals/0524-span-temporary-allocation.md) — SwiftLee Weekly · Issue 322 — Source repository · Topics: Developer Tools · Maps & Location · Swift
  **Published:** `2026-05-05T14:09:40.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0524Add `withTemporaryAllocation` using `Output(Raw)Span`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [KadrUI](https://github.com/SteliyanH/kadr-ui) — Fatbobman’s Swift Weekly · Issue 134 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `2026-05-04T12:03:54.604Z`
  **NeKI brief:** KadrUI supplies SwiftUI editing components such as multi-track timelines, inspectors, overlays, and keyframe editing. Use it when a video or motion-editing product needs a structured editor surface rather than isolated custom controls.
- [Recording & Analyzing SwiftUI Instruments Traces](https://github.com/AvdLee/SwiftUI-Agent-Skill) — SwiftLee Weekly · Issue 321 — Source repository · Topics: Performance · Swift · SwiftUI
  **Published:** `2026-04-28T14:07:22.000Z`
  **NeKI brief:** Describes A SwiftUI agent skill for better code reviews, focusing on practical tool integration and workflow trade-offs. Use it to evaluate reproducibility, trust boundaries, and debugging steps before adopting the approach in an Xcode project.
- [AcceptedSE-0511SwiftPM Add Target Plugin Command](https://github.com/apple/swift-evolution/blob/main/proposals/0511-swiftpm-add-target-plugin.md) — SwiftLee Weekly · Issue 321 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2026-04-28T14:07:22.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0511SwiftPM Add Target Plugin Command. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [open source](https://github.com/toprakdeviren/msf) — Fatbobman’s Swift Weekly · Issue 133 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2026-04-27T12:03:24.228Z`
  **NeKI brief:** msf open-sources a compiler frontend with lexer, parser, and semantic-analysis code. Use it as an educational route through language-tooling architecture, not as a drop-in replacement for the production Swift compiler.
- [OpenSwiftUI](https://github.com/OpenSwiftUIProject/OpenSwiftUI) — Fatbobman’s Swift Weekly · Issue 132 — Source repository · Topics: Developer Community & Business · Swift · SwiftUI
  **Published:** `2026-04-20T12:03:00.641Z`
  **NeKI brief:** OpenSwiftUI is a community reimplementation useful for studying declarative view behavior and framework boundaries. Follow it for comparative exploration, not as a drop-in substitute for Apple's implementation guarantees.
- [DanceUI](https://github.com/bytedance/DanceUI) — Fatbobman’s Swift Weekly · Issue 132 — Source repository · Topics: Developer Community & Business · Swift · SwiftUI
  **Published:** `2026-04-20T12:03:00.641Z`
  **NeKI brief:** DanceUI is ByteDance's open-source exploration of reimplementing SwiftUI concepts. Use it to inspect alternative declarative-UI architecture and rendering decisions, without assuming behavior matches Apple's private implementation.
- [Pica](https://github.com/onmyway133/pica) — iOS Dev Tools · iOS Dev Tools: SwiftZilla, Room Service, Pica — Source repository · Topics: Developer Tools
  **Published:** `2026-04-16T16:01:26.478Z`
  **NeKI brief:** Pica discovers Claude Code agents, skills, commands, hooks, and rules in GitHub repositories or local paths, then offers interactive copy or symlink installation at local or global scope. It helps inspect and curate agent tooling without manual file copying.
- [Claude Account Switcher](https://github.com/Symbioose/claude-account-switcher) — iOS Dev Tools · iOS Dev Tools: SwiftZilla, Room Service, Pica — Source repository · Topics: Developer Tools · macOS & AppKit
  **Published:** `2026-04-16T16:01:26.478Z`
  **NeKI brief:** Claude Account Switcher manages multiple Claude Code and Codex CLI accounts from a Mac menu bar, showing usage and switching at limits. Useful for studying credential-profile separation and the operational risks of automated account changes.
- [Ignite](https://github.com/twostraws/Ignite) — Fatbobman’s Swift Weekly · Issue 131 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2026-04-13T12:03:12.522Z`
  **NeKI brief:** Ignite is a Swift web framework inspired by SwiftUI-style APIs. Use it to evaluate declarative server-rendered site composition in Swift, while separating its design experiment from claims about an official SwiftUI implementation.
- [SwiftMCP](https://github.com/Cocoanetics/SwiftMCP.git) — Fatbobman’s Swift Weekly · Issue 131 — Source repository · Topics: AI Development · App Intents & System Surfaces · Swift
  **Published:** `2026-04-13T12:03:12.522Z`
  **NeKI brief:** SwiftMCP uses Swift macros to build MCP servers and map App Intents into agent-callable tools. Use it when exposing existing app capabilities to agents while retaining a typed, auditable declaration of each operation.
- [presentation repository](https://github.com/onevcat/2026-let-s-vision) — Fatbobman’s Swift Weekly · Issue 130 — Source repository · Topics: AI Development · Developer Tools · Objective-C & Cocoa
  **Published:** `2026-04-06T12:03:03.974Z`
  **NeKI brief:** Hosts WWDC-related Slidev material together with raw research and AI collaboration traces. Use it to inspect how a technical talk's claims were assembled and how agent-assisted research can remain reviewable.
- [Returned For RevisionSE-0490Environment Constrained Shared Libraries](https://github.com/apple/swift-evolution/blob/main/proposals/0490-environment-constrained-shared-libraries.md) — SwiftLee Weekly · Issue 317 — Source repository · Topics: Developer Tools · Swift · Xcode
  **Published:** `2026-03-31T14:07:14.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Returned For RevisionSE-0490Environment Constrained Shared Libraries. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ImplementedSE-0502Exclude private initialized properties from memberwise initializer](https://github.com/apple/swift-evolution/blob/main/proposals/0502-exclude-private-from-memberwise-init.md) — SwiftLee Weekly · Issue 317 — Source repository · Topics: Developer Tools · Swift · Xcode
  **Published:** `2026-03-31T14:07:14.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0502Exclude private initialized properties from memberwise initializer. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Conduit](https://github.com/christopherkarani/Conduit) — Fatbobman’s Swift Weekly · Issue 129 — Source repository · Topics: AI Development · Developer Career & Practice · Developer Tools
  **Published:** `2026-03-30T12:03:55.935Z`
  **NeKI brief:** Conduit is a unified SDK for working with multiple LLM providers. Use it when an application needs provider substitution behind one interface, while keeping model-specific capabilities and cost differences visible to callers.
- [Colony](https://github.com/christopherkarani/Colony) — Fatbobman’s Swift Weekly · Issue 129 — Source repository · Topics: AI Development · Developer Career & Practice · Developer Tools
  **Published:** `2026-03-30T12:03:55.935Z`
  **NeKI brief:** Colony is an agent runtime built around Apple Foundation Models. Use it to explore agent orchestration on-device, especially where tool execution, memory, and model-session lifecycle need a framework-level boundary.
- [ImplementedSE-0491Module selectors for name disambiguation](https://github.com/apple/swift-evolution/blob/main/proposals/0491-module-selectors.md) — SwiftLee Weekly · Issue 316 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2026-03-24T15:03:10.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0491Module selectors for name disambiguation. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ImplementedSE-0493Support `async` calls in `defer` bodies](https://github.com/apple/swift-evolution/blob/main/proposals/0493-defer-async.md) — SwiftLee Weekly · Issue 316 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2026-03-24T15:03:10.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0493Support `async` calls in `defer` bodies. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ImplementedSE-0499Support ~Copyable, ~Escapable in simple standard library protocols](https://github.com/apple/swift-evolution/blob/main/proposals/0499-support-non-copyable-simple-protocols.md) — SwiftLee Weekly · Issue 316 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2026-03-24T15:03:10.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0499Support ~Copyable, ~Escapable in simple standard library protocols. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Core Data Evolution](https://github.com/fatbobman/CoreDataEvolution) — Fatbobman’s Swift Weekly · Issue 128 — Source repository · Topics: Core Data · Persistence & Synchronisation · Swift
  **Published:** `2026-03-23T12:02:22.360Z`
  **NeKI brief:** CoreDataEvolution experiments with bringing ModelActor-like concurrency structure to Core Data. Use it when modernizing a Core Data stack while retaining its model and store, especially to centralize context ownership and serialized mutations.
- [Over-Extended Types On The Overuse Of Swift Extensions](https://pastey.github.io/blog/2026-02-15-extensions) — Those Who Swift · Issue 258 — Article · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2026-03-18`
  **NeKI brief:** Examines Over-Extended Types On The Overuse Of Swift Extensions, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [ImplementedSE-0481`weak let`](https://github.com/apple/swift-evolution/blob/main/proposals/0481-weak-let.md) — SwiftLee Weekly · Issue 315 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2026-03-17T15:01:49.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0481`weak let`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [AcceptedSE-0501HTML Coverage Report](https://github.com/apple/swift-evolution/blob/main/proposals/0501-swiftpm-html-coverage-report.md) — SwiftLee Weekly · Issue 315 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `2026-03-17T15:01:49.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0501HTML Coverage Report. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [AcceptedSE-0515Allow `reduce` to produce noncopyable results](https://github.com/apple/swift-evolution/blob/main/proposals/0515-noncopyable-reduce.md) — SwiftLee Weekly · Issue 315 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2026-03-17T15:01:49.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0515Allow `reduce` to produce noncopyable results. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [SwiftUI Agent Skill](https://github.com/AvdLee/SwiftUI-Agent-Skill/releases/tag/2.3.0) — SwiftLee Weekly · Issue 315 — Source repository · Topics: Developer Community & Business · Swift · SwiftUI
  **Published:** `2026-03-17T15:01:49.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for SwiftUI Agent Skill. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Swift Concurrency Agent Skill](https://github.com/AvdLee/Swift-Concurrency-Agent-Skill/releases/tag/2.0.0) — SwiftLee Weekly · Issue 315 — Source repository · Topics: Concurrency · Developer Community & Business · Swift
  **Published:** `2026-03-17T15:01:49.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Swift Concurrency Agent Skill. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ASC CLI](https://github.com/rudrankriyam/App-Store-Connect-CLI) — Fatbobman’s Swift Weekly · Issue 127 — Source repository · Topics: AI Development · App Distribution & Store Operations · Developer Tools
  **Published:** `2026-03-16T12:04:00.245Z`
  **NeKI brief:** App-Store-Connect-CLI automates App Store Connect tasks from the command line, including subscription-related setup. Use it to replace repetitive portal configuration with reviewable scripts, while treating credentials and destructive commands carefully.
- [open sourced the website itself](https://github.com/iOSDevDirectory/Website) — iOS Dev Weekly · Issue 745 — Source repository · Topics: Developer Tools · Performance
  **Published:** `13th March 2026`
  **NeKI brief:** Presents open sourced the website itself for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Skills](https://github.com/artemnovichkov/skills) — iOS Dev Tools · iOS Dev Tools: Skills, Speech Swift, Workflow Audit Skill, Orcv — Source repository · Topics: AI Development · Developer Tools
  **Published:** `2026-03-12T17:30:51.176Z`
  **NeKI brief:** This repository collects reusable skills, commands, hooks, and integrations for AI coding agents. It is useful for studying how agent workflows can be packaged as composable project tooling rather than embedded in one-off prompts.
- [Speech Swift](https://github.com/soniqo/speech-swift) — iOS Dev Tools · iOS Dev Tools: Skills, Speech Swift, Workflow Audit Skill, Orcv — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `2026-03-12T17:30:51.176Z`
  **NeKI brief:** Speech Swift combines ASR, text-to-speech, speech-to-speech, voice-activity detection, and diarization using MLX and Core ML on Apple Silicon. The repository helps evaluate a local, multi-stage speech pipeline and its platform-specific performance trade-offs.
- [Workflow Audit Skill](https://github.com/Terryc21/workflow-audit) — iOS Dev Tools · iOS Dev Tools: Skills, Speech Swift, Workflow Audit Skill, Orcv — Source repository · Topics: Developer Tools · Product Design · Swift
  **Published:** `2026-03-12T17:30:51.176Z`
  **NeKI brief:** Workflow Audit Skill traces SwiftUI entry points through user journeys, checks for dead ends and broken promises, evaluates UX friction, and verifies data wiring before producing a phased fix plan. It is useful for turning exploratory UI review into repeatable audit evidence.
- [Orcv](https://github.com/jasonjmcghee/orcv) — iOS Dev Tools · iOS Dev Tools: Skills, Speech Swift, Workflow Audit Skill, Orcv — Source repository · Topics: Developer Tools · macOS & AppKit
  **Published:** `2026-03-12T17:30:51.176Z`
  **NeKI brief:** Orcv arranges virtual displays in an infinite zoomable canvas, with savepoints, desktop jumps, window or mouse teleportation, undo/redo, and fullscreen shortcuts. It is useful as a concrete macOS window-management workflow rather than a conventional single-desktop utility.
- [dadederk/iOS-Accessibility-Agent-Skill](https://github.com/dadederk/iOS-Accessibility-Agent-Skill) — SwiftLee Weekly · Issue 314 — Source repository · Topics: Accessibility · Developer Tools · Swift
  **Published:** `2026-03-10T15:03:18.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for dadederk/iOS-Accessibility-Agent-Skill. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [twostraws/SwiftUI-Agent-Skill](https://github.com/twostraws/SwiftUI-Agent-Skill) — SwiftLee Weekly · Issue 314 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2026-03-10T15:03:18.000Z`
  **NeKI brief:** Provides a reusable SwiftUI-focused agent skill with guidance for generating and reviewing views. Useful as a concrete prompt and workflow artifact when evaluating AI-assisted UI composition, accessibility, and maintainability in a project.
- [Active ReviewSE-0518`~Sendable` for explicitly marking non-`Sendable` types](https://github.com/apple/swift-evolution/blob/main/proposals/0518-tilde-sendable.md) — SwiftLee Weekly · Issue 314 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2026-03-10T15:03:18.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0518`~Sendable` for explicitly marking non-`Sendable` types. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Mastering Geometry in SwiftUI - GeometryReader, GeometryProxy & onGeometryChange](https://www.sagarunagar.com/blog/geometry-in-swiftui) — SwiftUI Weekly · SwiftUI Weekly - Issue #230 — Article · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2026-03-09T13:33:31.501Z`
  **NeKI brief:** Surveys GeometryReader, GeometryProxy, and onGeometryChange through practical SwiftUI layout examples. Useful for choosing the least-coupled measurement tool when adaptive components need size or position information without destabilizing layout.
- [FOSDEM](https://swiftlang.github.io/event-fosdem) — Fatbobman’s Swift Weekly · Issue 126 — Article · Topics: Developer Community & Business · Developer Tools · Swift
  **Published:** `2026-03-09T12:02:58.691Z`
  **NeKI brief:** Collects Swift DevRoom talks from FOSDEM 2025 in one searchable programme and video index. Use the recordings to compare implementation techniques and ecosystem direction, then follow the referenced repositories or proposals when a talk informs production design.
- [SE-0506](https://github.com/swiftlang/swift-evolution/blob/main/proposals/0506-advanced-observation-tracking.md) — Fatbobman’s Swift Weekly · Issue 126 — Source repository · Topics: Developer Community & Business · Developer Tools · Swift
  **Published:** `2026-03-09T12:02:58.691Z`
  **NeKI brief:** SE-0506 advances observation tracking for more precise dependency detection and update control. Follow it when SwiftUI or Observation invalidates too broadly and a feature needs explicit understanding of what reads drive recomputation.
- [vChewing Input Method](https://vchewing.github.io/README.html) — Fatbobman’s Swift Weekly · Issue 126 — Article · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `2026-03-09T12:02:58.691Z`
  **NeKI brief:** vChewing documents a Chinese input method built for Apple platforms, including its user-facing behavior and project context. Follow it as a case study in text-input engineering, not as a general Swift UI tutorial.
- [IMKSwift](https://github.com/vChewing/IMKSwift) — Fatbobman’s Swift Weekly · Issue 126 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2026-03-09T12:02:58.691Z`
  **NeKI brief:** IMKSwift provides a Swift 6-oriented, @MainActor-isolated base controller for InputMethodKit sessions. Use it when modernizing macOS input methods and avoiding the concurrency hazards inherited from IMKInputController-style callbacks.
- [Next.app devcon](https://www.nextappcon.com/) — iOS Dev Tools · iOS Dev Tools: Notepad.exe, SimTag, Rich HTML Editor — Article · Topics: Developer Tools
  **Published:** `2026-03-05T17:46:01.942Z`
  **NeKI brief:** Provides public event information for Next.app devcon, including community sessions and speakers. Use it to discover practitioner perspectives and recordings, while treating any API guidance as contextual and verifying details independently.
- [edwardsanchez/MotionEyes](https://github.com/edwardsanchez/MotionEyes) — SwiftLee Weekly · Issue 313 — Source repository · Topics: AI Development · Developer Tools
  **Published:** `2026-03-03T15:11:29.000Z`
  **NeKI brief:** This source repository covers instrumenting and inspecting SwiftUI animation behavior. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Release 2.0.0 · AvdLee/SwiftUI-Agent-Skill](https://github.com/AvdLee/SwiftUI-Agent-Skill/releases/tag/2.0.0) — SwiftLee Weekly · Issue 313 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2026-03-03T15:11:29.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Release 2.0.0 · AvdLee/SwiftUI-Agent-Skill. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [AcceptedSE-0509Software Bill of Materials (SBOM) Generation for Swift Package Manager](https://github.com/apple/swift-evolution/blob/main/proposals/0509-swift-sboms-via-swiftpm.md) — SwiftLee Weekly · Issue 313 — Source repository · Topics: App Distribution & Store Operations · Swift · Swift Package Manager
  **Published:** `2026-03-03T15:11:29.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0509Software Bill of Materials (SBOM) Generation for Swift Package Manager. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ListKit](https://github.com/Iron-Ham/Lists) — Fatbobman’s Swift Weekly · Issue 125 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Performance
  **Published:** `2026-03-02T12:02:09.017Z`
  **NeKI brief:** Lists investigates UIKit diffable-data-source stalls caused by snapshot internals, then offers an alternative list approach. Use it when frequent updates cause measurable collection-view hitches and profiling points to diffing overhead.
- [SE-0508](https://github.com/swiftlang/swift-evolution/blob/main/proposals/0508-array-expression-trailing-closures.md) — Fatbobman’s Swift Weekly · Issue 125 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2026-03-02T12:02:09.017Z`
  **NeKI brief:** SE-0508 removes the special restriction that prevented array and dictionary type expressions from being followed by trailing closures. Use it to understand a small syntax change that improves consistency in generic and closure-heavy declarations.
- [in-depth reverse engineering work](https://github.com/wh1te4ever/super-tart-vphone-writeup) — Fatbobman’s Swift Weekly · Issue 125 — Source repository · Topics: Developer Community & Business · Developer Tools · Personal Essays
  **Published:** `2026-03-02T12:02:09.017Z`
  **NeKI brief:** Documents reverse engineering around vphone-related components in Apple platform firmware. Use it as technical research context for virtual-phone experiments, not as production guidance or an endorsement of unsupported platform modification.
- [Measuring Core Data and SwiftData](https://yaacoub.github.io/articles/swift-tip/measuring-core-data-and-swiftdata) — iOS Dev Weekly · Issue 744 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `27th February 2026`
  **NeKI brief:** Presents measuring core data and swiftdata for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [ImplementedSE-0508Array expression trailing closures](https://github.com/apple/swift-evolution/blob/main/proposals/0508-array-expression-trailing-closures.md) — SwiftLee Weekly · Issue 312 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2026-02-24T15:08:55.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0508Array expression trailing closures. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Paul Hudson's SwiftAgents AGENTS.md](https://github.com/twostraws/SwiftAgents) — SwiftLee Weekly · Issue 312 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2026-02-24T15:08:55.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Paul Hudson's SwiftAgents AGENTS.md. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [AcceptedSE-0504Task Cancellation Shields](https://github.com/apple/swift-evolution/blob/main/proposals/0504-task-cancellation-shields.md) — SwiftLee Weekly · Issue 311 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `2026-02-17T15:07:33.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0504Task Cancellation Shields. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Returned For RevisionSE-0505Delayed Enqueuing for Executors](https://github.com/apple/swift-evolution/blob/main/proposals/0505-delayed-enqueuing.md) — SwiftLee Weekly · Issue 311 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `2026-02-17T15:07:33.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Returned For RevisionSE-0505Delayed Enqueuing for Executors. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [AcceptedSE-0506Advanced Observation Tracking](https://github.com/apple/swift-evolution/blob/main/proposals/0506-advanced-observation-tracking.md) — SwiftLee Weekly · Issue 311 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `2026-02-17T15:07:33.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0506Advanced Observation Tracking. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [FeaturesKit](https://github.com/adamfootdev/FeaturesKit) — iOS Dev Tools · iOS Dev Tools: DevScroll, FeaturesKit, HeC - Unofficial Hetzner Cloud — Source repository · Topics: Apple Platform Ecosystem · Developer Tools
  **Published:** `2026-02-12T17:15:27.823Z`
  **NeKI brief:** FeaturesKit models feature flags and evaluates them through injectable configuration, making rollout and test scenarios explicit. The repository helps compare a typed feature-management layer with scattered boolean checks and explains where deterministic test overrides belong.
- [VPN Bypass](https://github.com/GeiserX/VPN-Bypass) — iOS Dev Tools · iOS Dev Tools: DevScroll, FeaturesKit, HeC - Unofficial Hetzner Cloud — Source repository · Topics: Developer Tools
  **Published:** `2026-02-12T17:15:27.823Z`
  **NeKI brief:** VPN-Bypass offers per-domain and subnet routing on macOS, selecting direct, VPN, proxy, or Tailscale egress through a menu-bar app and CLI. Useful for testing fine-grained network paths without changing the entire system route.
- [Claude XcodePreviews](https://github.com/Iron-Ham/Claude-XcodePreviews) — iOS Dev Tools · iOS Dev Tools: AboutKit, HelpKit, Claude XcodePreviews — Source repository · Topics: Developer Tools · Swift · Xcode
  **Published:** `2026-02-05T21:03:29.009Z`
  **NeKI brief:** Describes Claude XcodePreviews, focusing on practical tool integration and workflow trade-offs. Use it to evaluate reproducibility, trust boundaries, and debugging steps before adopting the approach in an Xcode project.
- [Designing Swift Errors for an SDK](https://nonstrict.eu/blog/2026/designing-swift-errors-for-an-sdk) — Those Who Swift · Issue 252 — Article · Topics: Developer Tools · Swift
  **Published:** `2026-02-04`
  **NeKI brief:** This article covers designing stable, expressive error APIs for Swift SDKs. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [SwiftUI agent skill](https://github.com/AvdLee/SwiftUI-Agent-Skill/pull/11) — SwiftLee Weekly · Issue 309 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2026-02-03T15:08:20.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for SwiftUI agent skill. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0509Software Bill of Materials (SBOM) Generation for Swift Package Manager](https://github.com/apple/swift-evolution/blob/main/proposals/0509-swift-sboms.md) — SwiftLee Weekly · Issue 309 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2026-02-03T15:08:20.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0509Software Bill of Materials (SBOM) Generation for Swift Package Manager. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Core Data](https://github.com/AvdLee/Core-Data-Agent-Skill) — Fatbobman’s Swift Weekly · Issue 121 — Source repository · Topics: Core Data · Persistence & Synchronisation · Swift
  **Published:** `2026-02-02T12:03:11.621Z`
  **NeKI brief:** Provides focused agent guidance for Core Data tasks. Use it to constrain an agent around contexts, threading, migrations, and persistence boundaries before it modifies an existing Core Data stack.
- [The unexpected @Binding side effect](https://swiftunwrap.com/article/binding-side-effect) — SwiftLee Weekly · Issue 308 — Article · Topics: Developer Tools · Observation & State Management · Swift
  **Published:** `2026-01-27T15:08:00.000Z`
  **NeKI brief:** Presents The unexpected @Binding side effect, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [meta-swift-examples](https://github.com/swift-embedded-linux/meta-swift-examples) — Fatbobman’s Swift Weekly · Issue 120 — Source repository · Topics: Developer Tools · Product Design · Swift
  **Published:** `2026-01-26T12:03:41.562Z`
  **NeKI brief:** meta-swift-examples provides a Dockerized Yocto environment and scripts for building Swift on embedded Linux. Use it to explore cross-compilation reproducibly, while budgeting for long full-image builds and Yocto-specific expertise.
- [meta-swift](https://github.com/jeremy-prater/meta-swift) — Fatbobman’s Swift Weekly · Issue 120 — Source repository · Topics: Developer Community & Business · Developer Tools · Swift
  **Published:** `2026-01-26T12:03:41.562Z`
  **NeKI brief:** meta-swift is the Yocto layer that packages Swift toolchains for embedded Linux builds. Use it when an appliance or device target needs Swift 6.1-era support within an existing Yocto distribution.
- [HealthKit Data Generator](https://github.com/aminbenarieb/healthkit-data-generator) — iOS Dev Tools · iOS Dev Tools: MachScope, SwiftFindRefs, HealthKit Data Generator — Source repository · Topics: AI Development · Developer Tools · Testing
  **Published:** `2026-01-22T20:01:38.499Z`
  **NeKI brief:** HealthKit Data Generator creates configurable, realistic HealthKit samples for iOS development and tests, including natural-language-assisted profiles. Useful for exercising charts and analytics without manually producing device health records.
- [Access-level modifiers on import declarations](https://github.com/swiftlang/swift-evolution/blob/main/proposals/0409-access-level-on-imports.md) — Fatbobman’s Swift Weekly · Issue 119 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2026-01-19T12:01:40.101Z`
  **NeKI brief:** SE-0409 adds access-level modifiers to imports so public APIs do not accidentally leak implementation dependencies. Use it when library modules need tighter dependency boundaries and clearer source-level visibility intent.
- [The Swift Programming Language - PDF edition](https://github.com/peterfriese/swift-book) — iOS Dev Weekly · Issue 739 — Source repository · Topics: Developer Tools · Swift
  **Published:** `16th January 2026`
  **NeKI brief:** Provides Peter Friese’s Swift book materials and examples as a public reference for learning and teaching core Swift concepts. Use it for structured study, not as version-specific API authority.
- [fantastic documentation](https://space-code.github.io/validator) — iOS Dev Weekly · Issue 739 — Article · Topics: Developer Community & Business · Developer Tools · Swift
  **Published:** `16th January 2026`
  **NeKI brief:** Presents fantastic documentation for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [SwiftAgents](https://github.com/christopherkarani/SwiftAgents) — iOS Dev Tools · iOS Dev Tools: SwiftAgents, XML Comparator, Colorful — Source repository · Topics: AI Development · Concurrency · Swift
  **Published:** `2026-01-15T18:30:34.396Z`
  **NeKI brief:** SwiftAgents is a Swift-oriented agent framework inspired by LangChain concepts. Use it to evaluate typed agent orchestration in a Swift project, while scrutinizing tool permissions, memory design, and provider boundaries.
- [Colorful](https://github.com/ktiays/colorful-apple-documents) — iOS Dev Tools · iOS Dev Tools: SwiftAgents, XML Comparator, Colorful — Source repository · Topics: Developer Tools · Swift
  **Published:** `2026-01-15T18:30:34.396Z`
  **NeKI brief:** Colorful Apple Documents is a Swift library for rendering richly styled Apple document formats. Use the repository to investigate document parsing and presentation options, checking supported formats, fidelity, and maintenance before adopting it in production.
- [WhisperShortcut](https://github.com/mgsgde/whisper-shortcut) — iOS Dev Tools · iOS Dev Tools: SwiftAgents, XML Comparator, Colorful — Source repository · Topics: AI Development · Developer Tools · macOS & AppKit
  **Published:** `2026-01-15T18:30:34.396Z`
  **NeKI brief:** WhisperShortcut provides speech-to-text and voice-to-prompt workflows on macOS using Whisper and Gemini integrations. Useful for evaluating local audio capture, transcription handoff, and assistant prompting in a keyboard-driven tool.
- [Dimillian/Skills: My Codex Skills](https://github.com/Dimillian/Skills) — SwiftLee Weekly · Issue 305 — Source repository · Topics: AI Development · Developer Tools
  **Published:** `2026-01-06T15:07:32.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Dimillian/Skills: My Codex Skills. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Agent Skills for Codex](https://developers.openai.com/codex/skills) — SwiftLee Weekly · Issue 305 — Article · Topics: AI Development · Developer Tools
  **Published:** `2026-01-06T15:07:32.000Z`
  **NeKI brief:** Presents Agent Skills for Codex, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Approachable Concurrency](https://github.com/swiftlang/swift-evolution/blob/main/visions/approachable-concurrency.md) — Those Who Swift · Issue 247 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2026-01-01`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for the vision document. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Swift-Parsing](https://github.com/pointfreeco/swift-parsing) — iOS Dev Tools · iOS Dev Tools: Swift-Parsing, ColorsKit, SwiftUI Indie Stack — Source repository · Topics: Developer Tools · Performance · Swift
  **Published:** `2025-12-25T17:35:11.361Z`
  **NeKI brief:** Swift Parsing composes small parsers into typed, reusable grammars with attention to performance and error reporting. Useful when decoding structured text or protocols where ad-hoc splitting obscures grammar and failure locations.
- [ColorsKit](https://github.com/ckdash-git/ColorsKit) — iOS Dev Tools · iOS Dev Tools: Swift-Parsing, ColorsKit, SwiftUI Indie Stack — Source repository · Topics: Accessibility · Developer Tools · Swift
  **Published:** `2025-12-25T17:35:11.361Z`
  **NeKI brief:** Provides SwiftUI and UIKit color utilities for hex parsing, palette generation, contrast checks, and color-vision-deficiency simulation. Follow it when validating a token system or prototyping accessibility-aware colors before integrating production design assets.
- [SwiftUI Indie Stack](https://github.com/cliffordh/swiftui-indie-stack) — iOS Dev Tools · iOS Dev Tools: Swift-Parsing, ColorsKit, SwiftUI Indie Stack — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2025-12-25T17:35:11.361Z`
  **NeKI brief:** SwiftUI Indie Stack is a production-oriented starter template bundling app structure, performance practices, and common SwiftUI infrastructure. Useful for comparing a curated bootstrap against assembling architecture and tooling from separate packages.
- [ClaudeBar](https://github.com/tddworks/ClaudeBar) — iOS Dev Tools · iOS Dev Tools: Swift-Parsing, ColorsKit, SwiftUI Indie Stack — Source repository · Topics: AI Development · Developer Tools · macOS & AppKit
  **Published:** `2025-12-25T17:35:11.361Z`
  **NeKI brief:** ClaudeBar monitors Claude, Codex, Antigravity, and Gemini usage quotas from a macOS menu bar. Useful for a compact multi-provider status surface, especially when comparing polling, rate-limit display, and privacy boundaries.
- [Thock](https://github.com/kamillobinski/thock) — iOS Dev Tools · iOS Dev Tools: Swift-Parsing, ColorsKit, SwiftUI Indie Stack — Source repository · Topics: Developer Tools
  **Published:** `2025-12-25T17:35:11.361Z`
  **NeKI brief:** Thock is a macOS utility centered on adding a tactile sound to keyboard input. Useful for studying global event monitoring and user-controlled feedback, while accounting for accessibility and privacy expectations.
- [list of tips in Paul’s AGENTS.md](https://github.com/twostraws/SwiftAgents/blob/main/AGENTS.md) — iOS Dev Weekly · Issue 737 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `19th December 2025`
  **NeKI brief:** Presents list of tips in paul’s agents.md for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [SwiftUI: Share Wi-Fi Network Credentials With Paired Accessories](https://levelup.gitconnected.com/swiftui-share-wi-fi-network-credentials-with-paired-accessories-30004a4bf8f9) — Those Who Swift · Issue 245 — Article · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2025-12-17`
  **NeKI brief:** Examines SwiftUI: Share Wi-Fi Network Credentials With Paired Accessories, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [swift-openapi-generator](https://github.com/apple/swift-openapi-generator) — Fatbobman’s Swift Weekly · Issue 115 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2025-12-15T12:01:14.054Z`
  **NeKI brief:** Generates type-safe Swift client and server interfaces from OpenAPI descriptions, separating schema-driven transport code from application logic. Use it when a REST contract should drive refactors and reduce manual endpoint decoding.
- [Returned For RevisionSE-0283Tuples Conform to `Equatable`, `Comparable`, and `Hashable`](https://github.com/apple/swift-evolution/blob/main/proposals/0283-tuples-are-equatable-comparable-hashable.md) — SwiftLee Weekly · Issue 301 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2025-12-09T15:08:23.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Returned For RevisionSE-0283Tuples Conform to `Equatable`, `Comparable`, and `Hashable`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [MarkdownView](https://github.com/LiYanan2004/MarkdownView) — Fatbobman’s Swift Weekly · Issue 114 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2025-12-08T12:00:58.751Z`
  **NeKI brief:** MarkdownView renders richer Markdown in SwiftUI, including mixed text and image layouts, selectable content, and interaction hooks. Use it when AttributedString's built-in Markdown support is too limited for a document-reading surface.
- [RichText](https://github.com/LiYanan2004/RichText) — Fatbobman’s Swift Weekly · Issue 114 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2025-12-08T12:00:58.751Z`
  **NeKI brief:** RichText supplies interactive, styled rich-text components for SwiftUI beyond ordinary Text rendering. Use it when links, mixed media, selection, or fine-grained text actions need an explicit view-layer solution.
- [ObjectBox](https://github.com/objectbox/objectbox-swift) — iOS Dev Tools · iOS Dev Tools: ObjectBox, RIB, Swon — Source repository · Topics: Developer Tools · Persistence & Synchronisation · Swift
  **Published:** `2025-12-04T17:28:54.311Z`
  **NeKI brief:** ObjectBox provides a typed Swift NoSQL API with relations, automatic schema migrations, cross-platform targets, and resource-conscious queries. Its on-device vector-search support makes the repository relevant when evaluating local persistence for large datasets or embedded AI features.
- [RIB](https://github.com/son-iOS/SwiftUI-RIB) — iOS Dev Tools · iOS Dev Tools: ObjectBox, RIB, Swon — Source repository · Topics: Architecture · Swift · SwiftUI
  **Published:** `2025-12-04T17:28:54.311Z`
  **NeKI brief:** SwiftUI-RIB adapts Uber's Router–Interactor–Builder architecture with dependency structs, Combine communication, and state/view containers. It is useful for comparing explicit parent-child lifecycle and navigation boundaries with coordinator or environment-driven SwiftUI designs.
- [Uber’s official documentation](https://github.com/uber/RIBs) — iOS Dev Tools · iOS Dev Tools: ObjectBox, RIB, Swon — Source repository · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2025-12-04T17:28:54.311Z`
  **NeKI brief:** Uber's RIBs framework structures mobile features around Router, Interactor, and Builder components with explicit lifecycles and parent-child ownership. Useful as an architectural comparison point for navigation-heavy applications and SwiftUI coordinators.
- [Swon](https://github.com/keeshux/swon) — iOS Dev Tools · iOS Dev Tools: ObjectBox, RIB, Swon — Source repository · Topics: Developer Tools · Foundation & Data Formats · Macros & Metaprogramming
  **Published:** `2025-12-04T17:28:54.311Z`
  **NeKI brief:** SWON uses Swift macros to generate JSON initializers for value types without Codable or Foundation, backed by cJSON and targeting Apple, Linux, Windows, and embedded environments. It is useful when minimizing runtime and framework dependencies in data parsing.
- [PortKiller](https://github.com/gupsammy/PortKiller) — iOS Dev Tools · iOS Dev Tools: ObjectBox, RIB, Swon — Source repository · Topics: Developer Tools · macOS & AppKit
  **Published:** `2025-12-04T17:28:54.311Z`
  **NeKI brief:** PortKiller lists processes bound to development ports and can terminate selected listeners from a macOS menu bar. Useful for quickly resolving local server conflicts without repeatedly composing lsof and kill commands.
- [Swift Macros From 0 to Hero](https://levelup.gitconnected.com/swift-macros-from-0-to-hero-0-01-2ff3eac8571a) — Those Who Swift · Issue 242 — Tutorial · Topics: Developer Tools · Macros & Metaprogramming · Swift
  **Published:** `2025-11-26`
  **NeKI brief:** Examines Swift Macros From 0 to Hero, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [imessage-kit](https://github.com/photon-hq/imessage-kit) — Fatbobman’s Swift Weekly · Issue 112 — Source repository · Topics: Developer Tools
  **Published:** `2025-11-24T12:01:09.147Z`
  **NeKI brief:** iMessageKit explores message-style interfaces on Apple platforms despite iMessage itself lacking a public automation API. Use it as a UI and data-model reference, not as evidence that third-party apps can access system conversations.
- [ImplementedSE-0495C compatible functions and enums](https://github.com/apple/swift-evolution/blob/main/proposals/0495-cdecl.md) — SwiftLee Weekly · Issue 298 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2025-11-18T19:03:17.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0495C compatible functions and enums. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Homebrew had released version 5.0](https://brew.sh/2025/11/12/homebrew-5.0.0) — Fatbobman’s Swift Weekly · Issue 111 — Article · Topics: AI Development · Developer Tools
  **Published:** `2025-11-17T12:02:46.781Z`
  **NeKI brief:** Homebrew 5.0 documents the package manager's new parallel download behavior and release changes. Use it when diagnosing changed brew-upgrade behavior or evaluating how local developer-tool installations may become faster and more concurrent.
- [demo projects](https://github.com/zhangqifan/Insights) — Fatbobman’s Swift Weekly · Issue 111 — Source repository · Topics: App Distribution & Store Operations · Architecture · Liquid Glass
  **Published:** `2025-11-17T12:02:46.781Z`
  **NeKI brief:** Insights contains demo projects for applying Liquid Glass design to a production health app. Use it to inspect concrete adaptations of translucent materials, hierarchy, and interaction rather than treating WWDC design guidance as abstract theory.
- [UniFFI](https://mozilla.github.io/uniffi-rs/latest) — Fatbobman’s Swift Weekly · Issue 111 — Article · Topics: Developer Tools · Swift · Testing
  **Published:** `2025-11-17T12:02:46.781Z`
  **NeKI brief:** UniFFI generates language bindings from Rust components, including Swift-facing APIs. Use it when sharing performant or security-sensitive core logic across platforms while keeping the generated Swift boundary explicit and testable.
- [ImplementedSE-0497Controlling function definition visibility in clients](https://github.com/apple/swift-evolution/blob/main/proposals/0497-definition-visibility.md) — SwiftLee Weekly · Issue 297 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2025-11-11T15:06:31.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0497Controlling function definition visibility in clients. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [AnyLanguageModel](https://github.com/mattt/AnyLanguageModel) — iOS Dev Tools · iOS Dev Tools: Clash X, AnyLanguageModel, HealthKit Data Generator — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **Published:** `2025-11-06T22:32:54.905Z`
  **NeKI brief:** AnyLanguageModel mirrors Apple's Foundation Models API while allowing alternative language-model providers, presenting a compatible abstraction for application code. Useful for testing provider substitution and keeping model integration behind a stable Swift interface.
- [MLX](https://github.com/ml-explore/mlx-swift) — iOS Dev Tools · iOS Dev Tools: Clash X, AnyLanguageModel, HealthKit Data Generator — Source repository · Topics: Developer Tools · Swift
  **Published:** `2025-11-06T22:32:54.905Z`
  **NeKI brief:** MLX Swift exposes Apple's MLX machine-learning array and model APIs to Swift applications on Apple Silicon. Useful for evaluating local inference pipelines that need native Swift integration rather than a Python-only runtime.
- [llama.cpp](https://github.com/ggml-org/llama.cpp) — iOS Dev Tools · iOS Dev Tools: Clash X, AnyLanguageModel, HealthKit Data Generator — Source repository · Topics: Developer Tools
  **Published:** `2025-11-06T22:32:54.905Z`
  **NeKI brief:** llama.cpp provides portable C/C++ inference for large language models, with quantization and hardware backends spanning desktop and embedded environments. Useful for understanding a low-level local inference option behind Swift wrappers.
- [HTTP API](https://github.com/ollama/ollama/blob/main/docs/api.md) — iOS Dev Tools · iOS Dev Tools: Clash X, AnyLanguageModel, HealthKit Data Generator — Source repository · Topics: Developer Tools
  **Published:** `2025-11-06T22:32:54.905Z`
  **NeKI brief:** Ollama's API document describes local model-generation and chat endpoints, request options, streaming responses, and embeddings. Useful when wiring a Swift client to a locally hosted model while keeping transport behavior explicit.
- [repository full of example code](https://github.com/swiftlang/swift-android-examples) — iOS Dev Weekly · Issue 733 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `31st October 2025`
  **NeKI brief:** Presents repository full of example code for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [CodeRabbit’s Free AI Code Reviews in your IDE—VS Code, Cursor, Windsurf](https://coderabbit.link/ios-dt) — iOS Dev Tools · iOS Dev Tools: Netrofit, MacPacker, GradientEditor — Article · Topics: AI Development · Code Quality · Developer Tools
  **Published:** `2025-10-30T18:15:32.319Z`
  **NeKI brief:** Introduces CodeRabbit’s AI-assisted code review tooling for iOS development. Use it to assess IDE review workflows, automated findings, and the boundary between generated suggestions and human approval.
- [Netrofit](https://github.com/winddpan/Netrofit) — iOS Dev Tools · iOS Dev Tools: Netrofit, MacPacker, GradientEditor — Source repository · Topics: Code Quality · Developer Tools · Swift
  **Published:** `2025-10-30T18:15:32.319Z`
  **NeKI brief:** Netrofit builds a Retrofit-like networking layer for Swift, using declarative endpoint definitions to reduce repeated request construction and response decoding. The source helps assess how far protocol-based API descriptions can simplify a typed client without hiding transport details.
- [MacPacker](https://github.com/sarensw/MacPacker) — iOS Dev Tools · iOS Dev Tools: Netrofit, MacPacker, GradientEditor — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2025-10-30T18:15:32.319Z`
  **NeKI brief:** MacPacker creates and packages macOS applications from project inputs, automating repeatable archive, signing, and distribution steps. It is useful for examining a small focused alternative to hand-written packaging scripts in local or CI release workflows.
- [GradientEditor](https://github.com/JoshuaSullivan/GradientEditor) — iOS Dev Tools · iOS Dev Tools: Netrofit, MacPacker, GradientEditor — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2025-10-30T18:15:32.319Z`
  **NeKI brief:** GradientEditor provides an interactive SwiftUI gradient editing surface with stops and color adjustments. Its code is useful when implementing editable design tokens and serializable gradient state rather than hard-coding visual parameters in view declarations.
- [Vercel Deployment Menu Bar](https://github.com/andrewk17/vercel-deployment-menu-bar) — iOS Dev Tools · iOS Dev Tools: Netrofit, MacPacker, GradientEditor — Source repository · Topics: Developer Tools · macOS & AppKit
  **Published:** `2025-10-30T18:15:32.319Z`
  **NeKI brief:** Vercel Deployment Menu Bar watches deployment states such as building, ready, and error from a macOS status item. Useful for a small event-driven release monitor that keeps CI feedback visible outside the browser.
- [porting to the Android platform](https://github.com/OpenSwiftUIProject/OpenSwiftUI/issues?q=is%3Aissue+label%3A%22platform%3A+Android%22) — Fatbobman’s Swift Weekly · Issue 108 — Source repository · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2025-10-27T12:02:17.397Z`
  **NeKI brief:** This OpenSwiftUI issue view tracks Android-platform work and compatibility questions in an open-source SwiftUI reimplementation. Follow it to assess cross-platform progress and limitations, not as evidence about Apple's private SwiftUI implementation.
- [AsyncCombine](https://github.com/will-lumley/AsyncCombine) — Fatbobman’s Swift Weekly · Issue 108 — Source repository · Topics: Combine & Reactive Programming · Concurrency · Swift
  **Published:** `2025-10-27T12:02:17.397Z`
  **NeKI brief:** AsyncCombine bridges familiar Combine-style concepts into Swift concurrency, including relay-like state sharing. Use it to compare an interim async stream abstraction with the proposed AsyncBroadcastSequence and choose explicit buffering semantics.
- [Tunable, physics-driven motion primitives for SwiftUI](https://github.com/roberthein/kinetics) — SwiftUI Weekly · SwiftUI Weekly - Issue #223 — Source repository · Topics: Concurrency · Swift · SwiftUI
  **Published:** `2025-10-20T15:15:23.773Z`
  **NeKI brief:** Provides tunable, physics-driven motion primitives for SwiftUI, including configurable springs and dynamics. Useful for experimenting with reusable interactive animations while inspecting API ergonomics, cancellation, and performance in real screens.
- [swift-subprocess](https://github.com/swiftlang/swift-subprocess) — Fatbobman’s Swift Weekly · Issue 107 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2025-10-20T12:02:20.057Z`
  **NeKI brief:** swift-subprocess modernizes launching and interacting with child processes through Swift concurrency. Use it for scripts and tools that need structured stdin, stdout, cancellation, and exit-status handling beyond Foundation's older Process API.
- [Navigator](https://github.com/hmlongco/Navigator) — iOS Dev Tools · iOS Dev Tools: SwiftGitX, AsyncLifetime, Navigator — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2025-10-09T16:31:37.747Z`
  **NeKI brief:** Navigator provides a SwiftUI navigation abstraction centered on route-driven presentation. Use it to compare centralized routing decisions with native NavigationStack state when complex flows need testable deep-link handling.
- [TranscriptDebugMenu](https://github.com/artemnovichkov/TranscriptDebugMenu) — Fatbobman’s Swift Weekly · Issue 105 — Source repository · Topics: AI Development · Foundation & Data Formats · Performance
  **Published:** `2025-10-06T12:03:37.161Z`
  **NeKI brief:** TranscriptDebugMenu is a debug surface for inspecting Foundation Models conversations and related app state. Use it alongside Xcode Instruments when testing session prewarming, tool calls, and model-output performance in development builds.
- [Package Traits](https://github.com/swiftlang/swift-evolution/blob/main/proposals/0450-swiftpm-package-traits.md) — iOS Dev Weekly · Issue 729 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `3rd October 2025`
  **NeKI brief:** Defines Swift Package Manager package traits for expressing optional dependency features. Study the proposal when designing modular packages, then verify accepted syntax and toolchain support before adopting it.
- [Building SyntaxKit](https://brightdigit.com/tutorials/syntaxkit-swift-code-generation) — iOS Dev Weekly · Issue 729 — Tutorial · Topics: Developer Tools · Macros & Metaprogramming · Swift
  **Published:** `3rd October 2025`
  **NeKI brief:** Presents building syntaxkit for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [React-native-enriched](https://github.com/software-mansion-labs/react-native-enriched) — iOS Dev Tools · iOS Dev Tools: React-native-enriched, Darling, Aidoku — Source repository · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `2025-10-02T19:15:22.078Z`
  **NeKI brief:** react-native-enriched exposes a native rich-text editor to React Native with synchronous styling, HTML parsing, and live style detection. Its New Architecture constraint and native text-input design are useful when evaluating editor performance and platform integration boundaries.
- [Darling](https://github.com/darlinghq/darling) — iOS Dev Tools · iOS Dev Tools: React-native-enriched, Darling, Aidoku — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2025-10-02T19:15:22.078Z`
  **NeKI brief:** Darling provides a macOS runtime environment on Linux, including DPREFIX-style environments, package and DMG handling, and support for compiling with Apple's toolchain and SDKs. It is useful for understanding the practical limits of cross-platform macOS compatibility.
- [Aidoku](https://github.com/Aidoku/Aidoku) — iOS Dev Tools · iOS Dev Tools: React-native-enriched, Darling, Aidoku — Source repository · Topics: Developer Tools
  **Published:** `2025-10-02T19:15:22.078Z`
  **NeKI brief:** Aidoku is an ad-free, open-source manga reader for iOS and iPadOS with downloadable content, external-source support, WebAssembly-based source modules, and AniList/MyAnimeList tracking. The project is a substantial example of modular content ingestion on Apple platforms.
- [sample project](https://github.com/JuniperPhoton/CornerMarginSample) — Fatbobman’s Swift Weekly · Issue 104 — Source repository · Topics: Developer Tools
  **Published:** `2025-09-29T12:00:38.726Z`
  **NeKI brief:** CornerMarginSample demonstrates layout behavior around corner and margin changes. Use it as a visual test fixture when comparing SwiftUI layout effects across OS versions instead of inferring geometry from screenshots alone.
- [Swift Package Index](https://github.com/SwiftPackageIndex/SwiftPackageIndex-Server) — iOS Dev Weekly · Issue 728 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `26th September 2025`
  **NeKI brief:** Examines open-source, focusing on georgios recommends the point-free swift-snapshot-testing which we also use to test the rendered html output from the…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [The TCA Playbook: Debugging Large Reducers Without Losing Your Mind](https://medium.com/@wesleymatlock/the-tca-playbook-debugging-large-reducers-without-losing-your-mind-e8813c9c6eda) — Those Who Swift · Issue 233 — Article · Topics: Composable Architecture · Developer Tools · Performance
  **Published:** `2025-09-24`
  **NeKI brief:** Examines The TCA Playbook: Debugging Large Reducers Without Losing Your Mind, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [ImplementedSE-0482Binary Static Library Dependencies](https://github.com/apple/swift-evolution/blob/main/proposals/0482-swiftpm-static-library-binary-target-non-apple-platforms.md) — SwiftLee Weekly · Issue 290 — Source repository · Topics: Dependency Injection · Developer Tools · Swift
  **Published:** `2025-09-23T14:09:24.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0482Binary Static Library Dependencies. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Layout Guidelines](https://marioaguzman.github.io/design/layoutguidelines) — iOS Dev Weekly · Issue 727 — Article · Topics: Developer Tools
  **Published:** `19th September 2025`
  **NeKI brief:** Presents layout guidelines for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Toolbar Guidelines](https://marioaguzman.github.io/design/toolbarguidelines) — iOS Dev Weekly · Issue 727 — Article · Topics: Developer Tools
  **Published:** `19th September 2025`
  **NeKI brief:** Presents toolbar guidelines for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [OpenAttributeGraph](https://github.com/OpenSwiftUIProject/OpenAttributeGraph) — Fatbobman’s Swift Weekly · Issue 102 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2025-09-15T12:03:30.479Z`
  **NeKI brief:** OpenAttributeGraph documents an open implementation of SwiftUI-style dependency tracking and attribute propagation. Use it to investigate why state changes invalidate views, while treating it as a learning model rather than Apple's private framework source.
- [JNIKit](https://github.com/swifdroid/jni-kit) — Fatbobman’s Swift Weekly · Issue 102 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `2025-09-15T12:03:30.479Z`
  **NeKI brief:** JNIKit provides Swift-friendly bindings for Android JNI interaction. Use it when a Swift Android library must call Java or Kotlin APIs, keeping conversion and reference-lifetime rules isolated from application code.
- [detailed introduction](https://brightdigit.com/tutorials/swift-build) — Fatbobman’s Swift Weekly · Issue 102 — Tutorial · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-09-15T12:03:30.479Z`
  **NeKI brief:** Explains using the swift-build GitHub Action to run Swift Package Manager builds and tests on macOS and Linux. Use it as a compact cross-platform CI starting point before adding caching, matrices, or release artifacts.
- [Haptic Video Sync](https://github.com/thomasdye12/HapticPlayer) — iOS Dev Tools · iOS Dev Tools: Subprocess, ReerJSON, Haptic Video Sync — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `2025-09-11T20:39:49.146Z`
  **NeKI brief:** HapticPlayer is an iOS haptic playback example, providing a focused repository for experimenting with Core Haptics patterns. Useful for isolating feedback timing and device capability checks before embedding haptics into a larger feature.
- [IQListKit](https://github.com/Instagram/IGListKit) — iOS Dev Tools · iOS Dev Tools: IQListKit, Radar, HapticPlayer — Source repository · Topics: Developer Tools
  **Published:** `2025-09-04T15:31:16.101Z`
  **NeKI brief:** IGListKit provides a data-driven collection-view architecture with section controllers, diffing, and incremental updates. It is useful for studying how large, frequently changing lists can avoid brittle index-path bookkeeping and preserve performant UIKit rendering.
- [QuickRecorder](https://github.com/lihaoyun6/QuickRecorder) — iOS Dev Tools · iOS Dev Tools: IQListKit, Radar, HapticPlayer — Source repository · Topics: Developer Tools · Performance
  **Published:** `2025-09-04T15:31:16.101Z`
  **NeKI brief:** QuickRecorder is a lightweight macOS recorder built around ScreenCaptureKit, covering screen capture and related recording controls. Useful for examining a native capture workflow when producing reproducible demos or test evidence.
- [Debugging Swift Concurrency: "Am I on the Main Actor?" (Not the Main Thread)](https://www.swiftyplace.com/blog/debugging-swift-concurrency) — SwiftLee Weekly · Issue 287 — Article · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2025-09-02T14:17:18.000Z`
  **NeKI brief:** Explains how to determine whether Swift code runs on the MainActor rather than merely the main thread. Use it to diagnose isolation mistakes and validate actor assumptions during concurrency debugging.
- [working sample](https://github.com/trozware/swiftui-webview) — iOS Dev Weekly · Issue 724 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `29th August 2025`
  **NeKI brief:** Presents working sample for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [ImplementedSE-0460Explicit Specialization](https://github.com/apple/swift-evolution/blob/main/proposals/0460-specialized.md) — SwiftLee Weekly · Issue 286 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2025-08-26T14:12:25.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0460Explicit Specialization. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ImplementedSE-0476Controlling the ABI of a function, initializer, property, or subscript](https://github.com/apple/swift-evolution/blob/main/proposals/0476-abi-attr.md) — SwiftLee Weekly · Issue 286 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2025-08-26T14:12:25.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0476Controlling the ABI of a function, initializer, property, or subscript. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Hidden Gems in the Swift Argument Parser – Part I](https://swifttoolkit.dev/posts/argument-parser-gems) — Those Who Swift · Issue 228 — Article · Topics: Developer Tools · Swift
  **Published:** `2025-08-20`
  **NeKI brief:** Examines Hidden Gems in the Swift Argument Parser – Part I, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Make Foundation Models Deterministic: Greedy Decoding in Swift](https://www.youtube.com/watch?v=Q6x3VeGlqwg) — Those Who Swift · Issue 228 — Video · Topics: AI Development · Foundation & Data Formats · Swift
  **Published:** `2025-08-20`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [WithdrawnSE-0030Property Behaviors](https://github.com/apple/swift-evolution/blob/main/proposals/0030-property-behavior-decls.md) — SwiftLee Weekly · Issue 285 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2025-08-19T14:12:01.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for WithdrawnSE-0030Property Behaviors. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [STTextView](https://github.com/krzyzanowskim/STTextView) — Fatbobman’s Swift Weekly · Issue 98 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2025-08-18T12:03:30.201Z`
  **NeKI brief:** STTextView is a TextKit 2-based text editor that exposes the practical gaps encountered in Apple's newer text system. Use it when building editor-like macOS UI and needing a tested reference for selection, layout, and editing behavior.
- [swift-argument-parser](https://github.com/apple/swift-argument-parser) — Fatbobman’s Swift Weekly · Issue 98 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2025-08-18T12:03:30.201Z`
  **NeKI brief:** swift-argument-parser declares command-line options, arguments, subcommands, validation, and help in typed Swift definitions. Use it when a developer tool needs discoverable CLI behavior without manually parsing argv or maintaining usage text separately.
- [ch.at](https://github.com/Deep-ai-inc/ch.at) — iOS Dev Tools · iOS Dev Tools: ch.at, Mercato, Dependencies — Source repository · Topics: AI Development · Developer Tools · Security & Privacy
  **Published:** `2025-08-14T19:53:26.103Z`
  **NeKI brief:** ch.at is an open-source chat application project from Deep AI Inc. Use the repository to inspect conversational UI, networking, and model-integration patterns, while treating its architecture as an example rather than a production security baseline.
- [Mercato](https://github.com/tikhop/Mercato) — iOS Dev Tools · iOS Dev Tools: ch.at, Mercato, Dependencies — Source repository · Topics: App Distribution & Store Operations · Developer Career & Practice · Developer Tools
  **Published:** `2025-08-14T19:53:26.103Z`
  **NeKI brief:** Mercato wraps StoreKit 2 for subscriptions and in-app purchases across Apple platforms, aiming to reduce repetitive transaction plumbing. Useful for comparing a focused purchase abstraction with direct StoreKit state and entitlement management.
- [Dependencies](https://github.com/pointfreeco/swift-dependencies) — iOS Dev Tools · iOS Dev Tools: ch.at, Mercato, Dependencies — Source repository · Topics: Dependency Injection · Developer Tools · Swift
  **Published:** `2025-08-14T19:53:26.103Z`
  **NeKI brief:** Swift Dependencies models dependency values in a SwiftUI-inspired environment, allowing production implementations to be replaced in tests and previews. Useful for making side effects explicit without threading every service through initializer parameters.
- [ImplementedSE-0480Warning Control Settings for SwiftPM](https://github.com/apple/swift-evolution/blob/main/proposals/0480-swiftpm-warning-control.md) — SwiftLee Weekly · Issue 284 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-08-12T18:01:44.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0480Warning Control Settings for SwiftPM. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Valkey](https://github.com/valkey-io/valkey) — Fatbobman’s Swift Weekly · Issue 97 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2025-08-11T12:04:06.619Z`
  **NeKI brief:** Valkey is a BSD-licensed, Redis-compatible high-performance key-value store forked from Redis 7.2.4. Use it when server-side caching or queues need Redis protocol compatibility without the later Redis licensing model.
- [valkey-swift](https://github.com/valkey-io/valkey-swift) — Fatbobman’s Swift Weekly · Issue 97 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2025-08-11T12:04:06.619Z`
  **NeKI brief:** valkey-swift is the official Swift-concurrency client for Valkey. Use it when a server-side Swift service needs asynchronous commands against a Redis-compatible store with library-managed connection and protocol handling.
- [xcode-build-server](https://github.com/SolaWing/xcode-build-server) — Fatbobman’s Swift Weekly · Issue 97 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools · Xcode
  **Published:** `2025-08-11T12:04:06.619Z`
  **NeKI brief:** xcode-build-server supplies build-server-protocol data for Xcode projects so editors can understand Swift builds. Use it when integrating non-Xcode tooling such as Zed with an existing workspace and its compiler settings.
- [swiftlang/swift-testing: A modern, expressive testing package for Swift](https://github.com/swiftlang/swift-testing) — SwiftLee Weekly · Issue 283 — Source repository · Topics: Developer Tools · Swift · Testing
  **Published:** `2025-08-05T17:17:03.000Z`
  **NeKI brief:** Presents a concrete implementation of Swift Testing. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.
- [apple/swift-async-algorithms: Async Algorithms for Swift](https://github.com/apple/swift-async-algorithms) — SwiftLee Weekly · Issue 283 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2025-08-05T17:17:03.000Z`
  **NeKI brief:** swift-async-algorithms adds reusable asynchronous sequence operators and utilities for Swift concurrency. Use it when async/await code needs throttling, merging, buffering, or other stream composition without reintroducing a full Combine pipeline.
- [sample app](https://github.com/trozware/swiftui-mac-2025) — Fatbobman’s Swift Weekly · Issue 96 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2025-08-04T12:03:39.737Z`
  **NeKI brief:** This sample app collects macOS SwiftUI 2025 features and implementation notes, including new icon formats and native controls. Use it as a runnable compatibility reference when adopting current macOS-specific SwiftUI APIs.
- [memory monitoring tool](https://github.com/egzonpllana/MemoryProfiler) — Fatbobman’s Swift Weekly · Issue 96 — Source repository · Topics: Developer Tools · Performance
  **Published:** `2025-08-04T12:03:39.737Z`
  **NeKI brief:** MemoryProfiler helps surface abnormal memory growth during iOS navigation and interaction. Use it to reproduce a suspected leak or retained graph before escalating to Instruments, rather than relying only on one-time memory snapshots.
- [FreeTypeFramework](https://github.com/EvgenijLutz/FreeTypeFramework) — iOS Dev Tools · iOS Dev Tools: FreeTypeFramework, IGListKit, Horoscope — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-07-31T18:12:59.226Z`
  **NeKI brief:** FreeTypeFramework packages the FreeType font engine for Apple-platform projects, making font parsing and rasterization available through a reusable framework. The repository is a useful starting point when system font APIs do not cover a custom rendering pipeline.
- [Horoscope](https://github.com/artemnovichkov/horoscope) — iOS Dev Tools · iOS Dev Tools: FreeTypeFramework, IGListKit, Horoscope — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **Published:** `2025-07-31T18:12:59.226Z`
  **NeKI brief:** Horoscope generates developer-oriented output with Apple's Foundation Models, making it a compact example of on-device model integration. Useful for inspecting prompt-to-result plumbing and the availability assumptions of current Apple AI APIs.
- [GitHub repository](https://github.com/AvdLee/CoreDataBestPractices) — SwiftLee Weekly · Issue 282 — Source repository · Topics: Core Data · Developer Tools · Persistence & Synchronisation
  **Published:** `2025-07-29T14:14:45.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for GitHub repository. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [current code](https://projects.blender.org/blender/blender.git) — Fatbobman’s Swift Weekly · Issue 95 — Tutorial · Topics: Developer Tools · Graphics, Media & Games · Xcode
  **Published:** `2025-07-28T12:02:57.187Z`
  **NeKI brief:** Blender is a large open-source 3D creation suite with a mature cross-platform codebase. Use the repository as a comparison point for graphics tooling and architecture, not as a Swift or Apple UI dependency.
- [Uncertain](https://github.com/mattt/Uncertain) — Fatbobman’s Swift Weekly · Issue 95 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2025-07-28T12:02:57.187Z`
  **NeKI brief:** Uncertain models values with explicit uncertainty rather than pretending sensor, location, or network-derived inputs are exact. Use it when an API must carry confidence or variance through decisions instead of collapsing ambiguous data prematurely.
- [Foundation Models Framework Example](https://github.com/rudrankriyam/Foundation-Models-Framework-Example) — iOS Dev Weekly · Issue 719 — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **Published:** `25th July 2025`
  **NeKI brief:** This source repository covers a practical lab for building, testing, and evaluating Apple Foundation Models apps. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [XCFolder](https://github.com/ZhgChgLi/XCFolder) — iOS Dev Tools · iOS Dev Tools: XCFolder, Mocking Star, SwiftPostgresClient — Source repository · Topics: Developer Tools · Xcode
  **Published:** `2025-07-24T17:41:16.681Z`
  **NeKI brief:** XCFolder converts Xcode's virtual groups into real directories, aligning project structure with filesystem-based generators such as Tuist and XcodeGen. Useful for reducing project-file drift while planning a source-tree migration.
- [Mocking Star](https://github.com/Trendyol/mockingstar) — iOS Dev Tools · iOS Dev Tools: XCFolder, Mocking Star, SwiftPostgresClient — Source repository · Topics: Developer Tools · Testing
  **Published:** `2025-07-24T17:41:16.681Z`
  **NeKI brief:** Mocking Star focuses on HTTP request mocking for network debugging and UI tests. Useful for creating deterministic response scenarios while comparing a dedicated mock server or interceptor with hand-written URLProtocol fixtures.
- [SwiftPostgresClient](https://github.com/willtemperley/swift-postgres-client) — iOS Dev Tools · iOS Dev Tools: XCFolder, Mocking Star, SwiftPostgresClient — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2025-07-24T17:41:16.681Z`
  **NeKI brief:** swift-postgres-client supplies a pure-Swift PostgreSQL client, exposing database connectivity without requiring a C driver wrapper. Useful for evaluating async database access in Swift services while checking pooling, TLS, and query-lifecycle needs.
- [ImplementedSE-0470Global-actor isolated conformances](https://github.com/apple/swift-evolution/blob/main/proposals/0470-isolated-conformances.md) — SwiftLee Weekly · Issue 281 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2025-07-22T14:08:43.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0470Global-actor isolated conformances. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0466Control default actor isolation inference](https://github.com/apple/swift-evolution/blob/main/proposals/0466-control-default-actor-isolation.md) — SwiftLee Weekly · Issue 280 — Source repository · Topics: AI Development · Concurrency · Swift
  **Published:** `2025-07-15T14:13:29.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0466Control default actor isolation inference. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ImplementedSE-0464UTF8Span: Safe UTF-8 Processing Over Contiguous Bytes](https://github.com/apple/swift-evolution/blob/main/proposals/0464-utf8span-safe-utf8-processing.md) — SwiftLee Weekly · Issue 279 — Source repository · Topics: Developer Tools · Liquid Glass · Swift
  **Published:** `2025-07-08T13:08:44.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0464UTF8Span: Safe UTF-8 Processing Over Contiguous Bytes. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ASO.report](https://aso.report/) — iOS Dev Tools · iOS Dev Tools: QuickLook, ASO.report, GitProbe — Article · Topics: Developer Tools
  **Published:** `2025-07-03T19:16:57.125Z`
  **NeKI brief:** ASO Report aggregates App Store optimization intelligence such as keyword, competitor, and ranking signals. Use it to structure market research and experiment tracking, validating data freshness and methodology before making publishing decisions.
- [GitProbe](https://github.com/git-probe/gitprobe) — iOS Dev Tools · iOS Dev Tools: QuickLook, ASO.report, GitProbe — Source repository · Topics: Developer Tools
  **Published:** `2025-07-03T19:16:57.125Z`
  **NeKI brief:** GitProbe changes a GitHub URL into an LLM-friendly codebase view, emphasizing structure discovery before code inspection. Useful for agent-assisted repository orientation when a full clone or broad file dump is unnecessary.
- [JustLockIn](https://github.com/spaceman1412/justlockin) — iOS Dev Tools · iOS Dev Tools: QuickLook, ASO.report, GitProbe — Source repository · Topics: Developer Tools
  **Published:** `2025-07-03T19:16:57.125Z`
  **NeKI brief:** JustLockIn is a minimalist macOS menu-bar Pomodoro timer controlled from a single click. Useful for examining a deliberately narrow focus workflow and the interaction cost of persistent desktop reminders.
- [ImplementedSE-0472Starting tasks synchronously from caller context](https://github.com/apple/swift-evolution/blob/main/proposals/0472-task-start-synchronously-on-caller-context.md) — SwiftLee Weekly · Issue 278 — Source repository · Topics: Developer Community & Business · Developer Tools · Swift
  **Published:** `2025-07-01T14:14:53.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0472Starting tasks synchronously from caller context. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ImplementedSE-0456Add `Span`-providing Properties to Standard Library Types](https://github.com/apple/swift-evolution/blob/main/proposals/0456-stdlib-span-properties.md) — SwiftLee Weekly · Issue 276 — Source repository · Topics: Developer Tools · Swift · UIKit
  **Published:** `2025-06-17T14:10:56.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0456Add `Span`-providing Properties to Standard Library Types. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ImplementedSE-0465Standard Library Primitives for Nonescapable Types](https://github.com/apple/swift-evolution/blob/main/proposals/0465-nonescapable-stdlib-primitives.md) — SwiftLee Weekly · Issue 276 — Source repository · Topics: Developer Tools · Swift · UIKit
  **Published:** `2025-06-17T14:10:56.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0465Standard Library Primitives for Nonescapable Types. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ImplementedSE-0468`Hashable` conformance for `Async(Throwing)Stream.Continuation`](https://github.com/apple/swift-evolution/blob/main/proposals/0468-async-stream-continuation-hashable-conformance.md) — SwiftLee Weekly · Issue 276 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2025-06-17T14:10:56.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0468`Hashable` conformance for `Async(Throwing)Stream.Continuation`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [StructuredQueries](https://github.com/pointfreeco/swift-structured-queries) — Fatbobman’s Swift Weekly · Issue 89 — Source repository · Topics: Developer Tools · Swift · SwiftData
  **Published:** `2025-06-16T12:01:00.435Z`
  **NeKI brief:** StructuredQueries builds SQL with typed Swift structure while preserving SQL's expressive power. Use it when query composition needs compiler assistance but hiding relational behavior behind an ORM would make performance or migrations opaque.
- [SharingGRDB](https://github.com/pointfreeco/sharing-grdb) — Fatbobman’s Swift Weekly · Issue 89 — Source repository · Topics: Developer Tools · Swift · SwiftData
  **Published:** `2025-06-16T12:01:00.435Z`
  **NeKI brief:** SharingGRDB combines shared observable state with GRDB-backed SQLite persistence. Use it when SwiftUI features need low deployment targets and direct SQL control, noting that it does not provide mature cross-device synchronization.
- [Dragula](https://github.com/mufasayc/Dragula) — Fatbobman’s Swift Weekly · Issue 89 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2025-06-16T12:01:00.435Z`
  **NeKI brief:** Dragula brings customizable drag-and-drop interactions to SwiftUI using UIKit for precise gesture behavior. Use it when standard SwiftUI reordering is insufficient and the interface needs configurable movement, drop targets, or visual feedback.
- [AI Git Narrator](https://github.com/pmusolino/AI-Git-Narrator) — iOS Dev Tools · iOS Dev Tools: AI Git Narrator, OAuthKit, FlipKit — Source repository · Topics: AI Development · Developer Tools
  **Published:** `2025-06-12T19:41:45.540Z`
  **NeKI brief:** AI-Git-Narrator generates commit messages and pull-request descriptions from staged or unstaged changes, with configurable model parameters. Useful for evaluating automated repository communication while keeping the diff as the source of truth.
- [OAuthKit](https://github.com/codefiesta/OAuthKit) — iOS Dev Tools · iOS Dev Tools: AI Git Narrator, OAuthKit, FlipKit — Source repository · Topics: Architecture · Combine & Reactive Programming · Swift
  **Published:** `2025-06-12T19:41:45.540Z`
  **NeKI brief:** OAuthKit provides an observable Swift framework for OAuth 2.0 authorization flows, centralizing state and callback handling. Useful for comparing a reusable authentication boundary with endpoint-specific browser-session code.
- [Discussion on Flutter’s Support for Liquid Glass](https://github.com/flutter/flutter/issues/170310) — Fatbobman’s Swift Weekly · Issue 88 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Liquid Glass
  **Published:** `2025-06-12T02:52:10.753Z`
  **NeKI brief:** This Flutter issue discusses support for Apple's Liquid Glass redesign and related platform integration concerns. Follow the thread for cross-platform implementation constraints and status, not as a guarantee of shipped Flutter behavior.
- [Enable Apple AI](https://github.com/kanshurichard/enableAppleAI) — Fatbobman’s Swift Weekly · Issue 88 — Source repository · Topics: AI Development · Developer Tools · Xcode
  **Published:** `2025-06-12T02:52:10.753Z`
  **NeKI brief:** EnableAppleAI collects experiments for enabling or examining Apple Intelligence features on unsupported configurations. Treat it as an exploratory and potentially fragile project; validate security, compatibility, and policy implications before use.
- [WWDC 2025 Group Lab Transcript](https://gist.github.com/samhenrigold) — Fatbobman’s Swift Weekly · Issue 88 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools
  **Published:** `2025-06-12T02:52:10.753Z`
  **NeKI brief:** Provides a concrete technical reference through WWDC 2025 Group Lab Transcript, useful for examining the surrounding design, tooling, or ecosystem discussion before choosing an implementation direction.
- [DataScoutCompanion](https://github.com/alex566/DataScoutCompanion) — Fatbobman’s Swift Weekly · Issue 87 — Source repository · Topics: Developer Tools · Swift · SwiftData
  **Published:** `2025-06-07T12:01:11.599Z`
  **NeKI brief:** DataScoutCompanion is an open-source companion for inspecting application data during development. Use it when debugging data flows needs a dedicated in-app inspection surface rather than scattered temporary logging statements.
- [the original post from Pedro Piñera,](https://swifttoolkit.dev/posts/distribute-swift-clis) — iOS Dev Weekly · Issue 713 — Article · Topics: Developer Tools · Swift
  **Published:** `6th June 2025`
  **NeKI brief:** This article covers distributing Swift command-line tools for macOS. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [ImmutableData-FoodTruck](https://github.com/Swift-ImmutableData/ImmutableData-FoodTruck) — Fatbobman’s Swift Weekly · Issue 85 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2025-05-26T12:01:23.043Z`
  **NeKI brief:** ImmutableData-FoodTruck is a migration tutorial showing incremental adoption of immutable-data patterns in a sample app. Use it to study a staged refactor rather than attempting to convert an existing mutable model all at once.
- [Supercharge your GitHub Actions with fully managed M4 Pro runners from Cirrus Labs](https://cirrus-runners.app/) — iOS Dev Tools · iOS Dev Tools: Bullseye, ProgressUI, Harmonize — Article · Topics: Developer Tools · Testing
  **Published:** `2025-05-22T17:27:20.321Z`
  **NeKI brief:** Describes managed M4 Pro runners for GitHub Actions workloads. Use it to evaluate faster macOS CI capacity, queue behavior, and cost before moving iOS builds to hosted hardware.
- [ProgressUI](https://github.com/PierreJanineh-com/ProgressUI) — iOS Dev Tools · iOS Dev Tools: Bullseye, ProgressUI, Harmonize — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2025-05-22T17:27:20.321Z`
  **NeKI brief:** ProgressUI supplies SwiftUI progress components for determinate and indeterminate work, allowing progress presentation to be composed without rebuilding indicator state in every screen. It is useful for comparing lightweight UI primitives with bespoke animation code.
- [Harmonize](https://github.com/perrystreetsoftware/Harmonize) — iOS Dev Tools · iOS Dev Tools: Bullseye, ProgressUI, Harmonize — Source repository · Topics: Architecture · Swift · Testing
  **Published:** `2025-05-22T17:27:20.321Z`
  **NeKI brief:** Harmonize coordinates shared state and communication across SwiftUI views, addressing the friction of passing bindings and environment values through deeper hierarchies. Its implementation is a concrete reference for reducing view wiring while keeping data flow explicit.
- [MenuScores](https://github.com/daniyalmaster693/MenuScores) — iOS Dev Tools · iOS Dev Tools: Bullseye, ProgressUI, Harmonize — Source repository · Topics: Developer Tools · macOS & AppKit
  **Published:** `2025-05-22T17:27:20.321Z`
  **NeKI brief:** MenuScores displays live sports scores in a macOS menu-bar or notch-oriented surface. Useful as a compact example of polling, transient status presentation, and constrained desktop UI layout.
- [AcceptedSE-0471Improved Custom SerialExecutor isolation checking for Concurrency Runtime](https://github.com/apple/swift-evolution/blob/main/proposals/0471-SerialExecutor-isIsolated.md) — SwiftLee Weekly · Issue 272 — Source repository · Topics: App Services & Extensions · Swift · Testing
  **Published:** `2025-05-20T14:12:58.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0471Improved Custom SerialExecutor isolation checking for Concurrency Runtime. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [SE-475: Transactional Observation of Values](https://github.com/swiftlang/swift-evolution/blob/main/proposals/0475-observed.md) — SwiftLee Weekly · Issue 272 — Source repository · Topics: Combine & Reactive Programming · Developer Tools · Swift
  **Published:** `2025-05-20T14:12:58.000Z`
  **NeKI brief:** Provides the public source repository for SE-0475. Inspect its implementation, examples, and issue history to evaluate integration boundaries and maintenance trade-offs before depending on it in an Apple-platform project.
- [App Review-safe Swift implementation](https://github.com/sebjvidal/_UIContextMenuAccessoryView-Demo) — Fatbobman’s Swift Weekly · Issue 84 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Swift
  **Published:** `2025-05-19T12:00:44.196Z`
  **NeKI brief:** Demonstrates an App Review-safe Swift approach to context-menu accessory UI inspired by Messages. Use it to understand the public-API boundary and avoid shipping private UIKit techniques that merely reproduce system visuals.
- [MenuWithAView](https://github.com/Aeastr/MenuWithAView) — Fatbobman’s Swift Weekly · Issue 84 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2025-05-19T12:00:44.196Z`
  **NeKI brief:** MenuWithAView adds custom accessory content to SwiftUI context menus based on public implementation techniques. Use it when menu actions need richer inline visual context, while testing behavior across menu presentation environments.
- [SwiftGG 在 GitHub 上的仓库](https://github.com/SwiftGGTeam/the-swift-programming-language-in-chinese) — Fatbobman’s Swift Weekly · Issue 84 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2025-05-19T12:00:44.196Z`
  **NeKI brief:** Maintains a Chinese translation of The Swift Programming Language with contribution workflows in its repository. Use it as a localized learning and translation-maintenance resource, not as the canonical source for evolving language semantics.
- [ImplementedSE-0461Run nonisolated async functions on the caller's actor by default](https://github.com/apple/swift-evolution/blob/main/proposals/0461-async-function-isolation.md) — SwiftLee Weekly · Issue 271 — Source repository · Topics: Concurrency · Swift · Testing
  **Published:** `2025-05-13T09:07:48.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0461Run nonisolated async functions on the caller's actor by default. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [SwiftPamphletApp](https://github.com/ming1016/SwiftPamphletApp) — Fatbobman’s Swift Weekly · Issue 83 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2025-05-12T12:02:48.422Z`
  **NeKI brief:** SwiftPamphletApp is an Apple-ecosystem knowledge-management app combining technical material, notes, and curated reading. Use it as a product reference for personal developer-information organization rather than a framework tutorial.
- [Metatype Keypaths](https://github.com/swiftlang/swift-evolution/blob/main/proposals/0438-metatype-keypath.md) — Fatbobman’s Swift Weekly · Issue 82 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2025-05-05T12:02:30.935Z`
  **NeKI brief:** SE-0438 introduces key paths rooted at metatypes for referring to static members. Use it when generic code needs a type-level projection, while verifying compiler support and syntax in the project's targeted Swift release.
- [Test Scoping Traits](https://github.com/swiftlang/swift-evolution/blob/main/proposals/testing/0007-test-scoping-traits.md) — Fatbobman’s Swift Weekly · Issue 82 — Source repository · Topics: Concurrency · Swift · Testing
  **Published:** `2025-05-05T12:02:30.935Z`
  **NeKI brief:** Proposes Swift Testing scoping traits that use TaskLocal context to establish isolated setup and teardown behavior. Follow it when async tests need predictable per-test environment control without global mutable configuration.
- [its source code is open-sourced](https://github.com/onevcat/vs2x) — Fatbobman’s Swift Weekly · Issue 82 — Source repository · Topics: Developer Community & Business · Developer Tools · Xcode
  **Published:** `2025-05-05T12:02:30.935Z`
  **NeKI brief:** vs2x converts Visual Studio Code color themes into Xcode-compatible themes. Use it when adopting a familiar editor palette in Xcode while keeping the generated theme separate from project source and team build configuration.
- [withValue](https://github.com/pointfreeco/swift-concurrency-extras/blob/main/Sources/ConcurrencyExtras/LockIsolated.swift) — Fatbobman’s Swift Weekly · Issue 82 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2025-05-05T12:02:30.935Z`
  **NeKI brief:** LockIsolated wraps mutable state behind a lock, but separate get and set operations do not make read-modify-write atomic. Use it to study why a single locked mutation closure is safer than exposing individual synchronized accessors.
- [ImplementedSE-0457Expose attosecond representation of `Duration`](https://github.com/apple/swift-evolution/blob/main/proposals/0457-duration-attosecond-represenation.md) — SwiftLee Weekly · Issue 269 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2025-04-29T14:18:33.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0457Expose attosecond representation of `Duration`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ImplementedSE-0462Task Priority Escalation APIs](https://github.com/apple/swift-evolution/blob/main/proposals/0462-task-priority-escalation-apis.md) — SwiftLee Weekly · Issue 269 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2025-04-29T14:18:33.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0462Task Priority Escalation APIs. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ImplementedSE-0463Import Objective-C completion handler parameters as `@Sendable`](https://github.com/apple/swift-evolution/blob/main/proposals/0463-sendable-completion-handlers.md) — SwiftLee Weekly · Issue 269 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2025-04-29T14:18:33.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0463Import Objective-C completion handler parameters as `@Sendable`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ErrorKit](https://github.com/FlineDev/ErrorKit) — Fatbobman’s Swift Weekly · Issue 81 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2025-04-28T00:00:42.290Z`
  **NeKI brief:** ErrorKit is an Apple-platform error presentation layer that turns failures into user-facing alerts, sheets, or notifications while keeping error handling composable. The source helps evaluate a centralized approach to reporting errors across SwiftUI and UIKit flows.
- [GRDB](https://github.com/groue/GRDB.swift) — Fatbobman’s Swift Weekly · Issue 81 — Source repository · Topics: Core Data · Swift · SwiftData
  **Published:** `2025-04-28T00:00:42.290Z`
  **NeKI brief:** GRDB.swift is a SQLite toolkit offering query interfaces, migrations, observations, and record mapping. Use it when an app needs transparent relational persistence and reactive database changes without SwiftData's deployment and sync assumptions.
- [DataScout](https://data-scout.pages.dev/) — iOS Dev Tools · iOS Dev Tools: AppsMan, ErrorKit, DataScout — Article · Topics: Core Data · Cross-Platform & Web · Persistence & Synchronisation
  **Published:** `2025-04-24T13:08:49.536Z`
  **NeKI brief:** Data Scout is a data-exploration project presented as a developer product. Inspect its concrete workflow when comparing small utility apps, data presentation choices, and the cost of maintaining a focused independent product.
- [a starting point in the repository's readme](https://github.com/swiftlang/swift/tree/release/6.2?tab=readme-ov-file) — SwiftLee Weekly · Issue 268 — Source repository · Topics: Developer Tools · Swift · Xcode
  **Published:** `2025-04-22T13:40:18.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for a starting point in the repository's readme. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [update](https://github.com/swiftfiddle/swiftregex) — Fatbobman’s Swift Weekly · Issue 80 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2025-04-21T12:00:29.052Z`
  **NeKI brief:** SwiftRegex converts traditional regular expressions into Swift RegexBuilder expressions with live preview and debugging support. Use it to migrate opaque pattern strings into typed, composable Swift regex code while comparing matching behavior.
- [swift-markdown](https://github.com/swiftlang/swift-markdown) — Fatbobman’s Swift Weekly · Issue 79 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2025-04-14T12:01:43.772Z`
  **NeKI brief:** swift-markdown parses and constructs Markdown using a typed document tree and Visitor traversal. Use it when a tool must transform Markdown structurally rather than applying fragile string replacements to source text.
- [UBI](https://github.com/houseabsolute/ubi) — Fatbobman’s Swift Weekly · Issue 79 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2025-04-14T12:01:43.772Z`
  **NeKI brief:** ubi installs precompiled command-line tool binaries from GitHub releases rather than building them locally. Use it when developer-tool setup must be fast and repeatable across machines, while checking release provenance and platform artifacts.
- [easy-frame](https://github.com/alschmut/EasyFrameCommand) — iOS Dev Tools · iOS Dev Tools: easy-frame, Sweetpad, StoreKitHelper — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Swift
  **Published:** `2025-04-11T07:56:27.598Z`
  **NeKI brief:** EasyFrameCommand is a Swift CLI that creates framed App Store screenshots from custom SwiftUI layouts. Useful for repeatable marketing-image generation that keeps device framing in source-controlled code instead of manual editing.
- [StoreKitHelper](https://github.com/jaywcjlove/StoreKitHelper) — iOS Dev Tools · iOS Dev Tools: easy-frame, Sweetpad, StoreKitHelper — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Swift
  **Published:** `2025-04-11T07:56:27.598Z`
  **NeKI brief:** StoreKitHelper wraps StoreKit 2 for SwiftUI in a lightweight package, reducing repeated purchase and entitlement plumbing. Useful for comparing a small declarative helper with direct StoreKit transaction observation and product loading.
- [Does AsyncStream Replace Combine? No.](https://levelup.gitconnected.com/does-asyncstream-replace-combine-a4fc091a8175) — Those Who Swift · Issue 208 — Article · Topics: Combine & Reactive Programming · Concurrency · Developer Tools
  **Published:** `2025-04-02`
  **NeKI brief:** This article covers the boundary between AsyncStream and Combine. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [ImplementedSE-0444Member import visibility](https://github.com/apple/swift-evolution/blob/main/proposals/0444-member-import-visibility.md) — SwiftLee Weekly · Issue 264 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2025-03-25T15:06:57.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0444Member import visibility. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [mcp-swift-sdk](https://github.com/loopwork-ai/mcp-swift-sdk) — Fatbobman’s Swift Weekly · Issue 76 — Source repository · Topics: AI Development · Apple Platform Ecosystem · Swift
  **Published:** `2025-03-24T12:01:29.089Z`
  **NeKI brief:** mcp-swift-sdk implements Model Context Protocol server and client concepts in Swift. Use it when exposing Apple-platform data or app capabilities to an agent through typed tools rather than maintaining a bespoke JSON protocol.
- [iMCP](https://github.com/loopwork-ai/iMCP) — Fatbobman’s Swift Weekly · Issue 76 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `2025-03-24T12:01:29.089Z`
  **NeKI brief:** iMCP is a macOS MCP server that brokers access to local calendar, contacts, messages, reminders, and weather data. Use it to inspect permission-aware system-data tool design before connecting an agent to personal information.
- [ReviewKit](https://github.com/FlineDev/ReviewKit) — iOS Dev Tools · iOS Dev Tools: Dock, Clippets, ReviewKit — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **Published:** `2025-03-20T17:08:58.928Z`
  **NeKI brief:** ReviewKit records positive user events and requests an App Store review only when configurable satisfaction criteria are met; events expire after a default window. It is a concrete pattern for making review prompts contextual instead of firing on arbitrary launches.
- [SwiftUI: Connect Two Points with Straight Line Segments + Rounded Corners](https://levelup.gitconnected.com/swiftui-connect-two-points-with-straight-line-segments-rounded-corners-dbbad5f27ab4) — Those Who Swift · Issue 206 — Article · Topics: Combine & Reactive Programming · Swift · SwiftUI
  **Published:** `2025-03-19`
  **NeKI brief:** Examines SwiftUI: Connect Two Points with Straight Line Segments + Rounded Corners, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [ImplementedSE-0451Raw identifiers](https://github.com/apple/swift-evolution/blob/main/proposals/0451-escaped-identifiers.md) — SwiftLee Weekly · Issue 263 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2025-03-18T15:01:58.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0451Raw identifiers. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Pull Request](https://github.com/swiftlang/swift/pull/79872) — Fatbobman’s Swift Weekly · Issue 75 — Source repository · Topics: Developer Tools · Performance · Swift
  **Published:** `2025-03-17T12:03:33.484Z`
  **NeKI brief:** Documents a Swift compiler use-after-free issue triggered under -Osize optimization. Use it as a regression and diagnosis reference when release-only crashes suggest optimizer behavior, rather than assuming source-level lifetime safety proves correctness.
- [Swift GraphQL Codegen](https://github.com/pm-dev/swift-graphql-codegen) — iOS Dev Tools · iOS Dev Tools: Swift GraphQL Codegen, HandySwiftUI, Surge — Source repository · Topics: Developer Tools · Networking · Swift
  **Published:** `2025-03-13T19:20:57.517Z`
  **NeKI brief:** Swift GraphQL Codegen generates Swift types and operations from a GraphQL schema, emphasizing correctness and flexible output. Useful for keeping API models synchronized with schema changes without hand-maintaining request and response structs.
- [HandySwiftUI](https://github.com/FlineDev/HandySwiftUI) — iOS Dev Tools · iOS Dev Tools: Swift GraphQL Codegen, HandySwiftUI, Surge — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2025-03-13T19:20:57.517Z`
  **NeKI brief:** This source repository covers SwiftUI utilities that fill gaps in the framework. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [MaClicker](https://github.com/WorldOfBasti/MaClicker) — iOS Dev Tools · iOS Dev Tools: Swift GraphQL Codegen, HandySwiftUI, Surge — Source repository · Topics: Developer Tools · Swift
  **Published:** `2025-03-13T19:20:57.517Z`
  **NeKI brief:** MaClicker is a small macOS auto-clicker implemented as a focused utility. Useful for examining global input automation and the permission boundary such tools require, rather than treating simulated clicks as ordinary app events.
- [Gist](https://gist.github.com/fatbobman/d47e7d11df5ce5d3c42f032e27457eed) — Fatbobman’s Swift Weekly · Issue 74 — Source repository · Topics: Developer Tools · Performance · Swift
  **Published:** `2025-03-10T12:03:47.395Z`
  **NeKI brief:** Collects the article's related source snippets in one Gist for easier comparison and reuse. Use it as a companion code reference, while reading the surrounding analysis for lifecycle and concurrency rationale.
- [ImplementedSE-0458Opt-in Strict Memory Safety Checking](https://github.com/apple/swift-evolution/blob/main/proposals/0458-strict-memory-safety.md) — SwiftLee Weekly · Issue 261 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2025-03-04T15:16:50.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0458Opt-in Strict Memory Safety Checking. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [sample code](https://github.com/artemnovichkov/ShazamKitExample) — Fatbobman’s Swift Weekly · Issue 73 — Source repository · Topics: Concurrency · Developer Career & Practice · Developer Tools
  **Published:** `2025-03-04T01:25:29.647Z`
  **NeKI brief:** ShazamKitExample demonstrates music recognition with ShazamKit's modern async APIs. Use it to trace recognition-result flow without manually coordinating AVAudioEngine callbacks, then adapt audio capture and permissions to the product's needs.
- [ViewInspector](https://github.com/nalexn/ViewInspector) — Fatbobman’s Swift Weekly · Issue 72 — Source repository · Topics: Swift · SwiftUI · Testing
  **Published:** `2025-02-24T12:03:49.550Z`
  **NeKI brief:** ViewInspector enables runtime inspection of SwiftUI view hierarchies in tests. Use it when asserting view structure or extracting state that normal UI tests cannot observe, while keeping tests resilient to intentional implementation changes.
- [Snapshot Testing](https://github.com/pointfreeco/swift-snapshot-testing) — Fatbobman’s Swift Weekly · Issue 72 — Source repository · Topics: Swift · SwiftUI · Testing
  **Published:** `2025-02-24T12:03:49.550Z`
  **NeKI brief:** SnapshotTesting can launch UI tests with a specified content-size category, making large accessibility sizes reproducible in image assertions. Follow it to catch Dynamic Type layout regressions that ordinary interaction tests may miss.
- [SwiftSoup](https://github.com/scinfu/SwiftSoup) — iOS Dev Tools · iOS Dev Tools: TranslateKit, SwiftSoup, InjectionIII — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `2025-02-20T19:09:31.201Z`
  **NeKI brief:** SwiftSoup ports jsoup-style HTML parsing to Swift, including DOM traversal, CSS selectors, sanitization, and WHATWG HTML5 parsing. Use it when extracting or transforming untrusted real-world markup without building a custom tokenizer.
- [AcceptedSE-0453InlineArray, a fixed-size array](https://github.com/apple/swift-evolution/blob/main/proposals/0453-vector.md) — SwiftLee Weekly · Issue 259 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `2025-02-18T15:10:59.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0453InlineArray, a fixed-size array. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ViewList](https://github.com/OpenSwiftUIProject/OpenSwiftUI/tree/main/Sources/OpenSwiftUICore/View/Input) — Fatbobman’s Swift Weekly · Issue 71 — Source repository · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2025-02-17T23:25:21.639Z`
  **NeKI brief:** Points directly into OpenSwiftUI's input-related view sources rather than its repository root. Use it to inspect how an open implementation models input plumbing when debugging or comparing SwiftUI behavior.
- [OpenGraph](https://github.com/OpenSwiftUIProject/OpenGraph) — Fatbobman’s Swift Weekly · Issue 71 — Source repository · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2025-02-17T23:25:21.639Z`
  **NeKI brief:** OpenGraph is an OpenSwiftUI-adjacent graph implementation to study alongside view construction and dependency propagation. Follow it when investigating how declarative UI state can be represented and traversed outside Apple's closed framework.
- [MLX-Outil project](https://github.com/rudrankriyam/MLX-Outil) — Fatbobman’s Swift Weekly · Issue 71 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `2025-02-17T23:25:21.639Z`
  **NeKI brief:** MLX-Outil provides utilities around Apple's MLX machine-learning ecosystem for Swift or Apple-platform experiments. Follow it when evaluating local model tooling, checking supported models, performance, and API stability before production adoption.
- [TranslateKit](https://github.com/FlineDev/TranslateKit) — Fatbobman’s Swift Weekly · Issue 71 — Source repository · Topics: Developer Tools · Localization · Swift
  **Published:** `2025-02-17T23:25:21.639Z`
  **NeKI brief:** TranslateKit packages localization workflows for Swift projects, including translation-oriented tooling around Xcode resources. Follow it when evaluating whether localization synchronization should live in build tooling instead of ad-hoc manual edits.
- [Mint](https://github.com/yonaskolb/Mint) — iOS Dev Tools · iOS Dev Tools: Starview, Mint, Giffy — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-02-13T18:15:48.650Z`
  **NeKI brief:** Mint installs and runs Swift Package Manager command-line tools at project-pinned versions. Use it to make generators, linters, and other developer executables reproducible without committing their binaries or relying on globally installed versions.
- [Giffy](https://github.com/uwaisalqadri/Giffy) — iOS Dev Tools · iOS Dev Tools: Starview, Mint, Giffy — Source repository · Topics: Architecture · Composable Architecture · Swift
  **Published:** `2025-02-13T18:15:48.650Z`
  **NeKI brief:** Giffy is a sample iOS application that combines SwiftUI, The Composable Architecture, and Swinject-based dependency injection. Use it to inspect how those architectural pieces are wired together in a small, runnable project.
- [VS Code extension for Swift update](https://www.swift.org/blog/vscode-swift-2) — Those Who Swift · Issue 201 — Article · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-02-12`
  **NeKI brief:** Introduces updates to the VS Code extension for Swift. Follow it when comparing editor workflows, language-server capabilities, and debugging support outside Xcode, while checking the extension and toolchain versions required by a project.
- [ImplementedSE-0450Package traits](https://github.com/apple/swift-evolution/blob/main/proposals/0450-swiftpm-package-traits.md) — SwiftLee Weekly · Issue 258 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-02-11T15:02:09.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0450Package traits. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [GitHub - swiftlang/swift-build: A high-level build system based on llbuild, used by Xcode, Swift Playground, and the Swift Package ManagerA high-level build system based on llbuild, used by Xcode, Swift Playground, and the Swift Package Manager - swiftlang/swift-buildGitHubswiftlang](https://github.com/swiftlang/swift-build?ref=createwithswift.com) — Create with Swift · Issue 47 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-02-07T16:00:24.000Z`
  **NeKI brief:** Swift Build is the open-sourced build engine behind Xcode and SwiftPM convergence work. Follow it when assessing build-graph architecture, toolchain behavior, and future migration implications for projects that currently rely on opaque Xcode builds.
- [ZIP Foundation](https://github.com/weichsel/ZIPFoundation) — iOS Dev Tools · iOS Dev Tools: Diagnostics, ZIP Foundation, WebKit — Source repository · Topics: Developer Tools · Foundation & Data Formats · Objective-C & Cocoa
  **Published:** `2025-02-06T17:32:00.627Z`
  **NeKI brief:** Provides the public source repository for ZIP Foundation. Inspect its implementation, examples, and issue history to evaluate integration boundaries and maintenance trade-offs before depending on it in an Apple-platform project.
- [Swift Build](https://github.com/swiftlang/swift-build) — SwiftLee Weekly · Issue 257 — Source repository · Topics: Developer Tools · Swift · Xcode
  **Published:** `2025-02-04T14:26:37.000Z`
  **NeKI brief:** Swift Build is the open-sourced build engine behind Xcode and SwiftPM convergence work. Follow it when assessing build-graph architecture, toolchain behavior, and future migration implications for projects that currently rely on opaque Xcode builds.
- [llbuild](https://github.com/swiftlang/swift-llbuild) — Fatbobman’s Swift Weekly · Issue 69 — Source repository · Topics: Swift · Swift Package Manager · Xcode
  **Published:** `2025-02-03T12:01:11.391Z`
  **NeKI brief:** llbuild is the lower-level build-system engine used by Swift tooling. Use it to inspect dependency scheduling and incremental compilation foundations, while keeping its implementation role distinct from the higher-level Swift Build repository.
- [Scale up your snapshot tests, without the friction](https://screenshotbot.io/) — iOS Dev Tools · iOS Dev Tools: SwiftUIX, Vapor, DevCleaner — Article · Topics: Developer Tools · Testing
  **Published:** `2025-01-30T15:53:21.682Z`
  **NeKI brief:** Provides Screenshotbot’s service for collecting and reviewing visual test artifacts. Use it to assess snapshot-test workflows, change review, and CI integration before selecting a visual regression platform.
- [Vapor](https://github.com/vapor/vapor) — iOS Dev Tools · iOS Dev Tools: SwiftUIX, Vapor, DevCleaner — Source repository · Topics: Developer Tools · Swift
  **Published:** `2025-01-30T15:53:21.682Z`
  **NeKI brief:** Provides the public source repository for Vapor. Inspect its implementation, examples, and issue history to evaluate integration boundaries and maintenance trade-offs before depending on it in an Apple-platform project.
- [Debugging An Undebuggable App](https://bryce.co/undebuggable) — SwiftLee Weekly · Issue 256 — Article · Topics: Dependency Injection · Developer Tools
  **Published:** `2025-01-28T15:11:34.000Z`
  **NeKI brief:** Explains Debugging An Undebuggable App, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [AcceptedSE-0454Custom Allocator for Toolchain](https://github.com/apple/swift-evolution/blob/main/proposals/0454-memory-allocator.md) — SwiftLee Weekly · Issue 256 — Source repository · Topics: Developer Tools · Swift · Systems Programming
  **Published:** `2025-01-28T15:11:34.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0454Custom Allocator for Toolchain. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [SE-0292](https://forums.swift.org/t/se-0292-package-registry-service/42623) — Fatbobman’s Swift Weekly · Issue 68 — Article · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2025-01-27T01:05:46.208Z`
  **NeKI brief:** SE-0292 defines a package-registry protocol and service model for SwiftPM dependencies. Follow it when designing package distribution, authentication, and version-resolution infrastructure beyond Git URL fetching.
- [partnership with GitHub](https://github.blog/news-insights/product-news/github-package-registry-will-support-swift-packages) — iOS Dev Weekly · Issue 696 — Article · Topics: Developer Tools · Swift · Xcode
  **Published:** `24th January 2025`
  **NeKI brief:** Presents partnership with github for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [JFrog](https://jfrog.com/integrations/swift-repository) — iOS Dev Weekly · Issue 696 — Article · Topics: Developer Tools · Swift · Xcode
  **Published:** `24th January 2025`
  **NeKI brief:** Presents jfrog for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Cloudsmith](https://cloudsmith.com/product/formats/swift) — iOS Dev Weekly · Issue 696 — Article · Topics: Developer Tools · Swift · Xcode
  **Published:** `24th January 2025`
  **NeKI brief:** Presents cloudsmith for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Mogenerator](https://github.com/rentzsch/mogenerator) — iOS Dev Tools · iOS Dev Tools: Mogenerator, xcpretty, vscode-swift — Source repository · Topics: Core Data · Developer Tools · Objective-C & Cocoa
  **Published:** `2025-01-23T15:15:36.631Z`
  **NeKI brief:** mogenerator reads a Core Data model and generates separate machine and human subclasses for managed objects. Use it in legacy Core Data projects that need repeatable typed accessors while preserving hand-written behavior across model regeneration.
- [xcpretty](https://github.com/xcpretty/xcpretty) — iOS Dev Tools · iOS Dev Tools: Mogenerator, xcpretty, vscode-swift — Source repository · Topics: Developer Tools · Xcode
  **Published:** `2025-01-23T15:15:36.631Z`
  **NeKI brief:** xcpretty reformats xcodebuild output into readable build, test, and failure summaries and can emit CI-friendly reports. Use it when raw compiler logs obscure the actionable failure, while retaining the original log as diagnostic evidence.
- [vscode-swift](https://github.com/swiftlang/vscode-swift) — iOS Dev Tools · iOS Dev Tools: Mogenerator, xcpretty, vscode-swift — Source repository · Topics: Developer Tools · Swift
  **Published:** `2025-01-23T15:15:36.631Z`
  **NeKI brief:** The official Swift extension for VS Code adds completion, navigation, package dependency management, build and test tasks, and CodeLLDB debugging. It is a practical reference for using Swift outside Xcode while retaining language-service tooling.
- [SwiftData CRUD Operations with ModelActor](https://brightdigit.com/tutorials/swiftdata-crud-operations-modelactor) — Those Who Swift · Issue 198 — Tutorial · Topics: Concurrency · Swift · SwiftData
  **Published:** `2025-01-23`
  **NeKI brief:** Examines SwiftData CRUD Operations with ModelActor, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [project](https://github.com/arrinal/ios-clean-architecture-project) — Fatbobman’s Swift Weekly · Issue 67 — Source repository · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2025-01-20T12:03:32.506Z`
  **NeKI brief:** Offers a concrete iOS Clean Architecture project layout rather than a conceptual diagram. Follow it to inspect boundaries between presentation, domain, and data layers and judge the ceremony against a real app.
- [backend service](https://github.com/arrinal/sample-service-swift-vapor) — Fatbobman’s Swift Weekly · Issue 67 — Source repository · Topics: Architecture · Developer Tools · Swift
  **Published:** `2025-01-20T12:03:32.506Z`
  **NeKI brief:** Pairs a Swift service example with Vapor, making the repository useful for tracing request handling and application-layer separation. Follow it when comparing server-side Swift structure with client architecture conventions.
- [Swift Bundler](https://github.com/stackotter/swift-bundler) — iOS Dev Tools · iOS Dev Tools: Swift Bundler, Swift for Visual Studio Code, iOS-uploader — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-01-16T21:51:40.196Z`
  **NeKI brief:** Swift Bundler wraps package creation, building, running, and testing in a single cross-platform workflow, with templates and Xcode integration. It helps compare a package-centric toolchain with manually maintained project and distribution scripts.
- [iOS-uploader](https://github.com/simonnilsson/ios-uploader) — iOS Dev Tools · iOS Dev Tools: Swift Bundler, Swift for Visual Studio Code, iOS-uploader — Source repository · Topics: App Distribution & Store Operations · Cross-Platform & Web · Developer Tools
  **Published:** `2025-01-16T21:51:40.196Z`
  **NeKI brief:** A cross-platform command-line uploader for App Store Connect that accepts familiar altool-style arguments and can upload multiple apps concurrently. Its prebuilt binaries and npm installation make it relevant when CI must publish from Windows, Linux, or macOS.
- [Active ReviewSE-0455SwiftPM @testable build setting](https://github.com/apple/swift-evolution/blob/main/proposals/0455-swiftpm-testable-build-setting.md) — SwiftLee Weekly · Issue 254 — Source repository · Topics: Objective-C & Cocoa · Swift · Testing
  **Published:** `2025-01-14T14:03:25.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0455SwiftPM @testable build setting. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [SE-0364](https://github.com/swiftlang/swift-evolution/blob/main/proposals/0364-retroactive-conformance-warning.md) — Fatbobman’s Swift Weekly · Issue 65 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2025-01-06T12:02:39.656Z`
  **NeKI brief:** SE-0364 proposes warnings for retroactive protocol conformances that can conflict with future declarations. Use it to understand library-evolution hazards and compiler diagnostics when extending types you do not own.
- [MongoKitten](https://github.com/orlandos-nl/MongoKitten) — Fatbobman’s Swift Weekly · Issue 65 — Source repository · Topics: Developer Tools · Foundation & Data Formats · Swift
  **Published:** `2025-01-06T12:02:39.656Z`
  **NeKI brief:** MongoKitten provides a pure-Swift MongoDB driver built on SwiftNIO. Follow it when evaluating asynchronous document-database access, connection lifecycle, and how a Swift server maps BSON operations into application models.
- [Nimble](https://github.com/Quick/Nimble) — iOS Dev Tools · iOS Dev Tools: Finch, Swift-mod, Nimble — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2025-01-02T17:37:26.914Z`
  **NeKI brief:** Provides the public source repository for Nimble. Inspect its implementation, examples, and issue history to evaluate integration boundaries and maintenance trade-offs before depending on it in an Apple-platform project.
- [Sourcery](https://github.com/krzysztofzablocki/Sourcery) — iOS Dev Tools · iOS Dev Tools: Sourcery, FengNiao, EasyStash — Source repository · Topics: Developer Tools · Swift
  **Published:** `2024-12-26T21:45:51.591Z`
  **NeKI brief:** Sourcery parses Swift source with templates to generate repetitive implementations such as mocks, equality, or Codable support. Use it when generated boilerplate has stable conventions and the templates can be reviewed as part of source control.
- [FengNiao](https://github.com/onevcat/FengNiao) — iOS Dev Tools · iOS Dev Tools: Sourcery, FengNiao, EasyStash — Source repository · Topics: Developer Tools · Swift
  **Published:** `2024-12-26T21:45:51.591Z`
  **NeKI brief:** FengNiao scans an iOS project for image and resource references to identify unused assets. Use it as a cleanup candidate generator, then verify dynamic names and storyboard or runtime lookups before deleting anything.
- [EasyStash](https://github.com/onmyway133/EasyStash) — iOS Dev Tools · iOS Dev Tools: Sourcery, FengNiao, EasyStash — Source repository · Topics: Developer Tools
  **Published:** `2024-12-26T21:45:51.591Z`
  **NeKI brief:** EasyStash provides a lightweight cross-platform persistence wrapper for Apple-platform apps. Use it to evaluate a small storage abstraction for simple values, while confirming its serialization, migration, and thread-safety limits against your data requirements.
- [SwiftUIKit](https://github.com/danielsaidi/SwiftUIKit) — Fatbobman’s Swift Weekly · Issue 63 — Source repository · Topics: Swift · SwiftUI · UIKit
  **Published:** `2024-12-23T12:01:34.355Z`
  **NeKI brief:** SwiftUIKit collects reusable UIKit helpers and extensions from Daniel Saidi's ecosystem. Use it as a source of focused implementation patterns when a project needs small UIKit conveniences without adopting a large UI framework.
- [Code for this week's article can be found on GitHub.](https://github.com/AvdLee/SwiftLeeArticlesCode) — SwiftLee Weekly · Issue 250 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2024-12-17T10:30:53.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Code for this week's article can be found on GitHub.. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [vision document](https://github.com/hborla/swift-evolution/blob/approachable-concurrency-vision/visions/approachable-concurrency.md) — Fatbobman’s Swift Weekly · Issue 62 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2024-12-16T12:01:20.048Z`
  **NeKI brief:** The approachable-concurrency vision frames migration barriers and proposed defaults for making isolation easier to adopt. Use it to connect compiler diagnostics and project settings with a staged Swift 6 concurrency rollout.
- [Wormholy](https://github.com/pmusolino/Wormholy) — iOS Dev Tools · iOS Dev Tools: Wormholy, Bagbutik, Kintsugi — Source repository · Topics: Developer Tools
  **Published:** `2024-12-12T14:42:27.564Z`
  **NeKI brief:** Provides the public source repository for Wormholy. Inspect its implementation, examples, and issue history to evaluate integration boundaries and maintenance trade-offs before depending on it in an Apple-platform project.
- [Kintsugi](https://github.com/Lightricks/Kintsugi) — iOS Dev Tools · iOS Dev Tools: Wormholy, Bagbutik, Kintsugi — Source repository · Topics: Developer Tools · Xcode
  **Published:** `2024-12-12T14:42:27.564Z`
  **NeKI brief:** Kintsugi helps resolve project.pbxproj merge conflicts by extracting each side’s changes and reapplying them through project-file editing. Use it when Xcode project conflicts are too structured for a normal text merge, then open and build the result.
- [TCA](https://github.com/pointfreeco/swift-composable-architecture) — Fatbobman’s Swift Weekly · Issue 61 — Source repository · Topics: Architecture · Composable Architecture · Swift
  **Published:** `2024-12-09T12:00:43.829Z`
  **NeKI brief:** The Composable Architecture structures feature state, actions, reducers, dependencies, and tests around explicit unidirectional flow. Use the repository and migration material to evaluate operational trade-offs before adopting or upgrading TCA in a production app.
- [Sharing](https://github.com/pointfreeco/swift-sharing) — Fatbobman’s Swift Weekly · Issue 61 — Source repository · Topics: Composable Architecture · Developer Tools · Swift
  **Published:** `2024-12-09T12:00:43.829Z`
  **NeKI brief:** Sharing provides `@Shared` state with persistence strategies spanning app storage, files, memory, and external stores. Follow it when routing shared SwiftUI/UIKit state while keeping observation and persistence concerns explicit.
- [SnapshotPreviews](https://github.com/EmergeTools/SnapshotPreviews) — Fatbobman’s Swift Weekly · Issue 60 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2024-12-02T12:03:20.977Z`
  **NeKI brief:** SnapshotPreviews captures SwiftUI previews as image artifacts for repeatable visual comparison. Follow it when preview states need regression coverage in CI without driving the full application UI.
- [Advent of Code Starter Template](https://github.com/swiftlang/swift-aoc-starter-example) — Fatbobman’s Swift Weekly · Issue 60 — Source repository · Topics: Developer Tools · Swift · Xcode
  **Published:** `2024-12-02T12:03:20.977Z`
  **NeKI brief:** Swift's Advent of Code starter template demonstrates a package and command-line workflow outside Xcode. Use it to bootstrap reproducible exercises and inspect the minimum project structure needed for SwiftPM-based development.
- [Time-Based View Updates in SwiftUI](https://digitalbunker.dev/time-based-view-updates-in-swiftui?ref=createwithswift.com) — Create with Swift · Issue 38 — Article · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2024-11-29T16:30:38.000Z`
  **NeKI brief:** Presents Time-Based View Updates in SwiftUI, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Time-Based View Updates in SwiftUI](https://digitalbunker.dev/time-based-view-updates-in-swiftui) — SwiftLee Weekly · Issue 247 — Article · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2024-11-26T15:01:34.000Z`
  **NeKI brief:** Presents Time-Based View Updates in SwiftUI, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [SwiftUI Experiments](https://github.com/mikelikesdesign/SwiftUI-experiments) — iOS Dev Weekly · Issue 688 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `22nd November 2024`
  **NeKI brief:** Presents swiftui experiments for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Copilot is now available in Xcode (and it’s good!)](https://www.swiftwithvincent.com/blog/copilot-is-available-in-xcode) — SwiftLee Weekly · Issue 246 — Article · Topics: AI Development · Swift · Xcode
  **Published:** `2024-11-19T12:58:52.000Z`
  **NeKI brief:** Presents Copilot is now available in Xcode (and it’s good!), focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [swift-format](https://github.com/swiftlang/swift-format) — SwiftLee Weekly · Issue 245 — Source repository · Topics: Developer Tools · Swift · Xcode
  **Published:** `2024-11-12T19:03:27.000Z`
  **NeKI brief:** swift-format is the official Swift formatter and linter. Use it to enforce formatting consistently in local development and CI without relying on editor-specific whitespace settings.
- [ImplementedSE-0106Add a `macOS` Alias for the `OSX` Platform Configuration Test](https://github.com/apple/swift-evolution/blob/main/proposals/0106-rename-osx-to-macos.md) — SwiftLee Weekly · Issue 245 — Source repository · Topics: Developer Tools · macOS & AppKit · Swift
  **Published:** `2024-11-12T19:03:27.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0106Add a `macOS` Alias for the `OSX` Platform Configuration Test. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ImplementedSE-0449Allow `nonisolated` to prevent global actor inference](https://github.com/apple/swift-evolution/blob/main/proposals/0449-nonisolated-for-global-actor-cutoff.md) — SwiftLee Weekly · Issue 245 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2024-11-12T19:03:27.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0449Allow `nonisolated` to prevent global actor inference. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Being Sendable with SwiftData](https://brightdigit.com/tutorials/swiftdata-sendable?issue=057) — Fatbobman’s Swift Weekly · Issue 57 — Tutorial · Topics: Concurrency · Swift · SwiftData
  **Published:** `2024-11-11T12:03:02.180Z`
  **NeKI brief:** Explains Sendable boundaries around SwiftData models and persistence access. Use it when concurrency checking exposes non-Sendable model crossings and you need to decide where actors or value projections belong.
- [SwiftFormat](https://github.com/nicklockwood/SwiftFormat) — Fatbobman’s Swift Weekly · Issue 57 — Source repository · Topics: Developer Tools · Swift · Xcode
  **Published:** `2024-11-11T12:03:02.180Z`
  **NeKI brief:** SwiftFormat offers configurable source-formatting rules and a mature command-line workflow. Follow it when comparing formatter policy, rule customization, and repository integration against Apple's swift-format rather than treating formatting as purely cosmetic.
- [announcement of a new Xcode plug-in](https://github.blog/changelog/2024-10-29-github-copilot-code-completion-in-xcode-is-now-available-in-public-preview) — iOS Dev Weekly · Issue 686 — Article · Topics: AI Development · Developer Tools · Xcode
  **Published:** `8th November 2024`
  **NeKI brief:** Records GitHub Copilot code completion becoming available in Xcode public preview, including the integration’s scope at that point. Useful historical release context when evaluating Xcode-native AI completion capabilities against current tooling and team policy.
- [Shx Guo’s plugin](https://github.com/intitni/CopilotForXcode) — iOS Dev Weekly · Issue 686 — Source repository · Topics: AI Development · Developer Tools · Xcode
  **Published:** `8th November 2024`
  **NeKI brief:** Describes Copilot for Xcode, focusing on practical tool integration and workflow trade-offs. Use it to evaluate reproducibility, trust boundaries, and debugging steps before adopting the approach in an Xcode project.
- [TrustKit](https://github.com/datatheorem/TrustKit) — iOS Dev Tools · iOS Dev Tools: TrustKit, CocoaLumberjack, Tart — Source repository · Topics: Developer Tools · Security & Privacy
  **Published:** `2024-11-07T18:01:24.658Z`
  **NeKI brief:** An open-source iOS and macOS framework for SSL public-key pinning. It centralizes pinning policies, validates server identity, blocks man-in-the-middle connections, and reports validation failures, making the repository useful when hardening app networking.
- [CocoaLumberjack](https://github.com/CocoaLumberjack/CocoaLumberjack) — iOS Dev Tools · iOS Dev Tools: TrustKit, CocoaLumberjack, Tart — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2024-11-07T18:01:24.658Z`
  **NeKI brief:** A configurable logging framework for Apple platforms that routes messages to destinations such as console, files, or remote servers. Its filtering and low-overhead logging model is useful when designing diagnostics that remain practical in production builds.
- [GitHub Copilot for Xcode](https://dimillian.medium.com/github-copilot-for-xcode-62931a645173) — SwiftLee Weekly · Issue 244 — Article · Topics: AI Development · Developer Tools · Xcode
  **Published:** `2024-11-05T21:06:10.000Z`
  **NeKI brief:** Presents GitHub Copilot for Xcode, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [ProtobufKit](https://github.com/OpenSwiftUIProject/ProtobufKit) — Fatbobman’s Swift Weekly · Issue 56 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2024-11-04T12:02:30.932Z`
  **NeKI brief:** ProtobufKit explores Protocol Buffers integration in the OpenSwiftUI ecosystem. Use it when evaluating generated message models and serialization boundaries for SwiftUI-oriented applications.
- [Word??](https://github.blog/changelog/2024-10-29-github-copilot-code-completion-in-xcode-is-now-available-in-public-preview?ref=createwithswift.com) — Create with Swift · Issue 34 — Article · Topics: AI Development · Developer Tools · Swift
  **Published:** `2024-11-01T19:30:40.000Z`
  **NeKI brief:** Records GitHub Copilot code completion becoming available in Xcode public preview, including the integration’s scope at that point. Useful historical release context when evaluating Xcode-native AI completion capabilities against current tooling and team policy.
- [App development on iPad](https://mutatingfunc.github.io/blog/2024-10-12-app-development-on-ipad) — iOS Dev Weekly · Issue 684 — Article · Topics: Developer Tools · Testing
  **Published:** `25th October 2024`
  **NeKI brief:** Presents app development on ipad for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [SwipeActions](https://github.com/aheze/SwipeActions) — iOS Dev Tools · iOS Dev Tools: FeaturesKit, SwipeActions, Carthage — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2024-10-24T17:09:28.334Z`
  **NeKI brief:** SwipeActions adds configurable trailing and leading swipe gestures to arbitrary SwiftUI views rather than only list rows. Use it when a custom collection or card interface needs contextual actions with controlled gesture and animation behavior.
- [Carthage](https://github.com/Carthage/Carthage) — iOS Dev Tools · iOS Dev Tools: FeaturesKit, SwipeActions, Carthage — Source repository · Topics: Dependency Injection · Developer Tools · Objective-C & Cocoa
  **Published:** `2024-10-24T17:09:28.334Z`
  **NeKI brief:** Carthage resolves and builds Cocoa dependencies as frameworks without modifying the Xcode project file. Use it when comparing decentralized binary/framework integration with Swift Package Manager, especially for older projects with explicit dependency wiring.
- [report](https://www.theregister.com/2024/10/15/apples_security_cert_lifespan) — Fatbobman’s Swift Weekly · Issue 54 — Article · Topics: Developer Tools · Security & Privacy
  **Published:** `2024-10-21T12:03:34.069Z`
  **NeKI brief:** Uses report as a practical reference for Apple-platform development, surfacing implementation constraints and workflow trade-offs worth checking before applying the idea in production code.
- [significant change](https://github.com/cabforum/servercert/pull/553) — Fatbobman’s Swift Weekly · Issue 54 — Source repository · Topics: Developer Tools · Security & Privacy
  **Published:** `2024-10-21T12:03:34.069Z`
  **NeKI brief:** Provides a concrete technical reference through significant change, useful for examining the surrounding design, tooling, or ecosystem discussion before choosing an implementation direction.
- [Swift-CowBox](https://github.com/Swift-CowBox/Swift-CowBox) — Fatbobman’s Swift Weekly · Issue 54 — Source repository · Topics: Developer Tools · Macros & Metaprogramming · Swift
  **Published:** `2024-10-21T12:03:34.069Z`
  **NeKI brief:** Swift-CowBox uses macros and copy-on-write wrappers to provide value-like behavior for reference-backed storage. Follow it when performance-sensitive models need controlled mutation semantics without duplicating large buffers.
- [@ObservableDefaults](https://github.com/fatbobman/ObservableDefaults) — Fatbobman’s Swift Weekly · Issue 53 — Source repository · Topics: Observation & State Management · Swift · SwiftUI
  **Published:** `2024-10-14T12:03:14.201Z`
  **NeKI brief:** ObservableDefaults bridges UserDefaults-backed values into SwiftUI observation. Use it when app settings need reactive updates while retaining UserDefaults persistence and predictable key-level storage.
- [ObservableDefaults library](https://github.com/fatbobman/ObservableDefaults?ref=createwithswift.com) — Create with Swift · Issue 31 — Source repository · Topics: Developer Tools · Observation & State Management · Swift
  **Published:** `2024-10-11T15:30:29.000Z`
  **NeKI brief:** ObservableDefaults bridges UserDefaults-backed values into SwiftUI observation. Use it when app settings need reactive updates while retaining UserDefaults persistence and predictable key-level storage.
- [Jazzy](https://github.com/realm/jazzy) — iOS Dev Tools · iOS Dev Tools: Jazzy, Concentric Onboarding, Quick — Source repository · Topics: Developer Tools
  **Published:** `2024-10-10T16:40:59.907Z`
  **NeKI brief:** Jazzy generates Apple-style API documentation from Swift and Objective-C source, including symbol graphs, declarations, and Markdown comments. The repository is useful when setting up repeatable documentation generation as part of a library or CI release pipeline.
- [Concentric Onboarding](https://github.com/exyte/ConcentricOnboarding) — iOS Dev Tools · iOS Dev Tools: Jazzy, Concentric Onboarding, Quick — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2024-10-10T16:40:59.907Z`
  **NeKI brief:** ConcentricOnboarding implements animated concentric-circle transitions for multi-step onboarding in SwiftUI and UIKit. It is a focused reference for coordinating shape scaling, page progression, and custom transition timing without coupling the flow to a single screen layout.
- [Quick](https://github.com/Quick/Quick) — iOS Dev Tools · iOS Dev Tools: Jazzy, Concentric Onboarding, Quick — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2024-10-10T16:40:59.907Z`
  **NeKI brief:** Quick adds a behavior-driven testing DSL for Swift and Objective-C, organizing examples with describe/context blocks and readable expectations. Its companion Nimble matcher style is useful when comparing specification-oriented tests with XCTest assertions.
- [Hummingbird](https://github.com/hummingbird-project/hummingbird) — iOS Dev Tools · iOS Dev Tools: Hummingbird, Apollo iOS, MBProgressHUD — Source repository · Topics: Architecture · Developer Tools · Swift
  **Published:** `2024-10-03T14:43:23.083Z`
  **NeKI brief:** Hummingbird is a modular server framework built on SwiftNIO, offering routing, request handling, and optional server components. Use it when a Swift backend needs a smaller, composable alternative to a more opinionated web framework.
- [Apollo iOS](https://github.com/apollographql/apollo-ios) — iOS Dev Tools · iOS Dev Tools: Hummingbird, Apollo iOS, MBProgressHUD — Source repository · Topics: Developer Tools · Networking · Swift
  **Published:** `2024-10-03T14:43:23.083Z`
  **NeKI brief:** Apollo iOS generates typed Swift GraphQL operations from a schema and manages normalized caching, networking, and code generation. Use it when GraphQL responses should be compiler-checked rather than manually decoded from generic JSON.
- [MBProgressHUD](https://github.com/jdg/MBProgressHUD) — iOS Dev Tools · iOS Dev Tools: Hummingbird, Apollo iOS, MBProgressHUD — Source repository · Topics: App Services & Extensions · Developer Tools
  **Published:** `2024-10-03T14:43:23.083Z`
  **NeKI brief:** MBProgressHUD presents an overlay progress indicator over UIKit content while background work runs. Use it for legacy UIKit flows that need an explicit blocking-progress affordance, while ensuring cancellation and accessibility remain available.
- [Cross-Platform macOS/Windows Application Developed Using Swift 6](https://forums.swift.org/t/example-of-a-cross-platform-macos-windows-application-developed-using-swift-6/74591) — iOS Dev Weekly · Issue 679 — Article · Topics: AI Development · Cross-Platform & Web · Swift
  **Published:** `20th September 2024`
  **NeKI brief:** Presents cross-platform macos/windows application developed using swift 6 for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [available on GitHub](https://github.com/fbarbat/fellmonger) — iOS Dev Weekly · Issue 679 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `20th September 2024`
  **NeKI brief:** Presents available on github for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Retcon](https://retcon.app/) — iOS Dev Tools · iOS Dev Tools: Retcon, Jack, ImpressKit — Article · Topics: Developer Tools
  **Published:** `2024-09-12T15:24:58.073Z`
  **NeKI brief:** Retcon is a macOS Git client focused on fast, visually clear history rewriting. Use it to inspect an alternative workflow for interactive commit editing, while keeping repository safety, collaboration, and recoverability explicit.
- [Github contribution graph with Swift Charts](https://www.artemnovichkov.com/blog/github-contribution-graph-swift-charts) — SwiftUI Weekly · SwiftUI Weekly - Issue #199 — Article · Topics: Developer Tools · Swift
  **Published:** `2024-09-09T19:49:43.177Z`
  **NeKI brief:** Creates a GitHub-style contribution graph with Swift Charts using calendar-shaped data. Useful for practicing custom mark layouts, color scales, and date-based visualization.
- [Alamofire](https://github.com/Alamofire/Alamofire) — iOS Dev Tools · iOS Dev Tools: R.swift, Alamofire, SwiftFormat — Source repository · Topics: Developer Tools · Networking · Swift
  **Published:** `2024-09-05T15:57:02.879Z`
  **NeKI brief:** Alamofire layers request construction, response validation, serialization, upload, and retry facilities over URLSession. Use it when those shared networking policies justify a dependency; otherwise compare its abstractions with direct URLSession code.
- [What's New in SwiftUI - WWDC24](https://yaacoub.github.io/articles/swift-tip/what-s-new-in-swiftui-wwdc24) — SwiftUI Weekly · SwiftUI Weekly - Issue #197 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2024-08-19T10:45:25.615Z`
  **NeKI brief:** Summarizes WWDC24 SwiftUI additions and their intended use cases. Useful as a release-oriented checklist when deciding which iOS 18 APIs can replace custom implementations.
- [Nuke](https://github.com/kean/Nuke) — iOS Dev Tools · iOS Dev Tools: Nuke, dataFude, XcodeGen — Source repository · Topics: Developer Career & Practice · Developer Tools
  **Published:** `2024-08-15T18:31:01.455Z`
  **NeKI brief:** Nuke provides image loading, caching, processing, and prefetching for Apple platforms, with UIKit and SwiftUI integrations. Use it when remote-image behavior needs explicit cache policy, progressive rendering, or processing pipelines beyond a minimal loader.
- [XcodeGen](https://github.com/yonaskolb/XcodeGen) — iOS Dev Tools · iOS Dev Tools: Nuke, dataFude, XcodeGen — Source repository · Topics: Developer Career & Practice · Developer Tools · Xcode
  **Published:** `2024-08-15T18:31:01.455Z`
  **NeKI brief:** XcodeGen generates Xcode projects from a declarative YAML or JSON specification. Use it to make targets, build settings, schemes, and dependencies reviewable text, avoiding fragile manual edits to project.pbxproj files.
- [https://gitbook.swiftgg.team/swift](https://gitbook.swiftgg.team/swift) — Fatbobman’s Swift Weekly · Issue 44 — Article · Topics: Developer Tools · Swift
  **Published:** `2024-08-12T12:00:20.465Z`
  **NeKI brief:** Uses https://gitbook.swiftgg.team/swift as a practical reference for Apple-platform development, surfacing implementation constraints and workflow trade-offs worth checking before applying the idea in production code.
- [Build Multilingual Ready Apps](https://yaacoub.github.io/articles/swift-tip/build-multilingual-ready-apps-wwdc24) — SwiftUI Weekly · SwiftUI Weekly - Issue #196 — Article · Topics: Apple Platform Ecosystem · Developer Tools · Swift
  **Published:** `2024-08-12T10:38:40.828Z`
  **NeKI brief:** Covers WWDC24 localization practices for multilingual Swift apps, including string handling and layout implications. Useful for finding hard-coded assumptions before expanding locale support.
- [Using @DebugDescription in Xcode 16](https://digitalbunker.dev/debug-description-macro-xcode-16?ref=createwithswift.com) — Create with Swift · Issue 23 — Article · Topics: Developer Tools · Macros & Metaprogramming · Xcode
  **Published:** `2024-07-26T15:00:26.000Z`
  **NeKI brief:** Presents using @debugdescription in xcode 16 for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Using @DebugDescription in Xcode 16](https://digitalbunker.dev/debug-description-macro-xcode-16) — iOS Dev Weekly · Issue 671 — Article · Topics: Developer Tools · Macros & Metaprogramming · Xcode
  **Published:** `26th July 2024`
  **NeKI brief:** Presents using @debugdescription in xcode 16 for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [ControlRoom](https://github.com/twostraws/ControlRoom) — iOS Dev Tools · iOS Dev Tools: ControlRoom, SwiftDeps, Starscream — Source repository · Topics: Developer Tools · Xcode
  **Published:** `2024-07-25T15:18:00.048Z`
  **NeKI brief:** ControlRoom is a macOS front end for simctl that manages iOS, tvOS, and watchOS Simulator state. Use it for device launch, screenshots, deep links, permissions, or location testing without repeatedly assembling command-line invocations.
- [Starscream](https://github.com/daltoniam/Starscream) — iOS Dev Tools · iOS Dev Tools: ControlRoom, SwiftDeps, Starscream — Source repository · Topics: Developer Tools · Swift
  **Published:** `2024-07-25T15:18:00.048Z`
  **NeKI brief:** Starscream is a Swift WebSocket client implementing RFC 6455 with TLS, compression, and non-blocking callbacks. Use it when an app needs persistent bidirectional messaging and you must model connection lifecycle, reconnects, and message framing.
- [Infinite4Pager](https://github.com/fatbobman/Infinite4Pager) — Fatbobman’s Swift Weekly · Issue 41 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2024-07-22T12:01:42.375Z`
  **NeKI brief:** Infinite4Pager implements looping pager behavior for SwiftUI, including the index-management concerns of wrapping content. Follow it when evaluating infinite carousels and the state synchronization they require.
- [Blend Modes in SwiftUI](https://digitalbunker.dev/blend-modes-in-swiftui?ref=createwithswift.com) — Create with Swift · Issue 22 — Article · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2024-07-19T16:00:03.000Z`
  **NeKI brief:** Presents a concrete implementation of Blend Modes in SwiftUI. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.
- [Using SwiftUI in Command Line Tools](https://swifttoolkit.dev/posts/swiftui-meets-command-line) — iOS Dev Weekly · Issue 670 — Article · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `19th July 2024`
  **NeKI brief:** Presents using swiftui in command line tools for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Blend Modes in SwiftUI](https://digitalbunker.dev/blend-modes-in-swiftui) — SwiftUI Weekly · SwiftUI Weekly - Issue #194 — Article · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2024-07-15T12:03:07.308Z`
  **NeKI brief:** Presents a concrete implementation of Blend Modes in SwiftUI. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.
- [Swinject](https://github.com/Swinject/Swinject) — iOS Dev Tools · iOS Dev Tools: AppLayoutsUI, Swinject, Pieces Copilot+ — Source repository · Topics: Architecture · Dependency Injection · Developer Tools
  **Published:** `2024-07-11T14:52:09.603Z`
  **NeKI brief:** Swinject resolves object graphs through registered factories and supports scopes such as transient or container lifetime. Use it to compare explicit dependency composition with container-based injection, especially around runtime resolution failures and test overrides.
- [Mastering Animatable and AnimatablePair in SwiftUI](https://digitalbunker.dev/mastering-animatable-and-animatablepair-swiftui) — SwiftUI Weekly · SwiftUI Weekly - Issue #193 — Article · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2024-07-08T08:54:13.719Z`
  **NeKI brief:** Explains Animatable and AnimatablePair for custom SwiftUI interpolation. Useful when building shape or geometry animations whose intermediate values need precise control.
- [Factory](https://github.com/hmlongco/Factory) — iOS Dev Tools · iOS Dev Tools: Anka, Factory, Runme — Source repository · Topics: Architecture · Concurrency · Swift
  **Published:** `2024-07-04T18:41:08.075Z`
  **NeKI brief:** Factory is a Swift dependency-injection container using property wrappers and scoped registrations for SwiftUI and UIKit. Use it when dependency overrides must be concise in previews and tests, while keeping registration ownership visible.
- [Tuist](https://tuist.io/) — iOS Dev Tools · iOS Dev Tools: Pricetag, Tuist, Snapshots — Article · Topics: Architecture · Developer Tools · Foundation & Data Formats
  **Published:** `2024-06-27T16:03:43.649Z`
  **NeKI brief:** Tuist provides project generation and automation for Xcode-based applications. Evaluate it when scaling modular projects, balancing reproducibility and abstraction against Xcode project complexity.
- [AudioKit](https://github.com/AudioKit/AudioKit) — iOS Dev Tools · iOS Dev Tools: Helm, AudioKit, Lottie — Source repository · Topics: Developer Tools
  **Published:** `2024-06-20T13:30:58.118Z`
  **NeKI brief:** Provides the public source repository for AudioKit. Inspect its implementation, examples, and issue history to evaluate integration boundaries and maintenance trade-offs before depending on it in an Apple-platform project.
- [playground](https://github.com/twostraws/whats-new-in-swift-6-0) — iOS Dev Weekly · Issue 665 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `14th June 2024`
  **NeKI brief:** The repository collects examples demonstrating what changed in Swift 6.0. Use it for runnable language-feature examples and migration ideas, while checking the compiler version and proposal status required by each example.
- [A New Direction for Testing in Swift](https://github.com/swiftlang/swift-evolution/blob/main/visions/swift-testing.md) — iOS Dev Weekly · Issue 665 — Source repository · Topics: Developer Tools · Swift · Testing
  **Published:** `14th June 2024`
  **NeKI brief:** Presents a new direction for testing in swift for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [recently accepted](https://github.com/swiftlang/swift-evolution/pull/2466) — iOS Dev Weekly · Issue 665 — Source repository · Topics: Developer Tools · Swift · Testing
  **Published:** `14th June 2024`
  **NeKI brief:** Presents recently accepted for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [What's new in Swift 6.0?](https://github.com/twostraws/whats-new-in-swift-6-0?issue=035) — Fatbobman’s Swift Weekly · Issue 35 — Source repository · Topics: Developer Tools · Swift · Xcode
  **Published:** `2024-06-11T12:03:15.731Z`
  **NeKI brief:** The repository collects examples demonstrating what changed in Swift 6.0. Use it for runnable language-feature examples and migration ideas, while checking the compiler version and proposal status required by each example.
- [老司机技术](https://github.com/SwiftOldDriver/iOS-Weekly) — Fatbobman’s Swift Weekly · Issue 35 — Source repository · Topics: App Distribution & Store Operations · Apple Platform Ecosystem · Developer Tools
  **Published:** `2024-06-11T12:03:15.731Z`
  **NeKI brief:** Indexes Chinese iOS development reading and project links in a repository-friendly format. Use it as a discovery route for community material, then verify each linked source independently before relying on it.
- [SQLite.swift](https://github.com/stephencelis/SQLite.swift) — iOS Dev Tools · iOS Dev Tools: Sw!ftalyzer, Invoice Maker, SQLite.swift — Source repository · Topics: Developer Tools · Persistence & Synchronisation · Swift
  **Published:** `2024-05-30T15:20:30.896Z`
  **NeKI brief:** SQLite.swift wraps SQLite3 in typed Swift query builders and value bindings rather than raw SQL strings alone. Use it when a lightweight relational store needs explicit schemas and transactions without adopting a full object-relational framework.
- [Debugging Animations](https://talk.objc.io/episodes/S01E405-debugging-animations?issue=031) — Fatbobman’s Swift Weekly · Issue 32 — Article · Topics: Developer Tools · Performance · Swift
  **Published:** `2024-05-20T12:02:52.341Z`
  **NeKI brief:** This objc.io episode demonstrates debugging SwiftUI animations through focused experiments and visual inspection. Follow it when diagnosing transaction or interpolation surprises, adapting the techniques to current SDK behavior.
- [Reducing iOS Test execution time with Selective Testing](https://levelup.gitconnected.com/reducing-ios-test-execution-time-with-selective-testing-384879e5f243?issue=031) — Fatbobman’s Swift Weekly · Issue 32 — Article · Topics: Concurrency · Swift · Testing
  **Published:** `2024-05-20T12:02:52.341Z`
  **NeKI brief:** Explains selective testing as a way to shorten iOS test feedback cycles by choosing affected tests. Use it to discuss CI optimization, validating its heuristics against the project's dependency graph and failure-reporting needs.
- [SyncUps](https://github.com/pointfreeco/syncups) — SwiftUI Weekly · SwiftUI Weekly - Issue #186 — Source repository · Topics: Architecture · Developer Tools · Objective-C & Cocoa
  **Published:** `2024-05-15T12:55:37.453Z`
  **NeKI brief:** Provides the SyncUps sample repository with SwiftUI architecture, persistence, and tests. Useful for inspecting concrete implementation trade-offs rather than relying on abstract diagrams.
- [Exporters](https://github.com/huggingface/exporters) — Fatbobman’s Swift Weekly · Issue 31 — Source repository · Topics: AI Development · Developer Tools
  **Published:** `2024-05-13T12:02:47.849Z`
  **NeKI brief:** Hugging Face Exporters converts trained models into deployment-oriented formats and artifacts. Follow it when an iOS ML pipeline needs a reproducible handoff from training output to Core ML or other runtime packaging.
- [LocationSimulator](https://github.com/Schlaubischlump/LocationSimulator) — iOS Dev Tools · iOS Dev Tools: LocationSimulator, EarlGrey 2.0, SwiftUI Introspect — Source repository · Topics: Developer Tools · Testing
  **Published:** `2024-05-09T15:35:40.691Z`
  **NeKI brief:** LocationSimulator is a macOS utility for injecting simulated locations into iOS apps and Simulator targets. Use it to exercise geofencing, map, and route states without a physical device or repeated manual coordinate changes.
- [EarlGrey 2.0](https://github.com/google/EarlGrey/tree/earlgrey2) — iOS Dev Tools · iOS Dev Tools: LocationSimulator, EarlGrey 2.0, SwiftUI Introspect — Source repository · Topics: Combine & Reactive Programming · Developer Tools · Testing
  **Published:** `2024-05-09T15:35:40.691Z`
  **NeKI brief:** EarlGrey 2 combines synchronized white-box UI testing with XCUITest integration for iOS. Use it when black-box assertions cannot reliably wait for app idleness, while considering its framework and maintenance cost against native UI tests.
- [SwiftUI Introspect](https://github.com/siteline/SwiftUI-Introspect) — iOS Dev Tools · iOS Dev Tools: LocationSimulator, EarlGrey 2.0, SwiftUI Introspect — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2024-05-09T15:35:40.691Z`
  **NeKI brief:** SwiftUI Introspect exposes the UIKit or AppKit backing view behind selected SwiftUI controls through version-scoped introspection. Use it for narrowly targeted platform customization when SwiftUI lacks an API, while minimizing reliance on implementation details.
- [Automerge Swift](https://github.com/automerge/automerge-swift) — Fatbobman’s Swift Weekly · Issue 30 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2024-05-06T12:01:46.954Z`
  **NeKI brief:** Automerge Swift brings CRDT-based document synchronization to Swift. Use it when offline-first collaboration requires mergeable edits and conflict resolution rather than last-write-wins persistence.
- [fully open-source and available on GitHub](https://github.com/thebrowsercompany/swift-winrt?ref=createwithswift.com) — Create with Swift · Issue 11 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2024-05-03T15:00:23.000Z`
  **NeKI brief:** swift-winrt generates Swift projections over Windows Runtime and its COM-based ABI. Use it to study cross-platform bindings, generated interop, and the boundary between Swift ergonomics and platform-specific runtime contracts.
- [SwiftLint](https://github.com/realm/SwiftLint) — iOS Dev Tools · [May 2nd] iOS Dev Tools: ShipThatApp, Kingfisher, SwiftLint — Source repository · Topics: Developer Tools · Swift
  **Published:** `2024-05-02T15:20:25.175Z`
  **NeKI brief:** Presents a concrete implementation of SwiftLint. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.
- [MLX](https://github.com/ml-explore/mlx) — Fatbobman’s Swift Weekly · Issue 29 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `2024-04-29T12:02:14.611Z`
  **NeKI brief:** MLX is Apple's research-oriented array and machine-learning framework for Apple Silicon, exposing unified CPU/GPU memory concepts. Useful for evaluating local model experiments outside a Python-only workflow.
- [Converting Codable Models To CSV](https://digitalbunker.dev/converting-codable-models-to-csv?issue=029) — Fatbobman’s Swift Weekly · Issue 29 — Article · Topics: Developer Tools · Foundation & Data Formats · Swift
  **Published:** `2024-04-29T12:02:14.611Z`
  **NeKI brief:** Shows mapping Codable models into CSV rows, including the column-order and value-conversion decisions serialization requires. Follow it when exporting Swift domain data for reports or interoperability rather than JSON APIs.
- [Pulse](https://github.com/kean/Pulse) — iOS Dev Tools · iOS Dev Tools: Pow, Maccy, Pulse — Source repository · Topics: Apple Platform Ecosystem · Developer Tools · Networking
  **Published:** `2024-04-25T13:41:52.260Z`
  **NeKI brief:** Provides the public source repository for Pulse. Inspect its implementation, examples, and issue history to evaluate integration boundaries and maintenance trade-offs before depending on it in an Apple-platform project.
- [HandVector](https://github.com/XanderXu/HandVector) — Fatbobman’s Swift Weekly · Issue 27 — Source repository · Topics: Developer Tools · Spatial Computing
  **Published:** `2024-04-15T22:00:50.399Z`
  **NeKI brief:** HandVector provides hand-pose data structures and utilities for visionOS or spatial interaction experiments. Use it when prototyping gesture input and deciding how tracked joints should cross application boundaries.
- [example code](https://github.com/steipete/OSLogTest/blob/master/LoggingTest/ContentView.swift) — iOS Dev Weekly · Issue 656 — Source repository · Topics: Concurrency · Developer Tools · Testing
  **Published:** `12th April 2024`
  **NeKI brief:** Presents example code for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Adwaita for Swift](https://github.com/AparokshaUI/adwaita-swift) — Fatbobman’s Swift Weekly · Issue 25 — Source repository · Topics: Apple Platform Ecosystem · Developer Community & Business · Swift
  **Published:** `2024-04-01T22:00:13.872Z`
  **NeKI brief:** Adwaita for Swift applies SwiftUI-like declarative ideas to GTK-based Linux applications. Use it when assessing how much view composition can be shared across Apple and Linux UI targets.
- [yolov5](https://github.com/ultralytics/yolov5) — iOS Dev Weekly · Issue 653 — Source repository · Topics: Developer Tools · Swift
  **Published:** `22nd March 2024`
  **NeKI brief:** Presents yolov5 for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Firefoo](https://www.firefoo.app/) — iOS Dev Tools · iOS Dev Tools: Skip, AppLayouts, Firefoo — Article · Topics: Developer Tools
  **Published:** `2024-03-21T14:02:34.735Z`
  **NeKI brief:** Firefoo is a graphical Firestore client for browsing and editing data, running queries, importing or exporting JSON and CSV, and managing users. Use it for local data exploration and debugging without building ad-hoc admin screens.
- [Concurrency Recipes](https://github.com/mattmassicotte/ConcurrencyRecipes) — iOS Dev Weekly · Issue 652 — Source repository · Topics: Concurrency · Developer Tools · Testing
  **Published:** `15th March 2024`
  **NeKI brief:** Collects practical Swift concurrency examples covering isolation, tasks, actors, and Sendable boundaries. Use the repository as a pattern library, adapting each recipe to current Swift 6 diagnostics and your app’s ownership model.
- [strict concurrency for global variables](https://github.com/apple/swift-evolution/blob/main/proposals/0412-strict-concurrency-for-global-variables.md) — Fatbobman’s Swift Weekly · Issue 22 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2024-03-11T22:00:11.596Z`
  **NeKI brief:** The strict-concurrency proposal addresses global-variable isolation and data-race diagnostics. Follow it when auditing shared mutable state and deciding which globals need actor isolation, Sendable wrappers, or removal.
- [the work he did with the Thread Sanitizer](https://github.com/SwiftPackageIndex/SwiftPackageIndex-Server/issues/2321) — iOS Dev Weekly · Issue 651 — Source repository · Topics: Concurrency · Swift · Swift Package Manager
  **Published:** `8th March 2024`
  **NeKI brief:** Presents the work he did with the thread sanitizer for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [SnapshotPreviews](https://github.com/EmergeTools/SnapshotPreviews-iOS) — Fatbobman’s Swift Weekly · Issue 21 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2024-03-04T22:00:16.297Z`
  **NeKI brief:** SnapshotPreviews-iOS provides a UIKit-oriented snapshot workflow for preview-like visual verification. Use it when UIKit screens need deterministic image comparisons alongside SwiftUI preview coverage.
- [SwiftUI](https://github.com/Jinxiansen/SwiftUI) — iOS Dev Tools · iOS Dev tools: SwiftUI, Swifty Compiler, Periphery — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2024-02-29T15:07:10.919Z`
  **NeKI brief:** This repository is a beginner-oriented catalogue of common SwiftUI controls and example usage. Use it as a quick exploratory reference for basic view APIs, not as an architectural guide or a substitute for current Apple documentation.
- [Periphery](https://github.com/peripheryapp/periphery) — iOS Dev Tools · iOS Dev tools: SwiftUI, Swifty Compiler, Periphery — Source repository · Topics: Concurrency · Developer Tools
  **Published:** `2024-02-29T15:07:10.919Z`
  **NeKI brief:** Periphery statically analyzes Swift projects to find unused declarations and code paths. Use its report to drive cleanup reviews in large codebases, but validate dynamic dispatch, reflection, and externally referenced symbols before removal.
- [XcodePluginLoader tool](https://github.com/brycepauken/XcodePluginLoader) — iOS Dev Weekly · Issue 649 — Source repository · Topics: Developer Tools · Xcode
  **Published:** `23rd February 2024`
  **NeKI brief:** Presents xcodepluginloader tool for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Swift Algorithms](https://github.com/apple/swift-algorithms) — Fatbobman’s Swift Weekly · Issue 19 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2024-02-19T22:00:33.358Z`
  **NeKI brief:** Swift Algorithms packages focused sequence and collection operations that complement the standard library. Follow it when a transformation is common enough to reuse but specific enough not to justify an app-local implementation.
- [threading torture test](https://github.com/LucasVanDongen/ThreadTortureTests) — iOS Dev Weekly · Issue 642 — Source repository · Topics: Developer Tools · Swift · Testing
  **Published:** `5th January 2024`
  **NeKI brief:** Presents threading torture test for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Multiliner](https://github.com/aheze/Multiliner) — iOS Dev Tools · 🔨 Micro, Mackup, Multiliner — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2024-01-04T15:45:44.353Z`
  **NeKI brief:** Provides the public source repository for Multiliner. Inspect its implementation, examples, and issue history to evaluate integration boundaries and maintenance trade-offs before depending on it in an Apple-platform project.
- [The Swift Package Index lives on the island of Swiftoria](https://anvaka.github.io/map-of-github) — iOS Dev Weekly · Issue 641 — Article · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `29th December 2023`
  **NeKI brief:** Presents the swift package index lives on the island of swiftoria for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Ice Cubes open-source code](https://github.com/Dimillian/IceCubesApp) — iOS Dev Weekly · Issue 640 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `15th December 2023`
  **NeKI brief:** Provides the public source repository for Ice Cubes. Inspect its implementation, examples, and issue history to evaluate integration boundaries and maintenance trade-offs before depending on it in an Apple-platform project.
- [examples repository](https://github.com/ml-explore/mlx-examples) — iOS Dev Weekly · Issue 639 — Source repository · Topics: AI Development · Developer Tools
  **Published:** `8th December 2023`
  **NeKI brief:** Presents examples repository for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Breadcrumbs](https://github.com/icanzilb/Breadcrumbs) — iOS Dev Weekly · Issue 639 — Source repository · Topics: Developer Tools
  **Published:** `8th December 2023`
  **NeKI brief:** Presents breadcrumbs for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Know your tools](https://khorbushko.github.io/article/2023/11/26/Know-your-tools.html) — Fatbobman’s Swift Weekly · Issue 9 — Article · Topics: Observation & State Management · Swift · SwiftUI
  **Published:** `2023-12-03T22:00:35.768Z`
  **NeKI brief:** Surveys the everyday tools and diagnostics that support Swift development and debugging. Use it as a checklist for improving feedback loops around builds, source inspection, runtime logs, and repeatable project maintenance.
- [Inferno](https://github.com/twostraws/Inferno) — Fatbobman’s Swift Weekly · Issue 7 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `2023-11-20T22:20:48.455Z`
  **NeKI brief:** Inferno is a SwiftUI-focused learning and example repository from Paul Hudson. Useful as a code-reading route for modern view composition, provided examples are checked against the target SDK.
- [ObservationBP](https://github.com/winddpan/ObservationBP) — Fatbobman’s Swift Weekly · Issue 7 — Source repository · Topics: AI Development · Developer Tools
  **Published:** `2023-11-20T22:20:48.455Z`
  **NeKI brief:** ObservationBP back-ports Swift's Observation model for projects that cannot yet use the native deployment baseline. Follow it when weighing compatibility against maintenance and behavioral differences from the current framework implementation.
- [GitHub](https://github.com/GetStream/motionscape-app) — iOS Dev Tools · 🔨 MotionScape, XCTestParametrizedMacro, Swiftly — Source repository · Topics: Developer Tools
  **Published:** `2023-11-16T15:47:07.018Z`
  **NeKI brief:** MotionScape is an open-source SwiftUI animation playground that previews parameterized examples and exports selected settings as production-ready SwiftUI code. Use it to experiment with easing and timing values before hand-writing an animation implementation.
- [XCTestParametrizedMacro](https://github.com/PGSSoft/XCTestParametrizedMacro) — iOS Dev Tools · 🔨 MotionScape, XCTestParametrizedMacro, Swiftly — Source repository · Topics: Developer Tools · Macros & Metaprogramming · Testing
  **Published:** `2023-11-16T15:47:07.018Z`
  **NeKI brief:** XCTestParametrizedMacro uses a Swift macro to expand a parameterized test into concrete XCTest cases. Use it to reduce duplicated test bodies while preserving separately reported inputs and failures in an XCTest-based suite.
- [Swiftly](https://github.com/swift-server/swiftly) — iOS Dev Tools · 🔨 MotionScape, XCTestParametrizedMacro, Swiftly — Source repository · Topics: Developer Tools · Swift
  **Published:** `2023-11-16T15:47:07.018Z`
  **NeKI brief:** Swiftly installs, selects, and updates Swift toolchains from the command line. Use it when CI or local development must switch compiler releases predictably without manually managing toolchain bundles and PATH configuration.
- [Let's xrOS](https://github.com/XRealityZone/Let-us-xrOS) — Fatbobman’s Swift Weekly · Issue 6 — Source repository · Topics: Developer Tools
  **Published:** `2023-11-13T22:20:44.462Z`
  **NeKI brief:** Let-us-xrOS collects examples and learning material for visionOS development. Use it as a practical discovery route for spatial APIs and project structure, then verify deployment requirements and framework behavior against Apple's documentation.
- [https://github.com/thebrowsercompany/swift-winrt](https://github.com/thebrowsercompany/swift-winrt) — Fatbobman’s Swift Weekly · Issue 5 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2023-11-06T22:30:15.675Z`
  **NeKI brief:** swift-winrt generates Swift projections over Windows Runtime and its COM-based ABI. Use it to study cross-platform bindings, generated interop, and the boundary between Swift ergonomics and platform-specific runtime contracts.
- [example](https://github.com/thebrowsercompany/windows-samples) — Fatbobman’s Swift Weekly · Issue 5 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2023-11-06T22:30:15.675Z`
  **NeKI brief:** Collects Windows sample projects that accompany experiments with Swift and WinRT interoperability. Follow it for concrete API-binding and build examples, while keeping platform-specific assumptions isolated from portable Swift package code.
- [creating a command line tool](https://www.swift.org/getting-started/cli-swiftpm) — iOS Dev Weekly · Issue 634 — Article · Topics: Developer Tools · Personal Essays · Swift
  **Published:** `3rd November 2023`
  **NeKI brief:** Uses SwiftPM’s executable-package workflow to build a command-line tool, providing a concrete starting point for scripts and developer utilities written in Swift.
- [SwiftMessages](https://github.com/SwiftKickMobile/SwiftMessages) — iOS Dev Tools · 🔨 RocketSim, SwiftMessages, Dash — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2023-11-02T14:15:02.032Z`
  **NeKI brief:** SwiftMessages presents configurable in-app banners, cards, and modal messages using UIKit or SwiftUI. Use it when transient feedback needs queuing, layout control, and presentation styles beyond a system alert or toast.
- [SwiftSyntax](https://github.com/apple/swift-syntax) — Fatbobman’s Swift Weekly · Issue 3 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2023-10-23T22:30:20.902Z`
  **NeKI brief:** SwiftSyntax provides the parsing and syntax-tree APIs behind Swift source tooling and macros. Use it as the canonical implementation route when a project must inspect or generate Swift code structurally.
- [ObservationBP](https://github.com/onevcat/ObservationBP) — Fatbobman’s Swift Weekly · Issue 2 — Source repository · Topics: Developer Tools · Performance
  **Published:** `2023-10-16T22:30:04.937Z`
  **NeKI brief:** ObservationBP back-ports Swift's Observation model for projects with an older deployment baseline. Use it to examine compatibility trade-offs and implementation differences before choosing a back-port over native Observation or another state-management approach.
- [Working With XcodeKit <> SwiftLeeds](https://digitalbunker.dev/swift-leeds-working-with-xcodekit) — Fatbobman’s Swift Weekly · Issue 2 — Article · Topics: Spatial Computing · Swift · Xcode
  **Published:** `2023-10-16T22:30:04.937Z`
  **NeKI brief:** Shows integrating XcodeKit source-editor extensions through `XCSourceEditorCommand`. Follow it when automating source transformations inside Xcode and deciding which editor context, selection, and completion behavior the extension must handle.
- [Configuring VSCode](https://www.bryanbraun.com/2023/08/10/things-i-wish-someone-would-have-told-me-about-configuring-vscode) — iOS Dev Weekly · Issue 631 — Article · Topics: Cross-Platform & Web · Developer Tools · Xcode
  **Published:** `13th October 2023`
  **NeKI brief:** Presents configuring vscode for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [or Swift](https://marketplace.visualstudio.com/items?itemName=sswg.swift-lang) — iOS Dev Weekly · Issue 631 — Article · Topics: Cross-Platform & Web · Swift · Xcode
  **Published:** `13th October 2023`
  **NeKI brief:** Provides the Swift language extension for Visual Studio Code. Follow it when setting up language-server completion, diagnostics, and package workflows outside Xcode, while validating debugger and SDK limitations separately.
- [FileKit](https://github.com/nvzqz/FileKit) — iOS Dev Tools · 🔨 Introducing Trace, Boop, FileKit — Source repository · Topics: Developer Career & Practice · Developer Tools · Swift
  **Published:** `2023-10-12T15:37:25.698Z`
  **NeKI brief:** FileKit wraps Foundation file-system operations in expressive Swift types for paths, directories, and files. Use it for concise tooling or macOS utility code, while checking its maintenance and platform assumptions before making it a core dependency.
- [摸鱼周报](https://github.com/zhangferry/iOSWeeklyLearning) — Fatbobman’s Swift Weekly · Issue 1 — Source repository · Topics: Developer Tools
  **Published:** `2023-10-09T14:00:25.178Z`
  **NeKI brief:** iOSWeeklyLearning organizes Chinese iOS learning notes and project links in a repository. Follow it as a community discovery index, then verify each linked technical source and its currency before applying an implementation pattern.
- [SwiftDataKit](https://github.com/fatbobman/SwiftDataKit) — Fatbobman’s Swift Weekly · Issue 1 — Source repository · Topics: Core Data · Swift · SwiftData
  **Published:** `2023-10-09T14:00:25.178Z`
  **NeKI brief:** SwiftDataKit exposes lower-level Core Data access for SwiftData-backed models. Use it when a migration needs framework escape hatches, persistent-history operations, or APIs not surfaced by SwiftData alone.
- [OpenSwiftUI](https://github.com/Kyle-Ye/OpenSwiftUI) — Fatbobman’s Swift Weekly · Issue 1 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2023-10-09T14:00:25.178Z`
  **NeKI brief:** Kyle Ye's OpenSwiftUI work offers a research implementation for studying SwiftUI and AttributeGraph-like behavior. Follow it for comparative experiments and internals-oriented learning, not as a compatibility promise for production Apple-platform code.
- [Building Reusable SwiftUI Components](https://peterfriese.github.io/Building-SwiftUI-Components-Tutorial/tutorials/tutorial-table-of-contents) — iOS Dev Weekly · Issue 630 — Tutorial · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `6th October 2023`
  **NeKI brief:** Presents building reusable swiftui components for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [project](https://github.com/toph42/ExampleKit) — iOS Dev Weekly · Issue 627 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `15th September 2023`
  **NeKI brief:** Provides the ExampleKit source for embedding Swift libraries in iPad Swift Playgrounds; inspect its package layout when sharing reusable code with playground-based clients.
- [Improve the build times of your SPM Packages and apps](https://mdb1.github.io/2023-08-18-improve-build-times-in-spm-packages-and-in-your-apps) — iOS Dev Weekly · Issue 624 — Article · Topics: Developer Tools · Swift · Xcode
  **Published:** `25th August 2023`
  **NeKI brief:** Explores Improve the build times of your SPM Packages and apps, focusing on this article from manu herrera has some great tips for. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [chat app](https://github.com/huggingface/swift-chat) — iOS Dev Weekly · Issue 622 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `11th August 2023`
  **NeKI brief:** Provides a macOS demonstration app for swift-transformers, showing how the project can host local language-model interactions. It is a concrete repository to inspect when evaluating a Swift-native prototype for on-device or desktop model experimentation.
- [SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON) — iOS Dev Tools · 🔨 Introducing SnapKit, SwiftyJSON, RxSwift — Source repository · Topics: Developer Tools · Swift
  **Published:** `2023-08-10T11:11:05.792Z`
  **NeKI brief:** Presents a concrete implementation of SwiftyJSON. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.
- [Link to GitHub.](https://github.com/mapbox/mapbox-maps-ios) — iOS Dev Tools · 🔨 Introducing Mapbox, Alamofire, RNCrypto — Source repository · Topics: Developer Tools · Maps & Location
  **Published:** `2023-08-03T12:40:06.374Z`
  **NeKI brief:** Mapbox Maps SDK for iOS provides vector maps, annotations, styling, navigation-oriented capabilities, and offline regions. Use it when Apple MapKit’s data or customization is insufficient, accounting for tokens, licensing, and offline package management.
- [RNCrypto](https://github.com/RNCryptor/RNCryptor) — iOS Dev Tools · 🔨 Introducing Mapbox, Alamofire, RNCrypto — Source repository · Topics: Developer Tools · Security & Privacy
  **Published:** `2023-08-03T12:40:06.374Z`
  **NeKI brief:** RNCryptor defines a cross-language encrypted-data format using AES-256-CBC, PBKDF2-derived keys, random salt and IV, plus HMAC. Use it when interoperable encrypted payloads are required, while handling keys separately from ciphertext storage.
- [Nuke - Efficient Image Handling for Swift](https://github.com/tuist/tuist) — iOS Dev Tools · 🔨 It's Clipboard Magic (and Other Stuff) — Source repository · Topics: Developer Tools · Swift · Testing
  **Published:** `2023-06-29T13:51:11.661Z`
  **NeKI brief:** Tuist declares Xcode projects, targets, dependencies, and automation in Swift manifests, then generates workspace artifacts. Use it to centralize large-project configuration and speed team onboarding, with generated files treated as derived output.
- [GitHub Dependency Graph, Dependabot Alerts, and Advisory Database now support Swift advisories](https://github.blog/changelog/2023-06-19-dependency-graph-dependabot-alerts-and-advisory-database-now-support-swift-advisories) — iOS Dev Weekly · Issue 615 — Article · Topics: Developer Tools · Persistence & Synchronisation · Swift
  **Published:** `23rd June 2023`
  **NeKI brief:** Explores GitHub Dependency Graph, Dependabot Alerts, and Advisory Database now support Swift advisories, focusing on if you have worked with other languages, you’ve likely come. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Swift-Macros: A curated list of awesome Swift Macros](https://github.com/krzysztofzablocki/Swift-Macros) — iOS Dev Weekly · Issue 614 — Source repository · Topics: Developer Tools · Macros & Metaprogramming · Swift
  **Published:** `16th June 2023`
  **NeKI brief:** Explores Swift-Macros: A curated list of awesome Swift Macros, focusing on the article discusses want to write something more detailed about. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [sample code](https://github.com/apple/sample-backyard-birds) — iOS Dev Weekly · Issue 613 — Source repository · Topics: Developer Community & Business · Developer Tools
  **Published:** `9th June 2023`
  **NeKI brief:** Explores sample code, focusing on the article discusses love this page from apple highlighting all the essential bits of documentation, articles, update summaries, key reference documentation, and. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Get Started](https://github.com/SwiftedMind/Queryable) — iOS Dev Weekly · Issue 607 — Source repository · Topics: Developer Career & Practice · Developer Tools · Observation & State Management
  **Published:** `28th April 2023`
  **NeKI brief:** Explores Get Started, focusing on the article discusses like the idea behind this new package from dennis müller. it tidies up the state management around presenting alerts,. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [SwiftUI Multiplatform Navigation Example](https://github.com/tunds/SwiftUI-Navigation-Multiplatform-Example) — SwiftUI Weekly · SwiftUI Weekly - Issue #140 — Source repository · Topics: Developer Community & Business · Swift · SwiftUI
  **Published:** `2023-04-25T07:37:25.660Z`
  **NeKI brief:** Provides a working SwiftUI navigation project across Apple platforms, showing route composition and platform adaptations. Useful as a concrete reference when designing a shared navigation model that still respects platform-specific presentation behavior.
- [macro support in Swift](https://github.com/apple/swift-evolution/blob/main/proposals/0382-expression-macros.md) — iOS Dev Weekly · Issue 604 — Source repository · Topics: Developer Tools · Macros & Metaprogramming · Swift
  **Published:** `7th April 2023`
  **NeKI brief:** Explores macro support in Swift, focusing on the article discusses love the idea behind this new library. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Wonderous: Build Wonders with Flutter](https://flutter.gskinner.com/wonderous) — iOS Dev Weekly · Issue 598 — Article · Topics: Accessibility · App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `24th February 2023`
  **NeKI brief:** Explores Wonderous: Build Wonders with Flutter, focusing on wonderous is an open-source ios app built with flutter. it. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Flutter](https://flutter.dev/multi-platform/mobile) — iOS Dev Weekly · Issue 598 — Article · Topics: Accessibility · App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `24th February 2023`
  **NeKI brief:** Explores Flutter, focusing on wonderous is an open-source ios app built with flutter. it features award-winning ux design and best practices for performance and accessibility. see. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Reliable mobile tests and actionable results in a fraction of the time](https://app.waldo.com/signup) — iOS Dev Weekly · Issue 597 — Article · Topics: Developer Tools · Testing
  **Published:** `17th February 2023`
  **NeKI brief:** Explores Reliable mobile tests and actionable results in a fraction of the time, focusing on developers deserve to ship releases with confidence. waldo helps teams. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [KeepSafe has saved +1000 hours](https://www.waldo.com/customer-stories/keepsafe) — iOS Dev Weekly · Issue 597 — Article · Topics: Developer Tools · Testing
  **Published:** `17th February 2023`
  **NeKI brief:** Explores KeepSafe has saved +1000 hours, focusing on stop spending time reproducing issues discovered during testing, and start. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Introducing EditKit Pro](https://digitalbunker.dev/editkit-pro) — iOS Dev Weekly · Issue 597 — Article · Topics: Developer Tools · Xcode
  **Published:** `17th February 2023`
  **NeKI brief:** Explores Introducing EditKit Pro, focusing on it’s been a while since i saw a new xcode. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [what](https://github.com/uliwitness/AppKitForClassic) — iOS Dev Weekly · Issue 590 — Source repository · Topics: Developer Tools · Xcode
  **Published:** `30th December 2022`
  **NeKI brief:** Explores what, focusing on are you looking for work? there are many exciting opportunities to work with all kinds of companies over on ios dev jobs.. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [make music](https://github.com/atrinh0/chart-de-lune) — iOS Dev Weekly · Issue 590 — Source repository · Topics: Developer Tools · Swift
  **Published:** `30th December 2022`
  **NeKI brief:** Explores make music, focusing on if using swift charts to visualise sort algorithms wasn’t enough, how about using them to make music? 🎶. Follow it to assess the approach, its trade-offs, and where it fits in a current Swift or Apple-platform project.
- [launch blog post](https://trycombine.com/posts/datatile-for-simulator-public-beta-on-testflight-now) — iOS Dev Weekly · Issue 587 — Article · Topics: App Distribution & Store Operations · Combine & Reactive Programming · Developer Tools
  **Published:** `2nd December 2022`
  **NeKI brief:** Explores launch blog post, focusing on the article discusses don’t know about you, but i still. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [implemented in Swift 5.7](https://github.com/apple/swift-evolution/blob/main/proposals/0292-package-registry-service.md) — iOS Dev Weekly · Issue 586 — Source repository · Topics: Developer Tools · Swift
  **Published:** `25th November 2022`
  **NeKI brief:** Explores implemented in Swift 5.7, focusing on package registries solve that by providing a mechanism to deliver. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [integration with DocC](https://github.com/apple/swift-evolution/blob/main/proposals/0356-swift-snippets.md) — iOS Dev Weekly · Issue 585 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `18th November 2022`
  **NeKI brief:** Explores integration with DocC, focusing on the article discusses don’t link to swift evolution proposals often,. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [R&D OSS Engineer @ DockYard](https://dockyard.breezy.hr/p/c463e5b6f7a0-ios-engineer-swiftui) — iOS Dev Weekly · Issue 585 — Article · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `18th November 2022`
  **NeKI brief:** Explores R&D OSS Engineer @ DockYard, focusing on r&d oss engineer @ dockyard – dockyard is a digital. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [implemented this change](https://github.com/apple/swift-org-website/pull/161) — iOS Dev Weekly · Issue 584 — Source repository · Topics: Developer Tools · Swift
  **Published:** `11th November 2022`
  **NeKI brief:** Explores implemented this change, focusing on for disclosure, i’m a member of the swift website workgroup. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Senior SwiftUI Developer @ Confidential Client](https://gist.github.com/looking4talent/60a1e5bbcbc7e0783e31111a29dadbe4) — iOS Dev Weekly · Issue 577 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `23rd September 2022`
  **NeKI brief:** Explores Senior SwiftUI Developer @ Confidential Client, focusing on senior swiftui developer @ confidential client – help us migrate. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [The Lighter Swift Codegen for SQLite3](https://www.alwaysrightinstitute.com//lighter) — iOS Dev Weekly · Issue 572 — Article · Topics: Developer Tools · Persistence & Synchronisation · Swift
  **Published:** `19th August 2022`
  **NeKI brief:** Explores The Lighter Swift Codegen for SQLite3, focusing on there’s a lot going on in this post from helge. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Grid Trainer app](https://gist.github.com/swiftui-lab/723eb1277d59d9ae092455ac8196b8ba) — iOS Dev Weekly · Issue 569 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `29th July 2022`
  **NeKI brief:** Provides a small interactive Grid trainer for experimenting with SwiftUI grid alignment. It is useful as executable reference material when a grid’s row, column, alignment, or span behaviour is easier to learn by changing code than by reading API documentation.
- [Stream](https://getstream.io/chat/sdk/swiftui) — iOS Dev Weekly · Issue 566 — Article · Topics: Developer Community & Business · Developer Tools · Swift
  **Published:** `8th July 2022`
  **NeKI brief:** Presents stream for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [X-SwiftFormat](https://github.com/ruiaureliano/X-SwiftFormat) — iOS Dev Weekly · Issue 565 — Source repository · Topics: Developer Tools · Swift · Xcode
  **Published:** `1st July 2022`
  **NeKI brief:** Examines X-SwiftFormat, focusing on will xcode ever support native integration with swift-format? if i had to guess, i’d say it will but that it’s unlikely…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [SwiftUI Digital Lounge archive](https://midnight-beanie-ccb.notion.site/swiftui-lounge-wwdc22-e20094b91f074398ba395c3fa245e63d) — iOS Dev Weekly · Issue 563 — Article · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `17th June 2022`
  **NeKI brief:** Explores SwiftUI Digital Lounge archive, focusing on the digital lounges were great again this year, but they. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [vscode-swift](https://github.com/swift-server/vscode-swift) — iOS Dev Weekly · Issue 559 — Source repository · Topics: Developer Tools · Swift
  **Published:** `20th May 2022`
  **NeKI brief:** Explores vscode-swift, focusing on if you had told me five years ago that in 2022, writing swift in a javascript-based text editor from microsoft called visual. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Debug logging forever!](https://www.sicpers.info/2022/05/you-say-cave-dweller-debugging-i-say-debug-logging) — iOS Dev Weekly · Issue 557 — Article · Topics: Developer Tools
  **Published:** `6th May 2022`
  **NeKI brief:** Explores Debug logging forever!, focusing on a love letter to print debugging by graham lee. maybe. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Xcodes.app](https://github.com/RobotsAndPencils/XcodesApp) — iOS Dev Weekly · Issue 552 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Xcode
  **Published:** `1st April 2022`
  **NeKI brief:** Explores Xcodes.app, focusing on the last time i mentioned xcodes, i was still using xcinfo. that changed recently with some fantastic improvements to xcodes.app. especially in. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [latest release](https://github.com/RobotsAndPencils/XcodesApp/releases/tag/v1.3.1b11) — iOS Dev Weekly · Issue 552 — Source repository · Topics: Developer Tools · Testing · Xcode
  **Published:** `1st April 2022`
  **NeKI brief:** Explores latest release, focusing on the last time i mentioned xcodes, i was still using xcinfo. that changed recently with some fantastic improvements to xcodes.app. especially in. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [tirelessly maintained since 2015](https://github.com/realm/SwiftLint/graphs/contributors) — iOS Dev Weekly · Issue 551 — Source repository · Topics: Developer Tools · Swift · Testing
  **Published:** `25th March 2022`
  **NeKI brief:** Explores tirelessly maintained since 2015, focusing on the article discusses don’t link to swiftlint enough in this. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [SE-0335](https://github.com/apple/swift-evolution/blob/main/proposals/0335-existential-any.md) — iOS Dev Weekly · Issue 550 — Source repository · Topics: Developer Tools · Swift · Xcode
  **Published:** `18th March 2022`
  **NeKI brief:** Contains SE-0335, the proposal that makes existential type usage explicit with any. Consult it when modernizing protocol-typed APIs or interpreting Swift diagnostics, because it explains the language rationale, migration source changes, and intended semantic clarity.
- [SPI benchmark tool](https://github.com/SwiftPackageIndex/spi-benchmark) — iOS Dev Weekly · Issue 549 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `11th March 2022`
  **NeKI brief:** Explores SPI benchmark tool, focusing on what began as an experiment to test how fast our. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Hosting your Swift Library Docs on Github Pages](https://rhonabwy.com/2022/01/28/hosting-your-swift-library-docs-on-github-pages) — iOS Dev Weekly · Issue 544 — Article · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `4th February 2022`
  **NeKI brief:** Explores Hosting your Swift Library Docs on Github Pages, focusing on there’s so much good stuff in this post from joseph. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [swift-docc-plugin](https://github.com/apple/swift-docc-plugin) — iOS Dev Weekly · Issue 544 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `4th February 2022`
  **NeKI brief:** Explores swift-docc-plugin, focusing on there’s so much good stuff in this post from joseph heck. he begins by talking about the upcoming plugin changes to the. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [external build tools](https://github.com/apple/swift-evolution/blob/main/proposals/0303-swiftpm-extensible-build-tools.md) — iOS Dev Weekly · Issue 543 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `28th January 2022`
  **NeKI brief:** Examines SE-0303 – Package Manager Extensible Build Tools, focusing on so, i was delighted to come across se-0303 – package manager extensible build tools, currently in review. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [SimulatorStatusMagic](https://github.com/shinydevelopment/SimulatorStatusMagic) — iOS Dev Weekly · Issue 533 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `12th November 2021`
  **NeKI brief:** Provides the Simulator Status Magic source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [new README](https://github.com/SwiftPackageIndex/SwiftPackageIndex-Server/blob/main/README.md) — iOS Dev Weekly · Issue 533 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `12th November 2021`
  **NeKI brief:** The project README gives the high-level orientation for the Swift Package Index server codebase and its contribution surface. Use it before inspecting implementation details to understand the repository’s purpose, major components, and expected local development entry points.
- [guide to setting up for local development](https://github.com/SwiftPackageIndex/SwiftPackageIndex-Server/blob/main/LOCAL_DEVELOPMENT_SETUP.md) — iOS Dev Weekly · Issue 533 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `12th November 2021`
  **NeKI brief:** Documents the local-development setup for the Swift Package Index server, making its environment and workflow inspectable without inference. Useful as a concrete example of onboarding documentation for a nontrivial Swift service with repository-specific tooling and dependencies.
- [How to use GitHub Copilot with Swift](https://antran.app/2021/github_copilot_swift) — iOS Dev Weekly · Issue 532 — Article · Topics: AI Development · Developer Tools · Swift
  **Published:** `5th November 2021`
  **NeKI brief:** Explores How to use GitHub Copilot with Swift, focusing on i’ve not thought much about github copilot since i wrote. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Debugging on iOS 15 with Xcode 12](https://hybridcattt.com/blog/debugging-on-latest-ios-with-older-xcode) — iOS Dev Weekly · Issue 530 — Article · Topics: Developer Tools · Testing · Xcode
  **Published:** `22nd October 2021`
  **NeKI brief:** Explores Debugging on iOS 15 with Xcode 12, focusing on this time of year is always awkward with versions of. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [AFNetworking](https://github.com/AFNetworking/AFNetworking) — iOS Dev Weekly · Issue 528 — Source repository · Topics: Developer Tools · Networking
  **Published:** `8th October 2021`
  **NeKI brief:** Provides the AFNetworking 2.0 source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [associated blog post](https://fabernovel.github.io/2021-07-22/enhance-xcode-snippets-using-git) — iOS Dev Weekly · Issue 517 — Article · Topics: Developer Tools · Xcode
  **Published:** `23rd July 2021`
  **NeKI brief:** Explores associated blog post, focusing on if you’re anything like me, you know how to add. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [source code control tool of choice](https://www.git-tower.com/mac) — iOS Dev Weekly · Issue 512 — Article · Topics: Developer Tools · Xcode
  **Published:** `18th June 2021`
  **NeKI brief:** Explores source code control tool of choice, focusing on if apple had made this a standalone tool that worked. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [his gist](https://gist.github.com/vibrazy/16e0408b5be7be4df508e92e0cf9448b) — iOS Dev Weekly · Issue 508 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `21st May 2021`
  **NeKI brief:** Provides a small SwiftUI helper for avoiding repetitive hard-coded view-modifier values under conditional configuration. It is useful as a compact code sketch when state-dependent styling is becoming noisy and a local abstraction may improve readability.
- [language support for Actors](https://github.com/apple/swift-evolution/blob/main/proposals/0306-actors.md) — iOS Dev Weekly · Issue 507 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `14th May 2021`
  **NeKI brief:** Explores language support for Actors, focusing on one of the new features coming in swift 5.5 is. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [working on it](https://github.com/SwiftPackageIndex/SwiftPackageIndex-Server/issues/1038) — iOS Dev Weekly · Issue 504 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `23rd April 2021`
  **NeKI brief:** Explores working on it, focusing on note: you’ll notice a full complement of failing builds on. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Inspecting SwiftUI views](https://fivestars.blog/swiftui/inspecting-views.html) — iOS Dev Weekly · Issue 500 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `26th March 2021`
  **NeKI brief:** Examines Inspecting SwiftUI views, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [sample code](https://github.com/nemecek-filip/CompositionalDiffablePlayground.ios) — iOS Dev Weekly · Issue 496 — Source repository · Topics: Developer Tools
  **Published:** `26th February 2021`
  **NeKI brief:** Examines Compositional Diffable Collection View Playground, focusing on i’ve enjoyed filip němeček’s posts on collection views recently, but there have been so many that it’s been hard to know…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against.
- [Injection4Xcode](https://github.com/johnno1962/InjectionIII) — iOS Dev Weekly · Issue 494 — Source repository · Topics: Developer Tools · Xcode
  **Published:** `12th February 2021`
  **NeKI brief:** Examines Injection4Xcode, focusing on sometimes you read a technical book to learn a practical skill that you’ll directly use in the apps you work on, and…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [and playground](https://github.com/twostraws/whats-new-in-swift-5-4) — iOS Dev Weekly · Issue 493 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `5th February 2021`
  **NeKI brief:** Examines and playground, focusing on the xcode 12.5 beta comes along with a beta of swift 5.4 too! it’s not quite async/await time yet, but that doesn’t mean…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current.
- [Who said we can’t unit test SwiftUI views?](https://nalexn.github.io/swiftui-unit-testing) — iOS Dev Weekly · Issue 492 — Article · Topics: Swift · SwiftUI · Testing
  **Published:** `29th January 2021`
  **NeKI brief:** Examines Who said we can't unit test SwiftUI views?, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [well documented](https://github.com/nalexn/ViewInspector/blob/master/guide.md) — iOS Dev Weekly · Issue 492 — Source repository · Topics: Swift · SwiftUI · Testing
  **Published:** `29th January 2021`
  **NeKI brief:** Examines well documented, focusing on when i first saw that all swiftui view hierarchy was a function of state stored in structs, i figured it would be ideal…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current.
- [Profiling SwiftUI app using Instruments](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3N3aWZ0d2l0aG1hamlkLmNvbS8yMDIxLzAxLzIwL3Byb2ZpbGluZy1zd2lmdHVpLWFwcC11c2luZy1pbnN0cnVtZW50cy8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiJmNDMyNzc3Ny02M2Q2LTQ1MDQtOWVkMC1lYTgwYzM4ZmVlZDUiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiMjVjODkyZTUtYTM5OC00YWVmLWFkMWEtMzYzZTkzNWE1OGJhIiwiaWF0IjoxNjc0MDYyNjc5LjQ1OSwiaXNzIjoib3JjaGlkIn0.yFE0lXxlheNBniRXd2cVmx609ueoWFP89URqNlmr9lo) — SwiftUI Weekly · SwiftUI Weekly - Issue #43 — Article · Topics: Performance · Swift · SwiftUI
  **Published:** `2021-01-26T13:13:48.000Z`
  **NeKI brief:** Uses Instruments to profile SwiftUI performance. Use it when a view-update or rendering problem needs measured call stacks and allocation evidence instead of intuition about declarative UI cost.
- [AutomaticSettings](https://github.com/krzysztofzablocki/AutomaticSettings) — iOS Dev Weekly · Issue 489 — Source repository · Topics: Developer Tools · Foundation & Data Formats · Graphics, Media & Games
  **Published:** `8th January 2021`
  **NeKI brief:** Examines AutomaticSettings, focusing on this new library from krzysztof zabłocki is interesting. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [which scissor emojis could actually cut paper](https://wh0.github.io/2020/01/02/scissors.html) — iOS Dev Weekly · Issue 488 — Article · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `1st January 2021`
  **NeKI brief:** Covers which scissor emojis could actually cut paper, focusing on Swift and Apple-platform engineering practice. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [Yes, it’s the full thing. I’m sorry](https://github.com/felixrieseberg/macintosh.js) — iOS Dev Weekly · Issue 488 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `1st January 2021`
  **NeKI brief:** Examines Yes, it’s the full thing. I’m sorry, focusing on how do you record videos of your apple watch apps? you have the watch on your wrist, tap the screen with your other hand,…. Use it as a focused research reference for related Apple-platform work.
- [Motion](https://github.com/b3ll/Motion) — iOS Dev Weekly · Issue 487 — Source repository · Topics: Developer Tools · Performance
  **Published:** `18th December 2020`
  **NeKI brief:** Examines Motion, focusing on performance-focused animation library from adam bell? that has to be worth checking out. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Decomposed](https://github.com/b3ll/Decomposed) — iOS Dev Weekly · Issue 487 — Source repository · Topics: Developer Tools · Performance
  **Published:** `18th December 2020`
  **NeKI brief:** Examines Decomposed, focusing on performance-focused animation library from adam bell? that has to be worth checking out. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [How to configure Xcode projects for different environments?](https://kocyigityunus.medium.com/how-to-configure-xcode-projects-for-different-environments-30b23ed44ee6) — iOS Dev Weekly · Issue 486 — Article · Topics: Developer Tools · Xcode
  **Published:** `11th December 2020`
  **NeKI brief:** Covers How to configure Xcode projects for different environments?, focusing on Swift tooling and build integration. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [James Dempsey’s Build Settings Extractor](https://github.com/dempseyatgithub/BuildSettingExtractor) — iOS Dev Weekly · Issue 483 — Source repository · Topics: Concurrency · Developer Tools
  **Published:** `20th November 2020`
  **NeKI brief:** Examines James Dempsey’s Build Settings Extractor, focusing on i’ll push people to learn about xcconfig files at every opportunity, so i’m grateful for junda ong provided me with a…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against.
- [AccessibilitySnapshot](https://github.com/cashapp/AccessibilitySnapshot) — iOS Dev Weekly · Issue 483 — Source repository · Topics: Accessibility · Developer Tools · Testing
  **Published:** `20th November 2020`
  **NeKI brief:** Examines AccessibilitySnapshot, focusing on this project from nick entin isn’t new, but i came across it recently via ryo aoyama’s extension to playbook, and it’s great. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Ryo Aoyama’s extension to Playbook](https://github.com/playbook-ui/accessibility-snapshot-ios) — iOS Dev Weekly · Issue 483 — Source repository · Topics: Accessibility · Developer Tools · Testing
  **Published:** `20th November 2020`
  **NeKI brief:** Examines Ryo Aoyama’s extension to Playbook, focusing on this project from nick entin isn’t new, but i came across it recently via ryo aoyama’s extension to playbook, and it’s great. Use it as a focused research reference for related Apple-platform work, and verify version-specific details.
- [about Combine](https://heckj.github.io/swiftui-notes) — iOS Dev Weekly · Issue 482 — Article · Topics: Combine & Reactive Programming · Concurrency · Swift
  **Published:** `13th November 2020`
  **NeKI brief:** Examines about Combine, offering practical guidance on networking and asynchronous reliability. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [manifesto](https://gist.github.com/lattner/31ed37682ef1576b16bca1432ea9f782) — iOS Dev Weekly · Issue 481 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `6th November 2020`
  **NeKI brief:** Examines Chris proposed, focusing on like bill atkins, i too am keen to see swift get support for async/await style concurrency. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [GoSwifty](https://github.com/rsrbk/GoSwifty) — iOS Dev Weekly · Issue 479 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `23rd October 2020`
  **NeKI brief:** Examines GoSwifty, focusing on are you working on an app that’s transitioning from objective-c to swift? do you know what percentage of your code is in…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Swift Service Discovery](https://github.com/apple/swift-service-discovery) — iOS Dev Weekly · Issue 479 — Source repository · Topics: Developer Tools · Swift
  **Published:** `23rd October 2020`
  **NeKI brief:** Examines Swift Service Discovery, focusing on have you noticed that apple releasing a new swift open-source library is an almost weekly occurrence these days? 🎉 this…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [new library](https://github.com/apple/swift-atomics) — iOS Dev Weekly · Issue 476 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2nd October 2020`
  **NeKI brief:** Examines new library, focusing on as karoy lorentey explains, this new library won’t solve all of your problems when writing asynchronous code. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [implementation of it](https://github.com/crafterm/swiftui-app-switcher) — iOS Dev Weekly · Issue 474 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `18th September 2020`
  **NeKI brief:** Examines implementation of it, focusing on the ios app switcher is a complex ui control but is all driven from a single drag gesture. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Parma](https://github.com/dasautoooo/Parma) — iOS Dev Weekly · Issue 470 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `21st August 2020`
  **NeKI brief:** Examines Parma, focusing on markdown rendering engine, using swiftui views? that sounds interesting! that’s what leonard chan has created here. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [XCSSET Malware Infects Xcode Projects](https://blog.trendmicro.com/trendlabs-security-intelligence/xcsset-mac-malware-infects-xcode-projects-performs-uxss-attack-on-safari-other-browsers-leverages-zero-day-exploits) — iOS Dev Weekly · Issue 469 — Article · Topics: Cross-Platform & Web · Developer Tools · Xcode
  **Published:** `14th August 2020`
  **NeKI brief:** Examines XCSSET Malware Infects Xcode Projects, offering practical guidance on Xcode tooling and development workflow. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [full report](https://documents.trendmicro.com/assets/pdf/XCSSET_Technical_Brief.pdf) — iOS Dev Weekly · Issue 469 — Article · Topics: Cross-Platform & Web · Developer Tools · Xcode
  **Published:** `14th August 2020`
  **NeKI brief:** Details Trend Micro's XCSSET technical findings, including malicious Xcode-project behavior and attack vectors. Use the report to review supply-chain defenses and CI isolation, while checking its historical threat context before acting.
- [Learning by experimenting with Playgrounds](https://gist.github.com/jordansinger) — iOS Dev Weekly · Issue 466 — Source repository · Topics: Developer Tools · Performance · Swift
  **Published:** `24th July 2020`
  **NeKI brief:** Examines Learning by experimenting with Playgrounds, focusing on i’ve been thoroughly enjoying jordan singer’s tweets recently, especially his experimentations with swiftui which he has…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [macOS.swift](https://gist.github.com/jordansinger/72a05653dde9d182b4a5e24f9d19a106) — iOS Dev Weekly · Issue 466 — Source repository · Topics: Developer Tools · Performance · Swift
  **Published:** `24th July 2020`
  **NeKI brief:** Examines macOS.swift, focusing on i’ve been thoroughly enjoying jordan singer’s tweets recently, especially his experimentations with swiftui which he has…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [sample project](https://github.com/swiftui-lab/swiftui-hero-animations) — iOS Dev Weekly · Issue 465 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `17th July 2020`
  **NeKI brief:** Examines sample project, focusing on magic move in keynote is a fantastic feature, and with this year’s releases you now get magic move in your swiftui apps!…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [StoreKit Testing in Xcode](https://www.revenuecat.com/blog/storekit-testing-in-xcode) — iOS Dev Weekly · Issue 463 — Article · Topics: App Distribution & Store Operations · Testing · Xcode
  **Published:** `3rd July 2020`
  **NeKI brief:** Examines StoreKit Testing in Xcode, focusing on the building, debugging, and testing of storekit code is always stressful. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [HorizonCalendar](https://github.com/airbnb/HorizonCalendar) — iOS Dev Weekly · Issue 461 — Source repository · Topics: Developer Tools
  **Published:** `19th June 2020`
  **NeKI brief:** Examines HorizonCalendar, focusing on the author’s discussion of don’t link to a lot of ui libraries here as it so often ends up being easier to write your own ui code. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current.
- [What Adding Dependencies Will Do To Your App in 2020](https://xavierlowmiller.github.io/blog/2020/06/04/Swift-Dependencies) — iOS Dev Weekly · Issue 460 — Article · Topics: Dependency Injection · Developer Tools · Swift
  **Published:** `12th June 2020`
  **NeKI brief:** Examines What Adding Dependencies Will Do To Your App in 2020, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Building a view debugger using SceneKit](https://www.youtube.com/watch?v=S6YN2Bsde_Q) — iOS Dev Weekly · Issue 459 — Video · Topics: Developer Tools · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `5th June 2020`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Nuke 9](https://kean.github.io/post/nuke-9) — iOS Dev Weekly · Issue 457 — Article · Topics: Combine & Reactive Programming · Developer Tools · Swift
  **Published:** `22nd May 2020`
  **NeKI brief:** Covers Nuke 9, focusing on Swift and Apple-platform engineering practice. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [Nuke](https://github.com/kean/Nuke/releases/tag/9.0.0) — iOS Dev Weekly · Issue 457 — Source repository · Topics: Combine & Reactive Programming · Developer Tools · Swift
  **Published:** `22nd May 2020`
  **NeKI brief:** Examines Nuke, focusing on it’s always nice to see a mature, stable, well-loved open-source project get an update, and that’s what nuke from…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Making iOS Accessibility Testing Easy](https://cashapp.github.io/2020-05-20/making-ios-accessibility-testing-easy) — iOS Dev Weekly · Issue 457 — Article · Topics: Accessibility · Developer Tools · Testing
  **Published:** `22nd May 2020`
  **NeKI brief:** Covers Making iOS Accessibility Testing Easy, focusing on testing, diagnostics, and feedback quality. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [example apps](https://github.com/pointfreeco/swift-composable-architecture/tree/master/Examples) — iOS Dev Weekly · Issue 455 — Source repository · Topics: Architecture · Objective-C & Cocoa · Testing
  **Published:** `8th May 2020`
  **NeKI brief:** Examines example apps, focusing on from a first look at this new architecture framework from brandon williams and stephen celis, i like it. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [DocTest](https://github.com/SwiftDocOrg/DocTest) — iOS Dev Weekly · Issue 454 — Source repository · Topics: Developer Tools · Swift · Testing
  **Published:** `1st May 2020`
  **NeKI brief:** Examines DocTest, focusing on adding code samples into your documentation comments is a great way to show other developers how to use your api, but…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [swift-format](https://github.com/apple/swift-format) — iOS Dev Weekly · Issue 450 — Source repository · Topics: Developer Tools · Swift · Xcode
  **Published:** `3rd April 2020`
  **NeKI brief:** Examines swift-format, focusing on will xcode ever support native integration with swift-format? if i had to guess, i’d say it will but that it’s unlikely…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Playbook](https://github.com/playbook-ui/playbook-ios) — iOS Dev Weekly · Issue 450 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `3rd April 2020`
  **NeKI brief:** Examines Playbook, focusing on inspired by storybook, this swiftui library from ryo aoyama lets you develop, and test ui components in isolation from…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [swift-outdated](https://github.com/kiliankoe/swift-outdated) — iOS Dev Weekly · Issue 449 — Source repository · Topics: Dependency Injection · Swift · Swift Package Manager
  **Published:** `27th March 2020`
  **NeKI brief:** Examines swift-outdated, focusing on if you’re using the swift package manager, then kilian koe has a helpful little tool to quickly let you know if you’ve…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [UIAlertController with Function Builders](https://felginep.github.io/2020-03-10/uialertcontroller-function-builders) — iOS Dev Weekly · Issue 447 — Article · Topics: Developer Tools · Swift
  **Published:** `13th March 2020`
  **NeKI brief:** Examines UIAlertController with Function Builders, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [ErrorAssertions](https://github.com/SlaunchaMan/ErrorAssertions) — iOS Dev Weekly · Issue 447 — Source repository · Topics: Developer Tools · Testing
  **Published:** `13th March 2020`
  **NeKI brief:** Examines ErrorAssertions, focusing on ever wish you could pass an error to assert, precondition, or fatalerror? what about writing tests that expect one of…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Swift Package Continuous Integration Guide](https://learningswift.brightdigit.com/swift-package-continuous-integration-guide) — iOS Dev Weekly · Issue 446 — Article · Topics: CI/CD & Automation · Swift · Swift Package Manager
  **Published:** `6th March 2020`
  **NeKI brief:** Examines Swift Package Continuous Integration Guide, offering practical guidance on Swift Package Manager integration. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Federico Zanetello’s ultimate guide to Swift executables](https://www.fivestars.blog//code/ultimate-guide-swift-executables.html) — iOS Dev Weekly · Issue 446 — Article · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `6th March 2020`
  **NeKI brief:** Examines the ultimate guide to Swift executables, offering practical guidance on Swift Package Manager integration. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Poes](https://github.com/AvdLee/Poes) — iOS Dev Weekly · Issue 444 — Source repository · Topics: App Services & Extensions · Developer Tools · Testing
  **Published:** `21st February 2020`
  **NeKI brief:** Examines Poes, focusing on one of the best new features of xcode 11.4 is that the new simulator can easily test remote push notifications. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [DefaultCodable](https://github.com/gonzalezreal/DefaultCodable) — iOS Dev Weekly · Issue 443 — Source repository · Topics: Developer Tools · Foundation & Data Formats
  **Published:** `14th February 2020`
  **NeKI brief:** Examines DefaultCodable, focusing on the author’s note that like this µpackage idea from guille gonzalez. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Sitrep](https://github.com/twostraws/Sitrep) — iOS Dev Weekly · Issue 442 — Source repository · Topics: Developer Tools
  **Published:** `7th February 2020`
  **NeKI brief:** Examines Sitrep, focusing on interested in what frameworks you’re importing? how many lines of code your biggest source file has? or how many classes,…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [swift-doc](https://github.com/SwiftDocOrg/swift-doc) — iOS Dev Weekly · Issue 441 — Source repository · Topics: Developer Tools · Swift
  **Published:** `31st January 2020`
  **NeKI brief:** Examines swift-doc, focusing on as mattt says when talking about the motivation behind building this we’ve been very lucky to have jazzy since the early…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Fast build times for big Swift projects with barber](https://github.com/michaeleisel/barber) — iOS Dev Weekly · Issue 440 — Source repository · Topics: Developer Tools · Swift
  **Published:** `24th January 2020`
  **NeKI brief:** Examines Fast build times for big Swift projects with barber, focusing on there are two interesting things about this project from michael eisel. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Spek](https://github.com/onmyway133/Spek) — iOS Dev Weekly · Issue 439 — Source repository · Topics: Developer Tools · Swift · Testing
  **Published:** `17th January 2020`
  **NeKI brief:** Examines Spek, focusing on this new bdd testing framework from khoa pham is implemented with swift 5.1 function builders and uses xctest assertions. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [this post from Jesse Squires](https://www.jessesquires.com/blog/selecting-an-xcode-version-on-github-ci) — iOS Dev Weekly · Issue 438 — Article · Topics: Developer Tools · Xcode
  **Published:** `10th January 2020`
  **NeKI brief:** Explains selecting an Xcode version in GitHub Actions, covering runner images and reproducible CI configuration. Compare its pinning strategy with your workflow, then verify currently supported macOS and Xcode combinations.
- [UBKAccessibilityKit](https://github.com/NAB/UBKAccessibilityKit) — iOS Dev Weekly · Issue 437 — Source repository · Topics: Accessibility · Developer Tools · Testing
  **Published:** `3rd January 2020`
  **NeKI brief:** Examines UBKAccessibilityKit, focusing on it’s typical, isn’t it? you wait years for a good accessibility testing framework and then two come along at once! 😂 this…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [new server-side frameworks for Swift continuing to pop up](https://github.com/amzn/smoke-framework) — iOS Dev Weekly · Issue 435 — Source repository · Topics: Developer Tools · Swift
  **Published:** `20th December 2019`
  **NeKI brief:** Examines Smoke Framework, focusing on first ibm, and now amazon with a new server-side swift framework. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [continuously updated](https://github.com/heckj/swiftui-notes/commits/master) — iOS Dev Weekly · Issue 435 — Source repository · Topics: Combine & Reactive Programming · Developer Tools · Swift
  **Published:** `20th December 2019`
  **NeKI brief:** Examines continuously updated, focusing on joseph heck, author of the wonderful (and continuously updated) using combine book talking about throttle and debounce in…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Alley](https://github.com/radianttap/Alley) — iOS Dev Weekly · Issue 434 — Source repository · Topics: Developer Tools · Networking
  **Published:** `13th December 2019`
  **NeKI brief:** Examines Alley, focusing on aleksandar vacić talking about his new micro-framework, alley. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Custom controls in SwiftUI](https://izakpavel.github.io/development/2019/11/28/creating-custom-views-in-swiftui.html) — iOS Dev Weekly · Issue 434 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `13th December 2019`
  **NeKI brief:** Examines Custom controls in SwiftUI, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Performance Battle: AnyView vs Group in SwiftUI](https://nalexn.github.io/anyview-vs-group) — iOS Dev Weekly · Issue 434 — Article · Topics: Performance · Swift · SwiftUI
  **Published:** `13th December 2019`
  **NeKI brief:** Examines Performance Battle: AnyView vs Group in SwiftUI, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [SwiftUI Introspect](https://github.com/timbersoftware/SwiftUI-Introspect) — iOS Dev Weekly · Issue 432 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `29th November 2019`
  **NeKI brief:** Examines SwiftUI Introspect, focusing on terrible idea, and i love it. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [AQUI](https://github.com/AlanQuatermain/AQUI) — iOS Dev Weekly · Issue 432 — Source repository · Topics: Core Data · Persistence & Synchronisation · Swift
  **Published:** `29th November 2019`
  **NeKI brief:** Examines AQUI, focusing on jim dovey on how to make swiftui and core data play nicely together using his aqui library. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [WaterfallGrid](https://github.com/paololeonardi/WaterfallGrid) — iOS Dev Weekly · Issue 428 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `1st November 2019`
  **NeKI brief:** Examines WaterfallGrid, focusing on the author’s discussion of linked to qgrid back in issue 414, but what if you need an irregular grid of content in your shiny new swiftui app?…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current.
- [QGrid](https://github.com/Q-Mobile/QGrid) — iOS Dev Weekly · Issue 428 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `1st November 2019`
  **NeKI brief:** Examines QGrid, focusing on the author’s discussion of linked to qgrid back in issue 414, but what if you need an irregular grid of content in your shiny new swiftui app?…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current.
- [SwiftUI Layout System](https://kean.github.io/post/swiftui-layout-system) — iOS Dev Weekly · Issue 427 — Article · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `25th October 2019`
  **NeKI brief:** Examines SwiftUI Layout System, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [SwiftLibrary](https://github.com/kiliankoe/SwiftLibrary) — iOS Dev Weekly · Issue 425 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `11th October 2019`
  **NeKI brief:** Examines SwiftLibrary, focusing on first of all, swiftlibrary from kilian koeltzsch – a command-line search tool built on top of the swiftpm library api. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [package source list](https://github.com/daveverwer/SwiftPMLibrary) — iOS Dev Weekly · Issue 425 — Source repository · Topics: Dependency Injection · Developer Tools · Swift
  **Published:** `11th October 2019`
  **NeKI brief:** Examines package source list, focusing on then, the swift dependency graph from adam fowler – a wonderful visualisation of package dependencies that doesn’t use…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [LLVS project](https://github.com/mentalfaculty/LLVS) — iOS Dev Weekly · Issue 424 — Source repository · Topics: Apple Platform Ecosystem · Combine & Reactive Programming · Persistence & Synchronisation
  **Published:** `4th October 2019`
  **NeKI brief:** Examines LLVS project, focusing on one topic that has been talked about consistently since wwdc is how core data (or any data persistence framework) will be…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [SwiftUI code that generates them](https://gist.github.com/chriseidhof/f1bfea3b26ed23c26f2b016a2d618ba4) — iOS Dev Weekly · Issue 423 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `27th September 2019`
  **NeKI brief:** Examines SwiftUI code that generates them, focusing on the author’s discussion of love it when an interesting tweet turns into a blog post, like this one from chris eidhof did this week. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against.
- [Accessibility in SwiftUI](https://mecid.github.io/2019/09/10/accessibility-in-swiftui) — iOS Dev Weekly · Issue 421 — Article · Topics: Accessibility · Swift · SwiftUI
  **Published:** `13th September 2019`
  **NeKI brief:** Examines Accessibility in SwiftUI, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [The Curious Case of the Core Data Crash](https://blog.iconfactory.com/2019/08/the-curious-case-of-the-core-data-crash) — iOS Dev Weekly · Issue 419 — Article · Topics: Concurrency · Core Data · Developer Tools
  **Published:** `30th August 2019`
  **NeKI brief:** Examines The Curious Case of the Core Data Crash, offering practical guidance on data modeling and persistence trade-offs. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Puma](https://github.com/pumaswift/Puma) — iOS Dev Weekly · Issue 418 — Source repository · Topics: CI/CD & Automation · Developer Tools · Swift
  **Published:** `23rd August 2019`
  **NeKI brief:** Examines Puma, focusing on build utilities, written in pure swift (not that that really matters for build utilities) from khoa pham. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [ColoredConsole](https://github.com/jjrscott/ColoredConsole) — iOS Dev Weekly · Issue 418 — Source repository · Topics: Developer Tools · Xcode
  **Published:** `23rd August 2019`
  **NeKI brief:** Examines ColoredConsole, focusing on relive the glory days of xcode 8 extensions with this really clever ligature hack from john scott. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [The Shape API in SwiftUI](https://mecid.github.io/2019/08/14/building-barchart-with-shape-api-in-swiftui) — iOS Dev Weekly · Issue 417 — Article · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `16th August 2019`
  **NeKI brief:** Examines The Shape API in SwiftUI, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Chisel](https://github.com/facebook/chisel) — iOS Dev Weekly · Issue 416 — Source repository · Topics: Developer Tools
  **Published:** `9th August 2019`
  **NeKI brief:** Provides the chisel source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [performance testing](https://github.com/quickbirdstudios/CombineRxSwiftPerformance/blob/master/Readme.md) — iOS Dev Weekly · Issue 416 — Source repository · Topics: Combine & Reactive Programming · Performance · Testing
  **Published:** `9th August 2019`
  **NeKI brief:** Examines performance testing, focusing on so much combine content this week! we’ll finish with stefan kofler taking a balanced look comparing rxswift to combine. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [sample code](https://github.com/swiftingio/NFCWriter) — iOS Dev Weekly · Issue 414 — Source repository · Topics: Developer Tools · Swift
  **Published:** `26th July 2019`
  **NeKI brief:** Examines sample code, focusing on core nfc is getting a big upgrade in ios 13. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [MovieSwiftUI](https://github.com/Dimillian/MovieSwiftUI) — iOS Dev Weekly · Issue 413 — Source repository · Topics: Combine & Reactive Programming · Swift · SwiftUI
  **Published:** `19th July 2019`
  **NeKI brief:** Examines MovieSwiftUI, focusing on how far can swiftui (and combine) go before you need to resort to uiviewrepresentable? thomas ricouard has been doing…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Gestures in SwiftUI](https://mecid.github.io/2019/07/10/gestures-in-swiftui) — iOS Dev Weekly · Issue 412 — Article · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `12th July 2019`
  **NeKI brief:** Examines Gestures in SwiftUI, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [NSAttributedStringBuilder](https://github.com/ethanhuang13/NSAttributedStringBuilder) — iOS Dev Weekly · Issue 412 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `12th July 2019`
  **NeKI brief:** Examines NSAttributedStringBuilder, focusing on swiftui makes the construction of views and ui easy. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [RetroRampage](https://github.com/nicklockwood/RetroRampage) — iOS Dev Weekly · Issue 411 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `5th July 2019`
  **NeKI brief:** Examines RetroRampage, focusing on finally with a welcome break from swiftui hot takes is this tutorial series from nick lockwood on how to implement a…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [this test](https://gist.github.com/mattgallagher/eaa5d3242d83360a52c45c9706479e34) — iOS Dev Weekly · Issue 410 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Testing
  **Published:** `28th June 2019`
  **NeKI brief:** Examines this test, focusing on when i saw this tweet i did wonder whether we were going to find that the true cost of a great api was runtime…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against.
- [Building forms with SwiftUI](https://mecid.github.io/2019/06/19/building-forms-with-swiftui) — iOS Dev Weekly · Issue 409 — Article · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `21st June 2019`
  **NeKI brief:** Covers Building forms with SwiftUI, focusing on Apple UI composition and interaction design. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [Solving ambiguous constraints without rerunning your app](https://mar.codes/2019-05-28/Solving-ambiguous-constraints-without-rerunning-your-app) — iOS Dev Weekly · Issue 406 — Article · Topics: Developer Tools · Objective-C & Cocoa · Personal Essays
  **Published:** `31st May 2019`
  **NeKI brief:** Covers Solving ambiguous constraints without rerunning your app, focusing on Swift and Apple-platform engineering practice. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [this project](https://github.com/tarunon/XCTAssertAutolayout) — iOS Dev Weekly · Issue 406 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Xcode
  **Published:** `31st May 2019`
  **NeKI brief:** Examines this project, focusing on tweak a constraint, build and run, tweak a constraint, build and run, tweak, build, tweak… there must be a better way?…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [well documented](https://github.com/groue/GRDB.swift/blob/master/README.md) — iOS Dev Weekly · Issue 405 — Source repository · Topics: Developer Tools · Persistence & Synchronisation · Swift
  **Published:** `24th May 2019`
  **NeKI brief:** Examines well documented, focusing on the author’s note that hadn’t come across gwendal roué’s sqlite wrapper for swift until i saw the announcement of v4 this week. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Type-safe tags in Swift](https://github.com/alexruperez/Tagging) — iOS Dev Weekly · Issue 404 — Source repository · Topics: Developer Tools · Swift
  **Published:** `17th May 2019`
  **NeKI brief:** Examines Type-safe tags in Swift, focusing on the author’s discussion of love it when blog posts and open source projects feed into each other. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [associated library](https://github.com/JohnSundell/Identity) — iOS Dev Weekly · Issue 404 — Source repository · Topics: Developer Tools · Swift
  **Published:** `17th May 2019`
  **NeKI brief:** Examines associated library, focusing on the author’s discussion of love it when blog posts and open source projects feed into each other. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [In App visual debugger](https://github.com/indragiek/InAppViewDebugger) — iOS Dev Weekly · Issue 402 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Xcode
  **Published:** `3rd May 2019`
  **NeKI brief:** Examines In App visual debugger, focusing on it’s probably not too much of a hassle to have a mac connected to your app so you can use reveal or the built in xcode…. Use it as a focused research reference for related Apple-platform work, and.
- [async/await](https://gist.github.com/lattner/429b9070918248274f25b714dcfc7619) — iOS Dev Weekly · Issue 402 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `3rd May 2019`
  **NeKI brief:** Examines async/await proposal, focusing on there has been plenty of speculation that language native concurrency will be a focus for a future release of swift. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Markdown Playgrounds for Swift](https://github.com/objcio/markdown-playgrounds) — iOS Dev Weekly · Issue 400 — Source repository · Topics: Developer Tools · Swift
  **Published:** `19th April 2019`
  **NeKI brief:** Examines Markdown Playgrounds for Swift, focusing on while updating their advanced swift book, chris eidhof and florian kugler frequently found themselves needing to execute…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [NavigationEngine](https://github.com/justeat/NavigationEngineDemo) — iOS Dev Weekly · Issue 400 — Source repository · Topics: Developer Tools · Navigation & Deep Linking
  **Published:** `19th April 2019`
  **NeKI brief:** Examines NavigationEngine, focusing on getting ios deep linking right is hard and a good solution usually needs to be baked in to the core of your app. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Blueprint: Declarative UI construction for iOS](https://github.com/square/Blueprint) — iOS Dev Weekly · Issue 398 — Source repository · Topics: Developer Community & Business · Developer Tools · Swift
  **Published:** `5th April 2019`
  **NeKI brief:** Examines Blueprint: Declarative UI construction for iOS, focusing on are apple working on a declarative, swift only ui api for us to use in the future? maybe! but why wait for that when you…. Use it as a focused research reference for related Apple-platform work.
- [simple playground example](https://github.com/timothymiko/swift-networking-examples) — iOS Dev Weekly · Issue 398 — Source repository · Topics: Dependency Injection · Developer Tools · Networking
  **Published:** `5th April 2019`
  **NeKI brief:** Examines simple playground example, focusing on i’ve said this a few times over the years but the reasons for using a third party networking library get fewer and fewer…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against.
- [UIView styling with functions](https://felginep.github.io/2019-02-19/uiview-styling-with-functions) — iOS Dev Weekly · Issue 393 — Article · Topics: Developer Tools
  **Published:** `1st March 2019`
  **NeKI brief:** Covers UIView styling with functions, focusing on Apple UI composition and interaction design. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [xcodeproj](https://github.com/tuist/xcodeproj) — iOS Dev Weekly · Issue 391 — Source repository · Topics: Developer Tools · Swift · Xcode
  **Published:** `15th February 2019`
  **NeKI brief:** Examines xcodeproj, focusing on back in issue 362 i linked to xcodegen, a way to generate your project files with yaml. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Swinject in practice](https://felginep.github.io/2019-02-05/swinject-in-practice) — iOS Dev Weekly · Issue 390 — Article · Topics: Architecture · Dependency Injection · Developer Tools
  **Published:** `8th February 2019`
  **NeKI brief:** Examines Swinject in practice, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [check out](https://github.com/wibosco/CoreDataMigrationRevised-Example) — iOS Dev Weekly · Issue 390 — Source repository · Topics: Core Data · Developer Tools · Persistence & Synchronisation
  **Published:** `8th February 2019`
  **NeKI brief:** Examines check out, focusing on comprehensive and well written look at the migration process for core data by william boles. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Path.swift](https://github.com/mxcl/Path.swift) — iOS Dev Weekly · Issue 388 — Source repository · Topics: Developer Tools · Foundation & Data Formats · Swift
  **Published:** `25th January 2019`
  **NeKI brief:** Examines Path.swift, focusing on the url/path manipulation methods in foundation have always been powerful, but also very verbose so this new wrapper…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [It’s time to use Swift Package Manager](http://artsy.github.io/blog/2019/01/05/its-time-to-use-spm) — iOS Dev Weekly · Issue 386 — Article · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `11th January 2019`
  **NeKI brief:** Covers It's time to use Swift Package Manager, focusing on Swift tooling and build integration. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [library](https://github.com/radianttap/Coordinator) — iOS Dev Weekly · Issue 385 — Source repository · Topics: Developer Tools · Navigation & Deep Linking · UIKit
  **Published:** `4th January 2019`
  **NeKI brief:** Examines library, focusing on aleksandar vacić with a great post (and library) on how he has tried to integrated the coordinator pattern with uikit. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Shapeshift](https://github.com/JohnSundell/Shapeshift) — iOS Dev Weekly · Issue 383 — Source repository · Topics: Developer Tools · Swift
  **Published:** `21st December 2018`
  **NeKI brief:** Examines Shapeshift, focusing on how do you easily get swift code into the ipad version of swift playgrounds? john sundell figured this was a problem that…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [changing in Swift 5](https://github.com/apple/swift-evolution/blob/master/proposals/0228-fix-expressiblebystringinterpolation.md) — iOS Dev Weekly · Issue 383 — Source repository · Topics: Developer Tools · Swift
  **Published:** `21st December 2018`
  **NeKI brief:** Examines changing in Swift 5, focusing on string interpolation is changing in swift 5 and erica sadun has put together a three part blog post on the subject. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current.
- [SwiftRewriter](https://github.com/inamiy/SwiftRewriter) — iOS Dev Weekly · Issue 382 — Source repository · Topics: Developer Tools · Swift
  **Published:** `14th December 2018`
  **NeKI brief:** Examines SwiftRewriter, focusing on first there was swiftformat (which is still very actively maintained!) but this week saw the first release of a new code…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [very actively maintained](https://github.com/nicklockwood/SwiftFormat/blob/9c008683c3b814a1ab9cd10bd3f6b29da34449bb/CHANGELOG.md) — iOS Dev Weekly · Issue 382 — Source repository · Topics: Developer Tools · Swift
  **Published:** `14th December 2018`
  **NeKI brief:** Examines very actively maintained, focusing on first there was swiftformat (which is still very actively maintained!) but this week saw the first release of a new code…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Xcode Comment Spell Checker](https://github.com/velyan/Comment-Spell-Checker) — iOS Dev Weekly · Issue 381 — Source repository · Topics: Developer Tools · Xcode
  **Published:** `7th December 2018`
  **NeKI brief:** Examines Xcode Comment Spell Checker, focusing on the author’s discussion of think it’s safe to say that the “new” xcode extensions have been a disappointment, mainly due to the restriction of…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current.
- [Xcode and LLDB Advanced Debugging](https://medium.com/@fadiderias/xcode-and-lldb-advanced-debugging-tutorial-part-1-31919aa149e0) — iOS Dev Weekly · Issue 380 — Tutorial · Topics: Developer Tools · Xcode
  **Published:** `30th November 2018`
  **NeKI brief:** Examines Xcode and LLDB Advanced Debugging, focusing on three part series of posts (part 1, part 2 and part 3) from fady derias which is sure to teach you a few things you…. Use it as a focused research reference for related Apple-platform work, and.
- [Daily Tips from the Swift world](https://github.com/MobileTipsters/Swift-Daily-Tips) — iOS Dev Weekly · Issue 379 — Source repository · Topics: Developer Tools · Swift
  **Published:** `23rd November 2018`
  **NeKI brief:** Examines Daily Tips from the Swift world, focusing on every time i see a project with “weekly” in the name, i think back to 2011 and remember thinking “how hard can it be to…. Use it as a focused research reference for related Apple-platform work.
- [this project](https://github.com/AvdLee/appstoreconnect-swift-sdk) — iOS Dev Weekly · Issue 377 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Swift
  **Published:** `9th November 2018`
  **NeKI brief:** Examines this project, focusing on the app store connect api is available and documented! straight away, antoine van der lee jumped into action and started…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [this library](https://github.com/airbnb/AloeStackView) — iOS Dev Weekly · Issue 376 — Source repository · Topics: Developer Tools · Testing
  **Published:** `2nd November 2018`
  **NeKI brief:** Examines this library, focusing on when uistackview isn’t quite enough and uitableview feels unwieldy for managing disparate collections of controls, where…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [don’t want them in source control](https://github.com/dxa4481/truffleHog) — iOS Dev Weekly · Issue 375 — Source repository · Topics: Developer Tools
  **Published:** `26th October 2018`
  **NeKI brief:** Examines don’t want them in source control, focusing on how do you share the api keys and other secrets that need to be present to get your projects built and shipped? obviously…. Use it as a focused research reference for related Apple-platform work, and verify.
- [CSProgress](https://github.com/CharlesJS/CSProgress) — iOS Dev Weekly · Issue 372 — Source repository · Topics: Developer Tools · Performance · Personal Essays
  **Published:** `5th October 2018`
  **NeKI brief:** Examines CSProgress, focusing on it’s ironic that using nsprogress to report on your long running task might actually make it slower. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [BulletinBoard](https://github.com/alexaubry/BulletinBoard) — iOS Dev Weekly · Issue 371 — Source repository · Topics: Developer Tools
  **Published:** `28th September 2018`
  **NeKI brief:** Examines BulletinBoard, focusing on this library from alex aubry is lovely. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [accompanying playground](https://github.com/twostraws/whats-new-in-swift-5-0) — iOS Dev Weekly · Issue 370 — Source repository · Topics: Developer Tools · Swift
  **Published:** `21st September 2018`
  **NeKI brief:** Examines accompanying playground, focusing on oh and if you’re wondering how swift 5.0 is shaping up so far, paul hudson has the jump on that with a post and…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against.
- [What I Learned Making 5 ARKit Prototypes](https://medium.com/@nathangitter/what-i-learned-making-five-arkit-prototypes-7a30c0cd3956) — iOS Dev Weekly · Issue 369 — Article · Topics: Developer Tools · Spatial Computing
  **Published:** `14th September 2018`
  **NeKI brief:** Examines What I Learned Making 5 ARKit Prototypes, focusing on the author’s note that talked about some of nathan gitter’s arkit prototypes back in issue 362 so i was pleased to read this write up of his…. Use it as a focused research reference for related Apple-platform work.
- [previous side projects](https://github.com/JohnSundell/Marathon) — iOS Dev Weekly · Issue 367 — Source repository · Topics: Developer Community & Business · Developer Tools
  **Published:** `31st August 2018`
  **NeKI brief:** Examines Marathon, focusing on we know that swift is intended to be usable as a scripting language, but there are some rough edges around actually using…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [swiff](https://github.com/agens-no/swiff) — iOS Dev Weekly · Issue 366 — Source repository · Topics: CI/CD & Automation · Developer Tools
  **Published:** `24th August 2018`
  **NeKI brief:** Examines swiff, focusing on this script from håvard fossli looks useful. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Validated](https://github.com/pointfreeco/swift-validated) — iOS Dev Weekly · Issue 366 — Source repository · Topics: Developer Tools · Swift
  **Published:** `24th August 2018`
  **NeKI brief:** Examines Validated, focusing on validated from brandon williams and stephen celis is a tiny library for collecting multiple errors together rather than…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [playground](https://github.com/ra1028/DifferenceKit/blob/master/DifferenceKit.playground/Contents.swift) — iOS Dev Weekly · Issue 366 — Source repository · Topics: Developer Tools · Swift
  **Published:** `24th August 2018`
  **NeKI brief:** Examines playground, focusing on ryo aoyama with a library designed to work with performbatchupdates on table and collection views to allow fast…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [xiblint](https://github.com/lyft/xiblint) — iOS Dev Weekly · Issue 364 — Source repository · Topics: Accessibility · Developer Tools · Swift
  **Published:** `10th August 2018`
  **NeKI brief:** Examines xiblint, focusing on swiftlint is a fantastic tool for keeping your code standards in check, but what about storyboards and xibs? with checks…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [xcode-install](https://github.com/krausefx/xcode-install) — iOS Dev Weekly · Issue 364 — Source repository · Topics: Developer Tools · Xcode
  **Published:** `10th August 2018`
  **NeKI brief:** Examines xcode-install, focusing on the author’s note that saw this tweet by felix krause this week and it seemed like a good idea to remind everyone that during this period of…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current.
- [Swift in 60 seconds](https://www.hackingwithswift.com/sixty) — iOS Dev Weekly · Issue 364 — Article · Topics: Developer Tools · Swift
  **Published:** `10th August 2018`
  **NeKI brief:** Explores Swift in 60 seconds in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Charles](https://www.charlesproxy.com/documentation/ios) — iOS Dev Weekly · Issue 363 — Article · Topics: Developer Tools
  **Published:** `3rd August 2018`
  **NeKI brief:** Profiles Charles, a developer tool or product relevant to Apple-platform workflows. Evaluate its integration surface, operational costs, privacy implications, and fit for the current project, then verify supported SDKs and capabilities before adoption.
- [battle tested networking library](https://github.com/twitter/ios-twitter-network-layer) — iOS Dev Weekly · Issue 361 — Source repository · Topics: Developer Community & Business · Networking · Testing
  **Published:** `20th July 2018`
  **NeKI brief:** Examines battle tested networking library, focusing on is this a networking library where every request only returns the first 280 characters of data? 🤣 no, of course it isn’t. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against.
- [Bartinter](https://github.com/MaximKotliar/Bartinter) — iOS Dev Weekly · Issue 359 — Source repository · Topics: Developer Tools
  **Published:** `6th July 2018`
  **NeKI brief:** Examines Bartinter, focusing on really nice idea from maxim kotliar. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Money](https://github.com/Flight-School/Money) — iOS Dev Weekly · Issue 358 — Source repository · Topics: Developer Tools · Testing
  **Published:** `29th June 2018`
  **NeKI brief:** Examines Money, focusing on described as a precise, type-safe representation of a monetary amount in a given currency, this library is extracted from…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [App Store Guidelines](https://gist.github.com/hongrich/260fc8c36aaed3f2a63c0612ba9fc910/revisions) — iOS Dev Weekly · Issue 355 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Spatial Computing
  **Published:** `8th June 2018`
  **NeKI brief:** Examines App Store Guidelines, focusing on but dave, what about all the other stuff from this week? what about the new app store guidelines, the swift 5 delay,…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current.
- [Swift 5 delay](https://github.com/apple/swift-evolution/commit/de7727f7dcf7bbfdea6763a87f4c8c534f27406e) — iOS Dev Weekly · Issue 355 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Swift
  **Published:** `8th June 2018`
  **NeKI brief:** Examines Swift 5 delay, focusing on but dave, what about all the other stuff from this week? what about the new app store guidelines, the swift 5 delay,…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current.
- [git branch and clean/dirty status](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/daveverwer.zsh-theme) — iOS Dev Weekly · Issue 354 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Xcode
  **Published:** `1st June 2018`
  **NeKI brief:** Examines git branch and clean/dirty status, focusing on nice tip from marc palmer on including various information in your terminal prompt. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Want to automatically build, test, and release your apps? Try App Center](https://www.youtube.com/watch?v=RDluKlJneZA) — iOS Dev Weekly · Issue 353 — Video · Topics: Developer Tools · Testing
  **Published:** `25th May 2018`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [xcprojectlint: A security blanket for Xcode project files](https://github.com/americanexpress/xcprojectlint) — iOS Dev Weekly · Issue 353 — Source repository · Topics: Developer Tools · Security & Privacy · Xcode
  **Published:** `25th May 2018`
  **NeKI brief:** Examines xcprojectlint: A security blanket for Xcode project files, focusing on would you like to automate some consistency in your xcode project files with checks for settings defined at the project…. Use it as a focused research reference for related Apple-platform work, and verify version-specific.
- [Microsoft and GitHub Present: A Solution for Mobile CI](https://aka.ms/appcentermarketplace) — iOS Dev Weekly · Issue 351 — Article · Topics: CI/CD & Automation · Developer Tools · Testing
  **Published:** `11th May 2018`
  **NeKI brief:** Examines Microsoft and GitHub Present: A Solution for Mobile CI, focusing on automate the build-test-distribute process for your mobile projects in github. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [SwiftNIO](https://github.com/apple/swift-nio) — iOS Dev Weekly · Issue 351 — Source repository · Topics: Developer Tools · Swift
  **Published:** `11th May 2018`
  **NeKI brief:** Examines SwiftNIO, focusing on it’s great to see this major release from the vapor team and it’s encouraging to see that it’s been built on top of…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [this Swift implementation](https://github.com/cgoldsby/LoginCritter) — iOS Dev Weekly · Issue 349 — Source repository · Topics: Developer Community & Business · Developer Tools · Swift
  **Published:** `27th April 2018`
  **NeKI brief:** Examines this Swift implementation, focusing on the author’s note that came across this ui experiment by darin senneff a couple of months ago, take a second to go and look at it before…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details.
- [this useful repository](https://github.com/jonreid/XcodeWarnings) — iOS Dev Weekly · Issue 348 — Source repository · Topics: Developer Tools · Xcode
  **Published:** `20th April 2018`
  **NeKI brief:** Examines this useful repository, focusing on steve kalkwarf on why xcconfig files are wonderful, and why you should use them. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [latest release](https://github.com/realm/SwiftLint/releases/tag/0.25.1) — iOS Dev Weekly · Issue 347 — Source repository · Topics: Developer Community & Business · Swift · Testing
  **Published:** `13th April 2018`
  **NeKI brief:** Examines latest release, focusing on the author’s note that said a couple of weeks ago that i was going to link to some established, and well maintained frameworks and when i came…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against.
- [this library](https://github.com/dreymonde/Delegated) — iOS Dev Weekly · Issue 344 — Source repository · Topics: Developer Tools
  **Published:** `23rd March 2018`
  **NeKI brief:** Examines this library, focusing on i’m a little conflicted about this library from oleg dreyman. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Layout](https://github.com/schibsted/layout) — iOS Dev Weekly · Issue 344 — Source repository · Topics: Developer Tools
  **Published:** `23rd March 2018`
  **NeKI brief:** Examines Layout, focusing on nick lockwood on layout a new declarative ui framework released last week. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Edit Breakpoints in Xcode](https://medium.com/@iostechset/edit-breakpoints-in-xcode-a20b4e453598) — iOS Dev Weekly · Issue 338 — Article · Topics: App Intents & System Surfaces · Developer Tools · Xcode
  **Published:** `9th February 2018`
  **NeKI brief:** Examines Edit Breakpoints in Xcode, focusing on breakpoints are extremely powerful, but how many of us use them just to freeze the app and use the debugger? this article…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against.
- [Promises by Google](https://github.com/google/promises) — iOS Dev Weekly · Issue 337 — Source repository · Topics: Concurrency · Developer Tools · Testing
  **Published:** `2nd February 2018`
  **NeKI brief:** Examines Promises by Google, focusing on the author’s note that recommend checking out promises if you hate the messiness that comes with nested async operations. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [evolution proposal](https://github.com/apple/swift-evolution/blob/master/proposals/0143-conditional-conformances.md) — iOS Dev Weekly · Issue 335 — Source repository · Topics: Developer Tools · Swift
  **Published:** `19th January 2018`
  **NeKI brief:** Examines evolution proposal, focusing on so planning for swift 4.1 is well underway now and this post by ben cohen brings us up to speed on some of the changes…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details.
- [Slanted Layout](https://github.com/yacir/CollectionViewSlantedLayout) — iOS Dev Weekly · Issue 334 — Source repository · Topics: Developer Tools · Swift
  **Published:** `12th January 2018`
  **NeKI brief:** Examines Slanted Layout, focusing on fully configurable subclass of uicollectionviewlayout that allows the display of slanted cells. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [quicktype](https://github.com/quicktype/quicktype-xcode) — iOS Dev Weekly · Issue 333 — Source repository · Topics: Developer Tools · Swift · Xcode
  **Published:** `5th January 2018`
  **NeKI brief:** Examines quicktype, focusing on this xcode extension created by david siegel takes in raw json and spits out swift structs to represent the data. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [RxFlow](https://github.com/RxSwiftCommunity/RxFlow) — iOS Dev Weekly · Issue 333 — Source repository · Topics: Developer Community & Business · Developer Tools · Swift
  **Published:** `5th January 2018`
  **NeKI brief:** Examines RxFlow, focusing on as reactive programming continues to become even more popular, we’re going to see even more ways that it can make writing…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [LSAnimator and CoreAnimator](https://github.com/Lision/LSAnimator) — iOS Dev Weekly · Issue 333 — Source repository · Topics: Concurrency · Developer Tools · Objective-C & Cocoa
  **Published:** `5th January 2018`
  **NeKI brief:** Examines LSAnimator and CoreAnimator, focusing on chained animations are annoying to deal with using standard frameworks, and trying to add concurrency on top of this is…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [SwiftKotlin](https://github.com/angelolloqui/SwiftKotlin) — iOS Dev Weekly · Issue 332 — Source repository · Topics: Developer Tools · Swift
  **Published:** `22nd December 2017`
  **NeKI brief:** Examines SwiftKotlin, focusing on tool for converting swift code to kotlin. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Apple open-sources Turi Create](https://github.com/apple/turicreate) — iOS Dev Weekly · Issue 331 — Source repository · Topics: AI Development · Developer Tools
  **Published:** `15th December 2017`
  **NeKI brief:** Examines Apple open-sources Turi Create, focusing on by releasing turi create to the public, apple is making is easier than ever for people without a machine learning…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Ease](https://github.com/roberthein/Ease) — iOS Dev Weekly · Issue 331 — Source repository · Topics: Developer Tools · UIKit
  **Published:** `15th December 2017`
  **NeKI brief:** Examines Ease, focusing on robert-hein hooijmans just released this animation framework which makes adding spring animations a breeze. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [IceCream](https://github.com/caiyue1993/IceCream) — iOS Dev Weekly · Issue 329 — Source repository · Topics: Developer Tools · Persistence & Synchronisation
  **Published:** `1st December 2017`
  **NeKI brief:** Examines IceCream, focusing on if you’ve been holding off on syncing your realm database with cloudkit thinking it requires a lot of work, well you’re…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Swizzling in iOS 11 with UIDebuggingInformationOverlay](https://www.raywenderlich.com/177890/swizzling-in-ios-11-with-uidebugginginformationoverlay) — iOS Dev Weekly · Issue 328 — Article · Topics: Developer Tools
  **Published:** `24th November 2017`
  **NeKI brief:** Explores Swizzling in iOS 11 with UIDebuggingInformationOverlay in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [stylesync](https://github.com/dylanslewis/stylesync) — iOS Dev Weekly · Issue 328 — Source repository · Topics: Developer Tools · Swift
  **Published:** `24th November 2017`
  **NeKI brief:** Examines stylesync, focusing on if designers are selecting precise fonts and colors in sketch, why should developers then have to manually copy all these…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Chronology](https://github.com/davedelong/Chronology) — iOS Dev Weekly · Issue 328 — Source repository · Topics: Developer Tools · Foundation & Data Formats · Swift
  **Published:** `24th November 2017`
  **NeKI brief:** Examines Chronology, focusing on former apple software engineer and developer evangelist dave delong is taking on the challenge of creating a swifty date…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Optimizing Swift Build Times](https://github.com/fastred/Optimizing-Swift-Build-Times) — iOS Dev Weekly · Issue 326 — Source repository · Topics: Developer Tools · Swift
  **Published:** `10th November 2017`
  **NeKI brief:** Examines Optimizing Swift Build Times, focusing on over the past 2 years, i’ve seen tons of great advice related to swift compile-time optimizations, spread across dozens…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [WhatsNew](https://github.com/BalestraPatrick/WhatsNew) — iOS Dev Weekly · Issue 325 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Testing
  **Published:** `3rd November 2017`
  **NeKI brief:** Examines WhatsNew, focusing on almost nobody reads app update information in the app store anymore, so how do you let your users know about what’s new…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Developer Tools for UI Debugging](https://medium.com/@dmytro.anokhin/overview-of-developer-tools-for-ui-debugging-122e4995f972) — iOS Dev Weekly · Issue 324 — Article · Topics: Developer Tools
  **Published:** `27th October 2017`
  **NeKI brief:** Examines Developer Tools for UI Debugging, focusing on dmytro anokhin with a great round up of all the tools that we have for debugging our apps. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Closures](https://github.com/vhesener/Closures) — iOS Dev Weekly · Issue 322 — Source repository · Topics: Developer Tools · UIKit
  **Published:** `13th October 2017`
  **NeKI brief:** Examines Closures, focusing on if you ever find uikit controls annoying to use thanks to their extensive uses of target-action or delegation, this is…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [AudioKit 4](https://github.com/AudioKit/AudioKit/releases/tag/v4.0) — iOS Dev Weekly · Issue 319 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `22nd September 2017`
  **NeKI brief:** Examines AudioKit 4, focusing on the author’s discussion of don’t think we’ve ever actually directly linked to audiokit before (although there was a video about it in issue 241)…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [TvOSPinKeyboard](https://github.com/zattoo/tvospinkeyboard) — iOS Dev Weekly · Issue 317 — Source repository · Topics: Developer Tools · Hardware & Devices
  **Published:** `8th September 2017`
  **NeKI brief:** Examines TvOSPinKeyboard, focusing on so many tvos apps require pin authentication, but there is no standard view controller for developers to just plug in. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [prototype](https://github.com/apple/swift/pull/11501) — iOS Dev Weekly · Issue 315 — Source repository · Topics: Concurrency · Developer Community & Business · Swift
  **Published:** `25th August 2017`
  **NeKI brief:** Examines prototype, focusing on there has been plenty of speculation that language native concurrency will be a focus for a future release of swift. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [ABI Stability Manifesto](https://github.com/apple/swift/blob/master/docs/ABIStabilityManifesto.md) — iOS Dev Weekly · Issue 313 — Source repository · Topics: Developer Tools · Swift
  **Published:** `11th August 2017`
  **NeKI brief:** Examines ABI Stability Manifesto, focusing on the swift team is no longer accepting proposals for swift 4, which will be released this fall, and is now looking toward…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current.
- [Queuer](https://github.com/FabrizioBrancati/Queuer) — iOS Dev Weekly · Issue 312 — Source repository · Topics: Concurrency · Developer Tools · Product Design
  **Published:** `4th August 2017`
  **NeKI brief:** Examines Queuer, focusing on built on top of operationqueue and gcd, queuer is a queue manager that makes it easy to create synchronous and…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [User Breakpoints in Xcode](https://pspdfkit.com/blog/2017/user-breakpoints-in-xcode) — iOS Dev Weekly · Issue 309 — Article · Topics: Developer Tools · Xcode
  **Published:** `14th July 2017`
  **NeKI brief:** Explores User Breakpoints in Xcode in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Why Core ML will not work for your app (most likely)](http://alexsosn.github.io/ml/2017/06/09/Core-ML-will-not-Work-for-Your-App.html) — iOS Dev Weekly · Issue 307 — Article · Topics: AI Development · Cross-Platform & Web · Developer Tools
  **Published:** `30th June 2017`
  **NeKI brief:** Explores Why Core ML will not work for your app (most likely) in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [iOS 11 Code Examples](https://github.com/artemnovichkov/iOS-11-by-Examples) — iOS Dev Weekly · Issue 307 — Source repository · Topics: Developer Tools · Testing
  **Published:** `30th June 2017`
  **NeKI brief:** Examines iOS 11 Code Examples, focusing on if you’d like to play with the latest ios 11 apis, but don’t feel like reading the docs or rolling out your own mini…. Use it as a focused research reference for related Apple-platform work, and verify version-specific.
- [UIDebuggingInformationOverlay](http://ryanipete.com/blog/ios/swift/objective-c/uidebugginginformationoverlay) — iOS Dev Weekly · Issue 303 — Article · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2nd June 2017`
  **NeKI brief:** Explores UIDebuggingInformationOverlay in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [DeckTransition](https://github.com/HarshilShah/DeckTransition/blob/master/README.md) — iOS Dev Weekly · Issue 302 — Source repository · Topics: Developer Tools
  **Published:** `26th May 2017`
  **NeKI brief:** Examines DeckTransition, focusing on for those of you looking to add a transition like apple music’s or overcast’s now playing, here you go! 🙌 harshil shah’s…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [MarkdownView](https://github.com/keitaoouchi/MarkdownView) — iOS Dev Weekly · Issue 302 — Source repository · Topics: Developer Tools · Swift
  **Published:** `26th May 2017`
  **NeKI brief:** Examines MarkdownView, focusing on this project makes displaying markdown on ios extremely simple. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Pastel 🎨](https://github.com/cruisediary/Pastel) — iOS Dev Weekly · Issue 301 — Source repository · Topics: Developer Tools
  **Published:** `19th May 2017`
  **NeKI brief:** Examines Pastel 🎨, focusing on seeing how flat colors have become quite popular over the years, i’m willing to bet that gradients will be the next big…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [LicensePlist](https://github.com/mono0926/LicensePlist) — iOS Dev Weekly · Issue 300 — Source repository · Topics: Dependency Injection · Developer Tools · Objective-C & Cocoa
  **Published:** `12th May 2017`
  **NeKI brief:** Examines LicensePlist, focusing on most of us use open-source libraries, and most oss asks that a license be included in apps that use them. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [TLPhotoPicker](https://github.com/tilltue/TLPhotoPicker) — iOS Dev Weekly · Issue 300 — Source repository · Topics: Developer Tools
  **Published:** `12th May 2017`
  **NeKI brief:** Examines TLPhotoPicker, focusing on ios includes an official uiimagepickerviewcontroller class, but like many of its siblings, this view controller is not…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [UIFontComplete](https://github.com/Nirma/UIFontComplete) — iOS Dev Weekly · Issue 299 — Source repository · Topics: Developer Tools · Swift
  **Published:** `5th May 2017`
  **NeKI brief:** Examines UIFontComplete, focusing on the author’s discussion of don’t know about you, but nothing bothers me more than stringly-typed apis in swift. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [few other things](https://github.com/apple/swift-source-compat-suite) — iOS Dev Weekly · Issue 298 — Source repository · Topics: Developer Tools · Swift
  **Published:** `28th April 2017`
  **NeKI brief:** Examines few other things, focusing on well this is a little surprising! to ensure minimal source compatibility issues in future versions of swift, apple…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [SquishButton](https://github.com/BalestraPatrick/SquishButton) — iOS Dev Weekly · Issue 297 — Source repository · Topics: Developer Tools
  **Published:** `21st April 2017`
  **NeKI brief:** Examines SquishButton, focusing on simply described as “a button that squishes when pressed”, this ui component made by patrick balestra is inspired by…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [PersistentStorageSerializable](https://github.com/IvanRublev/PersistentStorageSerializable) — iOS Dev Weekly · Issue 296 — Source repository · Topics: Developer Tools · Swift
  **Published:** `14th April 2017`
  **NeKI brief:** Examines PersistentStorageSerializable, focusing on ivan rublev with a swift library that makes it easy to automatically serialize user preferences with userdefaults or a plist. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Reverting SE-0025 and returning to Swift 2 access levels](https://github.com/apple/swift-evolution/blob/master/proposals/0159-fix-private-access-levels.md) — iOS Dev Weekly · Issue 293 — Source repository · Topics: Developer Tools · Swift
  **Published:** `24th March 2017`
  **NeKI brief:** Examines Reverting SE-0025 and returning to Swift 2 access levels, focusing on the proposal to introduce fileprivate was a controversial one at the time, and while it did get implemented, many of us…. Use it as a focused research reference for related Apple-platform work, and.
- [proposal to introduce fileprivate](https://github.com/apple/swift-evolution/blob/master/proposals/0025-scoped-access-level.md) — iOS Dev Weekly · Issue 293 — Source repository · Topics: Developer Tools · Swift
  **Published:** `24th March 2017`
  **NeKI brief:** Examines proposal to introduce fileprivate, focusing on the proposal to introduce fileprivate was a controversial one at the time, and while it did get implemented, many of us…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current.
- [iOS Continous integration: Xcode Server, Jenkins, Travis and fastlane](http://thebugcode.github.io/ios-continous-integration-choosing-a-build-server-and-tooling) — iOS Dev Weekly · Issue 292 — Article · Topics: CI/CD & Automation · Developer Tools · Xcode
  **Published:** `17th March 2017`
  **NeKI brief:** Profiles iOS Continous integration: Xcode Server, Jenkins, Travis and fastlane, a developer tool or product relevant to Apple-platform workflows. Evaluate its integration surface, operational costs, privacy implications, and fit for the current project, then verify supported SDKs and capabilities before adoption.
- [UITableView ReverseExtension](https://github.com/marty-suzuki/ReverseExtension) — iOS Dev Weekly · Issue 292 — Source repository · Topics: Developer Tools
  **Published:** `17th March 2017`
  **NeKI brief:** Examines UITableView ReverseExtension, focusing on ever wanted to build a messaging view, or anything else where content comes in from the bottom instead of the top? just…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Pageboy](https://github.com/msaps/Pageboy) — iOS Dev Weekly · Issue 291 — Source repository · Topics: Developer Tools
  **Published:** `10th March 2017`
  **NeKI brief:** Examines Pageboy, focusing on merrick sapsford with a uipageviewcontroller replacement that solves some really common problems with the original class…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Attabench](https://github.com/lorentey/Attabench) — iOS Dev Weekly · Issue 290 — Source repository · Topics: Developer Tools
  **Published:** `3rd March 2017`
  **NeKI brief:** Examines Attabench, focusing on so you want to benchmark some code you’ve written, pop a couple of log statement in and output the time. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Guitar](https://github.com/ArtSabintsev/Guitar) — iOS Dev Weekly · Issue 290 — Source repository · Topics: Developer Tools · Foundation & Data Formats · Swift
  **Published:** `3rd March 2017`
  **NeKI brief:** Examines Guitar, focusing on ever found the string class … lacking? arthur sabintsev has put together an extension library which already includes…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Spry](https://github.com/Quick/Spry) — iOS Dev Weekly · Issue 290 — Source repository · Topics: Developer Tools · Testing
  **Published:** `3rd March 2017`
  **NeKI brief:** Examines Spry, focusing on ever wanted to use nimble unit tests inside a playground? then spry will be what you’re looking for. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Swift 3 migration post mortem](https://mozilla-mobile.github.io/ios/firefox/swift/core/2017/02/22/migrating-to-swift-3.0.html) — iOS Dev Weekly · Issue 289 — Article · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `24th February 2017`
  **NeKI brief:** Explores Swift 3 migration post mortem in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Hydra: Promises & Await](https://github.com/malcommac/Hydra) — iOS Dev Weekly · Issue 287 — Source repository · Topics: Developer Tools · Swift
  **Published:** `13th February 2017`
  **NeKI brief:** Examines Hydra: Promises & Await, focusing on daniele margutti with another promises library for swift. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [TinyConstraints](https://github.com/roberthein/TinyConstraints) — iOS Dev Weekly · Issue 287 — Source repository · Topics: Developer Tools · Swift
  **Published:** `13th February 2017`
  **NeKI brief:** Examines TinyConstraints, focusing on there are plenty of libraries for ios that add syntactic sugar to auto layout, so why link to this one? well it…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Guaka](https://github.com/oarrabi/Guaka) — iOS Dev Weekly · Issue 286 — Source repository · Topics: Developer Tools · Swift
  **Published:** `3rd February 2017`
  **NeKI brief:** Examines Guaka, focusing on swift is a great language for building command line tools, but there’s more to a command line tool than just the ability…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [quick demo app](https://github.com/steventroughtonsmith/AlternateIconTest) — iOS Dev Weekly · Issue 285 — Source repository · Topics: Developer Tools · Testing
  **Published:** `27th January 2017`
  **NeKI brief:** Examines quick demo app, focusing on more 10.3 changes! this is a slightly strange feature, but the new beta allows apps to include two icons and change…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [SourceKittenSubl](https://github.com/Dan2552/SourceKittenSubl) — iOS Dev Weekly · Issue 284 — Source repository · Topics: Developer Community & Business · Developer Tools · Xcode
  **Published:** `20th January 2017`
  **NeKI brief:** Examines SourceKittenSubl, focusing on the text editing features of xcode sometimes leave you wanting more compared to some of the standalone editors like atom…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [The Swift String Manifesto](https://github.com/apple/swift/blob/master/docs/StringManifesto.md) — iOS Dev Weekly · Issue 284 — Source repository · Topics: Developer Tools · Swift
  **Published:** `20th January 2017`
  **NeKI brief:** Examines The Swift String Manifesto, focusing on this document appeared last night in the swift repository and it contains a huge amount of information about the plans…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [distcc](https://github.com/distcc/distcc) — iOS Dev Weekly · Issue 283 — Source repository · Topics: Developer Tools · Swift · Xcode
  **Published:** `13th January 2017`
  **NeKI brief:** Examines distcc, focusing on back before xcode 4.3 parallel builds was a feature built directly into xcode, but just because it’s not as easy as…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Injection for Xcode](https://github.com/johnno1962/injectionforxcode) — iOS Dev Weekly · Issue 282 — Source repository · Topics: Developer Tools · Personal Essays · Xcode
  **Published:** `6th January 2017`
  **NeKI brief:** Provides the Injection for Xcode source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [GDPerformanceView](https://github.com/dani-gavrilov/GDPerformanceView-Swift) — iOS Dev Weekly · Issue 282 — Source repository · Topics: Developer Tools · Performance · Swift
  **Published:** `6th January 2017`
  **NeKI brief:** Examines GDPerformanceView, focusing on can you tell the difference between 45fps animation in your app and 60fps? well, yes, you probably can 😀 but wouldn’t it…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [PlayAlways](https://github.com/insidegui/PlayAlways) — iOS Dev Weekly · Issue 281 — Source repository · Topics: Developer Tools · Xcode
  **Published:** `16th December 2016`
  **NeKI brief:** Examines PlayAlways, focusing on guilherme rambo with a new xcode extension. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [XestiMonitors](https://github.com/eBardX/XestiMonitors) — iOS Dev Weekly · Issue 281 — Source repository · Topics: Developer Tools · UIKit
  **Published:** `16th December 2016`
  **NeKI brief:** Examines XestiMonitors, focusing on nsnotification code can be a little messy which is a problem that this library by j. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [AsyncDisplayKit 2.0](https://github.com/facebook/AsyncDisplayKit/releases/tag/2.0) — iOS Dev Weekly · Issue 280 — Source repository · Topics: Concurrency · Developer Tools
  **Published:** `9th December 2016`
  **NeKI brief:** Examines AsyncDisplayKit 2.0, focusing on big changes if you’re using asyncdisplaykit, and from the stats in this post it appears that many people are as it’s…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [RefactoratorApp](https://github.com/johnno1962/RefactoratorApp) — iOS Dev Weekly · Issue 279 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2nd December 2016`
  **NeKI brief:** Examines RefactoratorApp, focusing on it’s pretty clear that apple don’t see refactoring support for swift as any kind of priority in xcode, it’s been more…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Swift renaming plugin](https://github.com/johnno1962/Refactorator) — iOS Dev Weekly · Issue 279 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2nd December 2016`
  **NeKI brief:** Provides the Refactorator source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Understanding Data Race Detection by Implementing it in Swift](http://blog.benjamin-encz.de/post/understanding-data-race-detection-by-implementing-in-swift) — iOS Dev Weekly · Issue 278 — Article · Topics: Developer Tools · Swift
  **Published:** `25th November 2016`
  **NeKI brief:** Explores Understanding Data Race Detection by Implementing it in Swift in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [GlueKit](https://github.com/lorentey/GlueKit) — iOS Dev Weekly · Issue 277 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `18th November 2016`
  **NeKI brief:** Examines GlueKit, focusing on do you miss kvo in swift? well this is going to be worth a look. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Overdrive](https://github.com/arikis/Overdrive) — iOS Dev Weekly · Issue 277 — Source repository · Topics: Concurrency · Dependency Injection · Developer Tools
  **Published:** `18th November 2016`
  **NeKI brief:** Examines Overdrive, focusing on said sikira with a really nice looking concurrency library built on top of gcd. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [PlaygroundTDD](https://github.com/WhiskerzAB/PlaygroundTDD) — iOS Dev Weekly · Issue 276 — Source repository · Topics: Developer Tools · Testing
  **Published:** `11th November 2016`
  **NeKI brief:** Examines PlaygroundTDD, focusing on chris schools and gabriel peart with a small library that adds a playgroundtestobserver to easily run your tests directly…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [markdown parsers](https://github.com/indragiek/CocoaMarkdown) — iOS Dev Weekly · Issue 275 — Source repository · Topics: Dependency Injection · Developer Tools · Swift
  **Published:** `4th November 2016`
  **NeKI brief:** Examines markdown parsers, focusing on loïc lecrenier with a new markdown parser, written in pure swift 3. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Macaw](https://github.com/exyte/Macaw) — iOS Dev Weekly · Issue 274 — Source repository · Topics: Developer Tools · Swift
  **Published:** `28th October 2016`
  **NeKI brief:** Examines Macaw, focusing on this looks great. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Plans for Swift 4.0](https://github.com/apple/swift-evolution/blob/master/README.md) — iOS Dev Weekly · Issue 272 — Source repository · Topics: Developer Tools · Swift · Xcode
  **Published:** `14th October 2016`
  **NeKI brief:** Examines Plans for Swift 4.0, focusing on the swift evolution readme was updated this week with an outline of the release schedule, and priorities for version 4. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [action](https://github.com/apple/swift/pull/1442) — iOS Dev Weekly · Issue 272 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `14th October 2016`
  **NeKI brief:** Provides the pull request source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Import: Xcode extension to automatically add imports](https://github.com/markohlebar/Import) — iOS Dev Weekly · Issue 272 — Source repository · Topics: Concurrency · Developer Tools · Xcode
  **Published:** `14th October 2016`
  **NeKI brief:** Examines Import: Xcode extension to automatically add imports, focusing on let’s face it, there’s a definite lack of code assistance and refactoring tools in xcode, especially when writing swift. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against.
- [Typist: Small Swift UIKit keyboard manager for iOS apps](https://github.com/totocaster/Typist) — iOS Dev Weekly · Issue 271 — Source repository · Topics: Developer Tools · Hardware & Devices · Swift
  **Published:** `7th October 2016`
  **NeKI brief:** Examines Typist: Small Swift UIKit keyboard manager for iOS apps, focusing on this library from toto tvalavadze is kinda interesting. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [HubFramework: Spotify’s component-driven UI framework for iOS](https://github.com/spotify/HubFramework) — iOS Dev Weekly · Issue 270 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `30th September 2016`
  **NeKI brief:** Examines HubFramework: Spotify’s component-driven UI framework for iOS, focusing on talking of component based ui frameworks, this is brand new from spotify. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [demo app](https://github.com/spotify/HubFramework/tree/master/demo) — iOS Dev Weekly · Issue 270 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `30th September 2016`
  **NeKI brief:** Examines demo app, focusing on talking of component based ui frameworks, this is brand new from spotify. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Memory Graph Debugger Tips](http://inessential.com/2016/09/22/memory_graph_debugger_tips) — iOS Dev Weekly · Issue 269 — Article · Topics: Developer Tools · Xcode
  **Published:** `23rd September 2016`
  **NeKI brief:** Explores Memory Graph Debugger Tips in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [VVDocumenter](https://github.com/onevcat/VVDocumenter-Xcode) — iOS Dev Weekly · Issue 267 — Source repository · Topics: Developer Tools · Xcode
  **Published:** `9th September 2016`
  **NeKI brief:** Provides the VVDocumenter source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [SwiftGen 3](http://alisoftware.github.io/news/oss/2016/09/04/swiftgen-3) — iOS Dev Weekly · Issue 267 — Article · Topics: Developer Tools · Swift · Xcode
  **Published:** `9th September 2016`
  **NeKI brief:** Explores SwiftGen 3 in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Perform](https://github.com/thoughtbot/Perform) — iOS Dev Weekly · Issue 267 — Source repository · Topics: Architecture · Dependency Injection · Developer Tools
  **Published:** `9th September 2016`
  **NeKI brief:** Examines Perform, focusing on chris dzombak on the difficulties of dependency injection with view controllers. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [xcenv/xcenv](https://github.com/xcenv/xcenv) — iOS Dev Weekly · Issue 266 — Source repository · Topics: Developer Tools · Xcode
  **Published:** `2nd September 2016`
  **NeKI brief:** Examines xcenv/xcenv, focusing on building from the command line with projects that require different versions of xcode to compile is a little painful. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [depcheck](https://github.com/wojteklu/depcheck) — iOS Dev Weekly · Issue 265 — Source repository · Topics: Dependency Injection · Developer Tools · Swift
  **Published:** `26th August 2016`
  **NeKI brief:** Examines depcheck, focusing on wojtek lukaszuk with a cute little tool that’ll analyse your swift project for class dependencies. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [PMHTTP](https://github.com/postmates/PMHTTP) — iOS Dev Weekly · Issue 264 — Source repository · Topics: Concurrency · Developer Tools · Testing
  **Published:** `18th August 2016`
  **NeKI brief:** Examines PMHTTP, focusing on kevin ballard with a new networking library written in swift but compatible with objective-c, pmhttp. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [reference implementation](https://github.com/tomkowz/NetworkLayerExample) — iOS Dev Weekly · Issue 263 — Source repository · Topics: Architecture · Core Data · Developer Tools
  **Published:** `11th August 2016`
  **NeKI brief:** Examines reference implementation, focusing on tomasz szulc on building network architecture that isn’t dependent on any third party libraries, or any apple provided…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [AspectFillFaceAware](https://github.com/BeauNouvelle/AspectFillFaceAware) — iOS Dev Weekly · Issue 262 — Source repository · Topics: Developer Tools · Performance
  **Published:** `5th August 2016`
  **NeKI brief:** Examines AspectFillFaceAware, focusing on this might as well be called “profilepictureimageview”, but that’s no bad thing! if you need to display a photo of…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [NXDrawKit](https://github.com/Nicejinux/NXDrawKit) — iOS Dev Weekly · Issue 262 — Source repository · Topics: Developer Tools · Product Design
  **Published:** `5th August 2016`
  **NeKI brief:** Examines NXDrawKit, focusing on the author’s note that can see that with imessage apps now being a thing, that it might be the case that the ability to write with your…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current.
- [Writing High-Performance Swift Code](https://github.com/apple/swift/blob/master/docs/OptimizationTips.rst) — iOS Dev Weekly · Issue 261 — Source repository · Topics: Developer Tools · Performance · Swift
  **Published:** `29th July 2016`
  **NeKI brief:** Examines Writing High-Performance Swift Code, focusing on the author’s note that hadn’t come across this document before this week and while it’s targeted mainly at developers working on the swift…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Code signing guides from fastlane](https://github.com/fastlane/fastlane/tree/master/fastlane/docs/Codesigning) — iOS Dev Weekly · Issue 258 — Source repository · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **Published:** `8th July 2016`
  **NeKI brief:** Examines Code signing guides from fastlane, focusing on felix krause with a set of guides covering all things code signing. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [PSTModernizer](https://github.com/PSPDFKit-labs/PSTModernizer) — iOS Dev Weekly · Issue 257 — Source repository · Topics: Developer Community & Business · Developer Tools · UIKit
  **Published:** `1st July 2016`
  **NeKI brief:** Examines PSTModernizer, focusing on what do you do when find a bug in uikit? you file a radar of course! but then what? maybe you find a workaround and fix…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details.
- [stops all unofficial plugins from working](https://github.com/alcatraz/Alcatraz/issues/475) — iOS Dev Weekly · Issue 255 — Source repository · Topics: Developer Tools · Xcode
  **Published:** `17th June 2016`
  **NeKI brief:** Examines stops all unofficial plugins from working, focusing on xcode finally gets official extensions! i’ve never really been a big user of xcode plugins other than to quickly try them…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details.
- [Scrollable GraphView](https://github.com/philackm/Scrollable-GraphView) — iOS Dev Weekly · Issue 253 — Source repository · Topics: Developer Tools
  **Published:** `3rd June 2016`
  **NeKI brief:** Examines Scrollable GraphView, focusing on really, really pretty. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Render: Swift and UIKit a la React](https://github.com/alexdrone/Render) — iOS Dev Weekly · Issue 252 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `27th May 2016`
  **NeKI brief:** Examines Render: Swift and UIKit a la React, focusing on if you like the concept of your ui being purely a function of your app’s state, but are not quite ready to go all in on…. Use it as a focused research reference for related.
- [URL Pattern Matching](http://johnpatrickmorgan.github.io/2016/05/11/URLPatternMatching) — iOS Dev Weekly · Issue 252 — Article · Topics: Developer Tools · Navigation & Deep Linking
  **Published:** `27th May 2016`
  **NeKI brief:** Explores URL Pattern Matching in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Pattern Matching](http://alisoftware.github.io/swift/pattern-matching/2016/03/27/pattern-matching-1) — iOS Dev Weekly · Issue 251 — Article · Topics: Developer Tools · Swift
  **Published:** `20th May 2016`
  **NeKI brief:** Explores Pattern Matching in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Networking](https://github.com/3lvis/Networking) — iOS Dev Weekly · Issue 251 — Source repository · Topics: Developer Tools · Networking · Testing
  **Published:** `20th May 2016`
  **NeKI brief:** Examines Networking, focusing on new networking library from elvis nuñez which shipped a 1.0 this week. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Tweaks](https://github.com/facebook/Tweaks) — iOS Dev Weekly · Issue 250 — Source repository · Topics: Developer Tools
  **Published:** `13th May 2016`
  **NeKI brief:** Provides the Tweaks source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [has been fixed](https://github.com/apple/swift/commit/2cdd7d64e1e2add7bcfd5452d36e7f5fc6c86a03) — iOS Dev Weekly · Issue 249 — Source repository · Topics: Developer Tools · Performance · Swift
  **Published:** `6th May 2016`
  **NeKI brief:** Provides the has been fixed source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [ImageButter](https://github.com/dollarshaveclub/ImageButter) — iOS Dev Weekly · Issue 247 — Source repository · Topics: Developer Tools · Graphics, Media & Games · UIKit
  **Published:** `22nd April 2016`
  **NeKI brief:** Provides the ImageButter source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Using Xcode’s Schemes to run a subset of your tests](http://artsy.github.io/blog/2016/04/06/Testing-Schemes) — iOS Dev Weekly · Issue 245 — Article · Topics: Developer Tools · Testing · Xcode
  **Published:** `8th April 2016`
  **NeKI brief:** Explains Using Xcode’s Schemes to run a subset of your tests with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical.
- [Using Git Hooks to prevent commiting test code](http://appventure.me/2016/04/04/prevent-accidental-test-code-commits) — iOS Dev Weekly · Issue 245 — Article · Topics: Developer Tools · Testing
  **Published:** `8th April 2016`
  **NeKI brief:** Explains Using Git Hooks to prevent commiting test code with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [PeekPop library](https://github.com/marmelroy/peekpop) — iOS Dev Weekly · Issue 242 — Source repository · Topics: Developer Tools
  **Published:** `18th March 2016`
  **NeKI brief:** Provides the PeekPop library source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [GitHub repository](https://github.com/joemasilotti/TestingNSURLSession) — iOS Dev Weekly · Issue 242 — Source repository · Topics: Developer Tools · Networking · Testing
  **Published:** `18th March 2016`
  **NeKI brief:** Provides the GitHub repository source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Code Injection for Xcode](http://artsy.github.io/blog/2016/03/05/iOS-Code-Injection) — iOS Dev Weekly · Issue 241 — Article · Topics: Developer Tools · Graphics, Media & Games · Xcode
  **Published:** `11th March 2016`
  **NeKI brief:** Explains Code Injection for Xcode with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [xcbuild](https://github.com/facebook/xcbuild) — iOS Dev Weekly · Issue 240 — Source repository · Topics: Developer Tools · Testing
  **Published:** `4th March 2016`
  **NeKI brief:** Provides the xcbuild source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [xctool](https://github.com/facebook/xctool) — iOS Dev Weekly · Issue 240 — Source repository · Topics: Developer Tools · Testing
  **Published:** `4th March 2016`
  **NeKI brief:** Provides the xctool source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Being Lazy](http://alisoftware.github.io/swift/2016/02/28/being-lazy) — iOS Dev Weekly · Issue 240 — Article · Topics: Developer Tools · Swift
  **Published:** `4th March 2016`
  **NeKI brief:** Explains Being Lazy with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Kitura](https://github.com/IBM-Swift/Kitura) — iOS Dev Weekly · Issue 239 — Source repository · Topics: Developer Tools · Swift
  **Published:** `26th February 2016`
  **NeKI brief:** Provides the Kitura source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Vapor](https://github.com/tannernelson/vapor) — iOS Dev Weekly · Issue 238 — Source repository · Topics: Developer Tools · Personal Essays · Swift
  **Published:** `19th February 2016`
  **NeKI brief:** Provides the Vapor source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [CocoaPods plugin and CLI for generating Swift Playgrounds](https://github.com/neonichu/ThisCouldBeUsButYouPlaying) — iOS Dev Weekly · Issue 237 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `12th February 2016`
  **NeKI brief:** Provides the CocoaPods plugin and CLI for generating Swift Playgrounds source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [1](https://github.com/apple/swift-evolution/blob/master/proposals/0005-objective-c-name-translation.md) — iOS Dev Weekly · Issue 236 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `5th February 2016`
  **NeKI brief:** Provides the 1 source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [2](https://github.com/apple/swift-evolution/blob/master/proposals/0006-apply-api-guidelines-to-the-standard-library.md) — iOS Dev Weekly · Issue 236 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `5th February 2016`
  **NeKI brief:** Provides the 2 source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [3](https://github.com/apple/swift-evolution/blob/master/proposals/0023-api-guidelines.md) — iOS Dev Weekly · Issue 236 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `5th February 2016`
  **NeKI brief:** Swift Evolution proposal 0023 records the API Design Guidelines that shaped Swift naming and labeling. Use it as historical rationale when reviewing consistency in older Swift code.
- [associated library](https://github.com/linkedin/LayoutTest-iOS) — iOS Dev Weekly · Issue 235 — Source repository · Topics: Developer Tools · Testing
  **Published:** `29th January 2016`
  **NeKI brief:** Provides the associated library source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [VWInstantRun](https://github.com/wangshengjia/VWInstantRun) — iOS Dev Weekly · Issue 232 — Source repository · Topics: Developer Tools · Xcode
  **Published:** `8th January 2016`
  **NeKI brief:** Provides the VWInstantRun source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [PMKVObserver](https://github.com/postmates/PMKVObserver) — iOS Dev Weekly · Issue 231 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `1st January 2016`
  **NeKI brief:** Provides the PMKVObserver source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Hacking Atom to create a Swift IDE](https://medium.com/@Aciid/hacking-atom-to-create-a-swift-ide-that-runs-on-linux-and-mac-c7d9520a0fac) — iOS Dev Weekly · Issue 229 — Article · Topics: Developer Tools · Product Design · Swift
  **Published:** `18th December 2015`
  **NeKI brief:** Explains Hacking Atom to create a Swift IDE with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [swiftenv](https://github.com/kylef/swiftenv) — iOS Dev Weekly · Issue 229 — Source repository · Topics: Developer Tools · Swift
  **Published:** `18th December 2015`
  **NeKI brief:** This source repository covers managing multiple installed Swift toolchains. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [KZLinkedConsole](https://github.com/krzysztofzablocki/KZLinkedConsole) — iOS Dev Weekly · Issue 228 — Source repository · Topics: Developer Tools · Xcode
  **Published:** `11th December 2015`
  **NeKI brief:** Provides the KZLinkedConsole source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [AFNetworking 3](https://github.com/AFNetworking/AFNetworking/releases/tag/3.0.0) — iOS Dev Weekly · Issue 228 — Source repository · Topics: Developer Tools · Networking
  **Published:** `11th December 2015`
  **NeKI brief:** Provides the AFNetworking 3 source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Migration Guide](https://github.com/AFNetworking/AFNetworking/wiki/AFNetworking-3.0-Migration-Guide) — iOS Dev Weekly · Issue 228 — Source repository · Topics: Developer Tools · Networking
  **Published:** `11th December 2015`
  **NeKI brief:** Provides the Migration Guide source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [tackling the hard problems](https://github.com/apple/swift/pull/168/files) — iOS Dev Weekly · Issue 227 — Source repository · Topics: Developer Tools · Swift
  **Published:** `4th December 2015`
  **NeKI brief:** Provides the tackling the hard problems source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Netfox](https://github.com/kasketis/netfox) — iOS Dev Weekly · Issue 226 — Source repository · Topics: Developer Tools
  **Published:** `27th November 2015`
  **NeKI brief:** Provides the Netfox source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [LLDB-Is-It-Not](https://github.com/alloy/LLDB-Is-It-Not) — iOS Dev Weekly · Issue 226 — Source repository · Topics: Developer Tools · Xcode
  **Published:** `27th November 2015`
  **NeKI brief:** Provides the LLDB-Is-It-Not source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Git Diff for Binary Property List Files](http://confusatory.org/post/133141617492/git-diff-for-binary-apple-property-list-files) — iOS Dev Weekly · Issue 225 — Article · Topics: Developer Tools
  **Published:** `20th November 2015`
  **NeKI brief:** Explains Git Diff for Binary Property List Files with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [Reveal-In-Github for Xcode](https://github.com/lzwjava/Reveal-In-Github) — iOS Dev Weekly · Issue 224 — Source repository · Topics: Developer Tools · Xcode
  **Published:** `13th November 2015`
  **NeKI brief:** Provides the Reveal-In-Github for Xcode source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [MPParallaxView](https://github.com/DroidsOnRoids/MPParallaxView) — iOS Dev Weekly · Issue 224 — Source repository · Topics: Developer Tools · UIKit
  **Published:** `13th November 2015`
  **NeKI brief:** Provides the MPParallaxView source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [TVButton](https://github.com/marmelroy/TVButton) — iOS Dev Weekly · Issue 224 — Source repository · Topics: Developer Tools · UIKit
  **Published:** `13th November 2015`
  **NeKI brief:** Provides the TVButton source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [SwiftGen](https://github.com/AliSoftware/SwiftGen?at=11lvzs&ct=ios+dev+tools) — iOS Dev Weekly · Issue 222 — Source repository · Topics: Developer Tools · Swift
  **Published:** `30th October 2015`
  **NeKI brief:** Provides the SwiftGen source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Reachability.swift](https://github.com/ashleymills/Reachability.swift) — iOS Dev Weekly · Issue 222 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `30th October 2015`
  **NeKI brief:** Provides the Reachability.swift source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [UIDynamics, UIKit or OpenGL? 3 Types of iOS Animations for Star Wars](https://yalantis.com/blog/uidynamics-uikit-or-opengl-3-types-of-ios-animations-for-the-star-wars) — iOS Dev Weekly · Issue 221 — Article · Topics: Developer Tools · Graphics, Media & Games · UIKit
  **Published:** `23rd October 2015`
  **NeKI brief:** Explains UIDynamics UIKit or OpenGL 3 Types of iOS Animations for Star Wars with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is.
- [MVVM in Swift](http://artsy.github.io/blog/2015/09/24/mvvm-in-swift) — iOS Dev Weekly · Issue 221 — Article · Topics: Developer Tools · Swift
  **Published:** `23rd October 2015`
  **NeKI brief:** Explains MVVM in Swift with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Xcode Swift Snippets](https://github.com/Abizern/xcode-snippets) — iOS Dev Weekly · Issue 220 — Source repository · Topics: Core Data · Developer Tools · Xcode
  **Published:** `16th October 2015`
  **NeKI brief:** Provides the Xcode Swift Snippets source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [SwiftGo](https://github.com/Zewo/SwiftGo) — iOS Dev Weekly · Issue 219 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `9th October 2015`
  **NeKI brief:** Provides the SwiftGo source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [libmill](https://github.com/sustrik/libmill) — iOS Dev Weekly · Issue 219 — Source repository · Topics: Concurrency · Developer Tools · Performance
  **Published:** `9th October 2015`
  **NeKI brief:** Provides the libmill source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Async](https://github.com/duemunk/Async) — iOS Dev Weekly · Issue 218 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2nd October 2015`
  **NeKI brief:** Provides the Async source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [A Better Way to Automatically Merge Xcode Project Files](https://medium.com/@matto1990/a-better-way-to-automatically-merge-changes-in-your-xcode-project-files-3d83b3583fe4) — iOS Dev Weekly · Issue 217 — Article · Topics: Developer Tools · Xcode
  **Published:** `25th September 2015`
  **NeKI brief:** Explains A Better Way to Automatically Merge Xcode Project Files with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS.
- [BluetoothKit](https://github.com/rasmusth/BluetoothKit) — iOS Dev Weekly · Issue 217 — Source repository · Topics: Developer Tools · Swift
  **Published:** `25th September 2015`
  **NeKI brief:** Provides the BluetoothKit source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Watchdog](https://github.com/wojteklukaszuk/Watchdog) — iOS Dev Weekly · Issue 216 — Source repository · Topics: Developer Tools
  **Published:** `18th September 2015`
  **NeKI brief:** Provides the Watchdog source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [SafariAutoLoginTest](https://github.com/mackuba/SafariAutoLoginTest) — iOS Dev Weekly · Issue 212 — Source repository · Topics: Developer Tools · Testing
  **Published:** `21st August 2015`
  **NeKI brief:** Provides the SafariAutoLoginTest source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [WAAppRouting](https://github.com/Wasappli/WAAppRouting) — iOS Dev Weekly · Issue 212 — Source repository · Topics: Developer Tools · Navigation & Deep Linking
  **Published:** `21st August 2015`
  **NeKI brief:** Provides the WAAppRouting source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [ResponseDetective](https://github.com/netguru/ResponseDetective) — iOS Dev Weekly · Issue 208 — Source repository · Topics: Developer Tools · Networking
  **Published:** `24th July 2015`
  **NeKI brief:** Provides the ResponseDetective source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Address Sanitizer](https://mikeash.com/pyblog/friday-qa-2015-07-03-address-sanitizer.html) — iOS Dev Weekly · Issue 206 — Article · Topics: Apple Platform Ecosystem · Cross-Platform & Web · Developer Tools
  **Published:** `10th July 2015`
  **NeKI brief:** Explains Address Sanitizer with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Fighting Log Entropy](http://spin.atomicobject.com/2015/07/02/fight-logging-entropy) — iOS Dev Weekly · Issue 206 — Article · Topics: Developer Tools · Performance
  **Published:** `10th July 2015`
  **NeKI brief:** Explains Fighting Log Entropy with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [open source annotation server](https://github.com/Kapeli/Dash-Annotations) — iOS Dev Weekly · Issue 205 — Source repository · Topics: Developer Tools · Xcode
  **Published:** `3rd July 2015`
  **NeKI brief:** Provides the open source annotation server source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Xcode Plugin](https://github.com/omz/Dash-Plugin-for-Xcode) — iOS Dev Weekly · Issue 205 — Source repository · Topics: Developer Tools · Xcode
  **Published:** `3rd July 2015`
  **NeKI brief:** Provides the Dash Plugin for Xcode source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [XcodeServerSDK](https://github.com/czechboy0/XcodeServerSDK) — iOS Dev Weekly · Issue 204 — Source repository · Topics: Developer Tools · Swift · Xcode
  **Published:** `26th June 2015`
  **NeKI brief:** Provides the XcodeServerSDK source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Buildasaur](https://github.com/czechboy0/Buildasaur) — iOS Dev Weekly · Issue 204 — Source repository · Topics: Developer Tools · Swift · Xcode
  **Published:** `26th June 2015`
  **NeKI brief:** Provides the Buildasaur source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [UI Testing with Xcode 7](https://medium.com/@larcus94/ui-testing-with-xcode-7-221d16bad276) — iOS Dev Weekly · Issue 204 — Article · Topics: Developer Tools · Testing · Xcode
  **Published:** `26th June 2015`
  **NeKI brief:** Explains UI Testing with Xcode 7 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [sigh](https://github.com/KrauseFx/sigh/releases/tag/1.0.0.beta5) — iOS Dev Weekly · Issue 202 — Source repository · Topics: CI/CD & Automation · Developer Tools
  **Published:** `12th June 2015`
  **NeKI brief:** Provides the sigh source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [CleanroomLogger](https://github.com/emaloney/CleanroomLogger) — iOS Dev Weekly · Issue 198 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `15th May 2015`
  **NeKI brief:** Provides the CleanroomLogger source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Sync](https://github.com/hyperoslo/Sync) — iOS Dev Weekly · Issue 193 — Source repository · Topics: Core Data · Developer Tools · Persistence & Synchronisation
  **Published:** `10th April 2015`
  **NeKI brief:** Provides the Sync source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [iOS Charts](https://github.com/danielgindi/ios-charts) — iOS Dev Weekly · Issue 192 — Source repository · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `3rd April 2015`
  **NeKI brief:** Provides the iOS Charts source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart) — iOS Dev Weekly · Issue 192 — Source repository · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `3rd April 2015`
  **NeKI brief:** Provides the MPAndroidChart source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Xcode Coverage](https://github.com/jonreid/XcodeCoverage) — iOS Dev Weekly · Issue 191 — Source repository · Topics: Developer Tools · Testing · Xcode
  **Published:** `27th March 2015`
  **NeKI brief:** Provides the Xcode Coverage source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Unofficial iTunes Connect API Docs](https://github.com/fastlane/itc-api-docs) — iOS Dev Weekly · Issue 191 — Source repository · Topics: CI/CD & Automation · Developer Tools
  **Published:** `27th March 2015`
  **NeKI brief:** Provides the Unofficial iTunes Connect API Docs source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [available publicly](https://github.com/facebook/react-native) — iOS Dev Weekly · Issue 191 — Source repository · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `27th March 2015`
  **NeKI brief:** Provides the available publicly source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [XCActionBar](https://github.com/pdcgomes/XCActionBar) — iOS Dev Weekly · Issue 190 — Source repository · Topics: Developer Tools · Xcode
  **Published:** `20th March 2015`
  **NeKI brief:** Provides the XCActionBar source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [ReactKit](https://github.com/ReactKit/ReactKit) — iOS Dev Weekly · Issue 188 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `6th March 2015`
  **NeKI brief:** Provides the ReactKit source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa/pull/1382) — iOS Dev Weekly · Issue 188 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `6th March 2015`
  **NeKI brief:** Provides the ReactiveCocoa source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Awesome Swift](https://github.com/matteocrippa/awesome-swift) — iOS Dev Weekly · Issue 187 — Source repository · Topics: Developer Tools · Swift
  **Published:** `27th February 2015`
  **NeKI brief:** Provides the Awesome Swift source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [standard format](https://github.com/bayandin/awesome-awesomeness) — iOS Dev Weekly · Issue 187 — Source repository · Topics: Developer Tools · Swift
  **Published:** `27th February 2015`
  **NeKI brief:** Provides the standard format source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [SwiftMoment](https://github.com/akosma/SwiftMoment) — iOS Dev Weekly · Issue 186 — Source repository · Topics: Developer Tools · Swift
  **Published:** `20th February 2015`
  **NeKI brief:** Provides the SwiftMoment source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [KPRunEverywhereXcodePlugin](https://github.com/kitschpatrol/KPRunEverywhereXcodePlugin) — iOS Dev Weekly · Issue 181 — Source repository · Topics: Developer Tools · Xcode
  **Published:** `16th January 2015`
  **NeKI brief:** Provides the KPRunEverywhereXcodePlugin source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [BigBrother](https://github.com/marcelofabri/BigBrother) — iOS Dev Weekly · Issue 180 — Source repository · Topics: Developer Tools · Networking · Objective-C & Cocoa
  **Published:** `9th January 2015`
  **NeKI brief:** Provides the BigBrother source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Siren](https://github.com/ArtSabintsev/Siren) — iOS Dev Weekly · Issue 180 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `9th January 2015`
  **NeKI brief:** Provides the Siren source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Harpy](https://github.com/ArtSabintsev/Harpy) — iOS Dev Weekly · Issue 180 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `9th January 2015`
  **NeKI brief:** Provides the Harpy source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Debugging: A Case Study](http://www.objc.io/issue-19/debugging-case-study.html) — iOS Dev Weekly · Issue 176 — Article · Topics: Cross-Platform & Web · Developer Tools · Testing
  **Published:** `12th December 2014`
  **NeKI brief:** Explains Debugging A Case Study with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Working Copy](https://itunes.apple.com/us/app/working-copy/id896694807?mt=8) — iOS Dev Weekly · Issue 173 — Article · Topics: Developer Tools
  **Published:** `21st November 2014`
  **NeKI brief:** Explains Working Copy with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [great documentation](https://github.com/stephencelis/SQLite.swift/blob/master/Documentation/Index.md) — iOS Dev Weekly · Issue 173 — Source repository · Topics: Developer Tools · Persistence & Synchronisation · Swift
  **Published:** `21st November 2014`
  **NeKI brief:** Provides the great documentation source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Developing a Bidding Kiosk for iOS in Swift](http://artsy.github.io/blog/2014/11/13/eidolon-retrospective) — iOS Dev Weekly · Issue 172 — Article · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `14th November 2014`
  **NeKI brief:** Explains Developing a Bidding Kiosk for iOS in Swift with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [app is open source](https://github.com/artsy/eidolon) — iOS Dev Weekly · Issue 172 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `14th November 2014`
  **NeKI brief:** Provides the app is open source source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [KMCGeigerCounter](https://github.com/kconner/KMCGeigerCounter) — iOS Dev Weekly · Issue 172 — Source repository · Topics: Developer Tools
  **Published:** `14th November 2014`
  **NeKI brief:** Provides the KMCGeigerCounter source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [SuperRecord](https://github.com/michaelarmstrong/SuperRecord) — iOS Dev Weekly · Issue 169 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `24th October 2014`
  **NeKI brief:** Provides the SuperRecord source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [MagicalRecord](https://github.com/magicalpanda/MagicalRecord) — iOS Dev Weekly · Issue 169 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `24th October 2014`
  **NeKI brief:** Provides the MagicalRecord source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [GitHub Xcode Bot Builder](https://github.com/modcloth-labs/github-xcode-bot-builder) — iOS Dev Weekly · Issue 160 — Source repository · Topics: Developer Tools · Xcode
  **Published:** `22nd August 2014`
  **NeKI brief:** Provides the GitHub Xcode Bot Builder source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [GitDiff](https://github.com/johnno1962/GitDiff) — iOS Dev Weekly · Issue 157 — Source repository · Topics: Developer Tools · Xcode
  **Published:** `1st August 2014`
  **NeKI brief:** Provides the GitDiff source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [How to break (and fix) the accessibility of a table view](https://gist.github.com/d-ronnqvist/3584ccf3379f9c318e4f) — iOS Dev Weekly · Issue 155 — Source repository · Topics: Accessibility · Developer Tools · Testing
  **Published:** `18th July 2014`
  **NeKI brief:** Provides the How to break and fix the accessibility of a table view source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current.
- [Swift In Flux](https://github.com/ksm/SwiftInFlux) — iOS Dev Weekly · Issue 154 — Source repository · Topics: Developer Tools · Product Design · Swift
  **Published:** `11th July 2014`
  **NeKI brief:** Provides the Swift In Flux source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [QueryKit](https://github.com/kylef/QueryKit) — iOS Dev Weekly · Issue 153 — Source repository · Topics: Core Data · Developer Tools · Swift
  **Published:** `4th July 2014`
  **NeKI brief:** Provides the QueryKit source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Popping](https://github.com/schneiderandre/popping) — iOS Dev Weekly · Issue 148 — Source repository · Topics: Developer Tools
  **Published:** `30th May 2014`
  **NeKI brief:** Provides the Popping source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [GitHub repository](https://github.com/albertodebortoli/ADBActors) — iOS Dev Weekly · Issue 147 — Source repository · Topics: Concurrency · Developer Tools · Objective-C & Cocoa
  **Published:** `23rd May 2014`
  **NeKI brief:** Provides the GitHub repository source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Azure API Management makes it easy to publish and manage your APIs](http://azure.microsoft.com/en-us/services/api-management) — iOS Dev Weekly · Issue 146 — Article · Topics: Developer Career & Practice · Developer Tools
  **Published:** `16th May 2014`
  **NeKI brief:** Explains Azure API Management makes it easy to publish and manage your APIs with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is.
- [GPL licensed](https://github.com/chrismiles/DynamicXray/blob/master/LICENSE.txt) — iOS Dev Weekly · Issue 146 — Source repository · Topics: Developer Tools · UIKit
  **Published:** `16th May 2014`
  **NeKI brief:** Provides the GPL licensed source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [PromiseKit](https://github.com/mxcl/PromiseKit) — iOS Dev Weekly · Issue 143 — Source repository · Topics: Concurrency · Developer Tools
  **Published:** `25th April 2014`
  **NeKI brief:** Provides the PromiseKit source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [GCDWebServer](https://github.com/swisspol/GCDWebServer) — iOS Dev Weekly · Issue 142 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `18th April 2014`
  **NeKI brief:** Provides the GCDWebServer source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Polychromatic](https://github.com/kolinkrewinkel/Polychromatic) — iOS Dev Weekly · Issue 141 — Source repository · Topics: Developer Tools · Xcode
  **Published:** `11th April 2014`
  **NeKI brief:** Provides the Polychromatic source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [BRFlabbyTable](https://github.com/brocoo/BRFlabbyTable) — iOS Dev Weekly · Issue 140 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `4th April 2014`
  **NeKI brief:** Provides the BRFlabbyTable source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [YLGIFImage](https://github.com/liyong03/YLGIFImage) — iOS Dev Weekly · Issue 140 — Source repository · Topics: Developer Tools
  **Published:** `4th April 2014`
  **NeKI brief:** Provides the YLGIFImage source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Xtrace](https://github.com/johnno1962/Xtrace) — iOS Dev Weekly · Issue 138 — Source repository · Topics: Developer Tools
  **Published:** `21st March 2014`
  **NeKI brief:** Provides the Xtrace source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Quick Look on UIViews](http://useyourloaf.com/blog/2014/03/12/xcode-debugger-quick-look.html) — iOS Dev Weekly · Issue 137 — Article · Topics: Cross-Platform & Web · Developer Tools · Xcode
  **Published:** `14th March 2014`
  **NeKI brief:** Explains Quick Look on UIViews with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Haneke](https://github.com/hpique/Haneke) — iOS Dev Weekly · Issue 136 — Source repository · Topics: Developer Tools · Networking · UIKit
  **Published:** `7th March 2014`
  **NeKI brief:** Provides the Haneke source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [StoryboardLint](https://github.com/jfahrenkrug/StoryboardLint) — iOS Dev Weekly · Issue 135 — Source repository · Topics: Developer Tools
  **Published:** `28th February 2014`
  **NeKI brief:** Provides the StoryboardLint source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Learn by Doing with Code School](https://www.codeschool.com/paths/ios) — iOS Dev Weekly · Issue 134 — Tutorial · Topics: Cross-Platform & Web · Developer Community & Business · Developer Tools
  **Published:** `21st February 2014`
  **NeKI brief:** Explains Learn by Doing with Code School with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [VENCalculatorInputView](https://github.com/venmo/VENCalculatorInputView) — iOS Dev Weekly · Issue 133 — Source repository · Topics: Developer Tools
  **Published:** `14th February 2014`
  **NeKI brief:** Provides the VENCalculatorInputView source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [CCHMapClusterController](https://github.com/choefele/CCHMapClusterController) — iOS Dev Weekly · Issue 132 — Source repository · Topics: Developer Tools
  **Published:** `7th February 2014`
  **NeKI brief:** Provides the CCHMapClusterController source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [ImageOptim CLI](https://github.com/JamieMason/ImageOptim-CLI) — iOS Dev Weekly · Issue 131 — Source repository · Topics: Developer Tools
  **Published:** `31st January 2014`
  **NeKI brief:** Provides the ImageOptim CLI source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Bolts](https://github.com/BoltsFramework/Bolts-iOS) — iOS Dev Weekly · Issue 131 — Source repository · Topics: Concurrency · Dependency Injection · Developer Tools
  **Published:** `31st January 2014`
  **NeKI brief:** Provides the Bolts source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [fui](https://github.com/dblock/fui) — iOS Dev Weekly · Issue 130 — Source repository · Topics: Developer Tools · Xcode
  **Published:** `24th January 2014`
  **NeKI brief:** Provides the fui source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [ClangFormat Xcode Plugin](https://github.com/travisjeffery/ClangFormat-Xcode) — iOS Dev Weekly · Issue 129 — Source repository · Topics: Developer Tools · Xcode
  **Published:** `17th January 2014`
  **NeKI brief:** Provides the ClangFormat Xcode Plugin source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [UIImageView+FaceAwareFill](https://github.com/Julioacarrettoni/UIImageView_FaceAwareFill) — iOS Dev Weekly · Issue 129 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `17th January 2014`
  **NeKI brief:** Provides the UIImageView+FaceAwareFill source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [objc-run](https://github.com/iljaiwas/objc-run) — iOS Dev Weekly · Issue 128 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `10th January 2014`
  **NeKI brief:** Provides the objc-run source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [EZAudio](https://github.com/syedhali/EZAudio) — iOS Dev Weekly · Issue 127 — Source repository · Topics: Developer Tools
  **Published:** `3rd January 2014`
  **NeKI brief:** Provides the EZAudio source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [SQKeyPath](https://gist.github.com/kyleve/8213806) — iOS Dev Weekly · Issue 127 — Source repository · Topics: Developer Tools · Macros & Metaprogramming
  **Published:** `3rd January 2014`
  **NeKI brief:** Provides the SQKeyPath source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [XCPretty](https://github.com/mneorr/XCPretty) — iOS Dev Weekly · Issue 124 — Source repository · Topics: Developer Tools · Testing · Xcode
  **Published:** `13th December 2013`
  **NeKI brief:** Provides the XCPretty source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [APIClient](https://github.com/klaaspieter/APIClient) — iOS Dev Weekly · Issue 124 — Source repository · Topics: Dependency Injection · Developer Tools · Navigation & Deep Linking
  **Published:** `13th December 2013`
  **NeKI brief:** Provides the APIClient source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [SDCAlertView](https://github.com/Scott90/SDCAlertView) — iOS Dev Weekly · Issue 122 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `29th November 2013`
  **NeKI brief:** Provides the SDCAlertView source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [NHBalancedFlowLayout](https://github.com/njdehoog/NHBalancedFlowLayout) — iOS Dev Weekly · Issue 120 — Source repository · Topics: Developer Tools
  **Published:** `15th November 2013`
  **NeKI brief:** Provides the NHBalancedFlowLayout source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Brushes](https://github.com/sprang/Brushes) — iOS Dev Weekly · Issue 120 — Source repository · Topics: Developer Tools
  **Published:** `15th November 2013`
  **NeKI brief:** Provides the Brushes source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Inkpad](https://github.com/sprang/Inkpad) — iOS Dev Weekly · Issue 119 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Testing
  **Published:** `8th November 2013`
  **NeKI brief:** Provides the Inkpad source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [BeaconEmitter](https://github.com/lgaches/BeaconEmitter) — iOS Dev Weekly · Issue 119 — Source repository · Topics: Developer Tools · Testing
  **Published:** `8th November 2013`
  **NeKI brief:** Provides the BeaconEmitter source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [OvershareKit](https://github.com/overshare/overshare-kit) — iOS Dev Weekly · Issue 118 — Source repository · Topics: Developer Tools
  **Published:** `1st November 2013`
  **NeKI brief:** Provides the OvershareKit source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [UIColor-Pantone](https://github.com/CaptainRedmuff/UIColor-Pantone) — iOS Dev Weekly · Issue 118 — Source repository · Topics: Developer Tools · Performance
  **Published:** `1st November 2013`
  **NeKI brief:** Provides the UIColor-Pantone source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [iOS Snapshot Test Case](https://github.com/facebook/ios-snapshot-test-case) — iOS Dev Weekly · Issue 117 — Source repository · Topics: Developer Tools · Testing · Xcode
  **Published:** `25th October 2013`
  **NeKI brief:** Provides the iOS Snapshot Test Case source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Handlebars for Objective-C](https://github.com/fotonauts/handlebars-objc) — iOS Dev Weekly · Issue 116 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `18th October 2013`
  **NeKI brief:** Provides the Handlebars for Objective-C source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [HiBeacons](https://github.com/nicktoumpelis/HiBeacons) — iOS Dev Weekly · Issue 115 — Source repository · Topics: Developer Tools · Testing
  **Published:** `11th October 2013`
  **NeKI brief:** Provides the HiBeacons source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Xcode 5 Plugin Template](https://github.com/kattrali/Xcode5-Plugin-Template) — iOS Dev Weekly · Issue 114 — Source repository · Topics: Developer Tools · Xcode
  **Published:** `4th October 2013`
  **NeKI brief:** Provides the Xcode 5 Plugin Template source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [LLDB-QuickLook](https://github.com/ryanolsonk/LLDB-QuickLook) — iOS Dev Weekly · Issue 112 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Xcode
  **Published:** `20th September 2013`
  **NeKI brief:** Provides the LLDB-QuickLook source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [FCModel](https://github.com/marcoarment/FCModel) — iOS Dev Weekly · Issue 112 — Source repository · Topics: Core Data · Objective-C & Cocoa · Persistence & Synchronisation
  **Published:** `20th September 2013`
  **NeKI brief:** Provides the FCModel source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [RMStore](https://github.com/robotmedia/RMStore) — iOS Dev Weekly · Issue 111 — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **Published:** `13th September 2013`
  **NeKI brief:** Provides the RMStore source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [UIKitLegacyDetector](https://gist.github.com/steipete/6526860) — iOS Dev Weekly · Issue 111 — Source repository · Topics: Developer Tools · Personal Essays · UIKit
  **Published:** `13th September 2013`
  **NeKI brief:** Provides the UIKitLegacyDetector source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [FMPSD](https://github.com/ccgus/fmpsd) — iOS Dev Weekly · Issue 110 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `6th September 2013`
  **NeKI brief:** Provides the FMPSD source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [FXBlurView](https://github.com/nicklockwood/FXBlurView) — iOS Dev Weekly · Issue 109 — Source repository · Topics: Developer Tools
  **Published:** `30th August 2013`
  **NeKI brief:** Provides the FXBlurView source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [AGAsyncTestHelper](https://github.com/hfossli/AGAsyncTestHelper) — iOS Dev Weekly · Issue 109 — Source repository · Topics: Concurrency · Developer Tools · Testing
  **Published:** `30th August 2013`
  **NeKI brief:** Provides the AGAsyncTestHelper source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [IGHTMLQuery](https://github.com/siuying/IGHTMLQuery) — iOS Dev Weekly · Issue 108 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Testing
  **Published:** `23rd August 2013`
  **NeKI brief:** Provides the IGHTMLQuery source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [WYPopoverController](https://github.com/nicolaschengdev/WYPopoverController) — iOS Dev Weekly · Issue 108 — Source repository · Topics: Developer Tools
  **Published:** `23rd August 2013`
  **NeKI brief:** Provides the WYPopoverController source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [ReactiveCocoa 2](https://github.com/ReactiveCocoa/ReactiveCocoa/blob/master/CHANGELOG.md) — iOS Dev Weekly · Issue 108 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `23rd August 2013`
  **NeKI brief:** Provides the ReactiveCocoa 2 source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [iOS Blur](https://github.com/JagCesar/iOS-blur) — iOS Dev Weekly · Issue 105 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · UIKit
  **Published:** `2nd August 2013`
  **NeKI brief:** Provides the iOS Blur source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [ParcelKit](https://github.com/overcommitted/ParcelKit) — iOS Dev Weekly · Issue 104 — Source repository · Topics: Core Data · Objective-C & Cocoa · Testing
  **Published:** `26th July 2013`
  **NeKI brief:** Provides the ParcelKit source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Masonry](https://github.com/cloudkite/Masonry) — iOS Dev Weekly · Issue 104 — Source repository · Topics: Developer Tools · Persistence & Synchronisation
  **Published:** `26th July 2013`
  **NeKI brief:** Provides the Masonry source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Objective-C Generics](https://github.com/tomersh/Objective-C-Generics) — iOS Dev Weekly · Issue 103 — Source repository · Topics: Developer Tools · Macros & Metaprogramming · Objective-C & Cocoa
  **Published:** `19th July 2013`
  **NeKI brief:** Provides the Objective-C Generics source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [WWDC Sample Code Downloader](https://github.com/jfahrenkrug/WWDC-Downloader) — iOS Dev Weekly · Issue 100 — Source repository · Topics: Apple Platform Ecosystem · Developer Tools · Graphics, Media & Games
  **Published:** `28th June 2013`
  **NeKI brief:** Provides the WWDC Sample Code Downloader source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [iOS Artwork Extractor](https://github.com/0xced/iOS-Artwork-Extractor) — iOS Dev Weekly · Issue 99 — Source repository · Topics: Concurrency · Developer Tools · Xcode
  **Published:** `21st June 2013`
  **NeKI brief:** Provides the iOS Artwork Extractor source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Sound Debugging](http://qnoid.com/2013/06/08/Sound-Debugging.html) — iOS Dev Weekly · Issue 98 — Article · Topics: Cross-Platform & Web · Developer Tools · Xcode
  **Published:** `14th June 2013`
  **NeKI brief:** Explains Sound Debugging with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Subliminal](https://github.com/inkling/Subliminal) — iOS Dev Weekly · Issue 98 — Source repository · Topics: Cross-Platform & Web · Objective-C & Cocoa · Testing
  **Published:** `14th June 2013`
  **NeKI brief:** Provides the Subliminal source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [UIKit Main Thread Guard](https://gist.github.com/steipete/5664345) — iOS Dev Weekly · Issue 96 — Source repository · Topics: Developer Tools · UIKit
  **Published:** `31st May 2013`
  **NeKI brief:** Provides the UIKit Main Thread Guard source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [FlatUIKit](https://github.com/Grouper/FlatUIKit) — iOS Dev Weekly · Issue 95 — Source repository · Topics: Developer Tools · UIKit
  **Published:** `24th May 2013`
  **NeKI brief:** Provides the FlatUIKit source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [UbiquityStoreManager](http://lhunath.github.io/UbiquityStoreManager) — iOS Dev Weekly · Issue 94 — Article · Topics: Core Data · Developer Tools · Persistence & Synchronisation
  **Published:** `17th May 2013`
  **NeKI brief:** Explains UbiquityStoreManager with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [PHFComposeBarView](https://github.com/fphilipe/PHFComposeBarView) — iOS Dev Weekly · Issue 93 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `10th May 2013`
  **NeKI brief:** Provides the PHFComposeBarView source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [ArgumentParser](https://github.com/NSError/ArgumentParser) — iOS Dev Weekly · Issue 93 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `10th May 2013`
  **NeKI brief:** Provides the ArgumentParser source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [UIView-EasingFunctions](https://github.com/zrxq/UIView-EasingFunctions) — iOS Dev Weekly · Issue 92 — Source repository · Topics: Developer Tools
  **Published:** `3rd May 2013`
  **NeKI brief:** Provides the UIView-EasingFunctions source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Alcatraz](http://mneorr.github.io/Alcatraz) — iOS Dev Weekly · Issue 91 — Article · Topics: Developer Tools · Xcode
  **Published:** `26th April 2013`
  **NeKI brief:** Explains Alcatraz with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Logging with Xcode Breakpoints](http://furbo.org/2013/04/11/logging-with-xcode-breakpoints) — iOS Dev Weekly · Issue 89 — Article · Topics: Developer Tools · Xcode
  **Published:** `12th April 2013`
  **NeKI brief:** Explains Logging with Xcode Breakpoints with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [AGi18n](https://github.com/angelolloqui/AGi18n) — iOS Dev Weekly · Issue 87 — Source repository · Topics: Developer Tools · Localization
  **Published:** `29th March 2013`
  **NeKI brief:** Provides the AGi18n source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [ADNKit](https://github.com/joeldev/ADNKit) — iOS Dev Weekly · Issue 86 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `22nd March 2013`
  **NeKI brief:** Provides the ADNKit source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [JSErrorStackTrace](https://github.com/JaviSoto/JSErrorStackTrace) — iOS Dev Weekly · Issue 86 — Source repository · Topics: Developer Tools
  **Published:** `22nd March 2013`
  **NeKI brief:** Provides the JSErrorStackTrace source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [AGGeometryKit](https://github.com/hfossli/AGGeometryKit) — iOS Dev Weekly · Issue 85 — Source repository · Topics: Developer Tools
  **Published:** `15th March 2013`
  **NeKI brief:** Provides the AGGeometryKit source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [UISS](https://github.com/robertwijas/UISS) — iOS Dev Weekly · Issue 84 — Source repository · Topics: Developer Community & Business · Developer Tools · UIKit
  **Published:** `8th March 2013`
  **NeKI brief:** Provides the UISS source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Xamarin Studio](http://blog.xamarin.com/announcing-xamarin-2.0) — iOS Dev Weekly · Issue 82 — Article · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `22nd February 2013`
  **NeKI brief:** Explains Xamarin Studio with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [RXCollections](https://github.com/robrix/RXCollections) — iOS Dev Weekly · Issue 82 — Source repository · Topics: Developer Tools
  **Published:** `22nd February 2013`
  **NeKI brief:** Provides the RXCollections source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [SCStringsUtility](https://github.com/stefanceriu/SCStringsUtility) — iOS Dev Weekly · Issue 80 — Source repository · Topics: Developer Tools · Xcode
  **Published:** `8th February 2013`
  **NeKI brief:** Provides the SCStringsUtility source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Hookshot](https://github.com/Cue/hookshot) — iOS Dev Weekly · Issue 78 — Source repository · Topics: Developer Tools · Performance
  **Published:** `25th January 2013`
  **NeKI brief:** Provides the Hookshot source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Halving size of iPad app with ImageOptim+ImageAlpha](http://imageoptim.com/tweetbot.html) — iOS Dev Weekly · Issue 76 — Article · Topics: Cross-Platform & Web · Developer Tools · Xcode
  **Published:** `11th January 2013`
  **NeKI brief:** Explains Halving size of iPad app with ImageOptim+ImageAlpha with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [GIKPopoverBackgroundView](https://github.com/GiK/GIKPopoverBackgroundView) — iOS Dev Weekly · Issue 76 — Source repository · Topics: Developer Tools
  **Published:** `11th January 2013`
  **NeKI brief:** Provides the GIKPopoverBackgroundView source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [BCGenieEffect](https://github.com/Ciechan/BCGenieEffect) — iOS Dev Weekly · Issue 75 — Source repository · Topics: Developer Tools
  **Published:** `4th January 2013`
  **NeKI brief:** Provides the BCGenieEffect source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [DLIntrospection](https://github.com/garnett/DLIntrospection) — iOS Dev Weekly · Issue 75 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `4th January 2013`
  **NeKI brief:** Provides the DLIntrospection source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Slash](https://github.com/chrisdevereux/Slash) — iOS Dev Weekly · Issue 73 — Source repository · Topics: Developer Tools · Product Design
  **Published:** `21st December 2012`
  **NeKI brief:** Provides the Slash source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [GVUserDefaults](https://github.com/gangverk/GVUserDefaults) — iOS Dev Weekly · Issue 73 — Source repository · Topics: Developer Tools
  **Published:** `21st December 2012`
  **NeKI brief:** Provides the GVUserDefaults source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [STTweetLabel](https://github.com/SebastienThiebaud/STTweetLabel) — iOS Dev Weekly · Issue 73 — Source repository · Topics: Developer Tools
  **Published:** `21st December 2012`
  **NeKI brief:** Provides the STTweetLabel source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [jsbindings](https://github.com/zynga/jsbindings) — iOS Dev Weekly · Issue 72 — Source repository · Topics: Developer Tools · Observation & State Management
  **Published:** `14th December 2012`
  **NeKI brief:** Provides the jsbindings source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [NUI](https://github.com/tombenner/nui) — iOS Dev Weekly · Issue 71 — Source repository · Topics: Accessibility · Developer Tools
  **Published:** `7th December 2012`
  **NeKI brief:** Provides the NUI source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [THObserversAndBinders](https://github.com/th-in-gs/THObserversAndBinders) — iOS Dev Weekly · Issue 71 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Observation & State Management
  **Published:** `7th December 2012`
  **NeKI brief:** Provides the THObserversAndBinders source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [RRAutoLayout](https://github.com/RolandasRazma/RRAutoLayout) — iOS Dev Weekly · Issue 71 — Source repository · Topics: Developer Tools
  **Published:** `7th December 2012`
  **NeKI brief:** Provides the RRAutoLayout source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Flags: very useful when debugging with Instruments](http://invasivecode.tumblr.com/post/18677362251/flags-very-useful-when-debugging-with) — iOS Dev Weekly · Issue 70 — Article · Topics: Developer Tools · Performance
  **Published:** `30th November 2012`
  **NeKI brief:** Explains Flags very useful when debugging with Instruments with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [UICollectionViewWaterfallLayout](https://github.com/chiahsien/UICollectionViewWaterfallLayout) — iOS Dev Weekly · Issue 69 — Source repository · Topics: Developer Tools
  **Published:** `23rd November 2012`
  **NeKI brief:** Provides the UICollectionViewWaterfallLayout source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [RNTextStatistics](https://github.com/rnystrom/RNTextStatistics) — iOS Dev Weekly · Issue 69 — Source repository · Topics: Developer Tools
  **Published:** `23rd November 2012`
  **NeKI brief:** Provides the RNTextStatistics source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [MSCachedAsyncViewDrawing](https://github.com/mindsnacks/MSCachedAsyncViewDrawing) — iOS Dev Weekly · Issue 68 — Source repository · Topics: Concurrency · Developer Tools · Graphics, Media & Games
  **Published:** `16th November 2012`
  **NeKI brief:** Provides the MSCachedAsyncViewDrawing source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [TouchDB-iOS](https://github.com/couchbaselabs/TouchDB-iOS) — iOS Dev Weekly · Issue 67 — Source repository · Topics: Developer Tools · Persistence & Synchronisation
  **Published:** `9th November 2012`
  **NeKI brief:** Provides the TouchDB-iOS source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Nocilla](https://github.com/luisobo/Nocilla) — iOS Dev Weekly · Issue 67 — Source repository · Topics: Developer Tools · Networking · Testing
  **Published:** `9th November 2012`
  **NeKI brief:** Provides the Nocilla source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Zipzap](https://github.com/pixelglow/zipzap) — iOS Dev Weekly · Issue 66 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2nd November 2012`
  **NeKI brief:** Provides the Zipzap source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Chaos Testing With UI AutoMonkey](http://cocoamanifest.net/articles/2012/11/chaos-testing-with-ui-automonkey.html) — iOS Dev Weekly · Issue 66 — Article · Topics: Cross-Platform & Web · Developer Tools · Testing
  **Published:** `2nd November 2012`
  **NeKI brief:** Explains Chaos Testing With UI AutoMonkey with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Mantle: a Model Framework for Objective-C](https://github.com/blog/1299-mantle-a-model-framework-for-objective-c) — iOS Dev Weekly · Issue 65 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `26th October 2012`
  **NeKI brief:** Provides the Mantle a Model Framework for Objective-C source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [FTAssetRenderer](https://github.com/Fingertips/FTAssetRenderer) — iOS Dev Weekly · Issue 64 — Source repository · Topics: Developer Tools
  **Published:** `19th October 2012`
  **NeKI brief:** Provides the FTAssetRenderer source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [CTObjectiveCRuntimeAdditions](https://github.com/ebf/CTObjectiveCRuntimeAdditions) — iOS Dev Weekly · Issue 63 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `12th October 2012`
  **NeKI brief:** Provides the CTObjectiveCRuntimeAdditions source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [AGImageChecker](https://github.com/angelolloqui/AGImageChecker) — iOS Dev Weekly · Issue 62 — Source repository · Topics: Developer Tools · Performance · Personal Essays
  **Published:** `5th October 2012`
  **NeKI brief:** Provides the AGImageChecker source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Shenzhen](https://github.com/mattt/shenzhen) — iOS Dev Weekly · Issue 62 — Source repository · Topics: Developer Tools · Testing
  **Published:** `5th October 2012`
  **NeKI brief:** Provides the Shenzhen source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [SKBounceAnimation](https://github.com/khanlou/SKBounceAnimation) — iOS Dev Weekly · Issue 61 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `28th September 2012`
  **NeKI brief:** Provides the SKBounceAnimation source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [PSTCollectionView](https://github.com/steipete/PSTCollectionView) — iOS Dev Weekly · Issue 60 — Source repository · Topics: Developer Tools
  **Published:** `21st September 2012`
  **NeKI brief:** Provides the PSTCollectionView source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [MiniXcode](https://github.com/Daij-Djan/MiniXcode) — iOS Dev Weekly · Issue 59 — Source repository · Topics: Developer Tools · Xcode
  **Published:** `14th September 2012`
  **NeKI brief:** Provides the MiniXcode source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [ColorSense for Xcode](https://github.com/omz/ColorSense-for-Xcode) — iOS Dev Weekly · Issue 59 — Source repository · Topics: Developer Tools · Xcode
  **Published:** `14th September 2012`
  **NeKI brief:** Provides the ColorSense for Xcode source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Swizzled UIImage imageNamed for iPhone 5](https://gist.github.com/3711077) — iOS Dev Weekly · Issue 59 — Source repository · Topics: Developer Tools
  **Published:** `14th September 2012`
  **NeKI brief:** Provides the Swizzled UIImage imageNamed for iPhone 5 source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [SkyLab](https://github.com/mattt/SkyLab) — iOS Dev Weekly · Issue 58 — Source repository · Topics: Developer Tools · Testing
  **Published:** `7th September 2012`
  **NeKI brief:** Provides the SkyLab source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [The White House App released as Open Sorce](https://github.com/WhiteHouse/wh-app-ios) — iOS Dev Weekly · Issue 58 — Source repository · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `7th September 2012`
  **NeKI brief:** Provides the The White House App released as Open Sorce source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [PonyDebugger: Remote Debugging Tools for Native iOS Apps](http://corner.squareup.com/2012/08/ponydebugger-remote-debugging.html) — iOS Dev Weekly · Issue 57 — Article · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `31st August 2012`
  **NeKI brief:** Explains PonyDebugger Remote Debugging Tools for Native iOS Apps with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [Experimentation with build numbering](http://paul-samuels.com/blog/2012/08/25/experimentation-with-build-numbering) — iOS Dev Weekly · Issue 57 — Article · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `31st August 2012`
  **NeKI brief:** Explains Experimentation with build numbering with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Fourgy](https://github.com/danielctull/Fourgy) — iOS Dev Weekly · Issue 54 — Source repository · Topics: Developer Tools
  **Published:** `10th August 2012`
  **NeKI brief:** Provides the Fourgy source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [FilterKit](https://github.com/eklipse2k8/FilterKit) — iOS Dev Weekly · Issue 53 — Source repository · Topics: Developer Tools
  **Published:** `3rd August 2012`
  **NeKI brief:** Provides the FilterKit source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [EasyTweet](https://github.com/amazingsyco/EasyTweet) — iOS Dev Weekly · Issue 51 — Source repository · Topics: Developer Tools
  **Published:** `20th July 2012`
  **NeKI brief:** Provides the EasyTweet source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Debugging Core Data Objects](http://furbo.org/2012/06/28/debugging-core-data-objects) — iOS Dev Weekly · Issue 48 — Article · Topics: Core Data · Developer Tools · Persistence & Synchronisation
  **Published:** `29th June 2012`
  **NeKI brief:** Explains Debugging Core Data Objects with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [DAAnisotropicImage](https://github.com/danielamitay/DAAnisotropicImage) — iOS Dev Weekly · Issue 48 — Source repository · Topics: Developer Tools
  **Published:** `29th June 2012`
  **NeKI brief:** Provides the DAAnisotropicImage source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [iOS Hierarchy Viewer](https://github.com/glock45/iOS-Hierarchy-Viewer) — iOS Dev Weekly · Issue 47 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `22nd June 2012`
  **NeKI brief:** Provides the iOS Hierarchy Viewer source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Circle](https://github.com/mikeash/Circle) — iOS Dev Weekly · Issue 46 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `15th June 2012`
  **NeKI brief:** Provides the Circle source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [UIImage imageNamed: from anywhere](https://github.com/appsandwich/UIImage-ASImage) — iOS Dev Weekly · Issue 44 — Source repository · Topics: Developer Tools
  **Published:** `1st June 2012`
  **NeKI brief:** Provides the UIImage imageNamed from anywhere source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [SSPullToRefresh](https://github.com/samsoffes/sspulltorefresh) — iOS Dev Weekly · Issue 43 — Source repository · Topics: Developer Tools
  **Published:** `25th May 2012`
  **NeKI brief:** Provides the SSPullToRefresh source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [ReactiveCocoa for a better world](https://github.com/blog/1107-reactivecocoa-for-a-better-world) — iOS Dev Weekly · Issue 41 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `11th May 2012`
  **NeKI brief:** Provides the ReactiveCocoa for a better world source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [SVPullToRefresh](https://github.com/samvermette/SVPullToRefresh) — iOS Dev Weekly · Issue 39 — Source repository · Topics: Developer Tools
  **Published:** `27th April 2012`
  **NeKI brief:** Provides the SVPullToRefresh source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Lockbox](https://github.com/granoff/Lockbox) — iOS Dev Weekly · Issue 39 — Source repository · Topics: Developer Tools · Persistence & Synchronisation · Security & Privacy
  **Published:** `27th April 2012`
  **NeKI brief:** Provides the Lockbox source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Tipi: Tiny Templating Engine](https://github.com/hiddenmemory/Tipi) — iOS Dev Weekly · Issue 37 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `13th April 2012`
  **NeKI brief:** Provides the Tipi Tiny Templating Engine source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Omni Frameworks](https://github.com/omnigroup/OmniGroup) — iOS Dev Weekly · Issue 37 — Source repository · Topics: Developer Tools
  **Published:** `13th April 2012`
  **NeKI brief:** Provides the Omni Frameworks source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [UIKit Artwork Extractor](https://github.com/0xced/UIKit-Artwork-Extractor) — iOS Dev Weekly · Issue 35 — Source repository · Topics: Concurrency · Developer Tools · UIKit
  **Published:** `30th March 2012`
  **NeKI brief:** Provides the UIKit Artwork Extractor source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [SMShadowedLayer](https://github.com/Spaceman-Labs/ShadowedLayer/blob/master/fiatlux/SMShadowedLayer.m) — iOS Dev Weekly · Issue 34 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Product Design
  **Published:** `23rd March 2012`
  **NeKI brief:** Provides the SMShadowedLayer source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Touchpose](https://github.com/toddreed/Touchpose) — iOS Dev Weekly · Issue 32 — Source repository · Topics: Combine & Reactive Programming · Developer Tools
  **Published:** `9th March 2012`
  **NeKI brief:** Provides the Touchpose source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Git branch management with Xcode](http://useyourloaf.com/blog/2012/2/29/git-branch-management-with-xcode.html) — iOS Dev Weekly · Issue 31 — Article · Topics: Developer Career & Practice · Developer Tools · Xcode
  **Published:** `2nd March 2012`
  **NeKI brief:** Explains Git branch management with Xcode with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [NYXImagesKit](https://github.com/Nyx0uf/NYXImagesKit) — iOS Dev Weekly · Issue 31 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2nd March 2012`
  **NeKI brief:** Provides the NYXImagesKit source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [GPUImage](https://github.com/BradLarson/GPUImage) — iOS Dev Weekly · Issue 29 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `17th February 2012`
  **NeKI brief:** Provides the GPUImage source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [UIImage Sprite Additions](https://github.com/r3econ/UIImage-Sprite-Additions) — iOS Dev Weekly · Issue 28 — Source repository · Topics: Developer Tools
  **Published:** `10th February 2012`
  **NeKI brief:** Provides the UIImage Sprite Additions source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [xcodebuild-rb](https://github.com/lukeredpath/xcodebuild-rb) — iOS Dev Weekly · Issue 27 — Source repository · Topics: Developer Tools · Xcode
  **Published:** `3rd February 2012`
  **NeKI brief:** Provides the xcodebuild-rb source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [FTCoreText](https://github.com/FuerteInternational/FTCoreText) — iOS Dev Weekly · Issue 27 — Source repository · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `3rd February 2012`
  **NeKI brief:** Provides the FTCoreText source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Zangetsu](https://github.com/Machx/Zangetsu) — iOS Dev Weekly · Issue 25 — Source repository · Topics: Developer Tools
  **Published:** `20th January 2012`
  **NeKI brief:** Provides the Zangetsu source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Revisiting git tags and building](http://www.cimgf.com/2011/02/20/revisiting-git-tags-and-building) — iOS Dev Weekly · Issue 23 — Article · Topics: Developer Tools
  **Published:** `6th January 2012`
  **NeKI brief:** Explains Revisiting git tags and building with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [RSOAuthEngine](https://github.com/rsieiro/RSOAuthEngine) — iOS Dev Weekly · Issue 20 — Source repository · Topics: Developer Tools
  **Published:** `16th December 2011`
  **NeKI brief:** Provides the RSOAuthEngine source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Debuggery](https://github.com/rustle/Debuggery) — iOS Dev Weekly · Issue 19 — Source repository · Topics: Developer Tools
  **Published:** `9th December 2011`
  **NeKI brief:** Provides the Debuggery source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [GMGridView](https://github.com/gmoledina/GMGridView) — iOS Dev Weekly · Issue 18 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2nd December 2011`
  **NeKI brief:** Provides the GMGridView source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Uncrustify Automator Services](https://github.com/tonyarnold/Xcode-4-Uncrustify-Automator-Services) — iOS Dev Weekly · Issue 17 — Source repository · Topics: Developer Tools · Xcode
  **Published:** `25th November 2011`
  **NeKI brief:** Provides the Uncrustify Automator Services source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [PSPushPopPressView](https://github.com/steipete/PSPushPopPressView) — iOS Dev Weekly · Issue 16 — Source repository · Topics: Developer Tools
  **Published:** `18th November 2011`
  **NeKI brief:** Provides the PSPushPopPressView source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [PSStackedView](https://github.com/steipete/PSStackedView) — iOS Dev Weekly · Issue 14 — Source repository · Topics: Developer Tools
  **Published:** `4th November 2011`
  **NeKI brief:** Provides the PSStackedView source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Xcode 4 Debugging Crash-Course](http://www.learn-cocos2d.com/2011/10/xcode-4-debugging-crashcourse) — iOS Dev Weekly · Issue 10 — Tutorial · Topics: Developer Community & Business · Developer Tools · Xcode
  **Published:** `7th October 2011`
  **NeKI brief:** Explains Xcode 4 Debugging Crash-Course with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [HGPageScrollView](https://github.com/100grams/HGPageScrollView) — iOS Dev Weekly · Issue 9 — Source repository · Topics: Developer Tools
  **Published:** `30th September 2011`
  **NeKI brief:** Provides the HGPageScrollView source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [DCIntrospect](https://github.com/domesticcatsoftware/DCIntrospect) — iOS Dev Weekly · Issue 7 — Source repository · Topics: Developer Tools
  **Published:** `16th September 2011`
  **NeKI brief:** Provides the DCIntrospect source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Xcode 4 Colour Themes](https://github.com/jbrennan/xcode4themes) — iOS Dev Weekly · Issue 5 — Source repository · Topics: Developer Tools · Xcode
  **Published:** `2nd September 2011`
  **NeKI brief:** Provides the Xcode 4 Colour Themes source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [AFNetworking](https://github.com/gowalla/AFNetworking) — iOS Dev Weekly · Issue 4 — Source repository · Topics: Developer Tools · Networking
  **Published:** `26th August 2011`
  **NeKI brief:** Provides the AFNetworking source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [UIDevice+UniqueIdentifier](https://github.com/gekitz/UIDevice-with-UniqueIdentifier-for-iOS-5) — iOS Dev Weekly · Issue 4 — Source repository · Topics: Developer Community & Business · Developer Tools
  **Published:** `26th August 2011`
  **NeKI brief:** Provides the UIDevice+UniqueIdentifier source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [QuickDialog](https://github.com/escoz/QuickDialog) — iOS Dev Weekly · Issue 3 — Source repository · Topics: Developer Tools
  **Published:** `19th August 2011`
  **NeKI brief:** Provides the QuickDialog source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Make Keychain as easy to use as NSUserDefaults](https://github.com/carlbrown/PDKeychainBindingsController) — iOS Dev Weekly · Issue 2 — Source repository · Topics: Developer Tools · Persistence & Synchronisation · Security & Privacy
  **Published:** `12th August 2011`
  **NeKI brief:** Provides the Make Keychain as easy to use as NSUserDefaults source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Pickle Rick Extension](https://github.com/galz10/pickle-rick-extension) — Not only Swift · Issue 96 — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the public source repository for Pickle Rick Extension. Inspect its implementation, examples, and issue history to evaluate integration boundaries and maintenance trade-offs before depending on it in an Apple-platform project.
- [Greenlight: Pre-submission compliance scanner for the Apple App Store](https://github.com/RevylAI/greenlight) — Not only Swift · Issue 96 — Source repository · Topics: AI Development · App Distribution & Store Operations · Developer Tools
  **NeKI brief:** This source repository covers Apple App Store pre-submission compliance scanning. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [App Store Connect CLI Skills](https://github.com/rudrankriyam/app-store-connect-cli-skills) — Not only Swift · Issue 96 — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **NeKI brief:** This source repository covers skills for automating App Store Connect through the asc CLI. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Google Play Developer CLI](https://github.com/dl-alexandre/Google-Play-Developer-CLI) — Not only Swift · Issue 96 — Source repository · Topics: AI Development · App Distribution & Store Operations · Developer Tools
  **NeKI brief:** This source repository covers an AI-agent-friendly Google Play command-line workflow. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [flatMapLatest in swift-async-algorithms](https://github.com/apple/swift-async-algorithms/releases/tag/1.1.3) — Not only Swift · Issue 95 — Source repository · Topics: Concurrency · Swift · Testing
  **NeKI brief:** Explores flatMapLatest in swift-async-algorithms with concrete Swift concurrency examples. Follow it to reason about isolation, cancellation, and Sendable boundaries, then verify availability and diagnostics against current Swift documentation.
- [ScreenStateKit: Managing States for SwiftUI Screens](https://github.com/anthony1810/ScreenStateKit) — Not only Swift · Issue 95 — Source repository · Topics: Architecture · Swift · SwiftUI
  **NeKI brief:** Explains the state-ownership behavior behind ScreenStateKit: Managing States for SwiftUI Screens. Use it to distinguish initialization, bindings, and view identity so updates remain predictable across SwiftUI recomputation and navigation.
- [MCP is dead. Long live the CLI](https://ejholmes.github.io/2026/02/28/mcp-is-dead-long-live-the-cli.html) — Not only Swift · Issue 95 — Article · Topics: AI Development · Cross-Platform & Web · Developer Tools
  **NeKI brief:** This article covers the case for durable command-line interfaces over MCP-only tooling. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Perspective-Server: OpenAI-compatible API for Apple Foundation Models](https://github.com/Techopolis/Perspective-Server) — Not only Swift · Issue 95 — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **NeKI brief:** This source repository covers exposing Apple Foundation Models through an OpenAI-compatible local API. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Google Workspace CLI: One tool for everything](https://github.com/googleworkspace/cli) — Not only Swift · Issue 95 — Source repository · Topics: Developer Tools · Swift · Systems Programming
  **NeKI brief:** This source repository covers a unified Google Workspace command-line interface with agent skills. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Typst template](https://github.com/peterfriese/eightbyten) — Not only Swift · Issue 94 — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** This source repository covers a Tufte-style Typst book template. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Xcode’s responses weren’t compatible with the MCP protocol](https://github.com/google-gemini/gemini-cli/issues/18371) — Not only Swift · Issue 94 — Source repository · Topics: AI Development · Developer Tools · Xcode
  **NeKI brief:** Describes Xcode’s responses weren’t compatible with the MCP protocol, focusing on practical tool integration and workflow trade-offs. Use it to evaluate reproducibility, trust boundaries, and debugging steps before adopting the approach in an Xcode project.
- [fix on our end](https://github.com/google-gemini/gemini-cli/pull/18376) — Not only Swift · Issue 94 — Source repository · Topics: AI Development · Developer Tools · Xcode
  **NeKI brief:** Provides the public source repository for fix on our end. Inspect its implementation, examples, and issue history to evaluate integration boundaries and maintenance trade-offs before depending on it in an Apple-platform project.
- [VecturaKit](https://github.com/rryam/VecturaKit) — Not only Swift · Issue 94 — Source repository · Topics: AI Development · Developer Tools · Graphics, Media & Games
  **NeKI brief:** Provides the public source repository for VecturaKit. Inspect its implementation, examples, and issue history to evaluate integration boundaries and maintenance trade-offs before depending on it in an Apple-platform project.
- [PiSwift](https://github.com/xibbon/PiSwift) — Not only Swift · Issue 94 — Source repository · Topics: Architecture · Objective-C & Cocoa · Swift
  **NeKI brief:** This source repository covers the PiSwift project and its Swift integration surface. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Beautiful Mermaid Swift](https://github.com/lukilabs/beautiful-mermaid-swift) — Not only Swift · Issue 94 — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** This source repository covers rendering Mermaid diagrams natively in Swift. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Apple Docs MCP](https://github.com/kimsungwhee/apple-docs-mcp) — Not only Swift · Issue 94 — Source repository · Topics: AI Development · Developer Tools · Swift
  **NeKI brief:** This source repository covers an MCP server for searching Apple developer documentation. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [MicroGPT](https://gist.github.com/karpathy/8627fe009c40f57531cb18360106ce95) — Not only Swift · Issue 94 — Source repository · Topics: Developer Tools
  **NeKI brief:** This source repository covers a minimal GPT implementation for understanding language-model mechanics. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Play](https://youtube.com/watch?v=bCz3Pc041ME) — Not only Swift · Issue 93 — Video · Topics: Developer Tools
  **NeKI brief:** Links to a public video about Play. Use the talk for practitioner context and demonstrations, then verify platform behavior, API availability, and recommended production practices in current primary documentation.
- [agent-device](https://github.com/callstackincubator/agent-device) — Not only Swift · Issue 93 — Source repository · Topics: AI Development · Developer Tools · Xcode
  **NeKI brief:** This source repository covers controlling iOS and Android devices from AI agents. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [DebugSwift: A Toolkit to Make Debugging iOS Applications Easier](https://github.com/DebugSwift/DebugSwift) — Not only Swift · Issue 92 — Source repository · Topics: AI Development · Developer Tools · Swift
  **NeKI brief:** This source repository covers debugging iOS applications with a dedicated Swift toolkit. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [collection of tools and utilities for Swift and SwiftUI development](https://github.com/hmlongco/Runes) — Not only Swift · Issue 92 — Source repository · Topics: Combine & Reactive Programming · Concurrency · Swift
  **NeKI brief:** This source repository covers reusable Swift and SwiftUI extensions and modifiers. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [MCP CLI + Skill](https://github.com/philschmid/mcp-cli) — Not only Swift · Issue 92 — Source repository · Topics: AI Development · Developer Tools · Product Design
  **NeKI brief:** This source repository covers a lightweight CLI and skill for interacting with MCP servers. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [The Humbling Math of Health AI: Why ChatGPT Can’t Grade Your Heart Yet](https://be-curious-not-judgmental.com/2026/01/26/the-humbling-math-of-health-ai-why-chatgpt-cant-grade-your-heart-yet) — Not only Swift · Issue 92 — Article · Topics: AI Development · Developer Tools
  **NeKI brief:** This article covers why health-AI answers require statistical humility and evidence. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [gt](https://github.com/melonamin/gt) — Not only Swift · Issue 92 — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** This source repository covers managing Git worktrees from a macOS menu bar. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Trees: Effortless Git worktrees in your menu bar](https://github.com/afterxleep/trees) — Not only Swift · Issue 91 — Source repository · Topics: AI Development · Developer Tools · macOS & AppKit
  **NeKI brief:** This source repository covers macOS menu-bar management for Git worktrees. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [last week’s livestream](https://www.youtube.com/watch?v=Z-KB7gOnE_E) — Not only Swift · Issue 90 — Video · Topics: AI Development · Developer Tools · Swift
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Finally understand Swift concurrency](https://fuckingapproachableswiftconcurrency.com/en) — Not only Swift · Issue 89 — Article · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** This article covers Swift concurrency through an approachable learning guide. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [SKILL.md](https://github.com/pepicrft/fuckingapproachableswiftconcurrency/blob/main/src/SKILL.md) — Not only Swift · Issue 89 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** This source repository covers the accompanying AGENTS skill source for the concurrency guide. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [English version for humans](https://github.com/pepicrft/fuckingapproachableswiftconcurrency/blob/main/src/en/index.md) — Not only Swift · Issue 89 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** This source repository covers the human-readable source of the concurrency guide. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Flexible rich text rendering in SwiftUI](https://github.com/gonzalezreal/textual) — Not only Swift · Issue 89 — Source repository · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** This source repository covers rich attributed-text rendering in SwiftUI. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [swift-markdown-ui](https://github.com/gonzalezreal/swift-markdown-ui) — Not only Swift · Issue 89 — Source repository · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** This source repository covers the maintenance status and migration path from Swift Markdown UI. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Why you should stop stashing and use worktrees](https://www.marcohaber.dev/blog/git-worktrees) — Not only Swift · Issue 89 — Article · Topics: Developer Tools · Objective-C & Cocoa · Xcode
  **NeKI brief:** Discusses Why you should stop stashing and use worktrees in a public developer resource. Use it to compare the author's concrete workflow and trade-offs with your project constraints, and verify any platform-specific claims against current primary documentation.
- [bjesus/pipet: Swiss-army tool for scraping and extracting data from online assets, made for hackers](https://github.com/bjesus/pipet) — Not only Swift · Issue 88 — Source repository · Topics: AI Development · Developer Tools
  **NeKI brief:** This source repository covers a command-line scraper for extracting online assets. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [this branch on the repository](https://github.com/firebase/quickstart-ios/tree/peterfriese/firebase-ai-quickstart-refresh/firebaseai) — Not only Swift · Issue 86 — Source repository · Topics: AI Development · Developer Tools
  **NeKI brief:** This source repository covers Firebase AI examples for an iOS quickstart branch. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [ActionMenu](https://github.com/peterfriese/ActionMenu) — Not only Swift · Issue 86 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** This source repository covers a reusable SwiftUI action menu. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [this repository](https://github.com/FirebaseExtended/firebase-video-samples/tree/main/firebase-ai-friendly-meals/apple) — Not only Swift · Issue 85 — Source repository · Topics: AI Development · Developer Community & Business · Developer Tools
  **NeKI brief:** Contains the Apple client sample for Firebase AI Friendly Meals, showing practical integration boundaries around Firebase services and SwiftUI. Inspect it for a runnable reference, then check current SDK setup and security guidance.
- [Agent Rules: Reusable Rules for AI Coding Assistants](https://github.com/steipete/agent-rules) — Not only Swift · Issue 85 — Source repository · Topics: AI Development · Developer Tools
  **NeKI brief:** This source repository covers reusable instruction rules for AI coding assistants. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Foundation Models Playgrounds: Comprehensive Examples for Apple's AI Framework](https://github.com/IvanCampos/Foundation-Models-Playgrounds) — Not only Swift · Issue 85 — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **NeKI brief:** This source repository covers Foundation Models Framework examples for Apple-platform development. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Have your cake and eat it too with SwiftUI-Backports](https://github.com/superwall/iOS-Backports) — Not only Swift · Issue 84 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** This source repository covers using current SwiftUI modifiers while supporting older iOS releases. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [AGDebugKit](https://github.com/OpenSwiftUIProject/AGDebugKit) — Not only Swift · Issue 84 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** This source repository covers AGDebugKit and diagnostics for OpenSwiftUI-based development. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Olleh: Ollama-compatible CLI for Apple's Foundation Models](https://github.com/loopwork/olleh) — Not only Swift · Issue 83 — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **NeKI brief:** This source repository covers an Ollama-compatible command-line interface for Apple Foundation Models. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [An OpenAI-compatible server for Apple's Foundation Models](https://github.com/gety-ai/apple-on-device-openai) — Not only Swift · Issue 83 — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **NeKI brief:** This source repository covers serving Apple on-device models through an OpenAI-compatible API. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [SFSymbolKit: Type-safe SF Symbols for SwiftUI](https://github.com/Sedlacek-Solutions/SFSymbolKit) — Not only Swift · Issue 80 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** This source repository covers type-safe SF Symbols as a SwiftUI library. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [best practices document document](https://github.com/Sedlacek-Solutions/SFSymbolKit/blob/main/BEST_PRACTICES.md) — Not only Swift · Issue 80 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** This source repository covers best practices for using type-safe SF Symbols in SwiftUI. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [CodeEditorView: A SwiftUI Code Editor for iOS, visionOS, and macOS](https://github.com/mchakravarty/CodeEditorView) — Not only Swift · Issue 79 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Presents a concrete implementation of CodeEditorView: A SwiftUI Code Editor for iOS, visionOS, and macOS. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.
- [Introducing Swiftly 1.0](https://www.swift.org/blog/introducing-swiftly_10) — Not only Swift · Issue 78 — Article · Topics: Cross-Platform & Web · Developer Tools · Swift
  **NeKI brief:** This technical resource covers Swiftly 1.0 as a Swift toolchain manager. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [official MCP Swift SDK](https://github.com/modelcontextprotocol/swift-sdk) — Not only Swift · Issue 78 — Source repository · Topics: AI Development · Developer Tools · Swift
  **NeKI brief:** Describes official MCP Swift SDK, focusing on practical tool integration and workflow trade-offs. Use it to evaluate reproducibility, trust boundaries, and debugging steps before adopting the approach in an Xcode project.
- [Resolver](https://github.com/hmlongco/Resolver) — Not only Swift · Issue 77 — Source repository · Topics: Architecture · Swift · SwiftUI
  **NeKI brief:** This source repository covers Resolver's dependency-injection approach and its deprecated status. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [range of production apps](https://github.com/FlineDev/HandySwiftUI?tab=readme-ov-file) — Not only Swift · Issue 77 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** This source repository covers SwiftUI utilities that fill gaps in the framework. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Implementing Sign in with Apple in the watchOS Simulator](https://brightdigit.com/tutorials/signin-apple-watchos-simulator) — Not only Swift · Issue 76 — Tutorial · Topics: Developer Tools · Swift
  **NeKI brief:** This article covers Sign in with Apple inside the watchOS Simulator. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [RenderMeThis: SwiftUI Debugging Tool](https://github.com/Aeastr/RenderMeThis) — Not only Swift · Issue 76 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** This source repository covers visualizing SwiftUI rendering, layouts, and measurements with Loupe. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [profile your SwiftUI code is via Instruments](https://www.hackingwithswift.com/quick-start/swiftui/how-to-use-instruments-to-profile-your-swiftui-code-and-identify-slow-layouts) — Not only Swift · Issue 76 — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Presents a concrete implementation of profile your SwiftUI code is via Instruments. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.
- [Open Symbols: SF Symbols from Popular Icon Sets](https://github.com/buzap/open-symbols) — Not only Swift · Issue 76 — Source repository · Topics: Developer Tools · Performance · Swift
  **NeKI brief:** Provides the public source repository for Open Symbols: SF Symbols from Popular Icon Sets. Inspect its implementation, examples, and issue history to evaluate integration boundaries and maintenance trade-offs before depending on it in an Apple-platform project.
