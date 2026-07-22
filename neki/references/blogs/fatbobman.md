# Fatbobman

Third-party source index. It provides source attribution and routing metadata, not republished article content. Verify article conclusions independently before applying them.

- Archive: [https://fatbobman.com/en/posts/](https://fatbobman.com/en/posts/)
- Last collected: `2026-07-22T21:58:56Z`
- Indexed entries: **213**

- [A Deep Dive into SwiftUI Rich Text Layout - Beyond AttributedString — Inside MarkdownView and RichText](https://fatbobman.com/en/posts/a-deep-dive-into-swiftui-rich-text-layout)
  **Published:** `2025-12-03T14:12:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Dissects how MarkdownView and RichText combine SwiftUI layout, SVG and formula rendering, text selection, and PreferenceKey-based measurement. It provides implementation context for rich document views that exceed AttributedString's layout capabilities.
- [From iOS to Android - A Candid Look at My Real-World Journey into Dual-Platform Development](https://fatbobman.com/en/posts/from-ios-to-android)
  **Published:** `2025-11-26T14:12:00.000Z`
  **Topics:** Cross-Platform & Web
  **NeKI brief:** Reports the practical costs of extending an iOS product to Android, including feature parity, store rules, monetization, and China-specific distribution. Use it to frame platform expansion as an operational decision, not only a UI rewrite.
- [Deep Dive into iMessage - Behind the Making of an Agent](https://fatbobman.com/en/posts/deep-dive-into-imessage)
  **Published:** `2025-11-19T14:12:00.000Z`
  **Topics:** Architecture · Core Data · Performance · Persistence & Synchronisation
  **NeKI brief:** Investigates iMessage storage through SQLite and Core Data timestamps, then uses imessage-kit to build an automation agent. The article is a concrete reference for understanding macOS message data boundaries and automation risks.
- [Grow on iOS 26 - Liquid Glass Adaptation in UIKit + SwiftUI Hybrid Architecture](https://fatbobman.com/en/posts/grow-on-ios26)
  **Published:** `2025-11-12T14:12:00.000Z`
  **Topics:** Architecture · Concurrency · Liquid Glass · Swift · SwiftUI · UIKit
  **NeKI brief:** Documents Grow's iOS 26 Liquid Glass migration across UIKit and SwiftUI, including navigation refactors, sheet behavior, bar-button sizing, and CABackdropLayer side effects. Follow it for production integration pitfalls beyond sample code.
- [Using MainActor.assumeIsolated to Solve Legacy API Compatibility Issues with Swift 6](https://fatbobman.com/en/posts/mainactor-assumeisolated)
  **Published:** `2025-09-03T14:00:00.000Z`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Explains how MainActor.assumeIsolated bridges synchronous legacy callbacks to actor-isolated code while preserving Sendable return values. It is useful when Swift 6 diagnostics expose an isolation mismatch that cannot be solved by simply adding async.
- [Swift 6 - Sendable, @unchecked Sendable, @Sendable, sending and nonsending](https://fatbobman.com/en/posts/sendable-sending-nonsending)
  **Published:** `2025-08-06T14:00:00.000Z`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Compares Sendable, sending, and nonsending boundaries in Swift concurrency. Use it when designing APIs that transfer values across isolation domains and need precise ownership or compiler-checking semantics.
- [Default Actor Isolation - New Problems from Good Intentions](https://fatbobman.com/en/posts/default-actor-isolation)
  **Published:** `2025-07-30T14:00:00.000Z`
  **Topics:** Concurrency · Macros & Metaprogramming · Swift
  **NeKI brief:** Swift 6.2 infers a default actor for otherwise unmarked declarations, reducing annotations but exposing actor-boundary errors in macros and mixed-isolation code. This is useful when auditing migration diagnostics and deciding where explicit isolation remains necessary.
- [Core Data Migration Incident Analysis - The Hidden Traps We Overlooked](https://fatbobman.com/en/posts/core-data-migration-incident-analysis)
  **Published:** `2025-07-23T14:00:00.000Z`
  **Topics:** Core Data · Persistence & Synchronisation
  **NeKI brief:** A production migration freeze is traced to WAL checkpoint behavior and work performed during startup. The analysis favors background initialization and explicit WAL optimization, giving a concrete checklist for separating migration cost from main-thread launch failures.
- [Icon Composer - Tackling Challenges](https://fatbobman.com/en/posts/icon-composer-tackling-challenges)
  **Published:** `2025-07-16T14:30:00.000Z`
  **Topics:** Liquid Glass · Xcode
  **NeKI brief:** Documents practical Icon Composer issues around SVG imports, monochrome brightness, layer limits, design trade-offs, and final Xcode integration.
- [How to Detect Text Truncation in SwiftUI?](https://fatbobman.com/en/posts/how-to-detect-text-truncation-in-swiftui)
  **Published:** `2025-07-09T14:12:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Measures SwiftUI text to detect truncation and compare rendered versus available dimensions. Useful for showing expansion affordances or accessibility hints when localized content does not fit.
- [Dancing with AI - My Month with Claude Code](https://fatbobman.com/en/posts/dancing-with-ai-my-month-with-claude-code)
  **Published:** `2025-07-02T14:12:00.000Z`
  **Topics:** AI Development
  **NeKI brief:** Reflects on a month using Claude Code while emphasizing active programming judgment and the risk of becoming a spectator. Use it to evaluate where agent speed supports learning versus where it erodes technical understanding.
- [NotificationCenter.Message - A New Concurrency-Safe Notification Experience in Swift 6.2](https://fatbobman.com/en/posts/notificationcentermessage-a-new-concurrency-safe-notification-experience-in-swift-62)
  **Published:** `2025-06-25T14:00:00.000Z`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Introduces Swift 6.2’s concurrency-safe NotificationCenter.Message APIs for typed notifications. Use it to replace loosely typed broadcasts and make notification payloads, isolation, and observer handling explicit.
- [Exploring the Secrets of layoutPriority in SwiftUI ZStack](https://fatbobman.com/en/posts/exploring-the-secrets-of-layoutpriority-in-zstack)
  **Published:** `2025-06-18T00:12:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** ZStack sizing can be changed by toggling layoutPriority, because the container evaluates competing child dimensions rather than simply overlaying them. The experiments provide a diagnostic model for surprising adaptive sizes without adding conditional branches.
- [WWDC 2025 First Impressions - As Expected, Yet Unexpected](https://fatbobman.com/en/posts/wwdc-2025-first-impressions)
  **Published:** `2025-06-11T00:12:00.000Z`
  **Topics:** AI Development · Liquid Glass · Persistence & Synchronisation · Swift · SwiftData · SwiftUI
  **NeKI brief:** Offers first impressions of WWDC 2025 through Liquid Glass, SwiftUI, SwiftData, Foundation Models, and macros. Follow it for ecosystem-level context and competing priorities, not as a substitute for API-level migration guidance.
- [Notepad.exe - A Lightweight Swift Code Editor](https://fatbobman.com/en/posts/notepad-exe-a-lightweight-swift-code-editor)
  **Published:** `2025-06-04T14:30:00.000Z`
  **Topics:** Swift · Testing
  **NeKI brief:** Notepad.exe is a lightweight editor built in Swift, making a concrete case study in composing document handling, syntax presentation, and macOS UI without a heavyweight IDE. Follow it for pragmatic scope and architecture trade-offs.
- [Swift 6 Refactoring in a Camera App - SLIT_STUDIO Development Log](https://fatbobman.com/en/posts/swift6-refactoring-in-a-camera-app)
  **Published:** `2025-05-28T14:00:00.000Z`
  **Topics:** Concurrency · Swift
  **NeKI brief:** The SLIT_STUDIO log documents a real Swift 6 refactor in a camera app, where strict concurrency and Sendable diagnostics expose hidden ownership assumptions. It is useful for seeing incremental fixes in feature-rich, hardware-facing code.
- [Experience the Charm of Swift - One-Click DataFrame Export](https://fatbobman.com/en/posts/experience-the-charm-of-swift-one-click-export-dataframe)
  **Published:** `2025-05-21T14:00:00.000Z`
  **Topics:** Concurrency · Dependency Injection · Swift
  **NeKI brief:** The DataFrame export example shows Swift tabular data moving into a one-click file workflow, connecting typed values with user-facing document output. Follow it when evaluating ergonomics and format boundaries in data-heavy tools.
- [Demystifying SwiftUI’s .ignoredByLayout() — How to Apply Geometry Effects Without Breaking Your Layout](https://fatbobman.com/en/posts/demystifying-swiftuis-ignoredbylayout)
  **Published:** `2025-05-14T00:12:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Explains how ignoredByLayout removes a view from layout participation while retaining rendering or interaction implications. Useful for distinguishing hidden geometry from conditional rendering when composing overlays and transitions.
- [From 180 cm to 5′ 11″ - A Complete Guide to Swift Measurement](https://fatbobman.com/en/posts/a-complete-guide-to-swift-measurement)
  **Published:** `2025-05-07T14:00:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Swift Measurement models units and conversions as typed values rather than ad-hoc multipliers. The guide is useful for diagnosing rounding and presentation errors when domain quantities cross locales, unit systems, or persistence boundaries.
- [Using equatable() to Avoid the NavigationLink Pre-Build Pitfall](https://fatbobman.com/en/posts/using-equatable-to-avoid-the-navigationlink-pre-build-pitfall)
  **Published:** `2025-04-29T14:12:00.000Z`
  **Topics:** Performance · Swift · SwiftUI
  **NeKI brief:** Explains how NavigationLink can pre-build destination views and how equatable() can limit unnecessary work. Use it when diagnosing navigation performance and stabilizing expensive destination construction.
- [Building Type‑Safe, High‑Performance SwiftData / Core Data Models](https://fatbobman.com/en/posts/building-typesafe-highperformance-swiftdata-core-data-models)
  **Published:** `2025-04-23T14:00:00.000Z`
  **Topics:** Core Data · Performance · Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** Explores type-safe, high-performance model design across SwiftData and Core Data, with attention to schema choices and query behavior. Use it when shaping a persistence layer that balances compile-time clarity, migration needs, and runtime performance.
- [My Hopes for Xcode](https://fatbobman.com/en/posts/my-hopes-for-xcode)
  **Published:** `2025-04-16T14:30:00.000Z`
  **Topics:** Xcode
  **NeKI brief:** Argues for six directions in Xcode's evolution, including stronger Swift Package Manager support, better project organization, a more open plugin model, AI tooling, and cloud services.
- [Building WASM Applications with Swift](https://fatbobman.com/en/posts/building-wasm-applications-with-swift)
  **Published:** `2025-04-09T14:30:00.000Z`
  **Topics:** Swift
  **NeKI brief:** Builds a WebAssembly application with Swift and discusses toolchain and platform constraints. Useful for evaluating Swift in browser-hosted environments while separating shared logic from Apple-framework assumptions.
- [Say Goodbye to dismiss - A State-Driven Path to More Maintainable SwiftUI](https://fatbobman.com/en/posts/say-goodbye-to-dismiss)
  **Published:** `2025-04-02T14:12:00.000Z`
  **Topics:** Observation & State Management · Swift · SwiftUI · Testing
  **NeKI brief:** Reframes SwiftUI dismissal as state-driven navigation. Use it when child views imperatively dismiss themselves and ownership of presentation state becomes hard to test or reason about.
- [SwiftUI Environment - @Environment, EnvironmentObject, Custom Values](https://fatbobman.com/en/posts/swiftui-environment-concepts-and-practice)
  **Published:** `2025-03-26T14:12:00.000Z`
  **Topics:** Architecture · Concurrency · Dependency Injection · Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Explains SwiftUI Environment as dependency propagation and value lookup. Use it when shared configuration or services need scoped injection without threading parameters through every intermediate view.
- [Proxyman iOS Debugging - Capture HTTPS and Mock API Responses](https://fatbobman.com/en/posts/using-proxyman-to-intercept-and-simulate-iphone-app-network-requests)
  **Published:** `2025-03-19T14:30:00.000Z`
  **Topics:** Developer Tools
  **NeKI brief:** Shows using Proxyman to capture HTTPS traffic, install certificates, map local responses, and mock APIs. Use it to reproduce network scenarios without changing a production server.
- [SwiftData Limitations - What to Know Before Adopting SwiftData](https://fatbobman.com/en/posts/key-considerations-before-using-swiftdata)
  **Published:** `2025-03-12T14:00:00.000Z`
  **Topics:** Performance · Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** Evaluates SwiftData's practical limits before adoption. Use it when deciding whether its model, migration, query, or synchronization behavior fits a production persistence requirement.
- [Lazy Initialization @State in SwiftUI - Overcoming Premature Object Creation](https://fatbobman.com/en/posts/lazy-initialization-state-in-swiftui)
  **Published:** `2025-03-05T14:12:00.000Z`
  **Topics:** Observation & State Management · Performance · Swift · SwiftUI
  **NeKI brief:** Explains lazy @State initialization for avoiding premature object construction. Use it when a state-owned object is expensive or depends on inputs that should be captured only at the correct lifecycle point.
- [Animatable Protocol - Taming Unruly SwiftUI Animations](https://fatbobman.com/en/posts/animatable-protocol-taming-unruly-swiftui-animation)
  **Published:** `2025-02-26T00:12:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Uses Animatable to control interpolation of custom SwiftUI values. Use it when a complex view animates discontinuously and needs a deliberate animatable-data representation.
- [From Host to Serverless - A Blog Architecture Migration Journey](https://fatbobman.com/en/posts/from-host-to-serverless)
  **Published:** `2025-02-19T14:20:00.000Z`
  **Topics:** Architecture · Performance
  **NeKI brief:** This architecture migration moves a blog from a traditional host toward serverless components, exposing trade-offs in deployment, storage, and operational coupling. Follow it for a concrete checklist when splitting a monolith without losing observability.
- [Mastering SwiftUI Scrolling - Implementing Custom Paging](https://fatbobman.com/en/posts/mastering-swiftui-scrolling-implementing-custom-paging)
  **Published:** `2025-02-12T00:12:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Implements custom SwiftUI paging behavior for scrolling content. Use it when system paging is insufficient and snapping, offsets, and selection state require coordinated control.
- [Why Certain View Modifiers in Swift 6 Cannot Use the @State Property](https://fatbobman.com/en/posts/why-certain-view-modifiers-in-swift-6-cannot-usethe-state-property)
  **Published:** `2024-12-24T00:12:00.000Z`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Explains why Swift 6’s stricter concurrency and MainActor rules reject @State in some SwiftUI view modifiers. Use it to align modifier isolation and resolve issues in alignmentGuide or scrollTransition code.
- [Traps and Countermeasures for Abnormal onAppear Calls in SwiftUI](https://fatbobman.com/en/posts/traps-and-countermeasures-for-abnormal-onappear-calls-in-swiftui)
  **Published:** `2024-12-18T00:12:00.000Z`
  **Topics:** Navigation & Deep Linking · Performance · Swift · SwiftUI
  **NeKI brief:** NavigationStack and TabView can trigger onAppear more often than a screen's visible lifetime suggests, causing duplicate loads or state mutations. The article identifies the triggering structure and offers containment strategies for lifecycle-sensitive work.
- [Model Inheritance in Core Data](https://fatbobman.com/en/posts/model-inheritance-in-core-data)
  **Published:** `2024-12-11T14:00:00.000Z`
  **Topics:** Core Data · Persistence & Synchronisation
  **NeKI brief:** Core Data model inheritance shares attributes through an entity hierarchy, but affects fetches, predicates, and migration shape. This article helps weigh polymorphic convenience against SQL complexity and unexpected inclusion of subtype objects.
- [Typefully - Say Goodbye to the Hassles of Social Media Posting](https://fatbobman.com/en/posts/typefully-say-goodbye-to-the-hassles-of-social-media-posting)
  **Published:** `2024-12-04T00:12:00.000Z`
  **Topics:** Developer Tools
  **NeKI brief:** Typefully's workflow demonstrates composing text editing, scheduling, and service integration into a focused product. Follow it for a concrete example of separating domain actions from platform-specific publishing APIs.
- [Intentional Design or Technical Flaw? The Anomaly of onChange in SwiftUI Multi-Layer Navigation](https://fatbobman.com/en/posts/the-anomaly-of-onchange-in-swiftui-multi-layer-navigation)
  **Published:** `2024-11-27T00:12:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Nested SwiftUI navigation can make onChange observe a value at an unexpected layer or timing, producing apparently contradictory callbacks. The investigation is a useful diagnostic for distinguishing modifier scope from intentional framework behavior.
- [Using Transactions Instead of Save in SwiftData and Core Data](https://fatbobman.com/en/posts/using-transactions-instead-of-save-in-swiftdata-and-core-data)
  **Published:** `2024-11-20T14:00:00.000Z`
  **Topics:** Concurrency · Core Data · Performance · Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** Compares transaction-style persistence work with ordinary save calls in SwiftData and Core Data. Use it when batching mutations, rollback boundaries, and consistency matter more than one-off writes.
- [Understanding SwiftUI's View Update Mechanism - Starting from a TimelineView Update Issue](https://fatbobman.com/en/posts/understanding-swiftui-view-update-mechanism)
  **Published:** `2024-11-13T00:12:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Builds a mental model for SwiftUI body evaluation, dependency tracking, and rendering updates. Useful when investigating redundant recomputation or assuming every state change redraws the entire hierarchy.
- [Mastering Data Tracking and Notifications in Core Data and SwiftData](https://fatbobman.com/en/posts/mastering-data-tracking-and-notifications-in-core-data-and-swiftdata)
  **Published:** `2024-11-06T14:00:00.000Z`
  **Topics:** Core Data · Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** Explores change tracking and notifications in Core Data and SwiftData. Use it when UI or synchronization logic must react to persistence mutations without polling or broad refreshes.
- [Starting with Project Refactoring - Sharing Five Swift Modules](https://fatbobman.com/en/posts/starting-with-project-refactoring-sharing-five-swift-modules)
  **Published:** `2024-10-30T14:00:00.000Z`
  **Topics:** Concurrency · Core Data · Swift
  **NeKI brief:** A refactoring log extracts five Swift modules from an application, exposing boundaries around shared models, utilities, and feature ownership. Follow it for decisions that reduce coupling without turning every file into a package.
- [Comprehensive Guide to Mastering KeyPath in Swift](https://fatbobman.com/en/posts/comprehensive-guide-to-mastering-keypath-in-swift)
  **Published:** `2024-10-23T14:00:00.000Z`
  **Topics:** Macros & Metaprogramming · Performance · Swift
  **NeKI brief:** Explains Swift key paths for typed property access and transformation. Use it when building reusable sorting, binding, observation, or mapping APIs without fragile string identifiers.
- [Reinventing Core Data Development with SwiftData Principles](https://fatbobman.com/en/posts/reinventing-core-data-development-with-swiftdata-principles)
  **Published:** `2024-10-16T14:00:00.000Z`
  **Topics:** Concurrency · Core Data · Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** Examines SwiftData through Core Data's persistence principles, highlighting schema, context, and migration trade-offs. Useful when adopting SwiftData without discarding lessons from mature persistence architecture.
- [UserDefaults and Observation in SwiftUI - How to Achieve Precise Responsiveness](https://fatbobman.com/en/posts/userdefaults-and-observation)
  **Published:** `2024-10-09T14:00:00.000Z`
  **Topics:** Macros & Metaprogramming · Observation & State Management · Persistence & Synchronisation · Swift · SwiftUI
  **NeKI brief:** Observation does not automatically make UserDefaults changes precise inside SwiftUI. The @ObservableDefaults approach bridges key reads and writes into tracked properties, avoiding broad invalidation while retaining UserDefaults persistence semantics.
- [NSManagedObjectID and PersistentIdentifier - Mastering Data Identifiers in Core Data and SwiftData](https://fatbobman.com/en/posts/nsmanagedobjectid-and-persistentidentifier)
  **Published:** `2024-09-25T14:00:00.000Z`
  **Topics:** Concurrency · Core Data · Navigation & Deep Linking · Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** Core Data's NSManagedObjectID and SwiftData's PersistentIdentifier encode object identity differently across stores and contexts. Comparing their lifecycle and URI-style use helps diagnose stale references and choose safe handoff values between persistence layers.
- [Mastering Data Binning with Swift Charts](https://fatbobman.com/en/posts/mastering-data-binning-with-swift-charts)
  **Published:** `2024-09-18T14:00:00.000Z`
  **Topics:** Performance · Swift
  **NeKI brief:** Data binning groups continuous values before charting, trading exact point detail for readable distributions and stable visual scale. The Swift Charts examples provide a concrete route from raw observations to histogram-like summaries.
- [Considerations for Using Codable and Enums in SwiftData Models](https://fatbobman.com/en/posts/considerations-for-using-codable-and-enums-in-swiftdata-models)
  **Published:** `2024-08-14T14:00:00.000Z`
  **Topics:** Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** SwiftData stores Codable structs and enums through generated persistence representations, which affects predicates, migrations, and queryability. The examples expose where convenient model types become opaque storage and when a normalized property is safer.
- [Nested Grid Layout Anomaly - Analysis Approach and Resolution Strategies for SwiftUI Layout Issues](https://fatbobman.com/en/posts/analysis-approach-and-resolution-strategies-for-swiftui-layout-issues)
  **Published:** `2024-08-07T14:12:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Presents a diagnostic workflow for SwiftUI layout problems: reduce the hierarchy, inspect proposed and reported sizes, then test competing explanations. Useful when visual symptoms hide an upstream sizing contract.
- [How to Tile Images in SwiftUI](https://fatbobman.com/en/posts/how-to-tile-images-in-swiftui)
  **Published:** `2024-07-31T14:20:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Builds a tiled image effect by controlling repeat geometry and clipping in SwiftUI. Useful for backgrounds and texture-like surfaces where repeatedly scaling one bitmap would lose the intended visual rhythm.
- [Common Misconceptions About SwiftUI](https://fatbobman.com/en/posts/common-misconceptions-about-swiftui)
  **Published:** `2024-07-24T00:12:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** The article tests popular SwiftUI assumptions against actual identity, layout, and state behavior. Its counterexamples are useful diagnostics when a seemingly reasonable mental model produces duplicate work or unexpected rendering.
- [Developing an Infinite Four-Direction Scrollable Pager with SwiftUI](https://fatbobman.com/en/posts/developing-an-infinite-four-direction-scrollable-pager-with-swiftui)
  **Published:** `2024-07-17T12:20:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Infinite4Pager combines custom gesture arbitration with recentering and coordinate bookkeeping to page indefinitely in four directions. Its trade-offs clarify why ordinary paging containers fail when both axes and unbounded content are required.
- [Techniques for Automatic Merging of String Catalogs in Multi-Package Monorepos](https://fatbobman.com/en/posts/merging-swift-string-catalogs-in-a-multi-package-monorepo)
  **Published:** `2024-07-12T00:12:00.000Z`
  **Topics:** Swift · Swift Package Manager
  **NeKI brief:** A build-phase script gathers String Catalogs emitted by package targets and merges them into the app catalog automatically. This keeps package-local localization ownership while producing one App Store-facing resource without manual synchronization.
- [List or LazyVStack - Choosing the Right Lazy Container in SwiftUI](https://fatbobman.com/en/posts/list-or-lazyvstack)
  **Published:** `2024-07-10T00:12:00.000Z`
  **Topics:** Architecture · Performance · Swift · SwiftUI
  **NeKI brief:** List and LazyVStack both defer row creation, but differ in recycling, platform behavior, system affordances, and measurement costs. The comparison gives a practical choice matrix instead of assuming one lazy container is universally faster.
- [Swifter and Swifty - Mastering the Swift Testing Framework](https://fatbobman.com/en/posts/mastering-the-swift-testing-framework)
  **Published:** `2024-07-03T00:12:00.000Z`
  **Topics:** Swift · Testing
  **NeKI brief:** Swift Testing replaces XCTest's class-and-method conventions with traits, parameterized cases, and expression-based expectations. The walkthrough is valuable for mapping setup, discovery, and failure reporting onto a modern Swift-native test suite.
- [The Evolution of SwiftUI Scroll Control APIs and Highlights from WWDC 2024](https://fatbobman.com/en/posts/the-evolution-of-swiftui-scroll-control-apis)
  **Published:** `2024-06-26T00:12:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** SwiftUI scroll APIs evolved from proxy-based imperative jumps to position, target layout, and visibility-aware control. The timeline clarifies which API fits user-driven scrolling versus state restoration and where older workarounds remain relevant.
- [Creating Stunning Dynamic Text Effects with TextRenderer](https://fatbobman.com/en/posts/creating-stunning-dynamic-text-effects-with-textrender)
  **Published:** `2024-06-19T00:20:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** TextRenderer exposes per-run layout and drawing so SwiftUI text can animate custom effects without replacing the text engine. The techniques help separate typographic measurement from visual decoration when diagnosing clipping or baseline drift.
- [Impressions on WWDC 2024](https://fatbobman.com/en/posts/impressions-on-wwdc-2024)
  **Published:** `2024-06-17T00:12:00.000Z`
  **Topics:** Persistence & Synchronisation · Swift · SwiftData · SwiftUI
  **NeKI brief:** The WWDC24 impressions connect new SwiftUI and platform capabilities to migration concerns, providing community prioritization that should be checked against current SDK documentation.
- [SwiftData in WWDC 2024 - The Revolution Continues, Stability Still Awaits](https://fatbobman.com/en/posts/swiftdata-in-wwdc2024)
  **Published:** `2024-06-12T00:12:00.000Z`
  **Topics:** Macros & Metaprogramming · Performance · Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** WWDC 2024 SwiftData additions promise richer querying and persistence, but practical stability and migration concerns remain. This review helps separate announced API surface from production readiness when planning adoption.
- [Before WWDC 2024 - The Future Potential and Real Challenges of SwiftData](https://fatbobman.com/en/posts/before-wwdc-2024-swiftdata)
  **Published:** `2024-05-29T00:12:00.000Z`
  **Topics:** Performance · Persistence & Synchronisation · Swift · SwiftData · Xcode
  **NeKI brief:** The pre-WWDC survey identifies SwiftData's missing capabilities and rough edges from real projects, turning feature requests into concrete evaluation criteria. Follow it to compare expectations with later framework changes.
- [Before WWDC 2024 - Reviewing Key SwiftUI Upgrades from 2019 to 2023 and Their Impact](https://fatbobman.com/en/posts/before-wwdc-2024)
  **Published:** `2024-05-22T00:12:00.000Z`
  **Topics:** Observation & State Management · Persistence & Synchronisation · Swift · SwiftData · SwiftUI
  **NeKI brief:** The pre-WWDC review traces SwiftUI's accumulated layout, navigation, and observation upgrades, showing which old workarounds became obsolete. It is useful for planning cleanup while keeping deployment-target constraints explicit.
- [What Does spacing = nil Mean in SwiftUI?](https://fatbobman.com/en/posts/spacing-of-swiftui)
  **Published:** `2024-05-15T00:12:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Investigates SwiftUI spacing decisions across stacks and platform defaults, showing why seemingly identical layouts can differ. Useful when tuning rhythm without replacing system spacing with unexplained constants.
- [Mastering the containerRelativeFrame Modifier in SwiftUI](https://fatbobman.com/en/posts/mastering-the-containerrelativeframe-modifier-in-swiftui)
  **Published:** `2024-05-08T00:12:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Examines containerRelativeFrame sizing against the enclosing container rather than the immediate parent. Useful for predictable adaptive cards, paging layouts, and safe-area-aware dimensions.
- [Developing Embedded Applications with Swift](https://fatbobman.com/en/posts/developing-embedded-applications-with-swift)
  **Published:** `2024-05-01T13:30:00.000Z`
  **Topics:** Swift
  **NeKI brief:** Embedded Swift removes much of the runtime and library surface for constrained devices, so code must account for platform availability and resource budgets. This overview helps assess where Swift language ergonomics survive outside Apple application targets.
- [In-Depth Exploration of Overlay and Background Modifiers in SwiftUI](https://fatbobman.com/en/posts/in-depth-exploration-of-overlay-and-background-modifiers-in-swiftui)
  **Published:** `2024-04-25T00:11:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Compares SwiftUI overlay and background modifiers with ZStack, explaining their layout relationships and suitable use cases. Use it when attaching decoration or measuring content while preserving the intended parent-child geometry.
- [Core Data Reform - Achieving Elegant Concurrency Operations like SwiftData](https://fatbobman.com/en/posts/core-data-reform-achieving-elegant-concurrency-operations-like-swiftdata)
  **Published:** `2024-04-18T00:20:00.000Z`
  **Topics:** Concurrency · Core Data · Macros & Metaprogramming · Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** The proposed Core Data reform wraps contexts and queue confinement to approximate SwiftData's actor-oriented access model. It is useful when modernizing legacy persistence while preserving existing stores and managed-object APIs.
- [The @State Specter - Analyzing a Bug in Multi-Window SwiftUI Applications](https://fatbobman.com/en/posts/the-state-specter-analyzing-a-bug-in-multi-window-swiftui-applications)
  **Published:** `2024-04-11T00:12:00.000Z`
  **Topics:** Macros & Metaprogramming · Observation & State Management · Swift · SwiftUI
  **NeKI brief:** A multi-window SwiftUI bug reveals that @State storage and view identity can diverge between scenes. The investigation gives a reproducible way to distinguish scene-local state from shared model ownership.
- [New Frameworks, New Mindset - Unveiling the Observation and SwiftData Frameworks](https://fatbobman.com/en/posts/new-frameworks-new-mindset)
  **Published:** `2024-04-03T00:12:00.000Z`
  **Topics:** Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** Observation and SwiftData replace several established Combine and Core Data habits, but their value depends on understanding new ownership and invalidation rules. This overview is useful for planning migration boundaries instead of mechanically swapping annotations.
- [SwiftUI Views and @MainActor](https://fatbobman.com/en/posts/swiftui-views-and-mainactor)
  **Published:** `2024-03-28T00:12:00.000Z`
  **Topics:** Concurrency · Observation & State Management · Swift · SwiftUI · Xcode
  **NeKI brief:** Explains SwiftUI View isolation and MainActor behavior under modern Swift concurrency. Useful for understanding why view code can interact with UI state safely while model work belongs elsewhere.
- [Practical SwiftData - Building SwiftUI Applications with Modern Approaches](https://fatbobman.com/en/posts/practical-swiftdata-building-swiftui-applications-with-modern-approaches)
  **Published:** `2024-03-21T00:20:00.000Z`
  **Topics:** Architecture · Persistence & Synchronisation · Swift · SwiftData · SwiftUI · Testing
  **NeKI brief:** Examines practical SwiftData application structure, including strict-concurrency challenges, model contexts, and SwiftUI integration. Use it to evaluate persistence boundaries and actor isolation before scaling a data-driven app beyond a demo.
- [Tips and Considerations for Using Lazy Containers in SwiftUI](https://fatbobman.com/en/posts/tips-and-considerations-for-using-lazy-containers-in-swiftui)
  **Published:** `2024-03-14T00:12:00.000Z`
  **Topics:** Performance · Swift · SwiftUI
  **NeKI brief:** Discusses lazy stack and grid creation behavior, identity, measurement, and memory trade-offs. Useful for choosing lazy containers based on workload and avoiding assumptions that off-screen views are never evaluated.
- [How to Dynamically Construct Complex Predicates for SwiftData](https://fatbobman.com/en/posts/how-to-dynamically-construct-complex-predicates-for-swiftdata)
  **Published:** `2024-03-07T00:12:00.000Z`
  **Topics:** Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** Dynamic SwiftData predicates are assembled from optional clauses rather than interpolated strings, preserving type checking while supporting user-selected filters. The patterns help diagnose compiler limitations and keep query composition testable.
- [Swift Predicate - Usage, Composition, and Considerations](https://fatbobman.com/en/posts/swift-predicate-usage-composition-and-considerations)
  **Published:** `2024-02-29T00:12:00.000Z`
  **Topics:** Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** Swift Predicate composes typed expressions that can be reused across SwiftData and related APIs, but closure syntax and supported operations are constrained. Follow it to identify expressive boundaries before designing a dynamic query DSL.
- [How to Handle Optional Values in SwiftData Predicates](https://fatbobman.com/en/posts/how-to-handle-optional-values-in-swiftdata-predicates)
  **Published:** `2024-02-22T00:12:00.000Z`
  **Topics:** Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** Optional values in SwiftData predicates require explicit comparisons and careful optional promotion, otherwise valid-looking expressions fail to compile or match unexpectedly. The examples provide focused remedies for nullable filters.
- [Exploring Property Wrappers in SwiftUI - @UIApplicationDelegateAdaptor, @AccessibilityFocusState, @FocusedObject, @FocusedValue, and @FocusedBinding](https://fatbobman.com/en/posts/exploring-swiftui-property-wrappers-4)
  **Published:** `2024-02-07T04:00:00.000Z`
  **Topics:** Accessibility · Observation & State Management · Swift · SwiftUI · UIKit
  **NeKI brief:** Explains @AccessibilityFocusState for binding SwiftUI state to the element VoiceOver should focus, alongside related focus wrappers. The mechanism is useful after navigation or validation when focus must move deliberately.
- [Exploring SwiftUI Property Wrappers - @FetchRequest, @SectionedFetchRequest, @Query, @Namespace, @Bindable](https://fatbobman.com/en/posts/exploring-swiftui-property-wrappers-3)
  **Published:** `2024-02-01T04:00:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** FetchRequest, SectionedFetchRequest, Query, Namespace, and Bindable each connect a view to data or identity differently. The comparison helps choose wrappers by lifetime and mutation direction instead of by superficial syntax.
- [Exploring SwiftUI Property Wrappers - @AppStorage, @SceneStorage, @FocusState, @GestureState and @ScaledMetric](https://fatbobman.com/en/posts/exploring-swiftui-property-wrappers-2)
  **Published:** `2024-01-25T04:00:00.000Z`
  **Topics:** Persistence & Synchronisation · Swift · SwiftUI
  **NeKI brief:** AppStorage, SceneStorage, FocusState, GestureState, and ScaledMetric each bind a different kind of transient or persisted value to SwiftUI. Comparing their lifetimes helps diagnose state restoration, focus loss, and gesture-reset bugs.
- [SwiftData Relationships - @Relationship, Inverse, One-to-Many](https://fatbobman.com/en/posts/relationships-in-swiftdata-changes-and-considerations)
  **Published:** `2024-01-18T00:12:00.000Z`
  **Topics:** Core Data · Performance · Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** SwiftData relationships infer inverses and delete behavior from model declarations, yet optionality and initialization still affect generated schema. The article helps diagnose unexpected relationship mutations and choose explicit @Relationship settings.
- [Mastering Relationships in Core Data - Practical Application](https://fatbobman.com/en/posts/mastering-relationships-in-core-data-practical)
  **Published:** `2024-01-11T00:12:00.000Z`
  **Topics:** Core Data · Persistence & Synchronisation · Swift
  **NeKI brief:** Practical Core Data relationships cover inverse maintenance, delete rules, and fetch behavior under real object graphs. Follow it when a model appears correct but cascades or faulting produce surprising runtime results.
- [Mastering Relationships in Core Data - Fundamentals](https://fatbobman.com/en/posts/mastering-relationships-in-core-data-fundamentals)
  **Published:** `2024-01-04T00:12:00.000Z`
  **Topics:** Core Data · Persistence & Synchronisation
  **NeKI brief:** Core Data relationship fundamentals explain cardinality, inverses, and object-graph consistency before application-specific code complicates the picture. It is a useful schema-design reference for preventing invalid graph states.
- [Blog Update Chronicle - Welcoming 2024 with a New Blog](https://fatbobman.com/en/posts/blog-update-chronicle-2024)
  **Published:** `2023-12-28T00:20:00.000Z`
  **Topics:** Developer Community & Business
  **NeKI brief:** A blog maintenance chronicle records content and tooling changes as operational work, useful for understanding how a technical knowledge base stays current across releases.
- [Exploring Key Property Wrappers in SwiftUI - @State, @Binding, @StateObject, @ObservedObject, @EnvironmentObject, and @Environment](https://fatbobman.com/en/posts/exploring-key-property-wrappers-in-swiftui)
  **Published:** `2023-12-21T04:00:00.000Z`
  **Topics:** Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Comparing State, Binding, StateObject, ObservedObject, and EnvironmentObject by ownership and lifetime clarifies which wrapper should create or merely receive reference state. Follow it when view recreation causes lost data or duplicate models.
- [Advanced iCloud Documents - Understanding Placeholder Files, Space Optimization, and Operational Techniques](https://fatbobman.com/en/posts/advanced-icloud-documents)
  **Published:** `2023-12-14T00:11:00.000Z`
  **Topics:** Persistence & Synchronisation
  **NeKI brief:** Advanced iCloud Documents distinguishes placeholder files, coordinated downloads, and storage optimization from ordinary local file I/O. The operational techniques are useful when diagnosing missing-content races and keeping document packages responsive under space pressure.
- [In-Depth Guide to iCloud Documents - Fundamental Setup and File Operations](https://fatbobman.com/en/posts/in-depth-guide-to-icloud-documents)
  **Published:** `2023-12-07T00:11:00.000Z`
  **Topics:** Navigation & Deep Linking
  **NeKI brief:** The iCloud Documents guide traces container setup, file coordination, and ubiquitous-document operations from first principles. It helps diagnose synchronization races by separating local URL handling from cloud availability and metadata.
- [SwiftUI geometryGroup() Guide - From Theory to Practice](https://fatbobman.com/en/posts/mastring-geometrygroup)
  **Published:** `2023-11-30T00:12:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** geometryGroup isolates a subtree's geometry before animation, changing how SwiftUI interpolates nested layout and transforms. The experiments are useful for explaining why a complex transition warps differently when geometry is grouped.
- [Pair Programming with AI](https://fatbobman.com/en/posts/pari-programming-with-ai)
  **Published:** `2023-11-23T00:12:00.000Z`
  **Topics:** AI Development
  **NeKI brief:** Describes rebuilding a blog with ChatGPT, Copilot, and Claude as collaborative programming tools while learning unfamiliar technologies. Use it to examine task decomposition and verification habits, not to infer production-level model reliability.
- [Mastering ViewThatFits](https://fatbobman.com/en/posts/mastering-viewthatfits)
  **Published:** `2023-11-16T00:12:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** ViewThatFits evaluates child alternatives against the proposed size and selects the first fitting result, making fallback layouts data-driven. The guide highlights proposal and priority details that matter when compact designs unexpectedly win.
- [GeometryReader - Blessing or Curse?](https://fatbobman.com/en/posts/geometryreader-blessing-or-curse)
  **Published:** `2023-11-09T00:20:00.000Z`
  **Topics:** Performance · Swift · SwiftUI
  **NeKI brief:** GeometryReader expands to its proposal and reports container coordinates, which can create feedback loops or surprising flexible layouts. This analysis is a practical diagnostic for deciding when preference keys or custom Layout are safer.
- [How to Observe Data Changes in SwiftData using Persistent History Tracking](https://fatbobman.com/en/posts/persistent-history-tracking-in-swiftdata)
  **Published:** `2023-11-02T00:12:00.000Z`
  **Topics:** Core Data · Persistence & Synchronisation · Swift · SwiftData · Testing
  **NeKI brief:** SwiftData persistent history exposes transactions from the same store, including widgets and batch work, so a client can react selectively instead of treating every save alike. The article shows filtering, replay, and tests for deterministic change handling.
- [Mastering TipKit - Advanced](https://fatbobman.com/en/posts/mastering-tipkit-advance)
  **Published:** `2023-10-25T00:12:00.000Z`
  **Topics:** UIKit
  **NeKI brief:** TipKit's advanced rules combine parameterized eligibility, event donation, invalidation, and display policy. The article is useful for diagnosing why a contextual tip remains hidden or reappears after seemingly successful user education.
- [Mastering TipKit - Basics](https://fatbobman.com/en/posts/mastering-tipkit-basic)
  **Published:** `2023-10-18T00:12:00.000Z`
  **Topics:** Swift · SwiftUI · Testing
  **NeKI brief:** TipKit combines eligibility rules, display events, and persistent tip state to control contextual education. The basics explain where configuration and donation timing belong, useful for avoiding tips that appear too early or never qualify.
- [Concurrent Programming in SwiftData](https://fatbobman.com/en/posts/concurret-programming-in-swiftdata)
  **Published:** `2023-10-11T00:20:00.000Z`
  **Topics:** Concurrency · Core Data · Macros & Metaprogramming · Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** SwiftData's ModelActor-backed serial executor provides a safer concurrency boundary than ad-hoc Core Data queue usage, but context ownership still matters. The discussion helps diagnose cross-actor model access and design explicit read/write entry points.
- [Unveiling the Data Modeling Principles of SwiftData](https://fatbobman.com/en/posts/unveiling-the-data-modeling-principles-of-swiftdata)
  **Published:** `2023-10-07T00:12:00.000Z`
  **Topics:** Core Data · Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** SwiftData's code-first models still encode schema decisions around identity, optionality, relationships, and value storage. The modeling principles help predict migration and query consequences before decorators harden an application's persistence design.
- [Exploring CoreData - From Data Model Creation to Managed Object Instances](https://fatbobman.com/en/posts/from-data-model-construction-to-managed-object-instances-in-core-data)
  **Published:** `2023-09-19T00:20:00.000Z`
  **Topics:** Core Data · Persistence & Synchronisation · Xcode
  **NeKI brief:** Core Data's model, coordinator, context, and managed-object layers form a lifecycle pipeline rather than a single database API. Tracing those boundaries helps diagnose context faults, unsaved changes, and object access on the wrong queue.
- [SwiftDataKit - Unleashing Advanced Core Data Features in SwiftData](https://fatbobman.com/en/posts/use-core-data-features-in-swiftdata-by-swiftdatakit)
  **Published:** `2023-09-07T00:12:00.000Z`
  **Topics:** Core Data · Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** SwiftDataKit exposes selected Core Data capabilities behind SwiftData models, allowing advanced store features without abandoning the newer declaration style. Follow it to weigh compatibility benefits against dependency and abstraction leakage.
- [Common Pitfalls Caused by Delayed State Updates in SwiftUI](https://fatbobman.com/en/posts/serious-issues-caused-by-delayed-state-updates-in-swiftui)
  **Published:** `2023-08-30T00:12:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Delayed SwiftUI state propagation can make a view render from stale values while actions already assume the new state. The investigation offers timing-focused diagnostics for distinguishing transaction scheduling from incorrect source-of-truth ownership.
- [WWDC 2023, What’s New in Core Data](https://fatbobman.com/en/posts/what-s-new-in-core-data-in-wwdc23)
  **Published:** `2023-07-04T00:12:00.000Z`
  **Topics:** Core Data · Persistence & Synchronisation · Swift
  **NeKI brief:** The WWDC 2023 Core Data review maps new capabilities to existing store and context constraints. Follow it when deciding whether an announced API removes a workaround or merely changes where complexity lives.
- [The Secret to Flawless SwiftUI Animations - A Deep Dive into Transactions](https://fatbobman.com/en/posts/mastering-transaction)
  **Published:** `2023-06-27T00:12:00.000Z`
  **Topics:** Swift · SwiftUI · Testing
  **NeKI brief:** SwiftUI transactions carry animation intent through the update tree, distinguishing implicit from explicit animation and allowing local overrides. Tracing transaction propagation is a practical way to explain animations that unexpectedly start, stop, or use the wrong curve.
- [A Deep Dive Into Observation - A New Way to Boost SwiftUI Performance](https://fatbobman.com/en/posts/mastering-observation)
  **Published:** `2023-06-19T00:12:00.000Z`
  **Topics:** Observation & State Management · Performance · Swift · SwiftUI
  **NeKI brief:** The Observation framework records which properties a view actually reads, narrowing invalidations compared with object-wide KVO or Combine updates. The Q&A format is useful for understanding registrar behavior, nested models, and performance limits before adopting @Observable.
- [SwiftUI ScrollView - scrollPosition, scrollTargetLayout, contentMargins](https://fatbobman.com/en/posts/new-features-of-scrollview-in-swiftui5)
  **Published:** `2023-06-13T00:12:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** scrollPosition, scrollTargetLayout, and contentMargins separate scroll identity, target alignment, and inset policy in SwiftUI 5. The examples provide a modern replacement map for proxy-only scrolling and layout hacks.
- [WWDC 23, First Impressions of SwiftUI 5 and SwiftData](https://fatbobman.com/en/posts/impressions-of-wwdc23)
  **Published:** `2023-06-09T00:12:00.000Z`
  **Topics:** Persistence & Synchronisation · Swift · SwiftData · SwiftUI
  **NeKI brief:** Summarizes the SwiftUI 5 and SwiftData changes announced at WWDC 2023, especially Observation-based property tracking, animation, visual effects, and persistence. Use it as historical release context, verifying exact availability and migration details with Apple documentation.
- [Five Years Since the Transplant](https://fatbobman.com/en/posts/5th-anniversary-of-kidney-transplant)
  **Published:** `2023-05-31T00:20:00.000Z`
  **Topics:** Health Apps
  **NeKI brief:** The anniversary essay is personal rather than technical, but its account of long-term recovery offers context on how lived constraints shape sustainable project and work decisions.
- [Building Stable Preview Views - How SwiftUI Previews Work](https://fatbobman.com/en/posts/how-swiftui-preview-works)
  **Published:** `2023-05-23T00:12:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** SwiftUI previews construct and rerender view instances in a special host, so state, dependencies, and side effects need deliberate isolation. This guide helps diagnose preview-only failures and build stable fixtures rather than production workarounds.
- [Building Cross-Platform SwiftUI Apps](https://fatbobman.com/en/posts/building-multiple-platforms-swiftui-app)
  **Published:** `2023-04-25T00:11:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Cross-platform SwiftUI composition shares view code while platform availability, navigation, and input conventions still diverge. The guide is useful for locating conditional boundaries without forcing identical UX across devices.
- [AI Services that I am Currently Using](https://fatbobman.com/en/posts/ai-services-i-am-currently-using)
  **Published:** `2023-04-11T00:12:00.000Z`
  **Topics:** AI Development
  **NeKI brief:** Reviews a personal mix of Copilot for Xcode, Notion AI, Warp AI, MidJourney, and ChatGPT. Use it to compare tool roles across coding, writing, terminal work, and media, while treating preferences as anecdotal.
- [Timing of onAppear Invocation](https://fatbobman.com/en/posts/onappear-call-timing)
  **Published:** `2023-03-29T00:12:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Experiments around onAppear timing show that construction, insertion, and visibility are separate lifecycle events in SwiftUI. Use the results to place work in the right hook and avoid treating appearance as a one-time initializer.
- [MacBook Pro Usage Experience](https://fatbobman.com/en/posts/experience_of_macbook_pro)
  **Published:** `2023-03-15T04:00:00.000Z`
  **Topics:** Performance
  **NeKI brief:** A MacBook Pro experience report connects hardware choices to development workflow and simulator performance, offering practical context rather than universal purchasing advice.
- [Memory Optimization Journey for a SwiftUI + Core Data App](https://fatbobman.com/en/posts/memory-usage-optimization)
  **Published:** `2023-03-08T00:20:00.000Z`
  **Topics:** Core Data · Performance · Persistence & Synchronisation · Swift · SwiftUI
  **NeKI brief:** A SwiftUI and Core Data memory investigation correlates object graph retention, fetch size, and view updates with measured footprint. It offers a concrete route from Instruments evidence to targeted reductions rather than speculative cleanup.
- [Layout in SwiftUI Way](https://fatbobman.com/en/posts/layout-in-swiftui-way)
  **Published:** `2023-03-01T00:12:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** The article explains SwiftUI layout as proposal, measurement, and placement, helping custom containers avoid fixed-size assumptions and feedback loops.
- [Cracking the Code - The Mysterious @State Injection Mechanism](https://fatbobman.com/en/posts/bug-code-by-state-inject)
  **Published:** `2023-02-23T00:20:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** SwiftUI injects State storage into view instances in ways that can make an apparently immutable struct hold persistent state. The investigation provides a route to reproduce and explain multi-window state anomalies.
- [Customizing the Appearance and Interaction Behavior of Buttons](https://fatbobman.com/en/posts/custom-button-style-in-swiftui)
  **Published:** `2023-02-16T00:12:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** ButtonStyle centralizes appearance and interaction behavior while preserving Button's semantics and accessibility. The examples help avoid gesture-based replacements that lose keyboard activation, hit testing, or pressed-state propagation.
- [SwiftUI and Core Data - Safely Responding to Data](https://fatbobman.com/en/posts/modern-core-data-respond-data-safely)
  **Published:** `2022-12-13T00:20:00.000Z`
  **Topics:** Core Data · Persistence & Synchronisation · Swift · SwiftUI
  **NeKI brief:** Safely responding to Core Data changes in SwiftUI means separating context notifications from view-facing state and avoiding direct cross-queue object use. The patterns keep updates coherent without broad refetching.
- [SwiftUI and Core Data - Data Fetching](https://fatbobman.com/en/posts/modern-core-data-fetcher)
  **Published:** `2022-12-06T00:20:00.000Z`
  **Topics:** Core Data · Persistence & Synchronisation · Swift · SwiftUI · Testing
  **NeKI brief:** A dedicated Core Data fetcher separates request construction, context access, and published results, making asynchronous data loading explicit. Follow it when view code has become entangled with fetch timing and cancellation.
- [SwiftUI and Core Data - Data Definition](https://fatbobman.com/en/posts/modern-core-data-data-definition)
  **Published:** `2022-11-29T00:20:00.000Z`
  **Topics:** Core Data · Persistence & Synchronisation · Swift · SwiftUI · Testing
  **NeKI brief:** Core Data data definition in a SwiftUI app establishes entities, identity, and optionality before view observation begins. The guide helps prevent model shortcuts that later complicate predicates, migrations, and bindings.
- [SwiftUI and Core Data - The Challenges](https://fatbobman.com/en/posts/modern-core-data-problem)
  **Published:** `2022-11-22T00:20:00.000Z`
  **Topics:** Concurrency · Core Data · Persistence & Synchronisation · Swift · SwiftUI · Testing
  **NeKI brief:** Using Core Data from SwiftUI exposes friction around context confinement, change propagation, and generated object lifetimes. The problem analysis is useful for choosing explicit boundaries before adding observation or convenience wrappers.
- [Adaptive Programmatic Navigation in SwiftUI](https://fatbobman.com/en/posts/adaptive-navigation-scheme)
  **Published:** `2022-11-15T00:20:00.000Z`
  **Topics:** Navigation & Deep Linking · Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Adaptive programmatic navigation coordinates selection state with different navigation containers and size classes. The design is useful for preventing push, split-view, and restoration paths from drifting into separate sources of truth.
- [Ask Apple 2022 Q&A Related to SwiftUI (Part 2)](https://fatbobman.com/en/posts/swiftui-of-ask-apple-2022-2)
  **Published:** `2022-11-01T00:12:00.000Z`
  **Topics:** Performance · Swift · SwiftUI
  **NeKI brief:** Ask Apple SwiftUI answers collect framework-team guidance on lifecycle, layout, and data flow edge cases. Use this historical source to test a workaround's assumptions before treating it as a durable API contract.
- [Ask Apple 2022 Q&A Related to SwiftUI (Part 1)](https://fatbobman.com/en/posts/swiftui-of-ask-apple-2022-1)
  **Published:** `2022-10-27T00:12:00.000Z`
  **Topics:** Swift · SwiftUI · Testing
  **NeKI brief:** Ask Apple SwiftUI answers capture framework guidance on layout, state, and navigation directly from engineers, including limitations often absent from API signatures. Use it as historical context before applying a workaround.
- [Ask Apple 2022 Q&A Related on Core Data (Part 2)](https://fatbobman.com/en/posts/core-data-of-ask-apple-2022-2)
  **Published:** `2022-10-24T00:12:00.000Z`
  **Topics:** App Intents & System Surfaces · Core Data · Persistence & Synchronisation
  **NeKI brief:** Ask Apple Core Data answers address practical concurrency and persistence questions that surface beyond introductory samples. Follow it to compare an app's context rules with documented framework-team reasoning.
- [Ask Apple 2022 Q&A Related on Core Data (Part 1)](https://fatbobman.com/en/posts/core-data-of-ask-apple-2022)
  **Published:** `2022-10-20T04:12:00.000Z`
  **Topics:** Core Data · Persistence & Synchronisation
  **NeKI brief:** Ask Apple Core Data answers expose practical guidance on contexts, concurrency, and migration boundaries. Follow it to compare community assumptions with framework-team explanations of what the stack guarantees.
- [The Composable Architecture (TCA)](https://fatbobman.com/en/posts/the_composable_architecture)
  **Published:** `2022-10-18T00:12:00.000Z`
  **Topics:** Architecture · Composable Architecture · Swift · SwiftUI
  **NeKI brief:** The Composable Architecture separates state, actions, reducers, and effects, making feature behavior testable and composable. Follow it to evaluate explicit data flow against the ceremony and dependency management it introduces.
- [SwiftUI’s StateObject and ObservedObject - The Key Differences](https://fatbobman.com/en/posts/stateobject_and_observedobject)
  **Published:** `2022-10-11T00:12:00.000Z`
  **Topics:** Observation & State Management · Swift · SwiftUI
  **NeKI brief:** StateObject owns and preserves an observable reference across view recreation, while ObservedObject observes one supplied by another owner. The distinction is a direct diagnostic for duplicate initialization and unexpectedly reset SwiftUI models.
- [Reflections on iBug 16](https://fatbobman.com/en/posts/ibug16)
  **Published:** `2022-09-27T00:12:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** The iBug16 reflections connect developer tooling and platform changes to day-to-day SwiftUI practice. It is useful historical routing for understanding why certain APIs and migration priorities emerged.
- [Some Suitable Tutorials for SwiftUI Beginners](https://fatbobman.com/en/posts/turorials_for_swiftui_beginners)
  **Published:** `2022-09-20T00:12:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** The beginner tutorial collection routes readers through state, layout, navigation, and data flow in increasing complexity. It is useful for identifying foundational gaps before adopting advanced SwiftUI abstractions.
- [How to Determine if ScrollView, List is Currently Scrolling in SwiftUI](https://fatbobman.com/en/posts/how_to_judge_scrollview_is_scrolling)
  **Published:** `2022-09-13T00:12:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Determining whether a SwiftUI ScrollView is actively scrolling requires observing geometry or gesture-linked state rather than reading a built-in boolean. The techniques help gate expensive work and diagnose scroll-dependent UI timing.
- [Old Man New Soldier - A Development Memoir of an iOS APP](https://fatbobman.com/en/posts/healthnote_development_log_2020)
  **Published:** `2022-09-06T00:12:00.000Z`
  **Topics:** Core Data · Persistence & Synchronisation · Swift · SwiftUI
  **NeKI brief:** The HealthNote development log exposes product and implementation decisions in a real health-data app, including persistence and feature scope. Follow it for practical trade-offs around privacy-sensitive user workflows.
- [Several Ways to Center Views in SwiftUI](https://fatbobman.com/en/posts/centering_the_view_in_swiftui)
  **Published:** `2022-08-30T00:20:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Several SwiftUI centering strategies expose different proposal and alignment behavior, from frame expansion to custom alignment guides. Comparing them helps avoid geometry hacks that break when content or device size changes.
- [Implementing Keyword-based Search and Positioning in SwiftUI Text](https://fatbobman.com/en/posts/search_and_location_in_text)
  **Published:** `2022-08-23T00:12:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Keyword highlighting and positioning in SwiftUI Text combines string range calculation with attributed rendering and layout coordinates. The approach is useful for search results that must both emphasize matches and scroll to them.
- [Mixing Text and Image in SwiftUI](https://fatbobman.com/en/posts/mixing_text_and_graphics_with_text_in_swiftui)
  **Published:** `2022-08-16T00:12:00.000Z`
  **Topics:** Accessibility · Swift · SwiftUI
  **NeKI brief:** Compares techniques for embedding images and graphics inside SwiftUI Text, including the newer TextRenderer approach. Follow it when inline imagery must retain predictable text layout and an intentional accessibility interpretation.
- [Mastering the SwiftUI task Modifier](https://fatbobman.com/en/posts/mastering_swiftui_task_modifier)
  **Published:** `2022-08-09T00:12:00.000Z`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** The task modifier ties asynchronous work to view identity and cancellation, so changing an id can restart a task while removal cancels it. Follow it when diagnosing duplicate loads or stale network results.
- [How to Avoid Repeating SwiftUI View Updates](https://fatbobman.com/en/posts/avoid_repeated_calculations_of_swiftui_views)
  **Published:** `2022-08-02T00:20:00.000Z`
  **Topics:** Performance · Swift · SwiftUI
  **NeKI brief:** Repeated SwiftUI calculations often come from expensive work inside body evaluation rather than excessive rendering alone. The article separates derived data, memoization, and dependency scope to make performance fixes measurable.
- [Switching Core Data Cloud Sync Status in Real-Time](https://fatbobman.com/en/posts/real-time-switching-of-cloud-syncs-status)
  **Published:** `2022-07-26T00:12:00.000Z`
  **Topics:** Core Data · Persistence & Synchronisation
  **NeKI brief:** Switching Core Data CloudKit synchronization at runtime requires coordinating store options, persistent containers, and existing contexts. The workflow is useful for diagnosing stale stores and deciding when a controlled rebuild is safer.
- [SwiftUI Layout - Cracking the Size Code](https://fatbobman.com/en/posts/layout-dimensions-2)
  **Published:** `2022-07-19T00:11:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** SwiftUI layout dimensions are determined through proposal, measurement, and placement, with modifiers changing which phase sees a value. The experiments are useful for explaining flexible views that ignore an apparent frame.
- [SwiftUI Layout - The Mystery of Size](https://fatbobman.com/en/posts/layout-dimensions-1)
  **Published:** `2022-07-12T00:11:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** SwiftUI's proposed size and ideal dimensions explain why fixed frames, intrinsic content, and flexible containers interact unexpectedly. The experiments provide a foundation for debugging layout before adding alignment hacks.
- [Alignment in SwiftUI - Everything You Need to Know](https://fatbobman.com/en/posts/layout-alignment)
  **Published:** `2022-07-05T00:11:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Alignment guides let sibling views share a custom coordinate without hard-coded offsets. The guide shows how alignment propagation works through containers, making it a practical alternative to geometry-based positioning.
- [Creating Tables with Table in SwiftUI](https://fatbobman.com/en/posts/table_in_swiftui)
  **Published:** `2022-06-22T00:20:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** SwiftUI Table separates column definitions, row identity, and platform-specific presentation, especially on macOS. Follow it when building sortable tabular data without forcing a List layout onto desktop interactions.
- [Deep Dive into Modern SwiftUI Navigation - NavigationStack and NavigationSplitView](https://fatbobman.com/en/posts/new_navigator_of_swiftui_4)
  **Published:** `2022-06-14T00:12:00.000Z`
  **Topics:** Navigation & Deep Linking · Swift · SwiftUI
  **NeKI brief:** NavigationStack and NavigationSplitView model destinations as data, enabling deep links and restoration across adaptive layouts. The article helps separate route state from presentation mechanics when supporting phone and split-view navigation.
- [Batch Operations in Core Data](https://fatbobman.com/en/posts/batchprocessingincoredata)
  **Published:** `2022-06-06T00:20:00.000Z`
  **Topics:** Core Data · Persistence & Synchronisation
  **NeKI brief:** Core Data batch inserts, updates, and deletes operate at the store level, so managed object contexts do not automatically see every change. The guide highlights merge and refresh steps needed for coherent UI state.
- [How Core Data Saves Data in SQLite](https://fatbobman.com/en/posts/tables_and_fields_of_coredata)
  **Published:** `2022-05-31T00:20:00.000Z`
  **Topics:** Core Data · Persistence & Synchronisation
  **NeKI brief:** Core Data's SQLite representation uses tables and fields that reflect entities, attributes, and internal metadata rather than a hand-designed schema. Inspecting it is useful for diagnosing migration and fetch-performance surprises.
- [Best Practices for Detecting and Opening URLs in SwiftUI](https://fatbobman.com/en/posts/open_url_in_swiftui)
  **Published:** `2022-05-24T00:12:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** SwiftUI's OpenURLAction lets views intercept and route URL activation through environment-driven behavior. The pattern helps centralize deep-link policy while preserving platform link semantics and testable fallbacks.
- [Going Beyond @Published -Empowering Custom Property Wrappers](https://fatbobman.com/en/posts/adding-published-ability-to-custom-property-wrapper-types)
  **Published:** `2022-05-17T00:20:00.000Z`
  **Topics:** Persistence & Synchronisation · Swift
  **NeKI brief:** Custom property wrappers can expose projected observation while retaining specialized storage behavior. The article explains the forwarding and mutation contracts needed to avoid wrappers that appear reactive but never invalidate views.
- [SwiftUI Animation - .animation, withAnimation, and AnimatableData](https://fatbobman.com/en/posts/the_animation_mechanism_of_swiftui)
  **Published:** `2022-05-10T00:20:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** SwiftUI animation distinguishes implicit modifiers, withAnimation transactions, and AnimatableData interpolation. Following value propagation explains why unrelated state changes animate and how custom shapes can define their own interpolation.
- [Demystifying SwiftUI List Responsiveness - Best Practices for Large Datasets](https://fatbobman.com/en/posts/optimize_the_response_efficiency_of_list)
  **Published:** `2022-04-26T00:12:00.000Z`
  **Topics:** Performance · Swift · SwiftUI
  **NeKI brief:** Large SwiftUI Lists become responsive when identity, row work, fetch strategy, and update scope are controlled together. The optimization guidance links measured scroll latency to concrete data and view changes.
- [Mastering zIndex in SwiftUI](https://fatbobman.com/en/posts/zindex)
  **Published:** `2022-04-19T00:12:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** SwiftUI zIndex changes draw order without changing layout order or view hierarchy ownership. The examples help diagnose overlays that look correct but still receive gestures or accessibility focus unexpectedly.
- [ViewBuilder Research - Creating a ViewBuilder Imitation](https://fatbobman.com/en/posts/viewbuilder2)
  **Published:** `2022-04-12T00:20:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** The second ViewBuilder exploration examines builder limits and composition strategies when branches become large. It is useful for choosing extracted views or helper builders without obscuring state dependencies.
- [ViewBuilder Research - Mastering Result Builders](https://fatbobman.com/en/posts/viewbuilder1)
  **Published:** `2022-04-06T00:20:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** ViewBuilder constructs heterogeneous conditional view content through result-builder transformations, which affects type shape and identity. The article helps explain compiler errors and update behavior in complex declarative branches.
- [SwiftUI Overlay Container 2 - Customizable, Efficient, and Convenient View Manager](https://fatbobman.com/en/posts/swiftuioverlaycontainer2)
  **Published:** `2022-03-20T09:20:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Overlay containers in SwiftUI coordinate layered content, hit testing, and presentation state without forcing navigation changes. The article helps diagnose z-order conflicts and choose a contained overlay architecture.
- [Count Queries in Core Data - The Master Guide](https://fatbobman.com/en/posts/countincoredata)
  **Published:** `2022-01-17T00:12:00.000Z`
  **Topics:** Core Data · Persistence & Synchronisation
  **NeKI brief:** Counting Core Data records efficiently uses store-side requests instead of fetching full managed objects. The guidance is useful for dashboards and validation paths where memory use and faulting matter.
- [SwiftUI Gestures - DragGesture, Tap Location, and UIKit Bridge](https://fatbobman.com/en/posts/swiftuigesture)
  **Published:** `2022-01-10T00:12:00.000Z`
  **Topics:** Swift · SwiftUI · UIKit
  **NeKI brief:** SwiftUI gestures compose recognition, state, priority, and simultaneous behavior through modifiers rather than imperative delegates. The article is useful for diagnosing conflicts between taps, drags, and container scrolling.
- [Exploring Xcode Playground (Part 2)](https://fatbobman.com/en/posts/xcodeplayground2)
  **Published:** `2021-12-31T00:12:00.000Z`
  **Topics:** Testing · Xcode
  **NeKI brief:** Xcode Playground techniques use small executable experiments to isolate framework behavior, while acknowledging their runtime differs from a full app. Follow it to reduce a layout or language question before changing production code.
- [Exploring Xcode Playground (Part 1)](https://fatbobman.com/en/posts/xcodeplayground1)
  **Published:** `2021-12-27T00:12:00.000Z`
  **Topics:** Concurrency · Xcode
  **NeKI brief:** Xcode Playgrounds isolate experiments with immediate execution and visual feedback, but their runtime differs from a full app target. Follow it for testing language or framework behavior before extrapolating to production lifecycle conditions.
- [Swift Playgrounds 4 - Entertainment or Productivity](https://fatbobman.com/en/posts/swiftplaygrounds4)
  **Published:** `2021-12-20T00:10:00.000Z`
  **Topics:** Swift
  **NeKI brief:** Swift Playgrounds experiments provide a fast feedback loop for Swift and UI ideas, but sandboxed lifecycle and dependencies limit equivalence with an app target. The guidance helps keep experiments evidential.
- [Using NSUbiquitousKeyValueStore with SwiftUI](https://fatbobman.com/en/posts/nsubiquitouskeyvaluestore)
  **Published:** `2021-12-13T00:12:00.000Z`
  **Topics:** Observation & State Management · Persistence & Synchronisation · Swift · SwiftUI
  **NeKI brief:** NSUbiquitousKeyValueStore synchronizes small preference values through iCloud, with asynchronous updates and conflict considerations. Follow it when deciding whether lightweight cross-device settings belong here or in document/database sync.
- [Collaboration between Combine and async/await](https://fatbobman.com/en/posts/combineandasync)
  **Published:** `2021-12-06T00:12:00.000Z`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Combine and async/await solve overlapping asynchronous coordination problems but differ in cancellation, streams, and composition. The comparison helps select a boundary rather than mixing models until ownership becomes unclear.
- [Lifecycle of SwiftUI Views](https://fatbobman.com/en/posts/swiftuilifecycle)
  **Published:** `2021-11-28T00:12:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** SwiftUI's app lifecycle replaces delegate-centric startup with scenes and declarative state, while some system callbacks remain imperative. The article helps map legacy app responsibilities onto the new lifecycle without losing initialization control.
- [SwiftUI Safe Area - safeAreaInset, SafeAreaInsets, and ignoresSafeArea](https://fatbobman.com/en/posts/safearea)
  **Published:** `2021-11-22T00:12:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** SwiftUI safe-area behavior depends on container proposals, ignoresSafeArea placement, and system overlays. The experiments help diagnose controls that are clipped or unexpectedly inset after navigation and keyboard changes.
- [How to Deep Copy NSManagedObject in Core Data](https://fatbobman.com/en/posts/mocloner)
  **Published:** `2021-11-15T00:10:00.000Z`
  **Topics:** Core Data · Persistence & Synchronisation
  **NeKI brief:** Cloning NSManagedObjects requires copying attributes and rebuilding relationships without carrying a source object's identity or context assumptions. The workflow is useful for templates, drafts, and safe duplication in Core Data.
- [Implementing iOS Notes' Document Scanning Feature with Apple's Official API](https://fatbobman.com/en/posts/docscaner)
  **Published:** `2021-11-10T00:20:00.000Z`
  **Topics:** App Intents & System Surfaces
  **NeKI brief:** A document-scanner implementation combines VisionKit capture with image processing and persistence boundaries. Follow it when evaluating where camera UI ends and app-owned recognition or storage begins.
- [Several Tips on Core Data Concurrency Programming](https://fatbobman.com/en/posts/concurrencyofcoredata)
  **Published:** `2021-11-05T00:20:00.000Z`
  **Topics:** Concurrency · Core Data · Performance · Persistence & Synchronisation
  **NeKI brief:** Core Data concurrency depends on context queue confinement and safely passing object IDs rather than managed objects. The article provides a diagnostic model for crashes caused by cross-thread object access.
- [Mastering Core Data Stack](https://fatbobman.com/en/posts/masteringofcoredatastack)
  **Published:** `2021-11-02T00:10:00.000Z`
  **Topics:** Core Data · Navigation & Deep Linking · Persistence & Synchronisation
  **NeKI brief:** A Core Data stack coordinates model, persistent store coordinator, and contexts with explicit ownership and startup sequencing. The article helps diagnose initialization races and choose boundaries for background context work.
- [Understanding SwiftUI's onChange](https://fatbobman.com/en/posts/onchange)
  **Published:** `2021-10-29T04:00:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** SwiftUI onChange observes Equatable state transitions after rendering, so mutation timing and feedback loops matter. The guide helps decide whether a side effect belongs in state observation, task, or a model layer.
- [How to use Derived and Transient Properties in Core Data](https://fatbobman.com/en/posts/derivedandtransient)
  **Published:** `2021-10-25T23:30:00.000Z`
  **Topics:** Core Data · Persistence & Synchronisation
  **NeKI brief:** Derived and transient Core Data attributes trade store persistence for computed behavior, affecting fetchability and change tracking. Follow it when modeling values that can be recalculated but still need UI observation.
- [SwiftUI TextField - FocusState, onSubmit, and Keyboard Accessory](https://fatbobman.com/en/posts/textfield-event-focus-keyboard)
  **Published:** `2021-10-21T01:00:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** SwiftUI TextField focus and keyboard events cross platform responder boundaries, requiring explicit focus state and dismissal policy. The examples help diagnose fields that lose focus or keep the keyboard visible unexpectedly.
- [Advanced SwiftUI TextField - Formatting and Validation](https://fatbobman.com/en/posts/textfield-1)
  **Published:** `2021-10-12T05:30:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** TextField editing distinguishes binding updates, validation, formatting, and submit events. The article is useful for keeping intermediate invalid input separate from the domain value a form ultimately commits.
- [AttributedString - Making Text More Beautiful Than Ever](https://fatbobman.com/en/posts/attributedstring)
  **Published:** `2021-10-08T00:20:00.000Z`
  **Topics:** Swift
  **NeKI brief:** AttributedString models rich text as typed runs with attributes, enabling transformations without raw HTML. Follow it when text styling, localization, and interaction need to remain distinct from view layout.
- [Modern Swift Formatter API - Deep Dive and Customization Guide](https://fatbobman.com/en/posts/newformatter)
  **Published:** `2021-10-01T02:00:00.000Z`
  **Topics:** Swift
  **NeKI brief:** Modern Foundation formatters use value-oriented formatting strategies instead of shared mutable formatter instances. The guide helps improve localization correctness and avoid formatter lifecycle bugs in concurrent code.
- [Globalize Your SwiftUI App - A Comprehensive Guide to Localization](https://fatbobman.com/en/posts/localizationapp-1)
  **Published:** `2021-09-26T08:40:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Localization architecture separates source strings, formatting, and resource organization so features can evolve without duplicating language-specific logic. The article helps identify where extraction and context should live.
- [Showcasing Core Data in Applications with Spotlight](https://fatbobman.com/en/posts/spotlight)
  **Published:** `2021-09-22T07:00:00.000Z`
  **Topics:** App Intents & System Surfaces · Core Data · Persistence & Synchronisation
  **NeKI brief:** Spotlight integration exposes app content through searchable identifiers and metadata, with indexing lifecycle separate from UI navigation. Follow it when designing deep-link restoration from a system search result.
- [SheetKit - SwiftUI Modal View Extension Library](https://fatbobman.com/en/posts/sheetkit)
  **Published:** `2021-09-16T11:50:00.000Z`
  **Topics:** Navigation & Deep Linking · Swift · SwiftUI
  **NeKI brief:** A sheet-management abstraction coordinates modal identity, presentation, and dismissal without scattering boolean flags. The pattern helps prevent competing sheets and keep modal routing testable in SwiftUI.
- [How to Implement interactiveDismissDisabled in SwiftUI](https://fatbobman.com/en/posts/newinteractivedismissdiabled)
  **Published:** `2021-09-15T06:30:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** interactiveDismissDisabled controls whether a presented SwiftUI sheet can be dismissed by system gestures, separating user flow requirements from modal presentation mechanics. The article helps protect unsaved editing workflows.
- [Core Data with CloudKit - Sharing Data in the iCloud](https://fatbobman.com/en/posts/coredatawithcloudkit-6)
  **Published:** `2021-09-11T11:20:00.000Z`
  **Topics:** Core Data · Persistence & Synchronisation
  **NeKI brief:** Core Data with CloudKit requires coordinating store configuration, merge behavior, and conflict observation across devices. Follow it when sync symptoms need to be traced to persistence boundaries rather than view updates.
- [Rebuilding SwiftUI's Redux-like State Container with Async-Await](https://fatbobman.com/en/posts/async-await-store)
  **Published:** `2021-09-06T03:05:00.000Z`
  **Topics:** Concurrency · Observation & State Management · Swift · SwiftUI
  **NeKI brief:** An async/await store wrapper turns callback-based persistence or service work into structured tasks with clear cancellation and error flow. The design helps prevent completion handlers from leaking into model state management.
- [Enhancing SwiftUI Navigation Views with NavigationViewKit](https://fatbobman.com/en/posts/navigationviewkit)
  **Published:** `2021-08-30T12:10:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** A NavigationView abstraction centralizes route selection and presentation state while adapting to SwiftUI navigation limitations. The pattern is useful for keeping deep links and programmatic transitions from becoming scattered booleans.
- [How to Preview a SwiftUI View with Core Data Elements in Xcode](https://fatbobman.com/en/posts/coredatainpreview)
  **Published:** `2021-08-28T00:20:00.000Z`
  **Topics:** Core Data · Persistence & Synchronisation · Swift · SwiftUI · Xcode
  **NeKI brief:** Core Data in SwiftUI previews needs isolated stores, seeded fixtures, and deterministic context ownership. The guide helps prevent previews from touching production data or failing because a persistent container is unavailable.
- [Using UIKit Views in SwiftUI](https://fatbobman.com/en/posts/uikitinswiftui)
  **Published:** `2021-08-23T03:12:00.000Z`
  **Topics:** Swift · SwiftUI · UIKit
  **NeKI brief:** UIKit integration in SwiftUI wraps imperative views and controllers behind representable lifecycle methods. Follow it when platform controls or delegate APIs are needed without giving SwiftUI ownership of their state.
- [Core Data with CloudKit - Synchronizing Public Database](https://fatbobman.com/en/posts/coredatawithcloudkit-5)
  **Published:** `2021-08-13T11:22:00.000Z`
  **Topics:** Core Data · Persistence & Synchronisation
  **NeKI brief:** Core Data with CloudKit sync debugging requires separating persistent-history changes, merge timing, and CloudKit transport state. The article helps locate cross-device inconsistencies without treating every stale view as a UI bug.
- [Core Data with CloudKit - Troubleshooting](https://fatbobman.com/en/posts/coredatawithcloudkit-4)
  **Published:** `2021-08-10T23:50:00.000Z`
  **Topics:** Core Data · Persistence & Synchronisation
  **NeKI brief:** CloudKit-backed Core Data stores need deliberate model and container configuration before data can synchronize safely. Follow it when tracing setup errors across development and production environments.
- [Core Data with CloudKit - Exploring the CloudKit Dashboard](https://fatbobman.com/en/posts/coredatawithcloudkit-3)
  **Published:** `2021-08-09T09:30:00.000Z`
  **Topics:** Core Data · Persistence & Synchronisation
  **NeKI brief:** Core Data CloudKit synchronization introduces remote-change observation and merge boundaries distinct from ordinary context saves. The guide helps prevent duplicate processing when local and remote transactions overlap.
- [Core Data with CloudKit - Syncing Local Database to iCloud Private Database](https://fatbobman.com/en/posts/coredatawithcloudkit-2)
  **Published:** `2021-08-09T00:50:00.000Z`
  **Topics:** Core Data · Persistence & Synchronisation
  **NeKI brief:** A CloudKit/Core Data integration must establish store options and account identity before application features assume shared data exists. The article is useful for designing first-run and offline fallback behavior.
- [Core Data with CloudKit - The Basics](https://fatbobman.com/en/posts/coredatawithcloudkit-1)
  **Published:** `2021-08-05T12:50:00.000Z`
  **Topics:** Core Data · Persistence & Synchronisation
  **NeKI brief:** The first Core Data with CloudKit installment maps object persistence to cloud-backed stores, clarifying deployment and schema prerequisites. Follow it before adding UI observation to a synchronization stack.
- [Mastering @AppStorage in SwiftUI](https://fatbobman.com/en/posts/appstorage)
  **Published:** `2021-07-31T10:40:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** AppStorage binds SwiftUI state to UserDefaults, but supported value types, key ownership, and invalidation scope still matter. The article helps decide when settings are simple preferences versus model data.
- [Using Persistent History Tracking in CoreData](https://fatbobman.com/en/posts/persistenthistorytracking)
  **Published:** `2021-07-27T04:00:00.000Z`
  **Topics:** Core Data · Persistence & Synchronisation
  **NeKI brief:** Persistent history tracking records Core Data transactions so contexts and extensions can process changes made elsewhere. Follow it when synchronization needs incremental, attributable changes instead of broad save notifications.
- [Setting Up a Swift Development and Debugging Environment on Linux](https://fatbobman.com/en/posts/swift-in-linux)
  **Published:** `2021-02-15T07:00:00.000Z`
  **Topics:** Swift
  **NeKI brief:** Swift on Linux changes framework availability, deployment, and integration assumptions while preserving much of the language toolchain. The overview helps separate portable Swift logic from Apple-platform-only dependencies.
- [Creating a Blog with Publish - Plugin](https://fatbobman.com/en/posts/publish-3)
  **Published:** `2021-02-03T11:58:00.000Z`
  **Topics:** Developer Community & Business
  **NeKI brief:** A Publish static-site workflow separates content, theme, and generation stages, making deployment repeatable. The article is useful for evaluating Swift-based tooling without confusing a site generator with runtime server architecture.
- [Creating a Blog with Publish - Theme](https://fatbobman.com/en/posts/publish-2)
  **Published:** `2021-02-01T08:20:00.000Z`
  **Topics:** Swift
  **NeKI brief:** The Publish workflow separates content models, themes, and generation steps, letting a Swift static site evolve without runtime server state. Follow it when evaluating site tooling and repeatable deployment boundaries.
- [Creating a Blog with Publish - Getting Started](https://fatbobman.com/en/posts/publish-1)
  **Published:** `2021-01-30T13:00:00.000Z`
  **Topics:** Swift
  **NeKI brief:** An introduction to Publish establishes Swift-based static-site generation and content organization before theme customization. The article is useful for distinguishing compile-time site output from a dynamic web application.
- [Adapting to iPad in SwiftUI](https://fatbobman.com/en/posts/swiftui-ipad)
  **Published:** `2020-10-29T04:00:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** iPad SwiftUI design must account for split views, pointer input, and size-class changes instead of scaling an iPhone screen. Follow it when an adaptive layout needs platform-specific navigation choices.
- [Discussing CoreData Usage in SwiftUI](https://fatbobman.com/en/posts/coredata-in-swiftui)
  **Published:** `2020-10-28T04:00:00.000Z`
  **Topics:** Core Data · Persistence & Synchronisation · Swift · SwiftUI
  **NeKI brief:** Using Core Data in SwiftUI connects managed contexts, fetch requests, and object identity to declarative updates. The guide helps identify where Core Data queue rules still apply despite a SwiftUI view layer.
- [Development Musings for Health Notes 2.0 (Part 6)](https://fatbobman.com/en/posts/healthnote2-development-memo-6)
  **Published:** `2020-10-26T04:00:00.000Z`
  **Topics:** Health Apps
  **NeKI brief:** A HealthNote development memo records implementation decisions in a health-data app, connecting feature work to privacy and persistence constraints. Follow it as a case-study perspective, not a normative HealthKit reference.
- [Creating a Sheet in SwiftUI with Controllable Cancel Gestures](https://fatbobman.com/en/posts/swiftui-dismiss-sheet)
  **Published:** `2020-09-17T04:00:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Dismissing a SwiftUI sheet depends on the presentation environment and ownership of modal state. The guide helps prevent dismissal actions that work in one hierarchy but fail in nested or programmatic presentations.
- [Development Musings for Health Notes 2.0 (Part 3)](https://fatbobman.com/en/posts/healthnote2-development-memo-3)
  **Published:** `2020-09-05T04:00:00.000Z`
  **Topics:** Health Apps
  **NeKI brief:** Describes consolidating scattered SwiftUI state into a single source of truth for real-time forms and centralized sheet selection, reducing divergent edit state and enabling features that otherwise require cross-view coordination.
- [Pop Up Different Sheets in SwiftUI as Needed](https://fatbobman.com/en/posts/swiftui-multisheet)
  **Published:** `2020-09-04T04:00:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Managing multiple SwiftUI sheets requires modal identity and a single routing authority, otherwise booleans compete and presentations replace each other. The article helps design testable, predictable modal flows.
- [How to Create a Real-Time Responsive Form in SwiftUI](https://fatbobman.com/en/posts/swiftui-input-form)
  **Published:** `2020-09-04T04:00:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** A SwiftUI input form separates draft bindings, validation, focus, and commit actions so incomplete text does not corrupt domain state. The patterns help make keyboard-driven forms resilient.
- [Discussing List and ForEach in SwiftUI](https://fatbobman.com/en/posts/swiftui-list-foreach)
  **Published:** `2020-08-24T04:00:00.000Z`
  **Topics:** Performance · Swift · SwiftUI
  **NeKI brief:** List and ForEach depend on stable identity to drive row reuse, diffing, and mutations. The guide helps diagnose deleted or reordered rows that display stale content after collection updates.
- [Development Musings for Health Notes 2.0 (Part 2)](https://fatbobman.com/en/posts/healthnote2-development-memo-2)
  **Published:** `2020-08-24T04:00:00.000Z`
  **Topics:** Health Apps
  **NeKI brief:** Builds SwiftUI preview fixtures around an in-memory Core Data store and sample managed objects, letting views render representative persistence data without coupling previews to the production store or live user records.
- [SwiftUIOverlayContainer — A SwiftUI Library for Creating Customized Popup Views](https://fatbobman.com/en/posts/swifui-overlay)
  **Published:** `2020-08-12T08:00:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** SwiftUI overlays layer presentation above content while preserving a separate layout and hit-testing boundary. Follow it when popups or HUDs should not distort the underlying screen's geometry.
- [Implementing the Side Menu for the iOS Mail App with SwiftUI](https://fatbobman.com/en/posts/swipecell)
  **Published:** `2020-08-12T06:00:00.000Z`
  **Topics:** Swift · SwiftUI · UIKit · Xcode
  **NeKI brief:** Compose a SwiftUI mail-style side menu from configurable buttons and slots, then dismiss it when scrolling begins. Gesture-driven presentation needs explicit coordination with the scroll view, otherwise horizontal actions and vertical navigation compete for input.
- [HowTo —— File Import and Export in SwiftUI 2.0](https://fatbobman.com/en/posts/howto-swiftui-import-export)
  **Published:** `2020-07-28T04:00:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Use fileImporter, fileExporter, and fileMover for SwiftUI document workflows instead of building custom pickers. Treat the selected URL's permission scope as part of the operation, since successful selection does not itself grant durable unrestricted access.
- [HowTo —— Using ScrollViewReader to Scroll to Position in SwiftUI 2.0](https://fatbobman.com/en/posts/howto-swiftui-scrollviewreader)
  **Published:** `2020-07-23T05:00:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** ScrollViewReader navigates to stable view identifiers rather than exposing pixel offsets. Assign IDs to meaningful targets and call proxy scrolling for programmatic movement, while recognizing that dynamic content and timing can make an apparent target unavailable.
- [HowTo —— Using ProgressView in SwiftUI 2.0 to Display Progress Bars](https://fatbobman.com/en/posts/howto-swiftui-progressview)
  **Published:** `2020-07-12T05:00:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** ProgressView supplies indeterminate and linear progress presentations with style customization. Bind a determinate value to real task progress and choose the form by whether completion can be measured; visual styling should not imply unavailable precision.
- [HowTo —— Handling Universal Links with onOpenURL](https://fatbobman.com/en/posts/howto-swiftui-onopenurl)
  **Published:** `2020-07-11T05:00:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Handle Universal Links and custom URL schemes in SwiftUI with onOpenURL at the view level, translating the incoming URL into app navigation or state. Centralize parsing so unsupported hosts and paths do not silently route users incorrectly.
- [HowTo —— Use ToolBar to Replace navigationbarItems in SwiftUI2.0](https://fatbobman.com/en/posts/howto-swiftui-toolbar)
  **Published:** `2020-07-10T06:00:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Replace navigationBarItems with Toolbar to express placement semantically across Apple platforms. Toolbar items adapt to the hosting navigation context, so grouping and placement should describe the intended command role rather than assume one iOS bar layout.
- [HowTo —— Use Link or openURL to open URL scheme in SwiftUI2.0](https://fatbobman.com/en/posts/howto-swiftui-link-openurl)
  **Published:** `2020-07-10T05:00:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Use Link for straightforward external destinations and openURL when an action must decide how or whether to open a scheme. Validate mail, phone, and custom URLs before dispatching because the system cannot guarantee every target app exists.
- [HowTO —— SwiftUI 2.0 LazyGrid](https://fatbobman.com/en/posts/howto-swiftui-grid)
  **Published:** `2020-07-10T04:00:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** LazyVGrid and LazyHGrid model flexible, fixed, and adaptive columns without third-party grid containers. Select grid-item sizing from the content's constraints; mixed layouts otherwise create surprising compression or spacing under size changes.
- [HowTo - SwiftUI 2.0 LazyVStack and LazyHStack](https://fatbobman.com/en/posts/howto-swiftui-lazystack)
  **Published:** `2020-07-09T05:05:00.000Z`
  **Topics:** Performance · Swift · SwiftUI
  **NeKI brief:** LazyVStack and LazyHStack defer child creation for long or continuous content, reducing initial work compared with eager stacks. Their laziness is a rendering strategy, not data pagination, so the backing collection still needs its own growth policy.
- [HowTo —— How to Use Label in SwiftUI 2.0](https://fatbobman.com/en/posts/howto-swiftui-label)
  **Published:** `2020-07-09T05:05:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Label couples an icon with localized text and lets styles adapt that pair to each platform context. Provide custom LabelStyle only when the standard semantics are retained; otherwise use a dedicated view for a genuinely different control.
- [HowTo - Displaying Maps in a View with Swift 2.0](https://fatbobman.com/en/posts/howto-swiftui-map)
  **Published:** `2020-07-09T05:00:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** SwiftUI's Map integrates MapKit content while letting the view bind to visible region and user-location state. Keep annotations and tracking behavior driven by model state, because map gestures can otherwise overwrite programmatic location changes.
- [SwiftUI 2.0 — Apps, Scenes, and New Code Structures (Part 2)](https://fatbobman.com/en/posts/swiftui2-new-feature-2)
  **Published:** `2020-07-08T06:00:00.000Z`
  **Topics:** Architecture · Swift · SwiftUI
  **NeKI brief:** AppStorage and SceneStorage persist small values at different scopes, while SwiftUI 2 property wrappers clarify ownership in the data flow. Choose scene storage for per-window restoration; app storage is shared and can accidentally couple independent scenes.
- [SwiftUI 2.0 — App, Scene, and New Code Structure (Part 1)](https://fatbobman.com/en/posts/swiftui2-new-feature-1)
  **Published:** `2020-07-08T04:00:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** SwiftUI's App and Scene protocols replace much application-delegate plumbing with declarative scene composition. WindowGroup and DocumentGroup express distinct lifecycle and document semantics, so select the scene type from how the system should create and restore UI.
- [@FocusedBinding Overview](https://fatbobman.com/en/posts/focusedbinding)
  **Published:** `2020-07-05T04:00:00.000Z`
  **Topics:** Observation & State Management · Swift · SwiftUI
  **NeKI brief:** FocusedBinding exposes a binding through the focused view hierarchy using a FocusedValueKey, allowing commands to affect the current editor without manual view traversal. It is context-sensitive, so callers must tolerate no focused value or changing focus.
- [SwiftUI 2.0 — Commands (macOS Menu)](https://fatbobman.com/en/posts/swiftui2-commands)
  **Published:** `2020-06-27T04:00:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Use Commands and CommandMenu to place macOS menu actions near system commands, with buttons and keyboard shortcuts defining behavior. The command tree is scene-level UI, so its actions should resolve state from focused context rather than a single window assumption.
- [SwiftUI 2.0 —— Research on @StateObject](https://fatbobman.com/en/posts/stateobject)
  **Published:** `2020-06-26T04:00:00.000Z`
  **Topics:** Observation & State Management · Swift · SwiftUI
  **NeKI brief:** StateObject owns an ObservableObject for the lifetime of the view identity, whereas ObservedObject receives ownership from elsewhere. Choose StateObject at the creation boundary; recreating reference state inside transient views loses data and subscriptions.
- [@State Research in SwiftUI](https://fatbobman.com/en/posts/swiftui-state)
  **Published:** `2020-05-17T04:00:00.000Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** State stores value-owned view data outside transient body recalculation and invalidates dependent rendering when it changes. Keep it local and small; projecting shared or reference-owned data into State blurs ownership and produces surprising resets.
- [Single Source of Truth in SwiftUI - Is ObservableObject Enough?](https://fatbobman.com/en/posts/observableobject-study)
  **Published:** `2020-05-17T04:00:00.000Z`
  **Topics:** Architecture · Dependency Injection · Observation & State Management · Swift · SwiftUI
  **NeKI brief:** ObservableObject supports reference-type state propagation, but it does not automatically make a data graph a single source of truth. Inject it at a deliberate boundary and minimize dependent views so object-change notifications do not redraw unrelated interface regions.
- [Installation and Configuration of Vapor4](https://fatbobman.com/en/posts/vapor4)
  **Published:** `2020-05-07T04:00:00.000Z`
  **Topics:** Swift
  **NeKI brief:** Set up Vapor 4 through its CLI, understand the generated server structure, and separate local debugging from deployment concerns. Swift server deployment also needs operating-system, reverse-proxy, and process-management configuration beyond the application target.
