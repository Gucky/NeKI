# Architecture

Third-party reading leads collected from NeKI sources. The links may be useful perspectives, but are not vetted recommendations or authoritative API guidance. NeKI publishes routing metadata, not the linked articles' text.

**Scope:** Application boundaries, modularity, state ownership, dependency direction, and design trade-offs.

- Last collected: `2026-07-22T21:56:49Z`
- Indexed links shown: **317**

## Direct-source reading

- [Introducing Advanced iOS App Architecture | Kodeco](https://www.kodeco.com/8477-introducing-advanced-ios-app-architecture) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Outlines a comparative advanced-architecture curriculum, including MVVM-oriented organization and case-study application. Useful as a routing lead when evaluating how presentation state, dependencies, and feature boundaries change across architecture styles rather than treating a pattern name as a design decision.
- [Networking With URLSession Course Updated for iOS 10, Xcode 8 and Swift 3 | Kodeco](https://www.kodeco.com/705-networking-with-urlsession-course-updated-for-ios-10-xcode-8-and-swift-3) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Describes a URLSession course spanning JSON GET and POST requests, authentication, client architecture, and testing in the Swift 3 era.
- [ReSwift Tutorial: Memory Game App | Kodeco](https://www.kodeco.com/516-reswift-tutorial-memory-game-app) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Implements unidirectional state flow with actions, reducers, subscriptions, routing, and asynchronous work in ReSwift. Useful as a concrete comparison point when evaluating whether centralized immutable state and explicit transitions justify the framework's ceremony.
- [Getting Started with SwiftData in iOS 26 | Kodeco](https://www.kodeco.com/49976785-getting-started-with-swiftdata-in-ios-26) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The iOS 26 SwiftData starter introduces model types, containers and SwiftUI queries as one persistence flow. Follow it to assess how observation and schema choices shape a modern app, while checking migration and background-context needs beyond the sample.
- [Swift Package Manager: Creating a Swift Package | Kodeco](https://www.kodeco.com/4047936-swift-package-manager-creating-a-swift-package) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Creates a Swift package with manifest, targets, tests, and dependencies. Useful for establishing a reusable module boundary that can build and test independently of an app project.
- [How To Make An App Like Instagram in iOS | Kodeco](https://www.kodeco.com/4001919-how-to-make-an-app-like-instagram-in-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The Instagram-style project spans feed UI, networking and a backend boundary. Its routing value is architectural: trace how media upload, pagination and authentication concerns should be separated before scaling a social feature set.
- [iOS Design Patterns | Kodeco](https://www.kodeco.com/3816-ios-design-patterns) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Introduces recurring iOS design patterns as ways to isolate specific forms of variability. Useful for asking what concrete responsibility needs separation before adopting a named pattern as architectural ceremony.
- [How To Make a Letter / Word Game with UIKit: Part 1/3 | Kodeco](https://www.kodeco.com/2749-how-to-make-a-letter-word-game-with-uikit-part-1-3) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This UIKit word-game part builds a board and keyboard around explicit game state. Follow it for the separation between rule evaluation and view updates, a pattern that remains useful in modern declarative UIs.
- [Creating a Static Library in iOS Tutorial | Kodeco](https://www.kodeco.com/2658-creating-a-static-library-in-ios-tutorial) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Creating a static iOS library exposes compile, link and resource-packaging boundaries. Follow it when maintaining legacy modularization, where symbol visibility and consumer build settings differ from a modern Swift package.
- [Resolver for iOS Dependency Injection: Getting Started | Kodeco](https://www.kodeco.com/22203552-resolver-for-ios-dependency-injection-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Refactors tightly coupled types with Resolver registrations, scopes, argument injection, protocol bindings, and mock containers. Useful for evaluating a service locator-style DI library against explicit injection, particularly where tests require isolated object graphs.
- [How To Make a Letter / Word Game with UIKit and Swift: Part 1/3 | Kodeco](https://www.kodeco.com/2187-how-to-make-a-letter-word-game-with-uikit-and-swift-part-1-3) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The first letter-game part builds UIKit board state and input handling around Swift. It is useful for seeing how game rules can remain separate from button and label presentation in an imperative UI.
- [Fundamental iOS Design Patterns | Kodeco](https://www.kodeco.com/1941154-fundamental-ios-design-patterns) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This pattern primer grounds MVC, delegation, strategy and observer in common iOS architecture. Its routing value is comparative: identify the ownership and communication problem first, then choose the smallest pattern that solves it.
- [WatchKit for watchOS 2: Initial Impressions | Kodeco](https://www.kodeco.com/1796-watchkit-for-watchos-2-initial-impressions) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Reviews early WatchKit capabilities and constraints. Useful historical context for distinguishing watch extension-era assumptions from current independent watchOS development.
- [Creating a Framework for iOS | Kodeco](https://www.kodeco.com/17753301-creating-a-framework-for-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Building an iOS framework demonstrates modularizing shared code and distributing it as a library. The useful decision point is API surface control: a framework boundary can enable reuse, but also freezes visibility and resource packaging choices.
- [Swinject Tutorial for iOS: Getting Started | Kodeco](https://www.kodeco.com/17-swinject-tutorial-for-ios-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Introduces Swinject dependency registration and resolution. Useful for comparing a container-managed object graph with explicit constructor injection in an iOS application.
- [Dependency Injection Tutorial for iOS: Getting Started | Kodeco](https://www.kodeco.com/14223279-dependency-injection-tutorial-for-ios-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Dependency injection is applied to a SwiftUI profile flow so services can be replaced and tested. Follow it to see constructor and environment trade-offs, particularly how much global convenience is acceptable before dependencies become implicit.
- [iOS Extensions: Document Provider Tutorial | Kodeco](https://www.kodeco.com/1060-ios-extensions-document-provider-tutorial) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Builds a Document Provider extension with app groups, a shared container, picker flows, and import/export behavior. Useful for understanding how an app's documents participate in other apps' file workflows without exposing its private storage directly.
- [Model-View-Controller (MVC) in iOS – A Modern Approach | Kodeco](https://www.kodeco.com/1000705-model-view-controller-mvc-in-ios-a-modern-approach) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Defines model, view, and controller responsibilities and walks through their collaboration in an iOS example. Useful for diagnosing MVC drift by asking whether presentation, domain state, and coordination have accumulated in the wrong layer.
- [Apple Chip Architecture from 1977 to 2026](https://blog.jacobstechtavern.com/p/apple-chip-architecture) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2026-06-09T15:02:45.323Z`
  **NeKI brief:** Connects Apple chip evolution to mobile software constraints, explaining why CPU, GPU, neural, memory, and power architecture influence rendering, machine-learning, and performance choices beyond simple benchmark comparisons.
- [Defining custom scenes in SwiftUI](https://nilcoalescing.com/blog/CustomScenesInSwiftUI) — Nil Coalescing · article catalogue
  **Published:** `2026-06-09`
  **NeKI brief:** Custom Scene definitions let a SwiftUI app declare window, menu, or document behavior as composable scene values. Follow it to understand lifecycle boundaries that are easy to obscure when everything is placed in App.body.
- [Beta Preview: ComposableArchitecture 2.0](https://www.pointfree.co/blog/posts/206-beta-preview-composablearchitecture-2-0) — Point-Free · article catalogue
  **Published:** `2026-04-01T00:00:00Z`
  **NeKI brief:** Previews Composable Architecture 2.0 changes and their implications for state, effects, and dependency management. Use it to assess an upcoming migration path before adopting beta conventions in a production feature.
- [Introducing: Point-Free Beta Previews](https://www.pointfree.co/blog/posts/204-introducing-point-free-beta-previews) — Point-Free · article catalogue
  **Published:** `2026-04-01T00:00:00Z`
  **NeKI brief:** Beta previews distribute DebugSnapshots and an early Composable Architecture 2.0 without making unfinished APIs the default release. The workflow gives adopters a controlled feedback channel while isolating compatibility and migration risk.
- [Hard Deprecations and Soft Landings with SwiftPM Traits](https://www.pointfree.co/blog/posts/203-hard-deprecations-and-soft-landings-with-swiftpm-traits) — Point-Free · article catalogue
  **Published:** `2026-03-16T00:00:00Z`
  **NeKI brief:** SwiftPM traits can keep a deprecated feature available as an opt-in while the default product removes its dependency, creating a soft migration before a hard break. The pattern balances source compatibility against leaner builds.
- [We’re going live soon!](https://www.pointfree.co/blog/posts/201-we-re-going-live-soon) — Point-Free · article catalogue
  **Published:** `2026-02-05T16:00:00Z`
  **NeKI brief:** The planned TCA 2.0 preview pairs a new architecture release with a live feedback loop before APIs stabilize. It is a routing lead for evaluating migration shape and testing strategy while distinguishing preview behavior from supported contracts.
- [The “Point-Free Way”, TCA 2.0 sneak peek, a giveaway, Q&A, and more!](https://www.pointfree.co/blog/posts/200-the-point-free-way-tca-2-0-sneak-peek-a-giveaway-q-a-and-more) — Point-Free · article catalogue
  **Published:** `2026-02-04T00:00:00Z`
  **NeKI brief:** The TCA 2.0 sneak peek frames concurrency and domain modeling changes as a migration conversation rather than a drop-in upgrade. Its Q&A format is useful for locating compatibility concerns before adopting a major architecture revision.
- [Deep Dive into iMessage - Behind the Making of an Agent](https://fatbobman.com/en/posts/deep-dive-into-imessage) — Fatbobman · article catalogue
  **Published:** `2025-11-19T14:12:00.000Z`
  **NeKI brief:** Investigates iMessage storage through SQLite and Core Data timestamps, then uses imessage-kit to build an automation agent. The article is a concrete reference for understanding macOS message data boundaries and automation risks.
- [2025: The Year SwiftUI Died](https://blog.jacobstechtavern.com/p/the-year-swiftui-died) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2025-11-17T16:03:10.524Z`
  **NeKI brief:** Examines SwiftUI production pain points through a 2025 retrospective, separating framework limitations from architectural misuse and identifying when teams should stabilize state, navigation, rendering, and interoperability boundaries instead of blaming declarative UI wholesale.
- [Grow on iOS 26 - Liquid Glass Adaptation in UIKit + SwiftUI Hybrid Architecture](https://fatbobman.com/en/posts/grow-on-ios26) — Fatbobman · article catalogue
  **Published:** `2025-11-12T14:12:00.000Z`
  **NeKI brief:** Documents Grow's iOS 26 Liquid Glass migration across UIKit and SwiftUI, including navigation refactors, sheet behavior, bar-button sizing, and CABackdropLayer side effects. Follow it for production integration pitfalls beyond sample code.
- [Tracking workouts with HealthKit in iOS apps](https://www.createwithswift.com/tracking-workouts-with-healthkit-in-ios-apps) — Create with Swift · article catalogue
  **Published:** `2025-11-11T14:00:06.000Z`
  **NeKI brief:** Shows reading and recording workout data through HealthKit. Follow it when designing authorization, quantity queries, background updates, and privacy-aware presentation of fitness information.
- [SwiftUI Architecture: Structure Views for Reusability and Clarity](https://www.avanderlee.com/swiftui/swiftui-architecture-structure-views-for-reusability-and-clarity) — Antoine van der Lee articles · article catalogue
  **Published:** `2025-10-21T07:28:53+00:00`
  **NeKI brief:** Refactors oversized SwiftUI view bodies by extracting responsibilities, choosing stable data flow, and isolating reusable components. The examples make the trade-off between abstraction and readable composition concrete for growing screens.
- [The Terrible Technical Architecture of my First Startup](https://blog.jacobstechtavern.com/p/my-terrible-startup-architecture) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2025-09-22T16:00:36.176Z`
  **NeKI brief:** Use an early product architecture retrospective to identify where client, backend, data, and deployment boundaries became expensive to change. Introduce modular seams, observability, and migration paths around demonstrated pressure points rather than importing enterprise complexity before the product needs it.
- [Microapps architecture in Swift. Scaling. | Swift with Majid](https://swiftwithmajid.com/2025/05/27/microapps-architecture-in-swift-scaling) — Swift with Majid · article catalogue
  **Published:** `2025-05-27T00:00:00+00:00`
  **NeKI brief:** Discusses scaling a Swift microapps architecture through modular feature boundaries. Use it when a growing app needs independently developed flows without turning every module dependency into global coupling.
- [SwiftUI Scroll Performance: The 120FPS Challenge](https://blog.jacobstechtavern.com/p/swiftui-scroll-performance-the-120fps) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2025-05-05T15:00:38.653Z`
  **NeKI brief:** Profile SwiftUI scrolling against the frame budget, especially on high-refresh-rate devices, and reduce unnecessary state changes, layout work, and view identity churn. Use Instruments and realistic data to find hitches before replacing declarative structure with imperative optimizations.
- [Dependency container on top of task local values in Swift | Swift with Majid](https://swiftwithmajid.com/2025/04/30/dependency-container-on-top-of-task-local-values-in-swift) — Swift with Majid · article catalogue
  **Published:** `2025-04-30T00:00:00+00:00`
  **NeKI brief:** Builds a dependency container using TaskLocal values. Use it when async call chains need contextual dependencies without passing parameters everywhere, while guarding scope and inheritance carefully.
- [Documenting your code with DocC | Swift with Majid](https://swiftwithmajid.com/2025/04/01/documenting-your-code-with-docc) — Swift with Majid · article catalogue
  **Published:** `2025-04-01T00:00:00+00:00`
  **NeKI brief:** Uses DocC to document modular Swift packages, where separate targets need navigable symbols and tutorials. The workflow turns documentation into a distributable module artifact, making API contracts discoverable instead of relying on repository context.
- [SwiftUI Environment - @Environment, EnvironmentObject, Custom Values](https://fatbobman.com/en/posts/swiftui-environment-concepts-and-practice) — Fatbobman · article catalogue
  **Published:** `2025-03-26T14:12:00.000Z`
  **NeKI brief:** Explains SwiftUI Environment as dependency propagation and value lookup. Use it when shared configuration or services need scoped injection without threading parameters through every intermediate view.
- [How to plan a migration to Swift 6 – Donny Wals](https://www.donnywals.com/how-to-plan-a-migration-to-swift-6) — Donny Wals · article catalogue
  **Published:** `2025-03-06T14:18:33+00:00`
  **NeKI brief:** Swift 6 migration is staged by measuring strict-concurrency diagnostics, fixing isolation boundaries, and tightening settings incrementally; postponing ownership decisions merely defers compile-time failures.
- [From Host to Serverless - A Blog Architecture Migration Journey](https://fatbobman.com/en/posts/from-host-to-serverless) — Fatbobman · article catalogue
  **Published:** `2025-02-19T14:20:00.000Z`
  **NeKI brief:** This architecture migration moves a blog from a traditional host toward serverless components, exposing trade-offs in deployment, storage, and operational coupling. Follow it for a concrete checklist when splitting a monolith without losing observability.
- [Static, Dynamic, Mergeable, oh, my!](https://blog.jacobstechtavern.com/p/static-dynamic-mergeable-oh-my) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2024-11-18T17:24:06.203Z`
  **NeKI brief:** Choose static, dynamic, or mergeable library linkage from measurable constraints such as launch time, app size, dependency reuse, and build behavior. Inspect the actual dependency graph and binary output before reorganizing modules, because linkage labels alone do not predict product performance.
- [What is dependency injection in Swift? – Donny Wals](https://www.donnywals.com/what-is-dependency-injection-in-swift) — Donny Wals · article catalogue
  **Published:** `2024-10-11T07:37:29+00:00`
  **NeKI brief:** Dependency injection moves construction decisions out of business logic, enabling deterministic fakes and environment-specific services while adding initializer or container wiring.
- [UIKit and the Composable Architecture](https://www.pointfree.co/blog/posts/150-uikit-and-the-composable-architecture) — Point-Free · article catalogue
  **Published:** `2024-08-15T00:00:00Z`
  **NeKI brief:** Shows how UIKit view controllers can host Composable Architecture stores while keeping state and effects outside imperative view code. The integration pattern helps migrate screens incrementally without forcing an all-at-once SwiftUI rewrite.
- [Swift Testing Bonanza](https://www.pointfree.co/blog/posts/148-swift-testing-bonanza) — Point-Free · article catalogue
  **Published:** `2024-07-24T00:00:00Z`
  **NeKI brief:** Surveys Swift Testing techniques used in Point-Free projects, including traits, parameterization, and dependency control. It provides concrete test-design patterns for keeping asynchronous feature tests deterministic and readable.
- [List or LazyVStack - Choosing the Right Lazy Container in SwiftUI](https://fatbobman.com/en/posts/list-or-lazyvstack) — Fatbobman · article catalogue
  **Published:** `2024-07-10T00:12:00.000Z`
  **NeKI brief:** List and LazyVStack both defer row creation, but differ in recycling, platform behavior, system affordances, and measurement costs. The comparison gives a practical choice matrix instead of assuming one lazy container is universally faster.
- [Composable Architecture Frequently Asked Questions](https://www.pointfree.co/blog/posts/141-composable-architecture-frequently-asked-questions) — Point-Free · article catalogue
  **Published:** `2024-06-04T00:00:00Z`
  **NeKI brief:** Answers recurring Composable Architecture questions about state, effects, reducers, and testing boundaries. Useful for evaluating architectural trade-offs before introducing a framework into a SwiftUI feature.
- [Building an app in the Composable Architecture, from scratch](https://www.pointfree.co/blog/posts/138-building-an-app-in-the-composable-architecture-from-scratch) — Point-Free · article catalogue
  **Published:** `2024-05-09T00:00:00Z`
  **NeKI brief:** Building a feature from scratch in the Composable Architecture makes state, actions, reducer logic, and effects visible in sequence. The workflow is useful for tracing where domain decisions belong before adding navigation or persistence.
- [We’re live!](https://www.pointfree.co/blog/posts/137-we-re-live) — Point-Free · article catalogue
  **Published:** `2024-05-09T00:00:00Z`
  **NeKI brief:** The live release discussion demonstrates how a library team explains architectural changes, migration risks, and feedback channels before finalizing APIs. Use it as process context alongside the concrete source and tests.
- [Shared state in the Composable Architecture](https://www.pointfree.co/blog/posts/135-shared-state-in-the-composable-architecture) — Point-Free · article catalogue
  **Published:** `2024-04-29T00:00:00Z`
  **NeKI brief:** Shared state in a reducer architecture needs one owner and explicit observation paths so features do not diverge silently. The design helps coordinate mutations while making synchronization behavior testable.
- [Practical SwiftData - Building SwiftUI Applications with Modern Approaches](https://fatbobman.com/en/posts/practical-swiftdata-building-swiftui-applications-with-modern-approaches) — Fatbobman · article catalogue
  **Published:** `2024-03-21T00:20:00.000Z`
  **NeKI brief:** Examines practical SwiftData application structure, including strict-concurrency challenges, model contexts, and SwiftUI integration. Use it to evaluate persistence boundaries and actor isolation before scaling a data-driven app beyond a demo.
- [Async Unit Testing: The Comprehensive Guide](https://blog.jacobstechtavern.com/p/async-unit-testing-in-swift-the-comprehensive) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2024-03-11T17:15:13.685Z`
  **NeKI brief:** Builds asynchronous unit testing from dependency injection and controllable test doubles through async/await, unstructured tasks, and Combine interoperation. Use the staged examples to reason about deterministic setup, cancellation, and ownership of asynchronous work.
- [Sharing state in the Composable Architecture](https://www.pointfree.co/blog/posts/134-sharing-state-in-the-composable-architecture) — Point-Free · article catalogue
  **Published:** `2024-02-26T00:00:00Z`
  **NeKI brief:** Sharing state across features is safer when dependencies define access and mutations flow through reducers, rather than passing mutable references freely. The article frames the resulting coordination and testing trade-offs.
- [Observation comes to the Composable Architecture](https://www.pointfree.co/blog/posts/130-observation-comes-to-the-composable-architecture) — Point-Free · article catalogue
  **Published:** `2024-01-29T00:00:00Z`
  **NeKI brief:** Observation integration lets Composable Architecture derive view updates from model access rather than explicit publisher plumbing. The change affects dependency and state boundaries, so migration should verify invalidation behavior and test isolation.
- [Modular Architecture for Apps](https://blog.jacobstechtavern.com/p/modular-architecture-for-apps) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2024-01-01T21:49:28.396Z`
  **NeKI brief:** Frames modularisation as a scaling and team-boundary decision rather than a screen-level architecture contest. The progression from a small target to separated modules makes build time, ownership, and dependency direction trade-offs explicit before a split is undertaken.
- [Observable Architecture Beta!](https://www.pointfree.co/blog/posts/125-observable-architecture-beta) — Point-Free · article catalogue
  **Published:** `2023-11-27T00:00:00Z`
  **NeKI brief:** Introduces the beta Observable Architecture tools from Point-Free and how existing Composable Architecture code can adopt the observation model. Useful for evaluating migration trade-offs between view-driven observation, testable state, and deployment support.
- [Macro Bonanza: Composable Architecture](https://www.pointfree.co/blog/posts/118-macro-bonanza-composable-architecture) — Point-Free · article catalogue
  **Published:** `2023-11-14T00:00:00Z`
  **NeKI brief:** Composable Architecture macros can synthesize repetitive reducer and observation plumbing from declared domains. The gain is less boilerplate; the trade-off is compiler-generated behavior that must be reviewed and versioned carefully.
- [Through the Ages: Apple CPU Architecture](https://blog.jacobstechtavern.com/p/through-the-ages-apple-cpu-architecture) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2023-10-30T19:47:24.880Z`
  **NeKI brief:** Traces Apple CPU architecture across generations while using each era to explain core processor concepts. It provides hardware context for performance discussions, with historical details that should not substitute for current device documentation.
- [2 Minute Tips: The Strategy Pattern](https://blog.jacobstechtavern.com/p/2-minute-tips-the-strategy-pattern) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2023-10-24T08:15:16.128Z`
  **NeKI brief:** Implements interchangeable sorting algorithms behind a Swift protocol, making the Strategy pattern's runtime substitution and differing time/space costs visible. Use it when behavior varies by policy and the algorithm choice should remain testable and isolated.
- [Composable Architecture 1.0](https://www.pointfree.co/blog/posts/112-composable-architecture-1-0) — Point-Free · article catalogue
  **Published:** `2023-07-31T00:00:00Z`
  **NeKI brief:** Introduces the 1.0 Composable Architecture model of reducers, state, actions, dependencies, and effects. Useful as a reference for explicit unidirectional data flow and testable SwiftUI features.
- [Unidirectional flow in Swift | Swift with Majid](https://swiftwithmajid.com/2023/07/11/unidirectional-flow-in-swift) — Swift with Majid · article catalogue
  **Published:** `2023-07-11T00:00:00+00:00`
  **NeKI brief:** Models state, actions, and reducers as a one-way flow, making mutations traceable and testable. The approach reduces incidental coupling, while large reducers need decomposition to avoid creating a new central bottleneck.
- [Dependency Injection Demystified](https://blog.jacobstechtavern.com/p/async-testing-masterclass-1-dependency) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2023-06-06T18:01:07.294Z`
  **NeKI brief:** Explains dependency injection as a testability boundary for asynchronous Swift code. Follow it to separate side effects from assertions and to make async tests deterministic without relying on production services.
- [Navigation tools come to the Composable Architecture](https://www.pointfree.co/blog/posts/106-navigation-tools-come-to-the-composable-architecture) — Point-Free · article catalogue
  **Published:** `2023-05-30T00:00:00Z`
  **NeKI brief:** Navigation tools model presentation and destination state inside a feature domain, allowing tests to exercise routing decisions without a live UI. The integration trades imperative convenience for explicit state transitions.
- [On Apple’s Guidance for StateObject Initialization | Swiftjective-C](https://swiftjectivec.com/Dependency-Injection-with-State-Object-SwiftUI) — Swiftjective-C · article catalogue
  **Published:** `2023-04-20T00:00:00-05:00`
  **NeKI brief:** Initializes a StateObject with injected dependencies, preserving ownership semantics while making previews and tests deterministic without hidden global services.
- [Composable navigation beta, part 2](https://www.pointfree.co/blog/posts/105-composable-navigation-beta-part-2) — Point-Free · article catalogue
  **Published:** `2023-04-17T00:00:00Z`
  **NeKI brief:** The navigation beta continues a state-driven model for stacks and presentations, emphasizing migration and composition across features. It is useful when evaluating how destination state affects restoration and deep links.
- [How to Open using Rosetta in Xcode 14.3 | Sarunw](https://sarunw.com/posts/open-using-rosetta-in-xcode-14-3) — Sarunw · article catalogue
  **Published:** `2023-04-10`
  **NeKI brief:** Explains Xcode's Rosetta launch option for Apple-silicon Macs when simulator or binary tooling still depends on Intel translation. Treat it as a compatibility diagnostic with performance cost, not a default build setting.
- [Composable navigation beta](https://www.pointfree.co/blog/posts/104-composable-navigation-beta) — Point-Free · article catalogue
  **Published:** `2023-02-27T00:00:00Z`
  **NeKI brief:** Composable navigation represents destination state in reducers, allowing deep-link and test flows to share the same transitions. The beta framing signals that migration APIs and semantics need validation before adoption.
- [Composable Architecture 1.0 Preview](https://www.pointfree.co/blog/posts/103-composable-architecture-1-0-preview) — Point-Free · article catalogue
  **Published:** `2023-02-13T00:00:00Z`
  **NeKI brief:** A 1.0 preview gives adopters a migration point for reducer, dependency, and navigation changes before final compatibility promises. It is useful release context, but concrete behavior still belongs to the versioned source.
- [Non-exhaustive testing in the Composable Architecture](https://www.pointfree.co/blog/posts/83-non-exhaustive-testing-in-the-composable-architecture) — Point-Free · article catalogue
  **Published:** `2022-10-31T05:00:00Z`
  **NeKI brief:** Non-exhaustive reducer tests focus assertions on behavior relevant to a scenario while allowing unrelated state changes. The approach reduces brittle fixtures but requires teams to decide which omissions would hide a regression.
- [The Composable Architecture (TCA)](https://fatbobman.com/en/posts/the_composable_architecture) — Fatbobman · article catalogue
  **Published:** `2022-10-18T00:12:00.000Z`
  **NeKI brief:** The Composable Architecture separates state, actions, reducers, and effects, making feature behavior testable and composable. Follow it to evaluate explicit data flow against the ceremony and dependency management it introduces.
- [Announcing the Reducer Protocol](https://www.pointfree.co/blog/posts/81-announcing-the-reducer-protocol) — Point-Free · article catalogue
  **Published:** `2022-10-10T05:00:00Z`
  **NeKI brief:** A reducer protocol makes state transitions and effects explicit as a composable unit, clarifying how feature logic can be tested without a UI. The abstraction trades ceremony for a stable boundary around action handling.
- [Dependency Injection with @State Variables | Swiftjective-C](https://swiftjectivec.com/SwiftUI-State-Dependency-Injection) — Swiftjective-C · article catalogue
  **Published:** `2022-09-14T00:00:00-05:00`
  **NeKI brief:** Injecting state dependencies into SwiftUI requires explicit ownership boundaries, avoiding accidental reinitialization when a view's body recomputes and a parent rebuilds its hierarchy.
- [Improving Composable Architecture performance](https://www.pointfree.co/blog/posts/80-improving-composable-architecture-performance) — Point-Free · article catalogue
  **Published:** `2022-09-08T05:00:00Z`
  **NeKI brief:** Performance work in a reducer architecture starts by measuring state propagation and identifying unnecessary copies or view updates. The article routes to concrete optimization trade-offs without abandoning value semantics.
- [Async Composable Architecture](https://www.pointfree.co/blog/posts/79-async-composable-architecture) — Point-Free · article catalogue
  **Published:** `2022-08-08T05:00:00Z`
  **NeKI brief:** Async effects integrate structured concurrency into reducer workflows, making cancellation and task lifetime part of feature logic. The design reduces callback plumbing but requires disciplined actor and dependency boundaries.
- [Localising a modularised application](https://www.polpiella.dev/modularised-app-localisation) — Pol Piella · article catalogue
  **Published:** `2022-07-27T00:00:00.000Z`
  **NeKI brief:** Localization in a modular app needs each module's resources and lookup boundaries to be explicit. Use shared terminology where appropriate and test every target's bundle resolution, avoiding silent fallback to untranslated strings.
- [How to prepare your iOS project to support modular architecture | Sarunw](https://sarunw.com/posts/how-to-prepare-ios-project-for-modular-architecture) — Sarunw · article catalogue
  **Published:** `2022-04-28`
  **NeKI brief:** Prepare later modularization by organizing folders around prospective modules and enforcing access levels before targets are split. Treat a folder boundary as a design boundary now, so extracting it into a package or framework does not expose accidental internals.
- [How to modularize existing iOS projects using Swift Package | Sarunw](https://sarunw.com/posts/how-to-modularize-existing-ios-projects-using-swift-package) — Sarunw · article catalogue
  **Published:** `2022-03-17`
  **NeKI brief:** Extract an existing iOS feature into a Swift Package by moving files, adding the package target, reconnecting it to the app, and tightening access levels. The access audit is essential: module boundaries expose every accidental reliance on internal symbols.
- [Microapps architecture in Swift. Dependency Injection. | Swift with Majid](https://swiftwithmajid.com/2022/02/02/microapps-architecture-in-swift-dependency-injection) — Swift with Majid · article catalogue
  **Published:** `2022-02-02T00:00:00+00:00`
  **NeKI brief:** Uses dependency injection between Swift package modules to keep microapp features independently testable. Explicit composition at the boundary avoids hidden globals, though the root assembly becomes responsible for wiring all capabilities.
- [@EnvironmentObject explained for sharing data between views in SwiftUI](https://www.avanderlee.com/swiftui/environmentobject) — Antoine van der Lee articles · article catalogue
  **Published:** `2022-02-01T08:53:05+00:00`
  **NeKI brief:** Demonstrates injecting an ObservableObject through SwiftUI's environment and reading it in descendants without forwarding properties through every initializer. It also highlights the runtime failure when a required object is missing.
- [Microapps architecture in Swift. Resources and localization. | Swift with Majid](https://swiftwithmajid.com/2022/01/26/microapps-architecture-in-swift-resources-and-localization) — Swift with Majid · article catalogue
  **Published:** `2022-01-26T00:00:00+00:00`
  **NeKI brief:** Shows how modular Swift packages own resources and localization bundles, preventing feature code from depending on the main app's bundle. Bundle lookup must remain target-aware when tests and previews run separately.
- [Microapps architecture in Swift. Feature modules. | Swift with Majid](https://swiftwithmajid.com/2022/01/19/microapps-architecture-in-swift-feature-modules) — Swift with Majid · article catalogue
  **Published:** `2022-01-19T00:00:00+00:00`
  **NeKI brief:** Splits a large Swift app into feature modules with explicit dependencies, improving build isolation and ownership. Module boundaries should follow stable domain seams rather than mirroring every screen one-for-one.
- [Microapps architecture in Swift. SPM basics. | Swift with Majid](https://swiftwithmajid.com/2022/01/12/microapps-architecture-in-swift-spm-basics) — Swift with Majid · article catalogue
  **Published:** `2022-01-12T00:00:00+00:00`
  **NeKI brief:** Uses Swift Package Manager targets to establish modular app foundations and dependency direction. Starting with small, independently buildable packages keeps later extraction cheaper, but shared utility targets need strict scope.
- [Five things iOS developers should focus on in 2022 – Donny Wals](https://www.donnywals.com/five-things-ios-developers-should-focus-on-in-2022) — Donny Wals · article catalogue
  **Published:** `2022-01-03T09:54:17+00:00`
  **NeKI brief:** The focus areas connect platform fundamentals with sustainable learning habits, offering a prioritization perspective rather than a substitute for project-specific technical requirements.
- [Lightweight dependency injection and unit testing using async functions | Swift by Sundell](https://www.swiftbysundell.com/articles/dependency-injection-and-unit-testing-using-async-await) — Swift by Sundell · article catalogue
  **Published:** `2021-12-09`
  **NeKI brief:** Builds lightweight async tests by injecting a networking dependency and replacing it with protocol-based mocks. The pattern keeps asynchronous production code intact while making response timing and failure paths deterministic enough to test.
- [Composition vs. Inheritance: code architecture solutions explained in Swift](https://www.avanderlee.com/swift/composition-inheritance-code-architecture) — Antoine van der Lee articles · article catalogue
  **Published:** `2021-11-16T09:52:06+00:00`
  **NeKI brief:** Contrasts inheritance's coupled override hierarchy with composition through collaborating types and protocols. Examples show how composition improves substitution and testability while inheritance remains useful for specialization.
- [Three ways to render a SwiftUI view in a playground | Swift by Sundell](https://www.swiftbysundell.com/tips/rendering-a-swiftui-view-in-a-playground) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Renders a SwiftUI view in a playground to inspect a small component without launching a full app. It is useful for isolated experiments, while device-specific environment and lifecycle behavior still need app-level verification.
- [Quickly replacing singletons with functions | Swift by Sundell](https://www.swiftbysundell.com/tips/quickly-replacing-singletons-with-functions) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Replaces singleton lookups with functions that return dependencies, creating a lightweight seam for tests and future configuration. The approach improves call-site control without forcing a large container, but shared lifetime must be decided explicitly.
- [Making properties overridable only in debug builds | Swift by Sundell](https://www.swiftbysundell.com/tips/making-properties-overridable-only-in-debug-builds) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Uses conditional compilation to expose mutable hooks only in debug builds, enabling test control without shipping a production escape hatch. Ensure release and debug APIs remain behaviorally aligned.
- [Enabling static dependency injection | Swift by Sundell](https://www.swiftbysundell.com/tips/enabling-static-dependency-injection) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Creates injection seams around static dependencies so tests can replace global behavior without a full container. The seam should remain explicit, preventing hidden production overrides from leaking between tests.
- [Dependency injection using functions | Swift by Sundell](https://www.swiftbysundell.com/tips/dependency-injection-using-functions) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Uses functions as lightweight dependencies, allowing tests to pass deterministic behavior directly. This avoids protocol boilerplate for simple seams, but complex lifecycle or grouping needs may justify a structured dependency type.
- [Calling instance methods as static functions | Swift by Sundell](https://www.swiftbysundell.com/tips/calling-instance-methods-as-static-functions) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Treats an instance method reference as a function when its receiver is supplied separately. This enables concise mapping, but method references should remain clear about which object supplies state.
- [Q&A: How to pick between using a struct or a class? | Swift by Sundell](https://www.swiftbysundell.com/questions/struct-vs-class) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Compares structs and classes through value semantics, identity, inheritance, and ownership. Choose based on the data model's mutation-sharing needs rather than a blanket preference.
- [Static factory methods in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/static-factory-methods-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Uses static factory methods to name construction intent and centralize configured defaults. Factories are most useful when creation validates or selects variants beyond a plain initializer.
- [Simple Swift dependency injection with functions | Swift by Sundell](https://www.swiftbysundell.com/articles/simple-swift-dependency-injection-with-functions) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Uses functions as simple dependency-injection seams for operations such as loading or formatting. This keeps tests lightweight, while larger dependency groups may need a dedicated value type.
- [Separation of concerns using protocols in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/separation-of-concerns-using-protocols-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Uses protocols to separate collaborators by the behavior each caller needs, reducing direct dependency on concrete types. Protocol boundaries should follow stable responsibilities, not be created for every class.
- [Refactoring Swift code for testability | Swift by Sundell](https://www.swiftbysundell.com/articles/refactoring-swift-code-for-testability) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Refactors code toward injectable dependencies and explicit inputs so behavior can be tested in isolation. Preserve observable behavior during extraction and avoid introducing abstractions that only serve mock mechanics.
- [Managing objects using Locks and Keys in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/managing-objects-using-locks-and-keys-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Manages shared objects with synchronization and keyed lookup patterns. Locks require disciplined scope and ordering; actor isolation may provide a safer modern alternative for async code.
- [Handling mutable models in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/handling-mutable-models-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Manages mutable models by controlling write access and observing meaningful transitions. Value semantics or actor isolation can reduce accidental shared mutation depending on the model's ownership.
- [Dismissing a SwiftUI modal or detail view | Swift by Sundell](https://www.swiftbysundell.com/articles/dismissing-swiftui-modal-and-detail-views) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Uses SwiftUI dismissal actions to close modal or detail presentations without coupling a child to navigation storage. Dismissal should respect the owning presentation context and unsaved-state policy.
- [Different flavors of dependency injection in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/different-flavors-of-dependency-injection-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Compares initializer, property, function, and environment-style dependency injection. Match the form to lifetime and requiredness, keeping production wiring explicit and test replacements local.
- [Dependency injection using factories in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/dependency-injection-using-factories-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Factories can assemble dependencies near their creation site and avoid giant initializers while preserving test substitution. Give each factory a narrow product responsibility; a global container merely relocates hidden dependency coupling unless its ownership is explicit.
- [Default arguments in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/default-arguments-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Uses default arguments to express common API configuration without overload proliferation. Defaults should be stable and unsurprising; required semantic choices deserve explicit parameters.
- [Custom container view controllers in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/custom-container-view-controllers-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Builds a custom UIViewController container by adding, removing, and transitioning child controllers while forwarding containment callbacks, illustrating how explicit ownership can modularize UIKit screen composition.
- [Constructing URLs in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/constructing-urls-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Constructs URLs from components so paths, queries, and percent encoding remain structurally correct. Avoid concatenating raw strings, especially when user input supplies query values.
- [Managing self and cancellable references when using Combine | Swift by Sundell](https://www.swiftbysundell.com/articles/combine-self-cancellable-memory-management) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Explains Combine cancellable ownership and self capture to avoid subscriptions outliving their consumers. Store cancellables with the appropriate owner and design cancellation as part of lifecycle.
- [Building an enum-based analytics system in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/building-an-enum-based-analytics-system-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Represent a closed analytics event vocabulary with enums, serialize each case centrally, and send it through a replaceable engine. This makes event names and payload requirements compiler-visible while letting production and test backends share the same API.
- [Avoiding singletons in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/avoiding-singletons-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Replace global singletons with injected services whose dependencies and lifetime are visible to callers. This makes tests substitute behavior directly and prevents unrelated features from sharing mutable global state through an apparently convenient API.
- [Avoiding massive SwiftUI views | Swift by Sundell](https://www.swiftbysundell.com/articles/avoiding-massive-swiftui-views) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Discusses decomposing large SwiftUI views by extracting stateful responsibilities and reusable subviews. Use it when a body becomes difficult to reason about and architectural boundaries should improve testability without arbitrary file splitting.
- [Point Freebies: Swift Concurrency and More](https://www.pointfree.co/blog/posts/64-point-freebies-swift-concurrency-and-more) — Point-Free · article catalogue
  **Published:** `2021-09-15T05:00:00Z`
  **NeKI brief:** The concurrency collection routes to examples of task cancellation, isolation, and structured lifetime. Use it as a map to concrete implementations, verifying each technique against the current Swift concurrency model.
- [The Composable Architecture ❤️ SwiftUI Bindings](https://www.pointfree.co/blog/posts/63-the-composable-architecture-%EF%B8%8F-swiftui-bindings) — Point-Free · article catalogue
  **Published:** `2021-09-06T05:00:00Z`
  **NeKI brief:** Composable Architecture bindings route UI edits through actions and reducer state instead of mutating model references directly. The integration keeps effects and validation testable while adding explicit binding case definitions.
- [Dependency Injection in Swift using latest Swift features - SwiftLee](https://www.avanderlee.com/swift/dependency-injection) — Antoine van der Lee articles · article catalogue
  **Published:** `2021-07-20T09:49:01+00:00`
  **NeKI brief:** Builds dependency injection with protocols and initializer defaults, then substitutes test doubles. The design separates construction from behavior while preserving convenient production call sites.
- [Better Performance Bonanza](https://www.pointfree.co/blog/posts/61-better-performance-bonanza) — Point-Free · article catalogue
  **Published:** `2021-07-14T05:00:00Z`
  **NeKI brief:** Performance improvements are most credible when accompanied by before-and-after measurements and a clear account of changed work. The collection routes to concrete Swift optimization examples rather than generic speed advice.
- [Testing dates consistently](https://www.polpiella.dev/testing-dates-consistently) — Pol Piella · article catalogue
  **Published:** `2021-07-02T00:00:00.000Z`
  **NeKI brief:** Date tests become deterministic by controlling clocks, calendars and time zones instead of comparing wall-clock values. The article is useful for eliminating locale-dependent failures from serialization and scheduling tests.
- [Announcing SwitchStore for the Composable Architecture](https://www.pointfree.co/blog/posts/59-announcing-switchstore-for-the-composable-architecture) — Point-Free · article catalogue
  **Published:** `2021-06-14T05:00:00Z`
  **NeKI brief:** SwitchStore selects a view branch from enum state while preserving the reducer as the state-transition owner. The pattern improves exhaustive UI modeling, but identity and child-store lifetime need deliberate handling.
- [Clean Architecture: A Feature Flag Manager](https://www.polpiella.dev/clean-architecture-a-feature-flag-provider) — Pol Piella · article catalogue
  **Published:** `2021-05-14T00:00:00.000Z`
  **NeKI brief:** A feature-flag provider hides remote or local flag retrieval behind an application-owned interface. Use it to keep business behavior testable and rollout policy replaceable, defining defaults for unavailable or malformed flag data.
- [App architecture basics in SwiftUI Part 4: Services | Cocoa with Love](https://www.cocoawithlove.com/blog/separated-services-layer.html) — Cocoa with Love · article catalogue
  **Published:** `2021-03-23`
  **NeKI brief:** Argues for a distinct Services layer in SwiftUI applications and shows how it isolates external effects from models and views. Follow it when deciding where networking, persistence, or system integration should live in a maintainable app.
- [Composable Architecture Test Store Improvements](https://www.pointfree.co/blog/posts/53-composable-architecture-test-store-improvements) — Point-Free · article catalogue
  **Published:** `2021-03-08T16:00:00Z`
  **NeKI brief:** Test-store improvements make action sequencing and state assertions clearer while keeping effects under test control. The workflow improves failure diagnosis, but tests still need to describe meaningful user-visible transitions.
- [App architecture basics in SwiftUI Part 3: Module-separated layers | Cocoa with Love](https://www.cocoawithlove.com/blog/app-submodules.html) — Cocoa with Love · article catalogue
  **Published:** `2021-02-12`
  **NeKI brief:** The third architecture step isolates SwiftUI layers into modules, making dependency direction explicit before choosing patterns; the cost is extra package boundaries and integration work.
- [Composable Forms: Say “Bye” to Boilerplate!](https://www.pointfree.co/blog/posts/52-composable-forms-say-bye-to-boilerplate) — Point-Free · article catalogue
  **Published:** `2021-02-01T06:00:00Z`
  **NeKI brief:** Composable forms derive validation and field state from domain structure, reducing repeated UI glue. The pattern centralizes rules but requires careful modeling of partial edits and submission effects.
- [App architecture basics in SwiftUI, Part 2: SwiftUI's natural pattern | Cocoa with Love](https://www.cocoawithlove.com/blog/swiftui-natural-pattern.html) — Cocoa with Love · article catalogue
  **Published:** `2021-01-19`
  **NeKI brief:** A minimalist SwiftUI app naturally separates view descriptions, state, and side effects; the article uses those roles to explain when adding a conventional controller would only reintroduce ceremony.
- [App architecture basics in SwiftUI, Part 1: Coding through iteration and integration | Cocoa with Love](https://www.cocoawithlove.com/blog/coding-through-iteration-and-integration.html) — Cocoa with Love · article catalogue
  **Published:** `2020-12-31`
  **NeKI brief:** A JSON feed reader is built through small compiling increments, using integration feedback to shape boundaries; this trades upfront design certainty for continuously executable architecture.
- [2020 Year-in-review](https://www.pointfree.co/blog/posts/50-2020-year-in-review) — Point-Free · article catalogue
  **Published:** `2020-12-23T06:00:00Z`
  **NeKI brief:** Recaps 2020 Composable Architecture development: feature composition, dependency control without protocol proliferation, and the 0.1.0 library release. Use it as historical context for why dependencies and reducer architecture became explicit design boundaries.
- [HTTP in Swift, Part 17: Brain Dump | Dave DeLong](https://davedelong.com/blog/2020/10/03/http-in-swift-part-17-brain-dump) — Dave DeLong · article catalogue
  **Published:** `2020-10-03T00:00:00+00:00`
  **NeKI brief:** The HTTP loader architecture is stress-tested against additional loader ideas, emphasizing reusable policy seams while acknowledging that not every feature deserves a dedicated type.
- [SwiftUI 2.0 — Apps, Scenes, and New Code Structures (Part 2)](https://fatbobman.com/en/posts/swiftui2-new-feature-2) — Fatbobman · article catalogue
  **Published:** `2020-07-08T06:00:00.000Z`
  **NeKI brief:** AppStorage and SceneStorage persist small values at different scopes, while SwiftUI 2 property wrappers clarify ownership in the data flow. Choose scene storage for per-window restoration; app storage is shared and can accidentally couple independent scenes.
- [The Composable Architecture and SwiftUI Alerts](https://www.pointfree.co/blog/posts/47-the-composable-architecture-and-swiftui-alerts) — Point-Free · article catalogue
  **Published:** `2020-06-30T04:00:00Z`
  **NeKI brief:** Alerts modeled as reducer state turn presentation and user responses into testable actions rather than imperative callbacks. The approach keeps dismissal, confirmation, and side effects in one transition system.
- [Core Motion support in the Composable Architecture](https://www.pointfree.co/blog/posts/46-core-motion-support-in-the-composable-architecture) — Point-Free · article catalogue
  **Published:** `2020-06-22T04:00:00Z`
  **NeKI brief:** Core Motion support is injected as a dependency so sensor updates can be represented as effects and substituted in tests. The boundary separates hardware lifecycle from feature state and cancellation logic.
- [Instrumenting features built in the Composable Architecture](https://www.pointfree.co/blog/posts/44-instrumenting-features-built-in-the-composable-architecture) — Point-Free · article catalogue
  **Published:** `2020-05-27T05:00:00Z`
  **NeKI brief:** Feature instrumentation can be modeled as a dependency or reducer effect, making analytics events follow the same state transitions as product behavior. This keeps telemetry testable and avoids scattered logging calls.
- [Core Location support in the Composable Architecture](https://www.pointfree.co/blog/posts/43-core-location-support-in-the-composable-architecture) — Point-Free · article catalogue
  **Published:** `2020-05-20T05:00:00Z`
  **NeKI brief:** Core Location is exposed as a dependency so authorization, updates, and cancellation become feature effects rather than view-controller callbacks. The boundary makes sensor behavior deterministic in tests.
- [Single Source of Truth in SwiftUI - Is ObservableObject Enough?](https://fatbobman.com/en/posts/observableobject-study) — Fatbobman · article catalogue
  **Published:** `2020-05-17T04:00:00.000Z`
  **NeKI brief:** ObservableObject supports reference-type state propagation, but it does not automatically make a data graph a single source of truth. Inject it at a deliberate boundary and minimize dependent views so object-change notifications do not redraw unrelated interface regions.
- [Composable Architecture, the library](https://www.pointfree.co/blog/posts/41-composable-architecture-the-library) — Point-Free · article catalogue
  **Published:** `2020-05-04T05:00:00Z`
  **NeKI brief:** Introduces Point-Free's Composable Architecture and its state, action, reducer, and effect model. Use it when evaluating a unidirectional architecture with testable feature boundaries.
- [Testing private methods and variables in Swift - SwiftLee](https://www.avanderlee.com/swift/testing-private-methods-variables) — Antoine van der Lee articles · article catalogue
  **Published:** `2020-03-17T08:00:00+00:00`
  **NeKI brief:** Argues for testing private behavior through public outcomes, while presenting limited access techniques when a seam is unavoidable. This avoids freezing implementation details in tests.
- [Class-only Protocols: class or AnyObject | Sarunw](https://sarunw.com/posts/class-only-protocols-class-or-anyobject) — Sarunw · article catalogue
  **Published:** `2020-03-09`
  **NeKI brief:** Constrain a protocol with AnyObject when it represents reference-only behavior such as a weak delegate. This replaces the deprecated class spelling while preserving the ownership requirement the compiler needs before a property can be declared weak.
- [@ - NSHipster](https://nshipster.com/at-compiler-directives) — NSHipster · article catalogue
  **Published:** `2020-01-06T00:00:00-08:00`
  **NeKI brief:** Objective-C's `@` directives mark language and runtime boundaries, from declarations to literals and synchronization constructs. Mapping those forms explains which behavior the compiler lowers and which semantics remain in the Objective-C runtime.
- [Dependency injection with Storyboards and Xcode 11 – Donny Wals](https://www.donnywals.com/dependency-injection-with-storyboards-and-xcode-11) — Donny Wals · article catalogue
  **Published:** `2019-12-23T08:00:51+00:00`
  **NeKI brief:** Storyboard dependency injection uses scene creation and preparation hooks to supply collaborators, avoiding hidden service lookups in view-controller lifecycle code.
- [Breaking an app up into modules – Donny Wals](https://www.donnywals.com/breaking-an-app-up-into-modules) — Donny Wals · article catalogue
  **Published:** `2019-12-15T08:00:44+00:00`
  **NeKI brief:** Modules isolate feature and infrastructure dependencies behind explicit package boundaries, improving build and ownership clarity while adding integration and tooling cost.
- [Redux-like state container in SwiftUI. Basics. | Swift with Majid](https://swiftwithmajid.com/2019/09/18/redux-like-state-container-in-swiftui) — Swift with Majid · article catalogue
  **Published:** `2019-09-18T00:00:00+00:00`
  **NeKI brief:** A Redux-like SwiftUI store centralizes state and actions into one update path. Follow it when app complexity requires traceable mutations, balancing that consistency against ceremony for simple features.
- [Cleaning up your dependencies with protocols – Donny Wals](https://www.donnywals.com/cleaning-up-your-dependencies-with-protocols) — Donny Wals · article catalogue
  **Published:** `2019-09-09T14:04:19+00:00`
  **NeKI brief:** Protocols define narrow dependency contracts for injection and fakes, though overly broad abstractions can hide concrete behavior rather than improve testability.
- [Composable styling in SwiftUI | Swift with Majid](https://swiftwithmajid.com/2019/08/28/composable-styling-in-swiftui) — Swift with Majid · article catalogue
  **Published:** `2019-08-28T00:00:00+00:00`
  **NeKI brief:** Composable styling layers reusable SwiftUI modifiers instead of repeating visual configuration. Follow it to create consistent design tokens, while keeping styling separate from controls’ interaction and accessibility semantics.
- [Custom UIHostingController | Sarunw](https://sarunw.com/posts/custom-uihostingcontroller) — Sarunw · article catalogue
  **Published:** `2019-08-27`
  **NeKI brief:** Subclass UIHostingController when a SwiftUI root view must participate in a storyboard or UIKit controller flow. Keep UIKit lifecycle and navigation ownership in the controller, while passing only the required model or callbacks into the SwiftUI root view.
- [Better dependency injection for Storyboards in iOS13 | Sarunw](https://sarunw.com/posts/better-dependency-injection-for-storyboards-in-ios13) — Sarunw · article catalogue
  **Published:** `2019-07-12`
  **NeKI brief:** Inject storyboard dependencies through @IBSegueAction during controller initialization instead of exposing mutable properties for post-instantiation setup. This makes required collaborators explicit before the destination loads and prevents a storyboard flow from reaching an incompletely configured controller.
- [Extracting presentation logic to make it testable | Swift with Majid](https://swiftwithmajid.com/2019/05/01/extracting-presentation-logic-to-make-it-testable) — Swift with Majid · article catalogue
  **Published:** `2019-05-01T00:00:00+00:00`
  **NeKI brief:** Presentation logic is extracted from view controllers into testable transformation code. The article is useful for separating formatting and UI decisions from side effects, enabling focused unit tests without loading views.
- [How to refactor massive view controllers – Hacking with Swift](https://www.hackingwithswift.com/articles/159/how-to-refactor-massive-view-controllers) — Hacking with Swift articles · article catalogue
  **Published:** `2019-04-07T14:01:18+00:00`
  **NeKI brief:** Extracting view-controller responsibilities into model, view, and coordinator collaborators reduces change coupling, but each new boundary needs a clear ownership contract.
- [Dependency Injection in Swift with Protocols | Swift with Majid](https://swiftwithmajid.com/2019/03/06/dependency-injection-in-swift-with-protocols) — Swift with Majid · article catalogue
  **Published:** `2019-03-06T00:00:00+00:00`
  **NeKI brief:** Protocol-based injection replaces concrete services with test doubles at construction boundaries. The guide is useful for making dependencies visible and testable without introducing a service locator that hides ownership.
- [Void - NSHipster](https://nshipster.com/void) — NSHipster · article catalogue
  **Published:** `2018-10-31T00:00:00-07:00`
  **NeKI brief:** Swift's `Void` is an alias for the empty tuple, which explains why functions returning no meaningful value still participate in generic result types. The detail matters when modeling callbacks, tuples, and overloads without inventing sentinel data.
- [How to Control the World](https://www.pointfree.co/blog/posts/21-how-to-control-the-world) — Point-Free · article catalogue
  **Published:** `2018-10-09T14:00:00Z`
  **NeKI brief:** Controlling dependencies through explicit environment values makes effects replaceable in tests and previews. The functional approach avoids hidden globals, but requires deliberate propagation of the dependency context.
- [Our New Book: App Architecture (Early Access) · objc.io](https://www.objc.io/blog/2018/01/19/new-book-ios-app-architecture) — objc.io · article catalogue
  **Published:** `2018-1-19`
  **NeKI brief:** Announces a book about iOS app architecture and its approach to structuring production code. Use it as a reading lead for architectural discussion rather than a standalone prescription.
- [An iOS alert view with a text field and a “smart” OK button – Ole Begemann](https://oleb.net/2018/uialertcontroller-textfield) — Ole Begemann · article catalogue
  **Published:** `2018-08-13T17:33:36Z`
  **NeKI brief:** Builds a UIAlertController text-field flow with validation before enabling the confirmation action. Use it when modal input must provide immediate feedback without allowing invalid values into the next state.
- [Conditional Compilation, Part 2: Including and Excluding Source Files | Dave DeLong](https://davedelong.com/blog/2018/07/25/conditional-compilation-in-swift-part-2) — Dave DeLong · article catalogue
  **Published:** `2018-07-25T00:00:00+00:00`
  **NeKI brief:** Continues conditional-compilation techniques using active compilation conditions and target configuration. Use it when refining cross-platform source boundaries without confusing compile-time and runtime availability.
- [App Architecture book – Ole Begemann](https://oleb.net/blog/2018/05/app-architecture-book) — Ole Begemann · article catalogue
  **Published:** `2018-05-24T12:30:03Z`
  **NeKI brief:** The architecture discussion frames boundaries, state ownership, and dependency direction as decisions that shape testability more than any single UI framework. It is useful context for comparing coordinator, MVVM, and unidirectional designs without recipe-driven conclusions.
- [Mastering MVVM on iOS | Swift with Majid](https://swiftwithmajid.com/2018/01/11/mastering-mvvm-on-ios) — Swift with Majid · article catalogue
  **Published:** `2018-01-11T00:00:00+00:00`
  **NeKI brief:** MVVM moves presentation transformation and commands into a view model while views render state. Follow it to improve testability, but define binding and navigation ownership clearly so the view model does not absorb every responsibility.
- [A view construction syntax | Cocoa with Love](https://www.cocoawithlove.com/blog/a-view-construction-syntax.html) — Cocoa with Love · article catalogue
  **Published:** `2017-12-15`
  **NeKI brief:** The proposed typed view syntax carries inherited parameters and optional configuration without parentheses or type repetition, improving composition while introducing a custom DSL that teammates must learn.
- [A Better MVC, Part 4: Future Directions | Dave DeLong](https://davedelong.com/blog/2017/11/06/a-better-mvc-part-4-future-directions) — Dave DeLong · article catalogue
  **Published:** `2017-11-06T00:00:00+00:00`
  **NeKI brief:** Discusses next architectural steps after improving MVC boundaries. Use it when a refactor needs a migration direction rather than introducing a replacement framework all at once.
- [A Better MVC, Part 2: Fixing Encapsulation | Dave DeLong](https://davedelong.com/blog/2017/11/06/a-better-mvc-part-2-fixing-encapsulation) — Dave DeLong · article catalogue
  **Published:** `2017-11-06T00:00:00+00:00`
  **NeKI brief:** Addresses MVC encapsulation by reducing inappropriate knowledge between components. Use it when view controllers expose internal state or coordination details that make changes ripple across a feature.
- [A Better MVC, Part 1: The Problems | Dave DeLong](https://davedelong.com/blog/2017/11/06/a-better-mvc-part-1-the-problems) — Dave DeLong · article catalogue
  **Published:** `2017-11-06T00:00:00+00:00`
  **NeKI brief:** Identifies structural problems in conventional Cocoa MVC, especially controller responsibility and testability. Follow it as the diagnostic starting point before evaluating alternative boundaries for state, presentation, and navigation.
- [The worst possible application | Cocoa with Love](https://www.cocoawithlove.com/blog/worst-possible-application.html) — Cocoa with Love · article catalogue
  **Published:** `2017-10-20`
  **NeKI brief:** Deliberately concentrating state and responsibilities in a pathological app makes architectural failure observable, providing a useful diagnostic baseline before introducing a less coupled design.
- [Statements, messages and reducers | Cocoa with Love](https://www.cocoawithlove.com/blog/statements-messages-reducers.html) — Cocoa with Love · article catalogue
  **Published:** `2017-06-22`
  **NeKI brief:** Separating statements, messages, and reducers confines mutable state to explicit computational tiers; the added routing machinery buys deterministic transitions and easier isolation of effects.
- [The weirdest subclass I've ever written | Cocoa with Love](https://www.cocoawithlove.com/blog/protocols-versus-subclasses.html) — Cocoa with Love · article catalogue
  **Published:** `2017-02-26`
  **NeKI brief:** A carefully chosen subclass preserves class-specific behavior that protocol composition cannot express, illustrating why substitutability alone is not a reason to eliminate inheritance.
- [Specifying function execution contexts | Cocoa with Love](https://www.cocoawithlove.com/blog/specifying-execution-contexts.html) — Cocoa with Love · article catalogue
  **Published:** `2016-10-14`
  **NeKI brief:** Execution context is a contract negotiated between caller and callee rather than a single queue choice; documenting both sides prevents accidental latency or thread-safety regressions.
- [Enforcing modular code with frameworks in Xcode – Donny Wals](https://www.donnywals.com/enforcing-modular-code-with-frameworks-in-xcode) — Donny Wals · article catalogue
  **Published:** `2016-07-17T14:54:12+00:00`
  **NeKI brief:** Framework boundaries enforce module dependencies at compile time, improving reuse and ownership while adding build, linking, and interface-maintenance cost.
- [iOS Architecture Patterns: Part 3 | Swiftjective-C](https://swiftjectivec.com/Architecture-Patterns-in-iOS-Part-3) — Swiftjective-C · article catalogue
  **Published:** `2016-02-20T00:00:00-06:00`
  **NeKI brief:** Compare model-view responsibilities by tracing which layer owns state, transforms data, and triggers presentation. Prefer the smallest pattern that makes those dependencies explicit and supports focused tests.
- [iOS Architecture Patterns: Part 2 | Swiftjective-C](https://swiftjectivec.com/Architecture-Patterns-in-iOS-Part-2) — Swiftjective-C · article catalogue
  **Published:** `2016-02-06T00:00:00-06:00`
  **NeKI brief:** Continue an architecture incrementally by moving navigation and feature control flow behind collaborators. Preserve clear ownership boundaries so view updates and domain decisions do not become hidden controller side effects.
- [iOS Architecture Patterns: Part 1 | Swiftjective-C](https://swiftjectivec.com/Architecture-Patterns-in-iOS-Part-1) — Swiftjective-C · article catalogue
  **Published:** `2016-01-22T00:00:00-06:00`
  **NeKI brief:** An iOS architecture should separate presentation, state, and coordination so each layer has a testable responsibility. Start with explicit data flow before introducing pattern names or framework-specific abstractions.
- [Mobile-first is a great workflow – Donny Wals](https://www.donnywals.com/mobile-first-is-a-great-workflow) — Donny Wals · article catalogue
  **Published:** `2015-03-18T13:52:32+00:00`
  **NeKI brief:** Mobile-first CSS establishes a constrained baseline before adding wider-layout enhancements, preventing desktop assumptions from becoming responsive exceptions and retrofitted overrides.
- [Apple’s Take on App Architecture – Ole Begemann](https://oleb.net/blog/2014/06/apples-take-on-app-architecture) — Ole Begemann · article catalogue
  **Published:** `2014-06-20T18:37:00Z`
  **NeKI brief:** Apple's architecture guidance separates application lifecycle, view coordination, and model responsibilities. It is useful context for evaluating boundaries, while concrete implementation choices remain product-specific.
- [How Dropbox Uses C++ for Cross-Platform iOS and Android Development – Ole Begemann](https://oleb.net/blog/2014/05/how-dropbox-uses-cplusplus-cross-platform-development) — Ole Begemann · article catalogue
  **Published:** `2014-05-23T20:17:00Z`
  **NeKI brief:** Analyzes Dropbox's former C++ shared-core strategy for iOS and Android, including the integration costs that later led it back to native languages and SDKs.
- [Namespacing - NSHipster](https://nshipster.com/namespacing) — NSHipster · article catalogue
  **Published:** `2014-02-24T00:00:00-08:00`
  **NeKI brief:** Namespacing prevents unrelated types and symbols from colliding as a codebase grows. Use modules, nested types and clear prefixes at Objective-C boundaries, avoiding artificial namespaces that obscure ownership.
- [Method Swizzling - NSHipster](https://nshipster.com/method-swizzling) — NSHipster · article catalogue
  **Published:** `2014-02-17T00:00:00-08:00`
  **NeKI brief:** Method swizzling replaces Objective-C method implementations at runtime and can alter framework behavior globally. Use it only as a tightly tested last resort, accounting for inheritance, thread safety and future OS changes.
- [Associated Objects - NSHipster](https://nshipster.com/associated-objects) — NSHipster · article catalogue
  **Published:** `2014-02-10T00:00:00-08:00`
  **NeKI brief:** Explains Objective-C associated objects and their runtime storage semantics. Useful historical context for legacy extensions, while making the hidden ownership and keying risks explicit before adoption.
- [MKTileOverlay,MKMapSnapshotter &MKDirections - NSHipster](https://nshipster.com/mktileoverlay-mkmapsnapshotter-mkdirections) — NSHipster · article catalogue
  **Published:** `2014-02-03T00:00:00-08:00`
  **NeKI brief:** MapKit overlays, snapshots and directions APIs support custom map rendering and route visualization. Use the service appropriate to the feature, respecting network latency, cache policy and attribution requirements in the UI.
- [UIAppearance - NSHipster](https://nshipster.com/uiappearance) — NSHipster · article catalogue
  **Published:** `2013-03-11T00:00:00-07:00`
  **NeKI brief:** UIAppearance applies default UIKit styling through appearance proxies before views are displayed. Use it for broad consistent theming, testing containment and lifecycle behavior rather than expecting it to override every instance property.
- [Type Encodings - NSHipster](https://nshipster.com/type-encodings) — NSHipster · article catalogue
  **Published:** `2013-02-04T00:00:00-08:00`
  **NeKI brief:** Explains Objective-C type-encoding strings as compact runtime metadata for method signatures, properties, and invocation. Use it when bridging reflection or generated interfaces, while treating the legacy syntax as version-sensitive implementation detail.
- [NSOrderedSet - NSHipster](https://nshipster.com/nsorderedset) — NSHipster · article catalogue
  **Published:** `2012-11-26T00:00:00-08:00`
  **NeKI brief:** Explains NSOrderedSet as a unique collection with stable ordering, distinct from NSSet and NSArray semantics. Use it when mapping Core Data or Objective-C models, checking equality, ordering, and Swift collection conversions.
- [UILocalizedIndexedCollation - NSHipster](https://nshipster.com/uilocalizedindexedcollation) — NSHipster · article catalogue
  **Published:** `2012-10-29T00:00:00-07:00`
  **NeKI brief:** Uses UILocalizedIndexedCollation to build locale-aware section indexes for large table views. Follow it when supporting legacy contact or catalog screens, verifying collation titles, section ordering, and modern list alternatives.
- [Working with Date and Time in Cocoa (Part 1) – Ole Begemann](https://oleb.net/blog/2011/11/working-with-date-and-time-in-cocoa-part-1) — Ole Begemann · article catalogue
  **Published:** `2011-11-17T22:55:00Z`
  **NeKI brief:** Explains the difference between absolute instants and calendar representations in Cocoa, helping avoid bugs caused by implicit time zones, locales, and date formatter assumptions.
- [A big weakness in Objective-C's weak typing | Cocoa with Love](https://www.cocoawithlove.com/2011/06/big-weakness-of-objective-c-weak-typing.html) — Cocoa with Love · article catalogue
  **Published:** `2011-06-30`
  **NeKI brief:** Objective-C's permissive message and type model shifts failures from compilation to runtime, motivating stronger boundaries where Swift or explicit validation can recover intent.
- [UITableView construction, drawing and management (revisited) | Cocoa with Love](https://www.cocoawithlove.com/2010/12/uitableview-construction-drawing-and.html) — Cocoa with Love · article catalogue
  **Published:** `2010-12-19`
  **NeKI brief:** UITableView performance depends on cell reuse, drawing cost, and when data management occurs, not simply on row count. The revisited construction guide offers profiling-oriented decisions for legacy UIKit lists.
- [Xcode Build Active Architecture Only](https://useyourloaf.com/blog/xcode-build-active-architecture-only) — Use Your Loaf · article catalogue
  **Published:** `2010-04-21T20:13:00+00:00`
  **NeKI brief:** Build Active Architecture Only shortens local build time by compiling just the connected or selected architecture. Keep release and archive builds configured for the full supported set, otherwise device-specific development settings can hide missing binary slices.
- [5 key-value coding approaches in Cocoa | Cocoa with Love](https://www.cocoawithlove.com/2010/01/5-key-value-coding-approaches-in-cocoa.html) — Cocoa with Love · article catalogue
  **Published:** `2010-01-25`
  **NeKI brief:** Five KVC approaches show how direct access, accessors, collection operators, and validation alter Cocoa data flow. Follow it to diagnose key-path failures and choose APIs that retain type and ownership clarity.
- [Getting the subclasses of an Objective-C class | Cocoa with Love](https://www.cocoawithlove.com/2010/01/getting-subclasses-of-objective-c-class.html) — Cocoa with Love · article catalogue
  **Published:** `2010-01-11`
  **NeKI brief:** Finding subclasses at runtime requires walking Objective-C's class registry and accounting for dynamically loaded types. The technique is useful for plugin discovery and diagnostic tooling, but should not replace explicit registration lightly.
- [The design of an iPhone application | Cocoa with Love](https://www.cocoawithlove.com/2009/12/design-of-iphone-application.html) — Cocoa with Love · article catalogue
  **Published:** `2009-12-08`
  **NeKI brief:** iPhone application design separates navigation, state, and rendering under memory and input constraints. The discussion is useful historical context when evaluating why early UIKit patterns favor controllers and small view hierarchies.
- [Objective-C's niche: why it survives in a world of alternatives | Cocoa with Love](https://www.cocoawithlove.com/2009/10/objective-c-niche-why-it-survives-in.html) — Cocoa with Love · article catalogue
  **Published:** `2009-10-12`
  **NeKI brief:** Objective-C's runtime messaging, Cocoa integration, and long-lived ecosystem explain its role alongside newer languages. The article is useful context when maintaining mixed-language code and choosing where interoperability is worth its cost.
- [A simple, extensible HTTP server in Cocoa | Cocoa with Love](https://www.cocoawithlove.com/2009/07/simple-extensible-http-server-in-cocoa.html) — Cocoa with Love · article catalogue
  **Published:** `2009-07-13`
  **NeKI brief:** A small extensible HTTP server in Cocoa separates parsing, routing, and connection handling behind configurable request logic. Follow it for understanding embedded-server boundaries before exposing application state over a network.
- [HashValue: an object for holding MD5 and SHA hashes | Cocoa with Love](https://www.cocoawithlove.com/2009/07/hashvalue-object-for-holding-md5-and.html) — Cocoa with Love · article catalogue
  **Published:** `2009-07-06`
  **NeKI brief:** A hash-value object encapsulates digest bytes, equality, and presentation so callers do not manipulate raw buffers. The design is useful for comparing identifiers while keeping binary representation and encoding policy centralized.
- [Easy custom UITableView drawing | Cocoa with Love](https://www.cocoawithlove.com/2009/04/easy-custom-uitableview-drawing.html) — Cocoa with Love · article catalogue
  **Published:** `2009-04-28`
  **NeKI brief:** Custom UITableView drawing can layer decoration without abandoning cell reuse, but must avoid expensive per-scroll rendering. The article helps balance visual customization against list performance in legacy UIKit.
- [Showing a "Loading..." message over the iPhone keyboard | Cocoa with Love](https://www.cocoawithlove.com/2009/04/showing-message-over-iphone-keyboard.html) — Cocoa with Love · article catalogue
  **Published:** `2009-04-12`
  **NeKI brief:** Presenting a message over the iPhone keyboard requires coordinating keyboard geometry, view hierarchy, and animation timing. The technique helps avoid overlays that are obscured or jump during text editing.
- [OrderedDictionary: Subclassing a Cocoa class cluster | Cocoa with Love](https://www.cocoawithlove.com/2008/12/ordereddictionary-subclassing-cocoa.html) — Cocoa with Love · article catalogue
  **Published:** `2008-12-18`
  **NeKI brief:** An ordered dictionary combines key lookup with stable insertion order, forcing explicit choices about mutation and enumeration semantics. The article is useful when an ordinary dictionary cannot preserve presentation order.
- [Application Design in AppKit | Cocoa with Love](https://www.cocoawithlove.com/2008/08/application-design-in-appkit.html) — Cocoa with Love · article catalogue
  **Published:** `2008-08-31`
  **NeKI brief:** Explain AppKit applications through concrete responsibilities beyond a generic MVC label: model objects, controllers, views, windows, and delegates communicate across distinct ownership boundaries. Mapping a real app onto those roles exposes where coordination should live.
- [Doing things in Cocoa with "nil" | Cocoa with Love](https://www.cocoawithlove.com/2008/06/doing-things-in-cocoa-with.html) — Cocoa with Love · article catalogue
  **Published:** `2008-06-21`
  **NeKI brief:** Objective-C permits messaging nil and initializes many scalar values to zero, simplifying optional-object flows. That convenience does not extend to collection values, where NSNull represents absence explicitly and prevents a nil insertion from changing the operation's meaning.
- [Five approaches to listening, observing and notifying in Cocoa. | Cocoa with Love](https://www.cocoawithlove.com/2008/06/five-approaches-to-listening-observing.html) — Cocoa with Love · article catalogue
  **Published:** `2008-06-07`
  **NeKI brief:** Compare manual listeners, KVO, notification centers, context notifications, and delegates by who owns the relationship and how broadly events fan out. Selecting the mechanism is an abstraction decision: direct delegation trades flexibility for clearer contracts.
- [Adapter interfaces in Objective-C, using categories. | Cocoa with Love](https://www.cocoawithlove.com/2008/05/adapter-interfaces-in-objective-c-using.html) — Cocoa with Love · article catalogue
  **Published:** `2008-05-24`
  **NeKI brief:** Objective-C categories can provide an adapter interface that lets two classes collaborate without mutual implementation dependencies. The pattern narrows coupling at the API boundary, but method-name collisions and undiscoverable category behavior require disciplined naming.
- [Construct an NSInvocation for any message, just by sending | Cocoa with Love](https://www.cocoawithlove.com/2008/03/construct-nsinvocation-for-any-message.html) — Cocoa with Love · article catalogue
  **Published:** `2008-03-19`
  **NeKI brief:** Use Objective-C message forwarding to capture a selector and arguments as NSInvocation without manually assembling a signature. This can record even broad message sets, but forwarding changes dispatch behavior and needs careful handling of return values.
- [Structuring universal links in iOS](https://tanaschita.com/swiftui-navigation-universal-links-architecture) — Tanaschita · article catalogue
  **NeKI brief:** Structures universal-link handling around SwiftUI navigation state. Use it when parsing an incoming URL, restoring a scene, and selecting a nested destination must work consistently on cold launch and while running.
- [Using NavigationPath with TabView in SwiftUI](https://tanaschita.com/swiftui-navigation-path-with-tabview) — Tanaschita · article catalogue
  **NeKI brief:** Uses NavigationPath with TabView to preserve typed navigation state per tab. Use it when deep links and tab switching must restore the correct nested destination.
- [Bridging interfaces with the Adapter pattern in Swift](https://tanaschita.com/swift-design-patterns-adapter) — Tanaschita · article catalogue
  **NeKI brief:** Demonstrates the Adapter pattern in Swift for integrating third-party or legacy APIs behind clean interfaces. Use it to isolate incompatible contracts and keep application code testable.
- [Comparing Combine's subjects with AsyncStream in Swift](https://tanaschita.com/swift-combine-subjects-vs-asyncstream) — Tanaschita · article catalogue
  **NeKI brief:** Compares Combine subjects with `AsyncStream`, contrasting multicasting and operator ecosystems with Swift Concurrency's cancellation-aware async iteration. Follow it when migrating event pipelines and deciding whether a stream needs replay, multiple consumers, or structured concurrency.
- [Building a dependency injection framework](https://tanaschita.com/dependency-injection-building-lightweight-container) — Tanaschita · article catalogue
  **NeKI brief:** Builds a lightweight dependency-injection container in Swift and discusses registration and resolution. Use it to evaluate a small explicit composition mechanism for app services, especially when replacing hidden singletons without introducing a framework-sized abstraction.
- [Updating Data in Firestore from a SwiftUI app](https://peterfriese.dev/blog/2020/swiftui-firebase-update-data) — Peter Friese articles · article catalogue
  **NeKI brief:** Firestore updates should target a document reference and encode only the fields that changed, preserving unrelated server data. The workflow separates optimistic UI state from write completion and gives failures a clear recovery path.
- [SwiftUI: Fetching Data from Firestore in Real Time](https://peterfriese.dev/blog/2020/swiftui-firebase-fetch-data) — Peter Friese articles · article catalogue
  **NeKI brief:** A Firestore snapshot listener can feed SwiftUI with real-time updates, but its registration must be paired with cancellation when the view disappears. The workflow makes subscription lifetime and ordering explicit instead of treating the database as a one-time fetch.
- [SwiftUI: Mapping Firestore Documents using Swift Codable](https://peterfriese.dev/blog/2020/swiftui-firebase-codable) — Peter Friese articles · article catalogue
  **NeKI brief:** Mapping Firestore documents through Codable centralizes field names, decoding, and identifier handling in a model boundary. The trade-off is that Firestore's dynamic values still need explicit strategies for timestamps, missing fields, and schema evolution.
- [Adding Data to Firestore from a SwiftUI app](https://peterfriese.dev/blog/2020/swiftui-firebase-add-data) — Peter Friese articles · article catalogue
  **NeKI brief:** Adding a Firestore document requires choosing whether the client or server supplies its identifier and how timestamps are generated. The article's model boundary keeps that persistence policy out of SwiftUI form state.
- [SwiftUI, Combine, and Firebase](https://peterfriese.dev/blog/2020/replicating-reminder-swiftui-firebase-part1) — Peter Friese articles · article catalogue
  **NeKI brief:** Combining SwiftUI, Combine, and Firebase requires keeping publishers for remote state separate from view-local mutations. The sample's layering makes asynchronous updates observable while retaining a clear place for authentication and persistence policy.
- [WWDC ’23: Using AR and VR to broaden your business](https://martiancraft.com/blog/2023/05/wwdc-ar-vr) — MartianCraft · article catalogue
  **NeKI brief:** The AR and VR discussion considers spatial computing as a product and interaction constraint, not merely a new rendering target. Follow it when evaluating whether immersive features solve a user problem.
- [Anticipation and Expectations: MartianCraft Staff Gear Up for WWDC ’23](https://martiancraft.com/blog/2023/05/wwdc-2023-expectations) — MartianCraft · article catalogue
  **NeKI brief:** The WWDC 2023 expectations article records pre-release developer priorities and uncertainties. Use it as historical context for comparing announced APIs with the problems teams expected platform updates to solve.
- [Creating a Component & Using Binding in SwiftUI](https://martiancraft.com/blog/2022/10/swiftui-reusable-components) — MartianCraft · article catalogue
  **NeKI brief:** Builds an animated SwiftUI card component whose state is controlled through Binding, demonstrating how reusable views expose mutation without owning the source of truth. The pattern helps separate presentation from app-level state transitions.
- [Data plays in the middle](https://martiancraft.com/blog/2018/10/data-plays-in-the-middle) — MartianCraft · article catalogue
  **NeKI brief:** The piece treats data as the integration layer between app features and services, emphasizing ownership and transformation boundaries. Follow it when deciding where mapping, validation, and persistence responsibilities should live.
- [Seven Deadly Signs That Your Software Project is in Hell](https://martiancraft.com/blog/2017/12/deadly-signs) — MartianCraft · article catalogue
  **NeKI brief:** Seven project failure signals connect unclear ownership, changing scope, and weak feedback loops to predictable delivery problems. The checklist helps technical leads diagnose process causes before adding more engineers or tooling.
- [Understanding the Android Support Library](https://martiancraft.com/blog/2015/06/android-support-library) — MartianCraft · article catalogue
  **NeKI brief:** Android Support Library separates compatibility shims from reusable components so newer APIs can serve fragmented platform versions. Choose dependencies by the minimum supported API and feature need; a support abstraction reduces branching but adds version-management responsibility.
- [My Core Data Stack](https://martiancraft.com/blog/2015/03/core-data-stack) — MartianCraft · article catalogue
  **NeKI brief:** A production-oriented Core Data stack walkthrough covering setup, contexts, and persistence boundaries. Use it to compare lifecycle and concurrency choices before adopting a shared storage layer.
- [Reducers — Chris Eidhof](https://chris.eidhof.nl/post/reducers) — Chris Eidhof · article catalogue
  **NeKI brief:** Introduces reducers as a model for state transitions and asynchronous effects, relating them to architectures such as Redux and Elm. Use it to understand reducer composition before adopting a specific framework.

## Newsletter and related leads

- [ImplementedSE-0525Safe loading API for `RawSpan`](https://github.com/apple/swift-evolution/blob/main/proposals/0525-rawspan-safe-loading-api.md) — SwiftLee Weekly · Issue 323 — Source repository · Topics: Architecture · Developer Tools · Swift
  **Published:** `2026-07-21T14:05:55.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0525Safe loading API for `RawSpan`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [You asked…we delivered! Submit your swiftCon talk by July 5th!](https://www.nextappcon.com/swiftcon) — iOS Dev Weekly · Issue 757 — Tutorial · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `3rd July 2026`
  **NeKI brief:** SwiftCon's call for speakers seeks production-focused Swift and iOS talks, including SwiftUI, architecture, performance, and testing. Follow the event page to assess the community's current themes or submit a concrete engineering case study.
- [What’s New In SwiftUI For iOS 27?](https://www.youtube.com/watch?v=tNxEqyUVGck) — Those Who Swift · Issue 273 — Video · Topics: Architecture · Swift · SwiftUI
  **Published:** `2026-07-01`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [SwiftUI: Observable macro under the hood](https://www.nsvasilev.com/posts/swiftui-observable-macro) — SwiftUI Weekly · SwiftUI Weekly - Issue #236 — Article · Topics: Macros & Metaprogramming · Swift · SwiftUI
  **Published:** `2026-06-22T10:29:00.171Z`
  **NeKI brief:** Peels back SwiftUI’s Observable macro expansion, showing the generated observation machinery behind an @Observable model. Useful when diagnosing tracking behavior, deciding which properties need observation, or explaining macro-generated code to a team.
- [Core Data + Observation: From Property-Level Reactivity to a Freer Mental Model](https://fatbobman.com/en/posts/core-data-observation-freer-mental-model) — iOS Dev Weekly · Issue 753 — Article · Topics: Core Data · Persistence & Synchronisation · Swift
  **Published:** `5th June 2026`
  **NeKI brief:** Explains how Core Data observation shifts from property-level change tracking toward a broader data-flow model, clarifying where SwiftUI invalidation and persistence boundaries meet.
- [Fatbobman](https://fatbobman.com/en/about) — iOS Dev Weekly · Issue 753 — Article · Topics: Core Data · Persistence & Synchronisation · Swift
  **Published:** `5th June 2026`
  **NeKI brief:** Presents fatbobman for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Modern Isn’t A Value. Fit Is.](https://www.swiftdifferently.com/blog/system-desgin/modern-isnot-a-value-fit-Is) — Those Who Swift · Issue 268 — Article · Topics: Architecture · Concurrency · Objective-C & Cocoa
  **Published:** `2026-05-27`
  **NeKI brief:** Argues that modern APIs are not automatically the right fit for every product or codebase. Use it as an architecture prompt: weigh compatibility, team understanding, migration cost, and user value before adopting a newer framework pattern.
- [A Feature Flags System In Swift](https://livsycode.com/best-practices/a-feature-flags-system-in-swift) — Those Who Swift · Issue 267 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2026-05-21`
  **NeKI brief:** Presents a Swift feature-flags design with centralized evaluation and rollout control. Use it to compare configuration models and testing seams, while ensuring flag ownership, expiration, and failure defaults are explicit in production.
- [How to Think About Performance in iOS](https://livsycode.com/best-practices/how-to-think-about-performance-in-ios?ref=createwithswift.com) — Create with Swift · Issue 107 — Article · Topics: Architecture · Graphics, Media & Games · Performance
  **Published:** `2026-05-15T16:00:08.000Z`
  **NeKI brief:** Frames iOS performance as a measurement and prioritization problem rather than a collection of tricks. Follow it when planning investigations, connecting user-visible symptoms to traces, and choosing fixes that improve the actual bottleneck.
- [How To Think About Performance In iOS](https://livsycode.com/best-practices/how-to-think-about-performance-in-ios) — Those Who Swift · Issue 266 — Article · Topics: Architecture · Networking · Performance
  **Published:** `2026-05-13`
  **NeKI brief:** Frames iOS performance as a measurement and prioritization problem rather than a collection of tricks. Follow it when planning investigations, connecting user-visible symptoms to traces, and choosing fixes that improve the actual bottleneck.
- [Production SwiftUI: Scalable Networking Architecture With Async/Await And Generics](https://www.youtube.com/watch?v=M5ZUGBeugP4) — Those Who Swift · Issue 266 — Video · Topics: Architecture · Concurrency · Networking
  **Published:** `2026-05-13`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Formatting Values in SwiftUI Text and TextField](https://serialcoder.dev/text-tutorials/swiftui/formatting-values-in-swiftui-text-and-textfield) — SwiftUI Weekly · SwiftUI Weekly - Issue #233 — Tutorial · Topics: Architecture · Swift · SwiftUI
  **Published:** `2026-05-11T08:48:00.658Z`
  **NeKI brief:** Explains formatting values in SwiftUI Text and TextField using format styles and bindings. Useful for locale-aware display and editing of numbers or dates while keeping model values typed and validation predictable.
- [Modern Swift Library Architecture](https://coenttb.com/en/blog/4-1-the-swift-package) — Fatbobman’s Swift Weekly · Issue 132 — Article · Topics: Architecture · Foundation & Data Formats · Swift
  **Published:** `2026-04-20T12:03:00.641Z`
  **NeKI brief:** Describes a layered Swift package ecosystem spanning primitives, standards, and foundations. Use it to study package-boundary design and dependency layering when a growing library family needs more than one monolithic module.
- [Returned For RevisionSE-0516Borrowing Sequence](https://github.com/apple/swift-evolution/blob/main/proposals/0516-borrowing-sequence.md) — SwiftLee Weekly · Issue 318 — Source repository · Topics: Architecture · Composable Architecture · Swift
  **Published:** `2026-04-07T14:09:08.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0516`Iterable`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0524Add `withTemporaryAllocation` using `Output(Raw)Span`](https://github.com/apple/swift-evolution/blob/main/proposals/0524-span-temporary-allocation.md) — SwiftLee Weekly · Issue 318 — Source repository · Topics: Architecture · Composable Architecture · Swift
  **Published:** `2026-04-07T14:09:08.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0524Add `withTemporaryAllocation` using `Output(Raw)Span`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [I Refactored 3 Apps In A Year. Here’s What I Actually Learned](https://kubamilcarz.medium.com/i-refactored-3-apps-in-a-year-heres-what-i-actually-learned-bc519ba33bb1?source=rss-b30973e2bd56------2) — Those Who Swift · Issue 259 — Article · Topics: Architecture · Concurrency · Objective-C & Cocoa
  **Published:** `2026-03-26`
  **NeKI brief:** Examines I Refactored 3 Apps In A Year. Here’s What I Actually Learned, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [CLAUDE.md for iOS Developers](https://www.youtube.com/watch?v=0UaqjKb3QHM&t=108s) — Those Who Swift · Issue 257 — Video · Topics: AI Development · Architecture · Graphics, Media & Games
  **Published:** `2026-03-11`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Modularizing Swift Apps with Swift Package Manager](https://kylebrowning.com/posts/modularizing-swift-apps-with-spm) — Those Who Swift · Issue 256 — Article · Topics: Architecture · Swift · Swift Package Manager
  **Published:** `2026-03-06`
  **NeKI brief:** Presents a concrete implementation of Modularizing Swift Apps with SPM. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.
- [SwiftUI Foundations: Build Great Apps Q&A](https://antongubarenko.substack.com/p/swiftui-foundations-build-great-apps) — Those Who Swift · Issue 254 — Article · Topics: Foundation & Data Formats · Swift · SwiftUI
  **Published:** `2026-02-18`
  **NeKI brief:** Examines SwiftUI Foundations: Build Great Apps Q&A, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Container-Based Dependency Injection](https://livsycode.com/best-practices/container-based-dependency-injection) — Those Who Swift · Issue 253 — Article · Topics: Architecture · Dependency Injection · Developer Career & Practice
  **Published:** `2026-02-12`
  **NeKI brief:** Presents container-based dependency injection in Swift and the trade-offs of centralized resolution. Use it when comparing composition strategies, keeping dependencies explicit, and preventing a container from becoming hidden global state.
- [Add an Open Recent Menu to a SwiftUI app](https://swiftdevjournal.com/posts/open-recent-menu) — SwiftUI Weekly · SwiftUI Weekly - Issue #228 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2026-02-09T10:51:28.125Z`
  **NeKI brief:** Adds an Open Recent menu to a SwiftUI app, wiring recent document state into platform menu commands. Useful for macOS document workflows that need persistence, discoverable actions, and correct scene-level ownership.
- [Community Showcase forum post](https://forums.swift.org/t/validator-a-modular-type-safe-validation-framework-for-swiftui-and-uikit/84074/1) — iOS Dev Weekly · Issue 739 — Article · Topics: Developer Community & Business · Swift · SwiftUI
  **Published:** `16th January 2026`
  **NeKI brief:** Presents community showcase forum post for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Explicit Dependency Injection Best Practices](https://livsycode.com/best-practices/explicit-dependency-injection) — Those Who Swift · Issue 247 — Article · Topics: Architecture · Dependency Injection · Swift
  **Published:** `2026-01-01`
  **NeKI brief:** Explains explicit dependency injection in Swift and why construction-time wiring improves testability. Use it when removing hidden singletons, defining feature boundaries, and keeping production composition separate from previews and test fixtures.
- [RIB](https://github.com/son-iOS/SwiftUI-RIB) — iOS Dev Tools · iOS Dev Tools: ObjectBox, RIB, Swon — Source repository · Topics: Architecture · Swift · SwiftUI
  **Published:** `2025-12-04T17:28:54.311Z`
  **NeKI brief:** SwiftUI-RIB adapts Uber's Router–Interactor–Builder architecture with dependency structs, Combine communication, and state/view containers. It is useful for comparing explicit parent-child lifecycle and navigation boundaries with coordinator or environment-driven SwiftUI designs.
- [Uber’s official documentation](https://github.com/uber/RIBs) — iOS Dev Tools · iOS Dev Tools: ObjectBox, RIB, Swon — Source repository · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2025-12-04T17:28:54.311Z`
  **NeKI brief:** Uber's RIBs framework structures mobile features around Router, Interactor, and Builder components with explicit lifecycles and parent-child ownership. Useful as an architectural comparison point for navigation-heavy applications and SwiftUI coordinators.
- [How to Build Scalable White-Label iOS Apps: From Multi-Target to Modular Architecture](https://swiftandmemes.com/how-to-build-scalable-white-label-ios-apps-from-multi-target-to-modular-architecture) — Those Who Swift · Issue 241 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2025-11-20`
  **NeKI brief:** Explains a white-label iOS architecture that evolves from multi-target projects toward modular components. Use it when separating brand configuration from shared features and assessing build, test, and release trade-offs.
- [demo projects](https://github.com/zhangqifan/Insights) — Fatbobman’s Swift Weekly · Issue 111 — Source repository · Topics: App Distribution & Store Operations · Architecture · Liquid Glass
  **Published:** `2025-11-17T12:02:46.781Z`
  **NeKI brief:** Insights contains demo projects for applying Liquid Glass design to a production health app. Use it to inspect concrete adaptations of translucent materials, hierarchy, and interaction rather than treating WWDC design guidance as abstract theory.
- [SwiftUI Architecture: Structure Views for Reusability and Clarity](https://youtu.be/W05mPR71zaQ) — SwiftLee Weekly · Issue 294 — Video · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2025-10-21T14:13:02.000Z`
  **NeKI brief:** Presents SwiftUI Architecture: Structure Views for Reusability and Clarity as a practical video walkthrough or discussion. Use it when visual demonstration, live tooling, or spoken context helps evaluate the technique, then verify APIs and version-specific claims independently.
- [Create Interactive Snippet Shortcut Using App Intents](https://www.swiftjectivec.com/create-interactive-snippet-shortcut-in-appintents) — Those Who Swift · Issue 233 — Article · Topics: App Intents & System Surfaces · Architecture · Dependency Injection
  **Published:** `2025-09-24`
  **NeKI brief:** Examines Create Interactive Snippet Shortcut Using App Intents, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Is MVVM a bad architecture for SwiftUI?](https://www.youtube.com/watch?v=KY4jvbrlzMM) — Those Who Swift · Issue 233 — Video · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2025-09-24`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [The Great Shift in Apple Development](https://captainswiftui.substack.com/p/the-great-shift-in-apple-development) — Those Who Swift · Issue 230 — Article · Topics: Architecture · Swift · SwiftUI
  **Published:** `2025-09-03`
  **NeKI brief:** Examines The Great Shift in Apple Development, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [What Is a Mobile Platform Engineer](https://mobilesystemdesign.substack.com/p/what-is-a-mobile-platform-engineer) — Those Who Swift · Issue 225 — Article · Topics: Architecture · CI/CD & Automation · Performance
  **Published:** `2025-08-07`
  **NeKI brief:** Examines What Is a Mobile Platform Engineer, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [OAuthKit](https://github.com/codefiesta/OAuthKit) — iOS Dev Tools · iOS Dev Tools: AI Git Narrator, OAuthKit, FlipKit — Source repository · Topics: Architecture · Combine & Reactive Programming · Swift
  **Published:** `2025-06-12T19:41:45.540Z`
  **NeKI brief:** OAuthKit provides an observable Swift framework for OAuth 2.0 authorization flows, centralizing state and callback handling. Useful for comparing a reusable authentication boundary with endpoint-specific browser-session code.
- [The evolution of native engineering at Tripadvisor: Part 1](https://medium.com/tripadvisor/the-evolution-of-native-engineering-at-tripadvisor-part-1-577cc0e36ec8) — SwiftUI Weekly · SwiftUI Weekly - Issue #217 — Article · Topics: Architecture · Composable Architecture · Concurrency
  **Published:** `2025-06-02T12:56:10.176Z`
  **NeKI brief:** Traces Tripadvisor's evolution of native mobile engineering and organizational architecture. Useful as large-team context for evaluating ownership, platform investment, and migration strategy alongside SwiftUI-specific decisions.
- [Harmonize](https://github.com/perrystreetsoftware/Harmonize) — iOS Dev Tools · iOS Dev Tools: Bullseye, ProgressUI, Harmonize — Source repository · Topics: Architecture · Swift · Testing
  **Published:** `2025-05-22T17:27:20.321Z`
  **NeKI brief:** Harmonize coordinates shared state and communication across SwiftUI views, addressing the friction of passing bindings and environment values through deeper hierarchies. Its implementation is a concrete reference for reducing view wiring while keeping data flow explicit.
- [Ultimate Guide to Dependency Injection for Modular iOS Apps](https://swiftandmemes.com/ultimate-guide-to-dependency-injection-for-modular-ios-apps) — Those Who Swift · Issue 215 — Article · Topics: Architecture · Dependency Injection · Swift
  **Published:** `2025-05-21`
  **NeKI brief:** Discusses Dependency Injection for Modular iOS Apps in a public developer resource. Use it to compare the author's concrete workflow and trade-offs with your project constraints, and verify any platform-specific claims against current primary documentation.
- [Enforce Your Architecture in Swift with Harmonize](https://itnext.io/goodbye-code-reviews-hello-harmonize-0a49e2872b5a) — iOS Dev Weekly · Issue 710 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2nd May 2025`
  **NeKI brief:** Presents enforce your architecture in swift with harmonize for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Swiftdata Architecture Patterns And PracticesBlog about iOS development and musings on technologyAzamSharpMohammad Azam](https://azamsharp.com/2025/03/28/swiftdata-architecture-patterns-and-practices.html?ref=createwithswift.com) — Create with Swift · Issue 55 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2025-04-04T15:49:40.000Z`
  **NeKI brief:** Explains Swiftdata Architecture Patterns And Practices, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Documenting your code with DocC](https://swiftwithmajid.com/2025/04/01/documenting-your-code-with-docc?ref=createwithswift.com) — Create with Swift · Issue 55 — Article · Topics: Accessibility · Swift · Xcode
  **Published:** `2025-04-04T15:49:40.000Z`
  **NeKI brief:** Uses DocC to document modular Swift packages, where separate targets need navigable symbols and tutorials. The workflow turns documentation into a distributable module artifact, making API contracts discoverable instead of relying on repository context.
- [Swiftdata Architecture Patterns And Practices](https://azamsharp.com/2025/03/28/swiftdata-architecture-patterns-and-practices.html) — SwiftLee Weekly · Issue 265 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2025-04-01T14:13:42.000Z`
  **NeKI brief:** Explains Swiftdata Architecture Patterns And Practices, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [The Composable Architecture: How Architectural Design Decisions Influence Performance](https://www.swiftyplace.com/blog/the-composable-architecture-performance) — SwiftUI Weekly · SwiftUI Weekly - Issue #211 — Article · Topics: Architecture · Objective-C & Cocoa · Performance
  **Published:** `2025-03-25T13:30:35.672Z`
  **NeKI brief:** Examines performance implications of The Composable Architecture in SwiftUI, including reducer and view update costs. Useful for measuring architectural overhead in realistic workloads rather than assuming framework use is free or prohibitive.
- [Simple Modularization Setup for a New App](https://www.manu.show/2025-02-27-simple-modularization-setup) — Those Who Swift · Issue 204 — Article · Topics: Architecture · Swift · Swift Package Manager
  **Published:** `2025-03-05`
  **NeKI brief:** Examines Simple Modularization Setup for a New App, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Giffy](https://github.com/uwaisalqadri/Giffy) — iOS Dev Tools · iOS Dev Tools: Starview, Mint, Giffy — Source repository · Topics: Architecture · Composable Architecture · Swift
  **Published:** `2025-02-13T18:15:48.650Z`
  **NeKI brief:** Giffy is a sample iOS application that combines SwiftUI, The Composable Architecture, and Swinject-based dependency injection. Use it to inspect how those architectural pieces are wired together in a small, runnable project.
- [project](https://github.com/arrinal/ios-clean-architecture-project) — Fatbobman’s Swift Weekly · Issue 67 — Source repository · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2025-01-20T12:03:32.506Z`
  **NeKI brief:** Offers a concrete iOS Clean Architecture project layout rather than a conceptual diagram. Follow it to inspect boundaries between presentation, domain, and data layers and judge the ceremony against a real app.
- [backend service](https://github.com/arrinal/sample-service-swift-vapor) — Fatbobman’s Swift Weekly · Issue 67 — Source repository · Topics: Architecture · Developer Tools · Swift
  **Published:** `2025-01-20T12:03:32.506Z`
  **NeKI brief:** Pairs a Swift service example with Vapor, making the repository useful for tracing request handling and application-layer separation. Follow it when comparing server-side Swift structure with client architecture conventions.
- [TCA](https://github.com/pointfreeco/swift-composable-architecture) — Fatbobman’s Swift Weekly · Issue 61 — Source repository · Topics: Architecture · Composable Architecture · Swift
  **Published:** `2024-12-09T12:00:43.829Z`
  **NeKI brief:** The Composable Architecture structures feature state, actions, reducers, dependencies, and tests around explicit unidirectional flow. Use the repository and migration material to evaluate operational trade-offs before adopting or upgrading TCA in a production app.
- [Guide to app architecture](https://developer.android.com/topic/architecture) — iOS Dev Weekly · Issue 685 — Article · Topics: Architecture · Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `1st November 2024`
  **NeKI brief:** Presents guide to app architecture for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [learning pathway](https://developer.android.com/courses/pathways/android-architecture) — iOS Dev Weekly · Issue 685 — Tutorial · Topics: Architecture · Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `1st November 2024`
  **NeKI brief:** Presents learning pathway for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Modular Navigation in SwiftUI: A Comprehensive Guide](https://ericsspace.com/articles/modular-navigation-in-swiftui-a-comprehensive-guide) — SwiftUI Weekly · SwiftUI Weekly - Issue #201 — Article · Topics: Architecture · Swift · SwiftUI
  **Published:** `2024-10-21T14:26:23.455Z`
  **NeKI brief:** Presents a modular navigation architecture for SwiftUI with separated route and feature concerns. Useful when deep links and navigation flows outgrow a single view's path handling.
- [Hummingbird](https://github.com/hummingbird-project/hummingbird) — iOS Dev Tools · iOS Dev Tools: Hummingbird, Apollo iOS, MBProgressHUD — Source repository · Topics: Architecture · Developer Tools · Swift
  **Published:** `2024-10-03T14:43:23.083Z`
  **NeKI brief:** Hummingbird is a modular server framework built on SwiftNIO, offering routing, request handling, and optional server components. Use it when a Swift backend needs a smaller, composable alternative to a more opinionated web framework.
- [SwiftDeps](https://swiftdeps.com/) — iOS Dev Tools · iOS Dev Tools: ControlRoom, SwiftDeps, Starscream — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2024-07-25T15:18:00.048Z`
  **NeKI brief:** SwiftDeps visualizes and manages dependencies among Xcode project components, helping teams inspect architectural connections. Use it when reviewing modularization or dependency direction and when generated project structure needs a more navigable map.
- [List or LazyVStack: Choosing the Right Lazy Container in SwiftUI](https://fatbobman.com/en/posts/list-or-lazyvstack?ref=createwithswift.com) — Create with Swift · Issue 22 — Article · Topics: Performance · Swift · SwiftUI
  **Published:** `2024-07-19T16:00:03.000Z`
  **NeKI brief:** List and LazyVStack both defer row creation, but differ in recycling, platform behavior, system affordances, and measurement costs. The comparison gives a practical choice matrix instead of assuming one lazy container is universally faster.
- [Swinject](https://github.com/Swinject/Swinject) — iOS Dev Tools · iOS Dev Tools: AppLayoutsUI, Swinject, Pieces Copilot+ — Source repository · Topics: Architecture · Dependency Injection · Developer Tools
  **Published:** `2024-07-11T14:52:09.603Z`
  **NeKI brief:** Swinject resolves object graphs through registered factories and supports scopes such as transient or container lifetime. Use it to compare explicit dependency composition with container-based injection, especially around runtime resolution failures and test overrides.
- [Factory](https://github.com/hmlongco/Factory) — iOS Dev Tools · iOS Dev Tools: Anka, Factory, Runme — Source repository · Topics: Architecture · Concurrency · Swift
  **Published:** `2024-07-04T18:41:08.075Z`
  **NeKI brief:** Factory is a Swift dependency-injection container using property wrappers and scoped registrations for SwiftUI and UIKit. Use it when dependency overrides must be concise in previews and tests, while keeping registration ownership visible.
- [Tuist](https://tuist.io/) — iOS Dev Tools · iOS Dev Tools: Pricetag, Tuist, Snapshots — Article · Topics: Architecture · Developer Tools · Foundation & Data Formats
  **Published:** `2024-06-27T16:03:43.649Z`
  **NeKI brief:** Tuist provides project generation and automation for Xcode-based applications. Evaluate it when scaling modular projects, balancing reproducibility and abstraction against Xcode project complexity.
- [Sw!ftalyzer](https://swiftalyzer.com/) — iOS Dev Tools · iOS Dev Tools: Sw!ftalyzer, Invoice Maker, SQLite.swift — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2024-05-30T15:20:30.896Z`
  **NeKI brief:** Swiftalyzer is a Swift code-analysis tool intended to surface project structure or quality signals. Use it as a discovery lead for static analysis, verifying rule coverage, false-positive handling, performance, and integration with the project’s review pipeline.
- [Pointfree's SyncUps App: A Great Example Architecture for a SwiftUI App](https://rodschmidt.com/posts/syncups) — SwiftUI Weekly · SwiftUI Weekly - Issue #186 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2024-05-15T12:55:37.453Z`
  **NeKI brief:** Analyses Point-Free's SyncUps sample architecture and feature boundaries. Useful for studying a complete SwiftUI application structure before adapting its patterns selectively.
- [SyncUps](https://github.com/pointfreeco/syncups) — SwiftUI Weekly · SwiftUI Weekly - Issue #186 — Source repository · Topics: Architecture · Developer Tools · Objective-C & Cocoa
  **Published:** `2024-05-15T12:55:37.453Z`
  **NeKI brief:** Provides the SyncUps sample repository with SwiftUI architecture, persistence, and tests. Useful for inspecting concrete implementation trade-offs rather than relying on abstract diagrams.
- [Migrating from CocoaPods to Tuist at Playtomic](https://dev.to/playtomic/migrating-from-cocoapods-to-tuist-at-playtomic-26ed?issue=031) — Fatbobman’s Swift Weekly · Issue 31 — Article · Topics: Architecture · Composable Architecture · Objective-C & Cocoa
  **Published:** `2024-05-13T12:02:47.849Z`
  **NeKI brief:** Describes a production migration from CocoaPods to Tuist, including project-generation and dependency-management implications. Follow it when planning a build-system transition and identifying CI or target-configuration risks.
- [The Composable Architecture: My 3 Year Experience](https://rodschmidt.com/posts/composable-architecture-experience) — SwiftUI Weekly · SwiftUI Weekly - Issue #185 — Article · Topics: Architecture · Composable Architecture · Objective-C & Cocoa
  **Published:** `2024-05-06T13:22:31.904Z`
  **NeKI brief:** A three-year TCA retrospective surfaces production trade-offs that API introductions omit, including architectural discipline and maintenance cost. Use it to evaluate long-lived team fit rather than reading it as a generic framework endorsement.
- [The Composable Architecture: My 3 Year Experience](https://rodschmidt.com/posts/composable-architecture-experience?issue=030) — Fatbobman’s Swift Weekly · Issue 30 — Article · Topics: Architecture · Composable Architecture · Objective-C & Cocoa
  **Published:** `2024-05-06T12:01:46.954Z`
  **NeKI brief:** A three-year TCA retrospective surfaces production trade-offs that API introductions omit, including architectural discipline and maintenance cost. Use it to evaluate long-lived team fit rather than reading it as a generic framework endorsement.
- [Questions about the data to create LLMs for embeddings](https://rhonabwy.com/2023/11/15/questions-about-the-data-to-create-llms-for-embeddings) — Fatbobman’s Swift Weekly · Issue 7 — Article · Topics: AI Development · Architecture · Swift
  **Published:** `2023-11-20T22:20:48.455Z`
  **NeKI brief:** Raises practical questions about collecting and preparing data for embedding-oriented language models. Follow it when designing retrieval datasets and evaluating provenance, chunking, quality, and privacy rather than treating embeddings as a drop-in search feature.
- [PEP 730 – Adding iOS as a supported platform](https://peps.python.org/pep-0730) — Fatbobman’s Swift Weekly · Issue 6 — Article · Topics: App Distribution & Store Operations · Architecture · Objective-C & Cocoa
  **Published:** `2023-11-13T22:20:44.462Z`
  **NeKI brief:** PEP 730 proposes adding iOS as a supported Python platform and outlines packaging and runtime considerations. Follow it when evaluating Python components in an iOS toolchain, distinguishing language support from native framework and App Store constraints.
- [A Layered Approach to Mobile App Security](https://www.guardsquare.com/defense-in-depth-layered-approach-to-mobile-app-security) — iOS Dev Weekly · Issue 612 — Article · Topics: Architecture · Objective-C & Cocoa · Security & Privacy
  **Published:** `2nd June 2023`
  **NeKI brief:** Explores A Layered Approach to Mobile App Security, focusing on developers are being called on to reevaluate their mobile application. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Featuring XcodeGen, Factory, & Swinject](https://github.com/yonaskolb/XcodeGen) — iOS Dev Tools · 🔨 Xcode Mastery & Updated Strategy? — Source repository · Topics: Concurrency · Swift · Xcode
  **Published:** `2023-06-01T12:01:55.488Z`
  **NeKI brief:** XcodeGen generates Xcode projects from a declarative YAML or JSON specification. Use it to make targets, build settings, schemes, and dependencies reviewable text, avoiding fragile manual edits to project.pbxproj files.
- [The evolution of Facebook’s iOS app architecture](https://engineering.fb.com/2023/02/06/ios/facebook-ios-app-architecture) — iOS Dev Weekly · Issue 596 — Article · Topics: Architecture · Objective-C & Cocoa
  **Published:** `10th February 2023`
  **NeKI brief:** Explores The evolution of Facebook’s iOS app architecture, focusing on i’ve never worked on a huge ios app like facebook,. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Composition in TCA: Scope, Combine and Pullback operators](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyJnY9WmYycEZFYTN1ZXciLCJwb3N0X2lkIjoiNTAxNjg3MDctMTllNi00OWVjLWEzMGUtZDM0NTg5OGM5Mzk5IiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6ImJkOTY3MzY1LTVhYTAtNGIzOS05NWY0LTJhMGViNjgwNTJhMyIsImlhdCI6MTY3NDA2MjU1Ni45LCJpc3MiOiJvcmNoaWQifQ.oCLiQ-6M7I0rhyM9-07MqJd2m-21FbRxpLCYhEXIV-0) — SwiftUI Weekly · SwiftUI Weekly - Issue #121 — Article · Topics: Architecture · Combine & Reactive Programming · Composable Architecture
  **Published:** `2022-11-21T12:42:39.000Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [View Is The View Model](https://azamsharp.com/2022/07/21/view-is-the-view-model.html) — iOS Dev Weekly · Issue 569 — Article · Topics: Architecture · Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `29th July 2022`
  **NeKI brief:** Explores View Is The View Model, focusing on do you need view models if you’re working with swiftui?. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [WPF](https://docs.microsoft.com/en-us/visualstudio/designers/getting-started-with-wpf) — iOS Dev Weekly · Issue 569 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `29th July 2022`
  **NeKI brief:** Explores WPF, focusing on do you need view models if you’re working with swiftui? mohammad azam makes the case in this post that you may not.. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Transitioning from Intel to Apple Silicon](https://www.macstadium.com/transitioning-from-intel-to-apple-silicon) — iOS Dev Weekly · Issue 560 — Article · Topics: Architecture · Objective-C & Cocoa
  **Published:** `27th May 2022`
  **NeKI brief:** Explores Transitioning from Intel to Apple Silicon, focusing on not sure how your mac builds or tests will be. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [How does the SwiftUI Environment work and can it be used outside SwiftUI for Dependency Injection?](https://blog.human-friendly.com/how-does-the-swiftui-environment-work-and-can-it-be-used-outside-swiftui-for-dependency-injection) — iOS Dev Weekly · Issue 497 — Tutorial · Topics: Architecture · Swift · SwiftUI
  **Published:** `5th March 2021`
  **NeKI brief:** Examines How does the SwiftUI Environment work and can it be used outside SwiftUI for Dependency Injection?, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Hummingbird](https://opticalaberration.com/2021/02/hummingbird.html) — iOS Dev Weekly · Issue 496 — Article · Topics: Architecture · Cross-Platform & Web · Swift
  **Published:** `26th February 2021`
  **NeKI brief:** Examines Hummingbird, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Dependency Injection in SwiftUI](https://mokacoding.com/blog/swiftui-dependency-injection) — iOS Dev Weekly · Issue 480 — Article · Topics: Architecture · Swift · SwiftUI
  **Published:** `30th October 2020`
  **NeKI brief:** Examines Dependency Injection in SwiftUI, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Double-Edged Sword](https://mohsen.dev/2020/06/21/swiftui-double-edged-sword.html) — iOS Dev Weekly · Issue 462 — Article · Topics: Architecture · Swift · SwiftUI
  **Published:** `26th June 2020`
  **NeKI brief:** Examines Double-Edged Sword, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [this walkthrough video](https://www.pointfree.co/episodes/ep100-a-tour-of-the-composable-architecture-part-1) — iOS Dev Weekly · Issue 455 — Article · Topics: Architecture · Objective-C & Cocoa · Testing
  **Published:** `8th May 2020`
  **NeKI brief:** A free tour of the newly open-sourced Composable Architecture that builds an application while introducing its state-management model. Useful for assessing the framework from a concrete implementation rather than only its API surface or architectural claims.
- [example apps](https://github.com/pointfreeco/swift-composable-architecture/tree/master/Examples) — iOS Dev Weekly · Issue 455 — Source repository · Topics: Architecture · Objective-C & Cocoa · Testing
  **Published:** `8th May 2020`
  **NeKI brief:** Examines example apps, focusing on from a first look at this new architecture framework from brandon williams and stephen celis, i like it. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [this post from Alejandro Martinez](https://alejandromp.com/blog/pointfree-composable-architecture-showcase) — iOS Dev Weekly · Issue 455 — Article · Topics: Architecture · Objective-C & Cocoa · Testing
  **Published:** `8th May 2020`
  **NeKI brief:** Collects a hands-on showcase of Point-Free’s Composable Architecture after early access to the library. It is useful for comparing a third-party implementation perspective with the framework’s own materials and identifying concrete patterns before committing an app architecture.
- [MVP and Coordinators in SwiftUI](https://lascorbe.com/posts/2020-04-27-MVPCoordinators-SwiftUI-part1) — iOS Dev Weekly · Issue 454 — Article · Topics: Architecture · Swift · SwiftUI
  **Published:** `1st May 2020`
  **NeKI brief:** Examines MVP and Coordinators in SwiftUI, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [2](https://lascorbe.com/posts/2020-04-28-MVPCoordinators-SwiftUI-part2) — iOS Dev Weekly · Issue 454 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `1st May 2020`
  **NeKI brief:** Continues the MVP-and-coordinators SwiftUI series with navigation composition and dependency flow. Compare the coordinator boundaries with your app's state model, then verify historical SDK assumptions before production use.
- [3](https://lascorbe.com/posts/2020-04-29-MVPCoordinators-SwiftUI-part3) — iOS Dev Weekly · Issue 454 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `1st May 2020`
  **NeKI brief:** Concludes the MVP-and-coordinators SwiftUI series, showing how screen routing and presentation responsibilities fit together. Use it to assess testability and state ownership, then verify historical SDK assumptions before production use.
- [diagnostic architecture](https://swift.org/blog/new-diagnostic-arch-overview) — iOS Dev Weekly · Issue 442 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `7th February 2020`
  **NeKI brief:** Examines new diagnostic architecture, focusing on one of those things got much better this week with the passing of the cutoff date for swift 5.2, and the appearance of…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against.
- [Using Type Erasure to Build a Dependency Injecting Routing Framework](https://swiftrocks.com/using-type-erasure-to-build-a-dependency-injector-in-swift.html) — iOS Dev Weekly · Issue 437 — Article · Topics: Architecture · Dependency Injection · Swift
  **Published:** `3rd January 2020`
  **NeKI brief:** Examines Using Type Erasure to Build a Dependency Injecting Routing Framework, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [SwiftUI Architectures: Model-View, Redux & MVVM](https://quickbirdstudios.com/blog/swiftui-architecture-redux-mvvm) — iOS Dev Weekly · Issue 430 — Article · Topics: Architecture · Objective-C & Cocoa · Product Design
  **Published:** `15th November 2019`
  **NeKI brief:** Examines SwiftUI Architectures: Model-View, Redux & MVVM, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Dependency Injection in Practice](https://www.racecondition.software/blog/dependency-injection) — iOS Dev Weekly · Issue 412 — Article · Topics: Architecture · Dependency Injection
  **Published:** `12th July 2019`
  **NeKI brief:** Examines Dependency Injection in Practice, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [great article on dependency injection](http://www.vadimbulavin.com/dependency-injection-in-swift) — iOS Dev Weekly · Issue 408 — Article · Topics: Architecture · Dependency Injection · Swift
  **Published:** `14th June 2019`
  **NeKI brief:** Examines great article on dependency injection, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Down the rabbit hole of iOS design patterns](https://benoitpasquier.com/down-rabbit-hole-ios-design-patterns) — iOS Dev Weekly · Issue 399 — Tutorial · Topics: Architecture · Developer Community & Business · Objective-C & Cocoa
  **Published:** `12th April 2019`
  **NeKI brief:** Compares common iOS design-pattern trade-offs through concrete examples rather than prescribing one architecture. Use it to frame team discussions about responsibilities, coupling, and test seams in an existing app.
- [Swift by Sundell](https://www.swiftbysundell.com/podcast/45) — iOS Dev Weekly · Issue 399 — Podcast · Topics: Architecture · Developer Community & Business · Swift
  **Published:** `12th April 2019`
  **NeKI brief:** Examines Swift by Sundell, focusing on benoit pasquier talks a lot of sense in this article on app architecture. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Swinject in practice](https://felginep.github.io/2019-02-05/swinject-in-practice) — iOS Dev Weekly · Issue 390 — Article · Topics: Architecture · Dependency Injection · Developer Tools
  **Published:** `8th February 2019`
  **NeKI brief:** Examines Swinject in practice, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Dependency Injection for Testability](http://racecondition.software/blog/unit-testing) — iOS Dev Weekly · Issue 380 — Article · Topics: Architecture · Dependency Injection · Testing
  **Published:** `30th November 2018`
  **NeKI brief:** Examines Dependency Injection for Testability, offering practical guidance on test design and automation strategy. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Finally, a complete course on advanced iOS architecture](http://matteomanferdini.com/ios-architect) — iOS Dev Weekly · Issue 374 — Tutorial · Topics: Architecture · Objective-C & Cocoa · Testing
  **Published:** `19th October 2018`
  **NeKI brief:** Walks through Finally, a complete course on advanced iOS architecture with practical Apple-platform examples. Use it to understand the underlying workflow, identify assumptions and trade-offs, and adapt the ideas carefully while checking API availability and behavior against current SDK documentation.
- [Top-down iOS error architecture](https://medium.com/@londeix/top-down-error-architecture-d8715a28d1ad) — iOS Dev Weekly · Issue 338 — Article · Topics: Architecture · Objective-C & Cocoa
  **Published:** `9th February 2018`
  **NeKI brief:** Examines Top-down iOS error architecture, focusing on what’s the best way to handle non-trivial errors in an app? bartosz polaczyk argues that a system that passes the error…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current.
- [Future-Proof DI for Storyboard-Based View Controllers](http://holko.pl/2017/12/06/future-proof-dependency-injection) — iOS Dev Weekly · Issue 330 — Article · Topics: Architecture · Dependency Injection
  **Published:** `8th December 2017`
  **NeKI brief:** Explores Future-Proof DI for Storyboard-Based View Controllers in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Sourcery](https://github.com/krzysztofzablocki/Sourcery) — iOS Dev Weekly · Issue 330 — Source repository · Topics: Architecture · Dependency Injection · Developer Tools
  **Published:** `8th December 2017`
  **NeKI brief:** Sourcery parses Swift source with templates to generate repetitive implementations such as mocks, equality, or Codable support. Use it when generated boilerplate has stable conventions and the templates can be reviewed as part of source control.
- [The Truth Behind Massive View Controllers](http://aplus.rs/2017/much-ado-about-ios-app-architecture) — iOS Dev Weekly · Issue 326 — Article · Topics: Architecture · Objective-C & Cocoa
  **Published:** `10th November 2017`
  **NeKI brief:** Explores The Truth Behind Massive View Controllers in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [A State Container-based iOS Architecture](https://jobandtalent.engineering/ios-architecture-an-state-container-based-approach-4f1a9b00b82e) — iOS Dev Weekly · Issue 323 — Article · Topics: Architecture · Objective-C & Cocoa
  **Published:** `20th October 2017`
  **NeKI brief:** Explores A State Container-based iOS Architecture in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Protocols and MVVM in Swift to avoid repetition](https://sudo.isl.co/swift-mvvm-protocols) — iOS Dev Weekly · Issue 300 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `12th May 2017`
  **NeKI brief:** Explores Protocols and MVVM in Swift to avoid repetition in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Using protocol compositon for dependency injection](http://merowing.info/2017/04/using-protocol-compositon-for-dependency-injection) — iOS Dev Weekly · Issue 297 — Article · Topics: Architecture · Dependency Injection · Testing
  **Published:** `21st April 2017`
  **NeKI brief:** Explores Using protocol compositon for dependency injection in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Imagining Dependency Injection via Initializer with Storyboards](http://holko.pl/2016/12/14/storyboards-dependency-injection) — iOS Dev Weekly · Issue 281 — Article · Topics: Architecture · Dependency Injection
  **Published:** `16th December 2016`
  **NeKI brief:** Explores Imagining Dependency Injection via Initializer with Storyboards in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Perform](https://github.com/thoughtbot/Perform) — iOS Dev Weekly · Issue 267 — Source repository · Topics: Architecture · Dependency Injection · Developer Tools
  **Published:** `9th September 2016`
  **NeKI brief:** Examines Perform, focusing on chris dzombak on the difficulties of dependency injection with view controllers. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [reference implementation](https://github.com/tomkowz/NetworkLayerExample) — iOS Dev Weekly · Issue 263 — Source repository · Topics: Architecture · Core Data · Developer Tools
  **Published:** `11th August 2016`
  **NeKI brief:** Examines reference implementation, focusing on tomasz szulc on building network architecture that isn’t dependent on any third party libraries, or any apple provided…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Apple’s Bitcode Telegraphs Future CPU Plans](https://medium.com/@InertialLemon/apple-s-bitcode-telegraphs-future-cpu-plans-a7b90d326228) — iOS Dev Weekly · Issue 203 — Tutorial · Topics: Architecture · Developer Community & Business · Objective-C & Cocoa
  **Published:** `19th June 2015`
  **NeKI brief:** Explains Apple’s Bitcode Telegraphs Future CPU Plans with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Buildasaur](https://github.com/czechboy0/Buildasaur) — iOS Dev Weekly · Issue 197 — Source repository · Topics: Architecture · Developer Tools · Xcode
  **Published:** `8th May 2015`
  **NeKI brief:** Provides the Buildasaur source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Coursera iOS Software Engineer - Mountain View, CA](https://www.coursera.org/about/careers/96aecab7-9cb9-424a-b95c-002842a792e8) — iOS Dev Weekly · Issue 156 — Tutorial · Topics: Architecture · Developer Career & Practice · Developer Community & Business
  **Published:** `25th July 2014`
  **NeKI brief:** Explains Coursera iOS Software Engineer Mountain View CA with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [Using CocoaPods to Modularize an iOS App](http://dev.hubspot.com/blog/architecting-a-large-ios-app-with-cocoapods) — iOS Dev Weekly · Issue 132 — Article · Topics: Architecture · Objective-C & Cocoa · Xcode
  **Published:** `7th February 2014`
  **NeKI brief:** HubSpot describes splitting a large iOS codebase into CocoaPods modules, making dependency boundaries and incremental ownership explicit. Useful when evaluating modularization costs and build-time trade-offs.
- [Preview Apps for Lightning-Fast Iteration](https://kylebrowning.com/posts/preview-apps-for-fast-iteration) — Not only Swift · Issue 95 — Article · Topics: Architecture · Swift
  **NeKI brief:** This article covers using standalone preview apps to shorten iteration cycles. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [ScreenStateKit: Managing States for SwiftUI Screens](https://github.com/anthony1810/ScreenStateKit) — Not only Swift · Issue 95 — Source repository · Topics: Architecture · Swift · SwiftUI
  **NeKI brief:** Explains the state-ownership behavior behind ScreenStateKit: Managing States for SwiftUI Screens. Use it to distinguish initialization, bindings, and view identity so updates remain predictable across SwiftUI recomputation and navigation.
- [Writing good agents.md files](https://www.philschmid.de/writing-good-agents) — Not only Swift · Issue 95 — Article · Topics: Architecture · Code Quality · Objective-C & Cocoa
  **NeKI brief:** This article covers writing effective AGENTS.md instruction files. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [PiSwift](https://github.com/xibbon/PiSwift) — Not only Swift · Issue 94 — Source repository · Topics: Architecture · Objective-C & Cocoa · Swift
  **NeKI brief:** This source repository covers the PiSwift project and its Swift integration surface. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Using Model Context Protocol in iOS apps](https://www.artemnovichkov.com/blog/using-model-context-protocol-in-ios-apps) — Not only Swift · Issue 81 — Article · Topics: AI Development · Architecture · Dependency Injection
  **NeKI brief:** Explores using Model Context Protocol from an iOS app. Follow it when assessing tool or resource integrations, keeping transport, trust, privacy, and user-consent boundaries explicit before exposing app data to external agents.
- [Resolver](https://github.com/hmlongco/Resolver) — Not only Swift · Issue 77 — Source repository · Topics: Architecture · Swift · SwiftUI
  **NeKI brief:** This source repository covers Resolver's dependency-injection approach and its deprecated status. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Navigator: Advanced Navigation Support for SwiftUI.](https://github.com/hmlongco/Navigator) — Not only Swift · Issue 77 — Source repository · Topics: Architecture · Swift · SwiftUI
  **NeKI brief:** Navigator provides a SwiftUI navigation abstraction centered on route-driven presentation. Use it to compare centralized routing decisions with native NavigationStack state when complex flows need testable deep-link handling.
