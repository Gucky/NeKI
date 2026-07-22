# objc.io

Third-party source index. It provides source attribution and routing metadata, not republished article content. Verify article conclusions independently before applying them.

- Archive: [https://www.objc.io/blog/archive](https://www.objc.io/blog/archive)
- Last collected: `2026-07-22T21:58:56Z`
- Indexed entries: **92**

- [Transitions in SwiftUI · objc.io](https://www.objc.io/blog/2022/04/14/transitions)
  **Published:** `2022-4-14`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Explores SwiftUI transitions as insertion and removal effects, including how asymmetric transitions and view identity shape the result. It is a useful mental model when animations appear to run on the wrong lifecycle edge.
- [Aspect Ratios in SwiftUI · objc.io](https://www.objc.io/blog/2022/03/29/aspectratio)
  **Published:** `2022-3-29`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI aspect-ratio layout behavior and the interaction between proposed size, content mode, and container constraints. Follow it when a view's dimensions differ from an apparently equivalent frame calculation.
- [Why Conditional View Modifiers are a Bad Idea · objc.io](https://www.objc.io/blog/2021/08/24/conditional-view-modifiers)
  **Published:** `2021-8-24`
  **Topics:** SwiftUI
  **NeKI brief:** Shows why conditionally applying modifiers can change view identity and produce surprising layout or state behavior. The alternatives make the trade-off between type-safe composition and stable runtime structure explicit.
- [Transactions and Animations · objc.io](https://www.objc.io/blog/2021/11/25/transactions-and-animations)
  **Published:** `2021-11-25`
  **Topics:** SwiftUI
  **NeKI brief:** Explains SwiftUI transactions as the mechanism carrying animation decisions through a view update, rather than treating animation as a property of one modifier. The examples help localize or disable animations without disrupting unrelated state changes.
- [A Fast Fuzzy Search Implementation · objc.io](https://www.objc.io/blog/2020/08/18/fuzzy-search)
  **Published:** `2020-8-18`
  **Topics:** Performance
  **NeKI brief:** Builds a fuzzy-search scorer that tolerates gaps and ordering differences while ranking stronger matches higher. The implementation is a useful baseline for command palettes or symbol search where substring matching is too strict.
- [SwiftUI: Running a Mac App Without an Xcode Project · objc.io](https://www.objc.io/blog/2020/05/19/swiftui-without-an-xcodeproj)
  **Published:** `2020-5-19`
  **Topics:** Swift · SwiftUI · Xcode
  **NeKI brief:** Shows how to run a SwiftUI macOS app directly from Swift Package Manager without an Xcode project. The setup clarifies which package targets and resources are needed when keeping a small executable workflow.
- [SwiftUI: Showing an Alert with a Text Field · objc.io](https://www.objc.io/blog/2020/04/21/swiftui-alert-with-textfield)
  **Published:** `2020-4-21`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Composes a SwiftUI alert containing a text field by bridging to UIKit presentation behavior. Follow it for the lifecycle and focus caveats involved when standard alert APIs do not expose editable content.
- [SwiftUI Alignment Guides · objc.io](https://www.objc.io/blog/2020/03/05/swiftui-alignment-guides)
  **Published:** `2020-3-5`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Demonstrates custom SwiftUI alignment guides to line up views across nested containers without hard-coded offsets. The examples make guide resolution and parent-child coordinate relationships concrete.
- [SwiftUI Line Graph Animation · objc.io](https://www.objc.io/blog/2020/03/16/swiftui-line-graph-animation)
  **Published:** `2020-3-16`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** The line-graph challenge animates a shape's changing path rather than swapping snapshots, so SwiftUI interpolates geometry between states. The workflow exposes how data normalization and `Shape` identity affect whether an animation looks continuous.
- [SwiftUI Path Animations · objc.io](https://www.objc.io/blog/2020/03/10/swiftui-path-animations)
  **Published:** `2020-3-10`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Animating a SwiftUI path requires keeping the same shape identity while its path parameters change; otherwise the framework has no geometry to interpolate. The example is a practical test for separating drawing data from view-state transitions.
- [New Book: Thinking in SwiftUI · objc.io](https://www.objc.io/blog/2020/02/03/thinking-in-swiftui)
  **Published:** `2020-2-3`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Frames SwiftUI around value semantics, state propagation, and declarative descriptions rather than imperative view mutation. Use it when a UIKit mental model produces identity or update bugs in a SwiftUI architecture.
- [SwiftUI Tab Bar · objc.io](https://www.objc.io/blog/2020/02/25/swiftui-tab-bar)
  **Published:** `2020-2-25`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** The custom tab bar challenge builds an animated selection indicator instead of relying on the system tab container. It demonstrates coordinating matched geometry, selection state, and hit targets while retaining a clear accessibility model.
- [A Signal Strength Indicator · objc.io](https://www.objc.io/blog/2020/02/18/a-signal-strength-indicator)
  **Published:** `2020-2-18`
  **Topics:** Developer Community & Business
  **NeKI brief:** The signal indicator challenge derives a variable number of bars from a scalar value and animates their visual state. It demonstrates separating normalized data from shape layout so the component scales without hard-coded geometry.
- [SwiftUI Challenge #1 · objc.io](https://www.objc.io/blog/2020/02/11/swiftui-challenge-1)
  **Published:** `2020-2-11`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** The first SwiftUI challenge establishes a repeatable workflow: model selection as state, compose primitive views, then animate only the indicator that changes. That decomposition keeps interaction logic independent from the decorative layout.
- [SwiftUI Layout Explained: Free to watch! · objc.io](https://www.objc.io/blog/2020/12/24/swiftui-layout-explained)
  **Published:** `2020-12-24`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** SwiftUI layout is a proposal-response protocol: parents suggest a size, children choose within it, and parents place the result. The explanation is a diagnostic tool for distinguishing sizing bugs from alignment or drawing issues.
- [SwiftUI's Grid Views · objc.io](https://www.objc.io/blog/2020/11/23/grid-layout)
  **Published:** `2020-11-23`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Uses layout quizzes to derive LazyVGrid behavior for fixed and adaptive columns, spacing, and proposed sizes. The concrete counterexamples help when a grid’s apparent sizing rules differ from an intuitive row-and-column model.
- [How an Hstack Lays out Its Children · objc.io](https://www.objc.io/blog/2020/11/10/hstacks-child-ordering)
  **Published:** `2020-11-10`
  **Topics:** SwiftUI
  **NeKI brief:** HStack layout is determined by proposed sizes, priorities, and child order, not simply by the order of pixels seen on screen. The investigation gives a diagnostic workflow for surprising truncation and explains when changing layout priority is the right fix.
- [SwiftUI: Animating Timing Curves · objc.io](https://www.objc.io/blog/2019/09/26/swiftui-animation-timing-curves)
  **Published:** `2019-9-26`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Derives SwiftUI timing curves from interpolation functions and shows how cubic Bézier control points shape motion. Use it to choose or tune custom easing when preset easeIn, easeOut, or spring behavior is unsuitable.
- [Animating Explicit Changes · objc.io](https://www.objc.io/blog/2019/09/17/animating-explicit-changes)
  **Published:** `2019-9-17`
  **Topics:** Personal Essays
  **NeKI brief:** Explicit animation scopes a state mutation so only the intended transition participates, avoiding accidental animation of unrelated updates. The article contrasts transaction placement and demonstrates why animation belongs near the decision that changes state.
- [Defunctionalization · objc.io](https://www.objc.io/blog/2019/09/10/defunctionalization)
  **Published:** `2019-9-10`
  **Topics:** Swift
  **NeKI brief:** Defunctionalization turns a collection of closures into an explicit enum of operations plus an interpreter. That trade-off makes behavior inspectable and serializable, at the cost of adding a data model and dispatch layer.
- [Removing Dependencies · objc.io](https://www.objc.io/blog/2019/08/06/removing-dependencies)
  **Published:** `2019-8-6`
  **Topics:** Dependency Injection
  **NeKI brief:** Removing dependencies from a Swift module starts by identifying which abstractions actually cross its boundary, then replacing incidental imports with narrower interfaces. The article frames compile-time isolation as a deliberate architecture trade-off, not a blanket ban on libraries.
- [SwiftUI: Paths vs. Shapes · objc.io](https://www.objc.io/blog/2019/08/20/paths-vs-shapes)
  **Published:** `2019-8-20`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** A SwiftUI `Path` is immediate drawing data, while a `Shape` is a reusable, animatable description that receives a proposed rectangle. Choosing between them determines whether geometry can be parameterized, animated, and composed as a view.
- [Conforming Tuples to Protocols · objc.io](https://www.objc.io/blog/2019/08/13/conforming-tuples-to-protocols)
  **Published:** `2019-8-13`
  **Topics:** SwiftUI
  **NeKI brief:** Tuple protocol conformance is unavailable directly, so generic code must wrap tuple values or introduce a dedicated type. The discussion exposes a language limitation and the readability-versus-flexibility trade-off of each workaround.
- [Swift Quiz in Review · objc.io](https://www.objc.io/blog/2019/07/30/swift-quiz-review)
  **Published:** `2019-7-30`
  **Topics:** Swift
  **NeKI brief:** Reviews answers and lessons from a Swift quiz, turning common language misunderstandings into discussion points. Use it for team learning and verify rules against current Swift documentation.
- [SwiftUI: Loading Data on Demand · objc.io](https://www.objc.io/blog/2019/07/02/lazy-loading)
  **Published:** `2019-7-2`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** SwiftUI's lazy containers defer child construction until items approach the visible region, reducing upfront work for large collections. The article also surfaces the trade-off: identity and measurement must remain stable as views are created incrementally.
- [Swift Tip: Sharing Code between Backend and Frontend · objc.io](https://www.objc.io/blog/2019/07/16/sharing-code)
  **Published:** `2019-7-16`
  **Topics:** Swift
  **NeKI brief:** Sharing Swift code between backend and frontend works best when the common module avoids platform-specific imports and models only transferable behavior. The article treats package boundaries and conditional compilation as the cost of reuse.
- [SwiftUI: Loading Data Asynchronously · objc.io](https://www.objc.io/blog/2019/06/25/swiftui-data-loading)
  **Published:** `2019-6-25`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Asynchronous SwiftUI loading separates a view's initial, loading, success, and failure states instead of mutating UI from a callback. The pattern makes cancellation and repeated loads visible, which is safer than an implicit one-shot side effect.
- [Swift Tip: Enums vs. Protocols · objc.io](https://www.objc.io/blog/2019/05/07/enums-vs-protocols)
  **Published:** `2019-5-7`
  **Topics:** Swift
  **NeKI brief:** Enums centralize a closed set of cases, while protocols permit independent conformances and extension by other modules. The comparison is a design decision about exhaustiveness, binary evolution, and where behavior should be dispatched.
- [Swift Tip: Wrapper Functions · objc.io](https://www.objc.io/blog/2019/05/28/wrapper-functions)
  **Published:** `2019-5-28`
  **Topics:** Swift
  **NeKI brief:** Wrapper functions can give a higher-level API a stable name while adapting argument labels, defaults, or effects. The article weighs that readability against another layer of indirection and the risk of hiding important semantics.
- [Swift Tip: Protocols vs. Values · objc.io](https://www.objc.io/blog/2019/05/14/protocols-vs-values)
  **Published:** `2019-5-14`
  **Topics:** Swift
  **NeKI brief:** Modeling behavior with protocol values enables substitution, while concrete values preserve discoverability and compiler specialization. The discussion helps choose the boundary deliberately instead of introducing existential storage for every abstraction.
- [Swift Tip: Reading from Standard Input/Output · objc.io](https://www.objc.io/blog/2019/04/30/reading-from-standard-input-output)
  **Published:** `2019-4-30`
  **Topics:** Swift
  **NeKI brief:** Swift command-line programs can read stdin and write stdout through Foundation or standard-library streams, enabling Unix pipeline composition. The article keeps terminal I/O separate from domain processing so the same logic remains testable.
- [Swift Tip: Exhaustive Switching with Enums · objc.io](https://www.objc.io/blog/2019/04/02/exhaustive-switching-with-enums)
  **Published:** `2019-4-2`
  **Topics:** Swift
  **NeKI brief:** An exhaustive enum switch makes the compiler enumerate every state and turns a new case into a migration task. The tip contrasts that safety with a default branch, which can hide behavior changes during model evolution.
- [Swift Tip: Unicode Scalar Properties · objc.io](https://www.objc.io/blog/2019/04/10/unicode-scalar-properties)
  **Published:** `2019-4-10`
  **Topics:** Swift
  **NeKI brief:** Unicode scalar properties let code classify characters by semantic categories instead of assuming ASCII ranges. The approach prevents incorrect validation and cursor behavior when user input includes composed or non-Latin text.
- [Swift Tip: Generics vs. Any · objc.io](https://www.objc.io/blog/2019/03/05/generics-vs-any)
  **Published:** `2019-3-5`
  **Topics:** Swift
  **NeKI brief:** Generics preserve static relationships between inputs and outputs, while `Any` erases them and shifts failures to runtime casts. The comparison helps decide whether an abstraction needs heterogeneous storage or merely a generic constraint.
- [Swift Tip: Collection Protocols · objc.io](https://www.objc.io/blog/2019/03/26/collection-protocols)
  **Published:** `2019-3-26`
  **Topics:** Swift
  **NeKI brief:** Collection protocols expose progressively stronger guarantees about indexing, traversal, and mutation. Choosing the narrowest protocol keeps algorithms reusable while avoiding assumptions that only Array or RandomAccessCollection can satisfy.
- [Wrapping Third Party APIs · objc.io](https://www.objc.io/blog/2019/03/19/wrapping-third-party-apis)
  **Published:** `2019-3-19`
  **Topics:** Networking
  **NeKI brief:** Wrapping a third-party API behind a local protocol isolates vendor types, error semantics, and replacement cost from the application. The boundary improves testing, but adds an adapter that must track upstream behavior deliberately.
- [Swift Tip: An NSScanner Alternative · objc.io](https://www.objc.io/blog/2019/02/05/a-scanner-alternative)
  **Published:** `2019-2-5`
  **Topics:** Swift
  **NeKI brief:** A Swift scanner can parse structured text by moving an index through a collection rather than relying on NSScanner. Use it for type-safe parsing, with explicit bounds and failure handling for malformed input.
- [Swift Tip: From Optionals to Errors · objc.io](https://www.objc.io/blog/2019/02/26/from-optionals-to-errors)
  **Published:** `2019-2-26`
  **Topics:** Swift
  **NeKI brief:** Replacing an optional result with a thrown error preserves why an operation failed. Use typed domain errors when callers need recovery or diagnostics, while retaining optionals for ordinary absence that requires no explanation.
- [Open-Sourcing The Swift Talk Backend · objc.io](https://www.objc.io/blog/2019/02/12/open-sourcing-the-swift-talk-backend)
  **Published:** `2019-2-12`
  **Topics:** Swift
  **NeKI brief:** The Swift Talk backend rewrite replaces Rails with a SwiftNIO-based service using six direct dependencies and no web framework. Follow it for a concrete server-side Swift dependency boundary and an openly inspectable Docker deployment.
- [Drawing Trees in SwiftUI · objc.io](https://www.objc.io/blog/2019/12/16/drawing-trees)
  **Published:** `2019-12-16`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** A recursive SwiftUI tree view renders hierarchical data by letting each node create its children. Use stable node identity and a clear expansion model, avoiding recursion that makes large trees hard to update efficiently.
- [Static Types in SwiftUI · objc.io](https://www.objc.io/blog/2019/11/05/static-types-in-swiftui)
  **Published:** `2019-11-5`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** SwiftUI's static view types enable composition and compiler checking, even though conditional UI can appear dynamic. Use small typed branches and view builders, avoiding unnecessary type erasure that conceals structure and costs performance.
- [SwiftUI: Setting Environment Values · objc.io](https://www.objc.io/blog/2019/10/29/swiftui-environment)
  **Published:** `2019-10-29`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Inspects SwiftUI’s generated view types to show how environment values travel through modified views and wrapper boundaries. It clarifies the mechanics behind custom environment keys and why modifier placement affects descendants.
- [SwiftUI: Shake Animation · objc.io](https://www.objc.io/blog/2019/10/01/swiftui-shake-animation)
  **Published:** `2019-10-1`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** A shake effect can be expressed as an animatable SwiftUI modifier driven by a changing value. Use it for concise feedback on invalid input, preserving motion preferences and not relying on animation as the only error signal.
- [Swift Tip: Non-Empty Collections · objc.io](https://www.objc.io/blog/2019/01/29/non-empty-collections)
  **Published:** `2019-1-29`
  **Topics:** Swift
  **NeKI brief:** A non-empty collection wrapper moves an important precondition into the type system. Use it where algorithms require a first element, providing ergonomic construction and conversion back to ordinary collections when needed.
- [Swift Tip: Non-Empty Optionals · objc.io](https://www.objc.io/blog/2019/01/22/non-empty-optionals)
  **Published:** `2019-1-22`
  **Topics:** Swift
  **NeKI brief:** A non-empty optional abstraction distinguishes an absent value from an optional whose wrapped value must be meaningful. Use it sparingly for domain invariants, because custom wrappers can complicate otherwise familiar optional handling.
- [Swift Tip: Atomic Variables — Part 2 · objc.io](https://www.objc.io/blog/2019/01/15/atomic-variables-part-2)
  **Published:** `2019-1-15`
  **Topics:** Swift
  **NeKI brief:** Atomic access must define the read-modify-write operation as one synchronization boundary, not merely protect independent reads and writes. Use a lock or dedicated primitive with carefully scoped invariants, avoiding false thread-safety claims.
- [Swift Tip: Switching with Associated Values · objc.io](https://www.objc.io/blog/2018/09/04/switching-with-associated-values)
  **Published:** `2018-9-4`
  **Topics:** Swift
  **NeKI brief:** Pattern matching associated enum values lets a switch branch on both case and payload shape. Use precise patterns to keep state handling exhaustive, extracting shared logic only after the meaningful distinctions remain visible.
- [Swift Tip: Mixing and Matching Imperative and Functional Code · objc.io](https://www.objc.io/blog/2018/09/18/imperative-or-functional)
  **Published:** `2018-9-18`
  **Topics:** Swift
  **NeKI brief:** Swift can mix functional transformations with imperative steps instead of treating them as competing styles. Use the form that makes data flow and mutation clearest, keeping side effects at intentional boundaries.
- [Building a Form Library · objc.io](https://www.objc.io/blog/2018/09/11/building-a-form-library)
  **Published:** `2018-9-11`
  **Topics:** SwiftUI
  **NeKI brief:** Summarizes a declarative UIKit form library whose model and controls stay synchronized, including dependent fields such as a personal-hotspot toggle. Useful for evaluating data-flow design in reusable form components.
- [Swift Tip: Testing Swift on Linux · objc.io](https://www.objc.io/blog/2018/08/28/testing-swift-on-linux)
  **Published:** `2018-8-28`
  **Topics:** Swift · Testing
  **NeKI brief:** Linux test execution exposes assumptions about Apple-only frameworks, paths and toolchains. Use it to keep a Swift package portable, separating platform adapters from core behavior and running the intended Swift version in CI.
- [Swift Tip: Notifications · objc.io](https://www.objc.io/blog/2018/07/03/notifications)
  **Published:** `2018-7-3`
  **Topics:** Swift
  **NeKI brief:** Notifications broadcast events without requiring the sender to know observers. Use them for genuinely decoupled fan-out, but document payloads and lifetime management so they do not become invisible control flow.
- [Swift Tip: Improving Readability · objc.io](https://www.objc.io/blog/2018/07/10/improving-readability)
  **Published:** `2018-7-10`
  **Topics:** Swift
  **NeKI brief:** Small extraction and naming choices can make Swift expressions reveal their intent before their mechanics. Use local types and helpers to explain domain concepts, without splitting straightforward code into needless indirection.
- [Swift Tip: Extracting Pure Functions · objc.io](https://www.objc.io/blog/2018/06/05/extracting-pure-functions)
  **Published:** `2018-6-5`
  **Topics:** Swift
  **NeKI brief:** Extracting a pure function isolates deterministic transformation from I/O and mutable context. Use it to reduce test setup and clarify invariants, passing dependencies explicitly instead of reaching into ambient state.
- [Swift Tip: Refactoring with Deprecations · objc.io](https://www.objc.io/blog/2018/06/26/refactoring-with-deprecations)
  **Published:** `2018-6-26`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Deprecation attributes let an API migration guide callers toward replacements while preserving a transition period. Use clear messages and forwarding implementations, removing the old path only after downstream adoption is measurable.
- [Swift Tip: Separating UI and Model Code · objc.io](https://www.objc.io/blog/2018/06/19/separating-ui-and-model-code)
  **Published:** `2018-6-19`
  **Topics:** Swift
  **NeKI brief:** Separating UI code from model transformations keeps rendering concerns from driving business rules. Use narrow inputs and outputs between layers, so model tests do not require views and UI changes do not rewrite logic.
- [Swift Tip: Quick Performance Timing · objc.io](https://www.objc.io/blog/2018/06/14/quick-performance-timing)
  **Published:** `2018-6-14`
  **Topics:** Performance · Swift
  **NeKI brief:** Lightweight timing around a focused operation can expose unexpected performance regressions before profiling. Use repeatable inputs and release-like conditions, treating elapsed time as a signal to investigate rather than a precise benchmark.
- [Swift Tip: First Class Functions · objc.io](https://www.objc.io/blog/2018/05/08/first-class-functions)
  **Published:** `2018-5-8`
  **Topics:** Swift
  **NeKI brief:** Functions as values can express configurable behavior without creating one-off protocol hierarchies. Use closures for small local variation, promoting them to named types when ownership, identity or complex composition needs stronger structure.
- [Swift Tip: Type-Safe Initialization Using Storyboards (Part 2) · objc.io](https://www.objc.io/blog/2018/05/29/type-safe-initialization-using-storyboards-2)
  **Published:** `2018-5-29`
  **Topics:** Swift
  **NeKI brief:** A typed storyboard factory can replace stringly identifiers and late casting with compile-time checked construction. Use it in legacy UIKit interfaces, keeping the wrapper close to storyboard ownership so navigation remains discoverable.
- [Swift Tip: Type-Safe Initialization using Storyboards (Part 1) · objc.io](https://www.objc.io/blog/2018/05/22/type-safe-initialization-using-storyboards)
  **Published:** `2018-5-22`
  **Topics:** Swift
  **NeKI brief:** Replaces stringly typed storyboard segues with typed initialization and configuration, moving missing-context failures closer to compile time. The pattern is useful when maintaining storyboard navigation without scattering prepare(for:) casts.
- [Swift Tip: Extracting Parameters · objc.io](https://www.objc.io/blog/2018/05/01/extracting-parameters)
  **Published:** `2018-5-1`
  **Topics:** Swift
  **NeKI brief:** Extracting related parameters into a value type reduces long call signatures and gives concepts a name. Use it when fields travel together or have shared validation, not merely to hide a method's complexity.
- [Swift Tip: Capture Lists · objc.io](https://www.objc.io/blog/2018/04/03/caputure-lists)
  **Published:** `2018-4-3`
  **Topics:** Swift
  **NeKI brief:** Uses a KVO callback to contrast weak and unowned capture lists, tying the choice to object lifetime guarantees and retain-cycle avoidance. The example is a compact reference for auditing closure ownership in UIKit code.
- [Swift Tip: Bindings with KVO and Key Paths · objc.io](https://www.objc.io/blog/2018/04/24/bindings-with-kvo-and-keypaths)
  **Published:** `2018-4-24`
  **Topics:** Observation & State Management · Swift
  **NeKI brief:** Key paths and KVO can create bindings between compatible observable properties in Cocoa code. Use explicit observation lifetime and threading rules, and prefer modern observation mechanisms where deployment targets permit them.
- [Swift Tip: In-Place Map · objc.io](https://www.objc.io/blog/2018/04/17/map-in-place)
  **Published:** `2018-4-17`
  **Topics:** Swift
  **NeKI brief:** An in-place map transforms mutable collection elements without allocating a second collection. Use it when mutation is intended and memory matters, but preserve value semantics expectations and avoid modifying while iterating invalid indices.
- [Swift Tip: Local Computed Variables · objc.io](https://www.objc.io/blog/2018/04/10/local-vars)
  **Published:** `2018-4-10`
  **Topics:** Swift
  **NeKI brief:** Local computed variables can name intermediate calculations and reduce repeated expressions. Use them to expose a decision's parts, maintaining a short scope so readers do not need to search for their derivation.
- [Swift Tip: Without Actually Escaping · objc.io](https://www.objc.io/blog/2018/03/06/without-actually-escaping)
  **Published:** `2018-3-6`
  **Topics:** Swift
  **NeKI brief:** withoutActuallyEscaping temporarily adapts a non-escaping closure to an API that requires escaping syntax. Use it only when the called API cannot retain the closure, because violating that guarantee traps at runtime.
- [Swift Tip: Unwrapping Optionals · objc.io](https://www.objc.io/blog/2018/03/27/unwrapping-optionals)
  **Published:** `2018-3-27`
  **Topics:** Swift
  **NeKI brief:** Optional unwrapping should make the absent case explicit at the point its meaning is known. Use guard for early exits and if-let for local branches, avoiding force unwraps except under proven invariants.
- [Swift Tip: Lazy Infinite Sequences · objc.io](https://www.objc.io/blog/2018/03/20/lazy-infinite-sequences)
  **Published:** `2018-3-20`
  **Topics:** Swift
  **NeKI brief:** Lazy sequences can model unbounded generated values while only evaluating what a consumer requests. Use them for pipelines with a natural stopping condition, avoiding accidental full traversal that never terminates.
- [Swift Tip: Enum Initializers · objc.io](https://www.objc.io/blog/2018/03/13/mutable-self)
  **Published:** `2018-3-13`
  **Topics:** Swift
  **NeKI brief:** An enum initializer can assign self to select a final case after validating input. Use this to preserve enum invariants during construction, keeping parsing and fallback policy explicit for invalid source values.
- [Swift Tip: Networking with Codable · objc.io](https://www.objc.io/blog/2018/02/06/networking-with-codable)
  **Published:** `2018-2-6`
  **Topics:** Networking · Swift
  **NeKI brief:** Codable can decode network payloads directly into domain-adjacent Swift types. Use dedicated transport models when wire formats are unstable, mapping and validating at the boundary rather than leaking decoding details across the app.
- [Swift Tip: Extensible Libraries with Protocols · objc.io](https://www.objc.io/blog/2018/02/27/extensible-libraries-with-protocols)
  **Published:** `2018-2-27`
  **Topics:** Swift
  **NeKI brief:** Protocols let a library accept new behavior without knowing every concrete type in advance. Use focused requirements and default implementations carefully, because overly broad protocols become difficult to evolve compatibly.
- [Swift Tip: Enums vs Classes · objc.io](https://www.objc.io/blog/2018/02/20/enums-vs-classes)
  **Published:** `2018-2-20`
  **Topics:** Swift
  **NeKI brief:** Enums represent a closed set of states, while classes suit identity, lifecycle and open polymorphism. Choose based on domain semantics first, not anticipated inheritance or a preference for reference types.
- [Swift Tip: String to Data and Back · objc.io](https://www.objc.io/blog/2018/02/13/string-to-data-and-back)
  **Published:** `2018-2-13`
  **Topics:** Swift
  **NeKI brief:** Shows why UTF-8 and other Unicode encodings can be safely converted from String while ASCII conversion can fail for characters such as emoji. Use it to avoid unjustified force unwraps around String-to-Data conversion.
- [Swift Tip: Unexpected Results from a Date Formatter · objc.io](https://www.objc.io/blog/2018/12/04/unexpected-results-from-a-date-formatter)
  **Published:** `2018-12-4`
  **Topics:** Swift
  **NeKI brief:** DateFormatter behavior depends on locale, calendar, time zone and its mutable configuration. Use fixed POSIX settings for machine formats and user locale settings for display, never relying on defaults for protocol data.
- [Swift Tip: Atomic Variables · objc.io](https://www.objc.io/blog/2018/12/18/atomic-variables)
  **Published:** `2018-12-18`
  **Topics:** Swift
  **NeKI brief:** An atomic variable protects a simple shared access pattern, but does not automatically make a larger workflow safe. Use synchronization around the invariant's full operation and document which thread owns higher-level coordination.
- [Swift Tip: Stable APIs on the Server · objc.io](https://www.objc.io/blog/2018/12/13/stable-apis-on-the-server)
  **Published:** `2018-12-13`
  **Topics:** Swift
  **NeKI brief:** A server API needs evolution rules for clients that update independently. Use additive changes, explicit versions and compatibility tests, avoiding changes to response meaning that compile successfully but break deployed consumers.
- [Swift Tip: Lightweight Observation · objc.io](https://www.objc.io/blog/2018/11/06/lightweight-observation)
  **Published:** `2018-11-6`
  **Topics:** Swift
  **NeKI brief:** A lightweight observation helper can connect change notifications to a focused callback without building a full reactive system. Use clear cancellation ownership and delivery rules, preventing observers from outliving the object they update.
- [Swift Tip: Vector Algebra with Protocols · objc.io](https://www.objc.io/blog/2018/11/29/vector-calculus-with-protocols)
  **Published:** `2018-11-29`
  **Topics:** Swift
  **NeKI brief:** Protocol-based vector operations express shared algebra over multiple numeric representations. Use generic constraints to capture the operations an algorithm actually needs, avoiding abstractions that hide numerical precision and performance trade-offs.
- [Swift Tip: Local Struct Definitions · objc.io](https://www.objc.io/blog/2018/11/20/local-structs)
  **Published:** `2018-11-20`
  **Topics:** Swift
  **NeKI brief:** A local struct can package temporary related data without widening a module's API surface. Use it to name a short-lived transformation, keeping the type near its use rather than creating an artificial shared model.
- [Swift Tip: Custom Views Without Subclassing · objc.io](https://www.objc.io/blog/2018/11/13/subclassing-alternatives)
  **Published:** `2018-11-13`
  **Topics:** Swift
  **NeKI brief:** Builds UIKit custom views through convenience initializers, composition, and local extensions instead of subclassing for every shared property. It provides a practical boundary for deciding when reuse needs inheritance and when configuration is enough.
- [Swift Tip: Auto Layout with Key Paths · objc.io](https://www.objc.io/blog/2018/10/30/auto-layout-with-key-paths)
  **Published:** `2018-10-30`
  **Topics:** Swift
  **NeKI brief:** Key paths can describe an Auto Layout attribute connection more safely than separate string-like selectors. Use a typed helper to reduce repeated constraint boilerplate, preserving explicit priority and activation decisions.
- [Swift Tip: Custom Types for Codable Conformance · objc.io](https://www.objc.io/blog/2018/10/23/custom-types-for-codable)
  **Published:** `2018-10-23`
  **Topics:** Swift
  **NeKI brief:** Custom Codable implementations translate between a wire representation and a richer Swift domain type. Use them for validation, legacy formats or semantic conversions, keeping decoding errors precise and encoding behavior symmetrical.
- [Swift Tip: Using AppKit from the Command-line · objc.io](https://www.objc.io/blog/2018/10/02/using-appkit-from-the-command-line)
  **Published:** `2018-10-2`
  **Topics:** Swift
  **NeKI brief:** A command-line Swift tool can load selected AppKit facilities when it needs macOS system services. Use this boundary deliberately, handling run-loop and entitlement requirements instead of assuming a GUI application lifecycle.
- [Swift Tip: An Example Refactoring · objc.io](https://www.objc.io/blog/2018/10/18/an-example-refactoring)
  **Published:** `2018-10-18`
  **Topics:** Concurrency · Swift
  **NeKI brief:** A small refactoring example demonstrates changing structure while preserving observable behavior. Use incremental tests and compiler guidance to make each step safe, resisting broad rewrites that combine unrelated design decisions.
- [Swift Tip: Refactoring to Associated Values · objc.io](https://www.objc.io/blog/2018/10/11/refactoring-to-associated-values)
  **Published:** `2018-10-11`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Associated enum values can replace parallel fields and invalid case combinations with one typed state model. Use the refactor when each case has distinct required data, preserving exhaustive handling at all consumers.
- [Swift Tip: A Functional Interface for Imperative Code · objc.io](https://www.objc.io/blog/2018/01/09/justified-flow-layout)
  **Published:** `2018-1-9`
  **Topics:** Swift
  **NeKI brief:** A functional facade over imperative layout code can make configuration and transformation easier to reason about. Use it to isolate mutable mechanics behind a narrow API, retaining profiling for performance-sensitive collection layouts.
- [Swift Tip: OpaquePointer vs. UnsafePointer · objc.io](https://www.objc.io/blog/2018/01/30/opaque-vs-unsafe-pointers)
  **Published:** `2018-1-30`
  **Topics:** Swift
  **NeKI brief:** OpaquePointer hides an unknown C pointee type, whereas UnsafePointer carries an element type. Use the least permissive pointer representation at interop boundaries, maintaining lifetime and mutability guarantees explicitly.
- [Swift Tip: Codable Enums · objc.io](https://www.objc.io/blog/2018/01/23/codable-enums)
  **Published:** `2018-1-23`
  **Topics:** Swift
  **NeKI brief:** Codable enums need an intentional wire representation for raw cases and associated values. Use stable discriminator fields and backwards-compatible decoding, avoiding encoded implementation details that prevent future case evolution.
- [Our New Book: App Architecture (Early Access) · objc.io](https://www.objc.io/blog/2018/01/19/new-book-ios-app-architecture)
  **Published:** `2018-1-19`
  **Topics:** Architecture
  **NeKI brief:** Announces a book about iOS app architecture and its approach to structuring production code. Use it as a reading lead for architectural discussion rather than a standalone prescription.
- [Swift Tip: Adding a toggle Extension on Bool · objc.io](https://www.objc.io/blog/2018/01/16/toggle-extension-on-bool)
  **Published:** `2018-1-16`
  **Topics:** Swift
  **NeKI brief:** A Bool toggle helper expresses state inversion as a mutating operation. Use such a tiny extension only when it improves a local state transition, avoiding generic helpers that obscure a meaningful domain action.
- [Swift Tip: Weak Arrays · objc.io](https://www.objc.io/blog/2017/12/28/weak-arrays)
  **Published:** `2017-12-28`
  **Topics:** Swift
  **NeKI brief:** A weak array tracks object references without extending their lifetime. Use it for observer-like registries with cleanup, accounting for nil entries and avoiding it as a substitute for a clearly owned relationship.
- [Swift Tip: Decomposing Emoji · objc.io](https://www.objc.io/blog/2017/12/19/decomposing-emoji)
  **Published:** `2017-12-19`
  **Topics:** Swift
  **NeKI brief:** Compares Swift Character counting with NSString and other string models, using multi-scalar emoji to show why lengths differ. The examples help prevent incorrect indexing, truncation, and user-visible character-count assumptions.
- [Swift Tip: A Quick Tip For String Performance · objc.io](https://www.objc.io/blog/2017/12/12/quick-tip-for-string-performance)
  **Published:** `2017-12-12`
  **Topics:** Performance · Swift
  **NeKI brief:** String performance depends on Unicode correctness, indexing and allocation behavior rather than simple character counts. Use measurement on representative text before optimizing, preserving correct grapheme semantics over byte-oriented shortcuts.
