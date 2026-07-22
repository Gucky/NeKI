# macOS & AppKit

Third-party reading leads collected from NeKI sources. The links may be useful perspectives, but are not vetted recommendations or authoritative API guidance. NeKI publishes routing metadata, not the linked articles' text.

**Scope:** macOS app lifecycle, menu-bar apps, Cocoa, and AppKit integration.

- Last collected: `2026-07-22T21:56:49Z`
- Indexed links shown: **187**

## Direct-source reading

- [How to Use NSTouchBar on macOS | Kodeco](https://www.kodeco.com/883-how-to-use-nstouchbar-on-macos) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Implements NSTouchBar controls for a macOS application. Useful for identifying how contextual commands are exposed, refreshed, and kept consistent with the main AppKit interface.
- [macOS NSTableView Tutorial | Kodeco](https://www.kodeco.com/830-macos-nstableview-tutorial) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Builds an NSTableView around column identifiers, data population, selection, double-click actions, and sorting. Useful for understanding the AppKit table contract when a macOS screen needs richer column-oriented interaction than a simple SwiftUI list.
- [macOS Development for Beginners: Part 2 | Kodeco](https://www.kodeco.com/730-macos-development-for-beginners-part-2) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Builds a macOS timer around a window controller, AppKit layout, menus, preferences, and bindings. Useful for seeing how a desktop app's visible controls and persistent settings are connected through native controller and window responsibilities.
- [macOS Development for Beginners: Part 3 | Kodeco](https://www.kodeco.com/729-macos-development-for-beginners-part-3) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Adds sandbox-aware file organization, MVC boundaries, buttons, menus, preferences, and sound to a macOS timer. Useful for tracing how a simple AppKit app grows beyond one view without mixing storage, settings, and interaction logic.
- [macOS View Controllers Tutorial | Kodeco](https://www.kodeco.com/704-macos-view-controllers-tutorial) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Explains AppKit view-controller responsibilities, window-controller boundaries, lifecycle, tabs, and detail screens. Useful when structuring a macOS interface so ownership of a window, its child views, and their state does not blur together.
- [FileManager Class Tutorial for macOS: Getting Started with the File System | Kodeco](https://www.kodeco.com/666-filemanager-class-tutorial-for-macos-getting-started-with-the-file-system) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This macOS FileManager tutorial covers locating, creating and traversing files and folders. It remains a practical reference for sandbox-aware tooling, where URL-based APIs and explicit error handling matter more than string path manipulation.
- [Windows and WindowController Tutorial for macOS | Kodeco](https://www.kodeco.com/613-windows-and-windowcontroller-tutorial-for-macos) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Builds macOS windows and window controllers around ownership and presentation responsibilities. Useful for debugging AppKit flows where document, window, and view controller lifecycles are easily conflated.
- [Porting Your iOS App to macOS | Kodeco](https://www.kodeco.com/571-porting-your-ios-app-to-macos) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Ports an iOS table-driven app to macOS by separating models, adapting UI, and supplying AppKit data-source and delegate behavior. Useful for identifying the practical work hidden behind shared logic when an iOS design becomes a desktop interface.
- [Catalyst Tutorial: Running iPad apps on macOS | Kodeco](https://www.kodeco.com/5037284-catalyst-tutorial-running-ipad-apps-on-macos) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Catalyst configuration shows how an iPad app can adopt Mac menus and contextual behavior while sharing most code. It is useful for finding platform-specific interaction seams instead of assuming a resized iPad UI is a finished Mac app.
- [Menus and Popovers in Menu Bar Apps for macOS | Kodeco](https://www.kodeco.com/450-menus-and-popovers-in-menu-bar-apps-for-macos) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Creates a menu-bar app with a status item, menu, popover, event monitor, and AppKit view controller. Useful when deciding how a background-oriented macOS utility should surface controls without a conventional dock-window application shell.
- [CocoaPods Tech Talk Video | Kodeco](https://www.kodeco.com/2549-cocoapods-tech-talk-video) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Explains practical CocoaPods usage and common dependency-management questions. Useful historical context for repositories that still use Pods and need to separate package integration from application code.
- [Charles Proxy Tutorial for iOS | Kodeco](https://www.kodeco.com/21931256-charles-proxy-tutorial-for-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The introductory Charles workflow configures an iOS device or simulator to inspect HTTP traffic. It is useful for validating API calls and caching, provided development interception remains isolated from production credentials.
- [NSOutlineView on macOS Tutorial | Kodeco](https://www.kodeco.com/1201-nsoutlineview-on-macos-tutorial) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Builds a hierarchical macOS browser with NSOutlineView data-source and delegate methods around a tree model. Useful when a desktop interface needs expandable parent-child content that cannot be represented as a flat table.
- [Core Graphics on macOS Tutorial | Kodeco](https://www.kodeco.com/1101-core-graphics-on-macos-tutorial) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** A macOS Core Graphics example renders charts directly into a view, clarifying the drawRect-style coordinate and context model. It is a useful reference for custom AppKit rendering when higher-level controls cannot express the required visualization.
- [Scanner Tutorial for macOS | Kodeco](https://www.kodeco.com/1039-scanner-tutorial-for-macos) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Builds a macOS scanning workflow around image capture and document handling. Useful for separating hardware acquisition, image processing, and user-facing file output.
- [Drag and Drop Tutorial for macOS | Kodeco](https://www.kodeco.com/1016-drag-and-drop-tutorial-for-macos) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This macOS walkthrough connects drag sources and drop destinations, showing how an app can accept files or model data through AppKit's drag-and-drop contract.
- [Add launch at login setting to a macOS app](https://nilcoalescing.com/blog/LaunchAtLoginSetting) — Nil Coalescing · article catalogue
  **Published:** `2025-03-21`
  **NeKI brief:** Demonstrates registering a macOS app as a login item with SMAppService. Use it to implement an explicit launch-at-login setting while keeping user control and system preferences aligned.
- [How to keep your macOS app's menu bar item running after quitting the app](https://www.polpiella.dev/keep-menu-bar-running-after-quitting-app) — Pol Piella · article catalogue
  **Published:** `2024-12-31T00:00:00.000Z`
  **NeKI brief:** Explains keeping a macOS menu-bar utility available after closing ordinary windows. Use it when separating an app's activation policy, status item, and termination behavior.
- [A menu bar only macOS app using AppKit](https://www.polpiella.dev/a-menu-bar-only-macos-app-using-appkit) — Pol Piella · article catalogue
  **Published:** `2022-10-26T00:00:00.000Z`
  **NeKI brief:** A menu-bar-only macOS app manages an NSStatusItem without a conventional main window. Use explicit lifecycle and activation choices, ensuring settings, quit behavior and accessibility remain discoverable to users.
- [mikeash.com: The How and Why of Cocoa Initializers](https://www.mikeash.com/pyblog/the-how-and-why-of-cocoa-initializers.html) — Mike Ash · article catalogue
  **NeKI brief:** Cocoa initialization separates allocation, designated initialization, convenience paths, and nib unarchiving, so overriding the wrong method can silently skip invariants. This explanation is a durable reference for debugging partially initialized Objective-C objects.
- [mikeash.com: Friday Q&A 2010-08-27: Defensive Programming in Cocoa](https://www.mikeash.com/pyblog/friday-qa-2010-08-27-defensive-programming-in-cocoa.html) — Mike Ash · article catalogue
  **NeKI brief:** Cocoa APIs expose failure through errors, exceptions, nil, and asynchronous state; normalize assumptions at boundaries, check documented preconditions, and preserve invariants before invoking framework behavior.
- [mikeash.com: Friday Q&A 2009-11-20: Probing Cocoa With PyObjC](https://www.mikeash.com/pyblog/friday-qa-2009-11-20-probing-cocoa-with-pyobjc.html) — Mike Ash · article catalogue
  **NeKI brief:** A dynamic bridge such as PyObjC can quickly inspect Cocoa classes, selectors, and runtime behavior; use exploratory scripts to form hypotheses, then verify production assumptions against documented APIs and tests.
- [mikeash.com: Friday Q&A 2009-11-13: Dangerous Cocoa Calls](https://www.mikeash.com/pyblog/friday-qa-2009-11-13-dangerous-cocoa-calls.html) — Mike Ash · article catalogue
  **NeKI brief:** APIs that launch processes, wait synchronously, or invoke callbacks can fail, block, or re-enter unexpectedly; establish error, cancellation, and thread-affinity handling before treating them as simple utility calls.

## Newsletter and related leads

- [Swift Scribe](https://github.com/FluidInference/swift-scribe) — iOS Dev Tools · iOS Dev Tools: MistKit, Swift Scribe, cmux — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `2026-07-16T16:45:11.086Z`
  **NeKI brief:** Swift Scribe combines local microphone transcription with on-device summarization on current Apple OS releases, without external dependencies. Useful for evaluating a privacy-preserving speech pipeline and its deployment-version constraints.
- [cmux](https://github.com/manaflow-ai/cmux) — iOS Dev Tools · iOS Dev Tools: MistKit, Swift Scribe, cmux — Source repository · Topics: AI Development · Developer Tools · Product Design
  **Published:** `2026-07-16T16:45:11.086Z`
  **NeKI brief:** cmux is a Ghostty-based macOS terminal organized around vertical tabs, notifications, and programmable agent workflows. Useful for evaluating a terminal layout that keeps multiple coding-agent sessions visible and actionable.
- [The Platform for Agentic macOS Development](https://go.macstadium.com/build-faster-with-orka) — iOS Dev Weekly · Issue 758 — Article · Topics: AI Development · CI/CD & Automation · Testing
  **Published:** `10th July 2026`
  **NeKI brief:** MacStadium's Orka overview describes API- and CLI-driven Apple-silicon virtual machines for CI, testing, and agent workflows. Use it to evaluate elastic macOS capacity against cost, isolation, Kubernetes integration, and reproducible build requirements.
- [TourKit](https://github.com/rampatra/TourKit) — iOS Dev Tools · iOS Dev Tools: TourKit, MockingKit, MemoryMap — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2026-07-09T16:30:20.398Z`
  **NeKI brief:** TourKit implements Apple-style onboarding tours for Mac and iPhone apps, providing guided highlights over application UI. Useful when a product needs contextual feature discovery instead of a sequence of static introduction screens.
- [cctop](https://cctop.app/) — iOS Dev Tools · iOS Dev Tools: TourKit, MockingKit, MemoryMap — Article · Topics: AI Development · Developer Tools · macOS & AppKit
  **Published:** `2026-07-09T16:30:20.398Z`
  **NeKI brief:** cctop is a macOS menu-bar utility for monitoring and managing Claude Code sessions. It is useful for keeping agent activity visible during development, especially when several terminal sessions compete for attention.
- [Lidless](https://github.com/nghialuong/Lidless) — iOS Dev Tools · iOS Dev Tools: TourKit, MockingKit, MemoryMap — Source repository · Topics: Developer Tools · macOS & AppKit · Personal Essays
  **Published:** `2026-07-09T16:30:20.398Z`
  **NeKI brief:** Lidless keeps a Mac running with its lid closed, targeting unattended coding-agent workflows from the menu bar. Useful for evaluating laptop clamshell automation while considering thermal, power, and security trade-offs.
- [OpenUsage](https://github.com/robinebers/openusage) — iOS Dev Tools · iOS Dev Tools: Apple App Store Scraper, SideScreen, SiteKit — Source repository · Topics: AI Development · App Distribution & Store Operations · Developer Tools
  **Published:** `2026-07-02T19:03:32.109Z`
  **NeKI brief:** OpenUsage presents subscription and usage information in an open-source desktop utility, helping users see where recurring services are being consumed. Useful as a reference for local usage aggregation and transparent cost awareness.
- [BLEUnlock](https://github.com/ts1/BLEUnlock) — iOS Dev Tools · iOS Dev Tools: Apple App Store Scraper, SideScreen, SiteKit — Source repository · Topics: Developer Tools · macOS & AppKit
  **Published:** `2026-07-02T19:03:32.109Z`
  **NeKI brief:** BLEUnlock uses Bluetooth LE proximity devices such as an iPhone or Apple Watch to lock and unlock a Mac. Useful for studying a practical CoreBluetooth-to-macOS security workflow and its trust-boundary limitations.
- [Headroom](https://headroom.walls.sh/) — iOS Dev Tools · iOS Dev Tools: Footprint, ZMarkupParser, Lettera — Article · Topics: macOS & AppKit
  **Published:** `2026-06-18T16:02:35.381Z`
  **NeKI brief:** Headroom is a macOS utility that surfaces available system memory and related pressure information. Use it while investigating resource-heavy development workflows, treating its readings as an operational aid rather than a replacement for Instruments.
- [Stop configuring MCPs in every AI app](https://www.mcp-beast.ai/mac-app-ios-developers) — SwiftLee Weekly · Issue 328 — Article · Topics: AI Development · Developer Tools · Persistence & Synchronisation
  **Published:** `2026-06-16T14:06:32.000Z`
  **NeKI brief:** Explores centralizing MCP configuration so multiple AI clients can share one setup. Use it when reducing repeated tool registration across development environments, while reviewing credential handling and client-specific capability differences.
- [iOS/MacOS: Apple Beta Doc Retriever](https://github.com/0Itsuki0/iOS-MacOS_AppleBetaDocRetriever) — Fatbobman’s Swift Weekly · Issue 140 — Source repository · Topics: Developer Tools
  **Published:** `2026-06-15T12:03:17.597Z`
  **NeKI brief:** AppleBetaDocRetriever collects iOS and macOS beta documentation for offline or searchable reference. Use it when beta APIs change quickly and you need a local comparison aid, while treating Apple's live documentation as authoritative.
- [WWDC Quick Look](https://wwdc-quick-look.swiftgg.team/articles) — Fatbobman’s Swift Weekly · Issue 140 — Article · Topics: Apple Platform Ecosystem · Swift
  **Published:** `2026-06-15T12:03:17.597Z`
  **NeKI brief:** WWDC Quick Look provides a community index of Apple developer announcements and session takeaways. Use it for fast discovery across topics, treating every summary as a pointer to the authoritative session or documentation.
- [EnableMacosAI](https://github.com/SkyBlue997/enableMacosAI) — Fatbobman’s Swift Weekly · Issue 140 — Source repository · Topics: AI Development · Developer Tools · macOS & AppKit
  **Published:** `2026-06-15T12:03:17.597Z`
  **NeKI brief:** EnableMacosAI documents a workaround for making Apple Intelligence features available in unsupported macOS environments. Treat it as experimental configuration research, not a supported deployment approach or substitute for official eligibility requirements.
- [Sparkle 2](https://github.com/sparkle-project/Sparkle) — iOS Dev Tools · iOS Dev Tools: Simtime, Sparkle 2, SwiftINI — Source repository · Topics: Developer Tools
  **Published:** `2026-06-04T17:01:58.905Z`
  **NeKI brief:** Sparkle provides signed software-update delivery for macOS applications, including feed handling and installer integration. Useful for studying a mature update channel and the security responsibilities around release signatures and keys.
- [SwiftBar](https://github.com/swiftbar/SwiftBar) — iOS Dev Tools · iOS Dev Tools: Simtime, Sparkle 2, SwiftINI — Source repository · Topics: Developer Tools · macOS & AppKit · Swift
  **Published:** `2026-06-04T17:01:58.905Z`
  **NeKI brief:** SwiftBar turns shell scripts into macOS menu-bar items, using script output to define labels, menus, and refresh behavior. Useful for lightweight developer dashboards without building a dedicated native status application.
- [DockDoor](https://github.com/ejbills/DockDoor) — iOS Dev Tools · iOS Dev Tools: Simtime, Sparkle 2, SwiftINI — Source repository · Topics: Developer Tools · Swift
  **Published:** `2026-06-04T17:01:58.905Z`
  **NeKI brief:** DockDoor adds macOS window peeking, alternate-tab behavior, and related desktop navigation enhancements. Useful for examining how a menu-bar utility can improve window switching while staying outside application code.
- [Open Caffeine](https://github.com/sapsaldog/open-caffeine) — iOS Dev Tools · iOS Dev Tools: Simtime, Sparkle 2, SwiftINI — Source repository · Topics: Developer Tools · macOS & AppKit · Swift
  **Published:** `2026-06-04T17:01:58.905Z`
  **NeKI brief:** Open Caffeine prevents a Mac from sleeping through a small menu-bar control. Useful for inspecting a minimal, reversible power-management utility used during long builds, demos, or unattended local jobs.
- [SwiftUI Should Become Open-Source](https://macguru.dev/swiftui-should-become-open-source) — Those Who Swift · Issue 268 — Article · Topics: Hardware & Devices · Swift · SwiftUI
  **Published:** `2026-05-27`
  **NeKI brief:** Makes a case for opening SwiftUI's implementation and discusses how transparency could affect the ecosystem. Treat it as opinion and community perspective, useful for framing trade-offs rather than as evidence about Apple's roadmap or framework internals.
- [How To Recognize Text In Images With Vision In Swift](https://onmyway133.com/posts/how-to-recognize-text-in-images-with-vision-in-swift) — Those Who Swift · Issue 267 — Article · Topics: Concurrency · Swift
  **Published:** `2026-05-21`
  **NeKI brief:** Shows text recognition in images with Apple's Vision framework. Use it when prototyping OCR, considering request configuration, region or language hints, result confidence, and asynchronous image processing before integrating recognized text into user-visible features.
- [Northstar](https://www.gonorthstar.io/) — iOS Dev Tools · iOS Dev Tools: SwiftSafeUI, Northstar, Ezscreenshots — Article · Topics: App Distribution & Store Operations
  **Published:** `2026-05-14T16:15:24.123Z`
  **NeKI brief:** Northstar combines App Store keyword opportunity scores, competitor metadata and review tracking, App Store Connect synchronization, and an MCP server for LLM-assisted optimization. It is useful when researching an auditable alternative to ad-hoc ASO spreadsheets.
- [TaskMenu](https://github.com/crazytan/TaskMenu) — iOS Dev Tools · iOS Dev Tools: SwiftSafeUI, Northstar, Ezscreenshots — Source repository · Topics: Developer Career & Practice · Developer Tools · macOS & AppKit
  **Published:** `2026-05-14T16:15:24.123Z`
  **NeKI brief:** TaskMenu surfaces Google Tasks in a native macOS menu-bar application. Useful for examining a small API-backed desktop client that keeps task capture accessible without maintaining a full windowed workspace.
- [Using SwiftUI to Build a Mac-assed App in 2026](https://pfandrade.me/blog/mac-assed-swiftui-app) — iOS Dev Weekly · Issue 750 — Article · Topics: Swift · SwiftUI
  **Published:** `8th May 2026`
  **NeKI brief:** Presents using swiftui to build a mac-assed app in 2026 for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Paywall Design Tips That Boost App Sales - Part 2](https://indieappdevs.substack.com/p/indie-app-devs-21) — Those Who Swift · Issue 264 — Article · Topics: Developer Community & Business · Swift · SwiftUI
  **Published:** `2026-04-29`
  **NeKI brief:** Examines Paywall Design Tips That Boost App Sales - Part 2, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Claude Account Switcher](https://github.com/Symbioose/claude-account-switcher) — iOS Dev Tools · iOS Dev Tools: SwiftZilla, Room Service, Pica — Source repository · Topics: Developer Tools · macOS & AppKit
  **Published:** `2026-04-16T16:01:26.478Z`
  **NeKI brief:** Claude Account Switcher manages multiple Claude Code and Codex CLI accounts from a Mac menu bar, showing usage and switching at limits. Useful for studying credential-profile separation and the operational risks of automated account changes.
- [OpenAI: Build For iOS And macOS](https://developers.openai.com/codex/use-cases/native-ios-macos-apps) — Those Who Swift · Issue 260 — Article · Topics: AI Development · Apple Platform Ecosystem · Testing
  **Published:** `2026-04-01`
  **NeKI brief:** Examines OpenAI: Build For iOS And macOS, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Orcv](https://github.com/jasonjmcghee/orcv) — iOS Dev Tools · iOS Dev Tools: Skills, Speech Swift, Workflow Audit Skill, Orcv — Source repository · Topics: Developer Tools · macOS & AppKit
  **Published:** `2026-03-12T17:30:51.176Z`
  **NeKI brief:** Orcv arranges virtual displays in an infinite zoomable canvas, with savepoints, desktop jumps, window or mouse teleportation, undo/redo, and fullscreen shortcuts. It is useful as a concrete macOS window-management workflow rather than a conventional single-desktop utility.
- [vChewing Input Method](https://vchewing.github.io/README.html) — Fatbobman’s Swift Weekly · Issue 126 — Article · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `2026-03-09T12:02:58.691Z`
  **NeKI brief:** vChewing documents a Chinese input method built for Apple platforms, including its user-facing behavior and project context. Follow it as a case study in text-input engineering, not as a general Swift UI tutorial.
- [IMKSwift](https://github.com/vChewing/IMKSwift) — Fatbobman’s Swift Weekly · Issue 126 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2026-03-09T12:02:58.691Z`
  **NeKI brief:** IMKSwift provides a Swift 6-oriented, @MainActor-isolated base controller for InputMethodKit sessions. Use it when modernizing macOS input methods and avoiding the concurrency hazards inherited from IMKInputController-style callbacks.
- [Notepad.exe](https://notepadexe.com/) — iOS Dev Tools · iOS Dev Tools: Notepad.exe, SimTag, Rich HTML Editor — Article
  **Published:** `2026-03-05T17:46:01.942Z`
  **NeKI brief:** Notepad.exe is a Swift-focused playground and editor experiment. Use it to explore lightweight code execution and text-editing workflows outside Xcode, not as a replacement for full project tooling.
- [CodexBar](https://codexbar.app/) — iOS Dev Tools · iOS Dev Tools: DevScroll, FeaturesKit, HeC - Unofficial Hetzner Cloud — Article · Topics: macOS & AppKit
  **Published:** `2026-02-12T17:15:27.823Z`
  **NeKI brief:** CodexBar is a macOS menu-bar application for monitoring Codex usage and related account limits. It is useful for keeping quota state visible during agent-heavy work, subject to provider changes and the tool’s credential-handling design.
- [Adding an Open Recent Menu in a macOS App](https://swiftdevjournal.com/posts/open-recent-menu) — Those Who Swift · Issue 253 — Article · Topics: Swift
  **Published:** `2026-02-12`
  **NeKI brief:** Adds an Open Recent menu to a SwiftUI app, wiring recent document state into platform menu commands. Useful for macOS document workflows that need persistence, discoverable actions, and correct scene-level ownership.
- [full tutorial available](https://www.electronjs.org/docs/latest/tutorial/native-code-and-electron-swift-macos) — iOS Dev Weekly · Issue 742 — Tutorial · Topics: macOS & AppKit · Swift · Testing
  **Published:** `6th February 2026`
  **NeKI brief:** Presents full tutorial available for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Deepgram](https://deepgram.com/) — iOS Dev Tools · iOS Dev Tools: AboutKit, HelpKit, Claude XcodePreviews — Article · Topics: macOS & AppKit
  **Published:** `2026-02-05T21:03:29.009Z`
  **NeKI brief:** Deepgram provides speech-to-text and voice AI APIs for transcription and related audio workloads. Use it when comparing hosted speech services, evaluating latency, language support, pricing, retention, and whether processing requirements permit sending audio off-device.
- [SwiftUI Alerting with NSAlert](https://medium.com/@itsuki.enjoy/swiftui-alerting-with-nsalert-21bdc3a8e650) — Those Who Swift · Issue 251 — Article · Topics: Developer Community & Business · Swift · SwiftUI
  **Published:** `2026-01-28`
  **NeKI brief:** Examines SwiftUI Alerting with NSAlert, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [WhisperShortcut](https://github.com/mgsgde/whisper-shortcut) — iOS Dev Tools · iOS Dev Tools: SwiftAgents, XML Comparator, Colorful — Source repository · Topics: AI Development · Developer Tools · macOS & AppKit
  **Published:** `2026-01-15T18:30:34.396Z`
  **NeKI brief:** WhisperShortcut provides speech-to-text and voice-to-prompt workflows on macOS using Whisper and Gemini integrations. Useful for evaluating local audio capture, transcription handoff, and assistant prompting in a keyboard-driven tool.
- [ClaudeBar](https://github.com/tddworks/ClaudeBar) — iOS Dev Tools · iOS Dev Tools: Swift-Parsing, ColorsKit, SwiftUI Indie Stack — Source repository · Topics: AI Development · Developer Tools · macOS & AppKit
  **Published:** `2025-12-25T17:35:11.361Z`
  **NeKI brief:** ClaudeBar monitors Claude, Codex, Antigravity, and Gemini usage quotas from a macOS menu bar. Useful for a compact multi-provider status surface, especially when comparing polling, rate-limit display, and privacy boundaries.
- [PortKiller](https://github.com/gupsammy/PortKiller) — iOS Dev Tools · iOS Dev Tools: ObjectBox, RIB, Swon — Source repository · Topics: Developer Tools · macOS & AppKit
  **Published:** `2025-12-04T17:28:54.311Z`
  **NeKI brief:** PortKiller lists processes bound to development ports and can terminate selected listeners from a macOS menu bar. Useful for quickly resolving local server conflicts without repeatedly composing lsof and kill commands.
- [Enabling Selection, Double-Click & Context Menus in SwiftUI List on macOS](https://serialcoder.dev/text-tutorials/swiftui/enabling-selection-double-click-and-context-menus-in-swiftui-list-on-macos) — Those Who Swift · Issue 242 — Tutorial · Topics: macOS & AppKit · Swift · SwiftUI
  **Published:** `2025-11-26`
  **NeKI brief:** Examines Enabling Selection, Double-Click & Context Menus in SwiftUI List on macOS, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [imessage-kit](https://github.com/photon-hq/imessage-kit) — Fatbobman’s Swift Weekly · Issue 112 — Source repository · Topics: Developer Tools
  **Published:** `2025-11-24T12:01:09.147Z`
  **NeKI brief:** iMessageKit explores message-style interfaces on Apple platforms despite iMessage itself lacking a public automation API. Use it as a UI and data-model reference, not as evidence that third-party apps can access system conversations.
- [The best mobile app monitoring product just keeps getting better](https://sentry.io/for/swift) — iOS Dev Weekly · Issue 733 — Article · Topics: Swift
  **Published:** `31st October 2025`
  **NeKI brief:** Presents The best mobile app monitoring product just keeps getting better, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Emerge Tools is now a part of Sentry](https://www.emergetools.com/blog/posts/emerge-tools-is-joining-sentry) — iOS Dev Weekly · Issue 733 — Article
  **Published:** `31st October 2025`
  **NeKI brief:** Presents Emerge Tools is now a part of Sentry, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [MacPacker](https://github.com/sarensw/MacPacker) — iOS Dev Tools · iOS Dev Tools: Netrofit, MacPacker, GradientEditor — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2025-10-30T18:15:32.319Z`
  **NeKI brief:** MacPacker creates and packages macOS applications from project inputs, automating repeatable archive, signing, and distribution steps. It is useful for examining a small focused alternative to hand-written packaging scripts in local or CI release workflows.
- [Vercel Deployment Menu Bar](https://github.com/andrewk17/vercel-deployment-menu-bar) — iOS Dev Tools · iOS Dev Tools: Netrofit, MacPacker, GradientEditor — Source repository · Topics: Developer Tools · macOS & AppKit
  **Published:** `2025-10-30T18:15:32.319Z`
  **NeKI brief:** Vercel Deployment Menu Bar watches deployment states such as building, ready, and error from a macOS status item. Useful for a small event-driven release monitor that keeps CI feedback visible outside the browser.
- [SwiftUI Concentric Rectangle & Concentric Corners in iOS 26](https://www.youtube.com/watch?v=VFnidjiH750) — Those Who Swift · Issue 236 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2025-10-15`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Darling](https://github.com/darlinghq/darling) — iOS Dev Tools · iOS Dev Tools: React-native-enriched, Darling, Aidoku — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2025-10-02T19:15:22.078Z`
  **NeKI brief:** Darling provides a macOS runtime environment on Linux, including DPREFIX-style environments, package and DMG handling, and support for compiling with Apple's toolchain and SDKs. It is useful for understanding the practical limits of cross-platform macOS compatibility.
- [9TO5Mac’s report](https://9to5mac.com/2025/09/22/macos-tahoe-26-1-beta-1-mcp-integration) — Fatbobman’s Swift Weekly · Issue 104 — Article · Topics: AI Development · macOS & AppKit
  **Published:** `2025-09-29T12:00:38.726Z`
  **NeKI brief:** Reports beta evidence of MCP-related integration in macOS Tahoe. Use it only as an early signal for system-level agent support, then validate actual APIs, availability, and permissions against Apple's released documentation.
- [Layout Guidelines](https://marioaguzman.github.io/design/layoutguidelines) — iOS Dev Weekly · Issue 727 — Article · Topics: Developer Tools
  **Published:** `19th September 2025`
  **NeKI brief:** Presents layout guidelines for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Toolbar Guidelines](https://marioaguzman.github.io/design/toolbarguidelines) — iOS Dev Weekly · Issue 727 — Article · Topics: Developer Tools
  **Published:** `19th September 2025`
  **NeKI brief:** Presents toolbar guidelines for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [detailed introduction](https://brightdigit.com/tutorials/swift-build) — Fatbobman’s Swift Weekly · Issue 102 — Tutorial · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-09-15T12:03:30.479Z`
  **NeKI brief:** Explains using the swift-build GitHub Action to run Swift Package Manager builds and tests on macOS and Linux. Use it as a compact cross-platform CI starting point before adding caching, matrices, or release artifacts.
- [QuickRecorder](https://github.com/lihaoyun6/QuickRecorder) — iOS Dev Tools · iOS Dev Tools: IQListKit, Radar, HapticPlayer — Source repository · Topics: Developer Tools · Performance
  **Published:** `2025-09-04T15:31:16.101Z`
  **NeKI brief:** QuickRecorder is a lightweight macOS recorder built around ScreenCaptureKit, covering screen capture and related recording controls. Useful for examining a native capture workflow when producing reproducible demos or test evidence.
- [SwiftUI for Mac 2025](https://troz.net/post/2025/swiftui-mac-2025) — SwiftLee Weekly · Issue 284 — Article · Topics: Swift · SwiftUI
  **Published:** `2025-08-12T18:01:44.000Z`
  **NeKI brief:** Presents SwiftUI for Mac 2025, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [sample app](https://github.com/trozware/swiftui-mac-2025) — Fatbobman’s Swift Weekly · Issue 96 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2025-08-04T12:03:39.737Z`
  **NeKI brief:** This sample app collects macOS SwiftUI 2025 features and implementation notes, including new icon formats and native controls. Use it as a runnable compatibility reference when adopting current macOS-specific SwiftUI APIs.
- [FreeTypeFramework](https://github.com/EvgenijLutz/FreeTypeFramework) — iOS Dev Tools · iOS Dev Tools: FreeTypeFramework, IGListKit, Horoscope — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-07-31T18:12:59.226Z`
  **NeKI brief:** FreeTypeFramework packages the FreeType font engine for Apple-platform projects, making font parsing and rasterization available through a reusable framework. The repository is a useful starting point when system font APIs do not cover a custom rendering pipeline.
- [Writing a macOS Finder "action" Extension with Swift 6 Concurrency](https://cmsj.net/2025/05/23/finder-action-swift6.html) — Fatbobman’s Swift Weekly · Issue 94 — Article · Topics: Concurrency · Cross-Platform & Web · Swift
  **Published:** `2025-07-21T12:02:54.857Z`
  **NeKI brief:** Shows a macOS Finder action extension that bridges synchronous system callbacks into Swift 6 concurrency. Use it when adapting callback-based extension points while preserving correct actor isolation and completion timing.
- [Chris Jones](https://cmsj.net/author/chris-jones.html) — Fatbobman’s Swift Weekly · Issue 94 — Article · Topics: Concurrency · Cross-Platform & Web · Swift
  **Published:** `2025-07-21T12:02:54.857Z`
  **NeKI brief:** Provides contextual background on Chris Jones, useful for understanding the surrounding product, policy, or ecosystem issue before drawing technical or business conclusions.
- [Meet the Inspector View in SwiftUI](https://serialcoder.dev/text-tutorials/swiftui/meet-the-inspector-view-in-swiftui) — Those Who Swift · Issue 221 — Tutorial · Topics: Swift · SwiftUI
  **Published:** `2025-07-02`
  **NeKI brief:** Examines Meet the Inspector View in SwiftUI, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Automatic Observation Tracking in UIKit and AppKit](https://steipete.me/posts/2025/automatic-observation-tracking-uikit-appkit) — iOS Dev Weekly · Issue 716 — Article · Topics: macOS & AppKit · Swift · UIKit
  **Published:** `27th June 2025`
  **NeKI brief:** Explores automatic Observation tracking in UIKit and AppKit. Use it when imperative views should react to observable model reads without manually registering broad notifications.
- [macOS by Tutorials](https://sarahreichelt.gumroad.com/l/oximx) — iOS Dev Weekly · Issue 715 — Tutorial · Topics: Graphics, Media & Games
  **Published:** `20th June 2025`
  **NeKI brief:** Presents macos by tutorials for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [WebView Is Finally Coming to SwiftUI](https://danielsaidi.com/blog/2025/06/10/webview-is-finally-coming-to-swiftui) — Those Who Swift · Issue 219 — Article · Topics: Swift · Swift Package Manager · SwiftUI
  **Published:** `2025-06-19`
  **NeKI brief:** Discusses the emerging native SwiftUI web-view direction and its implications for replacing representable wrappers. Useful for migration planning, while verifying availability and behavior against the target SDK.
- [Virtualizing macOS 26 Tahoe](https://eclecticlight.co/2025/06/11/virtualising-macos-26-tahoe) — Fatbobman’s Swift Weekly · Issue 88 — Article · Topics: macOS & AppKit
  **Published:** `2025-06-12T02:52:10.753Z`
  **NeKI brief:** Examines virtualizing macOS Tahoe and the practical changes around the new release. Use it when assessing test or CI environments that depend on virtual machines and need version-specific constraints.
- [macOS Tahoe Brings a New Disk Image Format](https://eclecticlight.co/2025/06/12/macos-tahoe-brings-a-new-disk-image-format) — Fatbobman’s Swift Weekly · Issue 88 — Article · Topics: macOS & AppKit
  **Published:** `2025-06-12T02:52:10.753Z`
  **NeKI brief:** Explains Tahoe's new disk-image format and its operational implications. Use it when build, test, packaging, or virtualization workflows manipulate disk images and may need compatibility planning across macOS releases.
- [MenuScores](https://github.com/daniyalmaster693/MenuScores) — iOS Dev Tools · iOS Dev Tools: Bullseye, ProgressUI, Harmonize — Source repository · Topics: Developer Tools · macOS & AppKit
  **Published:** `2025-05-22T17:27:20.321Z`
  **NeKI brief:** MenuScores displays live sports scores in a macOS menu-bar or notch-oriented surface. Useful as a compact example of polling, transient status presentation, and constrained desktop UI layout.
- [LogUI](https://eclecticlight.co/2025/03/14/browse-your-macs-log-with-logui) — Fatbobman’s Swift Weekly · Issue 83 — Article · Topics: Objective-C & Cocoa
  **Published:** `2025-05-12T12:02:48.422Z`
  **NeKI brief:** Shows how LogUI opens multiple views over unified macOS logs with independent searches and filters. Use it when application launch noise makes Console difficult to navigate and parallel focused log queries speed diagnosis.
- [Loving SwiftUI, missing UIKit.](https://collin.blog/2025/04/24/loving-swiftui-missing-uikit) — SwiftUI Weekly · SwiftUI Weekly - Issue #214 — Article · Topics: Swift · SwiftUI · UIKit
  **Published:** `2025-04-28T13:32:59.660Z`
  **NeKI brief:** Reflects on SwiftUI strengths and UIKit capabilities that developers may still miss. Useful as balanced migration context when deciding where a hybrid implementation remains the lower-risk product choice.
- [DataScout](https://data-scout.pages.dev/) — iOS Dev Tools · iOS Dev Tools: AppsMan, ErrorKit, DataScout — Article · Topics: Core Data · Cross-Platform & Web · Persistence & Synchronisation
  **Published:** `2025-04-24T13:08:49.536Z`
  **NeKI brief:** Data Scout is a data-exploration project presented as a developer product. Inspect its concrete workflow when comparing small utility apps, data presentation choices, and the cost of maintaining a focused independent product.
- [UBI](https://github.com/houseabsolute/ubi) — Fatbobman’s Swift Weekly · Issue 79 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2025-04-14T12:01:43.772Z`
  **NeKI brief:** ubi installs precompiled command-line tool binaries from GitHub releases rather than building them locally. Use it when developer-tool setup must be fast and repeatable across machines, while checking release provenance and platform artifacts.
- [Introducing swiftly 1.0](https://www.swift.org/blog/introducing-swiftly_10) — Those Who Swift · Issue 208 — Article · Topics: Developer Career & Practice · Foundation & Data Formats · Swift
  **Published:** `2025-04-02`
  **NeKI brief:** This technical resource covers Swiftly 1.0 as a Swift toolchain manager. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [iMCP](https://github.com/loopwork-ai/iMCP) — Fatbobman’s Swift Weekly · Issue 76 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `2025-03-24T12:01:29.089Z`
  **NeKI brief:** iMCP is a macOS MCP server that brokers access to local calendar, contacts, messages, reminders, and weather data. Use it to inspect permission-aware system-data tool design before connecting an agent to personal information.
- [Building a MCP Server in Swift](https://adamwulf.me/2025/03/building-a-mcp-server-in-swift) — Those Who Swift · Issue 206 — Article · Topics: AI Development · Swift
  **Published:** `2025-03-19`
  **NeKI brief:** Describes Building a MCP Server in Swift, focusing on practical tool integration and workflow trade-offs. Use it to evaluate reproducibility, trust boundaries, and debugging steps before adopting the approach in an Xcode project.
- [MaClicker](https://github.com/WorldOfBasti/MaClicker) — iOS Dev Tools · iOS Dev Tools: Swift GraphQL Codegen, HandySwiftUI, Surge — Source repository · Topics: Developer Tools · Swift
  **Published:** `2025-03-13T19:20:57.517Z`
  **NeKI brief:** MaClicker is a small macOS auto-clicker implemented as a focused utility. Useful for examining global input automation and the permission boundary such tools require, rather than treating simulated clicks as ordinary app events.
- [Peek](https://prateekkeshari.gumroad.com/l/peek) — iOS Dev Tools · iOS Dev Tools: Statused, Compot, FreemiumKit — Article · Topics: AI Development · macOS & AppKit
  **Published:** `2025-03-06T18:01:47.698Z`
  **NeKI brief:** Peek is a paid developer resource or utility distributed through Gumroad. Use the page to inspect its stated workflow and scope, verifying ownership, licensing, updates, and whether it solves a concrete development problem before purchase.
- [Swift Build](https://github.com/swiftlang/swift-build) — Fatbobman’s Swift Weekly · Issue 69 — Source repository · Topics: Swift · Swift Package Manager · Xcode
  **Published:** `2025-02-03T12:01:11.391Z`
  **NeKI brief:** Swift Build is the open-sourced build engine behind Xcode and SwiftPM convergence work. Follow it when assessing build-graph architecture, toolchain behavior, and future migration implications for projects that currently rely on opaque Xcode builds.
- [llbuild](https://github.com/swiftlang/swift-llbuild) — Fatbobman’s Swift Weekly · Issue 69 — Source repository · Topics: Swift · Swift Package Manager · Xcode
  **Published:** `2025-02-03T12:01:11.391Z`
  **NeKI brief:** llbuild is the lower-level build-system engine used by Swift tooling. Use it to inspect dependency scheduling and incremental compilation foundations, while keeping its implementation role distinct from the higher-level Swift Build repository.
- [Multiplatform Development for Apple Devices](https://darrylbayliss.net/multiplatform-development-for-apple-devices) — Those Who Swift · Issue 199 — Article · Topics: Swift · SwiftUI
  **Published:** `2025-01-30`
  **NeKI brief:** Examines Multiplatform Development for Apple Devices, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Add launch at login setting to a macOS app](https://nilcoalescing.com/blog/LaunchAtLoginSetting?ref=createwithswift.com) — Create with Swift · Issue 44 — Article · Topics: Swift
  **Published:** `2025-01-17T16:05:04.000Z`
  **NeKI brief:** Demonstrates registering a macOS app as a login item with SMAppService. Use it to implement an explicit launch-at-login setting while keeping user control and system preferences aligned.
- [Accessibility That Fits](https://khanlou.com/2024/12/accessibility-that-fits) — SwiftUI Weekly · SwiftUI Weekly - Issue #206 — Article · Topics: Accessibility · Product Design · Swift
  **Published:** `2025-01-13T09:29:54.892Z`
  **NeKI brief:** Discusses fitting accessibility behavior into existing interfaces without treating it as a late checklist. Useful for reviewing SwiftUI labels, traits, Dynamic Type, and interaction alternatives as part of component design.
- [How to keep your macOS app's menu bar item running after quitting the app](https://www.polpiella.dev/keep-menu-bar-running-after-quitting-app?ref=createwithswift.com) — Create with Swift · Issue 43 — Article · Topics: macOS & AppKit · Personal Essays · Swift
  **Published:** `2025-01-10T16:30:02.000Z`
  **NeKI brief:** Explains keeping a macOS menu-bar utility available after closing ordinary windows. Use it when separating an app's activation policy, status item, and termination behavior.
- [EasyStash](https://github.com/onmyway133/EasyStash) — iOS Dev Tools · iOS Dev Tools: Sourcery, FengNiao, EasyStash — Source repository · Topics: Developer Tools
  **Published:** `2024-12-26T21:45:51.591Z`
  **NeKI brief:** EasyStash provides a lightweight cross-platform persistence wrapper for Apple-platform apps. Use it to evaluate a small storage abstraction for simple values, while confirming its serialization, migration, and thread-safety limits against your data requirements.
- [VoiceOver on macOS: First Time, Huh?](https://www.basbroek.nl/macos-voiceover-first-time-huh) — SwiftLee Weekly · Issue 251 — Article · Topics: Accessibility · macOS & AppKit
  **Published:** `2024-12-23T10:34:05.000Z`
  **NeKI brief:** Presents VoiceOver on macOS: First Time, Huh?, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Should we use Apple Intelligence for Text and Inputs in SwiftUI using writingToolsBehavior](https://medium.com/@jpmtech/should-we-use-apple-intelligence-for-text-and-inputs-in-swiftui-using-writingtoolsbehavior-49d662ce5ede) — SwiftLee Weekly · Issue 247 — Article · Topics: AI Development · Swift · SwiftUI
  **Published:** `2024-11-26T15:01:34.000Z`
  **NeKI brief:** Evaluates writingToolsBehavior for Apple Intelligence text assistance in SwiftUI inputs. Use it when deciding whether system writing tools fit an editor, checking availability, privacy expectations, and user-control requirements.
- [ChatGPT for macOS can now work with Xcode](https://dimillian.medium.com/chatgpt-for-macos-can-now-work-with-xcode-28cecc9decf7) — SwiftLee Weekly · Issue 246 — Article · Topics: AI Development · macOS & AppKit · Xcode
  **Published:** `2024-11-19T12:58:52.000Z`
  **NeKI brief:** Presents ChatGPT for macOS can now work with Xcode, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [ImplementedSE-0106Add a `macOS` Alias for the `OSX` Platform Configuration Test](https://github.com/apple/swift-evolution/blob/main/proposals/0106-rename-osx-to-macos.md) — SwiftLee Weekly · Issue 245 — Source repository · Topics: Developer Tools · macOS & AppKit · Swift
  **Published:** `2024-11-12T19:03:27.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0106Add a `macOS` Alias for the `OSX` Platform Configuration Test. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [TrustKit](https://github.com/datatheorem/TrustKit) — iOS Dev Tools · iOS Dev Tools: TrustKit, CocoaLumberjack, Tart — Source repository · Topics: Developer Tools · Security & Privacy
  **Published:** `2024-11-07T18:01:24.658Z`
  **NeKI brief:** An open-source iOS and macOS framework for SSL public-key pinning. It centralizes pinning policies, validates server identity, blocks man-in-the-middle connections, and reports validation failures, making the repository useful when hardening app networking.
- [CocoaLumberjack](https://github.com/CocoaLumberjack/CocoaLumberjack) — iOS Dev Tools · iOS Dev Tools: TrustKit, CocoaLumberjack, Tart — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2024-11-07T18:01:24.658Z`
  **NeKI brief:** A configurable logging framework for Apple platforms that routes messages to destinations such as console, files, or remote servers. Its filtering and low-overhead logging model is useful when designing diagnostics that remain practical in production builds.
- [Orka Desktop](https://www.macstadium.com/orka-desktop) — iOS Dev Weekly · Issue 685 — Article · Topics: Personal Essays · Testing
  **Published:** `1st November 2024`
  **NeKI brief:** Presents orka desktop for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Cross-Platform macOS/Windows Application Developed Using Swift 6](https://forums.swift.org/t/example-of-a-cross-platform-macos-windows-application-developed-using-swift-6/74591) — iOS Dev Weekly · Issue 679 — Article · Topics: AI Development · Cross-Platform & Web · Swift
  **Published:** `20th September 2024`
  **NeKI brief:** Presents cross-platform macos/windows application developed using swift 6 for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [available on GitHub](https://github.com/fbarbat/fellmonger) — iOS Dev Weekly · Issue 679 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `20th September 2024`
  **NeKI brief:** Presents available on github for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Github contribution graph with Swift Charts](https://www.artemnovichkov.com/blog/github-contribution-graph-swift-charts) — SwiftUI Weekly · SwiftUI Weekly - Issue #199 — Article · Topics: Developer Tools · Swift
  **Published:** `2024-09-09T19:49:43.177Z`
  **NeKI brief:** Creates a GitHub-style contribution graph with Swift Charts using calendar-shaped data. Useful for practicing custom mark layouts, color scales, and date-based visualization.
- [SwiftFormat](https://github.com/nicklockwood/SwiftFormat) — iOS Dev Tools · iOS Dev Tools: R.swift, Alamofire, SwiftFormat — Source repository · Topics: Developer Tools · Product Design · Swift
  **Published:** `2024-09-05T15:57:02.879Z`
  **NeKI brief:** SwiftFormat offers configurable source-formatting rules and a mature command-line workflow. Follow it when comparing formatter policy, rule customization, and repository integration against Apple's swift-format rather than treating formatting as purely cosmetic.
- [SwiftUI for Mac 2024](https://troz.net/post/2024/swiftui-mac-2024) — iOS Dev Weekly · Issue 675 — Article · Topics: Swift · SwiftUI · Xcode
  **Published:** `23rd August 2024`
  **NeKI brief:** Reviews SwiftUI for macOS in 2024, including windowing, menus, and platform-specific controls. Useful for auditing which shared views need deliberate Mac adaptations.
- [MeshGradients in iOS 18](https://www.youtube.com/watch?v=s_eQZ8rRV8Y) — SwiftUI Weekly · SwiftUI Weekly - Issue #197 — Video · Topics: Graphics, Media & Games
  **Published:** `2024-08-19T10:45:25.615Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [ControlRoom](https://github.com/twostraws/ControlRoom) — iOS Dev Tools · iOS Dev Tools: ControlRoom, SwiftDeps, Starscream — Source repository · Topics: Developer Tools · Xcode
  **Published:** `2024-07-25T15:18:00.048Z`
  **NeKI brief:** ControlRoom is a macOS front end for simctl that manages iOS, tvOS, and watchOS Simulator state. Use it for device launch, screenshots, deep links, permissions, or location testing without repeatedly assembling command-line invocations.
- [SwiftUI can be a bit... eager](https://www.attributedstrings.com/swiftui-can-be-a-bit-eager) — SwiftUI Weekly · SwiftUI Weekly - Issue #193 — Article · Topics: Foundation & Data Formats · Swift · SwiftUI
  **Published:** `2024-07-08T08:54:13.719Z`
  **NeKI brief:** Investigates cases where SwiftUI evaluates views or work eagerly. Useful for diagnosing unexpected initialization, expensive computations, and lifecycle assumptions in declarative hierarchies.
- [Helm](https://helm-app.com/) — iOS Dev Tools · iOS Dev Tools: Helm, AudioKit, Lottie — Article · Topics: App Distribution & Store Operations
  **Published:** `2024-06-20T13:30:58.118Z`
  **NeKI brief:** Discusses Helm in a public developer resource. Use it to compare the author's concrete workflow and trade-offs with your project constraints, and verify any platform-specific claims against current primary documentation.
- [AudioKit](https://github.com/AudioKit/AudioKit) — iOS Dev Tools · iOS Dev Tools: Helm, AudioKit, Lottie — Source repository · Topics: Developer Tools
  **Published:** `2024-06-20T13:30:58.118Z`
  **NeKI brief:** Provides the public source repository for AudioKit. Inspect its implementation, examples, and issue history to evaluate integration boundaries and maintenance trade-offs before depending on it in an Apple-platform project.
- [Meet AppLayouts, an All-in-One Toolkit to Supercharge Your iOS and macOS App](https://www.applayouts.com/) — iOS Dev Tools · iOS Dev Tools: AppScreen Studio, StringSwitch, getuniversal.link — Article
  **Published:** `2024-06-06T16:11:51.001Z`
  **NeKI brief:** Provides a catalogue of reusable app layout patterns and interface examples. Use it to compare navigation, content hierarchy, and responsive composition ideas before designing a SwiftUI or UIKit screen.
- [macOS style Settings windows](https://paulpeelen.com/SettingsView) — iOS Dev Weekly · Issue 660 — Article · Topics: Swift · SwiftUI · Testing
  **Published:** `10th May 2024`
  **NeKI brief:** Presents macos style settings windows for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [the second](https://paulpeelen.com/SettingsViewPart2) — iOS Dev Weekly · Issue 660 — Article · Topics: Swift · SwiftUI · Testing
  **Published:** `10th May 2024`
  **NeKI brief:** Presents the second for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [LocationSimulator](https://github.com/Schlaubischlump/LocationSimulator) — iOS Dev Tools · iOS Dev Tools: LocationSimulator, EarlGrey 2.0, SwiftUI Introspect — Source repository · Topics: Developer Tools · Testing
  **Published:** `2024-05-09T15:35:40.691Z`
  **NeKI brief:** LocationSimulator is a macOS utility for injecting simulated locations into iOS apps and Simulator targets. Use it to exercise geofencing, map, and route states without a physical device or repeated manual coordinate changes.
- [SwiftUI Introspect](https://github.com/siteline/SwiftUI-Introspect) — iOS Dev Tools · iOS Dev Tools: LocationSimulator, EarlGrey 2.0, SwiftUI Introspect — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2024-05-09T15:35:40.691Z`
  **NeKI brief:** SwiftUI Introspect exposes the UIKit or AppKit backing view behind selected SwiftUI controls through version-scoped introspection. Use it for narrowly targeted platform customization when SwiftUI lacks an API, while minimizing reliance on implementation details.
- [SwiftUI Button Click-Through on macOS](https://christiantietze.de/posts/2024/04/enable-swiftui-button-click-through-inactive-windows) — iOS Dev Weekly · Issue 657 — Article · Topics: Swift · SwiftUI
  **Published:** `19th April 2024`
  **NeKI brief:** Presents swiftui button click-through on macos for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Veertu](https://veertu.com/) — iOS Dev Tools · iOS Dev tools: Chime, Parse Platform, Veertu — Article · Topics: CI/CD & Automation · Testing
  **Published:** `2024-04-18T13:45:11.063Z`
  **NeKI brief:** Veertu provides ephemeral macOS virtual machines intended for iOS continuous-integration testing without dedicated physical hardware. Use it when comparing reproducible macOS build capacity, accounting for licensing, performance, provisioning, and simulator constraints.
- [In Search of a Smooth Scroll](https://byla.lt/posts/in-search-of-smooth-scroll) — SwiftUI Weekly · SwiftUI Weekly - Issue #181 — Article · Topics: Objective-C & Cocoa
  **Published:** `2024-04-09T05:33:14.059Z`
  **NeKI brief:** Examines SwiftUI rendering and scrolling costs behind In Search of a Smooth Scroll. Use it to identify identity, layout, and update-frequency risks before measuring regressions with Instruments on representative devices.
- [Apple’s use of AppKit, Catalyst, Swift and SwiftUI in macOS Sonoma](https://blog.timac.org/2023/1128-state-of-appkit-catalyst-swift-swiftui-mac) — Fatbobman’s Swift Weekly · Issue 9 — Article · Topics: macOS & AppKit · Swift · SwiftUI
  **Published:** `2023-12-03T22:00:35.768Z`
  **NeKI brief:** Surveys AppKit, Catalyst, Swift, and SwiftUI capabilities on macOS, highlighting interoperability boundaries. Useful for choosing a platform strategy when an app spans native macOS and shared UI code.
- [Create Your Own Step Counter SwiftUI App in 5 Minutes](https://holyswift.app/create-your-own-step-counter-swiftui-app-in-5-minutes) — Fatbobman’s Swift Weekly · Issue 9 — Article · Topics: Swift · SwiftUI
  **Published:** `2023-12-03T22:00:35.768Z`
  **NeKI brief:** Builds a small step-counter app in SwiftUI, connecting motion-related data with observable view state. Use it to trace permission, sensor, and update-flow concerns before extracting production-grade health or fitness architecture.
- [The complete guide to Swift development in Neovim](https://wojciechkulik.pl/ios/the-complete-guide-to-ios-macos-development-in-neovim) — iOS Dev Weekly · Issue 636 — Article · Topics: macOS & AppKit · Swift · Xcode
  **Published:** `17th November 2023`
  **NeKI brief:** Presents the complete guide to swift development in neovim for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Sensei](https://cindori.com/sensei) — iOS Dev Tools · Introducing Codeshare, Sensei, ProfileMe — Article · Topics: Performance
  **Published:** `2023-09-28T13:10:04.363Z`
  **NeKI brief:** Sensei provides a customizable macOS material-blur view that goes beyond NSVisualEffectView's public configuration surface. Use it when a desktop UI needs controlled materials, while isolating the visual dependency from core application logic.
- [Understanding Publishers in SwiftUI and Combine](https://medium.com/bumble-tech/understanding-publishers-in-swiftui-and-combine-27806aa78ba1) — SwiftUI Weekly · SwiftUI Weekly - Issue #161 — Article · Topics: Combine & Reactive Programming · Swift · SwiftUI
  **Published:** `2023-09-25T21:58:53.226Z`
  **NeKI brief:** Explains how Combine publishers feed SwiftUI updates and how asynchronous streams compose in an application. Useful when diagnosing event pipelines, selecting operators, and deciding where publisher ownership belongs in a view model.
- [Combine](https://www.swiftbysundell.com/discover/combine) — SwiftUI Weekly · SwiftUI Weekly - Issue #161 — Article · Topics: Combine & Reactive Programming · Swift · SwiftUI
  **Published:** `2023-09-25T21:58:53.226Z`
  **NeKI brief:** Collects Swift by Sundell's Combine material on publishers, operators, and reactive application design. Useful as a navigation hub when maintaining Combine code or comparing legacy pipelines with newer async/await implementations.
- [AppKit vs SwiftUI: Stable vs Shiny](https://milen.me/writings/appkit-vs-swiftui-stable-vs-shiny) — iOS Dev Weekly · Issue 622 — Article · Topics: macOS & AppKit · Swift · SwiftUI
  **Published:** `11th August 2023`
  **NeKI brief:** Explores AppKit vs SwiftUI: Stable vs Shiny, focusing on every now and then, it’s worth checking back in on. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [answer to the question was from Sarah Reichelt](https://www.kodeco.com/books/macos-apprentice/v1.0/chapters/18-using-swiftui-in-appkit) — iOS Dev Weekly · Issue 622 — Article · Topics: macOS & AppKit · Swift · SwiftUI
  **Published:** `11th August 2023`
  **NeKI brief:** Explores answer to the question was from Sarah Reichelt, focusing on every now and then, it’s worth checking back in on. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Maccy - Lightweight Clipboard Manager for macOS](https://github.com/kean/Nuke) — iOS Dev Tools · 🔨 It's Clipboard Magic (and Other Stuff) — Source repository · Topics: Developer Tools · Product Design
  **Published:** `2023-06-29T13:51:11.661Z`
  **NeKI brief:** Nuke provides image loading, caching, processing, and prefetching for Apple platforms, with UIKit and SwiftUI integrations. Use it when remote-image behavior needs explicit cache policy, progressive rendering, or processing pipelines beyond a minimal loader.
- [Stats - Your Comprehensive macOS System Monitor](https://github.com/stephencelis/SQLite.swift) — iOS Dev Tools · 🔨 AR Madness with Some Mac Sprinkled in — Source repository · Topics: Developer Tools · Persistence & Synchronisation · Swift
  **Published:** `2023-06-15T12:01:05.754Z`
  **NeKI brief:** SQLite.swift wraps SQLite3 in typed Swift query builders and value bindings rather than raw SQL strings alone. Use it when a lightweight relational store needs explicit schemas and transactions without adopting a full object-relational framework.
- [Introspect for SwiftUI - Unleashing the Power of UIKit and AppKit in SwiftUI](https://github.com/intitni/CopilotForXcode) — iOS Dev Tools · 🔨 Swift Power Unleashed & More AI — Source repository · Topics: Swift · SwiftUI · UIKit
  **Published:** `2023-06-08T13:48:24.016Z`
  **NeKI brief:** Describes Copilot for Xcode, focusing on practical tool integration and workflow trade-offs. Use it to evaluate reproducibility, trust boundaries, and debugging steps before adopting the approach in an Xcode project.
- [Handling WebP Images When Using PHPickerViewController](https://swiftsenpai.com/development/webp-phpickerviewcontroller) — iOS Dev Weekly · Issue 611 — Article · Topics: Swift
  **Published:** `26th May 2023`
  **NeKI brief:** Explores Handling WebP Images When Using PHPickerViewController, focusing on even though webp has been around for many years, support. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Window Management with SwiftUI 4](https://www.fline.dev/window-management-on-macos-with-swiftui-4) — SwiftUI Weekly · SwiftUI Weekly - Issue #142 — Article · Topics: Developer Career & Practice · Swift · SwiftUI
  **Published:** `2023-05-15T09:13:45.627Z`
  **NeKI brief:** Explains macOS SwiftUI window management with openWindow and windowResizability while modernizing an existing app. Useful for multi-window designs that need explicit opening, sizing, and lifecycle behavior.
- [Apple Platforms Developer @ Cascable AB](https://cascable.se/jobs) — iOS Dev Weekly · Issue 609 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `12th May 2023`
  **NeKI brief:** Explores Apple Platforms Developer @ Cascable AB, focusing on apple platforms developer @ cascable ab – cascable is a. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [what](https://github.com/uliwitness/AppKitForClassic) — iOS Dev Weekly · Issue 590 — Source repository · Topics: Developer Tools · Xcode
  **Published:** `30th December 2022`
  **NeKI brief:** Explores what, focusing on are you looking for work? there are many exciting opportunities to work with all kinds of companies over on ios dev jobs.. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Apple’s use of AppKit, Mac Catalyst and SwiftUI in macOS](https://blog.timac.org/2022/0818-state-of-appkit-catalyst-swiftui-mac) — iOS Dev Weekly · Issue 572 — Article · Topics: macOS & AppKit · Swift · SwiftUI
  **Published:** `19th August 2022`
  **NeKI brief:** Explores Apple’s use of AppKit, Mac Catalyst and SwiftUI in macOS, focusing on alexandre colucci has been writing posts analysing apple’s use of. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [hiding the iOS home indicator](https://danielsaidi.com/blog/2022/08/01/removing-the-home-indicator-in-swiftui) — iOS Dev Weekly · Issue 571 — Article · Topics: Swift · SwiftUI · UIKit
  **Published:** `12th August 2022`
  **NeKI brief:** Shows how SwiftUI can hide the home indicator through UIKit hosting integration and environment handling. Useful for immersive media or game screens, with careful consideration of discoverability and platform review expectations.
- [SwiftUI Field Notes: DocumentGroup](https://rhonabwy.com/2022/07/19/swiftui-field-notes-documentgroup) — iOS Dev Weekly · Issue 568 — Article · Topics: Swift · SwiftUI
  **Published:** `22nd July 2022`
  **NeKI brief:** Explores SwiftUI Field Notes: DocumentGroup, focusing on talking of the new swiftui navigation apis, joseph heck wrote. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Swift language announcements from WWDC22](https://www.swift.org/blog/swift-language-updates-from-wwdc22) — iOS Dev Weekly · Issue 566 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `8th July 2022`
  **NeKI brief:** Explores Swift language announcements from WWDC22, focusing on it’s easy to get distracted by all the swiftui, uikit. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Accelerate Your iOS DevOps with Granular VM Control in Orka](https://www.macstadium.com/orka) — iOS Dev Weekly · Issue 564 — Article · Topics: Xcode
  **Published:** `24th June 2022`
  **NeKI brief:** Explores Accelerate Your iOS DevOps with Granular VM Control in Orka, focusing on orka 2.0 is now available and includes support for macos. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Requesting App Store reviews in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL25pbGNvYWxlc2NpbmcuY29tL2Jsb2cvUmVxdWVzdGluZ0FwcFN0b3JlUmV2aWV3c0luU3dpZnRVSS8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiJlOGMyZGIwMC05Y2NjLTRkOWItYmI5Ni1kMWU2MDU3NjFhOTciLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiY2E4YjI1ODQtMmEzYy00OWQ1LThlNzktNTM1NjdlNDI1OTY2IiwiaWF0IjoxNjc0MDYyNTU4Ljg3MywiaXNzIjoib3JjaGlkIn0.gpPrkF9rQIPK1vqfb0AZ1jFSBMP_sLOCzneScAJ-voM) — SwiftUI Weekly · SwiftUI Weekly - Issue #107 — Article · Topics: App Distribution & Store Operations · Swift · SwiftUI
  **Published:** `2022-06-21T10:41:22.000Z`
  **NeKI brief:** Shows how to trigger App Store review requests from SwiftUI while respecting the system-controlled presentation. Useful for choosing a meaningful in-app moment and avoiding repeated or disruptive prompts.
- [STTextView](https://christiantietze.de/posts/2022/05/sttextview-textkit-2-editor-without-nstextview) — iOS Dev Weekly · Issue 558 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `13th May 2022`
  **NeKI brief:** Explores STTextView, focusing on talking of textkit 2, in this post, christian tietze talks about marcin krzyzanowski’s syntax highlighting text editor control for macos, sttextview. it’s. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Send Events from SwiftUI to UIKit and Vice Versa](https://www.swiftjectivec.com/events-from-swiftui-to-uikit-and-vice-versa) — iOS Dev Weekly · Issue 557 — Article · Topics: Swift · SwiftUI · UIKit
  **Published:** `6th May 2022`
  **NeKI brief:** Explores Send Events from SwiftUI to UIKit and Vice Versa, focusing on you’ll find plenty of advice that tells you how easy. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Swift Bundler v2](https://forums.swift.org/t/swift-bundler-create-macos-apps-with-swiftpm-instead-of-xcodeprojs/56790) — iOS Dev Weekly · Issue 555 — Article · Topics: Swift · Swift Package Manager · Xcode
  **Published:** `22nd April 2022`
  **NeKI brief:** Explores Swift Bundler v2, focusing on talking of doing a great job at informing people of. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [macOS by Tutorials](https://www.raywenderlich.com/books/macos-by-tutorials) — iOS Dev Weekly · Issue 554 — Tutorial · Topics: macOS & AppKit · Swift · SwiftUI
  **Published:** `15th April 2022`
  **NeKI brief:** Explores macOS by Tutorials, focusing on the article discusses still have the first book on mac. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [The new Guide to NSButton styles](https://mackuba.eu/2021/12/30/new-nsbutton-post) — iOS Dev Weekly · Issue 541 — Article
  **Published:** `14th January 2022`
  **NeKI brief:** Explores The new Guide to NSButton styles, focusing on the article discusses linked to the original version of this. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [The world’s first virtualized M1 CI/CD environment on Bitrise](https://www.bitrise.io/m1-preregister) — iOS Dev Weekly · Issue 538 — Article · Topics: CI/CD & Automation · Performance · Testing
  **Published:** `17th December 2021`
  **NeKI brief:** Explores The world’s first virtualized M1 CI/CD environment on Bitrise, focusing on optimized for speed, stability, and extensibility. the performance of apple. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Debugging on iOS 15 with Xcode 12](https://hybridcattt.com/blog/debugging-on-latest-ios-with-older-xcode) — iOS Dev Weekly · Issue 530 — Article · Topics: Developer Tools · Testing · Xcode
  **Published:** `22nd October 2021`
  **NeKI brief:** Explores Debugging on iOS 15 with Xcode 12, focusing on this time of year is always awkward with versions of. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Implementing Three Column Navigation in SwiftUI](https://serialcoder.dev/text-tutorials/swiftui/implementing-three-column-navigation-in-swiftui) — iOS Dev Weekly · Issue 520 — Tutorial · Topics: Swift · SwiftUI
  **Published:** `13th August 2021`
  **NeKI brief:** Explores Implementing Three Column Navigation in SwiftUI, focusing on three column layouts in ipad and macos apps are more. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [How to show and hide a sidebar in a SwiftUI macOS app](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3NhcnVudy5jb20vcG9zdHMvaG93LXRvLXRvZ2dsZS1zaWRlYmFyLWluLW1hY29zLz91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6ImE1NzBjMjkxLTAwNTgtNGQ5Yy1iNzNkLTVkOTdjNGQ5MTA5ZiIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiI5YWNlYThlZi1mYzk4LTQ3NzYtYmY5NC0wZDg4NzdhZmI3NmIiLCJpYXQiOjE2NzQwNjI2MTguNjA4LCJpc3MiOiJvcmNoaWQifQ.IApUXo-okPnBAjXgfcN97KKTJyRGPcwf0JMLFCMHSE4) — SwiftUI Weekly · SwiftUI Weekly - Issue #70 — Article · Topics: Product Design · Swift · SwiftUI
  **Published:** `2021-08-02T14:01:12.000Z`
  **NeKI brief:** Explains how a macOS SwiftUI sidebar can become unreachable after collapsing and demonstrates recovery through toolbar or command actions. Follow it when testing window navigation states beyond the initial layout.
- [List Selection Based Navigation on macOS](https://lostmoa.com/blog/ListSelectionForNavigation) — iOS Dev Weekly · Issue 518 — Article · Topics: Swift · SwiftUI
  **Published:** `30th July 2021`
  **NeKI brief:** Explores List Selection Based Navigation on macOS, focusing on i’m working on a swiftui app at the moment where. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Implementing a focusable text field in SwiftUI](https://serialcoder.dev/text-tutorials/macos-tutorials/macos-programming-implementing-a-focusable-text-field-in-swiftui) — iOS Dev Weekly · Issue 516 — Tutorial · Topics: macOS & AppKit · Swift · SwiftUI
  **Published:** `16th July 2021`
  **NeKI brief:** Explores Implementing a focusable text field in SwiftUI, focusing on the article discusses enjoyed this article from gabriel theodoropoulos. at. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Creating a licensing system for paid apps in Swift](https://swiftrocks.com/creating-a-license-system-for-paid-apps-in-swift) — iOS Dev Weekly · Issue 502 — Article · Topics: App Distribution & Store Operations · Swift
  **Published:** `9th April 2021`
  **NeKI brief:** Explores Creating a licensing system for paid apps in Swift, focusing on unlike with ios, you have a choice of how you’d. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Setting up a multi-platform SwiftUI project](https://blog.scottlogic.com/2021/03/04/Multiplatform-SwiftUI.html) — iOS Dev Weekly · Issue 499 — Article · Topics: Swift · SwiftUI · Xcode
  **Published:** `19th March 2021`
  **NeKI brief:** Covers Setting up a multi-platform SwiftUI project, focusing on Apple UI composition and interaction design. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [AppKit is Done](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2tlYW4uYmxvZy9wb3N0L2FwcGtpdC1pcy1kb25lP3V0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiZjhkYzQzOWQtNjdhOS00N2IwLWI0NzEtOTE2YzY0MWZlN2FjIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6IjNmMDQyMTgxLWQ3NWUtNGE0ZC1hNmE5LWJjM2UwYjBlYTBkZiIsImlhdCI6MTY3NDA2MjY3OC44OTQsImlzcyI6Im9yY2hpZCJ9.DGocxcXaFPcCXGsnsZ3eHNT1uJHhzVUovNZuaulm2lo) — SwiftUI Weekly · SwiftUI Weekly - Issue #48 — Article · Topics: Swift · SwiftUI
  **Published:** `2021-03-01T13:49:29.000Z`
  **NeKI brief:** Reflects on replacing AppKit in a macOS application and the practical limits of a SwiftUI-first architecture. Use it to assess migration scope, platform gaps, and maintenance costs rather than as a universal prescription.
- [AppKit is Done](https://kean.blog/post/appkit-is-done) — iOS Dev Weekly · Issue 496 — Article · Topics: macOS & AppKit · Swift · SwiftUI
  **Published:** `26th February 2021`
  **NeKI brief:** Reflects on replacing AppKit in a macOS application and the practical limits of a SwiftUI-first architecture. Use it to assess migration scope, platform gaps, and maintenance costs rather than as a universal prescription.
- [Keyboard Navigation in SwiftUI](https://pspdfkit.com/blog/2021/keyboard-navigation-in-swiftui) — iOS Dev Weekly · Issue 494 — Article · Topics: Hardware & Devices · Swift · SwiftUI
  **Published:** `12th February 2021`
  **NeKI brief:** Examines Keyboard Navigation in SwiftUI, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Orchestrate macOS VMs on genuine Apple hardware - Try Orka](https://www.macstadium.com/orkademo) — iOS Dev Weekly · Issue 488 — Article
  **Published:** `1st January 2021`
  **NeKI brief:** Covers Orchestrate macOS VMs on genuine Apple hardware - Try Orka, focusing on Apple UI composition and interaction design. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [Xcode 12.3 is available on the Mac App Store](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2FwcHMuYXBwbGUuY29tL2F6L2FwcC94Y29kZS9pZDQ5Nzc5OTgzNT9tdD0xMiZ1dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6ImUwZDA3MDRlLWU3MDItNGQzOC05YjcxLWYxNmMzODc4NGI1ZSIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiI0ODRkOGEwZi02ZTM1LTQ2ODgtOWJlYy04OTdmYWY5M2I5N2MiLCJpYXQiOjE2NzQwNjI2NzkuNzA4LCJpc3MiOiJvcmNoaWQifQ.Rnp31Lwoh2tW1CP8rFSLWGLLC-3eQlf-aop4b01WMPw) — SwiftUI Weekly · SwiftUI Weekly - Issue #39 — Article · Topics: App Distribution & Store Operations · Swift · Xcode
  **Published:** `2020-12-15T13:53:41.000Z`
  **NeKI brief:** Links to the Xcode 12.3 Mac App Store release from the historical issue. Use it only as release-history context when investigating SDK-era behavior, not as a current installation recommendation.
- [How much time a day do you waste waiting for Xcode builds?](https://blog.kulman.sk/xcode-build-times) — iOS Dev Weekly · Issue 470 — Article · Topics: macOS & AppKit · Xcode
  **Published:** `21st August 2020`
  **NeKI brief:** Measures Xcode build-time contributors and shows practical configuration and dependency changes that affect iteration speed. Follow it when profiling compile bottlenecks before applying project-wide build-setting changes.
- [macOS.swift](https://gist.github.com/jordansinger/72a05653dde9d182b4a5e24f9d19a106) — iOS Dev Weekly · Issue 466 — Source repository · Topics: Developer Tools · Performance · Swift
  **Published:** `24th July 2020`
  **NeKI brief:** Examines macOS.swift, focusing on i’ve been thoroughly enjoying jordan singer’s tweets recently, especially his experimentations with swiftui which he has…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [PointFree snapshot testing](https://github.com/pointfreeco/swift-snapshot-testing) — iOS Dev Weekly · Issue 460 — Source repository · Topics: Accessibility · Developer Tools · Testing
  **Published:** `12th June 2020`
  **NeKI brief:** SnapshotTesting can launch UI tests with a specified content-size category, making large accessibility sizes reproducible in image assertions. Follow it to catch Dynamic Type layout regressions that ordinary interaction tests may miss.
- [diagnostic architecture](https://swift.org/blog/new-diagnostic-arch-overview) — iOS Dev Weekly · Issue 442 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `7th February 2020`
  **NeKI brief:** Examines new diagnostic architecture, focusing on one of those things got much better this week with the passing of the cutoff date for swift 5.2, and the appearance of…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against.
- [SwiftPM Catalog](https://zeezide.com/en/products/swiftpmcatalog) — iOS Dev Weekly · Issue 430 — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **Published:** `15th November 2019`
  **NeKI brief:** Examines SwiftPM Catalog, offering practical guidance on Swift Package Manager integration. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Quickly selected text in an Xcode Playground](https://medium.com/@DanielTavares/quickly-open-selected-text-in-xcode-playground-for-rapid-development-mac-os-56cd07030ef9) — iOS Dev Weekly · Issue 427 — Article · Topics: Xcode
  **Published:** `25th October 2019`
  **NeKI brief:** Examines Quickly selected text in an Xcode Playground, focusing on super simple and smart little hack from daniel tavares that leverages playground and macos automator. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Understanding the iOS Responder Chain](https://swiftrocks.com/understanding-the-ios-responder-chain.html) — iOS Dev Weekly · Issue 394 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `8th March 2019`
  **NeKI brief:** Examines Understanding the iOS Responder Chain, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Path.swift](https://github.com/mxcl/Path.swift) — iOS Dev Weekly · Issue 388 — Source repository · Topics: Developer Tools · Foundation & Data Formats · Swift
  **Published:** `25th January 2019`
  **NeKI brief:** Examines Path.swift, focusing on the url/path manipulation methods in foundation have always been powerful, but also very verbose so this new wrapper…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [SwiftNIO - Event-driven network application framework](https://github.com/apple/swift-nio) — iOS Dev Weekly · Issue 341 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2nd March 2018`
  **NeKI brief:** Examines SwiftNIO, focusing on it’s great to see this major release from the vapor team and it’s encouraging to see that it’s been built on top of…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [this article](https://www.bloomberg.com/news/articles/2017-12-20/apple-is-said-to-have-plan-to-combine-iphone-ipad-and-mac-apps) — iOS Dev Weekly · Issue 332 — Article · Topics: Combine & Reactive Programming · Cross-Platform & Web
  **Published:** `22nd December 2017`
  **NeKI brief:** Reports the historical proposal to unify iPhone, iPad, and Mac app distribution or development. Use it as platform-strategy context when assessing multiplatform architecture, while treating predictions as historical and checking the current Apple deployment model.
- [Container like Devops for iOS development environment](https://veertu.com/getting-started-anka-trials) — iOS Dev Weekly · Issue 318 — Article · Topics: Performance · Testing
  **Published:** `15th September 2017`
  **NeKI brief:** Explores Container like Devops for iOS development environment in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Neural Networks in iOS 10 and macOS](https://www.bignerdranch.com/blog/neural-networks-in-ios-10-and-macos) — iOS Dev Weekly · Issue 257 — Article · Topics: Graphics, Media & Games · macOS & AppKit · Networking
  **Published:** `1st July 2016`
  **NeKI brief:** Explores Neural Networks in iOS 10 and macOS in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [updates to Swift](http://www.russbishop.net/swift-2-beta-2) — iOS Dev Weekly · Issue 204 — Article · Topics: Swift
  **Published:** `26th June 2015`
  **NeKI brief:** Explains updates to Swift with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Force Touch APIs](http://9to5mac.com/2015/03/12/apple-releases-os-x-10-10-3-build-14d98-with-photos-app) — iOS Dev Weekly · Issue 189 — Article
  **Published:** `13th March 2015`
  **NeKI brief:** Reports evidence of dedicated Force Touch APIs in an OS X 10.10.3 build. It is historical reporting from before Force Touch's later platform rollout.
- [Automating OS X app test build distribution across multiple OS versions](http://www.cimgf.com/2013/12/17/automating-os-x-app-test-build-distribution-across-multiple-os-versions) — iOS Dev Weekly · Issue 125 — Article · Topics: Testing
  **Published:** `20th December 2013`
  **NeKI brief:** Explains Automating OS X app test build distribution across multiple OS versions with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a.
- [BeaconEmitter](https://github.com/lgaches/BeaconEmitter) — iOS Dev Weekly · Issue 119 — Source repository · Topics: Developer Tools · Testing
  **Published:** `8th November 2013`
  **NeKI brief:** Provides the BeaconEmitter source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Code Signing and Mavericks](http://furbo.org/2013/10/17/code-signing-and-mavericks) — iOS Dev Weekly · Issue 116 — Article · Topics: App Distribution & Store Operations
  **Published:** `18th October 2013`
  **NeKI brief:** Explains Code Signing and Mavericks with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Coda and Sandboxing](http://www.panic.com/blog/2012/12/coda-and-sandboxing) — iOS Dev Weekly · Issue 72 — Article · Topics: App Distribution & Store Operations · Performance · Security & Privacy
  **Published:** `14th December 2012`
  **NeKI brief:** Explains Coda and Sandboxing with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Build Doom3 on MacOSX with Xcode 4](http://fabiensanglard.net/doom3_macosx/index.php) — iOS Dev Weekly · Issue 18 — Article · Topics: Code Quality · macOS & AppKit · Xcode
  **Published:** `2nd December 2011`
  **NeKI brief:** Explains Build Doom3 on MacOSX with Xcode 4 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [Trees: Effortless Git worktrees in your menu bar](https://github.com/afterxleep/trees) — Not only Swift · Issue 91 — Source repository · Topics: AI Development · Developer Tools · macOS & AppKit
  **NeKI brief:** This source repository covers macOS menu-bar management for Git worktrees. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Distribute your Swift CLIs for macOS](https://swifttoolkit.dev/posts/distribute-swift-clis) — Not only Swift · Issue 79 — Article · Topics: Developer Community & Business · Swift
  **NeKI brief:** This article covers distributing Swift command-line tools for macOS. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [CodeEditorView: A SwiftUI Code Editor for iOS, visionOS, and macOS](https://github.com/mchakravarty/CodeEditorView) — Not only Swift · Issue 79 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Presents a concrete implementation of CodeEditorView: A SwiftUI Code Editor for iOS, visionOS, and macOS. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.
