# Donny Wals

Third-party source index. It provides source attribution and routing metadata, not republished article content. Verify article conclusions independently before applying them.

- Archive: [https://www.donnywals.com/the-blog/](https://www.donnywals.com/the-blog/)
- Last collected: `2026-07-22T21:58:56Z`
- Indexed entries: **308**

- [Installing simulator runtimes from the command line – Donny Wals](https://www.donnywals.com/installing-simulator-runtimes-from-the-command-line)
  **Published:** `2026-06-09T13:49:17+00:00`
  **Topics:** Xcode
  **NeKI brief:** Explains installing Xcode Simulator runtimes from the command line. Use it when CI or a fresh development machine must provision a specific runtime reproducibly instead of relying on Xcode's graphical download flow.
- [How I use FlowDeck to let my AI agent build and run my apps – Donny Wals](https://www.donnywals.com/how-i-use-flowdeck-to-let-my-ai-agent-build-and-run-my-apps)
  **Published:** `2026-04-17T12:43:41+00:00`
  **Topics:** Xcode
  **NeKI brief:** Describes an agent workflow that can build and run an iOS app through FlowDeck. Follow it to inspect the boundary between generated code, simulator execution, and human review before adopting agent-controlled delivery loops.
- [Setting up a delivery pipeline for your agentic iOS projects – Donny Wals](https://www.donnywals.com/setting-up-a-delivery-pipeline-for-your-agentic-ios-projects)
  **Published:** `2026-02-16T07:00:39+00:00`
  **Topics:** AI Development · Testing
  **NeKI brief:** Connects agentic planning and local setup with BugBot pull-request review, Bitrise builds, and rapid TestFlight feedback. Use it to design a delivery loop where generated changes meet automated gates before human device validation.
- [The importance of human touch in AI-driven development – Donny Wals](https://www.donnywals.com/the-importance-of-human-touch-in-ai-driven-development)
  **Published:** `2026-02-06T08:00:00+00:00`
  **Topics:** Developer Career & Practice
  **NeKI brief:** AI-generated code increases throughput but shifts value toward review, product judgment, and context; human checkpoints remain the mechanism for catching plausible but wrong changes.
- [Migrating an iOS app from Paid up Front to Freemium – Donny Wals](https://www.donnywals.com/migrating-an-ios-app-from-paid-up-front-to-freemium)
  **Published:** `2026-01-30T08:34:51+00:00`
  **Topics:** Testing
  **NeKI brief:** Documents the product and StoreKit decisions involved in moving an app from paid-up-front to freemium. Useful as business migration context, not as a universal monetization prescription.
- [A Deep Dive into SwiftData migrations – Donny Wals](https://www.donnywals.com/a-deep-dive-into-swiftdata-migrations)
  **Published:** `2026-01-19T12:23:36+00:00`
  **Topics:** Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** Walks through SwiftData migration planning with the uncomfortable case of real users upgrading persisted data. Use it to identify schema-change hazards, staged model versions, and validation work needed before shipping a store update.
- [A deep dive into Collections, Sequences, and Iterators in Swift – Donny Wals](https://www.donnywals.com/a-deep-dive-into-collections-sequences-and-iterators-in-swift)
  **Published:** `2025-11-05T11:49:20+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Clarifies the relationship between Collection, Sequence, and IteratorProtocol in Swift. Use it when a custom data source needs the right traversal guarantees and you must distinguish single-pass iteration from multi-pass indexed access.
- [Using Observations to observe @Observable model properties – Donny Wals](https://www.donnywals.com/using-observations-to-observe-observable-model-properties)
  **Published:** `2025-09-24T11:27:53+00:00`
  **Topics:** Observation & State Management · Xcode
  **NeKI brief:** Uses Observation tracking to react to specific model property reads rather than broad object changes. Useful for reducing unnecessary SwiftUI updates and understanding what actually establishes a dependency.
- [How to unwrap [weak self] in Swift Concurrency Tasks? – Donny Wals](https://www.donnywals.com/how-to-use-weak-self-in-swift-concurrency-tasks)
  **Published:** `2025-09-18T13:56:57+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Explains how weak self interacts with Swift concurrency tasks and object lifetime. Use it to choose capture strategies deliberately, avoiding retain cycles without accidentally discarding work that should complete.
- [Should you opt-in to Swift 6.2’s Main Actor isolation? – Donny Wals](https://www.donnywals.com/should-you-opt-in-to-swift-6-2s-main-actor-isolation)
  **Published:** `2025-09-11T13:59:33+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Weighs opting into Swift 6.2 default MainActor isolation, including migration benefits and accidental UI-executor work. Useful for choosing a project-wide concurrency baseline deliberately.
- [What is Approachable Concurrency in Xcode 26? – Donny Wals](https://www.donnywals.com/what-is-approachable-concurrency-in-xcode-26)
  **Published:** `2025-07-09T11:00:33+00:00`
  **Topics:** Concurrency · Swift · Swift Package Manager · Xcode
  **NeKI brief:** Explains Xcode 26's approachable concurrency settings and how default actor isolation changes migration ergonomics. Useful when staging strict concurrency adoption without immediately annotating every legacy declaration.
- [Ternary operator in Swift explained – Donny Wals](https://www.donnywals.com/ternary-expressions-in-swift-explained)
  **Published:** `2025-07-07T18:26:19+00:00`
  **Topics:** Swift
  **NeKI brief:** The ternary expression is concise for a small value choice, but replacing nested or effectful branches with if expressions preserves readability and debugging context.
- [Supporting Universal Links on iOS – Donny Wals](https://www.donnywals.com/supporting-universal-links-on-ios)
  **Published:** `2025-07-04T10:02:51+00:00`
  **Topics:** Testing
  **NeKI brief:** Universal Links pair an associated-domains entitlement with a server association file, routing verified URLs into the app while leaving unverified links safely on the web.
- [Grouping Liquid Glass components using glassEffectUnion on iOS 26 – Donny Wals](https://www.donnywals.com/grouping-liquid-glass-components-using-glasseffectunion-on-ios-26)
  **Published:** `2025-07-02T09:53:46+00:00`
  **Topics:** Liquid Glass
  **NeKI brief:** Explains glassEffectUnion for combining multiple Liquid Glass components into one connected visual shape on iOS 26. Follow it when grouped controls should read as a single surface while retaining separate layout, interaction, and accessibility semantics.
- [Designing custom UI with Liquid Glass on iOS 26 – Donny Wals](https://www.donnywals.com/designing-custom-ui-with-liquid-glass-on-ios-26)
  **Published:** `2025-07-01T18:27:48+00:00`
  **Topics:** Liquid Glass
  **NeKI brief:** Explores custom Liquid Glass composition on iOS 26, including grouping and material boundaries. Useful for matching the system visual language without treating every translucent surface as interchangeable.
- [Solving actor-isolated protocol conformance related errors in Swift 6.2 – Donny Wals](https://www.donnywals.com/solving-actor-isolated-protocol-conformance-related-errors-in-swift-6-2)
  **Published:** `2025-06-27T15:08:23+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Actor-isolated conformances restrict protocol use to a chosen actor, resolving Swift 6.2 isolation diagnostics; callers outside that actor must accept async or isolation handoffs.
- [What is @concurrent in Swift 6.2? – Donny Wals](https://www.donnywals.com/what-is-concurrent-in-swift-6-2)
  **Published:** `2025-06-23T10:29:31+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Introduces the @concurrent attribute in Swift 6.2 and its relationship to actor isolation and explicitly concurrent execution. Use it when reviewing performance-sensitive code and deciding where opt-in parallel work is safe without weakening data-race guarantees.
- [Exploring tab bars on iOS 26 with Liquid Glass – Donny Wals](https://www.donnywals.com/exploring-tab-bars-on-ios-26-with-liquid-glass)
  **Published:** `2025-06-19T11:31:50+00:00`
  **Topics:** Liquid Glass
  **NeKI brief:** Examines iOS 26 tab bars under Liquid Glass and the behavior of prominent tab presentation. Useful for designing navigation that respects new system hierarchy and interaction expectations.
- [Opting your app out of the Liquid Glass redesign with Xcode 26 – Donny Wals](https://www.donnywals.com/opting-your-app-out-of-the-liquid-glass-redesign-with-xcode-26)
  **Published:** `2025-06-10T08:46:38+00:00`
  **Topics:** Liquid Glass · Xcode
  **NeKI brief:** Explains the Xcode 26 compatibility option for temporarily opting an app out of Liquid Glass styling. Use it to plan a staged visual migration, not as a long-term substitute for testing the redesigned system components.
- [Setting default actor isolation in Xcode 26 – Donny Wals](https://www.donnywals.com/setting-default-actor-isolation-in-xcode-26)
  **Published:** `2025-06-10T08:00:12+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Shows configuring default actor isolation in Xcode 26 and the resulting compiler assumptions. Useful for making concurrency policy explicit at project scope instead of annotating declarations reactively.
- [Exploring concurrency changes in Swift 6.2 – Donny Wals](https://www.donnywals.com/exploring-concurrency-changes-in-swift-6-2)
  **Published:** `2025-05-20T08:30:04+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Swift 6.2 adjusts concurrency defaults and diagnostics to reduce migration friction, but teams still need explicit isolation decisions when legacy synchronous APIs cross actor boundaries.
- [Enabling upcoming feature flags in an SPM package – Donny Wals](https://www.donnywals.com/enabling-upcoming-feature-flags-in-an-spm-package)
  **Published:** `2025-05-19T07:43:57+00:00`
  **Topics:** Swift · Xcode
  **NeKI brief:** SwiftPM settings can enable evolution feature flags before a language mode ships, allowing controlled experiments while risking CI divergence if package and compiler versions differ.
- [Should you use network connectivity checks in Swift? – Donny Wals](https://www.donnywals.com/should-you-use-network-connectivity-checks-in-swift)
  **Published:** `2025-05-16T09:21:44+00:00`
  **Topics:** Networking · Swift
  **NeKI brief:** Examines whether explicit network connectivity checks are useful in Swift apps. Use it to distinguish reachability hints from actual request outcomes and avoid blocking networking on unreliable preflight state.
- [Choosing between LazyVStack, List, and VStack in SwiftUI – Donny Wals](https://www.donnywals.com/choosing-between-lazyvstack-list-and-vstack-in-swiftui)
  **Published:** `2025-05-08T18:21:32+00:00`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Compares VStack, LazyVStack, and List across rendering, behavior, and platform features. Useful for choosing a container based on data size, recycling needs, and built-in interaction rather than habit.
- [Differences between Thread.sleep and Task.sleep explained – Donny Wals](https://www.donnywals.com/differences-between-thread-sleep-and-task-sleep-explained)
  **Published:** `2025-05-01T08:13:38+00:00`
  **Topics:** Swift
  **NeKI brief:** Thread.sleep blocks an executor thread whereas Task.sleep suspends an async task, so choosing the latter preserves cooperative concurrency and cancellation behavior.
- [Protecting mutable state with Mutex in Swift – Donny Wals](https://www.donnywals.com/protecting-mutable-state-with-mutex-in-swift)
  **Published:** `2025-04-30T08:18:44+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Mutex offers synchronous protected access when an actor would force asynchronous APIs, making it useful for small critical regions but placing deadlock and lock-duration responsibility on the caller.
- [Using singletons in Swift 6 – Donny Wals](https://www.donnywals.com/using-singletons-in-swift-6)
  **Published:** `2025-04-23T09:41:05+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Revisits singleton state under Swift 6 concurrency checking, including isolation and Sendable implications. Useful for deciding whether a shared instance is safe or should become an injected actor-owned dependency.
- [Using Instruments to profile a SwiftUI app – Donny Wals](https://www.donnywals.com/using-instruments-to-profile-a-swiftui-app)
  **Published:** `2025-04-16T09:45:47+00:00`
  **Topics:** Performance · Swift · SwiftUI
  **NeKI brief:** Profiles a SwiftUI app with Instruments to connect view updates and runtime cost to measured workloads. Useful for replacing assumptions about rendering performance with trace evidence.
- [Staying productive as an indie developer – Donny Wals](https://www.donnywals.com/staying-productive-as-an-indie-developer)
  **Published:** `2025-04-09T09:00:57+00:00`
  **Topics:** Developer Career & Practice
  **NeKI brief:** Independent productivity is organized around protecting focus and choosing sustainable scope, a trade-off that favors shipping continuity over maximizing simultaneous ideas.
- [Implementing Task timeout with Swift Concurrency – Donny Wals](https://www.donnywals.com/implementing-task-timeout-with-swift-concurrency)
  **Published:** `2025-04-01T08:33:07+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** A timeout races work against a sleeping task and cancels the loser, giving structured callers a bounded result; cancellation only works if the operation cooperatively checks it.
- [How to plan a migration to Swift 6 – Donny Wals](https://www.donnywals.com/how-to-plan-a-migration-to-swift-6)
  **Published:** `2025-03-06T14:18:33+00:00`
  **Topics:** Architecture · Concurrency · Swift
  **NeKI brief:** Swift 6 migration is staged by measuring strict-concurrency diagnostics, fixing isolation boundaries, and tightening settings incrementally; postponing ownership decisions merely defers compile-time failures.
- [What’s new in Swift 6.1? – Donny Wals](https://www.donnywals.com/whats-new-in-swift-6-1)
  **Published:** `2025-02-27T13:24:04+00:00`
  **Topics:** Swift · Xcode
  **NeKI brief:** Summarizes the smaller Swift 6.1 release in Xcode 16.3, including TaskGroup behavior and imported-member visibility changes.
- [Why you should keep your git commits small and meaningful – Donny Wals](https://www.donnywals.com/why-you-should-keep-your-git-commits-small-and-meaningful)
  **Published:** `2025-02-19T16:00:18+00:00`
  **Topics:** Developer Career & Practice · Developer Tools
  **NeKI brief:** Small commits preserve reviewable intent and make rollback or bisecting practical, though overly fragmented history can obscure a feature's cohesive change.
- [Observing properties on an @Observable class outside of SwiftUI views – Donny Wals](https://www.donnywals.com/observing-properties-on-an-observable-class-outside-of-swiftui-views)
  **Published:** `2025-01-21T10:59:24+00:00`
  **Topics:** Macros & Metaprogramming · Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Observation can track an @Observable property from non-view code, extending SwiftUI's dependency model to coordinators while requiring a lifetime-managed observation scope.
- [Solving “Main actor-isolated property can not be referenced from a Sendable closure” in Swift – Donny Wals](https://www.donnywals.com/solving-main-actor-isolated-property-can-not-be-referenced-from-a-sendable-closure-in-swift)
  **Published:** `2025-01-10T09:17:29+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Diagnoses the compiler error caused by accessing main-actor-isolated state from a Sendable closure and presents isolation-aware fixes. Use it when migrating Swift concurrency code, choosing capture strategies, and preserving actor boundaries rather than silencing diagnostics.
- [Is 2025 the year to fully adopt Swift 6? – Donny Wals](https://www.donnywals.com/is-2025-the-year-to-fully-adopt-swift-6)
  **Published:** `2025-01-09T15:02:54+00:00`
  **Topics:** Swift · Xcode
  **NeKI brief:** Full Swift 6 adoption is framed as a staged team decision: enable diagnostics, budget isolation fixes, and align dependencies before strict mode turns warnings into blocking errors.
- [Sending vs Sendable in Swift – Donny Wals](https://www.donnywals.com/sending-vs-sendable-in-swift)
  **Published:** `2024-12-18T09:50:16+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** sending transfers a value across an isolation boundary once, while Sendable describes reusable safe sharing; confusing them leads either to needless copying or unsafe concurrent access.
- [Mocking a network connection in your Swift Tests – Donny Wals](https://www.donnywals.com/mocking-a-network-connection-in-your-swift-tests)
  **Published:** `2024-12-12T09:56:48+00:00`
  **Topics:** Dependency Injection · Networking · Swift · Testing
  **NeKI brief:** Injecting a controllable network connection keeps Swift tests deterministic and offline, letting failures assert request and response behavior without relying on a live server.
- [Testing completion handler based code in Swift Testing – Donny Wals](https://www.donnywals.com/testing-completion-handler-based-code-in-swift-testing)
  **Published:** `2024-12-04T09:10:47+00:00`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Completion-handler APIs are adapted into async Swift Testing tests, where continuations and explicit expectations expose callback ordering; missing exactly-once resumption can hang the suite.
- [Testing requirements with #require in Swift Testing – Donny Wals](https://www.donnywals.com/testing-requirements-with-require-in-swift-testing)
  **Published:** `2024-11-28T14:02:48+00:00`
  **Topics:** Macros & Metaprogramming · Swift · Testing
  **NeKI brief:** #require turns prerequisite failures into thrown test exits, separating invalid setup from behavioral assertions; use it sparingly so ordinary expectation failures still report together.
- [Asserting state with #expect in Swift Testing – Donny Wals](https://www.donnywals.com/asserting-state-with-expect-in-swift-testing)
  **Published:** `2024-11-21T10:45:26+00:00`
  **Topics:** Swift · Testing
  **NeKI brief:** #expect records failed boolean assertions without aborting the test, so multiple state mismatches can be reported together instead of hiding later failures behind one early exit.
- [Improving test coverage with parameterized tests in Swift testing](https://www.donnywals.com/improving-test-coverage-with-parameterized-tests-in-swift-testing)
  **Published:** `2024-10-31T09:59:49+00:00`
  **Topics:** Swift · Testing
  **NeKI brief:** Parameterized Swift Testing runs one test body over representative inputs, reducing duplicated setup while preserving per-case diagnostics and making boundary coverage easier to expand.
- [Swift Testing basics explained – Donny Wals](https://www.donnywals.com/swift-testing-basics-explained)
  **Published:** `2024-10-23T10:11:38+00:00`
  **Topics:** Swift · Testing
  **NeKI brief:** Swift Testing replaces XCTest ceremony with traits, expectations, and async tests, shifting suite design toward declarative metadata and explicit required setup.
- [Testing completion handler APIs with Swift Testing – Donny Wals](https://www.donnywals.com/testing-completion-handler-apis-with-swift-testing)
  **Published:** `2024-10-16T13:53:50+00:00`
  **Topics:** Swift · Testing
  **NeKI brief:** Completion handlers are bridged into async tests with continuations, making callback order testable; the continuation must resume exactly once or the test can deadlock.
- [What is dependency injection in Swift? – Donny Wals](https://www.donnywals.com/what-is-dependency-injection-in-swift)
  **Published:** `2024-10-11T07:37:29+00:00`
  **Topics:** Architecture · Dependency Injection · Swift
  **NeKI brief:** Dependency injection moves construction decisions out of business logic, enabling deterministic fakes and environment-specific services while adding initializer or container wiring.
- [Mesh Gradients in SwiftUI explained – Donny Wals](https://www.donnywals.com/getting-started-with-mesh-gradients-on-ios-18)
  **Published:** `2024-09-25T09:59:15+00:00`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Mesh gradients interpolate color across a controllable grid, producing richer SwiftUI backgrounds than linear gradients while increasing rendering and animation cost.
- [Animating SF Symbols on iOS 18 – Donny Wals](https://www.donnywals.com/animating-sf-symbols-on-ios-18)
  **Published:** `2024-09-04T07:38:55+00:00`
  **Topics:** UIKit
  **NeKI brief:** Uses iOS 18 SF Symbol animation APIs to express state changes through semantic symbol effects. Useful for lightweight feedback that remains aligned with the symbol's meaning and accessibility labels.
- [Solving “Value of non-Sendable type accessed after being transferred; later accesses could race;” – Donny Wals](https://www.donnywals.com/solving-value-of-non-sendable-type-accessed-after-being-transferred-later-accesses-could-race)
  **Published:** `2024-08-23T08:48:20+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** The transfer diagnostic indicates a value is used after crossing isolation; fixing ownership or making the type Sendable is safer than silencing the warning with unchecked annotations.
- [Setting the Swift Language mode for an SPM Package – Donny Wals](https://www.donnywals.com/setting-the-swift-language-mode-for-an-spm-package)
  **Published:** `2024-08-21T17:59:32+00:00`
  **Topics:** Swift · Swift Package Manager · Xcode
  **NeKI brief:** An SPM package's tools version and swiftLanguageModes determine which compiler rules apply, allowing staged Swift 6 adoption but risking inconsistent settings across package targets.
- [Solving “Task-isolated value of type ‘() async -> Void’ passed as a strongly transferred parameter”](https://www.donnywals.com/solving-task-isolated-value-of-type-async-void-passed-as-a-strongly-transferred-parameter)
  **Published:** `2024-08-21T08:38:51+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** The strongly transferred task diagnostic exposes an escaping closure that captures task-isolated state; restructuring captures or adding Sendable boundaries preserves race safety.
- [Solving “reference to var myVariable is not concurrency-safe because it involves shared mutable state” in Swift](https://www.donnywals.com/solving-reference-to-var-myvariable-is-not-concurrency-safe-because-it-involves-shared-mutable-state-in-swift)
  **Published:** `2024-08-15T09:50:01+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Strict concurrency rejects global or shared mutable variables because accesses can race; actor isolation or immutable snapshots provide a real ownership boundary.
- [Solving “Converting non-sendable function value may introduce data races” in Swift](https://www.donnywals.com/solving-converting-non-sendable-function-value-may-introduce-data-races-in-swift)
  **Published:** `2024-08-12T13:23:21+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Converting a non-Sendable closure across isolation can capture unsafe state, so annotating the closure or redesigning its inputs is preferable to forcing an unchecked send.
- [What are Optionals in Swift? – Donny Wals](https://www.donnywals.com/what-are-optionals-in-swift)
  **Published:** `2024-08-12T09:12:16+00:00`
  **Topics:** Swift
  **NeKI brief:** Optionals encode absence in the type system, forcing callers to choose defaulting, branching, or propagation instead of letting null values reach arbitrary runtime failures.
- [Solving “Capture of non-sendable type in @Sendable closure” in Swift](https://www.donnywals.com/solving-capture-of-non-sendable-type-in-sendable-closure-in-swift)
  **Published:** `2024-08-07T09:28:12+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** A Sendable closure cannot safely capture non-Sendable state across isolation; moving access behind an actor or capturing an immutable value preserves the compiler's race guarantee.
- [Solving “Reference to captured var in concurrently-executing code” in Swift](https://www.donnywals.com/solving-reference-to-captured-var-in-concurrently-executing-code-in-swift)
  **Published:** `2024-07-31T14:42:57+00:00`
  **Topics:** Swift
  **NeKI brief:** Captured mutable locals become unsafe when concurrently executed, so making a snapshot or isolating mutation removes the race instead of weakening diagnostics.
- [Adding values to the SwiftUI environment with @Entry – Donny Wals](https://www.donnywals.com/adding-values-to-the-swiftui-environment-with-entry)
  **Published:** `2024-07-15T07:10:54+00:00`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** The @Entry macro adds typed SwiftUI environment values with less boilerplate, while default semantics still need careful design so missing injections fail predictably.
- [Let and var in Swift explained – Donny Wals](https://www.donnywals.com/let-and-var-in-swift-explained)
  **Published:** `2024-07-12T07:10:10+00:00`
  **Topics:** Swift
  **NeKI brief:** Choosing let over var narrows mutation and communicates ownership intent, making compiler-enforced immutability a simple way to reduce accidental state changes.
- [Using PreviewModifier to build a previewing environment – Donny Wals](https://www.donnywals.com/using-previewmodifier-to-build-a-previewing-environment)
  **Published:** `2024-07-10T18:18:01+00:00`
  **Topics:** Xcode
  **NeKI brief:** Uses PreviewModifier to centralize mock-data setup and other reusable dependencies for richer Xcode preview environments.
- [Mixing colors in SwiftUI and Xcode 16 – Donny Wals](https://www.donnywals.com/mixing-colors-in-swiftui-and-xcode-16)
  **Published:** `2024-06-18T18:28:22+00:00`
  **Topics:** Swift · SwiftUI · Xcode
  **NeKI brief:** Introduces the SwiftUI color-mixing API available with Xcode 16 for blending a base color with another color on iOS 18 and macOS 15.
- [Using iOS 18’s new TabView with a sidebar – Donny Wals](https://www.donnywals.com/using-ios-18s-new-tabview-with-a-sidebar)
  **Published:** `2024-06-12T14:13:19+00:00`
  **Topics:** Developer Career & Practice
  **NeKI brief:** Explains the iOS 18 TabView sidebar presentation and its navigation behavior. Useful for adapting tab navigation across compact and regular size classes without maintaining separate navigation models.
- [Building a stretchy header view with SwiftUI on iOS 18 – Donny Wals](https://www.donnywals.com/building-a-stretchy-header-view-with-swiftui-on-ios-18)
  **Published:** `2024-06-11T13:13:59+00:00`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** A stretchy SwiftUI header derives geometry from scroll position and clamps offsets, producing a responsive effect while requiring stable coordinate spaces to avoid layout feedback.
- [Modern logging with the OSLog framework in Swift – Donny Wals](https://www.donnywals.com/modern-logging-with-the-oslog-framework-in-swift)
  **Published:** `2024-06-07T07:22:51+00:00`
  **Topics:** Performance · Swift · Xcode
  **NeKI brief:** OSLog categories and privacy annotations make production logs searchable without exposing sensitive values, turning logging into an operational interface rather than debug print output.
- [@preconcurrency usage in swift explained – Donny Wals](https://www.donnywals.com/preconcurrency-usage-in-swift-explained)
  **Published:** `2024-05-28T19:50:01+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** @preconcurrency imports legacy APIs with reduced checking during migration, providing a temporary compatibility bridge that should shrink as dependencies gain concurrency annotations.
- [Programmatic navigation in SwiftUI with NavigationPath and navigationDestination](https://www.donnywals.com/programmatic-navigation-in-swiftui-with-navigationpath-and-navigationdestination)
  **Published:** `2024-05-22T13:14:26+00:00`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Builds programmatic navigation with NavigationPath and navigationDestination, keeping route state explicit and codable. Useful for deep links and multi-step flows that exceed direct NavigationLink composition.
- [Turn off sidebar hiding on NavigationSplitView in SwiftUI](https://www.donnywals.com/turn-off-sidebar-hiding-on-navigationsplitview-in-swiftui)
  **Published:** `2024-05-21T18:04:25+00:00`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** NavigationSplitView's automatic sidebar collapse can be overridden with visibility state, giving apps predictable master-detail access while requiring adaptive behavior for compact widths.
- [How to decide between a Set and Array in Swift? – Donny Wals](https://www.donnywals.com/how-to-decide-between-a-set-and-array-in-swift)
  **Published:** `2024-05-15T07:04:04+00:00`
  **Topics:** Performance · Swift
  **NeKI brief:** Array preserves order and duplicates while Set optimizes membership and uniqueness; choosing between them makes data invariants explicit instead of relying on incidental lookup behavior.
- [Swift’s “if” and “switch” expressions explained – Donny Wals](https://www.donnywals.com/swifts-if-and-switch-expressions-explained)
  **Published:** `2024-05-14T12:56:18+00:00`
  **Topics:** Swift
  **NeKI brief:** Swift expressions let conditional branches produce values directly, reducing temporary mutation while making exhaustive switch coverage a compile-time design constraint.
- [What are enums in Swift? – Donny Wals](https://www.donnywals.com/what-are-enums-in-swift)
  **Published:** `2024-05-08T11:16:18+00:00`
  **Topics:** Swift
  **NeKI brief:** Enums model a closed set of states and associated data, enabling exhaustive switching and safer transitions than string constants with undocumented combinations.
- [How to add a privacy manifest file to your app for required reason API usage?](https://www.donnywals.com/how-to-add-a-privacy-manifest-file-to-your-app-for-required-reason-api-usage)
  **Published:** `2024-05-01T05:35:09+00:00`
  **Topics:** Security & Privacy
  **NeKI brief:** A privacy manifest declares required-reason API use for review tooling, so entries must match actual calls and remain maintained as dependencies change.
- [What is defer in Swift? – Donny Wals](https://www.donnywals.com/what-is-defer-in-swift)
  **Published:** `2024-04-29T07:00:26+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** defer guarantees cleanup at scope exit across early returns and thrown errors, making resource release reliable while potentially obscuring ordering when multiple defers stack.
- [Deciding between a computed property and a function in Swift](https://www.donnywals.com/deciding-between-a-computed-property-and-a-function-in-swift)
  **Published:** `2024-04-26T19:30:32+00:00`
  **Topics:** Swift
  **NeKI brief:** Computed properties model derived state without arguments, while functions signal work or parameters; choosing deliberately keeps call sites honest about cost and side effects.
- [if case let in Swift explained – Donny Wals](https://www.donnywals.com/if-case-let-in-swift-explained)
  **Published:** `2024-04-26T19:00:06+00:00`
  **Topics:** Swift
  **NeKI brief:** if case let combines pattern matching with conditional binding, making enum-associated data checks concise without sacrificing exhaustiveness where a full switch is clearer.
- [How Enterprise level CI/CD with AppCircle helps you scale](https://www.donnywals.com/how-enterprise-level-ci-cd-with-appcircle-helps-you-scale)
  **Published:** `2024-04-25T11:00:17+00:00`
  **Topics:** CI/CD & Automation
  **NeKI brief:** Enterprise CI/CD is framed around repeatable signing, testing, and distribution pipelines, with centralized automation trading setup complexity for consistent release control.
- [What are lazy vars in Swift? – Donny Wals](https://www.donnywals.com/what-are-lazy-vars-in-swift)
  **Published:** `2024-04-23T19:01:51+00:00`
  **Topics:** Swift
  **NeKI brief:** A lazy variable defers initialization until first access, useful for expensive dependencies but requiring awareness that its mutation and thread safety differ from a constant.
- [for vs forEach in Swift: The differences explained – Donny Wals](https://www.donnywals.com/for-vs-foreach-in-swift-the-differences-explained)
  **Published:** `2024-04-23T10:28:23+00:00`
  **Topics:** Swift
  **NeKI brief:** for-in supports control flow such as break and continue, whereas forEach treats iteration as a closure call; the distinction affects readability and early exit behavior.
- [Dispatching to the Main thread with MainActor in Swift – Donny Wals](https://www.donnywals.com/dispatching-to-the-main-thread-with-mainactor-in-swift)
  **Published:** `2024-04-23T08:46:53+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** MainActor isolation expresses UI-thread ownership in the type system, replacing ad hoc dispatch calls while making asynchronous hops and actor boundaries explicit.
- [Enabling upcoming feature flags for Swift using Xcode](https://www.donnywals.com/how-to-use-experimental-swift-versions-and-features-in-xcode)
  **Published:** `2024-04-18T10:46:09+00:00`
  **Topics:** Swift · Xcode
  **NeKI brief:** Xcode can opt a target into experimental Swift features for controlled evaluation, but such flags must stay isolated from production assumptions and CI toolchain guarantees.
- [Actor reentrancy in Swift explained – Donny Wals](https://www.donnywals.com/actor-reentrancy-in-swift-explained)
  **Published:** `2024-04-11T11:37:05+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Actor methods can be re-entered after an await, so invariants spanning suspension points need local snapshots or validation rather than assuming serialized execution throughout.
- [Building a backend-driven paywall with RevenueCat – Donny Wals](https://www.donnywals.com/building-a-backend-driven-paywall-with-revenuecat)
  **Published:** `2024-04-04T17:30:56+00:00`
  **Topics:** App Distribution & Store Operations
  **NeKI brief:** A backend-driven paywall separates entitlement presentation from a fixed client release, but remote configuration needs validation, fallback behavior, and clear experiment ownership.
- [Using closures for dependencies instead of protocols – Donny Wals](https://www.donnywals.com/using-closures-for-dependencies-instead-of-protocols)
  **Published:** `2024-04-02T11:46:02+00:00`
  **Topics:** Dependency Injection · Swift
  **NeKI brief:** Closure-based dependencies expose only the operations a caller needs, reducing protocol scaffolding; the trade-off is weaker discoverability when a dependency grows beyond a few behaviors.
- [Building an AsyncSequence with AsyncStream.makeStream – Donny Wals](https://www.donnywals.com/building-an-asyncsequence-with-asyncstream-makestream)
  **Published:** `2024-03-25T14:39:55+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** AsyncStream.makeStream separates continuation creation from consumer iteration, making callback-to-sequence adapters easier to wire while requiring explicit termination and buffering policies.
- [How to make sure your CI pipelines are always up to date? – Donny Wals](https://www.donnywals.com/how-to-make-sure-your-ci-pipelines-are-always-up-to-date)
  **Published:** `2024-03-12T14:45:16+00:00`
  **Topics:** Testing · Xcode
  **NeKI brief:** Keeping CI current requires treating toolchain and action versions as maintained dependencies, with scheduled review preventing a release-day upgrade surprise.
- [Everything you need to know about Swift 5.10 – Donny Wals](https://www.donnywals.com/everything-you-need-to-know-about-swift-5-10)
  **Published:** `2024-03-07T07:40:56+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Surveys Swift 5.10 language and concurrency changes with practical migration context. Useful as a release overview when maintaining projects across compiler and SDK transitions.
- [Working with dates and Codable in Swift – Donny Wals](https://www.donnywals.com/working-with-dates-and-codable-in-swift)
  **Published:** `2024-02-29T11:14:37+00:00`
  **Topics:** Swift
  **NeKI brief:** Codable date strategies centralize API format rules, avoiding ad hoc formatters while requiring explicit timezone and fractional-second assumptions at the decoding boundary.
- [Designing APIs with typed throws in Swift – Donny Wals](https://www.donnywals.com/designing-apis-with-typed-throws-in-swift)
  **Published:** `2024-02-22T12:13:03+00:00`
  **Topics:** Swift
  **NeKI brief:** Designs APIs with typed throws so callers can reason about failure cases at compile time. Useful for constraining error handling while assessing migration costs in existing untyped throwing code.
- [How to determine where tasks and async functions run in Swift?](https://www.donnywals.com/how-to-determine-where-tasks-and-async-functions-run-in-swift)
  **Published:** `2024-02-16T10:57:21+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Task execution depends on actor isolation and executor inheritance rather than a simple thread rule; tracing those boundaries prevents incorrect assumptions about UI or background work.
- [@Observable in SwiftUI explained – Donny Wals](https://www.donnywals.com/observable-in-swiftui-explained)
  **Published:** `2024-02-06T20:53:04+00:00`
  **Topics:** Macros & Metaprogramming · Observation & State Management · Swift · SwiftUI
  **NeKI brief:** @Observable tracks property reads so SwiftUI can invalidate only dependent views, improving update precision while making ownership and mutation boundaries more important.
- [Writing code that makes mistakes harder – Donny Wals](https://www.donnywals.com/writing-code-that-makes-mistakes-harder)
  **Published:** `2024-01-25T11:07:01+00:00`
  **Topics:** Code Quality · Product Design
  **NeKI brief:** Making invalid states difficult to represent uses types, narrow APIs, and validation to move likely mistakes from runtime behavior into construction-time constraints.
- [Connecting your git repository with a remote server – Donny Wals](https://www.donnywals.com/connecting-your-git-repository-with-a-remote-server)
  **Published:** `2024-01-18T15:52:44+00:00`
  **Topics:** Developer Tools
  **NeKI brief:** Adding a remote links local history to a shared server endpoint, but authentication, branch tracking, and push scope must be verified before collaboration begins.
- [Understanding and resolving merge conflicts – Donny Wals](https://www.donnywals.com/understanding-and-resolving-merge-conflicts)
  **Published:** `2024-01-10T11:03:22+00:00`
  **Topics:** Developer Tools
  **NeKI brief:** Merge conflicts are resolved by reconstructing intended changes around a shared base, then testing the combined behavior instead of mechanically accepting one side.
- [Git basics for iOS developers – Donny Wals](https://www.donnywals.com/git-basics-for-ios-developers)
  **Published:** `2024-01-03T15:45:31+00:00`
  **Topics:** Developer Tools
  **NeKI brief:** Git fundamentals frame commits, branches, and history as recoverable experiments, helping iOS teams isolate feature work before integration and release.
- [Making your SwiftData models Codable – Donny Wals](https://www.donnywals.com/making-your-swiftdata-models-codable)
  **Published:** `2023-08-15T12:56:12+00:00`
  **Topics:** Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** Examines the boundary between SwiftData models and Codable representations, including why persistence annotations do not automatically make a model a good wire format. It is useful when separating API payloads from storage objects.
- [SwiftUI’s Bindable property wrapper explained – Donny Wals](https://www.donnywals.com/swiftuis-bindable-property-wrapper-explained)
  **Published:** `2023-06-30T08:15:47+00:00`
  **Topics:** Swift · SwiftUI · Xcode
  **NeKI brief:** @Bindable creates bindings into an observable model from a view that does not own it, avoiding copied state while making the model's lifetime explicit.
- [What’s the difference between @Binding and @Bindable – Donny Wals](https://www.donnywals.com/whats-the-difference-between-binding-and-bindable)
  **Published:** `2023-06-10T18:18:16+00:00`
  **Topics:** Observation & State Management · Swift · SwiftUI
  **NeKI brief:** @Binding receives an existing binding whereas @Bindable derives bindings from an observable value; confusing them leads to the wrong ownership model.
- [What’s the difference between Macros and property wrappers? – Donny Wals](https://www.donnywals.com/whats-the-difference-between-macros-and-property-wrappers)
  **Published:** `2023-06-06T19:54:04+00:00`
  **Topics:** Macros & Metaprogramming · Swift · Xcode
  **NeKI brief:** Macros generate or transform declarations at compile time, whereas property wrappers mediate storage and access; they solve different extension points despite similar syntax.
- [Tips and tricks for exploring a new codebase – Donny Wals](https://www.donnywals.com/tips-and-tricks-for-exploring-a-new-codebase)
  **Published:** `2023-04-28T10:17:33+00:00`
  **Topics:** Developer Career & Practice
  **NeKI brief:** Offers a structured approach to exploring an unfamiliar codebase, from entry points and dependencies to runtime behavior. Use it to turn onboarding into evidence gathering rather than broad, unprioritized browsing.
- [Understanding unstructured and detached tasks in Swift](https://www.donnywals.com/understanding-unstructured-and-detached-tasks-in-swift)
  **Published:** `2023-04-13T09:01:43+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Unstructured tasks inherit useful context while detached tasks intentionally do not; choosing the latter requires explicit values, priority, and cancellation handling.
- [Structured concurrency in Swift explained – Donny Wals](https://www.donnywals.com/the-basics-of-structured-concurrency-in-swift-explained)
  **Published:** `2023-03-17T10:48:24+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Structured concurrency ties child-task lifetime and cancellation to a lexical scope, preventing orphaned work while requiring result handling before scope exit.
- [Setting up a simple local web socket server – Donny Wals](https://www.donnywals.com/setting-up-a-simple-local-web-socket-server)
  **Published:** `2023-01-24T09:00:58+00:00`
  **Topics:** Testing
  **NeKI brief:** A local WebSocket server provides a controllable peer for app development, separating protocol experiments from production infrastructure while requiring lifecycle cleanup.
- [Iterating over web socket messages with async / await in Swift](https://www.donnywals.com/iterating-over-web-socket-messages-with-async-await-in-swift)
  **Published:** `2023-01-24T09:00:05+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** WebSocket messages can become an async iteration stream, keeping receive loops structured while cancellation and connection errors determine termination behavior.
- [Understanding Swift Concurrency’s AsyncStream and AsyncThrowingStream – Donny Wals](https://www.donnywals.com/understanding-swift-concurrencys-asyncstream)
  **Published:** `2023-01-02T15:41:02+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** AsyncStream and AsyncThrowingStream turn multi-value callbacks into cancellation-aware iteration, with buffering and continuation finishing determining correctness under load.
- [Providing a default value for a SwiftUI Binding – Donny Wals](https://www.donnywals.com/providing-a-default-value-for-a-swiftui-binding)
  **Published:** `2022-11-15T09:02:28+00:00`
  **Topics:** Observation & State Management · Swift · SwiftUI
  **NeKI brief:** A binding default adapts optional model state for controls that require a value, but fallback writes need a clear decision about whether they persist.
- [Enabling Concurrency warnings in Xcode 16 – Donny Wals](https://www.donnywals.com/enabling-concurrency-warnings-in-xcode)
  **Published:** `2022-09-13T12:09:36+00:00`
  **Topics:** Concurrency · Swift · Swift Package Manager · Xcode
  **NeKI brief:** Concurrency warnings can be enabled before adopting Swift 6 mode, creating a staged inventory of isolation work without immediately blocking every build.
- [What are Sendable and @Sendable closures in Swift?](https://www.donnywals.com/what-are-sendable-and-sendable-closures-in-swift)
  **Published:** `2022-09-13T09:08:10+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Explains Sendable values and @Sendable closures. Use it when crossing concurrency boundaries and compiler diagnostics expose unsafe captured mutable state.
- [Xcode 14 “Publishing changes from within view updates is not allowed, this will cause undefined behavior”](https://www.donnywals.com/xcode-14-publishing-changes-from-within-view-updates-is-not-allowed-this-will-cause-undefined-behavior)
  **Published:** `2022-09-07T19:52:15+00:00`
  **Topics:** Swift · SwiftUI · Xcode
  **NeKI brief:** Publishing observable changes during a SwiftUI view update creates a feedback cycle; moving mutation to an event or deferred task restores a valid update boundary.
- [Swift’s associated types for protocols explained – Donny Wals](https://www.donnywals.com/swifts-associated-types-for-protocols-explained)
  **Published:** `2022-06-07T22:08:43+00:00`
  **Topics:** Swift
  **NeKI brief:** Associated types express relationships between protocol inputs and outputs, increasing type safety while making heterogeneous storage and existential use more constrained.
- [Differences between Swift’s any and some keywords explained](https://www.donnywals.com/differences-between-swifts-any-and-some-keywords-explained)
  **Published:** `2022-06-07T22:08:34+00:00`
  **Topics:** Swift · Xcode
  **NeKI brief:** any erases a conforming type behind an existential whereas some preserves one hidden concrete type, so the choice affects storage, specialization, and API guarantees.
- [Presenting a partially visible bottom sheet in SwiftUI on iOS 16](https://www.donnywals.com/presenting-a-partially-visible-bottom-sheet-in-swiftui-on-ios-16)
  **Published:** `2022-06-06T21:32:54+00:00`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Presentation detents model a partially visible sheet as stateful system behavior, avoiding custom drag machinery while requiring iOS 16 availability.
- [Formatting dates in Swift using Date.FormatStyle on iOS 15](https://www.donnywals.com/formatting-dates-in-swift-using-date-formatstyle-on-ios-15)
  **Published:** `2022-05-27T07:00:44+00:00`
  **Topics:** Swift
  **NeKI brief:** Date.FormatStyle provides locale-aware formatting through typed configuration, reducing fragile format strings while requiring availability handling for earlier deployment targets.
- [Closures in Swift explained – Donny Wals](https://www.donnywals.com/closures-in-swift-explained)
  **Published:** `2022-05-23T18:38:41+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Closures capture behavior and surrounding values for deferred execution, so capture lists and ownership choices are central when callbacks outlive their creator.
- [Debugging Network Traffic With Proxyman – Donny Wals](https://www.donnywals.com/debugging-network-traffic-with-proxyman)
  **Published:** `2022-05-12T09:21:21+00:00`
  **Topics:** Networking
  **NeKI brief:** A proxy inspector exposes actual requests, headers, and responses, making network failures observable while requiring careful treatment of credentials and personal data.
- [The difference between checked and unsafe continuations in Swift](https://www.donnywals.com/the-difference-between-checked-and-unsafe-continuation-in-swift)
  **Published:** `2022-04-24T13:47:35+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Checked continuations detect misuse such as double resumption, while unsafe continuations remove that protection for narrow performance cases that need strong external guarantees.
- [Migrating callback based code to Swift Concurrency with continuations](https://www.donnywals.com/migrating-callback-based-code-to-swift-concurrency-with-continuations)
  **Published:** `2022-04-24T13:47:27+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Continuations bridge one-shot callbacks into async functions, but every callback path must resume exactly once to avoid hangs or runtime misuse.
- [Comparing lifecycle management for async sequences and publishers](https://www.donnywals.com/comparing-lifecycle-management-for-async-sequences-and-publishers)
  **Published:** `2022-04-12T10:07:34+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Compares cancellation and ownership for AsyncSequence versus Combine publishers. The discussion clarifies where each abstraction ends work, which is useful when migrating a stream without accidentally retaining tasks or subscriptions.
- [Comparing use cases for async sequences and publishers – Donny Wals](https://www.donnywals.com/comparing-use-cases-for-async-sequences-and-publishers)
  **Published:** `2022-04-12T10:06:45+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** AsyncSequence favors structured pull-based iteration, whereas publishers model subscription and operator pipelines; selecting one should follow cancellation, fan-out, and platform constraints.
- [What is the “any” keyword in Swift? – Donny Wals](https://www.donnywals.com/what-is-the-any-keyword-in-swift)
  **Published:** `2022-03-15T10:45:29+00:00`
  **Topics:** Swift
  **NeKI brief:** Explains Swift's any keyword for existential protocol values. Use it when deciding whether an API needs dynamic protocol storage or should remain generic and statically specialized.
- [Writing custom property wrappers for SwiftUI – Donny Wals](https://www.donnywals.com/writing-custom-property-wrappers-for-swiftui)
  **Published:** `2022-01-16T07:00:47+00:00`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Custom property wrappers can package recurring state access rules, but their projected values and update semantics need to match SwiftUI's ownership model.
- [Adding custom keys to the SwiftUI environment – Donny Wals](https://www.donnywals.com/adding-custom-keys-to-the-swiftui-environment)
  **Published:** `2022-01-10T06:30:47+00:00`
  **Topics:** Dependency Injection · Swift · SwiftUI
  **NeKI brief:** Custom environment keys inject shared view dependencies without parameter threading, but defaults and overrides must make missing configuration observable in tests.
- [Five things iOS developers should focus on in 2022 – Donny Wals](https://www.donnywals.com/five-things-ios-developers-should-focus-on-in-2022)
  **Published:** `2022-01-03T09:54:17+00:00`
  **Topics:** Accessibility · Architecture · Concurrency · Core Data · Persistence & Synchronisation · Swift
  **NeKI brief:** The focus areas connect platform fundamentals with sustainable learning habits, offering a prioritization perspective rather than a substitute for project-specific technical requirements.
- [Forcing an app out of memory on iOS – Donny Wals](https://www.donnywals.com/forcing-an-app-out-of-memory-on-ios)
  **Published:** `2021-12-23T10:44:57+00:00`
  **Topics:** Testing
  **NeKI brief:** Forces low-memory conditions on iOS for testing. Use it when verifying cache eviction, recovery, and state restoration behavior that ordinary simulator runs rarely trigger.
- [Understanding how and when SwiftUI decides to redraw views](https://www.donnywals.com/understanding-how-and-when-swiftui-decides-to-redraw-views)
  **Published:** `2021-11-07T18:08:24+00:00`
  **Topics:** Performance · Swift · SwiftUI
  **NeKI brief:** Explains SwiftUI redraw decisions and dependency reads. Use it when a view updates too often or not at all and state ownership must be traced.
- [Understanding Swift’s AsyncSequence – Donny Wals](https://www.donnywals.com/understanding-swifts-asyncsequence)
  **Published:** `2021-11-01T11:32:49+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** AsyncSequence represents values arriving over time through structured iteration, giving cancellation-aware consumers a common abstraction beyond one-off callbacks.
- [Using async await in Swift to build an image loader – Donny Wals](https://www.donnywals.com/using-swifts-async-await-to-build-an-image-loader)
  **Published:** `2021-09-06T18:52:45+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Builds an image loader with async/await. Use it when download, cache, cancellation, and UI updates need explicit ownership rather than callback-based image loading.
- [What exactly is a Combine AnyCancellable? – Donny Wals](https://www.donnywals.com/what-exactly-is-a-combine-anycancellable)
  **Published:** `2021-08-24T18:27:21+00:00`
  **Topics:** Combine & Reactive Programming
  **NeKI brief:** AnyCancellable cancels a Combine subscription on deinitialization, so retaining it defines subscription lifetime and prevents publishers from stopping immediately.
- [Building a token refresh flow using async await in Swift](https://www.donnywals.com/building-a-token-refresh-flow-with-async-await-and-swift-concurrency)
  **Published:** `2021-08-16T06:45:32+00:00`
  **Topics:** Concurrency · Networking · Swift
  **NeKI brief:** A token-refresh actor can serialize credential renewal so concurrent requests await one refresh, preventing duplicate network work and inconsistent authentication state.
- [Using Swift’s TaskGroup for tasks with varying output](https://www.donnywals.com/using-swift-concurrencys-task-group-for-tasks-with-varying-output)
  **Published:** `2021-08-09T06:00:40+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Task groups require a common child result type; an associated-value enum can represent heterogeneous results while keeping parallel work structured and collectable.
- [How to use async let in Swift? – Donny Wals](https://www.donnywals.com/how-to-use-async-let-in-swift)
  **Published:** `2021-08-09T06:00:15+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** async let launches a scoped child task for independent values, giving concurrent work automatic cancellation and requiring awaits before the enclosing scope exits.
- [Swift Concurrency’s TaskGroup explained – Donny Wals](https://www.donnywals.com/swift-concurrencys-taskgroup-explained)
  **Published:** `2021-08-05T13:48:42+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** TaskGroup dynamically adds structured child tasks and iterates their results, fitting fan-out work where inputs are discovered during execution rather than fixed upfront.
- [Using UISheetPresentationController in SwiftUI 3 – Donny Wals](https://www.donnywals.com/using-uisheetpresentationcontroller-in-swiftui)
  **Published:** `2021-06-30T07:56:54+00:00`
  **Topics:** Swift · SwiftUI · UIKit
  **NeKI brief:** Wrapping UISheetPresentationController lets SwiftUI use UIKit detents before equivalent native APIs, but the bridge must synchronize presentation state and dismissal.
- [Presenting a bottom sheet in UIKit with UISheetPresentationController – Donny Wals](https://www.donnywals.com/presenting-a-bottom-sheet-in-uikit-with-uisheetpresentationcontroller)
  **Published:** `2021-06-30T07:56:52+00:00`
  **Topics:** UIKit
  **NeKI brief:** UISheetPresentationController configures detents and grabber behavior through UIKit presentation APIs, reducing custom gesture code while depending on iOS 15 availability.
- [What are Swift Concurrency’s task local values? – Donny Wals](https://www.donnywals.com/what-are-swift-concurrencys-task-local-values)
  **Published:** `2021-06-22T13:49:51+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Task-local values propagate contextual metadata through child tasks without global mutable state, useful for tracing while requiring a deliberate scope and default.
- [Actors in Swift explained with examples – Donny Wals](https://www.donnywals.com/actors-in-swift-explained-with-examples)
  **Published:** `2021-06-14T19:29:29+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Actors isolate mutable state behind asynchronous access, preventing data races while requiring callers to account for actor hops and reentrancy after awaits.
- [WWDC Notes: Swift concurrency: Behind the scenes – Donny Wals](https://www.donnywals.com/wwdc-notes-swift-concurrency-behind-the-scenes)
  **Published:** `2021-06-10T20:37:36+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** The session notes connect async functions, structured tasks, and actors into one execution model, helping map legacy queue assumptions onto Swift concurrency concepts.
- [WWDC Notes: Bring Core Data concurrency to Swift and SwiftUI – Donny Wals](https://www.donnywals.com/wwdc-notes-bring-core-data-concurrency-to-swift-and-swiftui)
  **Published:** `2021-06-10T19:27:35+00:00`
  **Topics:** Concurrency · Core Data · Persistence & Synchronisation · Swift · SwiftUI
  **NeKI brief:** Core Data concurrency requires contexts to respect their queue or executor boundaries, so SwiftUI integration must transfer object identifiers or values rather than managed objects.
- [WWDC Notes: Discover concurrency in SwiftUI – Donny Wals](https://www.donnywals.com/wwdc-notes-discover-concurrency-in-swiftui)
  **Published:** `2021-06-09T16:56:18+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** SwiftUI asynchronous work should keep slow operations off the main actor and return UI mutations to the correct isolation boundary, avoiding update races.
- [WWDC Notes: Meet AsyncSequence – Donny Wals](https://www.donnywals.com/wwdc-notes-meet-asyncsequence)
  **Published:** `2021-06-09T16:06:04+00:00`
  **Topics:** Concurrency
  **NeKI brief:** AsyncSequence supports familiar transformations while suspending between elements, making time-varying sources composable without manually managing callback chains.
- [WWDC Notes: What’s new in SwiftUI – Donny Wals](https://www.donnywals.com/wwdc-notes-whats-new-in-swiftui)
  **Published:** `2021-06-09T12:18:47+00:00`
  **Topics:** Swift · SwiftUI · UIKit
  **NeKI brief:** The SwiftUI notes emphasize incremental adoption beside UIKit and AppKit, clarifying a migration path that avoids rewriting stable screens wholesale.
- [WWDC Notes: Protect mutable state with Swift actors – Donny Wals](https://www.donnywals.com/wwdc-notes-protect-mutable-state-with-swift-actors)
  **Published:** `2021-06-08T18:08:12+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Actors protect mutable state by serializing access through their executor, but APIs must still define what happens when an awaited method is re-entered.
- [WWDC Notes: Explore structured concurrency in Swift – Donny Wals](https://www.donnywals.com/wwdc-notes-explore-structured-concurrency-in-swift)
  **Published:** `2021-06-08T16:35:58+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Structured concurrency uses lexical scope to make task lifetime and cancellation visible, reducing orphaned work compared with independently launched operations.
- [WWDC Notes: Meet async await in Swift – Donny Wals](https://www.donnywals.com/wwdc-notes-meet-async-await-in-swift)
  **Published:** `2021-06-08T14:37:23+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Async-await SDK APIs replace completion-handler nesting with sequential control flow, while errors and cancellation remain explicit parts of each call boundary.
- [Thoughts on Combine in an async/await world – Donny Wals](https://www.donnywals.com/thoughts-on-combine-in-an-async-await-world)
  **Published:** `2021-06-08T08:01:02+00:00`
  **Topics:** Concurrency
  **NeKI brief:** Combine and async-await solve overlapping asynchronous problems with different composition models; existing stream pipelines may justify Combine even after concurrency adoption.
- [The iOS Developer’s guide to WWDC 2024 – Donny Wals](https://www.donnywals.com/the-ios-developers-guide-to-wwdc-2024)
  **Published:** `2021-05-31T12:53:39+00:00`
  **Topics:** Apple Platform Ecosystem
  **NeKI brief:** Treat WWDC as a triage exercise: filter sessions by active product needs, prioritize documentation and sample code, then schedule deliberate exploration instead of attempting to consume every announcement.
- [What’s the difference between a singleton and a shared instance in Swift? – Donny Wals](https://www.donnywals.com/whats-the-difference-between-a-singleton-and-a-shared-instance-in-swift)
  **Published:** `2021-04-19T07:35:53+00:00`
  **Topics:** Swift
  **NeKI brief:** Distinguishes a true singleton's enforced single instance from a shared instance offered by convention. Use it when choosing global access patterns and testing seams for app-wide services.
- [An extensive guide to sorting Arrays in Swift – Donny Wals](https://www.donnywals.com/an-extensive-guide-to-sorting-arrays-in-swift)
  **Published:** `2021-04-07T10:56:40+00:00`
  **Topics:** Swift
  **NeKI brief:** Swift sorting APIs distinguish in-place mutation from returned copies and accept comparator closures, so stability, cost, and ordering rules should be chosen explicitly.
- [Splitting a JSON object into an enum and an associated object with Codable – Donny Wals](https://www.donnywals.com/splitting-a-json-object-into-an-enum-and-an-associated-object-with-codable)
  **Published:** `2021-04-05T18:33:21+00:00`
  **Topics:** Foundation & Data Formats
  **NeKI brief:** Decoding a discriminator into an enum plus associated payload models variant JSON safely, avoiding optional-field soup while requiring explicit unknown-case policy.
- [JSON parsing in Swift with custom encoding and decoding logic – Donny Wals](https://www.donnywals.com/json-parsing-in-swift-with-custom-encoding-and-decoding-logic)
  **Published:** `2021-04-05T18:33:18+00:00`
  **Topics:** Swift
  **NeKI brief:** Custom Codable logic handles irregular wire formats at a single boundary, keeping domain models coherent while making schema assumptions testable.
- [Customizing how Codable objects map to JSON data – Donny Wals](https://www.donnywals.com/customizing-how-codable-objects-map-to-json-data)
  **Published:** `2021-04-05T18:33:13+00:00`
  **Topics:** Swift
  **NeKI brief:** CodingKeys and custom Codable methods localize JSON naming and shape differences, avoiding server conventions leaking across the app's model layer.
- [JSON parsing in Swift explained using Codable – Donny Wals](https://www.donnywals.com/json-parsing-in-swift-explained-using-codable)
  **Published:** `2021-04-05T18:33:09+00:00`
  **Topics:** Swift
  **NeKI brief:** Codable maps remote JSON into typed models with synthesized behavior where possible, while failures reveal the specific contract mismatch at decoding time.
- [Flattening a nested JSON response into a single struct with Codable – Donny Wals](https://www.donnywals.com/flattening-a-nested-json-response-into-a-single-struct-with-codable)
  **Published:** `2021-04-04T14:43:44+00:00`
  **Topics:** Swift
  **NeKI brief:** A custom decoder can flatten nested transport JSON into one domain struct, simplifying consumers while making the adapter responsible for nesting changes.
- [Preventing unwanted fetches when using NSFetchedResultsController and fetchBatchSize](https://www.donnywals.com/preventing-unwanted-fetches-when-using-nsfetchedresultscontroller-and-fetchbatchsize)
  **Published:** `2021-01-18T08:45:28+00:00`
  **Topics:** Core Data · Persistence & Synchronisation · Swift · SwiftUI · UIKit
  **NeKI brief:** Fetched-results configuration can trigger more Core Data loading than expected; aligning batch size and controller behavior avoids hidden fetch cost during UI updates.
- [What does “atomic” mean in programming? – Donny Wals](https://www.donnywals.com/what-does-atomic-mean-in-programming)
  **Published:** `2021-01-06T08:00:37+00:00`
  **Topics:** Persistence & Synchronisation
  **NeKI brief:** Explains atomic operations as indivisible state changes and why compound read-modify-write code is not automatically atomic. Use it when designing synchronization around shared mutable state.
- [10 things iOS developers should focus on in 2021 – Donny Wals](https://www.donnywals.com/10-things-ios-developers-should-focus-on-in-2021)
  **Published:** `2021-01-04T08:00:12+00:00`
  **Topics:** Concurrency · Core Data · Performance · Persistence & Synchronisation · Swift · Testing
  **NeKI brief:** A 2021 iOS learning snapshot connecting Combine, SwiftUI, testing, and package-management priorities; use it to compare a team's skills against its dated ecosystem baseline rather than current platform guidance.
- [Observing the result of saving a background managed object context with Combine](https://www.donnywals.com/observing-the-result-of-saving-a-background-managed-object-context-with-combine)
  **Published:** `2020-12-07T07:30:42+00:00`
  **Topics:** Core Data · Persistence & Synchronisation
  **NeKI brief:** A background-context save can publish completion through Combine, letting UI consumers react without crossing managed objects between context confinement boundaries.
- [Responding to changes in a managed object context – Donny Wals](https://www.donnywals.com/responding-to-changes-in-a-managed-object-context)
  **Published:** `2020-11-23T08:00:41+00:00`
  **Topics:** Core Data · Persistence & Synchronisation
  **NeKI brief:** Context change notifications provide a synchronization signal across Core Data work, but consumers must merge or refetch on their own correct context.
- [Building a concurrency-proof token refresh flow in Combine – Donny Wals](https://www.donnywals.com/building-a-concurrency-proof-token-refresh-flow-in-combine)
  **Published:** `2020-11-09T08:30:48+00:00`
  **Topics:** Concurrency · Networking
  **NeKI brief:** Builds a Combine token-refresh flow that prevents overlapping refresh requests. Use it when concurrent API failures must share one authentication renewal and retry safely.
- [Building a simple remote configuration loader for your apps – Donny Wals](https://www.donnywals.com/building-a-simple-remote-configuration-for-your-apps)
  **Published:** `2020-10-26T21:01:31+00:00`
  **Topics:** Networking
  **NeKI brief:** Remote configuration separates app behavior from a binary release, but fetched values need defaults, validation, caching, and an owner for rollout safety.
- [Formatting dates in the user’s locale using DateFormatter in Swift – Donny Wals](https://www.donnywals.com/formatting-dates-in-the-users-locale-using-dateformatter-in-swift)
  **Published:** `2020-10-15T10:10:54+00:00`
  **Topics:** Swift
  **NeKI brief:** DateFormatter configured with a user's locale produces culturally appropriate display text, while parsing machine formats should remain separate and locale-independent.
- [Observing changes to managed objects across contexts with Combine – Donny Wals](https://www.donnywals.com/observing-changes-to-managed-objects-across-contexts-with-combine)
  **Published:** `2020-10-12T14:01:32+00:00`
  **Topics:** Core Data · Persistence & Synchronisation
  **NeKI brief:** Combine can observe Core Data context changes and feed UI updates, but object identity and context confinement still govern what may cross threads.
- [Understanding the differences between your Core Data model and managed objects](https://www.donnywals.com/understanding-the-differences-between-your-core-data-model-and-managed-objects)
  **Published:** `2020-10-05T09:39:16+00:00`
  **Topics:** Core Data · Persistence & Synchronisation · Xcode
  **NeKI brief:** A Core Data model describes persistent schema while managed objects are context-bound runtime instances; separating them prevents mistaken assumptions about thread safety and lifecycle.
- [Understanding how DispatchQueue.sync can cause deadlocks](https://www.donnywals.com/understanding-how-dispatchqueue-sync-can-cause-deadlocks)
  **Published:** `2020-09-21T20:25:09+00:00`
  **Topics:** Swift
  **NeKI brief:** Shows how synchronous dispatch can deadlock when a queue waits on itself or on a cycle of dependent queues. Follow it as a diagnostic aid when legacy GCD code hangs under load or during callback re-entry.
- [Configuring error types when using flatMap in Combine – Donny Wals](https://www.donnywals.com/configuring-error-types-when-using-flatmap-in-combine)
  **Published:** `2020-09-14T07:00:07+00:00`
  **Topics:** Combine & Reactive Programming
  **NeKI brief:** Combine flatMap must reconcile upstream and inner publisher failure types, so mapping errors deliberately preserves a coherent pipeline contract.
- [Dispatching async or sync? The differences explained](https://www.donnywals.com/dispatching-async-or-sync-the-differences-explained)
  **Published:** `2020-08-31T07:00:28+00:00`
  **Topics:** Concurrency
  **NeKI brief:** Contrasts synchronous and asynchronous dispatch queues. Use it when reasoning about ordering, deadlocks, and whether a caller waits for a block to complete.
- [Implementing a one-way sync strategy with Core Data, URLSession and Combine](https://www.donnywals.com/implementing-a-one-way-sync-strategy-with-core-data-urlsession-and-combine)
  **Published:** `2020-08-24T10:40:45+00:00`
  **Topics:** Core Data · Networking · Persistence & Synchronisation
  **NeKI brief:** A one-way sync pipeline fetches remote data, maps it, and persists it into Core Data, requiring conflict and offline-refresh policy at the boundary.
- [Understanding Swift’s OptionSet – Donny Wals](https://www.donnywals.com/understanding-swifts-optionset)
  **Published:** `2020-08-18T10:19:00+00:00`
  **Topics:** Swift
  **NeKI brief:** OptionSet models combinations of flags with set algebra, avoiding invalid string or integer values while retaining efficient bitwise interoperability.
- [Fetching objects from Core Data in a SwiftUI project – Donny Wals](https://www.donnywals.com/fetching-objects-from-core-data-in-a-swiftui-project)
  **Published:** `2020-08-10T09:48:04+00:00`
  **Topics:** Core Data · Persistence & Synchronisation · Swift · SwiftUI
  **NeKI brief:** Fetches Core Data objects into a SwiftUI view with an observation-aware wrapper. Use it when persistence updates should drive UI changes without manual reload logic.
- [Using Codable with Core Data and NSManagedObject – Donny Wals](https://www.donnywals.com/using-codable-with-core-data-and-nsmanagedobject)
  **Published:** `2020-08-03T08:54:44+00:00`
  **Topics:** Core Data · Persistence & Synchronisation · Swift
  **NeKI brief:** Making managed objects Codable crosses persistence and transport concerns, so context ownership, relationships, and decoding side effects need explicit containment.
- [Setting up a Core Data store for unit tests – Donny Wals](https://www.donnywals.com/setting-up-a-core-data-store-for-unit-tests)
  **Published:** `2020-07-27T07:00:53+00:00`
  **Topics:** Core Data · Persistence & Synchronisation · Testing
  **NeKI brief:** Sets up an isolated Core Data store for unit tests. Use it when persistence tests need deterministic data and migrations without touching an application's real database.
- [Using Core Data with SwiftUI 2.0 and Xcode 12 – Donny Wals](https://www.donnywals.com/using-core-data-with-swiftui-2-0-and-xcode-12)
  **Published:** `2020-07-20T07:00:48+00:00`
  **Topics:** Core Data · Persistence & Synchronisation · Swift · SwiftUI · Xcode
  **NeKI brief:** SwiftUI app lifecycle setup can inject a persistent Core Data container through the environment, keeping view fetches context-bound and previewable.
- [Understanding the importance of abstractions – Donny Wals](https://www.donnywals.com/understanding-the-importance-of-abstractions)
  **Published:** `2020-07-13T07:00:05+00:00`
  **Topics:** Networking
  **NeKI brief:** Abstractions hide volatile implementation details behind stable intent, but an unnecessary layer can make behavior harder to trace than the dependency it replaces.
- [Handling deeplinks in a SwiftUI app – Donny Wals](https://www.donnywals.com/handling-deeplinks-in-a-swiftui-app)
  **Published:** `2020-07-06T07:00:49+00:00`
  **Topics:** Navigation & Deep Linking · Swift · SwiftUI
  **NeKI brief:** onOpenURL routes incoming links into SwiftUI state, separating URL parsing from navigation decisions and allowing unsupported routes to fail safely.
- [Implementing an infinite scrolling list with SwiftUI and Combine](https://www.donnywals.com/implementing-an-infinite-scrolling-list-with-swiftui-and-combine)
  **Published:** `2020-06-29T07:00:21+00:00`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Infinite scrolling triggers pagination near a list boundary, but backpressure and duplicate-request guards are needed when appearance callbacks repeat.
- [Using multi-colored icons in iOS 14 with SF Symbols 2 – Donny Wals](https://www.donnywals.com/using-multi-colored-icons-in-ios14-with-sf-symbols-2)
  **Published:** `2020-06-28T10:43:20+00:00`
  **Topics:** Product Design · UIKit
  **NeKI brief:** SF Symbols rendering modes support hierarchical, palette, and multicolor icon treatments, allowing semantic system artwork to match UI emphasis without separate assets.
- [How to change a UICollectionViewListCell’s separator inset – Donny Wals](https://www.donnywals.com/how-to-change-a-uicollectionviewlistcells-separator-inset)
  **Published:** `2020-06-25T17:08:10+00:00`
  **Topics:** Apple Platform Ecosystem · Foundation & Data Formats · UIKit
  **NeKI brief:** List-cell separator insets are configured through the collection-list appearance APIs, keeping alignment consistent with custom content margins and layout direction.
- [What’s new with UICollectionView in iOS 14 – Donny Wals](https://www.donnywals.com/whats-new-with-uicollectionview-in-ios-14)
  **Published:** `2020-06-25T16:58:27+00:00`
  **Topics:** UIKit
  **NeKI brief:** iOS 14 collection-view APIs combine list configuration, registrations, and accessories, reducing boilerplate while making availability part of adoption planning.
- [How to add a custom accessory to a UICollectionViewListCell?](https://www.donnywals.com/how-to-add-a-custom-accessory-to-a-uicollectionviewlistcell)
  **Published:** `2020-06-24T14:08:06+00:00`
  **Topics:** UIKit
  **NeKI brief:** Custom list-cell accessories attach interactive or informational views through UICollectionView list configuration, separating row content from standardized chrome.
- [How to add accessories to a UICollectionViewListCell? – Donny Wals](https://www.donnywals.com/how-to-add-accessories-to-a-uicollectionviewlistcell)
  **Published:** `2020-06-24T13:32:46+00:00`
  **Topics:** UIKit
  **NeKI brief:** Built-in list-cell accessories provide disclosure, checkmark, and control affordances without custom subview layout, improving consistency with platform conventions.
- [How to add custom swipe actions to a UICollectionViewListCell?](https://www.donnywals.com/how-to-add-custom-swipe-actions-to-a-uicollectionviewlistcell)
  **Published:** `2020-06-24T13:05:39+00:00`
  **Topics:** UIKit
  **NeKI brief:** UICollectionView list swipe actions express contextual row commands using leading or trailing configurations, while destructive semantics should match confirmation and undo policy.
- [Configure collection view cells with UICollectionView.CellRegistration – Donny Wals](https://www.donnywals.com/configure-collection-view-cells-with-uicollectionview-cellregistration)
  **Published:** `2020-06-23T22:06:00+00:00`
  **Topics:** UIKit
  **NeKI brief:** CellRegistration binds dequeue configuration to a typed closure, preventing reuse-identifier drift while concentrating model-to-cell updates in one place.
- [@StateObject vs @ObservedObject: understanding the difference – Donny Wals](https://www.donnywals.com/stateobject-vs-observedobject-understanding-the-difference)
  **Published:** `2020-06-23T15:27:14+00:00`
  **Topics:** Observation & State Management
  **NeKI brief:** @StateObject creates and retains an observable model for a view's lifetime, whereas @ObservedObject observes externally owned state and must not recreate it.
- [Using custom publishers to drive SwiftUI views – Donny Wals](https://www.donnywals.com/using-custom-publishers-to-drive-swiftui-views)
  **Published:** `2020-06-23T00:16:02+00:00`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** A custom publisher can expose domain events to a SwiftUI view model, but subscription lifetime and main-thread delivery must be explicit.
- [Ignore first number of elements from a publisher in Combine – Donny Wals](https://www.donnywals.com/ignore-first-number-of-elements-from-a-publisher-in-combine)
  **Published:** `2020-06-19T09:44:19+00:00`
  **Topics:** Combine & Reactive Programming
  **NeKI brief:** Combine drop operators suppress initial publisher emissions, useful when defaults should not trigger work while preserving later state transitions.
- [Recursively execute a paginated network call with Combine – Donny Wals](https://www.donnywals.com/recursively-execute-a-paginated-network-call-with-combine)
  **Published:** `2020-06-15T07:15:40+00:00`
  **Topics:** Combine & Reactive Programming · Networking
  **NeKI brief:** Recursive pagination chains each response into the next request until exhaustion, requiring cancellation, error propagation, and termination conditions to remain centralized.
- [What’s the difference between Float and Double in Swift – Donny Wals](https://www.donnywals.com/whats-the-difference-between-float-and-double-in-swift)
  **Published:** `2020-06-10T11:37:02+00:00`
  **Topics:** Swift
  **NeKI brief:** Float and Double trade precision against storage and performance; calculations and external formats should choose deliberately rather than relying on inferred literals.
- [Understanding property wrappers in Swift with examples – Donny Wals](https://www.donnywals.com/understanding-property-wrappers-in-swift-with-examples)
  **Published:** `2020-06-08T07:45:58+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Property wrappers separate storage policy from property syntax, but initialization, projection, and enclosing-instance behavior must be understood before using them as generic magic.
- [What’s the difference between catch and replaceError in Combine? – Donny Wals](https://www.donnywals.com/whats-the-difference-between-catch-and-replaceerror-in-combine)
  **Published:** `2020-05-29T08:53:29+00:00`
  **Topics:** Combine & Reactive Programming
  **NeKI brief:** catch switches to a replacement publisher after failure, while replaceError emits a final fallback value; the choice determines whether a pipeline continues or completes.
- [Retrying a network request with a delay in Combine – Donny Wals](https://www.donnywals.com/retrying-a-network-request-with-a-delay-in-combine)
  **Published:** `2020-05-25T07:00:01+00:00`
  **Topics:** Combine & Reactive Programming · Networking
  **NeKI brief:** Delayed retries combine failure handling with scheduling, reducing immediate repeat traffic while requiring a bounded policy for persistent server errors.
- [Reclaim disk space by deleting old iOS simulators and Device Support files – Donny Wals](https://www.donnywals.com/delete-old-simulators-and-device-support-files-to-free-disk-space)
  **Published:** `2020-05-24T12:29:14+00:00`
  **Topics:** Xcode
  **NeKI brief:** Removing obsolete simulator runtimes and device-support data recovers development storage, but the cleanup should preserve SDK versions still required for supported testing.
- [Throttle network speeds for a specific host in Charles – Donny Wals](https://www.donnywals.com/throttle-network-speeds-for-a-specific-host-in-charles)
  **Published:** `2020-05-21T10:32:26+00:00`
  **Topics:** Networking · Testing
  **NeKI brief:** Host-specific network throttling simulates constrained backend conditions without slowing unrelated traffic, making latency and failure behavior testable during development.
- [How to have more than one type of cell in a Collection View – Donny Wals](https://www.donnywals.com/how-to-have-more-than-one-type-of-cell-in-a-collection-view)
  **Published:** `2020-05-19T07:42:32+00:00`
  **Topics:** UIKit
  **NeKI brief:** Multiple collection-view cell types are selected from model identity during configuration, keeping heterogeneous layouts explicit while reuse registration remains type-safe.
- [What is type erasure in Swift? An explanation with code samples](https://www.donnywals.com/understanding-type-erasure-in-swift)
  **Published:** `2020-05-18T07:29:52+00:00`
  **Topics:** Swift
  **NeKI brief:** Type erasure hides a concrete generic or associated type behind a stable interface, enabling heterogeneous storage while sacrificing some static information and specialization.
- [Getting started with testing your Combine code – Donny Wals](https://www.donnywals.com/getting-started-with-testing-your-combine-code)
  **Published:** `2020-05-11T08:00:35+00:00`
  **Topics:** Testing
  **NeKI brief:** Combine tests control publishers and schedulers so asynchronous emissions become deterministic, allowing assertions on values, completion, and cancellation without live timing.
- [Creating type-safe identifiers for your Codable models – Donny Wals](https://www.donnywals.com/creating-type-safe-identifiers-for-your-codable-models)
  **Published:** `2020-05-04T07:00:16+00:00`
  **Topics:** Swift
  **NeKI brief:** A dedicated identifier type prevents mixing unrelated IDs and can still Codable-map to the wire format, moving identity mistakes from runtime into type checking.
- [Why your @Atomic property wrapper doesn’t work for collection types](https://www.donnywals.com/why-your-atomic-property-wrapper-doesnt-work-for-collection-types)
  **Published:** `2020-04-20T07:00:43+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Explains why an atomic property wrapper fails to provide safe collection mutation when read-modify-write operations interleave. Follow it when designing synchronization around value types and distinguishing accessor locking from compound-operation atomicity.
- [Changing a publisher’s Failure type in Combine – Donny Wals](https://www.donnywals.com/changing-a-publishers-failure-type-in-combine)
  **Published:** `2020-04-15T08:28:15+00:00`
  **Topics:** Combine & Reactive Programming
  **NeKI brief:** Combine failure-type transformations adapt error contracts between publishers, allowing composition while preserving a deliberate distinction between impossible and recoverable failure.
- [An introduction to Big O in Swift – Donny Wals](https://www.donnywals.com/an-introduction-to-big-o-in-swift)
  **Published:** `2020-04-13T12:11:42+00:00`
  **Topics:** Swift
  **NeKI brief:** Big O describes how time or memory grows with input size, helping Swift developers choose data structures before micro-optimizing an already acceptable operation.
- [Using Closures to initialize properties in Swift – Donny Wals](https://www.donnywals.com/using-closures-to-initialize-properties-in-swift)
  **Published:** `2020-04-08T07:50:59+00:00`
  **Topics:** Swift
  **NeKI brief:** An immediately invoked closure can compute a property's initial value with local setup logic, keeping initialization encapsulated while avoiding later mutable configuration.
- [How to use SF Symbols in your apps – Donny Wals](https://www.donnywals.com/how-to-use-sf-symbols-in-your-apps)
  **Published:** `2020-04-06T07:20:17+00:00`
  **Topics:** UIKit
  **NeKI brief:** SF Symbols provide configurable system artwork that follows text weight and scale, reducing custom icon assets while requiring availability-aware symbol selection.
- [Find and copy Xcode device support files – Donny Wals](https://www.donnywals.com/find-and-copy-xcode-device-support-files)
  **Published:** `2020-04-01T07:30:37+00:00`
  **Topics:** Testing · Xcode
  **NeKI brief:** Device-support files let older Xcode installations communicate with newer iOS versions, but copied support data must match the debugging toolchain's expectations.
- [Enforcing code consistency with SwiftLint – Donny Wals](https://www.donnywals.com/enforcing-code-consistency-with-swiftlint)
  **Published:** `2020-03-30T07:43:34+00:00`
  **Topics:** Swift
  **NeKI brief:** SwiftLint makes style and selected correctness rules repeatable in local and CI builds, but teams need agreed rule severity to avoid alert fatigue.
- [Calculating the difference in hours between two dates in Swift](https://www.donnywals.com/calculating-the-difference-in-hours-between-two-dates-in-swift)
  **Published:** `2020-03-25T08:09:47+00:00`
  **Topics:** Swift
  **NeKI brief:** Calendar date components calculate elapsed calendar units with locale and timezone semantics, avoiding incorrect fixed-second arithmetic across daylight-saving changes.
- [Adding your app’s content to Spotlight – Donny Wals](https://www.donnywals.com/adding-your-apps-content-to-spotlight)
  **Published:** `2020-03-23T10:05:21+00:00`
  **Topics:** App Intents & System Surfaces
  **NeKI brief:** Core Spotlight and user activities expose app content to system search, requiring stable identifiers and deep-link restoration when a user opens a result.
- [Removing duplicate values from an array in Swift – Donny Wals](https://www.donnywals.com/removing-duplicate-values-from-an-array-in-swift)
  **Published:** `2020-03-18T09:44:43+00:00`
  **Topics:** Swift
  **NeKI brief:** Duplicate removal can preserve order through filtering or prioritize membership speed through Set conversion; the required ordering invariant determines the safer approach.
- [Profiling and debugging your Combine code with Timelane](https://www.donnywals.com/profiling-and-debugging-your-combine-code-with-timelane)
  **Published:** `2020-03-16T08:00:41+00:00`
  **Topics:** Concurrency · Performance · Swift
  **NeKI brief:** Shows using Timeline to record and inspect Combine event streams, making ordering and subscription behavior visible. Follow it when a reactive pipeline produces unexpected timing, duplicate values, or missing completions.
- [What is @escaping in Swift? – Donny Wals](https://www.donnywals.com/what-is-escaping-in-swift)
  **Published:** `2020-03-11T10:36:03+00:00`
  **Topics:** Swift
  **NeKI brief:** An escaping closure may outlive its call site, so captured state and ownership must remain valid after the function returns.
- [What are computed properties in Swift and when should you use them?](https://www.donnywals.com/what-are-computed-properties-in-swift-and-when-should-you-use-them)
  **Published:** `2020-03-09T08:00:51+00:00`
  **Topics:** Swift
  **NeKI brief:** Computed properties derive a value on demand from other state, but expensive or effectful work belongs in a method so callers can recognize its cost.
- [Reading and writing Property List files with Codable in Swift – Donny Wals](https://www.donnywals.com/reading-and-writing-property-list-files-in-swift)
  **Published:** `2020-03-04T08:15:52+00:00`
  **Topics:** Swift
  **NeKI brief:** Property-list serialization reads and writes Foundation-compatible values, fitting configuration-style data while lacking Codable's richer domain-model guarantees and explicit schema evolution tools.
- [Using Result in Swift 5 – Donny Wals](https://www.donnywals.com/using-result-in-swift-5)
  **Published:** `2020-03-02T08:00:33+00:00`
  **Topics:** Swift
  **NeKI brief:** Result represents success or typed failure as a value, allowing asynchronous boundaries to communicate outcomes without separate optional result and error channels.
- [Using KeyPaths as functions in Swift – Donny Wals](https://www.donnywals.com/using-keypaths-as-functions-in-swift-5-2)
  **Published:** `2020-02-26T08:00:14+00:00`
  **Topics:** Swift
  **NeKI brief:** Key paths can serve as concise transforms in higher-order functions, preserving property access semantics while avoiding closures that merely select one member.
- [Error handling in Swift with do catch – Donny Wals](https://www.donnywals.com/error-handling-in-swift-with-do-catch)
  **Published:** `2020-02-24T08:00:51+00:00`
  **Topics:** Swift
  **NeKI brief:** do-catch handles thrown errors at a chosen boundary, enabling typed recovery paths while keeping failures from being silently converted into absent values.
- [Adding default values to subscript arguments in Swift 5.2 – Donny Wals](https://www.donnywals.com/adding-default-values-to-subscripts-in-swift-5-2)
  **Published:** `2020-02-19T08:00:51+00:00`
  **Topics:** Swift
  **NeKI brief:** Custom subscripts can provide default access behavior for keyed collections, but mutation and missing-key semantics must stay obvious to callers.
- [How and when to use callAsFunction in Swift 5.2 – Donny Wals](https://www.donnywals.com/how-and-when-to-use-callasfunction-in-swift-5-2)
  **Published:** `2020-02-17T08:01:24+00:00`
  **Topics:** Swift
  **NeKI brief:** callAsFunction gives a type function-call syntax for a focused action, but its use should preserve readability rather than obscure ordinary method behavior.
- [Testing push notifications in the Simulator with Xcode 11.4 – Donny Wals](https://www.donnywals.com/testing-push-notifications-in-the-simulator-with-xcode-11-4)
  **Published:** `2020-02-12T08:00:46+00:00`
  **Topics:** Testing · Xcode
  **NeKI brief:** Simulator push-notification testing shortens iteration by injecting payloads locally, while production delivery, entitlement, and token behavior still need device coverage.
- [Using Promises and Futures in Combine – Donny Wals](https://www.donnywals.com/using-promises-and-futures-in-combine)
  **Published:** `2020-02-10T08:30:35+00:00`
  **Topics:** Concurrency
  **NeKI brief:** A Future adapts one asynchronous result into a Combine publisher, but its eager execution and single-output semantics differ from deferred or streaming publishers.
- [Using map, flatMap and compactMap in Combine – Donny Wals](https://www.donnywals.com/using-map-flatmap-and-compactmap-in-combine)
  **Published:** `2020-02-03T08:00:28+00:00`
  **Topics:** Combine & Reactive Programming
  **NeKI brief:** Combine transformations either map values, flatten nested publishers, or remove absent values; selecting the right operator preserves the intended stream shape.
- [Updating UI with assign(to:on:) in Combine – Donny Wals](https://www.donnywals.com/updating-ui-with-assigntoon-in-combine)
  **Published:** `2020-01-29T08:00:31+00:00`
  **Topics:** Combine & Reactive Programming
  **NeKI brief:** assign(to:on:) connects publisher output to an object's property, but retention and main-thread delivery must be explicit when updating UIKit state.
- [Publishing property changes in Combine – Donny Wals](https://www.donnywals.com/publishing-property-changes-in-combine)
  **Published:** `2020-01-27T08:00:23+00:00`
  **Topics:** Combine & Reactive Programming
  **NeKI brief:** Subjects and property publishers expose state changes as streams, allowing composition while requiring clear ownership of who may mutate the source.
- [Debugging network traffic with Charles – Donny Wals](https://www.donnywals.com/debugging-network-traffic-with-charles)
  **Published:** `2020-01-22T08:00:03+00:00`
  **Topics:** Networking
  **NeKI brief:** Charles exposes live HTTP requests and responses from simulator or device traffic, making transport failures inspectable while demanding careful credential handling.
- [How to sort an Array based on a property of an element in Swift?](https://www.donnywals.com/how-to-sort-an-array-based-on-a-property-of-an-element-in-swift)
  **Published:** `2020-01-20T10:52:16+00:00`
  **Topics:** Swift
  **NeKI brief:** Sorting by a property uses a comparator that defines ordering and ties, so callers should decide mutation versus returned copy and stable presentation needs.
- [Refactoring a networking layer to use Combine – Donny Wals](https://www.donnywals.com/refactoring-a-networking-layer-to-use-combine)
  **Published:** `2020-01-20T08:00:13+00:00`
  **Topics:** Concurrency · Networking
  **NeKI brief:** A Combine networking layer expresses requests, decoding, errors, and cancellation as one pipeline, but scheduler and lifetime choices become part of the API contract.
- [How to add an element to the start of an Array in Swift?](https://www.donnywals.com/how-to-add-an-element-to-the-start-of-an-array-in-swift)
  **Published:** `2020-01-19T11:02:16+00:00`
  **Topics:** Swift
  **NeKI brief:** Array insertion at index zero shifts existing elements, so it is clear for small collections but a queue-like workload may need a different structure.
- [How to check if two date ranges overlap in Swift – Donny Wals](https://www.donnywals.com/how-to-check-if-two-date-ranges-overlap-in-swift)
  **Published:** `2020-01-17T09:00:09+00:00`
  **Topics:** Swift
  **NeKI brief:** Date ranges overlap when each starts before the other ends, but inclusive bounds and timezone interpretation must match the product's scheduling rules.
- [Understanding Combine’s publishers and subscribers – Donny Wals](https://www.donnywals.com/understanding-combines-publishers-and-subscribers)
  **Published:** `2020-01-13T07:30:56+00:00`
  **Topics:** Combine & Reactive Programming
  **NeKI brief:** Publishers describe values and completion while subscribers receive demand-aware events, establishing the ownership and backpressure vocabulary behind Combine pipelines.
- [Removing a specific object from an Array in Swift – Donny Wals](https://www.donnywals.com/remove-instances-of-an-object-from-an-array-in-swift)
  **Published:** `2020-01-10T10:26:09+00:00`
  **Topics:** Performance · Swift
  **NeKI brief:** Removing array elements can target first occurrence, all matches, or a predicate; choosing explicitly preserves intended ordering and mutation semantics.
- [How to filter an Array in Swift? – Donny Wals](https://www.donnywals.com/how-to-filter-an-array-in-swift)
  **Published:** `2020-01-09T10:44:24+00:00`
  **Topics:** Swift
  **NeKI brief:** filter returns a new array containing elements that satisfy a predicate, keeping selection logic declarative while allocating a separate result collection.
- [Five tips to write better todos in Xcode – Donny Wals](https://www.donnywals.com/five-tips-to-write-better-todos-in-xcode)
  **Published:** `2020-01-08T08:30:08+00:00`
  **Topics:** Swift · Xcode
  **NeKI brief:** Shares a workflow for organizing TODO comments in Xcode so unfinished work remains visible and actionable. Use it when shaping lightweight code-review and maintenance conventions.
- [Getting started with Combine – Donny Wals](https://www.donnywals.com/an-introduction-to-combine)
  **Published:** `2020-01-06T08:10:33+00:00`
  **Topics:** Apple Platform Ecosystem · Combine & Reactive Programming
  **NeKI brief:** Combine models asynchronous values as composable publisher chains, but subscriptions, cancellation, schedulers, and failure types remain essential design choices.
- [Swift’s typealias explained with five examples – Donny Wals](https://www.donnywals.com/swifts-typealias-explained-with-five-examples)
  **Published:** `2020-01-02T09:00:55+00:00`
  **Topics:** Swift
  **NeKI brief:** typealias gives an existing type a domain-relevant name, improving API readability without creating a new type or adding identity safety.
- [Reversing an Array in Swift – Donny Wals](https://www.donnywals.com/reversing-an-array-in-swift)
  **Published:** `2020-01-01T13:03:29+00:00`
  **Topics:** Swift
  **NeKI brief:** reversed() presents elements in reverse order as a view or sequence, while a mutable in-place reversal has different ownership and performance implications.
- [Getting ready to publish your app on the App Store – Donny Wals](https://www.donnywals.com/getting-ready-to-publish-your-app-on-the-app-store)
  **Published:** `2019-12-24T08:00:25+00:00`
  **Topics:** Testing · Xcode
  **NeKI brief:** App Store publication requires coordinated signing, metadata, screenshots, review requirements, and release controls, turning shipping into an operational checklist.
- [Dependency injection with Storyboards and Xcode 11 – Donny Wals](https://www.donnywals.com/dependency-injection-with-storyboards-and-xcode-11)
  **Published:** `2019-12-23T08:00:51+00:00`
  **Topics:** Architecture · Dependency Injection · Xcode
  **NeKI brief:** Storyboard dependency injection uses scene creation and preparation hooks to supply collaborators, avoiding hidden service lookups in view-controller lifecycle code.
- [Using compositional collection view layouts in iOS 13 – Donny Wals](https://www.donnywals.com/using-compositional-collection-view-layouts-in-ios-13)
  **Published:** `2019-12-22T08:00:14+00:00`
  **Topics:** UIKit
  **NeKI brief:** Compositional layout expresses collection sections from nested groups and items, enabling complex adaptive layouts without subclassing a custom layout engine.
- [Modern table views with diffable data sources – Donny Wals](https://www.donnywals.com/modern-table-views-with-diffable-data-sources)
  **Published:** `2019-12-21T08:00:29+00:00`
  **Topics:** Apple Platform Ecosystem · UIKit
  **NeKI brief:** Introduces diffable data sources as a snapshot-driven replacement for manually coordinated table updates. The article connects stable identifiers and snapshot application to fewer invalid-update crashes in UIKit list screens.
- [Fetching and displaying data from the network – Donny Wals](https://www.donnywals.com/fetching-and-displaying-data-from-the-network)
  **Published:** `2019-12-20T08:00:52+00:00`
  **Topics:** Concurrency · Networking
  **NeKI brief:** Fetching remote data for UI requires separating transport, decoding, loading state, and presentation so failures and retries do not become view-controller side effects.
- [Architecting a robust networking layer with protocols – Donny Wals](https://www.donnywals.com/architecting-a-robust-networking-layer-with-protocols)
  **Published:** `2019-12-19T08:00:01+00:00`
  **Topics:** Networking
  **NeKI brief:** Protocol-based networking boundaries let endpoints and transports be replaced in tests, while error mapping and request ownership remain explicit application policy.
- [Installing multiple Xcode versions with xcversion – Donny Wals](https://www.donnywals.com/installing-multiple-xcode-versions-with-xcversion)
  **Published:** `2019-12-18T08:45:22+00:00`
  **Topics:** Xcode
  **NeKI brief:** Managing multiple Xcode versions supports project-specific SDK and compiler needs, but command-line selection and simulator compatibility must be verified per workspace.
- [Loose coupling and the law of Demeter – Donny Wals](https://www.donnywals.com/loose-coupling-and-the-law-of-demeter)
  **Published:** `2019-12-17T08:30:33+00:00`
  **Topics:** Code Quality
  **NeKI brief:** Loose coupling limits each component's knowledge of collaborators, reducing change propagation while avoiding abstraction layers that hide simple dependencies.
- [Sequencing tasks with DispatchGroup – Donny Wals](https://www.donnywals.com/sequencing-tasks-with-dispatchgroup)
  **Published:** `2019-12-16T08:00:20+00:00`
  **Topics:** Concurrency
  **NeKI brief:** DispatchGroup coordinates completion of several asynchronous tasks before a dependent step, but it does not itself provide cancellation, error aggregation, or ordering.
- [Breaking an app up into modules – Donny Wals](https://www.donnywals.com/breaking-an-app-up-into-modules)
  **Published:** `2019-12-15T08:00:44+00:00`
  **Topics:** Architecture · Xcode
  **NeKI brief:** Modules isolate feature and infrastructure dependencies behind explicit package boundaries, improving build and ownership clarity while adding integration and tooling cost.
- [Using preconditions, assertions, and fatal errors in Swift – Donny Wals](https://www.donnywals.com/using-preconditions-assertions-and-fatal-errors-in-swift)
  **Published:** `2019-12-14T08:00:32+00:00`
  **Topics:** Swift
  **NeKI brief:** Assertions, preconditions, and fatal errors encode different failure contracts, so selecting one should reflect debug-only checks, release invariants, or unrecoverable states.
- [Testing your push notifications without a third party service – Donny Wals](https://www.donnywals.com/testing-your-push-notifications-without-a-third-party-service)
  **Published:** `2019-12-13T08:00:06+00:00`
  **Topics:** Testing
  **NeKI brief:** Local tooling can inject push payloads without an external provider, speeding UI and routing tests while leaving real APNs delivery to integration coverage.
- [Scheduling daily notifications on iOS using Calendar and DateComponents](https://www.donnywals.com/scheduling-daily-notifications-on-ios-using-calendar-and-datecomponents)
  **Published:** `2019-12-12T07:45:26+00:00`
  **Topics:** App Services & Extensions · Foundation & Data Formats
  **NeKI brief:** Calendar notification triggers model recurring local delivery through date components, but authorization, timezone, and missed-trigger behavior need product decisions.
- [Handling deeplinks in your app – Donny Wals](https://www.donnywals.com/handling-deeplinks-in-your-app)
  **Published:** `2019-12-11T08:00:21+00:00`
  **Topics:** Navigation & Deep Linking
  **NeKI brief:** Deep-link handling parses an incoming URL into navigation intent, keeping unsupported routes safe and separating routing from the launch lifecycle.
- [Measuring performance with os_signpost – Donny Wals](https://www.donnywals.com/measuring-performance-with-os_signpost)
  **Published:** `2019-12-10T08:00:42+00:00`
  **Topics:** Performance
  **NeKI brief:** os_signpost marks named intervals and events for Instruments, connecting user-visible latency to measured code paths without relying on coarse wall-clock logs.
- [Using Xcode’s memory graph to find memory leaks – Donny Wals](https://www.donnywals.com/using-xcodes-memory-graph-to-find-memory-leaks)
  **Published:** `2019-12-09T08:00:50+00:00`
  **Topics:** Xcode
  **NeKI brief:** Xcode's memory graph exposes retained-object relationships, making cycles and unexpected ownership paths inspectable before they become persistent memory growth.
- [Finding slow code with Instruments – Donny Wals](https://www.donnywals.com/finding-slow-code-with-instruments)
  **Published:** `2019-12-08T08:00:15+00:00`
  **Topics:** Performance
  **NeKI brief:** Instruments sampling traces identify hot stacks behind slow behavior, so optimization follows repeated evidence rather than intuition about expensive code.
- [Effectively using static and class methods and properties – Donny Wals](https://www.donnywals.com/effectively-using-static-and-class-methods-and-properties)
  **Published:** `2019-12-07T08:00:45+00:00`
  **Topics:** Concurrency
  **NeKI brief:** static members belong to a type, while class members allow subclass overrides; selecting one expresses whether polymorphic customization is intended.
- [The some keyword in Swift explained – Donny Wals](https://www.donnywals.com/opaque-result-types-and-the-some-keyword-in-swift)
  **Published:** `2019-12-06T08:00:40+00:00`
  **Topics:** Swift · SwiftUI · Xcode
  **NeKI brief:** Opaque result types expose a protocol contract while retaining one hidden concrete type, preserving specialization without exposing implementation details to callers.
- [Generics in Swift explained – Donny Wals](https://www.donnywals.com/generics-in-swift-explained)
  **Published:** `2019-12-05T08:00:22+00:00`
  **Topics:** Swift
  **NeKI brief:** Generics preserve relationships between input and output types, enabling reusable algorithms without erasing the compiler guarantees provided by concrete models.
- [Efficiently loading images in table views and collection views – Donny Wals](https://www.donnywals.com/efficiently-loading-images-in-table-views-and-collection-views)
  **Published:** `2019-12-04T07:30:20+00:00`
  **Topics:** Networking · UIKit
  **NeKI brief:** Efficient scrolling image loading combines caching, cancellation, and cell-identity checks so reused cells do not display stale network results.
- [Appropriately using DispatchQueue.main – Donny Wals](https://www.donnywals.com/appropriately-using-dispatchqueue-main)
  **Published:** `2019-12-03T08:00:21+00:00`
  **Topics:** Concurrency
  **NeKI brief:** DispatchQueue.main is for UI-bound work, while unnecessary hops can hide ownership mistakes and add ordering latency to an already main-thread caller.
- [Changes to location access in iOS 13 – Donny Wals](https://www.donnywals.com/changes-to-location-access-in-ios-13)
  **Published:** `2019-12-02T08:00:02+00:00`
  **Topics:** Maps & Location
  **NeKI brief:** Location authorization changes affect when an app may receive updates, so product flows must explain permission scope and handle reduced access gracefully.
- [Using launch arguments for easier Core Data and SwiftData debugging – Donny Wals](https://www.donnywals.com/using-launch-arguments-for-easier-core-data-debugging)
  **Published:** `2019-12-01T08:00:00+00:00`
  **Topics:** Core Data · Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** Launch arguments enable Core Data diagnostics without changing source code, making SQL and migration behavior inspectable in a reproducible debug configuration.
- [Adding haptic feedback to your app with CoreHaptics – Donny Wals](https://www.donnywals.com/adding-haptics-to-your-app)
  **Published:** `2019-11-27T08:00:43+00:00`
  **Topics:** App Services & Extensions · Developer Career & Practice
  **NeKI brief:** Haptic feedback reinforces direct interactions through system generators, but timing and intensity should support meaning rather than add incidental vibration.
- [Storage options on iOS compared – Donny Wals](https://www.donnywals.com/storage-options-on-ios-compared)
  **Published:** `2019-11-25T08:00:44+00:00`
  **Topics:** Persistence & Synchronisation
  **NeKI brief:** iOS storage choices trade queryability, durability, privacy, and migration cost; the data's access pattern should choose between defaults, files, keychain, or databases.
- [Updating your apps with silent push notifications – Donny Wals](https://www.donnywals.com/updating-your-apps-with-silent-push-notifications)
  **Published:** `2019-11-20T08:00:03+00:00`
  **Topics:** App Services & Extensions
  **NeKI brief:** Silent pushes can request background refresh without user interruption, but delivery is best-effort and needs a fallback for stale app data.
- [Real time data exchange using web sockets in iOS 13 – Donny Wals](https://www.donnywals.com/real-time-data-exchange-using-web-sockets-in-ios-13)
  **Published:** `2019-11-18T07:00:07+00:00`
  **Topics:** Networking
  **NeKI brief:** WebSockets maintain a bidirectional connection for live events, requiring reconnect, ordering, and lifecycle policy beyond the basic receive loop.
- [Announcing: Advent of Swift – Donny Wals](https://www.donnywals.com/announcing-advent-of-swift)
  **Published:** `2019-11-14T15:00:47+00:00`
  **Topics:** Swift
  **NeKI brief:** Announces an Advent of Swift learning series built around small daily language exercises. Use it as structured practice material while checking examples against the relevant Swift version.
- [Configuring projects with xcconfig – Donny Wals](https://www.donnywals.com/configuring-projects-with-xcconfig)
  **Published:** `2019-11-13T07:00:05+00:00`
  **Topics:** Xcode
  **NeKI brief:** xcconfig files centralize build settings per configuration, avoiding target-setting drift while keeping identifiers and environment values reviewable in source control.
- [Building flexible components with generics and protocols – Donny Wals](https://www.donnywals.com/building-flexible-components-with-generics-and-protocols)
  **Published:** `2019-11-11T08:00:22+00:00`
  **Topics:** Combine & Reactive Programming
  **NeKI brief:** Generics plus protocol constraints express flexible components with required capabilities, but associated-type relationships can complicate heterogeneous storage and API-erasure decisions.
- [Add iOS 12 support to a new Xcode 11 Project – Donny Wals](https://www.donnywals.com/add-ios-12-support-to-a-new-xcode-11-project)
  **Published:** `2019-11-08T12:48:40+00:00`
  **Topics:** Xcode
  **NeKI brief:** Supporting an older iOS target in a newer Xcode project requires availability-aware APIs and compatible lifecycle choices, not just lowering the deployment setting.
- [[weak self] usage in Swift explained – Donny Wals](https://www.donnywals.com/when-to-use-weak-self-and-why)
  **Published:** `2019-11-06T07:00:06+00:00`
  **Topics:** Swift
  **NeKI brief:** weak self prevents a closure from retaining its owner indefinitely, but use it only where ownership truly creates a cycle and handle owner disappearance.
- [Adding support for multiple windows to your iPadOS app – Donny Wals](https://www.donnywals.com/adding-support-for-multiple-windows-to-your-ipados-app)
  **Published:** `2019-11-04T08:00:26+00:00`
  **Topics:** Apple Platform Ecosystem
  **NeKI brief:** iPadOS multi-window support moves state and navigation into per-scene lifecycles, requiring each window to restore independently rather than sharing one global UI.
- [Uploading images and forms to a server using URLSession – Donny Wals](https://www.donnywals.com/uploading-images-and-forms-to-a-server-using-urlsession)
  **Published:** `2019-10-30T07:30:13+00:00`
  **Topics:** Networking
  **NeKI brief:** Multipart URLSession uploads assemble fields and binary data with a boundary, requiring correct content type, streaming policy, and error handling for large files.
- [Understanding the iOS 13 Scene Delegate – Donny Wals](https://www.donnywals.com/understanding-the-ios-13-scene-delegate)
  **Published:** `2019-10-28T07:30:21+00:00`
  **Topics:** Xcode
  **NeKI brief:** Explains the iOS 13 scene lifecycle and how scene delegates divide responsibility from the application delegate. Use it when migrating lifecycle code or diagnosing multi-window state and connection events.
- [Map, flatMap and compactMap in Swift explained with examples](https://www.donnywals.com/map-flatmap-and-compactmap-in-swift-explained-with-examples)
  **Published:** `2019-10-23T08:00:56+00:00`
  **Topics:** Swift
  **NeKI brief:** map transforms elements, flatMap flattens nested results, and compactMap removes nils; choosing correctly makes collection shape changes explicit.
- [Faking network responses in tests – Donny Wals](https://www.donnywals.com/faking-network-responses-in-tests)
  **Published:** `2019-10-21T06:00:28+00:00`
  **Topics:** Swift · Testing
  **NeKI brief:** Fake network responses let tests control data, latency, and failures without live services, making decoding and error behavior reproducible.
- [For loops in Swift explained with examples – Donny Wals](https://www.donnywals.com/for-loops-in-swift-explained-with-examples)
  **Published:** `2019-10-16T07:00:38+00:00`
  **Topics:** Swift
  **NeKI brief:** for-in supports break, continue, and labeled control flow, while forEach is a closure call; the distinction matters when iteration needs early exit.
- [Optimizing Your Application’s Reviews – Donny Wals](https://www.donnywals.com/optimizing-your-applications-reviews)
  **Published:** `2019-10-14T07:00:03+00:00`
  **Topics:** App Distribution & Store Operations
  **NeKI brief:** Review prompts should follow meaningful user success and system rate limits, balancing feedback requests with an experience that does not interrupt routine work.
- [What is Module Stability in Swift and why should you care? – Donny Wals](https://www.donnywals.com/what-is-module-stability-in-swift-and-why-should-you-care)
  **Published:** `2019-10-07T08:00:38+00:00`
  **Topics:** Swift
  **NeKI brief:** Explains module stability and its role in distributing binary Swift frameworks across compiler versions. Use it when choosing library-evolution settings and separating ABI compatibility from source compatibility.
- [Finding the difference between two Arrays – Donny Wals](https://www.donnywals.com/finding-the-difference-between-two-arrays)
  **Published:** `2019-10-06T10:41:56+00:00`
  **Topics:** Developer Career & Practice
  **NeKI brief:** Array-difference algorithms depend on whether duplicates and order matter, so Set-based membership shortcuts are unsuitable when collection semantics must be preserved.
- [Getting started with unit testing your Swift code on iOS - part 2 – Donny Wals](https://www.donnywals.com/getting-started-with-unit-testing-on-ios-part-2)
  **Published:** `2019-10-02T06:20:47+00:00`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Network-dependent unit tests inject controllable responses, allowing error and decoding paths to run deterministically without a live service.
- [Getting started with unit testing your Swift code on iOS - part 1 – Donny Wals](https://www.donnywals.com/getting-started-with-unit-testing-on-ios-part-1)
  **Published:** `2019-09-30T08:00:46+00:00`
  **Topics:** Swift · Testing
  **NeKI brief:** Unit tests isolate one behavior with controlled inputs and assertions, creating regression evidence before broader UI or integration tests are needed.
- [Supporting Low Data Mode in your app – Donny Wals](https://www.donnywals.com/supporting-low-data-mode-in-your-app)
  **Published:** `2019-09-23T00:00:11+00:00`
  **Topics:** Networking
  **NeKI brief:** Shows responding to the system Low Data Mode preference when scheduling network work. Use it to reduce image quality, defer refreshes, or alter downloads without treating connectivity as simply online or offline.
- [Spend less time maintaining your test suite by using the Builder Pattern](https://www.donnywals.com/spend-less-time-maintaining-your-test-suite-by-using-the-builder-pattern)
  **Published:** `2019-09-16T07:51:03+00:00`
  **Topics:** Testing
  **NeKI brief:** Test builders provide defaults with targeted overrides, reducing fixture duplication while keeping each test's meaningful setup visible and resilient to initializer changes.
- [Cleaning up your dependencies with protocols – Donny Wals](https://www.donnywals.com/cleaning-up-your-dependencies-with-protocols)
  **Published:** `2019-09-09T14:04:19+00:00`
  **Topics:** Architecture · Dependency Injection · Testing
  **NeKI brief:** Protocols define narrow dependency contracts for injection and fakes, though overly broad abstractions can hide concrete behavior rather than improve testability.
- [Enforcing modular code with frameworks in Xcode – Donny Wals](https://www.donnywals.com/enforcing-modular-code-with-frameworks-in-xcode)
  **Published:** `2016-07-17T14:54:12+00:00`
  **Topics:** Architecture · Testing · Xcode
  **NeKI brief:** Framework boundaries enforce module dependencies at compile time, improving reuse and ownership while adding build, linking, and interface-maintenance cost.
- [On variable naming when teaching – Donny Wals](https://www.donnywals.com/on-variable-naming-when-teaching)
  **Published:** `2016-05-28T09:55:15+00:00`
  **Topics:** Developer Career & Practice
  **NeKI brief:** Naming examples affects how learners infer concepts, so teaching code benefits from names that reveal role and intent without hiding the underlying mechanics.
- [Apple has launched Safari Technology Preview (and that’s great news). – Donny Wals](https://www.donnywals.com/apple-has-launched-safari-technology-preview-and-thats-great-news)
  **Published:** `2016-03-31T11:27:24+00:00`
  **Topics:** Cross-Platform & Web · Foundation & Data Formats
  **NeKI brief:** Safari Technology Preview gives web developers an early testing channel for engine changes, helping detect compatibility issues before they reach stable Safari.
- [Build a simple web scraper with node.js – Donny Wals](https://www.donnywals.com/build-a-simple-web-scraper-with-node-js)
  **Published:** `2016-02-29T15:17:37+00:00`
  **Topics:** Cross-Platform & Web · Foundation & Data Formats
  **NeKI brief:** A simple Node scraper turns remote HTML into structured data, but selectors, rate limits, and source permission boundaries must be treated as fragile dependencies.
- [Clean derived data from Xcode, the simple way – Donny Wals](https://www.donnywals.com/clean-derived-data-from-xcode-the-simple-way)
  **Published:** `2016-02-26T09:53:11+00:00`
  **Topics:** Xcode
  **NeKI brief:** Clearing DerivedData removes stale build artifacts that can mask project changes, but it also discards local caches and costs a full rebuild.
- [Wrapping your callbacks in Promises – Donny Wals](https://www.donnywals.com/wrapping-your-callbacks-in-promises)
  **Published:** `2015-11-02T17:46:50+00:00`
  **Topics:** Concurrency
  **NeKI brief:** Wrapping callbacks in promises linearizes one-shot asynchronous results, but every success, failure, and cancellation path must settle the promise exactly once.
- [How I migrated from Apache to Nginx – Donny Wals](https://www.donnywals.com/how-i-migrated-from-apache-to-nginx)
  **Published:** `2015-09-05T14:41:30+00:00`
  **Topics:** Cross-Platform & Web
  **NeKI brief:** Migrating web servers changes routing, process, and configuration assumptions, so staged verification and rollback planning matter more than benchmark claims.
- [Step up your async game with PromiseKit – Donny Wals](https://www.donnywals.com/step-up-your-async-game-with-promisekit)
  **Published:** `2015-09-03T18:03:00+00:00`
  **Topics:** Concurrency
  **NeKI brief:** Promise chains compose dependent asynchronous operations with centralized error flow, but ownership and cancellation policies remain outside the syntax itself.
- [Why you should avoid force unwrapping in Swift – Donny Wals](https://www.donnywals.com/why-you-should-avoid-force-unwrapping-in-swift)
  **Published:** `2015-07-13T11:10:57+00:00`
  **Topics:** Swift
  **NeKI brief:** Force unwrapping converts an absent optional into a runtime crash, so required values should be established by types, guards, or explicit failure handling.
- [High performance shadows for UIView – Donny Wals](https://www.donnywals.com/high-performance-shadows-for-uiview)
  **Published:** `2015-07-08T13:06:12+00:00`
  **Topics:** Performance
  **NeKI brief:** Setting a layer shadowPath gives Core Animation fixed geometry, avoiding repeated offscreen shadow calculation while requiring updates when a view's shape changes.
- [Creating a custom UICollectionViewLayout in Swift – Donny Wals](https://www.donnywals.com/creating-a-custom-uicollectionviewlayout-in-swift)
  **Published:** `2015-07-07T20:33:12+00:00`
  **Topics:** Swift
  **NeKI brief:** A custom UICollectionViewLayout computes item attributes from collection data, enabling nonstandard geometry while requiring invalidation and scrolling performance discipline.
- [Find every other element in an array with Swift – Donny Wals](https://www.donnywals.com/find-every-other-element-in-an-array-with-swift)
  **Published:** `2015-06-30T15:49:30+00:00`
  **Topics:** Swift
  **NeKI brief:** Selecting alternating array elements depends on index stride and boundary policy, providing a clear example of preserving order while extracting a regular subset.
- [Exploring protocols and protocol extensions in Swift – Donny Wals](https://www.donnywals.com/exploring-protocols-and-protocol-extensions-in-swift)
  **Published:** `2015-06-29T17:50:02+00:00`
  **Topics:** Swift
  **NeKI brief:** Protocol extensions share default behavior across conforming types, but static dispatch and requirement placement determine whether customization actually takes effect.
- [Icon fonts vs. svg icons – Donny Wals](https://www.donnywals.com/icon-fonts-vs-svg-icons)
  **Published:** `2015-04-16T18:43:14+00:00`
  **Topics:** Cross-Platform & Web · Product Design
  **NeKI brief:** Icon fonts and SVGs have different scaling, accessibility, rendering, and asset-pipeline trade-offs, so a UI system should choose intentionally rather than follow legacy habits.
- [How to choose between rem and em – Donny Wals](https://www.donnywals.com/how-to-choose-between-rem-and-em)
  **Published:** `2015-04-12T19:29:55+00:00`
  **Topics:** Developer Career & Practice
  **NeKI brief:** rem units scale from the root font size while em units inherit from their local context, so the choice controls whether typography composes or stays global.
- [Using Flexbox in the real world – Donny Wals](https://www.donnywals.com/using-flexbox-in-the-real-world)
  **Published:** `2015-04-01T19:04:56+00:00`
  **Topics:** Cross-Platform & Web
  **NeKI brief:** Flexbox distributes items along one axis with alignment rules, simplifying responsive layouts while requiring clear understanding of shrink, grow, and basis interactions.
- [Service workers are awesome – Donny Wals](https://www.donnywals.com/service-workers-are-awesome)
  **Published:** `2015-03-29T15:18:57+00:00`
  **Topics:** App Services & Extensions · Cross-Platform & Web
  **NeKI brief:** Service workers intercept web requests for offline caching and background behavior, but update lifecycle and stale-content strategy must be designed deliberately.
- [Filling in the blanks with calc() – Donny Wals](https://www.donnywals.com/filling-in-the-blanks-with-calc)
  **Published:** `2015-03-28T16:48:30+00:00`
  **Topics:** Cross-Platform & Web
  **NeKI brief:** CSS calc() combines units within one computed value, allowing responsive sizing rules without scattering hard-coded pixel arithmetic across multiple breakpoint declarations.
- [Death by papercut (why small optimizations matter) – Donny Wals](https://www.donnywals.com/death-by-papercut-why-small-optimizations-matter)
  **Published:** `2015-03-21T22:02:59+00:00`
  **Topics:** Concurrency
  **NeKI brief:** Small inefficiencies compound in hot paths and repeated user flows, so profiling-guided micro-optimizations can matter when they target measured aggregate cost.
- [Three simple ways to start a local webserver – Donny Wals](https://www.donnywals.com/three-simple-ways-to-start-a-local-webserver)
  **Published:** `2015-03-20T07:39:19+00:00`
  **Topics:** Cross-Platform & Web
  **NeKI brief:** A local web server reproduces HTTP behavior that opening files cannot, enabling routing, asset, and fetch testing with an appropriately simple tool.
- [Mobile-first is a great workflow – Donny Wals](https://www.donnywals.com/mobile-first-is-a-great-workflow)
  **Published:** `2015-03-18T13:52:32+00:00`
  **Topics:** Architecture · Developer Career & Practice · Product Design
  **NeKI brief:** Mobile-first CSS establishes a constrained baseline before adding wider-layout enhancements, preventing desktop assumptions from becoming responsive exceptions and retrofitted overrides.
- [Don’t depend on javascript to render your page. – Donny Wals](https://www.donnywals.com/dont-depend-on-javascript-to-render-your-page)
  **Published:** `2015-03-14T10:55:12+00:00`
  **Topics:** Cross-Platform & Web
  **NeKI brief:** Progressive rendering keeps essential content available before JavaScript succeeds, reducing blank-screen risk for slow, blocked, or failing scripts.
- [Automagically load your Gulp plugins – Donny Wals](https://www.donnywals.com/automagically-load-your-gulp-plugins)
  **Published:** `2015-03-11T06:45:54+00:00`
  **Topics:** CI/CD & Automation · Cross-Platform & Web
  **NeKI brief:** Automatic Gulp plugin loading reduces repetitive imports, but explicit dependencies can be clearer when build behavior must be easy to audit.
- [Stop writing vendor prefixes, autoprefixer does that for you – Donny Wals](https://www.donnywals.com/stop-writing-vendor-prefixes-autoprefixer-does-that)
  **Published:** `2015-03-10T09:13:56+00:00`
  **Topics:** Cross-Platform & Web
  **NeKI brief:** Autoprefixer derives browser-specific CSS prefixes from target support data, keeping authored styles clean while making the browser matrix an explicit build input.
- [You should start using Browsersync today. – Donny Wals](https://www.donnywals.com/you-should-start-using-browsersync-today)
  **Published:** `2015-03-08T13:35:54+00:00`
  **Topics:** Cross-Platform & Web
  **NeKI brief:** BrowserSync synchronizes reloads and interactions across test browsers, shortening responsive-development feedback loops while remaining a local workflow tool.
- [How to prevent Gulp from crashing all the time – Donny Wals](https://www.donnywals.com/how-to-prevent-gulp-from-crashing-all-the-time)
  **Published:** `2015-03-03T12:00:43+00:00`
  **Topics:** CI/CD & Automation · Cross-Platform & Web
  **NeKI brief:** Build-stream error handling keeps Gulp watch tasks alive after an asset compilation failure, exposing the error without forcing a manual restart.
- [How I improved my workflow with Imagemagick – Donny Wals](https://www.donnywals.com/how-i-improved-my-workflow-with-imagemagick)
  **Published:** `2015-02-25T13:03:12+00:00`
  **Topics:** Developer Career & Practice
  **NeKI brief:** ImageMagick automates repeatable asset conversion and resizing, reducing manual editing while requiring commands to preserve source quality and naming conventions.
- [Getting started with Gulp – Donny Wals](https://www.donnywals.com/getting-started-with-gulp)
  **Published:** `2015-02-15T13:22:00+00:00`
  **Topics:** CI/CD & Automation · Cross-Platform & Web
  **NeKI brief:** Gulp organizes repeatable asset and development tasks as streams, but teams should keep the toolchain proportional to the project's actual build needs.
- [Weekly Swift 3, Interfaces and CoreData – Donny Wals](https://www.donnywals.com/weekly-swift-3-interfaces-and-coredata)
  **Published:** `2015-02-13T09:09:35+00:00`
  **Topics:** Core Data · Swift · UIKit
  **NeKI brief:** The Swift learning update connects protocol interfaces with Core Data exploration, showing how persistence concerns and type contracts influence early architecture choices.
- [Understanding HTML5 srcset – Donny Wals](https://www.donnywals.com/understanding-html5-srcset)
  **Published:** `2015-02-08T10:59:36+00:00`
  **Topics:** Cross-Platform & Web · Product Design
  **NeKI brief:** srcset lets browsers select an image resource appropriate to display density and layout width, reducing unnecessary downloads when responsive candidates are well defined.
- [Weekly Swift 2, getting somewhere – Donny Wals](https://www.donnywals.com/weekly-swift-2-getting-somewhere)
  **Published:** `2015-02-06T08:39:32+00:00`
  **Topics:** Swift
  **NeKI brief:** Build an interface incrementally by separating layout constraints, delegate-driven behavior, and optional visual effects such as a responsive header. Keeping those responsibilities distinct makes it easier to diagnose whether a bug belongs to geometry, event routing, or animation.
- [Avoid thinking in pixels – Donny Wals](https://www.donnywals.com/avoid-thinking-in-pixels)
  **Published:** `2014-12-15T20:08:29+00:00`
  **Topics:** Cross-Platform & Web · Product Design
  **NeKI brief:** Responsive CSS should express layout with relative dimensions and content-led breakpoints instead of copying a fixed pixel canvas, so the design adapts across screen densities and widths.
- [Sharing cookies between subdomains – Donny Wals](https://www.donnywals.com/sharing-cookies-between-subdomains)
  **Published:** `2014-11-20T10:03:45+00:00`
  **Topics:** Cross-Platform & Web
  **NeKI brief:** Cookie sharing across subdomains depends on domain, path, security, and same-site attributes, so authentication behavior should be tested in the actual browser environment.
