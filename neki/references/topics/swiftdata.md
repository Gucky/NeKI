# SwiftData

Third-party reading leads collected from NeKI sources. The links may be useful perspectives, but are not vetted recommendations or authoritative API guidance. NeKI publishes routing metadata, not the linked articles' text.

**Scope:** SwiftData models, queries, migrations, CloudKit integration, and data modelling.

- Last collected: `2026-08-27T19:22:09Z`
- Indexed links shown: **144**

## Direct-source reading

- [New in SQLiteData: Sectioned queries](https://www.pointfree.co/blog/posts/219-new-in-sqlitedata-sectioned-queries) — Point-Free · article catalogue
  **Published:** `2026-07-27T00:00:00Z`
  **NeKI brief:** Explains SQLiteData 1.8's @FetchAll(sectionBy:) grouping, which stays in SQLite and supports arbitrary SQL expressions, joins, ordering, dynamic reloads, and older OS versions. FetchKeyRequest covers typed or more complex section shapes.
- [Getting Started with SwiftData in iOS 26 | Kodeco](https://www.kodeco.com/49976785-getting-started-with-swiftdata-in-ios-26) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The iOS 26 SwiftData starter introduces model types, containers and SwiftUI queries as one persistence flow. Follow it to assess how observation and schema choices shape a modern app, while checking migration and background-context needs beyond the sample.
- [SwiftData: Simplifying Persistence in iOS Apps | Kodeco](https://www.kodeco.com/40504096-swiftdata-simplifying-persistence-in-ios-apps) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Explains SwiftData's @Model macro, model container, and context-driven persistence as a Swift-native layer over local storage. It is useful for evaluating migration from Core Data while keeping schema and context lifetime decisions explicit.
- [A Deep Dive into SwiftData migrations – Donny Wals](https://www.donnywals.com/a-deep-dive-into-swiftdata-migrations) — Donny Wals · article catalogue
  **Published:** `2026-01-19T12:23:36+00:00`
  **NeKI brief:** Walks through SwiftData migration planning with the uncomfortable case of real users upgrading persisted data. Use it to identify schema-change hazards, staged model versions, and validation work needed before shipping a store update.
- [Performing search with SwiftData in a SwiftUI app](https://www.createwithswift.com/performing-search-with-swiftdata-in-a-swiftui-app) — Create with Swift · article catalogue
  **Published:** `2025-10-07T13:00:01.000Z`
  **NeKI brief:** Builds SwiftData search in SwiftUI using predicates and query-driven state. Use it when filtering persisted models and needing search text, sort order, and result updates to remain declarative.
- [New in SQLiteData: Column groups and inheritance](https://www.pointfree.co/blog/posts/186-new-in-sqlitedata-column-groups-and-inheritance) — Point-Free · article catalogue
  **Published:** `2025-10-02T00:00:00Z`
  **NeKI brief:** Explains SQLiteData column groups and model inheritance as typed schema composition, reducing repetition while preserving SQL constraints. The design is a concrete alternative to duplicating fields across related tables.
- [SQLiteData 1.0: An alternative to SwiftData with CloudKit sync and sharing](https://www.pointfree.co/blog/posts/184-sqlitedata-1-0-an-alternative-to-swiftdata-with-cloudkit-sync-and-sharing) — Point-Free · article catalogue
  **Published:** `2025-09-17T00:00:00Z`
  **NeKI brief:** SQLiteData combines SQLite persistence with CloudKit synchronization and sharing. Use it when SwiftData lacks required deployment or SQL control, while evaluating the operational cost of its sync model.
- [SQLiteData 0.7.0: User-defined SQL functions](https://www.pointfree.co/blog/posts/183-sharinggrdb-0-7-0-user-defined-sql-functions) — Point-Free · article catalogue
  **Published:** `2025-09-03T00:00:00Z`
  **NeKI brief:** SQLiteData exposes user-defined SQL functions through Swift declarations, preserving type-checked query construction while allowing database-specific computation. The extension point trades portability for expressiveness and requires controlling registration and migration behavior.
- [SQLiteData 0.6.0: Full-text search and more](https://www.pointfree.co/blog/posts/182-sharinggrdb-0-6-0-full-text-search-and-more) — Point-Free · article catalogue
  **Published:** `2025-08-21T00:00:00Z`
  **NeKI brief:** The SQLiteData update layers SQLite full-text search onto Swift query APIs, turning tokenization and ranking into database work rather than in-memory filtering. The design improves scale but makes index configuration and match semantics part of the model.
- [A SwiftData alternative with SQLite + CloudKit: Public beta](https://www.pointfree.co/blog/posts/181-a-swiftdata-alternative-with-sqlite-cloudkit-public-beta) — Point-Free · article catalogue
  **Published:** `2025-08-04T00:00:00Z`
  **NeKI brief:** Announces a SQLite and CloudKit synchronization alternative to SwiftData. Use it to investigate relational persistence and sync options, then verify API maturity and operational trade-offs before adoption.
- [High Performance SwiftData Apps](https://blog.jacobstechtavern.com/p/high-performance-swiftdata) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2025-07-14T15:02:48.303Z`
  **NeKI brief:** Investigates SwiftData performance problems through measurements and diagnosis rather than assuming the model layer is free. Use it to identify query, observation, and persistence costs before changing an app's storage design.
- [A SwiftData alternative with SQLite + CloudKit: Private alpha](https://www.pointfree.co/blog/posts/179-a-swiftdata-alternative-with-sqlite-cloudkit-private-alpha) — Point-Free · article catalogue
  **Published:** `2025-06-30T00:00:00Z`
  **NeKI brief:** The private alpha combines SQLite persistence with CloudKit synchronization as an alternative to SwiftData's storage model. It is useful for evaluating explicit schema and sync control, while the preview status signals API and migration risk.
- [We’re going live soon!](https://www.pointfree.co/blog/posts/178-we-re-going-live-soon) — Point-Free · article catalogue
  **Published:** `2025-06-25T00:00:00Z`
  **NeKI brief:** The CloudKit synchronization preview positions SQLiteData as an explicit persistence layer with sync machinery added incrementally. The announcement is a routing lead for evaluating schema ownership and conflict behavior before adopting a beta.
- [Live stream reminder: A SwiftData alternative with CloudKit synchronization](https://www.pointfree.co/blog/posts/177-live-stream-reminder-a-swiftdata-alternative-with-cloudkit-synchronization) — Point-Free · article catalogue
  **Published:** `2025-06-24T00:00:00Z`
  **NeKI brief:** The planned CloudKit synchronization work extends a SQLite-backed SwiftData alternative rather than hiding storage behind framework defaults. It is useful when comparing explicit database control with SwiftData's integrated model and sync assumptions.
- [Free Episode: SwiftData versus SQL Query Builder](https://www.pointfree.co/blog/posts/174-free-episode-swiftdata-versus-sql-query-builder) — Point-Free · article catalogue
  **Published:** `2025-06-12T00:00:00Z`
  **NeKI brief:** Compares SwiftData with a SQL query-builder approach. Use it when choosing between declarative model persistence and explicit relational queries, migrations, and database-level control.
- [WWDC 2025 First Impressions - As Expected, Yet Unexpected](https://fatbobman.com/en/posts/wwdc-2025-first-impressions) — Fatbobman · article catalogue
  **Published:** `2025-06-11T00:12:00.000Z`
  **NeKI brief:** Offers first impressions of WWDC 2025 through Liquid Glass, SwiftUI, SwiftData, Foundation Models, and macros. Follow it for ecosystem-level context and competing priorities, not as a substitute for API-level migration guidance.
- [SwiftData Predicates For Parent Relationships](https://useyourloaf.com/blog/swiftdata-predicates-for-parent-relationships) — Use Your Loaf · article catalogue
  **Published:** `2025-05-05T10:31:41+01:00`
  **NeKI brief:** Builds a #Predicate over an optional SwiftData relationship by comparing the parent’s persistentModelID, then extends the pattern to multiple parent IDs. This is useful when CloudKit-compatible optional relationships must still support parameterized child queries.
- [Building Type‑Safe, High‑Performance SwiftData / Core Data Models](https://fatbobman.com/en/posts/building-typesafe-highperformance-swiftdata-core-data-models) — Fatbobman · article catalogue
  **Published:** `2025-04-23T14:00:00.000Z`
  **NeKI brief:** Explores type-safe, high-performance model design across SwiftData and Core Data, with attention to schema choices and query behavior. Use it when shaping a persistence layer that balances compile-time clarity, migration needs, and runtime performance.
- [A fast, lightweight replacement for SwiftData](https://www.pointfree.co/blog/posts/170-a-fast-lightweight-replacement-for-swiftdata) — Point-Free · article catalogue
  **Published:** `2025-04-22T00:00:00Z`
  **NeKI brief:** The proposed SwiftData replacement keeps SQL as the persistence core while exposing ergonomic Swift APIs for queries and mutations. The trade-off is explicit schema and query control in exchange for more database concepts at the application boundary.
- [SwiftData Limitations - What to Know Before Adopting SwiftData](https://fatbobman.com/en/posts/key-considerations-before-using-swiftdata) — Fatbobman · article catalogue
  **Published:** `2025-03-12T14:00:00.000Z`
  **NeKI brief:** Evaluates SwiftData's practical limits before adoption. Use it when deciding whether its model, migration, query, or synchronization behavior fits a production persistence requirement.
- [SQLiteData: A SwiftData Alternative](https://www.pointfree.co/blog/posts/168-sharinggrdb-a-swiftdata-alternative) — Point-Free · article catalogue
  **Published:** `2025-02-14T17:00:00Z`
  **NeKI brief:** Introduces SharingGRDB as a SQLite-backed state-sharing approach for SwiftUI, combining persistence with observation. Useful when evaluating a relational alternative to SwiftData for shared, queryable application state.
- [Parsing and the Advent of Code](https://www.pointfree.co/blog/posts/158-parsing-and-the-advent-of-code) — Point-Free · article catalogue
  **Published:** `2024-12-01T00:00:00Z`
  **NeKI brief:** The parsing project applies composable parser primitives to Advent of Code inputs, showing how grammar structure can replace brittle string splitting. It is useful for evaluating error propagation and parser reuse in production Swift code.
- [Using Transactions Instead of Save in SwiftData and Core Data](https://fatbobman.com/en/posts/using-transactions-instead-of-save-in-swiftdata-and-core-data) — Fatbobman · article catalogue
  **Published:** `2024-11-20T14:00:00.000Z`
  **NeKI brief:** Compares transaction-style persistence work with ordinary save calls in SwiftData and Core Data. Use it when batching mutations, rollback boundaries, and consistency matter more than one-off writes.
- [Mastering Data Tracking and Notifications in Core Data and SwiftData](https://fatbobman.com/en/posts/mastering-data-tracking-and-notifications-in-core-data-and-swiftdata) — Fatbobman · article catalogue
  **Published:** `2024-11-06T14:00:00.000Z`
  **NeKI brief:** Explores change tracking and notifications in Core Data and SwiftData. Use it when UI or synchronization logic must react to persistence mutations without polling or broad refreshes.
- [Reinventing Core Data Development with SwiftData Principles](https://fatbobman.com/en/posts/reinventing-core-data-development-with-swiftdata-principles) — Fatbobman · article catalogue
  **Published:** `2024-10-16T14:00:00.000Z`
  **NeKI brief:** Examines SwiftData through Core Data's persistence principles, highlighting schema, context, and migration trade-offs. Useful when adopting SwiftData without discarding lessons from mature persistence architecture.
- [How to run Swift Data and Core Data operations in the background and share models across concurrency contexts](https://www.polpiella.dev/core-data-swift-data-concurrency) — Pol Piella · article catalogue
  **Published:** `2024-10-04T00:00:00.000Z`
  **NeKI brief:** Core Data and SwiftData models are context-bound, so background work must pass IDs or values rather than share managed objects across threads. The article builds a stack around that boundary to prevent races and context violations.
- [NSManagedObjectID and PersistentIdentifier - Mastering Data Identifiers in Core Data and SwiftData](https://fatbobman.com/en/posts/nsmanagedobjectid-and-persistentidentifier) — Fatbobman · article catalogue
  **Published:** `2024-09-25T14:00:00.000Z`
  **NeKI brief:** Core Data's NSManagedObjectID and SwiftData's PersistentIdentifier encode object identity differently across stores and contexts. Comparing their lifecycle and URI-style use helps diagnose stale references and choose safe handoff values between persistence layers.
- [SwiftData Expressions](https://useyourloaf.com/blog/swiftdata-expressions) — Use Your Loaf · article catalogue
  **Published:** `2024-09-09T13:03:47+01:00`
  **NeKI brief:** Compares Core Data NSExpression aggregate fetches with iOS 18 SwiftData predicate expressions, showing the newer API’s current limitations rather than promising a drop-in replacement. Follow it when deciding whether database-side min/max work is practical.
- [Considerations for Using Codable and Enums in SwiftData Models](https://fatbobman.com/en/posts/considerations-for-using-codable-and-enums-in-swiftdata-models) — Fatbobman · article catalogue
  **Published:** `2024-08-14T14:00:00.000Z`
  **NeKI brief:** SwiftData stores Codable structs and enums through generated persistence representations, which affects predicates, migrations, and queryability. The examples expose where convenient model types become opaque storage and when a normalized property is safer.
- [SwiftData Indexes](https://useyourloaf.com/blog/swiftdata-indexes) — Use Your Loaf · article catalogue
  **Published:** `2024-07-25T14:52:41+01:00`
  **NeKI brief:** Shows SwiftData fetch indexes arriving in iOS 18 through the @Index model macro, while warning that the feature does not back-deploy to iOS 17 and Xcode 16 may still display an outdated incompatibility warning.
- [Impressions on WWDC 2024](https://fatbobman.com/en/posts/impressions-on-wwdc-2024) — Fatbobman · article catalogue
  **Published:** `2024-06-17T00:12:00.000Z`
  **NeKI brief:** The WWDC24 impressions connect new SwiftUI and platform capabilities to migration concerns, providing community prioritization that should be checked against current SDK documentation.
- [SwiftData in WWDC 2024 - The Revolution Continues, Stability Still Awaits](https://fatbobman.com/en/posts/swiftdata-in-wwdc2024) — Fatbobman · article catalogue
  **Published:** `2024-06-12T00:12:00.000Z`
  **NeKI brief:** WWDC 2024 SwiftData additions promise richer querying and persistence, but practical stability and migration concerns remain. This review helps separate announced API surface from production readiness when planning adoption.
- [Before WWDC 2024 - The Future Potential and Real Challenges of SwiftData](https://fatbobman.com/en/posts/before-wwdc-2024-swiftdata) — Fatbobman · article catalogue
  **Published:** `2024-05-29T00:12:00.000Z`
  **NeKI brief:** The pre-WWDC survey identifies SwiftData's missing capabilities and rough edges from real projects, turning feature requests into concrete evaluation criteria. Follow it to compare expectations with later framework changes.
- [Before WWDC 2024 - Reviewing Key SwiftUI Upgrades from 2019 to 2023 and Their Impact](https://fatbobman.com/en/posts/before-wwdc-2024) — Fatbobman · article catalogue
  **Published:** `2024-05-22T00:12:00.000Z`
  **NeKI brief:** The pre-WWDC review traces SwiftUI's accumulated layout, navigation, and observation upgrades, showing which old workarounds became obsolete. It is useful for planning cleanup while keeping deployment-target constraints explicit.
- [Core Data Reform - Achieving Elegant Concurrency Operations like SwiftData](https://fatbobman.com/en/posts/core-data-reform-achieving-elegant-concurrency-operations-like-swiftdata) — Fatbobman · article catalogue
  **Published:** `2024-04-18T00:20:00.000Z`
  **NeKI brief:** The proposed Core Data reform wraps contexts and queue confinement to approximate SwiftData's actor-oriented access model. It is useful when modernizing legacy persistence while preserving existing stores and managed-object APIs.
- [How to use SwiftData outside SwiftUI](https://blog.jacobstechtavern.com/p/swiftdata-outside-swiftui) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2024-04-15T16:15:46.653Z`
  **NeKI brief:** Uses SwiftData outside SwiftUI by explicitly constructing and injecting ModelContainer and ModelContext dependencies, preserving persistent-model access in services, tests, and non-view workflows without relying on environment propagation.
- [New Frameworks, New Mindset - Unveiling the Observation and SwiftData Frameworks](https://fatbobman.com/en/posts/new-frameworks-new-mindset) — Fatbobman · article catalogue
  **Published:** `2024-04-03T00:12:00.000Z`
  **NeKI brief:** Observation and SwiftData replace several established Combine and Core Data habits, but their value depends on understanding new ownership and invalidation rules. This overview is useful for planning migration boundaries instead of mechanically swapping annotations.
- [Practical SwiftData - Building SwiftUI Applications with Modern Approaches](https://fatbobman.com/en/posts/practical-swiftdata-building-swiftui-applications-with-modern-approaches) — Fatbobman · article catalogue
  **Published:** `2024-03-21T00:20:00.000Z`
  **NeKI brief:** Examines practical SwiftData application structure, including strict-concurrency challenges, model contexts, and SwiftUI integration. Use it to evaluate persistence boundaries and actor isolation before scaling a data-driven app beyond a demo.
- [Core Data staged migrations](https://www.polpiella.dev/staged-migrations) — Pol Piella · article catalogue
  **Published:** `2024-03-15T00:00:00.000Z`
  **NeKI brief:** Core Data staged migrations split a model change into explicit mapping steps managed by `NSStagedMigrationManager`. This makes complex schema evolution testable and reviewable, while requiring each intermediate model and mapping to remain supported.
- [How to Dynamically Construct Complex Predicates for SwiftData](https://fatbobman.com/en/posts/how-to-dynamically-construct-complex-predicates-for-swiftdata) — Fatbobman · article catalogue
  **Published:** `2024-03-07T00:12:00.000Z`
  **NeKI brief:** Dynamic SwiftData predicates are assembled from optional clauses rather than interpolated strings, preserving type checking while supporting user-selected filters. The patterns help diagnose compiler limitations and keep query composition testable.
- [Swift Predicate - Usage, Composition, and Considerations](https://fatbobman.com/en/posts/swift-predicate-usage-composition-and-considerations) — Fatbobman · article catalogue
  **Published:** `2024-02-29T00:12:00.000Z`
  **NeKI brief:** Swift Predicate composes typed expressions that can be reused across SwiftData and related APIs, but closure syntax and supported operations are constrained. Follow it to identify expressive boundaries before designing a dynamic query DSL.
- [How to Handle Optional Values in SwiftData Predicates](https://fatbobman.com/en/posts/how-to-handle-optional-values-in-swiftdata-predicates) — Fatbobman · article catalogue
  **Published:** `2024-02-22T00:12:00.000Z`
  **NeKI brief:** Optional values in SwiftData predicates require explicit comparisons and careful optional promotion, otherwise valid-looking expressions fail to compile or match unexpectedly. The examples provide focused remedies for nullable filters.
- [SwiftData Relationships - @Relationship, Inverse, One-to-Many](https://fatbobman.com/en/posts/relationships-in-swiftdata-changes-and-considerations) — Fatbobman · article catalogue
  **Published:** `2024-01-18T00:12:00.000Z`
  **NeKI brief:** SwiftData relationships infer inverses and delete behavior from model declarations, yet optionality and initialization still affect generated schema. The article helps diagnose unexpected relationship mutations and choose explicit @Relationship settings.
- [SwiftData Fetching Pending Changes](https://useyourloaf.com/blog/swiftdata-fetching-pending-changes) — Use Your Loaf · article catalogue
  **Published:** `2024-01-01T10:03:32+00:00`
  **NeKI brief:** Investigates SwiftData fetches that should include unsaved changes, using SQLDebug output and two historical iOS 17 bugs to show what was actually returned. The updated evidence makes OS-version qualification part of debugging fetch results.
- [Build your first app with SwiftUI and SwiftData – Hacking with Swift](https://www.hackingwithswift.com/articles/263/build-your-first-app-with-swiftui-and-swiftdata) — Hacking with Swift articles · article catalogue
  **Published:** `2023-12-23T22:51:36+00:00`
  **NeKI brief:** Walks through a complete SwiftUI and SwiftData app, connecting model declaration, queries, and view updates. Use it as a baseline for checking persistence wiring before introducing custom architecture.
- [SwiftData Deleting Data](https://useyourloaf.com/blog/swiftdata-deleting-data) — Use Your Loaf · article catalogue
  **Published:** `2023-12-18T10:29:31+00:00`
  **NeKI brief:** Explains SwiftData deletion semantics and the need to mutate the model context deliberately. Use it when implementing destructive actions, save timing, and UI refresh behavior around removed objects.
- [How to Observe Data Changes in SwiftData using Persistent History Tracking](https://fatbobman.com/en/posts/persistent-history-tracking-in-swiftdata) — Fatbobman · article catalogue
  **Published:** `2023-11-02T00:12:00.000Z`
  **NeKI brief:** SwiftData persistent history exposes transactions from the same store, including widgets and batch work, so a client can react selectively instead of treating every save alike. The article shows filtering, replay, and tests for deterministic change handling.
- [Concurrent Programming in SwiftData](https://fatbobman.com/en/posts/concurret-programming-in-swiftdata) — Fatbobman · article catalogue
  **Published:** `2023-10-11T00:20:00.000Z`
  **NeKI brief:** SwiftData's ModelActor-backed serial executor provides a safer concurrency boundary than ad-hoc Core Data queue usage, but context ownership still matters. The discussion helps diagnose cross-actor model access and design explicit read/write entry points.
- [Unveiling the Data Modeling Principles of SwiftData](https://fatbobman.com/en/posts/unveiling-the-data-modeling-principles-of-swiftdata) — Fatbobman · article catalogue
  **Published:** `2023-10-07T00:12:00.000Z`
  **NeKI brief:** SwiftData's code-first models still encode schema decisions around identity, optionality, relationships, and value storage. The modeling principles help predict migration and query consequences before decorators harden an application's persistence design.
- [Using Core Data and Swift Data side by side](https://www.polpiella.dev/core-data-and-swift-data) — Pol Piella · article catalogue
  **Published:** `2023-10-05T00:00:00.000Z`
  **NeKI brief:** Compares running Core Data and SwiftData side by side, focusing on model and persistence boundaries during migration. Follow it when incrementally adopting SwiftData without rewriting an established store all at once.
- [SwiftDataKit - Unleashing Advanced Core Data Features in SwiftData](https://fatbobman.com/en/posts/use-core-data-features-in-swiftdata-by-swiftdatakit) — Fatbobman · article catalogue
  **Published:** `2023-09-07T00:12:00.000Z`
  **NeKI brief:** SwiftDataKit exposes selected Core Data capabilities behind SwiftData models, allowing advanced store features without abandoning the newer declaration style. Follow it to weigh compatibility benefits against dependency and abstraction leakage.
- [SwiftData Fetching An Existing Object](https://useyourloaf.com/blog/swiftdata-fetching-an-existing-object) — Use Your Loaf · article catalogue
  **Published:** `2023-08-21T09:06:59+01:00`
  **NeKI brief:** Uses SwiftData’s Codable and Sendable PersistentIdentifier to pass an object identity across contexts or threads, then fetches it in the destination ModelContext. This mirrors Core Data object-ID handoff without passing non-Sendable model instances.
- [Making your SwiftData models Codable – Donny Wals](https://www.donnywals.com/making-your-swiftdata-models-codable) — Donny Wals · article catalogue
  **Published:** `2023-08-15T12:56:12+00:00`
  **NeKI brief:** Examines the boundary between SwiftData models and Codable representations, including why persistence annotations do not automatically make a model a good wire format. It is useful when separating API payloads from storage objects.
- [SwiftData Background Tasks](https://useyourloaf.com/blog/swiftdata-background-tasks) — Use Your Loaf · article catalogue
  **Published:** `2023-08-14T13:16:10+01:00`
  **NeKI brief:** Explains moving SwiftData work to a ModelActor and its model executor, keeping Model and ModelContext on their owning actor. Persistent identifiers, not model objects, form the safe boundary for background imports and other long-running operations.
- [SwiftData Saving Changes](https://useyourloaf.com/blog/swiftdata-saving-changes) — Use Your Loaf · article catalogue
  **Published:** `2023-07-24T13:19:25+01:00`
  **NeKI brief:** Explains when SwiftData persists model mutations and how explicit saves interact with the model context. Useful for avoiding assumptions about durability after background or lifecycle-driven updates.
- [Configuring SwiftData in a SwiftUI app](https://www.polpiella.dev/configuring-swiftdata-in-a-swiftui-app) — Pol Piella · article catalogue
  **Published:** `2023-06-28T00:00:00.000Z`
  **NeKI brief:** Walks through configuring SwiftData in a SwiftUI application, including container setup and model access. Useful for establishing persistence boundaries and avoiding accidental model-container creation in previews or tests.
- [WWDC23 SwiftData Lab Notes](https://useyourloaf.com/blog/wwdc23-swiftdata-lab-notes) — Use Your Loaf · article catalogue
  **Published:** `2023-06-19T10:24:33+01:00`
  **NeKI brief:** Records SwiftData lab observations from WWDC23, preserving early persistence and migration caveats that explain why later APIs may look intentionally constrained.
- [WWDC 23, First Impressions of SwiftUI 5 and SwiftData](https://fatbobman.com/en/posts/impressions-of-wwdc23) — Fatbobman · article catalogue
  **Published:** `2023-06-09T00:12:00.000Z`
  **NeKI brief:** Summarizes the SwiftUI 5 and SwiftData changes announced at WWDC 2023, especially Observation-based property tracking, animation, visual effects, and persistence. Use it as historical release context, verifying exact availability and migration details with Apple documentation.
- [The power of UserDefaults in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/the-power-of-userdefaults-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Uses UserDefaults for small preference values with typed access patterns and defaults. It is not a database or secret store; migrations and key ownership should be centralized.
- [Picking the right data structure in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/picking-the-right-data-structure-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Chooses Swift collections according to access, ordering, uniqueness, and mutation requirements. Data-structure choice is a domain and complexity decision, not just a matter of familiar syntax.
- [Using launch arguments for easier Core Data and SwiftData debugging – Donny Wals](https://www.donnywals.com/using-launch-arguments-for-easier-core-data-debugging) — Donny Wals · article catalogue
  **Published:** `2019-12-01T08:00:00+00:00`
  **NeKI brief:** Launch arguments enable Core Data diagnostics without changing source code, making SQL and migration behavior inspectable in a reproducible debug configuration.
- [C Callbacks in Swift – Ole Begemann](https://oleb.net/blog/2015/06/c-callbacks-in-swift) — Ole Begemann · article catalogue
  **Published:** `2015-06-22T21:06:00Z`
  **NeKI brief:** C callbacks in Swift need explicit bridging for function pointers, context storage, and object lifetime. The article shows where closures cannot be passed directly and how ownership must survive asynchronous invocation.
- [How to store images in SwiftData](https://tanaschita.com/swiftdata-store-images) — Tanaschita · article catalogue
  **NeKI brief:** Uses SwiftData's externalStorage attribute for larger image payloads, trading inline persistence convenience for a more appropriate storage layout and fetch footprint.
- [How to migrate to a new schema with SwiftData in iOS](https://tanaschita.com/swiftdata-schema-migration) — Tanaschita · article catalogue
  **NeKI brief:** Walks through SwiftData schema migration, focusing on explicit versioning and migration stages so model changes do not become launch-time surprises.
- [Quick developer guide on SwiftData for iOS](https://tanaschita.com/swiftdata-quick-developer-guide) — Tanaschita · article catalogue
  **NeKI brief:** Introduces SwiftData's macro-driven model and container setup, useful for understanding the framework's declarative persistence surface before selecting migration or architectural boundaries.
- [Keeping SwiftData behind a boundary](https://tanaschita.com/swiftdata-persistence-boundaries) — Tanaschita · article catalogue
  **NeKI brief:** Keeps SwiftData behind a persistence boundary instead of exposing models directly to SwiftUI, improving testability and reducing UI coupling to storage details.
- [How to define one-to-many relationships in SwiftData](https://tanaschita.com/swiftdata-one-to-many-relationships) — Tanaschita · article catalogue
  **NeKI brief:** Defines SwiftData one-to-many relationships with @Relationship, highlighting ownership and delete-rule decisions that determine graph consistency during mutation and migration.
- [How to get a SwiftData model container and context in SwiftUI](https://tanaschita.com/swiftdata-model-container-context-swiftui) — Tanaschita · article catalogue
  **NeKI brief:** Sets up a SwiftData model container and context through SwiftUI modifiers, showing the dependency-injection seam views need for previews and tests.
- [MartianCraft on WWDC26: What Caught Our Eye](https://martiancraft.com/blog/2026/06/mc-on-wwdc26) — MartianCraft · article catalogue
  **NeKI brief:** Collects MartianCraft's WWDC26 implementation observations, including SwiftData and design changes that can be easy to miss in keynote coverage. It helps prioritize follow-up experiments while keeping the team's perspective separate from Apple API guidance.

## Newsletter and related leads

- [Wally 7](https://danielsaidi.com/blog/2026/08/20/wally-7) — Those Who Swift · Issue 281 — Article · Topics: Swift · SwiftData
  **Published:** `2026-08-26T20:38:31.643Z`
  **NeKI brief:** Announces Wally 7, a major release of Daniel Saidi's native iOS app, with a new data store and additional features. The release is useful as a concrete example of evolving a long-lived Apple-platform app while replacing foundational persistence infrastructure.
- [Amethyst Vein: An Open-Source, Cross-Platform Local Persistence Framework with SwiftData-Style APIs](https://l.fatbobman.com/w0150-6) — Fatbobman’s Swift Weekly · Issue 150 — Article · Topics: Cross-Platform & Web · Swift · SwiftData
  **Published:** `2026-08-24T12:03:48.210Z`
  **NeKI brief:** Presents Vein, an open-source local-first ORM with SwiftData-like macros, model containers, queries, migrations, and a SQLite/SQLCipher backend across Apple platforms, Linux, Android, and Windows. Use it to assess a shared Swift persistence layer rather than assuming SwiftData portability.
- [Building Testable SwiftData Apps](https://azamsharp.com/2026/08/02/building-testable-swiftdata-apps.html) — Those Who Swift · Issue 279 — Article · Topics: Swift · SwiftData · Testing
  **Published:** `2026-08-12T20:30:39.583Z`
  **NeKI brief:** Structures SwiftData code so model containers and observations can be exercised outside a SwiftUI view hierarchy. Use it to test persistence behavior and query-driven updates without coupling every assertion to UI rendering.
- [Shipping a SwiftData App with iCloud Sync](https://thorsten-stark.de/posts/2026-08-13-Shipping-A-SwiftData-App-With-iCloud-Sync-Part-3) — Those Who Swift · Issue 278 — Article · Topics: Persistence & Synchronisation · SwiftData
  **Published:** `2026-08-05T20:00:46.292Z`
  **NeKI brief:** Covers SwiftData and CloudKit release behavior that local testing can miss: initial-sync empty states, widget timelines that do not react automatically to remote changes, limited conflict control, and production-schema constraints. It emphasizes device validation and designing cheap conflicts.
- [Avoiding Duplicate Data When SwiftData Syncs Across Devices](https://thorsten-stark.de/posts/2026-08-06-Avoiding-Duplicate-Data-With-SwiftData-iCloud-Sync-Part-2) — SwiftLee Weekly · Issue 335 — Article · Topics: Swift · SwiftData
  **Published:** `2026-08-04T14:04:01.000Z`
  **NeKI brief:** Explains why independently seeded SwiftData defaults duplicate when CloudKit later merges device stores, and uses stable identifiers to make seeding idempotent. The pattern is useful for distinguishing local bootstrap state from synchronised identity.
- [AcceptedSE-0526withDeadline](https://github.com/apple/swift-evolution/blob/main/proposals/0526-deadline.md) — SwiftLee Weekly · Issue 335 — Source repository · Topics: Developer Tools · Swift · SwiftData
  **Published:** `2026-08-04T14:04:01.000Z`
  **NeKI brief:** Proposal SE-0526 adds withDeadline for time-bounded asynchronous work. Read it to distinguish deadline expiry from ordinary cancellation and failure, and verify accepted semantics and toolchain availability before designing a public timeout API around it.
- [Active ReviewSE-0539Enable Macros to Grant `self` Access for Property Initializers](https://github.com/apple/swift-evolution/blob/main/proposals/0539-self-access-for-property-initializers.md) — SwiftLee Weekly · Issue 335 — Source repository · Topics: Developer Tools · Macros & Metaprogramming · Swift
  **Published:** `2026-08-04T14:04:01.000Z`
  **NeKI brief:** Proposal SE-0539 explores allowing attached macros to grant controlled self access during property initialization. Follow it when macro-generated storage needs enclosing-instance context, while checking review status and initialization-safety constraints before relying on the feature.
- [Syncing SwiftData with a custom backend using HistoryObserver](https://azamsharp.com/2026/07/16/syncing-swiftdata-with-a-custom-backend-using-historyobserver.html) — iOS Dev Weekly · Issue 760 — Article · Topics: Networking · Persistence & Synchronisation · SwiftData
  **Published:** `24th July 2026`
  **NeKI brief:** Builds a one-way synchronisation pipeline from SwiftData HistoryObserver transactions to a REST backend. Persisting the last processed transaction token avoids duplicate uploads; server-to-client changes remain a separate responsibility.
- [Keeping SwiftData behind a boundary](https://tanaschita.com/swiftdata-persistence-boundaries?ref=ioscodereview.com) — iOS Code Review · Issue 82 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `2026-07-14T19:04:53.000Z`
  **NeKI brief:** Keeps SwiftData behind a persistence boundary instead of exposing models directly to SwiftUI, improving testability and reducing UI coupling to storage details.
- [Reordering SwiftData In List And Grid](https://www.youtube.com/watch?v=m5VdG-EKnmk) — Those Who Swift · Issue 274 — Video · Topics: Swift · SwiftData
  **Published:** `2026-07-08`
  **NeKI brief:** Implements List movement and LazyVGrid drag-and-drop, first in memory and then with SwiftData sort-order persistence. A custom DropDelegate updates visual order during dragging and saves only when the operation completes.
- [What’s New In SwiftData For iOS 27](https://azamsharp.com/2026/06/12/whats-new-in-swiftdata.html) — Those Who Swift · Issue 271 — Article · Topics: Cross-Platform & Web · Swift · SwiftData
  **Published:** `2026-06-18`
  **NeKI brief:** Mohammad covers what’s new in SwiftData for iOS 27, showing how enum predicates, sectioned queries, compound predicates, the new .codable attribute, and ResultsObserver remove common workarounds.
- [Building a Custom Data Store in SwiftData](https://azamsharp.com/2026/05/26/building-a-custom-data-store-in-swiftdata.html) — iOS Dev Weekly · Issue 752 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `29th May 2026`
  **NeKI brief:** Walks through implementing a custom SwiftData store and the integration points needed to replace default persistence; useful when evaluating storage backends and their lifecycle trade-offs.
- [Decoupling SwiftData in SwiftUI: Is It Worth It?](https://www.youtube.com/watch?v=2so9ifq5hYY) — Those Who Swift · Issue 268 — Video · Topics: Swift · SwiftData · SwiftUI
  **Published:** `2026-05-27`
  **NeKI brief:** Implements protocol-backed SwiftData and SQLite stores, then examines the cost of losing SwiftData's automatic UI integration. Useful for deciding when persistence abstraction improves testability and when it merely adds architectural overhead.
- [SwiftData for Beginners](https://www.youtube.com/watch?v=mgUYC6TWbSM) — Those Who Swift · Issue 266 — Video · Topics: Swift · SwiftData
  **Published:** `2026-05-13`
  **NeKI brief:** Reviews SwiftData for Beginners. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [DataStoreKit](https://github.com/asymbas/datastorekit) — iOS Dev Tools · iOS Dev Tools: web2wave, CoreDataBrowser, DataStoreKit — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Persistence & Synchronisation
  **Published:** `2026-03-19T17:30:50.047Z`
  **NeKI brief:** DataStoreKit provides Swift persistence abstractions for storing application data. Follow its source and tests for concrete serialization, caching, and lifecycle semantics, then compare them with the project’s existing persistence layer.
- [Apple Doesn’t Show SwiftData iCloud Sync Status — So Let’s Build One](https://azamsharp.com/2026/03/16/swiftdata-icloud-sync-status.html) — Those Who Swift · Issue 258 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `2026-03-18`
  **NeKI brief:** Azam shows how to build a simple sync status monitor for SwiftData, giving users meaningful feedback on what's happening behind the scenes while their data syncs with iCloud.
- [Measuring Core Data and SwiftData](https://yaacoub.github.io/articles/swift-tip/measuring-core-data-and-swiftdata) — iOS Dev Weekly · Issue 744 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `27th February 2026`
  **NeKI brief:** Presents measuring core data and swiftdata for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [If You’re Not Versioning Your SwiftData Schema, You’re Gambling](https://azamsharp.com/2026/02/14/if-you-are-not-versioning-your-swiftdata-schema.html) — Those Who Swift · Issue 254 — Article · Topics: App Distribution & Store Operations · Swift · SwiftData
  **Published:** `2026-02-18`
  **NeKI brief:** Azam explains why schema versioning in SwiftData is essential once your app stores real user data and shows how to define VersionedSchema, implement custom migrations, and evolve models.
- [Sharing SwiftData Content Between Users](https://www.youtube.com/watch?v=t9FRldfZ8vc) — Those Who Swift · Issue 254 — Video · Topics: Swift · SwiftData · SwiftUI
  **Published:** `2026-02-18`
  **NeKI brief:** Exports selected SwiftData relationships as a custom file through UIActivityViewController, then imports them with onOpenURL and security-scoped access. The merge logic reconnects related models while preventing duplicates.
- [Sharing SwiftData Between Users](https://www.youtube.com/watch?v=TPGn2pJjfis) — Those Who Swift · Issue 253 — Video · Topics: Swift · SwiftData
  **Published:** `2026-02-12`
  **NeKI brief:** Reviews Sharing SwiftData Between Users. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Finishing the Rich Notes App in SwiftUI](https://www.youtube.com/watch?v=UUvgm9-yltE) — Those Who Swift · Issue 244 — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2025-12-11`
  **NeKI brief:** Reviews Finishing the Rich Notes App in SwiftUI. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [AcceptedSE-0491Module selectors for name disambiguation](https://github.com/apple/swift-evolution/blob/main/proposals/0491-module-selectors.md) — SwiftLee Weekly · Issue 293 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2025-10-14T14:14:22.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0491Module selectors for name disambiguation. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Performing Search with SwiftData in a SwiftUI app](https://l.fatbobman.com/w0106-04) — Fatbobman’s Swift Weekly · Issue 106 — Article · Topics: Objective-C & Cocoa · Swift · SwiftData
  **Published:** `2025-10-13T12:03:32.126Z`
  **NeKI brief:** Demonstrates combining SwiftData queries with SwiftUI’s searchable modifier to implement app search. Follow it when connecting query predicates, search state, and result presentation without duplicating a second in-memory data source.
- [Discussion on SwiftData’s ModelActor](https://l.fatbobman.com/w0100-04) — Fatbobman’s Swift Weekly · Issue 100 — Article · Topics: Concurrency · Swift · SwiftData
  **Published:** `2025-09-01T12:03:36.183Z`
  **NeKI brief:** Examines why SwiftData’s ModelActor can feel surprising and where its isolation model complicates persistence design. Follow it when reviewing actor boundaries, model-container ownership, and concurrency assumptions in SwiftData code.
- [CoreDataEvolution](https://github.com/fatbobman/CoreDataEvolution) — Fatbobman’s Swift Weekly · Issue 100 — Source repository · Topics: Concurrency · Core Data · Persistence & Synchronisation
  **Published:** `2025-09-01T12:03:36.183Z`
  **NeKI brief:** CoreDataEvolution experiments with bringing ModelActor-like concurrency structure to Core Data. Use it when modernizing a Core Data stack while retaining its model and store, especially to centralize context ownership and serialized mutations.
- [How to Work with SwiftData in the Background in Swift 6](https://www.natashatherobot.com/p/swiftdata-background-swift-6) — Those Who Swift · Issue 228 — Article · Topics: AI Development · Swift · SwiftData
  **Published:** `2025-08-20`
  **NeKI brief:** Explains How to Work with SwiftData in the Background in Swift 6, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [StructuredQueries](https://github.com/pointfreeco/swift-structured-queries) — Fatbobman’s Swift Weekly · Issue 89 — Source repository · Topics: Developer Tools · Swift · SwiftData
  **Published:** `2025-06-16T12:01:00.435Z`
  **NeKI brief:** StructuredQueries builds SQL with typed Swift structure while preserving SQL's expressive power. Use it when query composition needs compiler assistance but hiding relational behavior behind an ORM would make performance or migrations opaque.
- [SharingGRDB](https://github.com/pointfreeco/sharing-grdb) — Fatbobman’s Swift Weekly · Issue 89 — Source repository · Topics: Developer Tools · Swift · SwiftData
  **Published:** `2025-06-16T12:01:00.435Z`
  **NeKI brief:** SharingGRDB combines shared observable state with GRDB-backed SQLite persistence. Use it when SwiftUI features need low deployment targets and direct SQL control, noting that it does not provide mature cross-device synchronization.
- [DataScoutCompanion](https://github.com/alex566/DataScoutCompanion) — Fatbobman’s Swift Weekly · Issue 87 — Source repository · Topics: Developer Tools · Swift · SwiftData
  **Published:** `2025-06-07T12:01:11.599Z`
  **NeKI brief:** DataScoutCompanion is an open-source companion for inspecting application data during development. Use it when debugging data flows needs a dedicated in-app inspection surface rather than scattered temporary logging statements.
- [SwiftData Predicates For Parent RelationshipsHow do you write SwiftData predicates to query for parent relationships.Use Your Loaf - iOS Development News & Tips](https://useyourloaf.com/blog/swiftdata-predicates-for-parent-relationships?ref=createwithswift.com) — Create with Swift · Issue 60 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `2025-05-09T15:30:59.000Z`
  **NeKI brief:** Builds a #Predicate over an optional SwiftData relationship by comparing the parent’s persistentModelID, then extends the pattern to multiple parent IDs. This is useful when CloudKit-compatible optional relationships must still support parameterized child queries.
- [GRDB](https://github.com/groue/GRDB.swift) — Fatbobman’s Swift Weekly · Issue 81 — Source repository · Topics: Core Data · Swift · SwiftData
  **Published:** `2025-04-28T00:00:42.290Z`
  **NeKI brief:** GRDB.swift is a SQLite toolkit offering query interfaces, migrations, observations, and record mapping. Use it when an app needs transparent relational persistence and reactive database changes without SwiftData's deployment and sync assumptions.
- [DataScout](https://data-scout.pages.dev/) — iOS Dev Tools · iOS Dev Tools: AppsMan, ErrorKit, DataScout — Article · Topics: Core Data · Cross-Platform & Web · Persistence & Synchronisation
  **Published:** `2025-04-24T13:08:49.536Z`
  **NeKI brief:** Data Scout is a data-exploration project presented as a developer product. Inspect its concrete workflow when comparing small utility apps, data presentation choices, and the cost of maintaining a focused independent product.
- [Mastering Data Tracking and Notifications in Core Data and SwiftData](https://itnext.io/mastering-data-tracking-and-notifications-in-core-data-and-swiftdata-a21921ebfa9d?source=rss-b8c3000741------2) — Those Who Swift · Issue 209 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `2025-04-09`
  **NeKI brief:** Examines Mastering Data Tracking and Notifications in Core Data and SwiftData, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Swiftdata Architecture Patterns And PracticesBlog about iOS development and musings on technologyAzamSharpMohammad Azam](https://azamsharp.com/2025/03/28/swiftdata-architecture-patterns-and-practices.html?ref=createwithswift.com) — Create with Swift · Issue 55 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2025-04-04T15:49:40.000Z`
  **NeKI brief:** Using a practical example, Mohammad shows how to build scalable SwiftData apps in SwiftUI, covering model structure, business logic, DTOs, testing, previews, CloudKit integration, and strategies to future-proof your architecture.
- [ModelActor is Just Weird](https://www.massicotte.org/model-actor?ref=createwithswift.com) — Create with Swift · Issue 55 — Article · Topics: Concurrency · Swift · SwiftData
  **Published:** `2025-04-04T15:49:40.000Z`
  **NeKI brief:** In this article, Matt shows his journey in understanding how the ModelActor protocol and how Swift Data deals with concurrency in the system.
- [Swiftdata Architecture Patterns And Practices](https://azamsharp.com/2025/03/28/swiftdata-architecture-patterns-and-practices.html) — SwiftLee Weekly · Issue 265 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2025-04-01T14:13:42.000Z`
  **NeKI brief:** Using a practical example, Mohammad shows how to build scalable SwiftData apps in SwiftUI, covering model structure, business logic, DTOs, testing, previews, CloudKit integration, and strategies to future-proof your architecture.
- [ModelActor is Just Weird](https://www.massicotte.org/model-actor) — Those Who Swift · Issue 207 — Article · Topics: Concurrency · Swift · SwiftData
  **Published:** `2025-03-28`
  **NeKI brief:** In this article, Matt shows his journey in understanding how the ModelActor protocol and how Swift Data deals with concurrency in the system.
- [Key Considerations Before Using SwiftData](https://fatbobman.com/en/posts/key-considerations-before-using-swiftdata?ref=createwithswift.com) — Create with Swift · Issue 52 — Article · Topics: Concurrency · Swift · SwiftData
  **Published:** `2025-03-14T17:00:20.000Z`
  **NeKI brief:** Evaluates SwiftData's practical limits before adoption. Use it when deciding whether its model, migration, query, or synchronization behavior fits a production persistence requirement.
- [Filtering SwiftData Models Using Enum](https://azamsharp.com/2025/01/23/filtering-swiftdata-models-using-enum.html?ref=createwithswift.com) — Create with Swift · Issue 46 — Article · Topics: Cross-Platform & Web · Swift · SwiftData
  **Published:** `2025-01-31T16:30:58.000Z`
  **NeKI brief:** Azam explains how to filter SwiftData models using enum values, overcoming query limitations with raw values, while providing code examples and highlighting enums’ benefits.
- [Filtering SwiftData Models Using Enum](https://azamsharp.com/2025/01/23/filtering-swiftdata-models-using-enum.html) — Those Who Swift · Issue 199 — Article · Topics: Cross-Platform & Web · Swift · SwiftData
  **Published:** `2025-01-30`
  **NeKI brief:** Azam explains how to filter SwiftData models using enum values, overcoming query limitations with raw values, while providing code examples and highlighting enums’ benefits.
- [SwiftData CRUD Operations with ModelActor](https://brightdigit.com/tutorials/swiftdata-crud-operations-modelactor) — Those Who Swift · Issue 198 — Tutorial · Topics: Concurrency · Swift · SwiftData
  **Published:** `2025-01-23`
  **NeKI brief:** Examines SwiftData CRUD Operations with ModelActor, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Being Sendable with SwiftData](https://brightdigit.com/tutorials/swiftdata-sendable?issue=057) — Fatbobman’s Swift Weekly · Issue 57 — Tutorial · Topics: Concurrency · Swift · SwiftData
  **Published:** `2024-11-11T12:03:02.180Z`
  **NeKI brief:** Explains Sendable boundaries around SwiftData models and persistence access. Use it when concurrency checking exposes non-Sendable model crossings and you need to decide where actors or value projections belong.
- [Considerations for Using Codable and Enums in SwiftData Models](https://fatbobman.com/en/posts/considerations-for-using-codable-and-enums-in-swiftdata-models?ref=createwithswift.com) — Create with Swift · Issue 25 — Article · Topics: Foundation & Data Formats · Swift · SwiftData
  **Published:** `2024-08-30T15:00:43.000Z`
  **NeKI brief:** SwiftData stores Codable structs and enums through generated persistence representations, which affects predicates, migrations, and queryability. The examples expose where convenient model types become opaque storage and when a normalized property is safer.
- [@LiveModel in SwiftData](https://patstechweblog.com/posts/2-live-model?issue=031) — Fatbobman’s Swift Weekly · Issue 32 — Article · Topics: Swift · SwiftData · SwiftUI
  **Published:** `2024-05-20T12:02:52.341Z`
  **NeKI brief:** The article explores a SwiftData `@LiveModel` pattern for keeping model-backed UI current. Follow it when separating observation updates from persistence operations and checking whether a custom wrapper adds value beyond native model observation.
- [Reducing iOS Test execution time with Selective Testing](https://levelup.gitconnected.com/reducing-ios-test-execution-time-with-selective-testing-384879e5f243?issue=031) — Fatbobman’s Swift Weekly · Issue 32 — Article · Topics: Concurrency · Swift · Testing
  **Published:** `2024-05-20T12:02:52.341Z`
  **NeKI brief:** Explains selective testing as a way to shorten iOS test feedback cycles by choosing affected tests. Use it to discuss CI optimization, validating its heuristics against the project's dependency graph and failure-reporting needs.
- [The Composable Architecture: My 3 Year Experience](https://rodschmidt.com/posts/composable-architecture-experience?issue=030) — Fatbobman’s Swift Weekly · Issue 30 — Article · Topics: Architecture · Composable Architecture · Objective-C & Cocoa
  **Published:** `2024-05-06T12:01:46.954Z`
  **NeKI brief:** A three-year TCA retrospective surfaces production trade-offs that API introductions omit, including architectural discipline and maintenance cost. Use it to evaluate long-lived team fit rather than reading it as a generic framework endorsement.
- [Subscribing to SwiftData changes outside SwiftUI](https://www.finnvoorhees.com/words/subscribing-to-swiftdata-changes-outside-swiftui) — iOS Dev Weekly · Issue 659 — Article · Topics: Swift · SwiftData · SwiftUI
  **Published:** `3rd May 2024`
  **NeKI brief:** Presents subscribing to swiftdata changes outside swiftui for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [SwiftData](https://www.youtube.com/playlist?list=PLlc_rDuPW0Y1X55v_cJlTWomSmHd-MS5r) — iOS Dev Weekly · Issue 659 — Video · Topics: Graphics, Media & Games · Swift · SwiftData
  **Published:** `3rd May 2024`
  **NeKI brief:** A nine-part series of videos on SwiftData sounds like a lot to chew through, doesn’t it? What if it was from Daniel Steinberg? Now you’re interested? Well, what if I added that they’re each only about 5 minutes long? Did that trigger your clicking finger? 😂…
- [How to use SwiftData outside SwiftUI](https://jacobbartlett.substack.com/p/swiftdata-outside-swiftui) — iOS Dev Weekly · Issue 658 — Tutorial · Topics: Swift · SwiftData · SwiftUI
  **Published:** `26th April 2024`
  **NeKI brief:** Presents how to use swiftdata outside swiftui for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Quick and Painless Persistency on iOS](https://www.swiftjectivec.com/stupid-and-quick-persistency-on-ios-with-swift) — iOS Dev Weekly · Issue 655 — Article · Topics: Core Data · Persistence & Synchronisation · Swift
  **Published:** `5th April 2024`
  **NeKI brief:** Presents quick and painless persistency on ios for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Let's VisionOS 2024](https://letsvisionos24.swiftgg.team/en) — Fatbobman’s Swift Weekly · Issue 24 — Article · Topics: Spatial Computing · Swift · SwiftData
  **Published:** `2024-03-25T22:01:11.274Z`
  **NeKI brief:** Let’s VisionOS 2024 is a Beijing event focused on visionOS and Apple-platform development. Use it to find historical conference material and community perspectives, not as current API documentation or a direct implementation tutorial.
- [Let's VisionOS](https://letsvisionos24.swiftgg.team/cn) — Fatbobman’s Swift Weekly · Issue 23 — Article · Topics: Spatial Computing · Swift · SwiftData
  **Published:** `2024-03-18T22:00:43.468Z`
  **NeKI brief:** Uses Let's VisionOS as a practical reference for Apple-platform development, surfacing implementation constraints and workflow trade-offs worth checking before applying the idea in production code.
- [Tundsdev channel on YouTube](https://www.youtube.com/@tundsdev/videos?ref=createwithswift.com) — Create with Swift · Issue 3 — Video · Topics: Graphics, Media & Games · Swift · SwiftData
  **Published:** `2024-03-08T16:00:49.000Z`
  **NeKI brief:** Lately, anytime someone asks us about how to start learning Swift Data the first thing that comes to mind is tundsdev YouTube channel.
- [Screen vs View in SwiftUI](https://scottsmithdev.com/screen-vs-view-in-swiftui) — iOS Dev Weekly · Issue 647 — Article · Topics: Core Data · Swift · SwiftUI
  **Published:** `9th February 2024`
  **NeKI brief:** Contrasts screen-level composition with reusable SwiftUI views and gives naming and responsibility boundaries that help keep navigation and presentation code maintainable.
- [SwiftData](https://www.youtube.com/playlist?list=PLBn01m5Vbs4Ck-JEF2nkcFTF_2rhGBMKX) — iOS Dev Weekly · Issue 642 — Video · Topics: Developer Community & Business · Swift · SwiftData
  **Published:** `5th January 2024`
  **NeKI brief:** Collects videos around SwiftData in a single playlist. Useful for discovery and grouped learning, while each recording should be checked separately for current API behavior.
- [How to Play Spatial Video On iOS 17.2](https://xreality.zone/zh/posts/how-to-play-spatial-video-on-ios-17-2) — Fatbobman’s Swift Weekly · Issue 12 — Tutorial · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **Published:** `2023-12-25T22:00:09.856Z`
  **NeKI brief:** Demonstrates playing spatial video on iOS 17.2 and discusses the media and device prerequisites involved. Use it to investigate immersive-video playback paths while verifying format support and availability against current Apple APIs.
- [Integrating Haptic Feedback In SwiftUI Projects](https://serialcoder.dev/text-tutorials/swiftui/integrating-haptic-feedback-in-swiftui-projects) — Fatbobman’s Swift Weekly · Issue 12 — Tutorial · Topics: Swift · SwiftData · SwiftUI
  **Published:** `2023-12-25T22:00:09.856Z`
  **NeKI brief:** Shows how to trigger haptic feedback from SwiftUI interactions by bridging to the appropriate UIKit feedback generators. Follow it when adding tactile confirmation while keeping feedback timing, accessibility, and device capability checks explicit.
- [App Localizations](https://www.youtube.com/watch?v=kbgNL7VrQPo) — SwiftUI Weekly · SwiftUI Weekly - Issue #170 — Video · Topics: Graphics, Media & Games · Localization · Swift
  **Published:** `2023-12-11T13:23:19.560Z`
  **NeKI brief:** Demonstrates localizing a SwiftUI app with Xcode 15 String Catalogs, including the workflow for translating strings across languages. Useful when replacing scattered localization files with catalog-driven review and export in a modern project.
- [The Ultimate Swift Data GuideThe Ultimate Guide to Building SwiftData ApplicationsAzamSharpMohammad Azam](https://azamsharp.com/2023/07/04/the-ultimate-swift-data-guide.html?ref=ioscodereview.com) — iOS Code Review · Issue 61 — Article · Topics: Cross-Platform & Web · Swift · SwiftData
  **Published:** `2023-12-07T13:38:43.000Z`
  **NeKI brief:** Provides a broad SwiftData walkthrough covering model declaration, persistence, and cloud-sync-oriented concepts introduced at WWDC 2023. Useful for mapping Core Data requirements to SwiftData before committing to a migration or new model layer.
- [The Absolute Minimum Every Software Developer Must Know About Unicode in 2023 (Still No Excuses!)](https://tonsky.me/blog/unicode) — Fatbobman’s Swift Weekly · Issue 5 — Article · Topics: Foundation & Data Formats · Swift · SwiftData
  **Published:** `2023-11-06T22:30:15.675Z`
  **NeKI brief:** Explains Unicode fundamentals and common misconceptions that still cause text-processing bugs. Use it when reviewing Swift string handling, normalization, grapheme boundaries, and serialization across user-visible content and external systems.
- [2023 年每个软件开发者都必须知道的关于 Unicode 的最基本的知识（仍然不准找借口！）](https://blog.xinshijiededa.men/unicode) — Fatbobman’s Swift Weekly · Issue 5 — Article · Topics: Foundation & Data Formats · Swift · SwiftData
  **Published:** `2023-11-06T22:30:15.675Z`
  **NeKI brief:** Provides a Chinese-language treatment of Unicode basics and the pitfalls of assuming characters map directly to bytes or code points. Follow it as complementary reading when internationalized Swift text behavior needs careful validation.
- [SwiftDataKit](https://github.com/fatbobman/SwiftDataKit) — Fatbobman’s Swift Weekly · Issue 1 — Source repository · Topics: Core Data · Swift · SwiftData
  **Published:** `2023-10-09T14:00:25.178Z`
  **NeKI brief:** SwiftDataKit exposes lower-level Core Data access for SwiftData-backed models. Use it when a migration needs framework escape hatches, persistent-history operations, or APIs not surfaced by SwiftData alone.
- [Thinking in SwiftUI (2023)](https://www.objc.io/books/thinking-in-swiftui) — Fatbobman’s Swift Weekly · Issue 1 — Article · Topics: Core Data · Swift · SwiftUI
  **Published:** `2023-10-09T14:00:25.178Z`
  **NeKI brief:** Thinking in SwiftUI teaches the framework's state, identity, layout, and rendering mental models. Use it when a recurring SwiftUI bug indicates a conceptual mismatch rather than an isolated API issue.
- [SwiftData by Example](https://twostraws.gumroad.com/l/swiftdata-by-example) — iOS Dev Weekly · Issue 630 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `6th October 2023`
  **NeKI brief:** Presents swiftdata by example for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [online version that you can read for free](https://www.hackingwithswift.com/quick-start/swiftdata) — iOS Dev Weekly · Issue 630 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `6th October 2023`
  **NeKI brief:** Available as a PDF download or an online version that you can read for free, I’m confident Paul Hudson’s is the most comprehensive look at Apple’s new persistence framework there is. Incredibly, he published this book (effectively) simultaneously with the…
- [@Model for CoreData](https://www.alwaysrightinstitute.com/managedmodels) — iOS Dev Weekly · Issue 629 — Article · Topics: Core Data · Persistence & Synchronisation · Swift
  **Published:** `29th September 2023`
  **NeKI brief:** Presents @model for coredata for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Core Data Lab and SwiftData](https://betamagic.nl/news/2023/2023_03.html) — iOS Dev Weekly · Issue 628 — Article · Topics: Core Data · Cross-Platform & Web · Persistence & Synchronisation
  **Published:** `22nd September 2023`
  **NeKI brief:** I’ve written about Core Data Lab before, and it remains an excellent companion app with enough features specific to Core Data to make it worthwhile over a “regular” Core Data client, so I was excited to read that there’s a beta available for a new release…
- [Unlocking Advanced Core Data Features in SwiftData](https://itnext.io/swiftdatakit-unleashing-advanced-core-data-features-in-swiftdata-3fcd5f443c99) — iOS Dev Weekly · Issue 626 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `8th September 2023`
  **NeKI brief:** Presents unlocking advanced core data features in swiftdata for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Pietro Rea’s recent article](https://pietrorea.com/2023/07/21/will-swiftdata-fix-core-datas-marketing-problem) — iOS Dev Weekly · Issue 621 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `4th August 2023`
  **NeKI brief:** Examines Will SwiftData fix Core Data’s marketing problem? | Pietro Rea. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [How to Easily Persist Data in SwiftUI](https://www.youtube.com/watch?v=CcUgRDLcUmQ) — iOS Dev Weekly · Issue 621 — Video · Topics: Graphics, Media & Games · Persistence & Synchronisation · Swift
  **Published:** `4th August 2023`
  **NeKI brief:** Talking of SwiftData, how about a guide through the basics from Karin Prater? She builds the ultimate example app when you want to play with a persistence framework, a to-do list app!
- [The Ultimate Guide to Building SwiftData Applications](https://azamsharp.com/2023/07/04/the-ultimate-swift-data-guide.html) — SwiftUI Weekly · SwiftUI Weekly - Issue #151 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `2023-07-17T21:13:35.306Z`
  **NeKI brief:** Provides a broad SwiftData walkthrough covering model declaration, persistence, and cloud-sync-oriented concepts introduced at WWDC 2023. Useful for mapping Core Data requirements to SwiftData before committing to a migration or new model layer.
- [SwiftData Suprises](https://jsorge.net/2023/06/30/swiftdata-surprises) — iOS Dev Weekly · Issue 617 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `7th July 2023`
  **NeKI brief:** Explores SwiftData Suprises, focusing on understanding new frameworks is always important, but understanding new data storage frameworks is especially important!. Follow it to assess the approach, its trade-offs, and where it fits in a current Swift or Apple-platform project.
- [Build an app using SwiftData](https://www.youtube.com/playlist?list=PLvUWi5tdh92wZ5_iDMcBpenwTgFNan9T7) — iOS Dev Weekly · Issue 617 — Video · Topics: Apple Platform Ecosystem · Swift · SwiftData
  **Published:** `7th July 2023`
  **NeKI brief:** Explores Build an app using SwiftData, focusing on it’s a measure of how many new things were announced. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Relationships In SwiftData](https://www.youtube.com/watch?v=_QMalUGTM4E&feature=youtu.be) — SwiftUI Weekly · SwiftUI Weekly - Issue #148 — Video · Topics: Graphics, Media & Games · Swift · SwiftData
  **Published:** `2023-06-28T11:49:47.378Z`
  **NeKI brief:** Demonstrates adding relationships between SwiftData models in a SwiftUI to-do app. Useful for understanding relationship declaration, editing, and fetch behavior before modeling linked domain objects.
- [Here is what SwiftData will be…](https://drewmccormack.medium.com/here-is-what-swiftdata-will-be-and-what-it-could-have-been-65b79cd11c6a) — iOS Dev Weekly · Issue 509 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `28th May 2021`
  **NeKI brief:** Explores Here is what SwiftData will be…, focusing on that’s a bold title from drew mccormack! a new swiftui. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
