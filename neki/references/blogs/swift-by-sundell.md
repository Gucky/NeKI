# Swift by Sundell

Third-party source index. It provides source attribution and routing metadata, not republished article content. Verify article conclusions independently before applying them.

- Archive: [https://www.swiftbysundell.com/archive/](https://www.swiftbysundell.com/archive/)
- Last collected: `2026-07-22T21:58:56Z`
- Indexed entries: **481**

- [Building a design system at Genius Scan | Swift by Sundell](https://www.swiftbysundell.com/articles/building-a-design-system-at-genius-scan)
  **Published:** `2025-09-01`
  **Topics:** Swift · SwiftUI · UIKit
  **NeKI brief:** Describes building a shared design system with reusable components, tokens, and constraints at Genius Scan. Useful for connecting SwiftUI component reuse to product consistency and team-scale maintenance.
- [Deciding between ‘let’ and ‘var’ for Swift struct properties | Swift by Sundell](https://www.swiftbysundell.com/articles/let-vs-var-for-swift-struct-properties)
  **Published:** `2025-07-23`
  **Topics:** Swift
  **NeKI brief:** Examines let versus var properties in Swift structs and how immutability affects mutation and API design. Useful for choosing value semantics deliberately in models and view state.
- [Decoding Swift types that require additional data | Swift by Sundell](https://www.swiftbysundell.com/articles/decoding-swift-types-that-require-additional-data)
  **Published:** `2025-06-30`
  **Topics:** Swift
  **NeKI brief:** Shows how CodableWithConfiguration injects required data while decoding Swift types, without optionals or decoding-only wrapper types. Use it for configuration-dependent models whose inputs are unavailable in the encoded payload.
- [Tips and tricks for when using SwiftUI’s ViewBuilder | Swift by Sundell](https://www.swiftbysundell.com/articles/swiftui-viewbuilder-tips-and-tricks)
  **Published:** `2025-05-30`
  **Topics:** Swift · SwiftUI · UIKit
  **NeKI brief:** Collects ViewBuilder techniques for conditional composition, custom containers, and readable APIs. Useful when designing result-builder-based components without hiding state or type constraints.
- [Using Swift’s defer keyword within async and throwing contexts | Swift by Sundell](https://www.swiftbysundell.com/articles/using-defer-within-async-and-throwing-contexts)
  **Published:** `2025-04-15`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Explains defer cleanup across async suspension and thrown errors. Use it when file handles, transactions, or temporary state must release reliably without duplicating cleanup paths.
- [Modern URL construction in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/modern-url-construction-in-swift)
  **Published:** `2025-03-31`
  **Topics:** Macros & Metaprogramming · Persistence & Synchronisation · Swift · Testing
  **NeKI brief:** Builds URLs with modern Foundation components rather than string concatenation. Use it when paths, query items, and percent encoding must remain correct under optional or user-provided values.
- [Building a declarative animation framework in Swift - Part 1 | Swift by Sundell](https://www.swiftbysundell.com/articles/building-a-declarative-animation-framework-in-swift-part-1)
  **Published:** `2023-04-07`
  **Topics:** Swift
  **NeKI brief:** Models UIKit view animations as composable, declarative operations instead of scattered animate calls. The framework separates animation descriptions from execution, making sequences and reusable transitions easier to assemble and test.
- [SwiftUI views versus modifiers | Swift by Sundell](https://www.swiftbysundell.com/articles/swiftui-views-versus-modifiers)
  **Published:** `2023-02-27`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Compares extracting SwiftUI behavior as a View versus a ViewModifier. Both can structure, style, and own state; the useful deciding question is conceptual hierarchy—use modifiers when the change is styling, not a new structural component.
- [Observing the content offset of a SwiftUI ScrollView | Swift by Sundell](https://www.swiftbysundell.com/articles/observing-swiftui-scrollview-content-offset)
  **Published:** `2023-02-09`
  **Topics:** Swift · SwiftUI · UIKit
  **NeKI brief:** Shows observing a SwiftUI ScrollView's content offset through preference propagation. Use it when implementing sticky headers, scroll-aware effects, or analytics without replacing ScrollView with a custom UIKit bridge.
- [Combining opaque return types with primary associated types | Swift by Sundell](https://www.swiftbysundell.com/articles/opaque-return-types-primary-associated-types)
  **Published:** `2022-11-12`
  **Topics:** Swift
  **NeKI brief:** Shows how primary associated types let protocols express their key generic parameter, while opaque returns preserve a concrete conforming type without Any-erasure. This combination is useful for type-safe factories and lightweight abstraction boundaries.
- [Switching between SwiftUI’s HStack and VStack | Swift by Sundell](https://www.swiftbysundell.com/articles/switching-between-swiftui-hstack-vstack)
  **Published:** `2022-07-08`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Builds a dynamic stack that chooses HStack or VStack while keeping a single content declaration. The approach uses a custom layout abstraction to preserve call-site ergonomics when orientation depends on size or context.
- [Using the ‘some’ and ‘any’ keywords to reference generic protocols in Swift 5.7 | Swift by Sundell](https://www.swiftbysundell.com/articles/referencing-generic-protocols-with-some-and-any-keywords)
  **Published:** `2022-06-09`
  **Topics:** Swift
  **NeKI brief:** Explains Swift 5.7's explicit distinction between opaque some and existential any for generic protocols. Use it to decide whether an API should hide one concrete type or accept heterogeneous conformers at runtime.
- [Organizing default argument values | Swift by Sundell](https://www.swiftbysundell.com/tips/organizing-default-argument-values)
  **Published:** `2022-06-07`
  **Topics:** Swift
  **NeKI brief:** Demonstrates placing default argument construction in static members so call sites stay concise without hiding configuration. It helps keep defaults discoverable and avoids repeating setup expressions across initializers or functions.
- [Swift 5.7’s new optional unwrapping syntax | Swift by Sundell](https://www.swiftbysundell.com/articles/swifts-new-shorthand-optional-unwrapping-syntax)
  **Published:** `2022-06-07`
  **Topics:** Swift
  **NeKI brief:** Introduces Swift 5.7 shorthand if-let and guard-let syntax, including multiple optional bindings. It reduces naming noise while retaining the same early-exit and scope semantics, useful in validation-heavy code.
- [Rendering SwiftUI views within UITableView or UICollectionView cells on iOS 16 | Swift by Sundell](https://www.swiftbysundell.com/articles/rendering-swiftui-views-within-uitableview-or-uicollectionview)
  **Published:** `2022-06-07`
  **Topics:** Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Embeds SwiftUI views in UITableView or UICollectionView cells. Use it for incremental UIKit modernization while preserving reuse, sizing, and cell lifecycle behavior.
- [Q&A: When does the order of SwiftUI modifiers matter, and why? | Swift by Sundell](https://www.swiftbysundell.com/questions/swiftui-modifier-order)
  **Published:** `2022-05-07`
  **Topics:** Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Uses concrete SwiftUI examples to show why modifier order can change the resulting view hierarchy, layout, and rendering. Follow it when a seemingly equivalent chain produces different padding, backgrounds, or hit-testing behavior.
- [Using Combine’s futures and subjects | Swift by Sundell](https://www.swiftbysundell.com/articles/using-combine-futures-and-subjects)
  **Published:** `2022-05-07`
  **Topics:** Swift · Testing
  **NeKI brief:** Shows how Future adapts one-shot callback results and subjects expose externally-driven events without writing custom publishers. The distinction helps choose ownership and replay semantics when adding Combine to existing APIs.
- [A guide to the SwiftUI layout system - Part 1 | Swift by Sundell](https://www.swiftbysundell.com/articles/swiftui-layout-system-guide-part-1)
  **Published:** `2022-05-07`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Derives SwiftUI layout behavior by composing frames, stacks, spacers, and alignment rather than relying on imperative measurement. It is a useful mental model for understanding proposal and response interactions in adaptive screens.
- [Using Swift’s concurrency system to run multiple tasks in parallel | Swift by Sundell](https://www.swiftbysundell.com/articles/swift-concurrency-multiple-tasks-in-parallel)
  **Published:** `2022-05-07`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Compares async let, task groups, and unstructured Tasks for parallel work. The choice depends on whether child count is fixed, dynamic, or independently managed, with cancellation and error propagation differing accordingly.
- [Rule-based logic in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/rule-based-logic-in-swift)
  **Published:** `2022-05-07`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Refactors branching decisions into ordered rule objects or functions that each decide whether they apply. This local strategy makes business logic composable, independently testable, and easier to extend than a growing conditional.
- [Making SwiftUI views refreshable | Swift by Sundell](https://www.swiftbysundell.com/articles/making-swiftui-views-refreshable)
  **Published:** `2022-05-07`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Explains refreshable's async contract and how SwiftUI keeps refresh UI active until the awaited operation completes. The same mechanism can drive custom reload controls while centralizing loading and error handling.
- [Ignoring invalid JSON elements when using Codable | Swift by Sundell](https://www.swiftbysundell.com/articles/ignoring-invalid-json-elements-codable)
  **Published:** `2022-05-07`
  **Topics:** Swift
  **NeKI brief:** Adds a lossy Codable wrapper that attempts each array element and skips those that fail decoding. Use it only when partial results are acceptable; otherwise Codable's all-or-nothing failure preserves data integrity.
- [Performing POST and file upload requests using URLSession | Swift by Sundell](https://www.swiftbysundell.com/articles/http-post-and-file-upload-requests-using-urlsession)
  **Published:** `2022-05-07`
  **Topics:** Networking · Swift
  **NeKI brief:** Constructs POST requests and multipart file uploads directly with URLSession, including headers, body encoding, and response handling. It clarifies when Foundation is sufficient and where request-format details become the real complexity.
- [Formatting numbers in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/formatting-numbers-in-swift)
  **Published:** `2022-05-07`
  **Topics:** Persistence & Synchronisation · Swift
  **NeKI brief:** Covers localized number formatting in Swift. Use it when values require locale-aware display, rounding, currency, or measurement rules instead of manual string interpolation.
- [Controlling the timing of a Combine pipeline | Swift by Sundell](https://www.swiftbysundell.com/articles/controlling-the-timing-of-a-combine-pipeline)
  **Published:** `2022-05-07`
  **Topics:** Swift
  **NeKI brief:** Uses Combine operators to debounce input, defer work, and retry after delays. These timing choices prevent redundant requests and smooth transient failures, but require scheduler control to remain deterministic in tests.
- [Type placeholders in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/type-placeholders-in-swift)
  **Published:** `2022-04-14`
  **Topics:** Swift
  **NeKI brief:** Introduces Swift 5.6 type placeholders for specifying one generic argument while leaving others to inference. This is particularly useful with types such as CurrentValueSubject where the compiler cannot infer every parameter from a value alone.
- [Abstract types and methods in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/abstract-types-and-methods)
  **Published:** `2022-03-15`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Compares abstract base classes, protocols, and protocol compositions for shared model-loading APIs. The trade-off is between inherited implementation and value-oriented flexibility, with explicit failure paths needed when a base operation is not implemented.
- [Swift actors: How do they work, and what kinds of problems do they solve? | Swift by Sundell](https://www.swiftbysundell.com/articles/swift-actors)
  **Published:** `2022-03-07`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Explains Swift actors as isolated mutable-state containers. Use it when concurrent tasks share data and serialization is safer than manually locking every access.
- [Equality | Swift by Sundell](https://www.swiftbysundell.com/basics/equality)
  **Published:** `2022-03-04`
  **Topics:** Swift
  **NeKI brief:** Explains Equatable's value comparison, reference identity via ===, and conditional collection conformances. The distinction matters when model equality should represent content while object identity tracks the same instance.
- [Writing testable code when using SwiftUI | Swift by Sundell](https://www.swiftbysundell.com/articles/writing-testable-code-when-using-swiftui)
  **Published:** `2022-02-17`
  **Topics:** Concurrency · Swift · SwiftUI · Testing
  **NeKI brief:** Moves stateful UI decisions into independently testable types and injects dependencies at the view boundary. This keeps SwiftUI declarations thin while allowing behavior to be verified without rendering the entire interface.
- [Combining protocols in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/combining-protocols-in-swift)
  **Published:** `2022-02-15`
  **Topics:** Swift
  **NeKI brief:** Surveys protocol extensions, composition, and dedicated wrapper types for combining capabilities. It helps avoid forcing unrelated responsibilities into one protocol and makes the resulting abstraction's ownership explicit.
- [Implementing throwing protocol functions as non-throwing | Swift by Sundell](https://www.swiftbysundell.com/tips/implementing-throwing-protocol-functions-as-non-throwing)
  **Published:** `2022-02-09`
  **Topics:** Swift
  **NeKI brief:** Shows that a non-throwing implementation can satisfy a throwing protocol requirement, while existential calls still use try. This lets infallible conformers stay simple without weakening a protocol that permits fallible implementations.
- [Memory management when using async/await in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/memory-management-when-using-async-await)
  **Published:** `2022-02-03`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Examines how Tasks retain captured objects across suspension and how weak captures can alter lifetime and cancellation behavior. Use the patterns to avoid accidental retention while ensuring required work still has an owner.
- [Automatically retrying an asynchronous Swift Task | Swift by Sundell](https://www.swiftbysundell.com/articles/retrying-an-async-swift-task)
  **Published:** `2022-01-25`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Builds a retry loop around an async operation with bounded attempts and error propagation. A production implementation should additionally respect cancellation and distinguish transient failures from errors that should fail immediately.
- [When can a struct’s memberwise initializer be used? | Swift by Sundell](https://www.swiftbysundell.com/tips/when-can-memberwise-initializers-be-used)
  **Published:** `2022-01-21`
  **Topics:** Swift
  **NeKI brief:** Clarifies when Swift synthesizes a struct's memberwise initializer and which stored properties participate. Adding custom initializers or changing access levels can alter availability, so this is useful when designing construction APIs.
- [Backgrounds and overlays in SwiftUI | Swift by Sundell](https://www.swiftbysundell.com/articles/backgrounds-and-overlays-in-swiftui)
  **Published:** `2022-01-20`
  **Topics:** Swift · SwiftUI · Xcode
  **NeKI brief:** Compares ZStack, background, and overlay for layering SwiftUI content. Their sizing and alignment rules differ, so choosing deliberately prevents decorative views from unexpectedly changing layout or hit-testing.
- [Loops | Swift by Sundell](https://www.swiftbysundell.com/basics/loops)
  **Published:** `2022-01-13`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Contrasts for-in and forEach iteration, including control-flow differences such as break, continue, and early return. The choice affects readability and whether the loop needs imperative flow control.
- [Creating Combine-compatible versions of async/await-based APIs | Swift by Sundell](https://www.swiftbysundell.com/articles/creating-combine-compatible-versions-of-async-await-apis)
  **Published:** `2022-01-05`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Bridges async functions to Combine publishers by wrapping task execution and forwarding completion or failure. The adapter preserves each framework's calling style while making cancellation and subscription lifetime explicit.
- [Type-safe identifiers in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/type-safe-identifiers-in-swift)
  **Published:** `2022-01-03`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Builds identifier wrappers that prevent mixing IDs for different model types, then relates the pattern to Swift's later Identifiable protocol. Stronger types move accidental cross-entity lookups from runtime bugs to compiler errors.
- [Task-based concurrency in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/task-based-concurrency-in-swift)
  **Published:** `2022-01-03`
  **Topics:** Concurrency · Networking · Swift
  **NeKI brief:** Frames Tasks as a focused abstraction for asynchronous work, distinct from futures and Operation. Their lifetime and cancellation model make them suitable for scoped operations, but not automatically a replacement for every queue or workflow.
- [Making async system APIs backward compatible | Swift by Sundell](https://www.swiftbysundell.com/articles/making-async-system-apis-backward-compatible)
  **Published:** `2022-01-03`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Uses continuations to wrap iOS 15-only async system APIs behind availability-aware implementations. The pattern preserves one async-facing call site while retaining callback-based compatibility on older deployment targets.
- [Two ways of capturing self strongly within a closure | Swift by Sundell](https://www.swiftbysundell.com/articles/two-ways-of-capturing-self-strongly)
  **Published:** `2022-01-02`
  **Topics:** Swift
  **NeKI brief:** Compares explicit self references with capture lists for intentionally strong closure captures. The key decision is ownership: strong capture is safe for non-retained callbacks but can form a cycle when the closure is stored by self.
- [Unit testing Combine-based Swift code | Swift by Sundell](https://www.swiftbysundell.com/articles/unit-testing-combine-based-swift-code)
  **Published:** `2021-12-27`
  **Topics:** Swift · Testing
  **NeKI brief:** Tests Combine pipelines by waiting for publisher completion and collecting outputs, with helper utilities to reduce XCTest boilerplate. Deterministic subscriptions and cancellation checks are more valuable than asserting only the first emitted value.
- [Building an asynchronous SwiftUI button | Swift by Sundell](https://www.swiftbysundell.com/articles/building-an-async-swiftui-button)
  **Published:** `2021-12-22`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Encapsulates an async action in a reusable SwiftUI button and disables repeated taps while work is in flight. The control centralizes task state, spinner presentation, and completion handling instead of duplicating guards in each view.
- [Connecting async/await to other Swift code | Swift by Sundell](https://www.swiftbysundell.com/articles/connecting-async-await-with-other-swift-code)
  **Published:** `2021-12-17`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Presents continuation and Task-based adapters for connecting async/await with callback APIs, delegates, and Combine. These boundaries ease incremental migration while making resumption, cancellation, and single-completion guarantees explicit.
- [What role do Tasks play within Swift’s concurrency system? | Swift by Sundell](https://www.swiftbysundell.com/articles/the-role-tasks-play-in-swift-concurrency)
  **Published:** `2021-12-13`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Frames Task as the handle for starting, observing, and cancelling asynchronous work, including inherited actor context and awaited results. This makes lifecycle ownership explicit instead of letting detached work outlive the UI that initiated it.
- [Delaying an asynchronous Swift Task | Swift by Sundell](https://www.swiftbysundell.com/articles/delaying-an-async-swift-task)
  **Published:** `2021-12-13`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Uses Task.sleep to delay async work without blocking a thread, a better fit for debounce-like operations than synchronous sleeps. The workflow still needs cancellation handling, because a delayed task may become irrelevant before its wake-up.
- [Lightweight dependency injection and unit testing using async functions | Swift by Sundell](https://www.swiftbysundell.com/articles/dependency-injection-and-unit-testing-using-async-await)
  **Published:** `2021-12-09`
  **Topics:** Architecture · Concurrency · Dependency Injection · Networking · Swift · Testing
  **NeKI brief:** Builds lightweight async tests by injecting a networking dependency and replacing it with protocol-based mocks. The pattern keeps asynchronous production code intact while making response timing and failure paths deterministic enough to test.
- [Improving Swift compile times | Swift by Sundell](https://www.swiftbysundell.com/articles/improving-swift-compile-times)
  **Published:** `2021-11-22`
  **Topics:** Swift · Testing
  **NeKI brief:** Starts compile-time work by gathering measurements, then fixes warnings and structural hotspots rather than guessing at settings. The diagnostic workflow is the lasting takeaway: quantify the slow target before trading code clarity for build speed.
- [Unit testing Swift code that uses async/await | Swift by Sundell](https://www.swiftbysundell.com/articles/unit-testing-code-that-uses-async-await)
  **Published:** `2021-11-16`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Shows how to test async/await code by awaiting real task results, injecting clocks or dependencies where timing matters, and asserting thrown errors without reverting to expectation-based sleeps.
- [Async/await in Swift unit tests | Swift by Sundell](https://www.swiftbysundell.com/articles/asyncawait-in-swift-unit-tests)
  **Published:** `2021-11-16`
  **Topics:** Concurrency · Swift · Testing · Xcode
  **NeKI brief:** Adapts unit tests to async/await so assertions can await the operation directly instead of coordinating expectations manually. It reduces synchronization noise, while the discussion of added complexity helps identify tests that still need explicit eventual behavior.
- [Programmatic navigation in SwiftUI | Swift by Sundell](https://www.swiftbysundell.com/articles/swiftui-programmatic-navigation)
  **Published:** `2021-11-11`
  **Topics:** Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Builds programmatic SwiftUI navigation from state. Use it when a feature must route after async work or a deep link instead of only after a user tap.
- [Using count vs isEmpty to check whether a collection contains any elements | Swift by Sundell](https://www.swiftbysundell.com/articles/count-vs-isEmpty)
  **Published:** `2021-11-11`
  **Topics:** Swift
  **NeKI brief:** Recommends isEmpty when only emptiness matters, avoiding a potentially unnecessary count traversal for collections without constant-time counts. The small API choice communicates intent and keeps generic collection code efficient without changing its result.
- [Building async and concurrent versions of forEach and map | Swift by Sundell](https://www.swiftbysundell.com/articles/async-and-concurrent-forEach-and-map)
  **Published:** `2021-11-10`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Derives asynchronous and concurrent collection transforms from ordinary forEach/map semantics. The distinction matters: concurrency improves throughput for independent work, but ordering, cancellation, and task-group error propagation remain part of the API contract.
- [Working on async code in a playground | Swift by Sundell](https://www.swiftbysundell.com/tips/working-on-async-code-in-a-playground)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Uses a playground as a small async experiment surface, making it easier to probe concurrency APIs before integrating them into an app. Treat it as a diagnostic workflow, not production execution, since lifecycle and tooling differ.
- [Variable shadowing | Swift by Sundell](https://www.swiftbysundell.com/tips/variable-shadowing)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Shows how a local binding can intentionally shadow an outer value to narrow scope and improve naming. Use the technique sparingly: it reduces repetition, but accidental shadowing can hide which state a closure actually captures.
- [Using zip | Swift by Sundell](https://www.swiftbysundell.com/tips/using-zip)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses zip to traverse two sequences in lockstep, producing pairs without manual index bookkeeping. Because iteration stops at the shorter sequence, it is useful for aligned data but unsuitable when unequal lengths must be diagnosed.
- [Using where with for-loops | Swift by Sundell](https://www.swiftbysundell.com/tips/using-where-with-for-loops)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Places filtering conditions directly in a for-in where clause, keeping iteration and selection together without a separate if nest. This improves scanability for simple predicates, while complex conditions may deserve a named helper.
- [Using variadic parameters | Swift by Sundell](https://www.swiftbysundell.com/tips/using-variadic-parameters)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses variadic parameters for APIs that naturally accept a variable number of homogeneous values. The call site stays concise, but the single-array representation is preferable when values already arrive dynamically or need later mutation.
- [Using typealiases to reduce the length of method signatures | Swift by Sundell](https://www.swiftbysundell.com/tips/using-typealiases-to-reduce-the-length-of-method-signatures)
  **Published:** `2021-10-30`
  **Topics:** Swift · Testing
  **NeKI brief:** Shortens repeated generic or closure-heavy signatures with typealiases, making declarations easier to read and refactor. Keep aliases near the domain they describe so reduced visual noise does not hide important type relationships.
- [Using type aliases to give semantic meaning to primitives | Swift by Sundell](https://www.swiftbysundell.com/tips/using-type-aliases-to-give-semantic-meaning-to-primitives)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses type aliases to give semantic names to primitive values such as identifiers, making function signatures readable without runtime wrappers. The trade-off is documentation rather than stronger type isolation; distinct aliases can still be interchangeable.
- [Using "then" as an external parameter label for closures | Swift by Sundell](https://www.swiftbysundell.com/tips/using-then-as-an-external-parameter-label-for-closures)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses an external then label to make trailing closure call sites read like a sequence of operations. It improves fluent APIs, though labels should describe ordering semantics rather than disguise unrelated callbacks.
- [Using the where clause with associated types | Swift by Sundell](https://www.swiftbysundell.com/tips/using-the-where-clause-with-associated-types)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Applies where constraints to associated types so a protocol can express relationships between its generic pieces. This moves invalid combinations into compile-time checking instead of scattering runtime casts across conformances.
- [Comparing objects by instance | Swift by Sundell](https://www.swiftbysundell.com/tips/using-the-triple-equals-operator-to-compare-objects-by-instance)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Uses identity comparison with === when the question is whether two references point to the same instance, not whether their values are equal. That distinction prevents value equality implementations from masking ownership or cache bugs.
- [Using the guard statement in different scopes | Swift by Sundell](https://www.swiftbysundell.com/tips/using-the-guard-statement-in-many-different-scopes)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Demonstrates guard in functions, loops, and closures to exit early while keeping the success path unindented. The pattern is clearest when each guard checks one invariant and its exit explains the failure boundary.
- [Using test assertion messages as comments | Swift by Sundell](https://www.swiftbysundell.com/tips/using-test-assertion-messages-as-comments)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Adds contextual assertion messages so failures explain the intended invariant at the failure site. This complements, rather than replaces, precise assertions and keeps test output useful when many similar values are checked.
- [Using SwiftUI in a playground | Swift by Sundell](https://www.swiftbysundell.com/tips/using-swiftui-without-the-macos-beta)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Uses a playground to experiment with SwiftUI before a full app target is available. It is a lightweight learning workflow, but platform SDK availability and preview behavior still need verification in Xcode's real project context.
- [Using SwiftUI’s ForEach with raw values | Swift by Sundell](https://www.swiftbysundell.com/tips/using-swiftui-foreach-with-raw-values)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI · Xcode
  **NeKI brief:** Builds ForEach content from raw values by supplying stable identity, turning strings or integers into views without inventing model types. Stability matters: changing identifiers can cause SwiftUI to recreate stateful child views.
- [Using Swift’s built-in randomization APIs | Swift by Sundell](https://www.swiftbysundell.com/tips/using-swifts-built-in-randomization-apis)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses standard-library randomization APIs instead of hand-rolled generators, keeping random element and shuffle operations consistent with collection types. Tests should inject deterministic data when behavior depends on a random choice.
- [Using shared UserDefaults suites | Swift by Sundell](https://www.swiftbysundell.com/tips/using-shared-userdefaults-suites)
  **Published:** `2021-10-30`
  **Topics:** Persistence & Synchronisation · Swift
  **NeKI brief:** Shows shared UserDefaults suites as an explicit storage boundary for app extensions or cooperating targets. The suite improves sharing without global key collisions, but callers must coordinate keys and understand that values are not a secure secret store.
- [Using Self to refer to enclosing types | Swift by Sundell](https://www.swiftbysundell.com/tips/using-self-to-refer-to-enclosing-types)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Uses Self inside generic-type extensions to refer to the enclosing concrete specialization without repeating generic parameters. This keeps extensions compact while preserving static typing for factory methods and nested helpers.
- [Using self-executing closures for lazy properties | Swift by Sundell](https://www.swiftbysundell.com/tips/using-self-executing-closures-for-lazy-properties)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Initializes a lazy property with a self-executing closure so related setup stays beside the declaration. It improves locality for immutable configuration, but captured self and initialization order still deserve review.
- [Using property observers | Swift by Sundell](https://www.swiftbysundell.com/tips/using-property-observers)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses willSet and didSet to react to stored-property changes without replacing the property with a custom accessor. Observers are synchronous and can trigger cascading writes, so keep side effects bounded and predictable.
- [Using map to transform an optional into a Result type | Swift by Sundell](https://www.swiftbysundell.com/tips/using-map-to-transform-an-optional-into-a-result-type)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Maps an optional into a Result when absence needs an explicit failure value, preserving functional composition while improving diagnostics. It is a narrow conversion tool, not a substitute for modeling errors that carry richer context.
- [Using key paths in switch statements | Swift by Sundell](https://www.swiftbysundell.com/tips/using-key-paths-in-switch-statements)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Shows key paths as switchable values, allowing generic code to select a property without string reflection. This preserves compiler checking, although a key-path branch should remain small enough to keep the selected behavior obvious.
- [Using #function for UserDefaults key consistency | Swift by Sundell](https://www.swiftbysundell.com/tips/using-function-for-userdefaults-key-consistency)
  **Published:** `2021-10-30`
  **Topics:** Persistence & Synchronisation · Swift
  **NeKI brief:** Uses #function to derive UserDefaults keys from accessor names, reducing mismatches between reads and writes during refactors. The convenience couples persistence format to symbols, so explicit stable keys remain safer for migrations.
- [Using first class functions when iterating over a dictionary | Swift by Sundell](https://www.swiftbysundell.com/tips/using-first-class-functions-when-iterating-over-a-dictionary)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Applies first-class functions such as map or forEach when traversing dictionary contents, keeping transformation logic composable. Dictionary ordering is not a presentation contract, so sort explicitly when output order matters.
- [Using feature flags instead of feature branches | Swift by Sundell](https://www.swiftbysundell.com/tips/using-feature-flags-instead-of-feature-branches)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses feature flags to merge incomplete behavior behind runtime or configuration checks rather than maintaining long-lived branches. Flags enable incremental delivery, but require ownership, cleanup dates, and tests for both paths.
- [Using enums for async result types | Swift by Sundell](https://www.swiftbysundell.com/tips/using-enums-for-async-result-types)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Models asynchronous outcomes with an enum so success, loading, and failure states remain mutually explicit. This avoids state-specific optionals whose combinations are invalid, while associated values retain useful payloads and errors.
- [Using dot syntax for static properties and initializers | Swift by Sundell](https://www.swiftbysundell.com/tips/using-dot-syntax-for-static-properties-and-initializers)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses Swift dot syntax to select static properties or initializers when the expected type is known, making factory-style call sites concise. The shorthand improves readability for domain values but can obscure type inference in heavily generic code.
- [Using DispatchWorkItem | Swift by Sundell](https://www.swiftbysundell.com/tips/using-dispatchworkitem)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Uses DispatchWorkItem to encapsulate cancellable queued work and submit it to a dispatch queue. It is a focused legacy-GCD tool; new async code should compare Task cancellation semantics before introducing another scheduler abstraction.
- [Using closure types in generic constraints | Swift by Sundell](https://www.swiftbysundell.com/tips/using-closure-types-in-generic-constraints)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Constrains generic APIs with closure types to describe callbacks precisely at compile time. The technique improves reuse without protocol boilerplate, but complex closure signatures can hurt readability and should be aliased near the domain.
- [Using auto closures | Swift by Sundell](https://www.swiftbysundell.com/tips/using-auto-closures)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses @autoclosure to delay evaluating an argument until the callee needs it, useful for assertions and lightweight logging. Delayed evaluation can hide work and side effects, so reserve it for APIs where laziness is obvious.
- [Using associated enum values to avoid state-specific optionals | Swift by Sundell](https://www.swiftbysundell.com/tips/using-associated-enum-values-to-avoid-state-specific-optionals)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Stores related state in enum associated values instead of several optionals whose combinations can contradict one another. Pattern matching then makes transitions exhaustive, forcing callers to handle each valid state deliberately.
- [Using an AppDelegate with the new SwiftUI-based app lifecycle | Swift by Sundell](https://www.swiftbysundell.com/tips/using-an-app-delegate-with-swiftui-app-lifecycle)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI · UIKit
  **NeKI brief:** Bridges legacy UIApplicationDelegate callbacks into a SwiftUI App lifecycle for services that still depend on them. Keep the delegate adapter thin so scene and view state remain owned by SwiftUI.
- [Using a name already taken by the standard library | Swift by Sundell](https://www.swiftbysundell.com/tips/using-a-name-already-taken-by-the-standard-library)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Shows how to disambiguate a domain API whose name overlaps a standard-library symbol, preserving readable call sites without shadowing surprises. Explicit qualification is a useful escape hatch when inference chooses the wrong declaration.
- [Using a custom exception handler | Swift by Sundell](https://www.swiftbysundell.com/tips/using-a-custom-exception-handler)
  **Published:** `2021-10-30`
  **Topics:** Swift · Testing
  **NeKI brief:** Installs a custom exception handler for diagnosing Objective-C exceptions that ordinary Swift error handling cannot catch. Treat it as a debugging boundary only, since continuing after an exception may leave process state corrupted.
- [Useful Codable extensions | Swift by Sundell](https://www.swiftbysundell.com/tips/useful-codable-extensions)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Collects Codable extensions that reduce repetitive encoding and decoding glue while preserving typed models. Adopt helpers selectively: convenience should not hide schema migrations, date strategies, or the exact failure surface of a payload.
- [Usages of throwing functions | Swift by Sundell](https://www.swiftbysundell.com/tips/usages-of-throwing-functions)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Shows throwing functions as a way to propagate failure without sentinel values, including when to catch and translate errors. The workflow keeps recovery near the layer with enough context to make a meaningful decision.
- [Unwrapping an optional or throwing an error | Swift by Sundell](https://www.swiftbysundell.com/tips/unwrapping-an-optional-or-throwing-an-error)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Converts missing optional data into a thrown error at the boundary where absence becomes invalid. This keeps downstream code non-optional, but the chosen error should preserve enough context for diagnosis and user-facing recovery.
- [UIView bounds and transforms | Swift by Sundell](https://www.swiftbysundell.com/tips/uiview-bounds-and-transforms)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Explains why UIView bounds and transforms interact differently from frame coordinates, especially during rotation or scaling. Use bounds for local drawing and frame for superview placement, avoiding geometry calculations that mix coordinate spaces.
- [UIKit default arguments | Swift by Sundell](https://www.swiftbysundell.com/tips/uikit-default-arguments)
  **Published:** `2021-10-30`
  **Topics:** Swift · UIKit
  **NeKI brief:** Uses default arguments to make UIKit convenience APIs flexible without overload proliferation. Defaults should represent the common behavior and remain source-compatible, while uncommon configuration deserves an explicit parameter or builder.
- [Type inference for lazy properties in Swift | Swift by Sundell](https://www.swiftbysundell.com/tips/type-inference-for-lazy-properties-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Shows how contextual type inference can simplify lazy-property declarations while retaining a concrete collection or closure type. Rely on inference for local clarity, but annotate when the initializer's generic result is ambiguous.
- [Throwing tests and LocalizedError | Swift by Sundell](https://www.swiftbysundell.com/tips/throwing-tests-and-localizederror)
  **Published:** `2021-10-30`
  **Topics:** Swift · Testing
  **NeKI brief:** Uses a throwing test and LocalizedError to express expected failure paths with domain-readable messages. Throwing keeps setup linear, while assertions should still verify behavior rather than merely matching error text.
- [The rule of threes | Swift by Sundell](https://www.swiftbysundell.com/tips/the-rule-of-threes)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Applies the rule of threes before extracting an abstraction: wait until a pattern appears repeatedly enough to reveal its stable shape. This limits premature helpers, trading short-term duplication for better design evidence.
- [The power of variadic parameters | Swift by Sundell](https://www.swiftbysundell.com/tips/the-power-of-variadic-parameters)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses variadic parameters to create expressive APIs for a variable number of homogeneous values. The syntax is ergonomic for literals, but dynamic callers may need array overloads to avoid unnecessary splatting or conversion.
- [Using key paths to create convenience APIs | Swift by Sundell](https://www.swiftbysundell.com/tips/the-power-of-key-paths)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses key paths to build convenience APIs, reducing repetitive closures while preserving compile-time member selection and readable call sites.
- [The flexible syntax of enums | Swift by Sundell](https://www.swiftbysundell.com/tips/the-flexible-syntax-of-enums)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Explores enum syntax for associated and computed behavior, showing how one type can keep state and operations cohesive.
- [The ‘final’ keyword | Swift by Sundell](https://www.swiftbysundell.com/tips/the-final-keyword)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Explains final as an inheritance and dispatch decision, helping prevent unsupported subclassing while enabling more predictable optimization and clearer ownership boundaries.
- [The difference between static and class properties | Swift by Sundell](https://www.swiftbysundell.com/tips/the-difference-between-static-and-class-properties)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Compares static and class members, including whether subclasses can override them. Static is fixed to the declaring type; class enables polymorphic customization, so choosing one communicates extension intent.
- [Testing custom Codable implementations | Swift by Sundell](https://www.swiftbysundell.com/tips/testing-custom-codable-implementations)
  **Published:** `2021-10-30`
  **Topics:** Swift · Testing
  **NeKI brief:** Tests custom Codable implementations with representative encoded payloads and failure cases instead of trusting synthesis. Keeping fixtures small makes schema regressions visible, while round-trip tests alone may miss compatibility with older formats.
- [Testing code that uses static APIs | Swift by Sundell](https://www.swiftbysundell.com/tips/testing-code-that-uses-static-apis)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Introduces seams for code calling static APIs so tests can supply deterministic collaborators. The trade-off is a small abstraction around global behavior, buying isolation without requiring a full dependency framework.
- [Switching on multiple values | Swift by Sundell](https://www.swiftbysundell.com/tips/switching-on-multiple-values)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses tuple patterns to switch on multiple values simultaneously, keeping related branching exhaustive and readable. This avoids nested switches, but branch conditions should remain small enough that the tuple's meaning stays apparent.
- [Switching on a set | Swift by Sundell](https://www.swiftbysundell.com/tips/switching-on-a-set)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses Set pattern matching in switches, expressing membership-based branching without repeatedly searching collections or duplicating membership checks across branches.
- [SwiftUI mix and match | Swift by Sundell](https://www.swiftbysundell.com/tips/swiftui-mix-and-match)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Mixes SwiftUI and UIKit views at a narrow boundary, enabling incremental adoption while retaining existing lifecycle ownership and navigation control.
- [SwiftUI is a game changer | Swift by Sundell](https://www.swiftbysundell.com/tips/swiftui-is-a-game-changer)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Summarizes SwiftUI's declarative state-driven rendering and its trade-off against imperative view mutation. The useful routing point is architectural: model state and identity first, then choose framework boundaries.
- [SwiftUI extensions using generic type constraints | Swift by Sundell](https://www.swiftbysundell.com/tips/swiftui-extensions-using-generics)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Uses generic constraints on SwiftUI extensions to expose helpers only for compatible view types. Constrained extensions preserve fluent APIs while preventing invalid modifiers from appearing everywhere through unconstrained overloads.
- [Generating automatic placeholders for SwiftUI views | Swift by Sundell](https://www.swiftbysundell.com/tips/swiftui-automatic-placeholders)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI · UIKit
  **NeKI brief:** Generates SwiftUI placeholders from view structure. Use it when skeleton loading UI should mirror final layout without manually duplicating every row and shape.
- [Swift’s composition operator | Swift by Sundell](https://www.swiftbysundell.com/tips/swifts-composition-operator)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Builds a composition operator for functions, making transformation pipelines readable while exposing type and error-propagation trade-offs in real call chains.
- [Combined Swift packages | Swift by Sundell](https://www.swiftbysundell.com/tips/swift-packages-containing-both-a-command-line-tool-and-a-library)
  **Published:** `2021-10-30`
  **Topics:** Dependency Injection · Swift · Swift Package Manager
  **NeKI brief:** Combines a command-line tool and library in one Swift package, separating executable and library targets while sharing source infrastructure.
- [Structuring UI tests as extensions on XCUIApplication | Swift by Sundell](https://www.swiftbysundell.com/tips/structuring-ui-tests-as-extensions-on-xcuiapplication)
  **Published:** `2021-10-30`
  **Topics:** Swift · Testing
  **NeKI brief:** Adds semantic UI-test actions as XCUIApplication extensions, centralizing launch and navigation mechanics. Tests read like user workflows, while extension methods must remain thin to avoid hiding assertions and timing assumptions.
- [Struct convenience initializers | Swift by Sundell](https://www.swiftbysundell.com/tips/struct-convenience-initializers)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Shows convenience initializers on structs as delegating construction paths for common defaults. Keep the designated initializer as the invariant boundary, using convenience forms only for ergonomic alternatives.
- [String-based enums in string interpolation | Swift by Sundell](https://www.swiftbysundell.com/tips/string-based-enums-in-string-interpolation)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses RawRepresentable string enums in interpolation to retain semantic values while producing readable output. This avoids scattered literal conversions, but raw strings remain part of the persistence or wire-format contract.
- [Statically computed default property values | Swift by Sundell](https://www.swiftbysundell.com/tips/statically-computed-default-property-values)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses static computation for default property values. Use it when an initializer default needs shared calculation without repeating logic or relying on mutable global setup.
- [Stacking views in SwiftUI | Swift by Sundell](https://www.swiftbysundell.com/tips/stacking-views-in-swiftui)
  **Published:** `2021-10-30`
  **Topics:** Observation & State Management · Swift · SwiftUI · UIKit
  **NeKI brief:** Composes SwiftUI stacks to express layout hierarchy, clarifying when container choice affects alignment, spacing, adaptive behavior, and readability.
- [Specializing protocols using constraints | Swift by Sundell](https://www.swiftbysundell.com/tips/specializing-protocols-using-constraints)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Specializes protocol extensions with generic constraints, adding behavior only where associated-type guarantees make it valid and preventing overly broad APIs.
- [Specializing generics with type aliases | Swift by Sundell](https://www.swiftbysundell.com/tips/specializing-generics-with-type-aliases)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Specializes a generic type through a typealias to create a domain-specific name without wrapping storage. The alias improves call-site clarity, while the underlying generic behavior remains available for other contexts.
- [Showing view controllers, rather than pushing them | Swift by Sundell](https://www.swiftbysundell.com/tips/showing-view-controllers)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Presents a view controller modally instead of pushing it when the task is a temporary flow rather than hierarchical navigation. Choosing presentation semantics explicitly keeps dismissal ownership and state restoration predictable.
- [Setting up tests to avoid retain cycles with weak references | Swift by Sundell](https://www.swiftbysundell.com/tips/setting-up-tests-to-avoid-retain-cycles-with-weak-references)
  **Published:** `2021-10-30`
  **Topics:** Swift · Testing
  **NeKI brief:** Uses weak references in test setup to verify delegates and callbacks do not retain their owner. The test must retain the system under test strongly while allowing collaborators to deallocate naturally.
- [Assigning an expression to a variable with the same name | Swift by Sundell](https://www.swiftbysundell.com/tips/same-name-assignments)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses a temporary value or explicit self qualification when assigning a property from a same-named parameter. Making the receiver visible avoids shadowing mistakes and keeps initializer intent obvious during refactors.
- [Result’s convenience APIs | Swift by Sundell](https://www.swiftbysundell.com/tips/result-type-convenience-apis)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Adds convenience operations around Result to transform success values or recover failures without repeated switches. Keep error conversion explicit so a fluent chain does not erase the diagnostic information needed by callers.
- [Three ways to render a SwiftUI view in a playground | Swift by Sundell](https://www.swiftbysundell.com/tips/rendering-a-swiftui-view-in-a-playground)
  **Published:** `2021-10-30`
  **Topics:** Architecture · Swift · SwiftUI · Xcode
  **NeKI brief:** Renders a SwiftUI view in a playground to inspect a small component without launching a full app. It is useful for isolated experiments, while device-specific environment and lifecycle behavior still need app-level verification.
- [Referring to overloaded functions | Swift by Sundell](https://www.swiftbysundell.com/tips/referring-to-overloaded-functions)
  **Published:** `2021-10-30`
  **Topics:** Networking · Swift · Testing
  **NeKI brief:** Shows how explicit function types or labels select one overload when passing a method as a value. Clarifying the expected signature helps the compiler and prevents accidental capture of a similarly named variant.
- [Referring to enum cases with associated values as closures | Swift by Sundell](https://www.swiftbysundell.com/tips/referring-to-enum-cases-with-associated-values-as-closures)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses enum cases with associated values as closure-like constructors when their signature matches. This reduces adapter code for mapping operations, but inference can become opaque and merits a named closure when complex.
- [Referencing either external or internal parameter names when writing docs | Swift by Sundell](https://www.swiftbysundell.com/tips/referencing-either-external-or-internal-parameter-name-when-writing-docs)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Explains documenting Swift parameters with either external labels or internal names depending on the generated API context. Consistent terminology keeps DocC useful without leaking implementation naming that callers never see.
- [Refactoring SwiftUI views using functions | Swift by Sundell](https://www.swiftbysundell.com/tips/refactoring-swiftui-views-using-functions)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Extracts repeated SwiftUI view fragments into functions to reduce body complexity while retaining local data flow. Functions are a low-cost refactor, though independently stateful pieces may warrant dedicated subviews instead.
- [Refactoring enums which cases contain the same data | Swift by Sundell](https://www.swiftbysundell.com/tips/refactoring-enums-which-cases-contain-the-same-data)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Refactors enum cases that repeat associated data into shared payload types, reducing duplication while preserving exhaustive pattern matching. Keep the payload semantic so the enum still communicates meaningful state transitions.
- [Reducing the need for mocks | Swift by Sundell](https://www.swiftbysundell.com/tips/reducing-the-need-for-mocks)
  **Published:** `2021-10-30`
  **Topics:** Swift · Testing
  **NeKI brief:** Suggests designing boundaries around values and pure transformations so tests need fewer behavior-heavy mocks. Realistic fakes or injected data often expose integration bugs that interaction-count assertions would miss.
- [Reducing sequences | Swift by Sundell](https://www.swiftbysundell.com/tips/reducing-sequences)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses reduce when a sequence must accumulate into one value, from totals to composed output. The closure should expose the accumulator's invariant; otherwise a loop may communicate mutation and early exits more clearly.
- [Recursively calling closures as inline functions | Swift by Sundell](https://www.swiftbysundell.com/tips/recursively-calling-closures-as-inline-functions)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses a recursively invoked closure to keep a small algorithm local while still expressing repeated work. Add an explicit termination condition and consider a named function when recursion affects stack depth or readability.
- [Recursive enums with “fake” cases | Swift by Sundell](https://www.swiftbysundell.com/tips/recursive-enums-with-fake-cases)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Explains modeling recursive enum data while adding a non-recursive sentinel case for construction or termination. The sentinel simplifies algorithms, but callers must treat it as a real state and handle it exhaustively.
- [How the raw values of Int-based enums get incremented | Swift by Sundell](https://www.swiftbysundell.com/tips/raw-values-for-int-based-enums)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Explains automatic raw-value increments for consecutive Int enum cases and the maintenance risk when inserting cases. Persisted raw values therefore need migration thought before reordering or adding cases.
- [Quickly replacing singletons with functions | Swift by Sundell](https://www.swiftbysundell.com/tips/quickly-replacing-singletons-with-functions)
  **Published:** `2021-10-30`
  **Topics:** Architecture · Concurrency · Dependency Injection · Swift · Testing · Xcode
  **NeKI brief:** Replaces singleton lookups with functions that return dependencies, creating a lightweight seam for tests and future configuration. The approach improves call-site control without forcing a large container, but shared lifetime must be decided explicitly.
- [Automatic handling of property wrapper default values | Swift by Sundell](https://www.swiftbysundell.com/tips/property-wrapper-default-values)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Explains how property-wrapper default values can be handled automatically during initialization, reducing repetitive assignments. The convenience depends on wrapper initialization semantics, so explicit initialization remains preferable when defaults carry business meaning.
- [Picking between a for loop and forEach | Swift by Sundell](https://www.swiftbysundell.com/tips/picking-between-for-and-for-each)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Compares for-in and forEach control flow, highlighting that forEach cannot break or continue normally. Choose the loop form that communicates whether early exit and structured control are required.
- [Passing self to required Objective-C dependencies | Swift by Sundell](https://www.swiftbysundell.com/tips/passing-self-to-required-objective-c-dependencies)
  **Published:** `2021-10-30`
  **Topics:** Dependency Injection · Swift
  **NeKI brief:** Shows passing self to Objective-C APIs that require a delegate or callback dependency, while considering initialization timing. Ensure the object is fully initialized before registration to avoid observing partial state.
- [Passing operators as functions | Swift by Sundell](https://www.swiftbysundell.com/tips/passing-operators-as-functions)
  **Published:** `2021-10-30`
  **Topics:** Swift · Testing
  **NeKI brief:** Uses Swift operators as first-class functions when a transform already matches an operator signature. This can make collection pipelines concise, but a named closure is clearer when operand order is non-obvious.
- [Passing methods as SwiftUI view actions | Swift by Sundell](https://www.swiftbysundell.com/tips/passing-methods-as-swiftui-view-actions)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Passes existing methods directly as SwiftUI action closures, reducing wrapper code and keeping event behavior near its owner. Capture semantics still matter when the view outlives or recreates its model.
- [Passing key paths as functions | Swift by Sundell](https://www.swiftbysundell.com/tips/passing-key-paths-as-functions)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Shows passing key paths where functions are expected to project values from collections. Follow it when simplifying map/sort code while keeping the transformation's source property explicit and type-checked.
- [Parsing command line arguments using UserDefaults | Swift by Sundell](https://www.swiftbysundell.com/tips/parsing-command-line-arguments-using-userdefaults)
  **Published:** `2021-10-30`
  **Topics:** Persistence & Synchronisation · Swift
  **NeKI brief:** Uses UserDefaults' argument domain to parse launch-time flags for tests and development tools. This keeps configuration out of production persistence, but argument precedence should be documented when multiple domains overlap.
- [Overriding self with a weak reference | Swift by Sundell](https://www.swiftbysundell.com/tips/overriding-self-with-a-weak-reference)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Demonstrates weak self capture to prevent retain cycles in asynchronous callbacks. Weakness is not a universal fix: guard the lifetime deliberately so required work is not silently skipped after deallocation.
- [Organizing code using extensions | Swift by Sundell](https://www.swiftbysundell.com/tips/organizing-code-using-extensions)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses extensions to group a type's protocol conformance and related behavior into focused files. Organization helps navigation, but extensions should not conceal tightly coupled mutable state or oversized responsibilities.
- [Optional SwiftUI views | Swift by Sundell](https://www.swiftbysundell.com/tips/optional-swiftui-views)
  **Published:** `2021-10-30`
  **Topics:** Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Makes a SwiftUI child view optional with generic content and builder overloads, preserving a single container API. Generic inference and empty content behavior need explicit tests to avoid surprising layout changes.
- [Omitting the return keyword | Swift by Sundell](https://www.swiftbysundell.com/tips/omitting-the-return-keyword)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Omits return in single-expression closures and computed properties for concise transformations. The shorthand is readable for small expressions, but explicit return becomes preferable when branching or side effects grow.
- [Observing Combine publishers in SwiftUI views | Swift by Sundell](https://www.swiftbysundell.com/tips/observing-combine-publishers-in-swiftui-views)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI · UIKit
  **NeKI brief:** Connects Combine publishers to SwiftUI view state through lifecycle-aware observation. Store cancellables with the owning model and cancel on teardown so subscriptions do not duplicate after view recreation.
- [Nested generic types | Swift by Sundell](https://www.swiftbysundell.com/tips/nested-generic-types)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses nested generic types to keep helper data structures scoped to their enclosing domain. Nesting communicates ownership and reduces namespace noise, while overly deep nesting can make diagnostics harder to read.
- [Namespacing with nested types | Swift by Sundell](https://www.swiftbysundell.com/tips/namespacing-with-nested-types)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Uses an enclosing type as a namespace for related constants and helper values without allocating instances. This avoids global collisions, but nested names should remain discoverable and stable if used in persisted data.
- [Multiline string literals don’t require quotes to be escaped | Swift by Sundell](https://www.swiftbysundell.com/tips/multiline-string-literals)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses multiline string literals for readable fixtures and templates while preserving intentional whitespace. Normalize indentation and newline expectations when strings cross platform or serialization boundaries.
- [Multiline string literal tips and tricks | Swift by Sundell](https://www.swiftbysundell.com/tips/multiline-string-literal-tips-and-tricks)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Uses multiline literals with indentation and interpolation rules to build readable fixtures and templates. Normalize whitespace deliberately when strings are compared, serialized, or displayed across platforms.
- [Matching multiple enum cases with associated values | Swift by Sundell](https://www.swiftbysundell.com/tips/matching-multiple-enum-cases-with-associated-values)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Matches several enum cases with compatible associated values in one pattern, reducing duplicate branches. Keep shared handling truly identical; diverging cases should split so the state-specific behavior remains visible.
- [Manipulating points, sizes and frames using math operators | Swift by Sundell](https://www.swiftbysundell.com/tips/manipulating-points,-sizes-and-frames-using-math-operators)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Adds arithmetic operators for CGPoint, CGSize, and CGRect to make geometry calculations composable. Operator overloads improve layout formulas, but naming or comments may be needed when units differ.
- [Making weak or lazy properties readonly | Swift by Sundell](https://www.swiftbysundell.com/tips/making-weak-or-lazy-properties-readonly)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Makes weak or lazy properties read-only at the API surface while retaining controlled initialization internally. This protects ownership and mutation invariants, but the initialization path must remain explicit for tests and subclasses.
- [Making UIImage macOS compatible | Swift by Sundell](https://www.swiftbysundell.com/tips/making-uiimage-macos-compatible)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Wraps UIImage and NSImage differences behind a platform-neutral image abstraction for shared code. Conditional imports keep call sites consistent, while platform-specific rendering and color semantics still need tests.
- [Making types expressible by string interpolation | Swift by Sundell](https://www.swiftbysundell.com/tips/making-types-expressible-by-string-interpolation)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Conforms custom types to string interpolation so log and diagnostic output carries domain meaning automatically. Keep interpolation side-effect-free and avoid exposing sensitive fields through convenient descriptions.
- [Making properties overridable only in debug builds | Swift by Sundell](https://www.swiftbysundell.com/tips/making-properties-overridable-only-in-debug-builds)
  **Published:** `2021-10-30`
  **Topics:** Architecture · Dependency Injection · Swift
  **NeKI brief:** Uses conditional compilation to expose mutable hooks only in debug builds, enabling test control without shipping a production escape hatch. Ensure release and debug APIs remain behaviorally aligned.
- [Making async tests faster and more stable | Swift by Sundell](https://www.swiftbysundell.com/tips/making-async-tests-faster-and-more-stable)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Improves async test stability by controlling dependencies and waiting on meaningful signals rather than arbitrary delays. Deterministic clocks or injected schedulers reduce runtime while preserving the behavior under test.
- [Limiting collection mutations | Swift by Sundell](https://www.swiftbysundell.com/tips/limiting-collection-mutations)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Restricts collection mutation through a focused API so invariants cannot be bypassed by arbitrary writes. This improves model safety, but callers need deliberate operations for valid bulk updates.
- [Lightweight data hierarchies using tuples | Swift by Sundell](https://www.swiftbysundell.com/tips/lightweight-data-hierarchies-using-tuples)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI · Testing
  **NeKI brief:** Uses tuples for small local data hierarchies when a dedicated model would add ceremony. Tuple labels improve readability, but evolving or widely shared data deserves a named type.
- [Lazy property observers | Swift by Sundell](https://www.swiftbysundell.com/tips/lazy-property-observers)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Explains the interaction between lazy initialization and property observers, where initialization may not trigger the same callbacks as later mutation. Keep side effects outside assumptions about first access.
- [Internally mutable protocol-oriented APIs | Swift by Sundell](https://www.swiftbysundell.com/tips/internally-mutable-protocol-oriented-apis)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Designs protocol-oriented APIs that expose immutable views while allowing controlled internal mutation. The boundary protects invariants, but mutating operations still require clear ownership and synchronization semantics.
- [Inline wrapping of UIKit or AppKit views within SwiftUI | Swift by Sundell](https://www.swiftbysundell.com/tips/inline-wrapping-of-uikit-or-appkit-views-within-swiftui)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI · UIKit
  **NeKI brief:** Wraps a UIKit or AppKit view inline in SwiftUI through representable adapters, preserving native behavior during migration. Coordinators bridge delegates, while updates must avoid recreating imperative view state unnecessarily.
- [Inferred generic type constraints | Swift by Sundell](https://www.swiftbysundell.com/tips/inferred-generic-type-constraints)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Leverages inferred generic constraints to simplify declarations when surrounding context already determines types. Keep constraints explicit when inference would hide important relationships from API readers.
- [Improved memberwise initializers in Swift 5.1 | Swift by Sundell](https://www.swiftbysundell.com/tips/improved-memberwise-initializers-in-swift-5-1)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Explains Swift 5.1 memberwise initializer improvements and how defaults affect synthesized construction. Generated initializers are convenient, but public module APIs often need explicit stable initializers.
- [Improved compiler errors for auto-synthesized conformances in Xcode 11 | Swift by Sundell](https://www.swiftbysundell.com/tips/improved-compiler-errors-for-auto-synthesized-conformances-in-xcode-11)
  **Published:** `2021-10-30`
  **Topics:** Swift · Xcode
  **NeKI brief:** Shows clearer compiler diagnostics for failed synthesized conformances, helping locate the property blocking Codable or Equatable generation. Read the failing member first before writing unnecessary manual implementations.
- [Importing interactive UIKit views into SwiftUI | Swift by Sundell](https://www.swiftbysundell.com/tips/importing-interactive-uikit-views-into-swiftui)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI · UIKit
  **NeKI brief:** Imports interactive UIKit views into SwiftUI while retaining gestures and delegate-driven behavior. Adapter state must synchronize in both directions, especially when SwiftUI recreates the surrounding view.
- [Implicit capturing of self in Swift 5.3 | Swift by Sundell](https://www.swiftbysundell.com/tips/implicit-capturing-of-self)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Explains implicit self capture in closures and its consequences for object lifetime. Convenience should not conceal retain cycles; choose capture lists based on whether the work requires the owner to remain alive.
- [Handling view controllers that have custom initializers | Swift by Sundell](https://www.swiftbysundell.com/tips/handling-view-controllers-that-have-custom-initializers)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Handles UIViewController subclasses with custom initializer dependencies while remaining compatible with UIKit construction paths. Required initialization and storyboard decoding must establish the same invariants.
- [Handling keyUp and keyDown events on iOS 13.4 and later | Swift by Sundell](https://www.swiftbysundell.com/tips/handling-keyup-and-keydown-events)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Handles keyboard key-down and key-up events separately for responsive desktop or hardware-keyboard controls. Event timing and focus ownership determine correctness, so shortcuts should coexist with system commands.
- [Grouping throwing expressions using tuples | Swift by Sundell](https://www.swiftbysundell.com/tips/grouping-throwing-expressions-using-tuples)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Groups throwing expressions with tuples to keep related setup linear while propagating the first error. This can reduce boilerplate, but separate bindings may be clearer when failures need distinct recovery.
- [Generic type aliases | Swift by Sundell](https://www.swiftbysundell.com/tips/generic-type-aliases)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses generic type aliases to give recurring specialized types concise domain names. Aliases improve readability without runtime cost, but should not obscure the generic parameters callers need to understand.
- [Generic algorithms | Swift by Sundell](https://www.swiftbysundell.com/tips/generic-algorithms)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Builds algorithms against generic constraints rather than concrete collections to maximize reuse. Constrain only the capabilities needed, while preserving complexity guarantees and clear failure behavior.
- [Gathering test coverage in Xcode | Swift by Sundell](https://www.swiftbysundell.com/tips/gathering-test-coverage-in-xcode)
  **Published:** `2021-10-30`
  **Topics:** Swift · Testing · Xcode
  **NeKI brief:** Explains Xcode’s coverage reports and command-line collection, including selecting targets and interpreting line and function percentages, to connect coverage numbers with concrete untested branches rather than treating them as a quality score.
- [Functional networking | Swift by Sundell](https://www.swiftbysundell.com/tips/functional-networking)
  **Published:** `2021-10-30`
  **Topics:** Networking · Swift
  **NeKI brief:** Separates networking request construction and response decoding into composable functions, making each stage testable. The approach clarifies error translation, while retries and scheduling remain policy decisions above the functions.
- [Faster and more stable UI tests | Swift by Sundell](https://www.swiftbysundell.com/tips/faster-and-more-stable-ui-tests)
  **Published:** `2021-10-30`
  **Topics:** Swift · Testing · Xcode
  **NeKI brief:** Improves UI tests by waiting for meaningful UI state instead of fixed delays and by limiting shared setup. Stable accessibility identifiers and deterministic launch arguments reduce flakiness more than retries.
- [Extracting subsequences | Swift by Sundell](https://www.swiftbysundell.com/tips/extracting-subsequences)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses collection subsequences for slices without immediately copying the original storage. Slices are efficient for temporary work, but their retained backing collection matters when storing results long term.
- [Extending optionals | Swift by Sundell](https://www.swiftbysundell.com/tips/extending-optionals)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Extends Optional with domain helpers to centralize repeated nil-handling behavior. Helpers should preserve standard optional semantics and avoid turning absence into hidden side effects.
- [Expressively comparing a value with a list of candidates | Swift by Sundell](https://www.swiftbysundell.com/tips/expressively-comparing-a-value-with-a-list-of-candidates)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses pattern matching or collection membership to compare a value against several valid candidates without chained boolean expressions. The approach reads well when candidates form one domain set, not unrelated exceptions.
- [Explicit type annotations | Swift by Sundell](https://www.swiftbysundell.com/tips/explicit-type-annotations)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Adds type annotations when inference becomes ambiguous or hides the desired API contract. Annotations aid diagnostics and readers, but unnecessary declarations can obscure simple transformations.
- [Equatable and Hashable structures | Swift by Sundell](https://www.swiftbysundell.com/tips/equatable-and-hashable-structures)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Explains implementing Equatable and Hashable together so sets and dictionaries preserve their contract. Equal values must produce equal hashes; mutable identity fields should not participate after insertion.
- [Enums with custom raw types | Swift by Sundell](https://www.swiftbysundell.com/tips/enums-with-custom-raw-types)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses custom RawRepresentable types for enums when String or Int raw values are too weak. The wrapper can enforce parsing invariants, while persistence compatibility requires a stable representation.
- [Enabling static dependency injection | Swift by Sundell](https://www.swiftbysundell.com/tips/enabling-static-dependency-injection)
  **Published:** `2021-10-30`
  **Topics:** Architecture · Dependency Injection · Swift
  **NeKI brief:** Creates injection seams around static dependencies so tests can replace global behavior without a full container. The seam should remain explicit, preventing hidden production overrides from leaking between tests.
- [Dropping suffixes from method names to support multiple arguments | Swift by Sundell](https://www.swiftbysundell.com/tips/dropping-suffixes-from-method-names-to-support-multiple-arguments)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Refines method naming so Swift argument labels carry meaning without redundant suffixes. The call site should read naturally with multiple arguments, while preserving clarity over clever abbreviation.
- [Automatic conversions between Double and CGFloat values in Swift 5.5 | Swift by Sundell](https://www.swiftbysundell.com/tips/double-cgfloat-auto-conversions)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Explains automatic Double and CGFloat conversions in Swift 5.5. Use it when graphics calculations cross numeric types and older explicit conversion boilerplate can be simplified.
- [Dependency injection using functions | Swift by Sundell](https://www.swiftbysundell.com/tips/dependency-injection-using-functions)
  **Published:** `2021-10-30`
  **Topics:** Architecture · Dependency Injection · Swift
  **NeKI brief:** Uses functions as lightweight dependencies, allowing tests to pass deterministic behavior directly. This avoids protocol boilerplate for simple seams, but complex lifecycle or grouping needs may justify a structured dependency type.
- [Defining static URLs using string literals | Swift by Sundell](https://www.swiftbysundell.com/tips/defining-static-urls-using-string-literals)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Defines static URLs through typed string literals to validate constants at construction rather than scattering force unwraps. Dynamic components still need encoding and failure handling at their input boundary.
- [Defining custom option sets | Swift by Sundell](https://www.swiftbysundell.com/tips/defining-custom-option-sets)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Uses OptionSet for combinable flags while retaining type safety and expressive membership checks. Reserve flags for independent boolean capabilities; mutually exclusive state is clearer as an enum.
- [Defaults for associated types | Swift by Sundell](https://www.swiftbysundell.com/tips/defaults-for-associated-types)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Provides default associated types in protocols to simplify common conformances without removing customization. Defaults should reflect the typical case, while constraints keep alternate implementations type-safe.
- [Default enum associated values | Swift by Sundell](https://www.swiftbysundell.com/tips/default-enum-associated-values)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses default associated values to make enum case construction concise when one payload has a conventional value. Defaults reduce call-site noise, but avoid hiding values that materially change behavior.
- [Annotating properties with default decoding values | Swift by Sundell](https://www.swiftbysundell.com/tips/default-decoding-values)
  **Published:** `2021-10-30`
  **Topics:** Swift · Testing
  **NeKI brief:** Provides default values during decoding so missing fields can map to a valid model state. Defaults must represent safe compatibility behavior; silently inventing required data can hide a server contract break.
- [Custom UIView backing layers | Swift by Sundell](https://www.swiftbysundell.com/tips/custom-uiview-backing-layers)
  **Published:** `2021-10-30`
  **Topics:** Swift · UIKit
  **NeKI brief:** Overrides UIView's backing layer class for specialized drawing or effects without adding sublayers manually. The layer type becomes part of the view contract, so casts and rendering assumptions must stay localized.
- [Creating extensions with static factory methods | Swift by Sundell](https://www.swiftbysundell.com/tips/creating-extensions-with-static-factory-methods)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Uses static factory methods in extensions to create readable, discoverable construction APIs. Factories can validate or configure defaults, but should not obscure heavyweight work behind an innocuous-looking property.
- [Creating custom SwiftUI container views | Swift by Sundell](https://www.swiftbysundell.com/tips/creating-custom-swiftui-container-views)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Creates SwiftUI container views that accept generic child content and own layout policy. The abstraction improves reuse, but state and environment responsibilities should remain obvious at the call site.
- [Creating closure-based UI controls using UIAction | Swift by Sundell](https://www.swiftbysundell.com/tips/creating-closure-based-ui-controls-with-uiaction)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI · UIKit
  **NeKI brief:** Uses UIAction to attach closure-based handlers to UIKit controls, replacing target-selector plumbing for simple interactions. Capture ownership carefully and keep reusable controls from embedding screen-specific behavior.
- [Creating a dedicated identifier type | Swift by Sundell](https://www.swiftbysundell.com/tips/creating-a-dedicated-identifier-type)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Defines a dedicated identifier type instead of passing bare strings or integers between domains. Stronger typing prevents accidental mixing, while Codable and storage representation must remain stable.
- [Converting Swift errors to NSError | Swift by Sundell](https://www.swiftbysundell.com/tips/converting-swift-errors-to-nserror)
  **Published:** `2021-10-30`
  **Topics:** Swift · Testing
  **NeKI brief:** Bridges Swift Error values to NSError when interoperating with Objective-C APIs. Preserve domain and code information so legacy callers can inspect failures without losing Swift-specific context.
- [Converting between String and Data without optionals | Swift by Sundell](https://www.swiftbysundell.com/tips/converting-between-string-and-data-without-optionals)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Converts between String and Data with encoding choices that make failure explicit instead of force-unwrapping. UTF-8 is common, but external data needs validation because decoding can fail.
- [Constraining protocols to classes to ensure mutability | Swift by Sundell](https://www.swiftbysundell.com/tips/constraining-protocols-to-classes-to-ensure-mutability)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Constrains a protocol to classes when reference semantics or mutation through a let binding are required. This is an architectural choice; value-oriented protocols should not inherit class-only limits accidentally.
- [Publishing constant values using Combine | Swift by Sundell](https://www.swiftbysundell.com/tips/constant-combine-publishers)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses constant Combine publishers to model fixed success or failure streams in tests and simple pipelines. They simplify deterministic setup, but production publishers may need cancellation and scheduling behavior the constants omit.
- [Configurable types | Swift by Sundell](https://www.swiftbysundell.com/tips/configurable-types)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Designs configurable types with a closure or builder-style setup path, keeping construction readable without many initializer overloads. Defaults should stay safe, and configuration should not create partially initialized state.
- [Conditional conformances | Swift by Sundell](https://www.swiftbysundell.com/tips/conditional-conformances)
  **Published:** `2021-10-30`
  **Topics:** Networking · Swift · SwiftUI
  **NeKI brief:** Uses conditional conformances so generic containers adopt protocols only when their elements qualify. This preserves type safety and avoids runtime checks, while constraints should remain simple enough for compiler diagnostics.
- [Computed properties vs methods | Swift by Sundell](https://www.swiftbysundell.com/tips/computed-properties-vs-methods)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Distinguishes computed properties from methods by cost, side effects, and noun-versus-action semantics. Properties should feel cheap and stable; methods better signal work, parameters, or observable behavior.
- [Combining values with functions | Swift by Sundell](https://www.swiftbysundell.com/tips/combining-values-with-functions)
  **Published:** `2021-10-30`
  **Topics:** Networking · Swift
  **NeKI brief:** Uses function composition to combine value transformations without temporary variables. Composition clarifies pipelines when types line up, but named intermediate steps are preferable when diagnosing failures or branching.
- [Combining lazily evaluated sequences with the builder pattern | Swift by Sundell](https://www.swiftbysundell.com/tips/combining-lazily-evaluated-sequences-with-the-builder-pattern)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Combines lazy sequences with a builder pattern to defer work until a consumer requests values. This can reduce allocation, but deferred errors and retained inputs must be understood by callers.
- [Combining dynamic member lookup with key paths | Swift by Sundell](https://www.swiftbysundell.com/tips/combining-dynamic-member-lookup-with-key-paths)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Combines dynamic member lookup and key paths to forward typed property access through a wrapper. The syntax is concise, but constrain the exposed surface so forwarding does not obscure ownership or mutation.
- [Combining a sequence of functions | Swift by Sundell](https://www.swiftbysundell.com/tips/combining-a-sequence-of-functions)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Composes a sequence of compatible functions into a single transformation pipeline. This is useful for configurable processing steps, while error handling and type mismatches need a clear composition boundary.
- [Child view controller auto-resizing | Swift by Sundell](https://www.swiftbysundell.com/tips/child-view-controller-auto-resizing)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Configures child view-controller containment and resizing so embedded content follows its parent bounds. Correct constraints and lifecycle calls matter more than manual frame adjustment during rotation.
- [Checking whether an element was inserted into a set | Swift by Sundell](https://www.swiftbysundell.com/tips/checking-if-an-element-was-inserted-into-a-set)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses Set.insert's inserted result to tell whether a value was newly added without performing a separate lookup. This keeps uniqueness checks atomic at the collection API level.
- [Character category properties | Swift by Sundell](https://www.swiftbysundell.com/tips/character-category-properties)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses Unicode character category properties for text classification instead of ASCII ranges. This supports international input, while grapheme clusters and locale-specific rules may still require higher-level handling.
- [Chaining optionals with map and flatMap | Swift by Sundell](https://www.swiftbysundell.com/tips/chaining-optionals-with-map-and-flatmap)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Chains optional transformations with map and flatMap to avoid nested unwrapping. Use map for non-optional results and flatMap when the transform may itself fail, preserving absence semantics.
- [Chained implicit member expressions in Swift 5.4 | Swift by Sundell](https://www.swiftbysundell.com/tips/chained-implicit-member-expressions)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses chained implicit member expressions for concise construction when the expected type is clear. The shorthand should not hide an ambiguous type or make code reviewers reconstruct inference unnecessarily.
- [Capturing multiple values in mocks | Swift by Sundell](https://www.swiftbysundell.com/tips/capturing-multiple-values-in-mocks)
  **Published:** `2021-10-30`
  **Topics:** Swift · Testing
  **NeKI brief:** Captures multiple mock invocations and their arguments so tests can assert ordering and payloads without brittle one-off flags. Keep the mock focused on observable behavior rather than duplicating implementation logic.
- [Calling instance methods as static functions | Swift by Sundell](https://www.swiftbysundell.com/tips/calling-instance-methods-as-static-functions)
  **Published:** `2021-10-30`
  **Topics:** Architecture · Dependency Injection · Swift
  **NeKI brief:** Treats an instance method reference as a function when its receiver is supplied separately. This enables concise mapping, but method references should remain clear about which object supplies state.
- [Calling initializers with dot syntax and passing them as closures | Swift by Sundell](https://www.swiftbysundell.com/tips/calling-initializers-with-dot-syntax-and-passing-them-as-closures)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses initializer references and dot syntax where context determines the constructed type. This can streamline factories, while explicit constructors are clearer when several types share similar initializers.
- [Calling functions as closures with a tuple as parameters | Swift by Sundell](https://www.swiftbysundell.com/tips/calling-functions-as-closures-with-a-tuple-as-parameters)
  **Published:** `2021-10-30`
  **Topics:** Networking · Swift
  **NeKI brief:** Adapts function calls to tuple-shaped parameters for functional pipelines. Tuple adapters can reduce glue code, but named values often communicate intent better than positional elements.
- [Building an Observable type for SwiftUI views | Swift by Sundell](https://www.swiftbysundell.com/tips/building-an-observable-type-for-swiftui-views)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI · UIKit
  **NeKI brief:** Builds an observable model for SwiftUI so state changes drive view updates through published properties. Define ownership and main-thread delivery explicitly to avoid duplicate subscriptions or stale rendering.
- [Avoiding mocking UserDefaults | Swift by Sundell](https://www.swiftbysundell.com/tips/avoiding-mocking-userdefaults)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Persistence & Synchronisation · Swift · Testing
  **NeKI brief:** Avoids mocking UserDefaults directly by injecting a protocol, suite, or values abstraction. This produces deterministic persistence tests while keeping production defaults behavior at one boundary.
- [Avoiding Massive View Controllers | Swift by Sundell](https://www.swiftbysundell.com/tips/avoiding-massive-view-controllers)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Breaks massive view controllers into focused collaborators for presentation, data loading, and navigation. Extraction should follow stable responsibilities, not merely move methods into arbitrary extension files.
- [Avoiding manual Codable implementations | Swift by Sundell](https://www.swiftbysundell.com/tips/avoiding-manual-codable-implementations)
  **Published:** `2021-10-30`
  **Topics:** Swift · Testing · Xcode
  **NeKI brief:** Relies on Codable synthesis where the model matches the payload, avoiding hand-written encode/decode code. Custom implementations remain appropriate for schema adaptation, defaults, and backward compatibility.
- [Avoiding default cases in switch statements | Swift by Sundell](https://www.swiftbysundell.com/tips/avoiding-default-cases-in-switch-statements)
  **Published:** `2021-10-30`
  **Topics:** Swift · Testing
  **NeKI brief:** Avoids default switch cases when enumerating a known enum so compiler exhaustiveness catches new cases. A default remains appropriate for open domains, but it can hide required behavior after evolution.
- [Auto-Equatable enums with associated values | Swift by Sundell](https://www.swiftbysundell.com/tips/auto-equatable-enums-with-associated-values)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses synthesized Equatable for enums with associated values whose payloads are equatable. This avoids manual comparison branches, while equality still needs to represent the domain rather than implementation artifacts.
- [Attaching property wrappers to function arguments | Swift by Sundell](https://www.swiftbysundell.com/tips/attaching-property-wrappers-to-function-arguments)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Attaches property wrappers to function parameters to transform or validate inputs at the declaration boundary. The feature reduces repeated glue, but wrapper behavior should stay obvious to API callers.
- [Assigning to self in struct initializers | Swift by Sundell](https://www.swiftbysundell.com/tips/assigning-to-self-in-struct-initializers)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Assigns self in a struct initializer after building a valid value, useful for delegating construction paths. The technique must preserve initialization rules and avoid accessing members before full initialization.
- [Assigning optional tuple members to variables | Swift by Sundell](https://www.swiftbysundell.com/tips/assigning-optional-tuple-members-to-variables)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Destructures optional tuple members into local bindings while retaining explicit absence handling. It can simplify compact transformations, but named intermediate values improve readability for complex optional logic.
- [Annotating properties with result builder attributes | Swift by Sundell](https://www.swiftbysundell.com/tips/annotating-properties-with-result-builder-attributes)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses result-builder attributes on properties to collect declarative content beyond SwiftUI body. Builders improve DSL ergonomics, while generated control flow and type inference need constrained, well-documented APIs.
- [Adding the current locale to cache keys | Swift by Sundell](https://www.swiftbysundell.com/tips/adding-the-current-locale-to-cache-keys)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Includes locale in cache keys when formatted or localized output depends on user language and region. This prevents serving stale language content, while cache invalidation must also consider other presentation settings.
- [Adding SwiftUI’s ViewBuilder attribute to functions | Swift by Sundell](https://www.swiftbysundell.com/tips/adding-swiftui-viewbuilder-to-functions)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Applies ViewBuilder to helper functions so callers can pass conditional or multiple SwiftUI views declaratively. Keep helpers focused; excessive builders can make generic diagnostics and state ownership unclear.
- [Adding support for Apple Pencil double-taps | Swift by Sundell](https://www.swiftbysundell.com/tips/adding-support-for-apple-pencil-double-taps)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Handles Apple Pencil double-tap interactions as a configurable input shortcut rather than assuming a fixed tool change. Respect the user's Pencil preferences and offer equivalent touch-accessible controls.
- [Accessing the clipboard from a Swift script | Swift by Sundell](https://www.swiftbysundell.com/tips/accessing-the-clipboard-from-a-swift-script)
  **Published:** `2021-10-30`
  **Topics:** Persistence & Synchronisation · Swift
  **NeKI brief:** Accesses the clipboard from a Swift script for small developer workflows and automation. Clipboard data is external input; validate expected formats and avoid exposing sensitive values in logs.
- [A first look at SwiftUI’s new StateObject property wrapper | Swift by Sundell](https://www.swiftbysundell.com/tips/a-first-look-at-swiftui-stateobject)
  **Published:** `2021-10-30`
  **Topics:** Observation & State Management · Swift · SwiftUI · UIKit
  **NeKI brief:** Introduces StateObject for owning an observable reference model across SwiftUI body recomputation. Ownership differs from ObservedObject; instantiate once at the appropriate view boundary to avoid resetting state.
- [Q&A: When can Swift’s return keyword be omitted? | Swift by Sundell](https://www.swiftbysundell.com/questions/when-can-the-return-keyword-be-omitted)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Clarifies when Swift permits omitting return in single-expression functions, closures, and computed properties. Use the shorthand where inference is obvious; explicit return is clearer once control flow grows.
- [Q&A: How to sync the width or height of two SwiftUI views? | Swift by Sundell](https://www.swiftbysundell.com/questions/syncing-the-width-or-height-of-two-swiftui-views)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Explains synchronizing dimensions between SwiftUI siblings through measurement and preference flow. Keep geometry feedback one-way and scoped to avoid layout loops or stale size assumptions.
- [Q&A: How can a SwiftUI Text with mixed styling be created? | Swift by Sundell](https://www.swiftbysundell.com/questions/swiftui-text-mixed-styles)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI · UIKit
  **NeKI brief:** Shows composing mixed Text styles in SwiftUI while preserving one accessible textual sentence. Prefer semantic text composition over separate visual fragments that disrupt localization or VoiceOver reading order.
- [Q&A: How to pick between using a struct or a class? | Swift by Sundell](https://www.swiftbysundell.com/questions/struct-vs-class)
  **Published:** `2021-10-30`
  **Topics:** Architecture · Swift
  **NeKI brief:** Compares structs and classes through value semantics, identity, inheritance, and ownership. Choose based on the data model's mutation-sharing needs rather than a blanket preference.
- [Q&A: Why can’t certain protocols, like Equatable and Hashable, be referenced directly? | Swift by Sundell](https://www.swiftbysundell.com/questions/referencing-generic-protocols)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Addresses referencing protocols with associated types or generics, where existential use has limits. Opaque types, type erasure, or generic functions each preserve different amounts of type information.
- [Q&A: Is using [weak self] always required when working with closures? | Swift by Sundell](https://www.swiftbysundell.com/questions/is-weak-self-always-required)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Explains that weak self capture depends on ownership and callback lifetime rather than a universal closure rule. Capture strongly when work must keep the owner alive; otherwise break potential cycles deliberately.
- [Q&A: How to create an array with mixed types in Swift? | Swift by Sundell](https://www.swiftbysundell.com/questions/array-with-mixed-types)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Discusses mixed-type arrays and the cost of erasing type information into Any. Prefer enums, protocols, or dedicated wrappers when the elements represent a finite domain with real behavior.
- [Value and Reference Types | Swift by Sundell](https://www.swiftbysundell.com/basics/value-and-reference-types)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Compares value and reference semantics as the foundation for state ownership and copying behavior in Swift. Choose based on mutation sharing requirements, not merely class-versus-struct convention.
- [Unit Testing | Swift by Sundell](https://www.swiftbysundell.com/basics/unit-testing)
  **Published:** `2021-10-30`
  **Topics:** Swift · Testing · Xcode
  **NeKI brief:** Introduces unit testing around deterministic behavior, isolated setup, and clear assertions. A useful test observes outcomes rather than duplicating implementation details through mocks and internal calls.
- [Type inference | Swift by Sundell](https://www.swiftbysundell.com/basics/type-inference)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Explains Swift type inference and when contextual types make declarations concise. Add annotations where generic diagnostics or public API clarity outweigh the benefit of omitted types.
- [Time Complexity | Swift by Sundell](https://www.swiftbysundell.com/basics/time-complexity)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Introduces time-complexity reasoning for common operations so performance choices are made from algorithmic cost rather than intuition. Big-O guides scaling, while constant factors and measured workloads still matter.
- [SwiftUI | Swift by Sundell](https://www.swiftbysundell.com/basics/swiftui)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI · UIKit
  **NeKI brief:** Provides a SwiftUI foundation centered on declarative views, state, and identity. The key workflow is to model changing data clearly, then let rendering derive from that state.
- [Strings | Swift by Sundell](https://www.swiftbysundell.com/basics/strings)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Covers Swift String behavior as Unicode-correct text rather than integer-indexed bytes. Use String.Index and character-aware operations when processing user-visible text.
- [The Result Type | Swift by Sundell](https://www.swiftbysundell.com/basics/result)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Introduces Result for representing success or failure as a value that can be transformed and propagated. Use it at asynchronous or callback boundaries, while throws may remain clearer for linear control flow.
- [Protocols | Swift by Sundell](https://www.swiftbysundell.com/basics/protocols)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Explains protocols as behavior contracts that enable substitution and generic constraints. Keep protocol requirements focused on caller needs so conformers are not forced to expose unrelated implementation details.
- [Properties | Swift by Sundell](https://www.swiftbysundell.com/basics/properties)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Covers stored, computed, lazy, and observed properties as different state-management tools. Match the property kind to cost and ownership, avoiding observers for complex lifecycle orchestration.
- [Optionals | Swift by Sundell](https://www.swiftbysundell.com/basics/optionals)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Explains optionals as explicit absence and the tools for binding, mapping, and providing defaults. Keep nil handling at boundaries so inner domain logic can operate on validated values.
- [Networking | Swift by Sundell](https://www.swiftbysundell.com/basics/networking)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Networking · Swift · Testing
  **NeKI brief:** Introduces networking as request construction, asynchronous transport, decoding, and error handling. Separate these stages to make retries, caching, and tests depend on clear policies.
- [Memory Management | Swift by Sundell](https://www.swiftbysundell.com/basics/memory-management)
  **Published:** `2021-10-30`
  **Topics:** Swift · Testing
  **NeKI brief:** Covers ARC ownership, strong references, and cycles in Swift object graphs. Use weak or unowned references based on lifetime guarantees, then verify deallocation through targeted tests or memory tools.
- [Map, FlatMap and CompactMap | Swift by Sundell](https://www.swiftbysundell.com/basics/map-flatmap-and-compactmap)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Contrasts map, flatMap, and compactMap through their transformation and optional-flattening behavior. Use it when choosing collection operations by element shape and failure semantics rather than by superficial syntax similarity.
- [Layout Anchors | Swift by Sundell](https://www.swiftbysundell.com/basics/layout-anchors)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Introduces layout anchors as typed UIKit constraints for positioning and sizing views. Anchor APIs improve compiler checking, while content priorities and safe-area relationships remain design decisions.
- [Grand Central Dispatch | Swift by Sundell](https://www.swiftbysundell.com/basics/grand-central-dispatch)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Explains GCD queues and asynchronous scheduling for legacy or low-level concurrency work. Queue selection controls thread safety, while modern async/await may express structured task relationships more clearly.
- [Generics | Swift by Sundell](https://www.swiftbysundell.com/basics/generics)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Introduces generic types and functions for reuse while preserving static type information. Constrain generic parameters by actual requirements so APIs stay flexible without becoming opaque.
- [Error Handling | Swift by Sundell](https://www.swiftbysundell.com/basics/error-handling)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Covers Swift throws, do-catch, and Result-style failure propagation. Catch errors at the layer with recovery context, avoiding blanket swallowing that makes operational failures invisible.
- [Enums | Swift by Sundell](https://www.swiftbysundell.com/basics/enums)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Explains enums as finite state models with associated values and exhaustive switching. Model invalid combinations out of existence rather than storing several loosely related optionals.
- [Combine | Swift by Sundell](https://www.swiftbysundell.com/basics/combine)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Provides a focused Combine reference covering publishers, subscribers, operators, and cancellation. Use it to route legacy reactive code by concept before deciding whether a pipeline should migrate to async sequences.
- [Codable | Swift by Sundell](https://www.swiftbysundell.com/basics/codable)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Introduces Codable synthesis for translating models to and from external data. Synthesis is effective for aligned schemas, while migrations, defaults, and validation require explicit decoding policy.
- [Closures | Swift by Sundell](https://www.swiftbysundell.com/basics/closures)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Covers closures as values that capture context for callbacks and transformations. Capture ownership and execution context deliberately, especially when closures are stored or invoked asynchronously.
- [Child View Controllers | Swift by Sundell](https://www.swiftbysundell.com/basics/child-view-controllers)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Explains UIKit child view-controller containment, including add, embed, and lifecycle forwarding. Correct containment preserves appearance callbacks and rotation behavior that simply adding a child view would miss.
- [Availability checks | Swift by Sundell](https://www.swiftbysundell.com/basics/availability)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Introduces availability annotations and conditional APIs for supporting multiple OS versions. Let compiler checks enforce deployment boundaries, while runtime feature policy stays centralized rather than scattered.
- [Animations | Swift by Sundell](https://www.swiftbysundell.com/basics/animations)
  **Published:** `2021-10-30`
  **Topics:** Performance · Swift · SwiftUI
  **NeKI brief:** Covers animation as state transition over time, including completion and interruption concerns. Keep model state correct independently of visual animation so user interaction cannot leave UI and data out of sync.
- [Access Control | Swift by Sundell](https://www.swiftbysundell.com/basics/access-control)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Explains Swift access levels as module and implementation boundaries. Start with the narrowest visibility that supports callers, then widen intentionally when a stable public contract is needed.
- [Writing unit tests in Swift playgrounds | Swift by Sundell](https://www.swiftbysundell.com/articles/writing-unit-tests-in-a-swift-playground)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Networking · Swift · Testing
  **NeKI brief:** Uses a Swift playground to experiment with lightweight unit tests and isolated behavior. It supports fast learning, but package or app tests remain necessary for build settings and integration coverage.
- [Writing small utility functions in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/writing-small-utility-functions-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Builds small utility functions around one clear transformation or decision, improving testability and reuse. Avoid utility dumping grounds; a helper earns its place when its domain contract is stable.
- [Writing self-documenting Swift code | Swift by Sundell](https://www.swiftbysundell.com/articles/writing-self-documenting-swift-code)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Focuses self-documenting Swift code on meaningful names, type structure, and small units rather than explanatory comments. Comments remain valuable for non-obvious rationale, constraints, and external decisions.
- [Writing reusable Swift extensions | Swift by Sundell](https://www.swiftbysundell.com/articles/writing-reusable-swift-extensions)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses extensions to add reusable behavior where the receiver and constraints make applicability precise. Narrow extensions prevent global API pollution and keep helpers discoverable near their semantic type.
- [Writing end-to-end JSON mapping tests in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/writing-end-to-end-json-mapping-tests-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Networking · Swift · Testing
  **NeKI brief:** Tests JSON mapping end-to-end from fixture data through decoding to domain assertions. These tests catch schema drift, while focused unit tests still help isolate individual decoding failures.
- [Writing backward compatible Swift code | Swift by Sundell](https://www.swiftbysundell.com/articles/writing-backward-compatible-swift-code)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses availability checks and compatibility abstractions to support older platform versions without duplicating entire code paths. Keep wrappers temporary and deprecate them when the minimum deployment target advances.
- [Wrapping sequences in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/wrapping-sequences-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Wraps sequences in focused types to add domain behavior without eagerly materializing collections. Preserve sequence laziness where useful, while document whether repeated iteration is supported.
- [Working with files and folders in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/working-with-files-and-folders-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses Foundation file APIs to create, inspect, and organize files and directories in Swift. File operations can fail for permissions or missing paths, so errors and URL-based paths need explicit handling.
- [What makes code “Swifty”? | Swift by Sundell](https://www.swiftbysundell.com/articles/what-makes-code-swifty)
  **Published:** `2021-10-30`
  **Topics:** Performance · Swift
  **NeKI brief:** Discusses Swift style through type safety, expressive APIs, and value semantics rather than superficial syntax. Apply the ideas to improve clarity, while consistency with a codebase's established conventions still matters.
- [Validating email addresses using RawRepresentable and NSDataDetector | Swift by Sundell](https://www.swiftbysundell.com/articles/validating-email-addresses)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Validates email addresses using a practical boundary rather than attempting to fully parse every theoretical address form. Client checks improve feedback, but authoritative validation requires delivery or server-side confirmation.
- [Utilizing value semantics in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/utilizing-value-semantics-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Uses value semantics to make state changes local and predictable, reducing accidental shared mutation. Copy-on-write types can remain efficient, but large values and identity-dependent domains need conscious modeling.
- [Using unit tests to identify and avoid memory leaks in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/using-unit-tests-to-identify-avoid-memory-leaks-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift · Testing
  **NeKI brief:** Uses weak references and lifecycle assertions in unit tests to catch retained objects after work completes. Tests need controlled ownership; a passing deallocation check does not replace runtime memory-graph inspection.
- [Using tuples as lightweight types in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/using-tuples-as-lightweight-types-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses tuples for small local groupings without introducing a dedicated model. Tuple labels help nearby code, but cross-module or evolving data should graduate to a named type.
- [Using tokens to handle async Swift code | Swift by Sundell](https://www.swiftbysundell.com/articles/using-tokens-to-handle-async-swift-code)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Networking · Swift · Testing
  **NeKI brief:** Uses tokens to associate asynchronous callbacks with the current request and ignore stale results. Tokens prevent out-of-order UI updates, while cancellation should still stop unnecessary work where possible.
- [Using the factory pattern to avoid shared state in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/using-the-factory-pattern-to-avoid-shared-state-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Uses factories to create dependencies on demand rather than storing mutable shared instances globally. This improves isolation and tests, but factory ownership must still define lifetimes and caching policy.
- [Using the builder pattern in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/using-the-builder-pattern-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift · Testing
  **NeKI brief:** Uses a builder to assemble complex values step by step while separating configuration from final construction. Builders help when optional setup grows, but simple values remain clearer with direct initializers.
- [Using static protocol APIs to create conforming instances | Swift by Sundell](https://www.swiftbysundell.com/articles/using-static-protocol-apis-to-create-conforming-instances)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Uses static protocol requirements as factories so callers can construct conforming values without knowing concrete types. This supports substitution, while factory outputs need clear ownership and configuration inputs.
- [Using SpriteKit to create animations in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/using-spritekit-to-create-animations-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses SpriteKit scenes and actions for animation-heavy content where a dedicated rendering loop is useful. SpriteKit adds framework lifecycle concerns, so choose it only when UIKit or SwiftUI animation is insufficient.
- [Using multiple computed properties to form a SwiftUI view’s body | Swift by Sundell](https://www.swiftbysundell.com/articles/using-multiple-computed-properties-to-form-a-swiftui-view-body)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Splits a complex SwiftUI body into computed view properties to improve readability without changing state ownership. Extracted pieces should remain pure descriptions; stateful parts may be clearer as dedicated subviews.
- [Using lazy properties in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/using-lazy-properties-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Performance · Swift
  **NeKI brief:** Uses lazy properties to defer expensive or self-dependent construction until first use. The timing change is observable, so avoid assuming initialization work has occurred during object creation.
- [Using generic type constraints in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/using-generic-type-constraints-in-swift-4)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses generic constraints to describe the capabilities an algorithm needs rather than accepting overly concrete types. Precise constraints preserve reuse, but excessive associated-type complexity can hurt diagnostics.
- [Using errors as control flow in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/using-errors-as-control-flow-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI · Testing
  **NeKI brief:** Examines using thrown errors for control-flow branches and the trade-off with explicit optionals or enums. Errors fit exceptional failures; normal expected states are often clearer as data.
- [Using compiler directives in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/using-compiler-directives-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift · Xcode
  **NeKI brief:** Uses compiler directives for conditional compilation, diagnostics, and source organization. Directives should express real platform or build differences, not become a substitute for modular design.
- [Using Combine’s share operator to avoid duplicate work | Swift by Sundell](https://www.swiftbysundell.com/articles/using-combines-share-operator-to-avoid-duplicate-work)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Core Data · Persistence & Synchronisation · Swift · Testing
  **NeKI brief:** Uses Combine's share operator to multicast one upstream subscription to multiple observers, preventing repeated requests. Sharing changes lifetime and replay behavior, so subscribers must be coordinated deliberately.
- [Using child view controllers as plugins in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/using-child-view-controllers-as-plugins-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses child view controllers as pluggable feature units with explicit containment boundaries. The pattern helps composition, while parent-child lifecycle forwarding remains mandatory for correct behavior.
- [Using @autoclosure when designing Swift APIs | Swift by Sundell](https://www.swiftbysundell.com/articles/using-autoclosure-when-designing-swift-apis)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses @autoclosure to defer evaluation behind an API that reads like a value parameter. Restrict it to obvious laziness; hidden side effects or expensive expressions make call sites misleading.
- [Using ‘@unknown default’ within switch statements | Swift by Sundell](https://www.swiftbysundell.com/articles/using-an-unknown-default-case-within-a-switch-statement)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses @unknown default to handle future enum cases while retaining compiler diagnostics for known cases. It is especially useful for non-frozen system enums and should log or degrade safely.
- [Useful APIs when writing scripts and tools in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/useful-apis-when-writing-scripts-and-tools-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Networking · Swift · SwiftUI
  **NeKI brief:** Collects Foundation and process APIs useful for Swift command-line tools, such as paths and arguments. Tooling code still needs explicit error output and stable exit statuses for automation.
- [Unit testing asynchronous Swift code | Swift by Sundell](https://www.swiftbysundell.com/articles/unit-testing-asynchronous-swift-code)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Tests asynchronous Swift code by controlling completion and synchronization rather than sleeping. Injecting dependencies or clocks improves deterministic assertions and reveals race conditions earlier.
- [Under the hood of Futures and Promises in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/under-the-hood-of-futures-and-promises-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Networking · Swift
  **NeKI brief:** Explains futures and promises as abstractions for values delivered later and the state transitions they manage. They can organize callbacks, but cancellation and error propagation need explicit semantics.
- [Under the hood of Assertions in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/under-the-hood-of-assertions-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift · Testing
  **NeKI brief:** Examines assertion behavior across debug and release builds, clarifying which checks execute in production. Assertions protect programmer invariants, while user-recoverable failures require ordinary error handling.
- [UI testing analytics code in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/ui-testing-analytics-code-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Tests analytics through injected recording dependencies rather than requiring a live backend during UI tests. Assert meaningful events and payloads, while keeping test instrumentation separate from production transport.
- [Type inference-powered serialization in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/type-inference-powered-serialization-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses type inference to reduce serialization boilerplate while preserving typed decoding paths. Inference improves ergonomics, but schema validation and migration behavior must remain explicit.
- [Type erasure using closures in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/type-erasure-using-closures-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses closures for type erasure when generic protocols cannot be stored directly. The wrapper preserves only the required operations, trading concrete type information for a simpler abstraction boundary.
- [Trimming long argument lists in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/trimming-long-argument-lists-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Shortens unwieldy argument lists by grouping related configuration into value types or builders. The refactor improves call-site clarity, but group fields should share a coherent ownership and lifecycle.
- [Transforming collections in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/transforming-collections-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses map, compactMap, flatMap, and reduce to transform collections with clear output semantics. Choose operations by the required shape so concise pipelines do not conceal allocation or error-handling behavior.
- [Time traveling in Swift unit tests | Swift by Sundell](https://www.swiftbysundell.com/articles/time-traveling-in-swift-unit-tests)
  **Published:** `2021-10-30`
  **Topics:** Swift · Testing
  **NeKI brief:** Controls time in unit tests through injectable clocks or schedulers so timers and delayed work become deterministic. Advancing a test clock is faster and more reliable than sleeping in assertions.
- [Throwing and asynchronous Swift properties | Swift by Sundell](https://www.swiftbysundell.com/articles/throwing-async-properties)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Explains async and throwing computed properties as accessors that may suspend or fail. Use them for value-like retrieval, while operations with significant side effects may be clearer as methods.
- [The Swift 5.1 features that power SwiftUI’s API | Swift by Sundell](https://www.swiftbysundell.com/articles/the-swift-51-features-that-power-swiftuis-api)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI · UIKit
  **NeKI brief:** Explains Swift 5.1 language features such as result builders, opaque types, and property wrappers through the APIs they enable. The article connects syntax to framework design rather than treating features in isolation.
- [The power of UserDefaults in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/the-power-of-userdefaults-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Persistence & Synchronisation · Swift · SwiftData · Testing
  **NeKI brief:** Uses UserDefaults for small preference values with typed access patterns and defaults. It is not a database or secret store; migrations and key ownership should be centralized.
- [The power of type aliases in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/the-power-of-type-aliases-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses type aliases to shorten complex types and add domain vocabulary without runtime wrappers. Aliases improve readability, but do not enforce separation between otherwise identical underlying types.
- [The power of switch statements in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/the-power-of-switch-statements-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses exhaustive switch statements to model finite cases and bind associated values clearly. Switches make new enum cases compiler-visible, while default should be reserved for truly open domains.
- [The power of subscripts in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/the-power-of-subscripts-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses subscripts to expose collection-like access that reads naturally at call sites. A subscript should have predictable cost and side effects; complex operations often belong in named methods.
- [The power of sets in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/the-power-of-sets-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Core Data · Performance · Persistence & Synchronisation · Swift
  **NeKI brief:** Uses Set for uniqueness and efficient membership checks when order is not part of the contract. Stable presentation order needs a separate sorted or ordered representation.
- [The power of Result types in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/the-power-of-result-types-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses Result to carry success or failure through callback-oriented code and transformation pipelines. Keep domain errors informative, and avoid layering Result on top of throws without a clear boundary.
- [The power of key paths in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/the-power-of-key-paths-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Uses key paths to reference properties type-safely for sorting, mapping, and configuration APIs. They replace string reflection, while mutation key paths still require clear ownership.
- [The power of extensions in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/the-power-of-extensions-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Uses extensions to organize conformances and focused behavior around a type. Extensions improve navigation, but splitting tightly coupled mutable logic across files can obscure invariants.
- [Using the MainActor attribute to automatically dispatch UI updates on the main queue | Swift by Sundell](https://www.swiftbysundell.com/articles/the-main-actor-attribute)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Uses MainActor isolation to express UI-affine state and make compiler-enforced hops to the main executor. It prevents many data races, but long work must still leave the main actor.
- [The lifecycle and semantics of a SwiftUI view | Swift by Sundell](https://www.swiftbysundell.com/articles/the-lifecycle-and-semantics-of-a-swiftui-view)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI · Testing · UIKit
  **NeKI brief:** Explains SwiftUI views as transient value descriptions rather than long-lived UI objects. Store durable state in appropriate property wrappers or models, not in assumptions about a body instance.
- [The Decade of Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/the-decade-of-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Reflects on Swift's decade of language and ecosystem evolution. Use it as historical context when evaluating why value semantics, protocol-oriented design, and modern concurrency became central to current Swift architecture.
- [Testing Swift code that uses system singletons in 3 easy steps | Swift by Sundell](https://www.swiftbysundell.com/articles/testing-swift-code-that-uses-system-singletons-in-3-easy-steps)
  **Published:** `2021-10-30`
  **Topics:** Swift · Testing · UIKit
  **NeKI brief:** Creates seams around system singletons so tests can control environmental behavior without touching global process state. Thin wrappers preserve production APIs while enabling deterministic test doubles.
- [Testing networking logic in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/testing-networking-logic-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Networking · Swift · Testing
  **NeKI brief:** Separates networking logic from URLSession by injecting a request-performing abstraction, then tests success and failure paths with deterministic stubs; the archived article remains useful for dependency boundaries and response decoding.
- [Testing error code paths in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/testing-error-code-paths-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift · Testing · Xcode
  **NeKI brief:** Builds focused tests for thrown-error branches by injecting failing dependencies and asserting domain-specific errors, illustrating how error seams make recovery behavior testable without coupling tests to implementation details.
- [Test assertions in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/test-assertions-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift · Testing
  **NeKI brief:** Explains writing clear test assertions that verify outcomes and produce useful failures. Prefer focused expectations over broad boolean checks so regressions reveal the violated contract.
- [A guide to SwiftUI’s state management system | Swift by Sundell](https://www.swiftbysundell.com/articles/swiftui-state-management-guide)
  **Published:** `2021-10-30`
  **Topics:** Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Provides a state-management guide for SwiftUI. Use it when choosing local state, bindings, observable objects, or environment propagation based on actual ownership.
- [A guide to the SwiftUI layout system - Part 3 | Swift by Sundell](https://www.swiftbysundell.com/articles/swiftui-layout-system-guide-part-3)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Continues a SwiftUI layout-system guide with advanced proposal, sizing, and placement behavior. It is useful for debugging unexpected layouts, while custom layout code needs dynamic-type testing.
- [A guide to the SwiftUI layout system - Part 2 | Swift by Sundell](https://www.swiftbysundell.com/articles/swiftui-layout-system-guide-part-2)
  **Published:** `2021-10-30`
  **Topics:** Dependency Injection · Swift · SwiftUI
  **NeKI brief:** Explains intermediate SwiftUI layout mechanics and how parent proposals affect child size. Understanding proposal flow prevents incorrect frame modifiers used as compensating fixes.
- [Which of the SwiftUI APIs introduced in iOS 15 are backward compatible? | Swift by Sundell](https://www.swiftbysundell.com/articles/swiftui-ios15-backward-compatibility)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI · UIKit
  **NeKI brief:** Addresses SwiftUI iOS 15 backward compatibility. Use it when adopting newer APIs while preserving behavior and compilation across lower deployment targets.
- [Using SwiftUI’s frame modifier to resize and align views | Swift by Sundell](https://www.swiftbysundell.com/articles/swiftui-frame-modifier)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Explains SwiftUI frame as a layout proposal and alignment tool rather than a direct view resize command. Frame behavior depends on parent and child constraints, so inspect the full layout hierarchy.
- [SwiftUI and UIKit interoperability - Part 2 | Swift by Sundell](https://www.swiftbysundell.com/articles/swiftui-and-uikit-interoperability-part-2)
  **Published:** `2021-10-30`
  **Topics:** Observation & State Management · Swift · SwiftUI · UIKit
  **NeKI brief:** Extends SwiftUI/UIKit interoperability with representable lifecycle and coordination patterns. Bridges should translate state deliberately in both directions and avoid treating either framework as a passive wrapper.
- [SwiftUI and UIKit interoperability - Part 1 | Swift by Sundell](https://www.swiftbysundell.com/articles/swiftui-and-uikit-interoperability-part-1)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift · SwiftUI · UIKit
  **NeKI brief:** Introduces integrating SwiftUI into UIKit and UIKit views into SwiftUI for gradual migration. Clear ownership of navigation, state, and lifecycle prevents adapters from becoming hidden architecture layers.
- [Swift’s closure capturing mechanics | Swift by Sundell](https://www.swiftbysundell.com/articles/swifts-closure-capturing-mechanics)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Explains how Swift closures capture values and references, including ownership and mutation behavior. Use it when diagnosing retain cycles, stale snapshots, or unexpected lifetime extension in asynchronous callbacks.
- [Swift sequences: The art of being lazy | Swift by Sundell](https://www.swiftbysundell.com/articles/swift-sequences-the-art-of-being-lazy)
  **Published:** `2021-10-30`
  **Topics:** Observation & State Management · Performance · Persistence & Synchronisation · Swift · SwiftUI
  **NeKI brief:** Explains lazy Swift sequences as deferred transformations that avoid intermediate allocation until iteration. Laziness can improve pipelines, but deferred work and retained inputs should be obvious to callers.
- [Swift playgrounds tips and tricks | Swift by Sundell](https://www.swiftbysundell.com/articles/swift-playgrounds-tips-tricks)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Dependency Injection · Swift · Swift Package Manager · Xcode
  **NeKI brief:** Uses Swift playgrounds for small experiments, visual output, and API exploration without an app target. Playgrounds shorten feedback loops, while project integration and concurrency behavior still need real-target verification.
- [Subclass-free view controllers in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/subclass-free-view-controllers-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Builds view-controller composition without deep subclass hierarchies by injecting behavior or child components. This reduces inheritance coupling, while UIKit lifecycle responsibilities must remain clear.
- [Styling localized strings in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/styled-localized-strings-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI · UIKit
  **NeKI brief:** Builds styled localized strings while retaining translator-controlled ordering and placeholders. Apply attributes after localization or use supported interpolation so styles do not break grammar in other languages.
- [Structuring Swift code | Swift by Sundell](https://www.swiftbysundell.com/articles/structuring-swift-code)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Organizes Swift code around cohesive types, extensions, and feature boundaries to improve navigation. Structure should surface ownership and dependencies, not simply distribute methods across arbitrary files.
- [Structuring model data in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/structuring-model-data-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Structures model data with types that encode valid states and relationships explicitly. Good models reduce downstream conditional logic, while persistence and decoding boundaries require separate adaptation layers.
- [Stroking and filling a SwiftUI shape at the same time | Swift by Sundell](https://www.swiftbysundell.com/articles/stroking-and-filling-a-swiftui-shape-at-the-same-time)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Shows composing SwiftUI shapes so fill and stroke can be applied without losing the original shape value. Preserve geometry through overlays or duplicate shape definitions carefully when state changes.
- [String parsing in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/string-parsing-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Parses strings using explicit indices, ranges, and validation instead of assuming byte offsets. Parsing user or network input needs failure paths and Unicode-aware rules.
- [String literals in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/string-literals-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Explains Swift string literal forms including multiline and raw delimiters for readable source text. Literal convenience does not remove the need to validate dynamic or external strings.
- [Static factory methods in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/static-factory-methods-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Architecture · Concurrency · Dependency Injection · Swift · Testing
  **NeKI brief:** Uses static factory methods to name construction intent and centralize configured defaults. Factories are most useful when creation validates or selects variants beyond a plain initializer.
- [Splitting up Swift types | Swift by Sundell](https://www.swiftbysundell.com/articles/splitting-up-swift-types)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Splits oversized Swift types along stable responsibilities while preserving clear collaboration through protocols or values. Extraction should reduce coupling, not relocate methods without changing ownership.
- [Specializing protocols in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/specializing-protocols-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Specializes protocols with constraints to expose behavior only for compatible conformers. This keeps APIs type-safe, while overly narrow constraints can make reuse and diagnostics difficult.
- [Specialized extensions using generic type constraints | Swift by Sundell](https://www.swiftbysundell.com/articles/specialized-extensions-using-generic-type-constraints)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses generic constraints on extensions to add focused operations for specific element or associated types. The technique avoids runtime checks, but names and constraints should make applicability obvious.
- [Sorting Swift collections | Swift by Sundell](https://www.swiftbysundell.com/articles/sorting-swift-collections)
  **Published:** `2021-10-30`
  **Topics:** Performance · Swift
  **NeKI brief:** Explains sorting Swift collections with custom comparators and key extraction. Ordering should be stable from the user's perspective, and comparator logic must define a coherent relation.
- [Slot-based UI development in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/slot-based-ui-development-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Uses slot-based composition to let containers accept named pieces of UI without rigid inheritance. Slots improve reuse, while required and optional content contracts need clear defaults.
- [Slicing Swift collections | Swift by Sundell](https://www.swiftbysundell.com/articles/slicing-swift-collections)
  **Published:** `2021-10-30`
  **Topics:** Performance · Swift
  **NeKI brief:** Uses collection slices to work on a range without immediately copying storage. Slices retain their original collection, so convert to an owned array when storing a small subsection long term.
- [Simple Swift dependency injection with functions | Swift by Sundell](https://www.swiftbysundell.com/articles/simple-swift-dependency-injection-with-functions)
  **Published:** `2021-10-30`
  **Topics:** Architecture · Dependency Injection · Swift · Testing
  **NeKI brief:** Uses functions as simple dependency-injection seams for operations such as loading or formatting. This keeps tests lightweight, while larger dependency groups may need a dedicated value type.
- [Shifting paradigms in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/shifting-paradigms-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI · UIKit
  **NeKI brief:** Discusses changing programming paradigms in Swift through values, protocols, and functional composition. Adopt techniques where they clarify the domain, not merely because they are stylistically fashionable.
- [Sharing Swift code | Swift by Sundell](https://www.swiftbysundell.com/articles/sharing-swift-code)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Shares Swift code across targets through modules and packages rather than source-file copying. Explicit dependencies improve reuse, while platform-specific adapters keep common code portable.
- [Separation of concerns using protocols in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/separation-of-concerns-using-protocols-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Architecture · Swift · SwiftUI
  **NeKI brief:** Uses protocols to separate collaborators by the behavior each caller needs, reducing direct dependency on concrete types. Protocol boundaries should follow stable responsibilities, not be created for every class.
- [Applying rounded corners to a UIKit or SwiftUI view | Swift by Sundell](https://www.swiftbysundell.com/articles/rounded-corners-uikit-swiftui)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI · UIKit
  **NeKI brief:** Compares rounded-corner techniques in UIKit and SwiftUI, including clipping and masking implications. Follow it when matching visual shape, hit testing, and rendering behavior across mixed framework screens.
- [Review: Swift Playgrounds 3.0 for iPad | Swift by Sundell](https://www.swiftbysundell.com/articles/review-swift-playgrounds-30-for-ipad)
  **Published:** `2021-10-30`
  **Topics:** Swift · Testing · Xcode
  **NeKI brief:** Reviews Swift Playgrounds on iPad as a learning and experimentation environment. It can support rapid exploration, while production projects still need full build, test, and source-control workflows.
- [Reusable data sources in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/reusable-data-sources-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI · UIKit
  **NeKI brief:** Builds reusable data sources by separating collection configuration from view-controller presentation. Reuse improves consistency, while cell-specific behavior and ownership must remain clear.
- [Replacing legacy code using Swift protocols | Swift by Sundell](https://www.swiftbysundell.com/articles/replacing-legacy-code-using-swift-protocols)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Uses protocols as seams for incrementally replacing legacy implementations without a big-bang rewrite. Preserve observable behavior with tests, then migrate callers behind the new abstraction.
- [Rendering textured views with SwiftUI | Swift by Sundell](https://www.swiftbysundell.com/articles/rendering-textured-views-with-swiftui)
  **Published:** `2021-10-30`
  **Topics:** Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Renders textured SwiftUI views using composable drawing and visual layers instead of bitmap-only backgrounds. Keep textures lightweight and ensure contrast and performance remain acceptable during scrolling.
- [Reflection in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/reflection-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Explores Swift reflection for inspecting values at runtime and its limitations. Reflection is useful for diagnostics or tooling, but compile-time protocols and explicit metadata are safer for core behavior.
- [Refactoring Swift code for testability | Swift by Sundell](https://www.swiftbysundell.com/articles/refactoring-swift-code-for-testability)
  **Published:** `2021-10-30`
  **Topics:** Architecture · Concurrency · Dependency Injection · Swift · SwiftUI · Testing
  **NeKI brief:** Refactors code toward injectable dependencies and explicit inputs so behavior can be tested in isolation. Preserve observable behavior during extraction and avoid introducing abstractions that only serve mock mechanics.
- [Reducing flakiness in Swift tests | Swift by Sundell](https://www.swiftbysundell.com/articles/reducing-flakiness-in-swift-tests)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Reduces test flakiness by controlling asynchronous work, shared state, and timing assumptions. A stable test waits on meaningful conditions and isolates external services rather than retrying failures.
- [Reducers in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/reducers-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Uses reducers to turn state and actions into deterministic next state, making event handling testable. Effects should be modeled at the boundary so reducer logic stays pure.
- [Querying collections in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/querying-collections-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Queries Swift collections with predicates, filtering, and lookup operations chosen for the required result shape. Keep complexity in mind when chaining scans across large datasets.
- [Pure functions in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/pure-functions-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Uses pure functions for deterministic transformations without side effects or hidden dependencies. Purity improves testability and composition, while IO and stateful work belong in explicit outer layers.
- [Published properties in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/published-properties-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Networking · Swift
  **NeKI brief:** Uses published properties to expose observable state changes to Combine or UI subscribers. Define ownership and scheduling so updates are consistent and subscriptions do not outlive their consumers.
- [Providing a unified Swift error API | Swift by Sundell](https://www.swiftbysundell.com/articles/providing-a-unified-swift-error-api)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Unifies errors behind a domain API so callers can handle failures consistently across implementations. Preserve underlying diagnostic details while mapping user-facing recovery into stable categories.
- [Property wrappers in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/property-wrappers-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses property wrappers to encapsulate repeated storage, validation, or projection behavior at declarations. Wrappers reduce boilerplate, but hidden mutation and initialization semantics should remain transparent to callers.
- [Property observers in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/property-observers-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Uses willSet and didSet for localized reactions to stored-property mutation. Observers are synchronous and can cascade changes, so complex side effects should move into explicit methods or models.
- [Propagating user-facing errors in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/propagating-user-facing-errors-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI · UIKit
  **NeKI brief:** Maps low-level failures into user-facing errors with actionable descriptions and recovery choices. Preserve the underlying error for diagnostics while presenting stable product language.
- [Previewing SwiftUI views in landscape | Swift by Sundell](https://www.swiftbysundell.com/articles/previewing-swiftui-views-in-landscape)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI · Xcode
  **NeKI brief:** Previews SwiftUI views in landscape to expose width, safe-area, and compact-height issues early. Use previews for iteration, then confirm behavior on actual devices and dynamic settings.
- [Preventing views from being model aware in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/preventing-views-from-being-model-aware-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Prevents views from directly depending on rich models by supplying presentation-focused values or view models. The separation improves testability, while transformations should remain close to feature ownership.
- [Predicates in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/predicates-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses predicates to express filtering conditions separately from collection traversal or storage queries. Predicate design should preserve type safety and make composition readable, especially for user-provided search input.
- [Pragmatic unit testing in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/pragmatic-unit-testing-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Advocates unit tests that target behavior and valuable risk instead of mechanical coverage. Keep setup concise and assertions specific so tests remain maintainable through refactoring.
- [Five powerful, yet lesser-known ways to use Swift enums | Swift by Sundell](https://www.swiftbysundell.com/articles/powerful-ways-to-use-swift-enums)
  **Published:** `2021-10-30`
  **Topics:** Persistence & Synchronisation · Swift
  **NeKI brief:** Uses Swift enums with associated values, raw values, and exhaustive switches to model finite domain states. Enums remove invalid combinations when cases represent mutually exclusive behavior.
- [Picking the right way of failing in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/picking-the-right-way-of-failing-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Compares throws, Result, optionals, and assertions for different failure semantics. Pick the form that matches recoverability and caller context instead of forcing every failure into one channel.
- [Picking the right data structure in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/picking-the-right-data-structure-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftData
  **NeKI brief:** Chooses Swift collections according to access, ordering, uniqueness, and mutation requirements. Data-structure choice is a domain and complexity decision, not just a matter of familiar syntax.
- [Phantom types in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/phantom-types-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses phantom types to encode compile-time distinctions without storing extra runtime data. This can prevent invalid API combinations, but the additional generic vocabulary should pay for its complexity.
- [Pattern matching in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/pattern-matching-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses Swift pattern matching to destructure enums, optionals, tuples, and ranges without scattered type checks. Patterns should express domain cases clearly and retain exhaustiveness where possible.
- [Open sourcing Swift code | Swift by Sundell](https://www.swiftbysundell.com/articles/open-sourcing-swift-code)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Discusses preparing Swift code for open source through documentation, licensing, and stable public APIs. Extraction should include tests and clear dependency boundaries rather than merely publishing internal files.
- [Opaque return types in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/opaque-return-types-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Uses opaque return types to hide a concrete conforming type while retaining static protocol information. This avoids many type-erasure costs, but the underlying type must remain consistent per declaration.
- [Observers in Swift - Part 2 | Swift by Sundell](https://www.swiftbysundell.com/articles/observers-in-swift-part-2)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Continues observer design in Swift with lifecycle and callback management concerns. Observers should have explicit registration and cancellation rules to avoid leaks or stale updates.
- [Observers in Swift - Part 1 | Swift by Sundell](https://www.swiftbysundell.com/articles/observers-in-swift-part-1)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Introduces observer patterns for broadcasting changes between Swift components. Keep event contracts narrow and make ownership of subscriptions visible at the registration boundary.
- [Navigation in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/navigation-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Navigation & Deep Linking · Swift
  **NeKI brief:** Models navigation as state and transitions rather than scattering controller pushes through feature code. A clear routing boundary improves deep linking, testing, and restoration behavior.
- [Namespacing Swift code with nested types | Swift by Sundell](https://www.swiftbysundell.com/articles/namespacing-swift-code-with-nested-types)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses nested types to namespace related values and avoid global name collisions. Nesting communicates ownership, while overly deep names can reduce discoverability across modules.
- [Mutating and non-mutating Swift contexts | Swift by Sundell](https://www.swiftbysundell.com/articles/mutating-and-nonmutating-swift-contexts)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Explains mutating and nonmutating contexts in Swift value types and property wrappers. The distinction communicates state changes explicitly and affects which methods can run on immutable bindings.
- [Modelling state in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/modelling-state-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Models state with types that encode valid transitions and associated data rather than unrelated flags. A finite state model reduces impossible combinations and makes updates easier to test.
- [Model controllers in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/model-controllers-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Models controller-like coordination around explicit dependencies and state transitions rather than view-specific logic. The boundary improves tests, while UI routing should remain separate from domain decisions.
- [Mocking in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/mocking-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Networking · Swift · Testing
  **NeKI brief:** Uses mocks selectively to observe collaborations in tests while avoiding replication of implementation details. Favor fakes or values when behavior can be tested without interaction-count assertions.
- [Mock-free unit tests in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/mock-free-unit-tests-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Persistence & Synchronisation · Swift · Testing
  **NeKI brief:** Uses values, pure functions, and controllable dependencies to test behavior without elaborate mocks. Mock-free tests often better survive refactoring, though interaction verification still has focused use cases.
- [Mixing enums with other Swift types | Swift by Sundell](https://www.swiftbysundell.com/articles/mixing-enums-with-other-swift-types)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Combines enums with structs or classes to model finite variants alongside shared data. Keep variant-specific behavior in the enum and shared invariants in the companion type.
- [Managing objects using Locks and Keys in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/managing-objects-using-locks-and-keys-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Architecture · Concurrency · Swift
  **NeKI brief:** Manages shared objects with synchronization and keyed lookup patterns. Locks require disciplined scope and ordering; actor isolation may provide a safer modern alternative for async code.
- [Managing dependencies using the Swift Package Manager | Swift by Sundell](https://www.swiftbysundell.com/articles/managing-dependencies-using-the-swift-package-manager)
  **Published:** `2021-10-30`
  **Topics:** Dependency Injection · Swift · Swift Package Manager · Xcode
  **NeKI brief:** Uses Swift Package Manager to declare and resolve dependencies through manifests and version requirements. Pinning and update policy should balance reproducibility, security, and maintenance.
- [Making Swift tests easier to debug | Swift by Sundell](https://www.swiftbysundell.com/articles/making-swift-tests-easier-to-debug)
  **Published:** `2021-10-30`
  **Topics:** Swift · Testing
  **NeKI brief:** Improves test diagnostics with precise assertions, fixtures, and contextual failure messages. Debuggable tests shorten feedback loops without adding logging noise to every successful run.
- [Making Swift code extensible through plugins | Swift by Sundell](https://www.swiftbysundell.com/articles/making-swift-code-extensible-through-plugins)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses plugin-style extension points to make Swift code configurable without modifying a central implementation for every variant. The plugin contract should remain narrow and define lifecycle and error behavior.
- [Maintaining model consistency in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/maintaining-model-consistency-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Core Data · Persistence & Synchronisation · Swift
  **NeKI brief:** Maintains model consistency by centralizing invariants and preventing callers from independently mutating related fields. Typed transitions make invalid intermediate states harder to construct.
- [Logic controllers in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/logic-controllers-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Separates feature logic into controllers that coordinate models and services without becoming view controllers. This supports testing, while navigation and rendering remain owned by their appropriate layers.
- [Lightweight presenters in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/lightweight-presenters-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses lightweight presenters to transform domain output into display-ready data without tightly coupling views to models. Keep presenters deterministic so they can be tested as pure presentation policy.
- [Lightweight API design in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/lightweight-api-design-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Designs lightweight Swift APIs around clear types, sensible defaults, and small surface area. Good ergonomics should not hide costly work, ownership rules, or invalid configuration states.
- [Learning SwiftUI by building tools and prototypes | Swift by Sundell](https://www.swiftbysundell.com/articles/learning-swiftui-by-building-tools-and-prototypes)
  **Published:** `2021-10-30`
  **Topics:** Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Uses small tools and prototypes to learn SwiftUI interactions before applying them to a production feature. Experiments reveal API behavior, while accessibility, state ownership, and performance still need product validation.
- [Launch arguments in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/launch-arguments-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift · Testing
  **NeKI brief:** Uses launch arguments to configure process behavior for testing or diagnostics without changing source. Keep flags scoped to development paths and document precedence over persisted user settings.
- [Introducing Plot Components: A new way to build HTML pages using Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/introducing-plot-components)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Introduces reusable Plot components for server-side HTML. Use it when a Swift web project needs composable markup primitives instead of repeating page structure.
- [Integration tests in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/integration-tests-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Persistence & Synchronisation · Swift · Testing
  **NeKI brief:** Uses integration tests to exercise real collaboration between modules, persistence, or network adapters. They complement unit tests and need controlled environments to remain reliable.
- [Inline types and functions in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/inline-types-and-functions-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Uses inline types and functions to keep small implementation details near their only consumer. Locality improves readability, while reusable or independently tested behavior should move to named scope.
- [Initializers in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/initializers-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Explains Swift initialization rules, designated and convenience paths, and invariant establishment. Keep all stored properties valid before self escapes or overridable behavior runs.
- [Identifying objects in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/identifying-objects-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Distinguishes object identity from value equality when tracking reference instances in Swift. Use identity for ownership or caching questions; value equality answers whether state is equivalent.
- [How Swift 5.3 enhances SwiftUI’s DSL | Swift by Sundell](https://www.swiftbysundell.com/articles/how-swift-5-3-enhances-swiftui-dsl)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Connects Swift 5.3 language enhancements to the expressiveness of SwiftUI's declarative DSL. Understand generated builder behavior before relying on syntax that can complicate type diagnostics.
- [Handling non-optional optionals in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/handling-non-optional-optionals-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Handles values that are technically optional but required by a domain boundary through validation and conversion. Move the unwrapping close to input so deeper logic does not carry misleading optionality.
- [Handling mutable models in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/handling-mutable-models-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Architecture · Swift · SwiftUI
  **NeKI brief:** Manages mutable models by controlling write access and observing meaningful transitions. Value semantics or actor isolation can reduce accidental shared mutation depending on the model's ownership.
- [Handling model variants in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/handling-model-variants-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift · Testing · Xcode
  **NeKI brief:** Models variants with enums or typed representations instead of loosely optional fields. Variant-aware types make rendering and serialization branches exhaustive and easier to evolve.
- [Handling loading states within SwiftUI views | Swift by Sundell](https://www.swiftbysundell.com/articles/handling-loading-states-in-swiftui)
  **Published:** `2021-10-30`
  **Topics:** Accessibility · Concurrency · Swift · SwiftUI
  **NeKI brief:** Models loading, loaded, and failure UI states in SwiftUI. Use it when asynchronous content needs an explicit state machine instead of optional data scattered through a view.
- [Getting the most out of Xcode Previews for SwiftUI | Swift by Sundell](https://www.swiftbysundell.com/articles/getting-the-most-out-of-xcode-previews)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI · UIKit · Xcode
  **NeKI brief:** Uses Xcode previews with representative data and environment variants to speed UI iteration. Previews supplement, not replace, simulator and device testing of lifecycle and integration behavior.
- [Getting started with Xcode UI testing in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/getting-started-with-xcode-ui-testing-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Accessibility · Concurrency · Swift · Testing · Xcode
  **NeKI brief:** Starts Xcode UI testing with accessibility queries, actions, and assertions tied to user-visible state. Stable identifiers and synchronization conditions are essential for reliable test runs.
- [Generalizing Swift code | Swift by Sundell](https://www.swiftbysundell.com/articles/generalizing-swift-code)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Networking · Swift
  **NeKI brief:** Generalizes Swift code by extracting the true variable parts into parameters or generic constraints. Abstraction should follow repeated stable behavior, not anticipated reuse without evidence.
- [Functional networking in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/functional-networking-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Networking · Swift · Testing
  **NeKI brief:** Builds networking from composable pure request and response transformations, isolating side effects at the transport edge. This improves tests while authentication and retry policy stay explicit.
- [First class functions in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/first-class-functions-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses functions as values for callbacks and transformations, allowing behavior to be composed or injected. Function signatures should communicate errors, ownership, and execution context clearly.
- [Feature flags in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/feature-flags-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses feature flags to release incomplete behavior safely while keeping one integrated code path. Flags need owners, test coverage for both states, and a removal date to prevent permanent complexity.
- [Extracting view controller actions in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/extracting-view-controller-actions-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Extracts view-controller action logic into focused collaborators so event handling can be tested without UI lifecycle setup. Keep navigation and presentation ownership explicit at the boundary.
- [Extending optionals in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/extending-optionals-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Adds focused Optional extensions to centralize recurring nil-handling operations. Helpers should preserve explicit absence semantics and avoid hiding errors or side effects behind convenience names.
- [Extending Combine with convenience APIs | Swift by Sundell](https://www.swiftbysundell.com/articles/extending-combine-with-convenience-apis)
  **Published:** `2021-10-30`
  **Topics:** Networking · Swift · Testing
  **NeKI brief:** Extends Combine with domain-focused operators or helpers to remove repeated pipeline glue. Keep cancellation, scheduling, and error behavior visible so convenience does not obscure reactive lifecycle.
- [Exploring the new String API in Swift 4 | Swift by Sundell](https://www.swiftbysundell.com/articles/exploring-the-new-string-api-in-swift-4)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Explores Swift 4 String APIs through Unicode-aware indexing and collection behavior. Modern text logic should avoid integer offsets and validate assumptions with emoji and localized input.
- [Exploring Swift 5.2’s new functional features | Swift by Sundell](https://www.swiftbysundell.com/articles/exploring-swift-5-2s-new-functional-features)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Surveys Swift 5.2 functional additions and their effect on collection transformations and key-path expressions. Follow it when modernizing older imperative code while checking readability and type-inference costs.
- [Exploring some of the lesser-known, built-in Formatter types | Swift by Sundell](https://www.swiftbysundell.com/articles/exploring-some-of-the-lesser-known-formatter-types)
  **Published:** `2021-10-30`
  **Topics:** Persistence & Synchronisation · Swift
  **NeKI brief:** Surveys built-in Formatter subclasses beyond common date and number formatting. Use it when presentation rules should use Foundation's localized formatters instead of hand-built string conversion.
- [Enum iterations in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/enum-iterations-in-swift-42)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses CaseIterable and related patterns to enumerate finite enum cases for UI or tests. Associated-value enums need an explicit domain collection because synthesis cannot invent payloads.
- [Encapsulating SwiftUI view styles | Swift by Sundell](https://www.swiftbysundell.com/articles/encapsulating-swiftui-view-styles)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Encapsulates SwiftUI styling in reusable view styles and modifiers. Use it when visual conventions repeat across screens and should remain separate from feature-specific layout.
- [Encapsulating configuration code in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/encapsulating-configuration-code-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Encapsulates configuration in types or builders so setup does not scatter through call sites. The configuration boundary should validate defaults and make environment-specific choices auditable.
- [Early returning functions in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/early-returning-functions-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses guard and early returns to keep the successful path unindented and make preconditions visible. Each exit should represent one clear failed invariant or recoverable condition.
- [Dismissing a SwiftUI modal or detail view | Swift by Sundell](https://www.swiftbysundell.com/articles/dismissing-swiftui-modal-and-detail-views)
  **Published:** `2021-10-30`
  **Topics:** Architecture · Swift · SwiftUI
  **NeKI brief:** Uses SwiftUI dismissal actions to close modal or detail presentations without coupling a child to navigation storage. Dismissal should respect the owning presentation context and unsaved-state policy.
- [Different flavors of view models in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/different-flavors-of-view-models-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Compares view-model styles as presentation adapters with different ownership and transformation responsibilities. Choose the smallest model that keeps views independent of domain and service details.
- [Different flavors of type erasure in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/different-flavors-of-type-erasure-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Compares type-erasure techniques such as boxes, closures, and opaque returns for handling protocol abstractions. Preserve only the needed capability and understand what static information is lost.
- [Different flavors of dependency injection in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/different-flavors-of-dependency-injection-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Architecture · Dependency Injection · Swift
  **NeKI brief:** Compares initializer, property, function, and environment-style dependency injection. Match the form to lifetime and requiredness, keeping production wiring explicit and test replacements local.
- [The different categories of Swift protocols | Swift by Sundell](https://www.swiftbysundell.com/articles/different-categories-of-swift-protocols)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Distinguishes protocol categories by purpose, such as capability, abstraction, and marker protocols. Clear intent prevents protocols from becoming vague containers of unrelated requirements.
- [Designing Swift APIs | Swift by Sundell](https://www.swiftbysundell.com/articles/designing-swift-apis)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Designs Swift APIs around caller readability, type safety, and clear failure semantics. Good names and defaults should reveal behavior without hiding performance or ownership trade-offs.
- [Designing reusable Swift libraries | Swift by Sundell](https://www.swiftbysundell.com/articles/designing-reusable-swift-libraries)
  **Published:** `2021-10-30`
  **Topics:** Swift · Testing
  **NeKI brief:** Designs reusable Swift libraries around small public APIs, stable abstractions, and explicit dependencies. Keep application-specific assumptions out of the package so clients can adopt it independently.
- [Dependency injection using factories in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/dependency-injection-using-factories-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Architecture · Concurrency · Dependency Injection · Swift · Testing
  **NeKI brief:** Factories can assemble dependencies near their creation site and avoid giant initializers while preserving test substitution. Give each factory a narrow product responsibility; a global container merely relocates hidden dependency coupling unless its ownership is explicit.
- [Delegation in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/delegation-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Choose protocol delegates for ongoing behavior contracts, closures for localized callbacks, and configuration values for static policy. The delegation mechanism should match ownership and lifetime; using a closure for long-lived coordination can obscure retention and cancellation.
- [Defining testing data in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/defining-testing-data-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Dependency Injection · Networking · Swift · Testing
  **NeKI brief:** Separate test input construction from verification and define reusable stubs for values that are irrelevant to each assertion. Focused fixture builders reduce duplication, while explicit expected output keeps tests readable when models gain new fields.
- [Defining dynamic colors in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/defining-dynamic-colors-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI · UIKit
  **NeKI brief:** Use system dynamic colors where their semantic roles fit, or create custom colors that resolve against the current trait or color scheme. Centralizing color construction keeps UIKit and SwiftUI appearances consistent across light and dark modes.
- [Defining custom patterns in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/defining-custom-patterns-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Define custom Swift pattern matching through ~= to make switch cases express domain predicates rather than raw equality. Compose patterns from ranges, predicates, and key paths, but keep matching rules unsurprising so case order remains understandable.
- [Default arguments in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/default-arguments-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Architecture · Dependency Injection · Swift
  **NeKI brief:** Uses default arguments to express common API configuration without overload proliferation. Defaults should be stable and unsurprising; required semantic choices deserve explicit parameters.
- [A deep dive into Swift’s result builders | Swift by Sundell](https://www.swiftbysundell.com/articles/deep-dive-into-swift-function-builders)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Explores result builders as the language mechanism behind declarative DSLs such as SwiftUI. Builder control flow and type inference should be understood before extending the pattern broadly.
- [Deciding whether to adopt new Swift technologies | Swift by Sundell](https://www.swiftbysundell.com/articles/deciding-whether-to-adopt-new-swift-technologies)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Offers criteria for adopting new Swift technologies, balancing capability, deployment targets, maturity, and team cost. Follow it when a platform feature is attractive but migration and support constraints remain material.
- [Deciding what DispatchQueue to run a completion handler on | Swift by Sundell](https://www.swiftbysundell.com/articles/deciding-what-queue-to-run-a-completion-handler-on)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Chooses a completion handler's execution queue as part of an asynchronous API contract. Document delivery context so UI callers and background consumers can synchronize correctly.
- [Customizing how an external Swift type is encoded or decoded | Swift by Sundell](https://www.swiftbysundell.com/articles/customizing-how-a-type-is-encoded-or-decoded)
  **Published:** `2021-10-30`
  **Topics:** Swift · Testing
  **NeKI brief:** Customizes Codable encoding and decoding when external schemas differ from domain models. Keep conversion logic version-aware and test both successful and malformed payloads.
- [Customizing Codable types in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/customizing-codable-types-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses Codable customization to handle key mapping, defaults, and special representations without leaking wire-format concerns across the model. Explicit decoding errors improve schema diagnostics.
- [Creating custom query functions using key paths | Swift by Sundell](https://www.swiftbysundell.com/articles/custom-query-functions-using-key-paths)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses key paths to build reusable query functions that remain type-safe compared with string-based field references. Query helpers should still make sorting and complexity behavior apparent.
- [Custom operators in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/custom-operators-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Defines custom operators only when their semantics are familiar, symmetric, and improve domain readability. Operators can hide behavior, so named methods are safer for surprising or effectful work.
- [Custom container view controllers in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/custom-container-view-controllers-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Architecture · Performance · Swift · UIKit
  **NeKI brief:** Builds a custom UIViewController container by adding, removing, and transitioning child controllers while forwarding containment callbacks, illustrating how explicit ownership can modularize UIKit screen composition.
- [Creating generic networking APIs in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/creating-generic-networking-apis-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Networking · Swift
  **NeKI brief:** Creates generic networking APIs around typed requests and decoded responses. Keep transport, authentication, retries, and error mapping configurable rather than embedding all policy in one generic layer.
- [Creating custom collections in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/creating-custom-collections-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Builds custom collections by conforming to the appropriate Swift collection protocols and honoring their complexity contracts. Correct index behavior and mutation rules matter as much as ergonomic subscripts.
- [Constructing URLs in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/constructing-urls-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Architecture · Networking · Swift · Testing
  **NeKI brief:** Constructs URLs from components so paths, queries, and percent encoding remain structurally correct. Avoid concatenating raw strings, especially when user input supplies query values.
- [Connecting and merging Combine publishers in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/connecting-and-merging-combine-publishers-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Connects and merges Combine publishers to coordinate multiple asynchronous streams. Define completion, failure, and cancellation semantics explicitly so merged output does not obscure source lifecycle.
- [Configuring SwiftUI views | Swift by Sundell](https://www.swiftbysundell.com/articles/configuring-swiftui-views)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Configures SwiftUI views through explicit inputs and modifiers rather than hidden global state. Configuration should remain composable and testable across previews and feature entry points.
- [Configurable types in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/configurable-types-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses configurable types to collect optional setup before constructing a value. The configuration API should validate incompatible options and keep defaults aligned with common use.
- [Conditional conformances in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/conditional-conformances-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Uses conditional conformances to make generic wrappers adopt protocols only when their contents qualify. This preserves type safety and avoids runtime capability checks.
- [Conditional compilation within Swift expressions | Swift by Sundell](https://www.swiftbysundell.com/articles/conditional-compilation-within-swift-expressions)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Uses conditional compilation inside Swift expressions for platform or build differences without duplicating surrounding code. Keep branches small and retire compatibility conditions as targets advance.
- [Computing dates in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/computing-dates-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Computes dates with Calendar and DateComponents so calculations respect time zones, daylight saving, and calendar rules. Avoid adding fixed seconds for user-facing date logic.
- [Computed properties in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/computed-properties-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Performance · Swift
  **NeKI brief:** Uses computed properties for derived, inexpensive value-like state. If computation is costly, effectful, or parameterized, a method or cached model may communicate intent better.
- [Composing types in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/composing-types-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Composes Swift types from small responsibilities rather than building large inheritance trees. Composition improves reuse, while collaborators need clear ownership and dependency direction.
- [Combining value and reference types in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/combining-value-and-reference-types-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Combines value and reference types according to ownership and mutation-sharing needs. Values model independent state; references suit identity or shared coordination with explicit synchronization.
- [Managing self and cancellable references when using Combine | Swift by Sundell](https://www.swiftbysundell.com/articles/combine-self-cancellable-memory-management)
  **Published:** `2021-10-30`
  **Topics:** Architecture · Swift
  **NeKI brief:** Explains Combine cancellable ownership and self capture to avoid subscriptions outliving their consumers. Store cancellables with the appropriate owner and design cancellation as part of lifecycle.
- [Code encapsulation in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/code-encapsulation-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Dependency Injection · Swift
  **NeKI brief:** Encapsulates Swift implementation details behind narrow APIs so callers depend on stable behavior rather than storage. Good boundaries make invariants enforceable and refactoring less risky.
- [Codable synthesis for Swift enums | Swift by Sundell](https://www.swiftbysundell.com/articles/codable-synthesis-for-swift-enums)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Swift 5.5 can synthesize Codable for enums with associated values, but the generated keys become part of persisted data. Customize coding keys when compatibility requires it, and test decoding across old payloads before changing enum structure.
- [Capturing objects in Swift closures | Swift by Sundell](https://www.swiftbysundell.com/articles/capturing-objects-in-swift-closures)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Closures capture referenced objects and can create cycles when stored by the same object graph. Prefer capturing narrower context or passing arguments when possible, and use weak references only when the closure's lifetime truly should not keep an owner alive.
- [Calling async functions within a Combine pipeline | Swift by Sundell](https://www.swiftbysundell.com/articles/calling-async-functions-within-a-combine-pipeline)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Core Data · Persistence & Synchronisation · Swift
  **NeKI brief:** Bridge async functions into a Combine pipeline with a publisher wrapper that forwards values, errors, and cancellation coherently. Keep the concurrency boundary small, since combining two asynchronous models without ownership rules can leave tasks running after cancellation.
- [Caching in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/caching-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Performance · Swift
  **NeKI brief:** Design a cache with explicit keys, lifetime, invalidation, and persistence boundaries rather than treating memoization as automatic performance. Fast reads are only correct while cached values remain valid; stale-data policy is part of the cache API.
- [Core Animation gems: Using replicator layers in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/ca-gems-using-replicator-layers-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** CAReplicatorLayer repeats a configured sublayer with instance transforms, offsets, and color changes, avoiding manual duplication of animation layers. Keep the original layer simple, since every property and timing choice is multiplied across its instances.
- [Building SwiftUI debugging utilities | Swift by Sundell](https://www.swiftbysundell.com/articles/building-swiftui-debugging-utilities)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Builds debugging utilities tailored to SwiftUI state and layout. Use it when temporary inspection aids can make view behavior observable without permanently cluttering production UI.
- [Building modern collection views in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/building-modern-collection-views-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI · UIKit
  **NeKI brief:** Surveys iOS 13–14 collection-view modernization through diffable data sources, compositional layouts, and list configurations, connecting declarative snapshots and composable sections to less fragile UICollectionView code.
- [Building iPad Pro features in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/building-ipad-pro-features-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI · Testing · UIKit
  **NeKI brief:** Treat Apple Pencil input, double taps, external displays, and keyboard shortcuts as distinct iPad capabilities with tailored interaction paths. Do not infer touch behavior from Pencil input; feature-specific affordances need explicit availability and focus handling.
- [Building editable lists with SwiftUI | Swift by Sundell](https://www.swiftbysundell.com/articles/building-editable-swiftui-lists)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Combine List or ForEach with stable collection identity to support deletion and moving, then wrap repeated editing policy in a reusable abstraction. Apply mutations to the source collection, not a transient view copy, so UI edits persist predictably.
- [Building DSLs in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/building-dsls-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Use Swift's type inference, overloads, and carefully chosen operators to make a domain API read like its problem language. A DSL should retain type safety and debuggability; clever syntax that hides invalid states is worse than an explicit API.
- [Building custom Combine publishers in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/building-custom-combine-publishers-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Build a custom Combine publisher only when built-in operators cannot express the source, then honor subscription demand and cancellation in its implementation. Demand handling is part of the publisher contract; emitting indiscriminately can overwhelm downstream consumers.
- [Building an enum-based analytics system in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/building-an-enum-based-analytics-system-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Architecture · Swift · Testing
  **NeKI brief:** Represent a closed analytics event vocabulary with enums, serialize each case centrally, and send it through a replaceable engine. This makes event names and payload requirements compiler-visible while letting production and test backends share the same API.
- [Building a declarative animation framework in Swift - Part 2 | Swift by Sundell](https://www.swiftbysundell.com/articles/building-a-declarative-animation-framework-in-swift-part-2)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Compose declarative animations with sequence tokens that coordinate multiple views while preserving completion and cancellation semantics. A top-level API can make usage readable, but tokens must retain enough state to prevent overlapping sequences from finishing incorrectly.
- [Building a command line tool using the Swift Package Manager | Swift by Sundell](https://www.swiftbysundell.com/articles/building-a-command-line-tool-using-the-swift-package-manager)
  **Published:** `2021-10-30`
  **Topics:** Dependency Injection · Swift · Swift Package Manager · Testing · Xcode
  **NeKI brief:** Structure a Swift command-line tool as an executable target plus reusable library code, then define the entry point, arguments, dependencies, and installation path through Swift Package Manager. This separation keeps command parsing from consuming application logic.
- [Bindable values in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/bindable-values-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Observation & State Management · Swift
  **NeKI brief:** A bindable value connects model changes to UI updates and can transform values at the binding boundary. Define ownership and cancellation explicitly so automatic observation does not retain views or silently deliver changes after the consumer is gone.
- [Bindable SwiftUI list elements | Swift by Sundell](https://www.swiftbysundell.com/articles/bindable-swiftui-list-elements)
  **Published:** `2021-10-30`
  **Topics:** Observation & State Management · Swift · SwiftUI · Xcode
  **NeKI brief:** Create two-way bindings to collection elements by preserving stable identity and deriving each element binding from the collection's source of truth. Prefer SwiftUI's newer element-binding syntax when available; custom index bindings need careful mutation handling.
- [Avoiding having to recompute values within SwiftUI views | Swift by Sundell](https://www.swiftbysundell.com/articles/avoiding-swiftui-value-recomputation)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI · UIKit
  **NeKI brief:** Move expensive derived values out of SwiftUI body computation by initializing stable state from inputs or placing model logic in a dedicated type. Recompute only when the real source changes, while keeping view identity and update semantics correct.
- [Avoiding singletons in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/avoiding-singletons-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Architecture · Dependency Injection · Swift
  **NeKI brief:** Replace global singletons with injected services whose dependencies and lifetime are visible to callers. This makes tests substitute behavior directly and prevents unrelated features from sharing mutable global state through an apparently convenient API.
- [Avoiding race conditions in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/avoiding-race-conditions-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Avoid races by serializing access to shared pending handlers and defining when each completion becomes eligible to run. Thread safety is not only locking: operation ordering and cancellation ownership must be explicit so callbacks cannot observe half-updated state.
- [Avoiding problematic cases when using Swift enums | Swift by Sundell](https://www.swiftbysundell.com/articles/avoiding-problematic-enum-cases-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Use enums for closed domains with stable cases, not as a catch-all for absence, arbitrary identifiers, or open-ended data. Model those concerns with optional values, custom types, or static properties so exhaustiveness remains meaningful.
- [Avoiding massive SwiftUI views | Swift by Sundell](https://www.swiftbysundell.com/articles/avoiding-massive-swiftui-views)
  **Published:** `2021-10-30`
  **Topics:** Architecture · Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Discusses decomposing large SwiftUI views by extracting stateful responsibilities and reusable subviews. Use it when a body becomes difficult to reason about and architectural boundaries should improve testability without arbitrary file splitting.
- [Avoiding force unwrapping in Swift unit tests | Swift by Sundell](https://www.swiftbysundell.com/articles/avoiding-force-unwrapping-in-swift-unit-tests)
  **Published:** `2021-10-30`
  **Topics:** Swift · Testing
  **NeKI brief:** Tests can unwrap values with guard plus XCTFail, throwing helpers, or required-option APIs instead of force unwraps. Preserve a useful failure message and source location; a crash loses the context needed to distinguish broken setup from failed behavior.
- [Avoiding deeply nested Swift code | Swift by Sundell](https://www.swiftbysundell.com/articles/avoiding-deeply-nested-swift-code)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI · Testing
  **NeKI brief:** Reduce Swift nesting with guard-based early exits, extracted helpers, and explicit intermediate decisions. Flattening should expose the success path, not split one cohesive operation into fragments that hide shared preconditions or make error handling harder to follow.
- [Avoiding SwiftUI’s AnyView | Swift by Sundell](https://www.swiftbysundell.com/articles/avoiding-anyview-in-swiftui)
  **Published:** `2021-10-30`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Explains why AnyView can erase structural information SwiftUI uses for efficient updates. Use it when conditional composition seems to require erasure and a generic or ViewBuilder-based structure may preserve identity.
- [Async sequences, streams, and Combine | Swift by Sundell](https://www.swiftbysundell.com/articles/async-sequences-streams-and-combine)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift
  **NeKI brief:** AsyncSequence models values arriving over time; AsyncStream bridges callback-based producers into that iteration model. Compare it with Combine by cancellation, back-pressure, and transformation needs, rather than wrapping every publisher merely to adopt async/await syntax.
- [Alternatives to protocols in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/alternatives-to-protocols-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Protocols are not the only Swift abstraction: closures suit single behavior, generics retain type information, enums model finite choices, and classes express identity inheritance. Select the smallest construct that matches variation and ownership instead of creating broad protocols reflexively.
- [Adding Continuous Integration to a Swift project | Swift by Sundell](https://www.swiftbysundell.com/articles/adding-continuous-integration-to-a-swift-project)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Introduce CI by selecting a service that matches the repository, build environment, and team workflow, then make tests and build feedback automatic. A useful pipeline verifies every integration change rather than becoming a separate manual release ritual.
- [Accessing a Swift property wrapper’s enclosing instance | Swift by Sundell](https://www.swiftbysundell.com/articles/accessing-a-swift-property-wrappers-enclosing-instance)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** A property wrapper can use its enclosing instance through the static subscript mechanism to coordinate wrapper behavior with owner state. Reserve this advanced feature for clear ownership cases, since it makes wrapper access more indirect than ordinary value storage.
- [A deep dive into Grand Central Dispatch in Swift | Swift by Sundell](https://www.swiftbysundell.com/articles/a-deep-dive-into-grand-central-dispatch-in-swift)
  **Published:** `2021-10-30`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Use DispatchWorkItem for cancellable delays, DispatchGroup for task coordination, semaphores only for carefully bounded waiting, and DispatchSource for event observation. Choose the GCD primitive from cancellation and ownership needs rather than treating async as one operation.
- [5 small but significant improvements in Swift 5.1 | Swift by Sundell](https://www.swiftbysundell.com/articles/5-small-but-significant-improvements-in-swift-5-1)
  **Published:** `2021-10-30`
  **Topics:** Swift
  **NeKI brief:** Highlights several small Swift 5.1 language improvements and their practical effects. Use it for historical migration review and verify each feature's availability in the project toolchain.
