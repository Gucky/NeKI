# Tanaschita

Third-party source index. It provides source attribution and routing metadata, not republished article content. Verify article conclusions independently before applying them.

- Archive: [https://tanaschita.com/](https://tanaschita.com/)
- Last collected: `2026-07-22T12:45:57Z`
- Indexed entries: **185**

- [Understanding Xcode targets, schemes and build configurations](https://tanaschita.com/xcode-targets-schemes)
  **NeKI brief:** Explains how Xcode targets, schemes, and build configurations divide products and runtime settings. Useful for designing multi-app or multi-environment projects without hiding configuration in ad-hoc scripts.
- [My favorite Xcode keyboard shortcuts to be more productive](https://tanaschita.com/xcode-shortcuts)
  **NeKI brief:** Collects Xcode keyboard shortcuts for navigation, editing, and project workflows. Useful for reducing context-switching during daily maintenance without changing project configuration or source code.
- [Quick tip on how to learn Xcode keyboard shortcuts efficiently](https://tanaschita.com/xcode-quicktip-learning-shortcuts)
  **NeKI brief:** Turns Xcode's Help menu into a shortcut lookup loop: search an action, use the shown key combination, and repeat it in daily work. A custom macOS App Shortcut for opening Help removes the only recurring friction in that practice.
- [Learn to debug iOS features that require app start from external actions in Xcode](https://tanaschita.com/xcode-debugging-app-restart)
  **NeKI brief:** Uses Xcode's wait-for-executable scheme option to attach the debugger when deep links, universal links, quick actions, or other external events launch the app.
- [Working with Xcode configuration files](https://tanaschita.com/xcode-configuration-files)
  **NeKI brief:** Builds debug, staging, and release environments with xcconfig files, inherited settings, and Info.plist values while avoiding duplicated configuration.
- [Creating and managing multiple app environments in Xcode](https://tanaschita.com/xcode-build-environments)
  **NeKI brief:** Shows organizing Xcode build environments for development, staging, and production values. Useful for keeping endpoint and feature configuration explicit across schemes without scattering conditional literals.
- [WWDC 2025 summary of Apple's platforms state of the union talk for iOS developers](https://tanaschita.com/wwdc-2025-state-of-the-union-summary)
  **NeKI brief:** Summarizes the WWDC 2025 platform changes that affect existing apps, including automatic Liquid Glass adoption after recompiling with Xcode 26, opt-out controls, and the new Apple Intelligence and SwiftUI surfaces. Use it as release orientation before checking SDK-specific API contracts.
- [WWDC 2024 summary of Apple's platforms state of the union talk for iOS developers](https://tanaschita.com/wwdc-2024)
  **NeKI brief:** Connects WWDC 2024 announcements to concrete app work: Image Playground integration, Swift Testing's async-first tests, Swift 6 language changes, and SwiftData or Controls updates. It is useful for migration triage, with availability and exact behavior requiring current Apple documentation.
- [Building configurable widgets with WidgetKit and SwiftUI](https://tanaschita.com/widgetkit-configurable-widgets-swiftui)
  **NeKI brief:** Builds a configurable widget as a data flow: an AppIntent exposes an AppEnum or dynamic options, WidgetKit stores the selection, the provider receives it, and the SwiftUI entry renders the chosen value. Follow it when widget configuration must reflect app data.
- [Building widgets with WidgetKit and SwiftUI](https://tanaschita.com/widgetkit-building-widgets-with-swiftui)
  **NeKI brief:** Walks through the WidgetKit extension boundary, timeline provider, entry rendering, deep-linking, interactive controls, shared storage, and timeline reloads. The useful decision is to keep widgets glanceable and schedule data explicitly instead of treating them as miniature app screens.
- [Quick tip on adding child view controllers programmatically in UIKit](https://tanaschita.com/uikit-adding-childview-controller)
  **NeKI brief:** Provides a small UIViewController extension that performs containment calls, adds the child view, and constrains it to a supplied content view, reducing repetitive and error-prone programmatic UIKit composition.
- [Manipulating networking requests and responses with Charles](https://tanaschita.com/tools-charles-proxy-manipulating-network-requests-and-responses)
  **NeKI brief:** Uses Charles Breakpoints to intercept a matched request or response, edit its payload, and release the modified data to the app. This creates deterministic tests for malformed, missing, or unexpected server values without changing the production endpoint.
- [Quick guide on Charles Proxy for iOS development](https://tanaschita.com/tools-charles-proxy-for-ios-guide)
  **NeKI brief:** Shows Charles as an inspection and fault-injection proxy for simulator or device traffic, including trusted certificates for HTTPS, session views, request/response inspection, and simulated slow networking. Use it to diagnose transport behavior while keeping proxy trust confined to development.
- [Getting started with UI Testing for SwiftUI](https://tanaschita.com/testing-ui-swiftui-xctest-framework)
  **NeKI brief:** Demonstrates UI testing SwiftUI applications with XCTest, including accessibility-driven queries and interaction assertions. Useful for testing user-visible behavior without coupling tests to implementation details.
- [How to unit test async/await functions in Swift](https://tanaschita.com/testing-swift-async-await)
  **NeKI brief:** Demonstrates that XCTest methods can be marked async and await asynchronous work directly, eliminating manual XCTestExpectation bookkeeping. Throwing functions use try in the test, making success and failure paths explicit while keeping the test focused on returned behavior.
- [Testing remote iOS push notifications in a simulator with simctl](https://tanaschita.com/testing-remote-push-notifications-in-ios-simulator)
  **NeKI brief:** Explains testing remote push notifications in the iOS Simulator with simctl, including preparing payloads and delivering them locally. Useful for repeatable notification QA without waiting on a production provider, while still separating simulator limits from device behavior.
- [How to test in-app purchases locally using StoreKit](https://tanaschita.com/testing-in-app-purchases-locally-storekit)
  **NeKI brief:** Explains local StoreKit configuration in Xcode for simulating purchases, subscriptions, and failure cases without depending on App Store sandbox accounts.
- [Preventing forgotten database migrations with automated tests in iOS](https://tanaschita.com/testing-database-migrations)
  **NeKI brief:** Presents a database-migration testing workflow that verifies schema changes against realistic stores. Use it to catch destructive transformations, ordering mistakes, and data-loss regressions before shipping a new persistence version.
- [Customizing the appearance of the NavigationView title in SwiftUI](https://tanaschita.com/switui-navigationview-customize-title)
  **NeKI brief:** Shows the two NavigationView title controls: navigationBarTitleDisplayMode changes large versus inline behavior, while toolbar content can replace the title area with custom views. The article also flags NavigationStack as the modern choice for new navigation code.
- [Customizing the appearance of the NavigationStack title in SwiftUI](https://tanaschita.com/switui-navigationstack-customize-title)
  **NeKI brief:** Explains customizing a NavigationStack title in SwiftUI and controlling title display behavior. Use it when navigation bars need product-specific hierarchy or formatting while preserving correct large-title transitions, accessibility, and back-navigation affordances.
- [How to call async/await functions in SwiftUI](https://tanaschita.com/swiftui-with-async-await)
  **NeKI brief:** Maps SwiftUI async work to its trigger: task starts and automatically cancels work with view identity, Task handles button actions, and refreshable integrates pull-to-refresh. This separation helps avoid launching lifecycle work from synchronous view construction.
- [Using WebKit with SwiftUI to manage web content](https://tanaschita.com/swiftui-webkit)
  **NeKI brief:** Contrasts SwiftUI's WebView for straightforward URL display with WebPage for programmatic control such as navigation observation, JavaScript, and page state. It also outlines the UIViewRepresentable/WKWebView bridge needed when supporting systems before the native SwiftUI API.
- [Learn to build adaptive layouts with SwiftUI's ViewThatFits container.](https://tanaschita.com/swiftui-viewthatfits-container)
  **NeKI brief:** Explains how ViewThatFits selects the first SwiftUI view that fits available space. Use it to build adaptive layouts that gracefully switch between alternative compositions at different widths.
- [How to manage view lifecycle events in SwiftUI](https://tanaschita.com/swiftui-view-lifecycle-events)
  **NeKI brief:** Explains SwiftUI lifecycle callbacks such as task, onAppear, and onDisappear and their execution behavior. Follow it when attaching loading or cleanup work without accidentally duplicating effects across view identity changes.
- [Understanding composition in SwiftUI](https://tanaschita.com/swiftui-understanding-composition)
  **NeKI brief:** Explains SwiftUI composition as a tree of View values assembled through @ViewBuilder and the Composite pattern, rather than stored child objects. The model clarifies why conditional branches affect structural identity and why small views remain reusable building blocks.
- [How to combine SwiftUI and UIKit views in iOS](https://tanaschita.com/swiftui-uikit)
  **NeKI brief:** Defines both bridge directions: UIViewRepresentable updates a UIKit view from SwiftUI state, UIViewControllerRepresentable embeds controllers, and UIHostingController puts SwiftUI into UIKit. The make/update lifecycle is the key boundary for keeping ownership and state synchronization explicit.
- [Understanding toolbars in SwiftUI](https://tanaschita.com/swiftui-toolbars-guide)
  **NeKI brief:** Surveys SwiftUI toolbar placement, roles, and item composition across platforms. Useful for avoiding platform-specific placement surprises and keeping actions discoverable in navigation bars.
- [Understanding structural identity in SwiftUI](https://tanaschita.com/swiftui-structural-identity)
  **NeKI brief:** Explains how SwiftUI uses view type and hierarchy position as structural identity to decide what persists and redraws. Follow it when conditional branches unexpectedly reset state or trigger more updates than expected.
- [How to use SceneDelegate in SwiftUI](https://tanaschita.com/swiftui-scenedelegate)
  **NeKI brief:** Bridges scene lifecycle behavior into SwiftUI through a scene delegate integration. Useful when an application still needs UIKit lifecycle hooks for notifications, deep links, or window coordination.
- [How to create a custom reusable toolbar in SwiftUI](https://tanaschita.com/swiftui-reusable-toolbar)
  **NeKI brief:** Builds a reusable SwiftUI toolbar component while keeping actions and state explicit. Useful for design systems that need consistent toolbar composition across screens and platforms.
- [How to present a local HTML file in SwiftUI](https://tanaschita.com/swiftui-present-local-html-files)
  **NeKI brief:** Compares iOS 26's native WebView/WebPage path for bundled HTML—including local assets and preprocessing—with the older WKWebView UIViewRepresentable wrapper for iOS 14+. Choose the path by deployment target and by whether the page needs load control or HTML mutation.
- [Migrating to the Observation framework in SwiftUI](https://tanaschita.com/swiftui-observation-migrating-to-observation)
  **NeKI brief:** Walks through migrating SwiftUI models from ObservableObject to Observation, including property wrappers and ownership changes. Useful for an incremental migration that keeps view dependencies testable.
- [Understanding the Bindable property wrapper in SwiftUI](https://tanaschita.com/swiftui-observation-bindable)
  **NeKI brief:** Clarifies that an @Observable model can be read directly by a child view, but a child needing writable bindings must introduce @Bindable around that model. The wrapper exposes projected properties such as $model.name without reverting to ObservableObject ownership patterns.
- [How to use NavigationPath for routing in SwiftUI](https://tanaschita.com/swiftui-navigationpath)
  **NeKI brief:** Uses NavigationPath for programmatic SwiftUI routing, separating navigation data from destinations so deep links and restoration can share one stack model.
- [Structuring universal links in iOS](https://tanaschita.com/swiftui-navigation-universal-links-architecture)
  **NeKI brief:** Structures universal-link handling around SwiftUI navigation state. Use it when parsing an incoming URL, restoring a scene, and selecting a nested destination must work consistently on cold launch and while running.
- [How to persist navigation state in SwiftUI](https://tanaschita.com/swiftui-navigation-persist-state)
  **NeKI brief:** Shows how navigation containers preserve or recreate view state and how to place state storage accordingly. Useful when returning to a destination unexpectedly resets user input.
- [Using NavigationPath with TabView in SwiftUI](https://tanaschita.com/swiftui-navigation-path-with-tabview)
  **NeKI brief:** Uses NavigationPath with TabView to preserve typed navigation state per tab. Use it when deep links and tab switching must restore the correct nested destination.
- [Understanding localization with LocalizedStringKey in SwiftUI](https://tanaschita.com/swiftui-localization)
  **NeKI brief:** Compares LocalizedStringKey with NSLocalizedString in SwiftUI, clarifying interpolation and localization-context trade-offs when migrating existing string access patterns across views.
- [How to implement pagination with SwiftUI's List view](https://tanaschita.com/swiftui-list-pagination)
  **NeKI brief:** Implements incremental pagination in SwiftUI List as the user approaches the end of loaded content. Use it when an async data source needs explicit loading, error, and duplicate-request guards rather than eager full retrieval.
- [Adding navigation buttons to the keyboard in SwiftUI](https://tanaschita.com/swiftui-keyboard-buttons)
  **NeKI brief:** Explains adding keyboard toolbar buttons to SwiftUI input flows and coordinating focus with dismissal or navigation actions. Use it when forms need explicit keyboard controls that behave consistently across fields, platforms, and accessibility interaction modes.
- [How to identify data in Lists and ForEach in SwiftUI](https://tanaschita.com/swiftui-identifiable)
  **NeKI brief:** Explains Identifiable requirements and stable identity in SwiftUI collections. Useful for preventing row reuse, animation, and diffing bugs caused by transient or duplicated identifiers.
- [How to avoid using AnyView in SwiftUI](https://tanaschita.com/swiftui-how-to-avoid-using-anyview)
  **NeKI brief:** Shows alternatives to AnyView through generics, builders, and conditional composition. Useful for preserving static view types and avoiding type erasure where it would obscure layout or performance.
- [Understanding SwiftUI's Grid container](https://tanaschita.com/swiftui-grid-container)
  **NeKI brief:** Explains SwiftUI Grid's row and column behavior, helping decide when eager intrinsic sizing is preferable to nested stacks or lazy grids.
- [Understanding SwiftUI's liquid glass button styles](https://tanaschita.com/swiftui-glass-button-style)
  **NeKI brief:** Distinguishes SwiftUI glass button styles from the lower-level glassEffect modifier, making component-level styling decisions clearer in Liquid Glass interfaces.
- [When SwiftUI automatically applies the glass look and when it doesn’t](https://tanaschita.com/swiftui-glass-auto-apply)
  **NeKI brief:** Explains when SwiftUI automatically applies Liquid Glass and when explicit modifiers are required. Useful for diagnosing inconsistent material appearance across containers and platform contexts.
- [Understanding the @FetchRequest property wrapper in SwiftUI](https://tanaschita.com/swiftui-fetchrequest-property-wrapper)
  **NeKI brief:** Explains @FetchRequest as a SwiftUI-driven Core Data query, clarifying predicate, sort, and managed-object context boundaries that affect view updates.
- [Understanding the @Environment property wrapper in SwiftUI](https://tanaschita.com/swiftui-environment-property-wrapper)
  **NeKI brief:** Breaks down @Environment lookup scenarios, helping distinguish system values, injected dependencies, and custom keys so views do not hide required inputs accidentally.
- [Dynamic colors in SwiftUI](https://tanaschita.com/swiftui-dynamic-colors)
  **NeKI brief:** Builds dynamic SwiftUI colors that adapt to light and dark appearances, keeping semantic color decisions centralized instead of scattering color-scheme checks through views.
- [Building a draggable bottom sheet in SwiftUI](https://tanaschita.com/swiftui-draggable-bottom-sheet)
  **NeKI brief:** Builds a draggable SwiftUI bottom sheet with gesture state, detents, and snapping decisions. Useful for custom interaction when system sheets do not expose the required presentation behavior.
- [How to preview SwiftUI views in dark mode](https://tanaschita.com/swiftui-dark-mode-preview)
  **NeKI brief:** Dark-mode previews let a SwiftUI view be checked against both color schemes during development, catching contrast and asset mistakes before device testing.
- [Customizing buttons in SwiftUI with the ButtonStyle protocol](https://tanaschita.com/swiftui-customizing-button-with-buttonstyle)
  **NeKI brief:** Uses ButtonStyle to package reusable visual states, separating button interaction semantics from styling and avoiding repeated wrapper views for every action.
- [How to create custom @Environment values in SwiftUI](https://tanaschita.com/swiftui-custom-environment-values)
  **NeKI brief:** Defines custom SwiftUI environment keys and values for shared dependencies or configuration. Useful when a value should flow through a view tree while remaining overridable in previews and tests.
- [How to create custom reusable container views in SwiftUI](https://tanaschita.com/swiftui-custom-containers)
  **NeKI brief:** Creates generic reusable SwiftUI container views with view-builder content, preserving caller flexibility while keeping layout policy in one composable component.
- [How to use SwiftUI Coordinators to communicate with UIKit](https://tanaschita.com/swiftui-coordinators)
  **NeKI brief:** Uses DataScannerViewController to show how UIViewControllerRepresentable.Coordinator receives UIKit delegate callbacks and sends results back to SwiftUI, making the coordinator boundary concrete for delegate-driven integrations.
- [Understanding container values in SwiftUI](https://tanaschita.com/swiftui-container-values)
  **NeKI brief:** Uses SwiftUI container values to pass configuration through container hierarchies without bespoke environment keys. Useful for custom layout or collection components that need scoped child behavior.
- [Cancelling async tasks in SwiftUI](https://tanaschita.com/swiftui-cancel-async-work)
  **NeKI brief:** Shows task and task(id:) cancellation in SwiftUI, emphasizing view lifetime as the cancellation boundary and preventing stale asynchronous results from updating disappeared screens.
- [Understanding basic animations in SwiftUI](https://tanaschita.com/swiftui-basic-animations)
  **NeKI brief:** Introduces SwiftUI's state-driven animation model through basic transitions and modifiers. Follow it when mapping a state change to a visual effect and checking which view values actually participate in interpolation.
- [How to manage app lifecycle events in SwiftUI](https://tanaschita.com/swiftui-app-lifecycle-events)
  **NeKI brief:** Observes scenePhase changes to react to background and active transitions, making lifecycle work explicit while avoiding assumptions that a view callback represents the whole app.
- [How to store images in SwiftData](https://tanaschita.com/swiftdata-store-images)
  **NeKI brief:** Uses SwiftData's externalStorage attribute for larger image payloads, trading inline persistence convenience for a more appropriate storage layout and fetch footprint.
- [How to migrate to a new schema with SwiftData in iOS](https://tanaschita.com/swiftdata-schema-migration)
  **NeKI brief:** Walks through SwiftData schema migration, focusing on explicit versioning and migration stages so model changes do not become launch-time surprises.
- [Quick developer guide on SwiftData for iOS](https://tanaschita.com/swiftdata-quick-developer-guide)
  **NeKI brief:** Introduces SwiftData's macro-driven model and container setup, useful for understanding the framework's declarative persistence surface before selecting migration or architectural boundaries.
- [Keeping SwiftData behind a boundary](https://tanaschita.com/swiftdata-persistence-boundaries)
  **NeKI brief:** Keeps SwiftData behind a persistence boundary instead of exposing models directly to SwiftUI, improving testability and reducing UI coupling to storage details.
- [How to define one-to-many relationships in SwiftData](https://tanaschita.com/swiftdata-one-to-many-relationships)
  **NeKI brief:** Defines SwiftData one-to-many relationships with @Relationship, highlighting ownership and delete-rule decisions that determine graph consistency during mutation and migration.
- [How to get a SwiftData model container and context in SwiftUI](https://tanaschita.com/swiftdata-model-container-context-swiftui)
  **NeKI brief:** Sets up a SwiftData model container and context through SwiftUI modifiers, showing the dependency-injection seam views need for previews and tests.
- [How to solve problems with bitwise operators in Swift](https://tanaschita.com/swift-working-with-bits)
  **NeKI brief:** Uses bitwise operations and OptionSet-style flags for compact state representation, clarifying when bit-level packing improves interoperability and when named booleans remain clearer.
- [Storing Swift structs in UserDefaults](https://tanaschita.com/swift-user-defaults-storing-structs)
  **NeKI brief:** Shows encoding Swift structs before storing them in UserDefaults, keeping typed preferences behind a small persistence boundary. Useful for lightweight settings while avoiding UserDefaults as a substitute for relational data.
- [Understanding Substring and String indices in Swift](https://tanaschita.com/swift-strings-indices-and-substrings)
  **NeKI brief:** Explains Swift String indices and Substring lifetimes, preventing invalid integer-offset assumptions when handling Unicode text or slicing without unnecessary copies.
- [Swift optionals cheat sheet](https://tanaschita.com/swift-optionals-cheat-sheet)
  **NeKI brief:** The optional cheat sheet contrasts unwrapping, defaulting, and propagation, making absence-handling choices explicit instead of hiding them behind force casts.
- [Understanding opaque types and protocols with associatedtype in Swift](https://tanaschita.com/swift-opaque-types-protocols-associatedtype)
  **NeKI brief:** Shows how opaque some types work with protocols that have associated types. Use it to hide concrete implementations while preserving compiler-checked relationships between returned values and protocols.
- [Understanding opaque types in Swift](https://tanaschita.com/swift-opaque-types)
  **NeKI brief:** Explains opaque result types and their distinction from existential protocol values. Use it when an API should hide a concrete type while preserving compile-time specialization and identity guarantees.
- [How to use Swift's logging API](https://tanaschita.com/swift-logging-api)
  **NeKI brief:** Uses Logger for structured Swift logging, separating privacy and subsystem decisions from ad-hoc print output so diagnostics remain filterable in production.
- [How to use custom names for Swift properties when decoding JSON data](https://tanaschita.com/swift-json-decoding-custom-names)
  **NeKI brief:** Custom Codable keys map external JSON field names to Swift naming conventions without leaking transport spelling into the model. Use CodingKeys for stable mappings, keeping more complex schema transformations at a dedicated decoding boundary.
- [Understanding date decoding strategies when working with JSON in Swift](https://tanaschita.com/swift-json-date-decoding-encoding)
  **NeKI brief:** Date decoding strategies centralize format conversion for JSON, preventing repeated formatter logic while requiring the API's timezone and precision assumptions to be documented.
- [How to change JSON keys by using Swift's CodingKey protocol](https://tanaschita.com/swift-json-custom-decoding-encoding)
  **NeKI brief:** Custom Codable implementations handle irregular payloads while keeping model APIs typed, with manual code concentrating schema assumptions in one boundary.
- [How to use cryptographic hash functions in CryptoKit for iOS security](https://tanaschita.com/swift-hash-functions)
  **NeKI brief:** Uses CryptoKit hash functions for integrity and security-related fingerprints. Use it when comparing data or deriving stable digests, while distinguishing hashing from reversible encryption.
- [Extending optionals in Swift](https://tanaschita.com/swift-extending-optionals)
  **NeKI brief:** An Optional extension adds focused convenience while preserving nil semantics. The useful boundary is restraint: follow it for repeated unwrapping logic, but avoid hiding required state behind chains that obscure failure.
- [Understanding existentials and primary associated types in Swift](https://tanaschita.com/swift-existentials)
  **NeKI brief:** Explains existentials and primary associated types for protocols with associated types. Use it to choose between existential storage and generic constraints while keeping collections flexible and type-safe.
- [Bridging interfaces with the Adapter pattern in Swift](https://tanaschita.com/swift-design-patterns-adapter)
  **NeKI brief:** Demonstrates the Adapter pattern in Swift for integrating third-party or legacy APIs behind clean interfaces. Use it to isolate incompatible contracts and keep application code testable.
- [Async cleanup with defer in Swift](https://tanaschita.com/swift-defer-async)
  **NeKI brief:** Shows how defer interacts with async and throwing Swift code so cleanup still occurs across suspension and errors. Use it to centralize resource release while keeping asynchronous lifetime and cancellation behavior explicit.
- [Using defer in Swift to manage state cleanup](https://tanaschita.com/swift-defer)
  **NeKI brief:** Swift defer scopes cleanup and state restoration to a function or block exit. Follow it for loading indicators, locks and temporary resources, especially where multiple early returns would otherwise duplicate cleanup paths.
- [Understanding Sendable in Swift](https://tanaschita.com/swift-concurrency-sendable)
  **NeKI brief:** Explains Sendable and the compiler's concurrency-safety model with practical Swift examples. Use it when auditing values crossing actor boundaries and deciding whether types need immutable storage, explicit conformance, or isolation instead.
- [Understanding actors in Swift](https://tanaschita.com/swift-concurrency-actors-basics)
  **NeKI brief:** Actors serialize access to isolated mutable state while allowing asynchronous calls across the boundary. Follow this guide to decide what belongs in an actor and where Sendable values are still required.
- [Comparing Combine's subjects with AsyncStream in Swift](https://tanaschita.com/swift-combine-subjects-vs-asyncstream)
  **NeKI brief:** Compares Combine subjects with `AsyncStream`, contrasting multicasting and operator ecosystems with Swift Concurrency's cancellation-aware async iteration. Follow it when migrating event pipelines and deciding whether a stream needs replay, multiple consumers, or structured concurrency.
- [How to build a simple CLI tool using Swift](https://tanaschita.com/swift-cli-scripting)
  **NeKI brief:** A Swift CLI parses arguments and performs automation outside an app target. It is useful for building repeatable developer tools, where exit codes, standard output and filesystem errors form the user-facing API.
- [How to call async/await functions concurrently in Swift](https://tanaschita.com/swift-call-async-await-functions-concurrently)
  **NeKI brief:** Concurrent async calls are coordinated with task constructs and awaited results. Follow it to compare parallelism with sequencing, while checking cancellation and shared-state safety before launching independent work together.
- [Safe array subscription in Swift](https://tanaschita.com/swift-basics-safe-array-subscription)
  **NeKI brief:** A safe array subscript returns an optional instead of trapping on an invalid index. Follow it when boundary input is expected, but keep silent absence distinct from a programming error that should still fail loudly.
- [How to use async/await in synchronous Swift code with tasks](https://tanaschita.com/swift-await-async-in-synchronious-swift-code-with-tasks)
  **NeKI brief:** Task provides an entry point from synchronous code into async functions. The article is useful for migration, but its key caution is lifetime: unstructured tasks can outlive the caller unless cancellation is owned explicitly.
- [How to use the @available attribute in Swift](https://tanaschita.com/swift-available-attribute)
  **NeKI brief:** Explains Swift's @available attribute for marking APIs by platform, version, deprecation, or obsolescence. Useful when evolving libraries across OS releases and writing availability annotations that communicate migration paths without accidentally hiding supported code.
- [How to avoid retain cycles when working with tasks in Swift](https://tanaschita.com/swift-async-tasks-memory-management)
  **NeKI brief:** Explains retain-cycle risks around Task closures and reference ownership. Use it when asynchronous work outlives a view or controller and cancellation, weak capture, or task storage determines whether objects release.
- [Understanding task cancellation and lifetimes in Swift concurrency](https://tanaschita.com/swift-async-tasks-cancellation)
  **NeKI brief:** This concurrency guide contrasts structured cancellation with unstructured task lifetimes. Follow it to ensure cleanup and cooperative cancellation reach the actual operation rather than merely discarding a task handle.
- [Understanding Task and Task.detached in Swift concurrency](https://tanaschita.com/swift-async-task-vs-task-detached)
  **NeKI brief:** Task and Task.detached differ in inheritance of actor context, priority and task-local values. The comparison is valuable when choosing isolation deliberately instead of using detached work as a generic background queue.
- [Bridging completion handlers to Swift's async/await](https://tanaschita.com/swift-async-completions-to-async-await)
  **NeKI brief:** withCheckedContinuation bridges completion handlers into async functions while enforcing one resume. Follow it to migrate callback APIs, paying attention to cancellation and exactly-once completion when wrapping delegates.
- [Getting started with async/await in Swift](https://tanaschita.com/swift-async-await)
  **NeKI brief:** This async/await introduction contrasts callback nesting with structured suspension and result handling. It is useful for planning migrations, where actor isolation and cancellation should be designed alongside syntax changes.
- [Transforming AsyncStream with Swift Async Algorithms](https://tanaschita.com/swift-async-algorithms-asyncstream)
  **NeKI brief:** Transforms AsyncStream values with Swift Async Algorithms rather than hand-writing stream plumbing. Use it when throttling, combining, or mapping asynchronous events needs clear cancellation and buffering semantics.
- [Creating a particles snow effect with SpriteKit and SwiftUI](https://tanaschita.com/spritekit-particles-snow-effect-swiftui)
  **NeKI brief:** Embeds a SpriteKit particle system in SwiftUI to render a snow effect, bridging scene lifecycle and view layout. Useful for effects that exceed SwiftUI's native animation primitives.
- [Switching Swift Package Manager dependencies between versioned and local development](https://tanaschita.com/spm-quick-tip-on-switching-to-local-dev)
  **NeKI brief:** Shows how to switch a Swift Package dependency between a versioned remote requirement and a local checkout during development. Use it to test package changes quickly while preserving a clean, reproducible dependency declaration for collaborators and CI.
- [Get started with Swift Package Manager for iOS](https://tanaschita.com/spm-overview)
  **NeKI brief:** Swift Package Manager concepts are explained through package manifests, targets and products. Follow it when modularizing an iOS project, especially to distinguish dependency declaration from the API surface a package exports.
- [How to add public libraries as Swift Packages to an iOS project](https://tanaschita.com/spm-add-public-packages)
  **NeKI brief:** Adding a remote Swift package through Xcode covers version requirements and dependency updates. The guide is useful for reviewing reproducibility and supply-chain boundaries before accepting a package into an app target.
- [How to add local Swift Packages to an iOS project](https://tanaschita.com/spm-add-local-packages)
  **NeKI brief:** Local Swift packages provide a modular dependency boundary during development. Follow it to iterate on shared code without publishing, while keeping target membership and resource ownership explicit.
- [Objective-C basics for Swift developers](https://tanaschita.com/objective-c-for-swift-developers)
  **NeKI brief:** This Objective-C primer highlights classes, messaging, protocols and nullability for Swift developers. It is useful when crossing an interop boundary, where ownership and dynamic dispatch differ from Swift defaults.
- [Understanding LLDB print commands for iOS debugging with Xcode](https://tanaschita.com/lldb-understanding-print-commands)
  **NeKI brief:** LLDB v, p and po commands inspect different representations of runtime values. Follow it to choose the right diagnostic view and avoid mistaking debugger expression behavior for application code.
- [Changing runtime state with LLDB while debugging iOS apps](https://tanaschita.com/lldb-changing-variables-while-debugging)
  **NeKI brief:** LLDB expr can mutate variables and automate breakpoint actions during a paused run. The technique is useful for testing branches quickly, but changes are diagnostic only and must be reproduced in source or tests.
- [Introduction to Kotlin for Swift developers - protocols, extensions & generics](https://tanaschita.com/kotlin-for-swift-developers-part-3)
  **NeKI brief:** Protocols, extensions and generics are contrasted between Kotlin and Swift. The guide is useful for estimating portable abstractions while keeping each platform’s constraint and dispatch rules explicit.
- [Introduction to Kotlin for Swift developers - classes, structs & enums](https://tanaschita.com/kotlin-for-swift-developers-part-2)
  **NeKI brief:** Kotlin classes, structs and enums are compared with Swift value and reference types. Follow it to identify semantic differences before porting models, especially around inheritance, mutation and data-class behavior.
- [Introduction to Kotlin for Swift developers - variables, functions & control flow](https://tanaschita.com/kotlin-for-swift-developers-part-1)
  **NeKI brief:** This Kotlin primer maps variables, functions and control flow from a Swift developer’s perspective. It is useful for cross-platform work where syntax transfers easily but standard-library and nullability assumptions do not.
- [Supporting universal links in a SwiftUI application](https://tanaschita.com/ios-universal-links-swiftui)
  **NeKI brief:** Universal Links connect web URLs to SwiftUI navigation through associated domains and application callbacks. Follow it to trace website, entitlement and routing configuration as one end-to-end contract.
- [Developer guide on Swift Testing for iOS](https://tanaschita.com/ios-swift-testing)
  **NeKI brief:** This Swift Testing guide covers expectations, traits and XCTest migration. It is useful for choosing modern test structure while preserving clear failure diagnostics and keeping required setup separate from behavioral assertions.
- [How to support dark mode in SwiftUI programmatically](https://tanaschita.com/ios-supporting-dark-mode-programmatically)
  **NeKI brief:** Shows programmatic dark-mode control and trait-aware color choices in SwiftUI. Useful when an app offers an appearance setting while still respecting system defaults and semantic colors.
- [How to use String Catalogs for pluralization in Swift](https://tanaschita.com/ios-string-catalogs-pluralization)
  **NeKI brief:** String Catalog pluralization centralizes localized variants with type-safe lookup. Follow it to model grammatical quantities correctly instead of concatenating localized fragments that break in languages with different plural rules.
- [Migrating to String Catalogs in iOS](https://tanaschita.com/ios-string-catalogs-migration)
  **NeKI brief:** Migrating to String Catalogs converts legacy localization resources into .xcstrings while preserving keys and variants. Follow it to plan the file transition separately from product copy changes and avoid silent fallback strings.
- [Working with String Catalogs in iOS projects](https://tanaschita.com/ios-string-catalogs-in-practice)
  **NeKI brief:** Explains adopting String Catalogs for localized iOS content and managing translations in Xcode. Use it when migrating string resources, preserving localization keys, and checking plural or variation coverage before release.
- [SF Symbols guide for SwiftUI and UIKit](https://tanaschita.com/ios-sf-symbols)
  **NeKI brief:** Covers SF Symbols in SwiftUI and UIKit, including layers, rendering modes, scaling, and color customization. Use it to keep iconography consistent and adaptable across interfaces.
- [Understanding privacy manifests in iOS](https://tanaschita.com/ios-privacy-manifests)
  **NeKI brief:** Explains iOS privacy manifests, including required-reason APIs, declarations, and how app and third-party SDK manifests combine. Use it when auditing App Store compliance and documenting data-access reasons without confusing privacy manifests with permission prompts.
- [How to localize plurals with Localizable.stringsdict files in iOS](https://tanaschita.com/ios-plurals-localization-strictdict)
  **NeKI brief:** Localizable.stringsdict handles plural variants through locale-aware rules. Follow it when maintaining older localization resources, avoiding concatenated fragments that fail in languages with different grammatical categories.
- [Adding text input actions to iOS push and local notifications](https://tanaschita.com/ios-notifications-textinput)
  **NeKI brief:** Text-input notification actions collect a short response without opening the app. The guide is useful for category registration and response routing, while treating notification content and user input as untrusted external state.
- [Registering for push notifications in SwiftUI](https://tanaschita.com/ios-notifications-registering-in-swiftui)
  **NeKI brief:** Walks through requesting notification authorization and registering a SwiftUI app for remote notifications. Use it to separate permission timing, device-token registration, and app lifecycle handling instead of treating registration as one synchronous call.
- [How to add custom actions to iOS push and local notifications in SwiftUI](https://tanaschita.com/ios-notifications-custom-actions)
  **NeKI brief:** Custom notification actions define categories and route button responses into SwiftUI application logic. Follow it to keep registration timing, identifiers and background handling aligned across push and local notifications.
- [Quick guide on local notifications for iOS](https://tanaschita.com/ios-local-notifications-guide)
  **NeKI brief:** Local notification scheduling covers authorization, content and trigger configuration through UserNotifications. It is useful for separating scheduling policy from presentation, especially when permissions are denied or requests become stale.
- [Scheduling notifications with time, calendar, and location triggers in iOS](https://tanaschita.com/ios-local-notification-triggers)
  **NeKI brief:** Configures local notification triggers based on time intervals, calendar dates, and locations. Useful for choosing the correct UNNotificationTrigger and validating repeat behavior instead of scheduling every reminder identically.
- [Implementing Face ID authentication in SwiftUI](https://tanaschita.com/ios-local-authentication)
  **NeKI brief:** Integrates LocalAuthentication for Face ID or Touch ID in SwiftUI. Use it when sensitive actions need a platform authentication gate and clear fallback/error handling.
- [Working with the Keychain in iOS](https://tanaschita.com/ios-keychain-secure-data-storage)
  **NeKI brief:** Explains storing sensitive iOS data in Keychain and the accessibility choices that affect availability. Use it when designing credential persistence, selecting protection classes, and separating secrets from ordinary app storage.
- [Quick guide on home screen quick actions for SwiftUI](https://tanaschita.com/ios-home-screen-quick-actions)
  **NeKI brief:** Implements Home Screen quick actions in SwiftUI. Use it when a shortcut should launch directly into an app task while keeping scene activation and routing state explicit.
- [Working with files and directories in iOS](https://tanaschita.com/ios-file-system-overview)
  **NeKI brief:** Maps iOS file-system locations and the responsibilities of app documents, caches, and temporary storage. Use it when choosing a persistence location whose backup, eviction, and user-visibility behavior matches the data.
- [Implementing Passkeys in iOS with AuthenticationServices](https://tanaschita.com/ios-authentication-passkeys)
  **NeKI brief:** Implements passkey authentication with AuthenticationServices, covering request configuration, credential results, and account flow integration. Useful when replacing password login while keeping registration and sign-in state explicit.
- [Understanding associated domains in iOS](https://tanaschita.com/ios-associated-domains-basics)
  **NeKI brief:** Associated Domains links an app to verified web domains for Universal Links, shared credentials and related services. Use precise entitlements and a correctly hosted association file, testing device-side caching and fallback navigation.
- [Using associated domains alternate mode during development](https://tanaschita.com/ios-associated-domains-alternate-mode)
  **NeKI brief:** Explains alternate associated-domains mode for development and testing. Use it when universal-link or web-credential configuration must point at a non-production environment without changing the application's primary entitlement design.
- [Beginners guide to supporting VoiceOver in SwiftUI for better accessibility](https://tanaschita.com/ios-accessibility-voiceover-swiftui-guide)
  **NeKI brief:** Introduces SwiftUI accessibility modifiers alongside Xcode's Accessibility Inspector. Follow it for a beginner-friendly route from inspecting the element tree to correcting labels, traits, and grouping in a real screen.
- [Essential VoiceOver gestures for iOS - a quick guide to testing app accessibility](https://tanaschita.com/ios-accessibility-voiceover-gestures)
  **NeKI brief:** Catalogues essential VoiceOver gestures and a quick toggle workflow for testing. It is useful for establishing a repeatable manual pass that checks focus order and activation instead of relying only on simulator screenshots.
- [Supporting Reduced Motion accessibility setting in SwiftUI](https://tanaschita.com/ios-accessibility-reduced-motion)
  **NeKI brief:** Shows responding to the system Reduced Motion preference in iOS, with SwiftUI-oriented implementation guidance. Follow it when animations communicate state but must be simplified or removed for motion-sensitive users.
- [Overview on Accessibility Nutrition Labels for iOS development](https://tanaschita.com/ios-accessibility-nutrition-labels)
  **NeKI brief:** Explains accessibility nutrition labels and the information developers provide about app data practices. Useful for preparing App Store disclosures alongside actual privacy and analytics implementation.
- [How to support Dynamic Type accessibility in SwiftUI](https://tanaschita.com/ios-accessibility-dynamic-type)
  **NeKI brief:** Covers Dynamic Type support in SwiftUI, including scalable text and layout testing at accessibility sizes. Follow it when fixed frames or custom typography undermine the user's selected reading scale.
- [Supporting sufficient contrast accessibility with Xcode's Color Contrast Calculator](https://tanaschita.com/ios-accessibility-contrast)
  **NeKI brief:** Demonstrates Xcode's Color Contrast Calculator for checking foreground/background combinations. Use it as a concrete visual-QA step for text and controls, especially where custom palette choices may fail low-vision contrast needs.
- [GraphQL essentials for iOS development](https://tanaschita.com/graphql-essentials-for-ios)
  **NeKI brief:** GraphQL essentials frames schema, queries and selected fields from an iOS client perspective. The key trade-off is flexible payload shape versus client and server schema coordination, especially as queries become feature-specific.
- [Getting started with Apollo iOS for GraphQL in Swift](https://tanaschita.com/graphql-apollo-for-ios)
  **NeKI brief:** Apollo iOS generates Swift models and operations from a GraphQL schema and integrates through Swift Package Manager. Follow it to assess generated-code benefits against cache invalidation and schema evolution costs.
- [Getting started with Apple's Foundation Models framework](https://tanaschita.com/foundation-models-getting-started)
  **NeKI brief:** Introduces Apple's Foundation Models framework, its on-device model context, and when it differs from other AI approaches. Follow it for an initial API and capability orientation, then verify deployment requirements against current Apple documentation.
- [Building a dependency injection framework](https://tanaschita.com/dependency-injection-building-lightweight-container)
  **NeKI brief:** Builds a lightweight dependency-injection container in Swift and discusses registration and resolution. Use it to evaluate a small explicit composition mechanism for app services, especially when replacing hidden singletons without introducing a framework-sized abstraction.
- [Symmetric-key cryptography with CryptoKit for iOS](https://tanaschita.com/cryptokit-symmetric-key-cryptography)
  **NeKI brief:** CryptoKit symmetric encryption uses a shared secret to protect data with authenticated cryptography. Follow it to understand key handling and nonce requirements, where algorithm choice cannot compensate for weak secret storage.
- [Public-key cryptography with CryptoKit for iOS](https://tanaschita.com/cryptokit-public-key-cryptography)
  **NeKI brief:** Public-key CryptoKit examples cover encryption and digital signatures without sharing a private key. The guide is useful for separating confidentiality from authenticity and for keeping private keys outside app-controlled distribution.
- [How to set up and use Core Data with SwiftUI](https://tanaschita.com/coredata-with-swiftui)
  **NeKI brief:** Core Data is connected to SwiftUI through managed contexts, fetch requests and model updates. Follow it to examine observation boundaries, especially where view-driven mutations need validation and background persistence.
- [How to perform a lightweight migration in Core Data](https://tanaschita.com/core-data-lightweight-migration)
  **NeKI brief:** Lightweight Core Data migration handles compatible model changes through inferred mapping. The article is useful for deciding when automatic migration is sufficient and when a custom mapping model or staged data transform is required.
- [How to delay server requests for user's search query with SwiftUI and Combine](https://tanaschita.com/combine-swiftui-search-query-debounce)
  **NeKI brief:** Combine debounce delays search requests until input settles, reducing server load and result churn. Follow it to coordinate cancellation and latest-query wins semantics rather than allowing stale responses to replace newer results.
- [A visual cheat sheet of Combine operators](https://tanaschita.com/combine-operators-cheatsheet)
  **NeKI brief:** Maps common Combine operators to transformations, filtering, combination, and scheduling behavior. Follow it when refactoring a publisher pipeline and needing to choose an operator by demand semantics rather than memorized names.
- [Memory management in Combine](https://tanaschita.com/combine-memory-management)
  **NeKI brief:** Combine memory management centers on subscription ownership, cancellables and closure capture. The guide is valuable for diagnosing retain cycles where a publisher pipeline keeps its view model alive after the screen disappears.
- [Introduction to Combine for iOS developers with RxSwift experience](https://tanaschita.com/combine-for-rxswift-devs)
  **NeKI brief:** This RxSwift-to-Combine comparison maps concepts such as publishers, operators and cancellables across frameworks. Follow it during migration to identify semantic differences instead of performing a mechanical name replacement.
- [Quick guide to Combine essentials in Swift programming](https://tanaschita.com/combine-essentials)
  **NeKI brief:** Combine essentials introduces publishers, subscribers and operator chains for asynchronous events. It is useful for establishing vocabulary and lifecycle ownership before adopting more specialized subjects or scheduling strategies.
- [How to use a Connectable publisher in Combine](https://tanaschita.com/combine-connectable-publisher)
  **NeKI brief:** Connectable publishers defer emission until explicitly connected, giving callers control over start timing. Follow it when multiple subscribers must observe one shared sequence without triggering duplicate upstream work.
- [Understanding backpressure in Combine - efficient data handling in Swift](https://tanaschita.com/combine-back-pressure)
  **NeKI brief:** Combine backpressure lets a subscriber control demand instead of accepting unlimited values. The article is useful for high-volume streams, where demand strategy and buffering determine memory and responsiveness.
- [How to use TipKit to create tool tips in SwiftUI](https://tanaschita.com/20240304-tipkit-feature-hints)
  **NeKI brief:** Introduces TipKit feature hints and rules for surfacing contextual education in SwiftUI. Useful for replacing custom onboarding flags with system-managed tip eligibility and dismissal state.
- [How to delay an animation in SwiftUI](https://tanaschita.com/20240226-delay-swiftui-animation)
  **NeKI brief:** Shows delaying a SwiftUI animation by combining state changes with an explicit animation delay. Use it for staged appearances or timed UI transitions, while keeping cancellation and repeated-trigger behavior predictable.
- [Get started with auto‑renewable subscriptions for iOS](https://tanaschita.com/20231211-auto-renewable-subscriptions)
  **NeKI brief:** StoreKit 2 auto-renewable subscriptions are introduced through product loading, purchase and entitlement checks. Follow it to keep transaction verification and subscription state distinct from paywall presentation.
- [How to implemet a free trial period for StoreKit 2 subscriptions in iOS](https://tanaschita.com/20231113-subscriptions-introductory-offers)
  **NeKI brief:** StoreKit 2 introductory offers apply eligibility and offer configuration to subscription purchases. The guide is useful for separating App Store product metadata from local UI, while treating eligibility as server-verified state.
- [Introduction to bash scripting for iOS developers](https://tanaschita.com/20231023-bash-scripting-for-ios-devs)
  **NeKI brief:** Bash scripting examples automate repeatable iOS development tasks outside Xcode. The useful boundary is treating arguments, exit codes and environment variables as a stable tool contract rather than a shell-only convenience.
- [How to restore in-app purchases with StoreKit 2 for iOS](https://tanaschita.com/20231009-restore-in-app-purchases-storekit)
  **NeKI brief:** StoreKit 2 restore flows inspect current entitlements and transaction history rather than trusting a button callback. Follow it to make reinstalls and multi-device purchases converge on verified local access state.
- [Get started with StoreKit 2 for iOS](https://tanaschita.com/20231002-storekit-2-overview)
  **NeKI brief:** StoreKit 2 product loading and purchases are introduced through async APIs and verified transactions. Follow it to separate entitlement state from paywall UI and to keep verification on the trusted path.
- [How to intercept and edit a server response with Proxyman for iOS](https://tanaschita.com/20230918-proxyman-how-to-change-request)
  **NeKI brief:** Proxyman breakpoint rules intercept and edit responses to exercise client edge cases. It is useful for testing error and empty states, provided interception remains confined to development traffic and credentials.
- [How to manually subscribe to changes of SwiftUI's @Observable objects](https://tanaschita.com/20230822-observation-framework-subscribe-to-changes)
  **NeKI brief:** Observation allows manual subscription to changes from @Observable models. Follow it to understand registrar-driven updates and when explicit observation is justified instead of relying on SwiftUI’s automatic tracking.
- [The difference between @StateObject and @ObservedObject in SwiftUI](https://tanaschita.com/20230731-stateobject-observedobject-swiftui)
  **NeKI brief:** The StateObject versus ObservedObject distinction explains ownership and recreation across SwiftUI redraws. It is essential when diagnosing lost state, especially where a view creates versus receives its observable model.
- [How to automate taking screenshots with fastlane for iOS](https://tanaschita.com/20230724-fastlane-screenshots-ios)
  **NeKI brief:** Fastlane automates localized App Store screenshots through repeatable simulator runs. Follow it to keep devices, schemes and locale data deterministic, turning a manual release artifact into a checked pipeline output.
- [Beginner's guide on Flutter for iOS developers](https://tanaschita.com/20230717-flutter-for-ios-developers)
  **NeKI brief:** Compares Flutter concepts with familiar iOS development patterns. Use it when evaluating cross-platform trade-offs around widget composition, state, platform integration, and the boundary between shared UI and native behavior.
- [Quick tip on how to split text into words with the Natural Language framework in Swift.](https://tanaschita.com/20230619-tokenizing-words-with-natural-language-framework)
  **NeKI brief:** Natural Language tokenization splits text according to linguistic boundaries rather than simple whitespace. The guide is useful for search and text analysis where punctuation, Unicode and locale affect token meaning.
- [How to find synonyms with the Natural Language framework for iOS](https://tanaschita.com/20230612-find-similar-words-natural-language-framework-ios)
  **NeKI brief:** Natural Language similarity APIs compare words or sentences for relatedness. Follow it to evaluate semantic matching without building a model, while treating scores as heuristic signals rather than exact equivalence.
- [How to map a SwiftUI state to a binding of a different type](https://tanaschita.com/20230605-swiftui-state-binding-different-types)
  **NeKI brief:** A custom SwiftUI Binding maps state through a getter and setter of different types. The article is useful for adapting controls without duplicating source of truth, provided conversion failures remain explicit.
- [Continuous integration and delivery for iOS](https://tanaschita.com/20230529-continuous-integration-and-delivery-for-ios)
  **NeKI brief:** CI/CD concepts are mapped onto an iOS workflow covering tests, signing and distribution. Follow it to separate build verification from release promotion, with credentials and environment configuration treated as pipeline inputs.
- [How to identify parts of speech and names in a text with Swift](https://tanaschita.com/20230515-natural-language-framework-linguistic-tags)
  **NeKI brief:** Linguistic tagging identifies parts of speech and named entities in text. It is useful for lightweight content analysis, where tokenization, locale selection and confidence handling matter more than a binary label.
- [How to detect the language of a text with the Natural Language framework in Swift](https://tanaschita.com/20230501-detect-language-with-natural-language-framework)
  **NeKI brief:** Natural Language language recognition infers a text’s likely language from content. Follow it for routing localization or search behavior, while handling short or ambiguous strings as uncertain results.
- [Developer guide on App Clips for iOS](https://tanaschita.com/20230424-app-clips)
  **NeKI brief:** This App Clip guide connects invocation, associated domains and a focused task flow. It is useful for designing a small install-free experience that can hand off state cleanly to the full app.
- [Cheatsheet for the JSON payload of an iOS push notification](https://tanaschita.com/20230417-cheatsheet-for-anatomy-of-ios-push-notifications)
  **NeKI brief:** The push payload cheatsheet distinguishes alert, sound, badge and custom data fields. Follow it when debugging delivery behavior, keeping payload size, background execution and sensitive content constraints visible.
- [How to scan QR codes with VisionKit for iOS](https://tanaschita.com/20230410-how-to-scan-qr-codes-with-visionkit-for-ios)
  **NeKI brief:** VisionKit’s DataScannerViewController scans QR codes through a camera-backed system UI. The guide is useful for permission and availability handling, while keeping recognized payloads validated before acting on them.
- [Get started with Create ML to train a machine learning model in iOS](https://tanaschita.com/20230403-train-ml-model-with-create-ml-ios)
  **NeKI brief:** Shows training a Create ML model and integrating its output into an iOS app. Follow it when routing dataset preparation, model export, and on-device inference responsibilities across the development workflow.
- [Get started with NSPredicate to filter NSFetchRequest in Core Data](https://tanaschita.com/20230320-cheatsheet-nspredicate-fetchrequest-core-data)
  **NeKI brief:** NSPredicate filters NSFetchRequest results with composable conditions and comparisons. Follow it to keep filtering in the persistence layer, while validating format strings and avoiding broad in-memory scans.
- [Developer guide on machine learning for iOS with Core ML](https://tanaschita.com/20230313-machine-learning-ios-core-ml)
  **NeKI brief:** Provides an introductory path from basic machine-learning concepts to loading and using Core ML models in iOS. Follow it when onboarding to the model-consumption boundary, but treat current API and deployment details as version-sensitive.
- [Quick tip on how to unit test Swift optionals with XCTUnwrap](https://tanaschita.com/20230306-xctunwrap-quick-tip)
  **NeKI brief:** Presents a concise XCTest technique for unwrapping optionals with useful failure output. Use it to keep test setup readable while preserving clear diagnostics when required fixtures are missing.
- [Quick guide on fastlane for iOS development](https://tanaschita.com/20230213-fastlane-ios-developer-guide)
  **NeKI brief:** Fastlane organizes testing, signing and App Store delivery into repeatable lanes. The guide is useful for making release steps explicit, with credentials and environment-specific configuration kept out of source control.
- [How to import Objective-C types as optionals or non-optionals into Swift](https://tanaschita.com/20230130-nullability-declarations-objective-c)
  **NeKI brief:** Objective-C nullability annotations determine whether imported Swift values are optional. Follow it when maintaining mixed-language frameworks, where accurate headers prevent defensive unwraps and incorrect non-optional assumptions.
- [Authorizing App Store Connect API requests](https://tanaschita.com/20221226-authorizing-app-store-connect-api-requests)
  **NeKI brief:** App Store Connect API authorization combines an API key with a signed JWT. Follow it to understand issuer, audience and expiration claims, while keeping the private key in a protected automation environment.
- [Developer guide on iOS code signing & provisioning](https://tanaschita.com/20221212-code-signing-and-provisioning-for-ios)
  **NeKI brief:** Code signing and provisioning connect certificates, profiles, entitlements and bundle identifiers. The guide is useful for diagnosing build and distribution failures by separating identity, capability and installation concerns.
- [Developer guide on the App Store Connect API](https://tanaschita.com/20221128-app-store-connect-api-quide)
  **NeKI brief:** The App Store Connect API automates metadata and release operations through authenticated requests. Follow it to identify which manual portal tasks can become repeatable jobs, while respecting rate limits and role permissions.
- [How to handle non-optional Core Data properties in Swift](https://tanaschita.com/20221114-how-to-handle-non-optional-core-data-values-in-swift)
  **NeKI brief:** Explains handling Core Data attributes that are non-optional in Swift models despite migration or generated-code constraints. Follow it when aligning schema validation, managed-object access, and safe defaulting behavior.
- [Understanding different cache policies when working with URLRequest in Swift](https://tanaschita.com/20221031-managing-cache-when-working-with-urlsession-in-ios)
  **NeKI brief:** URLRequest cache policies control reuse, validation and network freshness. The comparison is useful for choosing per-request behavior rather than applying a global cache assumption to every endpoint.
- [How to create NSManagedObject subsclasses for Core Data entities in Xcode](https://tanaschita.com/20221024-how-to-create-a-managed-object-subclass-xcode-core-data)
  **NeKI brief:** Core Data code-generation modes determine which managed-object classes Xcode owns or expects developers to maintain. Follow it to prevent generated files being overwritten and to keep model changes aligned with source extensions.
- [Using URLSession with async/await in Swift](https://tanaschita.com/20221017-using-urlsession-with-async-await)
  **NeKI brief:** URLSession async APIs turn HTTP responses into structured suspension and typed decoding. The guide is useful for cancellation and error propagation, especially where a view task should not outlive its request context.
- [iOS developer guide on the main aspects of Core Data](https://tanaschita.com/20220919-understanding-the-main-aspects-of-core-data)
  **NeKI brief:** This Core Data overview connects model files, contexts, stores and fetches into one persistence architecture. Follow it to establish terminology before deciding where observation, background work and migrations belong.
- [How to bridge async/await functions to Combine's Future type in Swift](https://tanaschita.com/20220822-bridge-async-await-to-combine-future)
  **NeKI brief:** Bridges async/await work into Combine Future. Use it when a legacy publisher pipeline must call modern asynchronous APIs during an incremental concurrency migration.
- [Implementing Password AutoFill for an iOS application](https://tanaschita.com/20220815-supporting-password-autofill-for-ios-appilcations)
  **NeKI brief:** Password AutoFill relies on text-content types and associated domains to connect app fields with system credentials. Follow it to keep autofill configuration aligned across UIKit, SwiftUI and the website domain.
- [Quick guide on Proxyman for iOS development](https://tanaschita.com/20220704-quick-guide-on-proxyman)
  **NeKI brief:** Introduces Proxyman for inspecting iOS network traffic. Use it when HTTPS requests, payloads, and response failures need external debugging evidence.
