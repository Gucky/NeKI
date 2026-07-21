# SwiftLee Weekly

Third-party source index. It provides source attribution and routing metadata, not republished article content. Verify article conclusions independently before applying them.

- Archive: [https://newsletter.avanderlee.com/posts](https://newsletter.avanderlee.com/posts)
- Last collected: `2026-07-22T15:21:40Z`
- Indexed entries: **93**

## [Issue 323 · 2026-07-21](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-323-1)

- Published: `2026-07-21T14:05:55.000Z`

**Topics:** Swift · Architecture · SwiftUI · Persistence & Synchronisation · SwiftData · AI Development

**Sections:** SwiftLee Weekly by Antoine van der Lee · How to Test iOS Apps in Different Time Zones on a Physical iPhone · Share your AI agent’s work with your team

**Selected links:**
- [Building adaptive non-modal panels in SwiftUI](https://nilcoalescing.com/blog/BuildingAdaptiveNonModalPanelsInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a custom SwiftUI panel that changes from a bottom sheet to an edge-aligned panel using measured scene geometry, custom Layout, preferences, and detents. The drag implementation preserves scrolling by combining gestures deliberately.
- [ImplementedSE-0525Safe loading API for `RawSpan`](https://github.com/apple/swift-evolution/blob/main/proposals/0525-rawspan-safe-loading-api.md) — Source repository · Topics: Swift · Architecture
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0525Safe loading API for `RawSpan`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Geometry, compositing and drawing groups in SwiftUI](https://nilcoalescing.com/blog/GeometryCompositingAndDrawingGroupsInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Separates geometryGroup, compositingGroup, and drawingGroup by the stage of rendering or animation they affect. The comparison helps diagnose visual artifacts and choose a modifier based on actual compositing needs rather than similar names.

## [Issue 322 · 2026-07-14](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-322-1)

- Published: `2026-07-14T14:06:22.000Z`

**Topics:** Swift · Concurrency · SwiftUI · Liquid Glass · Xcode · Testing

**Sections:** SwiftLee Weekly by Antoine van der Lee · User Diagnostics Reports: Solving app bugs faster with AI Agents · Fastlane alternative - Codemagic CLI tools

**Selected links:**
- [The hidden cost of unstable SwiftUI environment defaults](https://nilcoalescing.com/blog/UnstableDefaultEnvironmentValuesInSwiftUI) — Article · Topics: Swift · SwiftUI · Xcode
  **NeKI brief:** Diagnoses update churn caused by reference-typed default environment values and explains why stable defaults matter. Useful when environment injection unexpectedly invalidates views or changes identity.
- [Splitting Large SwiftUI Views in the Apple's way](https://emredegirmenci.substack.com/p/splitting-large-swiftui-views-in) — Article · Topics: Swift · SwiftUI · Xcode
  **NeKI brief:** Explains Apple's own decomposition techniques for splitting large SwiftUI views, including state and builder boundaries. Useful for reducing oversized bodies while keeping data flow explicit, previewable, and understandable to teammates.
- [anyAppleOS in Swift 6.4](https://livsycode.com/swift/swift-6-4-adds-anyappleos-for-cleaner-availability-checks) — Article · Topics: Swift
  **NeKI brief:** Explains Swift 6.4's anyAppleOS type as a way to express availability checks without spelling every Apple platform. Use it when auditing cross-platform branches, while confirming the exact compiler and SDK version before adoption.
- [Fastlane alternative - Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [Liquid Glass can be gradually rolled out](https://www.scottberrevoets.com/til/liquid-glass-can-be-gradually-rolled-out) — Article · Topics: Liquid Glass
  **NeKI brief:** Shows how Liquid Glass adoption can be staged instead of switching an entire interface at once. Use it when planning incremental visual migrations, with separate review of fallback behavior and platform availability.

## [Issue 331](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-331)

- Published: `2026-07-07T14:05:55.000Z`

**Topics:** Swift · SwiftUI · Concurrency · Xcode · AI Development · Testing

**Sections:** SwiftLee Weekly by Antoine van der Lee · Defer in Swift explained with Code Examples · Tired of Fixing Xcode UI Tests Every Release?

**Selected links:**
- [Rotating Liquid Glass in SwiftUI without breaking the shape](https://livsycode.com/swiftui/liquid-glass-rotating) — Article · Topics: Swift · SwiftUI · Liquid Glass
  **NeKI brief:** Demonstrates rotating Liquid Glass content while preserving the effect's shape and visual continuity. Use it when animated controls or cards distort during transforms and you need a compositing-aware SwiftUI implementation.
- [physical devices](https://www.rocketsim.app/docs/features/capturing/physical-device-support) — Article · Topics: Swift · Concurrency · SwiftUI
  **NeKI brief:** Documents RocketSim capture support for USB-connected physical devices. Use it to evaluate a device-recording workflow for demos or bug evidence, checking supported OS versions and the operational limits of the tool.
- [Debugging Notes on Two SwiftUI Animation Bugs](https://fatbobman.com/en/posts/debugging-notes-on-two-swiftui-animation-bugs) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Uses two concrete SwiftUI animation failures to show how declarative animation can obscure causality. Follow it when a transition or state-driven animation misbehaves and you need diagnostic observations that reveal the framework behaviour rather than only a workaround.
- [AcceptedSE-0513API to get the path to the current executable](https://github.com/apple/swift-evolution/blob/main/proposals/0513-commandline-executablepath.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0513API to get the path to the current executable. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.

## [Issue 330](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-330)

- Published: `2026-06-30T14:07:37.000Z`

**Topics:** Swift · Xcode · Concurrency · Swift Package Manager · Testing · Networking

**Sections:** SwiftLee Weekly by Antoine van der Lee · Memberwise Initializer in Swift explained with Code Examples · Add AI Control to Xcode’s Simulator and Device Hub

**Selected links:**
- [ImplementedSE-0528`Continuation` — Safe and Performant Async Continuations](https://github.com/apple/swift-evolution/blob/main/proposals/0528-noncopyable-continuation.md) — Source repository · Topics: Swift · Concurrency
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0528`Continuation` — Safe and Performant Async Continuations. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0534Opt-in exact matching for version identifiers with build metadata](https://github.com/apple/swift-evolution/blob/main/proposals/0534-swiftpm-exact-literal-version-matching.md) — Source repository · Topics: Swift · Swift Package Manager
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0534Opt-in exact matching for version identifiers with build metadata. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Using Cursor in Xcode 27](https://www.polpiella.dev/cursor-xcode-27) — Article · Topics: Xcode
  **NeKI brief:** Explains installing Cursor’s agent CLI, registering it through Xcode 27’s ACP support, and selecting it for new conversations. Follow it when comparing external agent choice with Xcode’s remembered conversation-agent state.
- [iOS 27 SDK: 3 Major Requirements That Might Break Your App](https://blog.makwanbk.com/ios-27-sdk-3-major-requirements-that-migh-break-your-app) — Article · Topics: Xcode
  **NeKI brief:** Summarizes three iOS 27 SDK requirements that may surface during an upgrade. Use it as a migration checklist for build and runtime audits, then verify each requirement against Apple's release documentation.

## [Issue 329](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-329)

- Published: `2026-06-23T14:07:47.000Z`

**Topics:** Swift · Concurrency · SwiftUI · Xcode · App Intents & System Surfaces · Macros & Metaprogramming

**Sections:** SwiftLee Weekly by Antoine van der Lee · Swift 6.4: What’s New in Concurrency · Add AI Control to Xcode’s Simulator and Device Hub

**Selected links:**
- [iOS 27, Your App, and Siri](https://www.swiftjectivec.com/siri-ai-for-ios027) — Article · Topics: App Intents & System Surfaces · Swift · AI Development
  **NeKI brief:** Discusses how iOS 27's Siri and AI changes affect app integration through App Intents and system surfaces. Use it to identify intent-driven opportunities, then validate availability and interaction rules in Apple's documentation.
- [SwiftUI: Observable macro under the hood](https://www.nsvasilev.com/posts/swiftui-observable-macro) — Article · Topics: Macros & Metaprogramming · Swift · SwiftUI
  **NeKI brief:** Peels back SwiftUI’s Observable macro expansion, showing the generated observation machinery behind an @Observable model. Useful when diagnosing tracking behavior, deciding which properties need observation, or explaining macro-generated code to a team.
- [Active ReviewSE-0513API to get the path to the current executable](https://github.com/apple/swift-evolution/blob/main/proposals/0513-commandline-executablepath.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0513API to get the path to the current executable. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [What’s new in SwiftUI (2-minute recap)](https://www.swiftwithvincent.com/blog/whats-new-in-swiftui-2-minute-recap) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Provides a concise tour of SwiftUI changes introduced around WWDC 2026. Use it to triage which new APIs deserve deeper investigation before reading their authoritative availability, behavior, and migration details.

## [Issue 328](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-328)

- Published: `2026-06-16T14:06:32.000Z`

**Topics:** Swift · SwiftUI · Xcode · Concurrency · AI Development · Persistence & Synchronisation

**Sections:** SwiftLee Weekly by Antoine van der Lee · SwiftUI Best Practices, straight from Apple's Xcode 27 Agent Skill · Stop configuring MCPs in every AI app

**Selected links:**
- [Release 4.0.0 · AvdLee/SwiftUI-Agent-Skill](https://github.com/AvdLee/SwiftUI-Agent-Skill/releases/tag/4.0.0) — Source repository · Topics: Swift · SwiftUI · Testing
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Release 4.0.0 · AvdLee/SwiftUI-Agent-Skill. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Stop configuring MCPs in every AI app](https://www.mcp-beast.ai/mac-app-ios-developers) — Article · Topics: AI Development · Persistence & Synchronisation
  **NeKI brief:** Explores centralizing MCP configuration so multiple AI clients can share one setup. Use it when reducing repeated tool registration across development environments, while reviewing credential handling and client-specific capability differences.
- [WWDC26: Xcode Tips and Tricks Group Lab - Q&A](https://antongubarenko.substack.com/p/wwdc26-xcode-tips-and-tricks-group) — Article · Topics: Xcode · Testing
  **NeKI brief:** Explains WWDC26: Xcode Tips and Tricks Group Lab - Q&A, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [What's New In Swiftdata](https://azamsharp.com/2026/06/12/whats-new-in-swiftdata.html) — Article · Topics: Swift · SwiftData · Persistence & Synchronisation
  **NeKI brief:** Summarizes SwiftData changes for iOS 27. Use it to identify migration and feature candidates for a persistence layer, then verify model, query, and availability details against current Apple documentation.
- [Using Claude with Apple Foundation Models](https://artemnovichkov.com/blog/using-claude-with-apple-foundation-models) — Article · Topics: AI Development
  **NeKI brief:** Explores combining Claude with Apple Foundation Models in an Apple-platform workflow. Use it when comparing cloud-model assistance with on-device generation, especially around handoff boundaries, privacy, and feature availability.
- [Async cleanup with defer in Swift](https://tanaschita.com/swift-defer-async) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Shows how defer interacts with async and throwing Swift code so cleanup still occurs across suspension and errors. Use it to centralize resource release while keeping asynchronous lifetime and cancellation behavior explicit.
- [Custom scroll layouts with swipe actions in SwiftUI on iOS 27](https://nilcoalescing.com/blog/CustomScrollLayoutsWithSwipeActionsInSwiftUIOnIOS27) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows custom scroll layouts combined with swipe actions in SwiftUI on iOS 27. Use it when list-like interactions need nonstandard geometry without giving up contextual swipe affordances.

## [Issue 327](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-327)

- Published: `2026-06-09T21:59:45.000Z`

**Topics:** Swift · SwiftUI · Xcode · Concurrency · AI Development · Macros & Metaprogramming

**Sections:** SwiftLee Weekly by Antoine van der Lee · Using Xcode 27's Agent Skills in Claude, Codex, and Cursor · Stop configuring MCPs in every AI app

**Selected links:**
- [Initializing @Observable classes with the @State macro in Xcode 27](https://nilcoalescing.com/blog/InitializingObservableClassesWithTheStateMacroInXcode27) — Article · Topics: Macros & Metaprogramming · Xcode · Observation & State Management
  **NeKI brief:** Explains initializing an @Observable reference type through @State in current SwiftUI. Use it when a view owns an observable model and must preserve its identity across body recalculation rather than recreating it inline.
- [Stop configuring MCPs in every AI app](https://www.mcp-beast.ai/mac-app-ios-developers) — Article · Topics: AI Development · Persistence & Synchronisation
  **NeKI brief:** Explores centralizing MCP configuration so multiple AI clients can share one setup. Use it when reducing repeated tool registration across development environments, while reviewing credential handling and client-specific capability differences.
- [SwiftUI reorderable containers in iOS 27](https://livsycode.com/swiftui/swiftui-reorderable-containers-in-ios-27) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows reorderable SwiftUI containers introduced for iOS 27 and the interaction model they enable. Use it when replacing custom drag-state code, checking platform availability and accessibility behavior before migration.
- [What is new in SwiftUI after WWDC26](https://swiftwithmajid.com/2026/06/08/what-is-new-in-swiftui-after-wwdc26) — Article · Topics: Swift · SwiftUI · Concurrency
  **NeKI brief:** Summarizes SwiftUI additions after WWDC 2026. Use it to discover relevant new layout, rendering, and system-integration capabilities before narrowing to one feature and reading its authoritative API documentation.
- [iOS 27: Notable UIKit Additions](https://www.swiftjectivec.com/ios-27-notable-uikit-additions) — Article · Topics: UIKit · Swift
  **NeKI brief:** Surveys notable UIKit additions in iOS 27. Use it to identify modernization opportunities in an existing UIKit codebase, then verify API availability and migration impact in the relevant Apple documentation.
- [Active ReviewSE-0516`Iterable`](https://github.com/apple/swift-evolution/blob/main/proposals/0516-borrowing-sequence.md) — Source repository · Topics: Swift · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0516`Iterable`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.

## [Issue 326](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-326)

- Published: `2026-06-02T14:07:19.000Z`

**Topics:** Swift · Concurrency · AI Development · Persistence & Synchronisation · Xcode · Liquid Glass

**Sections:** SwiftLee Weekly by Antoine van der Lee · WWDC 2026: My predictions and wishes · Is Your iOS App Secure?

**Selected links:**
- [Task Names in Swift Concurrency](https://artemnovichkov.com/blog/task-names-in-swift-concurrency) — Article · Topics: Concurrency · Swift · Performance
  **NeKI brief:** Explains naming tasks in Swift concurrency and how names aid debugging and observability. Follow it when tracing asynchronous work, while keeping names descriptive and avoiding assumptions that labels change scheduling, isolation, or cancellation semantics.
- [Stateless Actors](https://www.massicotte.org/stateless-actors) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Examines stateless actors and what remains useful about actor isolation when no mutable state is stored. Follow it when choosing concurrency boundaries, distinguishing synchronization guarantees from mere type organization and measuring whether an actor adds real value.
- [DebugSnapshots: Public beta](https://www.pointfree.co/blog/posts/207-debugsnapshots-public-beta) — Article
  **NeKI brief:** Introduces DebugSnapshots for recording and inspecting application state as debugging artifacts. Use it when a visual or state regression needs reproducible evidence that can be reviewed without reproducing the entire interactive session.
- [W.W.D.C. 2026: The Pregame Quiz](https://www.swiftjectivec.com/wwdc-2026-the-pregame-quiz) — Article · Topics: Swift
  **NeKI brief:** Presents W.W.D.C. 2026: The Pregame Quiz, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Clearing UserDefaults during macOS app development](https://nilcoalescing.com/blog/ClearingUserDefaultsDuringmacOSAppDevelopment) — Article
  **NeKI brief:** Shows targeted UserDefaults cleanup during macOS development. Use it to reset persisted test state without deleting unrelated preferences, especially when a menu-bar or sandboxed app retains configuration between launches.

## [Issue 325](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-325)

- Published: `2026-05-26T14:06:24.000Z`

**Topics:** Swift · Xcode · Concurrency · Performance · SwiftUI · AI Development

**Sections:** SwiftLee Weekly by Antoine van der Lee · Using Xcode Instruments to optimize Swift Concurrency Code · Is Your iOS App Secure?

**Selected links:**
- [Using Xcode Instruments to optimize Swift Concurrency Code](https://www.youtube.com/watch?v=hDFOy-ynJ6I) — Video · Topics: Performance · Xcode · Concurrency
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Modern SwiftUI APIs for programmatic scrolling](https://nilcoalescing.com/blog/ModernSwiftUIAPIsForProgrammaticScrolling) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Uses modern SwiftUI scrolling APIs to observe visible items, target positions, and programmatic movement. Useful for replacing preference-key workarounds with typed scroll coordination.
- [Xcode should be decoupled from Swift versions](https://macguru.dev/xcode-should-be-decoupled-from-swift-versions) — Article · Topics: Swift · Xcode
  **NeKI brief:** Argues that Xcode and Swift version coupling creates avoidable upgrade friction. Use it as a language-toolchain compatibility perspective when planning CI matrices, migration sequencing, and package version constraints.
- [Deprecating your own convenience API](https://swiftwithmajid.com/2026/05/19/deprecating-your-own-convenience-api) — Article · Topics: Swift
  **NeKI brief:** Explains deprecating a convenience API with migration messages and replacement paths. Use it when evolving an internal or public Swift interface while keeping callers compiling and making the preferred alternative discoverable.
- [Making a SwiftUI sheet automatically size to fit its content](https://danielsaidi.com/blog/2026/05/22/making-a-swiftui-sheet-automatically-size-to-fit-its-content) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI sheet that measures its content and chooses an appropriate presentation height. Useful for compact forms and detail panels that should avoid excessive empty space while handling dynamic type and updates.

## [Issue 324](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-324)

- Published: `2026-05-19T14:04:54.000Z`

**Topics:** Swift · Concurrency · AI Development · Xcode · Liquid Glass · SwiftUI

**Sections:** SwiftLee Weekly by Antoine van der Lee · Recording a Physical iPhone for App Preview Videos · Fastlane alternative - Codemagic CLI tools

**Selected links:**
- [Using Xcode MCP with Claude Code](https://danielsaidi.com/blog/2026/04/30/using-xcode-mcp-with-claude-code) — Article · Topics: Xcode · AI Development
  **NeKI brief:** Describes connecting Claude Code to Xcode through Model Context Protocol. Follow it when evaluating agent-assisted build and debugging workflows, paying attention to permissions, simulator boundaries, generated changes, and human review checkpoints.
- [Teaching Skills to an AI Harness](https://alejandromp.com/development/blog/teaching-skills-to-an-ai-harness) — Article · Topics: AI Development · Swift
  **NeKI brief:** Describes structuring reusable skills for an AI coding harness rather than relying on one large prompt. Use it when designing maintainable agent instructions with explicit scope, tool boundaries, and progressive disclosure.
- [AcceptedSE-0525Safe loading API for `RawSpan`](https://github.com/apple/swift-evolution/blob/main/proposals/0525-rawspan-safe-loading-api.md) — Source repository · Topics: Swift · AI Development
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0525Safe loading API for `RawSpan`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [AcceptedSE-0530Async Result Support](https://github.com/apple/swift-evolution/blob/main/proposals/0530-async-result-support.md) — Source repository · Topics: Swift · Concurrency · AI Development
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0530Async Result Support. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Fastlane alternative - Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [A floating card using safeAreaBar](https://codakuma.com/floating-safe-area-bar) — Article
  **NeKI brief:** Creates a floating bar with SwiftUI’s safeAreaBar modifier, keeping controls attached to safe-area edges as content scrolls. Useful for persistent actions or playback controls without manual inset calculations and overlay hit-testing.

## [Issue 323 · 2026-05-12](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-323)

- Published: `2026-05-12T14:05:49.000Z`

**Topics:** Swift · SwiftUI · Concurrency · Xcode · Accessibility · Testing

**Sections:** SwiftLee Weekly by Antoine van der Lee · AI-Powered Xcode Simulator Automation (token-efficient) · Is Your iOS App Secure?

**Selected links:**
- [AI-Powered Xcode Simulator Automation (token-efficient)](https://www.youtube.com/watch?v=mD6vpokRpsU) — Video · Topics: Testing · Xcode · AI Development
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [A guide to macOS window toolbar styles in SwiftUI](https://nilcoalescing.com/blog/AGuideToMacOSToolbarStylesInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Compares macOS SwiftUI toolbar styles and their visual roles. Use it when a window's title area, navigation controls, and command density should align with the platform instead of inheriting an accidental default appearance.
- [3 Key Strategies to Make SwiftUI Views More Reusable](https://matteomanferdini.com/swiftui-reusable-views) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents three concrete strategies for making SwiftUI views reusable, from extracting components to controlling dependencies and state. Useful when reducing duplication without hiding feature-specific behavior behind overly generic abstractions.
- [Swift ARC: From Zombie Objects to Side Tables](https://livsycode.com/swift/swift-arc-from-zombie-objects-to-side-tables) — Article · Topics: Swift
  **NeKI brief:** Explains Swift ARC through zombie objects, reference counting, and side tables. Use it as a low-level diagnostic aid when investigating unexpected retention or weak-reference behavior, especially in mixed Swift and Objective-C code.
- [AcceptedSE-0528`Continuation` — Safe and Performant Async Continuations](https://github.com/apple/swift-evolution/blob/main/proposals/0528-noncopyable-continuation.md) — Source repository · Topics: Swift · Concurrency
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0528`Continuation` — Safe and Performant Async Continuations. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.

## [Issue 322 · 2026-05-05](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-322)

- Published: `2026-05-05T14:09:40.000Z`

**Topics:** Swift · Concurrency · SwiftUI · Testing · Xcode · AI Development

**Sections:** SwiftLee Weekly by Antoine van der Lee · Stop waiting. Start shipping. · Scheduling and handling background app refresh in SwiftUI

**Selected links:**
- [Synchronization in Swift: Actors vs Queues vs Locks → Livsy Code](https://livsycode.com/best-practices/actors-vs-queues-vs-locks-in-swift) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Compares actors, dispatch queues, and locks as synchronization tools in Swift. Use it when selecting a concurrency primitive by ownership, reentrancy, contention, and migration constraints rather than by modernity alone.
- [How to implement pagination with SwiftUI's List view](https://tanaschita.com/swiftui-list-pagination) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Implements incremental pagination in SwiftUI List as the user approaches the end of loaded content. Use it when an async data source needs explicit loading, error, and duplicate-request guards rather than eager full retrieval.
- [ImplementedSE-0524Add `withTemporaryAllocation` using `Output(Raw)Span`](https://github.com/apple/swift-evolution/blob/main/proposals/0524-span-temporary-allocation.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0524Add `withTemporaryAllocation` using `Output(Raw)Span`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Swift Concurrency Agent Skill](https://github.com/AvdLee/Swift-Concurrency-Agent-Skill) — Source repository · Topics: Concurrency · Swift
  **NeKI brief:** Provides focused agent guidance for Swift concurrency work. Use it to give coding agents project-relevant rules around isolation, Sendable boundaries, and async tests before they propose or edit concurrent Swift code.
- [Scheduling and handling background app refresh in SwiftUI](https://nilcoalescing.com/blog/SchedulingAndHandlingBackgroundAppRefreshInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows how a SwiftUI app enables, schedules, handles, and tests background refresh work using Background Tasks and backgroundTask(_:action:).
- [Active ReviewSE-0530Async Result Support](https://github.com/apple/swift-evolution/blob/main/proposals/0530-async-result-support.md) — Source repository · Topics: Swift · Concurrency
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0530Async Result Support. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [CLI](https://www.rocketsim.app/docs/features/agentic-development/rocketsim-cli) — Article · Topics: Testing · AI Development
  **NeKI brief:** Explains CLI, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [RocketSim now works with USB-connected devices](https://www.rocketsim.app/docs/features/capturing/physical-device-support) — Article
  **NeKI brief:** Documents RocketSim capture support for USB-connected physical devices. Use it to evaluate a device-recording workflow for demos or bug evidence, checking supported OS versions and the operational limits of the tool.

## [Issue 321](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-321)

- Published: `2026-04-28T14:07:22.000Z`

**Topics:** Swift · SwiftUI · Concurrency · Performance · Xcode · AI Development

**Sections:** SwiftLee Weekly by Antoine van der Lee · Stop waiting. Start shipping. · An Odometer-Style Number Animation in SwiftUI

**Selected links:**
- [An Odometer-Style Number Animation in SwiftUI](https://livsycode.com/swiftui/an-odometer-style-number-animation-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds an odometer-style number animation in SwiftUI using composable transitions and state changes. Use it for counters or metrics that need legible motion without manually coordinating per-digit UIKit layers.
- [Recording & Analyzing SwiftUI Instruments Traces](https://github.com/AvdLee/SwiftUI-Agent-Skill) — Source repository · Topics: Swift · SwiftUI · Performance
  **NeKI brief:** Describes A SwiftUI agent skill for better code reviews, focusing on practical tool integration and workflow trade-offs. Use it to evaluate reproducibility, trust boundaries, and debugging steps before adopting the approach in an Xcode project.
- [AcceptedSE-0511SwiftPM Add Target Plugin Command](https://github.com/apple/swift-evolution/blob/main/proposals/0511-swiftpm-add-target-plugin.md) — Source repository · Topics: Swift · Swift Package Manager · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0511SwiftPM Add Target Plugin Command. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [SwiftUI: Refreshable Task Cancellation](https://antongubarenko.substack.com/p/swiftui-refreshable-task-cancellation) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains how refreshable starts asynchronous work and how cancellation propagates when the user ends or repeats a refresh. Useful for making pull-to-refresh tasks idempotent, responsive, and safe against stale results.

## [Issue 320](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-320)

- Published: `2026-04-21T14:11:27.000Z`

**Topics:** Swift · SwiftUI · Performance · Concurrency · Xcode · App Intents & System Surfaces

**Sections:** SwiftLee Weekly by Antoine van der Lee · Lessons Learned from Security Incidents in Mobile Apps · Apple Developer Community Meetup during WWDC

**Selected links:**
- [A Reusable Spotlight Onboarding Component in SwiftUI](https://livsycode.com/swiftui/a-reusable-spotlight-onboarding-component-in-swiftui) — Article · Topics: Swift · SwiftUI · App Intents & System Surfaces
  **NeKI brief:** Builds a reusable SwiftUI spotlight onboarding component that highlights interface elements. Use it when designing guided discovery, keeping target geometry, overlay interaction, accessibility, and dismissal state separate from feature content.
- [Building a draggable bottom sheet in SwiftUI](https://tanaschita.com/swiftui-draggable-bottom-sheet) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a draggable SwiftUI bottom sheet with gesture state, detents, and snapping decisions. Useful for custom interaction when system sheets do not expose the required presentation behavior.
- [RocketSim's CLI is already live](https://www.rocketsim.app/docs/features/agentic-development/rocketsim-cli) — Article · Topics: AI Development · Xcode
  **NeKI brief:** Explains CLI, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [A Small SwiftUI Warning and a Long Journey to Understand It](https://alejandromp.com/development/blog/a-small-swiftui-warning-and-a-long-journey-to-understand-it) — Article · Topics: Swift · SwiftUI · Concurrency
  **NeKI brief:** Traces a seemingly minor SwiftUI warning back through view updates and concurrency interactions. Use it as a diagnostic case study for following framework diagnostics to their underlying data-flow cause instead of suppressing them.
- [Active ReviewSE-0528`Continuation` — Safe and Performant Async Continuations](https://github.com/apple/swift-evolution/blob/main/proposals/0528-noncopyable-continuation.md) — Source repository · Topics: Swift · Concurrency · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0528`Continuation` — Safe and Performant Async Continuations. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [FormatStyle Guide](https://chris.eidhof.nl/post/format-style-guide) — Article · Topics: Swift
  **NeKI brief:** Introduces an interactive browser-based guide to Swift Foundation FormatStyle APIs, implemented with WebAssembly. Use the linked guide for quickly comparing formatting capabilities and verify availability against current Foundation documentation.
- [AcceptedSE-0524Add `withTemporaryAllocation` using `Output(Raw)Span`](https://github.com/apple/swift-evolution/blob/main/proposals/0524-span-temporary-allocation.md) — Source repository · Topics: Swift · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0524Add `withTemporaryAllocation` using `Output(Raw)Span`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.

## [Issue 319](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-319)

- Published: `2026-04-14T14:07:31.000Z`

**Topics:** Swift · SwiftUI · Xcode · Concurrency · AI Development · Accessibility

**Sections:** SwiftLee Weekly by Antoine van der Lee · Network Requests Optimization using Xcode’s Simulator & Agents · Give your AI agent eyes and hands on iOS

**Selected links:**
- [Give your AI agent eyes and hands on iOS](https://flowdeck.studio/swiftlee?code=SWIFTLEE25) — Article · Topics: Swift · AI Development · Xcode
  **NeKI brief:** Presents Give your AI agent eyes and hands on iOS, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Checking accessibility with SwiftUI Previews](https://mobilea11y.com/blog/swiftui-preview-testing) — Article · Topics: Swift · SwiftUI · Accessibility
  **NeKI brief:** Uses SwiftUI previews as an accessibility testing surface, checking labels, traits, and contrast across representative states. Useful for finding VoiceOver regressions early without waiting for a full UI-test suite.
- [Network Requests Optimization using Xcode’s Simulator & Agents](https://www.youtube.com/watch?v=Y5bd6FHA3K4) — Video · Topics: Xcode
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Kids and Vibe Coding: The Joy of Building](https://www.swiftjectivec.com/kids-and-vibe-coding-ios-apps) — Article · Topics: Swift
  **NeKI brief:** Reflects on children building iOS apps with AI-assisted or vibe-coding tools. Use it as a product and education perspective on lowering entry barriers while retaining testing, safety, authorship, and review practices.
- [Working with files and directories in iOS](https://tanaschita.com/ios-file-system-overview) — Article
  **NeKI brief:** Maps iOS file-system locations and the responsibilities of app documents, caches, and temporary storage. Use it when choosing a persistence location whose backup, eviction, and user-visibility behavior matches the data.

## [Issue 318](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-318)

- Published: `2026-04-07T14:09:08.000Z`

**Topics:** Swift · SwiftUI · Architecture · Concurrency · Accessibility · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · Stop waiting. Start shipping. · iOSKonf Ticket Giveaway

**Selected links:**
- [Active ReviewSE-0525Safe loading API for `RawSpan`](https://github.com/apple/swift-evolution/blob/main/proposals/0525-rawspan-safe-loading-api.md) — Source repository · Topics: Swift · Architecture · Composable Architecture
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0525Safe loading API for `RawSpan`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Building List replacement in SwiftUI](https://swiftwithmajid.com/2026/04/06/building-list-replacement-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a custom SwiftUI list replacement by composing scrolling, layout, and row behavior directly. Use it when List's styling or interaction constraints are the real limitation, while measuring the performance cost of custom virtualization.
- [SwiftUI Custom Popover](https://livsycode.com/swiftui/swiftui-custom-popover) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates building a custom popover in SwiftUI when system presentation is too constrained. Follow it when evaluating geometry, dismissal, hit testing, and accessibility requirements, and prefer system popovers where their behavior is sufficient.
- [No, SwiftUI is not “Accessible by default”](https://mobilea11y.com/blog/swiftui-not-accessible) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Challenges the assumption that SwiftUI interfaces are accessible by default. Use it as an audit prompt to verify labels, traits, focus order, Dynamic Type, contrast, and custom controls with assistive technologies.
- [Beta Preview: ComposableArchitecture 2.0](https://www.pointfree.co/blog/posts/206-beta-preview-composablearchitecture-2-0) — Article · Topics: Architecture · Composable Architecture · Macros & Metaprogramming
  **NeKI brief:** Previews Composable Architecture 2.0 changes and their implications for state, effects, and dependency management. Use it to assess an upcoming migration path before adopting beta conventions in a production feature.
- [Returned For RevisionSE-0516Borrowing Sequence](https://github.com/apple/swift-evolution/blob/main/proposals/0516-borrowing-sequence.md) — Source repository · Topics: Swift · Architecture · Composable Architecture
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0516`Iterable`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0524Add `withTemporaryAllocation` using `Output(Raw)Span`](https://github.com/apple/swift-evolution/blob/main/proposals/0524-span-temporary-allocation.md) — Source repository · Topics: Swift · Architecture · Composable Architecture
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0524Add `withTemporaryAllocation` using `Output(Raw)Span`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Embedding SF Symbols in SwiftUI Text](https://nilcoalescing.com/blog/EmbeddingSFSymbolsInSwiftUIText) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows embedding SF Symbols inline with SwiftUI Text so symbol and typography layout together. Use it when labels need dynamic-type-aware iconography without separate HStack alignment and baseline adjustments.

## [Issue 317](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-317)

- Published: `2026-03-31T14:07:14.000Z`

**Topics:** Swift · Xcode · Concurrency · Testing · AI Development · SwiftUI

**Sections:** SwiftLee Weekly by Antoine van der Lee · Stop waiting. Start shipping. · WWDC 2026 Pins – Because We All Collect Them Anyway

**Selected links:**
- [Swift 6.3 Released](https://www.swift.org/blog/swift-6.3-released) — Article · Topics: Swift · Testing
  **NeKI brief:** Announces Swift 6.3 and summarizes the language, package, and tooling changes in that release. Use it to identify migration candidates, then consult the release notes and proposal links for exact compiler behavior and availability.
- [Package Traits in Xcode](https://www.massicotte.org/blog/package-traits-in-xcode) — Article · Topics: Xcode · AI Development
  **NeKI brief:** Introduces Swift package traits in Xcode and shows how conditional package features can avoid maintaining multiple package variants.
- [Returned For RevisionSE-0490Environment Constrained Shared Libraries](https://github.com/apple/swift-evolution/blob/main/proposals/0490-environment-constrained-shared-libraries.md) — Source repository · Topics: Swift · Xcode
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Returned For RevisionSE-0490Environment Constrained Shared Libraries. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ImplementedSE-0502Exclude private initialized properties from memberwise initializer](https://github.com/apple/swift-evolution/blob/main/proposals/0502-exclude-private-from-memberwise-init.md) — Source repository · Topics: Swift · Xcode
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0502Exclude private initialized properties from memberwise initializer. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.

## [Issue 316](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-316)

- Published: `2026-03-24T15:03:10.000Z`

**Topics:** Swift · Concurrency · SwiftUI · AI Development · Xcode · Liquid Glass

**Sections:** SwiftLee Weekly by Antoine van der Lee · iOS auth eating your time? · WWDC26 Apple Park Special Event

**Selected links:**
- [Expanding Animations in SwiftUI Lists](https://nerdyak.tech/development/2026/03/16/expand-animation-in-SwiftUI-List.html) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Diagnoses janky expand and collapse animations inside SwiftUI List and documents the identity and transaction choices that improve them. Useful when animating variable-height rows without breaking list diffing or scroll performance.
- [ImplementedSE-0493Support `async` calls in `defer` bodies](https://github.com/apple/swift-evolution/blob/main/proposals/0493-defer-async.md) — Source repository · Topics: Swift · Concurrency
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0493Support `async` calls in `defer` bodies. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [iOS auth eating your time?](https://go.clerk.com/sxkDCu7) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Presents iOS auth eating your time?, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Apple’s Hidden Collection and Sequence APIs You Should Be Using](https://www.sagarunagar.com/blog/swift-algorithms-complete-guide) — Article · Topics: Swift
  **NeKI brief:** Explains Apple’s Hidden Collection and Sequence APIs You Should Be Using, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [ImplementedSE-0491Module selectors for name disambiguation](https://github.com/apple/swift-evolution/blob/main/proposals/0491-module-selectors.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0491Module selectors for name disambiguation. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ImplementedSE-0499Support ~Copyable, ~Escapable in simple standard library protocols](https://github.com/apple/swift-evolution/blob/main/proposals/0499-support-non-copyable-simple-protocols.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0499Support ~Copyable, ~Escapable in simple standard library protocols. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.

## [Issue 315](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-315)

- Published: `2026-03-17T15:01:49.000Z`

**Topics:** Swift · SwiftUI · Concurrency · Xcode · Navigation & Deep Linking · AI Development

**Sections:** SwiftLee Weekly by Antoine van der Lee · How iOS apps actually make money · iOS Dev Directory

**Selected links:**
- [SwiftUI Agent Skill](https://github.com/AvdLee/SwiftUI-Agent-Skill/releases/tag/2.3.0) — Source repository · Topics: Swift · SwiftUI · Navigation & Deep Linking
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for SwiftUI Agent Skill. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Swift Concurrency Agent Skill](https://github.com/AvdLee/Swift-Concurrency-Agent-Skill/releases/tag/2.0.0) — Source repository · Topics: Concurrency · Swift · Navigation & Deep Linking
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Swift Concurrency Agent Skill. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Xcode 26 Compilation Cache](https://livsycode.com/best-practices/xcode-26-compilation-cache) — Article · Topics: Xcode
  **NeKI brief:** Presents Xcode 26 Compilation Cache, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [ImplementedSE-0481`weak let`](https://github.com/apple/swift-evolution/blob/main/proposals/0481-weak-let.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0481`weak let`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [AcceptedSE-0501HTML Coverage Report](https://github.com/apple/swift-evolution/blob/main/proposals/0501-swiftpm-html-coverage-report.md) — Source repository · Topics: Swift · Swift Package Manager
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0501HTML Coverage Report. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [iOS Dev Directory](https://iosdevdirectory.com/contributing) — Article · Topics: Swift
  **NeKI brief:** Explores add their site for them, focusing on so, whether you’ve fully migrated to mastodon or now split. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Learning to develop more accessible iOS games](https://accessibilityupto11.com/post/2026-02-22-01) — Article · Topics: Accessibility
  **NeKI brief:** Presents Learning to develop more accessible iOS games, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [AcceptedSE-0515Allow `reduce` to produce noncopyable results](https://github.com/apple/swift-evolution/blob/main/proposals/0515-noncopyable-reduce.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0515Allow `reduce` to produce noncopyable results. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.

## [Issue 314](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-314)

- Published: `2026-03-10T15:03:18.000Z`

**Topics:** Swift · SwiftUI · Concurrency · Accessibility · AI Development · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · A 9-Step Framework for Choosing the Right Agent Skill · Fastlane alternative - Codemagic CLI tools

**Selected links:**
- [Why Does Passing NSManagedObjectContext Across Isolation Domains No Longer Error in Swift 6.2?](https://fatbobman.com/en/posts/sendable-nsmanagedobjectcontext) — Article · Topics: Swift · Concurrency · Core Data
  **NeKI brief:** Explains why NSManagedObjectContext crossing isolation domains no longer errors in Swift 6.2. Use it to review Core Data concurrency assumptions and verify the behavior against the active compiler and SDK.
- [Active ReviewSE-0518`~Sendable` for explicitly marking non-`Sendable` types](https://github.com/apple/swift-evolution/blob/main/proposals/0518-tilde-sendable.md) — Source repository · Topics: Swift · Concurrency · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0518`~Sendable` for explicitly marking non-`Sendable` types. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Swift at scale: building the TelemetryDeck analytics service](https://www.swift.org/blog/building-privacy-first-analytics-with-swift) — Article · Topics: Swift
  **NeKI brief:** Describes building a privacy-first analytics service in Swift and the engineering choices behind it. Follow it when evaluating telemetry architecture, data minimization, and server-side Swift trade-offs without treating the service design as an app recipe.
- [dadederk/iOS-Accessibility-Agent-Skill](https://github.com/dadederk/iOS-Accessibility-Agent-Skill) — Source repository · Topics: Accessibility · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for dadederk/iOS-Accessibility-Agent-Skill. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [twostraws/SwiftUI-Agent-Skill](https://github.com/twostraws/SwiftUI-Agent-Skill) — Source repository · Topics: Swift · SwiftUI
  **NeKI brief:** Provides a reusable SwiftUI-focused agent skill with guidance for generating and reviewing views. Useful as a concrete prompt and workflow artifact when evaluating AI-assisted UI composition, accessibility, and maintainability in a project.
- [Adjusting line height in SwiftUI on iOS 26](https://nilcoalescing.com/blog/AdjustingLineHeightInSwiftUIOniOS26) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows the iOS 26 SwiftUI line-height controls for tuning text leading while preserving Dynamic Type behavior. Useful when typography needs precise rhythm without hard-coded UIKit paragraph styles.
- [Fastlane alternative - Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.

## [Issue 313](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-313)

- Published: `2026-03-03T15:11:29.000Z`

**Topics:** Swift · Xcode · SwiftUI · Concurrency · AI Development · Swift Package Manager

**Sections:** SwiftLee Weekly by Antoine van der Lee · Fix iOS issues faster with this workshop from Sentry · Array expression trailing closures in Swift

**Selected links:**
- [Release 2.0.0 · AvdLee/SwiftUI-Agent-Skill](https://github.com/AvdLee/SwiftUI-Agent-Skill/releases/tag/2.0.0) — Source repository · Topics: Swift · SwiftUI · AI Development
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Release 2.0.0 · AvdLee/SwiftUI-Agent-Skill. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [AcceptedSE-0509Software Bill of Materials (SBOM) Generation for Swift Package Manager](https://github.com/apple/swift-evolution/blob/main/proposals/0509-swift-sboms-via-swiftpm.md) — Source repository · Topics: Swift · Swift Package Manager · Xcode
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0509Software Bill of Materials (SBOM) Generation for Swift Package Manager. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0515Allow `reduce` to produce noncopyable results](https://github.com/apple/swift-evolution/blob/main/proposals/0515-noncopyable-reduce.md) — Source repository · Topics: Swift · Xcode
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0515Allow `reduce` to produce noncopyable results. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0516Borrowing Sequence](https://github.com/apple/swift-evolution/blob/main/proposals/0516-borrowing-sequence.md) — Source repository · Topics: Swift · Xcode
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0516`Iterable`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Custom Parameters and Animation with Metal Shaders](https://www.createwithswift.com/custom-parameters-and-animation-with-metal-shaders) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates passing custom parameters into Metal shaders and animating them from SwiftUI. Use it when an effect needs GPU-driven rendering with time-varying values, while keeping shader inputs and update frequency explicit.
- [edwardsanchez/MotionEyes](https://github.com/edwardsanchez/MotionEyes) — Source repository · Topics: AI Development
  **NeKI brief:** This source repository covers instrumenting and inspecting SwiftUI animation behavior. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.

## [Issue 312](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-312)

- Published: `2026-02-24T15:08:55.000Z`

**Topics:** Swift · SwiftUI · Testing · Concurrency · Accessibility · AI Development

**Sections:** SwiftLee Weekly by Antoine van der Lee · VoiceOver Navigator & 120 FPS Recordings for Xcode’s Simulator · Release white-label apps with a single click

**Selected links:**
- [Why Your @Observable Class init() Runs Multiple Times in SwiftUI](https://livsycode.com/swiftui/why-your-observable-class-init-runs-multiple-times-in-swiftui) — Article · Topics: Swift · SwiftUI · Observation & State Management
  **NeKI brief:** Investigates why an @Observable class initializer can run repeatedly in SwiftUI. Follow it when diagnosing ownership and identity mistakes, checking observation lifetime, view reconstruction, and the distinction between initialization and persistent model state.
- [ImplementedSE-0508Array expression trailing closures](https://github.com/apple/swift-evolution/blob/main/proposals/0508-array-expression-trailing-closures.md) — Source repository · Topics: Swift · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0508Array expression trailing closures. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0513API to get the path to the current executable](https://github.com/apple/swift-evolution/blob/main/proposals/0513-commandline-executablepath.md) — Source repository · Topics: Swift · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0513API to get the path to the current executable. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Paul Hudson's SwiftAgents AGENTS.md](https://github.com/twostraws/SwiftAgents) — Source repository · Topics: Swift · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Paul Hudson's SwiftAgents AGENTS.md. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Testing with Event Streams](https://www.massicotte.org/blog/testing-event-stream) — Article · Topics: Testing · Swift
  **NeKI brief:** Explains Testing with Event Streams, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Isolate SwiftUI animations to specific attributes](https://nilcoalescing.com/blog/IsolateSwiftUIAnimationsToSpecificAttributes) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows how to scope SwiftUI animation to selected attributes rather than every state change in a view update. Use it when unrelated layout or content changes animate accidentally and make interaction feel unstable.
- [SwiftUI Agent Skill](https://github.com/AvdLee/SwiftUI-Agent-Skill) — Source repository · Topics: Swift · SwiftUI
  **NeKI brief:** Describes A SwiftUI agent skill for better code reviews, focusing on practical tool integration and workflow trade-offs. Use it to evaluate reproducibility, trust boundaries, and debugging steps before adopting the approach in an Xcode project.
- [the article it's based on](https://www.hackingwithswift.com/articles/281/what-to-fix-in-ai-generated-swift-code) — Article · Topics: Swift · AI Development
  **NeKI brief:** Lists recurring defects in AI-written Swift and suggests concrete replacements, including unsafe assumptions around state, concurrency, and framework behavior. Follow it as a review checklist before accepting generated code into an app.
- [Tracking token usage in Foundation Models](https://artemnovichkov.com/blog/tracking-token-usage-in-foundation-models) — Article · Topics: AI Development
  **NeKI brief:** Presents Tracking token usage in Foundation Models, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.

## [Issue 311](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-311)

- Published: `2026-02-17T15:07:33.000Z`

**Topics:** Swift · AI Development · Testing · Xcode · Concurrency · Persistence & Synchronisation

**Sections:** SwiftLee Weekly by Antoine van der Lee · Fastlane alternative - Codemagic CLI tools · If You Are Not Versioning Your Swiftdata Schema

**Selected links:**
- [AcceptedSE-0504Task Cancellation Shields](https://github.com/apple/swift-evolution/blob/main/proposals/0504-task-cancellation-shields.md) — Source repository · Topics: Swift · AI Development · Xcode
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0504Task Cancellation Shields. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Returned For RevisionSE-0505Delayed Enqueuing for Executors](https://github.com/apple/swift-evolution/blob/main/proposals/0505-delayed-enqueuing.md) — Source repository · Topics: Swift · AI Development · Xcode
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Returned For RevisionSE-0505Delayed Enqueuing for Executors. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [AcceptedSE-0506Advanced Observation Tracking](https://github.com/apple/swift-evolution/blob/main/proposals/0506-advanced-observation-tracking.md) — Source repository · Topics: Swift · AI Development · Xcode
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0506Advanced Observation Tracking. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [AcceptedSE-0508Array expression trailing closures](https://github.com/apple/swift-evolution/blob/main/proposals/0508-array-expression-trailing-closures.md) — Source repository · Topics: Swift · AI Development · Xcode
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0508Array expression trailing closures. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Agentic Coding in Xcode with Gemini CLI](https://peterfriese.dev/blog/2026/agentic-coding-xcode-geminicli) — Article · Topics: AI Development · Xcode
  **NeKI brief:** Connects Gemini CLI to Xcode 26.3 through Apple's MCP bridge and walks through an emoji physics example. The setup highlights version and response-format requirements that matter when using agents other than Xcode's built-in integrations.
- [Advanced NavigationStack Patterns in SwiftUI](https://buczel.com/blog/swift-navigation-stack-patterns) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents advanced NavigationStack patterns for typed routes, destinations, and path state. Useful for structuring nested flows and deep links when direct NavigationLink composition no longer provides sufficient control or testability.
- [Fastlane alternative - Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.

## [Issue 310](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-310)

- Published: `2026-02-10T15:14:11.000Z`

**Topics:** Swift · Xcode · Concurrency · AI Development · Accessibility · Architecture

**Sections:** SwiftLee Weekly by Antoine van der Lee · Core Data Agent Skill: Now available open-source · Keep your mobile app size under control with Sentry’s Size Analysis

**Selected links:**
- [Active ReviewSE-0511SwiftPM Add Target Plugin Command](https://github.com/apple/swift-evolution/blob/main/proposals/0511-swiftpm-add-target-plugin.md) — Source repository · Topics: Swift · Swift Package Manager · Xcode
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0511SwiftPM Add Target Plugin Command. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Exploring AI Driven Coding: Using Xcode 26.3 MCP Tools in Cursor, Claude Code and Codex](https://rudrank.com/exploring-xcode-using-mcp-tools-cursor-external-clients) — Article · Topics: AI Development · Xcode
  **NeKI brief:** Describes Exploring AI Driven Coding: Using Xcode 26.3 MCP Tools in Cursor, Claude Code and Codex, focusing on practical tool integration and workflow trade-offs. Use it to evaluate reproducibility, trust boundaries, and debugging steps before adopting the approach in an Xcode project.
- [An Xcode Agent Prompt: What It Signals for Combine and RxSwift](https://livsycode.com/blog/an-xcode-agent-prompt-what-it-signals-for-combine-and-rxswift) — Article · Topics: Xcode · Swift
  **NeKI brief:** Presents An Xcode Agent Prompt: What It Signals for Combine and RxSwift, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [AcceptedSE-0502Exclude private initialized properties from memberwise initializer](https://github.com/apple/swift-evolution/blob/main/proposals/0502-exclude-private-from-memberwise-init.md) — Source repository · Topics: Swift · Xcode
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0502Exclude private initialized properties from memberwise initializer. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.

## [Issue 309](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-309)

- Published: `2026-02-03T15:08:20.000Z`

**Topics:** Swift · SwiftUI · Concurrency · Swift Package Manager · Xcode · AI Development

**Sections:** SwiftLee Weekly by Antoine van der Lee · Release every white-label app in one click · The creator of Clawd: "I ship code I don't read"

**Selected links:**
- [Reverse masking in SwiftUI using blend modes](https://livsycode.com/swiftui/reverse-masking-in-swiftui-using-blend-modes) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates reverse masking in SwiftUI with blend modes. Follow it for cutout or spotlight effects, separating compositing behavior from layout and checking rendering cost, color-space assumptions, and accessibility alternatives.
- [Active ReviewSE-0509Software Bill of Materials (SBOM) Generation for Swift Package Manager](https://github.com/apple/swift-evolution/blob/main/proposals/0509-swift-sboms.md) — Source repository · Topics: Swift · Swift Package Manager · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0509Software Bill of Materials (SBOM) Generation for Swift Package Manager. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Swift Bits: Transition vs Transaction](https://antongubarenko.substack.com/p/swift-bits-transition-vs-transaction) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Contrasts SwiftUI transitions, which define insertion and removal effects, with transactions, which carry animation and state-change context. Follow it when an animation behaves unexpectedly because presentation effects and animation configuration were mixed.
- [SwiftUI agent skill](https://github.com/AvdLee/SwiftUI-Agent-Skill/pull/11) — Source repository · Topics: Swift · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for SwiftUI agent skill. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0508Array expression trailing closures](https://github.com/apple/swift-evolution/blob/main/proposals/0508-array-expression-trailing-closures.md) — Source repository · Topics: Swift · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0508Array expression trailing closures. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Designing Swift Errors for an SDK](https://nonstrict.eu/blog/2026/designing-swift-errors-for-an-sdk) — Article · Topics: Swift
  **NeKI brief:** This article covers designing stable, expressive error APIs for Swift SDKs. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.

## [Issue 308](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-308)

- Published: `2026-01-27T15:08:00.000Z`

**Topics:** Swift · SwiftUI · Concurrency · Observation & State Management · Xcode · AI Development

**Sections:** SwiftLee Weekly by Antoine van der Lee · AI App Development: What I Learned in One Month · Transform Your Career with the iOS Lead Essentials — Limited Offer

**Selected links:**
- [The unexpected @Binding side effect](https://swiftunwrap.com/article/binding-side-effect) — Article · Topics: Observation & State Management · Swift
  **NeKI brief:** Presents The unexpected @Binding side effect, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [How to Avoid Double Updates When Filtering SwiftUI TextField Input](https://livsycode.com/swiftui/how-to-avoid-double-updates-when-filtering-swiftui-textfield-input) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains How to Avoid Double Updates When Filtering SwiftUI TextField Input, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [AvdLee/SwiftUI-Agent-Skill](https://github.com/AvdLee/SwiftUI-Agent-Skill) — Source repository · Topics: Swift · SwiftUI
  **NeKI brief:** Describes A SwiftUI agent skill for better code reviews, focusing on practical tool integration and workflow trade-offs. Use it to evaluate reproducibility, trust boundaries, and debugging steps before adopting the approach in an Xcode project.
- [my first Agent Skill on Swift Concurrency](https://github.com/AvdLee/Swift-Concurrency-Agent-Skill) — Source repository · Topics: Swift · Concurrency · SwiftUI
  **NeKI brief:** Provides focused agent guidance for Swift concurrency work. Use it to give coding agents project-relevant rules around isolation, Sendable boundaries, and async tests before they propose or edit concurrent Swift code.

## [Issue 307](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-307)

- Published: `2026-01-20T15:10:47.000Z`

**Topics:** Swift · Concurrency · AI Development · Testing · Xcode · Liquid Glass

**Sections:** SwiftLee Weekly by Antoine van der Lee · Fastlane alternative - Codemagic CLI tools · The Magic Behind UUID() in Swift, How Your App Generates Truly Unique…

**Selected links:**
- [Foundation Models Prompting Guide](https://livsycode.com/best-practices/foundation-models-prompting-guide) — Article · Topics: AI Development
  **NeKI brief:** Provides practical prompting guidance for Apple's Foundation Models. Use it when shaping instructions, output constraints, and context boundaries for on-device generation, then validate behavior across models, locales, and failure cases.
- [Fastlane alternative - Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [The Magic Behind UUID() in Swift, How Your App Generates Truly Unique Identifiers](https://www.swiftdifferently.com/blog/swift/the-magic-behind-uuid-in-swift) — Article · Topics: Swift
  **NeKI brief:** Explains how UUID values are generated in Swift and why they are treated as unique identifiers. Use it when reviewing identifier design, persistence, or collision assumptions in application data.
- [Universal Links At Scale: The Challenges Nobody Talks About](https://albertodebortoli.com/2026/01/15/universal-links-at-scale-the-challenges-nobody-talks-about) — Article · Topics: Testing
  **NeKI brief:** Explains Universal Links At Scale: The Challenges Nobody Talks About, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Swift Compiler Changes the Easy Way](https://www.massicotte.org/blog/compiler-changes-the-easy-way) — Article · Topics: Swift
  **NeKI brief:** Presents Swift Compiler Changes the Easy Way, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Defining custom string interpolation behavior in Swift](https://nilcoalescing.com/blog/DefiningCustomStringInterpolationBehaviorInSwift) — Article · Topics: Swift
  **NeKI brief:** Shows extending Swift string interpolation so domain types can control formatting directly inside literals. Use it when designing readable, type-directed output while keeping conversion logic centralized instead of scattering formatter calls through UI code.
- [Active ReviewSE-0505Delayed Enqueuing for Executors](https://github.com/apple/swift-evolution/blob/main/proposals/0505-delayed-enqueuing.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Returned For RevisionSE-0505Delayed Enqueuing for Executors. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.

## [Issue 306](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-306)

- Published: `2026-01-13T15:06:45.000Z`

**Topics:** Swift · Concurrency · SwiftUI · Testing · Xcode · AI Development

**Sections:** SwiftLee Weekly by Antoine van der Lee · AI Agents That Actually Optimize Your Apps · Understanding Spring Animations in SwiftUI

**Selected links:**
- [Swift Modules and Code/Assets Duplication](https://pfandrade.me/blog/swift-modules-and-codeassets-duplication) — Article · Topics: Swift · Swift Package Manager
  **NeKI brief:** Presents Swift Modules and Code/Assets Duplication, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [my YouTube series on this app](https://youtube.com/playlist?list=PLg4qABgFp_nRYMtGFdXz8sUeXb2IDxdPL&si=Imqah2BEAj-b-WAM) — Video · Topics: Testing
  **NeKI brief:** Provides a SwiftUI learning course playlist covering navigation and related interface patterns. Use it as a structured route through implementations, checking each example against current APIs before adopting its presentation or state-management techniques.
- [Agent Skills explained: Replacing AGENTS.md with reusable AI knowledge](https://www.youtube.com/watch?v=khekVi1PK3o) — Video · Topics: AI Development · Swift
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Understanding Spring Animations in SwiftUI](https://www.createwithswift.com/understanding-spring-animations-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains SwiftUI spring animation parameters and the relationship between motion response and damping. Use it when tuning a transition by observed behavior instead of repeatedly guessing numeric values.
- [Active ReviewSE-0502Exclude private initialized properties from memberwise initializer](https://github.com/apple/swift-evolution/blob/main/proposals/0502-exclude-private-from-memberwise-init.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0502Exclude private initialized properties from memberwise initializer. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [My Beef with the iOS 26 Tab Bar](https://ryanashcraft.com/ios-26-tab-bar-beef) — Article
  **NeKI brief:** Presents My Beef with the iOS 26 Tab Bar, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.

## [Issue 305](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-305)

- Published: `2026-01-06T15:07:32.000Z`

**Topics:** Swift · Concurrency · AI Development · Swift Package Manager · SwiftUI · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · Icon Composer: Transforming an AI-generated icon · Simple Tools for Network Debugging

**Selected links:**
- [Intercepting SwiftUI Sheet Dismissal](https://livsycode.com/swiftui/intercepting-swiftui-sheet-dismissal) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows how to intercept SwiftUI sheet dismissal before allowing a modal flow to close. Follow it for unsaved-edit confirmation and validation, keeping dismissal state, cancellation, and accessibility actions consistent across interactive and programmatic paths.
- [Have LLMs improved for Swift coding in the last 12 months?](https://www.cocoawithlove.com/blog/llms-twelve-months-later.html) — Article · Topics: AI Development · Swift
  **NeKI brief:** Re-tests several hosted and local LLMs on Swift tasks, including prompting an entire app and comparing model-specific behavior. Follow it for qualitative workflow evidence, not a stable benchmark, and reproduce tests on your own codebase.
- [Dimillian/Skills: My Codex Skills](https://github.com/Dimillian/Skills) — Source repository · Topics: AI Development
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Dimillian/Skills: My Codex Skills. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Agent Skills for Codex](https://developers.openai.com/codex/skills) — Article · Topics: AI Development
  **NeKI brief:** Presents Agent Skills for Codex, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Replay](https://nshipster.com/replay) — Article · Topics: Swift · Testing
  **NeKI brief:** Presents Replay, which records HTTP exchanges as HAR files and replays them through URL loading hooks during Swift Testing. The approach keeps networking tests realistic without live servers, while the sensitive-data section makes fixture sanitization part of the design.
- [Versioned Package.swift Files](https://www.massicotte.org/blog/package-swift) — Article · Topics: Swift · Swift Package Manager
  **NeKI brief:** Presents Versioned Package.swift Files, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.

## [Issue 304](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-304)

- Published: `2025-12-30T15:12:31.000Z`

**Topics:** Swift · Swift Package Manager · Xcode · Architecture · Dependency Injection · AI Development

**Sections:** SwiftLee Weekly by Antoine van der Lee · RocketSim: Build iOS apps up to 2x faster with enhanced Xcode Simulator tools · Shipping at Inference-Speed | Peter Steinberger

**Selected links:**
- [Explicit Dependency Injection → Livsy Code](https://livsycode.com/best-practices/explicit-dependency-injection) — Article · Topics: Architecture · Dependency Injection
  **NeKI brief:** Explains explicit dependency injection in Swift and why construction-time wiring improves testability. Use it when removing hidden singletons, defining feature boundaries, and keeping production composition separate from previews and test fixtures.
- [AI (Without the Hype)](https://build.ms/2025/12/24/ai-without-the-hype-ns-spain-2025) — Article · Topics: AI Development
  **NeKI brief:** Presents AI (Without the Hype), focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [How to Find a Winning App Idea (Before You Waste Months Building the Wrong One)](https://www.youtube.com/watch?v=LZWaMmTlw-M) — Video · Topics: AI Development
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Swift Package Manager Mirrors for Local Development](https://kunat.dev/notes/spm-package-mirroring) — Article · Topics: Swift Package Manager · Swift
  **NeKI brief:** Presents Swift Package Manager Mirrors for Local Development, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.

## [Issue 303](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-303)

- Published: `2025-12-23T15:06:56.000Z`

**Topics:** Swift · Concurrency · Xcode · SwiftUI · AI Development · Liquid Glass

**Sections:** SwiftLee Weekly by Antoine van der Lee · RocketSim: Build iOS apps up to 2x faster with enhanced Xcode Simulator tools · SwiftAgents: Langchain but for swift

**Selected links:**
- [SwiftAgents: Langchain but for swift](https://github.com/christopherkarani/SwiftAgents) — Source repository · Topics: Swift · AI Development
  **NeKI brief:** SwiftAgents is a Swift-oriented agent framework inspired by LangChain concepts. Use it to evaluate typed agent orchestration in a Swift project, while scrutinizing tool permissions, memory design, and provider boundaries.
- [How I use Codex GPT 5.2 with Xcode (My complete workflow)](https://www.youtube.com/watch?v=o4iKnSYlhBQ) — Video · Topics: Xcode · AI Development
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Stretchable Header in SwiftUI for Vertical and Horizontal ScrollView → Livsy Code](https://livsycode.com/swiftui/stretchable-header-in-swiftui-for-vertical-and-horizontal-scrollview) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a stretchable SwiftUI header for vertical or horizontal scrolling. Use it when designing elastic hero content, carefully separating scroll geometry from visual state and testing behavior with dynamic type, rotation, and nested gestures.
- [AcceptedSE-0499Support ~Copyable, ~Escapable in simple standard library protocols](https://github.com/apple/swift-evolution/blob/main/proposals/0499-support-non-copyable-simple-protocols.md) — Source repository · Topics: Swift · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0499Support ~Copyable, ~Escapable in simple standard library protocols. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.

## [Issue 302](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-302)

- Published: `2025-12-16T15:09:01.000Z`

**Topics:** Swift · Concurrency · SwiftUI · Xcode · AI Development · Liquid Glass

**Sections:** SwiftLee Weekly by Antoine van der Lee · Fastlane alternative - Codemagic CLI tools · Swift Configuration 1.0 released

**Selected links:**
- [How to avoid retain cycles when working with tasks in Swift](https://tanaschita.com/swift-async-tasks-memory-management) — Article · Topics: Swift · Concurrency
  **NeKI brief:** Explains retain-cycle risks around Task closures and reference ownership. Use it when asynchronous work outlives a view or controller and cancellation, weak capture, or task storage determines whether objects release.
- [Add an inner shadow to a symbol image in SwiftUI](https://nilcoalescing.com/blog/AddAnInnerShadowToASymbolImageInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Creates an inner-shadow effect for SF Symbols in SwiftUI through masking and compositing. Use it when symbol depth needs a controlled visual treatment without replacing scalable system glyphs with raster assets.
- [Understanding scenes for your macOS app](https://www.createwithswift.com/understanding-scenes-for-your-macos-app) — Article · Topics: Swift
  **NeKI brief:** Explains macOS SwiftUI scenes and their role in app windows, settings, menu commands, and lifecycle. Use it when decomposing a desktop app beyond one WindowGroup and assigning each surface its proper scene type.
- [Fastlane alternative - Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.

## [Issue 301](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-301)

- Published: `2025-12-09T15:08:23.000Z`

**Topics:** Swift · SwiftUI · Concurrency · Observation & State Management · Testing · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · Battery life on iOS and the impact of killing apps · Full iOS coverage. Fast

**Selected links:**
- [Organizing SwiftUI Views with TabContent and @TabContentBuilder → Livsy Code](https://livsycode.com/swiftui/organizing-swiftui-views-with-tabcontent-and-tabcontentbuilder) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains organizing SwiftUI tabs with TabContent and TabContentBuilder. Follow it when composing tab configuration declaratively, checking availability and selection state, and preserving clear navigation semantics as tab content grows.
- [Initializing @Observable classes within the SwiftUI hierarchy](https://nilcoalescing.com/blog/InitializingObservableClassesWithinTheSwiftUIHierarchy) — Article · Topics: Swift · SwiftUI · Observation & State Management
  **NeKI brief:** Compares ownership patterns for creating @Observable reference types inside SwiftUI, including state storage and dependency injection. Useful for preventing model recreation when view identity changes.
- [Returned For RevisionSE-0283Tuples Conform to `Equatable`, `Comparable`, and `Hashable`](https://github.com/apple/swift-evolution/blob/main/proposals/0283-tuples-are-equatable-comparable-hashable.md) — Source repository · Topics: Swift · Observation & State Management · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Returned For RevisionSE-0283Tuples Conform to `Equatable`, `Comparable`, and `Hashable`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0501HTML Coverage Report](https://github.com/apple/swift-evolution/blob/main/proposals/0501-swiftpm-html-coverage-report.md) — Source repository · Topics: Swift · Observation & State Management · Swift Package Manager
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0501HTML Coverage Report. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Full iOS coverage. Fast](https://www.qawolf.com/solutions/ios-testing) — Article · Topics: Testing
  **NeKI brief:** Explains Full iOS coverage. Fast, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.

## [Issue 300](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-300)

- Published: `2025-12-02T15:13:04.000Z`

**Topics:** Swift · Xcode · Testing · Swift Package Manager · AI Development · Liquid Glass

**Sections:** SwiftLee Weekly by Antoine van der Lee · The 7 changes I do for every new Xcode project · Full iOS coverage. Fast

**Selected links:**
- [How to access SFSymbols directly in Xcode](https://ohmyswift.com/blog/2025/11/30/how-to-access-sfsymbols-directly-in-xcode) — Article · Topics: Xcode · Swift
  **NeKI brief:** Explains How to access SFSymbols directly in Xcode, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Teaching AI to Read Xcode Builds](https://tuist.dev/blog/2025/11/27/teaching-ai-to-read-xcode-builds) — Article · Topics: Xcode · AI Development
  **NeKI brief:** Presents Teaching AI to Read Xcode Builds, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [The 7 changes I do for every new Xcode project](https://youtu.be/-D_OrL6wALM?si=orRBojhwAbofQore) — Video · Topics: Xcode
  **NeKI brief:** Presents The 7 changes I do for every new Xcode project as a practical video walkthrough or discussion. Use it when visual demonstration, live tooling, or spoken context helps evaluate the technique, then verify APIs and version-specific claims independently.
- [Full iOS coverage. Fast](https://www.qawolf.com/solutions/ios-testing) — Article · Topics: Testing
  **NeKI brief:** Explains Full iOS coverage. Fast, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Understanding the Transferable Protocol in Swift](https://www.createwithswift.com/understanding-the-transferable-protocol-in-swift) — Article · Topics: Swift
  **NeKI brief:** Explains Transferable representations and type-specific export or import formats for system sharing. Useful when designing drag, drop, paste, or share flows that support more than one data representation.
- [Using associated domains alternate mode during development](https://tanaschita.com/ios-associated-domains-alternate-mode) — Article
  **NeKI brief:** Explains alternate associated-domains mode for development and testing. Use it when universal-link or web-credential configuration must point at a non-production environment without changing the application's primary entitlement design.

## [Issue 299](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-299)

- Published: `2025-11-25T15:16:48.000Z`

**Topics:** Swift · Persistence & Synchronisation · Observation & State Management · SwiftData · UIKit · Concurrency

**Sections:** SwiftLee Weekly by Antoine van der Lee · iOS auth eating your time? · Automatic property observation in UIKit with @Observable

**Selected links:**
- [Automatic property observation in UIKit with @Observable](https://nilcoalescing.com/blog/AutomaticPropertyObservationInUIKitWithObservable) — Article · Topics: UIKit · Observation & State Management
  **NeKI brief:** Shows applying @Observable-style automatic property tracking outside SwiftUI, including UIKit. Use it when an imperative UI needs targeted change observation without manually maintaining a broad notification mechanism.
- [iOS auth eating your time?](https://go.clerk.com/sxkDCu7) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Presents iOS auth eating your time?, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [How SwiftData Represents AttributedString in Core Data Storage](https://medium.com/@djalex566/how-swiftdata-represents-attributedstring-in-core-data-storage-69036a4f166a) — Article · Topics: Swift · SwiftData · Persistence & Synchronisation
  **NeKI brief:** Explains How SwiftData Represents AttributedString in Core Data Storage, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Providing a default value in a String interpolation](https://www.swiftwithvincent.com/blog/providing-a-default-value-in-a-string-interpolation) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents Providing a default value in a String interpolation, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Active ReviewSE-0499Support ~Copyable, ~Escapable in simple standard library protocols](https://github.com/apple/swift-evolution/blob/main/proposals/0499-support-non-copyable-simple-protocols.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0499Support ~Copyable, ~Escapable in simple standard library protocols. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [When To Kill A Project](https://blog.jacobstechtavern.com/p/when-to-kill-a-project) — Article
  **NeKI brief:** Discusses signals and decision criteria for ending an app project when its costs, risks, or opportunity trade-offs no longer make sense. Useful as a product-engineering reflection before continuing sunk-cost work or reallocating a small team.

## [Issue 298](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-298)

- Published: `2025-11-18T19:03:17.000Z`

**Topics:** Swift · Concurrency · Performance · Xcode · Architecture · SwiftUI

**Sections:** SwiftLee Weekly by Antoine van der Lee · Try Clerk for Swift · Deep Dive into iMessage - Behind the Making of an Agent

**Selected links:**
- [Approachable Concurrency in Swift 6.2: A Clear Guide](https://youtu.be/y_Qc8cT-O_g?si=W2ExWkL4BbMjT8cH) — Video · Topics: Concurrency · Swift
  **NeKI brief:** Presents Approachable Concurrency in Swift 6.2: A Clear Guide as a practical video walkthrough or discussion. Use it when visual demonstration, live tooling, or spoken context helps evaluate the technique, then verify APIs and version-specific claims independently.
- [How to Build Scalable White-Label iOS Apps: From Multi-Target to Modular Architecture ‣ Swift and Memes](https://swiftandmemes.com/how-to-build-scalable-white-label-ios-apps-from-multi-target-to-modular-architecture) — Article · Topics: Architecture · Swift
  **NeKI brief:** Explains a white-label iOS architecture that evolves from multi-target projects toward modular components. Use it when separating brand configuration from shared features and assessing build, test, and release trade-offs.
- [Task Identity in SwiftUI & Swift Concurrency](https://chris.eidhof.nl/post/swiftui-task-identity) — Article · Topics: Swift · SwiftUI · Concurrency
  **NeKI brief:** Connects SwiftUI view identity and dependency tracking to the lifetime and restart behavior of tasks. Use it when asynchronous work appears to run with stale inputs or at unexpected times.
- [Building Peer-to-Peer Sessions: Advertising and Browsing Devices](https://www.createwithswift.com/building-peer-to-peer-sessions-advertising-and-browsing-devices) — Article · Topics: Swift
  **NeKI brief:** Builds peer-to-peer discovery by advertising and browsing nearby devices. Use it when a local collaboration feature needs session establishment without central infrastructure, while designing identity, invitations, and disconnect handling.
- [ImplementedSE-0495C compatible functions and enums](https://github.com/apple/swift-evolution/blob/main/proposals/0495-cdecl.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0495C compatible functions and enums. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Deep Dive into iMessage - Behind the Making of an Agent](https://fatbobman.com/en/posts/deep-dive-into-imessage) — Article
  **NeKI brief:** Investigates iMessage storage through SQLite and Core Data timestamps, then uses imessage-kit to build an automation agent. The article is a concrete reference for understanding macOS message data boundaries and automation risks.
- [Generating images in Swift using Image Playground](https://swiftwithmajid.com/2025/11/11/generating-images-in-swift-using-image-playground) — Article · Topics: Swift
  **NeKI brief:** Shows generating images through Image Playground from Swift. Use it when designing the app-to-system creation flow, including prompt context, user choice, and availability handling around Apple Intelligence features.

## [Issue 297](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-297)

- Published: `2025-11-11T15:06:31.000Z`

**Topics:** Swift · Concurrency · Performance · Xcode · AI Development · Liquid Glass

**Sections:** SwiftLee Weekly by Antoine van der Lee · Transform Your Career with the iOS Lead Essentials — Black Friday Offer · From Swift to Mojo and high-performance AI Engineering with Chris Lattner

**Selected links:**
- [Transforming AsyncStream with Swift Async Algorithms](https://tanaschita.com/swift-async-algorithms-asyncstream) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Transforms AsyncStream values with Swift Async Algorithms rather than hand-writing stream plumbing. Use it when throttling, combining, or mapping asynchronous events needs clear cancellation and buffering semantics.
- [From Swift to Mojo and high-performance AI Engineering with Chris Lattner](https://newsletter.pragmaticengineer.com/p/from-swift-to-mojo-and-high-performance) — Podcast · Topics: Swift · Performance · AI Development
  **NeKI brief:** Presents From Swift to Mojo and high-performance AI Engineering with Chris Lattner, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [A deep dive into Collections, Sequences, and Iterators in Swift](https://www.donnywals.com/a-deep-dive-into-collections-sequences-and-iterators-in-swift) — Article · Topics: Swift
  **NeKI brief:** Clarifies the relationship between Collection, Sequence, and IteratorProtocol in Swift. Use it when a custom data source needs the right traversal guarantees and you must distinguish single-pass iteration from multi-pass indexed access.
- [ImplementedSE-0497Controlling function definition visibility in clients](https://github.com/apple/swift-evolution/blob/main/proposals/0497-definition-visibility.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0497Controlling function definition visibility in clients. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [One Swift mistake everyone should stop making today](https://www.hackingwithswift.com/articles/280/one-swift-mistake-everyone-should-stop-making-today) — Article · Topics: Swift
  **NeKI brief:** Highlights a recurring Swift design or implementation pitfall through a focused example. Use it as a review prompt for the specific language habit discussed, then confirm it applies to your compiler and codebase context.

## [Issue 296](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-296)

- Published: `2025-11-04T08:02:52.000Z`

**Topics:** Swift · SwiftUI · Concurrency · Testing · AI Development · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · Your exclusive SwiftLee discount ends tonight · Simulator Camera: Test your app without a physical device

**Selected links:**
- [Optimize your app's speed and efficiency](https://www.youtube.com/watch?v=yXAQTIKR8fk) — Video · Topics: AI Development · Performance · Swift
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Text Effects using TextRenderer in SwiftUI](https://www.createwithswift.com/text-effects-using-textrenderer-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents Text Effects using TextRenderer in SwiftUI, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [The Problem With Combine Annotations](https://www.massicotte.org/combine-annotations) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains The Problem With Combine Annotations, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [ScrollView snapping in SwiftUI](https://nilcoalescing.com/blog/ScrollViewSnappingInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Configures SwiftUI scroll target behavior and snapping so items settle at deliberate positions. Useful for carousels and paged content without implementing custom drag-end calculations.

## [Issue 295](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-295)

- Published: `2025-10-28T15:02:32.000Z`

**Topics:** Swift · SwiftUI · Xcode · Performance · Concurrency · Testing

**Sections:** SwiftLee Weekly by Antoine van der Lee · Build performance analysis for speeding up Xcode builds · The best mobile app monitoring product just keeps getting better

**Selected links:**
- [Integrating Device Camera in SwiftUI Apps](https://www.createwithswift.com/integrating-device-camera-in-swiftui-apps) — Article · Topics: Swift · SwiftUI · Testing
  **NeKI brief:** Integrates device-camera capture into a SwiftUI app through an appropriate framework bridge. Use it when a camera feature needs permission flow, capture lifecycle, and image handoff designed explicitly rather than a one-off picker.
- [Build performance analysis for speeding up Xcode builds](https://youtu.be/9L1p0McuThM) — Video · Topics: Performance · Xcode
  **NeKI brief:** Presents Build performance analysis for speeding up Xcode builds as a practical video walkthrough or discussion. Use it when visual demonstration, live tooling, or spoken context helps evaluate the technique, then verify APIs and version-specific claims independently.
- [Custom Progress Indicator with SwiftUI Symbol Effects](https://livsycode.com/swiftui/custom-progress-indicator-with-swiftui-symbol-effects) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents Custom Progress Indicator with SwiftUI Symbol Effects, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [The best mobile app monitoring product just keeps getting better](https://sentry.io/for/swift) — Article · Topics: Swift
  **NeKI brief:** Presents The best mobile app monitoring product just keeps getting better, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Emerge Tools is now a part of Sentry](https://www.emergetools.com/blog/posts/emerge-tools-is-joining-sentry) — Article · Topics: Swift
  **NeKI brief:** Presents Emerge Tools is now a part of Sentry, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Announcing the Swift SDK for Android](https://www.swift.org/blog/nightly-swift-sdk-for-android) — Article · Topics: Swift
  **NeKI brief:** Announces nightly Swift SDK builds for Android. Follow it when experimenting with Swift on Android and tracking toolchain progress, keeping nightly instability, package compatibility, and deployment support explicit in evaluation notes.
- [Open source case study: Listening to our users](https://www.pointfree.co/blog/posts/189-open-source-case-study-listening-to-our-users) — Article · Topics: Persistence & Synchronisation
  **NeKI brief:** Shares Point-Free's open-source case study about listening to users and evolving a product in response. Useful for examining feedback loops, prioritization, and maintainers' communication choices when an Apple-platform library serves a changing community.

## [Issue 294](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-294)

- Published: `2025-10-21T14:13:02.000Z`

**Topics:** Swift · Concurrency · SwiftUI · Architecture · AI Development · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · SwiftUI Architecture: Structure Views for Reusability and Clarity · The best mobile app monitoring product just keeps getting better

**Selected links:**
- [Transforming Glass Views with the glassEffectID in SwiftUI](https://serialcoder.dev/text-tutorials/swiftui/transforming-glass-views-with-the-glasseffectid-modifier-in-swiftui) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Presents Transforming Glass Views with the glassEffectID in SwiftUI, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [SwiftUI Architecture: Structure Views for Reusability and Clarity](https://youtu.be/W05mPR71zaQ) — Video · Topics: Architecture · Swift · SwiftUI
  **NeKI brief:** Presents SwiftUI Architecture: Structure Views for Reusability and Clarity as a practical video walkthrough or discussion. Use it when visual demonstration, live tooling, or spoken context helps evaluate the technique, then verify APIs and version-specific claims independently.
- [The best mobile app monitoring product just keeps getting better](https://sentry.io/for/swift) — Article · Topics: Swift
  **NeKI brief:** Presents The best mobile app monitoring product just keeps getting better, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Emerge Tools is now a part of Sentry](https://www.emergetools.com/blog/posts/emerge-tools-is-joining-sentry) — Article · Topics: Swift
  **NeKI brief:** Presents Emerge Tools is now a part of Sentry, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Replacing Combine's subjects with AsyncStream in Swift](https://tanaschita.com/swift-combine-subjects-vs-asyncstream) — Article · Topics: Swift · Concurrency
  **NeKI brief:** Compares Combine subjects with `AsyncStream`, contrasting multicasting and operator ecosystems with Swift Concurrency's cancellation-aware async iteration. Follow it when migrating event pipelines and deciding whether a stream needs replay, multiple consumers, or structured concurrency.
- [Singletons with Swift Concurrency](https://www.massicotte.org/singletons) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains Singletons with Swift Concurrency, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Active ReviewSE-0497Controlling function definition visibility in clients](https://github.com/apple/swift-evolution/blob/main/proposals/0497-definition-visibility.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0497Controlling function definition visibility in clients. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.

## [Issue 293](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-293)

- Published: `2025-10-14T14:14:22.000Z`

**Topics:** Swift · SwiftUI · AI Development · Concurrency · Persistence & Synchronisation · SwiftData

**Sections:** SwiftLee Weekly by Antoine van der Lee · Why Swift Migration Tooling Matters · The best mobile app monitoring product just keeps getting better

**Selected links:**
- [Building AI features using Foundation Models. Streaming.](https://swiftwithmajid.com/2025/10/08/building-ai-features-using-foundation-models-streaming) — Article · Topics: AI Development · Swift
  **NeKI brief:** Shows how Foundation Models streams partial generated results rather than waiting for one completed response. Use it when designing incremental SwiftUI updates, cancellation behavior, and UI state for model output that arrives over time.
- [Performing search with SwiftData in a SwiftUI app](https://www.createwithswift.com/performing-search-with-swiftdata-in-a-swiftui-app) — Article · Topics: Swift · SwiftData · SwiftUI
  **NeKI brief:** Builds SwiftData search in SwiftUI using predicates and query-driven state. Use it when filtering persisted models and needing search text, sort order, and result updates to remain declarative.
- [AcceptedSE-0491Module selectors for name disambiguation](https://github.com/apple/swift-evolution/blob/main/proposals/0491-module-selectors.md) — Source repository · Topics: Swift · SwiftData · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0491Module selectors for name disambiguation. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [The best mobile app monitoring product just keeps getting better](https://sentry.io/for/swift) — Article · Topics: Swift
  **NeKI brief:** Presents The best mobile app monitoring product just keeps getting better, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Emerge Tools is now a part of Sentry](https://www.emergetools.com/blog/posts/emerge-tools-is-joining-sentry) — Article · Topics: Swift
  **NeKI brief:** Presents Emerge Tools is now a part of Sentry, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [When SwiftUI automatically applies the glass look and when it doesn’t](https://tanaschita.com/swiftui-glass-auto-apply) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains when SwiftUI automatically applies Liquid Glass and when explicit modifiers are required. Useful for diagnosing inconsistent material appearance across containers and platform contexts.
- [Cultivated Task Cancellation](https://macguru.dev/cultivated-task-cancellation) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains Cultivated Task Cancellation, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Why a custom ViewModifier is often useless](https://www.swiftwithvincent.com/blog/why-a-custom-viewmodifier-is-often-useless) — Article · Topics: Swift
  **NeKI brief:** Argues that many custom ViewModifiers add indirection without clarifying behavior, and shows when direct composition is better. Useful for reviewing SwiftUI abstractions against readability, reuse, and discoverable call-site intent.

## [Issue 292](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-292)

- Published: `2025-10-07T14:12:42.000Z`

**Topics:** Swift · Concurrency · SwiftUI · Xcode · Accessibility · AI Development

**Sections:** SwiftLee Weekly by Antoine van der Lee · The 5 biggest mistakes iOS Developers make with async/await · The best mobile app monitoring product just keeps getting better

**Selected links:**
- [Less Janky Placeholders in SwiftUI](https://harshil.net/blog/swiftui-placeholder-jank) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Presents Less Janky Placeholders in SwiftUI, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Avoiding text truncation in SwiftUI with Dynamic Type](https://nilcoalescing.com/blog/AvoidingTextTruncationInSwiftUI) — Article · Topics: Swift · SwiftUI · Accessibility
  **NeKI brief:** Demonstrates detecting and preventing SwiftUI text truncation through layout and typography choices. Useful for resilient localized interfaces where fixed line counts or widths are unsafe.
- [The best mobile app monitoring product just keeps getting better](https://sentry.io/for/swift) — Article · Topics: Swift
  **NeKI brief:** Presents The best mobile app monitoring product just keeps getting better, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Emerge Tools is now a part of Sentry](https://www.emergetools.com/blog/posts/emerge-tools-is-joining-sentry) — Article · Topics: Swift
  **NeKI brief:** Presents Emerge Tools is now a part of Sentry, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [How to install Xcode 26's Metal Toolchain on CI/CD](https://www.polpiella.dev/metal-toolchain-ci-cd) — Article · Topics: Xcode
  **NeKI brief:** Shows provisioning Xcode's Metal toolchain in CI/CD. Use it when a project compiles Metal shaders or GPU code outside a developer machine and a runner must install the matching components reproducibly.
- [Programmatic navigation with navigation destination in SwiftUI](https://www.createwithswift.com/programmatic-navigation-with-navigation-destination-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Uses navigationDestination for state-driven SwiftUI navigation. Use it when routing should be expressed through typed destinations and path state instead of imperative pushes scattered across child views.

## [Issue 291](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-291)

- Published: `2025-09-30T13:58:29.000Z`

**Topics:** Swift · Concurrency · Swift Package Manager · Xcode · Navigation & Deep Linking · Testing

**Sections:** SwiftLee Weekly by Antoine van der Lee · Derived Data: 5 Things iOS Developers Do Wrong · Product for Engineers newsletter

**Selected links:**
- [Structuring universal links in iOS](https://tanaschita.com/swiftui-navigation-universal-links-architecture) — Article · Topics: Architecture · Navigation & Deep Linking · Swift
  **NeKI brief:** Structures universal-link handling around SwiftUI navigation state. Use it when parsing an incoming URL, restoring a scene, and selecting a nested destination must work consistently on cold launch and while running.
- [How to hide a view in a screenshot](https://www.swiftwithvincent.com/blog/how-to-hide-a-view-in-a-screenshot) — Article · Topics: Swift
  **NeKI brief:** Explains How to hide a view in a screenshot, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Active ReviewSE-0495C compatible functions and enums](https://github.com/apple/swift-evolution/blob/main/proposals/0495-cdecl.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0495C compatible functions and enums. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [this tool](https://docs.rocketsim.app/features/hzQMSrSga7BGWvxdNVdwYs/deeplinks-universal-links/mYuk1cx8REK8mbbt4rhvWz) — Article · Topics: Navigation & Deep Linking · Testing
  **NeKI brief:** Explains this tool, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [All about Swift Package Manager Traits](https://theswiftdev.com/2025/all-about-swift-package-manager-traits) — Article · Topics: Swift · Swift Package Manager
  **NeKI brief:** Presents All about Swift Package Manager Traits, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.

## [Issue 290](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-290)

- Published: `2025-09-23T14:09:24.000Z`

**Topics:** Swift · Persistence & Synchronisation · Concurrency · Xcode · SwiftData · SwiftUI

**Sections:** SwiftLee Weekly by Antoine van der Lee · FREE eBook: Improve build times, streamline CI, and test faster. · Kinetics: Tunable, physics-driven motion primitives for SwiftUI.

**Selected links:**
- [ImplementedSE-0482Binary Static Library Dependencies](https://github.com/apple/swift-evolution/blob/main/proposals/0482-swiftpm-static-library-binary-target-non-apple-platforms.md) — Source repository · Topics: Swift · Dependency Injection · Swift Package Manager
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0482Binary Static Library Dependencies. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [SQLiteData 1.0: An alternative to SwiftData with CloudKit sync and sharing](https://www.pointfree.co/blog/posts/184-sqlitedata-1-0-an-alternative-to-swiftdata-with-cloudkit-sync-and-sharing) — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** SQLiteData combines SQLite persistence with CloudKit synchronization and sharing. Use it when SwiftData lacks required deployment or SQL control, while evaluating the operational cost of its sync model.
- [FREE eBook: Improve build times, streamline CI, and test faster.](https://bitrise.io/whitepapers/level-up-your-ios-game-tips-for-speeding-up-your-continuous-integration) — Article · Topics: Testing
  **NeKI brief:** Discusses Save Time on Every Build and Test Run in a public developer resource. Use it to compare the author's concrete workflow and trade-offs with your project constraints, and verify any platform-specific claims against current primary documentation.
- [Kinetics: Tunable, physics-driven motion primitives for SwiftUI.](https://github.com/roberthein/kinetics) — Source repository · Topics: Swift · SwiftUI
  **NeKI brief:** Provides tunable, physics-driven motion primitives for SwiftUI, including configurable springs and dynamics. Useful for experimenting with reusable interactive animations while inspecting API ergonomics, cancellation, and performance in real screens.
- [Active ReviewSE-0493Support `async` calls in `defer` bodies](https://github.com/apple/swift-evolution/blob/main/proposals/0493-defer-async.md) — Source repository · Topics: Swift · Concurrency
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0493Support `async` calls in `defer` bodies. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Swift 6.2 Released](https://www.swift.org/blog/swift-6.2-released) — Article · Topics: Swift
  **NeKI brief:** Swift 6.2's release announcement provides the authoritative overview of language and toolchain changes. Use it to plan adoption boundaries and match compiler behavior to the released version.

## [Issue 289](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-289)

- Published: `2025-09-16T14:09:42.000Z`

**Topics:** Swift · Concurrency · Liquid Glass · Testing · Xcode · AI Development

**Sections:** SwiftLee Weekly by Antoine van der Lee · Introducing Diagnostics: Improved Debugging and User Support · Paywalls Made Easy

**Selected links:**
- [How to disable Liquid Glass](https://www.swiftwithvincent.com/blog/how-to-disable-liquid-glass) — Article · Topics: Liquid Glass · Swift
  **NeKI brief:** Explains How to disable Liquid Glass, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Paywalls Made Easy](https://www.revenuecat.com/feature/paywalls) — Article · Topics: Testing
  **NeKI brief:** Explains Paywalls Made Easy, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [We Need to Talk About Observation](https://jaredsinclair.com/2025/09/10/observation.html) — Article · Topics: Testing
  **NeKI brief:** Explains We Need to Talk About Observation, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Debug crashes in iOS using MetricKit](https://ohmyswift.com/blog/2025/05/09/debug-crashes-in-ios-using-metrickit) — Article · Topics: Swift
  **NeKI brief:** Explains Debug crashes in iOS using MetricKit, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Understanding Live Activities: visual micro-storytelling](https://www.createwithswift.com/understanding-live-activities-visual-micro-storytelling) — Article · Topics: Swift
  **NeKI brief:** Explains Live Activities as a visual storytelling surface driven by timely state updates. Useful for designing concise lock-screen and Dynamic Island experiences without treating them as miniature full screens.
- [Active ReviewSE-0491Module selectors for name disambiguation](https://github.com/apple/swift-evolution/blob/main/proposals/0491-module-selectors.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0491Module selectors for name disambiguation. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.

## [Issue 288](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-288)

- Published: `2025-09-09T18:49:30.000Z`

**Topics:** Swift · Concurrency · SwiftUI · Testing · Xcode · Accessibility

**Sections:** SwiftLee Weekly by Antoine van der Lee · SwiftUI Toggle: A Complete Guide · Simple Tools for Network Debugging

**Selected links:**
- [Using MainActor.assumeIsolated to Solve Legacy API Compatibility Issues with Swift 6](https://fatbobman.com/en/posts/mainactor-assumeisolated) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains how MainActor.assumeIsolated bridges synchronous legacy callbacks to actor-isolated code while preserving Sendable return values. It is useful when Swift 6 diagnostics expose an isolation mismatch that cannot be solved by simply adding async.
- [Active ReviewSE-0490Environment Constrained Shared Libraries](https://github.com/apple/swift-evolution/blob/main/proposals/0490-environment-constrained-shared-libraries.md) — Source repository · Topics: Swift · Concurrency
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Returned For RevisionSE-0490Environment Constrained Shared Libraries. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Handling different iOS versions in a View body](https://swiftui-garden.com/Articles/Handling-different-iOS-versions-in-a-View-body) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents Handling different iOS versions in a View body, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [SwiftUI: Text Color & Concatenation](https://antongubarenko.substack.com/p/swiftui-text-color-and-concatenation) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents SwiftUI: Text Color & Concatenation, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Swift Default Value in String Interpolations](https://useyourloaf.com/blog/swift-default-value-in-string-interpolations) — Article · Topics: Swift
  **NeKI brief:** Shows Swift interpolation defaults that provide fallback text when optional values are absent. Useful for readable diagnostics and localized output without nested nil-coalescing expressions.
- [When should you use an actor?](https://www.massicotte.org/actors) — Article · Topics: Concurrency
  **NeKI brief:** Examines when actors are the right concurrency boundary rather than treating them as a default replacement for every mutable type. Follow it for the trade-offs around isolation, shared state, and choosing a model that makes concurrency easier to reason about.

## [Issue 287](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-287)

- Published: `2025-09-02T14:17:18.000Z`

**Topics:** Swift · Concurrency · Swift Package Manager · Xcode · SwiftUI · AI Development

**Sections:** SwiftLee Weekly by Antoine van der Lee · Fastlane alternative - Codemagic CLI tools · Building a design system at Genius Scan

**Selected links:**
- [Xcode Migrations: From Stone Age to AI Mastery](https://medium.com/qonto-way/xcode-migrations-from-stone-age-to-ai-mastery-d2590657e809) — Article · Topics: Xcode · AI Development
  **NeKI brief:** Explains Xcode Migrations: From Stone Age to AI Mastery, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Debugging Swift Concurrency: "Am I on the Main Actor?" (Not the Main Thread)](https://www.swiftyplace.com/blog/debugging-swift-concurrency) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains how to determine whether Swift code runs on the MainActor rather than merely the main thread. Use it to diagnose isolation mistakes and validate actor assumptions during concurrency debugging.
- [Building a design system at Genius Scan](https://www.swiftbysundell.com/articles/building-a-design-system-at-genius-scan) — Article · Topics: Swift
  **NeKI brief:** Describes building a shared design system with reusable components, tokens, and constraints at Genius Scan. Useful for connecting SwiftUI component reuse to product consistency and team-scale maintenance.
- [Treating Warnings As Errors In Swift Packages](https://useyourloaf.com/blog/treating-warnings-as-errors-in-swift-packages) — Article · Topics: Swift · Swift Package Manager
  **NeKI brief:** Configures Swift Package builds to treat warnings as errors. Use it to keep library quality gates strict, while staging adoption so existing warnings do not block unrelated migration work.
- [Fastlane alternative - Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.

## [Issue 286](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-286)

- Published: `2025-08-26T14:12:25.000Z`

**Topics:** Swift · Concurrency · SwiftUI · Testing · App Intents & System Surfaces · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · Swift Computed Property: Code Examples · Full iOS coverage. Fast

**Selected links:**
- [Open Intent in iOS 26](https://www.swiftjectivec.com/open-intent-additions-ios26-in-appintents) — Article · Topics: App Intents & System Surfaces · Swift
  **NeKI brief:** Presents Open Intent in iOS 26, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Corner concentricity in SwiftUI on iOS 26](https://nilcoalescing.com/blog/ConcentricRectangleInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Introduces ConcentricRectangle for corners that follow the system's concentric geometry. Useful for iOS 26 surfaces that need nested cards and containers to align with platform visual language.
- [ImplementedSE-0460Explicit Specialization](https://github.com/apple/swift-evolution/blob/main/proposals/0460-specialized.md) — Source repository · Topics: Swift · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0460Explicit Specialization. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ImplementedSE-0476Controlling the ABI of a function, initializer, property, or subscript](https://github.com/apple/swift-evolution/blob/main/proposals/0476-abi-attr.md) — Source repository · Topics: Swift · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0476Controlling the ABI of a function, initializer, property, or subscript. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Full iOS coverage. Fast](https://www.qawolf.com/solutions/ios-testing) — Article · Topics: Testing
  **NeKI brief:** Explains Full iOS coverage. Fast, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [SwiftUI WebView](https://troz.net/post/2025/swiftui-webview) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents a concrete implementation of SwiftUI WebView. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.
- [Swift Raw Identifiers](https://useyourloaf.com/blog/swift-raw-identifiers) — Article · Topics: Swift
  **NeKI brief:** Explains Swift raw identifiers for escaping keywords and preserving source names during interoperability. Useful when wrapping generated APIs or legacy declarations without resorting to renamed adapters everywhere.

## [Issue 285](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-285)

- Published: `2025-08-19T14:12:01.000Z`

**Topics:** Swift · Concurrency · Testing · SwiftUI · Persistence & Synchronisation · SwiftData

**Sections:** SwiftLee Weekly by Antoine van der Lee · Property Wrappers in Swift explained with code examples · Accurate iOS testing on real iPhones and iPads

**Selected links:**
- [How to Work with SwiftData in the Background in Swift 6](https://www.natashatherobot.com/p/swiftdata-background-swift-6) — Article · Topics: Swift · SwiftData · Persistence & Synchronisation
  **NeKI brief:** Explains How to Work with SwiftData in the Background in Swift 6, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Why I'm Not Using Xcode 26's AI Chat Integration (And What Could Change My Mind)](https://www.fline.dev/why-im-not-using-xcode-26s-ai-chat-integration-and-what-could-change-my-mind) — Tutorial · Topics: Xcode · AI Development
  **NeKI brief:** Evaluates Xcode 26's AI chat integration through practical workflow limitations and desired improvements. Use it as community perspective when comparing native and external coding-agent setups.
- [How to create a custom reusable toolbar in SwiftUI](https://tanaschita.com/swiftui-reusable-toolbar) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a reusable SwiftUI toolbar component while keeping actions and state explicit. Useful for design systems that need consistent toolbar composition across screens and platforms.
- [WithdrawnSE-0030Property Behaviors](https://github.com/apple/swift-evolution/blob/main/proposals/0030-property-behavior-decls.md) — Source repository · Topics: Swift · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for WithdrawnSE-0030Property Behaviors. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Accurate iOS testing on real iPhones and iPads](https://www.qawolf.com/solutions/ios-testing) — Article · Topics: Testing
  **NeKI brief:** Explains Full iOS coverage. Fast, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.

## [Issue 284](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-284)

- Published: `2025-08-12T18:01:44.000Z`

**Topics:** Swift · Concurrency · Xcode · Testing · SwiftUI · Liquid Glass

**Sections:** SwiftLee Weekly by Antoine van der Lee · Async await in Swift explained with code examples · Faster iOS app releases with automated QA

**Selected links:**
- [Streaming changes with Observations](https://swiftwithmajid.com/2025/07/30/streaming-changes-with-observations) — Article · Topics: Concurrency · Swift · Testing
  **NeKI brief:** Streams Observation changes as asynchronous values. Use it when observation must drive an async workflow outside a view body and cancellation or coalescing behavior needs explicit control.
- [another article](https://useyourloaf.com/blog/swift-observations-asyncsequence-for-state-changes) — Article · Topics: Concurrency · Swift · Testing
  **NeKI brief:** Connects Swift Observation state changes to AsyncSequence consumption. Use it when a task should react to model updates without Combine, while defining lifetime and cancellation ownership.
- [ImplementedSE-0480Warning Control Settings for SwiftPM](https://github.com/apple/swift-evolution/blob/main/proposals/0480-swiftpm-warning-control.md) — Source repository · Topics: Swift · Swift Package Manager · Xcode
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0480Warning Control Settings for SwiftPM. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Define the scroll edge effect style of a scroll view for Liquid Glass](https://www.createwithswift.com/define-the-scroll-edge-effect-style-of-a-scroll-view-for-liquid-glass) — Article · Topics: Liquid Glass · Swift
  **NeKI brief:** Configures scroll-edge effects for Liquid Glass scroll views. Use it when content transitions into system material need deliberate visual treatment rather than inheriting an unsuitable default.
- [SwiftUI for Mac 2025](https://troz.net/post/2025/swiftui-mac-2025) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents SwiftUI for Mac 2025, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Faster iOS app releases with automated QA](https://www.qawolf.com/solutions/ios-testing) — Article · Topics: Testing · AI Development
  **NeKI brief:** Explains Full iOS coverage. Fast, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [@isolated(any)](https://nshipster.com/isolated-any) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains Swift's isolated(any) function parameter for accepting closures whose actor isolation is inferred at the call site. The examples clarify how it can preserve isolation while designing reusable asynchronous APIs.

## [Issue 283](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-283)

- Published: `2025-08-05T17:17:03.000Z`

**Topics:** Swift · Testing · Concurrency · Xcode · AI Development · Liquid Glass

**Sections:** SwiftLee Weekly by Antoine van der Lee · Global actor in Swift Concurrency explained with code examples · Faster iOS app releases with automated QA

**Selected links:**
- [swiftlang/swift-subprocess: Subprocess is a cross-platform package for spawning processes in Swift.](https://github.com/swiftlang/swift-subprocess) — Source repository · Topics: Swift
  **NeKI brief:** swift-subprocess modernizes launching and interacting with child processes through Swift concurrency. Use it for scripts and tools that need structured stdin, stdout, cancellation, and exit-status handling beyond Foundation's older Process API.
- [Faster iOS app releases with automated QA](https://www.qawolf.com/solutions/ios-testing) — Article · Topics: Testing · AI Development
  **NeKI brief:** Explains Full iOS coverage. Fast, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [swiftlang/swift-testing: A modern, expressive testing package for Swift](https://github.com/swiftlang/swift-testing) — Source repository · Topics: Testing · Swift
  **NeKI brief:** Presents a concrete implementation of Swift Testing. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.
- [apple/swift-async-algorithms: Async Algorithms for Swift](https://github.com/apple/swift-async-algorithms) — Source repository · Topics: Concurrency · Swift
  **NeKI brief:** swift-async-algorithms adds reusable asynchronous sequence operators and utilities for Swift concurrency. Use it when async/await code needs throttling, merging, buffering, or other stream composition without reintroducing a full Combine pipeline.

## [Issue 282](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-282)

- Published: `2025-07-29T14:14:45.000Z`

**Topics:** Swift · Concurrency · Core Data · Persistence & Synchronisation · Xcode · AI Development

**Sections:** SwiftLee Weekly by Antoine van der Lee · Combine and Swift Concurrency: A threading risk · Fastlane alternative - Codemagic CLI tools

**Selected links:**
- [GitHub repository](https://github.com/AvdLee/CoreDataBestPractices) — Source repository · Topics: Core Data · Persistence & Synchronisation · Concurrency
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for GitHub repository. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Fastlane alternative - Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [A Peek into My Debugging Process (With Real Examples)](https://www.polpiella.dev/how-i-fix-bugs-in-my-apps) — Article
  **NeKI brief:** Describes an evidence-first bug-fixing workflow that captures reproduction, narrows the failing path, and adds regression coverage. Useful as a practical debugging process rather than a framework recipe.
- [Uncertain⟨T⟩](https://nshipster.com/uncertainty) — Article
  **NeKI brief:** Uses uncertainty as a modeling problem for noisy sensors, locations, and user behavior rather than forcing false precision into scalar values. It is useful when designing APIs that must carry confidence or probabilistic outcomes explicitly.
- [Flux pattern in Swift](https://swiftandpizza.wpcomstaging.com/flux-in-swift) — Article · Topics: Swift
  **NeKI brief:** Presents Flux pattern in Swift, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Deciding between ‘let’ and ‘var’ for Swift struct properties](https://www.swiftbysundell.com/articles/let-vs-var-for-swift-struct-properties) — Article · Topics: Swift
  **NeKI brief:** Examines let versus var properties in Swift structs and how immutability affects mutation and API design. Useful for choosing value semantics deliberately in models and view state.
- [Creating amazing loading animations with SF Symbols.](https://danielsaidi.com/blog/2025/06/19/creating-amazing-loading-animations-with-sf-symbols) — Article
  **NeKI brief:** Creates loading animations from SF Symbols using symbol effects and state-driven timing. Useful for lightweight progress feedback that remains scalable and semantic instead of relying on bespoke raster animation assets.

## [Issue 281](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-281)

- Published: `2025-07-22T14:08:43.000Z`

**Topics:** Swift · Concurrency · Xcode · AI Development · Swift Package Manager · SwiftUI

**Sections:** SwiftLee Weekly by Antoine van der Lee · Threads vs. Tasks in Swift Concurrency · Transform Your Career with the iOS Lead Essentials — Limited Offer

**Selected links:**
- [Approachable Concurrency in Swift Packages](https://useyourloaf.com/blog/approachable-concurrency-in-swift-packages) — Article · Topics: Concurrency · Swift · Swift Package Manager
  **NeKI brief:** Applies approachable concurrency settings to Swift packages and explains how target configuration changes diagnostics. Useful for aligning library and application migration plans.
- [ChatGPT in Xcode 26: there’s a hidden prompt!](https://www.swiftwithvincent.com/blog/chatgpt-in-xcode-26-theres-a-hidden-prompt) — Article · Topics: Xcode · Swift · AI Development
  **NeKI brief:** Presents ChatGPT in Xcode 26: there’s a hidden prompt!, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Giving Claude Code Eyes to See Your SwiftUI Views](https://twocentstudios.com/2025/07/13/giving-claude-code-eyes-to-see-your-swiftui-views) — Article · Topics: Swift · SwiftUI · AI Development
  **NeKI brief:** Presents Giving Claude Code Eyes to See Your SwiftUI Views, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [ImplementedSE-0470Global-actor isolated conformances](https://github.com/apple/swift-evolution/blob/main/proposals/0470-isolated-conformances.md) — Source repository · Topics: Swift · Concurrency
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0470Global-actor isolated conformances. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Icon Composer - Tackling Challenges](https://fatbobman.com/en/posts/icon-composer-tackling-challenges) — Article
  **NeKI brief:** Documents practical Icon Composer issues around SVG imports, monochrome brightness, layer limits, design trade-offs, and final Xcode integration.

## [Issue 280](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-280)

- Published: `2025-07-15T14:13:29.000Z`

**Topics:** Swift · Concurrency · Testing · SwiftUI · Macros & Metaprogramming · App Intents & System Surfaces

**Sections:** SwiftLee Weekly by Antoine van der Lee · Modern Swift Lock: Mutex & the Synchronization Framework · Transform Your Career with the iOS Lead Essentials — Limited Offer

**Selected links:**
- [Confirmation and Result Interactive Snippets](https://www.swiftjectivec.com/app-intents-interactive-snippets-confirm-vs-result) — Article · Topics: Swift · App Intents & System Surfaces
  **NeKI brief:** Presents Confirmation and Result Interactive Snippets, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [this post](https://superwall.com/blog/app-intents-interactive-snippets-in-ios-26) — Article · Topics: App Intents & System Surfaces · Swift
  **NeKI brief:** Presents this post, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Introducing Animatable macro in SwiftUI](https://swiftwithmajid.com/2025/07/08/introducing-animatable-macro-in-swiftui) — Article · Topics: Swift · SwiftUI · Macros & Metaprogramming
  **NeKI brief:** Explains SwiftUI's @Animatable macro as a way to synthesize animatable-data handling for custom views. Use it when complex values should interpolate correctly without maintaining a fragile manual AnimatableData implementation.
- [Four Months in the Making: SwiftMCP 1.0 is Here](https://www.cocoanetics.com/2025/07/four-months-in-the-making-swiftmcp-1-0-is-here) — Article · Topics: AI Development · Swift · Macros & Metaprogramming
  **NeKI brief:** Presents Four Months in the Making: SwiftMCP 1.0 is Here, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Active ReviewSE-0466Control default actor isolation inference](https://github.com/apple/swift-evolution/blob/main/proposals/0466-control-default-actor-isolation.md) — Source repository · Topics: Swift · Concurrency · AI Development
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0466Control default actor isolation inference. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0470Global-actor isolated conformances](https://github.com/apple/swift-evolution/blob/main/proposals/0470-isolated-conformances.md) — Source repository · Topics: Swift · AI Development · Concurrency
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0470Global-actor isolated conformances. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.

## [Issue 279](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-279)

- Published: `2025-07-08T13:08:44.000Z`

**Topics:** Swift · Liquid Glass · Xcode · Concurrency · Performance · AI Development

**Sections:** SwiftLee Weekly by Antoine van der Lee · Paywalls Made Easy – Superwall · Vibe coding in Xcode 26: is it good?

**Selected links:**
- [Vibe coding in Xcode 26: is it good?](https://www.swiftwithvincent.com/blog/vibe-coding-in-xcode-26-is-it-good) — Article · Topics: Xcode · Swift
  **NeKI brief:** Presents Vibe coding in Xcode 26: is it good?, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [ImplementedSE-0464UTF8Span: Safe UTF-8 Processing Over Contiguous Bytes](https://github.com/apple/swift-evolution/blob/main/proposals/0464-utf8span-safe-utf8-processing.md) — Source repository · Topics: Swift · Liquid Glass
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0464UTF8Span: Safe UTF-8 Processing Over Contiguous Bytes. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [The Anatomy of a LiquidGlass Button in iOS 26](https://www.natashatherobot.com/p/liquidglass-button-ios-26) — Article · Topics: Liquid Glass
  **NeKI brief:** Presents The Anatomy of a LiquidGlass Button in iOS 26, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Schedule a countdown timer with AlarmKit](https://nilcoalescing.com/blog/CountdownTimerWithAlarmKit) — Article
  **NeKI brief:** Schedules a countdown through AlarmKit rather than a foreground-only timer. Use it when an app needs a system-managed alert that survives normal lifecycle interruptions.
- [Designing custom UI with Liquid Glass on iOS 26](https://www.donnywals.com/designing-custom-ui-with-liquid-glass-on-ios-26) — Article · Topics: Liquid Glass
  **NeKI brief:** Explores custom Liquid Glass composition on iOS 26, including grouping and material boundaries. Useful for matching the system visual language without treating every translucent surface as interchangeable.

## [Issue 278](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-278)

- Published: `2025-07-01T14:14:53.000Z`

**Topics:** Swift · Concurrency · Xcode · Liquid Glass · Performance · SwiftUI

**Sections:** SwiftLee Weekly by Antoine van der Lee · Sparkle: Distribution apps in- and out of the Mac App Store · Observability that's custom-built for mobile

**Selected links:**
- [Understanding and Improving SwiftUI Performance](https://medium.com/airbnb-engineering/understanding-and-improving-swiftui-performance-37b77ac61896) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Explains Understanding and Improving SwiftUI Performance, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [A Swift Developer’s Guide to Prompt Engineering with Apple’s](https://www.natashatherobot.com/p/swift-prompt-engineering-apples-foundationmodels) — Article · Topics: Swift
  **NeKI brief:** Explains A Swift Developer’s Guide to Prompt Engineering with Apple’s, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [ImplementedSE-0472Starting tasks synchronously from caller context](https://github.com/apple/swift-evolution/blob/main/proposals/0472-task-start-synchronously-on-caller-context.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0472Starting tasks synchronously from caller context. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [RocketSim's documentation](https://docs.rocketsim.app/features/hzQMSrSga7BGWvxdNVdwYs/simulator-camera-support/58tQ5jvevLNSnyUEA7VgAv) — Article · Topics: Xcode
  **NeKI brief:** Presents RocketSim's documentation, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.

## [Issue 277](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-277)

- Published: `2025-06-24T14:09:23.000Z`

**Topics:** Swift · Xcode · Macros & Metaprogramming · Liquid Glass · SwiftUI · AI Development

**Sections:** SwiftLee Weekly by Antoine van der Lee · #Playground Macro: Running Code Snippets in Xcode’s canvas · Paywalls Made Easy – Superwall

**Selected links:**
- [Reverse-Engineering Xcode's Coding Intelligence prompt](https://peterfriese.dev/blog/2025/reveng-xcode-coding-intelligence) — Article · Topics: Xcode · AI Development
  **NeKI brief:** Inspects Xcode's Coding Intelligence prompt to show how project context and instructions shape generated code. The reverse-engineering perspective helps teams reason about agent inputs and reproducibility while avoiding assumptions about undocumented internals.
- [Exploring a new visual language: Liquid Glass](https://www.createwithswift.com/exploring-a-new-visual-language-liquid-glass) — Article · Topics: Swift · Liquid Glass
  **NeKI brief:** Explores Liquid Glass as a new Apple visual language. Use it when evaluating material, hierarchy, and interaction changes before adapting an existing interface to the system design.
- [Adding Icon Composer icons to Xcode](https://useyourloaf.com/blog/adding-icon-composer-icons-to-xcode) — Article · Topics: Xcode
  **NeKI brief:** Shows importing Icon Composer output into Xcode asset workflows. Use it when app-icon variants need a repeatable handoff from design composition to a buildable asset catalog.
- [read all about it inside the documentation](https://docs.rocketsim.app/features/hzQMSrSga7BGWvxdNVdwYs/simulator-camera-support/58tQ5jvevLNSnyUEA7VgAv) — Article
  **NeKI brief:** Presents RocketSim's documentation, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.

## [Issue 276](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-276)

- Published: `2025-06-17T14:10:56.000Z`

**Topics:** Swift · Concurrency · UIKit · App Intents & System Surfaces · Persistence & Synchronisation · SwiftData

**Sections:** SwiftLee Weekly by Antoine van der Lee · Default Actor Isolation in Swift 6.2 · Want to Stay Ahead in Mobile CI/CD?

**Selected links:**
- [Free Episode: SwiftData versus SQL Query Builder](https://www.pointfree.co/blog/posts/174-free-episode-swiftdata-versus-sql-query-builder) — Article · Topics: Swift · SwiftData · Persistence & Synchronisation
  **NeKI brief:** Compares SwiftData with a SQL query-builder approach. Use it when choosing between declarative model persistence and explicit relational queries, migrations, and database-level control.
- [ImplementedSE-0468`Hashable` conformance for `Async(Throwing)Stream.Continuation`](https://github.com/apple/swift-evolution/blob/main/proposals/0468-async-stream-continuation-hashable-conformance.md) — Source repository · Topics: Swift · Concurrency · UIKit
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0468`Hashable` conformance for `Async(Throwing)Stream.Continuation`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ImplementedSE-0456Add `Span`-providing Properties to Standard Library Types](https://github.com/apple/swift-evolution/blob/main/proposals/0456-stdlib-span-properties.md) — Source repository · Topics: Swift · UIKit
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0456Add `Span`-providing Properties to Standard Library Types. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ImplementedSE-0465Standard Library Primitives for Nonescapable Types](https://github.com/apple/swift-evolution/blob/main/proposals/0465-nonescapable-stdlib-primitives.md) — Source repository · Topics: Swift · UIKit
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0465Standard Library Primitives for Nonescapable Types. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [WWDC 2025: What's new for the Apple community?](https://www.createwithswift.com/wwdc-2025-whats-new-for-the-apple-community) — Article · Topics: Swift
  **NeKI brief:** Surveys WWDC 2025 changes across Liquid Glass, Icon Composer, accessibility, Apple Intelligence, Xcode, Swift, and SwiftUI. Use the cross-topic index to identify follow-up implementation areas, then consult authoritative session documentation.
- [iOS 26: Notable UIKit Additions](https://www.swiftjectivec.com/ios-26-notable-uikit-additions) — Article · Topics: UIKit · Swift
  **NeKI brief:** Surveys notable UIKit additions in iOS 26 and their practical use cases. Useful as a versioned API index when maintaining UIKit screens alongside SwiftUI migration work.

## [Issue 275](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-275)

- Published: `2025-06-12T15:03:23.000Z`

**Topics:** Swift · SwiftUI · Concurrency · Liquid Glass · UIKit · Testing

**Sections:** SwiftLee Weekly by Antoine van der Lee · @concurrent explained with code examples · Capture, Debug, and Optimize Your HTTP(s) Traffic in One App

**Selected links:**
- [Crafting Liquid Glass app icons with Icon Composer](https://www.createwithswift.com/crafting-liquid-glass-app-icons-with-icon-composer) — Article · Topics: Liquid Glass · Swift
  **NeKI brief:** Walks through creating Liquid Glass-compatible app icons with Icon Composer. Use it when adapting assets for the new system treatment and validating how layers, materials, and icon output render in context.
- [Developer experience wins from WWDC25](https://tuist.dev/blog/2025/06/10/wwdc) — Article · Topics: Testing · Macros & Metaprogramming
  **NeKI brief:** Explains Developer experience wins from WWDC25, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Introducing PickerKit for SwiftUI](https://danielsaidi.com/blog/2025/06/10/introducing-pickerkit-for-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents Introducing PickerKit for SwiftUI, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Automatic Observation Tracking in UIKit and AppKit: The Feature Apple Forgot to Mention | Peter Steinberger](https://steipete.me/posts/2025/automatic-observation-tracking-uikit-appkit) — Article · Topics: UIKit
  **NeKI brief:** Explores automatic Observation tracking in UIKit and AppKit. Use it when imperative views should react to observable model reads without manually registering broad notifications.

## [Issue 274](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-274)

- Published: `2025-06-03T14:11:29.000Z`

**Topics:** Swift · SwiftUI · Architecture · Macros & Metaprogramming · Performance · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · Unique values in Swift: Removing duplicates from an array · Fastlane alternative - Codemagic CLI tools

**Selected links:**
- [Tips and tricks for when using SwiftUI’s ViewBuilder](https://www.swiftbysundell.com/articles/swiftui-viewbuilder-tips-and-tricks) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Collects ViewBuilder techniques for conditional composition, custom containers, and readable APIs. Useful when designing result-builder-based components without hiding state or type constraints.
- [Automatic SwiftUI View Tracing with Swift Macros](https://medium.com/@alexandercohen/how-we-built-a-swift-macro-that-automatically-wraps-any-swiftui-view-no-more-manual-f5761376f923) — Article · Topics: Swift · Macros & Metaprogramming · SwiftUI
  **NeKI brief:** Presents Automatic SwiftUI View Tracing with Swift Macros, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Microapps architecture in Swift. Scaling.](https://swiftwithmajid.com/2025/05/27/microapps-architecture-in-swift-scaling) — Article · Topics: Swift · Architecture
  **NeKI brief:** Discusses scaling a Swift microapps architecture through modular feature boundaries. Use it when a growing app needs independently developed flows without turning every module dependency into global coupling.
- [Fastlane alternative - Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [Accessorise Your Context Menu Interactions](https://sebvidal.com/blog/accessorise-your-context-menu-interactions) — Article
  **NeKI brief:** Presents Accessorise Your Context Menu Interactions, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.

## [Issue 273](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-273)

- Published: `2025-05-27T14:08:19.000Z`

**Topics:** Swift · Xcode · Testing · AI Development · Dependency Injection · Liquid Glass

**Sections:** SwiftLee Weekly by Antoine van der Lee · Billing Grace Period Explained: How It Works and Why It Matters · Tired of chaotic mobile releases?

**Selected links:**
- [AcceptedSE-0482Binary Static Library Dependencies](https://github.com/apple/swift-evolution/blob/main/proposals/0482-swiftpm-static-library-binary-target-non-apple-platforms.md) — Source repository · Topics: Swift · Dependency Injection · Swift Package Manager
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0482Binary Static Library Dependencies. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Returned For RevisionSE-0480Warning Control Settings for SwiftPM](https://github.com/apple/swift-evolution/blob/main/proposals/0480-swiftpm-warning-control.md) — Source repository · Topics: Swift · Swift Package Manager
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0480Warning Control Settings for SwiftPM. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [W.W.D.C. 2025: The Pregame Quiz](https://www.swiftjectivec.com/wwdc-2025-the-pregame-quiz) — Article · Topics: Swift
  **NeKI brief:** Presents W.W.D.C. 2025: The Pregame Quiz, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Build an iOS app faster than ever with xtool](https://dimillian.medium.com/build-an-ios-app-faster-than-ever-with-xtool-d6dd7780c5f7) — Article · Topics: Xcode
  **NeKI brief:** Presents Build an iOS app faster than ever with xtool, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [AcceptedSE-0472Starting tasks synchronously from caller context](https://github.com/apple/swift-evolution/blob/main/proposals/0472-task-start-synchronously-on-caller-context.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0472Starting tasks synchronously from caller context. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.

## [Issue 272](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-272)

- Published: `2025-05-20T14:12:58.000Z`

**Topics:** Swift · SwiftUI · Testing · Concurrency · Observation & State Management · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · Institutional Purchases: Understanding and Detecting · Fastlane alternative - Codemagic CLI tools

**Selected links:**
- [SE-475: Transactional Observation of Values](https://github.com/swiftlang/swift-evolution/blob/main/proposals/0475-observed.md) — Source repository · Topics: Swift · Observation & State Management · SwiftUI
  **NeKI brief:** Provides the public source repository for SE-0475. Inspect its implementation, examples, and issue history to evaluate integration boundaries and maintenance trade-offs before depending on it in an Apple-platform project.
- [Demystifying SwiftUI’s .ignoredByLayout() — How to Apply Geometry Effects Without Breaking Your Layout](https://fatbobman.com/en/posts/demystifying-swiftuis-ignoredbylayout) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains how ignoredByLayout removes a view from layout participation while retaining rendering or interaction implications. Useful for distinguishing hidden geometry from conditional rendering when composing overlays and transitions.
- [Testing Remote Push Notifications with iOS Simulators](https://www.tiagohenriques.dev/blog/testing-push-notifications-ios-simulators) — Article · Topics: Testing · Xcode
  **NeKI brief:** Explains Testing Remote Push Notifications with iOS Simulators, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [AcceptedSE-0471Improved Custom SerialExecutor isolation checking for Concurrency Runtime](https://github.com/apple/swift-evolution/blob/main/proposals/0471-SerialExecutor-isIsolated.md) — Source repository · Topics: Swift · Testing · Concurrency
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0471Improved Custom SerialExecutor isolation checking for Concurrency Runtime. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Apple's open-sourced Async Algorithms framework](https://github.com/apple/swift-async-algorithms) — Source repository · Topics: Concurrency · Swift · Observation & State Management
  **NeKI brief:** swift-async-algorithms adds reusable asynchronous sequence operators and utilities for Swift concurrency. Use it when async/await code needs throttling, merging, buffering, or other stream composition without reintroducing a full Combine pipeline.
- [Optimized mathematical computations in Swift](https://swiftwithmajid.com/2025/05/13/optimized-mathematical-computations-in-swift) — Article · Topics: Swift
  **NeKI brief:** Explores optimization techniques for mathematical work in Swift. Use it when profiling identifies numeric hot paths and algorithm, memory layout, or vectorization decisions need measured comparison.
- [Default isolation with Swift 6.2](https://www.massicotte.org/default-isolation-swift-6_2) — Article · Topics: Swift · Concurrency
  **NeKI brief:** Explains Default isolation with Swift 6.2, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [SwiftUI Picker With Optional Selection](https://useyourloaf.com/blog/swiftui-picker-with-optional-selection) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows binding a SwiftUI Picker to an optional selection. Use it when no current choice is a valid state and placeholder, tag, and model values must remain type-consistent.
- [AcceptedSE-0481`weak let`](https://github.com/apple/swift-evolution/blob/main/proposals/0481-weak-let.md) — Source repository · Topics: Swift · Testing
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0481`weak let`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Fastlane alternative - Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.

## [Issue 271](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-271)

- Published: `2025-05-13T09:07:48.000Z`

**Topics:** Swift · Testing · Concurrency · AI Development · SwiftUI · Navigation & Deep Linking

**Sections:** SwiftLee Weekly by Antoine van der Lee · Universal Links implementation on iOS · Is Your Mobile CI/CD Pipeline Secure Enough?

**Selected links:**
- [Concurrency-Safe Testing in Swift 6.1 with @TaskLocal and Test Scoping](https://www.mobiledevdiary.com/posts/concurency-safe-testing-in-swift-6-1) — Article · Topics: Testing · Swift · Concurrency
  **NeKI brief:** Explains Concurrency-Safe Testing in Swift 6.1 with @TaskLocal and Test Scoping, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [ImplementedSE-0461Run nonisolated async functions on the caller's actor by default](https://github.com/apple/swift-evolution/blob/main/proposals/0461-async-function-isolation.md) — Source repository · Topics: Concurrency · Swift · Testing
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0461Run nonisolated async functions on the caller's actor by default. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Start a free 14-day trial ->](https://teams.rocketsim.app/signup/trial) — Tutorial · Topics: Swift · Concurrency
  **NeKI brief:** Introduces Start a free 14-day trial -> as a developer resource or service relevant to Swift and Apple-platform work. Use it to assess the stated workflow or offering, checking scope, pricing, access requirements, and technical fit before relying on it.
- [Can You use PreferenceKeys for Testing SwiftUI Views](https://www.swiftyplace.com/blog/swiftui-testing-with-preferencekeys) — Article · Topics: Testing · Swift · SwiftUI
  **NeKI brief:** Investigates whether PreferenceKeys can expose SwiftUI layout information to tests. Useful for understanding testability limits and deciding when a semantic UI assertion is preferable to measuring implementation details.
- [Using Model Context Protocol in iOS apps](https://www.artemnovichkov.com/blog/using-model-context-protocol-in-ios-apps) — Article · Topics: AI Development
  **NeKI brief:** Explores using Model Context Protocol from an iOS app. Follow it when assessing tool or resource integrations, keeping transport, trust, privacy, and user-consent boundaries explicit before exposing app data to external agents.
- [What's new in Swift 6.2?](https://www.hackingwithswift.com/articles/277/whats-new-in-swift-6-2) — Article · Topics: Swift · Concurrency
  **NeKI brief:** Summarizes Swift 6.2 additions and concurrency ergonomics, highlighting practical changes for existing projects. Useful for planning an incremental toolchain update and targeted experiments.

## [Issue 270](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-270)

- Published: `2025-05-06T14:02:39.000Z`

**Topics:** Swift · Testing · Dependency Injection · Swift Package Manager · Xcode · AI Development

**Sections:** SwiftLee Weekly by Antoine van der Lee · Testing push notifications on the iOS simulator · Are You Overlooking Mobile CI/CD Security?

**Selected links:**
- [Adding dependencies to binary Swift packages](https://danielsaidi.com/blog/2025/05/02/adding-dependencies-to-binary-swift-packages) — Article · Topics: Dependency Injection · Swift · Swift Package Manager
  **NeKI brief:** Presents Adding dependencies to binary Swift packages, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Active ReviewSE-0482Binary Static Library Dependencies](https://github.com/apple/swift-evolution/blob/main/proposals/0482-swiftpm-static-library-binary-target-non-apple-platforms.md) — Source repository · Topics: Swift · Dependency Injection · Swift Package Manager
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0482Binary Static Library Dependencies. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Building Better Apps with RocketSim - Special Guest Antoine van der Lee!](https://www.youtube.com/live/4MtostISJTY?feature=shared) — Video
  **NeKI brief:** Presents Building Better Apps with RocketSim - Special Guest Antoine van der Lee! as a practical video walkthrough or discussion. Use it when visual demonstration, live tooling, or spoken context helps evaluate the technique, then verify APIs and version-specific claims independently.
- [Applying to, prepping for, and speaking at Deep Dish Swift](https://jacobzivandesign.com/technology/preparing-my-first-talk) — Article · Topics: Swift
  **NeKI brief:** Presents Applying to, prepping for, and speaking at Deep Dish Swift, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Dependency container on top of task local values in Swift](https://swiftwithmajid.com/2025/04/30/dependency-container-on-top-of-task-local-values-in-swift) — Article · Topics: Swift
  **NeKI brief:** Builds a dependency container using TaskLocal values. Use it when async call chains need contextual dependencies without passing parameters everywhere, while guarding scope and inheritance carefully.
- [AcceptedSE-0476Controlling the ABI of a function, initializer, property, or subscript](https://github.com/apple/swift-evolution/blob/main/proposals/0476-abi-attr.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0476Controlling the ABI of a function, initializer, property, or subscript. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0481`weak let`](https://github.com/apple/swift-evolution/blob/main/proposals/0481-weak-let.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0481`weak let`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.

## [Issue 269](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-269)

- Published: `2025-04-29T14:18:33.000Z`

**Topics:** Swift · SwiftUI · Performance · Concurrency · Xcode · AI Development

**Sections:** SwiftLee Weekly by Antoine van der Lee · SwiftUI ForEach Explained with Code Examples · What's the cost of not prioritizing mobile release management?

**Selected links:**
- [ImplementedSE-0463Import Objective-C completion handler parameters as `@Sendable`](https://github.com/apple/swift-evolution/blob/main/proposals/0463-sendable-completion-handlers.md) — Source repository · Topics: Swift · Concurrency
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0463Import Objective-C completion handler parameters as `@Sendable`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ImplementedSE-0466Control default actor isolation inference](https://github.com/apple/swift-evolution/blob/main/proposals/0466-control-default-actor-isolation.md) — Source repository · Topics: Swift · Concurrency
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0466Control default actor isolation inference. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Drawing symbols with Canvas](https://www.createwithswift.com/drawing-symbols-with-canvas) — Article · Topics: Swift · SwiftUI · Performance
  **NeKI brief:** Draws SF Symbols with SwiftUI Canvas. Use it when symbol rendering needs custom transforms, compositing, or animation while retaining vector fidelity and system icon semantics.
- [ImplementedSE-0457Expose attosecond representation of `Duration`](https://github.com/apple/swift-evolution/blob/main/proposals/0457-duration-attosecond-represenation.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0457Expose attosecond representation of `Duration`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ImplementedSE-0462Task Priority Escalation APIs](https://github.com/apple/swift-evolution/blob/main/proposals/0462-task-priority-escalation-apis.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0462Task Priority Escalation APIs. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0480Warning Control Settings for SwiftPM](https://github.com/apple/swift-evolution/blob/main/proposals/0480-swiftpm-warning-control.md) — Source repository · Topics: Swift · Swift Package Manager
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0480Warning Control Settings for SwiftPM. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.

## [Issue 268](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-268)

- Published: `2025-04-22T13:40:18.000Z`

**Topics:** Swift · Concurrency · AI Development · Xcode · Testing · Liquid Glass

**Sections:** SwiftLee Weekly by Antoine van der Lee · Swift 6.2: A first look at how it’s changing Concurrency · Transform Your Career with the iOS Lead Essentials — Limited Offer

**Selected links:**
- [Creating MCP Servers in Swift](https://www.artemnovichkov.com/blog/creating-mcp-servers-in-swift) — Article · Topics: Swift · AI Development
  **NeKI brief:** Presents Creating MCP Servers in Swift, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [swiftlang/swift-subprocess: Subprocess is a cross-platform package for spawning processes in Swift.](https://github.com/swiftlang/swift-subprocess) — Source repository · Topics: Swift · Concurrency
  **NeKI brief:** swift-subprocess modernizes launching and interacting with child processes through Swift concurrency. Use it for scripts and tools that need structured stdin, stdout, cancellation, and exit-status handling beyond Foundation's older Process API.
- [ImplementedSE-0470Global-actor isolated conformances](https://github.com/apple/swift-evolution/blob/main/proposals/0470-isolated-conformances.md) — Source repository · Topics: Swift · Concurrency
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0470Global-actor isolated conformances. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [a starting point in the repository's readme](https://github.com/swiftlang/swift/tree/release/6.2?tab=readme-ov-file) — Source repository · Topics: Swift · Xcode
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for a starting point in the repository's readme. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Using Swift’s defer keyword within async and throwing contexts](https://www.swiftbysundell.com/articles/using-defer-within-async-and-throwing-contexts) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains defer cleanup across async suspension and thrown errors. Use it when file handles, transactions, or temporary state must release reliably without duplicating cleanup paths.
- [Returned For RevisionSE-0472Starting tasks synchronously from caller context](https://github.com/apple/swift-evolution/blob/main/proposals/0472-task-start-synchronously-on-caller-context.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0472Starting tasks synchronously from caller context. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.

## [Issue 267](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-267)

- Published: `2025-04-15T13:04:41.000Z`

**Topics:** Swift · SwiftUI · Concurrency · Xcode · AI Development · Liquid Glass

**Sections:** SwiftLee Weekly by Antoine van der Lee · Swift Reduce: Combining elements into a single value · Codemagic makes Apple M2 machines available, even on the free tier!

**Selected links:**
- [Create flexible interfaces in SwiftUI](https://www.createwithswift.com/create-flexible-interfaces-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds flexible SwiftUI interfaces that adapt to available space and content. Use it when a layout must remain usable across devices without branching into separate fixed-size view trees.
- [AcceptedSE-0470Global-actor isolated conformances](https://github.com/apple/swift-evolution/blob/main/proposals/0470-isolated-conformances.md) — Source repository · Topics: Swift · Concurrency
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0470Global-actor isolated conformances. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Using NavigationPath with TabView in SwiftUI](https://tanaschita.com/swiftui-navigation-path-with-tabview) — Article · Topics: Swift · SwiftUI · Navigation & Deep Linking
  **NeKI brief:** Uses NavigationPath with TabView to preserve typed navigation state per tab. Use it when deep links and tab switching must restore the correct nested destination.
- [AcceptedSE-0464UTF8Span: Safe UTF-8 Processing Over Contiguous Bytes](https://github.com/apple/swift-evolution/blob/main/proposals/0464-utf8span-safe-utf8-processing.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0464UTF8Span: Safe UTF-8 Processing Over Contiguous Bytes. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0476Controlling the ABI of a function, initializer, property, or subscript](https://github.com/apple/swift-evolution/blob/main/proposals/0476-abi-attr.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0476Controlling the ABI of a function, initializer, property, or subscript. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Supercharging SwiftUI Text with Dynamic Content Styling](https://danielsaidi.com/blog/2025/04/08/supercharging-swiftui-text-with-dynamic-content-styling) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents Supercharging SwiftUI Text with Dynamic Content Styling, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Building Better Apps with RocketSim - Special Guest Antoine van der Lee!](https://www.youtube.com/live/4MtostISJTY?feature=shared) — Video
  **NeKI brief:** Presents Building Better Apps with RocketSim - Special Guest Antoine van der Lee! as a practical video walkthrough or discussion. Use it when visual demonstration, live tooling, or spoken context helps evaluate the technique, then verify APIs and version-specific claims independently.
- [How to inspect .ipa files and secure your iOS app from common mistakes](https://www.artemnovichkov.com/blog/how-to-inspect-ipa-files) — Article
  **NeKI brief:** Shows how to inspect an IPA archive for packaging details and common security mistakes. Use it during release audits to examine embedded assets, metadata, and bundled resources before distribution.

## [Issue 266](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-266)

- Published: `2025-04-08T14:10:02.000Z`

**Topics:** Swift · SwiftUI · Concurrency · Testing · Xcode · AI Development

**Sections:** SwiftLee Weekly by Antoine van der Lee · SwiftUI Alert Guide + Code Examples · Transform Your Career with the iOS Lead Essentials — Limited Offer

**Selected links:**
- [Building a Business on Swift on the Server, Vapor & Open Source - Tim Condon](https://share.transistor.fm/s/941efac7) — Tutorial · Topics: Swift · Concurrency
  **NeKI brief:** Discusses building a business around server-side Swift, Vapor, and open source in an interview format. Use it for ecosystem and product context rather than as API documentation or implementation guidance.
- [Say Goodbye to dismiss - A State-Driven Path to More Maintainable SwiftUI](https://fatbobman.com/en/posts/say-goodbye-to-dismiss) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Reframes SwiftUI dismissal as state-driven navigation. Use it when child views imperatively dismiss themselves and ownership of presentation state becomes hard to test or reason about.
- [AcceptedSE-0461Run nonisolated async functions on the caller's actor by default](https://github.com/apple/swift-evolution/blob/main/proposals/0461-async-function-isolation.md) — Source repository · Topics: Swift · Concurrency · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0461Run nonisolated async functions on the caller's actor by default. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [AcceptedSE-0468`Hashable` conformance for `Async(Throwing)Stream.Continuation`](https://github.com/apple/swift-evolution/blob/main/proposals/0468-async-stream-continuation-hashable-conformance.md) — Source repository · Topics: Swift · Concurrency · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0468`Hashable` conformance for `Async(Throwing)Stream.Continuation`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [New in Swift 6.1: Test Scoping Traits](https://www.pointfree.co/blog/posts/169-new-in-swift-6-1-test-scoping-traits) — Article · Topics: Testing · Swift
  **NeKI brief:** Explains Swift 6.1 Test Scoping Traits as a mechanism for controlling test context before and after execution. Use it when suite-level fixtures must remain isolated under concurrent Swift Testing runs.
- [Text concatenation vs Text interpolation in SwiftUI](https://nilcoalescing.com/blog/TextConcatenationVsTextInterpolationInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Contrasts concatenating Text views with interpolating values into localized strings. Useful for preserving localization and formatting semantics when constructing styled SwiftUI copy.
- [Structuring Spacing for Scalable Mobile UIs](https://www.mobilesystemdesign.com/blog/design-system-spacing) — Article
  **NeKI brief:** Discusses spacing tokens and rhythm as foundations of a mobile design system. Useful for translating visual rules into reusable SwiftUI layout constants instead of accumulating screen-specific padding values.

## [Issue 265](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-265)

- Published: `2025-04-01T14:13:42.000Z`

**Topics:** Swift · SwiftUI · Xcode · Architecture · Concurrency · Persistence & Synchronisation

**Sections:** SwiftLee Weekly by Antoine van der Lee · SwiftUI Grid, LazyVGrid, LazyHGrid Explained with Code Examples · Discover the Top 10 Best Practices in App Distribution

**Selected links:**
- [Swiftdata Architecture Patterns And Practices](https://azamsharp.com/2025/03/28/swiftdata-architecture-patterns-and-practices.html) — Article · Topics: Architecture · Swift · SwiftData
  **NeKI brief:** Explains Swiftdata Architecture Patterns And Practices, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [AcceptedSE-0466Control default actor isolation inference](https://github.com/apple/swift-evolution/blob/main/proposals/0466-control-default-actor-isolation.md) — Source repository · Topics: Swift · Concurrency · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0466Control default actor isolation inference. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0471Improved Custom SerialExecutor isolation checking for Concurrency Runtime](https://github.com/apple/swift-evolution/blob/main/proposals/0471-SerialExecutor-isIsolated.md) — Source repository · Topics: Swift · Concurrency · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0471Improved Custom SerialExecutor isolation checking for Concurrency Runtime. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [an official release article](https://www.swift.org/blog/swift-6.1-released) — Article · Topics: Swift · AI Development · Xcode
  **NeKI brief:** Summarizes the Swift 6.1 release and its ecosystem changes. Use it as a starting point for compiler or package upgrades, verifying source compatibility, concurrency diagnostics, and platform support against the toolchain you actually ship.
- [See SWT-0007](https://github.com/swiftlang/swift-evolution/blob/main/proposals/testing/0007-test-scoping-traits.md) — Source repository · Topics: Testing · Swift · AI Development
  **NeKI brief:** Proposes Swift Testing scoping traits that use TaskLocal context to establish isolated setup and teardown behavior. Follow it when async tests need predictable per-test environment control without global mutable configuration.
- [Active ReviewSE-0472Starting tasks synchronously from caller context](https://github.com/apple/swift-evolution/blob/main/proposals/0472-task-start-synchronously-on-caller-context.md) — Source repository · Topics: Swift · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0472Starting tasks synchronously from caller context. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [the vision document](https://github.com/swiftlang/swift-evolution/blob/main/visions/approachable-concurrency.md) — Source repository · Topics: Swift · Concurrency · AI Development
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for the vision document. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Method dispatch mechanisms in Swift: static and dynamic dispatch](https://nilcoalescing.com/blog/MethodDispatchMechanismsInSwift) — Article · Topics: Swift · Performance
  **NeKI brief:** Contrasts static and dynamic Swift dispatch mechanisms. Use it when protocol requirements, extensions, class inheritance, or generics produce a method call that resolves differently than expected.
- [SwiftUI Environment - Concepts and Practice](https://fatbobman.com/en/posts/swiftui-environment-concepts-and-practice) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains SwiftUI Environment as dependency propagation and value lookup. Use it when shared configuration or services need scoped injection without threading parameters through every intermediate view.
- [first article](https://www.swiftbysundell.com/articles/modern-url-construction-in-swift) — Article · Topics: Swift
  **NeKI brief:** Builds URLs with modern Foundation components rather than string concatenation. Use it when paths, query items, and percent encoding must remain correct under optional or user-provided values.

## [Issue 264](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-264)

- Published: `2025-03-25T15:06:57.000Z`

**Topics:** Swift · Testing · Concurrency · SwiftUI · Xcode · AI Development

**Sections:** SwiftLee Weekly by Antoine van der Lee · SwiftUI TabView: Explained with Code Examples · Capture, Debug, and Optimize Your HTTP(s) Traffic in One App

**Selected links:**
- [ModelActor is Just Weird](https://www.massicotte.org/model-actor) — Article · Topics: Concurrency · Swift · SwiftData
  **NeKI brief:** Explains ModelActor is Just Weird, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Detecting body poses in a live video feed](https://www.createwithswift.com/detecting-body-poses-in-a-live-video-feed) — Article · Topics: Swift
  **NeKI brief:** Detects body poses from a live video feed with Vision. Use it when real-time camera analysis needs a clear pipeline from captured frames through inference to UI updates.
- [ImplementedSE-0444Member import visibility](https://github.com/apple/swift-evolution/blob/main/proposals/0444-member-import-visibility.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0444Member import visibility. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [SwiftUI Default Scroll Anchor](https://useyourloaf.com/blog/swiftui-default-scroll-anchor) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Configures a default scroll anchor so newly inserted or resized content settles at a chosen edge. Useful for chat and feed layouts where preserving the visible context matters.
- [Active ReviewSE-0470Global-actor isolated conformances](https://github.com/apple/swift-evolution/blob/main/proposals/0470-isolated-conformances.md) — Source repository · Topics: Swift · Concurrency
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0470Global-actor isolated conformances. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Why I Avoid Group](https://chris.eidhof.nl/post/why-i-avoid-group) — Article
  **NeKI brief:** Investigates why SwiftUI's Group can produce surprising behavior by examining variadic views and view lists. Use it to reason about view structure before adding Group as a seemingly neutral wrapper.

## [Issue 263](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-263)

- Published: `2025-03-18T15:01:58.000Z`

**Topics:** Swift · Concurrency · SwiftUI · Navigation & Deep Linking · Persistence & Synchronisation · SwiftData

**Sections:** SwiftLee Weekly by Antoine van der Lee · Swift Concurrency Course: Modern Concurrency & Swift 6 · Codemagic makes Apple M2 machines available, even on the free tier!

**Selected links:**
- [ImplementedSE-0451Raw identifiers](https://github.com/apple/swift-evolution/blob/main/proposals/0451-escaped-identifiers.md) — Source repository · Topics: Swift · Concurrency · Navigation & Deep Linking
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0451Raw identifiers. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [AcceptedSE-0462Task Priority Escalation APIs](https://github.com/apple/swift-evolution/blob/main/proposals/0462-task-priority-escalation-apis.md) — Source repository · Topics: Swift · Concurrency · Navigation & Deep Linking
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0462Task Priority Escalation APIs. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Exploring The LabeledContent View In SwiftUI](https://serialcoder.dev/text-tutorials/swiftui/exploring-the-labeledcontent-view-in-swiftui) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Explores LabeledContent for pairing values with descriptive labels in SwiftUI. Useful for settings, metadata, and inspector rows that need consistent semantics and platform styling without hand-built HStacks.
- [Key Considerations Before Using SwiftData](https://fatbobman.com/en/posts/key-considerations-before-using-swiftdata) — Article · Topics: Swift · SwiftData · Persistence & Synchronisation
  **NeKI brief:** Evaluates SwiftData's practical limits before adoption. Use it when deciding whether its model, migration, query, or synchronization behavior fits a production persistence requirement.
- [Refactoring my SwiftUI Navigation Layer to follow the Coordinator Pattern](https://www.tiagohenriques.dev/blog/swiftui-refactor-navigation-layer-using-coordinator-pattern) — Article · Topics: Swift · SwiftUI · Concurrency
  **NeKI brief:** Refactors a SwiftUI navigation layer toward the Coordinator pattern, separating route orchestration from views. Useful for deep-link handling and feature composition when NavigationStack state is spreading across screens.
- [AcceptedSE-0463Import Objective-C completion handler parameters as `@Sendable`](https://github.com/apple/swift-evolution/blob/main/proposals/0463-sendable-completion-handlers.md) — Source repository · Topics: Swift · Concurrency · Navigation & Deep Linking
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0463Import Objective-C completion handler parameters as `@Sendable`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0468`Hashable` conformance for `Async(Throwing)Stream.Continuation`](https://github.com/apple/swift-evolution/blob/main/proposals/0468-async-stream-continuation-hashable-conformance.md) — Source repository · Topics: Swift · Concurrency · Navigation & Deep Linking
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0468`Hashable` conformance for `Async(Throwing)Stream.Continuation`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [one of the latest vision documents](https://github.com/swiftlang/swift-evolution/blob/main/visions/approachable-concurrency.md) — Source repository · Topics: Swift · Concurrency · Testing
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for the vision document. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Understanding structural identity in SwiftUI](https://tanaschita.com/swiftui-structural-identity) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains how SwiftUI uses view type and hierarchy position as structural identity to decide what persists and redraws. Follow it when conditional branches unexpectedly reset state or trigger more updates than expected.
- [Identifying individual sounds in an audio file](https://www.createwithswift.com/identifying-individual-sounds-in-an-audio-file) — Article · Topics: Swift
  **NeKI brief:** Identifies individual sounds in audio with Apple's analysis frameworks. Use it when an app must classify or segment recorded media and route time-ranged results into a user-facing workflow.

## [Issue 262](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-262)

- Published: `2025-03-11T15:01:20.000Z`

**Topics:** Swift · SwiftUI · App Intents & System Surfaces · Concurrency · Observation & State Management · Performance

**Sections:** SwiftLee Weekly by Antoine van der Lee · Picker in SwiftUI explained with code examples · Paywalls Made Easy – Superwall

**Selected links:**
- [Rendering Pixel Art with SwiftUI](https://twocentstudios.com/2025/03/10/pixel-art-swift-ui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents Rendering Pixel Art with SwiftUI, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Creating App Intents using Assistant Schemas](https://www.createwithswift.com/creating-app-intents-using-assistant-schemas) — Article · Topics: App Intents & System Surfaces · Swift
  **NeKI brief:** Uses @AssistantSchema to declare App Intents that can integrate with system and Apple Intelligence experiences. Follow it when deciding how intent parameters and metadata should expose an existing feature without duplicating business logic.
- [Lazy Initialization @State in SwiftUI - Overcoming Premature Object Creation](https://fatbobman.com/en/posts/lazy-initialization-state-in-swiftui) — Article · Topics: Swift · SwiftUI · Observation & State Management
  **NeKI brief:** Explains lazy @State initialization for avoiding premature object construction. Use it when a state-owned object is expensive or depends on inputs that should be captured only at the correct lifecycle point.
- [Synchronous Work](https://www.massicotte.org/synchronous-work) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains Synchronous Work, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Active ReviewSE-0466Control default actor isolation inference](https://github.com/apple/swift-evolution/blob/main/proposals/0466-control-default-actor-isolation.md) — Source repository · Topics: Swift · Concurrency
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0466Control default actor isolation inference. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0464UTF8Span: Safe UTF-8 Processing Over Contiguous Bytes](https://github.com/apple/swift-evolution/blob/main/proposals/0464-utf8span-safe-utf8-processing.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0464UTF8Span: Safe UTF-8 Processing Over Contiguous Bytes. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0465Standard Library Primitives for Nonescapable Types](https://github.com/apple/swift-evolution/blob/main/proposals/0465-nonescapable-stdlib-primitives.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0465Standard Library Primitives for Nonescapable Types. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.

## [Issue 261](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-261)

- Published: `2025-03-04T15:16:50.000Z`

**Topics:** Swift · Concurrency · SwiftUI · Performance · Xcode · AI Development

**Sections:** SwiftLee Weekly by Antoine van der Lee · What is Structured Concurrency? · Webinar alert: Want to ship more code faster for iOS?

**Selected links:**
- [Symmetrical and asymmetrical transitions in SwiftUI with the Scroll Transition modifier](https://www.createwithswift.com/symmetrical-and-asymmetrical-transitions-in-swiftui-with-the-scroll-transition-modifier) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Applies scrollTransition with symmetric or asymmetric phases to animate content entering and leaving a scroll view. Useful for controlled motion tied to visibility rather than arbitrary timers.
- [Animatable Protocol - Taming Unruly SwiftUI Animations](https://fatbobman.com/en/posts/animatable-protocol-taming-unruly-swiftui-animation) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Uses Animatable to control interpolation of custom SwiftUI values. Use it when a complex view animates discontinuously and needs a deliberate animatable-data representation.
- [Designing a custom lazy list in SwiftUI with better performance](https://nilcoalescing.com/blog/CustomLazyListInSwiftUI) — Article · Topics: Swift · SwiftUI · Performance
  **NeKI brief:** Constructs a custom lazy list to control virtualization and layout beyond List's built-in behavior. Useful when custom scrolling visuals or cell composition require more control than standard list styles provide.
- [Safer Swift: How ~Copyable Prevents Hidden Bugs](https://arturgruchala.com/safer-swift-how-copyable-prevents-hidden-bugs) — Article · Topics: Swift
  **NeKI brief:** Explains Safer Swift: How ~Copyable Prevents Hidden Bugs, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [ImplementedSE-0458Opt-in Strict Memory Safety Checking](https://github.com/apple/swift-evolution/blob/main/proposals/0458-strict-memory-safety.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0458Opt-in Strict Memory Safety Checking. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0463Import Objective-C completion handler parameters as `@Sendable`](https://github.com/apple/swift-evolution/blob/main/proposals/0463-sendable-completion-handlers.md) — Source repository · Topics: Swift · Concurrency
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0463Import Objective-C completion handler parameters as `@Sendable`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.

## [Issue 260](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-260)

- Published: `2025-02-25T15:03:14.000Z`

**Topics:** Swift · Concurrency · SwiftUI · Xcode · AI Development · Liquid Glass

**Sections:** SwiftLee Weekly by Antoine van der Lee · Task.sleep() vs. Task.yield(): The differences explained · Codemagic makes Apple M2 machines available, even on the free tier!

**Selected links:**
- [Tapping on Stack Views](https://useyourloaf.com/blog/tapping-on-stack-views) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains why tapping empty space in a SwiftUI stack may not trigger a gesture and how contentShape changes hit testing. Useful for reliable row and card interactions.
- [Quick guide on home screen quick actions for SwiftUI](https://tanaschita.com/ios-home-screen-quick-actions) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Implements Home Screen quick actions in SwiftUI. Use it when a shortcut should launch directly into an app task while keeping scene activation and routing state explicit.
- [How Swift's server support powers Things Cloud](https://www.swift.org/blog/how-swifts-server-support-powers-things-cloud) — Article · Topics: Swift
  **NeKI brief:** Explains How Swift's server support powers Things Cloud, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [RocketSim for Teams](https://www.rocketsim.app/team-insights) — Article · Topics: Swift
  **NeKI brief:** Presents RocketSim for Teams, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Things](https://culturedcode.com/things) — Article · Topics: Swift
  **NeKI brief:** Things is a polished task-management app for Mac, iPhone, and iPad, organized around planning, projects, and daily actions. Use it as a product reference when evaluating information hierarchy, cross-device workflows, and the interaction quality expected from native productivity software.
- [Active ReviewSE-0462Task Priority Escalation APIs](https://github.com/apple/swift-evolution/blob/main/proposals/0462-task-priority-escalation-apis.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0462Task Priority Escalation APIs. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [New Concurrency Stuff with 6.1](https://www.massicotte.org/concurrency-6_1) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains New Concurrency Stuff with 6.1, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Active ReviewSE-0461Run nonisolated async functions on the caller's actor by default](https://github.com/apple/swift-evolution/blob/main/proposals/0461-async-function-isolation.md) — Source repository · Topics: Concurrency · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0461Run nonisolated async functions on the caller's actor by default. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [AcceptedSE-0456Add `Span`-providing Properties to Standard Library Types](https://github.com/apple/swift-evolution/blob/main/proposals/0456-stdlib-span-properties.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0456Add `Span`-providing Properties to Standard Library Types. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.

## [Issue 259](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-259)

- Published: `2025-02-18T15:10:59.000Z`

**Topics:** Swift · SwiftUI · Xcode · AI Development · Concurrency · Testing

**Sections:** SwiftLee Weekly by Antoine van der Lee · Swift 6: What’s New and How to Migrate · Master Mobile Monitoring SwiftUI Apps

**Selected links:**
- [Master Mobile Monitoring SwiftUI Apps](https://www.datadoghq.com/resources/mobile-monitoring-best-practices-b) — Article · Topics: Swift · SwiftUI · Performance
  **NeKI brief:** Presents Master Mobile Monitoring SwiftUI Apps, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [AcceptedSE-0453InlineArray, a fixed-size array](https://github.com/apple/swift-evolution/blob/main/proposals/0453-vector.md) — Source repository · Topics: Swift · AI Development · Xcode
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0453InlineArray, a fixed-size array. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Apple has open-sourced Swift's build system](https://www.swiftwithvincent.com/blog/apple-has-open-sourced-swifts-build-system) — Article · Topics: Swift · Testing
  **NeKI brief:** Explains Apple has open-sourced Swift's build system, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Presenting and Managing Expandable Sections in SwiftUI](https://serialcoder.dev/text-tutorials/swiftui/presenting-and-managing-expandable-sections-in-swiftui) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Builds expandable SwiftUI sections with disclosure state and animated content. Useful for settings and FAQ interfaces where row identity, accessibility labels, and collapsed content behavior must remain consistent.
- [Build a macOS menu bar utility in SwiftUI](https://nilcoalescing.com/blog/BuildAMacOSMenuBarUtilityInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Walks through a SwiftUI macOS menu-bar utility, including scene configuration and status-item presentation. Useful for small persistent tools that should avoid a conventional document window.
- [Mastering SwiftUI Scrolling - Implementing Custom Paging](https://fatbobman.com/en/posts/mastering-swiftui-scrolling-implementing-custom-paging) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Implements custom SwiftUI paging behavior for scrolling content. Use it when system paging is insufficient and snapping, offsets, and selection state require coordinated control.

## [Issue 258](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-258)

- Published: `2025-02-11T15:02:09.000Z`

**Topics:** Swift · SwiftUI · Xcode · AI Development · Liquid Glass · Performance

**Sections:** SwiftLee Weekly by Antoine van der Lee · How to develop an app for iOS · Master Mobile Monitoring SwiftUI Apps

**Selected links:**
- [Master Mobile Monitoring SwiftUI Apps](https://www.datadoghq.com/resources/mobile-monitoring-best-practices-b) — Article · Topics: Swift · SwiftUI · Performance
  **NeKI brief:** Presents Master Mobile Monitoring SwiftUI Apps, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Implementing Face ID authentication in SwiftUI](https://tanaschita.com/ios-local-authentication) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Integrates LocalAuthentication for Face ID or Touch ID in SwiftUI. Use it when sensitive actions need a platform authentication gate and clear fallback/error handling.
- [ImplementedSE-0450Package traits](https://github.com/apple/swift-evolution/blob/main/proposals/0450-swiftpm-package-traits.md) — Source repository · Topics: Swift · Swift Package Manager
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0450Package traits. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [The 7 Habits of Highly Effective People by Stephen Covey](https://amzn.to/46uww4e) — Article · Topics: Swift
  **NeKI brief:** Recommends The 7 Habits of Highly Effective People as a personal productivity reference for developers. Use its principles to reflect on prioritization, communication, and sustainable work habits, while adapting general advice to software-team realities.
- [SwiftUI - Navigation View If Needed](https://www.joshholtz.com/blog/2025/02/08/swiftui-navigation-view-if-needed.html) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents SwiftUI - Navigation View If Needed, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Grouping Controls with ControlGroup](https://www.createwithswift.com/grouping-controls-with-controlgroup) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Uses ControlGroup to semantically group related SwiftUI controls. Use it when command clusters need platform-adaptive presentation without manually reproducing toolbar or menu styling.
- [Provisional Authorization of User Notificatons](https://useyourloaf.com/blog/provisional-authorization-of-user-notificatons) — Article
  **NeKI brief:** Explains provisional notification authorization, which delivers quietly before a full permission prompt. Use it when an app can demonstrate notification value without interrupting first-run onboarding.

## [Issue 257](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-257)

- Published: `2025-02-04T14:26:37.000Z`

**Topics:** Swift · Testing · SwiftUI · Xcode · AI Development · Liquid Glass

**Sections:** SwiftLee Weekly by Antoine van der Lee · Parameterized tests in Swift: Reducing boilerplate code · FREE iOS Architect Crash Course for a limited time!

**Selected links:**
- [The Next Chapter in Swift Build Technologies](https://www.swift.org/blog/the-next-chapter-in-swift-build-technologies) — Article · Topics: Swift · Xcode
  **NeKI brief:** Discusses the direction of Swift build technologies and tooling. Use it for ecosystem context when planning build-system work, but keep implementation decisions grounded in the current Swift Package Manager and Xcode documentation.
- [Swift Build](https://github.com/swiftlang/swift-build) — Source repository · Topics: Swift · Xcode
  **NeKI brief:** Swift Build is the open-sourced build engine behind Xcode and SwiftPM convergence work. Follow it when assessing build-graph architecture, toolchain behavior, and future migration implications for projects that currently rely on opaque Xcode builds.
- [Container relative frames in SwiftUI](https://swiftwithmajid.com/2025/01/28/container-relative-frames-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Uses container-relative frames to size SwiftUI content from its enclosing container. Use it when adaptive grids, cards, or paged layouts need proportional sizing without GeometryReader plumbing.
- [Drawing maps with Swift Charts](https://www.artemnovichkov.com/blog/drawing-maps-with-swift-charts) — Article · Topics: Swift
  **NeKI brief:** Uses Swift Charts to draw map-like visualizations from coordinate data. Useful for plotting paths or geographic series when a chart is sufficient and a full map renderer would add unnecessary complexity.
- [AcceptedSE-0457Expose attosecond representation of `Duration`](https://github.com/apple/swift-evolution/blob/main/proposals/0457-duration-attosecond-represenation.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0457Expose attosecond representation of `Duration`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0460Explicit Specialization](https://github.com/apple/swift-evolution/blob/main/proposals/0460-specialized.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0460Explicit Specialization. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Advantages of Using withAnimation](https://www.magnuskahr.dk/posts/2025/01/advantage-of-withAnimation) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Compares value-driven animation modifiers with explicit withAnimation blocks and explains where the latter gives clearer control. Follow it when an interaction changes several pieces of state and the animation scope should be obvious at the mutation site.

## [Issue 256](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-256)

- Published: `2025-01-28T15:11:34.000Z`

**Topics:** Swift · SwiftUI · Networking · Testing · Xcode · Accessibility

**Sections:** SwiftLee Weekly by Antoine van der Lee · Network Link Conditioner: Simulating Slow Networking · Paywalls Made Easy – Superwall

**Selected links:**
- [Creating a reusable action menu component in SwiftUI](https://peterfriese.dev/blog/2025/swiftui-action-menu) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a reusable SwiftUI action menu with a view builder and sheet presentation, turning a one-off menu into a component with an explicit content contract. Follow it for composition patterns, not as a substitute for platform menu guidance.
- [Reducing Motion of Animations](https://useyourloaf.com/blog/reducing-motion-of-animations) — Article · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Shows respecting Reduce Motion preferences in animated interfaces. Use it when custom transitions or effects need an accessible reduced-motion alternative rather than assuming animation is always appropriate.
- [Debugging An Undebuggable App](https://bryce.co/undebuggable) — Article · Topics: Dependency Injection
  **NeKI brief:** Explains Debugging An Undebuggable App, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [AcceptedSE-0454Custom Allocator for Toolchain](https://github.com/apple/swift-evolution/blob/main/proposals/0454-memory-allocator.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0454Custom Allocator for Toolchain. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Color mixing in SwiftUI](https://swiftwithmajid.com/2025/01/21/color-mixing-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains SwiftUI color mixing for creating derived colors. Use it when an interface needs controlled interpolation between semantic colors while preserving dynamic appearance behavior.

## [Issue 255](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-255)

- Published: `2025-01-21T15:04:24.000Z`

**Topics:** Swift · AI Development · App Intents & System Surfaces · SwiftUI · Concurrency · Testing

**Sections:** SwiftLee Weekly by Antoine van der Lee · RocketSim 13 - Network Speed Control · Master Mobile Monitoring SwiftUI Apps

**Selected links:**
- [Master Mobile Monitoring SwiftUI Apps](https://www.datadoghq.com/resources/mobile-monitoring-best-practices-b) — Article · Topics: Swift · SwiftUI · Performance
  **NeKI brief:** Presents Master Mobile Monitoring SwiftUI Apps, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Active ReviewSE-0456Add `Span`-providing Properties to Standard Library Types](https://github.com/apple/swift-evolution/blob/main/proposals/0456-stdlib-span-properties.md) — Source repository · Topics: Swift · AI Development · App Intents & System Surfaces
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0456Add `Span`-providing Properties to Standard Library Types. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0457Expose attosecond representation of `Duration`](https://github.com/apple/swift-evolution/blob/main/proposals/0457-duration-attosecond-represenation.md) — Source repository · Topics: Swift · AI Development · App Intents & System Surfaces
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0457Expose attosecond representation of `Duration`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0458Opt-in Strict Memory Safety Checking](https://github.com/apple/swift-evolution/blob/main/proposals/0458-strict-memory-safety.md) — Source repository · Topics: Swift · AI Development · App Intents & System Surfaces
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0458Opt-in Strict Memory Safety Checking. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [How to use cryptographic hash functions in CryptoKit for iOS security](https://tanaschita.com/swift-hash-functions) — Article · Topics: Swift
  **NeKI brief:** Uses CryptoKit hash functions for integrity and security-related fingerprints. Use it when comparing data or deriving stable digests, while distinguishing hashing from reversible encryption.
- [Getting started with creative coding using Swift and SwiftUI](https://www.createwithswift.com/getting-started-with-creative-coding-using-swift-and-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Introduces creative coding with SwiftUI through generative visual experiments. Use it when exploring Canvas, animation, and mathematical drawing techniques outside conventional interface constraints.

## [Issue 254](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-254)

- Published: `2025-01-14T14:03:25.000Z`

**Topics:** Swift · SwiftUI · Observation & State Management · Navigation & Deep Linking · Networking · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · SwiftUI Lists: Present rows of data explained with code examples · Build Crash-Free iOS Apps

**Selected links:**
- [iPhone Apps 101 - SwiftUI App Development Course](https://paulsolt.teachable.com/p/iphoneapps101?affcode=1123_hyqyixcy) — Tutorial · Topics: Swift · SwiftUI · Networking
  **NeKI brief:** Introduces iPhone Apps 101 - SwiftUI App Development Course as a developer resource or service relevant to Swift and Apple-platform work. Use it to assess the stated workflow or offering, checking scope, pricing, access requirements, and technical fit before relying on it.
- [Active ReviewSE-0455SwiftPM @testable build setting](https://github.com/apple/swift-evolution/blob/main/proposals/0455-swiftpm-testable-build-setting.md) — Source repository · Topics: Swift · Testing · Swift Package Manager
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0455SwiftPM @testable build setting. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Creating a debounced search context for performant SwiftUI searches](https://danielsaidi.com/blog/2025/01/08/creating-a-debounced-search-context-for-performant-swiftui-searches) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents Creating a debounced search context for performant SwiftUI searches, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [This article from The Pragmatic Engineer](https://newsletter.pragmaticengineer.com/p/how-ai-will-change-software-engineering) — Article · Topics: AI Development · Swift
  **NeKI brief:** Presents This article from The Pragmatic Engineer, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [SwiftUI Navigation using the Router Pattern](https://tiagohenriques.vercel.app/blog/swiftui-navigation-router-pattern) — Article · Topics: Swift · SwiftUI · Navigation & Deep Linking
  **NeKI brief:** Implements a router pattern for SwiftUI navigation with centralized route decisions. Useful for making deep links, modal presentation, and navigation tests deterministic while keeping views focused on rendering.
- [Using withObservationTracking to monitor changes in @Observable properties outside SwiftUI views](https://www.polpiella.dev/observable-outside-of-a-view) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Uses withObservationTracking to observe @Observable changes outside SwiftUI views. Use it when an imperative coordinator or service needs dependency-aware callbacks without adopting Combine.
- [Build Crash-Free iOS Apps](https://www.datadoghq.com/resources/mobile-monitoring-best-practices-b) — Article · Topics: Performance
  **NeKI brief:** Presents Master Mobile Monitoring SwiftUI Apps, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Handle plurals in SwiftUI Text views with inflection](https://nilcoalescing.com/blog/HandlePluralsInSwiftUITextViewsWithInflection) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Uses SwiftUI text inflection to select plural forms from localized strings. Useful for grammatical counts that must adapt to locale without embedding English-only singular/plural conditionals.
- [Active ReviewSE-0454Custom Allocator for Toolchain](https://github.com/apple/swift-evolution/blob/main/proposals/0454-memory-allocator.md) — Source repository · Topics: Swift · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0454Custom Allocator for Toolchain. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.

## [Issue 253](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-253)

- Published: `2025-01-07T13:02:49.000Z`

**Topics:** Swift · SwiftUI · Testing · Xcode · Accessibility · AI Development

**Sections:** SwiftLee Weekly by Antoine van der Lee · iOS App Development: How to get started? · FREE iOS Architect Crash Course for a limited time!

**Selected links:**
- [How one new Xcode feature helped my work project to remove 66,000 lines of code](https://blog.makwanbk.com/how-one-new-xcode-feature-helped-my-work-project-eliminate-66k-lines-of-code) — Article · Topics: Xcode · Swift
  **NeKI brief:** Describes how an Xcode feature removed substantial generated or repetitive code from a production project. Use it to identify automation opportunities while checking the migration cost and generated-source boundaries.
- [Customizing macOS window background in SwiftUI](https://nilcoalescing.com/blog/CustomizingMacOSWindowBackgroundInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows how to customize a macOS SwiftUI window background while respecting the hosting window boundary. Useful for translucent or branded surfaces that cannot be achieved with view modifiers alone.
- [Accessibility That Fits](https://khanlou.com/2024/12/accessibility-that-fits) — Article · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Discusses fitting accessibility behavior into existing interfaces without treating it as a late checklist. Useful for reviewing SwiftUI labels, traits, Dynamic Type, and interaction alternatives as part of component design.
- [Getting started with UI Testing for SwiftUI](https://tanaschita.com/testing-ui-swiftui-xctest-framework) — Article · Topics: Testing · Swift · SwiftUI
  **NeKI brief:** Demonstrates UI testing SwiftUI applications with XCTest, including accessibility-driven queries and interaction assertions. Useful for testing user-visible behavior without coupling tests to implementation details.
- [How to keep your macOS app's menu bar item running after quitting the app](https://www.polpiella.dev/keep-menu-bar-running-after-quitting-app) — Article
  **NeKI brief:** Explains keeping a macOS menu-bar utility available after closing ordinary windows. Use it when separating an app's activation policy, status item, and termination behavior.

## [Issue 252](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-252)

- Published: `2024-12-31T13:36:11.000Z`

**Topics:** Swift · Concurrency · Observation & State Management · Testing · SwiftUI · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · SwiftLee in 2024: Lessons learned and achievements · Screenshotbot: Scale up your snapshot tests, without the friction

**NeKI brief:** Reviews SwiftLee’s 2024 lessons and achievements, then points to practical Swift and SwiftUI explainers covering async/await, MainActor, Sendable, ViewBuilder, and state-object choices. The issue pairs retrospective context with concrete concurrency, observation, and testing-oriented reading for Apple-platform developers.

## [Issue 251](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-251)

- Published: `2024-12-23T10:34:05.000Z`

**Topics:** Swift · SwiftUI · Accessibility · Xcode · Navigation & Deep Linking · AI Development

**Sections:** SwiftLee Weekly by Antoine van der Lee · Swift Tutorials: Learn Swift with Easy-to-Follow Code Examples · Codemagic makes Apple M2 machines available, even on the free tier!

**Selected links:**
- [Creating a SwiftUI text view with tappable links](https://danielsaidi.com/blog/2024/12/18/creating-a-swiftui-text-view-with-tappable-links) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents Creating a SwiftUI text view with tappable links, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [From Icon to Identity: The Essentials of Branding Your App](https://www.createwithswift.com/from-icon-to-identity-the-essentials-of-branding-your-app) — Article · Topics: Swift
  **NeKI brief:** Explains how app branding connects icon design, visual language, and user experience to recognition and trust. Useful when aligning product identity across launch assets and in-app surfaces without treating an icon as an isolated graphic.
- [VoiceOver on macOS: First Time, Huh?](https://www.basbroek.nl/macos-voiceover-first-time-huh) — Article · Topics: Accessibility
  **NeKI brief:** Presents VoiceOver on macOS: First Time, Huh?, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Local Xcode Build Duration insights for your whole team](https://www.rocketsim.app/team-insights) — Article · Topics: Xcode
  **NeKI brief:** Presents RocketSim for Teams, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Adjust the intensity of colors in SwiftUI views](https://nilcoalescing.com/blog/AdjustTheIntensityOfColorsInSwiftUIViews) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Adjusts SwiftUI color intensity with platform-aware rendering controls. Use it when a design needs subtle emphasis changes without replacing semantic colors with fixed, inaccessible values.
- [AcceptedSE-0450Package traits](https://github.com/apple/swift-evolution/blob/main/proposals/0450-swiftpm-package-traits.md) — Source repository · Topics: Swift · Swift Package Manager
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0450Package traits. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.

## [Issue 250](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-250)

- Published: `2024-12-17T10:30:53.000Z`

**Topics:** Swift · SwiftUI · Xcode · Testing · AI Development · Liquid Glass

**Sections:** SwiftLee Weekly by Antoine van der Lee · SwiftUI Button: Custom Styles, Variants, and Best Practices · Screenshotbot: Scale up your snapshot tests, without the friction

**Selected links:**
- [Code for this week's article can be found on GitHub.](https://github.com/AvdLee/SwiftLeeArticlesCode) — Source repository · Topics: Swift · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Code for this week's article can be found on GitHub.. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Xcode Library customization with SPM plugin](https://www.artemnovichkov.com/blog/xcode-library-customization-with-spm-plugin) — Article · Topics: Xcode
  **NeKI brief:** Presents Xcode Library customization with SPM plugin, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Exploring MLX Swift: Adding On-Device Inference to your App](https://www.rudrank.com/exploring-mlx-swift-adding-on-device-inference-to-your-app) — Article · Topics: Swift · AI Development
  **NeKI brief:** Presents Exploring MLX Swift: Adding On-Device Inference to your App, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Finding unused code with Periphery](https://adamwulf.me/2024/12/finding-unused-code-with-periphery) — Article
  **NeKI brief:** Presents Finding unused code with Periphery, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Noncopyable types in Swift](https://nilcoalescing.com/blog/NoncopyableTypesInSwift) — Article · Topics: Swift
  **NeKI brief:** Explains noncopyable Swift types and ownership restrictions. Use it when a resource must have unique lifetime semantics and accidental copying would be invalid or expensive.
- [Understanding opaque types in Swift](https://tanaschita.com/swift-opaque-types) — Article · Topics: Swift
  **NeKI brief:** Explains opaque result types and their distinction from existential protocol values. Use it when an API should hide a concrete type while preserving compile-time specialization and identity guarantees.

## [Issue 249](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-249)

- Published: `2024-12-10T13:47:59.000Z`

**Topics:** Swift · Testing · SwiftUI · AI Development · Concurrency · Xcode

**Sections:** SwiftLee Weekly by Antoine van der Lee · SF Symbol: How to for Swift & SwiftUI · Create a complete design system using SwiftUI

**Selected links:**
- [Create a complete design system using SwiftUI](https://iosdevlibrary.lemonsqueezy.com/buy/e6e97a6a-2762-4677-bee6-bcccbb024f7d?checkout%5Bdiscount_code%5D=SWIFTLEE40) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Introduces Create a complete design system using SwiftUI as a developer resource or service relevant to Swift and Apple-platform work. Use it to assess the stated workflow or offering, checking scope, pricing, access requirements, and technical fit before relying on it.
- [Be careful wrapping a throwing function in a Task](https://www.swiftwithvincent.com/blog/be-careful-wrapping-a-throwing-function-in-a-task) — Article · Topics: Swift · Concurrency
  **NeKI brief:** Explains Be careful wrapping a throwing function in a Task, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Exploring Apple Intelligence: Image Generation](https://www.createwithswift.com/exploring-apple-intelligence-image-generation) — Article · Topics: AI Development · Swift
  **NeKI brief:** Compares Image Playground, Image Wand, and Genmoji as Apple Intelligence image-generation surfaces. Use it to distinguish system experiences and choose the appropriate entry point before implementing app-specific creative workflows.
- [AcceptedSE-0451Raw identifiers](https://github.com/apple/swift-evolution/blob/main/proposals/0451-escaped-identifiers.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0451Raw identifiers. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Migrating XCTest to Swift Testing](https://useyourloaf.com/blog/migrating-xctest-to-swift-testing) — Article · Topics: Testing · Swift
  **NeKI brief:** A migration field guide that mixes XCTest and Swift Testing in one target, maps assertions and setup, and calls out the boundary: UI automation and XCTMetric performance tests still require XCTest.
- [How to change your app's business model from paid to freemium using StoreKit](https://www.polpiella.dev/paid-app-to-freemium) — Article
  **NeKI brief:** Shows changing an app's business model from paid upfront to freemium using StoreKit's AppTransaction API. Follow it when planning migration logic and entitlement checks, then verify transaction semantics, customer communication, and App Store policy requirements.

## [Issue 248](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-248)

- Published: `2024-12-03T14:26:41.000Z`

**Topics:** Swift · Concurrency · SwiftUI · Xcode · AI Development · Liquid Glass

**Sections:** SwiftLee Weekly by Antoine van der Lee · Enum explained in-depth with code examples in Swift · Tower: native Git client for Mac (30% OFF, only this week!)

**Selected links:**
- [TextField enhancements in SwiftUI](https://swiftwithmajid.com/2024/12/03/text-field-enhancements-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Covers newer SwiftUI TextField capabilities. Use it when text input needs richer editing behavior, formatting, or platform integration beyond a basic bound string.
- [SwiftUI matched geometry effect in a custom segmented control](https://nilcoalescing.com/blog/CustomSegmentedControlWithMatchedGeometryEffect) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a segmented control with matchedGeometryEffect so the selection indicator moves between segments. Useful for coordinated SwiftUI transitions while keeping selection state separate from animation identity.
- [MacWhisper: Transcribe audio files into text with OpenAI](https://goodsnooze.gumroad.com/l/macwhisper) — Article · Topics: Concurrency · AI Development · Swift
  **NeKI brief:** Explains MacWhisper: Transcribe audio files into text with OpenAI, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Concurrency Step-by-Step: Reading from Storage](https://www.massicotte.org/step-by-step-reading-from-storage) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains Concurrency Step-by-Step: Reading from Storage, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.

## [Issue 247](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-247)

- Published: `2024-11-26T15:01:34.000Z`

**Topics:** Swift · Persistence & Synchronisation · SwiftUI · Xcode · AI Development · Core Data

**Sections:** SwiftLee Weekly by Antoine van der Lee · Black Friday: 50% discount on RocketSim & Going Indie Course · Codemagic makes Apple M2 machines available, even on the free tier!

**Selected links:**
- [Should we use Apple Intelligence for Text and Inputs in SwiftUI using writingToolsBehavior](https://medium.com/@jpmtech/should-we-use-apple-intelligence-for-text-and-inputs-in-swiftui-using-writingtoolsbehavior-49d662ce5ede) — Article · Topics: AI Development · Swift · SwiftUI
  **NeKI brief:** Evaluates writingToolsBehavior for Apple Intelligence text assistance in SwiftUI inputs. Use it when deciding whether system writing tools fit an editor, checking availability, privacy expectations, and user-control requirements.
- [Using Transactions Instead of Save in SwiftData and Core Data](https://fatbobman.com/en/posts/using-transactions-instead-of-save-in-swiftdata-and-core-data) — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** Compares transaction-style persistence work with ordinary save calls in SwiftData and Core Data. Use it when batching mutations, rollback boundaries, and consistency matter more than one-off writes.
- [Time-Based View Updates in SwiftUI](https://digitalbunker.dev/time-based-view-updates-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents Time-Based View Updates in SwiftUI, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [How to create and upload high-quality App Store assets](https://www.polpiella.dev/creating-and-uploading-app-store-assets) — Article
  **NeKI brief:** Demonstrates creating App Store screenshots and previews with RocketSim and uploading assets through Helm. Useful for making release marketing repeatable, while reviewing device coverage, localization, metadata accuracy, and App Store Connect validation before submission.

## [Issue 246](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-246)

- Published: `2024-11-19T12:58:52.000Z`

**Topics:** Swift · AI Development · Xcode · SwiftUI · Testing · Observation & State Management

**Sections:** SwiftLee Weekly by Antoine van der Lee · Contingent pricing for in-app subscriptions · Master Test Distribution & App Releases Amid App Center’s Shutdown

**Selected links:**
- [Copilot is now available in Xcode (and it’s good!)](https://www.swiftwithvincent.com/blog/copilot-is-available-in-xcode) — Article · Topics: AI Development · Xcode · Swift
  **NeKI brief:** Presents Copilot is now available in Xcode (and it’s good!), focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [ChatGPT for macOS can now work with Xcode](https://dimillian.medium.com/chatgpt-for-macos-can-now-work-with-xcode-28cecc9decf7) — Article · Topics: Xcode · AI Development · Swift
  **NeKI brief:** Presents ChatGPT for macOS can now work with Xcode, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Active ReviewSE-0453Vector, a fixed-size array](https://github.com/apple/swift-evolution/blob/main/proposals/0453-vector.md) — Source repository · Topics: Testing · Swift · SwiftUI
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0453InlineArray, a fixed-size array. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Lazy vars in @Observable classes in Swift](https://nilcoalescing.com/blog/LazyVarsInObservableClasses) — Article · Topics: Observation & State Management · Swift
  **NeKI brief:** Shows why lazy properties in @Observable types need @ObservationIgnored and where observation would otherwise treat initialization as a tracked mutation. It is a targeted fix for compiler or runtime behavior during Observation migration.
- [Understanding SwiftUI's View Update Mechanism](https://fatbobman.com/en/posts/understanding-swiftui-view-update-mechanism) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a mental model for SwiftUI body evaluation, dependency tracking, and rendering updates. Useful when investigating redundant recomputation or assuming every state change redraws the entire hierarchy.

## [Issue 245](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-245)

- Published: `2024-11-12T19:03:27.000Z`

**Topics:** Swift · Persistence & Synchronisation · Core Data · Concurrency · Xcode · SwiftData

**Sections:** SwiftLee Weekly by Antoine van der Lee · MainActor usage in Swift explained to dispatch to the main thread · Transform Your Career with the iOS Lead Essentials — Black Friday Offer

**Selected links:**
- [Apple’s Swift Format in Xcode](https://troz.net/post/2024/swift_format) — Article · Topics: Swift · Xcode
  **NeKI brief:** Presents Apple’s Swift Format in Xcode, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [swift-format](https://github.com/swiftlang/swift-format) — Source repository · Topics: Swift · Xcode
  **NeKI brief:** swift-format is the official Swift formatter and linter. Use it to enforce formatting consistently in local development and CI without relying on editor-specific whitespace settings.
- [ImplementedSE-0106Add a `macOS` Alias for the `OSX` Platform Configuration Test](https://github.com/apple/swift-evolution/blob/main/proposals/0106-rename-osx-to-macos.md) — Source repository · Topics: Swift · Testing
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0106Add a `macOS` Alias for the `OSX` Platform Configuration Test. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [ImplementedSE-0449Allow `nonisolated` to prevent global actor inference](https://github.com/apple/swift-evolution/blob/main/proposals/0449-nonisolated-for-global-actor-cutoff.md) — Source repository · Topics: Swift · Concurrency
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0449Allow `nonisolated` to prevent global actor inference. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Mastering Data Tracking and Notifications in Core Data and SwiftData](https://fatbobman.com/en/posts/mastering-data-tracking-and-notifications-in-core-data-and-swiftdata) — Article · Topics: Persistence & Synchronisation · Core Data · Swift
  **NeKI brief:** Explores change tracking and notifications in Core Data and SwiftData. Use it when UI or synchronization logic must react to persistence mutations without polling or broad refreshes.
- [Apple is Killing Swift](https://blog.jacobstechtavern.com/p/apple-is-killing-swift) — Article · Topics: Swift
  **NeKI brief:** An opinionated examination of Swift's governance and ecosystem direction; useful for evaluating community concerns rather than technical guidance.
- [Prevent screenshot capture of sensitive SwiftUI views](https://www.createwithswift.com/prevent-screenshot-capture-of-sensitive-swiftui-views) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Discusses protecting sensitive SwiftUI content from screenshots or recordings. Use it when privacy-sensitive screens need a deliberate platform-supported strategy and clear limitations communicated to product stakeholders.

## [Issue 244](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-244-1)

- Published: `2024-11-05T21:06:10.000Z`

**Topics:** Swift · Concurrency · SwiftUI · Xcode · AI Development · Networking

**Sections:** SwiftLee Weekly by Antoine van der Lee · URLSession async/await: Perform network requests in Swift · Transform Your Career with the iOS Lead Essentials — Black Friday Offer

**Selected links:**
- [Using ViewThatFits to Create a More Accessible List Cell in SwiftUI](https://medium.com/@jpmtech/using-viewthatfits-to-create-a-more-accessible-list-cell-in-swiftui-e87dc8feb4d4) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents Using ViewThatFits to Create a More Accessible List Cell in SwiftUI, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [GitHub Copilot for Xcode](https://dimillian.medium.com/github-copilot-for-xcode-62931a645173) — Article · Topics: AI Development · Xcode
  **NeKI brief:** Presents GitHub Copilot for Xcode, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Problematic Patterns in Swift Concurrency](https://www.massicotte.org/problematic-patterns) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains Problematic Patterns in Swift Concurrency, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Exploring SwiftUI Image Playground](https://www.rudrank.com/exploring-swiftui-image-playground) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents Exploring SwiftUI Image Playground, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Exploring Apple’s Intelligence Writing Tools](https://www.createwithswift.com/exploring-apple-intelligence-writing-tools) — Article · Topics: Swift
  **NeKI brief:** Covers Writing Tools across SwiftUI and UIKit, including intelligent animation and ecosystem integration. Use it to compare framework-specific adoption paths and identify where text-editing controls can inherit system writing assistance.

## [Issue 243](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-243-2)

- Published: `2024-10-29T08:54:32.000Z`

**Topics:** Swift · SwiftUI · Testing · Macros & Metaprogramming · Xcode · AI Development

**Sections:** SwiftLee Weekly by Antoine van der Lee · Mastering the @require Macro in Swift Testing · Master Mobile Monitoring SwiftUI Apps

**Selected links:**
- [Master Mobile Monitoring SwiftUI Apps](https://www.datadoghq.com/resources/mobile-monitoring-best-practices-b) — Article · Topics: Swift · SwiftUI · Performance
  **NeKI brief:** Presents Master Mobile Monitoring SwiftUI Apps, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Creating View Transitions in SwiftUI](https://www.createwithswift.com/creating-view-transitions-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Creates custom SwiftUI view transitions. Use it when insertion and removal need coordinated visual state beyond the standard opacity or movement transitions.
- [Comprehensive Guide to Mastering KeyPath in Swift](https://fatbobman.com/en/posts/comprehensive-guide-to-mastering-keypath-in-swift) — Article · Topics: Swift
  **NeKI brief:** Explains Swift key paths for typed property access and transformation. Use it when building reusable sorting, binding, observation, or mapping APIs without fragile string identifiers.
- [AcceptedSE-0449Allow `nonisolated` to prevent global actor inference](https://github.com/apple/swift-evolution/blob/main/proposals/0449-nonisolated-for-global-actor-cutoff.md) — Source repository · Topics: Concurrency · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0449Allow `nonisolated` to prevent global actor inference. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0450Package traits](https://github.com/apple/swift-evolution/blob/main/proposals/0450-swiftpm-package-traits.md) — Source repository · Topics: Swift · Swift Package Manager
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0450Package traits. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Expedited App Reviews: When and How to Use Them](https://www.polpiella.dev/expedited-app-reviews) — Article
  **NeKI brief:** Explains Apple's expedited App Review process and the circumstances in which a developer can request faster review. Use it as operational guidance for urgent fixes, while documenting impact clearly and treating approval as discretionary rather than guaranteed.
- [Active ReviewSE-0451Raw identifiers](https://github.com/apple/swift-evolution/blob/main/proposals/0451-escaped-identifiers.md) — Source repository · Topics: Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0451Raw identifiers. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.

## [Issue 242](https://newsletter.avanderlee.com/posts/swiftlee-weekly-issue-242)

- Published: `2024-10-23T08:02:09.000Z`

**Topics:** Swift · SwiftUI · Testing · Xcode · AI Development · Liquid Glass

**Sections:** SwiftLee Weekly by Antoine van der Lee · Security-scoped bookmarks for URL access · Master Mobile Monitoring SwiftUI Apps

**NeKI brief:** Highlights security-scoped bookmarks for persistent sandboxed URL access and introduces mobile monitoring for SwiftUI apps. It also links an SE-0445 proposal; treat that primary-source item as language evolution context, while the two featured sections guide macOS persistence and production observability.

## [Issue 241](https://newsletter.avanderlee.com/posts/241)

- Published: `2024-10-23T07:44:05.000Z`

**Topics:** Swift · SwiftUI · Testing · Xcode · AI Development · Liquid Glass

**Sections:** SwiftLee Weekly by Antoine van der Lee · Security-scoped bookmarks for URL access · Master Mobile Monitoring SwiftUI Apps

**NeKI brief:** Mirrors Issue 242’s October 2024 programming: security-scoped bookmarks for sandboxed URL access and mobile monitoring for SwiftUI applications, alongside the same SwiftLee newsletter framing. Use it as a duplicate archive route, not as a separate set of recommendations.
