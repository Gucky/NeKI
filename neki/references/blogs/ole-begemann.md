# Ole Begemann

Third-party source index. It provides source attribution and routing metadata, not republished article content. Verify article conclusions independently before applying them.

- Archive: [https://oleb.net/blog/](https://oleb.net/blog/)
- Last collected: `2026-07-22T15:20:34Z`
- Indexed entries: **186**

- [Use 'git mv' to record filename case changes in Git – Ole Begemann](https://oleb.net/2025/git-mv-case-change) — 2025-12-16T17:11:22Z
  **NeKI brief:** Demonstrates that case-only filename changes on case-insensitive filesystems need an explicit git mv so Git records the rename. The two-stage workaround is a compact diagnostic for apparently ignored path changes.
- [Tracking renamed files in Git – Ole Begemann](https://oleb.net/2025/git-file-renaming) — 2025-12-15T15:51:35Z
  **NeKI brief:** Explains when git mv preserves rename history and when Git's similarity detection is sufficient, using concrete repository examples. It helps choose a transparent rename workflow instead of relying on index heuristics.
- [Building with nightly Swift toolchains on macOS – Ole Begemann](https://oleb.net/2024/swift-toolchains) — 2024-03-05T18:54:44Z
  **NeKI brief:** Compares ways to select nightly Swift toolchains on macOS and calls out caveats around Xcode, swift.org snapshots, and command-line selection. Use it when reproducing compiler behavior outside the default stable toolchain.
- [How the Swift compiler knows that DispatchQueue.main implies @MainActor – Ole Begemann](https://oleb.net/2024/dispatchqueue-mainactor) — 2024-02-29T18:54:47Z
  **NeKI brief:** Traces the compiler attribute that lets DispatchQueue.main.async closures satisfy @MainActor isolation, linking source behavior to Swift compiler implementation. It helps explain why some legacy GCD code type-checks while similar queues do not.
- [How the relative size modifier interacts with stack views – Ole Begemann](https://oleb.net/2023/swiftui-relative-size-in-stacks) — 2023-03-24T20:14:49Z
  **NeKI brief:** Analyzes why a relative-size SwiftUI modifier behaves differently inside stacks that distribute space among children. The layout reasoning is more useful than a fixed percentage recipe when composing adaptive interfaces.
- [Working with percentages in SwiftUI layout – Ole Begemann](https://oleb.net/2023/swiftui-relative-size) — 2023-03-23T22:31:11Z
  **NeKI brief:** Implements a SwiftUI layout and modifier for sizing a view relative to its container, exposing the proposed-size and placement decisions involved. Follow it when built-in frame constraints cannot express proportional layout cleanly.
- [Keyboard shortcuts for Export Unmodified Original in Photos for Mac – Ole Begemann](https://oleb.net/2023/photos-keyboard-shortcuts) — 2023-03-21T21:42:04Z
  **NeKI brief:** A shell script can assign a keyboard shortcut to Photos' Export Unmodified Original command, turning a buried menu action into a repeatable workflow. The approach demonstrates targeted macOS automation while keeping the app's own export semantics intact.
- [Swift Evolution proposals in Alfred – Ole Begemann](https://oleb.net/2023/alfred-swift-evolution) — 2023-03-09T22:33:14Z
  **NeKI brief:** Updates an Alfred workflow to search Swift Evolution proposals locally, turning proposal lookup into a fast developer-tool action. It is useful historical tooling context for teams that track language changes during design reviews.
- [Pattern matching on error codes – Ole Begemann](https://oleb.net/2023/catch-error-code) — 2023-02-27T19:32:22Z
  **NeKI brief:** Foundation overloads `~=` so a `catch` clause can pattern-match an error's code without downcasting every case manually. The technique keeps recovery branches declarative while requiring care when domains expose overlapping or unstable codes.
- [Understanding SwiftUI view lifecycles – Ole Begemann](https://oleb.net/2022/swiftui-view-lifecycle) — 2022-12-15T20:52:46Z
  **NeKI brief:** Analyzes SwiftUI view lifecycle events and how identity affects callbacks. Follow it when attaching setup, teardown, or task work and needing to avoid assumptions that a view struct maps to one lifetime.
- [clipped() doesn’t affect hit testing – Ole Begemann](https://oleb.net/2022/clipped-hit-testing) — 2022-11-24T18:30:58Z
  **NeKI brief:** Shows that clipping a SwiftUI view does not automatically constrain its hit-testing region. Use it when oversized content intercepts touches outside its visible bounds and the fix requires an explicit content shape.
- [When .animation animates more (or less) than it’s supposed to – Ole Begemann](https://oleb.net/2022/animation-modifier-position) — 2022-11-10T21:48:45Z
  **NeKI brief:** Demonstrates how the position of SwiftUI's animation modifier changes which updates animate. Use it when an animation affects too much or too little state and modifier scope needs to be made explicit.
- [Xcode 14.0 generates wrong concurrency code for macOS targets – Ole Begemann](https://oleb.net/2022/xcode-14-mac-concurrency-bugs) — 2022-10-12T19:12:17Z
  **NeKI brief:** Xcode 14.0 and 14.0.1 could emit incorrect Swift concurrency code for macOS 12 targets. The operational takeaway is to pin builds to Xcode 13.4.1 until 14.1, treating compiler choice as part of release risk management.
- [Where View.task gets its main-actor isolation from – Ole Begemann](https://oleb.net/2022/swiftui-task-mainactor) — 2022-10-11T16:41:34Z
  **NeKI brief:** Explains why SwiftUI View.task receives main-actor isolation. Use it when task code touches UI state and you need to know which work inherits that isolation.
- [Experimenting with Live Activities – Ole Begemann](https://oleb.net/2022/live-activity) — 2022-08-03T16:50:39Z
  **NeKI brief:** Experiments with early Live Activities APIs. Use it as historical implementation context, while checking current ActivityKit behavior and system constraints.
- [How @MainActor works – Ole Begemann](https://oleb.net/2022/how-mainactor-works) — 2022-05-05T13:52:42Z
  **NeKI brief:** `MainActor` is a global actor backed by an executor that runs jobs on the main dispatch queue; annotation therefore expresses isolation, not merely a UI convention. The explanation helps diagnose why crossing into actor-isolated code can suspend or require `await`.
- [AttributedString’s Codable format and what it has to do with Unicode – Ole Begemann](https://oleb.net/2022/attributedstring-codable) — 2022-04-27T13:28:03Z
  **NeKI brief:** Explains AttributedString's Codable representation and Unicode implications. Use it when storing rich text and needing stable serialization across grapheme clusters and attributes.
- [A heterogeneous dictionary with strong types in Swift – Ole Begemann](https://oleb.net/2022/heterogeneous-dictionary) — 2022-04-19T15:52:08Z
  **NeKI brief:** A heterogeneous dictionary can remain type-safe when each key carries the value type it accepts, with subscripting enforcing the key-value pairing. The design gains extensibility without `Any`, but requires carefully modeled existential storage internally.
- [Advanced Swift, fifth edition – Ole Begemann](https://oleb.net/2022/advanced-swift-5) — 2022-03-28T14:03:30Z
  **NeKI brief:** The fifth Advanced Swift edition updates examples for Swift 5.6, making collection, generics, and concurrency discussions consistent with the newer compiler. It is useful as versioned routing context, not a replacement for current API documentation.
- [Synchronous functions can support cancellation too – Ole Begemann](https://oleb.net/2022/sync-functions-cancellation) — 2022-02-01T22:59:43Z
  **NeKI brief:** Synchronous work can call `Task.checkCancellation()` or inspect cancellation even without being async. Adding those checkpoints lets long-running CPU work stop promptly when invoked from async code, trading a small polling cost for responsive cancellation.
- [Cancellation can come in many forms – Ole Begemann](https://oleb.net/2022/cancellation-forms) — 2022-01-31T18:20:07Z
  **NeKI brief:** Cancellation is a protocol between caller and callee, not one universal error path: code may throw, return partial data, or ignore the signal. The article compares these forms so an API can document and test its chosen cancellation semantics.
- [What is structured concurrency? – Ole Begemann](https://oleb.net/2021/structured-concurrency) — 2021-07-08T20:51:24Z
  **NeKI brief:** Structured concurrency ties child-task lifetime and error propagation to lexical scope, unlike detached work that can outlive its caller. The article supplies a vocabulary for choosing task groups, cancellation ownership, and safe cleanup boundaries.
- [How Swift runs an async executable – Ole Begemann](https://oleb.net/2021/async-program-launch-sequence) — 2021-06-30T21:04:29Z
  **NeKI brief:** Explains how Swift starts an async executable. Use it when command-line async code needs a correct mental model of entry points and runtime setup.
- [Swift needs a better language reference – Ole Begemann](https://oleb.net/2021/swift-language-reference) — 2021-06-03T15:29:29Z
  **NeKI brief:** A searchable, linkable Swift language reference shortens the path from compiler behavior to an authoritative explanation. The article is a tooling critique with practical implications for diagnosing edge cases that tutorials and generated symbol docs omit.
- [How OrderedSet works – Ole Begemann](https://oleb.net/2021/ordered-set) — 2021-04-30T15:34:50Z
  **NeKI brief:** Explains OrderedSet's combination of uniqueness and stable order. Use it when a collection needs set-like membership without losing insertion or display sequence.
- [Thinking in SwiftUI – Ole Begemann](https://oleb.net/2020/thinking-in-swiftui) — 2020-12-19T15:33:44Z
  **NeKI brief:** Thinking in SwiftUI treats layout and state as a value-driven system, emphasizing data flow and identity over imperative view mutation. The review is useful for locating conceptual material while checking examples against current SwiftUI behavior.
- [Where is end-to-end encryption for iCloud? – Ole Begemann](https://oleb.net/2020/icloud-end-to-end-encryption) — 2020-12-10T16:17:45Z
  **NeKI brief:** iCloud's privacy guarantees vary by data category and protection mode; end-to-end encryption is not universal by default. The analysis is useful when deciding what data an app may safely synchronize and what users must explicitly protect.
- [as, as?, and as! – Ole Begemann](https://oleb.net/2020/as) — 2020-06-29T18:11:04Z
  **NeKI brief:** Explains Swift casting operators as, as?, and as!. Use it when converting dynamic or bridged values and deciding between guaranteed, optional, and trapping casts.
- [Sanitizing GPX files for public sharing – Ole Begemann](https://oleb.net/2020/sanitizing-gpx) — 2020-06-22T14:01:32Z
  **NeKI brief:** GPX files can contain timestamps, device metadata, and precise locations beyond the route a user intends to share. An XmlStarlet filtering pass removes those fields before publication, trading convenience for a reproducible privacy boundary.
- [Linking to text fragments in web pages – Ole Begemann](https://oleb.net/2020/text-fragments) — 2020-06-21T21:07:03Z
  **NeKI brief:** Text-fragment URLs encode a phrase that compatible browsers can highlight on arrival, improving deep links into long documents. The article explains the browser and markup limitations that make this useful for navigation but unsuitable as a guaranteed cross-client contract.
- [Testing UIKit accessibility in unit tests – Ole Begemann](https://oleb.net/2020/accessibility-unit-tests) — 2020-04-30T16:29:29Z
  **NeKI brief:** Builds a UIKit unit test comparing a custom progress view's accessibility properties with UIProgressView. The pattern is useful for asserting semantic parity when replacing system controls with drop-in custom implementations.
- [Testing Swift packages on Linux using Docker – Ole Begemann](https://oleb.net/2020/swift-docker-linux) — 2020-02-02T18:44:07Z
  **NeKI brief:** Running SwiftPM tests in a Linux Docker image catches platform assumptions before deployment and gives CI a repeatable toolchain. The workflow trades container setup time for an environment that differs meaningfully from a Mac host.
- [Automatic test discovery in Swift on Linux – Ole Begemann](https://oleb.net/2020/swift-test-discovery) — 2020-02-02T18:43:03Z
  **NeKI brief:** SwiftPM's Linux test discovery is not enabled by default for older Swift toolchains, so packages need generated discovery or an explicit configuration step. The article identifies the portability gap that can make tests appear missing in CI.
- [Sheets don’t inherit the environment – Ole Begemann](https://oleb.net/2020/sheet-environment) — 2020-01-23T17:36:51Z
  **NeKI brief:** SwiftUI sheets do not inherit every environment value from their presenting view, so a dependency available in the parent may be absent in the sheet. Injecting required values at the presentation boundary prevents context-sensitive failures.
- [Enumerating elements in ForEach – Ole Begemann](https://oleb.net/2020/foreach-enumerated) — 2020-01-17T16:45:16Z
  **NeKI brief:** Demonstrates using enumerated sequences with SwiftUI ForEach while preserving stable identity. Follow it when displaying indices alongside elements and ensuring the chosen identifier remains correct during collection updates.
- [TopLevelEncoder and TopLevelDecoder in Combine – Ole Begemann](https://oleb.net/2020/topleveldecoder) — 2020-01-08T00:08:41Z
  **NeKI brief:** Combine's TopLevelEncoder and TopLevelDecoder protocols describe encoders that operate on a complete value rather than a keyed container. Their placement in Combine reflects publisher integration, while the generic abstraction remains useful across serialization formats.
- [URLSession.DataTaskPublisher’s failure type – Ole Begemann](https://oleb.net/2020/urlsession-publisher) — 2020-01-07T17:47:02Z
  **NeKI brief:** URLSession.DataTaskPublisher chooses a failure type that separates transport errors from HTTP status handling, leaving response validation to the pipeline. The article is a useful reminder to model status-code policy explicitly instead of assuming publisher failure means a bad response.
- [Chris Lattner on the origins of Swift – Ole Begemann](https://oleb.net/2019/chris-lattner-swift-origins) — 2019-02-18T16:13:45Z
  **NeKI brief:** Summarizes Chris Lattner's account of Swift's origins and design motivations. Use it as language-history context when discussing Swift's goals and evolution.
- [Splitting a Swift Sequence into head and tail – Ole Begemann](https://oleb.net/2018/sequence-head-tail) — 2018-11-29T22:57:46Z
  **NeKI brief:** Splitting a Sequence into head and tail must preserve its SubSequence and work for single-pass iterators, so eager array conversion is not a neutral shortcut. The implementation exercise clarifies which collection guarantees generic algorithms may rely on.
- [Roy Fielding’s REST dissertation – Ole Begemann](https://oleb.net/2018/rest) — 2018-10-31T22:49:07Z
  **NeKI brief:** Roy Fielding's REST dissertation distinguishes resources, representations, and uniform interface constraints from the looser meaning of HTTP API. The summary is useful when evaluating whether a service actually benefits from REST semantics or merely uses JSON endpoints.
- [PhotoKit’s data model – Ole Begemann](https://oleb.net/2018/photos-data-model) — 2018-09-28T15:36:36Z
  **NeKI brief:** PhotoKit separates assets, resources, and changes, so an app should request the representation it needs rather than assume a thumbnail is the original. Understanding those layers prevents unnecessary downloads and makes authorization failures easier to handle.
- [It’s wrappers all the way down – Ole Begemann](https://oleb.net/2018/lastindex-reversed) — 2018-09-25T18:09:06Z
  **NeKI brief:** Reimplementing `lastIndex(of:)` reveals why Swift collections use wrappers and reversed views instead of copying. The technique leverages existing traversal semantics while making complexity and index-direction constraints visible to API users.
- [The 2018 Macbook Pro – Ole Begemann](https://oleb.net/2018/macbook-pro) — 2018-09-07T14:59:26Z
  **NeKI brief:** Hardware retrospectives are useful when they connect observed performance to workload, thermals, and tooling rather than benchmark numbers alone. This report provides context for deciding whether a development-machine upgrade changes actual iteration bottlenecks.
- [Why you’re not supposed to call description – Ole Begemann](https://oleb.net/2018/dont-call-description) — 2018-08-31T19:57:26Z
  **NeKI brief:** `CustomStringConvertible` documents a textual representation, but calling `description` directly bypasses formatting conventions and overload resolution. `String(describing:)` is the stable entry point when diagnostics should respect the value's printable contract.
- [An iOS alert view with a text field and a “smart” OK button – Ole Begemann](https://oleb.net/2018/uialertcontroller-textfield) — 2018-08-13T17:33:36Z
  **NeKI brief:** Builds a UIAlertController text-field flow with validation before enabling the confirmation action. Use it when modal input must provide immediate feedback without allowing invalid values into the next state.
- [Migrating an Objective-C class to Swift using subclassing – Ole Begemann](https://oleb.net/2018/objc-swift-subclassing) — 2018-08-09T21:08:35Z
  **NeKI brief:** A Swift subclass can wrap an Objective-C class while migration proceeds incrementally, keeping existing callers on the old type. The approach reduces rewrite risk but introduces inheritance and bridging boundaries that must be removed deliberately later.
- [Migrating an Objective-C class to Swift: a piecemeal approach – Ole Begemann](https://oleb.net/2018/objc-swift-transition) — 2018-07-31T21:55:16Z
  **NeKI brief:** Describes incrementally migrating Objective-C classes to Swift while preserving interfaces and interoperability. Use it when replacing legacy implementations gradually and keeping callers stable during a mixed-language transition.
- [Nullability warnings with libextobjc’s @keypath macro – Ole Begemann](https://oleb.net/2018/@keypath) — 2018-07-27T21:31:14Z
  **NeKI brief:** The Objective-C `@keypath` macro turns a property expression into a checked key-path string, reducing typos in KVO and bindings. Nullability warnings still depend on macro expansion and declarations, so the convenience does not remove annotation work.
- [Thoughts on @dynamicMemberLookup – Ole Begemann](https://oleb.net/blog/2018/06/dynamic-member-lookup) — 2018-06-22T21:59:59Z
  **NeKI brief:** Explores Swift dynamic member lookup and its interaction with key paths and wrapper types. Use it when designing DSL-like APIs while weighing discoverability, static guarantees, and the cost of type-erased access.
- [Enumerating enum cases in Swift – Ole Begemann](https://oleb.net/blog/2018/06/enumerating-enum-cases) — 2018-06-09T18:35:36Z
  **NeKI brief:** Explains enumerating finite Swift enum cases with CaseIterable-era language support. Use it when UI choices or tests derive from known cases, while accounting for associated values.
- [Random numbers in Swift – Ole Begemann](https://oleb.net/blog/2018/06/random-numbers-in-swift) — 2018-06-07T16:59:09Z
  **NeKI brief:** Swift random APIs separate uniform generation from a caller-provided generator, allowing deterministic tests without changing production call sites. The design makes entropy ownership explicit and avoids seeding global state as a testing workaround.
- [Playground: What’s new in Swift 4.2 – Ole Begemann](https://oleb.net/blog/2018/06/whats-new-in-swift-4-2-playground) — 2018-06-06T20:44:30Z
  **NeKI brief:** Explores Swift 4.2 additions through a playground-based overview. Use it as dated language migration material and verify behavior with the active compiler.
- [How I do analytics – Ole Begemann](https://oleb.net/blog/2018/05/how-i-do-analytics) — 2018-05-25T07:25:07Z
  **NeKI brief:** Analytics instrumentation is more reliable when events are modeled and emitted through one small boundary instead of scattered string literals. The workflow balances useful product signals against privacy, sampling, and the maintenance cost of event schemas.
- [App Architecture book – Ole Begemann](https://oleb.net/blog/2018/05/app-architecture-book) — 2018-05-24T12:30:03Z
  **NeKI brief:** The architecture discussion frames boundaries, state ownership, and dependency direction as decisions that shape testability more than any single UI framework. It is useful context for comparing coordinator, MVVM, and unidirectional designs without recipe-driven conclusions.
- [Swift 4.1 – Ole Begemann](https://oleb.net/blog/2018/04/swift-4-1) — 2018-04-30T21:36:00Z
  **NeKI brief:** Swift 4.1's language and standard-library changes combine conditional conformances, synthesized Equatable, and package improvements into a migration step. The overview helps identify which compiler upgrade changes source shape versus only build tooling.
- [Making illegal states unrepresentable – Ole Begemann](https://oleb.net/blog/2018/03/making-illegal-states-unrepresentable) — 2018-03-26T14:50:00Z
  **NeKI brief:** Applies sum types and constrained value models to prevent invalid combinations from compiling. Follow it when domain state has mutually exclusive cases and runtime validation is becoming repetitive or incomplete.
- [How to make a copy of a Core Data SQLite database – Ole Begemann](https://oleb.net/blog/2018/03/core-data-sqlite-backup) — 2018-03-23T12:20:00Z
  **NeKI brief:** Copying a Core Data SQLite store while its journal is active can produce an inconsistent backup. The article points to coordinating saves and persistent-store lifecycle so the snapshot reflects a transactionally valid database.
- [A helper for working with temporary files in Swift – Ole Begemann](https://oleb.net/blog/2018/03/temp-file-helper) — 2018-03-22T16:39:00Z
  **NeKI brief:** Introduces a Swift helper for creating and cleaning up temporary files safely. Use it in tests and export workflows where deterministic lifecycle management matters more than relying on shared temporary directories.
- [XCTKVOExpectation for native Swift key paths – Ole Begemann](https://oleb.net/blog/2018/02/xctkvoexpectation-swift-keypaths) — 2018-02-28T21:27:00Z
  **NeKI brief:** A native Swift key-path variant of XCTKVOExpectation keeps observation type-checked while retaining XCTest's asynchronous fulfillment model. The adapter reduces stringly-typed tests but still requires precise lifetime and change-trigger setup.
- [A better NSManagedObjectContext.performAndWait – Ole Begemann](https://oleb.net/blog/2018/02/performandwait) — 2018-02-19T22:04:00Z
  **NeKI brief:** An overload of `performAndWait` can return the closure's result while preserving Core Data's queue confinement. The convenience removes mutable out-parameters, but callers still need to respect context ownership and avoid reentrant work.
- [A script to save the last backup date in SuperDuper – Ole Begemann](https://oleb.net/blog/2018/01/superduper-last-backup-timestamp) — 2018-01-31T18:37:00Z
  **NeKI brief:** Recording a backup timestamp in a small file gives scripts a durable handoff without parsing SuperDuper's UI. The workflow is intentionally simple, but consumers must define clock format and failure behavior for automation to remain reliable.
- [Do you have to manually unregister block-based NotificationCenter observers? – Ole Begemann](https://oleb.net/blog/2018/01/notificationcenter-removeobserver) — 2018-01-05T18:10:00Z
  **NeKI brief:** Tests block-based NotificationCenter observers and explains their lifetime under modern Foundation, including why relying on automatic cleanup can still leave a retained observer active. Useful when reviewing observer teardown and closure ownership.
- [Swift imports fixed-size C arrays as tuples – Ole Begemann](https://oleb.net/blog/2017/12/swift-imports-fixed-size-c-arrays-as-tuples) — 2017-12-29T19:05:00Z
  **NeKI brief:** Swift imports fixed-size C arrays as tuples, preserving inline storage but requiring pointer rebinding or tuple traversal for generic algorithms. The interop detail matters when passing buffers without copying them first.
- [A hack for fixed-size arrays in Swift – Ole Begemann](https://oleb.net/blog/2017/12/fixed-size-arrays) — 2017-12-28T19:01:00Z
  **NeKI brief:** Swift lacks a built-in fixed-size stack array, so tuple-based representations can provide static storage at the cost of awkward indexing and generic use. The workaround clarifies when a C buffer or collection is the better boundary.
- [How to import a C library in Swift using the Swift Package Manager – Ole Begemann](https://oleb.net/blog/2017/12/importing-c-library-into-swift) — 2017-12-18T21:18:00Z
  **NeKI brief:** Importing a C library into Swift requires a module map or SwiftPM system-library target that describes headers and linker settings. The setup makes interoperability repeatable, while platform-specific paths remain a packaging concern.
- [Why Dictionary sometimes encodes itself as an array – Ole Begemann](https://oleb.net/blog/2017/12/dictionary-codable-array) — 2017-12-05T20:31:00Z
  **NeKI brief:** Codable encodes dictionaries as keyed containers only when keys meet its supported scalar constraints; other keys become an unkeyed array of pairs. The behavior is a schema decision that affects interoperability and decoding expectations.
- [Strings in Swift 4 – Ole Begemann](https://oleb.net/blog/2017/11/swift-4-strings) — 2017-11-27T15:48:00Z
  **NeKI brief:** Swift String indexes account for variable-width Unicode rather than treating characters as bytes. The article explains why index traversal is deliberate and when normalization or grapheme-aware APIs must precede slicing and validation.
- [Advanced Swift, third edition – Ole Begemann](https://oleb.net/blog/2017/11/advanced-swift-3) — 2017-11-23T19:03:00Z
  **NeKI brief:** The Advanced Swift edition update uses concrete collection and generics examples to expose performance and type-system trade-offs. It is useful routing context for deeper mechanisms, not a substitute for current language documentation.
- [Injecting side effects into chained Sequence operations – Ole Begemann](https://oleb.net/blog/2017/10/chained-foreach) — 2017-10-30T21:05:00Z
  **NeKI brief:** Examines injecting forEach into chained Swift collection operations and the readability or side-effect trade-offs involved. Follow it when keeping transformations expressive without hiding mutation inside fluent pipelines.
- [Mental models in API design – Ole Begemann](https://oleb.net/blog/2017/07/mental-models-in-api-design) — 2017-07-31T13:22:00Z
  **NeKI brief:** Discusses API design through the mental models users form from names, ownership, and behavior. Use it when reviewing Swift interfaces for discoverability and avoiding abstractions whose surface semantics contradict their implementation.
- [Customizing the file header comment and other text macros in Xcode 9 – Ole Begemann](https://oleb.net/blog/2017/07/xcode-9-text-macros) — 2017-07-20T18:58:00Z
  **NeKI brief:** Explains Xcode text macros for file headers and templates. Use it when standardizing generated comment metadata without manually editing every new source file.
- [Chris Lattner on the Realm WWDC 2017 Swift panel – Ole Begemann](https://oleb.net/blog/2017/06/chris-lattner-wwdc-swift-panel) — 2017-06-30T17:13:00Z
  **NeKI brief:** Reports Chris Lattner's discussion of Swift at a WWDC panel. Use it as historical context for language design priorities and community expectations, not as current Swift evolution guidance.
- [Optimizing Collections – Ole Begemann](https://oleb.net/blog/2017/06/optimizing-collections-book) — 2017-06-12T18:37:00Z
  **NeKI brief:** Collection optimization depends on choosing storage and traversal guarantees that match the algorithm, not merely micro-optimizing loops. The review points toward measuring complexity and allocation behavior before changing a generic abstraction.
- [Playground: What’s new in Swift 4 – Ole Begemann](https://oleb.net/blog/2017/05/whats-new-in-swift-4-playground) — 2017-05-18T18:32:00Z
  **NeKI brief:** Summarizes Swift 4 additions in a playground. Use it as version-scoped language history when maintaining older code, not as current compiler migration advice.
- [Swift Package Manager macOS deployment target override – Ole Begemann](https://oleb.net/blog/2017/04/swift-3-1-package-manager-deployment-target) — 2017-04-07T16:54:49Z
  **NeKI brief:** SwiftPM deployment-target overrides let package clients select a compatible macOS minimum when the package manifest's default is too broad. The fix separates library declaration from product deployment policy.
- [How to test a Swift package on Linux using Docker – Ole Begemann](https://oleb.net/blog/2017/03/testing-swift-packages-on-linux) — 2017-03-31T12:03:32Z
  **NeKI brief:** Testing Swift packages on Linux in Docker isolates the toolchain and filesystem from the developer Mac. The repeatable setup catches portability assumptions while adding an image-maintenance cost to CI.
- [Keeping XCTest in sync on Linux – Ole Begemann](https://oleb.net/blog/2017/03/keeping-xctest-in-sync) — 2017-03-30T13:59:21Z
  **NeKI brief:** Explains how Linux XCTest discovery can silently omit tests in cross-platform Swift packages, then proposes a synchronization check. Follow it when CI must verify that Apple and Linux test suites execute equivalent coverage.
- [Swift releases have themes – Ole Begemann](https://oleb.net/blog/2017/03/swift-themed-releases) — 2017-03-20T19:25:08Z
  **NeKI brief:** The Swift release-theme proposal prioritizes a small number of coherent language goals per version, making evolution easier to reason about and implement. It is useful context when weighing feature breadth against compiler and migration stability.
- [Safeguarding Equatable implementations – Ole Begemann](https://oleb.net/blog/2017/03/dump-as-equatable-safeguard) — 2017-03-08T18:27:49Z
  **NeKI brief:** Uses Swift's `dump` output to make Equatable conformances fail loudly when stored properties change without corresponding equality updates. Follow it as a lightweight regression guard for value types with hand-written comparisons.
- [Enums, Equatable, and exhaustiveness – Ole Begemann](https://oleb.net/blog/2017/03/enums-equatable-exhaustiveness) — 2017-03-06T17:57:40Z
  **NeKI brief:** Enums with associated values can implement Equatable by comparing cases and payloads explicitly, while exhaustive switching keeps new cases visible to the compiler. The pattern avoids generated boilerplate without hiding model evolution.
- [A Sorted Array Implementation in Swift – Ole Begemann](https://oleb.net/blog/2017/02/sorted-array) — 2017-02-08T19:40:23Z
  **NeKI brief:** A sorted-array type maintains ordering at insertion cost, enabling binary search and predictable traversal later. The implementation makes invariants explicit and shows when a specialized value type is preferable to sorting ad hoc arrays.
- [Why String.CharacterView is not a MutableCollection – Ole Begemann](https://oleb.net/blog/2017/02/why-is-string-characterview-not-a-mutablecollection) — 2017-02-07T14:48:44Z
  **NeKI brief:** String.CharacterView cannot safely provide arbitrary mutation because grapheme clusters can change width and boundaries when characters are replaced. The explanation clarifies why collection protocols encode semantic guarantees, not just methods.
- [Being a Mutable Collection is not Sufficient to be a MutableCollection – Ole Begemann](https://oleb.net/blog/2017/02/why-is-dictionary-not-a-mutablecollection) — 2017-02-06T21:44:01Z
  **NeKI brief:** Dictionary mutation cannot satisfy MutableCollection's index semantics because insertions invalidate ordering and indices. The article distinguishes protocol guarantees from merely having subscript assignment.
- [Fun with String Interpolation – Ole Begemann](https://oleb.net/blog/2017/01/fun-with-string-interpolation) — 2017-01-25T21:31:08Z
  **NeKI brief:** Demonstrates custom string interpolation for sanitized and unsanitized HTML wrapper types. Use it when designing domain-specific literal formatting and ensuring output policy is encoded in types rather than left to call-site discipline.
- [Working with Asynchronous Objective-C APIs in Swift – Ole Begemann](https://oleb.net/blog/2017/01/result-init-helper) — 2017-01-19T16:43:06Z
  **NeKI brief:** Bridging asynchronous Objective-C completion handlers into Swift benefits from a Result initializer that centralizes success and error mapping. The helper reduces repeated callback plumbing while preserving explicit failure ownership.
- [Accessing Dictionaries with Key Paths – Ole Begemann](https://oleb.net/blog/2017/01/dictionary-key-paths) — 2017-01-09T15:39:00Z
  **NeKI brief:** Implements key-path-style traversal and mutation for heterogeneous Swift dictionaries. Follow it to study dynamic lookup trade-offs, while treating the technique as an edge-case tool rather than a replacement for typed models.
- [Protocols are more than Bags of Syntax – Ole Begemann](https://oleb.net/blog/2016/12/protocols-have-semantics) — 2016-12-30T21:12:55Z
  **NeKI brief:** Protocols communicate semantic contracts, not merely bags of required methods. The distinction helps decide which invariants belong in a protocol and prevents conformances that satisfy syntax while violating intended behavior.
- [Emoji 4.0 – Ole Begemann](https://oleb.net/blog/2016/12/emoji-4-0) — 2016-12-19T20:53:04Z
  **NeKI brief:** Uses Foundation string transforms to expose Unicode code-point names in emoji strings, illustrating the distinction between grapheme clusters and scalars and why Swift's ICU-backed string behavior matters.
- [Optionals and String Interpolation – Ole Begemann](https://oleb.net/blog/2016/12/optionals-string-interpolation) — 2016-12-07T16:38:07Z
  **NeKI brief:** Explains surprising optional interpolation diagnostics and defines a custom fallback operator for nil values. Use it when auditing user-facing strings so missing data produces intentional text instead of debug-style optional descriptions.
- [The RawRepresentable Protocol in Swift – Ole Begemann](https://oleb.net/blog/2016/11/rawrepresentable) — 2016-11-23T18:19:09Z
  **NeKI brief:** Explores RawRepresentable beyond enum string and integer syntax, showing how custom types can provide raw-value conversions. Follow it when designing serialization-friendly value types without conflating raw storage with domain identity.
- [How to Read the Swift Standard Library Source – Ole Begemann](https://oleb.net/blog/2016/10/swift-stdlib-source) — 2016-10-28T20:13:25Z
  **NeKI brief:** Reading the Swift standard-library source reveals implementation trade-offs hidden by simple APIs, especially around collections and generics. The workflow is a concrete way to verify complexity claims before optimizing client code.
- [Passing an Array of Strings from Swift to C – Ole Begemann](https://oleb.net/blog/2016/10/swift-array-of-c-strings) — 2016-10-27T15:12:40Z
  **NeKI brief:** Passing Swift strings to C requires stable UTF-8 storage and pointer lifetimes for the duration of the call. The article's bridge avoids dangling buffers while making ownership and null termination explicit.
- [Generic Range Algorithms – Ole Begemann](https://oleb.net/blog/2016/10/generic-range-algorithms) — 2016-10-13T18:48:10Z
  **NeKI brief:** Generic range algorithms can operate over collection indices without assuming integer offsets, preserving correctness for slices and custom collections. The technique separates traversal guarantees from concrete storage.
- [Optional Non-Escaping Closures – Ole Begemann](https://oleb.net/blog/2016/10/optional-non-escaping-closures) — 2016-10-10T21:28:37Z
  **NeKI brief:** Details Swift 3's non-escaping closure default and the compiler rules around optional closures. Use it when APIs accept optional callbacks and you need to reason about capture, lifetime, and explicit escaping annotations.
- [_playgroundPrintHook – Ole Begemann](https://oleb.net/blog/2016/09/playground-print-hook) — 2016-09-30T18:19:00Z
  **NeKI brief:** _playgroundPrintHook lets a type customize its Playground representation without changing ordinary description behavior. It is a focused debugging aid, not a stable interchange or logging contract.
- [Option Sets in Swift – Ole Begemann](https://oleb.net/blog/2016/09/swift-option-sets) — 2016-09-28T15:51:00Z
  **NeKI brief:** OptionSet models independent flags as a bitmask while retaining type-safe insertion and membership checks. The article explains why raw values are storage, not the public API, and how that affects Codable or persistence boundaries.
- [What’s in a Collection? – Ole Begemann](https://oleb.net/blog/2016/09/collection-associated-types) — 2016-09-22T21:23:00Z
  **NeKI brief:** Collection associated types let generic algorithms preserve index and element relationships without committing to Array. The design exposes why protocol constraints should state the guarantees an algorithm actually needs.
- [Ranges in Swift 3 – Ole Begemann](https://oleb.net/blog/2016/09/swift-3-ranges) — 2016-09-14T16:51:00Z
  **NeKI brief:** Swift 3 ranges distinguish half-open and closed bounds in their type, making iteration and slicing rules visible. The article helps prevent off-by-one conversions when translating interval semantics into collection indices.
- [Strings in Swift 3 – Ole Begemann](https://oleb.net/blog/2016/08/swift-3-strings) — 2016-08-31T17:20:00Z
  **NeKI brief:** Swift 3 string APIs make Unicode-correct indexing explicit, avoiding the false assumption that an integer offset identifies a user-visible character. The migration guidance exposes where old byte-oriented logic fails.
- [Measurements and Units with Phantom Types – Ole Begemann](https://oleb.net/blog/2016/08/measurements-and-units-with-phantom-types) — 2016-08-22T19:26:00Z
  **NeKI brief:** Phantom types encode a measurement's unit in the type system while storing the same numeric value, preventing accidental addition of incompatible quantities. The approach trades simple arithmetic for compile-time dimensional safety.
- [Measurements and Units, Part 3 – Ole Begemann](https://oleb.net/blog/2016/07/unitsquare) — 2016-07-29T17:30:00Z
  **NeKI brief:** Continues a Foundation Measurement series by refining unit APIs and introducing phantom-type constraints, showing how type-level design can prevent invalid operations across physical dimensions.
- [Putting the Physics Into Measurements and Units – Ole Begemann](https://oleb.net/blog/2016/07/unitproduct) — 2016-07-29T14:25:00Z
  **NeKI brief:** Multiplying typed quantities needs a representation for compound units, otherwise arithmetic loses dimensional meaning. The article develops that type-level composition and its trade-off against Foundation's runtime conversion model.
- [Measurements and Units in Foundation – Ole Begemann](https://oleb.net/blog/2016/07/measurements-and-units) — 2016-07-28T18:11:00Z
  **NeKI brief:** Foundation Measurement combines a numeric value with a Unit, enabling conversion at API boundaries instead of manual scale factors. The article explains when runtime unit flexibility outweighs a static type-level encoding.
- [Swift 3 – Ole Begemann](https://oleb.net/blog/2016/06/swift-3) — 2016-06-27T16:28:00Z
  **NeKI brief:** Swift 3's redesign emphasizes API naming and consistency across the standard library, making migration more than syntax replacement. The overview helps identify behavioral source changes that deserve focused regression tests.
- [Ellen Shapiro: Outside In – Using UI Tests to Start Improving Your App – Ole Begemann](https://oleb.net/blog/2016/06/ellen-shapiro-ui-testing) — 2016-06-06T13:14:00Z
  **NeKI brief:** Presents an outside-in testing approach that begins with UI tests on existing apps, stabilizing observable behavior before refactoring individual units and reducing fear of changing legacy code.
- [Method Dispatch in Protocol Extensions – Ole Begemann](https://oleb.net/blog/2016/06/lily-ballard-swift-dispatch) — 2016-06-05T16:24:00Z
  **NeKI brief:** Protocol-extension dispatch depends on whether a member is a protocol requirement; otherwise a call through an existential can choose the extension implementation. The talk summary identifies a frequent source of polymorphism surprises.
- [Protocol-Oriented Logging, or: Default Arguments in Swift Protocols – Ole Begemann](https://oleb.net/blog/2016/05/default-arguments-in-protocols) — 2016-05-01T20:03:00Z
  **NeKI brief:** Default arguments are selected at the call site, whereas protocol requirements dispatch through the witness implementation. The logging example shows why combining both can yield surprising behavior across existential boundaries.
- [Camera.app Pauses Audio Playback – Ole Begemann](https://oleb.net/blog/2016/03/ios-camera-app-pauses-audio-playback) — 2016-03-22T16:36:00Z
  **NeKI brief:** Camera and audio-session interactions reveal that system apps can interrupt an application's playback lifecycle. The observation is useful for designing interruption handling and resumption logic rather than assuming audio ownership is exclusive.
- [ICU Text Transforms in Foundation – Ole Begemann](https://oleb.net/blog/2016/01/icu-text-transforms) — 2016-01-31T20:59:00Z
  **NeKI brief:** Foundation's ICU text transforms can transliterate, normalize, or transform scripts using locale-aware rules instead of ad-hoc character replacement. The article warns that transformation is a linguistic policy, not neutral cleanup.
- [Lazy Properties in Structs – Ole Begemann](https://oleb.net/blog/2015/12/lazy-properties-in-structs-swift) — 2015-12-17T19:01:00Z
  **NeKI brief:** Lazy properties in value types expose a tension between deferred work and mutation: reading the property can require a mutable instance. The detail matters when designing cache-like behavior in structs.
- [More Pattern Matching Examples – Ole Begemann](https://oleb.net/blog/2015/09/more-pattern-matching-examples) — 2015-09-30T21:55:00Z
  **NeKI brief:** Additional pattern-matching examples show how associated values, optionals, and where clauses can express domain conditions together. The technique improves branch clarity when it reflects real alternatives rather than clever syntax.
- [Ranges and Intervals in Swift – Ole Begemann](https://oleb.net/blog/2015/09/swift-ranges-and-intervals) — 2015-09-24T21:51:00Z
  **NeKI brief:** Swift ranges model ordered bounds for discrete values, whereas time and measurement intervals often need different inclusion semantics. The comparison prevents using collection syntax as a universal interval representation.
- [Pattern Matching in Swift – Ole Begemann](https://oleb.net/blog/2015/09/swift-pattern-matching) — 2015-09-18T21:15:00Z
  **NeKI brief:** Swift pattern matching combines structural destructuring with `where` constraints, allowing conditions to stay adjacent to the case they refine. The article clarifies when a switch communicates domain alternatives better than nested conditionals.
- [How to Use updateConstraints – Ole Begemann](https://oleb.net/blog/2015/08/how-to-use-updateconstraints) — 2015-08-31T21:53:00Z
  **NeKI brief:** updateConstraints is the right hook for changing constraint definitions, while layout passes should not continually recreate them. The article maps Auto Layout work to lifecycle phases and prevents feedback-loop performance issues.
- [Swift Compiler Diagnostics – Ole Begemann](https://oleb.net/blog/2015/08/swift-compiler-diagnostics) — 2015-08-10T17:56:00Z
  **NeKI brief:** Compiler diagnostics become useful when reduced to a minimal expression that reveals failed inference or a type mismatch. The article treats error messages as evidence for restructuring code, not merely obstacles to silence.
- [Is it Immoral to not Block Ads? – Ole Begemann](https://oleb.net/blog/2015/08/is-it-immoral-to-not-block-ads) — 2015-08-04T22:47:00Z
  **NeKI brief:** Advertising-blocking decisions combine product ethics, publisher incentives, privacy, and user control rather than a purely technical toggle. The essay is useful context when an app's network policy affects third-party content.
- [Swift’s Type System – Ole Begemann](https://oleb.net/blog/2015/07/swift-type-system) — 2015-07-21T00:01:00Z
  **NeKI brief:** Swift's type system combines static checking, generics, protocols, and inference to express domain constraints before runtime. The overview is useful for deciding when a type-level model can replace validation branches.
- [C Callbacks in Swift – Ole Begemann](https://oleb.net/blog/2015/06/c-callbacks-in-swift) — 2015-06-22T21:06:00Z
  **NeKI brief:** C callbacks in Swift need explicit bridging for function pointers, context storage, and object lifetime. The article shows where closures cannot be passed directly and how ownership must survive asynchronous invocation.
- [WWDC 2015 – Ole Begemann](https://oleb.net/blog/2015/06/wwdc-2015) — 2015-06-12T18:33:00Z
  **NeKI brief:** WWDC retrospectives are useful for identifying platform changes that require migration work, but announcements need verification against the released SDK. The article provides historical routing context rather than normative API guidance.
- [Accessibility at the Apple Design Awards – Ole Begemann](https://oleb.net/blog/2015/06/workflow-accessibility-apple-design-awards) — 2015-06-11T15:30:00Z
  **NeKI brief:** Uses Workflow's Apple Design Award accessibility demonstration as a concrete product example, including blind engineers operating it live. The routing value is experiential: study how accessible interaction can remain first-class rather than bolted on.
- [Swift Standard Library.playground – Ole Begemann](https://oleb.net/blog/2015/06/swift-standard-library-playground) — 2015-06-09T15:16:00Z
  **NeKI brief:** Exploring the standard library in a Playground makes generic algorithms and value behavior inspectable in small experiments. The workflow is useful for testing hypotheses before embedding assumptions in production code.
- [Truncated Text in Mobile UIs – Ole Begemann](https://oleb.net/blog/2015/02/truncated-text) — 2015-02-27T15:29:00Z
  **NeKI brief:** Truncating text in mobile interfaces is a layout and accessibility decision, not merely a string operation. The article connects line limits, dynamic type, and disclosure of omitted content to user comprehension.
- [The Minus Sign – Ole Begemann](https://oleb.net/blog/2015/02/minus-sign) — 2015-02-26T21:40:00Z
  **NeKI brief:** The Unicode minus sign and ASCII hyphen have different semantics and typography, so formatting numeric output should select a locale-aware representation. The small detail matters for copyable values and consistent UI text.
- [Code vs. Poetry – Ole Begemann](https://oleb.net/blog/2015/01/code-vs-poetry) — 2015-01-13T19:10:00Z
  **NeKI brief:** Code and prose are both communicative artifacts, but executable behavior creates a stronger correctness obligation. The essay is useful when weighing elegance against maintainability and testable intent.
- [iPhone 6 Plus Pixel Peeping Follow-Up – Ole Begemann](https://oleb.net/blog/2014/12/pixel-peeping-followup) — 2014-12-17T15:51:00Z
  **NeKI brief:** Examines Display Zoom rendering on iPhone 6 and 6 Plus, distinguishing logical point dimensions from backing-pixel buffers so UI debugging does not confuse interface scale with panel resolution.
- [Dan Grossman’s Programming Languages Course – Ole Begemann](https://oleb.net/blog/2014/12/programming-languages-mooc) — 2014-12-10T18:01:00Z
  **NeKI brief:** A programming-languages course gives comparative vocabulary for evaluation, type systems, and abstraction boundaries. It is useful supplementary reading when a Swift design question benefits from language-level context.
- [iPhone 6 Plus Pixel Peeping – Ole Begemann](https://oleb.net/blog/2014/11/iphone-6-plus-screen) — 2014-11-20T00:13:00Z
  **NeKI brief:** Pixel-density analysis distinguishes rendered points, native pixels, and display scaling so screenshots are interpreted correctly. The investigation is useful when visual bugs depend on device-specific rasterization.
- [Backblaze Review – Ole Begemann](https://oleb.net/blog/2014/10/backblaze) — 2014-10-15T15:45:00Z
  **NeKI brief:** A backup-service review is useful when it evaluates restore behavior, retention, encryption, and operational failure modes rather than storage price alone. It frames backups as a recoverability workflow.
- [Work Habits at Apple – Ole Begemann](https://oleb.net/blog/2014/09/work-habits-at-apple) — 2014-09-30T16:40:00Z
  **NeKI brief:** Engineering work habits shape review, iteration, and communication as much as individual coding skill. The account is organizational context rather than a prescriptive process, useful for comparing team constraints.
- [iPhone 6 Plus First Impressions – Ole Begemann](https://oleb.net/blog/2014/09/iphone-6-plus-first-impressions) — 2014-09-25T17:25:00Z
  **NeKI brief:** Device first impressions are useful when they tie display, battery, and performance observations to real development workloads. Treat the historical hardware report as context, not current purchasing guidance.
- [Replacing Launch Images With Storyboards – Ole Begemann](https://oleb.net/blog/2014/08/replacing-launch-images-with-storyboards) — 2014-08-28T18:47:00Z
  **NeKI brief:** Launch screen storyboards replace static image variants with adaptive layout, reducing device-specific assets. The migration must avoid app-like initialization work because the system displays the launch screen before the process is ready.
- [Instance Methods are “Curried” Functions in Swift – Ole Begemann](https://oleb.net/blog/2014/07/swift-instance-methods-curried-functions) — 2014-07-28T16:27:00Z
  **NeKI brief:** Instance methods can be understood as functions that first capture the instance, then accept remaining arguments. This perspective explains partial application and method references without relying on special-case syntax.
- [Strings in Swift Updated – Ole Begemann](https://oleb.net/blog/2014/07/swift-strings-updated) — 2014-07-22T20:45:00Z
  **NeKI brief:** The updated Swift string model reinforces Unicode-aware traversal and makes index validity depend on the exact string value. The clarification helps prevent stale-index bugs after mutation or normalization.
- [Strings in Swift 1 – Ole Begemann](https://oleb.net/blog/2014/07/swift-strings) — 2014-07-03T16:05:00Z
  **NeKI brief:** Swift strings represent Unicode text rather than random-access byte arrays, making character traversal and slicing semantics explicit. The article explains why correctness across grapheme clusters requires different algorithms.
- [One for the Unicode Nerds – Ole Begemann](https://oleb.net/blog/2014/06/one-for-the-unicode-nerds) — 2014-06-27T12:46:00Z
  **NeKI brief:** Unicode details such as normalization and scalar equivalence affect text comparison beyond visible glyphs. The article is useful when input validation or search must be correct across scripts.
- [Apple’s Take on App Architecture – Ole Begemann](https://oleb.net/blog/2014/06/apples-take-on-app-architecture) — 2014-06-20T18:37:00Z
  **NeKI brief:** Apple's architecture guidance separates application lifecycle, view coordination, and model responsibilities. It is useful context for evaluating boundaries, while concrete implementation choices remain product-specific.
- [Core Data Concurrency Debugging – Ole Begemann](https://oleb.net/blog/2014/06/core-data-concurrency-debugging) — 2014-06-11T21:22:00Z
  **NeKI brief:** Enables Core Data's concurrency debugging to expose managed-object-context access on the wrong queue, turning a corruption-prone threading mistake into a diagnosable runtime failure during development.
- [How Dropbox Uses C++ for Cross-Platform iOS and Android Development – Ole Begemann](https://oleb.net/blog/2014/05/how-dropbox-uses-cplusplus-cross-platform-development) — 2014-05-23T20:17:00Z
  **NeKI brief:** Analyzes Dropbox's former C++ shared-core strategy for iOS and Android, including the integration costs that later led it back to native languages and SDKs.
- [Scroll Views Inside Scroll Views – Ole Begemann](https://oleb.net/blog/2014/05/scrollviews-inside-scrollviews) — 2014-05-21T15:55:00Z
  **NeKI brief:** Introduces a container scroll view that coordinates multiple nested scroll, table, or collection views, separating the combined outer scroll extent from each child view's own content behavior.
- [Parallax Scrolling – Ole Begemann](https://oleb.net/blog/2014/05/parallax-scrolling-collectionview) — 2014-05-02T15:32:00Z
  **NeKI brief:** Implements collection-view parallax by deriving each cell image position from the scroll view's translated bounds, keeping the visible image movement synchronized with reusable-cell layout.
- [Understanding UIScrollView – Ole Begemann](https://oleb.net/blog/2014/04/understanding-uiscrollview) — 2014-04-30T17:12:00Z
  **NeKI brief:** Reconstructs a minimal UIScrollView while explaining UIKit coordinate systems, bounds, frame, contentOffset, and contentSize, making the geometry and scrolling mechanics easier to reason about in nested layouts.
- [NSProgress – Ole Begemann](https://oleb.net/blog/2014/03/nsprogress) — 2014-03-12T22:55:00Z
  **NeKI brief:** Explains NSProgress as a composable progress tree for long-running work, while its later caveat highlights that performance and cancellation behavior must be measured before adopting it broadly.
- [How I Learned to Stop Worrying and Love Cocoa Auto Layout – Ole Begemann](https://oleb.net/blog/2014/03/how-i-learned-to-stop-worrying-and-love-auto-layout) — 2014-03-03T19:10:00Z
  **NeKI brief:** Shows where Auto Layout can coexist with manual frame calculation, using constraints for adaptable structure while retaining explicit layout code where constraint systems would add unnecessary complexity.
- [Handling Default Values With NSUserDefaults – Ole Begemann](https://oleb.net/blog/2014/02/nsuserdefaults-handling-default-values) — 2014-02-25T18:44:00Z
  **NeKI brief:** Explains why missing NSUserDefaults values silently become type defaults and shows how registered defaults make preference reads explicit, correct, and independent of whether a user has previously changed a setting.
- [A Geocoding Service for OS X – Ole Begemann](https://oleb.net/blog/2014/01/geocoding-automator-service) — 2014-01-23T21:15:00Z
  **NeKI brief:** Builds an OS X Automator service around command-line geocoding, turning selected place names into coordinates for development testing while keeping the external geocoder and output format explicit.
- [Parallelize Your for Loops With GCD – Ole Begemann](https://oleb.net/blog/2013/07/parallelize-for-loops-gcd-dispatch_apply) — 2013-07-17T13:50:00Z
  **NeKI brief:** Compares concurrent Foundation enumeration with dispatch_apply for parallel collection work, emphasizing that speed gains require independent iterations, controlled shared state, and measured scheduling overhead.
- [NSArray Binary Search – Ole Begemann](https://oleb.net/blog/2013/07/nsarray-binary-search) — 2013-07-10T19:25:00Z
  **NeKI brief:** Uses NSArray's comparator-based binary search to reduce lookup cost in sorted ranges, while requiring callers to preserve the same ordering semantics used by the search comparator.
- [On NSURLConnection API Design – Ole Begemann](https://oleb.net/blog/2013/07/nsurlconnection-api-design) — 2013-07-08T21:48:00Z
  **NeKI brief:** Explains why NSURLConnection's browser-oriented delegate design differs from typical web-service needs, providing historical context when migrating legacy networking code to modern URLSession abstractions.
- [Starting With Bluetooth Low Energy Development on iOS – Ole Begemann](https://oleb.net/blog/2013/04/starting-bluetooth-low-energy-development-ios) — 2013-04-29T18:04:00Z
  **NeKI brief:** Introduces Core Bluetooth's central/peripheral model for communicating with Bluetooth Low Energy devices, distinguishing app-managed BLE peripherals from accessory classes controlled directly by the operating system.
- [Compiler Warnings for Objective-C Developers – Ole Begemann](https://oleb.net/blog/2013/04/compiler-warnings-for-objective-c-developers) — 2013-04-25T21:35:00Z
  **NeKI brief:** Treats Clang warnings as a deliberate code-quality tool, explaining how stricter diagnostics catch dangerous but syntactically valid Objective-C patterns and should be enabled incrementally in legacy targets.
- [10 Things You Need to Know About Cocoa Auto Layout – Ole Begemann](https://oleb.net/blog/2013/03/things-you-need-to-know-about-cocoa-autolayout) — 2013-03-31T19:08:00Z
  **NeKI brief:** Distills Auto Layout into constraint sufficiency, priorities, and intrinsic content size, helping developers reason about ambiguous or unsatisfiable layouts instead of treating constraints as fixed frame assignments.
- [There is a Bug in the NSFetchedResultsControllerDelegate Documentation – Ole Begemann](https://oleb.net/blog/2013/02/nsfetchedresultscontroller-documentation-bug) — 2013-02-27T16:24:00Z
  **NeKI brief:** Identifies a NSFetchedResultsController delegate documentation error around table updates, illustrating why insertion, deletion, move, and reload handling must follow the controller's actual index-path contract.
- [Building a Blocks-Based Object System in (Objective-)C – Ole Begemann](https://oleb.net/blog/2013/02/building-blocks-based-object-system-in-objective-c) — 2013-02-11T15:42:00Z
  **NeKI brief:** Builds an Objective-C object system around blocks and message dispatch, illustrating how closures can encode behavior while making ownership, captured state, and extensibility explicit.
- [iOS Apps: Disable the Sleep Timer for Long-Running Tasks – Ole Begemann](https://oleb.net/blog/2013/02/ios-apps-disable-sleep-timer-long-running-tasks) — 2013-02-07T15:12:00Z
  **NeKI brief:** Uses UIApplication's idle-timer control to keep the screen awake during a legitimate long-running interaction, emphasizing that the setting should be scoped and restored to preserve battery behavior.
- [Mac Sandboxing: Location Services Access Requires Outgoing Connections – Ole Begemann](https://oleb.net/blog/2013/01/mac-sandboxing-location-services-outgoing-connections) — 2013-01-17T17:00:00Z
  **NeKI brief:** Explains a macOS sandboxing dependency where Location Services can require outgoing-network entitlement, helping diagnose an otherwise surprising capability failure in sandboxed apps.
- [Accessing and Pretty-Printing the Elements of a CGPath – Ole Begemann](https://oleb.net/blog/2012/12/accessing-pretty-printing-cgpath-elements) — 2012-12-07T15:00:00Z
  **NeKI brief:** Iterates CGPath elements through Core Graphics callbacks and formats their move, line, curve, and close commands, providing a practical debugging view of path geometry.
- [Prevent Layers From Snapping Back to Original Values When Using Explicit CAAnimations – Ole Begemann](https://oleb.net/blog/2012/11/prevent-caanimation-snap-back) — 2012-11-28T15:56:00Z
  **NeKI brief:** Prevents explicit Core Animation from visually snapping back by updating the model layer to the final value while the presentation layer animates the transition.
- [UTF-8 – Ole Begemann](https://oleb.net/blog/2012/09/utf-8) — 2012-09-17T18:45:00Z
  **NeKI brief:** Clarifies UTF-8 as a variable-width encoding and distinguishes bytes, Unicode scalars, and user-perceived characters, helping avoid incorrect string indexing and length assumptions.
- [Creating and Deleting Calendars in iOS – Ole Begemann](https://oleb.net/blog/2012/05/creating-and-deleting-calendars-in-ios) — 2012-05-31T16:28:00Z
  **NeKI brief:** Uses EventKit calendar APIs to create and remove user calendars, requiring explicit authorization and careful selection of the writable event-store source.
- [Checking Code Signing and Sandboxing Status in Code – Ole Begemann](https://oleb.net/blog/2012/02/checking-code-signing-and-sandboxing-status-in-code) — 2012-02-22T17:55:00Z
  **NeKI brief:** Inspects signing and sandbox state at runtime for diagnostic builds, helping distinguish entitlement configuration failures from ordinary application logic errors.
- [Passing Data Between View Controllers – Ole Begemann](https://oleb.net/blog/2012/02/passing-data-between-view-controllers) — 2012-02-21T19:10:00Z
  **NeKI brief:** Compares view-controller data handoff patterns, keeping ownership and lifecycle explicit so navigation does not become an implicit shared-state channel.
- [Revisiting the App Launch Sequence on iOS – Ole Begemann](https://oleb.net/blog/2012/02/app-launch-sequence-ios-revisited) — 2012-02-09T20:20:00Z
  **NeKI brief:** Traces the iOS app launch lifecycle to place initialization after its dependencies are available, avoiding work that blocks first presentation or assumes loaded UI too early.
- [CGPath Hit Testing – Ole Begemann](https://oleb.net/blog/2012/02/cgpath-hit-testing) — 2012-02-03T18:00:00Z
  **NeKI brief:** Performs hit testing against Core Graphics paths by converting touch coordinates into the path's coordinate space and applying the appropriate fill-rule semantics.
- [Gesture Recognition on iOS With Attention to Detail – Ole Begemann](https://oleb.net/blog/2012/01/gesture-recognition-on-ios-with-attention-to-detail) — 2012-01-25T17:08:00Z
  **NeKI brief:** Explains gesture recognizer coordination, including failure dependencies and touch-delivery trade-offs, for interfaces where competing gestures must remain predictable.
- [initWithNibName:bundle: Breaks Encapsulation – Ole Begemann](https://oleb.net/blog/2012/01/initWithNibName-bundle-breaks-encapsulation) — 2012-01-23T18:00:00Z
  **NeKI brief:** Shows how exposing nib names in UIViewController initialization leaks presentation details, motivating factory or subclass boundaries that preserve view-construction encapsulation.
- [Tutorial: How to Sort and Group UITableView by Date – Ole Begemann](https://oleb.net/blog/2011/12/tutorial-how-to-sort-and-group-uitableview-by-date) — 2011-12-02T17:40:00Z
  **NeKI brief:** Groups table-view records by calendar date after normalizing timestamps with an explicit calendar and time zone, separating sort keys from localized section-title presentation.
- [Date and Time Handling in Cocoa Cheat Sheet – Ole Begemann](https://oleb.net/blog/2011/11/date-and-time-in-cocoa-cheat-sheet) — 2011-11-23T18:00:00Z
  **NeKI brief:** Collects Cocoa date and time API distinctions, useful for checking formatter, calendar, time-zone, and locale responsibilities before treating a Date as a user-facing value.
- [Working with Date and Time in Cocoa (Part 2) – Ole Begemann](https://oleb.net/blog/2011/11/working-with-date-and-time-in-cocoa-part-2) — 2011-11-22T21:58:00Z
  **NeKI brief:** Continues Cocoa date handling with calendar calculations and formatter choices, stressing that human calendar concepts require explicit locale, calendar, and time-zone context.
- [Working with Date and Time in Cocoa (Part 1) – Ole Begemann](https://oleb.net/blog/2011/11/working-with-date-and-time-in-cocoa-part-1) — 2011-11-17T22:55:00Z
  **NeKI brief:** Explains the difference between absolute instants and calendar representations in Cocoa, helping avoid bugs caused by implicit time zones, locales, and date formatter assumptions.
- [Accessing Image Properties Without Loading the Image Into Memory – Ole Begemann](https://oleb.net/blog/2011/09/accessing-image-properties-without-loading-the-image-into-memory) — 2011-09-30T12:14:00Z
  **NeKI brief:** Reads image metadata through Image I/O without decoding full pixel data, a useful boundary when inspecting dimensions or EXIF information while controlling memory use.
- [The App Launch Sequence on iOS – Ole Begemann](https://oleb.net/blog/2011/06/app-launch-sequence-ios) — 2011-06-27T21:10:00Z
  **NeKI brief:** Traces iOS application launch callbacks and nib loading order so startup work is placed after required dependencies exist and before UI assumptions cause lifecycle bugs.
- [How Developers Should Handle All the Stuff Apple Introduced at WWDC – Ole Begemann](https://oleb.net/blog/2011/06/how-developers-should-handle-stuff-apple-introduced-at-wwdc) — 2011-06-07T18:09:00Z
  **NeKI brief:** Proposes a post-WWDC triage workflow: start with release notes and API diffs, then prioritize documentation, sessions, and controlled SDK experiments. Use the sequence to turn a large platform release into scoped engineering investigation.
- [Faking Instance Variables in Objective-C Categories With Associative References – Ole Begemann](https://oleb.net/blog/2011/05/faking-ivars-in-objc-categories-with-associative-references) — 2011-05-15T20:55:00Z
  **NeKI brief:** Shows how Objective-C associated objects can back category properties without subclassing or global maps. Use it when extending legacy objects, while keeping ownership policy, key uniqueness, and the inability to add real ivars explicit.
- [Using Cocoa to Convert Images From RGB to CMYK – Ole Begemann](https://oleb.net/blog/2011/05/using-cocoa-to-convert-images-from-rgb-to-cmyk) — 2011-05-12T20:02:00Z
  **NeKI brief:** Converts RGB images to CMYK by loading bitmap representations, changing color space, and writing output files while enumerating inputs concurrently. Useful for macOS batch utilities, though current color-management and ImageIO APIs should be verified.
- [Inspecting Core Data Attributes – Ole Begemann](https://oleb.net/blog/2011/05/inspecting-core-data-attributes) — 2011-05-04T21:35:00Z
  **NeKI brief:** Uses Core Data model introspection to inspect entities, property descriptions, and attribute types at runtime. Follow it when generic import, validation, or diagnostics code must adapt behavior to a managed object model instead of hard-coding fields.
- [New Site Design, Now Proudly Serving Static HTML – Ole Begemann](https://oleb.net/blog/2011/02/new-site-design-now-proudly-serving-static-html) — 2011-02-27T22:50:00Z
  **NeKI brief:** Describes a static-site publishing pipeline: author Markdown with metadata, compile and preview locally, commit to Git, then deploy generated output with rsync. The exact Nanoc/TextMate stack is historical, but the separation of source, build, preview, and deployment remains clear.
- [OBSlider, a UISlider Subclass With Variable Scrubbing Speed – Ole Begemann](https://oleb.net/blog/2011/01/obslider-a-uislider-subclass-with-variable-scrubbing-speed) — 2011-01-03T16:38:00Z
  **NeKI brief:** Implements variable-speed slider scrubbing by overriding UIControl tracking callbacks, measuring vertical touch offset, and scaling horizontal value changes through configurable thresholds. The Objective-C sample is historical, but the touch-tracking and control-event design remains useful for custom UIKit controls.
- [My Wish: Syntax Additions to Objective-C for Object Literals – Ole Begemann](https://oleb.net/blog/2010/12/syntax-additions-for-object-literals-to-objective-c) — 2010-12-22T11:07:00Z
  **NeKI brief:** Motivates Objective-C number, array, and dictionary literals by mapping concise syntax to their verbose factory-method equivalents, including Core Animation configuration. It provides useful historical context for reading legacy code that predates the literal syntax later adopted by the language.
- [Animating the Drawing of a CGPath With CAShapeLayer – Ole Begemann](https://oleb.net/blog/2010/12/animating-drawing-of-cgpath-with-cashapelayer) — 2010-12-18T17:57:00Z
  **NeKI brief:** Animates CAShapeLayer strokeEnd from zero to one to reveal a CGPath progressively, then synchronizes a keyframe-animated pen layer along the same path. The technique also connects text glyph paths to Core Text when the drawn path originates from typography.
- [Method Names in Objective-C – Ole Begemann](https://oleb.net/blog/2010/12/method-names-in-objective-c) — 2010-12-17T14:56:00Z
  **NeKI brief:** Explains that every keyword segment is part of an Objective-C selector and demonstrates that unlabeled later parameters are legal but harmful. Use it as a concise rationale for descriptive selector pieces when maintaining Objective-C APIs alongside modern Swift interfaces.
- [How to Debug an App That Was Launched by Push Notification or URL Handler – Ole Begemann](https://oleb.net/blog/2010/05/how-to-debug-app-launched-by-remote-event) — 2010-05-06T21:17:00Z
  **NeKI brief:** Shows two launch-debugging strategies for URL handlers and push events: inspect persistent logs when no debugger is attached, or configure the debugger to wait for the next process launch and stop at lifecycle breakpoints. Update the historical Xcode UI steps for current tooling.
- [OBGradientView: A Simple UIView Wrapper for CAGradientLayer – Ole Begemann](https://oleb.net/blog/2010/04/obgradientview-a-simple-uiview-wrapper-for-cagradientlayer) — 2010-04-20T13:15:00Z
  **NeKI brief:** Wraps CAGradientLayer in an OBGradientView UIView subclass, forwarding gradient properties while accepting UIColor arrays. The UIKit wrapper makes gradients autoresizable with ordinary view layout, avoiding manual layer management when a gradient should behave like a view background.
- [Porting RRGlossCausticShader to the iPhone – Ole Begemann](https://oleb.net/blog/2010/02/porting-rrglosscausticshader-to-the-iphone) — 2010-02-28T18:02:00Z
  **NeKI brief:** Porting a Core Graphics effect from AppKit to UIKit isolates platform color and graphics types behind a small adapter, so the rendering algorithm survives while platform-specific APIs stay at the boundary.
- [Mutable Properties of Immutable Objects – Ole Begemann](https://oleb.net/blog/2009/11/mutable-properties-of-immutable-objects) — 2009-11-30T21:30:00Z
  **NeKI brief:** An immutable Objective-C object must not expose mutable backing collections: publish an immutable view or copy while retaining internal mutation, otherwise callers can silently violate invariants and thread-safety assumptions.
- [OBShapedButton: Non-Rectangular Buttons on the iPhone – Ole Begemann](https://oleb.net/blog/2009/10/obshapedbutton-non-rectangular-buttons-on-the-iphone) — 2009-10-17T16:53:00Z
  **NeKI brief:** Nonrectangular button rendering is not enough for accurate interaction: hit testing must reject transparent image pixels so the control's touch target matches its visible shape. Reassess accessibility and performance with modern UIKit APIs.
- [The Music Player Framework in iPhone SDK 3.0 – Ole Begemann](https://oleb.net/blog/2009/07/the-music-player-framework-in-the-iphone-sdk) — 2009-07-13T13:53:00Z
  **NeKI brief:** MediaPlayer separates application and system music-player behavior, then uses playback notifications and a media-picker delegate to keep UI state synchronized with library selection. Treat the APIs as historical context and recheck current privacy requirements.
