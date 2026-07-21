# Jacob’s Tech Tavern

Third-party source index. It provides source attribution and routing metadata, not republished article content. Verify article conclusions independently before applying them.

- Archive: [https://blog.jacobstechtavern.com/archive](https://blog.jacobstechtavern.com/archive)
- Last collected: `2026-07-22T14:10:28Z`
- Indexed entries: **88**

## [Apple's "Snow Leopard" Year: WWDC 2026 Roundup](https://blog.jacobstechtavern.com/p/wwdc-2026-roundup)

- Published: `2026-06-11T12:03:43.079Z`

**NeKI brief:** Summarizes the author's WWDC 2026 takeaways across Apple-platform announcements and developer tooling. Use it as a discovery index before reading the corresponding sessions and documentation, not as an authoritative feature reference.

## [Apple Chip Architecture from 1977 to 2026](https://blog.jacobstechtavern.com/p/apple-chip-architecture)

- Published: `2026-06-09T15:02:45.323Z`

**Topics:** Architecture

**Sections:** Contents · 1977 · 1984

**NeKI brief:** Connects Apple chip evolution to mobile software constraints, explaining why CPU, GPU, neural, memory, and power architecture influence rendering, machine-learning, and performance choices beyond simple benchmark comparisons.

## [Touch to Pixels: UI Pipeline Internals on iOS](https://blog.jacobstechtavern.com/p/ui-pipeline-internals)

- Published: `2026-05-13T15:03:01.053Z`

**Sections:** Handling Physical Touch · Core Animation inside your app · Compositing, Animating, and Displaying

**NeKI brief:** Trace an iOS interaction from event delivery through main-thread state updates, layout, Core Animation transaction commit, render-server work, and GPU presentation. Use that pipeline to classify a hitch as input, CPU, layout, transaction, or rendering work before optimizing the wrong stage.

## [URLSession to Electrons: How Networking works on iOS](https://blog.jacobstechtavern.com/p/urlsession-to-electrons)

- Published: `2026-04-28T15:03:29.486Z`

**Topics:** Networking

**Sections:** Jacob’s Tech Tavern · Contents · What is the Internet?

**NeKI brief:** A layered networking deep dive that follows URLSession requests down through the Internet stack to the underlying hardware.

## [The 7 Deadly Sins of Cargo Culting](https://blog.jacobstechtavern.com/p/the-7-deadly-sins-of-cargo-culting)

- Published: `2026-04-14T15:03:03.506Z`

**Sections:** 👑 Pride · 🤑 Greed · 🧨 Wrath

**NeKI brief:** Adopt an iOS pattern only after understanding its data ownership, lifecycle, concurrency, and failure assumptions. Replace copied architectural rituals with a concrete problem statement and observable success criteria, so abstractions remain justified when the codebase or platform changes.

## [Survive the AI tech hiring winter ⛄️](https://blog.jacobstechtavern.com/p/survive-the-ai-tech-hiring-winter)

- Published: `2026-04-06T15:03:00.398Z`

**NeKI brief:** A career-focused perspective on the AI-era hiring market; use it for individual context, not technical decision-making.

## [Is SwiftUI finally as fast as UIKit in iOS 26?](https://blog.jacobstechtavern.com/p/swiftui-vs-uikit)

- Published: `2026-03-09T16:01:18.122Z`

**Topics:** Swift · SwiftUI · Performance · UIKit · Testing

**Sections:** Designing the most ridiculous scroll view I can imagine · A fair test · SwiftUI performance (feat. List)

**NeKI brief:** Compare SwiftUI and UIKit performance with equivalent view hierarchies, realistic data, and measured scrolling or interaction workloads. Use profiling evidence to locate layout, diffing, or rendering bottlenecks, then bridge to UIKit only where a specific capability or performance constraint requires it.

## [Agentic AI Engineering Workflows for iOS in 2026](https://blog.jacobstechtavern.com/p/agentic-ai-2026)

- Published: `2026-02-09T16:02:05.965Z`

**Topics:** AI Development

**Sections:** Contents · The State of the Art · Cargo-Culting the Creator of Claude Code

**NeKI brief:** Frames agentic iOS workflows around bounded tool access, reviewable changes, and feedback loops, helping teams distinguish useful automation from uncontrolled code generation and retain ownership of architecture, testing, and release decisions.

## [How to design an SDK to handle $10bn in transactions](https://blog.jacobstechtavern.com/p/revenuecat-sdk)

- Published: `2026-01-12T16:01:24.245Z`

**Sections:** Contents · High-Level System Design · How to make a Purchase

**NeKI brief:** Explains SDK design under high transaction volume through resilient networking, idempotency, caching, observability, and compatibility boundaries, showing how a client library protects product flows while backend systems absorb scale and failure.

## [Copy-on-write teaches you EVERYTHING about Swift Internals 🐮](https://blog.jacobstechtavern.com/p/copy-on-write-swift-internals)

- Published: `2025-12-15T16:01:29.247Z`

**Topics:** Swift · Performance

**Sections:** Journey to the centre of the 🐮 · What is 🐮? · Value and reference semantics

**NeKI brief:** Uses copy-on-write storage to expose Swift value semantics, uniqueness checks, heap allocation, and mutation behavior, helping developers reason about when apparently cheap collection copies actually trigger expensive duplication.

## [Method Dispatch in Swift: The Complete Guide](https://blog.jacobstechtavern.com/p/swift-method-dispatch)

- Published: `2025-12-01T16:02:54.698Z`

**Topics:** Swift

**Sections:** Inlining · Static Dispatch · Dynamic Dispatch

**NeKI brief:** Choose Swift dispatch with awareness of the call site: class inheritance, protocol requirements, protocol-extension members, generics, and final declarations do not share identical dispatch behavior. Diagnose surprising overrides by checking the static type and witness-table boundary before applying performance-oriented modifiers.

## [When To Kill A Project](https://blog.jacobstechtavern.com/p/when-to-kill-a-project)

- Published: `2025-11-20T16:01:51.473Z`

**Topics:** Swift · Swift Package Manager

**Sections:** iOS Dev Survey · Tackle Fishing · AppReviewTimes

**NeKI brief:** Discusses signals and decision criteria for ending an app project when its costs, risks, or opportunity trade-offs no longer make sense. Useful as a product-engineering reflection before continuing sunk-cost work or reallocating a small team.

## [2025: The Year SwiftUI Died](https://blog.jacobstechtavern.com/p/the-year-swiftui-died)

- Published: `2025-11-17T16:03:10.524Z`

**Topics:** Swift · SwiftUI · UIKit · Architecture

**Sections:** 2019: Early adoption · 2025: The summer everything changed · Why do people use iOS?

**NeKI brief:** Examines SwiftUI production pain points through a 2025 retrospective, separating framework limitations from architectural misuse and identifying when teams should stabilize state, navigation, rendering, and interoperability boundaries instead of blaming declarative UI wholesale.

## [The Great Connection Pool Meltdown](https://blog.jacobstechtavern.com/p/the-great-connection-pool-meltdown)

- Published: `2025-11-06T16:02:23.569Z`

**NeKI brief:** Analyses a production connection-pool failure and the cascading effects of saturation, retries, and recovery. Follow it for distributed-systems failure signals that can inform networking diagnostics in mobile backends.

## [Swift for Android vs. Kotlin Multiplatform](https://blog.jacobstechtavern.com/p/swift-for-android-vs-kmp)

- Published: `2025-11-03T16:20:36.220Z`

**Topics:** Swift

**Sections:** tl;dr · The bit with lots of code to keep you awake · Cross-platform module code

**NeKI brief:** Evaluate Swift-for-Android and Kotlin Multiplatform by separating shared domain logic from platform-specific UI, tooling, and operational costs. Treat both as evolving portability strategies, validate their build and debugging workflows early, and avoid assuming shared code removes native platform ownership.

## [Backend-driven SwiftUI](https://blog.jacobstechtavern.com/p/backend-driven-swiftui)

- Published: `2025-10-20T17:47:04.435Z`

**Topics:** Swift · SwiftUI

**Sections:** Why would you want Backend-driven UI? · Building backend-driven UI · When Not To Use Backend-driven UI

**NeKI brief:** Designs backend-driven SwiftUI as a schema-to-component pipeline, separating server-provided configuration from locally owned rendering and interaction rules so remote flexibility does not turn into untyped, untestable view logic.

## [Make Loading Screens Fun with the SwiftUI Game Engine](https://blog.jacobstechtavern.com/p/swiftui-game-engine)

- Published: `2025-10-06T15:00:57.466Z`

**Topics:** Swift · SwiftUI

**Sections:** What is a Game Engine? · Anatomy of the SwiftUI Game Engine · Building a Game: Flappy Bird Clone

**NeKI brief:** Build a lightweight SwiftUI loading interaction from explicit game state, timed updates, and composable drawing rather than blocking the main interface. Keep the experience optional and accessible, and separate the animation loop from the real loading task so progress and cancellation remain truthful.

## [The Terrible Technical Architecture of my First Startup](https://blog.jacobstechtavern.com/p/my-terrible-startup-architecture)

- Published: `2025-09-22T16:00:36.176Z`

**Topics:** Architecture

**Sections:** Era I: Bootstrapping · Era II: Angel Round · What I Should Have Done

**NeKI brief:** Use an early product architecture retrospective to identify where client, backend, data, and deployment boundaries became expensive to change. Introduce modular seams, observability, and migration paths around demonstrated pressure points rather than importing enterprise complexity before the product needs it.

## [Automate all the things with Swift Subprocess](https://blog.jacobstechtavern.com/p/swift-subprocess)

- Published: `2025-09-08T15:01:47.274Z`

**Topics:** Swift

**Sections:** A primer on scripting · Swift Scripting · swift-subprocess

**NeKI brief:** Uses Swift Subprocess to launch commands, stream standard output and errors, pass structured input, and handle termination, providing a concurrency-aware foundation for developer automation without hand-rolled Process plumbing.

## [Bits & Side Tables: How Reference Counting Works in Swift](https://blog.jacobstechtavern.com/p/swift-reference-counting)

- Published: `2025-08-25T15:02:22.684Z`

**Topics:** Swift

**Sections:** Quick primer on the Swift Runtime · Strong References & Bit Counting · Weak References & Side Tables

**NeKI brief:** Explains Swift ARC through object metadata, inline reference counts, and side tables, clarifying how strong, weak, and unowned references affect lifetime, performance, and debugging of unexpected retained objects.

## [Advanced Keyframe Animations in SwiftUI](https://blog.jacobstechtavern.com/p/swiftui-keyframe-animations)

- Published: `2025-08-11T15:02:07.592Z`

**Topics:** Swift · SwiftUI

**Sections:** Etymology: What is a keyframe? · Under the hood of Keyframes · Practical Keyframe Animations

**NeKI brief:** Uses SwiftUI keyframe animation tracks to coordinate multi-property motion over explicit timing segments, making complex transitions inspectable while preserving a clear relationship between animatable state, easing curves, and view updates.

## [My ADHD vs. the AlarmKit API - by Jacob Bartlett](https://blog.jacobstechtavern.com/p/adhd-vs-alarmkit)

- Published: `2025-07-28T21:00:20.731Z`

**Topics:** Testing

**Sections:** Jacob’s Tech Tavern · My ADHD vs. the AlarmKit API · How AlarmKit works under the hood

**NeKI brief:** Explores the new AlarmKit API from the perspective of building a real reminder experience and understanding its underlying behavior.

## [High Performance SwiftData Apps - by Jacob Bartlett](https://blog.jacobstechtavern.com/p/high-performance-swiftdata)

- Published: `2025-07-14T15:02:48.303Z`

**Topics:** Swift · Persistence & Synchronisation · SwiftData · Performance · SwiftUI

**Sections:** Jacob’s Tech Tavern · High Performance SwiftData Apps · Diagnosing the Problem

**NeKI brief:** Investigates SwiftData performance problems through measurements and diagnosis rather than assuming the model layer is free. Use it to identify query, observation, and persistence costs before changing an app's storage design.

## [Data: a swift-foundation deep-dive](https://blog.jacobstechtavern.com/p/data-deep-dive)

- Published: `2025-06-30T15:01:34.347Z`

**Topics:** Swift

**Sections:** Foundation and swift-foundation · Data · Data Optimisations

**NeKI brief:** Investigates Foundation Data as a byte-storage abstraction, covering ownership, slicing, mutation, bridging, and binary parsing so performance-sensitive code can avoid accidental copies and unsafe assumptions about contiguous memory.

## [Real-time systems with Combine and WebSockets](https://blog.jacobstechtavern.com/p/combine-vs-websockets)

- Published: `2025-06-16T14:02:50.719Z`

**Topics:** Networking

**Sections:** What are WebSockets? · Our App’s WebSocket Service · Connected Thermostat

**NeKI brief:** Model a WebSocket feed as a stream with explicit connection, decoding, error, cancellation, and reconnection behavior, then compose downstream updates through Combine. Keep transport lifetime separate from UI subscriptions so reconnect policy and backpressure do not become accidental view-state behavior.

## [I trapped your soul in a trading card (with client-side AI)](https://blog.jacobstechtavern.com/p/i-turned-you-into-a-trading-card)

- Published: `2025-06-02T15:02:23.930Z`

**Sections:** The Concept · Implementing CLIP & client-side AI · Trading Card Graphics

**NeKI brief:** Builds a client-side AI trading-card experience by combining user input, image or model generation, and local presentation, highlighting privacy, prompt handling, and capability constraints when inference occurs on device.

## [Advanced Swift Concurrency: AsyncStream - by Jacob Bartlett](https://blog.jacobstechtavern.com/p/async-stream)

- Published: `2025-05-19T15:01:49.012Z`

**Topics:** Concurrency · Swift

**Sections:** Jacob’s Tech Tavern · Advanced Swift Concurrency: AsyncStream · Conclusion

**NeKI brief:** Explains where AsyncStream fits in Swift Concurrency and how to use it for asynchronous event sequences.

## [SwiftUI Scroll Performance: The 120FPS Challenge](https://blog.jacobstechtavern.com/p/swiftui-scroll-performance-the-120fps)

- Published: `2025-05-05T15:00:38.653Z`

**Topics:** Performance · Architecture · Swift · SwiftUI

**Sections:** Scroll Architecture · Going Further with Performance · Last Orders

**NeKI brief:** Profile SwiftUI scrolling against the frame budget, especially on high-refresh-rate devices, and reduce unnecessary state changes, layout work, and view identity churn. Use Instruments and realistic data to find hitches before replacing declarative structure with imperative optimizations.

## [Fitting the Lapse experience into 15 MegaBytes](https://blog.jacobstechtavern.com/p/get-lapse-under-15mb)

- Published: `2025-04-21T14:02:35.921Z`

**Sections:** Jacob’s Tech Tavern · Static, Dynamic, Mergeable, oh, my!

**NeKI brief:** Describes reducing an App Clip to a 15 MB footprint through resource and dependency choices. It is a concrete optimization case study for size-constrained targets; recheck current App Clip limits before applying it.

## [Handle Deep Links with Async Algorithms](https://blog.jacobstechtavern.com/p/deep-links-with-async-algorithms)

- Published: `2025-03-24T16:02:06.309Z`

**Topics:** Concurrency · Navigation & Deep Linking

**NeKI brief:** Models deep links as asynchronous event streams and composes routing with Async Algorithms, making navigation ordering, cancellation, and multi-step dependencies explicit instead of scattering URL handling across view lifecycle callbacks.

## [How To Release Without Fear](https://blog.jacobstechtavern.com/p/release-without-fear)

- Published: `2025-03-10T16:01:09.054Z`

**NeKI brief:** Turns release confidence into an engineering system of staged rollout, observability, rollback readiness, and measurable risk, replacing one-shot deployment anxiety with feedback loops that expose regressions before broad customer impact.

## [A Tool To Automatically Detect Memory Leaks](https://blog.jacobstechtavern.com/p/automatically-detect-memory-leaks)

- Published: `2025-02-24T16:01:55.004Z`

**Topics:** Swift

**Sections:** Jacob’s Tech Tavern · I never learned what a memory leak is · Implementing The System

**NeKI brief:** Presents an automated approach to detecting memory leaks before release, linking instrumentation with repeatable checks. Use it as a starting point for a leak-detection pipeline and validate its tooling against current Xcode support.

## [Secret SwiftUI: A practical use of _VariadicView](https://blog.jacobstechtavern.com/p/secret-swiftui)

- Published: `2025-02-10T16:01:10.502Z`

**Topics:** Swift · SwiftUI

**Sections:** Jacob’s Tech Tavern · Secret SwiftUI: A practical use for _VariadicView

**NeKI brief:** Investigates a practical use of SwiftUI's underscored VariadicView APIs and their risks as non-public implementation details.

## [How I Stole Your ChatGPT API Keys](https://blog.jacobstechtavern.com/p/how-i-stole-your-api-keys)

- Published: `2025-01-27T17:15:45.206Z`

**Topics:** AI Development

**Sections:** Decompiling Your App · Monitoring Network Traffic · How can I protect my app?

**NeKI brief:** Demonstrates how client-shipped AI API keys can be extracted and abused, motivating server-side credential custody, scoped tokens, usage controls, and threat modeling rather than treating mobile application binaries as secret storage.

## [Hardcore Debugging](https://blog.jacobstechtavern.com/p/hardcore-debugging)

- Published: `2025-01-13T17:15:57.444Z`

**NeKI brief:** Presents a systematic debugging workflow that moves from symptom reproduction through instrumentation, hypothesis testing, and minimized evidence, helping engineers isolate root causes rather than repeatedly patching visible failures.

## [The Synchronization Framework in Swift 6](https://blog.jacobstechtavern.com/p/the-synchronisation-framework)

- Published: `2024-12-30T17:15:37.669Z`

**Topics:** Swift

**NeKI brief:** Use Swift Synchronization primitives such as Mutex and atomics for tightly scoped synchronous shared-state access, and compare them with actors based on isolation, suspension, and contention needs. Keep critical sections small, document invariants, and avoid mixing low-level synchronization casually with async workflows.

## [The Swift Runtime: Your Silent Partner - by Jacob Bartlett](https://blog.jacobstechtavern.com/p/the-swift-runtime-your-silent-partner)

- Published: `2024-12-16T17:15:51.319Z`

**Topics:** Swift

**Sections:** Jacob’s Tech Tavern · The Swift Runtime: Your Silent Partner

**NeKI brief:** Introduces the Swift runtime and the role its implementation details play in everyday language behavior.

## [Static, Dynamic, Mergeable, oh, my!](https://blog.jacobstechtavern.com/p/static-dynamic-mergeable-oh-my)

- Published: `2024-11-18T17:24:06.203Z`

**NeKI brief:** Choose static, dynamic, or mergeable library linkage from measurable constraints such as launch time, app size, dependency reuse, and build behavior. Inspect the actual dependency graph and binary output before reorganizing modules, because linkage labels alone do not predict product performance.

## [THE CRASH IS A LIE](https://blog.jacobstechtavern.com/p/what-is-a-crash)

- Published: `2024-11-04T17:15:56.192Z`

**NeKI brief:** Treat a crash as a diagnostic signal from the runtime, kernel, or app termination path rather than a single failure category. Capture symbolicated reports, distinguish memory and assertion failures from watchdog termination, and reproduce the triggering lifecycle or concurrency conditions before changing code.

## [Apple is Killing Swift - by Jacob Bartlett](https://blog.jacobstechtavern.com/p/apple-is-killing-swift)

- Published: `2024-10-21T16:15:15.245Z`

**Topics:** Swift

**Sections:** Jacob’s Tech Tavern · Apple is Killing Swift · Python: Benevolent Dictator For Life

**NeKI brief:** An opinionated examination of Swift's governance and ecosystem direction; useful for evaluating community concerns rather than technical guidance.

## [Migrating Combine to AsyncAlgorithms - by Jacob Bartlett](https://blog.jacobstechtavern.com/p/migrating-combine-to-asyncalgorithms)

- Published: `2024-10-07T16:15:57.105Z`

**Topics:** Concurrency

**Sections:** Jacob’s Tech Tavern · Migrating Combine to AsyncAlgorithms

**NeKI brief:** Guides a migration from Combine pipelines to AsyncAlgorithms, focusing on how asynchronous stream operations translate.

## [Why is my Task running on the main thread?](https://blog.jacobstechtavern.com/p/why-is-task-running-on-main-thread)

- Published: `2024-09-23T16:15:11.379Z`

**Topics:** Concurrency · Swift

**Sections:** Jacob’s Tech Tavern

**NeKI brief:** Builds an intuition for why a Swift Task may execute on the main thread and how actor isolation changes that behavior.

## [Jailbreak your Enemies with a Link: Remote Execution on iOS](https://blog.jacobstechtavern.com/p/jailbreak-enemies-with-a-link-remote-execution)

- Published: `2024-09-09T16:15:21.526Z`

**NeKI brief:** Use the historical WebKit exploit chain as a threat-modeling study: untrusted web content crosses a serious process boundary, so keep devices updated, minimize risky web surfaces, and understand why JavaScript-engine memory-safety failures can become system-level compromise paths.

## [Impress at Job Interviews by Inspecting their App Bundle](https://blog.jacobstechtavern.com/p/impress-at-job-interviews-by-decompiling)

- Published: `2024-08-19T16:15:41.587Z`

**NeKI brief:** For authorized architecture research, inspect a shipped app bundle to identify linked frameworks, assets, symbols, and configuration choices before forming questions. Treat static bundle evidence as a hypothesis, not proof of runtime behavior, and keep analysis within the app's permitted security boundary.

## [The Meme that gave me Imposter Syndrome](https://blog.jacobstechtavern.com/p/the-meme-that-gave-me-imposter-syndrome)

- Published: `2024-07-29T16:15:44.545Z`

**NeKI brief:** Use Swift type attributes deliberately by separating compile-time type-system constraints from ordinary declaration modifiers. When an attribute affects isolation, sendability, ownership, or ABI behavior, inspect the compiler-facing contract and add a focused example instead of treating it as decorative syntax.

## [Mobile Deployment Pipelines for $0](https://blog.jacobstechtavern.com/p/0-to-deploy-free-ci-with-fastlane)

- Published: `2024-07-08T16:15:20.826Z`

**NeKI brief:** Establish a small iOS delivery pipeline that builds, tests, signs, and distributes through fastlane with credentials isolated from repository content. Make each lane reproducible locally and in CI, then keep expensive deployment steps separate from fast pull-request validation.

## [Advanced Core Image](https://blog.jacobstechtavern.com/p/advanced-core-image)

- Published: `2024-06-17T16:15:52.294Z`

**NeKI brief:** Builds advanced Core Image processing around filter graphs, custom kernels, and GPU-backed rendering, showing how image pipelines compose lazily and where color spaces, context reuse, and output conversion determine correctness and performance.

## [Core Image: The Basics](https://blog.jacobstechtavern.com/p/core-image-the-basics)

- Published: `2024-05-27T16:15:04.516Z`

**NeKI brief:** Introduces Core Image's filter and image-processing model with a practical baseline for composing effects. It is useful for choosing GPU-backed image transformations, while API availability and performance need current verification.

## [How to (consistently) get 4.8* App Ratings](https://blog.jacobstechtavern.com/p/how-to-consistently-get-48-app-ratings-3be)

- Published: `2024-05-06T16:15:23.738Z`

**Sections:** Jacob’s Tech Tavern

**NeKI brief:** Shows how to time StoreKit review requests around a user's proven wow moment, with SwiftUI and UIKit examples, rather than prompting indiscriminately. Use it to connect a review prompt to completed value while preserving a low-friction experience and measuring ratings as a product outcome.

## [How to use SwiftData outside SwiftUI](https://blog.jacobstechtavern.com/p/swiftdata-outside-swiftui)

- Published: `2024-04-15T16:15:46.653Z`

**Topics:** Swift · Persistence & Synchronisation · SwiftData · SwiftUI

**NeKI brief:** Uses SwiftData outside SwiftUI by explicitly constructing and injecting ModelContainer and ModelContext dependencies, preserving persistent-model access in services, tests, and non-view workflows without relying on environment propagation.

## [Oh Sh*t, My App is Successful and I Didn’t Think About Accessibility](https://blog.jacobstechtavern.com/p/oh-sht-my-app-is-successful-and-i)

- Published: `2024-03-18T17:15:58.194Z`

**Topics:** Accessibility

**NeKI brief:** Uses an accessibility audit of a SwiftUI app to expose failures at larger text sizes and with screen readers, then turns those findings into concrete remediation work. Follow it when accessibility needs to become a release criterion rather than a late polish task.

## [Async Unit Testing: The Comprehensive Guide](https://blog.jacobstechtavern.com/p/async-unit-testing-in-swift-the-comprehensive)

- Published: `2024-03-11T17:15:13.685Z`

**Topics:** Testing · Concurrency · Architecture · Dependency Injection · Observation & State Management

**Sections:** Introduction · Arc 1: Foundational concepts · Arc 2: Async unit testing

**NeKI brief:** Builds asynchronous unit testing from dependency injection and controllable test doubles through async/await, unstructured tasks, and Combine interoperation. Use the staged examples to reason about deterministic setup, cancellation, and ownership of asynchronous work.

## [High Performance Swift Apps](https://blog.jacobstechtavern.com/p/high-performance-swift-apps)

- Published: `2024-03-04T17:16:05.054Z`

**Topics:** Performance · Swift

**NeKI brief:** Presents a measure-first performance loop: reproduce user-visible cost on a real device, profile the bottleneck with Instruments, then change the implementation and measure again. The workflow helps avoid speculative optimisation and keeps concurrency changes tied to evidence.

## [The 2FA app that tells you when you get `314159`](https://blog.jacobstechtavern.com/p/building-a-2fa-app-that-detects-patterns)

- Published: `2024-02-19T17:15:16.374Z`

**Topics:** Concurrency · Performance · Swift

**Sections:** High Performance Swift Apps

**NeKI brief:** Details a local 2FA-code processing pipeline that generates future six-digit values, detects numeric patterns, and schedules notifications. Follow it for the algorithm, batching, and scheduling constraints of doing substantial computation without turning a small app into a battery problem.

## [The Swift Method Dispatch Deep Dive](https://blog.jacobstechtavern.com/p/compiler-cocaine-the-swift-method)

- Published: `2024-02-05T17:15:58.307Z`

**Topics:** Swift

**NeKI brief:** Explains Swift method dispatch from static and witness-table calls through dynamic dispatch and inlining, connecting compiler choices with flexibility and runtime cost. Use it to investigate a measured hot path, not to apply final or other annotations as blanket optimisation.

## [My Toddler Still Loves Planes, So I Upgraded Her Radar](https://blog.jacobstechtavern.com/p/my-toddler-still-loves-planes-so)

- Published: `2024-01-22T19:37:06.281Z`

**NeKI brief:** Describes a second Aviator release after an upstream OpenSky outage, combining API failure recovery with a feature overhaul and real-user feedback. Use it as a case study in resilient third-party integrations and shipping fixes when release cadence is constrained.

## [Mobile DevOps for Enterprise that Just Works](https://blog.jacobstechtavern.com/p/mobile-devops-for-enterprise-that)

- Published: `2024-01-15T17:05:49.645Z`

**Topics:** Xcode

**Sections:** Ease of setup · Infrastructure Management · Build Speed

**NeKI brief:** Maps enterprise mobile delivery across setup, infrastructure, build speed, and permission management. Use it to frame which operational constraints a mobile CI/CD system must solve before selecting tools or automating a workflow.

## [The Case Against [unowned self]](https://blog.jacobstechtavern.com/p/the-case-against-unowned-self)

- Published: `2024-01-08T17:15:28.259Z`

**Topics:** Performance

**Sections:** Strong references · Weak references · Unowned references

**NeKI brief:** Argues that unowned captures trade memory behavior for crash risk when object lifetimes diverge. Use it to review closure capture choices, retaining weak references where failure is preferable to a dangling access.

## [Modular Architecture for Apps](https://blog.jacobstechtavern.com/p/modular-architecture-for-apps)

- Published: `2024-01-01T21:49:28.396Z`

**Topics:** Architecture

**NeKI brief:** Frames modularisation as a scaling and team-boundary decision rather than a screen-level architecture contest. The progression from a small target to separated modules makes build time, ownership, and dependency direction trade-offs explicit before a split is undertaken.

## [2 Minute Tips: The Dark Secrets of Bools](https://blog.jacobstechtavern.com/p/2-minute-tips-the-dark-secrets-of)

- Published: `2023-12-25T11:00:57.228Z`

**Sections:** A Frozen Struct · Builtins.Int1 · ExpressibleByBooleanLiteral

**NeKI brief:** Inspects Swift Bool as a frozen standard-library struct backed by Builtin.Int1, tying its ABI-stable layout to literal conversion and compiler representation. Follow for runtime intuition, while keeping implementation details separate from source-level API assumptions.

## [2 Minute Tips: iOS Springboard Paddling Pool](https://blog.jacobstechtavern.com/p/2-minute-tips-ios-springboard-paddling)

- Published: `2023-12-25T11:00:53.989Z`

**Sections:** Operating Systems & The Kernel · Userland · iOS Springboard

**NeKI brief:** Uses SpringBoard's privileged userland role to explain the boundary between iOS applications, syscalls, and the kernel. It is useful platform context for understanding why app metadata and home-screen behavior are unavailable to ordinary third-party code.

## [Metal in SwiftUI: How to Write Shaders](https://blog.jacobstechtavern.com/p/metal-in-swiftui-how-to-write-shaders)

- Published: `2023-12-18T17:15:08.786Z`

**Topics:** Swift · SwiftUI

**NeKI brief:** Demonstrates integrating Metal shaders into SwiftUI rendering and explains the boundary between declarative view composition and GPU effects. Use it when evaluating custom visual work that cannot be expressed with standard modifiers.

## [Localization in Xcode 15](https://blog.jacobstechtavern.com/p/localisation-in-xcode-15)

- Published: `2023-12-11T17:15:35.444Z`

**Topics:** Xcode

**Sections:** The Bad Old World™ · Creating a String Catalog · What sort of text exists in the app?

**NeKI brief:** Explains localization changes in Xcode 15 and the failure mode where keys appear instead of translated strings. Follow it when auditing string catalogs and build-resource configuration during an Xcode migration.

## [My Toddler Loves Planes, So I Built Her A Radar](https://blog.jacobstechtavern.com/p/my-toddler-loves-planes-so-i-built)

- Published: `2023-11-27T18:00:26.285Z`

**Topics:** Testing

**Sections:** Inspired · A Problem Statement Emerges · A Vision Takes Shape

**NeKI brief:** Builds an iOS flight-radar experience from real aircraft data, using map presentation and altitude-aware visual reasoning to make nearby flights understandable. Useful as a product case study where external data quality and spatial UI decisions interact.

## [Through the Ages: Apple Animation APIs - by Jacob Bartlett](https://blog.jacobstechtavern.com/p/through-the-ages-apple-animation)

- Published: `2023-11-21T20:52:07.633Z`

**Topics:** Swift · SwiftUI

**Sections:** Jacob’s Tech Tavern · Through the Ages: Apple Animation APIs

**NeKI brief:** Connects Apple's animation APIs across platform eras and uses working code to compare their programming models.

## [Unit Test the Observation Framework - by Jacob Bartlett](https://blog.jacobstechtavern.com/p/unit-test-the-observation-framework)

- Published: `2023-11-13T17:00:43.653Z`

**Topics:** Testing · Observation & State Management

**Sections:** Jacob’s Tech Tavern · Unit Test the Observation Framework · The Observation Framework

**NeKI brief:** Shows how to unit-test code built on the Observation framework, with attention to reliable view-model behavior.

## [COW2LLVM: The isKnownUniquelyReferenced Deep-Dive](https://blog.jacobstechtavern.com/p/cow2llvm-the-isknownuniquelyreferenced)

- Published: `2023-11-06T17:20:18.179Z`

**Topics:** Swift · Performance

**Sections:** Roadmap · What is 🐮? · Reference and value semantics

**NeKI brief:** Dives into Swift copy-on-write and isKnownUniquelyReferenced, connecting value semantics to heap buffers and compiler-generated behavior. Use it for performance reasoning, not as a license to bypass safe ownership abstractions.

## [Through the Ages: Apple CPU Architecture](https://blog.jacobstechtavern.com/p/through-the-ages-apple-cpu-architecture)

- Published: `2023-10-30T19:47:24.880Z`

**Topics:** Architecture · Performance

**Sections:** Timeline & Key Concepts · The King of CPU Architecture Migrations · 1984 — Motorola 68k

**NeKI brief:** Traces Apple CPU architecture across generations while using each era to explain core processor concepts. It provides hardware context for performance discussions, with historical details that should not substitute for current device documentation.

## [2 Minute Tips: The Strategy Pattern](https://blog.jacobstechtavern.com/p/2-minute-tips-the-strategy-pattern)

- Published: `2023-10-24T08:15:16.128Z`

**Sections:** Sorting Strategies · Why is this useful? · Switching Internal Implementations

**NeKI brief:** Implements interchangeable sorting algorithms behind a Swift protocol, making the Strategy pattern's runtime substitution and differing time/space costs visible. Use it when behavior varies by policy and the algorithm choice should remain testable and isolated.

## [Welcome to Jacob’s Tech Tavern! 🍺 - by Jacob Bartlett](https://blog.jacobstechtavern.com/p/aviator-demo-video)

- Published: `2023-10-14T14:29:06.846Z`

**Topics:** AI Development · Concurrency · Performance

**Sections:** Jacob’s Tech Tavern · Welcome to Jacob’s Tech Tavern! 🍺

**NeKI brief:** Introduces a newsletter focused on Swift concurrency, agentic engineering, SwiftUI, and iOS performance. Follow it as a routing point for future deep-dive articles rather than as evidence for a specific implementation decision.

## [Advanced Swift Actors: Re-entrancy & Interleaving](https://blog.jacobstechtavern.com/p/advanced-swift-actors-re-entrancy)

- Published: `2023-10-10T08:15:07.357Z`

**Topics:** Concurrency · Swift

**NeKI brief:** Examines actor re-entrancy and interleaving, showing why an actor-isolated method can observe changed state after an await. Follow it when diagnosing ordering assumptions and designing invariants across suspension points.

## [2 Minute Tips: The Dark Secret of Optionals](https://blog.jacobstechtavern.com/p/2-minute-tips-the-dark-secret-of)

- Published: `2023-10-02T08:15:02.783Z`

**NeKI brief:** Reveals Optional as a two-case standard-library enum and traces question-mark syntax to ordinary optional operations. The implementation tour is a compact aid for reasoning about nil propagation and unwrapping, not a replacement for clear domain-level optional handling.

## [Apple Animation Through the Ages: 2019](https://blog.jacobstechtavern.com/p/apple-animation-through-the-ages-580)

- Published: `2023-09-26T08:15:42.449Z`

**NeKI brief:** Places Apple's animation stack in a historical timeline and connects the 2019 APIs to earlier programming models. Follow it for conceptual context when choosing an animation layer, then verify current framework behavior and availability in Apple documentation.

## [Apple Animation Through the Ages: 2014](https://blog.jacobstechtavern.com/p/apple-animation-through-the-ages-265)

- Published: `2023-09-19T08:15:09.850Z`

**NeKI brief:** Uses Apple's 2014 animation era to show how framework abstractions evolved across the platform. It is a historical route into animation design decisions; treat version-specific APIs as context and confirm modern equivalents before implementation.

## [Apple Animation Through the Ages: 2007](https://blog.jacobstechtavern.com/p/apple-animation-through-the-ages-e96)

- Published: `2023-09-12T08:15:08.403Z`

**NeKI brief:** Connects the 2007 iPhone-era animation model to the constraints and abstractions that shaped early UIKit development. Follow for historical perspective on why APIs look the way they do, not as current implementation guidance.

## [Apple Animation Through the Ages: 2001](https://blog.jacobstechtavern.com/p/apple-animation-through-the-ages-c54)

- Published: `2023-09-05T08:15:04.496Z`

**NeKI brief:** Traces the 2001 transition in Apple's animation tooling and relates it to the programming model later exposed on Apple platforms. The historical comparison helps explain abstraction trade-offs while requiring current API verification.

## [Apple Animation Through the Ages: 1989](https://blog.jacobstechtavern.com/p/apple-animation-through-the-ages)

- Published: `2023-08-29T08:15:13.907Z`

**NeKI brief:** Introduces the earliest Apple animation milestone in the series and links hardware-era constraints to later compositing abstractions. Use it as background for platform evolution rather than as a recipe for present-day animation code.

## [Combine, async/await, and Unit Testing](https://blog.jacobstechtavern.com/p/combine-asyncawait-and-unit-testing)

- Published: `2023-08-22T08:15:10.291Z`

**Topics:** Testing · Concurrency

**NeKI brief:** Connects Combine, async/await, and unit testing when designing and verifying asynchronous application behavior.

## [Implement your Data Access Layer with Combine](https://blog.jacobstechtavern.com/p/implement-your-data-access-layer)

- Published: `2023-08-15T08:15:19.237Z`

**Sections:** Part V: (interlude) - Implement your Data Access Layer with Combine · The Data Access layer · Implementing our Repository with Combine

**NeKI brief:** Separates what data an app needs from how a network or cache retrieves it, then composes repository operations with Combine publishers. Follow it when introducing a data-access boundary that can swap sources and remain mockable in asynchronous tests.

## [Advanced async testing: Unstructured concurrency](https://blog.jacobstechtavern.com/p/async-testing-masterclass-4-advanced)

- Published: `2023-08-01T08:15:49.247Z`

**Topics:** Concurrency · Testing

**NeKI brief:** Explores advanced async testing with unstructured concurrency and the resulting control and cancellation concerns. Use it to reason about test lifetimes and task cleanup before adopting detached or manually managed tasks.

## [Unit Testing with async/await](https://blog.jacobstechtavern.com/p/async-testing-masterclass-3-the-basics)

- Published: `2023-07-18T08:15:53.603Z`

**Topics:** Testing · Concurrency

**Sections:** Setting up our first tests with callCount

**NeKI brief:** Shows the fundamentals of unit testing async/await code, including awaiting work and asserting outcomes. It is a practical entry point, but concurrency isolation and framework APIs should be checked against the target Swift version.

## [SwiftUI apps at scale](https://blog.jacobstechtavern.com/p/swiftui-apps-at-scale)

- Published: `2023-07-04T06:43:58.668Z`

**Topics:** Swift · SwiftUI

**NeKI brief:** Discusses structuring SwiftUI applications as they grow beyond isolated views, including ownership and module boundaries. Use it to compare scaling strategies against the project's navigation, state, and testing requirements.

## [Unit Testing Masterclass: Mocking like a Pro](https://blog.jacobstechtavern.com/p/async-testing-masterclass-2-mocking)

- Published: `2023-06-20T18:00:52.462Z`

**Topics:** Testing

**Sections:** Jacob’s Tech Tavern · Part II - Mocking like a Pro · What are mocks?

**NeKI brief:** Covers mock design for testing asynchronous code and the trade-offs of different test doubles. Use it when deciding which dependencies deserve protocols, fakes, or recorded fixtures in Swift tests.

## [Dependency Injection Demystified](https://blog.jacobstechtavern.com/p/async-testing-masterclass-1-dependency)

- Published: `2023-06-06T18:01:07.294Z`

**Topics:** Architecture · Dependency Injection · Testing

**Sections:** Part I - Dependency Injection · What is DI? · What does this have to do with testing?

**NeKI brief:** Explains dependency injection as a testability boundary for asynchronous Swift code. Follow it to separate side effects from assertions and to make async tests deterministic without relying on production services.

## [Swift Enums 🤝 Design Systems](https://blog.jacobstechtavern.com/p/enums-and-design-systems)

- Published: `2023-05-23T18:00:58.880Z`

**Topics:** Swift

**NeKI brief:** Uses Swift enums to model design-system variants and keep UI choices explicit. The pattern is useful for compiler-checked style APIs, provided the enum surface remains aligned with evolving product tokens.

## [The Magic of Sets](https://blog.jacobstechtavern.com/p/fun-with-sets)

- Published: `2023-04-11T19:00:52.706Z`

**NeKI brief:** Uses Swift Set operations to illustrate membership, uniqueness, and collection transformations. Follow it for a compact refresher when choosing set algebra over array scans, while checking complexity for the actual data size.

## [Access control in Swift like a boss](https://blog.jacobstechtavern.com/p/access-control-in-swift-like-a-boss)

- Published: `2023-03-28T19:16:06.245Z`

**Topics:** Swift

**NeKI brief:** Explains Swift access-control choices and the design consequences of exposing or hiding implementation details.

## [Mobile is actually pretty hard.](https://blog.jacobstechtavern.com/p/mobile-is-actually-pretty-hard)

- Published: `2023-03-21T22:35:08.372Z`

**NeKI brief:** Explains why mobile engineering spans device constraints, operating-system behavior, performance, distribution, and product integration, making platform expertise more than ordinary application coding.
