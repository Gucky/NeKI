# Antoine van der Lee articles

Third-party source index. It provides source attribution and routing metadata, not republished article content. Verify article conclusions independently before applying them.

- Archive: [https://www.avanderlee.com/](https://www.avanderlee.com/)
- Last collected: `2026-07-22T21:58:56Z`
- Indexed entries: **365**

- [How to Test iOS Apps in Different Time Zones on a Physical iPhone - SwiftLee](https://www.avanderlee.com/xcode/ios-time-zone-testing-physical-iphone)
  **Published:** `2026-07-20T12:27:42+00:00`
  **Topics:** Concurrency · Swift · Testing · Xcode
  **NeKI brief:** Compares ways to validate time-sensitive app behavior on a physical iPhone, including automatic time-zone handling and simulated location changes.
- [User Diagnostics Reports: Solving app bugs faster with AI Agents - SwiftLee](https://www.avanderlee.com/debugging/introducing-diagnostics-improved-debugging-and-user-support)
  **Published:** `2026-07-13T07:21:09+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Describes collecting structured user diagnostics—logs, context, and app state—to give an AI agent enough evidence to reproduce a bug. The workflow connects an in-app report to faster triage without requiring a live debugger session.
- [Defer in Swift explained with Code Examples - SwiftLee](https://www.avanderlee.com/swift/defer-usage-swift)
  **Published:** `2026-07-06T12:51:59+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Explains defer’s reverse-order cleanup semantics, scope boundaries, and Swift 6.4’s support for asynchronous cleanup. The examples help decide where resource-release code belongs and avoid assuming defer runs at task or function completion.
- [Memberwise Initializer in Swift explained with Code Examples](https://www.avanderlee.com/swift/memberwise-initializers)
  **Published:** `2026-06-29T13:40:35+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Shows how Swift synthesizes memberwise initializers for structs, how default values alter their signatures, and when a custom initializer replaces synthesis. Useful for designing value types without accidentally losing convenient construction APIs.
- [Swift 6.4: What’s New in Concurrency - SwiftLee](https://www.avanderlee.com/concurrency/swift-6-4-whats-new-in-concurrency)
  **Published:** `2026-06-21T07:05:27+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Surveys Swift 6.4 concurrency additions with runnable examples, highlighting changes that affect isolation, task behavior, and migration choices. It is a compact map for checking which language improvements are relevant before changing production concurrency code.
- [SwiftUI Best Practices, straight from Apple's Xcode 27 Agent Skill - SwiftLee](https://www.avanderlee.com/ai-development/swiftui-best-practices-xcode-27-agent-skill)
  **Published:** `2026-06-16T08:23:05+00:00`
  **Topics:** Concurrency · Swift · SwiftUI · Xcode
  **NeKI brief:** Turns Apple’s Xcode 27 SwiftUI guidance into an agent skill covering state flow, view composition, accessibility, and previews. The link is useful for making code-generation prompts enforce framework conventions instead of merely producing compilable views.
- [Using Xcode 27's Agent Skills in Claude, Codex, and Cursor - SwiftLee](https://www.avanderlee.com/ai-development/using-xcode-27s-agent-skills-in-claude-codex-and-cursor)
  **Published:** `2026-06-09T13:58:37+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Demonstrates exporting Xcode 27 agent skills for Claude, Codex, and Cursor, then invoking the same reusable guidance across tools. It addresses portability and setup trade-offs when teams want consistent AI-assisted Swift development workflows.
- [WWDC 2026: My predictions and wishes](https://www.avanderlee.com/wwdc/wwdc-2026-my-predictions-and-wishes)
  **Published:** `2026-06-02T08:36:35+00:00`
  **Topics:** AI Development · App Intents & System Surfaces · Concurrency · Swift
  **NeKI brief:** Previews possible WWDC directions around Xcode agentic development, App Store Connect MCP, App Intents, and official agent tooling. Use it as a hypothesis checklist before validating announced capabilities in primary Apple sessions.
- [Using Xcode Instruments to optimize Swift Concurrency Code - SwiftLee](https://www.avanderlee.com/concurrency/using-xcode-instruments-to-optimize-swift-concurrency-code)
  **Published:** `2026-05-26T07:36:44+00:00`
  **Topics:** Concurrency · Performance · Swift · Xcode
  **NeKI brief:** Uses Instruments’ concurrency and time-based views to correlate task execution with latency, then validates a change with a second recording. The workflow is a practical guard against optimizing async code from source inspection alone.
- [Recording a Physical iPhone for App Preview Videos - SwiftLee](https://www.avanderlee.com/xcode/record-iphone-app-preview-videos)
  **Published:** `2026-05-18T10:11:37+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Details a physical-iPhone capture workflow for App Store previews, including clean status-bar presentation, high-resolution recording, and transfer into marketing edits. It is useful when simulator output cannot represent device-only behavior or appearance.
- [AI-Powered Xcode Simulator Automation (token-efficient) - SwiftLee](https://www.avanderlee.com/ai-development/ai-powered-xcode-simulator-automation-token-efficient)
  **Published:** `2026-05-11T07:16:11+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Shows a token-efficient simulator automation loop that uses focused CLI actions and AI agents instead of repeatedly transmitting full UI state. The approach helps balance reproducibility, context cost, and coverage in agent-driven UI testing.
- [Unexpected Task suspension points in Swift Concurrency - SwiftLee](https://www.avanderlee.com/concurrency/unexpected-task-suspension-points-in-swift-concurrency)
  **Published:** `2026-05-04T06:41:29+00:00`
  **Topics:** Concurrency · Performance · Swift · Xcode
  **NeKI brief:** Explains why seemingly synchronous sections can suspend at hidden async boundaries, such as actor hops and awaited calls inside expressions. The examples help locate latency and ordering surprises when reading concurrent Swift code.
- [Immediate tasks in Swift Concurrency explained](https://www.avanderlee.com/concurrency/immediate-tasks-in-swift-concurrency-explained)
  **Published:** `2026-04-27T11:46:14+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Explains immediate tasks and their execution timing in Swift 6.2, contrasting them with ordinary task scheduling and actor hops. The examples clarify when reduced scheduling latency is useful and where ordering assumptions become unsafe.
- [Xcode Instruments Time Profiler: Improve performance with AI](https://www.avanderlee.com/ai-development/xcode-instruments-time-profiler-improve-performance-with-ai)
  **Published:** `2026-04-20T09:45:14+00:00`
  **Topics:** Accessibility · Concurrency · Performance · Swift · Xcode
  **NeKI brief:** Combines Time Profiler recordings with an AI-assisted investigation loop: capture a hot stack, provide the relevant code, and validate the proposed change with another profile. It emphasizes evidence-based optimization over guessing from source alone.
- [Network Requests Optimization using Xcode's Simulator & Agents - SwiftLee](https://www.avanderlee.com/ai-development/network-requests-optimization-using-xcodes-simulator-agents)
  **Published:** `2026-04-14T09:06:47+00:00`
  **Topics:** Concurrency · Networking · Performance · Swift · Xcode
  **NeKI brief:** Combines simulator observation with agent-assisted profiling to inspect slow network requests, identify repeated work, and verify improvements. It provides a concrete loop for measuring request behavior rather than trusting perceived UI responsiveness.
- [RocketSim 15: VoiceOver Navigator & Pro Simulator Recordings - SwiftLee](https://www.avanderlee.com/xcode/rocketsim-15-voiceover-navigator-pro-simulator-recordings)
  **Published:** `2026-04-07T07:30:42+00:00`
  **Topics:** Accessibility · Concurrency · Liquid Glass · Swift · Testing · Xcode
  **NeKI brief:** Covers RocketSim 15’s VoiceOver navigator and simulator recording controls, including accessibility inspection and polished capture output. The link is useful for shortening the feedback loop between VoiceOver behavior, visual review, and shareable bug evidence.
- [Xcode Build Optimization using 6 Agent Skills - SwiftLee](https://www.avanderlee.com/xcode/xcode-build-optimization-using-6-agent-skills)
  **Published:** `2026-03-30T10:22:39+00:00`
  **Topics:** Concurrency · Swift · SwiftUI · Xcode
  **NeKI brief:** Presents six focused agent skills for inspecting Xcode build reports, dependency graphs, and compiler hotspots. The separation turns build optimization into repeatable diagnostics while keeping proposed settings changes tied to measured bottlenecks.
- [The "One More Prompt" risk of agentic coding](https://www.avanderlee.com/ai-development/the-one-more-prompt-risk-of-agentic-coding)
  **Published:** `2026-03-23T10:48:10+00:00`
  **Topics:** AI Development · Concurrency · Swift
  **NeKI brief:** Examines how repeated follow-up prompts can expand an agentic coding task beyond its original scope, increasing churn and regressions. The discussion offers a useful boundary-setting heuristic for deciding when to stop prompting and review the diff.
- [Agentic Development: Multi-Project Challenges - SwiftLee](https://www.avanderlee.com/ai-development/agentic-development-multi-project-challenges)
  **Published:** `2026-03-16T13:11:45+00:00`
  **Topics:** AI Development · Concurrency · Swift
  **NeKI brief:** Describes the coordination problems agents encounter across multiple repositories, such as context switching, inconsistent conventions, and shared tooling. The proposed workflow helps structure project boundaries before delegating changes that span codebases.
- [A 9-Step Framework for Choosing the Right Agent Skill - SwiftLee](https://www.avanderlee.com/ai-development/a-9-step-framework-for-choosing-the-right-agent-skill)
  **Published:** `2026-03-09T08:55:45+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Provides a nine-step selection process that matches an agent skill to task scope, evidence needs, and tool permissions. It is useful for avoiding broad, overlapping instructions when a narrowly routed skill would be safer.
- [Using an MCP to perform product optimizations - SwiftLee](https://www.avanderlee.com/ai-development/using-an-mcp-to-perform-product-optimizations)
  **Published:** `2026-03-02T13:56:03+00:00`
  **Topics:** AI Development · Concurrency · Swift
  **NeKI brief:** Illustrates using an MCP server to connect product data with an optimization workflow, from querying evidence to evaluating an intervention. The article helps distinguish tool integration that improves decisions from automation that merely adds another interface.
- [VoiceOver Navigator & 120 FPS Recordings for Xcode's Simulator](https://www.avanderlee.com/xcode/voiceover-navigator-120-fps-recordings-for-xcode-simulator)
  **Published:** `2026-02-24T11:11:21+00:00`
  **Topics:** Accessibility · Concurrency · Networking · Swift · Testing · Xcode
  **NeKI brief:** Shows simulator VoiceOver navigation and 120-FPS recording workflows for inspecting accessibility and animation details. The combination provides more diagnostic fidelity than screenshots when reporting focus order or motion regressions.
- [Swift Testing Agent Skill: Write high quality tests with AI - SwiftLee](https://www.avanderlee.com/ai-development/swift-testing-agent-skill-write-high-quality-tests-with-ai)
  **Published:** `2026-02-17T09:37:01+00:00`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Uses a Swift Testing agent skill to guide test naming, setup, assertions, and coverage decisions. The examples show how reusable testing constraints reduce plausible-looking but weak AI-generated tests.
- [Core Data Agent Skill: Now available open-source - SwiftLee](https://www.avanderlee.com/ai-development/core-data-agent-skill-now-available-open-source)
  **Published:** `2026-02-08T23:15:00+00:00`
  **Topics:** Concurrency · Core Data · Persistence & Synchronisation · Swift
  **NeKI brief:** Introduces an open-source Core Data agent skill containing model, migration, fetch, and persistence guidance. It is useful for steering an assistant through framework-specific invariants instead of letting generated code treat Core Data like a generic database.
- [SwiftUI Agent Skill: Build better views with AI](https://www.avanderlee.com/ai-development/swiftui-agent-skill-build-better-views-with-ai)
  **Published:** `2026-02-02T12:51:55+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Demonstrates a SwiftUI agent skill that reviews state ownership, composition, and view refactoring decisions. The link is valuable when using AI to improve an existing hierarchy rather than generating isolated demo views.
- [AI App Development: What I Learned in One Month - SwiftLee](https://www.avanderlee.com/ai-development/ai-app-development-what-i-learned-in-one-month)
  **Published:** `2026-01-25T23:55:00+00:00`
  **Topics:** Concurrency · Dependency Injection · Swift
  **NeKI brief:** Reflects on building and shipping an app with AI over a month, separating rapid scaffolding from decisions still requiring human product and engineering judgment. It offers practical signals for evaluating where agent speed creates later maintenance cost.
- [11 Things I learned after using AI Agents full-time](https://www.avanderlee.com/ai-development/11-things-i-learned-after-using-ai-agents-full-time)
  **Published:** `2026-01-19T11:07:39+00:00`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Catalogues full-time AI-agent usage lessons around context management, verification, and task decomposition. The observations are useful for designing guardrails that preserve review quality when generation becomes the default implementation path.
- [Agent Skills explained: Replacing AGENTS.md with reusable AI knowledge](https://www.avanderlee.com/ai-development/agent-skills-replacing-agents-md-with-reusable-ai-knowledge)
  **Published:** `2026-01-12T09:13:31+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Explains packaging recurring repository guidance as reusable agent skills instead of duplicating large AGENTS.md files. The approach addresses discoverability, selective loading, and keeping project instructions focused on local constraints.
- [Icon Composer: Transforming an AI-generated icon - SwiftLee](https://www.avanderlee.com/workflow/icon-composer-transforming-an-ai-generated-icon)
  **Published:** `2026-01-05T07:53:01+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Walks through refining an AI-generated icon in Apple’s Icon Composer, focusing on layers, materials, and platform-ready variants. It is useful for understanding where manual composition remains necessary after image generation.
- [SwiftLee in 2025: A full year as an indie developer - SwiftLee](https://www.avanderlee.com/general/swiftlee-in-2025-a-full-year-as-an-indie-developer)
  **Published:** `2025-12-29T10:37:29+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Reviews SwiftLee's 2025 indie-development milestones and the product, publishing, and business choices behind them. Use it as retrospective context when weighing audience growth against sustainable solo-product work.
- [From App Idea to 10K MRR - YouTube Series - SwiftLee](https://www.avanderlee.com/workflow/from-app-idea-to-10k-mrr-youtube-series)
  **Published:** `2025-12-23T07:56:41+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Introduces a video case study following an app from initial idea toward recurring revenue, making the product and marketing steps visible. It is useful for assessing indie-app sequencing, not for treating revenue as a guaranteed outcome.
- [9 months of a Swift Concurrency Course](https://www.avanderlee.com/concurrency/9-months-of-a-swift-concurrency-course)
  **Published:** `2025-12-15T08:58:00+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Reflects on teaching Swift Concurrency over nine months, identifying the concepts that repeatedly challenge learners and the order that makes them approachable. It is useful for planning a concurrency curriculum around mental models rather than isolated syntax.
- [Battery life on iOS and the myth of killing apps](https://www.avanderlee.com/optimization/battery-life-on-ios-and-the-myth-of-killing-apps)
  **Published:** `2025-12-09T00:00:00+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Separates background execution, suspension, and force-quitting from common battery folklore, then identifies energy-saving behaviors that actually matter. The article is a useful diagnostic reference before prescribing app-lifecycle changes for power complaints.
- [The 7 changes I do for every new Xcode project](https://www.avanderlee.com/xcode/the-7-changes-i-do-for-every-new-xcode-project)
  **Published:** `2025-12-01T07:58:55+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Collects baseline project-setting decisions intended to reduce later migration debt, including Approachable Concurrency, upcoming features, and Swift 6 mode.
- [Black Friday: SwiftLee Courses & RocketSim - SwiftLee](https://www.avanderlee.com/general/black-friday-swiftlee-courses-rocketsim)
  **Published:** `2025-11-24T10:19:24+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Announces time-limited discounts for RocketSim and SwiftLee courses. Keep it as historical commercial context only; the offer and pricing are inherently stale and should not drive current tooling decisions.
- [Approachable Concurrency in Swift 6.2: A Clear Guide](https://www.avanderlee.com/concurrency/approachable-concurrency-in-swift-6-2-a-clear-guide)
  **Published:** `2025-11-17T12:11:51+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Breaks down the compiler settings behind Approachable Concurrency in Swift 6.2 and shows how new and existing Xcode projects opt into them.
- [MainActorMessage & AsyncMessage: Concurrency-safe notifications](https://www.avanderlee.com/concurrency/mainactormessage-asyncmessage-concurrency-safe-notifications)
  **Published:** `2025-11-10T13:20:40+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Introduces concurrency-safe notification messages for actor-isolated consumers, contrasting MainActorMessage with AsyncMessage delivery. The examples show how typed messages replace unstructured NotificationCenter payloads while preserving asynchronous observation.
- [Simulator Camera: Test your app without a physical device](https://www.avanderlee.com/xcode/simulator-camera-test-your-app-without-a-physical-device)
  **Published:** `2025-11-03T18:46:15+00:00`
  **Topics:** Concurrency · Swift · Testing · Xcode
  **NeKI brief:** Shows how to feed camera input through Xcode’s simulator so capture flows can be tested without hardware. It highlights the simulator’s coverage boundary and the cases that still require a physical camera for validation.
- [Build performance analysis for speeding up Xcode builds - SwiftLee](https://www.avanderlee.com/optimization/analysing-build-performance-xcode)
  **Published:** `2025-10-27T10:32:43+00:00`
  **Topics:** Concurrency · Performance · Swift · Swift Package Manager · Xcode
  **NeKI brief:** Uses Xcode's build reports and timing data to identify slow compilation, then narrows work to expensive files, type checking, and dependency structure. The workflow turns an otherwise vague 'build is slow' complaint into measurable candidates.
- [SwiftUI Architecture: Structure Views for Reusability and Clarity](https://www.avanderlee.com/swiftui/swiftui-architecture-structure-views-for-reusability-and-clarity)
  **Published:** `2025-10-21T07:28:53+00:00`
  **Topics:** Architecture · Concurrency · Swift · SwiftUI
  **NeKI brief:** Refactors oversized SwiftUI view bodies by extracting responsibilities, choosing stable data flow, and isolating reusable components. The examples make the trade-off between abstraction and readable composition concrete for growing screens.
- [Why Swift Migration Tooling Matters](https://www.avanderlee.com/concurrency/swift-migration-tooling-upcoming-swift-features)
  **Published:** `2025-10-14T07:26:08+00:00`
  **Topics:** Concurrency · Swift · Swift Package Manager
  **NeKI brief:** Explains how Swift migration tooling previews upcoming language changes and surfaces source edits needed for adoption. It is useful for planning incremental compiler migrations while distinguishing mechanical fixes from semantic concurrency decisions.
- [The 5 biggest mistakes iOS Developers make with async/await - SwiftLee](https://www.avanderlee.com/concurrency/the-5-biggest-mistakes-ios-developers-make-with-async-await)
  **Published:** `2025-10-07T07:02:52+00:00`
  **Topics:** Concurrency · Performance · Swift
  **NeKI brief:** Reviews common async/await errors such as unstructured tasks, missing cancellation, actor misuse, and accidental sequential work. Each example links the symptom to a safer structured-concurrency design, making it useful during code review.
- [Derived Data: 5 Things iOS Developers Do Wrong - SwiftLee](https://www.avanderlee.com/xcode/derived-data-5-things-ios-developers-do-wrong)
  **Published:** `2025-09-29T07:10:58+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Explains what Derived Data contains, why deleting it is not a universal fix, and which Xcode problems stem from stale build state. The guidance helps choose targeted cleanup or diagnosis instead of masking reproducible build issues.
- [App Store Optimization: Real-world Best Practices - SwiftLee](https://www.avanderlee.com/optimization/app-store-optimization-real-world-best-practices)
  **Published:** `2025-09-23T08:03:19+00:00`
  **Topics:** Concurrency · Performance · Swift
  **NeKI brief:** Connects App Store metadata, screenshots, localization, and experiment results to discoverability and conversion decisions. The real-world workflow is useful when prioritizing store changes with measurable funnel impact rather than aesthetic preference.
- [SwiftUI Toggle: A Complete Guide - SwiftLee](https://www.avanderlee.com/swiftui/toggle-switch-a-complete-guide)
  **Published:** `2025-09-09T10:01:00+00:00`
  **Topics:** Concurrency · Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Covers Toggle binding, labels, custom styles, accessibility, and state-driven behavior in SwiftUI. The examples help select system controls or custom presentation without breaking two-way state updates.
- [@ViewBuilder usage explained with code examples - SwiftLee](https://www.avanderlee.com/swiftui/viewbuilder)
  **Published:** `2025-08-31T10:22:04+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Explains @ViewBuilder’s result-builder rules, conditional branches, and interaction with opaque View return types. It is useful for diagnosing compiler errors when composing generic SwiftUI content closures.
- [Swift Computed Property: Code Examples - SwiftLee](https://www.avanderlee.com/swift/computed-property)
  **Published:** `2025-08-25T10:41:11+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Demonstrates stored-versus-computed property semantics, get/set accessors, lazy alternatives, and async or throwing accessors. The comparisons clarify when derived values should remain synchronous and side-effect free.
- [Property Wrappers in Swift explained with code examples - SwiftLee](https://www.avanderlee.com/swift/property-wrappers)
  **Published:** `2025-08-19T12:08:35+00:00`
  **Topics:** Concurrency · Macros & Metaprogramming · Persistence & Synchronisation · Swift
  **NeKI brief:** Builds custom property wrappers to centralize storage and projected values, then shows their initialization and composition rules. The article helps evaluate when a wrapper removes duplication without hiding important state transitions.
- [Async await in Swift explained with code examples - SwiftLee](https://www.avanderlee.com/swift/async-await)
  **Published:** `2025-08-11T06:53:59+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Introduces async/await with structured tasks, throwing functions, and parallel work, showing how control flow remains readable while operations suspend. It is a practical entry point for replacing callback nesting without losing cancellation semantics.
- [Global actor in Swift Concurrency explained with code examples - SwiftLee](https://www.avanderlee.com/concurrency/global-actor)
  **Published:** `2025-08-05T17:14:41+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Defines and applies a custom global actor, contrasting it with MainActor and ordinary actors. The examples show how global isolation serializes shared domain work across otherwise unrelated types and functions.
- [Combine and Swift Concurrency: A threading risk - SwiftLee](https://www.avanderlee.com/concurrency/combine-and-swift-concurrency-a-threading-risk)
  **Published:** `2025-07-28T22:05:00+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Examines how Combine delivery and Swift concurrency isolation can disagree, especially when receiving values on a scheduler and updating actor-isolated state. It traces the threading hazard and shows patterns for making the handoff explicit.
- [Threads vs. Tasks in Swift Concurrency - SwiftLee](https://www.avanderlee.com/concurrency/threads-vs-tasks-in-swift-concurrency)
  **Published:** `2025-07-21T23:00:00+00:00`
  **Topics:** Concurrency · Performance · Swift
  **NeKI brief:** Contrasts OS threads with Swift tasks, explaining cooperative scheduling, suspension, and why task count need not equal thread count. The model helps reason about concurrency behavior without importing thread-centric assumptions into async code.
- [Modern Swift Lock: Mutex & the Synchronization Framework - SwiftLee](https://www.avanderlee.com/concurrency/modern-swift-lock-mutex-the-synchronization-framework)
  **Published:** `2025-07-14T23:00:00+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Introduces Mutex and the Synchronization framework as a lock-based option for small critical sections, contrasting it with actors. Examples cover protected state and scoped mutation, clarifying when synchronous locking is preferable to an async hop.
- [Swift Concurrency & Swift 6 Course (Launch offer)](https://www.avanderlee.com/swift/swift-concurrency-course-tutorial-book)
  **Published:** `2025-07-08T07:17:37+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Outlines a Swift Concurrency and Swift 6 course covering actors, tasks, async sequences, synchronization, and migration. The structured progression helps teams choose a coherent learning resource instead of collecting disconnected concurrency articles.
- [Sparkle: Distribution apps in- and out of the Mac App Store - SwiftLee](https://www.avanderlee.com/xcode/sparkle-distribution-apps-in-and-out-of-the-mac-app-store)
  **Published:** `2025-06-30T09:43:46+00:00`
  **Topics:** Concurrency · Swift · Swift Package Manager · Xcode
  **NeKI brief:** Explains integrating Sparkle updates for macOS apps while retaining Mac App Store distribution, including signing and channel differences. It helps choose an update architecture that respects each distribution path’s constraints.
- [#Playground Macro: Running Code Snippets in Xcode's canvas - SwiftLee](https://www.avanderlee.com/swift/playground-macro-running-code-snippets-in-xcodes-canvas)
  **Published:** `2025-06-24T07:08:46+00:00`
  **Topics:** Concurrency · Macros & Metaprogramming · Swift · Xcode
  **NeKI brief:** Demonstrates Xcode 26's #Playground macro for running named Swift snippets in the canvas and navigating among multiple experiments.
- [Default Actor Isolation in Swift 6.2 - SwiftLee](https://www.avanderlee.com/concurrency/default-actor-isolation-in-swift-6-2)
  **Published:** `2025-06-16T08:24:57+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Shows how Swift 6.2 default actor isolation changes unannotated code and how to opt into it during migration. The examples clarify the convenience gained and the explicit Sendable or nonisolated work still required.
- [@concurrent explained with code examples - SwiftLee](https://www.avanderlee.com/concurrency/concurrent-explained-with-code-examples)
  **Published:** `2025-06-10T15:06:06+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Explains the @concurrent attribute and how it permits parallel execution for functions otherwise isolated by default. The examples expose the safety requirements and help decide when parallelism is worth the added isolation annotations.
- [Unique values in Swift: Removing duplicates from an array - SwiftLee](https://www.avanderlee.com/swift/unique-values-removing-duplicates-array)
  **Published:** `2025-06-02T08:18:08+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Compares duplicate removal by Set conversion with order-preserving approaches, including their performance and Hashable requirements. The trade-off matters when uniqueness must be retained without silently changing collection order.
- [Billing Grace Period Explained: How It Works and Why It Matters - SwiftLee](https://www.avanderlee.com/optimization/billing-grace-period-explained)
  **Published:** `2025-05-27T07:01:54+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Describes StoreKit subscription billing grace periods, eligibility, and entitlement handling while Apple retries payment. It is useful for implementing a temporary access policy that avoids treating every billing failure as immediate cancellation.
- [Institutional Purchases: Understanding and Detecting - SwiftLee](https://www.avanderlee.com/optimization/institutional-purchases-volume-purchase-program)
  **Published:** `2025-05-19T11:36:50+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Explains how Apple institutional or volume purchases differ from ordinary transactions and how an app can detect related installs. The guidance helps interpret download metrics and choose appropriate entitlement or support messaging.
- [Universal Links implementation on iOS - SwiftLee](https://www.avanderlee.com/swiftui/universal-links-ios)
  **Published:** `2025-05-12T07:18:42+00:00`
  **Topics:** Concurrency · Navigation & Deep Linking · Swift · SwiftUI · Testing
  **NeKI brief:** Details Universal Links setup across associated domains, application routing, and fallback behavior when a link cannot open the app. The checklist is useful for diagnosing why valid HTTPS links remain in Safari.
- [Testing push notifications on the iOS simulator - SwiftLee](https://www.avanderlee.com/workflow/testing-push-notifications-ios-simulator)
  **Published:** `2025-05-06T07:14:06+00:00`
  **Topics:** Concurrency · Swift · Testing · Xcode
  **NeKI brief:** Shows a local Mac workflow for sending test push payloads to the iOS simulator, including repeatable payload triggering for teammates. It shortens feedback cycles while preserving the need for device testing of production delivery.
- [SwiftUI ForEach Explained with Code Examples - SwiftLee](https://www.avanderlee.com/swiftui/swiftui-foreach-loop-index)
  **Published:** `2025-04-28T09:00:00+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Demonstrates index-aware ForEach patterns and explains identity requirements when iterating collections. The examples help avoid unstable IDs and out-of-range indexing while rendering editable SwiftUI lists.
- [Swift 6.2: A first look at how it's changing Concurrency - SwiftLee](https://www.avanderlee.com/concurrency/swift-6-2-concurrency-changes)
  **Published:** `2025-04-22T09:13:35+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Reviews Swift 6.2 concurrency changes that make isolation and asynchronous code more approachable, including compiler defaults and annotations. It is useful for identifying migration-impacting behavior before enabling the new mode across a project.
- [Swift Reduce: Combining elements into a single value - SwiftLee](https://www.avanderlee.com/swift/swift-reduce-combining-elements-into-a-single-value)
  **Published:** `2025-04-15T07:28:50+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Uses reduce to fold a collection into sums, dictionaries, and other accumulated values, explaining accumulator typing and initial state. The examples help choose reduce where a single pass is clearer than a multi-step transformation.
- [SwiftUI Alert Guide + Code Examples - SwiftLee](https://www.avanderlee.com/swiftui/swiftui-alert-presenting)
  **Published:** `2025-04-07T11:44:45+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Builds SwiftUI alerts from state, including dynamic messages, multiple actions, and reusable error presentation. The patterns clarify how presentation state should be modeled so alerts do not race with view updates.
- [SwiftUI Grid, LazyVGrid, LazyHGrid Explained with Code Examples](https://www.avanderlee.com/swiftui/grid-lazyvgrid-lazyhgrid-gridviews)
  **Published:** `2025-03-31T12:53:32+00:00`
  **Topics:** Concurrency · Performance · Swift · SwiftUI
  **NeKI brief:** Compares Grid, LazyVGrid, and LazyHGrid layout behavior, column definitions, and lazy rendering. The article helps select a grid based on content size and scrolling direction rather than treating the APIs as interchangeable.
- [SwiftUI TabView: Explained with Code Examples - SwiftLee](https://www.avanderlee.com/swiftui/tabview-tabbed-views)
  **Published:** `2025-03-24T12:20:10+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Explains TabView selection, tab items, styles, and state restoration for multi-section SwiftUI apps. The examples are useful for keeping navigation state explicit while adapting presentation across platforms.
- [Picker in SwiftUI explained with code examples](https://www.avanderlee.com/swiftui/picker-styles-color)
  **Published:** `2025-03-10T13:07:12+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Demonstrates Picker bindings and style choices such as menu, segmented, wheel, and navigation-link presentations. It connects control style to platform context and option count instead of only changing appearance.
- [What is Structured Concurrency? - SwiftLee](https://www.avanderlee.com/swift/what-is-structured-concurrency)
  **Published:** `2025-03-03T23:00:00+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Introduces structured concurrency’s parent-child task hierarchy, cancellation propagation, and scoped lifetimes. The model explains why task groups and async let are easier to reason about than detached, unowned work.
- [Task.sleep() vs. Task.yield(): The differences explained](https://www.avanderlee.com/concurrency/task-sleep-vs-yield-differences)
  **Published:** `2025-02-24T13:12:42+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Compares Task.sleep, which suspends for a duration and is cancellation-aware, with Task.yield, which merely gives other work a scheduling opportunity. The timing examples clarify which primitive fits throttling, polling, or cooperative responsiveness.
- [Swift 6: What’s New and How to Migrate](https://www.avanderlee.com/concurrency/swift-6-migrating-xcode-projects-packages)
  **Published:** `2025-02-17T08:53:56+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Explains the goals and major changes of Swift 6 and lays out an incremental migration path for Xcode projects and Swift packages.
- [How to develop an app for iOS](https://www.avanderlee.com/swiftui/how-to-develop-an-app-for-ios)
  **Published:** `2025-02-11T08:52:36+00:00`
  **Topics:** Concurrency · Swift · SwiftUI · Xcode
  **NeKI brief:** Provides a staged path from installing Xcode and choosing a project structure through building, testing, and distributing an iOS app. It is useful as a newcomer roadmap, not as a substitute for framework-specific references.
- [Parameterized tests in Swift: Reducing boilerplate code](https://www.avanderlee.com/swift-testing/parameterized-tests-reducing-boilerplate-code)
  **Published:** `2025-02-04T08:48:32+00:00`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Shows how Swift Testing parameterization turns repeated assertions into one @Test with arguments, including custom types and combinations, so edge cases can be expanded without duplicating test functions.
- [Network Link Conditioner: Simulating Slow Networking](https://www.avanderlee.com/debugging/network-link-conditioner-utility)
  **Published:** `2025-01-27T10:02:13+00:00`
  **Topics:** Concurrency · Networking · Swift · Testing
  **NeKI brief:** Shows how Network Link Conditioner profiles latency, bandwidth, and packet loss on Apple platforms. The workflow helps reproduce loading and retry failures under controlled conditions instead of relying on an engineer’s fast local connection.
- [RocketSim 13.0: Builds Apps Faster - SwiftLee](https://www.avanderlee.com/xcode/rocketsim-simulator-tool)
  **Published:** `2025-01-20T13:39:25+00:00`
  **Topics:** Concurrency · Navigation & Deep Linking · Swift · Testing · Xcode
  **NeKI brief:** Catalogues RocketSim features such as quick builds, touch recordings, device frames, and simulator controls. The link is useful for deciding which repetitive Simulator tasks can be moved into a faster development utility.
- [SwiftUI Lists: Present rows of data explained with code examples](https://www.avanderlee.com/swiftui/list-style-selection)
  **Published:** `2025-01-13T23:00:00+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Covers SwiftUI List styles, selection bindings, row identity, and background customization. The examples expose platform-specific differences that matter when a list must support both navigation and multi-selection.
- [iOS App Development: How to get started?](https://www.avanderlee.com/swift/ios-app-development-software-how-to)
  **Published:** `2025-01-06T23:00:00+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Maps the software stack for iOS development—from Xcode and SDKs to testing and distribution—and explains how the pieces fit together. It is useful for orienting new developers before they choose third-party tools.
- [SwiftLee in 2024: Lessons learned and achievements - SwiftLee](https://www.avanderlee.com/general/swiftlee-in-2024-lessons-learned-and-achievements)
  **Published:** `2024-12-30T23:00:00+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Reflects on SwiftLee's 2024 launches, including courses and a podcast, and the lessons drawn from operating independently. Follow for creator-business context rather than current Swift or App Store guidance.
- [Swift Tutorials: Learn Swift with Easy-to-Follow Code Examples](https://www.avanderlee.com/swift/swift-tutorials-learn-swift-code-examples)
  **Published:** `2024-12-23T09:17:18+00:00`
  **Topics:** Concurrency · Swift · SwiftUI · Testing · Xcode
  **NeKI brief:** Organizes Swift learning around language fundamentals, testing, concurrency, and UI examples, linking concepts to progressively larger exercises. The index is useful for routing a learner to the next missing prerequisite rather than repeating beginner material.
- [SwiftUI Button: Custom Styles, Variants, and Best Practices](https://www.avanderlee.com/swiftui/swiftui-button-styles)
  **Published:** `2024-12-17T00:00:00+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Builds reusable ButtonStyle implementations and shows how role, pressed state, and environment values influence rendering. It helps centralize interaction design while retaining SwiftUI’s accessibility and hit-testing behavior.
- [SF Symbol: How to for Swift & SwiftUI](https://www.avanderlee.com/swift/sf-symbol-guide)
  **Published:** `2024-12-10T12:50:37+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Explains selecting SF Symbols, applying weight, scale, rendering modes, and accessibility labels in Swift and SwiftUI. The guidance helps use Apple’s iconography without treating symbols as unannotated decorative images.
- [Enum explained in-depth with code examples in Swift](https://www.avanderlee.com/swift/enumerations)
  **Published:** `2024-12-03T13:39:07+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Explores enum associated values, pattern matching, fallthrough, Equatable conformance, and CaseIterable. The examples show how enums can model state transitions while keeping exhaustive handling enforced by the compiler.
- [Black Friday: 50% discount on RocketSim & Going Indie Course - SwiftLee](https://www.avanderlee.com/general/black-friday-2024)
  **Published:** `2024-11-25T12:39:30+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Documents a 2024 promotional bundle for RocketSim and an indie-development course. The article can explain the historical product positioning, but its discounts and calls to action are no longer actionable.
- [Contingent pricing for in-app subscriptions - SwiftLee](https://www.avanderlee.com/optimization/contingent-pricing-for-in-app-subscriptions)
  **Published:** `2024-11-19T10:04:11+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Explains StoreKit contingent pricing for offering a subscription price conditioned on another purchase, including eligibility and configuration boundaries. It is useful for evaluating retention offers without implementing ad-hoc discount logic.
- [MainActor usage in Swift explained to dispatch to the main thread](https://www.avanderlee.com/swift/mainactor-dispatch-main-thread)
  **Published:** `2024-11-11T09:09:30+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Clarifies that MainActor isolation expresses UI-thread access but does not make every operation globally synchronous. Examples contrast annotating declarations, hopping with MainActor.run, and avoiding unnecessary main-thread work.
- [URLSession async await: API Requests & JSON Decoding](https://www.avanderlee.com/concurrency/urlsession-async-await-network-requests-in-swift)
  **Published:** `2024-11-05T00:00:00+00:00`
  **Topics:** Concurrency · Networking · Swift
  **NeKI brief:** Builds URLSession requests with async/await, HTTP validation, decoding, and typed error handling without third-party networking frameworks. The sequence provides a concrete baseline for deciding where retries and cancellation belong.
- [Using the #require macro for Swift Testing - SwiftLee](https://www.avanderlee.com/swift-testing/require-macro)
  **Published:** `2024-10-28T08:01:48+00:00`
  **Topics:** Concurrency · Macros & Metaprogramming · Swift · Testing
  **NeKI brief:** Explains #require as Swift Testing’s throwing precondition for setup and optional unwrapping, contrasting its fail-fast behavior with #expect and showing how failure messages retain useful source context.
- [Vapor and Swift Testing: Running tests in parallel - SwiftLee](https://www.avanderlee.com/swift-testing/vapor-and-swift-testing-running-tests-in-parallel)
  **Published:** `2024-10-22T08:29:49+00:00`
  **Topics:** Concurrency · Performance · Persistence & Synchronisation · Swift · Testing
  **NeKI brief:** Explains why Vapor tests become unsafe under Swift Testing’s parallel execution and shows isolation strategies for shared databases and application state, making the concurrency trade-off concrete for server-side Swift.
- [Security-scoped bookmarks for URL access - SwiftLee](https://www.avanderlee.com/swift/security-scoped-bookmarks-for-url-access)
  **Published:** `2024-10-14T07:04:44+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Shows how macOS security-scoped bookmarks persist permission to user-selected files or directories across launches, including resolving and stopping access. The lifecycle details help avoid sandbox failures and leaked access scopes.
- [The Going Indie Podcast with Antoine van der Lee - SwiftLee](https://www.avanderlee.com/general/the-going-indie-podcast-with-antoine-van-der-lee)
  **Published:** `2024-10-08T10:19:48+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Introduces interviews with indie creators about leaving employment, shipping products, and building sustainable businesses. Use the series for varied experience reports, not as a prescriptive career or financial plan.
- [Using the #expect macro for Swift Testing - SwiftLee](https://www.avanderlee.com/swift-testing/expect-macro)
  **Published:** `2024-09-30T11:46:30+00:00`
  **Topics:** Concurrency · Macros & Metaprogramming · Swift · Testing
  **NeKI brief:** Walks through #expect’s expression-aware assertions, including equality, errors, and optional values, and shows how the macro records evaluated subexpressions to make failing tests easier to diagnose.
- [Indie Development: Full Course now Available - SwiftLee](https://www.avanderlee.com/general/indie-development-full-course-now-available)
  **Published:** `2024-09-24T08:58:23+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Presents a course framework for reducing risk while moving from employment toward indie development. It is a useful map of skills and sequencing, while the commercial course content and claims require independent evaluation.
- [Using Traits to annotate and customize test behavior - SwiftLee](https://www.avanderlee.com/swift-testing/using-traits-to-annotate-and-customize-test-behavior)
  **Published:** `2024-09-17T07:42:39+00:00`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Introduces Swift Testing traits for tags, bug links, time limits, and conditional execution, demonstrating how metadata and runtime policies can be attached declaratively to individual tests or suites.
- [Swift Testing: Writing a Modern Unit Test](https://www.avanderlee.com/swift-testing/modern-unit-test)
  **Published:** `2024-09-10T08:19:39+00:00`
  **Topics:** Concurrency · Macros & Metaprogramming · Swift · Testing
  **NeKI brief:** Builds a modern Swift Testing unit test from a small example, covering @Test, #expect, async code, and descriptive names while highlighting the framework’s macro-driven differences from XCTestCase methods.
- [App onboarding funnel optimization to increase conversions](https://www.avanderlee.com/optimization/app-onboarding-funnel-increase-conversions)
  **Published:** `2024-09-02T23:00:00+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Breaks onboarding into measurable funnel stages and discusses when to defer account creation, request permissions, or expose value. The advice is useful for testing conversion hypotheses without confusing completion rate with long-term activation.
- [Designing Apps: 5 Methods to improve your workflow](https://www.avanderlee.com/workflow/designing-apps-5-methods-to-improve-your-workflow)
  **Published:** `2024-08-27T07:00:00+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Presents five concrete design-workflow practices, from early sketches and component reuse to feedback loops and platform conventions. The link helps teams reduce rework before implementation rather than polishing isolated screens late.
- [JSON Parsing in Swift explained with code examples - SwiftLee](https://www.avanderlee.com/swift/json-parsing-decoding)
  **Published:** `2024-08-19T11:58:35+00:00`
  **Topics:** Concurrency · Dependency Injection · Swift
  **NeKI brief:** Demonstrates Codable-based JSON decoding, nested models, custom keys, dates, and error diagnosis. The examples provide a dependency-free baseline and show where custom decoding is preferable to weakening model types.
- [@Entry macro: Creating custom environment values in SwiftUI](https://www.avanderlee.com/swiftui/entry-macro-custom-environment-values)
  **Published:** `2024-08-13T18:33:02+00:00`
  **Topics:** Concurrency · Macros & Metaprogramming · Swift · SwiftUI
  **NeKI brief:** Uses SwiftUI’s @Entry macro to declare custom environment values with less boilerplate, then injects and reads them through the view hierarchy. It is useful when sharing dependencies while keeping defaults and ownership explicit.
- [App design: 5 benefits of using system components](https://www.avanderlee.com/optimization/app-design-5-benefits-of-using-system-components)
  **Published:** `2024-08-06T07:00:00+00:00`
  **Topics:** Accessibility · Concurrency · Performance · Swift
  **NeKI brief:** Explains why system controls improve accessibility, localization, consistency, and maintenance compared with fully custom replacements. The trade-offs help decide when visual customization justifies taking on platform behavior yourself.
- [Going Indie: From Side Project to Going Independent](https://www.avanderlee.com/general/from-side-project-to-going-indie)
  **Published:** `2024-07-29T12:56:44+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Outlines a transition from full-time employment to independent app development, including the role of side projects and revenue. Follow for one practitioner's risk-management narrative rather than a universal business formula.
- [Memory consumption when loading UIImage from disk](https://www.avanderlee.com/swiftui/memory-consumption-loading-uiimage-from-disk)
  **Published:** `2024-07-23T07:00:00+00:00`
  **Topics:** Concurrency · Performance · Swift · SwiftUI
  **NeKI brief:** Measures memory impact when loading UIImage data from disk and compares downsampling strategies for large assets. The article is useful for diagnosing image-driven memory spikes before adding caches or arbitrary autorelease workarounds.
- [Why macOS Development is Perfect for Indie Developers](https://www.avanderlee.com/swiftui/macos-development-powerful-utilities)
  **Published:** `2024-07-16T11:39:36+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Describes macOS utility opportunities, lifecycle differences, and distribution considerations learned from shipping indie apps. It is useful for evaluating a Mac companion product where desktop capabilities can justify a separate target.
- [Inspect network traffic using the Xcode Simulator](https://www.avanderlee.com/xcode/inspect-network-traffic-simulator)
  **Published:** `2024-07-08T23:00:00+00:00`
  **Topics:** Concurrency · Performance · Swift · Xcode
  **NeKI brief:** Compares ways to inspect Simulator network traffic, including proxy configuration and request visibility during development. The workflow helps identify malformed requests, unexpected payloads, and performance problems before server-side investigation.
- [Typed throws in Swift explained with code examples - SwiftLee](https://www.avanderlee.com/swift/typed-throws)
  **Published:** `2024-07-02T09:42:15+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Shows how typed throws constrain a function's error type, including propagation through do-catch and Result. Useful for evaluating where compile-time error specificity improves APIs and where it increases generic/concurrency friction.
- [@Previewable: Dynamic SwiftUI Previews Made Easy](https://www.avanderlee.com/swiftui/previewable-macro-usage-in-previews)
  **Published:** `2024-06-11T07:39:09+00:00`
  **Topics:** Concurrency · Macros & Metaprogramming · Swift · SwiftUI · Xcode
  **NeKI brief:** Explains how @Previewable works in Xcode 16 and uses it to make SwiftUI previews interactive without adding preview-only state to production views.
- [Swift Package Manager framework creation in Xcode - SwiftLee](https://www.avanderlee.com/swift/creating-swift-package-manager-framework)
  **Published:** `2024-06-04T08:10:16+00:00`
  **Topics:** Concurrency · Dependency Injection · Swift · Swift Package Manager · Xcode
  **NeKI brief:** Creates a Swift package in Xcode and covers Package.swift configuration, platform requirements, dependencies, and local development-package workflows.
- [ChatGPT for Swift: Top 5 code generation prompts](https://www.avanderlee.com/swift/chatgpt-code-generation-prompts)
  **Published:** `2024-05-28T07:00:00+00:00`
  **Topics:** AI Development · Concurrency · Swift · Testing
  **NeKI brief:** Presents five prompt patterns for generating Swift code, then stresses supplying context, constraints, and tests so output can be reviewed. Useful as a practical checklist for making AI-assisted coding reproducible rather than speculative.
- [MVVM: An architectural coding pattern to structure SwiftUI Views - SwiftLee](https://www.avanderlee.com/swiftui/mvvm-architectural-coding-pattern-to-structure-views)
  **Published:** `2024-05-21T07:45:24+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Separates SwiftUI view rendering from observable view-model state and actions, while discussing when that indirection helps testing and when it adds ceremony. Useful for choosing MVVM boundaries in larger view hierarchies.
- [Repository design pattern in Swift explained using code examples - SwiftLee](https://www.avanderlee.com/swift/repository-design-pattern)
  **Published:** `2024-05-13T18:45:10+00:00`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Uses a repository abstraction to isolate persistence or networking from callers, with protocols enabling substitutions in tests. The examples clarify the trade-off between centralized data access and an extra layer of indirection.
- [Xcode Build Insights: Keep track of project compilation times - SwiftLee](https://www.avanderlee.com/xcode/xcode-build-insights-keep-track-of-project-compilation-times)
  **Published:** `2024-05-07T11:18:19+00:00`
  **Topics:** Concurrency · Performance · Swift · Xcode
  **NeKI brief:** Demonstrates Xcode Build Insights for recording compilation times and locating expensive targets or files. Useful when turning an anecdotal slow-build complaint into measurable hotspots and prioritised refactoring work.
- [Solve Missing API declaration using required reason (ITMS-91053)](https://www.avanderlee.com/xcode/missing-api-declaration-required-reason-itms-91053)
  **Published:** `2024-04-30T08:39:33+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Explains ITMS-91053 required-reason API failures and maps affected APIs to the privacy manifest declarations App Store validation expects. Useful for diagnosing archive rejection without guessing at unrelated project settings.
- [Using @Environment in SwiftUI to link Swift Package dependencies - SwiftLee](https://www.avanderlee.com/swiftui/environment-property-wrapper)
  **Published:** `2024-04-23T11:23:35+00:00`
  **Topics:** Concurrency · Dependency Injection · Swift · Swift Package Manager · SwiftUI
  **NeKI brief:** Shows injecting shared values through SwiftUI's Environment, including defining custom EnvironmentKey values in a Swift package. Useful for keeping package views configurable without hard-coding app-level dependencies.
- [Bar Chart creation using Swift Charts - SwiftLee](https://www.avanderlee.com/swift-charts/bar-chart-creation-using-swift-charts)
  **Published:** `2024-04-16T09:15:48+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Builds a bar chart with Swift Charts by mapping model values to BarMark and configuring axes, labels, and styling. Useful as a concrete starting point for data-driven chart views.
- [Statistical significance and its importance with app experiments](https://www.avanderlee.com/general/statistical-significance-app-experiments)
  **Published:** `2024-04-09T07:00:00+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Explains why experiment results need statistical significance rather than raw conversion differences, and connects sample size and confidence to product decisions. Useful for avoiding premature conclusions from noisy A/B tests.
- [Identifiable protocol in SwiftUI explained with code examples - SwiftLee](https://www.avanderlee.com/swiftui/identifiable-protocol-object-identifier)
  **Published:** `2024-04-02T08:07:42+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Compares stable model identifiers with ObjectIdentifier-based identity in SwiftUI. Useful for understanding how ForEach diffing behaves and why identity must remain stable when rows are updated or reordered.
- [Key press events detection in SwiftUI - SwiftLee](https://www.avanderlee.com/swiftui/key-press-events-detection)
  **Published:** `2024-03-26T08:41:37+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Handles keyboard input in SwiftUI using key-event modifiers and phases, including modifier flags. Useful for making iPad hardware-keyboard and macOS-style shortcuts respond without dropping events into UIKit bridges.
- [The power of consistency in side projects - SwiftLee](https://www.avanderlee.com/optimization/the-power-of-consistency-in-side-projects)
  **Published:** `2024-03-19T08:00:00+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Argues that sustained, focused iteration compounds side-project progress and audience signals. Use it to frame execution habits and measurement cadence; the implied revenue outcomes remain anecdotal.
- [Test-Driven Development (TDD) for bug fixes in Swift - SwiftLee](https://www.avanderlee.com/workflow/test-driven-development-tdd-for-bug-fixes-in-swift)
  **Published:** `2024-03-12T09:19:08+00:00`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Frames a bug fix as a regression test first, then the smallest implementation change that makes it pass. Useful for preserving the failure case and preventing a narrowly fixed defect from returning.
- [Optionals in Swift explained: 5 things you should know - SwiftLee](https://www.avanderlee.com/swift/optionals-in-swift-explained-5-things-you-should-know)
  **Published:** `2024-03-05T14:45:22+00:00`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Walks through optional binding, map/flatMap, nil coalescing, and optional chaining with contrasting examples. Useful for choosing explicit failure handling instead of piling force unwraps into production code.
- [Third-party libraries acknowledgments using a Settings bundle](https://www.avanderlee.com/workflow/third-party-libraries-acknowledgments-swift-packages)
  **Published:** `2024-02-27T10:05:22+00:00`
  **Topics:** Concurrency · Swift · Swift Package Manager
  **NeKI brief:** Builds a Settings bundle acknowledgement screen from Swift Package dependencies, turning package metadata into user-visible credits. Useful for satisfying attribution requirements while keeping acknowledgements aligned with dependency changes.
- [Extensions in Swift: How and when to use them - SwiftLee](https://www.avanderlee.com/swift/extensions)
  **Published:** `2024-02-20T13:59:52+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Shows extensions for grouping protocol conformances and related behavior while warning against hiding core state or creating oversized catch-all files. Useful for deciding when an extension improves cohesion versus scattering implementation.
- [How to use @ScaledMetric in SwiftUI for Dynamic Type support](https://www.avanderlee.com/swiftui/scaledmetric-dynamic-type-support)
  **Published:** `2024-02-13T09:08:14+00:00`
  **Topics:** Accessibility · Concurrency · Swift · SwiftUI · Testing
  **NeKI brief:** Uses @ScaledMetric to scale custom dimensions with the user's Dynamic Type setting, alongside text styles. Useful when controls and spacing need accessibility scaling without manually observing size categories.
- [App Preview Videos Capturing using the Xcode simulator - SwiftLee](https://www.avanderlee.com/workflow/capture-ios-simulator-video-app-preview)
  **Published:** `2024-02-04T12:26:16+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Uses Simulator recording and command-line tooling to capture App Store preview footage, with steps for device framing and clean output. Useful for repeatable marketing captures without a physical-device camera rig.
- [Status bar overrides in the iOS Simulator](https://www.avanderlee.com/workflow/status-bar-overrides-in-the-ios-simulator)
  **Published:** `2024-01-30T08:23:21+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Configures Simulator status-bar overrides so time, battery, and connectivity appear deterministic in screenshots and recordings. Useful for producing consistent UI evidence and App Store imagery across capture runs.
- [ScrollView Bounce Behavior configuration in SwiftUI](https://www.avanderlee.com/swiftui/scrollview-bounce-behavior)
  **Published:** `2024-01-23T08:33:41+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Configures ScrollView bounce independently per axis with the modern scrollBounceBehavior modifier. Useful when nested or horizontally paged layouts need controlled elasticity without globally disabling expected scrolling physics.
- [Concurrency-safe global variables to prevent data races - SwiftLee](https://www.avanderlee.com/concurrency/concurrency-safe-global-variables-to-prevent-data-races)
  **Published:** `2024-01-16T08:39:40+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Replaces mutable global state with actor isolation or other synchronization so concurrent tasks cannot race. Useful for auditing legacy globals and choosing an ownership boundary the compiler can enforce.
- [@Observable Macro performance increase over ObservableObject](https://www.avanderlee.com/swiftui/observable-macro-performance-increase-observableobject)
  **Published:** `2024-01-09T08:00:00+00:00`
  **Topics:** Concurrency · Macros & Metaprogramming · Observation & State Management · Performance · Swift · SwiftUI
  **NeKI brief:** Compares the Observation framework's @Observable macro with ObservableObject, focusing on property-level tracking and view invalidation. The measurements and migration examples explain why fewer unnecessary updates can improve SwiftUI performance.
- [Swift Newsletters: How to stay up to date as an app developer - SwiftLee](https://www.avanderlee.com/optimization/swift-newsletters)
  **Published:** `2024-01-02T08:00:00+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Explains how a developer can build a deliberate reading routine from Swift newsletters and filter useful updates. The workflow is valuable for information triage, although publication availability and recommendations change over time.
- [SwiftLee 2023: A Year in Review - SwiftLee](https://www.avanderlee.com/general/swiftlee-2023-a-year-in-review)
  **Published:** `2023-12-27T08:00:00+00:00`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Summarizes SwiftLee's 2023 growth across articles, newsletters, and RocketSim. It provides historical creator-business context and shows how multiple channels were combined, not current technical guidance.
- [Using campaign links to track impressions, downloads, and sales](https://www.avanderlee.com/optimization/campaign-links-app-store-connect)
  **Published:** `2023-12-19T08:08:01+00:00`
  **Topics:** Concurrency · Performance · Swift
  **NeKI brief:** Uses App Store campaign links and their analytics to distinguish impressions, downloads, and sales by acquisition source. Useful for connecting promotional work to measurable store outcomes instead of relying on aggregate totals.
- [Symbolicate crash logs with Xcode - SwiftLee](https://www.avanderlee.com/xcode/symbolicate-crash-logs-reports)
  **Published:** `2023-12-12T08:35:59+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Explains symbolication by matching a crash report with the exact archive's dSYM, then locating the original Swift call site. Useful when diagnosing release-only crashes whose addresses are otherwise unreadable.
- [SFSafariViewController in SwiftUI: Open webpages in-app - SwiftLee](https://www.avanderlee.com/swiftui/sfsafariviewcontroller-open-webpages-in-app)
  **Published:** `2023-12-06T09:13:43+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Wraps SFSafariViewController in UIViewControllerRepresentable so SwiftUI can present an authenticated, in-app browser while retaining Safari's security model. Useful when a web flow should not leave the app context.
- [Swift Evolution: Reading and learning from proposals - SwiftLee](https://www.avanderlee.com/swift/swift-evolution-proposals)
  **Published:** `2023-11-28T09:01:01+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Describes a workflow for reading Swift Evolution proposals: identify motivation, review alternatives, and track implementation status. Useful for assessing upcoming language changes before adopting a proposal's syntax or assumptions.
- [Unit testing async/await Swift code - SwiftLee](https://www.avanderlee.com/concurrency/unit-testing-async-await)
  **Published:** `2023-11-21T07:52:59+00:00`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Shows how to structure async XCTest methods, await asynchronous values, and test throwing paths without races. The examples cover expectations and actor-aware setup, giving a concrete migration path from callback-based tests.
- [Debugging SwiftUI views: what caused that change? - SwiftLee](https://www.avanderlee.com/swiftui/debugging-swiftui-views)
  **Published:** `2023-11-13T13:19:06+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Shows techniques for identifying which state change caused a SwiftUI view update. Follow it when body recomputation is surprising and you need instrumentation before optimizing layout or observation.
- [Promotional offers: Increase App Revenue using discounts - SwiftLee](https://www.avanderlee.com/optimization/promotional-offers-increase-app-revenue-using-discounts)
  **Published:** `2023-10-31T08:16:50+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Compares App Store promotional offer mechanisms and the eligibility or configuration work behind discounts. Useful for designing subscription promotions that are technically valid and measurable rather than merely changing displayed prices.
- [User Defaults reading and writing in Swift - SwiftLee](https://www.avanderlee.com/swift/user-defaults-preferences)
  **Published:** `2023-10-23T17:31:53+00:00`
  **Topics:** Concurrency · Persistence & Synchronisation · Swift
  **NeKI brief:** Covers UserDefaults registration, typed access, and suite selection for lightweight preferences. Useful for separating defaults from sensitive or relational data and avoiding scattered string-key persistence.
- [Thread dispatching and Actors: understanding execution - SwiftLee](https://www.avanderlee.com/concurrency/thread-dispatching-actor-execution)
  **Published:** `2023-10-17T07:33:53+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Contrasts dispatch queues and actors by tracing where work executes and how isolation serializes access. Useful for migrating queue-based code while preserving execution guarantees and spotting accidental main-thread assumptions.
- [@preconcurrency: Incremental migration to concurrency checking](https://www.avanderlee.com/concurrency/preconcurrency-checking-swift)
  **Published:** `2023-10-10T07:12:09+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Uses @preconcurrency imports to stage a migration toward strict concurrency checking when dependencies are not yet annotated. It explains which diagnostics are suppressed and why the annotation should be temporary and narrowly scoped.
- [Picking your minimum iOS version to support - SwiftLee](https://www.avanderlee.com/workflow/minimum-ios-version)
  **Published:** `2023-10-03T07:16:15+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Frames minimum-OS support as a product and engineering trade-off involving API availability, testing matrix, and adoption data. Useful for making deployment-target decisions explicit before implementation begins.
- [Value and Type parameter packs in Swift explained with examples](https://www.avanderlee.com/swift/value-and-type-parameter-packs)
  **Published:** `2023-09-26T08:26:44+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Introduces parameter packs for generic functions and types that accept a compile-time variable number of arguments. Useful for replacing overload families while understanding pack expansion and type-safety constraints.
- [App Intent driven development in Swift and SwiftUI - SwiftLee](https://www.avanderlee.com/swift/app-intent-driven-development)
  **Published:** `2023-09-19T07:44:37+00:00`
  **Topics:** App Intents & System Surfaces · Concurrency · Swift · SwiftUI
  **NeKI brief:** Treats App Intents as a design input rather than an afterthought, modeling app actions and entities so Siri, Shortcuts, and Spotlight can invoke them. The examples connect intent definitions to SwiftUI app behavior and discoverability.
- [If and switch expressions in Swift - SwiftLee](https://www.avanderlee.com/swift/if-switch-expressions)
  **Published:** `2023-09-12T07:22:56+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Uses if and switch as expressions to assign values directly, reducing temporary mutable variables. Useful for concise branching while retaining exhaustiveness and making refactors easier to review.
- [Predicate Macro in Swift for filtering and searching - SwiftLee](https://www.avanderlee.com/swift/predicate-macro-filtering-searching)
  **Published:** `2023-09-05T08:40:34+00:00`
  **Topics:** Concurrency · Macros & Metaprogramming · Swift
  **NeKI brief:** Builds Swift predicates with the #Predicate macro, including optional relationships and reusable filtering expressions. The article is useful when translating in-memory searches into type-checked SwiftData or Core Data queries without relying on string predicates.
- [SwiftSyntax: Parse and Generate Swift source code - SwiftLee](https://www.avanderlee.com/swift/swiftsyntax-parse-and-generate-swift-source-code)
  **Published:** `2023-08-29T08:52:24+00:00`
  **Topics:** Concurrency · Macros & Metaprogramming · Swift
  **NeKI brief:** Uses SwiftSyntax to parse source files and generate formatted Swift code, walking syntax nodes instead of manipulating text. The pipeline is a useful starting point for linters, refactoring tools, and source-generating macros.
- [Xcode Debug Console Tour: Exploring All Options - SwiftLee](https://www.avanderlee.com/xcode/xcode-debug-console)
  **Published:** `2023-08-08T08:28:45+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Tours Xcode's debug console commands, expression evaluation, and output controls for inspecting a running process. Useful for choosing lightweight runtime probes before adding permanent logging or altering code.
- [Localization testing in Xcode - SwiftLee](https://www.avanderlee.com/xcode/localization-testing-in-xcode)
  **Published:** `2023-08-01T07:08:07+00:00`
  **Topics:** Concurrency · Swift · SwiftUI · Testing · Xcode
  **NeKI brief:** Configures Xcode schemes and previews to test localized strings, right-to-left layouts, and longer translations. Useful for finding truncation and layout assumptions before translators or users expose them.
- [OSLog and Unified logging as recommended by Apple - SwiftLee](https://www.avanderlee.com/debugging/oslog-unified-logging)
  **Published:** `2023-07-18T07:50:36+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Sets up OSLog categories and privacy-aware interpolation, then uses Console and Instruments to inspect signposts and messages. Useful for production diagnostics without leaking sensitive values or flooding logs.
- [@backDeployed to extend function availability to older OS releases](https://www.avanderlee.com/swift/backdeployed-function-back-deployment)
  **Published:** `2023-07-11T07:50:33+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Explains the @backDeployed attribute for shipping a newer implementation while supplying a fallback to older OS releases. It distinguishes back deployment from availability checks and shows the constraints that affect API design.
- [App Intents Spotlight integration using Shortcuts - SwiftLee](https://www.avanderlee.com/swiftui/app-intents-spotlight-integration-using-shortcuts)
  **Published:** `2023-07-05T08:15:59+00:00`
  **Topics:** App Intents & System Surfaces · Concurrency · Swift · SwiftUI
  **NeKI brief:** Connects App Intents to Spotlight and Shortcuts by defining discoverable actions and entities. Useful for designing intent parameters and donation behavior so app capabilities become searchable system actions.
- [#Preview SwiftUI Views using Macros - SwiftLee](https://www.avanderlee.com/xcode/preview-swiftui-uikit-appkit-views)
  **Published:** `2023-06-27T07:35:07+00:00`
  **Topics:** Concurrency · Macros & Metaprogramming · Swift · SwiftUI · UIKit · Xcode
  **NeKI brief:** Uses the #Preview macro to render SwiftUI, UIKit, and AppKit views, including wrapper setup for controller-based components. Useful for shortening visual feedback loops across mixed UI stacks.
- [Xcode Bookmarks: Save code landmarks & organize tasks](https://www.avanderlee.com/xcode/bookmarks-navigator)
  **Published:** `2023-06-20T07:36:03+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Uses Xcode bookmarks to mark code landmarks and group follow-up work independently of source comments. Useful for maintaining a navigable review queue without leaving temporary TODO clutter in production files.
- [Swift Macros: Extend Swift with New Kinds of Expressions](https://www.avanderlee.com/swift/macros)
  **Published:** `2023-06-13T08:03:31+00:00`
  **Topics:** Concurrency · Macros & Metaprogramming · Swift · Testing
  **NeKI brief:** Explains Swift macro roles and expansion, distinguishing freestanding from attached macros and showing generated declarations. Useful for evaluating when compile-time code generation reduces boilerplate without obscuring API behavior.
- [ContentUnavailableView: Handling Empty States in SwiftUI](https://www.avanderlee.com/swiftui/contentunavailableview-handling-empty-states)
  **Published:** `2023-06-06T14:44:20+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Introduces ContentUnavailableView for standard empty and error states, including custom labels and actions. Useful for consistent SwiftUI fallback screens that communicate why content is absent and what the user can do.
- [Share Swift Code between Swift On Server Vapor and Client App](https://www.avanderlee.com/swift/share-swift-code-swift-on-server-vapor)
  **Published:** `2023-05-30T07:35:04+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Shares Swift models and logic between a Vapor server and client target through a package, while isolating platform-specific code. Useful for reducing duplicated validation and keeping wire representations aligned.
- [10 Tips to Get Your App Featured on the App Store - SwiftLee](https://www.avanderlee.com/optimization/getting-app-featured-app-store)
  **Published:** `2023-05-23T07:48:51+00:00`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Shares tactics the author associates with repeated App Store editorial featuring, such as polish, timing, and presentation. Treat the list as a hypothesis checklist because editorial selection is discretionary and changes.
- [Ranges in Swift explained with code examples - SwiftLee](https://www.avanderlee.com/swift/ranges-explained)
  **Published:** `2023-05-15T12:15:32+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Compares closed, half-open, and one-sided ranges and shows their use in slicing and pattern matching. Useful for preventing off-by-one errors while expressing interval intent directly in Swift.
- [Optimizing your app for Network Reachability - SwiftLee](https://www.avanderlee.com/swift/optimizing-network-reachability)
  **Published:** `2023-04-25T07:45:16+00:00`
  **Topics:** Concurrency · Networking · Swift · Testing
  **NeKI brief:** Uses NWPathMonitor to observe connectivity without treating reachability as proof that a request will succeed. Useful for gating retries or UI hints while keeping the server response authoritative.
- [Deeplink URL handling in SwiftUI - SwiftLee](https://www.avanderlee.com/swiftui/deeplink-url-handling)
  **Published:** `2023-04-18T07:00:00+00:00`
  **Topics:** Concurrency · Navigation & Deep Linking · Swift · SwiftUI · Testing
  **NeKI brief:** Implements SwiftUI deep links by parsing incoming URLs, mapping routes into navigation state, and handling links while the app is active or launching. It highlights where scene and view lifecycle timing affects reliable routing.
- [Network Extension Debugging on macOS - SwiftLee](https://www.avanderlee.com/debugging/network-extension-debugging-macos)
  **Published:** `2023-04-04T07:00:00+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Outlines debugging Network Extension providers on macOS, including scheme setup, host/container processes, and console inspection. Useful when extension code runs outside the ordinary app debugger lifecycle.
- [Running Xcode on top of iPad - SwiftLee](https://www.avanderlee.com/xcode/running-xcode-on-top-of-ipad)
  **Published:** `2023-04-01T06:08:36+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Explores using an iPad as a display or remote surface while Xcode runs on a Mac, noting input and performance limits. Useful for assessing mobile development setups before investing in hardware workflows.
- [Location Simulation in Xcode's Simulator - SwiftLee](https://www.avanderlee.com/workflow/location-simulation-xcode-simulator)
  **Published:** `2023-03-28T07:33:04+00:00`
  **Topics:** Concurrency · Swift · Testing · Xcode
  **NeKI brief:** Configures custom GPX routes and location simulation in Xcode to exercise geofencing and map behavior. Useful for repeatable location tests that would be difficult to reproduce with manual device movement.
- [The operation couldn't be completed: solving errors in Swift](https://www.avanderlee.com/swift/operation-couldnt-completed-error-code)
  **Published:** `2023-03-21T08:00:00+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Shows how to inspect NSError domains and codes behind the generic 'operation couldn't be completed' message. Useful for replacing vague error handling with actionable diagnostics and user-facing recovery paths.
- [Equatable conformance in Swift explained with code examples](https://www.avanderlee.com/swift/equatable-comparible-conformance)
  **Published:** `2023-03-07T08:09:46+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Explains implementing Equatable by selecting value-defining fields and using synthesized conformance when possible. Useful for predictable diffing and tests while avoiding equality that accidentally ignores meaningful state.
- [View Composition using ViewModifiers in SwiftUI - SwiftLee](https://www.avanderlee.com/swiftui/view-composition-viewmodifiers)
  **Published:** `2023-02-28T08:35:39+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Builds reusable SwiftUI styling through ViewModifier types and custom modifier extensions. Useful for centralizing visual policy while keeping call sites readable and avoiding repeated modifier chains.
- [Introducing Roadmap: Offer Public Feature Voting](https://www.avanderlee.com/swiftui/roadmap-free-public-feature-voting)
  **Published:** `2023-02-21T08:28:48+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Introduces a public roadmap and feature-voting process for SwiftUI-related development. Use it to understand community prioritization and product feedback loops, while treating roadmap items as non-binding plans.
- [Detached Tasks in Swift explained with code examples - SwiftLee](https://www.avanderlee.com/concurrency/detached-tasks)
  **Published:** `2023-02-07T08:46:06+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Details what Task.detached gives up compared with structured child tasks: inherited priority, actor context, task-local values, and cancellation. The examples frame detached tasks as an escape hatch requiring explicit ownership and Sendable data.
- [Xcode Simulator Directories Exploration - SwiftLee](https://www.avanderlee.com/xcode/simulator-directories-access)
  **Published:** `2023-01-31T08:45:38+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Maps Simulator application, data, and container directories and shows how to reach them from Finder or Terminal. Useful for inspecting persisted state and test artifacts without confusing device and host paths.
- [Task Groups in Swift explained with code examples - SwiftLee](https://www.avanderlee.com/concurrency/task-groups-in-swift)
  **Published:** `2023-01-17T09:12:54+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Builds a task group to fan out work, collect child results, and propagate cancellation or errors. The article compares throwing and non-throwing groups and shows how dynamic task counts fit structured concurrency.
- [Engineering goals: How to become a more successful developer](https://www.avanderlee.com/optimization/engineering-goals-become-successful-developer)
  **Published:** `2023-01-03T08:54:10+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Turns broad engineering ambitions into measurable goals with a feedback loop and review cadence. Useful for connecting technical growth to observable outcomes rather than maintaining an unprioritized learning list.
- [SwiftLee 2022: A Year in Review - SwiftLee](https://www.avanderlee.com/general/swiftlee-2022-a-year-in-review)
  **Published:** `2022-12-20T08:00:00+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Reviews SwiftLee's 2022 milestones, revenue experiments, and goals for the following year. It is useful as a dated indie-development case study, not evidence for present market expectations.
- [OptionSet in Swift explained with code examples - SwiftLee](https://www.avanderlee.com/swift/optionset-swift)
  **Published:** `2022-12-13T08:26:30+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Implements bitmask-style flags with OptionSet, including raw values, insertion, and membership checks. Useful for modeling combinable capabilities more clearly than parallel booleans or magic integers.
- [How to use FormatStyle to restrict TextField input in SwiftUI](https://www.avanderlee.com/swiftui/formatstyle-formatter-restrict-textfield-input)
  **Published:** `2022-12-06T08:33:45+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Uses FormatStyle and Formatter integration to constrain TextField input while preserving typed values. Useful for validating numeric or date entry at the boundary without duplicating parsing logic in view state.
- [Sheets in SwiftUI explained with code examples - SwiftLee](https://www.avanderlee.com/swiftui/presenting-sheets)
  **Published:** `2022-11-29T09:18:49+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Compares sheet presentation driven by Boolean and identifiable item state, including dismissal and nested content. Useful for avoiding stale modal data and making SwiftUI presentation follow model state.
- [@dynamicCallable in Swift explained with code examples](https://www.avanderlee.com/swift/dynamiccallable)
  **Published:** `2022-11-22T09:32:05+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Adds call syntax to types with @dynamicCallable, forwarding arguments into a defined method. Useful for DSL-like wrappers, while the examples expose the loss of ordinary compile-time call-site clarity.
- [Binary Targets in Swift Package Manager - SwiftLee](https://www.avanderlee.com/swift/binary-targets-swift-package-manager)
  **Published:** `2022-11-15T09:37:59+00:00`
  **Topics:** Concurrency · Swift · Swift Package Manager
  **NeKI brief:** Configures binary targets in Swift Package Manager using artifacts or XCFrameworks, including checksum and distribution concerns. Useful for shipping prebuilt proprietary code while understanding portability and cache trade-offs.
- [Result builders in Swift explained with code examples - SwiftLee](https://www.avanderlee.com/swift/result-builders)
  **Published:** `2022-11-08T10:12:43+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Builds a custom result builder and traces how builder methods transform declarative blocks into a value. Useful for understanding control-flow limitations and designing readable DSL APIs.
- [Getting started with Unit Tests in Swift - SwiftLee](https://www.avanderlee.com/swift/unit-tests-best-practices)
  **Published:** `2022-11-01T08:57:10+00:00`
  **Topics:** Concurrency · Swift · Testing · Xcode
  **NeKI brief:** Covers unit-test isolation, naming, deterministic fixtures, and focused assertions in Swift. Useful for reducing flaky tests and making failures identify behavior rather than implementation details.
- [Refactoring Swift: Best Practices to succeed](https://www.avanderlee.com/optimization/refactoring-swift-best-practices)
  **Published:** `2022-10-25T07:52:50+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Frames a large Swift refactor as small, compiler-guided steps protected by tests and a deliberately narrow scope. Use it to maintain behavioral confidence while restructuring code instead of combining cleanup with unrelated feature changes.
- [Announcing the SwiftLee Talent Collective](https://www.avanderlee.com/swift/swiftlee-talent-collective)
  **Published:** `2022-10-18T07:51:27+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Announces a talent-matching service connecting Swift developers with companies and salary expectations. The page is recruitment-oriented; use it only to understand the historical offering, not as independent career advice.
- [Alternate App Icon Configuration in Xcode - SwiftLee](https://www.avanderlee.com/swift/alternate-app-icon-configuration-in-xcode)
  **Published:** `2022-10-11T07:53:11+00:00`
  **Topics:** Concurrency · Swift · SwiftUI · Xcode
  **NeKI brief:** Configures alternate icons through asset catalogs and Info.plist entries, then switches them with UIApplication. Useful for implementing seasonal or user-selected icons while respecting system prompts and reset behavior.
- [Never keyword in Swift: return type explained with code examples](https://www.avanderlee.com/swift/never-keyword)
  **Published:** `2022-10-04T07:20:26+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Explains Never as an uninhabited return type for functions that cannot complete normally, including fatal paths and exhaustive switches. Useful for expressing control-flow guarantees to the compiler and readers.
- [Side Projects: 10 Tips for being successful - SwiftLee](https://www.avanderlee.com/optimization/side-projects-10-tips-for-being-successful)
  **Published:** `2022-09-27T08:05:32+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Collects practical habits for finishing and launching side projects under limited time. Follow it for scope, cadence, and launch-process prompts while adapting the advice to the project's actual constraints.
- [Deadlocks in Swift explained: detecting and solving - SwiftLee](https://www.avanderlee.com/swift/deadlocks-detecting-solving)
  **Published:** `2022-09-20T08:25:43+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Illustrates deadlocks caused by synchronous waits and lock-order cycles, then applies safer asynchronous or ordered access. Useful for diagnosing hangs that produce no crash and designing synchronization with explicit ownership.
- [Variable WidgetBundle configuration based on conditions - SwiftLee](https://www.avanderlee.com/swiftui/variable-widgetbundle-configuration)
  **Published:** `2022-09-13T08:45:59+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Builds a WidgetBundle whose included widgets vary by configuration or platform conditions. Useful when shipping one extension across products or OS versions without registering unsupported widget types.
- [Accessibility in SwiftUI explained for UIKit developers - SwiftLee](https://www.avanderlee.com/swiftui/accessibility-uikit-developers)
  **Published:** `2022-09-05T23:00:00+00:00`
  **Topics:** Accessibility · Concurrency · Swift · SwiftUI · UIKit
  **NeKI brief:** Maps UIKit accessibility concepts to SwiftUI modifiers for labels, traits, grouping, and adjustable controls. Useful for porting accessibility behavior deliberately instead of assuming visual SwiftUI structure is automatically semantic.
- [VoiceOver navigation improvement tips for SwiftUI apps - SwiftLee](https://www.avanderlee.com/swiftui/voiceover-navigation-improvement-tips)
  **Published:** `2022-08-29T23:00:00+00:00`
  **Topics:** Accessibility · Concurrency · Swift · SwiftUI
  **NeKI brief:** Improves VoiceOver traversal by grouping related elements, supplying custom actions, and controlling sort priority. Useful for fixing navigation that is technically exposed but inefficient for screen-reader users.
- [Faster StoreKit testing by syncing in-app purchase products](https://www.avanderlee.com/xcode/storekit-testing-syncing-configuration-file)
  **Published:** `2022-08-16T07:00:00+00:00`
  **Topics:** Concurrency · Swift · Testing · Xcode
  **NeKI brief:** Uses StoreKit configuration synchronization to refresh local in-app-purchase products from App Store Connect, reducing manual fixture drift. Useful for faster purchase testing while keeping local products aligned with production metadata.
- [Shared with You implementation and testing explained - SwiftLee](https://www.avanderlee.com/swift/shared-with-you)
  **Published:** `2022-08-09T15:18:02+00:00`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Integrates Shared with You by saving incoming metadata, exposing a SWHighlightCenter, and testing shared URLs. Useful for making content discoverable in system surfaces without building a parallel sharing database.
- [Sendable and @Sendable closures explained with code examples](https://www.avanderlee.com/swift/sendable-protocol-closures)
  **Published:** `2022-08-02T07:59:00+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Explains Sendable and @Sendable closures as compiler contracts for values crossing concurrency domains, with examples of structs, classes, and captured state. It identifies why seemingly harmless captures trigger diagnostics and how to redesign them safely.
- [UIViewRepresentable explained to host UIView instances in SwiftUI](https://www.avanderlee.com/swiftui/integrating-swiftui-with-uikit)
  **Published:** `2022-07-26T07:19:53+00:00`
  **Topics:** Concurrency · Swift · SwiftUI · UIKit · Xcode
  **NeKI brief:** Wraps a UIView inside UIViewRepresentable and coordinates make/update lifecycle methods with SwiftUI state. Useful for incremental UIKit-to-SwiftUI migration when a control has no native SwiftUI equivalent.
- [URLSessionConfiguration: Exploring opt-in configurations - SwiftLee](https://www.avanderlee.com/swift/urlsessionconfiguration)
  **Published:** `2022-07-19T08:05:51+00:00`
  **Topics:** Concurrency · Networking · Performance · Swift
  **NeKI brief:** Compares URLSessionConfiguration choices for default, ephemeral, and background sessions, including caching, credentials, connectivity, and timeout behavior. The option-by-option examples help match transport policy to the app's privacy and reliability requirements.
- [App Store Connect API SDK in Swift: Creating Developer Tools - SwiftLee](https://www.avanderlee.com/swift/app-store-connect-api-adoption)
  **Published:** `2022-07-12T17:15:35+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Walks through generating a Swift SDK around the App Store Connect API, including JWT authentication, endpoint models, and pagination concerns. It provides concrete structure for building repeatable developer tooling instead of scripting individual requests.
- [Generics in Swift explained with code examples - SwiftLee](https://www.avanderlee.com/swift/generics-constraints)
  **Published:** `2022-07-05T07:43:43+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Uses generic constraints and where clauses to express relationships between types, reducing casts and overload duplication. Useful for designing reusable APIs whose valid combinations are checked at compile time.
- [Existential any in Swift explained with code examples - SwiftLee](https://www.avanderlee.com/swift/existential-any)
  **Published:** `2022-06-28T07:00:00+00:00`
  **Topics:** Accessibility · Concurrency · Performance · Swift
  **NeKI brief:** Contrasts existential any with generic parameters and opaque some types, showing when values erase their concrete type. Useful for choosing dynamic heterogeneity versus static specialization and understanding associated-type limitations.
- [Some keyword in Swift: Opaque types explained with code examples](https://www.avanderlee.com/swift/some-opaque-types)
  **Published:** `2022-06-21T08:48:09+00:00`
  **Topics:** Concurrency · Performance · Swift
  **NeKI brief:** Explains opaque result types with some, preserving a hidden concrete type while exposing protocol behavior. Useful for SwiftUI builders and API design where callers need static identity without seeing implementation types.
- [Using NavigationLink programmatically based on binding in SwiftUI](https://www.avanderlee.com/swiftui/navigationlink-programmatically-binding)
  **Published:** `2022-06-14T07:58:22+00:00`
  **Topics:** Concurrency · Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Shows binding-driven NavigationLink routing in SwiftUI, including activating a destination from optional state and clearing that state on dismissal. The pattern is useful for replacing imperative navigation flags with data-driven presentation.
- [App Icon Generator is no longer needed with Xcode 14 - SwiftLee](https://www.avanderlee.com/xcode/replacing-app-icon-generators)
  **Published:** `2022-06-07T09:25:22+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Shows how Xcode 14's asset catalog support replaces external app-icon generator tools, including alternate icon setup. Useful for simplifying build pipelines and keeping icon variants inside the project source of truth.
- [Increase App Ratings by using SKStoreReviewController - SwiftLee](https://www.avanderlee.com/swift/skstorereviewcontroller-app-ratings)
  **Published:** `2022-05-31T07:57:45+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Covers requesting reviews with SKStoreReviewController, including scene-aware invocation and Apple's throttling. Useful for placing prompts at appropriate moments while accepting that the system may decline to display one.
- [Markdown rendering using Text in SwiftUI - SwiftLee](https://www.avanderlee.com/swiftui/markdown-text)
  **Published:** `2022-05-24T06:42:34+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Renders Markdown inline with SwiftUI Text and handles parsing failures or attributed styling. Useful for displaying server-authored rich text without embedding a web view for simple formatting.
- [Memory leaks prevention using an autoreleasepool in unit tests - SwiftLee](https://www.avanderlee.com/swift/memory-leaks-unit-tests)
  **Published:** `2022-05-10T07:25:29+00:00`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Uses autoreleasepool around repeated unit-test allocations to surface leaks and bound temporary Objective-C memory. Useful for differentiating retained-object leaks from allocator growth during stress tests.
- [AsyncSequence explained with Code Examples - SwiftLee](https://www.avanderlee.com/concurrency/asyncsequence)
  **Published:** `2022-05-03T07:18:43+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Introduces AsyncSequence by adapting asynchronous event sources and consuming them with for-await-in. Examples cover iteration, cancellation, and throwing sequences, making the article a practical bridge from callback or Combine streams to structured concurrency.
- [AsyncThrowingStream and AsyncStream explained with code examples](https://www.avanderlee.com/swift/asyncthrowingstream-asyncstream)
  **Published:** `2022-04-26T07:51:56+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Bridges callback or delegate events into AsyncStream and AsyncThrowingStream, covering continuation yield, finish, and cancellation. Useful for migrating event APIs to for-await-in while preserving termination and error semantics.
- [Downloading and Caching images in SwiftUI - SwiftLee](https://www.avanderlee.com/swiftui/downloading-caching-images)
  **Published:** `2022-04-19T07:08:36+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Implements asynchronous image loading with in-memory caching and SwiftUI state updates, including placeholder and failure paths. Useful for avoiding duplicate requests and keeping scrolling views responsive.
- [Using MetricKit to monitor user data like launch times - SwiftLee](https://www.avanderlee.com/swift/metrickit-launch-time)
  **Published:** `2022-04-12T07:20:27+00:00`
  **Topics:** Concurrency · Performance · Swift
  **NeKI brief:** Shows how MetricKit delivers aggregated launch and performance payloads from real devices, including subscription and payload parsing. It helps connect production launch-time measurements to actionable trends without collecting a per-user trace.
- [Disable animations on a specific view in SwiftUI using transactions](https://www.avanderlee.com/swiftui/disable-animations-transactions)
  **Published:** `2022-04-05T07:16:57+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Disables animation for a specific SwiftUI update by changing the transaction rather than globally disabling animations. Useful when one state transition must snap while unrelated view updates retain motion.
- [AnyObject, Any, and any: When to use which?](https://www.avanderlee.com/swift/anyobject-any)
  **Published:** `2022-03-22T11:33:32+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Distinguishes AnyObject class constraints, Any value erasure, and the any existential spelling. Useful for modernizing APIs and avoiding accidental reference-type requirements or unnecessary type casts.
- [How to use the #available attribute in Swift - SwiftLee](https://www.avanderlee.com/swift/available-deprecated-renamed)
  **Published:** `2022-03-07T10:17:32+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Uses #available and related attributes to gate APIs, mark deprecations, and provide renamed replacements. Useful for maintaining multi-OS code while keeping compiler diagnostics actionable during API evolution.
- [@Published risks and usage explained with code examples - SwiftLee](https://www.avanderlee.com/swiftui/published-property-wrapper)
  **Published:** `2022-03-01T08:54:28+00:00`
  **Topics:** Concurrency · Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Explains that @Published emits from willSet, so subscribers can see the new value while the owning property still reads the old one. This timing matters when updating UI or combining publishers with imperative state.
- [@StateObject vs. @ObservedObject: The differences explained - SwiftLee](https://www.avanderlee.com/swiftui/stateobject-observedobject-differences)
  **Published:** `2022-02-22T09:07:26+00:00`
  **Topics:** Concurrency · Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Contrasts @StateObject's view-owned lifetime with @ObservedObject's externally owned reference. The distinction prevents model recreation during SwiftUI redraws and clarifies which view constructs observable state.
- [How to use the Redacted View Modifier in SwiftUI with useful extensions](https://www.avanderlee.com/swiftui/redacted-view-modifier)
  **Published:** `2022-02-15T09:26:55+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Shows SwiftUI redacted placeholders for loading states and extends them with custom reasons and conditional modifiers. The pattern keeps skeleton UI and previews aligned with production layout.
- [@EnvironmentObject explained for sharing data between views in SwiftUI](https://www.avanderlee.com/swiftui/environmentobject)
  **Published:** `2022-02-01T08:53:05+00:00`
  **Topics:** Architecture · Concurrency · Dependency Injection · Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Demonstrates injecting an ObservableObject through SwiftUI's environment and reading it in descendants without forwarding properties through every initializer. It also highlights the runtime failure when a required object is missing.
- [Self-documenting code in Swift to increase readability - SwiftLee](https://www.avanderlee.com/swift/self-documenting-code)
  **Published:** `2022-01-25T09:22:11+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Uses expressive names, focused types, and intent-revealing APIs to reduce explanatory comments. The examples frame readability as a design decision that lowers maintenance and review cost.
- [Tasks in Swift explained with code examples - SwiftLee](https://www.avanderlee.com/concurrency/tasks)
  **Published:** `2022-01-18T09:26:30+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Introduces Task as an unstructured concurrency entry point, covering priority, cancellation, handles, and inheritance. The examples show where tasks belong in UI code and why cancellation must be observed.
- [Guard statements in Swift explained with code examples - SwiftLee](https://www.avanderlee.com/swift/guard-statements)
  **Published:** `2022-01-11T10:06:05+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Explains guard as an early-exit construct for validating preconditions and unwrapping optionals while keeping the main path unindented. Failure must exit the enclosing function, loop, or closure.
- [Writing Swift Articles: Tips to become a better writer - SwiftLee](https://www.avanderlee.com/optimization/writing-swift-articles)
  **Published:** `2022-01-04T10:15:45+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Connects technical writing with clearer engineering thinking and community contribution, then suggests ways to develop an article. Use it as a communication workflow reference rather than a Swift tutorial.
- [Swift in 2021: A Year in Review - SwiftLee](https://www.avanderlee.com/general/swift-in-2021-a-year-in-review)
  **Published:** `2021-12-28T10:00:05+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Recaps the 2021 Swift ecosystem through releases such as async/await and Xcode Cloud. Its value is historical orientation; verify all language and tooling details against current Apple and Swift documentation.
- [Reflection in Swift: How Mirror works - SwiftLee](https://www.avanderlee.com/swift/reflection-how-mirror-works)
  **Published:** `2021-12-21T11:10:26+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Explains Mirror's runtime view of values, including children, labels, and display styles, and demonstrates reflective traversal. It clarifies what reflection can inspect and where compile-time safety no longer applies.
- [RunLoop.main vs DispatchQueue.main: The differences explained](https://www.avanderlee.com/combine/runloop-main-vs-dispatchqueue-main)
  **Published:** `2021-12-07T10:01:39+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Compares RunLoop.main scheduling with DispatchQueue.main, showing that both target the main thread but differ in queueing and run-loop behavior. The distinction helps diagnose delivery timing.
- [Creating an App Update Notifier using Combine and async/await - SwiftLee](https://www.avanderlee.com/swift/app-update-notifier)
  **Published:** `2021-11-30T08:50:19+00:00`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Builds an update notifier by combining App Store version checks with Combine and async/await, then exposes state to the UI. The workflow covers caching and deciding when prompts appear.
- [Non-fatal errors vs fatal crashes: The differences explained - SwiftLee](https://www.avanderlee.com/optimization/non-fatal-errors-vs-fatal-crashes)
  **Published:** `2021-11-23T08:53:13+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Distinguishes recoverable errors from process-terminating crashes and pairs crash-free sessions with non-fatal-error rates. Use it when telemetry should reveal degraded user journeys that never appear in a crash dashboard.
- [Composition vs. Inheritance: code architecture solutions explained in Swift](https://www.avanderlee.com/swift/composition-inheritance-code-architecture)
  **Published:** `2021-11-16T09:52:06+00:00`
  **Topics:** Architecture · Concurrency · Swift
  **NeKI brief:** Contrasts inheritance's coupled override hierarchy with composition through collaborating types and protocols. Examples show how composition improves substitution and testability while inheritance remains useful for specialization.
- [Increasing development effectiveness by recognizing repetition - SwiftLee](https://www.avanderlee.com/optimization/increasing-development-effectiveness)
  **Published:** `2021-10-26T07:33:13+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Uses repeated manual work as a signal for automation and process improvement. The article helps identify high-leverage developer workflows, but each proposed optimization should be validated against actual team cost.
- [Presentation tips for performing professional Swift talks - SwiftLee](https://www.avanderlee.com/optimization/presentation-tips-swift-talks)
  **Published:** `2021-10-12T07:30:39+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Distills lessons from delivering Swift talks into preparation, narrative, and presentation practices. It is useful for communicating technical decisions to teams, not for framework implementation.
- [Nonisolated and isolated keywords: Understanding Actor isolation](https://www.avanderlee.com/swift/nonisolated-isolated)
  **Published:** `2021-10-05T09:08:11+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Demonstrates nonisolated members for safe immutable access and protocol conformance, then uses isolated parameters to borrow an actor's isolation. The examples make await requirements concrete.
- [EXC_BAD_ACCESS crash error: Understanding and solving it - SwiftLee](https://www.avanderlee.com/swift/exc-bad-access-crash)
  **Published:** `2021-09-28T07:21:30+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Explains EXC_BAD_ACCESS as invalid memory access and routes diagnosis through Xcode sanitizers. Use it when crashes suggest lifetime, use-after-free, or unsafe-memory faults that require evidence beyond the visible stack trace.
- [Race condition vs. Data Race: the differences explained - SwiftLee](https://www.avanderlee.com/swift/race-condition-vs-data-race)
  **Published:** `2021-09-21T10:11:48+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Distinguishes logical race conditions from simultaneous unsynchronized memory access, showing why thread safety does not guarantee valid ordering. The terminology improves diagnosis and synchronization-tool choice.
- [Thread Sanitizer explained: Data Races in Swift - SwiftLee](https://www.avanderlee.com/swift/thread-sanitizer-data-races)
  **Published:** `2021-09-14T13:00:39+00:00`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Shows how Thread Sanitizer instruments Swift tests and apps to detect conflicting memory accesses, then interprets reports. It is a practical diagnostic for races that rarely reproduce.
- [PassthroughSubject vs. CurrentValueSubject explained](https://www.avanderlee.com/combine/passthroughsubject-currentvaluesubject-explained)
  **Published:** `2021-09-07T07:00:00+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Compares subjects that emit only future values with subjects retaining and replaying the latest value. Choosing between them changes initial-state delivery and Combine pipeline semantics.
- [@AppStorage explained and replicated for a better alternative - SwiftLee](https://www.avanderlee.com/swift/appstorage-explained)
  **Published:** `2021-08-24T08:23:08+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Explains @AppStorage's UserDefaults bridge and recreates its publisher behavior, exposing limitations around supported types, suites, and test isolation. The implementation makes persistence mechanics inspectable.
- [How to use throwing properties to catch failures in Swift - SwiftLee](https://www.avanderlee.com/swift/throwing-properties)
  **Published:** `2021-08-17T08:09:37+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Shows Swift throwing getters and subscripts for fallible read-only access. Use it when retrieving a derived value can genuinely fail and a property-like API remains clearer than a method with hidden mutation or work.
- [Unwrap or throw: Exploring solutions in Swift - SwiftLee](https://www.avanderlee.com/swift/unwrap-or-throw)
  **Published:** `2021-08-10T08:21:32+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Presents helper patterns converting optional absence into domain errors, including throwing unwrap functions. The trade-off is explicit failure propagation instead of silently carrying nil through later code.
- [Async let explained: call async functions in parallel - SwiftLee](https://www.avanderlee.com/swift/async-let-asynchronous-functions-in-parallel)
  **Published:** `2021-08-03T08:30:17+00:00`
  **Topics:** Concurrency · Performance · Swift
  **NeKI brief:** Uses async let child tasks to start independent work concurrently and awaits results at consumption. Structured cancellation and error propagation remain tied to the parent scope.
- [Development Assets in Xcode to enrich SwiftUI Previews](https://www.avanderlee.com/xcode/development-assets-preview-catalog)
  **Published:** `2021-07-27T07:54:09+00:00`
  **Topics:** Concurrency · Swift · SwiftUI · Xcode
  **NeKI brief:** Shows development asset catalogs providing preview-only resources and sample data without shipping them in production. This keeps SwiftUI previews rich while controlling bundle contents.
- [Dependency Injection in Swift using latest Swift features - SwiftLee](https://www.avanderlee.com/swift/dependency-injection)
  **Published:** `2021-07-20T09:49:01+00:00`
  **Topics:** Architecture · Concurrency · Dependency Injection · Swift · Testing
  **NeKI brief:** Builds dependency injection with protocols and initializer defaults, then substitutes test doubles. The design separates construction from behavior while preserving convenient production call sites.
- [Actors in Swift: how to use and prevent data races - SwiftLee](https://www.avanderlee.com/swift/actors)
  **Published:** `2021-06-29T08:34:45+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Introduces actors as isolated reference types serializing access to mutable state and requiring await across boundaries. Serialization prevents data races but does not promise a fixed thread.
- [Flaky tests resolving using Test Repetitions in Xcode - SwiftLee](https://www.avanderlee.com/debugging/flaky-tests-test-repetitions)
  **Published:** `2021-06-22T06:00:00+00:00`
  **Topics:** Concurrency · Swift · Testing · Xcode
  **NeKI brief:** Uses Xcode test repetitions to rerun a test automatically and expose intermittent failures, with controls for count and stop conditions. It turns flaky behavior into reproducible evidence.
- [Improve discoverability using Static Member Lookup in Generic Contexts](https://www.avanderlee.com/swift/static-member-lookup-generic-contexts)
  **Published:** `2021-06-15T08:41:36+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Explains SE-0299's generic static-member lookup through a SwiftUI ButtonStyle example. A constrained extension enables leading-dot syntax such as .swiftLee, improving autocomplete and reducing explicit type construction in generic modifier calls.
- [Presenting sheets with UIKit using a UISheetPresentationController](https://www.avanderlee.com/swift/presenting-sheets-uikit-uisheetpresentationcontroller)
  **Published:** `2021-06-08T10:11:41+00:00`
  **Topics:** Concurrency · Swift · UIKit
  **NeKI brief:** Configures UIKit sheets with UISheetPresentationController detents, grabbers, and interactive dismissal. The article provides the native presentation contract for medium and large bottom sheets.
- [WWDC 2021 Events, Parties, and Panels you don't want to miss - SwiftLee](https://www.avanderlee.com/wwdc/wwdc-2021-events-parties-panels)
  **Published:** `2021-06-01T09:01:41+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Catalogues remote WWDC 2021 community events, including watch parties, mentorship, labs, hackathons, and panels. Useful for reconstructing the online conference ecosystem and planning supplemental learning or networking around Apple's official sessions.
- [Swift Jobs: How to make the right career move - SwiftLee](https://www.avanderlee.com/swift/swift-jobs-career-move)
  **Published:** `2021-05-25T07:00:00+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Uses the author's career changes to frame evaluating Swift roles through growth, responsibilities, company context, and timing rather than compensation alone. Useful as a reflective checklist for comparing an opportunity with a developer's longer-term direction.
- [Fileprivate vs private in Swift: The differences explained - SwiftLee](https://www.avanderlee.com/swift/fileprivate-private-differences-explained)
  **Published:** `2021-05-18T07:37:52+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Clarifies Swift access-control boundaries: private limits the enclosing declaration and extensions, while fileprivate spans the source file. Choosing the narrower scope protects implementation details.
- [URLSession: Common pitfalls with background download & upload tasks](https://www.avanderlee.com/swift/urlsession-common-pitfalls-with-background-download-upload-tasks)
  **Published:** `2021-05-04T07:39:17+00:00`
  **Topics:** Concurrency · Networking · Swift · Testing · Xcode
  **NeKI brief:** Details background URLSession constraints, including delegate ownership, identifiers, relaunch handling, and file-based transfer requirements. Foreground request code cannot simply be reused for reliable background transfers.
- [NSPredicate based XCTestExpectations for conditional checks - SwiftLee](https://www.avanderlee.com/swift/nspredicate-xctestexpectations)
  **Published:** `2021-04-27T18:09:21+00:00`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Combines NSPredicate expectations with XCTest to wait until observable state satisfies a condition instead of sleeping. The approach reduces timing flakiness in asynchronous integration tests.
- [How to observe NSManagedObject changes in Core Data using Combine](https://www.avanderlee.com/combine/nsmanagedobject-observe-changes-core-data)
  **Published:** `2021-04-20T07:00:00+00:00`
  **Topics:** Concurrency · Core Data · Persistence & Synchronisation · Swift · SwiftUI
  **NeKI brief:** Bridges NSManagedObject changes into Combine publishers so individual property updates can refresh UI without redrawing an entire fetched-results list. Useful when NSFetchedResultsController or diffable snapshots miss fine-grained relationship or value changes.
- [How to create a Conditional View Modifier in SwiftUI - SwiftLee](https://www.avanderlee.com/swiftui/conditional-view-modifier)
  **Published:** `2021-04-13T08:27:07+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Creates a conditional SwiftUI modifier applying a transformation only when a Boolean is true, preserving fluent composition. The extension avoids duplicated branches while keeping modifier order explicit.
- [Getting started with the Combine framework in Swift - SwiftLee](https://www.avanderlee.com/swift/combine)
  **Published:** `2021-04-06T07:00:00+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Introduces Combine's publishers, subscribers, operators, subjects, and cancellables as a pipeline for values over time. Useful for building a mental model of how ObservableObject and @Published connect asynchronous events to SwiftUI state.
- [How to test optionals in Swift with XCTest - SwiftLee](https://www.avanderlee.com/swift/test-optionals-xctest)
  **Published:** `2021-03-30T09:58:17+00:00`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Compares XCTest's throwing XCTUnwrap with a custom optional assertion helper, focusing on readable failure messages and avoiding setup noise. Useful when deciding whether an optional is required test state or the behavior under test.
- [How to use the rethrows keyword in Swift - SwiftLee](https://www.avanderlee.com/swift/rethrows)
  **Published:** `2021-03-23T08:49:58+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Explains rethrows as a signature propagating errors only when a supplied closure can throw. Examples expose compiler rules and prevent unnecessarily broad throws declarations.
- [How to use @autoclosure in Swift to improve performance - SwiftLee](https://www.avanderlee.com/swift/autoclosure)
  **Published:** `2021-03-09T08:16:31+00:00`
  **Topics:** Concurrency · Performance · Swift
  **NeKI brief:** Demonstrates @autoclosure's deferred implicit closure conversion for assertions and lazy conditions. Delayed evaluation can obscure control flow, so it suits readable side-effect-free expressions.
- [How to create a Dynamic Pager View for onboardings - SwiftLee](https://www.avanderlee.com/swiftui/dynamic-pager-view-onboarding)
  **Published:** `2021-03-02T08:00:00+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI onboarding pager from enum-defined pages, supporting different page sets for new and returning users and older OS versions before PageTabViewStyle. Useful for dynamic feature announcements with explicit page identity.
- [How and when to use Lazy Collections in Swift - SwiftLee](https://www.avanderlee.com/swift/lazy-collections-arrays)
  **Published:** `2021-02-23T08:56:37+00:00`
  **Topics:** Concurrency · Performance · Swift
  **NeKI brief:** Explains lazy collection adapters deferring map, filter, and traversal work until elements are requested. The trade-off is lower intermediate allocation versus repeated computation on revisits.
- [How to use Variadic parameters in Swift - SwiftLee](https://www.avanderlee.com/swift/variadic-parameters)
  **Published:** `2021-02-16T08:48:34+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Uses variadic parameters to accept a variable number of values through one argument, then covers array conversion and overload limits. The examples help choose concise APIs without confusing variadics with collections.
- [XCTExpectFailure: Expected test failures explained with code examples](https://www.avanderlee.com/swift/xctexpectfailure-expected-failures)
  **Published:** `2021-02-02T08:56:40+00:00`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Introduces XCTExpectFailure for documenting known failing assertions while keeping the suite informative when a bug is fixed. Configuration controls unexpected passes and additional failures.
- [Lazy var in Swift explained with code examples - SwiftLee](https://www.avanderlee.com/swift/lazy-var-property)
  **Published:** `2021-01-25T16:36:46+00:00`
  **Topics:** Concurrency · Performance · Swift
  **NeKI brief:** Explains lazy stored properties as deferred, cached initialization and demonstrates closure-backed computation. Useful for postponing expensive setup until first use, while remembering that lazy state is mutable and not thread-safe by itself.
- [Closures in Swift explained with Code Examples - SwiftLee](https://www.avanderlee.com/swift/trailing-escaping-closures)
  **Published:** `2021-01-19T09:48:02+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Explains closure syntax, trailing closures, escaping storage, and capture behavior through examples. The distinctions matter when callback APIs retain work beyond a function call.
- [SwiftLee 2020 In Review: Most read blog posts - SwiftLee](https://www.avanderlee.com/swift/swiftlee-2020-in-review)
  **Published:** `2021-01-05T09:25:40+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Reviews SwiftLee's 2020 readership, publishing cadence, and business metrics, then identifies the year's most-read technical posts. Useful as historical context for Swift community interests and the author's evolution toward independent development.
- [Getting started with associated types in Swift Protocols - SwiftLee](https://www.avanderlee.com/swift/associated-types-protocols)
  **Published:** `2020-12-22T08:38:57+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Uses associated types to let a protocol describe relationships between inputs and outputs without fixing concrete types. Examples show why such protocols cannot always be used directly as existentials.
- [Result in Swift: Getting started with Code Examples - SwiftLee](https://www.avanderlee.com/swift/result-enum-type)
  **Published:** `2020-12-15T10:02:11+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Introduces Result as an explicit success-or-failure value for APIs, including mapping and extracting outcomes. Typed error transport can replace nested callbacks while preserving failure information.
- [Xcode Mark Line to improve readability using // Mark: comments](https://www.avanderlee.com/xcode/xcode-mark-line-comment)
  **Published:** `2020-12-08T10:21:56+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Shows how // MARK: comments create navigable sections in Xcode, but treats a growing number of marks as a signal to split an oversized type. Useful for balancing editor navigation convenience against single-responsibility design.
- [App Launch Time: 7 tips to increase performance - SwiftLee](https://www.avanderlee.com/optimization/launch-time-performance-optimization)
  **Published:** `2020-12-01T08:00:00+00:00`
  **Topics:** Concurrency · Dependency Injection · Performance · Swift · Testing · Xcode
  **NeKI brief:** Breaks launch latency into loading, initialization, and first-frame work, then prioritizes reductions with profiling. The tips focus on moving or deferring nonessential startup tasks.
- [Data validation on insertion, update, and deletion in Core Data - SwiftLee](https://www.avanderlee.com/core-data/data-validation)
  **Published:** `2020-11-10T07:58:43+00:00`
  **Topics:** Concurrency · Core Data · Persistence & Synchronisation · Swift
  **NeKI brief:** Covers Core Data validation hooks for insertion, updates, and deletion, showing how managed objects reject invalid state before persistence. Checks remain tied to object-level save errors.
- [Derived Attributes to improve Core Data Fetch Performance - SwiftLee](https://www.avanderlee.com/core-data/derived-attributes-optimise-fetch-performance)
  **Published:** `2020-11-03T09:25:35+00:00`
  **Topics:** Concurrency · Core Data · Performance · Persistence & Synchronisation · Swift
  **NeKI brief:** Uses Core Data derived attributes to precompute values needed for sorting or filtering, reducing fetch-time work. The trade-off is maintaining derived data when source properties change.
- [Constraints in Core Data Entities explained - SwiftLee](https://www.avanderlee.com/swift/constraints-core-data-entities)
  **Published:** `2020-10-27T07:00:00+00:00`
  **Topics:** Concurrency · Core Data · Persistence & Synchronisation · Swift · SwiftUI
  **NeKI brief:** Explains Core Data entity constraints enforcing uniqueness and resolving conflicts during saves. Model configuration must be paired with an appropriate merge policy for duplicates.
- [NSManagedObject events: handling state in Core Data - SwiftLee](https://www.avanderlee.com/swift/nsmanagedobject-awakefrominsert-preparefordeletion)
  **Published:** `2020-10-20T06:35:23+00:00`
  **Topics:** Concurrency · Core Data · Persistence & Synchronisation · Swift
  **NeKI brief:** Traces NSManagedObject callbacks such as awakeFromInsert and prepareForDeletion for defaults and relationship cleanup. Knowing callback timing prevents lifecycle side effects in ordinary observers.
- [Try Catch Throw: Error Handling in Swift with Code Examples](https://www.avanderlee.com/swift/try-catch-throw-error-handling)
  **Published:** `2020-10-05T07:00:00+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Walks through Swift throw, do-catch, try?, and try! forms, then shows error propagation across function boundaries. The comparison makes failure handling choices explicit.
- [Overriding UserDefaults for improved productivity - SwiftLee](https://www.avanderlee.com/xcode/overriding-userdefaults-launch-arguments)
  **Published:** `2020-09-29T07:00:00+00:00`
  **Topics:** Concurrency · Persistence & Synchronisation · Swift · Xcode
  **NeKI brief:** Uses Xcode scheme launch arguments to override UserDefaults at process startup, enabling repeatable flags and test configuration. Overrides stay isolated to the run.
- [How-to use Diffable Data Sources with Core Data - SwiftLee](https://www.avanderlee.com/swift/diffable-data-sources-core-data)
  **Published:** `2020-09-22T07:45:52+00:00`
  **Topics:** Concurrency · Core Data · Performance · Persistence & Synchronisation · Swift
  **NeKI brief:** Integrates Core Data changes with UICollectionViewDiffableDataSource using stable identifiers and snapshots. The approach replaces index-path bookkeeping but requires careful update and deletion handling.
- [Diffable Data Sources Adoption with Ease - SwiftLee](https://www.avanderlee.com/swift/diffable-data-sources-adoption)
  **Published:** `2020-09-15T07:00:00+00:00`
  **Topics:** Concurrency · Swift · UIKit
  **NeKI brief:** Explains incremental adoption of diffable data sources: model Hashable identifiers, build snapshots, and apply changes declaratively. This reduces synchronization bugs in collection and table views.
- [Persistent History Tracking in Core Data - SwiftLee](https://www.avanderlee.com/swift/persistent-history-tracking-core-data)
  **Published:** `2020-09-08T07:00:00+00:00`
  **Topics:** Concurrency · Core Data · Persistence & Synchronisation · Swift
  **NeKI brief:** Shows persistent history tracking for querying transactions made by other contexts or processes, then marking history consumed. It supports extension synchronization without observing every live context.
- [withAnimation completion callback with animatable modifiers - SwiftLee](https://www.avanderlee.com/swiftui/withanimation-completion-callback)
  **Published:** `2020-09-01T07:00:00+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Adds a completion callback to SwiftUI animations by observing animatable progress, including interruption concerns. The technique lets code react after visual state reaches its target.
- [Write-Ahead Logging (WAL) disabled to force commits in Core Data](https://www.avanderlee.com/swift/write-ahead-logging-wal)
  **Published:** `2020-08-25T13:51:17+00:00`
  **Topics:** Concurrency · Core Data · Performance · Persistence & Synchronisation · Swift
  **NeKI brief:** Explains SQLite write-ahead logging in Core Data and why disabling WAL can force commits into the main store. The trade-off matters for durability and cross-process visibility.
- [How to combine text weights in SwiftUI - SwiftLee](https://www.avanderlee.com/swiftui/text-weight-combinations)
  **Published:** `2020-08-18T07:00:00+00:00`
  **Topics:** Concurrency · Swift · SwiftUI
  **NeKI brief:** Combines SwiftUI Text values with the plus operator to mix font weights while preserving natural wrapping, contrasting this with HStack and UIViewRepresentable approaches. Useful for styled inline copy without abandoning SwiftUI layout behavior.
- [Adding a closure as a target to UIButton and other controls in Swift](https://www.avanderlee.com/swift/uibutton-uicontrol-closure-target)
  **Published:** `2020-08-05T17:15:14+00:00`
  **Topics:** Concurrency · Dependency Injection · Swift
  **NeKI brief:** Builds a closure-based UIControl target helper that stores callbacks and forwards events without selectors. The implementation must retain the target for the control's lifetime.
- [Launch screens in Xcode: All the options explained - SwiftLee](https://www.avanderlee.com/xcode/launch-screen)
  **Published:** `2020-07-28T07:00:00+00:00`
  **Topics:** Concurrency · Swift · SwiftUI · Xcode
  **NeKI brief:** Traces launch-screen options from static images to storyboards and Xcode 12's launch-screen configuration, including caching and URL-scheme considerations. Useful for auditing legacy launch assets and avoiding dynamic-content assumptions during startup.
- [ValueTransformer in Core Data explained: Storing absolute URLs](https://www.avanderlee.com/swift/valuetransformer-core-data)
  **Published:** `2020-07-14T07:00:00+00:00`
  **Topics:** Concurrency · Core Data · Persistence & Synchronisation · Swift
  **NeKI brief:** Implements a Core Data ValueTransformer to persist URL values while exposing a typed Swift property, including registration and conversion failures. It bridges unsupported model types safely.
- [Full-screen development with Xcode and the Simulator - SwiftLee](https://www.avanderlee.com/workflow/full-screen-xcode-simulator)
  **Published:** `2020-07-07T07:00:00+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Configures a focused full-screen workspace with Xcode and the Simulator side by side using macOS Mission Control. Useful as a low-friction workflow adjustment for reducing visual distractions during iterative UI development.
- [SVG Assets in Xcode for Single Scale Images - SwiftLee](https://www.avanderlee.com/xcode/svg-image-assets)
  **Published:** `2020-06-30T07:00:00+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Explains Xcode 12's SVG image assets as single-scale vector resources for Apple platforms, contrasting them with PDF assets and generated @1x/@2x/@3x files. Useful for simplifying scalable icon pipelines while checking asset-rendering constraints.
- [WWDC 2020: 7 Tips to prepare yourself - SwiftLee](https://www.avanderlee.com/optimization/wwdc-2020-tips)
  **Published:** `2020-06-16T07:00:00+00:00`
  **Topics:** Concurrency · Swift · Testing · Xcode
  **NeKI brief:** Suggests preparing for the fully online WWDC 2020 by reserving time, planning keynote and State of the Union viewing, and organizing sessions and community activities. Useful as historical event-planning context for remote conferences.
- [@discardableResult in Swift explained: Ignoring return values - SwiftLee](https://www.avanderlee.com/swift/discardableresult)
  **Published:** `2020-06-09T07:00:00+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Explains @discardableResult as an API annotation permitting callers to ignore a return value without warnings. The decision should reflect optional results, not hide misuse.
- [Core Data Performance: 6 tips you should know - SwiftLee](https://www.avanderlee.com/swift/core-data-performance)
  **Published:** `2020-06-02T07:00:00+00:00`
  **Topics:** Concurrency · Core Data · Performance · Persistence & Synchronisation · Swift
  **NeKI brief:** Connects Core Data performance to fetch limits, batching, faulting, predicates, and background contexts. Each technique targets store work or memory pressure and suggests profiling leads.
- [Introducing GitBuddy: Changelog and Release manager for GitHub](https://www.avanderlee.com/workflow/gitbuddy-changelog-generator)
  **Published:** `2020-05-26T07:40:33+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Introduces GitBuddy as a release workflow that reads repository changes, groups pull requests, and generates changelogs and release notes across projects. Useful for reducing forgotten tags and manual release bookkeeping in open-source maintenance.
- [Expressible literals in Swift explained by 3 useful examples - SwiftLee](https://www.avanderlee.com/swift/expressible-literals)
  **Published:** `2020-05-19T07:13:24+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Demonstrates ExpressibleBy*Literal conformances allowing custom types to initialize from literals. Examples show concise syntax while exposing conversion and type-inference constraints.
- [String Interpolation in Swift explained using 4 useful cases - SwiftLee](https://www.avanderlee.com/swift/string-interpolation)
  **Published:** `2020-05-12T06:31:41+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Uses custom String interpolation segments to embed formatted values and domain-specific rendering directly in strings. The approach centralizes presentation rules while preserving compile-time syntax.
- [Using Custom debug descriptions to improve debugging - SwiftLee](https://www.avanderlee.com/swift/custom-debug-descriptions)
  **Published:** `2020-05-05T07:43:44+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Implements CustomDebugStringConvertible to provide structured diagnostic output distinct from user-facing descriptions. Better debug representations make logs and LLDB inspection useful.
- [URLs in Swift: Common scenarios explained in-depth - SwiftLee](https://www.avanderlee.com/swift/url-components)
  **Published:** `2020-04-21T07:00:00+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Builds URLs with URLComponents and URLQueryItem instead of manual concatenation, covering encoding and query mutation. The method avoids malformed escaping and keeps requests inspectable.
- [SwiftUI Previews: Validating views in different states - SwiftLee](https://www.avanderlee.com/swiftui/previews-different-states)
  **Published:** `2020-04-14T07:00:00+00:00`
  **Topics:** Accessibility · Concurrency · Swift · SwiftUI · Xcode
  **NeKI brief:** Uses SwiftUI previews to render loading, empty, populated, and error states with representative dependencies. State-focused previews reveal layout regressions before running the application.
- [Custom Operators in Swift with practical code examples - SwiftLee](https://www.avanderlee.com/swift/custom-operators-swift)
  **Published:** `2020-04-07T07:48:23+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Explains declaring custom prefix, postfix, and infix operators with precedence and associativity, then weighs readability against cleverness. Operators should express domain relations consistently.
- [Custom subscripts in Swift explained with code examples - SwiftLee](https://www.avanderlee.com/swift/custom-subscripts)
  **Published:** `2020-03-31T09:22:14+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Shows custom subscripts exposing indexed or keyed access over domain types, including get/set behavior. The API can simplify models but should preserve predictable bounds and mutation.
- [NSFetchedResultsController extension to observe relationship changes](https://www.avanderlee.com/swift/nsfetchedresultscontroller-observe-relationship-changes)
  **Published:** `2020-03-24T08:00:00+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Extends NSFetchedResultsController to react when related Core Data objects change, a gap in its normal object and section callbacks. Useful when list cells depend on relationship values that otherwise leave fetched results visually stale.
- [Testing private methods and variables in Swift - SwiftLee](https://www.avanderlee.com/swift/testing-private-methods-variables)
  **Published:** `2020-03-17T08:00:00+00:00`
  **Topics:** Architecture · Concurrency · Dependency Injection · Swift · Testing
  **NeKI brief:** Argues for testing private behavior through public outcomes, while presenting limited access techniques when a seam is unavoidable. This avoids freezing implementation details in tests.
- [How to mock Alamofire and URLSession requests in Swift](https://www.avanderlee.com/swift/mocking-alamofire-urlsession-requests)
  **Published:** `2020-03-10T08:00:00+00:00`
  **Topics:** Concurrency · Networking · Swift
  **NeKI brief:** Introduces protocol abstraction and URLProtocol interception for mocking Alamofire or URLSession responses. Tests exercise decoding and error paths deterministically without real network calls.
- [Creating a command line tool using the Swift Package Manager - SwiftLee](https://www.avanderlee.com/swift/command-line-tool-package-manager)
  **Published:** `2020-03-03T08:00:00+00:00`
  **Topics:** Concurrency · Swift · Swift Package Manager
  **NeKI brief:** Creates a Swift Package Manager executable target, defines its manifest, and runs it from the command line. The workflow is a compact template for Swift developer utilities.
- [Authentication with signed requests in Alamofire 5 - SwiftLee](https://www.avanderlee.com/swift/authentication-alamofire-request-adapter)
  **Published:** `2020-02-25T08:00:00+00:00`
  **Topics:** Concurrency · Networking · Swift
  **NeKI brief:** Uses Alamofire's RequestAdapter to attach signed authentication data consistently, centralizing credential preparation and retry behavior. Endpoint code stays focused on payloads.
- [SwiftLee 2019 in review: Top Swift Development blog posts - SwiftLee](https://www.avanderlee.com/swift/swiftlee-2019-in-review-top-swift-development-blog-posts)
  **Published:** `2019-12-31T08:00:00+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Summarizes SwiftLee's 2019 audience growth, weekly publishing milestone, and most-read Swift articles. Useful as a dated map of community interests and a historical route into older implementation discussions.
- [No space left on device: Testing low storage scenarios - SwiftLee](https://www.avanderlee.com/debugging/no-space-left-on-device)
  **Published:** `2019-12-24T08:00:00+00:00`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Tests low-storage behavior by filling simulator or device capacity and observing app failures, cleanup, and recovery. The scenario exposes writable-space assumptions ordinary tests miss.
- [4 Tips to make it easier to fix crashes and bugs - SwiftLee](https://www.avanderlee.com/workflow/fixing-crashes-bugs)
  **Published:** `2019-12-17T08:00:00+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Recommends combining crash reports, reproducible context, diagnostics, and regression tests when fixing production issues. Useful as an evidence-first debugging workflow that turns vague reports into actionable code paths and prevents recurrence.
- [Advanced asynchronous operations by making use of generics - SwiftLee](https://www.avanderlee.com/swift/advanced-asynchronous-operations)
  **Published:** `2019-12-10T08:00:00+00:00`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Builds reusable asynchronous operations with explicit state, cancellation, and completion handling instead of nesting callbacks. The patterns are useful when coordinating legacy Operation-based work with newer async/await entry points.
- [Asynchronous operations for writing concurrent solutions in Swift - SwiftLee](https://www.avanderlee.com/swift/asynchronous-operations)
  **Published:** `2019-12-03T09:14:06+00:00`
  **Topics:** Concurrency · Dependency Injection · Swift
  **NeKI brief:** Builds an asynchronous Operation by managing executing and finished KVO states around callback completion. Correct transitions let OperationQueue schedule dependencies and recognize completion.
- [Getting started with Operations and OperationQueues in Swift - SwiftLee](https://www.avanderlee.com/swift/operations)
  **Published:** `2019-11-26T13:00:46+00:00`
  **Topics:** Concurrency · Dependency Injection · Swift
  **NeKI brief:** Introduces Operation and OperationQueue for cancellable, dependency-aware units of work, contrasting them with raw GCD blocks. Examples show lifecycle hooks for composable tasks.
- [Concurrent vs Serial DispatchQueue: Concurrency in Swift explained](https://www.avanderlee.com/swift/concurrent-serial-dispatchqueue)
  **Published:** `2019-11-12T08:00:04+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Compares serial and concurrent DispatchQueues, including barrier synchronization and targeting. The behavior explains ordering guarantees versus parallel throughput and why queues alone do not make state safe.
- [Dark Mode: Adding support to your app in Swift - SwiftLee](https://www.avanderlee.com/swift/dark-mode-support-ios)
  **Published:** `2019-11-05T08:30:36+00:00`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Adds dark-mode support by auditing colors and images, using semantic system colors, and responding to trait changes. The workflow prevents hard-coded contrast failures.
- [Core Data and App extensions: Sharing a single database - SwiftLee](https://www.avanderlee.com/swift/core-data-app-extension-data-sharing)
  **Published:** `2019-10-29T08:00:39+00:00`
  **Topics:** Concurrency · Core Data · Persistence & Synchronisation · Swift
  **NeKI brief:** Shares a Core Data store between an app and extensions through an app group, coordinating container setup and saves. Cross-process use requires concurrency and migration care.
- [Auto Layout in Swift: Writing constraints programmatically - SwiftLee](https://www.avanderlee.com/swift/auto-layout-programmatically)
  **Published:** `2019-10-22T07:00:07+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Constructs Auto Layout constraints in code using anchors and activation, then explains ambiguity errors. Programmatic constraints stay reviewable when grouped around view relationships.
- [Mastering the assistant editor in Xcode 11 - SwiftLee](https://www.avanderlee.com/xcode/xcode-assistant-editor)
  **Published:** `2019-10-01T07:00:32+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Explains Xcode 11's Assistant Editor as a second context-aware source pane and shows how editor placement and navigation changed. Useful for restoring a predictable two-editor workflow after migrating from earlier Xcode behavior.
- [5 Xcode breakpoints tips you might not yet know - SwiftLee](https://www.avanderlee.com/debugging/xcode-breakpoints-tips)
  **Published:** `2019-09-24T19:12:44+00:00`
  **Topics:** Concurrency · Swift · Testing · Xcode
  **NeKI brief:** Shows conditional, symbolic, exception, and action breakpoints plus logging and auto-continue behavior. These options capture state without repeatedly editing source.
- [Rich notifications on iOS explained in Swift - SwiftLee](https://www.avanderlee.com/swift/rich-notifications)
  **Published:** `2019-09-17T07:00:56+00:00`
  **Topics:** Concurrency · Swift · Testing
  **NeKI brief:** Builds rich notifications with attachments, custom actions, categories, and a notification service extension. The extension can transform content before delivery within time and resource limits.
- [Struct vs classes in Swift: The differences explained - SwiftLee](https://www.avanderlee.com/swift/struct-class-differences)
  **Published:** `2019-08-27T07:00:16+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Compares value semantics, reference identity, inheritance, and copy-on-write behavior between structs and classes. The guidance connects ownership and mutation requirements to API design.
- [Xcode Instruments usage to improve app performance](https://www.avanderlee.com/debugging/xcode-instruments-time-profiler)
  **Published:** `2019-08-20T07:00:46+00:00`
  **Topics:** Concurrency · Performance · Swift · Xcode
  **NeKI brief:** Uses Instruments Time Profiler to record call stacks, identify hot methods, and verify optimizations against measured samples. The workflow favors profiling representative workloads over guessing.
- [Error handling in Combine explained with code examples - SwiftLee](https://www.avanderlee.com/swift/combine-error-handling)
  **Published:** `2019-08-13T07:00:42+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Explains Combine's Failure type, mapError, catch, retry, and replaceError operators. Each choice determines whether a stream terminates, retries work, or recovers with fallback data.
- [Array vs Set: Fundamentals in Swift explained - SwiftLee](https://www.avanderlee.com/swift/array-vs-set-differences-explained)
  **Published:** `2019-08-06T07:00:41+00:00`
  **Topics:** Concurrency · Core Data · Performance · Persistence & Synchronisation · Swift
  **NeKI brief:** Contrasts Array's ordered duplicate-preserving storage with Set's uniqueness and hash-based membership, including performance implications. Selection should follow access and identity requirements.
- [Xcode refactoring options explained with examples - SwiftLee](https://www.avanderlee.com/swift/xcode-refactoring)
  **Published:** `2019-07-30T08:00:12+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Surveys Xcode refactoring commands for renaming symbols, extracting methods, and restructuring Swift code while preserving references. Tool-assisted edits reduce mechanical mistakes.
- [Unused images and resources clean up in Xcode - SwiftLee](https://www.avanderlee.com/optimization/unused-images-clean-up)
  **Published:** `2019-07-23T07:00:01+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Identifies unused image assets through build outputs and asset-catalog inspection, then removes candidates safely. Cleanup reduces bundle size while requiring checks for runtime-generated names.
- [UIKeyCommand how-to add keyboard shortcuts & speed up your workflow](https://www.avanderlee.com/swift/uikeycommand-keyboard-shortcuts)
  **Published:** `2019-07-16T08:46:22+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Adds UIKeyCommand entries by overriding UIResponder.keyCommands, then routes shortcuts through responders such as tab bars and collection views. Useful for testing hardware-keyboard workflows in the Simulator and designing discoverable iPad commands.
- [Combine debugging using operators in Swift - SwiftLee](https://www.avanderlee.com/debugging/combine-swift)
  **Published:** `2019-07-09T07:00:42+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Debugs Combine pipelines with handleEvents, print-style tracing, breakpointOnError, and conditional breakpoints. The operator-based workflow exposes subscription and completion timing without deciphering a long asynchronous stack trace.
- [Creating a custom Combine Publisher to extend UIKit - SwiftLee](https://www.avanderlee.com/swift/custom-combine-publisher)
  **Published:** `2019-07-02T07:00:25+00:00`
  **Topics:** Concurrency · Swift · UIKit
  **NeKI brief:** Builds a custom Combine Subscription and Publisher to turn UIControl events into a cancellable stream. Useful when UIKit lacks a native publisher, while making demand and cancellation responsibilities explicit.
- [Using Xcode Previews with existing UIKit views without using SwiftUI - SwiftLee](https://www.avanderlee.com/xcode/xcode-previews)
  **Published:** `2019-06-18T07:00:26+00:00`
  **Topics:** Concurrency · Swift · SwiftUI · UIKit · Xcode
  **NeKI brief:** Uses Xcode 11 previews for existing UIView and UIViewController types through lightweight PreviewProvider wrappers, so UIKit screens can iterate in the canvas without a SwiftUI rewrite. Useful for incremental UI modernization.
- [Dynamic Member Lookup combined with key paths in Swift](https://www.avanderlee.com/swift/dynamic-member-lookup)
  **Published:** `2019-06-11T18:48:03+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Combines @dynamicMemberLookup with key paths to forward member access through a wrapper while retaining typed paths. Useful for proxy or JSON-style APIs, but the indirection trade-off should be weighed against ordinary properties.
- [Using NSBatchDeleteRequest to delete batches in Core Data - SwiftLee](https://www.avanderlee.com/swift/nsbatchdeleterequest-core-data)
  **Published:** `2019-05-21T07:00:06+00:00`
  **Topics:** Concurrency · Core Data · Persistence & Synchronisation · Swift
  **NeKI brief:** Uses NSBatchDeleteRequest to remove records directly at the persistent-store SQL layer, then addresses context-merging pitfalls. Useful for large purges where per-object deletion is slow, provided in-memory contexts are refreshed correctly.
- [Weak self and unowned self explained in Swift - SwiftLee](https://www.avanderlee.com/swift/weak-self)
  **Published:** `2019-05-14T07:00:33+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Contrasts weak and unowned captures under ARC, tying each choice to whether the referenced object may disappear. The examples also explain why value types do not need these capture modifiers and where retain cycles arise.
- [Typealias usage in Swift - SwiftLee](https://www.avanderlee.com/swift/typealias-usage-swift)
  **Published:** `2019-04-30T07:00:45+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Shows typealias for readable domain names and generic aliases, while clarifying that an alias does not create a new type. Useful for API readability without expecting additional compile-time type separation.
- [Developer productivity boost with Google Search Tips & Tricks - SwiftLee](https://www.avanderlee.com/optimization/developer-productivity-boost-with-google-search-tips-tricks)
  **Published:** `2019-04-16T07:00:03+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Presents focused Google queries—wildcards, domain filters, and ‘solved’ qualifiers—to narrow programming research quickly. Useful as a practical debugging and documentation-search workflow rather than a code technique.
- [@unknown default usage with enums in Swift - SwiftLee](https://www.avanderlee.com/swift/unknown-default-enums-in-swift)
  **Published:** `2019-04-09T11:29:34+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Explains @unknown default as a future-proof switch branch that still warns when a known enum case is added. Useful for SDK-facing enums where exhaustive handling must evolve without silently swallowing new cases.
- [Swift 5.0: How to migrate your project and frameworks - SwiftLee](https://www.avanderlee.com/swift/updating-swift-5)
  **Published:** `2019-04-02T07:00:10+00:00`
  **Topics:** Concurrency · Dependency Injection · Swift
  **NeKI brief:** Outlines a Swift 5 migration pass covering the migration assistant, dependencies, CI images, Result adoption, and ABI-stability implications. Useful for planning project-wide upgrade work beyond merely changing the compiler version.
- [WWDC First timer tips: How to get the most out of it - SwiftLee](https://www.avanderlee.com/wwdc/wwdc-first-timer-tips-after-visiting)
  **Published:** `2019-03-25T18:06:15+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Offers a first-time WWDC workflow covering session planning, labs, meetups, and conference logistics. Useful for turning a large event into actionable learning and networking time rather than relying on the keynote alone.
- [Blog about Swift: Tips and ideas to start your own - SwiftLee](https://www.avanderlee.com/swift/blog-about-swift)
  **Published:** `2019-03-19T07:30:15+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Reflects on starting and sustaining a Swift blog, from choosing a narrow audience to publishing consistently and measuring reach. Useful for developers evaluating technical writing as a knowledge-sharing or career practice.
- [Unused localized strings clean up from a Strings file - SwiftLee](https://www.avanderlee.com/xcode/unused-localized-strings)
  **Published:** `2019-03-12T10:59:21+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Describes scanning localization files for keys no longer referenced by source and removing confirmed leftovers. Useful for keeping growing Strings resources maintainable, while recognizing that dynamic lookup needs manual review.
- [Required keyword usage in Swift classes and structs - SwiftLee](https://www.avanderlee.com/swift/required-keyword)
  **Published:** `2019-02-19T08:00:38+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Clarifies that required marks an initializer every subclass must implement; it does not make that initializer the only construction path. Useful when designing class hierarchies and avoiding incorrect assumptions about initializer inheritance.
- [Speeding up development: a collection of tips - SwiftLee](https://www.avanderlee.com/optimization/speeding-up-development-a-collection-of-tips)
  **Published:** `2019-02-12T08:00:02+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Groups productivity practices around focus, automation, learning, and mastery of development tools. Useful as a workflow checklist for reducing context switching and repetitive work, not as a framework-specific optimization guide.
- [Danger plugins to speed up code reviews - SwiftLee](https://www.avanderlee.com/optimization/danger-plugins)
  **Published:** `2019-02-05T08:00:25+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Introduces Danger as a pull-request automation layer and shows plugins that flag reviewable issues such as missing documentation or unsafe captures. Useful for moving repeatable review comments into CI while keeping human design review intact.
- [Alamofire vs URLSession: a comparison for networking in Swift - SwiftLee](https://www.avanderlee.com/swift/alamofire-vs-urlsession)
  **Published:** `2019-01-29T14:22:55+00:00`
  **Topics:** Concurrency · Networking · Swift
  **NeKI brief:** Compares Foundation URLSession with Alamofire across API ergonomics, dependency cost, and built-in request features. Useful for making a networking choice based on project needs instead of assuming an external abstraction is automatically better.
- [How to use for loop, for each, while, and repeat in Swift (in-depth)](https://www.avanderlee.com/swift/loops-swift)
  **Published:** `2019-01-22T07:25:22+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Contrasts for-in, forEach, while, repeat-while, and where clauses, including their control-flow differences. Useful for selecting iteration syntax deliberately when early exit, guaranteed execution, or readability matters.
- [QR Code generation with a custom logo and color using Swift - SwiftLee](https://www.avanderlee.com/swift/qr-code-generation-swift)
  **Published:** `2019-01-02T14:18:03+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Generates QR images with Core Image, adjusts foreground color, and composites a custom logo while preserving scannability. Useful for implementing branded codes and validating output in a small playground before integrating it into an app.
- [Cheat sheet examples for Xcode and Swift development - SwiftLee](https://www.avanderlee.com/workflow/cheat-sheet-xcode-swift)
  **Published:** `2018-12-26T14:24:57+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Collects compact references for assert/precondition/fatalError, Xcode shortcuts, and Git commands. Useful as a desk-side lookup for daily development decisions, especially distinguishing recoverable checks from deliberate process termination.
- [SwiftLee 2018 in review: Top Swift Development blog posts](https://www.avanderlee.com/swift/swiftlee-2018-in-review-top-swift-development-blog-posts)
  **Published:** `2018-12-18T07:16:51+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Reviews SwiftLee’s 2018 readership and highlights the year’s most-read Swift development articles. Useful as a curated route into older topics, with the caveat that APIs and recommendations may reflect that release era.
- [Implementing Siri support using NSUserActivity, intents and shortcuts - SwiftLee](https://www.avanderlee.com/swift/siri-support-nsuseractivity)
  **Published:** `2018-12-04T07:59:50+00:00`
  **Topics:** App Intents & System Surfaces · Concurrency · Swift
  **NeKI brief:** Implements Siri entry points with NSUserActivity, shortcut donation, and handling an incoming activity, avoiding the heavier Intents extension for a simple deep-link flow. Useful for exposing app navigation and actions to Siri predictions.
- [Speeding up with Xcode Behaviors - SwiftLee](https://www.avanderlee.com/xcode/xcode-behaviours-optimized)
  **Published:** `2018-11-27T14:10:31+00:00`
  **Topics:** Concurrency · Swift · Testing · Xcode
  **NeKI brief:** Configures Xcode Behaviors to open issue or test navigators on failures and start debugging in a focused tab. Useful for shortening the feedback loop after builds, tests, or breakpoints without adding project code.
- [Shortcuts essentials in Xcode to speed up your workflow - SwiftLee](https://www.avanderlee.com/workflow/essential-shortcuts-xcode-workflow)
  **Published:** `2018-10-16T11:04:28+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Demonstrates Xcode shortcuts for running without rebuilding, jumping to definitions, opening document items, and using the assistant editor. Useful for reducing mouse-driven navigation and preserving coding flow during everyday maintenance.
- [Measure the performance of code in Swift - SwiftLee](https://www.avanderlee.com/optimization/measure-performance-code)
  **Published:** `2018-10-09T06:44:53+00:00`
  **Topics:** Concurrency · Performance · Swift · Testing
  **NeKI brief:** Measures Swift code with repeatable test input, runs the benchmark from the terminal, and compares observed timings before optimizing. Useful for replacing intuition with a small reproducible performance experiment.
- [Performance, functional programming and collections in Swift - SwiftLee](https://www.avanderlee.com/swift/performance-collections)
  **Published:** `2018-10-02T12:38:26+00:00`
  **Topics:** Concurrency · Performance · Swift
  **NeKI brief:** Shows collection-level choices such as contains over first(where:), isEmpty over count checks, and specialized min/max or allSatisfy operations. Useful for clearer intent and avoiding unnecessary traversal in hot paths.
- [SwiftLint valuable opt-in rules to improve your code - SwiftLee](https://www.avanderlee.com/optimization/swiftlint-optin-rules)
  **Published:** `2018-09-25T11:00:03+00:00`
  **Topics:** Concurrency · Performance · Swift
  **NeKI brief:** Reviews SwiftLint opt-in rules including empty_count, first_where, modifier_order, prohibited_interface_builder, and unused_private_declaration. Useful for selectively enforcing conventions that catch maintainability issues without enabling every rule globally.
- [Updating to Swift 4.2 with Xcode 10 using related sources - SwiftLee](https://www.avanderlee.com/swift/updating-swift-4-2)
  **Published:** `2018-09-17T20:32:29+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Summarizes Swift 4.2 migration conveniences such as self in closures, #warning replacing TODO markers, enum case iteration, and random-value APIs. Useful when modernizing older code alongside Xcode 10’s migration guidance.
- [Command-click on code options and possibilities in Xcode - SwiftLee](https://www.avanderlee.com/xcode/command-click-code-xcode)
  **Published:** `2018-09-10T20:13:04+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Explains Xcode’s Command-click menu for callers, rename-in-scope, extraction, and navigation, plus how to restore definition-jump behavior. Useful for discovering refactoring actions without leaving the editor.
- [CompactMap vs flatMap: The differences explained - SwiftLee](https://www.avanderlee.com/swift/compactmap-flatmap-differences-explained)
  **Published:** `2018-08-28T07:03:08+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Distinguishes compactMap’s nil-filtering transformation from flatMap’s flattening of nested sequences, with examples of when each expresses intent. Useful for avoiding accidental data loss or the wrong collection shape in pipelines.
- [Effective development by improving the daily routine as a developer](https://www.avanderlee.com/workflow/effective-development)
  **Published:** `2018-08-21T11:28:40+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Connects developer productivity to a repeatable daily routine: clear goals, fewer notifications, scheduled meetings, and protected focus. Useful as a lightweight process experiment for reducing interruptions and increasing consistency.
- [Compiler Diagnostic Directives using a hashtag in Swift - SwiftLee](https://www.avanderlee.com/swift/compiler-diagnostic-directives)
  **Published:** `2018-08-14T06:49:15+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Catalogues Swift compiler diagnostic directives such as #warning, #error, and availability-related checks, with examples of using them to enforce migration or configuration requirements. It is a practical reference for making build failures intentional.
- [Where usage in Swift - SwiftLee](https://www.avanderlee.com/swift/where-using-swift)
  **Published:** `2018-08-07T07:15:42+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Catalogues where clauses in switches, loops, protocol extensions, initializers, and collection predicates. Useful for expressing filtering conditions close to the control-flow construct instead of adding nested if statements.
- [Debugging breakpoints as a replacement for prints - SwiftLee](https://www.avanderlee.com/debugging/debugging-breakpoints)
  **Published:** `2018-07-31T12:00:53+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Uses reusable Xcode breakpoints, conditions, and actions as a cleaner alternative to temporary print statements. Useful for inspecting state repeatedly while keeping diagnostic code out of production sources.
- [Typed notifications using custom extensions - SwiftLee](https://www.avanderlee.com/swift/typed-notifications-using-extensions)
  **Published:** `2018-07-24T06:58:46+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Wraps NotificationCenter notifications in typed representers so names and userInfo payloads become discoverable Swift APIs. Useful for reducing stringly typed casts while preserving access to system and app lifecycle events.
- [Core Data Debugging in Xcode using launch arguments - SwiftLee](https://www.avanderlee.com/debugging/core-data-debugging-xcode)
  **Published:** `2018-07-03T10:00:11+00:00`
  **Topics:** Concurrency · Core Data · Performance · Persistence & Synchronisation · Swift · Xcode
  **NeKI brief:** Uses launch arguments and Xcode diagnostics to inspect Core Data SQL, query performance, thread-safety violations, and migration behavior. Useful for turning opaque persistence bugs into observable store-level evidence.
- [Using Xcode custom file templates with GIT - SwiftLee](https://www.avanderlee.com/workflow/xcode-custom-file-templates-git)
  **Published:** `2018-06-26T14:00:45+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Stores user-defined Xcode file templates in a Git repository and shares them across a team. Useful for standardizing repetitive file structure while keeping template evolution reviewable and recoverable.
- [Useful less known Xcode tips to improve your workflow - SwiftLee](https://www.avanderlee.com/workflow/useful-xcode-tips)
  **Published:** `2018-06-19T07:00:42+00:00`
  **Topics:** Concurrency · Swift · Testing · Xcode
  **NeKI brief:** Collects lesser-known Xcode actions such as Edit All in Scope, custom search scopes, and filtered test or issue views. Useful for making navigation and failure triage faster without changing project configuration.
- [App Store Optimization for your App Store Page - SwiftLee](https://www.avanderlee.com/optimization/app-store-optimization)
  **Published:** `2018-06-12T09:00:42+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Breaks App Store Optimization into title, subtitle, promotional text, assets, keywords, ratings, and Search Ads feedback. Useful for treating store discoverability as an iterative product surface rather than a one-time metadata task.
- [Enabling newly added opt-in features in Xcode 10 - SwiftLee](https://www.avanderlee.com/xcode/optin-features-xcode-10)
  **Published:** `2018-06-05T20:04:39+00:00`
  **Topics:** Concurrency · Performance · Swift · Testing · Xcode
  **NeKI brief:** Shows Xcode 10 settings worth opting into, including code folding, incremental builds, optimization levels, faster testing, and #warning markers. Useful for tuning the development environment while understanding which changes affect build or test behavior.
- [Printing data requests using a custom URLProtocol - SwiftLee](https://www.avanderlee.com/swift/printing-data-requests)
  **Published:** `2018-05-29T19:09:02+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Implements a custom URLProtocol that intercepts requests and prints their details, then scopes activation so it can be enabled for debugging. Useful for inspecting networking without embedding logging in every request call site.
- [Controlling Progress children by adding remove - SwiftLee](https://www.avanderlee.com/swift/controlling-progress-children)
  **Published:** `2018-05-24T09:00:26+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Extends Progress to remove child progress entries and recompute completion, addressing a gap in the default add-only API. Useful for dynamic workflows where tasks can be cancelled or replaced after registration.
- [Share Extension UI Tests written in Swift - SwiftLee](https://www.avanderlee.com/swift/ui-test-share-extension)
  **Published:** `2018-05-18T11:38:41+00:00`
  **Topics:** Concurrency · Swift · SwiftUI · Testing
  **NeKI brief:** Builds an XCTest UI flow that opens a share extension and verifies its interaction steps. Useful for covering extension-specific presentation and handoff behavior that ordinary app-target UI tests cannot exercise.
- [Fixing crashes with Firebase Crashlytics - SwiftLee](https://www.avanderlee.com/workflow/firebase-crashlytics-breadcrumbs)
  **Published:** `2018-05-08T20:26:56+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Triages a real Crashlytics crash by examining dashboard context, drilling into the failing code path, and reproducing the triggering state. Useful as a concrete crash-investigation workflow rather than a generic logging overview.
- [Update to Swift 4.1 with Xcode 9.3 using related sources](https://www.avanderlee.com/swift/update-to-swift-4-1)
  **Published:** `2018-03-30T09:58:40+00:00`
  **Topics:** Concurrency · Swift · Xcode
  **NeKI brief:** Provides a historical migration checklist for Swift 4.1 and Xcode 9.3, including related release resources. Keep it for migration-history context only; modern projects need current Swift migration documentation.
- [How to get iOS reviews with 4+ stars for your app - SwiftLee](https://www.avanderlee.com/optimization/buienradar-featured-reviews)
  **Published:** `2016-06-08T19:23:46+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Describes a Buienradar ratings campaign that selected an in-app moment and used Swrve targeting to request reviews from engaged users. Useful for understanding timing and segmentation trade-offs behind higher-quality App Store feedback.
- [Optional protocol methods in Swift - SwiftLee](https://www.avanderlee.com/swift/optional-protocol-methods)
  **Published:** `2016-03-18T16:08:16+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Explains the pre-protocol-extension workaround for optional Swift requirements and contrasts it with @objc optional methods. Useful when designing protocol APIs that need default behavior without imposing Objective-C runtime constraints.
- [WWDC First timers tips collection top 10 - SwiftLee](https://www.avanderlee.com/wwdc/wwdc-first-timers-tips-collection-top-10)
  **Published:** `2015-06-03T17:56:29+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Collects practical first-time WWDC advice on planning sessions, meeting developers, and balancing talks with the wider event. Useful for preparing an efficient conference itinerary when the schedule is larger than one attendee can cover.
- [The start of a new blog - SwiftLee](https://www.avanderlee.com/swift/the-start-of-a-new-blog)
  **Published:** `2015-05-02T12:52:51+00:00`
  **Topics:** Concurrency · Swift
  **NeKI brief:** Describes the motivation and scope behind starting a Swift development blog, including choosing a technical audience and publishing consistently. Useful as historical context for the author’s later writing and as a reflection on developer knowledge sharing.
