# Dependency Injection

Third-party reading leads collected from NeKI sources. The links may be useful perspectives, but are not vetted recommendations or authoritative API guidance. NeKI publishes routing metadata, not the linked articles' text.

**Scope:** Dependency injection, test seams, service composition, and dependency management.

- Last collected: `2026-07-22T21:56:49Z`
- Indexed links shown: **162**

## Direct-source reading

- [CocoaPods Tutorial for Swift: Getting Started | Kodeco](https://www.kodeco.com/7076593-cocoapods-tutorial-for-swift-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The CocoaPods guide explains dependency installation, Podfiles and integration into Swift projects. Use it to understand the generated workspace and build-setting consequences when maintaining legacy dependencies alongside Swift Package Manager.
- [Scripting in Swift: Managing Dependencies | Kodeco](https://www.kodeco.com/4979-scripting-in-swift-managing-dependencies) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Manages dependencies for Swift scripts rather than copying supporting code into one file. Useful for keeping automation maintainable when a script begins to rely on external packages.
- [Getting Started with iOS App Observability | Kodeco](https://www.kodeco.com/49535198-getting-started-with-ios-app-observability) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Despite its misleading catalogue title, the saved page describes Foundation Models integration with structured generation and OpenTelemetry setup. Use it to separate model-feature instrumentation from generic app observability before relying on the tutorial.
- [Moving From Cocoapods to Swift Package Manager | Kodeco](https://www.kodeco.com/3949145-moving-from-cocoapods-to-swift-package-manager) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Migrates dependencies from CocoaPods to Swift Package Manager and addresses project integration changes. Useful for planning the boundary between package declaration, Xcode project settings, and reproducible dependency resolution.
- [Resolver for iOS Dependency Injection: Getting Started | Kodeco](https://www.kodeco.com/22203552-resolver-for-ios-dependency-injection-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Refactors tightly coupled types with Resolver registrations, scopes, argument injection, protocol bindings, and mock containers. Useful for evaluating a service locator-style DI library against explicit injection, particularly where tests require isolated object graphs.
- [An Introduction to Swift Package Manager | Kodeco](https://www.kodeco.com/1993018-an-introduction-to-swift-package-manager) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Swift Package Manager is introduced through a small Swift project and dependency workflow. It is useful for understanding package manifests, targets and products before modularizing an app or migrating away from older dependency managers.
- [Swinject Tutorial for iOS: Getting Started | Kodeco](https://www.kodeco.com/17-swinject-tutorial-for-ios-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Introduces Swinject dependency registration and resolution. Useful for comparing a container-managed object graph with explicit constructor injection in an iOS application.
- [Dependency Injection Tutorial for iOS: Getting Started | Kodeco](https://www.kodeco.com/14223279-dependency-injection-tutorial-for-ios-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Dependency injection is applied to a SwiftUI profile flow so services can be replaced and tested. Follow it to see constructor and environment trade-offs, particularly how much global convenience is acceptable before dependencies become implicit.
- [“Trait-ifying” our libraries to reduce transitive dependencies](https://www.pointfree.co/blog/posts/216-trait-ifying-our-libraries-to-reduce-transitive-dependencies) — Point-Free · article catalogue
  **Published:** `2026-06-24T00:00:00Z`
  **NeKI brief:** Applies SwiftPM traits to make optional library features opt-in, using SwiftNavigation as the test case. Follow it when reducing transitive dependencies while weighing package configuration complexity against smaller builds.
- [Introducing @DependencyEntry](https://www.pointfree.co/blog/posts/213-introducing-dependencyentry) — Point-Free · article catalogue
  **Published:** `2026-06-17T00:00:00Z`
  **NeKI brief:** Presents @DependencyEntry as a macro for registering dependencies while supporting live, preview, and test values. The design shows how generated declarations can keep dependency setup concise without losing explicit override points.
- [AI App Development: What I Learned in One Month - SwiftLee](https://www.avanderlee.com/ai-development/ai-app-development-what-i-learned-in-one-month) — Antoine van der Lee articles · article catalogue
  **Published:** `2026-01-25T23:55:00+00:00`
  **NeKI brief:** Reflects on building and shipping an app with AI over a month, separating rapid scaffolding from decisions still requiring human product and engineering judgment. It offers practical signals for evaluating where agent speed creates later maintenance cost.
- [Building for Love: Creating Authentic Connections](https://www.createwithswift.com/building-for-love-creating-authentic-connections) — Create with Swift · article catalogue
  **Published:** `2025-10-10T13:00:41.000Z`
  **NeKI brief:** Discusses product design that builds authentic connections by focusing on user emotions and intentional choices. Use it when evaluating whether an experience communicates purpose and trust rather than optimizing only for engagement.
- [Experience the Charm of Swift - One-Click DataFrame Export](https://fatbobman.com/en/posts/experience-the-charm-of-swift-one-click-export-dataframe) — Fatbobman · article catalogue
  **Published:** `2025-05-21T14:00:00.000Z`
  **NeKI brief:** The DataFrame export example shows Swift tabular data moving into a one-click file workflow, connecting typed values with user-facing document output. Follow it when evaluating ergonomics and format boundaries in data-heavy tools.
- [Dependency container on top of task local values in Swift | Swift with Majid](https://swiftwithmajid.com/2025/04/30/dependency-container-on-top-of-task-local-values-in-swift) — Swift with Majid · article catalogue
  **Published:** `2025-04-30T00:00:00+00:00`
  **NeKI brief:** Builds a dependency container using TaskLocal values. Use it when async call chains need contextual dependencies without passing parameters everywhere, while guarding scope and inheritance carefully.
- [SwiftUI Environment - @Environment, EnvironmentObject, Custom Values](https://fatbobman.com/en/posts/swiftui-environment-concepts-and-practice) — Fatbobman · article catalogue
  **Published:** `2025-03-26T14:12:00.000Z`
  **NeKI brief:** Explains SwiftUI Environment as dependency propagation and value lookup. Use it when shared configuration or services need scoped injection without threading parameters through every intermediate view.
- [Mocking a network connection in your Swift Tests – Donny Wals](https://www.donnywals.com/mocking-a-network-connection-in-your-swift-tests) — Donny Wals · article catalogue
  **Published:** `2024-12-12T09:56:48+00:00`
  **NeKI brief:** Injecting a controllable network connection keeps Swift tests deterministic and offline, letting failures assert request and response behavior without relying on a live server.
- [What is dependency injection in Swift? – Donny Wals](https://www.donnywals.com/what-is-dependency-injection-in-swift) — Donny Wals · article catalogue
  **Published:** `2024-10-11T07:37:29+00:00`
  **NeKI brief:** Dependency injection moves construction decisions out of business logic, enabling deterministic fakes and environment-specific services while adding initializer or container wiring.
- [JSON Parsing in Swift explained with code examples - SwiftLee](https://www.avanderlee.com/swift/json-parsing-decoding) — Antoine van der Lee articles · article catalogue
  **Published:** `2024-08-19T11:58:35+00:00`
  **NeKI brief:** Demonstrates Codable-based JSON decoding, nested models, custom keys, dates, and error diagnosis. The examples provide a dependency-free baseline and show where custom decoding is preferable to weakening model types.
- [Swift Testing Bonanza](https://www.pointfree.co/blog/posts/148-swift-testing-bonanza) — Point-Free · article catalogue
  **Published:** `2024-07-24T00:00:00Z`
  **NeKI brief:** Surveys Swift Testing techniques used in Point-Free projects, including traits, parameterization, and dependency control. It provides concrete test-design patterns for keeping asynchronous feature tests deterministic and readable.
- [Swift Package Manager framework creation in Xcode - SwiftLee](https://www.avanderlee.com/swift/creating-swift-package-manager-framework) — Antoine van der Lee articles · article catalogue
  **Published:** `2024-06-04T08:10:16+00:00`
  **NeKI brief:** Creates a Swift package in Xcode and covers Package.swift configuration, platform requirements, dependencies, and local development-package workflows.
- [Building an app in the Composable Architecture, from scratch](https://www.pointfree.co/blog/posts/138-building-an-app-in-the-composable-architecture-from-scratch) — Point-Free · article catalogue
  **Published:** `2024-05-09T00:00:00Z`
  **NeKI brief:** Building a feature from scratch in the Composable Architecture makes state, actions, reducer logic, and effects visible in sequence. The workflow is useful for tracing where domain decisions belong before adding navigation or persistence.
- [Using @Environment in SwiftUI to link Swift Package dependencies - SwiftLee](https://www.avanderlee.com/swiftui/environment-property-wrapper) — Antoine van der Lee articles · article catalogue
  **Published:** `2024-04-23T11:23:35+00:00`
  **NeKI brief:** Shows injecting shared values through SwiftUI's Environment, including defining custom EnvironmentKey values in a Swift package. Useful for keeping package views configurable without hard-coding app-level dependencies.
- [Using closures for dependencies instead of protocols – Donny Wals](https://www.donnywals.com/using-closures-for-dependencies-instead-of-protocols) — Donny Wals · article catalogue
  **Published:** `2024-04-02T11:46:02+00:00`
  **NeKI brief:** Closure-based dependencies expose only the operations a caller needs, reducing protocol scaffolding; the trade-off is weaker discoverability when a dependency grows beyond a few behaviors.
- [Async Unit Testing: The Comprehensive Guide](https://blog.jacobstechtavern.com/p/async-unit-testing-in-swift-the-comprehensive) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2024-03-11T17:15:13.685Z`
  **NeKI brief:** Builds asynchronous unit testing from dependency injection and controllable test doubles through async/await, unstructured tasks, and Combine interoperation. Use the staged examples to reason about deterministic setup, cancellation, and ownership of asynchronous work.
- [Macro Bonanza: Dependencies](https://www.pointfree.co/blog/posts/120-macro-bonanza-dependencies) — Point-Free · article catalogue
  **Published:** `2023-11-16T00:00:00Z`
  **NeKI brief:** A dependency macro can synthesize environment plumbing while keeping live and test implementations interchangeable. The pattern reduces manual injection code, but generated behavior still needs inspection when compiler or macro expansion changes.
- [Masking Third Party Dependencies | Swiftjective-C](https://swiftjectivec.com/Masking-Third-Party-Dependencies-Swift) — Swiftjective-C · article catalogue
  **Published:** `2023-10-17T00:00:00-05:00`
  **NeKI brief:** Masking a third-party dependency behind an app-owned interface limits vendor leakage, making replacement and test fakes possible at the cost of adapter maintenance.
- [Dependency Injection Demystified](https://blog.jacobstechtavern.com/p/async-testing-masterclass-1-dependency) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2023-06-06T18:01:07.294Z`
  **NeKI brief:** Explains dependency injection as a testability boundary for asynchronous Swift code. Follow it to separate side effects from assertions and to make async tests deterministic without relying on production services.
- [On Apple’s Guidance for StateObject Initialization | Swiftjective-C](https://swiftjectivec.com/Dependency-Injection-with-State-Object-SwiftUI) — Swiftjective-C · article catalogue
  **Published:** `2023-04-20T00:00:00-05:00`
  **NeKI brief:** Initializes a StateObject with injected dependencies, preserving ownership semantics while making previews and tests deterministic without hidden global services.
- [Safely pinning SPM dependencies to exact versions](https://www.polpiella.dev/safely-pinning-spm-depedencies-to-exact-versions) — Pol Piella · article catalogue
  **Published:** `2023-02-15T00:00:00.000Z`
  **NeKI brief:** Exact Swift Package dependency pins make builds reproducible and reviewable. The article is useful for weighing update control against security freshness, especially when lockfile changes need deliberate dependency review.
- [Adding and Removing Swift Package dependencies in Xcode | Sarunw](https://sarunw.com/posts/managing-swift-package-in-xcode) — Sarunw · article catalogue
  **Published:** `2023-02-02`
  **NeKI brief:** Adds and removes Swift Package dependencies in Xcode, emphasizing package identity and target linkage so dependency changes remain reviewable.
- [Modern SwiftUI](https://www.pointfree.co/blog/posts/99-modern-swiftui) — Point-Free · article catalogue
  **Published:** `2023-01-27T00:00:00Z`
  **NeKI brief:** Presents a modern SwiftUI architecture built around state, bindings, and composition rather than imperative view controllers. Useful as a conceptual reference when simplifying older SwiftUI code.
- [Modern SwiftUI: Dependencies](https://www.pointfree.co/blog/posts/97-modern-swiftui-dependencies) — Point-Free · article catalogue
  **Published:** `2023-01-26T00:00:00Z`
  **NeKI brief:** Modern SwiftUI dependency design keeps feature code independent from live services and makes previews and tests deterministic. The trade-off is explicit dependency plumbing instead of convenient global access.
- [A new library to control dependencies and avoid letting them control you](https://www.pointfree.co/blog/posts/92-a-new-library-to-control-dependencies-and-avoid-letting-them-control-you) — Point-Free · article catalogue
  **Published:** `2023-01-09T00:00:00Z`
  **NeKI brief:** Introduces Swift Dependencies, extracted from the Composable Architecture, to make feature dependencies explicit and replaceable. Follow it when designing testable Swift code and weighing controlled dependency injection against hidden global or live-service access.
- [Dependency Injection with @State Variables | Swiftjective-C](https://swiftjectivec.com/SwiftUI-State-Dependency-Injection) — Swiftjective-C · article catalogue
  **Published:** `2022-09-14T00:00:00-05:00`
  **NeKI brief:** Injecting state dependencies into SwiftUI requires explicit ownership boundaries, avoiding accidental reinitialization when a view's body recomputes and a parent rebuilds its hierarchy.
- [Introducing XCTUnimplemented](https://www.pointfree.co/blog/posts/77-introducing-xctunimplemented) — Point-Free · article catalogue
  **Published:** `2022-06-29T05:00:00Z`
  **NeKI brief:** XCTUnimplemented creates test-only dependency implementations that fail on unexpected endpoint use, while explicit placeholders cover required return values. Use it to prove side effects stay absent unless a test deliberately configures them.
- [Microapps architecture in Swift. Dependency Injection. | Swift with Majid](https://swiftwithmajid.com/2022/02/02/microapps-architecture-in-swift-dependency-injection) — Swift with Majid · article catalogue
  **Published:** `2022-02-02T00:00:00+00:00`
  **NeKI brief:** Uses dependency injection between Swift package modules to keep microapp features independently testable. Explicit composition at the boundary avoids hidden globals, though the root assembly becomes responsible for wiring all capabilities.
- [@EnvironmentObject explained for sharing data between views in SwiftUI](https://www.avanderlee.com/swiftui/environmentobject) — Antoine van der Lee articles · article catalogue
  **Published:** `2022-02-01T08:53:05+00:00`
  **NeKI brief:** Demonstrates injecting an ObservableObject through SwiftUI's environment and reading it in descendants without forwarding properties through every initializer. It also highlights the runtime failure when a required object is missing.
- [Adding custom keys to the SwiftUI environment – Donny Wals](https://www.donnywals.com/adding-custom-keys-to-the-swiftui-environment) — Donny Wals · article catalogue
  **Published:** `2022-01-10T06:30:47+00:00`
  **NeKI brief:** Custom environment keys inject shared view dependencies without parameter threading, but defaults and overrides must make missing configuration observable in tests.
- [Lightweight dependency injection and unit testing using async functions | Swift by Sundell](https://www.swiftbysundell.com/articles/dependency-injection-and-unit-testing-using-async-await) — Swift by Sundell · article catalogue
  **Published:** `2021-12-09`
  **NeKI brief:** Builds lightweight async tests by injecting a networking dependency and replacing it with protocol-based mocks. The pattern keeps asynchronous production code intact while making response timing and failure paths deterministic enough to test.
- [What do @main, @UIApplicationMain, and @NSApplicationMain mean | Sarunw](https://sarunw.com/posts/what-do-main-uiapplicationmain-nsapplicationmain-mean) — Sarunw · article catalogue
  **Published:** `2021-11-22`
  **NeKI brief:** Explains how Swift's @main and the older UIApplicationMain or NSApplicationMain attributes establish an app entry point, clarifying the migration from generated main functions.
- [Combined Swift packages | Swift by Sundell](https://www.swiftbysundell.com/tips/swift-packages-containing-both-a-command-line-tool-and-a-library) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Combines a command-line tool and library in one Swift package, separating executable and library targets while sharing source infrastructure.
- [Quickly replacing singletons with functions | Swift by Sundell](https://www.swiftbysundell.com/tips/quickly-replacing-singletons-with-functions) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Replaces singleton lookups with functions that return dependencies, creating a lightweight seam for tests and future configuration. The approach improves call-site control without forcing a large container, but shared lifetime must be decided explicitly.
- [Passing self to required Objective-C dependencies | Swift by Sundell](https://www.swiftbysundell.com/tips/passing-self-to-required-objective-c-dependencies) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Shows passing self to Objective-C APIs that require a delegate or callback dependency, while considering initialization timing. Ensure the object is fully initialized before registration to avoid observing partial state.
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
- [A guide to the SwiftUI layout system - Part 2 | Swift by Sundell](https://www.swiftbysundell.com/articles/swiftui-layout-system-guide-part-2) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Explains intermediate SwiftUI layout mechanics and how parent proposals affect child size. Understanding proposal flow prevents incorrect frame modifiers used as compensating fixes.
- [Swift playgrounds tips and tricks | Swift by Sundell](https://www.swiftbysundell.com/articles/swift-playgrounds-tips-tricks) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Uses Swift playgrounds for small experiments, visual output, and API exploration without an app target. Playgrounds shorten feedback loops, while project integration and concurrency behavior still need real-target verification.
- [Static factory methods in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/static-factory-methods-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Uses static factory methods to name construction intent and centralize configured defaults. Factories are most useful when creation validates or selects variants beyond a plain initializer.
- [Simple Swift dependency injection with functions | Swift by Sundell](https://www.swiftbysundell.com/articles/simple-swift-dependency-injection-with-functions) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Uses functions as simple dependency-injection seams for operations such as loading or formatting. This keeps tests lightweight, while larger dependency groups may need a dedicated value type.
- [Refactoring Swift code for testability | Swift by Sundell](https://www.swiftbysundell.com/articles/refactoring-swift-code-for-testability) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Refactors code toward injectable dependencies and explicit inputs so behavior can be tested in isolation. Preserve observable behavior during extraction and avoid introducing abstractions that only serve mock mechanics.
- [Managing dependencies using the Swift Package Manager | Swift by Sundell](https://www.swiftbysundell.com/articles/managing-dependencies-using-the-swift-package-manager) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Uses Swift Package Manager to declare and resolve dependencies through manifests and version requirements. Pinning and update policy should balance reproducibility, security, and maintenance.
- [Different flavors of dependency injection in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/different-flavors-of-dependency-injection-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Compares initializer, property, function, and environment-style dependency injection. Match the form to lifetime and requiredness, keeping production wiring explicit and test replacements local.
- [Dependency injection using factories in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/dependency-injection-using-factories-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Factories can assemble dependencies near their creation site and avoid giant initializers while preserving test substitution. Give each factory a narrow product responsibility; a global container merely relocates hidden dependency coupling unless its ownership is explicit.
- [Defining testing data in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/defining-testing-data-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Separate test input construction from verification and define reusable stubs for values that are irrelevant to each assertion. Focused fixture builders reduce duplication, while explicit expected output keeps tests readable when models gain new fields.
- [Default arguments in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/default-arguments-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Uses default arguments to express common API configuration without overload proliferation. Defaults should be stable and unsurprising; required semantic choices deserve explicit parameters.
- [Code encapsulation in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/code-encapsulation-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Encapsulates Swift implementation details behind narrow APIs so callers depend on stable behavior rather than storage. Good boundaries make invariants enforceable and refactoring less risky.
- [Building a command line tool using the Swift Package Manager | Swift by Sundell](https://www.swiftbysundell.com/articles/building-a-command-line-tool-using-the-swift-package-manager) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Structure a Swift command-line tool as an executable target plus reusable library code, then define the entry point, arguments, dependencies, and installation path through Swift Package Manager. This separation keeps command parsing from consuming application logic.
- [Avoiding singletons in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/avoiding-singletons-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Replace global singletons with injected services whose dependencies and lifetime are visible to callers. This makes tests substitute behavior directly and prevents unrelated features from sharing mutable global state through an apparently convenient API.
- [Dependency Injection in Swift using latest Swift features - SwiftLee](https://www.avanderlee.com/swift/dependency-injection) — Antoine van der Lee articles · article catalogue
  **Published:** `2021-07-20T09:49:01+00:00`
  **NeKI brief:** Builds dependency injection with protocols and initializer defaults, then substitutes test doubles. The design separates construction from behavior while preserving convenient production call sites.
- [Testing dates consistently](https://www.polpiella.dev/testing-dates-consistently) — Pol Piella · article catalogue
  **Published:** `2021-07-02T00:00:00.000Z`
  **NeKI brief:** Date tests become deterministic by controlling clocks, calendars and time zones instead of comparing wall-clock values. The article is useful for eliminating locale-dependent failures from serialization and scheduling tests.
- [App Launch Time: 7 tips to increase performance - SwiftLee](https://www.avanderlee.com/optimization/launch-time-performance-optimization) — Antoine van der Lee articles · article catalogue
  **Published:** `2020-12-01T08:00:00+00:00`
  **NeKI brief:** Breaks launch latency into loading, initialization, and first-frame work, then prioritizes reductions with profiling. The tips focus on moving or deferring nonessential startup tasks.
- [Adding a closure as a target to UIButton and other controls in Swift](https://www.avanderlee.com/swift/uibutton-uicontrol-closure-target) — Antoine van der Lee articles · article catalogue
  **Published:** `2020-08-05T17:15:14+00:00`
  **NeKI brief:** Builds a closure-based UIControl target helper that stores callbacks and forwards events without selectors. The implementation must retain the target for the control's lifetime.
- [Single Source of Truth in SwiftUI - Is ObservableObject Enough?](https://fatbobman.com/en/posts/observableobject-study) — Fatbobman · article catalogue
  **Published:** `2020-05-17T04:00:00.000Z`
  **NeKI brief:** ObservableObject supports reference-type state propagation, but it does not automatically make a data graph a single source of truth. Inject it at a deliberate boundary and minimize dependent views so object-change notifications do not redraw unrelated interface regions.
- [Testing private methods and variables in Swift - SwiftLee](https://www.avanderlee.com/swift/testing-private-methods-variables) — Antoine van der Lee articles · article catalogue
  **Published:** `2020-03-17T08:00:00+00:00`
  **NeKI brief:** Argues for testing private behavior through public outcomes, while presenting limited access techniques when a seam is unavoidable. This avoids freezing implementation details in tests.
- [Removing Dependencies · objc.io](https://www.objc.io/blog/2019/08/06/removing-dependencies) — objc.io · article catalogue
  **Published:** `2019-8-6`
  **NeKI brief:** Removing dependencies from a Swift module starts by identifying which abstractions actually cross its boundary, then replacing incidental imports with narrower interfaces. The article frames compile-time isolation as a deliberate architecture trade-off, not a blanket ban on libraries.
- [Dependency injection with Storyboards and Xcode 11 – Donny Wals](https://www.donnywals.com/dependency-injection-with-storyboards-and-xcode-11) — Donny Wals · article catalogue
  **Published:** `2019-12-23T08:00:51+00:00`
  **NeKI brief:** Storyboard dependency injection uses scene creation and preparation hooks to supply collaborators, avoiding hidden service lookups in view-controller lifecycle code.
- [Asynchronous operations for writing concurrent solutions in Swift - SwiftLee](https://www.avanderlee.com/swift/asynchronous-operations) — Antoine van der Lee articles · article catalogue
  **Published:** `2019-12-03T09:14:06+00:00`
  **NeKI brief:** Builds an asynchronous Operation by managing executing and finished KVO states around callback completion. Correct transitions let OperationQueue schedule dependencies and recognize completion.
- [Getting started with Operations and OperationQueues in Swift - SwiftLee](https://www.avanderlee.com/swift/operations) — Antoine van der Lee articles · article catalogue
  **Published:** `2019-11-26T13:00:46+00:00`
  **NeKI brief:** Introduces Operation and OperationQueue for cancellable, dependency-aware units of work, contrasting them with raw GCD blocks. Examples show lifecycle hooks for composable tasks.
- [Cleaning up your dependencies with protocols – Donny Wals](https://www.donnywals.com/cleaning-up-your-dependencies-with-protocols) — Donny Wals · article catalogue
  **Published:** `2019-09-09T14:04:19+00:00`
  **NeKI brief:** Protocols define narrow dependency contracts for injection and fakes, though overly broad abstractions can hide concrete behavior rather than improve testability.
- [Better dependency injection for Storyboards in iOS13 | Sarunw](https://sarunw.com/posts/better-dependency-injection-for-storyboards-in-ios13) — Sarunw · article catalogue
  **Published:** `2019-07-12`
  **NeKI brief:** Inject storyboard dependencies through @IBSegueAction during controller initialization instead of exposing mutable properties for post-instantiation setup. This makes required collaborators explicit before the destination loads and prevents a storyboard flow from reaching an incompletely configured controller.
- [Swift 5.0: How to migrate your project and frameworks - SwiftLee](https://www.avanderlee.com/swift/updating-swift-5) — Antoine van der Lee articles · article catalogue
  **Published:** `2019-04-02T07:00:10+00:00`
  **NeKI brief:** Outlines a Swift 5 migration pass covering the migration assistant, dependencies, CI images, Result adoption, and ABI-stability implications. Useful for planning project-wide upgrade work beyond merely changing the compiler version.
- [Dependency Injection in Swift with Protocols | Swift with Majid](https://swiftwithmajid.com/2019/03/06/dependency-injection-in-swift-with-protocols) — Swift with Majid · article catalogue
  **Published:** `2019-03-06T00:00:00+00:00`
  **NeKI brief:** Protocol-based injection replaces concrete services with test doubles at construction boundaries. The guide is useful for making dependencies visible and testable without introducing a service locator that hides ownership.
- [Hiding third-party dependencies with protocols and extensions | Swift with Majid](https://swiftwithmajid.com/2019/02/13/hiding-third-party-dependencies-with-protocols-and-extensions) — Swift with Majid · article catalogue
  **Published:** `2019-02-13T00:00:00+00:00`
  **NeKI brief:** Protocols and extensions hide third-party APIs behind app-owned abstractions. Follow it to limit vendor coupling and simplify tests, while avoiding abstractions that merely mirror every external method.
- [How to Control the World](https://www.pointfree.co/blog/posts/21-how-to-control-the-world) — Point-Free · article catalogue
  **Published:** `2018-10-09T14:00:00Z`
  **NeKI brief:** Controlling dependencies through explicit environment values makes effects replaceable in tests and previews. The functional approach avoids hidden globals, but requires deliberate propagation of the dependency context.
- [Injecting side effects into chained Sequence operations – Ole Begemann](https://oleb.net/blog/2017/10/chained-foreach) — Ole Begemann · article catalogue
  **Published:** `2017-10-30T21:05:00Z`
  **NeKI brief:** Examines injecting forEach into chained Swift collection operations and the readability or side-effect trade-offs involved. Follow it when keeping transformations expressive without hiding mutation inside fluent pipelines.
- [Using 'swift package fetch' in an Xcode project | Cocoa with Love](https://www.cocoawithlove.com/blog/package-manager-fetch.html) — Cocoa with Love · article catalogue
  **Published:** `2017-01-30`
  **NeKI brief:** Explains wiring Swift Package Manager dependency fetching into an Xcode build before native integration existed, exposing the build-phase and dependency-ordering concerns involved. Follow it for historical build-system trade-offs and CI diagnosis.
- [Testing actions over time | Cocoa with Love](https://www.cocoawithlove.com/blog/testing-actions-over-time.html) — Cocoa with Love · article catalogue
  **Published:** `2016-10-25`
  **NeKI brief:** A debug context coordinator replaces wall-clock scheduling with simulated time, making ordering and execution-context assertions deterministic at the cost of testing through a scheduler abstraction.
- [Putting the Physics Into Measurements and Units – Ole Begemann](https://oleb.net/blog/2016/07/unitproduct) — Ole Begemann · article catalogue
  **Published:** `2016-07-29T14:25:00Z`
  **NeKI brief:** Multiplying typed quantities needs a representation for compound units, otherwise arithmetic loses dimensional meaning. The article develops that type-level composition and its trade-off against Foundation's runtime conversion model.
- [Creating a CocoaPod](https://useyourloaf.com/blog/creating-a-cocoapod) — Use Your Loaf · article catalogue
  **Published:** `2014-08-13T21:00:48+01:00`
  **NeKI brief:** Explains creating a CocoaPod as historical package-distribution context. Public packaging requires a stable API, tests, and versioning discipline; modern distribution choices should be checked against current tooling.
- [NSOperation - NSHipster](https://nshipster.com/nsoperation) — NSHipster · article catalogue
  **Published:** `2014-07-14T00:00:00-07:00`
  **NeKI brief:** Operation models a cancellable unit of work with dependencies and execution state. Use it when scheduling needs more structure than a queue closure, implementing KVO-compliant state transitions correctly for asynchronous subclasses.
- [UIApplicationDelegate launchOptions - NSHipster](https://nshipster.com/launch-options) — NSHipster · article catalogue
  **Published:** `2013-12-16T00:00:00-08:00`
  **NeKI brief:** Application launch options expose the cause of an iOS app startup, such as a notification or URL. The guide is useful for routing at the lifecycle boundary before scene-based APIs take over navigation responsibility.
- [DRYing your instance variables](https://useyourloaf.com/blog/drying-your-instance-variables) — Use Your Loaf · article catalogue
  **Published:** `2011-02-13T19:27:00+00:00`
  **NeKI brief:** Reduces duplicate instance-variable handling through shared initialization or abstractions. DRY refactors should retain clear ownership rather than merge unrelated state merely because it is repeated.
- [Delegation or Notification](https://useyourloaf.com/blog/delegation-or-notification) — Use Your Loaf · article catalogue
  **Published:** `2010-06-06T22:19:00+00:00`
  **NeKI brief:** Use delegation for a focused one-to-one behavior contract and notifications for broader, decoupled event fan-out. The right choice depends on ownership and response expectations; notifications avoid direct dependencies but can make event flow less discoverable.
- [Automatically Running Unit Tests](https://useyourloaf.com/blog/automatically-running-unit-tests) — Use Your Loaf · article catalogue
  **Published:** `2010-05-31T20:41:00+00:00`
  **NeKI brief:** Make a unit-test target depend on the application target so normal builds execute tests automatically. This shortens feedback loops, but retain a dedicated CI test command as the authoritative check because build-triggered tests can be skipped by configuration.
- [Unit Testing with OCUnit](https://useyourloaf.com/blog/unit-testing-with-ocunit) — Use Your Loaf · article catalogue
  **Published:** `2010-05-26T21:33:00+00:00`
  **NeKI brief:** Shows setting up legacy OCUnit model tests inside Xcode and explains why starting with non-UI code reduces harness complexity. Use it for historical XCTest migration context, replacing obsolete SenTestCase APIs today.
- [Singletons, AppDelegates and top-level data. | Cocoa with Love](https://www.cocoawithlove.com/2008/11/singletons-appdelegates-and-top-level.html) — Cocoa with Love · article catalogue
  **Published:** `2008-11-16`
  **NeKI brief:** Singletons and app delegates centralize process-wide state but can obscure dependencies and test setup. The discussion helps decide which responsibilities are truly global and which should be injected explicitly.
- [Adapter interfaces in Objective-C, using categories. | Cocoa with Love](https://www.cocoawithlove.com/2008/05/adapter-interfaces-in-objective-c-using.html) — Cocoa with Love · article catalogue
  **Published:** `2008-05-24`
  **NeKI brief:** Objective-C categories can provide an adapter interface that lets two classes collaborate without mutual implementation dependencies. The pattern narrows coupling at the API boundary, but method-name collisions and undiscoverable category behavior require disciplined naming.
- [Switching Swift Package Manager dependencies between versioned and local development](https://tanaschita.com/spm-quick-tip-on-switching-to-local-dev) — Tanaschita · article catalogue
  **NeKI brief:** Shows how to switch a Swift Package dependency between a versioned remote requirement and a local checkout during development. Use it to test package changes quickly while preserving a clean, reproducible dependency declaration for collaborators and CI.
- [How to add public libraries as Swift Packages to an iOS project](https://tanaschita.com/spm-add-public-packages) — Tanaschita · article catalogue
  **NeKI brief:** Adding a remote Swift package through Xcode covers version requirements and dependency updates. The guide is useful for reviewing reproducibility and supply-chain boundaries before accepting a package into an app target.
- [How to add local Swift Packages to an iOS project](https://tanaschita.com/spm-add-local-packages) — Tanaschita · article catalogue
  **NeKI brief:** Local Swift packages provide a modular dependency boundary during development. Follow it to iterate on shared code without publishing, while keeping target membership and resource ownership explicit.
- [Building a dependency injection framework](https://tanaschita.com/dependency-injection-building-lightweight-container) — Tanaschita · article catalogue
  **NeKI brief:** Builds a lightweight dependency-injection container in Swift and discusses registration and resolution. Use it to evaluate a small explicit composition mechanism for app services, especially when replacing hidden singletons without introducing a framework-sized abstraction.
- [SwiftUI, Combine, and Firebase](https://peterfriese.dev/blog/2020/replicating-reminder-swiftui-firebase-part1) — Peter Friese articles · article catalogue
  **NeKI brief:** Combining SwiftUI, Combine, and Firebase requires keeping publishers for remote state separate from view-local mutations. The sample's layering makes asynchronous updates observable while retaining a clear place for authentication and persistence policy.
- [On third-party code and security concerns for iOS](https://martiancraft.com/blog/2024/07/security-concerns-for-ios) — MartianCraft · article catalogue
  **NeKI brief:** Uses a CocoaPods compromise to frame dependency security as a supply-chain responsibility, covering review, provenance, and update choices. Follow it when auditing third-party code rather than treating package managers as a security boundary.
- [Developer Lingo Every iOS Project Manager Should Know](https://martiancraft.com/blog/2020/04/dev-lingo) — MartianCraft · article catalogue
  **NeKI brief:** Shared terminology around builds, releases, APIs, and bugs reduces translation loss between project managers and iOS engineers. The glossary is useful for establishing a precise delivery vocabulary before planning work.
- [Analyzing Third Party Libraries](https://martiancraft.com/blog/2017/04/analyzing-third-party-libraries) — MartianCraft · article catalogue
  **NeKI brief:** Evaluate third-party libraries against a build-versus-adopt baseline: identify capability gained, maintenance and replacement cost, platform-update lag, bug ownership, and exit path. Accept a dependency only when its concrete benefit outweighs the technical debt and integration lock-in.
- [My Core Data Stack](https://martiancraft.com/blog/2015/03/core-data-stack) — MartianCraft · article catalogue
  **NeKI brief:** A production-oriented Core Data stack walkthrough covering setup, contexts, and persistence boundaries. Use it to compare lifecycle and concurrency choices before adopting a shared storage layer.
- [Integrating Dependencies into LLM-Assisted Projects — Chris Eidhof](https://chris.eidhof.nl/post/integrating-dependencies-into-llm-assistant-projects) — Chris Eidhof · article catalogue
  **NeKI brief:** Discusses vendoring dependency source into an LLM-assisted codebase so the agent can inspect and adapt it as part of the project. It is useful for evaluating agent visibility and maintenance trade-offs, with licensing and update costs considered separately.
- [Dependencies — Chris Eidhof](https://chris.eidhof.nl/post/fewer-dependencies) — Chris Eidhof · article catalogue
  **NeKI brief:** Explains why the author moved toward fewer third-party dependencies, emphasizing complexity, control, and long-term maintenance. Use it to evaluate dependency trade-offs rather than as an argument to avoid libraries categorically.
- [Weeknotes № 21 — Chris Eidhof](https://chris.eidhof.nl/post/2023-21) — Chris Eidhof · article catalogue
  **NeKI brief:** A development weeknote about recreating Git's core read-only data structures in Swift and then experimenting with writing them. Useful as an approachable pointer to Git's underlying object model.

## Newsletter and related leads

- [MockingKit](https://github.com/danielsaidi/MockingKit) — iOS Dev Tools · iOS Dev Tools: TourKit, MockingKit, MemoryMap — Source repository · Topics: Dependency Injection · Developer Tools · Swift
  **Published:** `2026-07-09T16:30:20.398Z`
  **NeKI brief:** MockingKit generates or supplies mock implementations for Swift protocols and classes, reducing hand-written test doubles. Useful for isolating collaborators while comparing generated convenience against explicit, behavior-focused test seams.
- [Production SwiftUI: Scalable Networking Architecture With Async/Await And Generics](https://www.youtube.com/watch?v=M5ZUGBeugP4) — Those Who Swift · Issue 266 — Video · Topics: Architecture · Concurrency · Networking
  **Published:** `2026-05-13`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Modularizing Swift Apps with Swift Package Manager](https://kylebrowning.com/posts/modularizing-swift-apps-with-spm) — Those Who Swift · Issue 256 — Article · Topics: Architecture · Swift · Swift Package Manager
  **Published:** `2026-03-06`
  **NeKI brief:** Presents a concrete implementation of Modularizing Swift Apps with SPM. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.
- [release announcement](https://forums.swift.org/t/grdb-v7-10-0-android-linux-windows-and-sqlcipher-swiftpm/84754) — Fatbobman’s Swift Weekly · Issue 124 — Article · Topics: Cross-Platform & Web · Product Design · Swift
  **Published:** `2026-02-23T12:03:12.462Z`
  **NeKI brief:** GRDB 7.10's release discussion covers Android, Linux, Windows, and SQLCipher packaging, including current SwiftPM trait limitations. Use it when planning cross-platform SQLite support and checking which dependencies Xcode still downloads unnecessarily.
- [Container-Based Dependency Injection](https://livsycode.com/best-practices/container-based-dependency-injection) — Those Who Swift · Issue 253 — Article · Topics: Architecture · Dependency Injection · Developer Career & Practice
  **Published:** `2026-02-12`
  **NeKI brief:** Presents container-based dependency injection in Swift and the trade-offs of centralized resolution. Use it when comparing composition strategies, keeping dependencies explicit, and preventing a container from becoming hidden global state.
- [Explicit Dependency Injection Best Practices](https://livsycode.com/best-practices/explicit-dependency-injection) — Those Who Swift · Issue 247 — Article · Topics: Architecture · Dependency Injection · Swift
  **Published:** `2026-01-01`
  **NeKI brief:** Explains explicit dependency injection in Swift and why construction-time wiring improves testability. Use it when removing hidden singletons, defining feature boundaries, and keeping production composition separate from previews and test fixtures.
- [Teaching AI to Read Xcode Builds](https://tuist.dev/blog/2025/11/27/teaching-ai-to-read-xcode-builds) — Those Who Swift · Issue 243 — Article · Topics: AI Development · Dependency Injection · Xcode
  **Published:** `2025-12-10`
  **NeKI brief:** Presents Teaching AI to Read Xcode Builds, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Chris Eidhof](https://m.objc.io/@chris) — Fatbobman’s Swift Weekly · Issue 111 — Article · Topics: Dependency Injection · Swift · SwiftUI
  **Published:** `2025-11-17T12:02:46.781Z`
  **NeKI brief:** Presents chris eidhof for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Cultivated Task Cancellation](https://macguru.dev/cultivated-task-cancellation) — iOS Dev Weekly · Issue 733 — Article · Topics: Dependency Injection · Testing
  **Published:** `31st October 2025`
  **NeKI brief:** Explains Cultivated Task Cancellation, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Create Interactive Snippet Shortcut Using App Intents](https://www.swiftjectivec.com/create-interactive-snippet-shortcut-in-appintents) — Those Who Swift · Issue 233 — Article · Topics: App Intents & System Surfaces · Architecture · Dependency Injection
  **Published:** `2025-09-24`
  **NeKI brief:** Examines Create Interactive Snippet Shortcut Using App Intents, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [ImplementedSE-0482Binary Static Library Dependencies](https://github.com/apple/swift-evolution/blob/main/proposals/0482-swiftpm-static-library-binary-target-non-apple-platforms.md) — SwiftLee Weekly · Issue 290 — Source repository · Topics: Dependency Injection · Developer Tools · Swift
  **Published:** `2025-09-23T14:09:24.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0482Binary Static Library Dependencies. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [OpenAttributeGraph](https://github.com/OpenSwiftUIProject/OpenAttributeGraph) — Fatbobman’s Swift Weekly · Issue 101 — Source repository · Topics: Dependency Injection · Swift · SwiftUI
  **Published:** `2025-09-08T12:03:42.721Z`
  **NeKI brief:** OpenAttributeGraph documents an open implementation of SwiftUI-style dependency tracking and attribute propagation. Use it to investigate why state changes invalidate views, while treating it as a learning model rather than Apple's private framework source.
- [Dependencies](https://github.com/pointfreeco/swift-dependencies) — iOS Dev Tools · iOS Dev Tools: ch.at, Mercato, Dependencies — Source repository · Topics: Dependency Injection · Developer Tools · Swift
  **Published:** `2025-08-14T19:53:26.103Z`
  **NeKI brief:** Swift Dependencies models dependency values in a SwiftUI-inspired environment, allowing production implementations to be replaced in tests and previews. Useful for making side effects explicit without threading every service through initializer parameters.
- [Ultimate Guide to Dependency Injection for Modular iOS Apps](https://swiftandmemes.com/ultimate-guide-to-dependency-injection-for-modular-ios-apps) — Those Who Swift · Issue 215 — Article · Topics: Architecture · Dependency Injection · Swift
  **Published:** `2025-05-21`
  **NeKI brief:** Discusses Dependency Injection for Modular iOS Apps in a public developer resource. Use it to compare the author's concrete workflow and trade-offs with your project constraints, and verify any platform-specific claims against current primary documentation.
- [Adding Dependencies to Binary Swift Packages](https://danielsaidi.com/blog/2025/05/02/adding-dependencies-to-binary-swift-packages) — Those Who Swift · Issue 213 — Article · Topics: Dependency Injection · Swift · Swift Package Manager
  **Published:** `2025-05-07`
  **NeKI brief:** Presents Adding dependencies to binary Swift packages, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Swift Testing Challenge: Can You Refactor This?](https://www.mobiledevdiary.com/posts/swift-testing-challange-can-you-refactor-this) — Those Who Swift · Issue 211 — Article · Topics: Concurrency · Swift · Testing
  **Published:** `2025-04-24`
  **NeKI brief:** Examines Swift Testing Challenge: Can You Refactor This?, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Giffy](https://github.com/uwaisalqadri/Giffy) — iOS Dev Tools · iOS Dev Tools: Starview, Mint, Giffy — Source repository · Topics: Architecture · Composable Architecture · Swift
  **Published:** `2025-02-13T18:15:48.650Z`
  **NeKI brief:** Giffy is a sample iOS application that combines SwiftUI, The Composable Architecture, and Swinject-based dependency injection. Use it to inspect how those architectural pieces are wired together in a small, runnable project.
- [Debugging An Undebuggable App](https://bryce.co/undebuggable) — SwiftLee Weekly · Issue 256 — Article · Topics: Dependency Injection · Developer Tools
  **Published:** `2025-01-28T15:11:34.000Z`
  **NeKI brief:** Explains Debugging An Undebuggable App, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Being Sendable with SwiftData](https://brightdigit.com/tutorials/swiftdata-sendable?issue=057) — Fatbobman’s Swift Weekly · Issue 57 — Tutorial · Topics: Concurrency · Swift · SwiftData
  **Published:** `2024-11-11T12:03:02.180Z`
  **NeKI brief:** Explains Sendable boundaries around SwiftData models and persistence access. Use it when concurrency checking exposes non-Sendable model crossings and you need to decide where actors or value projections belong.
- [Carthage](https://github.com/Carthage/Carthage) — iOS Dev Tools · iOS Dev Tools: FeaturesKit, SwipeActions, Carthage — Source repository · Topics: Dependency Injection · Developer Tools · Objective-C & Cocoa
  **Published:** `2024-10-24T17:09:28.334Z`
  **NeKI brief:** Carthage resolves and builds Cocoa dependencies as frameworks without modifying the Xcode project file. Use it when comparing decentralized binary/framework integration with Swift Package Manager, especially for older projects with explicit dependency wiring.
- [Extending SwiftPM Metadata](https://alejandromp.com/development/blog/swift-package-manager-dependency-owners) — iOS Dev Weekly · Issue 677 — Article · Topics: Dependency Injection · Swift
  **Published:** `6th September 2024`
  **NeKI brief:** Presents extending swiftpm metadata for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Swinject](https://github.com/Swinject/Swinject) — iOS Dev Tools · iOS Dev Tools: AppLayoutsUI, Swinject, Pieces Copilot+ — Source repository · Topics: Architecture · Dependency Injection · Developer Tools
  **Published:** `2024-07-11T14:52:09.603Z`
  **NeKI brief:** Swinject resolves object graphs through registered factories and supports scopes such as transient or container lifetime. Use it to compare explicit dependency composition with container-based injection, especially around runtime resolution failures and test overrides.
- [Factory](https://github.com/hmlongco/Factory) — iOS Dev Tools · iOS Dev Tools: Anka, Factory, Runme — Source repository · Topics: Architecture · Concurrency · Swift
  **Published:** `2024-07-04T18:41:08.075Z`
  **NeKI brief:** Factory is a Swift dependency-injection container using property wrappers and scoped registrations for SwiftUI and UIKit. Use it when dependency overrides must be concise in previews and tests, while keeping registration ownership visible.
- [Swift Package Manager framework creation in Xcode](https://www.avanderlee.com/swift/creating-swift-package-manager-framework?ref=createwithswift.com) — Create with Swift · Issue 16 — Article · Topics: Swift · Swift Package Manager · Xcode
  **Published:** `2024-06-07T15:00:34.000Z`
  **NeKI brief:** Creates a Swift package in Xcode and covers Package.swift configuration, platform requirements, dependencies, and local development-package workflows.
- [Converting Local LLMs to Core ML Models - How to Use 🤗 Exporters](https://zenn.dev/shu223/articles/coreml-exporters) — Fatbobman’s Swift Weekly · Issue 31 — Article · Topics: AI Development · Dependency Injection · Xcode
  **Published:** `2024-05-13T12:02:47.849Z`
  **NeKI brief:** Introduces exporting machine-learning models for Core ML, with attention to conversion tooling and deployment constraints. Use it to understand an end-to-end model-export workflow, verifying supported operators and runtime requirements for the target device.
- [Injecting code in result builders](https://trycombine.com/posts/an-example-of-using-arbitrary-code-in-result-builders) — Fatbobman’s Swift Weekly · Issue 10 — Article · Topics: Combine & Reactive Programming · Dependency Injection
  **Published:** `2023-12-11T22:00:36.607Z`
  **NeKI brief:** Demonstrates injecting arbitrary code into result builders and explains how builder transformation rules affect control flow. Use it when designing custom DSLs and checking whether generated component structure remains readable and type-checkable.
- [Questions about the data to create LLMs for embeddings](https://rhonabwy.com/2023/11/15/questions-about-the-data-to-create-llms-for-embeddings) — Fatbobman’s Swift Weekly · Issue 7 — Article · Topics: AI Development · Architecture · Swift
  **Published:** `2023-11-20T22:20:48.455Z`
  **NeKI brief:** Raises practical questions about collecting and preparing data for embedding-oriented language models. Follow it when designing retrieval datasets and evaluating provenance, chunking, quality, and privacy rather than treating embeddings as a drop-in search feature.
- [Featuring XcodeGen, Factory, & Swinject](https://github.com/yonaskolb/XcodeGen) — iOS Dev Tools · 🔨 Xcode Mastery & Updated Strategy? — Source repository · Topics: Concurrency · Swift · Xcode
  **Published:** `2023-06-01T12:01:55.488Z`
  **NeKI brief:** XcodeGen generates Xcode projects from a declarative YAML or JSON specification. Use it to make targets, build settings, schemes, and dependencies reviewable text, avoiding fragile manual edits to project.pbxproj files.
- [On the new Point-Free swift-dependencies library](https://alejandromp.com/blog/on-the-new-pointfree-swift-dependencies) — iOS Dev Weekly · Issue 592 — Article · Topics: Dependency Injection · Swift
  **Published:** `13th January 2023`
  **NeKI brief:** Explores On the new Point-Free swift-dependencies library, focusing on why am i linking to alejandro martinez’s articles on the. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [How does the SwiftUI Environment work and can it be used outside SwiftUI for Dependency Injection?](https://blog.human-friendly.com/how-does-the-swiftui-environment-work-and-can-it-be-used-outside-swiftui-for-dependency-injection) — iOS Dev Weekly · Issue 497 — Tutorial · Topics: Architecture · Swift · SwiftUI
  **Published:** `5th March 2021`
  **NeKI brief:** Examines How does the SwiftUI Environment work and can it be used outside SwiftUI for Dependency Injection?, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Dependency Injection in SwiftUI](https://mokacoding.com/blog/swiftui-dependency-injection) — iOS Dev Weekly · Issue 480 — Article · Topics: Architecture · Swift · SwiftUI
  **Published:** `30th October 2020`
  **NeKI brief:** Examines Dependency Injection in SwiftUI, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [What Adding Dependencies Will Do To Your App in 2020](https://xavierlowmiller.github.io/blog/2020/06/04/Swift-Dependencies) — iOS Dev Weekly · Issue 460 — Article · Topics: Dependency Injection · Developer Tools · Swift
  **Published:** `12th June 2020`
  **NeKI brief:** Examines What Adding Dependencies Will Do To Your App in 2020, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [swift-outdated](https://github.com/kiliankoe/swift-outdated) — iOS Dev Weekly · Issue 449 — Source repository · Topics: Dependency Injection · Swift · Swift Package Manager
  **Published:** `27th March 2020`
  **NeKI brief:** Examines swift-outdated, focusing on if you’re using the swift package manager, then kilian koe has a helpful little tool to quickly let you know if you’ve…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Using Type Erasure to Build a Dependency Injecting Routing Framework](https://swiftrocks.com/using-type-erasure-to-build-a-dependency-injector-in-swift.html) — iOS Dev Weekly · Issue 437 — Article · Topics: Architecture · Dependency Injection · Swift
  **Published:** `3rd January 2020`
  **NeKI brief:** Examines Using Type Erasure to Build a Dependency Injecting Routing Framework, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [package source list](https://github.com/daveverwer/SwiftPMLibrary) — iOS Dev Weekly · Issue 425 — Source repository · Topics: Dependency Injection · Developer Tools · Swift
  **Published:** `11th October 2019`
  **NeKI brief:** Examines package source list, focusing on then, the swift dependency graph from adam fowler – a wonderful visualisation of package dependencies that doesn’t use…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Injecting and changing code on the fly with LLDB](https://swiftrocks.com/using-lldb-manually-xcode-console-tricks.html) — iOS Dev Weekly · Issue 416 — Article · Topics: Cross-Platform & Web · Dependency Injection · Swift
  **Published:** `9th August 2019`
  **NeKI brief:** Examines Injecting and changing code on the fly with LLDB, offering practical guidance on Xcode tooling and development workflow. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Dependency Injection in Practice](https://www.racecondition.software/blog/dependency-injection) — iOS Dev Weekly · Issue 412 — Article · Topics: Architecture · Dependency Injection
  **Published:** `12th July 2019`
  **NeKI brief:** Examines Dependency Injection in Practice, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [great article on dependency injection](http://www.vadimbulavin.com/dependency-injection-in-swift) — iOS Dev Weekly · Issue 408 — Article · Topics: Architecture · Dependency Injection · Swift
  **Published:** `14th June 2019`
  **NeKI brief:** Examines great article on dependency injection, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [simple playground example](https://github.com/timothymiko/swift-networking-examples) — iOS Dev Weekly · Issue 398 — Source repository · Topics: Dependency Injection · Developer Tools · Networking
  **Published:** `5th April 2019`
  **NeKI brief:** Examines simple playground example, focusing on i’ve said this a few times over the years but the reasons for using a third party networking library get fewer and fewer…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against.
- [Swinject in practice](https://felginep.github.io/2019-02-05/swinject-in-practice) — iOS Dev Weekly · Issue 390 — Article · Topics: Architecture · Dependency Injection · Developer Tools
  **Published:** `8th February 2019`
  **NeKI brief:** Examines Swinject in practice, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Dependency Injection for Testability](http://racecondition.software/blog/unit-testing) — iOS Dev Weekly · Issue 380 — Article · Topics: Architecture · Dependency Injection · Testing
  **Published:** `30th November 2018`
  **NeKI brief:** Examines Dependency Injection for Testability, offering practical guidance on test design and automation strategy. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Building iOS dependencies with Carthage](https://blog.kulman.sk/building-ios-depedencies-with-carthage) — iOS Dev Weekly · Issue 374 — Article · Topics: Dependency Injection · Objective-C & Cocoa
  **Published:** `19th October 2018`
  **NeKI brief:** Explores Building iOS dependencies with Carthage in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Future-Proof DI for Storyboard-Based View Controllers](http://holko.pl/2017/12/06/future-proof-dependency-injection) — iOS Dev Weekly · Issue 330 — Article · Topics: Architecture · Dependency Injection
  **Published:** `8th December 2017`
  **NeKI brief:** Explores Future-Proof DI for Storyboard-Based View Controllers in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Sourcery](https://github.com/krzysztofzablocki/Sourcery) — iOS Dev Weekly · Issue 330 — Source repository · Topics: Architecture · Dependency Injection · Developer Tools
  **Published:** `8th December 2017`
  **NeKI brief:** Sourcery parses Swift source with templates to generate repetitive implementations such as mocks, equality, or Codable support. Use it when generated boilerplate has stable conventions and the templates can be reviewed as part of source control.
- [migration guide](https://theswiftpost.co/migrating-from-vapor-1-to-vapor-2) — iOS Dev Weekly · Issue 303 — Tutorial · Topics: Dependency Injection · Developer Community & Business · Swift
  **Published:** `2nd June 2017`
  **NeKI brief:** Walks through migration guide with practical Apple-platform examples. Use it to understand the underlying workflow, identify assumptions and trade-offs, and adapt the ideas carefully while checking API availability and behavior against current SDK documentation.
- [LicensePlist](https://github.com/mono0926/LicensePlist) — iOS Dev Weekly · Issue 300 — Source repository · Topics: Dependency Injection · Developer Tools · Objective-C & Cocoa
  **Published:** `12th May 2017`
  **NeKI brief:** Examines LicensePlist, focusing on most of us use open-source libraries, and most oss asks that a license be included in apps that use them. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Loading Images in iOS Without Dependencies](https://medium.com/@matthew_healy/loading-images-in-ios-without-dependencies-aff1555dbf1e) — iOS Dev Weekly · Issue 299 — Article · Topics: Dependency Injection · Networking
  **Published:** `5th May 2017`
  **NeKI brief:** Examines Loading Images in iOS Without Dependencies, focusing on matthew liam healy answers the age-old question, “how do i download resources from a server?” i love this article because…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against.
- [Using protocol compositon for dependency injection](http://merowing.info/2017/04/using-protocol-compositon-for-dependency-injection) — iOS Dev Weekly · Issue 297 — Article · Topics: Architecture · Dependency Injection · Testing
  **Published:** `21st April 2017`
  **NeKI brief:** Explores Using protocol compositon for dependency injection in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Imagining Dependency Injection via Initializer with Storyboards](http://holko.pl/2016/12/14/storyboards-dependency-injection) — iOS Dev Weekly · Issue 281 — Article · Topics: Architecture · Dependency Injection
  **Published:** `16th December 2016`
  **NeKI brief:** Explores Imagining Dependency Injection via Initializer with Storyboards in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Overdrive](https://github.com/arikis/Overdrive) — iOS Dev Weekly · Issue 277 — Source repository · Topics: Concurrency · Dependency Injection · Developer Tools
  **Published:** `18th November 2016`
  **NeKI brief:** Examines Overdrive, focusing on said sikira with a really nice looking concurrency library built on top of gcd. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [markdown parsers](https://github.com/indragiek/CocoaMarkdown) — iOS Dev Weekly · Issue 275 — Source repository · Topics: Dependency Injection · Developer Tools · Swift
  **Published:** `4th November 2016`
  **NeKI brief:** Examines markdown parsers, focusing on loïc lecrenier with a new markdown parser, written in pure swift 3. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Perform](https://github.com/thoughtbot/Perform) — iOS Dev Weekly · Issue 267 — Source repository · Topics: Architecture · Dependency Injection · Developer Tools
  **Published:** `9th September 2016`
  **NeKI brief:** Examines Perform, focusing on chris dzombak on the difficulties of dependency injection with view controllers. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [depcheck](https://github.com/wojteklu/depcheck) — iOS Dev Weekly · Issue 265 — Source repository · Topics: Dependency Injection · Developer Tools · Swift
  **Published:** `26th August 2016`
  **NeKI brief:** Examines depcheck, focusing on wojtek lukaszuk with a cute little tool that’ll analyse your swift project for class dependencies. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Managing Xcode](http://pewpewthespells.com/blog/managing_xcode.html) — iOS Dev Weekly · Issue 215 — Article · Topics: Cross-Platform & Web · Dependency Injection · Xcode
  **Published:** `11th September 2015`
  **NeKI brief:** Explains Managing Xcode with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [guide to xcconfig files](http://pewpewthespells.com/blog/xcconfig_guide.html) — iOS Dev Weekly · Issue 215 — Article · Topics: Cross-Platform & Web · Dependency Injection · Xcode
  **Published:** `11th September 2015`
  **NeKI brief:** Explains The Unofficial Guide to xcconfig files with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Bolts](https://github.com/BoltsFramework/Bolts-iOS) — iOS Dev Weekly · Issue 131 — Source repository · Topics: Concurrency · Dependency Injection · Developer Tools
  **Published:** `31st January 2014`
  **NeKI brief:** Provides the Bolts source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [APIClient](https://github.com/klaaspieter/APIClient) — iOS Dev Weekly · Issue 124 — Source repository · Topics: Dependency Injection · Developer Tools · Navigation & Deep Linking
  **Published:** `13th December 2013`
  **NeKI brief:** Provides the APIClient source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Stop writing data parsing code in your Apps](http://www.merowing.info/2013/07/stop-writing-data-parsing-code-in-your-apps) — iOS Dev Weekly · Issue 104 — Article · Topics: Dependency Injection
  **Published:** `26th July 2013`
  **NeKI brief:** Explains Stop writing data parsing code in your Apps with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [Using Model Context Protocol in iOS apps](https://www.artemnovichkov.com/blog/using-model-context-protocol-in-ios-apps) — Not only Swift · Issue 81 — Article · Topics: AI Development · Architecture · Dependency Injection
  **NeKI brief:** Explores using Model Context Protocol from an iOS app. Follow it when assessing tool or resource integrations, keeping transport, trust, privacy, and user-consent boundaries explicit before exposing app data to external agents.
- [Resolver](https://github.com/hmlongco/Resolver) — Not only Swift · Issue 77 — Source repository · Topics: Architecture · Swift · SwiftUI
  **NeKI brief:** This source repository covers Resolver's dependency-injection approach and its deprecated status. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Navigator: Advanced Navigation Support for SwiftUI.](https://github.com/hmlongco/Navigator) — Not only Swift · Issue 77 — Source repository · Topics: Architecture · Swift · SwiftUI
  **NeKI brief:** Navigator provides a SwiftUI navigation abstraction centered on route-driven presentation. Use it to compare centralized routing decisions with native NavigationStack state when complex flows need testable deep-link handling.
