# Persistence & Synchronisation

Third-party reading leads collected from NeKI sources. The links may be useful perspectives, but are not vetted recommendations or authoritative API guidance. NeKI publishes routing metadata, not the linked articles' text.

**Scope:** Local storage, CloudKit, databases, caching, keychain use, and synchronisation.

- Last collected: `2026-07-22T21:56:49Z`
- Indexed links shown: **566**

## Direct-source reading

- [CloudKit JS Tutorial for iOS | Kodeco](https://www.kodeco.com/997-cloudkit-js-tutorial-for-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** A hands-on bridge between an iOS CloudKit container and a browser client, showing where CloudKit JS fits when the same records must be exposed on the web.
- [Core Data with SwiftUI Tutorial: Getting Started | Kodeco](https://www.kodeco.com/9335365-core-data-with-swiftui-tutorial-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The starter app wires Core Data into SwiftUI through @State, @Environment, and @FetchRequest, illustrating the view-to-persistence data flow in the older SwiftUI model API.
- [Keychain Services API Tutorial for Passwords in Swift | Kodeco](https://www.kodeco.com/9240-keychain-services-api-tutorial-for-passwords-in-swift) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This guide wraps the C-based Keychain Services API for password storage, making the security and query steps explicit instead of treating credentials as ordinary app data.
- [Realm Tutorial: Getting Started | Kodeco](https://www.kodeco.com/9220-realm-tutorial-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** A small wildlife app introduces Realm's object model and persistence workflow, providing a concrete contrast to Core Data's managed-object approach.
- [Docker on macOS: Getting Started | Kodeco](https://www.kodeco.com/9159-docker-on-macos-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The Docker walkthrough covers container lifecycle, published ports, volumes, and a split database/web setup, giving a practical mental model for networking and filesystem boundaries on macOS.
- [Using Fluent and Persisting Models in Vapor | Kodeco](https://www.kodeco.com/890936-using-fluent-and-persisting-models-in-vapor) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Fluent's ORM is used to map server-side Swift models to a database, with the article emphasizing persistence without tying application code to one engine.
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
- [Parse Server Tutorial with iOS | Kodeco](https://www.kodeco.com/717-parse-server-tutorial-with-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Sets up Parse Server with its database and dashboard, configures an iOS client, deploys the service, and adds push notifications. Useful as an end-to-end example of the operational pieces hidden behind a backend-as-a-service style mobile data layer.
- [Beginning Core Data | Kodeco](https://www.kodeco.com/7104-beginning-core-data) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This Core Data series covers model relationships, updates and fetch predicates as a complete persistence workflow. Its routing value is in connecting schema design to query behavior, rather than treating the managed object context as a generic database handle.
- [Realm and Accessibility – Podcast S08 E04 | Kodeco](https://www.kodeco.com/6990-realm-and-accessibility-podcast-s08-e04) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** A Kodeco podcast discussion that pairs Realm experience with a case for adopting stronger accessibility practices. Use it for practitioner perspective and motivation around accessibility, not as a step-by-step Realm or VoiceOver implementation guide.
- [NSCoding Tutorial for iOS: How to Permanently Save App Data | Kodeco](https://www.kodeco.com/6733-nscoding-tutorial-for-ios-how-to-permanently-save-app-data) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Implements NSCoding and NSSecureCoding for disk persistence, including object initialization, deletion, and image storage. Useful for understanding archive-based persistence boundaries in legacy code before deciding whether a modern Codable or database migration is warranted.
- [FileManager Class Tutorial for macOS: Getting Started with the File System | Kodeco](https://www.kodeco.com/666-filemanager-class-tutorial-for-macos-getting-started-with-the-file-system) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This macOS FileManager tutorial covers locating, creating and traversing files and folders. It remains a practical reference for sandbox-aware tooling, where URL-based APIs and explicit error handling matter more than string path manipulation.
- [SQLite With Swift Tutorial: Getting Started | Kodeco](https://www.kodeco.com/6620276-sqlite-with-swift-tutorial-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Creates SQLite tables and performs insert, update, delete, and query operations from Swift. Follow it when a small relational store is appropriate and you need to keep SQL schema and transaction behavior explicit.
- [RWDevCon 2017 Vault Free Tutorial #3: Server Side Swift with Perfect | Kodeco](https://www.kodeco.com/646-rwdevcon-2017-vault-free-tutorial-3-server-side-swift-with-perfect) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Builds an early server-side Swift web application with templating, persistence, and authentication. Useful historical context for separating web-facing concerns from the iOS client and its data model.
- [Updated Course: Beginning Realm on iOS | Kodeco](https://www.kodeco.com/592-updated-course-beginning-realm-on-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Introduces Realm persistence and object models in an iOS app. Use it to understand the framework’s live-object behavior and how that differs from value snapshots or Core Data managed objects.
- [Updated Course: Intermediate Realm on iOS | Kodeco](https://www.kodeco.com/575-updated-course-intermediate-realm-on-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Updates an intermediate Realm course around model access and persistence workflows. Follow it when maintaining Realm-backed apps and evaluating how object lifetimes, queries, and migrations constrain application architecture.
- [Couchbase Tutorial for iOS: Getting Started | Kodeco](https://www.kodeco.com/5480-couchbase-tutorial-for-ios-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Couchbase and Sync Gateway are used to persist and synchronize a mobile data set. The article is useful for comparing local-first replication with CloudKit or Core Data, especially around conflict policy and server ownership.
- [Server Side Swift with Vapor: Parent-Child Relations | Kodeco](https://www.kodeco.com/5025-server-side-swift-with-vapor-parent-child-relations) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Models parent-child relationships in Vapor persistence. It is useful for designing nested resources and queries, while making deletion, loading, and ownership semantics explicit instead of relying on implicit object graphs.
- [Server Side Swift with Vapor: Configuring a Database | Kodeco](https://www.kodeco.com/5024-server-side-swift-with-vapor-configuring-a-database) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Connects a Vapor app to database backends such as MySQL, MongoDB, or PostgreSQL through explicit configuration steps. Use it to keep driver selection and credentials separate from model and request-handling code.
- [Server Side Swift With Vapor: Sibling Relations | Kodeco](https://www.kodeco.com/5009-server-side-swift-with-vapor-sibling-relations) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Demonstrates sibling relationships between Vapor models through a shared parent. Follow it when querying related records, checking schema keys, and preventing relationship logic from leaking into route handlers.
- [Getting Started with SwiftData in iOS 26 | Kodeco](https://www.kodeco.com/49976785-getting-started-with-swiftdata-in-ios-26) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The iOS 26 SwiftData starter introduces model types, containers and SwiftUI queries as one persistence flow. Follow it to assess how observation and schema choices shape a modern app, while checking migration and background-context needs beyond the sample.
- [Server Side Swift with Vapor: CRUD Database Options | Kodeco](https://www.kodeco.com/4996-server-side-swift-with-vapor-crud-database-options) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Implements CRUD operations with Vapor and compares database options behind those routes. Follow it when shaping a service API, because consistency, error mapping, and persistence capabilities influence the apparent simplicity of each endpoint.
- [Server Side Swift with Vapor: Persisting Models | Kodeco](https://www.kodeco.com/4960-server-side-swift-with-vapor-persisting-models) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Creates Vapor model objects that persist to a database, linking model definition with query and save operations. The article helps identify where persistence conventions belong before a server grows beyond a single resource.
- [CloudKit Tutorial: Getting Started | Kodeco](https://www.kodeco.com/4878052-cloudkit-tutorial-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** A concise CloudKit starter shows creating and querying records, then inspecting them in CloudKit Dashboard. It is valuable for validating the request-to-schema workflow before adding subscriptions, conflict handling or more elaborate synchronization logic.
- [Introducing Realm: Building Modern Swift Apps with Realm Database | Kodeco](https://www.kodeco.com/48-introducing-realm-building-modern-swift-apps-with-realm-database) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Defines Realm objects with dynamic properties and primary keys, reads and mutates persisted data, observes changes, and deletes records. Useful for understanding the live-object model behind Realm before comparing its update behavior with Core Data or immutable stores.
- [Database Migrations with Vapor | Kodeco](https://www.kodeco.com/4620455-database-migrations-with-vapor) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Vapor database migrations evolve a PostgreSQL schema through versioned changes. The workflow is useful for treating server data shape as deployable code, with ordering and rollback limits that differ from local app migrations.
- [Beginning CloudKit | Kodeco](https://www.kodeco.com/4247-beginning-cloudkit) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This CloudKit series treats iCloud as a backend, covering records, queries and the dashboard without a custom server. It helps evaluate schema and sync decisions early, particularly the boundary between public data and user-private stores.
- [Intermediate Realm on iOS | Kodeco](https://www.kodeco.com/4200-intermediate-realm-on-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Explores more advanced Realm persistence patterns in an iOS application. Useful for assessing how object queries, updates, and schema evolution affect a production data layer beyond introductory CRUD.
- [Beginning Realm on iOS | Kodeco](https://www.kodeco.com/4146-beginning-realm-on-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Realm’s object database is introduced through model definitions, queries and live updates. It is useful for comparing a mobile-first persistence layer with Core Data, especially where thread confinement and migration strategy affect repository design.
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
- [Beginning Realm on iOS | Kodeco](https://www.kodeco.com/3479-beginning-realm-on-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Realm persistence is introduced through models, queries and live updates. Follow it to compare thread-confined objects and migrations with Core Data, especially when deciding how a repository exposes observable storage.
- [Beginning Core Data | Kodeco](https://www.kodeco.com/3444-beginning-core-data) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Introduces Core Data entities, managed objects, contexts, and persistence. Useful for tracing how a UI change becomes a durable object-graph mutation.
- [Introduction to CloudKit | Kodeco](https://www.kodeco.com/3413-introduction-to-cloudkit) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Introduces CloudKit's container and record-oriented data model for iOS. Useful for evaluating how app data, user identity, and server-managed storage fit together before implementing sync behavior.
- [Realm With SwiftUI Tutorial: Getting Started | Kodeco](https://www.kodeco.com/32960966-realm-with-swiftui-tutorial-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Defines Realm object relationships, observes queries through @ObservedResults, performs mutations, and migrates a schema change. Useful for evaluating how a live object database feeds SwiftUI and what model evolution work persists beyond simple CRUD.
- [Intermediate Realm on iOS | Kodeco](https://www.kodeco.com/3245-intermediate-realm-on-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Covers intermediate Realm use in an iOS codebase. Useful for revisiting how live queries, object updates, and schema changes influence architecture once persistence is no longer limited to a single simple screen.
- [Core Data: Beyond the Basics | Kodeco](https://www.kodeco.com/32317039-core-data-beyond-the-basics) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Core Data’s fetch, sort and filter behavior is explored beyond model creation, including persistent-store access patterns. It is useful when tuning predicates and fetch requests instead of moving all filtering into application memory.
- [Beginning Core Data | Kodeco](https://www.kodeco.com/3200-beginning-core-data) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Covers Core Data setup, fetches, and saves in an introductory workflow. Useful for separating model persistence from table or form presentation responsibilities.
- [SQLite Tutorial for iOS: Creating and Scripting | Kodeco](https://www.kodeco.com/3137-sqlite-tutorial-for-ios-creating-and-scripting) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Creates and scripts a SQLite schema for an iOS app. Follow it when schema setup and repeatable database initialization need to be explicit rather than hidden inside ad hoc startup code.
- [SQLite Tutorial for iOS: Making Our App | Kodeco](https://www.kodeco.com/3136-sqlite-tutorial-for-ios-making-our-app) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Applies SQLite to an iOS app, connecting schema operations with a usable feature. The article is valuable for seeing how query results, persistence errors, and UI updates must be coordinated rather than treated as isolated SQL calls.
- [Core Data Tutorial for iOS: How To Use NSFetchedResultsController | Kodeco](https://www.kodeco.com/3134-core-data-tutorial-for-ios-how-to-use-nsfetchedresultscontroller) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Uses NSFetchedResultsController to bridge Core Data changes into a table view. Useful for preserving incremental UI updates without manually refetching and rebuilding an entire list after every change.
- [NSCoding Tutorial for iOS: How To Save Your App Data | Kodeco](https://www.kodeco.com/3111-nscoding-tutorial-for-ios-how-to-save-your-app-data) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Archives a model with NSCoding, restores it from disk, and persists associated images. Useful for maintaining an older UIKit codebase where file-backed object archives still define its data format and must be understood before migration.
- [NSIncrementalStore Tutorial for iOS: Getting Started | Kodeco](https://www.kodeco.com/311-nsincrementalstore-tutorial-for-ios-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Implements an NSIncrementalStore that maps Core Data fetches and saves onto a web service, including IDs, caching, relationships, and optimistic conflicts. Useful for understanding why remote-backed persistence requires careful identity and consistency design.
- [How To Write A Simple PHP/MySQL Web Service for an iOS App | Kodeco](https://www.kodeco.com/3077-how-to-write-a-simple-php-mysql-web-service-for-an-ios-app) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This legacy web-service tutorial connects an iOS client to a PHP/MySQL backend. Its routing value is architectural: isolate transport and serialization from UI, and treat server validation as authoritative.
- [Sharing Core Data With CloudKit in SwiftUI | Kodeco](https://www.kodeco.com/29934862-sharing-core-data-with-cloudkit-in-swiftui) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Explains synchronizing a Core Data store with CloudKit from a SwiftUI app. Follow it when evaluating Apple-backed data sharing, because container configuration, model compatibility, and offline synchronization remain separate operational concerns.
- [Firebase Real-Time Database Tutorial for iOS | Kodeco](https://www.kodeco.com/29394678-firebase-real-time-database-tutorial-for-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Firebase Realtime Database is used from iOS to observe and mutate synchronized JSON data. It is useful for weighing low-latency remote state against schema discipline, offline behavior and the security rules that protect client-writable paths.
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
- [How To Choose the Best Backend Provider for your iOS App: Parse vs Stackmob vs. Appcelerator Cloud and More! | Kodeco](https://www.kodeco.com/2819-how-to-choose-the-best-backend-provider-for-your-ios-app-parse-vs-stackmob-vs-appcelerator-cloud-and-more) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This backend comparison evaluates hosted providers through capabilities and operational trade-offs. Its durable value is the decision checklist: storage, auth, vendor lock-in and migration effort matter more than a short integration demo.
- [How to Use Cocoa Bindings and Core Data in a Mac App | Kodeco](https://www.kodeco.com/2814-how-to-use-cocoa-bindings-and-core-data-in-a-mac-app) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Cocoa Bindings connect Core Data objects to AppKit controls with less glue code. It is useful legacy material for understanding binding keys and context ownership, while modern SwiftUI may replace the presentation layer.
- [Core Data: Fundamentals | Kodeco](https://www.kodeco.com/27468235-core-data-fundamentals) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Core Data fundamentals connect entities, contexts and persistent stores in a complete model. The guide is useful for separating schema, lifecycle and query concerns before layering SwiftUI observation or CloudKit synchronization.
- [Dynamic Core Data with SwiftUI Tutorial for iOS | Kodeco](https://www.kodeco.com/27201015-dynamic-core-data-with-swiftui-tutorial-for-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Dynamic Core Data content is surfaced in SwiftUI while the model drives changing sections. The tutorial is useful for examining fetch-driven identity and view updates, especially where deletes or inserts can invalidate assumptions about row order.
- [CloudKit | Kodeco](https://www.kodeco.com/27184225-cloudkit) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This CloudKit overview frames records, containers and dashboard configuration as a backend workflow. It is useful for deciding which data belongs to public, private or shared databases before implementing sync and access controls.
- [Set Up Core Spotlight with Core Data: Getting Started | Kodeco](https://www.kodeco.com/26871651-set-up-core-spotlight-with-core-data-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Indexes Core Data records in Core Spotlight so users can find app content through system search. Follow it when mapping persistent identity, searchable metadata, and reindexing behavior across updates.
- [Developing and Testing Server-Side Swift with Docker and Vapor | Kodeco](https://www.kodeco.com/26322368-developing-and-testing-server-side-swift-with-docker-and-vapor) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Docker and Vapor are combined with tests to make server-side Swift development reproducible. The article is useful for separating containerized dependencies from application assertions, so local success does not hide deployment-specific failures.
- [Realm Database on Android: Getting Started | Kodeco](https://www.kodeco.com/25768145-realm-database-on-android-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Defines a Realm schema, queries and sorts records, models relationships, migrates data, and compares Realm with Room. Useful as a cross-platform persistence comparison when shared product behavior must account for differing mobile database idioms.
- [Database Migrations With Vapor | Kodeco](https://www.kodeco.com/23848990-database-migrations-with-vapor) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This Vapor migration walkthrough applies versioned schema changes to a server database. Its value is operational: migrations must be ordered, repeatable and deployed with the code that expects the new shape.
- [Video Tutorial: Saving Data in iOS Part 2: Using The Filemanager | Kodeco](https://www.kodeco.com/2378-video-tutorial-saving-data-in-ios-part-2-using-the-filemanager) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Explains writing and organizing files with FileManager in an iOS app. Follow it when choosing document, caches, and support directories, because location and backup policy are part of persistence correctness.
- [How To Secure iOS User Data: The Keychain and Biometrics — Face ID or Touch ID | Kodeco](https://www.kodeco.com/236-how-to-secure-ios-user-data-the-keychain-and-biometrics-face-id-or-touch-id) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Secures user data with Keychain storage and biometric authentication. Useful for separating durable secret storage from an authentication gate that merely permits access.
- [Video Tutorial: Saving Data in iOS Part 5: App Settings and User Defaults | Kodeco](https://www.kodeco.com/2351-video-tutorial-saving-data-in-ios-part-5-app-settings-and-user-defaults) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Explains app settings and UserDefaults for small preference values. Follow it to separate lightweight configuration from durable user documents and avoid placing sensitive or queryable data in defaults.
- [Video Tutorial: Saving Data in iOS Part 8: Using SQLite | Kodeco](https://www.kodeco.com/2330-video-tutorial-saving-data-in-ios-part-8-using-sqlite) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Uses SQLite directly in an iOS data-storage series. Follow it when evaluating schema, SQL queries, and transaction boundaries, especially for legacy code that predates higher-level persistence wrappers.
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
- [Beginning Firebase for iOS | Kodeco](https://www.kodeco.com/22029618-beginning-firebase-for-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Beginning Firebase for iOS surveys service integration and configuration in an app target. Its routing value is in identifying SDK initialization and environment boundaries before adding analytics, database or authentication features.
- [Server-Side Swift with Vapor | Kodeco](https://www.kodeco.com/21451628-server-side-swift-with-vapor) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Introduces server-side Swift with Vapor and the framework’s application model. Follow it for historical orientation around routing, middleware, and deployment before comparing those concepts with current Vapor releases.
- [Two Books Updated for Swift 4.2 and iOS 12: Realm and RxSwift! | Kodeco](https://www.kodeco.com/2089042-two-books-updated-for-swift-4-2-and-ios-12-realm-and-rxswift) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Announces updates to Realm and RxSwift books for Swift 4.2 and iOS 12. It is useful historical routing context when version-specific persistence or reactive examples must be matched to an older codebase.
- [Video Tutorial: iOS App Extensions Part 7: Today Extensions: Core Data | Kodeco](https://www.kodeco.com/2076-video-tutorial-ios-app-extensions-part-7-today-extensions-core-data) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Shares a Core Data store between an iOS app and a Today extension. The key decision is coordinating an app-group file and context lifecycle so both processes see consistent data without unsafe concurrent writes.
- [Using Core Data in iOS with RubyMotion | Kodeco](https://www.kodeco.com/1764-using-core-data-in-ios-with-rubymotion) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Explores Core Data access from RubyMotion-based iOS code. Use it as historical maintenance context for managed objects and contexts when a non-Swift application still shares Apple persistence concepts.
- [Using Fluent and Persisting Models in Vapor | Kodeco](https://www.kodeco.com/15249598-using-fluent-and-persisting-models-in-vapor) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Shows how Fluent maps Vapor model types onto interchangeable database drivers and persists records. Follow it when choosing an ORM boundary, especially where schema migrations and database-specific behavior must remain visible rather than hidden behind app code.
- [Modern, Efficient Core Data | Kodeco](https://www.kodeco.com/14958063-modern-efficient-core-data) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Combines batch inserts, persistent history tracking, query generations, transaction authors, history tokens, and derived attributes. Useful for designing Core Data synchronization that merges only relevant changes without flooding contexts with broad save notifications.
- [Realm Tutorial: Getting Started | Kodeco](https://www.kodeco.com/1464-realm-tutorial-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Creates Realm models, browses and queries records, applies predicates, updates objects, and organizes categories. Useful for learning the database's object-query workflow before committing to a persistence layer whose thread and migration behavior differs from Core Data.
- [Getting Started with Core Data and CloudKit | Kodeco](https://www.kodeco.com/13219461-getting-started-with-core-data-and-cloudkit) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** NSPersistentCloudKitContainer bridges a Core Data model to CloudKit, making schema and synchronization assumptions explicit. This guide is valuable before enabling sharing or conflict resolution, where local modeling choices become server-visible records.
- [Basic iOS Security: Keychain and Hashing | Kodeco](https://www.kodeco.com/129-basic-ios-security-keychain-and-hashing) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The security primer separates Keychain storage from one-way hashing and explains where each belongs. It is useful for reviewing credential handling, while remembering that passwords need a server-side password scheme rather than client-only hashing.
- [Getting Started with Cloud Firestore and SwiftUI | Kodeco](https://www.kodeco.com/11609977-getting-started-with-cloud-firestore-and-swiftui) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The sample persists SwiftUI app data in Firebase Cloud Firestore, showing the document-oriented write/read flow and its boundary outside Apple's native stores.
- [How To Secure iOS User Data: Keychain Services and Biometrics with SwiftUI | Kodeco](https://www.kodeco.com/11496196-how-to-secure-ios-user-data-keychain-services-and-biometrics-with-swiftui) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** A password-protected SwiftUI notes app combines Keychain storage with biometric authentication, clarifying how credential retrieval and user presence fit together.
- [Deploying to Vapor Cloud 2 Tutorial | Kodeco](https://www.kodeco.com/1144342-deploying-to-vapor-cloud-2-tutorial) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Vapor Cloud deployment packages a server app with managed database support and environment configuration. Follow it to trace the gap between local Vapor assumptions and hosted process, port and persistence constraints.
- [Unit Testing Core Data in iOS | Kodeco](https://www.kodeco.com/11349416-unit-testing-core-data-in-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Demonstrates testing Core Data with isolated stores and controlled managed-object contexts. The key diagnostic boundary is preventing persistent test state from leaking between cases while still exercising fetch, save, and relationship behavior realistically.
- [Beginning Core Data | Kodeco](https://www.kodeco.com/10794954-beginning-core-data) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The Core Data series covers entity modeling, relationships, saving, and fetching, providing a concrete baseline for evaluating persistence-layer choices.
- [Encode and decode SwiftUI color](https://nilcoalescing.com/blog/EncodeAndDecodeSwiftUIColor) — Nil Coalescing · article catalogue
  **Published:** `2026-06-09`
  **NeKI brief:** Encodes and decodes SwiftUI Color values. Use it when persisting user-selected colors while accounting for color-space and dynamic-system-color limitations.
- [Clearing UserDefaults during macOS app development](https://nilcoalescing.com/blog/ClearingUserDefaultsDuringmacOSAppDevelopment) — Nil Coalescing · article catalogue
  **Published:** `2026-06-02`
  **NeKI brief:** Shows targeted UserDefaults cleanup during macOS development. Use it to reset persisted test state without deleting unrelated preferences, especially when a menu-bar or sandboxed app retains configuration between launches.
- [Teach your AI to write Swift the Hacking with Swift way – Hacking with Swift](https://www.hackingwithswift.com/articles/284/teach-your-ai-to-write-swift-the-hacking-with-swift-way) — Hacking with Swift articles · article catalogue
  **Published:** `2026-04-01T12:13:39+00:00`
  **NeKI brief:** Presents an AGENTS.md that encodes opinions about SwiftUI, Core Data, and particles for coding agents. Follow it as a concrete example of turning project conventions into reviewable guidance rather than relying on generic prompts.
- [Access application files on iOS simulator](https://nilcoalescing.com/blog/AccessApplicationFilesOniOSSimulator) — Nil Coalescing · article catalogue
  **Published:** `2026-03-04`
  **NeKI brief:** Simulator application data can be located and inspected through the platform's container layout, which is invaluable for checking persistence and exported files. The workflow distinguishes app containers from shared and system data.
- [Core Data Agent Skill: Now available open-source - SwiftLee](https://www.avanderlee.com/ai-development/core-data-agent-skill-now-available-open-source) — Antoine van der Lee articles · article catalogue
  **Published:** `2026-02-08T23:15:00+00:00`
  **NeKI brief:** Introduces an open-source Core Data agent skill containing model, migration, fetch, and persistence guidance. It is useful for steering an assistant through framework-specific invariants instead of letting generated code treat Core Data like a generic database.
- [A Deep Dive into SwiftData migrations – Donny Wals](https://www.donnywals.com/a-deep-dive-into-swiftdata-migrations) — Donny Wals · article catalogue
  **Published:** `2026-01-19T12:23:36+00:00`
  **NeKI brief:** Walks through SwiftData migration planning with the uncomfortable case of real users upgrading persisted data. Use it to identify schema-change hazards, staged model versions, and validation work needed before shipping a store update.
- [2025 Year-in-Review](https://www.pointfree.co/blog/posts/196-2025-year-in-review) — Point-Free · article catalogue
  **Published:** `2025-12-22T00:00:00Z`
  **NeKI brief:** The year review records how open-source library work, release cadence, and long-lived architecture projects reinforce one another. It is useful for tracing why API stability and maintenance investment matter beyond a single feature release.
- [Deep Dive into iMessage - Behind the Making of an Agent](https://fatbobman.com/en/posts/deep-dive-into-imessage) — Fatbobman · article catalogue
  **Published:** `2025-11-19T14:12:00.000Z`
  **NeKI brief:** Investigates iMessage storage through SQLite and Core Data timestamps, then uses imessage-kit to build an automation agent. The article is a concrete reference for understanding macOS message data boundaries and automation risks.
- [New in SQLiteData: Custom aggregate functions](https://www.pointfree.co/blog/posts/188-new-in-sqlitedata-custom-aggregate-functions) — Point-Free · article catalogue
  **Published:** `2025-10-16T00:00:00Z`
  **NeKI brief:** Adds custom aggregate SQL functions to SQLiteData while retaining typed query construction. Follow it when domain calculations belong in the database and you need schema-aware Swift rather than raw SQL strings.
- [New in SQLiteData: Migration tool for CloudKit sync](https://www.pointfree.co/blog/posts/187-new-in-sqlitedata-migration-tool-for-cloudkit-sync) — Point-Free · article catalogue
  **Published:** `2025-10-08T00:00:00Z`
  **NeKI brief:** Introduces a SQLiteData migration tool for stores synchronized with CloudKit, focusing on coordinating schema evolution with remote data. It is useful when persistence changes must remain deployable across already-synced installations.
- [Performing search with SwiftData in a SwiftUI app](https://www.createwithswift.com/performing-search-with-swiftdata-in-a-swiftui-app) — Create with Swift · article catalogue
  **Published:** `2025-10-07T13:00:01.000Z`
  **NeKI brief:** Builds SwiftData search in SwiftUI using predicates and query-driven state. Use it when filtering persisted models and needing search text, sort order, and result updates to remain declarative.
- [New in SQLiteData: Column groups and inheritance](https://www.pointfree.co/blog/posts/186-new-in-sqlitedata-column-groups-and-inheritance) — Point-Free · article catalogue
  **Published:** `2025-10-02T00:00:00Z`
  **NeKI brief:** Explains SQLiteData column groups and model inheritance as typed schema composition, reducing repetition while preserving SQL constraints. The design is a concrete alternative to duplicating fields across related tables.
- [What’s new in SQLiteData: Views](https://www.pointfree.co/blog/posts/185-what-s-new-in-sqlitedata-views) — Point-Free · article catalogue
  **Published:** `2025-09-24T00:00:00Z`
  **NeKI brief:** Uses SQLite views to expose derived read models through SQLiteData's typed APIs. Follow it when joins or aggregates should be reusable query surfaces without pretending they are independently mutable tables.
- [SQLiteData 1.0: An alternative to SwiftData with CloudKit sync and sharing](https://www.pointfree.co/blog/posts/184-sqlitedata-1-0-an-alternative-to-swiftdata-with-cloudkit-sync-and-sharing) — Point-Free · article catalogue
  **Published:** `2025-09-17T00:00:00Z`
  **NeKI brief:** SQLiteData combines SQLite persistence with CloudKit synchronization and sharing. Use it when SwiftData lacks required deployment or SQL control, while evaluating the operational cost of its sync model.
- [SQLiteData 0.7.0: User-defined SQL functions](https://www.pointfree.co/blog/posts/183-sharinggrdb-0-7-0-user-defined-sql-functions) — Point-Free · article catalogue
  **Published:** `2025-09-03T00:00:00Z`
  **NeKI brief:** SQLiteData exposes user-defined SQL functions through Swift declarations, preserving type-checked query construction while allowing database-specific computation. The extension point trades portability for expressiveness and requires controlling registration and migration behavior.
- [SQLiteData 0.6.0: Full-text search and more](https://www.pointfree.co/blog/posts/182-sharinggrdb-0-6-0-full-text-search-and-more) — Point-Free · article catalogue
  **Published:** `2025-08-21T00:00:00Z`
  **NeKI brief:** The SQLiteData update layers SQLite full-text search onto Swift query APIs, turning tokenization and ranking into database work rather than in-memory filtering. The design improves scale but makes index configuration and match semantics part of the model.
- [Property Wrappers in Swift explained with code examples - SwiftLee](https://www.avanderlee.com/swift/property-wrappers) — Antoine van der Lee articles · article catalogue
  **Published:** `2025-08-19T12:08:35+00:00`
  **NeKI brief:** Builds custom property wrappers to centralize storage and projected values, then shows their initialization and composition rules. The article helps evaluate when a wrapper removes duplication without hiding important state transitions.
- [A SwiftData alternative with SQLite + CloudKit: Public beta](https://www.pointfree.co/blog/posts/181-a-swiftdata-alternative-with-sqlite-cloudkit-public-beta) — Point-Free · article catalogue
  **Published:** `2025-08-04T00:00:00Z`
  **NeKI brief:** Announces a SQLite and CloudKit synchronization alternative to SwiftData. Use it to investigate relational persistence and sync options, then verify API maturity and operational trade-offs before adoption.
- [Core Data Migration Incident Analysis - The Hidden Traps We Overlooked](https://fatbobman.com/en/posts/core-data-migration-incident-analysis) — Fatbobman · article catalogue
  **Published:** `2025-07-23T14:00:00.000Z`
  **NeKI brief:** A production migration freeze is traced to WAL checkpoint behavior and work performed during startup. The analysis favors background initialization and explicit WAL optimization, giving a concrete checklist for separating migration cost from main-thread launch failures.
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
- [Type-safe, schema-safe SQL triggers in Swift](https://www.pointfree.co/blog/posts/176-type-safe-schema-safe-sql-triggers-in-swift) — Point-Free · article catalogue
  **Published:** `2025-06-23T00:00:00Z`
  **NeKI brief:** Typed SQL triggers can be declared alongside Swift models so trigger names, tables, and expressions remain part of a checked schema surface. The approach improves migration visibility while accepting that database-side behavior is harder to debug from Swift alone.
- [Upcoming live stream: A vision for modern persistence](https://www.pointfree.co/blog/posts/175-upcoming-live-stream-a-vision-for-modern-persistence) — Point-Free · article catalogue
  **Published:** `2025-06-17T00:00:00Z`
  **NeKI brief:** The modern-persistence proposal favors explicit SQLite control and composable synchronization over opaque model storage. It is useful for comparing schema ownership and query observability, while the announced status means API stability is not guaranteed.
- [Free Episode: SwiftData versus SQL Query Builder](https://www.pointfree.co/blog/posts/174-free-episode-swiftdata-versus-sql-query-builder) — Point-Free · article catalogue
  **Published:** `2025-06-12T00:00:00Z`
  **NeKI brief:** Compares SwiftData with a SQL query-builder approach. Use it when choosing between declarative model persistence and explicit relational queries, migrations, and database-level control.
- [WWDC 2025 First Impressions - As Expected, Yet Unexpected](https://fatbobman.com/en/posts/wwdc-2025-first-impressions) — Fatbobman · article catalogue
  **Published:** `2025-06-11T00:12:00.000Z`
  **NeKI brief:** Offers first impressions of WWDC 2025 through Liquid Glass, SwiftUI, SwiftData, Foundation Models, and macros. Follow it for ecosystem-level context and competing priorities, not as a substitute for API-level migration guidance.
- [Syncing TipKit with CloudKit](https://useyourloaf.com/blog/syncing-tipkit-with-cloudkit) — Use Your Loaf · article catalogue
  **Published:** `2025-06-02T11:43:39+01:00`
  **NeKI brief:** Opting TipKit into CloudKit requires an iCloud container ending in .tips, remote notifications capability, and Tips.configure with cloudKitContainer. The article highlights the automatic-container convention and the deployment/setup steps needed for cross-device tip state.
- [SwiftData Predicates For Parent Relationships](https://useyourloaf.com/blog/swiftdata-predicates-for-parent-relationships) — Use Your Loaf · article catalogue
  **Published:** `2025-05-05T10:31:41+01:00`
  **NeKI brief:** Builds a #Predicate over an optional SwiftData relationship by comparing the parent’s persistentModelID, then extends the pattern to multiple parent IDs. This is useful when CloudKit-compatible optional relationships must still support parameterized child queries.
- [Building Type‑Safe, High‑Performance SwiftData / Core Data Models](https://fatbobman.com/en/posts/building-typesafe-highperformance-swiftdata-core-data-models) — Fatbobman · article catalogue
  **Published:** `2025-04-23T14:00:00.000Z`
  **NeKI brief:** Explores type-safe, high-performance model design across SwiftData and Core Data, with attention to schema choices and query behavior. Use it when shaping a persistence layer that balances compile-time clarity, migration needs, and runtime performance.
- [A fast, lightweight replacement for SwiftData](https://www.pointfree.co/blog/posts/170-a-fast-lightweight-replacement-for-swiftdata) — Point-Free · article catalogue
  **Published:** `2025-04-22T00:00:00Z`
  **NeKI brief:** The proposed SwiftData replacement keeps SQL as the persistence core while exposing ergonomic Swift APIs for queries and mutations. The trade-off is explicit schema and query control in exchange for more database concepts at the application boundary.
- [Modern URL construction in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/modern-url-construction-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2025-03-31`
  **NeKI brief:** Builds URLs with modern Foundation components rather than string concatenation. Use it when paths, query items, and percent encoding must remain correct under optional or user-provided values.
- [SwiftData Limitations - What to Know Before Adopting SwiftData](https://fatbobman.com/en/posts/key-considerations-before-using-swiftdata) — Fatbobman · article catalogue
  **Published:** `2025-03-12T14:00:00.000Z`
  **NeKI brief:** Evaluates SwiftData's practical limits before adoption. Use it when deciding whether its model, migration, query, or synchronization behavior fits a production persistence requirement.
- [Testing SceneStorage state persistence in Xcode](https://nilcoalescing.com/blog/TestingSceneStorageStatePersistenceInXcode) — Nil Coalescing · article catalogue
  **Published:** `2025-02-19`
  **NeKI brief:** Describes a repeatable simulator sequence for testing SceneStorage restoration: background the app, terminate or relaunch it, and verify state after scene recreation. The workflow avoids false positives from merely navigating away within one process.
- [SQLiteData: A SwiftData Alternative](https://www.pointfree.co/blog/posts/168-sharinggrdb-a-swiftdata-alternative) — Point-Free · article catalogue
  **Published:** `2025-02-14T17:00:00Z`
  **NeKI brief:** Introduces SharingGRDB as a SQLite-backed state-sharing approach for SwiftUI, combining persistence with observation. Useful when evaluating a relational alternative to SwiftData for shared, queryable application state.
- [Model Inheritance in Core Data](https://fatbobman.com/en/posts/model-inheritance-in-core-data) — Fatbobman · article catalogue
  **Published:** `2024-12-11T14:00:00.000Z`
  **NeKI brief:** Core Data model inheritance shares attributes through an entity hierarchy, but affects fetches, predicates, and migration shape. This article helps weigh polymorphic convenience against SQL complexity and unexpected inclusion of subtype objects.
- [Simple state sharing and persistence in Swift](https://www.pointfree.co/blog/posts/159-simple-state-sharing-and-persistence-in-swift) — Point-Free · article catalogue
  **Published:** `2024-12-02T00:00:00Z`
  **NeKI brief:** A state-sharing abstraction can combine observation with persistence while keeping storage choice behind a dependency. The design makes synchronization policy testable, but callers must still define conflict and reset semantics.
- [Using Transactions Instead of Save in SwiftData and Core Data](https://fatbobman.com/en/posts/using-transactions-instead-of-save-in-swiftdata-and-core-data) — Fatbobman · article catalogue
  **Published:** `2024-11-20T14:00:00.000Z`
  **NeKI brief:** Compares transaction-style persistence work with ordinary save calls in SwiftData and Core Data. Use it when batching mutations, rollback boundaries, and consistency matter more than one-off writes.
- [Mastering Data Tracking and Notifications in Core Data and SwiftData](https://fatbobman.com/en/posts/mastering-data-tracking-and-notifications-in-core-data-and-swiftdata) — Fatbobman · article catalogue
  **Published:** `2024-11-06T14:00:00.000Z`
  **NeKI brief:** Explores change tracking and notifications in Core Data and SwiftData. Use it when UI or synchronization logic must react to persistence mutations without polling or broad refreshes.
- [Vapor and Swift Testing: Running tests in parallel - SwiftLee](https://www.avanderlee.com/swift-testing/vapor-and-swift-testing-running-tests-in-parallel) — Antoine van der Lee articles · article catalogue
  **Published:** `2024-10-22T08:29:49+00:00`
  **NeKI brief:** Explains why Vapor tests become unsafe under Swift Testing’s parallel execution and shows isolation strategies for shared databases and application state, making the concurrency trade-off concrete for server-side Swift.
- [Reinventing Core Data Development with SwiftData Principles](https://fatbobman.com/en/posts/reinventing-core-data-development-with-swiftdata-principles) — Fatbobman · article catalogue
  **Published:** `2024-10-16T14:00:00.000Z`
  **NeKI brief:** Examines SwiftData through Core Data's persistence principles, highlighting schema, context, and migration trade-offs. Useful when adopting SwiftData without discarding lessons from mature persistence architecture.
- [UserDefaults and Observation in SwiftUI - How to Achieve Precise Responsiveness](https://fatbobman.com/en/posts/userdefaults-and-observation) — Fatbobman · article catalogue
  **Published:** `2024-10-09T14:00:00.000Z`
  **NeKI brief:** Observation does not automatically make UserDefaults changes precise inside SwiftUI. The @ObservableDefaults approach bridges key reads and writes into tracked properties, avoiding broad invalidation while retaining UserDefaults persistence semantics.
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
- [Storing information using User Defaults and @AppStorage](https://www.createwithswift.com/storing-information-using-user-defaults-appstorage) — Create with Swift · article catalogue
  **Published:** `2024-05-09T13:23:19.000Z`
  **NeKI brief:** Stores lightweight settings with UserDefaults and AppStorage, separating persistent preference values from domain data that needs stronger modeling.
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
- [Custom Core Data migrations](https://www.polpiella.dev/custom-core-data-migrations) — Pol Piella · article catalogue
  **Published:** `2024-02-21T00:00:00.000Z`
  **NeKI brief:** Custom Core Data migrations provide a mapping policy for transformations that lightweight inference cannot express. The design keeps legacy data readable while requiring explicit tests for each source-to-destination field conversion.
- [Disabling Core Data CloudKit Logging](https://useyourloaf.com/blog/disabling-core-data-cloudkit-logging) — Use Your Loaf · article catalogue
  **Published:** `2024-02-05T13:17:02+00:00`
  **NeKI brief:** Shows how to reduce noisy Core Data and CloudKit logging during development while retaining actionable diagnostics. Useful for separating persistence debugging from unrelated framework chatter.
- [Exploring SwiftUI Property Wrappers - @AppStorage, @SceneStorage, @FocusState, @GestureState and @ScaledMetric](https://fatbobman.com/en/posts/exploring-swiftui-property-wrappers-2) — Fatbobman · article catalogue
  **Published:** `2024-01-25T04:00:00.000Z`
  **NeKI brief:** AppStorage, SceneStorage, FocusState, GestureState, and ScaledMetric each bind a different kind of transient or persisted value to SwiftUI. Comparing their lifetimes helps diagnose state restoration, focus loss, and gesture-reset bugs.
- [SwiftData Relationships - @Relationship, Inverse, One-to-Many](https://fatbobman.com/en/posts/relationships-in-swiftdata-changes-and-considerations) — Fatbobman · article catalogue
  **Published:** `2024-01-18T00:12:00.000Z`
  **NeKI brief:** SwiftData relationships infer inverses and delete behavior from model declarations, yet optionality and initialization still affect generated schema. The article helps diagnose unexpected relationship mutations and choose explicit @Relationship settings.
- [Introducing Elite Soccer Club | Swiftjective-C](https://swiftjectivec.com/Using-Keychain-Access-Secure-Notes-on-macOS-To-Store-Socials) — Swiftjective-C · article catalogue
  **Published:** `2024-01-14T00:00:00-06:00`
  **NeKI brief:** Using Keychain-backed secure notes separates sensitive account data from app files, but retrieval and sharing workflows still need explicit access-control decisions.
- [Mastering Relationships in Core Data - Practical Application](https://fatbobman.com/en/posts/mastering-relationships-in-core-data-practical) — Fatbobman · article catalogue
  **Published:** `2024-01-11T00:12:00.000Z`
  **NeKI brief:** Practical Core Data relationships cover inverse maintenance, delete rules, and fetch behavior under real object graphs. Follow it when a model appears correct but cascades or faulting produce surprising runtime results.
- [Mastering Relationships in Core Data - Fundamentals](https://fatbobman.com/en/posts/mastering-relationships-in-core-data-fundamentals) — Fatbobman · article catalogue
  **Published:** `2024-01-04T00:12:00.000Z`
  **NeKI brief:** Core Data relationship fundamentals explain cardinality, inverses, and object-graph consistency before application-specific code complicates the picture. It is a useful schema-design reference for preventing invalid graph states.
- [SwiftData Fetching Pending Changes](https://useyourloaf.com/blog/swiftdata-fetching-pending-changes) — Use Your Loaf · article catalogue
  **Published:** `2024-01-01T10:03:32+00:00`
  **NeKI brief:** Investigates SwiftData fetches that should include unsaved changes, using SQLDebug output and two historical iOS 17 bugs to show what was actually returned. The updated evidence makes OS-version qualification part of debugging fetch results.
- [Build your first app with SwiftUI and SwiftData – Hacking with Swift](https://www.hackingwithswift.com/articles/263/build-your-first-app-with-swiftui-and-swiftdata) — Hacking with Swift articles · article catalogue
  **Published:** `2023-12-23T22:51:36+00:00`
  **NeKI brief:** Walks through a complete SwiftUI and SwiftData app, connecting model declaration, queries, and view updates. Use it as a baseline for checking persistence wiring before introducing custom architecture.
- [SwiftData Deleting Data](https://useyourloaf.com/blog/swiftdata-deleting-data) — Use Your Loaf · article catalogue
  **Published:** `2023-12-18T10:29:31+00:00`
  **NeKI brief:** Explains SwiftData deletion semantics and the need to mutate the model context deliberately. Use it when implementing destructive actions, save timing, and UI refresh behavior around removed objects.
- [Advanced iCloud Documents - Understanding Placeholder Files, Space Optimization, and Operational Techniques](https://fatbobman.com/en/posts/advanced-icloud-documents) — Fatbobman · article catalogue
  **Published:** `2023-12-14T00:11:00.000Z`
  **NeKI brief:** Advanced iCloud Documents distinguishes placeholder files, coordinated downloads, and storage optimization from ordinary local file I/O. The operational techniques are useful when diagnosing missing-content races and keeping document packages responsive under space pressure.
- [Migrating a Core Data store to an App Group shared container](https://www.polpiella.dev/core-data-migration-app-group) — Pol Piella · article catalogue
  **Published:** `2023-11-15T00:00:00.000Z`
  **NeKI brief:** Moving a Core Data store into an App Group container combines a filesystem relocation with model loading and coordinated migration. The sequence must preserve the old store until a successful copy and open have been verified.
- [How to Observe Data Changes in SwiftData using Persistent History Tracking](https://fatbobman.com/en/posts/persistent-history-tracking-in-swiftdata) — Fatbobman · article catalogue
  **Published:** `2023-11-02T00:12:00.000Z`
  **NeKI brief:** SwiftData persistent history exposes transactions from the same store, including widgets and batch work, so a client can react selectively instead of treating every save alike. The article shows filtering, replay, and tests for deterministic change handling.
- [User Defaults reading and writing in Swift - SwiftLee](https://www.avanderlee.com/swift/user-defaults-preferences) — Antoine van der Lee articles · article catalogue
  **Published:** `2023-10-23T17:31:53+00:00`
  **NeKI brief:** Covers UserDefaults registration, typed access, and suite selection for lightweight preferences. Useful for separating defaults from sensitive or relational data and avoiding scattered string-key persistence.
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
- [SwiftData Fetching An Existing Object](https://useyourloaf.com/blog/swiftdata-fetching-an-existing-object) — Use Your Loaf · article catalogue
  **Published:** `2023-08-21T09:06:59+01:00`
  **NeKI brief:** Uses SwiftData’s Codable and Sendable PersistentIdentifier to pass an object identity across contexts or threads, then fetches it in the destination ModelContext. This mirrors Core Data object-ID handoff without passing non-Sendable model instances.
- [Making your SwiftData models Codable – Donny Wals](https://www.donnywals.com/making-your-swiftdata-models-codable) — Donny Wals · article catalogue
  **Published:** `2023-08-15T12:56:12+00:00`
  **NeKI brief:** Examines the boundary between SwiftData models and Codable representations, including why persistence annotations do not automatically make a model a good wire format. It is useful when separating API payloads from storage objects.
- [Implement your Data Access Layer with Combine](https://blog.jacobstechtavern.com/p/implement-your-data-access-layer) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2023-08-15T08:15:19.237Z`
  **NeKI brief:** Separates what data an app needs from how a network or cache retrieves it, then composes repository operations with Combine publishers. Follow it when introducing a data-access boundary that can swap sources and remain mockable in asynchronous tests.
- [SwiftData Background Tasks](https://useyourloaf.com/blog/swiftdata-background-tasks) — Use Your Loaf · article catalogue
  **Published:** `2023-08-14T13:16:10+01:00`
  **NeKI brief:** Explains moving SwiftData work to a ModelActor and its model executor, keeping Model and ModelContext on their owning actor. Persistent identifiers, not model objects, form the safe boundary for background imports and other long-running operations.
- [SwiftData Saving Changes](https://useyourloaf.com/blog/swiftdata-saving-changes) — Use Your Loaf · article catalogue
  **Published:** `2023-07-24T13:19:25+01:00`
  **NeKI brief:** Explains when SwiftData persists model mutations and how explicit saves interact with the model context. Useful for avoiding assumptions about durability after background or lifecycle-driven updates.
- [WWDC 2023, What’s New in Core Data](https://fatbobman.com/en/posts/what-s-new-in-core-data-in-wwdc23) — Fatbobman · article catalogue
  **Published:** `2023-07-04T00:12:00.000Z`
  **NeKI brief:** The WWDC 2023 Core Data review maps new capabilities to existing store and context constraints. Follow it when deciding whether an announced API removes a workaround or merely changes where complexity lives.
- [Configuring SwiftData in a SwiftUI app](https://www.polpiella.dev/configuring-swiftdata-in-a-swiftui-app) — Pol Piella · article catalogue
  **Published:** `2023-06-28T00:00:00.000Z`
  **NeKI brief:** Walks through configuring SwiftData in a SwiftUI application, including container setup and model access. Useful for establishing persistence boundaries and avoiding accidental model-container creation in previews or tests.
- [WWDC23 Core Data Lab Notes](https://useyourloaf.com/blog/wwdc23-core-data-lab-notes) — Use Your Loaf · article catalogue
  **Published:** `2023-06-26T10:00:07+01:00`
  **NeKI brief:** Records Core Data lab guidance on CloudKit synchronization and persistence edges, useful historical context for understanding why store coordination must remain explicit.
- [WWDC23 SwiftData Lab Notes](https://useyourloaf.com/blog/wwdc23-swiftdata-lab-notes) — Use Your Loaf · article catalogue
  **Published:** `2023-06-19T10:24:33+01:00`
  **NeKI brief:** Records SwiftData lab observations from WWDC23, preserving early persistence and migration caveats that explain why later APIs may look intentionally constrained.
- [WWDC 23, First Impressions of SwiftUI 5 and SwiftData](https://fatbobman.com/en/posts/impressions-of-wwdc23) — Fatbobman · article catalogue
  **Published:** `2023-06-09T00:12:00.000Z`
  **NeKI brief:** Summarizes the SwiftUI 5 and SwiftData changes announced at WWDC 2023, especially Observation-based property tracking, animation, visual effects, and persistence. Use it as historical release context, verifying exact availability and migration details with Apple documentation.
- [Memory Optimization Journey for a SwiftUI + Core Data App](https://fatbobman.com/en/posts/memory-usage-optimization) — Fatbobman · article catalogue
  **Published:** `2023-03-08T00:20:00.000Z`
  **NeKI brief:** A SwiftUI and Core Data memory investigation correlates object graph retention, fetch size, and view updates with measured footprint. It offers a concrete route from Instruments evidence to targeted reductions rather than speculative cleanup.
- [Making a serverless Swift function with Fastly and Upstash](https://www.polpiella.dev/making-a-serverless-swift-function-with-fastly-and-upstash) — Pol Piella · article catalogue
  **Published:** `2023-01-18T00:00:00.000Z`
  **NeKI brief:** Builds a serverless Swift function backed by Fastly and Upstash services. Use it to evaluate edge execution, external state, and deployment boundaries when a small API does not need a long-lived server.
- [How to Save and Read Array in UserDefaults in Swift | Sarunw](https://sarunw.com/posts/how-to-save-array-in-userdefaults) — Sarunw · article catalogue
  **Published:** `2023-01-05`
  **NeKI brief:** Persists Codable arrays in UserDefaults for small settings data, while making the size and security boundary clear before choosing a database.
- [SwiftUI and Core Data - Safely Responding to Data](https://fatbobman.com/en/posts/modern-core-data-respond-data-safely) — Fatbobman · article catalogue
  **Published:** `2022-12-13T00:20:00.000Z`
  **NeKI brief:** Safely responding to Core Data changes in SwiftUI means separating context notifications from view-facing state and avoiding direct cross-queue object use. The patterns keep updates coherent without broad refetching.
- [SwiftUI and Core Data - Data Fetching](https://fatbobman.com/en/posts/modern-core-data-fetcher) — Fatbobman · article catalogue
  **Published:** `2022-12-06T00:20:00.000Z`
  **NeKI brief:** A dedicated Core Data fetcher separates request construction, context access, and published results, making asynchronous data loading explicit. Follow it when view code has become entangled with fetch timing and cancellation.
- [SwiftUI and Core Data - Data Definition](https://fatbobman.com/en/posts/modern-core-data-data-definition) — Fatbobman · article catalogue
  **Published:** `2022-11-29T00:20:00.000Z`
  **NeKI brief:** Core Data data definition in a SwiftUI app establishes entities, identity, and optionality before view observation begins. The guide helps prevent model shortcuts that later complicate predicates, migrations, and bindings.
- [CloudKit Console Act As iCloud Account](https://useyourloaf.com/blog/cloudkit-console-act-as-icloud-account) — Use Your Loaf · article catalogue
  **Published:** `2022-11-28T10:14:19+00:00`
  **NeKI brief:** Shows how CloudKit Console’s Act As iCloud Account feature lets development or production data be inspected for a different user, including private database and Core Data zone selection. It is a diagnostic workflow for reproducing account-specific sync issues.
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
- [How to save enum with associated value in UserDefaults using Swift | Sarunw](https://sarunw.com/posts/how-to-save-enum-associated-value-in-userdefaults-using-swift) — Sarunw · article catalogue
  **Published:** `2022-08-22`
  **NeKI brief:** Persists enums with associated values in UserDefaults through Codable representation, keeping serialization stable as enum cases evolve over future releases.
- [How to save enum in UserDefaults using Swift | Sarunw](https://sarunw.com/posts/how-to-save-enum-in-userdefaults-using-swift) — Sarunw · article catalogue
  **Published:** `2022-08-15`
  **NeKI brief:** Stores simple Swift enums in UserDefaults using raw values, keeping persistence format explicit and recoverable when values are absent.
- [Switching Core Data Cloud Sync Status in Real-Time](https://fatbobman.com/en/posts/real-time-switching-of-cloud-syncs-status) — Fatbobman · article catalogue
  **Published:** `2022-07-26T00:12:00.000Z`
  **NeKI brief:** Switching Core Data CloudKit synchronization at runtime requires coordinating store options, persistent containers, and existing contexts. The workflow is useful for diagnosing stale stores and deciding when a controlled rebuild is safer.
- [WWDC22 Core Data Lab Notes](https://useyourloaf.com/blog/wwdc22-core-data-lab-notes) — Use Your Loaf · article catalogue
  **Published:** `2022-07-11T11:19:23+01:00`
  **NeKI brief:** Summarizes Core Data lab guidance on concurrency, persistent history, and modern store behavior. Use it as a routing index for migration and synchronization decisions, then validate each recommendation against the app's context topology.
- [Better way to get paths to system directories in iOS 16 | Sarunw](https://sarunw.com/posts/url-type-properties) — Sarunw · article catalogue
  **Published:** `2022-07-07`
  **NeKI brief:** Uses URL type properties for system directories, replacing fragile string paths with platform-managed file locations and correct sandbox scope.
- [Batch Operations in Core Data](https://fatbobman.com/en/posts/batchprocessingincoredata) — Fatbobman · article catalogue
  **Published:** `2022-06-06T00:20:00.000Z`
  **NeKI brief:** Core Data batch inserts, updates, and deletes operate at the store level, so managed object contexts do not automatically see every change. The guide highlights merge and refresh steps needed for coherent UI state.
- [How Core Data Saves Data in SQLite](https://fatbobman.com/en/posts/tables_and_fields_of_coredata) — Fatbobman · article catalogue
  **Published:** `2022-05-31T00:20:00.000Z`
  **NeKI brief:** Core Data's SQLite representation uses tables and fields that reflect entities, attributes, and internal metadata rather than a hand-designed schema. Inspecting it is useful for diagnosing migration and fetch-performance surprises.
- [Core Data Saving Changes](https://useyourloaf.com/blog/core-data-saving-changes) — Use Your Loaf · article catalogue
  **Published:** `2022-05-23T11:43:44+01:00`
  **NeKI brief:** Explains Core Data's save propagation from child to parent contexts and persistent store, clarifying where errors surface. The workflow helps choose save boundaries and avoid assuming a child save has durably written user data.
- [Going Beyond @Published -Empowering Custom Property Wrappers](https://fatbobman.com/en/posts/adding-published-ability-to-custom-property-wrapper-types) — Fatbobman · article catalogue
  **Published:** `2022-05-17T00:20:00.000Z`
  **NeKI brief:** Custom property wrappers can expose projected observation while retaining specialized storage behavior. The article explains the forwarding and mutation contracts needed to avoid wrappers that appear reactive but never invalidate views.
- [Formatting numbers in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/formatting-numbers-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2022-05-07`
  **NeKI brief:** Covers localized number formatting in Swift. Use it when values require locale-aware display, rounding, currency, or measurement rules instead of manual string interpolation.
- [Exporting data from Unified Logging System in Swift | Swift with Majid](https://swiftwithmajid.com/2022/04/19/exporting-data-from-unified-logging-system-in-swift) — Swift with Majid · article catalogue
  **Published:** `2022-04-19T00:00:00+00:00`
  **NeKI brief:** Exports Unified Logging entries from Swift for support or diagnostics. Use it when a bug report needs structured OSLog evidence instead of screenshots or manually copied console text.
- [Zone sharing in CloudKit | Swift with Majid](https://swiftwithmajid.com/2022/03/29/zone-sharing-in-cloudkit) — Swift with Majid · article catalogue
  **Published:** `2022-03-29T00:00:00+00:00`
  **NeKI brief:** Explains CloudKit record-zone sharing and participant permissions for collaborative data. Sharing changes ownership and conflict assumptions, so the app must handle invitation state, server errors, and private database boundaries.
- [Getting started with CloudKit | Swift with Majid](https://swiftwithmajid.com/2022/03/22/getting-started-with-cloudkit) — Swift with Majid · article catalogue
  **Published:** `2022-03-22T00:00:00+00:00`
  **NeKI brief:** Introduces CloudKit containers, records, and database scopes as the persistence boundary for iCloud-backed apps. Network availability and quota failures are normal paths, requiring local caching or retry policy.
- [How to set UserDefaults value with Launch Arguments | Sarunw](https://sarunw.com/posts/how-to-set-userdefaults-value-with-launch-arguments) — Sarunw · article catalogue
  **Published:** `2022-03-10`
  **NeKI brief:** Use launch arguments to override UserDefaults values during tests or debug runs without changing persistent app state manually. Define predictable argument-to-key mapping and reset behavior, so test scenarios remain reproducible across simulator and CI launches.
- [Async Core Data Testing](https://useyourloaf.com/blog/async-core-data-testing) — Use Your Loaf · article catalogue
  **Published:** `2022-02-28T14:36:12+00:00`
  **NeKI brief:** Tests asynchronous Core Data operations with explicit completion synchronization, preventing false positives where a test exits before the store work has actually finished.
- [Count Queries in Core Data - The Master Guide](https://fatbobman.com/en/posts/countincoredata) — Fatbobman · article catalogue
  **Published:** `2022-01-17T00:12:00.000Z`
  **NeKI brief:** Counting Core Data records efficiently uses store-side requests instead of fetching full managed objects. The guidance is useful for dashboards and validation paths where memory use and faulting matter.
- [How to customize automatic synthesizing Codable for enums with associated values | Sarunw](https://sarunw.com/posts/how-to-customize-automatic-synthesizing-codable-for-enums-with-associated-values) — Sarunw · article catalogue
  **Published:** `2022-01-13`
  **NeKI brief:** Customize synthesized Codable enum representation by controlling coding keys and associated-value labels while preserving a stable external schema. Inspect the synthesized structure before changing cases, because seemingly local enum edits can break stored data or API decoding.
- [Five things iOS developers should focus on in 2022 – Donny Wals](https://www.donnywals.com/five-things-ios-developers-should-focus-on-in-2022) — Donny Wals · article catalogue
  **Published:** `2022-01-03T09:54:17+00:00`
  **NeKI brief:** The focus areas connect platform fundamentals with sustainable learning habits, offering a prioritization perspective rather than a substitute for project-specific technical requirements.
- [Using @SceneStorage With @FetchRequest](https://useyourloaf.com/blog/using-@scenestorage-with-@fetchrequest) — Use Your Loaf · article catalogue
  **Published:** `2021-12-20T10:19:35+00:00`
  **NeKI brief:** Combines SceneStorage with @FetchRequest to preserve selection or filter state across scene restoration, separating transient UI continuity from persistent Core Data records.
- [Using NSUbiquitousKeyValueStore with SwiftUI](https://fatbobman.com/en/posts/nsubiquitouskeyvaluestore) — Fatbobman · article catalogue
  **Published:** `2021-12-13T00:12:00.000Z`
  **NeKI brief:** NSUbiquitousKeyValueStore synchronizes small preference values through iCloud, with asynchronous updates and conflict considerations. Follow it when deciding whether lightweight cross-device settings belong here or in document/database sync.
- [How to Deep Copy NSManagedObject in Core Data](https://fatbobman.com/en/posts/mocloner) — Fatbobman · article catalogue
  **Published:** `2021-11-15T00:10:00.000Z`
  **NeKI brief:** Cloning NSManagedObjects requires copying attributes and rebuilding relationships without carrying a source object's identity or context assumptions. The workflow is useful for templates, drafts, and safe duplication in Core Data.
- [Several Tips on Core Data Concurrency Programming](https://fatbobman.com/en/posts/concurrencyofcoredata) — Fatbobman · article catalogue
  **Published:** `2021-11-05T00:20:00.000Z`
  **NeKI brief:** Core Data concurrency depends on context queue confinement and safely passing object IDs rather than managed objects. The article provides a diagnostic model for crashes caused by cross-thread object access.
- [Mastering Core Data Stack](https://fatbobman.com/en/posts/masteringofcoredatastack) — Fatbobman · article catalogue
  **Published:** `2021-11-02T00:10:00.000Z`
  **NeKI brief:** A Core Data stack coordinates model, persistent store coordinator, and contexts with explicit ownership and startup sequencing. The article helps diagnose initialization races and choose boundaries for background context work.
- [Using shared UserDefaults suites | Swift by Sundell](https://www.swiftbysundell.com/tips/using-shared-userdefaults-suites) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Shows shared UserDefaults suites as an explicit storage boundary for app extensions or cooperating targets. The suite improves sharing without global key collisions, but callers must coordinate keys and understand that values are not a secure secret store.
- [Using #function for UserDefaults key consistency | Swift by Sundell](https://www.swiftbysundell.com/tips/using-function-for-userdefaults-key-consistency) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Uses #function to derive UserDefaults keys from accessor names, reducing mismatches between reads and writes during refactors. The convenience couples persistence format to symbols, so explicit stable keys remain safer for migrations.
- [Parsing command line arguments using UserDefaults | Swift by Sundell](https://www.swiftbysundell.com/tips/parsing-command-line-arguments-using-userdefaults) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Uses UserDefaults' argument domain to parse launch-time flags for tests and development tools. This keeps configuration out of production persistence, but argument precedence should be documented when multiple domains overlap.
- [Avoiding mocking UserDefaults | Swift by Sundell](https://www.swiftbysundell.com/tips/avoiding-mocking-userdefaults) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Avoids mocking UserDefaults directly by injecting a protocol, suite, or values abstraction. This produces deterministic persistence tests while keeping production defaults behavior at one boundary.
- [Accessing the clipboard from a Swift script | Swift by Sundell](https://www.swiftbysundell.com/tips/accessing-the-clipboard-from-a-swift-script) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Accesses the clipboard from a Swift script for small developer workflows and automation. Clipboard data is external input; validate expected formats and avoid exposing sensitive values in logs.
- [Using Combine’s share operator to avoid duplicate work | Swift by Sundell](https://www.swiftbysundell.com/articles/using-combines-share-operator-to-avoid-duplicate-work) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Uses Combine's share operator to multicast one upstream subscription to multiple observers, preventing repeated requests. Sharing changes lifetime and replay behavior, so subscribers must be coordinated deliberately.
- [The power of UserDefaults in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/the-power-of-userdefaults-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Uses UserDefaults for small preference values with typed access patterns and defaults. It is not a database or secret store; migrations and key ownership should be centralized.
- [The power of sets in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/the-power-of-sets-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Uses Set for uniqueness and efficient membership checks when order is not part of the contract. Stable presentation order needs a separate sorted or ordered representation.
- [Swift sequences: The art of being lazy | Swift by Sundell](https://www.swiftbysundell.com/articles/swift-sequences-the-art-of-being-lazy) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Explains lazy Swift sequences as deferred transformations that avoid intermediate allocation until iteration. Laziness can improve pipelines, but deferred work and retained inputs should be obvious to callers.
- [Five powerful, yet lesser-known ways to use Swift enums | Swift by Sundell](https://www.swiftbysundell.com/articles/powerful-ways-to-use-swift-enums) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Uses Swift enums with associated values, raw values, and exhaustive switches to model finite domain states. Enums remove invalid combinations when cases represent mutually exclusive behavior.
- [Mock-free unit tests in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/mock-free-unit-tests-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Uses values, pure functions, and controllable dependencies to test behavior without elaborate mocks. Mock-free tests often better survive refactoring, though interaction verification still has focused use cases.
- [Maintaining model consistency in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/maintaining-model-consistency-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Maintains model consistency by centralizing invariants and preventing callers from independently mutating related fields. Typed transitions make invalid intermediate states harder to construct.
- [Integration tests in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/integration-tests-in-swift) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Uses integration tests to exercise real collaboration between modules, persistence, or network adapters. They complement unit tests and need controlled environments to remain reliable.
- [Exploring some of the lesser-known, built-in Formatter types | Swift by Sundell](https://www.swiftbysundell.com/articles/exploring-some-of-the-lesser-known-formatter-types) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Surveys built-in Formatter subclasses beyond common date and number formatting. Use it when presentation rules should use Foundation's localized formatters instead of hand-built string conversion.
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
- [How to set custom CodingKey for the convertFromSnakeCase decoding strategy | Sarunw](https://sarunw.com/posts/how-to-set-custom-codingkey-for-convertfromsnakecase-decoding-strategy) — Sarunw · article catalogue
  **Published:** `2021-09-06`
  **NeKI brief:** Use JSONDecoder.convertFromSnakeCase for ordinary keys, then define explicit CodingKeys for acronym or legacy exceptions such as URL and ID. Test underscore and capitalization edge cases against real payloads instead of assuming the automatic conversion matches every property name.
- [How to Preview a SwiftUI View with Core Data Elements in Xcode](https://fatbobman.com/en/posts/coredatainpreview) — Fatbobman · article catalogue
  **Published:** `2021-08-28T00:20:00.000Z`
  **NeKI brief:** Core Data in SwiftUI previews needs isolated stores, seeded fixtures, and deterministic context ownership. The guide helps prevent previews from touching production data or failing because a persistent container is unavailable.
- [Core Data with CloudKit - Synchronizing Public Database](https://fatbobman.com/en/posts/coredatawithcloudkit-5) — Fatbobman · article catalogue
  **Published:** `2021-08-13T11:22:00.000Z`
  **NeKI brief:** Core Data with CloudKit sync debugging requires separating persistent-history changes, merge timing, and CloudKit transport state. The article helps locate cross-device inconsistencies without treating every stale view as a UI bug.
- [How to create a property wrapper in Swift | Swift with Majid](https://swiftwithmajid.com/2021/08/11/how-to-create-a-property-wrapper-in-swift) — Swift with Majid · article catalogue
  **Published:** `2021-08-11T00:00:00+00:00`
  **NeKI brief:** A custom property wrapper can isolate storage, observation and projected bindings behind a reusable property declaration. Use it when repeated state behavior is truly consistent, avoiding wrappers that obscure ordinary dependencies.
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
- [How to read App Name, Version, and Build Number from Info.plist | Sarunw](https://sarunw.com/posts/how-to-read-info-plist) — Sarunw · article catalogue
  **Published:** `2021-05-17`
  **NeKI brief:** Read app display name, version, and build number from the bundled Info.plist through Bundle APIs, then keep presentation formatting separate from the raw values. This avoids duplicating release metadata in source and lets diagnostics reflect the actual built artifact.
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
- [How to delete UserDefaults data on macOS and Catalyst | Sarunw](https://sarunw.com/posts/how-to-delete-userdefaults-data-on-macos-catalyst) — Sarunw · article catalogue
  **Published:** `2021-02-11`
  **NeKI brief:** Uses macOS defaults domains to reset standard or custom UserDefaults during development, distinguishing bundle identifiers from suite names so Catalyst preference cleanup targets the intended store.
- [Profiling SwiftUI app using Instruments | Swift with Majid](https://swiftwithmajid.com/2021/01/20/profiling-swiftui-app-using-instruments) — Swift with Majid · article catalogue
  **Published:** `2021-01-20T00:00:00+00:00`
  **NeKI brief:** Uses Instruments to profile SwiftUI performance. Use it when a view-update or rendering problem needs measured call stacks and allocation evidence instead of intuition about declarative UI cost.
- [Preventing unwanted fetches when using NSFetchedResultsController and fetchBatchSize](https://www.donnywals.com/preventing-unwanted-fetches-when-using-nsfetchedresultscontroller-and-fetchbatchsize) — Donny Wals · article catalogue
  **Published:** `2021-01-18T08:45:28+00:00`
  **NeKI brief:** Fetched-results configuration can trigger more Core Data loading than expected; aligning batch size and controller behavior avoids hidden fetch cost during UI updates.
- [What does “atomic” mean in programming? – Donny Wals](https://www.donnywals.com/what-does-atomic-mean-in-programming) — Donny Wals · article catalogue
  **Published:** `2021-01-06T08:00:37+00:00`
  **NeKI brief:** Explains atomic operations as indivisible state changes and why compound read-modify-write code is not automatically atomic. Use it when designing synchronization around shared mutable state.
- [10 things iOS developers should focus on in 2021 – Donny Wals](https://www.donnywals.com/10-things-ios-developers-should-focus-on-in-2021) — Donny Wals · article catalogue
  **Published:** `2021-01-04T08:00:12+00:00`
  **NeKI brief:** A 2021 iOS learning snapshot connecting Combine, SwiftUI, testing, and package-management priorities; use it to compare a team's skills against its dated ecosystem baseline rather than current platform guidance.
- [Where is end-to-end encryption for iCloud? – Ole Begemann](https://oleb.net/2020/icloud-end-to-end-encryption) — Ole Begemann · article catalogue
  **Published:** `2020-12-10T16:17:45Z`
  **NeKI brief:** iCloud's privacy guarantees vary by data category and protection mode; end-to-end encryption is not universal by default. The analysis is useful when deciding what data an app may safely synchronize and what users must explicitly protect.
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
- [Setting default values for NSUserDefaults | Sarunw](https://sarunw.com/posts/setting-default-value-for-nsuserdefaults) — Sarunw · article catalogue
  **Published:** `2020-09-30`
  **NeKI brief:** Register UserDefaults defaults instead of writing fallback values on every launch, and distinguish registered defaults from persisted user choices. The walkthrough covers property-list input and the nil-key behavior, helping preference code preserve a user's override while retaining a reliable initial value.
- [Overriding UserDefaults for improved productivity - SwiftLee](https://www.avanderlee.com/xcode/overriding-userdefaults-launch-arguments) — Antoine van der Lee articles · article catalogue
  **Published:** `2020-09-29T07:00:00+00:00`
  **NeKI brief:** Uses Xcode scheme launch arguments to override UserDefaults at process startup, enabling repeatable flags and test configuration. Overrides stay isolated to the run.
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
- [Decode an array with a corrupted element | Sarunw](https://sarunw.com/posts/decode-array-with-corrupted-element) — Sarunw · article catalogue
  **Published:** `2020-05-15`
  **NeKI brief:** Codable normally fails an entire array when one element violates its schema, which is the right default for controlled APIs. For legacy or third-party data, decode elements through a lossy optional wrapper, discard failures deliberately, and log the data-quality trade-off.
- [How to read a Property List (plist) into the code | Sarunw](https://sarunw.com/posts/how-to-read-plist-file) — Sarunw · article catalogue
  **Published:** `2020-03-03`
  **NeKI brief:** Load a bundled property-list resource through Bundle, then decode its data with PropertyListSerialization into the expected dictionary or array shape. Keep the resource name and schema explicit, and treat decode failure as configuration validation rather than force-casting arbitrary values.
- [Using launch arguments for easier Core Data and SwiftData debugging – Donny Wals](https://www.donnywals.com/using-launch-arguments-for-easier-core-data-debugging) — Donny Wals · article catalogue
  **Published:** `2019-12-01T08:00:00+00:00`
  **NeKI brief:** Launch arguments enable Core Data diagnostics without changing source code, making SQL and migration behavior inspectable in a reproducible debug configuration.
- [Storage options on iOS compared – Donny Wals](https://www.donnywals.com/storage-options-on-ios-compared) — Donny Wals · article catalogue
  **Published:** `2019-11-25T08:00:44+00:00`
  **NeKI brief:** iOS storage choices trade queryability, durability, privacy, and migration cost; the data's access pattern should choose between defaults, files, keychain, or databases.
- [KeyValuePairs - NSHipster](https://nshipster.com/keyvaluepairs) — NSHipster · article catalogue
  **Published:** `2019-11-19T00:00:00-08:00`
  **NeKI brief:** KeyValuePairs preserves insertion order and duplicate keys, unlike Dictionary, making it suitable for argument lists and ordered configuration rather than lookup. The distinction prevents accidentally promising uniqueness when an API needs call-site order.
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
- [NSDataAsset - NSHipster](https://nshipster.com/nsdataasset) — NSHipster · article catalogue
  **Published:** `2018-08-26T00:00:00-07:00`
  **NeKI brief:** Shows packaging binary data in asset catalogs with NSDataAsset and loading it by name. Follow it when bundling configuration, certificates, or other data resources while keeping target membership and lookup explicit.
- [Core Data Debugging in Xcode using launch arguments - SwiftLee](https://www.avanderlee.com/debugging/core-data-debugging-xcode) — Antoine van der Lee articles · article catalogue
  **Published:** `2018-07-03T10:00:11+00:00`
  **NeKI brief:** Uses launch arguments and Xcode diagnostics to inspect Core Data SQL, query performance, thread-safety violations, and migration behavior. Useful for turning opaque persistence bugs into observable store-level evidence.
- [The Laws of Core Data | Dave DeLong](https://davedelong.com/blog/2018/05/09/the-laws-of-core-data) — Dave DeLong · article catalogue
  **Published:** `2018-05-09T00:00:00+00:00`
  **NeKI brief:** Core Data laws frame managed objects as context-bound lifecycles rather than ordinary models, clarifying why thread confinement and save ordering are correctness constraints.
- [How to make a copy of a Core Data SQLite database – Ole Begemann](https://oleb.net/blog/2018/03/core-data-sqlite-backup) — Ole Begemann · article catalogue
  **Published:** `2018-03-23T12:20:00Z`
  **NeKI brief:** Copying a Core Data SQLite store while its journal is active can produce an inconsistent backup. The article points to coordinating saves and persistent-store lifecycle so the snapshot reflects a transactionally valid database.
- [A script to save the last backup date in SuperDuper – Ole Begemann](https://oleb.net/blog/2018/01/superduper-last-backup-timestamp) — Ole Begemann · article catalogue
  **Published:** `2018-01-31T18:37:00Z`
  **NeKI brief:** Recording a backup timestamp in a small file gives scripts a durable handoff without parsing SuperDuper's UI. The workflow is intentionally simple, but consumers must define clock format and failure behavior for automation to remain reliable.
- [The 2018c Timezone Database Update | Dave DeLong](https://davedelong.com/blog/2018/01/31/the-2018c-timezone-database-update) — Dave DeLong · article catalogue
  **Published:** `2018-01-31T00:00:00+00:00`
  **NeKI brief:** Time-zone database updates can change historical and future civil-time interpretation without application code changes. Use explicit time-zone data and regression cases around affected regions, avoiding assumptions that UTC offsets are permanent.
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
- [CloudKit - NSHipster](https://nshipster.com/cloudkit) — NSHipster · article catalogue
  **Published:** `2015-06-29T00:00:00-07:00`
  **NeKI brief:** NSHipster’s CloudKit overview frames containers, records and iCloud-backed synchronization as distinct concerns. Follow it for historical API context and schema thinking before mapping a legacy design onto current CloudKit tooling.
- [iOS 9 - NSHipster](https://nshipster.com/ios9) — NSHipster · article catalogue
  **Published:** `2015-06-22T00:00:00-07:00`
  **NeKI brief:** This iOS 9 API tour covers string transformation, single-shot location requests, Swiftified Cocoa names, formatter additions and CloudKit. Use it to understand legacy API choices, checking current framework documentation and deprecation status before implementation.
- [Creating an OS X Core Data Helper App](https://useyourloaf.com/blog/creating-an-os-x-core-data-helper-app) — Use Your Loaf · article catalogue
  **Published:** `2015-03-25T21:46:47+00:00`
  **NeKI brief:** Uses a helper app around Core Data for focused management or diagnostics outside the main iOS client. Shared-store access requires coordinated model versions and clear ownership of migrations.
- [Backblaze Review – Ole Begemann](https://oleb.net/blog/2014/10/backblaze) — Ole Begemann · article catalogue
  **Published:** `2014-10-15T15:45:00Z`
  **NeKI brief:** A backup-service review is useful when it evaluates restore behavior, retention, encryption, and operational failure modes rather than storage price alone. It frames backups as a recoverability workflow.
- [Creating a CocoaPod](https://useyourloaf.com/blog/creating-a-cocoapod) — Use Your Loaf · article catalogue
  **Published:** `2014-08-13T21:00:48+01:00`
  **NeKI brief:** Explains creating a CocoaPod as historical package-distribution context. Public packaging requires a stable API, tests, and versioning discipline; modern distribution choices should be checked against current tooling.
- [Core Data Concurrency Debugging – Ole Begemann](https://oleb.net/blog/2014/06/core-data-concurrency-debugging) — Ole Begemann · article catalogue
  **Published:** `2014-06-11T21:22:00Z`
  **NeKI brief:** Enables Core Data's concurrency debugging to expose managed-object-context access on the wrong queue, turning a corruption-prone threading mistake into a diagnosable runtime failure during development.
- [iOS 8 - NSHipster](https://nshipster.com/ios8) — NSHipster · article catalogue
  **Published:** `2014-06-09T00:00:00-07:00`
  **NeKI brief:** This iOS 8 API tour examines LocalAuthentication, WKWebView, NSQualityOfService, HealthKit statistics, motion data and Foundation formatter additions. Use it to decode legacy code paths, verifying modern availability and privacy requirements before reuse.
- [How Dropbox Uses C++ for Cross-Platform iOS and Android Development – Ole Begemann](https://oleb.net/blog/2014/05/how-dropbox-uses-cplusplus-cross-platform-development) — Ole Begemann · article catalogue
  **Published:** `2014-05-23T20:17:00Z`
  **NeKI brief:** Analyzes Dropbox's former C++ shared-core strategy for iOS and Android, including the integration costs that later led it back to native languages and SDKs.
- [NSURL /NSURLComponents - NSHipster](https://nshipster.com/nsurl) — NSHipster · article catalogue
  **Published:** `2014-03-24T00:00:00-07:00`
  **NeKI brief:** Explains URL parsing and construction with NSURL and NSURLComponents. Useful for keeping scheme, host, path, and query manipulation structured instead of assembling fragile URL strings.
- [Temporary Files - NSHipster](https://nshipster.com/temporary-files) — NSHipster · article catalogue
  **Published:** `2014-03-03T00:00:00-08:00`
  **NeKI brief:** Discusses temporary-file lifetimes and cleanup in Cocoa applications. Useful for designing short-lived export, download, or transformation workflows without confusing cacheable artifacts with durable user data.
- [Handling Default Values With NSUserDefaults – Ole Begemann](https://oleb.net/blog/2014/02/nsuserdefaults-handling-default-values) — Ole Begemann · article catalogue
  **Published:** `2014-02-25T18:44:00Z`
  **NeKI brief:** Explains why missing NSUserDefaults values silently become type defaults and shows how registered defaults make preference reads explicit, correct, and independent of whether a user has previously changed a setting.
- [Namespacing - NSHipster](https://nshipster.com/namespacing) — NSHipster · article catalogue
  **Published:** `2014-02-24T00:00:00-08:00`
  **NeKI brief:** Namespacing prevents unrelated types and symbols from colliding as a codebase grows. Use modules, nested types and clear prefixes at Objective-C boundaries, avoiding artificial namespaces that obscure ownership.
- [FileManager - NSHipster](https://nshipster.com/filemanager) — NSHipster · article catalogue
  **Published:** `2013-11-18T00:00:00-08:00`
  **NeKI brief:** FileManager handles file creation, moves, copies and directory traversal through URL-based APIs. Follow it when implementing storage features, with sandbox locations, coordination and errors treated as part of the design.
- [Key-Value Observing - NSHipster](https://nshipster.com/key-value-observing) — NSHipster · article catalogue
  **Published:** `2013-10-07T00:00:00-07:00`
  **NeKI brief:** Key-Value Observing reports dynamic property changes from Objective-C-compatible objects. Follow it for legacy Cocoa integration, but manage observer lifetime and prefer typed observation mechanisms for new Swift code.
- [iOS 7 - NSHipster](https://nshipster.com/ios7) — NSHipster · article catalogue
  **Published:** `2013-09-23T00:00:00-07:00`
  **NeKI brief:** This iOS 7 API tour covers Base64 data encoding, URL components, NSProgress, metadata capture, Safari Reading List, speech synthesis and distance formatting. Use it as legacy context while replacing obsolete patterns with current frameworks.
- [NSPredicate - NSHipster](https://nshipster.com/nspredicate) — NSHipster · article catalogue
  **Published:** `2013-07-15T00:00:00-07:00`
  **NeKI brief:** Explains NSPredicate's query syntax for filtering and fetching collections. Useful for expressing selection declaratively while keeping predicate-format construction, validation, and data-store semantics visible.
- [NSDataDetector - NSHipster](https://nshipster.com/nsdatadetector) — NSHipster · article catalogue
  **Published:** `2013-06-02T00:00:00-07:00`
  **NeKI brief:** Introduces NSDataDetector for recognizing dates, addresses, links, and similar content in text. Useful for enriching user-entered content with system parsing rather than maintaining brittle regular-expression sets.
- [NSCoding / NSKeyedArchiver - NSHipster](https://nshipster.com/nscoding) — NSHipster · article catalogue
  **Published:** `2013-05-13T00:00:00-07:00`
  **NeKI brief:** Explains NSCoding and keyed archiving for reconstructing persisted object graphs. Useful historical context when maintaining archive-based storage or planning a deliberate migration to a modern persistence format.
- [NSSecureCoding - NSHipster](https://nshipster.com/nssecurecoding) — NSHipster · article catalogue
  **Published:** `2013-04-15T00:00:00-07:00`
  **NeKI brief:** Covers NSSecureCoding's class validation during keyed unarchiving. Useful for treating archived input as untrusted and restricting the types that can re-enter an application's object graph.
- [BOOL / bool / Boolean / NSCFBoolean - NSHipster](https://nshipster.com/bool) — NSHipster · article catalogue
  **Published:** `2013-04-08T00:00:00-07:00`
  **NeKI brief:** Boolean bridging spans C, Objective-C and Swift representations with different historical types and conventions. Use Swift Bool at application boundaries, converting explicitly when a C or Objective-C API requires another form.
- [iCloud - NSHipster](https://nshipster.com/icloud) — NSHipster · article catalogue
  **Published:** `2013-04-01T00:00:00-07:00`
  **NeKI brief:** iCloud services synchronize selected app data through distinct APIs with different conflict and availability behavior. Use the service that matches the data model, designing offline states and merge policy rather than assuming instant consistency.
- [C Storage Classes - NSHipster](https://nshipster.com/c-storage-classes) — NSHipster · article catalogue
  **Published:** `2013-03-18T00:00:00-07:00`
  **NeKI brief:** C storage classes control linkage, duration and visibility of variables and functions. Use them when reading or bridging C code, keeping Swift-facing interfaces narrow so C lifetime rules do not leak widely.
- [UIAppearance - NSHipster](https://nshipster.com/uiappearance) — NSHipster · article catalogue
  **Published:** `2013-03-11T00:00:00-07:00`
  **NeKI brief:** UIAppearance applies default UIKit styling through appearance proxies before views are displayed. Use it for broad consistent theming, testing containment and lifecycle behavior rather than expecting it to override every instance property.
- [Core Data by Marcus Zarra](https://useyourloaf.com/blog/core-data-by-marcus-zarra) — Use Your Loaf · article catalogue
  **Published:** `2013-03-07T22:12:00+00:00`
  **NeKI brief:** Routes to Core Data learning material as a deeper persistence reference. Apply patterns selectively and verify concurrency, migration, and framework APIs against the current platform.
- [NSURLCache - NSHipster](https://nshipster.com/nsurlcache) — NSHipster · article catalogue
  **Published:** `2013-02-11T00:00:00-08:00`
  **NeKI brief:** URLCache stores HTTP responses according to cache policy and headers. Use it to reduce repeat network work, validating cache-control behavior and privacy expectations before persisting authenticated or sensitive responses.
- [Type Encodings - NSHipster](https://nshipster.com/type-encodings) — NSHipster · article catalogue
  **Published:** `2013-02-04T00:00:00-08:00`
  **NeKI brief:** Explains Objective-C type-encoding strings as compact runtime metadata for method signatures, properties, and invocation. Use it when bridging reflection or generated interfaces, while treating the legacy syntax as version-sensitive implementation detail.
- [NSValue - NSHipster](https://nshipster.com/nsvalue) — NSHipster · article catalogue
  **Published:** `2013-01-28T00:00:00-08:00`
  **NeKI brief:** Shows how NSValue boxes scalars, structs, and geometry for Objective-C collections and APIs. Follow it when auditing mixed Swift/Objective-C boundaries, choosing Codable or native Swift values where modern code can avoid boxing.
- [KVC Collection Operators - NSHipster](https://nshipster.com/kvc-collection-operators) — NSHipster · article catalogue
  **Published:** `2012-12-03T00:00:00-08:00`
  **NeKI brief:** Uses Key-Value Coding collection operators to aggregate, filter, and transform object properties without manual loops. Treat it as legacy Objective-C machinery and verify key paths, nil handling, and Swift alternatives before reuse.
- [ValueTransformer - NSHipster](https://nshipster.com/valuetransformer) — NSHipster · article catalogue
  **Published:** `2012-11-12T00:00:00-08:00`
  **NeKI brief:** Describes ValueTransformer as a boundary for converting model values to persisted or transport representations. Use it when maintaining Core Data transformations, checking registration, reversibility, and compatibility with modern Codable or transformable attributes.
- [Adding A Search Bar To A Table View With Storyboards](https://useyourloaf.com/blog/search-bar-table-view-storyboard) — Use Your Loaf · article catalogue
  **Published:** `2012-09-06T15:10:00+00:00`
  **NeKI brief:** Integrates a search bar with a table view in a storyboard-based UI while maintaining filtering state. Keep query handling separate from cell rendering so updates remain testable.
- [NSCache - NSHipster](https://nshipster.com/nscache) — NSHipster · article catalogue
  **Published:** `2012-07-14T00:00:00-07:00`
  **NeKI brief:** NSCache provides memory-sensitive object caching with automatic eviction behavior. The guide is useful for avoiding unbounded dictionaries, while treating cached values as disposable and retaining a correct source of truth.
- [NSIndexSet - NSHipster](https://nshipster.com/nsindexset) — NSHipster · article catalogue
  **Published:** `2012-07-07T00:00:00-07:00`
  **NeKI brief:** Explains NSIndexSet as a sorted set of non-contiguous integer indexes, useful for batch selection and range operations. Follow it in legacy UIKit data-source code, verifying mutation and index validity across updates.
- [Prototype Table Cells and Storyboards](https://useyourloaf.com/blog/prototype-table-cells-and-storyboards) — Use Your Loaf · article catalogue
  **Published:** `2012-06-07T13:42:00+00:00`
  **NeKI brief:** Uses prototype table cells in storyboards to define reusable row layouts and identifiers. Cells must still reset state on reuse and adapt to dynamic type and different data lengths.
- [Creating and Deleting Calendars in iOS – Ole Begemann](https://oleb.net/blog/2012/05/creating-and-deleting-calendars-in-ios) — Ole Begemann · article catalogue
  **Published:** `2012-05-31T16:28:00Z`
  **NeKI brief:** Uses EventKit calendar APIs to create and remove user calendars, requiring explicit authorization and careful selection of the writable event-store source.
- [Core Data Queries Using Expressions](https://useyourloaf.com/blog/core-data-queries-using-expressions) — Use Your Loaf · article catalogue
  **Published:** `2012-01-19T22:15:00+00:00`
  **NeKI brief:** Uses Core Data expressions in fetch requests for computed or aggregate query results. Expressions can reduce data transfer, but their store support and result types need verification.
- [Sync preference data with iCloud](https://useyourloaf.com/blog/sync-preference-data-with-icloud) — Use Your Loaf · article catalogue
  **Published:** `2011-10-24T21:50:00+00:00`
  **NeKI brief:** Syncs small preference values through iCloud key-value storage while handling conflicts and availability. Keep preferences separate from authoritative user data and define a deterministic merge policy.
- [Passing Arguments with Xcode 4](https://useyourloaf.com/blog/passing-arguments-with-xcode-4) — Use Your Loaf · article catalogue
  **Published:** `2011-07-03T22:29:00+00:00`
  **NeKI brief:** Uses Xcode scheme arguments to configure launches for development or testing without source edits. Arguments should be documented and isolated from user-persisted preferences.
- [Remember to backup your keychain](https://useyourloaf.com/blog/remember-to-backup-your-keychain) — Use Your Loaf · article catalogue
  **Published:** `2011-06-19T21:59:00+00:00`
  **NeKI brief:** Reminds developers to back up Keychain credentials and signing material as operational hygiene. Secrets require secure storage and recovery planning, not copying them into repositories or source files.
- [UYLPasswordManager clearing the cache](https://useyourloaf.com/blog/uylpasswordmanager-clearing-the-cache) — Use Your Loaf · article catalogue
  **Published:** `2011-06-18T19:07:00+00:00`
  **NeKI brief:** Discusses clearing a password-manager cache as application maintenance behavior. Cache invalidation must preserve authentication state semantics and avoid silently discarding user data or credentials.
- [iOS and Keychain Migration and Data Protection - Part 3](https://useyourloaf.com/blog/ios-and-keychain-migration-and-data-protection-part-3) — Use Your Loaf · article catalogue
  **Published:** `2011-06-02T16:55:00+00:00`
  **NeKI brief:** Covers Keychain migration and data-protection behavior when users move devices or restore backups. Credential accessibility classes are a security contract and need explicit recovery-path testing.
- [iOS and Keychain Migration and Data Protection - Part 2](https://useyourloaf.com/blog/ios-and-keychain-migration-and-data-protection-part-2) — Use Your Loaf · article catalogue
  **Published:** `2011-06-01T21:24:00+00:00`
  **NeKI brief:** Continues Keychain data-protection guidance around backup and migration semantics. Store only what the chosen accessibility class protects, and avoid assuming a key survives every device transition.
- [iOS Keychain Migration and Data Protection - Part 1](https://useyourloaf.com/blog/ios-keychain-migration-and-data-protection-part-1) — Use Your Loaf · article catalogue
  **Published:** `2011-05-27T21:49:00+00:00`
  **NeKI brief:** Introduces Keychain migration and protection concepts for sensitive iOS data. Design access around device lock state and account lifecycle, not merely convenient persistence.
- [Inspecting Core Data Attributes – Ole Begemann](https://oleb.net/blog/2011/05/inspecting-core-data-attributes) — Ole Begemann · article catalogue
  **Published:** `2011-05-04T21:35:00Z`
  **NeKI brief:** Uses Core Data model introspection to inspect entities, property descriptions, and attribute types at runtime. Follow it when generic import, validation, or diagnostics code must adapt behavior to a managed object model instead of hard-coding fields.
- [User interface strings in Cocoa | Cocoa with Love](https://www.cocoawithlove.com/2011/04/user-interface-strings-in-cocoa.html) — Cocoa with Love · article catalogue
  **Published:** `2011-04-05`
  **NeKI brief:** Centralizing Cocoa UI strings makes localization an explicit resource lookup, but format placeholders and fallback behavior must remain consistent across languages.
- [Substituting local data for remote UIWebView requests | Cocoa with Love](https://www.cocoawithlove.com/2010/09/substituting-local-data-for-remote.html) — Cocoa with Love · article catalogue
  **Published:** `2010-09-06`
  **NeKI brief:** Substituting local data for remote UIWebView requests uses URL interception and a local response path, enabling deterministic offline rendering. The pattern helps test web-backed screens without relying on network timing.
- [Filtering arrays with NSPredicate](https://useyourloaf.com/blog/filtering-arrays-with-nspredicate) — Use Your Loaf · article catalogue
  **Published:** `2010-07-27T22:24:00+00:00`
  **NeKI brief:** Filters arrays with NSPredicate for reusable condition logic over Foundation collections. Typed Swift closures are often safer for new code, while predicate strings need carefully controlled keys and formats.
- [Requesting a new development certificate](https://useyourloaf.com/blog/requesting-a-new-development-certificate) — Use Your Loaf · article catalogue
  **Published:** `2010-06-19T11:57:00+00:00`
  **NeKI brief:** A development certificate expiry blocks new test-device installs even though already-installed apps keep running. Check certificate status in Keychain or Xcode, request a replacement through the developer portal, and regenerate dependent profiles for a complete recovery.
- [Managing User Preferences within an iPhone App](https://useyourloaf.com/blog/managing-user-preferences-within-an-iphone-app) — Use Your Loaf · article catalogue
  **Published:** `2010-05-19T20:13:00+00:00`
  **NeKI brief:** Choose in-app preferences for settings users change while using the feature, and system Settings for infrequent app-wide configuration. Keep both backed by the same defaults model so presentation location does not create divergent preference state.
- [Keychain duplicate item when adding password](https://useyourloaf.com/blog/keychain-duplicate-item-when-adding-password) — Use Your Loaf · article catalogue
  **Published:** `2010-04-28T18:53:00+00:00`
  **NeKI brief:** Keychain duplicate errors can occur when a lookup omits attributes that participate in an item's uniqueness. Build matching and add dictionaries from the same identity model, then update the existing item when appropriate instead of repeatedly calling SecItemAdd.
- [Network data requirements on iPhone OS devices | Cocoa with Love](https://www.cocoawithlove.com/2010/04/network-data-requirements-on-iphone-os.html) — Cocoa with Love · article catalogue
  **Published:** `2010-04-07`
  **NeKI brief:** Early iPhone networking constraints include bandwidth, latency, radio energy, and intermittent connectivity. The analysis helps frame request batching and caching as product behavior, not only transport optimization.
- [Keychain group access](https://useyourloaf.com/blog/keychain-group-access) — Use Your Loaf · article catalogue
  **Published:** `2010-04-03T16:07:00+00:00`
  **NeKI brief:** Share Keychain items only among apps signed with the same bundle seed and configured access group. Treat the entitlement as a security boundary: free and premium siblings can share account data, but unrelated apps must not inherit that access.
- [Simple iPhone Keychain Access](https://useyourloaf.com/blog/simple-iphone-keychain-access) — Use Your Loaf · article catalogue
  **Published:** `2010-03-29T21:14:00+00:00`
  **NeKI brief:** Store passwords, licenses, and other durable secrets in the iOS Keychain rather than ordinary app storage, since Keychain items can survive reinstalls and protected device backups. Define item class and accessibility deliberately; secure persistence has lifecycle implications.
- [Using categories with private methods](https://useyourloaf.com/blog/using-categories-with-private-methods) — Use Your Loaf · article catalogue
  **Published:** `2010-03-24T22:54:00+00:00`
  **NeKI brief:** Use a class extension or category to keep Objective-C helper methods private to the implementation file, preserving a small public interface while organizing internal behavior without exposing implementation details to callers.
- [Using categories with core data](https://useyourloaf.com/blog/using-categories-with-core-data) — Use Your Loaf · article catalogue
  **Published:** `2010-03-23T18:34:00+00:00`
  **NeKI brief:** Use Objective-C categories to extend generated Core Data classes without losing custom methods when model files are regenerated. Keep generated and hand-written concerns separate so schema updates do not erase application behavior.
- [Code signing error CSSMERR_DL_MISSING_VALUE](https://useyourloaf.com/blog/code-signing-error-cssmerr_dl_missing_value) — Use Your Loaf · article catalogue
  **Published:** `2010-03-15T21:06:00+00:00`
  **NeKI brief:** A CSSMERR_DL_MISSING_VALUE signing failure can come from Xcode selecting the wrong keychain or external certificate source. Inspect available identities and remove the conflicting token path rather than repeatedly regenerating valid iPhone signing credentials.
- [NSFetchedResultsController and sort performance](https://useyourloaf.com/blog/nsfetchedresultscontroller-and-sort-performance) — Use Your Loaf · article catalogue
  **Published:** `2010-03-15T14:29:00+00:00`
  **NeKI brief:** Fetched-results controllers simplify Core Data table updates, but grouped-table performance depends heavily on store-side sort descriptors. Avoid expensive case-insensitive sorting without measuring it; optimize the persistent representation or query when grouping becomes the bottleneck.
- [Debugging core data on the iPhone](https://useyourloaf.com/blog/debugging-core-data-on-the-iphone) — Use Your Loaf · article catalogue
  **Published:** `2010-03-11T19:36:00+00:00`
  **NeKI brief:** Enable Core Data SQL tracing through launch arguments when on-device tools do not expose persistence work. Read the emitted queries alongside slow operations to distinguish fetch design, faulting, and store-level costs before optimizing application code.
- [The differences between Core Data and a Database | Cocoa with Love](https://www.cocoawithlove.com/2010/02/differences-between-core-data-and.html) — Cocoa with Love · article catalogue
  **Published:** `2010-02-16`
  **NeKI brief:** Core Data manages an object graph and persistence context rather than exposing a plain relational database contract. The comparison clarifies faulting, identity, and change tracking before choosing queries or storage abstractions.
- [Finding the cause of performance issues in your programs | Cocoa with Love](https://www.cocoawithlove.com/2010/02/finding-cause-of-simple-performance.html) — Cocoa with Love · article catalogue
  **Published:** `2010-02-01`
  **NeKI brief:** Simple performance investigations start by measuring a reproducible workload and narrowing the dominant operation before optimizing. The workflow remains useful for avoiding intuition-driven changes in Cocoa code.
- [5 key-value coding approaches in Cocoa | Cocoa with Love](https://www.cocoawithlove.com/2010/01/5-key-value-coding-approaches-in-cocoa.html) — Cocoa with Love · article catalogue
  **Published:** `2010-01-25`
  **NeKI brief:** Five KVC approaches show how direct access, accessors, collection operators, and validation alter Cocoa data flow. Follow it to diagnose key-path failures and choose APIs that retain type and ownership clarity.
- [There's a Garbage Collection ninja hiding in the project templates | Cocoa with Love](https://www.cocoawithlove.com/2009/12/there-garbage-collection-ninja-hiding.html) — Cocoa with Love · article catalogue
  **Published:** `2009-12-01`
  **NeKI brief:** Garbage collection can hide leaks while leaving resource lifetime, cycles, and responsiveness unresolved. The essay helps distinguish memory reclamation from deterministic cleanup and ownership design.
- [Performance tests: Replacing Core Data Key Paths | Cocoa with Love](https://www.cocoawithlove.com/2009/11/performance-tests-replacing-core-data.html) — Cocoa with Love · article catalogue
  **Published:** `2009-11-21`
  **NeKI brief:** Replacing Core Data should be evaluated with representative persistence benchmarks, not assumptions about ORM overhead. The tests connect query shape, object creation, and caching behavior to measurable trade-offs.
- [Temporary files and folders in Cocoa | Cocoa with Love](https://www.cocoawithlove.com/2009/07/temporary-files-and-folders-in-cocoa.html) — Cocoa with Love · article catalogue
  **Published:** `2009-07-23`
  **NeKI brief:** Temporary files and folders should use system-provided locations and unique names, with explicit cleanup ownership. The workflow helps prevent collisions, sandbox violations, and orphaned intermediate artifacts.
- [Verifying that a string contains an email address using NSPredicate | Cocoa with Love](https://www.cocoawithlove.com/2009/06/verifying-that-string-is-email-address.html) — Cocoa with Love · article catalogue
  **Published:** `2009-06-23`
  **NeKI brief:** Email-address validation must separate superficial syntax checks from actual mailbox verification and product policy. The discussion helps avoid regexes that reject valid addresses or imply a stronger guarantee than validation provides.
- [Base64 encoding options on the Mac and iPhone | Cocoa with Love](https://www.cocoawithlove.com/2009/06/base64-encoding-options-on-mac-and.html) — Cocoa with Love · article catalogue
  **Published:** `2009-06-03`
  **NeKI brief:** Base64 encoding choices affect line wrapping, URL safety, padding, and binary-data interoperability. The comparison is useful when a transport or persistence format silently rejects otherwise valid encoded values.
- [Simple methods for date formatting and transcoding | Cocoa with Love](https://www.cocoawithlove.com/2009/05/simple-methods-for-date-formatting-and.html) — Cocoa with Love · article catalogue
  **Published:** `2009-05-25`
  **NeKI brief:** Date formatting requires choosing calendar, locale, time zone, and input semantics explicitly; a shared formatter is not a universal conversion tool. The article helps diagnose display and parsing errors in Cocoa apps.
- [Using NSKeyedArchiver to archive a C linked-list | Cocoa with Love](https://www.cocoawithlove.com/2009/03/using-nskeyedarchiver-to-archive-c.html) — Cocoa with Love · article catalogue
  **Published:** `2009-03-28`
  **NeKI brief:** NSKeyedArchiver archives object graphs through stable keys and decoding contracts, so schema evolution requires deliberate defaults and version handling. Follow it when persisting Cocoa models across app releases.
- [Serving an NSManagedObjectContext over an NSConnection | Cocoa with Love](https://www.cocoawithlove.com/2009/01/serving-nsmanagedobjectcontext-over.html) — Cocoa with Love · article catalogue
  **Published:** `2009-01-05`
  **NeKI brief:** Serving an NSManagedObjectContext over a boundary exposes why contexts are not thread-safe data services. Follow it when designing a persistence interface that must pass IDs or values instead of live managed objects.
- [Key Value Information | Cocoa with Love](https://www.cocoawithlove.com/2008/07/key-value-information.html) — Cocoa with Love · article catalogue
  **Published:** `2008-07-27`
  **NeKI brief:** KVC dynamically resolves accessor methods but does not directly expose an object's complete supported-key contract. Inspecting classes and accessors can reveal likely keys, yet dynamic resolution means runtime behavior remains more authoritative than reflection alone.
- [Five approaches to listening, observing and notifying in Cocoa. | Cocoa with Love](https://www.cocoawithlove.com/2008/06/five-approaches-to-listening-observing.html) — Cocoa with Love · article catalogue
  **Published:** `2008-06-07`
  **NeKI brief:** Compare manual listeners, KVO, notification centers, context notifications, and delegates by who owns the relationship and how broadly events fan out. Selecting the mechanism is an abstraction decision: direct delegation trades flexibility for clearer contracts.
- [Implementing countByEnumeratingWithState:objects:count: | Cocoa with Love](https://www.cocoawithlove.com/2008/05/implementing-countbyenumeratingwithstat.html) — Cocoa with Love · article catalogue
  **Published:** `2008-05-19`
  **NeKI brief:** Implement NSFastEnumeration by reporting mutation state, filling the caller's object buffer, and advancing the enumeration state correctly. The two examples distinguish wrapping existing contiguous storage from allocating temporary storage, where lifetime management becomes essential.
- [Propagate deletes immediately in Core Data | Cocoa with Love](https://www.cocoawithlove.com/2008/04/propagate-deletes-immediately-in-core.html) — Cocoa with Love · article catalogue
  **Published:** `2008-04-25`
  **NeKI brief:** Core Data cascade deletes may not update dependent graph state at the moment an app expects. Perform required relationship cleanup deliberately before saving when UI or business logic needs immediate consistency, then let the persistent store commit the final transaction.
- [Testing Core Data with very big hierarchical data sets | Cocoa with Love](https://www.cocoawithlove.com/2008/03/testing-core-data-with-very-big.html) — Cocoa with Love · article catalogue
  **Published:** `2008-03-28`
  **NeKI brief:** Benchmark Core Data with a realistic large hierarchy across creation, load, fetch, and traversal phases instead of inferring scale from small fixtures. Split measurements by operation so indexing, faulting, and relationship walking bottlenecks are distinguishable.
- [Core Data: one line fetch | Cocoa with Love](https://www.cocoawithlove.com/2008/03/core-data-one-line-fetch.html) — Cocoa with Love · article catalogue
  **Published:** `2008-03-07`
  **NeKI brief:** A concise Core Data fetch helper can remove boilerplate for ordinary queries while retaining the framework's predicate and context semantics. Do not let one-line convenience hide error handling, fetch limits, batching, or memory behavior needed by larger datasets.
- [mikeash.com: Friday Q&A 2010-08-12: Implementing NSCoding](https://www.mikeash.com/pyblog/friday-qa-2010-08-12-implementing-nscoding.html) — Mike Ash · article catalogue
  **NeKI brief:** Archiving types should encode a stable schema, decode defensively, and evolve optional fields compatibly; validate classes and values before reconstructing object graphs from untrusted or old archives.
- [Preventing forgotten database migrations with automated tests in iOS](https://tanaschita.com/testing-database-migrations) — Tanaschita · article catalogue
  **NeKI brief:** Presents a database-migration testing workflow that verifies schema changes against realistic stores. Use it to catch destructive transformations, ordering mistakes, and data-loss regressions before shipping a new persistence version.
- [Understanding the @FetchRequest property wrapper in SwiftUI](https://tanaschita.com/swiftui-fetchrequest-property-wrapper) — Tanaschita · article catalogue
  **NeKI brief:** Explains @FetchRequest as a SwiftUI-driven Core Data query, clarifying predicate, sort, and managed-object context boundaries that affect view updates.
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
- [Storing Swift structs in UserDefaults](https://tanaschita.com/swift-user-defaults-storing-structs) — Tanaschita · article catalogue
  **NeKI brief:** Shows encoding Swift structs before storing them in UserDefaults, keeping typed preferences behind a small persistence boundary. Useful for lightweight settings while avoiding UserDefaults as a substitute for relational data.
- [Working with the Keychain in iOS](https://tanaschita.com/ios-keychain-secure-data-storage) — Tanaschita · article catalogue
  **NeKI brief:** Explains storing sensitive iOS data in Keychain and the accessibility choices that affect availability. Use it when designing credential persistence, selecting protection classes, and separating secrets from ordinary app storage.
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
- [SwiftUI, Combine, and Firebase](https://peterfriese.dev/blog/2020/replicating-reminder-swiftui-firebase-part1) — Peter Friese articles · article catalogue
  **NeKI brief:** Combining SwiftUI, Combine, and Firebase requires keeping publishers for remote state separate from view-local mutations. The sample's layering makes asynchronous updates observable while retaining a clear place for authentication and persistence policy.
- [MartianCraft on WWDC26: What Caught Our Eye](https://martiancraft.com/blog/2026/06/mc-on-wwdc26) — MartianCraft · article catalogue
  **NeKI brief:** Collects MartianCraft's WWDC26 implementation observations, including SwiftData and design changes that can be easy to miss in keynote coverage. It helps prioritize follow-up experiments while keeping the team's perspective separate from Apple API guidance.
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
- [Analyzing a MySQL database with R — Chris Eidhof](https://chris.eidhof.nl/post/analyzing-a-mysql-database-with-r) — Chris Eidhof · article catalogue
  **NeKI brief:** Demonstrates connecting R to a MySQL database and analyzing soccer-transfer data on macOS. It is a historical data-analysis tutorial outside NeKI's main Apple-development focus, with setup details likely outdated.
- [Accessing an API using CoreData's NSIncrementalStore — Chris Eidhof](https://chris.eidhof.nl/post/accessing-an-api-using-coredatas-nsincrementalstore) — Chris Eidhof · article catalogue
  **NeKI brief:** Builds an object-graph facade over the Bandcamp API by parsing responses, modeling entities and relationships in Core Data, then implementing an NSIncrementalStore to fetch them lazily. Use it to study decoupling controllers from API shape, while treating the experiment as historical.
- [Weeknotes № 21 — Chris Eidhof](https://chris.eidhof.nl/post/2023-21) — Chris Eidhof · article catalogue
  **NeKI brief:** A development weeknote about recreating Git's core read-only data structures in Swift and then experimenting with writing them. Useful as an approachable pointer to Git's underlying object model.

## Newsletter and related leads

- [MistKit](https://github.com/brightdigit/MistKit) — iOS Dev Tools · iOS Dev Tools: MistKit, Swift Scribe, cmux — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2026-07-16T16:45:11.086Z`
  **NeKI brief:** MistKit packages CloudKit Web Services access for server-side Swift and command-line tools, separating backend automation from Apple's client frameworks. Useful when a service needs CloudKit data without running inside an iOS app.
- [MemoryMap](https://github.com/naftaly/MemoryMap) — iOS Dev Tools · iOS Dev Tools: TourKit, MockingKit, MemoryMap — Source repository · Topics: Developer Tools · Persistence & Synchronisation · Swift
  **Published:** `2026-07-09T16:30:20.398Z`
  **NeKI brief:** MemoryMap persists plain-old-data Swift structs through memory-mapped files, emphasizing efficient access and crash-resilient storage. Useful for large fixed-layout local data where serialized object graphs would add unnecessary overhead.
- [Reordering SwiftData In List And Grid](https://www.youtube.com/watch?v=m5VdG-EKnmk) — Those Who Swift · Issue 274 — Video · Topics: Swift · SwiftData
  **Published:** `2026-07-08`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [What’s New In SwiftData For iOS 27](https://azamsharp.com/2026/06/12/whats-new-in-swiftdata.html) — Those Who Swift · Issue 271 — Article · Topics: Cross-Platform & Web · Swift · SwiftData
  **Published:** `2026-06-18`
  **NeKI brief:** Summarizes SwiftData changes for iOS 27. Use it to identify migration and feature candidates for a persistence layer, then verify model, query, and availability details against current Apple documentation.
- [Stop configuring MCPs in every AI app](https://www.mcp-beast.ai/mac-app-ios-developers) — SwiftLee Weekly · Issue 328 — Article · Topics: AI Development · Developer Tools · Persistence & Synchronisation
  **Published:** `2026-06-16T14:06:32.000Z`
  **NeKI brief:** Explores centralizing MCP configuration so multiple AI clients can share one setup. Use it when reducing repeated tool registration across development environments, while reviewing credential handling and client-specific capability differences.
- [Core Data + Observation: From Property-Level Reactivity to a Freer Mental Model](https://fatbobman.com/en/posts/core-data-observation-freer-mental-model?ref=createwithswift.com) — Create with Swift · Issue 110 — Article · Topics: Core Data · Persistence & Synchronisation · Swift
  **Published:** `2026-06-06T14:00:23.000Z`
  **NeKI brief:** Explains how Core Data observation shifts from property-level change tracking toward a broader data-flow model, clarifying where SwiftUI invalidation and persistence boundaries meet.
- [Core Data + Observation: From Property-Level Reactivity to a Freer Mental Model](https://fatbobman.com/en/posts/core-data-observation-freer-mental-model) — iOS Dev Weekly · Issue 753 — Article · Topics: Core Data · Persistence & Synchronisation · Swift
  **Published:** `5th June 2026`
  **NeKI brief:** Explains how Core Data observation shifts from property-level change tracking toward a broader data-flow model, clarifying where SwiftUI invalidation and persistence boundaries meet.
- [Fatbobman](https://fatbobman.com/en/about) — iOS Dev Weekly · Issue 753 — Article · Topics: Core Data · Persistence & Synchronisation · Swift
  **Published:** `5th June 2026`
  **NeKI brief:** Presents fatbobman for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Working with the Keychain in iOS](https://tanaschita.com/ios-keychain-secure-data-storage?ref=createwithswift.com) — Create with Swift · Issue 109 — Article · Topics: Persistence & Synchronisation · Security & Privacy · Swift
  **Published:** `2026-05-29T16:00:08.000Z`
  **NeKI brief:** Explains storing sensitive iOS data in Keychain and the accessibility choices that affect availability. Use it when designing credential persistence, selecting protection classes, and separating secrets from ordinary app storage.
- [Building a Custom Data Store in SwiftData](https://azamsharp.com/2026/05/26/building-a-custom-data-store-in-swiftdata.html) — iOS Dev Weekly · Issue 752 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `29th May 2026`
  **NeKI brief:** Walks through implementing a custom SwiftData store and the integration points needed to replace default persistence; useful when evaluating storage backends and their lifecycle trade-offs.
- [Decoupling SwiftData in SwiftUI: Is It Worth It?](https://www.youtube.com/watch?v=2so9ifq5hYY) — Those Who Swift · Issue 268 — Video · Topics: Swift · SwiftData · SwiftUI
  **Published:** `2026-05-27`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
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
- [Sharing SwiftData Content Between Users](https://www.youtube.com/watch?v=t9FRldfZ8vc) — Those Who Swift · Issue 254 — Video · Topics: Swift · SwiftData · SwiftUI
  **Published:** `2026-02-18`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Mastering DatePicker, MultiDatePicker, and ColorPicker in SwiftUI](https://www.youtube.com/watch?v=O540BJGGpYw&t=2s) — Those Who Swift · Issue 252 — Video · Topics: Persistence & Synchronisation · Swift · SwiftUI
  **Published:** `2026-02-04`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Swift Concurrency](https://github.com/AvdLee/Swift-Concurrency-Agent-Skill) — Fatbobman’s Swift Weekly · Issue 121 — Source repository · Topics: Concurrency · Swift · SwiftUI
  **Published:** `2026-02-02T12:03:11.621Z`
  **NeKI brief:** Provides focused agent guidance for Swift concurrency work. Use it to give coding agents project-relevant rules around isolation, Sendable boundaries, and async tests before they propose or edit concurrent Swift code.
- [Core Data](https://github.com/AvdLee/Core-Data-Agent-Skill) — Fatbobman’s Swift Weekly · Issue 121 — Source repository · Topics: Core Data · Persistence & Synchronisation · Swift
  **Published:** `2026-02-02T12:03:11.621Z`
  **NeKI brief:** Provides focused agent guidance for Core Data tasks. Use it to constrain an agent around contexts, threading, migrations, and persistence boundaries before it modifies an existing Core Data stack.
- [Mobile Engineers, You’re All Full-Stack](https://newsletter.mobileengineer.io/p/mobile-engineers-youre-all-full-stack?r=g891u&triedRedirect=true) — Those Who Swift · Issue 248 — Article · Topics: Code Quality · Networking · Persistence & Synchronisation
  **Published:** `2026-01-08`
  **NeKI brief:** Examines Mobile Engineers, You’re All Full-Stack, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Eight Years with CloudKit](https://fatbobman.com/en/posts/my-eight-years-with-cloudkit) — Those Who Swift · Issue 245 — Article · Topics: Performance · Persistence & Synchronisation
  **Published:** `2025-12-17`
  **NeKI brief:** Examines Eight Years with CloudKit, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [swift-openapi-generator](https://github.com/apple/swift-openapi-generator) — Fatbobman’s Swift Weekly · Issue 115 — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2025-12-15T12:01:14.054Z`
  **NeKI brief:** Generates type-safe Swift client and server interfaces from OpenAPI descriptions, separating schema-driven transport code from application logic. Use it when a REST contract should drive refactors and reduce manual endpoint decoding.
- [ObjectBox](https://github.com/objectbox/objectbox-swift) — iOS Dev Tools · iOS Dev Tools: ObjectBox, RIB, Swon — Source repository · Topics: Developer Tools · Persistence & Synchronisation · Swift
  **Published:** `2025-12-04T17:28:54.311Z`
  **NeKI brief:** ObjectBox provides a typed Swift NoSQL API with relations, automatic schema migrations, cross-platform targets, and resource-conscious queries. Its on-device vector-search support makes the repository relevant when evaluating local persistence for large datasets or embedded AI features.
- [How SwiftData Represents AttributedString in Core Data Storage](https://medium.com/@djalex566/how-swiftdata-represents-attributedstring-in-core-data-storage-69036a4f166a) — SwiftLee Weekly · Issue 299 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `2025-11-25T15:16:48.000Z`
  **NeKI brief:** Explains How SwiftData Represents AttributedString in Core Data Storage, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [AcceptedSE-0491Module selectors for name disambiguation](https://github.com/apple/swift-evolution/blob/main/proposals/0491-module-selectors.md) — SwiftLee Weekly · Issue 293 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2025-10-14T14:14:22.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0491Module selectors for name disambiguation. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Swift Server Workgroup](https://www.swift.org/sswg) — iOS Dev Weekly · Issue 728 — Article · Topics: Developer Community & Business · Swift
  **Published:** `26th September 2025`
  **NeKI brief:** The Swift Server Workgroup coordinates ecosystem efforts for server-side Swift. Use it to discover supported libraries and governance context, not as an implementation reference.
- [How to Work with SwiftData in the Background in Swift 6](https://www.natashatherobot.com/p/swiftdata-background-swift-6) — Those Who Swift · Issue 228 — Article · Topics: AI Development · Swift · SwiftData
  **Published:** `2025-08-20`
  **NeKI brief:** Explains How to Work with SwiftData in the Background in Swift 6, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [GitHub repository](https://github.com/AvdLee/CoreDataBestPractices) — SwiftLee Weekly · Issue 282 — Source repository · Topics: Core Data · Developer Tools · Persistence & Synchronisation
  **Published:** `2025-07-29T14:14:45.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for GitHub repository. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [StructuredQueries](https://github.com/pointfreeco/swift-structured-queries) — Fatbobman’s Swift Weekly · Issue 89 — Source repository · Topics: Developer Tools · Swift · SwiftData
  **Published:** `2025-06-16T12:01:00.435Z`
  **NeKI brief:** StructuredQueries builds SQL with typed Swift structure while preserving SQL's expressive power. Use it when query composition needs compiler assistance but hiding relational behavior behind an ORM would make performance or migrations opaque.
- [SharingGRDB](https://github.com/pointfreeco/sharing-grdb) — Fatbobman’s Swift Weekly · Issue 89 — Source repository · Topics: Developer Tools · Swift · SwiftData
  **Published:** `2025-06-16T12:01:00.435Z`
  **NeKI brief:** SharingGRDB combines shared observable state with GRDB-backed SQLite persistence. Use it when SwiftUI features need low deployment targets and direct SQL control, noting that it does not provide mature cross-device synchronization.
- [DataScoutCompanion](https://github.com/alex566/DataScoutCompanion) — Fatbobman’s Swift Weekly · Issue 87 — Source repository · Topics: Developer Tools · Swift · SwiftData
  **Published:** `2025-06-07T12:01:11.599Z`
  **NeKI brief:** DataScoutCompanion is an open-source companion for inspecting application data during development. Use it when debugging data flows needs a dedicated in-app inspection surface rather than scattered temporary logging statements.
- [discussion thread](https://mjtsai.com/blog/2025/05/15/sqlite-databases-in-app-group-containers-dont) — Fatbobman’s Swift Weekly · Issue 84 — Article · Topics: Persistence & Synchronisation
  **Published:** `2025-05-19T12:00:44.196Z`
  **NeKI brief:** Investigates SQLite databases placed in App Group containers and the cross-process coordination risks involved. Use it when an app and extension share persistence, especially to validate locking, WAL behavior, and migration strategy.
- [SwiftData Predicates For Parent RelationshipsHow do you write SwiftData predicates to query for parent relationships.Use Your Loaf - iOS Development News & Tips](https://useyourloaf.com/blog/swiftdata-predicates-for-parent-relationships?ref=createwithswift.com) — Create with Swift · Issue 60 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `2025-05-09T15:30:59.000Z`
  **NeKI brief:** Builds a #Predicate over an optional SwiftData relationship by comparing the parent’s persistentModelID, then extends the pattern to multiple parent IDs. This is useful when CloudKit-compatible optional relationships must still support parameterized child queries.
- [Harmonize](https://github.com/perrystreetsoftware/Harmonize) — iOS Dev Tools · iOS Dev Tools: WinWinLinks, MMKV, Harmonize — Source repository · Topics: Developer Tools · Swift
  **Published:** `2025-05-08T14:22:48.081Z`
  **NeKI brief:** Harmonize coordinates shared state and communication across SwiftUI views, addressing the friction of passing bindings and environment values through deeper hierarchies. Its implementation is a concrete reference for reducing view wiring while keeping data flow explicit.
- [GRDB](https://github.com/groue/GRDB.swift) — Fatbobman’s Swift Weekly · Issue 81 — Source repository · Topics: Core Data · Swift · SwiftData
  **Published:** `2025-04-28T00:00:42.290Z`
  **NeKI brief:** GRDB.swift is a SQLite toolkit offering query interfaces, migrations, observations, and record mapping. Use it when an app needs transparent relational persistence and reactive database changes without SwiftData's deployment and sync assumptions.
- [DataScout](https://data-scout.pages.dev/) — iOS Dev Tools · iOS Dev Tools: AppsMan, ErrorKit, DataScout — Article · Topics: Core Data · Cross-Platform & Web · Persistence & Synchronisation
  **Published:** `2025-04-24T13:08:49.536Z`
  **NeKI brief:** Data Scout is a data-exploration project presented as a developer product. Inspect its concrete workflow when comparing small utility apps, data presentation choices, and the cost of maintaining a focused independent product.
- [Mastering Data Tracking and Notifications in Core Data and SwiftData](https://itnext.io/mastering-data-tracking-and-notifications-in-core-data-and-swiftdata-a21921ebfa9d?source=rss-b8c3000741------2) — Those Who Swift · Issue 209 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `2025-04-09`
  **NeKI brief:** Examines Mastering Data Tracking and Notifications in Core Data and SwiftData, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Modern URL construction in Swift](https://www.swiftbysundell.com/articles/modern-url-construction-in-swift?ref=createwithswift.com) — Create with Swift · Issue 55 — Article · Topics: Foundation & Data Formats · Swift
  **Published:** `2025-04-04T15:49:40.000Z`
  **NeKI brief:** Builds URLs with modern Foundation components rather than string concatenation. Use it when paths, query items, and percent encoding must remain correct under optional or user-provided values.
- [Swiftdata Architecture Patterns And PracticesBlog about iOS development and musings on technologyAzamSharpMohammad Azam](https://azamsharp.com/2025/03/28/swiftdata-architecture-patterns-and-practices.html?ref=createwithswift.com) — Create with Swift · Issue 55 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2025-04-04T15:49:40.000Z`
  **NeKI brief:** Explains Swiftdata Architecture Patterns And Practices, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Swiftdata Architecture Patterns And Practices](https://azamsharp.com/2025/03/28/swiftdata-architecture-patterns-and-practices.html) — SwiftLee Weekly · Issue 265 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2025-04-01T14:13:42.000Z`
  **NeKI brief:** Explains Swiftdata Architecture Patterns And Practices, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [ModelActor is Just Weird](https://www.massicotte.org/model-actor) — Those Who Swift · Issue 207 — Article · Topics: Concurrency · Swift · SwiftData
  **Published:** `2025-03-28`
  **NeKI brief:** Explains ModelActor is Just Weird, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Key Considerations Before Using SwiftData](https://fatbobman.com/en/posts/key-considerations-before-using-swiftdata?ref=createwithswift.com) — Create with Swift · Issue 52 — Article · Topics: Concurrency · Swift · SwiftData
  **Published:** `2025-03-14T17:00:20.000Z`
  **NeKI brief:** Evaluates SwiftData's practical limits before adoption. Use it when deciding whether its model, migration, query, or synchronization behavior fits a production persistence requirement.
- [UserDefaults and Observation in SwiftUI: How to Achieve Precise Responsiveness](https://itnext.io/userdefaults-and-observation-in-swiftui-how-to-achieve-precise-responsiveness-2bd8bda1568e) — Those Who Swift · Issue 205 — Article · Topics: Observation & State Management · Swift · SwiftUI
  **Published:** `2025-03-12`
  **NeKI brief:** Examines UserDefaults and Observation in SwiftUI: How to Achieve Precise Responsiveness, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Filtering SwiftData Models Using Enum](https://azamsharp.com/2025/01/23/filtering-swiftdata-models-using-enum.html?ref=createwithswift.com) — Create with Swift · Issue 46 — Article · Topics: Cross-Platform & Web · Swift · SwiftData
  **Published:** `2025-01-31T16:30:58.000Z`
  **NeKI brief:** Examines Filtering SwiftData Models Using Enum, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Filtering SwiftData Models Using Enum](https://azamsharp.com/2025/01/23/filtering-swiftdata-models-using-enum.html) — Those Who Swift · Issue 199 — Article · Topics: Cross-Platform & Web · Swift · SwiftData
  **Published:** `2025-01-30`
  **NeKI brief:** Examines Filtering SwiftData Models Using Enum, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Mogenerator](https://github.com/rentzsch/mogenerator) — iOS Dev Tools · iOS Dev Tools: Mogenerator, xcpretty, vscode-swift — Source repository · Topics: Core Data · Developer Tools · Objective-C & Cocoa
  **Published:** `2025-01-23T15:15:36.631Z`
  **NeKI brief:** mogenerator reads a Core Data model and generates separate machine and human subclasses for managed objects. Use it in legacy Core Data projects that need repeatable typed accessors while preserving hand-written behavior across model regeneration.
- [SwiftData CRUD Operations with ModelActor](https://brightdigit.com/tutorials/swiftdata-crud-operations-modelactor) — Those Who Swift · Issue 198 — Tutorial · Topics: Concurrency · Swift · SwiftData
  **Published:** `2025-01-23`
  **NeKI brief:** Examines SwiftData CRUD Operations with ModelActor, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [MongoKitten](https://github.com/orlandos-nl/MongoKitten) — Fatbobman’s Swift Weekly · Issue 65 — Source repository · Topics: Developer Tools · Foundation & Data Formats · Swift
  **Published:** `2025-01-06T12:02:39.656Z`
  **NeKI brief:** MongoKitten provides a pure-Swift MongoDB driver built on SwiftNIO. Follow it when evaluating asynchronous document-database access, connection lifecycle, and how a Swift server maps BSON operations into application models.
- [What was that doing in my database](https://eieio.games/essays/the-secret-in-one-million-checkboxes) — iOS Dev Weekly · Issue 692 — Article · Topics: Graphics, Media & Games · Persistence & Synchronisation
  **Published:** `20th December 2024`
  **NeKI brief:** Presents what was that doing in my database for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [TCA](https://github.com/pointfreeco/swift-composable-architecture) — Fatbobman’s Swift Weekly · Issue 61 — Source repository · Topics: Architecture · Composable Architecture · Swift
  **Published:** `2024-12-09T12:00:43.829Z`
  **NeKI brief:** The Composable Architecture structures feature state, actions, reducers, dependencies, and tests around explicit unidirectional flow. Use the repository and migration material to evaluate operational trade-offs before adopting or upgrading TCA in a production app.
- [Sharing](https://github.com/pointfreeco/swift-sharing) — Fatbobman’s Swift Weekly · Issue 61 — Source repository · Topics: Composable Architecture · Developer Tools · Swift
  **Published:** `2024-12-09T12:00:43.829Z`
  **NeKI brief:** Sharing provides `@Shared` state with persistence strategies spanning app storage, files, memory, and external stores. Follow it when routing shared SwiftUI/UIKit state while keeping observation and persistence concerns explicit.
- [Being Sendable with SwiftData](https://brightdigit.com/tutorials/swiftdata-sendable?issue=057) — Fatbobman’s Swift Weekly · Issue 57 — Tutorial · Topics: Concurrency · Swift · SwiftData
  **Published:** `2024-11-11T12:03:02.180Z`
  **NeKI brief:** Explains Sendable boundaries around SwiftData models and persistence access. Use it when concurrency checking exposes non-Sendable model crossings and you need to decide where actors or value projections belong.
- [Beware UserDefaults: a tale of hard to find bugs, and lost data](https://christianselig.com/2024/10/beware-userdefaults) — iOS Dev Weekly · Issue 683 — Article · Topics: Persistence & Synchronisation
  **Published:** `18th October 2024`
  **NeKI brief:** Presents beware userdefaults: a tale of hard to find bugs, and lost data for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [@ObservableDefaults](https://github.com/fatbobman/ObservableDefaults) — Fatbobman’s Swift Weekly · Issue 53 — Source repository · Topics: Observation & State Management · Swift · SwiftUI
  **Published:** `2024-10-14T12:03:14.201Z`
  **NeKI brief:** ObservableDefaults bridges UserDefaults-backed values into SwiftUI observation. Use it when app settings need reactive updates while retaining UserDefaults persistence and predictable key-level storage.
- [Chris Eidhof](https://m.objc.io/@chris) — Fatbobman’s Swift Weekly · Issue 53 — Article · Topics: Observation & State Management · Swift · SwiftUI
  **Published:** `2024-10-14T12:03:14.201Z`
  **NeKI brief:** Presents chris eidhof for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Beware UserDefaults: a tale of hard to find bugs, and lost data](https://christianselig.com/2024/10/beware-userdefaults?ref=createwithswift.com) — Create with Swift · Issue 31 — Article · Topics: Persistence & Synchronisation · Swift
  **Published:** `2024-10-11T15:30:29.000Z`
  **NeKI brief:** Presents beware userdefaults: a tale of hard to find bugs, and lost data for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [UserDefaults and Observation in SwiftUI: How to Achieve Precise Responsiveness](https://fatbobman.com/en/posts/userdefaults-and-observation?ref=createwithswift.com) — Create with Swift · Issue 31 — Article · Topics: Observation & State Management · Swift · SwiftUI
  **Published:** `2024-10-11T15:30:29.000Z`
  **NeKI brief:** Observation does not automatically make UserDefaults changes precise inside SwiftUI. The @ObservableDefaults approach bridges key reads and writes into tracked properties, avoiding broad invalidation while retaining UserDefaults persistence semantics.
- [ObservableDefaults library](https://github.com/fatbobman/ObservableDefaults?ref=createwithswift.com) — Create with Swift · Issue 31 — Source repository · Topics: Developer Tools · Observation & State Management · Swift
  **Published:** `2024-10-11T15:30:29.000Z`
  **NeKI brief:** ObservableDefaults bridges UserDefaults-backed values into SwiftUI observation. Use it when app settings need reactive updates while retaining UserDefaults persistence and predictable key-level storage.
- [The weirdest Core Data crash I have seen](https://nemecek.be/blog/207/the-weirdest-core-data-crash-i-have-seen) — iOS Dev Weekly · Issue 678 — Article · Topics: Core Data · Persistence & Synchronisation
  **Published:** `13th September 2024`
  **NeKI brief:** Presents the weirdest core data crash i have seen for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Considerations for Using Codable and Enums in SwiftData Models](https://fatbobman.com/en/posts/considerations-for-using-codable-and-enums-in-swiftdata-models?ref=createwithswift.com) — Create with Swift · Issue 25 — Article · Topics: Foundation & Data Formats · Swift · SwiftData
  **Published:** `2024-08-30T15:00:43.000Z`
  **NeKI brief:** SwiftData stores Codable structs and enums through generated persistence representations, which affects predicates, migrations, and queryability. The examples expose where convenient model types become opaque storage and when a normalized property is safer.
- [Displaying Data with Table](https://captainswiftui.substack.com/p/displaying-data-with-table-part-i?r=a1d9l&triedRedirect=true) — SwiftUI Weekly · SwiftUI Weekly - Issue #195 — Article · Topics: Persistence & Synchronisation · Swift · SwiftUI
  **Published:** `2024-08-05T15:18:59.956Z`
  **NeKI brief:** Introduces SwiftUI Table for displaying structured rows and columns. Useful for macOS or iPad data-heavy screens where List cannot express comparative fields clearly.
- [SQLite.swift](https://github.com/stephencelis/SQLite.swift) — iOS Dev Tools · iOS Dev Tools: Sw!ftalyzer, Invoice Maker, SQLite.swift — Source repository · Topics: Developer Tools · Persistence & Synchronisation · Swift
  **Published:** `2024-05-30T15:20:30.896Z`
  **NeKI brief:** SQLite.swift wraps SQLite3 in typed Swift query builders and value bindings rather than raw SQL strings alone. Use it when a lightweight relational store needs explicit schemas and transactions without adopting a full object-relational framework.
- [@LiveModel in SwiftData](https://patstechweblog.com/posts/2-live-model?issue=031) — Fatbobman’s Swift Weekly · Issue 32 — Article · Topics: Swift · SwiftData · SwiftUI
  **Published:** `2024-05-20T12:02:52.341Z`
  **NeKI brief:** The article explores a SwiftData `@LiveModel` pattern for keeping model-backed UI current. Follow it when separating observation updates from persistence operations and checking whether a custom wrapper adds value beyond native model observation.
- [Reducing iOS Test execution time with Selective Testing](https://levelup.gitconnected.com/reducing-ios-test-execution-time-with-selective-testing-384879e5f243?issue=031) — Fatbobman’s Swift Weekly · Issue 32 — Article · Topics: Concurrency · Swift · Testing
  **Published:** `2024-05-20T12:02:52.341Z`
  **NeKI brief:** Explains selective testing as a way to shorten iOS test feedback cycles by choosing affected tests. Use it to discuss CI optimization, validating its heuristics against the project's dependency graph and failure-reporting needs.
- [Creating Settings Screen in SwiftUI With AppStorage](https://holyswift.app/using-userdefaults-to-persist-in-swiftui) — SwiftUI Weekly · SwiftUI Weekly - Issue #186 — Article · Topics: Persistence & Synchronisation · Swift · SwiftUI
  **Published:** `2024-05-15T12:55:37.453Z`
  **NeKI brief:** Shows persisting SwiftUI settings with AppStorage and UserDefaults. Useful for small preferences whose lifetime should survive launches without introducing a database model.
- [Creating Settings Screen in SwiftUI With AppStorage](https://holyswift.app/using-userdefaults-to-persist-in-swiftui?ref=createwithswift.com) — Create with Swift · Issue 12 — Article · Topics: Persistence & Synchronisation · Swift · SwiftUI
  **Published:** `2024-05-10T15:00:28.000Z`
  **NeKI brief:** Shows persisting SwiftUI settings with AppStorage and UserDefaults. Useful for small preferences whose lifetime should survive launches without introducing a database model.
- [The Composable Architecture: My 3 Year Experience](https://rodschmidt.com/posts/composable-architecture-experience?issue=030) — Fatbobman’s Swift Weekly · Issue 30 — Article · Topics: Architecture · Composable Architecture · Objective-C & Cocoa
  **Published:** `2024-05-06T12:01:46.954Z`
  **NeKI brief:** A three-year TCA retrospective surfaces production trade-offs that API introductions omit, including architectural discipline and maintenance cost. Use it to evaluate long-lived team fit rather than reading it as a generic framework endorsement.
- [Subscribing to SwiftData changes outside SwiftUI](https://www.finnvoorhees.com/words/subscribing-to-swiftdata-changes-outside-swiftui) — iOS Dev Weekly · Issue 659 — Article · Topics: Swift · SwiftData · SwiftUI
  **Published:** `3rd May 2024`
  **NeKI brief:** Presents subscribing to swiftdata changes outside swiftui for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
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
- [Screen vs View in SwiftUI](https://scottsmithdev.com/screen-vs-view-in-swiftui) — iOS Dev Weekly · Issue 647 — Article · Topics: Core Data · Swift · SwiftUI
  **Published:** `9th February 2024`
  **NeKI brief:** Contrasts screen-level composition with reusable SwiftUI views and gives naming and responsibility boundaries that help keep navigation and presentation code maintainable.
- [How to Play Spatial Video On iOS 17.2](https://xreality.zone/zh/posts/how-to-play-spatial-video-on-ios-17-2) — Fatbobman’s Swift Weekly · Issue 12 — Tutorial · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **Published:** `2023-12-25T22:00:09.856Z`
  **NeKI brief:** Demonstrates playing spatial video on iOS 17.2 and discusses the media and device prerequisites involved. Use it to investigate immersive-video playback paths while verifying format support and availability against current Apple APIs.
- [Integrating Haptic Feedback In SwiftUI Projects](https://serialcoder.dev/text-tutorials/swiftui/integrating-haptic-feedback-in-swiftui-projects) — Fatbobman’s Swift Weekly · Issue 12 — Tutorial · Topics: Swift · SwiftData · SwiftUI
  **Published:** `2023-12-25T22:00:09.856Z`
  **NeKI brief:** Shows how to trigger haptic feedback from SwiftUI interactions by bridging to the appropriate UIKit feedback generators. Follow it when adding tactile confirmation while keeping feedback timing, accessibility, and device capability checks explicit.
- [App Localizations](https://www.youtube.com/watch?v=kbgNL7VrQPo) — SwiftUI Weekly · SwiftUI Weekly - Issue #170 — Video · Topics: Graphics, Media & Games · Localization · Swift
  **Published:** `2023-12-11T13:23:19.560Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Distributing Work Between Actors](https://jackmorris.xyz/posts/2023/11/06/distributing-work-between-actors) — iOS Dev Weekly · Issue 636 — Article · Topics: Concurrency · Persistence & Synchronisation
  **Published:** `17th November 2023`
  **NeKI brief:** Presents distributing work between actors for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
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
- [@Model for CoreData](https://www.alwaysrightinstitute.com/managedmodels) — iOS Dev Weekly · Issue 629 — Article · Topics: Core Data · Persistence & Synchronisation · Swift
  **Published:** `29th September 2023`
  **NeKI brief:** Presents @model for coredata for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Unlocking Advanced Core Data Features in SwiftData](https://itnext.io/swiftdatakit-unleashing-advanced-core-data-features-in-swiftdata-3fcd5f443c99) — iOS Dev Weekly · Issue 626 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `8th September 2023`
  **NeKI brief:** Presents unlocking advanced core data features in swiftdata for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [The Ultimate Guide to Building SwiftData Applications](https://azamsharp.com/2023/07/04/the-ultimate-swift-data-guide.html) — SwiftUI Weekly · SwiftUI Weekly - Issue #151 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `2023-07-17T21:13:35.306Z`
  **NeKI brief:** Provides a broad SwiftData walkthrough covering model declaration, persistence, and cloud-sync-oriented concepts introduced at WWDC 2023. Useful for mapping Core Data requirements to SwiftData before committing to a migration or new model layer.
- [SwiftData Suprises](https://jsorge.net/2023/06/30/swiftdata-surprises) — iOS Dev Weekly · Issue 617 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `7th July 2023`
  **NeKI brief:** Explores SwiftData Suprises, focusing on understanding new frameworks is always important, but understanding new data storage frameworks is especially important!. Follow it to assess the approach, its trade-offs, and where it fits in a current Swift or Apple-platform project.
- [Build an app using SwiftData](https://www.youtube.com/playlist?list=PLvUWi5tdh92wZ5_iDMcBpenwTgFNan9T7) — iOS Dev Weekly · Issue 617 — Video · Topics: Apple Platform Ecosystem · Swift · SwiftData
  **Published:** `7th July 2023`
  **NeKI brief:** Uses State, Binding, ObservableObject, StateObject, and EnvironmentObject in practical SwiftUI data-flow examples. Follow it to compare ownership and propagation choices when a view hierarchy has multiple sources of mutable state.
- [Relationships In SwiftData](https://www.youtube.com/watch?v=_QMalUGTM4E&feature=youtu.be) — SwiftUI Weekly · SwiftUI Weekly - Issue #148 — Video · Topics: Graphics, Media & Games · Swift · SwiftData
  **Published:** `2023-06-28T11:49:47.378Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [GitHub Dependency Graph, Dependabot Alerts, and Advisory Database now support Swift advisories](https://github.blog/changelog/2023-06-19-dependency-graph-dependabot-alerts-and-advisory-database-now-support-swift-advisories) — iOS Dev Weekly · Issue 615 — Article · Topics: Developer Tools · Persistence & Synchronisation · Swift
  **Published:** `23rd June 2023`
  **NeKI brief:** Explores GitHub Dependency Graph, Dependabot Alerts, and Advisory Database now support Swift advisories, focusing on if you have worked with other languages, you’ve likely come. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [What I Learned Writing My Own CloudKit Syncing Library](https://ryanashcraft.com/what-i-learned-writing-my-own-cloudkit-sync-library) — iOS Dev Weekly · Issue 605 — Article · Topics: Core Data · Persistence & Synchronisation
  **Published:** `14th April 2023`
  **NeKI brief:** Shares lessons from building an open-source CloudKit synchronization library, including the practical complexity hidden behind sync-enabled apps. Follow it when comparing a custom sync layer with direct CloudKit use and identifying the design decisions the abstraction must own.
- [Advanced Data Protection and CloudKit](https://blog.justtact.com/advanced-data-protection) — iOS Dev Weekly · Issue 593 — Article
  **Published:** `20th January 2023`
  **NeKI brief:** Explores Advanced Data Protection and CloudKit, focusing on when apple introduced advanced data protection at the end of. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [The Lighter Swift Codegen for SQLite3](https://www.alwaysrightinstitute.com//lighter) — iOS Dev Weekly · Issue 572 — Article · Topics: Developer Tools · Persistence & Synchronisation · Swift
  **Published:** `19th August 2022`
  **NeKI brief:** Explores The Lighter Swift Codegen for SQLite3, focusing on there’s a lot going on in this post from helge. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Exporting data from Unified Logging System in Swift](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3N3aWZ0d2l0aG1hamlkLmNvbS8yMDIyLzA0LzE5L2V4cG9ydGluZy1kYXRhLWZyb20tdW5pZmllZC1sb2dnaW5nLXN5c3RlbS1pbi1zd2lmdC8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiI3Zjg1ZDc1Ny0xZjZhLTRmODItOTcyYi1iMGRhZDIzOWE2ZmIiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiODFjMmM0MWMtODZhOC00NWM4LThmOTEtMzcxOWE2ZWRhZDI0IiwiaWF0IjoxNjc0MDYyNTU5LjIxOCwiaXNzIjoib3JjaGlkIn0.0LDRJdpcern5h3_dv7zNRck3LYVsnUu2ZnWXBtQRpfg) — SwiftUI Weekly · SwiftUI Weekly - Issue #100 — Article · Topics: Persistence & Synchronisation · Swift
  **Published:** `2022-04-25T10:00:02.000Z`
  **NeKI brief:** Demonstrates exporting Unified Logging data for inspection outside the running app. Useful when diagnosing production behavior, collecting reproducible evidence, and turning OSLog output into shareable debugging artifacts.
- [Clash of the Optionals](https://atomicbird.com/blog/clash-of-the-optionals) — iOS Dev Weekly · Issue 543 — Article · Topics: Core Data · Persistence & Synchronisation · Swift
  **Published:** `28th January 2022`
  **NeKI brief:** Explores Clash of the Optionals, focusing on the article discusses heard you like optionals, so i put an optional in your optional. Follow it to assess the approach, its trade-offs, and where it fits in a current Swift or Apple-platform project.
- [follow up post from Jesse Squires](https://www.jessesquires.com/blog/2022/01/26/core-data-optionals) — iOS Dev Weekly · Issue 543 — Article · Topics: Core Data · Persistence & Synchronisation · Swift
  **Published:** `28th January 2022`
  **NeKI brief:** Explores follow up post from Jesse Squires, focusing on the article discusses heard you like optionals, so i put an optional in your optional. Follow it to assess the approach, its trade-offs, and where it fits in a current Swift or Apple-platform project.
- [Building a music recognization app in SwiftUI with ShazamKit](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3N3YXBuYW5pbGRob2wubWVkaXVtLmNvbS9idWlsZGluZy1hLW11c2ljLXJlY29nbml6YXRpb24tYXBwLWluLXN3aWZ0dWktd2l0aC1zaGF6YW1raXQtN2NhYjc2NDA3ZDEwP3V0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiOTg1NDJmZTMtOWU5Zi00ZmY4LTk5YzAtNDQ4NzU3M2JkNjQyIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6ImUwZDE2NzkyLTFmZjUtNGEyMS05ODRjLTRlOTQxOGI5YTM5ZSIsImlhdCI6MTY3NDA2MjY3Ny4wMSwiaXNzIjoib3JjaGlkIn0.D1X3KuG_ZZVBpnjLs42Pwiu20YFyMkC-z5viuvXke6c) — SwiftUI Weekly · SwiftUI Weekly - Issue #63 — Tutorial · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **Published:** `2021-06-14T22:35:11.000Z`
  **NeKI brief:** Builds a SwiftUI music-recognition app around ShazamKit. Follow it to see how capture, matching results, permissions, and asynchronous updates are connected to observable UI state.
- [Here is what SwiftData will be…](https://drewmccormack.medium.com/here-is-what-swiftdata-will-be-and-what-it-could-have-been-65b79cd11c6a) — iOS Dev Weekly · Issue 509 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `28th May 2021`
  **NeKI brief:** Explores Here is what SwiftData will be…, focusing on that’s a bold title from drew mccormack! a new swiftui. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
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
- [Profiling SwiftUI app using Instruments](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3N3aWZ0d2l0aG1hamlkLmNvbS8yMDIxLzAxLzIwL3Byb2ZpbGluZy1zd2lmdHVpLWFwcC11c2luZy1pbnN0cnVtZW50cy8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiJmNDMyNzc3Ny02M2Q2LTQ1MDQtOWVkMC1lYTgwYzM4ZmVlZDUiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiMjVjODkyZTUtYTM5OC00YWVmLWFkMWEtMzYzZTkzNWE1OGJhIiwiaWF0IjoxNjc0MDYyNjc5LjQ1OSwiaXNzIjoib3JjaGlkIn0.yFE0lXxlheNBniRXd2cVmx609ueoWFP89URqNlmr9lo) — SwiftUI Weekly · SwiftUI Weekly - Issue #43 — Article · Topics: Performance · Swift · SwiftUI
  **Published:** `2021-01-26T13:13:48.000Z`
  **NeKI brief:** Uses Instruments to profile SwiftUI performance. Use it when a view-update or rendering problem needs measured call stacks and allocation evidence instead of intuition about declarative UI cost.
- [Core Data by Tutorials](https://www.raywenderlich.com/books/core-data-by-tutorials) — iOS Dev Weekly · Issue 484 — Tutorial · Topics: Core Data · Observation & State Management · Persistence & Synchronisation
  **Published:** `27th November 2020`
  **NeKI brief:** Examines Core Data by Tutorials, offering practical guidance on data modeling and persistence trade-offs. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Price Testing for Subscription Apps](https://www.revenuecat.com/blog/price-testing-for-subscription-apps) — iOS Dev Weekly · Issue 467 — Article · Topics: App Distribution & Store Operations · Persistence & Synchronisation · Testing
  **Published:** `31st July 2020`
  **NeKI brief:** Covers Price Testing for Subscription Apps, focusing on testing, diagnostics, and feedback quality. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [Propagating user-facing errors in Swift](https://swiftbysundell.com/articles/propagating-user-facing-errors-in-swift) — iOS Dev Weekly · Issue 456 — Tutorial · Topics: Core Data · Developer Community & Business · Swift
  **Published:** `15th May 2020`
  **NeKI brief:** Examines Propagating user-facing errors in Swift, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Using CoreData with SwiftUI](https://augmentedcode.io/2020/01/19/using-coredata-with-swiftui) — iOS Dev Weekly · Issue 441 — Article · Topics: Core Data · Persistence & Synchronisation · Swift
  **Published:** `31st January 2020`
  **NeKI brief:** Walks through connecting Core Data fetches and managed-object context to SwiftUI views. Use it to inspect ownership and update-flow choices, then adapt the pattern to the app’s concurrency and persistence model.
- [AQUI](https://github.com/AlanQuatermain/AQUI) — iOS Dev Weekly · Issue 432 — Source repository · Topics: Core Data · Persistence & Synchronisation · Swift
  **Published:** `29th November 2019`
  **NeKI brief:** Examines AQUI, focusing on jim dovey on how to make swiftui and core data play nicely together using his aqui library. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Five tips and tricks for CloudKit Sharing](https://contagious.dev/blog/cloudkit-sharing-five-tips-and-tricks) — iOS Dev Weekly · Issue 427 — Article · Topics: Persistence & Synchronisation
  **Published:** `25th October 2019`
  **NeKI brief:** Examines Five tips and tricks for CloudKit Sharing, offering practical guidance on data modeling and persistence trade-offs. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [LLVS project](https://github.com/mentalfaculty/LLVS) — iOS Dev Weekly · Issue 424 — Source repository · Topics: Apple Platform Ecosystem · Combine & Reactive Programming · Persistence & Synchronisation
  **Published:** `4th October 2019`
  **NeKI brief:** Examines LLVS project, focusing on one topic that has been talked about consistently since wwdc is how core data (or any data persistence framework) will be…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [The Curious Case of the Core Data Crash](https://blog.iconfactory.com/2019/08/the-curious-case-of-the-core-data-crash) — iOS Dev Weekly · Issue 419 — Article · Topics: Concurrency · Core Data · Developer Tools
  **Published:** `30th August 2019`
  **NeKI brief:** Examines The Curious Case of the Core Data Crash, offering practical guidance on data modeling and persistence trade-offs. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Getting Started With NSPersistentCloudKitContainer](https://www.andrewcbancroft.com/blog/ios-development/data-persistence/getting-started-with-nspersistentcloudkitcontainer) — iOS Dev Weekly · Issue 416 — Article · Topics: Core Data · Persistence & Synchronisation · Personal Essays
  **Published:** `9th August 2019`
  **NeKI brief:** Examines Getting Started With NSPersistentCloudKitContainer, offering practical guidance on data modeling and persistence trade-offs. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [announcement of v4 this week](https://forums.swift.org/t/new-release-grdb-4-0-0/24798) — iOS Dev Weekly · Issue 405 — Article · Topics: Persistence & Synchronisation · Swift
  **Published:** `24th May 2019`
  **NeKI brief:** Examines announcement of v4 this week, focusing on the author’s note that hadn’t come across gwendal roué’s sqlite wrapper for swift until i saw the announcement of v4 this week. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [well documented](https://github.com/groue/GRDB.swift/blob/master/README.md) — iOS Dev Weekly · Issue 405 — Source repository · Topics: Developer Tools · Persistence & Synchronisation · Swift
  **Published:** `24th May 2019`
  **NeKI brief:** Examines well documented, focusing on the author’s note that hadn’t come across gwendal roué’s sqlite wrapper for swift until i saw the announcement of v4 this week. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
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
- [IceCream](https://github.com/caiyue1993/IceCream) — iOS Dev Weekly · Issue 329 — Source repository · Topics: Developer Tools · Persistence & Synchronisation
  **Published:** `1st December 2017`
  **NeKI brief:** Examines IceCream, focusing on if you’ve been holding off on syncing your realm database with cloudkit thinking it requires a lot of work, well you’re…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Modeling one-to-many in SQlite using the JSON1 extension](http://blog.benjamin-encz.de/post/sqlite-one-to-many-json1-extension) — iOS Dev Weekly · Issue 324 — Article · Topics: Persistence & Synchronisation
  **Published:** `27th October 2017`
  **NeKI brief:** Explores Modeling one-to-many in SQlite using the JSON1 extension in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Better NSUserDefaults with Swift](http://www.xs-labs.com/en/blog/2017/10/08/better-nsuserdefaults-with-swift) — iOS Dev Weekly · Issue 322 — Article · Topics: Persistence & Synchronisation · Swift
  **Published:** `13th October 2017`
  **NeKI brief:** Explores Better NSUserDefaults with Swift in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [PersistentStorageSerializable](https://github.com/IvanRublev/PersistentStorageSerializable) — iOS Dev Weekly · Issue 296 — Source repository · Topics: Developer Tools · Swift
  **Published:** `14th April 2017`
  **NeKI brief:** Examines PersistentStorageSerializable, focusing on ivan rublev with a swift library that makes it easy to automatically serialize user preferences with userdefaults or a plist. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
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
- [Swifty APIs: NSUserDefaults](http://radex.io/swift/nsuserdefaults) — iOS Dev Weekly · Issue 182 — Article · Topics: Persistence & Synchronisation · Swift
  **Published:** `23rd January 2015`
  **NeKI brief:** Explains Swifty APIs NSUserDefaults with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Swifty Methods article](http://radex.io/swift/methods) — iOS Dev Weekly · Issue 182 — Article · Topics: Swift
  **Published:** `23rd January 2015`
  **NeKI brief:** Explains Swifty methods with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [great documentation](https://github.com/stephencelis/SQLite.swift/blob/master/Documentation/Index.md) — iOS Dev Weekly · Issue 173 — Source repository · Topics: Developer Tools · Persistence & Synchronisation · Swift
  **Published:** `21st November 2014`
  **NeKI brief:** Provides the great documentation source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [About iCloud changes in 1Password 5](http://blog.agilebits.com/2014/10/21/about-icloud-changes-in-1password-5) — iOS Dev Weekly · Issue 169 — Article · Topics: Developer Community & Business · Security & Privacy
  **Published:** `24th October 2014`
  **NeKI brief:** Explains About iCloud changes in 1Password 5 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Seeking Continuity with iOS 8 & Yosemite](https://medium.com/@distefam/seeking-continuity-with-ios-8-yosemite-dff213083f16) — iOS Dev Weekly · Issue 168 — Article · Topics: Persistence & Synchronisation · Personal Essays · Security & Privacy
  **Published:** `17th October 2014`
  **NeKI brief:** Explains Seeking Continuity with iOS 8 Yosemite with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Treehouse: Code Better iOS Apps](http://teamtreehouse.com/join/ios-development?cid=2672) — iOS Dev Weekly · Issue 159 — Tutorial · Topics: Core Data · Networking · Persistence & Synchronisation
  **Published:** `15th August 2014`
  **NeKI brief:** Explains Treehouse Code Better iOS Apps with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Jazzy](https://github.com/realm/jazzy) — iOS Dev Weekly · Issue 155 — Source repository · Topics: Developer Tools · Persistence & Synchronisation
  **Published:** `18th July 2014`
  **NeKI brief:** Jazzy generates Apple-style API documentation from Swift and Objective-C source, including symbol graphs, declarations, and Markdown comments. The repository is useful when setting up repeatable documentation generation as part of a library or CI release pipeline.
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
- [Masonry](https://github.com/cloudkite/Masonry) — iOS Dev Weekly · Issue 104 — Source repository · Topics: Developer Tools · Persistence & Synchronisation
  **Published:** `26th July 2013`
  **NeKI brief:** Provides the Masonry source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
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
- [GVUserDefaults](https://github.com/gangverk/GVUserDefaults) — iOS Dev Weekly · Issue 73 — Source repository · Topics: Developer Tools
  **Published:** `21st December 2012`
  **NeKI brief:** Provides the GVUserDefaults source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [TouchDB-iOS](https://github.com/couchbaselabs/TouchDB-iOS) — iOS Dev Weekly · Issue 67 — Source repository · Topics: Developer Tools · Persistence & Synchronisation
  **Published:** `9th November 2012`
  **NeKI brief:** Provides the TouchDB-iOS source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
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
- [Lockbox](https://github.com/granoff/Lockbox) — iOS Dev Weekly · Issue 39 — Source repository · Topics: Developer Tools · Persistence & Synchronisation · Security & Privacy
  **Published:** `27th April 2012`
  **NeKI brief:** Provides the Lockbox source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Core Data Queries Using Expressions](http://useyourloaf.com/blog/2012/1/19/core-data-queries-using-expressions.html) — iOS Dev Weekly · Issue 26 — Article · Topics: Core Data · Cross-Platform & Web · Persistence & Synchronisation
  **Published:** `27th January 2012`
  **NeKI brief:** Explains Core Data Queries Using Expressions with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [MagicalRecord](https://github.com/magicalpanda/MagicalRecord) — iOS Dev Weekly · Issue 18 — Source repository · Topics: Core Data · Developer Tools · Persistence & Synchronisation
  **Published:** `2nd December 2011`
  **NeKI brief:** Provides the MagicalRecord source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [How to import contacts into the iPhone Simulator](http://www.icodeblog.com/2011/11/09/how-to-import-contacts-into-the-iphone-simulator) — iOS Dev Weekly · Issue 16 — Article · Topics: Objective-C & Cocoa · Persistence & Synchronisation
  **Published:** `18th November 2011`
  **NeKI brief:** Explains How to import contacts into the iPhone Simulator with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [Make Keychain as easy to use as NSUserDefaults](https://github.com/carlbrown/PDKeychainBindingsController) — iOS Dev Weekly · Issue 2 — Source repository · Topics: Developer Tools · Persistence & Synchronisation · Security & Privacy
  **Published:** `12th August 2011`
  **NeKI brief:** Provides the Make Keychain as easy to use as NSUserDefaults source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Transient Entities and Core Data](http://www.cimgf.com/2011/08/08/transient-entities-and-core-data) — iOS Dev Weekly · Issue 2 — Article · Topics: Core Data · Objective-C & Cocoa · Persistence & Synchronisation
  **Published:** `12th August 2011`
  **NeKI brief:** Explains Transient Entities and Core Data with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Exposed Moltbook Database Let Anyone Take Control of Any AI Agent on the Site](https://www.404media.co/exposed-moltbook-database-let-anyone-take-control-of-any-ai-agent-on-the-site) — Not only Swift · Issue 92 — Article · Topics: AI Development · Persistence & Synchronisation
  **NeKI brief:** This article covers a Moltbook database exposure that enabled AI-agent takeover. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [CodeEditorView: A SwiftUI Code Editor for iOS, visionOS, and macOS](https://github.com/mchakravarty/CodeEditorView) — Not only Swift · Issue 79 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Presents a concrete implementation of CodeEditorView: A SwiftUI Code Editor for iOS, visionOS, and macOS. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.
