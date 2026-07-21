# Peter Friese articles

Third-party source index. It provides source attribution and routing metadata, not republished article content. Verify article conclusions independently before applying them.

- Archive: [https://peterfriese.dev/](https://peterfriese.dev/)
- Last collected: `2026-07-22T09:47:03Z`
- Indexed entries: **42**

- [Agentic Coding in Xcode with Gemini CLI](https://peterfriese.dev/blog/2026/agentic-coding-xcode-geminicli)
  **NeKI brief:** Connects Gemini CLI to Xcode 26.3 through Apple's MCP bridge and walks through an emoji physics example. The setup highlights version and response-format requirements that matter when using agents other than Xcode's built-in integrations.
- [Understanding SwiftUI Preferences](https://peterfriese.dev/blog/2025/swiftui-preferences-swift6)
  **NeKI brief:** Explains SwiftUI Preferences as an upward data channel from child views to ancestors, with Swift 6 examples. It is useful for designing reusable components that report measurements or actions without tight parent-child coupling.
- [Creating a reusable action menu component in SwiftUI](https://peterfriese.dev/blog/2025/swiftui-action-menu)
  **NeKI brief:** Builds a reusable SwiftUI action menu with a view builder and sheet presentation, turning a one-off menu into a component with an explicit content contract. Follow it for composition patterns, not as a substitute for platform menu guidance.
- [Reverse-Engineering Xcode's Coding Intelligence prompt](https://peterfriese.dev/blog/2025/reveng-xcode-coding-intelligence)
  **NeKI brief:** Inspects Xcode's Coding Intelligence prompt to show how project context and instructions shape generated code. The reverse-engineering perspective helps teams reason about agent inputs and reproducibility while avoiding assumptions about undocumented internals.
- [Turn Your Photos Into Miniature Magic with Nano Banana](https://peterfriese.dev/blog/2025/gemini-nano-banana-ios)
  **NeKI brief:** Demonstrates integrating Gemini's Nano Banana image generation into an iOS app to transform photos into miniature scenes. Useful for evaluating an image-generation feature end to end, including prompt construction, media handling, latency, and product safeguards.
- [Extracting structured data from PDFs using Gemini 2.0 and Genkit](https://peterfriese.dev/blog/2025/gemini-genkit-pdf-structured-data)
  **NeKI brief:** Demonstrates extracting structured data from PDFs with Gemini 2.0 and Genkit. Useful for assessing document-ingestion workflows, schema validation, and error handling before integrating model-produced fields into an app's trusted domain model.
- [Creating custom SF Symbols using the SF Symbols app](https://peterfriese.dev/blog/2025/custom-sf-symbols)
  **NeKI brief:** Creates custom SF Symbols-style artwork and integrates it with SwiftUI symbol effects. Useful when system symbols lack a domain icon, while preserving consistent scaling and state animation.
- [SwiftUI Hero Animations with NavigationTransition](https://peterfriese.dev/blog/2024/hero-animation)
  **NeKI brief:** Recreates an App Store-style hero transition with SwiftUI's NavigationTransition APIs, tying source and destination identity to the animation. The example is a practical reference for coordinating navigation state with matched visual elements.
- [Improve your app's UX with SwiftUI's task view modifier](https://peterfriese.dev/blog/2024/delay-task-modifier)
  **NeKI brief:** Implements a delayed task modifier that cancels prior work when the input changes. Useful for debounced search and validation, where task identity and cancellation prevent stale results.
- [Styling SwiftUI Views](https://peterfriese.dev/blog/2023/swiftui-styling-views)
  **NeKI brief:** Defines custom SwiftUI styles for built-in controls by separating configuration from appearance, then applies them consistently across a view hierarchy. The technique scales better than repeating modifier chains at each call site.
- [Previewing Stateful SwiftUI Views](https://peterfriese.dev/blog/2022/swiftui-previews-interactive)
  **NeKI brief:** Shows how to supply mutable preview state for views that depend on Binding, turning Xcode previews into an interactive harness. The setup is useful for exercising UI behavior without launching the full application.
- [Networking with Combine and SwiftUI](https://peterfriese.dev/blog/2022/swiftui-combine-networking-gettingstarted)
  **NeKI brief:** Connects a Combine URL-loading pipeline to SwiftUI state, covering publisher composition and delivery before rendering remote results. It is historical Combine guidance that helps maintain older code while planning an async/await migration.
- [Error Handling with Combine and SwiftUI](https://peterfriese.dev/blog/2022/swiftui-combine-networking-errorhandling)
  **NeKI brief:** A Combine networking pipeline can map transport, decoding, and domain failures into one UI-facing error model before publishing state to SwiftUI. The workflow keeps retry and presentation decisions out of low-level URLSession callbacks.
- [Optimise your networking layer with Combine](https://peterfriese.dev/blog/2022/swiftui-combine-networking-efficient)
  **NeKI brief:** A Combine networking layer becomes more efficient by sharing work and avoiding duplicate subscriptions for the same request. The article turns request lifetime, replay, and cancellation into explicit pipeline choices rather than accidental publisher behavior.
- [Building a Custom Combine Operator for Exponential Backoff](https://peterfriese.dev/blog/2022/swiftui-combine-custom-operators)
  **NeKI brief:** The exponential-backoff operator schedules retries with increasing delays while keeping retry policy composable in a Combine chain. Its value is making timing and termination explicit, rather than hiding repeated requests inside ad-hoc recursion.
- [Calling asynchronous Firebase APIs from Swift](https://peterfriese.dev/blog/2022/firebase-async-calls-swift)
  **NeKI brief:** Demonstrates bridging Firebase completion-handler APIs into Swift async functions, preserving thrown errors and return values at the call site. Follow it when isolating callback adapters from the rest of a structured-concurrency codebase.
- [Asynchronous programming with SwiftUI and Combine](https://peterfriese.dev/blog/2022/combine-vs-async)
  **NeKI brief:** Bridging asynchronous work between Combine and Swift concurrency exposes a boundary between stream composition and structured task lifetime. The comparison helps choose one owner for cancellation and avoid accidentally subscribing and awaiting the same operation twice.
- [Swipe Actions in SwiftUI 3](https://peterfriese.dev/blog/2021/swiftui-listview-part4)
  **NeKI brief:** SwiftUI swipe actions attach destructive or secondary commands to a row while the system supplies gesture behavior and accessibility affordances. The article shows where action roles belong and why custom gesture replicas lose platform consistency.
- [Styling List Views](https://peterfriese.dev/blog/2021/swiftui-listview-part3)
  **NeKI brief:** SwiftUI list styling is split between row content, list-wide modifiers, and platform-specific container behavior. The examples help isolate which visual requirement belongs to the row and which is controlled by the enclosing List implementation.
- [Building Dynamic Lists in SwiftUI](https://peterfriese.dev/blog/2021/swiftui-listview-part2)
  **NeKI brief:** Builds a dynamic SwiftUI List with asynchronous loading, pull-to-refresh, searching, and editable rows. The example illustrates how list identity and state updates must cooperate when remote data changes underneath active editing.
- [Building Static Lists in SwiftUI](https://peterfriese.dev/blog/2021/swiftui-listview-part1)
  **NeKI brief:** Static SwiftUI lists are built by composing identifiable rows rather than manually managing index paths and cell reuse. The trade-off is declarative simplicity, with identity becoming the key requirement for stable updates.
- [SwiftUI List Bindings](https://peterfriese.dev/blog/2021/swiftui-list-item-bindings-behind-the-scenes)
  **NeKI brief:** Explains how SwiftUI derives bindings for individual collection elements and why stable identity matters when rows mutate. The discussion helps diagnose disappearing edits or index-based binding bugs in editable lists.
- [Managing Focus in SwiftUI List Views](https://peterfriese.dev/blog/2021/swiftui-list-focus)
  **NeKI brief:** Uses FocusState to move focus among controls embedded in SwiftUI List rows, accounting for row reuse and keyboard-driven navigation. It provides a concrete pattern for making forms and editors predictable inside scrolling containers.
- [Using View Modifiers to Display Empty State](https://peterfriese.dev/blog/2021/swiftui-empty-state)
  **NeKI brief:** A view modifier can overlay an empty-state presentation while leaving the underlying list or content generic. This keeps the condition close to rendering policy and allows the same data view to define loading, empty, and populated states consistently.
- [Confirmation Dialogs in SwiftUI](https://peterfriese.dev/blog/2021/swiftui-confirmation-dialogs)
  **NeKI brief:** A reusable confirmation-dialog modifier centralizes destructive-action presentation while accepting the action's state and message as inputs. This keeps confirmation policy consistent and avoids embedding alert state in every feature view.
- [Cooperative Task Cancellation](https://peterfriese.dev/blog/2021/swiftui-concurrency-essentials-part2)
  **NeKI brief:** Uses cooperative cancellation with async/await in SwiftUI, checking cancellation while work is in progress and stopping updates when a task is no longer relevant. The pattern prevents stale results from winning after view state changes.
- [Getting Started with async/await in SwiftUI](https://peterfriese.dev/blog/2021/swiftui-concurrency-essentials-part1)
  **NeKI brief:** Introduces async/await in SwiftUI by moving asynchronous work into task-aware view code and awaiting results directly. It clarifies the lifecycle boundary that cancels work when the associated view disappears.
- [Mapping Firestore Data in Swift](https://peterfriese.dev/blog/2021/firestore-codable-the-comprehensive-guide)
  **NeKI brief:** Firestore Codable mapping must account for document IDs and server-specific field types in addition to ordinary Swift properties. The guide's boundary is useful for keeping persistence adapters separate from models used by SwiftUI.
- [Using async/await in SwiftUI](https://peterfriese.dev/blog/2021/async-await-in-swiftui)
  **NeKI brief:** Compares callback-based networking with Swift's async/await syntax and shows how asynchronous results feed SwiftUI state. The migration examples are useful for untangling nested closures without changing the underlying endpoint behavior.
- [The Ultimate Guide to the SwiftUI 2 Application Life Cycle](https://peterfriese.dev/blog/2020/ultimate-guide-to-swiftui2-application-lifecycle)
  **NeKI brief:** SwiftUI's application lifecycle shifts launch and scene ownership into declarative scene definitions, changing where delegates and shared services are initialized. The guide maps those boundaries so migration does not duplicate startup work across scenes.
- [Firebase and the new SwiftUI 2 Application Life Cycle](https://peterfriese.dev/blog/2020/swiftui-new-app-lifecycle-firebase)
  **NeKI brief:** Firebase initialization under SwiftUI's lifecycle belongs at a process-level entry point, before views request services. Keeping setup there avoids repeated configuration and makes authentication state available consistently across scene creation.
- [Updating Data in Firestore from a SwiftUI app](https://peterfriese.dev/blog/2020/swiftui-firebase-update-data)
  **NeKI brief:** Firestore updates should target a document reference and encode only the fields that changed, preserving unrelated server data. The workflow separates optimistic UI state from write completion and gives failures a clear recovery path.
- [SwiftUI: Fetching Data from Firestore in Real Time](https://peterfriese.dev/blog/2020/swiftui-firebase-fetch-data)
  **NeKI brief:** A Firestore snapshot listener can feed SwiftUI with real-time updates, but its registration must be paired with cancellation when the view disappears. The workflow makes subscription lifetime and ordering explicit instead of treating the database as a one-time fetch.
- [SwiftUI: Mapping Firestore Documents using Swift Codable](https://peterfriese.dev/blog/2020/swiftui-firebase-codable)
  **NeKI brief:** Mapping Firestore documents through Codable centralizes field names, decoding, and identifier handling in a model boundary. The trade-off is that Firestore's dynamic values still need explicit strategies for timestamps, missing fields, and schema evolution.
- [Adding Data to Firestore from a SwiftUI app](https://peterfriese.dev/blog/2020/swiftui-firebase-add-data)
  **NeKI brief:** Adding a Firestore document requires choosing whether the client or server supplies its identifier and how timestamps are generated. The article's model boundary keeps that persistence policy out of SwiftUI form state.
- [Firebase Authentication: Migrating User Data](https://peterfriese.dev/blog/2020/replicating-reminder-swiftui-firebase-part4)
  **NeKI brief:** Migrating Firebase user data requires identifying old documents, writing the new ownership model, and handling partial completion safely. The staged workflow makes retries possible instead of assuming one atomic cross-collection operation.
- [Sign in with Apple using SwiftUI and Firebase](https://peterfriese.dev/blog/2020/replicating-reminder-swiftui-firebase-part3)
  **NeKI brief:** Sign in with Apple plus Firebase requires forwarding Apple's credential and nonce, then linking the authenticated Firebase user to app data. The integration preserves Apple's privacy guarantees while giving Firestore a stable authenticated identity.
- [Connecting SwiftUI and Cloud Firestore](https://peterfriese.dev/blog/2020/replicating-reminder-swiftui-firebase-part2)
  **NeKI brief:** Connecting SwiftUI to Cloud Firestore is a boundary problem: views observe a model, while a repository owns listeners, writes, and decoding. That separation keeps view updates testable and makes subscription cleanup explicit.
- [SwiftUI, Combine, and Firebase](https://peterfriese.dev/blog/2020/replicating-reminder-swiftui-firebase-part1)
  **NeKI brief:** Combining SwiftUI, Combine, and Firebase requires keeping publishers for remote state separate from view-local mutations. The sample's layering makes asynchronous updates observable while retaining a clear place for authentication and persistence policy.
- [Fetching API Keys from Property List Files](https://peterfriese.dev/blog/2020/reading-api-keys-from-plist-files)
  **NeKI brief:** Moves API-key lookup into a property-list-backed configuration boundary rather than embedding secrets in source. The article is a reminder that packaging configuration and secret protection are separate concerns requiring an appropriate deployment strategy.
- [Essential Xcode Shortcuts for More Efficient Coding](https://peterfriese.dev/blog/2019/xcode-shortcuts)
  **NeKI brief:** Xcode shortcuts are most valuable when they reduce repeated navigation and inspection rather than merely speeding text entry. The catalogue is a workflow reference for keeping code search, refactoring, and build feedback in one loop.
- [SwiftUI + Combine = ❤️](https://peterfriese.dev/blog/2019/swift-combine-love)
  **NeKI brief:** The SwiftUI and Combine pairing models UI as a projection of published state, with subscriptions driving invalidation rather than imperative redraws. The trade-off is managing cancellation and ownership so publishers do not outlive the view that consumes them.
