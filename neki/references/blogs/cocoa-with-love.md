# Cocoa with Love

Third-party source index. It provides source attribution and routing metadata, not republished article content. Verify article conclusions independently before applying them.

- Archive: [https://www.cocoawithlove.com/archive/](https://www.cocoawithlove.com/archive/)
- Last collected: `2026-07-22T21:58:56Z`
- Indexed entries: **199**

- [Training an LLM in Swift, Part 2: macOS built-in frameworks | Cocoa with Love](https://www.cocoawithlove.com/blog/macos-ml-frameworks.html)
  **Published:** `2026-06-08`
  **Topics:** AI Development · Swift
  **NeKI brief:** Benchmarks Accelerate, BNNS, Core ML, and MPSGraph while implementing GPT-2 components on macOS. The comparison shows which built-in framework fits matrix math, neural-network kernels, or model execution when building Swift ML experiments.
- [Training an LLM in Swift, Part 1: Taking matrix multiplication from Gflop/s to Tflop/s | Cocoa with Love](https://www.cocoawithlove.com/blog/matrix-multiplications-swift.html)
  **Published:** `2026-04-18`
  **Topics:** AI Development · Swift · Testing
  **NeKI brief:** Implements matrix multiplication ten ways, moving from straightforward C and Swift loops to vectorized Accelerate and Metal kernels. The measurements make optimization costs visible and provide a useful baseline for deciding when GPU work is justified.
- [Have LLMs improved for Swift coding in the last 12 months? | Cocoa with Love](https://www.cocoawithlove.com/blog/llms-twelve-months-later.html)
  **Published:** `2025-12-29`
  **Topics:** AI Development · Swift
  **NeKI brief:** Re-tests several hosted and local LLMs on Swift tasks, including prompting an entire app and comparing model-specific behavior. Follow it for qualitative workflow evidence, not a stable benchmark, and reproduce tests on your own codebase.
- [Using Copilot to write a raindrop audio synthesizer using AVAudioEngine | Cocoa with Love](https://www.cocoawithlove.com/blog/copilot-raindrop-generator.html)
  **Published:** `2024-12-25`
  **Topics:** AI Development · Swift · SwiftUI
  **NeKI brief:** Uses Copilot to build an AVAudioEngine raindrop synthesizer, chart its waveform, add noise, and repair thread-safety issues. Follow it to study AI-assisted iteration where generated code still needs audio-domain validation and concurrency cleanup.
- [App architecture basics in SwiftUI Part 4: Services | Cocoa with Love](https://www.cocoawithlove.com/blog/separated-services-layer.html)
  **Published:** `2021-03-23`
  **Topics:** Architecture · Swift · SwiftUI · Testing
  **NeKI brief:** Argues for a distinct Services layer in SwiftUI applications and shows how it isolates external effects from models and views. Follow it when deciding where networking, persistence, or system integration should live in a maintainable app.
- [App architecture basics in SwiftUI Part 3: Module-separated layers | Cocoa with Love](https://www.cocoawithlove.com/blog/app-submodules.html)
  **Published:** `2021-02-12`
  **Topics:** Architecture · Swift · Swift Package Manager · SwiftUI
  **NeKI brief:** The third architecture step isolates SwiftUI layers into modules, making dependency direction explicit before choosing patterns; the cost is extra package boundaries and integration work.
- [App architecture basics in SwiftUI, Part 2: SwiftUI's natural pattern | Cocoa with Love](https://www.cocoawithlove.com/blog/swiftui-natural-pattern.html)
  **Published:** `2021-01-19`
  **Topics:** Architecture · Observation & State Management · Swift · SwiftUI
  **NeKI brief:** A minimalist SwiftUI app naturally separates view descriptions, state, and side effects; the article uses those roles to explain when adding a conventional controller would only reintroduce ceremony.
- [App architecture basics in SwiftUI, Part 1: Coding through iteration and integration | Cocoa with Love](https://www.cocoawithlove.com/blog/coding-through-iteration-and-integration.html)
  **Published:** `2020-12-31`
  **Topics:** Architecture · Swift · SwiftUI
  **NeKI brief:** A JSON feed reader is built through small compiling increments, using integration feedback to shape boundaries; this trades upfront design certainty for continuously executable architecture.
- [22 short tests of combine – Part 3: Asynchrony | Cocoa with Love](https://www.cocoawithlove.com/blog/twenty-two-short-tests-of-combine-part-3.html)
  **Published:** `2019-08-18`
  **Topics:** Concurrency · Performance · Testing
  **NeKI brief:** Uses focused experiments to explain Combine asynchrony, including scheduling and delivery timing. The tests are valuable when diagnosing race-prone pipelines or checking whether an operator chain preserves the execution context an app expects.
- [22 short tests of combine – Part 2: Sharing | Cocoa with Love](https://www.cocoawithlove.com/blog/twenty-two-short-tests-of-combine-part-2.html)
  **Published:** `2019-08-17`
  **Topics:** Testing
  **NeKI brief:** Explores how Combine publishers share work and state through small executable tests. It helps distinguish duplicated subscriptions from shared upstream computation before choosing multicast, share, or replay behavior in a reactive feature.
- [22 short tests of Combine – Part 1: Protocols | Cocoa with Love](https://www.cocoawithlove.com/blog/twenty-two-short-tests-of-combine-part-1.html)
  **Published:** `2019-08-16`
  **Topics:** Testing
  **NeKI brief:** Uses small focused tests to probe Combine operator behavior and scheduling. Follow it when validating assumptions about demand, completion, cancellation, or ordering instead of relying on visual behavior alone.
- [First impressions of SwiftUI | Cocoa with Love](https://www.cocoawithlove.com/blog/swiftui.html)
  **Published:** `2019-06-08`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Provides early implementation analysis of SwiftUI's declarative model and rendering implications. Follow it for historical context when comparing initial assumptions with current framework behavior and migration lessons.
- [Declarative Views | Cocoa with Love](https://www.cocoawithlove.com/blog/declarative-views.html)
  **Published:** `2019-05-03`
  **Topics:** Apple Platform Ecosystem · SwiftUI
  **NeKI brief:** Explores declarative view construction and the state-to-rendering relationship behind it. Follow it when designing UIKit abstractions that aim to reduce imperative mutation without adopting SwiftUI wholesale.
- [Introducing CwlViews | Cocoa with Love](https://www.cocoawithlove.com/blog/introducing-cwlviews.html)
  **Published:** `2019-04-28`
  **Topics:** Observation & State Management · Testing
  **NeKI brief:** Introduces CwlViews as a declarative Swift wrapper around UIKit view construction. Use it to compare typed, compositional view descriptions with SwiftUI and assess the trade-offs in an incremental UIKit codebase.
- [Article updates, 2018 edition | Cocoa with Love](https://www.cocoawithlove.com/blog/updating-for-2018.html)
  **Published:** `2018-10-09`
  **Topics:** Navigation & Deep Linking · Swift · Xcode
  **NeKI brief:** The 2018 update log shows how a large article corpus is kept coherent across Xcode, Swift, and OS releases, with build-system regressions becoming part of maintenance cost.
- [A Farewell to StreamToMe | Cocoa with Love](https://www.cocoawithlove.com/blog/a-farewell-to-streamtome.html)
  **Published:** `2018-09-04`
  **Topics:** Apple Platform Ecosystem · Graphics, Media & Games · Swift
  **NeKI brief:** Removing a profitable app illustrates the maintenance burden of support, platform changes, and neglected quality; withdrawal can be a deliberate product decision when operational cost outweighs revenue.
- [Model-View-Controller without the Controller | Cocoa with Love](https://www.cocoawithlove.com/blog/mvc-without-the-c.html)
  **Published:** `2018-01-20`
  **Topics:** Observation & State Management · Testing
  **NeKI brief:** CwlViews turns view construction into a unidirectional pipeline, so state changes flow without UIViewController subclasses; navigation and imperative escape hatches remain the main trade-off.
- [A view construction syntax | Cocoa with Love](https://www.cocoawithlove.com/blog/a-view-construction-syntax.html)
  **Published:** `2017-12-15`
  **Topics:** Architecture · Swift · Xcode
  **NeKI brief:** The proposed typed view syntax carries inherited parameters and optional configuration without parentheses or type repetition, improving composition while introducing a custom DSL that teammates must learn.
- [View-state driven applications | Cocoa with Love](https://www.cocoawithlove.com/blog/view-state-driven-applications.html)
  **Published:** `2017-11-08`
  **Topics:** Navigation & Deep Linking · SwiftUI · Testing
  **NeKI brief:** Explores driving application behavior from explicit view state rather than scattered callbacks. Use it when designing predictable state transitions that can be rendered, tested, and restored independently of UIKit lifecycle events.
- [The worst possible application | Cocoa with Love](https://www.cocoawithlove.com/blog/worst-possible-application.html)
  **Published:** `2017-10-20`
  **Topics:** Architecture
  **NeKI brief:** Deliberately concentrating state and responsibilities in a pathological app makes architectural failure observable, providing a useful diagnostic baseline before introducing a less coupled design.
- [CwlLayout: a Swift wrapper around Auto Layout | Cocoa with Love](https://www.cocoawithlove.com/blog/cwllayout.html)
  **Published:** `2017-08-03`
  **Topics:** Swift
  **NeKI brief:** Introduces CwlLayout as a Swift wrapper around Auto Layout constraints. Follow it when comparing typed layout construction with Interface Builder or raw NSLayoutConstraint calls in UIKit-heavy code.
- [About flatMap, compactMap and monads | Cocoa with Love](https://www.cocoawithlove.com/blog/an-aside-about-flatmap-and-monads.html)
  **Published:** `2017-06-30`
  **Topics:** Swift
  **NeKI brief:** Swift flatMap is examined as a conditional transformation rather than automatically a full monad; the distinction helps choose composition patterns without importing algebraic terminology blindly.
- [Statements, messages and reducers | Cocoa with Love](https://www.cocoawithlove.com/blog/statements-messages-reducers.html)
  **Published:** `2017-06-22`
  **Topics:** Architecture · Swift
  **NeKI brief:** Separating statements, messages, and reducers confines mutable state to explicit computational tiers; the added routing machinery buys deterministic transitions and easier isolation of effects.
- [Looking at Model-View-Controller in Cocoa | Cocoa with Love](https://www.cocoawithlove.com/blog/mvc-and-cocoa.html)
  **Published:** `2017-02-28`
  **Topics:** Observation & State Management · UIKit
  **NeKI brief:** Traces Cocoa MVC from its Smalltalk roots through Apple's implementation and highlights where the pattern's boundaries become weak. Use it for architecture context when deciding whether a new feature needs clearer state or presentation separation.
- [The weirdest subclass I've ever written | Cocoa with Love](https://www.cocoawithlove.com/blog/protocols-versus-subclasses.html)
  **Published:** `2017-02-26`
  **Topics:** Architecture · Swift
  **NeKI brief:** A carefully chosen subclass preserves class-specific behavior that protocol composition cannot express, illustrating why substitutability alone is not a reason to eliminate inheritance.
- [Using 'swift package fetch' in an Xcode project | Cocoa with Love](https://www.cocoawithlove.com/blog/package-manager-fetch.html)
  **Published:** `2017-01-30`
  **Topics:** Dependency Injection · Swift · Swift Package Manager · Xcode
  **NeKI brief:** Explains wiring Swift Package Manager dependency fetching into an Xcode build before native integration existed, exposing the build-phase and dependency-ordering concerns involved. Follow it for historical build-system trade-offs and CI diagnosis.
- [Compiling a Mac OS 8 application on macOS Sierra | Cocoa with Love](https://www.cocoawithlove.com/blog/porting-from-macos8-to-sierra.html)
  **Published:** `2017-01-12`
  **Topics:** Xcode
  **NeKI brief:** Porting a 1999 Mac OS 8 C++ game to modern Xcode exposes framework and toolchain assumptions, making historical compatibility a concrete exercise in isolating platform dependencies.
- [A key-value observing wrapper | Cocoa with Love](https://www.cocoawithlove.com/blog/key-value-observing-wrapper.html)
  **Published:** `2016-12-31`
  **Topics:** Swift
  **NeKI brief:** A small KVO wrapper normalizes observer registration and teardown, reducing boilerplate while retaining Objective-C runtime semantics that still constrain type safety.
- [Reference counted releases in Swift | Cocoa with Love](https://www.cocoawithlove.com/blog/resources-releases-reentrancy.html)
  **Published:** `2016-12-27`
  **Topics:** Swift
  **NeKI brief:** Swift may reorder reference-counted releases, so withExtendedLifetime is needed when scope does not guarantee a resource remains alive; forcing lifetime can mask ownership design problems.
- [What is reactive programming and why should I use it? | Cocoa with Love](https://www.cocoawithlove.com/blog/reactive-programming-what-and-why.html)
  **Published:** `2016-11-28`
  **Topics:** Concurrency
  **NeKI brief:** Motivates reactive programming through recurring application problems such as unsafe callbacks, verbosity, and difficult refactoring. Use it as conceptual context before choosing a concrete publisher or async-sequence implementation.
- [CwlSignal, a library for reactive programming | Cocoa with Love](https://www.cocoawithlove.com/blog/cwlsignal.html)
  **Published:** `2016-11-28`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Presents CwlSignal as a thread-safe reactive programming library with explicit signal composition. Follow it to compare lightweight event propagation and cancellation semantics with Combine or callback-based application code.
- [Testing actions over time | Cocoa with Love](https://www.cocoawithlove.com/blog/testing-actions-over-time.html)
  **Published:** `2016-10-25`
  **Topics:** Dependency Injection · Navigation & Deep Linking · Testing
  **NeKI brief:** A debug context coordinator replaces wall-clock scheduling with simulated time, making ordering and execution-context assertions deterministic at the cost of testing through a scheduler abstraction.
- [Specifying function execution contexts | Cocoa with Love](https://www.cocoawithlove.com/blog/specifying-execution-contexts.html)
  **Published:** `2016-10-14`
  **Topics:** Architecture · Concurrency · Swift
  **NeKI brief:** Execution context is a contract negotiated between caller and callee rather than a single queue choice; documenting both sides prevents accidental latency or thread-safety regressions.
- [Optimizing a copy-on-write double-ended queue in Swift | Cocoa with Love](https://www.cocoawithlove.com/blog/2016/09/22/deque.html)
  **Published:** `2016-09-22`
  **Topics:** Swift
  **NeKI brief:** The deque implementation combines copy-on-write storage with ring-buffer indexing to outperform Array for FIFO workloads, trading a more complex invariant for cheaper front removals.
- [Updating Cocoa with Love for Swift 3 | Cocoa with Love](https://www.cocoawithlove.com/blog/2016/09/14/updating-cocoawithlove.html)
  **Published:** `2016-09-14`
  **Topics:** Swift · Testing · Xcode
  **NeKI brief:** The Swift 3 migration records API renames and platform changes as a repeatable compatibility pass, useful for estimating modernization effort rather than treating upgrades as one edit.
- [Values and errors, part 2: eight languages compared | Cocoa with Love](https://www.cocoawithlove.com/blog/2016/08/23/result-types-part-two.html)
  **Published:** `2016-08-23`
  **Topics:** Swift
  **NeKI brief:** Comparing Result designs across eight languages exposes Swift's typed-error trade-offs, especially whether failure belongs in return values or exceptional control flow.
- [Values and errors, part 1: 'Result' in Swift | Cocoa with Love](https://www.cocoawithlove.com/blog/2016/08/21/result-types-part-one.html)
  **Published:** `2016-08-21`
  **Topics:** Swift
  **NeKI brief:** Result packages success and failure into one value, making error propagation explicit and composable; callers pay with more branching when failures are not recoverable locally.
- [Design patterns for safe timer usage | Cocoa with Love](https://www.cocoawithlove.com/blog/2016/07/30/timer-problems.html)
  **Published:** `2016-07-30`
  **Topics:** Concurrency
  **NeKI brief:** Timer ownership, run-loop modes, and invalidation are treated as design constraints, preventing retain cycles and missed firings that appear when scheduling is hidden in view code.
- [Exponential time complexity in the Swift type checker | Cocoa with Love](https://www.cocoawithlove.com/blog/2016/07/12/type-checker-issues.html)
  **Published:** `2016-07-12`
  **Topics:** Performance · Swift
  **NeKI brief:** Analyzes Swift type-checker blowups behind 'expression too complex' diagnostics and suggests restructuring expressions to reduce inference work. Follow it when compile-time performance points to constraint-solving shape rather than runtime algorithm cost.
- [Parsing whitespace in an Xcode extension | Cocoa with Love](https://www.cocoawithlove.com/blog/2016/06/25/policing-whitespace.html)
  **Published:** `2016-06-25`
  **Topics:** Swift · Xcode
  **NeKI brief:** A pushdown automaton parses Swift whitespace inside an Xcode source-editor extension, showing how lexical state avoids corrupting strings and comments during formatting.
- [Mutexes and closure capture in Swift | Cocoa with Love](https://www.cocoawithlove.com/blog/2016/06/02/threads-and-mutexes.html)
  **Published:** `2016-06-02`
  **Topics:** Concurrency · Performance · Swift
  **NeKI brief:** Closure capture and mutex scope determine whether shared Swift state is actually protected; locking too broadly avoids races but can create reentrancy and latency hazards.
- [Random number generators in Swift | Cocoa with Love](https://www.cocoawithlove.com/blog/2016/05/19/random-numbers.html)
  **Published:** `2016-05-19`
  **Topics:** Performance · Swift
  **NeKI brief:** Several Swift random generators are compared for statistical quality and speed, clarifying when a fast deterministic algorithm is acceptable and when stronger randomness is required.
- [Comparing Swift to C++ for parsing | Cocoa with Love](https://www.cocoawithlove.com/blog/2016/05/01/swift-name-demangling.html)
  **Published:** `2016-05-01`
  **Topics:** Performance · Swift
  **NeKI brief:** Reimplementing Swift demangling in Swift beside the C++ original turns parsing into a measurable interoperability experiment, revealing performance costs of safety and expressiveness.
- [Presenting unanticipated errors to users | Cocoa with Love](https://www.cocoawithlove.com/blog/2016/04/14/error-recovery-attempter.html)
  **Published:** `2016-04-14`
  **Topics:** Swift
  **NeKI brief:** Unexpected Cocoa errors are routed through an explicit recovery attempter, separating user-facing remediation from low-level failure detection and preserving a fallback for unknown cases.
- [Indent with tabs or spaces? I wish I didn't need to know. | Cocoa with Love](https://www.cocoawithlove.com/blog/2016/04/01/neither-tabs-nor-spaces.html)
  **Published:** `2016-04-01`
  **Topics:** Swift
  **NeKI brief:** Whitespace encoding should remain invisible to program meaning; treating formatting as a lexical concern avoids debates leaking into source semantics and tooling behavior.
- [Breaking Swift with reference counted structs | Cocoa with Love](https://www.cocoawithlove.com/blog/2016/03/27/on-delete.html)
  **Published:** `2016-03-27`
  **Topics:** Swift
  **NeKI brief:** Reference-counted structs can perform deallocation work through hidden heap storage, but this breaks value-type expectations and makes copying and destruction order part of the API contract.
- [Errors: unexpected, composite, non-pure, external. | Cocoa with Love](https://www.cocoawithlove.com/blog/2016/03/17/non-pure-errors.html)
  **Published:** `2016-03-17`
  **Topics:** Testing
  **NeKI brief:** Errors are classified by purity, composition, and external origin, helping decide whether recovery belongs near the cause or at a broader application boundary.
- [Gathering system information in Swift with sysctl | Cocoa with Love](https://www.cocoawithlove.com/blog/2016/03/08/swift-wrapper-for-sysctl.html)
  **Published:** `2016-03-08`
  **Topics:** Swift
  **NeKI brief:** Wrapping sysctl turns platform-specific C buffers into typed Swift access, while preserving explicit size and ownership handling needed for reliable system inspection.
- [Tracking tasks with stack traces in Swift | Cocoa with Love](https://www.cocoawithlove.com/blog/2016/02/28/stack-traces-in-swift.html)
  **Published:** `2016-02-28`
  **Topics:** Swift
  **NeKI brief:** Capturing stack traces alongside asynchronous tasks makes later failures diagnosable, trading runtime bookkeeping and symbolication work for actionable provenance.
- [Use it or lose it: why safe C is sometimes unsafe Swift | Cocoa with Love](https://www.cocoawithlove.com/blog/2016/02/16/use_it_or_lose_it_why_safe_c_is_sometimes_unsafe_swift.html)
  **Published:** `2016-02-16`
  **Topics:** Swift
  **NeKI brief:** Swift's safer surface can still expose C lifetime and pointer hazards when imported APIs erase ownership, so safety depends on auditing the boundary rather than syntax alone.
- [Partial functions in Swift, Part 2: Catching precondition failures | Cocoa with Love](https://www.cocoawithlove.com/blog/2016/02/02/partial-functions-part-two-catching-precondition-failures.html)
  **Published:** `2016-02-02`
  **Topics:** Swift · Testing
  **NeKI brief:** Catching precondition failures can contain invalid-input crashes at a boundary, but it also risks normalizing programmer bugs that should remain fail-fast during development.
- [Partial functions in Swift, Part 1: Avoidance | Cocoa with Love](https://www.cocoawithlove.com/blog/2016/01/25/partial-functions-part-one-avoidance.html)
  **Published:** `2016-01-25`
  **Topics:** Swift
  **NeKI brief:** Treating partial functions as explicit design hazards encourages total inputs and recoverable results, reducing crash paths before adding any error-catching machinery.
- [A new era for Cocoa with Love | Cocoa with Love](https://www.cocoawithlove.com/blog/2016/01/25/a-new-era-for-cocoa-with-love.html)
  **Published:** `2016-01-25`
  **Topics:** Swift
  **NeKI brief:** The site's restart uses Swift and modern Cocoa as a deliberate boundary, illustrating how a project can preserve accumulated knowledge while changing implementation assumptions.
- [A big weakness in Objective-C's weak typing | Cocoa with Love](https://www.cocoawithlove.com/2011/06/big-weakness-of-objective-c-weak-typing.html)
  **Published:** `2011-06-30`
  **Topics:** Architecture · Swift · Xcode
  **NeKI brief:** Objective-C's permissive message and type model shifts failures from compilation to runtime, motivating stronger boundaries where Swift or explicit validation can recover intent.
- [An RSS-feed and location-based iOS application | Cocoa with Love](https://www.cocoawithlove.com/2011/06/process-of-writing-ios-application.html)
  **Published:** `2011-06-19`
  **Topics:** Networking
  **NeKI brief:** An RSS and location-based app is decomposed around network parsing, persistence, and UI updates, showing where asynchronous data flow creates coordination pressure.
- [Classes for fetching and parsing XML or JSON via HTTP | Cocoa with Love](https://www.cocoawithlove.com/2011/05/classes-for-fetching-and-parsing-xml-or.html)
  **Published:** `2011-05-30`
  **Topics:** Networking · Swift
  **NeKI brief:** Reusable fetch-and-parse classes separate transport from XML or JSON decoding, allowing format changes without rewriting request lifecycle and error handling.
- [Presenting a Mac dialog sheet with visual cue effects | Cocoa with Love](https://www.cocoawithlove.com/2011/05/presenting-mac-dialog-sheet-with-visual.html)
  **Published:** `2011-05-05`
  **Topics:** Graphics, Media & Games · UIKit
  **NeKI brief:** AppKit dialog sheets combine modal flow with visual cue effects, requiring window lifecycle coordination so animation feedback does not obscure dismissal or focus behavior.
- [Background audio through an iOS movie player | Cocoa with Love](https://www.cocoawithlove.com/2011/04/background-audio-through-ios-movie.html)
  **Published:** `2011-04-20`
  **Topics:** Testing
  **NeKI brief:** Background audio through the movie-player APIs depends on session configuration and interruption behavior, so playback reliability is a lifecycle contract rather than a single flag.
- [User interface strings in Cocoa | Cocoa with Love](https://www.cocoawithlove.com/2011/04/user-interface-strings-in-cocoa.html)
  **Published:** `2011-04-05`
  **Topics:** App Intents & System Surfaces · Persistence & Synchronisation · Swift
  **NeKI brief:** Centralizing Cocoa UI strings makes localization an explicit resource lookup, but format placeholders and fallback behavior must remain consistent across languages.
- [Mac QuartzGL (2D drawing on the graphics card) performance | Cocoa with Love](https://www.cocoawithlove.com/2011/03/mac-quartzgl-2d-drawing-on-graphics.html)
  **Published:** `2011-03-25`
  **Topics:** Performance · Testing
  **NeKI brief:** QuartzGL can move 2D drawing to the graphics card, yet compositing and upload overhead may erase gains; profiling the actual workload determines whether acceleration helps.
- [A history of iOS media APIs (iPhone OS 2.0 to iOS 4.3) | Cocoa with Love](https://www.cocoawithlove.com/2011/03/history-of-ios-media-apis-iphone-os-20.html)
  **Published:** `2011-03-20`
  **Topics:** Apple Platform Ecosystem · Graphics, Media & Games · Swift
  **NeKI brief:** The history of iOS media APIs tracks changing capture, playback, and codec abstractions across early releases. Follow it to understand compatibility constraints before maintaining legacy AVFoundation or MediaPlayer code.
- [Advanced drawing using AppKit | Cocoa with Love](https://www.cocoawithlove.com/2011/01/advanced-drawing-using-appkit.html)
  **Published:** `2011-01-31`
  **Topics:** Graphics, Media & Games · UIKit
  **NeKI brief:** Advanced AppKit drawing composes paths, transforms, and clipping to control raster output, trading manual geometry for predictable rendering beyond standard controls.
- [Submitting functionality for a future version of iOS | Cocoa with Love](https://www.cocoawithlove.com/2011/01/submitting-functionality-for-future.html)
  **Published:** `2011-01-26`
  **Topics:** Apple Platform Ecosystem · Swift
  **NeKI brief:** Designing for future iOS functionality requires isolating optional capabilities from today's shipped behavior, reducing migration risk when APIs or platform assumptions change.
- [UITableView construction, drawing and management (revisited) | Cocoa with Love](https://www.cocoawithlove.com/2010/12/uitableview-construction-drawing-and.html)
  **Published:** `2010-12-19`
  **Topics:** Architecture · Swift · UIKit
  **NeKI brief:** UITableView performance depends on cell reuse, drawing cost, and when data management occurs, not simply on row count. The revisited construction guide offers profiling-oriented decisions for legacy UIKit lists.
- [Version control for solo Mac developers | Cocoa with Love](https://www.cocoawithlove.com/2010/12/version-control-for-solo-mac-developers.html)
  **Published:** `2010-12-12`
  **Topics:** Swift · Xcode
  **NeKI brief:** Solo development still benefits from disciplined commits and recoverable history, because version control is a debugging tool even without code review partners.
- [Back to the Mac? 12 features from iOS I'd like to see in Lion | Cocoa with Love](https://www.cocoawithlove.com/2010/11/back-to-mac-12-features-from-ios-i-like.html)
  **Published:** `2010-11-20`
  **Topics:** Graphics, Media & Games · Swift · UIKit
  **NeKI brief:** Comparing iOS interaction features with Mac conventions highlights where platform transfer improves consistency and where pointer, keyboard, and window models require different decisions.
- [A Cocoa application for running scripts | Cocoa with Love](https://www.cocoawithlove.com/2010/11/cocoa-application-for-running-scripts.html)
  **Published:** `2010-11-12`
  **Topics:** Swift · Xcode
  **NeKI brief:** A Cocoa script runner coordinates process launch, output capture, and user feedback, making shell automation approachable while requiring explicit cancellation and error reporting.
- [A deployment script for a generic Cocoa Mac application | Cocoa with Love](https://www.cocoawithlove.com/2010/11/deployment-script-for-generic-cocoa-mac.html)
  **Published:** `2010-11-05`
  **Topics:** Swift · UIKit · Xcode
  **NeKI brief:** A deployment script packages a generic Cocoa app reproducibly, moving signing and resource layout out of manual steps while making build assumptions inspectable.
- [An iOS tone generator (an introduction to AudioUnits) | Cocoa with Love](https://www.cocoawithlove.com/2010/10/ios-tone-generator-introduction-to.html)
  **Published:** `2010-10-20`
  **Topics:** Graphics, Media & Games
  **NeKI brief:** An AudioUnit tone generator demonstrates buffer-level synthesis and real-time constraints, where allocation or blocking in the render callback would immediately damage playback.
- [Testing if an arbitrary pointer is a valid object pointer | Cocoa with Love](https://www.cocoawithlove.com/2010/10/testing-if-arbitrary-pointer-is-valid.html)
  **Published:** `2010-10-06`
  **Topics:** Testing
  **NeKI brief:** Testing arbitrary pointer validity exposes the limits of defensive runtime probing, since memory can change between check and use and undefined behavior remains possible.
- [A ZoomingViewController to animate a UIView to fullscreen | Cocoa with Love](https://www.cocoawithlove.com/2010/09/zoomingviewcontroller-to-animate-uiview.html)
  **Published:** `2010-09-26`
  **Topics:** UIKit
  **NeKI brief:** Animating a view from its normal hierarchy to fullscreen requires preserving transforms, coordinate conversion, and restoration state. The ZoomingViewController example is useful for diagnosing jumps during custom UIKit transitions.
- [Minimalist Cocoa programming | Cocoa with Love](https://www.cocoawithlove.com/2010/09/minimalist-cocoa-programming.html)
  **Published:** `2010-09-20`
  **Topics:** Xcode
  **NeKI brief:** Minimalist Cocoa programming emphasizes reducing framework surface and object ceremony to clarify what an app actually needs. It is useful historical context when a small feature has accumulated unnecessary infrastructure.
- [The overhead of spawning threads (a performance experiment) | Cocoa with Love](https://www.cocoawithlove.com/2010/09/overhead-of-spawning-threads.html)
  **Published:** `2010-09-14`
  **Topics:** Performance · Testing
  **NeKI brief:** Thread-spawning benchmarks show startup overhead can dominate short tasks, motivating reuse or dispatch queues when latency matters more than isolation simplicity.
- [Substituting local data for remote UIWebView requests | Cocoa with Love](https://www.cocoawithlove.com/2010/09/substituting-local-data-for-remote.html)
  **Published:** `2010-09-06`
  **Topics:** Networking · Persistence & Synchronisation · UIKit
  **NeKI brief:** Substituting local data for remote UIWebView requests uses URL interception and a local response path, enabling deterministic offline rendering. The pattern helps test web-backed screens without relying on network timing.
- [Alternative Objective-C object allocation for large arrays | Cocoa with Love](https://www.cocoawithlove.com/2010/08/alternative-objective-c-object.html)
  **Published:** `2010-08-30`
  **Topics:** Graphics, Media & Games · Performance · Swift
  **NeKI brief:** Alternative Objective-C allocation strategies can reduce overhead for very large arrays by changing object layout and initialization cost. The article is useful historical evidence that allocation behavior should be measured against workload.
- [Is a virtual machine for Cocoa programming inevitable? | Cocoa with Love](https://www.cocoawithlove.com/2010/07/is-virtual-machine-for-cocoa.html)
  **Published:** `2010-07-15`
  **Topics:** Performance
  **NeKI brief:** The virtual-machine question weighs runtime portability against native API access and performance. Follow it for a concrete lens on why cross-platform abstractions often leak platform lifecycle and rendering semantics.
- [Tips & Tricks for conditional iOS3, iOS3.2 and iOS4 code | Cocoa with Love](https://www.cocoawithlove.com/2010/07/tips-tricks-for-conditional-ios3-ios32.html)
  **Published:** `2010-07-06`
  **Topics:** Macros & Metaprogramming
  **NeKI brief:** Conditional compilation and availability checks let one codebase target divergent iOS SDKs, but each branch adds testing surface. These tips help isolate source compatibility from runtime capability and deployment-target policy.
- [Assign, retain, copy: pitfalls in Obj-C property accessors | Cocoa with Love](https://www.cocoawithlove.com/2010/06/assign-retain-copy-pitfalls-in-obj-c.html)
  **Published:** `2010-06-30`
  **Topics:** Performance · Swift
  **NeKI brief:** Objective-C assign, retain, and copy properties encode distinct ownership and mutation semantics; choosing the wrong one creates dangling pointers or shared mutable state. The examples remain useful when auditing legacy model declarations.
- [The design of every Mac application | Cocoa with Love](https://www.cocoawithlove.com/2010/06/design-of-every-mac-application.html)
  **Published:** `2010-06-22`
  **Topics:** Objective-C & Cocoa
  **NeKI brief:** Mac application design is decomposed into document, event, window, and responder responsibilities rather than one monolithic controller. The model helps diagnose lifecycle bugs in AppKit applications that mix UI and persistence.
- [Sorting an NSMutableArray with a random comparison method | Cocoa with Love](https://www.cocoawithlove.com/2010/06/sorting-nsmutablearray-with-random.html)
  **Published:** `2010-06-10`
  **Topics:** Swift
  **NeKI brief:** Sorting with a random comparison violates comparator transitivity, so results become undefined rather than merely shuffled. The example is a useful warning when generating randomized orderings for tests or UI.
- [Avoiding deadlocks and latency in libdispatch | Cocoa with Love](https://www.cocoawithlove.com/2010/06/avoiding-deadlocks-and-latency-in.html)
  **Published:** `2010-06-02`
  **Topics:** Concurrency · Performance
  **NeKI brief:** libdispatch deadlocks arise when synchronous work waits on a queue that is already executing the caller, while latency grows from unnecessary serialization. Queue-graph reasoning reveals both failure modes.
- [Handling unhandled exceptions and signals | Cocoa with Love](https://www.cocoawithlove.com/2010/05/handling-unhandled-exceptions-and.html)
  **Published:** `2010-05-25`
  **Topics:** Swift · Testing
  **NeKI brief:** Unhandled exceptions and signals require different capture paths and have different recovery guarantees. This guide helps distinguish crash diagnostics from safe recovery, avoiding handlers that continue after corrupted process state.
- [5 ways to draw a 2D shape with a hole in CoreGraphics | Cocoa with Love](https://www.cocoawithlove.com/2010/05/5-ways-to-draw-2d-shape-with-hole-in.html)
  **Published:** `2010-05-17`
  **Topics:** Graphics, Media & Games
  **NeKI brief:** Core Graphics can create a hole through winding rules, clipping, paths, masks, or compositing, each with different antialiasing behavior. Comparing them helps choose the right rendering mechanism for complex shapes.
- [A look at how malloc works on the Mac | Cocoa with Love](https://www.cocoawithlove.com/2010/05/look-at-how-malloc-works-on-mac.html)
  **Published:** `2010-05-12`
  **Topics:** Performance
  **NeKI brief:** Understanding malloc's arenas, allocation sizes, and free-list behavior gives context to fragmentation and heap-growth measurements. Follow it before attributing a memory spike to a single retained object.
- [Finding or creating the application support directory | Cocoa with Love](https://www.cocoawithlove.com/2010/05/finding-or-creating-application-support.html)
  **Published:** `2010-05-06`
  **Topics:** Swift
  **NeKI brief:** Application Support directory lookup must respect sandbox and platform conventions instead of hard-coding paths. The workflow is useful for keeping generated databases and caches in locations that survive OS changes.
- [Porting a Mac program to Windows using The Cocotron | Cocoa with Love](https://www.cocoawithlove.com/2010/04/porting-mac-program-to-windows-using.html)
  **Published:** `2010-04-27`
  **Topics:** Xcode
  **NeKI brief:** Porting a Mac program with Cocotron exposes which application behavior belongs to Cocoa and which can be abstracted. Follow it to evaluate compatibility layers without assuming a shared API guarantees shared UX.
- [Design of a multi-platform app using The Cocotron | Cocoa with Love](https://www.cocoawithlove.com/2010/04/design-of-multi-platform-app-using.html)
  **Published:** `2010-04-21`
  **Topics:** Swift
  **NeKI brief:** A Cocotron multi-platform design separates application logic from platform integration points, making portability an explicit architectural cost. The discussion helps identify where windowing, files, and controls inevitably diverge.
- [Options for porting Objective-C/Cocoa apps to Windows | Cocoa with Love](https://www.cocoawithlove.com/2010/04/options-for-porting-objective-ccocoa.html)
  **Published:** `2010-04-15`
  **Topics:** Objective-C & Cocoa
  **NeKI brief:** Porting Objective-C/Cocoa applications to Windows compares compatibility frameworks, rewrites, and platform abstractions. It is useful for weighing code reuse against build, UI, and runtime behavior that cannot be shared.
- [Network data requirements on iPhone OS devices | Cocoa with Love](https://www.cocoawithlove.com/2010/04/network-data-requirements-on-iphone-os.html)
  **Published:** `2010-04-07`
  **Topics:** Apple Platform Ecosystem · Networking · Persistence & Synchronisation
  **NeKI brief:** Early iPhone networking constraints include bandwidth, latency, radio energy, and intermittent connectivity. The analysis helps frame request batching and caching as product behavior, not only transport optimization.
- [Streaming MP3/AAC audio again | Cocoa with Love](https://www.cocoawithlove.com/2010/03/streaming-mp3aac-audio-again.html)
  **Published:** `2010-03-29`
  **Topics:** Graphics, Media & Games · Networking
  **NeKI brief:** Streaming compressed audio requires buffering, format negotiation, and interruption handling in addition to decoding. Follow it for diagnosing underruns and designing playback that remains responsive on variable networks.
- [Dynamic ivars: solving a fragile base class problem | Cocoa with Love](https://www.cocoawithlove.com/2010/03/dynamic-ivars-solving-fragile-base.html)
  **Published:** `2010-03-22`
  **Topics:** Apple Platform Ecosystem · Swift
  **NeKI brief:** Dynamic ivars avoid fragile-base-class assumptions by resolving storage at runtime, but shift safety and introspection costs into the implementation. The technique is useful historical context for Objective-C runtime compatibility.
- [Custom UI Bindings in Interface Builder | Cocoa with Love](https://www.cocoawithlove.com/2010/03/custom-ui-bindings-in-interface-builder.html)
  **Published:** `2010-03-15`
  **Topics:** Observation & State Management
  **NeKI brief:** Custom Interface Builder bindings connect key paths to controls, reducing glue code while making naming and observation contracts implicit. The article helps weigh binding convenience against runtime debugging difficulty.
- [Designing a view with Bindings (UITableView on the Mac) | Cocoa with Love](https://www.cocoawithlove.com/2010/03/designing-view-with-bindings.html)
  **Published:** `2010-03-10`
  **Topics:** Observation & State Management
  **NeKI brief:** Cocoa bindings can connect a UITableView to model values through controllers and key paths, reducing glue code. The design is useful when evaluating observation-driven UI against the debugging opacity of implicit wiring.
- [Load from NIB or construct views in code: which is faster? | Cocoa with Love](https://www.cocoawithlove.com/2010/03/load-from-nib-or-construct-views-in.html)
  **Published:** `2010-03-01`
  **Topics:** Performance
  **NeKI brief:** Nib loading and programmatic view construction trade serialization convenience against allocation and startup work. The comparison is useful when choosing a UIKit composition strategy based on measured launch and reuse costs.
- [Resolving a path containing a mixture of aliases and symlinks | Cocoa with Love](https://www.cocoawithlove.com/2010/02/resolving-path-containing-mixture-of.html)
  **Published:** `2010-02-21`
  **Topics:** Swift
  **NeKI brief:** Resolving paths that mix aliases and symlinks requires preserving filesystem semantics across multiple indirections. The technique is useful for tooling that must canonicalize user-selected files without losing valid references.
- [The differences between Core Data and a Database | Cocoa with Love](https://www.cocoawithlove.com/2010/02/differences-between-core-data-and.html)
  **Published:** `2010-02-16`
  **Topics:** Core Data · Persistence & Synchronisation
  **NeKI brief:** Core Data manages an object graph and persistence context rather than exposing a plain relational database contract. The comparison clarifies faulting, identity, and change tracking before choosing queries or storage abstractions.
- [Custom build rules, generated tables and faster floating point | Cocoa with Love](https://www.cocoawithlove.com/2010/02/custom-build-rules-generated-tables-and.html)
  **Published:** `2010-02-08`
  **Topics:** Performance
  **NeKI brief:** Custom build rules can generate lookup tables before compilation, moving repetitive computation out of runtime code. The trade-off is build complexity and generated-source maintenance, which should be justified with measurements.
- [Finding the cause of performance issues in your programs | Cocoa with Love](https://www.cocoawithlove.com/2010/02/finding-cause-of-simple-performance.html)
  **Published:** `2010-02-01`
  **Topics:** Core Data · Performance · Persistence & Synchronisation
  **NeKI brief:** Simple performance investigations start by measuring a reproducible workload and narrowing the dominant operation before optimizing. The workflow remains useful for avoiding intuition-driven changes in Cocoa code.
- [5 key-value coding approaches in Cocoa | Cocoa with Love](https://www.cocoawithlove.com/2010/01/5-key-value-coding-approaches-in-cocoa.html)
  **Published:** `2010-01-25`
  **Topics:** Architecture · Persistence & Synchronisation · Swift
  **NeKI brief:** Five KVC approaches show how direct access, accessors, collection operators, and validation alter Cocoa data flow. Follow it to diagnose key-path failures and choose APIs that retain type and ownership clarity.
- [What is a meta-class in Objective-C? | Cocoa with Love](https://www.cocoawithlove.com/2010/01/what-is-meta-class-in-objective-c.html)
  **Published:** `2010-01-17`
  **Topics:** Macros & Metaprogramming · Swift
  **NeKI brief:** Objective-C metaclasses explain how class methods participate in the same message-dispatch model as instance methods. The article is valuable when debugging runtime introspection, swizzling, or unexpected class-level behavior.
- [Getting the subclasses of an Objective-C class | Cocoa with Love](https://www.cocoawithlove.com/2010/01/getting-subclasses-of-objective-c-class.html)
  **Published:** `2010-01-11`
  **Topics:** Architecture
  **NeKI brief:** Finding subclasses at runtime requires walking Objective-C's class registry and accounting for dynamically loaded types. The technique is useful for plugin discovery and diagnostic tooling, but should not replace explicit registration lightly.
- [Quality control in application development without unit testing | Cocoa with Love](https://www.cocoawithlove.com/2010/01/high-quality-in-software-development.html)
  **Published:** `2010-01-05`
  **Topics:** Testing
  **NeKI brief:** Contrasts code-level unit tests with system-level tests for application defect detection, identifying isolation, integration, timing, and reentrancy gaps; an historically opinionated testing perspective to interrogate rather than adopt.
- [A sample iPhone application with complete unit tests | Cocoa with Love](https://www.cocoawithlove.com/2009/12/sample-iphone-application-with-complete.html)
  **Published:** `2009-12-27`
  **Topics:** Testing · Xcode
  **NeKI brief:** The sample iPhone application connects application lifecycle, model ownership, navigation, and view setup as one complete flow. It is useful historical evidence for locating responsibilities in UIKit-era architecture.
- [A sample Mac application with complete unit tests | Cocoa with Love](https://www.cocoawithlove.com/2009/12/sample-mac-application-with-complete.html)
  **Published:** `2009-12-21`
  **Topics:** Testing · Xcode
  **NeKI brief:** The complete Mac sample traces document, controller, and window coordination through an AppKit application. Follow it for a concrete lifecycle map when untangling legacy desktop code.
- [Multiple copy buffers, cursor and tab key tricks in Xcode | Cocoa with Love](https://www.cocoawithlove.com/2009/12/multiple-copy-buffers-cursor-and-tab.html)
  **Published:** `2009-12-12`
  **Topics:** Observation & State Management · Xcode
  **NeKI brief:** Multiple copy buffers require explicit responder routing, pasteboard selection, and cursor state rather than assuming one global clipboard. The example helps design editor interactions with deterministic command behavior.
- [The design of an iPhone application | Cocoa with Love](https://www.cocoawithlove.com/2009/12/design-of-iphone-application.html)
  **Published:** `2009-12-08`
  **Topics:** Architecture · Swift
  **NeKI brief:** iPhone application design separates navigation, state, and rendering under memory and input constraints. The discussion is useful historical context when evaluating why early UIKit patterns favor controllers and small view hierarchies.
- [There's a Garbage Collection ninja hiding in the project templates | Cocoa with Love](https://www.cocoawithlove.com/2009/12/there-garbage-collection-ninja-hiding.html)
  **Published:** `2009-12-01`
  **Topics:** Core Data · Persistence & Synchronisation · Xcode
  **NeKI brief:** Garbage collection can hide leaks while leaving resource lifetime, cycles, and responsiveness unresolved. The essay helps distinguish memory reclamation from deterministic cleanup and ownership design.
- [Writing a parser using NSScanner (a CSV parsing example) | Cocoa with Love](https://www.cocoawithlove.com/2009/11/writing-parser-using-nsscanner-csv.html)
  **Published:** `2009-11-30`
  **Topics:** Swift
  **NeKI brief:** An NSScanner CSV parser makes token boundaries, escaped fields, and error handling explicit instead of relying on naive splitting. Follow it when input syntax needs predictable recovery and testable parsing rules.
- [Performance tests: Replacing Core Data Key Paths | Cocoa with Love](https://www.cocoawithlove.com/2009/11/performance-tests-replacing-core-data.html)
  **Published:** `2009-11-21`
  **Topics:** Core Data · Performance · Persistence & Synchronisation · Testing
  **NeKI brief:** Replacing Core Data should be evaluated with representative persistence benchmarks, not assumptions about ORM overhead. The tests connect query shape, object creation, and caching behavior to measurable trade-offs.
- [A drop-in fix for the problems with NSHost | Cocoa with Love](https://www.cocoawithlove.com/2009/11/drop-in-fix-for-problems-with-nshost.html)
  **Published:** `2009-11-14`
  **Topics:** Concurrency
  **NeKI brief:** A drop-in NSHost fix addresses hostname resolution edge cases through a compatibility wrapper rather than changing callers. Follow it when legacy network failures require isolating platform behavior behind a narrow boundary.
- [Memory and thread-safe custom property methods | Cocoa with Love](https://www.cocoawithlove.com/2009/10/memory-and-thread-safe-custom-property.html)
  **Published:** `2009-10-25`
  **Topics:** Concurrency · Performance · Swift
  **NeKI brief:** A memory- and thread-safe custom property requires explicit synchronization and ownership semantics around accessors. The example helps identify why merely marking a property atomic does not protect compound operations.
- [How blocks are implemented (and the consequences) | Cocoa with Love](https://www.cocoawithlove.com/2009/10/how-blocks-are-implemented-and.html)
  **Published:** `2009-10-18`
  **Topics:** Swift · Xcode
  **NeKI brief:** Understanding block implementation exposes captures, stack-to-heap copying, and retained object lifetimes beneath closure syntax. The article is useful for diagnosing legacy Objective-C retain cycles and callback ownership.
- [Objective-C's niche: why it survives in a world of alternatives | Cocoa with Love](https://www.cocoawithlove.com/2009/10/objective-c-niche-why-it-survives-in.html)
  **Published:** `2009-10-12`
  **Topics:** Architecture
  **NeKI brief:** Objective-C's runtime messaging, Cocoa integration, and long-lived ecosystem explain its role alongside newer languages. The article is useful context when maintaining mixed-language code and choosing where interoperability is worth its cost.
- [The ugly side of blocks: explicit declarations and casting. | Cocoa with Love](https://www.cocoawithlove.com/2009/10/ugly-side-of-blocks-explicit.html)
  **Published:** `2009-10-05`
  **Topics:** Apple Platform Ecosystem · Swift
  **NeKI brief:** The explicit side of blocks shows how capture and lifetime rules can create surprising object retention. Follow it when reviewing callback APIs where convenience syntax obscures ownership and cancellation responsibility.
- [Optimizing the loading of a very large table on the iPhone | Cocoa with Love](https://www.cocoawithlove.com/2009/09/optimizing-loading-of-very-large-table.html)
  **Published:** `2009-09-28`
  **Topics:** Performance · Testing
  **NeKI brief:** Very large table loading is optimized by separating data preparation, cell reuse, and incremental display. The workflow helps distinguish loading latency from drawing cost when profiling UIKit list responsiveness.
- [WhereIsMyMac, a Snow Leopard CoreLocation project | Cocoa with Love](https://www.cocoawithlove.com/2009/09/whereismymac-snow-leopard-corelocation.html)
  **Published:** `2009-09-21`
  **Topics:** Apple Platform Ecosystem · Swift
  **NeKI brief:** Core Location on macOS combines authorization, asynchronous updates, and accuracy trade-offs rather than a synchronous coordinates lookup. The article is useful historical context for lifecycle-aware location features.
- [Building for earlier OS versions from Snow Leopard | Cocoa with Love](https://www.cocoawithlove.com/2009/09/building-for-earlier-os-versions-in.html)
  **Published:** `2009-09-16`
  **Topics:** Xcode
  **NeKI brief:** Building for earlier OS versions requires separating SDK availability, deployment target, and runtime feature checks. The guidance helps prevent code that compiles on a new SDK but crashes on supported older systems.
- [Creating alpha masks from text on the iPhone and Mac | Cocoa with Love](https://www.cocoawithlove.com/2009/09/creating-alpha-masks-from-text-on.html)
  **Published:** `2009-09-09`
  **Topics:** Graphics, Media & Games · Swift · UIKit
  **NeKI brief:** Creating alpha masks from text uses Core Graphics rendering and image compositing to turn glyph shapes into reusable transparency. Follow it when custom text effects need deterministic raster output.
- [An NSSplitView delegate for priority based resizing | Cocoa with Love](https://www.cocoawithlove.com/2009/09/nssplitview-delegate-for-priority-based.html)
  **Published:** `2009-09-01`
  **Topics:** Xcode
  **NeKI brief:** A priority-based NSSplitView delegate allocates available width according to explicit pane importance rather than default proportional resizing. The technique helps preserve critical controls in constrained desktop windows.
- [Adding shadow effects to UITableView using CAGradientLayer | Cocoa with Love](https://www.cocoawithlove.com/2009/08/adding-shadow-effects-to-uitableview.html)
  **Published:** `2009-08-21`
  **Topics:** Navigation & Deep Linking · Swift · UIKit
  **NeKI brief:** UITableView shadow effects require layering and clipping choices that preserve scrolling performance and cell reuse. The technique is useful for legacy UIKit styling where visual effects can accidentally trigger offscreen rendering.
- [Animating a window to fullscreen on the Mac | Cocoa with Love](https://www.cocoawithlove.com/2009/08/animating-window-to-fullscreen-on-mac.html)
  **Published:** `2009-08-14`
  **Topics:** Graphics, Media & Games · Swift
  **NeKI brief:** Animating a Mac window to fullscreen requires coordinating frame changes, screen bounds, and restoration state. Follow it when custom AppKit transitions must remain coherent across displays and resize events.
- [Safe, threaded design and inter-thread communication | Cocoa with Love](https://www.cocoawithlove.com/2009/08/safe-threaded-design-and-inter-thread.html)
  **Published:** `2009-08-09`
  **Topics:** Concurrency · Networking
  **NeKI brief:** Safe threaded design makes message ownership, queue crossing, and handoff timing explicit instead of sharing mutable state. The article provides a diagnostic model for intermittent cross-thread UI and data races.
- [Control and configuration of applications through Info.plist | Cocoa with Love](https://www.cocoawithlove.com/2009/08/control-and-configuration-of.html)
  **Published:** `2009-08-03`
  **Topics:** Xcode
  **NeKI brief:** Control and configuration of background work requires a clear command channel rather than mutating worker state from arbitrary threads. The pattern helps preserve cancellation and configuration invariants in legacy concurrent code.
- [Rules to avoid retain cycles | Cocoa with Love](https://www.cocoawithlove.com/2009/07/rules-to-avoid-retain-cycles.html)
  **Published:** `2009-07-27`
  **Topics:** Performance · Swift
  **NeKI brief:** Retain-cycle avoidance depends on mapping ownership edges across delegates, blocks, and parent-child objects. The rules are useful for auditing legacy Cocoa lifetimes before relying on Instruments to find leaks.
- [Temporary files and folders in Cocoa | Cocoa with Love](https://www.cocoawithlove.com/2009/07/temporary-files-and-folders-in-cocoa.html)
  **Published:** `2009-07-23`
  **Topics:** Persistence & Synchronisation · Swift
  **NeKI brief:** Temporary files and folders should use system-provided locations and unique names, with explicit cleanup ownership. The workflow helps prevent collisions, sandbox violations, and orphaned intermediate artifacts.
- [A simple, extensible HTTP server in Cocoa | Cocoa with Love](https://www.cocoawithlove.com/2009/07/simple-extensible-http-server-in-cocoa.html)
  **Published:** `2009-07-13`
  **Topics:** Architecture · Networking · Swift
  **NeKI brief:** A small extensible HTTP server in Cocoa separates parsing, routing, and connection handling behind configurable request logic. Follow it for understanding embedded-server boundaries before exposing application state over a network.
- [HashValue: an object for holding MD5 and SHA hashes | Cocoa with Love](https://www.cocoawithlove.com/2009/07/hashvalue-object-for-holding-md5-and.html)
  **Published:** `2009-07-06`
  **Topics:** Architecture · Swift
  **NeKI brief:** A hash-value object encapsulates digest bytes, equality, and presentation so callers do not manipulate raw buffers. The design is useful for comparing identifiers while keeping binary representation and encoding policy centralized.
- [Custom views in Interface Builder using IBPlugins | Cocoa with Love](https://www.cocoawithlove.com/2009/07/custom-views-in-interface-builder-using.html)
  **Published:** `2009-07-02`
  **Topics:** Xcode
  **NeKI brief:** Custom Interface Builder views need controlled initialization paths for archived and programmatic construction. The article helps prevent configuration that works in a nib but fails when the view is created in code.
- [Verifying that a string contains an email address using NSPredicate | Cocoa with Love](https://www.cocoawithlove.com/2009/06/verifying-that-string-is-email-address.html)
  **Published:** `2009-06-23`
  **Topics:** Core Data · Persistence & Synchronisation
  **NeKI brief:** Email-address validation must separate superficial syntax checks from actual mailbox verification and product policy. The discussion helps avoid regexes that reject valid addresses or imply a stronger guarantee than validation provides.
- [Revisiting an old post: Streaming and playing an MP3 stream | Cocoa with Love](https://www.cocoawithlove.com/2009/06/revisiting-old-post-streaming-and.html)
  **Published:** `2009-06-17`
  **Topics:** Concurrency · Networking · Swift
  **NeKI brief:** Revisiting audio streaming exposes how earlier buffering and transport assumptions aged with platform APIs. Follow it when maintaining historical playback code and deciding which compatibility behaviors still warrant support.
- [Method names in Objective-C | Cocoa with Love](https://www.cocoawithlove.com/2009/06/method-names-in-objective-c.html)
  **Published:** `2009-06-10`
  **Topics:** Swift
  **NeKI brief:** Objective-C method names encode argument labels as part of selector design, shaping readability and dynamic dispatch. The article helps maintain API consistency when evolving a Cocoa interface without hiding parameter meaning.
- [Base64 encoding options on the Mac and iPhone | Cocoa with Love](https://www.cocoawithlove.com/2009/06/base64-encoding-options-on-mac-and.html)
  **Published:** `2009-06-03`
  **Topics:** Persistence & Synchronisation · Swift
  **NeKI brief:** Base64 encoding choices affect line wrapping, URL safety, padding, and binary-data interoperability. The comparison is useful when a transport or persistence format silently rejects otherwise valid encoded values.
- [Simple methods for date formatting and transcoding | Cocoa with Love](https://www.cocoawithlove.com/2009/05/simple-methods-for-date-formatting-and.html)
  **Published:** `2009-05-25`
  **Topics:** Persistence & Synchronisation · Swift
  **NeKI brief:** Date formatting requires choosing calendar, locale, time zone, and input semantics explicitly; a shared formatter is not a universal conversion tool. The article helps diagnose display and parsing errors in Cocoa apps.
- [Intercepting status bar touches on the iPhone | Cocoa with Love](https://www.cocoawithlove.com/2009/05/intercepting-status-bar-touches-on.html)
  **Published:** `2009-05-19`
  **Topics:** Graphics, Media & Games · UIKit
  **NeKI brief:** Intercepting status-bar touches requires working with UIKit's event-routing assumptions rather than adding an ordinary view. The technique is useful historical context for custom gesture behavior near system-controlled areas.
- [Variable argument lists in Cocoa | Cocoa with Love](https://www.cocoawithlove.com/2009/05/variable-argument-lists-in-cocoa.html)
  **Published:** `2009-05-10`
  **Topics:** Swift
  **NeKI brief:** Variable argument lists trade call-site brevity for weaker type checking and termination conventions. Follow it when maintaining Objective-C APIs where variadic syntax may hide argument-count or ownership mistakes.
- [Invoking other processes in Cocoa | Cocoa with Love](https://www.cocoawithlove.com/2009/05/invoking-other-processes-in-cocoa.html)
  **Published:** `2009-05-04`
  **Topics:** Objective-C & Cocoa
  **NeKI brief:** Invoking another process from Cocoa requires controlled arguments, environment, output capture, and termination handling. The workflow helps avoid shell-injection and lifecycle bugs in desktop automation features.
- [Easy custom UITableView drawing | Cocoa with Love](https://www.cocoawithlove.com/2009/04/easy-custom-uitableview-drawing.html)
  **Published:** `2009-04-28`
  **Topics:** Architecture · Graphics, Media & Games · UIKit
  **NeKI brief:** Custom UITableView drawing can layer decoration without abandoning cell reuse, but must avoid expensive per-scroll rendering. The article helps balance visual customization against list performance in legacy UIKit.
- [What does it mean when you assign [super init] to self? | Cocoa with Love](https://www.cocoawithlove.com/2009/04/what-does-it-mean-when-you-assign-super.html)
  **Published:** `2009-04-18`
  **Topics:** Swift · Xcode
  **NeKI brief:** Assigning super in Objective-C has specific initializer and message-dispatch implications, not a general shortcut for parent state. The explanation helps diagnose subclass initialization and override mistakes.
- [Showing a "Loading..." message over the iPhone keyboard | Cocoa with Love](https://www.cocoawithlove.com/2009/04/showing-message-over-iphone-keyboard.html)
  **Published:** `2009-04-12`
  **Topics:** Architecture
  **NeKI brief:** Presenting a message over the iPhone keyboard requires coordinating keyboard geometry, view hierarchy, and animation timing. The technique helps avoid overlays that are obscured or jump during text editing.
- [8 Confusing Objective-C Warnings and Errors | Cocoa with Love](https://www.cocoawithlove.com/2009/04/8-confusing-objective-c-warnings-and.html)
  **Published:** `2009-04-05`
  **Topics:** Swift · Xcode
  **NeKI brief:** Confusing Objective-C warnings often reveal mismatched selectors, ownership annotations, or type conversions hidden by dynamic messaging. The examples are useful for turning compiler noise into concrete runtime-risk checks.
- [Using NSKeyedArchiver to archive a C linked-list | Cocoa with Love](https://www.cocoawithlove.com/2009/03/using-nskeyedarchiver-to-archive-c.html)
  **Published:** `2009-03-28`
  **Topics:** Persistence & Synchronisation · Swift
  **NeKI brief:** NSKeyedArchiver archives object graphs through stable keys and decoding contracts, so schema evolution requires deliberate defaults and version handling. Follow it when persisting Cocoa models across app releases.
- [Recreating UITableViewController to increase code reuse | Cocoa with Love](https://www.cocoawithlove.com/2009/03/recreating-uitableviewcontroller-to.html)
  **Published:** `2009-03-22`
  **Topics:** UIKit
  **NeKI brief:** Recreating UITableViewController behavior in a custom controller exposes how table ownership, editing, and lifecycle callbacks are coordinated. Follow it when a standard controller subclass no longer fits a specialized UIKit container.
- [Scripted window management in Xcode | Cocoa with Love](https://www.cocoawithlove.com/2009/03/scripted-window-management-in-xcode.html)
  **Published:** `2009-03-13`
  **Topics:** Xcode
  **NeKI brief:** Scripted window management in Xcode automates arrangement and focus of development tools, making workspace state repeatable. The article is useful for reducing manual context switching in multi-window workflows.
- [An Asteroids-style game in CoreAnimation, Part Four. | Cocoa with Love](https://www.cocoawithlove.com/2009/03/asteroids-style-game-in-coreanimation_08.html)
  **Published:** `2009-03-08`
  **Topics:** Performance · Testing
  **NeKI brief:** An Asteroids-style game in Core Animation treats layers, transforms, and frame updates as a lightweight rendering loop. The example helps compare retained-mode animation with a custom drawing or game engine approach.
- [An Asteroids-style game in CoreAnimation, Part Three. | Cocoa with Love](https://www.cocoawithlove.com/2009/03/asteroids-style-game-in-coreanimation.html)
  **Published:** `2009-03-01`
  **Topics:** Graphics, Media & Games · Performance
  **NeKI brief:** Core Animation game mechanics require separating model updates from layer presentation so collision and motion remain deterministic. Follow it when visual interpolation must not become the game's source of truth.
- [An Asteroids-style game in CoreAnimation, Part Two. | Cocoa with Love](https://www.cocoawithlove.com/2009/02/asteroids-style-game-in-coreanimation_22.html)
  **Published:** `2009-02-22`
  **Topics:** Graphics, Media & Games · Performance · UIKit
  **NeKI brief:** The Core Animation Asteroids follow-up explores frame updates and layer composition under an interactive workload. It is useful for understanding where rendering convenience stops and game-loop state management begins.
- [An Asteroids-style game in CoreAnimation, Part One. | Cocoa with Love](https://www.cocoawithlove.com/2009/02/asteroids-style-game-in-coreanimation.html)
  **Published:** `2009-02-17`
  **Topics:** Graphics, Media & Games · Performance
  **NeKI brief:** Use Core Animation as a 2D game's renderer behind a model-view-controller design, with a constant-aspect view for resolution independence. Keeping world coordinates separate from the window prevents display size from leaking into gameplay calculations.
- [Breadth-first traversal of a graph of Objective-C objects | Cocoa with Love](https://www.cocoawithlove.com/2009/02/breadth-first-traversal-of-graph-of.html)
  **Published:** `2009-02-07`
  **Topics:** Testing
  **NeKI brief:** Breadth-first traversal visits graph nodes in distance order using a queue and explicit visited set. The implementation is useful for hierarchy searches where recursive depth-first traversal gives the wrong route semantics.
- [Interprocess communication: snooping, intercepting and subverting | Cocoa with Love](https://www.cocoawithlove.com/2009/02/interprocess-communication-snooping.html)
  **Published:** `2009-02-01`
  **Topics:** Xcode
  **NeKI brief:** Interprocess communication snooping reveals messages at a boundary for debugging, but must preserve timing and privacy assumptions. Follow it when diagnosing opaque process interactions without modifying both endpoints.
- [Multiple virtual pages in a UIScrollView with just 2 child views | Cocoa with Love](https://www.cocoawithlove.com/2009/01/multiple-virtual-pages-in-uiscrollview.html)
  **Published:** `2009-01-23`
  **Topics:** Swift · UIKit
  **NeKI brief:** Multiple virtual UIScrollView pages manage content offsets and reusable page state to simulate a larger document. The pattern helps keep memory bounded while supporting paged navigation in legacy UIKit.
- [Demystifying NSApplication by recreating it | Cocoa with Love](https://www.cocoawithlove.com/2009/01/demystifying-nsapplication-by.html)
  **Published:** `2009-01-18`
  **Topics:** Concurrency · Swift
  **NeKI brief:** NSApplication coordinates event dispatch, activation, and responder routing across an AppKit process. The article helps locate responsibility when custom menus, windows, or application delegates behave unexpectedly.
- [Multiple row selection and editing in a UITableView | Cocoa with Love](https://www.cocoawithlove.com/2009/01/multiple-row-selection-and-editing-in.html)
  **Published:** `2009-01-10`
  **Topics:** UIKit
  **NeKI brief:** Multiple table-row selection and editing require consistent selection identity, edit state, and mutation ordering. The guide is useful for legacy UIKit tables where batch actions interact with user edits.
- [Serving an NSManagedObjectContext over an NSConnection | Cocoa with Love](https://www.cocoawithlove.com/2009/01/serving-nsmanagedobjectcontext-over.html)
  **Published:** `2009-01-05`
  **Topics:** Core Data · Networking · Persistence & Synchronisation
  **NeKI brief:** Serving an NSManagedObjectContext over a boundary exposes why contexts are not thread-safe data services. Follow it when designing a persistence interface that must pass IDs or values instead of live managed objects.
- [Heterogeneous cells in a UITableViewController | Cocoa with Love](https://www.cocoawithlove.com/2008/12/heterogeneous-cells-in.html)
  **Published:** `2008-12-27`
  **Topics:** UIKit
  **NeKI brief:** Heterogeneous table cells require a data model that selects reuse identifiers and configuration paths predictably. The pattern helps avoid branching cell logic that breaks reuse or row-height calculation.
- [OrderedDictionary: Subclassing a Cocoa class cluster | Cocoa with Love](https://www.cocoawithlove.com/2008/12/ordereddictionary-subclassing-cocoa.html)
  **Published:** `2008-12-18`
  **Topics:** Architecture · Swift
  **NeKI brief:** An ordered dictionary combines key lookup with stable insertion order, forcing explicit choices about mutation and enumeration semantics. The article is useful when an ordinary dictionary cannot preserve presentation order.
- [Drawing a custom window on Mac OS X | Cocoa with Love](https://www.cocoawithlove.com/2008/12/drawing-custom-window-on-mac-os-x.html)
  **Published:** `2008-12-12`
  **Topics:** Graphics, Media & Games · Swift
  **NeKI brief:** Custom Mac window drawing coordinates frame view rendering, title-bar behavior, and window controls without discarding AppKit lifecycle. Follow it when branding a desktop window while retaining system interactions.
- [Instance variable to synthesized property (an Xcode user script) | Cocoa with Love](https://www.cocoawithlove.com/2008/12/instance-variable-to-synthesized.html)
  **Published:** `2008-12-06`
  **Topics:** Xcode
  **NeKI brief:** Synthesized Objective-C properties connect accessor methods to backing ivars, with naming and ownership decisions affecting subclass behavior. The article helps diagnose property state that appears disconnected from its expected storage.
- [Method invocation formatting styles in Objective-C | Cocoa with Love](https://www.cocoawithlove.com/2008/11/method-invocation-formatting-styles-in.html)
  **Published:** `2008-11-29`
  **Topics:** Swift
  **NeKI brief:** Objective-C method-invocation formatting affects selector readability and how arguments convey roles at call sites. The discussion helps maintain API consistency in dynamic Cocoa codebases.
- [Automated user interface testing on the iPhone | Cocoa with Love](https://www.cocoawithlove.com/2008/11/automated-user-interface-testing-on.html)
  **Published:** `2008-11-23`
  **Topics:** Testing
  **NeKI brief:** Automated UI testing drives application controls through repeatable interactions, requiring stable accessibility and deterministic setup. Follow it when manual regression coverage must become an executable behavior contract.
- [Singletons, AppDelegates and top-level data. | Cocoa with Love](https://www.cocoawithlove.com/2008/11/singletons-appdelegates-and-top-level.html)
  **Published:** `2008-11-16`
  **Topics:** Dependency Injection
  **NeKI brief:** Singletons and app delegates centralize process-wide state but can obscure dependencies and test setup. The discussion helps decide which responsibilities are truly global and which should be injected explicitly.
- [Simplifying your code using NSDictionary | Cocoa with Love](https://www.cocoawithlove.com/2008/11/simplifying-your-code-using.html)
  **Published:** `2008-11-10`
  **Topics:** Swift
  **NeKI brief:** Replace state-dependent conditional trees with dictionaries that map states to data and behavior. This makes repetitive program choices declarative, but it moves type checking and discoverability from compiler-visible branches into carefully validated configuration.
- [Using libxml2 for XML parsing and XPath queries in Cocoa | Cocoa with Love](https://www.cocoawithlove.com/2008/10/using-libxml2-for-parsing-and-xpath.html)
  **Published:** `2008-10-31`
  **Topics:** Networking
  **NeKI brief:** Wrap libxml2's C tree and XPath APIs in Cocoa-oriented objects when NSXMLDocument is unavailable or too heavyweight. The approach preserves tree querying while making ownership, project linking, and libxml2's awkward documentation explicit integration concerns.
- [Debugging tips for Objective-C programming | Cocoa with Love](https://www.cocoawithlove.com/2008/10/debugging-tips-for-objective-c.html)
  **Published:** `2008-10-25`
  **Topics:** Xcode
  **NeKI brief:** Use debugger commands deliberately: print Objective-C objects, inspect raw values, map addresses back to symbols, and add data formatters where default displays obscure state. Crash-log symbolication and interactive inspection answer different diagnostic questions.
- [Synthesizing a touch event on the iPhone | Cocoa with Love](https://www.cocoawithlove.com/2008/10/synthesizing-touch-event-on-iphone.html)
  **Published:** `2008-10-17`
  **Topics:** Testing
  **NeKI brief:** Programmatically construct touch and event objects through categories to drive an interface for testing, then dispatch the resulting event through the normal responder path. This relies on private behavior, so testing convenience carries distribution and compatibility risk.
- [WorldTimeConverter: Dates and timezones in Cocoa | Cocoa with Love](https://www.cocoawithlove.com/2008/10/worldtimeconverter-dates-and-timezones.html)
  **Published:** `2008-10-10`
  **Topics:** Swift
  **NeKI brief:** Foundation date values are absolute instants; timezone conversion depends on applying the correct calendar and offset for the chosen future date. Keep date picking, conversion logic, and presentation in separate controller responsibilities to avoid current-time assumptions.
- [Sliding UITextFields around to avoid the keyboard | Cocoa with Love](https://www.cocoawithlove.com/2008/10/sliding-uitextfields-around-to-avoid.html)
  **Published:** `2008-10-03`
  **Topics:** Swift · UIKit
  **NeKI brief:** Track the active text field through delegate callbacks and shift a containing view only far enough to keep it visible above the keyboard. A hidden measurement field converts keyboard overlap into a reliable layout adjustment rather than hard-coded offsets.
- [Streaming and playing an MP3 stream | Cocoa with Love](https://www.cocoawithlove.com/2008/09/streaming-and-playing-live-mp3-stream.html)
  **Published:** `2008-09-28`
  **Topics:** Graphics, Media & Games · Networking · Testing
  **NeKI brief:** Extend AudioFileStreamExample into a Cocoa app that incrementally receives, parses, queues, and plays remote MP3 data. The implementation documents stream-buffer boundaries and a crash workaround, showing that live audio needs defensive handling beyond a local-file player.
- [A Cocoa application driven by HTTP data | Cocoa with Love](https://www.cocoawithlove.com/2008/09/cocoa-application-driven-by-http-data.html)
  **Published:** `2008-09-20`
  **Topics:** Networking · Swift
  **NeKI brief:** Structure a small Cocoa client as fetch, parse/search, format, then present: each HTTP response stage has one transformation responsibility. Keeping transport, HTML extraction, and UI output separate makes a dashboard-style data application easier to diagnose and replace.
- [Drawing gloss gradients in CoreGraphics | Cocoa with Love](https://www.cocoawithlove.com/2008/09/drawing-gloss-gradients-in-coregraphics.html)
  **Published:** `2008-09-13`
  **Topics:** Graphics, Media & Games
  **NeKI brief:** Derive every stop in a gloss gradient from one base color, then render the composed effect with Core Graphics. Encapsulating highlight and caustic calculations in one function produces consistent chrome while allowing the base palette to vary.
- [Parametric acceleration curves in Core Animation | Cocoa with Love](https://www.cocoawithlove.com/2008/09/parametric-acceleration-curves-in-core.html)
  **Published:** `2008-09-09`
  **Topics:** Graphics, Media & Games · Swift
  **NeKI brief:** CAMediaTimingFunction only covers a limited family of easing curves. Sample a desired parametric curve into CAKeyframeAnimation values when the motion profile matters, accepting more generated keyframes in exchange for exact acceleration behavior.
- [Application Design in AppKit | Cocoa with Love](https://www.cocoawithlove.com/2008/08/application-design-in-appkit.html)
  **Published:** `2008-08-31`
  **Topics:** Architecture
  **NeKI brief:** Explain AppKit applications through concrete responsibilities beyond a generic MVC label: model objects, controllers, views, windows, and delegates communicate across distinct ownership boundaries. Mapping a real app onto those roles exposes where coordination should live.
- [Safely fetching an NSManagedObject by URI | Cocoa with Love](https://www.cocoawithlove.com/2008/08/safely-fetching-nsmanagedobject-by-uri.html)
  **Published:** `2008-08-24`
  **Topics:** Core Data · Swift
  **NeKI brief:** Persist a managed object's URI representation when crossing context boundaries, but treat resolving it as fallible because stores, contexts, and deleted objects can invalidate the apparent reference. Validate the persistent-store coordinator's result before using it.
- [In defense of Objective-C 2.0 Properties | Cocoa with Love](https://www.cocoawithlove.com/2008/08/in-defense-of-objective-c-20-properties.html)
  **Published:** `2008-08-16`
  **Topics:** Objective-C & Cocoa
  **NeKI brief:** Objective-C properties define an interface-level access contract, not merely generated accessors or dot syntax. Declaring that contract lets callers use a stable abstraction while implementations retain freedom over storage, validation, and derived values.
- [NSArray or NSSet, NSDictionary or NSMapTable | Cocoa with Love](https://www.cocoawithlove.com/2008/08/nsarray-or-nsset-nsdictionary-or.html)
  **Published:** `2008-08-09`
  **Topics:** Performance
  **NeKI brief:** Choose Cocoa collections by uniqueness, ordering, lookup needs, and measured workload rather than interchangeable syntax. Arrays, sets, dictionaries, and map tables encode different guarantees; a benchmark identifies when a semantically valid alternative also changes cost.
- [String philosophies: char arrays, std::string and NSString | Cocoa with Love](https://www.cocoawithlove.com/2008/08/string-philosophies-char-arrays.html)
  **Published:** `2008-08-02`
  **Topics:** Swift
  **NeKI brief:** C arrays, std::string, and NSString differ in representation and in whether operations favor aggregate or iterative processing. Select the string type from ownership, encoding, interoperability, and workload semantics instead of translating APIs by superficial syntax.
- [Key Value Information | Cocoa with Love](https://www.cocoawithlove.com/2008/07/key-value-information.html)
  **Published:** `2008-07-27`
  **Topics:** Core Data · Observation & State Management · Persistence & Synchronisation
  **NeKI brief:** KVC dynamically resolves accessor methods but does not directly expose an object's complete supported-key contract. Inspecting classes and accessors can reveal likely keys, yet dynamic resolution means runtime behavior remains more authoritative than reflection alone.
- [Better integration for NSViewController and NSView | Cocoa with Love](https://www.cocoawithlove.com/2008/07/better-integration-for-nsviewcontroller.html)
  **Published:** `2008-07-21`
  **Topics:** UIKit
  **NeKI brief:** NSViewController loads a nib-backed view but lacks some NSWindowController-style lifecycle integration. Add explicit coordination between view loading, ownership, and embedding so outlet initialization and presentation decisions do not leak across arbitrary callers.
- [CoreGraphics curves and lines: a sample app | Cocoa with Love](https://www.cocoawithlove.com/2008/07/coregraphics-curves-and-lines-sample.html)
  **Published:** `2008-07-12`
  **Topics:** Graphics, Media & Games
  **NeKI brief:** A small Core Graphics sample exposes line and curve primitives through draggable control points, turning geometry into observable behavior. Interactive handles make Bézier parameters and endpoint relationships easier to validate than static drawing code alone.
- [NSMapTable: more than an NSDictionary for weak pointers | Cocoa with Love](https://www.cocoawithlove.com/2008/07/nsmaptable-more-than-nsdictionary-for.html)
  **Published:** `2008-07-06`
  **Topics:** Swift
  **NeKI brief:** NSMapTable is not merely a weak-key NSDictionary substitute: its pointer and object personality options support mappings NSDictionary cannot safely express. Select its memory semantics intentionally, because weak associations solve retention issues but can disappear during lookup.
- [Hidden Xcode build, debug and template settings | Cocoa with Love](https://www.cocoawithlove.com/2008/06/hidden-xcode-build-debug-and-template.html)
  **Published:** `2008-06-28`
  **Topics:** Macros & Metaprogramming · Xcode
  **NeKI brief:** Xcode behavior is shaped by build settings, scripts, launch arguments, environment variables, and template macros beyond visible target controls. Keep such customization discoverable and versioned where possible, since hidden per-user settings undermine reproducible builds.
- [Doing things in Cocoa with "nil" | Cocoa with Love](https://www.cocoawithlove.com/2008/06/doing-things-in-cocoa-with.html)
  **Published:** `2008-06-21`
  **Topics:** Architecture · Swift
  **NeKI brief:** Objective-C permits messaging nil and initializes many scalar values to zero, simplifying optional-object flows. That convenience does not extend to collection values, where NSNull represents absence explicitly and prevents a nil insertion from changing the operation's meaning.
- [Speed test: NSManagedObject ObjC-2.0 accessors | Cocoa with Love](https://www.cocoawithlove.com/2008/06/speed-test-nsmanagedobject-objc-20.html)
  **Published:** `2008-06-13`
  **Topics:** Performance · Testing
  **NeKI brief:** Compare the available NSManagedObject property-access styles with a focused relative benchmark before optimizing generated accessors. Core Data's dynamic behavior means convenience syntax and direct access may differ in cost, but measurements must match the workload.
- [Five approaches to listening, observing and notifying in Cocoa. | Cocoa with Love](https://www.cocoawithlove.com/2008/06/five-approaches-to-listening-observing.html)
  **Published:** `2008-06-07`
  **Topics:** Architecture · Persistence & Synchronisation · Swift
  **NeKI brief:** Compare manual listeners, KVO, notification centers, context notifications, and delegates by who owns the relationship and how broadly events fan out. Selecting the mechanism is an abstraction decision: direct delegation trades flexibility for clearer contracts.
- [Adapter interfaces in Objective-C, using categories. | Cocoa with Love](https://www.cocoawithlove.com/2008/05/adapter-interfaces-in-objective-c-using.html)
  **Published:** `2008-05-24`
  **Topics:** Architecture · Dependency Injection · Swift
  **NeKI brief:** Objective-C categories can provide an adapter interface that lets two classes collaborate without mutual implementation dependencies. The pattern narrows coupling at the API boundary, but method-name collisions and undiscoverable category behavior require disciplined naming.
- [Implementing countByEnumeratingWithState:objects:count: | Cocoa with Love](https://www.cocoawithlove.com/2008/05/implementing-countbyenumeratingwithstat.html)
  **Published:** `2008-05-19`
  **Topics:** Persistence & Synchronisation · Swift
  **NeKI brief:** Implement NSFastEnumeration by reporting mutation state, filling the caller's object buffer, and advancing the enumeration state correctly. The two examples distinguish wrapping existing contiguous storage from allocating temporary storage, where lifetime management becomes essential.
- [Objective-C 2.0: Fast enumeration clarifications | Cocoa with Love](https://www.cocoawithlove.com/2008/05/fast-enumeration-clarifications.html)
  **Published:** `2008-05-15`
  **Topics:** Swift
  **NeKI brief:** Fast enumeration improves loop syntax and performance but its mutation and buffer behavior has important caveats. Understand what the runtime detects and what it does not before relying on enumeration over collections that may change during iteration.
- [Square Root: Numerical fun with NSDecimalNumber | Cocoa with Love](https://www.cocoawithlove.com/2008/05/square-root-numerical-fun-with.html)
  **Published:** `2008-05-09`
  **Topics:** Swift
  **NeKI brief:** Extend NSDecimalNumber with a square-root algorithm when decimal precision matters more than binary floating-point convenience. Define convergence and special-case handling explicitly; numerical correctness depends on rounding and invalid-input behavior as much as the iteration itself.
- [Open the previous document on application startup | Cocoa with Love](https://www.cocoawithlove.com/2008/05/open-previous-document-on-application.html)
  **Published:** `2008-05-02`
  **Topics:** Objective-C & Cocoa
  **NeKI brief:** Use the application delegate and recent-document support to reopen the last document at launch rather than presenting a blank untitled window. Make startup restoration conditional so an explicit user-open request is not overridden by automatic document selection.
- [Propagate deletes immediately in Core Data | Cocoa with Love](https://www.cocoawithlove.com/2008/04/propagate-deletes-immediately-in-core.html)
  **Published:** `2008-04-25`
  **Topics:** Core Data · Persistence & Synchronisation
  **NeKI brief:** Core Data cascade deletes may not update dependent graph state at the moment an app expects. Perform required relationship cleanup deliberately before saving when UI or business logic needs immediate consistency, then let the persistent store commit the final transaction.
- [viewWillDraw - a welcome addition to NSView in 10.5 | Cocoa with Love](https://www.cocoawithlove.com/2008/04/viewwilldraw-welcome-addition-to-nsview.html)
  **Published:** `2008-04-20`
  **Topics:** Graphics, Media & Games · Swift
  **NeKI brief:** NSView's viewWillDraw consolidates older layout and drawing-preparation hooks into one pre-draw point. Put geometry-dependent preparation there when it must reflect final layout, rather than scattering equivalent work through obsolete callbacks.
- [Type punning isn't funny: Using pointers to recast in C is bad. | Cocoa with Love](https://www.cocoawithlove.com/2008/04/using-pointers-to-recast-in-c-is-bad.html)
  **Published:** `2008-04-14`
  **Topics:** Macros & Metaprogramming
  **NeKI brief:** Pointer type punning can violate aliasing and representation assumptions, producing compiler-dependent bugs. Use a union or controlled byte-level conversion when reinterpretation is unavoidable, and never assume visually similar structs are safely interchangeable in memory.
- [The value of immutable values | Cocoa with Love](https://www.cocoawithlove.com/2008/04/value-of-immutable-values.html)
  **Published:** `2008-04-06`
  **Topics:** Swift
  **NeKI brief:** Immutable value objects make equality, sharing, and collection use predictable because callers cannot silently change the represented value. Prefer immutability by default, then introduce mutation only when copying or replacement would be materially impractical.
- [Supersequent implementation | Cocoa with Love](https://www.cocoawithlove.com/2008/03/supersequent-implementation.html)
  **Published:** `2008-03-30`
  **Topics:** Macros & Metaprogramming
  **NeKI brief:** Category method overrides and swizzling complicate reaching the implementation that previously handled a selector. A supersequent technique can traverse that chain, but it relies on runtime internals and should remain a constrained compatibility tool rather than normal dispatch.
- [Testing Core Data with very big hierarchical data sets | Cocoa with Love](https://www.cocoawithlove.com/2008/03/testing-core-data-with-very-big.html)
  **Published:** `2008-03-28`
  **Topics:** Core Data · Performance · Persistence & Synchronisation · Testing
  **NeKI brief:** Benchmark Core Data with a realistic large hierarchy across creation, load, fetch, and traversal phases instead of inferring scale from small fixtures. Split measurements by operation so indexing, faulting, and relationship walking bottlenecks are distinguishable.
- [Construct an NSInvocation for any message, just by sending | Cocoa with Love](https://www.cocoawithlove.com/2008/03/construct-nsinvocation-for-any-message.html)
  **Published:** `2008-03-19`
  **Topics:** Architecture · Swift
  **NeKI brief:** Use Objective-C message forwarding to capture a selector and arguments as NSInvocation without manually assembling a signature. This can record even broad message sets, but forwarding changes dispatch behavior and needs careful handling of return values.
- [Cocoa Application Startup | Cocoa with Love](https://www.cocoawithlove.com/2008/03/cocoa-application-startup.html)
  **Published:** `2008-03-14`
  **Topics:** Objective-C & Cocoa
  **NeKI brief:** Cocoa startup proceeds through Objective-C runtime initialization, NSApplication setup, nib loading, and document loading. Put initialization in the phase matching its dependencies; code that touches outlets or documents too early creates lifecycle-order failures.
- [Break into Debugger | Cocoa with Love](https://www.cocoawithlove.com/2008/03/break-into-debugger.html)
  **Published:** `2008-03-09`
  **Topics:** Macros & Metaprogramming
  **NeKI brief:** A platform-aware DebugBreak macro deliberately traps at the caller's source line, avoiding an extra helper-frame detour during diagnosis. Guard such diagnostics for development builds and architectures so debugging instrumentation never becomes production behavior.
- [Core Data: one line fetch | Cocoa with Love](https://www.cocoawithlove.com/2008/03/core-data-one-line-fetch.html)
  **Published:** `2008-03-07`
  **Topics:** Core Data · Persistence & Synchronisation
  **NeKI brief:** A concise Core Data fetch helper can remove boilerplate for ordinary queries while retaining the framework's predicate and context semantics. Do not let one-line convenience hide error handling, fetch limits, batching, or memory behavior needed by larger datasets.
- [IMP of the current method | Cocoa with Love](https://www.cocoawithlove.com/2008/02/imp-of-current-method.html)
  **Published:** `2008-02-25`
  **Topics:** Swift
  **NeKI brief:** An IMP is the runtime function pointer implementing an Objective-C selector; accessing the current method's IMP requires runtime-aware techniques rather than ordinary C function references. Such introspection is obscure and should be isolated from application-level logic.
