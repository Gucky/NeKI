# iOS Code Review

Third-party source index. It provides source attribution and routing metadata, not republished article content. Verify article conclusions independently before applying them.

- Archive: [https://ioscodereview.com/](https://ioscodereview.com/)
- Last collected: `2026-08-05T09:01:09Z`
- Indexed entries: **82**

## [Issue 82](https://ioscodereview.com/issues/issue-82-why-your-views-re-run-deadlines-in-review-swiftdata-behind-a-wall)

- Published: `2026-07-14T19:04:53.000Z`

**Topics:** macOS & AppKit · Observation & State Management · Persistence & Synchronisation · Swift · SwiftData · SwiftUI

**Sections:** SwiftUI: Your @Entry default may be reallocating on every access · SwiftUI: Binding(get:set:) in a body is a re-render tax · SwiftUI: Add Equatable, skip the invalidation

**NeKI brief:** Curates this edition’s code-review material on SwiftUI: Your @Entry default may be reallocating on every access, SwiftUI: Binding(get:set:) in a body is a re-render tax, and SwiftUI: Add Equatable, skip the invalidation. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [The hidden cost of unstable SwiftUI environment defaults](https://nilcoalescing.com/blog/UnstableDefaultEnvironmentValuesInSwiftUI?ref=ioscodereview.com) — Article · Topics: Swift · SwiftUI · Xcode
  **NeKI brief:** Diagnoses update churn caused by reference-typed default environment values and explains why stable defaults matter. Useful when environment injection unexpectedly invalidates views or changes identity.
- [debugging notes on two SwiftUI animation bugs](https://fatbobman.com/en/posts/debugging-notes-on-two-swiftui-animation-bugs?ref=ioscodereview.com) — Article · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Uses two concrete SwiftUI animation failures to show how declarative animation can obscure causality. Follow it when a transition or state-driven animation misbehaves and you need diagnostic observations that reveal the framework behaviour rather than only a workaround.
- [Custom bindings in SwiftUI: closures vs subscripts](https://nilcoalescing.com/blog/CustomBindingsInSwiftUIClosuresVsSubscripts?ref=ioscodereview.com) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Compares closure-based and subscript-based custom Bindings in SwiftUI, including how each expresses read and write access. Use it when designing reusable bindings and choosing an approach that keeps transformations clear, composable, and maintainable.
- [Equatable properties in @Observable classes](https://nilcoalescing.com/blog/EquatablePropertiesInObservableClasses?ref=ioscodereview.com) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Explains using equatable properties to limit Observation invalidation in reference types. Useful when expensive SwiftUI views depend on models whose unrelated mutations should not trigger recomputation.
- [SE-0526: withDeadline](https://github.com/swiftlang/swift-evolution/blob/main/proposals/0526-deadline.md?ref=ioscodereview.com) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Provides the source and change history for SE-0526: withDeadline, relevant to Concurrency and Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [Keeping SwiftData behind a boundary](https://tanaschita.com/swiftdata-persistence-boundaries?ref=ioscodereview.com) — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** Keeps SwiftData behind a persistence boundary instead of exposing models directly to SwiftUI, improving testability and reducing UI coupling to storage details.
- [first iOS 27 public beta](https://appleinsider.com/articles/26/07/13/first-ios-27-macos-27-public-betas-are-out-but-you-should-still-be-careful?ref=ioscodereview.com) — Article · Topics: macOS & AppKit · Swift · SwiftUI
  **NeKI brief:** Examines first iOS 27 public beta in the context of macOS & AppKit and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [open sourced](https://github.com/apple/swift-nio-quic?ref=ioscodereview.com) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Provides the source and change history for open sourced, relevant to Developer Tools and Swift. Inspect its implementation, open issues, and release state before adopting the approach.
- [Understanding Sendable in Swift](https://tanaschita.com/swift-concurrency-sendable?ref=ioscodereview.com) — Article · Topics: Concurrency · Swift · SwiftUI
  **NeKI brief:** Explains Sendable and the compiler's concurrency-safety model with practical Swift examples. Use it when auditing values crossing actor boundaries and deciding whether types need immutable storage, explicit conformance, or isolation instead.
- [URLRequest](https://nilcoalescing.com/blog/AsyncImageImprovementsInSwiftUIOnIOS27?ref=ioscodereview.com) — Article · Topics: Concurrency · Swift · SwiftUI
  **NeKI brief:** Covers iOS 27 AsyncImage improvements for loading behavior and presentation. Useful when replacing custom image loaders, while checking cache, cancellation, and failure semantics against the deployment target.
- [developer beta 3](https://www.macrumors.com/2026/07/06/apple-seeds-ios-27-beta-3?ref=ioscodereview.com) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines developer beta 3 in the context of Swift and SwiftUI. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [June digest](https://www.swift.org/blog/whats-new-in-swift-june-2026?ref=ioscodereview.com) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines June digest in the context of Swift and SwiftUI. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [episode 371](https://www.pointfree.co/episodes?ref=ioscodereview.com) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines episode 371 in the context of Swift and SwiftUI. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 81](https://ioscodereview.com/issues/issue-81-swiftuis-toolbars-grow-up-iphone-apps-get-resizable-and-a-community-skill-for-better-tests)

- Published: `2026-06-30T16:31:22.000Z`

**Topics:** App Distribution & Store Operations · Developer Community & Business · macOS & AppKit · Swift · SwiftUI · Testing

**NeKI brief:** Curates this edition’s code-review material on SwiftUI's Toolbars Grow Up, iPhone Apps Get Resizable, and a Community Skill for Better Tests. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [iPhone Apps Are Resizable Now, and It's Not Just for iPad](https://dev.to/arshtechpro/wwdc26-whats-new-in-swiftui-a-developers-breakdown-1333?ref=ioscodereview.com) — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Examines iPhone Apps Are Resizable Now, and It's Not Just for iPad in the context of Apple Platform Ecosystem and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [SwiftUI's Toolbars Get Actual Overflow Logic](https://swiftwithmajid.com/2026/06/23/taking-control-of-toolbar-items-in-swiftui?ref=ioscodereview.com) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explores newer SwiftUI toolbar controls for styling the UI control layer separately from content, an important distinction in the current design language. Follow it when toolbar placement and appearance must remain predictable across platforms.
- [A Community Agent Skill for Swift Testing](https://github.com/twostraws/Swift-Testing-Agent-Skill?ref=ioscodereview.com) — Source repository · Topics: Developer Community & Business · Swift · Testing
  **NeKI brief:** Provides the source and change history for A Community Agent Skill for Swift Testing, relevant to Developer Community & Business and Swift. Inspect its implementation, open issues, and release state before adopting the approach.

## [Issue 80](https://ioscodereview.com/issues/issue-80-wwdc26-lands-agentic-xcode-new-swiftui-toys)

- Published: `2026-06-15T17:08:20.000Z`

**Topics:** AI Development · macOS & AppKit · Swift · SwiftUI · UIKit · Xcode

**NeKI brief:** Curates this edition’s code-review material on WWDC26 Lands, Agentic Xcode, and New SwiftUI Toys. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Using Xcode 27's Agent Skills in Claude, Codex, and Cursor](https://www.avanderlee.com/ai-development/using-xcode-27s-agent-skills-in-claude-codex-and-cursor?ref=ioscodereview.com) — Article · Topics: Swift · SwiftUI · Xcode
  **NeKI brief:** Demonstrates exporting Xcode 27 agent skills for Claude, Codex, and Cursor, then invoking the same reusable guidance across tools. It addresses portability and setup trade-offs when teams want consistent AI-assisted Swift development workflows.
- [Foundation Models can now swap providers](https://www.techtimes.com/articles/318039/20260609/wwdc-2026-developer-tools-foundation-models-now-swaps-ai-providers-without-code-changes.htm?ref=ioscodereview.com) — Article · Topics: AI Development · Foundation & Data Formats · Xcode
  **NeKI brief:** Examines Foundation Models can now swap providers in the context of AI Development and Foundation & Data Formats. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Evaluations framework](https://app.daily.dev/posts/wwdc26-meet-the-evaluations-framework-apple-e7e4p4zb5?ref=ioscodereview.com) — Article · Topics: AI Development · Apple Platform Ecosystem · Xcode
  **NeKI brief:** Examines Evaluations framework in the context of AI Development and Apple Platform Ecosystem. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [What is new in SwiftUI after WWDC26](https://swiftwithmajid.com/2026/06/08/what-is-new-in-swiftui-after-wwdc26?ref=ioscodereview.com) — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Summarizes SwiftUI additions after WWDC 2026. Use it to discover relevant new layout, rendering, and system-integration capabilities before narrowing to one feature and reading its authoritative API documentation.
- [WWDC 2026 - What's New in Swift](https://dev.to/arshtechpro/wwdc-2026-whats-new-in-swift-3nb2?ref=ioscodereview.com) — Article · Topics: Apple Platform Ecosystem · Swift · Testing
  **NeKI brief:** Summarises WWDC 2026 - What's New in Swift for Apple Platform Ecosystem and Swift. Use it to identify the relevant changes and follow its primary links before relying on version-sensitive details.

## [Issue 79](https://ioscodereview.com/issues/issue-79-defer-done-right-instruments-is-back-and-wwdc-is-one-week-away)

- Published: `2026-06-01T16:27:14.000Z`

**Topics:** Apple Platform Ecosystem · macOS & AppKit · Performance · Swift · SwiftUI · UIKit

**NeKI brief:** Curates this edition’s code-review material on defer Done Right, Instruments is Back, and WWDC Is One Week Away. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Using Xcode Instruments to optimize Swift Concurrency CodeExplore how Xcode Instruments can help you analyze, debug, and optimize your code for better app performance.SwiftLeeAntoine van der Lee](https://www.avanderlee.com/concurrency/using-xcode-instruments-to-optimize-swift-concurrency-code?ref=ioscodereview.com) — Article · Topics: Concurrency · Performance · Swift
  **NeKI brief:** Uses Instruments’ concurrency and time-based views to correlate task execution with latency, then validates a change with a second recording. The workflow is a practical guard against optimizing async code from source inspection alone.
- [Understanding basic animations in SwiftUILearn different options to animate SwiftUI views in your iOS applications. Understand the two animation options animation(_:value:) view modifier and the withAnimation(_:_:) global function.](https://tanaschita.com/swiftui-basic-animations?ref=ioscodereview.com) — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Introduces SwiftUI's state-driven animation model through basic transitions and modifiers. Follow it when mapping a state change to a visual effect and checking which view values actually participate in interpolation.
- [MacRumors + 2](https://www.macrumors.com/2026/05/18/apple-design-award-finalists-2026?ref=ioscodereview.com) — Article · Topics: Architecture · Composable Architecture · Testing
  **NeKI brief:** Examines MacRumors + 2 in the context of Architecture and Composable Architecture. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [AppleInsider](https://appleinsider.com/articles/26/05/18/apple-design-awards-2026-finalists-include-cyberpunk-2077-civilization-vii?ref=ioscodereview.com) — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games
  **NeKI brief:** Examines AppleInsider in the context of Apple Platform Ecosystem and Graphics, Media & Games. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [TUAW](https://www.tuaw.com/2026/05/19/apple-design-awards-2026-finalists-revealed?ref=ioscodereview.com) — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games
  **NeKI brief:** Examines TUAW in the context of Apple Platform Ecosystem and Graphics, Media & Games. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Deprecating your own convenience APIAlmost after every major update of iOS, we got new APIs that we use on the most recent platform but can’t use on the previous one. Usually, I solve this kind of thing by introducing my own convenience code that runs new APIs on the available versions and my custom implementation or stubs on old platform versions.Swift with MajidMajid Jabrayilov](http://swiftwithmajid.com/2026/05/19/deprecating-your-own-convenience-api?ref=ioscodereview.com) — Article · Topics: Swift
  **NeKI brief:** Explains deprecating a convenience API with migration messages and replacement paths. Use it when evolving an internal or public Swift interface while keeping callers compiling and making the preferred alternative discoverable.
- [Swift Defer. Clean up before you leave.You may think about defer keyword as one of the most ambiguous language features in Swift, but it is very useful in some cases. You can use it deliberately, and it will give you safety. This week we will talk about some best practices of using defer in Swift.Swift with MajidMajid Jabrayilov](https://swiftwithmajid.com/2026/05/26/swift-defer-clean-up-before-you-leave?ref=ioscodereview.com) — Article · Topics: Swift
  **NeKI brief:** Treats defer as deliberate scope cleanup rather than mysterious syntax, emphasizing multiple exits and readable ownership. It is a useful review checklist for ensuring release, rollback, or state-restoration work runs on every path.

## [Issue 78](https://ioscodereview.com/issues/issue-78-the-paste-bug-is-dead-bottom-sheets-done-right-and-wwdc-is-30-days-away)

- Published: `2026-05-16T17:59:28.000Z`

**Topics:** Apple Platform Ecosystem · Concurrency · macOS & AppKit · Swift · SwiftUI · UIKit

**NeKI brief:** Curates this edition’s code-review material on The Paste Bug Is Dead, Bottom Sheets Done Right, and WWDC Is 30 Days Away. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Building a draggable bottom sheet in SwiftUI](https://tanaschita.com/swiftui-draggable-bottom-sheet?ref=ioscodereview.com) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a draggable SwiftUI bottom sheet with gesture state, detents, and snapping decisions. Useful for custom interaction when system sheets do not expose the required presentation behavior.
- [How to implement pagination with SwiftUI's List view](https://tanaschita.com/swiftui-list-pagination?ref=ioscodereview.com) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Implements incremental pagination in SwiftUI List as the user approaches the end of loaded content. Use it when an async data source needs explicit loading, error, and duplicate-request guards rather than eager full retrieval.
- [Install Swift 6.3.1 — Swift.org](https://www.swift.org/install?ref=ioscodereview.com) — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **NeKI brief:** Examines Install Swift 6.3.1 — Swift.org in the context of Cross-Platform & Web and Objective-C & Cocoa. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Swift.orgSwift is a general-purpose programming language built using a modern approach to safety, performance, and software design patterns.Swift.orgApple Inc.](https://www.swift.org/install/windows?ref=ioscodereview.com) — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **NeKI brief:** Examines Swift.orgSwift is a general-purpose programming language built using a modern approach to safety, performance… in the context of Cross-Platform & Web and Objective-C & Cocoa. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Checking accessibility with SwiftUI Previews](https://mobilea11y.com/blog/swiftui-preview-testing?ref=ioscodereview.com) — Article · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Uses SwiftUI previews as an accessibility testing surface, checking labels, traits, and contrast across representative states. Useful for finding VoiceOver regressions early without waiting for a full UI-test suite.
- [Swift Student Challenge winners](https://9to5mac.com/2026/05/07/apple-highlights-four-swift-student-challenge-apps-ahead-of-wwdc-2026?ref=ioscodereview.com) — Article · Topics: AI Development · Apple Platform Ecosystem · Swift
  **NeKI brief:** Examines Swift Student Challenge winners in the context of AI Development and Apple Platform Ecosystem. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Previewing SwiftUI views in both dark and light mode](https://peterringset.dev/articles/light-and-dark-preview?ref=ioscodereview.com) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates previewing SwiftUI views in both light and dark color schemes with representative content. Useful for catching contrast, asset, and layout failures before device testing, especially in reusable components.

## [Issue 77](https://ioscodereview.com/issues/issue-77-swift-is-bigger-than-xcode-and-other-dev-updates)

- Published: `2026-04-15T16:20:56.000Z`

**Topics:** Apple Platform Ecosystem · Graphics, Media & Games · macOS & AppKit · Swift · SwiftUI · UIKit

**NeKI brief:** Curates this edition’s code-review material on Swift Is Bigger Than Xcode, a Paste Bug You've Probably Hit, and WWDC Is 57 Days Away. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Swift](https://www.swift.org/blog/expanding-swift-ide-support?ref=ioscodereview.com) — Article · Topics: AI Development · Graphics, Media & Games · Swift
  **NeKI brief:** Examines Swift in the context of AI Development and Graphics, Media & Games. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [InfoWorld](https://www.infoworld.com/article/4157422/swift-for-visual-studio-code-comes-to-open-vsx-registry.html?ref=ioscodereview.com) — Article · Topics: Cross-Platform & Web · Foundation & Data Formats · Swift
  **NeKI brief:** Examines InfoWorld in the context of Cross-Platform & Web and Foundation & Data Formats. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [@samwize](https://samwize.com/2026/03/30/xcode-simulator-paste-broken-workaround?ref=ioscodereview.com) — Article · Topics: AI Development · Cross-Platform & Web · Xcode
  **NeKI brief:** Examines @samwize in the context of AI Development and Cross-Platform & Web. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Harold Serrano](https://www.haroldserrano.com/blog?ref=ioscodereview.com) — Article · Topics: Graphics, Media & Games · Swift
  **NeKI brief:** Examines Harold Serrano in the context of Graphics, Media & Games and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [MacRumors](https://www.macrumors.com/roundup/wwdc?ref=ioscodereview.com) — Article · Topics: Apple Platform Ecosystem
  **NeKI brief:** Examines MacRumors in the context of Apple Platform Ecosystem. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 76](https://ioscodereview.com/issues/issue-76-swift-6-3-is-here-swift-on-android-smarter-tests-one-very-important-date)

- Published: `2026-03-30T18:21:46.000Z`

**Topics:** AI Development · macOS & AppKit · Swift · SwiftUI · Testing · UIKit

**NeKI brief:** Curates this edition’s code-review material on Swift 6.3 Is Here, Swift on Android, and Smarter Tests. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Swift 6.3 ReleasedSwift is designed to be the language you reach for at every layer of the software stack. Whether you’re building embedded firmware, internet-scale services, or full-featured mobile apps, Swift delivers strong safety guarantees, performance control when you need it, and expressive language features and APIs.Swift.orgApple Inc.](https://www.swift.org/blog/swift-6.3-released?ref=ioscodereview.com) — Article · Topics: Graphics, Media & Games · Swift · Testing
  **NeKI brief:** Announces Swift 6.3 and summarizes the language, package, and tooling changes in that release. Use it to identify migration candidates, then consult the release notes and proposal links for exact compiler behavior and availability.
- [Embedded Swift Improvements Coming in Swift 6.3Embedded Swift is a subset of Swift that’s designed for low resource usage, making it capable of running on constrained environments like microcontrollers. Using a special compilation mode, Embedded Swift produces significantly smaller binaries than regular Swift. While a subset of the full language, the vast majority of the Swift language works exactly the same in Embedded Swift. Additional information is described in the Embedded Swift vision document.Swift.orgApple Inc.](https://www.swift.org/blog/embedded-swift-improvements-coming-in-swift-6.3?ref=ioscodereview.com) — Article · Topics: Combine & Reactive Programming · Foundation & Data Formats · Swift
  **NeKI brief:** Examines Embedded Swift Improvements Coming in Swift 6.3Embedded Swift is a subset of Swift that’s designed for low… in the context of Combine & Reactive Programming and Foundation & Data Formats. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Swift.orgSwift is a general-purpose programming language built using a modern approach to safety, performance, and software design patterns.Swift.orgApple Inc.](https://www.swift.org/documentation/articles/swift-sdk-for-android-getting-started.html?ref=ioscodereview.com) — Article · Topics: Cross-Platform & Web · Performance · Swift
  **NeKI brief:** Presents getting started guide for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [MacRumors](https://www.macrumors.com/2026/03/26/apple-swift-student-challenge-winners-2026?ref=ioscodereview.com) — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games · Swift
  **NeKI brief:** Examines MacRumors in the context of App Distribution & Store Operations and Graphics, Media & Games. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 75](https://ioscodereview.com/issues/issue-75-were-back-tool-calling-default-actors-the-clock-is-ticking)

- Published: `2026-03-17T06:28:33.000Z`

**Topics:** AI Development · Concurrency · Foundation & Data Formats · macOS & AppKit · Swift · Testing

**NeKI brief:** Curates this edition’s code-review material on We're Back! Tool Calling, Default Actors, and the Clock Is Ticking. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Should you opt-in to Swift 6.2’s Main Actor isolation? – Donny WalsSwift 6.2 comes with some interesting Concurrency improvements. One of the most notable changes is that there’s now a compiler flag that will, by default, isolate all your (implicitly nonisolated)…Donny Walsdonnywals](https://www.donnywals.com/should-you-opt-in-to-swift-6-2s-main-actor-isolation?ref=ioscodereview.com) — Article · Topics: Concurrency · Swift · Xcode
  **NeKI brief:** Weighs opting into Swift 6.2 default MainActor isolation, including migration benefits and accidental UI-executor work. Useful for choosing a project-wide concurrency baseline deliberately.
- [Default Actor Isolation in Swift 6.2Use Default Actor Isolation in Swift 6.2 to run code on the @MainActor by default and smoothen your migration.SwiftLeeAntoine van der Lee](https://www.avanderlee.com/concurrency/default-actor-isolation-in-swift-6-2?ref=ioscodereview.com) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Shows how Swift 6.2 default actor isolation changes unannotated code and how to opt into it during migration. The examples clarify the convenience gained and the explicit Sendable or nonisolated work still required.
- [YouTube playlist](https://www.youtube.com/watch?v=jAgydnnjj0Y&list=PLeb93j_rsErO182fdoJ4m1p_suKAOcBnM&ref=ioscodereview.com) — Video · Topics: Swift · Testing
  **NeKI brief:** Records YouTube playlist as a visual walkthrough relevant to Swift and Testing. Use it to inspect the demonstrated workflow, then verify version-specific details with current primary sources.
- [Building a design system at Genius Scan | Swift by SundellAn example of how to approach the task of building a design system for an app, by focusing on creating an initial set of reusable components that can be tweaked using the SwiftUI environment.Swift by Sundell](https://www.swiftbysundell.com/articles/building-a-design-system-at-genius-scan?ref=ioscodereview.com) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Describes building a shared design system with reusable components, tokens, and constraints at Genius Scan. Useful for connecting SwiftUI component reuse to product consistency and team-scale maintenance.
- [Swift](https://www.swift.org/blog/swift-6.2-released?ref=ioscodereview.com) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Swift 6.2's release announcement provides the authoritative overview of language and toolchain changes. Use it to plan adoption boundaries and match compiler behavior to the released version.
- [Fatbobman's Swift Weekly](https://fatbobman.com/en/posts/default-actor-isolation?ref=ioscodereview.com) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Swift 6.2 infers a default actor for otherwise unmarked declarations, reducing annotations but exposing actor-boundary errors in macros and mixed-isolation code. This is useful when auditing migration diagnostics and deciding where explicit isolation remains necessary.

## [Issue 74](https://ioscodereview.com/issues/74)

- Published: `2024-12-04T11:30:50.000Z`

**Topics:** AI Development · Code Quality · macOS & AppKit · Swift · Testing · Xcode

**Sections:** Issue #74 · Xcode and ChatGPT Support · Swift Testing: Parameters

**NeKI brief:** Curates this edition’s code-review material on Xcode and ChatGPT Support, Swift Testing: Parameters, and Swift Testing: Traits & Tags. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [ChatGPT + XCodeVideo’s delen met vrienden, familie en de rest van de wereldYouTube](https://youtube.com/playlist?list=PLvHc56e5L-7xgZsgvF2yL7P13lmTwNcoh&ref=ioscodereview.com) — Video · Topics: Graphics, Media & Games · Xcode
  **NeKI brief:** Records ChatGPT + XCodeVideo’s delen met vrienden, familie en de rest van de wereldYouTube as a visual walkthrough relevant to Graphics, Media & Games and Xcode. Use it to inspect the demonstrated workflow, then verify version-specific details with current primary sources.
- [Swift Testing: Suites](https://swiftwithmajid.com/2024/10/29/introducing-swift-testing-lifecycle?ref=ioscodereview.com) — Article · Topics: Macros & Metaprogramming · Swift · Testing
  **NeKI brief:** Explains Swift Testing lifecycle hooks and how setup or teardown scopes differ from XCTest methods. Useful for isolating shared fixtures without leaking state between parallel tests.
- [SwiftLee](https://www.avanderlee.com/swift-testing/require-macro?ref=ioscodereview.com) — Article · Topics: Macros & Metaprogramming · Swift · Testing
  **NeKI brief:** Explains #require as Swift Testing’s throwing precondition for setup and optional unwrapping, contrasting its fail-fast behavior with #expect and showing how failure messages retain useful source context.
- [Danny Walls](https://www.donnywals.com/testing-requirements-with-require-in-swift-testing?ref=ioscodereview.com) — Article · Topics: Macros & Metaprogramming · Swift · Testing
  **NeKI brief:** #require turns prerequisite failures into thrown test exits, separating invalid setup from behavioral assertions; use it sparingly so ordinary expectation failures still report together.
- [Here’s how to build the perfect mobile release train](https://www.runway.team/blog/how-to-build-the-perfect-mobile-release-train) — Article · Topics: Code Quality
  **NeKI brief:** Walks through how to build the perfect release train, with practical context for Apple-platform engineering. Use it when implementing the workflow, while checking current tool and platform versions before copying the setup.
- [Working with Natural Language frameworkLearn how to use the Natural Language framework to analyze text in real time.Artem Novichkov](https://www.artemnovichkov.com/blog/working-with-natural-language-framework?ref=ioscodereview.com) — Article · Topics: Objective-C & Cocoa
  **NeKI brief:** Examines Working with Natural Language frameworkLearn how to use the Natural Language framework to analyze text in real… in the context of Objective-C & Cocoa. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Swift Testing: Parameters](https://swiftwithmajid.com/2024/11/12/introducing-swift-testing-parameterized-tests?ref=ioscodereview.com) — Article · Topics: Swift · Testing
  **NeKI brief:** Shows parameterized Swift Testing cases that reuse one test body across input matrices. Useful for expanding edge-case coverage without duplicating assertion and setup code.
- [Swift Testing: Traits & Tags](https://swiftwithmajid.com/2024/11/05/introducing-swift-testing-traits?ref=ioscodereview.com) — Article · Topics: Swift · Testing
  **NeKI brief:** Uses Swift Testing traits to tag, condition, and customize tests. Useful for expressing platform requirements and execution policy close to the test rather than in external schemes.

## [Issue 73](https://ioscodereview.com/issues/73)

- Published: `2024-11-20T11:14:23.000Z`

**Topics:** Code Quality · Concurrency · macOS & AppKit · Swift · Testing · UIKit

**Sections:** Issue #73 · Xcode 16: Try Swift Testing · Secrets to Success With @MainActor

**NeKI brief:** Curates this edition’s code-review material on Xcode 16: Try Swift Testing, Secrets to Success With @MainActor, and More Secrets to Success With @MainActor. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Xcode 16: Try Swift Testing](https://swiftwithmajid.com/2024/10/22/introducing-swift-testing-basics?ref=ioscodereview.com) — Article · Topics: Swift · Testing · Xcode
  **NeKI brief:** Introduces Swift Testing's test declarations, expectations, and setup model. Useful as a migration starting point when replacing XCTest boilerplate while keeping behavioral assertions readable.
- [Secrets to Success With @MainActor](https://www.hackingwithswift.com/quick-start/concurrency/how-to-use-mainactor-to-run-code-on-the-main-queue?ref=ioscodereview.com) — Article · Topics: App Services & Extensions · Concurrency · Observation & State Management
  **NeKI brief:** Examines this article by Paul Hudson in the context of Concurrency and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Swift Over Coffee](https://podcasts.apple.com/gb/podcast/swift-over-coffee/id1435076502?i=1000676386646&ref=ioscodereview.com) — Podcast · Topics: Developer Community & Business · Hardware & Devices · Swift
  **NeKI brief:** Examines Swift Over Coffee in the context of Developer Community & Business and Hardware & Devices. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [https://keyboardkit.com/pro](https://keyboardkit.com/pro?ref=ioscodereview.com) — Article · Topics: Code Quality · Hardware & Devices
  **NeKI brief:** Examines Get started for free 🚀 in the context of App Distribution & Store Operations and Developer Career & Practice. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Exploring Apple Intelligence: Writing ToolsUnderstand Writing Tools, powered by Apple Intelligence.Create with SwiftAntonella Giugliano](https://www.createwithswift.com/exploring-apple-intelligence-writing-tools?ref=ioscodereview.com) — Article · Topics: AI Development · Swift · UIKit
  **NeKI brief:** Covers Writing Tools across SwiftUI and UIKit, including intelligent animation and ecosystem integration. Use it to compare framework-specific adoption paths and identify where text-editing controls can inherit system writing assistance.
- [More Secrets to Success With @MainActor](https://www.avanderlee.com/swift/mainactor-dispatch-main-thread?ref=ioscodereview.com) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Clarifies that MainActor isolation expresses UI-thread access but does not make every operation globally synchronous. Examples contrast annotating declarations, hopping with MainActor.run, and avoiding unnecessary main-thread work.
- [trailing comma in comma-separated lists](https://github.com/swiftlang/swift-evolution/blob/main/proposals/0439-trailing-comma-lists.md?ref=ioscodereview.com) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the source and change history for trailing comma in comma-separated lists, relevant to Developer Tools and Swift. Inspect its implementation, open issues, and release state before adopting the approach.
- [lack of a native Vector type](https://github.com/swiftlang/swift-evolution/blob/main/proposals/0453-vector.md?ref=ioscodereview.com) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the source and change history for lack of a native Vector type, relevant to Developer Tools and Swift. Inspect its implementation, open issues, and release state before adopting the approach.

## [Issue 72](https://ioscodereview.com/issues/72)

- Published: `2024-11-06T11:00:17.000Z`

**Topics:** App Distribution & Store Operations · macOS & AppKit · Swift · SwiftUI · UIKit · Xcode

**Sections:** Issue #72 · Swift 6: Typed Throws · How do we make illegal states unrepresentable?

**NeKI brief:** Curates this edition’s code-review material on Swift 6: Typed Throws, How do we make illegal states unrepresentable?, and @Entry in SwiftUI. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [GitHub Copilot for XcodeMicrosoft released an Xcode extension in a surprising turn of eventMediumThomas Ricouard](https://dimillian.medium.com/github-copilot-for-xcode-62931a645173?ref=ioscodereview.com) — Article · Topics: AI Development · Developer Tools · Xcode
  **NeKI brief:** Presents GitHub Copilot for Xcode, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [@Entry in SwiftUI](https://www.swiftwithvincent.com/blog/new-in-swiftui-the-macro-entry?ref=ioscodereview.com) — Article · Topics: Macros & Metaprogramming · Swift · SwiftUI
  **NeKI brief:** Examines @Entry in SwiftUI in the context of Macros & Metaprogramming and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [A couple of how-tos](https://www.createwithswift.com/implement-blurring-when-multitasking-in-swiftui?ref=ioscodereview.com) — Article · Topics: App Distribution & Store Operations · Swift · SwiftUI
  **NeKI brief:** Blurs SwiftUI content during multitasking transitions, protecting sensitive screen data by coupling privacy presentation to scene activity changes.
- [Swift 6: Typed Throws](https://github.com/swiftlang/swift-evolution/blob/main/proposals/0413-typed-throws.md?ref=ioscodereview.com) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the source and change history for Swift 6: Typed Throws, relevant to Developer Tools and Swift. Inspect its implementation, open issues, and release state before adopting the approach.
- [Here’s how to build the perfect mobile release train](https://www.runway.team/blog/how-to-build-the-perfect-mobile-release-train) — Article
  **NeKI brief:** Walks through how to build the perfect release train, with practical context for Apple-platform engineering. Use it when implementing the workflow, while checking current tool and platform versions before copying the setup.
- [How do we make illegal states unrepresentable?](https://swiftology.io/articles/making-illegal-states-unrepresentable?ref=ioscodereview.com) — Article · Topics: Swift
  **NeKI brief:** Examines How do we make illegal states unrepresentable? in the context of Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 71](https://ioscodereview.com/issues/71)

- Published: `2024-09-24T10:08:19.000Z`

**Topics:** Apple Platform Ecosystem · Architecture · macOS & AppKit · Swift · SwiftUI · UIKit

**Sections:** Issue #71 · Ask WWDC AI · Scroll view margins in SwiftUI

**NeKI brief:** Curates this edition’s code-review material on Ask WWDC AI, Scroll view margins in SwiftUI, and Swift Regex examples. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Building Large Scale Apps SwiftuiBuilding Large-Scale Apps with SwiftUI: A Guide to Modular ArchitectureAzamSharpMohammad Azam](https://azamsharp.com/2023/02/28/building-large-scale-apps-swiftui.html?ref=ioscodereview.com) — Article · Topics: Architecture · Swift · SwiftUI
  **NeKI brief:** Explores Building Large Scale Apps with SwiftUI, focusing on i’m not going to try to summarise this post from. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Scroll view margins in SwiftUI](https://serialcoder.dev/text-tutorials/swiftui/insetting-scrollable-views-content-with-contentmargins-in-swiftui?ref=ioscodereview.com) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates contentMargins for insetting ScrollView content in SwiftUI. Useful for consistent readable edges and indicator placement without spacer-based layout hacks.
- [Swift Regex examples](https://github.com/DandyLyons/NativeRegexExamples?ref=ioscodereview.com) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the source and change history for Swift Regex examples, relevant to Developer Tools and Swift. Inspect its implementation, open issues, and release state before adopting the approach.
- [Read on Squarespace's blog](https://engineering.squarespace.com/blog/2024/unfolds-modern-mobile-release-process-and-the-subtle-art-of-making-them-boring?ref=ioscodereview.com) — Article · Topics: Combine & Reactive Programming
  **NeKI brief:** Examines Read on Squarespace's blog in the context of Combine & Reactive Programming. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 70](https://ioscodereview.com/issues/70)

- Published: `2024-09-02T10:30:09.000Z`

**Topics:** Code Quality · Concurrency · macOS & AppKit · Swift · SwiftUI · UIKit

**Sections:** Issue #70 · Typesafe identifiers, my favourite way · Concurrency in detail

**NeKI brief:** Curates this edition’s code-review material on Typesafe identifiers, my favourite way, Concurrency in detail, and Format styles in excruciating detail. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Concurrency in detail](https://www.massicotte.org/step-by-step-network-request?ref=ioscodereview.com) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Presents a network request for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Beautiful async buttons](https://github.com/Dean151/ButtonKit?ref=ioscodereview.com) — Source repository · Topics: Concurrency · Developer Tools
  **NeKI brief:** Provides the source and change history for Beautiful async buttons, relevant to Concurrency and Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [Typesafe identifiers, my favourite way](https://jacobzivandesign.com/technology/people_make_mistakes?ref=ioscodereview.com) — Article · Topics: Macros & Metaprogramming · Swift
  **NeKI brief:** Examines Typesafe identifiers, my favourite way in the context of Macros & Metaprogramming and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 69](https://ioscodereview.com/issues/69)

- Published: `2024-04-29T09:59:36.000Z`

**Topics:** Code Quality · Graphics, Media & Games · macOS & AppKit · Swift · SwiftUI · UIKit

**Sections:** Issue #69 · Goodbye GeometryReader, hello containerRelativeFrame · New Content Margins modifier

**NeKI brief:** Curates this edition’s code-review material on Goodbye GeometryReader, hello containerRelativeFrame, New Content Margins modifier, and Computed property or a function. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [New Content Margins modifier](https://swiftwithmajid.com/2024/04/23/content-margins-in-swiftui?ref=ioscodereview.com) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains SwiftUI content margins as a separate layout tool from the safe area, showing where margin modifiers place content and how that distinction affects edge-to-edge screens.
- [Computed property or a function](https://www.donnywals.com/deciding-between-a-computed-property-and-a-function-in-swift?ref=ioscodereview.com) — Article · Topics: Swift
  **NeKI brief:** Computed properties model derived state without arguments, while functions signal work or parameters; choosing deliberately keeps call sites honest about cost and side effects.

## [Issue 68](https://ioscodereview.com/issues/68)

- Published: `2024-04-16T09:25:01.000Z`

**Topics:** Code Quality · macOS & AppKit · Security & Privacy · Swift · SwiftUI · UIKit

**Sections:** Issue #68 · Everything about the AASA file · ContentUnavailableView FTW

**NeKI brief:** Curates this edition’s code-review material on Everything about the AASA file, ContentUnavailableView FTW, and Overcoming obstacles. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [There is no right or wrong in software engineering (often)](https://swiftrocks.com/there-is-no-right-or-wrong-in-software-engineering?ref=ioscodereview.com) — Article · Topics: Swift
  **NeKI brief:** Examines There is no right or wrong in software engineering (often) in the context of Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [ContentUnavailableView FTW](https://www.createwithswift.com/display-empty-states-with-contentunavailableview-in-swiftui?ref=ioscodereview.com) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Uses ContentUnavailableView for empty SwiftUI states, separating no-data presentation from loading and error states without custom placeholder layouts.
- [Everything about the AASA file](https://digitalbunker.dev/apple-app-site-association?ref=ioscodereview.com) — Article · Topics: Developer Tools
  **NeKI brief:** Examines Everything about the AASA file in the context of Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Overcoming obstacles](https://blog.supereasyapps.com/5-practical-ways-to-quickly-overcome-a-programming-obstacle?ref=ioscodereview.com) — Article
  **NeKI brief:** Examines Overcoming obstacles in the context of Apple-platform engineering. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 67](https://ioscodereview.com/issues/67)

- Published: `2024-04-03T12:22:37.000Z`

**Topics:** App Distribution & Store Operations · Apple Platform Ecosystem · macOS & AppKit · Swift · SwiftUI · UIKit

**Sections:** Issue #67 · Handling family shared in-app subscriptions · Date decoding strategies in Swift, with examples

**NeKI brief:** Curates this edition’s code-review material on Handling family shared in-app subscriptions, Date decoding strategies in Swift, with examples, and Trigger value pattern in SwiftUI. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Trigger value pattern in SwiftUI](https://swiftwithmajid.com/2024/04/02/trigger-value-pattern-in-swiftui?ref=ioscodereview.com) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Uses SwiftUI trigger values to restart asynchronous or visual work when a specific input changes. Useful for making task identity explicit instead of relying on incidental view reconstruction.
- [Date decoding strategies in Swift, with examples](https://matteomanferdini.com/datedecodingstrategy?ref=ioscodereview.com) — Article · Topics: Swift
  **NeKI brief:** Examines Date decoding strategies in Swift, with examples in the context of Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Apple DeveloperHello and welcome to the official Apple Developer YouTube channel.YouTube](https://www.youtube.com/@AppleDeveloper/playlists?ref=ioscodereview.com) — Video · Topics: Apple Platform Ecosystem · Graphics, Media & Games
  **NeKI brief:** Records Apple DeveloperHello and welcome to the official Apple Developer YouTube channel.YouTube as a visual walkthrough relevant to Apple Platform Ecosystem and Graphics, Media & Games. Use it to inspect the demonstrated workflow, then verify version-specific details with current primary sources.
- [Handling family shared in-app subscriptions](https://furbo.org/2024/03/29/app-store-subscriptions-and-family-sharing?ref=ioscodereview.com) — Article · Topics: App Distribution & Store Operations
  **NeKI brief:** Examines Handling family shared in-app subscriptions in the context of App Distribution & Store Operations. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 66](https://ioscodereview.com/issues/66)

- Published: `2024-03-18T13:34:21.000Z`

**Topics:** Accessibility · macOS & AppKit · Observation & State Management · Swift · SwiftUI · Testing

**Sections:** Issue #66 · What's new in Swift 5.10 · Have you tried Observation framework?

**NeKI brief:** Curates this edition’s code-review material on What's new in Swift 5.10, Have you tried Observation framework?, and Unit testing Observable models. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Unit Test the Observation FrameworkMake your iOS 17 view models rock-solidJacob’s Tech TavernJacob Bartlett](https://jacobbartlett.substack.com/p/unit-test-the-observation-framework) — Article · Topics: Combine & Reactive Programming · Observation & State Management · Testing
  **NeKI brief:** Examines Unit Test the Observation FrameworkMake your iOS 17 view models rock-solidJacob’s Tech TavernJacob Bartlett in the context of Combine & Reactive Programming and Observation & State Management. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Swift concurrency roadmap](https://forums.swift.org/t/swift-concurrency-roadmap/41611?ref=ioscodereview.com) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Examines Swift concurrency roadmap in the context of Concurrency and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Accessibility Representation modifier](https://www.createwithswift.com/making-a-view-accessible-using-the-accessibility-representation-modifier?ref=ioscodereview.com) — Article · Topics: Accessibility · Swift
  **NeKI brief:** Uses accessibilityRepresentation to replace a complex SwiftUI view's exposed semantics with a simpler representative hierarchy. This is useful when visual composition is elaborate but assistive users need one coherent control.
- [What's new in Swift 5.10](https://www.swift.org/blog/swift-5.10-released?ref=ioscodereview.com) — Article · Topics: Swift
  **NeKI brief:** Summarises What's new in Swift 5.10 for Swift. Use it to identify the relevant changes and follow its primary links before relying on version-sensitive details.
- [Have you tried Observation framework?](https://www.donnywals.com/comparing-observable-to-observableobjects?ref=ioscodereview.com) — Article · Topics: Observation & State Management
  **NeKI brief:** Examines Have you tried Observation framework? in the context of Observation & State Management. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 65](https://ioscodereview.com/issues/65)

- Published: `2024-03-05T11:24:22.000Z`

**Topics:** Code Quality · macOS & AppKit · Security & Privacy · Swift · SwiftUI · UIKit

**Sections:** Issue #65 · Type-driven design · Verifying associated domains

**NeKI brief:** Curates this edition’s code-review material on Type-driven design, Verifying associated domains, and Combining SF symbols. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Using inout](https://danielsaidi.com/blog/2024/02/18/the-power-of-inout-parameters?ref=ioscodereview.com) — Article · Topics: Swift
  **NeKI brief:** Examines Using inout in the context of Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Type-driven design](https://swiftology.io/articles/tydd-part-2?ref=ioscodereview.com) — Article · Topics: Swift
  **NeKI brief:** Examines Type-driven design in the context of Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 64](https://ioscodereview.com/issues/64)

- Published: `2024-02-20T20:21:17.000Z`

**Topics:** Code Quality · Developer Tools · macOS & AppKit · Swift · SwiftUI · UIKit

**Sections:** Issue #64 · Don't write recursive functions in Swift · Avoid using default enum case

**NeKI brief:** Curates this edition’s code-review material on Don't write recursive functions in Swift, Avoid using default enum case, and Previewing CIImage in the debugger. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Swift enums and the danger of the default caseHow not to lay traps for future developersMediumToby O’Connell](https://oconnelltoby.medium.com/swift-enums-and-the-danger-of-the-default-case-625a0830f57a?ref=ioscodereview.com) — Article · Topics: Swift
  **NeKI brief:** Examines Swift enums and the danger of the default caseHow not to lay traps for future developersMediumToby O’Connell in the context of Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 63](https://ioscodereview.com/issues/63)

- Published: `2024-02-05T11:17:38.000Z`

**Topics:** Code Quality · Core Data · macOS & AppKit · Swift · SwiftUI · UIKit

**Sections:** Issue #63 · Serialising dictionary writes correctly · Document directory path changes

**NeKI brief:** Curates this edition’s code-review material on Serialising dictionary writes correctly, Document directory path changes, and What if we stopped nitpicking?. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Serialising dictionary writes correctly](https://augmentedcode.io/2024/01/29/avoiding-subtle-mistake-when-guarding-mutable-state-with-dispatchqueue?ref=ioscodereview.com) — Article
  **NeKI brief:** Examines Serialising dictionary writes correctly in the context of Apple-platform engineering. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [What if we stopped nitpicking?](https://blog.danlew.net/2021/02/23/stop-nitpicking-in-code-reviews?ref=ioscodereview.com) — Article
  **NeKI brief:** Examines What if we stopped nitpicking? in the context of Apple-platform engineering. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 62](https://ioscodereview.com/issues/62)

- Published: `2024-01-18T12:04:53.000Z`

**Topics:** Graphics, Media & Games · macOS & AppKit · Swift · SwiftUI · Testing · UIKit

**Sections:** Issue #62 · Naming unit tests · [UI]Image memory footprint

**NeKI brief:** Curates this edition’s code-review material on Naming unit tests, UI]Image memory footprint, and Typestate pattern: next-level type safety. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Naming unit tests](https://qualitycoding.org/unit-test-naming?ref=ioscodereview.com) — Article · Topics: Testing
  **NeKI brief:** Examines Naming unit tests in the context of Testing. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [[UI]Image memory footprint](https://swiftsenpai.com/development/reduce-uiimage-memory-footprint?ref=ioscodereview.com) — Article · Topics: Swift
  **NeKI brief:** Examines UI]Image memory footprint in the context of Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Typestate pattern: next-level type safety](https://swiftology.io/articles/typestate?ref=ioscodereview.com) — Article · Topics: Swift
  **NeKI brief:** Examines Typestate pattern: next-level type safety in the context of Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 61](https://ioscodereview.com/issues/61)

- Published: `2023-12-07T13:38:43.000Z`

**Topics:** Code Quality · macOS & AppKit · Swift · SwiftData · SwiftUI · UIKit

**Sections:** Issue #61 · UIViewController viewIsAppearing · Catching memory leaks on CI

**NeKI brief:** Curates this edition’s code-review material on UIViewController viewIsAppearing, Catching memory leaks on CI, and Opening SFSafariViewController, cleanly. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [The Ultimate Swift Data GuideThe Ultimate Guide to Building SwiftData ApplicationsAzamSharpMohammad Azam](https://azamsharp.com/2023/07/04/the-ultimate-swift-data-guide.html?ref=ioscodereview.com) — Article · Topics: Cross-Platform & Web · Swift · SwiftData
  **NeKI brief:** Provides a broad SwiftData walkthrough covering model declaration, persistence, and cloud-sync-oriented concepts introduced at WWDC 2023. Useful for mapping Core Data requirements to SwiftData before committing to a migration or new model layer.
- [UIViewController viewIsAppearing](https://ohmyswift.com/blog/2023/12/01/from-viewwillappear-to-viewisappearing-perfecting-your-ios-view-transitions?ref=ioscodereview.com) — Article · Topics: Objective-C & Cocoa · Swift
  **NeKI brief:** Explains the transition from viewWillAppear to viewIsAppearing and the timing differences relevant to layout and appearance updates. Follow it when modernizing UIKit lifecycle code that depends on final geometry or trait state.
- [Automating Memory Leak Detection with CI Integration for iOSA solution to automate memory leak detection in iOS DevelopmentLevel Up CodingTuan Hoang (Eric)](https://levelup.gitconnected.com/automating-memory-leak-detection-with-ci-integration-for-ios-380f08a55f0b?ref=ioscodereview.com) — Article · Topics: Developer Tools · Testing
  **NeKI brief:** Examines Automating Memory Leak Detection with CI Integration for iOSA solution to automate memory leak detection in… in the context of Developer Tools and Testing. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Opening SFSafariViewController, cleanly](https://www.avanderlee.com/swiftui/sfsafariviewcontroller-open-webpages-in-app?ref=ioscodereview.com) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Wraps SFSafariViewController in UIViewControllerRepresentable so SwiftUI can present an authenticated, in-app browser while retaining Safari's security model. Useful when a web flow should not leave the app context.

## [Issue 60](https://ioscodereview.com/issues/60)

- Published: `2023-11-23T12:38:53.000Z`

**Topics:** App Distribution & Store Operations · Code Quality · macOS & AppKit · Swift · SwiftUI · UIKit

**Sections:** Issue #60 · Alternative to Spacer · Pin SwiftUI view to an edge

**NeKI brief:** Curates this edition’s code-review material on Alternative to Spacer, Pin SwiftUI view to an edge, and Living with flaky tests (temporarily). Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Living with flaky tests (temporarily)](https://holyswift.app/unit-test-expected-failures-in-swift?ref=ioscodereview.com) — Article · Topics: Swift · Testing
  **NeKI brief:** Examines Living with flaky tests (temporarily) in the context of Swift and Testing. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Get started for free 🚀](https://keyboardkit.com/pro?ref=ioscodereview.com) — Article · Topics: App Distribution & Store Operations · Developer Career & Practice · Hardware & Devices
  **NeKI brief:** Examines Get started for free 🚀 in the context of App Distribution & Store Operations and Developer Career & Practice. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Alternative to Spacer](https://david.y4ng.fr/the-alternative-to-swiftui-spacer?ref=ioscodereview.com) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Examines Alternative to Spacer in the context of Performance and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Self-editing | Technical Writing | Google for DevelopersGoogle for Developers](https://developers.google.com/tech-writing/two/editing?ref=ioscodereview.com) — Article · Topics: Hardware & Devices
  **NeKI brief:** Examines Self-editing | Technical Writing | Google for DevelopersGoogle for Developers in the context of Hardware & Devices. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [EmojiKit](https://kankoda.com/emojikit?ref=ioscodereview.com) — Article · Topics: App Distribution & Store Operations · Developer Career & Practice
  **NeKI brief:** Examines EmojiKit in the context of App Distribution & Store Operations and Developer Career & Practice. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [LicenseKit](https://kankoda.com/licensekit?ref=ioscodereview.com) — Article · Topics: App Distribution & Store Operations · Developer Career & Practice
  **NeKI brief:** Examines LicenseKit in the context of App Distribution & Store Operations and Developer Career & Practice. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Pin SwiftUI view to an edge](https://onmyway133.com/posts/how-to-show-anchor-bottom-view-in-swiftui?ref=ioscodereview.com) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines Pin SwiftUI view to an edge in the context of Swift and SwiftUI. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 59](https://ioscodereview.com/issues/59)

- Published: `2023-11-09T13:26:49.000Z`

**Topics:** Code Quality · macOS & AppKit · Performance · Swift · SwiftUI · UIKit

**Sections:** Issue #59 · Swift Algorithms - split an array into chunks, and more · Split a list by month

**NeKI brief:** Curates this edition’s code-review material on Swift Algorithms - split an array into chunks, and more, Split a list by month, and GeometryReader - Blessing or Curse?. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Swift Algorithms - split an array into chunks, and more](https://www.swift.org/blog/swift-algorithms?ref=ioscodereview.com) — Article · Topics: Performance · Swift · Testing
  **NeKI brief:** Examines Swift Algorithms - split an array into chunks, and more in the context of Performance and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Take the 6-question Health Check](https://bitrise.io/learn/modas-health-check) — Article · Topics: Code Quality
  **NeKI brief:** Examines Take the 6-question Health Check in the context of Code Quality and Developer Community & Business. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Split a list by month](https://www.danijelavrzan.com/posts/2023/10/swift-algorithms-chunked?ref=ioscodereview.com) — Article · Topics: Swift
  **NeKI brief:** Examines Split a list by month in the context of Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 58](https://ioscodereview.com/issues/58)

- Published: `2023-10-26T11:38:39.000Z`

**Topics:** Developer Tools · macOS & AppKit · Swift · SwiftUI · Testing · UIKit

**Sections:** Issue #58 · How (not) to monitor SwiftUI @State · Random enum case

**NeKI brief:** Curates this edition’s code-review material on How (not) to monitor SwiftUI @State, Random enum case, and Launching a SwiftUI view from the terminal. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [How (not) to monitor SwiftUI @State](https://blog.thomasdurand.fr/story/2023-10-21-how-not-to-monitor-swiftui-state?ref=ioscodereview.com) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Examines How (not) to monitor SwiftUI @State in the context of Observation & State Management and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Launching a SwiftUI view from the terminal](https://www.polpiella.dev/launching-a-swiftui-view-from-the-terminal?ref=ioscodereview.com) — Article · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** A SwiftUI view launched from a terminal can use a small executable target or preview harness to iterate without the full app lifecycle. The technique is useful for isolated rendering checks, while dependency injection remains necessary for realistic state.
- [Random enum case](https://www.swiftjectivec.com/swift-randomnumbergenerator?ref=ioscodereview.com) — Article · Topics: Swift
  **NeKI brief:** Examines Random enum case in the context of Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Writing better unit tests](https://blog.devgenius.io/writing-good-unit-tests-2158be9ee82d?ref=ioscodereview.com) — Article · Topics: Testing
  **NeKI brief:** Examines Writing better unit tests in the context of Testing. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Take the 6-question Health Check](https://bitrise.io/learn/modas-health-check) — Article
  **NeKI brief:** Examines Take the 6-question Health Check in the context of Code Quality and Developer Community & Business. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 57](https://ioscodereview.com/issues/57)

- Published: `2023-10-12T11:48:38.000Z`

**Topics:** Code Quality · macOS & AppKit · Personal Essays · Swift · SwiftUI · UIKit

**Sections:** Issue #57 · onAppear vs task · viewIsAppearing - new in iOS 17

**NeKI brief:** Curates this edition’s code-review material on onAppear vs task, viewIsAppearing - new in iOS 17, and There's still a place for UIKit. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Take the 6-question Health Check](https://bitrise.io/learn/modas-health-check) — Article · Topics: Code Quality · Developer Community & Business · Graphics, Media & Games
  **NeKI brief:** Examines Take the 6-question Health Check in the context of Code Quality and Developer Community & Business. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Running Code When Your View Appears](https://chris.eidhof.nl/post/swiftui-on-appear-vs-task?ref=ioscodereview.com) — Article · Topics: Personal Essays · Swift · SwiftUI
  **NeKI brief:** Compares onAppear and task as ways to start work when a SwiftUI view becomes active, emphasizing that their lifecycle semantics differ. Use it when choosing where asynchronous or expensive work should begin.
- [Not Only Swift](https://not-only-swift.peterfriese.dev/issues/43?ref=ioscodereview.com) — Article · Topics: Personal Essays · Swift
  **NeKI brief:** Examines Not Only Swift in the context of Personal Essays and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [all other talk recordings from NSSpain 2023 on Vimeo](https://vimeo.com/showcase/10672108?ref=ioscodereview.com) — Video
  **NeKI brief:** Records all other talk recordings from NSSpain 2023 on Vimeo as a visual walkthrough relevant to Apple-platform engineering. Use it to inspect the demonstrated workflow, then verify version-specific details with current primary sources.

## [Issue 56](https://ioscodereview.com/issues/56)

- Published: `2023-09-28T11:24:10.000Z`

**Topics:** Code Quality · macOS & AppKit · Swift · SwiftUI · UIKit · Xcode

**Sections:** Issue #56 · Are you using SwiftData? · New behaviour of URL(string:) in iOS 17

**NeKI brief:** Curates this edition’s code-review material on Are you using SwiftData?, New behaviour of URL(string:) in iOS 17, and How to make a strong case for accessibility. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [brilliant article](https://smart-interface-design-patterns.com/articles/accessibility-strong-case?ref=ioscodereview.com) — Article · Topics: Accessibility
  **NeKI brief:** Examines brilliant article in the context of Accessibility. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 55](https://ioscodereview.com/issues/55)

- Published: `2023-09-19T13:32:36.000Z`

**Topics:** Architecture · Code Quality · macOS & AppKit · Swift · SwiftUI · UIKit

**Sections:** Issue #55 · Cache vs Persistent store · Simple app architecture

**NeKI brief:** Curates this edition’s code-review material on Cache vs Persistent store, Simple app architecture, and Working with time. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Read the blog post to see what's new.](https://www.swift.org/blog/swift-5.9-released?ref=ioscodereview.com) — Article · Topics: Macros & Metaprogramming · Swift · Systems Programming
  **NeKI brief:** Summarises Read the blog post to see what's new for Macros & Metaprogramming and Swift. Use it to identify the relevant changes and follow its primary links before relying on version-sensitive details.

## [Issue 54](https://ioscodereview.com/issues/54)

- Published: `2023-08-31T14:20:05.000Z`

**Topics:** Code Quality · Developer Tools · macOS & AppKit · Swift · SwiftUI · UIKit

**Sections:** Issue #54 · Cleaner grid initialization · Analogue clock on macOS in SwiftUI

**NeKI brief:** Curates this edition’s code-review material on Cleaner grid initialization, Analogue clock on macOS in SwiftUI, and Premature Optimization: Universally Misunderstood. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Premature Optimization: Universally Misunderstood](https://milen.me/writings/premature-optimization-universally-misunderstood?ref=ioscodereview.com) — Article · Topics: Architecture · Code Quality · Objective-C & Cocoa
  **NeKI brief:** Examines Premature Optimization: Universally Misunderstood in the context of Architecture and Code Quality. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Periphery](https://github.com/peripheryapp/periphery?ref=ioscodereview.com) — Source repository · Topics: Developer Tools
  **NeKI brief:** Periphery statically analyzes Swift projects to find unused declarations and code paths. Use its report to drive cleanup reviews in large codebases, but validate dynamic dispatch, reflection, and externally referenced symbols before removal.
- [Cleaner grid initialization](https://danielsaidi.com/blog/2023/08/30/cleaner-grid-initialization-in-swiftui?ref=ioscodereview.com) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines Cleaner grid initialization in the context of Swift and SwiftUI. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Tool to find unused code](https://www.manu.show/2023-08-21-use-periphery-to-find-unused-code?ref=ioscodereview.com) — Article
  **NeKI brief:** Examines Tool to find unused code in the context of Apple-platform engineering. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Co-authoring Git commits](https://dev.to/cassidoo/co-authoring-git-commits-3gin?ref=ioscodereview.com) — Article · Topics: Developer Tools
  **NeKI brief:** Examines Co-authoring Git commits in the context of Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 53](https://ioscodereview.com/issues/53)

- Published: `2023-08-17T11:03:56.000Z`

**Topics:** Code Quality · Concurrency · macOS & AppKit · Swift · SwiftUI · UIKit

**Sections:** Issue #53 · Enum-based sheet presentation · Using #error

**NeKI brief:** Curates this edition’s code-review material on Enum-based sheet presentation, Using #error, and Text + Text. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Enum-based sheet presentation](https://www.avanderlee.com/swiftui/presenting-sheets) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Compares sheet presentation driven by Boolean and identifiable item state, including dismissal and nested content. Useful for avoiding stale modal data and making SwiftUI presentation follow model state.
- [Vincent sharing](https://www.swiftwithvincent.com/blog/discover-hash-sign-error?ref=ioscodereview.com) — Article · Topics: Swift
  **NeKI brief:** Examines Vincent sharing in the context of Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [A refactoring story](https://qualitycoding.org/refactoring-cleaning-mess?ref=ioscodereview.com) — Article · Topics: Concurrency
  **NeKI brief:** Examines A refactoring story in the context of Concurrency. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 52](https://ioscodereview.com/issues/52)

- Published: `2023-07-06T18:35:01.000Z`

**Topics:** Code Quality · macOS & AppKit · Swift · SwiftUI · UIKit · Xcode

**Sections:** Issue #52 · GIFs in SwiftUI · View vs View modifier?

**NeKI brief:** Curates this edition’s code-review material on GIFs in SwiftUI, View vs View modifier?, and Beware of Xcode's automatic version management. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Beware of Xcode's automatic version management](https://alexanderweiss.dev/blog/2023-07-04-appstore-connect-manage-app-version-and-build-number?ref=ioscodereview.com) — Article · Topics: App Distribution & Store Operations · Developer Career & Practice · Xcode
  **NeKI brief:** Examines Beware of Xcode's automatic version management in the context of App Distribution & Store Operations and Developer Career & Practice. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [View vs View modifier?](https://www.swiftbysundell.com/articles/swiftui-views-versus-modifiers?ref=ioscodereview.com) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Compares extracting SwiftUI behavior as a View versus a ViewModifier. Both can structure, style, and own state; the useful deciding question is conceptual hierarchy—use modifiers when the change is styling, not a new structural component.
- [osstatus.com](https://www.osstatus.com/search/results?platform=all&framework=all&search=12&ref=ioscodereview.com) — Article · Topics: Objective-C & Cocoa · Xcode
  **NeKI brief:** Examines osstatus.com in the context of Objective-C & Cocoa and Xcode. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 51](https://ioscodereview.com/issues/51)

- Published: `2023-06-22T13:14:57.000Z`

**Topics:** macOS & AppKit · Macros & Metaprogramming · Swift · SwiftUI · Testing · UIKit

**Sections:** Issue #51 · Check your third party dependencies · Shuffling arrays

**NeKI brief:** Curates this edition’s code-review material on Check your third party dependencies, Shuffling arrays, and On skipping tests. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [On skipping tests](https://www.wwdcnotes.com/notes/wwdc20/10164?ref=ioscodereview.com) — Article · Topics: Apple Platform Ecosystem · Testing · Xcode
  **NeKI brief:** Examines On skipping tests in the context of Apple Platform Ecosystem and Testing. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [on Youtube](https://www.youtube.com/playlist?list=PLbKJc0NMPDrB29Ir8q8ABVOyJJZzkUwEN&ref=ioscodereview.com) — Video · Topics: Dependency Injection
  **NeKI brief:** Records on Youtube as a visual walkthrough relevant to Dependency Injection. Use it to inspect the demonstrated workflow, then verify version-specific details with current primary sources.

## [Issue 50](https://ioscodereview.com/issues/50)

- Published: `2023-06-09T10:49:04.000Z`

**Topics:** Apple Platform Ecosystem · Code Quality · macOS & AppKit · Swift · SwiftUI · UIKit

**Sections:** Issue #50 👑 · Happy WWDC! · Structural identity in SwiftUI

**NeKI brief:** Curates this edition’s code-review material on Happy WWDC!, Structural identity in SwiftUI, and And more. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Download free report](https://yo.bitrise.io/mobile-devops-assessment-report-2023-download.html) — Article · Topics: Apple Platform Ecosystem · Code Quality · Cross-Platform & Web
  **NeKI brief:** Examines Download free report in the context of Code Quality and Cross-Platform & Web. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Structural identity in SwiftUI](https://swiftwithmajid.com/2021/12/09/structural-identity-in-swiftui?ref=ioscodereview.com) — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **NeKI brief:** Explains structural identity and why conditional branches can create or destroy view state. Stable structure and explicit IDs help preserve local state, but IDs should represent domain identity rather than arbitrary indexes.

## [Issue 49](https://ioscodereview.com/issues/49)

- Published: `2023-05-25T15:05:24.000Z`

**Topics:** Accessibility · Code Quality · macOS & AppKit · Swift · SwiftUI · UIKit

**Sections:** Issue #49 · The efficiency of += · Ranged line limit in SwiftUI

**NeKI brief:** Curates this edition’s code-review material on The efficiency of +=, Ranged line limit in SwiftUI, and Accessibility for custom SwiftUI views. Use it to compare the linked techniques and follow each original source for its complete implementation context.

## [Issue 48](https://ioscodereview.com/issues/48)

- Published: `2023-05-11T12:53:06.000Z`

**Topics:** Developer Tools · macOS & AppKit · Performance · Swift · SwiftUI · UIKit

**Sections:** Issue #48 · Lightweight view initialization · Sorting user-entered strings

**NeKI brief:** Curates this edition’s code-review material on Lightweight view initialization, Sorting user-entered strings, and Modern UISegmentedControl. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [the Swift docs](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/stringsandcharacters?ref=ioscodereview.com) — Article · Topics: Swift
  **NeKI brief:** Examines the Swift docs in the context of Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Download free report](https://yo.bitrise.io/mobile-devops-assessment-report-2023-download.html) — Article · Topics: Cross-Platform & Web · Developer Tools
  **NeKI brief:** Examines Download free report in the context of Code Quality and Cross-Platform & Web. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 47](https://ioscodereview.com/issues/47)

- Published: `2023-04-28T10:30:39.000Z`

**Topics:** Code Quality · Combine & Reactive Programming · macOS & AppKit · Swift · SwiftUI · UIKit

**Sections:** Issue #47 · Use the right assertions · Private Set

**NeKI brief:** Curates this edition’s code-review material on Use the right assertions, Private Set, and Implementing reachability. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Use the right assertions](https://www.hackingwithswift.com/plus/intermediate-swift/understanding-assertions?ref=ioscodereview.com) — Article · Topics: Combine & Reactive Programming · Developer Tools · Swift
  **NeKI brief:** Examines Use the right assertions in the context of Combine & Reactive Programming and Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Download free report](https://yo.bitrise.io/mobile-devops-assessment-report-2023-download.html) — Article · Topics: Code Quality · Cross-Platform & Web
  **NeKI brief:** Examines Download free report in the context of Code Quality and Cross-Platform & Web. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Implementing reachability](https://www.avanderlee.com/swift/optimizing-network-reachability?ref=ioscodereview.com) — Article · Topics: Networking · Swift
  **NeKI brief:** Uses NWPathMonitor to observe connectivity without treating reachability as proof that a request will succeed. Useful for gating retries or UI hints while keeping the server response authoritative.
- [@available attribute](https://tanaschita.com/20230206-the-available-attribute-in-ios?ref=ioscodereview.com) — Article
  **NeKI brief:** Examines @available attribute in the context of Apple-platform engineering. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 46](https://ioscodereview.com/issues/46)

- Published: `2023-04-13T11:37:25.000Z`

**Topics:** macOS & AppKit · Swift · SwiftUI · Testing · UIKit · Xcode

**Sections:** Issue #46 · Iterating over some elements · Xcode 14.3 & Swift 5.8

**NeKI brief:** Curates this edition’s code-review material on Iterating over some elements and Xcode 14.3 & Swift 5.8. Use it to compare the linked techniques and follow each original source for its complete implementation context.

## [Issue 45](https://ioscodereview.com/issues/45)

- Published: `2023-03-16T13:58:41.000Z`

**Topics:** Core Data · macOS & AppKit · Persistence & Synchronisation · Swift · SwiftUI · UIKit

**Sections:** Issue #45 · Modern UIButton actions · Inline images in Text in SwiftUI

**NeKI brief:** Curates this edition’s code-review material on Modern UIButton actions, Inline images in Text in SwiftUI, and Deciphering Core Data error codes. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [CoreDataErrors.h as a gist on GitHub](https://gist.github.com/hishma/7cb505f94230ac7d7ed53d52a1e6dab6?ref=ioscodereview.com) — Source repository · Topics: Core Data · Developer Tools · Persistence & Synchronisation
  **NeKI brief:** Provides the source and change history for CoreDataErrors.h as a gist on GitHub, relevant to Core Data and Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.

## [Issue 44](https://ioscodereview.com/issues/44)

- Published: `2023-03-02T12:48:03.000Z`

**Topics:** Code Quality · macOS & AppKit · Swift · SwiftUI · Testing · UIKit

**Sections:** Issue #44 · Structuring unit tests · Don't change default params when subclassing

**NeKI brief:** Curates this edition’s code-review material on Structuring unit tests, Don't change default params when subclassing, and Delegate naming conventions. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Xcode Header Template for Swift PackagesIf you use Swift Package, there are 2 pesky problems whenever you create a new file.@samwize](https://samwize.com/2023/02/28/xcode-header-template-for-swift-packages?ref=ioscodereview.com) — Article · Topics: Swift · Swift Package Manager · Xcode
  **NeKI brief:** Examines Xcode Header Template for Swift PackagesIf you use Swift Package, there are 2 pesky problems whenever you… in the context of Swift and Swift Package Manager. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Learn about SwiftUI view lifecycle](https://github.com/ole/swiftui-view-lifecycle?ref=ioscodereview.com) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Provides the source and change history for Learn about SwiftUI view lifecycle, relevant to Developer Tools and Swift. Inspect its implementation, open issues, and release state before adopting the approach.
- [Delegate naming conventions](https://swiftbysundell.com/articles/delegation-in-swift?ref=ioscodereview.com) — Article · Topics: Swift
  **NeKI brief:** Examines Delegate naming conventions in the context of Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [bliki: GivenWhenThena bliki entry for GivenWhenThenmartinfowler.comMartin Fowler](https://martinfowler.com/bliki/GivenWhenThen.html?ref=ioscodereview.com) — Article · Topics: Cross-Platform & Web · Testing
  **NeKI brief:** Examines bliki: GivenWhenThena bliki entry for GivenWhenThenmartinfowler.comMartin Fowler in the context of Cross-Platform & Web and Testing. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 43](https://ioscodereview.com/issues/43)

- Published: `2023-02-14T12:18:23.000Z`

**Topics:** Developer Tools · macOS & AppKit · Swift · SwiftUI · Testing · UIKit

**Sections:** Issue #43 · Documenting hacks · Two ways to mock in tests

**NeKI brief:** Curates this edition’s code-review material on Documenting hacks, Two ways to mock in tests, and Don't subclass URLCache. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Two ways to mock in tests](https://mdb1.github.io/2023-02-13-enhancing-testability-with-protocols?ref=ioscodereview.com) — Article · Topics: Developer Tools · Testing
  **NeKI brief:** Examines Two ways to mock in tests in the context of Developer Tools and Testing. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [What's new in Swift - a refresher](https://www.swiftwithvincent.com/blog/discover-some-new-features-of-swift-5-7?ref=ioscodereview.com) — Article · Topics: Swift · Xcode
  **NeKI brief:** Summarises What's new in Swift - a refresher for Swift and Xcode. Use it to identify the relevant changes and follow its primary links before relying on version-sensitive details.
- [Pull request merge queue (public beta) | GitHub ChangelogPull request merge queue (public beta)The GitHub Blog](https://github.blog/changelog/2023-02-08-pull-request-merge-queue-public-beta?ref=ioscodereview.com) — Article · Topics: Developer Tools
  **NeKI brief:** Examines Pull request merge queue (public beta) | GitHub ChangelogPull request merge queue (public beta)The GitHub Blog in the context of Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Don't subclass URLCache](https://zhuk.fi/subclassing-urlcache?ref=ioscodereview.com) — Article
  **NeKI brief:** Examines Don't subclass URLCache in the context of Apple-platform engineering. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 42](https://ioscodereview.com/issues/42)

- Published: `2023-02-02T14:07:19.000Z`

**Topics:** macOS & AppKit · Performance · Swift · SwiftUI · Testing · UIKit

**Sections:** Issue #42 · Speeding app launch by improving code · Optimizing code performance

**NeKI brief:** Curates this edition’s code-review material on Speeding app launch by improving code, Optimizing code performance, and Improving linting speed. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Improving linting speed](https://github.com/steven851007/SwiftLint_build_phase_example?ref=ioscodereview.com) — Source repository · Topics: Developer Tools · Swift · Xcode
  **NeKI brief:** Provides the source and change history for Improving linting speed, relevant to Developer Tools and Swift. Inspect its implementation, open issues, and release state before adopting the approach.

## [Issue 41](https://ioscodereview.com/issues/41)

- Published: `2023-01-19T13:15:00.000Z`

**Topics:** Architecture · Code Quality · macOS & AppKit · Swift · SwiftUI · UIKit

**Sections:** Issue #41 · My favorite architecture · VStack, LazyVStack vs List

**NeKI brief:** Curates this edition’s code-review material on My favorite architecture, VStack, LazyVStack vs List, and On technical debt. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [VStack, LazyVStack vs List](https://www.donnywals.com/implementing-an-infinite-scrolling-list-with-swiftui-and-combine?ref=ioscodereview.com) — Article · Topics: Combine & Reactive Programming · Swift · SwiftUI
  **NeKI brief:** Infinite scrolling triggers pagination near a list boundary, but backpressure and duplicate-request guards are needed when appearance callbacks repeat.

## [Issue 40](https://ioscodereview.com/issues/40)

- Published: `2023-01-05T13:13:42.000Z`

**Topics:** Accessibility · macOS & AppKit · Swift · SwiftUI · Testing · UIKit

**Sections:** Issue #40 · Ordered dictionary anyone? · Using Label in SwiftUI

**NeKI brief:** Curates this edition’s code-review material on Ordered dictionary anyone?, Using Label in SwiftUI, and Accessibility of images in SwiftUI. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Using Label in SwiftUI](https://sarunw.com/posts/swiftui-label-a-standard-way-to-label-user-interface-items?ref=ioscodereview.com) — Article · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Use SwiftUI Label to pair text with an icon using system-adaptive semantics and styles. It communicates the relationship to accessibility and platform conventions more clearly than independently arranged image and text views for standard labeled actions.
- [Accessibility of images in SwiftUI](https://nilcoalescing.com/blog/ImageAccessibilityLabelsFromLocalizableStringsFiles?ref=ioscodereview.com) — Article · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Explains SwiftUI's localized image-label lookup, where a matching localization key can supply an accessibility label without repeating modifier text. It also highlights the naming dependency to verify when localization changes.
- [Ordered dictionary anyone?](https://github.com/apple/swift-collections?ref=ioscodereview.com) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the source and change history for Ordered dictionary anyone?, relevant to Developer Tools and Swift. Inspect its implementation, open issues, and release state before adopting the approach.
- [Better XCTest failure messages](https://qualitycoding.org/unit-test-optionals-swift?ref=ioscodereview.com) — Article · Topics: Swift · Testing
  **NeKI brief:** Examines Better XCTest failure messages in the context of Swift and Testing. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [OrderedDictionary In SwiftLearn how and when to use OrderedDictionary, provided by the swift-collections package, in Swift.Advanced SwiftRobert Pieta](https://www.advancedswift.com/ordereddictionary?ref=ioscodereview.com) — Article · Topics: Swift
  **NeKI brief:** Examines OrderedDictionary In SwiftLearn how and when to use OrderedDictionary, provided by the swift-collections… in the context of Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 39](https://ioscodereview.com/issues/39)

- Published: `2022-12-15T12:06:43.000Z`

**Topics:** Code Quality · macOS & AppKit · Swift · SwiftUI · Testing · UIKit

**Sections:** Issue #39 · Supporting webp images with PHPicker · Equality vs Identity

**NeKI brief:** Curates this edition’s code-review material on Supporting webp images with PHPicker, Equality vs Identity, and More formatter coolness. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [large number separators — Swift with VincentHere’s the code if you want to experiment with it!Swift with VincentVincent Pradeilles](https://www.swiftwithvincent.com/tips/large-number-separators?ref=ioscodereview.com) — Article · Topics: Swift
  **NeKI brief:** Examines large number separators — Swift with VincentHere’s the code if you want to experiment with it!Swift with… in the context of Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 38](https://ioscodereview.com/issues/38)

- Published: `2022-12-01T13:37:36.000Z`

**Topics:** Code Quality · macOS & AppKit · Swift · SwiftUI · UIKit · Xcode

**Sections:** Issue #38 · Modern collection views · xcconfig files

**NeKI brief:** Curates this edition’s code-review material on Modern collection views, xcconfig files, and Custom screenshot support. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Development Assets in Xcode to enrich SwiftUI Previews](https://www.avanderlee.com/xcode/development-assets-preview-catalog?ref=ioscodereview.com) — Article · Topics: Swift · SwiftUI · Xcode
  **NeKI brief:** Shows development asset catalogs providing preview-only resources and sample data without shipping them in production. This keeps SwiftUI previews rich while controlling bundle contents.
- [xcconfig files](https://www.danijelavrzan.com/posts/2022/11/xcode-configuration?ref=ioscodereview.com) — Article · Topics: Xcode
  **NeKI brief:** Explores How to manage build settings using Xcode configuration files, focusing on are you using xcconfig files? whenever i link to an. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.

## [Issue 37](https://ioscodereview.com/issues/37)

- Published: `2022-11-18T11:51:59.000Z`

**Topics:** macOS & AppKit · Swift · SwiftUI · Testing · UIKit · Xcode

**Sections:** Issue #37 · Structuring SwiftUI views · Organizing test image assets

**NeKI brief:** Curates this edition’s code-review material on Structuring SwiftUI views, Organizing test image assets, and Project quality-of-life. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Codelime](https://onmyway133.com/codelime?ref=ioscodereview.com) — Article · Topics: Graphics, Media & Games · Xcode
  **NeKI brief:** Examines Codelime in the context of Concurrency and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [URLRequest cache policies](https://tanaschita.com/20221031-managing-cache-when-working-with-urlsession-in-ios?ref=ioscodereview.com) — Article · Topics: Networking
  **NeKI brief:** URLRequest cache policies control reuse, validation and network freshness. The comparison is useful for choosing per-request behavior rather than applying a global cache assumption to every endpoint.

## [Issue 36](https://ioscodereview.com/issues/36)

- Published: `2022-11-04T13:07:52.000Z`

**Topics:** Code Quality · Developer Career & Practice · macOS & AppKit · Swift · SwiftUI · UIKit

**Sections:** [bonus issue] Issue #36 · Managing secrets · Writing a perfect pull request

**NeKI brief:** Curates this edition’s code-review material on bonus issue] Issue #36, Managing secrets, and Writing a perfect pull request. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Secret Management on iOS - NSHipster](https://nshipster.com/secrets?ref=ioscodereview.com) — Article · Topics: Developer Career & Practice
  **NeKI brief:** Discusses managing secrets in iOS projects and the risks of embedding credentials in app binaries. Use it to route Keychain, build configuration, and server-mediated secret handling decisions.
- [How To Write The PERFECT Pull Request | Level Up Coding](https://levelup.gitconnected.com/how-to-write-the-perfect-pull-request-d044625ace98?gi=6a8f584c2877&ref=ioscodereview.com) — Article · Topics: Developer Tools
  **NeKI brief:** Walks through how To Write The PERFECT Pull Request | Level Up Coding, with practical context for Developer Tools. Use it when implementing the workflow, while checking current tool and platform versions before copying the setup.

## [Issue 35](https://ioscodereview.com/issues/35)

- Published: `2022-11-03T12:33:05.000Z`

**Topics:** Accessibility · Concurrency · Swift · SwiftUI · Testing · UIKit

**Sections:** Issue #35 · Better test assertions · Multiple accessibility labels

**NeKI brief:** Curates this edition’s code-review material on Better test assertions, Multiple accessibility labels, and System background. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Codelime](https://onmyway133.com/codelime?ref=ioscodereview.com) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Examines Codelime in the context of Concurrency and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Swift Concurrency – Things They Don’t Tell You](https://wojciechkulik.pl/ios/swift-concurrency-things-they-dont-tell-you?ref=ioscodereview.com) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explores The Things They Don’t Tell You About Swift Concurrency, focusing on i’m not sure i particularly agree with the introduction of. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.

## [Issue 34](https://ioscodereview.com/issues/34)

- Published: `2022-10-20T11:05:16.000Z`

**Topics:** Accessibility · macOS & AppKit · Performance · Swift · SwiftUI · UIKit

**Sections:** Issue #34 · Organising package manifests · Localised lists

**NeKI brief:** Curates this edition’s code-review material on Organising package manifests, Localised lists, and Year formatting. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Accessibility in SwiftUI explained for UIKit developers - SwiftLee](https://www.avanderlee.com/swiftui/accessibility-uikit-developers?ref=ioscodereview.com) — Article · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Maps UIKit accessibility concepts to SwiftUI modifiers for labels, traits, grouping, and adjustable controls. Useful for porting accessibility behavior deliberately instead of assuming visual SwiftUI structure is automatically semantic.
- [SwiftUI performance tips – martinmitrevski](https://martinmitrevski.com/2022/04/14/swiftui-performance-tips?ref=ioscodereview.com) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI performance tips – martinmitrevski in the context of Performance and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 33](https://ioscodereview.com/issues/33)

- Published: `2022-10-06T11:12:57.000Z`

**Topics:** Code Quality · macOS & AppKit · Objective-C & Cocoa · Swift · SwiftUI · UIKit

**Sections:** Issue #33 · Traversing the view hierarchy · Completion handlers

**NeKI brief:** Curates this edition’s code-review material on Traversing the view hierarchy, Completion handlers, and Better TODO warnings. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Efficiently Develop Cleaner SwiftUI Views Using A View Model](https://www.curiousalgorithm.com/post/efficiently-develop-cleaner-swiftui-views-using-a-view-model?ref=ioscodereview.com) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines Efficiently Develop Cleaner SwiftUI Views Using A View Model in the context of Swift and SwiftUI. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Initialization — The Swift Programming Language (Swift 5.7)](https://docs.swift.org/swift-book/LanguageGuide/Initialization.html?ref=ioscodereview.com) — Article · Topics: Cross-Platform & Web · Swift
  **NeKI brief:** Examines Initialization — The Swift Programming Language (Swift 5.7) in the context of Cross-Platform & Web and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 32](https://ioscodereview.com/issues/32)

- Published: `2022-09-22T10:30:02.000Z`

**Topics:** Code Quality · macOS & AppKit · Security & Privacy · Swift · SwiftUI · UIKit

**Sections:** Issue #32 · Is it SwiftUI's fault? · Swift 5.7 is here!

**NeKI brief:** Curates this edition’s code-review material on Is it SwiftUI's fault?, Swift 5.7 is here!, and Compiler errors ftw. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [the official overview](https://www.swift.org/blog/swift-language-updates-from-wwdc22?ref=ioscodereview.com) — Article · Topics: Apple Platform Ecosystem · Swift
  **NeKI brief:** Explores Swift language announcements from WWDC22, focusing on it’s easy to get distracted by all the swiftui, uikit. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [the full list of evolution proposals released in 5.7](https://www.swift.org/blog/swift-5.7-released?ref=ioscodereview.com) — Article · Topics: Swift
  **NeKI brief:** Summarises the full list of evolution proposals released in 5.7 for Swift. Use it to identify the relevant changes and follow its primary links before relying on version-sensitive details.

## [Issue 31](https://ioscodereview.com/issues/31)

- Published: `2022-09-08T10:50:25.000Z`

**Topics:** Code Quality · Concurrency · macOS & AppKit · Swift · SwiftUI · UIKit

**Sections:** Issue #31 · On [weak] self (again) · Thoughts on massive observable objects

**NeKI brief:** Curates this edition’s code-review material on On [weak] self (again), Thoughts on massive observable objects, and Actions in @Environment. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Callable structs](https://docs.swift.org/swift-book/ReferenceManual/Declarations.html?ref=ioscodereview.com) — Article · Topics: Cross-Platform & Web · Swift
  **NeKI brief:** Examines Callable structs in the context of Cross-Platform & Web and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [The Golden Rules of weak self | Chris Downie](https://chrisdownie.net/software/2022/04/10/the-golden-rules-of-weak-self?ref=ioscodereview.com) — Article · Topics: Swift
  **NeKI brief:** Examines The Golden Rules of weak self | Chris Downie in the context of Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 30](https://ioscodereview.com/issues/30)

- Published: `2022-08-25T11:13:00.000Z`

**Topics:** App Services & Extensions · macOS & AppKit · Networking · Swift · SwiftUI · UIKit

**Sections:** Issue #30 · On push notifications · The sum effort

**NeKI brief:** Curates this edition’s code-review material on On push notifications, The sum effort, and Better equality test failures. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Difference](https://github.com/krzysztofzablocki/Difference?ref=ioscodereview.com) — Source repository · Topics: Developer Tools · Testing
  **NeKI brief:** Provides the source and change history for the Difference library, relevant to Developer Tools and Foundation & Data Formats. Inspect its implementation, open issues, and release state before adopting the approach.
- [Duplication - Code with Jason](https://www.codewithjason.com/duplication?ref=ioscodereview.com) — Article
  **NeKI brief:** Examines Duplication - Code with Jason in the context of Apple-platform engineering. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [https://youtu.be/CgTqqkzeeh8](https://youtu.be/CgTqqkzeeh8?ref=ioscodereview.com) — Video
  **NeKI brief:** Records https://youtu.be/CgTqqkzeeh8 as a visual walkthrough relevant to Apple-platform engineering. Use it to inspect the demonstrated workflow, then verify version-specific details with current primary sources.

## [Issue 29](https://ioscodereview.com/issues/29)

- Published: `2022-08-11T10:30:02.000Z`

**Topics:** Developer Tools · macOS & AppKit · Swift · SwiftUI · Testing · UIKit

**Sections:** Issue #29 · Implicit weak self is coming · The background modifier

**NeKI brief:** Curates this edition’s code-review material on Implicit weak self is coming, The background modifier, and Testing the mocks. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Thread Safety in Swift](https://swiftrocks.com/thread-safety-in-swift?ref=ioscodereview.com) — Article · Topics: Concurrency · Performance · Swift
  **NeKI brief:** Examines Thread Safety in Swift in the context of Concurrency and Performance. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [swift-evolution/0365-implicit-self-weak-capture.md · apple/swift-evolution · GitHub](https://github.com/apple/swift-evolution/blob/main/proposals/0365-implicit-self-weak-capture.md?ref=ioscodereview.com) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the source and change history for swift-evolution/0365-implicit-self-weak-capture.md · apple/swift-evolution · GitHub, relevant to Developer Tools and Swift. Inspect its implementation, open issues, and release state before adopting the approach.
- [SE-0269](https://github.com/apple/swift-evolution/blob/main/proposals/0269-implicit-self-explicit-capture.md?ref=ioscodereview.com) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the source and change history for SE-0269, relevant to Developer Tools and Swift. Inspect its implementation, open issues, and release state before adopting the approach.

## [Issue 28](https://ioscodereview.com/issues/28)

- Published: `2022-07-28T11:12:02.000Z`

**Topics:** Dependency Injection · Foundation & Data Formats · macOS & AppKit · Swift · SwiftUI · Testing

**Sections:** Issue #28 · Live-updating cells · Approaches to mocking

**NeKI brief:** Curates this edition’s code-review material on Live-updating cells, Approaches to mocking, and On code readability. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [How to test custom Codable initializer | Danijela's blog](https://danijelavrzan.com/posts/2022/07/how-to-test-custom-codable?ref=ioscodereview.com) — Article · Topics: Foundation & Data Formats · Testing
  **NeKI brief:** Walks through how to test custom Codable initializer | Danijela's blog, with practical context for Foundation & Data Formats and Testing. Use it when implementing the workflow, while checking current tool and platform versions before copying the setup.
- [the Difference library](https://github.com/krzysztofzablocki/Difference?ref=ioscodereview.com) — Source repository · Topics: Developer Tools · Foundation & Data Formats · Testing
  **NeKI brief:** Provides the source and change history for the Difference library, relevant to Developer Tools and Foundation & Data Formats. Inspect its implementation, open issues, and release state before adopting the approach.

## [Issue 27](https://ioscodereview.com/issues/27)

- Published: `2022-07-14T11:10:44.000Z`

**Topics:** Core Data · macOS & AppKit · Persistence & Synchronisation · Swift · SwiftUI · UIKit

**Sections:** Issue #27 · Using unsafe pointers safely · DRY, evolved

**NeKI brief:** Curates this edition’s code-review material on Using unsafe pointers safely, DRY, evolved, and Beautiful rounded corners. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [How to more gracefully handle non-optional Core Data properties in Swift · Jesse Squires](https://www.jessesquires.com/blog/2022/01/26/core-data-optionals?ref=ioscodereview.com) — Article · Topics: Core Data · Persistence & Synchronisation · Swift
  **NeKI brief:** Explores follow up post from Jesse Squires, focusing on the article discusses heard you like optionals, so i put an optional in your optional. Follow it to assess the approach, its trade-offs, and where it fits in a current Swift or Apple-platform project.
- [App Transfer Criteria](https://help.apple.com/app-store-connect?ref=ioscodereview.com) — Article
  **NeKI brief:** Examines App Transfer Criteria in the context of Apple-platform engineering. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 26](https://ioscodereview.com/issues/26)

- Published: `2022-06-30T10:52:20.000Z`

**Topics:** Code Quality · macOS & AppKit · Persistence & Synchronisation · Swift · SwiftUI · UIKit

**Sections:** Issue #26 · Accessible custom tab bars · Interactive image preview transition

**NeKI brief:** Curates this edition’s code-review material on Accessible custom tab bars, Interactive image preview transition, and Sink. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Building an Accessible Custom Tab Bar | Bas’ Blog](https://www.basbroek.nl/custom-tab-bar-accessibility?ref=ioscodereview.com) — Article · Topics: Accessibility
  **NeKI brief:** Explores Building an Accessible Custom Tab Bar, focusing on the very best way to ensure that the tab bar. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [General Findings About NSPersistentCloudKitContainer](https://crunchybagel.com/nspersistentcloudkitcontainer?ref=ioscodereview.com) — Article · Topics: Persistence & Synchronisation
  **NeKI brief:** Examines General Findings About NSPersistentCloudKitContainer in the context of Persistence & Synchronisation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 25](https://ioscodereview.com/issues/25)

- Published: `2022-06-16T10:30:01.000Z`

**Topics:** Developer Tools · macOS & AppKit · Swift · SwiftUI · Testing · UIKit

**Sections:** Issue #25 · #unavailable attribute · Dealing with SwiftUI type inference

**NeKI brief:** Curates this edition’s code-review material on #unavailable attribute, Dealing with SwiftUI type inference, and Unit tests eh?. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [#unavailable](https://docs.swift.org/swift-book/ReferenceManual/Attributes.html?ref=ioscodereview.com) — Article · Topics: Cross-Platform & Web · Swift · Xcode
  **NeKI brief:** Examines #unavailable in the context of Cross-Platform & Web and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [AppForce1 podcast](https://www.buzzsprout.com/1414396/10721946?ref=ioscodereview.com) — Podcast · Topics: Developer Community & Business
  **NeKI brief:** Examines AppForce1 podcast in the context of Developer Community & Business. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 24](https://ioscodereview.com/issues/24)

- Published: `2022-06-02T10:41:20.000Z`

**Topics:** Accessibility · Apple Platform Ecosystem · macOS & AppKit · Swift · SwiftUI · UIKit

**Sections:** Issue #24 · Accessibility hints · Attributed Strings

**NeKI brief:** Curates this edition’s code-review material on Accessibility hints, Attributed Strings, and Equal sizing in SwiftUI. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [AttributedString Attribute Scopes](https://nilcoalescing.com/blog/AttributedStringAttributeScopes?ref=ioscodereview.com) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** AttributedString attribute scopes constrain which custom and Foundation attributes are available through typed lookup. The article helps design safe rich-text transformations without stringly-typed keys or accidental scope collisions.
- [SwiftUI equal and ideal sizes](https://sudrocket.de/blog/2022/05/swiftui-equal-and-ideal-sizes?ref=ioscodereview.com) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI equal and ideal sizes in the context of Swift and SwiftUI. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 23](https://ioscodereview.com/issues/23)

- Published: `2022-05-19T11:03:01.000Z`

**Topics:** Architecture · Dependency Injection · macOS & AppKit · Security & Privacy · Swift · Testing

**Sections:** Issue #23 · Sizing of SF Symbols · Automating the encryption compliance check

**NeKI brief:** Curates this edition’s code-review material on Sizing of SF Symbols, Automating the encryption compliance check, and Comparing date ranges. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Unit testing: The pragmatic guide on where to start | Marina Gornostaeva](https://hybridcattt.com/blog/start-testing-pragmatic-guide?ref=ioscodereview.com) — Article · Topics: Testing
  **NeKI brief:** Examines Unit testing: The pragmatic guide on where to start | Marina Gornostaeva in the context of Testing. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 22](https://ioscodereview.com/issues/22)

- Published: `2022-05-05T10:51:40.000Z`

**Topics:** Code Quality · Dependency Injection · macOS & AppKit · Swift · SwiftUI · UIKit

**Sections:** Issue #22 · Updating @State values · Disabling animation on a View

**NeKI brief:** Curates this edition’s code-review material on Updating @State values, Disabling animation on a View, and forEach vs for. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [The Hidden Costs of Your Dependencies | Jason Zurita](https://jasonzurita.com/the-hidden-cost-of-dependencies?ref=ioscodereview.com) — Article · Topics: Dependency Injection
  **NeKI brief:** Examines The Hidden Costs of Your Dependencies | Jason Zurita in the context of Dependency Injection. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 21](https://ioscodereview.com/issues/21)

- Published: `2022-04-21T11:21:14.000Z`

**Topics:** Concurrency · Foundation & Data Formats · macOS & AppKit · Persistence & Synchronisation · Swift · SwiftUI

**Sections:** Issue #21 · MainActor.run vs @MainActor · Synchronizing user defaults

**NeKI brief:** Curates this edition’s code-review material on MainActor.run vs @MainActor, Synchronizing user defaults, and Codable in Firebase. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [comprehensive guide](https://peterfriese.dev/posts/firestore-codable-the-comprehensive-guide?ref=ioscodereview.com) — Article · Topics: Foundation & Data Formats
  **NeKI brief:** Examines comprehensive guide in the context of Foundation & Data Formats. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Wikipedia](https://en.wikipedia.org/wiki/Code_refactoring?ref=ioscodereview.com) — Article · Topics: Concurrency
  **NeKI brief:** Examines Wikipedia in the context of Concurrency. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [this article by Paul Hudson](https://www.hackingwithswift.com/quick-start/concurrency/how-to-use-mainactor-to-run-code-on-the-main-queue?ref=ioscodereview.com) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Examines this article by Paul Hudson in the context of Concurrency and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [CodableFirebase](https://github.com/alickbass/CodableFirebase?ref=ioscodereview.com) — Source repository · Topics: Developer Tools · Foundation & Data Formats
  **NeKI brief:** Provides the source and change history for CodableFirebase, relevant to Developer Tools and Foundation & Data Formats. Inspect its implementation, open issues, and release state before adopting the approach.
- [iCloud red flag for indie developers](https://jknlsn.com/posts/2022-03-24-icloud-redflag-for-indie-developers?ref=ioscodereview.com) — Article
  **NeKI brief:** Examines iCloud red flag for indie developers in the context of Apple-platform engineering. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 20](https://ioscodereview.com/issues/20)

- Published: `2022-04-07T10:47:31.000Z`

**Topics:** Code Quality · Hardware & Devices · macOS & AppKit · Swift · SwiftUI · UIKit

**Sections:** Issue #20 · Old new UIKit APIs · Array slice indices

**NeKI brief:** Curates this edition’s code-review material on Old new UIKit APIs, Array slice indices, and Int vs UInt. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Using UITabBarAppearance for Tab Bar changes in iOS 13](https://emptytheory.com/2019/12/31/using-uitabbarappearance-for-tab-bar-changes-in-ios-13?ref=ioscodereview.com) — Article · Topics: UIKit
  **NeKI brief:** Examines Using UITabBarAppearance for Tab Bar changes in iOS 13 in the context of UIKit. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [UINavigationBar changes in iOS 13](https://sarunw.com/posts/uinavigationbar-changes-in-ios13?ref=ioscodereview.com) — Article · Topics: UIKit
  **NeKI brief:** Details iOS 13 UINavigationBar appearance changes and the new appearance APIs. Follow it when a navigation bar unexpectedly changes styling after deployment and you need deterministic standard, compact, and scroll-edge configuration.
- [the official Swift documentation](https://docs.swift.org/swift-book/LanguageGuide/TheBasics.html?ref=ioscodereview.com) — Article · Topics: Cross-Platform & Web · Swift
  **NeKI brief:** Examines the official Swift documentation in the context of Cross-Platform & Web and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Apply "Broken-Windows" theory to the Software Design](https://www.offnotes.org/apply-broken-windows-theory-to-the-software-design?ref=ioscodereview.com) — Article
  **NeKI brief:** Examines Apply "Broken-Windows" theory to the Software Design in the context of Apple-platform engineering. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 19](https://ioscodereview.com/issues/19)

- Published: `2022-03-24T11:50:04.000Z`

**Topics:** Code Quality · Concurrency · macOS & AppKit · Swift · SwiftUI · UIKit

**Sections:** Issue #19 · The Code Review Pyramid · Struct properties - var or let?

**NeKI brief:** Curates this edition’s code-review material on The Code Review Pyramid, Struct properties - var or let?, and Decoding corrupted arrays with Codable. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Fixing SwiftUI’s Automatic Preview Updating Paused | Marina Gornostaeva](https://hybridcattt.com/blog/fixing-swiftui-previews?ref=ioscodereview.com) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explores Fixing SwiftUI’s Automatic Preview Updating Paused, focusing on the article discusses love this idea from marina gornostaeva for. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [The Code Review Pyramid](https://www.morling.dev/blog/the-code-review-pyramid?ref=ioscodereview.com) — Article · Topics: Code Quality
  **NeKI brief:** Examines The Code Review Pyramid in the context of Code Quality. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Decode an array with a corrupted element | Sarunw](https://sarunw.com/posts/decode-array-with-corrupted-element?ref=ioscodereview.com) — Article · Topics: Foundation & Data Formats
  **NeKI brief:** Codable normally fails an entire array when one element violates its schema, which is the right default for controlled APIs. For legacy or third-party data, decode elements through a lossy optional wrapper, discard failures deliberately, and log the data-quality trade-off.
- [Refactoring Uber's Rider app • Space is Disorienting](http://spaceisdisorienting.com/refactoring-the-uber-rider-app?ref=ioscodereview.com) — Article · Topics: Concurrency
  **NeKI brief:** Examines Refactoring Uber's Rider app • Space is Disorienting in the context of Concurrency. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 18](https://ioscodereview.com/issues/18)

- Published: `2022-03-10T11:47:29.000Z`

**Topics:** App Distribution & Store Operations · Code Quality · macOS & AppKit · Swift · SwiftUI · UIKit

**Sections:** Issue #18 · Documenting app's footprint · Named loops

**NeKI brief:** Curates this edition’s code-review material on Documenting app's footprint, Named loops, and Text or String?. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Swift’s Break and Continue Statements by Andy Bargh](https://andybargh.com/break-and-continue?ref=ioscodereview.com) — Article · Topics: Swift
  **NeKI brief:** Examines Swift’s Break and Continue Statements by Andy Bargh in the context of Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 17](https://ioscodereview.com/issues/17)

- Published: `2022-02-24T11:04:06.000Z`

**Topics:** Architecture · Code Quality · macOS & AppKit · Objective-C & Cocoa · Swift · SwiftUI

**Sections:** Issue #17 · Uninitialized variables + defer = 👯‍♀️ · HttpServer or HTTPServer?

**NeKI brief:** Curates this edition’s code-review material on Uninitialized variables + defer = 👯‍♀️, HttpServer or HTTPServer?, and Representing measurement units. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Swift API design guidelines](https://swift.org/documentation/api-design-guidelines?ref=ioscodereview.com) — Article · Topics: Code Quality · Swift
  **NeKI brief:** Examines API guidelines, focusing on ash furrow with a great article on the flexibility swift has around naming. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [TabView](https://swiftontap.com/tabview?ref=ioscodereview.com) — Article · Topics: Developer Community & Business · Swift · SwiftUI
  **NeKI brief:** Examines TabView in the context of Developer Community & Business and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 16](https://ioscodereview.com/issues/16)

- Published: `2022-02-10T11:16:37.000Z`

**Topics:** Concurrency · Developer Career & Practice · macOS & AppKit · Swift · SwiftUI · UIKit

**Sections:** Issue #16 · Managing image assets · Use Labels in SwiftUI

**NeKI brief:** Curates this edition’s code-review material on Managing image assets, Use Labels in SwiftUI, and On counting characters. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Memory management when using async/await in Swift | Swift by Sundell](https://swiftbysundell.com/articles/memory-management-when-using-async-await?ref=ioscodereview.com) — Article · Topics: Concurrency · Developer Career & Practice · Swift
  **NeKI brief:** Examines Memory management when using async/await in Swift | Swift by Sundell in the context of Concurrency and Developer Career & Practice. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 15](https://ioscodereview.com/issues/15)

- Published: `2022-01-27T11:57:44.000Z`

**Topics:** Localization · macOS & AppKit · Swift · SwiftUI · UIKit · Xcode

**Sections:** Issue #15 · On mixing Swift and ObjC · Golden path

**NeKI brief:** Curates this edition’s code-review material on On mixing Swift and ObjC, Golden path, and @discardableResult. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [How to solve a data race](https://www.avanderlee.com/swift/thread-sanitizer-data-races?ref=ioscodereview.com) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Shows how Thread Sanitizer instruments Swift tests and apps to detect conflicting memory accesses, then interprets reports. It is a practical diagnostic for races that rarely reproduce.
- [Typos in Xcode – Never Again!](https://fbernutz.github.io/posts/2022-01-23-spelling-grammar-in-xcode?ref=ioscodereview.com) — Article · Topics: Developer Tools · Xcode
  **NeKI brief:** Examines Typos in Xcode – Never Again! in the context of Developer Tools and Xcode. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [An Approach for Migrating From Objective-C to Swift](https://www.steveonstuff.com/2022/01/13/migrating-from-objc-to-swift.html?ref=ioscodereview.com) — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **NeKI brief:** Explores An Approach for Migrating From Objective-C to Swift, focusing on moving a codebase of any reasonable size from objective-c to. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [‎Apple Style Guide on Apple Books](https://books.apple.com/book/id1161855204?ref=ioscodereview.com) — Article
  **NeKI brief:** Examines Apple Style Guide on Apple Books in the context of Apple-platform engineering. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Wikipedia describes](https://en.wikipedia.org/wiki/Happy_path?ref=ioscodereview.com) — Article · Topics: Swift
  **NeKI brief:** Examines Wikipedia describes in the context of Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 14](https://ioscodereview.com/issues/14)

- Published: `2022-01-13T12:22:06.000Z`

**Topics:** App Distribution & Store Operations · macOS & AppKit · Objective-C & Cocoa · Swift · SwiftUI · Testing

**Sections:** Issue #14 · On counting words · Working with years in dates

**NeKI brief:** Curates this edition’s code-review material on On counting words, Working with years in dates, and Custom date formats, localized. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [the official Unicode documentation](http://unicode.org/reports/tr35/tr35-31/tr35-dates.html?ref=ioscodereview.com) — Article · Topics: Cross-Platform & Web · Foundation & Data Formats · Testing
  **NeKI brief:** Examines the official Unicode documentation in the context of Cross-Platform & Web and Foundation & Data Formats. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [GitHub - russell-archer/StoreHelper](https://github.com/russell-archer/StoreHelper?ref=ioscodereview.com) — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Testing
  **NeKI brief:** Provides the source and change history for GitHub - russell-archer/StoreHelper, relevant to Developer Tools and Objective-C & Cocoa. Inspect its implementation, open issues, and release state before adopting the approach.
- [GitHub - russell-archer/IAPDemo](https://github.com/russell-archer/IAPDemo?ref=ioscodereview.com) — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Testing
  **NeKI brief:** Provides the source and change history for GitHub - russell-archer/IAPDemo, relevant to Developer Tools and Objective-C & Cocoa. Inspect its implementation, open issues, and release state before adopting the approach.

## [Issue 13](https://ioscodereview.com/issues/13)

- Published: `2021-12-09T12:01:55.000Z`

**Topics:** Code Quality · Developer Tools · macOS & AppKit · Swift · SwiftUI · UIKit

**Sections:** Issue #13 · Changes to app launch sequence · Learning from CLLocation APIs

**NeKI brief:** Curates this edition’s code-review material on Changes to app launch sequence, Learning from CLLocation APIs, and Printing HTTP status codes. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Mastering GroupBox in SwiftUI on Swift with Majid](https://swiftwithmajid.com/2020/10/15/mastering-groupbox-in-swiftui?ref=ioscodereview.com) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** GroupBox supplies a semantic, styleable container for related SwiftUI content. Use it when grouping improves scanning and platform adaptation, rather than adding visual boxes that do not express a real relationship.
- [GitHub - pointfreeco/swift-identified-collections](https://github.com/pointfreeco/swift-identified-collections?ref=ioscodereview.com) — Source repository · Topics: Developer Tools · Swift
  **NeKI brief:** Provides the source and change history for GitHub - pointfreeco/swift-identified-collections, relevant to Developer Tools and Swift. Inspect its implementation, open issues, and release state before adopting the approach.
- [Github repo](https://github.com/nemecek-filip/CompositionalDiffablePlayground.ios?ref=ioscodereview.com) — Source repository · Topics: Developer Tools
  **NeKI brief:** Examines Compositional Diffable Collection View Playground, focusing on i’ve enjoyed filip němeček’s posts on collection views recently, but there have been so many that it’s been hard to know…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against.
- [Solving Mysterious Logout Issues on iOS 15 | Source Diving](https://sourcediving.com/solving-mysterious-logout-issues-on-ios-15-8b818c089466?gi=bedb7055d213&ref=ioscodereview.com) — Article
  **NeKI brief:** Examines Solving Mysterious Logout Issues on iOS 15 | Source Diving in the context of Apple-platform engineering. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 12](https://ioscodereview.com/issues/12)

- Published: `2021-11-25T12:50:15.000Z`

**Topics:** Code Quality · Developer Tools · macOS & AppKit · Swift · SwiftUI · UIKit

**Sections:** Issue #12 · Tired of translatesAutoresizingMasksIntoConstraints? · Type-safe identifiers

**NeKI brief:** Curates this edition’s code-review material on Tired of translatesAutoresizingMasksIntoConstraints?, Type-safe identifiers, and Understanding SwiftUI navigation. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [GitHub - pointfreeco/swiftui-navigation: Tools for making SwiftUI navigation simpler, more ergonomic and more precise.](https://github.com/pointfreeco/swiftui-navigation?ref=ioscodereview.com) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Provides the source and change history for GitHub - pointfreeco/swiftui-navigation: Tools for making SwiftUI navigation simpler, more ergonomic and more…, relevant to Developer Tools and Swift. Inspect its implementation, open issues, and release state before adopting the approach.
- [@mecid wrote an article](https://swiftwithmajid.com/2021/02/18/phantom-types-in-swift?ref=ioscodereview.com) — Article · Topics: Swift
  **NeKI brief:** Phantom types encode compile-time distinctions without changing runtime storage. Use them to prevent invalid API combinations through generic constraints, while avoiding abstractions that make ordinary call sites difficult to understand.
- [his recent article](https://www.avanderlee.com/optimization/non-fatal-errors-vs-fatal-crashes?ref=ioscodereview.com) — Article
  **NeKI brief:** Distinguishes recoverable errors from process-terminating crashes and pairs crash-free sessions with non-fatal-error rates. Use it when telemetry should reveal degraded user journeys that never appear in a crash dashboard.

## [Issue 11](https://ioscodereview.com/issues/11)

- Published: `2021-11-11T13:07:22.000Z`

**Topics:** Code Quality · Graphics, Media & Games · macOS & AppKit · Swift · SwiftUI · UIKit

**Sections:** Issue #11 · On text truncation in SwiftUI · Compiler + enums = 🧡

**NeKI brief:** Curates this edition’s code-review material on On text truncation in SwiftUI, Compiler + enums = 🧡, and More on logging. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Michael Tsai - Blog - Dangerous NSLog() Calls in Swift](https://mjtsai.com/blog/2021/11/02/dangerous-nslog-calls-in-swift?ref=ioscodereview.com) — Article · Topics: Swift · Testing
  **NeKI brief:** Examines Michael Tsai - Blog - Dangerous NSLog() Calls in Swift in the context of Swift and Testing. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 10](https://ioscodereview.com/issues/10)

- Published: `2021-10-28T11:19:01.000Z`

**Topics:** Concurrency · macOS & AppKit · Swift · SwiftUI · UIKit · Xcode

**Sections:** Issue #10 · async/await is really here · print() vs os_log()

**NeKI brief:** Curates this edition’s code-review material on async/await is really here, print() vs os_log(), and Managing fallbacks. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Using iOS-15-only View modifiers in older iOS versions](https://www.ralfebert.de/swiftui/backporting-ios-view-modifiers?ref=ioscodereview.com) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines Using iOS-15-only View modifiers in older iOS versions in the context of Swift and SwiftUI. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [the best article ever about os_log](https://www.avanderlee.com/workflow/oslog-unified-logging?ref=ioscodereview.com) — Article
  **NeKI brief:** Examines the best article ever about os_log in the context of Apple-platform engineering. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Problems with os_log](https://mjtsai.com/blog/2019/03/06/problems-with-os_log?ref=ioscodereview.com) — Article
  **NeKI brief:** Examines Problems with os_log in the context of Apple-platform engineering. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 9](https://ioscodereview.com/issues/9)

- Published: `2021-10-14T13:09:40.000Z`

**Topics:** Developer Tools · macOS & AppKit · Swift · SwiftUI · Testing · UIKit

**Sections:** Issue #9 · ❤️ SwiftUI previews · On manipulating strings

**NeKI brief:** Curates this edition’s code-review material on SwiftUI previews, On manipulating strings, and SF Symbols. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [The Complete Guide to SF Symbols by Paul Hudson](https://www.hackingwithswift.com/articles/237/complete-guide-to-sf-symbols?ref=ioscodereview.com) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** SF Symbols provide semantic vector icons with weight and scale variants, keeping UI aligned with system typography while requiring availability and rendering-mode checks.
- [GitHub - theoriginalbit/PreviewView: Make use of SwiftUI Previews for UIKit!](https://github.com/theoriginalbit/PreviewView?ref=ioscodereview.com) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Provides the source and change history for GitHub - theoriginalbit/PreviewView: Make use of SwiftUI Previews for UIKit!, relevant to Developer Tools and Swift. Inspect its implementation, open issues, and release state before adopting the approach.
- [(Improving Your) XCTAssert* Failure Messages | Bas’ Blog](https://www.basbroek.nl/xctassert-asterisk?ref=ioscodereview.com) — Article · Topics: Testing
  **NeKI brief:** Examines Improving Your) XCTAssert* Failure Messages | Bas’ Blog in the context of Testing. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 8](https://ioscodereview.com/issues/8)

- Published: `2021-09-30T11:10:38.000Z`

**Topics:** Architecture · Concurrency · Dependency Injection · macOS & AppKit · Swift · UIKit

**Sections:** Issue #8 · Status of async/await · Catching errors

**NeKI brief:** Curates this edition’s code-review material on Status of async/await, Catching errors, and Modern dependency injection. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Swift 5.5 has serious stack corruption bugs! - Compiler - Swift Forums](https://forums.swift.org/t/swift-5-5-has-serious-stack-corruption-bugs/52344?ref=ioscodereview.com) — Article · Topics: Concurrency · Swift · Testing
  **NeKI brief:** Explores Stack Corruption Problems in Swift 5.5, focusing on it’s hard to say how widespread or severe the issues. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [overview](https://quickbirdstudios.com/blog/swift-dependency-injection-service-locators?ref=ioscodereview.com) — Article · Topics: Architecture · Dependency Injection · Swift
  **NeKI brief:** Examines overview in the context of Architecture and Dependency Injection. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Dependency Injection in Swift using latest Swift features - SwiftLee](https://www.avanderlee.com/swift/dependency-injection?ref=ioscodereview.com) — Article · Topics: Dependency Injection · Swift · Testing
  **NeKI brief:** Builds dependency injection with protocols and initializer defaults, then substitutes test doubles. The design separates construction from behavior while preserving convenient production call sites.
- [the official language reference on patterns in Swift](https://docs.swift.org/swift-book/ReferenceManual/Patterns.html?ref=ioscodereview.com) — Article · Topics: Cross-Platform & Web · Swift
  **NeKI brief:** Examines the official language reference on patterns in Swift in the context of Cross-Platform & Web and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Sarun's article](https://sarunw.com/posts/different-ways-to-catch-throwing-errors-in-swift?ref=ioscodereview.com) — Article · Topics: Swift
  **NeKI brief:** Handle Swift errors with ordered catch clauses that match the domain cases you can recover from, then preserve an explicit fallback for unexpected failures. Avoid collapsing every error into one generic path, because it hides user action, retry policy, and diagnostic context.
- [talk](https://vimeo.com/362202970?ref=ioscodereview.com) — Video · Topics: UIKit
  **NeKI brief:** Records talk as a visual walkthrough relevant to UIKit. Use it to inspect the demonstrated workflow, then verify version-specific details with current primary sources.

## [Issue 7](https://ioscodereview.com/issues/7)

- Published: `2021-09-16T10:10:03.000Z`

**Topics:** Code Quality · Combine & Reactive Programming · Developer Tools · macOS & AppKit · Swift · SwiftUI

**Sections:** Issue #7 · Crash in Combine · SwiftUI + Combine = 🧡

**NeKI brief:** Curates this edition’s code-review material on Crash in Combine, SwiftUI + Combine = 🧡, and Swift API design guidelines. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Swift.org - API Design Guidelines](https://swift.org/documentation/api-design-guidelines?ref=ioscodereview.com) — Article · Topics: Code Quality · Performance · Swift
  **NeKI brief:** Examines API guidelines, focusing on ash furrow with a great article on the flexibility swift has around naming. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [the documentation](https://git-scm.com/book/en/v2/Git-Tools-Revision-Selection?ref=ioscodereview.com) — Article · Topics: Developer Tools
  **NeKI brief:** Examines the documentation in the context of Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 6](https://ioscodereview.com/issues/6)

- Published: `2021-09-02T11:47:05.000Z`

**Topics:** Code Quality · Concurrency · macOS & AppKit · Swift · SwiftUI · UIKit

**Sections:** Issue #6 · Waiting on multiple async calls · Conditional modifiers are bad? 😬

**NeKI brief:** Curates this edition’s code-review material on Waiting on multiple async calls, Conditional modifiers are bad? 😬, and Timers, scrolling, run loops. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Why Conditional View Modifiers are a Bad Idea](https://www.objc.io/blog/2021/08/24/conditional-view-modifiers?ref=ioscodereview.com) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows why conditionally applying modifiers can change view identity and produce surprising layout or state behavior. The alternatives make the trade-off between type-safe composition and stable runtime structure explicit.

## [Issue 5](https://ioscodereview.com/issues/5)

- Published: `2021-08-19T12:22:37.000Z`

**Topics:** Developer Tools · macOS & AppKit · Swift · SwiftUI · Testing · UIKit

**Sections:** Issue #5 · Check your back buttons · On force unwrapping

**NeKI brief:** Curates this edition’s code-review material on Check your back buttons, On force unwrapping, and Testing throwing code. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Demystifying Git Rebase](https://www.thinktecture.com/en/tools/demystifying-git-rebase?ref=ioscodereview.com) — Article · Topics: Developer Tools
  **NeKI brief:** Examines Demystifying Git Rebase in the context of Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [A new way to manage the back button title in iOS 14 with backButtonDisplayMode | Sarunw](https://sarunw.com/posts/new-way-to-manage-back-button-title-in-ios14?ref=ioscodereview.com) — Article
  **NeKI brief:** Explains UINavigationItem.backButtonDisplayMode and the title sources it controls, including default, generic, and minimal behavior. It helps change a pushed screen's back label through the navigation item rather than replacing the system back button.

## [Issue 4](https://ioscodereview.com/issues/4)

- Published: `2021-08-05T14:19:35.000Z`

**Topics:** AI Development · Combine & Reactive Programming · Graphics, Media & Games · macOS & AppKit · Persistence & Synchronisation · Swift

**Sections:** Issue #4 · When not to use [weak self] · Lazy collections for speed

**NeKI brief:** Curates this edition’s code-review material on When not to use [weak self], Lazy collections for speed, and There's no secrets in UserDefaults. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [playground with four improvement iterations](https://github.com/hybridcattt/remix-copilot-swift-playground/blob/main/RemixCopilot.playground/Contents.swift?ref=ioscodereview.com) — Source repository · Topics: AI Development · Developer Tools · Swift
  **NeKI brief:** Provides the source and change history for playground with four improvement iterations, relevant to AI Development and Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [Watch full video on Youtube (6 min)](https://www.youtube.com/watch?v=YeGVrZJj-Mg&ref=ioscodereview.com) — Video · Topics: Graphics, Media & Games
  **NeKI brief:** Records Watch full video on Youtube (6 min) as a visual walkthrough relevant to Graphics, Media & Games. Use it to inspect the demonstrated workflow, then verify version-specific details with current primary sources.
- [Does 'assign(to:)' produce memory leaks? - Using Swift - Swift Forums](https://forums.swift.org/t/does-assign-to-produce-memory-leaks/29546?ref=ioscodereview.com) — Article · Topics: Combine & Reactive Programming · Swift
  **NeKI brief:** Examines Does 'assign(to:)' produce memory leaks? - Using Swift - Swift Forums in the context of Combine & Reactive Programming and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Watch on Youtube (4 min)](https://www.youtube.com/watch?v=UAgtOTOH2nQ&ref=ioscodereview.com) — Video
  **NeKI brief:** Records Watch on Youtube (4 min) as a visual walkthrough relevant to Apple-platform engineering. Use it to inspect the demonstrated workflow, then verify version-specific details with current primary sources.

## [Issue 3](https://ioscodereview.com/issues/3)

- Published: `2021-07-22T11:33:43.000Z`

**Topics:** Architecture · Combine & Reactive Programming · macOS & AppKit · Swift · SwiftUI · UIKit

**Sections:** Issue #3 · Architectures are for humans · Retain cycles with Combine

**NeKI brief:** Curates this edition’s code-review material on Architectures are for humans, Retain cycles with Combine, and Configuring SwiftUI views with Environment. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [article](https://swiftwithmajid.com/2019/08/21/the-power-of-environment-in-swiftui?ref=ioscodereview.com) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** SwiftUI Environment injects contextual values through a view hierarchy without parameter plumbing. The article is useful for system-level dependencies, but cautions against making feature-specific services invisible to tests.
- [changing width of columns in UISplitViewController](https://useyourloaf.com/blog/change-the-width-of-master-view-in-split-view-controller?ref=ioscodereview.com) — Article · Topics: UIKit
  **NeKI brief:** Customizes split-view primary-column width while respecting adaptive display modes. Width is part of navigation ergonomics, so constrain it with minimum readable content rather than one fixed pixel value.

## [Issue 2](https://ioscodereview.com/issues/2)

- Published: `2021-07-08T10:37:35.000Z`

**Topics:** AI Development · Code Quality · Concurrency · Developer Tools · Swift · Testing

**Sections:** Issue #2 · Function annotations for structs · Handling actions in UIButton

**NeKI brief:** Curates this edition’s code-review material on Function annotations for structs, Handling actions in UIButton, and On testing and refactoring. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [Mutating and non-mutating Swift contexts | Swift by Sundell](https://swiftbysundell.com/articles/mutating-and-nonmutating-swift-contexts?ref=ioscodereview.com) — Article · Topics: Swift
  **NeKI brief:** Examines Mutating and non-mutating Swift contexts | Swift by Sundell in the context of Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 1](https://ioscodereview.com/issues/1)

- Published: `2021-06-30T12:23:30.000Z`

**Topics:** Code Quality · macOS & AppKit · Performance · Swift · SwiftUI · UIKit

**Sections:** Issue #1 - Highlights from 2020 · Change suggestions in PR comments · Tired of translatesAutoresizingMasksIntoConstraints?

**NeKI brief:** Curates this edition’s code-review material on Change suggestions in PR comments, Tired of translatesAutoresizingMasksIntoConstraints?, and Access control for performance. Use it to compare the linked techniques and follow each original source for its complete implementation context.

**Selected links:**
- [change suggestions in PR comments](https://docs.github.com/en/github/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/incorporating-feedback-in-your-pull-request?ref=ioscodereview.com) — Source repository · Topics: Developer Tools
  **NeKI brief:** Provides the source and change history for change suggestions in PR comments, relevant to Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
