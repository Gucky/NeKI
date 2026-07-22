# Combine & Reactive Programming

Third-party reading leads collected from NeKI sources. The links may be useful perspectives, but are not vetted recommendations or authoritative API guidance. NeKI publishes routing metadata, not the linked articles' text.

**Scope:** Combine publishers, subscribers, operators, and reactive-programming techniques.

- Last collected: `2026-07-22T21:56:49Z`
- Indexed links shown: **95**

## Direct-source reading

- [Implement your Data Access Layer with Combine](https://blog.jacobstechtavern.com/p/implement-your-data-access-layer) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2023-08-15T08:15:19.237Z`
  **NeKI brief:** Separates what data an app needs from how a network or cache retrieves it, then composes repository operations with Combine publishers. Follow it when introducing a data-access boundary that can swap sources and remain mockable in asynchronous tests.
- [What exactly is a Combine AnyCancellable? – Donny Wals](https://www.donnywals.com/what-exactly-is-a-combine-anycancellable) — Donny Wals · article catalogue
  **Published:** `2021-08-24T18:27:21+00:00`
  **NeKI brief:** AnyCancellable cancels a Combine subscription on deinitialization, so retaining it defines subscription lifetime and prevents publishers from stopping immediately.
- [Configuring error types when using flatMap in Combine – Donny Wals](https://www.donnywals.com/configuring-error-types-when-using-flatmap-in-combine) — Donny Wals · article catalogue
  **Published:** `2020-09-14T07:00:07+00:00`
  **NeKI brief:** Combine flatMap must reconcile upstream and inner publisher failure types, so mapping errors deliberately preserves a coherent pipeline contract.
- [Ignore first number of elements from a publisher in Combine – Donny Wals](https://www.donnywals.com/ignore-first-number-of-elements-from-a-publisher-in-combine) — Donny Wals · article catalogue
  **Published:** `2020-06-19T09:44:19+00:00`
  **NeKI brief:** Combine drop operators suppress initial publisher emissions, useful when defaults should not trigger work while preserving later state transitions.
- [Recursively execute a paginated network call with Combine – Donny Wals](https://www.donnywals.com/recursively-execute-a-paginated-network-call-with-combine) — Donny Wals · article catalogue
  **Published:** `2020-06-15T07:15:40+00:00`
  **NeKI brief:** Recursive pagination chains each response into the next request until exhaustion, requiring cancellation, error propagation, and termination conditions to remain centralized.
- [What’s the difference between catch and replaceError in Combine? – Donny Wals](https://www.donnywals.com/whats-the-difference-between-catch-and-replaceerror-in-combine) — Donny Wals · article catalogue
  **Published:** `2020-05-29T08:53:29+00:00`
  **NeKI brief:** catch switches to a replacement publisher after failure, while replaceError emits a final fallback value; the choice determines whether a pipeline continues or completes.
- [Retrying a network request with a delay in Combine – Donny Wals](https://www.donnywals.com/retrying-a-network-request-with-a-delay-in-combine) — Donny Wals · article catalogue
  **Published:** `2020-05-25T07:00:01+00:00`
  **NeKI brief:** Delayed retries combine failure handling with scheduling, reducing immediate repeat traffic while requiring a bounded policy for persistent server errors.
- [Changing a publisher’s Failure type in Combine – Donny Wals](https://www.donnywals.com/changing-a-publishers-failure-type-in-combine) — Donny Wals · article catalogue
  **Published:** `2020-04-15T08:28:15+00:00`
  **NeKI brief:** Combine failure-type transformations adapt error contracts between publishers, allowing composition while preserving a deliberate distinction between impossible and recoverable failure.
- [Using map, flatMap and compactMap in Combine – Donny Wals](https://www.donnywals.com/using-map-flatmap-and-compactmap-in-combine) — Donny Wals · article catalogue
  **Published:** `2020-02-03T08:00:28+00:00`
  **NeKI brief:** Combine transformations either map values, flatten nested publishers, or remove absent values; selecting the right operator preserves the intended stream shape.
- [Updating UI with assign(to:on:) in Combine – Donny Wals](https://www.donnywals.com/updating-ui-with-assigntoon-in-combine) — Donny Wals · article catalogue
  **Published:** `2020-01-29T08:00:31+00:00`
  **NeKI brief:** assign(to:on:) connects publisher output to an object's property, but retention and main-thread delivery must be explicit when updating UIKit state.
- [Publishing property changes in Combine – Donny Wals](https://www.donnywals.com/publishing-property-changes-in-combine) — Donny Wals · article catalogue
  **Published:** `2020-01-27T08:00:23+00:00`
  **NeKI brief:** Subjects and property publishers expose state changes as streams, allowing composition while requiring clear ownership of who may mutate the source.
- [Understanding Combine’s publishers and subscribers – Donny Wals](https://www.donnywals.com/understanding-combines-publishers-and-subscribers) — Donny Wals · article catalogue
  **Published:** `2020-01-13T07:30:56+00:00`
  **NeKI brief:** Publishers describe values and completion while subscribers receive demand-aware events, establishing the ownership and backpressure vocabulary behind Combine pipelines.
- [TopLevelEncoder and TopLevelDecoder in Combine – Ole Begemann](https://oleb.net/2020/topleveldecoder) — Ole Begemann · article catalogue
  **Published:** `2020-01-08T00:08:41Z`
  **NeKI brief:** Combine's TopLevelEncoder and TopLevelDecoder protocols describe encoders that operate on a complete value rather than a keyed container. Their placement in Combine reflects publisher integration, while the generic abstraction remains useful across serialization formats.
- [Getting started with Combine – Donny Wals](https://www.donnywals.com/an-introduction-to-combine) — Donny Wals · article catalogue
  **Published:** `2020-01-06T08:10:33+00:00`
  **NeKI brief:** Combine models asynchronous values as composable publisher chains, but subscriptions, cancellation, schedulers, and failure types remain essential design choices.
- [Building flexible components with generics and protocols – Donny Wals](https://www.donnywals.com/building-flexible-components-with-generics-and-protocols) — Donny Wals · article catalogue
  **Published:** `2019-11-11T08:00:22+00:00`
  **NeKI brief:** Generics plus protocol constraints express flexible components with required capabilities, but associated-type relationships can complicate heterogeneous storage and API-erasure decisions.
- [A visual cheat sheet of Combine operators](https://tanaschita.com/combine-operators-cheatsheet) — Tanaschita · article catalogue
  **NeKI brief:** Maps common Combine operators to transformations, filtering, combination, and scheduling behavior. Follow it when refactoring a publisher pipeline and needing to choose an operator by demand semantics rather than memorized names.
- [How to use a Connectable publisher in Combine](https://tanaschita.com/combine-connectable-publisher) — Tanaschita · article catalogue
  **NeKI brief:** Connectable publishers defer emission until explicitly connected, giving callers control over start timing. Follow it when multiple subscribers must observe one shared sequence without triggering duplicate upstream work.

## Newsletter and related leads

- [Release 4.0.0 · AvdLee/SwiftUI-Agent-Skill](https://github.com/AvdLee/SwiftUI-Agent-Skill/releases/tag/4.0.0) — SwiftLee Weekly · Issue 328 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2026-06-16T14:06:32.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Release 4.0.0 · AvdLee/SwiftUI-Agent-Skill. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [A floating card using safeAreaBarBuilding a floating card component using iOS 26’s safeAreaBar with an iOS 18 fallbackCodakuma](https://codakuma.com/floating-safe-area-bar?ref=createwithswift.com) — Create with Swift · Issue 109 — Article · Topics: Combine & Reactive Programming · Swift · SwiftUI
  **Published:** `2026-05-29T16:00:08.000Z`
  **NeKI brief:** Creates a floating bar with SwiftUI’s safeAreaBar modifier, keeping controls attached to safe-area edges as content scrolls. Useful for persistent actions or playback controls without manual inset calculations and overlay hit-testing.
- [An Xcode Agent Prompt: What It Signals for Combine and RxSwift](https://livsycode.com/blog/an-xcode-agent-prompt-what-it-signals-for-combine-and-rxswift) — SwiftLee Weekly · Issue 310 — Article · Topics: Combine & Reactive Programming · Swift · Xcode
  **Published:** `2026-02-10T15:14:11.000Z`
  **NeKI brief:** Presents An Xcode Agent Prompt: What It Signals for Combine and RxSwift, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [AcceptedSE-0502Exclude private initialized properties from memberwise initializer](https://github.com/apple/swift-evolution/blob/main/proposals/0502-exclude-private-from-memberwise-init.md) — SwiftLee Weekly · Issue 310 — Source repository · Topics: Combine & Reactive Programming · Developer Tools · Swift
  **Published:** `2026-02-10T15:14:11.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0502Exclude private initialized properties from memberwise initializer. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0511SwiftPM Add Target Plugin Command](https://github.com/apple/swift-evolution/blob/main/proposals/0511-swiftpm-add-target-plugin.md) — SwiftLee Weekly · Issue 310 — Source repository · Topics: Combine & Reactive Programming · Developer Tools · Swift
  **Published:** `2026-02-10T15:14:11.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0511SwiftPM Add Target Plugin Command. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Creating and Introducing AsyncSharedStream](https://medium.com/the-swift-cooperative/creating-and-introducing-asyncsharedstream-3e9185317a5a) — Those Who Swift · Issue 250 — Article · Topics: Combine & Reactive Programming · Concurrency · Swift
  **Published:** `2026-01-21`
  **NeKI brief:** Introduces an AsyncSharedStream abstraction for sharing asynchronous events among consumers. Follow it when evaluating fan-out stream design, cancellation, buffering, and termination semantics instead of assuming AsyncStream alone defines the desired policy.
- [Approachable Concurrency in Swift 6.2: A Clear Guide](https://youtu.be/y_Qc8cT-O_g?si=W2ExWkL4BbMjT8cH) — SwiftLee Weekly · Issue 298 — Video · Topics: Combine & Reactive Programming · Concurrency · Swift
  **Published:** `2025-11-18T19:03:17.000Z`
  **NeKI brief:** Presents Approachable Concurrency in Swift 6.2: A Clear Guide as a practical video walkthrough or discussion. Use it when visual demonstration, live tooling, or spoken context helps evaluate the technique, then verify APIs and version-specific claims independently.
- [Combine Annotations and Swift Concurrency](https://www.massicotte.org/combine-annotations) — Those Who Swift · Issue 239 — Article · Topics: Combine & Reactive Programming · Concurrency · Swift
  **Published:** `2025-11-05`
  **NeKI brief:** Explains The Problem With Combine Annotations, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [AsyncBroadcastSequence](https://forums.swift.org/t/swift-async-algorithms-proposal-broadcast-previously-shared/61210) — Fatbobman’s Swift Weekly · Issue 108 — Article · Topics: Combine & Reactive Programming · Concurrency · Swift
  **Published:** `2025-10-27T12:02:17.397Z`
  **NeKI brief:** Proposes AsyncBroadcastSequence for sharing async values among consumers with cached history, backpressure, and lifecycle policy. Follow it when one producer must fan out events without reimplementing a Combine-style relay.
- [AsyncCombine](https://github.com/will-lumley/AsyncCombine) — Fatbobman’s Swift Weekly · Issue 108 — Source repository · Topics: Combine & Reactive Programming · Concurrency · Swift
  **Published:** `2025-10-27T12:02:17.397Z`
  **NeKI brief:** AsyncCombine bridges familiar Combine-style concepts into Swift concurrency, including relay-like state sharing. Use it to compare an interim async stream abstraction with the proposed AsyncBroadcastSequence and choose explicit buffering semantics.
- [Transforming Glass Views with the glassEffectID in SwiftUI](https://serialcoder.dev/text-tutorials/swiftui/transforming-glass-views-with-the-glasseffectid-modifier-in-swiftui) — SwiftLee Weekly · Issue 294 — Tutorial · Topics: Combine & Reactive Programming · Swift · SwiftUI
  **Published:** `2025-10-21T14:13:02.000Z`
  **NeKI brief:** Presents Transforming Glass Views with the glassEffectID in SwiftUI, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [AsyncSequence for Real-Time APIs](https://medium.com/@wesleymatlock/asyncsequence-for-real-time-apis-from-legacy-polling-to-swift-6-elegance-c2b8139c21e0) — Those Who Swift · Issue 234 — Article · Topics: Combine & Reactive Programming · Concurrency · Swift
  **Published:** `2025-10-01`
  **NeKI brief:** Examines AsyncSequence for Real-Time APIs, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [We Need to Talk About Observation](https://jaredsinclair.com/2025/09/10/observation.html) — SwiftLee Weekly · Issue 289 — Article · Topics: Combine & Reactive Programming · Cross-Platform & Web · Testing
  **Published:** `2025-09-16T14:09:42.000Z`
  **NeKI brief:** Explains We Need to Talk About Observation, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [OpenSwiftUI](https://github.com/OpenSwiftUIProject/OpenSwiftUI) — Fatbobman’s Swift Weekly · Issue 99 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2025-08-25T12:03:32.117Z`
  **NeKI brief:** OpenSwiftUI is a community reimplementation useful for studying declarative view behavior and framework boundaries. Follow it for comparative exploration, not as a drop-in substitute for Apple's implementation guarantees.
- [Four Months in the Making: SwiftMCP 1.0 is Here](https://www.cocoanetics.com/2025/07/four-months-in-the-making-swiftmcp-1-0-is-here) — SwiftLee Weekly · Issue 280 — Article · Topics: AI Development · Objective-C & Cocoa · Swift
  **Published:** `2025-07-15T14:13:29.000Z`
  **NeKI brief:** Presents Four Months in the Making: SwiftMCP 1.0 is Here, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [swift-async-algorithms](https://github.com/apple/swift-async-algorithms) — Fatbobman’s Swift Weekly · Issue 90 — Source repository · Topics: Combine & Reactive Programming · Concurrency · Swift
  **Published:** `2025-06-23T12:02:42.068Z`
  **NeKI brief:** swift-async-algorithms adds reusable asynchronous sequence operators and utilities for Swift concurrency. Use it when async/await code needs throttling, merging, buffering, or other stream composition without reintroducing a full Combine pipeline.
- [OAuthKit](https://github.com/codefiesta/OAuthKit) — iOS Dev Tools · iOS Dev Tools: AI Git Narrator, OAuthKit, FlipKit — Source repository · Topics: Architecture · Combine & Reactive Programming · Swift
  **Published:** `2025-06-12T19:41:45.540Z`
  **NeKI brief:** OAuthKit provides an observable Swift framework for OAuth 2.0 authorization flows, centralizing state and callback handling. Useful for comparing a reusable authentication boundary with endpoint-specific browser-session code.
- [SE-475: Transactional Observation of Values](https://github.com/swiftlang/swift-evolution/blob/main/proposals/0475-observed.md) — SwiftLee Weekly · Issue 272 — Source repository · Topics: Combine & Reactive Programming · Developer Tools · Swift
  **Published:** `2025-05-20T14:12:58.000Z`
  **NeKI brief:** Provides the public source repository for SE-0475. Inspect its implementation, examples, and issue history to evaluate integration boundaries and maintenance trade-offs before depending on it in an Apple-platform project.
- [Supercharge your GitHub Actions with fully managed M4 Pro runners from Cirrus Labs](https://cirrus-runners.app/) — iOS Dev Tools · iOS Dev Tools: FormattedListKit, Libraried, Pressdeck — Article · Topics: Combine & Reactive Programming · Developer Tools · Testing
  **Published:** `2025-04-17T13:23:18.210Z`
  **NeKI brief:** Describes managed M4 Pro runners for GitHub Actions workloads. Use it to evaluate faster macOS CI capacity, queue behavior, and cost before moving iOS builds to hosted hardware.
- [Does AsyncStream Replace Combine? No.](https://levelup.gitconnected.com/does-asyncstream-replace-combine-a4fc091a8175) — Those Who Swift · Issue 208 — Article · Topics: Combine & Reactive Programming · Concurrency · Developer Tools
  **Published:** `2025-04-02`
  **NeKI brief:** This article covers the boundary between AsyncStream and Combine. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [SwiftUI: Connect Two Points with Straight Line Segments + Rounded Corners](https://levelup.gitconnected.com/swiftui-connect-two-points-with-straight-line-segments-rounded-corners-dbbad5f27ab4) — Those Who Swift · Issue 206 — Article · Topics: Combine & Reactive Programming · Swift · SwiftUI
  **Published:** `2025-03-19`
  **NeKI brief:** Examines SwiftUI: Connect Two Points with Straight Line Segments + Rounded Corners, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [ViewList](https://github.com/OpenSwiftUIProject/OpenSwiftUI/tree/main/Sources/OpenSwiftUICore/View/Input) — Fatbobman’s Swift Weekly · Issue 71 — Source repository · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2025-02-17T23:25:21.639Z`
  **NeKI brief:** Points directly into OpenSwiftUI's input-related view sources rather than its repository root. Use it to inspect how an open implementation models input plumbing when debugging or comparing SwiftUI behavior.
- [OpenGraph](https://github.com/OpenSwiftUIProject/OpenGraph) — Fatbobman’s Swift Weekly · Issue 71 — Source repository · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2025-02-17T23:25:21.639Z`
  **NeKI brief:** OpenGraph is an OpenSwiftUI-adjacent graph implementation to study alongside view construction and dependency propagation. Follow it when investigating how declarative UI state can be represented and traversed outside Apple's closed framework.
- [Sharing GRDB](https://github.com/pointfreeco/sharing-grdb) — Fatbobman’s Swift Weekly · Issue 71 — Source repository · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2025-02-17T23:25:21.639Z`
  **NeKI brief:** SharingGRDB combines shared observable state with GRDB-backed SQLite persistence. Use it when SwiftUI features need low deployment targets and direct SQL control, noting that it does not provide mature cross-device synchronization.
- [SwiftUIKit](https://github.com/danielsaidi/SwiftUIKit) — Fatbobman’s Swift Weekly · Issue 63 — Source repository · Topics: Swift · SwiftUI · UIKit
  **Published:** `2024-12-23T12:01:34.355Z`
  **NeKI brief:** SwiftUIKit collects reusable UIKit helpers and extensions from Daniel Saidi's ecosystem. Use it as a source of focused implementation patterns when a project needs small UIKit conveniences without adopting a large UI framework.
- [HandySwiftUI](https://github.com/FlineDev/HandySwiftUI) — Fatbobman’s Swift Weekly · Issue 56 — Source repository · Topics: Combine & Reactive Programming · Swift · SwiftUI
  **Published:** `2024-11-04T12:02:30.932Z`
  **NeKI brief:** This source repository covers SwiftUI utilities that fill gaps in the framework. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [EarlGrey 2.0](https://github.com/google/EarlGrey/tree/earlgrey2) — iOS Dev Tools · iOS Dev Tools: LocationSimulator, EarlGrey 2.0, SwiftUI Introspect — Source repository · Topics: Combine & Reactive Programming · Developer Tools · Testing
  **Published:** `2024-05-09T15:35:40.691Z`
  **NeKI brief:** EarlGrey 2 combines synchronized white-box UI testing with XCUITest integration for iOS. Use it when black-box assertions cannot reliably wait for app idleness, while considering its framework and maintenance cost against native UI tests.
- [Injecting code in result builders](https://trycombine.com/posts/an-example-of-using-arbitrary-code-in-result-builders) — Fatbobman’s Swift Weekly · Issue 10 — Article · Topics: Combine & Reactive Programming · Dependency Injection
  **Published:** `2023-12-11T22:00:36.607Z`
  **NeKI brief:** Demonstrates injecting arbitrary code into result builders and explains how builder transformation rules affect control flow. Use it when designing custom DSLs and checking whether generated component structure remains readable and type-checkable.
- [Creating Shortcuts with App Intents](https://www.kodeco.com/40950083-creating-shortcuts-with-app-intents) — Fatbobman’s Swift Weekly · Issue 5 — Article · Topics: App Distribution & Store Operations · App Intents & System Surfaces · Combine & Reactive Programming
  **Published:** `2023-11-06T22:30:15.675Z`
  **NeKI brief:** Explains creating Shortcuts actions with App Intents and connecting typed app operations to system automation. Use it when exposing discoverable actions while checking entity modeling, parameter resolution, availability, and privacy boundaries.
- [Understanding Publishers in SwiftUI and Combine](https://medium.com/bumble-tech/understanding-publishers-in-swiftui-and-combine-27806aa78ba1) — SwiftUI Weekly · SwiftUI Weekly - Issue #161 — Article · Topics: Combine & Reactive Programming · Swift · SwiftUI
  **Published:** `2023-09-25T21:58:53.226Z`
  **NeKI brief:** Explains how Combine publishers feed SwiftUI updates and how asynchronous streams compose in an application. Useful when diagnosing event pipelines, selecting operators, and deciding where publisher ownership belongs in a view model.
- [Combine](https://www.swiftbysundell.com/discover/combine) — SwiftUI Weekly · SwiftUI Weekly - Issue #161 — Article · Topics: Combine & Reactive Programming · Swift · SwiftUI
  **Published:** `2023-09-25T21:58:53.226Z`
  **NeKI brief:** Collects Swift by Sundell's Combine material on publishers, operators, and reactive application design. Useful as a navigation hub when maintaining Combine code or comparing legacy pipelines with newer async/await implementations.
- [Explore the docs →](https://www.revenuecat.com/docs/paywalls) — iOS Dev Weekly · Issue 626 — Article · Topics: Combine & Reactive Programming · Testing
  **Published:** `8th September 2023`
  **NeKI brief:** RevenueCat documentation for configuring and presenting in-app paywalls through its SDK and dashboard tooling. Use it when evaluating a subscription implementation, validating entitlement flow choices, or integrating RevenueCat's paywall APIs into an Apple-platform app.
- [Asynchronous Programming with SwiftUI and Combine](https://link.springer.com/book/10.1007/978-1-4842-8572-5) — iOS Dev Weekly · Issue 595 — Article · Topics: Combine & Reactive Programming · Swift · SwiftUI
  **Published:** `3rd February 2023`
  **NeKI brief:** Explores Asynchronous Programming with SwiftUI and Combine, focusing on this new book from peter friese may not be trying. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [SwiftUI view modifier for paid app features](https://trycombine.com/posts/simple-view-modifier-to-handle-features-that-are-only-enabled-in-the-pro-version-of-the-app) — iOS Dev Weekly · Issue 588 — Article · Topics: Combine & Reactive Programming · Swift · SwiftUI
  **Published:** `9th December 2022`
  **NeKI brief:** Explores SwiftUI view modifier for paid app features, focusing on the article discusses love the idea of this swiftui view. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [launch blog post](https://trycombine.com/posts/datatile-for-simulator-public-beta-on-testflight-now) — iOS Dev Weekly · Issue 587 — Article · Topics: App Distribution & Store Operations · Combine & Reactive Programming · Developer Tools
  **Published:** `2nd December 2022`
  **NeKI brief:** Explores launch blog post, focusing on the article discusses don’t know about you, but i still. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Composition in TCA: Scope, Combine and Pullback operators](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyJnY9WmYycEZFYTN1ZXciLCJwb3N0X2lkIjoiNTAxNjg3MDctMTllNi00OWVjLWEzMGUtZDM0NTg5OGM5Mzk5IiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6ImJkOTY3MzY1LTVhYTAtNGIzOS05NWY0LTJhMGViNjgwNTJhMyIsImlhdCI6MTY3NDA2MjU1Ni45LCJpc3MiOiJvcmNoaWQifQ.oCLiQ-6M7I0rhyM9-07MqJd2m-21FbRxpLCYhEXIV-0) — SwiftUI Weekly · SwiftUI Weekly - Issue #121 — Article · Topics: Architecture · Combine & Reactive Programming · Composable Architecture
  **Published:** `2022-11-21T12:42:39.000Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [The Things They Don’t Tell You About Swift Concurrency](https://wojciechkulik.pl/ios/swift-concurrency-things-they-dont-tell-you) — iOS Dev Weekly · Issue 582 — Article · Topics: Combine & Reactive Programming · Concurrency · Swift
  **Published:** `28th October 2022`
  **NeKI brief:** Explores The Things They Don’t Tell You About Swift Concurrency, focusing on i’m not sure i particularly agree with the introduction of. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Pitfall of Nested ObservableObject](https://samwize.com/2022/09/30/pitfall-of-nested-observableobject) — iOS Dev Weekly · Issue 579 — Article · Topics: Combine & Reactive Programming · Observation & State Management · Swift
  **Published:** `7th October 2022`
  **NeKI brief:** Explores Pitfall of Nested ObservableObject, focusing on if you’ve worked with swiftui, you’ll likely have dealt with. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Using AsyncAlgorithms to close the gap on Combine](https://johnoreilly.dev/posts/swift-async-algorithms-combine) — iOS Dev Weekly · Issue 556 — Article · Topics: Combine & Reactive Programming · Concurrency · Swift
  **Published:** `29th April 2022`
  **NeKI brief:** Explores Using AsyncAlgorithms to close the gap on Combine, focusing on the article discusses enjoyed this post from john o’reilly talking. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Run iOS builds on M1, Intel or both with Orka](https://www.macstadium.com/orka) — iOS Dev Weekly · Issue 553 — Article · Topics: Combine & Reactive Programming · Testing
  **Published:** `8th April 2022`
  **NeKI brief:** Explores Accelerate Your iOS DevOps with Granular VM Control in Orka, focusing on orka 2.0 is now available and includes support for macos. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Introducing Swift Async Algorithms](https://www.swift.org/blog/swift-async-algorithms) — iOS Dev Weekly · Issue 552 — Article · Topics: Combine & Reactive Programming · Concurrency · Swift
  **Published:** `1st April 2022`
  **NeKI brief:** Explores Introducing Swift Async Algorithms, focusing on the article discusses mentioned it briefly in this week’s comment,. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Optimization in Swift](https://trycombine.com/posts/swift-performance-concurrency-1) — iOS Dev Weekly · Issue 550 — Article · Topics: Concurrency · Performance · Swift
  **Published:** `18th March 2022`
  **NeKI brief:** Explores Optimization in Swift, focusing on the article discusses enjoyed this four-part (1, 2, 3, and. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [2](https://trycombine.com/posts/swift-performance-concurrency-2) — iOS Dev Weekly · Issue 550 — Article · Topics: Combine & Reactive Programming · Concurrency · Performance
  **Published:** `18th March 2022`
  **NeKI brief:** Explores 2, focusing on the article discusses enjoyed this four-part (1, 2, 3, and 4) series of posts from marin todorov on optimising a concurrent filter. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [3](https://trycombine.com/posts/swift-performance-concurrency-3) — iOS Dev Weekly · Issue 550 — Article · Topics: Combine & Reactive Programming · Concurrency · Performance
  **Published:** `18th March 2022`
  **NeKI brief:** Explores 3, focusing on the article discusses enjoyed this four-part (1, 2, 3, and 4) series of posts from marin todorov on optimising a concurrent filter. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [4](https://trycombine.com/posts/swift-performance-concurrency-4) — iOS Dev Weekly · Issue 550 — Article · Topics: Combine & Reactive Programming · Concurrency · Performance
  **Published:** `18th March 2022`
  **NeKI brief:** Explores 4, focusing on the article discusses enjoyed this four-part (1, 2, 3, and 4) series of posts from marin todorov on optimising a concurrent filter. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Building a Camera App With SwiftUI and Combine](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy5yYXl3ZW5kZXJsaWNoLmNvbS8yNjI0NDc5My1idWlsZGluZy1hLWNhbWVyYS1hcHAtd2l0aC1zd2lmdHVpLWFuZC1jb21iaW5lP3V0bV9jYW1wYWlnbj1idWZmZXImdXRtX2NvbnRlbnQ9YnVmZmVyZDA5NDUmdXRtX21lZGl1bT1zb2NpYWwmdXRtX3NvdXJjZT10d2l0dGVyLmNvbSIsInBvc3RfaWQiOiJjMmZkZTdjMS00NjU0LTQ2ODctYWI0MC00NWEyNTI4NTVlMDUiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiOGUyZmQzNDUtYWJjYS00YTA5LThkYTMtNDE2NDVmNzA5OTJhIiwiaWF0IjoxNjc0MDYyNjE3LjcxNiwiaXNzIjoib3JjaGlkIn0.EYtjzcEt9k9qHn7Q5bQvobwNg9NVsUag7xF3x7v0QKc) — SwiftUI Weekly · SwiftUI Weekly - Issue #83 — Article · Topics: Combine & Reactive Programming · Graphics, Media & Games · Swift
  **Published:** `2021-11-15T14:19:45.000Z`
  **NeKI brief:** Builds a camera experience by bridging capture APIs into SwiftUI with Combine-backed state. Useful for understanding preview integration, authorization, capture events, and lifecycle management around UIKit services.
- [Thread.sleep() and Task.sleep()](https://trycombine.com/posts/thread-task-sleep) — iOS Dev Weekly · Issue 527 — Article · Topics: Combine & Reactive Programming · Concurrency · Swift
  **Published:** `1st October 2021`
  **NeKI brief:** Explores Thread.sleep() and Task.sleep(), focusing on it used to be a safe bet to stick to. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Swift Actors: A Practical Example](https://trycombine.com/posts/swift-actors) — iOS Dev Weekly · Issue 507 — Article · Topics: Combine & Reactive Programming · Concurrency · Swift
  **Published:** `14th May 2021`
  **NeKI brief:** Explores Swift Actors: A Practical Example, focusing on one of the new features coming in swift 5.5 is. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [2](https://trycombine.com/posts/swift-actors-combine) — iOS Dev Weekly · Issue 507 — Article · Topics: Combine & Reactive Programming · Concurrency · Swift
  **Published:** `14th May 2021`
  **NeKI brief:** Explores 2, focusing on one of the new features coming in swift 5.5 is language support for actors. what are actors? i’ll let marin todorov explain. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Abstracting Navigation in SwiftUI](https://obscuredpixels.com/abstracting-navigation-in-swiftui) — iOS Dev Weekly · Issue 506 — Article · Topics: Combine & Reactive Programming · Swift · SwiftUI
  **Published:** `7th May 2021`
  **NeKI brief:** Explores Abstracting Navigation in SwiftUI, focusing on the article discusses agree with omar that the mechanisms we. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Getting Started with Combine](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD9mZWF0dXJlPXlvdXR1LmJlJnV0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXImdj1YMm0wZjJOb0IxMCIsInBvc3RfaWQiOiI3NzBkNzMwYy05ZmNkLTRlOTItYWVjNi01YTJjOGM5YjcwZjgiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiYjIzMDBmZWMtNDg2NC00YTRjLWIzM2UtN2JiZDlmNTcwMjUwIiwiaWF0IjoxNjc0MDYyNjc4LjI0MiwiaXNzIjoib3JjaGlkIn0.yG7_Fvr4s6AVhNrkvo-hVvyg2Qj5YZhIkX4eTkhsyG4) — SwiftUI Weekly · SwiftUI Weekly - Issue #56 — Tutorial · Topics: App Distribution & Store Operations · Combine & Reactive Programming · Graphics, Media & Games
  **Published:** `2021-04-26T20:19:20.000Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Timer App Clone](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyJnY9cVNMdk5HaU5fcjAiLCJwb3N0X2lkIjoiMGYzMzljOTUtMzM2Ny00OGE5LWI4M2EtNzFlZjc0NjY3OGM2IiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6IjQ0YmNiZGM1LWZlMzMtNDA1ZC1hMDUzLTZlYzk0NDRiOTJiNyIsImlhdCI6MTY3NDA2MjY3OC4yMzgsImlzcyI6Im9yY2hpZCJ9.YKWs6zmCgJceKFjjkHQAcH_p5XFr2sI41lfv9Kg_sVg) — SwiftUI Weekly · SwiftUI Weekly - Issue #50 — Article · Topics: AI Development · Combine & Reactive Programming · Swift
  **Published:** `2021-03-15T20:06:20.000Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Core Store](https://dimsumthinking.com/Blog/2021/03/04-CoreStore.html) — iOS Dev Weekly · Issue 497 — Article · Topics: Combine & Reactive Programming · Core Data · Persistence & Synchronisation
  **Published:** `5th March 2021`
  **NeKI brief:** Examines Core Store, focusing on core data works well with new technologies like swiftui and combine, but does it feel at home with them? it does not. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Build a news app in SwiftUI 2.0 (Combine, API, MVVM & Swift Package Manager)](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyJnY9TTJwc1gtSndIZEUiLCJwb3N0X2lkIjoiZmI3YTliMDItOWZiMi00MWJkLTlhNGUtMzRjY2JjMzIzZjQxIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6IjA4NWFhZTc4LWY0ZGQtNDk1NS04MDA2LTQyZmIwYzcxMmNhNCIsImlhdCI6MTY3NDA2MjY3OC40MTksImlzcyI6Im9yY2hpZCJ9.9_MYRo5QPnk2BAP2P8aD_71Ckd92WPNekkK-uesvp78) — SwiftUI Weekly · SwiftUI Weekly - Issue #47 — Tutorial · Topics: Swift · Swift Package Manager · SwiftUI
  **Published:** `2021-02-23T19:43:19.000Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Combine and Swift Concurrency](https://rhonabwy.com/2020/11/08/combine-and-swift-concurrency) — iOS Dev Weekly · Issue 482 — Article · Topics: Combine & Reactive Programming · Concurrency · Swift
  **Published:** `13th November 2020`
  **NeKI brief:** Examines Combine and Swift Concurrency, offering practical guidance on networking and asynchronous reliability. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [about Combine](https://heckj.github.io/swiftui-notes) — iOS Dev Weekly · Issue 482 — Article · Topics: Combine & Reactive Programming · Concurrency · Swift
  **Published:** `13th November 2020`
  **NeKI brief:** Examines about Combine, offering practical guidance on networking and asynchronous reliability. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Nuke 9](https://kean.github.io/post/nuke-9) — iOS Dev Weekly · Issue 457 — Article · Topics: Combine & Reactive Programming · Developer Tools · Swift
  **Published:** `22nd May 2020`
  **NeKI brief:** Covers Nuke 9, focusing on Swift and Apple-platform engineering practice. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [Nuke](https://github.com/kean/Nuke/releases/tag/9.0.0) — iOS Dev Weekly · Issue 457 — Source repository · Topics: Combine & Reactive Programming · Developer Tools · Swift
  **Published:** `22nd May 2020`
  **NeKI brief:** Examines Nuke, focusing on it’s always nice to see a mature, stable, well-loved open-source project get an update, and that’s what nuke from…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Using Combine to simulate async / await](https://moreindirection.wordpress.com/2020/05/13/using-combine-to-simulate-async-await-in-swift) — iOS Dev Weekly · Issue 456 — Article · Topics: Combine & Reactive Programming · Concurrency · Swift
  **Published:** `15th May 2020`
  **NeKI brief:** Covers Using Combine to simulate async / await, focusing on Swift and Apple-platform engineering practice. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [Chris proposed](https://gist.github.com/lattner/31ed37682ef1576b16bca1432ea9f782) — iOS Dev Weekly · Issue 456 — Source repository · Topics: Combine & Reactive Programming · Concurrency · Swift
  **Published:** `15th May 2020`
  **NeKI brief:** Examines Chris proposed, focusing on like bill atkins, i too am keen to see swift get support for async/await style concurrency. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Exploring Futures over Closures](https://www.swiftjectivec.com/exploring-closures-with-futures) — iOS Dev Weekly · Issue 453 — Article · Topics: Combine & Reactive Programming · Swift
  **Published:** `24th April 2020`
  **NeKI brief:** Examines Exploring Futures over Closures, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [more information here](http://trycombine.com/posts/announcing-timelane-combine) — iOS Dev Weekly · Issue 445 — Article · Topics: Combine & Reactive Programming · Concurrency · Performance
  **Published:** `28th February 2020`
  **NeKI brief:** Examines more information here, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [continuously updated](https://github.com/heckj/swiftui-notes/commits/master) — iOS Dev Weekly · Issue 435 — Source repository · Topics: Combine & Reactive Programming · Developer Tools · Swift
  **Published:** `20th December 2019`
  **NeKI brief:** Examines continuously updated, focusing on joseph heck, author of the wonderful (and continuously updated) using combine book talking about throttle and debounce in…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Combine by Tutorials](https://store.raywenderlich.com/products/combine-asynchronous-programming-with-swift) — iOS Dev Weekly · Issue 428 — Tutorial · Topics: Combine & Reactive Programming · Concurrency · Swift
  **Published:** `1st November 2019`
  **NeKI brief:** Examines Combine by Tutorials, focusing on the author’s note that should make it clear that i haven’t read all of these books myself. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [LLVS project](https://github.com/mentalfaculty/LLVS) — iOS Dev Weekly · Issue 424 — Source repository · Topics: Apple Platform Ecosystem · Combine & Reactive Programming · Persistence & Synchronisation
  **Published:** `4th October 2019`
  **NeKI brief:** Examines LLVS project, focusing on one topic that has been talked about consistently since wwdc is how core data (or any data persistence framework) will be…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Using Combine to Supplement Delegates With Publishers](https://www.iamsim.me/using-combine-to-supplement-delegates-with-publishers) — iOS Dev Weekly · Issue 424 — Article · Topics: Combine & Reactive Programming · Swift · SwiftUI
  **Published:** `4th October 2019`
  **NeKI brief:** Examines Using Combine to Supplement Delegates With Publishers, offering practical guidance on networking and asynchronous reliability. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Combine vs. RxSwift: Should you switch to Combine?](https://quickbirdstudios.com/blog/combine-vs-rxswift) — iOS Dev Weekly · Issue 416 — Article · Topics: Combine & Reactive Programming · Swift · Testing
  **Published:** `9th August 2019`
  **NeKI brief:** Covers Combine vs. RxSwift: Should you switch to Combine?, focusing on Swift and Apple-platform engineering practice. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [performance testing](https://github.com/quickbirdstudios/CombineRxSwiftPerformance/blob/master/Readme.md) — iOS Dev Weekly · Issue 416 — Source repository · Topics: Combine & Reactive Programming · Performance · Testing
  **Published:** `9th August 2019`
  **NeKI brief:** Examines performance testing, focusing on so much combine content this week! we’ll finish with stefan kofler taking a balanced look comparing rxswift to combine. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [MovieSwiftUI](https://github.com/Dimillian/MovieSwiftUI) — iOS Dev Weekly · Issue 413 — Source repository · Topics: Combine & Reactive Programming · Swift · SwiftUI
  **Published:** `19th July 2019`
  **NeKI brief:** Examines MovieSwiftUI, focusing on how far can swiftui (and combine) go before you need to resort to uiviewrepresentable? thomas ricouard has been doing…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [GRDB](https://github.com/groue/GRDB.swift) — iOS Dev Weekly · Issue 410 — Source repository · Topics: Apple Platform Ecosystem · Combine & Reactive Programming · Developer Tools
  **Published:** `28th June 2019`
  **NeKI brief:** GRDB.swift is a SQLite toolkit offering query interfaces, migrations, observations, and record mapping. Use it when an app needs transparent relational persistence and reactive database changes without SwiftData's deployment and sync assumptions.
- [this article](https://www.bloomberg.com/news/articles/2017-12-20/apple-is-said-to-have-plan-to-combine-iphone-ipad-and-mac-apps) — iOS Dev Weekly · Issue 332 — Article · Topics: Combine & Reactive Programming · Cross-Platform & Web
  **Published:** `22nd December 2017`
  **NeKI brief:** Reports the historical proposal to unify iPhone, iPad, and Mac app distribution or development. Use it as platform-strategy context when assessing multiplatform architecture, while treating predictions as historical and checking the current Apple deployment model.
- [Intro to Generics](https://blog.bobthedeveloper.io/intro-to-generics-in-swift-with-bob-df58118a5001) — iOS Dev Weekly · Issue 296 — Article · Topics: Combine & Reactive Programming · Swift
  **Published:** `14th April 2017`
  **NeKI brief:** Explores Intro to Generics in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Intro to Protocol Oriented Programming](https://blog.bobthedeveloper.io/introduction-to-protocol-oriented-programming-in-swift-b358fe4974f) — iOS Dev Weekly · Issue 296 — Article · Topics: Combine & Reactive Programming · Swift
  **Published:** `14th April 2017`
  **NeKI brief:** Explores Intro to Protocol Oriented Programming in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Touchpose](https://github.com/toddreed/Touchpose) — iOS Dev Weekly · Issue 32 — Source repository · Topics: Combine & Reactive Programming · Developer Tools
  **Published:** `9th March 2012`
  **NeKI brief:** Provides the Touchpose source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Multi-agent coding with Antigravity](https://www.youtube.com/watch?v=bCz3Pc041ME) — Not only Swift · Issue 94 — Video · Topics: Combine & Reactive Programming
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [collection of tools and utilities for Swift and SwiftUI development](https://github.com/hmlongco/Runes) — Not only Swift · Issue 92 — Source repository · Topics: Combine & Reactive Programming · Concurrency · Swift
  **NeKI brief:** This source repository covers reusable Swift and SwiftUI extensions and modifiers. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [The Secret to Buttery Smooth SwiftUI](https://www.swiftdifferently.com/blog/swiftui/swiftui-performance-article) — Not only Swift · Issue 92 — Article · Topics: Concurrency · Swift · SwiftUI
  **NeKI brief:** Explores practical causes of sluggish SwiftUI rendering and techniques for reducing unnecessary work. Useful as a performance checklist before profiling view identity, expensive body computations, and state-driven update frequency with Instruments.
- [Building a MCP Server in Swift](https://adamwulf.me/2025/03/building-a-mcp-server-in-swift) — Not only Swift · Issue 78 — Article · Topics: AI Development · Combine & Reactive Programming · Swift
  **NeKI brief:** Describes Building a MCP Server in Swift, focusing on practical tool integration and workflow trade-offs. Use it to evaluate reproducibility, trust boundaries, and debugging steps before adopting the approach in an Xcode project.
