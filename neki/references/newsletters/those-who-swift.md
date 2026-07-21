# Those Who Swift

Third-party source index. It provides source attribution and routing metadata, not republished article content. Verify article conclusions independently before applying them.

- Archive: [https://thosewhoswift.substack.com/archive](https://thosewhoswift.substack.com/archive)
- Last collected: `2026-07-22T15:04:37Z`
- Indexed entries: **81**

## [Issue 275](https://thosewhoswift.substack.com/p/those-who-swift-issue-275)

- Published: `2026-07-15`

**Topics:** Swift · AI Development · Xcode · App Intents & System Surfaces · Liquid Glass · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 275 · Weekly note ✏️

**Selected links:**
- [WWDC 2026 Developer Tools: Xcode 27, Swift, Foundation Models](https://andrew.ooo/answers/wwdc-2026-developer-tools-xcode-swift-foundation-models-june-2026) — Article · Topics: Swift · Xcode · AI Development
  **NeKI brief:** Surveys the WWDC 2026 developer-tool changes across Xcode, Swift, and Foundation Models. Use it as a release-oriented map of new workflows, then verify specific APIs, deployment requirements, and availability in Apple's current documentation.
- [SwiftUI Best Practices, straight from Apple’s Xcode 27 Agent Skill](https://www.avanderlee.com/ai-development/swiftui-best-practices-xcode-27-agent-skill) — Article · Topics: Swift · SwiftUI · Xcode
  **NeKI brief:** Turns Apple’s Xcode 27 SwiftUI guidance into an agent skill covering state flow, view composition, accessibility, and previews. The link is useful for making code-generation prompts enforce framework conventions instead of merely producing compilable views.
- [Swift Bits: My Top Xcode CI Environment Variables](https://antongubarenko.substack.com/p/swift-bits-my-top-xcode-ci-environment) — Article · Topics: Xcode · Swift
  **NeKI brief:** Collects Xcode-related environment variables that can make CI jobs more predictable and diagnosable. Follow it when hardening build scripts, while checking each variable against the project's Xcode version and the behavior of its hosted runners.
- [Foundation Models in iOS 27: Tool-Calling Control](https://blakecrosley.com/blog/foundation-models-tool-calling-ios-27) — Article · Topics: AI Development
  **NeKI brief:** Shows how tool calling and local OCR or barcode capabilities can fit into Foundation Models workflows.
- [How I use FlowDeck to let my AI agent build and run my apps](https://www.donnywals.com/how-i-use-flowdeck-to-let-my-ai-agent-build-and-run-my-apps) — Article · Topics: AI Development
  **NeKI brief:** Describes an agent workflow that can build and run an iOS app through FlowDeck. Follow it to inspect the boundary between generated code, simulator execution, and human review before adopting agent-controlled delivery loops.

## [Issue 274](https://thosewhoswift.substack.com/p/those-who-swift-issue-274)

- Published: `2026-07-08`

**Topics:** Swift · SwiftUI · Concurrency · Performance · Observation & State Management · Persistence & Synchronisation

**Sections:** Those Who Swift · Those Who Swift - Issue 274 · Weekly note ✏️

**Selected links:**
- [Understanding Sendable In Swift](https://tanaschita.com/swift-concurrency-sendable) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains Sendable and the compiler's concurrency-safety model with practical Swift examples. Use it when auditing values crossing actor boundaries and deciding whether types need immutable storage, explicit conformance, or isolation instead.
- [ConcentricRectangle And ContainerRelativeShape](https://swiftui-garden.com/Reference/ConcentricRectangle-and-ContainerRelativeShape) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Provides a focused SwiftUI reference for ConcentricRectangle and ContainerRelativeShape. Use it when creating shapes that follow container geometry or platform corner conventions, and compare the examples with the deployment targets your layout must support.
- [Reordering SwiftData In List And Grid](https://www.youtube.com/watch?v=m5VdG-EKnmk) — Video · Topics: Swift · SwiftData
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Custom Bindings In SwiftUI: Closures Vs Subscripts](https://nilcoalescing.com/blog/CustomBindingsInSwiftUIClosuresVsSubscripts) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Compares closure-based and subscript-based custom Bindings in SwiftUI, including how each expresses read and write access. Use it when designing reusable bindings and choosing an approach that keeps transformations clear, composable, and maintainable.
- [Defer In Swift Explained With Code Examples](https://www.avanderlee.com/swift/defer-usage-swift) — Article · Topics: Swift
  **NeKI brief:** Explains defer’s reverse-order cleanup semantics, scope boundaries, and Swift 6.4’s support for asynchronous cleanup. The examples help decide where resource-release code belongs and avoid assuming defer runs at task or function completion.

## [Issue 273](https://thosewhoswift.substack.com/p/those-who-swift-issue-273)

- Published: `2026-07-01`

**Topics:** Swift · SwiftUI · Testing · Xcode · Architecture · Persistence & Synchronisation

**Sections:** Those Who Swift · Those Who Swift - Issue 273 · Weekly note ✏️

**Selected links:**
- [What’s New In SwiftUI For iOS 27?](https://www.youtube.com/watch?v=tNxEqyUVGck) — Video · Topics: Swift · SwiftUI · Architecture
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [SwiftUI Is One Graph, Over 40+ Years of Engineering](https://aleahim.com/blog/swiftui-is-one-graph) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Uses SwiftUI's graph model to explain how declarative descriptions, dependencies, and updates fit together. Useful for forming a concrete mental model before diagnosing invalidation, identity, or unexpected recomputation in complex view hierarchies.
- [Understanding Privacy Manifests In iOS](https://tanaschita.com/ios-privacy-manifests) — Article · Topics: Xcode
  **NeKI brief:** Explains iOS privacy manifests, including required-reason APIs, declarations, and how app and third-party SDK manifests combine. Use it when auditing App Store compliance and documenting data-access reasons without confusing privacy manifests with permission prompts.
- [Using Cursor In Xcode 27](https://www.polpiella.dev/cursor-xcode-27) — Article · Topics: Xcode
  **NeKI brief:** Explains installing Cursor’s agent CLI, registering it through Xcode 27’s ACP support, and selecting it for new conversations. Follow it when comparing external agent choice with Xcode’s remembered conversation-agent state.
- [Reordering Beyond List - SwiftUI iOS 27](https://www.sagarunagar.com/blog/swiftui-reorderable-lazy-layouts-ios-27) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains the newer SwiftUI reordering path for LazyVStack, LazyVGrid, and custom layouts, contrasting it with hand-built drag and drop. Useful when List is too restrictive but users still need a native item-rearrangement interaction.
- [Proposing Task-Local Test Traits For Swift Testing](https://www.pointfree.co/blog/posts/217-proposing-task-local-test-traits-for-swift-testing) — Article · Topics: Testing · Swift
  **NeKI brief:** Proposes task-local test traits for Swift Testing, based on patterns developed in Point-Free libraries. The article is useful for understanding how per-test configuration could compose with structured concurrency before the proposal becomes platform API.

## [Issue 272](https://thosewhoswift.substack.com/p/those-who-swift-issue-272)

- Published: `2026-06-24`

**Topics:** Swift · SwiftUI · Concurrency · Liquid Glass · Macros & Metaprogramming · Xcode

**Sections:** Those Who Swift · Those Who Swift - Issue 272 · Weekly note ✏️

**Selected links:**
- [Liquid Glass In SwiftUI: How To Modernize An iOS App Template](https://iosapptemplates.com/blog/liquid-glass-swiftui-app-template-modernization) — Article · Topics: Liquid Glass · Swift · SwiftUI
  **NeKI brief:** Walks through modernizing a SwiftUI template with Liquid Glass styling. Use it to identify migration touchpoints in an existing UI, then validate visual hierarchy, accessibility, and API availability rather than applying the template wholesale.
- [Swift 6.4: What’s New In Concurrency](https://www.avanderlee.com/concurrency/swift-6-4-whats-new-in-concurrency) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Surveys Swift 6.4 concurrency additions with runnable examples, highlighting changes that affect isolation, task behavior, and migration choices. It is a compact map for checking which language improvements are relevant before changing production concurrency code.
- [Swift Macros Demystified: Build A Freestanding Expression Macro](https://www.youtube.com/watch?v=7W6R2TIoEW8) — Video · Topics: Macros & Metaprogramming · Swift
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [UIPortalView: From Live Mirroring to Liquid Glass-Style Effects](https://livsycode.com/uikit/exploring-_uiportalview-live-view-replication-without-copying-or-snapshots) — Article · Topics: Liquid Glass · UIKit
  **NeKI brief:** Explores UIKit's UIPortalView for live view replication without copying or taking snapshots. Follow it when evaluating mirrored or glass-like effects and when deciding how rendering, hierarchy, interaction, and performance constraints affect the design.
- [SwiftUI’s New Item Based Presentations In iOS 27](https://www.sagarunagar.com/blog/swiftui-item-based-alert-confirmation-dialog) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains item-driven SwiftUI alerts and confirmation dialogs, where an optional identifiable value selects the presented content. Useful for eliminating Boolean presentation races and associating destructive actions with the correct model item.
- [WWDC26: SwiftUI Group Lab 2nd - Q&A](https://antongubarenko.substack.com/p/wwdc26-swiftui-group-lab-2nd-q-and) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Summarizes questions and answers from the second WWDC26 SwiftUI Group Lab, capturing implementation guidance and framework constraints discussed with Apple engineers. Useful as contextual follow-up when an API’s behavior is unclear from documentation alone.

## [Issue 271](https://thosewhoswift.substack.com/p/those-who-swift-issue-271)

- Published: `2026-06-18`

**Topics:** Swift · AI Development · Testing · SwiftUI · Concurrency · Persistence & Synchronisation

**Sections:** Those Who Swift · Those Who Swift - Issue 271 · Weekly note ✏️

**Selected links:**
- [Testing Foundation Models: Code That Won’t Give The Same Answer Twice](https://www.wesleymatlock.com/testing-on-device-ai-swift-testing) — Article · Topics: Testing · AI Development · Swift
  **NeKI brief:** Discusses testing nondeterministic Foundation Models output with Swift Testing. Use it when designing assertions for on-device AI, focusing on stable structure, bounded behavior, and controlled inputs instead of brittle exact-text comparisons.
- [Async Cleanup In defer With Swift 6.4](https://livsycode.com/swift/async-cleanup-in-defer-with-swift-6-4) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains asynchronous cleanup in defer with Swift 6.4. Follow it when resource release itself must await work, and verify execution order, cancellation behavior, and toolchain support before introducing async cleanup into production paths.
- [Build a Swift Terminal Developer Toolkit with TUIkit](https://www.youtube.com/watch?v=hqDurFnEJs8) — Video · Topics: Swift · UIKit
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [What’s New In SwiftData For iOS 27](https://azamsharp.com/2026/06/12/whats-new-in-swiftdata.html) — Article · Topics: Swift · SwiftData · Persistence & Synchronisation
  **NeKI brief:** Summarizes SwiftData changes for iOS 27. Use it to identify migration and feature candidates for a persistence layer, then verify model, query, and availability details against current Apple documentation.
- [Using Claude With Apple Foundation Models](https://artemnovichkov.com/blog/using-claude-with-apple-foundation-models) — Article · Topics: AI Development
  **NeKI brief:** Explores combining Claude with Apple Foundation Models in an Apple-platform workflow. Use it when comparing cloud-model assistance with on-device generation, especially around handoff boundaries, privacy, and feature availability.
- [SwiftUI’s New .prominent Tab In iOS 27 Is Not A Floating Action Button](https://www.sagarunagar.com/blog/swiftui-prominent-tab-is-not-a-floating-action-button) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Clarifies the prominent tab role in iOS 26 and why it is navigation hierarchy rather than a generic floating action button. Useful for avoiding misleading tab-bar designs.
- [Custom Scroll Layouts With Swipe Actions In SwiftUI On iOS 27](https://nilcoalescing.com/blog/CustomScrollLayoutsWithSwipeActionsInSwiftUIOnIOS27) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows custom scroll layouts combined with swipe actions in SwiftUI on iOS 27. Use it when list-like interactions need nonstandard geometry without giving up contextual swipe affordances.
- [(Some) Unanswered Swift Group Questions](https://www.massicotte.org/blog/wwdc26-unanswered-qa) — Article · Topics: Swift
  **NeKI brief:** Collects Swift Group questions that remained unanswered around WWDC26, making uncertainty visible instead of implying unsupported behavior. Useful for identifying topics that need direct documentation or reproducible experiments.
- [WWDC26: Swift Group Lab – Q&A](https://antongubarenko.substack.com/p/wwdc26-swift-group-lab-q-and-a) — Article · Topics: Swift
  **NeKI brief:** Summarizes SwiftUI Group Lab questions from WWDC26, capturing practical API clarifications and design guidance that are easy to miss in session videos. Useful as a focused follow-up for current SwiftUI adoption decisions.

## [Issue 270](https://thosewhoswift.substack.com/p/those-who-swift-issue-270)

- Published: `2026-06-10`

**Topics:** Swift · SwiftUI · Macros & Metaprogramming · Networking · AI Development · UIKit

**Sections:** Those Who Swift · Those Who Swift - Issue 270 · Weekly note ✏️

**Selected links:**
- [SwiftUI’s State Is Now A Macro](https://livsycode.com/swiftui/swiftuis-state-is-now-a-macro) — Article · Topics: Swift · SwiftUI · Macros & Metaprogramming
  **NeKI brief:** Explains SwiftUI's newer macro-based state capabilities and their effect on view-state declarations. Use it when evaluating whether an existing property-wrapper pattern can be simplified without changing ownership or lifecycle semantics.
- [Announcing The Networking Workgroup](https://www.swift.org/blog/announcing-networking-workgroup) — Article · Topics: Networking · Swift
  **NeKI brief:** Announces Swift's Networking Workgroup and its role in coordinating networking APIs and ecosystem direction. Use it for project discovery and community context, not as a substitute for the concrete package or API documentation used in implementation.
- [SwiftUI Localization Guide — Change Language Without Restarting The App](https://www.sagarunagar.com/blog/swiftui-app-language-switching-without-restart) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows how a SwiftUI app can switch its language without restarting. Use it when evaluating runtime locale changes, while checking environment propagation, persistence, pluralization, and state refresh behavior across the app's navigation tree.
- [SwiftUI: Observable Macro Under The Hood](https://www.nsvasilev.com/posts/swiftui-observable-macro) — Article · Topics: Macros & Metaprogramming · Swift · SwiftUI
  **NeKI brief:** Peels back SwiftUI’s Observable macro expansion, showing the generated observation machinery behind an @Observable model. Useful when diagnosing tracking behavior, deciding which properties need observation, or explaining macro-generated code to a team.
- [iOS 27: Notable UIKit Additions](https://www.swiftjectivec.com/ios-27-notable-uikit-additions) — Article · Topics: UIKit · Swift
  **NeKI brief:** Surveys notable UIKit additions in iOS 27. Use it to identify modernization opportunities in an existing UIKit codebase, then verify API availability and migration impact in the relevant Apple documentation.
- [What Is New In SwiftUI After WWDC26](https://swiftwithmajid.com/2026/06/08/what-is-new-in-swiftui-after-wwdc26) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Summarizes SwiftUI additions after WWDC 2026. Use it to discover relevant new layout, rendering, and system-integration capabilities before narrowing to one feature and reading its authoritative API documentation.
- [SwiftUI Animation Timing](https://nilcoalescing.com/blog/AnimationTimingInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Breaks down SwiftUI animation timing and how duration, delay, and timing curves shape transitions. Use it when a visual effect feels out of sync and the fix requires separating state change from animation parameters.
- [Styling Measurement Unit Fonts In SwiftUI](https://nilcoalescing.com/blog/StylingMeasurementUnitFontsInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows styling measurement-unit fonts in SwiftUI so values and units retain intentional hierarchy. Follow it when displaying measurements, percentages, or localized quantities where typography should distinguish numeric content from its unit.

## [Issue 269](https://thosewhoswift.substack.com/p/those-who-swift-issue-269)

- Published: `2026-06-04`

**Topics:** Concurrency · Swift · Xcode · AI Development · SwiftUI · Testing

**Sections:** Those Who Swift · Those Who Swift - Issue 269 · Weekly note ✏️

**Selected links:**
- [Task Names In Swift Concurrency](https://artemnovichkov.com/blog/task-names-in-swift-concurrency) — Article · Topics: Swift · Concurrency · Performance
  **NeKI brief:** Explains naming tasks in Swift concurrency and how names aid debugging and observability. Follow it when tracing asynchronous work, while keeping names descriptive and avoiding assumptions that labels change scheduling, isolation, or cancellation semantics.
- [Enter Sandman Mode: Three Months Inside Xcode 26.3’s Agentic Coding](https://medium.com/@wesleymatlock/enter-sandman-mode-three-months-inside-xcode-26-3s-agentic-coding-cbe67ce46df9) — Article · Topics: AI Development · Xcode · Concurrency
  **NeKI brief:** Examines Enter Sandman Mode: Three Months Inside Xcode 26.3’s Agentic Coding, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Enabling Haptic Feedback With](https://serialcoder.dev/text-tutorials/swiftui/enabling-haptic-feedback-with-sensoryfeedback-in-swiftui) — Tutorial · Topics: Swift · SwiftUI · AI Development
  **NeKI brief:** Demonstrates SwiftUI haptic feedback through sensoryFeedback. Use it when tying tactile responses to meaningful state transitions, and review platform availability, user settings, frequency, and accessibility so feedback remains helpful rather than noisy.
- [Registering For Push Notifications In SwiftUI](https://tanaschita.com/ios-notifications-registering-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Walks through requesting notification authorization and registering a SwiftUI app for remote notifications. Use it to separate permission timing, device-token registration, and app lifecycle handling instead of treating registration as one synchronous call.
- [Stateless Actors](https://www.massicotte.org/stateless-actors) — Article · Topics: Concurrency
  **NeKI brief:** Examines stateless actors and what remains useful about actor isolation when no mutable state is stored. Follow it when choosing concurrency boundaries, distinguishing synchronization guarantees from mere type organization and measuring whether an actor adds real value.

## [Issue 268](https://thosewhoswift.substack.com/p/those-who-swift-issue-268)

- Published: `2026-05-27`

**Topics:** Swift · SwiftUI · Persistence & Synchronisation · Accessibility · Concurrency · App Intents & System Surfaces

**Sections:** Those Who Swift · Those Who Swift - Issue 268 · Weekly note ✏️

**Selected links:**
- [Modern Isn’t A Value. Fit Is.](https://www.swiftdifferently.com/blog/system-desgin/modern-isnot-a-value-fit-Is) — Article · Topics: Concurrency · Architecture · Swift
  **NeKI brief:** Argues that modern APIs are not automatically the right fit for every product or codebase. Use it as an architecture prompt: weigh compatibility, team understanding, migration cost, and user value before adopting a newer framework pattern.
- [SwiftUI Should Become Open-Source](https://macguru.dev/swiftui-should-become-open-source) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Makes a case for opening SwiftUI's implementation and discusses how transparency could affect the ecosystem. Treat it as opinion and community perspective, useful for framing trade-offs rather than as evidence about Apple's roadmap or framework internals.
- [Decoupling SwiftData in SwiftUI: Is It Worth It?](https://www.youtube.com/watch?v=2so9ifq5hYY) — Video · Topics: Swift · SwiftData · SwiftUI
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Anthropic Co-Founder Chris Olah’s Remarks On Pope Leo XIV’s Encyclical “Magnifica Humanitas”](https://www.anthropic.com/news/chris-olah-pope-leo-encyclical) — Article · Topics: AI Development
  **NeKI brief:** Examines Anthropic Co-Founder Chris Olah’s Remarks On Pope Leo XIV’s Encyclical “Magnifica Humanitas”, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Making A SwiftUI Sheet Automatically Size To Fit Its Content](https://danielsaidi.com/blog/2026/05/22/making-a-swiftui-sheet-automatically-size-to-fit-its-content) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI sheet that measures its content and chooses an appropriate presentation height. Useful for compact forms and detail panels that should avoid excessive empty space while handling dynamic type and updates.
- [Refreshing And Animating Views Using TimelineView In SwiftUI](https://nilcoalescing.com/blog/TimelineViewInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Uses TimelineView to refresh SwiftUI content on a schedule without manually managing a timer. Follow it for clocks, elapsed-time displays, and periodic UI updates where lifecycle and cadence should remain declarative.
- [Working With The Keychain In iOS](https://tanaschita.com/ios-keychain-secure-data-storage) — Article · Topics: Persistence & Synchronisation
  **NeKI brief:** Explains storing sensitive iOS data in Keychain and the accessibility choices that affect availability. Use it when designing credential persistence, selecting protection classes, and separating secrets from ordinary app storage.
- [W.W.D.C. 2026: The Pregame Quiz](https://www.swiftjectivec.com/wwdc-2026-the-pregame-quiz) — Article · Topics: Swift
  **NeKI brief:** Presents W.W.D.C. 2026: The Pregame Quiz, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.

## [Issue 267](https://thosewhoswift.substack.com/p/those-who-swift-issue-267)

- Published: `2026-05-21`

**Topics:** Swift · SwiftUI · AI Development · Accessibility · Xcode · Architecture

**Sections:** Those Who Swift · Those Who Swift - Issue 267 · Weekly note ✏️

**Selected links:**
- [Using Xcode MCP With Claude Code](https://danielsaidi.com/blog/2026/04/30/using-xcode-mcp-with-claude-code) — Article · Topics: Xcode · AI Development · Swift
  **NeKI brief:** Describes connecting Claude Code to Xcode through Model Context Protocol. Follow it when evaluating agent-assisted build and debugging workflows, paying attention to permissions, simulator boundaries, generated changes, and human review checkpoints.
- [ContentUnavailableView In SwiftUI - Complete Guide With Examples](https://www.sagarunagar.com/blog/contentunavailableview-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates ContentUnavailableView for empty, failed, or unavailable SwiftUI states with labels and actions. Useful for standardizing placeholder screens while preserving semantic messaging and a clear recovery path.
- [Understanding Basic Animations In SwiftUI](https://tanaschita.com/swiftui-basic-animations) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Introduces SwiftUI's state-driven animation model through basic transitions and modifiers. Follow it when mapping a state change to a visual effect and checking which view values actually participate in interpolation.
- [How To Recognize Text In Images With Vision In Swift](https://onmyway133.com/posts/how-to-recognize-text-in-images-with-vision-in-swift) — Article · Topics: Swift · Concurrency
  **NeKI brief:** Shows text recognition in images with Apple's Vision framework. Use it when prototyping OCR, considering request configuration, region or language hints, result confidence, and asynchronous image processing before integrating recognized text into user-visible features.
- [Deprecating Your Own Convenience API](https://swiftwithmajid.com/2026/05/19/deprecating-your-own-convenience-api) — Article · Topics: Swift
  **NeKI brief:** Explains deprecating a convenience API with migration messages and replacement paths. Use it when evolving an internal or public Swift interface while keeping callers compiling and making the preferred alternative discoverable.
- [A Feature Flags System In Swift](https://livsycode.com/best-practices/a-feature-flags-system-in-swift) — Article · Topics: Swift · Architecture
  **NeKI brief:** Presents a Swift feature-flags design with centralized evaluation and rollout control. Use it to compare configuration models and testing seams, while ensuring flag ownership, expiration, and failure defaults are explicit in production.

## [Issue 266](https://thosewhoswift.substack.com/p/those-who-swift-issue-266)

- Published: `2026-05-13`

**Topics:** Swift · SwiftUI · Performance · Architecture · Networking · Testing

**Sections:** Those Who Swift · Those Who Swift - Issue 266 · Weekly note ✏️

**Selected links:**
- [How To Think About Performance In iOS](https://livsycode.com/best-practices/how-to-think-about-performance-in-ios) — Article · Topics: Performance · Architecture · Networking
  **NeKI brief:** Frames iOS performance as a measurement and prioritization problem rather than a collection of tricks. Follow it when planning investigations, connecting user-visible symptoms to traces, and choosing fixes that improve the actual bottleneck.
- [Production SwiftUI: Scalable Networking Architecture With Async/Await And Generics](https://www.youtube.com/watch?v=M5ZUGBeugP4) — Video · Topics: Architecture · Concurrency · Networking
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Cut Your Swift Compile Times with Xcode 26](https://watch.getcontrast.io/register/bitrise-how-to-speed-up-ios-builds-with-xcode-26-compilation-caching) — Article · Topics: Xcode · Swift
  **NeKI brief:** This Bitrise session registration page covers techniques for improving iOS build speed with Xcode 26 compilation caching. Use it to discover CI optimization guidance, then validate recommendations against the project’s toolchain and measured build traces.
- [Accelerate Framework In Swift - Complete Guide To High-Performance Computing](https://www.sagarunagar.com/blog/accelerate-framework-swift-guide) — Article · Topics: Swift · Performance
  **NeKI brief:** Introduces Apple's Accelerate framework through Swift examples for vector and numerical workloads. Use it when evaluating CPU-intensive computations, comparing optimized primitives with simpler code, and checking memory layout, precision, and platform availability.
- [Formatting Values In SwiftUI Text And TextField](https://serialcoder.dev/text-tutorials/swiftui/formatting-values-in-swiftui-text-and-textfield) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Explains formatting values in SwiftUI Text and TextField using format styles and bindings. Useful for locale-aware display and editing of numbers or dates while keeping model values typed and validation predictable.
- [SwiftUI: @State Under The Hood](https://www.nsvasilev.com/posts/swiftui-state) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explores SwiftUI @State storage and its relationship to view identity and lifetime. Useful for diagnosing resets, deciding which state belongs in a view, and explaining why a local mutation survives recomputation.

## [Issue 265](https://thosewhoswift.substack.com/p/those-who-swift-issue-265)

- Published: `2026-05-06`

**Topics:** Swift · Concurrency · SwiftUI · AI Development · Architecture · Performance

**Sections:** Those Who Swift · Those Who Swift - Issue 265 · Weekly note ✏️

**Selected links:**
- [Scheduling And Handling Background App Refresh In SwiftUI](https://nilcoalescing.com/blog/SchedulingAndHandlingBackgroundAppRefreshInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows how a SwiftUI app enables, schedules, handles, and tests background refresh work using Background Tasks and backgroundTask(_:action:).
- [Swift Concurrency: One await, Two Actors: A Runtime Trace](https://adjoe.io/company/engineer-blog/swift-concurrency-await-runtime-trace-executor-hops) — Article · Topics: Concurrency · Swift · Performance
  **NeKI brief:** Traces how an await can move execution between actors and executors at runtime. Follow it when diagnosing latency or unexpected scheduling, using Instruments or logs to validate hops instead of inferring behavior from source order alone.
- [Actors Vs Queues Vs Locks In Swift](https://livsycode.com/best-practices/actors-vs-queues-vs-locks-in-swift) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Compares actors, dispatch queues, and locks as synchronization tools in Swift. Use it when selecting a concurrency primitive by ownership, reentrancy, contention, and migration constraints rather than by modernity alone.
- [3 Key Strategies To Make SwiftUI Views More Reusable](https://matteomanferdini.com/swiftui-reusable-views) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents three concrete strategies for making SwiftUI views reusable, from extracting components to controlling dependencies and state. Useful when reducing duplication without hiding feature-specific behavior behind overly generic abstractions.
- [Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.

## [Issue 264](https://thosewhoswift.substack.com/p/those-who-swift-issue-264)

- Published: `2026-04-29`

**Topics:** Swift · Concurrency · SwiftUI · Performance · Testing · AI Development

**Sections:** Those Who Swift · Those Who Swift - Issue 264 · Weekly note ✏️

**Selected links:**
- [iOS 26 SDK Migration Guide: What Every App Needs To Update](https://idiotswithios.com/ios-26-sdk-migration-guide-what-every-app-needs-to-update) — Article · Topics: Testing · Liquid Glass · Xcode
  **NeKI brief:** Highlights migration areas when adopting the iOS 26 SDK, including project settings and UI changes. Use it as a checklist for an upgrade pass, then verify each required change against current Xcode release notes and API documentation.
- [Immediate Tasks In Swift Concurrency Explained](https://www.avanderlee.com/concurrency/immediate-tasks-in-swift-concurrency-explained) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains immediate tasks and their execution timing in Swift 6.2, contrasting them with ordinary task scheduling and actor hops. The examples clarify when reduced scheduling latency is useful and where ordering assumptions become unsafe.
- [Understanding Inout Parameters In Swift - How They Work And When To Use Them](https://www.sagarunagar.com/blog/swift-inout-parameters) — Article · Topics: Swift · Performance
  **NeKI brief:** Explains Swift inout parameters, including exclusivity and mutation semantics. Follow it when reviewing APIs that borrow mutable storage, especially where escaping closures, overlapping accesses, or value-copy expectations can make a seemingly simple call unsafe.
- [Paywall Design Tips That Boost App Sales - Part 2](https://indieappdevs.substack.com/p/indie-app-devs-21) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines Paywall Design Tips That Boost App Sales - Part 2, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [How To Implement Pagination With SwiftUI’s List View](https://tanaschita.com/swiftui-list-pagination) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Implements incremental pagination in SwiftUI List as the user approaches the end of loaded content. Use it when an async data source needs explicit loading, error, and duplicate-request guards rather than eager full retrieval.

## [Issue 263](https://thosewhoswift.substack.com/p/those-who-swift-issue-263)

- Published: `2026-04-22`

**Topics:** Swift · SwiftUI · Performance · App Intents & System Surfaces · Concurrency · Testing

**Sections:** Those Who Swift · Those Who Swift - Issue 263

**Selected links:**
- [A Reusable Spotlight Onboarding Component In SwiftUI](https://livsycode.com/swiftui/a-reusable-spotlight-onboarding-component-in-swiftui) — Article · Topics: Swift · SwiftUI · App Intents & System Surfaces
  **NeKI brief:** Builds a reusable SwiftUI spotlight onboarding component that highlights interface elements. Use it when designing guided discovery, keeping target geometry, overlay interaction, accessibility, and dismissal state separate from feature content.
- [Associatedtype In Swift Explained - A Complete Guide With SwiftUI Examples](https://www.sagarunagar.com/blog/associatedtype-swift-explained-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains associatedtype requirements with Swift and SwiftUI examples. Use it when designing protocols with type relationships, deciding when generics or type erasure are needed, and keeping implementation constraints understandable to callers.
- [SE-0526: WithDeadline](https://forums.swift.org/t/se-0526-withdeadline/85850) — Article · Topics: Swift · Concurrency
  **NeKI brief:** Presents the Swift Evolution discussion for SE-0526, WithDeadline. Follow the proposal thread to understand motivation, naming, and review trade-offs, but consult the accepted proposal and installed SDK before relying on a specific API shape.
- [Building A Draggable Bottom Sheet In SwiftUI](https://tanaschita.com/swiftui-draggable-bottom-sheet) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a draggable SwiftUI bottom sheet with gesture state, detents, and snapping decisions. Useful for custom interaction when system sheets do not expose the required presentation behavior.
- [FormatStyle Guide](https://chris.eidhof.nl/post/format-style-guide) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Introduces an interactive browser-based guide to Swift Foundation FormatStyle APIs, implemented with WebAssembly. Use the linked guide for quickly comparing formatting capabilities and verify availability against current Foundation documentation.
- [SwiftUI: Refreshable Task Cancellation](https://antongubarenko.substack.com/p/swiftui-refreshable-task-cancellation) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains how refreshable starts asynchronous work and how cancellation propagates when the user ends or repeats a refresh. Useful for making pull-to-refresh tasks idempotent, responsive, and safe against stale results.

## [Issue 262](https://thosewhoswift.substack.com/p/those-who-swift-issue-262)

- Published: `2026-04-15`

**Topics:** Swift · SwiftUI · Testing · Accessibility · Concurrency

**Sections:** Those Who Swift · Those Who Swift - Issue 262 · Weekly note ✏️

**Selected links:**
- [Kids And Vibe Coding: The Joy Of Building](https://www.swiftjectivec.com/kids-and-vibe-coding-ios-apps) — Article · Topics: AI Development · Swift
  **NeKI brief:** Reflects on children building iOS apps with AI-assisted or vibe-coding tools. Use it as a product and education perspective on lowering entry barriers while retaining testing, safety, authorship, and review practices.
- [Checking Accessibility With SwiftUI Previews](https://mobilea11y.com/blog/swiftui-preview-testing) — Article · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Uses SwiftUI previews as an accessibility testing surface, checking labels, traits, and contrast across representative states. Useful for finding VoiceOver regressions early without waiting for a full UI-test suite.
- [Interface Segregation Principle In IOS: How To Prevent A Protocol From Becoming A Prison](https://swiftandmemes.com/interface-segregation-principle-in-ios-how-to-prevent-protocol-from-becoming-a-prison) — Article · Topics: Swift
  **NeKI brief:** Examines Interface Segregation Principle In IOS: How To Prevent A Protocol From Becoming A Prison, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [How To Test In-App Purchases Locally Using StoreKit](https://tanaschita.com/testing-in-app-purchases-locally-storekit) — Article · Topics: Testing
  **NeKI brief:** Explains local StoreKit configuration in Xcode for simulating purchases, subscriptions, and failure cases without depending on App Store sandbox accounts.

## [Issue 261](https://thosewhoswift.substack.com/p/those-who-swift-issue-261)

- Published: `2026-04-08`

**Topics:** Swift · SwiftUI · Testing · AI Development · Accessibility · Concurrency

**Sections:** Those Who Swift · Those Who Swift - Issue 261 · Weekly note ✏️

**Selected links:**
- [Building List Replacement In SwiftUI](https://swiftwithmajid.com/2026/04/06/building-list-replacement-in-swiftui) — Article · Topics: Swift · SwiftUI · Performance
  **NeKI brief:** Builds a custom SwiftUI list replacement by composing scrolling, layout, and row behavior directly. Use it when List's styling or interaction constraints are the real limitation, while measuring the performance cost of custom virtualization.
- [SwiftUI Custom Popover](https://livsycode.com/swiftui/swiftui-custom-popover) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates building a custom popover in SwiftUI when system presentation is too constrained. Follow it when evaluating geometry, dismissal, hit testing, and accessibility requirements, and prefer system popovers where their behavior is sufficient.
- [Beta Preview: DebugSnapshots](https://www.pointfree.co/blog/posts/205-beta-preview-debugsnapshots) — Article · Topics: Testing · Macros & Metaprogramming
  **NeKI brief:** Introduces DebugSnapshots for recording structured debugging state alongside UI behavior. Follow it when reproducing visual or state-dependent failures requires an inspectable artifact rather than a screenshot detached from its model inputs.
- [No, SwiftUI Is Not “Accessible By Default”](https://mobilea11y.com/blog/swiftui-not-accessible) — Article · Topics: Swift · SwiftUI · Accessibility
  **NeKI brief:** Challenges the assumption that SwiftUI interfaces are accessible by default. Use it as an audit prompt to verify labels, traits, focus order, Dynamic Type, contrast, and custom controls with assistive technologies.

## [Issue 260](https://thosewhoswift.substack.com/p/those-who-swift-issue-260)

- Published: `2026-04-01`

**Topics:** Swift · SwiftUI · Navigation & Deep Linking · AI Development · Concurrency · Testing

**Sections:** Those Who Swift · Those Who Swift - Issue 260 · Weekly note ✏️

**Selected links:**
- [Top 10 Developer Tools Apple Introduced At WWDC25](https://fline.dev/blog/top-10-developer-tools-apple-introduced-at-wwdc25) — Article · Topics: AI Development · Swift · SwiftUI
  **NeKI brief:** Examines Top 10 Developer Tools Apple Introduced At WWDC25, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [OpenAI: Build For iOS And macOS](https://developers.openai.com/codex/use-cases/native-ios-macos-apps) — Article · Topics: Testing · AI Development · Swift
  **NeKI brief:** Examines OpenAI: Build For iOS And macOS, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [What’s New In Swift: March 2026 Edition](https://www.swift.org/blog/whats-new-in-swift-march-2026) — Article · Topics: Swift · Swift Package Manager
  **NeKI brief:** Summarizes Swift changes released or highlighted in March 2026. Use it to locate language and tooling updates relevant to a project, then read the linked proposals and release notes before changing source or compiler settings.
- [Thread Vs Queue Vs Actor Executor In Swift: Interview Essentials](https://livsycode.com/swift/thread-vs-queue-vs-actor) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Compares threads, queues, and actor executors for Swift concurrency reasoning. Follow it when explaining execution models or debugging ordering, while distinguishing conceptual scheduling from the guarantees provided by structured concurrency and isolation.
- [SwiftUI View Lifecycle: When onAppear Actually Fires](https://www.swiftyplace.com/blog/swiftui-view-lifecycle-onappear) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Investigates surprising onAppear behavior across SwiftUI view hierarchies and lifecycle changes. Useful for placing side effects safely, distinguishing view construction from appearance, and preventing duplicate loads or missed refreshes.
- [Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.

## [Issue 259](https://thosewhoswift.substack.com/p/those-who-swift-issue-259)

- Published: `2026-03-26`

**Topics:** Swift · SwiftUI · Concurrency · Architecture · AI Development · Liquid Glass

**Sections:** Those Who Swift · Those Who Swift - Issue 259 · Weekly note ✏️

**Selected links:**
- [SwiftUI Live Broadcasting With AWS IVS](https://medium.com/@itsuki.enjoy/swiftui-live-broadcasting-with-aws-ivs-bcd461764e2b) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI Live Broadcasting With AWS IVS, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [I Refactored 3 Apps In A Year. Here’s What I Actually Learned](https://kubamilcarz.medium.com/i-refactored-3-apps-in-a-year-heres-what-i-actually-learned-bc519ba33bb1?source=rss-b30973e2bd56------2) — Article · Topics: Concurrency · Architecture
  **NeKI brief:** Examines I Refactored 3 Apps In A Year. Here’s What I Actually Learned, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Apple Foundation Models In Practice: Building On-Device AI Features In Swift](https://medium.com/@wesleymatlock/apple-foundation-models-in-practice-building-on-device-ai-features-in-swift-b6243976af4f) — Article · Topics: AI Development · Swift
  **NeKI brief:** Examines Apple Foundation Models In Practice: Building On-Device AI Features In Swift, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [The Layout Protocol (Part 1)](https://talk.objc.io/episodes/S01E484-the-layout-protocol-part-1) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines The Layout Protocol (Part 1), emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Talking Liquid Glass With Apple](https://captainswiftui.substack.com/p/talking-liquid-glass-with-apple) — Article · Topics: Liquid Glass · Swift · SwiftUI
  **NeKI brief:** Reports a direct discussion with Apple about Liquid Glass design and implementation guidance. Useful for understanding the intended visual language and avoiding speculative patterns while adapting SwiftUI interfaces to the new material system.
- [Swift Algorithms - Apple’s Hidden Collection And Sequence APIs You Should Be Using](https://www.sagarunagar.com/blog/swift-algorithms-complete-guide) — Article · Topics: Swift
  **NeKI brief:** Explains Apple’s Hidden Collection and Sequence APIs You Should Be Using, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Swift 6.3 Released](https://www.swift.org/blog/swift-6.3-released) — Article · Topics: Swift
  **NeKI brief:** Announces Swift 6.3 and summarizes the language, package, and tooling changes in that release. Use it to identify migration candidates, then consult the release notes and proposal links for exact compiler behavior and availability.

## [Issue 258](https://thosewhoswift.substack.com/p/those-who-swift-issue-258)

- Published: `2026-03-18`

**Topics:** Swift · SwiftUI · Xcode · Persistence & Synchronisation · SwiftData · AI Development

**Sections:** Those Who Swift · Those Who Swift - Issue 258 · Weekly note ✏️

**Selected links:**
- [Apple Doesn’t Show SwiftData iCloud Sync Status — So Let’s Build One](https://azamsharp.com/2026/03/16/swiftdata-icloud-sync-status.html) — Article · Topics: Swift · SwiftData · Persistence & Synchronisation
  **NeKI brief:** Examines Apple Doesn’t Show SwiftData iCloud Sync Status — So Let’s Build One, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Over-Extended Types On The Overuse Of Swift Extensions](https://pastey.github.io/blog/2026-02-15-extensions) — Article · Topics: Swift · Concurrency
  **NeKI brief:** Examines Over-Extended Types On The Overuse Of Swift Extensions, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Expanding Animations In SwiftUI Lists](https://nerdyak.tech/development/2026/03/16/expand-animation-in-SwiftUI-List.html) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Diagnoses janky expand and collapse animations inside SwiftUI List and documents the identity and transaction choices that improve them. Useful when animating variable-height rows without breaking list diffing or scroll performance.
- [Build A Searchable, Sortable SwiftUI List With An Index Scrubber](https://www.youtube.com/watch?v=sUZ6agowSew) — Video · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Working With String Catalogs In iOS Projects](https://tanaschita.com/ios-string-catalogs-in-practice) — Article · Topics: Xcode
  **NeKI brief:** Explains adopting String Catalogs for localized iOS content and managing translations in Xcode. Use it when migrating string resources, preserving localization keys, and checking plural or variation coverage before release.

## [Issue 257](https://thosewhoswift.substack.com/p/those-who-swift-issue-257)

- Published: `2026-03-11`

**Topics:** Swift · SwiftUI · Core Data · Persistence & Synchronisation · Xcode · Testing

**Sections:** Those Who Swift · Those Who Swift - Issue 257 · Weekly note ✏️

**Selected links:**
- [CLAUDE.md for iOS Developers](https://www.youtube.com/watch?v=0UaqjKb3QHM&t=108s) — Video · Topics: AI Development · Architecture · Swift
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Swift At Scale: Building The TelemetryDeck Analytics Service](https://www.swift.org/blog/building-privacy-first-analytics-with-swift) — Article · Topics: Swift · Xcode
  **NeKI brief:** Describes building a privacy-first analytics service in Swift and the engineering choices behind it. Follow it when evaluating telemetry architecture, data minimization, and server-side Swift trade-offs without treating the service design as an app recipe.
- [Get Rid Of Your SwiftGen Dependency](https://appleboy.tech/articles/get-rid-of-your-swiftgen-dependency) — Article · Topics: Swift · Xcode
  **NeKI brief:** Examines Get Rid Of Your SwiftGen Dependency, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [What AI Coding Costs You](https://tomwojcik.com/posts/2026-02-15/finding-the-right-amount-of-ai) — Article · Topics: AI Development · Testing
  **NeKI brief:** Discusses What AI coding costs you in a public developer resource. Use it to compare the author's concrete workflow and trade-offs with your project constraints, and verify any platform-specific claims against current primary documentation.
- [Creating Overlays On A Map In A SwiftUI App In iOS 26](https://www.createwithswift.com/creating-overlays-on-a-map-in-a-swiftui-app-in-ios-26) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows placing custom overlays on a SwiftUI Map in iOS 26. Follow it when map annotations need richer layout or interaction and you must keep geographic positioning separate from overlay view state.
- [Speed Hacks for iOS Builds](https://bitrise.io/whitepapers/level-up-your-ios-game-tips-for-speeding-up-your-continuous-integration) — Article
  **NeKI brief:** Discusses Save Time on Every Build and Test Run in a public developer resource. Use it to compare the author's concrete workflow and trade-offs with your project constraints, and verify any platform-specific claims against current primary documentation.

## [Issue 256](https://thosewhoswift.substack.com/p/those-who-swift-issue-256)

- Published: `2026-03-06`

**Topics:** Swift · Swift Package Manager · UIKit · SwiftUI · Architecture · Networking

**Sections:** Those Who Swift · Those Who Swift - Issue 256 · Weekly note ✏️

**Selected links:**
- [Modularizing Swift Apps with Swift Package Manager](https://kylebrowning.com/posts/modularizing-swift-apps-with-spm) — Article · Topics: Swift · Swift Package Manager · Architecture
  **NeKI brief:** Presents a concrete implementation of Modularizing Swift Apps with SPM. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.
- [Building a Reusable Network Manager in Swift](https://www.youtube.com/watch?v=zEzIxdA8zLQ) — Video · Topics: Swift · Networking · Concurrency
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Geometry in SwiftUI Explained](https://www.sagarunagar.com/blog/geometry-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Surveys GeometryReader, GeometryProxy, and onGeometryChange through practical SwiftUI layout examples. Useful for choosing the least-coupled measurement tool when adaptive components need size or position information without destabilizing layout.
- [NSCache in Swift](https://livsycode.com/best-practices/nscache-in-swift-a-practical-guide) — Article · Topics: Swift · Performance
  **NeKI brief:** Explains NSCache usage in Swift, including eviction-oriented caching behavior. Use it when adding an in-memory cache, choosing keys and cost limits, and ensuring correctness does not depend on cached values surviving memory pressure.
- [Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.

## [Issue 255](https://thosewhoswift.substack.com/p/those-who-swift-issue-255)

- Published: `2026-02-25`

**Topics:** Swift · SwiftUI · Testing · Persistence & Synchronisation · Concurrency · Observation & State Management

**Sections:** Those Who Swift · Those Who Swift - Issue 255 · Weekly note ✏️

**Selected links:**
- [Why Your @Observable Class init Runs Multiple Times in SwiftUI?](https://livsycode.com/swiftui/why-your-observable-class-init-runs-multiple-times-in-swiftui) — Article · Topics: Swift · SwiftUI · Observation & State Management
  **NeKI brief:** Investigates why an @Observable class initializer can run repeatedly in SwiftUI. Follow it when diagnosing ownership and identity mistakes, checking observation lifetime, view reconstruction, and the distinction between initialization and persistent model state.
- [Testing Event Streams](https://www.massicotte.org/blog/testing-event-stream) — Article · Topics: Testing · Concurrency
  **NeKI brief:** Explains Testing with Event Streams, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Testing Database Migrations](https://tanaschita.com/testing-database-migrations) — Article · Topics: Testing · Persistence & Synchronisation
  **NeKI brief:** Presents a database-migration testing workflow that verifies schema changes against realistic stores. Use it to catch destructive transformations, ordering mistakes, and data-loss regressions before shipping a new persistence version.
- [Static vs Dynamic Dispatch in Swift](https://www.sagarunagar.com/blog/static-vs-dynamic-dispatch-swift) — Article · Topics: Swift · Performance
  **NeKI brief:** Examines Static vs Dynamic Dispatch in Swift, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Creating Maps in SwiftUI Apps With MapKit](https://www.createwithswift.com/creating-maps-in-swiftui-apps-with-mapkit) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a MapKit-backed SwiftUI map with regions and content. Follow it when moving from delegate-driven maps to state-driven annotations, selection, and camera updates in a modern SwiftUI screen.

## [Issue 254](https://thosewhoswift.substack.com/p/those-who-swift-issue-254)

- Published: `2026-02-18`

**Topics:** Swift · SwiftUI · AI Development · Persistence & Synchronisation · SwiftData · Observation & State Management

**Sections:** Those Who Swift · Those Who Swift - Issue 254 · Weekly note ✏️

**Selected links:**
- [SwiftUI Foundations: Build Great Apps Q&A](https://antongubarenko.substack.com/p/swiftui-foundations-build-great-apps) — Article · Topics: Swift · SwiftUI · Architecture
  **NeKI brief:** Examines SwiftUI Foundations: Build Great Apps Q&A, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [How to Migrate to @Observable Without Breaking Your App](https://swiftandmemes.com/how-to-migrate-to-observable-without-breaking-your-app) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Examines How to Migrate to @Observable Without Breaking Your App, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Sharing SwiftData Content Between Users](https://www.youtube.com/watch?v=t9FRldfZ8vc) — Video · Topics: Swift · SwiftData · SwiftUI
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Tracking Token Usage in Foundation Models](https://artemnovichkov.com/blog/tracking-token-usage-in-foundation-models) — Article · Topics: AI Development · Performance
  **NeKI brief:** Presents Tracking token usage in Foundation Models, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Isolate SwiftUI Animations to Specific Attributes](https://nilcoalescing.com/blog/IsolateSwiftUIAnimationsToSpecificAttributes) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows how to scope SwiftUI animation to selected attributes rather than every state change in a view update. Use it when unrelated layout or content changes animate accidentally and make interaction feel unstable.
- [Taking First Steps Into Metal Shaders](https://www.createwithswift.com/taking-first-steps-into-metal-shaders) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Introduces Metal shader integration from a SwiftUI perspective, including the boundary between view modifiers and GPU functions. Follow it when prototyping shader effects and evaluating parameter flow, availability, and fallback behavior.

## [Issue 253](https://thosewhoswift.substack.com/p/those-who-swift-issue-253)

- Published: `2026-02-12`

**Topics:** Swift · SwiftUI · Xcode · AI Development · Architecture · Navigation & Deep Linking

**Sections:** Those Who Swift · Those Who Swift - Issue 253 · Weekly note ✏️

**Selected links:**
- [Container-Based Dependency Injection](https://livsycode.com/best-practices/container-based-dependency-injection) — Article · Topics: Architecture · Dependency Injection · Swift
  **NeKI brief:** Presents container-based dependency injection in Swift and the trade-offs of centralized resolution. Use it when comparing composition strategies, keeping dependencies explicit, and preventing a container from becoming hidden global state.
- [SwiftUI Coordinators](https://tanaschita.com/swiftui-coordinators) — Article · Topics: Navigation & Deep Linking · Swift · SwiftUI
  **NeKI brief:** Uses DataScannerViewController to show how UIViewControllerRepresentable.Coordinator receives UIKit delegate callbacks and sends results back to SwiftUI, making the coordinator boundary concrete for delegate-driven integrations.
- [Measure App Launch Time in iOS](https://swiftdevjournal.com/posts/measure-app-launch-time) — Article · Topics: Performance · Swift · Xcode
  **NeKI brief:** Explains ways to measure iOS app launch time and interpret the resulting timings. Follow it when establishing a baseline, separating cold and warm launches, and connecting signposts or metrics to user-visible startup work.
- [Agentic Coding in Xcode 26.3 with Claude Code and Codex](https://www.swiftjectivec.com/agentic-coding-codex-claude-code-in-xcode) — Article · Topics: AI Development · Xcode · Swift
  **NeKI brief:** Examines Agentic Coding in Xcode 26.3 with Claude Code and Codex, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Agentic Coding in Xcode](https://swiftwithmajid.com/2026/02/10/agentic-coding-in-xcode) — Article · Topics: AI Development · Xcode · Swift
  **NeKI brief:** Details configuring Xcode 26.3’s agentic coding support and practical habits for delegating Apple-platform work. Follow it when establishing project context, reviewing generated diffs, and keeping Xcode’s agent actions inside an auditable workflow.
- [Morphing Sheets Out of Buttons in SwiftUI](https://serialcoder.dev/text-tutorials/swiftui/morphing-sheets-out-of-buttons-in-swiftui) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates morphing a SwiftUI button into sheet content using matched visual state and presentation transitions. Useful for building expressive modal affordances while keeping trigger state, accessibility, and dismissal behavior explicit.
- [Adding an Open Recent Menu in a macOS App](https://swiftdevjournal.com/posts/open-recent-menu) — Article · Topics: Swift
  **NeKI brief:** Adds an Open Recent menu to a SwiftUI app, wiring recent document state into platform menu commands. Useful for macOS document workflows that need persistence, discoverable actions, and correct scene-level ownership.

## [Issue 252](https://thosewhoswift.substack.com/p/those-who-swift-issue-252)

- Published: `2026-02-04`

**Topics:** Swift · SwiftUI · AI Development · Performance · Xcode · App Intents & System Surfaces

**Sections:** Those Who Swift · Those Who Swift - Issue 252 · Weekly note ✏️

**Selected links:**
- [The Secret to Buttery Smooth SwiftUI](https://www.swiftdifferently.com/blog/swiftui/swiftui-performance-article) — Article · Topics: Swift · SwiftUI · Performance
  **NeKI brief:** Explores practical causes of sluggish SwiftUI rendering and techniques for reducing unnecessary work. Useful as a performance checklist before profiling view identity, expensive body computations, and state-driven update frequency with Instruments.
- [Mastering DatePicker, MultiDatePicker, and ColorPicker in SwiftUI](https://www.youtube.com/watch?v=O540BJGGpYw&t=2s) — Video · Topics: Swift · SwiftUI · Persistence & Synchronisation
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Tiered Caching in Swift](https://kylebrowning.com/posts/tiered-caching-in-swift) — Article · Topics: Swift · Performance
  **NeKI brief:** Presents a tiered caching approach in Swift across faster and slower storage layers. Use it when designing cache lookup and invalidation policy, keeping source-of-truth ownership, freshness, serialization, and memory pressure behavior explicit.
- [SwiftUI Weather App Copy Cat With WeatherKit](https://medium.com/@itsuki.enjoy/swiftui-weather-app-copy-cat-with-weather-kit-6d3dfafbd1e4) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI Weather App Copy Cat With WeatherKit, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Designing Swift Errors for an SDK](https://nonstrict.eu/blog/2026/designing-swift-errors-for-an-sdk) — Article · Topics: Swift
  **NeKI brief:** This article covers designing stable, expressive error APIs for Swift SDKs. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Branding With AI Superpowers for Indie Creators](https://www.createwithswift.com/branding-with-ai-superpowers-for-indie-creators) — Article · Topics: AI Development · Swift
  **NeKI brief:** Explores how indie creators can use AI tools to shape a product brand, from visual direction through reusable assets and messaging. Useful for evaluating an AI-assisted branding workflow while retaining human decisions about audience, tone, and consistency.
- [Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.

## [Issue 251](https://thosewhoswift.substack.com/p/those-who-swift-issue-251)

- Published: `2026-01-28`

**Topics:** Swift · SwiftUI · Concurrency · Liquid Glass

**Sections:** Those Who Swift · Those Who Swift - Issue 251 · Weekly note ✏️

**Selected links:**
- [Liquid Glass Toast in SwiftUI](https://writetodisk.com/liquid-glass-toast) — Tutorial · Topics: Liquid Glass · Swift · SwiftUI
  **NeKI brief:** Demonstrates a Liquid Glass toast-style notification in SwiftUI. Follow it for transient feedback experiments, but verify timing, safe-area placement, VoiceOver announcements, reduced motion, and whether an existing system affordance is more appropriate.
- [SwiftUI Alerting with NSAlert](https://medium.com/@itsuki.enjoy/swiftui-alerting-with-nsalert-21bdc3a8e650) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI Alerting with NSAlert, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Swift Actors: Common Pitfalls and How to Avoid Them](https://www.fractal-dev.com/blog/swift-actors-pitfalls?lang=en) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Catalogues common Swift actor pitfalls, including reentrancy and isolation misunderstandings. Use it when reviewing actor-based designs, pairing each warning with compiler diagnostics, tests, and a clear model of which state is actually protected.
- [App-Wide Theming in SwiftUI](https://www.sagarunagar.com/blog/app-wide-theming-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds an app-wide SwiftUI theming system around reusable colors, typography, and style tokens. Useful for centralizing design decisions and testing appearance variants without scattering literal values across feature views.
- [Reverse Masking in SwiftUI Using Blend Modes](https://livsycode.com/swiftui/reverse-masking-in-swiftui-using-blend-modes) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates reverse masking in SwiftUI with blend modes. Follow it for cutout or spotlight effects, separating compositing behavior from layout and checking rendering cost, color-space assumptions, and accessibility alternatives.
- [Sharing Content Among Apps Using AppEntity and Transferable Protocol](https://www.createwithswift.com/sharing-content-among-apps-using-appentity-and-transferable-protocol) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Combines AppEntity and Transferable to expose app content across system sharing surfaces. Use it when designing typed representations that can serve both App Intents discovery and drag, drop, or share operations.
- [Combine Operators Cheat Sheet](https://tanaschita.com/combine-operators-cheatsheet) — Article · Topics: Swift
  **NeKI brief:** Maps common Combine operators to transformations, filtering, combination, and scheduling behavior. Follow it when refactoring a publisher pipeline and needing to choose an operator by demand semantics rather than memorized names.
- [announced a major shift](https://skip.dev/blog/skip-is-free) — Article
  **NeKI brief:** Announces Skip as free and open source, enabling shared Swift and SwiftUI code to target additional platforms through translation. Useful for evaluating cross-platform reach, with platform-specific behavior still requiring verification.

## [Issue 250](https://thosewhoswift.substack.com/p/those-who-swift-issue-250)

- Published: `2026-01-21`

**Topics:** Swift · SwiftUI · Concurrency · AI Development · Architecture · Swift Package Manager

**Sections:** Those Who Swift · Those Who Swift - Issue 250 · Weekly note ✏️

**Selected links:**
- [recent news around Gemini integration focuses solely on Siri](https://blog.google/company-news/inside-google/company-announcements/joint-statement-google-apple) — Article · Topics: AI Development · App Intents & System Surfaces · Xcode
  **NeKI brief:** Examines recent news around Gemini integration focuses solely on Siri, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Creating and Introducing AsyncSharedStream](https://medium.com/the-swift-cooperative/creating-and-introducing-asyncsharedstream-3e9185317a5a) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Introduces an AsyncSharedStream abstraction for sharing asynchronous events among consumers. Follow it when evaluating fan-out stream design, cancellation, buffering, and termination semantics instead of assuming AsyncStream alone defines the desired policy.
- [Modern Concurrency and Legacy Code](https://www.swiftdifferently.com/blog/swift/concurrency/modern-concurrency-and-legacy-code) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Discusses integrating modern Swift concurrency with legacy callback or synchronization code. Use it when planning incremental migration, marking isolation boundaries, and preventing accidental blocking or duplicated ownership during the transition.
- [Crafting Document-Based Apps in SwiftUI](https://www.createwithswift.com/crafting-document-based-apps-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a document-based SwiftUI app around file-backed document types and scene integration. Use it when routing document lifecycle, autosave, import/export, and editing state through Apple's document architecture.
- [Foundation Models Prompting Guide](https://livsycode.com/best-practices/foundation-models-prompting-guide) — Article · Topics: AI Development
  **NeKI brief:** Provides practical prompting guidance for Apple's Foundation Models. Use it when shaping instructions, output constraints, and context boundaries for on-device generation, then validate behavior across models, locales, and failure cases.
- [Emptiness in SwiftUI](https://captainswiftui.substack.com/p/emptiness-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Reflects on empty states in SwiftUI and the design meaning of showing no content. Useful for turning absence into deliberate loading, unavailable, or recovery UI rather than leaving screens visually ambiguous.

## [Issue 249](https://thosewhoswift.substack.com/p/those-who-swift-issue-249)

- Published: `2026-01-14`

**Topics:** Swift · SwiftUI · AI Development · App Intents & System Surfaces · Xcode · Testing

**Sections:** Those Who Swift · Those Who Swift - Issue 249 · Weekly note ✏️

**Selected links:**
- [SwiftUI: Report Device Activity Visually](https://medium.com/@itsuki.enjoy/swiftui-report-device-activity-graphically-visually-73f4d76f5039) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI: Report Device Activity Visually, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Swift Programming Guide](https://github.com/peterfriese/swift-book) — Source repository · Topics: Swift · SwiftUI
  **NeKI brief:** Provides Peter Friese’s Swift book materials and examples as a public reference for learning and teaching core Swift concepts. Use it for structured study, not as version-specific API authority.
- [MVVM and Reducer Pattern in Swift](https://www.fractal-dev.com/blog/mvvm-and-reducer-pattern?lang=en) — Article · Topics: Swift · Testing
  **NeKI brief:** Examines MVVM and Reducer Pattern in Swift, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Initializing Observable Classes](https://www.youtube.com/watch?v=z0GD03x3gc4&t=1184s) — Video · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Natalia Panferova](https://nilcoalescing.com/blog/DefiningCustomStringInterpolationBehaviorInSwift) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows extending Swift string interpolation so domain types can control formatting directly inside literals. Use it when designing readable, type-directed output while keeping conversion logic centralized instead of scattering formatter calls through UI code.
- [Understanding Gesture Hierarchy in SwiftUI](https://www.createwithswift.com/understanding-gesture-hierarchy) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains SwiftUI gesture priority and how parent and child recognizers compete for touches. Useful when nested controls stop receiving input after adding a container-level gesture.

## [Issue 248](https://thosewhoswift.substack.com/p/those-who-swift-issue-248)

- Published: `2026-01-08`

**Topics:** Swift · SwiftUI · Testing · AI Development · Accessibility · Networking

**Sections:** Those Who Swift · Those Who Swift - Issue 248 · Weekly note ✏️

**Selected links:**
- [Sidebar Selection in SwiftUI](https://swiftdevjournal.com/posts/sidebar-selection) — Article · Topics: Swift · SwiftUI · Observation & State Management
  **NeKI brief:** Examines Sidebar Selection in SwiftUI, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Adaptive Sheet Presentation in SwiftUI](https://alexanderweiss.dev/blog/2025-12-30-adaptive-sheet-presentation-in-swiftui) — Article · Topics: Swift · SwiftUI · Testing
  **NeKI brief:** Examines Adaptive Sheet Presentation in SwiftUI, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Mobile Engineers, You’re All Full-Stack](https://newsletter.mobileengineer.io/p/mobile-engineers-youre-all-full-stack?r=g891u&triedRedirect=true) — Article · Topics: Networking · Persistence & Synchronisation · Testing
  **NeKI brief:** Examines Mobile Engineers, You’re All Full-Stack, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Intercepting SwiftUI Sheet Dismissal](https://livsycode.com/swiftui/intercepting-swiftui-sheet-dismissal) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows how to intercept SwiftUI sheet dismissal before allowing a modal flow to close. Follow it for unsaved-edit confirmation and validation, keeping dismissal state, cancellation, and accessibility actions consistent across interactive and programmatic paths.
- [Replay - Recording and Inspecting App Sessions](https://nshipster.com/replay) — Article
  **NeKI brief:** Presents Replay, which records HTTP exchanges as HAR files and replays them through URL loading hooks during Swift Testing. The approach keeps networking tests realistic without live servers, while the sensitive-data section makes fixture sanitization part of the design.

## [Issue 247](https://thosewhoswift.substack.com/p/those-who-swift-issue-247)

- Published: `2026-01-01`

**Topics:** Swift · Concurrency · SwiftUI · Architecture · Dependency Injection · Xcode

**Sections:** Those Who Swift · Those Who Swift - Issue 247 · Weekly note ✏️

**Selected links:**
- [Approachable Concurrency](https://github.com/swiftlang/swift-evolution/blob/main/visions/approachable-concurrency.md) — Source repository · Topics: Concurrency · Swift · Xcode
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for the vision document. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Explicit Dependency Injection Best Practices](https://livsycode.com/best-practices/explicit-dependency-injection) — Article · Topics: Architecture · Dependency Injection · Swift
  **NeKI brief:** Explains explicit dependency injection in Swift and why construction-time wiring improves testability. Use it when removing hidden singletons, defining feature boundaries, and keeping production composition separate from previews and test fixtures.
- [Override Color Scheme](https://antongubarenko.substack.com/p/swift-bits-override-color-scheme) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Examines Override Color Scheme, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [SwiftUI Zoom Navigation Transitions](https://www.sagarunagar.com/blog/swiftui-zoom-navigation-transitions) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI Zoom Navigation Transitions, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [F*** Approachable Swift Concurrency](https://fuckingapproachableswiftconcurrency.com/en) — Article · Topics: Concurrency · Swift
  **NeKI brief:** This article covers Swift concurrency through an approachable learning guide. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Introducing Jujutsu VCS](https://swiftwithmajid.com/2025/10/15/introducing-jujutsu-vcs) — Article · Topics: Swift
  **NeKI brief:** Introduces Jujutsu's change-oriented version-control model and its relationship to Git repositories. Follow it when evaluating workflows for stacked changes, mutable history, and review-friendly experimentation in Swift projects.
- [Swift coming to Android](https://www.swift.org/blog/nightly-swift-sdk-for-android) — Tutorial · Topics: Swift
  **NeKI brief:** Announces nightly Swift SDK builds for Android. Follow it when experimenting with Swift on Android and tracking toolchain progress, keeping nightly instability, package compatibility, and deployment support explicit in evaluation notes.

## [Issue 246](https://thosewhoswift.substack.com/p/those-who-swift-issue-246)

- Published: `2025-12-24`

**Topics:** Swift · SwiftUI · Concurrency · Liquid Glass · Observation & State Management · Performance

**Sections:** Those Who Swift · Those Who Swift - Issue 246 · Weekly note ✏️

**Selected links:**
- [Exploring the Swift SDK for Android](https://www.swift.org/blog/exploring-the-swift-sdk-for-android) — Article · Topics: Swift · Performance
  **NeKI brief:** Explores the Swift SDK for Android and its implications for cross-platform Swift development. Use it to understand the emerging toolchain and interoperability story, then verify supported packages, APIs, and production readiness before committing to it.
- [SwiftUI Live Activity Broadcast Push Notifications](https://medium.com/@itsuki.enjoy/swiftui-live-activity-broadcast-push-notifications-1fcf4418f87b) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI Live Activity Broadcast Push Notifications, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Stretchable Header in SwiftUI for Vertical & Horizontal ScrollView](https://livsycode.com/swiftui/stretchable-header-in-swiftui-for-vertical-and-horizontal-scrollview) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a stretchable SwiftUI header for vertical or horizontal scrolling. Use it when designing elastic hero content, carefully separating scroll geometry from visual state and testing behavior with dynamic type, rotation, and nested gestures.
- [Adding Custom HTTP Headers to WebView in SwiftUI](https://www.youtube.com/watch?v=bOFTLU3e5Ew) — Video · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Why Child State Won’t Update From Parent in SwiftUI](https://fatbobman.com/en/snippet/why-child-state-won-not-update-from-parent-in-swiftui) — Article · Topics: Swift · SwiftUI · Observation & State Management
  **NeKI brief:** Explains why a child view's @State does not automatically follow later parent changes after initialization. Useful for distinguishing owned local state from bindings and selecting the correct data-flow fix instead of forcing refreshes.
- [Implementing Consumable In-App Purchases With StoreKit 2](https://www.createwithswift.com/implementing-consumable-in-app-purchases-with-storekit-2) — Article · Topics: Swift
  **NeKI brief:** Walks through StoreKit 2 consumable purchases, transaction handling, and entitlement updates. Use it when implementing one-time consumables and ensuring verified transactions are finished only after app-side delivery succeeds.
- [Swift Concurrency](https://www.swift.org/blog/swift-6.2-released) — Article · Topics: Swift · Concurrency
  **NeKI brief:** Swift 6.2's release announcement provides the authoritative overview of language and toolchain changes. Use it to plan adoption boundaries and match compiler behavior to the released version.
- [Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.

## [Issue 245](https://thosewhoswift.substack.com/p/those-who-swift-issue-245)

- Published: `2025-12-17`

**Topics:** Swift · SwiftUI · AI Development · Concurrency · Performance · Persistence & Synchronisation

**Sections:** Those Who Swift · Those Who Swift - Issue 245 · Weekly note ✏️

**Selected links:**
- [SwiftUI Navigation Pain](https://elegantchaos.com/2025/12/12/navigation-pain.html) — Article · Topics: Swift · SwiftUI · Navigation & Deep Linking
  **NeKI brief:** Examines SwiftUI Navigation Pain, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Mastering SwiftUI — Free Guide](https://psimas.gumroad.com/l/swiftui?layout=discover&recommended_by=search&_gl=1%2A10g751b%2A_ga%2AODYxNDkzMDQzLjE3NjU2NDU4NjM.%2A_ga_6LJN6D94N6%2AczE3NjU2NDU4NjIkbzEkZzAkdDE3NjU2NDU4NjIkajYwJGwwJGgw) — Article · Topics: Swift · SwiftUI · Observation & State Management
  **NeKI brief:** Examines Mastering SwiftUI — Free Guide, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Eight Years with CloudKit](https://fatbobman.com/en/posts/my-eight-years-with-cloudkit) — Article · Topics: Performance · Persistence & Synchronisation
  **NeKI brief:** Examines Eight Years with CloudKit, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [SwiftUI: Share Wi-Fi Network Credentials With Paired Accessories](https://levelup.gitconnected.com/swiftui-share-wi-fi-network-credentials-with-paired-accessories-30004a4bf8f9) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI: Share Wi-Fi Network Credentials With Paired Accessories, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Understanding Scenes for Your macOS App](https://www.createwithswift.com/understanding-scenes-for-your-macos-app) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains macOS SwiftUI scenes and their role in app windows, settings, menu commands, and lifecycle. Use it when decomposing a desktop app beyond one WindowGroup and assigning each surface its proper scene type.
- [The Power of Ethics in Mobile Design](https://www.createwithswift.com/the-power-of-ethics-in-mobile-design) — Article · Topics: Swift
  **NeKI brief:** Examines the ethical influence mobile designers have when shaping behavior, expectations, and trust. Use it to evaluate interaction choices beyond usability and consider how product decisions affect people in everyday contexts.

## [Issue 244](https://thosewhoswift.substack.com/p/those-who-swift-issue-244)

- Published: `2025-12-11`

**Topics:** Swift · SwiftUI · AI Development · Concurrency · Performance · Persistence & Synchronisation

**Sections:** Those Who Swift · Those Who Swift - Issue 244 · Weekly note ✏️

**Selected links:**
- [Journey to Swift 6 and Strict Concurrency](https://calcopilot.app/blog/posts/swift-6-and-strict-concurrency) — Article · Topics: Concurrency · Swift · AI Development
  **NeKI brief:** Examines Journey to Swift 6 and Strict Concurrency, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [SwiftUI: Supporting Apple Pay](https://medium.com/@itsuki.enjoy/swiftui-supporting-apple-pay-bbd61fc08d5c) — Article · Topics: Swift · SwiftUI · Xcode
  **NeKI brief:** Examines SwiftUI: Supporting Apple Pay, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [What to Fix in AI-Generated Swift Code](https://www.hackingwithswift.com/articles/281/what-to-fix-in-ai-generated-swift-code) — Article · Topics: Swift · AI Development
  **NeKI brief:** Lists recurring defects in AI-written Swift and suggests concrete replacements, including unsafe assumptions around state, concurrency, and framework behavior. Follow it as a review checklist before accepting generated code into an app.
- [Monitoring App Performance with MetricKit](https://swiftwithmajid.com/2025/12/09/monitoring-app-performance-with-metrickit) — Article · Topics: Performance · Swift
  **NeKI brief:** Uses MetricKit diagnostics to move beyond the aggregate metrics in Xcode Organizer and build more detailed monitoring for crashes, hangs, launches, memory, energy, and terminations.
- [SwiftUI Book — Big Mountain Studio](https://www.bigmountainstudio.com/free-swiftui-book) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI View Picture Book (FREE), emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Designing With People: Creating Applications for Reality](https://www.createwithswift.com/designing-with-people-creating-applications-for-reality) — Article · Topics: Swift
  **NeKI brief:** Explains why applications should be designed with their communities and real-world circumstances in mind. Use it to ground product decisions in people’s needs rather than treating interface design as an isolated visual exercise.

## [Issue 243](https://thosewhoswift.substack.com/p/those-who-swift-issue-243)

- Published: `2025-12-10`

**Topics:** Swift · SwiftUI · Performance · AI Development · Xcode · Accessibility

**Sections:** Those Who Swift · Those Who Swift - Issue 243 · Weekly note ✏️

**Selected links:**
- [Initializing Observable Classes Within the SwiftUI Hierarchy](https://nilcoalescing.com/blog/InitializingObservableClassesWithinTheSwiftUIHierarchy) — Article · Topics: Swift · SwiftUI · Observation & State Management
  **NeKI brief:** Compares ownership patterns for creating @Observable reference types inside SwiftUI, including state storage and dependency injection. Useful for preventing model recreation when view identity changes.
- [Teaching AI to Read Xcode Builds](https://tuist.dev/blog/2025/11/27/teaching-ai-to-read-xcode-builds) — Article · Topics: Xcode · AI Development · Dependency Injection
  **NeKI brief:** Presents Teaching AI to Read Xcode Builds, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Organizing SwiftUI Views with TabContent and TabContentBuilder](https://livsycode.com/swiftui/organizing-swiftui-views-with-tabcontent-and-tabcontentbuilder) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains organizing SwiftUI tabs with TabContent and TabContentBuilder. Follow it when composing tab configuration declaratively, checking availability and selection state, and preserving clear navigation semantics as tab content grows.
- [SwiftUI Charts Interactivity — Part 1](https://antongubarenko.substack.com/p/swiftui-charts-interactivity-part) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI Charts Interactivity — Part 1, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Understanding the Transferable Protocol in Swift](https://www.createwithswift.com/understanding-the-transferable-protocol-in-swift) — Article · Topics: Swift
  **NeKI brief:** Explains Transferable representations and type-specific export or import formats for system sharing. Useful when designing drag, drop, paste, or share flows that support more than one data representation.

## [Issue 242](https://thosewhoswift.substack.com/p/those-who-swift-issue-242)

- Published: `2025-11-26`

**Topics:** Swift · SwiftUI · Macros & Metaprogramming · Observation & State Management · UIKit · Testing

**Sections:** Those Who Swift · Those Who Swift - Issue 242 · Weekly note ✏️

**Selected links:**
- [Building Better SwiftUI Modifiers with onGeometryChange](https://dimillian.medium.com/beyond-geometryreader-building-better-swiftui-modifiers-with-ongeometrychange-ac976e5c9107) — Article · Topics: Swift · SwiftUI · Performance
  **NeKI brief:** Examines Building Better SwiftUI Modifiers with onGeometryChange, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Enabling Selection, Double-Click & Context Menus in SwiftUI List on macOS](https://serialcoder.dev/text-tutorials/swiftui/enabling-selection-double-click-and-context-menus-in-swiftui-list-on-macos) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Examines Enabling Selection, Double-Click & Context Menus in SwiftUI List on macOS, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Swift Macros From 0 to Hero](https://levelup.gitconnected.com/swift-macros-from-0-to-hero-0-01-2ff3eac8571a) — Tutorial · Topics: Macros & Metaprogramming · Swift
  **NeKI brief:** Examines Swift Macros From 0 to Hero, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Rich Text Editing in SwiftUI Mastering Attributed Strings in iOS 26](https://www.youtube.com/watch?v=-hKpuysa6PM) — Video · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Automatic Property Observation in UIKit with @Observable](https://nilcoalescing.com/blog/AutomaticPropertyObservationInUIKitWithObservable) — Article · Topics: UIKit · Observation & State Management · Swift
  **NeKI brief:** Shows applying @Observable-style automatic property tracking outside SwiftUI, including UIKit. Use it when an imperative UI needs targeted change observation without manually maintaining a broad notification mechanism.
- [Designing Humanist Data Visualization for Mobile](https://www.createwithswift.com/designing-humanist-data-visualization-for-mobile) — Article · Topics: Accessibility · Swift
  **NeKI brief:** Explores human-centered mobile data visualization aligned with users’ needs and goals. Use it when choosing visual encodings, hierarchy, and interaction patterns that help people understand data instead of merely displaying it.
- [From iOS to Android: A Candid Look at My Real-World Journey into Dual-Platform Development](https://fatbobman.com/en/posts/from-ios-to-android) — Article
  **NeKI brief:** Reports the practical costs of extending an iOS product to Android, including feature parity, store rules, monetization, and China-specific distribution. Use it to frame platform expansion as an operational decision, not only a UI rewrite.

## [Issue 241](https://thosewhoswift.substack.com/p/those-who-swift-issue-241)

- Published: `2025-11-20`

**Topics:** Swift · Architecture · SwiftUI · Liquid Glass · Testing · UIKit

**Sections:** Those Who Swift · Those Who Swift - Issue 241 · Weekly note ✏️

**Selected links:**
- [Singletons with Swift Concurrency](https://www.massicotte.org/singletons) — Article · Topics: Swift · Concurrency · Observation & State Management
  **NeKI brief:** Explains Singletons with Swift Concurrency, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [How to Build Scalable White-Label iOS Apps: From Multi-Target to Modular Architecture](https://swiftandmemes.com/how-to-build-scalable-white-label-ios-apps-from-multi-target-to-modular-architecture) — Article · Topics: Architecture · Swift
  **NeKI brief:** Explains a white-label iOS architecture that evolves from multi-target projects toward modular components. Use it when separating brand configuration from shared features and assessing build, test, and release trade-offs.
- [Grow on iOS 26: Liquid Glass Adaptation in UIKit + SwiftUI Hybrid Architecture](https://fatbobman.com/en/posts/grow-on-ios26) — Article · Topics: Liquid Glass · Swift · SwiftUI
  **NeKI brief:** Documents Grow's iOS 26 Liquid Glass migration across UIKit and SwiftUI, including navigation refactors, sheet behavior, bar-button sizing, and CABackdropLayer side effects. Follow it for production integration pitfalls beyond sample code.
- [Task Identity in SwiftUI](https://chris.eidhof.nl/post/swiftui-task-identity) — Article · Topics: Swift · SwiftUI · Dependency Injection
  **NeKI brief:** Connects SwiftUI view identity and dependency tracking to the lifetime and restart behavior of tasks. Use it when asynchronous work appears to run with stale inputs or at unexpected times.
- [Generating Images in Swift Using Image Playground](https://swiftwithmajid.com/2025/11/11/generating-images-in-swift-using-image-playground) — Article · Topics: Swift
  **NeKI brief:** Shows generating images through Image Playground from Swift. Use it when designing the app-to-system creation flow, including prompt context, user choice, and availability handling around Apple Intelligence features.
- [Building Peer-to-Peer Sessions: Advertising and Browsing Devices](https://www.createwithswift.com/building-peer-to-peer-sessions-advertising-and-browsing-devices) — Tutorial · Topics: Swift
  **NeKI brief:** Builds peer-to-peer discovery by advertising and browsing nearby devices. Use it when a local collaboration feature needs session establishment without central infrastructure, while designing identity, invitations, and disconnect handling.

## [Issue 240](https://thosewhoswift.substack.com/p/those-who-swift-issue-240)

- Published: `2025-11-12`

**Topics:** Swift · SwiftUI · Concurrency · AI Development · Macros & Metaprogramming · Swift Package Manager

**Sections:** Those Who Swift · Those Who Swift - Issue 240 · Weekly note ✏️

**Selected links:**
- [How to Build a Modern Async/Await Location Manager in Swift](https://www.vbutko.com/articles/swift-async-await-location-manager) — Article · Topics: Concurrency · Swift · Testing
  **NeKI brief:** Examines How to Build a Modern Async/Await Location Manager in Swift, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Introducing Temporal Swift SDK: Building Durable Workflows](https://www.swift.org/blog/swift-temporal-sdk) — Article · Topics: Swift · Concurrency · Macros & Metaprogramming
  **NeKI brief:** Introduces a Temporal SDK for Swift and explains how Swift code can define durable workflows. Follow it when assessing workflow orchestration, persistence, retries, and deployment boundaries for server-side or long-running Swift services.
- [Using SwiftUI Foundation Models Transcripts to build a Chatbot](https://www.youtube.com/watch?v=cyOqYbWpQzU) — Video · Topics: AI Development · Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [SwiftUI Discardable Slider](https://open.substack.com/pub/antongubarenko/p/swiftui-discardable-slider) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI Discardable Slider, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Creative Coding: Randomness and Noise](https://www.createwithswift.com/creative-coding-randomness-and-noise) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Uses deterministic randomness and noise functions to generate creative Swift visuals. Useful for procedural backgrounds and experiments where repeatable seeds matter more than hand-authored coordinates.
- [Creating Ornaments in visionOS](https://www.createwithswift.com/creating-ornaments-in-visionos) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Introduces ornaments in visionOS and shows how they provide persistent controls around a volumetric or immersive experience. Use it when placing secondary actions spatially without obscuring content or treating visionOS surfaces like ordinary iOS toolbars.
- [Tracking Workouts With HealthKit in iOS Apps](https://www.createwithswift.com/tracking-workouts-with-healthkit-in-ios-apps) — Article · Topics: Swift
  **NeKI brief:** Shows reading and recording workout data through HealthKit. Follow it when designing authorization, quantity queries, background updates, and privacy-aware presentation of fitness information.

## [Issue 239](https://thosewhoswift.substack.com/p/those-who-swift-issue-239)

- Published: `2025-11-05`

**Topics:** Swift · AI Development · Concurrency · SwiftUI · Testing · Accessibility

**Sections:** Those Who Swift · Those Who Swift - Issue 239 · Weekly note ✏️

**Selected links:**
- [Guided Generation with Foundation Models in Swift](https://www.youtube.com/watch?v=kBwwztRY1FQ) — Video · Topics: AI Development · Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Swift Concurrency Part 2](https://www.nsvasilev.com/posts/swift-concurrency-part-2) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Examines Swift Concurrency Part 2, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Building a Custom Markdown Formatter in Swift: The Journey and Why Unit Tests Matter](https://medium.com/@majidboudaoud/building-a-custom-markdown-formatter-in-swift-the-journey-and-why-unit-tests-matter-d47a80a4847f) — Article · Topics: Swift · Testing
  **NeKI brief:** Examines Building a Custom Markdown Formatter in Swift: The Journey and Why Unit Tests Matter, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Organizing SwiftUI Views With ToolbarContent and ToolbarContentBuilder](https://livsycode.com/swiftui/organizing-swiftui-views-with-toolbarcontent-and-toolbarcontentbuilder) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows how ToolbarContent and ToolbarContentBuilder structure SwiftUI toolbars. Use it when sharing toolbar composition across screens while keeping placement, role, platform differences, and accessibility labels explicit.
- [Making Apps More Personal with Language Discovery](https://www.createwithswift.com/making-apps-more-personal-with-language-discovery) — Article · Topics: Swift
  **NeKI brief:** Shows how Language Discovery can reflect users’ languages and cultural contexts in an app experience. Use it when planning localization-aware personalization that goes beyond selecting a display language.
- [Combine Annotations and Swift Concurrency](https://www.massicotte.org/combine-annotations) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains The Problem With Combine Annotations, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.

## [Issue 238](https://thosewhoswift.substack.com/p/those-who-swift-issue-238)

- Published: `2025-10-29`

**Topics:** Swift · SwiftUI · AI Development · Concurrency · Xcode · Liquid Glass

**Sections:** Those Who Swift · Those Who Swift - Issue 238 · Weekly note ✏️

**Selected links:**
- [Announcing the Swift SDK for Android](https://www.swift.org/blog/nightly-swift-sdk-for-android) — Article · Topics: Swift · Swift Package Manager
  **NeKI brief:** Announces nightly Swift SDK builds for Android. Follow it when experimenting with Swift on Android and tracking toolchain progress, keeping nightly instability, package compatibility, and deployment support explicit in evaluation notes.
- [Concurrency Step-by-Step: Conforming to Protocols](https://www.massicotte.org/step-by-step-conforming-to-protocols) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Examines Concurrency Step-by-Step: Conforming to Protocols, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Power-Up SwiftUI Form Validation with Key Paths](https://danielsaidi.com/blog/2025/10/24/power-up-swiftui-form-validation-with-key-paths) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines Power-Up SwiftUI Form Validation with Key Paths, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [SwiftUI Custom URL Schemes](https://useyourloaf.com/blog/swiftui-custom-url-schemes) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Explains registering and handling custom URL schemes in SwiftUI. Use it when routing external links into navigation state and deciding how to validate, authenticate, and fall back from malformed deep links.
- [Exploring Widgets: Crafting Glanceable Experiences](https://www.createwithswift.com/exploring-widgets-crafting-glanceable-experiences) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explores WidgetKit timelines and glanceable design constraints for SwiftUI widgets. Follow it when deciding what data can be rendered from a snapshot and how refresh policy affects freshness and battery use.
- [Free iOS eBook: Build faster. Ship with confidence.](https://bitrise.io/whitepapers/level-up-your-ios-game-tips-for-speeding-up-your-continuous-integration) — Article
  **NeKI brief:** Discusses Save Time on Every Build and Test Run in a public developer resource. Use it to compare the author's concrete workflow and trade-offs with your project constraints, and verify any platform-specific claims against current primary documentation.

## [Issue 237](https://thosewhoswift.substack.com/p/those-who-swift-issue-237)

- Published: `2025-10-22`

**Topics:** Swift · Concurrency · SwiftUI · AI Development · Liquid Glass · Testing

**Sections:** Those Who Swift · Those Who Swift - Issue 237 · Weekly note ✏️

**Selected links:**
- [Transforming Glass Views with glassEffectID in SwiftUI](https://serialcoder.dev/text-tutorials/swiftui/transforming-glass-views-with-the-glasseffectid-modifier-in-swiftui) — Tutorial · Topics: Swift · SwiftUI · Liquid Glass
  **NeKI brief:** Presents Transforming Glass Views with the glassEffectID in SwiftUI, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [SwiftUI Custom Progress Bar With Masking](https://livsycode.com/swiftui/swiftui-custom-progress-bar-with-masking) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates a custom SwiftUI progress bar built with masking. Follow it for branded progress visuals, separating measured progress from drawing, animation, and accessibility values so the control remains meaningful without the decoration.
- [Crafting Interactive Tiles in SwiftUI](https://uvolchyk.me/blog/crafting-interactive-tiles-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines Crafting Interactive Tiles in SwiftUI, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Handle Out-of-Scope Expertise Collaboration](https://open.substack.com/pub/swiftdiscovery/p/indie-app-devs-6?r=21t43r&showWelcomeOnShare=false) — Article · Topics: Swift
  **NeKI brief:** Examines Handle Out-of-Scope Expertise Collaboration, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Getting Started With Multipeer Connectivity in Swift](https://www.createwithswift.com/getting-started-with-multipeer-connectivity-in-swift) — Article · Topics: Swift
  **NeKI brief:** Walks through discovering nearby peers and exchanging data with Multipeer Connectivity in Swift. Useful for prototyping local collaboration, device-to-device transfer, or shared experiences while reasoning about sessions, invitations, connectivity changes, and transport limitations.
- [Singletons and Swift Concurrency: Rethinking Global Mutable State](https://www.massicotte.org/singletons) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains Singletons with Swift Concurrency, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Combine Subjects vs AsyncStream in Swift](https://tanaschita.com/swift-combine-subjects-vs-asyncstream) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Compares Combine subjects with `AsyncStream`, contrasting multicasting and operator ecosystems with Swift Concurrency's cancellation-aware async iteration. Follow it when migrating event pipelines and deciding whether a stream needs replay, multiple consumers, or structured concurrency.
- [Unlock more sales with multiple payment methods](https://developer.paddle.com/concepts/sell/hosted-checkout-mobile-apps) — Article
  **NeKI brief:** Describes Paddle hosted checkout flows for selling through mobile apps. Use it to understand payment-page integration, handoff, and return handling before implementing a compliant purchase experience.

## [Issue 236](https://thosewhoswift.substack.com/p/those-who-swift-issue-236)

- Published: `2025-10-15`

**Topics:** Swift · SwiftUI · Testing · Concurrency · Liquid Glass · Performance

**Sections:** Those Who Swift · Those Who Swift - Issue 236 · Weekly note ✏️

**Selected links:**
- [Image Caching in SwiftUI](https://www.createwithswift.com/image-caching-in-swiftui) — Article · Topics: Swift · SwiftUI · Concurrency
  **NeKI brief:** Demonstrates image caching for SwiftUI content to avoid repeated downloads and decoding. Follow it when designing cache keys, memory/disk policy, and loading states for remote image-heavy screens.
- [7 Custom Progress Indicators for SwiftUI](https://medium.com/@himalimarasinghe/7-custom-progress-indicators-for-swiftui-with-code-c8c877b9c82d) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines 7 Custom Progress Indicators, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [SwiftUI Concentric Rectangle & Concentric Corners in iOS 26](https://www.youtube.com/watch?v=VFnidjiH750) — Video · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [SwiftUI: Auto-Applying Glass Styles](https://tanaschita.com/swiftui-glass-auto-apply) — Article · Topics: Swift · SwiftUI · Liquid Glass
  **NeKI brief:** Explains when SwiftUI automatically applies Liquid Glass and when explicit modifiers are required. Useful for diagnosing inconsistent material appearance across containers and platform contexts.
- [Building for Love: Creating Authentic Connections](https://www.createwithswift.com/building-for-love-creating-authentic-connections) — Article · Topics: Swift
  **NeKI brief:** Discusses product design that builds authentic connections by focusing on user emotions and intentional choices. Use it when evaluating whether an experience communicates purpose and trust rather than optimizing only for engagement.
- [Show Icons Only in SwiftUI Swipe Actions on iOS 26](https://nilcoalescing.com/blog/ShowIconsOnlyInSwiftUISwipeActionsOnIOS26) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows how iOS 26 SwiftUI swipe actions can present icons without visible button titles. Use it to create compact row actions while checking discoverability, accessibility labels, destructive styling, and whether the reduced affordance remains understandable.
- [Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [iPhone 17 Screen Sizes](https://useyourloaf.com/blog/iphone-17-screen-sizes) — Article
  **NeKI brief:** Summarizes the 2025 iPhone 17 screen sizes and their display differences. Use it when checking layout assumptions, preview coverage, and responsive constraints for devices introduced with that generation.

## [Issue 235](https://thosewhoswift.substack.com/p/those-who-swift-issue-235)

- Published: `2025-10-08`

**Topics:** Swift · SwiftUI · Performance · Testing · Liquid Glass · AI Development

**Sections:** Those Who Swift · Those Who Swift - Issue 235 · Weekly note ✏️

**Selected links:**
- [Programmatic Navigation in SwiftUI](https://www.createwithswift.com/programmatic-navigation-with-navigation-destination-in-swiftui) — Article · Topics: Swift · SwiftUI · Navigation & Deep Linking
  **NeKI brief:** Uses navigationDestination for state-driven SwiftUI navigation. Use it when routing should be expressed through typed destinations and path state instead of imperative pushes scattered across child views.
- [Adopting Liquid Glass: Experiences and Pitfalls](https://juniperphoton.substack.com/p/adopting-liquid-glass-experiences) — Article · Topics: Liquid Glass · Testing
  **NeKI brief:** Examines Adopting Liquid Glass: Experiences and Pitfalls, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [iOS 26: Foundation Model Framework - Code-Along Q&A](https://antongubarenko.substack.com/p/ios-26-foundation-model-framework-f6d) — Article · Topics: Testing · AI Development
  **NeKI brief:** Examines iOS 26: Foundation Model Framework - Code-Along Q&A, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Creating Custom Controls in SwiftUI: Learnable, Memorable, Accessible](https://www.swiftjectivec.com/creating-custom-controls-swiftui-learnable-memorable-accessibile) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines Creating Custom Controls in SwiftUI: Learnable, Memorable, Accessible, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Introducing Swift Profile Recorder](https://www.swift.org/blog/swift-profile-recorder) — Article · Topics: Swift · Performance · Swift Package Manager
  **NeKI brief:** Introduces Swift Profile Recorder for capturing runtime profiling data from Swift applications. Useful for collecting reproducible performance evidence in environments where full Instruments sessions are impractical.

## [Issue 234](https://thosewhoswift.substack.com/p/those-who-swift-issue-234)

- Published: `2025-10-01`

**Topics:** Swift · AI Development · SwiftUI · Xcode · Concurrency · Performance

**Sections:** Those Who Swift · Those Who Swift - Issue 234 · Weekly note ✏️

**Selected links:**
- [SwiftUI: Eliminating Navigation Registration](https://medium.com/the-swift-cooperative/swiftui-eliminating-navigation-registration-7339691c2887) — Article · Topics: Swift · SwiftUI · Navigation & Deep Linking
  **NeKI brief:** Examines SwiftUI: Eliminating Navigation Registration, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [AsyncSequence for Real-Time APIs](https://medium.com/@wesleymatlock/asyncsequence-for-real-time-apis-from-legacy-polling-to-swift-6-elegance-c2b8139c21e0) — Article · Topics: Concurrency · Swift · Testing
  **NeKI brief:** Examines AsyncSequence for Real-Time APIs, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Foundation Models Profiling with Xcode Instruments](https://artemnovichkov.com/blog/foundation-models-profiling-with-xcode-instruments) — Article · Topics: Performance · AI Development · Xcode
  **NeKI brief:** Examines Foundation Models Profiling with Xcode Instruments, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [An Apple Intelligence-Style Glow Effect in SwiftUI](https://livsycode.com/swiftui/an-apple-intelligence-style-glow-effect-in-swiftui) — Tutorial · Topics: Swift · SwiftUI · AI Development
  **NeKI brief:** Creates an Apple Intelligence-style glow effect in SwiftUI. Use it as a rendering experiment for animated gradients and masks, while considering GPU cost, reduced-motion preferences, contrast, and a non-animated fallback.
- [Implementing Drag-and-Drop With The SwiftUI Modifiers](https://www.createwithswift.com/implementing-drag-and-drop-with-the-swiftui-modifiers) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows SwiftUI drag-and-drop using the framework's transfer modifiers. Follow it when connecting draggable representations to drop destinations and keeping data conversion, validation, and visual feedback explicit.
- [Structuring Universal Links in iOS](https://tanaschita.com/swiftui-navigation-universal-links-architecture) — Article · Topics: Architecture · Swift · SwiftUI
  **NeKI brief:** Structures universal-link handling around SwiftUI navigation state. Use it when parsing an incoming URL, restoring a scene, and selecting a nested destination must work consistently on cold launch and while running.
- [Free iOS eBook: Build faster. Ship with confidence.](https://bitrise.io/whitepapers/level-up-your-ios-game-tips-for-speeding-up-your-continuous-integration) — Article
  **NeKI brief:** Discusses Save Time on Every Build and Test Run in a public developer resource. Use it to compare the author's concrete workflow and trade-offs with your project constraints, and verify any platform-specific claims against current primary documentation.

## [Issue 233](https://thosewhoswift.substack.com/p/those-who-swift-issue-233)

- Published: `2025-09-24`

**Topics:** Swift · Testing · SwiftUI · Architecture · App Intents & System Surfaces · Composable Architecture

**Sections:** Those Who Swift · Those Who Swift - Issue 233 · Weekly note ✏️

**Selected links:**
- [Localization Troubles With Swift PM](https://www.scottberrevoets.com/2025/09/19/localization-troubles-with-swift-pm) — Article · Topics: Swift · Swift Package Manager · Xcode
  **NeKI brief:** Examines Localization Troubles With Swift PM, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Create Interactive Snippet Shortcut Using App Intents](https://www.swiftjectivec.com/create-interactive-snippet-shortcut-in-appintents) — Article · Topics: App Intents & System Surfaces · Architecture · Dependency Injection
  **NeKI brief:** Examines Create Interactive Snippet Shortcut Using App Intents, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [The TCA Playbook: Debugging Large Reducers Without Losing Your Mind](https://medium.com/@wesleymatlock/the-tca-playbook-debugging-large-reducers-without-losing-your-mind-e8813c9c6eda) — Article · Topics: Composable Architecture · Performance · Testing
  **NeKI brief:** Examines The TCA Playbook: Debugging Large Reducers Without Losing Your Mind, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Is MVVM a bad architecture for SwiftUI?](https://www.youtube.com/watch?v=KY4jvbrlzMM) — Video · Topics: Architecture · Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [How To Use [weak self] In Swift Concurrency Tasks](https://www.donnywals.com/how-to-use-weak-self-in-swift-concurrency-tasks) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains how weak self interacts with Swift concurrency tasks and object lifetime. Use it to choose capture strategies deliberately, avoiding retain cycles without accidentally discarding work that should complete.
- [Getting Started With The Contacts Framework](https://www.createwithswift.com/getting-started-with-the-contacts-framework) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Introduces access to user contacts from SwiftUI applications. Use it to plan authorization, fetching, and presentation boundaries while keeping contact data handling explicit and privacy-conscious.

## [Issue 232](https://thosewhoswift.substack.com/p/those-who-swift-issue-232)

- Published: `2025-09-17`

**Topics:** Swift · SwiftUI · Testing · Observation & State Management · Liquid Glass · Concurrency

**Sections:** Those Who Swift · Those Who Swift - Issue 232 · Weekly note ✏️

**Selected links:**
- [SwiftUI Redraw System In Depth](https://medium.com/@matgnt/swiftui-redraw-system-in-depth-attributes-recomputation-diffing-and-observation-66b469fdcada) — Article · Topics: Swift · SwiftUI · Observation & State Management
  **NeKI brief:** Presents a concrete implementation of SwiftUI Redraw System In Depth. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.
- [The Northern Stars of Liquid Glass](https://captainswiftui.substack.com/p/the-northern-stars-of-liquid-glass) — Article · Topics: Liquid Glass · Swift · SwiftUI
  **NeKI brief:** Examines The Northern Stars of Liquid Glass, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [How To Manage View Lifecycle Events In SwiftUI](https://tanaschita.com/swiftui-view-lifecycle-events) — Article · Topics: Swift · SwiftUI · Concurrency
  **NeKI brief:** Explains SwiftUI lifecycle callbacks such as task, onAppear, and onDisappear and their execution behavior. Follow it when attaching loading or cleanup work without accidentally duplicating effects across view identity changes.
- [Swift Protocol Oriented Design: Build a Pluggable Data Source](https://blog.stackademic.com/swift-protocol-oriented-design-build-a-pluggable-data-source-57e7937312aa) — Article · Topics: Swift · Testing
  **NeKI brief:** Examines Swift Protocol Oriented Design: Build a Pluggable Data Source, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Feature Flags in Swift](https://swiftwithmajid.com/2025/09/16/feature-flags-in-swift) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows modeling feature flags in Swift and routing conditional behavior through a centralized configuration. Use it when controlling staged releases while keeping flag evaluation testable and avoiding scattered compile-time or global checks.
- [Swift 6.2 Released](https://www.swift.org/blog/swift-6.2-released) — Article · Topics: Swift · Concurrency
  **NeKI brief:** Swift 6.2's release announcement provides the authoritative overview of language and toolchain changes. Use it to plan adoption boundaries and match compiler behavior to the released version.
- [We Need to Talk About Observation](https://jaredsinclair.com/2025/09/10/observation.html) — Article · Topics: Observation & State Management · Performance
  **NeKI brief:** Explains We Need to Talk About Observation, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Turn Your Photos Into Miniature Magic With Nano Banana](https://peterfriese.dev/blog/2025/gemini-nano-banana-ios) — Article · Topics: AI Development
  **NeKI brief:** Demonstrates integrating Gemini's Nano Banana image generation into an iOS app to transform photos into miniature scenes. Useful for evaluating an image-generation feature end to end, including prompt construction, media handling, latency, and product safeguards.
- [Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [Understanding Live Activities: Visual Micro-Storytelling](https://www.createwithswift.com/understanding-live-activities-visual-micro-storytelling) — Article · Topics: Swift
  **NeKI brief:** Explains Live Activities as a visual storytelling surface driven by timely state updates. Useful for designing concise lock-screen and Dynamic Island experiences without treating them as miniature full screens.

## [Issue 231](https://thosewhoswift.substack.com/p/those-who-swift-issue-231)

- Published: `2025-09-10`

**Topics:** Swift · AI Development · SwiftUI · Concurrency · Liquid Glass · Navigation & Deep Linking

**Sections:** Those Who Swift · Those Who Swift - Issue 231 · Weekly note ✏️

**Selected links:**
- [Liquid Glass Sheets with NavigationStack & Form](https://nilcoalescing.com/blog/LiquidGlassSheetsWithNavigationStackAndForm) — Article · Topics: Liquid Glass · Swift · SwiftUI
  **NeKI brief:** Explains composing Liquid Glass sheets with NavigationStack and Form, including presentation structure and styling boundaries. Follow it when migrating modal editing flows to iOS 26 while keeping navigation titles, controls, and form content legible.
- [Using MainActor.assumeIsolated to Solve Legacy API Compatibility Issues with Swift 6](https://weekly.fatbobman.com/p/fatbobmans-swift-weekly-0101?publication_id=843693&post_id=173061745&isFreemail=true&r=21t43r&triedRedirect=true) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Examines Using MainActor.assumeIsolated to Solve Legacy API Compatibility Issues with Swift 6, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Exploring Concentricity in SwiftUI](https://www.createwithswift.com/exploring-concentricity-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explores SwiftUI concentric geometry and how nested rounded surfaces align with the system's corner treatment. Useful for custom iOS 26 cards and containers that should feel native under Liquid Glass.
- [LLM Interactive Guide](https://bbycroft.net/llm) — Article · Topics: AI Development
  **NeKI brief:** This article covers a visual, comprehensive introduction to large language models. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [SwiftUI: Text Color & Concatenation](https://antongubarenko.substack.com/p/swiftui-text-color-and-concatenation) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents SwiftUI: Text Color & Concatenation, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [When Should You Use an Actor?](https://www.massicotte.org/actors) — Article · Topics: Concurrency
  **NeKI brief:** Examines when actors are the right concurrency boundary rather than treating them as a default replacement for every mutable type. Follow it for the trade-offs around isolation, shared state, and choosing a model that makes concurrency easier to reason about.

## [Issue 230](https://thosewhoswift.substack.com/p/those-who-swift-issue-230)

- Published: `2025-09-03`

**Topics:** Swift · Testing · Swift Package Manager · Concurrency · UIKit · Xcode

**Sections:** Those Who Swift · Those Who Swift - Issue 230 · Weekly note ✏️

**Selected links:**
- [The Great Shift in Apple Development](https://captainswiftui.substack.com/p/the-great-shift-in-apple-development) — Article · Topics: Swift · SwiftUI · Architecture
  **NeKI brief:** Examines The Great Shift in Apple Development, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Switching SPM Dependencies Between Versioned and Local Development](https://tanaschita.com/spm-quick-tip-on-switching-to-local-dev) — Article · Topics: Dependency Injection · Swift · Swift Package Manager
  **NeKI brief:** Shows how to switch a Swift Package dependency between a versioned remote requirement and a local checkout during development. Use it to test package changes quickly while preserving a clean, reproducible dependency declaration for collaborators and CI.
- [Swift progres: UIKit iOS 26, FoundationModels API and SPM traits](https://www.youtube.com/watch?v=Ew101hvrWJk) — Video · Topics: AI Development · UIKit · Swift
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Treating Warnings as Errors in Swift Packages](https://useyourloaf.com/blog/treating-warnings-as-errors-in-swift-packages) — Article · Topics: Swift · Swift Package Manager
  **NeKI brief:** Configures Swift Package builds to treat warnings as errors. Use it to keep library quality gates strict, while staging adoption so existing warnings do not block unrelated migration work.
- [Building a Design System at Genius Scan](https://www.swiftbysundell.com/articles/building-a-design-system-at-genius-scan) — Article · Topics: Swift
  **NeKI brief:** Describes building a shared design system with reusable components, tokens, and constraints at Genius Scan. Useful for connecting SwiftUI component reuse to product consistency and team-scale maintenance.
- [Get Your Indie App Noticed and Featured by Journalists](https://open.substack.com/pub/swiftdiscovery/p/indie-app-devs-3) — Article · Topics: Swift
  **NeKI brief:** This Swift Discovery article discusses independent app development and the tools or practices surrounding it. Use it for practitioner perspective and idea generation, not as authoritative guidance on current Apple APIs or store policy.
- [Forget about Ruby and Fastlane installation issues!](https://github.com/codemagic-ci-cd/cli-tools) — Source repository
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [Design as Brand: The Power of Choice and Belief](https://www.createwithswift.com/design-as-brand-the-power-of-choice-and-belief) — Article · Topics: Swift
  **NeKI brief:** Shows how brand choices and messages can be communicated through application design. Use it to align visual language, interaction details, and product beliefs into a coherent user-facing identity.

## [Issue 229](https://thosewhoswift.substack.com/p/those-who-swift-issue-229)

- Published: `2025-08-27`

**Topics:** Swift · SwiftUI · Architecture · Xcode · AI Development · Dependency Injection

**Sections:** Those Who Swift · Those Who Swift - Issue 229 · Weekly note ✏️

**Selected links:**
- [Custom Animations with Timing Curves in SwiftUI: Make Your UI Rock](https://medium.com/@wesleymatlock/custom-animations-with-phaseanimator-e5134891e0b7) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines Custom Animations with Timing Curves in SwiftUI: Make Your UI Rock, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [ChatGPT in Xcode 26: is it as good as Cursor or Claude Code?](https://www.youtube.com/watch?v=BCUjW0TkaUY) — Video · Topics: Xcode · AI Development
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [What your app’s MVP needs to have?](https://swiftdiscovery.substack.com/p/indie-app-devs-2) — Article · Topics: Swift
  **NeKI brief:** Examines What your app’s MVP needs to have?, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Setting Alarms for Calendar Events](https://www.createwithswift.com/setting-alarms-for-calendar-events) — Article · Topics: Swift
  **NeKI brief:** Demonstrates adding an alarm that notifies users before a calendar event starts. Use it when modeling event reminders and deciding how notification timing should be represented and edited.
- [High-Level Anatomy of a Camera Capturing Session](https://mfaani.com/posts/ios/swiftui-camera-learnings) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines High-Level Anatomy of a Camera Capturing Session, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.

## [Issue 228](https://thosewhoswift.substack.com/p/those-who-swift-issue-228)

- Published: `2025-08-20`

**Topics:** Swift · Concurrency · AI Development · Persistence & Synchronisation · SwiftData · Liquid Glass

**Sections:** Those Who Swift · Those Who Swift - Issue 228 · Weekly note ✏️

**Selected links:**
- [How to Work with SwiftData in the Background in Swift 6](https://www.natashatherobot.com/p/swiftdata-background-swift-6) — Article · Topics: Swift · SwiftData · AI Development
  **NeKI brief:** Explains How to Work with SwiftData in the Background in Swift 6, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Make Foundation Models Deterministic: Greedy Decoding in Swift](https://www.youtube.com/watch?v=Q6x3VeGlqwg) — Video · Topics: AI Development · Swift · Testing
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Swift Sendable: A Practical Guide to Safer Concurrency](https://medium.com/@himalimarasinghe/swift-sendable-a-practical-guide-to-safer-concurrency-88826e44fd6c) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Examines Swift Sendable: A Practical Guide to Safer Concurrency, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Hidden Gems in the Swift Argument Parser – Part I](https://swifttoolkit.dev/posts/argument-parser-gems) — Article · Topics: Swift
  **NeKI brief:** Examines Hidden Gems in the Swift Argument Parser – Part I, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Getting Access to the User’s Calendar](https://www.createwithswift.com/getting-access-to-the-users-calendar) — Tutorial · Topics: Swift
  **NeKI brief:** Explains requesting access to and interacting with a user’s calendar and reminder data. Use it to separate authorization, EventKit queries, and data presentation in a SwiftUI feature.

## [Issue 227](https://thosewhoswift.substack.com/p/those-who-swift-issue-227)

- Published: `2025-08-13`

**Topics:** Swift · Concurrency · App Intents & System Surfaces · Navigation & Deep Linking · SwiftUI · AI Development

**Sections:** Those Who Swift · Those Who Swift - Issue 227 · Weekly note ✏️

**Selected links:**
- [Tuist’s AI Whitepaper](https://tuist.dev/blog/2025/08/11/tuist-ai-whitepaper) — Article · Topics: AI Development · Testing · Swift
  **NeKI brief:** Examines Tuist’s AI Whitepaper, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [NavigationStack Deep Linking in Large SwiftUI Apps](https://medium.com/@wesleymatlock/%EF%B8%8F-navigationstack-deep-linking-in-large-swiftui-apps-439a1ce77337) — Article · Topics: Navigation & Deep Linking · Swift · SwiftUI
  **NeKI brief:** Examines NavigationStack Deep Linking in Large SwiftUI Apps, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Creating Core Image Metal Shader Library in a Swift Package Plugin](https://juniperphoton.substack.com/p/creating-core-image-metal-shader) — Article · Topics: Swift · Swift Package Manager
  **NeKI brief:** Examines Creating Core Image Metal Shader Library in a Swift Package Plugin, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Designing Custom AlarmKit Interfaces in SwiftUI](https://www.createwithswift.com/designing-custom-alarmkit-interfaces-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows how to create personalized alarm interfaces with AlarmKit and SwiftUI. Use it when building alarm configuration or status screens that need system integration with a custom presentation.
- [Vibe check your code](https://coderabbit.link/ios-dt) — Article · Topics: AI Development
  **NeKI brief:** Introduces CodeRabbit’s AI-assisted code review tooling for iOS development. Use it to assess IDE review workflows, automated findings, and the boundary between generated suggestions and human approval.
- [Core Spotlight Integration for Spotlight & In-App Search](https://nilcoalescing.com/blog/CoreSpotlightIntegration) — Article · Topics: App Intents & System Surfaces
  **NeKI brief:** Shows using a shared Core Spotlight index to expose app content to system Spotlight and internal search. Useful for designing one indexing pipeline with searchable attributes, stable identifiers, updates, and deletion handling across both search surfaces.
- [Exploring the Foundation Models Framework](https://www.createwithswift.com/exploring-the-foundation-models-framework) — Article · Topics: AI Development · Swift
  **NeKI brief:** Introduces Apple's Foundation Models framework and its on-device language-model capabilities. Useful for mapping model sessions, availability, and structured generation before integrating AI into an app.

## [Issue 225](https://thosewhoswift.substack.com/p/those-who-swift-issue-225)

- Published: `2025-08-07`

**Topics:** Swift · SwiftUI · Performance · AI Development · Architecture · Liquid Glass

**Sections:** Those Who Swift · Those Who Swift - Issue 225 · Weekly note ✏️

**Selected links:**
- [Providing Multiple Accent Colors in SwiftUI Apps](https://serialcoder.dev/text-tutorials/swiftui/providing-multiple-accent-colors-in-swiftui-apps) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Shows how to provide multiple accent colors in a SwiftUI app and select them through state or settings. Useful for appearance customization while preserving semantic styling and consistent behavior across scenes.
- [What Is a Mobile Platform Engineer](https://mobilesystemdesign.substack.com/p/what-is-a-mobile-platform-engineer) — Article · Topics: Architecture · Performance
  **NeKI brief:** Examines What Is a Mobile Platform Engineer, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [SwiftUI Search Enhancements in iOS and iPadOS 26](https://nilcoalescing.com/blog/SwiftUISearchEnhancementsIniOSAndiPadOS26) — Article · Topics: Swift · SwiftUI · Liquid Glass
  **NeKI brief:** Shows iOS and iPadOS 26 SwiftUI search enhancements for placement, suggestions, and presentation. Useful for modernizing search flows without rebuilding the search field and toolbar integration.
- [Uncertain: Modeling GPS Accuracy](https://nshipster.com/uncertainty) — Article · Topics: Swift
  **NeKI brief:** Uses uncertainty as a modeling problem for noisy sensors, locations, and user behavior rather than forcing false precision into scalar values. It is useful when designing APIs that must carry confidence or probabilistic outcomes explicitly.
- [Assembler for Swift Developers](https://arturgruchala.com/assembler-for-swift-developers) — Article · Topics: Swift
  **NeKI brief:** This article covers assembly-language concepts explained for Swift developers. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.

## [Issue 226](https://thosewhoswift.substack.com/p/those-who-swift-issue-226)

- Published: `2025-08-06`

**Topics:** Swift · Concurrency · Liquid Glass · SwiftUI · AI Development · Persistence & Synchronisation

**Sections:** Those Who Swift · Those Who Swift - Issue 226 · Weekly note ✏️

**Selected links:**
- [Using Foundation Models Framework to Stream from External LLM Providers](https://www.natashatherobot.com/p/foundationmodels-streaming-external-llm) — Article · Topics: AI Development · Xcode
  **NeKI brief:** Examines Using Foundation Models Framework to Stream from External LLM Providers, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Define Scroll Edge Effect Style for a ScrollView in Liquid Glass](https://www.createwithswift.com/define-the-scroll-edge-effect-style-of-a-scroll-view-for-liquid-glass) — Article · Topics: Liquid Glass · Swift
  **NeKI brief:** Configures scroll-edge effects for Liquid Glass scroll views. Use it when content transitions into system material need deliberate visual treatment rather than inheriting an unsuitable default.
- [Swift Concurrency: Part 1](https://www.nsvasilev.com/posts/swift-concurrency-part-1) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Examines Swift Concurrency: Part 1, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Sendable, sending, and Nonsending Explained](https://fatbobman.com/en/posts/sendable-sending-nonsending) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Compares Sendable, sending, and nonsending boundaries in Swift concurrency. Use it when designing APIs that transfer values across isolation domains and need precise ownership or compiler-checking semantics.
- [SwiftUI for Mac 2025](https://troz.net/post/2025/swiftui-mac-2025) — Article · Topics: Swift · SwiftUI · Testing
  **NeKI brief:** Presents SwiftUI for Mac 2025, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Swift Observations AsyncSequence for State Changes](https://useyourloaf.com/blog/swift-observations-asyncsequence-for-state-changes) — Article · Topics: Swift · Concurrency · Observation & State Management
  **NeKI brief:** Connects Swift Observation state changes to AsyncSequence consumption. Use it when a task should react to model updates without Combine, while defining lifetime and cancellation ownership.
- [SharingGRDB Public Beta](https://www.pointfree.co/blog/posts/181-a-swiftdata-alternative-with-sqlite-cloudkit-public-beta) — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** Announces a SQLite and CloudKit synchronization alternative to SwiftData. Use it to investigate relational persistence and sync options, then verify API maturity and operational trade-offs before adoption.
- [Building for Hate: Designing for Deception](https://www.createwithswift.com/building-for-hate-designing-for-deception) — Article · Topics: Swift
  **NeKI brief:** Distinguishes persuasive interface design from manipulative deception and examines the consequences. Use it as a review prompt for dark-pattern risks in onboarding, permissions, monetization, and retention flows.
- [Understanding Swift’s @available Attribute](https://tanaschita.com/swift-available-attribute) — Article · Topics: Swift
  **NeKI brief:** Explains Swift's @available attribute for marking APIs by platform, version, deprecation, or obsolescence. Useful when evolving libraries across OS releases and writing availability annotations that communicate migration paths without accidentally hiding supported code.
- [Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.

## [Issue 224](https://thosewhoswift.substack.com/p/those-who-swift-issue-224)

- Published: `2025-07-24`

**Topics:** Swift · SwiftUI · Testing · Concurrency · Swift Package Manager · AI Development

**Sections:** Those Who Swift · Those Who Swift - Issue 224 · Weekly note ✏️

**Selected links:**
- [Approachable Concurrency in Swift Packages](https://useyourloaf.com/blog/approachable-concurrency-in-swift-packages) — Article · Topics: Concurrency · Swift · Swift Package Manager
  **NeKI brief:** Applies approachable concurrency settings to Swift packages and explains how target configuration changes diagnostics. Useful for aligning library and application migration plans.
- [Enable Horizontal and Vertical Scrolling with ScrollView](https://www.createwithswift.com/enable-horizontal-and-vertical-scrolling-with-scrollview) — Article · Topics: Swift · Performance · SwiftUI
  **NeKI brief:** Shows configuring ScrollView for both horizontal and vertical content. Follow it when building bidirectional canvases or nested scrolling layouts and needing explicit axis, sizing, and gesture decisions.
- [The Last UIKit Developer](https://dimillian.medium.com/the-last-uikit-developer-079f59e835d4) — Article · Topics: UIKit · Swift · SwiftUI
  **NeKI brief:** Examines The Last UIKit Developer, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Giving Claude Code Eyes to See Your SwiftUI Views](https://twocentstudios.com/2025/07/13/giving-claude-code-eyes-to-see-your-swiftui-views) — Article · Topics: Swift · Testing · SwiftUI
  **NeKI brief:** Presents Giving Claude Code Eyes to See Your SwiftUI Views, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Mastering Forms in SwiftUI: Sliders and Steppers](https://www.createwithswift.com/mastering-forms-in-swiftui-sliders-and-steppers) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds SwiftUI forms with Slider and Stepper controls, showing how values, labels, ranges, and formatting work together. Use it when creating adjustable settings screens that need clear feedback, sensible bounds, and accessible control descriptions.
- [Presenting Liquid Glass Sheets in SwiftUI](https://nilcoalescing.com/blog/PresentingLiquidGlassSheetsInSwiftUI) — Article · Topics: Liquid Glass · Swift · SwiftUI
  **NeKI brief:** Demonstrates presenting sheets that participate in iOS 26 Liquid Glass styling and detents. Useful for adopting system material behavior while keeping modal content and dismissal state explicit.
- [A Peek into Debugging Process](https://www.polpiella.dev/how-i-fix-bugs-in-my-apps) — Article
  **NeKI brief:** Describes an evidence-first bug-fixing workflow that captures reproduction, narrows the failing path, and adds regression coverage. Useful as a practical debugging process rather than a framework recipe.
- [Let vs Var for Struct Properties in Swift](https://www.swiftbysundell.com/articles/let-vs-var-for-swift-struct-properties) — Article · Topics: Swift
  **NeKI brief:** Examines let versus var properties in Swift structs and how immutability affects mutation and API design. Useful for choosing value semantics deliberately in models and view state.

## [Issue 223](https://thosewhoswift.substack.com/p/those-who-swift-issue-223)

- Published: `2025-07-16`

**Topics:** Swift · SwiftUI · AI Development · Macros & Metaprogramming · Accessibility · Performance

**Sections:** Those Who Swift · Those Who Swift - Issue 223 · Weekly note ✏️

**Selected links:**
- [Swift Macros in the Wild: Building Reusable SwiftUI Views with @expression](https://medium.com/%40wesleymatlock/swift-macros-in-the-wild-building-reusable-swiftui-views-with-expression-99a321b54693) — Article · Topics: Swift · Macros & Metaprogramming · SwiftUI
  **NeKI brief:** Examines Swift Macros in the Wild: Building Reusable SwiftUI Views with @expression, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Supporting Reduced Motion Accessibility in iOS](https://tanaschita.com/ios-accessibility-reduced-motion) — Article · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Shows responding to the system Reduced Motion preference in iOS, with SwiftUI-oriented implementation guidance. Follow it when animations communicate state but must be simplified or removed for motion-sensitive users.
- [Handling WebView Navigation in SwiftUI](https://www.artemnovichkov.com/blog/handling-webview-navigation-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Handles WKWebView navigation callbacks inside a SwiftUI wrapper, including coordinator delegation and policy decisions. Useful for exposing web navigation state without leaking UIKit controller details into feature views.
- [Creating and Customizing the Menu Bar of a SwiftUI App](https://www.createwithswift.com/creating-and-customizing-the-menu-bar-of-a-swiftui-app) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains creating and customizing a SwiftUI menu bar for iPadOS and macOS. Use it when deciding menu structure, commands, and platform-specific navigation behavior for a multi-platform app.

## [Issue 222](https://thosewhoswift.substack.com/p/those-who-swift-issue-222)

- Published: `2025-07-10`

**Topics:** Swift · SwiftUI · Testing · Concurrency · AI Development · Liquid Glass

**Sections:** Those Who Swift · Those Who Swift - Issue 222 · Weekly note ✏️

**Selected links:**
- [Using WebKit to Load Web Content in SwiftUI](https://www.artemnovichkov.com/blog/using-webkit-to-load-web-content-in-swiftui) — Article · Topics: Swift · SwiftUI · Concurrency
  **NeKI brief:** Integrates WebKit content loading with SwiftUI through UIViewRepresentable and a coordinator. Useful for controlled web content, navigation state, and lifecycle handling in hybrid screens.
- [Adapting Search to the Liquid Glass Design System](https://www.createwithswift.com/adapting-search-to-the-liquid-glass-design-system) — Article · Topics: Liquid Glass · Swift · SwiftUI
  **NeKI brief:** Explores search behavior within Apple’s Liquid Glass design system in SwiftUI. Use it to adapt search placement, styling, and interaction while preserving the system’s visual hierarchy.
- [Grouping Elements Within a Glass Effect Container in SwiftUI](https://www.createwithswift.com/grouping-elements-within-a-glass-effect-container-in-swiftui) — Tutorial · Topics: Swift · SwiftUI · Liquid Glass
  **NeKI brief:** Shows how to group SwiftUI views inside a glass effect container so related controls share a coherent Liquid Glass surface. Useful for designing hierarchy and spacing while avoiding a collection of visually competing individual glass elements.
- [Setting Default Actor Isolation in Xcode 26](https://www.donnywals.com/what-is-approachable-concurrency-in-xcode-26) — Article · Topics: Concurrency · Xcode
  **NeKI brief:** Explains Xcode 26's approachable concurrency settings and how default actor isolation changes migration ergonomics. Useful when staging strict concurrency adoption without immediately annotating every legacy declaration.
- [Introducing the Animatable Macro in SwiftUI](https://swiftwithmajid.com/2025/07/08/introducing-animatable-macro-in-swiftui) — Article · Topics: Macros & Metaprogramming · Swift · SwiftUI
  **NeKI brief:** Explains SwiftUI's @Animatable macro as a way to synthesize animatable-data handling for custom views. Use it when complex values should interpolate correctly without maintaining a fragile manual AnimatableData implementation.
- [CodeRabbit’s Free AI Code Reviews in your IDE—VS Code, Cursor, Windsurf](https://coderabbit.link/ios-dt) — Article · Topics: AI Development
  **NeKI brief:** Introduces CodeRabbit’s AI-assisted code review tooling for iOS development. Use it to assess IDE review workflows, automated findings, and the boundary between generated suggestions and human approval.

## [Issue 221](https://thosewhoswift.substack.com/p/those-who-swift-issue-221)

- Published: `2025-07-02`

**Topics:** Swift · AI Development · Liquid Glass · Accessibility · Concurrency · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 221 · Weekly note ✏️

**Selected links:**
- [Supporting Dynamic Type Accessibility in iOS](https://tanaschita.com/ios-accessibility-dynamic-type) — Article · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Covers Dynamic Type support in SwiftUI, including scalable text and layout testing at accessibility sizes. Follow it when fixed frames or custom typography undermine the user's selected reading scale.
- [Getting Started with Apple's Foundation Models](https://www.artemnovichkov.com/blog/getting-started-with-apple-foundation-models) — Article · Topics: AI Development · Swift
  **NeKI brief:** Examines Getting Started with Apple's Foundation Models, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Meet the Inspector View in SwiftUI](https://serialcoder.dev/text-tutorials/swiftui/meet-the-inspector-view-in-swiftui) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Examines Meet the Inspector View in SwiftUI, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [NotificationCenter.Message: A New Concurrency-Safe Notification Experience in Swift 6.2](https://fatbobman.com/en/posts/notificationcentermessage-a-new-concurrency-safe-notification-experience-in-swift-62) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Introduces Swift 6.2’s concurrency-safe NotificationCenter.Message APIs for typed notifications. Use it to replace loosely typed broadcasts and make notification payloads, isolation, and observer handling explicit.
- [Decoding Swift Types That Require Additional Data](https://www.swiftbysundell.com/articles/decoding-swift-types-that-require-additional-data) — Article · Topics: Swift
  **NeKI brief:** Shows how CodableWithConfiguration injects required data while decoding Swift types, without optionals or decoding-only wrapper types. Use it for configuration-dependent models whose inputs are unavailable in the encoded payload.
- [Grouping Liquid Glass Components Using glassEffectUnion](https://www.donnywals.com/grouping-liquid-glass-components-using-glasseffectunion-on-ios-26) — Article · Topics: Liquid Glass
  **NeKI brief:** Explains glassEffectUnion for combining multiple Liquid Glass components into one connected visual shape on iOS 26. Follow it when grouped controls should read as a single surface while retaining separate layout, interaction, and accessibility semantics.
- [Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [GitProbe](https://github.com/git-probe/gitprobe) — Source repository
  **NeKI brief:** GitProbe changes a GitHub URL into an LLM-friendly codebase view, emphasizing structure discovery before code inspection. Useful for agent-assisted repository orientation when a full clone or broad file dump is unnecessary.

## [Issue 220](https://thosewhoswift.substack.com/p/those-who-swift-issue-220)

- Published: `2025-06-25`

**Topics:** Swift · SwiftUI · Concurrency · Swift Package Manager · Liquid Glass · Xcode

**Sections:** Those Who Swift · Those Who Swift - Issue 220 · Weekly note ✏️

**Selected links:**
- [Rewriting a 12 Year Old Objective-C iOS App with Claude Code](https://twocentstudios.com/2025/06/22/vinylogue-swift-rewrite) — Article · Topics: Swift · Performance · SwiftUI
  **NeKI brief:** Examines Rewriting a 12 Year Old Objective-C iOS App with Claude Code, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Create a Swift Package from Your SwiftUI Project](https://www.youtube.com/watch?v=_KYc2wJVIDE) — Video · Topics: Swift · Swift Package Manager · SwiftUI
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Overlapping Views in SwiftUI with zIndex](https://serialcoder.dev/text-tutorials/swiftui/overlapping-views-in-swiftui-with-zindex) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates overlapping SwiftUI views with zIndex and stack composition. Useful for cards, badges, and layered controls where rendering order and hit testing must stay predictable.
- [Reverse‑Engineering Xcode’s Coding Intelligence Prompt](https://peterfriese.dev/blog/2025/reveng-xcode-coding-intelligence) — Article · Topics: Xcode · AI Development
  **NeKI brief:** Inspects Xcode's Coding Intelligence prompt to show how project context and instructions shape generated code. The reverse-engineering perspective helps teams reason about agent inputs and reproducibility while avoiding assumptions about undocumented internals.
- [What Is @concurrent in Swift 6.2?](https://www.donnywals.com/what-is-concurrent-in-swift-6-2) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Introduces the @concurrent attribute in Swift 6.2 and its relationship to actor isolation and explicitly concurrent execution. Use it when reviewing performance-sensitive code and deciding where opt-in parallel work is safe without weakening data-race guarantees.
- [Exploring a New Visual Language: Liquid Glass](https://www.createwithswift.com/exploring-a-new-visual-language-liquid-glass) — Article · Topics: Liquid Glass · Swift
  **NeKI brief:** Explores Liquid Glass as a new Apple visual language. Use it when evaluating material, hierarchy, and interaction changes before adapting an existing interface to the system design.
- [See how it works](https://www.revenuecat.com/docs/tools/paywalls-v2) — Article
  **NeKI brief:** Documents RevenueCat Paywalls 2 tooling for configuring and presenting subscription paywalls. Use it to inspect templates, purchase flows, and customization boundaries before integrating monetization into an app.

## [Issue 219](https://thosewhoswift.substack.com/p/those-who-swift-issue-219)

- Published: `2025-06-19`

**Topics:** Swift · SwiftUI · Liquid Glass · Xcode · AI Development · Concurrency

**Sections:** Those Who Swift · Those Who Swift - Issue 219 · Weekly note ✏️

**Selected links:**
- [What’s New in SwiftUI After WWDC25](https://swiftwithmajid.com/2025/06/10/what-is-new-in-swiftui-after-wwdc25) — Article · Topics: Swift · SwiftUI · Liquid Glass
  **NeKI brief:** Summarizes post-WWDC 2025 SwiftUI changes in one implementation-oriented overview. Use it to triage adoption opportunities across layout, rendering, and system integration before following specific APIs into primary documentation.
- [WebView Is Finally Coming to SwiftUI](https://danielsaidi.com/blog/2025/06/10/webview-is-finally-coming-to-swiftui) — Article · Topics: Swift · SwiftUI · Swift Package Manager
  **NeKI brief:** Discusses the emerging native SwiftUI web-view direction and its implications for replacing representable wrappers. Useful for migration planning, while verifying availability and behavior against the target SDK.
- [Bringing On‑Device AI to Your App Using Apple’s Foundation Models](https://dimillian.medium.com/bringing-on-device-ai-to-your-app-using-apples-foundation-models-8a1df297eeaa) — Article · Topics: AI Development · Swift · Xcode
  **NeKI brief:** Discusses Bringing On-Device AI to your app: Using Apple's Foundation Models in a public developer resource. Use it to compare the author's concrete workflow and trade-offs with your project constraints, and verify any platform-specific claims against current primary documentation.
- [Swift Concurrency Explained with Code Examples](https://www.avanderlee.com/concurrency/concurrent-explained-with-code-examples) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains the @concurrent attribute and how it permits parallel execution for functions otherwise isolated by default. The examples expose the safety requirements and help decide when parallelism is worth the added isolation annotations.
- [Cook Up 3D Charts with Swift Charts](https://www.artemnovichkov.com/blog/cook-up-3d-charts-with-swift-charts) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates creating three-dimensional charts with Swift Charts, covering data mapping, axes, and interactive presentation. Useful for exploring spatial analytics on Apple platforms while considering readability, camera or gesture behavior, and fallbacks for non-3D contexts.
- [Crafting Liquid Glass App Icons with Icon Composer](https://www.createwithswift.com/crafting-liquid-glass-app-icons-with-icon-composer) — Article · Topics: Liquid Glass · Swift
  **NeKI brief:** Walks through creating Liquid Glass-compatible app icons with Icon Composer. Use it when adapting assets for the new system treatment and validating how layers, materials, and icon output render in context.
- [Stretchy Header in SwiftUI](https://nilcoalescing.com/blog/StretchyHeaderInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a stretchy scrolling header with GeometryReader and visual effects tied to scroll offset. Useful for immersive detail screens while keeping the effect isolated from content layout.
- [Opting Your App Out of the Liquid Glass Redesign](https://www.donnywals.com/opting-your-app-out-of-the-liquid-glass-redesign-with-xcode-26) — Article · Topics: Liquid Glass · Xcode
  **NeKI brief:** Explains the Xcode 26 compatibility option for temporarily opting an app out of Liquid Glass styling. Use it to plan a staged visual migration, not as a long-term substitute for testing the redesigned system components.
- [See how it works](https://www.revenuecat.com/docs/tools/paywalls-v2) — Article
  **NeKI brief:** Documents RevenueCat Paywalls 2 tooling for configuring and presenting subscription paywalls. Use it to inspect templates, purchase flows, and customization boundaries before integrating monetization into an app.

## [Issue 217](https://thosewhoswift.substack.com/p/those-who-swift-issue-217)

- Published: `2025-06-18`

**Topics:** Swift · SwiftUI · App Intents & System Surfaces · Architecture · Performance · Concurrency

**Sections:** Those Who Swift · Those Who Swift - Issue 217 · Weekly note ✏️

**Selected links:**
- [Integrating App Intents with Control Action](https://www.createwithswift.com/integrating-app-intents-with-control-action) — Article · Topics: App Intents & System Surfaces · Swift · SwiftUI
  **NeKI brief:** Shows how to expose an app operation through App Intents and Control Action for system surfaces. Use it when connecting an app's domain action to Control Center or other integrations while keeping intent parameters, authorization, and state updates explicit.
- [Tips and Tricks for When Using SwiftUI’s ViewBuilder](https://www.swiftbysundell.com/articles/swiftui-viewbuilder-tips-and-tricks) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Collects ViewBuilder techniques for conditional composition, custom containers, and readable APIs. Useful when designing result-builder-based components without hiding state or type constraints.
- [Quick Guide on Toolbars in SwiftUI](https://tanaschita.com/swiftui-toolbars-guide) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Surveys SwiftUI toolbar placement, roles, and item composition across platforms. Useful for avoiding platform-specific placement surprises and keeping actions discoverable in navigation bars.
- [The Future of Design in an AI-Driven World](https://www.createwithswift.com/the-future-of-design-in-an-ai-driven-world) — Article · Topics: AI Development · Swift
  **NeKI brief:** Discusses how AI changes product and interface design responsibilities, including generated output, iteration speed, and human judgment. Useful as a strategic prompt when defining an AI-assisted design process that protects usability, authorship, and coherent product intent.
- [Unique Values in Swift: Removing Duplicates from an Array](https://www.avanderlee.com/swift/unique-values-removing-duplicates-array) — Article · Topics: Swift
  **NeKI brief:** Compares duplicate removal by Set conversion with order-preserving approaches, including their performance and Hashable requirements. The trade-off matters when uniqueness must be retained without silently changing collection order.
- [Swift at Apple: Migrating the Password Monitoring Service from Java](https://www.swift.org/blog/swift-at-apple-migrating-the-password-monitoring-service-from-java) — Article · Topics: Swift · Performance
  **NeKI brief:** Describes Apple's migration of a password-monitoring service from Java to Swift, including server-side concurrency and operational considerations. Useful as a production case study for Swift beyond client applications.
- [See how it works](https://www.revenuecat.com/docs/tools/paywalls-v2) — Article
  **NeKI brief:** Documents RevenueCat Paywalls 2 tooling for configuring and presenting subscription paywalls. Use it to inspect templates, purchase flows, and customization boundaries before integrating monetization into an app.

## [Issue 195](https://thosewhoswift.substack.com/p/those-who-swift-issue-195)

- Published: `2025-06-18`

**Topics:** Swift · Testing · SwiftUI · Xcode · Concurrency

**Sections:** Those Who Swift · Those Who Swift - Issue 195 · Swift Around the Web

**Selected links:**
- [Getting started with UI Testing for SwiftUI](https://tanaschita.com/testing-ui-swiftui-xctest-framework) — Article · Topics: Testing · Swift · SwiftUI
  **NeKI brief:** Demonstrates UI testing SwiftUI applications with XCTest, including accessibility-driven queries and interaction assertions. Useful for testing user-visible behavior without coupling tests to implementation details.
- [Learn Swift with Easy-to-Follow Code Examples](https://www.avanderlee.com/swift/swift-tutorials-learn-swift-code-examples) — Tutorial · Topics: Swift · Testing · Concurrency
  **NeKI brief:** Organizes Swift learning around language fundamentals, testing, concurrency, and UI examples, linking concepts to progressively larger exercises. The index is useful for routing a learner to the next missing prerequisite rather than repeating beginner material.
- [Adjust the intensity of colors in SwiftUI views](https://nilcoalescing.com/blog/AdjustTheIntensityOfColorsInSwiftUIViews) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Adjusts SwiftUI color intensity with platform-aware rendering controls. Use it when a design needs subtle emphasis changes without replacing semantic colors with fixed, inaccessible values.
- [Essential xcodebuild Commands for iOS Developers](https://medium.com/@awasthi027.ashish/essential-xcodebuild-commands-for-ios-developers-9ff101783ce2) — Article · Topics: Xcode · Testing
  **NeKI brief:** Examines Essential xcodebuild Commands for iOS Developers, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Why Certain View Modifiers in Swift 6 Cannot Use the @State Property](https://fatbobman.com/en/posts/why-certain-view-modifiers-in-swift-6-cannot-usethe-state-property) — Article · Topics: Swift · Concurrency · SwiftUI
  **NeKI brief:** Explains why Swift 6’s stricter concurrency and MainActor rules reject @State in some SwiftUI view modifiers. Use it to align modifier isolation and resolve issues in alignmentGuide or scrollTransition code.
- [Reading and displaying Genmoji in non-rich text formatted data context](https://www.createwithswift.com/reading-and-displaying-genmoji-in-non-rich-text-formatted-data-context) — Article · Topics: Swift
  **NeKI brief:** Shows how to read and display generated emoji in contexts that do not support rich text. Use it when preserving Genmoji content across plain strings, storage, and custom rendering.
- [Finding unused code with Periphery](https://adamwulf.me/2024/12/finding-unused-code-with-periphery) — Article · Topics: Swift
  **NeKI brief:** Presents Finding unused code with Periphery, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Creating a SwiftUI text view with tappable links](https://danielsaidi.com/blog/2024/12/18/creating-a-swiftui-text-view-with-tappable-links) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents Creating a SwiftUI text view with tappable links, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.

## [Issue 218](https://thosewhoswift.substack.com/p/those-who-swift-issue-218)

- Published: `2025-06-11`

**Topics:** Swift · SwiftUI · AI Development · Liquid Glass · Testing · Xcode

**Sections:** Those Who Swift · Those Who Swift - Issue 218 · Weekly note ✏️

**Selected links:**
- [Using AI and Cursor to Localize Xcode String Catalogs](https://danielsaidi.com/blog/2025/06/08/using-ai-and-cursor-to-localize-xcode-string-catalogs) — Article · Topics: Xcode · AI Development · Swift
  **NeKI brief:** Examines Using AI and Cursor to Localize Xcode String Catalogs, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Sharing Content in SwiftUI with ShareLink](https://serialcoder.dev/text-tutorials/swiftui/sharing-content-in-swiftui-with-sharelink) — Tutorial · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Examines Sharing Content in SwiftUI with ShareLink, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [How to Make Zoom Transition Animation in iOS 18](https://onmyway133.com/posts/how-to-make-zoom-transition-animation-in-ios-18) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines How to Make Zoom Transition Animation in iOS 18, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [SwiftUI Keyboard Toolbar Buttons](https://tanaschita.com/swiftui-keyboard-buttons) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains adding keyboard toolbar buttons to SwiftUI input flows and coordinating focus with dismissal or navigation actions. Use it when forms need explicit keyboard controls that behave consistently across fields, platforms, and accessibility interaction modes.
- [Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [Creating Animation Annotations for Custom SF Symbols](https://www.createwithswift.com/creating-animation-annotations-for-custom-sf-symbols) — Article · Topics: Swift
  **NeKI brief:** Explains adding animation annotations to custom SF Symbols. Use it when extending symbol assets with motion while keeping the animation metadata compatible with the SF Symbols toolchain.

## [Issue 216](https://thosewhoswift.substack.com/p/those-who-swift-issue-216)

- Published: `2025-05-28`

**Topics:** Swift · SwiftUI · Xcode · Accessibility · Architecture · Swift Package Manager

**Sections:** Those Who Swift · Those Who Swift - Issue 216 · Weekly note ✏️

**Selected links:**
- [Creating Xcode Source Editor Extensions](https://www.createwithswift.com/creating-xcode-source-editor-extensions) — Tutorial · Topics: Xcode · Swift · SwiftUI
  **NeKI brief:** Walks through developing and distributing Xcode source editor extensions. Use it to add focused editor automation and understand the packaging, command, and distribution requirements.
- [Understanding SwiftUI’s ViewThatFits Container](https://tanaschita.com/swiftui-viewthatfits-container) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains how ViewThatFits selects the first SwiftUI view that fits available space. Use it to build adaptive layouts that gracefully switch between alternative compositions at different widths.
- [Creating Shapes Using Path in the SwiftUI Canvas View](https://www.createwithswift.com/creating-shapes-using-path-in-the-swiftui-canvas-view) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates drawing custom shapes with Path inside SwiftUI Canvas. Follow it when rendering vector geometry efficiently or building bespoke illustrations, while separating coordinate calculations, styling, and drawing state from the surrounding view hierarchy.
- [Microapps Architecture in Swift: Scaling](https://swiftwithmajid.com/2025/05/27/microapps-architecture-in-swift-scaling) — Article · Topics: Swift · Architecture · Swift Package Manager
  **NeKI brief:** Discusses scaling a Swift microapps architecture through modular feature boundaries. Use it when a growing app needs independently developed flows without turning every module dependency into global coupling.
- [See how it works](https://www.revenuecat.com/docs/tools/paywalls-v2) — Article
  **NeKI brief:** Documents RevenueCat Paywalls 2 tooling for configuring and presenting subscription paywalls. Use it to inspect templates, purchase flows, and customization boundaries before integrating monetization into an app.

## [Issue 215](https://thosewhoswift.substack.com/p/those-who-swift-issue-215)

- Published: `2025-05-21`

**Topics:** Swift · Testing · SwiftUI · Architecture · Dependency Injection · Composable Architecture

**Sections:** Those Who Swift · Those Who Swift - Issue 215 · Weekly note ✏️

**Selected links:**
- [Ultimate Guide to Dependency Injection for Modular iOS Apps](https://swiftandmemes.com/ultimate-guide-to-dependency-injection-for-modular-ios-apps) — Article · Topics: Architecture · Dependency Injection · Swift
  **NeKI brief:** Discusses Dependency Injection for Modular iOS Apps in a public developer resource. Use it to compare the author's concrete workflow and trade-offs with your project constraints, and verify any platform-specific claims against current primary documentation.
- [Programmatically Setting Focus on SwiftUI Text Fields with FocusState](https://serialcoder.dev/text-tutorials/swiftui/programmatically-setting-focus-on-swiftui-text-fields-with-focusstate) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Examines Programmatically Setting Focus on SwiftUI Text Fields with FocusState, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Change a Map Viewpoint with MapKit](https://www.createwithswift.com/change-a-map-viewpoint-with-mapkit) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Shows changing a MapKit map viewpoint programmatically in SwiftUI, including camera positioning and state-driven updates. Useful for fitting maps to a selection or route while keeping user interaction and app-driven camera changes coordinated.
- [Getting Started with Unit Testing for iOS Development in Swift](https://www.youtube.com/watch?v=CsuUwdoVwyw) — Video · Topics: Testing · Swift
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [The Evolution of Native Engineering at Tripadvisor: Part 1](https://medium.com/tripadvisor/the-evolution-of-native-engineering-at-tripadvisor-part-1-577cc0e36ec8) — Article · Topics: Architecture · Composable Architecture · Testing
  **NeKI brief:** Traces Tripadvisor's evolution of native mobile engineering and organizational architecture. Useful as large-team context for evaluating ownership, platform investment, and migration strategy alongside SwiftUI-specific decisions.
- [Should You Use Network Connectivity Checks in Swift?](https://www.donnywals.com/should-you-use-network-connectivity-checks-in-swift) — Article · Topics: Swift
  **NeKI brief:** Examines whether explicit network connectivity checks are useful in Swift apps. Use it to distinguish reachability hints from actual request outcomes and avoid blocking networking on unreliable preflight state.
- [Exploring Creative Coding with Swift and SwiftUI](https://www.createwithswift.com/exploring-creative-coding-with-swift-and-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explores creative coding with Swift and SwiftUI through layered computational art techniques. Use it to connect declarative view composition with procedural visuals and interactive experimentation.

## [Issue 214](https://thosewhoswift.substack.com/p/those-who-swift-issue-214)

- Published: `2025-05-15`

**Topics:** Swift · SwiftUI · Testing · AI Development · App Intents & System Surfaces · Performance

**Sections:** Those Who Swift · Those Who Swift - Issue 214 · Weekly note ✏️

**Selected links:**
- [Using Model Context Protocol in iOS Apps](https://www.artemnovichkov.com/blog/using-model-context-protocol-in-ios-apps) — Article · Topics: AI Development · Swift · SwiftUI
  **NeKI brief:** Explores using Model Context Protocol from an iOS app. Follow it when assessing tool or resource integrations, keeping transport, trust, privacy, and user-consent boundaries explicit before exposing app data to external agents.
- [Building a Serial Task Executor in Swift](https://iosdevlibrary.com/building-a-serial-task-executor-in-swift) — Article · Topics: Swift · Concurrency
  **NeKI brief:** Builds a serial task executor in Swift for ordering asynchronous work. Use it when a feature needs one-at-a-time execution, checking cancellation, failure propagation, fairness, and actor isolation instead of relying on incidental task ordering.
- [Customizing an App Intent](https://www.createwithswift.com/customizing-an-app-intent) — Article · Topics: App Intents & System Surfaces · Swift
  **NeKI brief:** Shows how to customize App Intents with parameters and dialogs in SwiftUI apps. Use it when exposing app actions to system surfaces while keeping user input and confirmation meaningful.
- [A Tale of Two Custom Container APIs](https://open.substack.com/pub/captainswiftui/p/a-tale-of-two-custom-container-apis) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines A Tale of Two Custom Container APIs, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Using Core Motion Within a SwiftUI Application](https://www.createwithswift.com/using-core-motion-within-a-swiftui-application) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Introduces using Core Motion data from a SwiftUI application, including manager ownership and publishing sensor updates. Use it when building motion-aware interfaces and deciding how to handle permissions, update cadence, lifecycle, and main-thread UI delivery.
- [What's New in Swift 6.2](https://www.hackingwithswift.com/articles/277/whats-new-in-swift-6-2) — Article · Topics: Swift · Testing
  **NeKI brief:** Summarizes Swift 6.2 additions and concurrency ergonomics, highlighting practical changes for existing projects. Useful for planning an incremental toolchain update and targeted experiments.
- [Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.

## [Issue 213](https://thosewhoswift.substack.com/p/those-who-swift-issue-213)

- Published: `2025-05-07`

**Topics:** Swift · SwiftUI · Swift Package Manager · Dependency Injection · Accessibility · UIKit

**Sections:** Those Who Swift · Those Who Swift - Issue 213 · Weekly note ✏️

**Selected links:**
- [SwiftUI: How to Use Custom Fonts, Colours, and Images in a Swift Package](https://dev.jeremygale.com/swiftui-how-to-use-custom-fonts-colours-and-images-in-a-swift-package) — Article · Topics: Swift · SwiftUI · Swift Package Manager
  **NeKI brief:** Examines SwiftUI: How to Use Custom Fonts, Colours, and Images in a Swift Package, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Synthesizing Text into Speech in SwiftUI](https://www.createwithswift.com/synthesizing-text-into-speech) — Tutorial · Topics: Swift · SwiftUI · Accessibility
  **NeKI brief:** Demonstrates turning text input into spoken audio with AVFoundation in SwiftUI. Use it to design speech synthesis flows that separate text state, utterance configuration, and playback control.
- [Implementing Live Activities in a SwiftUI App](https://www.createwithswift.com/implementing-live-activities-in-a-swiftui-app) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Walks through implementing Live Activities in a SwiftUI app, from ActivityKit attributes and updates to the visible presentation. Useful for time-sensitive progress or status features that must coordinate app state, push or local updates, and lifecycle expiration.
- [Adding Dependencies to Binary Swift Packages](https://danielsaidi.com/blog/2025/05/02/adding-dependencies-to-binary-swift-packages) — Article · Topics: Dependency Injection · Swift · Swift Package Manager
  **NeKI brief:** Presents Adding dependencies to binary Swift packages, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [SwiftUI View Model Ownership](https://chris.eidhof.nl/post/swiftui-view-model) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Investigates ownership and initialization of a view model created by a SwiftUI view, including the traps around init and state storage. Use it when deciding how a view should create and retain reference-model state.
- [What's New in Swift 6.1](https://www.hackingwithswift.com/articles/276/whats-new-in-swift-6-1) — Article · Topics: Swift
  **NeKI brief:** Summarizes Swift 6.1 language and concurrency additions with migration context. Useful as a release index before evaluating compiler diagnostics and standard-library changes in an existing codebase.

## [Issue 212](https://thosewhoswift.substack.com/p/those-who-swift-issue-212)

- Published: `2025-04-30`

**Topics:** Swift · SwiftUI · Performance · Testing · Networking

**Sections:** Those Who Swift · Those Who Swift - Issue 212 · Weekly note ✏️

**Selected links:**
- [Using equatable() to Avoid the NavigationLink Pre-Build Pitfall](https://fatbobman.com/en/posts/using-equatable-to-avoid-the-navigationlink-pre-build-pitfall) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Explains how NavigationLink can pre-build destination views and how equatable() can limit unnecessary work. Use it when diagnosing navigation performance and stabilizing expensive destination construction.
- [How to profile a SwiftUI app's performance?](https://www.youtube.com/watch?v=Dyh-ymg-qAo) — Video · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [SwiftUI Label and Button Style View Modifiers](https://useyourloaf.com/blog/swiftui-label-and-button-style-view-modifiers) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows convenient SwiftUI extensions around Label and Button styles. Use it to centralize repeated control styling without duplicating modifier chains across feature views.
- [Handling App Lifecycle In SwiftUI With scenePhase](https://serialcoder.dev/text-tutorials/swiftui/handling-app-lifecycle-in-swiftui-with-scenephase) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Examines Handling App Lifecycle In SwiftUI With scenePhase, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Swift Design Patterns: Adapter](https://tanaschita.com/swift-design-patterns-adapter) — Article · Topics: Swift
  **NeKI brief:** Demonstrates the Adapter pattern in Swift for integrating third-party or legacy APIs behind clean interfaces. Use it to isolate incompatible contracts and keep application code testable.

## [Issue 211](https://thosewhoswift.substack.com/p/those-who-swift-issue-211)

- Published: `2025-04-24`

**Topics:** Swift · SwiftUI · Concurrency · Persistence & Synchronisation · Testing · Core Data

**Sections:** Those Who Swift · Those Who Swift - Issue 211 · Weekly note ✏️

**Selected links:**
- [Is There A Better AsyncButton?](https://captainswiftui.substack.com/p/is-there-a-better-asyncbutton?triedRedirect=true) — Article · Topics: Concurrency · Swift · SwiftUI
  **NeKI brief:** Compares AsyncButton designs for loading, cancellation, and repeated taps in SwiftUI. Useful when standardizing asynchronous action controls and deciding which state transitions belong in the button versus its caller.
- [Why Your SwiftUI App Is Slower Than You Think](https://medium.com/@wesleymatlock/why-your-swiftui-app-is-slower-than-you-think-c3e9bb46174b) — Article · Topics: Swift · SwiftUI · Performance
  **NeKI brief:** Examines SwiftUI rendering and scrolling costs behind Why Your SwiftUI App Is Slower Than You Think. Use it to identify identity, layout, and update-frequency risks before measuring regressions with Instruments on representative devices.
- [Building Type-Safe, High-Performance SwiftData/Core Data Models](https://fatbobman.com/en/posts/building-typesafe-highperformance-swiftdata-core-data-models) — Article · Topics: Swift · Performance · Persistence & Synchronisation
  **NeKI brief:** Explores type-safe, high-performance model design across SwiftData and Core Data, with attention to schema choices and query behavior. Use it when shaping a persistence layer that balances compile-time clarity, migration needs, and runtime performance.
- [Swift Testing Challenge: Can You Refactor This?](https://www.mobiledevdiary.com/posts/swift-testing-challange-can-you-refactor-this) — Article · Topics: Testing · Concurrency · Swift
  **NeKI brief:** Examines Swift Testing Challenge: Can You Refactor This?, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Ensure Visual Accessibility: Supporting Reduced Motion Preferences in SwiftUI](https://www.createwithswift.com/ensure-visual-accessibility-supporting-reduced-motion-preferences-in-swiftui) — Article · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Demonstrates reading the system Reduce Motion preference in SwiftUI and conditionally simplifying or removing animations. The decision preserves state changes while avoiding motion that can trigger discomfort for some users.
- [Swift Actors: What Are They For? Basics](https://blog.egesucu.com.tr/swift-actors-what-are-they-for-fd40b4264d9a) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Examines Swift Actors: What Are They For? Basics, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Reading Data from HealthKit in a SwiftUI App](https://www.createwithswift.com/reading-data-from-healthkit-in-a-swiftui-app) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Introduces reading Health app data from a SwiftUI application. Use it to plan HealthKit authorization, query boundaries, and privacy-sensitive presentation of health records.

## [Issue 210](https://thosewhoswift.substack.com/p/those-who-swift-issue-210)

- Published: `2025-04-16`

**Topics:** Swift · SwiftUI · Persistence & Synchronisation · Performance · App Intents & System Surfaces · Core Data

**Sections:** Those Who Swift · Those Who Swift - Issue 210 · Weekly Note ✏️

**Selected links:**
- [SwiftUI NavigationPath with TabView](https://tanaschita.com/swiftui-navigation-path-with-tabview) — Article · Topics: Swift · SwiftUI · Navigation & Deep Linking
  **NeKI brief:** Uses NavigationPath with TabView to preserve typed navigation state per tab. Use it when deep links and tab switching must restore the correct nested destination.
- [A Guide to the SwiftUI @Environment](https://www.devfright.com/a-guide-to-the-swiftui-environment) — Article · Topics: Swift · SwiftUI · Accessibility
  **NeKI brief:** Provides a practical tour of SwiftUI environment lookup and propagation. Useful for deciding which dependencies should be injected implicitly, how overrides work in previews, and where explicit parameters improve clarity.
- [Using Instruments to Profile a SwiftUI App](https://www.donnywals.com/using-instruments-to-profile-a-swiftui-app) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Profiles a SwiftUI app with Instruments to connect view updates and runtime cost to measured workloads. Useful for replacing assumptions about rendering performance with trace evidence.
- [Make Your App Content Show on Spotlight](https://www.createwithswift.com/make-your-app-content-show-on-spotlight) — Article · Topics: App Intents & System Surfaces · Swift
  **NeKI brief:** Shows how to index app content so it appears in Spotlight, using Apple system search integration and searchable identifiers. Follow it when exposing meaningful records beyond the app while planning updates, deletion, privacy, and deep-link behavior.
- [Using Swift’s](https://www.swiftbysundell.com/articles/using-defer-within-async-and-throwing-contexts) — Article · Topics: Swift · Concurrency · Core Data
  **NeKI brief:** Explains defer cleanup across async suspension and thrown errors. Use it when file handles, transactions, or temporary state must release reliably without duplicating cleanup paths.
- [Ways to Customize Text Color in SwiftUI](https://nilcoalescing.com/blog/ForegroundColorStyleAndTintInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Compares SwiftUI's `foregroundStyle`, `foregroundColor`, `tint`, AttributedString attributes, and text-rendering options. Use it when choosing between semantic hierarchy, control accenting, gradients, and advanced per-run text styling.

## [Issue 209](https://thosewhoswift.substack.com/p/those-who-swift-issue-209)

- Published: `2025-04-09`

**Topics:** Swift · SwiftUI · Persistence & Synchronisation · Concurrency · Testing · SwiftData

**Sections:** Those Who Swift · Those Who Swift - Issue 209 · Weekly note ✏️

**Selected links:**
- [Mastering Data Tracking and Notifications in Core Data and SwiftData](https://itnext.io/mastering-data-tracking-and-notifications-in-core-data-and-swiftdata-a21921ebfa9d?source=rss-b8c3000741------2) — Article · Topics: Swift · SwiftData · Persistence & Synchronisation
  **NeKI brief:** Examines Mastering Data Tracking and Notifications in Core Data and SwiftData, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Working With The task Modifier In SwiftUI](https://serialcoder.dev/text-tutorials/swiftui/working-with-the-task-modifier-in-swiftui) — Tutorial · Topics: Swift · SwiftUI · Concurrency
  **NeKI brief:** Examines Working With The task Modifier In SwiftUI, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [SwiftUI - Scratch to Reveal animation - Xcode 16](https://www.youtube.com/watch?v=6h3udYETzDU) — Video · Topics: Swift · SwiftUI · Xcode
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [SwiftUI Keyboard Shortcut Scope](https://useyourloaf.com/blog/swiftui-keyboard-shortcut-scope) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Configures keyboard shortcut scope in SwiftUI so commands apply only within the intended scene or view hierarchy. Useful for avoiding global shortcuts that conflict across windows or editing contexts.
- [Testing Remote iOS Push Notifications in a Simulator with simctl](https://tanaschita.com/testing-remote-push-notifications-in-ios-simulator) — Article · Topics: Testing · Xcode
  **NeKI brief:** Explains testing remote push notifications in the iOS Simulator with simctl, including preparing payloads and delivering them locally. Useful for repeatable notification QA without waiting on a production provider, while still separating simulator limits from device behavior.
- [Say Goodbye to dismiss: A State-Driven Path to More Maintainable SwiftUI](https://fatbobman.com/en/posts/say-goodbye-to-dismiss) — Article · Topics: Swift · SwiftUI · Observation & State Management
  **NeKI brief:** Reframes SwiftUI dismissal as state-driven navigation. Use it when child views imperatively dismiss themselves and ownership of presentation state becomes hard to test or reason about.
- [Create Flexible Interfaces in SwiftUI](https://www.createwithswift.com/create-flexible-interfaces-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds flexible SwiftUI interfaces that adapt to available space and content. Use it when a layout must remain usable across devices without branching into separate fixed-size view trees.
- [Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [How to Inspect .ipa Files and Secure Your iOS App from Common Mistakes](https://www.artemnovichkov.com/blog/how-to-inspect-ipa-files) — Article
  **NeKI brief:** Shows how to inspect an IPA archive for packaging details and common security mistakes. Use it during release audits to examine embedded assets, metadata, and bundled resources before distribution.
- [Structuring Spacing for Scalable Mobile UIs](https://www.mobilesystemdesign.com/blog/design-system-spacing) — Article
  **NeKI brief:** Discusses spacing tokens and rhythm as foundations of a mobile design system. Useful for translating visual rules into reusable SwiftUI layout constants instead of accumulating screen-specific padding values.

## [Issue 208](https://thosewhoswift.substack.com/p/those-who-swift-issue-208)

- Published: `2025-04-02`

**Topics:** Swift · Concurrency · SwiftUI · Performance · Persistence & Synchronisation · Architecture

**Sections:** Those Who Swift · Those Who Swift - Issue 208 · Weekly note ✏️

**Selected links:**
- [Modern URL Construction in Swift](https://www.swiftbysundell.com/articles/modern-url-construction-in-swift) — Article · Topics: Swift · Macros & Metaprogramming · Testing
  **NeKI brief:** Builds URLs with modern Foundation components rather than string concatenation. Use it when paths, query items, and percent encoding must remain correct under optional or user-provided values.
- [Building a Dependency Injection Framework](https://tanaschita.com/dependency-injection-building-lightweight-container) — Article · Topics: Architecture · Dependency Injection · Swift
  **NeKI brief:** Builds a lightweight dependency-injection container in Swift and discusses registration and resolution. Use it to evaluate a small explicit composition mechanism for app services, especially when replacing hidden singletons without introducing a framework-sized abstraction.
- [Swift 6.1 Release](https://www.swift.org/blog/swift-6.1-released) — Article · Topics: Swift · Concurrency
  **NeKI brief:** Summarizes the Swift 6.1 release and its ecosystem changes. Use it as a starting point for compiler or package upgrades, verifying source compatibility, concurrency diagnostics, and platform support against the toolchain you actually ship.
- [SwiftUI Grid, LazyVGrid, LazyHGrid Explained with Code Examples](https://www.avanderlee.com/swiftui/grid-lazyvgrid-lazyhgrid-gridviews) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Compares Grid, LazyVGrid, and LazyHGrid layout behavior, column definitions, and lazy rendering. The article helps select a grid based on content size and scrolling direction rather than treating the APIs as interchangeable.
- [Detecting Barcodes on an Image with the Vision Framework](https://www.createwithswift.com/detecting-barcodes-on-an-image-with-the-vision-framework) — Article · Topics: Swift
  **NeKI brief:** Shows how Vision’s barcode detection API identifies barcodes in images. Use it when implementing image-based scanning and deciding how detection results map into app actions.
- [Does AsyncStream Replace Combine? No.](https://levelup.gitconnected.com/does-asyncstream-replace-combine-a4fc091a8175) — Article · Topics: Concurrency · Swift
  **NeKI brief:** This article covers the boundary between AsyncStream and Combine. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Introducing swiftly 1.0](https://www.swift.org/blog/introducing-swiftly_10) — Article · Topics: Swift
  **NeKI brief:** This technical resource covers Swiftly 1.0 as a Swift toolchain manager. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.

## [Issue 207](https://thosewhoswift.substack.com/p/those-who-swift-issue-207)

- Published: `2025-03-28`

**Topics:** Swift · SwiftUI · Concurrency · Performance · Accessibility · AI Development

**Sections:** Those Who Swift · Those Who Swift - Issue 207 · Weekly note ✏️

**Selected links:**
- [SwiftUI TabView: Explained with Code Examples](https://www.avanderlee.com/swiftui/tabview-tabbed-views) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains TabView selection, tab items, styles, and state restoration for multi-section SwiftUI apps. The examples are useful for keeping navigation state explicit while adapting presentation across platforms.
- [Modal Presentation Background and Color Scheme in SwiftUI](https://nilcoalescing.com/blog/ModalPresentationBackgroundAndColorSchemeInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows custom backgrounds and explicit color-scheme control for SwiftUI sheets, popovers, and full-screen covers. Use it when modal presentation needs consistent appearance across light and dark environments.
- [Detecting Body Poses in a Live Video Feed](https://www.createwithswift.com/detecting-body-poses-in-a-live-video-feed) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Detects body poses from a live video feed with Vision. Use it when real-time camera analysis needs a clear pipeline from captured frames through inference to UI updates.
- [Tracking Down Memory Leaks with Instruments](https://www.youtube.com/watch?v=j8y-LtRV4hM) — Video · Topics: Performance · Xcode
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [ModelActor is Just Weird](https://www.massicotte.org/model-actor) — Article · Topics: Concurrency · Swift · SwiftData
  **NeKI brief:** Explains ModelActor is Just Weird, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Adapting Images and Symbols to Dynamic Type Sizes in SwiftUI](https://nilcoalescing.com/blog/AdaptingImagesAndSymbolsToDynamicTypeSizesInSwiftUI) — Article · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Uses Dynamic Type size information to adapt image and symbol sizing alongside text, rather than letting decorative controls become visually disproportionate. The approach is useful when auditing compact layouts at accessibility sizes.
- [The Simple Life(cycle) of a SwiftUI View in 2025](https://captainswiftui.substack.com/p/the-simple-lifecycle-of-a-swiftui) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Describes the lifecycle of a SwiftUI view from identity through evaluation and disappearance. Useful for placing initialization, side effects, and cleanup where their timing matches actual view lifetime.
- [Awaiting Multiple Async Tasks in Swift](https://swiftwithmajid.com/2025/03/24/awaiting-multiple-async-tasks-in-swift) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains Swift async let for concurrently starting multiple child tasks and awaiting their results. Use it when parallel work has fixed structure and needs clear cancellation and error propagation.
- [Using Proxyman to Intercept and Simulate iPhone App Network Requests](https://fatbobman.com/en/posts/using-proxyman-to-intercept-and-simulate-iphone-app-network-requests) — Article
  **NeKI brief:** Shows using Proxyman to capture HTTPS traffic, install certificates, map local responses, and mock APIs. Use it to reproduce network scenarios without changing a production server.

## [Issue 206](https://thosewhoswift.substack.com/p/those-who-swift-issue-206)

- Published: `2025-03-19`

**Topics:** Swift · SwiftUI · Persistence & Synchronisation · Core Data · SwiftData · AI Development

**Sections:** Those Who Swift · Those Who Swift - Issue 206 · Weekly note ✏️

**Selected links:**
- [Custom Environment Values in SwiftUI](https://nilcoalescing.com/blog/CustomEnvironmentValuesInSwiftUI) — Article · Topics: Swift · SwiftUI · Macros & Metaprogramming
  **NeKI brief:** Compares the pre-Xcode 16 pattern for defining SwiftUI environment keys with the @Entry macro, then shows how values flow through a view hierarchy.
- [SwiftUI: Connect Two Points with Straight Line Segments + Rounded Corners](https://levelup.gitconnected.com/swiftui-connect-two-points-with-straight-line-segments-rounded-corners-dbbad5f27ab4) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI: Connect Two Points with Straight Line Segments + Rounded Corners, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Identifying individual sounds in an audio file](https://www.createwithswift.com/identifying-individual-sounds-in-an-audio-file) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Identifies individual sounds in audio with Apple's analysis frameworks. Use it when an app must classify or segment recorded media and route time-ranged results into a user-facing workflow.
- [Placing UI Components Within the Safe Area Inset](https://www.createwithswift.com/placing-ui-components-within-the-safe-area-inset) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Uses safeAreaInset to place persistent controls while reserving layout space for content. Useful for bottom actions that should avoid overlap with scrolling content and system regions.
- [Building a MCP Server in Swift](https://adamwulf.me/2025/03/building-a-mcp-server-in-swift) — Article · Topics: Swift · AI Development
  **NeKI brief:** Describes Building a MCP Server in Swift, focusing on practical tool integration and workflow trade-offs. Use it to evaluate reproducibility, trust boundaries, and debugging steps before adopting the approach in an Xcode project.
- [Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [Understanding Existentials and Primary Associated Types in Swift](https://tanaschita.com/swift-existentials) — Article · Topics: Swift
  **NeKI brief:** Explains existentials and primary associated types for protocols with associated types. Use it to choose between existential storage and generic constraints while keeping collections flexible and type-safe.

## [Issue 205](https://thosewhoswift.substack.com/p/those-who-swift-issue-205)

- Published: `2025-03-12`

**Topics:** Swift · SwiftUI · Persistence & Synchronisation · Testing · SwiftData · Concurrency

**Sections:** Those Who Swift · Those Who Swift - Issue 205 · Weekly note ✏️

**Selected links:**
- [Stream’s Swift SDK](https://getstream.io/chat/sdk/ios) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Documents Stream’s iOS chat SDK for adding messaging experiences. Use it to assess ready-made conversation UI, client integration, and customization boundaries before building chat infrastructure yourself.
- [pre-built UI components](https://getstream.io/chat/ui-kit) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Stream's Chat UI Kit supplies prebuilt messaging interface components for iOS. Assess its customization, accessibility, state ownership, and service coupling before choosing it over an in-house chat surface.
- [UserDefaults and Observation in SwiftUI: How to Achieve Precise Responsiveness](https://itnext.io/userdefaults-and-observation-in-swiftui-how-to-achieve-precise-responsiveness-2bd8bda1568e) — Article · Topics: Swift · SwiftUI · Observation & State Management
  **NeKI brief:** Examines UserDefaults and Observation in SwiftUI: How to Achieve Precise Responsiveness, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Key Considerations Before Using SwiftData](https://fatbobman.com/en/posts/key-considerations-before-using-swiftdata) — Article · Topics: Swift · SwiftData · Persistence & Synchronisation
  **NeKI brief:** Evaluates SwiftData's practical limits before adoption. Use it when deciding whether its model, migration, query, or synchronization behavior fits a production persistence requirement.
- [Swift Testing Completion Handlers](https://useyourloaf.com/blog/swift-testing-completion-handlers) — Article · Topics: Testing · Swift · Concurrency
  **NeKI brief:** Uses a Core Data persistent-store example to replace XCTest expectations with Swift Testing’s async confirmation, explaining how to await completion-handler callbacks without blocking the test thread.
- [Picker in SwiftUI Explained with Code Examples](https://www.avanderlee.com/swiftui/picker-styles-color) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates Picker bindings and style choices such as menu, segmented, wheel, and navigation-link presentations. It connects control style to platform context and option count instead of only changing appearance.
- [Customizing Modal Presentation Background and Color Scheme in SwiftUI](https://nilcoalescing.com/blog/ModalPresentationBackgroundAndColorSchemeInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows custom backgrounds and explicit color-scheme control for SwiftUI sheets, popovers, and full-screen covers. Use it when modal presentation needs consistent appearance across light and dark environments.
- [Start Building with Stream](https://getstream.io/chat/trial) — Article · Topics: Swift
  **NeKI brief:** Explores Free In-App Messaging SDK & UI Kits for iOS/Swift, focusing on stream chat is the easiest way to add messaging to. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Rendering Pixel Art with SwiftUI](https://twocentstudios.com/2025/03/10/pixel-art-swift-ui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents Rendering Pixel Art with SwiftUI, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.

## [Issue 204](https://thosewhoswift.substack.com/p/those-who-swift-issue-204)

- Published: `2025-03-05`

**Topics:** Swift · SwiftUI · Performance · Testing · UIKit · Architecture

**Sections:** Those Who Swift · Those Who Swift - Issue 204 · Weekly note ✏️

**Selected links:**
- [Stream’s Swift SDK](https://getstream.io/chat/sdk/ios) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Documents Stream’s iOS chat SDK for adding messaging experiences. Use it to assess ready-made conversation UI, client integration, and customization boundaries before building chat infrastructure yourself.
- [pre-built UI components](https://getstream.io/chat/ui-kit) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Stream's Chat UI Kit supplies prebuilt messaging interface components for iOS. Assess its customization, accessibility, state ownership, and service coupling before choosing it over an in-house chat surface.
- [Simple Modularization Setup for a New App](https://www.manu.show/2025-02-27-simple-modularization-setup) — Article · Topics: Architecture · Swift Package Manager · Swift
  **NeKI brief:** Examines Simple Modularization Setup for a New App, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Custom Lazy List in SwiftUI with Better Performance](https://nilcoalescing.com/blog/CustomLazyListInSwiftUI) — Article · Topics: Swift · SwiftUI · Performance
  **NeKI brief:** Constructs a custom lazy list to control virtualization and layout beyond List's built-in behavior. Useful when custom scrolling visuals or cell composition require more control than standard list styles provide.
- [SwiftUI Performance - How to use UIKit](https://swiftwithmajid.com/2025/03/04/swiftui-performance-how-to-use-uikit) — Article · Topics: Swift · Performance · SwiftUI
  **NeKI brief:** Explains selectively replacing expensive SwiftUI portions with UIKit when profiling identifies a real rendering bottleneck. Useful as a measured interoperability fallback rather than a default architectural preference.
- [Adapting Widgets for Tint Mode and Dark Mode in SwiftUI](https://www.createwithswift.com/adapting-widgets-for-tint-mode-and-dark-mode-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explores widget rendering modes for tint and dark-mode device settings in SwiftUI. Use it to keep widget imagery legible and intentional across system appearance configurations.
- [Detect Focused Window on macOS](https://nilcoalescing.com/blog/DetectFocusedWindowOnMacOS) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates detecting macOS window focus with SwiftUI’s appearsActive environment value. Use it to update controls or visuals when a scene becomes active or inactive.
- [Start Building with Stream](https://getstream.io/chat/trial) — Article · Topics: Swift
  **NeKI brief:** Explores Free In-App Messaging SDK & UI Kits for iOS/Swift, focusing on stream chat is the easiest way to add messaging to. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Safer Swift: How ~Copyable Prevents Hidden Bugs](https://arturgruchala.com/safer-swift-how-copyable-prevents-hidden-bugs) — Article · Topics: Swift
  **NeKI brief:** Explains Safer Swift: How ~Copyable Prevents Hidden Bugs, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Notification Action Buttons with Images in iOS](https://nilcoalescing.com/blog/NotificationActionButtonsWithImages) — Article · Topics: Testing
  **NeKI brief:** Shows adding icons to actionable push-notification buttons with UNNotificationActionIcon. Use it to make notification actions more recognizable while checking platform and asset requirements.
- [Detecting Face Landmarks with the Vision Framework](https://www.createwithswift.com/detecting-face-landmarks-with-the-vision-framework) — Article · Topics: Swift
  **NeKI brief:** Explains using Vision to detect facial landmarks in images. Use it when mapping eyes, brows, or other features into analysis or camera experiences while handling detection failure.

## [Issue 203](https://thosewhoswift.substack.com/p/those-who-swift-issue-203)

- Published: `2025-02-26`

**Topics:** Swift · SwiftUI · Testing · Persistence & Synchronisation · SwiftData · Xcode

**Sections:** Those Who Swift · Those Who Swift - Issue 203 · Weekly note ✏️

**Selected links:**
- [SwiftUI Fundamentals: a deeper look into the framework](https://books.nilcoalescing.com/swiftui-fundamentals) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI Fundamentals: a deeper look into the framework, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Faking Value Semantics with Custom FormatStyles](https://khanlou.com/2025/02/faking-value-semantics-with-custom-formatstyles) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines Faking Value Semantics with Custom FormatStyles, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Implementing Look Around with MapKit in SwiftUI](https://www.createwithswift.com/implementing-look-around-with-mapkit-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates integrating MapKit Look Around into SwiftUI to present street-level previews for a location. Useful for place-detail experiences that need availability checks, asynchronous scene loading, and graceful fallback when imagery is unavailable.
- [Tapping on Stack Views](https://useyourloaf.com/blog/tapping-on-stack-views) — Article
  **NeKI brief:** Explains why tapping empty space in a SwiftUI stack may not trigger a gesture and how contentShape changes hit testing. Useful for reliable row and card interactions.

## [Issue 202](https://thosewhoswift.substack.com/p/those-who-swift-issue-202)

- Published: `2025-02-19`

**Topics:** Swift · SwiftUI · Testing · Concurrency · AI Development · UIKit

**Sections:** Those Who Swift · Those Who Swift - Issue 202 · Weekly note ✏️

**Selected links:**
- [Enable Multi-Finger Tap Gestures in SwiftUI](https://fatbobman.medium.com/enable-multi-finger-tap-gestures-in-swiftui-2dbfdc5c759c) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Examines Enable Multi-Finger Tap Gestures in SwiftUI, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Yielding and Debouncing in Swift Concurrency](https://swiftwithmajid.com/2025/02/18/yielding-and-debouncing-in-swift-concurrency) — Article · Topics: Swift · Concurrency
  **NeKI brief:** Explains yielding and debouncing techniques with Swift concurrency, showing how tasks can cooperate and suppress redundant work. Follow it for search, input, or event pipelines where cancellation, scheduling fairness, and latest-value behavior must be explicit.
- [Adjust the Intensity of Colors in SwiftUI Views](https://nilcoalescing.com/blog/AdjustTheIntensityOfColorsInSwiftUIViews) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Adjusts SwiftUI color intensity with platform-aware rendering controls. Use it when a design needs subtle emphasis changes without replacing semantic colors with fixed, inaccessible values.
- [How to use SceneDelegate in SwiftUI](https://tanaschita.com/swiftui-scenedelegate) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Bridges scene lifecycle behavior into SwiftUI through a scene delegate integration. Useful when an application still needs UIKit lifecycle hooks for notifications, deep links, or window coordination.
- [Creating CarPlay apps within a SwiftUI app lifecycle](https://www.createwithswift.com/creating-carplay-apps-within-a-swiftui-app-lifecyle) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains integrating a CarPlay scene into a SwiftUI application's lifecycle and scene configuration. Useful when the phone UI and vehicle experience share models but require distinct connection boundaries.
- [Enabling Interaction with Table View in SwiftUI](https://www.createwithswift.com/enabling-interaction-with-table-view-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows how to enable interaction with table-style content in SwiftUI, bridging row selection or actions into state. Use it when a table needs predictable interaction semantics and you must account for platform differences, identity, and accessibility.
- [Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [Extracting structured data from PDFs using Gemini 2.0 and Genkit](https://peterfriese.dev/blog/2025/gemini-genkit-pdf-structured-data) — Article
  **NeKI brief:** Demonstrates extracting structured data from PDFs with Gemini 2.0 and Genkit. Useful for assessing document-ingestion workflows, schema validation, and error handling before integrating model-produced fields into an app's trusted domain model.
- [Ollama: Running LLMs Locally on Your Mac](https://nshipster.com/ollama) — Article · Topics: AI Development
  **NeKI brief:** Shows how Ollama runs local language models on a Mac and exposes them to developer workflows without sending prompts to a hosted service. The trade-off is a concrete starting point for evaluating privacy, hardware, and model-quality constraints.

## [Issue 201](https://thosewhoswift.substack.com/p/those-who-swift-issue-201)

- Published: `2025-02-12`

**Topics:** Swift · SwiftUI · Testing · Xcode · Concurrency · Swift Package Manager

**Sections:** Those Who Swift · Those Who Swift - Issue 201 · Weekly note ✏️

**Selected links:**
- [Stream’s Swift SDK](https://getstream.io/chat/sdk/ios) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Documents Stream’s iOS chat SDK for adding messaging experiences. Use it to assess ready-made conversation UI, client integration, and customization boundaries before building chat infrastructure yourself.
- [pre-built UI components](https://getstream.io/chat/ui-kit) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Stream's Chat UI Kit supplies prebuilt messaging interface components for iOS. Assess its customization, accessibility, state ownership, and service coupling before choosing it over an in-house chat surface.
- [VS Code extension for Swift update](https://www.swift.org/blog/vscode-swift-2) — Article · Topics: Swift · Swift Package Manager · Testing
  **NeKI brief:** Introduces updates to the VS Code extension for Swift. Follow it when comparing editor workflows, language-server capabilities, and debugging support outside Xcode, while checking the extension and toolchain versions required by a project.
- [Parameterized Tests in Swift: Reducing Boilerplate Code](https://www.avanderlee.com/swift-testing/parameterized-tests-reducing-boilerplate-code) — Article · Topics: Testing · Swift
  **NeKI brief:** Shows how Swift Testing parameterization turns repeated assertions into one @Test with arguments, including custom types and combinations, so edge cases can be expanded without duplicating test functions.
- [Mastering Task Groups in Swift](https://swiftwithmajid.com/2025/02/11/task-cancellation-in-swift-concurrency) — Article · Topics: Swift · Concurrency
  **NeKI brief:** Demonstrates cooperative task cancellation in Swift, including checking cancellation and stopping asynchronous work promptly. Useful for preventing stale network or search results from continuing after a view disappears.
- [Displaying Tabular Data in SwiftUI Using Table View](https://www.createwithswift.com/displaying-tabular-data-in-swiftui-using-table-view) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Introduces SwiftUI Table for representing tabular data. Use it when presenting columns and rows on supported Apple platforms, while considering platform-specific behavior and data identity.
- [Start Building with Stream](https://getstream.io/chat/trial) — Article · Topics: Swift
  **NeKI brief:** Explores Free In-App Messaging SDK & UI Kits for iOS/Swift, focusing on stream chat is the easiest way to add messaging to. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.

## [Issue 200](https://thosewhoswift.substack.com/p/those-who-swift-issue-200)

- Published: `2025-02-05`

**Topics:** Swift · SwiftUI · Xcode · UIKit · AI Development · Performance

**Sections:** Those Who Swift · Those Who Swift - Issue 200 · Weekly note ✏️

**Selected links:**
- [Stream’s Swift SDK](https://getstream.io/chat/sdk/ios) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Documents Stream’s iOS chat SDK for adding messaging experiences. Use it to assess ready-made conversation UI, client integration, and customization boundaries before building chat infrastructure yourself.
- [pre-built UI components](https://getstream.io/chat/ui-kit) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Stream's Chat UI Kit supplies prebuilt messaging interface components for iOS. Assess its customization, accessibility, state ownership, and service coupling before choosing it over an in-house chat surface.
- [SwiftUI Image Playground](https://www.youtube.com/watch?v=fjtWpQGs5lU) — Video · Topics: Swift · SwiftUI · AI Development
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [The Next Chapter in Swift Build Technologies](https://www.swift.org/blog/the-next-chapter-in-swift-build-technologies) — Article · Topics: Swift · Performance
  **NeKI brief:** Discusses the direction of Swift build technologies and tooling. Use it for ecosystem context when planning build-system work, but keep implementation decisions grounded in the current Swift Package Manager and Xcode documentation.
- [SwiftUI Preferences in Swift 6](https://peterfriese.dev/blog/2025/swiftui-preferences-swift6) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains SwiftUI Preferences as an upward data channel from child views to ancestors, with Swift 6 examples. It is useful for designing reusable components that report measurements or actions without tight parent-child coupling.
- [Start Building with Stream](https://getstream.io/chat/trial) — Article · Topics: Swift
  **NeKI brief:** Explores Free In-App Messaging SDK & UI Kits for iOS/Swift, focusing on stream chat is the easiest way to add messaging to. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Drawing Maps with Swift Charts](https://www.artemnovichkov.com/blog/drawing-maps-with-swift-charts) — Article · Topics: Swift
  **NeKI brief:** Uses Swift Charts to draw map-like visualizations from coordinate data. Useful for plotting paths or geographic series when a chart is sufficient and a full map renderer would add unnecessary complexity.
- [Capture UUID Values with Regex](https://nilcoalescing.com/blog/CaptureUUIDValuesWithRegex) — Article · Topics: Swift
  **NeKI brief:** Uses Swift RegexBuilder to extract and validate UUID values with reusable typed components. Use it when parsing identifiers from user input or untrusted text without ad-hoc string operations.
- [Using SF Symbols in iOS](https://tanaschita.com/ios-sf-symbols) — Article
  **NeKI brief:** Covers SF Symbols in SwiftUI and UIKit, including layers, rendering modes, scaling, and color customization. Use it to keep iconography consistent and adaptable across interfaces.
- [Joining a List of Strings in Swift](https://www.polpiella.dev/join-list-of-strings) — Article · Topics: Swift
  **NeKI brief:** Explains using ListFormatter or formatted instead of joined for natural, localized lists of strings. Use it when composing human-readable sentences that must respect locale grammar and punctuation.

## [Issue 199](https://thosewhoswift.substack.com/p/those-who-swift-issue-199)

- Published: `2025-01-30`

**Topics:** Swift · SwiftUI · Testing · Navigation & Deep Linking · Persistence & Synchronisation · SwiftData

**Sections:** Those Who Swift · Those Who Swift - Issue 199 · Weekly note ✏️

**Selected links:**
- [Filtering SwiftData Models Using Enum](https://azamsharp.com/2025/01/23/filtering-swiftdata-models-using-enum.html) — Article · Topics: Swift · SwiftData · Persistence & Synchronisation
  **NeKI brief:** Examines Filtering SwiftData Models Using Enum, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Customizing NavigationStack Title in SwiftUI](https://tanaschita.com/switui-navigationstack-customize-title) — Article · Topics: Swift · SwiftUI · Navigation & Deep Linking
  **NeKI brief:** Explains customizing a NavigationStack title in SwiftUI and controlling title display behavior. Use it when navigation bars need product-specific hierarchy or formatting while preserving correct large-title transitions, accessibility, and back-navigation affordances.
- [Multiplatform Development for Apple Devices](https://darrylbayliss.net/multiplatform-development-for-apple-devices) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines Multiplatform Development for Apple Devices, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [SwiftUI Button Image When Pressed](https://useyourloaf.com/blog/swiftui-button-image-when-pressed) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Uses SwiftUI state and button styles to swap or animate an image while a button is pressed. Useful for immediate tactile feedback without manually tracking touch events.
- [Container relative frames in SwiftUI](https://swiftwithmajid.com/2025/01/28/container-relative-frames-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Uses container-relative frames to size SwiftUI content from its enclosing container. Use it when adaptive grids, cards, or paged layouts need proportional sizing without GeometryReader plumbing.
- [Understanding Design Systems](https://www.createwithswift.com/understanding-design-systems) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Introduces the building blocks and rationale of design systems, from reusable components to shared tokens and governance. Useful when aligning SwiftUI or UIKit implementation with product language and deciding which visual rules deserve centralized ownership.
- [Popover on iPhone in SwiftUI](https://nilcoalescing.com/blog/PopoverOniPhoneInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows iPhone popover presentation and adaptation behavior in SwiftUI. Useful for lightweight contextual actions that should not become a full navigation destination or sheet.

## [Issue 198](https://thosewhoswift.substack.com/p/those-who-swift-issue-198)

- Published: `2025-01-23`

**Topics:** Swift · SwiftUI · Architecture · Macros & Metaprogramming · Testing · Concurrency

**Sections:** Those Who Swift · Those Who Swift - Issue 198 · Weekly note ✏️

**Selected links:**
- [SwiftData CRUD Operations with ModelActor](https://brightdigit.com/tutorials/swiftdata-crud-operations-modelactor) — Tutorial · Topics: Swift · Concurrency · SwiftData
  **NeKI brief:** Examines SwiftData CRUD Operations with ModelActor, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Replacing EnvironmentKit with the new SwiftUI Entry macro](https://danielsaidi.com/blog/2025/01/11/replacing-environmentkit-with-the-entry-macro) — Article · Topics: Macros & Metaprogramming · Swift · SwiftUI
  **NeKI brief:** Examines Replacing EnvironmentKit with the new SwiftUI Entry macro, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [SwiftUI View Picture Book (FREE)](https://www.bigmountainstudio.com/free-swiftui-book) — Article · Topics: Swift · SwiftUI · Accessibility
  **NeKI brief:** Examines SwiftUI View Picture Book (FREE), emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [SwiftUI Action Menu](https://peterfriese.dev/blog/2025/swiftui-action-menu) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a reusable SwiftUI action menu with a view builder and sheet presentation, turning a one-off menu into a component with an explicit content contract. Follow it for composition patterns, not as a substitute for platform menu guidance.
- [Launch at Login Setting](https://nilcoalescing.com/blog/LaunchAtLoginSetting) — Article · Topics: Swift
  **NeKI brief:** Demonstrates registering a macOS app as a login item with SMAppService. Use it to implement an explicit launch-at-login setting while keeping user control and system preferences aligned.
- [The Synchronisation Framework](https://blog.jacobstechtavern.com/p/the-synchronisation-framework) — Article · Topics: Architecture
  **NeKI brief:** Use Swift Synchronization primitives such as Mutex and atomics for tightly scoped synchronous shared-state access, and compare them with actors based on isolation, suspension, and contention needs. Keep critical sections small, document invariants, and avoid mixing low-level synchronization casually with async workflows.

## [Issue 197](https://thosewhoswift.substack.com/p/those-who-swift-issue-197)

- Published: `2025-01-17`

**Topics:** Swift · SwiftUI · Concurrency · Observation & State Management

**Sections:** Those Who Swift · Those Who Swift - Issue 197 · Weekly note ✏️

**Selected links:**
- [Using withObservationTracking to monitor changes in @Observable properties outside SwiftUI views](https://www.polpiella.dev/observable-outside-of-a-view) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Uses withObservationTracking to observe @Observable changes outside SwiftUI views. Use it when an imperative coordinator or service needs dependency-aware callbacks without adopting Combine.
- [Handle plurals in SwiftUI Text views with inflection](https://nilcoalescing.com/blog/HandlePluralsInSwiftUITextViewsWithInflection) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Uses SwiftUI text inflection to select plural forms from localized strings. Useful for grammatical counts that must adapt to locale without embedding English-only singular/plural conditionals.
- [How to hide private information](https://www.swiftwithvincent.com/blog/how-to-hide-private-information) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines How to hide private information, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Controlling keyboard events with keys and phases](https://www.createwithswift.com/controlling-keyboard-events-with-keys-and-phases) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows handling keyboard events in SwiftUI through key values and event phases. Follow it when desktop or iPad hardware-keyboard interactions need predictable shortcuts, focus behavior, and propagation control without coupling input handling to a single view.
- [How to use cryptographic hash functions in CryptoKit for iOS security](https://tanaschita.com/swift-hash-functions) — Article · Topics: Swift
  **NeKI brief:** Uses CryptoKit hash functions for integrity and security-related fingerprints. Use it when comparing data or deriving stable digests, while distinguishing hashing from reversible encryption.
- [Solving “Main actor-isolated property can not be referenced from a Sendable closure” in Swift](https://www.donnywals.com/solving-main-actor-isolated-property-can-not-be-referenced-from-a-sendable-closure-in-swift) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Diagnoses the compiler error caused by accessing main-actor-isolated state from a Sendable closure and presents isolation-aware fixes. Use it when migrating Swift concurrency code, choosing capture strategies, and preserving actor boundaries rather than silencing diagnostics.
- [Exploring Tab View Styles in SwiftUI](https://www.createwithswift.com/exploring-tab-view-styles-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Compares SwiftUI TabView styles and their platform-specific behavior. Useful for choosing a tab presentation that matches navigation semantics instead of treating styles as purely cosmetic.
- [Creating custom SF Symbols using the SF Symbols app](https://peterfriese.dev/blog/2025/custom-sf-symbols) — Tutorial
  **NeKI brief:** Creates custom SF Symbols-style artwork and integrates it with SwiftUI symbol effects. Useful when system symbols lack a domain icon, while preserving consistent scaling and state animation.

## [Issue 196](https://thosewhoswift.substack.com/p/those-who-swift-issue-196)

- Published: `2025-01-09`

**Topics:** Swift · Testing · SwiftUI · Xcode · Networking · Concurrency

**Sections:** Those Who Swift · Those Who Swift - Issue 196 · Weekly note ✏️

**Selected links:**
- [Creating tiny utility apps with SwiftUI Previews](https://danielsaidi.com/blog/2025/01/04/creating-tiny-utility-apps-with-swiftui-previews-copy) — Article · Topics: Swift · SwiftUI · Xcode
  **NeKI brief:** Examines Creating tiny utility apps with SwiftUI Previews, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [iOSDevKit - Cheat Sheets, Posters & Infographics](https://ishtiakahmed.gumroad.com/l/iOSDevKit) — Article · Topics: Swift · SwiftUI · Xcode
  **NeKI brief:** Examines iOSDevKit - Cheat Sheets, Posters & Infographics, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Adopting Swift 6 across the app codebase](https://swiftwithmajid.com/2025/01/07/adopting-swift6-across-the-app-codebase) — Article · Topics: Swift · Concurrency
  **NeKI brief:** Describes a staged approach to adopting Swift 6 across an existing app, including strict concurrency diagnostics and incremental remediation. Useful for planning migration work by ownership boundary, measuring warning debt, and keeping delivery possible during the transition.
- [Swift Parameterized Testing](https://useyourloaf.com/blog/swift-parameterized-testing) — Article · Topics: Testing · Swift
  **NeKI brief:** Demonstrates Swift Testing’s @Test arguments with single values, Cartesian products, and zip-based pairing, showing how the Test Navigator reports each case and where the two-argument limit shapes test data design.
- [Enhance UI/UX with the confirmation dialog component](https://www.createwithswift.com/enhance-ui-ux-with-the-confirmation-dialog-component) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains using SwiftUI confirmation dialogs for action choices. Use it to present destructive or consequential options with clear labels and a predictable dismissal path.
- [Understanding opaque types and protocols with associatedtype in Swift](https://tanaschita.com/swift-opaque-types-protocols-associatedtype) — Article · Topics: Swift
  **NeKI brief:** Shows how opaque some types work with protocols that have associated types. Use it to hide concrete implementations while preserving compiler-checked relationships between returned values and protocols.
- [Codable conformance for Swift enums](https://nilcoalescing.com/blog/CodableConformanceForSwiftEnums) — Article · Topics: Swift
  **NeKI brief:** Explains synthesized and custom Codable conformance for Swift enums, including manual implementations for complex cases. Use it when serialized representations need compatibility beyond automatic coding keys.
- [Xcode 16's Buildable Folders](https://blog.makwanbk.com/how-one-new-xcode-feature-helped-my-work-project-eliminate-66k-lines-of-code) — Article · Topics: Xcode
  **NeKI brief:** Describes how an Xcode feature removed substantial generated or repetitive code from a production project. Use it to identify automation opportunities while checking the migration cost and generated-source boundaries.
