# SwiftLee Weekly

Third-party source index. It provides source attribution and routing metadata, not republished article content. Verify article conclusions independently before applying them.

- Archive: [https://newsletter.avanderlee.com/posts](https://newsletter.avanderlee.com/posts)
- Last collected: `2026-08-27T19:22:09Z`
- Indexed entries: **98**

## [Issue 338](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-338-1)

- Published: `2026-08-25T14:06:16.000Z`

**Topics:** AI Development · Performance · Swift · SwiftUI · Testing · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · @StateObject vs. @ObservedObject: The differences explained · Turn Xcode Instruments Traces Into Ranked Performance Evidence

**NeKI brief:** Curates community reading on Observation, macOS dylib inspection, adaptive SwiftUI layout, and StateReporting, alongside existing SwiftUI and Foundation Models articles. Sponsor, primary-source proposal, and newsletter-navigation links are not selected reading.

**Selected links:**
- [Apple Foundation Models: Hybrid AI with Dynamic Profiles](https://peterfriese.dev/blog/2026/hybrid-ai-apple-foundation-models-gemini) — Article · Topics: AI Development · Foundation & Data Formats · Performance
  **NeKI brief:** Uses Foundation Models dynamic profiles to choose between an on-device model and Gemini through Firebase AI Logic. The design makes privacy, capability, availability, and network trade-offs explicit at the request-routing boundary.
- [withContinuousObservation in Swift](https://livsycode.com/swift/withcontinuousobservation-in-swift) — Article · Topics: Observation & State Management · Swift
  **NeKI brief:** Explains iOS 27’s withContinuousObservation(options:apply:) for non-View consumers that must re-register dependencies after each change, contrasting it with one-shot withObservationTracking.
- [Building adaptive SwiftUI layouts with containerRelativeFrame()](https://nilcoalescing.com/blog/BuildingAdaptiveSwiftUILayoutsWithContainerRelativeFrame) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows how containerRelativeFrame() sizes and positions SwiftUI content relative to its container, making layouts adapt cleanly across split views, navigation surfaces, and different window sizes.
- [Returned For RevisionSE-0539Enable Macros to Grant `self` Access for Property Initializers](https://github.com/apple/swift-evolution/blob/main/proposals/0539-self-access-for-property-initializers.md) — Source repository · Topics: Developer Tools · Macros & Metaprogramming · Swift
  **NeKI brief:** Proposal SE-0539 explores allowing attached macros to grant controlled self access during property initialization. Follow it when macro-generated storage needs enclosing-instance context, while checking review status and initialization-safety constraints before relying on the feature.
- [Detecting (Evil) Dylibs](https://objective-see.org/blog/blog_0x89.html) — Article · Topics: Cross-Platform & Web · Security & Privacy
  **NeKI brief:** Surveys static, runtime, and load-time enumeration of dynamic libraries as a basis for detecting dylib-based attacks on modern macOS, including the limits of current mitigations.
- [AcceptedSE-0543InlineArray: Hashable](https://github.com/apple/swift-evolution/blob/main/proposals/0543-inline-array-hashable.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Proposes conditional Equatable and Hashable conformances for InlineArray when its elements qualify, using elementwise equality and hashing every element with linear complexity.
- [Active ReviewSE-0546Same-file memberwise initializer extensions](https://github.com/apple/swift-evolution/blob/main/proposals/0546-memberwise-init-extensions.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Specifies SE-0546, which permits a same-file extension to declare a memberwise initializer with broader access. It defines the matching rules and explains how an explicit initializer interacts with synthesis, helping library authors expose stable construction APIs without changing ABI behavior.
- [What’s new in Swift 6.4](https://swiftlee-weekly.com/swift-evolution/releases/swift-6-4) — Article · Topics: Swift
  **NeKI brief:** Summarizes the 23 proposals implemented in Swift 6.4 beta, grouping ergonomics, ownership, concurrency, warnings, and memory safety. It links individual proposal status to practical adoption guides, but final availability should be checked against the selected toolchain.
- [iOS 27: StateReporter](https://antongubarenko.substack.com/p/ios-27-statereporter) — Article
  **NeKI brief:** Introduces iOS 27 StateReporting for attaching concise application-state transitions and metadata to MetricKit diagnostics, helping connect hangs or hitches to the user activity that preceded them.

## [Issue 337](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-337)

- Published: `2026-08-18T14:06:21.000Z`

**Topics:** AI Development · CI/CD & Automation · Swift · SwiftUI · Testing · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · Swift Testing explained with code examples · Fastlane alternative - Codemagic CLI tools

**NeKI brief:** Combines Swift Testing, Codemagic tooling, DataDetector, testable SwiftUI navigation, headless Xcode MCP, PhaseAnimator, and ContentBuilder. The issue is a compact route to current testing, automation, framework, and compiler-performance reading.

**Selected links:**
- [Headless Xcode: From Prompt to Simulator with MCP](https://artemnovichkov.com/blog/headless-xcode-from-prompt-to-simulator-with-mcp) — Article · Topics: AI Development · Testing · Xcode
  **NeKI brief:** Walks through Xcode 27's xcrun mcp-server, its separate service and project permission gates, exported Apple agent skills, headless previews, and simulator verification. It also identifies the beta tooling and administrator-account constraints.
- [AcceptedSE-0537Section Placement Control for Functions](https://github.com/apple/swift-evolution/blob/main/proposals/0537-function-sections.md) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Extends Swift's section placement attribute from stored data to functions, initializers, deinitializers, closures, and accessors, while adding a default-section override. The motivation is precise linker placement for firmware entry points and embedded startup code.
- [Active ReviewSE-0545SwiftPM Build Performance Debugging Options](https://github.com/apple/swift-evolution/blob/main/proposals/0545-build-debugging-options.md) — Source repository · Topics: Developer Tools · Performance · Swift
  **NeKI brief:** Proposes SwiftPM flags for Trace Event output and task backtraces across build-running commands. The generated timing, dependency, and optional stack data is intended to diagnose parallelism, invalidation, and clean or incremental build bottlenecks.
- [Fastlane alternative - Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository · Topics: CI/CD & Automation · Developer Tools
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [ContentBuilder Explained - The Secret Behind SwiftUI's Type-Checking Speedup](https://fatbobman.com/en/posts/contentbuilder-explained) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Dissects ContentBuilder as a separation between content construction and protocol-specific validation, then benchmarks the resulting type-checking gains. It also explains where the pattern helps shared SwiftUI APIs and where it is not a cure-all.
- [Unit Testing Navigation Logic In Swiftui](https://azamsharp.com/2026/08/13/unit-testing-navigation-logic-in-swiftui.html) — Article · Topics: Swift · SwiftUI · Testing
  **NeKI brief:** Moves business-dependent destinations into explicit router state so registration roles and conditions can be tested without driving NavigationStack UI. The example separates navigation decisions from view presentation and asserts the resulting route directly.
- [Creating multi-step animations with PhaseAnimator in SwiftUI](https://nilcoalescing.com/blog/PhaseAnimationsInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds ordered SwiftUI animation sequences with PhaseAnimator, using phase values and per-phase transitions for repeating motion and event-triggered runs. The examples clarify when phase-based state is simpler than coordinating several independent animations.
- [iOS 26: DataDetector](https://antongubarenko.substack.com/p/ios-26-data-detector) — Article
  **NeKI brief:** Shows how the Swift-native DataDetector replaces NSTextCheckingResult-style branching with typed matches for links, contacts, calendar events, addresses, and other semantic objects. The examples make the migration from NSDataDetector concrete.

## [Issue 336](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-336)

- Published: `2026-08-11T14:07:13.000Z`

**Topics:** Concurrency · Performance · Swift · SwiftUI · Testing · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · Sendable and @Sendable closures explained with code examples · What are you shipping this month?

**NeKI brief:** Collects critical AI-use guidance, new SwiftUI shape and toolbar techniques, Swift Evolution changes and the emerging portable Agent Plugins format.

**Selected links:**
- [Concentric Buttons with OS 27's SwiftUI APIs](https://alexanderweiss.dev/blog/2026-08-09-concentric-button-os-27-swiftui-apis) — Article · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Builds a custom SwiftUI button border from GeometryProxy.concentricCornerRadii, including container-shape requirements, nil fallback behavior and the limitation that ButtonBorderShape remains closed.
- [Adaptive SwiftUI toolbars in iOS 27](https://nilcoalescing.com/blog/AdaptiveSwiftUIToolbarsInIOS27) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains iOS 27 toolbar visibility priorities, explicit overflow placement, trailing-edge pinning and navigation-bar minimization so important actions survive compact layouts.
- [AcceptedSE-0516`Iterable`](https://github.com/apple/swift-evolution/blob/main/proposals/0516-borrowing-sequence.md) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0516`Iterable`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [AcceptedSE-0535Add CLI for editing global mirrors configuration](https://github.com/apple/swift-evolution/blob/main/proposals/0535-global-mirrors-configuration-cli.md) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Adds a --global option to SwiftPM's mirror configuration commands so user-wide mirrors can be viewed and edited outside a package directory without changing existing local behavior.
- [Active ReviewSE-0541Flexible Swift/C Interoperability for Packages](https://github.com/apple/swift-evolution/blob/main/proposals/0541-flexible-swift-c-interoperability-for-packages.md) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Proposes mixed Swift and C-family sources in SwiftPM targets, bridging-header manifest support and sounder generated-header consumption for package interoperability.
- [Active ReviewSE-0543InlineArray: Hashable](https://github.com/apple/swift-evolution/blob/main/proposals/0543-inline-array-hashable.md) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Proposes conditional Equatable and Hashable conformances for InlineArray when its elements qualify, using elementwise equality and hashing every element with linear complexity.
- [My Swift Concurrency Agent Skill should already work](https://github.com/AvdLee/Swift-Concurrency-Agent-Skill/releases/tag/2.2.0) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Updates the Swift concurrency skill with approachable-concurrency settings, Xcode defaults and SendableMetatype guidance while adopting the Agent Plugins 1.0 portable package format.
- [Using AI while exercising your critical thinking](https://swiftrocks.com/using-ai-without-losing-critical-thinking) — Article · Topics: AI Development · Swift
  **NeKI brief:** Argues that developers must verify AI claims and retain engineering judgment, framing uncritical relay of model output as cognitive surrender rather than productive delegation.
- [Controlling Orphans in SwiftUI Text using an undocumented method](https://fatbobman.com/en/posts/controlling-orphans-in-swiftui-text) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Investigates SwiftUI Text's automatic orphan avoidance and an undocumented avoidsOrphans control, while warning that relying on the hidden API carries compatibility and review risk.
- [a new open standard for Agent Plugins](https://www.youtube.com/watch?v=UaeWJK_vv-Y) — Video
  **NeKI brief:** Introduces the portable Agent Plugins standard for bundling reusable agent capabilities so skills and related tooling can move between compatible coding harnesses.

## [Issue 335](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-335)

- Published: `2026-08-04T14:04:01.000Z`

**Topics:** Concurrency · Developer Community & Business · Persistence & Synchronisation · Swift · SwiftData · Testing

**Sections:** SwiftLee Weekly by Antoine van der Lee · @MainActor in Swift explained with code examples · Let AI Control the iOS Simulator

**NeKI brief:** Curates current reading on Media Intelligence, SwiftData synchronisation and testing, protocol isolation and Swift 6.2 thread hopping. The mix is useful for comparing data-layer and concurrency techniques before checking their current platform constraints.

**Selected links:**
- [Building Testable SwiftData Apps](https://azamsharp.com/2026/08/02/building-testable-swiftdata-apps.html) — Article · Topics: Swift · SwiftData · Testing
  **NeKI brief:** Structures SwiftData code so model containers and observations can be exercised outside a SwiftUI view hierarchy. Use it to test persistence behavior and query-driven updates without coupling every assertion to UI rendering.
- [AcceptedSE-0526withDeadline](https://github.com/apple/swift-evolution/blob/main/proposals/0526-deadline.md) — Source repository · Topics: Developer Tools · Swift · SwiftData
  **NeKI brief:** Proposal SE-0526 adds withDeadline for time-bounded asynchronous work. Read it to distinguish deadline expiry from ordinary cancellation and failure, and verify accepted semantics and toolchain availability before designing a public timeout API around it.
- [Active ReviewSE-0539Enable Macros to Grant `self` Access for Property Initializers](https://github.com/apple/swift-evolution/blob/main/proposals/0539-self-access-for-property-initializers.md) — Source repository · Topics: Developer Tools · Macros & Metaprogramming · Swift
  **NeKI brief:** Proposal SE-0539 explores allowing attached macros to grant controlled self access during property initialization. Follow it when macro-generated storage needs enclosing-instance context, while checking review status and initialization-safety constraints before relying on the feature.
- [Avoiding Duplicate Data When SwiftData Syncs Across Devices](https://thorsten-stark.de/posts/2026-08-06-Avoiding-Duplicate-Data-With-SwiftData-iCloud-Sync-Part-2) — Article · Topics: Swift · SwiftData
  **NeKI brief:** Explains why independently seeded SwiftData defaults duplicate when CloudKit later merges device stores, and uses stable identifiers to make seeding idempotent. The pattern is useful for distinguishing local bootstrap state from synchronised identity.
- [Swift protocols and the main actor](https://www.swiftbysundell.com/articles/swift-protocols-and-the-main-actor) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Compares isolating an entire protocol with isolating individual requirements. The examples expose how conformance placement can affect a type's actor isolation and why requirement-level annotations give custom actors a more flexible boundary.
- [Demystifying Thread Hopping with Swift 6.2 Approachable Concurrency](https://www.nsvasilev.com/posts/approachable_concurrency) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains Swift 6.2 thread hopping under Approachable Concurrency, especially the effect of nonisolated-nonsending defaults on executor inheritance. Use it to reason about isolation and scheduling without treating a particular thread as the concurrency contract.
- [iOS 27: Media Intelligence](https://antongubarenko.substack.com/p/ios-27-media-intelligence-framework) — Article
  **NeKI brief:** Introduces iOS 27’s Media Intelligence framework for analysing video and grouping detected faces, including the need for a physical device. Use it as an implementation lead while confirming supported media, privacy behavior, and final SDK availability.

## [Issue 324 · 2026-07-28](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-324-1)

- Published: `2026-07-28T14:07:11.000Z`

**Topics:** Combine & Reactive Programming · Developer Community & Business · Swift · SwiftUI · Testing · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · How to free up Xcode disk space safely with an AI Agent · Let AI Control the iOS Simulator

**NeKI brief:** Curates Apple's TrueType interpreter migration to Swift, SwiftUI blend modes, creative Markdown links, UIBarMinimization and modern app icons. Follow the issue for language-migration evidence and UI techniques spanning implementation and design.

**Selected links:**
- [iOS 27: UIBarMinimization](https://antongubarenko.substack.com/p/ios-27-uibarminimization) — Article · Topics: SwiftUI · UIKit
  **NeKI brief:** Separates UIKit navigation-bar minimisation into trigger, restoration, and safe-area decisions, then compares the corresponding SwiftUI toolbar behaviour. The examples are useful for replacing custom scroll-offset handling while the iOS 27 API remains beta.
- [Blend modes in SwiftUI](https://nilcoalescing.com/blog/BlendModesInSwiftUI) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Catalogues all 21 SwiftUI blend modes with focused visual examples and explains their colour or alpha calculations. The closing compositingGroup examples clarify how to constrain which sibling views participate in a blend operation.
- [Markdown links can do what?](https://jacobzivandesign.com/technology/links_in_swiftui_markdown_do_what) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows how SwiftUI Markdown links can trigger application actions by combining custom URL schemes with OpenURLAction instead of opening a web page. Use the technique when inline text needs accessible, link-like commands with explicit routing.
- [Swift at Apple: Migrating the TrueType Hinting Interpreter](https://www.swift.org/blog/migrating-truetype-hinting-to-swift) — Article · Topics: Swift
  **NeKI brief:** Describes Apple’s migration of the security-sensitive TrueType hinting interpreter from C to memory-safe Swift, including a reported average performance improvement and published source. It is useful evidence for evaluating incremental systems-code rewrites rather than assuming safety costs speed.
- [What’s an Icon in 2026?](https://blog.jim-nielsen.com/2026/icons-as-software) — Article
  **NeKI brief:** Examines how Icon Composer turns an app icon from one static asset into layered, stateful output rendered by platform software. The essay is useful for considering toolchain dependence, portability, and what source material an icon now represents.

## [Issue 323 · 2026-07-21](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-323-1)

- Published: `2026-07-21T14:05:55.000Z`

**Topics:** Architecture · Developer Community & Business · Objective-C & Cocoa · Swift · SwiftUI · Testing

**Sections:** SwiftLee Weekly by Antoine van der Lee · How to Test iOS Apps in Different Time Zones on a Physical iPhone · Share your AI agent’s work with your team

**Selected links:**
- [ImplementedSE-0522Source-Level Control Over Compiler Warnings](https://github.com/apple/swift-evolution/blob/main/proposals/0522-source-warning-control.md) — Source repository · Topics: Architecture · Developer Tools · Swift
  **NeKI brief:** Records ImplementedSE-0522Source-Level Control Over Compiler Warnings, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [ImplementedSE-0525Safe loading API for `RawSpan`](https://github.com/apple/swift-evolution/blob/main/proposals/0525-rawspan-safe-loading-api.md) — Source repository · Topics: Architecture · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0525Safe loading API for `RawSpan`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Building adaptive non-modal panels in SwiftUI](https://nilcoalescing.com/blog/BuildingAdaptiveNonModalPanelsInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a custom SwiftUI panel that changes from a bottom sheet to an edge-aligned panel using measured scene geometry, custom Layout, preferences, and detents. The drag implementation preserves scrolling by combining gestures deliberately.
- [Revisiting the JET iOS Modular Architecture in 2026](https://albertodebortoli.com/2026/07/15/revisiting-the-jet-ios-modular-architecture-in-2026) — Article · Topics: Architecture · Objective-C & Cocoa
  **NeKI brief:** Revisits Just Eat’s 2019 modular iOS model, retaining useful domain boundaries while refining module vocabulary and cross-domain dependencies for current Swift tooling. Use it to test whether an inherited architecture still matches team and build constraints.
- [Syncing SwiftData With A Custom Backend Using HistoryObserver](https://azamsharp.com/2026/07/16/syncing-swiftdata-with-a-custom-backend-using-historyobserver.html) — Article · Topics: Networking · Persistence & Synchronisation · SwiftData
  **NeKI brief:** Builds a one-way synchronisation pipeline from SwiftData HistoryObserver transactions to a REST backend. Persisting the last processed transaction token avoids duplicate uploads; server-to-client changes remain a separate responsibility.
- [RejectedSE-0533Generating synchronous overloads of `async` functions with a macro](https://github.com/apple/swift-evolution/blob/main/proposals/0533-reasync-macros.md) — Source repository · Topics: Architecture · Concurrency · Swift
  **NeKI brief:** Records RejectedSE-0533Generating synchronous overloads of `async` functions with a macro, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Active ReviewSE-0537Section Placement Control for Functions](https://github.com/apple/swift-evolution/blob/main/proposals/0537-function-sections.md) — Source repository · Topics: Architecture · Developer Tools · Swift
  **NeKI brief:** Extends Swift's section placement attribute from stored data to functions, initializers, deinitializers, closures, and accessors, while adding a default-section override. The motivation is precise linker placement for firmware entry points and embedded startup code.
- [Active ReviewSE-0538Disconnected](https://github.com/apple/swift-evolution/blob/main/proposals/0538-disconnected.md) — Source repository · Topics: Architecture · Developer Tools · Swift
  **NeKI brief:** Records Active ReviewSE-0538Disconnected, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Copywriting with Agents and…Apple Designers?](https://www.swiftjectivec.com/copywriting-with-agents-and-apple-designers) — Article · Topics: Swift
  **NeKI brief:** Uses agents to sharpen copy while retaining human design judgment, a useful workflow for treating generated language as a draft that still needs product voice and platform-specific review.
- [Geometry, compositing and drawing groups in SwiftUI](https://nilcoalescing.com/blog/GeometryCompositingAndDrawingGroupsInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Separates geometryGroup, compositingGroup, and drawingGroup by the stage of rendering or animation they affect. The comparison helps diagnose visual artifacts and choose a modifier based on actual compositing needs rather than similar names.

## [Issue 322 · 2026-07-14](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-322-1)

- Published: `2026-07-14T14:06:22.000Z`

**Topics:** CI/CD & Automation · Concurrency · Developer Community & Business · Liquid Glass · Swift · SwiftUI

**Sections:** SwiftLee Weekly by Antoine van der Lee · User Diagnostics Reports: Solving app bugs faster with AI Agents · Fastlane alternative - Codemagic CLI tools

**Selected links:**
- [The hidden cost of unstable SwiftUI environment defaults](https://nilcoalescing.com/blog/UnstableDefaultEnvironmentValuesInSwiftUI) — Article · Topics: Swift · SwiftUI · Xcode
  **NeKI brief:** Diagnoses update churn caused by reference-typed default environment values and explains why stable defaults matter. Useful when environment injection unexpectedly invalidates views or changes identity.
- [Splitting Large SwiftUI Views in the Apple's way](https://emredegirmenci.substack.com/p/splitting-large-swiftui-views-in) — Article · Topics: Swift · SwiftUI · Xcode
  **NeKI brief:** Explains Apple's own decomposition techniques for splitting large SwiftUI views, including state and builder boundaries. Useful for reducing oversized bodies while keeping data flow explicit, previewable, and understandable to teammates.
- [Fastlane alternative - Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository · Topics: CI/CD & Automation · Developer Tools
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [Active ReviewSE-0536Package Registry Search](https://github.com/apple/swift-evolution/blob/main/proposals/0536-registry-search.md) — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **NeKI brief:** Records Active ReviewSE-0536Package Registry Search, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [anyAppleOS in Swift 6.4](https://livsycode.com/swift/swift-6-4-adds-anyappleos-for-cleaner-availability-checks) — Article · Topics: Swift
  **NeKI brief:** Explains Swift 6.4's anyAppleOS type as a way to express availability checks without spelling every Apple platform. Use it when auditing cross-platform branches, while confirming the exact compiler and SDK version before adoption.
- [AcceptedSE-0532`Optional` noncopyable improvements and generalizations](https://github.com/apple/swift-evolution/blob/main/proposals/0532-optional-noncopyable-improvements.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Records AcceptedSE-0532`Optional` noncopyable improvements and generalizations, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Liquid Glass can be gradually rolled out](https://www.scottberrevoets.com/til/liquid-glass-can-be-gradually-rolled-out) — Article · Topics: Liquid Glass
  **NeKI brief:** Shows how Liquid Glass adoption can be staged instead of switching an entire interface at once. Use it when planning incremental visual migrations, with separate review of fallback behavior and platform availability.
- [iOS27: CADisplayLink for UIWindowScene](https://antongubarenko.substack.com/p/ios27-cadisplaylink-for-uiwindowscene) — Article
  **NeKI brief:** This article explains why CADisplayLink is frame-synchronized while Timer is schedule-based, then applies that distinction to visual periodic work in a UIWindowScene. It helps decide when display-refresh timing is appropriate for iOS 27 UI updates.

## [Issue 331](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-331)

- Published: `2026-07-07T14:05:55.000Z`

**Topics:** AI Development · Concurrency · Developer Community & Business · Swift · SwiftUI · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · Defer in Swift explained with Code Examples · Tired of Fixing Xcode UI Tests Every Release?

**Selected links:**
- [Debugging Notes on Two SwiftUI Animation Bugs](https://fatbobman.com/en/posts/debugging-notes-on-two-swiftui-animation-bugs) — Article · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Uses two concrete SwiftUI animation failures to show how declarative animation can obscure causality. Follow it when a transition or state-driven animation misbehaves and you need diagnostic observations that reveal the framework behaviour rather than only a workaround.
- [Rotating Liquid Glass in SwiftUI without breaking the shape](https://livsycode.com/swiftui/liquid-glass-rotating) — Article · Topics: Liquid Glass · Swift · SwiftUI
  **NeKI brief:** Artem explains how modifier order affects rotated Liquid Glass views in SwiftUI, and why applying rotation after the glass effect can break the intended shape instead of rotating the effect cleanly with the content.
- [physical devices](https://www.rocketsim.app/docs/features/capturing/physical-device-support) — Article · Topics: Apple Platform Ecosystem · Concurrency · Swift
  **NeKI brief:** Documents RocketSim capture support for USB-connected physical devices. Use it to evaluate a device-recording workflow for demos or bug evidence, checking supported OS versions and the operational limits of the tool.
- [AcceptedSE-0513API to get the path to the current executable](https://github.com/apple/swift-evolution/blob/main/proposals/0513-commandline-executablepath.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0513API to get the path to the current executable. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [10 Tips for Building iOS Apps That Handle Dynamic Type Well](https://mobilea11y.com/blog/good-dynamic-type) — Article · Topics: Accessibility
  **NeKI brief:** Rob shares practical guidelines for building Dynamic Type-friendly SwiftUI interfaces, covering adaptive layouts, scalable UI elements, and thoughtful tradeoffs for larger accessibility text sizes.
- [How To (Not) Spend $10k/wk on Coding Agents](https://allenpike.com/2026/how-to-not-spend-10k-on-coding-agents) — Article · Topics: AI Development
  **NeKI brief:** This field report describes progressively automating coding loops while adding tests, guardrails, review automation, and UX evidence as new bottlenecks appear. It is useful for evaluating where agent automation needs human checks instead of assuming productivity scales for free.
- [Introducing the Safari MCP server for web developers](https://webkit.org/blog/18136/introducing-the-safari-mcp-server-for-web-developers) — Article · Topics: AI Development · Cross-Platform & Web
  **NeKI brief:** Examines Safari now has an MCP! in the context of AI Development and CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 330](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-330)

- Published: `2026-06-30T14:07:37.000Z`

**Topics:** Concurrency · Developer Community & Business · Graphics, Media & Games · Swift · Swift Package Manager · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · Memberwise Initializer in Swift explained with Code Examples · Add AI Control to Xcode’s Simulator and Device Hub

**Selected links:**
- [ImplementedSE-0528`Continuation` — Safe and Performant Async Continuations](https://github.com/apple/swift-evolution/blob/main/proposals/0528-noncopyable-continuation.md) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0528`Continuation` — Safe and Performant Async Continuations. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0534Opt-in exact matching for version identifiers with build metadata](https://github.com/apple/swift-evolution/blob/main/proposals/0534-swiftpm-exact-literal-version-matching.md) — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0534Opt-in exact matching for version identifiers with build metadata. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ImplementedSE-0521Improved Syntax for Optionals of Opaque and Existential Types](https://github.com/apple/swift-evolution/blob/main/proposals/0521-improved-optional-opaque-and-any.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Records ImplementedSE-0521Improved Syntax for Optionals of Opaque and Existential Types, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Using Cursor in Xcode 27](https://www.polpiella.dev/cursor-xcode-27) — Article · Topics: Xcode
  **NeKI brief:** Explains installing Cursor’s agent CLI, registering it through Xcode 27’s ACP support, and selecting it for new conversations. Follow it when comparing external agent choice with Xcode’s remembered conversation-agent state.
- [iOS 27 SDK: 3 Major Requirements That Might Break Your App](https://blog.makwanbk.com/ios-27-sdk-3-major-requirements-that-migh-break-your-app) — Article · Topics: Xcode
  **NeKI brief:** Makwan highlights three iOS 27 SDK requirements that could break older apps or block App Store submission: UIScene support, the new launch screen requirement, and the end of the Liquid Glass compatibility opt-out.
- [AI Agents for the iOS Simulator](https://www.rocketsim.app/blog/ai-agents-ios-simulator) — Article · Topics: AI Development
  **NeKI brief:** Documents AI Agents for the iOS Simulator, focusing on an iOS Simulator workflow and the concrete debugging or testing decisions it enables for Apple-platform development.
- [All new frameworks presented at WWDC26](https://blog.eidinger.info/all-new-frameworks-presented-at-wwdc26) — Article · Topics: Apple Platform Ecosystem · Objective-C & Cocoa
  **NeKI brief:** This reference inventories the 14 frameworks introduced at WWDC26 and pairs each name with its Apple-platform purpose. It is useful as a compact discovery map before following the relevant primary documentation for App Intents, AI, routing, graphics, or testing work.
- [iOS Simulator Camera: Test Camera Flows](https://www.rocketsim.app/blog/ios-simulator-camera) — Article · Topics: Graphics, Media & Games · Testing
  **NeKI brief:** Documents iOS Simulator Camera: Test Camera Flows, focusing on an iOS Simulator workflow and the concrete debugging or testing decisions it enables for Apple-platform development.
- [Active ReviewSE-0526withDeadline](https://github.com/apple/swift-evolution/blob/main/proposals/0526-deadline.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Proposal SE-0526 adds withDeadline for time-bounded asynchronous work. Read it to distinguish deadline expiry from ordinary cancellation and failure, and verify accepted semantics and toolchain availability before designing a public timeout API around it.
- [Free The Icons](https://weblog.rogueamoeba.com/2026/06/26/free-the-icons) — Article
  **NeKI brief:** Presents Free The Icons, with practical context for Apple-platform developers evaluating the technique, workflow, or engineering decision described on the page.

## [Issue 329](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-329)

- Published: `2026-06-23T14:07:47.000Z`

**Topics:** App Intents & System Surfaces · Concurrency · Developer Community & Business · Swift · SwiftUI · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · Swift 6.4: What’s New in Concurrency · Add AI Control to Xcode’s Simulator and Device Hub

**Selected links:**
- [iOS 27, Your App, and Siri](https://www.swiftjectivec.com/siri-ai-for-ios027) — Article · Topics: AI Development · App Intents & System Surfaces · Swift
  **NeKI brief:** Jordan explains how iOS 27’s new Siri intelligence can work with your app’s data, covering AppEntity, app schemas, and APIs that help Siri understand and act on what’s currently on screen.
- [Active ReviewSE-0513API to get the path to the current executable](https://github.com/apple/swift-evolution/blob/main/proposals/0513-commandline-executablepath.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0513API to get the path to the current executable. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [What’s new in SwiftUI (2-minute recap)](https://www.swiftwithvincent.com/blog/whats-new-in-swiftui-2-minute-recap) — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Provides a concise tour of SwiftUI changes introduced around WWDC 2026. Use it to triage which new APIs deserve deeper investigation before reading their authoritative availability, behavior, and migration details.
- [SwiftUI: Observable macro under the hood](https://www.nsvasilev.com/posts/swiftui-observable-macro) — Article · Topics: Macros & Metaprogramming · Swift · SwiftUI
  **NeKI brief:** Peels back SwiftUI’s Observable macro expansion, showing the generated observation machinery behind an @Observable model. Useful when diagnosing tracking behavior, deciding which properties need observation, or explaining macro-generated code to a team.
- [Helm 2.3: WWDC & Helm CLI](https://helm-app.com/changelog/helm-2-3-helm-cli) — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem
  **NeKI brief:** Examines Automate your App Store Connect workflows with Helm’s new CLI! in the context of App Distribution & Store Operations and Apple Platform Ecosystem. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [From Size Class to Available Space - Is horizontalSizeClass Still Reliable?](https://fatbobman.com/en/posts/from-size-class-to-available-space) — Article
  **NeKI brief:** Explains why horizontalSizeClass is no longer a dependable width proxy once iPhone apps become freely resizable, and shifts layout decisions toward measured available space. The examples cover both SwiftUI and UIKit adaptation.

## [Issue 328](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-328)

- Published: `2026-06-16T14:06:32.000Z`

**Topics:** AI Development · Concurrency · Developer Community & Business · Swift · SwiftUI · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · SwiftUI Best Practices, straight from Apple's Xcode 27 Agent Skill · Stop configuring MCPs in every AI app

**Selected links:**
- [Stop configuring MCPs in every AI app](https://www.mcp-beast.ai/mac-app-ios-developers) — Article · Topics: AI Development · Developer Tools · Persistence & Synchronisation
  **NeKI brief:** Explores centralizing MCP configuration so multiple AI clients can share one setup. Use it when reducing repeated tool registration across development environments, while reviewing credential handling and client-specific capability differences.
- [WWDC26: Xcode Tips and Tricks Group Lab - Q&A](https://antongubarenko.substack.com/p/wwdc26-xcode-tips-and-tricks-group) — Article · Topics: Apple Platform Ecosystem · Testing · Xcode
  **NeKI brief:** Explains WWDC26: Xcode Tips and Tricks Group Lab - Q&A, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Release 4.0.0 · AvdLee/SwiftUI-Agent-Skill](https://github.com/AvdLee/SwiftUI-Agent-Skill/releases/tag/4.0.0) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Release 4.0.0 · AvdLee/SwiftUI-Agent-Skill. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Using Claude with Apple Foundation Models](https://artemnovichkov.com/blog/using-claude-with-apple-foundation-models) — Article · Topics: AI Development · Foundation & Data Formats
  **NeKI brief:** Artem shows how Claude can be used into Apple’s Foundation Models framework on iOS 27, using the same LanguageModelSessionAPI to switch between on-device models and Claude.
- [add 30+ features to Xcode's Device Hub](https://www.rocketsim.app/docs/features/capturing/device-hub-support) — Article · Topics: Apple Platform Ecosystem · Xcode
  **NeKI brief:** Documents add 30+ features to Xcode's Device Hub, focusing on an iOS Simulator workflow and the concrete debugging or testing decisions it enables for Apple-platform development.
- [What's New In Swiftdata](https://azamsharp.com/2026/06/12/whats-new-in-swiftdata.html) — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** Mohammad covers what’s new in SwiftData for iOS 27, showing how enum predicates, sectioned queries, compound predicates, the new .codable attribute, and ResultsObserver remove common workarounds.
- [Returned For RevisionSE-0526withDeadline](https://github.com/apple/swift-evolution/blob/main/proposals/0526-deadline.md) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Proposal SE-0526 adds withDeadline for time-bounded asynchronous work. Read it to distinguish deadline expiry from ordinary cancellation and failure, and verify accepted semantics and toolchain availability before designing a public timeout API around it.
- [Async cleanup with defer in Swift](https://tanaschita.com/swift-defer-async) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Shows how defer interacts with async and throwing Swift code so cleanup still occurs across suspension and errors. Use it to centralize resource release while keeping asynchronous lifetime and cancellation behavior explicit.
- [Custom scroll layouts with swipe actions in SwiftUI on iOS 27](https://nilcoalescing.com/blog/CustomScrollLayoutsWithSwipeActionsInSwiftUIOnIOS27) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows custom scroll layouts combined with swipe actions in SwiftUI on iOS 27. Use it when list-like interactions need nonstandard geometry without giving up contextual swipe affordances.

## [Issue 327](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-327)

- Published: `2026-06-09T21:59:45.000Z`

**Topics:** Apple Platform Ecosystem · Concurrency · Developer Community & Business · Swift · SwiftUI · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · Using Xcode 27's Agent Skills in Claude, Codex, and Cursor · Stop configuring MCPs in every AI app

**Selected links:**
- [Stop configuring MCPs in every AI app](https://www.mcp-beast.ai/mac-app-ios-developers) — Article · Topics: AI Development · Developer Tools · Persistence & Synchronisation
  **NeKI brief:** Explores centralizing MCP configuration so multiple AI clients can share one setup. Use it when reducing repeated tool registration across development environments, while reviewing credential handling and client-specific capability differences.
- [SwiftUI reorderable containers in iOS 27](https://livsycode.com/swiftui/swiftui-reorderable-containers-in-ios-27) — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Artem shares how SwiftUI’s new iOS 27 reorderable containers let you add drag-to-reorder support beyond List, using reorderable()and reorderContainer to make stacks, grids, and custom layouts easier to rearrange.
- [Initializing @Observable classes with the @State macro in Xcode 27](https://nilcoalescing.com/blog/InitializingObservableClassesWithTheStateMacroInXcode27) — Article · Topics: Macros & Metaprogramming · Observation & State Management · Xcode
  **NeKI brief:** Explains initializing an @Observable reference type through @State in current SwiftUI. Use it when a view owns an observable model and must preserve its identity across body recalculation rather than recreating it inline.
- [What is new in SwiftUI after WWDC26](https://swiftwithmajid.com/2026/06/08/what-is-new-in-swiftui-after-wwdc26) — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Summarizes SwiftUI additions after WWDC 2026. Use it to discover relevant new layout, rendering, and system-integration capabilities before narrowing to one feature and reading its authoritative API documentation.
- [Active ReviewSE-0478File-level defaults](https://github.com/apple/swift-evolution/blob/main/proposals/0478-default-isolation-typealias.md) — Source repository · Topics: Apple Platform Ecosystem · Developer Tools · Swift
  **NeKI brief:** Records Active ReviewSE-0478File-level defaults, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Active ReviewSE-0516`Iterable`](https://github.com/apple/swift-evolution/blob/main/proposals/0516-borrowing-sequence.md) — Source repository · Topics: Apple Platform Ecosystem · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0516`Iterable`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [AcceptedSE-0529Add `FilePath` to the Standard Library](https://github.com/apple/swift-evolution/blob/main/proposals/0529-filepath-in-stdlib.md) — Source repository · Topics: Apple Platform Ecosystem · Developer Tools · Swift
  **NeKI brief:** Records AcceptedSE-0529Add `FilePath` to the Standard Library, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Xcode Device Hub and the Future of RocketSim](https://www.rocketsim.app/blog/fixing-devicehub-xcode-simulator) — Article · Topics: Xcode
  **NeKI brief:** Documents Xcode Device Hub and the Future of RocketSim, focusing on an iOS Simulator workflow and the concrete debugging or testing decisions it enables for Apple-platform development.
- [iOS 27: Notable UIKit Additions](https://www.swiftjectivec.com/ios-27-notable-uikit-additions) — Article · Topics: Swift · UIKit
  **NeKI brief:** Jordan walks you through the notable UIKit additions in iOS 27, focusing on practical updates to navigation bars, bar buttons, scenes, windows, tab bars, sidebars, menus, and document launch screens.

## [Issue 326](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-326)

- Published: `2026-06-02T14:07:19.000Z`

**Topics:** AI Development · Apple Platform Ecosystem · Concurrency · Developer Community & Business · Graphics, Media & Games · Swift

**Sections:** SwiftLee Weekly by Antoine van der Lee · WWDC 2026: My predictions and wishes · Is Your iOS App Secure?

**Selected links:**
- [Task Names in Swift Concurrency](https://artemnovichkov.com/blog/task-names-in-swift-concurrency) — Article · Topics: Concurrency · Performance · Swift
  **NeKI brief:** Artem explains Swift Concurrency task names, showing how to label Task, Task.detached, task groups, and SwiftUI .task calls so they’re easier to identify in LLDB, Instruments, and logs.
- [W.W.D.C. 2026: The Pregame Quiz](https://www.swiftjectivec.com/wwdc-2026-the-pregame-quiz) — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Swift
  **NeKI brief:** Presents W.W.D.C. 2026: The Pregame Quiz, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Active ReviewSE-0532`Optional` noncopyable improvements and generalizations](https://github.com/apple/swift-evolution/blob/main/proposals/0532-optional-noncopyable-improvements.md) — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **NeKI brief:** Records AcceptedSE-0532`Optional` noncopyable improvements and generalizations, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Stateless Actors](https://www.massicotte.org/stateless-actors) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Examines stateless actors and what remains useful about actor isolation when no mutable state is stored. Follow it when choosing concurrency boundaries, distinguishing synchronization guarantees from mere type organization and measuring whether an actor adds real value.
- [DebugSnapshots: Public beta](https://www.pointfree.co/blog/posts/207-debugsnapshots-public-beta) — Article
  **NeKI brief:** Introduces DebugSnapshots for recording and inspecting application state as debugging artifacts. Use it when a visual or state regression needs reproducible evidence that can be reviewed without reproducing the entire interactive session.
- [Is Your iOS App Secure?](https://hubs.la/Q04b9pGH0) — Article · Topics: Security & Privacy
  **NeKI brief:** Discusses Is Your iOS App Secure?, providing concrete engineering context that Apple-platform developers can use when evaluating the referenced workflow.
- [Clearing UserDefaults during macOS app development](https://nilcoalescing.com/blog/ClearingUserDefaultsDuringmacOSAppDevelopment) — Article
  **NeKI brief:** Shows targeted UserDefaults cleanup during macOS development. Use it to reset persisted test state without deleting unrelated preferences, especially when a menu-bar or sandboxed app retains configuration between launches.

## [Issue 325](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-325)

- Published: `2026-05-26T14:06:24.000Z`

**Topics:** Concurrency · Developer Community & Business · Performance · Swift · SwiftUI · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · Using Xcode Instruments to optimize Swift Concurrency Code · Is Your iOS App Secure?

**Selected links:**
- [Using Xcode Instruments to optimize Swift Concurrency Code](https://www.youtube.com/watch?v=hDFOy-ynJ6I) — Video · Topics: Concurrency · Performance · Xcode
  **NeKI brief:** Profiles inefficient AI-generated Swift concurrency code with Instruments' Tasks, Actors, Hangs, and Time Profiler instruments, then improves it using isolation choices, task groups, @concurrent, and a clearer understanding of suspension points.
- [Modern SwiftUI APIs for programmatic scrolling](https://nilcoalescing.com/blog/ModernSwiftUIAPIsForProgrammaticScrolling) — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Uses modern SwiftUI scrolling APIs to observe visible items, target positions, and programmatic movement. Useful for replacing preference-key workarounds with typed scroll coordination.
- [Xcode should be decoupled from Swift versions](https://macguru.dev/xcode-should-be-decoupled-from-swift-versions) — Article · Topics: Apple Platform Ecosystem · Swift · Xcode
  **NeKI brief:** Argues that Xcode and Swift version coupling creates avoidable upgrade friction. Use it as a language-toolchain compatibility perspective when planning CI matrices, migration sequencing, and package version constraints.
- [Make It Visible: Accessibility Meetup @ CommunityKit](https://luma.com/ro48u8fw) — Article · Topics: Accessibility · Apple Platform Ecosystem · Developer Community & Business
  **NeKI brief:** Describes Make It Visible: Accessibility Meetup @ CommunityKit, providing the event-specific information needed to identify its Apple-platform community context.
- [Deprecating your own convenience API](https://swiftwithmajid.com/2026/05/19/deprecating-your-own-convenience-api) — Article · Topics: Swift
  **NeKI brief:** Explains deprecating a convenience API with migration messages and replacement paths. Use it when evolving an internal or public Swift interface while keeping callers compiling and making the preferred alternative discoverable.
- [A Recipe to Custom Instructions for GitHub Copilot](https://www.ioscoffeebreak.com/issue/issue72) — Article · Topics: AI Development · Developer Tools
  **NeKI brief:** Explains A Recipe to Custom Instructions for GitHub Copilot, connecting the underlying Apple-platform mechanism to implementation choices and practical trade-offs that Swift developers can evaluate.
- [Making a SwiftUI sheet automatically size to fit its content](https://danielsaidi.com/blog/2026/05/22/making-a-swiftui-sheet-automatically-size-to-fit-its-content) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI sheet that measures its content and chooses an appropriate presentation height. Useful for compact forms and detail panels that should avoid excessive empty space while handling dynamic type and updates.
- [Is Your iOS App Secure?](https://hubs.la/Q04b9pGH0) — Article · Topics: Security & Privacy
  **NeKI brief:** Discusses Is Your iOS App Secure?, providing concrete engineering context that Apple-platform developers can use when evaluating the referenced workflow.

## [Issue 324 · 2026-05-19](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-324)

- Published: `2026-05-19T14:04:54.000Z`

**Topics:** AI Development · Concurrency · Developer Community & Business · Graphics, Media & Games · Swift · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · Recording a Physical iPhone for App Preview Videos · Fastlane alternative - Codemagic CLI tools

**Selected links:**
- [AcceptedSE-0525Safe loading API for `RawSpan`](https://github.com/apple/swift-evolution/blob/main/proposals/0525-rawspan-safe-loading-api.md) — Source repository · Topics: AI Development · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0525Safe loading API for `RawSpan`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Fastlane alternative - Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository · Topics: CI/CD & Automation · Developer Tools
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [Using Xcode MCP with Claude Code](https://danielsaidi.com/blog/2026/04/30/using-xcode-mcp-with-claude-code) — Article · Topics: AI Development · Xcode
  **NeKI brief:** Describes connecting Claude Code to Xcode through Model Context Protocol. Follow it when evaluating agent-assisted build and debugging workflows, paying attention to permissions, simulator boundaries, generated changes, and human review checkpoints.
- [Teaching Skills to an AI Harness](https://alejandromp.com/development/blog/teaching-skills-to-an-ai-harness) — Article · Topics: AI Development · Swift
  **NeKI brief:** Describes structuring reusable skills for an AI coding harness rather than relying on one large prompt. Use it when designing maintainable agent instructions with explicit scope, tool boundaries, and progressive disclosure.
- [AcceptedSE-0530Async Result Support](https://github.com/apple/swift-evolution/blob/main/proposals/0530-async-result-support.md) — Source repository · Topics: AI Development · Concurrency · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0530Async Result Support. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [A Type-Safe EventBus in Swift](https://livsycode.com/best-practices/a-type-safe-eventbus-in-swift) — Article · Topics: Swift
  **NeKI brief:** Discusses A Type-Safe EventBus in Swift, extracting concrete engineering practices and trade-offs that Apple-platform developers can apply when evaluating this workflow.
- [Cupertino v1.1.0: my Apple docs index was 30% lies and I didn't know](https://aleahim.com/blog/cupertino-v1-1-0-poison-cleanup) — Article · Topics: AI Development
  **NeKI brief:** This post audits Cupertino's Apple-documentation database and shows how stale or erroneous rows can survive a green health check. It provides a concrete upgrade, database-rebuild, and verification workflow for maintaining local documentation indexes.
- [A floating card using safeAreaBar](https://codakuma.com/floating-safe-area-bar) — Article
  **NeKI brief:** Shaun shows how to build a reusable floating bottom card in SwiftUI using safeAreaBar on iOS 26, with an iOS 18 fallback that combines safeAreaInset, material, and a gradient fade to keep scrolling content readable behind it.
- [MCP](https://ifttt.com/explore/what-is-ifttt-mcp) — Article
  **NeKI brief:** Discusses MCP, extracting concrete engineering practices and trade-offs that Apple-platform developers can apply when evaluating this workflow.

## [Issue 323 · 2026-05-12](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-323)

- Published: `2026-05-12T14:05:49.000Z`

**Topics:** Accessibility · Concurrency · Developer Community & Business · Swift · SwiftUI · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · AI-Powered Xcode Simulator Automation (token-efficient) · Is Your iOS App Secure?

**Selected links:**
- [AI-Powered Xcode Simulator Automation (token-efficient)](https://www.youtube.com/watch?v=mD6vpokRpsU) — Video · Topics: AI Development · Testing · Xcode
  **NeKI brief:** Demonstrates RocketSim's command-line and agent skill controlling an iOS Simulator through a compact accessibility-tree representation. Useful for evaluating repeatable agent-driven navigation, inspection, and simulator automation against conventional screenshot-heavy workflows.
- [3 Key Strategies to Make SwiftUI Views More Reusable](https://matteomanferdini.com/swiftui-reusable-views) — Article · Topics: Product Design · Swift · SwiftUI
  **NeKI brief:** Presents three concrete strategies for making SwiftUI views reusable, from extracting components to controlling dependencies and state. Useful when reducing duplication without hiding feature-specific behavior behind overly generic abstractions.
- [A guide to macOS window toolbar styles in SwiftUI](https://nilcoalescing.com/blog/AGuideToMacOSToolbarStylesInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Compares macOS SwiftUI toolbar styles and their visual roles. Use it when a window's title area, navigation controls, and command density should align with the platform instead of inheriting an accidental default appearance.
- [Swift ARC: From Zombie Objects to Side Tables](https://livsycode.com/swift/swift-arc-from-zombie-objects-to-side-tables) — Article · Topics: Objective-C & Cocoa · Swift
  **NeKI brief:** Explains Swift ARC through zombie objects, reference counting, and side tables. Use it as a low-level diagnostic aid when investigating unexpected retention or weak-reference behavior, especially in mixed Swift and Objective-C code.
- [How to Create Dynamic Quick Actions in iOS](https://diamantidis.github.io/2026/05/10/how-to-create-dynamic-quick-actions-ios-swift) — Article · Topics: Developer Tools · Swift
  **NeKI brief:** Explains How to Create Dynamic Quick Actions in iOS, focusing on the underlying Apple-platform behavior and the implementation trade-offs relevant to production code.
- [AcceptedSE-0528`Continuation` — Safe and Performant Async Continuations](https://github.com/apple/swift-evolution/blob/main/proposals/0528-noncopyable-continuation.md) — Source repository · Topics: Concurrency · Developer Community & Business · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0528`Continuation` — Safe and Performant Async Continuations. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Swift Island - A Swift Conference, on an island](https://ti.to/swiftisland/2026/discount/ANTOINE_APPROVED) — Article · Topics: Developer Community & Business · Swift
  **NeKI brief:** Describes Swift Island - A Swift Conference, on an island, providing the event-specific information needed to identify its Apple-platform community context.
- [Is Your iOS App Secure?](https://hubs.la/Q04b9pGH0) — Article · Topics: Security & Privacy
  **NeKI brief:** Discusses Is Your iOS App Secure?, providing concrete engineering context that Apple-platform developers can use when evaluating the referenced workflow.

## [Issue 322 · 2026-05-05](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-322)

- Published: `2026-05-05T14:09:40.000Z`

**Topics:** App Distribution & Store Operations · Concurrency · Developer Community & Business · Maps & Location · Swift · SwiftUI

**Sections:** SwiftLee Weekly by Antoine van der Lee · Stop waiting. Start shipping. · Scheduling and handling background app refresh in SwiftUI

**Selected links:**
- [ImplementedSE-0524Add `withTemporaryAllocation` using `Output(Raw)Span`](https://github.com/apple/swift-evolution/blob/main/proposals/0524-span-temporary-allocation.md) — Source repository · Topics: Developer Tools · Maps & Location · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0524Add `withTemporaryAllocation` using `Output(Raw)Span`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [join the TestFlight](https://testflight.apple.com/join/gW6FgtZP) — Article · Topics: App Distribution & Store Operations · Security & Privacy · Testing
  **NeKI brief:** Links to join the TestFlight, a concrete TestFlight distribution page for evaluating the referenced iOS build anonymously.
- [RocketSim for Teams](https://www.rocketsim.app/for-teams) — Article · Topics: App Distribution & Store Operations · Security & Privacy · Testing
  **NeKI brief:** Documents RocketSim for Teams, focusing on an iOS Simulator workflow and the concrete debugging or testing decisions it enables for Apple-platform development.
- [Synchronization in Swift: Actors vs Queues vs Locks → Livsy Code](https://livsycode.com/best-practices/actors-vs-queues-vs-locks-in-swift) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Artem compares actors, queues, and locks in Swift, showing when each is useful for safely synchronizing shared state and what trade-offs they bring.
- [How to implement pagination with SwiftUI's List view](https://tanaschita.com/swiftui-list-pagination) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Implements incremental pagination in SwiftUI List as the user approaches the end of loaded content. Use it when an async data source needs explicit loading, error, and duplicate-request guards rather than eager full retrieval.
- [Swift Concurrency Agent Skill](https://github.com/AvdLee/Swift-Concurrency-Agent-Skill) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Provides focused agent guidance for Swift concurrency work. Use it to give coding agents project-relevant rules around isolation, Sendable boundaries, and async tests before they propose or edit concurrent Swift code.
- [Scheduling and handling background app refresh in SwiftUI](https://nilcoalescing.com/blog/SchedulingAndHandlingBackgroundAppRefreshInSwiftUI) — Article · Topics: App Services & Extensions · Swift · SwiftUI
  **NeKI brief:** Shows how a SwiftUI app enables, schedules, handles, and tests background refresh work using Background Tasks and backgroundTask(_:action:).
- [AcceptedSE-0517UniqueBox](https://github.com/apple/swift-evolution/blob/main/proposals/0517-uniquebox.md) — Source repository · Topics: Developer Tools · Maps & Location · Swift
  **NeKI brief:** Records AcceptedSE-0517UniqueBox, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Returned For RevisionSE-0526withDeadline](https://github.com/apple/swift-evolution/blob/main/proposals/0526-deadline.md) — Source repository · Topics: Developer Tools · Maps & Location · Swift
  **NeKI brief:** Proposal SE-0526 adds withDeadline for time-bounded asynchronous work. Read it to distinguish deadline expiry from ordinary cancellation and failure, and verify accepted semantics and toolchain availability before designing a public timeout API around it.
- [Active ReviewSE-0530Async Result Support](https://github.com/apple/swift-evolution/blob/main/proposals/0530-async-result-support.md) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0530Async Result Support. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [CLI](https://www.rocketsim.app/docs/features/agentic-development/rocketsim-cli) — Article · Topics: AI Development · Testing
  **NeKI brief:** Explains CLI, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Agent Skill](https://www.rocketsim.app/docs/features/agentic-development/agent-skill) — Article · Topics: AI Development · Testing
  **NeKI brief:** Documents Agent Skill, focusing on an iOS Simulator workflow and the concrete debugging or testing decisions it enables for Apple-platform development.
- [Understanding 'indirect' keyword in Swift - Recursive Enums Explained Clearly](https://www.sagarunagar.com/blog/indirect-keyword-swift-recursive-enums) — Article · Topics: Swift
  **NeKI brief:** Explains Understanding 'indirect' keyword in Swift - Recursive Enums Explained Clearly, focusing on the underlying Swift or Apple-platform mechanism and the implementation trade-offs relevant to production code.
- [Six Years Perfecting Maps on watchOS](https://david-smith.org/blog/2026/04/29/maps-on-watchos) — Article · Topics: Maps & Location
  **NeKI brief:** Discusses Six Years Perfecting Maps on watchOS, extracting concrete engineering practices and trade-offs that Apple-platform developers can apply when evaluating this workflow.
- [RocketSim now works with USB-connected devices](https://www.rocketsim.app/docs/features/capturing/physical-device-support) — Article
  **NeKI brief:** Documents RocketSim capture support for USB-connected physical devices. Use it to evaluate a device-recording workflow for demos or bug evidence, checking supported OS versions and the operational limits of the tool.

## [Issue 321](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-321)

- Published: `2026-04-28T14:07:22.000Z`

**Topics:** Concurrency · Developer Community & Business · Performance · Swift · SwiftUI · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · Stop waiting. Start shipping. · An Odometer-Style Number Animation in SwiftUI

**Selected links:**
- [An Odometer-Style Number Animation in SwiftUI](https://livsycode.com/swiftui/an-odometer-style-number-animation-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds an odometer-style number animation in SwiftUI using composable transitions and state changes. Use it for counters or metrics that need legible motion without manually coordinating per-digit UIKit layers.
- [Recording & Analyzing SwiftUI Instruments Traces](https://github.com/AvdLee/SwiftUI-Agent-Skill) — Source repository · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Describes A SwiftUI agent skill for better code reviews, focusing on practical tool integration and workflow trade-offs. Use it to evaluate reproducibility, trust boundaries, and debugging steps before adopting the approach in an Xcode project.
- [AcceptedSE-0511SwiftPM Add Target Plugin Command](https://github.com/apple/swift-evolution/blob/main/proposals/0511-swiftpm-add-target-plugin.md) — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0511SwiftPM Add Target Plugin Command. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [AcceptedSE-0521Improved Syntax for Optionals of Opaque and Existential Types](https://github.com/apple/swift-evolution/blob/main/proposals/0521-improved-optional-opaque-and-any.md) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Records ImplementedSE-0521Improved Syntax for Optionals of Opaque and Existential Types, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Active ReviewSE-0529Add `FilePath` to the Standard Library](https://github.com/apple/swift-evolution/blob/main/proposals/0529-filepath-in-stdlib.md) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Records AcceptedSE-0529Add `FilePath` to the Standard Library, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Making breakpoints work with single-line code blocks](https://peterringset.dev/articles/column-breakpoints) — Article · Topics: Xcode
  **NeKI brief:** Presents Making breakpoints work with single-line code blocks, with practical context for Apple-platform developers evaluating the technique, workflow, or engineering decision described on the page.
- [SwiftUI: Refreshable Task Cancellation](https://antongubarenko.substack.com/p/swiftui-refreshable-task-cancellation) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains how refreshable starts asynchronous work and how cancellation propagates when the user ends or repeats a refresh. Useful for making pull-to-refresh tasks idempotent, responsive, and safe against stale results.
- [Optional has a take() function](https://www.scottberrevoets.com/til/optional-has-a-take-function) — Article · Topics: Swift
  **NeKI brief:** Explains Optional has a take() function, showing the language behavior behind the API and how it can simplify or clarify everyday Swift code.

## [Issue 320](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-320)

- Published: `2026-04-21T14:11:27.000Z`

**Topics:** Concurrency · Developer Community & Business · Performance · Swift · SwiftUI · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · Lessons Learned from Security Incidents in Mobile Apps · Apple Developer Community Meetup during WWDC

**Selected links:**
- [Building a draggable bottom sheet in SwiftUI](https://tanaschita.com/swiftui-draggable-bottom-sheet) — Article · Topics: Maps & Location · Swift · SwiftUI
  **NeKI brief:** Builds a draggable SwiftUI bottom sheet with gesture state, detents, and snapping decisions. Useful for custom interaction when system sheets do not expose the required presentation behavior.
- [A Reusable Spotlight Onboarding Component in SwiftUI](https://livsycode.com/swiftui/a-reusable-spotlight-onboarding-component-in-swiftui) — Article · Topics: App Intents & System Surfaces · Swift · SwiftUI
  **NeKI brief:** Artem shares how to build a reusable SwiftUI spotlight onboarding component that highlights views with a rounded cutout, positions an overlay card, and supports multi-step flows using anchors and PreferenceKey.
- [FormatStyle Guide](https://chris.eidhof.nl/post/format-style-guide) — Article · Topics: Foundation & Data Formats · Swift
  **NeKI brief:** Introduces an interactive browser-based guide to Swift Foundation FormatStyle APIs, implemented with WebAssembly. Use the linked guide for quickly comparing formatting capabilities and verify availability against current Foundation documentation.
- [RocketSim's CLI is already live](https://www.rocketsim.app/docs/features/agentic-development/rocketsim-cli) — Article · Topics: AI Development · Xcode
  **NeKI brief:** Explains CLI, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Lessons Learned from Security Incidents in Mobile Apps](https://hubs.la/Q049VR2g0) — Article · Topics: Objective-C & Cocoa · Security & Privacy · Testing
  **NeKI brief:** Discusses Lessons Learned from Security Incidents in Mobile Apps, providing concrete engineering context that Apple-platform developers can use when evaluating the referenced workflow.
- [A Small SwiftUI Warning and a Long Journey to Understand It](https://alejandromp.com/development/blog/a-small-swiftui-warning-and-a-long-journey-to-understand-it) — Article · Topics: Concurrency · Swift · SwiftUI
  **NeKI brief:** Traces a seemingly minor SwiftUI warning back through view updates and concurrency interactions. Use it as a diagnostic case study for following framework diagnostics to their underlying data-flow cause instead of suppressing them.
- [AcceptedSE-0524Add `withTemporaryAllocation` using `Output(Raw)Span`](https://github.com/apple/swift-evolution/blob/main/proposals/0524-span-temporary-allocation.md) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0524Add `withTemporaryAllocation` using `Output(Raw)Span`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0528`Continuation` — Safe and Performant Async Continuations](https://github.com/apple/swift-evolution/blob/main/proposals/0528-noncopyable-continuation.md) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0528`Continuation` — Safe and Performant Async Continuations. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.

## [Issue 319](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-319)

- Published: `2026-04-14T14:07:31.000Z`

**Topics:** AI Development · Concurrency · Developer Community & Business · Swift · SwiftUI · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · Network Requests Optimization using Xcode’s Simulator & Agents · Give your AI agent eyes and hands on iOS

**Selected links:**
- [Give your AI agent eyes and hands on iOS](https://flowdeck.studio/swiftlee?code=SWIFTLEE25) — Article · Topics: AI Development · Swift · Xcode
  **NeKI brief:** Presents Give your AI agent eyes and hands on iOS, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Checking accessibility with SwiftUI Previews](https://mobilea11y.com/blog/swiftui-preview-testing) — Article · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Rob shows how SwiftUI Previews can be used as a lightweight accessibility testing tool, letting you quickly inspect UI variations before testing on a device.
- [AcceptedSE-0523Hashable conformance for `UnownedTaskExecutor`](https://github.com/apple/swift-evolution/blob/main/proposals/0523-hashable-unownedtask-executor.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Records AcceptedSE-0523Hashable conformance for `UnownedTaskExecutor`, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Active ReviewSE-0526withDeadline](https://github.com/apple/swift-evolution/blob/main/proposals/0526-deadline.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Proposal SE-0526 adds withDeadline for time-bounded asynchronous work. Read it to distinguish deadline expiry from ordinary cancellation and failure, and verify accepted semantics and toolchain availability before designing a public timeout API around it.
- [read here](https://www.rocketsim.app/blog/15-voiceover-navigator-pro-xcode-simulator-recordings) — Article · Topics: Accessibility · Combine & Reactive Programming · Xcode
  **NeKI brief:** Documents read here, focusing on an iOS Simulator workflow and the concrete debugging or testing decisions it enables for Apple-platform development.
- [Network Requests Optimization using Xcode’s Simulator & Agents](https://www.youtube.com/watch?v=Y5bd6FHA3K4) — Video · Topics: Xcode
  **NeKI brief:** Uses RocketSim's background network capture to inspect JSON, headers, timing metrics, and request behavior, then exports evidence to an AI agent for identifying overfetching and bottlenecks. Useful for measurement-driven network optimization.
- [Kids and Vibe Coding: The Joy of Building](https://www.swiftjectivec.com/kids-and-vibe-coding-ios-apps) — Article · Topics: Swift
  **NeKI brief:** Reflects on children building iOS apps with AI-assisted or vibe-coding tools. Use it as a product and education perspective on lowering entry barriers while retaining testing, safety, authorship, and review practices.
- [Lazy Properties in Swift - Why They Don’t Always Work in SwiftUI](https://www.sagarunagar.com/blog/lazy-properties-swiftui-pitfalls) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains Lazy Properties in Swift - Why They Don’t Always Work in SwiftUI, focusing on the underlying Swift or Apple-platform mechanism and the implementation trade-offs relevant to production code.
- [Console logs showing up in the Network Monitor](https://www.rocketsim.app/docs/features/networking/network-traffic-monitoring) — Article · Topics: Networking
  **NeKI brief:** Documents Console logs showing up in the Network Monitor, focusing on an iOS Simulator workflow and the concrete debugging or testing decisions it enables for Apple-platform development.
- [Launching deeplinks with dynamic arguments](https://www.rocketsim.app/docs/features/app-actions/deeplinks-universal-links) — Article · Topics: Navigation & Deep Linking
  **NeKI brief:** Documents Launching deeplinks with dynamic arguments, focusing on an iOS Simulator workflow and the concrete debugging or testing decisions it enables for Apple-platform development.
- [Working with files and directories in iOS](https://tanaschita.com/ios-file-system-overview) — Article
  **NeKI brief:** Maps iOS file-system locations and the responsibilities of app documents, caches, and temporary storage. Use it when choosing a persistence location whose backup, eviction, and user-visibility behavior matches the data.
- [Pinch support for recordings](https://www.rocketsim.app/docs/features/capturing/post-editor) — Article
  **NeKI brief:** Documents Pinch support for recordings, focusing on an iOS Simulator workflow and the concrete debugging or testing decisions it enables for Apple-platform development.
- [Quick minimize of the side window](https://www.rocketsim.app/docs/settings/side-window) — Article
  **NeKI brief:** Documents Quick minimize of the side window, focusing on an iOS Simulator workflow and the concrete debugging or testing decisions it enables for Apple-platform development.

## [Issue 318](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-318)

- Published: `2026-04-07T14:09:08.000Z`

**Topics:** Accessibility · Architecture · Developer Community & Business · Objective-C & Cocoa · Swift · SwiftUI

**Sections:** SwiftLee Weekly by Antoine van der Lee · Stop waiting. Start shipping. · iOSKonf Ticket Giveaway

**Selected links:**
- [Active ReviewSE-0525Safe loading API for `RawSpan`](https://github.com/apple/swift-evolution/blob/main/proposals/0525-rawspan-safe-loading-api.md) — Source repository · Topics: Architecture · Composable Architecture · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0525Safe loading API for `RawSpan`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Building List replacement in SwiftUI](https://swiftwithmajid.com/2026/04/06/building-list-replacement-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a custom SwiftUI list replacement by composing scrolling, layout, and row behavior directly. Use it when List's styling or interaction constraints are the real limitation, while measuring the performance cost of custom virtualization.
- [SwiftUI Custom Popover](https://livsycode.com/swiftui/swiftui-custom-popover) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Artem explains how to build a reusable custom popover in SwiftUI using matchedGeometryEffect, allowing you to attach an overlay to any view without dealing with frames or coordinate spaces
- [No, SwiftUI is not “Accessible by default”](https://mobilea11y.com/blog/swiftui-not-accessible) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Rob challenges the idea that SwiftUI automatically produces accessible apps, showing that developers still need to actively define accessibility to avoid common pitfalls.
- [Beta Preview: ComposableArchitecture 2.0](https://www.pointfree.co/blog/posts/206-beta-preview-composablearchitecture-2-0) — Article · Topics: Architecture · Composable Architecture · Objective-C & Cocoa
  **NeKI brief:** Previews Composable Architecture 2.0 changes and their implications for state, effects, and dependency management. Use it to assess an upcoming migration path before adopting beta conventions in a production feature.
- [RejectedSE-0246Generic Math(s) Functions](https://github.com/apple/swift-evolution/blob/main/proposals/0246-mathable.md) — Source repository · Topics: Architecture · Composable Architecture · Swift
  **NeKI brief:** Records RejectedSE-0246Generic Math(s) Functions, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Returned For RevisionSE-0516Borrowing Sequence](https://github.com/apple/swift-evolution/blob/main/proposals/0516-borrowing-sequence.md) — Source repository · Topics: Architecture · Composable Architecture · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0516`Iterable`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0524Add `withTemporaryAllocation` using `Output(Raw)Span`](https://github.com/apple/swift-evolution/blob/main/proposals/0524-span-temporary-allocation.md) — Source repository · Topics: Architecture · Composable Architecture · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0524Add `withTemporaryAllocation` using `Output(Raw)Span`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Awaiting ReviewSE-0526withDeadline](https://github.com/apple/swift-evolution/blob/main/proposals/0526-deadline.md) — Source repository · Topics: Architecture · Composable Architecture · Swift
  **NeKI brief:** Proposal SE-0526 adds withDeadline for time-bounded asynchronous work. Read it to distinguish deadline expiry from ordinary cancellation and failure, and verify accepted semantics and toolchain availability before designing a public timeout API around it.
- [Embedding SF Symbols in SwiftUI Text](https://nilcoalescing.com/blog/EmbeddingSFSymbolsInSwiftUIText) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows embedding SF Symbols inline with SwiftUI Text so symbol and typography layout together. Use it when labels need dynamic-type-aware iconography without separate HStack alignment and baseline adjustments.

## [Issue 317](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-317)

- Published: `2026-03-31T14:07:14.000Z`

**Topics:** Apple Platform Ecosystem · Concurrency · Developer Community & Business · Swift · Testing · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · Stop waiting. Start shipping. · WWDC 2026 Pins – Because We All Collect Them Anyway

**Selected links:**
- [Returned For RevisionSE-0479Method and Initializer Key Paths](https://github.com/apple/swift-evolution/blob/main/proposals/0479-method-and-initializer-keypaths.md) — Source repository · Topics: Developer Tools · Swift · Xcode
  **NeKI brief:** Records Returned For RevisionSE-0479Method and Initializer Key Paths, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Returned For RevisionSE-0490Environment Constrained Shared Libraries](https://github.com/apple/swift-evolution/blob/main/proposals/0490-environment-constrained-shared-libraries.md) — Source repository · Topics: Developer Tools · Swift · Xcode
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Returned For RevisionSE-0490Environment Constrained Shared Libraries. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ImplementedSE-0502Exclude private initialized properties from memberwise initializer](https://github.com/apple/swift-evolution/blob/main/proposals/0502-exclude-private-from-memberwise-init.md) — Source repository · Topics: Developer Tools · Swift · Xcode
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0502Exclude private initialized properties from memberwise initializer. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ImplementedSE-0507Borrow and Mutate Accessors](https://github.com/apple/swift-evolution/blob/main/proposals/0507-borrow-accessors.md) — Source repository · Topics: Developer Tools · Swift · Xcode
  **NeKI brief:** Records ImplementedSE-0507Borrow and Mutate Accessors, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Active ReviewSE-0523Hashable conformance for `UnownedTaskExecutor`](https://github.com/apple/swift-evolution/blob/main/proposals/0523-hashable-unownedtask-executor.md) — Source repository · Topics: Developer Tools · Swift · Xcode
  **NeKI brief:** Records AcceptedSE-0523Hashable conformance for `UnownedTaskExecutor`, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Swift 6.3 Released](https://www.swift.org/blog/swift-6.3-released) — Article · Topics: Swift · Testing
  **NeKI brief:** Announces Swift 6.3 and summarizes the language, package, and tooling changes in that release. Use it to identify migration candidates, then consult the release notes and proposal links for exact compiler behavior and availability.
- [Package Traits in Xcode](https://www.massicotte.org/blog/package-traits-in-xcode) — Article · Topics: AI Development · Xcode
  **NeKI brief:** Introduces Swift package traits in Xcode and shows how conditional package features can avoid maintaining multiple package variants.
- [Xcode 26.4 Simulator Paste Is Broken: Here’s the Workaround](https://samwize.com/2026/03/30/xcode-simulator-paste-broken-workaround) — Article · Topics: Developer Tools · Xcode
  **NeKI brief:** Examines @samwize in the context of AI Development and Cross-Platform & Web. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [88: SwiftLee – Antoine van der Lee](https://launchedfm.com/episode/88-swiftlee-antoine-van-der-lee) — Podcast · Topics: Developer Community & Business · Swift
  **NeKI brief:** Discusses 88: SwiftLee – Antoine van der Lee, extracting concrete engineering practices and trade-offs that Apple-platform developers can apply when evaluating this workflow.

## [Issue 316](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-316)

- Published: `2026-03-24T15:03:10.000Z`

**Topics:** AI Development · Apple Platform Ecosystem · Concurrency · Developer Community & Business · Swift · SwiftUI

**Sections:** SwiftLee Weekly by Antoine van der Lee · iOS auth eating your time? · WWDC26 Apple Park Special Event

**Selected links:**
- [Expanding Animations in SwiftUI Lists](https://nerdyak.tech/development/2026/03/16/expand-animation-in-SwiftUI-List.html) — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **NeKI brief:** Diagnoses janky expand and collapse animations inside SwiftUI List and documents the identity and transaction choices that improve them. Useful when animating variable-height rows without breaking list diffing or scroll performance.
- [ImplementedSE-0493Support `async` calls in `defer` bodies](https://github.com/apple/swift-evolution/blob/main/proposals/0493-defer-async.md) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0493Support `async` calls in `defer` bodies. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ImplementedSE-0491Module selectors for name disambiguation](https://github.com/apple/swift-evolution/blob/main/proposals/0491-module-selectors.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0491Module selectors for name disambiguation. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ImplementedSE-0499Support ~Copyable, ~Escapable in simple standard library protocols](https://github.com/apple/swift-evolution/blob/main/proposals/0499-support-non-copyable-simple-protocols.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0499Support ~Copyable, ~Escapable in simple standard library protocols. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0522Source-Level Control Over Compiler Warnings](https://github.com/apple/swift-evolution/blob/main/proposals/0522-source-warning-control.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Records ImplementedSE-0522Source-Level Control Over Compiler Warnings, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [iOS auth eating your time?](https://go.clerk.com/sxkDCu7) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Presents iOS auth eating your time?, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Join the TestFlight](https://testflight.apple.com/join/emGszFpq) — Article · Topics: App Distribution & Store Operations · Developer Community & Business · Testing
  **NeKI brief:** Links to Join the TestFlight, a concrete TestFlight distribution page for evaluating the referenced iOS build anonymously.
- [Apple’s Hidden Collection and Sequence APIs You Should Be Using](https://www.sagarunagar.com/blog/swift-algorithms-complete-guide) — Article · Topics: Swift
  **NeKI brief:** Explains Apple’s Hidden Collection and Sequence APIs You Should Be Using, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Review your own AI-generated code](https://www.scottberrevoets.com/2026/03/20/review-your-own-ai-generated-code) — Article · Topics: AI Development
  **NeKI brief:** Discusses Review your own AI-generated code, extracting concrete engineering practices and trade-offs that Apple-platform developers can apply when evaluating this workflow.
- [Copy-On-Write in Swift: Semantics, Misconceptions, and a Custom Implementation](https://livsycode.com/swift/copy-on-write-in-swift-semantics-misconceptions-and-a-custom-implementation) — Article · Topics: Swift
  **NeKI brief:** Explains Swift copy-on-write semantics and a custom implementation. Useful for reasoning about value performance, uniqueness checks, and the difference between apparent copies and actual storage duplication.
- [Generally Useful Prompts](https://david-smith.org/blog/2026/03/20/generally-useful-prompts) — Article · Topics: AI Development
  **NeKI brief:** Discusses Generally Useful Prompts, extracting concrete engineering practices and trade-offs that Apple-platform developers can apply when evaluating this workflow.

## [Issue 315](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-315)

- Published: `2026-03-17T15:01:49.000Z`

**Topics:** Concurrency · Developer Community & Business · Graphics, Media & Games · Swift · SwiftUI · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · How iOS apps actually make money · iOS Dev Directory

**Selected links:**
- [ImplementedSE-0489Improve `EncodingError` and `DecodingError`'s printed descriptions](https://github.com/apple/swift-evolution/blob/main/proposals/0489-codable-error-printing.md) — Source repository · Topics: Developer Tools · Foundation & Data Formats · Swift
  **NeKI brief:** Records ImplementedSE-0489Improve `EncodingError` and `DecodingError`'s printed descriptions, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [ImplementedSE-0481`weak let`](https://github.com/apple/swift-evolution/blob/main/proposals/0481-weak-let.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0481`weak let`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ImplementedSE-0492Section Placement Control](https://github.com/apple/swift-evolution/blob/main/proposals/0492-section-control.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Records ImplementedSE-0492Section Placement Control, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [ImplementedSE-0496`@inline(always)` attribute](https://github.com/apple/swift-evolution/blob/main/proposals/0496-inline-always.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Records ImplementedSE-0496`@inline(always)` attribute, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Avoid Spacers in SwiftUI Stacks](https://nerdyak.tech/development/2023/04/06/avoid-swiftui-spacers-in-stacks.html) — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **NeKI brief:** Explains Avoid Spacers in SwiftUI Stacks, connecting the underlying Apple-platform mechanism to implementation choices and practical trade-offs that Swift developers can evaluate.
- [SwiftUI transitions with distortion effect and Metal Shaders](https://nerdyak.tech/development/2023/06/16/distortionEffect-with-Metal-shaders-for-better-transitions.html) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Explains SwiftUI transitions with distortion effect and Metal Shaders, connecting the underlying Apple-platform mechanism to implementation choices and practical trade-offs that Swift developers can evaluate.
- [AcceptedSE-0501HTML Coverage Report](https://github.com/apple/swift-evolution/blob/main/proposals/0501-swiftpm-html-coverage-report.md) — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0501HTML Coverage Report. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [SwiftUI Agent Skill](https://github.com/AvdLee/SwiftUI-Agent-Skill/releases/tag/2.3.0) — Source repository · Topics: Developer Community & Business · Swift · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for SwiftUI Agent Skill. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Swift Concurrency Agent Skill](https://github.com/AvdLee/Swift-Concurrency-Agent-Skill/releases/tag/2.0.0) — Source repository · Topics: Concurrency · Developer Community & Business · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Swift Concurrency Agent Skill. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Xcode 26 Compilation Cache](https://livsycode.com/best-practices/xcode-26-compilation-cache) — Article · Topics: Xcode
  **NeKI brief:** Artem takes a look at the new Compilation Cache in Xcode 26, how it works, when it makes a real difference, and what to keep in mind before expecting it to solve all your build time problems.
- [iOS Dev Directory](https://iosdevdirectory.com/contributing) — Article · Topics: Developer Community & Business · Swift
  **NeKI brief:** Explores add their site for them, focusing on so, whether you’ve fully migrated to mastodon or now split. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Learning to develop more accessible iOS games](https://accessibilityupto11.com/post/2026-02-22-01) — Article · Topics: Accessibility · Graphics, Media & Games
  **NeKI brief:** Daniel shares lessons from making his new game, RetroRapid!, more accessible, focusing on multiple control options, alternative feedback, and customizable settings to make gameplay inclusive.
- [AcceptedSE-0507Borrow and Mutate Accessors](https://github.com/apple/swift-evolution/blob/main/proposals/0507-borrow-accessors.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Records ImplementedSE-0507Borrow and Mutate Accessors, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [AcceptedSE-0515Allow `reduce` to produce noncopyable results](https://github.com/apple/swift-evolution/blob/main/proposals/0515-noncopyable-reduce.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0515Allow `reduce` to produce noncopyable results. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [How iOS apps actually make money](https://www.revenuecat.com/state-of-subscription-apps) — Article · Topics: App Distribution & Store Operations
  **NeKI brief:** Explains How iOS apps actually make money, connecting the underlying Apple-platform mechanism to implementation choices and practical trade-offs that Swift developers can evaluate.

## [Issue 314](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-314)

- Published: `2026-03-10T15:03:18.000Z`

**Topics:** Accessibility · CI/CD & Automation · Concurrency · Developer Community & Business · Swift · SwiftUI

**Sections:** SwiftLee Weekly by Antoine van der Lee · A 9-Step Framework for Choosing the Right Agent Skill · Fastlane alternative - Codemagic CLI tools

**Selected links:**
- [Fastlane alternative - Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository · Topics: CI/CD & Automation · Developer Tools
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [Swift at scale: building the TelemetryDeck analytics service](https://www.swift.org/blog/building-privacy-first-analytics-with-swift) — Article · Topics: Security & Privacy · Swift
  **NeKI brief:** Describes building a privacy-first analytics service in Swift and the engineering choices behind it. Follow it when evaluating telemetry architecture, data minimization, and server-side Swift trade-offs without treating the service design as an app recipe.
- [dadederk/iOS-Accessibility-Agent-Skill](https://github.com/dadederk/iOS-Accessibility-Agent-Skill) — Source repository · Topics: Accessibility · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for dadederk/iOS-Accessibility-Agent-Skill. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [one from Roberto Gómez](https://github.com/rgmez/apple-accessibility-skills) — Source repository · Topics: Accessibility · Developer Tools · Swift
  **NeKI brief:** Points to one from Roberto Gómez, an open-source implementation or issue with concrete code and discussion that can inform Apple-platform development decisions.
- [Pasquale Vittoriosi](https://github.com/PasqualeVittoriosi/swift-accessibility-skill) — Source repository · Topics: Accessibility · Developer Tools · Swift
  **NeKI brief:** Points to Pasquale Vittoriosi, an open-source implementation or issue with concrete code and discussion that can inform Apple-platform development decisions.
- [twostraws/SwiftUI-Agent-Skill](https://github.com/twostraws/SwiftUI-Agent-Skill) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Provides a reusable SwiftUI-focused agent skill with guidance for generating and reviewing views. Useful as a concrete prompt and workflow artifact when evaluating AI-assisted UI composition, accessibility, and maintainability in a project.
- [Why Does Passing NSManagedObjectContext Across Isolation Domains No Longer Error in Swift 6.2?](https://fatbobman.com/en/posts/sendable-nsmanagedobjectcontext) — Article · Topics: Concurrency · Core Data · Swift
  **NeKI brief:** Explains why NSManagedObjectContext crossing isolation domains no longer errors in Swift 6.2. Use it to review Core Data concurrency assumptions and verify the behavior against the active compiler and SDK.
- [Active ReviewSE-0518`~Sendable` for explicitly marking non-`Sendable` types](https://github.com/apple/swift-evolution/blob/main/proposals/0518-tilde-sendable.md) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0518`~Sendable` for explicitly marking non-`Sendable` types. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0519`Borrow` and `Inout` types for safe, first-class references](https://github.com/apple/swift-evolution/blob/main/proposals/0519-borrow-inout-types.md) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Records Active ReviewSE-0519`Borrow` and `Inout` types for safe, first-class references, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Adjusting line height in SwiftUI on iOS 26](https://nilcoalescing.com/blog/AdjustingLineHeightInSwiftUIOniOS26) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows the iOS 26 SwiftUI line-height controls for tuning text leading while preserving Dynamic Type behavior. Useful when typography needs precise rhythm without hard-coded UIKit paragraph styles.

## [Issue 313](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-313)

- Published: `2026-03-03T15:11:29.000Z`

**Topics:** AI Development · App Distribution & Store Operations · Developer Community & Business · Swift · SwiftUI · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · Fix iOS issues faster with this workshop from Sentry · Array expression trailing closures in Swift

**Selected links:**
- [Release 2.0.0 · AvdLee/SwiftUI-Agent-Skill](https://github.com/AvdLee/SwiftUI-Agent-Skill/releases/tag/2.0.0) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Release 2.0.0 · AvdLee/SwiftUI-Agent-Skill. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [AcceptedSE-0509Software Bill of Materials (SBOM) Generation for Swift Package Manager](https://github.com/apple/swift-evolution/blob/main/proposals/0509-swift-sboms-via-swiftpm.md) — Source repository · Topics: App Distribution & Store Operations · Swift · Swift Package Manager
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0509Software Bill of Materials (SBOM) Generation for Swift Package Manager. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0515Allow `reduce` to produce noncopyable results](https://github.com/apple/swift-evolution/blob/main/proposals/0515-noncopyable-reduce.md) — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0515Allow `reduce` to produce noncopyable results. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0516Borrowing Sequence](https://github.com/apple/swift-evolution/blob/main/proposals/0516-borrowing-sequence.md) — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0516`Iterable`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Custom Parameters and Animation with Metal Shaders](https://www.createwithswift.com/custom-parameters-and-animation-with-metal-shaders) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Demonstrates passing custom parameters into Metal shaders and animating them from SwiftUI. Use it when an effect needs GPU-driven rendering with time-varying values, while keeping shader inputs and update frequency explicit.
- [Array expression trailing closures in Swift](https://livsycode.com/swift/array-expression-trailing-closures-in-swift) — Article · Topics: Swift
  **NeKI brief:** Discusses Array expression trailing closures in Swift, extracting concrete engineering practices and trade-offs that Apple-platform developers can apply when evaluating this workflow.
- [edwardsanchez/MotionEyes](https://github.com/edwardsanchez/MotionEyes) — Source repository · Topics: AI Development · Developer Tools
  **NeKI brief:** This source repository covers instrumenting and inspecting SwiftUI animation behavior. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.

## [Issue 312](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-312)

- Published: `2026-02-24T15:08:55.000Z`

**Topics:** Accessibility · Developer Community & Business · Swift · SwiftUI · Testing · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · VoiceOver Navigator & 120 FPS Recordings for Xcode’s Simulator · Release white-label apps with a single click

**Selected links:**
- [Why Your @Observable Class init() Runs Multiple Times in SwiftUI](https://livsycode.com/swiftui/why-your-observable-class-init-runs-multiple-times-in-swiftui) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Artem explains why a SwiftUI @Observable class’s initializer can run multiple times, how SwiftUI recreates view structs and re-evaluates default @State values, and how to avoid unintended repeated work.
- [ImplementedSE-0508Array expression trailing closures](https://github.com/apple/swift-evolution/blob/main/proposals/0508-array-expression-trailing-closures.md) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0508Array expression trailing closures. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0513API to get the path to the current executable](https://github.com/apple/swift-evolution/blob/main/proposals/0513-commandline-executablepath.md) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0513API to get the path to the current executable. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Paul Hudson's SwiftAgents AGENTS.md](https://github.com/twostraws/SwiftAgents) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Paul Hudson's SwiftAgents AGENTS.md. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0512Document that `Mutex.withLockIfAvailable(_:)` cannot spuriously fail](https://github.com/apple/swift-evolution/blob/main/proposals/0512-withlockifavailable-cannot-spuriously-fail.md) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Records Active ReviewSE-0512Document that `Mutex.withLockIfAvailable(_:)` cannot spuriously fail, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Active ReviewSE-0514`Hashable` Conformance for `Dictionary.Keys`, `CollectionOfOne` and `EmptyCollection`](https://github.com/apple/swift-evolution/blob/main/proposals/0514-hashable-conformance-for-dictionarykeys-collectionofone-emptycollection.md) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Records Active ReviewSE-0514`Hashable` Conformance for `Dictionary.Keys`, `CollectionOfOne` and `EmptyCollection`, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [SwiftUI Agent Skill](https://github.com/AvdLee/SwiftUI-Agent-Skill) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Describes A SwiftUI agent skill for better code reviews, focusing on practical tool integration and workflow trade-offs. Use it to evaluate reproducibility, trust boundaries, and debugging steps before adopting the approach in an Xcode project.
- [the article it's based on](https://www.hackingwithswift.com/articles/281/what-to-fix-in-ai-generated-swift-code) — Article · Topics: AI Development · Developer Community & Business · Swift
  **NeKI brief:** Lists recurring defects in AI-written Swift and suggests concrete replacements, including unsafe assumptions around state, concurrency, and framework behavior. Follow it as a review checklist before accepting generated code into an app.
- [Tracking token usage in Foundation Models](https://artemnovichkov.com/blog/tracking-token-usage-in-foundation-models) — Article · Topics: AI Development · Foundation & Data Formats
  **NeKI brief:** Artem explains how to measure the tokens Foundation Models consume for instructions, prompts, tools, and full session transcripts, helping you understand context limits and optimize prompt design.
- [The 4-Step Process I Use to Create SwiftUI Animations](https://www.swiftdifferently.com/blog/swiftui/swiftui-animation-with-example) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains The 4-Step Process I Use to Create SwiftUI Animations, focusing on the underlying Swift or Apple-platform mechanism and the implementation trade-offs relevant to production code.
- [Testing with Event Streams](https://www.massicotte.org/blog/testing-event-stream) — Article · Topics: Swift · Testing
  **NeKI brief:** Explains Testing with Event Streams, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Isolate SwiftUI animations to specific attributes](https://nilcoalescing.com/blog/IsolateSwiftUIAnimationsToSpecificAttributes) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows how to scope SwiftUI animation to selected attributes rather than every state change in a view update. Use it when unrelated layout or content changes animate accidentally and make interaction feel unstable.
- [Release white-label apps with a single click](https://www.runway.team/use-case/white-label) — Article · Topics: App Distribution & Store Operations
  **NeKI brief:** Discusses Release white-label apps with a single click, providing concrete engineering context that Apple-platform developers can use when evaluating the referenced workflow.

## [Issue 311](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-311)

- Published: `2026-02-17T15:07:33.000Z`

**Topics:** AI Development · Concurrency · Developer Community & Business · Swift · Testing · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · Fastlane alternative - Codemagic CLI tools · If You Are Not Versioning Your Swiftdata Schema

**Selected links:**
- [AcceptedSE-0504Task Cancellation Shields](https://github.com/apple/swift-evolution/blob/main/proposals/0504-task-cancellation-shields.md) — Source repository · Topics: AI Development · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0504Task Cancellation Shields. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Returned For RevisionSE-0505Delayed Enqueuing for Executors](https://github.com/apple/swift-evolution/blob/main/proposals/0505-delayed-enqueuing.md) — Source repository · Topics: AI Development · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Returned For RevisionSE-0505Delayed Enqueuing for Executors. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [AcceptedSE-0506Advanced Observation Tracking](https://github.com/apple/swift-evolution/blob/main/proposals/0506-advanced-observation-tracking.md) — Source repository · Topics: AI Development · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0506Advanced Observation Tracking. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [AcceptedSE-0508Array expression trailing closures](https://github.com/apple/swift-evolution/blob/main/proposals/0508-array-expression-trailing-closures.md) — Source repository · Topics: AI Development · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0508Array expression trailing closures. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Fastlane alternative - Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository · Topics: CI/CD & Automation · Developer Tools
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [Agentic Coding in Xcode with Gemini CLI](https://peterfriese.dev/blog/2026/agentic-coding-xcode-geminicli) — Article · Topics: AI Development · Xcode
  **NeKI brief:** Connects Gemini CLI to Xcode 26.3 through Apple's MCP bridge and walks through an emoji physics example. The setup highlights version and response-format requirements that matter when using agents other than Xcode's built-in integrations.
- [If You Are Not Versioning Your Swiftdata Schema](https://azamsharp.com/2026/02/14/if-you-are-not-versioning-your-swiftdata-schema.html) — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** Azam explains why schema versioning in SwiftData is essential once your app stores real user data and shows how to define VersionedSchema, implement custom migrations, and evolve models.
- [now part of OpenAI, congrats Peter!](https://steipete.me/posts/2026/openclaw) — Article · Topics: AI Development
  **NeKI brief:** Presents now part of OpenAI, congrats Peter!, with practical context for Apple-platform developers evaluating the technique, workflow, or engineering decision described on the page.
- [Advanced NavigationStack Patterns in SwiftUI](https://buczel.com/blog/swift-navigation-stack-patterns) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents advanced NavigationStack patterns for typed routes, destinations, and path state. Useful for structuring nested flows and deep links when direct NavigationLink composition no longer provides sufficient control or testability.

## [Issue 310](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-310)

- Published: `2026-02-10T15:14:11.000Z`

**Topics:** AI Development · Combine & Reactive Programming · Concurrency · Developer Community & Business · Swift · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · Core Data Agent Skill: Now available open-source · Keep your mobile app size under control with Sentry’s Size Analysis

**Selected links:**
- [An Xcode Agent Prompt: What It Signals for Combine and RxSwift](https://livsycode.com/blog/an-xcode-agent-prompt-what-it-signals-for-combine-and-rxswift) — Article · Topics: Combine & Reactive Programming · Swift · Xcode
  **NeKI brief:** Presents An Xcode Agent Prompt: What It Signals for Combine and RxSwift, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [AcceptedSE-0502Exclude private initialized properties from memberwise initializer](https://github.com/apple/swift-evolution/blob/main/proposals/0502-exclude-private-from-memberwise-init.md) — Source repository · Topics: Combine & Reactive Programming · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0502Exclude private initialized properties from memberwise initializer. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0510Introduce `Dictionary.mapValuesWithKeys`](https://github.com/apple/swift-evolution/blob/main/proposals/0510-dictionary-mapvalues-with-keys.md) — Source repository · Topics: Combine & Reactive Programming · Developer Tools · Swift
  **NeKI brief:** Records Active ReviewSE-0510Introduce `Dictionary.mapValuesWithKeys`, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Active ReviewSE-0511SwiftPM Add Target Plugin Command](https://github.com/apple/swift-evolution/blob/main/proposals/0511-swiftpm-add-target-plugin.md) — Source repository · Topics: Combine & Reactive Programming · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0511SwiftPM Add Target Plugin Command. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Exploring AI Driven Coding: Using Xcode 26.3 MCP Tools in Cursor, Claude Code and Codex](https://rudrank.com/exploring-xcode-using-mcp-tools-cursor-external-clients) — Article · Topics: AI Development · Xcode
  **NeKI brief:** Describes Exploring AI Driven Coding: Using Xcode 26.3 MCP Tools in Cursor, Claude Code and Codex, focusing on practical tool integration and workflow trade-offs. Use it to evaluate reproducibility, trust boundaries, and debugging steps before adopting the approach in an Xcode project.
- [How Your Views Actually Move](https://www.swiftdifferently.com/blog/swiftui/swiftui-animations-deep-dive) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Omar dives deep on how animations actually work in SwiftUI from implicit and explicit animations to animation placement, the Animatable protocol for custom motion, transitions, transactions, and performance tips.
- [From Pixel Capture to Metadata - Reimagining Screen Recording Architecture on macOS](https://fatbobman.com/en/posts/screensage-from-pixel-to-meta) — Article · Topics: Architecture · Objective-C & Cocoa
  **NeKI brief:** Uses a macOS recorder to connect ScreenCaptureKit and Metal capture, bitrate control, crash recovery, multi-window behavior, and SwiftUI timeline performance. The engineering log helps separate recording architecture from product-facing metadata workflows.
- [Accessibility Inspector](https://github.com/AvdLee/RocketSimApp/issues/521) — Source repository · Topics: Accessibility · Developer Tools
  **NeKI brief:** Points to Accessibility Inspector, an open-source implementation or issue with concrete code and discussion that can inform Apple-platform development decisions.

## [Issue 309](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-309)

- Published: `2026-02-03T15:08:20.000Z`

**Topics:** Combine & Reactive Programming · Concurrency · Developer Community & Business · Graphics, Media & Games · Swift · SwiftUI

**Sections:** SwiftLee Weekly by Antoine van der Lee · Release every white-label app in one click · The creator of Clawd: "I ship code I don't read"

**Selected links:**
- [Reverse masking in SwiftUI using blend modes](https://livsycode.com/swiftui/reverse-masking-in-swiftui-using-blend-modes) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates reverse masking in SwiftUI with blend modes. Follow it for cutout or spotlight effects, separating compositing behavior from layout and checking rendering cost, color-space assumptions, and accessibility alternatives.
- [SwiftUI agent skill](https://github.com/AvdLee/SwiftUI-Agent-Skill/pull/11) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for SwiftUI agent skill. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0508Array expression trailing closures](https://github.com/apple/swift-evolution/blob/main/proposals/0508-array-expression-trailing-closures.md) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0508Array expression trailing closures. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0509Software Bill of Materials (SBOM) Generation for Swift Package Manager](https://github.com/apple/swift-evolution/blob/main/proposals/0509-swift-sboms.md) — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0509Software Bill of Materials (SBOM) Generation for Swift Package Manager. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Swift Bits: Transition vs Transaction](https://antongubarenko.substack.com/p/swift-bits-transition-vs-transaction) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Contrasts SwiftUI transitions, which define insertion and removal effects, with transactions, which carry animation and state-change context. Follow it when an animation behaves unexpectedly because presentation effects and animation configuration were mixed.
- [How Apple Hooks Entire Frameworks](https://bryce.co/swizzle-everything) — Article · Topics: Graphics, Media & Games
  **NeKI brief:** This investigation reverse-engineers framework-wide method swizzling and the trade-offs that appear when scaling from thousands to millions of methods. It connects Main Thread Checker-style instrumentation to binary-size limits and a practical library implementation.
- [Designing Swift Errors for an SDK](https://nonstrict.eu/blog/2026/designing-swift-errors-for-an-sdk) — Article · Topics: Swift
  **NeKI brief:** This article covers designing stable, expressive error APIs for Swift SDKs. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Release every white-label app in one click](https://www.runway.team/use-case/white-label) — Article
  **NeKI brief:** Discusses Release white-label apps with a single click, providing concrete engineering context that Apple-platform developers can use when evaluating the referenced workflow.

## [Issue 308](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-308)

- Published: `2026-01-27T15:08:00.000Z`

**Topics:** Concurrency · Developer Career & Practice · Developer Community & Business · Observation & State Management · Swift · SwiftUI

**Sections:** SwiftLee Weekly by Antoine van der Lee · AI App Development: What I Learned in One Month · Transform Your Career with the iOS Lead Essentials — Limited Offer

**Selected links:**
- [The unexpected @Binding side effect](https://swiftunwrap.com/article/binding-side-effect) — Article · Topics: Developer Tools · Observation & State Management · Swift
  **NeKI brief:** Presents The unexpected @Binding side effect, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [AvdLee/SwiftUI-Agent-Skill](https://github.com/AvdLee/SwiftUI-Agent-Skill) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Describes A SwiftUI agent skill for better code reviews, focusing on practical tool integration and workflow trade-offs. Use it to evaluate reproducibility, trust boundaries, and debugging steps before adopting the approach in an Xcode project.
- [How to Avoid Double Updates When Filtering SwiftUI TextField Input](https://livsycode.com/swiftui/how-to-avoid-double-updates-when-filtering-swiftui-textfield-input) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains How to Avoid Double Updates When Filtering SwiftUI TextField Input, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [my first Agent Skill on Swift Concurrency](https://github.com/AvdLee/Swift-Concurrency-Agent-Skill) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Provides focused agent guidance for Swift concurrency work. Use it to give coding agents project-relevant rules around isolation, Sendable boundaries, and async tests before they propose or edit concurrent Swift code.
- [How I Stopped Resisting AI and Started Teaching It](https://www.swiftdifferently.com/blog/swiftui/How%20I%20stopped-resisting-ai-and-atarted-teaching-it) — Article · Topics: AI Development · Swift · SwiftUI
  **NeKI brief:** With agentic workflows now integrated into Xcode and intelligence features evolving rapidly, the conversation shifts from what AI can do with to how developers shape, use and guide it. This echoes the theme in "How I Stopped Resisting AI and Started Teaching…
- [UnknownSE-0507Borrow and Mutate Accessors](https://github.com/apple/swift-evolution/blob/main/proposals/0507-borrow-accessors.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Records ImplementedSE-0507Borrow and Mutate Accessors, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.

## [Issue 307](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-307)

- Published: `2026-01-20T15:10:47.000Z`

**Topics:** AI Development · CI/CD & Automation · Concurrency · Developer Community & Business · Foundation & Data Formats · Swift

**Sections:** SwiftLee Weekly by Antoine van der Lee · Fastlane alternative - Codemagic CLI tools · The Magic Behind UUID() in Swift, How Your App Generates Truly Unique…

**Selected links:**
- [Fastlane alternative - Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository · Topics: CI/CD & Automation · Developer Tools
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [Foundation Models Prompting Guide](https://livsycode.com/best-practices/foundation-models-prompting-guide) — Article · Topics: AI Development · Foundation & Data Formats
  **NeKI brief:** Provides practical prompting guidance for Apple's Foundation Models. Use it when shaping instructions, output constraints, and context boundaries for on-device generation, then validate behavior across models, locales, and failure cases.
- [AcceptedSE-0500Improving package creation with custom templates: SwiftPM Template Initialization](https://github.com/apple/swift-evolution/blob/main/proposals/0500-package-manager-templates.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Records AcceptedSE-0500Improving package creation with custom templates: SwiftPM Template Initialization, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Active ReviewSE-0505Delayed Enqueuing for Executors](https://github.com/apple/swift-evolution/blob/main/proposals/0505-delayed-enqueuing.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Returned For RevisionSE-0505Delayed Enqueuing for Executors. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [The Magic Behind UUID() in Swift, How Your App Generates Truly Unique Identifiers](https://www.swiftdifferently.com/blog/swift/the-magic-behind-uuid-in-swift) — Article · Topics: Swift
  **NeKI brief:** Explains how UUID values are generated in Swift and why they are treated as unique identifiers. Use it when reviewing identifier design, persistence, or collision assumptions in application data.
- [Universal Links At Scale: The Challenges Nobody Talks About](https://albertodebortoli.com/2026/01/15/universal-links-at-scale-the-challenges-nobody-talks-about) — Article · Topics: Testing
  **NeKI brief:** Explains Universal Links At Scale: The Challenges Nobody Talks About, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Swift Compiler Changes the Easy Way](https://www.massicotte.org/blog/compiler-changes-the-easy-way) — Article · Topics: Swift
  **NeKI brief:** Presents Swift Compiler Changes the Easy Way, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Defining custom string interpolation behavior in Swift](https://nilcoalescing.com/blog/DefiningCustomStringInterpolationBehaviorInSwift) — Article · Topics: Swift
  **NeKI brief:** Shows extending Swift string interpolation so domain types can control formatting directly inside literals. Use it when designing readable, type-directed output while keeping conversion logic centralized instead of scattering formatter calls through UI code.
- [Introducing AI prompts and recording metadata](https://www.rocketsim.app/blog/introducing-ai-prompts-and-recording-metadata) — Article · Topics: AI Development
  **NeKI brief:** Documents Introducing AI prompts and recording metadata, focusing on an iOS Simulator workflow and the concrete debugging or testing decisions it enables for Apple-platform development.
- [@_exported import VS public import](https://alexanderweiss.dev/blog/2026-01-16-exported-import-vs-public-import) — Article
  **NeKI brief:** This article compares Swift's @_exported imports with SE-0409 access-level imports. It clarifies how each choice controls dependency visibility for framework clients and when a migration should prefer the newer public-import model.

## [Issue 306](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-306)

- Published: `2026-01-13T15:06:45.000Z`

**Topics:** App Distribution & Store Operations · Concurrency · Developer Community & Business · Graphics, Media & Games · Swift · SwiftUI

**Sections:** SwiftLee Weekly by Antoine van der Lee · AI Agents That Actually Optimize Your Apps · Understanding Spring Animations in SwiftUI

**Selected links:**
- [my YouTube series on this app](https://youtube.com/playlist?list=PLg4qABgFp_nRYMtGFdXz8sUeXb2IDxdPL&si=Imqah2BEAj-b-WAM) — Video · Topics: App Distribution & Store Operations · Graphics, Media & Games · Testing
  **NeKI brief:** Documents building and launching an open-source app toward $10K monthly recurring revenue, including releases, App Store review, crashes, growth, pricing, and technical decisions. Useful for connecting product milestones with implementation trade-offs.
- [Swift Modules and Code/Assets Duplication](https://pfandrade.me/blog/swift-modules-and-codeassets-duplication) — Article · Topics: Swift · Swift Package Manager
  **NeKI brief:** Presents Swift Modules and Code/Assets Duplication, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Agent Skills explained: Replacing AGENTS.md with reusable AI knowledge](https://www.youtube.com/watch?v=khekVi1PK3o) — Video · Topics: AI Development · Graphics, Media & Games · Swift
  **NeKI brief:** Explains how coding-agent skills differ from repository instructions, how they are discovered, installed, and updated, then applies a Swift concurrency skill to a real app refactor. Useful for assessing reusable agent workflows.
- [Understanding Spring Animations in SwiftUI](https://www.createwithswift.com/understanding-spring-animations-in-swiftui) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Explains SwiftUI spring animation parameters and the relationship between motion response and damping. Use it when tuning a transition by observed behavior instead of repeatedly guessing numeric values.
- [InlineArray in Swift - Memory Efficient Fixed-Size Arrays](https://www.sagarunagar.com/blog/inlinearray-in-swift) — Article · Topics: Performance · Swift
  **NeKI brief:** Explains InlineArray in Swift - Memory Efficient Fixed-Size Arrays, focusing on the underlying Swift or Apple-platform mechanism and the implementation trade-offs relevant to production code.
- [Active ReviewSE-0502Exclude private initialized properties from memberwise initializer](https://github.com/apple/swift-evolution/blob/main/proposals/0502-exclude-private-from-memberwise-init.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0502Exclude private initialized properties from memberwise initializer. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0503Suppressed Default Conformances on Associated Types With Defaults](https://github.com/apple/swift-evolution/blob/main/proposals/0503-suppressed-associated-types.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Records Active ReviewSE-0503Suppressed Default Conformances on Associated Types With Defaults, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [CKSyncEngine questions and answers](https://christianselig.com/2026/01/cksyncengine) — Article
  **NeKI brief:** Christian dives into his experience using Apple’s new CKSyncEngine API for CloudKit syncing, answering common questions and sharing practical insights on real-world issues.
- [My Beef with the iOS 26 Tab Bar](https://ryanashcraft.com/ios-26-tab-bar-beef) — Article
  **NeKI brief:** Presents My Beef with the iOS 26 Tab Bar, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.

## [Issue 305](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-305)

- Published: `2026-01-06T15:07:32.000Z`

**Topics:** AI Development · Concurrency · Developer Community & Business · Developer Tools · Swift · Swift Package Manager

**Sections:** SwiftLee Weekly by Antoine van der Lee · Icon Composer: Transforming an AI-generated icon · Simple Tools for Network Debugging

**Selected links:**
- [Have LLMs improved for Swift coding in the last 12 months?](https://www.cocoawithlove.com/blog/llms-twelve-months-later.html) — Article · Topics: AI Development · Objective-C & Cocoa · Swift
  **NeKI brief:** Re-tests several hosted and local LLMs on Swift tasks, including prompting an entire app and comparing model-specific behavior. Follow it for qualitative workflow evidence, not a stable benchmark, and reproduce tests on your own codebase.
- [Dimillian/Skills: My Codex Skills](https://github.com/Dimillian/Skills) — Source repository · Topics: AI Development · Developer Tools
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Dimillian/Skills: My Codex Skills. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Agent Skills for Codex](https://developers.openai.com/codex/skills) — Article · Topics: AI Development · Developer Tools
  **NeKI brief:** Presents Agent Skills for Codex, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Intercepting SwiftUI Sheet Dismissal](https://livsycode.com/swiftui/intercepting-swiftui-sheet-dismissal) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Artem shows how to intercept and control sheet dismissal in SwiftUI to detect when a presented sheet is being dismissed, letting you run custom logic or block the dismissal when needed.
- [Replay](https://nshipster.com/replay) — Article · Topics: Swift · Testing
  **NeKI brief:** Presents Replay, which records HTTP exchanges as HAR files and replays them through URL loading hooks during Swift Testing. The approach keeps networking tests realistic without live servers, while the sensitive-data section makes fixture sanitization part of the design.
- [Versioned Package.swift Files](https://www.massicotte.org/blog/package-swift) — Article · Topics: Swift · Swift Package Manager
  **NeKI brief:** Presents Versioned Package.swift Files, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.

## [Issue 304](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-304)

- Published: `2025-12-30T15:12:31.000Z`

**Topics:** Architecture · Dependency Injection · Developer Community & Business · Swift · Swift Package Manager · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · RocketSim: Build iOS apps up to 2x faster with enhanced Xcode Simulator tools · Shipping at Inference-Speed | Peter Steinberger

**Selected links:**
- [Explicit Dependency Injection → Livsy Code](https://livsycode.com/best-practices/explicit-dependency-injection) — Article · Topics: Architecture · Dependency Injection
  **NeKI brief:** Explains explicit dependency injection in Swift and why construction-time wiring improves testability. Use it when removing hidden singletons, defining feature boundaries, and keeping production composition separate from previews and test fixtures.
- [AI (Without the Hype)](https://build.ms/2025/12/24/ai-without-the-hype-ns-spain-2025) — Article · Topics: AI Development
  **NeKI brief:** Presents AI (Without the Hype), focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [How to Find a Winning App Idea (Before You Waste Months Building the Wrong One)](https://www.youtube.com/watch?v=LZWaMmTlw-M) — Video · Topics: AI Development
  **NeKI brief:** Presents an eight-step process for validating a potentially profitable app idea through market research, ASO data, competitor analysis, monetization, personal strengths, and audience fit before committing to implementation.
- [Swift Package Manager Mirrors for Local Development](https://kunat.dev/notes/spm-package-mirroring) — Article · Topics: Swift · Swift Package Manager
  **NeKI brief:** Presents Swift Package Manager Mirrors for Local Development, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Shipping at Inference-Speed | Peter Steinberger](https://steipete.me/posts/2025/shipping-at-inference-speed) — Article · Topics: AI Development
  **NeKI brief:** Discusses Shipping at Inference-Speed | Peter Steinberger, extracting concrete product or engineering practices that help independent Apple-platform developers make informed delivery decisions.

## [Issue 303](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-303)

- Published: `2025-12-23T15:06:56.000Z`

**Topics:** AI Development · Concurrency · Developer Community & Business · Swift · SwiftUI · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · RocketSim: Build iOS apps up to 2x faster with enhanced Xcode Simulator tools · SwiftAgents: Langchain but for swift

**Selected links:**
- [SwiftAgents: Langchain but for swift](https://github.com/christopherkarani/SwiftAgents) — Source repository · Topics: AI Development · Developer Tools · Swift
  **NeKI brief:** SwiftAgents is a Swift-oriented agent framework inspired by LangChain concepts. Use it to evaluate typed agent orchestration in a Swift project, while scrutinizing tool permissions, memory design, and provider boundaries.
- [How I use Codex GPT 5.2 with Xcode (My complete workflow)](https://www.youtube.com/watch?v=o4iKnSYlhBQ) — Video · Topics: AI Development · Personal Essays · Xcode
  **NeKI brief:** Shows a Codex-and-Xcode workflow built around Makefile commands, xcbeautify, simulator-control tools, accessibility inspection, and Instruments. Useful for understanding how an agent can build, observe, interact with, and profile an iOS app.
- [AcceptedSE-0499Support ~Copyable, ~Escapable in simple standard library protocols](https://github.com/apple/swift-evolution/blob/main/proposals/0499-support-non-copyable-simple-protocols.md) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0499Support ~Copyable, ~Escapable in simple standard library protocols. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Stop Getting Average Code from Your LLM | Krzysztof Zabłocki](https://merowing.info/posts/stop-getting-average-code-from-your-llm) — Article · Topics: AI Development · Code Quality
  **NeKI brief:** Discusses Stop Getting Average Code from Your LLM | Krzysztof Zabłocki, providing concrete engineering context that Apple-platform developers can use when evaluating the referenced workflow.
- [Stretchable Header in SwiftUI for Vertical and Horizontal ScrollView → Livsy Code](https://livsycode.com/swiftui/stretchable-header-in-swiftui-for-vertical-and-horizontal-scrollview) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Artem explains how to build a stretchable header in SwiftUI that enlarges or shrinks based on scroll position, whether in a vertical or horizontal ScrollView, using geometry readers and view offset tracking.
- [Non-Sendable First Design](https://www.massicotte.org/blog/non-sendable-first-design) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Matt argues for designing Swift code around non-Sendable types by default, introducing Sendable and actors only when crossing isolation boundaries to keep concurrency simpler and more intentional.

## [Issue 302](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-302)

- Published: `2025-12-16T15:09:01.000Z`

**Topics:** CI/CD & Automation · Concurrency · Developer Community & Business · macOS & AppKit · Swift · SwiftUI

**Sections:** SwiftLee Weekly by Antoine van der Lee · Fastlane alternative - Codemagic CLI tools · Swift Configuration 1.0 released

**Selected links:**
- [How to avoid retain cycles when working with tasks in Swift](https://tanaschita.com/swift-async-tasks-memory-management) — Article · Topics: Concurrency · Developer Career & Practice · Swift
  **NeKI brief:** Explains retain-cycle risks around Task closures and reference ownership. Use it when asynchronous work outlives a view or controller and cancellation, weak capture, or task storage determines whether objects release.
- [Fastlane alternative - Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository · Topics: CI/CD & Automation · Developer Tools
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [Understanding scenes for your macOS app](https://www.createwithswift.com/understanding-scenes-for-your-macos-app) — Article · Topics: macOS & AppKit · Swift
  **NeKI brief:** Explains macOS SwiftUI scenes and their role in app windows, settings, menu commands, and lifecycle. Use it when decomposing a desktop app beyond one WindowGroup and assigning each surface its proper scene type.
- [Add an inner shadow to a symbol image in SwiftUI](https://nilcoalescing.com/blog/AddAnInnerShadowToASymbolImageInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Creates an inner-shadow effect for SF Symbols in SwiftUI through masking and compositing. Use it when symbol depth needs a controlled visual treatment without replacing scalable system glyphs with raster assets.
- [SwiftUI Group Still(?) Considered Harmful](https://twocentstudios.com/2025/12/12/swiftui-group-still-considered-harmful) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains SwiftUI Group Still(?) Considered Harmful, connecting the underlying Apple-platform mechanism to implementation choices and practical trade-offs that Swift developers can evaluate.

## [Issue 301](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-301)

- Published: `2025-12-09T15:08:23.000Z`

**Topics:** App Distribution & Store Operations · Concurrency · Developer Community & Business · Graphics, Media & Games · Swift · SwiftUI

**Sections:** SwiftLee Weekly by Antoine van der Lee · Battery life on iOS and the impact of killing apps · Full iOS coverage. Fast

**Selected links:**
- [Apple's new App Review Guidelines crack down on copycat apps](https://9to5mac.com/2025/11/13/apple-tightens-app-review-guidelines-to-crack-down-on-copycat-apps) — Article · Topics: AI Development · App Distribution & Store Operations
  **NeKI brief:** Discusses Apple's new App Review Guidelines crack down on copycat apps, extracting concrete engineering practices and trade-offs that Apple-platform developers can apply when evaluating this workflow.
- [Organizing SwiftUI Views with TabContent and @TabContentBuilder → Livsy Code](https://livsycode.com/swiftui/organizing-swiftui-views-with-tabcontent-and-tabcontentbuilder) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Artem explains how to organize a SwiftUI project by using a custom @TabContentBuilder to cleanly structure and manage tab-based navigation/components making your code more modular and easier to maintain.
- [Initializing @Observable classes within the SwiftUI hierarchy](https://nilcoalescing.com/blog/InitializingObservableClassesWithinTheSwiftUIHierarchy) — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **NeKI brief:** Compares ownership patterns for creating @Observable reference types inside SwiftUI, including state storage and dependency injection. Useful for preventing model recreation when view identity changes.
- [Returned For RevisionSE-0283Tuples Conform to `Equatable`, `Comparable`, and `Hashable`](https://github.com/apple/swift-evolution/blob/main/proposals/0283-tuples-are-equatable-comparable-hashable.md) — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Returned For RevisionSE-0283Tuples Conform to `Equatable`, `Comparable`, and `Hashable`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0501HTML Coverage Report](https://github.com/apple/swift-evolution/blob/main/proposals/0501-swiftpm-html-coverage-report.md) — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0501HTML Coverage Report. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Full iOS coverage. Fast](https://www.qawolf.com/solutions/ios-testing) — Article · Topics: Testing
  **NeKI brief:** Explains Full iOS coverage. Fast, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.

## [Issue 300](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-300)

- Published: `2025-12-02T15:13:04.000Z`

**Topics:** CI/CD & Automation · Developer Tools · Swift · Swift Package Manager · Testing · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · The 7 changes I do for every new Xcode project · Full iOS coverage. Fast

**Selected links:**
- [How to access SFSymbols directly in Xcode](https://ohmyswift.com/blog/2025/11/30/how-to-access-sfsymbols-directly-in-xcode) — Article · Topics: Swift · Xcode
  **NeKI brief:** Explains How to access SFSymbols directly in Xcode, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Teaching AI to Read Xcode Builds](https://tuist.dev/blog/2025/11/27/teaching-ai-to-read-xcode-builds) — Article · Topics: AI Development · Xcode
  **NeKI brief:** Presents Teaching AI to Read Xcode Builds, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Improving Swift Package Scripts with GitHub Actions workflows](https://danielsaidi.com/blog/2025/11/26/improving-swift-package-scripts-with-github-action-workflows) — Article · Topics: Developer Tools · Swift · Swift Package Manager
  **NeKI brief:** Examines A list of ready-to-use GitHub Actions workflows for Swift Packages in the context of Developer Tools and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [The 7 changes I do for every new Xcode project](https://youtu.be/-D_OrL6wALM?si=orRBojhwAbofQore) — Video · Topics: Xcode
  **NeKI brief:** Reviews seven Xcode project settings and structural choices, including approachable concurrency, upcoming Swift features, strict concurrency, build settings, App Groups, folder organization, and package boundaries. Useful when modernizing a project's baseline configuration.
- [Full iOS coverage. Fast](https://www.qawolf.com/solutions/ios-testing) — Article · Topics: Testing
  **NeKI brief:** Explains Full iOS coverage. Fast, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Understanding the Transferable Protocol in Swift](https://www.createwithswift.com/understanding-the-transferable-protocol-in-swift) — Article · Topics: Swift
  **NeKI brief:** Explains Transferable representations and type-specific export or import formats for system sharing. Useful when designing drag, drop, paste, or share flows that support more than one data representation.
- [Using associated domains alternate mode during development](https://tanaschita.com/ios-associated-domains-alternate-mode) — Article · Topics: App Services & Extensions
  **NeKI brief:** Explains alternate associated-domains mode for development and testing. Use it when universal-link or web-credential configuration must point at a non-production environment without changing the application's primary entitlement design.

## [Issue 299](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-299)

- Published: `2025-11-25T15:16:48.000Z`

**Topics:** Developer Community & Business · Observation & State Management · Persistence & Synchronisation · Swift · SwiftData · UIKit

**Sections:** SwiftLee Weekly by Antoine van der Lee · iOS auth eating your time? · Automatic property observation in UIKit with @Observable

**Selected links:**
- [Automatic property observation in UIKit with @Observable](https://nilcoalescing.com/blog/AutomaticPropertyObservationInUIKitWithObservable) — Article · Topics: Observation & State Management · UIKit
  **NeKI brief:** Shows applying @Observable-style automatic property tracking outside SwiftUI, including UIKit. Use it when an imperative UI needs targeted change observation without manually maintaining a broad notification mechanism.
- [iOS auth eating your time?](https://go.clerk.com/sxkDCu7) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Presents iOS auth eating your time?, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Providing a default value in a String interpolation](https://www.swiftwithvincent.com/blog/providing-a-default-value-in-a-string-interpolation) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents Providing a default value in a String interpolation, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Active ReviewSE-0499Support ~Copyable, ~Escapable in simple standard library protocols](https://github.com/apple/swift-evolution/blob/main/proposals/0499-support-non-copyable-simple-protocols.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0499Support ~Copyable, ~Escapable in simple standard library protocols. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0500Improving package creation with custom templates: SwiftPM Template Initialization](https://github.com/apple/swift-evolution/blob/main/proposals/0500-package-manager-templates.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Records AcceptedSE-0500Improving package creation with custom templates: SwiftPM Template Initialization, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Build Smart Before You Build Fast](https://tuist.dev/blog/2025/11/17/smart-before-fast) — Article
  **NeKI brief:** Presents Build Smart Before You Build Fast, with practical context for Apple-platform developers evaluating the technique, workflow, or engineering decision described on the page.
- [When To Kill A Project](https://blog.jacobstechtavern.com/p/when-to-kill-a-project) — Article
  **NeKI brief:** Discusses signals and decision criteria for ending an app project when its costs, risks, or opportunity trade-offs no longer make sense. Useful as a product-engineering reflection before continuing sunk-cost work or reallocating a small team.

## [Issue 298](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-298)

- Published: `2025-11-18T19:03:17.000Z`

**Topics:** Architecture · Concurrency · Developer Community & Business · Performance · Swift · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · Try Clerk for Swift · Deep Dive into iMessage - Behind the Making of an Agent

**Selected links:**
- [Approachable Concurrency in Swift 6.2: A Clear Guide](https://youtu.be/y_Qc8cT-O_g?si=W2ExWkL4BbMjT8cH) — Video · Topics: Combine & Reactive Programming · Concurrency · Swift
  **NeKI brief:** Explains Swift 6.2 approachable concurrency through default actor isolation, nonisolated async behavior, isolated conformances, and upcoming features, then applies the migration concepts to RocketSim. Useful for planning incremental concurrency adoption.
- [How to Build Scalable White-Label iOS Apps: From Multi-Target to Modular Architecture ‣ Swift and Memes](https://swiftandmemes.com/how-to-build-scalable-white-label-ios-apps-from-multi-target-to-modular-architecture) — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **NeKI brief:** Explains a white-label iOS architecture that evolves from multi-target projects toward modular components. Use it when separating brand configuration from shared features and assessing build, test, and release trade-offs.
- [ImplementedSE-0495C compatible functions and enums](https://github.com/apple/swift-evolution/blob/main/proposals/0495-cdecl.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0495C compatible functions and enums. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Task Identity in SwiftUI & Swift Concurrency](https://chris.eidhof.nl/post/swiftui-task-identity) — Article · Topics: Concurrency · Swift · SwiftUI
  **NeKI brief:** Connects SwiftUI view identity and dependency tracking to the lifetime and restart behavior of tasks. Use it when asynchronous work appears to run with stale inputs or at unexpected times.
- [Deep Dive into iMessage - Behind the Making of an Agent](https://fatbobman.com/en/posts/deep-dive-into-imessage) — Article · Topics: Security & Privacy
  **NeKI brief:** Investigates iMessage storage through SQLite and Core Data timestamps, then uses imessage-kit to build an automation agent. The article is a concrete reference for understanding macOS message data boundaries and automation risks.
- [Building Peer-to-Peer Sessions: Advertising and Browsing Devices](https://www.createwithswift.com/building-peer-to-peer-sessions-advertising-and-browsing-devices) — Article · Topics: Swift
  **NeKI brief:** Builds peer-to-peer discovery by advertising and browsing nearby devices. Use it when a local collaboration feature needs session establishment without central infrastructure, while designing identity, invitations, and disconnect handling.
- [Generating images in Swift using Image Playground](https://swiftwithmajid.com/2025/11/11/generating-images-in-swift-using-image-playground) — Article · Topics: Swift
  **NeKI brief:** Shows generating images through Image Playground from Swift. Use it when designing the app-to-system creation flow, including prompt context, user choice, and availability handling around Apple Intelligence features.

## [Issue 297](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-297)

- Published: `2025-11-11T15:06:31.000Z`

**Topics:** Combine & Reactive Programming · Concurrency · Developer Career & Practice · Developer Community & Business · Performance · Swift

**Sections:** SwiftLee Weekly by Antoine van der Lee · Transform Your Career with the iOS Lead Essentials — Black Friday Offer · From Swift to Mojo and high-performance AI Engineering with Chris Lattner

**Selected links:**
- [Transforming AsyncStream with Swift Async Algorithms](https://tanaschita.com/swift-async-algorithms-asyncstream) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Transforms AsyncStream values with Swift Async Algorithms rather than hand-writing stream plumbing. Use it when throttling, combining, or mapping asynchronous events needs clear cancellation and buffering semantics.
- [ImplementedSE-0497Controlling function definition visibility in clients](https://github.com/apple/swift-evolution/blob/main/proposals/0497-definition-visibility.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0497Controlling function definition visibility in clients. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [From Swift to Mojo and high-performance AI Engineering with Chris Lattner](https://newsletter.pragmaticengineer.com/p/from-swift-to-mojo-and-high-performance) — Podcast · Topics: AI Development · Performance · Swift
  **NeKI brief:** Presents From Swift to Mojo and high-performance AI Engineering with Chris Lattner, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Active ReviewSE-0498Expose demangle function in Runtime module](https://github.com/apple/swift-evolution/blob/main/proposals/0498-runtime-demangle.md) — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **NeKI brief:** Records Active ReviewSE-0498Expose demangle function in Runtime module, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [A deep dive into Collections, Sequences, and Iterators in Swift](https://www.donnywals.com/a-deep-dive-into-collections-sequences-and-iterators-in-swift) — Article · Topics: Swift
  **NeKI brief:** Clarifies the relationship between Collection, Sequence, and IteratorProtocol in Swift. Use it when a custom data source needs the right traversal guarantees and you must distinguish single-pass iteration from multi-pass indexed access.
- [How Antoine van der Lee made $40K on his first Teachable course launch → Teachable](https://teachable.com/blog/antoine-van-der-lee-case-study) — Tutorial · Topics: Developer Community & Business
  **NeKI brief:** Presents How Antoine van der Lee made $40K on his first Teachable course launch → Teachable, documenting the referenced developer product or learning offer and its practical context for independent iOS work.
- [One Swift mistake everyone should stop making today](https://www.hackingwithswift.com/articles/280/one-swift-mistake-everyone-should-stop-making-today) — Article · Topics: Swift
  **NeKI brief:** Highlights a recurring Swift design or implementation pitfall through a focused example. Use it as a review prompt for the specific language habit discussed, then confirm it applies to your compiler and codebase context.

## [Issue 296](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-296)

- Published: `2025-11-04T08:02:52.000Z`

**Topics:** Combine & Reactive Programming · Concurrency · Developer Community & Business · Graphics, Media & Games · Swift · SwiftUI

**Sections:** SwiftLee Weekly by Antoine van der Lee · Your exclusive SwiftLee discount ends tonight · Simulator Camera: Test your app without a physical device

**Selected links:**
- [Optimize your app's speed and efficiency](https://www.youtube.com/watch?v=yXAQTIKR8fk) — Video · Topics: AI Development · Foundation & Data Formats · Performance
  **NeKI brief:** Summarizes a Meet with Apple performance session spanning power use, Foundation Models response latency, SwiftUI responsiveness, and Snap's diagnostic tools. Useful as a map of optimization areas before consulting the corresponding primary guidance.
- [Text Effects using TextRenderer in SwiftUI](https://www.createwithswift.com/text-effects-using-textrenderer-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents Text Effects using TextRenderer in SwiftUI, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [The Problem With Combine Annotations](https://www.massicotte.org/combine-annotations) — Article · Topics: Combine & Reactive Programming · Concurrency · Swift
  **NeKI brief:** Explains The Problem With Combine Annotations, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [ScrollView snapping in SwiftUI](https://nilcoalescing.com/blog/ScrollViewSnappingInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Configures SwiftUI scroll target behavior and snapping so items settle at deliberate positions. Useful for carousels and paged content without implementing custom drag-end calculations.
- [I Gave My First Conference Talk](https://chriswu.com/posts/speaking/sl2025) — Article · Topics: Developer Community & Business
  **NeKI brief:** Discusses I Gave My First Conference Talk, extracting concrete engineering practices and trade-offs that Apple-platform developers can apply when evaluating this workflow.
- [What's new in Swift: October 2025 Edition](https://swift.org/blog/whats-new-in-swift-october-2025) — Article · Topics: Swift
  **NeKI brief:** Explains What's new in Swift: October 2025 Edition, connecting the underlying Apple-platform mechanism to implementation choices and practical trade-offs that Swift developers can evaluate.

## [Issue 295](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-295)

- Published: `2025-10-28T15:02:32.000Z`

**Topics:** Developer Community & Business · Graphics, Media & Games · Performance · Swift · SwiftUI · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · Build performance analysis for speeding up Xcode builds · The best mobile app monitoring product just keeps getting better

**Selected links:**
- [Build performance analysis for speeding up Xcode builds](https://youtu.be/9L1p0McuThM) — Video · Topics: Graphics, Media & Games · Performance · Xcode
  **NeKI brief:** Shows how to investigate Xcode build performance using the Build Navigator, timing summaries, compiler flags, script phases, and clean-versus-incremental comparisons. It also covers slow SwiftUI expressions and tracking improvements across a team.
- [Integrating Device Camera in SwiftUI Apps](https://www.createwithswift.com/integrating-device-camera-in-swiftui-apps) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Integrates device-camera capture into a SwiftUI app through an appropriate framework bridge. Use it when a camera feature needs permission flow, capture lifecycle, and image handoff designed explicitly rather than a one-off picker.
- [Announcing the Swift SDK for Android](https://www.swift.org/blog/nightly-swift-sdk-for-android) — Article · Topics: Cross-Platform & Web · Swift
  **NeKI brief:** We can't wait to see what scary things you will Create with Swift tonight! 🎃👻
- [Custom Progress Indicator with SwiftUI Symbol Effects](https://livsycode.com/swiftui/custom-progress-indicator-with-swiftui-symbol-effects) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents Custom Progress Indicator with SwiftUI Symbol Effects, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [The best mobile app monitoring product just keeps getting better](https://sentry.io/for/swift) — Article · Topics: Swift
  **NeKI brief:** Presents The best mobile app monitoring product just keeps getting better, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Emerge Tools is now a part of Sentry](https://www.emergetools.com/blog/posts/emerge-tools-is-joining-sentry) — Article · Topics: Swift
  **NeKI brief:** Presents Emerge Tools is now a part of Sentry, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [AcceptedSE-0496`@inline(always)` attribute](https://github.com/apple/swift-evolution/blob/main/proposals/0496-inline-always.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Records ImplementedSE-0496`@inline(always)` attribute, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Open source case study: Listening to our users](https://www.pointfree.co/blog/posts/189-open-source-case-study-listening-to-our-users) — Article · Topics: Persistence & Synchronisation
  **NeKI brief:** Shares Point-Free's open-source case study about listening to users and evolving a product in response. Useful for examining feedback loops, prioritization, and maintainers' communication choices when an Apple-platform library serves a changing community.

## [Issue 294](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-294)

- Published: `2025-10-21T14:13:02.000Z`

**Topics:** Architecture · Combine & Reactive Programming · Concurrency · Developer Community & Business · Swift · SwiftUI

**Sections:** SwiftLee Weekly by Antoine van der Lee · SwiftUI Architecture: Structure Views for Reusability and Clarity · The best mobile app monitoring product just keeps getting better

**Selected links:**
- [SwiftUI Architecture: Structure Views for Reusability and Clarity](https://youtu.be/W05mPR71zaQ) — Video · Topics: Architecture · Objective-C & Cocoa · Swift
  **NeKI brief:** Refactors a large SwiftUI view into reusable components, modifiers, extensions, and a small UI library. It explains why computed view properties alone do not provide the isolation or reuse of genuine component boundaries.
- [Replacing Combine's subjects with AsyncStream in Swift](https://tanaschita.com/swift-combine-subjects-vs-asyncstream) — Article · Topics: Combine & Reactive Programming · Concurrency · Swift
  **NeKI brief:** Compares Combine subjects with `AsyncStream`, contrasting multicasting and operator ecosystems with Swift Concurrency's cancellation-aware async iteration. Follow it when migrating event pipelines and deciding whether a stream needs replay, multiple consumers, or structured concurrency.
- [AcceptedSE-0492Section Placement Control](https://github.com/apple/swift-evolution/blob/main/proposals/0492-section-control.md) — Source repository · Topics: Developer Community & Business · Developer Tools · Swift
  **NeKI brief:** Records ImplementedSE-0492Section Placement Control, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [AcceptedSE-0494Add `isIdentical(to:)` Methods for Quick Comparisons to Concrete Types](https://github.com/apple/swift-evolution/blob/main/proposals/0494-add-is-identical-methods.md) — Source repository · Topics: Developer Community & Business · Developer Tools · Swift
  **NeKI brief:** Records AcceptedSE-0494Add `isIdentical(to:)` Methods for Quick Comparisons to Concrete Types, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Active ReviewSE-0497Controlling function definition visibility in clients](https://github.com/apple/swift-evolution/blob/main/proposals/0497-definition-visibility.md) — Source repository · Topics: Developer Community & Business · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0497Controlling function definition visibility in clients. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [The best mobile app monitoring product just keeps getting better](https://sentry.io/for/swift) — Article · Topics: Swift
  **NeKI brief:** Presents The best mobile app monitoring product just keeps getting better, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Emerge Tools is now a part of Sentry](https://www.emergetools.com/blog/posts/emerge-tools-is-joining-sentry) — Article · Topics: Swift
  **NeKI brief:** Presents Emerge Tools is now a part of Sentry, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Don't make this mistake with a TaskGroup](https://www.swiftwithvincent.com/blog/dont-make-this-mistake-with-a-taskgroup) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains Don't make this mistake with a TaskGroup, focusing on the underlying Swift or Apple-platform mechanism and the implementation trade-offs relevant to production code.
- [Singletons with Swift Concurrency](https://www.massicotte.org/singletons) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains Singletons with Swift Concurrency, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Just Talk To It - the no-bs Way of Agentic Engineering](https://steipete.me/posts/just-talk-to-it) — Article · Topics: AI Development · Swift
  **NeKI brief:** Presents Just Talk To It - the no-bs Way of Agentic Engineering, with practical context for Apple-platform developers evaluating the technique, workflow, or engineering decision described on the page.

## [Issue 293](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-293)

- Published: `2025-10-14T14:14:22.000Z`

**Topics:** AI Development · Concurrency · Developer Community & Business · Objective-C & Cocoa · Swift · SwiftUI

**Sections:** SwiftLee Weekly by Antoine van der Lee · Why Swift Migration Tooling Matters · The best mobile app monitoring product just keeps getting better

**Selected links:**
- [Building AI features using Foundation Models. Streaming.](https://swiftwithmajid.com/2025/10/08/building-ai-features-using-foundation-models-streaming) — Article · Topics: AI Development · Foundation & Data Formats · Swift
  **NeKI brief:** Shows how Foundation Models streams partial generated results rather than waiting for one completed response. Use it when designing incremental SwiftUI updates, cancellation behavior, and UI state for model output that arrives over time.
- [Performing search with SwiftData in a SwiftUI app](https://www.createwithswift.com/performing-search-with-swiftdata-in-a-swiftui-app) — Article · Topics: Objective-C & Cocoa · Swift · SwiftData
  **NeKI brief:** Builds SwiftData search in SwiftUI using predicates and query-driven state. Use it when filtering persisted models and needing search text, sort order, and result updates to remain declarative.
- [AcceptedSE-0491Module selectors for name disambiguation](https://github.com/apple/swift-evolution/blob/main/proposals/0491-module-selectors.md) — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0491Module selectors for name disambiguation. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [The best mobile app monitoring product just keeps getting better](https://sentry.io/for/swift) — Article · Topics: Swift
  **NeKI brief:** Presents The best mobile app monitoring product just keeps getting better, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Emerge Tools is now a part of Sentry](https://www.emergetools.com/blog/posts/emerge-tools-is-joining-sentry) — Article · Topics: Swift
  **NeKI brief:** Presents Emerge Tools is now a part of Sentry, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [When SwiftUI automatically applies the glass look and when it doesn’t](https://tanaschita.com/swiftui-glass-auto-apply) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains when SwiftUI automatically applies Liquid Glass and when explicit modifiers are required. Useful for diagnosing inconsistent material appearance across containers and platform contexts.
- [Cultivated Task Cancellation](https://macguru.dev/cultivated-task-cancellation) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains Cultivated Task Cancellation, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Why a custom ViewModifier is often useless](https://www.swiftwithvincent.com/blog/why-a-custom-viewmodifier-is-often-useless) — Article · Topics: Swift
  **NeKI brief:** Argues that many custom ViewModifiers add indirection without clarifying behavior, and shows when direct composition is better. Useful for reviewing SwiftUI abstractions against readability, reuse, and discoverable call-site intent.

## [Issue 292](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-292)

- Published: `2025-10-07T14:12:42.000Z`

**Topics:** Concurrency · Developer Community & Business · Graphics, Media & Games · Swift · SwiftUI · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · The 5 biggest mistakes iOS Developers make with async/await · The best mobile app monitoring product just keeps getting better

**Selected links:**
- [How to install Xcode 26's Metal Toolchain on CI/CD](https://www.polpiella.dev/metal-toolchain-ci-cd) — Article · Topics: CI/CD & Automation · Graphics, Media & Games · Xcode
  **NeKI brief:** Shows provisioning Xcode's Metal toolchain in CI/CD. Use it when a project compiles Metal shaders or GPU code outside a developer machine and a runner must install the matching components reproducibly.
- [Less Janky Placeholders in SwiftUI](https://harshil.net/blog/swiftui-placeholder-jank) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Presents Less Janky Placeholders in SwiftUI, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Avoiding text truncation in SwiftUI with Dynamic Type](https://nilcoalescing.com/blog/AvoidingTextTruncationInSwiftUI) — Article · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Demonstrates detecting and preventing SwiftUI text truncation through layout and typography choices. Useful for resilient localized interfaces where fixed line counts or widths are unsafe.
- [The best mobile app monitoring product just keeps getting better](https://sentry.io/for/swift) — Article · Topics: Swift
  **NeKI brief:** Presents The best mobile app monitoring product just keeps getting better, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Emerge Tools is now a part of Sentry](https://www.emergetools.com/blog/posts/emerge-tools-is-joining-sentry) — Article · Topics: Swift
  **NeKI brief:** Presents Emerge Tools is now a part of Sentry, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Programmatic navigation with navigation destination in SwiftUI](https://www.createwithswift.com/programmatic-navigation-with-navigation-destination-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Uses navigationDestination for state-driven SwiftUI navigation. Use it when routing should be expressed through typed destinations and path state instead of imperative pushes scattered across child views.
- [Active ReviewSE-0496`@inline(always)` attribute](https://github.com/apple/swift-evolution/blob/main/proposals/0496-inline-always.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Records ImplementedSE-0496`@inline(always)` attribute, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Dev Conversations #14: Antoine van Der Lee](https://www.swifttoolkit.dev/posts/dc-antoine) — Article · Topics: Swift
  **NeKI brief:** Explains Dev Conversations #14: Antoine van Der Lee, focusing on the underlying Swift or Apple-platform mechanism and the implementation trade-offs relevant to production code.

## [Issue 291](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-291)

- Published: `2025-09-30T13:58:29.000Z`

**Topics:** App Distribution & Store Operations · Concurrency · Developer Community & Business · Swift · Swift Package Manager · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · Derived Data: 5 Things iOS Developers Do Wrong · Product for Engineers newsletter

**Selected links:**
- [Active ReviewSE-0495C compatible functions and enums](https://github.com/apple/swift-evolution/blob/main/proposals/0495-cdecl.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0495C compatible functions and enums. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Structuring universal links in iOS](https://tanaschita.com/swiftui-navigation-universal-links-architecture) — Article · Topics: Architecture · Navigation & Deep Linking · Objective-C & Cocoa
  **NeKI brief:** Structures universal-link handling around SwiftUI navigation state. Use it when parsing an incoming URL, restoring a scene, and selecting a nested destination must work consistently on cold launch and while running.
- [Accessing Swift Package Manager dependency versions at runtime](https://annema.me/blog/accessing-swift-package-manager-dependency-versions-at-runtime) — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **NeKI brief:** This article solves runtime dependency-version display by copying Package.resolved during the build and parsing it in the app. It explains why a cross-platform Xcode run-script approach can collide with code signing and offers a practical debug-screen alternative.
- [How to hide a view in a screenshot](https://www.swiftwithvincent.com/blog/how-to-hide-a-view-in-a-screenshot) — Article · Topics: Swift
  **NeKI brief:** Explains How to hide a view in a screenshot, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [this tool](https://docs.rocketsim.app/features/hzQMSrSga7BGWvxdNVdwYs/deeplinks-universal-links/mYuk1cx8REK8mbbt4rhvWz) — Article · Topics: Navigation & Deep Linking · Testing
  **NeKI brief:** Explains this tool, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [All about Swift Package Manager Traits](https://theswiftdev.com/2025/all-about-swift-package-manager-traits) — Article · Topics: Swift · Swift Package Manager
  **NeKI brief:** Presents All about Swift Package Manager Traits, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.

## [Issue 290](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-290)

- Published: `2025-09-23T14:09:24.000Z`

**Topics:** AI Development · Concurrency · Developer Community & Business · Persistence & Synchronisation · Swift · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · FREE eBook: Improve build times, streamline CI, and test faster. · Kinetics: Tunable, physics-driven motion primitives for SwiftUI.

**Selected links:**
- [ImplementedSE-0482Binary Static Library Dependencies](https://github.com/apple/swift-evolution/blob/main/proposals/0482-swiftpm-static-library-binary-target-non-apple-platforms.md) — Source repository · Topics: Dependency Injection · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0482Binary Static Library Dependencies. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [FREE eBook: Improve build times, streamline CI, and test faster.](https://bitrise.io/whitepapers/level-up-your-ios-game-tips-for-speeding-up-your-continuous-integration) — Article · Topics: Graphics, Media & Games · Testing
  **NeKI brief:** Discusses Save Time on Every Build and Test Run in a public developer resource. Use it to compare the author's concrete workflow and trade-offs with your project constraints, and verify any platform-specific claims against current primary documentation.
- [Kinetics: Tunable, physics-driven motion primitives for SwiftUI.](https://github.com/roberthein/kinetics) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Kinetics is an Apple-platform project related to motion or animation behavior. Follow its source for concrete timing, physics, or interaction techniques, while verifying framework and performance assumptions.
- [SQLiteData 1.0: An alternative to SwiftData with CloudKit sync and sharing](https://www.pointfree.co/blog/posts/184-sqlitedata-1-0-an-alternative-to-swiftdata-with-cloudkit-sync-and-sharing) — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** SQLiteData combines SQLite persistence with CloudKit synchronization and sharing. Use it when SwiftData lacks required deployment or SQL control, while evaluating the operational cost of its sync model.
- [Active ReviewSE-0493Support `async` calls in `defer` bodies](https://github.com/apple/swift-evolution/blob/main/proposals/0493-defer-async.md) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0493Support `async` calls in `defer` bodies. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [available on GitHub](https://github.com/NSHipster/sosumi.ai) — Source repository · Topics: AI Development · Developer Tools
  **NeKI brief:** Points to available on GitHub, an open-source implementation or issue with concrete code and discussion that can inform Apple-platform development decisions.
- [Active ReviewSE-0492Section Placement Control](https://github.com/apple/swift-evolution/blob/main/proposals/0492-section-control.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Records ImplementedSE-0492Section Placement Control, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Active ReviewSE-0494Add `isIdentical(to:)` Methods for Quick Comparisons to Concrete Types](https://github.com/apple/swift-evolution/blob/main/proposals/0494-add-is-identical-methods.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Records AcceptedSE-0494Add `isIdentical(to:)` Methods for Quick Comparisons to Concrete Types, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Swift 6.2 Released](https://www.swift.org/blog/swift-6.2-released) — Article · Topics: Swift
  **NeKI brief:** Swift 6.2 is here with improvements that make coding smoother and faster. It delivers improved performance, faster build times, enhanced tools, and early WebAssembly support, making Swift easier and more reliable for developers.
- [Widgetsmith Five Years Later - David Smith, Independent iOS Developer](https://david-smith.org/blog/2025/09/18/widgetsmith-at-five) — Article · Topics: Apple Platform Ecosystem
  **NeKI brief:** Explains Widgetsmith Five Years Later - David Smith, Independent iOS Developer, focusing on the underlying Apple-platform behavior and the implementation trade-offs relevant to production code.

## [Issue 289](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-289)

- Published: `2025-09-16T14:09:42.000Z`

**Topics:** App Distribution & Store Operations · App Services & Extensions · Concurrency · Developer Community & Business · Developer Tools · Swift

**Sections:** SwiftLee Weekly by Antoine van der Lee · Introducing Diagnostics: Improved Debugging and User Support · Paywalls Made Easy

**Selected links:**
- [We Need to Talk About Observation](https://jaredsinclair.com/2025/09/10/observation.html) — Article · Topics: Combine & Reactive Programming · Cross-Platform & Web · Testing
  **NeKI brief:** Explains We Need to Talk About Observation, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [How to disable Liquid Glass](https://www.swiftwithvincent.com/blog/how-to-disable-liquid-glass) — Article · Topics: Liquid Glass · Swift
  **NeKI brief:** Explains How to disable Liquid Glass, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Understanding Live Activities: visual micro-storytelling](https://www.createwithswift.com/understanding-live-activities-visual-micro-storytelling) — Article · Topics: App Services & Extensions · Swift
  **NeKI brief:** Explains Live Activities as a visual storytelling surface driven by timely state updates. Useful for designing concise lock-screen and Dynamic Island experiences without treating them as miniature full screens.
- [Active ReviewSE-0491Module selectors for name disambiguation](https://github.com/apple/swift-evolution/blob/main/proposals/0491-module-selectors.md) — Source repository · Topics: App Services & Extensions · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0491Module selectors for name disambiguation. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Paywalls Made Easy](https://www.revenuecat.com/feature/paywalls) — Article · Topics: Testing
  **NeKI brief:** Explains Paywalls Made Easy, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Debug crashes in iOS using MetricKit](https://ohmyswift.com/blog/2025/05/09/debug-crashes-in-ios-using-metrickit) — Article · Topics: Swift
  **NeKI brief:** Explains Debug crashes in iOS using MetricKit, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Memory Integrity Enforcement: A complete vision for memory safety in Apple devices](https://security.apple.com/blog/memory-integrity-enforcement) — Article · Topics: Security & Privacy
  **NeKI brief:** Examines Memory Integrity Enforcement: A complete vision for memory safety in Apple devices, outlining the platform-security mechanism and its implications for designing, debugging, and shipping Apple-platform software.

## [Issue 288](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-288)

- Published: `2025-09-09T18:49:30.000Z`

**Topics:** App Distribution & Store Operations · Concurrency · Developer Community & Business · Swift · SwiftUI · Testing

**Sections:** SwiftLee Weekly by Antoine van der Lee · SwiftUI Toggle: A Complete Guide · Simple Tools for Network Debugging

**Selected links:**
- [Active ReviewSE-0490Environment Constrained Shared Libraries](https://github.com/apple/swift-evolution/blob/main/proposals/0490-environment-constrained-shared-libraries.md) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Returned For RevisionSE-0490Environment Constrained Shared Libraries. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Using MainActor.assumeIsolated to Solve Legacy API Compatibility Issues with Swift 6](https://fatbobman.com/en/posts/mainactor-assumeisolated) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains how MainActor.assumeIsolated bridges synchronous legacy callbacks to actor-isolated code while preserving Sendable return values. It is useful when Swift 6 diagnostics expose an isolation mismatch that cannot be solved by simply adding async.
- [Handling different iOS versions in a View body](https://swiftui-garden.com/Articles/Handling-different-iOS-versions-in-a-View-body) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents Handling different iOS versions in a View body, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [SwiftUI: Text Color & Concatenation](https://antongubarenko.substack.com/p/swiftui-text-color-and-concatenation) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents SwiftUI: Text Color & Concatenation, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Matching Strings In Unit Tests](https://elegantchaos.com/2025/09/03/matching-strings-in-unit-tests.html) — Article · Topics: Cross-Platform & Web · Testing
  **NeKI brief:** Discusses Matching Strings In Unit Tests, extracting concrete engineering practices and trade-offs that Apple-platform developers can apply when evaluating this workflow.
- [join the TestFlight here](https://testflight.apple.com/join/jNkgt4mf) — Article · Topics: App Distribution & Store Operations · Testing
  **NeKI brief:** Links to join the TestFlight here, a concrete TestFlight distribution page for evaluating the referenced iOS build anonymously.
- [Swift Default Value in String Interpolations](https://useyourloaf.com/blog/swift-default-value-in-string-interpolations) — Article · Topics: Swift
  **NeKI brief:** Shows Swift interpolation defaults that provide fallback text when optional values are absent. Useful for readable diagnostics and localized output without nested nil-coalescing expressions.
- [When should you use an actor?](https://www.massicotte.org/actors) — Article · Topics: Concurrency
  **NeKI brief:** Matt explores when actors are the right tool in Swift, explaining their unique isolation domain capabilities, why this protection mechanism matters for concurrent programming and outlining the specific conditions that make them the optimal choice.

## [Issue 287](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-287)

- Published: `2025-09-02T14:17:18.000Z`

**Topics:** CI/CD & Automation · Concurrency · Developer Community & Business · Graphics, Media & Games · Swift · Swift Package Manager

**Sections:** SwiftLee Weekly by Antoine van der Lee · Fastlane alternative - Codemagic CLI tools · Building a design system at Genius Scan

**Selected links:**
- [Debugging Swift Concurrency: "Am I on the Main Actor?" (Not the Main Thread)](https://www.swiftyplace.com/blog/debugging-swift-concurrency) — Article · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Explains how to determine whether Swift code runs on the MainActor rather than merely the main thread. Use it to diagnose isolation mistakes and validate actor assumptions during concurrency debugging.
- [Fastlane alternative - Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository · Topics: CI/CD & Automation · Developer Tools
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [Xcode Migrations: From Stone Age to AI Mastery](https://medium.com/qonto-way/xcode-migrations-from-stone-age-to-ai-mastery-d2590657e809) — Article · Topics: AI Development · Xcode
  **NeKI brief:** Explains Xcode Migrations: From Stone Age to AI Mastery, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Pragma Conference](https://www.pragmaconference.com/speakers.html) — Article · Topics: Concurrency · Cross-Platform & Web · Developer Community & Business
  **NeKI brief:** Describes Pragma Conference, providing the event-specific information needed to identify its Apple-platform community context.
- [Building a design system at Genius Scan](https://www.swiftbysundell.com/articles/building-a-design-system-at-genius-scan) — Article · Topics: Swift
  **NeKI brief:** Describes building a shared design system with reusable components, tokens, and constraints at Genius Scan. Useful for connecting SwiftUI component reuse to product consistency and team-scale maintenance.
- [Treating Warnings As Errors In Swift Packages](https://useyourloaf.com/blog/treating-warnings-as-errors-in-swift-packages) — Article · Topics: Swift · Swift Package Manager
  **NeKI brief:** Configures Swift Package builds to treat warnings as errors. Use it to keep library quality gates strict, while staging adoption so existing warnings do not block unrelated migration work.
- [Creating amazing loading animations with SF Symbols.](https://danielsaidi.com/blog/2025/07/24/creating-amazing-loading-animations-with-sf-symbols) — Article
  **NeKI brief:** Discusses Creating amazing loading animations with SF Symbols., extracting concrete engineering practices and trade-offs that Apple-platform developers can apply when evaluating this workflow.

## [Issue 286](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-286)

- Published: `2025-08-26T14:12:25.000Z`

**Topics:** Combine & Reactive Programming · Concurrency · Developer Community & Business · Swift · SwiftUI · Testing

**Sections:** SwiftLee Weekly by Antoine van der Lee · Swift Computed Property: Code Examples · Full iOS coverage. Fast

**Selected links:**
- [ImplementedSE-0460Explicit Specialization](https://github.com/apple/swift-evolution/blob/main/proposals/0460-specialized.md) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0460Explicit Specialization. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ImplementedSE-0476Controlling the ABI of a function, initializer, property, or subscript](https://github.com/apple/swift-evolution/blob/main/proposals/0476-abi-attr.md) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0476Controlling the ABI of a function, initializer, property, or subscript. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Open Intent in iOS 26](https://www.swiftjectivec.com/open-intent-additions-ios26-in-appintents) — Article · Topics: App Intents & System Surfaces · Swift
  **NeKI brief:** Presents Open Intent in iOS 26, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Corner concentricity in SwiftUI on iOS 26](https://nilcoalescing.com/blog/ConcentricRectangleInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Introduces ConcentricRectangle for corners that follow the system's concentric geometry. Useful for iOS 26 surfaces that need nested cards and containers to align with platform visual language.
- [SwiftUI WebView](https://troz.net/post/2025/swiftui-webview) — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Presents a concrete implementation of SwiftUI WebView. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.
- [Full iOS coverage. Fast](https://www.qawolf.com/solutions/ios-testing) — Article · Topics: Testing
  **NeKI brief:** Explains Full iOS coverage. Fast, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Managing code deprecations on iOS](https://www.scottberrevoets.com/2025/08/20/managing-code-deprecations-on-ios) — Article · Topics: Testing
  **NeKI brief:** Explains Managing code deprecations on iOS, focusing on the underlying Swift or Apple-platform mechanism and the implementation trade-offs relevant to production code.
- [Join the beta here!](https://testflight.apple.com/join/jNkgt4mf) — Article · Topics: App Distribution & Store Operations · Testing
  **NeKI brief:** Links to join the TestFlight here, a concrete TestFlight distribution page for evaluating the referenced iOS build anonymously.
- [Swift Raw Identifiers](https://useyourloaf.com/blog/swift-raw-identifiers) — Article · Topics: Swift
  **NeKI brief:** Explains Swift raw identifiers for escaping keywords and preserving source names during interoperability. Useful when wrapping generated APIs or legacy declarations without resorting to renamed adapters everywhere.

## [Issue 285](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-285)

- Published: `2025-08-19T14:12:01.000Z`

**Topics:** Concurrency · Developer Community & Business · macOS & AppKit · Swift · SwiftUI · Testing

**Sections:** SwiftLee Weekly by Antoine van der Lee · Property Wrappers in Swift explained with code examples · Accurate iOS testing on real iPhones and iPads

**Selected links:**
- [Why I'm Not Using Xcode 26's AI Chat Integration (And What Could Change My Mind)](https://www.fline.dev/why-im-not-using-xcode-26s-ai-chat-integration-and-what-could-change-my-mind) — Tutorial · Topics: AI Development · Developer Community & Business · Xcode
  **NeKI brief:** Evaluates Xcode 26's AI chat integration through practical workflow limitations and desired improvements. Use it as community perspective when comparing native and external coding-agent setups.
- [How to Work with SwiftData in the Background in Swift 6](https://www.natashatherobot.com/p/swiftdata-background-swift-6) — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** Explains How to Work with SwiftData in the Background in Swift 6, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [WithdrawnSE-0030Property Behaviors](https://github.com/apple/swift-evolution/blob/main/proposals/0030-property-behavior-decls.md) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for WithdrawnSE-0030Property Behaviors. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [AcceptedSE-0487Nonexhaustive enums](https://github.com/apple/swift-evolution/blob/main/proposals/0487-extensible-enums.md) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Records AcceptedSE-0487Nonexhaustive enums, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [How to create a custom reusable toolbar in SwiftUI](https://tanaschita.com/swiftui-reusable-toolbar) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a reusable SwiftUI toolbar component while keeping actions and state explicit. Useful for design systems that need consistent toolbar composition across screens and platforms.
- [Accurate iOS testing on real iPhones and iPads](https://www.qawolf.com/solutions/ios-testing) — Article · Topics: Testing
  **NeKI brief:** Explains Full iOS coverage. Fast, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [TextKit 2 - the promised land](https://blog.krzyzanowskim.com/2025/08/14/textkit-2-the-promised-land) — Article · Topics: Objective-C & Cocoa
  **NeKI brief:** Based on years building STTextView, this critique explains where TextKit 2 improves on TextKit 1 and where it is not a silver bullet. It provides practical caution about text-layout complexity before committing an iOS or macOS editor to the newer engine.
- [What's New in UIKit](https://sebvidal.com/blog/whats-new-in-uikit-26) — Article · Topics: UIKit
  **NeKI brief:** In this 64-minute read, Seb shares an in-depth, comprehensive, and detailed analysis of all the new UIKit APIs introduced in iOS 26.
- [Faster Equatable and Hashable conformances](https://erkek.in/faster-equatable-and-hashable-conformances-with-identifiable) — Article
  **NeKI brief:** Discusses Faster Equatable and Hashable conformances, extracting concrete engineering practices and trade-offs that Apple-platform developers can apply when evaluating this workflow.

## [Issue 284](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-284)

- Published: `2025-08-12T18:01:44.000Z`

**Topics:** Combine & Reactive Programming · Concurrency · Developer Community & Business · Swift · SwiftUI · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · Async await in Swift explained with code examples · Faster iOS app releases with automated QA

**Selected links:**
- [Streaming changes with Observations](https://swiftwithmajid.com/2025/07/30/streaming-changes-with-observations) — Article · Topics: Combine & Reactive Programming · Concurrency · Swift
  **NeKI brief:** Streams Observation changes as asynchronous values. Use it when observation must drive an async workflow outside a view body and cancellation or coalescing behavior needs explicit control.
- [another article](https://useyourloaf.com/blog/swift-observations-asyncsequence-for-state-changes) — Article · Topics: Combine & Reactive Programming · Concurrency · Swift
  **NeKI brief:** Connects Swift Observation state changes to AsyncSequence consumption. Use it when a task should react to model updates without Combine, while defining lifetime and cancellation ownership.
- [ImplementedSE-0459Add `Collection` conformances for `enumerated()`](https://github.com/apple/swift-evolution/blob/main/proposals/0459-enumerated-collection.md) — Source repository · Topics: Developer Tools · Swift · Xcode
  **NeKI brief:** Records ImplementedSE-0459Add `Collection` conformances for `enumerated()`, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [ImplementedSE-0477Default Value in String Interpolations](https://github.com/apple/swift-evolution/blob/main/proposals/0477-default-interpolation-values.md) — Source repository · Topics: Developer Tools · Swift · Xcode
  **NeKI brief:** Records ImplementedSE-0477Default Value in String Interpolations, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [ImplementedSE-0480Warning Control Settings for SwiftPM](https://github.com/apple/swift-evolution/blob/main/proposals/0480-swiftpm-warning-control.md) — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0480Warning Control Settings for SwiftPM. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ImplementedSE-0483`InlineArray` Type Sugar](https://github.com/apple/swift-evolution/blob/main/proposals/0483-inline-array-sugar.md) — Source repository · Topics: Developer Tools · Swift · Xcode
  **NeKI brief:** Records ImplementedSE-0483`InlineArray` Type Sugar, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [ImplementedSE-0485OutputSpan: delegate initialization of contiguous memory](https://github.com/apple/swift-evolution/blob/main/proposals/0485-outputspan.md) — Source repository · Topics: Developer Tools · Swift · Xcode
  **NeKI brief:** Records ImplementedSE-0485OutputSpan: delegate initialization of contiguous memory, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [ImplementedSE-0488Apply the extracting() slicing pattern more widely](https://github.com/apple/swift-evolution/blob/main/proposals/0488-extracting.md) — Source repository · Topics: Developer Tools · Swift · Xcode
  **NeKI brief:** Records ImplementedSE-0488Apply the extracting() slicing pattern more widely, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [AcceptedSE-0489Improve `EncodingError` and `DecodingError`'s printed descriptions](https://github.com/apple/swift-evolution/blob/main/proposals/0489-codable-error-printing.md) — Source repository · Topics: Developer Tools · Foundation & Data Formats · Swift
  **NeKI brief:** Records ImplementedSE-0489Improve `EncodingError` and `DecodingError`'s printed descriptions, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Define the scroll edge effect style of a scroll view for Liquid Glass](https://www.createwithswift.com/define-the-scroll-edge-effect-style-of-a-scroll-view-for-liquid-glass) — Article · Topics: Liquid Glass · Swift
  **NeKI brief:** Configures scroll-edge effects for Liquid Glass scroll views. Use it when content transitions into system material need deliberate visual treatment rather than inheriting an unsuitable default.
- [Faster iOS app releases with automated QA](https://www.qawolf.com/solutions/ios-testing) — Article · Topics: AI Development · Personal Essays · Testing
  **NeKI brief:** Explains Full iOS coverage. Fast, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Working with partially generated content in Xcode previews](https://www.artemnovichkov.com/blog/working-with-partially-generated-content-in-xcode-previews) — Article · Topics: Xcode
  **NeKI brief:** Presents Working with partially generated content in Xcode previews, with practical context for Apple-platform developers evaluating the technique, workflow, or engineering decision described on the page.
- [@isolated(any)](https://nshipster.com/isolated-any) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains Swift's isolated(any) function parameter for accepting closures whose actor isolation is inferred at the call site. The examples clarify how it can preserve isolation while designing reusable asynchronous APIs.

## [Issue 283](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-283)

- Published: `2025-08-05T17:17:03.000Z`

**Topics:** Concurrency · Cross-Platform & Web · Developer Community & Business · Developer Tools · Swift · Testing

**Sections:** SwiftLee Weekly by Antoine van der Lee · Global actor in Swift Concurrency explained with code examples · Faster iOS app releases with automated QA

**Selected links:**
- [swiftlang/swift-subprocess: Subprocess is a cross-platform package for spawning processes in Swift.](https://github.com/swiftlang/swift-subprocess) — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **NeKI brief:** swift-subprocess modernizes launching and interacting with child processes through Swift concurrency. Use it for scripts and tools that need structured stdin, stdout, cancellation, and exit-status handling beyond Foundation's older Process API.
- [Faster iOS app releases with automated QA](https://www.qawolf.com/solutions/ios-testing) — Article · Topics: AI Development · Personal Essays · Testing
  **NeKI brief:** Explains Full iOS coverage. Fast, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [swiftlang/swift-testing: A modern, expressive testing package for Swift](https://github.com/swiftlang/swift-testing) — Source repository · Topics: Developer Tools · Swift · Testing
  **NeKI brief:** Presents a concrete implementation of Swift Testing. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.
- [Swift](https://github.com/swiftlang/swift) — Source repository · Topics: Developer Tools · Swift · Testing
  **NeKI brief:** Points to Swift, an open-source implementation or issue with concrete code and discussion that can inform Apple-platform development decisions.
- [swift-package-manager](https://github.com/swiftlang/swift-package-manager) — Source repository · Topics: Developer Tools · Swift · Testing
  **NeKI brief:** Points to swift-package-manager, an open-source implementation or issue with concrete code and discussion that can inform Apple-platform development decisions.
- [swiftlang/swiftly: A Swift toolchain installer and manager, written in Swift.](https://github.com/swiftlang/swiftly) — Source repository · Topics: Developer Tools · Swift · Testing
  **NeKI brief:** Points to swiftlang/swiftly: A Swift toolchain installer and manager, written in Swift., an open-source implementation or issue with concrete code and discussion that can inform Apple-platform development decisions.
- [apple/swift-async-algorithms: Async Algorithms for Swift](https://github.com/apple/swift-async-algorithms) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** swift-async-algorithms adds reusable asynchronous sequence operators and utilities for Swift concurrency. Use it when async/await code needs throttling, merging, buffering, or other stream composition without reintroducing a full Combine pipeline.
- [apple/swift-collections: Commonly used data structures for Swift](https://github.com/apple/swift-collections) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the source and change history for Ordered dictionary anyone?, relevant to Developer Tools and Swift. Inspect its implementation, open issues, and release state before adopting the approach.

## [Issue 282](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-282)

- Published: `2025-07-29T14:14:45.000Z`

**Topics:** Combine & Reactive Programming · Concurrency · Core Data · Developer Tools · Persistence & Synchronisation · Swift

**Sections:** SwiftLee Weekly by Antoine van der Lee · Combine and Swift Concurrency: A threading risk · Fastlane alternative - Codemagic CLI tools

**Selected links:**
- [Fastlane alternative - Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository · Topics: CI/CD & Automation · Developer Tools
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [Flux pattern in Swift](https://swiftandpizza.wpcomstaging.com/flux-in-swift) — Article · Topics: Objective-C & Cocoa · Product Design · Swift
  **NeKI brief:** Presents Flux pattern in Swift, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [GitHub repository](https://github.com/AvdLee/CoreDataBestPractices) — Source repository · Topics: Core Data · Developer Tools · Persistence & Synchronisation
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for GitHub repository. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [A Peek into My Debugging Process (With Real Examples)](https://www.polpiella.dev/how-i-fix-bugs-in-my-apps) — Article · Topics: Developer Tools
  **NeKI brief:** Describes an evidence-first bug-fixing workflow that captures reproduction, narrows the failing path, and adds regression coverage. Useful as a practical debugging process rather than a framework recipe.
- [Uncertain⟨T⟩](https://nshipster.com/uncertainty) — Article
  **NeKI brief:** Uses uncertainty as a modeling problem for noisy sensors, locations, and user behavior rather than forcing false precision into scalar values. It is useful when designing APIs that must carry confidence or probabilistic outcomes explicitly.
- [Deciding between ‘let’ and ‘var’ for Swift struct properties](https://www.swiftbysundell.com/articles/let-vs-var-for-swift-struct-properties) — Article · Topics: Swift
  **NeKI brief:** Examines let versus var properties in Swift structs and how immutability affects mutation and API design. Useful for choosing value semantics deliberately in models and view state.
- [Creating amazing loading animations with SF Symbols.](https://danielsaidi.com/blog/2025/06/19/creating-amazing-loading-animations-with-sf-symbols) — Article
  **NeKI brief:** Creates loading animations from SF Symbols using symbol effects and state-driven timing. Useful for lightweight progress feedback that remains scalable and semantic instead of relying on bespoke raster animation assets.

## [Issue 281](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-281)

- Published: `2025-07-22T14:08:43.000Z`

**Topics:** AI Development · Concurrency · Developer Community & Business · Swift · Testing · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · Threads vs. Tasks in Swift Concurrency · Transform Your Career with the iOS Lead Essentials — Limited Offer

**Selected links:**
- [Approachable Concurrency in Swift Packages](https://useyourloaf.com/blog/approachable-concurrency-in-swift-packages) — Article · Topics: Concurrency · Swift · Swift Package Manager
  **NeKI brief:** Applies approachable concurrency settings to Swift packages and explains how target configuration changes diagnostics. Useful for aligning library and application migration plans.
- [ChatGPT in Xcode 26: there’s a hidden prompt!](https://www.swiftwithvincent.com/blog/chatgpt-in-xcode-26-theres-a-hidden-prompt) — Article · Topics: AI Development · Swift · Xcode
  **NeKI brief:** Presents ChatGPT in Xcode 26: there’s a hidden prompt!, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Giving Claude Code Eyes to See Your SwiftUI Views](https://twocentstudios.com/2025/07/13/giving-claude-code-eyes-to-see-your-swiftui-views) — Article · Topics: AI Development · Swift · SwiftUI
  **NeKI brief:** Chriss shows a method to enhance Claude Code’s AI-assisted SwiftUI development by letting the model visually verify and iteratively refine its view-generated code based on image comparisons.
- [ImplementedSE-0470Global-actor isolated conformances](https://github.com/apple/swift-evolution/blob/main/proposals/0470-isolated-conformances.md) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0470Global-actor isolated conformances. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [My 10 Tips for Using Claude Code](https://samwize.com/2025/07/08/my-10-tips-for-using-claude-code) — Article · Topics: AI Development
  **NeKI brief:** Presents My 10 Tips for Using Claude Code, with practical context for Apple-platform developers evaluating the technique, workflow, or engineering decision described on the page.
- [AcceptedSE-0488Apply the extracting() slicing pattern more widely](https://github.com/apple/swift-evolution/blob/main/proposals/0488-extracting.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Records ImplementedSE-0488Apply the extracting() slicing pattern more widely, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Icon Composer - Tackling Challenges](https://fatbobman.com/en/posts/icon-composer-tackling-challenges) — Article
  **NeKI brief:** Documents practical Icon Composer issues around SVG imports, monochrome brightness, layer limits, design trade-offs, and final Xcode integration.

## [Issue 280](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-280)

- Published: `2025-07-15T14:13:29.000Z`

**Topics:** Concurrency · Developer Community & Business · Macros & Metaprogramming · Swift · SwiftUI · Testing

**Sections:** SwiftLee Weekly by Antoine van der Lee · Modern Swift Lock: Mutex & the Synchronization Framework · Transform Your Career with the iOS Lead Essentials — Limited Offer

**Selected links:**
- [Confirmation and Result Interactive Snippets](https://www.swiftjectivec.com/app-intents-interactive-snippets-confirm-vs-result) — Article · Topics: App Intents & System Surfaces · Swift
  **NeKI brief:** Jordan explains how App Intents use confirmation and result snippets to handle user interactions, highlighting when to request user approval before running an action versus simply displaying the final outcome.
- [this post](https://superwall.com/blog/app-intents-interactive-snippets-in-ios-26) — Article · Topics: App Intents & System Surfaces · Swift
  **NeKI brief:** Presents this post, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Introducing Animatable macro in SwiftUI](https://swiftwithmajid.com/2025/07/08/introducing-animatable-macro-in-swiftui) — Article · Topics: Macros & Metaprogramming · Swift · SwiftUI
  **NeKI brief:** Explains SwiftUI's @Animatable macro as a way to synthesize animatable-data handling for custom views. Use it when complex values should interpolate correctly without maintaining a fragile manual AnimatableData implementation.
- [Four Months in the Making: SwiftMCP 1.0 is Here](https://www.cocoanetics.com/2025/07/four-months-in-the-making-swiftmcp-1-0-is-here) — Article · Topics: AI Development · Objective-C & Cocoa · Swift
  **NeKI brief:** Presents Four Months in the Making: SwiftMCP 1.0 is Here, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Active ReviewSE-0466Control default actor isolation inference](https://github.com/apple/swift-evolution/blob/main/proposals/0466-control-default-actor-isolation.md) — Source repository · Topics: AI Development · Concurrency · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0466Control default actor isolation inference. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0470Global-actor isolated conformances](https://github.com/apple/swift-evolution/blob/main/proposals/0470-isolated-conformances.md) — Source repository · Topics: AI Development · Concurrency · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0470Global-actor isolated conformances. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0489Improve `EncodingError` and `DecodingError`'s printed descriptions](https://github.com/apple/swift-evolution/blob/main/proposals/0489-codable-error-printing.md) — Source repository · Topics: AI Development · Developer Tools · Swift
  **NeKI brief:** Records ImplementedSE-0489Improve `EncodingError` and `DecodingError`'s printed descriptions, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Reaper - An open-source SDK for finding dead code](https://blog.sentry.io/an-open-source-sdk-for-finding-dead-code) — Article
  **NeKI brief:** Examines How Duolingo deleted 1% of their code using this Open Source tool in the context of Apple-platform engineering. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Launch Booster](https://blog.sentry.io/open-source-tool-speed-up-ios-app-launch) — Article
  **NeKI brief:** Examines Speed up your launch times with this Open Source tool in the context of Performance. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [6 Mistakes That Slow Down Mobile Feature Development](https://www.mobilesystemdesign.com/blog/six-feature-development-mistakes) — Article · Topics: AI Development
  **NeKI brief:** Presents 6 Mistakes That Slow Down Mobile Feature Development, with practical context for Apple-platform developers evaluating the technique, workflow, or engineering decision described on the page.

## [Issue 279](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-279)

- Published: `2025-07-08T13:08:44.000Z`

**Topics:** App Distribution & Store Operations · Concurrency · Developer Community & Business · Liquid Glass · Swift · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · Paywalls Made Easy – Superwall · Vibe coding in Xcode 26: is it good?

**Selected links:**
- [ImplementedSE-0464UTF8Span: Safe UTF-8 Processing Over Contiguous Bytes](https://github.com/apple/swift-evolution/blob/main/proposals/0464-utf8span-safe-utf8-processing.md) — Source repository · Topics: Developer Tools · Liquid Glass · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0464UTF8Span: Safe UTF-8 Processing Over Contiguous Bytes. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Vibe coding in Xcode 26: is it good?](https://www.swiftwithvincent.com/blog/vibe-coding-in-xcode-26-is-it-good) — Article · Topics: Swift · Xcode
  **NeKI brief:** Presents Vibe coding in Xcode 26: is it good?, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Active ReviewSE-0487Extensible enums](https://github.com/apple/swift-evolution/blob/main/proposals/0487-extensible-enums.md) — Source repository · Topics: Developer Tools · Liquid Glass · Swift
  **NeKI brief:** Records AcceptedSE-0487Nonexhaustive enums, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Active ReviewSE-0488Apply the extracting() slicing pattern more widely](https://github.com/apple/swift-evolution/blob/main/proposals/0488-extracting.md) — Source repository · Topics: Developer Tools · Liquid Glass · Swift
  **NeKI brief:** Records ImplementedSE-0488Apply the extracting() slicing pattern more widely, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [The Anatomy of a LiquidGlass Button in iOS 26](https://www.natashatherobot.com/p/liquidglass-button-ios-26) — Article · Topics: Liquid Glass
  **NeKI brief:** Presents The Anatomy of a LiquidGlass Button in iOS 26, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Schedule a countdown timer with AlarmKit](https://nilcoalescing.com/blog/CountdownTimerWithAlarmKit) — Article · Topics: Apple Platform Ecosystem
  **NeKI brief:** Schedules a countdown through AlarmKit rather than a foreground-only timer. Use it when an app needs a system-managed alert that survives normal lifecycle interruptions.
- [Finding my Way](https://david-smith.org/blog/2025/07/02/new-maps) — Article · Topics: Maps & Location
  **NeKI brief:** Discusses Finding my Way, extracting concrete engineering practices and trade-offs that Apple-platform developers can apply when evaluating this workflow.
- [Designing custom UI with Liquid Glass on iOS 26](https://www.donnywals.com/designing-custom-ui-with-liquid-glass-on-ios-26) — Article · Topics: Liquid Glass
  **NeKI brief:** Explores custom Liquid Glass composition on iOS 26, including grouping and material boundaries. Useful for matching the system visual language without treating every translucent surface as interchangeable.

## [Issue 278](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-278)

- Published: `2025-07-01T14:14:53.000Z`

**Topics:** App Distribution & Store Operations · Concurrency · Developer Community & Business · Personal Essays · Swift · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · Sparkle: Distribution apps in- and out of the Mac App Store · Observability that's custom-built for mobile

**Selected links:**
- [ImplementedSE-0472Starting tasks synchronously from caller context](https://github.com/apple/swift-evolution/blob/main/proposals/0472-task-start-synchronously-on-caller-context.md) — Source repository · Topics: Developer Community & Business · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0472Starting tasks synchronously from caller context. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [RocketSim's documentation](https://docs.rocketsim.app/features/hzQMSrSga7BGWvxdNVdwYs/simulator-camera-support/58tQ5jvevLNSnyUEA7VgAv) — Article · Topics: Graphics, Media & Games · Objective-C & Cocoa · Xcode
  **NeKI brief:** Presents RocketSim's documentation, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [A Swift Developer’s Guide to Prompt Engineering with Apple’s](https://www.natashatherobot.com/p/swift-prompt-engineering-apples-foundationmodels) — Article · Topics: Foundation & Data Formats · Swift
  **NeKI brief:** Explains A Swift Developer’s Guide to Prompt Engineering with Apple’s, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Why Liquid Glass Is Making Developers Rethink Flutter](https://ohmyswift.com/blog/2025/06/28/why-liquid-glass-is-making-developers-rethink-flutter) — Article · Topics: Cross-Platform & Web · Liquid Glass · Swift
  **NeKI brief:** Explains Why Liquid Glass Is Making Developers Rethink Flutter, connecting the underlying Apple-platform mechanism to implementation choices and practical trade-offs that Swift developers can evaluate.
- [Understanding and Improving SwiftUI Performance](https://medium.com/airbnb-engineering/understanding-and-improving-swiftui-performance-37b77ac61896) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Explains Understanding and Improving SwiftUI Performance, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [AcceptedSE-0474Yielding accessors](https://github.com/apple/swift-evolution/blob/main/proposals/0474-yielding-accessors.md) — Source repository · Topics: Developer Community & Business · Developer Tools · Swift
  **NeKI brief:** Records AcceptedSE-0474Yielding accessors, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Diagnostics](https://github.com/wetransfer/diagnostics) — Source repository · Topics: Concurrency · Developer Community & Business · Swift
  **NeKI brief:** Points to Diagnostics, an open-source implementation or issue with concrete code and discussion that can inform Apple-platform development decisions.
- [NIOFileSystem](https://github.com/apple/swift-nio/tree/main/Sources/NIOFileSystem) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Points to NIOFileSystem, an open-source implementation or issue with concrete code and discussion that can inform Apple-platform development decisions.
- [How I lost £25,000 running a successful conference](https://www.timc.dev/posts/the-cost-of-running-a-conference) — Article · Topics: Developer Community & Business · Personal Essays
  **NeKI brief:** Breaks down the financial outcome of running a successful developer conference, including the gap between attendance and actual event costs. It is useful as an operational case study for community-event budgeting, not as iOS implementation guidance.
- [this thread](https://forums.swift.org/t/task-safe-way-to-write-a-file-asynchronously/54639) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Discusses this thread, extracting concrete engineering practices and trade-offs that Apple-platform developers can apply when evaluating this workflow.
- [Considerations for New iOS Versions](https://david-smith.org/blog/2025/06/27/requiring-26) — Article
  **NeKI brief:** Explains Considerations for New iOS Versions, focusing on the underlying Apple-platform behavior and the implementation trade-offs relevant to production code.

## [Issue 277](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-277)

- Published: `2025-06-24T14:09:23.000Z`

**Topics:** App Distribution & Store Operations · Graphics, Media & Games · Liquid Glass · Macros & Metaprogramming · Swift · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · #Playground Macro: Running Code Snippets in Xcode’s canvas · Paywalls Made Easy – Superwall

**Selected links:**
- [Adding Icon Composer icons to Xcode](https://useyourloaf.com/blog/adding-icon-composer-icons-to-xcode) — Article · Topics: Apple Platform Ecosystem · Xcode
  **NeKI brief:** Shows importing Icon Composer output into Xcode asset workflows. Use it when app-icon variants need a repeatable handoff from design composition to a buildable asset catalog.
- [Reverse-Engineering Xcode's Coding Intelligence prompt](https://peterfriese.dev/blog/2025/reveng-xcode-coding-intelligence) — Article · Topics: AI Development · Xcode
  **NeKI brief:** Inspects Xcode's Coding Intelligence prompt to show how project context and instructions shape generated code. The reverse-engineering perspective helps teams reason about agent inputs and reproducibility while avoiding assumptions about undocumented internals.
- [Exploring a new visual language: Liquid Glass](https://www.createwithswift.com/exploring-a-new-visual-language-liquid-glass) — Article · Topics: Liquid Glass · Swift
  **NeKI brief:** Explores Liquid Glass as a new Apple visual language. Use it when evaluating material, hierarchy, and interaction changes before adapting an existing interface to the system design.
- [ImplementedSE-0486Migration tooling for Swift features](https://github.com/apple/swift-evolution/blob/main/proposals/0486-adoption-tooling-for-swift-features.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Records ImplementedSE-0486Migration tooling for Swift features, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [read all about it inside the documentation](https://docs.rocketsim.app/features/hzQMSrSga7BGWvxdNVdwYs/simulator-camera-support/58tQ5jvevLNSnyUEA7VgAv) — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **NeKI brief:** Presents RocketSim's documentation, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [FaultOrdering - Open source tool to speed up iOS app launch](https://blog.sentry.io/open-source-tool-speed-up-ios-app-launch) — Article
  **NeKI brief:** Examines Speed up your launch times with this Open Source tool in the context of Performance. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [part of Sentry](https://blog.sentry.io/emerge-tools-is-now-a-part-of-sentry) — Article
  **NeKI brief:** Summarises Sentry announced that they were acquiring Emerge Tools for Performance. Use it to identify the relevant changes and follow its primary links before relying on version-sensitive details.

## [Issue 276](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-276)

- Published: `2025-06-17T14:10:56.000Z`

**Topics:** Apple Platform Ecosystem · Concurrency · Developer Community & Business · Graphics, Media & Games · Swift · UIKit

**Sections:** SwiftLee Weekly by Antoine van der Lee · Default Actor Isolation in Swift 6.2 · Want to Stay Ahead in Mobile CI/CD?

**Selected links:**
- [WWDC 2025: What's new for the Apple community?](https://www.createwithswift.com/wwdc-2025-whats-new-for-the-apple-community) — Article · Topics: Apple Platform Ecosystem · Developer Community & Business · Swift
  **NeKI brief:** Surveys WWDC 2025 changes across Liquid Glass, Icon Composer, accessibility, Apple Intelligence, Xcode, Swift, and SwiftUI. Use the cross-topic index to identify follow-up implementation areas, then consult authoritative session documentation.
- [Free Episode: SwiftData versus SQL Query Builder](https://www.pointfree.co/blog/posts/174-free-episode-swiftdata-versus-sql-query-builder) — Article · Topics: Apple Platform Ecosystem · Swift · SwiftData
  **NeKI brief:** Compares SwiftData with a SQL query-builder approach. Use it when choosing between declarative model persistence and explicit relational queries, migrations, and database-level control.
- [ImplementedSE-0456Add `Span`-providing Properties to Standard Library Types](https://github.com/apple/swift-evolution/blob/main/proposals/0456-stdlib-span-properties.md) — Source repository · Topics: Developer Tools · Swift · UIKit
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0456Add `Span`-providing Properties to Standard Library Types. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ImplementedSE-0465Standard Library Primitives for Nonescapable Types](https://github.com/apple/swift-evolution/blob/main/proposals/0465-nonescapable-stdlib-primitives.md) — Source repository · Topics: Developer Tools · Swift · UIKit
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0465Standard Library Primitives for Nonescapable Types. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ImplementedSE-0467MutableSpan and MutableRawSpan: delegate mutations of contiguous memory](https://github.com/apple/swift-evolution/blob/main/proposals/0467-MutableSpan.md) — Source repository · Topics: Developer Tools · Swift · UIKit
  **NeKI brief:** Records ImplementedSE-0467MutableSpan and MutableRawSpan: delegate mutations of contiguous memory, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [ImplementedSE-0468`Hashable` conformance for `Async(Throwing)Stream.Continuation`](https://github.com/apple/swift-evolution/blob/main/proposals/0468-async-stream-continuation-hashable-conformance.md) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0468`Hashable` conformance for `Async(Throwing)Stream.Continuation`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [AcceptedSE-0485OutputSpan: delegate initialization of contiguous memory](https://github.com/apple/swift-evolution/blob/main/proposals/0485-outputspan.md) — Source repository · Topics: Developer Tools · Swift · UIKit
  **NeKI brief:** Records ImplementedSE-0485OutputSpan: delegate initialization of contiguous memory, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [iOS 26: Notable UIKit Additions](https://www.swiftjectivec.com/ios-26-notable-uikit-additions) — Article · Topics: Swift · UIKit
  **NeKI brief:** Surveys notable UIKit additions in iOS 26 and their practical use cases. Useful as a versioned API index when maintaining UIKit screens alongside SwiftUI migration work.
- [macOS Tahoe forces all app icons into iOS squircles](https://lapcatsoftware.com/articles/2025/6/2.html) — Article · Topics: Cross-Platform & Web
  **NeKI brief:** Explains macOS Tahoe forces all app icons into iOS squircles, focusing on the underlying Apple-platform behavior and the implementation trade-offs relevant to production code.

## [Issue 275](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-275)

- Published: `2025-06-12T15:03:23.000Z`

**Topics:** Apple Platform Ecosystem · Concurrency · Developer Community & Business · Swift · SwiftUI · UIKit

**Sections:** SwiftLee Weekly by Antoine van der Lee · @concurrent explained with code examples · Capture, Debug, and Optimize Your HTTP(s) Traffic in One App

**Selected links:**
- [Automatic Observation Tracking in UIKit and AppKit: The Feature Apple Forgot to Mention | Peter Steinberger](https://steipete.me/posts/2025/automatic-observation-tracking-uikit-appkit) — Article · Topics: Apple Platform Ecosystem · macOS & AppKit · UIKit
  **NeKI brief:** Explores automatic Observation tracking in UIKit and AppKit. Use it when imperative views should react to observable model reads without manually registering broad notifications.
- [Developer experience wins from WWDC25](https://tuist.dev/blog/2025/06/10/wwdc) — Article · Topics: Apple Platform Ecosystem · Macros & Metaprogramming · Testing
  **NeKI brief:** Explains Developer experience wins from WWDC25, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Introducing PickerKit for SwiftUI](https://danielsaidi.com/blog/2025/06/10/introducing-pickerkit-for-swiftui) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Presents Introducing PickerKit for SwiftUI, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Crafting Liquid Glass app icons with Icon Composer](https://www.createwithswift.com/crafting-liquid-glass-app-icons-with-icon-composer) — Article · Topics: Liquid Glass · Swift
  **NeKI brief:** Walks through creating Liquid Glass-compatible app icons with Icon Composer. Use it when adapting assets for the new system treatment and validating how layers, materials, and icon output render in context.
- [A (Re-)Introduction to ExtensionKit](https://www.massicotte.org/extensionkit-intro) — Article
  **NeKI brief:** Explains A (Re-)Introduction to ExtensionKit, connecting the underlying Apple-platform mechanism to implementation choices and practical trade-offs that Swift developers can evaluate.

## [Issue 274](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-274)

- Published: `2025-06-03T14:11:29.000Z`

**Topics:** Architecture · CI/CD & Automation · Macros & Metaprogramming · Objective-C & Cocoa · Swift · SwiftUI

**Sections:** SwiftLee Weekly by Antoine van der Lee · Unique values in Swift: Removing duplicates from an array · Fastlane alternative - Codemagic CLI tools

**Selected links:**
- [Fastlane alternative - Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository · Topics: CI/CD & Automation · Developer Tools
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [Tips and tricks for when using SwiftUI’s ViewBuilder](https://www.swiftbysundell.com/articles/swiftui-viewbuilder-tips-and-tricks) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Collects ViewBuilder techniques for conditional composition, custom containers, and readable APIs. Useful when designing result-builder-based components without hiding state or type constraints.
- [Microapps architecture in Swift. Scaling.](https://swiftwithmajid.com/2025/05/27/microapps-architecture-in-swift-scaling) — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **NeKI brief:** Discusses scaling a Swift microapps architecture through modular feature boundaries. Use it when a growing app needs independently developed flows without turning every module dependency into global coupling.
- [Automatic SwiftUI View Tracing with Swift Macros](https://medium.com/@alexandercohen/how-we-built-a-swift-macro-that-automatically-wraps-any-swiftui-view-no-more-manual-f5761376f923) — Article · Topics: Macros & Metaprogramming · Swift · SwiftUI
  **NeKI brief:** Presents Automatic SwiftUI View Tracing with Swift Macros, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Accessorise Your Context Menu Interactions](https://sebvidal.com/blog/accessorise-your-context-menu-interactions) — Article
  **NeKI brief:** Seb shows how to use private API to add accessory views to your context menu interactions. However, this can result in the app being rejected when submitted to the App Store.
- [Survey finds your mobile engineers lose 5 hours per release](https://www.runway.team/whitepapers/2025-state-of-mobile-release-management-report) — Article · Topics: Developer Career & Practice
  **NeKI brief:** Discusses Survey finds your mobile engineers lose 5 hours per release, providing concrete engineering context that Apple-platform developers can use when evaluating the referenced workflow.

## [Issue 273](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-273)

- Published: `2025-05-27T14:08:19.000Z`

**Topics:** App Distribution & Store Operations · Developer Community & Business · Developer Tools · Graphics, Media & Games · Swift · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · Billing Grace Period Explained: How It Works and Why It Matters · Tired of chaotic mobile releases?

**Selected links:**
- [W.W.D.C. 2025: The Pregame Quiz](https://www.swiftjectivec.com/wwdc-2025-the-pregame-quiz) — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Swift
  **NeKI brief:** Presents W.W.D.C. 2025: The Pregame Quiz, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Returned For RevisionSE-0480Warning Control Settings for SwiftPM](https://github.com/apple/swift-evolution/blob/main/proposals/0480-swiftpm-warning-control.md) — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0480Warning Control Settings for SwiftPM. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [AcceptedSE-0482Binary Static Library Dependencies](https://github.com/apple/swift-evolution/blob/main/proposals/0482-swiftpm-static-library-binary-target-non-apple-platforms.md) — Source repository · Topics: Dependency Injection · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0482Binary Static Library Dependencies. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [add it to the GitHub issue](https://github.com/AvdLee/RocketSimApp/issues/607) — Source repository · Topics: Developer Tools · Graphics, Media & Games · Xcode
  **NeKI brief:** Points to add it to the GitHub issue, an open-source implementation or issue with concrete code and discussion that can inform Apple-platform development decisions.
- [StoreKit Examples - GitHub Repo](https://github.com/jordibruin/StoreKit-Examples) — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **NeKI brief:** Points to StoreKit Examples - GitHub Repo, an open-source implementation or issue with concrete code and discussion that can inform Apple-platform development decisions.
- [Building a business around Tuist](https://tuist.dev/blog/2025/05/20/business-around-tuist) — Article · Topics: Developer Community & Business · Security & Privacy
  **NeKI brief:** Discusses Building a business around Tuist, extracting concrete product or engineering practices that help independent Apple-platform developers make informed delivery decisions.
- [AcceptedSE-0472Starting tasks synchronously from caller context](https://github.com/apple/swift-evolution/blob/main/proposals/0472-task-start-synchronously-on-caller-context.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0472Starting tasks synchronously from caller context. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0485OutputSpan: delegate initialization of contiguous memory](https://github.com/apple/swift-evolution/blob/main/proposals/0485-outputspan.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Records ImplementedSE-0485OutputSpan: delegate initialization of contiguous memory, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Active ReviewSE-0486Migration tooling for Swift features](https://github.com/apple/swift-evolution/blob/main/proposals/0486-adoption-tooling-for-swift-features.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Records ImplementedSE-0486Migration tooling for Swift features, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Build an iOS app faster than ever with xtool](https://dimillian.medium.com/build-an-ios-app-faster-than-ever-with-xtool-d6dd7780c5f7) — Article · Topics: Xcode
  **NeKI brief:** Presents Build an iOS app faster than ever with xtool, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.

## [Issue 272](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-272)

- Published: `2025-05-20T14:12:58.000Z`

**Topics:** Concurrency · Developer Community & Business · Observation & State Management · Swift · SwiftUI · Testing

**Sections:** SwiftLee Weekly by Antoine van der Lee · Institutional Purchases: Understanding and Detecting · Fastlane alternative - Codemagic CLI tools

**Selected links:**
- [Demystifying SwiftUI’s .ignoredByLayout() — How to Apply Geometry Effects Without Breaking Your Layout](https://fatbobman.com/en/posts/demystifying-swiftuis-ignoredbylayout) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Explains how ignoredByLayout removes a view from layout participation while retaining rendering or interaction implications. Useful for distinguishing hidden geometry from conditional rendering when composing overlays and transitions.
- [Testing Remote Push Notifications with iOS Simulators](https://www.tiagohenriques.dev/blog/testing-push-notifications-ios-simulators) — Article · Topics: App Services & Extensions · Testing · Xcode
  **NeKI brief:** Explains Testing Remote Push Notifications with iOS Simulators, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [SE-475: Transactional Observation of Values](https://github.com/swiftlang/swift-evolution/blob/main/proposals/0475-observed.md) — Source repository · Topics: Combine & Reactive Programming · Developer Tools · Swift
  **NeKI brief:** Provides the public source repository for SE-0475. Inspect its implementation, examples, and issue history to evaluate integration boundaries and maintenance trade-offs before depending on it in an Apple-platform project.
- [Fastlane alternative - Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository · Topics: CI/CD & Automation · Developer Tools
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [RocketSim Meetup at CommunityKit](https://lu.ma/g4m3q37q) — Article · Topics: Apple Platform Ecosystem · Developer Community & Business · Swift
  **NeKI brief:** Describes RocketSim Meetup at CommunityKit, providing the event-specific information needed to identify its Apple-platform community context.
- [AcceptedSE-0471Improved Custom SerialExecutor isolation checking for Concurrency Runtime](https://github.com/apple/swift-evolution/blob/main/proposals/0471-SerialExecutor-isIsolated.md) — Source repository · Topics: App Services & Extensions · Swift · Testing
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0471Improved Custom SerialExecutor isolation checking for Concurrency Runtime. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [AcceptedSE-0481`weak let`](https://github.com/apple/swift-evolution/blob/main/proposals/0481-weak-let.md) — Source repository · Topics: App Services & Extensions · Swift · Testing
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0481`weak let`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Apple's open-sourced Async Algorithms framework](https://github.com/apple/swift-async-algorithms) — Source repository · Topics: Combine & Reactive Programming · Concurrency · Swift
  **NeKI brief:** swift-async-algorithms adds reusable asynchronous sequence operators and utilities for Swift concurrency. Use it when async/await code needs throttling, merging, buffering, or other stream composition without reintroducing a full Combine pipeline.
- [AsyncExtensions](https://github.com/sideeffect-io/AsyncExtensions) — Source repository · Topics: Combine & Reactive Programming · Concurrency · Developer Tools
  **NeKI brief:** Points to AsyncExtensions, an open-source implementation or issue with concrete code and discussion that can inform Apple-platform development decisions.
- [Optimized mathematical computations in Swift](https://swiftwithmajid.com/2025/05/13/optimized-mathematical-computations-in-swift) — Article · Topics: Swift
  **NeKI brief:** Explores optimization techniques for mathematical work in Swift. Use it when profiling identifies numeric hot paths and algorithm, memory layout, or vectorization decisions need measured comparison.
- [Default isolation with Swift 6.2](https://www.massicotte.org/default-isolation-swift-6_2) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains Default isolation with Swift 6.2, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [SwiftUI Picker With Optional Selection](https://useyourloaf.com/blog/swiftui-picker-with-optional-selection) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows binding a SwiftUI Picker to an optional selection. Use it when no current choice is a valid state and placeholder, tag, and model values must remain type-consistent.

## [Issue 271](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-271)

- Published: `2025-05-13T09:07:48.000Z`

**Topics:** AI Development · Concurrency · Developer Community & Business · Swift · SwiftUI · Testing

**Sections:** SwiftLee Weekly by Antoine van der Lee · Universal Links implementation on iOS · Is Your Mobile CI/CD Pipeline Secure Enough?

**Selected links:**
- [Concurrency-Safe Testing in Swift 6.1 with @TaskLocal and Test Scoping](https://www.mobiledevdiary.com/posts/concurency-safe-testing-in-swift-6-1) — Article · Topics: Concurrency · Swift · Testing
  **NeKI brief:** Explains Concurrency-Safe Testing in Swift 6.1 with @TaskLocal and Test Scoping, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [ImplementedSE-0461Run nonisolated async functions on the caller's actor by default](https://github.com/apple/swift-evolution/blob/main/proposals/0461-async-function-isolation.md) — Source repository · Topics: Concurrency · Swift · Testing
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0461Run nonisolated async functions on the caller's actor by default. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Start a free 14-day trial ->](https://teams.rocketsim.app/signup/trial) — Tutorial · Topics: Concurrency · Developer Community & Business · Swift
  **NeKI brief:** Introduces Start a free 14-day trial -> as a developer resource or service relevant to Swift and Apple-platform work. Use it to assess the stated workflow or offering, checking scope, pricing, access requirements, and technical fit before relying on it.
- [Diagnostics](https://github.com/WeTransfer/Diagnostics) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Points to Diagnostics, an open-source implementation or issue with concrete code and discussion that can inform Apple-platform development decisions.
- [Can You use PreferenceKeys for Testing SwiftUI Views](https://www.swiftyplace.com/blog/swiftui-testing-with-preferencekeys) — Article · Topics: Swift · SwiftUI · Testing
  **NeKI brief:** Investigates whether PreferenceKeys can expose SwiftUI layout information to tests. Useful for understanding testability limits and deciding when a semantic UI assertion is preferable to measuring implementation details.
- [Active ReviewSE-0484Allow Additional Arguments to `@dynamicMemberLookup` Subscripts](https://github.com/apple/swift-evolution/blob/main/proposals/0484-allow-additional-args-to-dynamicmemberlookup-subscripts.md) — Source repository · Topics: Concurrency · Swift · Testing
  **NeKI brief:** Records Active ReviewSE-0484Allow Additional Arguments to `@dynamicMemberLookup` Subscripts, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Using Model Context Protocol in iOS apps](https://www.artemnovichkov.com/blog/using-model-context-protocol-in-ios-apps) — Article · Topics: AI Development
  **NeKI brief:** Artem continues exploring the Model Context Protocol (MCP) to facilitate interaction between AI models and external tools or data sources, this time showing how to access HealthKit data through the Claude API.
- [Is Your Mobile CI/CD Pipeline Secure Enough?](https://appcircle.io/blog/mobile-ci-cd-security-top-5-best-practices) — Article · Topics: CI/CD & Automation · Security & Privacy
  **NeKI brief:** Examines How Secure Is Your Mobile CI/CD Pipeline? in the context of CI/CD & Automation and Security & Privacy. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [What's new in Swift 6.2?](https://www.hackingwithswift.com/articles/277/whats-new-in-swift-6-2) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Summarizes Swift 6.2 additions and concurrency ergonomics, highlighting practical changes for existing projects. Useful for planning an incremental toolchain update and targeted experiments.

## [Issue 270](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-270)

- Published: `2025-05-06T14:02:39.000Z`

**Topics:** App Distribution & Store Operations · App Services & Extensions · CI/CD & Automation · Dependency Injection · Swift · Testing

**Sections:** SwiftLee Weekly by Antoine van der Lee · Testing push notifications on the iOS simulator · Are You Overlooking Mobile CI/CD Security?

**Selected links:**
- [Adding dependencies to binary Swift packages](https://danielsaidi.com/blog/2025/05/02/adding-dependencies-to-binary-swift-packages) — Article · Topics: Dependency Injection · Swift · Swift Package Manager
  **NeKI brief:** Presents Adding dependencies to binary Swift packages, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Active ReviewSE-0482Binary Static Library Dependencies](https://github.com/apple/swift-evolution/blob/main/proposals/0482-swiftpm-static-library-binary-target-non-apple-platforms.md) — Source repository · Topics: Dependency Injection · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0482Binary Static Library Dependencies. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Are You Overlooking Mobile CI/CD Security?](https://appcircle.io/whitepapers/enhancing-mobile-ci-cd-security) — Article · Topics: CI/CD & Automation · Security & Privacy
  **NeKI brief:** Discusses Are You Overlooking Mobile CI/CD Security?, extracting concrete engineering practices and trade-offs that Apple-platform developers can apply when evaluating this workflow.
- [AcceptedSE-0476Controlling the ABI of a function, initializer, property, or subscript](https://github.com/apple/swift-evolution/blob/main/proposals/0476-abi-attr.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0476Controlling the ABI of a function, initializer, property, or subscript. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [AcceptedSE-0477Default Value in String Interpolations](https://github.com/apple/swift-evolution/blob/main/proposals/0477-default-interpolation-values.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Records ImplementedSE-0477Default Value in String Interpolations, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Active ReviewSE-0481`weak let`](https://github.com/apple/swift-evolution/blob/main/proposals/0481-weak-let.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0481`weak let`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0483`InlineArray` Literal Syntax](https://github.com/apple/swift-evolution/blob/main/proposals/0483-inline-array-sugar.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Records ImplementedSE-0483`InlineArray` Type Sugar, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Building Better Apps with RocketSim - Special Guest Antoine van der Lee!](https://www.youtube.com/live/4MtostISJTY?feature=shared) — Video
  **NeKI brief:** Records a live RocketSim session with Antoine van der Lee demonstrating simulator workflows, product features, and practical tips while answering audience questions. Useful for evaluating the tool through an unscripted end-to-end walkthrough.
- [Applying to, prepping for, and speaking at Deep Dish Swift](https://jacobzivandesign.com/technology/preparing-my-first-talk) — Article · Topics: Swift
  **NeKI brief:** Presents Applying to, prepping for, and speaking at Deep Dish Swift, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Dependency container on top of task local values in Swift](https://swiftwithmajid.com/2025/04/30/dependency-container-on-top-of-task-local-values-in-swift) — Article · Topics: Swift
  **NeKI brief:** Builds a dependency container using TaskLocal values. Use it when async call chains need contextual dependencies without passing parameters everywhere, while guarding scope and inheritance carefully.
- [Three Indie Marketing Tips from my Deep Dish 2025 Talk](https://www.swiftjectivec.com/three-key-takeaways-from-my-deep-dish-swift-talk-on-indie-marketing) — Article · Topics: Swift
  **NeKI brief:** Jordan shares the three tips for effective marketing strategies for Indie app developers from his recent Deep Dish Swift 2025 talk.

## [Issue 269](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-269)

- Published: `2025-04-29T14:18:33.000Z`

**Topics:** App Distribution & Store Operations · Developer Career & Practice · Developer Community & Business · Performance · Swift · SwiftUI

**Sections:** SwiftLee Weekly by Antoine van der Lee · SwiftUI ForEach Explained with Code Examples · What's the cost of not prioritizing mobile release management?

**Selected links:**
- [ImplementedSE-0463Import Objective-C completion handler parameters as `@Sendable`](https://github.com/apple/swift-evolution/blob/main/proposals/0463-sendable-completion-handlers.md) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0463Import Objective-C completion handler parameters as `@Sendable`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ImplementedSE-0466Control default actor isolation inference](https://github.com/apple/swift-evolution/blob/main/proposals/0466-control-default-actor-isolation.md) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0466Control default actor isolation inference. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ImplementedSE-0457Expose attosecond representation of `Duration`](https://github.com/apple/swift-evolution/blob/main/proposals/0457-duration-attosecond-represenation.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0457Expose attosecond representation of `Duration`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ImplementedSE-0462Task Priority Escalation APIs](https://github.com/apple/swift-evolution/blob/main/proposals/0462-task-priority-escalation-apis.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0462Task Priority Escalation APIs. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ImplementedSE-0469Task Naming](https://github.com/apple/swift-evolution/blob/main/proposals/0469-task-names.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Records ImplementedSE-0469Task Naming, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Drawing symbols with Canvas](https://www.createwithswift.com/drawing-symbols-with-canvas) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Draws SF Symbols with SwiftUI Canvas. Use it when symbol rendering needs custom transforms, compositing, or animation while retaining vector fidelity and system icon semantics.
- [Active ReviewSE-0480Warning Control Settings for SwiftPM](https://github.com/apple/swift-evolution/blob/main/proposals/0480-swiftpm-warning-control.md) — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0480Warning Control Settings for SwiftPM. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0479Method and Initializer Key Paths](https://github.com/apple/swift-evolution/blob/main/proposals/0479-method-and-initializer-keypaths.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Records Returned For RevisionSE-0479Method and Initializer Key Paths, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [How a Single Line Of Code Could Brick Your iPhone](https://rambo.codes/posts/2025-04-24-how-a-single-line-of-code-could-brick-your-iphone) — Article
  **NeKI brief:** Presents How a Single Line Of Code Could Brick Your iPhone, with practical context for Apple-platform developers evaluating the technique, workflow, or engineering decision described on the page.
- [What's the cost of not prioritizing mobile release management?](https://www.runway.team/webinar/the-roi-of-mobile-release-management) — Article · Topics: Developer Career & Practice
  **NeKI brief:** Discusses What's the cost of not prioritizing mobile release management?, providing concrete engineering context that Apple-platform developers can use when evaluating the referenced workflow.

## [Issue 268](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-268)

- Published: `2025-04-22T13:40:18.000Z`

**Topics:** AI Development · Concurrency · Cross-Platform & Web · Developer Career & Practice · Developer Community & Business · Swift

**Sections:** SwiftLee Weekly by Antoine van der Lee · Swift 6.2: A first look at how it’s changing Concurrency · Transform Your Career with the iOS Lead Essentials — Limited Offer

**Selected links:**
- [swiftlang/swift-subprocess: Subprocess is a cross-platform package for spawning processes in Swift.](https://github.com/swiftlang/swift-subprocess) — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **NeKI brief:** swift-subprocess modernizes launching and interacting with child processes through Swift concurrency. Use it for scripts and tools that need structured stdin, stdout, cancellation, and exit-status handling beyond Foundation's older Process API.
- [ImplementedSE-0470Global-actor isolated conformances](https://github.com/apple/swift-evolution/blob/main/proposals/0470-isolated-conformances.md) — Source repository · Topics: Concurrency · Cross-Platform & Web · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0470Global-actor isolated conformances. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [a starting point in the repository's readme](https://github.com/swiftlang/swift/tree/release/6.2?tab=readme-ov-file) — Source repository · Topics: Developer Tools · Swift · Xcode
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for a starting point in the repository's readme. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Creating MCP Servers in Swift](https://www.artemnovichkov.com/blog/creating-mcp-servers-in-swift) — Article · Topics: AI Development · Swift
  **NeKI brief:** Artem explains how to create an MCP server (Model Context Protocol) that can be used to connect LLMs model with the tools that we use everyday using the Swift programming language.
- [Using Swift’s defer keyword within async and throwing contexts](https://www.swiftbysundell.com/articles/using-defer-within-async-and-throwing-contexts) — Article · Topics: Concurrency · Developer Career & Practice · Swift
  **NeKI brief:** Explains defer cleanup across async suspension and thrown errors. Use it when file handles, transactions, or temporary state must release reliably without duplicating cleanup paths.
- [Returned For RevisionSE-0472Starting tasks synchronously from caller context](https://github.com/apple/swift-evolution/blob/main/proposals/0472-task-start-synchronously-on-caller-context.md) — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0472Starting tasks synchronously from caller context. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0477Default Value in String Interpolations](https://github.com/apple/swift-evolution/blob/main/proposals/0477-default-interpolation-values.md) — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **NeKI brief:** Records ImplementedSE-0477Default Value in String Interpolations, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [release/6.2 branch](https://github.com/swiftlang/swift/tree/release/6.2) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Points to release/6.2 branch, an open-source implementation or issue with concrete code and discussion that can inform Apple-platform development decisions.
- [UIApplication delegate deprecation coming in iOS 19 SDK](https://lapcatsoftware.com/articles/2025/4/5.html) — Article · Topics: Cross-Platform & Web
  **NeKI brief:** Discusses UIApplication delegate deprecation in the iOS 19 SDK. Useful for planning lifecycle migrations and identifying compatibility boundaries before removing established delegate-based integration.
- [Advice to My Younger Self](https://www.mobilesystemdesign.com/blog/advice-to-younger-self) — Article
  **NeKI brief:** Presents Advice to My Younger Self, with practical context for Apple-platform developers evaluating the technique, workflow, or engineering decision described on the page.

## [Issue 267](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-267)

- Published: `2025-04-15T13:04:41.000Z`

**Topics:** App Distribution & Store Operations · Combine & Reactive Programming · Concurrency · Developer Community & Business · Swift · SwiftUI

**Sections:** SwiftLee Weekly by Antoine van der Lee · Swift Reduce: Combining elements into a single value · Codemagic makes Apple M2 machines available, even on the free tier!

**Selected links:**
- [AcceptedSE-0470Global-actor isolated conformances](https://github.com/apple/swift-evolution/blob/main/proposals/0470-isolated-conformances.md) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0470Global-actor isolated conformances. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Create flexible interfaces in SwiftUI](https://www.createwithswift.com/create-flexible-interfaces-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds flexible SwiftUI interfaces that adapt to available space and content. Use it when a layout must remain usable across devices without branching into separate fixed-size view trees.
- [AcceptedSE-0464UTF8Span: Safe UTF-8 Processing Over Contiguous Bytes](https://github.com/apple/swift-evolution/blob/main/proposals/0464-utf8span-safe-utf8-processing.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0464UTF8Span: Safe UTF-8 Processing Over Contiguous Bytes. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [AcceptedSE-0473Clock Epochs](https://github.com/apple/swift-evolution/blob/main/proposals/0473-clock-epochs.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Records AcceptedSE-0473Clock Epochs, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Active ReviewSE-0475Transactional Observation of Values](https://github.com/apple/swift-evolution/blob/main/proposals/0475-observed.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Records Active ReviewSE-0475Transactional Observation of Values, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Active ReviewSE-0476Controlling the ABI of a function, initializer, property, or subscript](https://github.com/apple/swift-evolution/blob/main/proposals/0476-abi-attr.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0476Controlling the ABI of a function, initializer, property, or subscript. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Using NavigationPath with TabView in SwiftUI](https://tanaschita.com/swiftui-navigation-path-with-tabview) — Article · Topics: Navigation & Deep Linking · Swift · SwiftUI
  **NeKI brief:** Uses NavigationPath with TabView to preserve typed navigation state per tab. Use it when deep links and tab switching must restore the correct nested destination.
- [How to inspect .ipa files and secure your iOS app from common mistakes](https://www.artemnovichkov.com/blog/how-to-inspect-ipa-files) — Article · Topics: Security & Privacy
  **NeKI brief:** In this original article, Artem provides a comprehensive guide on examining the contents of iOS application packages (.ipa files) and highlights common security pitfalls to avoid.
- [Supercharging SwiftUI Text with Dynamic Content Styling](https://danielsaidi.com/blog/2025/04/08/supercharging-swiftui-text-with-dynamic-content-styling) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents Supercharging SwiftUI Text with Dynamic Content Styling, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Building Better Apps with RocketSim - Special Guest Antoine van der Lee!](https://www.youtube.com/live/4MtostISJTY?feature=shared) — Video
  **NeKI brief:** Records a live RocketSim session with Antoine van der Lee demonstrating simulator workflows, product features, and practical tips while answering audience questions. Useful for evaluating the tool through an unscripted end-to-end walkthrough.

## [Issue 266](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-266)

- Published: `2025-04-08T14:10:02.000Z`

**Topics:** App Distribution & Store Operations · Concurrency · Developer Community & Business · Swift · SwiftUI · Testing

**Sections:** SwiftLee Weekly by Antoine van der Lee · SwiftUI Alert Guide + Code Examples · Transform Your Career with the iOS Lead Essentials — Limited Offer

**Selected links:**
- [Building a Business on Swift on the Server, Vapor & Open Source - Tim Condon](https://share.transistor.fm/s/941efac7) — Tutorial · Topics: Concurrency · Developer Community & Business · Swift
  **NeKI brief:** Discusses building a business around server-side Swift, Vapor, and open source in an interview format. Use it for ecosystem and product context rather than as API documentation or implementation guidance.
- [Building a Business on Swift on the Server, Vapor & Open Source](https://podcast.going-indie.com/episodes/building-a-business-on-swift-on-the-server-vapor-open-source-tim-condon) — Podcast · Topics: Developer Community & Business · Swift
  **NeKI brief:** Explains Building a Business on Swift on the Server, Vapor & Open Source, connecting the underlying Apple-platform mechanism to implementation choices and practical trade-offs that Swift developers can evaluate.
- [Say Goodbye to dismiss - A State-Driven Path to More Maintainable SwiftUI](https://fatbobman.com/en/posts/say-goodbye-to-dismiss) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Reframes SwiftUI dismissal as state-driven navigation. Use it when child views imperatively dismiss themselves and ownership of presentation state becomes hard to test or reason about.
- [Text concatenation vs Text interpolation in SwiftUI](https://nilcoalescing.com/blog/TextConcatenationVsTextInterpolationInSwiftUI) — Article · Topics: Localization · Swift · SwiftUI
  **NeKI brief:** Contrasts concatenating Text views with interpolating values into localized strings. Useful for preserving localization and formatting semantics when constructing styled SwiftUI copy.
- [AcceptedSE-0461Run nonisolated async functions on the caller's actor by default](https://github.com/apple/swift-evolution/blob/main/proposals/0461-async-function-isolation.md) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0461Run nonisolated async functions on the caller's actor by default. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [AcceptedSE-0468`Hashable` conformance for `Async(Throwing)Stream.Continuation`](https://github.com/apple/swift-evolution/blob/main/proposals/0468-async-stream-continuation-hashable-conformance.md) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0468`Hashable` conformance for `Async(Throwing)Stream.Continuation`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [New in Swift 6.1: Test Scoping Traits](https://www.pointfree.co/blog/posts/169-new-in-swift-6-1-test-scoping-traits) — Article · Topics: Swift · Testing
  **NeKI brief:** Explains Swift 6.1 Test Scoping Traits as a mechanism for controlling test context before and after execution. Use it when suite-level fixtures must remain isolated under concurrent Swift Testing runs.
- [The Great App That Nobody Knows About](https://www.swiftjectivec.com/a-great-app-that-no-one-knows-about) — Article · Topics: Swift
  **NeKI brief:** Explains The Great App That Nobody Knows About, focusing on the underlying Swift or Apple-platform mechanism and the implementation trade-offs relevant to production code.
- [Structuring Spacing for Scalable Mobile UIs](https://www.mobilesystemdesign.com/blog/design-system-spacing) — Article
  **NeKI brief:** Discusses spacing tokens and rhythm as foundations of a mobile design system. Useful for translating visual rules into reusable SwiftUI layout constants instead of accumulating screen-specific padding values.

## [Issue 265](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-265)

- Published: `2025-04-01T14:13:42.000Z`

**Topics:** App Distribution & Store Operations · Developer Community & Business · Objective-C & Cocoa · Swift · SwiftUI · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · SwiftUI Grid, LazyVGrid, LazyHGrid Explained with Code Examples · Discover the Top 10 Best Practices in App Distribution

**Selected links:**
- [Swiftdata Architecture Patterns And Practices](https://azamsharp.com/2025/03/28/swiftdata-architecture-patterns-and-practices.html) — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **NeKI brief:** Using a practical example, Mohammad shows how to build scalable SwiftData apps in SwiftUI, covering model structure, business logic, DTOs, testing, previews, CloudKit integration, and strategies to future-proof your architecture.
- [AcceptedSE-0466Control default actor isolation inference](https://github.com/apple/swift-evolution/blob/main/proposals/0466-control-default-actor-isolation.md) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0466Control default actor isolation inference. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [AcceptedSE-0467MutableSpan and MutableRawSpan: delegate mutations of contiguous memory](https://github.com/apple/swift-evolution/blob/main/proposals/0467-MutableSpan.md) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Records ImplementedSE-0467MutableSpan and MutableRawSpan: delegate mutations of contiguous memory, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Active ReviewSE-0471Improved Custom SerialExecutor isolation checking for Concurrency Runtime](https://github.com/apple/swift-evolution/blob/main/proposals/0471-SerialExecutor-isIsolated.md) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0471Improved Custom SerialExecutor isolation checking for Concurrency Runtime. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0472Starting tasks synchronously from caller context](https://github.com/apple/swift-evolution/blob/main/proposals/0472-task-start-synchronously-on-caller-context.md) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0472Starting tasks synchronously from caller context. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0473Clock Epochs](https://github.com/apple/swift-evolution/blob/main/proposals/0473-clock-epochs.md) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Records AcceptedSE-0473Clock Epochs, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [an official release article](https://www.swift.org/blog/swift-6.1-released) — Article · Topics: AI Development · Swift · Xcode
  **NeKI brief:** The community has already shared some excellent insights. If you’re looking to dive deeper, we highly recommend checking out this video by Vincent!
- [See SWT-0007](https://github.com/swiftlang/swift-evolution/blob/main/proposals/testing/0007-test-scoping-traits.md) — Source repository · Topics: AI Development · Swift · Testing
  **NeKI brief:** Proposes Swift Testing scoping traits that use TaskLocal context to establish isolated setup and teardown behavior. Follow it when async tests need predictable per-test environment control without global mutable configuration.
- [How to turn a SwiftUI color into a gradient](https://www.swiftwithvincent.com/blog/how-to-turn-a-swiftui-color-into-a-gradient) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains How to turn a SwiftUI color into a gradient, focusing on the underlying Swift or Apple-platform mechanism and the implementation trade-offs relevant to production code.
- [Swift by Sundell is back!](https://www.swiftbysundell.com/special/swift-by-sundell-is-back) — Article · Topics: Developer Community & Business · Personal Essays · Swift
  **NeKI brief:** Explains Swift by Sundell is back!, focusing on the underlying Swift or Apple-platform mechanism and the implementation trade-offs relevant to production code.
- [first article](https://www.swiftbysundell.com/articles/modern-url-construction-in-swift) — Article · Topics: Developer Community & Business · Personal Essays · Swift
  **NeKI brief:** Builds URLs with modern Foundation components rather than string concatenation. Use it when paths, query items, and percent encoding must remain correct under optional or user-provided values.
- [the vision document](https://github.com/swiftlang/swift-evolution/blob/main/visions/approachable-concurrency.md) — Source repository · Topics: AI Development · Concurrency · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for the vision document. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Discover the Top 10 Best Practices in App Distribution](https://appcircle.io/blog/10-best-practices-in-app-distribution-for-testing) — Article · Topics: CI/CD & Automation · Testing
  **NeKI brief:** Examines Discover the Top 10 Best Practices in App Distribution in the context of CI/CD & Automation and Testing. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Method dispatch mechanisms in Swift: static and dynamic dispatch](https://nilcoalescing.com/blog/MethodDispatchMechanismsInSwift) — Article · Topics: Performance · Swift
  **NeKI brief:** Contrasts static and dynamic Swift dispatch mechanisms. Use it when protocol requirements, extensions, class inheritance, or generics produce a method call that resolves differently than expected.
- [SwiftUI Environment - Concepts and Practice](https://fatbobman.com/en/posts/swiftui-environment-concepts-and-practice) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains SwiftUI Environment as dependency propagation and value lookup. Use it when shared configuration or services need scoped injection without threading parameters through every intermediate view.

## [Issue 264](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-264)

- Published: `2025-03-25T15:06:57.000Z`

**Topics:** Concurrency · Developer Community & Business · Graphics, Media & Games · Swift · SwiftUI · Testing

**Sections:** SwiftLee Weekly by Antoine van der Lee · SwiftUI TabView: Explained with Code Examples · Capture, Debug, and Optimize Your HTTP(s) Traffic in One App

**Selected links:**
- [Detecting body poses in a live video feed](https://www.createwithswift.com/detecting-body-poses-in-a-live-video-feed) — Article · Topics: Graphics, Media & Games · Swift
  **NeKI brief:** Detects body poses from a live video feed with Vision. Use it when real-time camera analysis needs a clear pipeline from captured frames through inference to UI updates.
- [ImplementedSE-0444Member import visibility](https://github.com/apple/swift-evolution/blob/main/proposals/0444-member-import-visibility.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0444Member import visibility. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ModelActor is Just Weird](https://www.massicotte.org/model-actor) — Article · Topics: Apple Platform Ecosystem · Concurrency · Swift
  **NeKI brief:** In this article, Matt shows his journey in understanding how the ModelActor protocol and how Swift Data deals with concurrency in the system.
- [FlowNavigation](https://github.com/magnuskahr/swiftui-flow-navigation) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Points to FlowNavigation, an open-source implementation or issue with concrete code and discussion that can inform Apple-platform development decisions.
- [Active ReviewSE-0470Global-actor isolated conformances](https://github.com/apple/swift-evolution/blob/main/proposals/0470-isolated-conformances.md) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0470Global-actor isolated conformances. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [SwiftUI Default Scroll Anchor](https://useyourloaf.com/blog/swiftui-default-scroll-anchor) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Configures a default scroll anchor so newly inserted or resized content settles at a chosen edge. Useful for chat and feed layouts where preserving the visible context matters.
- [Announcing FlowNavigation](https://www.magnuskahr.dk/posts/2025/03/announcing-FlowNavigation) — Article
  **NeKI brief:** Presents Announcing FlowNavigation, with practical context for Apple-platform developers evaluating the technique, workflow, or engineering decision described on the page.
- [Why I Avoid Group](https://chris.eidhof.nl/post/why-i-avoid-group) — Article
  **NeKI brief:** Investigates why SwiftUI's Group can produce surprising behavior by examining variadic views and view lists. Use it to reason about view structure before adding Group as a seemingly neutral wrapper.

## [Issue 263](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-263)

- Published: `2025-03-18T15:01:58.000Z`

**Topics:** App Distribution & Store Operations · Concurrency · Developer Community & Business · Navigation & Deep Linking · Swift · SwiftUI

**Sections:** SwiftLee Weekly by Antoine van der Lee · Swift Concurrency Course: Modern Concurrency & Swift 6 · Codemagic makes Apple M2 machines available, even on the free tier!

**Selected links:**
- [ImplementedSE-0451Raw identifiers](https://github.com/apple/swift-evolution/blob/main/proposals/0451-escaped-identifiers.md) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0451Raw identifiers. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [AcceptedSE-0462Task Priority Escalation APIs](https://github.com/apple/swift-evolution/blob/main/proposals/0462-task-priority-escalation-apis.md) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0462Task Priority Escalation APIs. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Key Considerations Before Using SwiftData](https://fatbobman.com/en/posts/key-considerations-before-using-swiftdata) — Article · Topics: Apple Platform Ecosystem · Swift · SwiftData
  **NeKI brief:** Evaluates SwiftData's practical limits before adoption. Use it when deciding whether its model, migration, query, or synchronization behavior fits a production persistence requirement.
- [Refactoring my SwiftUI Navigation Layer to follow the Coordinator Pattern](https://www.tiagohenriques.dev/blog/swiftui-refactor-navigation-layer-using-coordinator-pattern) — Article · Topics: Concurrency · Swift · SwiftUI
  **NeKI brief:** Refactors a SwiftUI navigation layer toward the Coordinator pattern, separating route orchestration from views. Useful for deep-link handling and feature composition when NavigationStack state is spreading across screens.
- [AcceptedSE-0463Import Objective-C completion handler parameters as `@Sendable`](https://github.com/apple/swift-evolution/blob/main/proposals/0463-sendable-completion-handlers.md) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0463Import Objective-C completion handler parameters as `@Sendable`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0467MutableSpan and MutableRawSpan: delegate mutations of contiguous memory](https://github.com/apple/swift-evolution/blob/main/proposals/0467-MutableSpan.md) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Records ImplementedSE-0467MutableSpan and MutableRawSpan: delegate mutations of contiguous memory, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Active ReviewSE-0468`Hashable` conformance for `Async(Throwing)Stream.Continuation`](https://github.com/apple/swift-evolution/blob/main/proposals/0468-async-stream-continuation-hashable-conformance.md) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0468`Hashable` conformance for `Async(Throwing)Stream.Continuation`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0469Task Naming](https://github.com/apple/swift-evolution/blob/main/proposals/0469-task-names.md) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Records ImplementedSE-0469Task Naming, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [one of the latest vision documents](https://github.com/swiftlang/swift-evolution/blob/main/visions/approachable-concurrency.md) — Source repository · Topics: Concurrency · Swift · Testing
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for the vision document. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Understanding structural identity in SwiftUI](https://tanaschita.com/swiftui-structural-identity) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains how SwiftUI uses view type and hierarchy position as structural identity to decide what persists and redraws. Follow it when conditional branches unexpectedly reset state or trigger more updates than expected.
- [The Power of Consistency: a Path to Indie Development - Pol Piella](https://podcast.going-indie.com/episodes/the-power-of-consistency-a-path-to-indie-development-pol-piella) — Podcast · Topics: Developer Community & Business
  **NeKI brief:** Discusses The Power of Consistency: a Path to Indie Development - Pol Piella, extracting concrete product or engineering practices that help independent Apple-platform developers make informed delivery decisions.
- [Identifying individual sounds in an audio file](https://www.createwithswift.com/identifying-individual-sounds-in-an-audio-file) — Article · Topics: Swift
  **NeKI brief:** Identifies individual sounds in audio with Apple's analysis frameworks. Use it when an app must classify or segment recorded media and route time-ranged results into a user-facing workflow.

## [Issue 262](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-262)

- Published: `2025-03-11T15:01:20.000Z`

**Topics:** App Intents & System Surfaces · Developer Community & Business · Graphics, Media & Games · Observation & State Management · Swift · SwiftUI

**Sections:** SwiftLee Weekly by Antoine van der Lee · Picker in SwiftUI explained with code examples · Paywalls Made Easy – Superwall

**Selected links:**
- [Rendering Pixel Art with SwiftUI](https://twocentstudios.com/2025/03/10/pixel-art-swift-ui) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Chris explores how to display pixel art crisply in SwiftUI, ensuring sharp edges without unwanted blurring for game assets but also for low-resolution graphics.
- [Creating App Intents using Assistant Schemas](https://www.createwithswift.com/creating-app-intents-using-assistant-schemas) — Article · Topics: App Intents & System Surfaces · Swift
  **NeKI brief:** Uses @AssistantSchema to declare App Intents that can integrate with system and Apple Intelligence experiences. Follow it when deciding how intent parameters and metadata should expose an existing feature without duplicating business logic.
- [Lazy Initialization @State in SwiftUI - Overcoming Premature Object Creation](https://fatbobman.com/en/posts/lazy-initialization-state-in-swiftui) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Explains lazy @State initialization for avoiding premature object construction. Use it when a state-owned object is expensive or depends on inputs that should be captured only at the correct lifecycle point.
- [Active ReviewSE-0466Control default actor isolation inference](https://github.com/apple/swift-evolution/blob/main/proposals/0466-control-default-actor-isolation.md) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0466Control default actor isolation inference. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Synchronous Work](https://www.massicotte.org/synchronous-work) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Matt delves into the trade-offs between synchronous and asynchronous execution, emphasizing the importance of understanding when and how to use each approach effectively, highlighting the trade-offs between efficiency and complexity when deciding whether to…
- [Active ReviewSE-0464UTF8Span: Safe UTF-8 Processing Over Contiguous Bytes](https://github.com/apple/swift-evolution/blob/main/proposals/0464-utf8span-safe-utf8-processing.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0464UTF8Span: Safe UTF-8 Processing Over Contiguous Bytes. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0465Standard Library Primitives for Nonescapable Types](https://github.com/apple/swift-evolution/blob/main/proposals/0465-nonescapable-stdlib-primitives.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0465Standard Library Primitives for Nonescapable Types. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [.animation() vs withAnimation(): what's the difference?](https://www.swiftwithvincent.com/blog/animation-vs-withanimation-whats-the-difference) — Article · Topics: Swift
  **NeKI brief:** Explains .animation() vs withAnimation(): what's the difference?, focusing on the underlying Swift or Apple-platform mechanism and the implementation trade-offs relevant to production code.

## [Issue 261](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-261)

- Published: `2025-03-04T15:16:50.000Z`

**Topics:** App Distribution & Store Operations · Concurrency · Developer Community & Business · Performance · Swift · SwiftUI

**Sections:** SwiftLee Weekly by Antoine van der Lee · What is Structured Concurrency? · Webinar alert: Want to ship more code faster for iOS?

**Selected links:**
- [Symmetrical and asymmetrical transitions in SwiftUI with the Scroll Transition modifier](https://www.createwithswift.com/symmetrical-and-asymmetrical-transitions-in-swiftui-with-the-scroll-transition-modifier) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Applies scrollTransition with symmetric or asymmetric phases to animate content entering and leaving a scroll view. Useful for controlled motion tied to visibility rather than arbitrary timers.
- [Animatable Protocol - Taming Unruly SwiftUI Animations](https://fatbobman.com/en/posts/animatable-protocol-taming-unruly-swiftui-animation) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Uses Animatable to control interpolation of custom SwiftUI values. Use it when a complex view animates discontinuously and needs a deliberate animatable-data representation.
- [ImplementedSE-0447Span: Safe Access to Contiguous Storage](https://github.com/apple/swift-evolution/blob/main/proposals/0447-span-access-shared-contiguous-storage.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Records ImplementedSE-0447Span: Safe Access to Contiguous Storage, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [ImplementedSE-0458Opt-in Strict Memory Safety Checking](https://github.com/apple/swift-evolution/blob/main/proposals/0458-strict-memory-safety.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0458Opt-in Strict Memory Safety Checking. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Designing a custom lazy list in SwiftUI with better performance](https://nilcoalescing.com/blog/CustomLazyListInSwiftUI) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Constructs a custom lazy list to control virtualization and layout beyond List's built-in behavior. Useful when custom scrolling visuals or cell composition require more control than standard list styles provide.
- [Active ReviewSE-0463Import Objective-C completion handler parameters as `@Sendable`](https://github.com/apple/swift-evolution/blob/main/proposals/0463-sendable-completion-handlers.md) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0463Import Objective-C completion handler parameters as `@Sendable`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [SE-461 Run nonisolated async functions on the caller's actor by default](https://github.com/swiftlang/swift-evolution/blob/e56820b8eaeb5441ad4b0a4e0132eb501729f291/proposals/0461-async-function-isolation.md) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Records SE-461 Run nonisolated async functions on the caller's actor by default, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Safer Swift: How ~Copyable Prevents Hidden Bugs](https://arturgruchala.com/safer-swift-how-copyable-prevents-hidden-bugs) — Article · Topics: Swift
  **NeKI brief:** Explains Safer Swift: How ~Copyable Prevents Hidden Bugs, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [a new thread on the Swift Forums](https://forums.swift.org/t/so-is-task-unstructured-or-what/78111) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Discusses a new thread on the Swift Forums, extracting concrete engineering practices and trade-offs that Apple-platform developers can apply when evaluating this workflow.
- [An Ode to Swift Enums: The View Models That Could](https://www.swiftjectivec.com/swift-enums-as-lighweight-view-models) — Article · Topics: Swift
  **NeKI brief:** Jordan discusses utilizing Swift enumerations as lightweight view models in iOS development, illustrating how enums can manage related values efficiently and emphasizing enums’ versatility beyond traditional uses.

## [Issue 260](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-260)

- Published: `2025-02-25T15:03:14.000Z`

**Topics:** App Distribution & Store Operations · Combine & Reactive Programming · Concurrency · Developer Community & Business · Swift · SwiftUI

**Sections:** SwiftLee Weekly by Antoine van der Lee · Task.sleep() vs. Task.yield(): The differences explained · Codemagic makes Apple M2 machines available, even on the free tier!

**Selected links:**
- [Tapping on Stack Views](https://useyourloaf.com/blog/tapping-on-stack-views) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains why tapping empty space in a SwiftUI stack may not trigger a gesture and how contentShape changes hit testing. Useful for reliable row and card interactions.
- [Quick guide on home screen quick actions for SwiftUI](https://tanaschita.com/ios-home-screen-quick-actions) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Implements Home Screen quick actions in SwiftUI. Use it when a shortcut should launch directly into an app task while keeping scene activation and routing state explicit.
- [Active ReviewSE-0462Task Priority Escalation APIs](https://github.com/apple/swift-evolution/blob/main/proposals/0462-task-priority-escalation-apis.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0462Task Priority Escalation APIs. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0461Run nonisolated async functions on the caller's actor by default](https://github.com/apple/swift-evolution/blob/main/proposals/0461-async-function-isolation.md) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0461Run nonisolated async functions on the caller's actor by default. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [How Swift's server support powers Things Cloud](https://www.swift.org/blog/how-swifts-server-support-powers-things-cloud) — Article · Topics: Swift
  **NeKI brief:** Explains How Swift's server support powers Things Cloud, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [RocketSim for Teams](https://www.rocketsim.app/team-insights) — Article · Topics: Swift
  **NeKI brief:** Presents RocketSim for Teams, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Things](https://culturedcode.com/things) — Article · Topics: Swift
  **NeKI brief:** Things is a polished task-management app for Mac, iPhone, and iPad, organized around planning, projects, and daily actions. Use it as a product reference when evaluating information hierarchy, cross-device workflows, and the interaction quality expected from native productivity software.
- [New Concurrency Stuff with 6.1](https://www.massicotte.org/concurrency-6_1) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains New Concurrency Stuff with 6.1, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [AcceptedSE-0456Add `Span`-providing Properties to Standard Library Types](https://github.com/apple/swift-evolution/blob/main/proposals/0456-stdlib-span-properties.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0456Add `Span`-providing Properties to Standard Library Types. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.

## [Issue 259](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-259)

- Published: `2025-02-18T15:10:59.000Z`

**Topics:** Developer Community & Business · Developer Tools · macOS & AppKit · Swift · SwiftUI · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · Swift 6: What’s New and How to Migrate · Master Mobile Monitoring SwiftUI Apps

**Selected links:**
- [Master Mobile Monitoring SwiftUI Apps](https://www.datadoghq.com/resources/mobile-monitoring-best-practices-b) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Presents Master Mobile Monitoring SwiftUI Apps, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Build a macOS menu bar utility in SwiftUI](https://nilcoalescing.com/blog/BuildAMacOSMenuBarUtilityInSwiftUI) — Article · Topics: macOS & AppKit · Swift · SwiftUI
  **NeKI brief:** Walks through a SwiftUI macOS menu-bar utility, including scene configuration and status-item presentation. Useful for small persistent tools that should avoid a conventional document window.
- [Code completion in GitHub Copilot for Xcode is now generally available · GitHub Changelog](https://github.blog/changelog/2025-02-14-code-completion-in-github-copilot-for-xcode-is-now-generally-available) — Article · Topics: AI Development · Developer Tools · Xcode
  **NeKI brief:** Examines GitHub Copilot for Xcode is now generally available in the context of AI Development and Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [AcceptedSE-0453InlineArray, a fixed-size array](https://github.com/apple/swift-evolution/blob/main/proposals/0453-vector.md) — Source repository · Topics: AI Development · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0453InlineArray, a fixed-size array. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Apple has open-sourced Swift's build system](https://www.swiftwithvincent.com/blog/apple-has-open-sourced-swifts-build-system) — Article · Topics: Swift · Testing
  **NeKI brief:** Explains Apple has open-sourced Swift's build system, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Mastering SwiftUI Scrolling - Implementing Custom Paging](https://fatbobman.com/en/posts/mastering-swiftui-scrolling-implementing-custom-paging) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Implements custom SwiftUI paging behavior for scrolling content. Use it when system paging is insufficient and snapping, offsets, and selection state require coordinated control.

## [Issue 258](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-258)

- Published: `2025-02-11T15:02:09.000Z`

**Topics:** App Distribution & Store Operations · App Services & Extensions · Developer Community & Business · Objective-C & Cocoa · Swift · SwiftUI

**Sections:** SwiftLee Weekly by Antoine van der Lee · How to develop an app for iOS · Master Mobile Monitoring SwiftUI Apps

**Selected links:**
- [Master Mobile Monitoring SwiftUI Apps](https://www.datadoghq.com/resources/mobile-monitoring-best-practices-b) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Presents Master Mobile Monitoring SwiftUI Apps, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [ImplementedSE-0450Package traits](https://github.com/apple/swift-evolution/blob/main/proposals/0450-swiftpm-package-traits.md) — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0450Package traits. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Implementing Face ID authentication in SwiftUI](https://tanaschita.com/ios-local-authentication) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Integrates LocalAuthentication for Face ID or Touch ID in SwiftUI. Use it when sensitive actions need a platform authentication gate and clear fallback/error handling.
- [The 7 Habits of Highly Effective People by Stephen Covey](https://amzn.to/46uww4e) — Article · Topics: Developer Career & Practice · Swift
  **NeKI brief:** Recommends The 7 Habits of Highly Effective People as a personal productivity reference for developers. Use its principles to reflect on prioritization, communication, and sustainable work habits, while adapting general advice to software-team realities.
- [SwiftUI - Navigation View If Needed](https://www.joshholtz.com/blog/2025/02/08/swiftui-navigation-view-if-needed.html) — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **NeKI brief:** Presents SwiftUI - Navigation View If Needed, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Provisional Authorization of User Notificatons](https://useyourloaf.com/blog/provisional-authorization-of-user-notificatons) — Article · Topics: App Services & Extensions
  **NeKI brief:** Explains provisional notification authorization, which delivers quietly before a full permission prompt. Use it when an app can demonstrate notification value without interrupting first-run onboarding.
- [Interactive & Beautiful CLI Tools with Noora](https://swifttoolkit.dev/posts/noora-package) — Article · Topics: Developer Tools · Swift
  **NeKI brief:** Examines Ready to use UI components for Swift CLIs in the context of Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Grouping Controls with ControlGroup](https://www.createwithswift.com/grouping-controls-with-controlgroup) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Uses ControlGroup to semantically group related SwiftUI controls. Use it when command clusters need platform-adaptive presentation without manually reproducing toolbar or menu styling.
- [Active ReviewSE-0459Add `Collection` conformances for `enumerated()`](https://github.com/apple/swift-evolution/blob/main/proposals/0459-enumerated-collection.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Records ImplementedSE-0459Add `Collection` conformances for `enumerated()`, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.

## [Issue 257](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-257)

- Published: `2025-02-04T14:26:37.000Z`

**Topics:** Developer Community & Business · Developer Tools · Objective-C & Cocoa · Swift · SwiftUI · Testing

**Sections:** SwiftLee Weekly by Antoine van der Lee · Parameterized tests in Swift: Reducing boilerplate code · FREE iOS Architect Crash Course for a limited time!

**Selected links:**
- [Swift Build](https://github.com/swiftlang/swift-build) — Source repository · Topics: Developer Tools · Swift · Xcode
  **NeKI brief:** This commitment led Apple to open-sourcing Swift Build, a build engine that offers a comprehensive set of build rules for constructing Swift projects.
- [The Next Chapter in Swift Build Technologies](https://www.swift.org/blog/the-next-chapter-in-swift-build-technologies) — Article · Topics: Swift · Xcode
  **NeKI brief:** This commitment led Apple to open-sourcing Swift Build, a build engine that offers a comprehensive set of build rules for constructing Swift projects.
- [Container relative frames in SwiftUI](https://swiftwithmajid.com/2025/01/28/container-relative-frames-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Uses container-relative frames to size SwiftUI content from its enclosing container. Use it when adaptive grids, cards, or paged layouts need proportional sizing without GeometryReader plumbing.
- [Drawing maps with Swift Charts](https://www.artemnovichkov.com/blog/drawing-maps-with-swift-charts) — Article · Topics: Maps & Location · Swift
  **NeKI brief:** Artem shows how developers merge location-based data with the Swift Chart framework to create insightful data visualizations.
- [AcceptedSE-0452Integer Generic Parameters](https://github.com/apple/swift-evolution/blob/main/proposals/0452-integer-generic-parameters.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Records AcceptedSE-0452Integer Generic Parameters, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [AcceptedSE-0457Expose attosecond representation of `Duration`](https://github.com/apple/swift-evolution/blob/main/proposals/0457-duration-attosecond-represenation.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0457Expose attosecond representation of `Duration`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0460Explicit Specialization](https://github.com/apple/swift-evolution/blob/main/proposals/0460-specialized.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0460Explicit Specialization. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Advantages of Using withAnimation](https://www.magnuskahr.dk/posts/2025/01/advantage-of-withAnimation) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Compares value-driven animation modifiers with explicit withAnimation blocks and explains where the latter gives clearer control. Follow it when an interaction changes several pieces of state and the animation scope should be obvious at the mutation site.

## [Issue 256](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-256)

- Published: `2025-01-28T15:11:34.000Z`

**Topics:** Developer Community & Business · Developer Tools · Networking · Objective-C & Cocoa · Swift · SwiftUI

**Sections:** SwiftLee Weekly by Antoine van der Lee · Network Link Conditioner: Simulating Slow Networking · Paywalls Made Easy – Superwall

**Selected links:**
- [AcceptedSE-0454Custom Allocator for Toolchain](https://github.com/apple/swift-evolution/blob/main/proposals/0454-memory-allocator.md) — Source repository · Topics: Developer Tools · Swift · Systems Programming
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0454Custom Allocator for Toolchain. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Creating a reusable action menu component in SwiftUI](https://peterfriese.dev/blog/2025/swiftui-action-menu) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a reusable SwiftUI action menu with a view builder and sheet presentation, turning a one-off menu into a component with an explicit content contract. Follow it for composition patterns, not as a substitute for platform menu guidance.
- [Debugging An Undebuggable App](https://bryce.co/undebuggable) — Article · Topics: Dependency Injection · Developer Tools
  **NeKI brief:** Explains Debugging An Undebuggable App, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Reducing Motion of Animations](https://useyourloaf.com/blog/reducing-motion-of-animations) — Article · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Shows respecting Reduce Motion preferences in animated interfaces. Use it when custom transitions or effects need an accessible reduced-motion alternative rather than assuming animation is always appropriate.
- [Things that did (and didn't) contribute to Burnout Buddy's success](https://swiftrocks.com/things-that-did-and-didnt-contribute-to-burnout-buddys-success) — Tutorial · Topics: Developer Community & Business · Swift
  **NeKI brief:** Explains Things that did (and didn't) contribute to Burnout Buddy's success, connecting the underlying Apple-platform mechanism to implementation choices and practical trade-offs that Swift developers can evaluate.
- [Color mixing in SwiftUI](https://swiftwithmajid.com/2025/01/21/color-mixing-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains SwiftUI color mixing for creating derived colors. Use it when an interface needs controlled interpolation between semantic colors while preserving dynamic appearance behavior.

## [Issue 255](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-255)

- Published: `2025-01-21T15:04:24.000Z`

**Topics:** AI Development · App Distribution & Store Operations · App Intents & System Surfaces · Concurrency · Swift · SwiftUI

**Sections:** SwiftLee Weekly by Antoine van der Lee · RocketSim 13 - Network Speed Control · Master Mobile Monitoring SwiftUI Apps

**Selected links:**
- [Master Mobile Monitoring SwiftUI Apps](https://www.datadoghq.com/resources/mobile-monitoring-best-practices-b) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Presents Master Mobile Monitoring SwiftUI Apps, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [How to use cryptographic hash functions in CryptoKit for iOS security](https://tanaschita.com/swift-hash-functions) — Article · Topics: Security & Privacy · Swift
  **NeKI brief:** Uses CryptoKit hash functions for integrity and security-related fingerprints. Use it when comparing data or deriving stable digests, while distinguishing hashing from reversible encryption.
- [Active ReviewSE-0456Add `Span`-providing Properties to Standard Library Types](https://github.com/apple/swift-evolution/blob/main/proposals/0456-stdlib-span-properties.md) — Source repository · Topics: AI Development · App Intents & System Surfaces · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0456Add `Span`-providing Properties to Standard Library Types. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0457Expose attosecond representation of `Duration`](https://github.com/apple/swift-evolution/blob/main/proposals/0457-duration-attosecond-represenation.md) — Source repository · Topics: AI Development · App Intents & System Surfaces · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0457Expose attosecond representation of `Duration`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0458Opt-in Strict Memory Safety Checking](https://github.com/apple/swift-evolution/blob/main/proposals/0458-strict-memory-safety.md) — Source repository · Topics: AI Development · App Intents & System Surfaces · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0458Opt-in Strict Memory Safety Checking. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Getting started with creative coding using Swift and SwiftUI](https://www.createwithswift.com/getting-started-with-creative-coding-using-swift-and-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Introduces creative coding with SwiftUI through generative visual experiments. Use it when exploring Canvas, animation, and mathematical drawing techniques outside conventional interface constraints.
- [Introduction to Non-Copyable types](https://www.swiftwithvincent.com/blog/introduction-to-non-copyable-types) — Article · Topics: Swift
  **NeKI brief:** Explains Introduction to Non-Copyable types, focusing on the underlying Swift or Apple-platform mechanism and the implementation trade-offs relevant to production code.

## [Issue 254](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-254)

- Published: `2025-01-14T14:03:25.000Z`

**Topics:** App Distribution & Store Operations · Developer Community & Business · Objective-C & Cocoa · Observation & State Management · Swift · SwiftUI

**Sections:** SwiftLee Weekly by Antoine van der Lee · SwiftUI Lists: Present rows of data explained with code examples · Build Crash-Free iOS Apps

**Selected links:**
- [iPhone Apps 101 - SwiftUI App Development Course](https://paulsolt.teachable.com/p/iphoneapps101?affcode=1123_hyqyixcy) — Tutorial · Topics: Developer Community & Business · Swift · SwiftUI
  **NeKI brief:** Introduces iPhone Apps 101 - SwiftUI App Development Course as a developer resource or service relevant to Swift and Apple-platform work. Use it to assess the stated workflow or offering, checking scope, pricing, access requirements, and technical fit before relying on it.
- [Creating a debounced search context for performant SwiftUI searches](https://danielsaidi.com/blog/2025/01/08/creating-a-debounced-search-context-for-performant-swiftui-searches) — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **NeKI brief:** Presents Creating a debounced search context for performant SwiftUI searches, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Active ReviewSE-0455SwiftPM @testable build setting](https://github.com/apple/swift-evolution/blob/main/proposals/0455-swiftpm-testable-build-setting.md) — Source repository · Topics: Objective-C & Cocoa · Swift · Testing
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0455SwiftPM @testable build setting. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Build Crash-Free iOS Apps](https://www.datadoghq.com/resources/mobile-monitoring-best-practices-b) — Article · Topics: Performance · Product Design
  **NeKI brief:** Presents Master Mobile Monitoring SwiftUI Apps, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [This article from The Pragmatic Engineer](https://newsletter.pragmaticengineer.com/p/how-ai-will-change-software-engineering) — Article · Topics: AI Development · Swift
  **NeKI brief:** Presents This article from The Pragmatic Engineer, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [SwiftUI Navigation using the Router Pattern](https://tiagohenriques.vercel.app/blog/swiftui-navigation-router-pattern) — Article · Topics: Navigation & Deep Linking · Swift · SwiftUI
  **NeKI brief:** Implements a router pattern for SwiftUI navigation with centralized route decisions. Useful for making deep links, modal presentation, and navigation tests deterministic while keeping views focused on rendering.
- [Using withObservationTracking to monitor changes in @Observable properties outside SwiftUI views](https://www.polpiella.dev/observable-outside-of-a-view) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Uses withObservationTracking to observe @Observable changes outside SwiftUI views. Use it when an imperative coordinator or service needs dependency-aware callbacks without adopting Combine.
- [Active ReviewSE-0454Custom Allocator for Toolchain](https://github.com/apple/swift-evolution/blob/main/proposals/0454-memory-allocator.md) — Source repository · Topics: Objective-C & Cocoa · Swift · Systems Programming
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0454Custom Allocator for Toolchain. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Handle plurals in SwiftUI Text views with inflection](https://nilcoalescing.com/blog/HandlePluralsInSwiftUITextViewsWithInflection) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Uses SwiftUI text inflection to select plural forms from localized strings. Useful for grammatical counts that must adapt to locale without embedding English-only singular/plural conditionals.

## [Issue 253](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-253)

- Published: `2025-01-07T13:02:49.000Z`

**Topics:** Developer Community & Business · macOS & AppKit · Swift · SwiftUI · Testing · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · iOS App Development: How to get started? · FREE iOS Architect Crash Course for a limited time!

**Selected links:**
- [How one new Xcode feature helped my work project to remove 66,000 lines of code](https://blog.makwanbk.com/how-one-new-xcode-feature-helped-my-work-project-eliminate-66k-lines-of-code) — Article · Topics: Swift · Xcode
  **NeKI brief:** Makwan highlights how Xcode 16’s buildable folders helped streamline the author’s team project while exploring its impact and trade-offs.
- [How to keep your macOS app's menu bar item running after quitting the app](https://www.polpiella.dev/keep-menu-bar-running-after-quitting-app) — Article · Topics: macOS & AppKit · Personal Essays
  **NeKI brief:** Explains keeping a macOS menu-bar utility available after closing ordinary windows. Use it when separating an app's activation policy, status item, and termination behavior.
- [Customizing macOS window background in SwiftUI](https://nilcoalescing.com/blog/CustomizingMacOSWindowBackgroundInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows how to customize a macOS SwiftUI window background while respecting the hosting window boundary. Useful for translucent or branded surfaces that cannot be achieved with view modifiers alone.
- [Accessibility That Fits](https://khanlou.com/2024/12/accessibility-that-fits) — Article · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Discusses fitting accessibility behavior into existing interfaces without treating it as a late checklist. Useful for reviewing SwiftUI labels, traits, Dynamic Type, and interaction alternatives as part of component design.
- [Getting started with UI Testing for SwiftUI](https://tanaschita.com/testing-ui-swiftui-xctest-framework) — Article · Topics: Swift · SwiftUI · Testing
  **NeKI brief:** Demonstrates UI testing SwiftUI applications with XCTest, including accessibility-driven queries and interaction assertions. Useful for testing user-visible behavior without coupling tests to implementation details.

## [Issue 252](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-252)

- Published: `2024-12-31T13:36:11.000Z`

**Topics:** App Distribution & Store Operations · Concurrency · Developer Community & Business · Observation & State Management · Swift · Testing

**Sections:** SwiftLee Weekly by Antoine van der Lee · SwiftLee in 2024: Lessons learned and achievements · Screenshotbot: Scale up your snapshot tests, without the friction

**NeKI brief:** Reviews SwiftLee’s 2024 lessons and achievements, then points to practical Swift and SwiftUI explainers covering async/await, MainActor, Sendable, ViewBuilder, and state-object choices. The issue pairs retrospective context with concrete concurrency, observation, and testing-oriented reading for Apple-platform developers.

## [Issue 251](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-251)

- Published: `2024-12-23T10:34:05.000Z`

**Topics:** Accessibility · App Distribution & Store Operations · Developer Community & Business · macOS & AppKit · Swift · SwiftUI

**Sections:** SwiftLee Weekly by Antoine van der Lee · Swift Tutorials: Learn Swift with Easy-to-Follow Code Examples · Codemagic makes Apple M2 machines available, even on the free tier!

**Selected links:**
- [From Icon to Identity: The Essentials of Branding Your App](https://www.createwithswift.com/from-icon-to-identity-the-essentials-of-branding-your-app) — Article · Topics: Product Design · Swift
  **NeKI brief:** Explains how app branding connects icon design, visual language, and user experience to recognition and trust. Useful when aligning product identity across launch assets and in-app surfaces without treating an icon as an isolated graphic.
- [VoiceOver on macOS: First Time, Huh?](https://www.basbroek.nl/macos-voiceover-first-time-huh) — Article · Topics: Accessibility · macOS & AppKit
  **NeKI brief:** Presents VoiceOver on macOS: First Time, Huh?, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Creating a SwiftUI text view with tappable links](https://danielsaidi.com/blog/2024/12/18/creating-a-swiftui-text-view-with-tappable-links) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents Creating a SwiftUI text view with tappable links, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [AcceptedSE-0450Package traits](https://github.com/apple/swift-evolution/blob/main/proposals/0450-swiftpm-package-traits.md) — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0450Package traits. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Local Xcode Build Duration insights for your whole team](https://www.rocketsim.app/team-insights) — Article · Topics: Xcode
  **NeKI brief:** Presents RocketSim for Teams, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Adjust the intensity of colors in SwiftUI views](https://nilcoalescing.com/blog/AdjustTheIntensityOfColorsInSwiftUIViews) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Adjusts SwiftUI color intensity with platform-aware rendering controls. Use it when a design needs subtle emphasis changes without replacing semantic colors with fixed, inaccessible values.
- [Under the Radar Podcast: What's In Our Toolbox: Simulators & Source Control](https://www.relay.fm/radar/308) — Podcast · Topics: Developer Community & Business
  **NeKI brief:** Discusses Under the Radar Podcast: What's In Our Toolbox: Simulators & Source Control, providing concrete engineering context that Apple-platform developers can use when evaluating the referenced workflow.
- [get your link in front of my audience](https://getsponsy.com/my/swiftlee-weekly-newsletter) — Article · Topics: Swift
  **NeKI brief:** Discusses get your link in front of my audience, providing concrete engineering context that Apple-platform developers can use when evaluating the referenced workflow.
- [webhooks](https://www.revenuecat.com/docs/integrations/webhooks) — Article · Topics: App Distribution & Store Operations
  **NeKI brief:** Discusses webhooks, extracting concrete product or engineering practices that help independent Apple-platform developers make informed delivery decisions.
- [Never Miss a Localized String Value Again](https://jacobzivandesign.com/technology/never-miss-a-localized-string) — Article
  **NeKI brief:** Discusses Never Miss a Localized String Value Again, extracting concrete engineering practices and trade-offs that Apple-platform developers can apply when evaluating this workflow.

## [Issue 250](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-250)

- Published: `2024-12-17T10:30:53.000Z`

**Topics:** App Distribution & Store Operations · Developer Tools · Swift · SwiftUI · Testing · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · SwiftUI Button: Custom Styles, Variants, and Best Practices · Screenshotbot: Scale up your snapshot tests, without the friction

**Selected links:**
- [Code for this week's article can be found on GitHub.](https://github.com/AvdLee/SwiftLeeArticlesCode) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Code for this week's article can be found on GitHub.. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Xcode Library customization with SPM plugin](https://www.artemnovichkov.com/blog/xcode-library-customization-with-spm-plugin) — Article · Topics: Xcode
  **NeKI brief:** Artem explains how to customize the Xcode Library by using a Swift Package Manager demonstrating how to automate the discovery and addition of reusable UI components, such as views and modifiers, to the library.
- [Exploring MLX Swift: Adding On-Device Inference to your App](https://www.rudrank.com/exploring-mlx-swift-adding-on-device-inference-to-your-app) — Article · Topics: AI Development · Swift
  **NeKI brief:** Presents Exploring MLX Swift: Adding On-Device Inference to your App, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Getting rid of macOS Sequoia Screen Recording permission alerts](https://9to5mac.com/2024/09/24/macos-sequoia-screen-recording-permission-nags-can-now-be-permanently-vanquished) — Article · Topics: macOS & AppKit · Swift
  **NeKI brief:** Discusses Getting rid of macOS Sequoia Screen Recording permission alerts, extracting concrete engineering practices and trade-offs that Apple-platform developers can apply when evaluating this workflow.
- [Finding unused code with Periphery](https://adamwulf.me/2024/12/finding-unused-code-with-periphery) — Article
  **NeKI brief:** Presents Finding unused code with Periphery, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Noncopyable types in Swift](https://nilcoalescing.com/blog/NoncopyableTypesInSwift) — Article · Topics: Swift
  **NeKI brief:** Explains noncopyable Swift types and ownership restrictions. Use it when a resource must have unique lifetime semantics and accidental copying would be invalid or expensive.
- [Understanding opaque types in Swift](https://tanaschita.com/swift-opaque-types) — Article · Topics: Swift
  **NeKI brief:** Explains opaque result types and their distinction from existential protocol values. Use it when an API should hide a concrete type while preserving compile-time specialization and identity guarantees.
- [get your product in front of my audience](https://getsponsy.com/my/swiftlee-weekly-newsletter) — Article · Topics: Swift
  **NeKI brief:** Discusses get your link in front of my audience, providing concrete engineering context that Apple-platform developers can use when evaluating the referenced workflow.

## [Issue 249](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-249)

- Published: `2024-12-10T13:47:59.000Z`

**Topics:** AI Development · App Distribution & Store Operations · Developer Community & Business · Swift · SwiftUI · Testing

**Sections:** SwiftLee Weekly by Antoine van der Lee · SF Symbol: How to for Swift & SwiftUI · Create a complete design system using SwiftUI

**Selected links:**
- [Create a complete design system using SwiftUI](https://iosdevlibrary.lemonsqueezy.com/buy/e6e97a6a-2762-4677-bee6-bcccbb024f7d?checkout%5Bdiscount_code%5D=SWIFTLEE40) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Introduces Create a complete design system using SwiftUI as a developer resource or service relevant to Swift and Apple-platform work. Use it to assess the stated workflow or offering, checking scope, pricing, access requirements, and technical fit before relying on it.
- [Be careful wrapping a throwing function in a Task](https://www.swiftwithvincent.com/blog/be-careful-wrapping-a-throwing-function-in-a-task) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains Be careful wrapping a throwing function in a Task, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Exploring Apple Intelligence: Image Generation](https://www.createwithswift.com/exploring-apple-intelligence-image-generation) — Article · Topics: AI Development · Swift
  **NeKI brief:** Compares Image Playground, Image Wand, and Genmoji as Apple Intelligence image-generation surfaces. Use it to distinguish system experiences and choose the appropriate entry point before implementing app-specific creative workflows.
- [AcceptedSE-0451Raw identifiers](https://github.com/apple/swift-evolution/blob/main/proposals/0451-escaped-identifiers.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0451Raw identifiers. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Migrating XCTest to Swift Testing](https://useyourloaf.com/blog/migrating-xctest-to-swift-testing) — Article · Topics: Swift · Testing
  **NeKI brief:** A migration field guide that mixes XCTest and Swift Testing in one target, maps assertions and setup, and calls out the boundary: UI automation and XCTMetric performance tests still require XCTest.
- [How to change your app's business model from paid to freemium using StoreKit](https://www.polpiella.dev/paid-app-to-freemium) — Article
  **NeKI brief:** Shows changing an app's business model from paid upfront to freemium using StoreKit's AppTransaction API. Follow it when planning migration logic and entitlement checks, then verify transaction semantics, customer communication, and App Store policy requirements.
- [let is a lie (sometimes)](https://www.swiftwithvincent.com/blog/let-is-a-lie-sometimes) — Article · Topics: Swift
  **NeKI brief:** Explains let is a lie (sometimes), focusing on the underlying Swift or Apple-platform mechanism and the implementation trade-offs relevant to production code.

## [Issue 248](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-248)

- Published: `2024-12-03T14:26:41.000Z`

**Topics:** Concurrency · Developer Community & Business · Developer Tools · Swift · SwiftUI · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · Enum explained in-depth with code examples in Swift · Tower: native Git client for Mac (30% OFF, only this week!)

**Selected links:**
- [TextField enhancements in SwiftUI](https://swiftwithmajid.com/2024/12/03/text-field-enhancements-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Covers newer SwiftUI TextField capabilities. Use it when text input needs richer editing behavior, formatting, or platform integration beyond a basic bound string.
- [SwiftUI matched geometry effect in a custom segmented control](https://nilcoalescing.com/blog/CustomSegmentedControlWithMatchedGeometryEffect) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a segmented control with matchedGeometryEffect so the selection indicator moves between segments. Useful for coordinated SwiftUI transitions while keeping selection state separate from animation identity.
- [MacWhisper: Transcribe audio files into text with OpenAI](https://goodsnooze.gumroad.com/l/macwhisper) — Article · Topics: AI Development · Concurrency · Swift
  **NeKI brief:** Explains MacWhisper: Transcribe audio files into text with OpenAI, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Concurrency Step-by-Step: Reading from Storage](https://www.massicotte.org/step-by-step-reading-from-storage) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Matt offers a step-by-step guide to handling concurrent data storage operations in Swift, focusing on common challenges and best practices explaining how to properly manage data access across different threads while maintaining type safety.
- [That's possible!](https://getsponsy.com/my/swiftlee-weekly-newsletter) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Discusses get your link in front of my audience, providing concrete engineering context that Apple-platform developers can use when evaluating the referenced workflow.
- [Find out in this interview I've had with Firm24](https://www.firm24.com/ondernemersverhalen/swiftlee) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Discusses Find out in this interview I've had with Firm24, providing concrete engineering context that Apple-platform developers can use when evaluating the referenced workflow.
- [Why Can't You Loop Over Ranges of Characters in Swift](https://mfaani.com/posts/swift/why-cant-you-loop-over-ranges-of-characters-in-swift) — Article · Topics: Swift
  **NeKI brief:** Discusses Why Can't You Loop Over Ranges of Characters in Swift, providing concrete engineering context that Apple-platform developers can use when evaluating the referenced workflow.
- [How I reduce the iOS TPBank app size by half](https://ericsspace.com/articles/how-to-reduce-tpbank-appsize-by-half) — Article · Topics: Cross-Platform & Web
  **NeKI brief:** Examines A practical example on how to cut your app’s size in half in the context of Cross-Platform & Web. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 247](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-247)

- Published: `2024-11-26T15:01:34.000Z`

**Topics:** AI Development · Developer Community & Business · Persistence & Synchronisation · Swift · SwiftUI · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · Black Friday: 50% discount on RocketSim & Going Indie Course · Codemagic makes Apple M2 machines available, even on the free tier!

**Selected links:**
- [Should we use Apple Intelligence for Text and Inputs in SwiftUI using writingToolsBehavior](https://medium.com/@jpmtech/should-we-use-apple-intelligence-for-text-and-inputs-in-swiftui-using-writingtoolsbehavior-49d662ce5ede) — Article · Topics: AI Development · Swift · SwiftUI
  **NeKI brief:** Evaluates writingToolsBehavior for Apple Intelligence text assistance in SwiftUI inputs. Use it when deciding whether system writing tools fit an editor, checking availability, privacy expectations, and user-control requirements.
- [Using Transactions Instead of Save in SwiftData and Core Data](https://fatbobman.com/en/posts/using-transactions-instead-of-save-in-swiftdata-and-core-data) — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** Compares transaction-style persistence work with ordinary save calls in SwiftData and Core Data. Use it when batching mutations, rollback boundaries, and consistency matter more than one-off writes.
- [Time-Based View Updates in SwiftUI](https://digitalbunker.dev/time-based-view-updates-in-swiftui) — Article · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** In this article Aryaman shares how to use the TimeLineView container to programmatically update a SwiftUI View following a specific schedule.
- [How to create and upload high-quality App Store assets](https://www.polpiella.dev/creating-and-uploading-app-store-assets) — Article · Topics: App Distribution & Store Operations
  **NeKI brief:** Demonstrates creating App Store screenshots and previews with RocketSim and uploading assets through Helm. Useful for making release marketing repeatable, while reviewing device coverage, localization, metadata accuracy, and App Store Connect validation before submission.

## [Issue 246](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-246)

- Published: `2024-11-19T12:58:52.000Z`

**Topics:** AI Development · App Distribution & Store Operations · Swift · SwiftUI · Testing · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · Contingent pricing for in-app subscriptions · Master Test Distribution & App Releases Amid App Center’s Shutdown

**Selected links:**
- [Copilot is now available in Xcode (and it’s good!)](https://www.swiftwithvincent.com/blog/copilot-is-available-in-xcode) — Article · Topics: AI Development · Swift · Xcode
  **NeKI brief:** Presents Copilot is now available in Xcode (and it’s good!), focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [ChatGPT for macOS can now work with Xcode](https://dimillian.medium.com/chatgpt-for-macos-can-now-work-with-xcode-28cecc9decf7) — Article · Topics: AI Development · macOS & AppKit · Xcode
  **NeKI brief:** Presents ChatGPT for macOS can now work with Xcode, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Active ReviewSE-0453Vector, a fixed-size array](https://github.com/apple/swift-evolution/blob/main/proposals/0453-vector.md) — Source repository · Topics: Developer Tools · Swift · Testing
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0453InlineArray, a fixed-size array. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Lazy vars in @Observable classes in Swift](https://nilcoalescing.com/blog/LazyVarsInObservableClasses) — Article · Topics: Observation & State Management · Swift
  **NeKI brief:** Shows why lazy properties in @Observable types need @ObservationIgnored and where observation would otherwise treat initialization as a tracked mutation. It is a targeted fix for compiler or runtime behavior during Observation migration.
- [Understanding SwiftUI's View Update Mechanism](https://fatbobman.com/en/posts/understanding-swiftui-view-update-mechanism) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a mental model for SwiftUI body evaluation, dependency tracking, and rendering updates. Useful when investigating redundant recomputation or assuming every state change redraws the entire hierarchy.
- [App Store Nominations](https://helm-app.com/changelog/helm-1-4-app-store-nominations-rocketsim) — Article · Topics: App Distribution & Store Operations
  **NeKI brief:** Discusses App Store Nominations, extracting concrete engineering practices and trade-offs that Apple-platform developers can apply when evaluating this workflow.

## [Issue 245](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-245)

- Published: `2024-11-12T19:03:27.000Z`

**Topics:** Concurrency · Core Data · Developer Community & Business · Objective-C & Cocoa · Persistence & Synchronisation · Swift

**Sections:** SwiftLee Weekly by Antoine van der Lee · MainActor usage in Swift explained to dispatch to the main thread · Transform Your Career with the iOS Lead Essentials — Black Friday Offer

**Selected links:**
- [swift-format](https://github.com/swiftlang/swift-format) — Source repository · Topics: Developer Tools · Swift · Xcode
  **NeKI brief:** swift-format is the official Swift formatter and linter. Use it to enforce formatting consistently in local development and CI without relying on editor-specific whitespace settings.
- [ImplementedSE-0106Add a `macOS` Alias for the `OSX` Platform Configuration Test](https://github.com/apple/swift-evolution/blob/main/proposals/0106-rename-osx-to-macos.md) — Source repository · Topics: Developer Tools · macOS & AppKit · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0106Add a `macOS` Alias for the `OSX` Platform Configuration Test. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ImplementedSE-0449Allow `nonisolated` to prevent global actor inference](https://github.com/apple/swift-evolution/blob/main/proposals/0449-nonisolated-for-global-actor-cutoff.md) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0449Allow `nonisolated` to prevent global actor inference. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Apple’s Swift Format in Xcode](https://troz.net/post/2024/swift_format) — Article · Topics: Swift · Xcode
  **NeKI brief:** Presents Apple’s Swift Format in Xcode, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [ImplementedSE-0371Isolated synchronous deinit](https://github.com/apple/swift-evolution/blob/main/proposals/0371-isolated-synchronous-deinit.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Records ImplementedSE-0371Isolated synchronous deinit, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Mastering Data Tracking and Notifications in Core Data and SwiftData](https://fatbobman.com/en/posts/mastering-data-tracking-and-notifications-in-core-data-and-swiftdata) — Article · Topics: Core Data · Persistence & Synchronisation · Swift
  **NeKI brief:** Explores change tracking and notifications in Core Data and SwiftData. Use it when UI or synchronization logic must react to persistence mutations without polling or broad refreshes.
- [Apple is Killing Swift](https://blog.jacobstechtavern.com/p/apple-is-killing-swift) — Article · Topics: Swift
  **NeKI brief:** An opinionated examination of Swift's governance and ecosystem direction; useful for evaluating community concerns rather than technical guidance.
- [Prevent screenshot capture of sensitive SwiftUI views](https://www.createwithswift.com/prevent-screenshot-capture-of-sensitive-swiftui-views) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Discusses protecting sensitive SwiftUI content from screenshots or recordings. Use it when privacy-sensitive screens need a deliberate platform-supported strategy and clear limitations communicated to product stakeholders.
- [AcceptedSE-0446Nonescapable Types](https://github.com/apple/swift-evolution/blob/main/proposals/0446-non-escapable.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Records AcceptedSE-0446Nonescapable Types, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Adapty: Revenue manage­ment platform for mobile apps](https://go.adapty.io/adapty.main) — Article · Topics: Swift
  **NeKI brief:** Presents Adapty: Revenue manage­ment platform for mobile apps, documenting the referenced developer product or learning offer and its practical context for independent iOS work.

## [Issue 244](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-244-1)

- Published: `2024-11-05T21:06:10.000Z`

**Topics:** AI Development · Concurrency · Developer Tools · Swift · SwiftUI · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · URLSession async/await: Perform network requests in Swift · Transform Your Career with the iOS Lead Essentials — Black Friday Offer

**Selected links:**
- [Using ViewThatFits to Create a More Accessible List Cell in SwiftUI](https://medium.com/@jpmtech/using-viewthatfits-to-create-a-more-accessible-list-cell-in-swiftui-e87dc8feb4d4) — Article · Topics: Product Design · Swift · SwiftUI
  **NeKI brief:** Presents Using ViewThatFits to Create a More Accessible List Cell in SwiftUI, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [GitHub Copilot for Xcode](https://dimillian.medium.com/github-copilot-for-xcode-62931a645173) — Article · Topics: AI Development · Developer Tools · Xcode
  **NeKI brief:** Presents GitHub Copilot for Xcode, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Problematic Patterns in Swift Concurrency](https://www.massicotte.org/problematic-patterns) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains Problematic Patterns in Swift Concurrency, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Exploring SwiftUI Image Playground](https://www.rudrank.com/exploring-swiftui-image-playground) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Rudrank explores the new Image Playground feature which enables customizable image generation directly within SwiftUI apps.
- [Exploring Apple’s Intelligence Writing Tools](https://www.createwithswift.com/exploring-apple-intelligence-writing-tools) — Article · Topics: Swift
  **NeKI brief:** Covers Writing Tools across SwiftUI and UIKit, including intelligent animation and ecosystem integration. Use it to compare framework-specific adoption paths and identify where text-editing controls can inherit system writing assistance.

## [Issue 243](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-243-2)

- Published: `2024-10-29T08:54:32.000Z`

**Topics:** App Distribution & Store Operations · Developer Tools · Macros & Metaprogramming · Swift · SwiftUI · Testing

**Sections:** SwiftLee Weekly by Antoine van der Lee · Mastering the @require Macro in Swift Testing · Master Mobile Monitoring SwiftUI Apps

**Selected links:**
- [Master Mobile Monitoring SwiftUI Apps](https://www.datadoghq.com/resources/mobile-monitoring-best-practices-b) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Presents Master Mobile Monitoring SwiftUI Apps, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Creating View Transitions in SwiftUI](https://www.createwithswift.com/creating-view-transitions-in-swiftui) — Article · Topics: Product Design · Swift · SwiftUI
  **NeKI brief:** Creates custom SwiftUI view transitions. Use it when insertion and removal need coordinated visual state beyond the standard opacity or movement transitions.
- [ImplementedSE-0387Swift SDKs for Cross-Compilation](https://github.com/apple/swift-evolution/blob/main/proposals/0387-cross-compilation-destinations.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Records ImplementedSE-0387Swift SDKs for Cross-Compilation, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [AcceptedSE-0449Allow `nonisolated` to prevent global actor inference](https://github.com/apple/swift-evolution/blob/main/proposals/0449-nonisolated-for-global-actor-cutoff.md) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0449Allow `nonisolated` to prevent global actor inference. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0450Package traits](https://github.com/apple/swift-evolution/blob/main/proposals/0450-swiftpm-package-traits.md) — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0450Package traits. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Expedited App Reviews: When and How to Use Them](https://www.polpiella.dev/expedited-app-reviews) — Article · Topics: App Distribution & Store Operations
  **NeKI brief:** Explains Apple's expedited App Review process and the circumstances in which a developer can request faster review. Use it as operational guidance for urgent fixes, while documenting impact clearly and treating approval as discretionary rather than guaranteed.
- [Comprehensive Guide to Mastering KeyPath in Swift](https://fatbobman.com/en/posts/comprehensive-guide-to-mastering-keypath-in-swift) — Article · Topics: Swift
  **NeKI brief:** Explains Swift key paths for typed property access and transformation. Use it when building reusable sorting, binding, observation, or mapping APIs without fragile string identifiers.
- [AcceptedSE-0447Span: Safe Access to Contiguous Storage](https://github.com/apple/swift-evolution/blob/main/proposals/0447-span-access-shared-contiguous-storage.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Records ImplementedSE-0447Span: Safe Access to Contiguous Storage, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Active ReviewSE-0451Raw identifiers](https://github.com/apple/swift-evolution/blob/main/proposals/0451-escaped-identifiers.md) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0451Raw identifiers. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.

## [Issue 242](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-242)

- Published: `2024-10-23T08:02:09.000Z`

**Topics:** Combine & Reactive Programming · Developer Community & Business · Developer Tools · Security & Privacy · Swift · SwiftUI

**Sections:** SwiftLee Weekly by Antoine van der Lee · Security-scoped bookmarks for URL access · Master Mobile Monitoring SwiftUI Apps

**NeKI brief:** Highlights security-scoped bookmarks for persistent sandboxed URL access and introduces mobile monitoring for SwiftUI apps. It also links an SE-0445 proposal; treat that primary-source item as language evolution context, while the two featured sections guide macOS persistence and production observability.

## [Issue 241](https://newsletter.avanderlee.com/posts/241)

- Published: `2024-10-23T07:44:05.000Z`

**Topics:** Combine & Reactive Programming · Developer Community & Business · Developer Tools · Security & Privacy · Swift · SwiftUI

**Sections:** SwiftLee Weekly by Antoine van der Lee · Security-scoped bookmarks for URL access · Master Mobile Monitoring SwiftUI Apps

**NeKI brief:** Mirrors Issue 242’s October 2024 programming: security-scoped bookmarks for sandboxed URL access and mobile monitoring for SwiftUI applications, alongside the same SwiftLee newsletter framing. Use it as a duplicate archive route, not as a separate set of recommendations.
