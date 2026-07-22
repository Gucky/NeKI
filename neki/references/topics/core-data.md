# Core Data

Third-party reading leads collected from NeKI sources. The links may be useful perspectives, but are not vetted recommendations or authoritative API guidance. NeKI publishes routing metadata, not the linked articles' text.

**Scope:** Core Data models, fetching, migration, concurrency, and persistence behaviour.

- Last collected: `2026-07-22T21:56:49Z`
- Indexed links shown: **274**

## Direct-source reading

- [Core Data with SwiftUI Tutorial: Getting Started | Kodeco](https://www.kodeco.com/9335365-core-data-with-swiftui-tutorial-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The starter app wires Core Data into SwiftUI through @State, @Environment, and @FetchRequest, illustrating the view-to-persistence data flow in the older SwiftUI model API.
- [Beginning Core Data Course Updated for Swift 3 & iOS 10 | Kodeco](https://www.kodeco.com/761-beginning-core-data-course-updated-for-swift-3-ios-10) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This Core Data course covers model relationships, CRUD operations and filtered fetches across multiple lessons. It is useful for legacy maintenance because it exposes how context ownership and schema choices shape every later query.
- [Multiple Managed Object Contexts with Core Data Tutorial | Kodeco](https://www.kodeco.com/7586-multiple-managed-object-contexts-with-core-data-tutorial) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Multiple Core Data contexts are introduced as a way to isolate work and reduce UI contention, with performance implications that still require current-API verification.
- [Lightweight Migrations in Core Data Tutorial | Kodeco](https://www.kodeco.com/7585-lightweight-migrations-in-core-data-tutorial) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This Core Data migration walkthrough focuses on evolving a model while preserving stored objects, clarifying when lightweight migration can cover schema changes.
- [Getting Started with Core Data Tutorial | Kodeco](https://www.kodeco.com/7569-getting-started-with-core-data-tutorial) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This Core Data starter covers entities, contexts and fetch requests as the first persistence layer. Its value is in showing how managed-object lifecycle reaches UI code, a boundary later implementations should isolate behind repositories.
- [Updated Course: Intermediate Core Data | Kodeco](https://www.kodeco.com/751-updated-course-intermediate-core-data) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Summarizes intermediate Core Data patterns beyond basic setup. It is useful for tracing managed-object contexts, fetch behavior, and persistence boundaries before introducing custom repository abstractions.
- [Beginning Core Data | Kodeco](https://www.kodeco.com/7104-beginning-core-data) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This Core Data series covers model relationships, updates and fetch predicates as a complete persistence workflow. Its routing value is in connecting schema design to query behavior, rather than treating the managed object context as a generic database handle.
- [SwiftData: Simplifying Persistence in iOS Apps | Kodeco](https://www.kodeco.com/40504096-swiftdata-simplifying-persistence-in-ios-apps) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Explains SwiftData's @Model macro, model container, and context-driven persistence as a Swift-native layer over local storage. It is useful for evaluating migration from Core Data while keeping schema and context lifetime decisions explicit.
- [Intermediate Core Data | Kodeco](https://www.kodeco.com/3815-intermediate-core-data) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Explores intermediate Core Data concepts beyond a basic fetch-and-save flow. Useful for evaluating context behavior, relationships, and persistence design when an application's data model starts carrying real synchronization and lifecycle complexity.
- [Beginning Core Data | Kodeco](https://www.kodeco.com/3813-beginning-core-data) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Introduces Core Data's model, managed objects, contexts, and persistence workflow. Useful for establishing the responsibilities of the object graph before adding migrations, sync, or background contexts.
- [Intermediate Core Data | Kodeco](https://www.kodeco.com/3660-intermediate-core-data) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Develops intermediate Core Data usage patterns and data-model concerns. Useful for identifying where a persistence issue belongs: fetch semantics, object graph relationships, context ownership, or schema evolution.
- [Beginning Core Data | Kodeco](https://www.kodeco.com/3444-beginning-core-data) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Introduces Core Data entities, managed objects, contexts, and persistence. Useful for tracing how a UI change becomes a durable object-graph mutation.
- [Core Data: Beyond the Basics | Kodeco](https://www.kodeco.com/32317039-core-data-beyond-the-basics) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Core Data’s fetch, sort and filter behavior is explored beyond model creation, including persistent-store access patterns. It is useful when tuning predicates and fetch requests instead of moving all filtering into application memory.
- [Beginning Core Data | Kodeco](https://www.kodeco.com/3200-beginning-core-data) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Covers Core Data setup, fetches, and saves in an introductory workflow. Useful for separating model persistence from table or form presentation responsibilities.
- [Core Data Tutorial for iOS: How To Use NSFetchedResultsController | Kodeco](https://www.kodeco.com/3134-core-data-tutorial-for-ios-how-to-use-nsfetchedresultscontroller) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Uses NSFetchedResultsController to bridge Core Data changes into a table view. Useful for preserving incremental UI updates without manually refetching and rebuilding an entire list after every change.
- [NSIncrementalStore Tutorial for iOS: Getting Started | Kodeco](https://www.kodeco.com/311-nsincrementalstore-tutorial-for-ios-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Implements an NSIncrementalStore that maps Core Data fetches and saves onto a web service, including IDs, caching, relationships, and optimistic conflicts. Useful for understanding why remote-backed persistence requires careful identity and consistency design.
- [Sharing Core Data With CloudKit in SwiftUI | Kodeco](https://www.kodeco.com/29934862-sharing-core-data-with-cloudkit-in-swiftui) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Explains synchronizing a Core Data store with CloudKit from a SwiftUI app. Follow it when evaluating Apple-backed data sharing, because container configuration, model compatibility, and offline synchronization remain separate operational concerns.
- [Core Data on iOS 5 Tutorial: How To Preload and Import Existing Data | Kodeco](https://www.kodeco.com/2935-core-data-on-ios-5-tutorial-how-to-preload-and-import-existing-data) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Preloading Core Data from bundled or imported records demonstrates seeding a persistent store before user interaction. It is useful for migration work, where idempotence and managed-object context ownership prevent duplicate imports.
- [Core Data Tutorial Series Updated for iOS 5 | Kodeco](https://www.kodeco.com/2927-core-data-tutorial-series-updated-for-ios-5) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This Core Data series update covers model creation, contexts and fetches for iOS 5. Its value is legacy maintenance context, helping identify assumptions about managed objects and persistence setup before a migration.
- [Core Data on iOS 5 Tutorial: How To Work with Relations and Predicates | Kodeco](https://www.kodeco.com/2896-core-data-on-ios-5-tutorial-how-to-work-with-relations-and-predicates) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This Core Data tutorial focuses on relationships and predicates, showing how object graphs affect fetch results. It is useful legacy material for diagnosing overly broad queries and modeling associations before migrating persistence code.
- [How To Synchronize Core Data with a Web Service – Part 2 | Kodeco](https://www.kodeco.com/2867-how-to-synchronize-core-data-with-a-web-service-part-2) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The synchronization continuation handles sending local changes and reconciling remote data. Follow it to identify conflict and retry policies, which must be explicit when a local store and server can both mutate records.
- [How To Synchronize Core Data with a Web Service – Part 1 | Kodeco](https://www.kodeco.com/2866-how-to-synchronize-core-data-with-a-web-service-part-1) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This synchronization tutorial connects local Core Data objects to a web service and discusses import direction. Follow it to identify mapping and conflict boundaries before implementing a bidirectional sync engine.
- [How to Use Cocoa Bindings and Core Data in a Mac App | Kodeco](https://www.kodeco.com/2814-how-to-use-cocoa-bindings-and-core-data-in-a-mac-app) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Cocoa Bindings connect Core Data objects to AppKit controls with less glue code. It is useful legacy material for understanding binding keys and context ownership, while modern SwiftUI may replace the presentation layer.
- [Core Data: Fundamentals | Kodeco](https://www.kodeco.com/27468235-core-data-fundamentals) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Core Data fundamentals connect entities, contexts and persistent stores in a complete model. The guide is useful for separating schema, lifecycle and query concerns before layering SwiftUI observation or CloudKit synchronization.
- [Dynamic Core Data with SwiftUI Tutorial for iOS | Kodeco](https://www.kodeco.com/27201015-dynamic-core-data-with-swiftui-tutorial-for-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Dynamic Core Data content is surfaced in SwiftUI while the model drives changing sections. The tutorial is useful for examining fetch-driven identity and view updates, especially where deletes or inserts can invalidate assumptions about row order.
- [Set Up Core Spotlight with Core Data: Getting Started | Kodeco](https://www.kodeco.com/26871651-set-up-core-spotlight-with-core-data-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Indexes Core Data records in Core Spotlight so users can find app content through system search. Follow it when mapping persistent identity, searchable metadata, and reindexing behavior across updates.
- [MagicalRecord Tutorial for iOS | Kodeco](https://www.kodeco.com/2514-magicalrecord-tutorial-for-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Uses MagicalRecord to create, query, debug, delete, search, and seed Core Data entities. Useful for maintaining an older Core Data stack while recognizing which convenience methods hide context management that modern code should expose deliberately.
- [Video Tutorial: Saving Data in iOS Part 10: Core Data | Kodeco](https://www.kodeco.com/2319-video-tutorial-saving-data-in-ios-part-10-core-data) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Surveys Core Data setup, managed objects, contexts, and persistence in an iOS app. Use it to trace the framework’s object graph and save boundaries before optimizing fetches or introducing newer persistence layers.
- [Top 10 Core Data Tools and Libraries | Kodeco](https://www.kodeco.com/2317-top-10-core-data-tools-and-libraries) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Catalogues tools and libraries that support Core Data development. Follow it when diagnosing persistence workflows, but verify each dependency’s current maintenance before adopting a historical recommendation.
- [Video Tutorial: Saving Data in iOS Part 11: Core Data NSFetchedResultsController | Kodeco](https://www.kodeco.com/2311-video-tutorial-saving-data-in-ios-part-11-core-data-nsfetchedresultscontroller) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Introduces NSFetchedResultsController for observing Core Data changes and updating list views. It helps connect persistence notifications to table updates without manually reloading every row after each save.
- [Integrate Combine Into an App | Kodeco](https://www.kodeco.com/22070915-integrate-combine-into-an-app) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Applies Combine to a complete SwiftUI app through published state, view models, networking, Core Data, and tests. Useful for seeing where reactive pipelines belong in an application rather than adding publishers directly to every view.
- [Video Tutorial: iOS App Extensions Part 7: Today Extensions: Core Data | Kodeco](https://www.kodeco.com/2076-video-tutorial-ios-app-extensions-part-7-today-extensions-core-data) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Shares a Core Data store between an iOS app and a Today extension. The key decision is coordinating an app-group file and context lifecycle so both processes see consistent data without unsafe concurrent writes.
- [Using Core Data in iOS with RubyMotion | Kodeco](https://www.kodeco.com/1764-using-core-data-in-ios-with-rubymotion) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Explores Core Data access from RubyMotion-based iOS code. Use it as historical maintenance context for managed objects and contexts when a non-Swift application still shares Apple persistence concepts.
- [Modern, Efficient Core Data | Kodeco](https://www.kodeco.com/14958063-modern-efficient-core-data) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Combines batch inserts, persistent history tracking, query generations, transaction authors, history tokens, and derived attributes. Useful for designing Core Data synchronization that merges only relevant changes without flooding contexts with broad save notifications.
- [Realm Tutorial: Getting Started | Kodeco](https://www.kodeco.com/1464-realm-tutorial-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Creates Realm models, browses and queries records, applies predicates, updates objects, and organizes categories. Useful for learning the database's object-query workflow before committing to a persistence layer whose thread and migration behavior differs from Core Data.
- [Getting Started with Core Data and CloudKit | Kodeco](https://www.kodeco.com/13219461-getting-started-with-core-data-and-cloudkit) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** NSPersistentCloudKitContainer bridges a Core Data model to CloudKit, making schema and synchronization assumptions explicit. This guide is valuable before enabling sharing or conflict resolution, where local modeling choices become server-visible records.
- [Unit Testing Core Data in iOS | Kodeco](https://www.kodeco.com/11349416-unit-testing-core-data-in-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Demonstrates testing Core Data with isolated stores and controlled managed-object contexts. The key diagnostic boundary is preventing persistent test state from leaking between cases while still exercising fetch, save, and relationship behavior realistically.
- [Beginning Core Data | Kodeco](https://www.kodeco.com/10794954-beginning-core-data) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The Core Data series covers entity modeling, relationships, saving, and fetching, providing a concrete baseline for evaluating persistence-layer choices.
- [Teach your AI to write Swift the Hacking with Swift way – Hacking with Swift](https://www.hackingwithswift.com/articles/284/teach-your-ai-to-write-swift-the-hacking-with-swift-way) — Hacking with Swift articles · article catalogue
  **Published:** `2026-04-01T12:13:39+00:00`
  **NeKI brief:** Presents an AGENTS.md that encodes opinions about SwiftUI, Core Data, and particles for coding agents. Follow it as a concrete example of turning project conventions into reviewable guidance rather than relying on generic prompts.
- [Access application files on iOS simulator](https://nilcoalescing.com/blog/AccessApplicationFilesOniOSSimulator) — Nil Coalescing · article catalogue
  **Published:** `2026-03-04`
  **NeKI brief:** Simulator application data can be located and inspected through the platform's container layout, which is invaluable for checking persistence and exported files. The workflow distinguishes app containers from shared and system data.
- [Core Data Agent Skill: Now available open-source - SwiftLee](https://www.avanderlee.com/ai-development/core-data-agent-skill-now-available-open-source) — Antoine van der Lee articles · article catalogue
  **Published:** `2026-02-08T23:15:00+00:00`
  **NeKI brief:** Introduces an open-source Core Data agent skill containing model, migration, fetch, and persistence guidance. It is useful for steering an assistant through framework-specific invariants instead of letting generated code treat Core Data like a generic database.
- [Deep Dive into iMessage - Behind the Making of an Agent](https://fatbobman.com/en/posts/deep-dive-into-imessage) — Fatbobman · article catalogue
  **Published:** `2025-11-19T14:12:00.000Z`
  **NeKI brief:** Investigates iMessage storage through SQLite and Core Data timestamps, then uses imessage-kit to build an automation agent. The article is a concrete reference for understanding macOS message data boundaries and automation risks.
- [Core Data Migration Incident Analysis - The Hidden Traps We Overlooked](https://fatbobman.com/en/posts/core-data-migration-incident-analysis) — Fatbobman · article catalogue
  **Published:** `2025-07-23T14:00:00.000Z`
  **NeKI brief:** A production migration freeze is traced to WAL checkpoint behavior and work performed during startup. The analysis favors background initialization and explicit WAL optimization, giving a concrete checklist for separating migration cost from main-thread launch failures.
- [Building Type‑Safe, High‑Performance SwiftData / Core Data Models](https://fatbobman.com/en/posts/building-typesafe-highperformance-swiftdata-core-data-models) — Fatbobman · article catalogue
  **Published:** `2025-04-23T14:00:00.000Z`
  **NeKI brief:** Explores type-safe, high-performance model design across SwiftData and Core Data, with attention to schema choices and query behavior. Use it when shaping a persistence layer that balances compile-time clarity, migration needs, and runtime performance.
- [Model Inheritance in Core Data](https://fatbobman.com/en/posts/model-inheritance-in-core-data) — Fatbobman · article catalogue
  **Published:** `2024-12-11T14:00:00.000Z`
  **NeKI brief:** Core Data model inheritance shares attributes through an entity hierarchy, but affects fetches, predicates, and migration shape. This article helps weigh polymorphic convenience against SQL complexity and unexpected inclusion of subtype objects.
- [Using Transactions Instead of Save in SwiftData and Core Data](https://fatbobman.com/en/posts/using-transactions-instead-of-save-in-swiftdata-and-core-data) — Fatbobman · article catalogue
  **Published:** `2024-11-20T14:00:00.000Z`
  **NeKI brief:** Compares transaction-style persistence work with ordinary save calls in SwiftData and Core Data. Use it when batching mutations, rollback boundaries, and consistency matter more than one-off writes.
- [Mastering Data Tracking and Notifications in Core Data and SwiftData](https://fatbobman.com/en/posts/mastering-data-tracking-and-notifications-in-core-data-and-swiftdata) — Fatbobman · article catalogue
  **Published:** `2024-11-06T14:00:00.000Z`
  **NeKI brief:** Explores change tracking and notifications in Core Data and SwiftData. Use it when UI or synchronization logic must react to persistence mutations without polling or broad refreshes.
- [Starting with Project Refactoring - Sharing Five Swift Modules](https://fatbobman.com/en/posts/starting-with-project-refactoring-sharing-five-swift-modules) — Fatbobman · article catalogue
  **Published:** `2024-10-30T14:00:00.000Z`
  **NeKI brief:** A refactoring log extracts five Swift modules from an application, exposing boundaries around shared models, utilities, and feature ownership. Follow it for decisions that reduce coupling without turning every file into a package.
- [Reinventing Core Data Development with SwiftData Principles](https://fatbobman.com/en/posts/reinventing-core-data-development-with-swiftdata-principles) — Fatbobman · article catalogue
  **Published:** `2024-10-16T14:00:00.000Z`
  **NeKI brief:** Examines SwiftData through Core Data's persistence principles, highlighting schema, context, and migration trade-offs. Useful when adopting SwiftData without discarding lessons from mature persistence architecture.
- [How to run Swift Data and Core Data operations in the background and share models across concurrency contexts](https://www.polpiella.dev/core-data-swift-data-concurrency) — Pol Piella · article catalogue
  **Published:** `2024-10-04T00:00:00.000Z`
  **NeKI brief:** Core Data and SwiftData models are context-bound, so background work must pass IDs or values rather than share managed objects across threads. The article builds a stack around that boundary to prevent races and context violations.
- [NSManagedObjectID and PersistentIdentifier - Mastering Data Identifiers in Core Data and SwiftData](https://fatbobman.com/en/posts/nsmanagedobjectid-and-persistentidentifier) — Fatbobman · article catalogue
  **Published:** `2024-09-25T14:00:00.000Z`
  **NeKI brief:** Core Data's NSManagedObjectID and SwiftData's PersistentIdentifier encode object identity differently across stores and contexts. Comparing their lifecycle and URI-style use helps diagnose stale references and choose safe handoff values between persistence layers.
- [Core Data Reform - Achieving Elegant Concurrency Operations like SwiftData](https://fatbobman.com/en/posts/core-data-reform-achieving-elegant-concurrency-operations-like-swiftdata) — Fatbobman · article catalogue
  **Published:** `2024-04-18T00:20:00.000Z`
  **NeKI brief:** The proposed Core Data reform wraps contexts and queue confinement to approximate SwiftData's actor-oriented access model. It is useful when modernizing legacy persistence while preserving existing stores and managed-object APIs.
- [Core Data staged migrations](https://www.polpiella.dev/staged-migrations) — Pol Piella · article catalogue
  **Published:** `2024-03-15T00:00:00.000Z`
  **NeKI brief:** Core Data staged migrations split a model change into explicit mapping steps managed by `NSStagedMigrationManager`. This makes complex schema evolution testable and reviewable, while requiring each intermediate model and mapping to remain supported.
- [Custom Core Data migrations](https://www.polpiella.dev/custom-core-data-migrations) — Pol Piella · article catalogue
  **Published:** `2024-02-21T00:00:00.000Z`
  **NeKI brief:** Custom Core Data migrations provide a mapping policy for transformations that lightweight inference cannot express. The design keeps legacy data readable while requiring explicit tests for each source-to-destination field conversion.
- [Disabling Core Data CloudKit Logging](https://useyourloaf.com/blog/disabling-core-data-cloudkit-logging) — Use Your Loaf · article catalogue
  **Published:** `2024-02-05T13:17:02+00:00`
  **NeKI brief:** Shows how to reduce noisy Core Data and CloudKit logging during development while retaining actionable diagnostics. Useful for separating persistence debugging from unrelated framework chatter.
- [SwiftData Relationships - @Relationship, Inverse, One-to-Many](https://fatbobman.com/en/posts/relationships-in-swiftdata-changes-and-considerations) — Fatbobman · article catalogue
  **Published:** `2024-01-18T00:12:00.000Z`
  **NeKI brief:** SwiftData relationships infer inverses and delete behavior from model declarations, yet optionality and initialization still affect generated schema. The article helps diagnose unexpected relationship mutations and choose explicit @Relationship settings.
- [Mastering Relationships in Core Data - Practical Application](https://fatbobman.com/en/posts/mastering-relationships-in-core-data-practical) — Fatbobman · article catalogue
  **Published:** `2024-01-11T00:12:00.000Z`
  **NeKI brief:** Practical Core Data relationships cover inverse maintenance, delete rules, and fetch behavior under real object graphs. Follow it when a model appears correct but cascades or faulting produce surprising runtime results.
- [Mastering Relationships in Core Data - Fundamentals](https://fatbobman.com/en/posts/mastering-relationships-in-core-data-fundamentals) — Fatbobman · article catalogue
  **Published:** `2024-01-04T00:12:00.000Z`
  **NeKI brief:** Core Data relationship fundamentals explain cardinality, inverses, and object-graph consistency before application-specific code complicates the picture. It is a useful schema-design reference for preventing invalid graph states.
- [SwiftData Fetching Pending Changes](https://useyourloaf.com/blog/swiftdata-fetching-pending-changes) — Use Your Loaf · article catalogue
  **Published:** `2024-01-01T10:03:32+00:00`
  **NeKI brief:** Investigates SwiftData fetches that should include unsaved changes, using SQLDebug output and two historical iOS 17 bugs to show what was actually returned. The updated evidence makes OS-version qualification part of debugging fetch results.
- [Migrating a Core Data store to an App Group shared container](https://www.polpiella.dev/core-data-migration-app-group) — Pol Piella · article catalogue
  **Published:** `2023-11-15T00:00:00.000Z`
  **NeKI brief:** Moving a Core Data store into an App Group container combines a filesystem relocation with model loading and coordinated migration. The sequence must preserve the old store until a successful copy and open have been verified.
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
- [Exploring CoreData - From Data Model Creation to Managed Object Instances](https://fatbobman.com/en/posts/from-data-model-construction-to-managed-object-instances-in-core-data) — Fatbobman · article catalogue
  **Published:** `2023-09-19T00:20:00.000Z`
  **NeKI brief:** Core Data's model, coordinator, context, and managed-object layers form a lifecycle pipeline rather than a single database API. Tracing those boundaries helps diagnose context faults, unsaved changes, and object access on the wrong queue.
- [SwiftDataKit - Unleashing Advanced Core Data Features in SwiftData](https://fatbobman.com/en/posts/use-core-data-features-in-swiftdata-by-swiftdatakit) — Fatbobman · article catalogue
  **Published:** `2023-09-07T00:12:00.000Z`
  **NeKI brief:** SwiftDataKit exposes selected Core Data capabilities behind SwiftData models, allowing advanced store features without abandoning the newer declaration style. Follow it to weigh compatibility benefits against dependency and abstraction leakage.
- [WWDC 2023, What’s New in Core Data](https://fatbobman.com/en/posts/what-s-new-in-core-data-in-wwdc23) — Fatbobman · article catalogue
  **Published:** `2023-07-04T00:12:00.000Z`
  **NeKI brief:** The WWDC 2023 Core Data review maps new capabilities to existing store and context constraints. Follow it when deciding whether an announced API removes a workaround or merely changes where complexity lives.
- [WWDC23 Core Data Lab Notes](https://useyourloaf.com/blog/wwdc23-core-data-lab-notes) — Use Your Loaf · article catalogue
  **Published:** `2023-06-26T10:00:07+01:00`
  **NeKI brief:** Records Core Data lab guidance on CloudKit synchronization and persistence edges, useful historical context for understanding why store coordination must remain explicit.
- [Memory Optimization Journey for a SwiftUI + Core Data App](https://fatbobman.com/en/posts/memory-usage-optimization) — Fatbobman · article catalogue
  **Published:** `2023-03-08T00:20:00.000Z`
  **NeKI brief:** A SwiftUI and Core Data memory investigation correlates object graph retention, fetch size, and view updates with measured footprint. It offers a concrete route from Instruments evidence to targeted reductions rather than speculative cleanup.
- [SwiftUI and Core Data - Safely Responding to Data](https://fatbobman.com/en/posts/modern-core-data-respond-data-safely) — Fatbobman · article catalogue
  **Published:** `2022-12-13T00:20:00.000Z`
  **NeKI brief:** Safely responding to Core Data changes in SwiftUI means separating context notifications from view-facing state and avoiding direct cross-queue object use. The patterns keep updates coherent without broad refetching.
- [SwiftUI and Core Data - Data Fetching](https://fatbobman.com/en/posts/modern-core-data-fetcher) — Fatbobman · article catalogue
  **Published:** `2022-12-06T00:20:00.000Z`
  **NeKI brief:** A dedicated Core Data fetcher separates request construction, context access, and published results, making asynchronous data loading explicit. Follow it when view code has become entangled with fetch timing and cancellation.
- [SwiftUI and Core Data - Data Definition](https://fatbobman.com/en/posts/modern-core-data-data-definition) — Fatbobman · article catalogue
  **Published:** `2022-11-29T00:20:00.000Z`
  **NeKI brief:** Core Data data definition in a SwiftUI app establishes entities, identity, and optionality before view observation begins. The guide helps prevent model shortcuts that later complicate predicates, migrations, and bindings.
- [SwiftUI and Core Data - The Challenges](https://fatbobman.com/en/posts/modern-core-data-problem) — Fatbobman · article catalogue
  **Published:** `2022-11-22T00:20:00.000Z`
  **NeKI brief:** Using Core Data from SwiftUI exposes friction around context confinement, change propagation, and generated object lifetimes. The problem analysis is useful for choosing explicit boundaries before adding observation or convenience wrappers.
- [Ask Apple 2022 Q&A Related on Core Data (Part 2)](https://fatbobman.com/en/posts/core-data-of-ask-apple-2022-2) — Fatbobman · article catalogue
  **Published:** `2022-10-24T00:12:00.000Z`
  **NeKI brief:** Ask Apple Core Data answers address practical concurrency and persistence questions that surface beyond introductory samples. Follow it to compare an app's context rules with documented framework-team reasoning.
- [Ask Apple 2022 Q&A Related on Core Data (Part 1)](https://fatbobman.com/en/posts/core-data-of-ask-apple-2022) — Fatbobman · article catalogue
  **Published:** `2022-10-20T04:12:00.000Z`
  **NeKI brief:** Ask Apple Core Data answers expose practical guidance on contexts, concurrency, and migration boundaries. Follow it to compare community assumptions with framework-team explanations of what the stack guarantees.
- [Old Man New Soldier - A Development Memoir of an iOS APP](https://fatbobman.com/en/posts/healthnote_development_log_2020) — Fatbobman · article catalogue
  **Published:** `2022-09-06T00:12:00.000Z`
  **NeKI brief:** The HealthNote development log exposes product and implementation decisions in a real health-data app, including persistence and feature scope. Follow it for practical trade-offs around privacy-sensitive user workflows.
- [Switching Core Data Cloud Sync Status in Real-Time](https://fatbobman.com/en/posts/real-time-switching-of-cloud-syncs-status) — Fatbobman · article catalogue
  **Published:** `2022-07-26T00:12:00.000Z`
  **NeKI brief:** Switching Core Data CloudKit synchronization at runtime requires coordinating store options, persistent containers, and existing contexts. The workflow is useful for diagnosing stale stores and deciding when a controlled rebuild is safer.
- [WWDC22 Core Data Lab Notes](https://useyourloaf.com/blog/wwdc22-core-data-lab-notes) — Use Your Loaf · article catalogue
  **Published:** `2022-07-11T11:19:23+01:00`
  **NeKI brief:** Summarizes Core Data lab guidance on concurrency, persistent history, and modern store behavior. Use it as a routing index for migration and synchronization decisions, then validate each recommendation against the app's context topology.
- [Batch Operations in Core Data](https://fatbobman.com/en/posts/batchprocessingincoredata) — Fatbobman · article catalogue
  **Published:** `2022-06-06T00:20:00.000Z`
  **NeKI brief:** Core Data batch inserts, updates, and deletes operate at the store level, so managed object contexts do not automatically see every change. The guide highlights merge and refresh steps needed for coherent UI state.
- [How Core Data Saves Data in SQLite](https://fatbobman.com/en/posts/tables_and_fields_of_coredata) — Fatbobman · article catalogue
  **Published:** `2022-05-31T00:20:00.000Z`
  **NeKI brief:** Core Data's SQLite representation uses tables and fields that reflect entities, attributes, and internal metadata rather than a hand-designed schema. Inspecting it is useful for diagnosing migration and fetch-performance surprises.
- [Core Data Saving Changes](https://useyourloaf.com/blog/core-data-saving-changes) — Use Your Loaf · article catalogue
  **Published:** `2022-05-23T11:43:44+01:00`
  **NeKI brief:** Explains Core Data's save propagation from child to parent contexts and persistent store, clarifying where errors surface. The workflow helps choose save boundaries and avoid assuming a child save has durably written user data.
- [Async Core Data Testing](https://useyourloaf.com/blog/async-core-data-testing) — Use Your Loaf · article catalogue
  **Published:** `2022-02-28T14:36:12+00:00`
  **NeKI brief:** Tests asynchronous Core Data operations with explicit completion synchronization, preventing false positives where a test exits before the store work has actually finished.
- [Count Queries in Core Data - The Master Guide](https://fatbobman.com/en/posts/countincoredata) — Fatbobman · article catalogue
  **Published:** `2022-01-17T00:12:00.000Z`
  **NeKI brief:** Counting Core Data records efficiently uses store-side requests instead of fetching full managed objects. The guidance is useful for dashboards and validation paths where memory use and faulting matter.
- [Five things iOS developers should focus on in 2022 – Donny Wals](https://www.donnywals.com/five-things-ios-developers-should-focus-on-in-2022) — Donny Wals · article catalogue
  **Published:** `2022-01-03T09:54:17+00:00`
  **NeKI brief:** The focus areas connect platform fundamentals with sustainable learning habits, offering a prioritization perspective rather than a substitute for project-specific technical requirements.
- [Using @SceneStorage With @FetchRequest](https://useyourloaf.com/blog/using-@scenestorage-with-@fetchrequest) — Use Your Loaf · article catalogue
  **Published:** `2021-12-20T10:19:35+00:00`
  **NeKI brief:** Combines SceneStorage with @FetchRequest to preserve selection or filter state across scene restoration, separating transient UI continuity from persistent Core Data records.
- [How to Deep Copy NSManagedObject in Core Data](https://fatbobman.com/en/posts/mocloner) — Fatbobman · article catalogue
  **Published:** `2021-11-15T00:10:00.000Z`
  **NeKI brief:** Cloning NSManagedObjects requires copying attributes and rebuilding relationships without carrying a source object's identity or context assumptions. The workflow is useful for templates, drafts, and safe duplication in Core Data.
- [Several Tips on Core Data Concurrency Programming](https://fatbobman.com/en/posts/concurrencyofcoredata) — Fatbobman · article catalogue
  **Published:** `2021-11-05T00:20:00.000Z`
  **NeKI brief:** Core Data concurrency depends on context queue confinement and safely passing object IDs rather than managed objects. The article provides a diagnostic model for crashes caused by cross-thread object access.
- [Mastering Core Data Stack](https://fatbobman.com/en/posts/masteringofcoredatastack) — Fatbobman · article catalogue
  **Published:** `2021-11-02T00:10:00.000Z`
  **NeKI brief:** A Core Data stack coordinates model, persistent store coordinator, and contexts with explicit ownership and startup sequencing. The article helps diagnose initialization races and choose boundaries for background context work.
- [Using Combine’s share operator to avoid duplicate work | Swift by Sundell](https://www.swiftbysundell.com/articles/using-combines-share-operator-to-avoid-duplicate-work) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Uses Combine's share operator to multicast one upstream subscription to multiple observers, preventing repeated requests. Sharing changes lifetime and replay behavior, so subscribers must be coordinated deliberately.
- [The power of sets in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/the-power-of-sets-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Uses Set for uniqueness and efficient membership checks when order is not part of the contract. Stable presentation order needs a separate sorted or ordered representation.
- [Maintaining model consistency in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/maintaining-model-consistency-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Maintains model consistency by centralizing invariants and preventing callers from independently mutating related fields. Typed transitions make invalid intermediate states harder to construct.
- [Calling async functions within a Combine pipeline | Swift by Sundell](https://www.swiftbysundell.com/articles/calling-async-functions-within-a-combine-pipeline) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Bridge async functions into a Combine pipeline with a publisher wrapper that forwards values, errors, and cancellation coherently. Keep the concurrency boundary small, since combining two asynchronous models without ownership rules can leave tasks running after cancellation.
- [How to use Derived and Transient Properties in Core Data](https://fatbobman.com/en/posts/derivedandtransient) — Fatbobman · article catalogue
  **Published:** `2021-10-25T23:30:00.000Z`
  **NeKI brief:** Derived and transient Core Data attributes trade store persistence for computed behavior, affecting fetchability and change tracking. Follow it when modeling values that can be recalculated but still need UI observation.
- [Showcasing Core Data in Applications with Spotlight](https://fatbobman.com/en/posts/spotlight) — Fatbobman · article catalogue
  **Published:** `2021-09-22T07:00:00.000Z`
  **NeKI brief:** Spotlight integration exposes app content through searchable identifiers and metadata, with indexing lifecycle separate from UI navigation. Follow it when designing deep-link restoration from a system search result.
- [Core Data with CloudKit - Sharing Data in the iCloud](https://fatbobman.com/en/posts/coredatawithcloudkit-6) — Fatbobman · article catalogue
  **Published:** `2021-09-11T11:20:00.000Z`
  **NeKI brief:** Core Data with CloudKit requires coordinating store configuration, merge behavior, and conflict observation across devices. Follow it when sync symptoms need to be traced to persistence boundaries rather than view updates.
- [How to Preview a SwiftUI View with Core Data Elements in Xcode](https://fatbobman.com/en/posts/coredatainpreview) — Fatbobman · article catalogue
  **Published:** `2021-08-28T00:20:00.000Z`
  **NeKI brief:** Core Data in SwiftUI previews needs isolated stores, seeded fixtures, and deterministic context ownership. The guide helps prevent previews from touching production data or failing because a persistent container is unavailable.
- [Core Data with CloudKit - Synchronizing Public Database](https://fatbobman.com/en/posts/coredatawithcloudkit-5) — Fatbobman · article catalogue
  **Published:** `2021-08-13T11:22:00.000Z`
  **NeKI brief:** Core Data with CloudKit sync debugging requires separating persistent-history changes, merge timing, and CloudKit transport state. The article helps locate cross-device inconsistencies without treating every stale view as a UI bug.
- [Core Data with CloudKit - Troubleshooting](https://fatbobman.com/en/posts/coredatawithcloudkit-4) — Fatbobman · article catalogue
  **Published:** `2021-08-10T23:50:00.000Z`
  **NeKI brief:** CloudKit-backed Core Data stores need deliberate model and container configuration before data can synchronize safely. Follow it when tracing setup errors across development and production environments.
- [Configuring SwiftUI Fetch Requests](https://useyourloaf.com/blog/configuring-swiftui-fetch-requests) — Use Your Loaf · article catalogue
  **Published:** `2021-08-09T10:55:09+01:00`
  **NeKI brief:** Configures a SwiftUI fetch request from runtime predicates or sort descriptors, allowing Core Data views to reflect user-selected filters. Rebuilding the request intentionally avoids stale queries but can reset view-local state.
- [Core Data with CloudKit - Exploring the CloudKit Dashboard](https://fatbobman.com/en/posts/coredatawithcloudkit-3) — Fatbobman · article catalogue
  **Published:** `2021-08-09T09:30:00.000Z`
  **NeKI brief:** Core Data CloudKit synchronization introduces remote-change observation and merge boundaries distinct from ordinary context saves. The guide helps prevent duplicate processing when local and remote transactions overlap.
- [Core Data with CloudKit - Syncing Local Database to iCloud Private Database](https://fatbobman.com/en/posts/coredatawithcloudkit-2) — Fatbobman · article catalogue
  **Published:** `2021-08-09T00:50:00.000Z`
  **NeKI brief:** A CloudKit/Core Data integration must establish store options and account identity before application features assume shared data exists. The article is useful for designing first-run and offline fallback behavior.
- [Core Data with CloudKit - The Basics](https://fatbobman.com/en/posts/coredatawithcloudkit-1) — Fatbobman · article catalogue
  **Published:** `2021-08-05T12:50:00.000Z`
  **NeKI brief:** The first Core Data with CloudKit installment maps object persistence to cloud-backed stores, clarifying deployment and schema prerequisites. Follow it before adding UI observation to a synchronization stack.
- [Using Persistent History Tracking in CoreData](https://fatbobman.com/en/posts/persistenthistorytracking) — Fatbobman · article catalogue
  **Published:** `2021-07-27T04:00:00.000Z`
  **NeKI brief:** Persistent history tracking records Core Data transactions so contexts and extensions can process changes made elsewhere. Follow it when synchronization needs incremental, attributable changes instead of broad save notifications.
- [Testing Core Data In A Swift Package](https://useyourloaf.com/blog/testing-core-data-in-a-swift-package) — Use Your Loaf · article catalogue
  **Published:** `2021-07-12T10:16:08+01:00`
  **NeKI brief:** Sets up an isolated Core Data test stack inside a Swift Package, keeping persistence tests independent from the application target. In-memory stores speed tests, but schema and migration coverage still need dedicated fixtures.
- [WWDC Notes: Bring Core Data concurrency to Swift and SwiftUI – Donny Wals](https://www.donnywals.com/wwdc-notes-bring-core-data-concurrency-to-swift-and-swiftui) — Donny Wals · article catalogue
  **Published:** `2021-06-10T19:27:35+00:00`
  **NeKI brief:** Core Data concurrency requires contexts to respect their queue or executor boundaries, so SwiftUI integration must transfer object identifiers or values rather than managed objects.
- [Core Data In Memory Store](https://useyourloaf.com/blog/core-data-in-memory-store) — Use Your Loaf · article catalogue
  **Published:** `2021-05-24T10:55:02+01:00`
  **NeKI brief:** Uses Core Data's in-memory store for isolated tests and previews. Use it when persistence behavior should be exercised without filesystem state or cleanup.
- [Changing The Core Data Test Store Location](https://useyourloaf.com/blog/changing-the-core-data-test-store-location) — Use Your Loaf · article catalogue
  **Published:** `2021-05-10T10:36:57+01:00`
  **NeKI brief:** Moves a Core Data test store to a controlled location so fixtures and SQLite artifacts are predictable. Explicit paths simplify cleanup and inspection, but tests must avoid sharing mutable stores across parallel runs.
- [Debugging Core Data](https://useyourloaf.com/blog/debugging-core-data) — Use Your Loaf · article catalogue
  **Published:** `2021-04-26T10:04:45+01:00`
  **NeKI brief:** Combines Core Data logging, persistent-store diagnostics, and object-graph inspection to locate faults or save failures. The evidence-first workflow is safer than changing merge policies blindly when the bug is context ownership.
- [How to observe NSManagedObject changes in Core Data using Combine](https://www.avanderlee.com/combine/nsmanagedobject-observe-changes-core-data) — Antoine van der Lee articles · article catalogue
  **Published:** `2021-04-20T07:00:00+00:00`
  **NeKI brief:** Bridges NSManagedObject changes into Combine publishers so individual property updates can refresh UI without redrawing an entire fetched-results list. Useful when NSFetchedResultsController or diffable snapshots miss fine-grained relationship or value changes.
- [Core Data and SwiftUI | Dave DeLong](https://davedelong.com/blog/2021/04/03/core-data-and-swiftui) — Dave DeLong · article catalogue
  **Published:** `2021-04-03T00:00:00+00:00`
  **NeKI brief:** Connects Core Data with SwiftUI state updates. Use it when fetched objects, context changes, and view identity need coordination in a persistence-backed interface.
- [Profiling SwiftUI app using Instruments | Swift with Majid](https://swiftwithmajid.com/2021/01/20/profiling-swiftui-app-using-instruments) — Swift with Majid · article catalogue
  **Published:** `2021-01-20T00:00:00+00:00`
  **NeKI brief:** Uses Instruments to profile SwiftUI performance. Use it when a view-update or rendering problem needs measured call stacks and allocation evidence instead of intuition about declarative UI cost.
- [Preventing unwanted fetches when using NSFetchedResultsController and fetchBatchSize](https://www.donnywals.com/preventing-unwanted-fetches-when-using-nsfetchedresultscontroller-and-fetchbatchsize) — Donny Wals · article catalogue
  **Published:** `2021-01-18T08:45:28+00:00`
  **NeKI brief:** Fetched-results configuration can trigger more Core Data loading than expected; aligning batch size and controller behavior avoids hidden fetch cost during UI updates.
- [10 things iOS developers should focus on in 2021 – Donny Wals](https://www.donnywals.com/10-things-ios-developers-should-focus-on-in-2021) — Donny Wals · article catalogue
  **Published:** `2021-01-04T08:00:12+00:00`
  **NeKI brief:** A 2021 iOS learning snapshot connecting Combine, SwiftUI, testing, and package-management priorities; use it to compare a team's skills against its dated ecosystem baseline rather than current platform guidance.
- [Observing the result of saving a background managed object context with Combine](https://www.donnywals.com/observing-the-result-of-saving-a-background-managed-object-context-with-combine) — Donny Wals · article catalogue
  **Published:** `2020-12-07T07:30:42+00:00`
  **NeKI brief:** A background-context save can publish completion through Combine, letting UI consumers react without crossing managed objects between context confinement boundaries.
- [Responding to changes in a managed object context – Donny Wals](https://www.donnywals.com/responding-to-changes-in-a-managed-object-context) — Donny Wals · article catalogue
  **Published:** `2020-11-23T08:00:41+00:00`
  **NeKI brief:** Context change notifications provide a synchronization signal across Core Data work, but consumers must merge or refetch on their own correct context.
- [Data validation on insertion, update, and deletion in Core Data - SwiftLee](https://www.avanderlee.com/core-data/data-validation) — Antoine van der Lee articles · article catalogue
  **Published:** `2020-11-10T07:58:43+00:00`
  **NeKI brief:** Covers Core Data validation hooks for insertion, updates, and deletion, showing how managed objects reject invalid state before persistence. Checks remain tied to object-level save errors.
- [Derived Attributes to improve Core Data Fetch Performance - SwiftLee](https://www.avanderlee.com/core-data/derived-attributes-optimise-fetch-performance) — Antoine van der Lee articles · article catalogue
  **Published:** `2020-11-03T09:25:35+00:00`
  **NeKI brief:** Uses Core Data derived attributes to precompute values needed for sorting or filtering, reducing fetch-time work. The trade-off is maintaining derived data when source properties change.
- [Discussing CoreData Usage in SwiftUI](https://fatbobman.com/en/posts/coredata-in-swiftui) — Fatbobman · article catalogue
  **Published:** `2020-10-28T04:00:00.000Z`
  **NeKI brief:** Using Core Data in SwiftUI connects managed contexts, fetch requests, and object identity to declarative updates. The guide helps identify where Core Data queue rules still apply despite a SwiftUI view layer.
- [Constraints in Core Data Entities explained - SwiftLee](https://www.avanderlee.com/swift/constraints-core-data-entities) — Antoine van der Lee articles · article catalogue
  **Published:** `2020-10-27T07:00:00+00:00`
  **NeKI brief:** Explains Core Data entity constraints enforcing uniqueness and resolving conflicts during saves. Model configuration must be paired with an appropriate merge policy for duplicates.
- [NSManagedObject events: handling state in Core Data - SwiftLee](https://www.avanderlee.com/swift/nsmanagedobject-awakefrominsert-preparefordeletion) — Antoine van der Lee articles · article catalogue
  **Published:** `2020-10-20T06:35:23+00:00`
  **NeKI brief:** Traces NSManagedObject callbacks such as awakeFromInsert and prepareForDeletion for defaults and relationship cleanup. Knowing callback timing prevents lifecycle side effects in ordinary observers.
- [Observing changes to managed objects across contexts with Combine – Donny Wals](https://www.donnywals.com/observing-changes-to-managed-objects-across-contexts-with-combine) — Donny Wals · article catalogue
  **Published:** `2020-10-12T14:01:32+00:00`
  **NeKI brief:** Combine can observe Core Data context changes and feed UI updates, but object identity and context confinement still govern what may cross threads.
- [Understanding the differences between your Core Data model and managed objects](https://www.donnywals.com/understanding-the-differences-between-your-core-data-model-and-managed-objects) — Donny Wals · article catalogue
  **Published:** `2020-10-05T09:39:16+00:00`
  **NeKI brief:** A Core Data model describes persistent schema while managed objects are context-bound runtime instances; separating them prevents mistaken assumptions about thread safety and lifecycle.
- [How-to use Diffable Data Sources with Core Data - SwiftLee](https://www.avanderlee.com/swift/diffable-data-sources-core-data) — Antoine van der Lee articles · article catalogue
  **Published:** `2020-09-22T07:45:52+00:00`
  **NeKI brief:** Integrates Core Data changes with UICollectionViewDiffableDataSource using stable identifiers and snapshots. The approach replaces index-path bookkeeping but requires careful update and deletion handling.
- [Persistent History Tracking in Core Data - SwiftLee](https://www.avanderlee.com/swift/persistent-history-tracking-core-data) — Antoine van der Lee articles · article catalogue
  **Published:** `2020-09-08T07:00:00+00:00`
  **NeKI brief:** Shows persistent history tracking for querying transactions made by other contexts or processes, then marking history consumed. It supports extension synchronization without observing every live context.
- [Write-Ahead Logging (WAL) disabled to force commits in Core Data](https://www.avanderlee.com/swift/write-ahead-logging-wal) — Antoine van der Lee articles · article catalogue
  **Published:** `2020-08-25T13:51:17+00:00`
  **NeKI brief:** Explains SQLite write-ahead logging in Core Data and why disabling WAL can force commits into the main store. The trade-off matters for durability and cross-process visibility.
- [Implementing a one-way sync strategy with Core Data, URLSession and Combine](https://www.donnywals.com/implementing-a-one-way-sync-strategy-with-core-data-urlsession-and-combine) — Donny Wals · article catalogue
  **Published:** `2020-08-24T10:40:45+00:00`
  **NeKI brief:** A one-way sync pipeline fetches remote data, maps it, and persists it into Core Data, requiring conflict and offline-refresh policy at the boundary.
- [Fetching objects from Core Data in a SwiftUI project – Donny Wals](https://www.donnywals.com/fetching-objects-from-core-data-in-a-swiftui-project) — Donny Wals · article catalogue
  **Published:** `2020-08-10T09:48:04+00:00`
  **NeKI brief:** Fetches Core Data objects into a SwiftUI view with an observation-aware wrapper. Use it when persistence updates should drive UI changes without manual reload logic.
- [Using Codable with Core Data and NSManagedObject – Donny Wals](https://www.donnywals.com/using-codable-with-core-data-and-nsmanagedobject) — Donny Wals · article catalogue
  **Published:** `2020-08-03T08:54:44+00:00`
  **NeKI brief:** Making managed objects Codable crosses persistence and transport concerns, so context ownership, relationships, and decoding side effects need explicit containment.
- [Setting up a Core Data store for unit tests – Donny Wals](https://www.donnywals.com/setting-up-a-core-data-store-for-unit-tests) — Donny Wals · article catalogue
  **Published:** `2020-07-27T07:00:53+00:00`
  **NeKI brief:** Sets up an isolated Core Data store for unit tests. Use it when persistence tests need deterministic data and migrations without touching an application's real database.
- [Using Core Data with SwiftUI 2.0 and Xcode 12 – Donny Wals](https://www.donnywals.com/using-core-data-with-swiftui-2-0-and-xcode-12) — Donny Wals · article catalogue
  **Published:** `2020-07-20T07:00:48+00:00`
  **NeKI brief:** SwiftUI app lifecycle setup can inject a persistent Core Data container through the environment, keeping view fetches context-bound and previewable.
- [ValueTransformer in Core Data explained: Storing absolute URLs](https://www.avanderlee.com/swift/valuetransformer-core-data) — Antoine van der Lee articles · article catalogue
  **Published:** `2020-07-14T07:00:00+00:00`
  **NeKI brief:** Implements a Core Data ValueTransformer to persist URL values while exposing a typed Swift property, including registration and conversion failures. It bridges unsupported model types safely.
- [Core Data Performance: 6 tips you should know - SwiftLee](https://www.avanderlee.com/swift/core-data-performance) — Antoine van der Lee articles · article catalogue
  **Published:** `2020-06-02T07:00:00+00:00`
  **NeKI brief:** Connects Core Data performance to fetch limits, batching, faulting, predicates, and background contexts. Each technique targets store work or memory pressure and suggests profiling leads.
- [Using launch arguments for easier Core Data and SwiftData debugging – Donny Wals](https://www.donnywals.com/using-launch-arguments-for-easier-core-data-debugging) — Donny Wals · article catalogue
  **Published:** `2019-12-01T08:00:00+00:00`
  **NeKI brief:** Launch arguments enable Core Data diagnostics without changing source code, making SQL and migration behavior inspectable in a reproducible debug configuration.
- [Core Data and App extensions: Sharing a single database - SwiftLee](https://www.avanderlee.com/swift/core-data-app-extension-data-sharing) — Antoine van der Lee articles · article catalogue
  **Published:** `2019-10-29T08:00:39+00:00`
  **NeKI brief:** Shares a Core Data store between an app and extensions through an app group, coordinating container setup and saves. Cross-process use requires concurrency and migration care.
- [Array vs Set: Fundamentals in Swift explained - SwiftLee](https://www.avanderlee.com/swift/array-vs-set-differences-explained) — Antoine van der Lee articles · article catalogue
  **Published:** `2019-08-06T07:00:41+00:00`
  **NeKI brief:** Contrasts Array's ordered duplicate-preserving storage with Set's uniqueness and hash-based membership, including performance implications. Selection should follow access and identity requirements.
- [Using NSBatchDeleteRequest to delete batches in Core Data - SwiftLee](https://www.avanderlee.com/swift/nsbatchdeleterequest-core-data) — Antoine van der Lee articles · article catalogue
  **Published:** `2019-05-21T07:00:06+00:00`
  **NeKI brief:** Uses NSBatchDeleteRequest to remove records directly at the persistent-store SQL layer, then addresses context-merging pitfalls. Useful for large purges where per-object deletion is slow, provided in-memory contexts are refreshed correctly.
- [Faster App Setup For Unit Tests](https://useyourloaf.com/blog/faster-app-setup-for-unit-tests) — Use Your Loaf · article catalogue
  **Published:** `2019-01-28T10:34:42+00:00`
  **NeKI brief:** Describes reducing application launch overhead for unit tests by separating test setup from full app initialization. Follow it when test suites are slow because production composition runs unnecessarily for isolated cases.
- [PhotoKit’s data model – Ole Begemann](https://oleb.net/2018/photos-data-model) — Ole Begemann · article catalogue
  **Published:** `2018-09-28T15:36:36Z`
  **NeKI brief:** PhotoKit separates assets, resources, and changes, so an app should request the representation it needs rather than assume a thumbnail is the original. Understanding those layers prevents unnecessary downloads and makes authorization failures easier to handle.
- [Core Data Debugging in Xcode using launch arguments - SwiftLee](https://www.avanderlee.com/debugging/core-data-debugging-xcode) — Antoine van der Lee articles · article catalogue
  **Published:** `2018-07-03T10:00:11+00:00`
  **NeKI brief:** Uses launch arguments and Xcode diagnostics to inspect Core Data SQL, query performance, thread-safety violations, and migration behavior. Useful for turning opaque persistence bugs into observable store-level evidence.
- [The Laws of Core Data | Dave DeLong](https://davedelong.com/blog/2018/05/09/the-laws-of-core-data) — Dave DeLong · article catalogue
  **Published:** `2018-05-09T00:00:00+00:00`
  **NeKI brief:** Core Data laws frame managed objects as context-bound lifecycles rather than ordinary models, clarifying why thread confinement and save ordering are correctness constraints.
- [How to make a copy of a Core Data SQLite database – Ole Begemann](https://oleb.net/blog/2018/03/core-data-sqlite-backup) — Ole Begemann · article catalogue
  **Published:** `2018-03-23T12:20:00Z`
  **NeKI brief:** Copying a Core Data SQLite store while its journal is active can produce an inconsistent backup. The article points to coordinating saves and persistent-store lifecycle so the snapshot reflects a transactionally valid database.
- [A better NSManagedObjectContext.performAndWait – Ole Begemann](https://oleb.net/blog/2018/02/performandwait) — Ole Begemann · article catalogue
  **Published:** `2018-02-19T22:04:00Z`
  **NeKI brief:** An overload of `performAndWait` can return the closure's result while preserving Core Data's queue confinement. The convenience removes mutable out-parameters, but callers still need to respect context ownership and avoid reentrant work.
- [Moving Core Data Files](https://useyourloaf.com/blog/moving-core-data-files) — Use Your Loaf · article catalogue
  **Published:** `2017-05-15T09:40:13+01:00`
  **NeKI brief:** Moves Core Data store files safely, accounting for SQLite sidecar files and persistent-store coordination. Treat the store as a set of related artifacts and close contexts before relocating it.
- [Cleaning up Core Data Fetch Requests](https://useyourloaf.com/blog/cleaning-up-core-data-fetch-requests) — Use Your Loaf · article catalogue
  **Published:** `2017-01-30T12:59:27+00:00`
  **NeKI brief:** Refactors Core Data fetch setup into focused descriptors, predicates, and result configuration. Clear request construction improves reuse, while fetch performance still depends on indexes and faulting behavior.
- [Easier Core Data Setup with Persistent Containers](https://useyourloaf.com/blog/easier-core-data-setup-with-persistent-containers) — Use Your Loaf · article catalogue
  **Published:** `2017-01-16T13:27:14+00:00`
  **NeKI brief:** Uses NSPersistentContainer to centralize Core Data stack setup, store loading, and context access. The convenience reduces boilerplate, but merge policy and background-context behavior still require explicit application decisions.
- [Core Data Code Generation](https://useyourloaf.com/blog/core-data-code-generation) — Use Your Loaf · article catalogue
  **Published:** `2017-01-02T13:41:20+00:00`
  **NeKI brief:** Covers Core Data managed-object code generation choices and their effect on customization and regeneration. Manual subclasses offer control, while generated code requires keeping model and source ownership aligned.
- [New Swift, Core Data and Cocoa Books](https://useyourloaf.com/blog/new-swift-core-data-and-cocoa-books) — Use Your Loaf · article catalogue
  **Published:** `2016-05-16T10:43:25+01:00`
  **NeKI brief:** Collects book recommendations around Swift, Core Data, and Cocoa as a learning route. Treat editions as historical context and cross-check API guidance against current Apple documentation.
- [cellForRowAtIndexPath in Four Lines](https://useyourloaf.com/blog/cellforrowatindexpath-in-four-lines) — Use Your Loaf · article catalogue
  **Published:** `2015-10-26T12:59:18+00:00`
  **NeKI brief:** Demonstrates reducing table-cell configuration boilerplate through focused helpers or data modeling. Concision should not hide reuse identifiers, registration, or the cell's state-reset responsibilities.
- [Creating an OS X Core Data Helper App](https://useyourloaf.com/blog/creating-an-os-x-core-data-helper-app) — Use Your Loaf · article catalogue
  **Published:** `2015-03-25T21:46:47+00:00`
  **NeKI brief:** Uses a helper app around Core Data for focused management or diagnostics outside the main iOS client. Shared-store access requires coordinated model versions and clear ownership of migrations.
- [Weekly Swift 3, Interfaces and CoreData – Donny Wals](https://www.donnywals.com/weekly-swift-3-interfaces-and-coredata) — Donny Wals · article catalogue
  **Published:** `2015-02-13T09:09:35+00:00`
  **NeKI brief:** The Swift learning update connects protocol interfaces with Core Data exploration, showing how persistence concerns and type contracts influence early architecture choices.
- [Core Data Concurrency Debugging – Ole Begemann](https://oleb.net/blog/2014/06/core-data-concurrency-debugging) — Ole Begemann · article catalogue
  **Published:** `2014-06-11T21:22:00Z`
  **NeKI brief:** Enables Core Data's concurrency debugging to expose managed-object-context access on the wrong queue, turning a corruption-prone threading mistake into a diagnosable runtime failure during development.
- [How Dropbox Uses C++ for Cross-Platform iOS and Android Development – Ole Begemann](https://oleb.net/blog/2014/05/how-dropbox-uses-cplusplus-cross-platform-development) — Ole Begemann · article catalogue
  **Published:** `2014-05-23T20:17:00Z`
  **NeKI brief:** Analyzes Dropbox's former C++ shared-core strategy for iOS and Android, including the integration costs that later led it back to native languages and SDKs.
- [NSPredicate - NSHipster](https://nshipster.com/nspredicate) — NSHipster · article catalogue
  **Published:** `2013-07-15T00:00:00-07:00`
  **NeKI brief:** Explains NSPredicate's query syntax for filtering and fetching collections. Useful for expressing selection declaratively while keeping predicate-format construction, validation, and data-store semantics visible.
- [NSExpression - NSHipster](https://nshipster.com/nsexpression) — NSHipster · article catalogue
  **Published:** `2013-07-08T00:00:00-07:00`
  **NeKI brief:** NSExpression evaluates key-path and operator expressions used by predicates and aggregations. Use it only with trusted, constrained inputs, since opaque expression strings make validation and debugging harder than typed transformations.
- [iCloud - NSHipster](https://nshipster.com/icloud) — NSHipster · article catalogue
  **Published:** `2013-04-01T00:00:00-07:00`
  **NeKI brief:** iCloud services synchronize selected app data through distinct APIs with different conflict and availability behavior. Use the service that matches the data model, designing offline states and merge policy rather than assuming instant consistency.
- [Core Data by Marcus Zarra](https://useyourloaf.com/blog/core-data-by-marcus-zarra) — Use Your Loaf · article catalogue
  **Published:** `2013-03-07T22:12:00+00:00`
  **NeKI brief:** Routes to Core Data learning material as a deeper persistence reference. Apply patterns selectively and verify concurrency, migration, and framework APIs against the current platform.
- [ValueTransformer - NSHipster](https://nshipster.com/valuetransformer) — NSHipster · article catalogue
  **Published:** `2012-11-12T00:00:00-08:00`
  **NeKI brief:** Describes ValueTransformer as a boundary for converting model values to persisted or transport representations. Use it when maintaining Core Data transformations, checking registration, reversibility, and compatibility with modern Codable or transformable attributes.
- [Adding A Search Bar To A Table View With Storyboards](https://useyourloaf.com/blog/search-bar-table-view-storyboard) — Use Your Loaf · article catalogue
  **Published:** `2012-09-06T15:10:00+00:00`
  **NeKI brief:** Integrates a search bar with a table view in a storyboard-based UI while maintaining filtering state. Keep query handling separate from cell rendering so updates remain testable.
- [Prototype Table Cells and Storyboards](https://useyourloaf.com/blog/prototype-table-cells-and-storyboards) — Use Your Loaf · article catalogue
  **Published:** `2012-06-07T13:42:00+00:00`
  **NeKI brief:** Uses prototype table cells in storyboards to define reusable row layouts and identifiers. Cells must still reset state on reuse and adapt to dynamic type and different data lengths.
- [Core Data Queries Using Expressions](https://useyourloaf.com/blog/core-data-queries-using-expressions) — Use Your Loaf · article catalogue
  **Published:** `2012-01-19T22:15:00+00:00`
  **NeKI brief:** Uses Core Data expressions in fetch requests for computed or aggregate query results. Expressions can reduce data transfer, but their store support and result types need verification.
- [Sync preference data with iCloud](https://useyourloaf.com/blog/sync-preference-data-with-icloud) — Use Your Loaf · article catalogue
  **Published:** `2011-10-24T21:50:00+00:00`
  **NeKI brief:** Syncs small preference values through iCloud key-value storage while handling conflicts and availability. Keep preferences separate from authoritative user data and define a deterministic merge policy.
- [Passing Arguments with Xcode 4](https://useyourloaf.com/blog/passing-arguments-with-xcode-4) — Use Your Loaf · article catalogue
  **Published:** `2011-07-03T22:29:00+00:00`
  **NeKI brief:** Uses Xcode scheme arguments to configure launches for development or testing without source edits. Arguments should be documented and isolated from user-persisted preferences.
- [Inspecting Core Data Attributes – Ole Begemann](https://oleb.net/blog/2011/05/inspecting-core-data-attributes) — Ole Begemann · article catalogue
  **Published:** `2011-05-04T21:35:00Z`
  **NeKI brief:** Uses Core Data model introspection to inspect entities, property descriptions, and attribute types at runtime. Follow it when generic import, validation, or diagnostics code must adapt behavior to a managed object model instead of hard-coding fields.
- [Searching arrays with NSPredicate and blocks](https://useyourloaf.com/blog/searching-arrays-with-nspredicate-and-blocks) — Use Your Loaf · article catalogue
  **Published:** `2010-10-19T21:06:00+00:00`
  **NeKI brief:** Uses NSPredicate and block-based filtering to query arrays with explicit conditions. Predicate strings are flexible but need careful key validation; typed Swift closures are often safer for new code.
- [Filtering arrays with NSPredicate](https://useyourloaf.com/blog/filtering-arrays-with-nspredicate) — Use Your Loaf · article catalogue
  **Published:** `2010-07-27T22:24:00+00:00`
  **NeKI brief:** Filters arrays with NSPredicate for reusable condition logic over Foundation collections. Typed Swift closures are often safer for new code, while predicate strings need carefully controlled keys and formats.
- [Using categories with private methods](https://useyourloaf.com/blog/using-categories-with-private-methods) — Use Your Loaf · article catalogue
  **Published:** `2010-03-24T22:54:00+00:00`
  **NeKI brief:** Use a class extension or category to keep Objective-C helper methods private to the implementation file, preserving a small public interface while organizing internal behavior without exposing implementation details to callers.
- [Using categories with core data](https://useyourloaf.com/blog/using-categories-with-core-data) — Use Your Loaf · article catalogue
  **Published:** `2010-03-23T18:34:00+00:00`
  **NeKI brief:** Use Objective-C categories to extend generated Core Data classes without losing custom methods when model files are regenerated. Keep generated and hand-written concerns separate so schema updates do not erase application behavior.
- [NSFetchedResultsController and sort performance](https://useyourloaf.com/blog/nsfetchedresultscontroller-and-sort-performance) — Use Your Loaf · article catalogue
  **Published:** `2010-03-15T14:29:00+00:00`
  **NeKI brief:** Fetched-results controllers simplify Core Data table updates, but grouped-table performance depends heavily on store-side sort descriptors. Avoid expensive case-insensitive sorting without measuring it; optimize the persistent representation or query when grouping becomes the bottleneck.
- [Finding memory leaks in Xcode](https://useyourloaf.com/blog/finding-memory-leaks-in-xcode) — Use Your Loaf · article catalogue
  **Published:** `2010-03-12T18:29:00+00:00`
  **NeKI brief:** Keep leak-diagnosis launch arguments ready but disabled by default: zombies expose use-after-free, malloc stack logging traces allocations, and Core Data SQL debug shows persistence work. Enable only the necessary instrumentation, since these flags alter performance and must never ship.
- [Debugging core data on the iPhone](https://useyourloaf.com/blog/debugging-core-data-on-the-iphone) — Use Your Loaf · article catalogue
  **Published:** `2010-03-11T19:36:00+00:00`
  **NeKI brief:** Enable Core Data SQL tracing through launch arguments when on-device tools do not expose persistence work. Read the emitted queries alongside slow operations to distinguish fetch design, faulting, and store-level costs before optimizing application code.
- [The differences between Core Data and a Database | Cocoa with Love](https://www.cocoawithlove.com/2010/02/differences-between-core-data-and.html) — Cocoa with Love · article catalogue
  **Published:** `2010-02-16`
  **NeKI brief:** Core Data manages an object graph and persistence context rather than exposing a plain relational database contract. The comparison clarifies faulting, identity, and change tracking before choosing queries or storage abstractions.
- [Finding the cause of performance issues in your programs | Cocoa with Love](https://www.cocoawithlove.com/2010/02/finding-cause-of-simple-performance.html) — Cocoa with Love · article catalogue
  **Published:** `2010-02-01`
  **NeKI brief:** Simple performance investigations start by measuring a reproducible workload and narrowing the dominant operation before optimizing. The workflow remains useful for avoiding intuition-driven changes in Cocoa code.
- [There's a Garbage Collection ninja hiding in the project templates | Cocoa with Love](https://www.cocoawithlove.com/2009/12/there-garbage-collection-ninja-hiding.html) — Cocoa with Love · article catalogue
  **Published:** `2009-12-01`
  **NeKI brief:** Garbage collection can hide leaks while leaving resource lifetime, cycles, and responsiveness unresolved. The essay helps distinguish memory reclamation from deterministic cleanup and ownership design.
- [Performance tests: Replacing Core Data Key Paths | Cocoa with Love](https://www.cocoawithlove.com/2009/11/performance-tests-replacing-core-data.html) — Cocoa with Love · article catalogue
  **Published:** `2009-11-21`
  **NeKI brief:** Replacing Core Data should be evaluated with representative persistence benchmarks, not assumptions about ORM overhead. The tests connect query shape, object creation, and caching behavior to measurable trade-offs.
- [Verifying that a string contains an email address using NSPredicate | Cocoa with Love](https://www.cocoawithlove.com/2009/06/verifying-that-string-is-email-address.html) — Cocoa with Love · article catalogue
  **Published:** `2009-06-23`
  **NeKI brief:** Email-address validation must separate superficial syntax checks from actual mailbox verification and product policy. The discussion helps avoid regexes that reject valid addresses or imply a stronger guarantee than validation provides.
- [Serving an NSManagedObjectContext over an NSConnection | Cocoa with Love](https://www.cocoawithlove.com/2009/01/serving-nsmanagedobjectcontext-over.html) — Cocoa with Love · article catalogue
  **Published:** `2009-01-05`
  **NeKI brief:** Serving an NSManagedObjectContext over a boundary exposes why contexts are not thread-safe data services. Follow it when designing a persistence interface that must pass IDs or values instead of live managed objects.
- [Safely fetching an NSManagedObject by URI | Cocoa with Love](https://www.cocoawithlove.com/2008/08/safely-fetching-nsmanagedobject-by-uri.html) — Cocoa with Love · article catalogue
  **Published:** `2008-08-24`
  **NeKI brief:** Persist a managed object's URI representation when crossing context boundaries, but treat resolving it as fallible because stores, contexts, and deleted objects can invalidate the apparent reference. Validate the persistent-store coordinator's result before using it.
- [Key Value Information | Cocoa with Love](https://www.cocoawithlove.com/2008/07/key-value-information.html) — Cocoa with Love · article catalogue
  **Published:** `2008-07-27`
  **NeKI brief:** KVC dynamically resolves accessor methods but does not directly expose an object's complete supported-key contract. Inspecting classes and accessors can reveal likely keys, yet dynamic resolution means runtime behavior remains more authoritative than reflection alone.
- [Propagate deletes immediately in Core Data | Cocoa with Love](https://www.cocoawithlove.com/2008/04/propagate-deletes-immediately-in-core.html) — Cocoa with Love · article catalogue
  **Published:** `2008-04-25`
  **NeKI brief:** Core Data cascade deletes may not update dependent graph state at the moment an app expects. Perform required relationship cleanup deliberately before saving when UI or business logic needs immediate consistency, then let the persistent store commit the final transaction.
- [Testing Core Data with very big hierarchical data sets | Cocoa with Love](https://www.cocoawithlove.com/2008/03/testing-core-data-with-very-big.html) — Cocoa with Love · article catalogue
  **Published:** `2008-03-28`
  **NeKI brief:** Benchmark Core Data with a realistic large hierarchy across creation, load, fetch, and traversal phases instead of inferring scale from small fixtures. Split measurements by operation so indexing, faulting, and relationship walking bottlenecks are distinguishable.
- [Core Data: one line fetch | Cocoa with Love](https://www.cocoawithlove.com/2008/03/core-data-one-line-fetch.html) — Cocoa with Love · article catalogue
  **Published:** `2008-03-07`
  **NeKI brief:** A concise Core Data fetch helper can remove boilerplate for ordinary queries while retaining the framework's predicate and context semantics. Do not let one-line convenience hide error handling, fetch limits, batching, or memory behavior needed by larger datasets.
- [Understanding the @FetchRequest property wrapper in SwiftUI](https://tanaschita.com/swiftui-fetchrequest-property-wrapper) — Tanaschita · article catalogue
  **NeKI brief:** Explains @FetchRequest as a SwiftUI-driven Core Data query, clarifying predicate, sort, and managed-object context boundaries that affect view updates.
- [How to set up and use Core Data with SwiftUI](https://tanaschita.com/coredata-with-swiftui) — Tanaschita · article catalogue
  **NeKI brief:** Core Data is connected to SwiftUI through managed contexts, fetch requests and model updates. Follow it to examine observation boundaries, especially where view-driven mutations need validation and background persistence.
- [How to perform a lightweight migration in Core Data](https://tanaschita.com/core-data-lightweight-migration) — Tanaschita · article catalogue
  **NeKI brief:** Lightweight Core Data migration handles compatible model changes through inferred mapping. The article is useful for deciding when automatic migration is sufficient and when a custom mapping model or staged data transform is required.
- [Get started with NSPredicate to filter NSFetchRequest in Core Data](https://tanaschita.com/20230320-cheatsheet-nspredicate-fetchrequest-core-data) — Tanaschita · article catalogue
  **NeKI brief:** NSPredicate filters NSFetchRequest results with composable conditions and comparisons. Follow it to keep filtering in the persistence layer, while validating format strings and avoiding broad in-memory scans.
- [How to handle non-optional Core Data properties in Swift](https://tanaschita.com/20221114-how-to-handle-non-optional-core-data-values-in-swift) — Tanaschita · article catalogue
  **NeKI brief:** Explains handling Core Data attributes that are non-optional in Swift models despite migration or generated-code constraints. Follow it when aligning schema validation, managed-object access, and safe defaulting behavior.
- [How to create NSManagedObject subsclasses for Core Data entities in Xcode](https://tanaschita.com/20221024-how-to-create-a-managed-object-subclass-xcode-core-data) — Tanaschita · article catalogue
  **NeKI brief:** Core Data code-generation modes determine which managed-object classes Xcode owns or expects developers to maintain. Follow it to prevent generated files being overwritten and to keep model changes aligned with source extensions.
- [iOS developer guide on the main aspects of Core Data](https://tanaschita.com/20220919-understanding-the-main-aspects-of-core-data) — Tanaschita · article catalogue
  **NeKI brief:** This Core Data overview connects model files, contexts, stores and fetches into one persistence architecture. Follow it to establish terminology before deciding where observation, background work and migrations belong.
- [Why Swift is the most satisfying language for using Core Data](https://martiancraft.com/blog/2015/12/nsmanaged) — MartianCraft · article catalogue
  **NeKI brief:** Swift can wrap Core Data's dynamic @NSManaged accessors with custom, expressive computed APIs while preserving Objective-C compatibility. Put validation and type conversion at that boundary, and automate repetitive accessor generation only after the model contract is clear.
- [Moving from Objective-C to Swift with Core Data](https://martiancraft.com/blog/2015/07/objective-c-swift-core-data) — MartianCraft · article catalogue
  **NeKI brief:** Migrate Core Data helpers from Objective-C categories to Swift by replacing unsafe casts with typed errors and protocol extensions. Preserve the established managed-object behavior while using Swift's type system to make invalid conversions visible at compile time.
- [Shared Core Data](https://martiancraft.com/blog/2015/06/shared-core-data) — MartianCraft · article catalogue
  **NeKI brief:** Sharing Core Data across an app-group's processes needs a real change-propagation strategy, not just a common store URL. Coordinate contexts and persistent-store updates so each process notices external writes without corrupting or indefinitely caching stale objects.
- [My Core Data Stack](https://martiancraft.com/blog/2015/03/core-data-stack) — MartianCraft · article catalogue
  **NeKI brief:** A production-oriented Core Data stack walkthrough covering setup, contexts, and persistence boundaries. Use it to compare lifecycle and concurrency choices before adopting a shared storage layer.
- [Lenses in Swift — Chris Eidhof](https://chris.eidhof.nl/post/lenses-in-swift) — Chris Eidhof · article catalogue
  **NeKI brief:** Explores lenses as composable getter-and-setter pairs for reading and updating nested data in Swift. Use it to understand a functional approach to immutable-style updates rather than as a required Swift design pattern.
- [Accessing an API using CoreData's NSIncrementalStore — Chris Eidhof](https://chris.eidhof.nl/post/accessing-an-api-using-coredatas-nsincrementalstore) — Chris Eidhof · article catalogue
  **NeKI brief:** Builds an object-graph facade over the Bandcamp API by parsing responses, modeling entities and relationships in Core Data, then implementing an NSIncrementalStore to fetch them lazily. Use it to study decoupling controllers from API shape, while treating the experiment as historical.
- [Weeknotes № 21 — Chris Eidhof](https://chris.eidhof.nl/post/2023-21) — Chris Eidhof · article catalogue
  **NeKI brief:** A development weeknote about recreating Git's core read-only data structures in Swift and then experimenting with writing them. Useful as an approachable pointer to Git's underlying object model.

## Newsletter and related leads

- [Core Data + Observation: From Property-Level Reactivity to a Freer Mental Model](https://fatbobman.com/en/posts/core-data-observation-freer-mental-model?ref=createwithswift.com) — Create with Swift · Issue 110 — Article · Topics: Core Data · Persistence & Synchronisation · Swift
  **Published:** `2026-06-06T14:00:23.000Z`
  **NeKI brief:** Explains how Core Data observation shifts from property-level change tracking toward a broader data-flow model, clarifying where SwiftUI invalidation and persistence boundaries meet.
- [Core Data + Observation: From Property-Level Reactivity to a Freer Mental Model](https://fatbobman.com/en/posts/core-data-observation-freer-mental-model) — iOS Dev Weekly · Issue 753 — Article · Topics: Core Data · Persistence & Synchronisation · Swift
  **Published:** `5th June 2026`
  **NeKI brief:** Explains how Core Data observation shifts from property-level change tracking toward a broader data-flow model, clarifying where SwiftUI invalidation and persistence boundaries meet.
- [Fatbobman](https://fatbobman.com/en/about) — iOS Dev Weekly · Issue 753 — Article · Topics: Core Data · Persistence & Synchronisation · Swift
  **Published:** `5th June 2026`
  **NeKI brief:** Presents fatbobman for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Building a Custom Data Store in SwiftData](https://azamsharp.com/2026/05/26/building-a-custom-data-store-in-swiftdata.html) — iOS Dev Weekly · Issue 752 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `29th May 2026`
  **NeKI brief:** Walks through implementing a custom SwiftData store and the integration points needed to replace default persistence; useful when evaluating storage backends and their lifecycle trade-offs.
- [Core Data Evolution](https://github.com/fatbobman/CoreDataEvolution) — Fatbobman’s Swift Weekly · Issue 128 — Source repository · Topics: Core Data · Persistence & Synchronisation · Swift
  **Published:** `2026-03-23T12:02:22.360Z`
  **NeKI brief:** CoreDataEvolution experiments with bringing ModelActor-like concurrency structure to Core Data. Use it when modernizing a Core Data stack while retaining its model and store, especially to centralize context ownership and serialized mutations.
- [Apple Doesn’t Show SwiftData iCloud Sync Status — So Let’s Build One](https://azamsharp.com/2026/03/16/swiftdata-icloud-sync-status.html) — Those Who Swift · Issue 258 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `2026-03-18`
  **NeKI brief:** Examines Apple Doesn’t Show SwiftData iCloud Sync Status — So Let’s Build One, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Why Does Passing NSManagedObjectContext Across Isolation Domains No Longer Error in Swift 6.2?](https://fatbobman.com/en/posts/sendable-nsmanagedobjectcontext) — SwiftLee Weekly · Issue 314 — Article · Topics: Concurrency · Core Data · Swift
  **Published:** `2026-03-10T15:03:18.000Z`
  **NeKI brief:** Explains why NSManagedObjectContext crossing isolation domains no longer errors in Swift 6.2. Use it to review Core Data concurrency assumptions and verify the behavior against the active compiler and SDK.
- [Measuring Core Data and SwiftData](https://yaacoub.github.io/articles/swift-tip/measuring-core-data-and-swiftdata) — iOS Dev Weekly · Issue 744 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `27th February 2026`
  **NeKI brief:** Presents measuring core data and swiftdata for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Swift Concurrency](https://github.com/AvdLee/Swift-Concurrency-Agent-Skill) — Fatbobman’s Swift Weekly · Issue 121 — Source repository · Topics: Concurrency · Swift · SwiftUI
  **Published:** `2026-02-02T12:03:11.621Z`
  **NeKI brief:** Provides focused agent guidance for Swift concurrency work. Use it to give coding agents project-relevant rules around isolation, Sendable boundaries, and async tests before they propose or edit concurrent Swift code.
- [Core Data](https://github.com/AvdLee/Core-Data-Agent-Skill) — Fatbobman’s Swift Weekly · Issue 121 — Source repository · Topics: Core Data · Persistence & Synchronisation · Swift
  **Published:** `2026-02-02T12:03:11.621Z`
  **NeKI brief:** Provides focused agent guidance for Core Data tasks. Use it to constrain an agent around contexts, threading, migrations, and persistence boundaries before it modifies an existing Core Data stack.
- [How SwiftData Represents AttributedString in Core Data Storage](https://medium.com/@djalex566/how-swiftdata-represents-attributedstring-in-core-data-storage-69036a4f166a) — SwiftLee Weekly · Issue 299 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `2025-11-25T15:16:48.000Z`
  **NeKI brief:** Explains How SwiftData Represents AttributedString in Core Data Storage, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [GitHub repository](https://github.com/AvdLee/CoreDataBestPractices) — SwiftLee Weekly · Issue 282 — Source repository · Topics: Core Data · Developer Tools · Persistence & Synchronisation
  **Published:** `2025-07-29T14:14:45.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for GitHub repository. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [GRDB](https://github.com/groue/GRDB.swift) — Fatbobman’s Swift Weekly · Issue 81 — Source repository · Topics: Core Data · Swift · SwiftData
  **Published:** `2025-04-28T00:00:42.290Z`
  **NeKI brief:** GRDB.swift is a SQLite toolkit offering query interfaces, migrations, observations, and record mapping. Use it when an app needs transparent relational persistence and reactive database changes without SwiftData's deployment and sync assumptions.
- [DataScout](https://data-scout.pages.dev/) — iOS Dev Tools · iOS Dev Tools: AppsMan, ErrorKit, DataScout — Article · Topics: Core Data · Cross-Platform & Web · Persistence & Synchronisation
  **Published:** `2025-04-24T13:08:49.536Z`
  **NeKI brief:** Data Scout is a data-exploration project presented as a developer product. Inspect its concrete workflow when comparing small utility apps, data presentation choices, and the cost of maintaining a focused independent product.
- [Mastering Data Tracking and Notifications in Core Data and SwiftData](https://itnext.io/mastering-data-tracking-and-notifications-in-core-data-and-swiftdata-a21921ebfa9d?source=rss-b8c3000741------2) — Those Who Swift · Issue 209 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `2025-04-09`
  **NeKI brief:** Examines Mastering Data Tracking and Notifications in Core Data and SwiftData, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Mogenerator](https://github.com/rentzsch/mogenerator) — iOS Dev Tools · iOS Dev Tools: Mogenerator, xcpretty, vscode-swift — Source repository · Topics: Core Data · Developer Tools · Objective-C & Cocoa
  **Published:** `2025-01-23T15:15:36.631Z`
  **NeKI brief:** mogenerator reads a Core Data model and generates separate machine and human subclasses for managed objects. Use it in legacy Core Data projects that need repeatable typed accessors while preserving hand-written behavior across model regeneration.
- [The weirdest Core Data crash I have seen](https://nemecek.be/blog/207/the-weirdest-core-data-crash-i-have-seen) — iOS Dev Weekly · Issue 678 — Article · Topics: Core Data · Persistence & Synchronisation
  **Published:** `13th September 2024`
  **NeKI brief:** Presents the weirdest core data crash i have seen for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Quick and Painless Persistency on iOS](https://www.swiftjectivec.com/stupid-and-quick-persistency-on-ios-with-swift) — iOS Dev Weekly · Issue 655 — Article · Topics: Core Data · Persistence & Synchronisation · Swift
  **Published:** `5th April 2024`
  **NeKI brief:** Presents quick and painless persistency on ios for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Screen vs View in SwiftUI](https://scottsmithdev.com/screen-vs-view-in-swiftui) — iOS Dev Weekly · Issue 647 — Article · Topics: Core Data · Swift · SwiftUI
  **Published:** `9th February 2024`
  **NeKI brief:** Contrasts screen-level composition with reusable SwiftUI views and gives naming and responsibility boundaries that help keep navigation and presentation code maintainable.
- [Integrating Haptic Feedback In SwiftUI Projects](https://serialcoder.dev/text-tutorials/swiftui/integrating-haptic-feedback-in-swiftui-projects) — Fatbobman’s Swift Weekly · Issue 12 — Tutorial · Topics: Swift · SwiftData · SwiftUI
  **Published:** `2023-12-25T22:00:09.856Z`
  **NeKI brief:** Shows how to trigger haptic feedback from SwiftUI interactions by bridging to the appropriate UIKit feedback generators. Follow it when adding tactile confirmation while keeping feedback timing, accessibility, and device capability checks explicit.
- [Deep Understanding of Observation - Principles, Back Porting, and Performance](https://onevcat.com/2023/08/observation-framework) — Fatbobman’s Swift Weekly · Issue 2 — Article · Topics: Core Data · Performance · Persistence & Synchronisation
  **Published:** `2023-10-16T22:30:04.937Z`
  **NeKI brief:** Explains Observation's principles, back-porting approaches, and performance implications. Follow it when migrating from older observation mechanisms and deciding where registrar-driven tracking improves update precision without obscuring model ownership.
- [SwiftDataKit](https://github.com/fatbobman/SwiftDataKit) — Fatbobman’s Swift Weekly · Issue 1 — Source repository · Topics: Core Data · Swift · SwiftData
  **Published:** `2023-10-09T14:00:25.178Z`
  **NeKI brief:** SwiftDataKit exposes lower-level Core Data access for SwiftData-backed models. Use it when a migration needs framework escape hatches, persistent-history operations, or APIs not surfaced by SwiftData alone.
- [Thinking in SwiftUI (2023)](https://www.objc.io/books/thinking-in-swiftui) — Fatbobman’s Swift Weekly · Issue 1 — Article · Topics: Core Data · Swift · SwiftUI
  **Published:** `2023-10-09T14:00:25.178Z`
  **NeKI brief:** Thinking in SwiftUI teaches the framework's state, identity, layout, and rendering mental models. Use it when a recurring SwiftUI bug indicates a conceptual mismatch rather than an isolated API issue.
- [@Model for CoreData](https://www.alwaysrightinstitute.com/managedmodels) — iOS Dev Weekly · Issue 629 — Article · Topics: Core Data · Persistence & Synchronisation · Swift
  **Published:** `29th September 2023`
  **NeKI brief:** Presents @model for coredata for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Unlocking Advanced Core Data Features in SwiftData](https://itnext.io/swiftdatakit-unleashing-advanced-core-data-features-in-swiftdata-3fcd5f443c99) — iOS Dev Weekly · Issue 626 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `8th September 2023`
  **NeKI brief:** Presents unlocking advanced core data features in swiftdata for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [The Ultimate Guide to Building SwiftData Applications](https://azamsharp.com/2023/07/04/the-ultimate-swift-data-guide.html) — SwiftUI Weekly · SwiftUI Weekly - Issue #151 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `2023-07-17T21:13:35.306Z`
  **NeKI brief:** Provides a broad SwiftData walkthrough covering model declaration, persistence, and cloud-sync-oriented concepts introduced at WWDC 2023. Useful for mapping Core Data requirements to SwiftData before committing to a migration or new model layer.
- [What I Learned Writing My Own CloudKit Syncing Library](https://ryanashcraft.com/what-i-learned-writing-my-own-cloudkit-sync-library) — iOS Dev Weekly · Issue 605 — Article · Topics: Core Data · Persistence & Synchronisation
  **Published:** `14th April 2023`
  **NeKI brief:** Shares lessons from building an open-source CloudKit synchronization library, including the practical complexity hidden behind sync-enabled apps. Follow it when comparing a custom sync layer with direct CloudKit use and identifying the design decisions the abstraction must own.
- [Clash of the Optionals](https://atomicbird.com/blog/clash-of-the-optionals) — iOS Dev Weekly · Issue 543 — Article · Topics: Core Data · Persistence & Synchronisation · Swift
  **Published:** `28th January 2022`
  **NeKI brief:** Explores Clash of the Optionals, focusing on the article discusses heard you like optionals, so i put an optional in your optional. Follow it to assess the approach, its trade-offs, and where it fits in a current Swift or Apple-platform project.
- [follow up post from Jesse Squires](https://www.jessesquires.com/blog/2022/01/26/core-data-optionals) — iOS Dev Weekly · Issue 543 — Article · Topics: Core Data · Persistence & Synchronisation · Swift
  **Published:** `28th January 2022`
  **NeKI brief:** Explores follow up post from Jesse Squires, focusing on the article discusses heard you like optionals, so i put an optional in your optional. Follow it to assess the approach, its trade-offs, and where it fits in a current Swift or Apple-platform project.
- [Core Data and SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2RhdmVkZWxvbmcuY29tL2Jsb2cvMjAyMS8wNC8wMy9jb3JlLWRhdGEtYW5kLXN3aWZ0dWkvP3V0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiNDc4NmJhYzAtODVlZi00ZDNlLTg4YTgtMGRmOWNmOWRkOWI5IiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6ImVmYmMxZmZhLWQ1M2UtNGIzNC04N2M2LTkyNDE2MjMwZWE2ZSIsImlhdCI6MTY3NDA2MjY3OC4yMjMsImlzcyI6Im9yY2hpZCJ9.EbooE-IrTlRQIDyUJlXQ2lH3GHe2qC85Z_zpQIXJqZI) — SwiftUI Weekly · SwiftUI Weekly - Issue #53 — Article · Topics: Core Data · Swift · SwiftUI
  **Published:** `2021-04-05T15:38:12.000Z`
  **NeKI brief:** Connects Core Data with SwiftUI state updates. Use it when fetched objects, context changes, and view identity need coordination in a persistence-backed interface.
- [How to Set Up Core Data and CloudKit When You Haven’t the Faintest Clue What You’re Doing](https://beckyhansmeyer.com/2021/03/30/how-to-set-up-core-data-cloudkit-and-swiftui-when-you-havent-the-faintest-clue-what-youre-doing) — iOS Dev Weekly · Issue 501 — Article · Topics: Core Data · Persistence & Synchronisation · Testing
  **Published:** `2nd April 2021`
  **NeKI brief:** Explores How to Set Up Core Data and CloudKit When You Haven’t the Faintest Clue What You’re Doing, focusing on what a candid blog post title from. Follow it to assess trade-offs before applying it in a current Swift or Apple-platform project.
- [Quick guide to using Core Data with SwiftUI](https://tanaschita.com/20210320-using-core-data-with-swiftui) — iOS Dev Weekly · Issue 500 — Article · Topics: Persistence & Synchronisation · Swift · SwiftUI
  **Published:** `26th March 2021`
  **NeKI brief:** Examines Quick guide to using Core Data with SwiftUI, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Core Store](https://dimsumthinking.com/Blog/2021/03/04-CoreStore.html) — iOS Dev Weekly · Issue 497 — Article · Topics: Combine & Reactive Programming · Core Data · Persistence & Synchronisation
  **Published:** `5th March 2021`
  **NeKI brief:** Examines Core Store, focusing on core data works well with new technologies like swiftui and combine, but does it feel at home with them? it does not. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Build Complete Apple Watch Tasks App Clone in WatchOS, SwiftUI with CoreData](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyJnY9OVFxdzU5NXFkY0UiLCJwb3N0X2lkIjoiZjhkYzQzOWQtNjdhOS00N2IwLWI0NzEtOTE2YzY0MWZlN2FjIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6IjNmMDQyMTgxLWQ3NWUtNGE0ZC1hNmE5LWJjM2UwYjBlYTBkZiIsImlhdCI6MTY3NDA2MjY3OC44OTUsImlzcyI6Im9yY2hpZCJ9.WcabseSQh2BOGdp0_x6eltLYiVZeTSCbK1h_Kcxqhs4) — SwiftUI Weekly · SwiftUI Weekly - Issue #48 — Tutorial · Topics: Core Data · Swift · SwiftUI
  **Published:** `2021-03-01T13:49:29.000Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Profiling SwiftUI app using Instruments](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3N3aWZ0d2l0aG1hamlkLmNvbS8yMDIxLzAxLzIwL3Byb2ZpbGluZy1zd2lmdHVpLWFwcC11c2luZy1pbnN0cnVtZW50cy8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiJmNDMyNzc3Ny02M2Q2LTQ1MDQtOWVkMC1lYTgwYzM4ZmVlZDUiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiMjVjODkyZTUtYTM5OC00YWVmLWFkMWEtMzYzZTkzNWE1OGJhIiwiaWF0IjoxNjc0MDYyNjc5LjQ1OSwiaXNzIjoib3JjaGlkIn0.yFE0lXxlheNBniRXd2cVmx609ueoWFP89URqNlmr9lo) — SwiftUI Weekly · SwiftUI Weekly - Issue #43 — Article · Topics: Performance · Swift · SwiftUI
  **Published:** `2021-01-26T13:13:48.000Z`
  **NeKI brief:** Uses Instruments to profile SwiftUI performance. Use it when a view-update or rendering problem needs measured call stacks and allocation evidence instead of intuition about declarative UI cost.
- [Core Data by Tutorials](https://www.raywenderlich.com/books/core-data-by-tutorials) — iOS Dev Weekly · Issue 484 — Tutorial · Topics: Core Data · Observation & State Management · Persistence & Synchronisation
  **Published:** `27th November 2020`
  **NeKI brief:** Examines Core Data by Tutorials, offering practical guidance on data modeling and persistence trade-offs. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Propagating user-facing errors in Swift](https://swiftbysundell.com/articles/propagating-user-facing-errors-in-swift) — iOS Dev Weekly · Issue 456 — Tutorial · Topics: Core Data · Developer Community & Business · Swift
  **Published:** `15th May 2020`
  **NeKI brief:** Examines Propagating user-facing errors in Swift, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Using CoreData with SwiftUI](https://augmentedcode.io/2020/01/19/using-coredata-with-swiftui) — iOS Dev Weekly · Issue 441 — Article · Topics: Core Data · Persistence & Synchronisation · Swift
  **Published:** `31st January 2020`
  **NeKI brief:** Walks through connecting Core Data fetches and managed-object context to SwiftUI views. Use it to inspect ownership and update-flow choices, then adapt the pattern to the app’s concurrency and persistence model.
- [AQUI](https://github.com/AlanQuatermain/AQUI) — iOS Dev Weekly · Issue 432 — Source repository · Topics: Core Data · Persistence & Synchronisation · Swift
  **Published:** `29th November 2019`
  **NeKI brief:** Examines AQUI, focusing on jim dovey on how to make swiftui and core data play nicely together using his aqui library. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [LLVS project](https://github.com/mentalfaculty/LLVS) — iOS Dev Weekly · Issue 424 — Source repository · Topics: Apple Platform Ecosystem · Combine & Reactive Programming · Persistence & Synchronisation
  **Published:** `4th October 2019`
  **NeKI brief:** Examines LLVS project, focusing on one topic that has been talked about consistently since wwdc is how core data (or any data persistence framework) will be…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [The Curious Case of the Core Data Crash](https://blog.iconfactory.com/2019/08/the-curious-case-of-the-core-data-crash) — iOS Dev Weekly · Issue 419 — Article · Topics: Concurrency · Core Data · Developer Tools
  **Published:** `30th August 2019`
  **NeKI brief:** Examines The Curious Case of the Core Data Crash, offering practical guidance on data modeling and persistence trade-offs. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Getting Started With NSPersistentCloudKitContainer](https://www.andrewcbancroft.com/blog/ios-development/data-persistence/getting-started-with-nspersistentcloudkitcontainer) — iOS Dev Weekly · Issue 416 — Article · Topics: Core Data · Persistence & Synchronisation · Personal Essays
  **Published:** `9th August 2019`
  **NeKI brief:** Examines Getting Started With NSPersistentCloudKitContainer, offering practical guidance on data modeling and persistence trade-offs. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [check out](https://github.com/wibosco/CoreDataMigrationRevised-Example) — iOS Dev Weekly · Issue 390 — Source repository · Topics: Core Data · Developer Tools · Persistence & Synchronisation
  **Published:** `8th February 2019`
  **NeKI brief:** Examines check out, focusing on comprehensive and well written look at the migration process for core data by william boles. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [The Laws of Core Data](http://davedelong.com/blog/2018/05/09/the-laws-of-core-data) — iOS Dev Weekly · Issue 351 — Article · Topics: Core Data · Objective-C & Cocoa · Persistence & Synchronisation
  **Published:** `11th May 2018`
  **NeKI brief:** Core Data laws frame managed objects as context-bound lifecycles rather than ordinary models, clarifying why thread confinement and save ordering are correctness constraints.
- [follow up](http://www.cimgf.com/2018/05/10/response-the-laws-of-core-data) — iOS Dev Weekly · Issue 351 — Article · Topics: Core Data · Objective-C & Cocoa · Persistence & Synchronisation
  **Published:** `11th May 2018`
  **NeKI brief:** Responds to Core Data design rules with practical clarification about model boundaries, persistence behavior, and application architecture. Use it to compare competing guidance and identify trade-offs, then verify assumptions against current Core Data documentation and project constraints.
- [Dealing with Dates](http://martiancraft.com/blog/2018/05/dealing-with-dates) — iOS Dev Weekly · Issue 351 — Article · Topics: Core Data · Persistence & Synchronisation
  **Published:** `11th May 2018`
  **NeKI brief:** Date bugs arise when an instant, calendar date, locale, and time zone are conflated. The guide uses Foundation's calendar and formatter APIs to make those boundaries explicit, a useful diagnostic checklist for scheduling and display failures.
- [mogenerator and Swift 3](http://rentzsch.tumblr.com/post/151300114355/mogenerator-131) — iOS Dev Weekly · Issue 271 — Article · Topics: Core Data · Persistence & Synchronisation · Swift
  **Published:** `7th October 2016`
  **NeKI brief:** Explores mogenerator and Swift 3 in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [reference implementation](https://github.com/tomkowz/NetworkLayerExample) — iOS Dev Weekly · Issue 263 — Source repository · Topics: Architecture · Core Data · Developer Tools
  **Published:** `11th August 2016`
  **NeKI brief:** Examines reference implementation, focusing on tomasz szulc on building network architecture that isn’t dependent on any third party libraries, or any apple provided…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Using a Core Data Model in Swift Playgrounds](https://www.andrewcbancroft.com/2016/07/10/using-a-core-data-model-in-swift-playgrounds) — iOS Dev Weekly · Issue 259 — Article · Topics: Core Data · Persistence & Synchronisation · Swift
  **Published:** `15th July 2016`
  **NeKI brief:** Explores Using a Core Data Model in Swift Playgrounds in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [New Swift, Core Data and Cocoa Books](http://useyourloaf.com/blog/new-swift-core-data-and-cocoa-books) — iOS Dev Weekly · Issue 251 — Article · Topics: Core Data · Objective-C & Cocoa · Swift
  **Published:** `20th May 2016`
  **NeKI brief:** Collects book recommendations around Swift, Core Data, and Cocoa as a learning route. Treat editions as historical context and cross-check API guidance against current Apple documentation.
- [Xcode Swift Snippets](https://github.com/Abizern/xcode-snippets) — iOS Dev Weekly · Issue 220 — Source repository · Topics: Core Data · Developer Tools · Xcode
  **Published:** `16th October 2015`
  **NeKI brief:** Provides the Xcode Swift Snippets source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Core Data](http://www.objc.io/books/core-data) — iOS Dev Weekly · Issue 209 — Article · Topics: Core Data · Persistence & Synchronisation · Swift
  **Published:** `31st July 2015`
  **NeKI brief:** Explains Core Data with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Advanced Swift](http://www.objc.io/books/advanced-swift) — iOS Dev Weekly · Issue 209 — Article · Topics: Core Data · Persistence & Synchronisation · Swift
  **Published:** `31st July 2015`
  **NeKI brief:** Points to objc.io's Advanced Swift book as a structured treatment of modern language features and design techniques. Use it for historical Swift study and cross-check syntax, ownership, and standard-library guidance against the current Swift toolchain.
- [Cache Me If You Can](http://khanlou.com/2015/07/cache-me-if-you-can) — iOS Dev Weekly · Issue 208 — Article · Topics: Core Data · Persistence & Synchronisation
  **Published:** `24th July 2015`
  **NeKI brief:** Explains Cache Me If You Can with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Sync](https://github.com/hyperoslo/Sync) — iOS Dev Weekly · Issue 193 — Source repository · Topics: Core Data · Developer Tools · Persistence & Synchronisation
  **Published:** `10th April 2015`
  **NeKI brief:** Provides the Sync source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [My Core Data Stack](http://martiancraft.com/blog/2015/03/core-data-stack) — iOS Dev Weekly · Issue 192 — Article · Topics: Core Data · Persistence & Synchronisation · Xcode
  **Published:** `3rd April 2015`
  **NeKI brief:** A production-oriented Core Data stack walkthrough covering setup, contexts, and persistence boundaries. Use it to compare lifecycle and concurrency choices before adopting a shared storage layer.
- [Treehouse: Code Better iOS Apps](http://teamtreehouse.com/join/ios-development?cid=2672) — iOS Dev Weekly · Issue 159 — Tutorial · Topics: Core Data · Networking · Persistence & Synchronisation
  **Published:** `15th August 2014`
  **NeKI brief:** Explains Treehouse Code Better iOS Apps with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [QueryKit](https://github.com/kylef/QueryKit) — iOS Dev Weekly · Issue 153 — Source repository · Topics: Core Data · Developer Tools · Swift
  **Published:** `4th July 2014`
  **NeKI brief:** Provides the QueryKit source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [The Core Data stack in Swift](http://www.cimgf.com/2014/06/08/the-core-data-stack-in-swift) — iOS Dev Weekly · Issue 152 — Article · Topics: Core Data · Objective-C & Cocoa · Swift
  **Published:** `27th June 2014`
  **NeKI brief:** Explains The Core Data stack in Swift with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [CloudKit: Moves like Azure](http://www.atomicbird.com/blog/cloudkit-moves-like-azure) — iOS Dev Weekly · Issue 151 — Article · Topics: Core Data · Persistence & Synchronisation
  **Published:** `20th June 2014`
  **NeKI brief:** Explains CloudKit Moves like Azure with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [ICACloud: iCloud Simplified](http://mentalfaculty.tumblr.com/post/73709086974/introducing-icacloud-icloud-simplified) — iOS Dev Weekly · Issue 130 — Article · Topics: Core Data · Persistence & Synchronisation
  **Published:** `24th January 2014`
  **NeKI brief:** Explains ICACloud iCloud Simplified with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Apportable](http://www.youtube.com/watch?v=dSkhtd6L8RM) — iOS Dev Weekly · Issue 117 — Video · Topics: App Services & Extensions · Core Data · Cross-Platform & Web
  **Published:** `25th October 2013`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Ensembles](http://mentalfaculty.tumblr.com/post/62909673342/introducing-ensembles-core-data-sync-the-way-it-should) — iOS Dev Weekly · Issue 114 — Article · Topics: Core Data · Persistence & Synchronisation
  **Published:** `4th October 2013`
  **NeKI brief:** Explains Ensembles with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [FCModel](https://github.com/marcoarment/FCModel) — iOS Dev Weekly · Issue 112 — Source repository · Topics: Core Data · Objective-C & Cocoa · Persistence & Synchronisation
  **Published:** `20th September 2013`
  **NeKI brief:** Provides the FCModel source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [ParcelKit](https://github.com/overcommitted/ParcelKit) — iOS Dev Weekly · Issue 104 — Source repository · Topics: Core Data · Objective-C & Cocoa · Testing
  **Published:** `26th July 2013`
  **NeKI brief:** Provides the ParcelKit source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Dropbox Datastore](http://www.atomicbird.com/blog/dropbox-datastore) — iOS Dev Weekly · Issue 102 — Article · Topics: Core Data · Persistence & Synchronisation
  **Published:** `12th July 2013`
  **NeKI brief:** Explains Dropbox Datastore with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Clear in the iCloud](http://blog.helftone.com/clear-in-the-icloud) — iOS Dev Weekly · Issue 96 — Article · Topics: Core Data · Persistence & Synchronisation
  **Published:** `31st May 2013`
  **NeKI brief:** Explains Clear in the iCloud with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Does Core Data Sync Quack?](http://mentalfaculty.tumblr.com/post/51143164677/does-core-data-sync-quack) — iOS Dev Weekly · Issue 95 — Article · Topics: Core Data · Persistence & Synchronisation
  **Published:** `24th May 2013`
  **NeKI brief:** Explains Does Core Data Sync Quack with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [UbiquityStoreManager](http://lhunath.github.io/UbiquityStoreManager) — iOS Dev Weekly · Issue 94 — Article · Topics: Core Data · Developer Tools · Persistence & Synchronisation
  **Published:** `17th May 2013`
  **NeKI brief:** Explains UbiquityStoreManager with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [momdec](http://www.atomicbird.com/blog/introducing-momdec) — iOS Dev Weekly · Issue 90 — Article · Topics: Core Data · Persistence & Synchronisation
  **Published:** `19th April 2013`
  **NeKI brief:** Explains momdec with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [The Gathering Storm: Our Travails with iCloud Sync](http://rms2.tumblr.com/post/46505165521/the-gathering-storm-our-travails-with-icloud-sync) — iOS Dev Weekly · Issue 87 — Article · Topics: Apple Platform Ecosystem · Core Data · Persistence & Synchronisation
  **Published:** `29th March 2013`
  **NeKI brief:** Explains The Gathering Storm Our Travails with iCloud Sync with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [iCloud and That Sinking Feeling](http://nicemohawk.com/blog/2013/02/icloud-and-that-sinking-feeling) — iOS Dev Weekly · Issue 83 — Article · Topics: Core Data · Persistence & Synchronisation
  **Published:** `1st March 2013`
  **NeKI brief:** Explains iCloud and That Sinking Feeling with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [NSIncrementalStore – The future of web services in iOS / Mac OS X](http://sealedabstract.com/code/nsincrementalstore-the-future-of-web-services-in-ios-mac-os-x) — iOS Dev Weekly · Issue 50 — Article · Topics: Core Data · Persistence & Synchronisation
  **Published:** `13th July 2012`
  **NeKI brief:** Explains NSIncrementalStore The future of web services in iOS Mac OS X with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a.
- [Debugging Core Data Objects](http://furbo.org/2012/06/28/debugging-core-data-objects) — iOS Dev Weekly · Issue 48 — Article · Topics: Core Data · Developer Tools · Persistence & Synchronisation
  **Published:** `29th June 2012`
  **NeKI brief:** Explains Debugging Core Data Objects with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Unit Testing with Core Data](http://www.cimgf.com/2012/05/15/unit-testing-with-core-data) — iOS Dev Weekly · Issue 42 — Article · Topics: Core Data · Persistence & Synchronisation · Testing
  **Published:** `18th May 2012`
  **NeKI brief:** Explains Unit Testing with Core Data with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Under the Sheets with iCloud and Core Data: How it Works](http://mentalfaculty.tumblr.com/post/23231176783/under-the-sheets-with-icloud-and-core-data-how-it) — iOS Dev Weekly · Issue 42 — Article · Topics: Core Data · Persistence & Synchronisation
  **Published:** `18th May 2012`
  **NeKI brief:** Explains Under the Sheets with iCloud and Core Data How it Works with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a.
- [Core Data Queries Using Expressions](http://useyourloaf.com/blog/2012/1/19/core-data-queries-using-expressions.html) — iOS Dev Weekly · Issue 26 — Article · Topics: Core Data · Cross-Platform & Web · Persistence & Synchronisation
  **Published:** `27th January 2012`
  **NeKI brief:** Explains Core Data Queries Using Expressions with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [MagicalRecord](https://github.com/magicalpanda/MagicalRecord) — iOS Dev Weekly · Issue 18 — Source repository · Topics: Core Data · Developer Tools · Persistence & Synchronisation
  **Published:** `2nd December 2011`
  **NeKI brief:** Provides the MagicalRecord source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Transient Entities and Core Data](http://www.cimgf.com/2011/08/08/transient-entities-and-core-data) — iOS Dev Weekly · Issue 2 — Article · Topics: Core Data · Objective-C & Cocoa · Persistence & Synchronisation
  **Published:** `12th August 2011`
  **NeKI brief:** Explains Transient Entities and Core Data with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
