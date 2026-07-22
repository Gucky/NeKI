# Composable Architecture

Third-party reading leads collected from NeKI sources. The links may be useful perspectives, but are not vetted recommendations or authoritative API guidance. NeKI publishes routing metadata, not the linked articles' text.

**Scope:** The Composable Architecture, reducers, effects, state, and dependency patterns.

- Last collected: `2026-07-22T21:56:49Z`
- Indexed links shown: **48**

## Direct-source reading

- [Hard Deprecations and Soft Landings with SwiftPM Traits](https://www.pointfree.co/blog/posts/203-hard-deprecations-and-soft-landings-with-swiftpm-traits) — Point-Free · article catalogue
  **Published:** `2026-03-16T00:00:00Z`
  **NeKI brief:** SwiftPM traits can keep a deprecated feature available as an opt-in while the default product removes its dependency, creating a soft migration before a hard break. The pattern balances source compatibility against leaner builds.
- [We’re going live soon!](https://www.pointfree.co/blog/posts/201-we-re-going-live-soon) — Point-Free · article catalogue
  **Published:** `2026-02-05T16:00:00Z`
  **NeKI brief:** The planned TCA 2.0 preview pairs a new architecture release with a live feedback loop before APIs stabilize. It is a routing lead for evaluating migration shape and testing strategy while distinguishing preview behavior from supported contracts.
- [The “Point-Free Way”, TCA 2.0 sneak peek, a giveaway, Q&A, and more!](https://www.pointfree.co/blog/posts/200-the-point-free-way-tca-2-0-sneak-peek-a-giveaway-q-a-and-more) — Point-Free · article catalogue
  **Published:** `2026-02-04T00:00:00Z`
  **NeKI brief:** The TCA 2.0 sneak peek frames concurrency and domain modeling changes as a migration conversation rather than a drop-in upgrade. Its Q&A format is useful for locating compatibility concerns before adopting a major architecture revision.
- [UIKit and the Composable Architecture](https://www.pointfree.co/blog/posts/150-uikit-and-the-composable-architecture) — Point-Free · article catalogue
  **Published:** `2024-08-15T00:00:00Z`
  **NeKI brief:** Shows how UIKit view controllers can host Composable Architecture stores while keeping state and effects outside imperative view code. The integration pattern helps migrate screens incrementally without forcing an all-at-once SwiftUI rewrite.
- [Swift Testing Bonanza](https://www.pointfree.co/blog/posts/148-swift-testing-bonanza) — Point-Free · article catalogue
  **Published:** `2024-07-24T00:00:00Z`
  **NeKI brief:** Surveys Swift Testing techniques used in Point-Free projects, including traits, parameterization, and dependency control. It provides concrete test-design patterns for keeping asynchronous feature tests deterministic and readable.
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
- [Sharing state in the Composable Architecture](https://www.pointfree.co/blog/posts/134-sharing-state-in-the-composable-architecture) — Point-Free · article catalogue
  **Published:** `2024-02-26T00:00:00Z`
  **NeKI brief:** Sharing state across features is safer when dependencies define access and mutations flow through reducers, rather than passing mutable references freely. The article frames the resulting coordination and testing trade-offs.
- [Observation comes to the Composable Architecture](https://www.pointfree.co/blog/posts/130-observation-comes-to-the-composable-architecture) — Point-Free · article catalogue
  **Published:** `2024-01-29T00:00:00Z`
  **NeKI brief:** Observation integration lets Composable Architecture derive view updates from model access rather than explicit publisher plumbing. The change affects dependency and state boundaries, so migration should verify invalidation behavior and test isolation.
- [Observable Architecture Beta!](https://www.pointfree.co/blog/posts/125-observable-architecture-beta) — Point-Free · article catalogue
  **Published:** `2023-11-27T00:00:00Z`
  **NeKI brief:** Introduces the beta Observable Architecture tools from Point-Free and how existing Composable Architecture code can adopt the observation model. Useful for evaluating migration trade-offs between view-driven observation, testable state, and deployment support.
- [Macro Bonanza: Composable Architecture](https://www.pointfree.co/blog/posts/118-macro-bonanza-composable-architecture) — Point-Free · article catalogue
  **Published:** `2023-11-14T00:00:00Z`
  **NeKI brief:** Composable Architecture macros can synthesize repetitive reducer and observation plumbing from declared domains. The gain is less boilerplate; the trade-off is compiler-generated behavior that must be reviewed and versioned carefully.
- [Composable Architecture 1.0](https://www.pointfree.co/blog/posts/112-composable-architecture-1-0) — Point-Free · article catalogue
  **Published:** `2023-07-31T00:00:00Z`
  **NeKI brief:** Introduces the 1.0 Composable Architecture model of reducers, state, actions, dependencies, and effects. Useful as a reference for explicit unidirectional data flow and testable SwiftUI features.
- [Navigation tools come to the Composable Architecture](https://www.pointfree.co/blog/posts/106-navigation-tools-come-to-the-composable-architecture) — Point-Free · article catalogue
  **Published:** `2023-05-30T00:00:00Z`
  **NeKI brief:** Navigation tools model presentation and destination state inside a feature domain, allowing tests to exercise routing decisions without a live UI. The integration trades imperative convenience for explicit state transitions.
- [Composable navigation beta, part 2](https://www.pointfree.co/blog/posts/105-composable-navigation-beta-part-2) — Point-Free · article catalogue
  **Published:** `2023-04-17T00:00:00Z`
  **NeKI brief:** The navigation beta continues a state-driven model for stacks and presentations, emphasizing migration and composition across features. It is useful when evaluating how destination state affects restoration and deep links.
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
- [Improving Composable Architecture performance](https://www.pointfree.co/blog/posts/80-improving-composable-architecture-performance) — Point-Free · article catalogue
  **Published:** `2022-09-08T05:00:00Z`
  **NeKI brief:** Performance work in a reducer architecture starts by measuring state propagation and identifying unnecessary copies or view updates. The article routes to concrete optimization trade-offs without abandoning value semantics.
- [Async Composable Architecture](https://www.pointfree.co/blog/posts/79-async-composable-architecture) — Point-Free · article catalogue
  **Published:** `2022-08-08T05:00:00Z`
  **NeKI brief:** Async effects integrate structured concurrency into reducer workflows, making cancellation and task lifetime part of feature logic. The design reduces callback plumbing but requires disciplined actor and dependency boundaries.
- [Point Freebies: Swift Concurrency and More](https://www.pointfree.co/blog/posts/64-point-freebies-swift-concurrency-and-more) — Point-Free · article catalogue
  **Published:** `2021-09-15T05:00:00Z`
  **NeKI brief:** The concurrency collection routes to examples of task cancellation, isolation, and structured lifetime. Use it as a map to concrete implementations, verifying each technique against the current Swift concurrency model.
- [The Composable Architecture ❤️ SwiftUI Bindings](https://www.pointfree.co/blog/posts/63-the-composable-architecture-%EF%B8%8F-swiftui-bindings) — Point-Free · article catalogue
  **Published:** `2021-09-06T05:00:00Z`
  **NeKI brief:** Composable Architecture bindings route UI edits through actions and reducer state instead of mutating model references directly. The integration keeps effects and validation testable while adding explicit binding case definitions.
- [Better Performance Bonanza](https://www.pointfree.co/blog/posts/61-better-performance-bonanza) — Point-Free · article catalogue
  **Published:** `2021-07-14T05:00:00Z`
  **NeKI brief:** Performance improvements are most credible when accompanied by before-and-after measurements and a clear account of changed work. The collection routes to concrete Swift optimization examples rather than generic speed advice.
- [Announcing SwitchStore for the Composable Architecture](https://www.pointfree.co/blog/posts/59-announcing-switchstore-for-the-composable-architecture) — Point-Free · article catalogue
  **Published:** `2021-06-14T05:00:00Z`
  **NeKI brief:** SwitchStore selects a view branch from enum state while preserving the reducer as the state-transition owner. The pattern improves exhaustive UI modeling, but identity and child-store lifetime need deliberate handling.
- [Composable Architecture Test Store Improvements](https://www.pointfree.co/blog/posts/53-composable-architecture-test-store-improvements) — Point-Free · article catalogue
  **Published:** `2021-03-08T16:00:00Z`
  **NeKI brief:** Test-store improvements make action sequencing and state assertions clearer while keeping effects under test control. The workflow improves failure diagnosis, but tests still need to describe meaningful user-visible transitions.
- [Composable Forms: Say “Bye” to Boilerplate!](https://www.pointfree.co/blog/posts/52-composable-forms-say-bye-to-boilerplate) — Point-Free · article catalogue
  **Published:** `2021-02-01T06:00:00Z`
  **NeKI brief:** Composable forms derive validation and field state from domain structure, reducing repeated UI glue. The pattern centralizes rules but requires careful modeling of partial edits and submission effects.
- [2020 Year-in-review](https://www.pointfree.co/blog/posts/50-2020-year-in-review) — Point-Free · article catalogue
  **Published:** `2020-12-23T06:00:00Z`
  **NeKI brief:** Recaps 2020 Composable Architecture development: feature composition, dependency control without protocol proliferation, and the 0.1.0 library release. Use it as historical context for why dependencies and reducer architecture became explicit design boundaries.
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
- [Composable Architecture, the library](https://www.pointfree.co/blog/posts/41-composable-architecture-the-library) — Point-Free · article catalogue
  **Published:** `2020-05-04T05:00:00Z`
  **NeKI brief:** Introduces Point-Free's Composable Architecture and its state, action, reducer, and effect model. Use it when evaluating a unidirectional architecture with testable feature boundaries.
- [Composable styling in SwiftUI | Swift with Majid](https://swiftwithmajid.com/2019/08/28/composable-styling-in-swiftui) — Swift with Majid · article catalogue
  **Published:** `2019-08-28T00:00:00+00:00`
  **NeKI brief:** Composable styling layers reusable SwiftUI modifiers instead of repeating visual configuration. Follow it to create consistent design tokens, while keeping styling separate from controls’ interaction and accessibility semantics.

## Newsletter and related leads

- [The TCA Playbook: Debugging Large Reducers Without Losing Your Mind](https://medium.com/@wesleymatlock/the-tca-playbook-debugging-large-reducers-without-losing-your-mind-e8813c9c6eda) — Those Who Swift · Issue 233 — Article · Topics: Composable Architecture · Developer Tools · Performance
  **Published:** `2025-09-24`
  **NeKI brief:** Examines The TCA Playbook: Debugging Large Reducers Without Losing Your Mind, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [The evolution of native engineering at Tripadvisor: Part 1](https://medium.com/tripadvisor/the-evolution-of-native-engineering-at-tripadvisor-part-1-577cc0e36ec8) — SwiftUI Weekly · SwiftUI Weekly - Issue #217 — Article · Topics: Architecture · Composable Architecture · Concurrency
  **Published:** `2025-06-02T12:56:10.176Z`
  **NeKI brief:** Traces Tripadvisor's evolution of native mobile engineering and organizational architecture. Useful as large-team context for evaluating ownership, platform investment, and migration strategy alongside SwiftUI-specific decisions.
- [open letter to Arc users](https://browsercompany.substack.com/p/letter-to-arc-members-2025) — Fatbobman’s Swift Weekly · Issue 86 — Article · Topics: Composable Architecture · Developer Community & Business · Objective-C & Cocoa
  **Published:** `2025-06-02T12:03:07.832Z`
  **NeKI brief:** Explains the Browser Company's 2025 decision and communication to Arc members. Useful historical context for assessing product continuity, migration expectations, and risks when relying on a fast-changing developer tool.
- [The Composable Architecture: How Architectural Design Decisions Influence Performance](https://www.swiftyplace.com/blog/the-composable-architecture-performance) — SwiftUI Weekly · SwiftUI Weekly - Issue #211 — Article · Topics: Architecture · Objective-C & Cocoa · Performance
  **Published:** `2025-03-25T13:30:35.672Z`
  **NeKI brief:** Examines performance implications of The Composable Architecture in SwiftUI, including reducer and view update costs. Useful for measuring architectural overhead in realistic workloads rather than assuming framework use is free or prohibitive.
- [Giffy](https://github.com/uwaisalqadri/Giffy) — iOS Dev Tools · iOS Dev Tools: Starview, Mint, Giffy — Source repository · Topics: Architecture · Composable Architecture · Swift
  **Published:** `2025-02-13T18:15:48.650Z`
  **NeKI brief:** Giffy is a sample iOS application that combines SwiftUI, The Composable Architecture, and Swinject-based dependency injection. Use it to inspect how those architectural pieces are wired together in a small, runnable project.
- [TCA](https://github.com/pointfreeco/swift-composable-architecture) — Fatbobman’s Swift Weekly · Issue 61 — Source repository · Topics: Architecture · Composable Architecture · Swift
  **Published:** `2024-12-09T12:00:43.829Z`
  **NeKI brief:** The Composable Architecture structures feature state, actions, reducers, dependencies, and tests around explicit unidirectional flow. Use the repository and migration material to evaluate operational trade-offs before adopting or upgrading TCA in a production app.
- [Sharing](https://github.com/pointfreeco/swift-sharing) — Fatbobman’s Swift Weekly · Issue 61 — Source repository · Topics: Composable Architecture · Developer Tools · Swift
  **Published:** `2024-12-09T12:00:43.829Z`
  **NeKI brief:** Sharing provides `@Shared` state with persistence strategies spanning app storage, files, memory, and external stores. Follow it when routing shared SwiftUI/UIKit state while keeping observation and persistence concerns explicit.
- [Migrating from CocoaPods to Tuist at Playtomic](https://dev.to/playtomic/migrating-from-cocoapods-to-tuist-at-playtomic-26ed?issue=031) — Fatbobman’s Swift Weekly · Issue 31 — Article · Topics: Architecture · Composable Architecture · Objective-C & Cocoa
  **Published:** `2024-05-13T12:02:47.849Z`
  **NeKI brief:** Describes a production migration from CocoaPods to Tuist, including project-generation and dependency-management implications. Follow it when planning a build-system transition and identifying CI or target-configuration risks.
- [The Composable Architecture: My 3 Year Experience](https://rodschmidt.com/posts/composable-architecture-experience) — SwiftUI Weekly · SwiftUI Weekly - Issue #185 — Article · Topics: Architecture · Composable Architecture · Objective-C & Cocoa
  **Published:** `2024-05-06T13:22:31.904Z`
  **NeKI brief:** A three-year TCA retrospective surfaces production trade-offs that API introductions omit, including architectural discipline and maintenance cost. Use it to evaluate long-lived team fit rather than reading it as a generic framework endorsement.
- [The Composable Architecture: My 3 Year Experience](https://rodschmidt.com/posts/composable-architecture-experience?issue=030) — Fatbobman’s Swift Weekly · Issue 30 — Article · Topics: Architecture · Composable Architecture · Objective-C & Cocoa
  **Published:** `2024-05-06T12:01:46.954Z`
  **NeKI brief:** A three-year TCA retrospective surfaces production trade-offs that API introductions omit, including architectural discipline and maintenance cost. Use it to evaluate long-lived team fit rather than reading it as a generic framework endorsement.
- [Composition in TCA: Scope, Combine and Pullback operators](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyJnY9WmYycEZFYTN1ZXciLCJwb3N0X2lkIjoiNTAxNjg3MDctMTllNi00OWVjLWEzMGUtZDM0NTg5OGM5Mzk5IiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6ImJkOTY3MzY1LTVhYTAtNGIzOS05NWY0LTJhMGViNjgwNTJhMyIsImlhdCI6MTY3NDA2MjU1Ni45LCJpc3MiOiJvcmNoaWQifQ.oCLiQ-6M7I0rhyM9-07MqJd2m-21FbRxpLCYhEXIV-0) — SwiftUI Weekly · SwiftUI Weekly - Issue #121 — Article · Topics: Architecture · Combine & Reactive Programming · Composable Architecture
  **Published:** `2022-11-21T12:42:39.000Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [SwiftUI-Agent-Skill: Expert reviews for your codebase](https://github.com/twostraws/SwiftUI-Agent-Skill) — Not only Swift · Issue 95 — Source repository · Topics: Composable Architecture · Swift · SwiftUI
  **NeKI brief:** Provides a reusable SwiftUI-focused agent skill with guidance for generating and reviewing views. Useful as a concrete prompt and workflow artifact when evaluating AI-assisted UI composition, accessibility, and maintainability in a project.
