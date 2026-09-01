# macOS & AppKit

Third-party reading leads collected from NeKI sources. The links may be useful perspectives, but are not vetted recommendations or authoritative API guidance. NeKI publishes routing metadata, not the linked articles' text.

**Scope:** macOS app lifecycle, menu-bar apps, Cocoa, and AppKit integration.

- Last collected: `2026-09-01T10:14:10Z`
- Indexed links shown: **537**

## Direct-source reading

- [Tracking value sources to prevent recursive SwiftUI updates](https://nilcoalescing.com/blog/TrackingValueSourcesToPreventRecursiveSwiftUIUpdates) — Nil Coalescing · article catalogue
  **Published:** `2026-08-04`
  **NeKI brief:** Tags binding writes with a custom SwiftUI transaction value so wrapped text views can recognise their own updates. This avoids repeated large-string comparisons, redundant layout and cursor jumps in UITextView or NSTextView representables.
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
- [Launchpad: A Modern macOS Launchpad With Enhanced Functionality - iOS Dev Tools](https://iosdev.tools/blog/launchpad) — iOS Dev Tools Blog · article catalogue
  **Published:** `2026-02-11T13:12:24+00:00`
  **NeKI brief:** Profiles Launchpad as a Modern macOS Launchpad With Enhanced Functionality. Use it when evaluating whether this tool or package fits an Apple-platform development, testing, or delivery workflow.
- [From Pixel Capture to Metadata - Reimagining Screen Recording Architecture on macOS](https://fatbobman.com/en/posts/screensage-from-pixel-to-meta) — Fatbobman · article catalogue
  **Published:** `2026-02-04T14:12:00.000Z`
  **NeKI brief:** Uses a macOS recorder to connect ScreenCaptureKit and Metal capture, bitrate control, crash recovery, multi-window behavior, and SwiftUI timeline performance. The engineering log helps separate recording architecture from product-facing metadata workflows.
- [Escaping the Mac App Store - Building a Distribution and Sales System for Indie Apps from Scratch](https://fatbobman.com/en/posts/zipic-2-selling-and-distribution) — Fatbobman · article catalogue
  **Published:** `2025-12-22T14:11:00.000Z`
  **NeKI brief:** Builds an independent macOS distribution stack around DMG packaging, Sparkle updates, licensing, payments, and key delivery. The walkthrough exposes operational trade-offs hidden by the Mac App Store's integrated sales model.
- [Solving SwiftUI Pain Points and Performance Bottlenecks - Zipic Development Technical Retrospective](https://fatbobman.com/en/posts/zipic-3-technical-details) — Fatbobman · article catalogue
  **Published:** `2025-12-22T14:10:00.000Z`
  **NeKI brief:** Explains Zipic's SwiftUI adaptation, Core Graphics and PDF compression work, Raycast integration, and performance fixes. The retrospective connects low-level image processing with native macOS interaction and component constraints.
- [Bezel: Mirror Any iPhone on Your Mac - iOS Dev Tools](https://iosdev.tools/blog/bezel) — iOS Dev Tools Blog · article catalogue
  **Published:** `2025-07-18T14:41:19+00:00`
  **NeKI brief:** Profiles Bezel as mirror Any iPhone on Your Mac. Use it when evaluating whether this tool or package fits an Apple-platform development, testing, or delivery workflow.
- [QuickLook: Quickly Preview App Packages - iOS Dev Tools](https://iosdev.tools/blog/quicklook) — iOS Dev Tools Blog · article catalogue
  **Published:** `2025-07-16T14:16:03+00:00`
  **NeKI brief:** Profiles QuickLook as quickly Preview App Packages. Use it when evaluating whether this tool or package fits an Apple-platform development, testing, or delivery workflow.
- [Add launch at login setting to a macOS app](https://nilcoalescing.com/blog/LaunchAtLoginSetting) — Nil Coalescing · article catalogue
  **Published:** `2025-03-21`
  **NeKI brief:** Demonstrates registering a macOS app as a login item with SMAppService. Use it to implement an explicit launch-at-login setting while keeping user control and system preferences aligned.
- [Usage: Keep an Eye on the Activity of Your Devices - iOS Dev Tools](https://iosdev.tools/blog/usage) — iOS Dev Tools Blog · article catalogue
  **Published:** `2025-02-13T14:20:09+00:00`
  **NeKI brief:** Profiles Usage as keep an Eye on the Activity of Your Devices. Use it when evaluating whether this tool or package fits an Apple-platform development, testing, or delivery workflow.
- [How to keep your macOS app's menu bar item running after quitting the app](https://www.polpiella.dev/keep-menu-bar-running-after-quitting-app) — Pol Piella · article catalogue
  **Published:** `2024-12-31T00:00:00.000Z`
  **NeKI brief:** Explains keeping a macOS menu-bar utility available after closing ordinary windows. Use it when separating an app's activation policy, status item, and termination behavior.
- [Maccy: Fast and Lightweight Clipboard Manager for macOS - iOS Dev Tools](https://iosdev.tools/blog/maccy) — iOS Dev Tools Blog · article catalogue
  **Published:** `2024-07-25T09:31:06+00:00`
  **NeKI brief:** Profiles Maccy as fast and Lightweight Clipboard Manager for macOS. Use it when evaluating whether this tool or package fits an Apple-platform development, testing, or delivery workflow.
- [DisplayBuddy: Control Monitor Brightness Directly From Your Device - iOS Dev Tools](https://iosdev.tools/blog/displaybuddy) — iOS Dev Tools Blog · article catalogue
  **Published:** `2024-04-09T19:23:12+00:00`
  **NeKI brief:** Profiles DisplayBuddy as control Monitor Brightness Directly From Your Device. Use it when evaluating whether this tool or package fits an Apple-platform development, testing, or delivery workflow.
- [Type: Take Notes Without Interrupting Your Flow - iOS Dev Tools](https://iosdev.tools/blog/type) — iOS Dev Tools Blog · article catalogue
  **Published:** `2024-02-20T17:58:22+00:00`
  **NeKI brief:** Profiles Type as take Notes Without Interrupting Your Flow. Use it when evaluating whether this tool or package fits an Apple-platform development, testing, or delivery workflow.
- [ScanTexter: Scan Text on Screen and Translate It at Once - iOS Dev Tools](https://iosdev.tools/blog/scantexter) — iOS Dev Tools Blog · article catalogue
  **Published:** `2024-02-03T21:43:46+00:00`
  **NeKI brief:** Profiles ScanTexter as scan Text on Screen and Translate It at Once. Use it when evaluating whether this tool or package fits an Apple-platform development, testing, or delivery workflow.
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

- [Mac App Direct Distribution, DMG Signing & Notarization Guide](https://l.fatbobman.com/w0151-05) — Fatbobman’s Swift Weekly · Issue 151 — Article · Topics: App Distribution & Store Operations
  **Published:** `2026-08-31T12:01:53.025Z`
  **NeKI brief:** Walks through direct macOS distribution with Developer ID signing, DMG creation, notarization, stapling, and Gatekeeper validation. Use it as a release-process checklist while verifying current Apple requirements.
- [Hotspot Meter](https://hotspot-meter.loam.sk/) — iOS Dev Tools · iOS Dev Tools: JoltPhysics, asc-cli, Xtend — Article · Topics: macOS & AppKit
  **Published:** `2026-08-27T20:30:45.555Z`
  **NeKI brief:** Presents a macOS menu-bar utility for tracking Wi-Fi and hotspot usage. It is a product-discovery lead rather than networking API guidance.
- [DynamicNotch: Building Polished Notch and Screen-Edge Interactions for macOS](https://l.fatbobman.com/w0150-7) — Fatbobman’s Swift Weekly · Issue 150 — Article · Topics: Swift · Swift Package Manager · SwiftUI
  **Published:** `2026-08-24T12:03:48.210Z`
  **NeKI brief:** Offers a macOS Swift package for notch-aware SwiftUI surfaces and AppKit-backed floating edge windows. It centralizes clipping, hit testing, safe-area and multi-display geometry, placement, and compact-notch reservations while leaving product state and interaction policy to the host app.
- [KSCrash](https://github.com/kstenerud/KSCrash) — iOS Dev Tools · iOS Dev Tools: Appllama, KSCrash, Reely — Source repository · Topics: Apple Platform Ecosystem · Developer Tools
  **Published:** `2026-08-20T16:31:57.620Z`
  **NeKI brief:** KSCrash is a mature iOS/macOS crash-reporting library that captures native crashes and turns them into reports for later symbolication or delivery. It is useful when comparing in-process crash capture with hosted crash-reporting SDK trade-offs.
- [Macshot](https://macshot.io/) — iOS Dev Tools · iOS Dev Tools: Appllama, KSCrash, Reely — Article · Topics: Graphics, Media & Games
  **Published:** `2026-08-20T16:31:57.620Z`
  **NeKI brief:** Open-source macOS capture utility for annotated screenshots, recordings, scrolling capture, OCR, and uploads. It is useful for inspecting a native developer-facing capture workflow and its annotation feature set.
- [Abendrot](https://abendrot.app/) — iOS Dev Tools · iOS Dev Tools: Appllama, KSCrash, Reely — Article · Topics: Objective-C & Cocoa
  **Published:** `2026-08-20T16:31:57.620Z`
  **NeKI brief:** Open-source macOS screen warmer for night work with external-display support and no app telemetry. Its menu-bar controls and evidence-linked privacy posture are useful reference points for a small native utility.
- [Recording VoiceOver on iOS & macOS](https://www.basbroek.nl/recording-voiceover) — Those Who Swift · Issue 280 — Article · Topics: Accessibility · Testing
  **Published:** `2026-08-19T20:31:22.272Z`
  **NeKI brief:** Explains why iOS screen recording captures VoiceOver directly and how macOS needs virtual audio routing, illustrated with Loopback. The workflow produces clean accessibility demonstrations without recording speakers or room noise.
- [Simple Simulator Manager](https://github.com/Heckscheibe/SimpleSimulatorManager) — iOS Dev Tools · iOS Dev Tools: Simple Simulator Manager, StoreSync, JsonXmlEditor — Source repository · Topics: Developer Tools · macOS & AppKit
  **Published:** `2026-08-13T16:30:38.104Z`
  **NeKI brief:** Provides a macOS menu-bar route to simulator app containers, bundles, Documents, UserDefaults, and App Groups, plus cleanup of unavailable runtimes. It removes repeated CoreSimulator UUID hunting from inspection and disk-maintenance workflows.
- [StoreSync](https://apps.apple.com/us/app/storesync-metadata-manager/id6775701704?mt=12) — iOS Dev Tools · iOS Dev Tools: Simple Simulator Manager, StoreSync, JsonXmlEditor — Article · Topics: App Distribution & Store Operations · Developer Career & Practice · Persistence & Synchronisation
  **Published:** `2026-08-13T16:30:38.104Z`
  **NeKI brief:** Manages App Store Connect metadata, localizations, diffs, keyword tracking, and competitor research from a native macOS client. API keys stay in Keychain while requests go directly to Apple, clarifying its privacy and workflow model.
- [JsonXmlEditor](https://thelittlebakery.org/json-xml-editor) — iOS Dev Tools · iOS Dev Tools: Simple Simulator Manager, StoreSync, JsonXmlEditor — Article · Topics: Developer Tools · Security & Privacy
  **Published:** `2026-08-13T16:30:38.104Z`
  **NeKI brief:** Combines native JSON and XML formatting, validation, comparison, conversion, a REST client, and DTO generation in an offline macOS workspace. Its low-overhead design is a focused alternative to browser and Electron utilities.
- [Bird Chimes](https://apps.apple.com/us/app/bird-chimes-break-reminder/id6767737245?mt=12) — iOS Dev Tools · iOS Dev Tools: Simple Simulator Manager, StoreSync, JsonXmlEditor — Article · Topics: macOS & AppKit
  **Published:** `2026-08-13T16:30:38.104Z`
  **NeKI brief:** Provides configurable macOS hourly cues using bird sounds, with Focus-mode silencing, quiet hours, and menu-bar controls. Its accessibility framing is useful when evaluating ambient time awareness without visual or spoken-clock interruptions.
- [Ironsmith](https://ironsmith.app/) — iOS Dev Tools · iOS Dev Tools: ConsentBus, FoundationModelsKit, Agent Island — Article · Topics: AI Development · Developer Tools · Security & Privacy
  **Published:** `2026-08-06T16:00:49.980Z`
  **NeKI brief:** Offers an open-source macOS menu-bar workflow that turns prompts into sandboxed native SwiftUI utilities, using local models or configured cloud providers and packaging each result as a runnable app.
- [Michael Tsai](https://mjtsai.com/blog/2026/07/24/golden-gate-application-support-protection?ref=ioscodereview.com) — iOS Code Review · Issue 83 — Article · Topics: macOS & AppKit · Security & Privacy
  **Published:** `2026-08-06T06:44:37.000Z`
  **NeKI brief:** Reports macOS 27 extending com.apple.macl protection to selected non-sandboxed Application Support folders through an allowlist in sandboxd, apparently updateable via XProtect. Treat it as an investigation lead for TCC-adjacent access asymmetry, not documented API behavior.
- [Working with Xcode on CI](https://l.fatbobman.com/w0146-02) — Fatbobman’s Swift Weekly · Issue 146 — Article · Topics: Objective-C & Cocoa · Xcode
  **Published:** `2026-07-27T12:04:26.788Z`
  **NeKI brief:** Explains provisioning Xcode on macOS CI, selecting versions with DEVELOPER_DIR, running first-launch setup, and installing simulator or Metal components. It also documents authentication and stale-toolchain trade-offs that prevent a completely hands-off installer.
- [Swift Scribe](https://github.com/FluidInference/swift-scribe) — iOS Dev Tools · iOS Dev Tools: MistKit, Swift Scribe, cmux — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `2026-07-16T16:45:11.086Z`
  **NeKI brief:** Swift Scribe combines local microphone transcription with on-device summarization on current Apple OS releases, without external dependencies. Useful for evaluating a privacy-preserving speech pipeline and its deployment-version constraints.
- [cmux](https://github.com/manaflow-ai/cmux) — iOS Dev Tools · iOS Dev Tools: MistKit, Swift Scribe, cmux — Source repository · Topics: AI Development · Developer Tools · Product Design
  **Published:** `2026-07-16T16:45:11.086Z`
  **NeKI brief:** cmux is a Ghostty-based macOS terminal organized around vertical tabs, notifications, and programmable agent workflows. Useful for evaluating a terminal layout that keeps multiple coding-agent sessions visible and actionable.
- [WhatCable](https://www.whatcable.uk/) — iOS Dev Tools · iOS Dev Tools: MistKit, Swift Scribe, cmux — Article · Topics: macOS & AppKit · Product Design
  **Published:** `2026-07-16T16:45:11.086Z`
  **NeKI brief:** WhatCable is a developer utility or product page. Follow it for the concrete workflow and integration surface described there, while requiring further technical evidence before adoption.
- [5 biggest Liquid Glass changes in iOS 27 and macOS 27](https://www.cultofmac.com/news/liquid-glass-changes-ios-27-macos-27) — Those Who Swift · Issue 275 — Article · Topics: Liquid Glass · macOS & AppKit
  **Published:** `2026-07-15`
  **NeKI brief:** Summarizes major Liquid Glass changes in iOS 27 and macOS 27. Useful for high-level UI migration awareness before checking exact behavior in Apple documentation and SDKs.
- [first iOS 27 public beta](https://appleinsider.com/articles/26/07/13/first-ios-27-macos-27-public-betas-are-out-but-you-should-still-be-careful?ref=ioscodereview.com) — iOS Code Review · Issue 82 — Article · Topics: macOS & AppKit · Swift · SwiftUI
  **Published:** `2026-07-14T19:04:53.000Z`
  **NeKI brief:** Examines first iOS 27 public beta in the context of macOS & AppKit and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [https://www.figma.com/community/file/1651309003795292092/ios-and-ipados-27](https://www.figma.com/community/file/1651309003795292092/ios-and-ipados-27?ref=createwithswift.com) — Create with Swift · Issue 115 — Article · Topics: Apple Platform Ecosystem · Developer Community & Business · Swift
  **Published:** `2026-07-10T15:00:44.000Z`
  **NeKI brief:** Apple has updated its official Figma UI kits for iOS, iPadOS, and macOS 27, giving designers and developers a refreshed set of components, styles, materials, and templates that reflect the latest platform updates. The new kits are useful for creating more…
- [https://www.figma.com/community/file/1651309434229735362/macos-27](https://www.figma.com/community/file/1651309434229735362/macos-27?ref=createwithswift.com) — Create with Swift · Issue 115 — Article · Topics: Developer Community & Business · macOS & AppKit · Swift
  **Published:** `2026-07-10T15:00:44.000Z`
  **NeKI brief:** https://www.figma.com/community/file/1651309434229735362/macos-27. This link is retained as a technical reading lead for Apple-platform development.
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
- [Quay](https://abhi.am/quay) — iOS Dev Tools · iOS Dev Tools: TourKit, MockingKit, MemoryMap — Article · Topics: Developer Tools · macOS & AppKit
  **Published:** `2026-07-09T16:30:20.398Z`
  **NeKI brief:** Quay is a macOS utility from Kumar Abhishek; follow the product page to inspect its stated workflow and positioning as a focused developer tool rather than an implementation article or framework reference.
- [👀 How Warp runs their CI/CD pipelines](https://namespace.so/customers/warp) — iOS CI Newsletter · Issue 90 — Article · Topics: CI/CD & Automation
  **Published:** `2026-07-06T00:00:00.000Z`
  **NeKI brief:** Examines How Warp runs their CI/CD pipelines in the context of CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [SideScreen](https://www.sidescreen.dev/) — iOS Dev Tools · iOS Dev Tools: Apple App Store Scraper, SideScreen, SiteKit — Article · Topics: Cross-Platform & Web
  **Published:** `2026-07-02T19:03:32.109Z`
  **NeKI brief:** SideScreen extends a Mac workspace across an iPad or other display. Follow it for concrete multi-display and window-management behavior, while checking network, performance, and permission requirements.
- [OpenUsage](https://github.com/robinebers/openusage) — iOS Dev Tools · iOS Dev Tools: Apple App Store Scraper, SideScreen, SiteKit — Source repository · Topics: AI Development · App Distribution & Store Operations · Developer Tools
  **Published:** `2026-07-02T19:03:32.109Z`
  **NeKI brief:** OpenUsage presents subscription and usage information in an open-source desktop utility, helping users see where recurring services are being consumed. Useful as a reference for local usage aggregation and transparent cost awareness.
- [Amnesia](https://www.vidursaini.com/amnesia) — iOS Dev Tools · iOS Dev Tools: Apple App Store Scraper, SideScreen, SiteKit — Article · Topics: macOS & AppKit
  **Published:** `2026-07-02T19:03:32.109Z`
  **NeKI brief:** Amnesia is a macOS utility or developer product page. Follow it for the concrete workflow described there, while requiring current documentation before relying on its technical behavior.
- [BLEUnlock](https://github.com/ts1/BLEUnlock) — iOS Dev Tools · iOS Dev Tools: Apple App Store Scraper, SideScreen, SiteKit — Source repository · Topics: Developer Tools · macOS & AppKit
  **Published:** `2026-07-02T19:03:32.109Z`
  **NeKI brief:** BLEUnlock uses Bluetooth LE proximity devices such as an iPhone or Apple Watch to lock and unlock a Mac. Useful for studying a practical CoreBluetooth-to-macOS security workflow and its trust-boundary limitations.
- [Free The Icons](https://weblog.rogueamoeba.com/2026/06/26/free-the-icons) — SwiftLee Weekly · Issue 330 — Article
  **Published:** `2026-06-30T14:07:37.000Z`
  **NeKI brief:** Presents Free The Icons, with practical context for Apple-platform developers evaluating the technique, workflow, or engineering decision described on the page.
- [Reef](https://github.com/gouwsxander/Reef) — iOS Dev Tools · iOS Dev Tools: Reef, CodeIsland, Lucide Swift — Source repository · Topics: Developer Tools
  **Published:** `2026-06-25T18:30:48.034Z`
  **NeKI brief:** Reef is a Swift or Apple-platform developer project. Follow its repository for the concrete problem, public API, and integration examples, then assess maintenance and dependency risk before adoption.
- [CodeIsland](https://github.com/wxtsky/CodeIsland) — iOS Dev Tools · iOS Dev Tools: Reef, CodeIsland, Lucide Swift — Source repository · Topics: AI Development · Developer Tools
  **Published:** `2026-06-25T18:30:48.034Z`
  **NeKI brief:** CodeIsland provides a macOS developer utility or coding workspace. Follow its source and README for concrete interaction and integration behavior, while verifying platform support and maintenance before adoption.
- [Vorssaint](https://github.com/vorssaint/vorssaint-utils) — iOS Dev Tools · iOS Dev Tools: Reef, CodeIsland, Lucide Swift — Source repository · Topics: Developer Career & Practice · Developer Tools · macOS & AppKit
  **Published:** `2026-06-25T18:30:48.034Z`
  **NeKI brief:** Vorssaint-utils provides reusable utilities for Swift or Apple-platform development. Follow its source and tests for concrete helper behavior, then evaluate API stability, naming, and supported Swift versions before adoption.
- [RemindMe](https://github.com/samirpatil2000/remindme) — iOS Dev Tools · iOS Dev Tools: Reef, CodeIsland, Lucide Swift — Source repository · Topics: Developer Tools · Swift
  **Published:** `2026-06-25T18:30:48.034Z`
  **NeKI brief:** RemindMe is a Swift or Apple-platform reminder utility. Follow its source for concrete scheduling, notification, and persistence behavior, while verifying authorization and lifecycle handling before adoption.
- [OpenCore Legacy Patcher](https://dortania.github.io/OpenCore-Legacy-Patcher) — iOS Dev Weekly · Issue 755 — Article · Topics: Developer Tools · Graphics, Media & Games
  **Published:** `19th June 2026`
  **NeKI brief:** Examines Experience macOS just like before. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [AFP (Apple Filing Protocol)](https://appleinsider.com/articles/26/06/10/time-capsule-support-is-dead-in-macos-27-but-you-can-keep-the-hardware-alive) — iOS Dev Weekly · Issue 755 — Article · Topics: macOS & AppKit · Networking
  **Published:** `19th June 2026`
  **NeKI brief:** Examines Apple has terminated support for AFP in macOS 27, effectively killing off the Time Capsule. However, affected owners might be able to revive their hardware. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [M4 Max Mac Studio](https://www.youtube.com/watch?v=SjsmBfkH1K0) — iOS Dev Weekly · Issue 755 — Video · Topics: Networking
  **Published:** `19th June 2026`
  **NeKI brief:** It is truly the end of an era across the board, especially with macOS 27 also quietly pulling the plug on AFP (Apple Filing Protocol) and vintage AirPort Time Capsules. Seeing a networking standard that dates back to System 6 finally get sunsetted really…
- [Headroom](https://headroom.walls.sh/) — iOS Dev Tools · iOS Dev Tools: Footprint, ZMarkupParser, Lettera — Article · Topics: macOS & AppKit
  **Published:** `2026-06-18T16:02:35.381Z`
  **NeKI brief:** Headroom is a macOS utility that surfaces available system memory and related pressure information. Use it while investigating resource-heavy development workflows, treating its readings as an operational aid rather than a replacement for Instruments.
- [PawPause](https://miladsafarzadeh1.github.io/PawPause-mac) — iOS Dev Tools · iOS Dev Tools: Footprint, ZMarkupParser, Lettera — Article · Topics: Developer Tools · Hardware & Devices · macOS & AppKit
  **Published:** `2026-06-18T16:02:35.381Z`
  **NeKI brief:** PawPause is a macOS utility for encouraging breaks or managing screen habits. Follow it for a concrete reminder and productivity workflow, rather than as framework implementation guidance.
- [Quakpit](https://quakpit.app/) — iOS Dev Tools · iOS Dev Tools: Footprint, ZMarkupParser, Lettera — Article · Topics: macOS & AppKit
  **Published:** `2026-06-18T16:02:35.381Z`
  **NeKI brief:** Quakpit is a macOS utility or developer product page. Follow it for the concrete workflow and integration surface described there, while requiring additional evidence before relying on its technical behavior.
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
- [Offsend](https://github.com/Offsend/Offsend) — iOS Dev Tools · iOS Dev Tools: Promptberry, SolidLikeARock, MLX Swift LM — Source repository · Topics: AI Development · Developer Tools · macOS & AppKit
  **Published:** `2026-06-11T16:01:47.008Z`
  **NeKI brief:** Offsend is a GitHub project for sending or transferring content. Follow its README and source to inspect the concrete workflow, protocol, and platform assumptions before treating it as a maintained dependency.
- [MenuBarShelf](https://menubarshelf.talkiplanet.com/) — iOS Dev Tools · iOS Dev Tools: Promptberry, SolidLikeARock, MLX Swift LM — Article · Topics: macOS & AppKit · Swift
  **Published:** `2026-06-11T16:01:47.008Z`
  **NeKI brief:** MenuBarShelf stores frequently used items in a macOS menu-bar shelf. Follow it for concrete quick-access and persistence interactions, while checking current menu-bar and permission behavior.
- [QuickCal](https://github.com/BrianB-22/quickcal) — iOS Dev Tools · iOS Dev Tools: Promptberry, SolidLikeARock, MLX Swift LM — Source repository · Topics: Developer Tools · macOS & AppKit · Swift
  **Published:** `2026-06-11T16:01:47.008Z`
  **NeKI brief:** QuickCal is a GitHub project for fast calendar entry or scheduling workflows. Follow its source and README to inspect the concrete interaction and integration surface before treating it as a maintained dependency.
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
- [TongueType](https://tonguetype.app/) — iOS Dev Tools · iOS Dev Tools: GQLSwift, ScreenPlace, BuildWatch — Article · Topics: AI Development · App Distribution & Store Operations · Personal Essays
  **Published:** `2026-05-28T16:31:04.346Z`
  **NeKI brief:** TongueType is a text or typing utility for macOS. Follow its page for concrete input and productivity interactions, while requiring additional technical evidence before treating it as developer guidance.
- [Rainbow](https://jorviksoftware.cc/utilities/rainbowapple) — iOS Dev Tools · iOS Dev Tools: GQLSwift, ScreenPlace, BuildWatch — Article · Topics: macOS & AppKit
  **Published:** `2026-05-28T16:31:04.346Z`
  **NeKI brief:** Rainbow is a macOS utility for working with or inspecting colors. Follow its page for a concrete developer-design workflow, while checking its supported color models and integration capabilities.
- [Leaf](https://satwiktungala.com/apps) — iOS Dev Tools · iOS Dev Tools: GQLSwift, ScreenPlace, BuildWatch — Article
  **Published:** `2026-05-28T16:31:04.346Z`
  **NeKI brief:** Leaf is a macOS utility or developer-focused application from Satwik Tungala. Follow its page for the concrete workflow described there, while requiring further technical evidence before adoption.
- [SmartClose](https://github.com/mahirozdin/SmartClose) — iOS Dev Tools · iOS Dev Tools: GQLSwift, ScreenPlace, BuildWatch — Source repository · Topics: Developer Tools · macOS & AppKit
  **Published:** `2026-05-28T16:31:04.346Z`
  **NeKI brief:** SmartClose closes or manages macOS applications through a focused utility workflow. Follow its source for concrete process-control and window-state behavior, while reviewing permissions and failure handling before adoption.
- [Tug](https://apps.apple.com/us/app/tug-menu-bar-timer/id6768515427?mt=12) — iOS Dev Tools · iOS Dev Tools: GQLSwift, ScreenPlace, BuildWatch — Article · Topics: macOS & AppKit
  **Published:** `2026-05-28T16:31:04.346Z`
  **NeKI brief:** Tug turns a macOS menu-bar timer into a pull gesture: dragging its tongue sets duration, then naming and releasing starts the timer. It is a concrete interaction-design example built around direct manipulation.
- [SwiftUI Should Become Open-Source](https://macguru.dev/swiftui-should-become-open-source) — Those Who Swift · Issue 268 — Article · Topics: Hardware & Devices · Swift · SwiftUI
  **Published:** `2026-05-27`
  **NeKI brief:** Makes a case for opening SwiftUI's implementation and discusses how transparency could affect the ecosystem. Treat it as opinion and community perspective, useful for framing trade-offs rather than as evidence about Apple's roadmap or framework internals.
- [MacPane](https://github.com/Gigaxel/macpane) — iOS Dev Tools · iOS Dev Tools: MacPane, Livable, Sherlock — Source repository · Topics: Accessibility · Developer Tools · Hardware & Devices
  **Published:** `2026-05-21T16:30:30.985Z`
  **NeKI brief:** MacPane embeds or hosts web content in native macOS panes. Follow its source and README for concrete window, web-view, and application-shell integration patterns.
- [How To Recognize Text In Images With Vision In Swift](https://onmyway133.com/posts/how-to-recognize-text-in-images-with-vision-in-swift) — Those Who Swift · Issue 267 — Article · Topics: Concurrency · Swift
  **Published:** `2026-05-21`
  **NeKI brief:** Shows text recognition in images with Apple's Vision framework. Use it when prototyping OCR, considering request configuration, region or language hints, result confidence, and asynchronous image processing before integrating recognized text into user-visible features.
- [⚠️ GitHub Actions macos-latest image is changing](https://github.blog/changelog/2026-05-14-github-actions-upcoming-image-migrations) — iOS CI Newsletter · Issue 88 — Article · Topics: Developer Tools · macOS & AppKit · Testing
  **Published:** `2026-05-18T00:00:00.000Z`
  **NeKI brief:** Examines GitHub Actions macos-latest image is changing in the context of Developer Tools and macOS & AppKit. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [A guide to macOS window toolbar styles in SwiftUI](https://nilcoalescing.com/blog/AGuideToMacOSToolbarStylesInSwiftUI?ck_subscriber_id=2978342081) — Create with Swift · Issue 107 — Article · Topics: Combine & Reactive Programming · Swift · SwiftUI
  **Published:** `2026-05-15T16:00:08.000Z`
  **NeKI brief:** Natalia covers all the modifiers you need to customize the macOS window toolbar in SwiftUI, from layout styles to title and background visibility.
- [Northstar](https://www.gonorthstar.io/) — iOS Dev Tools · iOS Dev Tools: SwiftSafeUI, Northstar, Ezscreenshots — Article · Topics: App Distribution & Store Operations
  **Published:** `2026-05-14T16:15:24.123Z`
  **NeKI brief:** Northstar combines App Store keyword opportunity scores, competitor metadata and review tracking, App Store Connect synchronization, and an MCP server for LLM-assisted optimization. It is useful when researching an auditable alternative to ad-hoc ASO spreadsheets.
- [TaskMenu](https://github.com/crazytan/TaskMenu) — iOS Dev Tools · iOS Dev Tools: SwiftSafeUI, Northstar, Ezscreenshots — Source repository · Topics: Developer Career & Practice · Developer Tools · macOS & AppKit
  **Published:** `2026-05-14T16:15:24.123Z`
  **NeKI brief:** TaskMenu surfaces Google Tasks in a native macOS menu-bar application. Useful for examining a small API-backed desktop client that keeps task capture accessible without maintaining a full windowed workspace.
- [Using SwiftUI to Build a Mac-assed App in 2026](https://pfandrade.me/blog/mac-assed-swiftui-app) — iOS Dev Weekly · Issue 750 — Article · Topics: Swift · SwiftUI
  **Published:** `8th May 2026`
  **NeKI brief:** Presents using swiftui to build a mac-assed app in 2026 for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [openclick](https://openclick.sh/) — iOS Dev Tools · iOS Dev Tools: AscBuddy, TourKit, Hokusai — Article · Topics: Accessibility · AI Development
  **Published:** `2026-05-07T16:16:37.368Z`
  **NeKI brief:** openclick presents a tool for automating or triggering clicks. Follow it for concrete scheduled-input behavior, while reviewing accessibility permissions, safeguards, and appropriate use before adoption.
- [AeroSpace (Beta)](https://github.com/nikitabobko/AeroSpace) — iOS Dev Tools · iOS Dev Tools: KIF, AeroSpace, FineTune — Source repository · Topics: Developer Tools
  **Published:** `2026-05-01T08:18:29.566Z`
  **NeKI brief:** AeroSpace is a tiling window manager for macOS. Follow its source for concrete workspace, keyboard, and window-placement behavior, while checking configuration and compatibility with current system APIs.
- [FineTune](https://github.com/ronitsingh10/FineTune) — iOS Dev Tools · iOS Dev Tools: KIF, AeroSpace, FineTune — Source repository · Topics: Developer Tools · macOS & AppKit · Navigation & Deep Linking
  **Published:** `2026-05-01T08:18:29.566Z`
  **NeKI brief:** FineTune is a GitHub project for tuning or configuring AI models or outputs. Follow its source for concrete training or evaluation workflows, while verifying supported runtimes, data handling, and resource requirements.
- [MonthBar](https://month.bar/) — iOS Dev Tools · iOS Dev Tools: KIF, AeroSpace, FineTune — Article · Topics: macOS & AppKit
  **Published:** `2026-05-01T08:18:29.566Z`
  **NeKI brief:** MonthBar displays month or calendar information in a macOS menu-bar interface. Follow it for a concrete compact calendar interaction, while checking localization and current system compatibility.
- [Just10](https://github.com/zunguyen/Just10) — iOS Dev Tools · iOS Dev Tools: KIF, AeroSpace, FineTune — Source repository · Topics: Developer Tools · macOS & AppKit
  **Published:** `2026-05-01T08:18:29.566Z`
  **NeKI brief:** Just10 is a Swift or Apple-platform developer project. Follow its repository for the concrete problem, API shape, and usage examples, while verifying supported platforms and maintenance before adoption.
- [Paywall Design Tips That Boost App Sales - Part 2](https://indieappdevs.substack.com/p/indie-app-devs-21) — Those Who Swift · Issue 264 — Article · Topics: Developer Community & Business · Swift · SwiftUI
  **Published:** `2026-04-29`
  **NeKI brief:** Examines Paywall Design Tips That Boost App Sales - Part 2, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [MakLock](https://github.com/dutkiewiczmaciej/MakLock) — iOS Dev Tools · iOS Dev Tools: Yotei, Pica, Revyl — Source repository · Topics: Developer Tools · macOS & AppKit · Security & Privacy
  **Published:** `2026-04-23T16:32:50.159Z`
  **NeKI brief:** MakLock provides a macOS locking or security utility. Follow its source for concrete system-integration and state-transition behavior, while checking permissions and failure handling before relying on it for device protection.
- [Claude Account Switcher](https://github.com/Symbioose/claude-account-switcher) — iOS Dev Tools · iOS Dev Tools: SwiftZilla, Room Service, Pica — Source repository · Topics: Developer Tools · macOS & AppKit
  **Published:** `2026-04-16T16:01:26.478Z`
  **NeKI brief:** Claude Account Switcher manages multiple Claude Code and Codex CLI accounts from a Mac menu bar, showing usage and switching at limits. Useful for studying credential-profile separation and the operational risks of automated account changes.
- [CatBar](https://www.catbar.app/) — iOS Dev Tools · iOS Dev Tools: SwiftZilla, Room Service, Pica — Article · Topics: macOS & AppKit
  **Published:** `2026-04-16T16:01:26.478Z`
  **NeKI brief:** CatBar is a macOS menu-bar utility. Follow its page for concrete compact-status and interaction behavior, while checking permissions and current macOS compatibility.
- [Audio-mcp](https://github.com/BugorBN/audio-mcp) — iOS Dev Tools · iOS Dev Tools: Audio-mcp, Remodex, Pippin — Source repository · Topics: AI Development · Developer Tools
  **Published:** `2026-04-09T17:01:21.324Z`
  **NeKI brief:** Audio-mcp is a GitHub project connecting audio capabilities to an MCP-style tool interface. Follow its source and README to inspect the concrete command surface and integration boundaries before adopting it in an AI-assisted workflow.
- [CodeCleaner](https://code-cleaner.com/) — iOS Dev Tools · iOS Dev Tools: Audio-mcp, Remodex, Pippin — Article · Topics: Xcode
  **Published:** `2026-04-09T17:01:21.324Z`
  **NeKI brief:** CodeCleaner presents a tool for detecting and removing unwanted code or project clutter. Follow it for a concrete maintenance workflow, while checking its supported languages and cleanup rules before relying on it in production.
- [xcodebuild.nvim](https://github.com/wojciech-kulik/xcodebuild.nvim) — iOS Dev Tools · iOS Dev Tools: Superset, xcodebuild.nvim, Mole — Source repository · Topics: Developer Tools · Testing · Xcode
  **Published:** `2026-04-02T18:33:52.413Z`
  **NeKI brief:** xcodebuild.nvim integrates Xcode build actions into Neovim. Follow its source for concrete command, output, and project-discovery behavior, while verifying the required Neovim, Xcode, and environment configuration.
- [OpenAI: Build For iOS And macOS](https://developers.openai.com/codex/use-cases/native-ios-macos-apps) — Those Who Swift · Issue 260 — Article · Topics: AI Development · Apple Platform Ecosystem · Testing
  **Published:** `2026-04-01`
  **NeKI brief:** Examines OpenAI: Build For iOS And macOS, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [CoreDataBrowser](https://github.com/kyletaylor94/CoreDataBrowser) — iOS Dev Tools · iOS Dev Tools: web2wave, CoreDataBrowser, DataStoreKit — Source repository · Topics: Core Data · Developer Tools · Persistence & Synchronisation
  **Published:** `2026-03-19T17:30:50.047Z`
  **NeKI brief:** CoreDataBrowser provides tooling for browsing Core Data stores. Follow its source for concrete persistence inspection and debugging workflows, while checking schema, migration, and read/write safety boundaries.
- [Petal](https://github.com/Aayush9029/petal) — iOS Dev Tools · iOS Dev Tools: web2wave, CoreDataBrowser, DataStoreKit — Source repository · Topics: Developer Tools
  **Published:** `2026-03-19T17:30:50.047Z`
  **NeKI brief:** Petal is a GitHub project offering an Apple-platform developer implementation. Follow its source and README to inspect the concrete API shape, supported platform, and integration trade-offs before using it as a dependency.
- [NothingHere](https://solee0524.github.io/NothingHere) — iOS Dev Tools · iOS Dev Tools: web2wave, CoreDataBrowser, DataStoreKit — Article · Topics: Developer Tools
  **Published:** `2026-03-19T17:30:50.047Z`
  **NeKI brief:** NothingHere is a small GitHub Pages project with minimal or exploratory content. Follow it only for the concrete artifact linked there; it does not currently provide substantial technical reading.
- [Fix iTerm2 Microphone Permission For Claude Code Voice Mode](https://mokacoding.com/blog/how-to-claude-code-voice-mode-iterm-permission) — Those Who Swift · Issue 258 — Article · Topics: Security & Privacy · Swift
  **Published:** `2026-03-18`
  **NeKI brief:** Diagnoses iTerm2 microphone permission for Claude Code voice mode. Useful for tracing macOS permission, host-app, and tool integration boundaries in a concrete workflow.
- [Orcv](https://github.com/jasonjmcghee/orcv) — iOS Dev Tools · iOS Dev Tools: Skills, Speech Swift, Workflow Audit Skill, Orcv — Source repository · Topics: Developer Tools · macOS & AppKit
  **Published:** `2026-03-12T17:30:51.176Z`
  **NeKI brief:** Orcv arranges virtual displays in an infinite zoomable canvas, with savepoints, desktop jumps, window or mouse teleportation, undo/redo, and fullscreen shortcuts. It is useful as a concrete macOS window-management workflow rather than a conventional single-desktop utility.
- [WhyFi](https://whyfi.network/) — iOS Dev Tools · iOS Dev Tools: Skills, Speech Swift, Workflow Audit Skill, Orcv — Article · Topics: macOS & AppKit
  **Published:** `2026-03-12T17:30:51.176Z`
  **NeKI brief:** WhyFi is a networking or connectivity utility. Follow its page for the concrete network workflow described there, while verifying supported protocols, privacy behavior, and platform compatibility.
- [vChewing Input Method](https://vchewing.github.io/README.html) — Fatbobman’s Swift Weekly · Issue 126 — Article · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `2026-03-09T12:02:58.691Z`
  **NeKI brief:** vChewing documents a Chinese input method built for Apple platforms, including its user-facing behavior and project context. Follow it as a case study in text-input engineering, not as a general Swift UI tutorial.
- [IMKSwift](https://github.com/vChewing/IMKSwift) — Fatbobman’s Swift Weekly · Issue 126 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2026-03-09T12:02:58.691Z`
  **NeKI brief:** IMKSwift provides a Swift 6-oriented, @MainActor-isolated base controller for InputMethodKit sessions. Use it when modernizing macOS input methods and avoiding the concurrency hazards inherited from IMKInputController-style callbacks.
- [Time Machine](https://support.apple.com/en-us/104984) — Those Who Swift · Issue 256 — Article
  **Published:** `2026-03-06`
  **NeKI brief:** Reviews Time Machine. Useful as a focused reference for evaluating the described workflow or technology, while validating current platform behavior and project-specific constraints against primary documentation.
- [Automating Mac App Screenshots](https://www.amyworrall.com/blog/automating-mac-app-screenshots) — Those Who Swift · Issue 256 — Article · Topics: App Distribution & Store Operations
  **Published:** `2026-03-06`
  **NeKI brief:** Examines Automating Mac app screenshots — Amy Worrall. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Notepad.exe](https://notepadexe.com/) — iOS Dev Tools · iOS Dev Tools: Notepad.exe, SimTag, Rich HTML Editor — Article
  **Published:** `2026-03-05T17:46:01.942Z`
  **NeKI brief:** Notepad.exe is a Swift-focused playground and editor experiment. Use it to explore lightweight code execution and text-editing workflows outside Xcode, not as a replacement for full project tooling.
- [Rich HTML Editor](https://github.com/Infomaniak/swift-rich-html-editor) — iOS Dev Tools · iOS Dev Tools: Notepad.exe, SimTag, Rich HTML Editor — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `2026-03-05T17:46:01.942Z`
  **NeKI brief:** Infomaniak’s Swift Rich HTML Editor provides an editable rich-text component for Swift applications. Follow its source for concrete HTML, selection, and editor integration choices, then verify supported platforms and serialization behavior.
- [GitSync](https://apps.apple.com/in/app/gitsync-lite/id6759090001?mt=12) — iOS Dev Tools · iOS Dev Tools: Notepad.exe, SimTag, Rich HTML Editor — Article · Topics: Developer Tools · macOS & AppKit
  **Published:** `2026-03-05T17:46:01.942Z`
  **NeKI brief:** GitSync Lite scans developer directories for repositories and reports branch state, uncommitted changes, ahead-behind counts, commit time, and .git size. It is a concrete lead for lightweight local repository monitoring.
- [Notepad.exe — A Notepad for Developers](https://l.fatbobman.com/sb-notepad) — Fatbobman’s Swift Weekly · Issue 125 — Article
  **Published:** `2026-03-02T12:02:09.017Z`
  **NeKI brief:** Presents Notepad.exe as a Mac code editor that runs Swift, Python, JavaScript, and Go files, with an on-device agent and Linux testing. Follow it when assessing lightweight cross-language development environments.
- [Netfluss](https://github.com/rana-gmbh/netfluss) — iOS Dev Tools · iOS Dev Tools: Wax, RespectASO, ThemeKit — Source repository · Topics: Developer Tools · macOS & AppKit
  **Published:** `2026-02-26T17:30:30.625Z`
  **NeKI brief:** Netfluss is a Swift or networking-oriented developer project. Follow its source and README for concrete transport or monitoring behavior, while verifying protocol scope, security, and platform assumptions.
- [Swift System Metrics 1.0 Released](https://www.swift.org/blog/swift-system-metrics-1.0-released) — Those Who Swift · Issue 255 — Article · Topics: Product Design · Swift
  **Published:** `2026-02-25`
  **NeKI brief:** Announces Swift System Metrics 1.0. Useful for collecting process and system measurements in Swift while keeping metric semantics and platform availability explicit.
- [FRTMProxy](https://github.com/ValentinoPalomba/FRTMProxy) — iOS Dev Tools · iOS Dev Tools: FRTMProxy, LLM Checker, PicoClaw — Source repository · Topics: Developer Tools
  **Published:** `2026-02-19T20:00:59.741Z`
  **NeKI brief:** FRTMProxy provides a proxy-related developer tool or library. Follow its source and README for concrete request-routing and inspection behavior, then verify supported protocols, security boundaries, and maintenance before adoption.
- [Usagebar](https://usagebar.com/) — iOS Dev Tools · iOS Dev Tools: FRTMProxy, LLM Checker, PicoClaw — Article · Topics: macOS & AppKit
  **Published:** `2026-02-19T20:00:59.741Z`
  **NeKI brief:** Usagebar presents usage information in a macOS status-bar interface. Follow it for concrete monitoring and compact-display patterns, while verifying the metrics, data sources, and current system compatibility.
- [CodexBar](https://codexbar.app/) — iOS Dev Tools · iOS Dev Tools: DevScroll, FeaturesKit, HeC - Unofficial Hetzner Cloud — Article · Topics: macOS & AppKit
  **Published:** `2026-02-12T17:15:27.823Z`
  **NeKI brief:** CodexBar is a macOS menu-bar application for monitoring Codex usage and related account limits. It is useful for keeping quota state visible during agent-heavy work, subject to provider changes and the tool’s credential-handling design.
- [Adding an Open Recent Menu in a macOS App](https://swiftdevjournal.com/posts/open-recent-menu) — Those Who Swift · Issue 253 — Article · Topics: Swift
  **Published:** `2026-02-12`
  **NeKI brief:** Adds an Open Recent menu to a SwiftUI app, wiring recent document state into platform menu commands. Useful for macOS document workflows that need persistence, discoverable actions, and correct scene-level ownership.
- [Mark Szymczyk](https://mastodon.world/@swiftdevjournal) — Fatbobman’s Swift Weekly · Issue 122 — Article · Topics: Swift · SwiftUI
  **Published:** `2026-02-09T12:02:48.843Z`
  **NeKI brief:** Mark shows how to use instrument to profile your app, spot views with high update frequency and investigate the roots of unnecessary re-renders.
- [launching a rewrite](https://sparkmailapp.com/blog/all-new-spark) — iOS Dev Weekly · Issue 742 — Article · Topics: Swift
  **Published:** `6th February 2026`
  **NeKI brief:** Examines Spark is more than an email app with a few new features. It. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [full tutorial available](https://www.electronjs.org/docs/latest/tutorial/native-code-and-electron-swift-macos) — iOS Dev Weekly · Issue 742 — Tutorial · Topics: macOS & AppKit · Swift · Testing
  **Published:** `6th February 2026`
  **NeKI brief:** Presents full tutorial available for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Typester](https://github.com/nickustinov/typester-macos) — iOS Dev Tools · iOS Dev Tools: AboutKit, HelpKit, Claude XcodePreviews — Source repository · Topics: Developer Tools · macOS & AppKit
  **Published:** `2026-02-05T21:03:29.009Z`
  **NeKI brief:** Typester is a macOS typing or text utility. Follow its source for concrete input and menu-bar interaction patterns, while verifying permissions and behavior before treating it as a developer dependency.
- [Soniox](https://soniox.com/) — iOS Dev Tools · iOS Dev Tools: AboutKit, HelpKit, Claude XcodePreviews — Article · Topics: macOS & AppKit
  **Published:** `2026-02-05T21:03:29.009Z`
  **NeKI brief:** Soniox provides speech-to-text and transcription APIs. Follow its developer materials for concrete streaming, language, and recognition integration, while verifying current SDK, pricing, and privacy boundaries.
- [Deepgram](https://deepgram.com/) — iOS Dev Tools · iOS Dev Tools: AboutKit, HelpKit, Claude XcodePreviews — Article · Topics: macOS & AppKit
  **Published:** `2026-02-05T21:03:29.009Z`
  **NeKI brief:** Deepgram provides speech-to-text and voice AI APIs for transcription and related audio workloads. Use it when comparing hosted speech services, evaluating latency, language support, pricing, retention, and whether processing requirements permit sending audio off-device.
- [Pinster](https://github.com/nickustinov/pinster-macos) — iOS Dev Tools · iOS Dev Tools: AboutKit, HelpKit, Claude XcodePreviews — Source repository · Topics: Developer Tools · macOS & AppKit
  **Published:** `2026-02-05T21:03:29.009Z`
  **NeKI brief:** Pinster is a macOS utility for managing pinned or saved information. Follow its source for concrete menu-bar and persistence behavior, while checking its supported workflows and current compatibility.
- [Need to debug HTTPS on your iPhone?](https://l.fatbobman.com/sb-proxyman) — Fatbobman’s Swift Weekly · Issue 121 — Article · Topics: Developer Tools
  **Published:** `2026-02-02T12:03:11.621Z`
  **NeKI brief:** Presents Proxyman as a native cross-platform HTTP debugging proxy for capturing, inspecting, and mocking HTTP and HTTPS traffic. Follow it when comparing request-inspection workflows across Apple and other development environments.
- [Commander](https://commanderai.app/) — iOS Dev Tools · iOS Dev Tools: Bullseye, Commander, InAppPurchaseKit — Article · Topics: AI Development · Concurrency · Developer Tools
  **Published:** `2026-01-29T21:12:37.433Z`
  **NeKI brief:** Commander is a macOS utility that exposes actions and workflows from a keyboard-oriented command interface. Follow it for a concrete productivity pattern centered on searchable commands and rapid app control.
- [TighterMenubar](https://apps.apple.com/us/app/tightermenubar/id6751470911?mt=12) — iOS Dev Tools · iOS Dev Tools: Bullseye, Commander, InAppPurchaseKit — Article · Topics: macOS & AppKit
  **Published:** `2026-01-29T21:12:37.433Z`
  **NeKI brief:** TighterMenubar adjusts macOS menu-bar spacing and density to prevent items disappearing behind a notch. Follow it for a focused example of adapting system chrome to constrained desktop display layouts.
- [SwiftUI Alerting with NSAlert](https://medium.com/@itsuki.enjoy/swiftui-alerting-with-nsalert-21bdc3a8e650) — Those Who Swift · Issue 251 — Article · Topics: Developer Community & Business · Swift · SwiftUI
  **Published:** `2026-01-28`
  **NeKI brief:** Examines SwiftUI Alerting with NSAlert, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [MachScope](https://github.com/sadopc/machscope) — iOS Dev Tools · iOS Dev Tools: MachScope, SwiftFindRefs, HealthKit Data Generator — Source repository · Topics: Dependency Injection · Developer Tools · Swift
  **Published:** `2026-01-22T20:01:38.499Z`
  **NeKI brief:** MachScope inspects Mach or low-level process information on Apple platforms. Follow its source for concrete diagnostics and system interfaces, while treating private APIs, permissions, and OS-version behavior as constraints.
- [SwiftFindRefs](https://github.com/michaelversus/SwiftFindRefs) — iOS Dev Tools · iOS Dev Tools: MachScope, SwiftFindRefs, HealthKit Data Generator — Source repository · Topics: Developer Tools · Swift · Xcode
  **Published:** `2026-01-22T20:01:38.499Z`
  **NeKI brief:** SwiftFindRefs searches Swift source for references to symbols. Follow its source for concrete indexing and navigation behavior, while verifying parser/compiler-version support and performance on large workspaces.
- [WhisperShortcut](https://github.com/mgsgde/whisper-shortcut) — iOS Dev Tools · iOS Dev Tools: SwiftAgents, XML Comparator, Colorful — Source repository · Topics: AI Development · Developer Tools · macOS & AppKit
  **Published:** `2026-01-15T18:30:34.396Z`
  **NeKI brief:** WhisperShortcut provides speech-to-text and voice-to-prompt workflows on macOS using Whisper and Gemini integrations. Useful for evaluating local audio capture, transcription handoff, and assistant prompting in a keyboard-driven tool.
- [Icons in Menus Everywhere - Send Help](https://blog.jim-nielsen.com/2025/icons-in-menus) — iOS Dev Weekly · Issue 738 — Article
  **Published:** `9th January 2026`
  **NeKI brief:** I’d say it’s a little unfair to hold Apple to what they published in decades-old Human Interface Guidelines, but the point that Jim Nielsen makes in this post remains valid. Adding an icon to every menu item in a macOS app doesn’t help with usability. It’s…
- [article on the same subject](https://tonsky.me/blog/tahoe-icons) — iOS Dev Weekly · Issue 738 — Article
  **Published:** `9th January 2026`
  **NeKI brief:** I’d say it’s a little unfair to hold Apple to what they published in decades-old Human Interface Guidelines, but the point that Jim Nielsen makes in this post remains valid. Adding an icon to every menu item in a macOS app doesn’t help with usability. It’s…
- [SwiftTerm](https://github.com/migueldeicaza/SwiftTerm) — iOS Dev Tools · iOS Dev Tools: SwiftTerm, Conduit, FRTMTools — Source repository · Topics: Developer Tools · Swift
  **Published:** `2026-01-08T21:14:36.266Z`
  **NeKI brief:** SwiftTerm provides terminal-emulation components in Swift. Follow its source for concrete screen-buffer, escape-sequence, input, and rendering behavior, then evaluate platform and concurrency assumptions before embedding it.
- [provided separately](https://github.com/migueldeicaza/TermKit) — iOS Dev Tools · iOS Dev Tools: SwiftTerm, Conduit, FRTMTools — Source repository · Topics: Developer Tools · Swift · UIKit
  **Published:** `2026-01-08T21:14:36.266Z`
  **NeKI brief:** TermKit supplies terminal UI or command-line components for Swift. Follow its source for concrete terminal layout and interaction abstractions, while verifying its maintenance and supported Apple platforms.
- [Lasso](https://www.thelasso.app/) — iOS Dev Tools · iOS Dev Tools: SwiftTerm, Conduit, FRTMTools — Article
  **Published:** `2026-01-08T21:14:36.266Z`
  **NeKI brief:** Lasso is a macOS utility or developer product page. Follow it for the concrete workflow and interaction model described there, while requiring current documentation before relying on its technical behavior.
- [Asset Catalog Viewer](https://github.com/artemnovichkov/asset-catalog-viewer) — iOS Dev Tools · iOS Dev Tools: Swift Commit Generator, CommonSwiftUI, Asset Catalog Viewer — Source repository · Topics: Apple Platform Ecosystem · Developer Tools · Xcode
  **Published:** `2025-12-31T16:45:21.414Z`
  **NeKI brief:** Asset Catalog Viewer inspects Xcode asset catalogs and their contained resources. Follow its source for concrete catalog parsing and preview behavior, useful when auditing image, color, and app-icon assets outside Xcode.
- [Workspace Manager](https://frafra077.github.io/workspace-manager) — iOS Dev Tools · iOS Dev Tools: Swift Commit Generator, CommonSwiftUI, Asset Catalog Viewer — Article · Topics: Developer Tools
  **Published:** `2025-12-31T16:45:21.414Z`
  **NeKI brief:** Workspace Manager presents a way to organize and reopen development workspaces. Follow it for a concrete project-context workflow, especially when coordinating multiple repositories, terminals, and editor windows.
- [ClaudeBar](https://github.com/tddworks/ClaudeBar) — iOS Dev Tools · iOS Dev Tools: Swift-Parsing, ColorsKit, SwiftUI Indie Stack — Source repository · Topics: AI Development · Developer Tools · macOS & AppKit
  **Published:** `2025-12-25T17:35:11.361Z`
  **NeKI brief:** ClaudeBar monitors Claude, Codex, Antigravity, and Gemini usage quotas from a macOS menu bar. Useful for a compact multi-provider status surface, especially when comparing polling, rate-limit display, and privacy boundaries.
- [PRs MenuBar](https://apps.apple.com/ch/app/prs-menubar/id6754046899?l=en-GB&mt=12) — iOS Dev Tools · iOS Dev Tools: VideoKit, MacsyZones, SwiftUI Routes — Article · Topics: macOS & AppKit
  **Published:** `2025-12-18T17:31:09.014Z`
  **NeKI brief:** PRs MenuBar aggregates pull requests from GitHub, GitLab, Gitea, and Forgejo in a Mac menu-bar workflow. Its multi-account and self-hosted support makes it a concrete lead for developer-status monitoring.
- [VibeProxy](https://github.com/automazeio/vibeproxy) — iOS Dev Tools · iOS Dev Tools: Price Localize App, Swift AI SDK, ThreadCommissionerKit — Source repository · Topics: App Distribution & Store Operations · Developer Tools · macOS & AppKit
  **Published:** `2025-12-11T17:45:25.072Z`
  **NeKI brief:** VibeProxy presents a proxy-oriented developer tool. Follow its source and README for concrete traffic-routing or integration behavior, while verifying protocol support, credentials, and security implications before use.
- [Endel](https://endel.io/) — iOS Dev Tools · iOS Dev Tools: Price Localize App, Swift AI SDK, ThreadCommissionerKit — Article · Topics: App Distribution & Store Operations · macOS & AppKit
  **Published:** `2025-12-11T17:45:25.072Z`
  **NeKI brief:** Endel describes adaptive soundscapes intended to support focus, relaxation, and sleep. Follow it only as a concrete productivity-app example; it is not a technical Apple-platform resource.
- [PortKiller](https://github.com/gupsammy/PortKiller) — iOS Dev Tools · iOS Dev Tools: ObjectBox, RIB, Swon — Source repository · Topics: Developer Tools · macOS & AppKit
  **Published:** `2025-12-04T17:28:54.311Z`
  **NeKI brief:** PortKiller lists processes bound to development ports and can terminate selected listeners from a macOS menu bar. Useful for quickly resolving local server conflicts without repeatedly composing lsof and kill commands.
- [Native macOS AI Client: GPT, Claude, Gemini & Local Models](https://l.fatbobman.com/boltai-week-en) — Fatbobman’s Swift Weekly · Issue 113 — Article · Topics: AI Development
  **Published:** `2025-12-01T12:03:23.979Z`
  **NeKI brief:** Describes BoltAI as a native Mac client that brings hosted and local language models into a desktop workflow. Follow it when comparing developer-oriented AI assistants and the trade-offs of keeping model interaction on-device.
- [imessage-kit](https://github.com/photon-hq/imessage-kit) — Fatbobman’s Swift Weekly · Issue 112 — Source repository · Topics: Developer Tools
  **Published:** `2025-11-24T12:01:09.147Z`
  **NeKI brief:** iMessageKit explores message-style interfaces on Apple platforms despite iMessage itself lacking a public automation API. Use it as a UI and data-model reference, not as evidence that third-party apps can access system conversations.
- [🎥 [WEBINAR RECORDING] Automate your app’s releases with AWS](https://streamyard.com/watch/WfUTdS8snB6i) — iOS CI Newsletter · Issue 81 — Article · Topics: CI/CD & Automation · Developer Tools
  **Published:** `2025-11-24T00:00:00.000Z`
  **NeKI brief:** Summarises FREE WEBINAR] Automate your app’s releases with AWS for Developer Tools. Use it to identify the relevant changes and follow its primary links before relying on version-sensitive details.
- [AppLayoutsUI 2.0](https://www.applayouts.com/ui) — iOS Dev Tools · iOS Dev Tools: AppLayoutsUI 2.0, SettingsKit, SwiftCache — Article · Topics: Swift · SwiftUI
  **Published:** `2025-11-20T16:50:33.113Z`
  **NeKI brief:** AppLayoutsUI provides reusable layouts or interface components for Apple-platform apps. Follow it for concrete UI composition patterns, while checking customization, accessibility, and current platform support.
- [SwiftCache](https://github.com/SudhirGadhvi/SwiftCache-SDK) — iOS Dev Tools · iOS Dev Tools: AppLayoutsUI 2.0, SettingsKit, SwiftCache — Source repository · Topics: Developer Tools · Swift
  **Published:** `2025-11-20T16:50:33.113Z`
  **NeKI brief:** SwiftCache-SDK provides caching functionality for Swift applications. Follow its source and README for concrete key, storage, expiration, and retrieval semantics, then evaluate its thread-safety and persistence behavior.
- [LlamaBarn](https://github.com/ggml-org/LlamaBarn) — iOS Dev Tools · iOS Dev Tools: PostgresNIO, SwiftDisc, SM3 — Source repository · Topics: AI Development · Developer Tools · macOS & AppKit
  **Published:** `2025-11-13T17:02:43.035Z`
  **NeKI brief:** LlamaBarn is an Apple-platform project related to running or managing Llama models. Follow its source for concrete local-inference workflows, while verifying model formats, hardware requirements, and current API boundaries.
- [Subscription Day](https://appps.od.ua/subscription-day) — iOS Dev Tools · iOS Dev Tools: PostgresNIO, SwiftDisc, SM3 — Article · Topics: App Distribution & Store Operations · macOS & AppKit
  **Published:** `2025-11-13T17:02:43.035Z`
  **NeKI brief:** Subscription Day tracks recurring subscriptions on macOS and presents their renewal schedule. Follow it for a concrete utility pattern around calendar-linked reminders, recurring payment visibility, and lightweight personal data management.
- [Pickle](https://pickleformac.app/) — iOS Dev Tools · iOS Dev Tools: Clash X, AnyLanguageModel, HealthKit Data Generator — Article · Topics: Security & Privacy
  **Published:** `2025-11-06T22:32:54.905Z`
  **NeKI brief:** Pickle is a macOS utility or developer product page. Follow it for the concrete workflow described there, while requiring further documentation before relying on its technical behavior.
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
- [iOS Conf SG](https://www.iosconf.sg/) — iOS Dev Tools · iOS Dev Tools: Netrofit, MacPacker, GradientEditor — Article · Topics: macOS & AppKit
  **Published:** `2025-10-30T18:15:32.319Z`
  **NeKI brief:** iOS Conf SG is an Apple-platform developer conference page. It is event promotion rather than technical reading and should normally be excluded from the knowledge index.
- [ARCtic Conference](https://arcticonference.com/) — iOS Dev Tools · iOS Dev Tools: Netrofit, MacPacker, GradientEditor — Article · Topics: Developer Community & Business · macOS & AppKit · Objective-C & Cocoa
  **Published:** `2025-10-30T18:15:32.319Z`
  **NeKI brief:** ARCtic Conference is an Apple-platform developer event covering iOS, visionOS, iPadOS, macOS, and watchOS. This page is an event listing rather than technical reading and should normally remain excluded from the knowledge index.
- [Saving money with self-hosted CI runners](https://jeffverkoeyen.com/blog/2025/10/17/SelfHostingMacMinis) — iOS Dev Weekly · Issue 732 — Article · Topics: Developer Tools
  **Published:** `24th October 2025`
  **NeKI brief:** Examines How this app saved $4000+ every month with self-hosted CI/CD Runners in the context of CI/CD & Automation and Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Jeff Verkoeyen](https://www.threads.com/@featherless) — iOS Dev Weekly · Issue 732 — Article · Topics: Developer Tools
  **Published:** `24th October 2025`
  **NeKI brief:** Jeff Verkoeyen recently decided to see how much it would cost to add CI to his Sidecar app. GitHub Actions is great for the first 3,000 minutes per month, unless you’re using macOS runners, in which case the allowance is 300 minutes. 😬 The other options…
- [Liquid Glass or … something else?](https://mastodon.design/@rafa/115406890660401171) — iOS Dev Weekly · Issue 732 — Article · Topics: Liquid Glass
  **Published:** `24th October 2025`
  **NeKI brief:** Talking of Liquid Glass, Rafael Conde posted some fascinating details about the process of adapting Sketch to macOS Tahoe. Does that mean adopting Liquid Glass? Well, kinda. It’s a really good set of posts, I just wish it were a blog post, as I find threads…
- [Rafael Conde](https://mastodon.design/@rafa) — iOS Dev Weekly · Issue 732 — Article · Topics: Liquid Glass
  **Published:** `24th October 2025`
  **NeKI brief:** The public Mastodon profile identifies Rafael Conde and exposes the author's profile and published posts without authentication.
- [Menu Drop](https://sindresorhus.com/menu-drop) — iOS Dev Tools · iOS Dev Tools: GitHub Feedback SDK, CornerCraft, Appbot — Article · Topics: macOS & AppKit
  **Published:** `2025-10-23T17:57:34.511Z`
  **NeKI brief:** Menu Drop is a macOS menu-bar utility from Sindre Sorhus. Follow its page for concrete compact-menu interaction behavior, while checking permissions and current macOS compatibility.
- [Introducing ChatGPT Atlas](https://www.youtube.com/watch?v=8UWKxJbjriY) — Those Who Swift · Issue 237 — Video · Topics: AI Development · Cross-Platform & Web
  **Published:** `2025-10-22`
  **NeKI brief:** Reviews Introducing ChatGPT Atlas. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [LaunchPad](https://github.com/kristof12345/Launchpad) — iOS Dev Tools · iOS Dev Tools: col.or, iOS Image Optimizer, LaunchPad — Source repository · Topics: Developer Tools
  **Published:** `2025-10-16T18:35:25.053Z`
  **NeKI brief:** LaunchPad is a macOS launcher or application-navigation utility. Follow its source for concrete discovery and launch behavior, while checking permissions and compatibility with current application lifecycle APIs.
- [SwiftUI Concentric Rectangle & Concentric Corners in iOS 26](https://www.youtube.com/watch?v=VFnidjiH750) — Those Who Swift · Issue 236 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2025-10-15`
  **NeKI brief:** Explores SwiftUI's ConcentricRectangle and concentric-corner clipping APIs through per-corner radii, container-aware shapes, sheets, popovers, and tiled images. Useful for understanding how nested geometry can preserve visually consistent corners.
- [Peep Screen Time](https://apps.apple.com/us/app/peep-screen-time/id6752670359) — iOS Dev Tools · iOS Dev Tools: SwiftGitX, AsyncLifetime, Navigator — Article · Topics: macOS & AppKit
  **Published:** `2025-10-09T16:31:37.747Z`
  **NeKI brief:** Peep provides visual awareness of time spent in front of a device, turning screen-time monitoring into a lightweight self-regulation prompt. Follow it for a concrete productivity interaction centered on attention and usage feedback.
- [Darling](https://github.com/darlinghq/darling) — iOS Dev Tools · iOS Dev Tools: React-native-enriched, Darling, Aidoku — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2025-10-02T19:15:22.078Z`
  **NeKI brief:** Darling provides a macOS runtime environment on Linux, including DPREFIX-style environments, package and DMG handling, and support for compiling with Apple's toolchain and SDKs. It is useful for understanding the practical limits of cross-platform macOS compatibility.
- [Dockify](https://offfwhite.design/dockify) — iOS Dev Tools · iOS Dev Tools: React-native-enriched, Darling, Aidoku — Article
  **Published:** `2025-10-02T19:15:22.078Z`
  **NeKI brief:** Dockify is a macOS Dock customization utility. Follow its page for concrete icon, layout, or launch behavior, while checking permissions and compatibility with current macOS Dock APIs.
- [9TO5Mac’s report](https://9to5mac.com/2025/09/22/macos-tahoe-26-1-beta-1-mcp-integration) — Fatbobman’s Swift Weekly · Issue 104 — Article · Topics: AI Development · macOS & AppKit
  **Published:** `2025-09-29T12:00:38.726Z`
  **NeKI brief:** Reports beta evidence of MCP-related integration in macOS Tahoe. Use it only as an early signal for system-level agent support, then validate actual APIs, availability, and permissions against Apple's released documentation.
- [Adopting the New Window Controls in iPadOS 26](https://l.fatbobman.com/w0104-01) — Fatbobman’s Swift Weekly · Issue 104 — Article · Topics: macOS & AppKit
  **Published:** `2025-09-29T12:00:38.726Z`
  **NeKI brief:** Shows how iPadOS 26 window controls and a macOS-like menu bar change the windowing experience. Follow it when adapting multiwindow layouts and deciding which controls belong to the system chrome versus the app interface.
- [Benjamin Button Reviews macOS](https://l.fatbobman.com/w0104-04) — Fatbobman’s Swift Weekly · Issue 104 — Article · Topics: Liquid Glass · Testing
  **Published:** `2025-09-29T12:00:38.726Z`
  **NeKI brief:** Reviews macOS through the Benjamin Button utility’s perspective and feature set. Follow it as a product-oriented macOS observation, not as a technical implementation guide or platform reference.
- [YoutubeBarPlayer](https://artiomgramatin.github.io/SunnyAAGWebsite/YoutubeBarPlayer.html) — iOS Dev Tools · iOS Dev Tools: LaunchNext, Feather, DeskRest — Article · Topics: Cross-Platform & Web · Developer Tools · Graphics, Media & Games
  **Published:** `2025-09-25T16:45:27.027Z`
  **NeKI brief:** YoutubeBarPlayer plays YouTube videos from a macOS menu bar popover by accepting a pasted link and embedding playback. Follow it for a concrete lightweight media utility interaction without a full browser window.
- [👋 macOS 13 GitHub-hosted images are closing down](https://github.blog/changelog/2025-09-05-github-actions-ai-labeler-and-moderator-with-the-github-models-inference-api) — iOS CI Newsletter · Issue 75 — Article · Topics: AI Development · Developer Tools
  **Published:** `2025-09-21T00:00:00.000Z`
  **NeKI brief:** Examines Automatically triage and moderate GitHub issues in the context of AI Development and Developer Career & Practice. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Layout Guidelines](https://marioaguzman.github.io/design/layoutguidelines) — iOS Dev Weekly · Issue 727 — Article · Topics: Developer Tools
  **Published:** `19th September 2025`
  **NeKI brief:** Presents layout guidelines for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Toolbar Guidelines](https://marioaguzman.github.io/design/toolbarguidelines) — iOS Dev Weekly · Issue 727 — Article · Topics: Developer Tools
  **Published:** `19th September 2025`
  **NeKI brief:** Presents toolbar guidelines for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Swift-Build GitHub Action](https://l.fatbobman.com/w0102-07) — Fatbobman’s Swift Weekly · Issue 102 — Article · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-09-15T12:03:30.479Z`
  **NeKI brief:** Provides a GitHub Action for building and testing Swift packages across platforms. Follow it when setting up matrix-based package validation and comparing CI workflows for Linux, macOS, and other supported targets.
- [detailed introduction](https://brightdigit.com/tutorials/swift-build) — Fatbobman’s Swift Weekly · Issue 102 — Tutorial · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-09-15T12:03:30.479Z`
  **NeKI brief:** Explains using the swift-build GitHub Action to run Swift Package Manager builds and tests on macOS and Linux. Use it as a compact cross-platform CI starting point before adding caching, matrices, or release artifacts.
- [AppKitUI](https://l.fatbobman.com/w0102-08) — Fatbobman’s Swift Weekly · Issue 102 — Article · Topics: Observation & State Management · Swift · SwiftUI
  **Published:** `2025-09-15T12:03:30.479Z`
  **NeKI brief:** Provides an AppKit UI toolkit that simplifies creating and managing NSView content with Swift. Follow it when evaluating reusable macOS UI abstractions that complement SwiftUI without hiding AppKit ownership and lifecycle details.
- [ReerJSON](https://github.com/reers/ReerJSON) — iOS Dev Tools · iOS Dev Tools: Subprocess, ReerJSON, Haptic Video Sync — Source repository · Topics: Developer Tools · Product Design
  **Published:** `2025-09-11T20:39:49.146Z`
  **NeKI brief:** ReerJSON provides JSON parsing or serialization helpers for Swift. Follow its source and tests for concrete decoding behavior and error handling, then evaluate compatibility with Codable and project data models.
- [How Large is That File?](https://l.fatbobman.com/w0101-03) — Fatbobman’s Swift Weekly · Issue 101 — Article
  **Published:** `2025-09-08T12:03:42.721Z`
  **NeKI brief:** Investigates how macOS file sizes can diverge because extended attributes are counted differently across tools and system versions. Follow it when diagnosing filesystem-size discrepancies involving metadata, APFS, and Finder-style reporting.
- [QuickRecorder](https://github.com/lihaoyun6/QuickRecorder) — iOS Dev Tools · iOS Dev Tools: IQListKit, Radar, HapticPlayer — Source repository · Topics: Developer Tools · Performance
  **Published:** `2025-09-04T15:31:16.101Z`
  **NeKI brief:** QuickRecorder is a lightweight macOS recorder built around ScreenCaptureKit, covering screen capture and related recording controls. Useful for examining a native capture workflow when producing reproducible demos or test evidence.
- [Join the beta here!](https://testflight.apple.com/join/jNkgt4mf) — SwiftLee Weekly · Issue 286 — Article · Topics: App Distribution & Store Operations · Testing
  **Published:** `2025-08-26T14:12:25.000Z`
  **NeKI brief:** Links to join the TestFlight here, a concrete TestFlight distribution page for evaluating the referenced iOS build anonymously.
- [Schedule-A-Click](https://apps.apple.com/us/app/schedule-a-click/id6747453453) — iOS Dev Tools · iOS Dev Tools: Votice, SwiftMCP, NetworkKit — Article · Topics: macOS & AppKit
  **Published:** `2025-08-21T17:28:34.537Z`
  **NeKI brief:** Schedule-A-Click triggers mouse clicks through countdown timers or scheduled times, with use cases including testing and accessibility. It is a concrete automation lead for repeatable macOS interaction timing.
- [Hidden Bar](https://github.com/dwarvesf/hidden) — iOS Dev Tools · iOS Dev Tools: SparkDI, SwiftNetworkRequest, TranscriptDebugMenu — Source repository · Topics: Developer Tools · macOS & AppKit
  **Published:** `2025-08-07T19:48:09.291Z`
  **NeKI brief:** Hidden Bar hides or reveals macOS menu-bar items to manage limited horizontal space. Follow its source for concrete menu-bar status-item behavior and system integration, while checking current macOS compatibility.
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
- [Applite](https://github.com/milanvarady/Applite) — iOS Dev Tools · iOS Dev Tools: Picasso, YoutubeTranscript, Applite — Source repository · Topics: Developer Career & Practice · Developer Tools · Swift
  **Published:** `2025-07-17T18:57:30.320Z`
  **NeKI brief:** Applite is a macOS graphical client for Homebrew package management. Follow its source for concrete package discovery, installation, and update workflows, while checking privilege and repository assumptions.
- [Windowing on iPadOS (Or How I Learned to Love the Backlog Bomb)](https://captainswiftui.substack.com/p/windowing-on-ipados-or-how-i-learned) — Those Who Swift · Issue 223 — Article · Topics: macOS & AppKit · Swift · SwiftUI
  **Published:** `2025-07-16`
  **NeKI brief:** Danny explores the new iPadOS 26 windowing system showing how to implement resizable, interactive windows in SwiftUI, use environment actions like openWindow and pushWindow, and set custom placements.
- [⚠️ Important updates to GitHub-hosted macOS runners](https://github.blog/changelog/2025-07-11-upcoming-changes-to-macos-hosted-runners-macos-latest-migration-and-xcode-support-policy-updates) — iOS CI Newsletter · Issue 72 — Article · Topics: Developer Tools · macOS & AppKit · Testing
  **Published:** `2025-07-14T00:00:00.000Z`
  **NeKI brief:** Examines Important updates to GitHub-hosted macOS runners in the context of Developer Tools and macOS & AppKit. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [FlashSpace](https://github.com/wojciech-kulik/FlashSpace) — iOS Dev Tools · iOS Dev Tools: FluidAudio, PlayCover, FlashSpace — Source repository · Topics: Developer Tools
  **Published:** `2025-07-10T20:12:55.159Z`
  **NeKI brief:** FlashSpace is a macOS window and workspace manager. Follow its source for concrete workspace, shortcut, and window-placement behavior, while checking permissions and compatibility with current macOS Spaces.
- [AltTab](https://alt-tab-macos.netlify.app/) — iOS Dev Tools · iOS Dev Tools: FluidAudio, PlayCover, FlashSpace — Article · Topics: macOS & AppKit
  **Published:** `2025-07-10T20:12:55.159Z`
  **NeKI brief:** AltTab Pro presents a macOS window-switching utility that exposes windows through a fast keyboard-driven workflow. Follow it for a concrete example of replacing the default app-switching interaction with a focused menu-bar tool.
- [QuickLook for IPA & APK](https://apps.apple.com/us/app/quicklook-for-ipa-apk/id6746680688) — iOS Dev Tools · iOS Dev Tools: QuickLook, ASO.report, GitProbe — Article
  **Published:** `2025-07-03T19:16:57.125Z`
  **NeKI brief:** QuickLook for IPA and APK adds Finder previews and thumbnails for mobile application packages without extracting or installing them. Follow it for a concrete package-inspection workflow that exposes metadata early in a developer’s process.
- [Meet the Inspector View in SwiftUI](https://serialcoder.dev/text-tutorials/swiftui/meet-the-inspector-view-in-swiftui) — Those Who Swift · Issue 221 — Tutorial · Topics: Swift · SwiftUI
  **Published:** `2025-07-02`
  **NeKI brief:** Examines Meet the Inspector View in SwiftUI, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Automatic Observation Tracking in UIKit and AppKit](https://steipete.me/posts/2025/automatic-observation-tracking-uikit-appkit) — iOS Dev Weekly · Issue 716 — Article · Topics: macOS & AppKit · Swift · UIKit
  **Published:** `27th June 2025`
  **NeKI brief:** Explores automatic Observation tracking in UIKit and AppKit. Use it when imperative views should react to observable model reads without manually registering broad notifications.
- [AlwaysOnTop](https://github.com/itsabhishekolkha/AlwaysOnTop) — iOS Dev Tools · iOS Dev Tools: Create Custom Symbols, MoPromoteKit, SyntaxKit — Source repository · Topics: Developer Tools · macOS & AppKit
  **Published:** `2025-06-26T19:24:23.404Z`
  **NeKI brief:** AlwaysOnTop keeps selected macOS windows above other windows. Follow its source for concrete window-level and menu-bar integration, while checking accessibility permissions and behavior across Spaces and full-screen apps.
- [Escape from Tutorial Hell](https://sarahreichelt.gumroad.com/l/iqdry) — iOS Dev Weekly · Issue 715 — Tutorial · Topics: Graphics, Media & Games
  **Published:** `20th June 2025`
  **NeKI brief:** Is there an irony in the title of Sarah Reichelt’s new book when her previous book was named “macOS by Tutorials“? Maybe! 😂 But it doesn’t make the problem people face any less real. How do you transition from following a YouTube video or blog article to…
- [macOS by Tutorials](https://sarahreichelt.gumroad.com/l/oximx) — iOS Dev Weekly · Issue 715 — Tutorial · Topics: Graphics, Media & Games
  **Published:** `20th June 2025`
  **NeKI brief:** Presents macos by tutorials for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Iconed](https://github.com/jaywcjlove/iconed) — iOS Dev Tools · iOS Dev Tools: App Store Screenshot Tester, Iconed, ChessKit, — Source repository · Topics: Developer Tools
  **Published:** `2025-06-19T14:20:14.930Z`
  **NeKI brief:** Iconed is a project for generating or managing application icons. Follow its source for concrete asset-generation and export behavior, while checking required formats and App Store submission constraints.
- [WebView Is Finally Coming to SwiftUI](https://danielsaidi.com/blog/2025/06/10/webview-is-finally-coming-to-swiftui) — Those Who Swift · Issue 219 — Article · Topics: Swift · Swift Package Manager · SwiftUI
  **Published:** `2025-06-19`
  **NeKI brief:** Discusses the emerging native SwiftUI web-view direction and its implications for replacing representable wrappers. Useful for migration planning, while verifying availability and behavior against the target SDK.
- [Exploring AI: Cosine Similarity for RAG using Accelerate and Swift](https://www.rudrank.com/exploring-ai-cosine-similarity-rag-accelerate-swift) — Those Who Swift · Issue 195 — Article · Topics: AI Development · Swift
  **Published:** `2025-06-18`
  **NeKI brief:** Uses cosine similarity and Accelerate for RAG in Swift. Useful for connecting vector math, embedding search, and performance considerations in an Apple-platform retrieval pipeline.
- [macOS Tahoe forces all app icons into iOS squircles](https://lapcatsoftware.com/articles/2025/6/2.html) — SwiftLee Weekly · Issue 276 — Article · Topics: Cross-Platform & Web
  **Published:** `2025-06-17T14:10:56.000Z`
  **NeKI brief:** Explains macOS Tahoe forces all app icons into iOS squircles, focusing on the underlying Apple-platform behavior and the implementation trade-offs relevant to production code.
- [Virtualizing macOS 26 Tahoe](https://eclecticlight.co/2025/06/11/virtualising-macos-26-tahoe) — Fatbobman’s Swift Weekly · Issue 88 — Article · Topics: macOS & AppKit
  **Published:** `2025-06-12T02:52:10.753Z`
  **NeKI brief:** Examines virtualizing macOS Tahoe and the practical changes around the new release. Use it when assessing test or CI environments that depend on virtual machines and need version-specific constraints.
- [macOS Tahoe Brings a New Disk Image Format](https://eclecticlight.co/2025/06/12/macos-tahoe-brings-a-new-disk-image-format) — Fatbobman’s Swift Weekly · Issue 88 — Article · Topics: macOS & AppKit
  **Published:** `2025-06-12T02:52:10.753Z`
  **NeKI brief:** Explains Tahoe's new disk-image format and its operational implications. Use it when build, test, packaging, or virtualization workflows manipulate disk images and may need compatibility planning across macOS releases.
- [Ice](https://github.com/jordanbaird/Ice) — iOS Dev Tools · iOS Dev Tools: Bezel, Footprint, AppRouter — Source repository · Topics: Developer Career & Practice · Developer Tools · macOS & AppKit
  **Published:** `2025-06-05T19:50:55.283Z`
  **NeKI brief:** Ice manages macOS menu-bar items and hidden status icons. Follow its source for concrete menu-bar layout and interaction behavior, while checking current macOS compatibility and permission boundaries.
- [Syncthing](https://github.com/syncthing/syncthing-macos) — iOS Dev Tools · iOS Dev Tools: OneSignal iOS SDK, Syncthing, Flex — Source repository · Topics: Developer Tools · macOS & AppKit
  **Published:** `2025-05-29T19:34:37.258Z`
  **NeKI brief:** Syncthing for macOS synchronizes files across devices without a central cloud service. Follow its source for concrete peer discovery, replication, and conflict behavior, while reviewing security and operational trade-offs.
- [Reminders MenuBar](https://github.com/DamascenoRafael/reminders-menubar) — iOS Dev Tools · iOS Dev Tools: OneSignal iOS SDK, Syncthing, Flex — Source repository · Topics: Developer Tools · macOS & AppKit
  **Published:** `2025-05-29T19:34:37.258Z`
  **NeKI brief:** Reminders MenuBar is a macOS menu-bar utility for creating or viewing reminders. Follow its source to inspect a focused EventKit-style workflow and the concrete choices used for quick task capture.
- [Building a Dev Tool](https://dasdom.dev/building-a-dev-tool) — Those Who Swift · Issue 216 — Article · Topics: Hardware & Devices
  **Published:** `2025-05-28`
  **NeKI brief:** Builds a development tool and discusses its implementation path. Useful as a focused example for evaluating tooling UX, local workflows, and the boundary between an app feature and a developer utility.
- [Bullseye](https://apps.apple.com/app/id6741164141) — iOS Dev Tools · iOS Dev Tools: Bullseye, ProgressUI, Harmonize — Article · Topics: Swift · SwiftUI
  **Published:** `2025-05-22T17:27:20.321Z`
  **NeKI brief:** Bullseye provides a native interface for viewing and managing Apple Ads campaigns, including keyboard shortcuts, toolbar customization, and dark mode. It is a concrete example of replacing a web-only marketing workflow with a Mac app.
- [MenuScores](https://github.com/daniyalmaster693/MenuScores) — iOS Dev Tools · iOS Dev Tools: Bullseye, ProgressUI, Harmonize — Source repository · Topics: Developer Tools · macOS & AppKit
  **Published:** `2025-05-22T17:27:20.321Z`
  **NeKI brief:** MenuScores displays live sports scores in a macOS menu-bar or notch-oriented surface. Useful as a compact example of polling, transient status presentation, and constrained desktop UI layout.
- [ShutdownScheduler](https://github.com/ihugang/ShutdownScheduler) — iOS Dev Tools · iOS Dev Tools: MYCloudKit, SwiftUX, Deploy Path — Source repository · Topics: Developer Tools · macOS & AppKit
  **Published:** `2025-05-15T18:46:45.755Z`
  **NeKI brief:** ShutdownScheduler schedules Mac shutdown or related power actions. Follow its source for concrete scheduling and system-command behavior, while reviewing permission, cancellation, and failure handling before relying on it.
- [LogUI](https://eclecticlight.co/2025/03/14/browse-your-macs-log-with-logui) — Fatbobman’s Swift Weekly · Issue 83 — Article · Topics: Objective-C & Cocoa
  **Published:** `2025-05-12T12:02:48.422Z`
  **NeKI brief:** Shows how LogUI opens multiple views over unified macOS logs with independent searches and filters. Use it when application launch noise makes Console difficult to navigate and parallel focused log queries speed diagnosis.
- [Why Some Mac Apps Launch Slowly: A Follow-Up](https://lapcatsoftware.com/articles/2025/5/1.html) — Those Who Swift · Issue 213 — Article · Topics: Cross-Platform & Web
  **Published:** `2025-05-07`
  **NeKI brief:** Investigates slow Mac app launch behavior. Useful for separating startup work, system factors, and application initialization when diagnosing launch performance outside iOS.
- [Build Your First Apple Multiplatform App](https://www.youtube.com/watch?v=SQmbABVS9d0) — Those Who Swift · Issue 213 — Video
  **Published:** `2025-05-07`
  **NeKI brief:** Reviews Build Your First Apple Multiplatform App. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Simular](https://www.simular.ai/simular-for-macos) — iOS Dev Tools · iOS Dev Tools: GrowASO, XcodeBuild MCP, Compot — Article · Topics: AI Development · macOS & AppKit
  **Published:** `2025-05-01T14:50:23.226Z`
  **NeKI brief:** Simular for macOS provides AI-assisted interaction or automation capabilities. Follow its product page for concrete screen-understanding and action workflows, while checking processing location, permissions, and reliability before adoption.
- [Macopy](https://macopy.kk-web.link/) — iOS Dev Tools · iOS Dev Tools: GrowASO, XcodeBuild MCP, Compot — Article · Topics: Hardware & Devices
  **Published:** `2025-05-01T14:50:23.226Z`
  **NeKI brief:** Macopy is a macOS utility for copying or managing clipboard content. Follow its page for concrete capture and paste behavior, while checking persistence, permissions, and privacy before adoption.
- [Loving SwiftUI, missing UIKit.](https://collin.blog/2025/04/24/loving-swiftui-missing-uikit) — SwiftUI Weekly · SwiftUI Weekly - Issue #214 — Article · Topics: Swift · SwiftUI · UIKit
  **Published:** `2025-04-28T13:32:59.660Z`
  **NeKI brief:** Reflects on SwiftUI strengths and UIKit capabilities that developers may still miss. Useful as balanced migration context when deciding where a hybrid implementation remains the lower-risk product choice.
- [DataScout](https://data-scout.pages.dev/) — iOS Dev Tools · iOS Dev Tools: AppsMan, ErrorKit, DataScout — Article · Topics: Core Data · Cross-Platform & Web · Persistence & Synchronisation
  **Published:** `2025-04-24T13:08:49.536Z`
  **NeKI brief:** Data Scout is a data-exploration project presented as a developer product. Inspect its concrete workflow when comparing small utility apps, data presentation choices, and the cost of maintaining a focused independent product.
- [UBI](https://github.com/houseabsolute/ubi) — Fatbobman’s Swift Weekly · Issue 79 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2025-04-14T12:01:43.772Z`
  **NeKI brief:** ubi installs precompiled command-line tool binaries from GitHub releases rather than building them locally. Use it when developer-tool setup must be fast and repeatable across machines, while checking release provenance and platform artifacts.
- [the Vapor team built an action that uses Swiftly under the hood and that installs any version of Swift you want as part of your GitHub Actions workflows](https://github.com/vapor/swiftly-action) — iOS CI Newsletter · Issue 65 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2025-04-06T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for the Vapor team built an action that uses Swiftly under the hood and that installs any version of Swift you…, relevant to Developer Tools and Swift. Inspect its implementation, open issues, and release state before adopting the approach.
- [🚀 How to automate App Store screenshot generation for macOS apps](https://www.jessesquires.com/blog/2025/03/24/automate-perfect-mac-screenshots) — iOS CI Newsletter · Issue 65 — Article · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Community & Business
  **Published:** `2025-04-06T00:00:00.000Z`
  **NeKI brief:** Walks through how to automate App Store screenshot generation for macOS apps, with practical context for App Distribution & Store Operations and CI/CD & Automation. Use it when implementing the workflow, while checking current tool and platform versions before copying the setup.
- [AppleAI](https://github.com/bunnysayzz/AppleAI) — iOS Dev Tools · iOS Dev Tools: WinWinKit, ASO.dev, NeoBrutalism — Source repository · Topics: AI Development · Developer Tools · macOS & AppKit
  **Published:** `2025-04-03T14:55:54.485Z`
  **NeKI brief:** AppleAI is a GitHub project exploring Apple-platform AI capabilities. Follow its source for concrete framework calls and integration experiments, while verifying availability, privacy boundaries, and current Apple API contracts independently.
- [Introducing swiftly 1.0](https://www.swift.org/blog/introducing-swiftly_10) — Those Who Swift · Issue 208 — Article · Topics: Developer Career & Practice · Foundation & Data Formats · Swift
  **Published:** `2025-04-02`
  **NeKI brief:** This technical resource covers Swiftly 1.0 as a Swift toolchain manager. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [EncodeDecode](https://apps.apple.com/us/app/encodedecode-url-encoding/id6739855060) — iOS Dev Tools · iOS Dev Tools: RevenueFlo, ChatLayout, HandySwift — Article · Topics: macOS & AppKit
  **Published:** `2025-03-27T21:08:09.510Z`
  **NeKI brief:** EncodeDecode applies context-aware URL encoding to hosts, paths, queries, and components, with a fallback for arbitrary text. Follow it for a concrete developer utility centered on correct URL representation.
- [iMCP](https://github.com/loopwork-ai/iMCP) — Fatbobman’s Swift Weekly · Issue 76 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `2025-03-24T12:01:29.089Z`
  **NeKI brief:** iMCP is a macOS MCP server that brokers access to local calendar, contacts, messages, reminders, and weather data. Use it to inspect permission-aware system-data tool design before connecting an agent to personal information.
- [Choosing Optimism about iOS 19](https://david-smith.org/blog/2025/03/17/optimism) — iOS Dev Weekly · Issue 704 — Article · Topics: Developer Community & Business
  **Published:** `21st March 2025`
  **NeKI brief:** The page covers “Choosing Optimism about iOS 19” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Coding](https://youtu.be/EFmxPMdBqmU) — iOS Dev Weekly · Issue 704 — Video
  **Published:** `21st March 2025`
  **NeKI brief:** The YouTube page provides the publicly viewable Coding video and its associated metadata.
- [Dock](https://dock-app.com/) — iOS Dev Tools · iOS Dev Tools: Dock, Clippets, ReviewKit — Article · Topics: App Distribution & Store Operations · Developer Career & Practice
  **Published:** `2025-03-20T17:08:58.928Z`
  **NeKI brief:** Dock is a macOS utility that augments or reorganizes the system Dock experience. Follow it for a concrete example of extending desktop navigation, while checking its compatibility and scope on current macOS versions.
- [Building a MCP Server in Swift](https://adamwulf.me/2025/03/building-a-mcp-server-in-swift) — Those Who Swift · Issue 206 — Article · Topics: AI Development · Swift
  **Published:** `2025-03-19`
  **NeKI brief:** Describes Building a MCP Server in Swift, focusing on practical tool integration and workflow trade-offs. Use it to evaluate reproducibility, trust boundaries, and debugging steps before adopting the approach in an Xcode project.
- [MaClicker](https://github.com/WorldOfBasti/MaClicker) — iOS Dev Tools · iOS Dev Tools: Swift GraphQL Codegen, HandySwiftUI, Surge — Source repository · Topics: Developer Tools · Swift
  **Published:** `2025-03-13T19:20:57.517Z`
  **NeKI brief:** MaClicker is a small macOS auto-clicker implemented as a focused utility. Useful for examining global input automation and the permission boundary such tools require, rather than treating simulated clicks as ordinary app events.
- [📺 Turning your Swift command-line apps into beautiful macOS apps](https://www.swiftyplace.com/blog/building-macos-utiltiy-apps) — iOS CI Newsletter · Issue 63 — Article · Topics: CI/CD & Automation · macOS & AppKit · Swift
  **Published:** `2025-03-09T00:00:00.000Z`
  **NeKI brief:** Examines Turning your Swift command-line apps into beautiful macOS apps in the context of CI/CD & Automation and macOS & AppKit. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Peek](https://prateekkeshari.gumroad.com/l/peek) — iOS Dev Tools · iOS Dev Tools: Statused, Compot, FreemiumKit — Article · Topics: AI Development · macOS & AppKit
  **Published:** `2025-03-06T18:01:47.698Z`
  **NeKI brief:** Peek is a paid developer resource or utility distributed through Gumroad. Use the page to inspect its stated workflow and scope, verifying ownership, licensing, updates, and whether it solves a concrete development problem before purchase.
- [DeskMinder](https://appps.od.ua/deskminder) — iOS Dev Tools · iOS Dev Tools: Statused, Compot, FreemiumKit — Article · Topics: macOS & AppKit
  **Published:** `2025-03-06T18:01:47.698Z`
  **NeKI brief:** DeskMinder is a macOS productivity utility that monitors desk activity and encourages breaks. Its product page provides a concrete example of packaging timer, reminder, and menu-bar interactions into a focused native tool.
- [Creating macOS Menu Bar App in SwiftUI](https://clive819.github.io/posts/creating-macos-menu-bar-app-in-swiftui) — Those Who Swift · Issue 204 — Article · Topics: macOS & AppKit · Swift · SwiftUI
  **Published:** `2025-03-05`
  **NeKI brief:** Builds a macOS menu-bar app with SwiftUI. Useful for understanding menu-bar lifecycle, scene configuration, and the platform-specific constraints that differ from a regular windowed app.
- [LinksKit](https://github.com/FlineDev/LinksKit) — iOS Dev Tools · iOS Dev Tools: PrettyPrintedJSON, LinksKit, Hex — Source repository · Topics: Developer Tools
  **Published:** `2025-02-27T16:23:55.746Z`
  **NeKI brief:** LinksKit is a Swift library for working with links or link-related UI. Follow the repository for concrete model and interaction abstractions, and verify supported platforms and maintenance before integrating it.
- [Hex](https://github.com/kitlangton/Hex) — iOS Dev Tools · iOS Dev Tools: PrettyPrintedJSON, LinksKit, Hex — Source repository · Topics: Architecture · Composable Architecture · Developer Tools
  **Published:** `2025-02-27T16:23:55.746Z`
  **NeKI brief:** Hex provides Swift utilities or UI for hexadecimal data and representation. Follow its source for concrete conversion and formatting behavior, while checking byte-order, validation, and platform integration details.
- [Viz](https://github.com/alienator88/Viz) — iOS Dev Tools · iOS Dev Tools: PrettyPrintedJSON, LinksKit, Hex — Source repository · Topics: Developer Tools · Graphics, Media & Games · macOS & AppKit
  **Published:** `2025-02-27T16:23:55.746Z`
  **NeKI brief:** Viz is a GitHub project for visualizing or inspecting data on Apple platforms. Follow its source and examples for concrete rendering and interaction patterns, while verifying the project’s supported frameworks and current maintenance.
- [appstoreconnect-swift-sdk](https://github.com/AvdLee/appstoreconnect-swift-sdk) — iOS CI Newsletter · Issue 62 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Swift
  **Published:** `2025-02-23T00:00:00.000Z`
  **NeKI brief:** Examines this project, focusing on the app store connect api is available and documented! straight away, antoine van der lee jumped into action and started…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [🖥️ Bitrise makes M4 Pro runners available](https://bitrise.io/blog/post/introducing-m4-pro-mac-mini-on-bitrise-more-power-speed-efficiency-for-your-ci-cd) — iOS CI Newsletter · Issue 62 — Article
  **Published:** `2025-02-23T00:00:00.000Z`
  **NeKI brief:** Examines Bitrise makes M4 Pro runners available in the context of Apple-platform engineering. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [InjectionIII](https://apps.apple.com/us/app/injectioniii/id1380446739) — iOS Dev Tools · iOS Dev Tools: TranslateKit, SwiftSoup, InjectionIII — Article · Topics: Objective-C & Cocoa · Personal Essays · Swift
  **Published:** `2025-02-20T19:09:31.201Z`
  **NeKI brief:** InjectionIII adds hot reloading to Swift and Objective-C iOS, tvOS, and macOS projects, allowing implementation and SwiftUI body changes without restarting. Follow it for rapid iteration during UI and behavior development.
- [🍎 Running Xcode in unsupported macOS versions](https://marcelvoss.com/2025/tricking-xcode-into-running-on-an-unsupported-macos) — iOS CI Newsletter · Issue 61 — Article · Topics: Apple Platform Ecosystem · Personal Essays · Xcode
  **Published:** `2025-02-09T00:00:00.000Z`
  **NeKI brief:** Examines Running Xcode in unsupported macOS versions in the context of Apple Platform Ecosystem and Personal Essays. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Diagnostics](https://github.com/wetransfer/diagnostics) — iOS Dev Tools · iOS Dev Tools: Diagnostics, ZIP Foundation, WebKit — Source repository · Topics: Developer Tools · Swift
  **Published:** `2025-02-06T17:32:00.627Z`
  **NeKI brief:** Points to Diagnostics, an open-source implementation or issue with concrete code and discussion that can inform Apple-platform development decisions.
- [WebKit](https://github.com/WebKit/WebKit) — iOS Dev Tools · iOS Dev Tools: Diagnostics, ZIP Foundation, WebKit — Source repository · Topics: Developer Tools · Foundation & Data Formats · Product Design
  **Published:** `2025-02-06T17:32:00.627Z`
  **NeKI brief:** WebKit is Apple’s open-source browser engine and framework implementation. Follow the repository for concrete engine architecture and platform behavior, but use current Apple documentation for supported public APIs and guarantees.
- [Swift Build](https://github.com/swiftlang/swift-build) — Fatbobman’s Swift Weekly · Issue 69 — Source repository · Topics: Swift · Swift Package Manager · Xcode
  **Published:** `2025-02-03T12:01:11.391Z`
  **NeKI brief:** This commitment led Apple to open-sourcing Swift Build, a build engine that offers a comprehensive set of build rules for constructing Swift projects.
- [llbuild](https://github.com/swiftlang/swift-llbuild) — Fatbobman’s Swift Weekly · Issue 69 — Source repository · Topics: Swift · Swift Package Manager · Xcode
  **Published:** `2025-02-03T12:01:11.391Z`
  **NeKI brief:** llbuild is the lower-level build-system engine used by Swift tooling. Use it to inspect dependency scheduling and incremental compilation foundations, while keeping its implementation role distinct from the higher-level Swift Build repository.
- [Godot IDE for Mac](https://godotengine.org/download/macos) — iOS Dev Weekly · Issue 697 — Article · Topics: macOS & AppKit
  **Published:** `31st January 2025`
  **NeKI brief:** Examines ¹ Yes, there’s already a Godot IDE for Mac. It’s fine, but it doesn’t feel at home on macOS, whereas Xogot lives and breathes the HIG. ❤️ Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [it’s beautiful](https://www.theverge.com/2024/6/12/24176917/macos-sequoia-wallpaper-classic-macintosh-icons-susan-kare) — iOS Dev Weekly · Issue 697 — Article · Topics: macOS & AppKit
  **Published:** `31st January 2025`
  **NeKI brief:** This isn’t new by any means, but I only found it this week and it’s beautiful! 😱 Give it a try if you haven’t already.
- [DevCleaner](https://github.com/vashpan/xcode-dev-cleaner) — iOS Dev Tools · iOS Dev Tools: SwiftUIX, Vapor, DevCleaner — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Xcode
  **Published:** `2025-01-30T15:53:21.682Z`
  **NeKI brief:** DevCleaner is a macOS tool for finding and removing development artifacts. Follow its source for concrete path discovery and cleanup rules, while verifying exactly which Xcode, simulator, and build files it can delete.
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
- [read a happy story](https://weblog.rogueamoeba.com/2024/12/13/the-developers-who-came-in-from-the-cold) — iOS Dev Weekly · Issue 693 — Article
  **Published:** `3rd January 2025`
  **NeKI brief:** It’s so nice to read a happy story about something that could have so easily become impossible with various changes to macOS over the years.
- [EasyStash](https://github.com/onmyway133/EasyStash) — iOS Dev Tools · iOS Dev Tools: Sourcery, FengNiao, EasyStash — Source repository · Topics: Developer Tools
  **Published:** `2024-12-26T21:45:51.591Z`
  **NeKI brief:** EasyStash provides a lightweight cross-platform persistence wrapper for Apple-platform apps. Use it to evaluate a small storage abstraction for simple values, while confirming its serialization, migration, and thread-safety limits against your data requirements.
- [VoiceOver on macOS: First Time, Huh?](https://www.basbroek.nl/macos-voiceover-first-time-huh) — SwiftLee Weekly · Issue 251 — Article · Topics: Accessibility · macOS & AppKit
  **Published:** `2024-12-23T10:34:05.000Z`
  **NeKI brief:** Presents VoiceOver on macOS: First Time, Huh?, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [KVKCalendar](https://github.com/kvyatkovskys/KVKCalendar) — iOS Dev Tools · iOS Dev Tools: KVKCalendar, PLCrashReporter, Mackup — Source repository · Topics: Developer Tools
  **Published:** `2024-12-19T15:19:02.752Z`
  **NeKI brief:** KVKCalendar provides calendar UI components for Swift applications. Follow its source and examples for concrete event, date, layout, and interaction patterns, then evaluate localization and accessibility behavior.
- [PLCrashReporter](https://github.com/microsoft/plcrashreporter) — iOS Dev Tools · iOS Dev Tools: KVKCalendar, PLCrashReporter, Mackup — Source repository · Topics: Developer Tools · Product Design
  **Published:** `2024-12-19T15:19:02.752Z`
  **NeKI brief:** PLCrashReporter captures and symbolizes crash reports from Apple-platform applications. Follow its source for concrete crash-diagnostics, signal-handling, and report-format behavior, while checking compatibility and privacy implications before integrating it.
- [Getting rid of macOS Sequoia Screen Recording permission alerts](https://9to5mac.com/2024/09/24/macos-sequoia-screen-recording-permission-nags-can-now-be-permanently-vanquished) — SwiftLee Weekly · Issue 250 — Article · Topics: macOS & AppKit · Swift
  **Published:** `2024-12-17T10:30:53.000Z`
  **NeKI brief:** Discusses Getting rid of macOS Sequoia Screen Recording permission alerts, extracting concrete engineering practices and trade-offs that Apple-platform developers can apply when evaluating this workflow.
- [CoreStore](https://github.com/JohnEstropia/CoreStore) — iOS Dev Tools · iOS Dev Tools: Compose Multiplatform, CoreStore, SourceKitten — Source repository · Topics: Core Data · Developer Career & Practice · Developer Tools
  **Published:** `2024-12-05T17:49:51.669Z`
  **NeKI brief:** CoreStore provides a higher-level Swift interface for Core Data persistence. Follow its source for concrete stack setup, transaction, and object-management abstractions, then compare them with the project’s existing persistence boundaries.
- [StatusBuddy](https://github.com/insidegui/StatusBuddy) — iOS Dev Tools · iOS Dev Tools: CoreData Studio, Swift Crypto, StatusBuddy — Source repository · Topics: App Distribution & Store Operations · Developer Tools · macOS & AppKit
  **Published:** `2024-11-28T18:43:21.075Z`
  **NeKI brief:** StatusBuddy monitors or presents macOS system status from a focused utility. Follow its source for concrete status-item and system-integration patterns, while checking current macOS APIs and resource usage.
- [Should we use Apple Intelligence for Text and Inputs in SwiftUI using writingToolsBehavior](https://medium.com/@jpmtech/should-we-use-apple-intelligence-for-text-and-inputs-in-swiftui-using-writingtoolsbehavior-49d662ce5ede) — SwiftLee Weekly · Issue 247 — Article · Topics: AI Development · Swift · SwiftUI
  **Published:** `2024-11-26T15:01:34.000Z`
  **NeKI brief:** Evaluates writingToolsBehavior for Apple Intelligence text assistance in SwiftUI inputs. Use it when deciding whether system writing tools fit an editor, checking availability, privacy expectations, and user-control requirements.
- [did you know that you can create screensavers with Swift??????](https://digitalbunker.dev/creating-a-macos-screensaver-in-swiftui?ref=createwithswift.com) — Create with Swift · Issue 37 — Article · Topics: Developer Tools · macOS & AppKit · Swift
  **Published:** `2024-11-22T16:00:12.000Z`
  **NeKI brief:** And as a curiosity... did you know that you can create screensavers with Swift??????
- [Learn how to use NSDockTilePlugIn](https://github.com/marioaguzman/NSDockTilePlugIn-Example) — iOS Dev Weekly · Issue 688 — Source repository · Topics: Developer Tools
  **Published:** `22nd November 2024`
  **NeKI brief:** Examines I like this quick macOS tip and tutorial from Mario Guzmán about dynamic dock icons on macOS. It’s worth noting that: Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [VirtualBuddy](https://github.com/insidegui/VirtualBuddy) — iOS Dev Tools · iOS Dev Tools: VirtualBuddy, Facebook SDK, SocketRocket — Source repository · Topics: Developer Tools · Testing
  **Published:** `2024-11-21T15:40:40.034Z`
  **NeKI brief:** Guilherme Rambo has been experimenting with macOS 11’s Virtualization framework and the Ventura beta, and just like that, he now has a new app! It’s open-source, so feel free to look at how it works or contribute something!
- [SocketRocket](https://github.com/facebookincubator/SocketRocket) — iOS Dev Tools · iOS Dev Tools: VirtualBuddy, Facebook SDK, SocketRocket — Source repository · Topics: Developer Tools
  **Published:** `2024-11-21T15:40:40.034Z`
  **NeKI brief:** SocketRocket implements a WebSocket client for iOS and macOS. Follow its source for concrete connection, delegate, and message-handling behavior, then evaluate protocol, concurrency, and maintenance compatibility with current networking code.
- [ChatGPT for macOS can now work with Xcode](https://dimillian.medium.com/chatgpt-for-macos-can-now-work-with-xcode-28cecc9decf7) — SwiftLee Weekly · Issue 246 — Article · Topics: AI Development · macOS & AppKit · Xcode
  **Published:** `2024-11-19T12:58:52.000Z`
  **NeKI brief:** Presents ChatGPT for macOS can now work with Xcode, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [NetShears](https://github.com/divar-ir/NetShears) — iOS Dev Tools · iOS Dev Tools: Gravatar iOS SDK, GRDB, NetShears — Source repository · Topics: Developer Tools · Swift
  **Published:** `2024-11-14T14:46:00.891Z`
  **NeKI brief:** NetShears is a networking or traffic-inspection project. Follow its source and README for concrete filtering or request-handling behavior, while assessing protocol coverage, data exposure, and maintenance before adoption.
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
- [🔌 Beware of this argument when using xcodebuild and plugins](https://elegantchaos.com/2024/10/11/xcodebuild-platforms-and-plugins.html) — iOS CI Newsletter · Issue 53 — Article · Topics: Cross-Platform & Web · Xcode
  **Published:** `2024-10-20T00:00:00.000Z`
  **NeKI brief:** Examines Beware of this argument when using xcodebuild and plugins in the context of Cross-Platform & Web and Xcode. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [repeated screen recording permission prompts](https://tidbits.com/2024/09/23/how-to-avoid-sequoias-repetitive-screen-recording-permissions-prompts) — iOS Dev Weekly · Issue 683 — Article
  **Published:** `18th October 2024`
  **NeKI brief:** Presents repeated screen recording permission prompts, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [coming in 15.1](https://9to5mac.com/2024/10/07/macos-sequoia-screen-recording-popups) — iOS Dev Weekly · Issue 683 — Article · Topics: macOS & AppKit
  **Published:** `18th October 2024`
  **NeKI brief:** Examines With today’s release of macOS Sequoia 15.1 beta 6, Apple is making another change to screen recording permissions. The company. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Cross-Platform macOS/Windows Application Developed Using Swift 6](https://forums.swift.org/t/example-of-a-cross-platform-macos-windows-application-developed-using-swift-6/74591) — iOS Dev Weekly · Issue 679 — Article · Topics: AI Development · Cross-Platform & Web · Swift
  **Published:** `20th September 2024`
  **NeKI brief:** Presents cross-platform macos/windows application developed using swift 6 for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [available on GitHub](https://github.com/fbarbat/fellmonger) — iOS Dev Weekly · Issue 679 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `20th September 2024`
  **NeKI brief:** Presents available on github for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Github contribution graph with Swift Charts](https://www.artemnovichkov.com/blog/github-contribution-graph-swift-charts) — SwiftUI Weekly · SwiftUI Weekly - Issue #199 — Article · Topics: Developer Tools · Swift
  **Published:** `2024-09-09T19:49:43.177Z`
  **NeKI brief:** Creates a GitHub-style contribution graph with Swift Charts using calendar-shaped data. Useful for practicing custom mark layouts, color scales, and date-based visualization.
- [Codemagic CI/CD for mobile teams](https://codemagic.io/start) — iOS CI Newsletter · Issue 50 — Article · Topics: CI/CD & Automation · Testing · Xcode
  **Published:** `2024-09-08T00:00:00.000Z`
  **NeKI brief:** Examines Codemagic CI/CD for mobile teams in the context of CI/CD & Automation and Testing. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Group container naming in macOS Sequoia](https://www.goldenhillsoftware.com/2024/06/migration-step-in-next-beta-of-unread-for-macos) — iOS Dev Weekly · Issue 677 — Article · Topics: macOS & AppKit · Security & Privacy
  **Published:** `6th September 2024`
  **NeKI brief:** This might be a little obscure, but is probably worth mentioning. If your Mac app uses group containers to share data between your app and its extensions, depending on how you set it up, you might need to move things around. Unfortunately, in a sandboxed…
- [SwiftFormat](https://github.com/nicklockwood/SwiftFormat) — iOS Dev Tools · iOS Dev Tools: R.swift, Alamofire, SwiftFormat — Source repository · Topics: Developer Tools · Product Design · Swift
  **Published:** `2024-09-05T15:57:02.879Z`
  **NeKI brief:** SwiftFormat offers configurable source-formatting rules and a mature command-line workflow. Follow it when comparing formatter policy, rule customization, and repository integration against Apple's swift-format rather than treating formatting as purely cosmetic.
- [🚨 FlyCI Runners to be discontinued on September 30th](https://flyci.net/blog/flyci-discontinue-macos-runners) — iOS CI Newsletter · Issue 49 — Article · Topics: Developer Tools · macOS & AppKit
  **Published:** `2024-08-25T00:00:00.000Z`
  **NeKI brief:** Examines FlyCI Runners to be discontinued on September 30th in the context of Developer Tools and macOS & AppKit. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [CI Wingman feature](https://flyci.net/docs) — iOS CI Newsletter · Issue 49 — Article · Topics: Developer Tools
  **Published:** `2024-08-25T00:00:00.000Z`
  **NeKI brief:** Examines Automatically fix your failing CI/CD builds in the context of CI/CD & Automation and Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [SwiftUI for Mac 2024](https://troz.net/post/2024/swiftui-mac-2024) — iOS Dev Weekly · Issue 675 — Article · Topics: Swift · SwiftUI · Xcode
  **Published:** `23rd August 2024`
  **NeKI brief:** Reviews SwiftUI for macOS in 2024, including windowing, menus, and platform-specific controls. Useful for auditing which shared views need deliberate Mac adaptations.
- [MeshGradients in iOS 18](https://www.youtube.com/watch?v=s_eQZ8rRV8Y) — SwiftUI Weekly · SwiftUI Weekly - Issue #197 — Video · Topics: Graphics, Media & Games
  **Published:** `2024-08-19T10:45:25.615Z`
  **NeKI brief:** Demonstrates mesh gradients introduced for iOS 18 visual effects. Useful for evaluating animated, multicolor backgrounds without manually composing many gradient layers.
- [🧰 Releasing Swift Binaries with GitHub Actions](https://swifttoolkit.dev/posts/releasing-with-gh-actions) — iOS CI Newsletter · Issue 48 — Article · Topics: Developer Tools · Product Design · Swift
  **Published:** `2024-08-11T00:00:00.000Z`
  **NeKI brief:** Examines Releasing Swift Binaries with GitHub Actions in the context of Developer Tools and Product Design. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [FilterMagic](https://apps.apple.com/us/app/filter-magic/id1594986951) — iOS Dev Tools · iOS Dev Tools: FilterMagic, Stevia, Blink Shell — Article · Topics: Graphics, Media & Games
  **Published:** `2024-08-08T14:06:02.007Z`
  **NeKI brief:** FilterMagic exposes Core Image filters for exploring image and video processing without immediately writing a custom Metal shader. Follow it as a concrete visual-development tool for comparing CIFilter effects.
- [ControlRoom](https://github.com/twostraws/ControlRoom) — iOS Dev Tools · iOS Dev Tools: ControlRoom, SwiftDeps, Starscream — Source repository · Topics: Developer Tools · Xcode
  **Published:** `2024-07-25T15:18:00.048Z`
  **NeKI brief:** ControlRoom is a macOS front end for simctl that manages iOS, tvOS, and watchOS Simulator state. Use it for device launch, screenshots, deep links, permissions, or location testing without repeatedly assembling command-line invocations.
- [SwiftUI can be a bit... eager](https://www.attributedstrings.com/swiftui-can-be-a-bit-eager) — SwiftUI Weekly · SwiftUI Weekly - Issue #193 — Article · Topics: Foundation & Data Formats · Swift · SwiftUI
  **Published:** `2024-07-08T08:54:13.719Z`
  **NeKI brief:** Investigates cases where SwiftUI evaluates views or work eagerly. Useful for diagnosing unexpected initialization, expensive computations, and lifecycle assumptions in declarative hierarchies.
- [⚠️ GitHub-hosted macOS runners are changing their selected Xcode version](https://github.com/actions/runner-images/blob/main/images/macos/macos-14-arm64-Readme.md) — iOS CI Newsletter · Issue 45 — Source repository · Topics: Developer Tools · macOS & AppKit · Xcode
  **Published:** `2024-07-01T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for GitHub-hosted macOS runners are changing their selected Xcode version, relevant to Developer Tools and macOS & AppKit. Inspect its implementation, open issues, and release state before adopting the approach.
- [Pricetag](https://macpricetag.com/) — iOS Dev Tools · iOS Dev Tools: Pricetag, Tuist, Snapshots — Article · Topics: App Distribution & Store Operations
  **Published:** `2024-06-27T16:03:43.649Z`
  **NeKI brief:** Pricetag presents a macOS utility for tracking or displaying app pricing. Follow it for concrete price-monitoring behavior, while verifying data sources and update cadence before relying on it.
- [Helm](https://helm-app.com/) — iOS Dev Tools · iOS Dev Tools: Helm, AudioKit, Lottie — Article · Topics: App Distribution & Store Operations
  **Published:** `2024-06-20T13:30:58.118Z`
  **NeKI brief:** Discusses Helm in a public developer resource. Use it to compare the author's concrete workflow and trade-offs with your project constraints, and verify any platform-specific claims against current primary documentation.
- [AudioKit](https://github.com/AudioKit/AudioKit) — iOS Dev Tools · iOS Dev Tools: Helm, AudioKit, Lottie — Source repository · Topics: Developer Tools
  **Published:** `2024-06-20T13:30:58.118Z`
  **NeKI brief:** Provides the public source repository for AudioKit. Inspect its implementation, examples, and issue history to evaluate integration boundaries and maintenance trade-offs before depending on it in an Apple-platform project.
- [🚨 CircleCI is deprecating their Intel macOS runners](https://discuss.circleci.com/t/macos-intel-support-deprecation-in-january-2024/48718) — iOS CI Newsletter · Issue 44 — Article · Topics: macOS & AppKit
  **Published:** `2024-06-16T00:00:00.000Z`
  **NeKI brief:** Examines CircleCI is deprecating their Intel macOS runners in the context of macOS & AppKit. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Installing macOS Sequoia in a Separate APFS Volume](https://adrian.schoenig.me/blog/2024/06/13/installing-macos-sequoia-in-a-separate-volume) — iOS Dev Weekly · Issue 665 — Article · Topics: macOS & AppKit
  **Published:** `14th June 2024`
  **NeKI brief:** Examines I. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Meet AppLayouts, an All-in-One Toolkit to Supercharge Your iOS and macOS App](https://www.applayouts.com/) — iOS Dev Tools · iOS Dev Tools: AppScreen Studio, StringSwitch, getuniversal.link — Article
  **Published:** `2024-06-06T16:11:51.001Z`
  **NeKI brief:** Provides a catalogue of reusable app layout patterns and interface examples. Use it to compare navigation, content hierarchy, and responsive composition ideas before designing a SwiftUI or UIKit screen.
- [📹 Block’s macOS runner migration from in-house to AWS](https://www.youtube.com/watch?v=i-pQwwCZyxs) — iOS CI Newsletter · Issue 43 — Video
  **Published:** `2024-06-02T00:00:00.000Z`
  **NeKI brief:** Records Block’s macOS runner migration from in-house to AWS as a visual walkthrough relevant to Apple-platform engineering. Use it to inspect the demonstrated workflow, then verify version-specific details with current primary sources.
- [Stats](https://github.com/exelban/stats) — iOS Dev Tools · iOS Dev Tools: AppDab, MessageKit, Stats — Source repository · Topics: Developer Tools · macOS & AppKit
  **Published:** `2024-05-16T13:45:55.601Z`
  **NeKI brief:** Stats is a macOS menu-bar system monitor exposing CPU, memory, disk, network, battery, and sensor information. Follow its source for concrete polling and status-item patterns, while checking resource overhead and permissions.
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
- [Rectangle](https://rectangleapp.com/) — iOS Dev Tools · iOS Dev tools: SwiftyLaunch, Rectangle, Screen Sizes — Article · Topics: Developer Career & Practice · Hardware & Devices
  **Published:** `2024-04-04T15:28:44.338Z`
  **NeKI brief:** Rectangle is a macOS window-management utility for keyboard-driven snapping and resizing. Follow its source for concrete accessibility and window-placement integration, while checking current permissions and Spaces behavior.
- [LocalizApp](https://localizapp.dimitrigiani.com/) — iOS Dev Tools · iOS Dev tools: Ducky Model Editor, LocalizApp, Brewer X — Article · Topics: Developer Career & Practice
  **Published:** `2024-03-28T15:43:54.859Z`
  **NeKI brief:** LocalizApp provides tooling for translating or managing application localization. Follow it for concrete string and resource workflows, while verifying supported formats and Xcode integration before adoption.
- [CodeEdit](https://www.codeedit.app/) — iOS Dev Tools · iOS Dev tools: Haptics, CodeEdit, Pastepal — Article
  **Published:** `2024-02-22T14:00:50.078Z`
  **NeKI brief:** CodeEdit is an open-source code editor for Apple platforms. Follow its source for concrete document, editor, extension, and project-management architecture, while checking current feature completeness and platform support.
- [🆕 GitHub-hosted macOS Sonoma runners are now available!](https://github.blog/changelog/2024-01-30-github-actions-macos-14-sonoma-is-now-available) — iOS CI Newsletter · Issue 35 — Article · Topics: Developer Tools · macOS & AppKit · Personal Essays
  **Published:** `2024-02-11T00:00:00.000Z`
  **NeKI brief:** Examines GitHub-hosted macOS Sonoma runners are now available! in the context of Developer Tools and macOS & AppKit. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Badging Premium Features with Menu Badges](https://furnacecreek.org/blog/2024-01-21-badging-premium-features-with-menu-badges) — iOS Dev Weekly · Issue 646 — Article
  **Published:** `2nd February 2024`
  **NeKI brief:** As I read this post, I had fond memories of the old QuickTime “Pro” badges in the old QuickTime 7 Player macOS menus. It was a good way to show what features would unlock with the paid upgrade, and this post from David Sorel shows you how to do something…
- [Wins](https://wins.cool/) — iOS Dev Tools · 🔨 Wins, Bushel, Warp — Article
  **Published:** `2023-12-21T15:03:29.456Z`
  **NeKI brief:** Wins is a productivity or achievement-focused application. Follow its page for the concrete workflow described there, while requiring further technical evidence before treating it as developer reading.
- [Bushel](https://getbushel.app/) — iOS Dev Tools · 🔨 Wins, Bushel, Warp — Article · Topics: Testing
  **Published:** `2023-12-21T15:03:29.456Z`
  **NeKI brief:** Bushel presents a product for managing Apple devices or deployment workflows. Follow it for the concrete administration capabilities described on the page, while verifying platform scope and operational prerequisites.
- [Warp](https://www.warp.dev/) — iOS Dev Tools · 🔨 Wins, Bushel, Warp — Article · Topics: Developer Tools
  **Published:** `2023-12-21T15:03:29.456Z`
  **NeKI brief:** Warp is a modern terminal for developer workflows. Follow its product materials for concrete command, collaboration, and automation features, while checking shell, privacy, and platform integration behavior.
- [Transferable drag & drop on macOS](https://nonstrict.eu/blog/2023/transferable-drag-drop-fails-with-only-FileRepresentation) — iOS Dev Weekly · Issue 640 — Article
  **Published:** `15th December 2023`
  **NeKI brief:** Presents Transferable drag & drop on macOS, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Founder/CTO @ XLIO](https://docs.google.com/document/d/1LMWlg7FMzdHyuILgIONjFprE52Onm8GRAgb2nQJRWlI) — iOS Dev Weekly · Issue 639 — Article · Topics: Graphics, Media & Games · Swift
  **Published:** `8th December 2023`
  **NeKI brief:** Founder/CTO @ XLIO – An opportunity to lead the development of a greenfield project requiring deep macOS integration (this is not “just another” Swift app) which will be installed on hundreds of thousands of devices worldwide. – Remote (within US timezones)…
- [Apple’s use of AppKit, Catalyst, Swift and SwiftUI in macOS Sonoma](https://blog.timac.org/2023/1128-state-of-appkit-catalyst-swift-swiftui-mac) — Fatbobman’s Swift Weekly · Issue 9 — Article · Topics: macOS & AppKit · Swift · SwiftUI
  **Published:** `2023-12-03T22:00:35.768Z`
  **NeKI brief:** Surveys AppKit, Catalyst, Swift, and SwiftUI capabilities on macOS, highlighting interoperability boundaries. Useful for choosing a platform strategy when an app spans native macOS and shared UI code.
- [Create Your Own Step Counter SwiftUI App in 5 Minutes](https://holyswift.app/create-your-own-step-counter-swiftui-app-in-5-minutes) — Fatbobman’s Swift Weekly · Issue 9 — Article · Topics: Swift · SwiftUI
  **Published:** `2023-12-03T22:00:35.768Z`
  **NeKI brief:** Builds a small step-counter app in SwiftUI, connecting motion-related data with observable view state. Use it to trace permission, sensor, and update-flow concerns before extracting production-grade health or fitness architecture.
- [The complete guide to Swift development in Neovim](https://wojciechkulik.pl/ios/the-complete-guide-to-ios-macos-development-in-neovim) — iOS Dev Weekly · Issue 636 — Article · Topics: macOS & AppKit · Swift · Xcode
  **Published:** `17th November 2023`
  **NeKI brief:** Presents the complete guide to swift development in neovim for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [ToDoBar](https://todobar.compzets.com/) — iOS Dev Tools · 🔨 ASO, ToDoBar, EffectsLibrary — Article · Topics: macOS & AppKit
  **Published:** `2023-11-09T14:17:10.440Z`
  **NeKI brief:** ToDoBar presents tasks and reminders from a macOS menu-bar interface. Follow it for concrete quick-entry and notification behavior, while checking persistence and authorization requirements.
- [WishKit](https://www.wishkit.io/?ref=iosdevtool) — iOS Dev Tools · 🔨 SwiftHub, WishKit, Presentify — Article
  **Published:** `2023-10-26T14:13:35.621Z`
  **NeKI brief:** WishKit provides a feedback and feature-request workflow for iOS applications. Follow it for concrete in-app feedback collection and prioritization patterns, while checking SDK, privacy, and storage behavior.
- [LaunchBuddy](https://launchbuddy.app/) — iOS Dev Tools · 🔨 Introducing Bezel, Minify ASO, LaunchBuddy — Article · Topics: Developer Career & Practice
  **Published:** `2023-10-19T14:30:17.945Z`
  **NeKI brief:** LaunchBuddy is a macOS utility for managing or launching development applications and workflows. Follow its page for concrete workspace and process-launch behavior, while checking permissions and current compatibility before adoption.
- [Quinn “The Eskimo!”](https://toot.community/@justkwin) — iOS Dev Weekly · Issue 631 — Article · Topics: App Distribution & Store Operations · Developer Community & Business
  **Published:** `13th October 2023`
  **NeKI brief:** In one way, this article by Nikita Zhuk contains some valuable advice on whether you should subclass URLCache. In another, it’s a reminder of the amazing work that Quinn and other DTS team members and Apple employees do on the developer forums. It’s easy to…
- [🎉 M1 GitHub-hosted runners publicly available!](https://github.blog/changelog/2023-10-02-github-actions-apple-silicon-m1-macos-runners-are-now-available-in-public-beta) — iOS CI Newsletter · Issue 26 — Article · Topics: Developer Tools · macOS & AppKit
  **Published:** `2023-10-08T00:00:00.000Z`
  **NeKI brief:** Examines M1 GitHub-hosted runners publicly available! in the context of Developer Tools and macOS & AppKit. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Sensei](https://cindori.com/sensei) — iOS Dev Tools · Introducing Codeshare, Sensei, ProfileMe — Article · Topics: Performance
  **Published:** `2023-09-28T13:10:04.363Z`
  **NeKI brief:** Sensei provides a customizable macOS material-blur view that goes beyond NSVisualEffectView's public configuration surface. Use it when a desktop UI needs controlled materials, while isolating the visual dependency from core application logic.
- [Understanding Publishers in SwiftUI and Combine](https://medium.com/bumble-tech/understanding-publishers-in-swiftui-and-combine-27806aa78ba1) — SwiftUI Weekly · SwiftUI Weekly - Issue #161 — Article · Topics: Combine & Reactive Programming · Swift · SwiftUI
  **Published:** `2023-09-25T21:58:53.226Z`
  **NeKI brief:** Explains how Combine publishers feed SwiftUI updates and how asynchronous streams compose in an application. Useful when diagnosing event pipelines, selecting operators, and deciding where publisher ownership belongs in a view model.
- [Combine](https://www.swiftbysundell.com/discover/combine) — SwiftUI Weekly · SwiftUI Weekly - Issue #161 — Article · Topics: Combine & Reactive Programming · Swift · SwiftUI
  **Published:** `2023-09-25T21:58:53.226Z`
  **NeKI brief:** Collects Swift by Sundell's Combine material on publishers, operators, and reactive application design. Useful as a navigation hub when maintaining Combine code or comparing legacy pipelines with newer async/await implementations.
- [Considering adding a platform? A word of caution](https://thatvirtualboy.com/remove-macos-catalyst) — iOS Dev Weekly · Issue 628 — Article · Topics: macOS & AppKit
  **Published:** `22nd September 2023`
  **NeKI brief:** Presents Considering adding a platform? A word of caution, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [I18n Studio](https://github.com/i18n-studio/i18n-studio) — iOS Dev Tools · Introducing RemafoX, Statused, I18n Studio — Source repository · Topics: Developer Tools
  **Published:** `2023-09-21T12:20:19.663Z`
  **NeKI brief:** I18n Studio provides tooling for managing localization resources. Follow its source and workflow documentation for concrete string extraction, translation, and catalog handling, while verifying supported Xcode and localization formats.
- [AppKit vs SwiftUI: Stable vs Shiny](https://milen.me/writings/appkit-vs-swiftui-stable-vs-shiny) — iOS Dev Weekly · Issue 622 — Article · Topics: macOS & AppKit · Swift · SwiftUI
  **Published:** `11th August 2023`
  **NeKI brief:** Explores AppKit vs SwiftUI: Stable vs Shiny, focusing on every now and then, it’s worth checking back in on. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [answer to the question was from Sarah Reichelt](https://www.kodeco.com/books/macos-apprentice/v1.0/chapters/18-using-swiftui-in-appkit) — iOS Dev Weekly · Issue 622 — Article · Topics: macOS & AppKit · Swift · SwiftUI
  **Published:** `11th August 2023`
  **NeKI brief:** Explores answer to the question was from Sarah Reichelt, focusing on every now and then, it’s worth checking back in on. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Featuring Maccy, Nuke, & Tuist](https://github.com/p0deje/Maccy) — iOS Dev Tools · 🔨 It's Clipboard Magic (and Other Stuff) — Source repository · Topics: Developer Tools · Security & Privacy
  **Published:** `2023-06-29T13:51:11.661Z`
  **NeKI brief:** Maccy is a macOS clipboard manager with local history and quick retrieval. Follow its source for concrete clipboard monitoring, persistence, and privacy behavior, while checking retention and permission boundaries.
- [Maccy - Lightweight Clipboard Manager for macOS](https://github.com/kean/Nuke) — iOS Dev Tools · 🔨 It's Clipboard Magic (and Other Stuff) — Source repository · Topics: Developer Tools · Product Design
  **Published:** `2023-06-29T13:51:11.661Z`
  **NeKI brief:** Nuke provides image loading, caching, processing, and prefetching for Apple platforms, with UIKit and SwiftUI integrations. Use it when remote-image behavior needs explicit cache policy, progressive rendering, or processing pipelines beyond a minimal loader.
- [Moya 15.0.0](https://github.com/Moya/Moya) — iOS Dev Tools · 🔨 Elevate Swift Networking with Moya & More — Source repository · Topics: Developer Career & Practice · Networking · Swift
  **Published:** `2023-06-22T13:47:30.798Z`
  **NeKI brief:** Moya wraps network requests in a higher-level Swift abstraction over URLSession. Follow its source for concrete target, provider, plugin, and request-testing patterns, then compare them with the project’s networking architecture.
- [Mirador](https://github.com/HyperARCo/Mirador) — iOS Dev Tools · 🔨 AR Madness with Some Mac Sprinkled in — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `2023-06-15T12:01:05.754Z`
  **NeKI brief:** Mirador is an Apple-platform project for inspecting or presenting augmented-reality content. Follow its repository for concrete rendering and interaction code, while verifying device and framework requirements before adoption.
- [Stats - Your Comprehensive macOS System Monitor](https://github.com/stephencelis/SQLite.swift) — iOS Dev Tools · 🔨 AR Madness with Some Mac Sprinkled in — Source repository · Topics: Developer Tools · Persistence & Synchronisation · Swift
  **Published:** `2023-06-15T12:01:05.754Z`
  **NeKI brief:** SQLite.swift wraps SQLite3 in typed Swift query builders and value bindings rather than raw SQL strings alone. Use it when a lightweight relational store needs explicit schemas and transactions without adopting a full object-relational framework.
- [Introspect for SwiftUI - Unleashing the Power of UIKit and AppKit in SwiftUI](https://github.com/intitni/CopilotForXcode) — iOS Dev Tools · 🔨 Swift Power Unleashed & More AI — Source repository · Topics: Swift · SwiftUI · UIKit
  **Published:** `2023-06-08T13:48:24.016Z`
  **NeKI brief:** Describes Copilot for Xcode, focusing on practical tool integration and workflow trade-offs. Use it to evaluate reproducibility, trust boundaries, and debugging steps before adopting the approach in an Xcode project.
- [Handling WebP Images When Using PHPickerViewController](https://swiftsenpai.com/development/webp-phpickerviewcontroller) — iOS Dev Weekly · Issue 611 — Article · Topics: Swift
  **Published:** `26th May 2023`
  **NeKI brief:** Explores Handling WebP Images When Using PHPickerViewController, focusing on even though webp has been around for many years, support. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [WebP](https://developers.google.com/speed/webp) — iOS Dev Weekly · Issue 611 — Article
  **Published:** `26th May 2023`
  **NeKI brief:** The page covers “WebP” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [This Window Is Leaking](https://byla.lt/posts/this-window-is-leaking) — SwiftUI Weekly · SwiftUI Weekly - Issue #143 — Article · Topics: macOS & AppKit · Swift · SwiftUI
  **Published:** `2023-05-22T15:14:28.541Z`
  **NeKI brief:** Diagnoses a macOS SwiftUI window leak caused by replacing an NSWindowDelegate without restoring the original delegate. Useful when bridging AppKit window customization into SwiftUI and tracking lifecycle ownership.
- [Window Management with SwiftUI 4](https://www.fline.dev/window-management-on-macos-with-swiftui-4) — SwiftUI Weekly · SwiftUI Weekly - Issue #142 — Article · Topics: Developer Career & Practice · Swift · SwiftUI
  **Published:** `2023-05-15T09:13:45.627Z`
  **NeKI brief:** Explains macOS SwiftUI window management with openWindow and windowResizability while modernizing an existing app. Useful for multi-window designs that need explicit opening, sizing, and lifecycle behavior.
- [Xamarin.Mac](https://learn.microsoft.com/en-us/xamarin/mac) — iOS Dev Weekly · Issue 609 — Article · Topics: Cross-Platform & Web
  **Published:** `12th May 2023`
  **NeKI brief:** Examines Xamarin.Mac exposes the complete macOS SDK for .NET developers to build native Mac applications using C#. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [React Native for macOS](https://microsoft.github.io/react-native-windows) — iOS Dev Weekly · Issue 609 — Article · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `12th May 2023`
  **NeKI brief:** Examines Build native Windows apps with Javascript and React. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [official desktop showcase](https://microsoft.github.io/react-native-windows/resources-showcase) — iOS Dev Weekly · Issue 609 — Article · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `12th May 2023`
  **NeKI brief:** The React Native for Windows showcase presents official desktop resources and examples for building Windows applications with the framework.
- [Apple Platforms Developer @ Cascable AB](https://cascable.se/jobs) — iOS Dev Weekly · Issue 609 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `12th May 2023`
  **NeKI brief:** Explores Apple Platforms Developer @ Cascable AB, focusing on apple platforms developer @ cascable ab – cascable is a. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [🆕 GitHub Actions: macOS 13 available!](https://github.blog/changelog/2023-04-24-github-actions-macos-13-is-now-available) — iOS CI Newsletter · Issue 15 — Article · Topics: Developer Tools · macOS & AppKit · Personal Essays
  **Published:** `2023-05-07T00:00:00.000Z`
  **NeKI brief:** Examines GitHub Actions: macOS 13 available! in the context of Developer Tools and macOS & AppKit. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [💻 Tartelet: An app to manage self-hosted ephemeral GitHub runners](https://shape.dk/news-and-knowledge/tartelet) — iOS CI Newsletter · Issue 13 — Article · Topics: Developer Tools
  **Published:** `2023-04-09T00:00:00.000Z`
  **NeKI brief:** Examines Tartelet: An app to manage self-hosted ephemeral GitHub runners in the context of Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Tartelet](https://github.com/shapehq/tartelet/wiki/Installing-Tartelet) — iOS CI Newsletter · Issue 13 — Source repository · Topics: Developer Tools
  **Published:** `2023-04-09T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for Tartelet, relevant to Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [open-source code for banner in macOS](https://bitsplitting.org/2023/03/17/spelunking-apples-open-source) — iOS Dev Weekly · Issue 604 — Article
  **Published:** `7th April 2023`
  **NeKI brief:** Examines Since the earliest days of Mac OS X, Apple has complied with the licenses for the dozens of open source components it includes in the OS by posting (sometimes a little belatedly) u. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [⚡️ M1 macOS runners now available on CircleCI](https://circleci.com/blog/m1-mac-resource-class) — iOS CI Newsletter · Issue 12 — Article · Topics: Developer Tools
  **Published:** `2023-03-26T00:00:00.000Z`
  **NeKI brief:** Examines M1 macOS runners now available on CircleCI in the context of Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [use ChatGPT](https://www.digitaltrends.com/mobile/how-to-replace-siri-with-chatgpt-iphone) — iOS Dev Weekly · Issue 601 — Article · Topics: AI Development · App Intents & System Surfaces · Developer Tools
  **Published:** `17th March 2023`
  **NeKI brief:** Presents use ChatGPT, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [⚡️ 12-core GitHub-hosted macOS runners](https://github.blog/2023-03-01-github-actions-introducing-faster-github-hosted-x64-macos-runners) — iOS CI Newsletter · Issue 11 — Article · Topics: Developer Tools · macOS & AppKit
  **Published:** `2023-03-12T00:00:00.000Z`
  **NeKI brief:** Examines 12-core GitHub-hosted macOS runners in the context of Developer Tools and macOS & AppKit. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [alternate reality](https://swallowmygraphicdesign.com/project/macostalgia) — iOS Dev Weekly · Issue 590 — Article · Topics: macOS & AppKit
  **Published:** `30th December 2022`
  **NeKI brief:** Examines (mac)OStalgia - Hello, I'm Michael.. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [what](https://github.com/uliwitness/AppKitForClassic) — iOS Dev Weekly · Issue 590 — Source repository · Topics: Developer Tools · Xcode
  **Published:** `30th December 2022`
  **NeKI brief:** Explores what, focusing on are you looking for work? there are many exciting opportunities to work with all kinds of companies over on ios dev jobs.. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [GitHub issue about the availability of macOS 13 GitHub-hosted runners](https://github.com/actions/runner-images/issues/6426) — iOS CI Newsletter · Issue 5 — Source repository · Topics: Developer Tools
  **Published:** `2022-12-18T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for GitHub issue about the availability of macOS 13 GitHub-hosted runners, relevant to Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [Monitor stability across iOS, macOS, tvOS, and now watchOS](https://docs.bugsnag.com/platforms/watchos) — iOS Dev Weekly · Issue 588 — Article
  **Published:** `9th December 2022`
  **NeKI brief:** Documents Bugsnag stability monitoring for watchOS alongside Apple-platform targets. Useful for evaluating crash-reporting coverage and configuration boundaries in a multi-platform app, while keeping vendor-specific setup separate from general diagnostics practice.
- [macOS / iOS Developers @ Kagi Inc.](https://browser.kagi.com/faq.html) — iOS Dev Weekly · Issue 578 — Article · Topics: Cross-Platform & Web
  **Published:** `30th September 2022`
  **NeKI brief:** The page covers “macOS / iOS Developers @ Kagi Inc.” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [An Introduction to ExtensionKit](https://www.chimehq.com/blog/extensionkit-intro) — iOS Dev Weekly · Issue 577 — Article · Topics: App Services & Extensions
  **Published:** `23rd September 2022`
  **NeKI brief:** Examines Chime is an editor for macOS. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [2](https://www.chimehq.com/blog/extensionkit-xpc) — iOS Dev Weekly · Issue 577 — Article · Topics: App Services & Extensions
  **Published:** `23rd September 2022`
  **NeKI brief:** Presents 2, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [3](https://www.chimehq.com/blog/extensionkit-end-to-end) — iOS Dev Weekly · Issue 577 — Article · Topics: App Services & Extensions
  **Published:** `23rd September 2022`
  **NeKI brief:** Presents 3, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [4](https://www.chimehq.com/blog/extensionkit-views) — iOS Dev Weekly · Issue 577 — Article · Topics: App Services & Extensions
  **Published:** `23rd September 2022`
  **NeKI brief:** Examines Chime is an editor for macOS. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Apple’s use of AppKit, Mac Catalyst and SwiftUI in macOS](https://blog.timac.org/2022/0818-state-of-appkit-catalyst-swiftui-mac) — iOS Dev Weekly · Issue 572 — Article · Topics: macOS & AppKit · Swift · SwiftUI
  **Published:** `19th August 2022`
  **NeKI brief:** Explores Apple’s use of AppKit, Mac Catalyst and SwiftUI in macOS, focusing on alexandre colucci has been writing posts analysing apple’s use of. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [hiding the iOS home indicator](https://danielsaidi.com/blog/2022/08/01/removing-the-home-indicator-in-swiftui) — iOS Dev Weekly · Issue 571 — Article · Topics: Swift · SwiftUI · UIKit
  **Published:** `12th August 2022`
  **NeKI brief:** Shows how SwiftUI can hide the home indicator through UIKit hosting integration and environment handling. Useful for immersive media or game screens, with careful consideration of discoverability and platform review expectations.
- [SwiftUI Field Notes: DocumentGroup](https://rhonabwy.com/2022/07/19/swiftui-field-notes-documentgroup) — iOS Dev Weekly · Issue 568 — Article · Topics: Swift · SwiftUI
  **Published:** `22nd July 2022`
  **NeKI brief:** Explores SwiftUI Field Notes: DocumentGroup, focusing on talking of the new swiftui navigation apis, joseph heck wrote. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Every programmer should care about UI design](https://silverhammermba.github.io/blog/2022/07/10/ui) — iOS Dev Weekly · Issue 567 — Article · Topics: Developer Tools
  **Published:** `15th July 2022`
  **NeKI brief:** I’m going to sneak this article by Maxwell Anselm into the bottom of the Code section so that those who skip the Design section get tricked into reading it! 😂 It’s way more common for people working on iOS/macOS projects to care about design than with some…
- [Swift language announcements from WWDC22](https://www.swift.org/blog/swift-language-updates-from-wwdc22) — iOS Dev Weekly · Issue 566 — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `8th July 2022`
  **NeKI brief:** Explores Swift language announcements from WWDC22, focusing on it’s easy to get distracted by all the swiftui, uikit. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Accelerate Your iOS DevOps with Granular VM Control in Orka](https://www.macstadium.com/orka) — iOS Dev Weekly · Issue 564 — Article · Topics: Xcode
  **Published:** `24th June 2022`
  **NeKI brief:** Explores Accelerate Your iOS DevOps with Granular VM Control in Orka, focusing on orka 2.0 is now available and includes support for macos. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Purgeable Mac Apps](https://bitsplitting.org/2022/06/18/purgeable-mac-apps) — iOS Dev Weekly · Issue 564 — Article · Topics: Developer Tools
  **Published:** `24th June 2022`
  **NeKI brief:** Examines For months now, I have been scratching my head over a small but persistent number of "crash reports" affecting a few of my apps. The issue is most prevalent in MarsEdit,. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Requesting App Store reviews in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL25pbGNvYWxlc2NpbmcuY29tL2Jsb2cvUmVxdWVzdGluZ0FwcFN0b3JlUmV2aWV3c0luU3dpZnRVSS8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiJlOGMyZGIwMC05Y2NjLTRkOWItYmI5Ni1kMWU2MDU3NjFhOTciLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiY2E4YjI1ODQtMmEzYy00OWQ1LThlNzktNTM1NjdlNDI1OTY2IiwiaWF0IjoxNjc0MDYyNTU4Ljg3MywiaXNzIjoib3JjaGlkIn0.gpPrkF9rQIPK1vqfb0AZ1jFSBMP_sLOCzneScAJ-voM) — SwiftUI Weekly · SwiftUI Weekly - Issue #107 — Article · Topics: App Distribution & Store Operations · Swift · SwiftUI
  **Published:** `2022-06-21T10:41:22.000Z`
  **NeKI brief:** Shows how to trigger App Store review requests from SwiftUI while respecting the system-controlled presentation. Useful for choosing a meaningful in-app moment and avoiding repeated or disruptive prompts.
- [Get More Done Faster with a New Mac Studio Hosted by MacStadium](https://www.macstadium.com/blog/the-new-mac-studio-is-coming-to-macstadium) — iOS Dev Weekly · Issue 562 — Article · Topics: Graphics, Media & Games
  **Published:** `10th June 2022`
  **NeKI brief:** Presents Get More Done Faster with a New Mac Studio Hosted by MacStadium, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [some good tips](https://kernelpanic.me/2022/06/06/running-macos-ventura-as-a-vm) — iOS Dev Weekly · Issue 562 — Article · Topics: macOS & AppKit · Objective-C & Cocoa · Personal Essays
  **Published:** `10th June 2022`
  **NeKI brief:** Examines While Xcode 14 runs perfectly well on macOS Monterey, if you want to play with all the features, you’ll need runtime support which is only¹ available if you’re running the new macOS Ventura beta. This Twitter thread from Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [more information on getting the most out of the site](https://blog.eidinger.info/view-all-public-frameworks-provided-by-apple-and-check-their-platform-availability-at-a-glance) — iOS Dev Weekly · Issue 561 — Article
  **Published:** `3rd June 2022`
  **NeKI brief:** Discusses more information on getting the most out of the site, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [STTextView](https://christiantietze.de/posts/2022/05/sttextview-textkit-2-editor-without-nstextview) — iOS Dev Weekly · Issue 558 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `13th May 2022`
  **NeKI brief:** Explores STTextView, focusing on talking of textkit 2, in this post, christian tietze talks about marcin krzyzanowski’s syntax highlighting text editor control for macos, sttextview. it’s. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Send Events from SwiftUI to UIKit and Vice Versa](https://www.swiftjectivec.com/events-from-swiftui-to-uikit-and-vice-versa) — iOS Dev Weekly · Issue 557 — Article · Topics: Swift · SwiftUI · UIKit
  **Published:** `6th May 2022`
  **NeKI brief:** Explores Send Events from SwiftUI to UIKit and Vice Versa, focusing on you’ll find plenty of advice that tells you how easy. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Designing macOS menu bar extras](https://bjango.com/articles/designingmenubarextras) — iOS Dev Weekly · Issue 556 — Article · Topics: macOS & AppKit · Objective-C & Cocoa
  **Published:** `29th April 2022`
  **NeKI brief:** Discusses Designing macOS menu bar extras, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [Swift Bundler v2](https://forums.swift.org/t/swift-bundler-create-macos-apps-with-swiftpm-instead-of-xcodeprojs/56790) — iOS Dev Weekly · Issue 555 — Article · Topics: Swift · Swift Package Manager · Xcode
  **Published:** `22nd April 2022`
  **NeKI brief:** Explores Swift Bundler v2, focusing on talking of doing a great job at informing people of. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [macOS by Tutorials](https://www.raywenderlich.com/books/macos-by-tutorials) — iOS Dev Weekly · Issue 554 — Tutorial · Topics: macOS & AppKit · Swift · SwiftUI
  **Published:** `15th April 2022`
  **NeKI brief:** Explores macOS by Tutorials, focusing on the article discusses still have the first book on mac. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Mac-assed Mac app](https://daringfireball.net/linked/2020/03/20/mac-assed-mac-apps) — iOS Dev Weekly · Issue 546 — Article · Topics: Swift · SwiftUI
  **Published:** `18th February 2022`
  **NeKI brief:** We’ve been in a slightly awkward place with macOS software development for a while now. AppKit is the rock-solid, dependable choice that you can definitely make a Mac-assed Mac app with. SwiftUI on the Mac is the future, but it still feels like that future…
- [BackLog](https://eternalstorms.at/backlog) — iOS Dev Weekly · Issue 542 — Article
  **Published:** `21st January 2022`
  **NeKI brief:** Examines Have you ever had to talk someone through finding a debug message in Console.app? It’s a powerful app, but it can be confusing to talk someone through using it. This utility from Matthias Gansrigler will be of more use t Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [The new Guide to NSButton styles](https://mackuba.eu/2021/12/30/new-nsbutton-post) — iOS Dev Weekly · Issue 541 — Article
  **Published:** `14th January 2022`
  **NeKI brief:** Explores The new Guide to NSButton styles, focusing on the article discusses linked to the original version of this. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [get an update](https://mackuba.eu/2014/10/06/a-guide-to-nsbutton-styles) — iOS Dev Weekly · Issue 541 — Article
  **Published:** `14th January 2022`
  **NeKI brief:** Examines The NSButton class used for making buttons in Mac apps has as many as 15 different styles, not counting subclasses. But which should be used where? (Updated with new examples and B. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
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
- [rolled back the fairly radical new Safari tab design](https://9to5mac.com/2021/07/14/macos-monterey-beta-3-brings-redesigned-safari-tab-interface-to-address-complaints) — iOS Dev Weekly · Issue 516 — Article · Topics: macOS & AppKit · Testing
  **Published:** `16th July 2021`
  **NeKI brief:** The page covers “rolled back the fairly radical new Safari tab design” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Implementing a focusable text field in SwiftUI](https://serialcoder.dev/text-tutorials/macos-tutorials/macos-programming-implementing-a-focusable-text-field-in-swiftui) — iOS Dev Weekly · Issue 516 — Tutorial · Topics: macOS & AppKit · Swift · SwiftUI
  **Published:** `16th July 2021`
  **NeKI brief:** Explores Implementing a focusable text field in SwiftUI, focusing on the article discusses enjoyed this article from gabriel theodoropoulos. at. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [newly released macOS app](https://github.com/dennisbirch/simple-analytics-reader) — iOS Dev Weekly · Issue 510 — Source repository · Topics: Developer Tools
  **Published:** `4th June 2021`
  **NeKI brief:** Examines A macOS application for accessing the output of the SimpleAnalytics package on the desktop. - dennisbirch/simple-analytics-reader. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Creating a licensing system for paid apps in Swift](https://swiftrocks.com/creating-a-license-system-for-paid-apps-in-swift) — iOS Dev Weekly · Issue 502 — Article · Topics: App Distribution & Store Operations · Swift
  **Published:** `9th April 2021`
  **NeKI brief:** Explores Creating a licensing system for paid apps in Swift, focusing on unlike with ios, you have a choice of how you’d. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [XcodeSpy targets Xcode developers](https://labs.sentinelone.com/new-macos-malware-xcodespy-targets-xcode-developers-with-eggshell-backdoor) — iOS Dev Weekly · Issue 499 — Article · Topics: Developer Tools · macOS & AppKit · Xcode
  **Published:** `19th March 2021`
  **NeKI brief:** The page covers “XcodeSpy targets Xcode developers” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Setting up a multi-platform SwiftUI project](https://blog.scottlogic.com/2021/03/04/Multiplatform-SwiftUI.html) — iOS Dev Weekly · Issue 499 — Article · Topics: Swift · SwiftUI · Xcode
  **Published:** `19th March 2021`
  **NeKI brief:** Covers Setting up a multi-platform SwiftUI project, focusing on Apple UI composition and interaction design. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [Adding Services to Grocery for Mac](http://conradstoll.com/blog/2021/2/26/adding-services-to-grocery-for-mac-with-catalyst-and-appkit) — iOS Dev Weekly · Issue 497 — Article · Topics: macOS & AppKit
  **Published:** `5th March 2021`
  **NeKI brief:** This case study shows how a Catalyst application can expose macOS Services while integrating with AppKit conventions. It is useful for developers extending a shared iPad or Catalyst codebase with platform-specific workflows expected by long-time Mac users.
- [AppKit is Done](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2tlYW4uYmxvZy9wb3N0L2FwcGtpdC1pcy1kb25lP3V0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiZjhkYzQzOWQtNjdhOS00N2IwLWI0NzEtOTE2YzY0MWZlN2FjIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6IjNmMDQyMTgxLWQ3NWUtNGE0ZC1hNmE5LWJjM2UwYjBlYTBkZiIsImlhdCI6MTY3NDA2MjY3OC44OTQsImlzcyI6Im9yY2hpZCJ9.DGocxcXaFPcCXGsnsZ3eHNT1uJHhzVUovNZuaulm2lo) — SwiftUI Weekly · SwiftUI Weekly - Issue #48 — Article · Topics: Swift · SwiftUI
  **Published:** `2021-03-01T13:49:29.000Z`
  **NeKI brief:** Reflects on replacing AppKit in a macOS application and the practical limits of a SwiftUI-first architecture. Use it to assess migration scope, platform gaps, and maintenance costs rather than as a universal prescription.
- [Similar Detritus Not Allowed](https://indiestack.com/2021/02/similar-detritus-not-allowed) — iOS Dev Weekly · Issue 496 — Article
  **Published:** `26th February 2021`
  **NeKI brief:** Examines Over the past few weeks, I've noticed a spike in the number of Mac and iOS developers who are running into a specific code signing error while building their apps. I myself ra. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [AppKit is Done](https://kean.blog/post/appkit-is-done) — iOS Dev Weekly · Issue 496 — Article · Topics: macOS & AppKit · Swift · SwiftUI
  **Published:** `26th February 2021`
  **NeKI brief:** Reflects on replacing AppKit in a macOS application and the practical limits of a SwiftUI-first architecture. Use it to assess migration scope, platform gaps, and maintenance costs rather than as a universal prescription.
- [Keyboard Navigation in SwiftUI](https://pspdfkit.com/blog/2021/keyboard-navigation-in-swiftui) — iOS Dev Weekly · Issue 494 — Article · Topics: Hardware & Devices · Swift · SwiftUI
  **Published:** `12th February 2021`
  **NeKI brief:** Examines Keyboard Navigation in SwiftUI, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Pulse](https://kean.blog/post/pulse) — iOS Dev Weekly · Issue 493 — Article · Topics: Developer Tools
  **Published:** `5th February 2021`
  **NeKI brief:** This new tool and library from Alex Grebenyuk looks great. It’s a network monitor, but in a similar way to Proxyman with Atlantis, there’s no need to worry about proxies. View the logs either on-device in your app, or via a macOS app. 👍
- [Open-Source iOS & macOS Chat SDK](https://github.com/getstream/stream-chat-swift) — iOS Dev Weekly · Issue 492 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `29th January 2021`
  **NeKI brief:** Explains Open-Source iOS & macOS Chat SDK, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [A guide to distributing macOS apps outside of the App Store](https://rambo.codes/posts/2021-01-08-distributing-mac-apps-outside-the-app-store) — iOS Dev Weekly · Issue 490 — Article · Topics: App Distribution & Store Operations
  **Published:** `15th January 2021`
  **NeKI brief:** Examines Gui Rambo writes about his coding and reverse engineering adventures. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [review of the year](https://indiedevmonday.com/issue-23) — iOS Dev Weekly · Issue 489 — Article
  **Published:** `8th January 2021`
  **NeKI brief:** I don’t quite know how I’ve managed not to link to Josh Holtz’s interview-based newsletter before, but let’s fix that right now. Every Monday, you’ll learn all about an independent iOS or macOS developer, and their apps. If you want to catch up with all of…
- [Orchestrate macOS VMs on genuine Apple hardware - Try Orka](https://www.macstadium.com/orkademo) — iOS Dev Weekly · Issue 488 — Article
  **Published:** `1st January 2021`
  **NeKI brief:** Covers Orchestrate macOS VMs on genuine Apple hardware - Try Orka, focusing on Apple UI composition and interaction design. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [Want to visit Catalina Island, virtually](https://birchtree.me/blog/flying-around-the-world-recreating-macos-wallpapers) — iOS Dev Weekly · Issue 488 — Article · Topics: macOS & AppKit
  **Published:** `1st January 2021`
  **NeKI brief:** The post describes recreating macOS wallpaper locations and virtually exploring Catalina Island through the resulting project.
- [Xcode 12.3 is available on the Mac App Store](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2FwcHMuYXBwbGUuY29tL2F6L2FwcC94Y29kZS9pZDQ5Nzc5OTgzNT9tdD0xMiZ1dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6ImUwZDA3MDRlLWU3MDItNGQzOC05YjcxLWYxNmMzODc4NGI1ZSIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiI0ODRkOGEwZi02ZTM1LTQ2ODgtOWJlYy04OTdmYWY5M2I5N2MiLCJpYXQiOjE2NzQwNjI2NzkuNzA4LCJpc3MiOiJvcmNoaWQifQ.Rnp31Lwoh2tW1CP8rFSLWGLLC-3eQlf-aop4b01WMPw) — SwiftUI Weekly · SwiftUI Weekly - Issue #39 — Article · Topics: App Distribution & Store Operations · Swift · Xcode
  **Published:** `2020-12-15T13:53:41.000Z`
  **NeKI brief:** Links to the Xcode 12.3 Mac App Store release from the historical issue. Use it only as release-history context when investigating SDK-era behavior, not as a current installation recommendation.
- [indie apps that are on sale](https://trycatchswift.com/black-friday-cyber-monday-ios-macos-watchos-apps-2020) — iOS Dev Weekly · Issue 484 — Article · Topics: Developer Community & Business · macOS & AppKit · Swift
  **Published:** `27th November 2020`
  **NeKI brief:** It’s becoming a tradition that I link to Marius Landwehr’s annual round-up of Black Friday deals, and this year is no different! If you’re looking to spend some money on the most commercial day of the year, feast your eyes. Or, check out Bryan Dubno’s list…
- [iOS Apps on M1 Macs](https://ryanashcraft.com/ios-apps-on-m1-macs) — iOS Dev Weekly · Issue 484 — Article · Topics: Personal Essays · Testing
  **Published:** `27th November 2020`
  **NeKI brief:** Examines Why I'm incredibly excited about iOS apps on the Mac, and what I had to do to get FoodNoms ready. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [View Controllers without XIBs](https://padraig.org/appkit/2020/10/25/layout-in-code.html) — iOS Dev Weekly · Issue 480 — Article · Topics: Cross-Platform & Web · macOS & AppKit · Swift
  **Published:** `30th October 2020`
  **NeKI brief:** Examines Notes from a Swift programmer. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [the untold history of macOS System Preferences](https://www.arun.is/blog/system-preferences) — iOS Dev Weekly · Issue 474 — Article
  **Published:** `18th September 2020`
  **NeKI brief:** Examines System Preferences may not be the most exciting part of the Mac, but by looking through its evolution over the decades, we. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [How much time a day do you waste waiting for Xcode builds?](https://blog.kulman.sk/xcode-build-times) — iOS Dev Weekly · Issue 470 — Article · Topics: macOS & AppKit · Xcode
  **Published:** `21st August 2020`
  **NeKI brief:** Measures Xcode build-time contributors and shows practical configuration and dependency changes that affect iteration speed. Follow it when profiling compile bottlenecks before applying project-wide build-setting changes.
- [BitBar](https://github.com/matryer/bitbar) — iOS Dev Weekly · Issue 470 — Source repository · Topics: Developer Tools · macOS & AppKit · Xcode
  **Published:** `21st August 2020`
  **NeKI brief:** Here’s an interesting little timewaster from Igor Kulman that adds up all the time that Xcode spends building during your day and displays it in your menu bar. The irony of this post is that if you do this, you’ll spend more time thinking about your build…
- [macOS.swift](https://gist.github.com/jordansinger/72a05653dde9d182b4a5e24f9d19a106) — iOS Dev Weekly · Issue 466 — Source repository · Topics: Developer Tools · Performance · Swift
  **Published:** `24th July 2020`
  **NeKI brief:** Examines macOS.swift, focusing on i’ve been thoroughly enjoying jordan singer’s tweets recently, especially his experimentations with swiftui which he has…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [directly addressed the issue of whether iOS and macOS would merge](https://www.youtube.com/watch?v=DOYikXbC6Fs) — iOS Dev Weekly · Issue 462 — Video
  **Published:** `26th June 2020`
  **NeKI brief:** They’ve been consistent with their message about how important the Mac is for a long time though. Back as far as 2010, they ran a “Back to the Mac” event as they unveiled iLife ’09 and Tim Cook spent several minutes saying how important the Mac was to their…
- [Installing the macOS Big Sur beta on a new partition](https://lickability.com/blog/installing-macos-big-sur-on-a-new-partition) — iOS Dev Weekly · Issue 462 — Article · Topics: macOS & AppKit
  **Published:** `26th June 2020`
  **NeKI brief:** Presents Installing the macOS Big Sur beta on a new partition, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [organising notes and blog posts](https://github.com/twostraws/wwdc) — iOS Dev Weekly · Issue 461 — Source repository · Topics: Apple Platform Ecosystem · Developer Community & Business · Developer Tools
  **Published:** `19th June 2020`
  **NeKI brief:** If you have a ticket and are going to California, I hope you have a wonderful time at the event. If you’ll be there without a ticket, I hope you have a wonderful time at CommunityKit and One More Thing, and the countless other events during the week!
- [PointFree snapshot testing](https://github.com/pointfreeco/swift-snapshot-testing) — iOS Dev Weekly · Issue 460 — Source repository · Topics: Accessibility · Developer Tools · Testing
  **Published:** `12th June 2020`
  **NeKI brief:** SnapshotTesting can launch UI tests with a specified content-size category, making large accessibility sizes reproducible in image assertions. Follow it to catch Dynamic Type layout regressions that ordinary interaction tests may miss.
- [Adaptivity](https://itunes.apple.com/app/id1054670022) — iOS Dev Weekly · Issue 450 — Article
  **Published:** `3rd April 2020`
  **NeKI brief:** Examines Download Adaptivity (A) by Geoff Hackworth on the App Store. See screenshots, ratings and reviews, user tips, and more apps like Adaptivity (A). Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Mac App Store in a nutshell](https://lapcatsoftware.com/articles/nutshell.html) — iOS Dev Weekly · Issue 449 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `27th March 2020`
  **NeKI brief:** Examines Mac App Store in a nutshell. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [SwiftPlaygroundsCLI](https://github.com/SvenTiigi/SwiftPlaygroundsCLI) — iOS Dev Weekly · Issue 443 — Source repository · Topics: Developer Tools · Swift
  **Published:** `14th February 2020`
  **NeKI brief:** The page covers “SwiftPlaygroundsCLI” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [diagnostic architecture](https://swift.org/blog/new-diagnostic-arch-overview) — iOS Dev Weekly · Issue 442 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `7th February 2020`
  **NeKI brief:** Examines new diagnostic architecture, focusing on one of those things got much better this week with the passing of the cutoff date for swift 5.2, and the appearance of…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against.
- [SwiftPM Catalog](https://zeezide.com/en/products/swiftpmcatalog) — iOS Dev Weekly · Issue 430 — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **Published:** `15th November 2019`
  **NeKI brief:** Examines SwiftPM Catalog, offering practical guidance on Swift Package Manager integration. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [manually curated packages](https://github.com/ZeeZide/SwiftPMCatalog/blob/develop/catalog-info.json) — iOS Dev Weekly · Issue 430 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `15th November 2019`
  **NeKI brief:** Explains manually curated packages, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [Quickly selected text in an Xcode Playground](https://medium.com/@DanielTavares/quickly-open-selected-text-in-xcode-playground-for-rapid-development-mac-os-56cd07030ef9) — iOS Dev Weekly · Issue 427 — Article · Topics: Xcode
  **Published:** `25th October 2019`
  **NeKI brief:** Examines Quickly selected text in an Xcode Playground, focusing on super simple and smart little hack from daniel tavares that leverages playground and macos automator. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Playground](https://github.com/JohnSundell/Playground) — iOS Dev Weekly · Issue 427 — Source repository · Topics: Developer Tools
  **Published:** `25th October 2019`
  **NeKI brief:** The page covers “Playground” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Catalytic Converter](https://tla.systems/blog/2019/10/08/catalytic-converter) — iOS Dev Weekly · Issue 425 — Article
  **Published:** `11th October 2019`
  **NeKI brief:** Presents Catalytic Converter, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Dice](https://pcalc.com/dice/index.html) — iOS Dev Weekly · Issue 425 — Article · Topics: Cross-Platform & Web
  **Published:** `11th October 2019`
  **NeKI brief:** So macOS Catalina is here and with it, the first set of Catalyst apps. The conversation on Catalyst has been mostly drowned out by this all summer, so it was fascinating for me to read James Thomson’s piece on his experimentation with potentially bringing…
- [Meet Orka: Orchestration with Kubernetes on Apple](https://www.macstadium.com/iosdev) — iOS Dev Weekly · Issue 406 — Article
  **Published:** `31st May 2019`
  **NeKI brief:** Examines App Development Solutions for macOS & iOS | MacStadium. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Appreciating AppKit](https://pilky.me/appreciating-appkit-part-1) — iOS Dev Weekly · Issue 404 — Article · Topics: macOS & AppKit
  **Published:** `17th May 2019`
  **NeKI brief:** Examines JNETOTO membawa konsep baru dalam dunia toto macau digital melalui situs togel modern, akses ringan, dan pengalaman online yang lebih seamless. Temukan informasi terkait togel Maca. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [part 2](https://pilky.me/appreciating-appkit-part-2) — iOS Dev Weekly · Issue 404 — Article · Topics: macOS & AppKit
  **Published:** `17th May 2019`
  **NeKI brief:** Examines JNETOTO membawa konsep baru dalam dunia toto macau digital melalui situs togel modern, akses ringan, dan pengalaman online yang lebih seamless. Temukan informasi terkait togel Maca. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Swift talk episodes](https://talk.objc.io/collections/markdown-playgrounds) — iOS Dev Weekly · Issue 400 — Article · Topics: App Distribution & Store Operations · Swift
  **Published:** `19th April 2019`
  **NeKI brief:** The associated Swift talk episodes are also worth watching if you’re interested in how they built this, or if you’re curious about AppKit development. The first one is free, the rest need a subscription.
- [Core Image Filter Reference](https://noahgilmore.com/blog/cifilterio) — iOS Dev Weekly · Issue 398 — Article · Topics: Graphics, Media & Games
  **Published:** `5th April 2019`
  **NeKI brief:** Presents Core Image Filter Reference, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Marzipanify](https://github.com/steventroughtonsmith/marzipanify) — iOS Dev Weekly · Issue 394 — Source repository · Topics: Developer Tools
  **Published:** `8th March 2019`
  **NeKI brief:** Marzipanify has been around for a while, but this week Steve kept himself very busy with three lengthy blog posts about it. Bringing iOS Apps to macOS Using Marzipanify, Making Marzipan Apps Sing, and Deeper Integration with Marzipan. The posts speak for…
- [Bringing iOS Apps to macOS Using Marzipanify](https://www.highcaffeinecontent.com/blog/20190301-Bringing-iOS-Apps-to-macOS-Using-Marzipanify) — iOS Dev Weekly · Issue 394 — Article
  **Published:** `8th March 2019`
  **NeKI brief:** Marzipanify has been around for a while, but this week Steve kept himself very busy with three lengthy blog posts about it. Bringing iOS Apps to macOS Using Marzipanify, Making Marzipan Apps Sing, and Deeper Integration with Marzipan. The posts speak for…
- [Making Marzipan Apps Sing](https://www.highcaffeinecontent.com/blog/20190302-Making-Marzipan-Apps-Sing) — iOS Dev Weekly · Issue 394 — Article
  **Published:** `8th March 2019`
  **NeKI brief:** Marzipanify has been around for a while, but this week Steve kept himself very busy with three lengthy blog posts about it. Bringing iOS Apps to macOS Using Marzipanify, Making Marzipan Apps Sing, and Deeper Integration with Marzipan. The posts speak for…
- [Deeper Integration with Marzipan](https://www.highcaffeinecontent.com/blog/20190307-Deeper-Integration-with-Marzipan) — iOS Dev Weekly · Issue 394 — Article
  **Published:** `8th March 2019`
  **NeKI brief:** Marzipanify has been around for a while, but this week Steve kept himself very busy with three lengthy blog posts about it. Bringing iOS Apps to macOS Using Marzipanify, Making Marzipan Apps Sing, and Deeper Integration with Marzipan. The posts speak for…
- [Understanding the iOS Responder Chain](https://swiftrocks.com/understanding-the-ios-responder-chain.html) — iOS Dev Weekly · Issue 394 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `8th March 2019`
  **NeKI brief:** Examines Understanding the iOS Responder Chain, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Path.swift](https://github.com/mxcl/Path.swift) — iOS Dev Weekly · Issue 388 — Source repository · Topics: Developer Tools · Foundation & Data Formats · Swift
  **Published:** `25th January 2019`
  **NeKI brief:** Examines Path.swift, focusing on the url/path manipulation methods in foundation have always been powerful, but also very verbose so this new wrapper…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [code sample](https://github.com/TwoLivesLeft/Menu) — iOS Dev Weekly · Issue 385 — Source repository · Topics: Developer Tools
  **Published:** `4th January 2019`
  **NeKI brief:** Examines macOS style menus aren’t going to be a good fit for most apps, in fact I’d say that they are only going to be useful in a tiny number of apps. Codea is one of them though, and that’s what Simeon Saëns writes about here. Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [this is worth a read](https://lapcatsoftware.com/articles/notarization-privacy.html) — iOS Dev Weekly · Issue 381 — Article · Topics: Cross-Platform & Web · Security & Privacy
  **Published:** `7th December 2018`
  **NeKI brief:** We knew to expect changes requiring the new notarization (sic) feature in Mojave, but I must admit they’re happening quicker than I expected. Also, this is worth a read from Jeff Johnson.
- [Transmit 5 on the Mac App Store](https://panic.com/blog/transmit-5-on-the-mac-app-store) — iOS Dev Weekly · Issue 379 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem
  **Published:** `23rd November 2018`
  **NeKI brief:** Examines Panic Blog » Transmit 5 on the Mac App Store. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [article by Daniel Jalkut](https://bitsplitting.org/2018/11/15/mac-sandboxing-privileged-file-operations) — iOS Dev Weekly · Issue 379 — Article · Topics: Apple Platform Ecosystem · Security & Privacy
  **Published:** `23rd November 2018`
  **NeKI brief:** No sign of BBEdit yet, but the promised return of Transmit from this year’s WWDC finally happened. Here’s the news from Panic’s blog, and there’s also this article by Daniel Jalkut on the entitlements that it uses.
- [Implementing Support for Continuity Camera](https://thomas.zoechling.me/journal/2018/10/Continuity.html) — iOS Dev Weekly · Issue 375 — Article · Topics: Cross-Platform & Web · Graphics, Media & Games
  **Published:** `26th October 2018`
  **NeKI brief:** Examines Build and Run: Implementing Support for Continuity Camera. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Dark Mode and CSS](https://blog.iconfactory.com/2018/10/dark-mode-and-css) — iOS Dev Weekly · Issue 375 — Article · Topics: Concurrency · Cross-Platform & Web
  **Published:** `26th October 2018`
  **NeKI brief:** I know we’re straying quite far from iOS development with this article from Craig Hockenberry. But, you all have web sites to market your apps, and people look at those web sites on macOS in Dark Mode. Justified! 😂
- [iOS Developer at Savvy Apps (Remote)](https://remoteok.io/remote-jobs/68437-remote-ios-developer-savvy-apps) — iOS Dev Weekly · Issue 375 — Article
  **Published:** `26th October 2018`
  **NeKI brief:** The job page describes the iOS Developer role at Savvy Apps and provides publicly readable position details.
- [Dark Mode](https://indiestack.com/2018/10/dark-mode-series-introduction) — iOS Dev Weekly · Issue 374 — Article
  **Published:** `19th October 2018`
  **NeKI brief:** Examines I spent a good part of the summer learning about macOS Mojave's new Dark Mode theme, and how Mac apps can support the theme both in technical and practical ways. I adapted Mar. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Porting iOS Apps to the Mac with “Marzipan”](https://pspdfkit.com/blog/2018/porting-ios-apps-to-mac-marzipan-iosmac-uikit-appkit) — iOS Dev Weekly · Issue 370 — Article · Topics: macOS & AppKit · Personal Essays · UIKit
  **Published:** `21st September 2018`
  **NeKI brief:** Explains Porting iOS Apps to the Mac with “Marzipan”, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [Finder Quick Actions](https://indiestack.com/2018/09/finder-quick-actions) — iOS Dev Weekly · Issue 368 — Article
  **Published:** `7th September 2018`
  **NeKI brief:** Daniel Jalkut with an interesting investigation into whether Mojave Quick Actions might one day be able to be exposed by a fully native app as well as by Automator. There’s nothing official yet but what he found shows promise for the future.
- [ARM based Macs](http://shapeof.com/archives/2018/6/marzipan_to_arm_on_mac.html) — iOS Dev Weekly · Issue 358 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `29th June 2018`
  **NeKI brief:** The article discusses ARM-based Macs and the possible platform and software consequences of Apple's processor transition.
- [a new declarative UI framework](https://daringfireball.net/2018/04/scuttlebutt_regarding_ui_project) — iOS Dev Weekly · Issue 358 — Article · Topics: UIKit
  **Published:** `29th June 2018`
  **NeKI brief:** Examines It’s no longer called “Marzipan”, almost certainly isn’t coming this year, and is probably a declarative user interface API. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [What’s orange and sounds like a parrot?](https://www.hackingwithswift.com/offers/iosdev2-50) — iOS Dev Weekly · Issue 355 — Article · Topics: Swift
  **Published:** `8th June 2018`
  **NeKI brief:** A carrot. In entirely unrelated news, this is your last chance to buy books from the Hacking with Swift series at half price. We have books on Vapor 3, Swift design patterns, macOS development, and more, all with free lifetime updates for Swift. Don’t miss…
- [You’re Practically a Mac Developer](http://inessential.com/2018/04/25/youre_practically_a_mac_developer) — iOS Dev Weekly · Issue 349 — Article
  **Published:** `27th April 2018`
  **NeKI brief:** Examines Are you waiting for a “Marzipan” or similar framework from Apple to get started with macOS development? Brent Simmons thinks you’re probably already closer to being a Mac developer than you think. Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [SwiftNIO - Event-driven network application framework](https://github.com/apple/swift-nio) — iOS Dev Weekly · Issue 341 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2nd March 2018`
  **NeKI brief:** Examines SwiftNIO, focusing on it’s great to see this major release from the vapor team and it’s encouraging to see that it’s been built on top of…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [this article](https://www.bloomberg.com/news/articles/2017-12-20/apple-is-said-to-have-plan-to-combine-iphone-ipad-and-mac-apps) — iOS Dev Weekly · Issue 332 — Article · Topics: Combine & Reactive Programming · Cross-Platform & Web
  **Published:** `22nd December 2017`
  **NeKI brief:** Reports the historical proposal to unify iPhone, iPad, and Mac app distribution or development. Use it as platform-strategy context when assessing multiplatform architecture, while treating predictions as historical and checking the current Apple deployment model.
- [Apple’s use of Swift in iOS 11.1](https://blog.timac.org/2017/1115-state-of-swift-ios11-1-macos10-13) — iOS Dev Weekly · Issue 329 — Article · Topics: macOS & AppKit · Swift
  **Published:** `1st December 2017`
  **NeKI brief:** Examines Apple’s use of Swift in iOS 11.1 and macOS 10.13.1. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Kotlin/Objective-C Interoperability](https://blog.jetbrains.com/kotlin/2017/11/kotlinnative-v0-4-released-objective-c-interop-webassembly-and-more) — iOS Dev Weekly · Issue 328 — Article · Topics: Objective-C & Cocoa · Systems Programming · Testing
  **Published:** `24th November 2017`
  **NeKI brief:** Examines We’re happy to announce the release of Kotlin/Native v0.4, KotlinConf 2017 edition! This release adds support for accessing Objective-C APIs on iOS and macOS, WebAssembly target pl. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Container like Devops for iOS development environment](https://veertu.com/getting-started-anka-trials) — iOS Dev Weekly · Issue 318 — Article · Topics: Performance · Testing
  **Published:** `15th September 2017`
  **NeKI brief:** Explores Container like Devops for iOS development environment in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Brisk](https://github.com/br1sk/brisk) — iOS Dev Weekly · Issue 297 — Source repository · Topics: Developer Tools
  **Published:** `21st April 2017`
  **NeKI brief:** Submitting radars is not exactly a smooth experience and having to do it through an old web interface is less than ideal. This macOS application by Keith Smiley attempts to simplify that. For lack of an official native app from Apple for submitting radars…
- [Quick Radar](https://github.com/amyworrall/QuickRadar) — iOS Dev Weekly · Issue 297 — Source repository · Topics: Developer Tools
  **Published:** `21st April 2017`
  **NeKI brief:** Submitting radars is not exactly a smooth experience and having to do it through an old web interface is less than ideal. This macOS application by Keith Smiley attempts to simplify that. For lack of an official native app from Apple for submitting radars…
- [Open Radar](https://openradar.appspot.com/page/1) — iOS Dev Weekly · Issue 297 — Article
  **Published:** `21st April 2017`
  **NeKI brief:** The Open Radar page provides a publicly readable index of community-submitted Apple platform bug reports.
- [A Change of Heart ❤️](http://appleinsider.com/articles/17/04/10/apple-issues-second-betas-of-ios-1032-macos-10125-watchos-322-tvos-1021) — iOS Dev Weekly · Issue 296 — Article · Topics: macOS & AppKit
  **Published:** `14th April 2017`
  **NeKI brief:** Examines Apple on Monday issued second betas of iOS 10.3.2 and macOS 10.12.5 to developers, paving the way for what are likely to be minor bugfixes and security improvements for Macs, iPhon. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [KiteKit](https://github.com/kitecomp/kitekit) — iOS Dev Weekly · Issue 291 — Source repository · Topics: Developer Tools
  **Published:** `10th March 2017`
  **NeKI brief:** This looks amazing! It’s a new animation and prototyping tool for macOS which looks to be very powerful. Not only can you quickly put together a simple animation but there’s in-app scripting and KiteKit which can bring your creations directly into your app…
- [UITextField-Navigation](https://github.com/T-Pham/UITextField-Navigation) — iOS Dev Weekly · Issue 290 — Source repository · Topics: Developer Tools
  **Published:** `3rd March 2017`
  **NeKI brief:** If you’ve ever done any macOS development you’ll be familiar with nextKeyView which lets the app define the “tab order” of fields in a view. This library aims to do something similar, but for iOS and with a UI that lives on the input accessory view. Probably…
- [Swift Ownership Manifesto](https://github.com/apple/swift/blob/master/docs/OwnershipManifesto.md) — iOS Dev Weekly · Issue 289 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `24th February 2017`
  **NeKI brief:** So ARC is baked directly into the core of Swift and I’d imagine we’re all pretty happy with that? I know that as an iOS developer I certainly am. But Swift is not just for writing iOS and macOS apps, it’s also designed as a systems language and that can…
- [Making More Outside The Mac App Store](https://weblog.rogueamoeba.com/2017/02/10/piezos-life-outside-the-app-store) — iOS Dev Weekly · Issue 287 — Article · Topics: App Distribution & Store Operations · Developer Community & Business
  **Published:** `13th February 2017`
  **NeKI brief:** There have been a few Interesting posts this week on making money without the MAS. First up is Paul Kafasis talking about sales figures after removing Piezo from the App Store. He also references Bogdan Popescu’s post on sales of Dash after it also left the…
- [Bogdan Popescu’s post](https://blog.kapeli.com/100-days-without-the-app-store) — iOS Dev Weekly · Issue 287 — Article · Topics: App Distribution & Store Operations · Developer Community & Business
  **Published:** `13th February 2017`
  **NeKI brief:** Discusses Bogdan Popescu’s post, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [70 Cents Put Me on the Mac App Store Charts](http://lapcatsoftware.com/articles/70cents.html) — iOS Dev Weekly · Issue 286 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `3rd February 2017`
  **NeKI brief:** This is an unbelievable story and just shows how top heavy the MAS has become. Is it time to call it a failure yet? I think it might be. Such a shame.
- [Developer PSA: The Discrete GPU and You](http://supermegaultragroovy.com//2016/12/10/auto-graphics-switching) — iOS Dev Weekly · Issue 281 — Article
  **Published:** `16th December 2016`
  **NeKI brief:** With all the talk about laptop batteries this week, this article on keeping GPU usage under control in your app so you don’t use unnecessary battery is very timely. Chris Liscio explains how to avoid activating the discrete GPU to keep your app using only…
- [swiftgd](https://github.com/twostraws/swiftgd) — iOS Dev Weekly · Issue 278 — Source repository · Topics: Developer Community & Business · Developer Tools · Swift
  **Published:** `25th November 2016`
  **NeKI brief:** If you’ve been doing any work the server with Swift you might be missing Core Graphics which is not available outside of macOS. Of course, there are other graphics libraries available, such as libgd and to help you out, Paul Hudson has wrapped this library…
- [libgd](https://libgd.github.io/manuals/2.2.3/files/preamble-txt.html) — iOS Dev Weekly · Issue 278 — Tutorial · Topics: Cross-Platform & Web · Developer Community & Business · Developer Tools
  **Published:** `25th November 2016`
  **NeKI brief:** The page covers “libgd” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [The Touch Bar on your iPad](https://github.com/bikkelbroeders/TouchBarDemoApp) — iOS Dev Weekly · Issue 276 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Testing
  **Published:** `11th November 2016`
  **NeKI brief:** Examines Allows you to use your macOS Touch Bar from an iPad (through USB connection) or on-screen by pressing the Fn-key. - bikkelbroeders/TouchBarDemoApp. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [demo video](https://www.youtube.com/watch?v=RZLx03OPpUU) — iOS Dev Weekly · Issue 276 — Video · Topics: Graphics, Media & Games · Testing
  **Published:** `11th November 2016`
  **NeKI brief:** Want to develop for the touch bar on-device, but don’t have a shiny new MacBook? Andreas Verhoeven and Robbert Klarenbeek have just the thing for you. I haven’t tested this myself as I still haven’t upgraded to Sierra but it looks good from the demo video.
- [How to Use NSTouchBar on macOS](https://www.littlebitesofcocoa.com/281-touch-bar-basics) — iOS Dev Weekly · Issue 275 — Article · Topics: Objective-C & Cocoa
  **Published:** `4th November 2016`
  **NeKI brief:** Examines During yesterday's MacBook Pro event, Apple announced a fantastic new piece of hardware called the Touch Bar. It's a 1085 x 30 point matte-finish Retina screen that sits ab. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [significant thought and effort](http://shapeof.com/archives/2016/11/notes_on_working_with_nstouchbar_apis.html) — iOS Dev Weekly · Issue 275 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `4th November 2016`
  **NeKI brief:** The article records detailed thoughts on working with NSTouchBar APIs and the engineering effort required to integrate them.
- [SimPholders Beta and macOS Sierra](https://simpholders.com/beta) — iOS Dev Weekly · Issue 271 — Article
  **Published:** `7th October 2016`
  **NeKI brief:** I haven’t yet upgraded to Sierra (I know, shame on me!) so I had not come across this incompatibility with one of my favourite iOS development tools. Good news is there’s now a beta of v3 out which is fully compatible! 🎉
- [public beta](https://beta.apple.com/sp/betaprogram) — iOS Dev Weekly · Issue 258 — Article
  **Published:** `8th July 2016`
  **NeKI brief:** Discusses public beta, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [1 star reviews](https://techcrunch.com/2015/07/21/you-can-no-longer-leave-app-store-reviews-if-you-run-a-beta-version-of-ios) — iOS Dev Weekly · Issue 258 — Article
  **Published:** `8th July 2016`
  **NeKI brief:** Reports Apple’s historical change preventing beta iOS users from leaving App Store reviews. Useful context for interpreting review data and testing feedback pipelines, but not as a current App Store policy reference.
- [Neural Networks in iOS 10 and macOS](https://www.bignerdranch.com/blog/neural-networks-in-ios-10-and-macos) — iOS Dev Weekly · Issue 257 — Article · Topics: Graphics, Media & Games · macOS & AppKit · Networking
  **Published:** `1st July 2016`
  **NeKI brief:** Explores Neural Networks in iOS 10 and macOS in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Sierra and Gatekeeper Path Randomization](http://weblog.rogueamoeba.com/2016/06/29/sierra-and-gatekeeper-path-randomization) — iOS Dev Weekly · Issue 257 — Article
  **Published:** `1st July 2016`
  **NeKI brief:** Really interesting change to OS X macOS coming in Sierra. There’s some great discussion in the comments too.
- [The Talk Show](https://daringfireball.net/thetalkshow) — iOS Dev Weekly · Issue 255 — Article
  **Published:** `17th June 2016`
  **NeKI brief:** Examines Daring Fireball: The Talk Show. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [enhancements to accessibility](http://9to5mac.com/2016/06/15/accessibility-ios-10-macos-appletv-watch) — iOS Dev Weekly · Issue 255 — Article · Topics: Accessibility · macOS & AppKit
  **Published:** `17th June 2016`
  **NeKI brief:** This article surveys the accessibility enhancements announced across iOS 10, macOS, tvOS, and watchOS. It is useful historical context for tracing how Apple platform accessibility capabilities evolved and for identifying the system features an app should accommodate.
- [AgileCloudKit: iCloud Sync Gets Its Wings](https://blog.agilebits.com/2016/01/12/agilecloudkit-icloud-sync-gets-its-wings) — iOS Dev Weekly · Issue 233 — Article · Topics: Persistence & Synchronisation
  **Published:** `15th January 2016`
  **NeKI brief:** Examines Up until recently, iCloud sync in Mac apps has always been dependent on the app being available in the MAS. This is a pain for developers, and potentially confusing for users if you sell both a MAS and a non-MAS version Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Acorn 5’s Live Help Search](http://shapeof.com/archives/2015/8/acorn_5_search_index.html) — iOS Dev Weekly · Issue 213 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `28th August 2015`
  **NeKI brief:** Presents Acorn 5’s Live Help Search, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Acorn 5](http://flyingmeat.com/acorn) — iOS Dev Weekly · Issue 213 — Article · Topics: Objective-C & Cocoa
  **Published:** `28th August 2015`
  **NeKI brief:** Examines Acorn is an awesome image editor for the Mac. Use Acorn to edit photos, add filters, retouch pictures, paint, crop, add text, create new images, and much more!. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Half-Assed](http://furbo.org/2015/07/22/half-assed) — iOS Dev Weekly · Issue 208 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games · Product Design
  **Published:** `24th July 2015`
  **NeKI brief:** Discusses Half-Assed, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [worth a read](http://bitsplitting.org/2015/07/23/six-in-one) — iOS Dev Weekly · Issue 208 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games · Product Design
  **Published:** `24th July 2015`
  **NeKI brief:** Examines Craig Hockenberry's "Half-Assed" calls out the disparity between Apple's Mac and iOS App Stores with respect to app analytics, limiting customer reviews from be. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [NotificationExtensionTest](https://github.com/hamzasood/NotificationExtensionTest) — iOS Dev Weekly · Issue 206 — Source repository · Topics: Developer Tools · Graphics, Media & Games · Testing
  **Published:** `10th July 2015`
  **NeKI brief:** Animated GIF notifications for everyone! Hamza Sood has been digging around with an undocumented feature in El Capitan. Check out the demo video for a quick look at what’s possible. Note: This may never make it as a feature we can use, but it’s interesting…
- [updates to Swift](http://www.russbishop.net/swift-2-beta-2) — iOS Dev Weekly · Issue 204 — Article · Topics: Swift
  **Published:** `26th June 2015`
  **NeKI brief:** Explains updates to Swift with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Sparkler](https://github.com/mackuba/sparkler) — iOS Dev Weekly · Issue 198 — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **Published:** `15th May 2015`
  **NeKI brief:** Presents Sparkler, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [App Design on Yosemite](http://www.git-tower.com/blog/tower2-yosemite-design) — iOS Dev Weekly · Issue 193 — Article · Topics: Developer Tools
  **Published:** `10th April 2015`
  **NeKI brief:** The page covers “App Design on Yosemite” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Force Touch APIs](http://9to5mac.com/2015/03/12/apple-releases-os-x-10-10-3-build-14d98-with-photos-app) — iOS Dev Weekly · Issue 189 — Article
  **Published:** `13th March 2015`
  **NeKI brief:** Reports evidence of dedicated Force Touch APIs in an OS X 10.10.3 build. It is historical reporting from before Force Touch's later platform rollout.
- [BBEdit is leaving the Mac App Store](http://sixcolors.com/post/2014/10/bbedit-at-max-q) — iOS Dev Weekly · Issue 168 — Article · Topics: App Distribution & Store Operations
  **Published:** `17th October 2014`
  **NeKI brief:** Discusses BBEdit is leaving the Mac App Store, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [Panic making the same decision with Coda](http://www.panic.com/blog/coda-2-5-and-the-mac-app-store) — iOS Dev Weekly · Issue 168 — Article · Topics: App Distribution & Store Operations
  **Published:** `17th October 2014`
  **NeKI brief:** With the announcement that BBEdit is leaving the Mac App Store at Çingleton last weekend and Panic making the same decision with Coda a few months ago it has to be time for another look at what could be improved. Milen Dzhumerov does the honours.
- [Take This Code and Sign It](http://indiestack.com/2014/08/take-this-code-and-sign-it) — iOS Dev Weekly · Issue 158 — Article
  **Published:** `8th August 2014`
  **NeKI brief:** As of 10.9.5 (and 10.10 when it’s released) if your Mac app is signed with an older version 1 signature then Gatekeeper will not allow it to launch! Apple announced this in TN2206 and the change is going live fairly soon (10.9.5 is already in beta). Daniel…
- [follow up post](http://indiestack.com/2014/08/re-signing-code) — iOS Dev Weekly · Issue 158 — Article
  **Published:** `8th August 2014`
  **NeKI brief:** As of 10.9.5 (and 10.10 when it’s released) if your Mac app is signed with an older version 1 signature then Gatekeeper will not allow it to launch! Apple announced this in TN2206 and the change is going live fairly soon (10.9.5 is already in beta). Daniel…
- [Inspecting Yosemite’s Icons](http://martiancraft.com/blog/2014/07/inspecting-yosemite-icons) — iOS Dev Weekly · Issue 153 — Article
  **Published:** `4th July 2014`
  **NeKI brief:** The article inspects OS X Yosemite icons and analyzes their visual construction and design details.
- [OS X and Helvetica Neue](http://furbo.org/2014/04/18/get-ready-for-june-2nd) — iOS Dev Weekly · Issue 143 — Article · Topics: Apple Platform Ecosystem
  **Published:** `25th April 2014`
  **NeKI brief:** Examines There’s no doubt in my mind that Apple is going to overhaul the look of Mac OS X in the next version. As more and more apps bridge the gap between the desktop and mobile, the. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [QuickTime Banned From Mac App Store](http://mjtsai.com/blog/2014/04/01/quicktime-banned-from-mac-app-store) — iOS Dev Weekly · Issue 140 — Article · Topics: App Distribution & Store Operations
  **Published:** `4th April 2014`
  **NeKI brief:** Examines Michael Tsai sums up the details of Drew McCormack’s recent rejection for using QTKit in an app. It seems really soon to start rejecting apps that use an API that was deprecated less than 6 months ago and this causes big Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [A Typographic Approach to Email](http://blog.weare1910.com/post/78113100010/a-typographic-approach-to-email) — iOS Dev Weekly · Issue 136 — Article
  **Published:** `7th March 2014`
  **NeKI brief:** Discusses typography choices for email layouts and the constraints imposed by inconsistent clients. Useful for understanding why visual hierarchy and fallback design matter when content crosses rendering environments.
- [Open Sourcing OmniGraphSketcher](http://www.omnigroup.com/blog/setting-omnigraphsketcher-free) — iOS Dev Weekly · Issue 130 — Article
  **Published:** `24th January 2014`
  **NeKI brief:** The Omni Group post announces open-sourcing OmniGraphSketcher and explains the project's availability and development context.
- [Silhouette](https://github.com/fraserhess/silhouette) — iOS Dev Weekly · Issue 127 — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **Published:** `3rd January 2014`
  **NeKI brief:** Examines Sparkle profiling for the Mac App Store. Contribute to fraserhess/silhouette development by creating an account on GitHub. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Automating OS X app test build distribution across multiple OS versions](http://www.cimgf.com/2013/12/17/automating-os-x-app-test-build-distribution-across-multiple-os-versions) — iOS Dev Weekly · Issue 125 — Article · Topics: Testing
  **Published:** `20th December 2013`
  **NeKI brief:** Explains Automating OS X app test build distribution across multiple OS versions with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a.
- [BeaconEmitter](https://github.com/lgaches/BeaconEmitter) — iOS Dev Weekly · Issue 119 — Source repository · Topics: Developer Tools · Testing
  **Published:** `8th November 2013`
  **NeKI brief:** Provides macOS code for emitting iBeacon advertisements, based on CoreBluetooth-style beacon behavior. It is useful when prototyping proximity signals or testing beacon consumers without dedicated beacon hardware.
- [OS X Application Testing Mindmap](http://objdev.com/2013/10/OS-X-Application-Testing-Mindmap) — iOS Dev Weekly · Issue 118 — Article · Topics: Testing
  **Published:** `1st November 2013`
  **NeKI brief:** I linked to Nick Arnott’s iOS testing mind map back in issue 58 and now Cory Bohon has taken it and made an alternative version for testing OS X apps. Lots of edge cases mentioned here and this would make a great place to start when planning testing of a new…
- [Mac App Store Receipts and Mavericks](http://furbo.org/2013/10/21/mac-app-store-receipts-and-mavericks) — iOS Dev Weekly · Issue 117 — Article · Topics: App Distribution & Store Operations
  **Published:** `25th October 2013`
  **NeKI brief:** This post investigates Mac App Store receipt behavior around Mavericks and the validation assumptions developers had to make at the time. It offers historical context for designing entitlement and receipt checks that tolerate platform-version differences.
- [Code Signing and Mavericks](http://furbo.org/2013/10/17/code-signing-and-mavericks) — iOS Dev Weekly · Issue 116 — Article · Topics: App Distribution & Store Operations
  **Published:** `18th October 2013`
  **NeKI brief:** Explains Code Signing and Mavericks with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [JNWCollectionView](https://github.com/jwilling/JNWCollectionView) — iOS Dev Weekly · Issue 111 — Source repository · Topics: Developer Tools
  **Published:** `13th September 2013`
  **NeKI brief:** Examines Customizable and performant collection view for the Mac. - jwilling/JNWCollectionView. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [OmniKeyMaster: Upgrade Pricing for Mac App Store Customers](http://www.omnigroup.com/blog/entry/omnikeymaster-upgrade-pricing-for-mac-app-store-customers) — iOS Dev Weekly · Issue 109 — Article · Topics: App Distribution & Store Operations
  **Published:** `30th August 2013`
  **NeKI brief:** Examines The most disappointing thing to me about this article is the entire premise of the article is based around moving people off the Mac App Store. I love the convenience and licensing terms of the Mac App Store so much, I w Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [SDMMobileDevice](https://github.com/samdmarshall/SDMMobileDevice) — iOS Dev Weekly · Issue 107 — Source repository · Topics: Developer Tools · Security & Privacy
  **Published:** `16th August 2013`
  **NeKI brief:** The GitHub repository contains SDMMobileDevice, an open-source project for interacting with mobile-device services on Apple platforms.
- [Butter](https://github.com/ButterKit/Butter) — iOS Dev Weekly · Issue 104 — Source repository · Topics: Developer Tools
  **Published:** `26th July 2013`
  **NeKI brief:** Examines A big shot of epicness for AppKit. It's time to put a jetpack on your tricycle. - ButterKit/Butter. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Everything you need to know about OS X Mavericks](http://www.macworld.com/article/2041581/faq-everything-you-need-to-know-about-os-x-mavericks.html) — iOS Dev Weekly · Issue 98 — Article · Topics: Cross-Platform & Web
  **Published:** `14th June 2013`
  **NeKI brief:** With all of the iOS 7 talk, it’s easy to forget that we also had an announcement of a major new version of Mac OS this week as well.
- [Getting rid of “Open With” duplicates](http://www.leancrew.com/all-this/2013/02/getting-rid-of-open-with-duplicates) — iOS Dev Weekly · Issue 82 — Article · Topics: Developer Tools
  **Published:** `22nd February 2013`
  **NeKI brief:** Examines If you develop for OS X then I am sure you will be familiar with this problem but even if you don’t then it is likely that you have seen multiple copies of apps appear on the Open With menu over time. This quick bash ali Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Mac App Store: Year Two](http://www.macstories.net/stories/mac-app-store-year-two) — iOS Dev Weekly · Issue 76 — Article · Topics: App Distribution & Store Operations
  **Published:** `11th January 2013`
  **NeKI brief:** Examines It doesn’t seem like two years since the Mac App Store debuted and to mark the anniversary Federico Viticci has written a comprehensive retrospective on the story so far. Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Coda and Sandboxing](http://www.panic.com/blog/2012/12/coda-and-sandboxing) — iOS Dev Weekly · Issue 72 — Article · Topics: App Distribution & Store Operations · Performance · Security & Privacy
  **Published:** `14th December 2012`
  **NeKI brief:** Explains Coda and Sandboxing with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [MASPreferences](https://github.com/shpakovski/MASPreferences) — iOS Dev Weekly · Issue 69 — Source repository · Topics: Developer Tools
  **Published:** `23rd November 2012`
  **NeKI brief:** Examines Modern implementation of the Preferences window for OS X apps, used in TextMate, GitBox and Mou: - cocoabits/MASPreferences. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Developers stymied by Mac App Store approval delays](http://www.macworld.com/article/2011430/developers-stymied-by-mac-app-store-approval-delays.html) — iOS Dev Weekly · Issue 63 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `12th October 2012`
  **NeKI brief:** So we hit the news a little this week with several stories about the steadily increasing Mac App Store review times triggered by data from our review times site. I have always been a defender of the App Store review processes and so I am really sad to see…
- [Retina for Masochists](http://furbo.org/2012/09/12/retina-for-masochists) — iOS Dev Weekly · Issue 59 — Article
  **Published:** `14th September 2012`
  **NeKI brief:** Examines Today we released an update for xScope that supports the Retina display. As I alluded to on Episode 14 of The Talk Show, this update was harder than most. The 68k to PowerPC, Carbo. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Build Doom3 on MacOSX with Xcode 4](http://fabiensanglard.net/doom3_macosx/index.php) — iOS Dev Weekly · Issue 18 — Article · Topics: Code Quality · macOS & AppKit · Xcode
  **Published:** `2nd December 2011`
  **NeKI brief:** Explains Build Doom3 on MacOSX with Xcode 4 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [Alt-Tab window switching for macOS](https://go.peterfriese.dev/alt-tab-window-switching?s=newsletter&t=ext) — Not only Swift · Issue 97 — Article · Topics: AI Development · Developer Tools
  **NeKI brief:** Covers a macOS utility for switching between windows rather than only applications. It is useful as a small productivity-tool reference for developers working across Xcode, simulators, terminals, and documentation.
- [Textream - Live Teleprompter for macOS](https://blog.fka.dev/textream) — Not only Swift · Issue 93 — Article · Topics: Developer Tools
  **NeKI brief:** Introduces Textream, a native macOS live teleprompter for displaying text while presenting or recording. It is a concrete example of a focused desktop utility and its presentation-oriented interaction model.
- [Trees: Effortless Git worktrees in your menu bar](https://github.com/afterxleep/trees) — Not only Swift · Issue 91 — Source repository · Topics: AI Development · Developer Tools · macOS & AppKit
  **NeKI brief:** This source repository covers macOS menu-bar management for Git worktrees. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Distribute your Swift CLIs for macOS](https://swifttoolkit.dev/posts/distribute-swift-clis) — Not only Swift · Issue 79 — Article · Topics: Developer Community & Business · Swift
  **NeKI brief:** This article covers distributing Swift command-line tools for macOS. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [CodeEditorView: A SwiftUI Code Editor for iOS, visionOS, and macOS](https://github.com/mchakravarty/CodeEditorView) — Not only Swift · Issue 79 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Presents a concrete implementation of CodeEditorView: A SwiftUI Code Editor for iOS, visionOS, and macOS. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.
