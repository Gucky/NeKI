# Point-Free

Third-party source index. It provides source attribution and routing metadata, not republished article content. Verify article conclusions independently before applying them.

- Archive: [https://www.pointfree.co/blog](https://www.pointfree.co/blog)
- Last collected: `2026-07-22T21:58:56Z`
- Indexed entries: **153**

- [Xcode 27 support in the Point-Free ecosystem](https://www.pointfree.co/blog/posts/218-xcode-27-support-in-the-point-free-ecosystem)
  **Published:** `2026-06-26T00:00:00Z`
  **Topics:** Xcode
  **NeKI brief:** Records the compatibility work needed to keep Point-Free libraries building against early Xcode 27 betas, including fixes for Swift 6.4 regressions. It illustrates the maintenance cost of evolving toolchains and the value of open-source feedback loops.
- [Proposing task-local test traits for Swift Testing](https://www.pointfree.co/blog/posts/217-proposing-task-local-test-traits-for-swift-testing)
  **Published:** `2026-06-25T00:00:00Z`
  **Topics:** Swift · Testing
  **NeKI brief:** Proposes task-local test traits for Swift Testing, based on patterns developed in Point-Free libraries. The article is useful for understanding how per-test configuration could compose with structured concurrency before the proposal becomes platform API.
- [“Trait-ifying” our libraries to reduce transitive dependencies](https://www.pointfree.co/blog/posts/216-trait-ifying-our-libraries-to-reduce-transitive-dependencies)
  **Published:** `2026-06-24T00:00:00Z`
  **Topics:** Dependency Injection · Swift · Swift Package Manager · Testing
  **NeKI brief:** Applies SwiftPM traits to make optional library features opt-in, using SwiftNavigation as the test case. Follow it when reducing transitive dependencies while weighing package configuration complexity against smaller builds.
- [New macros for SwiftNavigation](https://www.pointfree.co/blog/posts/215-new-macros-for-swiftnavigation)
  **Published:** `2026-06-23T00:00:00Z`
  **Topics:** Macros & Metaprogramming · Observation & State Management · Swift
  **NeKI brief:** Introduces @CaseBindable and @UITransactionEntry macros for deriving enum-case bindings and custom UI transaction keys. The examples show how code generation can remove repetitive navigation glue while preserving typed state.
- [DebugSnapshots now logs SwiftUI bindings](https://www.pointfree.co/blog/posts/214-debugsnapshots-now-logs-swiftui-bindings)
  **Published:** `2026-06-22T00:00:00Z`
  **Topics:** Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Extends DebugSnapshots to record mutations made through SwiftUI bindings, making model evolution visible during interaction tests. It is particularly useful for diagnosing unexpected state transitions that ordinary final-screen snapshots hide.
- [Introducing @DependencyEntry](https://www.pointfree.co/blog/posts/213-introducing-dependencyentry)
  **Published:** `2026-06-17T00:00:00Z`
  **Topics:** Dependency Injection · Macros & Metaprogramming · Testing
  **NeKI brief:** Presents @DependencyEntry as a macro for registering dependencies while supporting live, preview, and test values. The design shows how generated declarations can keep dependency setup concise without losing explicit override points.
- [TaskLocal test traits](https://www.pointfree.co/blog/posts/209-tasklocal-test-traits)
  **Published:** `2026-06-04T00:00:00Z`
  **Topics:** Concurrency · Swift · Testing · Xcode
  **NeKI brief:** A Swift Testing trait can install a task-local value for an entire test or suite, eliminating repetitive `withValue` wrappers. Traits compose, but the approach still depends on task inheritance and must account for Xcode test-support build quirks.
- [DebugSnapshots: Public beta](https://www.pointfree.co/blog/posts/207-debugsnapshots-public-beta)
  **Published:** `2026-05-27T00:00:00Z`
  **Topics:** Observation & State Management · Testing
  **NeKI brief:** Introduces DebugSnapshots for recording and inspecting application state as debugging artifacts. Use it when a visual or state regression needs reproducible evidence that can be reviewed without reproducing the entire interactive session.
- [Beta Preview: ComposableArchitecture 2.0](https://www.pointfree.co/blog/posts/206-beta-preview-composablearchitecture-2-0)
  **Published:** `2026-04-01T00:00:00Z`
  **Topics:** Architecture · Concurrency · Macros & Metaprogramming · Testing
  **NeKI brief:** Previews Composable Architecture 2.0 changes and their implications for state, effects, and dependency management. Use it to assess an upcoming migration path before adopting beta conventions in a production feature.
- [Beta Preview: DebugSnapshots](https://www.pointfree.co/blog/posts/205-beta-preview-debugsnapshots)
  **Published:** `2026-04-01T00:00:00Z`
  **Topics:** Macros & Metaprogramming · Observation & State Management · Testing
  **NeKI brief:** Introduces DebugSnapshots for recording structured debugging state alongside UI behavior. Follow it when reproducing visual or state-dependent failures requires an inspectable artifact rather than a screenshot detached from its model inputs.
- [Introducing: Point-Free Beta Previews](https://www.pointfree.co/blog/posts/204-introducing-point-free-beta-previews)
  **Published:** `2026-04-01T00:00:00Z`
  **Topics:** Architecture · Testing
  **NeKI brief:** Beta previews distribute DebugSnapshots and an early Composable Architecture 2.0 without making unfinished APIs the default release. The workflow gives adopters a controlled feedback channel while isolating compatibility and migration risk.
- [Hard Deprecations and Soft Landings with SwiftPM Traits](https://www.pointfree.co/blog/posts/203-hard-deprecations-and-soft-landings-with-swiftpm-traits)
  **Published:** `2026-03-16T00:00:00Z`
  **Topics:** Architecture · Composable Architecture · Swift · Swift Package Manager
  **NeKI brief:** SwiftPM traits can keep a deprecated feature available as an opt-in while the default product removes its dependency, creating a soft migration before a hard break. The pattern balances source compatibility against leaner builds.
- [Introducing: The Point-Free Way](https://www.pointfree.co/blog/posts/202-introducing-the-point-free-way)
  **Published:** `2026-02-06T00:00:00Z`
  **Topics:** Swift
  **NeKI brief:** The Point-Free Way packages recurring Swift application workflows, architecture patterns, and testing practices as a navigable curriculum. Its value is operational: teams can compare a complete process rather than copy an isolated code snippet.
- [We’re going live soon!](https://www.pointfree.co/blog/posts/201-we-re-going-live-soon)
  **Published:** `2026-02-05T16:00:00Z`
  **Topics:** Architecture · Composable Architecture
  **NeKI brief:** The planned TCA 2.0 preview pairs a new architecture release with a live feedback loop before APIs stabilize. It is a routing lead for evaluating migration shape and testing strategy while distinguishing preview behavior from supported contracts.
- [The “Point-Free Way”, TCA 2.0 sneak peek, a giveaway, Q&A, and more!](https://www.pointfree.co/blog/posts/200-the-point-free-way-tca-2-0-sneak-peek-a-giveaway-q-a-and-more)
  **Published:** `2026-02-04T00:00:00Z`
  **Topics:** Architecture · Composable Architecture
  **NeKI brief:** The TCA 2.0 sneak peek frames concurrency and domain modeling changes as a migration conversation rather than a drop-in upgrade. Its Q&A format is useful for locating compatibility concerns before adopting a major architecture revision.
- [Point-Free turns 8!](https://www.pointfree.co/blog/posts/199-point-free-turns-8)
  **Published:** `2026-01-29T00:00:00Z`
  **Topics:** Developer Community & Business
  **NeKI brief:** The anniversary preview links the Point-Free Way curriculum with an upcoming Composable Architecture beta, showing how education and library evolution can be staged together. Treat the roadmap as exploratory context, not a stable API promise.
- [2025 Year-in-Review](https://www.pointfree.co/blog/posts/196-2025-year-in-review)
  **Published:** `2025-12-22T00:00:00Z`
  **Topics:** Persistence & Synchronisation
  **NeKI brief:** The year review records how open-source library work, release cadence, and long-lived architecture projects reinforce one another. It is useful for tracing why API stability and maintenance investment matter beyond a single feature release.
- [Open source case study: Listening to our users](https://www.pointfree.co/blog/posts/189-open-source-case-study-listening-to-our-users)
  **Published:** `2025-10-21T00:00:00Z`
  **Topics:** Swift
  **NeKI brief:** Shares Point-Free's open-source case study about listening to users and evolving a product in response. Useful for examining feedback loops, prioritization, and maintainers' communication choices when an Apple-platform library serves a changing community.
- [New in SQLiteData: Custom aggregate functions](https://www.pointfree.co/blog/posts/188-new-in-sqlitedata-custom-aggregate-functions)
  **Published:** `2025-10-16T00:00:00Z`
  **Topics:** Persistence & Synchronisation · Swift
  **NeKI brief:** Adds custom aggregate SQL functions to SQLiteData while retaining typed query construction. Follow it when domain calculations belong in the database and you need schema-aware Swift rather than raw SQL strings.
- [New in SQLiteData: Migration tool for CloudKit sync](https://www.pointfree.co/blog/posts/187-new-in-sqlitedata-migration-tool-for-cloudkit-sync)
  **Published:** `2025-10-08T00:00:00Z`
  **Topics:** Persistence & Synchronisation
  **NeKI brief:** Introduces a SQLiteData migration tool for stores synchronized with CloudKit, focusing on coordinating schema evolution with remote data. It is useful when persistence changes must remain deployable across already-synced installations.
- [New in SQLiteData: Column groups and inheritance](https://www.pointfree.co/blog/posts/186-new-in-sqlitedata-column-groups-and-inheritance)
  **Published:** `2025-10-02T00:00:00Z`
  **Topics:** Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** Explains SQLiteData column groups and model inheritance as typed schema composition, reducing repetition while preserving SQL constraints. The design is a concrete alternative to duplicating fields across related tables.
- [What’s new in SQLiteData: Views](https://www.pointfree.co/blog/posts/185-what-s-new-in-sqlitedata-views)
  **Published:** `2025-09-24T00:00:00Z`
  **Topics:** Persistence & Synchronisation
  **NeKI brief:** Uses SQLite views to expose derived read models through SQLiteData's typed APIs. Follow it when joins or aggregates should be reusable query surfaces without pretending they are independently mutable tables.
- [SQLiteData 1.0: An alternative to SwiftData with CloudKit sync and sharing](https://www.pointfree.co/blog/posts/184-sqlitedata-1-0-an-alternative-to-swiftdata-with-cloudkit-sync-and-sharing)
  **Published:** `2025-09-17T00:00:00Z`
  **Topics:** Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** SQLiteData combines SQLite persistence with CloudKit synchronization and sharing. Use it when SwiftData lacks required deployment or SQL control, while evaluating the operational cost of its sync model.
- [SQLiteData 0.7.0: User-defined SQL functions](https://www.pointfree.co/blog/posts/183-sharinggrdb-0-7-0-user-defined-sql-functions)
  **Published:** `2025-09-03T00:00:00Z`
  **Topics:** Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** SQLiteData exposes user-defined SQL functions through Swift declarations, preserving type-checked query construction while allowing database-specific computation. The extension point trades portability for expressiveness and requires controlling registration and migration behavior.
- [SQLiteData 0.6.0: Full-text search and more](https://www.pointfree.co/blog/posts/182-sharinggrdb-0-6-0-full-text-search-and-more)
  **Published:** `2025-08-21T00:00:00Z`
  **Topics:** Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** The SQLiteData update layers SQLite full-text search onto Swift query APIs, turning tokenization and ranking into database work rather than in-memory filtering. The design improves scale but makes index configuration and match semantics part of the model.
- [A SwiftData alternative with SQLite + CloudKit: Public beta](https://www.pointfree.co/blog/posts/181-a-swiftdata-alternative-with-sqlite-cloudkit-public-beta)
  **Published:** `2025-08-04T00:00:00Z`
  **Topics:** Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** Announces a SQLite and CloudKit synchronization alternative to SwiftData. Use it to investigate relational persistence and sync options, then verify API maturity and operational trade-offs before adoption.
- [Perception 2.0: An updated back-port of Swift’s Observation framework](https://www.pointfree.co/blog/posts/180-perception-2-0-an-updated-back-port-of-swift-s-observation-framework)
  **Published:** `2025-07-30T00:00:00Z`
  **Topics:** Observation & State Management · Swift
  **NeKI brief:** Explains Perception 2.0 as a back-port of Swift Observation for older deployment targets. Useful when sharing modern observation patterns while an application cannot yet require iOS 17.
- [A SwiftData alternative with SQLite + CloudKit: Private alpha](https://www.pointfree.co/blog/posts/179-a-swiftdata-alternative-with-sqlite-cloudkit-private-alpha)
  **Published:** `2025-06-30T00:00:00Z`
  **Topics:** Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** The private alpha combines SQLite persistence with CloudKit synchronization as an alternative to SwiftData's storage model. It is useful for evaluating explicit schema and sync control, while the preview status signals API and migration risk.
- [We’re going live soon!](https://www.pointfree.co/blog/posts/178-we-re-going-live-soon)
  **Published:** `2025-06-25T00:00:00Z`
  **Topics:** Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** The CloudKit synchronization preview positions SQLiteData as an explicit persistence layer with sync machinery added incrementally. The announcement is a routing lead for evaluating schema ownership and conflict behavior before adopting a beta.
- [Live stream reminder: A SwiftData alternative with CloudKit synchronization](https://www.pointfree.co/blog/posts/177-live-stream-reminder-a-swiftdata-alternative-with-cloudkit-synchronization)
  **Published:** `2025-06-24T00:00:00Z`
  **Topics:** Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** The planned CloudKit synchronization work extends a SQLite-backed SwiftData alternative rather than hiding storage behind framework defaults. It is useful when comparing explicit database control with SwiftData's integrated model and sync assumptions.
- [Type-safe, schema-safe SQL triggers in Swift](https://www.pointfree.co/blog/posts/176-type-safe-schema-safe-sql-triggers-in-swift)
  **Published:** `2025-06-23T00:00:00Z`
  **Topics:** Persistence & Synchronisation · Swift
  **NeKI brief:** Typed SQL triggers can be declared alongside Swift models so trigger names, tables, and expressions remain part of a checked schema surface. The approach improves migration visibility while accepting that database-side behavior is harder to debug from Swift alone.
- [Upcoming live stream: A vision for modern persistence](https://www.pointfree.co/blog/posts/175-upcoming-live-stream-a-vision-for-modern-persistence)
  **Published:** `2025-06-17T00:00:00Z`
  **Topics:** Persistence & Synchronisation
  **NeKI brief:** The modern-persistence proposal favors explicit SQLite control and composable synchronization over opaque model storage. It is useful for comparing schema ownership and query observability, while the announced status means API stability is not guaranteed.
- [Free Episode: SwiftData versus SQL Query Builder](https://www.pointfree.co/blog/posts/174-free-episode-swiftdata-versus-sql-query-builder)
  **Published:** `2025-06-12T00:00:00Z`
  **Topics:** Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** Compares SwiftData with a SQL query-builder approach. Use it when choosing between declarative model persistence and explicit relational queries, migrations, and database-level control.
- [Mitigating SwiftSyntax build times](https://www.pointfree.co/blog/posts/171-mitigating-swiftsyntax-build-times)
  **Published:** `2025-06-03T00:00:00Z`
  **Topics:** Macros & Metaprogramming · Swift
  **NeKI brief:** Diagnoses SwiftSyntax compile-time costs and describes mitigation strategies around target boundaries and dependency choices. The article is useful for turning macro-heavy build slowdowns into measurable package-structure changes.
- [A fast, lightweight replacement for SwiftData](https://www.pointfree.co/blog/posts/170-a-fast-lightweight-replacement-for-swiftdata)
  **Published:** `2025-04-22T00:00:00Z`
  **Topics:** Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** The proposed SwiftData replacement keeps SQL as the persistence core while exposing ergonomic Swift APIs for queries and mutations. The trade-off is explicit schema and query control in exchange for more database concepts at the application boundary.
- [New in Swift 6.1: Test Scoping Traits](https://www.pointfree.co/blog/posts/169-new-in-swift-6-1-test-scoping-traits)
  **Published:** `2025-04-02T00:00:00Z`
  **Topics:** Swift · Testing · Xcode
  **NeKI brief:** Explains Swift 6.1 Test Scoping Traits as a mechanism for controlling test context before and after execution. Use it when suite-level fixtures must remain isolated under concurrent Swift Testing runs.
- [SQLiteData: A SwiftData Alternative](https://www.pointfree.co/blog/posts/168-sharinggrdb-a-swiftdata-alternative)
  **Published:** `2025-02-14T17:00:00Z`
  **Topics:** Observation & State Management · Persistence & Synchronisation · Swift · SwiftData · SwiftUI · UIKit
  **NeKI brief:** Introduces SharingGRDB as a SQLite-backed state-sharing approach for SwiftUI, combining persistence with observation. Useful when evaluating a relational alternative to SwiftData for shared, queryable application state.
- [A new project, episodes sneak peek, a giveaway, Q&A, and more!](https://www.pointfree.co/blog/posts/166-a-new-project-episodes-sneak-peek-a-giveaway-q-a-and-more)
  **Published:** `2025-02-13T00:00:00Z`
  **Topics:** Developer Community & Business
  **NeKI brief:** The announced project previews a new open-source component before release, giving adopters a chance to inspect design direction and compatibility risk. Treat the material as exploratory evidence, not a supported API contract.
- [Sharing 2](https://www.pointfree.co/blog/posts/164-sharing-2)
  **Published:** `2025-01-07T00:00:00Z`
  **Topics:** Concurrency
  **NeKI brief:** Sharing 2 expands state persistence tools around a composable Swift interface, allowing local and shared state to use the same dependency-aware model. The update is useful for evaluating migration cost from ad-hoc UserDefaults wrappers.
- [Tour of Sharing: Free for all to watch!](https://www.pointfree.co/blog/posts/163-tour-of-sharing-free-for-all-to-watch)
  **Published:** `2025-01-06T00:00:00Z`
  **Topics:** Functional Programming
  **NeKI brief:** The Sharing tour demonstrates state propagation and persistence as composable operations instead of view-specific plumbing. It is a useful workflow reference for tracing ownership and testing boundaries in a SwiftUI feature.
- [2024 Year-in-Review](https://www.pointfree.co/blog/posts/160-2024-year-in-review)
  **Published:** `2024-12-17T00:00:00Z`
  **Topics:** SwiftUI
  **NeKI brief:** The year review connects library releases, open-source projects, and educational output into a maintenance strategy rather than isolated launches. It provides roadmap context while leaving individual APIs to their canonical documentation.
- [Simple state sharing and persistence in Swift](https://www.pointfree.co/blog/posts/159-simple-state-sharing-and-persistence-in-swift)
  **Published:** `2024-12-02T00:00:00Z`
  **Topics:** Persistence & Synchronisation · Swift
  **NeKI brief:** A state-sharing abstraction can combine observation with persistence while keeping storage choice behind a dependency. The design makes synchronization policy testable, but callers must still define conflict and reset semantics.
- [Parsing and the Advent of Code](https://www.pointfree.co/blog/posts/158-parsing-and-the-advent-of-code)
  **Published:** `2024-12-01T00:00:00Z`
  **Topics:** Swift · SwiftData
  **NeKI brief:** The parsing project applies composable parser primitives to Advent of Code inputs, showing how grammar structure can replace brittle string splitting. It is useful for evaluating error propagation and parser reuse in production Swift code.
- [Point-Free is Xcode 16 ready](https://www.pointfree.co/blog/posts/152-point-free-is-xcode-16-ready)
  **Published:** `2024-09-12T00:00:00Z`
  **Topics:** Swift · Xcode
  **NeKI brief:** Xcode compatibility work across Point-Free libraries demonstrates why beta SDK validation and rapid dependency releases belong in an open-source maintenance workflow. The announcement is a routing lead for checking concrete compiler and framework fixes.
- [Cross-Platform Swift: Building a Swift app for the browser](https://www.pointfree.co/blog/posts/151-cross-platform-swift-building-a-swift-app-for-the-browser)
  **Published:** `2024-08-28T00:00:00Z`
  **Topics:** Swift
  **NeKI brief:** Cross-platform Swift in the browser requires choosing a runtime and adapting platform APIs while preserving shared domain code. The experiment is a useful boundary study for deciding what belongs in portable modules versus platform targets.
- [UIKit and the Composable Architecture](https://www.pointfree.co/blog/posts/150-uikit-and-the-composable-architecture)
  **Published:** `2024-08-15T00:00:00Z`
  **Topics:** Architecture · Composable Architecture · UIKit
  **NeKI brief:** Shows how UIKit view controllers can host Composable Architecture stores while keeping state and effects outside imperative view code. The integration pattern helps migrate screens incrementally without forcing an all-at-once SwiftUI rewrite.
- [Swift Navigation: Powerful navigation tools for all Swift platforms](https://www.pointfree.co/blog/posts/149-swift-navigation-powerful-navigation-tools-for-all-swift-platforms)
  **Published:** `2024-08-05T00:00:00Z`
  **Topics:** Observation & State Management · Swift · SwiftUI · UIKit
  **NeKI brief:** Presents composable navigation tools for Swift across Apple platforms, emphasizing state-driven routes and testable destinations. Useful when navigation logic has outgrown direct view-to-view links.
- [Swift Testing Bonanza](https://www.pointfree.co/blog/posts/148-swift-testing-bonanza)
  **Published:** `2024-07-24T00:00:00Z`
  **Topics:** Architecture · Composable Architecture · Dependency Injection · Swift · Testing
  **NeKI brief:** Surveys Swift Testing techniques used in Point-Free projects, including traits, parameterization, and dependency control. It provides concrete test-design patterns for keeping asynchronous feature tests deterministic and readable.
- [Unobtrusive and testable issue reporting](https://www.pointfree.co/blog/posts/147-unobtrusive-and-testable-issue-reporting)
  **Published:** `2024-07-23T00:00:00Z`
  **Topics:** Testing · Xcode
  **NeKI brief:** Designs issue reporting as an unobtrusive, testable dependency rather than a global crash or alert path. Useful for collecting actionable diagnostics while keeping user-facing reporting separate from feature logic.
- [A preview of our upcoming UIKitNavigation library](https://www.pointfree.co/blog/posts/145-a-preview-of-our-upcoming-uikitnavigation-library)
  **Published:** `2024-06-18T00:00:00Z`
  **Topics:** Observation & State Management · UIKit
  **NeKI brief:** UIKitNavigation previews a navigation layer that makes UIKit state-driven while retaining imperative controllers. The design is useful for assessing migration seams and lifecycle ownership before depending on a beta abstraction.
- [Swift Testing support for SnapshotTesting](https://www.pointfree.co/blog/posts/146-swift-testing-support-for-snapshottesting)
  **Published:** `2024-06-08T00:00:00Z`
  **Topics:** Macros & Metaprogramming · Swift · Testing
  **NeKI brief:** Connects Swift Testing test functions with SnapshotTesting assertions, preserving snapshot diffs while adopting the newer test framework. Follow it when migrating suites without losing failure artifacts or custom traits.
- [Composable Architecture Frequently Asked Questions](https://www.pointfree.co/blog/posts/141-composable-architecture-frequently-asked-questions)
  **Published:** `2024-06-04T00:00:00Z`
  **Topics:** Architecture · Composable Architecture
  **NeKI brief:** Answers recurring Composable Architecture questions about state, effects, reducers, and testing boundaries. Useful for evaluating architectural trade-offs before introducing a framework into a SwiftUI feature.
- [This is what peak UIKit looks like](https://www.pointfree.co/blog/posts/140-this-is-what-peak-uikit-looks-like)
  **Published:** `2024-05-27T00:00:00Z`
  **Topics:** Observation & State Management · Swift · UIKit
  **NeKI brief:** The peak UIKit discussion treats view controllers, state, and navigation as explicit seams rather than incidental callbacks. It is useful for evaluating imperative architecture with the same ownership and testing discipline applied to SwiftUI.
- [Sharing shared state with everyone!](https://www.pointfree.co/blog/posts/139-sharing-shared-state-with-everyone)
  **Published:** `2024-05-24T00:00:00Z`
  **Topics:** Concurrency
  **NeKI brief:** Shared state becomes manageable when reads and writes pass through a dependency-aware abstraction instead of global singletons. The article highlights synchronization ownership and test substitution as the trade-off for convenient cross-feature access.
- [Building an app in the Composable Architecture, from scratch](https://www.pointfree.co/blog/posts/138-building-an-app-in-the-composable-architecture-from-scratch)
  **Published:** `2024-05-09T00:00:00Z`
  **Topics:** Architecture · Composable Architecture · Dependency Injection · Testing
  **NeKI brief:** Building a feature from scratch in the Composable Architecture makes state, actions, reducer logic, and effects visible in sequence. The workflow is useful for tracing where domain decisions belong before adding navigation or persistence.
- [We’re live!](https://www.pointfree.co/blog/posts/137-we-re-live)
  **Published:** `2024-05-09T00:00:00Z`
  **Topics:** Architecture · Composable Architecture
  **NeKI brief:** The live release discussion demonstrates how a library team explains architectural changes, migration risks, and feedback channels before finalizing APIs. Use it as process context alongside the concrete source and tests.
- [Shared state in the Composable Architecture](https://www.pointfree.co/blog/posts/135-shared-state-in-the-composable-architecture)
  **Published:** `2024-04-29T00:00:00Z`
  **Topics:** Architecture · Composable Architecture
  **NeKI brief:** Shared state in a reducer architecture needs one owner and explicit observation paths so features do not diverge silently. The design helps coordinate mutations while making synchronization behavior testable.
- [Sharing state in the Composable Architecture](https://www.pointfree.co/blog/posts/134-sharing-state-in-the-composable-architecture)
  **Published:** `2024-02-26T00:00:00Z`
  **Topics:** Architecture · Composable Architecture
  **NeKI brief:** Sharing state across features is safer when dependencies define access and mutations flow through reducers, rather than passing mutable references freely. The article frames the resulting coordination and testing trade-offs.
- [Observation comes to the Composable Architecture](https://www.pointfree.co/blog/posts/130-observation-comes-to-the-composable-architecture)
  **Published:** `2024-01-29T00:00:00Z`
  **Topics:** Architecture · Composable Architecture · Swift
  **NeKI brief:** Observation integration lets Composable Architecture derive view updates from model access rather than explicit publisher plumbing. The change affects dependency and state boundaries, so migration should verify invalidation behavior and test isolation.
- [Perception: A back-port of @Observable](https://www.pointfree.co/blog/posts/129-perception-a-back-port-of-observable)
  **Published:** `2024-01-09T00:00:00Z`
  **Topics:** Observation & State Management · Swift
  **NeKI brief:** Introduces Perception as a back-port of Swift Observation for older deployment targets. Useful when sharing observation-based SwiftUI architecture before the application can require iOS 17.
- [2023 Year-in-review](https://www.pointfree.co/blog/posts/126-2023-year-in-review)
  **Published:** `2023-12-19T00:00:00Z`
  **Topics:** SwiftUI
  **NeKI brief:** The year review links releases and open-source maintenance to a sustained architecture roadmap. It is useful for locating related projects and understanding sequencing, while individual API behavior still belongs to source documentation.
- [Observable Architecture Beta!](https://www.pointfree.co/blog/posts/125-observable-architecture-beta)
  **Published:** `2023-11-27T00:00:00Z`
  **Topics:** Architecture · Composable Architecture · Observation & State Management · Swift
  **NeKI brief:** Introduces the beta Observable Architecture tools from Point-Free and how existing Composable Architecture code can adopt the observation model. Useful for evaluating migration trade-offs between view-driven observation, testable state, and deployment support.
- [Macro Bonanza](https://www.pointfree.co/blog/posts/121-macro-bonanza)
  **Published:** `2023-11-17T00:00:00Z`
  **Topics:** Macros & Metaprogramming · Swift
  **NeKI brief:** Surveys Swift macro capabilities through concrete generation examples. Use it to compare attached and freestanding macro designs before introducing generated declarations into a production module.
- [Macro Bonanza: Dependencies](https://www.pointfree.co/blog/posts/120-macro-bonanza-dependencies)
  **Published:** `2023-11-16T00:00:00Z`
  **Topics:** Dependency Injection · Macros & Metaprogramming
  **NeKI brief:** A dependency macro can synthesize environment plumbing while keeping live and test implementations interchangeable. The pattern reduces manual injection code, but generated behavior still needs inspection when compiler or macro expansion changes.
- [Macro Bonanza: SwiftUI Navigation](https://www.pointfree.co/blog/posts/119-macro-bonanza-swiftui-navigation)
  **Published:** `2023-11-15T00:00:00Z`
  **Topics:** Macros & Metaprogramming · Swift · SwiftUI
  **NeKI brief:** A navigation macro can derive destination and path plumbing from domain declarations, reducing stringly-typed routing code. The trade-off is compiler-generated structure that must be version-pinned and tested at feature boundaries.
- [Macro Bonanza: Composable Architecture](https://www.pointfree.co/blog/posts/118-macro-bonanza-composable-architecture)
  **Published:** `2023-11-14T00:00:00Z`
  **Topics:** Architecture · Composable Architecture · Macros & Metaprogramming
  **NeKI brief:** Composable Architecture macros can synthesize repetitive reducer and observation plumbing from declared domains. The gain is less boilerplate; the trade-off is compiler-generated behavior that must be reviewed and versioned carefully.
- [Macro Bonanza: Case Paths](https://www.pointfree.co/blog/posts/117-macro-bonanza-case-paths)
  **Published:** `2023-11-13T00:00:00Z`
  **Topics:** Macros & Metaprogramming · Swift
  **NeKI brief:** Case-path macros can derive enum extraction and embedding helpers from declarations, reducing hand-maintained pattern-matching glue. The approach improves consistency while macro expansion remains part of the build surface.
- [Being a good citizen in the land of SwiftSyntax](https://www.pointfree.co/blog/posts/116-being-a-good-citizen-in-the-land-of-swiftsyntax)
  **Published:** `2023-10-17T00:00:00Z`
  **Topics:** Swift
  **NeKI brief:** Explains how SwiftSyntax-based tools should coexist with the compiler ecosystem and its conventions. Follow it when building source transforms that need stable parsing, diagnostics, and respectful package integration.
- [MacroTesting 0.2.0: Test more with less](https://www.pointfree.co/blog/posts/115-macrotesting-0-2-0-test-more-with-less)
  **Published:** `2023-10-03T00:00:00Z`
  **Topics:** Macros & Metaprogramming · Testing
  **NeKI brief:** Describes MacroTesting’s snapshot-based harness for Swift macro expansion, including failure diffs and fixture updates, so compiler-plugin behavior can be reviewed as concise source transformations.
- [A new tool for testing macros in Swift](https://www.pointfree.co/blog/posts/114-a-new-tool-for-testing-macros-in-swift)
  **Published:** `2023-09-18T00:00:00Z`
  **Topics:** Macros & Metaprogramming · Swift · Testing
  **NeKI brief:** Introduces a macro-testing tool that compares expanded source against expected output. Useful for regression-testing code generation without relying only on downstream compilation failures.
- [Inline Snapshot Testing](https://www.pointfree.co/blog/posts/113-inline-snapshot-testing)
  **Published:** `2023-09-13T00:00:00Z`
  **Topics:** Testing
  **NeKI brief:** Introduces inline snapshot testing, keeping expected output beside the test and updating it deliberately when behavior changes; the examples clarify reviewable diffs for serialized values and rendered output.
- [Composable Architecture 1.0](https://www.pointfree.co/blog/posts/112-composable-architecture-1-0)
  **Published:** `2023-07-31T00:00:00Z`
  **Topics:** Architecture · Composable Architecture
  **NeKI brief:** Introduces the 1.0 Composable Architecture model of reducers, state, actions, dependencies, and effects. Useful as a reference for explicit unidirectional data flow and testable SwiftUI features.
- [Reliably testing async code in Swift](https://www.pointfree.co/blog/posts/110-reliably-testing-async-code-in-swift)
  **Published:** `2023-07-19T00:00:00Z`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Analyzes flaky asynchronous tests and presents deterministic scheduling and clock-control techniques, explaining how explicit task coordination removes sleeps and makes concurrent effects reproducible.
- [Announcing Concurrency Extras: Useful, testable Swift concurrency.](https://www.pointfree.co/blog/posts/109-announcing-concurrency-extras-useful-testable-swift-concurrency)
  **Published:** `2023-07-18T00:00:00Z`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** ConcurrencyExtras packages testable helpers around Swift concurrency, giving code explicit control over clocks, task behavior, and isolation in tests. The library addresses determinism without pretending production scheduling can be made globally synchronous.
- [Navigation tools come to the Composable Architecture](https://www.pointfree.co/blog/posts/106-navigation-tools-come-to-the-composable-architecture)
  **Published:** `2023-05-30T00:00:00Z`
  **Topics:** Architecture · Composable Architecture · Testing
  **NeKI brief:** Navigation tools model presentation and destination state inside a feature domain, allowing tests to exercise routing decisions without a live UI. The integration trades imperative convenience for explicit state transitions.
- [Composable navigation beta, part 2](https://www.pointfree.co/blog/posts/105-composable-navigation-beta-part-2)
  **Published:** `2023-04-17T00:00:00Z`
  **Topics:** Architecture · Composable Architecture
  **NeKI brief:** The navigation beta continues a state-driven model for stacks and presentations, emphasizing migration and composition across features. It is useful when evaluating how destination state affects restoration and deep links.
- [Composable navigation beta](https://www.pointfree.co/blog/posts/104-composable-navigation-beta)
  **Published:** `2023-02-27T00:00:00Z`
  **Topics:** Architecture · Composable Architecture · Testing
  **NeKI brief:** Composable navigation represents destination state in reducers, allowing deep-link and test flows to share the same transitions. The beta framing signals that migration APIs and semantics need validation before adoption.
- [Composable Architecture 1.0 Preview](https://www.pointfree.co/blog/posts/103-composable-architecture-1-0-preview)
  **Published:** `2023-02-13T00:00:00Z`
  **Topics:** Architecture · Composable Architecture
  **NeKI brief:** A 1.0 preview gives adopters a migration point for reducer, dependency, and navigation changes before final compatibility promises. It is useful release context, but concrete behavior still belongs to the versioned source.
- [Modern SwiftUI](https://www.pointfree.co/blog/posts/99-modern-swiftui)
  **Published:** `2023-01-27T00:00:00Z`
  **Topics:** Dependency Injection · Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Presents a modern SwiftUI architecture built around state, bindings, and composition rather than imperative view controllers. Useful as a conceptual reference when simplifying older SwiftUI code.
- [Modern SwiftUI: Testing](https://www.pointfree.co/blog/posts/98-modern-swiftui-testing)
  **Published:** `2023-01-27T00:00:00Z`
  **Topics:** Swift · SwiftUI · Testing
  **NeKI brief:** Modern SwiftUI testing focuses on state transitions and dependency behavior before rendering assertions, keeping most tests deterministic. The workflow reserves UI-level checks for behavior that truly crosses the presentation boundary.
- [Modern SwiftUI: Dependencies](https://www.pointfree.co/blog/posts/97-modern-swiftui-dependencies)
  **Published:** `2023-01-26T00:00:00Z`
  **Topics:** Dependency Injection · Swift · SwiftUI
  **NeKI brief:** Modern SwiftUI dependency design keeps feature code independent from live services and makes previews and tests deterministic. The trade-off is explicit dependency plumbing instead of convenient global access.
- [Modern SwiftUI: State-driven navigation](https://www.pointfree.co/blog/posts/96-modern-swiftui-state-driven-navigation)
  **Published:** `2023-01-25T00:00:00Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** State-driven navigation derives destinations from domain state, so deep links and restoration use the same source of truth as user actions. The approach reduces imperative push coordination while making route modeling explicit.
- [Modern SwiftUI: Identified arrays](https://www.pointfree.co/blog/posts/95-modern-swiftui-identified-arrays)
  **Published:** `2023-01-24T00:00:00Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Identified arrays pair stable IDs with collection semantics, letting reducers update one element without losing ordering or replacing unrelated values. The abstraction makes list identity and targeted mutation explicit for SwiftUI features.
- [Modern SwiftUI: Parent-child communication](https://www.pointfree.co/blog/posts/94-modern-swiftui-parent-child-communication)
  **Published:** `2023-01-23T00:00:00Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Modernizes parent-child SwiftUI communication with event-named delegate closures, then extends the pattern to ObservableObject models. Point-Free’s unimplemented closures preserve ergonomic initialization while producing loud runtime warnings or test failures when a parent forgets binding.
- [Modern SwiftUI](https://www.pointfree.co/blog/posts/93-modern-swiftui)
  **Published:** `2023-01-17T00:00:00Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Modern SwiftUI architecture favors value-driven state and explicit dependencies, allowing views to remain projections rather than owners of side effects. The overview is useful for tracing how those boundaries affect testing and navigation.
- [A new library to control dependencies and avoid letting them control you](https://www.pointfree.co/blog/posts/92-a-new-library-to-control-dependencies-and-avoid-letting-them-control-you)
  **Published:** `2023-01-09T00:00:00Z`
  **Topics:** Dependency Injection · Swift
  **NeKI brief:** Introduces Swift Dependencies, extracted from the Composable Architecture, to make feature dependencies explicit and replaceable. Follow it when designing testable Swift code and weighing controlled dependency injection against hidden global or live-service access.
- [2022 Year-in-review](https://www.pointfree.co/blog/posts/88-2022-year-in-review)
  **Published:** `2022-12-19T06:00:00Z`
  **Topics:** SwiftUI
  **NeKI brief:** Recaps Swift Parsing’s 2022 evolution from builder syntax to structured error messages and bidirectional printing. Use its examples to understand how one composable parser description can diagnose malformed input and serialize typed values.
- [swift-parsing: Swift 5.7 improvements](https://www.pointfree.co/blog/posts/87-swift-parsing-swift-5-7-improvements)
  **Published:** `2022-12-08T06:00:00Z`
  **Topics:** Swift
  **NeKI brief:** Swift Parsing's 5.7 improvements refine parser composition and diagnostics while keeping grammar pieces reusable. The update is useful for comparing typed parsing against ad-hoc string processing.
- [Better SwiftUI navigation APIs](https://www.pointfree.co/blog/posts/84-better-swiftui-navigation-apis)
  **Published:** `2022-11-21T06:00:00Z`
  **Topics:** Navigation & Deep Linking · Swift · SwiftUI
  **NeKI brief:** Presents improved SwiftUI navigation APIs and state-driven destination modeling. Follow it when replacing ad-hoc presentation flags with typed navigation state that can support deep links and deterministic tests.
- [Non-exhaustive testing in the Composable Architecture](https://www.pointfree.co/blog/posts/83-non-exhaustive-testing-in-the-composable-architecture)
  **Published:** `2022-10-31T05:00:00Z`
  **Topics:** Architecture · Composable Architecture · Testing
  **NeKI brief:** Non-exhaustive reducer tests focus assertions on behavior relevant to a scenario while allowing unrelated state changes. The approach reduces brittle fixtures but requires teams to decide which omissions would hide a regression.
- [Open Sourcing swift-clocks](https://www.pointfree.co/blog/posts/82-open-sourcing-swift-clocks)
  **Published:** `2022-10-24T05:00:00Z`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** A controllable clock dependency lets asynchronous features test time-based behavior deterministically instead of sleeping in tests. Production code can still use the live clock through the same boundary.
- [Announcing the Reducer Protocol](https://www.pointfree.co/blog/posts/81-announcing-the-reducer-protocol)
  **Published:** `2022-10-10T05:00:00Z`
  **Topics:** Architecture · Composable Architecture
  **NeKI brief:** A reducer protocol makes state transitions and effects explicit as a composable unit, clarifying how feature logic can be tested without a UI. The abstraction trades ceremony for a stable boundary around action handling.
- [Improving Composable Architecture performance](https://www.pointfree.co/blog/posts/80-improving-composable-architecture-performance)
  **Published:** `2022-09-08T05:00:00Z`
  **Topics:** Architecture · Composable Architecture · Performance · Testing
  **NeKI brief:** Performance work in a reducer architecture starts by measuring state propagation and identifying unnecessary copies or view updates. The article routes to concrete optimization trade-offs without abandoning value semantics.
- [Async Composable Architecture](https://www.pointfree.co/blog/posts/79-async-composable-architecture)
  **Published:** `2022-08-08T05:00:00Z`
  **Topics:** Architecture · Composable Architecture · Concurrency · Swift · SwiftUI · Testing
  **NeKI brief:** Async effects integrate structured concurrency into reducer workflows, making cancellation and task lifetime part of feature logic. The design reduces callback plumbing but requires disciplined actor and dependency boundaries.
- [Reverse Engineering SwiftUI’s NavigationPath Codability](https://www.pointfree.co/blog/posts/78-reverse-engineering-swiftui-s-navigationpath-codability)
  **Published:** `2022-07-12T05:00:00Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Reverse-engineering NavigationPath codability treats opaque navigation state as an observed encoding contract rather than a guaranteed API. The investigation is useful for deciding whether persistence should store stable route data instead of framework internals.
- [Introducing XCTUnimplemented](https://www.pointfree.co/blog/posts/77-introducing-xctunimplemented)
  **Published:** `2022-06-29T05:00:00Z`
  **Topics:** Dependency Injection · Testing
  **NeKI brief:** XCTUnimplemented creates test-only dependency implementations that fail on unexpected endpoint use, while explicit placeholders cover required return values. Use it to prove side effects stay absent unless a test deliberately configures them.
- [Open Sourcing URLRouting and VaporRouting](https://www.pointfree.co/blog/posts/75-open-sourcing-urlrouting-and-vaporrouting)
  **Published:** `2022-05-02T05:00:00Z`
  **Topics:** Navigation & Deep Linking
  **NeKI brief:** Models URL endpoints as route-enum cases, then composes parsers that both recognize requests and print URLs. Use it when sharing type-checked deep-link and server-route contracts instead of manually parsing path and query strings.
- [Parser-printer unification](https://www.pointfree.co/blog/posts/74-parser-printer-unification)
  **Published:** `2022-04-11T05:00:00Z`
  **Topics:** Swift
  **NeKI brief:** Parser-printer unification models parsing and serialization as two directions of one composable description. The design reduces duplicated schemas while requiring explicit handling for formats that are not perfectly invertible.
- [Parser Errors](https://www.pointfree.co/blog/posts/73-parser-errors)
  **Published:** `2022-02-14T06:00:00Z`
  **Topics:** Swift
  **NeKI brief:** Composable parser errors can preserve the failing input position and expected alternatives, making diagnostics actionable instead of returning a generic failure. The design balances rich context against the cost of carrying structured error data.
- [Backtracking Parsers](https://www.pointfree.co/blog/posts/72-backtracking-parsers)
  **Published:** `2022-02-09T06:00:00Z`
  **Topics:** Swift
  **NeKI brief:** Backtracking parsers preserve alternatives until later input disambiguates them, trading simpler grammar composition for potentially repeated work. The approach is useful when failure diagnostics and predictable limits are designed together.
- [Introducing Parser Builders](https://www.pointfree.co/blog/posts/71-introducing-parser-builders)
  **Published:** `2022-01-24T06:00:00Z`
  **Topics:** Swift
  **NeKI brief:** Parser builders turn grammar composition into ordinary Swift expressions, making alternatives and sequencing visible in source. The abstraction improves reuse while requiring diagnostics that identify the failing parser branch.
- [Unobtrusive runtime warnings for libraries](https://www.pointfree.co/blog/posts/70-unobtrusive-runtime-warnings-for-libraries)
  **Published:** `2022-01-03T06:00:00Z`
  **Topics:** Networking
  **NeKI brief:** Runtime warnings can surface library misuse without crashing production, then become test failures in controlled contexts. The pattern balances observability with resilience and gives teams a migration path from warning to enforcement.
- [2021 Year-in-review](https://www.pointfree.co/blog/posts/68-2021-year-in-review)
  **Published:** `2021-12-22T06:00:00Z`
  **Topics:** SwiftUI
  **NeKI brief:** Recaps Point-Free’s 2021 SwiftUI architecture work, including rebuilding a SwiftUI application in UIKit and test-support constraints imposed by Xcode module boundaries. Use it as historical context for separating application architecture from platform-specific UI layers.
- [Open Sourcing SwiftUI Navigation](https://www.pointfree.co/blog/posts/66-open-sourcing-swiftui-navigation)
  **Published:** `2021-11-16T06:00:00Z`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Introduces SwiftUI Navigation tools for state-driven routing. Use it when deep links and destination state need a composable, testable alternative to ad-hoc bindings.
- [Point Freebies: Swift Concurrency and More](https://www.pointfree.co/blog/posts/64-point-freebies-swift-concurrency-and-more)
  **Published:** `2021-09-15T05:00:00Z`
  **Topics:** Architecture · Composable Architecture · Concurrency · Swift · SwiftUI · Xcode
  **NeKI brief:** The concurrency collection routes to examples of task cancellation, isolation, and structured lifetime. Use it as a map to concrete implementations, verifying each technique against the current Swift concurrency model.
- [The Composable Architecture ❤️ SwiftUI Bindings](https://www.pointfree.co/blog/posts/63-the-composable-architecture-%EF%B8%8F-swiftui-bindings)
  **Published:** `2021-09-06T05:00:00Z`
  **Topics:** Architecture · Composable Architecture · Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Composable Architecture bindings route UI edits through actions and reducer state instead of mutating model references directly. The integration keeps effects and validation testable while adding explicit binding case definitions.
- [Open Sourcing: Custom Dump](https://www.pointfree.co/blog/posts/62-open-sourcing-custom-dump)
  **Published:** `2021-08-23T05:00:00Z`
  **Topics:** Testing
  **NeKI brief:** Introduces Custom Dump for structured value comparison and diagnostics. Use it when test failures need readable nested differences rather than opaque string descriptions.
- [Better Performance Bonanza](https://www.pointfree.co/blog/posts/61-better-performance-bonanza)
  **Published:** `2021-07-14T05:00:00Z`
  **Topics:** Architecture · Composable Architecture · Performance
  **NeKI brief:** Performance improvements are most credible when accompanied by before-and-after measurements and a clear account of changed work. The collection routes to concrete Swift optimization examples rather than generic speed advice.
- [Open Sourcing Identified Collections](https://www.pointfree.co/blog/posts/60-open-sourcing-identified-collections)
  **Published:** `2021-07-12T05:00:00Z`
  **Topics:** SwiftUI
  **NeKI brief:** Introduces identified collections for stable element lookup and mutation. Use it when a feature stores ordered state whose elements need identity-safe updates.
- [Announcing SwitchStore for the Composable Architecture](https://www.pointfree.co/blog/posts/59-announcing-switchstore-for-the-composable-architecture)
  **Published:** `2021-06-14T05:00:00Z`
  **Topics:** Architecture · Composable Architecture · Performance
  **NeKI brief:** SwitchStore selects a view branch from enum state while preserving the reducer as the state-transition owner. The pattern improves exhaustive UI modeling, but identity and child-store lifetime need deliberate handling.
- [A Tour of isowords](https://www.pointfree.co/blog/posts/57-a-tour-of-isowords)
  **Published:** `2021-05-12T05:00:00Z`
  **Topics:** Swift
  **NeKI brief:** The isowords tour uses a real application to connect reducer composition, dependencies, effects, and persistence. It is a useful end-to-end architecture reference rather than an isolated pattern recipe.
- [Better Testing Bonanza](https://www.pointfree.co/blog/posts/56-better-testing-bonanza)
  **Published:** `2021-03-22T05:00:00Z`
  **Topics:** Testing
  **NeKI brief:** The testing collection emphasizes deterministic dependencies, state assertions, and focused failure output for Swift features. Its value is a workflow for reducing flaky tests without weakening behavioral coverage.
- [Open Sourcing isowords](https://www.pointfree.co/blog/posts/55-open-sourcing-isowords)
  **Published:** `2021-03-17T16:00:00Z`
  **Topics:** Functional Programming
  **NeKI brief:** Explains the open sourcing of isowords and exposes a production game's architecture. Use it as a case study for composable state, effects, and testable game feature design.
- [Announcing: isowords](https://www.pointfree.co/blog/posts/54-announcing-isowords)
  **Published:** `2021-03-17T07:00:00Z`
  **Topics:** Functional Programming
  **NeKI brief:** isowords demonstrates an application assembled from independently testable features, dependencies, and effects. Its open-source release is valuable for tracing architecture decisions through a nontrivial codebase.
- [Composable Architecture Test Store Improvements](https://www.pointfree.co/blog/posts/53-composable-architecture-test-store-improvements)
  **Published:** `2021-03-08T16:00:00Z`
  **Topics:** Architecture · Composable Architecture · Testing
  **NeKI brief:** Test-store improvements make action sequencing and state assertions clearer while keeping effects under test control. The workflow improves failure diagnosis, but tests still need to describe meaningful user-visible transitions.
- [Composable Forms: Say “Bye” to Boilerplate!](https://www.pointfree.co/blog/posts/52-composable-forms-say-bye-to-boilerplate)
  **Published:** `2021-02-01T06:00:00Z`
  **Topics:** Architecture · Composable Architecture
  **NeKI brief:** Composable forms derive validation and field state from domain structure, reducing repeated UI glue. The pattern centralizes rules but requires careful modeling of partial edits and submission effects.
- [2020 Year-in-review](https://www.pointfree.co/blog/posts/50-2020-year-in-review)
  **Published:** `2020-12-23T06:00:00Z`
  **Topics:** Architecture · Composable Architecture
  **NeKI brief:** Recaps 2020 Composable Architecture development: feature composition, dependency control without protocol proliferation, and the 0.1.0 library release. Use it as historical context for why dependencies and reducer architecture became explicit design boundaries.
- [Open Sourcing Parsing](https://www.pointfree.co/blog/posts/49-open-sourcing-parsing)
  **Published:** `2020-12-21T06:00:00Z`
  **Topics:** Performance
  **NeKI brief:** Open-sourcing a parsing library makes parser composition, diagnostics, and performance trade-offs inspectable by users. It is a routing lead for comparing typed grammar models against handwritten string parsing.
- [The Composable Architecture and SwiftUI Alerts](https://www.pointfree.co/blog/posts/47-the-composable-architecture-and-swiftui-alerts)
  **Published:** `2020-06-30T04:00:00Z`
  **Topics:** Architecture · Composable Architecture · Swift · SwiftUI
  **NeKI brief:** Alerts modeled as reducer state turn presentation and user responses into testable actions rather than imperative callbacks. The approach keeps dismissal, confirmation, and side effects in one transition system.
- [Core Motion support in the Composable Architecture](https://www.pointfree.co/blog/posts/46-core-motion-support-in-the-composable-architecture)
  **Published:** `2020-06-22T04:00:00Z`
  **Topics:** Architecture · Composable Architecture
  **NeKI brief:** Core Motion support is injected as a dependency so sensor updates can be represented as effects and substituted in tests. The boundary separates hardware lifecycle from feature state and cancellation logic.
- [Open Sourcing CombineSchedulers](https://www.pointfree.co/blog/posts/45-open-sourcing-combineschedulers)
  **Published:** `2020-06-15T04:00:00Z`
  **Topics:** Testing
  **NeKI brief:** Injectable Combine schedulers make timing and thread delivery explicit, allowing asynchronous pipelines to be tested without real delays. The library separates scheduling policy from publisher transformation logic.
- [Instrumenting features built in the Composable Architecture](https://www.pointfree.co/blog/posts/44-instrumenting-features-built-in-the-composable-architecture)
  **Published:** `2020-05-27T05:00:00Z`
  **Topics:** Architecture · Composable Architecture
  **NeKI brief:** Feature instrumentation can be modeled as a dependency or reducer effect, making analytics events follow the same state transitions as product behavior. This keeps telemetry testable and avoids scattered logging calls.
- [Core Location support in the Composable Architecture](https://www.pointfree.co/blog/posts/43-core-location-support-in-the-composable-architecture)
  **Published:** `2020-05-20T05:00:00Z`
  **Topics:** Architecture · Composable Architecture
  **NeKI brief:** Core Location is exposed as a dependency so authorization, updates, and cancellation become feature effects rather than view-controller callbacks. The boundary makes sensor behavior deterministic in tests.
- [Composable Architecture, the library](https://www.pointfree.co/blog/posts/41-composable-architecture-the-library)
  **Published:** `2020-05-04T05:00:00Z`
  **Topics:** Architecture · Composable Architecture · Testing
  **NeKI brief:** Introduces Point-Free's Composable Architecture and its state, action, reducer, and effect model. Use it when evaluating a unidirectional architecture with testable feature boundaries.
- [Announcing Episode Collections](https://www.pointfree.co/blog/posts/40-announcing-episode-collections)
  **Published:** `2020-03-11T06:00:00Z`
  **Topics:** Swift
  **NeKI brief:** Episode collections package related architecture material into a navigable sequence, useful for finding a complete workflow rather than isolated snippets. They are discovery metadata, while source examples provide the technical evidence.
- [Open Sourcing Case Paths](https://www.pointfree.co/blog/posts/38-open-sourcing-case-paths)
  **Published:** `2020-02-04T07:00:00Z`
  **Topics:** Observation & State Management
  **NeKI brief:** Case paths provide extraction and embedding operations for enum cases, enabling generic navigation and composition over sum types. The library makes case-focused APIs reusable while preserving explicit failure when a case does not match.
- [Snapshot Testing SwiftUI](https://www.pointfree.co/blog/posts/35-snapshot-testing-swiftui)
  **Published:** `2019-12-23T06:00:00Z`
  **Topics:** Swift · SwiftUI · Testing
  **NeKI brief:** Snapshot testing SwiftUI renders a view under controlled traits and compares pixels or images against a reference. The technique catches visual regressions, but needs deterministic data, fonts, and rendering environments.
- [A Crash Course in Combine](https://www.pointfree.co/blog/posts/32-a-crash-course-in-combine)
  **Published:** `2019-11-20T06:00:00Z`
  **Topics:** Developer Community & Business
  **NeKI brief:** Introduces Combine's publisher/subscriber model through practical pipelines and operators. Follow it when onboarding a codebase that still uses Combine and you need a conceptual route to composition, cancellation, and testing.
- [Higher-Order Snapshot Testing](https://www.pointfree.co/blog/posts/31-higher-order-snapshot-testing)
  **Published:** `2019-11-07T06:00:00Z`
  **Topics:** Testing
  **NeKI brief:** Higher-order snapshot helpers wrap a test strategy with shared device, trait, or naming configuration. The abstraction removes repeated setup while keeping each feature's visual assertion explicit.
- [SwiftUI and State Management Corrections](https://www.pointfree.co/blog/posts/30-swiftui-and-state-management-corrections)
  **Published:** `2019-07-30T06:00:00Z`
  **Topics:** Observation & State Management · Swift · SwiftUI · Xcode
  **NeKI brief:** Corrections to SwiftUI state guidance are valuable because ownership and identity mistakes can create stale or duplicated UI. The article routes readers to revised reasoning rather than preserving an obsolete pattern.
- [Open Sourcing Enum Properties](https://www.pointfree.co/blog/posts/28-open-sourcing-enum-properties)
  **Published:** `2019-04-29T06:00:00Z`
  **Topics:** Swift
  **NeKI brief:** Enum properties derive predicates and associated-value accessors from case structure, making domain branching reusable. The library reduces repeated switches while preserving explicit failure for nonmatching cases.
- [Open Sourcing Gen](https://www.pointfree.co/blog/posts/27-open-sourcing-gen)
  **Published:** `2019-03-18T06:00:00Z`
  **Topics:** Swift
  **NeKI brief:** Gen models random-data generation as composable values, enabling property-style tests to vary inputs without hand-writing every fixture. The approach improves coverage while generators still need constraints that reflect valid domains.
- [Announcing swift-html 0.2.0](https://www.pointfree.co/blog/posts/26-announcing-swift-html-0-2-0)
  **Published:** `2019-01-08T09:00:00Z`
  **Topics:** Swift · Testing
  **NeKI brief:** Type-safe HTML construction models elements and attributes in Swift values, catching structural mistakes before rendering. The library trades template familiarity for compiler-checked composition and reusable view functions.
- [SnapshotTesting 1.0: Delightful Swift snapshot testing](https://www.pointfree.co/blog/posts/23-snapshottesting-1-0-delightful-swift-snapshot-testing)
  **Published:** `2018-12-03T09:00:00Z`
  **Topics:** Swift · Testing
  **NeKI brief:** Introduces SnapshotTesting for asserting rendered views and other values against recorded representations. Follow it when visual regressions need reviewable diffs and test fixtures must capture exact UI state.
- [Some news about contramap](https://www.pointfree.co/blog/posts/22-some-news-about-contramap)
  **Published:** `2018-10-29T09:00:00Z`
  **Topics:** Functional Programming
  **NeKI brief:** Contramap adapts a consumer to accept a broader input by transforming it before use, a dual to mapping outputs. The article explains how this functional operation composes formatting and validation behavior.
- [How to Control the World](https://www.pointfree.co/blog/posts/21-how-to-control-the-world)
  **Published:** `2018-10-09T14:00:00Z`
  **Topics:** Architecture · Dependency Injection · Testing
  **NeKI brief:** Controlling dependencies through explicit environment values makes effects replaceable in tests and previews. The functional approach avoids hidden globals, but requires deliberate propagation of the dependency context.
- [Random Zalgo Generator](https://www.pointfree.co/blog/posts/19-random-zalgo-generator)
  **Published:** `2018-09-20T06:29:36Z`
  **Topics:** Swift
  **NeKI brief:** A random Zalgo generator applies Unicode combining marks to base characters, demonstrating how visually extreme text can remain valid scalar sequences. It is a useful reminder to test text rendering and normalization boundaries.
- [Type-safe HTML with Kitura](https://www.pointfree.co/blog/posts/18-type-safe-html-with-kitura)
  **Published:** `2018-09-13T06:00:01Z`
  **Topics:** Swift
  **NeKI brief:** Type-safe HTML integrated with Kitura turns server responses into compiler-checked view composition instead of string templates. The adapter keeps routing and rendering separate while preserving reusable HTML components.
- [Type-safe HTML with Vapor](https://www.pointfree.co/blog/posts/17-type-safe-html-with-vapor)
  **Published:** `2018-09-13T06:00:00Z`
  **Topics:** Swift
  **NeKI brief:** Type-safe HTML with Vapor expresses server views as compiler-checked Swift composition instead of string templates. The integration keeps routing and rendering boundaries explicit while reusing typed element builders.
- [Open sourcing swift-html: A Type-Safe Alternative to Templating Languages in Swift](https://www.pointfree.co/blog/posts/16-open-sourcing-swift-html-a-type-safe-alternative-to-templating-languages-in-swift)
  **Published:** `2018-09-12T07:57:04Z`
  **Topics:** Swift
  **NeKI brief:** swift-html models markup as Swift values, allowing element structure and attributes to be checked before rendering. The library trades template syntax for composable functions and stronger refactoring support.
- [Overture 0.3.0: Now with Zip](https://www.pointfree.co/blog/posts/15-overture-0-3-0-now-with-zip)
  **Published:** `2018-08-17T05:57:04Z`
  **Topics:** Functional Programming
  **NeKI brief:** Functional zip combines independent computations into one result while preserving each input's structure. The release illustrates how small compositional primitives can remove repetitive coordination code.
- [Open Sourcing Validated](https://www.pointfree.co/blog/posts/14-open-sourcing-validated)
  **Published:** `2018-08-17T05:57:03Z`
  **Topics:** Swift
  **NeKI brief:** Introduces Validated for accumulating independent validation failures instead of stopping at the first error. Follow it when forms or data imports should report all invalid fields in one pass.
- [Solutions to Exercises: Zip Part 3](https://www.pointfree.co/blog/posts/13-solutions-to-exercises-zip-part-3)
  **Published:** `2018-08-16T05:57:03Z`
  **Topics:** Functional Programming
  **NeKI brief:** Zip exercises demonstrate how combining effects depends on the algebra of the container, not merely tuple construction. The solutions are useful for recognizing when independent operations can be composed safely.
- [Solutions to Exercises: Zip Part 2](https://www.pointfree.co/blog/posts/12-solutions-to-exercises-zip-part-2)
  **Published:** `2018-08-15T05:57:03Z`
  **Topics:** Functional Programming
  **NeKI brief:** Zip composition combines independent structures positionally, exposing how success and failure behavior depends on the underlying effect. The exercises provide a concrete way to test that intuition.
- [Solutions to Exercises: Zip Part 1](https://www.pointfree.co/blog/posts/11-solutions-to-exercises-zip-part-1)
  **Published:** `2018-08-14T05:57:03Z`
  **Topics:** Functional Programming
  **NeKI brief:** Zip exercises make positional composition explicit, revealing how independent values and effects combine into one result. The examples help distinguish applicative composition from sequential dependency.
- [Conditional Coding](https://www.pointfree.co/blog/posts/8-conditional-coding)
  **Published:** `2018-07-02T09:57:03Z`
  **Topics:** Swift
  **NeKI brief:** Conditional coding composes behavior based on a predicate while keeping both branches as ordinary values. The functional pattern clarifies when conditional configuration can replace deeply nested control flow.
- [Open Sourcing NonEmpty](https://www.pointfree.co/blog/posts/7-open-sourcing-nonempty)
  **Published:** `2018-06-25T09:57:03Z`
  **Topics:** Swift
  **NeKI brief:** NonEmpty encodes the invariant that a collection has at least one element. Use it when APIs should eliminate repeated empty-case checks through a stronger input type.
- [Tagged Seconds and Milliseconds](https://www.pointfree.co/blog/posts/6-tagged-seconds-and-milliseconds)
  **Published:** `2018-06-18T14:36:46Z`
  **Topics:** Functional Programming
  **NeKI brief:** Tagged time units prevent seconds and milliseconds from being mixed even though both are numeric values. The small type wrapper moves a common conversion error from runtime into the compiler.
- [Styling with Functions: Free for Everyone!](https://www.pointfree.co/blog/posts/5-styling-with-functions-free-for-everyone)
  **Published:** `2018-05-30T09:57:03Z`
  **Topics:** UIKit
  **NeKI brief:** Styling with functions treats visual configuration as composable transformations rather than scattered modifier chains. The approach can improve reuse, while overly abstract style functions may obscure local intent.
- [Overture: Now with Functional Setters](https://www.pointfree.co/blog/posts/4-overture-now-with-functional-setters)
  **Published:** `2018-05-15T09:57:03Z`
  **Topics:** Functional Programming
  **NeKI brief:** Functional setters transform immutable values by returning updated copies, making configuration composable without shared mutation. The pattern clarifies how value semantics can support fluent construction.
- [Solutions to Exercises: Contravariance](https://www.pointfree.co/blog/posts/3-solutions-to-exercises-contravariance)
  **Published:** `2018-05-07T04:01:02Z`
  **Topics:** Functional Programming
  **NeKI brief:** Contravariance adapts consumers to broader input types by precomposing a transformation. The exercise grounds an abstract variance rule in composable Swift functions and type-safe API design.
- [Case Study: Algebraic Data Types](https://www.pointfree.co/blog/posts/2-case-study-algebraic-data-types)
  **Published:** `2018-04-23T04:01:02Z`
  **Topics:** Concurrency
  **NeKI brief:** Algebraic data types model product and sum domains explicitly, making impossible states harder to represent. The case study connects those types to exhaustive logic and maintainable feature state.
- [Announcing Point-Free Pointers!](https://www.pointfree.co/blog/posts/1-announcing-point-free-pointers)
  **Published:** `2018-04-23T04:01:02Z`
  **Topics:** Functional Programming
  **NeKI brief:** Point-Free Pointers collects focused functional-programming material around small composable ideas. It is discovery context for the linked experiments, not a technical specification itself.
