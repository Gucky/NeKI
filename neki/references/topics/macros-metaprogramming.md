# Macros & Metaprogramming

Third-party reading leads collected from NeKI sources. The links may be useful perspectives, but are not vetted recommendations or authoritative API guidance. NeKI publishes routing metadata, not the linked articles' text.

**Scope:** Macros, compiler plugins, generated code, and metaprogramming techniques.

- Last collected: `2026-07-22T21:56:49Z`
- Indexed links shown: **136**

## Direct-source reading

- [Swift Metaprogramming: Writing Code that Inspects Itself | Kodeco](https://www.kodeco.com/52631262-swift-metaprogramming-writing-code-that-inspects-itself) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Uses Mirror reflection to inspect Swift values at runtime, then connects that mechanism to reducing repetitive conformance and serialization code. The useful boundary is that reflection can discover structure, but does not replace explicit compile-time guarantees.
- [SwiftData: Simplifying Persistence in iOS Apps | Kodeco](https://www.kodeco.com/40504096-swiftdata-simplifying-persistence-in-ios-apps) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Explains SwiftData's @Model macro, model container, and context-driven persistence as a Swift-native layer over local storage. It is useful for evaluating migration from Core Data while keeping schema and context lifetime decisions explicit.
- [Using @Observable in SwiftUI views](https://nilcoalescing.com/blog/ObservableInSwiftUI) — Nil Coalescing · article catalogue
  **Published:** `2026-07-13`
  **NeKI brief:** Introduces @Observable and explains its property-level tracking difference from ObservableObject. The examples show why migration can reduce needless view updates while still requiring deliberate ownership of observable instances.
- [Initializing @Observable classes with the @State macro in Xcode 27](https://nilcoalescing.com/blog/InitializingObservableClassesWithTheStateMacroInXcode27) — Nil Coalescing · article catalogue
  **Published:** `2026-07-13`
  **NeKI brief:** Explains initializing an @Observable reference type through @State in current SwiftUI. Use it when a view owns an observable model and must preserve its identity across body recalculation rather than recreating it inline.
- [New macros for SwiftNavigation](https://www.pointfree.co/blog/posts/215-new-macros-for-swiftnavigation) — Point-Free · article catalogue
  **Published:** `2026-06-23T00:00:00Z`
  **NeKI brief:** Introduces @CaseBindable and @UITransactionEntry macros for deriving enum-case bindings and custom UI transaction keys. The examples show how code generation can remove repetitive navigation glue while preserving typed state.
- [Introducing @DependencyEntry](https://www.pointfree.co/blog/posts/213-introducing-dependencyentry) — Point-Free · article catalogue
  **Published:** `2026-06-17T00:00:00Z`
  **NeKI brief:** Presents @DependencyEntry as a macro for registering dependencies while supporting live, preview, and test values. The design shows how generated declarations can keep dependency setup concise without losing explicit override points.
- [Custom environment values in SwiftUI](https://nilcoalescing.com/blog/CustomEnvironmentValuesInSwiftUI) — Nil Coalescing · article catalogue
  **Published:** `2026-06-09`
  **NeKI brief:** Compares the pre-Xcode 16 pattern for defining SwiftUI environment keys with the @Entry macro, then shows how values flow through a view hierarchy.
- [Beta Preview: ComposableArchitecture 2.0](https://www.pointfree.co/blog/posts/206-beta-preview-composablearchitecture-2-0) — Point-Free · article catalogue
  **Published:** `2026-04-01T00:00:00Z`
  **NeKI brief:** Previews Composable Architecture 2.0 changes and their implications for state, effects, and dependency management. Use it to assess an upcoming migration path before adopting beta conventions in a production feature.
- [Beta Preview: DebugSnapshots](https://www.pointfree.co/blog/posts/205-beta-preview-debugsnapshots) — Point-Free · article catalogue
  **Published:** `2026-04-01T00:00:00Z`
  **NeKI brief:** Introduces DebugSnapshots for recording structured debugging state alongside UI behavior. Follow it when reproducing visual or state-dependent failures requires an inspectable artifact rather than a screenshot detached from its model inputs.
- [Understanding Live Activities: visual micro-storytelling](https://www.createwithswift.com/understanding-live-activities-visual-micro-storytelling) — Create with Swift · article catalogue
  **Published:** `2025-09-12T13:00:50.000Z`
  **NeKI brief:** Explains Live Activities as a visual storytelling surface driven by timely state updates. Useful for designing concise lock-screen and Dynamic Island experiences without treating them as miniature full screens.
- [Property Wrappers in Swift explained with code examples - SwiftLee](https://www.avanderlee.com/swift/property-wrappers) — Antoine van der Lee articles · article catalogue
  **Published:** `2025-08-19T12:08:35+00:00`
  **NeKI brief:** Builds custom property wrappers to centralize storage and projected values, then shows their initialization and composition rules. The article helps evaluate when a wrapper removes duplication without hiding important state transitions.
- [Exploring the Foundation Models framework](https://www.createwithswift.com/exploring-the-foundation-models-framework) — Create with Swift · article catalogue
  **Published:** `2025-08-07T13:00:24.000Z`
  **NeKI brief:** Introduces Apple's Foundation Models framework and its on-device language-model capabilities. Useful for mapping model sessions, availability, and structured generation before integrating AI into an app.
- [Default Actor Isolation - New Problems from Good Intentions](https://fatbobman.com/en/posts/default-actor-isolation) — Fatbobman · article catalogue
  **Published:** `2025-07-30T14:00:00.000Z`
  **NeKI brief:** Swift 6.2 infers a default actor for otherwise unmarked declarations, reducing annotations but exposing actor-boundary errors in macros and mixed-isolation code. This is useful when auditing migration diagnostics and deciding where explicit isolation remains necessary.
- [Introducing Animatable macro in SwiftUI | Swift with Majid](https://swiftwithmajid.com/2025/07/08/introducing-animatable-macro-in-swiftui) — Swift with Majid · article catalogue
  **Published:** `2025-07-08T00:00:00+00:00`
  **NeKI brief:** Explains SwiftUI's @Animatable macro as a way to synthesize animatable-data handling for custom views. Use it when complex values should interpolate correctly without maintaining a fragile manual AnimatableData implementation.
- [#Playground Macro: Running Code Snippets in Xcode's canvas - SwiftLee](https://www.avanderlee.com/swift/playground-macro-running-code-snippets-in-xcodes-canvas) — Antoine van der Lee articles · article catalogue
  **Published:** `2025-06-24T07:08:46+00:00`
  **NeKI brief:** Demonstrates Xcode 26's #Playground macro for running named Swift snippets in the canvas and navigating among multiple experiments.
- [Mitigating SwiftSyntax build times](https://www.pointfree.co/blog/posts/171-mitigating-swiftsyntax-build-times) — Point-Free · article catalogue
  **Published:** `2025-06-03T00:00:00Z`
  **NeKI brief:** Diagnoses SwiftSyntax compile-time costs and describes mitigation strategies around target boundaries and dependency choices. The article is useful for turning macro-heavy build slowdowns into measurable package-structure changes.
- [Modern URL construction in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/modern-url-construction-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2025-03-31`
  **NeKI brief:** Builds URLs with modern Foundation components rather than string concatenation. Use it when paths, query items, and percent encoding must remain correct under optional or user-provided values.
- [Preview SwiftUI views with bindings using @Previewable](https://nilcoalescing.com/blog/PreviewSwiftUIViewsWithBindings) — Nil Coalescing · article catalogue
  **Published:** `2025-03-04`
  **NeKI brief:** Shows how Xcode 16's @Previewable macro supplies local mutable state so SwiftUI previews can exercise views that require bindings.
- [Observing properties on an @Observable class outside of SwiftUI views – Donny Wals](https://www.donnywals.com/observing-properties-on-an-observable-class-outside-of-swiftui-views) — Donny Wals · article catalogue
  **Published:** `2025-01-21T10:59:24+00:00`
  **NeKI brief:** Observation can track an @Observable property from non-view code, extending SwiftUI's dependency model to coordinators while requiring a lifetime-managed observation scope.
- [Testing requirements with #require in Swift Testing – Donny Wals](https://www.donnywals.com/testing-requirements-with-require-in-swift-testing) — Donny Wals · article catalogue
  **Published:** `2024-11-28T14:02:48+00:00`
  **NeKI brief:** #require turns prerequisite failures into thrown test exits, separating invalid setup from behavioral assertions; use it sparingly so ordinary expectation failures still report together.
- [Introducing Swift Testing. Lifecycle. | Swift with Majid](https://swiftwithmajid.com/2024/10/29/introducing-swift-testing-lifecycle) — Swift with Majid · article catalogue
  **Published:** `2024-10-29T00:00:00+00:00`
  **NeKI brief:** Explains Swift Testing lifecycle hooks and how setup or teardown scopes differ from XCTest methods. Useful for isolating shared fixtures without leaking state between parallel tests.
- [Using the #require macro for Swift Testing - SwiftLee](https://www.avanderlee.com/swift-testing/require-macro) — Antoine van der Lee articles · article catalogue
  **Published:** `2024-10-28T08:01:48+00:00`
  **NeKI brief:** Explains #require as Swift Testing’s throwing precondition for setup and optional unwrapping, contrasting its fail-fast behavior with #expect and showing how failure messages retain useful source context.
- [Comprehensive Guide to Mastering KeyPath in Swift](https://fatbobman.com/en/posts/comprehensive-guide-to-mastering-keypath-in-swift) — Fatbobman · article catalogue
  **Published:** `2024-10-23T14:00:00.000Z`
  **NeKI brief:** Explains Swift key paths for typed property access and transformation. Use it when building reusable sorting, binding, observation, or mapping APIs without fragile string identifiers.
- [Introducing Swift Testing. Basics. | Swift with Majid](https://swiftwithmajid.com/2024/10/22/introducing-swift-testing-basics) — Swift with Majid · article catalogue
  **Published:** `2024-10-22T00:00:00+00:00`
  **NeKI brief:** Introduces Swift Testing's test declarations, expectations, and setup model. Useful as a migration starting point when replacing XCTest boilerplate while keeping behavioral assertions readable.
- [How to listen for property changes in an @Observable class using AsyncStreams](https://www.polpiella.dev/observable-property-changes) — Pol Piella · article catalogue
  **Published:** `2024-10-10T00:00:00.000Z`
  **NeKI brief:** AsyncStream can bridge Observation changes into an async consumer, replacing ObservableObject publishers while preserving cancellation and backpressure decisions. The comparison clarifies when a stream should be scoped to a task and when direct observation is simpler.
- [UserDefaults and Observation in SwiftUI - How to Achieve Precise Responsiveness](https://fatbobman.com/en/posts/userdefaults-and-observation) — Fatbobman · article catalogue
  **Published:** `2024-10-09T14:00:00.000Z`
  **NeKI brief:** Observation does not automatically make UserDefaults changes precise inside SwiftUI. The @ObservableDefaults approach bridges key reads and writes into tracked properties, avoiding broad invalidation while retaining UserDefaults persistence semantics.
- [Using the #expect macro for Swift Testing - SwiftLee](https://www.avanderlee.com/swift-testing/expect-macro) — Antoine van der Lee articles · article catalogue
  **Published:** `2024-09-30T11:46:30+00:00`
  **NeKI brief:** Walks through #expect’s expression-aware assertions, including equality, errors, and optional values, and shows how the macro records evaluated subexpressions to make failing tests easier to diagnose.
- [Swift Testing: Writing a Modern Unit Test](https://www.avanderlee.com/swift-testing/modern-unit-test) — Antoine van der Lee articles · article catalogue
  **Published:** `2024-09-10T08:19:39+00:00`
  **NeKI brief:** Builds a modern Swift Testing unit test from a small example, covering @Test, #expect, async code, and descriptive names while highlighting the framework’s macro-driven differences from XCTestCase methods.
- [SwiftUI Previewable Macro](https://useyourloaf.com/blog/swiftui-previewable-macro) — Use Your Loaf · article catalogue
  **Published:** `2024-08-26T13:14:36+01:00`
  **NeKI brief:** Uses the Previewable macro to create mutable preview state without manually declaring State wrappers. Useful for interactive previews that exercise editing and selection flows quickly.
- [@Entry macro: Creating custom environment values in SwiftUI](https://www.avanderlee.com/swiftui/entry-macro-custom-environment-values) — Antoine van der Lee articles · article catalogue
  **Published:** `2024-08-13T18:33:02+00:00`
  **NeKI brief:** Uses SwiftUI’s @Entry macro to declare custom environment values with less boilerplate, then injects and reads them through the view hierarchy. It is useful when sharing dependencies while keeping defaults and ownership explicit.
- [Entry Macro for Custom SwiftUI Environment Values](https://useyourloaf.com/blog/entry-macro-for-custom-swiftui-environment-values) — Use Your Loaf · article catalogue
  **Published:** `2024-08-12T10:37:14+01:00`
  **NeKI brief:** Replaces the separate EnvironmentKey and EnvironmentValues boilerplate with SwiftUI’s iOS 18 @Entry macro, while preserving the same environment injection and read behavior. Use it to reduce custom environment declarations without changing the dependency flow.
- [Introducing Entry macro in SwiftUI | Swift with Majid](https://swiftwithmajid.com/2024/07/09/introducing-entry-macro-in-swiftui) — Swift with Majid · article catalogue
  **Published:** `2024-07-09T00:00:00+00:00`
  **NeKI brief:** Introduces SwiftUI's Entry macro for declaring framework-style entries with less boilerplate. It is a targeted macro convenience rather than a general dependency system, so availability and generated API shape should be checked when supporting older SDKs.
- [SwiftData in WWDC 2024 - The Revolution Continues, Stability Still Awaits](https://fatbobman.com/en/posts/swiftdata-in-wwdc2024) — Fatbobman · article catalogue
  **Published:** `2024-06-12T00:12:00.000Z`
  **NeKI brief:** WWDC 2024 SwiftData additions promise richer querying and persistence, but practical stability and migration concerns remain. This review helps separate announced API surface from production readiness when planning adoption.
- [Getting started with Swift Testing](https://www.polpiella.dev/swift-testing) — Pol Piella · article catalogue
  **Published:** `2024-06-12T00:00:00.000Z`
  **NeKI brief:** Introduces Swift Testing in the Swift 6 toolchain, then maps representative XCTest cases to the macro-based test and expectation APIs.
- [@Previewable: Dynamic SwiftUI Previews Made Easy](https://www.avanderlee.com/swiftui/previewable-macro-usage-in-previews) — Antoine van der Lee articles · article catalogue
  **Published:** `2024-06-11T07:39:09+00:00`
  **NeKI brief:** Explains how @Previewable works in Xcode 16 and uses it to make SwiftUI previews interactive without adding preview-only state to production views.
- [What’s new in Swift 5.9? – Hacking with Swift](https://www.hackingwithswift.com/articles/258/whats-new-in-swift-5-9) — Hacking with Swift articles · article catalogue
  **Published:** `2024-06-09T21:24:01+00:00`
  **NeKI brief:** Summarizes Swift 5.9 features including macros and parameter packs with migration context. Useful as a language-version index before adopting individual syntax in production code.
- [Swift Testing support for SnapshotTesting](https://www.pointfree.co/blog/posts/146-swift-testing-support-for-snapshottesting) — Point-Free · article catalogue
  **Published:** `2024-06-08T00:00:00Z`
  **NeKI brief:** Connects Swift Testing test functions with SnapshotTesting assertions, preserving snapshot diffs while adopting the newer test framework. Follow it when migrating suites without losing failure artifacts or custom traits.
- [Core Data Reform - Achieving Elegant Concurrency Operations like SwiftData](https://fatbobman.com/en/posts/core-data-reform-achieving-elegant-concurrency-operations-like-swiftdata) — Fatbobman · article catalogue
  **Published:** `2024-04-18T00:20:00.000Z`
  **NeKI brief:** The proposed Core Data reform wraps contexts and queue confinement to approximate SwiftData's actor-oriented access model. It is useful when modernizing legacy persistence while preserving existing stores and managed-object APIs.
- [The @State Specter - Analyzing a Bug in Multi-Window SwiftUI Applications](https://fatbobman.com/en/posts/the-state-specter-analyzing-a-bug-in-multi-window-swiftui-applications) — Fatbobman · article catalogue
  **Published:** `2024-04-11T00:12:00.000Z`
  **NeKI brief:** A multi-window SwiftUI bug reveals that @State storage and view identity can diverge between scenes. The investigation gives a reproducible way to distinguish scene-local state from shared model ownership.
- [@Observable in SwiftUI explained – Donny Wals](https://www.donnywals.com/observable-in-swiftui-explained) — Donny Wals · article catalogue
  **Published:** `2024-02-06T20:53:04+00:00`
  **NeKI brief:** @Observable tracks property reads so SwiftUI can invalidate only dependent views, improving update precision while making ownership and mutation boundaries more important.
- [@Observable Macro performance increase over ObservableObject](https://www.avanderlee.com/swiftui/observable-macro-performance-increase-observableobject) — Antoine van der Lee articles · article catalogue
  **Published:** `2024-01-09T08:00:00+00:00`
  **NeKI brief:** Compares the Observation framework's @Observable macro with ObservableObject, focusing on property-level tracking and view invalidation. The measurements and migration examples explain why fewer unnecessary updates can improve SwiftUI performance.
- [Distributing a Swift Macro using CocoaPods](https://www.polpiella.dev/cocoapods-swift-macros) — Pol Piella · article catalogue
  **Published:** `2023-12-06T00:00:00.000Z`
  **NeKI brief:** Details distributing a Swift macro through CocoaPods, including packaging constraints for compiler plugins. Use it when a macro package must support consumers outside SwiftPM and the distribution model changes build integration.
- [How to import Swift macros without using Swift Package Manager](https://www.polpiella.dev/binary-swift-macros) — Pol Piella · article catalogue
  **Published:** `2023-11-29T00:00:00.000Z`
  **NeKI brief:** Builds binary Swift macros and discusses packaging compiler plugins for consumers. Useful when distributing macro implementations without exposing source, while accounting for toolchain and platform compatibility.
- [Macro Bonanza](https://www.pointfree.co/blog/posts/121-macro-bonanza) — Point-Free · article catalogue
  **Published:** `2023-11-17T00:00:00Z`
  **NeKI brief:** Surveys Swift macro capabilities through concrete generation examples. Use it to compare attached and freestanding macro designs before introducing generated declarations into a production module.
- [Macro Bonanza: Dependencies](https://www.pointfree.co/blog/posts/120-macro-bonanza-dependencies) — Point-Free · article catalogue
  **Published:** `2023-11-16T00:00:00Z`
  **NeKI brief:** A dependency macro can synthesize environment plumbing while keeping live and test implementations interchangeable. The pattern reduces manual injection code, but generated behavior still needs inspection when compiler or macro expansion changes.
- [Macro Bonanza: SwiftUI Navigation](https://www.pointfree.co/blog/posts/119-macro-bonanza-swiftui-navigation) — Point-Free · article catalogue
  **Published:** `2023-11-15T00:00:00Z`
  **NeKI brief:** A navigation macro can derive destination and path plumbing from domain declarations, reducing stringly-typed routing code. The trade-off is compiler-generated structure that must be version-pinned and tested at feature boundaries.
- [Macro Bonanza: Composable Architecture](https://www.pointfree.co/blog/posts/118-macro-bonanza-composable-architecture) — Point-Free · article catalogue
  **Published:** `2023-11-14T00:00:00Z`
  **NeKI brief:** Composable Architecture macros can synthesize repetitive reducer and observation plumbing from declared domains. The gain is less boilerplate; the trade-off is compiler-generated behavior that must be reviewed and versioned carefully.
- [Macro Bonanza: Case Paths](https://www.pointfree.co/blog/posts/117-macro-bonanza-case-paths) — Point-Free · article catalogue
  **Published:** `2023-11-13T00:00:00Z`
  **NeKI brief:** Case-path macros can derive enum extraction and embedding helpers from declarations, reducing hand-maintained pattern-matching glue. The approach improves consistency while macro expansion remains part of the build surface.
- [Mastering Preview macro in Swift | Swift with Majid](https://swiftwithmajid.com/2023/10/17/mastering-preview-macro-in-swift) — Swift with Majid · article catalogue
  **Published:** `2023-10-17T00:00:00+00:00`
  **NeKI brief:** Introduces Swift's preview macro for rendering SwiftUI and UIKit components in Xcode. Useful for replacing PreviewProvider boilerplate while preserving representative preview states.
- [Concurrent Programming in SwiftData](https://fatbobman.com/en/posts/concurret-programming-in-swiftdata) — Fatbobman · article catalogue
  **Published:** `2023-10-11T00:20:00.000Z`
  **NeKI brief:** SwiftData's ModelActor-backed serial executor provides a safer concurrency boundary than ad-hoc Core Data queue usage, but context ownership still matters. The discussion helps diagnose cross-actor model access and design explicit read/write entry points.
- [MacroTesting 0.2.0: Test more with less](https://www.pointfree.co/blog/posts/115-macrotesting-0-2-0-test-more-with-less) — Point-Free · article catalogue
  **Published:** `2023-10-03T00:00:00Z`
  **NeKI brief:** Describes MacroTesting’s snapshot-based harness for Swift macro expansion, including failure diffs and fixture updates, so compiler-plugin behavior can be reviewed as concise source transformations.
- [Mastering Observation framework in Swift | Swift with Majid](https://swiftwithmajid.com/2023/10/03/mastering-observable-framework-in-swift) — Swift with Majid · article catalogue
  **Published:** `2023-10-03T00:00:00+00:00`
  **NeKI brief:** Introduces the Observation framework's @Observable macro and property tracking, reducing manual objectWillChange plumbing. Fine-grained invalidation can improve updates, but reference ownership and main-actor boundaries still need explicit design.
- [A new tool for testing macros in Swift](https://www.pointfree.co/blog/posts/114-a-new-tool-for-testing-macros-in-swift) — Point-Free · article catalogue
  **Published:** `2023-09-18T00:00:00Z`
  **NeKI brief:** Introduces a macro-testing tool that compares expanded source against expected output. Useful for regression-testing code generation without relying only on downstream compilation failures.
- [Predicate Macro in Swift for filtering and searching - SwiftLee](https://www.avanderlee.com/swift/predicate-macro-filtering-searching) — Antoine van der Lee articles · article catalogue
  **Published:** `2023-09-05T08:40:34+00:00`
  **NeKI brief:** Builds Swift predicates with the #Predicate macro, including optional relationships and reusable filtering expressions. The article is useful when translating in-memory searches into type-checked SwiftData or Core Data queries without relying on string predicates.
- [SwiftSyntax: Parse and Generate Swift source code - SwiftLee](https://www.avanderlee.com/swift/swiftsyntax-parse-and-generate-swift-source-code) — Antoine van der Lee articles · article catalogue
  **Published:** `2023-08-29T08:52:24+00:00`
  **NeKI brief:** Uses SwiftSyntax to parse source files and generate formatted Swift code, walking syntax nodes instead of manipulating text. The pipeline is a useful starting point for linters, refactoring tools, and source-generating macros.
- [#Preview SwiftUI Views using Macros - SwiftLee](https://www.avanderlee.com/xcode/preview-swiftui-uikit-appkit-views) — Antoine van der Lee articles · article catalogue
  **Published:** `2023-06-27T07:35:07+00:00`
  **NeKI brief:** Uses the #Preview macro to render SwiftUI, UIKit, and AppKit views, including wrapper setup for controller-based components. Useful for shortening visual feedback loops across mixed UI stacks.
- [Swift Macros: Extend Swift with New Kinds of Expressions](https://www.avanderlee.com/swift/macros) — Antoine van der Lee articles · article catalogue
  **Published:** `2023-06-13T08:03:31+00:00`
  **NeKI brief:** Explains Swift macro roles and expansion, distinguishing freestanding from attached macros and showing generated declarations. Useful for evaluating when compile-time code generation reduces boilerplate without obscuring API behavior.
- [What’s the difference between Macros and property wrappers? – Donny Wals](https://www.donnywals.com/whats-the-difference-between-macros-and-property-wrappers) — Donny Wals · article catalogue
  **Published:** `2023-06-06T19:54:04+00:00`
  **NeKI brief:** Macros generate or transform declarations at compile time, whereas property wrappers mediate storage and access; they solve different extension points despite similar syntax.
- [What are Character and Run in AttributedString | Sarunw](https://sarunw.com/posts/attributed-string-views) — Sarunw · article catalogue
  **Published:** `2023-03-28`
  **NeKI brief:** Distinguishes AttributedString's Character and Run views: characters address textual units, while runs group contiguous attributes. This is a useful inspection model when styling or parsing rich text without treating each Unicode character as an independent attribute span.
- [AttributedString in iOS 15 | Sarunw](https://sarunw.com/posts/attributed-string) — Sarunw · article catalogue
  **Published:** `2023-03-20`
  **NeKI brief:** Introduces AttributedString as Swift's value-typed rich-text model, covering concatenation, containers, and partial styling. Follow it when replacing NSAttributedString to gain safer composition while still mapping presentation attributes deliberately.
- [What is the difference between #available and @available | Sarunw](https://sarunw.com/posts/available-vs-available) — Sarunw · article catalogue
  **Published:** `2022-12-13`
  **NeKI brief:** Distinguishes runtime #available checks from declaration-level @available annotations, helping place deployment compatibility at the correct API boundary and avoid redundant guards.
- [How to handle API Changes with @available | Sarunw](https://sarunw.com/posts/how-to-handle-api-changes-with-available) — Sarunw · article catalogue
  **Published:** `2022-04-21`
  **NeKI brief:** Use @available to annotate declarations with platform constraints, and use #available to branch at runtime when an API may be absent. Keeping those roles separate lets the compiler enforce unsupported use while preserving an explicit fallback implementation.
- [What do @main, @UIApplicationMain, and @NSApplicationMain mean | Sarunw](https://sarunw.com/posts/what-do-main-uiapplicationmain-nsapplicationmain-mean) — Sarunw · article catalogue
  **Published:** `2021-11-22`
  **NeKI brief:** Explains how Swift's @main and the older UIApplicationMain or NSApplicationMain attributes establish an app entry point, clarifying the migration from generated main functions.
- [How to remove extra padding when converting HTML to NSAttributedString | Sarunw](https://sarunw.com/posts/how-to-remove-extra-padding-when-converting-html-to-nsattributedstring) — Sarunw · article catalogue
  **Published:** `2021-10-21`
  **NeKI brief:** When HTML conversion adds UILabel spacing, distinguish block-element margins from trailing newline characters in the attributed result. Normalize the HTML or trim only leading and trailing whitespace while preserving attributes, rather than compensating with arbitrary layout offsets.
- [As We May Code - NSHipster](https://nshipster.com/as-we-may-code) — NSHipster · article catalogue
  **Published:** `2020-07-07T00:00:00-07:00`
  **NeKI brief:** The essay treats source code as material for analysis, not only execution, and points toward tools that raise code into understandable structure. It is useful context when evaluating syntax-aware refactoring or documentation workflows.
- [How to display HTML in UILabel and UITextView | Sarunw](https://sarunw.com/posts/how-to-display-html-in-uilabel-and-uitextview) — Sarunw · article catalogue
  **Published:** `2020-04-14`
  **NeKI brief:** Converts HTML into NSAttributedString for UILabel or UITextView, then applies app styling around the rendered value when a backend supplies marked-up text without embedding a web view.
- [Nullability warnings with libextobjc’s @keypath macro – Ole Begemann](https://oleb.net/2018/@keypath) — Ole Begemann · article catalogue
  **Published:** `2018-07-27T21:31:14Z`
  **NeKI brief:** The Objective-C `@keypath` macro turns a property expression into a checked key-path string, reducing typos in KVO and bindings. Nullability warnings still depend on macro expansion and declarations, so the convenience does not remove annotation work.
- [Customizing the file header comment and other text macros in Xcode 9 – Ole Begemann](https://oleb.net/blog/2017/07/xcode-9-text-macros) — Ole Begemann · article catalogue
  **Published:** `2017-07-20T18:58:00Z`
  **NeKI brief:** Explains Xcode text macros for file headers and templates. Use it when standardizing generated comment metadata without manually editing every new source file.
- [Chris Lattner on the Realm WWDC 2017 Swift panel – Ole Begemann](https://oleb.net/blog/2017/06/chris-lattner-wwdc-swift-panel) — Ole Begemann · article catalogue
  **Published:** `2017-06-30T17:13:00Z`
  **NeKI brief:** Reports Chris Lattner's discussion of Swift at a WWDC panel. Use it as historical context for language design priorities and community expectations, not as current Swift evolution guidance.
- [OptionSet - NSHipster](https://nshipster.com/optionset) — NSHipster · article catalogue
  **Published:** `2014-09-08T00:00:00-07:00`
  **NeKI brief:** OptionSet represents combinable flags with a type-safe Swift interface over bit patterns. Use it for independent capabilities that may coexist, avoiding enums when callers must select more than one case.
- [IBAction / IBOutlet / IBOutletCollection - NSHipster](https://nshipster.com/ibaction-iboutlet-iboutletcollection) — NSHipster · article catalogue
  **Published:** `2014-05-05T00:00:00-07:00`
  **NeKI brief:** IBAction and IBOutlet connect Interface Builder objects to UIKit code through runtime wiring. Use typed, minimal outlets and actions, validating connections during refactors so storyboard identifiers do not become hidden failure points.
- [Extended File Attributes - NSHipster](https://nshipster.com/extended-file-attributes) — NSHipster · article catalogue
  **Published:** `2014-01-20T00:00:00-08:00`
  **NeKI brief:** Extended attributes attach metadata to filesystem items outside their visible contents. The article is useful for understanding Finder tags and quarantine-like data, while preserving attributes intentionally during file copy and export workflows.
- [NSRange - NSHipster](https://nshipster.com/nsrange) — NSHipster · article catalogue
  **Published:** `2014-01-13T00:00:00-08:00`
  **NeKI brief:** NSRange represents UTF-16-based locations used by many Foundation APIs. Follow it when bridging Swift String indices to Objective-C interfaces, where Unicode grapheme boundaries make integer offsets unsafe.
- [NSValue - NSHipster](https://nshipster.com/nsvalue) — NSHipster · article catalogue
  **Published:** `2013-01-28T00:00:00-08:00`
  **NeKI brief:** Shows how NSValue boxes scalars, structs, and geometry for Objective-C collections and APIs. Follow it when auditing mixed Swift/Objective-C boundaries, choosing Codable or native Swift values where modern code can avoid boxing.
- [__attribute__ - NSHipster](https://nshipster.com/__attribute__) — NSHipster · article catalogue
  **Published:** `2013-01-14T00:00:00-08:00`
  **NeKI brief:** Surveys Clang __attribute__ annotations that influence diagnostics, availability, ownership, and API import behavior. Follow it when maintaining Objective-C headers or generated Swift interfaces, verifying each annotation against the active compiler and SDK.
- [nil / Nil / NULL / NSNull - NSHipster](https://nshipster.com/nil) — NSHipster · article catalogue
  **Published:** `2013-01-07T00:00:00-08:00`
  **NeKI brief:** Distinguishes nil, Nil, NULL, and NSNull across Objective-C pointers, class references, C values, and collection placeholders. Use it to diagnose mixed-language nullability bugs instead of treating every empty value as interchangeable.
- [UICollectionView - NSHipster](https://nshipster.com/uicollectionview) — NSHipster · article catalogue
  **Published:** `2012-09-24T00:00:00-07:00`
  **NeKI brief:** Introduces UICollectionView layout, data-source, and reusable-cell primitives for grid and custom collection interfaces. Follow it when maintaining UIKit screens, then verify modern diffable data sources, compositional layouts, and cell registration choices.
- [Tips & Tricks for conditional iOS3, iOS3.2 and iOS4 code | Cocoa with Love](https://www.cocoawithlove.com/2010/07/tips-tricks-for-conditional-ios3-ios32.html) — Cocoa with Love · article catalogue
  **Published:** `2010-07-06`
  **NeKI brief:** Conditional compilation and availability checks let one codebase target divergent iOS SDKs, but each branch adds testing surface. These tips help isolate source compatibility from runtime capability and deployment-target policy.
- [What is a meta-class in Objective-C? | Cocoa with Love](https://www.cocoawithlove.com/2010/01/what-is-meta-class-in-objective-c.html) — Cocoa with Love · article catalogue
  **Published:** `2010-01-17`
  **NeKI brief:** Objective-C metaclasses explain how class methods participate in the same message-dispatch model as instance methods. The article is valuable when debugging runtime introspection, swizzling, or unexpected class-level behavior.
- [Hidden Xcode build, debug and template settings | Cocoa with Love](https://www.cocoawithlove.com/2008/06/hidden-xcode-build-debug-and-template.html) — Cocoa with Love · article catalogue
  **Published:** `2008-06-28`
  **NeKI brief:** Xcode behavior is shaped by build settings, scripts, launch arguments, environment variables, and template macros beyond visible target controls. Keep such customization discoverable and versioned where possible, since hidden per-user settings undermine reproducible builds.
- [Type punning isn't funny: Using pointers to recast in C is bad. | Cocoa with Love](https://www.cocoawithlove.com/2008/04/using-pointers-to-recast-in-c-is-bad.html) — Cocoa with Love · article catalogue
  **Published:** `2008-04-14`
  **NeKI brief:** Pointer type punning can violate aliasing and representation assumptions, producing compiler-dependent bugs. Use a union or controlled byte-level conversion when reinterpretation is unavoidable, and never assume visually similar structs are safely interchangeable in memory.
- [Supersequent implementation | Cocoa with Love](https://www.cocoawithlove.com/2008/03/supersequent-implementation.html) — Cocoa with Love · article catalogue
  **Published:** `2008-03-30`
  **NeKI brief:** Category method overrides and swizzling complicate reaching the implementation that previously handled a selector. A supersequent technique can traverse that chain, but it relies on runtime internals and should remain a constrained compatibility tool rather than normal dispatch.
- [Break into Debugger | Cocoa with Love](https://www.cocoawithlove.com/2008/03/break-into-debugger.html) — Cocoa with Love · article catalogue
  **Published:** `2008-03-09`
  **NeKI brief:** A platform-aware DebugBreak macro deliberately traps at the caller's source line, avoiding an extra helper-frame detour during diagnosis. Guard such diagnostics for development builds and architectures so debugging instrumentation never becomes production behavior.
- [mikeash.com: Friday Q&A 2010-12-31: C Macro Tips and Tricks](https://www.mikeash.com/pyblog/friday-qa-2010-12-31-c-macro-tips-and-tricks.html) — Mike Ash · article catalogue
  **NeKI brief:** C macros operate on tokens before type checking, so parenthesize parameters and the whole expansion, avoid repeated evaluation, and reserve macros for cases where functions or generics cannot express the requirement.
- [mikeash.com: Friday Q&A 2009-08-21: Writing Vararg Macros and Functions](https://www.mikeash.com/pyblog/friday-qa-2009-08-21-writing-vararg-macros-and-functions.html) — Mike Ash · article catalogue
  **NeKI brief:** Varargs APIs require an explicit convention for count, terminator, or format-driven types; use `va_list` correctly, and prefer typed collections or wrappers when callers need compiler-checked arguments.
- [Migrating to the Observation framework in SwiftUI](https://tanaschita.com/swiftui-observation-migrating-to-observation) — Tanaschita · article catalogue
  **NeKI brief:** Walks through migrating SwiftUI models from ObservableObject to Observation, including property wrappers and ownership changes. Useful for an incremental migration that keeps view dependencies testable.
- [Quick developer guide on SwiftData for iOS](https://tanaschita.com/swiftdata-quick-developer-guide) — Tanaschita · article catalogue
  **NeKI brief:** Introduces SwiftData's macro-driven model and container setup, useful for understanding the framework's declarative persistence surface before selecting migration or architectural boundaries.
- [How to define one-to-many relationships in SwiftData](https://tanaschita.com/swiftdata-one-to-many-relationships) — Tanaschita · article catalogue
  **NeKI brief:** Defines SwiftData one-to-many relationships with @Relationship, highlighting ownership and delete-rule decisions that determine graph consistency during mutation and migration.
- [How to manually subscribe to changes of SwiftUI's @Observable objects](https://tanaschita.com/20230822-observation-framework-subscribe-to-changes) — Tanaschita · article catalogue
  **NeKI brief:** Observation allows manual subscription to changes from @Observable models. Follow it to understand registrar-driven updates and when explicit observation is justified instead of relying on SwiftUI’s automatic tracking.
- [How to import Objective-C types as optionals or non-optionals into Swift](https://tanaschita.com/20230130-nullability-declarations-objective-c) — Tanaschita · article catalogue
  **NeKI brief:** Objective-C nullability annotations determine whether imported Swift values are optional. Follow it when maintaining mixed-language frameworks, where accurate headers prevent defensive unwraps and incorrect non-optional assumptions.

## Newsletter and related leads

- [Splitting Large SwiftUI Views in the Apple's way](https://emredegirmenci.substack.com/p/splitting-large-swiftui-views-in) — SwiftUI Weekly · SwiftUI Weekly - Issue #238 — Article · Topics: Macros & Metaprogramming · Swift · SwiftUI
  **Published:** `2026-07-13T20:46:02.053Z`
  **NeKI brief:** Explains Apple's own decomposition techniques for splitting large SwiftUI views, including state and builder boundaries. Useful for reducing oversized bodies while keeping data flow explicit, previewable, and understandable to teammates.
- [Swift Macros Demystified: Build A Freestanding Expression Macro](https://www.youtube.com/watch?v=7W6R2TIoEW8) — Those Who Swift · Issue 272 — Video · Topics: Macros & Metaprogramming · Swift
  **Published:** `2026-06-24`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [SwiftUI: Observable macro under the hood](https://www.nsvasilev.com/posts/swiftui-observable-macro) — SwiftLee Weekly · Issue 329 — Article · Topics: Macros & Metaprogramming · Swift · SwiftUI
  **Published:** `2026-06-23T14:07:47.000Z`
  **NeKI brief:** Peels back SwiftUI’s Observable macro expansion, showing the generated observation machinery behind an @Observable model. Useful when diagnosing tracking behavior, deciding which properties need observation, or explaining macro-generated code to a team.
- [SwiftUI’s @State is now a macro](https://livsycode.com/swiftui/swiftuis-state-is-now-a-macro) — Fatbobman’s Swift Weekly · Issue 140 — Article · Topics: Macros & Metaprogramming · Swift · SwiftUI
  **Published:** `2026-06-15T12:03:17.597Z`
  **NeKI brief:** Explains SwiftUI's newer macro-based state capabilities and their effect on view-state declarations. Use it when evaluating whether an existing property-wrapper pattern can be simplified without changing ownership or lifecycle semantics.
- [SwiftMCP](https://github.com/Cocoanetics/SwiftMCP.git) — Fatbobman’s Swift Weekly · Issue 131 — Source repository · Topics: AI Development · App Intents & System Surfaces · Swift
  **Published:** `2026-04-13T12:03:12.522Z`
  **NeKI brief:** SwiftMCP uses Swift macros to build MCP servers and map App Intents into agent-callable tools. Use it when exposing existing app capabilities to agents while retaining a typed, auditable declaration of each operation.
- [Why Your @Observable Class init() Runs Multiple Times in SwiftUI](https://livsycode.com/swiftui/why-your-observable-class-init-runs-multiple-times-in-swiftui) — SwiftLee Weekly · Issue 312 — Article · Topics: Observation & State Management · Swift · SwiftUI
  **Published:** `2026-02-24T15:08:55.000Z`
  **NeKI brief:** Investigates why an @Observable class initializer can run repeatedly in SwiftUI. Follow it when diagnosing ownership and identity mistakes, checking observation lifetime, view reconstruction, and the distinction between initialization and persistent model state.
- [Swon](https://github.com/keeshux/swon) — iOS Dev Tools · iOS Dev Tools: ObjectBox, RIB, Swon — Source repository · Topics: Developer Tools · Foundation & Data Formats · Macros & Metaprogramming
  **Published:** `2025-12-04T17:28:54.311Z`
  **NeKI brief:** SWON uses Swift macros to generate JSON initializers for value types without Codable or Foundation, backed by cJSON and targeting Apple, Linux, Windows, and embedded environments. It is useful when minimizing runtime and framework dependencies in data parsing.
- [Swift Macros From 0 to Hero](https://levelup.gitconnected.com/swift-macros-from-0-to-hero-0-01-2ff3eac8571a) — Those Who Swift · Issue 242 — Tutorial · Topics: Developer Tools · Macros & Metaprogramming · Swift
  **Published:** `2025-11-26`
  **NeKI brief:** Examines Swift Macros From 0 to Hero, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Introducing Temporal Swift SDK: Building Durable Workflows](https://www.swift.org/blog/swift-temporal-sdk) — Those Who Swift · Issue 240 — Article · Topics: Concurrency · Macros & Metaprogramming · Swift
  **Published:** `2025-11-12`
  **NeKI brief:** Introduces a Temporal SDK for Swift and explains how Swift code can define durable workflows. Follow it when assessing workflow orchestration, persistence, retries, and deployment boundaries for server-side or long-running Swift services.
- [Building SyntaxKit](https://brightdigit.com/tutorials/syntaxkit-swift-code-generation) — iOS Dev Weekly · Issue 729 — Tutorial · Topics: Developer Tools · Macros & Metaprogramming · Swift
  **Published:** `3rd October 2025`
  **NeKI brief:** Presents building syntaxkit for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Leo Dion](https://c.im/@leogdion) — iOS Dev Weekly · Issue 729 — Article · Topics: Macros & Metaprogramming · Testing
  **Published:** `3rd October 2025`
  **NeKI brief:** Presents leo dion for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Swift Macros in the Wild: Building Reusable SwiftUI Views with @expression](https://medium.com/%40wesleymatlock/swift-macros-in-the-wild-building-reusable-swiftui-views-with-expression-99a321b54693) — Those Who Swift · Issue 223 — Article · Topics: Macros & Metaprogramming · Swift · SwiftUI
  **Published:** `2025-07-16`
  **NeKI brief:** Examines Swift Macros in the Wild: Building Reusable SwiftUI Views with @expression, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Four Months in the Making: SwiftMCP 1.0 is Here](https://www.cocoanetics.com/2025/07/four-months-in-the-making-swiftmcp-1-0-is-here) — SwiftLee Weekly · Issue 280 — Article · Topics: AI Development · Objective-C & Cocoa · Swift
  **Published:** `2025-07-15T14:13:29.000Z`
  **NeKI brief:** Presents Four Months in the Making: SwiftMCP 1.0 is Here, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Developer experience wins from WWDC25](https://tuist.dev/blog/2025/06/10/wwdc) — SwiftLee Weekly · Issue 275 — Article · Topics: Apple Platform Ecosystem · Macros & Metaprogramming · Testing
  **Published:** `2025-06-12T15:03:23.000Z`
  **NeKI brief:** Explains Developer experience wins from WWDC25, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Automatic SwiftUI View Tracing with Swift Macros](https://medium.com/@alexandercohen/how-we-built-a-swift-macro-that-automatically-wraps-any-swiftui-view-no-more-manual-f5761376f923) — SwiftLee Weekly · Issue 274 — Article · Topics: Macros & Metaprogramming · Swift · SwiftUI
  **Published:** `2025-06-03T14:11:29.000Z`
  **NeKI brief:** Presents Automatic SwiftUI View Tracing with Swift Macros, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Modern URL construction in Swift](https://www.swiftbysundell.com/articles/modern-url-construction-in-swift?ref=createwithswift.com) — Create with Swift · Issue 55 — Article · Topics: Foundation & Data Formats · Swift
  **Published:** `2025-04-04T15:49:40.000Z`
  **NeKI brief:** Builds URLs with modern Foundation components rather than string concatenation. Use it when paths, query items, and percent encoding must remain correct under optional or user-provided values.
- [Custom environment values in SwiftUI](https://nilcoalescing.com/blog/CustomEnvironmentValuesInSwiftUI?ref=createwithswift.com) — Create with Swift · Issue 52 — Article · Topics: Macros & Metaprogramming · Swift · SwiftUI
  **Published:** `2025-03-14T17:00:20.000Z`
  **NeKI brief:** Compares the pre-Xcode 16 pattern for defining SwiftUI environment keys with the @Entry macro, then shows how values flow through a view hierarchy.
- [Replacing EnvironmentKit with the new SwiftUI Entry macro](https://danielsaidi.com/blog/2025/01/11/replacing-environmentkit-with-the-entry-macro) — Those Who Swift · Issue 198 — Article · Topics: Macros & Metaprogramming · Swift · SwiftUI
  **Published:** `2025-01-23`
  **NeKI brief:** Examines Replacing EnvironmentKit with the new SwiftUI Entry macro, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Preview SwiftUI views with bindings using @Previewable](https://nilcoalescing.com/blog/PreviewSwiftUIViewsWithBindings?ref=createwithswift.com) — Create with Swift · Issue 36 — Article · Topics: Observation & State Management · Swift · SwiftUI
  **Published:** `2024-11-15T15:53:25.000Z`
  **NeKI brief:** Shows how Xcode 16's @Previewable macro supplies local mutable state so SwiftUI previews can exercise views that require bindings.
- [Introducing Swift Testing. Basics.](https://swiftwithmajid.com/2024/10/22/introducing-swift-testing-basics?ref=createwithswift.com) — Create with Swift · Issue 34 — Article · Topics: Macros & Metaprogramming · Swift · Testing
  **Published:** `2024-11-01T19:30:40.000Z`
  **NeKI brief:** Introduces Swift Testing's test declarations, expectations, and setup model. Useful as a migration starting point when replacing XCTest boilerplate while keeping behavioral assertions readable.
- [Swift-CowBox](https://github.com/Swift-CowBox/Swift-CowBox) — Fatbobman’s Swift Weekly · Issue 54 — Source repository · Topics: Developer Tools · Macros & Metaprogramming · Swift
  **Published:** `2024-10-21T12:03:34.069Z`
  **NeKI brief:** Swift-CowBox uses macros and copy-on-write wrappers to provide value-like behavior for reference-backed storage. Follow it when performance-sensitive models need controlled mutation semantics without duplicating large buffers.
- [UserDefaults and Observation in SwiftUI: How to Achieve Precise Responsiveness](https://fatbobman.com/en/posts/userdefaults-and-observation?ref=createwithswift.com) — Create with Swift · Issue 31 — Article · Topics: Observation & State Management · Swift · SwiftUI
  **Published:** `2024-10-11T15:30:29.000Z`
  **NeKI brief:** Observation does not automatically make UserDefaults changes precise inside SwiftUI. The @ObservableDefaults approach bridges key reads and writes into tracked properties, avoiding broad invalidation while retaining UserDefaults persistence semantics.
- [How to listen for property changes in an @Observable class using AsyncStreams](https://www.polpiella.dev/observable-property-changes?ref=createwithswift.com) — Create with Swift · Issue 31 — Article · Topics: Concurrency · Observation & State Management · Swift
  **Published:** `2024-10-11T15:30:29.000Z`
  **NeKI brief:** AsyncStream can bridge Observation changes into an async consumer, replacing ObservableObject publishers while preserving cancellation and backpressure decisions. The comparison clarifies when a stream should be scoped to a task and when direct observation is simpler.
- [Using @DebugDescription in Xcode 16](https://digitalbunker.dev/debug-description-macro-xcode-16?ref=createwithswift.com) — Create with Swift · Issue 23 — Article · Topics: Developer Tools · Macros & Metaprogramming · Xcode
  **Published:** `2024-07-26T15:00:26.000Z`
  **NeKI brief:** Presents using @debugdescription in xcode 16 for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Using @DebugDescription in Xcode 16](https://digitalbunker.dev/debug-description-macro-xcode-16) — iOS Dev Weekly · Issue 671 — Article · Topics: Developer Tools · Macros & Metaprogramming · Xcode
  **Published:** `26th July 2024`
  **NeKI brief:** Presents using @debugdescription in xcode 16 for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Xcode 16’s Entry macro](https://www.donnywals.com/adding-values-to-the-swiftui-environment-with-xcode-16s-entry-macro) — iOS Dev Weekly · Issue 670 — Article · Topics: Macros & Metaprogramming · Swift · SwiftUI
  **Published:** `19th July 2024`
  **NeKI brief:** Presents xcode 16’s entry macro for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [@Previewable: Dynamic SwiftUI Previews Made Easy](https://www.avanderlee.com/swiftui/previewable-macro-usage-in-previews?ref=createwithswift.com) — Create with Swift · Issue 17 — Article · Topics: Macros & Metaprogramming · Swift · SwiftUI
  **Published:** `2024-06-14T15:15:32.000Z`
  **NeKI brief:** Explains how @Previewable works in Xcode 16 and uses it to make SwiftUI previews interactive without adding preview-only state to production views.
- [Getting started with Swift Testing](https://www.polpiella.dev/swift-testing?ref=createwithswift.com) — Create with Swift · Issue 17 — Article · Topics: Swift · Testing
  **Published:** `2024-06-14T15:15:32.000Z`
  **NeKI brief:** Introduces Swift Testing in the Swift 6 toolchain, then maps representative XCTest cases to the macro-based test and expectation APIs.
- [Flora Damiano](https://www.behance.net/FloraDamiano) — Fatbobman’s Swift Weekly · Issue 15 — Article · Topics: Macros & Metaprogramming · Observation & State Management · Swift
  **Published:** `2024-01-15T22:00:34.609Z`
  **NeKI brief:** Flora Damiano's portfolio showcases visual and interaction design work. Use it as a design reference when discussing visual language, illustration, and product presentation rather than as an engineering source.
- [Questions about the data to create LLMs for embeddings](https://rhonabwy.com/2023/11/15/questions-about-the-data-to-create-llms-for-embeddings) — Fatbobman’s Swift Weekly · Issue 7 — Article · Topics: AI Development · Architecture · Swift
  **Published:** `2023-11-20T22:20:48.455Z`
  **NeKI brief:** Raises practical questions about collecting and preparing data for embedding-oriented language models. Follow it when designing retrieval datasets and evaluating provenance, chunking, quality, and privacy rather than treating embeddings as a drop-in search feature.
- [XCTestParametrizedMacro](https://github.com/PGSSoft/XCTestParametrizedMacro) — iOS Dev Tools · 🔨 MotionScape, XCTestParametrizedMacro, Swiftly — Source repository · Topics: Developer Tools · Macros & Metaprogramming · Testing
  **Published:** `2023-11-16T15:47:07.018Z`
  **NeKI brief:** XCTestParametrizedMacro uses a Swift macro to expand a parameterized test into concrete XCTest cases. Use it to reduce duplicated test bodies while preserving separately reported inputs and failures in an XCTest-based suite.
- [discussion](https://forums.swift.org/t/macro-adoption-concerns-around-swiftsyntax/66588) — Fatbobman’s Swift Weekly · Issue 3 — Article · Topics: Macros & Metaprogramming · Swift
  **Published:** `2023-10-23T22:30:20.902Z`
  **NeKI brief:** Discusses SwiftSyntax adoption concerns around macro development, including dependency size and version coupling. Useful when deciding whether a macro's build and maintenance costs fit a project.
- [Apple’s use of Swift and SwiftUI in iOS 17](https://blog.timac.org/2023/1019-state-of-swift-and-swiftui-ios17) — Fatbobman’s Swift Weekly · Issue 3 — Article · Topics: Macros & Metaprogramming · Swift · SwiftUI
  **Published:** `2023-10-23T22:30:20.902Z`
  **NeKI brief:** Reviews Swift and SwiftUI changes around iOS 17 with implementation context. Use it to orient migration work and identify which new APIs affect deployment targets or existing view architecture.
- [Introducing ObservableConverter](https://lickability.com/blog/introducing-observableconverter) — iOS Dev Weekly · Issue 624 — Article · Topics: Macros & Metaprogramming · Swift
  **Published:** `25th August 2023`
  **NeKI brief:** Explores Introducing ObservableConverter, focusing on apple has a well-written guide and some sample code for migrating from the observable object protocol to the new observable macro, but. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Automating Memory Leak Detection with XCTest](https://qualitycoding.org/swift-memory-leak-detection-xctest) — iOS Dev Weekly · Issue 623 — Article · Topics: Macros & Metaprogramming · Swift · Testing
  **Published:** `18th August 2023`
  **NeKI brief:** Explores Automating Memory Leak Detection with XCTest, focusing on what a clever technique written up by dan torres for. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Swift Macros](https://www.youtube.com/playlist?list=PLlc_rDuPW0Y2Z2T1Dv-je_fG1ZQyIhehi) — iOS Dev Weekly · Issue 620 — Video · Topics: Graphics, Media & Games · Macros & Metaprogramming · Swift
  **Published:** `28th July 2023`
  **NeKI brief:** Uses State, Binding, ObservableObject, StateObject, and EnvironmentObject in practical SwiftUI data-flow examples. Follow it to compare ownership and propagation choices when a view hierarchy has multiple sources of mutable state.
- [SwiftUI Data Flow in iOS 17 - Observation](https://www.youtube.com/watch?v=EK7SthdWV2w) — SwiftUI Weekly · SwiftUI Weekly - Issue #148 — Video · Topics: Graphics, Media & Games · Macros & Metaprogramming · Observation & State Management
  **Published:** `2023-06-28T11:49:47.378Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Swift-Macros: A curated list of awesome Swift Macros](https://github.com/krzysztofzablocki/Swift-Macros) — iOS Dev Weekly · Issue 614 — Source repository · Topics: Developer Tools · Macros & Metaprogramming · Swift
  **Published:** `16th June 2023`
  **NeKI brief:** Explores Swift-Macros: A curated list of awesome Swift Macros, focusing on the article discusses want to write something more detailed about. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Introducing Swift Power Assert](https://forums.swift.org/t/introducing-swift-power-assert/64197) — iOS Dev Weekly · Issue 604 — Article · Topics: Macros & Metaprogramming · Swift
  **Published:** `7th April 2023`
  **NeKI brief:** Explores Introducing Swift Power Assert, focusing on the article discusses love the idea behind this new library. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [macro support in Swift](https://github.com/apple/swift-evolution/blob/main/proposals/0382-expression-macros.md) — iOS Dev Weekly · Issue 604 — Source repository · Topics: Developer Tools · Macros & Metaprogramming · Swift
  **Published:** `7th April 2023`
  **NeKI brief:** Explores macro support in Swift, focusing on the article discusses love the idea behind this new library. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Converting Complex Objective-C Macros to Swift Functions](http://www.andrewcbancroft.com/2015/01/29/converting-complex-objective-c-macros-swift-functions) — iOS Dev Weekly · Issue 183 — Article · Topics: Macros & Metaprogramming · Objective-C & Cocoa · Swift
  **Published:** `30th January 2015`
  **NeKI brief:** Explains Converting Complex Objective-C Macros to Swift Functions with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [SQKeyPath](https://gist.github.com/kyleve/8213806) — iOS Dev Weekly · Issue 127 — Source repository · Topics: Developer Tools · Macros & Metaprogramming
  **Published:** `3rd January 2014`
  **NeKI brief:** Provides the SQKeyPath source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [AGAsyncTestHelper](https://github.com/hfossli/AGAsyncTestHelper) — iOS Dev Weekly · Issue 109 — Source repository · Topics: Concurrency · Developer Tools · Testing
  **Published:** `30th August 2013`
  **NeKI brief:** Provides the AGAsyncTestHelper source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Objective-C Generics](https://github.com/tomersh/Objective-C-Generics) — iOS Dev Weekly · Issue 103 — Source repository · Topics: Developer Tools · Macros & Metaprogramming · Objective-C & Cocoa
  **Published:** `19th July 2013`
  **NeKI brief:** Provides the Objective-C Generics source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Down with Magic Strings](http://www.cimgf.com/2013/01/29/down-with-magic-strings) — iOS Dev Weekly · Issue 79 — Article · Topics: Macros & Metaprogramming
  **Published:** `1st February 2013`
  **NeKI brief:** Explains Down with Magic Strings with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [sneak preview of the new macros they’re working on](https://www.youtube.com/live/sfWYh-oxk8k?si=NLmSS8NcHtEUadXe&t=4877) — Not only Swift · Issue 87 — Video · Topics: AI Development · Macros & Metaprogramming · Swift
  **NeKI brief:** Links to a public video about sneak preview of the new macros they’re working on. Use the talk for practitioner context and demonstrations, then verify platform behavior, API availability, and recommended production practices in current primary documentation.
