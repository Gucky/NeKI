# SwiftUI Weekly

Third-party source index. It provides source attribution and routing metadata, not republished article content. Verify article conclusions independently before applying them.

- Archive: [https://weekly.swiftwithmajid.com/archive](https://weekly.swiftwithmajid.com/archive)
- Last collected: `2026-07-22T21:49:38Z`
- Indexed entries: **212**

## [SwiftUI Weekly - Issue #238](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-238)

- Published: `2026-07-13T20:46:02.053Z`

**Topics:** Macros & Metaprogramming · Observation & State Management · Performance · Swift · SwiftUI · Xcode

**Selected links:**
- [Splitting Large SwiftUI Views in the Apple's way](https://emredegirmenci.substack.com/p/splitting-large-swiftui-views-in) — Article · Topics: Macros & Metaprogramming · Swift · SwiftUI
  **NeKI brief:** Explains Apple's own decomposition techniques for splitting large SwiftUI views, including state and builder boundaries. Useful for reducing oversized bodies while keeping data flow explicit, previewable, and understandable to teammates.
- [Equatable properties in @Observable classes](https://nilcoalescing.com/blog/EquatablePropertiesInObservableClasses) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Explains using equatable properties to limit Observation invalidation in reference types. Useful when expensive SwiftUI views depend on models whose unrelated mutations should not trigger recomputation.
- [The Anatomy of a Reusable SwiftUI View](https://alexanderweiss.dev/blog/2026-07-12-the-anatomy-of-a-reusable-swiftui-view) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Examines how SwiftUI view responsibilities, inputs, and composition boundaries affect reuse. Useful when extracting components that remain readable, previewable, and stable under changing state.
- [The hidden cost of unstable SwiftUI environment defaults](https://nilcoalescing.com/blog/UnstableDefaultEnvironmentValuesInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Diagnoses update churn caused by reference-typed default environment values and explains why stable defaults matter. Useful when environment injection unexpectedly invalidates views or changes identity.

## [SwiftUI Weekly - Issue #237](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-237)

- Published: `2026-06-30T10:02:02.302Z`

**Topics:** Concurrency · Networking · Swift · SwiftUI

**Selected links:**
- [AsyncImage improvements in iOS 27](https://nilcoalescing.com/blog/AsyncImageImprovementsInSwiftUIOnIOS27) — Article · Topics: Concurrency · Swift · SwiftUI
  **NeKI brief:** Covers iOS 27 AsyncImage improvements for loading behavior and presentation. Useful when replacing custom image loaders, while checking cache, cancellation, and failure semantics against the deployment target.
- [SwiftUI Is One Graph, Over 40+ Years of Engineering](https://aleahim.com/blog/swiftui-is-one-graph) — Article · Topics: Concurrency · Swift · SwiftUI
  **NeKI brief:** Uses SwiftUI's graph model to explain how declarative descriptions, dependencies, and updates fit together. Useful for forming a concrete mental model before diagnosing invalidation, identity, or unexpected recomputation in complex view hierarchies.
- [SwiftUI Navigation Transitions Got Better in iOS 27](https://dkvekariya.medium.com/swiftui-navigation-transitions-got-better-in-ios-27-118801f1d8b6) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Reviews the iOS 27 navigation-transition improvements and their effect on destination presentation. Useful for deciding when built-in transitions replace custom choreography, while checking availability and behavior against the target SDK.

## [SwiftUI Weekly - Issue #236](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-236)

- Published: `2026-06-22T10:29:00.171Z`

**Topics:** Apple Platform Ecosystem · Architecture · Liquid Glass · Macros & Metaprogramming · Swift · SwiftUI

**Selected links:**
- [WWDC26: SwiftUI Group Lab 2nd - Q&A](https://antongubarenko.substack.com/p/wwdc26-swiftui-group-lab-2nd-q-and) — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Summarizes questions and answers from the second WWDC26 SwiftUI Group Lab, capturing implementation guidance and framework constraints discussed with Apple engineers. Useful as contextual follow-up when an API’s behavior is unclear from documentation alone.
- [New SwiftUI APIs for reordering and drag and drop on iOS 27](https://nilcoalescing.com/blog/NewSwiftUIAPIsForReorderingAndDragAndDropOniOS27) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explores iOS 27 reorder and drag-container APIs for SwiftUI collections. Useful for implementing movable content with explicit drop configuration instead of manually translating gesture coordinates.
- [SwiftUI's new item based presentations in iOS 27](https://www.sagarunagar.com/blog/swiftui-item-based-alert-confirmation-dialog) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains item-driven SwiftUI alerts and confirmation dialogs, where an optional identifiable value selects the presented content. Useful for eliminating Boolean presentation races and associating destructive actions with the correct model item.
- [SwiftUI: Observable macro under the hood](https://www.nsvasilev.com/posts/swiftui-observable-macro) — Article · Topics: Macros & Metaprogramming · Swift · SwiftUI
  **NeKI brief:** Peels back SwiftUI’s Observable macro expansion, showing the generated observation machinery behind an @Observable model. Useful when diagnosing tracking behavior, deciding which properties need observation, or explaining macro-generated code to a team.

## [SwiftUI Weekly - Issue #235](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-235)

- Published: `2026-06-15T15:55:05.373Z`

**Topics:** Apple Platform Ecosystem · Architecture · Developer Tools · macOS & AppKit · Swift · SwiftUI

**Selected links:**
- [WWDC26: SwiftUI Group Lab - Q&A](https://antongubarenko.substack.com/p/wwdc26-swiftui-group-lab-q-and-a) — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Summarizes SwiftUI Group Lab questions from WWDC26, capturing practical API clarifications and design guidance that are easy to miss in session videos. Useful as a focused follow-up for current SwiftUI adoption decisions.
- [Navigation transition updates in SwiftUI on iOS 27](https://nilcoalescing.com/blog/SwiftUINavigationTransitionUpdatesIniOS27) — Article · Topics: Architecture · Swift · SwiftUI
  **NeKI brief:** Covers iOS 27 navigation transition updates and how destination transitions participate in the navigation stack. Useful when aligning custom transitions with system navigation state.
- [SwiftUI's New .prominent Tab in iOS 27 Is Not a Floating Action Button](https://www.sagarunagar.com/blog/swiftui-prominent-tab-is-not-a-floating-action-button) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Clarifies the prominent tab role in iOS 26 and why it is navigation hierarchy rather than a generic floating action button. Useful for avoiding misleading tab-bar designs.

## [SwiftUI Weekly - Issue #234](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-234)

- Published: `2026-05-25T08:50:12.302Z`

**Topics:** Swift · SwiftUI

**Selected links:**
- [Making a SwiftUI sheet automatically size to fit its content](https://danielsaidi.com/blog/2026/05/22/making-a-swiftui-sheet-automatically-size-to-fit-its-content) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI sheet that measures its content and chooses an appropriate presentation height. Useful for compact forms and detail panels that should avoid excessive empty space while handling dynamic type and updates.
- [Modern SwiftUI APIs for programmatic scrolling](https://nilcoalescing.com/blog/ModernSwiftUIAPIsForProgrammaticScrolling) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Uses modern SwiftUI scrolling APIs to observe visible items, target positions, and programmatic movement. Useful for replacing preference-key workarounds with typed scroll coordination.
- [ContentUnavailableView in SwiftUI](https://www.sagarunagar.com/blog/contentunavailableview-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates ContentUnavailableView for empty, failed, or unavailable SwiftUI states with labels and actions. Useful for standardizing placeholder screens while preserving semantic messaging and a clear recovery path.
- [A floating card using safeAreaBar](https://codakuma.com/floating-safe-area-bar) — Article
  **NeKI brief:** Creates a floating bar with SwiftUI’s safeAreaBar modifier, keeping controls attached to safe-area edges as content scrolls. Useful for persistent actions or playback controls without manual inset calculations and overlay hit-testing.

## [SwiftUI Weekly - Issue #233](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-233)

- Published: `2026-05-11T08:48:00.658Z`

**Topics:** App Services & Extensions · Architecture · Swift · SwiftUI

**Selected links:**
- [Formatting Values in SwiftUI Text and TextField](https://serialcoder.dev/text-tutorials/swiftui/formatting-values-in-swiftui-text-and-textfield) — Tutorial · Topics: Architecture · Swift · SwiftUI
  **NeKI brief:** Explains formatting values in SwiftUI Text and TextField using format styles and bindings. Useful for locale-aware display and editing of numbers or dates while keeping model values typed and validation predictable.
- [SwiftUI: @State under the hood](https://www.nsvasilev.com/posts/swiftui-state) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explores SwiftUI @State storage and its relationship to view identity and lifetime. Useful for diagnosing resets, deciding which state belongs in a view, and explaining why a local mutation survives recomputation.
- [3 Key Strategies to Make SwiftUI Views More Reusable](https://matteomanferdini.com/swiftui-reusable-views) — Article · Topics: App Services & Extensions · Swift · SwiftUI
  **NeKI brief:** Presents three concrete strategies for making SwiftUI views reusable, from extracting components to controlling dependencies and state. Useful when reducing duplication without hiding feature-specific behavior behind overly generic abstractions.
- [Scheduling and handling background app refresh in SwiftUI](https://nilcoalescing.com/blog/SchedulingAndHandlingBackgroundAppRefreshInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows how a SwiftUI app enables, schedules, handles, and tests background refresh work using Background Tasks and backgroundTask(_:action:).

## [SwiftUI Weekly - Issue #232](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-232)

- Published: `2026-04-27T08:30:04.557Z`

**Topics:** Accessibility · Concurrency · Maps & Location · Swift · SwiftUI · UIKit

**Selected links:**
- [SwiftUI: Refreshable Task Cancellation](https://antongubarenko.substack.com/p/swiftui-refreshable-task-cancellation) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Explains how refreshable starts asynchronous work and how cancellation propagates when the user ends or repeats a refresh. Useful for making pull-to-refresh tasks idempotent, responsive, and safe against stale results.
- [Previewing SwiftUI views in both dark and light mode](https://peterringset.dev/articles/light-and-dark-preview) — Article · Topics: Concurrency · Swift · SwiftUI
  **NeKI brief:** Demonstrates previewing SwiftUI views in both light and dark color schemes with representative content. Useful for catching contrast, asset, and layout failures before device testing, especially in reusable components.
- [Checking accessibility with SwiftUI Previews](https://mobilea11y.com/blog/swiftui-preview-testing) — Article · Topics: Maps & Location · Swift · SwiftUI
  **NeKI brief:** Uses SwiftUI previews as an accessibility testing surface, checking labels, traits, and contrast across representative states. Useful for finding VoiceOver regressions early without waiting for a full UI-test suite.
- [Building a draggable bottom sheet in SwiftUI](https://tanaschita.com/swiftui-draggable-bottom-sheet) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a draggable SwiftUI bottom sheet with gesture state, detents, and snapping decisions. Useful for custom interaction when system sheets do not expose the required presentation behavior.

## [SwiftUI Weekly - Issue #231](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-231)

- Published: `2026-04-06T15:12:39.552Z`

**Topics:** Liquid Glass · Swift · SwiftUI

**Selected links:**
- [How to support dark mode in SwiftUI programmatically](https://tanaschita.com/ios-supporting-dark-mode-programmatically) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows programmatic dark-mode control and trait-aware color choices in SwiftUI. Useful when an app offers an appearance setting while still respecting system defaults and semantic colors.
- [Talking Liquid Glass with Apple](https://captainswiftui.substack.com/p/talking-liquid-glass-with-apple) — Article · Topics: Liquid Glass · Swift · SwiftUI
  **NeKI brief:** Reports a direct discussion with Apple about Liquid Glass design and implementation guidance. Useful for understanding the intended visual language and avoiding speculative patterns while adapting SwiftUI interfaces to the new material system.
- [Expanding Animations in SwiftUI Lists](https://nerdyak.tech/development/2026/03/16/expand-animation-in-SwiftUI-List.html) — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **NeKI brief:** Diagnoses janky expand and collapse animations inside SwiftUI List and documents the identity and transaction choices that improve them. Useful when animating variable-height rows without breaking list diffing or scroll performance.
- [SwiftUI View Lifecycle: When onAppear Actually fires](https://www.swiftyplace.com/blog/swiftui-view-lifecycle-onappear) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Investigates surprising onAppear behavior across SwiftUI view hierarchies and lifecycle changes. Useful for placing side effects safely, distinguishing view construction from appearance, and preventing duplicate loads or missed refreshes.

## [SwiftUI Weekly - Issue #230](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-230)

- Published: `2026-03-09T13:33:31.501Z`

**Topics:** Accessibility · Cross-Platform & Web · Developer Tools · Foundation & Data Formats · Swift · SwiftUI

**Sections:** Reading

**Selected links:**
- [Borrowing from Kotlin/Android to Architect Scalable iOS Apps in SwiftUI](https://www.infoq.com/articles/kotlin-scalable-swiftui-patterns) — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **NeKI brief:** Translates scalable architecture ideas from Kotlin and Android into SwiftUI patterns, with emphasis on boundaries and composition. Useful for comparing cross-platform architectural trade-offs before adopting abstractions in a growing iOS codebase.
- [SwiftUI Pro](https://github.com/twostraws/SwiftUI-Agent-Skill) — Source repository · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Provides a reusable SwiftUI-focused agent skill with guidance for generating and reviewing views. Useful as a concrete prompt and workflow artifact when evaluating AI-assisted UI composition, accessibility, and maintainability in a project.
- [Mastering Geometry in SwiftUI - GeometryReader, GeometryProxy & onGeometryChange](https://www.sagarunagar.com/blog/geometry-in-swiftui) — Article · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Surveys GeometryReader, GeometryProxy, and onGeometryChange through practical SwiftUI layout examples. Useful for choosing the least-coupled measurement tool when adaptive components need size or position information without destabilizing layout.
- [Adjusting line height in SwiftUI on iOS 26](https://nilcoalescing.com/blog/AdjustingLineHeightInSwiftUIOniOS26) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows the iOS 26 SwiftUI line-height controls for tuning text leading while preserving Dynamic Type behavior. Useful when typography needs precise rhythm without hard-coded UIKit paragraph styles.

## [SwiftUI Weekly - Issue #229](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-229)

- Published: `2026-02-16T14:07:46.823Z`

**Topics:** AI Development · Navigation & Deep Linking · Swift · SwiftUI · UIKit · Xcode

**Sections:** Reading

**Selected links:**
- [How to use SwiftUI Coordinators to communicate with UIKit](https://tanaschita.com/swiftui-coordinators) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Uses DataScannerViewController to show how UIViewControllerRepresentable.Coordinator receives UIKit delegate callbacks and sends results back to SwiftUI, making the coordinator boundary concrete for delegate-driven integrations.
- [Morphing Sheets Out of Buttons in SwiftUI](https://serialcoder.dev/text-tutorials/swiftui/morphing-sheets-out-of-buttons-in-swiftui) — Tutorial · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Demonstrates morphing a SwiftUI button into sheet content using matched visual state and presentation transitions. Useful for building expressive modal affordances while keeping trigger state, accessibility, and dismissal behavior explicit.
- [Advanced NavigationStack Patterns in SwiftUI](https://buczel.com/blog/swift-navigation-stack-patterns) — Article · Topics: Navigation & Deep Linking · Swift · SwiftUI
  **NeKI brief:** Presents advanced NavigationStack patterns for typed routes, destinations, and path state. Useful for structuring nested flows and deep links when direct NavigationLink composition no longer provides sufficient control or testability.
- [Making SwiftUI Buttons with Equal Widths](https://www.neilmacy.co.uk/blog/swiftui-button-equal-sizing) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows techniques for giving SwiftUI buttons equal widths through layout and frame choices. Useful for action rows and toolbars that need balanced controls without hard-coding device-specific dimensions.

## [SwiftUI Weekly - Issue #228](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-228)

- Published: `2026-02-09T10:51:28.125Z`

**Topics:** Architecture · Code Quality · Navigation & Deep Linking · Observation & State Management · Swift · SwiftUI

**Sections:** Reading

**Selected links:**
- [SwiftUI Agent Skill: Build better views with AI](https://www.avanderlee.com/ai-development/swiftui-agent-skill-build-better-views-with-ai) — Article · Topics: AI Development · Swift · SwiftUI
  **NeKI brief:** Demonstrates a SwiftUI agent skill that reviews state ownership, composition, and view refactoring decisions. The link is valuable when using AI to improve an existing hierarchy rather than generating isolated demo views.
- [Advanced NavigationStack Patterns in SwiftUI](https://buczel.com/blog/welcome) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Introduces NavigationStack patterns and navigation architecture for SwiftUI applications. Useful as a starting point for reviewing route ownership, destination registration, and path-driven deep-link handling in a multi-screen feature.
- [Add an Open Recent Menu to a SwiftUI app](https://swiftdevjournal.com/posts/open-recent-menu) — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **NeKI brief:** Adds an Open Recent menu to a SwiftUI app, wiring recent document state into platform menu commands. Useful for macOS document workflows that need persistence, discoverable actions, and correct scene-level ownership.
- [Migrating to the Observation framework in SwiftUI](https://tanaschita.com/swiftui-observation-migrating-to-observation) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Walks through migrating SwiftUI models from ObservableObject to Observation, including property wrappers and ownership changes. Useful for an incremental migration that keeps view dependencies testable.
- [Swift Bits: Transition vs Transaction](https://antongubarenko.substack.com/p/swift-bits-transition-vs-transaction) — Article · Topics: Swift
  **NeKI brief:** Contrasts SwiftUI transitions, which define insertion and removal effects, with transactions, which carry animation and state-change context. Follow it when an animation behaves unexpectedly because presentation effects and animation configuration were mixed.

## [SwiftUI Weekly - Issue #227](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-227)

- Published: `2026-02-02T11:12:03.900Z`

**Topics:** App Distribution & Store Operations · Liquid Glass · Swift · SwiftUI

**Sections:** Reading

**Selected links:**
- [The Secret to Buttery Smooth SwiftUI](https://www.swiftdifferently.com/blog/swiftui/swiftui-performance-article) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Explores practical causes of sluggish SwiftUI rendering and techniques for reducing unnecessary work. Useful as a performance checklist before profiling view identity, expensive body computations, and state-driven update frequency with Instruments.
- [Introducing FabBar: The Liquid Glass Tab Bar I Wish Apple Made](https://ryanashcraft.com/introducing-fabbar) — Article · Topics: Liquid Glass · Swift · SwiftUI
  **NeKI brief:** Introduces FabBar, a custom Liquid Glass tab-bar implementation with prominent actions and visual effects. Useful for studying custom navigation chrome, while weighing platform conventions, accessibility, and maintenance against system TabView behavior.
- [Designing a Scalable App-Wide Theming System in SwiftUI](https://www.sagarunagar.com/blog/app-wide-theming-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds an app-wide SwiftUI theming system around reusable colors, typography, and style tokens. Useful for centralizing design decisions and testing appearance variants without scattering literal values across feature views.
- [Emptiness in SwiftUI](https://captainswiftui.substack.com/p/emptiness-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Reflects on empty states in SwiftUI and the design meaning of showing no content. Useful for turning absence into deliberate loading, unavailable, or recovery UI rather than leaving screens visually ambiguous.
- [Migrating an iOS app from Paid up Front to Freemium](https://www.donnywals.com/migrating-an-ios-app-from-paid-up-front-to-freemium) — Article · Topics: App Distribution & Store Operations
  **NeKI brief:** Documents the product and StoreKit decisions involved in moving an app from paid-up-front to freemium. Useful as business migration context, not as a universal monetization prescription.

## [SwiftUI Weekly - Issue #226](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-226)

- Published: `2025-12-22T12:33:43.144Z`

**Topics:** Graphics, Media & Games · Navigation & Deep Linking · Observation & State Management · Performance · Swift · SwiftUI

**Sections:** Reading

**Selected links:**
- [Reducing the Number of .sheet Modifiers in Your SwiftUI Views](https://swiftdevjournal.com/posts/reducing-sheet-modifiers) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Refactors repeated sheet modifiers into centralized, typed presentation state. Useful for reducing modal branching in SwiftUI views while making destinations, dismissal, and presentation tests easier to reason about.
- [Why Child @State Won't Update from Parent in SwiftUI](https://fatbobman.com/en/snippet/why-child-state-won-not-update-from-parent-in-swiftui) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Explains why a child view's @State does not automatically follow later parent changes after initialization. Useful for distinguishing owned local state from bindings and selecting the correct data-flow fix instead of forcing refreshes.
- [Animating SF Symbols in SwiftUI](https://nilcoalescing.com/blog/AnimatingSFSymbolsInSwiftUI) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Uses SwiftUI symbol effects and configuration to animate SF Symbols in response to state changes. Useful for lightweight feedback that remains tied to semantic icon transitions rather than custom image sequences.
- [From broken to testable SwiftUI navigation: The decoupled approach of MVVM with coordinators](https://matteomanferdini.com/mvvm-coordinator-swiftui) — Article · Topics: Navigation & Deep Linking · Swift · SwiftUI
  **NeKI brief:** Builds a decoupled SwiftUI navigation approach combining MVVM and coordinators, with route orchestration outside view bodies. Useful for testing navigation decisions and containing flow complexity as features expand.

## [SwiftUI Weekly - Issue #225](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-225)

- Published: `2025-12-02T09:51:26.955Z`

**Topics:** Objective-C & Cocoa · Observation & State Management · Swift · SwiftUI · UIKit

**Sections:** Reading

**Selected links:**
- [Task Identity](https://chris.eidhof.nl/post/swiftui-task-identity) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Connects SwiftUI view identity and dependency tracking to the lifetime and restart behavior of tasks. Use it when asynchronous work appears to run with stale inputs or at unexpected times.
- [Initializing @Observable classes within the SwiftUI hierarchy](https://nilcoalescing.com/blog/InitializingObservableClassesWithinTheSwiftUIHierarchy) — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **NeKI brief:** Compares ownership patterns for creating @Observable reference types inside SwiftUI, including state storage and dependency injection. Useful for preventing model recreation when view identity changes.
- [Understanding the Transferable Protocol in Swift](https://www.createwithswift.com/understanding-the-transferable-protocol-in-swift) — Article · Topics: Swift
  **NeKI brief:** Explains Transferable representations and type-specific export or import formats for system sharing. Useful when designing drag, drop, paste, or share flows that support more than one data representation.
- [Document Preview Options in SwiftUI](https://livsycode.com/swiftui/document-preview-options-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explores document-preview presentation options in SwiftUI, including configuration of the preview surface and source document. Useful for implementing file workflows with appropriate presentation, dismissal, and platform-specific behavior.

## [SwiftUI Weekly - Issue #224](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-224)

- Published: `2025-11-03T11:19:35.224Z`

**Topics:** AI Development · Architecture · Graphics, Media & Games · Objective-C & Cocoa · Swift · SwiftUI

**Sections:** Reading · Video

**Selected links:**
- [Optimize your app's speed and efficiency](https://www.youtube.com/watch?v=yXAQTIKR8fk) — Video · Topics: AI Development · Foundation & Data Formats · Graphics, Media & Games
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [SwiftUI Architecture: Structure Views for Reusability and Clarity](https://www.avanderlee.com/swiftui/swiftui-architecture-structure-views-for-reusability-and-clarity) — Article · Topics: Architecture · Swift · SwiftUI
  **NeKI brief:** Refactors oversized SwiftUI view bodies by extracting responsibilities, choosing stable data flow, and isolating reusable components. The examples make the trade-off between abstraction and readable composition concrete for growing screens.
- [Zooming With The Magnify Gesture in SwiftUI](https://serialcoder.dev/text-tutorials/swiftui/zooming-with-the-magnify-gesture-in-swiftui) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Implements pinch-to-zoom in SwiftUI with MagnifyGesture and accumulated scale state. Useful for image or canvas interactions that need bounded zoom, gesture continuity, and predictable reset behavior.
- [ScrollView snapping in SwiftUI](https://nilcoalescing.com/blog/ScrollViewSnappingInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Configures SwiftUI scroll target behavior and snapping so items settle at deliberate positions. Useful for carousels and paged content without implementing custom drag-end calculations.

## [SwiftUI Weekly - Issue #223](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-223)

- Published: `2025-10-20T15:15:23.773Z`

**Topics:** App Distribution & Store Operations · Concurrency · Foundation & Data Formats · Swift · SwiftUI · Testing

**Sections:** Reading

**Selected links:**
- [Why a custom ViewModifier is often useless](https://www.swiftwithvincent.com/blog/why-a-custom-viewmodifier-is-often-useless) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Argues that many custom ViewModifiers add indirection without clarifying behavior, and shows when direct composition is better. Useful for reviewing SwiftUI abstractions against readability, reuse, and discoverable call-site intent.
- [Tunable, physics-driven motion primitives for SwiftUI](https://github.com/roberthein/kinetics) — Source repository · Topics: Concurrency · Swift · SwiftUI
  **NeKI brief:** Provides tunable, physics-driven motion primitives for SwiftUI, including configurable springs and dynamics. Useful for experimenting with reusable interactive animations while inspecting API ergonomics, cancellation, and performance in real screens.
- [When SwiftUI automatically applies the glass look and when it doesn’t](https://tanaschita.com/swiftui-glass-auto-apply) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains when SwiftUI automatically applies Liquid Glass and when explicit modifiers are required. Useful for diagnosing inconsistent material appearance across containers and platform contexts.
- [Add a Close button to SwiftUI modals on iOS 26](https://nilcoalescing.com/blog/AddACloseButtonToSwiftUIModalsOnIOS26) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates the iOS 26 modal close-button API and its placement rules. Useful for adopting system-consistent dismissal affordances without building a custom toolbar button for every sheet.

## [SwiftUI Weekly - Issue #222](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-222)

- Published: `2025-09-01T13:02:53.458Z`

**Topics:** Apple Platform Ecosystem · Combine & Reactive Programming · Observation & State Management · Swift · SwiftUI

**Selected links:**
- [How to create a custom reusable toolbar in SwiftUI](https://tanaschita.com/swiftui-reusable-toolbar) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Builds a reusable SwiftUI toolbar component while keeping actions and state explicit. Useful for design systems that need consistent toolbar composition across screens and platforms.
- [Building a design system at Genius Scan](https://www.swiftbysundell.com/articles/building-a-design-system-at-genius-scan) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Describes building a shared design system with reusable components, tokens, and constraints at Genius Scan. Useful for connecting SwiftUI component reuse to product consistency and team-scale maintenance.
- [Corner concentricity in SwiftUI on iOS 26](https://nilcoalescing.com/blog/ConcentricRectangleInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Introduces ConcentricRectangle for corners that follow the system's concentric geometry. Useful for iOS 26 surfaces that need nested cards and containers to align with platform visual language.
- [Perception 2.0: An updated back-port of Swift’s Observation framework](https://www.pointfree.co/blog/posts/180-perception-2-0-an-updated-back-port-of-swift-s-observation-framework) — Article · Topics: Apple Platform Ecosystem · Observation & State Management · Swift
  **NeKI brief:** Explains Perception 2.0 as a back-port of Swift Observation for older deployment targets. Useful when sharing modern observation patterns while an application cannot yet require iOS 17.

## [SwiftUI Weekly - Issue #221](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-221)

- Published: `2025-07-28T14:19:08.051Z`

**Topics:** Objective-C & Cocoa · Swift · SwiftUI

**Sections:** Reading

**Selected links:**
- [SwiftUI Search Enhancements in iOS and iPadOS 26](https://nilcoalescing.com/blog/SwiftUISearchEnhancementsIniOSAndiPadOS26) — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **NeKI brief:** Shows iOS and iPadOS 26 SwiftUI search enhancements for placement, suggestions, and presentation. Useful for modernizing search flows without rebuilding the search field and toolbar integration.
- [SwiftUI: Scrollview tracking offset/items](https://antongubarenko.substack.com/p/swiftui-scrollview-tracking-offsetitems) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates tracking ScrollView offsets and visible items with modern SwiftUI APIs. Useful for scroll-aware headers, pagination, and deferred effects without relying on fragile preference-key geometry plumbing.
- [Providing Multiple Accent Colors in SwiftUI Apps](https://serialcoder.dev/text-tutorials/swiftui/providing-multiple-accent-colors-in-swiftui-apps) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Shows how to provide multiple accent colors in a SwiftUI app and select them through state or settings. Useful for appearance customization while preserving semantic styling and consistent behavior across scenes.
- [Creating amazing loading animations with SF Symbols.](https://danielsaidi.com/blog/2025/06/19/creating-amazing-loading-animations-with-sf-symbols) — Article
  **NeKI brief:** Creates loading animations from SF Symbols using symbol effects and state-driven timing. Useful for lightweight progress feedback that remains scalable and semantic instead of relying on bespoke raster animation assets.

## [SwiftUI Weekly - Issue #220](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-220)

- Published: `2025-07-21T14:51:16.987Z`

**Topics:** Accessibility · Liquid Glass · Swift · SwiftUI

**Sections:** Reading

**Selected links:**
- [Supporting Reduced Motion accessibility setting in SwiftUI](https://tanaschita.com/ios-accessibility-reduced-motion) — Article · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Shows responding to the system Reduced Motion preference in iOS, with SwiftUI-oriented implementation guidance. Follow it when animations communicate state but must be simplified or removed for motion-sensitive users.
- [Handling WebView navigation in SwiftUI](https://www.artemnovichkov.com/blog/handling-webview-navigation-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Handles WKWebView navigation callbacks inside a SwiftUI wrapper, including coordinator delegation and policy decisions. Useful for exposing web navigation state without leaking UIKit controller details into feature views.
- [Presenting Liquid Glass sheets in SwiftUI on iOS 26](https://nilcoalescing.com/blog/PresentingLiquidGlassSheetsInSwiftUI) — Article · Topics: Liquid Glass · Swift · SwiftUI
  **NeKI brief:** Demonstrates presenting sheets that participate in iOS 26 Liquid Glass styling and detents. Useful for adopting system material behavior while keeping modal content and dismissal state explicit.
- [Structuring Spacing for Scalable Mobile UIs](https://www.mobilesystemdesign.com/blog/design-system-spacing) — Article
  **NeKI brief:** Discusses spacing tokens and rhythm as foundations of a mobile design system. Useful for translating visual rules into reusable SwiftUI layout constants instead of accumulating screen-specific padding values.

## [SwiftUI Weekly - Issue #219](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-219)

- Published: `2025-07-07T19:56:01.128Z`

**Topics:** Apple Platform Ecosystem · Liquid Glass · Swift · SwiftUI

**Sections:** Reading

**Selected links:**
- [Using WebKit to load web content in SwiftUI](https://www.artemnovichkov.com/blog/using-webkit-to-load-web-content-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Integrates WebKit content loading with SwiftUI through UIViewRepresentable and a coordinator. Useful for controlled web content, navigation state, and lifecycle handling in hybrid screens.
- [Designing custom UI with Liquid Glass on iOS 26](https://www.donnywals.com/designing-custom-ui-with-liquid-glass-on-ios-26) — Article · Topics: Liquid Glass
  **NeKI brief:** Explores custom Liquid Glass composition on iOS 26, including grouping and material boundaries. Useful for matching the system visual language without treating every translucent surface as interchangeable.
- [Attribute graph](https://chris.eidhof.nl/presentations/attribute-graph) — Article
  **NeKI brief:** Explains SwiftUI's AttributeGraph as the dependency engine behind updates and evaluation. Useful for building a sharper mental model of invalidation and diagnosing why seemingly unrelated state changes propagate.

## [SwiftUI Weekly - Issue #218](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-218)

- Published: `2025-06-23T10:41:25.657Z`

**Topics:** Apple Platform Ecosystem · Developer Community & Business · Liquid Glass · Swift · SwiftUI · Xcode

**Sections:** Reading · Books

**Selected links:**
- [Dave DeLong’s “Backport”](https://davedelong.com/blog/2021/10/09/simplifying-backwards-compatibility-in-swift) — Article · Topics: Liquid Glass · Swift · Xcode
  **NeKI brief:** Shows a compatibility wrapper pattern that centralizes availability checks and exposes one stable API to callers. Useful when supporting older OS releases without scattering #available branches through SwiftUI views.
- [Exploring tab bars on iOS 26 with Liquid Glass](https://www.donnywals.com/exploring-tab-bars-on-ios-26-with-liquid-glass) — Article · Topics: Liquid Glass · Xcode
  **NeKI brief:** Examines iOS 26 tab bars under Liquid Glass and the behavior of prominent tab presentation. Useful for designing navigation that respects new system hierarchy and interaction expectations.
- [Escape from Tutorial Hell](https://sarahreichelt.gumroad.com/l/iqdry/nuy8ey0) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Offers a SwiftUI learning resource focused on practical interface construction and concepts. Useful as structured study material when a team needs shared foundations before tackling advanced layout or state-management topics.
- [Overlapping Views in SwiftUI with zIndex](https://serialcoder.dev/text-tutorials/swiftui/overlapping-views-in-swiftui-with-zindex) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates overlapping SwiftUI views with zIndex and stack composition. Useful for cards, badges, and layered controls where rendering order and hit testing must stay predictable.
- [Stretchy header in SwiftUI with visualEffect()](https://nilcoalescing.com/blog/StretchyHeaderInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a stretchy scrolling header with GeometryReader and visual effects tied to scroll offset. Useful for immersive detail screens while keeping the effect isolated from content layout.

## [SwiftUI Weekly - Issue #217](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-217)

- Published: `2025-06-02T12:56:10.176Z`

**Topics:** Accessibility · Architecture · Code Quality · Composable Architecture · Swift · SwiftUI

**Sections:** Reading

**Selected links:**
- [Tips and tricks for when using SwiftUI’s ViewBuilder](https://www.swiftbysundell.com/articles/swiftui-viewbuilder-tips-and-tricks) — Article · Topics: Code Quality · Swift · SwiftUI
  **NeKI brief:** Collects ViewBuilder techniques for conditional composition, custom containers, and readable APIs. Useful when designing result-builder-based components without hiding state or type constraints.
- [SwiftUI in 2025: Forget MVVM](https://dimillian.medium.com/swiftui-in-2025-forget-mvvm-262ff2bbd2ed) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Challenges defaulting to MVVM in modern SwiftUI and discusses state-driven alternatives. Useful for comparing architectural ceremony against feature complexity before introducing view models solely by convention.
- [Understanding toolbars in SwiftUI](https://tanaschita.com/swiftui-toolbars-guide) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Surveys SwiftUI toolbar placement, roles, and item composition across platforms. Useful for avoiding platform-specific placement surprises and keeping actions discoverable in navigation bars.
- [The evolution of native engineering at Tripadvisor: Part 1](https://medium.com/tripadvisor/the-evolution-of-native-engineering-at-tripadvisor-part-1-577cc0e36ec8) — Article · Topics: Architecture · Composable Architecture · Concurrency
  **NeKI brief:** Traces Tripadvisor's evolution of native mobile engineering and organizational architecture. Useful as large-team context for evaluating ownership, platform investment, and migration strategy alongside SwiftUI-specific decisions.
- [Enable scrolling based on content size in SwiftUI](https://nilcoalescing.com/blog/EnableScrollingBasedOnContentSizeInSwiftUI) — Article · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Uses measured content and container dimensions to enable scrolling only when content exceeds available space. Useful for avoiding awkward always-scrollable screens in adaptive SwiftUI layouts.

## [SwiftUI Weekly - Issue #216](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-216)

- Published: `2025-05-26T11:50:16.922Z`

**Topics:** Graphics, Media & Games · Objective-C & Cocoa · Swift · SwiftUI · Testing

**Sections:** Reading · Videos

**Selected links:**
- [Demystifying SwiftUI’s .ignoredByLayout() — How to Apply Geometry Effects Without Breaking Your Layout](https://fatbobman.com/en/posts/demystifying-swiftuis-ignoredbylayout) — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **NeKI brief:** Explains how ignoredByLayout removes a view from layout participation while retaining rendering or interaction implications. Useful for distinguishing hidden geometry from conditional rendering when composing overlays and transitions.
- [XCUITest: How to Write UI Tests for SwiftUI Apps](https://www.swiftyplace.com/blog/xcuitest-ui-testing-swiftui) — Article · Topics: Swift · SwiftUI · Testing
  **NeKI brief:** Walks through XCUITest coverage for SwiftUI views using accessibility identifiers and user-level interactions. Useful for writing resilient UI tests that verify behavior rather than private view structure.
- [Ever heard of .contextMenu()?](https://www.swiftwithvincent.com/blog/ever-heard-of-contextmenu) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Introduces SwiftUI context menus and their action composition. Useful for adding secondary actions while checking discoverability, platform conventions, and accessibility alternatives for actions hidden behind a long press.
- [Mesh gradients in SwiftUI](https://nilcoalescing.com/blog/MeshGradientsInSwiftUI) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Builds mesh gradients in SwiftUI by defining a grid of interpolated colors and positions. Useful for expressive backgrounds while understanding rendering cost and the need for platform availability checks.

## [SwiftUI Weekly - Issue #215](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-214-8dc)

- Published: `2025-05-12T16:53:14.591Z`

**Topics:** Cross-Platform & Web · Graphics, Media & Games · Security & Privacy · Swift · SwiftUI · Testing

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #215 · Reading

**Selected links:**
- [Choosing between LazyVStack, List, and VStack in SwiftUI](https://www.donnywals.com/choosing-between-lazyvstack-list-and-vstack-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Compares VStack, LazyVStack, and List across rendering, behavior, and platform features. Useful for choosing a container based on data size, recycling needs, and built-in interaction rather than habit.
- [Formatting data inside SwiftUI Text views](https://nilcoalescing.com/blog/FormattingDataInsideSwiftUITextViews) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Formats inline values inside SwiftUI Text using interpolation and format styles. Useful for localized dates, measurements, and numbers where presentation should follow locale rather than manual string assembly.
- [Can You use PreferenceKeys for Testing SwiftUI Views](https://www.swiftyplace.com/blog/swiftui-testing-with-preferencekeys) — Article · Topics: Swift · SwiftUI · Testing
  **NeKI brief:** Investigates whether PreferenceKeys can expose SwiftUI layout information to tests. Useful for understanding testability limits and deciding when a semantic UI assertion is preferable to measuring implementation details.
- [SwiftUI View Model Ownership](https://chris.eidhof.nl/post/swiftui-view-model) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Investigates ownership and initialization of a view model created by a SwiftUI view, including the traps around init and state storage. Use it when deciding how a view should create and retain reference-model state.
- [our workshops](https://www.swiftuifieldguide.com/workshops) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Lists practical SwiftUI workshops covering layout, animation, and architecture through guided exercises. Useful for selecting focused team training that maps to concrete framework gaps rather than generic video consumption.
- [What's new in Swift 6.2?](https://www.hackingwithswift.com/articles/277/whats-new-in-swift-6-2) — Article · Topics: Swift
  **NeKI brief:** Summarizes Swift 6.2 additions and concurrency ergonomics, highlighting practical changes for existing projects. Useful for planning an incremental toolchain update and targeted experiments.

## [SwiftUI Weekly - Issue #214](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-214)

- Published: `2025-04-28T13:32:59.660Z`

**Topics:** Cross-Platform & Web · Graphics, Media & Games · macOS & AppKit · Swift · SwiftUI · UIKit

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #214 · Reading

**Selected links:**
- [How to persist navigation state in SwiftUI](https://tanaschita.com/swiftui-navigation-persist-state) — Article · Topics: Navigation & Deep Linking · Swift · SwiftUI
  **NeKI brief:** Shows how navigation containers preserve or recreate view state and how to place state storage accordingly. Useful when returning to a destination unexpectedly resets user input.
- [SwiftUI ForEach Explained with Code Examples](https://www.avanderlee.com/swiftui/swiftui-foreach-loop-index) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates index-aware ForEach patterns and explains identity requirements when iterating collections. The examples help avoid unstable IDs and out-of-range indexing while rendering editable SwiftUI lists.
- [Loving SwiftUI, missing UIKit.](https://collin.blog/2025/04/24/loving-swiftui-missing-uikit) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Reflects on SwiftUI strengths and UIKit capabilities that developers may still miss. Useful as balanced migration context when deciding where a hybrid implementation remains the lower-risk product choice.
- [Why Your SwiftUI App Is Slower Than You Think](https://medium.com/@wesleymatlock/why-your-swiftui-app-is-slower-than-you-think-c3e9bb46174b) — Article · Topics: Personal Essays · Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI rendering and scrolling costs behind Why Your SwiftUI App Is Slower Than You Think. Use it to identify identity, layout, and update-frequency risks before measuring regressions with Instruments on representative devices.
- [Free mobile payments SDK by Square](https://fnf.dev/4lkI0hT) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Promotes Square's mobile payments SDK for integrating payment acceptance into an iOS app. Useful as a discovery link when evaluating payment capabilities, while separately checking SDK availability, compliance, pricing, and production support.

## [SwiftUI Weekly - Issue #213](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-213)

- Published: `2025-04-21T14:45:08.780Z`

**Topics:** Concurrency · Cross-Platform & Web · Performance · Swift · SwiftUI · Testing

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #213 · Reading

**Selected links:**
- [Using Instruments to profile a SwiftUI app](https://www.donnywals.com/using-instruments-to-profile-a-swiftui-app) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Profiles a SwiftUI app with Instruments to connect view updates and runtime cost to measured workloads. Useful for replacing assumptions about rendering performance with trace evidence.
- [Is There A Better AsyncButton?](https://captainswiftui.substack.com/p/is-there-a-better-asyncbutton?triedRedirect=true) — Article · Topics: Concurrency · Swift · SwiftUI
  **NeKI brief:** Compares AsyncButton designs for loading, cancellation, and repeated taps in SwiftUI. Useful when standardizing asynchronous action controls and deciding which state transitions belong in the button versus its caller.
- [Free mobile payments SDK by Square](https://fnf.dev/4lkI0hT) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Promotes Square's mobile payments SDK for integrating payment acceptance into an iOS app. Useful as a discovery link when evaluating payment capabilities, while separately checking SDK availability, compliance, pricing, and production support.

## [SwiftUI Weekly - Issue #212](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-212)

- Published: `2025-04-14T08:07:47.601Z`

**Topics:** Accessibility · Apple Platform Ecosystem · Combine & Reactive Programming · Cross-Platform & Web · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #212 · Reading

**Selected links:**
- [A Guide to the SwiftUI @Environment](https://www.devfright.com/a-guide-to-the-swiftui-environment) — Article · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Provides a practical tour of SwiftUI environment lookup and propagation. Useful for deciding which dependencies should be injected implicitly, how overrides work in previews, and where explicit parameters improve clarity.
- [Showing What's New Screens using @AppStorage](https://www.swiftjectivec.com/Simply-Whats-New-Logic-in-SwiftUI-iOS-apps) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Implements a simple What's New flow with AppStorage and version-aware presentation logic. Useful for persisting per-version onboarding state without coupling release notes to every feature screen.
- [Plurals with SwiftUI](https://samwize.com/2025/04/11/plurals-with-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows pluralization in SwiftUI using localized string resources and interpolation. Useful for count-based copy that remains grammatically correct across locales instead of embedding English singular/plural branches.
- [Text concatenation vs Text interpolation in SwiftUI](https://nilcoalescing.com/blog/TextConcatenationVsTextInterpolationInSwiftUI) — Article · Topics: Combine & Reactive Programming · Swift · SwiftUI
  **NeKI brief:** Contrasts concatenating Text views with interpolating values into localized strings. Useful for preserving localization and formatting semantics when constructing styled SwiftUI copy.
- [Free mobile payments SDK by Square](https://fnf.dev/4lkI0hT) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Promotes Square's mobile payments SDK for integrating payment acceptance into an iOS app. Useful as a discovery link when evaluating payment capabilities, while separately checking SDK availability, compliance, pricing, and production support.

## [SwiftUI Weekly - Issue #211](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-211)

- Published: `2025-03-25T13:30:35.672Z`

**Topics:** Composable Architecture · Concurrency · Objective-C & Cocoa · Performance · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #211 · Reading

**Selected links:**
- [SwiftUI TabView: Explained with Code Examples](https://www.avanderlee.com/swiftui/tabview-tabbed-views) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains TabView selection, tab items, styles, and state restoration for multi-section SwiftUI apps. The examples are useful for keeping navigation state explicit while adapting presentation across platforms.
- [Clean Up Your Sheet API](https://medium.com/@jpmtech/clean-up-your-sheet-api-7763b796cd94) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Proposes a cleaner API for presenting SwiftUI sheets through typed state and centralized routing. Useful for reducing boolean presentation flags and making modal destinations easier to test and extend.
- [The Simple Life(cycle) of a SwiftUI View in 2025](https://captainswiftui.substack.com/p/the-simple-lifecycle-of-a-swiftui) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Describes the lifecycle of a SwiftUI view from identity through evaluation and disappearance. Useful for placing initialization, side effects, and cleanup where their timing matches actual view lifetime.
- [The Composable Architecture: How Architectural Design Decisions Influence Performance](https://www.swiftyplace.com/blog/the-composable-architecture-performance) — Article · Topics: Architecture · Objective-C & Cocoa · Performance
  **NeKI brief:** Examines performance implications of The Composable Architecture in SwiftUI, including reducer and view update costs. Useful for measuring architectural overhead in realistic workloads rather than assuming framework use is free or prohibitive.
- [SwiftUI Default Scroll Anchor](https://useyourloaf.com/blog/swiftui-default-scroll-anchor) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Configures a default scroll anchor so newly inserted or resized content settles at a chosen edge. Useful for chat and feed layouts where preserving the visible context matters.

## [SwiftUI Weekly - Issue #210](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-210)

- Published: `2025-03-17T10:10:06.430Z`

**Topics:** Apple Platform Ecosystem · Concurrency · Cross-Platform & Web · Swift · SwiftUI · UIKit

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #210 · Reading

**Selected links:**
- [Refactoring my SwiftUI Navigation Layer to follow the Coordinator Pattern](https://www.tiagohenriques.dev/blog/swiftui-refactor-navigation-layer-using-coordinator-pattern) — Article · Topics: Concurrency · Swift · SwiftUI
  **NeKI brief:** Refactors a SwiftUI navigation layer toward the Coordinator pattern, separating route orchestration from views. Useful for deep-link handling and feature composition when NavigationStack state is spreading across screens.
- [Exploring The LabeledContent View In SwiftUI](https://serialcoder.dev/text-tutorials/swiftui/exploring-the-labeledcontent-view-in-swiftui) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Explores LabeledContent for pairing values with descriptive labels in SwiftUI. Useful for settings, metadata, and inspector rows that need consistent semantics and platform styling without hand-built HStacks.
- [Picker in SwiftUI explained with code examples](https://www.avanderlee.com/swiftui/picker-styles-color) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates Picker bindings and style choices such as menu, segmented, wheel, and navigation-link presentations. It connects control style to platform context and option count instead of only changing appearance.
- [Placing UI components within the Safe Area Inset](https://www.createwithswift.com/placing-ui-components-within-the-safe-area-inset) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Uses safeAreaInset to place persistent controls while reserving layout space for content. Useful for bottom actions that should avoid overlap with scrolling content and system regions.

## [SwiftUI Weekly - Issue #209](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-209)

- Published: `2025-03-03T16:45:42.215Z`

**Topics:** Concurrency · Cross-Platform & Web · macOS & AppKit · Performance · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #209

**Selected links:**
- [Symmetrical and asymmetrical transitions in SwiftUI with the Scroll Transition modifier](https://www.createwithswift.com/symmetrical-and-asymmetrical-transitions-in-swiftui-with-the-scroll-transition-modifier) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Applies scrollTransition with symmetric or asymmetric phases to animate content entering and leaving a scroll view. Useful for controlled motion tied to visibility rather than arbitrary timers.
- [Designing a custom lazy list in SwiftUI with better performance](https://nilcoalescing.com/blog/CustomLazyListInSwiftUI) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Constructs a custom lazy list to control virtualization and layout beyond List's built-in behavior. Useful when custom scrolling visuals or cell composition require more control than standard list styles provide.
- [SwiftUI Phase Animation "Bug"](https://chris.eidhof.nl/post/swiftui-phase-animation-bug) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Debugs unexpected phase-animation behavior that initially looks like a framework bug but has another cause. Use it as a focused diagnostic example before concluding that PhaseAnimator itself is broken.
- [Tapping on Stack Views](https://useyourloaf.com/blog/tapping-on-stack-views) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains why tapping empty space in a SwiftUI stack may not trigger a gesture and how contentShape changes hit testing. Useful for reliable row and card interactions.

## [SwiftUI Weekly - Issue #208](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-208)

- Published: `2025-02-18T13:13:57.808Z`

**Topics:** Concurrency · Foundation & Data Formats · macOS & AppKit · Swift · SwiftUI · UIKit

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #208 · Reading

**Selected links:**
- [The easiest way to use SwiftUI in a UIKit app](https://www.swiftwithvincent.com/blog/the-easiest-way-to-use-swiftui-in-a-uikit-app) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Shows a minimal path for embedding SwiftUI inside an existing UIKit application. Useful for incremental adoption, choosing hosting boundaries, and sharing navigation or dependency state across frameworks.
- [Build a macOS menu bar utility in SwiftUI](https://nilcoalescing.com/blog/BuildAMacOSMenuBarUtilityInSwiftUI) — Article · Topics: macOS & AppKit · Swift · SwiftUI
  **NeKI brief:** Walks through a SwiftUI macOS menu-bar utility, including scene configuration and status-item presentation. Useful for small persistent tools that should avoid a conventional document window.
- [How to use SceneDelegate in SwiftUI](https://tanaschita.com/swiftui-scenedelegate) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Bridges scene lifecycle behavior into SwiftUI through a scene delegate integration. Useful when an application still needs UIKit lifecycle hooks for notifications, deep links, or window coordination.
- [Presenting and Managing Expandable Sections in SwiftUI](https://serialcoder.dev/text-tutorials/swiftui/presenting-and-managing-expandable-sections-in-swiftui) — Tutorial · Topics: Product Design · Swift · SwiftUI
  **NeKI brief:** Builds expandable SwiftUI sections with disclosure state and animated content. Useful for settings and FAQ interfaces where row identity, accessibility labels, and collapsed content behavior must remain consistent.

## [SwiftUI Weekly - Issue #207](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-207)

- Published: `2025-02-03T16:14:36.700Z`

**Topics:** Cross-Platform & Web · Maps & Location · Objective-C & Cocoa · Security & Privacy · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #207 · Reading

**Selected links:**
- [Drawing maps with Swift Charts](https://www.artemnovichkov.com/blog/drawing-maps-with-swift-charts) — Article · Topics: Maps & Location · Swift
  **NeKI brief:** Uses Swift Charts to draw map-like visualizations from coordinate data. Useful for plotting paths or geographic series when a chart is sufficient and a full map renderer would add unnecessary complexity.
- [Understanding SwiftUI Preferences](https://peterfriese.dev/blog/2025/swiftui-preferences-swift6) — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **NeKI brief:** Explains SwiftUI Preferences as an upward data channel from child views to ancestors, with Swift 6 examples. It is useful for designing reusable components that report measurements or actions without tight parent-child coupling.
- [Show a popover on iPhone in SwiftUI](https://nilcoalescing.com/blog/PopoverOniPhoneInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows iPhone popover presentation and adaptation behavior in SwiftUI. Useful for lightweight contextual actions that should not become a full navigation destination or sheet.
- [SwiftUI Button Image When Pressed](https://useyourloaf.com/blog/swiftui-button-image-when-pressed) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Uses SwiftUI state and button styles to swap or animate an image while a button is pressed. Useful for immediate tactile feedback without manually tracking touch events.
- [Advantages of Using withAnimation](https://www.magnuskahr.dk/posts/2025/01/advantage-of-withAnimation) — Article
  **NeKI brief:** Compares value-driven animation modifiers with explicit withAnimation blocks and explains where the latter gives clearer control. Follow it when an interaction changes several pieces of state and the animation scope should be obvious at the mutation site.

## [SwiftUI Weekly - Issue #206](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-206)

- Published: `2025-01-13T09:29:54.892Z`

**Topics:** Accessibility · Code Quality · macOS & AppKit · Swift · SwiftUI · Testing

**Selected links:**
- [Accessibility That Fits](https://khanlou.com/2024/12/accessibility-that-fits) — Article · Topics: Accessibility · Product Design · Swift
  **NeKI brief:** Discusses fitting accessibility behavior into existing interfaces without treating it as a late checklist. Useful for reviewing SwiftUI labels, traits, Dynamic Type, and interaction alternatives as part of component design.
- [SwiftUI Navigation using the Router Pattern](https://tiagohenriques.vercel.app/blog/swiftui-navigation-router-pattern) — Article · Topics: Foundation & Data Formats · Swift · SwiftUI
  **NeKI brief:** Implements a router pattern for SwiftUI navigation with centralized route decisions. Useful for making deep links, modal presentation, and navigation tests deterministic while keeping views focused on rendering.
- [Customizing macOS window background in SwiftUI](https://nilcoalescing.com/blog/CustomizingMacOSWindowBackgroundInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows how to customize a macOS SwiftUI window background while respecting the hosting window boundary. Useful for translucent or branded surfaces that cannot be achieved with view modifiers alone.
- [Handle plurals in SwiftUI Text views with inflection](https://nilcoalescing.com/blog/HandlePluralsInSwiftUITextViewsWithInflection) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Uses SwiftUI text inflection to select plural forms from localized strings. Useful for grammatical counts that must adapt to locale without embedding English-only singular/plural conditionals.
- [Getting started with UI Testing for SwiftUI](https://tanaschita.com/testing-ui-swiftui-xctest-framework) — Article · Topics: Swift · SwiftUI · Testing
  **NeKI brief:** Demonstrates UI testing SwiftUI applications with XCTest, including accessibility-driven queries and interaction assertions. Useful for testing user-visible behavior without coupling tests to implementation details.

## [SwiftUI Weekly - Issue #205](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-205)

- Published: `2024-12-16T17:10:10.299Z`

**Topics:** Apple Platform Ecosystem · Cross-Platform & Web · Security & Privacy · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #205 · Reading

**Selected links:**
- [SF Symbol: How to for Swift & SwiftUI](https://www.avanderlee.com/swift/sf-symbol-guide) — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Explains selecting SF Symbols, applying weight, scale, rendering modes, and accessibility labels in Swift and SwiftUI. The guidance helps use Apple’s iconography without treating symbols as unannotated decorative images.
- [Mastering Forms in SwiftUI: Creating and Styling](https://www.createwithswift.com/mastering-forms-in-swiftui-creating-and-styling) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Composes and styles SwiftUI Forms with sections, controls, and platform-aware presentation. Useful for settings and data-entry screens that should retain system accessibility and focus behavior.
- [Exploring TabView Advancements in SwiftUI](https://serialcoder.dev/text-tutorials/swiftui/exploring-tabview-advancements-in-swiftui-part-1) — Tutorial · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Explores newer TabView configuration and presentation APIs in SwiftUI. Useful when building adaptive tab navigation that needs explicit selection, customization, or platform-aware behavior.
- [Apple’s use of Swift and SwiftUI in iOS 18](https://blog.timac.org/2024/1208-state-of-swift-and-swiftui-ios18) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Surveys how Apple used Swift and SwiftUI in iOS 18, connecting framework capabilities to production features. Useful for identifying platform-supported patterns before designing equivalent app architecture.

## [SwiftUI Weekly - Issue #204](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-203-c70)

- Published: `2024-12-03T07:24:48.832Z`

**Topics:** Apple Platform Ecosystem · Cross-Platform & Web · macOS & AppKit · Swift · SwiftUI · Xcode

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #204 · Reading

**Selected links:**
- [SwiftUI Zoom Navigation Transitions: Add a Touch of Magic to Your App](https://www.stphndxn.com/swiftui-zoom-navigation-transitions-add-a-touch-of-magic-to-your-app) — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Demonstrates zoom navigation transitions between SwiftUI source and destination views. Useful for preserving visual continuity when tapping thumbnails into detail screens.
- [SwiftUI matched geometry effect in a custom segmented control](https://nilcoalescing.com/blog/CustomSegmentedControlWithMatchedGeometryEffect) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a segmented control with matchedGeometryEffect so the selection indicator moves between segments. Useful for coordinated SwiftUI transitions while keeping selection state separate from animation identity.
- [Getting view size in SwiftUI without GeometryReader](https://nemecek.be/blog/208/getting-view-size-in-swiftui-without-geometryreader) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows modern ways to obtain a SwiftUI view's size without GeometryReader. Useful for reducing layout coupling when a component needs measurements for adaptive presentation.
- [SwiftUI Charts Plotting Functions](https://useyourloaf.com/blog/swiftui-charts-plotting-functions) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Plots mathematical functions with Swift Charts by generating sampled data and mapping it to marks. Useful for technical visualizations where the chart is derived from a formula rather than stored measurements.

## [SwiftUI Weekly - Issue #203](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-203)

- Published: `2024-11-19T05:45:58.937Z`

**Topics:** Cross-Platform & Web · Macros & Metaprogramming · Observation & State Management · Swift · SwiftUI · Xcode

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #203

**Selected links:**
- [Deep Dive into Environment in SwiftUI](https://azamsharp.com/2024/11/18/deep-dive-into-environment-in-swiftui.html) — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **NeKI brief:** Explains SwiftUI environment propagation, custom keys, and dependency lookup. Useful for deciding which shared services belong in environment values versus explicit initializer parameters.
- [Preview SwiftUI views with bindings using @Previewable](https://nilcoalescing.com/blog/PreviewSwiftUIViewsWithBindings) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Shows how Xcode 16's @Previewable macro supplies local mutable state so SwiftUI previews can exercise views that require bindings.
- [Mastering TextEditor in SwiftUI: Features, Limitations, and Tips](https://www.artemnovichkov.com/blog/mastering-text-editor-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Reviews TextEditor capabilities, styling constraints, and editing behavior in SwiftUI. Useful for designing robust multiline input while accounting for focus, scrolling, and platform differences.
- [Understanding SwiftUI's View Update Mechanism: Starting from a TimelineView Update Issue](https://fatbobman.com/en/posts/understanding-swiftui-view-update-mechanism) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a mental model for SwiftUI body evaluation, dependency tracking, and rendering updates. Useful when investigating redundant recomputation or assuming every state change redraws the entire hierarchy.
- [How to identify data in Lists and ForEach in SwiftUI](https://tanaschita.com/swiftui-identifiable) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains Identifiable requirements and stable identity in SwiftUI collections. Useful for preventing row reuse, animation, and diffing bugs caused by transient or duplicated identifiers.

## [SwiftUI Weekly - Issue #202](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-202)

- Published: `2024-11-11T09:06:45.768Z`

**Topics:** Accessibility · Cross-Platform & Web · Product Design · Security & Privacy · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #202 · Reading

**Selected links:**
- [SwiftUI Self-Sizing Flow Layouts](https://useyourloaf.com/blog/swiftui-self-sizing-flow-layouts) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Builds a self-sizing flow layout in SwiftUI by measuring children and wrapping them across available width. Useful for tags and chips where fixed grid assumptions fail.
- [Using ViewThatFits to Create a More Accessible List Cell in SwiftUI](https://blog.stackademic.com/using-viewthatfits-to-create-a-more-accessible-list-cell-in-swiftui-e87dc8feb4d4) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Uses ViewThatFits to select an accessible list-cell layout based on available space. Useful for preserving readable labels and actions across Dynamic Type sizes.
- [Font modifiers in SwiftUI](https://nilcoalescing.com/blog/FontModifiersInSwiftUI) — Article · Topics: Product Design · Swift · SwiftUI
  **NeKI brief:** Shows how custom font modifiers can centralize typography while preserving Dynamic Type and environment behavior. Useful for design-system APIs that should express semantic text roles rather than repeat font construction.
- [Conditional SwiftUI Accessibility Labels](https://useyourloaf.com/blog/conditional-swiftui-accessibility-labels) — Article · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Shows conditionally composing SwiftUI accessibility labels when a view's meaning changes with state. This avoids announcing stale or contradictory text and keeps the spoken contract aligned with what the control currently does.

## [SwiftUI Weekly - Issue #201](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-201)

- Published: `2024-10-21T14:26:23.455Z`

**Topics:** Architecture · Concurrency · Graphics, Media & Games · Objective-C & Cocoa · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #201 · Reading

**Selected links:**
- [Modular Navigation in SwiftUI: A Comprehensive Guide](https://ericsspace.com/articles/modular-navigation-in-swiftui-a-comprehensive-guide) — Article · Topics: Architecture · Swift · SwiftUI
  **NeKI brief:** Presents a modular navigation architecture for SwiftUI with separated route and feature concerns. Useful when deep links and navigation flows outgrow a single view's path handling.
- [MockData, PreviewModifiers and PreviewTraits in SwiftUI](https://www.youtube.com/watch?v=Yw7H4Ujpwtg) — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [SwiftUI Environment](https://nilcoalescing.com/blog/SwiftUIEnvironment) — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **NeKI brief:** Explains environment propagation and dependency lookup in SwiftUI. Useful for deciding which shared values belong in environment keys versus explicit view inputs.
- [Improve your app's UX with SwiftUI's task view modifier](https://peterfriese.dev/blog/2024/delay-task-modifier) — Article · Topics: Concurrency · Swift · SwiftUI
  **NeKI brief:** Implements a delayed task modifier that cancels prior work when the input changes. Useful for debounced search and validation, where task identity and cancellation prevent stale results.

## [SwiftUI Weekly - Issue #200](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-200)

- Published: `2024-09-30T17:14:55.385Z`

**Topics:** Apple Platform Ecosystem · Cross-Platform & Web · Objective-C & Cocoa · Security & Privacy · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #200 · Reading

**Selected links:**
- [Phase Animator Behavior](https://chris.eidhof.nl/post/phase-animator) — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **NeKI brief:** Investigates PhaseAnimator behavior through experiments aimed at explaining unexpected results. Use it to build a deeper SwiftUI animation model and verify details against the current SDK.
- [Insetting Scrollable Views’ Content With contentMargins In SwiftUI](https://serialcoder.dev/text-tutorials/swiftui/insetting-scrollable-views-content-with-contentmargins-in-swiftui) — Tutorial · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Demonstrates contentMargins for insetting ScrollView content in SwiftUI. Useful for consistent readable edges and indicator placement without spacer-based layout hacks.
- [Introduction to Communication Patterns in SwiftUI](https://azamsharp.com/2024/09/22/introduction-to-communication-patterns-in-swiftui.html) — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **NeKI brief:** Compares communication patterns between SwiftUI views, including bindings, callbacks, and shared state. Useful for choosing data-flow direction while keeping feature interfaces testable.
- [Using the zoom navigation transition in SwiftUI](https://www.createwithswift.com/using-the-zoom-navigation-transition-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Implements the zoom navigation transition to connect source and destination content across a SwiftUI navigation path. Useful for spatial continuity when presenting detail views from thumbnails.

## [SwiftUI Weekly - Issue #199](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-199)

- Published: `2024-09-09T19:49:43.177Z`

**Topics:** Developer Tools · macOS & AppKit · Macros & Metaprogramming · Spatial Computing · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #199 · News

**Selected links:**
- [Backport SwiftUI modifiers](https://alejandromp.com/development/blog/backport-swiftui-modifiers) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds compatibility wrappers that backport SwiftUI modifiers across OS versions. Useful for centralizing availability checks and preserving one call-site API for older deployments.
- [Github contribution graph with Swift Charts](https://www.artemnovichkov.com/blog/github-contribution-graph-swift-charts) — Article · Topics: Developer Tools · Swift
  **NeKI brief:** Creates a GitHub-style contribution graph with Swift Charts using calendar-shaped data. Useful for practicing custom mark layouts, color scales, and date-based visualization.
- [Integrate Chat with Stream’s iOS SDK 🛠️](https://getstream.io/tutorials/ios-chat) — Tutorial · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Walks through integrating Stream's chat SDK into an iOS app, including message UI and networking. Useful as an implementation reference when evaluating managed real-time messaging.
- [SwiftUI Previewable Macro](https://useyourloaf.com/blog/swiftui-previewable-macro) — Article · Topics: Macros & Metaprogramming · Swift · SwiftUI
  **NeKI brief:** Uses the Previewable macro to create mutable preview state without manually declaring State wrappers. Useful for interactive previews that exercise editing and selection flows quickly.
- [Animating SF Symbols on iOS 18](https://www.donnywals.com/animating-sf-symbols-on-ios-18) — Article
  **NeKI brief:** Uses iOS 18 SF Symbol animation APIs to express state changes through semantic symbol effects. Useful for lightweight feedback that remains aligned with the symbol's meaning and accessibility labels.

## [SwiftUI Weekly - Issue #198](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-198)

- Published: `2024-08-26T10:56:58.237Z`

**Topics:** Apple Platform Ecosystem · Graphics, Media & Games · Macros & Metaprogramming · Observation & State Management · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #198 · Reading

**Selected links:**
- [Using @Observable in SwiftUI views](https://nilcoalescing.com/blog/ObservableInSwiftUI) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Introduces @Observable and explains its property-level tracking difference from ObservableObject. The examples show why migration can reduce needless view updates while still requiring deliberate ownership of observable instances.
- [Let’s build iOS 18’s navigation title card in SwiftUI](https://jeffverkoeyen.com/blog/2024/08/24/iOS-18-Navigation-Title-Cards) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Recreates iOS 18 navigation title cards in SwiftUI and examines their layout behavior. Useful when matching system navigation visuals or building a compatible custom title treatment.
- [Understanding container values in SwiftUI](https://tanaschita.com/swiftui-container-values) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Uses SwiftUI container values to pass configuration through container hierarchies without bespoke environment keys. Useful for custom layout or collection components that need scoped child behavior.
- [SwiftUI for Mac 2024](https://troz.net/post/2024/swiftui-mac-2024) — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Reviews SwiftUI for macOS in 2024, including windowing, menus, and platform-specific controls. Useful for auditing which shared views need deliberate Mac adaptations.

## [SwiftUI Weekly - Issue #197](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-197)

- Published: `2024-08-19T10:45:25.615Z`

**Topics:** Apple Platform Ecosystem · Cross-Platform & Web · Graphics, Media & Games · macOS & AppKit · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #197 · Reading

**Selected links:**
- [What's New in SwiftUI - WWDC24](https://yaacoub.github.io/articles/swift-tip/what-s-new-in-swiftui-wwdc24) — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Summarizes WWDC24 SwiftUI additions and their intended use cases. Useful as a release-oriented checklist when deciding which iOS 18 APIs can replace custom implementations.
- [Customizing the appearance of symbol images in SwiftUI](https://nilcoalescing.com/blog/CustomizingTheAppearanceOfSymbolImagesInSwiftUI) — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Demonstrates SwiftUI symbol rendering modes, palettes, and hierarchical styles. Useful for making SF Symbols communicate emphasis and state without exporting separate tinted assets.
- [Hyper Advanced Link Techniques Using openURL](https://captainswiftui.substack.com/p/hyper-advanced-link-techniques-using) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explores advanced openURL link handling and interception in SwiftUI. Useful for routing external, internal, and transformed URLs while preserving environment-based test seams.
- [MeshGradients in iOS 18](https://www.youtube.com/watch?v=s_eQZ8rRV8Y) — Video · Topics: Graphics, Media & Games
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.

## [SwiftUI Weekly - Issue #196](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-196)

- Published: `2024-08-12T10:38:40.828Z`

**Topics:** Apple Platform Ecosystem · Cross-Platform & Web · Hardware & Devices · Product Design · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #196

**Selected links:**
- [Build Multilingual Ready Apps](https://yaacoub.github.io/articles/swift-tip/build-multilingual-ready-apps-wwdc24) — Article · Topics: Apple Platform Ecosystem · Developer Tools · Swift
  **NeKI brief:** Covers WWDC24 localization practices for multilingual Swift apps, including string handling and layout implications. Useful for finding hard-coded assumptions before expanding locale support.
- [Nested Grid Layout Anomaly: Analysis Approach and Resolution Strategies for SwiftUI Layout Issues](https://fatbobman.com/en/posts/analysis-approach-and-resolution-strategies-for-swiftui-layout-issues) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents a diagnostic workflow for SwiftUI layout problems: reduce the hierarchy, inspect proposed and reported sizes, then test competing explanations. Useful when visual symptoms hide an upstream sizing contract.
- [Truncating Text In SwiftUI](https://serialcoder.dev/text-tutorials/swiftui/truncating-text-in-swiftui) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Explains SwiftUI text truncation, line limits, and layout priorities. Useful for controlling overflow in list rows and cards while keeping important content visible.
- [Using onScrollPhaseChange for Scroll Changes in iOS 18](https://www.rudrank.com/exploring-swiftui-using-onscrollphasechange) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows onScrollPhaseChange reacting to scrolling phases in SwiftUI. Useful for deferring work, updating controls, or coordinating effects based on actively scrolling versus settled content.

## [SwiftUI Weekly - Issue #195](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-195)

- Published: `2024-08-05T15:18:59.956Z`

**Topics:** Cross-Platform & Web · Graphics, Media & Games · macOS & AppKit · Persistence & Synchronisation · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #195 · Reading

**Selected links:**
- [How to Tile Images in SwiftUI](https://fatbobman.com/en/posts/how-to-tile-images-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a tiled image effect by controlling repeat geometry and clipping in SwiftUI. Useful for backgrounds and texture-like surfaces where repeatedly scaling one bitmap would lose the intended visual rhythm.
- [Displaying Data with Table](https://captainswiftui.substack.com/p/displaying-data-with-table-part-i?r=a1d9l&triedRedirect=true) — Article · Topics: Persistence & Synchronisation · Swift · SwiftUI
  **NeKI brief:** Introduces SwiftUI Table for displaying structured rows and columns. Useful for macOS or iPad data-heavy screens where List cannot express comparative fields clearly.
- [Olympic Logo in SwiftUI](https://medium.com/@alessandromanilii/olympic-logo-in-swiftui-dee37cbd53f1) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Builds the Olympic logo with SwiftUI shapes and composition. Useful as a concrete exercise in layering, geometry, and reusable vector-style drawing.

## [SwiftUI Weekly - Issue #194](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-194)

- Published: `2024-07-15T12:03:07.308Z`

**Topics:** Cross-Platform & Web · Graphics, Media & Games · Macros & Metaprogramming · Spatial Computing · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #194 · Reading

**Selected links:**
- [Zoom Transitions in SwiftUI](https://www.youtube.com/watch?v=malwmE5fDHw) — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Creating advanced hover effects in visionOS](https://www.createwithswift.com/creating-advanced-hover-effects-in-visionos) — Article · Topics: Spatial Computing · Swift
  **NeKI brief:** Creates advanced hover effects for visionOS by combining pointer focus with SwiftUI visual transformations. Useful for spatial interfaces where depth and emphasis must respond to gaze or hand targeting.
- [Blend Modes in SwiftUI](https://digitalbunker.dev/blend-modes-in-swiftui) — Article · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Presents a concrete implementation of Blend Modes in SwiftUI. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.
- [List or LazyVStack: Choosing the Right Lazy Container in SwiftUI](https://itnext.io/list-or-lazyvstack-choosing-the-right-lazy-container-in-swiftui-27f5b8272dae) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Compares List and LazyVStack across styling, virtualization, and behavior. Useful for selecting a scrolling container based on interaction requirements rather than default convenience.
- [Using PreviewModifier to build a previewing environment](https://www.donnywals.com/using-previewmodifier-to-build-a-previewing-environment) — Article · Topics: Xcode
  **NeKI brief:** Uses PreviewModifier to centralize mock-data setup and other reusable dependencies for richer Xcode preview environments.

## [SwiftUI Weekly - Issue #193](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-193)

- Published: `2024-07-08T08:54:13.719Z`

**Topics:** App Distribution & Store Operations · Cross-Platform & Web · Developer Career & Practice · Graphics, Media & Games · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #193 · Reading

**Selected links:**
- [Mastering Animatable and AnimatablePair in SwiftUI](https://digitalbunker.dev/mastering-animatable-and-animatablepair-swiftui) — Article · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Explains Animatable and AnimatablePair for custom SwiftUI interpolation. Useful when building shape or geometry animations whose intermediate values need precise control.
- [SwiftUI can be a bit... eager](https://www.attributedstrings.com/swiftui-can-be-a-bit-eager) — Article · Topics: Foundation & Data Formats · Swift · SwiftUI
  **NeKI brief:** Investigates cases where SwiftUI evaluates views or work eagerly. Useful for diagnosing unexpected initialization, expensive computations, and lifecycle assumptions in declarative hierarchies.
- [A Summary Of How To Pass Data To SwiftUI Environment](https://serialcoder.dev/text-tutorials/swiftui/a-summary-of-how-to-pass-data-to-swiftui-environment) — Tutorial · Topics: Developer Career & Practice · Swift · SwiftUI
  **NeKI brief:** Summarizes passing dependencies through SwiftUI environment values and custom keys. Useful for comparing environment injection with explicit data flow in reusable views.
- [Laying out views with ContainerRelativeFrame in SwiftUI](https://www.youtube.com/watch?v=DudvesMYAAY) — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.

## [SwiftUI Weekly - Issue #192](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-192)

- Published: `2024-07-02T09:09:59.000Z`

**Topics:** Accessibility · Apple Platform Ecosystem · Graphics, Media & Games · Navigation & Deep Linking · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #192 · Reading

**Selected links:**
- [Using TextRenderer to create highlighted text](https://alexanderweiss.dev/blog/2024-06-24-using-textrenderer-to-create-highlighted-text) — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Uses TextRenderer to draw highlighted text in SwiftUI. Useful for search results, annotation, or syntax emphasis where attributed-string styling alone is insufficient.
- [SwiftUI and Accessibility: Creating Inclusive iOS Applications](https://iosdevlibrary.lemonsqueezy.com/buy/d130b2f9-cc2d-427f-b2a5-a93cfb58bfd1) — Article · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Provides a paid guide to accessibility in SwiftUI applications. Useful for auditing accessibility concepts and identifying topics to verify against Apple's current APIs.
- [My Favorite SwiftUI Updates in iOS 18](https://www.youtube.com/watch?v=aCbh9LmIZTI) — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Wrapping text within another view in SwiftUI](https://nilcoalescing.com/blog/WrappingTextWithinAnotherViewInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows how to make a custom container report text's intrinsic size and wrapping correctly. Useful when composed text gets clipped because a wrapper consumes the wrong proposed width.

## [SwiftUI Weekly - Issue #191](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-191)

- Published: `2024-06-17T19:22:55.398Z`

**Topics:** Apple Platform Ecosystem · Cross-Platform & Web · Security & Privacy · Swift · SwiftUI · Xcode

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #191

**Selected links:**
- [Drawing a Custom Spiral using SwiftUI's new LinePlot](https://lucasvandongen.dev/recreating_ovo_timer_in_swiftui.php) — Article · Topics: Swift · SwiftUI · Xcode
  **NeKI brief:** Recreates a timer interface with SwiftUI LinePlot and custom drawing. Useful for learning data-driven paths and animation techniques for instrument-like visualizations.
- [Zoom navigation transition in SwiftUI](https://augmentedcode.io/2024/06/17/zoom-navigation-transition-in-swiftui) — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Implements SwiftUI zoom navigation transitions with matched source and destination content. Useful for building detail navigation that retains the user's visual point of origin.
- [Present a form sheet in SwiftUI](https://nilcoalescing.com/blog/FormSheetInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents form-sheet sizing and presentation behavior in SwiftUI, including platform-specific adaptation. Useful when a form needs modal structure without treating every sheet as full-screen content.
- [Enhanced replace transition for SF Symbols in iOS 18](https://nilcoalescing.com/blog/EnhancedReplaceTransitionForSFSymbolsInIOS18) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Combines symbol replacement effects with SwiftUI transitions for smoother icon changes on iOS 18. Useful when state-driven symbols should animate semantically instead of cross-fading unrelated images.

## [SwiftUI Weekly - Issue #190](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-190)

- Published: `2024-06-10T10:26:42.278Z`

**Topics:** App Intents & System Surfaces · Composable Architecture · Maps & Location · Swift · SwiftUI · Xcode

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #190 · Reading

**Selected links:**
- [Creating gradient on polylines in SwiftUI MapKit](https://nilcoalescing.com/blog/GradientOnPolylinesInSwiftUIMapKit) — Article · Topics: Swift · SwiftUI · Xcode
  **NeKI brief:** Applies a gradient along MapKit polylines rendered in SwiftUI. Useful for route visualizations where color encodes progress or another value along a geographic path.
- [Aligning views in different stacks in SwiftUI](https://augmentedcode.io/2024/06/03/aligning-views-in-different-stacks-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows alignment techniques for views placed in different SwiftUI stacks. Useful when independent containers must share a baseline or edge without fragile offsets.
- [Formatting data as text in a Text view in SwiftUI](https://www.createwithswift.com/formatting-data-as-text-in-a-text-view-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Formats dates, numbers, and measurements directly in SwiftUI Text using locale-aware format styles. Useful for avoiding manually assembled strings that break localization or accessibility.
- [Using App Intents in a SwiftUI app](https://www.createwithswift.com/using-app-intents-swiftui-app) — Article · Topics: App Intents & System Surfaces · Swift · SwiftUI
  **NeKI brief:** Integrates App Intents with SwiftUI actions and entities so app capabilities become available to Shortcuts and system surfaces. Useful for designing discoverability alongside the view feature itself.
- [Composable Architecture Frequently Asked Questions](https://www.pointfree.co/blog/posts/141-composable-architecture-frequently-asked-questions) — Article · Topics: Architecture · Composable Architecture · Objective-C & Cocoa
  **NeKI brief:** Answers recurring Composable Architecture questions about state, effects, reducers, and testing boundaries. Useful for evaluating architectural trade-offs before introducing a framework into a SwiftUI feature.
- [What's new in Swift 6.0?](https://www.hackingwithswift.com/articles/269/whats-new-in-swift-6) — Article · Topics: Swift
  **NeKI brief:** Surveys Swift 6 language and concurrency changes with migration-oriented examples. Useful as a release overview before selecting specific compiler diagnostics or APIs to adopt.

## [SwiftUI Weekly - Issue #189](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-189)

- Published: `2024-06-04T09:49:38.933Z`

**Topics:** Concurrency · Cross-Platform & Web · macOS & AppKit · Networking · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #189 · Reading

**Selected links:**
- [AsyncImage in SwiftUI: Loading Images from URLs](https://matteomanferdini.com/swiftui-asyncimage) — Article · Topics: Concurrency · Swift · SwiftUI
  **NeKI brief:** Explains AsyncImage loading phases, placeholders, and failures in SwiftUI. Useful for simple remote-image screens while clarifying when caching or a dedicated loader is still required.
- [Scenes types in a SwiftUI Mac app](https://nilcoalescing.com/blog/ScenesTypesInASwiftUIMacApp) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Compares SwiftUI scene types for macOS applications, including windows, menus, and settings. Useful for choosing lifecycle and presentation boundaries before adding imperative AppKit plumbing.
- [How to create custom @Environment values in SwiftUI](https://tanaschita.com/swiftui-custom-environment-values) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Defines custom SwiftUI environment keys and values for shared dependencies or configuration. Useful when a value should flow through a view tree while remaining overridable in previews and tests.
- [Adding a Bottom Sheet or Partial Modal in SwiftUI](https://medium.com/@jpmtech/adding-a-bottom-sheet-or-partial-modal-in-swiftui-b962bd9cb962) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a partial bottom sheet in SwiftUI with drag and presentation behavior. Useful for lightweight modal flows when system sheet detents need custom interaction.
- [Do NOT init State externally in SwiftUI](https://samwize.com/2024/05/08/do-not-init-state-externally-in-swiftui-view) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains the state-ownership behavior behind Do NOT init State externally in SwiftUI. Use it to distinguish initialization, bindings, and view identity so updates remain predictable across SwiftUI recomputation and navigation.

## [SwiftUI Weekly - Issue #188](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-188)

- Published: `2024-05-27T10:42:14.070Z`

**Topics:** App Services & Extensions · Cross-Platform & Web · Navigation & Deep Linking · Objective-C & Cocoa · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #188 · Reading

**Selected links:**
- [Programmatic navigation in SwiftUI with NavigationPath and navigationDestination](https://www.donnywals.com/programmatic-navigation-in-swiftui-with-navigationpath-and-navigationdestination) — Article · Topics: Navigation & Deep Linking · Swift · SwiftUI
  **NeKI brief:** Builds programmatic navigation with NavigationPath and navigationDestination, keeping route state explicit and codable. Useful for deep links and multi-step flows that exceed direct NavigationLink composition.
- [handling deeplinks on iOS 14](https://www.donnywals.com/handling-deeplinks-in-ios-14-with-onopenurl) — Article · Topics: Navigation & Deep Linking · Swift · SwiftUI
  **NeKI brief:** Handles deep links in SwiftUI using onOpenURL on iOS 14. Useful for routing incoming URLs into navigation state while supporting early SwiftUI deployments.
- [Your Complete Guide to Push Notifications in SwiftUI](https://medium.com/@jpmtech/your-complete-guide-to-push-notifications-in-swiftui-8a13f5588662) — Tutorial · Topics: App Services & Extensions · Swift · SwiftUI
  **NeKI brief:** Walks through push-notification registration and handling in a SwiftUI app. Useful for connecting authorization, device tokens, and notification-driven navigation into app lifecycle code.
- [How to build segmented circular progress views in SwiftUI with Swift Charts](https://www.polpiella.dev/swiftui-charts-progress-views) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds progress visualizations with Swift Charts and SwiftUI, mapping task values into marks and labels. Useful for dashboards where progress needs accessible, data-driven presentation.
- [MVVM: An architectural coding pattern to structure SwiftUI Views](https://www.avanderlee.com/swiftui/mvvm-architectural-coding-pattern-to-structure-views) — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **NeKI brief:** Separates SwiftUI view rendering from observable view-model state and actions, while discussing when that indirection helps testing and when it adds ceremony. Useful for choosing MVVM boundaries in larger view hierarchies.

## [SwiftUI Weekly - Issue #187](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-187)

- Published: `2024-05-20T22:04:41.287Z`

**Topics:** Concurrency · Graphics, Media & Games · Swift · SwiftUI · UIKit · Xcode

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #187 · Reading

**Selected links:**
- [React to network status updates in SwiftUI](https://nilcoalescing.com/blog/ReactToNetworkStatusUpdatesInSwiftUI) — Article · Topics: Concurrency · Swift · SwiftUI
  **NeKI brief:** Adapts NWPathMonitor into an AsyncSequence so SwiftUI state can react to connectivity changes with structured cancellation. Follow it when replacing callback plumbing while preserving lifecycle-safe observation.
- [Did you know that Xcode Previews also work with UIKit?](https://www.youtube.com/watch?v=sC0WnigbmJw) — Video · Topics: Graphics, Media & Games · UIKit · Xcode
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Using materials with SwiftUI](https://www.createwithswift.com/using-materials-with-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Uses SwiftUI materials to create translucent surfaces that adapt to background content and appearance. Useful for overlays and cards that should follow system contrast behavior instead of fixed alpha colors.
- [Avoid These Common Errors When Switching from UIKit to SwiftUI](https://dev.jeremygale.com/avoid-these-common-errors-when-switching-from-uikit-to-swiftui) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Catalogues common migration mistakes when moving from UIKit to SwiftUI. Useful as a review checklist for state ownership, lifecycle assumptions, and layout translation.
- [What Does spacing = nil Mean in SwiftUI?](https://fatbobman.com/en/posts/spacing-of-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Investigates SwiftUI spacing decisions across stacks and platform defaults, showing why seemingly identical layouts can differ. Useful when tuning rhythm without replacing system spacing with unexplained constants.

## [SwiftUI Weekly - Issue #186](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-186)

- Published: `2024-05-15T12:55:37.453Z`

**Topics:** Apple Platform Ecosystem · Architecture · Graphics, Media & Games · Objective-C & Cocoa · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #186 · Reading

**Selected links:**
- [How to use custom fonts and images in a Swift Package](https://dev.jeremygale.com/swiftui-how-to-use-custom-fonts-and-images-in-a-swift-package) — Article · Topics: Swift · Swift Package Manager · SwiftUI
  **NeKI brief:** Explains bundling custom fonts and images in a Swift package for SwiftUI. Useful for reusable modules that must load resources through their package bundle reliably.
- [Pointfree's SyncUps App: A Great Example Architecture for a SwiftUI App](https://rodschmidt.com/posts/syncups) — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **NeKI brief:** Analyses Point-Free's SyncUps sample architecture and feature boundaries. Useful for studying a complete SwiftUI application structure before adapting its patterns selectively.
- [SyncUps](https://github.com/pointfreeco/syncups) — Source repository · Topics: Architecture · Developer Tools · Objective-C & Cocoa
  **NeKI brief:** Provides the SyncUps sample repository with SwiftUI architecture, persistence, and tests. Useful for inspecting concrete implementation trade-offs rather than relying on abstract diagrams.
- [Mastering the containerRelativeFrame Modifier in SwiftUI](https://fatbobman.com/en/posts/mastering-the-containerrelativeframe-modifier-in-swiftui) — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Examines containerRelativeFrame sizing against the enclosing container rather than the immediate parent. Useful for predictable adaptive cards, paging layouts, and safe-area-aware dimensions.
- [Creating Settings Screen in SwiftUI With AppStorage](https://holyswift.app/using-userdefaults-to-persist-in-swiftui) — Article · Topics: Persistence & Synchronisation · Swift · SwiftUI
  **NeKI brief:** Shows persisting SwiftUI settings with AppStorage and UserDefaults. Useful for small preferences whose lifetime should survive launches without introducing a database model.

## [SwiftUI Weekly - Issue #185](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-185)

- Published: `2024-05-06T13:22:31.904Z`

**Topics:** Architecture · Composable Architecture · Graphics, Media & Games · Objective-C & Cocoa · Swift · SwiftUI

**Sections:** Reading · Videos

**Selected links:**
- [Flighty in SwiftUI](https://www.youtube.com/watch?v=81FwPLo-1eE) — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Challenges When Re-using SwiftUI Cells in a UITableView](https://lucasvandongen.dev/swiftui_uitableviewcell_reuse_id.php) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI cell reuse inside UITableView and identity interactions. Useful when embedding SwiftUI content in reusable UIKit cells and tracking stale state bugs.
- [The Composable Architecture: My 3 Year Experience](https://rodschmidt.com/posts/composable-architecture-experience) — Article · Topics: Architecture · Composable Architecture · Objective-C & Cocoa
  **NeKI brief:** A three-year TCA retrospective surfaces production trade-offs that API introductions omit, including architectural discipline and maintenance cost. Use it to evaluate long-lived team fit rather than reading it as a generic framework endorsement.
- [TCA](https://github.com/pointfreeco/swift-composable-architecture) — Source repository · Topics: Architecture · Composable Architecture · Objective-C & Cocoa
  **NeKI brief:** The Composable Architecture structures feature state, actions, reducers, dependencies, and tests around explicit unidirectional flow. Use the repository and migration material to evaluate operational trade-offs before adopting or upgrading TCA in a production app.

## [SwiftUI Weekly - Issue #184](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-184)

- Published: `2024-04-29T19:19:04.048Z`

**Topics:** Apple Platform Ecosystem · Swift · SwiftUI · Xcode

**Sections:** Reading

**Selected links:**
- [In-Depth Exploration of Overlay and Background Modifiers in SwiftUI](https://fatbobman.com/en/posts/in-depth-exploration-of-overlay-and-background-modifiers-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Compares SwiftUI overlay and background modifiers with ZStack, explaining their layout relationships and suitable use cases. Use it when attaching decoration or measuring content while preserving the intended parent-child geometry.
- [SwiftUI Pie Charts](https://useyourloaf.com/blog/swiftui-pie-charts) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Introduces iOS 17 Swift Charts SectorMark for pie-chart segments, including angle values and styling. Follow it when presenting proportional data and deciding how labels, legends, and accessibility should accompany the visual.

## [SwiftUI Weekly - Issue #183](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-183)

- Published: `2024-04-22T17:42:59.039Z`

**Topics:** Developer Career & Practice · Graphics, Media & Games · Objective-C & Cocoa · Observation & State Management · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #183 · Reading

**Selected links:**
- [Making your lists searchable in a SwiftUI app](https://www.createwithswift.com/making-your-lists-searchable-in-a-swiftui-app) — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **NeKI brief:** Adds searchable behavior to SwiftUI lists and connects query state to filtering. Useful for implementing discoverable in-app search while keeping navigation and empty-state handling explicit.
- [Professional Grade Application Protection for Swift and Objective-C iOS Apps](https://www.vpdae.com/redirect/e9xwl532e60eyhhks87um6yabmy) — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **NeKI brief:** Promotes application protection for Swift and Objective-C binaries. Useful only as security-product context when assessing threat models and tooling claims for shipped apps.
- [Bar Chart creation using Swift Charts](https://www.avanderlee.com/swift-charts/bar-chart-creation-using-swift-charts) — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Builds a bar chart with Swift Charts by mapping model values to BarMark and configuring axes, labels, and styling. Useful as a concrete starting point for data-driven chart views.
- [Improve Test Clarity (TDD with SwiftUI)](https://www.youtube.com/watch?v=AF8cCxrJr8M) — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.

## [SwiftUI Weekly - Issue #182](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-182)

- Published: `2024-04-15T08:36:47.645Z`

**Topics:** App Services & Extensions · Localization · Navigation & Deep Linking · Swift · SwiftUI

**Sections:** Reading

**Selected links:**
- [Creating Shapes from SVG in a SwiftUI app](https://www.createwithswift.com/creating-shapes-from-svg-in-a-swiftui-app) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows how to turn SVG path data into scalable SwiftUI Shape implementations rather than raster assets. Use it when importing vector artwork and deciding how path parsing, fills, strokes, and resizing should be handled.

## [SwiftUI Weekly - Issue #181](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-180-e74)

- Published: `2024-04-09T05:33:14.059Z`

**Topics:** Architecture · Graphics, Media & Games · macOS & AppKit · Objective-C & Cocoa · Swift · SwiftUI

**Sections:** Reading · Videos

**Selected links:**
- [Camera capture setup in a SwiftUI app](https://www.createwithswift.com/camera-capture-setup-in-a-swiftui-app) — Tutorial · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Sets up an AVFoundation camera feed for a SwiftUI app, including capture-session configuration and preview integration. Follow it as a foundation for camera features, then add authorization, lifecycle, and error handling deliberately.
- [Identifiable protocol in SwiftUI explained with code examples](https://www.avanderlee.com/swiftui/identifiable-protocol-object-identifier) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Compares stable model identifiers with ObjectIdentifier-based identity in SwiftUI. Useful for understanding how ForEach diffing behaves and why identity must remain stable when rows are updated or reordered.
- [How to avoid using AnyView in SwiftUI](https://tanaschita.com/swiftui-how-to-avoid-using-anyview) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows alternatives to AnyView through generics, builders, and conditional composition. Useful for preserving static view types and avoiding type erasure where it would obscure layout or performance.
- [In Search of a Smooth Scroll](https://byla.lt/posts/in-search-of-smooth-scroll) — Article · Topics: Objective-C & Cocoa
  **NeKI brief:** Examines SwiftUI rendering and scrolling costs behind In Search of a Smooth Scroll. Use it to identify identity, layout, and update-frequency risks before measuring regressions with Instruments on representative devices.

## [SwiftUI Weekly - Issue #180](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-180)

- Published: `2024-04-01T10:00:24.491Z`

**Topics:** Concurrency · Graphics, Media & Games · Observation & State Management · Persistence & Synchronisation · Swift · SwiftUI

**Sections:** Videos

**Selected links:**
- [Practical SwiftData: Building SwiftUI Applications with Modern Approaches](https://fatbobman.com/en/posts/practical-swiftdata-building-swiftui-applications-with-modern-approaches) — Article · Topics: Concurrency · Swift · SwiftData
  **NeKI brief:** Examines practical SwiftData application structure, including strict-concurrency challenges, model contexts, and SwiftUI integration. Use it to evaluate persistence boundaries and actor isolation before scaling a data-driven app beyond a demo.
- [SwiftUI Views and @MainActor](https://fatbobman.com/en/posts/swiftui-views-and-mainactor) — Tutorial · Topics: Concurrency · Swift · SwiftUI
  **NeKI brief:** Explains SwiftUI View isolation and MainActor behavior under modern Swift concurrency. Useful for understanding why view code can interact with UI state safely while model work belongs elsewhere.
- [Key press events detection in SwiftUI](https://www.avanderlee.com/swiftui/key-press-events-detection) — Article · Topics: Concurrency · Swift · SwiftUI
  **NeKI brief:** Handles keyboard input in SwiftUI using key-event modifiers and phases, including modifier flags. Useful for making iPad hardware-keyboard and macOS-style shortcuts respond without dropping events into UIKit bridges.
- [SwiftUI Inverting A Boolean Binding](https://useyourloaf.com/blog/swiftui-inverting-a-boolean-binding) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Demonstrates deriving an inverted SwiftUI Binding<Bool> for controls such as suppression toggles and confirmation dialogs. Follow it when a UI expresses the opposite meaning of stored state without introducing duplicated or unsynchronized properties.

## [SwiftUI Weekly - Issue #179](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-179)

- Published: `2024-03-19T15:26:15.403Z`

**Topics:** Concurrency · Cross-Platform & Web · Developer Career & Practice · Maps & Location · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #179 · Reading

**Selected links:**
- [How to build a draggable bottom sheet with a scroll view in SwiftUI](https://tanaschita.com/20240311-draggable-sheet-with-scroll-view) — Article · Topics: Maps & Location · Swift · SwiftUI
  **NeKI brief:** Builds a draggable SwiftUI bottom sheet coordinated with an inner ScrollView. Useful for designing gesture handoff and preventing sheet dragging from fighting content scrolling.
- [Customizing a Chart in Swift Charts](https://www.createwithswift.com/customizing-a-chart-in-swift-charts) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Customizes Swift Charts marks, axes, annotations, and styling to match an application's visual language. Useful when default chart presentation obscures the data story or interaction affordances.
- [How to support dark mode in SwiftUI programmatically](https://tanaschita.com/supporting-dark-mode-programmatically) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows programmatic dark-mode handling in SwiftUI through color-scheme environment control. Useful for previews, settings, and controlled appearance tests without hard-coding global behavior.
- [SwiftUI Tasks Blocking the MainActor](https://useyourloaf.com/blog/swiftui-tasks-blocking-the-mainactor) — Article · Topics: Concurrency · Swift · SwiftUI
  **NeKI brief:** Diagnoses SwiftUI tasks that accidentally block MainActor execution and explains how to move expensive work off the UI executor. Useful for investigating frozen interfaces during async operations.
- [Tips and Considerations for Using Lazy Containers in SwiftUI](https://fatbobman.com/en/posts/tips-and-considerations-for-using-lazy-containers-in-swiftui) — Article · Topics: Developer Career & Practice · Swift · SwiftUI
  **NeKI brief:** Discusses lazy stack and grid creation behavior, identity, measurement, and memory trade-offs. Useful for choosing lazy containers based on workload and avoiding assumptions that off-screen views are never evaluated.

## [SwiftUI Weekly - Issue #178](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-178)

- Published: `2024-03-04T12:24:09.172Z`

**Topics:** Concurrency · Graphics, Media & Games · Macros & Metaprogramming · Spatial Computing · Swift · SwiftUI

**Sections:** Reading · Videos

**Selected links:**
- [How to delay an animation in SwiftUI](https://tanaschita.com/20240226-delay-swiftui-animation) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows delaying a SwiftUI animation by combining state changes with an explicit animation delay. Use it for staged appearances or timed UI transitions, while keeping cancellation and repeated-trigger behavior predictable.
- [An Introduction to Isolation in Swift](https://www.massicotte.org/intro-to-isolation) — Tutorial · Topics: Concurrency · Developer Community & Business · Swift
  **NeKI brief:** Explores An Introduction to Isolation in Swift with concrete Swift concurrency examples. Follow it to reason about isolation, cancellation, and Sendable boundaries, then verify availability and diagnostics against current Swift documentation.
- [Mastering Model3D View](https://www.createwithswift.com/mastering-model3d-view) — Article · Topics: Swift
  **NeKI brief:** Explores RealityKit’s Model3D view for loading and displaying 3D assets in visionOS. Follow it when embedding model content in SwiftUI and deciding how asynchronous loading, placeholders, errors, and scale affect the experience.
- [RevenueCat's SDK](https://www.revenuecat.com/docs) — Article
  **NeKI brief:** RevenueCat's SDK documentation describes configuring products, purchases, entitlements, and customer subscription state in an app. Follow it when prototyping StoreKit-backed subscriptions, while checking platform versions, receipt behavior, and current App Store rules before shipping.

## [SwiftUI Weekly - Issue #177](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-176-583)

- Published: `2024-02-26T08:21:15.312Z`

**Topics:** Graphics, Media & Games · Persistence & Synchronisation · Swift · SwiftData · SwiftUI · UIKit

**Sections:** Reading · Videos

**NeKI brief:** Customizable component APIs, Observation networking, NWPathMonitor, and Swift isolation make this issue useful for designing reusable SwiftUI boundaries. Research it when model updates depend on connectivity and actor isolation must remain explicit.

## [SwiftUI Weekly - Issue #176](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-176)

- Published: `2024-02-12T08:54:16.360Z`

**Topics:** Accessibility · Graphics, Media & Games · Observation & State Management · Spatial Computing · Swift · SwiftUI

**Sections:** Reading · Videos

**Selected links:**
- [Create an animated transition with Matched Geometry Effect in SwiftUI](https://www.createwithswift.com/create-an-animated-transition-with-matched-geometry-effect-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds an animated SwiftUI transition with matchedGeometryEffect, linking corresponding elements across view states. Use it to coordinate shared-element motion while checking stable identifiers, namespaces, and layout changes across containers.
- [RevenueCat's SDK](https://www.revenuecat.com/docs) — Article
  **NeKI brief:** RevenueCat's SDK documentation describes configuring products, purchases, entitlements, and customer subscription state in an app. Follow it when prototyping StoreKit-backed subscriptions, while checking platform versions, receipt behavior, and current App Store rules before shipping.

## [SwiftUI Weekly - Issue #175](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-175)

- Published: `2024-01-29T09:25:06.841Z`

**Topics:** Graphics, Media & Games · Spatial Computing · Swift · SwiftUI

**Sections:** Reading · Videos

**Selected links:**
- [Implementing volumes in visionOS](https://www.createwithswift.com/implementing-volumes-in-visionos) — Article · Topics: Spatial Computing · Swift
  **NeKI brief:** Explains visionOS volumes as containers for inspectable 3D content viewed from multiple perspectives. Follow it when choosing between windows and volumes and when structuring immersive RealityKit content inside a SwiftUI app.
- [ScrollView Bounce Behavior configuration in SwiftUI](https://www.avanderlee.com/swiftui/scrollview-bounce-behavior) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Configures ScrollView bounce independently per axis with the modern scrollBounceBehavior modifier. Useful when nested or horizontally paged layouts need controlled elasticity without globally disabling expected scrolling physics.
- [RevenueCat's SDK](https://www.revenuecat.com/docs) — Article
  **NeKI brief:** RevenueCat's SDK documentation describes configuring products, purchases, entitlements, and customer subscription state in an app. Follow it when prototyping StoreKit-backed subscriptions, while checking platform versions, receipt behavior, and current App Store rules before shipping.

## [SwiftUI Weekly - Issue #174](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-174)

- Published: `2024-01-22T13:02:05.973Z`

**Topics:** Code Quality · Macros & Metaprogramming · Observation & State Management · Swift · SwiftUI · UIKit

**Sections:** Reading

**NeKI brief:** Lazy grids, launch-state modeling, one-way bindings, and SwiftUI composition patterns cover scalable collection screens. Follow it to choose grid containers deliberately and keep startup transitions and child data flow predictable.

## [SwiftUI Weekly - Issue #173](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-173)

- Published: `2024-01-15T11:07:04.573Z`

**Topics:** App Distribution & Store Operations · Concurrency · Macros & Metaprogramming · Observation & State Management · Swift · SwiftUI

**Sections:** Reading

**Selected links:**
- [Asynchronous SwiftUI buttons](https://blog.thomasdurand.fr/story/2024-01-14-asynchronous-swiftui-buttons) — Article · Topics: Concurrency · Swift · SwiftUI
  **NeKI brief:** Explores Asynchronous SwiftUI buttons with concrete Swift concurrency examples. Follow it to reason about isolation, cancellation, and Sendable boundaries, then verify availability and diagnostics against current Swift documentation.
- [@Observable Macro performance increase over ObservableObject](https://www.avanderlee.com/swiftui/observable-macro-performance-increase-observableobject) — Article · Topics: Macros & Metaprogramming · Observation & State Management · Performance
  **NeKI brief:** Compares the Observation framework's @Observable macro with ObservableObject, focusing on property-level tracking and view invalidation. The measurements and migration examples explain why fewer unnecessary updates can improve SwiftUI performance.
- [Perception: A back-port of @Observable](https://www.pointfree.co/blog/posts/129-perception-a-back-port-of-observable) — Article · Topics: Observation & State Management · Swift
  **NeKI brief:** Introduces Perception as a back-port of Swift Observation for older deployment targets. Useful when sharing observation-based SwiftUI architecture before the application can require iOS 17.

## [SwiftUI Weekly - Issue #172](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-172)

- Published: `2024-01-08T11:28:18.077Z`

**Topics:** Combine & Reactive Programming · Objective-C & Cocoa · Observation & State Management · Performance · Swift · SwiftUI

**Sections:** Reading

**Selected links:**
- [SwiftUI Binding Tips](https://chris.eidhof.nl/post/swiftui-binding-tricks) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Shows how dynamic member lookup and small transformations can make SwiftUI bindings easier to adapt. Use it when deriving focused bindings such as an inverted Boolean without repetitive closure code.
- [RevenueCat's SDK](https://www.revenuecat.com/docs) — Article
  **NeKI brief:** RevenueCat's SDK documentation describes configuring products, purchases, entitlements, and customer subscription state in an app. Follow it when prototyping StoreKit-backed subscriptions, while checking platform versions, receipt behavior, and current App Store rules before shipping.

## [SwiftUI Weekly - Issue #171](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-171)

- Published: `2023-12-25T11:04:56.488Z`

**Topics:** Graphics, Media & Games · Maps & Location · Objective-C & Cocoa · Persistence & Synchronisation · Swift · SwiftUI

**Sections:** Reading

**Selected links:**
- [Build your first app with SwiftUI and SwiftData](https://www.hackingwithswift.com/articles/263/build-your-first-app-with-swiftui-and-swiftdata) — Article · Topics: Swift · SwiftData · SwiftUI
  **NeKI brief:** Walks through a complete SwiftUI and SwiftData app, connecting model declaration, queries, and view updates. Use it as a baseline for checking persistence wiring before introducing custom architecture.
- [Quick Search with SwiftUI Searchable](https://danielsaidi.com/blog/2023/12/20/quick-search-with-swiftui-searchable) — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **NeKI brief:** Shows a compact searchable SwiftUI flow with query state and filtering. Follow it when adding search to a list and deciding where debouncing, predicate construction, or empty-query behavior belongs.
- [Using TipKit on a SwiftUI app](https://www.createwithswift.com/using-tipkit-on-a-swiftui-app) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Integrates TipKit into a SwiftUI app, defining tips and presentation conditions. Useful for contextual onboarding that can be governed by eligibility rules instead of one-time alerts.

## [SwiftUI Weekly - Issue #170](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-170)

- Published: `2023-12-11T13:23:19.560Z`

**Topics:** App Distribution & Store Operations · Concurrency · Graphics, Media & Games · Objective-C & Cocoa · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #170 · Reading

**Selected links:**
- [AsyncPhoto for displayng large photos in SwiftUI](https://augmentedcode.io/2023/12/11/asyncphoto-in-swiftui-for-displayng-large-photos) — Article · Topics: Concurrency · Swift · SwiftUI
  **NeKI brief:** Implements an AsyncPhoto-style loader that accepts an async data-producing closure instead of only a URL, with placeholder and failure states. Useful when loading large or transformed images while keeping view code asynchronous and testable.
- [SwiftUI geometryGroup() Guide: From Theory to Practice](https://medium.com/the-swift-cooperative/swiftui-geometrygroup-guide-from-theory-to-practice-1a7f4b04c4ec) — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Explains geometryGroup() and the animation anomalies it addresses by grouping a view's geometry before interpolation. Useful when nested SwiftUI animations distort layout or require coordinated geometry without rebuilding the hierarchy.
- [App Localizations](https://www.youtube.com/watch?v=kbgNL7VrQPo) — Video · Topics: Graphics, Media & Games · Localization · Swift
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [How to ask the user to leave an App Store review](https://www.youtube.com/watch?v=RUWGjeDCkN8) — Video · Topics: App Distribution & Store Operations · Graphics, Media & Games · Objective-C & Cocoa
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.

## [SwiftUI Weekly - Issue #169](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-169)

- Published: `2023-12-04T12:32:29.066Z`

**Topics:** Architecture · Graphics, Media & Games · Maps & Location · Objective-C & Cocoa · Swift · SwiftUI

**Sections:** Reading · Videos

**Selected links:**
- [Accessing the app life cycle within a SwiftUI app](https://www.createwithswift.com/accessing-the-app-life-cycle-within-a-swiftui-app) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows how a SwiftUI App accesses application lifecycle events and coordinates them with scene-driven state. Useful when migrating lifecycle-dependent work from AppDelegate callbacks while preserving launch, background, and foreground handling.
- [Observable Architecture Beta!](https://www.pointfree.co/blog/posts/125-observable-architecture-beta) — Article · Topics: Architecture · Objective-C & Cocoa · Observation & State Management
  **NeKI brief:** Introduces the beta Observable Architecture tools from Point-Free and how existing Composable Architecture code can adopt the observation model. Useful for evaluating migration trade-offs between view-driven observation, testable state, and deployment support.

## [SwiftUI Weekly - Issue #168](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-168)

- Published: `2023-11-20T17:58:13.347Z`

**Topics:** Apple Platform Ecosystem · Graphics, Media & Games · macOS & AppKit · Swift · SwiftUI · UIKit

**Sections:** Reading · Library

**Selected links:**
- [Animating numeric text in SwiftUI with the Content Transition modifier](https://www.createwithswift.com/animating-numeric-text-in-swiftui-with-the-content-transition-modifier) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Uses SwiftUI's contentTransition modifier to animate changing numeric text rather than manually interpolating strings. Useful for counters, scores, and prices where updates should remain legible and transition with semantic content changes.
- [Custom Traits and SwiftUI](https://useyourloaf.com/blog/custom-traits-and-swiftui) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Explains defining custom UIKit traits and allowing them to interoperate with SwiftUI's environment from iOS 17 onward. Useful for carrying app-specific presentation or configuration values across mixed UIKit and SwiftUI hierarchies.
- [Introducing Inferno: Metal shaders for SwiftUI](https://www.hackingwithswift.com/articles/262/introducing-inferno-metal-shaders-for-swiftui) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Introduces Inferno's Metal shader effects for SwiftUI and the API boundary between declarative views and GPU code. Follow it when evaluating shader-driven visuals, performance, and fallback behavior.

## [SwiftUI Weekly - Issue #167](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-167)

- Published: `2023-11-06T09:00:48.537Z`

**Topics:** Cross-Platform & Web · Graphics, Media & Games · Objective-C & Cocoa · Product Design · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #167 · Reading

**Selected links:**
- [Understanding Text Case And Capitalization In SwiftUI](https://serialcoder.dev/text-tutorials/swiftui/understanding-text-case-and-capitalization-in-swiftui) — Tutorial · Topics: Product Design · Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI text-case and capitalization modifiers across labels, fields, and user-entered text. Useful for choosing presentation-only transformations without corrupting stored input or producing inconsistent localization behavior.
- [Building Complex Scroll Animations With New iOS 17 API's](https://www.youtube.com/watch?v=ytRim2TSdyY) — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Hierarchical background styles in SwiftUI](https://nilcoalescing.com/blog/HierarchicalBackgroundStyles) — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **NeKI brief:** Explains hierarchical background styles and how they derive contrast from surrounding system materials. Useful for adaptive surfaces that should remain legible across appearances without custom color branches.

## [SwiftUI Weekly - Issue #166](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-166)

- Published: `2023-10-31T07:27:47.287Z`

**Topics:** Apple Platform Ecosystem · Swift · SwiftUI · UIKit

**Sections:** Reading

**Selected links:**
- [Backport SwiftUI modifiers](https://alejandromp.com/blog/backport-swiftui-modifiers) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents a concrete implementation of Backport SwiftUI modifiers. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.
- [Advanced SwiftUI Animations – Part 7: PhaseAnimator](https://swiftui-lab.com/swiftui-animations-part7) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explores another advanced SwiftUI animation experiment, focusing on coordinated transitions and animatable state. Useful for understanding interpolation behavior beyond straightforward implicit animations.
- [Mastering TipKit: Basics](https://itnext.io/mastering-tipkit-basics-dcccfdbc9927) — Article · Topics: Apple Platform Ecosystem
  **NeKI brief:** Introduces TipKit's core model for defining, displaying, and controlling contextual tips in an app. Useful when planning discoverability prompts with eligibility rules and dismissals instead of ad hoc overlays.

## [SwiftUI Weekly - Issue #165](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-165)

- Published: `2023-10-23T07:26:31.986Z`

**Topics:** Combine & Reactive Programming · Graphics, Media & Games · Macros & Metaprogramming · Swift · SwiftUI · UIKit

**Sections:** News · Reading · Videos

**Selected links:**
- [Content Unavailable Views](https://useyourloaf.com/blog/content-unavailable-views) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Compares SwiftUI ContentUnavailableView with UIKit’s UIContentUnavailableConfiguration, showing how labels, descriptions, actions, and state-driven updates produce consistent empty, error, and no-results screens.
- [Apple’s use of Swift and SwiftUI in iOS 17](https://blog.timac.org/2023/1019-state-of-swift-and-swiftui-ios17) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Reviews Swift and SwiftUI changes around iOS 17 with implementation context. Use it to orient migration work and identify which new APIs affect deployment targets or existing view architecture.

## [SwiftUI Weekly - Issue #164](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-164)

- Published: `2023-10-16T11:29:03.902Z`

**Topics:** Graphics, Media & Games · Hardware & Devices · Objective-C & Cocoa · Swift · SwiftUI · Xcode

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #164 · Reading

**Selected links:**
- [How to dismiss Keyboard in SwiftUI](https://sarunw.com/posts/dismiss-keyboard-in-swiftui) — Article · Topics: Hardware & Devices · Swift · SwiftUI
  **NeKI brief:** Demonstrates dismissing the keyboard from SwiftUI using environment actions and focus state. Useful for predictable form submission and navigation flows without reaching for global UIKit calls.
- [Mastering Xcode Previews: Show, Edit, and Preview SwiftUI Code](https://www.swiftyplace.com/blog/xcode-previews-with-swiftui-and-uikit) — Article · Topics: Swift · SwiftUI · Xcode
  **NeKI brief:** Demonstrates Xcode Previews for SwiftUI views and UIKit components, including preview setup and editing workflow. Useful for shortening visual feedback loops when screens combine representables, legacy views, and new SwiftUI code.
- [Replacing IBDesignable with Xcode Previews](https://useyourloaf.com/blog/replacing-ibdesignable-with-xcode-previews) — Article · Topics: Xcode
  **NeKI brief:** Replaces IBDesignable previews with Xcode previews for UIKit views, shortening visual iteration without Interface Builder rendering. Useful during incremental UIKit-to-SwiftUI tooling modernization.

## [SwiftUI Weekly - Issue #163](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-163)

- Published: `2023-10-09T12:59:37.492Z`

**Topics:** Combine & Reactive Programming · Concurrency · Graphics, Media & Games · Observation & State Management · Swift · SwiftUI

**Sections:** Reading · Videos

**Selected links:**
- [Daniel Steinberg - SwiftUI to destroy the Publishing Industry](https://www.youtube.com/watch?v=rhqASksgJu0) — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Chris Eidhof - A Day in the Life of a SwiftUI View](https://www.youtube.com/watch?v=MRY3UCUVv98) — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Advanced SwiftUI Animations – Part 6: CustomAnimation](https://swiftui-lab.com/swiftui-animations-part6) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explores advanced SwiftUI animation composition and transition timing through concrete experiments. Useful for understanding phase, interpolation, and coordination limits beyond basic withAnimation calls.
- [Advanced SwiftUI Animations series](https://swiftui-lab.com/swiftui-animations-part1) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds foundational SwiftUI animations by separating animatable state from view composition. Useful for learning how implicit and explicit animation transactions propagate through a hierarchy.
- [RevenueCat](https://www.revenuecat.com/docs) — Article
  **NeKI brief:** RevenueCat's SDK documentation describes configuring products, purchases, entitlements, and customer subscription state in an app. Follow it when prototyping StoreKit-backed subscriptions, while checking platform versions, receipt behavior, and current App Store rules before shipping.

## [SwiftUI Weekly - Issue #162](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-162)

- Published: `2023-10-02T11:07:38.791Z`

**Topics:** Concurrency · Graphics, Media & Games · Persistence & Synchronisation · Swift · SwiftData · SwiftUI

**Sections:** Reading · Videos

**Selected links:**
- [RevenueCat](https://www.revenuecat.com/docs) — Article
  **NeKI brief:** RevenueCat's SDK documentation describes configuring products, purchases, entitlements, and customer subscription state in an app. Follow it when prototyping StoreKit-backed subscriptions, while checking platform versions, receipt behavior, and current App Store rules before shipping.

## [SwiftUI Weekly - Issue #161](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-161)

- Published: `2023-09-25T21:58:53.226Z`

**Topics:** App Intents & System Surfaces · Combine & Reactive Programming · Concurrency · Graphics, Media & Games · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #161 · Reading

**Selected links:**
- [How to use the new inspector SwiftUI view modifier](https://dimillian.medium.com/how-to-use-the-new-inspector-swiftui-view-modifier-9cefb8353beb) — Article · Topics: Swift · SwiftUI · Testing
  **NeKI brief:** Shows the SwiftUI inspector modifier for presenting supplemental controls alongside a view. Useful when adding platform-appropriate inspector panels while reasoning about visibility, content, and state-driven presentation.
- [App Intent driven development in Swift and SwiftUI](https://www.avanderlee.com/swift/app-intent-driven-development) — Article · Topics: App Intents & System Surfaces · Objective-C & Cocoa · Swift
  **NeKI brief:** Treats App Intents as a design input rather than an afterthought, modeling app actions and entities so Siri, Shortcuts, and Spotlight can invoke them. The examples connect intent definitions to SwiftUI app behavior and discoverability.
- [Understanding Publishers in SwiftUI and Combine](https://medium.com/bumble-tech/understanding-publishers-in-swiftui-and-combine-27806aa78ba1) — Article · Topics: Combine & Reactive Programming · Swift · SwiftUI
  **NeKI brief:** Explains how Combine publishers feed SwiftUI updates and how asynchronous streams compose in an application. Useful when diagnosing event pipelines, selecting operators, and deciding where publisher ownership belongs in a view model.
- [Combine](https://www.swiftbysundell.com/discover/combine) — Article · Topics: Combine & Reactive Programming · Swift · SwiftUI
  **NeKI brief:** Collects Swift by Sundell's Combine material on publishers, operators, and reactive application design. Useful as a navigation hub when maintaining Combine code or comparing legacy pipelines with newer async/await implementations.

## [SwiftUI Weekly - Issue #160](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-160)

- Published: `2023-09-18T12:26:01.319Z`

**Topics:** Apple Platform Ecosystem · Graphics, Media & Games · Hardware & Devices · Observation & State Management · Swift · SwiftUI

**Sections:** Reading · Videos

**NeKI brief:** Widget container backgrounds, macOS help menus, StateObject versus ObservedObject, and keyboard types address platform integration and ownership. The issue helps prevent model recreation while tuning input behavior across Apple platforms.

## [SwiftUI Weekly - Issue #159](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-159)

- Published: `2023-09-11T10:23:27.802Z`

**Topics:** Developer Community & Business · Graphics, Media & Games · Persistence & Synchronisation · Swift · SwiftData · SwiftUI

**Sections:** Reading · Videos

**Selected links:**
- [SwiftUI Sensory Feedback](https://useyourloaf.com/blog/swiftui-sensory-feedback) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Demonstrates SwiftUI sensory feedback and its trigger conditions for haptic responses. Useful for tying feedback to meaningful state transitions while respecting platform availability.

## [SwiftUI Weekly - Issue #158](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-158)

- Published: `2023-09-04T10:38:25.949Z`

**Topics:** App Distribution & Store Operations · Graphics, Media & Games · Macros & Metaprogramming · Objective-C & Cocoa · Swift · SwiftUI

**Sections:** Reading · Videos

**Selected links:**
- [Enabling drag reordering in SwiftUI lazy grids and stacks](https://danielsaidi.com/blog/2023/08/30/enabling-drag-reordering-in-swiftui-lazy-grids-and-stacks) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents a concrete implementation of Enabling drag reordering in SwiftUI lazy grids and stacks. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.
- [How To Visualize The Safe Area](https://chris.eidhof.nl/post/visualize-swiftui-safe-area) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows a visual technique for revealing SwiftUI safe-area boundaries and the effect of ignoring them. Use it when diagnosing why a view does or does not extend to screen edges.

## [SwiftUI Weekly - Issue #157](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-157)

- Published: `2023-08-28T11:14:18.626Z`

**Topics:** App Distribution & Store Operations · Graphics, Media & Games · macOS & AppKit · Maps & Location · Swift · SwiftUI

**Sections:** Reading · Videos

**NeKI brief:** StoreKit 2 SubscriptionStoreView, paginated Lists, MapKit integration, and iOS 17 ScrollView changes form a practical feature set. Research it when building subscription surfaces or large, map-backed collections with modern SwiftUI APIs.

## [SwiftUI Weekly - Issue #156](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-156)

- Published: `2023-08-21T19:48:52.195Z`

**Topics:** Graphics, Media & Games · Maps & Location · Objective-C & Cocoa · Observation & State Management · Swift · SwiftUI

**Sections:** Reading · Library · Videos

**Selected links:**
- [Building a searchable map with SwiftUI and MapKit](https://www.polpiella.dev/mapkit-and-swiftui-searchable-map) — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **NeKI brief:** Builds a searchable map component with MapKit and SwiftUI's iOS 17 APIs, connecting query results to map annotations. Useful for prototyping location search while evaluating state flow, selection, and map camera updates.

## [SwiftUI Weekly - Issue #155](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-155)

- Published: `2023-08-14T11:40:26.494Z`

**Topics:** App Distribution & Store Operations · Graphics, Media & Games · Persistence & Synchronisation · Swift · SwiftData · SwiftUI

**Sections:** Reading · Videos

**Selected links:**
- [Delightful SwiftUI image drag & drop for a macOS app](https://www.polpiella.dev/qreate-drag-and-drop) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Implements native image drag-and-drop for a macOS SwiftUI app, handling dropped data and integrating it into an editing workflow. Useful when designing desktop interactions that accept Finder assets without custom pasteboard plumbing.

## [SwiftUI Weekly - Issue #154](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-154)

- Published: `2023-08-08T03:29:42.397Z`

**Topics:** App Distribution & Store Operations · Graphics, Media & Games · Persistence & Synchronisation · Swift · SwiftData · SwiftUI

**Sections:** Reading · Videos

**Selected links:**
- [Applying metal shader to text in SwiftUI](https://augmentedcode.io/2023/08/07/applying-metal-shader-to-text-in-swiftui) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Applies a simple Metal shader to SwiftUI text using the shader-related view modifiers introduced with WWDC 2023. A compact first example for learning how ShaderLibrary effects connect SwiftUI views to custom Metal code.
- [MapKit for SwiftUI](https://useyourloaf.com/blog/mapkit-for-swiftui) — Article · Topics: Maps & Location · Swift · SwiftUI
  **NeKI brief:** Surveys the more SwiftUI-friendly MapKit API introduced in iOS 17, including map content and interaction configuration. Useful when replacing representable-based maps and checking which camera or annotation behaviors are now declarative.
- [ContentUnavailableView in SwiftUI](https://sarunw.com/posts/content-unavailable-view-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Introduces ContentUnavailableView for representing empty or unavailable states in SwiftUI on iOS 17. Useful for standardizing search, loading-failure, and no-content screens with system-consistent messaging and actions.

## [SwiftUI Weekly - Issue #153](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-153)

- Published: `2023-07-31T10:48:04.250Z`

**Topics:** Architecture · Composable Architecture · Objective-C & Cocoa · Persistence & Synchronisation · Swift · SwiftUI

**Sections:** Reading · Code · Videos

**Selected links:**
- [How to show the app icon and version in a SwiftUI view](https://www.polpiella.dev/show-app-icon-and-version-in-a-swiftui-view) — Article · Topics: Swift · SwiftUI · Testing
  **NeKI brief:** Shows how to display an app's icon and version metadata inside a SwiftUI view. Useful for About, diagnostics, and tester-facing screens that need to identify build variants without duplicating configuration values.
- [Composable Architecture 1.0](https://www.pointfree.co/blog/posts/112-composable-architecture-1-0) — Article · Topics: Architecture · Composable Architecture · Objective-C & Cocoa
  **NeKI brief:** Introduces the 1.0 Composable Architecture model of reducers, state, actions, dependencies, and effects. Useful as a reference for explicit unidirectional data flow and testable SwiftUI features.
- [Composable Architecture](https://github.com/pointfreeco/swift-composable-architecture) — Source repository · Topics: Architecture · Composable Architecture · Objective-C & Cocoa
  **NeKI brief:** The Composable Architecture structures feature state, actions, reducers, dependencies, and tests around explicit unidirectional flow. Use the repository and migration material to evaluate operational trade-offs before adopting or upgrading TCA in a production app.
- [SwiftData Saving Changes](https://useyourloaf.com/blog/swiftdata-saving-changes) — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** Explains when SwiftData persists model mutations and how explicit saves interact with the model context. Useful for avoiding assumptions about durability after background or lifecycle-driven updates.

## [SwiftUI Weekly - Issue #152](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-152)

- Published: `2023-07-24T10:52:41.199Z`

**Topics:** App Services & Extensions · Graphics, Media & Games · Navigation & Deep Linking · Swift · SwiftUI

**Sections:** Reading · Videos

**NeKI brief:** Swift Charts selection, push-notification options, NavigationStack hero animation, and a Thread-inspired interface connect data visualization with navigation. Use it to study selection state and animated transitions without coupling screens to imperative callbacks.

## [SwiftUI Weekly - Issue #151](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-151)

- Published: `2023-07-17T21:13:35.306Z`

**Topics:** Graphics, Media & Games · Observation & State Management · Persistence & Synchronisation · Swift · SwiftData · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #151 · Reading

**Selected links:**
- [The Ultimate Guide to Building SwiftData Applications](https://azamsharp.com/2023/07/04/the-ultimate-swift-data-guide.html) — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** Provides a broad SwiftData walkthrough covering model declaration, persistence, and cloud-sync-oriented concepts introduced at WWDC 2023. Useful for mapping Core Data requirements to SwiftData before committing to a migration or new model layer.
- [SwiftUI AlignmentGuides](https://www.youtube.com/watch?v=fdSGlCgz1fQ) — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Observation Framework in iOS 17](https://sarunw.com/posts/observation-framework-in-ios17) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Introduces the iOS 17 Observation framework and migration from ObservableObject. Useful for understanding macro-generated tracking, ownership, and the deployment constraints of the newer model.
- [Set a Preview Shape for Views Presenting Context Menus](https://www.swiftjectivec.com/snip-context-menu-preview-shape-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows using contentShape with the contextMenuPreview shape kind to customize a context menu preview. Useful for matching previews to rounded cards or irregular content instead of accepting the default rectangle.
- [SwiftUI onChange Deprecation](https://useyourloaf.com/blog/swiftui-onchange-deprecation) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains the newer onChange overloads and migration from deprecated signatures. Useful for making state-change handlers explicit about old and new values and avoiding accidental initial execution.

## [SwiftUI Weekly - Issue #150](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-150)

- Published: `2023-07-10T08:48:10.425Z`

**Topics:** Foundation & Data Formats · Graphics, Media & Games · Persistence & Synchronisation · Swift · SwiftData · SwiftUI

**Sections:** Reading · Code · Videos

**Selected links:**
- [Migrating to Observable](https://useyourloaf.com/blog/migrating-to-observable) — Article
  **NeKI brief:** Presents a focused migration from ObservableObject to the Observation framework's @Observable model. Useful for identifying property-wrapper and ownership changes in an incremental SwiftUI modernization.

## [SwiftUI Weekly - Issue #149](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-149)

- Published: `2023-07-03T15:07:33.765Z`

**Topics:** App Intents & System Surfaces · Graphics, Media & Games · Persistence & Synchronisation · Swift · SwiftData · SwiftUI

**Sections:** Reading · Videos

**Selected links:**
- [SwiftUI Data Flow 2023](https://troz.net/post/2023/swiftui-data-flow-2023) — Article · Topics: Developer Community & Business · Swift · SwiftUI
  **NeKI brief:** Presents a concrete implementation of SwiftUI Data Flow 2023. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.
- [Configuring SwiftData in a SwiftUI app](https://www.polpiella.dev/configuring-swiftdata-in-a-swiftui-app) — Article · Topics: Swift · SwiftData · SwiftUI
  **NeKI brief:** Walks through configuring SwiftData in a SwiftUI application, including container setup and model access. Useful for establishing persistence boundaries and avoiding accidental model-container creation in previews or tests.
- [Create an Interactive Widget Using App Intents](https://www.swiftjectivec.com/snip-create-a-basic-interactive-widget-using-app-intent-button) — Article · Topics: App Intents & System Surfaces · Swift
  **NeKI brief:** Discusses Create an Interactive Widget Using App Intents in a public developer resource. Use it to compare the author's concrete workflow and trade-offs with your project constraints, and verify any platform-specific claims against current primary documentation.

## [SwiftUI Weekly - Issue #148](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-148)

- Published: `2023-06-28T11:49:47.378Z`

**Topics:** Graphics, Media & Games · Macros & Metaprogramming · Observation & State Management · Persistence & Synchronisation · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #148 · Reading

**Selected links:**
- [#Preview SwiftUI Views using Macros](https://www.avanderlee.com/xcode/preview-swiftui-uikit-appkit-views) — Article · Topics: Macros & Metaprogramming · Swift · SwiftUI
  **NeKI brief:** Uses the #Preview macro to render SwiftUI, UIKit, and AppKit views, including wrapper setup for controller-based components. Useful for shortening visual feedback loops across mixed UI stacks.
- [Relationships In SwiftData](https://www.youtube.com/watch?v=_QMalUGTM4E&feature=youtu.be) — Video · Topics: Graphics, Media & Games · Swift · SwiftData
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Modifier Monday: .containerRelativeFrame(_ axes:)](https://www.swiftjectivec.com/swiftui-modifier-monday-container-relative-frame) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explores containerRelativeFrame and how it sizes views against a container's available dimensions. Useful for adaptive grids, carousels, and full-width content where fixed geometry would break across devices.
- [SwiftUI Data Flow in iOS 17 - Observation](https://www.youtube.com/watch?v=EK7SthdWV2w) — Video · Topics: Graphics, Media & Games · Macros & Metaprogramming · Observation & State Management
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.

## [SwiftUI Weekly - Issue #147](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-147)

- Published: `2023-06-19T09:19:07.103Z`

**Topics:** Graphics, Media & Games · Swift · SwiftUI

**Sections:** Reading · Videos

**Selected links:**
- [What’s new in SwiftUI for iOS 17](https://www.hackingwithswift.com/articles/260/whats-new-in-swiftui-for-ios-17) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Surveys SwiftUI additions in iOS 17 such as scroll effects, container-relative sizing, and Metal-backed rendering. Use it as historical release orientation, then verify current availability and behavior against Apple's documentation.
- [Interpolate text with custom foreground style in SwiftUI](https://nilcoalescing.com/blog/ForegroundStyleInsideTextInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows styling interpolated Text ranges with foregroundStyle in SwiftUI, enabling richer inline formatting from iOS 17. Useful for badges, emphasized fragments, and semantic text that needs multiple styles without overlaying separate labels.
- [SwiftUI Prefers Semantics](https://danielsaidi.com/blog/2023/06/15/swiftui-prefers-semantics) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows a semantic way to enable newer SwiftUI features while retaining clean code for older deployment targets. Useful when availability checks begin to leak through view code and the team needs an intentional compatibility boundary instead.

## [SwiftUI Weekly - Issue #146](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-146)

- Published: `2023-06-12T15:50:57.870Z`

**Topics:** Apple Platform Ecosystem · Core Data · Persistence & Synchronisation · Swift · SwiftData · SwiftUI

**Sections:** Reading · Videos

**Selected links:**
- [ContentUnavailableView: Handling Empty States in SwiftUI](https://www.avanderlee.com/swiftui/contentunavailableview-handling-empty-states) — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Introduces ContentUnavailableView for standard empty and error states, including custom labels and actions. Useful for consistent SwiftUI fallback screens that communicate why content is absent and what the user can do.
- [Inspectors in SwiftUI](https://nilcoalescing.com/blog/InspectorInSwiftUI) — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Uses SwiftUI's inspector presentation to expose contextual controls from a view. Useful for macOS and iPad interfaces where secondary configuration should remain discoverable without another navigation screen.

## [SwiftUI Weekly - Issue #145](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-145)

- Published: `2023-06-05T08:35:48.243Z`

**Topics:** App Distribution & Store Operations · Foundation & Data Formats · Graphics, Media & Games · Objective-C & Cocoa · Swift · SwiftUI

**Sections:** Reading · Videos

**Selected links:**
- [What’s new in Swift 5.9?](https://www.hackingwithswift.com/articles/258/whats-new-in-swift-5-9) — Article · Topics: Concurrency · Macros & Metaprogramming · Swift
  **NeKI brief:** Summarizes Swift 5.9 features including macros and parameter packs with migration context. Useful as a language-version index before adopting individual syntax in production code.
- [Using compositing group for unifying shapes within buttons in SwiftUI](https://nilcoalescing.com/blog/CompositingGroupInButtons) — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa · Swift
  **NeKI brief:** Explains how compositingGroup changes rendering and hit behavior in styled SwiftUI buttons. Useful when effects, masks, and backgrounds produce unexpected visual or interaction results.
- [Glassfy](https://eu1.hubs.ly/H01-5vC0) — Article
  **NeKI brief:** Links to Glassfy's service for managing in-app purchases, paywalls, and backend subscription work. Useful as a product integration lead when comparing hosted monetization infrastructure, SDK coverage, and vendor dependency against StoreKit-first designs.

## [SwiftUI Weekly - Issue #144](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-144)

- Published: `2023-05-29T23:10:25.571Z`

**Topics:** App Distribution & Store Operations · Cross-Platform & Web · Developer Career & Practice · Graphics, Media & Games · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #144 · Reading

**Selected links:**
- [Glassfy](https://eu1.hubs.ly/H01-5vC0) — Article · Topics: App Distribution & Store Operations · Developer Career & Practice · Swift
  **NeKI brief:** Links to Glassfy's service for managing in-app purchases, paywalls, and backend subscription work. Useful as a product integration lead when comparing hosted monetization infrastructure, SDK coverage, and vendor dependency against StoreKit-first designs.
- [Exploring Circular Paths: How to Create a Circular Text View in SwiftUI](https://holyswift.app/how-to-create-an-circular-text-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a circular text view by placing and transforming individual characters along a curved path. Useful for badges, dial-like controls, and decorative labels where standard text layout cannot follow custom geometry.
- [Creating Forms in SwiftUI](https://serialcoder.dev/creating-forms-in-swiftui) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Explains composing SwiftUI Form containers with input controls and platform-appropriate styling. Useful for settings and data-entry screens that need grouped controls while retaining native behavior across iOS and related platforms.
- [Ratings view in SwiftUI](https://augmentedcode.io/2023/05/29/ratings-view-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Implements a half-step ratings view with SF Symbols for values from zero to five. Useful for reusable rating displays where fractional values, accessibility labels, and symbol configuration must stay synchronized.

## [SwiftUI Weekly - Issue #143](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-143)

- Published: `2023-05-22T15:14:28.541Z`

**Topics:** Apple Platform Ecosystem · Core Data · Graphics, Media & Games · macOS & AppKit · Swift · SwiftUI

**Sections:** Reading · Videos

**Selected links:**
- [Using Layout protocol to align explicitly positioned views in SwiftUI](https://nilcoalescing.com/blog/AnchoredPositionInSwiftUI) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates anchored positioning for placing SwiftUI content relative to a point or anchor. Useful for overlays and callouts that should follow layout geometry without manual offsets.
- [Glassfy](https://eu1.hubs.ly/H01-5vC0) — Article
  **NeKI brief:** Links to Glassfy's service for managing in-app purchases, paywalls, and backend subscription work. Useful as a product integration lead when comparing hosted monetization infrastructure, SDK coverage, and vendor dependency against StoreKit-first designs.

## [SwiftUI Weekly - Issue #142](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-142)

- Published: `2023-05-15T09:13:45.627Z`

**Topics:** Developer Career & Practice · Graphics, Media & Games · Product Design · Swift · SwiftUI · UIKit

**Sections:** Reading · Video

**Selected links:**
- [How to implement a UIViewController delegate when working with SwiftUI](https://tanaschita.com/20230508-coordinators-in-swiftui) — Article · Topics: Navigation & Deep Linking · Swift · SwiftUI
  **NeKI brief:** Demonstrates UIViewControllerRepresentable.Coordinator forwarding UIKit delegate callbacks into SwiftUI state. Useful when wrapping delegate-driven controllers such as scanners or pickers while keeping the bridge's lifecycle and data flow explicit.
- [SwiftUI Showcase View - Highlight App New Features](https://www.youtube.com/watch?v=I9v-zqrE8gI) — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Create a color pencil in SwiftUI](https://swdevnotes.com/swift/2023/create-a-color-pencil-in-swiftui) — Article · Topics: Product Design · Swift · SwiftUI
  **NeKI brief:** Creates a color-pencil control in SwiftUI to make color selection feel tangible rather than presenting only a plain rectangle. Useful for drawing and note-taking interfaces where custom visuals communicate selection state.
- [Window Management with SwiftUI 4](https://www.fline.dev/window-management-on-macos-with-swiftui-4) — Article · Topics: Developer Career & Practice · Swift · SwiftUI
  **NeKI brief:** Explains macOS SwiftUI window management with openWindow and windowResizability while modernizing an existing app. Useful for multi-window designs that need explicit opening, sizing, and lifecycle behavior.
- [Glassfy](https://eu1.hubs.ly/H01-5vC0) — Article
  **NeKI brief:** Links to Glassfy's service for managing in-app purchases, paywalls, and backend subscription work. Useful as a product integration lead when comparing hosted monetization infrastructure, SDK coverage, and vendor dependency against StoreKit-first designs.

## [SwiftUI Weekly - Issue #141](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-141)

- Published: `2023-05-10T09:39:15.692Z`

**Topics:** Graphics, Media & Games · macOS & AppKit · Swift · SwiftUI · Xcode

**Sections:** Reading · Video

**Selected links:**
- [Export SwiftUI views as images in macOS](https://www.polpiella.dev/how-to-save-swiftui-views-as-images-in-macos) — Article · Topics: macOS & AppKit · Swift · SwiftUI
  **NeKI brief:** Shows exporting SwiftUI views as images on macOS, using a QR-code editing workflow as the concrete case. Useful for implementing reliable snapshot export while separating rendering configuration from file-writing concerns.

## [SwiftUI Weekly - Issue #140](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-140)

- Published: `2023-04-25T07:37:25.660Z`

**Topics:** Developer Community & Business · Navigation & Deep Linking · Observation & State Management · Personal Essays · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #140 · Reading

**Selected links:**
- [How to initialize @Binding in SwiftUI](https://sarunw.com/posts/binding-initialization) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Clarifies initializing SwiftUI views that accept Binding values and the distinction between a binding and its wrapped value. Useful for avoiding underscore-storage mistakes in custom view initializers.
- [SwiftUI Multiplatform Navigation Example](https://github.com/tunds/SwiftUI-Navigation-Multiplatform-Example) — Source repository · Topics: Developer Community & Business · Swift · SwiftUI
  **NeKI brief:** Provides a working SwiftUI navigation project across Apple platforms, showing route composition and platform adaptations. Useful as a concrete reference when designing a shared navigation model that still respects platform-specific presentation behavior.
- [course](https://youtube.com/playlist?list=PLvUWi5tdh92wWS3F-AVsCJHkhBlrkBp6f) — Video · Topics: Developer Community & Business · Navigation & Deep Linking · Swift
  **NeKI brief:** Provides a SwiftUI learning course playlist covering navigation and related interface patterns. Use it as a structured route through implementations, checking each example against current APIs before adopting its presentation or state-management techniques.
- [Speedrun Design: Heart Rate Zone View in SwiftUI](https://www.david-smith.org/blog/2023/04/24/design-notes-35) — Article · Topics: Graphics, Media & Games · Personal Essays · Swift
  **NeKI brief:** Builds a SwiftUI heart-rate-zone view as a compact design exercise, exposing the visual decisions behind a data-driven display. It is useful for studying how a constrained, real-world metric can become a readable custom SwiftUI component.
- [Discover how @MainActor works](https://www.swiftwithvincent.com/blog/discover-how-main-actor-works-in-swift) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains MainActor isolation, executor scheduling, and why UI-facing Swift code belongs on the main actor. Useful when reviewing async SwiftUI code for accidental data races, unnecessary hops, or blocked responsiveness.

## [SwiftUI Weekly - Issue #139](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-139)

- Published: `2023-04-17T14:01:12.627Z`

**Topics:** Concurrency · Graphics, Media & Games · Swift · SwiftUI · Xcode

**Sections:** Reading · Videos

**Selected links:**
- [SwiftUI Form Styling](https://sarunw.com/posts/swiftui-form-styling) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows how SwiftUI Form styling follows the platform’s List behavior: use tint and foregroundColor for controls, hide the scroll background before applying a custom color, and put listRowBackground on sections or row content rather than the Form itself.

## [SwiftUI Weekly - Issue #138](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-138)

- Published: `2023-04-10T11:18:51.019Z`

**Topics:** App Services & Extensions · Graphics, Media & Games · macOS & AppKit · Navigation & Deep Linking · Swift · SwiftUI

**Sections:** Reading · Videos

**Selected links:**
- [When Matched Geometry Effect Doesn't Work](https://chris.eidhof.nl/post/matched-geometry-effect) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Investigates a SwiftUI matched-geometry transition that behaves unexpectedly and traces the result to declaration order. It is useful when building a mental model for matchedGeometryEffect and diagnosing apparently incorrect animations.

## [SwiftUI Weekly - Issue #137](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-137)

- Published: `2023-04-03T19:16:33.994Z`

**Topics:** Architecture · Concurrency · Graphics, Media & Games · Navigation & Deep Linking · Swift · SwiftUI

**Sections:** News · Reading · Videos

**Selected links:**
- [Swift 5.8 Released!](https://www.swift.org/blog/swift-5.8-released) — Article · Topics: Swift
  **NeKI brief:** Presents a concrete implementation of Swift 5.8 Released!. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.

## [SwiftUI Weekly - Issue #136](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-136)

- Published: `2023-03-27T21:57:02.938Z`

**Topics:** AI Development · Graphics, Media & Games · Navigation & Deep Linking · Swift · SwiftUI · Xcode

**Sections:** Reading · Videos

**Selected links:**
- [Can ChatGPT write better SwiftUI code than you?](https://www.youtube.com/watch?v=dxxCPdcMcFw) — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Using foregroundColor(), foregroundStyle() or tint() to set text color in SwiftUI](https://nilcoalescing.com/blog/ForegroundColorStyleAndTintInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Compares SwiftUI's `foregroundStyle`, `foregroundColor`, `tint`, AttributedString attributes, and text-rendering options. Use it when choosing between semantic hierarchy, control accenting, gradients, and advanced per-run text styling.

## [SwiftUI Weekly - Issue #135 · 2023-03-20](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-135-a39)

- Published: `2023-03-20T11:38:06.573Z`

**Topics:** Graphics, Media & Games · Localization · Persistence & Synchronisation · Swift · SwiftUI

**Sections:** Reading · Videos

**Selected links:**
- [Handling status bar color scheme and visibility in SwiftUI](https://danielsaidi.com/blog/2023/03/14/handling-status-bar-color-scheme-and-visibility-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents a concrete implementation of Handling status bar color scheme and visibility in SwiftUI. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.

## [SwiftUI Weekly - Issue #135 · 2023-03-13](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-135)

- Published: `2023-03-13T10:48:39.427Z`

**Topics:** Concurrency · Graphics, Media & Games · macOS & AppKit · Networking · Swift · SwiftUI

**Sections:** Reading · Videos

**Selected links:**
- [SwiftUI Tables Quick Guide](https://useyourloaf.com/blog/swiftui-tables-quick-guide) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** A practical Table guide covering Identifiable rows, column key paths, single or multiple selection, and KeyPathComparator sorting. It also flags platform caveats: tables suit macOS and iPadOS, while compact iPhone layouts collapse toward a list.
- [What's new in Swift 5.8](https://www.hackingwithswift.com/articles/256/whats-new-in-swift-5-8) — Article · Topics: Swift
  **NeKI brief:** Surveys Swift 5.8 language and tooling changes, including macros groundwork and compiler behavior. Follow it as historical migration context when maintaining packages across Swift 5.x toolchains.

## [SwiftUI Weekly - Issue #134](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-134)

- Published: `2023-03-06T15:27:12.172Z`

**Topics:** Accessibility · Architecture · Objective-C & Cocoa · Swift · SwiftUI · UIKit

**Sections:** Reading · Videos

**Selected links:**
- [The difference between List and LazyVStack](https://dimillian.medium.com/swiftui-the-difference-between-list-and-lazyvstack-3d5eeaccb156) — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **NeKI brief:** Compares List with LazyVStack through the rendering, scrolling, and interaction behaviour that makes them different despite similar output. Follow it before replacing one with the other in a performance-sensitive screen or a layout needing list-specific capabilities.
- [SwiftUI's .task modifier](https://alexanderweiss.dev/blog/2023-03-05-swiftui-task-modifier) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents a concrete implementation of SwiftUI's .task modifier. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.

## [SwiftUI Weekly - Issue #133](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-133)

- Published: `2023-03-01T21:30:35.589Z`

**Topics:** App Distribution & Store Operations · Graphics, Media & Games · Swift · SwiftUI · UIKit

**Sections:** Reading · Videos

**Selected links:**
- [SwiftUI views versus modifiers](https://www.swiftbysundell.com/articles/swiftui-views-versus-modifiers) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Compares extracting SwiftUI behavior as a View versus a ViewModifier. Both can structure, style, and own state; the useful deciding question is conceptual hierarchy—use modifiers when the change is styling, not a new structural component.
- [Arbitrary SwiftUI Linear Gradient Rotation](https://www.david-smith.org/blog/2023/02/22/design-notes-24) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Works through rotating a SwiftUI linear gradient at arbitrary angles without relying on an oversized rotated layer. It is a focused rendering technique for gradients that need predictable geometry, smooth animation, and less accidental clipping.

## [SwiftUI Weekly - Issue #132](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-132)

- Published: `2023-02-21T07:37:59.536Z`

**Topics:** App Distribution & Store Operations · App Services & Extensions · Graphics, Media & Games · Hardware & Devices · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #132 · Reading

**Selected links:**
- [Build for free today](https://eu1.hubs.ly/H01-5vC0) — Article · Topics: App Distribution & Store Operations · Swift · SwiftUI
  **NeKI brief:** Links to Glassfy's service for managing in-app purchases, paywalls, and backend subscription work. Useful as a product integration lead when comparing hosted monetization infrastructure, SDK coverage, and vendor dependency against StoreKit-first designs.
- [Arc Coding Chronicles](https://www.youtube.com/watch?v=94asyypYj5c) — Video · Topics: Graphics, Media & Games · Objective-C & Cocoa · Swift
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Reading keyboard modifiers on iPad in SwiftUI](https://nilcoalescing.com/blog/ReadingKeyboardModifiers) — Article · Topics: Hardware & Devices · Product Design · Swift
  **NeKI brief:** Reads keyboard modifier flags in SwiftUI commands and gestures. Useful for macOS and iPad keyboard workflows where the same action changes with Command, Option, Shift, or Control.
- [What's new in Xcode 14.3 and iOS 16.4](https://sarunw.com/posts/whats-new-in-xcode-14_3-and-ios-16_4) — Article · Topics: Xcode
  **NeKI brief:** Summarizes Xcode 14.3 and iOS 16.4 changes relevant to SwiftUI development. Useful as a versioned route into SDK additions and toolchain behavior when maintaining older deployment targets.
- [The making of Ice Cubes, an open source, SwiftUI Mastodon client.](https://dimillian.medium.com/the-making-of-ice-cubes-an-open-source-swiftui-mastodon-client-45ebea5cf6b6) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents a concrete implementation of The making of Ice Cubes, an open source, SwiftUI Mastodon client. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.

## [SwiftUI Weekly - Issue #131](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-131)

- Published: `2023-02-14T07:17:12.491Z`

**Topics:** Combine & Reactive Programming · Graphics, Media & Games · Swift · SwiftUI

**Sections:** Reading · Videos

**Selected links:**
- [SwiftUI Environment Tips](https://chris.eidhof.nl/post/swiftui-environment-tips) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI environment design with attention to precise dependency tracking and avoiding unnecessary updates. Use it when passing shared styles or configuration through a view tree.
- [Timer in SwiftUI](https://sarunw.com/posts/timer-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains periodic SwiftUI work with Timer.publish and onReceive, including main-run-loop scheduling and autoconnect. Cancellation stops the upstream connection; resuming requires recreating the published timer, typically by storing it in State.
- [Build for free today](https://eu1.hubs.ly/H01-5vC0) — Article
  **NeKI brief:** Links to Glassfy's service for managing in-app purchases, paywalls, and backend subscription work. Useful as a product integration lead when comparing hosted monetization infrastructure, SDK coverage, and vendor dependency against StoreKit-first designs.

## [SwiftUI Weekly - Issue #130](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-130)

- Published: `2023-02-06T21:14:10.165Z`

**Topics:** App Distribution & Store Operations · Graphics, Media & Games · Swift · SwiftUI · UIKit

**Sections:** Reading · Videos

**Selected links:**
- [Styling Components in SwiftUI](https://movingparts.io/styling-components-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents a concrete implementation of Styling Components in SwiftUI. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.
- [Observing the content offset of a SwiftUI ScrollView](https://www.swiftbysundell.com/articles/observing-swiftui-scrollview-content-offset) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows observing a SwiftUI ScrollView's content offset through preference propagation. Use it when implementing sticky headers, scroll-aware effects, or analytics without replacing ScrollView with a custom UIKit bridge.
- [Tracking hover location in SwiftUI](https://nilcoalescing.com/blog/TrackingHoverLocationInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates continuous pointer tracking with onContinuousHover on macOS 13 and iPadOS 16. Store the active HoverPhase location in State, then use the coordinates for hover-driven drawing, effects, or custom interaction within the view’s bounds.
- [Changing orientation for a single screen in SwiftUI](https://www.polpiella.dev/changing-orientation-for-a-single-screen-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents a per-screen orientation approach for SwiftUI that bridges into UIKit, changing the supported interface orientations while a particular screen is active and restoring the app-wide policy afterward. Useful for flows such as media or camera interfaces.
- [Build for free today](https://eu1.hubs.ly/H01-5vC0) — Article
  **NeKI brief:** Links to Glassfy's service for managing in-app purchases, paywalls, and backend subscription work. Useful as a product integration lead when comparing hosted monetization infrastructure, SDK coverage, and vendor dependency against StoreKit-first designs.

## [SwiftUI Weekly - Issue #129](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-129)

- Published: `2023-01-30T11:20:24.661Z`

**Topics:** App Distribution & Store Operations · Graphics, Media & Games · Objective-C & Cocoa · Observation & State Management · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #129 · Reading

**Selected links:**
- [Build for free today](https://eu1.hubs.ly/H01-5vC0) — Article · Topics: App Distribution & Store Operations · Swift · SwiftUI
  **NeKI brief:** Links to Glassfy's service for managing in-app purchases, paywalls, and backend subscription work. Useful as a product integration lead when comparing hosted monetization infrastructure, SDK coverage, and vendor dependency against StoreKit-first designs.
- [30,000 lines of SwiftUI in production later: We love it but you know there was going to be a “but”](https://blog.timing.is/swiftui-production-experience-problems-solutions-performance-tips) — Article · Topics: App Distribution & Store Operations · Swift · SwiftUI
  **NeKI brief:** Reports production SwiftUI performance problems and the remedies used to diagnose them. Useful as a field-tested checklist for investigating rendering cost, navigation behavior, and architectural friction beyond small sample projects.
- [Container Pattern in SwiftUI](https://azamsharp.com/2023/01/24/introduction-to-container-pattern.html) — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **NeKI brief:** Introduces the SwiftUI container pattern for separating screen composition from data-loading and coordination responsibilities. Useful when extracting feature-level dependencies without turning view bodies into implicit service locators.
- [Modern SwiftUI](https://www.pointfree.co/blog/posts/99-modern-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents a modern SwiftUI architecture built around state, bindings, and composition rather than imperative view controllers. Useful as a conceptual reference when simplifying older SwiftUI code.
- [The Nested Observables Problem in SwiftUI](https://holyswift.app/how-to-solve-observable-object-problem) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines why changes inside nested observable objects may not refresh a SwiftUI view as expected. Useful when a state graph appears correct but updates stop propagating, and you need to choose ownership, forwarding, or a newer observation model deliberately.
- [Variadic Views](https://chris.eidhof.nl/post/variadic-views) — Article
  **NeKI brief:** Explores SwiftUI's variadic view behavior and later relates the investigation to officially supported APIs. Use it for conceptual understanding of containers that operate on view lists, while checking current SDK availability.

## [SwiftUI Weekly - Issue #128](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-128)

- Published: `2023-01-23T19:36:17.730Z`

**Topics:** Apple Platform Ecosystem · Cross-Platform & Web · Graphics, Media & Games · Swift · Swift Package Manager · SwiftUI

**Sections:** Reading · Videos

**Selected links:**
- [How to use SwiftUI in Storyboard using UIHostingController subclass](https://sarunw.com/posts/swiftui-view-in-uikit-using-uihostingcontroller-subclass) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Shows a custom UIHostingController subclass for placing SwiftUI in storyboard positions where IBSegueAction is unavailable, such as an initial controller, navigation root, or tab. The subclass fixes its generic root view and implements init(coder:).
- [Swift Package String Localization](https://useyourloaf.com/blog/swift-package-string-localization) — Article · Topics: Localization · Swift · Swift Package Manager
  **NeKI brief:** Recaps Swift Package localization requirements: use Swift tools 5.3 or newer, declare defaultLocalization, add each language’s .lproj resources under the target, and load keys from Bundle.module. Mixed app/package locales may require CFBundleAllowMixedLocalizations.
- [Modern SwiftUI: Parent-child communication](https://www.pointfree.co/blog/posts/94-modern-swiftui-parent-child-communication) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Modernizes parent-child SwiftUI communication with event-named delegate closures, then extends the pattern to ObservableObject models. Point-Free’s unimplemented closures preserve ergonomic initialization while producing loud runtime warnings or test failures when a parent forgets binding.
- [Customize ShareLink appearance with view modifiers](https://nilcoalescing.com/blog/CustomizeShareLinkAppearance) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates customizing ShareLink appearance while preserving the system sharing action. Follow it when adapting labels, icons, or styling without reimplementing share-sheet presentation and its platform behavior.

## [SwiftUI Weekly - Issue #127](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-127)

- Published: `2023-01-16T08:00:00.000Z`

**Topics:** Architecture · Graphics, Media & Games · Objective-C & Cocoa · Swift · SwiftUI · UIKit

**Sections:** Reading · Video

**Selected links:**
- [How to Hide Navigation bar in SwiftUI](https://sarunw.com/posts/hide-navigation-bar-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains hiding SwiftUI navigation bars per destination. Older code uses navigationBarHidden; iOS 16 replaces it with toolbar(.hidden, for: .navigationBar). The modifier belongs on the content view, and pushed destinations need their own policy.
- [Understanding basic animations in SwiftUI](https://tanaschita.com/20230116-animations-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents a concrete implementation of Understanding basic animations in SwiftUI. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.
- [Text modifiers in SwiftUI](https://nilcoalescing.com/blog/TextModifiersInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains composing text modifiers in SwiftUI and how modifier order affects rendered output. Use it when styling, accessibility, and localization concerns interact in a Text view and visual results seem surprising.

## [SwiftUI Weekly - Issue #126](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-126)

- Published: `2022-12-26T08:42:03.000Z`

**Topics:** Concurrency · Cross-Platform & Web · Graphics, Media & Games · Observation & State Management · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #126 · Reading

**Selected links:**
- [Efficiently Managing Multiple Async Tasks in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2hvbHlzd2lmdC5hcHAvZWZmaWNpZW50bHktbWFuYWdpbmctbXVsdGlwbGUtYXN5bmMtdGFza3MtaW4tc3dpZnR1aS8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiJjZmM5ZTE2MC02YWY1LTRlMWUtOGI1OS0zZGNmZmRkNTVhYmQiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiMDU5Zjc1ZDEtOGJlYy00ZGY3LWEwMzAtMjQ1NTIzYWE3Y2I1IiwiaWF0IjoxNjc0MDYyNTU2LjgyMSwiaXNzIjoib3JjaGlkIn0.HZzGOwzhoPo69a-J0S_8WKXHvIGOrH2bNN_LiZNPSQY) — Article · Topics: Concurrency · Swift · SwiftUI
  **NeKI brief:** Explores coordinating multiple asynchronous operations from a SwiftUI view, including task lifetime and result handling. Useful for dashboards or detail screens that must combine independent loads while respecting cancellation and view identity.
- [Previewing Stateful SwiftUI Views](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3BldGVyZnJpZXNlLmRldi9wb3N0cy9zd2lmdHVpLXByZXZpZXdzLWludGVyYWN0aXZlLz91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6ImNmYzllMTYwLTZhZjUtNGUxZS04YjU5LTNkY2ZmZGQ1NWFiZCIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiIwNTlmNzVkMS04YmVjLTRkZjctYTAzMC0yNDU1MjNhYTdjYjUiLCJpYXQiOjE2NzQwNjI1NTYuODIxLCJpc3MiOiJvcmNoaWQifQ.6TcnO7G482yXKeKCJPrYsiBFjJuIRDG-2UQm2zpi1aA) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Shows interactive SwiftUI previews with mutable state and realistic user flows. Useful for exercising editing, selection, and navigation behavior in preview-driven development before writing a full UI test.
- [How to change SwiftUI Button Size](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3NhcnVudy5jb20vcG9zdHMvc3dpZnR1aS1idXR0b24tc2l6ZS8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiJjZmM5ZTE2MC02YWY1LTRlMWUtOGI1OS0zZGNmZmRkNTVhYmQiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiMDU5Zjc1ZDEtOGJlYy00ZGY3LWEwMzAtMjQ1NTIzYWE3Y2I1IiwiaWF0IjoxNjc0MDYyNTU2LjgyMSwiaXNzIjoib3JjaGlkIn0.KG-o2QTt9nJ6oOZfi5U1rzqI3hFdw3vrr1eim6rJHS8) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Controls SwiftUI button sizing through labels, frames, and styles, clarifying which layer should own hit-target expansion versus visual dimensions.
- [Spot the differences, merge in seconds](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2thbGVpZG9zY29wZS5hcHAvP3V0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiY2ZjOWUxNjAtNmFmNS00ZTFlLThiNTktM2RjZmZkZDU1YWJkIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6IjA1OWY3NWQxLThiZWMtNGRmNy1hMDMwLTI0NTUyM2FhN2NiNSIsImlhdCI6MTY3NDA2MjU1Ni44MjEsImlzcyI6Im9yY2hpZCJ9.S7BcU-pcGYFSQyo6yYRrC_9wF3kwo5_D-bQzQz_0ae8) — Article · Topics: Product Design · Swift · SwiftUI
  **NeKI brief:** Presents Kaleidoscope, a visual diff and merge application for comparing files and folders. It is useful when reviewing SwiftUI snapshot changes or generated project assets, making unintended visual or textual regressions easier to isolate.

## [SwiftUI Weekly - Issue #125](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-125)

- Published: `2022-12-20T12:22:54.000Z`

**Topics:** Developer Tools · Graphics, Media & Games · Navigation & Deep Linking · Swift · SwiftUI · Testing

**Sections:** Reading · Building custom layout in SwiftUI. LayoutValueKey. · Understanding SwiftUI view lifecycles

**NeKI brief:** LayoutValueKey custom layouts and the accompanying SwiftUI design experiments show how child measurements become container metadata. Follow this issue when building reusable layouts that need explicit spacing or per-subview values rather than GeometryReader workarounds.

## [SwiftUI Weekly - Issue #124](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-124)

- Published: `2022-12-12T12:49:34.000Z`

**Topics:** AI Development · Developer Tools · Graphics, Media & Games · Swift · SwiftUI · Testing

**Sections:** Reading · Building custom layout in SwiftUI. Spacing. · How to use FormatStyle to restrict TextField input in SwiftUI

**NeKI brief:** Custom layout spacing and LayoutValueKey techniques explain how SwiftUI containers negotiate geometry. It is useful for implementing adaptive flow components while keeping spacing rules local, testable, and independent of device-specific frame constants.

## [SwiftUI Weekly - Issue #123](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-123)

- Published: `2022-12-04T21:25:23.000Z`

**Topics:** AI Development · App Distribution & Store Operations · Graphics, Media & Games · Navigation & Deep Linking · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #123 · Reading

**Selected links:**
- [Prototyping SwiftUI interfaces with OpenAI's ChatGPT](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy5jcmVhdGV3aXRoc3dpZnQuY29tL3Byb3RvdHlwaW5nLXN3aWZ0dWktaW50ZXJmYWNlcy13aXRoLW9wZW5haXMtY2hhdGdwdC8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiJkNTBhNTkyYy02YjBmLTQ4ZDQtODhhMS1jNjE1ZGE1NmVhMjQiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiZTVkY2QxZmUtNjFmMC00YzNkLTk4MGYtODFhNTRiZTczYzk1IiwiaWF0IjoxNjc0MDYyNTU2Ljg4NiwiaXNzIjoib3JjaGlkIn0.--3_tX3nFerJI79NxG55TYekWMImzuRNPY5f2bXzyAs) — Article · Topics: AI Development · Swift · SwiftUI
  **NeKI brief:** Demonstrates using conversational prompts to scaffold SwiftUI code, making the gap between an idea and a runnable prototype smaller. Follow it to assess where generated UI accelerates exploration and where compile-time review remains essential.
- [Building custom layout in SwiftUI. Caching.](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3N3aWZ0d2l0aG1hamlkLmNvbS8yMDIyLzExLzI5L2J1aWxkaW5nLWN1c3RvbS1sYXlvdXQtaW4tc3dpZnR1aS1jYWNoaW5nLz91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6ImQ1MGE1OTJjLTZiMGYtNDhkNC04OGExLWM2MTVkYTU2ZWEyNCIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiJlNWRjZDFmZS02MWYwLTRjM2QtOTgwZi04MWE1NGJlNzNjOTUiLCJpYXQiOjE2NzQwNjI1NTYuODg2LCJpc3MiOiJvcmNoaWQifQ.Sm2-BiOuDVBNJxvvi5PdhGr0xLSaf8fO1X82Fpvwfpg) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains caching measurements in a custom SwiftUI Layout to avoid repeated expensive calculations. Follow it when layout performance suffers and cached proposal-dependent results can safely be invalidated.
- [Animated Background in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2hvbHlzd2lmdC5hcHAvYW5pbWF0ZWQtYmFja2dyb3VuZC1pbi1zd2lmdHVpLz91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6ImQ1MGE1OTJjLTZiMGYtNDhkNC04OGExLWM2MTVkYTU2ZWEyNCIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiJlNWRjZDFmZS02MWYwLTRjM2QtOTgwZi04MWE1NGJlNzNjOTUiLCJpYXQiOjE2NzQwNjI1NTYuODg2LCJpc3MiOiJvcmNoaWQifQ.jXv-RMjHBVfLeAy0Tf_eCGJq3V7NzVLrlEh2YK_dgcs) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Builds an animated SwiftUI background from layered shapes and timed state changes. Useful for ambient loading or decorative surfaces while evaluating redraw cost and reduced-motion behavior.
- [Sheets in SwiftUI explained with code examples](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy5hdmFuZGVybGVlLmNvbS9zd2lmdHVpL3ByZXNlbnRpbmctc2hlZXRzLz91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6ImQ1MGE1OTJjLTZiMGYtNDhkNC04OGExLWM2MTVkYTU2ZWEyNCIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiJlNWRjZDFmZS02MWYwLTRjM2QtOTgwZi04MWE1NGJlNzNjOTUiLCJpYXQiOjE2NzQwNjI1NTYuODg2LCJpc3MiOiJvcmNoaWQifQ.P8cA3a2DFN3gNEcPbhHTCkO6brg9lXovpc8-yN-2HxA) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Compares sheet presentation driven by Boolean and identifiable item state, including dismissal and nested content. Useful for avoiding stale modal data and making SwiftUI presentation follow model state.

## [SwiftUI Weekly - Issue #122](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-122)

- Published: `2022-11-27T23:36:34.000Z`

**Topics:** App Distribution & Store Operations · Graphics, Media & Games · Swift · SwiftUI · Testing · Xcode

**Sections:** Reading · Swift Charts Tutorial: Getting Started · Sized-to-fit SwiftUI bottom sheet

**NeKI brief:** Swift Charts fundamentals and sized-to-fit bottom sheets cover data presentation and adaptive modal height. Research it when chart marks need clear model mapping and sheets should avoid fixed detents for compact content.

## [SwiftUI Weekly - Issue #121](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-121)

- Published: `2022-11-21T12:42:39.000Z`

**Topics:** App Distribution & Store Operations · Combine & Reactive Programming · Graphics, Media & Games · Observation & State Management · Swift · SwiftUI

**Sections:** Reading · Building custom layout in SwiftUI. Basics. · A Guided Tour for SwiftUI ForEach Structure

**Selected links:**
- [Composition in TCA: Scope, Combine and Pullback operators](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyJnY9WmYycEZFYTN1ZXciLCJwb3N0X2lkIjoiNTAxNjg3MDctMTllNi00OWVjLWEzMGUtZDM0NTg5OGM5Mzk5IiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6ImJkOTY3MzY1LTVhYTAtNGIzOS05NWY0LTJhMGViNjgwNTJhMyIsImlhdCI6MTY3NDA2MjU1Ni45LCJpc3MiOiJvcmNoaWQifQ.oCLiQ-6M7I0rhyM9-07MqJd2m-21FbRxpLCYhEXIV-0) — Article · Topics: Architecture · Combine & Reactive Programming · Composable Architecture
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [‎Empower Apps: Behind the Scenes of SwiftUI.](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3BvZGNhc3RzLmFwcGxlLmNvbS91cy9wb2RjYXN0L2lkMTQzNzQzNTM5Mj9pPTEwMDA1ODUzMzUxNDcmdXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiI1MDE2ODcwNy0xOWU2LTQ5ZWMtYTMwZS1kMzQ1ODk4YzkzOTkiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiYmQ5NjczNjUtNWFhMC00YjM5LTk1ZjQtMmEwZWI2ODA1MmEzIiwiaWF0IjoxNjc0MDYyNTU2LjksImlzcyI6Im9yY2hpZCJ9.mFD5gTgP8ji8ehZv_6noqd5XdLWSwtu0pJF0pBQfYas) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Features an Empower Apps episode about the engineering decisions behind a SwiftUI application. Use the production discussion to question architecture, performance, and platform trade-offs rather than treating a showcased implementation as a drop-in recipe.
- [Building custom layout in SwiftUI. Basics.](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3N3aWZ0d2l0aG1hamlkLmNvbS8yMDIyLzExLzE2L2J1aWxkaW5nLWN1c3RvbS1sYXlvdXQtaW4tc3dpZnR1aS1iYXNpY3MvP3V0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiNTAxNjg3MDctMTllNi00OWVjLWEzMGUtZDM0NTg5OGM5Mzk5IiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6ImJkOTY3MzY1LTVhYTAtNGIzOS05NWY0LTJhMGViNjgwNTJhMyIsImlhdCI6MTY3NDA2MjU1Ni45LCJpc3MiOiJvcmNoaWQifQ.oBDsU5Ohkkmf0XCelWV9NRdIVquQ9leZw9fPWfABQFQ) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Introduces SwiftUI's Layout protocol for building custom containers. Use it when arranging child subviews requires explicit measurement and placement rather than nested stacks or offset adjustments.
- [A Guided Tour for SwiftUI ForEach Structure](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2hvbHlzd2lmdC5hcHAvYS1ndWlkZWQtdG91ci1mb3Itc3dpZnR1aS1mb3JlYWNoLXN0cnVjdHVyZS8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiI1MDE2ODcwNy0xOWU2LTQ5ZWMtYTMwZS1kMzQ1ODk4YzkzOTkiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiYmQ5NjczNjUtNWFhMC00YjM5LTk1ZjQtMmEwZWI2ODA1MmEzIiwiaWF0IjoxNjc0MDYyNTU2LjksImlzcyI6Im9yY2hpZCJ9.uAPAEtFBRViS79-t8wBrlcGZ7lu5UcdfjcjxKpgwqRY) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines ForEach identity, data collections, and generated child views in SwiftUI. Useful for avoiding unstable identifiers and understanding why list updates or animations can attach to the wrong row.

## [SwiftUI Weekly - Issue #120](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-120)

- Published: `2022-11-13T21:07:50.000Z`

**Topics:** Architecture · Composable Architecture · Graphics, Media & Games · Objective-C & Cocoa · Swift · SwiftUI

**Sections:** Reading · When .animation animates more than it’s supposed to · Working with Lists in Multiplatform SwiftUI Apps

**NeKI brief:** Animation scoping and multiplatform List behavior are the technical focus. The issue helps diagnose modifiers that animate unrelated state and compare collection semantics across iOS and macOS before sharing a view hierarchy.

## [SwiftUI Weekly - Issue #119](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-119)

- Published: `2022-11-07T00:26:34.000Z`

**Topics:** Accessibility · Developer Career & Practice · macOS & AppKit · Observation & State Management · Swift · SwiftUI

**Sections:** Reading · Window management in SwiftUI · Running Code Only Once in SwiftUI

**NeKI brief:** SwiftUI window management and run-once code patterns address scene lifecycle and side-effect ownership. Follow it when desktop scenes need explicit window behavior and initialization work must not repeat during view recomputation.

## [SwiftUI Weekly - Issue #118](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-118)

- Published: `2022-11-01T11:57:40.000Z`

**Topics:** App Distribution & Store Operations · App Intents & System Surfaces · App Services & Extensions · Graphics, Media & Games · Swift · SwiftUI

**Sections:** Reading · Mastering NavigationSplitView in SwiftUI · Hello Swift Charts

**NeKI brief:** NavigationSplitView architecture and subscription tooling lead this issue. The SwiftUI material is useful for multi-column navigation, especially when adapting split behavior across size classes and keeping destinations driven by selection state.

## [SwiftUI Weekly - Issue #117](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-117)

- Published: `2022-10-17T11:20:35.000Z`

**Topics:** Composable Architecture · Concurrency · Navigation & Deep Linking · Objective-C & Cocoa · Swift · SwiftUI

**Sections:** News · Apple’s use of Swift and SwiftUI in iOS 16 · Reading

**NeKI brief:** Apple’s iOS 16 implementation, NavigationPath, tab badges, and task main-actor isolation provide concrete platform context. Research it when deep links mutate typed paths or asynchronous view work needs a justified actor boundary.

## [SwiftUI Weekly - Issue #116](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-116)

- Published: `2022-10-04T11:50:56.000Z`

**Topics:** App Services & Extensions · Developer Tools · Graphics, Media & Games · Swift · SwiftUI · UIKit

**Sections:** Reading · Displaying live activities in iOS 16 · Mastering Dynamic Island in SwiftUI

**NeKI brief:** Live Activities, Dynamic Island layouts, monospaced date digits, and lifecycle events span widgets and SwiftUI scenes. The issue helps coordinate timeline-driven UI with predictable task and appearance handling.

## [SwiftUI Weekly - Issue #115](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-115)

- Published: `2022-09-19T21:30:23.000Z`

**Topics:** App Services & Extensions · Navigation & Deep Linking · Observation & State Management · Swift · SwiftUI · Testing

**Sections:** Reading · New BackgroundTask in SwiftUI and How to Test It · Dependency Injection with @State Variables

**NeKI brief:** BackgroundTask testing, State-based dependency injection, editable navigation titles, and AppStorage bindings cover lifecycle and persistence. Follow it when background work must be testable and injected models should survive view updates.

## [SwiftUI Weekly - Issue #114](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-114)

- Published: `2022-09-13T16:37:55.000Z`

**Topics:** App Intents & System Surfaces · App Services & Extensions · Graphics, Media & Games · Navigation & Deep Linking · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #114 · News

**Selected links:**
- [The SwiftUI Layout Protocol - Part 2](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3N3aWZ0dWktbGFiLmNvbS9sYXlvdXQtcHJvdG9jb2wtcGFydC0yLz91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6ImYyZTA5NDQxLWI0OWQtNDY2Ni1iZGY0LWNhMDE1ZWNmYTdiMSIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiJlYzNhYzhhNC01YThhLTQzZGUtYmY3OC1jMGViNTNmMWZlZjUiLCJpYXQiOjE2NzQwNjI1NTguMDk2LCJpc3MiOiJvcmNoaWQifQ._glPwaca1iVFJwupEeTdogDJhpWE9AaEf-Mko6Z_onA) — Article · Topics: Foundation & Data Formats · Swift · SwiftUI
  **NeKI brief:** Continues custom SwiftUI Layout implementation techniques. Use it when caching, placement, and subview proposals need deliberate control for performance.
- [How to build a configurable widget with WidgetKit and SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3RhbmFzY2hpdGEuY29tLzIwMjIwOTA1LWhvdy10by1idWlsZC1hLWNvbmZpZ3VyYWJsZS13aWRnZXQtd2l0aC13aWRnZXRraXQtYW5kLXN3aWZ0dWkvP3V0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiZjJlMDk0NDEtYjQ5ZC00NjY2LWJkZjQtY2EwMTVlY2ZhN2IxIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6ImVjM2FjOGE0LTVhOGEtNDNkZS1iZjc4LWMwZWI1M2YxZmVmNSIsImlhdCI6MTY3NDA2MjU1OC4wOTYsImlzcyI6Im9yY2hpZCJ9.rMp3X_sYwUx7J0iCHmj_IUI8W8XzqKIELF-qKAwhWbE) — Article · Topics: Product Design · Swift · SwiftUI
  **NeKI brief:** Builds a configurable WidgetKit widget with SwiftUI configuration and timeline data. Useful for connecting user-selected widget parameters to deterministic entries and previewable widget states.
- [Customizing toolbars in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3N3aWZ0d2l0aG1hamlkLmNvbS8yMDIyLzA5LzA3L2N1c3RvbWl6aW5nLXRvb2xiYXJzLWluLXN3aWZ0dWkvP3V0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiZjJlMDk0NDEtYjQ5ZC00NjY2LWJkZjQtY2EwMTVlY2ZhN2IxIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6ImVjM2FjOGE0LTVhOGEtNDNkZS1iZjc4LWMwZWI1M2YxZmVmNSIsImlhdCI6MTY3NDA2MjU1OC4wOTYsImlzcyI6Im9yY2hpZCJ9.7AuY2JhBPlm4DbfQl8DdDn3qYCviquyQ5ePgfvMiXhs) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Customizes SwiftUI toolbars through placements and content. Use it when commands need platform-appropriate presentation across navigation, windows, and keyboard workflows.
- [How to make SwiftUI button with buttonStyle expand to full width](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3NhcnVudy5jb20vcG9zdHMvc3dpZnR1aS1idXR0b24tc3R5bGUtd2lkdGgvP3V0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiZjJlMDk0NDEtYjQ5ZC00NjY2LWJkZjQtY2EwMTVlY2ZhN2IxIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6ImVjM2FjOGE0LTVhOGEtNDNkZS1iZjc4LWMwZWI1M2YxZmVmNSIsImlhdCI6MTY3NDA2MjU1OC4wOTYsImlzcyI6Im9yY2hpZCJ9.fJh5689Uwlx1NANDSCeIeiR02piSDjat8idPz-EeDT8) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Expands a button styled with ButtonStyle to full width, separating hit-target layout from the style's visual treatment and semantic role.

## [SwiftUI Weekly - Issue #113](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-113)

- Published: `2022-08-30T13:30:24.000Z`

**Topics:** Graphics, Media & Games · macOS & AppKit · Swift · SwiftUI · Testing

**Sections:** Reading · Conditional layouts in SwiftUI · Mastering grid layout in SwiftUI

**NeKI brief:** Conditional layouts, custom grids, focus navigation direction, and ViewThatFits demonstrate adaptive composition. Use this issue to choose between layout alternatives and preserve keyboard or remote-focus behavior across form factors.

## [SwiftUI Weekly - Issue #112](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-112)

- Published: `2022-08-09T00:02:23.000Z`

**Topics:** Graphics, Media & Games · macOS & AppKit · Objective-C & Cocoa · Swift · SwiftUI · Testing

**Sections:** Reading · Content transition in SwiftUI · What is the fixedSize modifier in SwiftUI

**NeKI brief:** Content transitions, fixedSize, SwiftUI Table, and NavigationSplitView introduce presentation and macOS layout concerns. Research it when text changes should animate without layout surprises and desktop navigation needs explicit column roles.

## [SwiftUI Weekly - Issue #111](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-111)

- Published: `2022-08-01T20:26:06.000Z`

**Topics:** Cross-Platform & Web · Graphics, Media & Games · Swift · Swift Package Manager · SwiftUI · Xcode

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #111 · Reading

**Selected links:**
- [SwiftUI Gauges](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3VzZXlvdXJsb2FmLmNvbS9ibG9nL3N3aWZ0dWktZ2F1Z2VzLz91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6ImZjNWNiNzAxLTM3ZDctNGExYy1iNWZlLTBmNzYwM2M3MTQ1ZiIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiJjYTVlZjAwNi1iM2VjLTQ3MmYtYjQ4MS0yMjM3ZWIxODZmYzciLCJpYXQiOjE2NzQwNjI1NTcuOTg1LCJpc3MiOiJvcmNoaWQifQ.HU7SGDICNKuXQYH6V01lTZJxlcDAqjWNWJY5a6f0utc) — Article · Topics: Swift · SwiftUI · Xcode
  **NeKI brief:** Introduces SwiftUI Gauge for progress and range values, useful for choosing a semantic control whose style can vary independently from measurement state.
- [Extracting Views Into Components in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyJnY9Rkk0WXJtR2VncWciLCJwb3N0X2lkIjoiZmM1Y2I3MDEtMzdkNy00YTFjLWI1ZmUtMGY3NjAzYzcxNDVmIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6ImNhNWVmMDA2LWIzZWMtNDcyZi1iNDgxLTIyMzdlYjE4NmZjNyIsImlhdCI6MTY3NDA2MjU1Ny45ODUsImlzcyI6Im9yY2hpZCJ9.gTL9x1122ggPRSt8rIVlwZE8wGlOmIW2f0Z_J-RWaso) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [SwiftUI: Packaging Views](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyJnY9UnVGQ05FZjRQN0UiLCJwb3N0X2lkIjoiZmM1Y2I3MDEtMzdkNy00YTFjLWI1ZmUtMGY3NjAzYzcxNDVmIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6ImNhNWVmMDA2LWIzZWMtNDcyZi1iNDgxLTIyMzdlYjE4NmZjNyIsImlhdCI6MTY3NDA2MjU1Ny45ODUsImlzcyI6Im9yY2hpZCJ9.AFv-2mqF3eMA1R73dQIGybln7ZQiPjXYo6Lnf1zbyHE) — Article · Topics: Swift · Swift Package Manager · SwiftUI
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Removing the iOS home indicator in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2RhbmllbHNhaWRpLmNvbS9ibG9nLzIwMjIvMDgvMDEvcmVtb3ZpbmctdGhlLWhvbWUtaW5kaWNhdG9yLWluLXN3aWZ0dWk_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiJmYzVjYjcwMS0zN2Q3LTRhMWMtYjVmZS0wZjc2MDNjNzE0NWYiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiY2E1ZWYwMDYtYjNlYy00NzJmLWI0ODEtMjIzN2ViMTg2ZmM3IiwiaWF0IjoxNjc0MDYyNTU3Ljk4NSwiaXNzIjoib3JjaGlkIn0.p5jgDVjm62fq_cpWKfdi0Ss1AT7qRmjXHipLWe-K1ss) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Shows how SwiftUI can hide the home indicator through UIKit hosting integration and environment handling. Useful for immersive media or game screens, with careful consideration of discoverability and platform review expectations.

## [SwiftUI Weekly - Issue #110](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-110)

- Published: `2022-07-25T14:27:26.000Z`

**Topics:** Apple Platform Ecosystem · Concurrency · Graphics, Media & Games · Swift · SwiftUI · Testing

**Sections:** Reading · Bottom sheet API in SwiftUI · Mastering LabeledContent in SwiftUI

**NeKI brief:** Bottom-sheet APIs, LabeledContent, split-view configuration, and iPad-customizable toolbars form a platform-oriented SwiftUI set. Follow it when presentation detents and adaptive chrome must remain semantic and size-class aware.

## [SwiftUI Weekly - Issue #109](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-109)

- Published: `2022-07-11T20:32:48.000Z`

**Topics:** Concurrency · Graphics, Media & Games · macOS & AppKit · Swift · SwiftUI · Xcode

**Sections:** News · What's New in Xcode 14 Previews · Reading

**NeKI brief:** Xcode previews, task lifecycle, renderers, and typed NSUserActivity payloads connect development tooling with state restoration. The issue is useful for previewing asynchronous screens and making handoff or deep-link data type-safe.

## [SwiftUI Weekly - Issue #108](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-108)

- Published: `2022-06-28T06:42:32.000Z`

**Topics:** Graphics, Media & Games · macOS & AppKit · Maps & Location · Navigation & Deep Linking · Swift · SwiftUI

**Sections:** News · SwiftUI Index · Reading

**NeKI brief:** NavigationStack deep links, macOS SwiftUI, and ViewThatFits cover route restoration and adaptive presentation. Research it when one codebase spans desktop and mobile while destinations must be selected from external URLs.

## [SwiftUI Weekly - Issue #107](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-107)

- Published: `2022-06-21T10:41:22.000Z`

**Topics:** App Distribution & Store Operations · Apple Platform Ecosystem · Developer Tools · Graphics, Media & Games · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #107 · Reading

**Selected links:**
- [Mastering NavigationStack in SwiftUI. Navigator Pattern.](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3N3aWZ0d2l0aG1hamlkLmNvbS8yMDIyLzA2LzE1L21hc3RlcmluZy1uYXZpZ2F0aW9uc3RhY2staW4tc3dpZnR1aS1uYXZpZ2F0b3ItcGF0dGVybi8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiJlOGMyZGIwMC05Y2NjLTRkOWItYmI5Ni1kMWU2MDU3NjFhOTciLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiY2E4YjI1ODQtMmEzYy00OWQ1LThlNzktNTM1NjdlNDI1OTY2IiwiaWF0IjoxNjc0MDYyNTU4Ljg3MywiaXNzIjoib3JjaGlkIn0.-tZb7r5BXvSxhCgyx7-7lMYTg9-uqRno78zJ8Lvvbjs) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Explains a navigator pattern around NavigationStack, turning destinations and routing decisions into explicit state. Useful for testing deep links, centralizing navigation mutations, and keeping feature views independent of presentation mechanics.
- [Using ViewThatFits to replace GeometryReader in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy5jcmVhdGV3aXRoc3dpZnQuY29tL3VzaW5nLXZpZXd0aGF0Zml0cy10by1yZXBsYWNlLWdlb21ldHJ5cmVhZGVyLWluLXN3aWZ0dWkvP3V0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiZThjMmRiMDAtOWNjYy00ZDliLWJiOTYtZDFlNjA1NzYxYTk3IiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6ImNhOGIyNTg0LTJhM2MtNDlkNS04ZTc5LTUzNTY3ZTQyNTk2NiIsImlhdCI6MTY3NDA2MjU1OC44NzMsImlzcyI6Im9yY2hpZCJ9.SNpycsd5yJT-2Mbxz9F_-rNT5IeEMU7DZI1u9fqXj3A) — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Demonstrates ViewThatFits for selecting a layout that fits available space instead of measuring manually with GeometryReader. Useful for responsive controls that need graceful alternatives across compact and regular widths.
- [Requesting App Store reviews in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL25pbGNvYWxlc2NpbmcuY29tL2Jsb2cvUmVxdWVzdGluZ0FwcFN0b3JlUmV2aWV3c0luU3dpZnRVSS8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiJlOGMyZGIwMC05Y2NjLTRkOWItYmI5Ni1kMWU2MDU3NjFhOTciLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiY2E4YjI1ODQtMmEzYy00OWQ1LThlNzktNTM1NjdlNDI1OTY2IiwiaWF0IjoxNjc0MDYyNTU4Ljg3MywiaXNzIjoib3JjaGlkIn0.gpPrkF9rQIPK1vqfb0AZ1jFSBMP_sLOCzneScAJ-voM) — Article · Topics: App Distribution & Store Operations · Swift · SwiftUI
  **NeKI brief:** Shows how to trigger App Store review requests from SwiftUI while respecting the system-controlled presentation. Useful for choosing a meaningful in-app moment and avoiding repeated or disruptive prompts.
- [Build a 3D Bar Chart in SceneKit With SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2JldHRlcnByb2dyYW1taW5nLnB1Yi9idWlsZC1hLTNkLWJhci1jaGFydC1pbi1zY2VuZWtpdC13aXRoLXN3aWZ0dWktNzg5YTI2MzFlZjZmP2dpPTg1YzdjMDE1YTk1JnV0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiZThjMmRiMDAtOWNjYy00ZDliLWJiOTYtZDFlNjA1NzYxYTk3IiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6ImNhOGIyNTg0LTJhM2MtNDlkNS04ZTc5LTUzNTY3ZTQyNTk2NiIsImlhdCI6MTY3NDA2MjU1OC44NzMsImlzcyI6Im9yY2hpZCJ9.oERc-pJ7HTDhbqnjYoyFf6zEXGXSuMjroDQDR8UEYh8) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Combines SceneKit’s 3D bar geometry with SwiftUI presentation to visualize data interactively. Useful when a chart needs depth, rotation, or custom scene rendering beyond native SwiftUI charts.

## [SwiftUI Weekly - Issue #106](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-106)

- Published: `2022-06-13T14:04:29.000Z`

**Topics:** Apple Platform Ecosystem · Graphics, Media & Games · macOS & AppKit · Swift · SwiftUI · Xcode

**Sections:** News · What’s new in Swift 5.7 · What is new in SwiftUI after WWDC22

**NeKI brief:** Swift 5.7, WWDC22 SwiftUI changes, Xcode 14, and resizable sheets provide a release-era migration snapshot. Use it to compare new sheet APIs with deployment constraints and identify compiler features affecting view code.

## [SwiftUI Weekly - Issue #105](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-105)

- Published: `2022-05-30T19:57:23.000Z`

**Topics:** Accessibility · Combine & Reactive Programming · Cross-Platform & Web · Graphics, Media & Games · Swift · SwiftUI

**Sections:** News · SwiftUI in 2022 · Reading

**NeKI brief:** Accessibility children, equal and ideal sizing, Markdown Text, and the 2022 SwiftUI landscape address semantic and adaptive rendering. Follow it when rich text needs VoiceOver structure and layouts must tolerate content variation.

## [SwiftUI Weekly - Issue #104](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-104)

- Published: `2022-05-23T22:33:49.000Z`

**Topics:** Architecture · Developer Career & Practice · Developer Community & Business · Graphics, Media & Games · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #104 · Reading

**Selected links:**
- [How to Make a Game Like Wordle in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy5yYXl3ZW5kZXJsaWNoLmNvbS8zMTY2MTI2My1ob3ctdG8tbWFrZS1hLWdhbWUtbGlrZS13b3JkbGUtaW4tc3dpZnR1aS1wYXJ0LW9uZT9oc3NfY2hhbm5lbD10dy04MDg0MzI2MiZ1dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fY29udGVudD0yMDg5OTg0MjUmdXRtX21lZGl1bT1zb2NpYWwmdXRtX3NvdXJjZT10d2l0dGVyIiwicG9zdF9pZCI6ImRhYmRkNzEwLWM0MDgtNGFmYS04NDI4LTRlZGUxNWIzMmM3NSIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiJiOGViODljMC02MGFkLTQ2MjYtODY4Zi1mZWJkNDAzYTdhNzkiLCJpYXQiOjE2NzQwNjI1NTkuMTI5LCJpc3MiOiJvcmNoaWQifQ.hnLhTIeWgfOZ5bBnbKNbq0UhoAvhtPpAB7w93UZfYns) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Builds a Wordle-style game in SwiftUI, covering tile state, guesses, keyboard input, and feedback. Useful as a concrete exercise in modeling transient game state and composing grid-based UI.
- [Build an Onboarding Flow in SwiftUI with @AppStorage, Transition, Login & Logout](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyJnY9eGk5VDhqZjdSWFkiLCJwb3N0X2lkIjoiZGFiZGQ3MTAtYzQwOC00YWZhLTg0MjgtNGVkZTE1YjMyYzc1IiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6ImI4ZWI4OWMwLTYwYWQtNDYyNi04NjhmLWZlYmQ0MDNhN2E3OSIsImlhdCI6MTY3NDA2MjU1OS4xMjksImlzcyI6Im9yY2hpZCJ9.akbcSLgLlU5s2GXo_iu6cFB4rQrMCYzqJZjyvqmRbTI) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Constructs an onboarding and authentication flow using @AppStorage, transitions, and login/logout state. Useful for separating persisted session decisions from view presentation while keeping first-run navigation predictable.
- [Mastering TimelineView in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3N3aWZ0d2l0aG1hamlkLmNvbS8yMDIyLzA1LzE4L21hc3RlcmluZy10aW1lbGluZXZpZXctaW4tc3dpZnR1aS8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiJkYWJkZDcxMC1jNDA4LTRhZmEtODQyOC00ZWRlMTViMzJjNzUiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiYjhlYjg5YzAtNjBhZC00NjI2LTg2OGYtZmViZDQwM2E3YTc5IiwiaWF0IjoxNjc0MDYyNTU5LjEyOSwiaXNzIjoib3JjaGlkIn0.jKBoXpALzcTY9SLQeomKi-2GuH0AiVAmzh-H8nbpcPs) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explores TimelineView schedules and timeline entries for periodically refreshed SwiftUI content. Useful for clocks, animations, and lightweight time-based updates while keeping refresh cadence explicit and energy-aware.
- [Using the isEnabled environment value in iOS 14](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2RhbmllbHNhaWRpLmNvbS9ibG9nLzIwMjIvMDUvMjAvdXNpbmctdGhlLWlzRW5hYmxlZC1lbnZpcm9ubWVudC12YWx1ZS1pbi1pT1MtMTQ_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiJkYWJkZDcxMC1jNDA4LTRhZmEtODQyOC00ZWRlMTViMzJjNzUiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiYjhlYjg5YzAtNjBhZC00NjI2LTg2OGYtZmViZDQwM2E3YTc5IiwiaWF0IjoxNjc0MDYyNTU5LjEyOSwiaXNzIjoib3JjaGlkIn0.uSErxWRhNLz9RqyzTkZnoHHK69Y8I5luSpiNtce45kA) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows how child SwiftUI views read the isEnabled environment value to adapt styling or behavior when controls are disabled. Useful for reusable components that must mirror parent interaction state.

## [SwiftUI Weekly - Issue #103](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-103)

- Published: `2022-05-16T22:15:03.000Z`

**Topics:** App Distribution & Store Operations · Concurrency · Graphics, Media & Games · Swift · Swift Package Manager · SwiftUI

**Sections:** News · Update to subscription notifications · Reading

**NeKI brief:** Subscription notifications, error modeling, the SwiftUI render loop, and production-readiness criticism create a diagnostic issue. Research it when state updates appear cyclic or domain errors need to remain separate from view rendering.

## [SwiftUI Weekly - Issue #102](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-102)

- Published: `2022-05-09T09:44:17.000Z`

**Topics:** Concurrency · Graphics, Media & Games · macOS & AppKit · Swift · SwiftUI · UIKit

**Sections:** Reading · String Interpolation in LocalizedStringKey in SwiftUI · How to create SwiftUI circular progress bar

**NeKI brief:** LocalizedStringKey interpolation, circular progress, cross-framework hex colors, and MainActor semantics cover localization and concurrency fundamentals. Use it to avoid losing format arguments and to isolate UI mutations on the correct actor.

## [SwiftUI Weekly - Issue #101](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-101)

- Published: `2022-05-02T15:33:22.000Z`

**Topics:** App Distribution & Store Operations · Concurrency · Core Data · Persistence & Synchronisation · Swift · SwiftUI

**Sections:** Reading · Sharing Core Data With CloudKit in SwiftUI · Flow Navigation With SwiftUI

**NeKI brief:** Core Data with CloudKit, flow navigation, external displays, and animated rating controls span persistence and multi-scene UI. Follow it when navigation state and shared stores must work beyond the primary screen.

## [SwiftUI Weekly - Issue #100](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-100)

- Published: `2022-04-25T10:00:02.000Z`

**Topics:** Graphics, Media & Games · macOS & AppKit · Performance · Persistence & Synchronisation · Swift · SwiftUI

**Sections:** Reading · Exporting data from Unified Logging System in Swift · Build a Flexible Picker With SwiftUI

**Selected links:**
- [Exporting data from Unified Logging System in Swift](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3N3aWZ0d2l0aG1hamlkLmNvbS8yMDIyLzA0LzE5L2V4cG9ydGluZy1kYXRhLWZyb20tdW5pZmllZC1sb2dnaW5nLXN5c3RlbS1pbi1zd2lmdC8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiI3Zjg1ZDc1Ny0xZjZhLTRmODItOTcyYi1iMGRhZDIzOWE2ZmIiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiODFjMmM0MWMtODZhOC00NWM4LThmOTEtMzcxOWE2ZWRhZDI0IiwiaWF0IjoxNjc0MDYyNTU5LjIxOCwiaXNzIjoib3JjaGlkIn0.0LDRJdpcern5h3_dv7zNRck3LYVsnUu2ZnWXBtQRpfg) — Article · Topics: Persistence & Synchronisation · Swift
  **NeKI brief:** Demonstrates exporting Unified Logging data for inspection outside the running app. Useful when diagnosing production behavior, collecting reproducible evidence, and turning OSLog output into shareable debugging artifacts.
- [Build a Flexible Picker With SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2JldHRlcnByb2dyYW1taW5nLnB1Yi9mbGV4aWJsZS1waWNrZXItd2l0aC1zd2lmdHVpLTU4MTdmZmU5ZmRkZj9naT1lNGNjMTZiN2JkZTcmdXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiI3Zjg1ZDc1Ny0xZjZhLTRmODItOTcyYi1iMGRhZDIzOWE2ZmIiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiODFjMmM0MWMtODZhOC00NWM4LThmOTEtMzcxOWE2ZWRhZDI0IiwiaWF0IjoxNjc0MDYyNTU5LjIxOCwiaXNzIjoib3JjaGlkIn0.aNqBsgEtyN4ewnTZM5vrgbhv6A-llNKn1MuGNuHcye4) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Implements a flexible picker component with custom selection presentation and reusable options. Useful when Picker styles cannot express product-specific layouts but selection semantics should remain typed and accessible.
- [Animating number changes in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3N0ZWZhbmJsb3MuY29tL3Bvc3RzL2FuaW1hdGluZy1udW1iZXItY2hhbmdlcy8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiI3Zjg1ZDc1Ny0xZjZhLTRmODItOTcyYi1iMGRhZDIzOWE2ZmIiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiODFjMmM0MWMtODZhOC00NWM4LThmOTEtMzcxOWE2ZWRhZDI0IiwiaWF0IjoxNjc0MDYyNTU5LjIxOCwiaXNzIjoib3JjaGlkIn0.fkJ4JVm6TlZWatfHYJeQaFwpgt4MVjNdcmWkT-O3Cfo) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explores animating changing numeric values in SwiftUI so updates communicate deltas rather than abruptly replacing text. Useful for counters, balances, and progress displays where motion should clarify state changes.
- [Downloading and Caching images in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy5hdmFuZGVybGVlLmNvbS9zd2lmdHVpL2Rvd25sb2FkaW5nLWNhY2hpbmctaW1hZ2VzLz91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6IjdmODVkNzU3LTFmNmEtNGY4Mi05NzJiLWIwZGFkMjM5YTZmYiIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiI4MWMyYzQxYy04NmE4LTQ1YzgtOGY5MS0zNzE5YTZlZGFkMjQiLCJpYXQiOjE2NzQwNjI1NTkuMjE4LCJpc3MiOiJvcmNoaWQifQ.kInSjhLVbVe1ydYxbUNulXOLxyfZsrdPvKNxC0z6nCk) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows an image-loading pipeline that downloads remote images and caches results for later SwiftUI rendering. Useful for reducing repeated network work while handling placeholders, failures, and asynchronous view updates.

## [SwiftUI Weekly - Issue #99](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-99)

- Published: `2022-04-11T16:24:07.000Z`

**Topics:** Apple Platform Ecosystem · Developer Tools · Persistence & Synchronisation · Swift · SwiftUI · Xcode

**Sections:** News · WWDC22 · Reading

**NeKI brief:** CloudKit zone sharing, adaptive stacks, logging, and WWDC22 context support robust data-backed layouts. Research it when availability changes with size classes and CloudKit collaboration errors need observable diagnostics.

## [SwiftUI Weekly - Issue #98](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-98)

- Published: `2022-03-29T11:07:26.000Z`

**Topics:** Graphics, Media & Games · Objective-C & Cocoa · Persistence & Synchronisation · Swift · SwiftUI · Testing

**Sections:** Reading · Getting started with CloudKit · Lifetime of State Properties in SwiftUI

**NeKI brief:** CloudKit setup, State lifetime, pull-to-refresh, and simplified error alerts address data loading and ownership. The issue helps ensure refresh tasks do not outlive their view and local state resets only when identity changes.

## [SwiftUI Weekly - Issue #97](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-97)

- Published: `2022-03-22T00:08:50.000Z`

**Topics:** Accessibility · Combine & Reactive Programming · Concurrency · Swift · SwiftUI · Testing

**Sections:** Reading · Functional core Imperative shell in Swift. Unidirectional Flow · SwiftUI List Selection On iPad

**NeKI brief:** Unidirectional flow, iPad List selection, custom-font pitfalls, and spring animations cover architecture and platform detail. Follow it when selection behavior diverges by device or typography changes invalidate animation and layout assumptions.

## [SwiftUI Weekly - Issue #96](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-96)

- Published: `2022-03-15T13:39:20.000Z`

**Topics:** Core Data · Product Design · Swift · Swift Package Manager · SwiftUI · Xcode

**Sections:** News · Swift 5.6 Released! · Reading

**NeKI brief:** State restoration, UISheetPresentationController bridging, confirmation dialogs, and Swift 5.6 changes connect UIKit interoperability with SwiftUI state. Research it when restoring navigation or exposing platform sheet controls without losing declarative ownership.

## [SwiftUI Weekly - Issue #95](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-95)

- Published: `2022-03-08T07:19:07.000Z`

**Topics:** Foundation & Data Formats · Graphics, Media & Games · Objective-C & Cocoa · Personal Essays · Swift · SwiftUI

**Sections:** News · What’s new in Swift 5.6? · Reading

**NeKI brief:** Swift 5.6, functional-core architecture, LabelStyle adaptation, and @Published risks provide guidance for isolating side effects. Use it when refactoring observable models and deciding which formatting belongs in reusable styles.

## [SwiftUI Weekly - Issue #94](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-94)

- Published: `2022-02-28T09:54:32.000Z`

**Topics:** Concurrency · Graphics, Media & Games · Objective-C & Cocoa · Observation & State Management · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #94 · Reading

**Selected links:**
- [SwiftUI under the Hood: Variadic Views](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL21vdmluZ3BhcnRzLmlvL3ZhcmlhZGljLXZpZXdzLWluLXN3aWZ0dWk_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiIxOTk1YWIwNy0zNjQwLTQxYzktYWNjMy1jN2VkZDc5Mjc1NzAiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiMzRhNjRmMTctNGJmMC00YTJjLWEyYjUtZjg1OTFmODJlYjdkIiwiaWF0IjoxNjc0MDYyNjE2Ljg4NywiaXNzIjoib3JjaGlkIn0.vKHxIRY4TOLk3x4euC-DsDkEltXaDURt7h1IR-MUACg) — Article · Topics: AI Development · Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI’s variadic view machinery and how containers inspect child content. Useful for understanding result-builder composition, custom container behavior, and why certain child transformations are difficult.
- [Using the ViewBuilder Attribute to Implement SwiftUI Views in Methods](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3NlcmlhbGNvZGVyLmRldi90ZXh0LXR1dG9yaWFscy9zd2lmdHVpL3VzaW5nLXRoZS12aWV3YnVpbGRlci1hdHRyaWJ1dGUtdG8taW1wbGVtZW50LXN3aWZ0dWktdmlld3MtaW4tbWV0aG9kcy8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiIxOTk1YWIwNy0zNjQwLTQxYzktYWNjMy1jN2VkZDc5Mjc1NzAiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiMzRhNjRmMTctNGJmMC00YTJjLWEyYjUtZjg1OTFmODJlYjdkIiwiaWF0IjoxNjc0MDYyNjE2Ljg4NywiaXNzIjoib3JjaGlkIn0.jnEAe3AYFRyCM4TUBM2YogClGuCdhIyIqmDRMOzGYdk) — Article · Topics: AI Development · Swift · SwiftUI
  **NeKI brief:** Uses @ViewBuilder on methods to return conditional SwiftUI content while preserving declarative composition. Useful for extracting repeated branches without erasing types or making view bodies harder to read.
- [Loading an Image with AsyncImage() in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy5zd2lmdGx5cnVzaC5jb20vbG9hZGluZy1hbi1pbWFnZS13aXRoLWFzeW5jaW1hZ2UtaW4tc3dpZnR1aS8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiIxOTk1YWIwNy0zNjQwLTQxYzktYWNjMy1jN2VkZDc5Mjc1NzAiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiMzRhNjRmMTctNGJmMC00YTJjLWEyYjUtZjg1OTFmODJlYjdkIiwiaWF0IjoxNjc0MDYyNjE2Ljg4NywiaXNzIjoib3JjaGlkIn0.gB5E-_40OIJVOYvlR7U6h1dSSf9F77MWV43dY8TlP-g) — Article · Topics: Concurrency · Swift · SwiftUI
  **NeKI brief:** Introduces AsyncImage for loading remote images with phase-aware success, failure, and placeholder views. Useful for simple network imagery when you can accept system loading behavior and provide explicit fallback UI.
- [SwiftUI Filtering with the Searchable Modifier](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD90PThzJnV0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXImdj13em9YV2haVUI1byIsInBvc3RfaWQiOiIxOTk1YWIwNy0zNjQwLTQxYzktYWNjMy1jN2VkZDc5Mjc1NzAiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiMzRhNjRmMTctNGJmMC00YTJjLWEyYjUtZjg1OTFmODJlYjdkIiwiaWF0IjoxNjc0MDYyNjE2Ljg4NywiaXNzIjoib3JjaGlkIn0.MIRHY06NAcrGpIiXhmfgyOFumNl-UFq7Q2nKMIMwGeY) — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **NeKI brief:** Demonstrates searchable-based filtering in SwiftUI, connecting query text to collection results. Useful for building discoverable list search while deciding where normalization, debouncing, and empty-state handling belong.

## [SwiftUI Weekly - Issue #93](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-93)

- Published: `2022-02-21T22:32:58.000Z`

**Topics:** Concurrency · Product Design · Swift · SwiftUI · Testing · UIKit

**Sections:** Reading · Redux-like state container in SwiftUI. Swift concurrency model. · Writing testable code when using SwiftUI

**NeKI brief:** Redux-like state containers, Swift concurrency, testable SwiftUI, redacted placeholders, and hex colors form a cohesive architecture-and-UX batch. Follow it to separate loading state from domain state and keep view tests deterministic.

## [SwiftUI Weekly - Issue #92](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-92)

- Published: `2022-02-14T16:59:35.000Z`

**Topics:** Developer Tools · Foundation & Data Formats · Graphics, Media & Games · Objective-C & Cocoa · Swift · SwiftUI

**Sections:** Reading · SwiftUI Search: Getting Started · Debugging SwiftUI views: what caused that change?

**NeKI brief:** SwiftUI search, change-cause debugging, Markdown behavior, and fixedSize modifier details help explain unexpected updates and text layout. Research it when search state or rich text causes views to redraw or clip unexpectedly.

## [SwiftUI Weekly - Issue #91](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-91)

- Published: `2022-02-07T15:09:32.000Z`

**Topics:** Architecture · Concurrency · Dependency Injection · Objective-C & Cocoa · Swift · SwiftUI

**Sections:** News · Unlisted App Distribution · Reading

**NeKI brief:** Async image loading choices, dependency-injected microapps, unlisted distribution, and interactive animations span architecture and media. Use it to compare caching and cancellation strategies before embedding image work in view bodies.

## [SwiftUI Weekly - Issue #90](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-90)

- Published: `2022-01-31T19:01:20.000Z`

**Topics:** Architecture · Localization · Objective-C & Cocoa · Swift · SwiftUI · Xcode

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #90 · News

**Selected links:**
- [New SwiftUI documentation in Xcode 13.3 Beta 1](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy5maXZlc3RhcnMuYmxvZy9hcnRpY2xlcy94Y29kZS0xMy0zLWJldGEtMS8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiI2YTk3ZmNmYy05ODYwLTRiNTMtYWM4MC1hZmVlNmZjMDRmMzAiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiOWE0OGI1ZTktMDA0Mi00Mzk0LTg2NzQtNzdkYzIxYjk4OTZiIiwiaWF0IjoxNjc0MDYyNjE2LjkxOSwiaXNzIjoib3JjaGlkIn0.-Ob0Ep6OEPjmpfFkATftfXOCFh4cvuOCmdXYvFRq2FU) — Article · Topics: Swift · SwiftUI · Xcode
  **NeKI brief:** Highlights the expanded SwiftUI documentation shipped with Xcode 13.3 beta, including API references and conceptual guidance. Useful for navigating framework changes and checking intended usage during SDK adoption.
- [SF Symbols guide for SwiftUI and UIKit](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3RhbmFzY2hpdGEuY29tLzIwMjIwMTMxLXNmLXN5bWJvbHMtaW9zLWd1aWRlLz91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6IjZhOTdmY2ZjLTk4NjAtNGI1My1hYzgwLWFmZWU2ZmMwNGYzMCIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiI5YTQ4YjVlOS0wMDQyLTQzOTQtODY3NC03N2RjMjFiOTg5NmIiLCJpYXQiOjE2NzQwNjI2MTYuOTIsImlzcyI6Im9yY2hpZCJ9.VZLlS4nCImLT1fAswjK95Dlv2eTKkeXe7MalIR_tB-c) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Surveys SF Symbols usage across SwiftUI and UIKit, including naming, configuration, rendering, and accessibility considerations. Useful for selecting semantic icons that scale consistently across platforms and appearance modes.
- [How to show QR code in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL29ubXl3YXkxMzMuY29tL3Bvc3RzL2hvdy10by1zaG93LXFyLWNvZGUtaW4tc3dpZnR1aS8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiI2YTk3ZmNmYy05ODYwLTRiNTMtYWM4MC1hZmVlNmZjMDRmMzAiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiOWE0OGI1ZTktMDA0Mi00Mzk0LTg2NzQtNzdkYzIxYjk4OTZiIiwiaWF0IjoxNjc0MDYyNjE2LjkyLCJpc3MiOiJvcmNoaWQifQ.Vpu1E0QAbuxCiyvETnmzUhBqMuIfPyzKqNvD9Y04Sro) — Article · Topics: AI Development · Swift · SwiftUI
  **NeKI brief:** Shows generating and presenting a QR code in SwiftUI, including image rendering considerations. Useful for sharing links or identifiers while keeping scaling, contrast, and scanning reliability in mind.
- [Animations Inside a ScrollView With SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2JldHRlcnByb2dyYW1taW5nLnB1Yi9hbmltYXRpb25zLWluc2lkZS1hLXNjcm9sbHZpZXctd2l0aC1zd2lmdHVpLTNiNTUwYzE4YTQ0Mj9naT02Yzc4MzI0MDljMmYmdXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiI2YTk3ZmNmYy05ODYwLTRiNTMtYWM4MC1hZmVlNmZjMDRmMzAiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiOWE0OGI1ZTktMDA0Mi00Mzk0LTg2NzQtNzdkYzIxYjk4OTZiIiwiaWF0IjoxNjc0MDYyNjE2LjkxOSwiaXNzIjoib3JjaGlkIn0.gHAVywWNugXVugwqNR6aeYKNid9fjQuEjWCoWo9z0vM) — Article · Topics: AI Development · Swift · SwiftUI
  **NeKI brief:** Explores animation behavior inside SwiftUI ScrollView content and the interactions between scrolling, identity, and transitions. Useful for preventing jumpy updates when list-like content changes during user movement.

## [SwiftUI Weekly - Issue #89](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-89)

- Published: `2022-01-24T17:18:02.000Z`

**Topics:** Architecture · Combine & Reactive Programming · Graphics, Media & Games · Objective-C & Cocoa · Swift · SwiftUI

**Sections:** Reading · Microapps architecture in Swift. SPM basics. · Microapps architecture in Swift. Feature modules.

**NeKI brief:** Feature modules, SPM microapp structure, backgrounds and overlays, and infinite scrolling with Combine address modularity and collection loading. Follow it when decomposing a growing SwiftUI app without hiding pagination state.

## [SwiftUI Weekly - Issue #88](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-88)

- Published: `2022-01-12T15:40:25.000Z`

**Topics:** Combine & Reactive Programming · Concurrency · Observation & State Management · Persistence & Synchronisation · Swift · SwiftUI

**Sections:** News · Apple’s use of Swift and SwiftUI in iOS 15 · Reading

**NeKI brief:** SF Symbols, custom environment keys, Combine-driven updates, and Apple’s iOS 15 usage offer fundamentals for semantic styling and dependency propagation. Research it when environment values or publishers produce surprising SwiftUI invalidation.

## [SwiftUI Weekly - Issue #87](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-87)

- Published: `2021-12-20T16:53:23.000Z`

**Topics:** Architecture · Concurrency · Cross-Platform & Web · Objective-C & Cocoa · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #87 · Reading

**Selected links:**
- [Structural identity in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3N3aWZ0d2l0aG1hamlkLmNvbS8yMDIxLzEyLzA5L3N0cnVjdHVyYWwtaWRlbnRpdHktaW4tc3dpZnR1aS8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiI0NjgyOTBiZS05YzgzLTRkMjEtOGQyMi0wYjZlZDE0MmMyN2IiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiODVjN2Q2MTItZDI1My00M2RjLTliMmYtYTJhMzgzOTM4MmM0IiwiaWF0IjoxNjc0MDYyNjE3LjUzMSwiaXNzIjoib3JjaGlkIn0.sP5fjVe1QaDdit-zNS1fkeM8DS8nqZXsf8qKsv-h1x8) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Explains structural identity and how conditional view composition affects state lifetime and reuse. Useful for diagnosing disappearing state, unexpected transitions, and performance issues caused by changing view structure.
- [Animations and Transactions](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3RhbGsub2JqYy5pby9lcGlzb2Rlcy9TMDFFMjg1LWFuaW1hdGlvbnMtYW5kLXRyYW5zYWN0aW9ucz91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6IjQ2ODI5MGJlLTljODMtNGQyMS04ZDIyLTBiNmVkMTQyYzI3YiIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiI4NWM3ZDYxMi1kMjUzLTQzZGMtOWIyZi1hMmEzODM5MzgyYzQiLCJpYXQiOjE2NzQwNjI2MTcuNTMxLCJpc3MiOiJvcmNoaWQifQ.vvFUAaPGTS49DwmfXXowvWC3ye4G5ZbXOC1Gaz5KdAI) — Article · Topics: AI Development · Swift · SwiftUI
  **NeKI brief:** Discusses SwiftUI transactions as the context that carries animation decisions through a view update. Useful for scoping or disabling animations precisely instead of relying on broad withAnimation calls.
- [Implement YouTube-like filtering in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2tldmluLWZ1cmphbi5oYXNobm9kZS5kZXYvaW1wbGVtZW50LXlvdXR1YmUtbGlrZS1maWx0ZXJpbmctaW4tc3dpZnR1aT91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6IjQ2ODI5MGJlLTljODMtNGQyMS04ZDIyLTBiNmVkMTQyYzI3YiIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiI4NWM3ZDYxMi1kMjUzLTQzZGMtOWIyZi1hMmEzODM5MzgyYzQiLCJpYXQiOjE2NzQwNjI2MTcuNTMxLCJpc3MiOiJvcmNoaWQifQ.2HewNKM_bDKS4M94AYTfrOuzbvU2Gx9HxXGp469jES8) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a YouTube-style filter interface in SwiftUI with selectable categories and filtered content. Useful for modeling selection state and composing horizontally scrollable controls above dynamic results.
- [SwiftUI Text Field: Deep Dive](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy5kZXZ0ZWNoaWUuY29tL3N3aWZ0dWlfdGV4dGZpZWxkX2RlZXBkaXZlP3V0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiNDY4MjkwYmUtOWM4My00ZDIxLThkMjItMGI2ZWQxNDJjMjdiIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6Ijg1YzdkNjEyLWQyNTMtNDNkYy05YjJmLWEyYTM4MzkzODJjNCIsImlhdCI6MTY3NDA2MjYxNy41MzEsImlzcyI6Im9yY2hpZCJ9.uMIbqZJUmKbztERuh5_HSCTCGd8kO9ONRM-7vt47CkY) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Provides a detailed look at SwiftUI TextField configuration, editing behavior, and styling. Useful for handling focus, validation, keyboard interaction, and text input edge cases in production forms.

## [SwiftUI Weekly - Issue #86](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-86)

- Published: `2021-12-06T22:25:22.000Z`

**Topics:** Concurrency · Graphics, Media & Games · Localization · Swift · SwiftUI · Testing

**Sections:** Reading · Customizing view content shape in SwiftUI · SwiftUI Localization Tutorial for iOS

**NeKI brief:** Content shapes, localization, TextField behavior, and Swift concurrency Tasks cover interaction semantics and async work. Use it to make hit regions intentional, preserve localized text, and tie task cancellation to view lifetime.

## [SwiftUI Weekly - Issue #85](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-85)

- Published: `2021-11-30T12:44:45.000Z`

**Topics:** Combine & Reactive Programming · Concurrency · Core Data · Networking · Swift · SwiftUI

**Sections:** Reading · Mastering ProgressView in SwiftUI · Displaying Borders in SwiftUI

**NeKI brief:** ProgressView, borders, TimelineView, Canvas, transactions, and animations show how SwiftUI draws time-based and styled content. Follow it when choosing between declarative timelines and explicit animation transactions for performance-sensitive visuals.

## [SwiftUI Weekly - Issue #84](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-84)

- Published: `2021-11-23T00:08:11.000Z`

**Topics:** Concurrency · Foundation & Data Formats · Graphics, Media & Games · Swift · SwiftUI · Xcode

**Sections:** News · What's new in Xcode 13.2 beta 2 · Reading

**NeKI brief:** ShapeStyle, navigation open-source work, camera text capture, and Xcode 13.2 context combine rendering and integration. Research it when custom materials need semantic styling or camera results must enter SwiftUI state safely.

## [SwiftUI Weekly - Issue #83](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-83)

- Published: `2021-11-15T14:19:45.000Z`

**Topics:** Combine & Reactive Programming · Concurrency · Graphics, Media & Games · Swift · SwiftUI · UIKit

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #83 · Reading

**Selected links:**
- [Building a Camera App With SwiftUI and Combine](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy5yYXl3ZW5kZXJsaWNoLmNvbS8yNjI0NDc5My1idWlsZGluZy1hLWNhbWVyYS1hcHAtd2l0aC1zd2lmdHVpLWFuZC1jb21iaW5lP3V0bV9jYW1wYWlnbj1idWZmZXImdXRtX2NvbnRlbnQ9YnVmZmVyZDA5NDUmdXRtX21lZGl1bT1zb2NpYWwmdXRtX3NvdXJjZT10d2l0dGVyLmNvbSIsInBvc3RfaWQiOiJjMmZkZTdjMS00NjU0LTQ2ODctYWI0MC00NWEyNTI4NTVlMDUiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiOGUyZmQzNDUtYWJjYS00YTA5LThkYTMtNDE2NDVmNzA5OTJhIiwiaWF0IjoxNjc0MDYyNjE3LjcxNiwiaXNzIjoib3JjaGlkIn0.EYtjzcEt9k9qHn7Q5bQvobwNg9NVsUag7xF3x7v0QKc) — Article · Topics: Combine & Reactive Programming · Graphics, Media & Games · Swift
  **NeKI brief:** Builds a camera experience by bridging capture APIs into SwiftUI with Combine-backed state. Useful for understanding preview integration, authorization, capture events, and lifecycle management around UIKit services.
- [Getting Started with Swift Concurrency](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD9mZWF0dXJlPXlvdXR1LmJlJnV0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXImdj1VNmxRdXN0aVRHRSIsInBvc3RfaWQiOiJjMmZkZTdjMS00NjU0LTQ2ODctYWI0MC00NWEyNTI4NTVlMDUiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiOGUyZmQzNDUtYWJjYS00YTA5LThkYTMtNDE2NDVmNzA5OTJhIiwiaWF0IjoxNjc0MDYyNjE3LjcxNiwiaXNzIjoib3JjaGlkIn0.b6NKewbwPA4mJtumWudUDdzfNgnrnE7GRvN53k3htnk) — Tutorial · Topics: Concurrency · Graphics, Media & Games · Swift
  **NeKI brief:** Introduces Swift concurrency concepts and basic async code through practical examples. Useful for understanding async/await, task structure, and the migration mindset before applying concurrency to SwiftUI features.
- [Displaying badges in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3N3aWZ0d2l0aG1hamlkLmNvbS8yMDIxLzExLzEwL2Rpc3BsYXlpbmctYmFkZ2VzLWluLXN3aWZ0dWkvP3V0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiYzJmZGU3YzEtNDY1NC00Njg3LWFiNDAtNDVhMjUyODU1ZTA1IiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6IjhlMmZkMzQ1LWFiY2EtNGEwOS04ZGEzLTQxNjQ1ZjcwOTkyYSIsImlhdCI6MTY3NDA2MjYxNy43MTYsImlzcyI6Im9yY2hpZCJ9.NYiuQKV-vEc3afiCzM1vPbq3lzt7hfLzZx-jfb6yAMU) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows adding badges to SwiftUI navigation and list elements using the platform APIs. Useful for surfacing counts or status indicators while preserving familiar system semantics and compact layouts.
- [Managing Focus in SwiftUI List Views](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3BldGVyZnJpZXNlLmRldi9zd2lmdHVpLWxpc3QtZm9jdXMvP3V0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiYzJmZGU3YzEtNDY1NC00Njg3LWFiNDAtNDVhMjUyODU1ZTA1IiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6IjhlMmZkMzQ1LWFiY2EtNGEwOS04ZGEzLTQxNjQ1ZjcwOTkyYSIsImlhdCI6MTY3NDA2MjYxNy43MTYsImlzcyI6Im9yY2hpZCJ9.fuETOFFkZP3I1Ky8CUEOY227kgB7HVoY1pkS6lZjQjs) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates controlling focus for fields embedded in SwiftUI lists. Useful for form-heavy rows where keyboard navigation, focus transitions, and cell reuse can otherwise produce confusing interaction behavior.

## [SwiftUI Weekly - Issue #82](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-82)

- Published: `2021-11-09T14:18:09.000Z`

**Topics:** App Distribution & Store Operations · Concurrency · Foundation & Data Formats · Product Design · Swift · SwiftUI

**Sections:** News · Submissions now accepted through the holidays · Reading

**NeKI brief:** Safe-area management, redraw decisions, redacted content, and Xcode beta changes provide a foundation for loading UI and layout diagnostics. Use it to distinguish intentional invalidation from unnecessary body recomputation before optimizing.

## [SwiftUI Weekly - Issue #81](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-81)

- Published: `2021-11-01T18:34:46.000Z`

**Topics:** Concurrency · Graphics, Media & Games · Objective-C & Cocoa · Swift · SwiftUI · Xcode

**Sections:** News · Xcode 13.2 beta · Introducing Swift Distributed Actors

**NeKI brief:** Issue 81 covers SwiftUI state, accessibility, and view composition in the early iOS 15 era. Use it to compare environment-driven state and semantic design guidance with current Observation, especially when auditing old screens for update and accessibility regressions.

## [SwiftUI Weekly - Issue #80](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-80)

- Published: `2021-10-25T19:33:34.000Z`

**Topics:** Graphics, Media & Games · Swift · SwiftUI · Testing · Xcode

**Sections:** News · Xcode 13.1 Release Notes · Reading

**NeKI brief:** Issue 80 surveys SwiftUI navigation, layout, and asynchronous work. It is useful for tracing pre-NavigationStack route modeling and identifying where loading, cancellation, and view identity interact in legacy applications.

## [SwiftUI Weekly - Issue #79](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-79)

- Published: `2021-10-18T15:20:48.000Z`

**Topics:** Accessibility · Code Quality · macOS & AppKit · Swift · SwiftUI · UIKit

**Sections:** Reading · API Design · Which of the SwiftUI APIs introduced in iOS 15 are backward compatible?

**NeKI brief:** This issue focuses on SwiftUI animation and layout techniques. Consult it for concrete transition and geometry patterns, then test whether their assumptions about identity, transaction timing, and rendering cost still hold on current SDKs.

## [SwiftUI Weekly - Issue #78](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-78)

- Published: `2021-10-04T18:21:47.000Z`

**Topics:** Accessibility · Apple Platform Ecosystem · Graphics, Media & Games · Swift · SwiftUI · UIKit

**Sections:** Reading · Audio graphs in SwiftUI · Programmatic navigation in SwiftUI

**Selected links:**
- [Audio graphs in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3N3aWZ0d2l0aG1hamlkLmNvbS8yMDIxLzA5LzI5L2F1ZGlvLWdyYXBocy1pbi1zd2lmdHVpLz91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6ImQwODQ4YzM4LWI2YTQtNDFiZC04Mzg0LTU4YzJlNWRjZjE1MSIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiJjNTRlMGI4OS0zZmY3LTQxMzQtYmJkYS01NjNhMDU4Y2QyMDkiLCJpYXQiOjE2NzQwNjI2MTcuNzY5LCJpc3MiOiJvcmNoaWQifQ.829H2GnAJ8KdJW2hjHJYtVQtz26oGDSbPa2yAgm7Cwc) — Article · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Explores visualizing audio data as graphs in SwiftUI, translating signal values into dynamic drawing. Useful for waveform or level displays that need efficient rendering and clear mapping from samples to pixels.
- [The SwiftUI Environment](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy5maXZlc3RhcnMuYmxvZy9hcnRpY2xlcy9zd2lmdHVpLWVudmlyb25tZW50LXByb3BhZ2F0aW9uLz91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6ImQwODQ4YzM4LWI2YTQtNDFiZC04Mzg0LTU4YzJlNWRjZjE1MSIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiJjNTRlMGI4OS0zZmY3LTQxMzQtYmJkYS01NjNhMDU4Y2QyMDkiLCJpYXQiOjE2NzQwNjI2MTcuNzcsImlzcyI6Im9yY2hpZCJ9.HuT9AYMXhtb-Iiu_vZyWQr5EEwI4m_9PWqCDa4hGB-M) — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **NeKI brief:** Explains how SwiftUI environment values propagate dependencies and configuration through a view hierarchy. Useful for designing shared settings and services while keeping injection explicit and previews manageable.
- [SwiftUI Animation Lessons From Building “Time’s Up! Timer”](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2Jsb2cub3ZlcmRlc2lnbmVkLm5ldC9wb3N0cy8yMDIxLTA5LTI5LXN3aWZ0dWktYW5pbWF0aW9uLXRyaWNrcy8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiJkMDg0OGMzOC1iNmE0LTQxYmQtODM4NC01OGMyZTVkY2YxNTEiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiYzU0ZTBiODktM2ZmNy00MTM0LWJiZGEtNTYzYTA1OGNkMjA5IiwiaWF0IjoxNjc0MDYyNjE3Ljc3LCJpc3MiOiJvcmNoaWQifQ.HOtABwqvpucENWdyx01y1LC1rlGOR2qwNfTHI3K1tHc) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Derives SwiftUI animation lessons from building a timer, including timing, transitions, and state-driven motion. Useful for coordinating repeated animations without desynchronizing them from the underlying timer state.
- [Working with Picker in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3NlcmlhbGNvZGVyLmRldi90ZXh0LXR1dG9yaWFscy9zd2lmdHVpL3dvcmtpbmctd2l0aC1waWNrZXItaW4tc3dpZnR1aS8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiJkMDg0OGMzOC1iNmE0LTQxYmQtODM4NC01OGMyZTVkY2YxNTEiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiYzU0ZTBiODktM2ZmNy00MTM0LWJiZGEtNTYzYTA1OGNkMjA5IiwiaWF0IjoxNjc0MDYyNjE3Ljc3LCJpc3MiOiJvcmNoaWQifQ.GDxhVFvzIi2K279lK2aLaUa39LjA6XKFeI8dhh_8QKw) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Covers SwiftUI Picker styles, tags, selection bindings, and common configuration choices. Useful for building typed selection controls that adapt across platforms without coupling feature logic to one visual style.

## [SwiftUI Weekly - Issue #77](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-77)

- Published: `2021-09-27T16:02:11.000Z`

**Topics:** Accessibility · Architecture · Composable Architecture · Concurrency · Swift · SwiftUI

**Sections:** Reading · Accessibility focus in SwiftUI · Structuring platform specific code in SwiftUI

**NeKI brief:** Issue 77 combines SwiftUI collections, bindings, and interaction design. Use it when researching data-driven list updates and selection behavior, paying attention to identity, mutation propagation, and accessibility semantics.

## [SwiftUI Weekly - Issue #76](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-76)

- Published: `2021-09-20T14:24:21.000Z`

**Topics:** Apple Platform Ecosystem · Combine & Reactive Programming · Concurrency · Swift · SwiftUI · Xcode

**Sections:** News · Xcode 13 RC · Reading

**NeKI brief:** This issue presents practical SwiftUI architecture and state-management reading. It helps compare early MVVM and environment patterns with modern Observation, especially around ownership, dependency injection, and previewability.

## [SwiftUI Weekly - Issue #75](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-75)

- Published: `2021-09-14T13:59:13.000Z`

**Topics:** Accessibility · Combine & Reactive Programming · macOS & AppKit · Objective-C & Cocoa · Swift · SwiftUI

**Sections:** Reading · Accessibility rotors in SwiftUI · Advanced SwiftUI Animations - Part 5: Canvas

**NeKI brief:** Issue 75 explores SwiftUI layout and reusable view construction. Follow it to investigate geometry measurement, adaptive composition, and the trade-offs between custom containers and built-in lazy components.

## [SwiftUI Weekly - Issue #74](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-74)

- Published: `2021-09-06T15:57:15.000Z`

**Topics:** Accessibility · App Distribution & Store Operations · Cross-Platform & Web · Graphics, Media & Games · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #74 · News

**Selected links:**
- [The power of accessibilityRepresentation view modifier in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3N3aWZ0d2l0aG1hamlkLmNvbS8yMDIxLzA5LzAxL3RoZS1wb3dlci1vZi1hY2Nlc3NpYmlsaXR5LXJlcHJlc2VudGF0aW9uLXZpZXctbW9kaWZpZXItaW4tc3dpZnR1aS8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiJiMTAyNjk4ZS03OGRlLTQzYmMtOTc1Ni03OGVlZTNhMzNhODAiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiMmJkZDhjZTgtNDNhMS00ZGQxLWFjMzctNjI1ZjQ4ZmFlNjI5IiwiaWF0IjoxNjc0MDYyNjE4LjcwMiwiaXNzIjoib3JjaGlkIn0.jL3cvCsCdVQknDqCNYU58QqVyCcpszasNK_nRC6n9ec) — Article · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Demonstrates accessibilityRepresentation for supplying a semantic accessibility element different from a view’s visual implementation. Useful when custom controls need clear VoiceOver behavior without sacrificing bespoke visuals.
- [Exploring SwiftUI map custom annotations](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2tyaXN0YXBzLm1lL2Jsb2cvc3dpZnR1aS1tYXAtYW5ub3RhdGlvbnMvP3V0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiYjEwMjY5OGUtNzhkZS00M2JjLTk3NTYtNzhlZWUzYTMzYTgwIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6IjJiZGQ4Y2U4LTQzYTEtNGRkMS1hYzM3LTYyNWY0OGZhZTYyOSIsImlhdCI6MTY3NDA2MjYxOC43MDIsImlzcyI6Im9yY2hpZCJ9.FmNElOxlqHay04K6xCOZZmTC_H8zb6EvCdxCVMIIR6Q) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows creating custom annotations in SwiftUI maps and positioning content over geographic coordinates. Useful for map-based features that need branded markers, data-driven selection, and interactive callouts.
- [How to Create Animated Gradients in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy5hcHBjb2RhLmNvbS9hbmltYXRlLWdyYWRpZW50LXN3aWZ0dWkvP3V0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiYjEwMjY5OGUtNzhkZS00M2JjLTk3NTYtNzhlZWUzYTMzYTgwIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6IjJiZGQ4Y2U4LTQzYTEtNGRkMS1hYzM3LTYyNWY0OGZhZTYyOSIsImlhdCI6MTY3NDA2MjYxOC43MDIsImlzcyI6Im9yY2hpZCJ9.tuEqp7q1Ysp-Uv8cwPxbAdMKtQaUVkF-aSqGk-RZIK0) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Builds animated gradients in SwiftUI by changing gradient parameters over time. Useful for expressive backgrounds and loading states while considering redraw cost, contrast, and reduced-motion preferences.
- [BottomSheet](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2dpdGh1Yi5jb20vTHVjYXNNdWNHSC9Cb3R0b21TaGVldD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6ImIxMDI2OThlLTc4ZGUtNDNiYy05NzU2LTc4ZWVlM2EzM2E4MCIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiIyYmRkOGNlOC00M2ExLTRkZDEtYWMzNy02MjVmNDhmYWU2MjkiLCJpYXQiOjE2NzQwNjI2MTguNzAyLCJpc3MiOiJvcmNoaWQifQ.bY3dZwlAKlD9LaDs4GWNpy7JE9E2NUEDp2l57LQRVkI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Provides an open-source BottomSheet implementation for SwiftUI with configurable presentation behavior. Useful when evaluating custom sheet interactions or detents, while checking maintenance, accessibility, and platform compatibility before adoption.

## [SwiftUI Weekly - Issue #73](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-73)

- Published: `2021-08-25T13:20:34.000Z`

**Topics:** Combine & Reactive Programming · Concurrency · Developer Community & Business · Graphics, Media & Games · Swift · SwiftUI

**Sections:** News · My favorite new Swift API from iOS 15 · Reading

**NeKI brief:** This issue covers SwiftUI navigation and platform integration. Use it as a historical reference for route state, deep links, and UIKit boundaries, verifying all APIs against current availability and lifecycle behavior.

## [SwiftUI Weekly - Issue #72](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-72)

- Published: `2021-08-16T21:43:18.000Z`

**Topics:** Developer Career & Practice · Graphics, Media & Games · Swift · SwiftUI · Testing · Xcode

**Sections:** News · What's new in Xcode 13 beta 5 · Reading

**NeKI brief:** Issue 72 focuses on SwiftUI performance and rendering behavior. It offers research leads for profiling body updates, reducing expensive layout work, and distinguishing actual bottlenecks from harmless value-view recomputation.

## [SwiftUI Weekly - Issue #71](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-71)

- Published: `2021-08-09T11:06:22.000Z`

**Topics:** App Distribution & Store Operations · Concurrency · macOS & AppKit · Personal Essays · Swift · SwiftUI

**Sections:** Reading · Implementing Three Column Navigation in SwiftUI · Running tasks concurrently with Swift Concurrency’s async let

**NeKI brief:** This issue examines SwiftUI accessibility and animation patterns. Consult it when designing motion that remains understandable with assistive technologies and reduced-motion settings, while keeping semantic actions separate from decoration.

## [SwiftUI Weekly - Issue #70](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-70)

- Published: `2021-08-02T14:01:12.000Z`

**Topics:** Graphics, Media & Games · macOS & AppKit · Observation & State Management · Swift · SwiftUI · Xcode

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #70 · News

**Selected links:**
- [Create your custom view router with SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3JvbWFuLWlvcy5tZWRpdW0uY29tL2NyZWF0ZS15b3VyLWN1c3RvbS12aWV3LXJvdXRlci13aXRoLXN3aWZ0dWktMi0zLWNjZGUxYWNhMDViZj91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6ImE1NzBjMjkxLTAwNTgtNGQ5Yy1iNzNkLTVkOTdjNGQ5MTA5ZiIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiI5YWNlYThlZi1mYzk4LTQ3NzYtYmY5NC0wZDg4NzdhZmI3NmIiLCJpYXQiOjE2NzQwNjI2MTguNjA4LCJpc3MiOiJvcmNoaWQifQ.FW6MwCna9V5TaY38cvmhYwd6ko-dOEYOQpArbV3bXr4) — Article · Topics: Product Design · Swift · SwiftUI
  **NeKI brief:** Builds a custom SwiftUI view-router abstraction for switching screens. Use it to evaluate explicit route state and navigation ownership when NavigationStack cannot express a legacy flow cleanly.
- [How to show and hide a sidebar in a SwiftUI macOS app](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3NhcnVudy5jb20vcG9zdHMvaG93LXRvLXRvZ2dsZS1zaWRlYmFyLWluLW1hY29zLz91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6ImE1NzBjMjkxLTAwNTgtNGQ5Yy1iNzNkLTVkOTdjNGQ5MTA5ZiIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiI5YWNlYThlZi1mYzk4LTQ3NzYtYmY5NC0wZDg4NzdhZmI3NmIiLCJpYXQiOjE2NzQwNjI2MTguNjA4LCJpc3MiOiJvcmNoaWQifQ.IApUXo-okPnBAjXgfcN97KKTJyRGPcwf0JMLFCMHSE4) — Article · Topics: Product Design · Swift · SwiftUI
  **NeKI brief:** Explains how a macOS SwiftUI sidebar can become unreachable after collapsing and demonstrates recovery through toolbar or command actions. Follow it when testing window navigation states beyond the initial layout.
- [SwiftUI Data Flow playlist](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS9wbGF5bGlzdD9saXN0PVBMdlVXaTV0ZGg5Mnpmc1Y5eFJneDd2VGxBU3ZtclRvcVEmdXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiJhNTcwYzI5MS0wMDU4LTRkOWMtYjczZC01ZDk3YzRkOTEwOWYiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiOWFjZWE4ZWYtZmM5OC00Nzc2LWJmOTQtMGQ4ODc3YWZiNzZiIiwiaWF0IjoxNjc0MDYyNjE4LjYwOCwiaXNzIjoib3JjaGlkIn0.i30UMwNELl4qt5VzeTLua1q1IA4anAJXYp0FHOFHElM) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Uses State, Binding, ObservableObject, StateObject, and EnvironmentObject in practical SwiftUI data-flow examples. Follow it to compare ownership and propagation choices when a view hierarchy has multiple sources of mutable state.
- [SwiftUI Preview Orientation Tutorial](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy5pb3NjcmVhdG9yLmNvbS90dXRvcmlhbHMvc3dpZnR1aS1wcmV2aWV3LW9yaWVudGF0aW9uLXR1dG9yaWFsP3V0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiYTU3MGMyOTEtMDA1OC00ZDljLWI3M2QtNWQ5N2M0ZDkxMDlmIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6IjlhY2VhOGVmLWZjOTgtNDc3Ni1iZjk0LTBkODg3N2FmYjc2YiIsImlhdCI6MTY3NDA2MjYxOC42MDgsImlzcyI6Im9yY2hpZCJ9.BL1o4yaA6KzdggDU85VyJDDODQ0_sUjIuiKo7dlYp6k) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates previewInterfaceOrientation with portrait and landscape variants. Use it to make orientation-specific SwiftUI layout regressions visible during preview review instead of discovering them only on devices.

## [SwiftUI Weekly - Issue #69](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-69)

- Published: `2021-07-26T15:02:52.000Z`

**Topics:** Architecture · Combine & Reactive Programming · Dependency Injection · Swift · SwiftUI · Testing

**Sections:** Reading · Submitting values to SwiftUI view · Dependency Injection in Swift using latest Swift features

**NeKI brief:** Issue 69 discusses SwiftUI controls and data flow. Use it to compare binding, focus, and validation approaches, particularly when migrating form-heavy UIKit screens into value-based views.

## [SwiftUI Weekly - Issue #68](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-68)

- Published: `2021-07-19T14:03:32.000Z`

**Topics:** Cross-Platform & Web · Developer Community & Business · Graphics, Media & Games · Swift · SwiftUI · Xcode

**Sections:** News · What's new in Xcode 13 beta 3 · Reading

**NeKI brief:** This issue surveys SwiftUI layout and reusable components. It is useful for studying how geometry and environment values propagate through hierarchies, and for checking whether custom modifiers preserve predictable identity.

## [SwiftUI Weekly - Issue #67](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-67)

- Published: `2021-07-12T22:30:23.000Z`

**Topics:** Concurrency · Developer Career & Practice · Graphics, Media & Games · Objective-C & Cocoa · Swift · SwiftUI

**Sections:** Reading · Mastering AsyncImage in SwiftUI · How to translate SwiftUI applications

**NeKI brief:** Issue 67 links SwiftUI concurrency with platform APIs. Follow it to investigate task lifetimes, cancellation, and state updates from asynchronous work, then compare the historical patterns with actor isolation today.

## [SwiftUI Weekly - Issue #66](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-66)

- Published: `2021-07-06T10:24:10.000Z`

**Topics:** Code Quality · Concurrency · Developer Community & Business · Graphics, Media & Games · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #66 · Reading

**Selected links:**
- [SwiftUI patterns evolution: view builders](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2ZpdmVzdGFycy5ibG9nL2FydGljbGVzL3N3aWZ0dWktcGF0dGVybnMtdmlldy1idWlsZGVycy8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiIzNmNmNWJjYi1mMDU3LTQzN2EtOWY3Ni1jMDQ0NTc0YWQyYjciLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiZWMyZjUxYTYtZTFjYy00MWFjLThhMTgtZGQxN2QxMTE4ZjYwIiwiaWF0IjoxNjc0MDYyNjc3LjA2MSwiaXNzIjoib3JjaGlkIn0.1iTXRq_oB78yxzsqRJp_rX8sxGAwzmG5SZ-hO6mmvI4) — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Traces how SwiftUI view-builder patterns evolve as APIs become more expressive. Follow it when choosing between generic composition, result builders, and concrete helper views for maintainable screen structure.
- [Dismissing a SwiftUI modal or detail view](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3N3aWZ0YnlzdW5kZWxsLmNvbS9hcnRpY2xlcy9kaXNtaXNzaW5nLXN3aWZ0dWktbW9kYWwtYW5kLWRldGFpbC12aWV3cy8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiIzNmNmNWJjYi1mMDU3LTQzN2EtOWY3Ni1jMDQ0NTc0YWQyYjciLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiZWMyZjUxYTYtZTFjYy00MWFjLThhMTgtZGQxN2QxMTE4ZjYwIiwiaWF0IjoxNjc0MDYyNjc3LjA2MSwiaXNzIjoib3JjaGlkIn0.rkxgLrSjo6nK68tLIiqJ688Xaj4W1CKCjaEFigWV1ks) — Article · Topics: Product Design · Swift · SwiftUI
  **NeKI brief:** Compares dismissal mechanisms for SwiftUI modals and detail views, including environment actions and state-driven presentation. Use it to keep navigation ownership explicit across sheets, navigation stacks, and reusable child views.
- [Getting Started with async/await in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3BldGVyZnJpZXNlLmRldi9zd2lmdHVpLWNvbmN1cnJlbmN5LWVzc2VudGlhbHMtcGFydDEvP3V0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiMzZjZjViY2ItZjA1Ny00MzdhLTlmNzYtYzA0NDU3NGFkMmI3IiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6ImVjMmY1MWE2LWUxY2MtNDFhYy04YTE4LWRkMTdkMTExOGY2MCIsImlhdCI6MTY3NDA2MjY3Ny4wNjEsImlzcyI6Im9yY2hpZCJ9.6Ti6EtUakdORyaUjvr0Y0E9Y7NLJETJnd6ddAaFzkgI) — Article · Topics: Concurrency · Swift · SwiftUI
  **NeKI brief:** Introduces async/await in SwiftUI with task-based asynchronous work and result handling. Follow it when replacing callback code and deciding where view-triggered work should start, cancel, and update state.
- [Build an iOS News App with SwiftUI 3 & NewsAPI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyJnY9TFJuYkZqcTBiVE0iLCJwb3N0X2lkIjoiMzZjZjViY2ItZjA1Ny00MzdhLTlmNzYtYzA0NDU3NGFkMmI3IiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6ImVjMmY1MWE2LWUxY2MtNDFhYy04YTE4LWRkMTdkMTExOGY2MCIsImlhdCI6MTY3NDA2MjY3Ny4wNjEsImlzcyI6Im9yY2hpZCJ9.r7-p50YbFCYfvRxSccrB_jpoMBivOTJRcLwl-txmetU) — Tutorial · Topics: Developer Community & Business · Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.

## [SwiftUI Weekly - Issue #65](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-65)

- Published: `2021-06-28T16:37:19.000Z`

**Topics:** Concurrency · Graphics, Media & Games · Objective-C & Cocoa · Swift · SwiftUI · Xcode

**Sections:** News · What's new in Xcode 13 beta 2 · Reading

**NeKI brief:** Issue 65 connects Xcode 13 beta 2 changes with SwiftUI development, concurrency, and persistence. Use it as a historical snapshot for assessing early async/await adoption, preview tooling, and migration hazards when maintaining code from the Swift 5.5 transition.

## [SwiftUI Weekly - Issue #64](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-64)

- Published: `2021-06-22T09:56:13.000Z`

**Topics:** Apple Platform Ecosystem · Concurrency · Developer Tools · Graphics, Media & Games · Swift · SwiftUI

**Sections:** News · WWDC21: Wrap up and recommended talks · Reading

**NeKI brief:** A WWDC21 wrap-up focused on SwiftUI and concurrency, this issue helps researchers map the announced APIs to practical adoption questions. Compare its recommended sessions with current framework behavior, especially structured concurrency, state flow, and platform availability.

## [SwiftUI Weekly - Issue #63](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-63)

- Published: `2021-06-14T22:35:11.000Z`

**Topics:** Apple Platform Ecosystem · Concurrency · Cross-Platform & Web · macOS & AppKit · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #63 · Spokestack - AutoML tools that put custom voice into software

**Selected links:**
- [Spokestack - AutoML tools that put custom voice into software](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy5zcG9rZXN0YWNrLmlvLz91dG1fY2FtcGFpZ249bWFrZXJfbGF1bmNoX1BBSUQmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPXN3aWZ0dWlfd2Vla2x5IiwicG9zdF9pZCI6Ijk4NTQyZmUzLTllOWYtNGZmOC05OWMwLTQ0ODc1NzNiZDY0MiIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiJlMGQxNjc5Mi0xZmY1LTRhMjEtOTg0Yy00ZTk0MThiOWEzOWUiLCJpYXQiOjE2NzQwNjI2NzcuMDEsImlzcyI6Im9yY2hpZCJ9.atUK69hH2ROd-1KMu7E8qDPRvdFtWbAB5xcDUbJ8hiU) — Article · Topics: AI Development · App Intents & System Surfaces · Cross-Platform & Web
  **NeKI brief:** Presents Spokestack tools for adding custom voice interfaces and models to software. Use it as a discovery lead when evaluating speech-triggered features, model training workflow, and service dependencies.
- [Building a music recognization app in SwiftUI with ShazamKit](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3N3YXBuYW5pbGRob2wubWVkaXVtLmNvbS9idWlsZGluZy1hLW11c2ljLXJlY29nbml6YXRpb24tYXBwLWluLXN3aWZ0dWktd2l0aC1zaGF6YW1raXQtN2NhYjc2NDA3ZDEwP3V0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiOTg1NDJmZTMtOWU5Zi00ZmY4LTk5YzAtNDQ4NzU3M2JkNjQyIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6ImUwZDE2NzkyLTFmZjUtNGEyMS05ODRjLTRlOTQxOGI5YTM5ZSIsImlhdCI6MTY3NDA2MjY3Ny4wMSwiaXNzIjoib3JjaGlkIn0.D1X3KuG_ZZVBpnjLs42Pwiu20YFyMkC-z5viuvXke6c) — Tutorial · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI music-recognition app around ShazamKit. Follow it to see how capture, matching results, permissions, and asynchronous updates are connected to observable UI state.
- [SwiftUI List Bindings - Behind the Scenes](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3BldGVyZnJpZXNlLmRldi9zd2lmdHVpLWxpc3QtaXRlbS1iaW5kaW5ncy1iZWhpbmQtdGhlLXNjZW5lcy8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiI5ODU0MmZlMy05ZTlmLTRmZjgtOTljMC00NDg3NTczYmQ2NDIiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiZTBkMTY3OTItMWZmNS00YTIxLTk4NGMtNGU5NDE4YjlhMzllIiwiaWF0IjoxNjc0MDYyNjc3LjAxLCJpc3MiOiJvcmNoaWQifQ.cVZAeLciuou9hqP3-whh96OkazPcGkriDvNEXgvfY4c) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Explains how SwiftUI list bindings derive writable access to collection elements. Use it when editing rows in place and when diagnosing identity or mutation behavior in ForEach-driven forms.
- [Setup SwiftUI App with Firebase SPM](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD9mZWF0dXJlPXlvdXR1LmJlJnV0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXImdj1sLWlOMGtZX2JtZyIsInBvc3RfaWQiOiI5ODU0MmZlMy05ZTlmLTRmZjgtOTljMC00NDg3NTczYmQ2NDIiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiZTBkMTY3OTItMWZmNS00YTIxLTk4NGMtNGU5NDE4YjlhMzllIiwiaWF0IjoxNjc0MDYyNjc3LjAxLCJpc3MiOiJvcmNoaWQifQ.WIHfKf395U66uMHaK5JZw1hIXIbu9ISyoHi28IKOEX4) — Tutorial · Topics: Swift · Swift Package Manager · SwiftUI
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.

## [SwiftUI Weekly - Issue #62](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-62)

- Published: `2021-06-11T15:16:38.000Z`

**Topics:** Apple Platform Ecosystem · Combine & Reactive Programming · Concurrency · Foundation & Data Formats · Swift · SwiftUI

**Sections:** News · What is new in SwiftUI after WWDC21 · What's new in SwiftUI

**NeKI brief:** This post-WWDC21 issue surveys what changed in SwiftUI, including concurrency and system-surface work. Use it to locate the original explanations of new APIs, then verify lifecycle, availability, and migration guidance against current Apple documentation.

## [SwiftUI Weekly - Issue #61](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-61)

- Published: `2021-05-31T16:20:16.000Z`

**Topics:** Apple Platform Ecosystem · Combine & Reactive Programming · Concurrency · macOS & AppKit · Swift · SwiftUI

**Sections:** News · What's new in Swift 5.5? · Reading

**NeKI brief:** Issue 61 reviews Swift 5.5 alongside SwiftUI concurrency, testing, and UIKit interoperability. Follow it when comparing early async task patterns and observable state practices, particularly where UI tests and actor isolation meet legacy view-controller code.

## [SwiftUI Weekly - Issue #60](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-60)

- Published: `2021-05-24T13:27:43.000Z`

**Topics:** Apple Platform Ecosystem · Developer Community & Business · Graphics, Media & Games · Objective-C & Cocoa · Swift · SwiftUI

**Sections:** News · Apple’s all-online Worldwide Developers Conference kicks off June 7 with… · Reading

**NeKI brief:** This issue pairs WWDC preparation with Core Data and SwiftUI reading. It offers a concrete route into managed-object observation, persistence boundaries, and view updates, useful when evaluating whether a data model should remain Core Data-backed or be modernized.

## [SwiftUI Weekly - Issue #59](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-59)

- Published: `2021-05-17T14:46:35.000Z`

**Topics:** Apple Platform Ecosystem · Combine & Reactive Programming · Networking · Performance · Swift · SwiftUI

**Sections:** News · Wishes for WWDC 2021 · Reading

**NeKI brief:** Issue 59 collects WWDC wishes around SwiftUI networking and performance. Use it as a retrospective checklist: identify pain points such as loading state, cancellation, and rendering cost, then compare the proposed solutions with APIs introduced since 2021.

## [SwiftUI Weekly - Issue #58](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-58)

- Published: `2021-05-10T15:49:17.000Z`

**Topics:** Combine & Reactive Programming · Concurrency · Developer Career & Practice · Graphics, Media & Games · Swift · SwiftUI

**Sections:** Reading · Chaining publishers with Combine in Swift · A TextFieldStyle API preview!

**NeKI brief:** This issue examines Combine publisher chaining and an early TextFieldStyle preview. It is valuable for understanding how reactive pipelines reached SwiftUI controls, including error propagation, cancellation, and styling seams that later APIs changed.

## [SwiftUI Weekly - Issue #57](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-57)

- Published: `2021-05-03T16:57:45.000Z`

**Topics:** Combine & Reactive Programming · Graphics, Media & Games · Objective-C & Cocoa · Swift · Swift Package Manager · SwiftUI

**Sections:** News · What's new in Swift Package Manager in Swift 5.4 · Reading

**NeKI brief:** Issue 57 focuses on Swift Package Manager updates and composable architecture around SwiftUI. Consult it when studying dependency modularization, reducer-driven state, and Xcode package workflows, while treating version-specific package behavior as historical context.

## [SwiftUI Weekly - Issue #56](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-56)

- Published: `2021-04-26T20:19:20.000Z`

**Topics:** Combine & Reactive Programming · Graphics, Media & Games · Hardware & Devices · Swift · SwiftUI · Xcode

**Sections:** News · What’s new in Swift 5.4? · Reading

**Selected links:**
- [Getting Started with Combine](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD9mZWF0dXJlPXlvdXR1LmJlJnV0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXImdj1YMm0wZjJOb0IxMCIsInBvc3RfaWQiOiI3NzBkNzMwYy05ZmNkLTRlOTItYWVjNi01YTJjOGM5YjcwZjgiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiYjIzMDBmZWMtNDg2NC00YTRjLWIzM2UtN2JiZDlmNTcwMjUwIiwiaWF0IjoxNjc0MDYyNjc4LjI0MiwiaXNzIjoib3JjaGlkIn0.yG7_Fvr4s6AVhNrkvo-hVvyg2Qj5YZhIkX4eTkhsyG4) — Tutorial · Topics: App Distribution & Store Operations · Combine & Reactive Programming · Graphics, Media & Games
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Handling Keyboard & Pointer Interactions in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy5yYXl3ZW5kZXJsaWNoLmNvbS8yMDg3OTkwNC1oYW5kbGluZy1rZXlib2FyZC1wb2ludGVyLWludGVyYWN0aW9ucy1pbi1zd2lmdHVpP3V0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiNzcwZDczMGMtOWZjZC00ZTkyLWFlYzYtNWEyYzhjOWI3MGY4IiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6ImIyMzAwZmVjLTQ4NjQtNGE0Yy1iMzNlLTdiYmQ5ZjU3MDI1MCIsImlhdCI6MTY3NDA2MjY3OC4yNDIsImlzcyI6Im9yY2hpZCJ9.KQBda0GJii5RtQ5IpDlivuTHRk_pCnLv_SgEkH4Gt_0) — Article · Topics: Hardware & Devices · Swift · SwiftUI
  **NeKI brief:** Covers keyboard shortcuts and pointer interactions in SwiftUI across desktop-style inputs. Use it when making controls usable with hardware interaction while retaining sensible touch and accessibility behavior.
- [Four ways to customize TextFields](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2ZpdmVzdGFycy5ibG9nL2FydGljbGVzL2hvdy10by1jdXN0b21pemUtdGV4dGZpZWxkcy8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiI3NzBkNzMwYy05ZmNkLTRlOTItYWVjNi01YTJjOGM5YjcwZjgiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiYjIzMDBmZWMtNDg2NC00YTRjLWIzM2UtN2JiZDlmNTcwMjUwIiwiaWF0IjoxNjc0MDYyNjc4LjI0MiwiaXNzIjoib3JjaGlkIn0.gobttufJeXoOsuvQO-Us1VSJNOPNRwAmFKxfGKM6SvY) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Compares four techniques for customizing SwiftUI TextField appearance and behavior. Use it to choose an appropriate styling boundary without sacrificing focus, keyboard, accessibility, or platform conventions.
- [Drop Shadow in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3NlcmlhbGNvZGVyLmRldi9zd2lmdHVpL2Ryb3Atc2hhZG93LWluLXN3aWZ0dWkvP3V0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiNzcwZDczMGMtOWZjZC00ZTkyLWFlYzYtNWEyYzhjOWI3MGY4IiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6ImIyMzAwZmVjLTQ4NjQtNGE0Yy1iMzNlLTdiYmQ5ZjU3MDI1MCIsImlhdCI6MTY3NDA2MjY3OC4yNDIsImlzcyI6Im9yY2hpZCJ9.0amqxZbViRGiPVW7EIIbmiqwXhMogdnZK4xQ_ZwaX_c) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains SwiftUI shadow parameters and their effect on rendered surfaces. Follow it when tuning elevation cues and checking how radius, offset, and opacity interact with clipping and compositing.

## [SwiftUI Weekly - Issue #55](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-55)

- Published: `2021-04-19T16:53:03.000Z`

**Topics:** Accessibility · Architecture · Composable Architecture · Graphics, Media & Games · Swift · SwiftUI

**Sections:** Reading · Accessibility actions in SwiftUI · SwiftUI Aurora Background Animation

**NeKI brief:** Issue 55 highlights accessibility actions and an animated Aurora background. Use it to contrast semantic actions with decorative animation, checking how custom accessibility actions, motion settings, and composable visual effects affect inclusive SwiftUI interfaces.

## [SwiftUI Weekly - Issue #54](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-54)

- Published: `2021-04-12T21:25:15.000Z`

**Topics:** Apple Platform Ecosystem · Combine & Reactive Programming · macOS & AppKit · Observation & State Management · Swift · SwiftUI

**Sections:** News · How to Become an iOS Developer in 2021 · Reading

**NeKI brief:** This issue surveys becoming an iOS developer while discussing SwiftUI networking and architecture. Its research value is the juxtaposition of foundational app structure with real data flow, useful for evaluating onboarding material against production dependency and state boundaries.

## [SwiftUI Weekly - Issue #53](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-53)

- Published: `2021-04-05T15:38:12.000Z`

**Topics:** Apple Platform Ecosystem · Core Data · Foundation & Data Formats · Persistence & Synchronisation · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #53 · News

**Selected links:**
- [Core Data and SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2RhdmVkZWxvbmcuY29tL2Jsb2cvMjAyMS8wNC8wMy9jb3JlLWRhdGEtYW5kLXN3aWZ0dWkvP3V0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiNDc4NmJhYzAtODVlZi00ZDNlLTg4YTgtMGRmOWNmOWRkOWI5IiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6ImVmYmMxZmZhLWQ1M2UtNGIzNC04N2M2LTkyNDE2MjMwZWE2ZSIsImlhdCI6MTY3NDA2MjY3OC4yMjMsImlzcyI6Im9yY2hpZCJ9.EbooE-IrTlRQIDyUJlXQ2lH3GHe2qC85Z_zpQIXJqZI) — Article · Topics: Core Data · Swift · SwiftUI
  **NeKI brief:** Connects Core Data with SwiftUI state updates. Use it when fetched objects, context changes, and view identity need coordination in a persistence-backed interface.
- [TextEditor in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3NlcmlhbGNvZGVyLmRldi9zd2lmdHVpL3RleHRlZGl0b3ItaW4tc3dpZnR1aS8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiI0Nzg2YmFjMC04NWVmLTRkM2UtODhhOC0wZGY5Y2Y5ZGQ5YjkiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiZWZiYzFmZmEtZDUzZS00YjM0LTg3YzYtOTI0MTYyMzBlYTZlIiwiaWF0IjoxNjc0MDYyNjc4LjIyMywiaXNzIjoib3JjaGlkIn0.u3i56nvErNV1R99eNjnpRUxlbWhqD68-YdwEQtyYvVs) — Article · Topics: Product Design · Swift · SwiftUI
  **NeKI brief:** Demonstrates configuring SwiftUI TextEditor for multiline input and presentation. Follow it when building editors that need padding, focus, typography, and scrolling behavior beyond a single-line TextField.
- [pure-swift-ui](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2dpdGh1Yi5jb20vQ29kZVNsaWNpbmcvcHVyZS1zd2lmdC11aT91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6IjQ3ODZiYWMwLTg1ZWYtNGQzZS04OGE4LTBkZjljZjlkZDliOSIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiJlZmJjMWZmYS1kNTNlLTRiMzQtODdjNi05MjQxNjIzMGVhNmUiLCJpYXQiOjE2NzQwNjI2NzguMjIzLCJpc3MiOiJvcmNoaWQifQ.9fhNu0spGUh4kFzTo_hmUMgdLB4CGkHrWfnx16glS2Q) — Article · Topics: Swift · Swift Package Manager · SwiftUI
  **NeKI brief:** Provides a pure-SwiftUI component implementation and accompanying source to study. Use it as a code reference for composing reusable primitives without UIKit dependencies, while checking its historical API assumptions.
- [How to Use ScrollViewReader to Perform Programmatic Scrolling](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy5hcHBjb2RhLmNvbS9zY3JvbGx2aWV3cmVhZGVyLz91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6IjQ3ODZiYWMwLTg1ZWYtNGQzZS04OGE4LTBkZjljZjlkZDliOSIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiJlZmJjMWZmYS1kNTNlLTRiMzQtODdjNi05MjQxNjIzMGVhNmUiLCJpYXQiOjE2NzQwNjI2NzguMjIzLCJpc3MiOiJvcmNoaWQifQ.FuIWlaWirmmXTnkLrmaJ-wTm9fNEKD8JKryMjTTCpPg) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows ScrollViewReader driving programmatic movement to identified content. Use it for chat jumps, deep links, and navigation-driven scrolling, while accounting for stable IDs and timing of target creation.

## [SwiftUI Weekly - Issue #52](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-52)

- Published: `2021-03-29T17:21:08.000Z`

**Topics:** App Intents & System Surfaces · App Services & Extensions · Combine & Reactive Programming · Swift · SwiftUI · Testing

**Sections:** News · Celebrating Women’s History Month · SwiftOnTap

**Selected links:**
- [Using UIKit in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyJnY9VFozLWlRNDYyUTgiLCJwb3N0X2lkIjoiY2ZmNjI0MjctMTQ0My00ODBmLTkxNjctNTg3OTQ2OTgwMTlkIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6ImExZDI5ZjUzLTEzOWItNDQzYy04YmY0LWNjMGZhYmI3M2ZmMiIsImlhdCI6MTY3NDA2MjY3OC4zNzIsImlzcyI6Im9yY2hpZCJ9.Ms9T22gA8v-B9mg2K07lk6iROPTaS6dgk8NXZW5y1JY) — Tutorial · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [UI Testing using Page Object pattern in Swift](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3N3aWZ0d2l0aG1hamlkLmNvbS8yMDIxLzAzLzI0L3VpLXRlc3RpbmctdXNpbmctcGFnZS1vYmplY3QtcGF0dGVybi1pbi1zd2lmdC8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiJjZmY2MjQyNy0xNDQzLTQ4MGYtOTE2Ny01ODc5NDY5ODAxOWQiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiYTFkMjlmNTMtMTM5Yi00NDNjLThiZjQtY2MwZmFiYjczZmYyIiwiaWF0IjoxNjc0MDYyNjc4LjM3MiwiaXNzIjoib3JjaGlkIn0.olUbTNfXEn-CkpeMcfiwqOX22xZeNYdenz5YGlU08Po) — Article · Topics: Swift · Testing
  **NeKI brief:** Applies the Page Object pattern to Swift UI tests. Use it to isolate accessibility queries and interaction details from test scenarios, improving maintenance as screen structure changes.
- [How to Create iOS 14 Widgets With WidgetKit](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2V4eXRlLmNvbS9ibG9nL2hvdy10by1jcmVhdGUtd2lkZ2V0cy13aXRoLXdpZGdldGtpdD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6ImNmZjYyNDI3LTE0NDMtNDgwZi05MTY3LTU4Nzk0Njk4MDE5ZCIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiJhMWQyOWY1My0xMzliLTQ0M2MtOGJmNC1jYzBmYWJiNzNmZjIiLCJpYXQiOjE2NzQwNjI2NzguMzcyLCJpc3MiOiJvcmNoaWQifQ.oxFvSu5jv-Gz7PUZapxW-Nfadb-f5DpSLiMhaLqq2b4) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds an iOS 14 WidgetKit extension and its timeline content. Follow it to understand provider configuration, placeholder snapshots, and the constraints that distinguish widget rendering from an app scene.
- [How to show and hide content with DisclosureGroup using SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2tyaXN0YXBzLm1lL2Jsb2cvc3dpZnR1aS1kaXNjbG9zdXJlLWdyb3VwLz91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6ImNmZjYyNDI3LTE0NDMtNDgwZi05MTY3LTU4Nzk0Njk4MDE5ZCIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiJhMWQyOWY1My0xMzliLTQ0M2MtOGJmNC1jYzBmYWJiNzNmZjIiLCJpYXQiOjE2NzQwNjI2NzguMzcyLCJpc3MiOiJvcmNoaWQifQ.XGqJI5rz7okqGMzUugt-QYYr67_xmWIMotyOfDzWGns) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates using DisclosureGroup to reveal and hide secondary content in SwiftUI. Follow it when a compact mobile screen needs progressive disclosure, and compare the resulting interaction with navigation-based detail rather than assuming every detail belongs on a new screen.

## [SwiftUI Weekly - Issue #51](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-51)

- Published: `2021-03-22T16:15:22.000Z`

**Topics:** Accessibility · Graphics, Media & Games · Swift · SwiftUI · Testing · Xcode

**Sections:** News · Trojanized Xcode project targeting Apple developers found in the wild · Reading

**NeKI brief:** Issue 51 combines Swift 5.4, testing, accessibility, and state-management material. Use it to trace early guidance for bindings, focus, and test structure, then identify which assumptions changed with newer Observation and Swift Testing tools.

## [SwiftUI Weekly - Issue #50](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-50)

- Published: `2021-03-15T20:06:20.000Z`

**Topics:** Combine & Reactive Programming · Cross-Platform & Web · Objective-C & Cocoa · Swift · SwiftUI · Xcode

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #50 · Reading

**Selected links:**
- [Mastering SwiftUI previews](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3N3aWZ0d2l0aG1hamlkLmNvbS8yMDIxLzAzLzEwL21hc3RlcmluZy1zd2lmdHVpLXByZXZpZXdzLz91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6IjBmMzM5Yzk1LTMzNjctNDhhOS1iODNhLTcxZWY3NDY2NzhjNiIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiI0NGJjYmRjNS1mZTMzLTQwNWQtYTA1My02ZWM5NDQ0YjkyYjciLCJpYXQiOjE2NzQwNjI2NzguMjMyLCJpc3MiOiJvcmNoaWQifQ.-cW0Sxekc-wVFWgUcS3VtBd3-q3F6zPpF_8T-mHrRNE) — Article · Topics: Swift · SwiftUI · Xcode
  **NeKI brief:** Covers SwiftUI preview configuration for multiple states and environments. Use it when previews should expose loading, errors, localization, or dynamic-type issues before a simulator run.
- [Timer App Clone](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyJnY9cVNMdk5HaU5fcjAiLCJwb3N0X2lkIjoiMGYzMzljOTUtMzM2Ny00OGE5LWI4M2EtNzFlZjc0NjY3OGM2IiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6IjQ0YmNiZGM1LWZlMzMtNDA1ZC1hMDUzLTZlYzk0NDRiOTJiNyIsImlhdCI6MTY3NDA2MjY3OC4yMzgsImlzcyI6Im9yY2hpZCJ9.YKWs6zmCgJceKFjjkHQAcH_p5XFr2sI41lfv9Kg_sVg) — Article · Topics: AI Development · Combine & Reactive Programming · Swift
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [How to use View protocol in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL29ubXl3YXkxMzMuY29tL3Bvc3RzL2hvdy10by11c2Utdmlldy1wcm90b2NvbC1pbi1zd2lmdHVpLz91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6IjBmMzM5Yzk1LTMzNjctNDhhOS1iODNhLTcxZWY3NDY2NzhjNiIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiI0NGJjYmRjNS1mZTMzLTQwNWQtYTA1My02ZWM5NDQ0YjkyYjciLCJpYXQiOjE2NzQwNjI2NzguMjM0LCJpc3MiOiJvcmNoaWQifQ.M-mV6XmzW39B3obe4RaWxrEVt5nbBCEM-OWkqzUn6Cw) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains the SwiftUI View protocol and its associated-type constraints. Follow it when designing generic view APIs and deciding when opaque return types or type erasure are justified.
- [How to Scan Images and Perform Text Recognition in SwiftUI Using VisionKit](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy5hcHBjb2RhLmNvbS9zd2lmdHVpLXRleHQtcmVjb2duaXRpb24vP3V0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiMGYzMzljOTUtMzM2Ny00OGE5LWI4M2EtNzFlZjc0NjY3OGM2IiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6IjQ0YmNiZGM1LWZlMzMtNDA1ZC1hMDUzLTZlYzk0NDRiOTJiNyIsImlhdCI6MTY3NDA2MjY3OC4yMzgsImlzcyI6Im9yY2hpZCJ9.O97HMefQ6Mn39x_t3PthItM1avhhlw85WZXhAUsSaU0) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Combines SwiftUI with VisionKit image scanning and text recognition. Use it to reason about camera or photo authorization, result delivery, and presenting recognized text without blocking the view hierarchy.

## [SwiftUI Weekly - Issue #49](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-49)

- Published: `2021-03-08T15:59:36.000Z`

**Topics:** Graphics, Media & Games · macOS & AppKit · Maps & Location · Observation & State Management · Swift · SwiftUI

**Sections:** Reading · FocusedValue and FocusedBinding property wrappers in SwiftUI · Quick tips on embracing @ViewBuilder

**NeKI brief:** Issue 49 explores FocusedValue and FocusedBinding plus ViewBuilder patterns. Consult it when designing command or focus propagation across scenes, and when deciding whether builder-based composition improves readability without obscuring identity and state ownership.

## [SwiftUI Weekly - Issue #48](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-48)

- Published: `2021-03-01T13:49:29.000Z`

**Topics:** Core Data · macOS & AppKit · Maps & Location · Product Design · Swift · SwiftUI

**Sections:** Reading · AppKit is Done · SwiftUI patterns: passing & accepting views

**Selected links:**
- [Build Complete Apple Watch Tasks App Clone in WatchOS, SwiftUI with CoreData](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyJnY9OVFxdzU5NXFkY0UiLCJwb3N0X2lkIjoiZjhkYzQzOWQtNjdhOS00N2IwLWI0NzEtOTE2YzY0MWZlN2FjIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6IjNmMDQyMTgxLWQ3NWUtNGE0ZC1hNmE5LWJjM2UwYjBlYTBkZiIsImlhdCI6MTY3NDA2MjY3OC44OTUsImlzcyI6Im9yY2hpZCJ9.WcabseSQh2BOGdp0_x6eltLYiVZeTSCbK1h_Kcxqhs4) — Tutorial · Topics: Core Data · Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Using UIKit Components in SwiftUI (Coordinators)](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyJnY9V29KdHJsREJseVkiLCJwb3N0X2lkIjoiZjhkYzQzOWQtNjdhOS00N2IwLWI0NzEtOTE2YzY0MWZlN2FjIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6IjNmMDQyMTgxLWQ3NWUtNGE0ZC1hNmE5LWJjM2UwYjBlYTBkZiIsImlhdCI6MTY3NDA2MjY3OC44OTUsImlzcyI6Im9yY2hpZCJ9.61EuLk6HarMsg30D45ewI7xYWDhIoZOmzg6CjyKYvDE) — Article · Topics: Navigation & Deep Linking · Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [AppKit is Done](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2tlYW4uYmxvZy9wb3N0L2FwcGtpdC1pcy1kb25lP3V0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiZjhkYzQzOWQtNjdhOS00N2IwLWI0NzEtOTE2YzY0MWZlN2FjIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6IjNmMDQyMTgxLWQ3NWUtNGE0ZC1hNmE5LWJjM2UwYjBlYTBkZiIsImlhdCI6MTY3NDA2MjY3OC44OTQsImlzcyI6Im9yY2hpZCJ9.DGocxcXaFPcCXGsnsZ3eHNT1uJHhzVUovNZuaulm2lo) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Reflects on replacing AppKit in a macOS application and the practical limits of a SwiftUI-first architecture. Use it to assess migration scope, platform gaps, and maintenance costs rather than as a universal prescription.
- [SwiftUI patterns: passing & accepting views](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2ZpdmVzdGFycy5ibG9nL3N3aWZ0dWkvc3dpZnR1aS1wYXR0ZXItcGFzc2luZy12aWV3cy5odG1sP3V0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiZjhkYzQzOWQtNjdhOS00N2IwLWI0NzEtOTE2YzY0MWZlN2FjIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6IjNmMDQyMTgxLWQ3NWUtNGE0ZC1hNmE5LWJjM2UwYjBlYTBkZiIsImlhdCI6MTY3NDA2MjY3OC44OTUsImlzcyI6Im9yY2hpZCJ9.lVjIm8QCT5uZXjaxGE1OmhrIdaJW475GkX_coG0Bsn8) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows patterns for passing view content into SwiftUI components with generic closures and builders. Follow it when designing container APIs that remain flexible without erasing useful type information.

## [SwiftUI Weekly - Issue #47](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-47)

- Published: `2021-02-23T19:43:19.000Z`

**Topics:** Combine & Reactive Programming · Developer Community & Business · Graphics, Media & Games · Swift · Swift Package Manager · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #47 · Reading

**Selected links:**
- [Pass Data Between Views with SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2xlYXJuYXBwbWFraW5nLmNvbS9wYXNzLWRhdGEtYmV0d2Vlbi12aWV3cy1zd2lmdHVpLWhvdy10by8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiJmYjdhOWIwMi05ZmIyLTQxYmQtOWE0ZS0zNGNjYmMzMjNmNDEiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiMDg1YWFlNzgtZjRkZC00OTU1LTgwMDYtNDJmYjBjNzEyY2E0IiwiaWF0IjoxNjc0MDYyNjc4LjQxOSwiaXNzIjoib3JjaGlkIn0.KzVZKR_YP_qh4MqxWhd3sEBAT-A1BIVJE-LJtoUxcOE) — Tutorial · Topics: Product Design · Swift · SwiftUI
  **NeKI brief:** Compares SwiftUI techniques for passing values and bindings between views. Follow it when selecting one-way data, two-way mutation, or shared observable state for a particular ownership relationship.
- [Build a news app in SwiftUI 2.0 (Combine, API, MVVM & Swift Package Manager)](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyJnY9TTJwc1gtSndIZEUiLCJwb3N0X2lkIjoiZmI3YTliMDItOWZiMi00MWJkLTlhNGUtMzRjY2JjMzIzZjQxIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6IjA4NWFhZTc4LWY0ZGQtNDk1NS04MDA2LTQyZmIwYzcxMmNhNCIsImlhdCI6MTY3NDA2MjY3OC40MTksImlzcyI6Im9yY2hpZCJ9.9_MYRo5QPnk2BAP2P8aD_71Ckd92WPNekkK-uesvp78) — Tutorial · Topics: Swift · Swift Package Manager · SwiftUI
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Custom Popup in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy52YWRpbWJ1bGF2aW4uY29tL3N3aWZ0dWktcG9wdXAtc2hlZXQtcG9wb3Zlci8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiJmYjdhOWIwMi05ZmIyLTQxYmQtOWE0ZS0zNGNjYmMzMjNmNDEiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiMDg1YWFlNzgtZjRkZC00OTU1LTgwMDYtNDJmYjBjNzEyY2E0IiwiaWF0IjoxNjc0MDYyNjc4LjQxOSwiaXNzIjoib3JjaGlkIn0.8S2Wpqt2kk7toTujC4e9kEtdYGupda-DEZMzXYZY2_M) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Implements custom popup, sheet, and popover presentation patterns in SwiftUI. Use it when system presentation APIs do not match the required overlay geometry, dismissal behavior, or interaction model.
- [The First 50 Daily Coding Tips (Swift and SwiftUI)](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3R5cGVzYWZlbHkuc3Vic3RhY2suY29tL3AvdGhlLWZpcnN0LTUwLWRhaWx5LWNvZGluZy10aXBzP3V0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiZmI3YTliMDItOWZiMi00MWJkLTlhNGUtMzRjY2JjMzIzZjQxIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6IjA4NWFhZTc4LWY0ZGQtNDk1NS04MDA2LTQyZmIwYzcxMmNhNCIsImlhdCI6MTY3NDA2MjY3OC40MTksImlzcyI6Im9yY2hpZCJ9.UQjJY24uGDY80gH1Qr6Y2ZFhEYg6xqpNqd4K5EMIdAU) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Collects short Swift and SwiftUI coding tips spanning syntax and everyday implementation decisions. Use it as a review checklist for small improvements, verifying older examples against current SDK behavior.

## [SwiftUI Weekly - Issue #46](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-46)

- Published: `2021-02-15T11:27:02.000Z`

**Topics:** Architecture · Combine & Reactive Programming · Hardware & Devices · Objective-C & Cocoa · Swift · SwiftUI

**Sections:** Reading · SwiftUI keyboard avoidance · @ObservedObject and Friends in SwiftUI

**NeKI brief:** This issue focuses on keyboard avoidance and the ObservedObject family. It helps researchers compare environmental keyboard geometry with object lifetime rules, particularly when migrating UIKit forms and preventing duplicated subscriptions or unexpectedly recreated models.

## [SwiftUI Weekly - Issue #45](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-45)

- Published: `2021-02-08T14:56:00.000Z`

**Topics:** Combine & Reactive Programming · Observation & State Management · Product Design · Swift · SwiftUI · Testing

**Sections:** News · What’s new in Swift 5.4? · Reading

**NeKI brief:** Issue 45 reviews Swift 5.4 and SwiftUI architecture, testing, and concurrency. Use it to locate early discussions of async behavior and test seams, then validate whether those patterns remain sound under actors, Sendable checking, and current test frameworks.

## [SwiftUI Weekly - Issue #44](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-44)

- Published: `2021-02-02T12:45:33.000Z`

**Topics:** Combine & Reactive Programming · Hardware & Devices · Swift · SwiftUI · Testing · Xcode

**Sections:** News · Xcode 12.5 Beta is here! · Reading

**NeKI brief:** This issue reports Xcode 12.5 beta and related SwiftUI testing material. It is useful for historical build compatibility investigations, especially when reproducing preview, XCTest, or SDK behavior tied to that toolchain generation.

## [SwiftUI Weekly - Issue #43](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-43)

- Published: `2021-01-26T13:13:48.000Z`

**Topics:** Observation & State Management · Performance · Swift · SwiftUI · UIKit · Xcode

**Sections:** Reading · Profiling SwiftUI app using Instruments · SwiftUI patterns: @Bindings

**Selected links:**
- [Profiling SwiftUI app using Instruments](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3N3aWZ0d2l0aG1hamlkLmNvbS8yMDIxLzAxLzIwL3Byb2ZpbGluZy1zd2lmdHVpLWFwcC11c2luZy1pbnN0cnVtZW50cy8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiJmNDMyNzc3Ny02M2Q2LTQ1MDQtOWVkMC1lYTgwYzM4ZmVlZDUiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiMjVjODkyZTUtYTM5OC00YWVmLWFkMWEtMzYzZTkzNWE1OGJhIiwiaWF0IjoxNjc0MDYyNjc5LjQ1OSwiaXNzIjoib3JjaGlkIn0.yFE0lXxlheNBniRXd2cVmx609ueoWFP89URqNlmr9lo) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Uses Instruments to profile SwiftUI performance. Use it when a view-update or rendering problem needs measured call stacks and allocation evidence instead of intuition about declarative UI cost.
- [SwiftUI patterns: @Bindings](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2ZpdmVzdGFycy5ibG9nL3N3aWZ0dWkvc3dpZnR1aS1wYXR0ZXJucy1iaW5kaW5ncy5odG1sP3V0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiZjQzMjc3NzctNjNkNi00NTA0LTllZDAtZWE4MGMzOGZlZWQ1IiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6IjI1Yzg5MmU1LWEzOTgtNGFlZi1hZDFhLTM2M2U5MzVhNThiYSIsImlhdCI6MTY3NDA2MjY3OS40NTksImlzcyI6Im9yY2hpZCJ9.VLZGw91JCdjf5JQ53J3emP3PShSceBSMPRXHzIC-ydM) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Explains SwiftUI Binding patterns for exposing controlled mutable state to child views. Use it to separate ownership from editing capability and avoid introducing shared state where a projection is enough.
- [Applying rounded corners to a UIKit or SwiftUI view](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy5zd2lmdGJ5c3VuZGVsbC5jb20vYXJ0aWNsZXMvcm91bmRlZC1jb3JuZXJzLXVpa2l0LXN3aWZ0dWkvP3V0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiZjQzMjc3NzctNjNkNi00NTA0LTllZDAtZWE4MGMzOGZlZWQ1IiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6IjI1Yzg5MmU1LWEzOTgtNGFlZi1hZDFhLTM2M2U5MzVhNThiYSIsImlhdCI6MTY3NDA2MjY3OS40NiwiaXNzIjoib3JjaGlkIn0.mXwAII31JNVytCbP_7966nGHKASSmW9GR_u9UI70V2Y) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Compares rounded-corner techniques in UIKit and SwiftUI, including clipping and masking implications. Follow it when matching visual shape, hit testing, and rendering behavior across mixed framework screens.
- [2021 SwiftUI Tutorial for Beginners](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyJnY9RjJvakM2VE53d3MiLCJwb3N0X2lkIjoiZjQzMjc3NzctNjNkNi00NTA0LTllZDAtZWE4MGMzOGZlZWQ1IiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6IjI1Yzg5MmU1LWEzOTgtNGFlZi1hZDFhLTM2M2U5MzVhNThiYSIsImlhdCI6MTY3NDA2MjY3OS40NiwiaXNzIjoib3JjaGlkIn0.gQ6KdqAbJ5IzVWr6SgzNiLnQWsH-sL6BCnjtKFOMUME) — Tutorial · Topics: Swift · SwiftUI · Xcode
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.

## [SwiftUI Weekly - Issue #42](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-42)

- Published: `2021-01-18T16:16:53.000Z`

**Topics:** Graphics, Media & Games · Networking · Observation & State Management · Swift · SwiftUI

**Sections:** Reading · Recreating the Strava Activity Graph in SwiftUI · How to check if Text is truncated in SwiftUI?

**NeKI brief:** This issue covers recreating a Strava activity graph and detecting truncated Text. It offers concrete research leads for custom drawing, layout measurement, accessibility-aware overflow handling, and deciding when a chart should become a reusable component.

## [SwiftUI Weekly - Issue #41](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-41)

- Published: `2021-01-13T12:37:17.000Z`

**Topics:** Graphics, Media & Games · Hardware & Devices · Maps & Location · Performance · Swift · SwiftUI

**Sections:** Reading · AnimatableModifier in SwiftUI · Labels in SwiftUI

**NeKI brief:** Issue 41 discusses AnimatableModifier and Labels. Use it to study custom interpolation and semantic icon-text presentation, including how animation state, rendering cost, and accessibility labels interact in reusable SwiftUI components.

## [SwiftUI Weekly - Issue #40](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-40)

- Published: `2020-12-28T15:59:02.000Z`

**Topics:** Graphics, Media & Games · Networking · Objective-C & Cocoa · Swift · SwiftUI · UIKit

**Sections:** News · Reading · Hero animations in SwiftUI

**NeKI brief:** This issue combines hero animations with UIKit, networking, and Xcode context. It is a useful case study for coordinating matched visual transitions across navigation boundaries while keeping asynchronous data loading and legacy controllers isolated.

## [SwiftUI Weekly - Issue #39](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-39)

- Published: `2020-12-15T13:53:41.000Z`

**Topics:** App Distribution & Store Operations · Developer Community & Business · macOS & AppKit · Swift · SwiftUI · Xcode

**Sections:** News · Xcode 12.3 is available on the Mac App Store · Reading

**Selected links:**
- [Xcode 12.3 is available on the Mac App Store](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2FwcHMuYXBwbGUuY29tL2F6L2FwcC94Y29kZS9pZDQ5Nzc5OTgzNT9tdD0xMiZ1dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6ImUwZDA3MDRlLWU3MDItNGQzOC05YjcxLWYxNmMzODc4NGI1ZSIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiI0ODRkOGEwZi02ZTM1LTQ2ODgtOWJlYy04OTdmYWY5M2I5N2MiLCJpYXQiOjE2NzQwNjI2NzkuNzA4LCJpc3MiOiJvcmNoaWQifQ.Rnp31Lwoh2tW1CP8rFSLWGLLC-3eQlf-aop4b01WMPw) — Article · Topics: App Distribution & Store Operations · Swift · Xcode
  **NeKI brief:** Links to the Xcode 12.3 Mac App Store release from the historical issue. Use it only as release-history context when investigating SDK-era behavior, not as a current installation recommendation.
- [Develop Apps with SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2RldmVsb3Blci5hcHBsZS5jb20vdHV0b3JpYWxzL2FwcC1kZXYtdHJhaW5pbmc_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiJlMGQwNzA0ZS1lNzAyLTRkMzgtOWI3MS1mMTZjMzg3ODRiNWUiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiNDg0ZDhhMGYtNmUzNS00Njg4LTliZWMtODk3ZmFmOTNiOTdjIiwiaWF0IjoxNjc0MDYyNjc5LjcwOCwiaXNzIjoib3JjaGlkIn0.JXlAnX70EydaQCRqRSS7bqXf61jU6_5TE4c6kccdXRE) — Article · Topics: Swift · SwiftUI · Xcode
  **NeKI brief:** Apple's Develop Apps with SwiftUI training provides a structured project-based path through views, data flow, and app construction. Use it as a foundational lab sequence rather than a narrowly scoped API reference.
- [ScrollViewReader](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyJnY9cUkzZENXd3prXzAiLCJwb3N0X2lkIjoiZTBkMDcwNGUtZTcwMi00ZDM4LTliNzEtZjE2YzM4Nzg0YjVlIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6IjQ4NGQ4YTBmLTZlMzUtNDY4OC05YmVjLTg5N2ZhZjkzYjk3YyIsImlhdCI6MTY3NDA2MjY3OS43MDksImlzcyI6Im9yY2hpZCJ9.ba7FWiVaHLQouxFIKWLRvLuym_eJb1vjp2ocXKUpBy0) — Article · Topics: AI Development · Product Design · Swift
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Building a tvOS app in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwOi8vZGFuaWVsc2FpZGkuY29tL2Jsb2cvMjAyMC8xMi8wOS9idWlsZGluZy1hLXR2b3MtYXBwLWluLXN3aWZ0dWk_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiJlMGQwNzA0ZS1lNzAyLTRkMzgtOWI3MS1mMTZjMzg3ODRiNWUiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiNDg0ZDhhMGYtNmUzNS00Njg4LTliZWMtODk3ZmFmOTNiOTdjIiwiaWF0IjoxNjc0MDYyNjc5LjcwOCwiaXNzIjoib3JjaGlkIn0.2FAS4tnw91HM9Q3ZSiDKFj9wX-vUylQXXw69Wz566Kg) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a tvOS interface with SwiftUI and discusses focus-driven navigation. Follow it when adapting shared views to remote-control focus, large-screen layout, and platform-specific interaction expectations.

## [SwiftUI Weekly - Issue #38](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-38)

- Published: `2020-12-07T23:44:38.000Z`

**Topics:** App Distribution & Store Operations · App Intents & System Surfaces · Swift · SwiftUI · UIKit · Xcode

**Sections:** News · Enroll in the App Store Small Business Program · Reading

**NeKI brief:** This issue pairs App Store Small Business Program news with SwiftUI and UIKit reading. Its research value lies in the surrounding platform context and practical migration examples, useful when documenting why an older app adopted SwiftUI incrementally.

## [SwiftUI Weekly - Issue #37](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-37)

- Published: `2020-11-24T15:05:31.000Z`

**Topics:** App Distribution & Store Operations · App Services & Extensions · Graphics, Media & Games · Hardware & Devices · Swift · SwiftUI

**Sections:** News · Apple announces App Store Small Business Program · Reading

**NeKI brief:** Issue 37 covers the Small Business Program alongside accessibility and concurrency topics. Follow it for early examples of making asynchronous SwiftUI interfaces usable, especially where task timing, announcements, and semantic labels need deliberate coordination.

## [SwiftUI Weekly - Issue #36](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-36)

- Published: `2020-11-16T20:30:01.000Z`

**Topics:** App Distribution & Store Operations · Apple Platform Ecosystem · macOS & AppKit · Swift · SwiftUI · UIKit

**Sections:** News · macOS Big Sur: The MacStories Review · Reading

**NeKI brief:** This issue reviews macOS Big Sur and includes SwiftUI, UIKit, accessibility, and testing material. Use it to investigate desktop adaptation, keyboard behavior, and test strategy when a shared view must satisfy macOS interaction conventions.

## [SwiftUI Weekly - Issue #35](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-35)

- Published: `2020-11-11T13:50:14.000Z`

**Topics:** Apple Platform Ecosystem · Combine & Reactive Programming · Graphics, Media & Games · Swift · SwiftUI · UIKit

**Sections:** News · Apple Unveils New M1 Apple Silicon Chip for Macs · Reading

**NeKI brief:** Issue 35 places SwiftUI beside UIKit and Swift Package Manager during the Apple Silicon transition. It is useful for studying package and architecture choices across architectures, while checking historical build assumptions against current Xcode.

## [SwiftUI Weekly - Issue #34](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-34)

- Published: `2020-11-02T15:02:22.000Z`

**Topics:** Architecture · Dependency Injection · Developer Tools · Navigation & Deep Linking · Swift · SwiftUI

**Sections:** Reading · When does the order of SwiftUI modifiers matter, and why? · Dependency Injection in SwiftUI

**NeKI brief:** This issue examines modifier ordering and dependency injection in SwiftUI, with navigation and concurrency context. Consult it when debugging environment propagation or visual differences caused by modifier placement, and when separating injectable services from view state.

## [SwiftUI Weekly - Issue #33](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-33)

- Published: `2020-10-27T16:57:07.000Z`

**Topics:** Graphics, Media & Games · Localization · Observation & State Management · Swift · SwiftUI · Xcode

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #33 · Reading

**Selected links:**
- [Hashable SwiftUI bindings](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2ZpdmVzdGFycy5ibG9nL3N3aWZ0dWkvaGFzaGFibGUtYmluZGluZ3MuaHRtbD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6ImM3ZjI4NTk4LTg4ODEtNGI5NC1hMzQwLTQwOTJhMDk3Mjg0MCIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiI2ZDM4NmYxNi0wNzZmLTRiM2QtYTg5ZC01MWZlZTAwNDY2YzYiLCJpYXQiOjE2NzQwNjI3MzYuODE2LCJpc3MiOiJvcmNoaWQifQ.hYiEm2U7_ereRlPNa5ssDYaUJ8VIAANmxLLdRWD8xiI) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Explores making SwiftUI Binding values Hashable for collection and navigation use cases. Use it when binding identity must participate in sets or routes, while checking whether hashing mutable state is semantically stable.
- [Adapting to SwiftUI View Lifecycle](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3F2aWsuY29tL25ld3MvYWRhcHRpbmctdG8tc3dpZnR1aS12aWV3LWxpZmVjeWNsZS8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiJjN2YyODU5OC04ODgxLTRiOTQtYTM0MC00MDkyYTA5NzI4NDAiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiNmQzODZmMTYtMDc2Zi00YjNkLWE4OWQtNTFmZWUwMDQ2NmM2IiwiaWF0IjoxNjc0MDYyNzM2LjgxNiwiaXNzIjoib3JjaGlkIn0.dZlOuST5A068Kq91Ms3bu42xDHIKroWb7lZq34WK0jE) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Discusses adapting to SwiftUI's value-oriented lifecycle and repeated body evaluation. Follow it when porting imperative view-controller assumptions and deciding where initialization, side effects, and cleanup belong.
- [SwiftCamera: The source project for the SwiftCamera tutorial](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2dpdGh1Yi5jb20vcm9yb2RyaWd1ZXoxMTYvU3dpZnRDYW1lcmE_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiJjN2YyODU5OC04ODgxLTRiOTQtYTM0MC00MDkyYTA5NzI4NDAiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiNmQzODZmMTYtMDc2Zi00YjNkLWE4OWQtNTFmZWUwMDQ2NmM2IiwiaWF0IjoxNjc0MDYyNzM2LjgxNiwiaXNzIjoib3JjaGlkIn0.NmimYkKoustjVoU5_ZFzajEkdlaWS9ctJUv9ZJ8dgmI) — Tutorial · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Provides source for a SwiftCamera tutorial project. Use it to inspect camera-session setup, preview integration, and capture flow as a concrete UIKit or SwiftUI interoperability reference.
- [SwiftUI Tutorial: Core Concepts: AnimatableModifier](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyJnY9NmhuejVNbjlUWmciLCJwb3N0X2lkIjoiYzdmMjg1OTgtODg4MS00Yjk0LWEzNDAtNDA5MmEwOTcyODQwIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6IjZkMzg2ZjE2LTA3NmYtNGIzZC1hODlkLTUxZmVlMDA0NjZjNiIsImlhdCI6MTY3NDA2MjczNi44MTYsImlzcyI6Im9yY2hpZCJ9.Wg4mAP1cHrV_BnY7X-Pm5sL0MRHawGOqjKvYQBm_Gzs) — Tutorial · Topics: Product Design · Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.

## [SwiftUI Weekly - Issue #32](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-32)

- Published: `2020-10-19T21:44:20.000Z`

**Topics:** Graphics, Media & Games · Swift · SwiftUI · UIKit

**Sections:** News · Apple’s iPhone 12 Lineup: The MacStories Overview · Reading

**NeKI brief:** This issue combines iPhone 12 context with SwiftUI and UIKit reading. Use it as a historical platform-adaptation reference for device-specific layouts, interoperability, and the design assumptions that accompanied early iOS 14 SwiftUI releases.

## [SwiftUI Weekly - Issue #31](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-31)

- Published: `2020-10-12T21:50:36.000Z`

**Topics:** Concurrency · Graphics, Media & Games · Navigation & Deep Linking · Product Design · Swift · SwiftUI

**Sections:** News · Announcing Swift Algorithms · Reading

**NeKI brief:** Issue 31 links Swift Algorithms with SwiftUI navigation and concurrency. Follow it to study collection-driven view models and route state, then assess how algorithmic transformations and asynchronous loading should remain testable and isolated.

## [SwiftUI Weekly - Issue #30](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-30)

- Published: `2020-10-05T15:38:17.000Z`

**Topics:** Accessibility · Graphics, Media & Games · macOS & AppKit · Swift · SwiftUI · UIKit

**Sections:** Reading · Lazy stacks secrets · Introducing View Preferences in SwiftUI

**NeKI brief:** This issue focuses on lazy-stack behavior and View Preferences. It provides practical leads for measuring child geometry, propagating layout data upward, and avoiding eager rendering, useful when tuning large SwiftUI feeds or custom overlays.

## [SwiftUI Weekly - Issue #29](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-29)

- Published: `2020-09-28T20:44:06.000Z`

**Topics:** Accessibility · Apple Platform Ecosystem · Hardware & Devices · Networking · Swift · SwiftUI

**Sections:** News · Apple’s use of Swift and SwiftUI in iOS 14 · Reading

**Selected links:**
- [Mastering ScrollView in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3N3aWZ0d2l0aG1hamlkLmNvbS8yMDIwLzA5LzI0L21hc3RlcmluZy1zY3JvbGx2aWV3LWluLXN3aWZ0dWkvP3V0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXIiLCJwb3N0X2lkIjoiMjRiMzQ3YmQtZTA2NS00ZGJmLThjMTAtMzJhZjQ4ZTM1MTZmIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6Ijk4ZDliYTZjLWE2NjAtNDdiOC1iZjg1LTQwZmU4ODY2OGViOCIsImlhdCI6MTY3NDA2MjczNi43OTIsImlzcyI6Im9yY2hpZCJ9.8uSewvaVO9CkH6aARNQquTsEmJ6KVckQz6RnAtixA_4) — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Surveys ScrollView composition, axes, indicators, and nested content in SwiftUI. Follow it when diagnosing scrolling layout behavior or choosing between a plain scroll container and a lazy collection.
- [Handling Undo & Redo in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2xvc3Rtb2EuY29tL2Jsb2cvSGFuZGxpbmdVbmRvQW5kUmVkb0luU3dpZnRVSS8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiIyNGIzNDdiZC1lMDY1LTRkYmYtOGMxMC0zMmFmNDhlMzUxNmYiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiOThkOWJhNmMtYTY2MC00N2I4LWJmODUtNDBmZTg4NjY4ZWI4IiwiaWF0IjoxNjc0MDYyNzM2Ljc5MiwiaXNzIjoib3JjaGlkIn0.zfLJGHqaxycBVGdd4RG7eF5-HkJteF590BGB1HSY62s) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Describes undo and redo handling in SwiftUI, including command or state-history considerations. Use it when editing workflows need reversible mutations without conflating undo management with ordinary view state.
- [GraphQL Interfaces, Unions, and Fragments In SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyJnY9SE5rc2lxTXVQMUkiLCJwb3N0X2lkIjoiMjRiMzQ3YmQtZTA2NS00ZGJmLThjMTAtMzJhZjQ4ZTM1MTZmIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6Ijk4ZDliYTZjLWE2NjAtNDdiOC1iZjg1LTQwZmU4ODY2OGViOCIsImlhdCI6MTY3NDA2MjczNi43OTMsImlzcyI6Im9yY2hpZCJ9.teolY23pM5QygzOT8FIwGcxuhQfPjdSLMQLZxLbATNo) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [SwiftUICharts](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2dpdGh1Yi5jb20vbWVjaWQvU3dpZnRVSUNoYXJ0cz91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6IjI0YjM0N2JkLWUwNjUtNGRiZi04YzEwLTMyYWY0OGUzNTE2ZiIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiI5OGQ5YmE2Yy1hNjYwLTQ3YjgtYmY4NS00MGZlODg2NjhlYjgiLCJpYXQiOjE2NzQwNjI3MzYuNzkzLCJpc3MiOiJvcmNoaWQifQ.enDYdXPLnmTh0pruHod1CpxiPTNWEOhKRtbQa7QNFE8) — Article · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Offers a SwiftUI charting library with source code for reusable data visualizations. Follow it to study chart composition and API design, while evaluating maintenance and accessibility against current system Charts.

## [SwiftUI Weekly - Issue #28](https://weekly.swiftwithmajid.com/p/swiftui-weekly-issue-28)

- Published: `2020-09-21T17:31:43.000Z`

**Topics:** Apple Platform Ecosystem · Cross-Platform & Web · Developer Career & Practice · Observation & State Management · Swift · SwiftUI

**Sections:** SwiftUI Weekly · SwiftUI Weekly - Issue #28 · News

**Selected links:**
- [Building a Collection For SwiftUI - Mimicking Collections in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2RlZmFnb3MuZ2l0aHViLmlvL3N3aWZ0dWlfY29sbGVjdGlvbl9wYXJ0MS8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiJkMzQ1YTcxNy0xYzRkLTRjODAtYWJmZi1jZmI4OWI2MGE0YTUiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiNThkNTcwYjYtNGVlMy00ZGQ1LThlZDctYWM0YjYyZmNmYzMwIiwiaWF0IjoxNjc0MDYyNzM2Ljg0LCJpc3MiOiJvcmNoaWQifQ.apXIfe4Xu3QOS-7F1q2so6Mm57M1vsWSNQDqeDM9DMY) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Begins implementing a custom SwiftUI collection by examining collection protocols and view composition. Use it to understand the abstractions needed when standard List or LazyVGrid cannot provide the required behavior.
- [Building a Collection For SwiftUI - SwiftUI Collection Implementation](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2RlZmFnb3MuZ2l0aHViLmlvL3N3aWZ0dWlfY29sbGVjdGlvbl9wYXJ0Mi8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiJkMzQ1YTcxNy0xYzRkLTRjODAtYWJmZi1jZmI4OWI2MGE0YTUiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiNThkNTcwYjYtNGVlMy00ZGQ1LThlZDctYWM0YjYyZmNmYzMwIiwiaWF0IjoxNjc0MDYyNzM2Ljg0LCJpc3MiOiJvcmNoaWQifQ.xoNgXlBYcEyTzCoqCVS18e-Ckvahd1vhfiTmTTTT3s0) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Completes the custom SwiftUI collection implementation with layout and data-handling details. Follow it when evaluating bespoke collection components and their trade-offs against built-in lazy containers.
- [Build a Twitter-Inspired Animated Like Button in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL21lZGl1bS5jb20vYmV0dGVyLXByb2dyYW1taW5nL2J1aWxkLWEtdHdpdHRlci1pbnNwaXJlZC1hbmltYXRlZC1saWtlLWJ1dHRvbi1pbi1zd2lmdHVpLWQ1NThjNGEzZmMwMD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6ImQzNDVhNzE3LTFjNGQtNGM4MC1hYmZmLWNmYjg5YjYwYTRhNSIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiI1OGQ1NzBiNi00ZWUzLTRkZDUtOGVkNy1hYzRiNjJmY2ZjMzAiLCJpYXQiOjE2NzQwNjI3MzYuODQsImlzcyI6Im9yY2hpZCJ9.XnJcrBbgcJKz4MM0V4XppVi2SGHNFPTplstlJUHvepo) — Article · Topics: AI Development · Swift · SwiftUI
  **NeKI brief:** Builds a Twitter-inspired animated like button with SwiftUI state and transitions. Use it as a focused example of coordinating icon, color, and scale changes around one user action.
- [DeckKit](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2dpdGh1Yi5jb20vZGFuaWVsc2FpZGkvRGVja0tpdD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6ImQzNDVhNzE3LTFjNGQtNGM4MC1hYmZmLWNmYjg5YjYwYTRhNSIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiI1OGQ1NzBiNi00ZWUzLTRkZDUtOGVkNy1hYzRiNjJmY2ZjMzAiLCJpYXQiOjE2NzQwNjI3MzYuODQsImlzcyI6Im9yY2hpZCJ9.apFoUvCh0ftwDhFiCphT9BEerMqLYEIlkOcg_G3k_Pw) — Article · Topics: AI Development · Swift · SwiftUI
  **NeKI brief:** DeckKit is a SwiftUI-oriented card or deck component library with source available for inspection. Use it to study reusable card APIs and interaction modeling before adopting or recreating a similar component.
