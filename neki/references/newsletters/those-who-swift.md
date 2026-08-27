# Those Who Swift

Third-party source index. It provides source attribution and routing metadata, not republished article content. Verify article conclusions independently before applying them.

- Archive: [https://thosewhoswift.substack.com/archive](https://thosewhoswift.substack.com/archive)
- Last collected: `2026-08-27T19:22:09Z`
- Indexed entries: **89**

## [Issue 281](https://thosewhoswift.substack.com/p/those-who-swift-issue-281)

- Published: `2026-08-26T20:38:31.643Z`

**Topics:** App Distribution & Store Operations · Developer Tools · Objective-C & Cocoa · Performance · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 281 · Weekly note ✏️

**NeKI brief:** Combines a sustainability-focused developer note with current Swift, Apple, AI-tooling, tutorial and video links, offering both release-lifecycle perspective and a broad set of follow-up reading.

**Selected links:**
- [Empty States in SwiftUI with ContentUnavailableView](https://kylebrowning.com/posts/swiftui-empty-states-contentunavailableview) — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **NeKI brief:** Compares the ContentUnavailableView initializers and shows how to build reusable SwiftUI empty states for search, errors, and offline conditions. The approach reduces repeated per-screen placeholder logic while keeping each state understandable to users.
- [Preventing Transitive Swift Imports with Bazel](https://adincebic.com/2026/08/23/preventing-transitive-swift-imports-with.html) — Article · Topics: Architecture · Cross-Platform & Web · Swift
  **NeKI brief:** Explains how permissive transitive Swift imports let a module use dependencies it did not declare directly, and presents Bazel-oriented ways to prevent that leakage. Explicit dependency ownership improves build reasoning and reduces accidental coupling between modules.
- [Apple Foundation Models: Hybrid AI with Dynamic Profiles](https://peterfriese.dev/blog/2026/hybrid-ai-apple-foundation-models-gemini) — Article · Topics: AI Development · Foundation & Data Formats · Performance
  **NeKI brief:** Uses Foundation Models dynamic profiles to choose between an on-device model and Gemini through Firebase AI Logic. The design makes privacy, capability, availability, and network trade-offs explicit at the request-routing boundary.
- [AI Wanted to Give Up. The Human Didn’t.](https://fatbobman.com/en/weekly/issue-150) — Article · Topics: AI Development · Developer Tools · Persistence & Synchronisation
  **NeKI brief:** Curates Apple-platform topics including AI delegation, Swift Package Registry, CoreBluetooth concurrency, CloudKit, and OCR mapping. It serves as a source map to several implementation discussions, with each linked article requiring its own technical evaluation.
- [Presenting Alerts and Confirmation Dialogs from Identifiable Data in SwiftUI](https://tanaschita.com/swiftui-alert-identifiable-data) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Shows iOS 27's `item:` overloads for `alert` and `confirmationDialog`, where one optional `Identifiable` value simultaneously controls presentation and supplies the selected model. This removes coupled Boolean/item state and clears the selection automatically on dismissal.
- [Wally 7](https://danielsaidi.com/blog/2026/08/20/wally-7) — Article · Topics: Swift · SwiftData
  **NeKI brief:** Announces Wally 7, a major release of Daniel Saidi's native iOS app, with a new data store and additional features. The release is useful as a concrete example of evolving a long-lived Apple-platform app while replacing foundational persistence infrastructure.
- [NSTextTable in Swift](https://livsycode.com/uikit/nstexttable-in-swift) — Article · Topics: Swift · UIKit
  **NeKI brief:** Introduces NSTextTable and NSTextTableBlock in UIKit for creating tables inside NSAttributedString, now available to iOS developers in the iOS 27 SDK. It distinguishes rich-text tables from UITableView and shows when the text model is the appropriate layout layer.
- [Translation Sub-Agents Go Brrrrrrrr](https://cuteios.dev/2026/08/17/localizations-translations) — Article · Topics: Localization · Xcode
  **NeKI brief:** Describes an app-localization workflow that uses translation sub-agents to take over repetitive translation work. The article is useful for evaluating where automation can support localization while keeping terminology and final language quality under developer control.
- [Running iOS Background Tasks Reliably, Part 1](https://calcopilot.app/blog/posts/running-ios-background-tasks-reliably-part1) — Article · Topics: AI Development · App Services & Extensions · Personal Essays
  **NeKI brief:** Documents lessons learned while pursuing reliable iOS background-task execution in iOS 26. The article focuses on the practical reliability gap between scheduling background work and getting it to run consistently, which is useful when designing refresh and deferred-processing workflows.
- [Protecting SwiftUI Views With Authentication](https://azamsharp.com/2026/08/22/protecting-swiftui-views-with-authentication.html) — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **NeKI brief:** Shows how to protect SwiftUI views behind an authentication boundary. The topic connects view composition with session state, making it useful for deciding where authenticated routing and access checks belong in a SwiftUI application.
- [The Curious Case of the Missing SwiftUI Clicks](https://damian.fyi/swift/2026/08/16/curious-case-of-missing-click.html) — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **NeKI brief:** Investigates a missing SwiftUI click in the context of a searchable, on-device timeline app. The debugging story highlights how gesture targets and view composition can diverge from the visual hierarchy, a useful reminder when diagnosing apparently inactive controls.
- [A Framework to Make Decisions Faster as a Lead Software Engineer](https://mfaani.com/posts/career/a-framework-to-make-decisions-faster-as-a-lead-software-engineer) — Article · Topics: Developer Career & Practice · Objective-C & Cocoa
  **NeKI brief:** Presents a decision-making framework for lead software engineers who must act quickly under pressure. Its focus is on structuring incomplete information and trade-offs so technical leadership decisions become faster and more deliberate.
- [More Incredible Tales of App Store Curation](https://lapcatsoftware.com/articles/2026/8/9.html) — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **NeKI brief:** Examines Apple App Store curation through concrete examples of review and editorial treatment. It provides product and distribution context for developers whose release strategy depends on App Store visibility, rather than describing an implementation technique.
- [iOS 27: StateReporter](https://antongubarenko.substack.com/p/ios-27-statereporter) — Article · Topics: Performance
  **NeKI brief:** Introduces iOS 27 StateReporting for attaching concise application-state transitions and metadata to MetricKit diagnostics, helping connect hangs or hitches to the user activity that preceded them.
- [Looking for Maintainers!](https://www.massicotte.org/blog/looking-for-maintainers) — Article
  **NeKI brief:** Invites maintainers for an open-source portfolio and frames maintenance as an ongoing engineering responsibility rather than a one-time publication event. It is relevant when evaluating the sustainability, ownership, and contribution paths of Swift community projects.

## [Devs for Devs: Short Eye Long Eye - Those Who Swift](https://thosewhoswift.substack.com/p/devs-for-devs-short-eye-long-eye)

- Published: `2026-08-23T20:51:09.749Z`

**Topics:** Cross-Platform & Web · Security & Privacy · Swift

**Sections:** Those Who Swift · Devs for Devs: Short Eye Long Eye

**NeKI brief:** Presents an indie-development planning method that balances a long-term product direction with small daily MASS goals—meaningful, achievable, simple and small—to reduce rabbit holes and preserve shipping momentum.

## [Issue 280](https://thosewhoswift.substack.com/p/those-who-swift-issue-280)

- Published: `2026-08-19T20:31:22.272Z`

**Topics:** Concurrency · Developer Tools · Swift · SwiftUI · Testing · Xcode

**Sections:** Those Who Swift · Those Who Swift - Issue 280 · Weekly note ✏️

**NeKI brief:** A large community round-up spanning SwiftUI implementation traps, concurrency and networking, privacy, profiling, accessibility and current AI tooling; use its individual links to investigate concrete platform and workflow questions.

**Selected links:**
- [ContentBuilder Explained: The Secret Behind SwiftUI's Type-Checking Speedup](https://fatbobman.com/en/posts/contentbuilder-explained) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Dissects ContentBuilder as a separation between content construction and protocol-specific validation, then benchmarks the resulting type-checking gains. It also explains where the pattern helps shared SwiftUI APIs and where it is not a cure-all.
- [A Change of State](https://www.createchsol.com/blog/2026-08-12-a-change-of-state.html) — Article · Topics: Cross-Platform & Web · Macros & Metaprogramming · Swift
  **NeKI brief:** Discusses a change-of-state problem in a software-development context. The piece is relevant as an engineering design note because state transitions are where UI, persistence, and asynchronous work most often need explicit coordination.
- [The Curious Case of the missing SwiftUI Clicks](https://damian.fyi/swift/2026/08/16/curious-case-of-missing-click.html) — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **NeKI brief:** Investigates a missing SwiftUI click in the context of a searchable, on-device timeline app. The debugging story highlights how gesture targets and view composition can diverge from the visual hierarchy, a useful reminder when diagnosing apparently inactive controls.
- [How to stream SSE with URLSession in Swift](https://onmyway133.com/posts/how-to-stream-sse-with-urlsession-in-swift) — Article · Topics: AI Development · Networking · Swift
  **NeKI brief:** Builds a Server-Sent Events client from URLSession.bytes, first parsing data lines and then handling multi-field events through AsyncStream. The progression is useful for lightweight LLM token streaming without a separate dependency.
- [Using Top Functions Mode in Instruments to Quickly Find the Slowest Code](https://swiftdevjournal.com/posts/top-functions) — Article · Topics: Performance · Swift · Xcode
  **NeKI brief:** Shows how Instruments' Top Functions mode reorders Time Profiler or CPU Profiler samples by self weight, then relates the result to the flame graph. It offers a faster first pass for locating genuinely expensive functions.
- [Installing simulator runtimes from the command line](https://www.donnywals.com/installing-simulator-runtimes-from-the-command-line) — Article · Topics: Developer Tools · Objective-C & Cocoa · Xcode
  **NeKI brief:** Explains installing Xcode Simulator runtimes from the command line. Use it when CI or a fresh development machine must provision a specific runtime reproducibly instead of relying on Xcode's graphical download flow.
- [Adapting EPUB 3 Features to CoreText in Yuedu Reader](https://chang-jui-lin.github.io/Yuedu-reader/2026/06/08/coretext-epub3-adaptation) — Article · Topics: Developer Tools · Graphics, Media & Games
  **NeKI brief:** Explains how the Yuedu Reader maps EPUB 3 features such as fixed layout, media overlays, HTML5 media, CSS floats, tables, and bidirectional text onto a native CoreText engine. The article is a concrete case study in preserving rich document semantics across a custom reader layout.
- [Sendable and @Sendable closures explained with code examples](https://www.avanderlee.com/swift/sendable-protocol-closures) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains Sendable and @Sendable closures as compiler contracts for values crossing concurrency domains, with examples of structs, classes, and captured state. It identifies why seemingly harmless captures trigger diagnostics and how to redesign them safely.
- [Build a Local Codex Token Usage Ledger Without Replay Errors](https://agent-island.dev/blog/codex-token-replay-guard) — Article · Topics: AI Development · Swift
  **NeKI brief:** Describes a token replay guard for Codex-style agent workflows, focusing on preventing a previously accepted token from being reused outside its intended request context. The security pattern is relevant to agent tooling that carries authorization or execution state across steps.
- [Recording VoiceOver on iOS & macOS](https://www.basbroek.nl/recording-voiceover) — Article · Topics: Accessibility · Testing
  **NeKI brief:** Explains why iOS screen recording captures VoiceOver directly and how macOS needs virtual audio routing, illustrated with Loopback. The workflow produces clean accessibility demonstrations without recording speakers or room noise.
- [IP and DNS Leaks in WebKit Affecting Proxy Browsers and Apple iCloud Private Relay](https://mysk.blog/2026/08/04/webkit-proxy-icloud-private-relay-ip-leak) — Article · Topics: Developer Tools · Objective-C & Cocoa · Security & Privacy
  **NeKI brief:** Demonstrates three WebKit paths—DNS prefetching, WebAuthn related-origin requests, and WebTransport—that can bypass configured proxies and expose a device's network. It distinguishes affected proxy and Private Relay setups from system-level VPN tunnels.
- [SwiftUI should become Open-Source](https://macguru.dev/swiftui-should-become-open-source) — Article · Topics: Hardware & Devices · Swift · SwiftUI
  **NeKI brief:** Makes a case for opening SwiftUI's implementation and discusses how transparency could affect the ecosystem. Treat it as opinion and community perspective, useful for framing trade-offs rather than as evidence about Apple's roadmap or framework internals.
- [Type-safe JSON and JSONB in StructuredQueries](https://www.pointfree.co/blog/posts/220-type-safe-json-and-jsonb-in-structuredqueries) — Article · Topics: Persistence & Synchronisation
  **NeKI brief:** Introduces StructuredQueries 0.35 support for SQLite JSON and JSONB columns, key-path-based extraction and mutation, and json_each collection queries. The examples show where binary storage improves efficiency while preserving compile-time schema checks.
- [Using Cursor in Xcode 27](https://www.polpiella.dev/cursor-xcode-27) — Article · Topics: Xcode
  **NeKI brief:** Explains installing Cursor’s agent CLI, registering it through Xcode 27’s ACP support, and selecting it for new conversations. Follow it when comparing external agent choice with Xcode’s remembered conversation-agent state.
- [SwiftUI After 7 Years: A Story of Mediocrity](https://ykvm.com/2026/07/swiftui-a-story-of-mediocrity) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Critiques SwiftUI after seven years, focusing on perceived stability, performance, and maturity gaps. The opinionated assessment is useful for weighing framework trade-offs, but its broad claims should be separated from measurable behavior in a current project.
- [Taking control of toolbar items in SwiftUI](https://swiftwithmajid.com/2026/06/23/taking-control-of-toolbar-items-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explores newer SwiftUI toolbar controls for styling the UI control layer separately from content, an important distinction in the current design language. Follow it when toolbar placement and appearance must remain predictable across platforms.

## [Devs for Devs: From XCUITest to Promo Video](https://thosewhoswift.substack.com/p/devs-for-devs-from-xcuitest-to-promo)

- Published: `2026-08-16T19:30:07.593Z`

**Topics:** Cross-Platform & Web · Graphics, Media & Games · Security & Privacy · Swift · SwiftUI · Testing

**Sections:** Those Who Swift · Treating Marketing Assets Like Build Artifacts · Start with an Exact SwiftUI State

**NeKI brief:** Treats App Store screenshots and promo videos as reproducible build output: launch exact SwiftUI state, operate capture through XCUITest, compose in Remotion, and verify inputs with manifests and hashes.

## [Issue 279](https://thosewhoswift.substack.com/p/those-who-swift-issue-279)

- Published: `2026-08-12T20:30:39.583Z`

**Topics:** Concurrency · Developer Tools · Persistence & Synchronisation · Swift · SwiftUI · Testing

**Sections:** Those Who Swift · Those Who Swift - Issue 279 · Weekly note ✏️

**NeKI brief:** Curates Swift concurrency isolation, testable SwiftData, new SwiftUI APIs, agent worktrees and runtime SF Symbols previewing, with a monthly Swift-project digest.

**Selected links:**
- [Building Testable SwiftData Apps](https://azamsharp.com/2026/08/02/building-testable-swiftdata-apps.html) — Article · Topics: Swift · SwiftData · Testing
  **NeKI brief:** Structures SwiftData code so model containers and observations can be exercised outside a SwiftUI view hierarchy. Use it to test persistence behavior and query-driven updates without coupling every assertion to UI rendering.
- [Bluetooth Without the Delegate Dance](https://kylebrowning.com/posts/bluetooth-without-the-delegate-dance) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Compares raw CoreBluetooth delegates, an older wrapper and a Swift 6.2 actor design, then introduces BLESwift and its macOS command-line companion for async device workflows.
- [SwiftUI Document APIs in the 2027 Releases: Everything You Need to Know](https://sagarunagar.com/blog/swiftui-document-apis-2027-whats-new) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Surveys new SwiftUI document creation, reading, writing and snapshot APIs, emphasizing asynchronous disk work, responsive large-file handling and direct document URL access.
- [Using SwiftUI's ContentBuilder with Non-View Types](https://artemnovichkov.com/blog/using-swiftui-contentbuilder-with-non-view-types) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Uses Xcode 27's ContentBuilder to assemble a type-safe deep-link routing DSL from non-View values, with an approach for preserving similar syntax on earlier deployment targets.
- [Concentric Buttons with OS 27's SwiftUI APIs](https://alexanderweiss.dev/blog/2026-08-09-concentric-button-os-27-swiftui-apis) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a custom SwiftUI button border from GeometryProxy.concentricCornerRadii, including container-shape requirements, nil fallback behavior and the limitation that ButtonBorderShape remains closed.
- [Adaptive SwiftUI Toolbars in iOS 27](https://nilcoalescing.com/blog/AdaptiveSwiftUIToolbarsInIOS27) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains iOS 27 toolbar visibility priorities, explicit overflow placement, trailing-edge pinning and navigation-bar minimization so important actions survive compact layouts.
- [How to Use Git Worktree — and How AI Agents Use It](https://mfaani.com/posts/ai/how-to-use-git-worktree-and-how-its-used-by-ai-agents) — Article · Topics: AI Development · Developer Tools
  **NeKI brief:** Explains creating sibling Git worktrees, the one-worktree-per-branch constraint and why isolated checkouts let several coding agents work concurrently without sharing an index.
- [Managing Focus in SwiftUI with FocusState](https://tanaschita.com/swiftui-focus-state) — Article · Topics: Developer Career & Practice · Swift · SwiftUI
  **NeKI brief:** Shows how FocusState drives programmatic focus, switches among several fields, dismisses the keyboard and passes a focus binding into child views.
- [Swift 6.2 Concurrency in Practice: Default to MainActor, Escape on Purpose](https://blakecrosley.com/blog/swift-6-2-concurrency-in-practice) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains approachable-concurrency defaults: module-wide MainActor isolation, caller-actor execution for nonisolated async functions and explicit @concurrent escape points for CPU-heavy work.
- [What's New in Swift: July 2026 Edition](https://www.swift.org/blog/whats-new-in-swift-july-2026) — Article · Topics: Developer Community & Business · Swift
  **NeKI brief:** Summarizes July activity across Swift releases, evolution, tooling and community workgroups, providing a routing overview rather than a single API tutorial.
- [Using AI Without Losing Your Critical Thinking](https://swiftrocks.com/using-ai-without-losing-critical-thinking) — Article · Topics: AI Development · Swift
  **NeKI brief:** Argues that developers must verify AI claims and retain engineering judgment, framing uncritical relay of model output as cognitive surrender rather than productive delegation.
- [iOS 27: Working with the Media Intelligence Framework](https://antongubarenko.substack.com/p/ios-27-media-intelligence-framework) — Article
  **NeKI brief:** Introduces iOS 27’s Media Intelligence framework for analysing video and grouping detected faces, including the need for a physical device. Use it as an implementation lead while confirming supported media, privacy behavior, and final SDK availability.
- [An Even Closer Look at Protocols and Global Actors](https://www.massicotte.org/blog/protocols-and-global-actors) — Article · Topics: Concurrency
  **NeKI brief:** Compares whole-protocol, per-requirement and conformance-level global-actor isolation, showing how each choice changes protocol usability and where nonisolated conformances preserve flexibility.
- [Previewing SF Symbols with Apple's Own Renderer](https://www.amyworrall.com/blog/previewing-sf-symbols-with-apples-own-renderer) — Article
  **NeKI brief:** Previews edited custom SF Symbols with Apple's renderer by patching a template asset catalog at runtime, loading the generated Assets.car through a temporary bundle.

## [Issue 278](https://thosewhoswift.substack.com/p/those-who-swift-issue-278)

- Published: `2026-08-05T20:00:46.292Z`

**Topics:** Concurrency · Liquid Glass · Persistence & Synchronisation · Swift · SwiftUI · Testing

**Sections:** Those Who Swift · Those Who Swift - Issue 278 · Weekly note ✏️

**NeKI brief:** Curates current Swift reading across Liquid Glass, concurrency, SwiftUI list and image performance, SwiftData and CloudKit, and agent-assisted development. Use the issue as a cross-source snapshot; each link retains its own access and technical context.

**Selected links:**
- [The iOS Testing Strategy Agent Skill](https://livsycode.com/best-practices/the-ios-testing-strategy-agent-skill) — Article · Topics: AI Development · Code Quality · Testing
  **NeKI brief:** Presents an agent skill that starts test design from behavior, risk, and observable outcomes rather than one test file per type. It chooses boundaries and doubles by determinism, execution time, maintenance cost, and the confidence each layer adds.
- [SwiftUI Image Caching Explained: Faster Lists and Better Performance](https://www.youtube.com/watch?v=zfEt6PLICr8) — Video · Topics: Networking · Performance · SwiftUI
  **NeKI brief:** Compares AsyncImage’s system-managed HTTP caching with an explicit image-cache layer for SwiftUI list performance. Follow the walkthrough when deciding whether server headers and URLCache are sufficient or the app needs controllable memory and disk behavior.
- [Liquid Glass: A Field Guide to UIKit Compatibility Pitfalls](https://fatbobman.com/en/posts/liquid-glass-a-field-guide-to-uikit-compatibility-pitfalls) — Article · Topics: Liquid Glass · UIKit
  **NeKI brief:** Catalogues real UIKit compatibility failures around Liquid Glass in iOS 26 and 27, including bar buttons, tab bars, web views, and steppers. Use the cases to distinguish workable adaptations from framework bugs that still lack reliable fixes.
- [Changing the Shape of Glass Buttons in SwiftUI](https://livsycode.com/swiftui/changing-the-shape-of-glass-buttons-in-swiftui) — Article · Topics: Liquid Glass · SwiftUI
  **NeKI brief:** Uses buttonBorderShape to change a system Liquid Glass button from its default capsule to a circle or rounded rectangle. It explains why participating in the button style preserves system effects better than clipping the rendered result afterward.
- [Demystifying Thread Hopping with Swift 6.2 Approachable Concurrency](https://www.nsvasilev.com/posts/approachable_concurrency) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains Swift 6.2 thread hopping under Approachable Concurrency, especially the effect of nonisolated-nonsending defaults on executor inheritance. Use it to reason about isolation and scheduling without treating a particular thread as the concurrency contract.
- [AsyncImage Finally Gets Caching in SwiftUI](https://www.sagarunagar.com/blog/asyncimage-caching-wwdc-2026) — Article · Topics: Networking · Performance · SwiftUI
  **NeKI brief:** Explains AsyncImage’s Xcode 27 HTTP caching, including automatic URLCache behavior driven by server headers plus URLRequest and custom URLSession control. Useful for reducing repeat downloads while keeping cache policy explicit for image-heavy scrolling interfaces.
- [Swift Protocols and the Main Actor](https://www.swiftbysundell.com/articles/swift-protocols-and-the-main-actor) — Article · Topics: Concurrency · Foundation & Data Formats · Swift
  **NeKI brief:** Compares isolating an entire protocol with isolating individual requirements. The examples expose how conformance placement can affect a type's actor isolation and why requirement-level annotations give custom actors a more flexible boundary.
- [Introducing ListKit: An Open-Source Library for SwiftUI Lists](https://danielsaidi.com/blog/2026/06/08/introducing-listkit) — Article · Topics: Architecture · Swift Package Manager · SwiftUI
  **NeKI brief:** Introduces ListKit as a focused extraction from SwiftUIKit, with reusable SwiftUI list utilities, adaptive action groups, shelf layouts, and list-specific modifiers. The smaller package illustrates trading a broad convenience monolith for narrower dependencies.
- [New in SQLiteData: Sectioned Queries](https://www.pointfree.co/blog/posts/219-new-in-sqlitedata-sectioned-queries) — Article · Topics: Persistence & Synchronisation · Swift · SwiftUI
  **NeKI brief:** Explains SQLiteData 1.8's @FetchAll(sectionBy:) grouping, which stays in SQLite and supports arbitrary SQL expressions, joins, ordering, dynamic reloads, and older OS versions. FetchKeyRequest covers typed or more complex section shapes.
- [Keeping Canvas Interactions Responsive with Frame Reprojection](https://nilcoalescing.com/blog/KeepingCanvasInteractionsResponsiveWithFrameReprojection) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Shows how Exsto keeps large Metal canvases responsive by reprojecting the last rendered frame while a newer offscreen frame is queued, then synchronising transform and texture updates with CAMetalLayer, CATransaction, overdraw, and gesture-time MSAA reduction.
- [A Sol's Work: Shipping with GPT-5.6 Sol](https://rudrank.com/a-sols-work-shipping-with-gpt-5-6-sol) — Article · Topics: AI Development · Developer Tools · Personal Essays
  **NeKI brief:** Describes a walk-away test for long-running coding agents: survive changing branches, review feedback, CI failures, and retries, then report verified reality. Production examples show increased autonomy while preserving explicit human review before shipping.
- [Shipping a SwiftData App with iCloud Sync](https://thorsten-stark.de/posts/2026-08-13-Shipping-A-SwiftData-App-With-iCloud-Sync-Part-3) — Article · Topics: Persistence & Synchronisation · SwiftData
  **NeKI brief:** Covers SwiftData and CloudKit release behavior that local testing can miss: initial-sync empty states, widget timelines that do not react automatically to remote changes, limited conflict control, and production-schema constraints. It emphasizes device validation and designing cheap conflicts.

## [Issue 277](https://thosewhoswift.substack.com/p/those-who-swift-issue-277)

- Published: `2026-07-29T20:01:55.196Z`

**Topics:** App Distribution & Store Operations · Graphics, Media & Games · Persistence & Synchronisation · Swift · SwiftData · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 277 · Weekly note ✏️

**NeKI brief:** Examines smaller iOS 27 API changes that can replace custom swipe-action, reordering, panel and toolbar workarounds. The issue is useful as a migration checklist focused on deleting framework-adaptation code rather than adding headline features.

**Selected links:**
- [WWDC26: Reordering Items in SwiftUI Lists and Grids](https://serialcoder.dev/text-tutorials/swiftui/wwdc26-reordering-items-in-swiftui-lists-and-grids) — Tutorial · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Demonstrates iOS 27 reordering for SwiftUI lists and grids through reorderContainer and the model mutation it drives. Use it to compare the new shared mechanism with older List-only movement and custom drag implementations.
- [Understanding Code Signing and Provisioning in iOS](https://tanaschita.com/ios-code-signing-provisioning) — Article · Topics: App Distribution & Store Operations · Performance · Security & Privacy
  **NeKI brief:** Code signing and provisioning connect certificates, profiles, entitlements, and bundle identifiers. The guide is useful for diagnosing build and distribution failures by separating identity, capability, and installation concerns.
- [Blend Modes in SwiftUI](https://nilcoalescing.com/blog/BlendModesInSwiftUI) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Catalogues all 21 SwiftUI blend modes with focused visual examples and explains their colour or alpha calculations. The closing compositingGroup examples clarify how to constrain which sibling views participate in a blend operation.
- [Building Adaptive Non-Modal Panels in SwiftUI](https://nilcoalescing.com/blog/BuildingAdaptiveNonModalPanelsInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a custom SwiftUI panel that changes from a bottom sheet to an edge-aligned panel using measured scene geometry, custom Layout, preferences, and detents. The drag implementation preserves scrolling by combining gestures deliberately.
- [Taking Control of Toolbar Items in SwiftUI](https://swiftwithmajid.com/2026/06/23/taking-control-of-toolbar-items-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explores newer SwiftUI toolbar controls for styling the UI control layer separately from content, an important distinction in the current design language. Follow it when toolbar placement and appearance must remain predictable across platforms.
- [iOS 27: UIBarMinimization](https://antongubarenko.substack.com/p/ios-27-uibarminimization) — Article · Topics: SwiftUI · UIKit
  **NeKI brief:** Separates UIKit navigation-bar minimisation into trigger, restoration, and safe-area decisions, then compares the corresponding SwiftUI toolbar behaviour. The examples are useful for replacing custom scroll-offset handling while the iOS 27 API remains beta.
- [Test iOS Apps in Different Time Zones](https://www.avanderlee.com/xcode/ios-time-zone-testing-physical-iphone) — Article · Topics: Testing · Xcode
  **NeKI brief:** Compares ways to validate time-sensitive app behavior on a physical iPhone, including automatic time-zone handling and simulated location changes.
- [iOS 27 SwiftUI Updates in Action](https://www.youtube.com/watch?v=N_0P9mp5T6w) — Video · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates new SwiftUI behavior in iOS 27 through runnable visual examples. Use the walkthrough to identify APIs worth testing, then confirm availability and final semantics against the shipping SDK and Apple documentation.
- [Keeping SwiftData Behind a Boundary](https://tanaschita.com/swiftdata-persistence-boundaries) — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** Keeps SwiftData behind a persistence boundary instead of exposing models directly to SwiftUI, improving testability and reducing UI coupling to storage details.
- [Bridging Gemini Video with Foundation Models and CustomSegment](https://rudrank.com/exploring-foundation-models-bridging-gemini-video-with-customsegment) — Article · Topics: AI Development · Foundation & Data Formats · Graphics, Media & Games
  **NeKI brief:** Bridges unsupported video input through a custom Transcript segment and LanguageModelExecutor that delegates analysis to Gemini. The layered verification is useful when extending Foundation Models-style sessions beyond the on-device model’s native modalities.
- [Making a SwiftUI Sheet Automatically Size to Fit Its Content](https://danielsaidi.com/blog/2026/05/22/making-a-swiftui-sheet-automatically-size-to-fit-its-content) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI sheet that measures its content and chooses an appropriate presentation height. Useful for compact forms and detail panels that should avoid excessive empty space while handling dynamic type and updates.
- [Swipe Actions Outside of List in SwiftUI](https://swiftwithmajid.com/2026/06/16/swipe-actions-outside-of-list-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows how SwiftUI swipe actions can be applied outside List, extending contextual row interactions to custom layouts. Useful when a bespoke collection needs native swipe affordances without surrendering its container design.
- [User Diagnostics Reports: Solving Bugs Faster with AI Agents](https://www.avanderlee.com/debugging/introducing-diagnostics-improved-debugging-and-user-support) — Article · Topics: AI Development · Developer Tools
  **NeKI brief:** Describes collecting structured user diagnostics—logs, context, and app state—to give an AI agent enough evidence to reproduce a bug. The workflow connects an in-app report to faster triage without requiring a live debugger session.
- [From Size Class to Available Space](https://fatbobman.com/en/posts/from-size-class-to-available-space) — Article
  **NeKI brief:** Explains why horizontalSizeClass is no longer a dependable width proxy once iPhone apps become freely resizable, and shifts layout decisions toward measured available space. The examples cover both SwiftUI and UIKit adaptation.

## [Issue 276](https://thosewhoswift.substack.com/p/those-who-swift-issue-276)

- Published: `2026-07-22T20:01:13.378Z`

**Topics:** AI Development · App Distribution & Store Operations · Graphics, Media & Games · Swift · SwiftUI · Xcode

**Sections:** Those Who Swift · Those Who Swift - Issue 276 · Weekly note ✏️

**NeKI brief:** Collects beta-era Swift reading on SDK migration constraints, Foundation Models architecture, async bridging, SwiftUI rendering, actor isolation, and developer tooling. Use it to triage current community leads, then verify beta APIs and availability with Apple documentation.

**Selected links:**
- [Rendering SwiftUI Previews with Xcode's MCP Server](https://cuteios.dev/2026/07/14/previews-and-mcp) — Article · Topics: AI Development · Graphics, Media & Games · Xcode
  **NeKI brief:** Builds a SwiftUI preview gallery by combining Xcode’s MCP server, project context, and generated preview metadata. The article maps the moving parts and current limitations, making it useful when evaluating agent-assisted preview tooling.
- [SwiftUI Animation Techniques: The iOS 27 Update](https://nathanfennel.com/blog/swiftui-animation-techniques-2026) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Surveys current SwiftUI motion techniques including layer shaders, timeline-driven sequencing, reorderable lists, and spring tuning. Use it to choose between built-in interactions and a custom animation system, then confirm beta API names and availability.
- [Copywriting with Agents and…Apple Designers?](https://www.swiftjectivec.com/copywriting-with-agents-and-apple-designers) — Article · Topics: AI Development · Swift
  **NeKI brief:** Uses agents to sharpen copy while retaining human design judgment, a useful workflow for treating generated language as a draft that still needs product voice and platform-specific review.
- [Swift Actors Explained with Real Examples](https://www.swiftbyrahul.com/posts/SwiftActorsExplainedWithRealExamples) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains actor isolation as serialized access to mutable state, contrasting it with locks, semaphores, and dispatch queues through practical examples. Follow it when deciding whether a shared resource should become actor-owned and where calls must suspend.
- [Taming Row Height and Spacing Jumps in SwiftUI List](https://fatbobman.com/en/posts/taming-row-height-and-spacing-jumps) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Addresses List row-height animation jumps by separating displayed state from source data and combining Animatable, custom Layout, and layout values. Useful when a dynamic SwiftUI row disappears before its size transition can interpolate smoothly.
- [Apple Foundation Models in iOS 27: The Complete Builder Guide](https://chatforest.com/builders-log/apple-foundation-models-ios-27-on-device-llm-api-builder-guide) — Article · Topics: AI Development · Foundation & Data Formats
  **NeKI brief:** Maps an on-device Foundation Models stack from model capability through app logic, tool calls, availability, and optional fine-tuning. Follow it when scoping a local AI feature, while validating beta hardware, privacy, and storage constraints independently.
- [What's New in SwiftUI for iOS 27](https://www.youtube.com/watch?v=tNxEqyUVGck) — Video · Topics: Swift · SwiftUI
  **NeKI brief:** Surveys iOS 27 SwiftUI changes including lazy @State creation, compile-time improvements, reorderable containers, swipe actions outside List, and the Document protocol. Useful as a migration map before checking final SDK semantics.
- [Foundation Models Is Now a Hybrid Platform — and Picking the Tier Is the New Design Decision](https://www.wesleymatlock.com/foundation-models-hybrid-platform) — Article · Topics: AI Development · Foundation & Data Formats · Navigation & Deep Linking
  **NeKI brief:** Frames model-tier selection as a feature-level architectural decision, with session creation and graceful fallback kept behind a focused boundary. Useful when designing a Foundation Models feature that may choose on-device, cloud, or frontier capability paths.
- [Continuation vs CheckedContinuation vs UnsafeContinuation](https://livsycode.com/swift/continuation-vs-checkedcontinuation-vs-unsafecontinuation-in-swift) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Artem dives deep into Continuation API, showing how it differs from CheckedContinuation and UnsafeContinuation, and when each is the right tool for bridging callback-based code to async/await.
- [The Hidden Cost of Unstable SwiftUI Environment Defaults](https://nilcoalescing.com/blog/UnstableDefaultEnvironmentValuesInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Diagnoses update churn caused by reference-typed default environment values and explains why stable defaults matter. Useful when environment injection unexpectedly invalidates views or changes identity.
- [iOS 27 SDK: 3 Major Requirements That Might Break Your App](https://blog.makwanbk.com/ios-27-sdk-3-major-requirements-that-migh-break-your-app) — Article · Topics: Liquid Glass
  **NeKI brief:** Makwan highlights three iOS 27 SDK requirements that could break older apps or block App Store submission: UIScene support, the new launch screen requirement, and the end of the Liquid Glass compatibility opt-out.

## [Issue 275](https://thosewhoswift.substack.com/p/those-who-swift-issue-275)

- Published: `2026-07-15`

**Topics:** AI Development · App Intents & System Surfaces · Apple Platform Ecosystem · Foundation & Data Formats · Swift · Xcode

**Sections:** Those Who Swift · Those Who Swift - Issue 275 · Weekly note ✏️

**Selected links:**
- [Foundation Models in iOS 27: Tool-Calling Control](https://blakecrosley.com/blog/foundation-models-tool-calling-ios-27) — Article · Topics: AI Development · Foundation & Data Formats · Objective-C & Cocoa
  **NeKI brief:** Shows how tool calling and local OCR or barcode capabilities can fit into Foundation Models workflows.
- [WWDC 2026 Developer Tools: Xcode 27, Swift, Foundation Models](https://andrew.ooo/answers/wwdc-2026-developer-tools-xcode-swift-foundation-models-june-2026) — Article · Topics: Apple Platform Ecosystem · Foundation & Data Formats · Swift
  **NeKI brief:** Surveys the WWDC 2026 developer-tool changes across Xcode, Swift, and Foundation Models. Use it as a release-oriented map of new workflows, then verify specific APIs, deployment requirements, and availability in Apple's current documentation.
- [SwiftUI Best Practices, straight from Apple’s Xcode 27 Agent Skill](https://www.avanderlee.com/ai-development/swiftui-best-practices-xcode-27-agent-skill) — Article · Topics: Swift · SwiftUI · Xcode
  **NeKI brief:** Turns Apple’s Xcode 27 SwiftUI guidance into an agent skill covering state flow, view composition, accessibility, and previews. The link is useful for making code-generation prompts enforce framework conventions instead of merely producing compilable views.
- [Swift Bits: My Top Xcode CI Environment Variables](https://antongubarenko.substack.com/p/swift-bits-my-top-xcode-ci-environment) — Article · Topics: Developer Tools · Swift · Xcode
  **NeKI brief:** Collects Xcode-related environment variables that can make CI jobs more predictable and diagnosable. Follow it when hardening build scripts, while checking each variable against the project's Xcode version and the behavior of its hosted runners.
- [Getting Started with Apple’s Foundation Models](https://artemnovichkov.com/blog/getting-started-with-apple-foundation-models) — Article · Topics: AI Development · Foundation & Data Formats
  **NeKI brief:** Demonstrates rendering Markdown in SwiftUI. Useful for choosing a rendering pipeline, handling attributed content, and deciding where links and styling should remain controlled by the app.
- [FoundationModelsKit](https://divyaravidev.substack.com/p/introducing-foundationmodelskit-production) — Article · Topics: AI Development · Foundation & Data Formats · Swift
  **NeKI brief:** Introduces FoundationModelsKit for production-oriented use. Useful for evaluating a wrapper around Apple’s model APIs while keeping availability, model behavior, and app-level safeguards explicit.
- [Apple’s WWDC26 AI Story Is About Control, Not Just Models](https://jonbrown.org/blog/apple-intelligence-xcode-wwdc26-platform-control) — Article · Topics: AI Development · Apple Platform Ecosystem · Xcode
  **NeKI brief:** Argues that Apple’s AI direction emphasizes platform control and developer tooling. Useful for strategic context when assessing how Foundation Models and Xcode capabilities shape implementation choices.
- [How I use FlowDeck to let my AI agent build and run my apps](https://www.donnywals.com/how-i-use-flowdeck-to-let-my-ai-agent-build-and-run-my-apps) — Article · Topics: AI Development
  **NeKI brief:** Describes an agent workflow that can build and run an iOS app through FlowDeck. Follow it to inspect the boundary between generated code, simulator execution, and human review before adopting agent-controlled delivery loops.
- [5 biggest Liquid Glass changes in iOS 27 and macOS 27](https://www.cultofmac.com/news/liquid-glass-changes-ios-27-macos-27) — Article · Topics: Liquid Glass · macOS & AppKit
  **NeKI brief:** Summarizes major Liquid Glass changes in iOS 27 and macOS 27. Useful for high-level UI migration awareness before checking exact behavior in Apple documentation and SDKs.

## [Issue 274](https://thosewhoswift.substack.com/p/those-who-swift-issue-274)

- Published: `2026-07-08`

**Topics:** Concurrency · Observation & State Management · Performance · Persistence & Synchronisation · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 274 · Weekly note ✏️

**Selected links:**
- [Understanding Sendable In Swift](https://tanaschita.com/swift-concurrency-sendable) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains Sendable and the compiler's concurrency-safety model with practical Swift examples. Use it when auditing values crossing actor boundaries and deciding whether types need immutable storage, explicit conformance, or isolation instead.
- [ConcentricRectangle And ContainerRelativeShape](https://swiftui-garden.com/Reference/ConcentricRectangle-and-ContainerRelativeShape) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Provides a focused SwiftUI reference for ConcentricRectangle and ContainerRelativeShape. Use it when creating shapes that follow container geometry or platform corner conventions, and compare the examples with the deployment targets your layout must support.
- [Reordering SwiftData In List And Grid](https://www.youtube.com/watch?v=m5VdG-EKnmk) — Video · Topics: Swift · SwiftData
  **NeKI brief:** Implements List movement and LazyVGrid drag-and-drop, first in memory and then with SwiftData sort-order persistence. A custom DropDelegate updates visual order during dragging and saves only when the operation completes.
- [Custom Bindings In SwiftUI: Closures Vs Subscripts](https://nilcoalescing.com/blog/CustomBindingsInSwiftUIClosuresVsSubscripts) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Compares closure-based and subscript-based custom Bindings in SwiftUI, including how each expresses read and write access. Use it when designing reusable bindings and choosing an approach that keeps transformations clear, composable, and maintainable.
- [Defer In Swift Explained With Code Examples](https://www.avanderlee.com/swift/defer-usage-swift) — Article · Topics: Swift
  **NeKI brief:** Explains defer’s reverse-order cleanup semantics, scope boundaries, and Swift 6.4’s support for asynchronous cleanup. The examples help decide where resource-release code belongs and avoid assuming defer runs at task or function completion.
- [iOS27: CADisplayLink for UIWindowScene](https://antongubarenko.substack.com/p/ios27-cadisplaylink-for-uiwindowscene) — Article · Topics: UIKit
  **NeKI brief:** This article explains why CADisplayLink is frame-synchronized while Timer is schedule-based, then applies that distinction to visual periodic work in a UIWindowScene. It helps decide when display-refresh timing is appropriate for iOS 27 UI updates.
- [What’s New In Swift: June 2026 Edition](https://www.swift.org/blog/whats-new-in-swift-june-2026) — Article · Topics: Apple Platform Ecosystem · Swift
  **NeKI brief:** Examines June digest in the context of Swift and SwiftUI. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [SwiftUI .crossFade Navigation Transition In iOS 27](https://www.sagarunagar.com/blog/swiftui-crossfade-navigation-transition) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Sagar explores SwiftUI’s new crossFade navigation transition, showing how to apply it and when it’s a better fit than zoom transitions for smooth, context-independent navigation.
- [Modern iOS Performance Myths: Episode 1](https://www.youtube.com/watch?v=F7cvw2_m_b4) — Video · Topics: Performance · Swift
  **NeKI brief:** Reviews Modern iOS Performance Myths: Episode 1. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [AI Agent Skills For iOS Development](https://livsycode.com/best-practices/ai-agent-skills-for-ios-development) — Article · Topics: AI Development
  **NeKI brief:** Introduces AI-agent skills for iOS development. Useful for organizing repeatable platform workflows and separating tool instructions from project-specific engineering judgment.
- [The iOS Core Engineering Series — Volume 1](https://anubhav52.gumroad.com/l/txbtwg?layout=discover&recommended_by=search&_gl=1%2A1e2sg2v%2A_ga%2AMTAxODg0NTgzOC4xNzgzNTE0MDA0%2A_ga_6LJN6D94N6%2AczE3ODM1MTQwMDQkbzEkZzEkdDE3ODM1MTQwMjckajM3JGwwJGgw) — Article · Topics: Objective-C & Cocoa
  **NeKI brief:** Reviews The iOS Core Engineering Series — Volume 1. Useful as a focused reference for evaluating the described workflow or technology, while validating current platform behavior and project-specific constraints against primary documentation.
- [Claude Cowork On Web And Mobile](https://claude.com/blog/cowork-web-mobile) — Article
  **NeKI brief:** Presents Claude Cowork across web and mobile contexts. Useful for comparing agent surfaces, context continuity, and permission boundaries in mobile development workflows.

## [Issue 273](https://thosewhoswift.substack.com/p/those-who-swift-issue-273)

- Published: `2026-07-01`

**Topics:** Objective-C & Cocoa · Security & Privacy · Swift · SwiftUI · Testing · Xcode

**Sections:** Those Who Swift · Those Who Swift - Issue 273 · Weekly note ✏️

**Selected links:**
- [What’s New In SwiftUI For iOS 27?](https://www.youtube.com/watch?v=tNxEqyUVGck) — Video · Topics: Architecture · Swift · SwiftUI
  **NeKI brief:** Surveys iOS 27 SwiftUI changes including lazy @State creation, compile-time improvements, reorderable containers, swipe actions outside List, and the Document protocol. Useful as a migration map before checking final SDK semantics.
- [Understanding Privacy Manifests In iOS](https://tanaschita.com/ios-privacy-manifests) — Article · Topics: Security & Privacy · Xcode
  **NeKI brief:** Explains iOS privacy manifests, including required-reason APIs, declarations, and how app and third-party SDK manifests combine. Use it when auditing App Store compliance and documenting data-access reasons without confusing privacy manifests with permission prompts.
- [SwiftUI Is One Graph, Over 40+ Years of Engineering](https://aleahim.com/blog/swiftui-is-one-graph) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Uses SwiftUI's graph model to explain how declarative descriptions, dependencies, and updates fit together. Useful for forming a concrete mental model before diagnosing invalidation, identity, or unexpected recomputation in complex view hierarchies.
- [Using Cursor In Xcode 27](https://www.polpiella.dev/cursor-xcode-27) — Article · Topics: Xcode
  **NeKI brief:** Explains installing Cursor’s agent CLI, registering it through Xcode 27’s ACP support, and selecting it for new conversations. Follow it when comparing external agent choice with Xcode’s remembered conversation-agent state.
- [Reordering Beyond List - SwiftUI iOS 27](https://www.sagarunagar.com/blog/swiftui-reorderable-lazy-layouts-ios-27) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains the newer SwiftUI reordering path for LazyVStack, LazyVGrid, and custom layouts, contrasting it with hand-built drag and drop. Useful when List is too restrictive but users still need a native item-rearrangement interaction.
- [A Custom Pull-to-Refresh In SwiftUI](https://livsycode.com/swiftui/a-custom-pull-to-refresh-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a custom pull-to-refresh interaction in SwiftUI. Useful for understanding gesture state, refresh triggering, and loading feedback when the platform default does not fit the required interaction.
- [Proposing Task-Local Test Traits For Swift Testing](https://www.pointfree.co/blog/posts/217-proposing-task-local-test-traits-for-swift-testing) — Article · Topics: Swift · Testing
  **NeKI brief:** Proposes task-local test traits for Swift Testing, based on patterns developed in Point-Free libraries. The article is useful for understanding how per-test configuration could compose with structured concurrency before the proposal becomes platform API.
- [Claude Science, An AI Workbench For Scientists, Is Now Available](https://www.anthropic.com/news/claude-science-ai-workbench) — Article · Topics: AI Development · Objective-C & Cocoa
  **NeKI brief:** Reviews Claude Science, An AI Workbench For Scientists, Is Now Available. Useful as a focused reference for evaluating the described workflow or technology, while validating current platform behavior and project-specific constraints against primary documentation.
- [Introducing Claude Sonnet 5](https://www.anthropic.com/news/claude-sonnet-5) — Article · Topics: AI Development
  **NeKI brief:** Reviews Introducing Claude Sonnet 5. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.

## [Issue 272](https://thosewhoswift.substack.com/p/those-who-swift-issue-272)

- Published: `2026-06-24`

**Topics:** Apple Platform Ecosystem · Concurrency · Liquid Glass · Macros & Metaprogramming · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 272 · Weekly note ✏️

**Selected links:**
- [Liquid Glass In SwiftUI: How To Modernize An iOS App Template](https://iosapptemplates.com/blog/liquid-glass-swiftui-app-template-modernization) — Article · Topics: Liquid Glass · Swift · SwiftUI
  **NeKI brief:** Walks through modernizing a SwiftUI template with Liquid Glass styling. Use it to identify migration touchpoints in an existing UI, then validate visual hierarchy, accessibility, and API availability rather than applying the template wholesale.
- [Swift 6.4: What’s New In Concurrency](https://www.avanderlee.com/concurrency/swift-6-4-whats-new-in-concurrency) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Surveys Swift 6.4 concurrency additions with runnable examples, highlighting changes that affect isolation, task behavior, and migration choices. It is a compact map for checking which language improvements are relevant before changing production concurrency code.
- [Swift Macros Demystified: Build A Freestanding Expression Macro](https://www.youtube.com/watch?v=7W6R2TIoEW8) — Video · Topics: Macros & Metaprogramming · Swift
  **NeKI brief:** Builds a freestanding #URL Swift macro that validates literals at compile time. The walkthrough connects package structure, syntax-tree inspection, expansion, and custom SwiftDiagnostics so invalid inputs produce targeted compiler errors.
- [UIPortalView: From Live Mirroring to Liquid Glass-Style Effects](https://livsycode.com/uikit/exploring-_uiportalview-live-view-replication-without-copying-or-snapshots) — Article · Topics: Graphics, Media & Games · Liquid Glass · UIKit
  **NeKI brief:** Artem dives deep on how the private UIKit _UIPortalView mirrors live view content without duplicating view hierarchies or taking snapshots, using it as a window into how UIKit, Core Animation, and Liquid Glass-style effects compose live UI at the rendering…
- [WWDC26: SwiftUI Group Lab 2nd - Q&A](https://antongubarenko.substack.com/p/wwdc26-swiftui-group-lab-2nd-q-and) — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Summarizes questions and answers from the second WWDC26 SwiftUI Group Lab, capturing implementation guidance and framework constraints discussed with Apple engineers. Useful as contextual follow-up when an API’s behavior is unclear from documentation alone.
- [discussions](https://www.them.us/story/discord-has-stopped-using-peter-thiel-backed-software-tied-to-us-surveillance) — Article · Topics: AI Development · Security & Privacy
  **NeKI brief:** Reviews discussions. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Actors In Swift: The Problem They Solve And How It Works](https://www.swiftdifferently.com/blog/swift/concurrency/how-actors-work) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Omar explains why Swift actors exist, how actor isolation protects shared mutable state, and what happens under the hood.
- [SwiftUI’s New Item Based Presentations In iOS 27](https://www.sagarunagar.com/blog/swiftui-item-based-alert-confirmation-dialog) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Sagar covers iOS 27’s new item-based alerts and confirmation dialogs in SwiftUI, where optional item or error state can drive presentation directly without extra Boolean flags or synchronization bugs.
- [rolling out identity verification](https://support.claude.com/en/articles/14328960-identity-verification-on-claude) — Article
  **NeKI brief:** Reviews rolling out identity verification. Useful as a focused reference for evaluating the described workflow or technology, while validating current platform behavior and project-specific constraints against primary documentation.

## [Issue 271](https://thosewhoswift.substack.com/p/those-who-swift-issue-271)

- Published: `2026-06-18`

**Topics:** AI Development · Apple Platform Ecosystem · Foundation & Data Formats · Swift · SwiftUI · Testing

**Sections:** Those Who Swift · Those Who Swift - Issue 271 · Weekly note ✏️

**Selected links:**
- [Testing Foundation Models: Code That Won’t Give The Same Answer Twice](https://www.wesleymatlock.com/testing-on-device-ai-swift-testing) — Article · Topics: AI Development · Foundation & Data Formats · Testing
  **NeKI brief:** Discusses testing nondeterministic Foundation Models output with Swift Testing. Use it when designing assertions for on-device AI, focusing on stable structure, bounded behavior, and controlled inputs instead of brittle exact-text comparisons.
- [Build a Swift Terminal Developer Toolkit with TUIkit](https://www.youtube.com/watch?v=hqDurFnEJs8) — Video · Topics: Developer Tools · Swift · UIKit
  **NeKI brief:** Builds a Swift TUIkit terminal application with Pomodoro, Git-status, and release-tracking panels. The walkthrough covers NavigationSplitView-style composition, PulseTimer, shell commands, AppStorage persistence, and TUI-specific state-update constraints.
- [Async Cleanup In defer With Swift 6.4](https://livsycode.com/swift/async-cleanup-in-defer-with-swift-6-4) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains asynchronous cleanup in defer with Swift 6.4. Follow it when resource release itself must await work, and verify execution order, cancellation behavior, and toolchain support before introducing async cleanup into production paths.
- [Using Claude With Apple Foundation Models](https://artemnovichkov.com/blog/using-claude-with-apple-foundation-models) — Article · Topics: AI Development · Foundation & Data Formats
  **NeKI brief:** Artem shows how Claude can be used into Apple’s Foundation Models framework on iOS 27, using the same LanguageModelSessionAPI to switch between on-device models and Claude.
- [Custom Scroll Layouts With Swipe Actions In SwiftUI On iOS 27](https://nilcoalescing.com/blog/CustomScrollLayoutsWithSwipeActionsInSwiftUIOnIOS27) — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Shows custom scroll layouts combined with swipe actions in SwiftUI on iOS 27. Use it when list-like interactions need nonstandard geometry without giving up contextual swipe affordances.
- [What’s New In SwiftData For iOS 27](https://azamsharp.com/2026/06/12/whats-new-in-swiftdata.html) — Article · Topics: Cross-Platform & Web · Swift · SwiftData
  **NeKI brief:** Mohammad covers what’s new in SwiftData for iOS 27, showing how enum predicates, sectioned queries, compound predicates, the new .codable attribute, and ResultsObserver remove common workarounds.
- [WWDC26 Group Labs: The Real Story Isn’t Foundation Models. It’s Evaluation.](https://divyaravidev.substack.com/p/wwdc26-group-labs-the-real-story) — Article · Topics: AI Development · Apple Platform Ecosystem · Foundation & Data Formats
  **NeKI brief:** Reports on WWDC26 group labs and evaluation around Foundation Models. Useful for understanding model assessment as an engineering concern rather than relying on demo quality alone.
- [(Some) Unanswered Swift Group Questions](https://www.massicotte.org/blog/wwdc26-unanswered-qa) — Article · Topics: Apple Platform Ecosystem · Swift
  **NeKI brief:** Collects Swift Group questions that remained unanswered around WWDC26, making uncertainty visible instead of implying unsupported behavior. Useful for identifying topics that need direct documentation or reproducible experiments.
- [WWDC26: Swift Group Lab – Q&A](https://antongubarenko.substack.com/p/wwdc26-swift-group-lab-q-and-a) — Article · Topics: Apple Platform Ecosystem · Swift
  **NeKI brief:** Summarizes SwiftUI Group Lab questions from WWDC26, capturing practical API clarifications and design guidance that are easy to miss in session videos. Useful as a focused follow-up for current SwiftUI adoption decisions.
- [SwiftUI’s New .prominent Tab In iOS 27 Is Not A Floating Action Button](https://www.sagarunagar.com/blog/swiftui-prominent-tab-is-not-a-floating-action-button) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Sagar shares why SwiftUI’s new .prominent tab role should be used to highlight important destinations, not as a replacement for floating action buttons, toolbar actions, or “add” buttons.
- [Statement On The US Government Directive To Suspend Access To Fable 5 And Mythos 5](https://www.anthropic.com/news/fable-mythos-access) — Article
  **NeKI brief:** Reviews Statement On The US Government Directive To Suspend Access To Fable 5 And Mythos 5. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.

## [Issue 270](https://thosewhoswift.substack.com/p/those-who-swift-issue-270)

- Published: `2026-06-10`

**Topics:** App Distribution & Store Operations · Apple Platform Ecosystem · Macros & Metaprogramming · Networking · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 270 · Weekly note ✏️

**Selected links:**
- [SwiftUI’s State Is Now A Macro](https://livsycode.com/swiftui/swiftuis-state-is-now-a-macro) — Article · Topics: Macros & Metaprogramming · Swift · SwiftUI
  **NeKI brief:** Explains SwiftUI's newer macro-based state capabilities and their effect on view-state declarations. Use it when evaluating whether an existing property-wrapper pattern can be simplified without changing ownership or lifecycle semantics.
- [SwiftUI Localization Guide — Change Language Without Restarting The App](https://www.sagarunagar.com/blog/swiftui-app-language-switching-without-restart) — Article · Topics: Localization · Swift · SwiftUI
  **NeKI brief:** Shows how a SwiftUI app can switch its language without restarting. Use it when evaluating runtime locale changes, while checking environment propagation, persistence, pluralization, and state refresh behavior across the app's navigation tree.
- [Announcing The Networking Workgroup](https://www.swift.org/blog/announcing-networking-workgroup) — Article · Topics: Networking · Swift
  **NeKI brief:** Announces Swift's Networking Workgroup and its role in coordinating networking APIs and ecosystem direction. Use it for project discovery and community context, not as a substitute for the concrete package or API documentation used in implementation.
- [iOS 27: Notable UIKit Additions](https://www.swiftjectivec.com/ios-27-notable-uikit-additions) — Article · Topics: Developer Career & Practice · Swift · UIKit
  **NeKI brief:** Jordan walks you through the notable UIKit additions in iOS 27, focusing on practical updates to navigation bars, bar buttons, scenes, windows, tab bars, sidebars, menus, and document launch screens.
- [What Is New In SwiftUI After WWDC26](https://swiftwithmajid.com/2026/06/08/what-is-new-in-swiftui-after-wwdc26) — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Summarizes SwiftUI additions after WWDC 2026. Use it to discover relevant new layout, rendering, and system-integration capabilities before narrowing to one feature and reading its authoritative API documentation.
- [SwiftUI: Observable Macro Under The Hood](https://www.nsvasilev.com/posts/swiftui-observable-macro) — Article · Topics: Macros & Metaprogramming · Swift · SwiftUI
  **NeKI brief:** Peels back SwiftUI’s Observable macro expansion, showing the generated observation machinery behind an @Observable model. Useful when diagnosing tracking behavior, deciding which properties need observation, or explaining macro-generated code to a team.
- [What’s New In Swift: May 2026 Edition](https://www.swift.org/blog/whats-new-in-swift-may-2026) — Article · Topics: Swift · Systems Programming
  **NeKI brief:** Reviews What’s New In Swift: May 2026 Edition. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [SwiftUI Animation Timing](https://nilcoalescing.com/blog/AnimationTimingInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Breaks down SwiftUI animation timing and how duration, delay, and timing curves shape transitions. Use it when a visual effect feels out of sync and the fix requires separating state change from animation parameters.
- [Styling Measurement Unit Fonts In SwiftUI](https://nilcoalescing.com/blog/StylingMeasurementUnitFontsInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows styling measurement-unit fonts in SwiftUI so values and units retain intentional hierarchy. Follow it when displaying measurements, percentages, or localized quantities where typography should distinguish numeric content from its unit.
- [Claude Fable 5 and Claude Mythos 5](https://www.anthropic.com/news/claude-fable-5-mythos-5) — Article
  **NeKI brief:** Reviews Claude Fable 5 and Claude Mythos 5. Useful as a focused reference for evaluating the described workflow or technology, while validating current platform behavior and project-specific constraints against primary documentation.

## [Issue 269](https://thosewhoswift.substack.com/p/those-who-swift-issue-269)

- Published: `2026-06-04`

**Topics:** AI Development · Apple Platform Ecosystem · Concurrency · Security & Privacy · Swift · Xcode

**Sections:** Those Who Swift · Those Who Swift - Issue 269 · Weekly note ✏️

**Selected links:**
- [Task Names In Swift Concurrency](https://artemnovichkov.com/blog/task-names-in-swift-concurrency) — Article · Topics: Concurrency · Performance · Swift
  **NeKI brief:** Artem explains Swift Concurrency task names, showing how to label Task, Task.detached, task groups, and SwiftUI .task calls so they’re easier to identify in LLDB, Instruments, and logs.
- [Enter Sandman Mode: Three Months Inside Xcode 26.3’s Agentic Coding](https://medium.com/@wesleymatlock/enter-sandman-mode-three-months-inside-xcode-26-3s-agentic-coding-cbe67ce46df9) — Article · Topics: AI Development · Concurrency · Xcode
  **NeKI brief:** Examines Enter Sandman Mode: Three Months Inside Xcode 26.3’s Agentic Coding, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Apple’s Hidden AI: Unlock Foundation Models on Your Mac with Apfel](https://www.youtube.com/watch?v=KlCqHP32c8M) — Video · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **NeKI brief:** Reviews Apple’s Hidden AI: Unlock Foundation Models on Your Mac with Apfel. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [How Do You Build A Mutex That Works With Async/Await?](https://www.swiftdifferently.com/blog/swift/concurrency/how-do-you-build-a-mutex-that-works-with-async-await) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Builds a mutex that works with async/await. Useful for comparing synchronous locking with actor-based isolation and avoiding blocking the cooperative concurrency runtime.
- [Reactive Frameworks Vs Async/Await Vs AsyncAlgorithms](https://livsycode.com/best-practices/reactive-is-no-longer-the-default-in-swift) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Compares reactive frameworks with async/await and AsyncAlgorithms. Useful for reviewing whether a stream-processing dependency still fits a project’s concurrency model and maintenance constraints.
- [Apple Music playlist](https://music.apple.com/ru/playlist/wwdc26-hello/pl.c2b332d45b194756aeb66a44329a2a08?l=en-GB) — Article · Topics: Apple Platform Ecosystem · Developer Community & Business · Graphics, Media & Games
  **NeKI brief:** Links an Apple Music playlist. Useful only as media navigation, not as a knowledge-index reading source.
- [Registering For Push Notifications In SwiftUI](https://tanaschita.com/ios-notifications-registering-in-swiftui) — Article · Topics: App Services & Extensions · Swift · SwiftUI
  **NeKI brief:** Walks through requesting notification authorization and registering a SwiftUI app for remote notifications. Use it to separate permission timing, device-token registration, and app lifecycle handling instead of treating registration as one synchronous call.
- [Modern iOS Security: Attacks, Defenses & AI](https://www.youtube.com/watch?v=Jtk4O1rDKTI) — Video · Topics: AI Development · Security & Privacy · Swift
  **NeKI brief:** Reviews Modern iOS Security: Attacks, Defenses & AI. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Building For Voice In, Visuals Out](https://allenpike.com/2026/voice-in-visuals-out) — Article · Topics: AI Development
  **NeKI brief:** Examines voice-first app design where visual output is secondary. Useful for evaluating interaction flows, accessibility, and feedback when an iOS experience must work without relying on persistent screen attention.
- [Stateless Actors](https://www.massicotte.org/stateless-actors) — Article · Topics: Concurrency
  **NeKI brief:** Examines stateless actors and what remains useful about actor isolation when no mutable state is stored. Follow it when choosing concurrency boundaries, distinguishing synchronization guarantees from mere type organization and measuring whether an actor adds real value.

## [Issue 268](https://thosewhoswift.substack.com/p/those-who-swift-issue-268)

- Published: `2026-05-27`

**Topics:** Accessibility · Concurrency · Persistence & Synchronisation · Security & Privacy · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 268 · Weekly note ✏️

**Selected links:**
- [Modern Isn’t A Value. Fit Is.](https://www.swiftdifferently.com/blog/system-desgin/modern-isnot-a-value-fit-Is) — Article · Topics: Architecture · Concurrency · Objective-C & Cocoa
  **NeKI brief:** Argues that modern APIs are not automatically the right fit for every product or codebase. Use it as an architecture prompt: weigh compatibility, team understanding, migration cost, and user value before adopting a newer framework pattern.
- [SwiftUI Should Become Open-Source](https://macguru.dev/swiftui-should-become-open-source) — Article · Topics: Hardware & Devices · Swift · SwiftUI
  **NeKI brief:** Makes a case for opening SwiftUI's implementation and discusses how transparency could affect the ecosystem. Treat it as opinion and community perspective, useful for framing trade-offs rather than as evidence about Apple's roadmap or framework internals.
- [Swift Task Lifecycle Management - Structured vs Unstructured Concurrency](https://www.sagarunagar.com/blog/swift-task-lifecycle-management) — Article · Topics: Concurrency · Developer Career & Practice · Swift
  **NeKI brief:** Sagar explains Swift task lifecycle management by comparing structured and unstructured concurrency, showing how choices like async let, TaskGroup, SwiftUI’s .task, Task, and Task.detached affect cancellation, errors, memory, and UI.
- [Decoupling SwiftData in SwiftUI: Is It Worth It?](https://www.youtube.com/watch?v=2so9ifq5hYY) — Video · Topics: Swift · SwiftData · SwiftUI
  **NeKI brief:** Implements protocol-backed SwiftData and SQLite stores, then examines the cost of losing SwiftData's automatic UI integration. Useful for deciding when persistence abstraction improves testability and when it merely adds architectural overhead.
- [W.W.D.C. 2026: The Pregame Quiz](https://www.swiftjectivec.com/wwdc-2026-the-pregame-quiz) — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem · Graphics, Media & Games
  **NeKI brief:** Presents W.W.D.C. 2026: The Pregame Quiz, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Anthropic Co-Founder Chris Olah’s Remarks On Pope Leo XIV’s Encyclical “Magnifica Humanitas”](https://www.anthropic.com/news/chris-olah-pope-leo-encyclical) — Article · Topics: AI Development
  **NeKI brief:** Examines Anthropic Co-Founder Chris Olah’s Remarks On Pope Leo XIV’s Encyclical “Magnifica Humanitas”, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Making A SwiftUI Sheet Automatically Size To Fit Its Content](https://danielsaidi.com/blog/2026/05/22/making-a-swiftui-sheet-automatically-size-to-fit-its-content) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI sheet that measures its content and chooses an appropriate presentation height. Useful for compact forms and detail panels that should avoid excessive empty space while handling dynamic type and updates.
- [Working With The Keychain In iOS](https://tanaschita.com/ios-keychain-secure-data-storage) — Article · Topics: Persistence & Synchronisation · Security & Privacy
  **NeKI brief:** Explains storing sensitive iOS data in Keychain and the accessibility choices that affect availability. Use it when designing credential persistence, selecting protection classes, and separating secrets from ordinary app storage.
- [Refreshing And Animating Views Using TimelineView In SwiftUI](https://nilcoalescing.com/blog/TimelineViewInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Uses TimelineView to refresh SwiftUI content on a schedule without manually managing a timer. Follow it for clocks, elapsed-time displays, and periodic UI updates where lifecycle and cadence should remain declarative.
- [UniqueBox, Ref, And MutableRef In Swift 6.4](https://livsycode.com/swift/uniquebox-ref-and-mutableref-in-swift-6-4) — Article · Topics: Swift
  **NeKI brief:** Explores UniqueBox, Ref, and MutableRef in Swift 6.4. Useful for examining ownership and mutation techniques that trade convenience against explicit lifetime and uniqueness guarantees.
- [Making Accessibility Accessible](https://www.basbroek.nl/making-accessibility-acceessible) — Article · Topics: Accessibility
  **NeKI brief:** Discusses making accessibility more approachable in iOS development. Useful for reviewing inclusive design practices and integrating accessibility checks into ordinary implementation work.

## [Issue 267](https://thosewhoswift.substack.com/p/those-who-swift-issue-267)

- Published: `2026-05-21`

**Topics:** Accessibility · AI Development · App Distribution & Store Operations · Apple Platform Ecosystem · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 267 · Weekly note ✏️

**Selected links:**
- [Using Xcode MCP With Claude Code](https://danielsaidi.com/blog/2026/04/30/using-xcode-mcp-with-claude-code) — Article · Topics: AI Development · Swift · Xcode
  **NeKI brief:** Describes connecting Claude Code to Xcode through Model Context Protocol. Follow it when evaluating agent-assisted build and debugging workflows, paying attention to permissions, simulator boundaries, generated changes, and human review checkpoints.
- [ContentUnavailableView In SwiftUI - Complete Guide With Examples](https://www.sagarunagar.com/blog/contentunavailableview-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates ContentUnavailableView for empty, failed, or unavailable SwiftUI states with labels and actions. Useful for standardizing placeholder screens while preserving semantic messaging and a clear recovery path.
- [Understanding Basic Animations In SwiftUI](https://tanaschita.com/swiftui-basic-animations) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Introduces SwiftUI's state-driven animation model through basic transitions and modifiers. Follow it when mapping a state change to a visual effect and checking which view values actually participate in interpolation.
- [How To Recognize Text In Images With Vision In Swift](https://onmyway133.com/posts/how-to-recognize-text-in-images-with-vision-in-swift) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Shows text recognition in images with Apple's Vision framework. Use it when prototyping OCR, considering request configuration, region or language hints, result confidence, and asynchronous image processing before integrating recognized text into user-visible features.
- [Understanding Swift Result Builders-The Power Behind ViewBuilder](https://www.youtube.com/watch?v=dW6KeYCqCFc) — Video · Topics: Swift · SwiftUI
  **NeKI brief:** Reviews Understanding Swift Result Builders-The Power Behind ViewBuilder. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [A Feature Flags System In Swift](https://livsycode.com/best-practices/a-feature-flags-system-in-swift) — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **NeKI brief:** Presents a Swift feature-flags design with centralized evaluation and rollout control. Use it to compare configuration models and testing seams, while ensuring flag ownership, expiration, and failure defaults are explicit in production.
- [Deprecating Your Own Convenience API](https://swiftwithmajid.com/2026/05/19/deprecating-your-own-convenience-api) — Article · Topics: Swift
  **NeKI brief:** Explains deprecating a convenience API with migration messages and replacement paths. Use it when evolving an internal or public Swift interface while keeping callers compiling and making the preferred alternative discoverable.
- [How Claude Code Works In Large Codebases: Best Practices And Where To Start](https://claude.com/blog/how-claude-code-works-in-large-codebases-best-practices-and-where-to-start) — Article · Topics: AI Development
  **NeKI brief:** Explains how Claude Code works in large codebases. Useful for understanding repository context, navigation, and staged agent changes before trusting automation on a complex project.
- [Tracking App Store Purchases With Server Notifications](https://azamsharp.com/2026/05/16/storekit2-app-store-server-notifications.html) — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **NeKI brief:** Explains App Store server notifications for tracking subscription purchases. Useful for separating server-confirmed transaction state from client presentation and for designing entitlement updates that survive missed app launches.
- [Optimizing For VoiceOver And Voice Control](https://www.basbroek.nl/optimizing-assistive-technology) — Article · Topics: Accessibility · Combine & Reactive Programming
  **NeKI brief:** Explores optimization for assistive technology such as VoiceOver and Voice Control. Useful for checking labels, focus, and interaction semantics beyond visual layout correctness.
- [Claude Code Just Dropped /Goal (Master It In 8 Minutes)](https://www.youtube.com/watch?v=aMfig5cKOtY) — Video
  **NeKI brief:** Reviews Claude Code Just Dropped /Goal (Master It In 8 Minutes). Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.

## [Issue 266](https://thosewhoswift.substack.com/p/those-who-swift-issue-266)

- Published: `2026-05-13`

**Topics:** Architecture · Networking · Objective-C & Cocoa · Performance · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 266 · Weekly note ✏️

**Selected links:**
- [How To Think About Performance In iOS](https://livsycode.com/best-practices/how-to-think-about-performance-in-ios) — Article · Topics: Architecture · Networking · Performance
  **NeKI brief:** Artem walks through iOS performance as a layered system covering metrics, architecture, UI rendering, networking, caching, memory, and CPU behavior.
- [Production SwiftUI: Scalable Networking Architecture With Async/Await And Generics](https://www.youtube.com/watch?v=M5ZUGBeugP4) — Video · Topics: Architecture · Concurrency · Networking
  **NeKI brief:** Builds a protocol-driven SwiftUI networking stack with a Sendable API client, typed errors, endpoints, services, dependency injection, and preview mocks. The architectural discussion clarifies boundaries between view models, services, and concurrency isolation.
- [Cut Your Swift Compile Times with Xcode 26](https://watch.getcontrast.io/register/bitrise-how-to-speed-up-ios-builds-with-xcode-26-compilation-caching) — Article · Topics: Swift · Xcode
  **NeKI brief:** This Bitrise session registration page covers techniques for improving iOS build speed with Xcode 26 compilation caching. Use it to discover CI optimization guidance, then validate recommendations against the project’s toolchain and measured build traces.
- [Accelerate Framework In Swift - Complete Guide To High-Performance Computing](https://www.sagarunagar.com/blog/accelerate-framework-swift-guide) — Article · Topics: Performance · Swift
  **NeKI brief:** Introduces Apple's Accelerate framework through Swift examples for vector and numerical workloads. Use it when evaluating CPU-intensive computations, comparing optimized primitives with simpler code, and checking memory layout, precision, and platform availability.
- [Agent View In Claude Code](https://claude.com/blog/agent-view-in-claude-code) — Article · Topics: Personal Essays · Testing
  **NeKI brief:** Introduces an agent view in Claude Code. Useful for understanding how a coding agent exposes progress and interaction state during development workflows, with human review still required for generated changes.
- [SwiftUI: @State Under The Hood](https://www.nsvasilev.com/posts/swiftui-state) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explores SwiftUI @State storage and its relationship to view identity and lifetime. Useful for diagnosing resets, deciding which state belongs in a view, and explaining why a local mutation survives recomputation.
- [The CTO’s Incoming Storms](https://ctosub.com/p/the-ctos-incoming-storms) — Article · Topics: AI Development · Maps & Location
  **NeKI brief:** Discusses incoming risks and decisions for CTOs. Useful as engineering-leadership context when evaluating organizational resilience, technical strategy, and the operational consequences of shipping systems under changing constraints.
- [Finally Found A Use Case For .fixedSize](https://www.swiftdifferently.com/blog/swiftui/fixedsize-usecase) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Omar explains how .fixedSize(horizontal: false, vertical: true) solves a tricky card height layout problem in a horizontal scroll view.
- [SwiftData for Beginners](https://www.youtube.com/watch?v=mgUYC6TWbSM) — Video · Topics: Swift · SwiftData
  **NeKI brief:** Reviews SwiftData for Beginners. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.

## [Issue 265](https://thosewhoswift.substack.com/p/those-who-swift-issue-265)

- Published: `2026-05-06`

**Topics:** AI Development · Concurrency · Objective-C & Cocoa · Security & Privacy · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 265 · Weekly note ✏️

**Selected links:**
- [Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [Scheduling And Handling Background App Refresh In SwiftUI](https://nilcoalescing.com/blog/SchedulingAndHandlingBackgroundAppRefreshInSwiftUI) — Article · Topics: App Services & Extensions · Swift · SwiftUI
  **NeKI brief:** Shows how a SwiftUI app enables, schedules, handles, and tests background refresh work using Background Tasks and backgroundTask(_:action:).
- [Swift Concurrency: One await, Two Actors: A Runtime Trace](https://adjoe.io/company/engineer-blog/swift-concurrency-await-runtime-trace-executor-hops) — Article · Topics: Concurrency · Objective-C & Cocoa · Swift
  **NeKI brief:** Traces how an await can move execution between actors and executors at runtime. Follow it when diagnosing latency or unexpected scheduling, using Instruments or logs to validate hops instead of inferring behavior from source order alone.
- [Apple Foundation Models With Mohammad Azam](https://www.youtube.com/watch?v=UeZfiKBHUCs&list=PL2iZPZus2bhSl3CDE_vs2851UMgix285u) — Video · Topics: AI Development · Foundation & Data Formats · Objective-C & Cocoa
  **NeKI brief:** Reviews Apple Foundation Models With Mohammad Azam. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [iOS Privacy Manifest & Required Reasons APIs: A Compliance Checklist](https://idiotswithios.com/ios-privacy-manifest-required-reasons-apis-compliance-checklist) — Article · Topics: Security & Privacy
  **NeKI brief:** Explains required-reason API declarations in Apple privacy manifests. Useful for auditing SDK and app dependencies before submission and connecting API usage to the compliance metadata Apple expects.
- [Actors Vs Queues Vs Locks In Swift](https://livsycode.com/best-practices/actors-vs-queues-vs-locks-in-swift) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Artem compares actors, queues, and locks in Swift, showing when each is useful for safely synchronizing shared state and what trade-offs they bring.
- [3 Key Strategies To Make SwiftUI Views More Reusable](https://matteomanferdini.com/swiftui-reusable-views) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents three concrete strategies for making SwiftUI views reusable, from extracting components to controlling dependencies and state. Useful when reducing duplication without hiding feature-specific behavior behind overly generic abstractions.
- [Managing Personal Projects With Agents](https://krausefx.com/blog/managing-personal-projects-with-agents) — Article · Topics: AI Development
  **NeKI brief:** Describes managing personal projects with agents. Useful for understanding practical task decomposition and automation while keeping priorities, context, and human decisions explicit.
- [My Take On The New Apple](https://www.youtube.com/watch?v=i9TvUGeTltE) — Video
  **NeKI brief:** Reviews My Take On The New Apple. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Algorithms](https://jeffe.cs.illinois.edu/teaching/algorithms) — Article
  **NeKI brief:** Provides an algorithms course reference. Useful for grounding performance and data-structure decisions in established algorithmic trade-offs rather than intuition alone.

## [Issue 264](https://thosewhoswift.substack.com/p/those-who-swift-issue-264)

- Published: `2026-04-29`

**Topics:** App Distribution & Store Operations · Concurrency · Developer Community & Business · Objective-C & Cocoa · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 264 · Weekly note ✏️

**Selected links:**
- [Immediate Tasks In Swift Concurrency Explained](https://www.avanderlee.com/concurrency/immediate-tasks-in-swift-concurrency-explained) — Article · Topics: Concurrency · Personal Essays · Swift
  **NeKI brief:** Explains immediate tasks and their execution timing in Swift 6.2, contrasting them with ordinary task scheduling and actor hops. The examples clarify when reduced scheduling latency is useful and where ordering assumptions become unsafe.
- [Understanding Inout Parameters In Swift - How They Work And When To Use Them](https://www.sagarunagar.com/blog/swift-inout-parameters) — Article · Topics: Code Quality · Performance · Swift
  **NeKI brief:** Explains Swift inout parameters, including exclusivity and mutation semantics. Follow it when reviewing APIs that borrow mutable storage, especially where escaping closures, overlapping accesses, or value-copy expectations can make a seemingly simple call unsafe.
- [Paywall Design Tips That Boost App Sales - Part 2](https://indieappdevs.substack.com/p/indie-app-devs-21) — Article · Topics: Developer Community & Business · Swift · SwiftUI
  **NeKI brief:** Examines Paywall Design Tips That Boost App Sales - Part 2, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [I Couldn’t Find The Perfect Browser, So I Built One With AI In Two Weeks](https://www.swiftdifferently.com/blog/career-advice/how-I-built-full-browser-in-two-weeks) — Article · Topics: AI Development · Developer Career & Practice · Swift
  **NeKI brief:** Reviews I Couldn’t Find The Perfect Browser, So I Built One With AI In Two Weeks. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [iOS 26 SDK Migration Guide: What Every App Needs To Update](https://idiotswithios.com/ios-26-sdk-migration-guide-what-every-app-needs-to-update) — Article · Topics: Liquid Glass · Security & Privacy · Testing
  **NeKI brief:** Highlights migration areas when adopting the iOS 26 SDK, including project settings and UI changes. Use it as a checklist for an upgrade pass, then verify each required change against current Xcode release notes and API documentation.
- [How To Implement Pagination With SwiftUI’s List View](https://tanaschita.com/swiftui-list-pagination) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Implements incremental pagination in SwiftUI List as the user approaches the end of loaded content. Use it when an async data source needs explicit loading, error, and duplicate-request guards rather than eager full retrieval.
- [When SwiftUI Modifiers Hold Onto Memory Longer Than Expected](https://livsycode.com/swiftui/when-swiftui-modifiers-hold-onto-memory-longer-than-expected) — Article · Topics: Dependency Injection · Swift · SwiftUI
  **NeKI brief:** Explains when SwiftUI modifiers retain memory longer than expected. Useful for diagnosing ownership and lifetime surprises in view composition and validating suspected leaks with measurement.
- [Q&A: Swift Concurrency - Formatted](https://antongubarenko.substack.com/p/q-and-a-swift-concurrency-formatted) — Article · Topics: Concurrency · Objective-C & Cocoa · Swift
  **NeKI brief:** Answers practical Swift concurrency questions with formatted examples. Useful for comparing isolation, task structure, and compiler behavior against a concrete implementation rather than applying concurrency rules without checking their context.
- [Appearance Mode Changer](https://www.createchsol.com/blog/2026-04-28-appearance-mode-changer.html) — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **NeKI brief:** Introduces OAuth with illustrated explanations. Useful for understanding authorization roles, redirects, and token boundaries before integrating an OAuth flow into an app or service.
- [reached quickly](https://www.reddit.com/r/claude/comments/1soumaq/opus_47_30_in_just_5_minutes) — Article · Topics: Performance
  **NeKI brief:** Reviews reached quickly. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Enums. Swift’s Secret Superpower.](https://lumley.io/blogs/swift-enums) — Article · Topics: Objective-C & Cocoa · Swift
  **NeKI brief:** Explains Swift enums and their expressive modeling role. Useful for choosing between cases, associated values, and alternative representations when designing domain state.
- [Concurrency Step-By-Step: Designing Protocols](https://www.massicotte.org/step-by-step-designing-protocols) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Matt walks you through designing Swift protocols under Swift concurrency, explaining how choices like async requirements, nonisolated, and more specific constraints can make protocols safer and easier.
- [Microsoft Accidentally Told The Truth About AI](https://www.youtube.com/watch?v=4CIlTOnc6I8) — Video · Topics: AI Development · Graphics, Media & Games
  **NeKI brief:** Reviews Microsoft Accidentally Told The Truth About AI. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Customizing Claude Code Memory](https://samwize.com/2026/04/23/customizing-claude-code-memory) — Article
  **NeKI brief:** Describes customizing Claude Code memory. Useful for shaping persistent agent context while keeping project facts, preferences, and sensitive information intentionally separated.
- [GPT Image 2 Prompts](https://youmind.com/gpt-image-2-prompts) — Article · Topics: Graphics, Media & Games
  **NeKI brief:** Presents GPT Image 2 prompt guidance. Useful for understanding image-generation controls and prompt structure when evaluating AI-assisted visual workflows.
- [Claude For Creative Work](https://www.anthropic.com/news/claude-for-creative-work) — Article
  **NeKI brief:** Reviews Claude For Creative Work. Useful as a focused reference for evaluating the described workflow or technology, while validating current platform behavior and project-specific constraints against primary documentation.

## [Issue 263](https://thosewhoswift.substack.com/p/those-who-swift-issue-263)

- Published: `2026-04-22`

**Topics:** App Intents & System Surfaces · Combine & Reactive Programming · Graphics, Media & Games · Performance · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 263

**Selected links:**
- [A Reusable Spotlight Onboarding Component In SwiftUI](https://livsycode.com/swiftui/a-reusable-spotlight-onboarding-component-in-swiftui) — Article · Topics: App Intents & System Surfaces · Swift · SwiftUI
  **NeKI brief:** Artem shares how to build a reusable SwiftUI spotlight onboarding component that highlights views with a rounded cutout, positions an overlay card, and supports multi-step flows using anchors and PreferenceKey.
- [Building A Draggable Bottom Sheet In SwiftUI](https://tanaschita.com/swiftui-draggable-bottom-sheet) — Article · Topics: Combine & Reactive Programming · Swift · SwiftUI
  **NeKI brief:** Builds a draggable SwiftUI bottom sheet with gesture state, detents, and snapping decisions. Useful for custom interaction when system sheets do not expose the required presentation behavior.
- [FormatStyle Guide](https://chris.eidhof.nl/post/format-style-guide) — Article · Topics: Foundation & Data Formats · Swift · SwiftUI
  **NeKI brief:** Introduces an interactive browser-based guide to Swift Foundation FormatStyle APIs, implemented with WebAssembly. Use the linked guide for quickly comparing formatting capabilities and verify availability against current Foundation documentation.
- [Associatedtype In Swift Explained - A Complete Guide With SwiftUI Examples](https://www.sagarunagar.com/blog/associatedtype-swift-explained-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Sagar explains what associatedtype is and why it exists, clarifying how it differs from generics and how it enables flexible, type-safe abstractions in protocols.
- [SE-0526: WithDeadline](https://forums.swift.org/t/se-0526-withdeadline/85850) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Presents the Swift Evolution discussion for SE-0526, WithDeadline. Follow the proposal thread to understand motivation, naming, and review trade-offs, but consult the accepted proposal and installed SDK before relying on a specific API shape.
- [Watch here.](https://www.youtube.com/@trySwiftConference/videos) — Video · Topics: Developer Community & Business · Graphics, Media & Games · Swift
  **NeKI brief:** Reviews Watch here.. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Introducing Claude Opus 4.7](https://www.anthropic.com/news/claude-opus-4-7) — Article · Topics: Performance · Personal Essays
  **NeKI brief:** Reviews Introducing Claude Opus 4.7. Useful as a focused reference for evaluating the described workflow or technology, while validating current platform behavior and project-specific constraints against primary documentation.
- [SwiftUI: Refreshable Task Cancellation](https://antongubarenko.substack.com/p/swiftui-refreshable-task-cancellation) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains how refreshable starts asynchronous work and how cancellation propagates when the user ends or repeats a refresh. Useful for making pull-to-refresh tasks idempotent, responsive, and safe against stale results.
- [Introducing Claude Design By Anthropic Labs](https://www.anthropic.com/news/claude-design-anthropic-labs) — Article · Topics: Cross-Platform & Web
  **NeKI brief:** Reviews Introducing Claude Design By Anthropic Labs. Useful as a focused reference for evaluating the described workflow or technology, while validating current platform behavior and project-specific constraints against primary documentation.

## [Issue 262](https://thosewhoswift.substack.com/p/those-who-swift-issue-262)

- Published: `2026-04-15`

**Topics:** Accessibility · App Distribution & Store Operations · Developer Community & Business · Swift · SwiftUI · Testing

**Sections:** Those Who Swift · Those Who Swift - Issue 262 · Weekly note ✏️

**Selected links:**
- [Kids And Vibe Coding: The Joy Of Building](https://www.swiftjectivec.com/kids-and-vibe-coding-ios-apps) — Article · Topics: AI Development · Product Design · Swift
  **NeKI brief:** Reflects on children building iOS apps with AI-assisted or vibe-coding tools. Use it as a product and education perspective on lowering entry barriers while retaining testing, safety, authorship, and review practices.
- [How To Test In-App Purchases Locally Using StoreKit](https://tanaschita.com/testing-in-app-purchases-locally-storekit) — Article · Topics: App Distribution & Store Operations · Testing
  **NeKI brief:** Explains local StoreKit configuration in Xcode for simulating purchases, subscriptions, and failure cases without depending on App Store sandbox accounts.
- [Swish: Clojure-Like Lisp For Swift Video Series](https://www.youtube.com/playlist?list=PLgZNfD3JAd4_2JeJQaFaOwuXV3Z5OX-SB) — Video · Topics: Graphics, Media & Games · Swift
  **NeKI brief:** Reviews Swish: Clojure-Like Lisp For Swift Video Series. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Project Glasswing](https://www.anthropic.com/glasswing) — Article · Topics: Objective-C & Cocoa · Security & Privacy · Testing
  **NeKI brief:** Reviews Project Glasswing. Useful as a focused reference for evaluating the described workflow or technology, while validating current platform behavior and project-specific constraints against primary documentation.
- [Checking Accessibility With SwiftUI Previews](https://mobilea11y.com/blog/swiftui-preview-testing) — Article · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Rob shows how SwiftUI Previews can be used as a lightweight accessibility testing tool, letting you quickly inspect UI variations before testing on a device.
- [Interface Segregation Principle In IOS: How To Prevent A Protocol From Becoming A Prison](https://swiftandmemes.com/interface-segregation-principle-in-ios-how-to-prevent-protocol-from-becoming-a-prison) — Article · Topics: Swift
  **NeKI brief:** Examines Interface Segregation Principle In IOS: How To Prevent A Protocol From Becoming A Prison, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [restricting third-party access tools like OpenClaw](https://www.theverge.com/ai-artificial-intelligence/907074/anthropic-openclaw-claude-subscription-ban) — Article · Topics: AI Development · App Distribution & Store Operations
  **NeKI brief:** Reviews restricting third-party access tools like OpenClaw. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [See How Often the Top Swift Apps are Shipping](https://bitrise.io/resources/tools/app-navigator) — Article · Topics: App Distribution & Store Operations · Swift
  **NeKI brief:** Bitrise App Navigator benchmarks an app’s App Store position and related competitive signals. Follow it for a concrete mobile-growth measurement workflow, while treating ranking data as time-sensitive commercial analytics.
- [Lazy Properties In Swift - Why They Don’t Always Work In SwiftUI](https://www.sagarunagar.com/blog/lazy-properties-swiftui-pitfalls) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains Lazy Properties in Swift - Why They Don’t Always Work in SwiftUI, focusing on the underlying Swift or Apple-platform mechanism and the implementation trade-offs relevant to production code.
- [SwiftUI WithAnimation Completion On iOS 13–16](https://livsycode.com/swiftui/swiftui-withanimation-completion-on-ios-13-16) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains WithAnimation completion behavior across iOS 13–16. Useful for handling animation lifecycle differences when coordinating state transitions on older deployment targets.

## [Issue 261](https://thosewhoswift.substack.com/p/those-who-swift-issue-261)

- Published: `2026-04-08`

**Topics:** AI Development · App Distribution & Store Operations · Developer Tools · Swift · SwiftUI · Testing

**Sections:** Those Who Swift · Those Who Swift - Issue 261 · Weekly note ✏️

**Selected links:**
- [SwiftUI Custom Popover](https://livsycode.com/swiftui/swiftui-custom-popover) — Article · Topics: Code Quality · Swift · SwiftUI
  **NeKI brief:** Artem explains how to build a reusable custom popover in SwiftUI using matchedGeometryEffect, allowing you to attach an overlay to any view without dealing with frames or coordinate spaces
- [Building List Replacement In SwiftUI](https://swiftwithmajid.com/2026/04/06/building-list-replacement-in-swiftui) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Builds a custom SwiftUI list replacement by composing scrolling, layout, and row behavior directly. Use it when List's styling or interaction constraints are the real limitation, while measuring the performance cost of custom virtualization.
- [Beta Preview: DebugSnapshots](https://www.pointfree.co/blog/posts/205-beta-preview-debugsnapshots) — Article · Topics: Macros & Metaprogramming · Testing
  **NeKI brief:** Introduces DebugSnapshots for recording structured debugging state alongside UI behavior. Follow it when reproducing visual or state-dependent failures requires an inspectable artifact rather than a screenshot detached from its model inputs.
- [No, SwiftUI Is Not “Accessible By Default”](https://mobilea11y.com/blog/swiftui-not-accessible) — Article · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Rob challenges the idea that SwiftUI automatically produces accessible apps, showing that developers still need to actively define accessibility to avoid common pitfalls.
- [Spec-Driven Development With OpenSec](https://antongubarenko.substack.com/p/spec-driven-development-with-opensec?r=21t43r) — Article · Topics: AI Development
  **NeKI brief:** Describes spec-driven development with OpenSec. Useful for making agent work explicit through requirements and checks before implementation, while keeping generated output subject to review.
- [Advanced Techniques for Working with Optionals in Swift](https://www.youtube.com/watch?v=qgDIOrKnmuw) — Video · Topics: Swift
  **NeKI brief:** Reviews Advanced Techniques for Working with Optionals in Swift. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Mutex In Swift - Protecting Shared Mutable State With Locks](https://www.sagarunagar.com/blog/swift-mutex-shared-mutable-state) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains Swift Mutex for protecting shared mutable state. Useful for comparing synchronous locking with actors and choosing coordination primitives deliberately.
- [Purchase here.](https://www.manning.com/books/grokking-data-structures) — Article
  **NeKI brief:** Reviews Purchase here.. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Meet The New Cursor](https://cursor.com/blog/cursor-3) — Article
  **NeKI brief:** Introduces Cursor 3 and its agent-assisted development workflow. Useful for assessing multi-file context, automation boundaries, and review requirements before adopting a rapidly changing AI editor.

## [Issue 260](https://thosewhoswift.substack.com/p/those-who-swift-issue-260)

- Published: `2026-04-01`

**Topics:** AI Development · App Distribution & Store Operations · CI/CD & Automation · Navigation & Deep Linking · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 260 · Weekly note ✏️

**Selected links:**
- [Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [What’s New In Swift: March 2026 Edition](https://www.swift.org/blog/whats-new-in-swift-march-2026) — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **NeKI brief:** Summarizes Swift changes released or highlighted in March 2026. Use it to locate language and tooling updates relevant to a project, then read the linked proposals and release notes before changing source or compiler settings.
- [CI/CD Build Speed Benchmark: Codemagic Vs GitHub Actions Vs Bitrise](https://blog.codemagic.io/build-speed-benchmark-comparison) — Article · Topics: CI/CD & Automation · Cross-Platform & Web · Developer Tools
  **NeKI brief:** Examines How fast can each CI/CD service build your app? in the context of CI/CD & Automation and Concurrency. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Top 10 Developer Tools Apple Introduced At WWDC25](https://fline.dev/blog/top-10-developer-tools-apple-introduced-at-wwdc25) — Article · Topics: AI Development · Apple Platform Ecosystem · Foundation & Data Formats
  **NeKI brief:** Examines Top 10 Developer Tools Apple Introduced At WWDC25, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [OpenAI: Build For iOS And macOS](https://developers.openai.com/codex/use-cases/native-ios-macos-apps) — Article · Topics: AI Development · Apple Platform Ecosystem · Testing
  **NeKI brief:** Examines OpenAI: Build For iOS And macOS, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Thread Vs Queue Vs Actor Executor In Swift: Interview Essentials](https://livsycode.com/swift/thread-vs-queue-vs-actor) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Compares threads, queues, and actor executors for Swift concurrency reasoning. Follow it when explaining execution models or debugging ordering, while distinguishing conceptual scheduling from the guarantees provided by structured concurrency and isolation.
- [Animatable In SwiftUI Explained - Complete Guide With Examples & Deep Dive](https://www.sagarunagar.com/blog/swiftui-animatable-protocol-guide) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Sagar explains how the Animatable protocol works in SwiftUI, showing how to animate custom values, combine multiple properties, and build more precise animations beyond the default system ones.
- [iOS Agent Skills, App Store Connect CLI, Foundation Models Tokens & More](https://www.youtube.com/watch?v=VU-NiioUpxg&t=237s) — Video · Topics: AI Development · App Distribution & Store Operations · Foundation & Data Formats
  **NeKI brief:** Reviews iOS Agent Skills, App Store Connect CLI, Foundation Models Tokens & More. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [SwiftUI: Charts Axis Scale](https://antongubarenko.substack.com/p/swiftui-charts-axis-scale) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains SwiftUI Charts axis-scale configuration and its effect on interpretation. Useful when automatic ranges obscure comparisons or outliers and a chart needs an explicit, reviewable value domain.
- [SwiftUI View Lifecycle: When onAppear Actually Fires](https://www.swiftyplace.com/blog/swiftui-view-lifecycle-onappear) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Investigates surprising onAppear behavior across SwiftUI view hierarchies and lifecycle changes. Useful for placing side effects safely, distinguishing view construction from appearance, and preventing duplicate loads or missed refreshes.

## [Issue 259](https://thosewhoswift.substack.com/p/those-who-swift-issue-259)

- Published: `2026-03-26`

**Topics:** AI Development · Architecture · Concurrency · Objective-C & Cocoa · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 259 · Weekly note ✏️

**Selected links:**
- [SwiftUI Live Broadcasting With AWS IVS](https://medium.com/@itsuki.enjoy/swiftui-live-broadcasting-with-aws-ivs-bcd461764e2b) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI Live Broadcasting With AWS IVS, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [I Refactored 3 Apps In A Year. Here’s What I Actually Learned](https://kubamilcarz.medium.com/i-refactored-3-apps-in-a-year-heres-what-i-actually-learned-bc519ba33bb1?source=rss-b30973e2bd56------2) — Article · Topics: Architecture · Concurrency · Objective-C & Cocoa
  **NeKI brief:** Examines I Refactored 3 Apps In A Year. Here’s What I Actually Learned, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Apple Foundation Models In Practice: Building On-Device AI Features In Swift](https://medium.com/@wesleymatlock/apple-foundation-models-in-practice-building-on-device-ai-features-in-swift-b6243976af4f) — Article · Topics: AI Development · Foundation & Data Formats · Swift
  **NeKI brief:** Examines Apple Foundation Models In Practice: Building On-Device AI Features In Swift, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Swift 6.3 Released](https://www.swift.org/blog/swift-6.3-released) — Article · Topics: Cross-Platform & Web · Swift
  **NeKI brief:** Announces Swift 6.3 and summarizes the language, package, and tooling changes in that release. Use it to identify migration candidates, then consult the release notes and proposal links for exact compiler behavior and availability.
- [The Layout Protocol (Part 1)](https://talk.objc.io/episodes/S01E484-the-layout-protocol-part-1) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines The Layout Protocol (Part 1), emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Talking Liquid Glass With Apple](https://captainswiftui.substack.com/p/talking-liquid-glass-with-apple) — Article · Topics: Liquid Glass · Swift · SwiftUI
  **NeKI brief:** Reports a direct discussion with Apple about Liquid Glass design and implementation guidance. Useful for understanding the intended visual language and avoiding speculative patterns while adapting SwiftUI interfaces to the new material system.
- [SwiftUI Architecture Lessons I Wish I Knew Earlier](https://azamsharp.com/2026/02/18/swiftui-architecture-tips.html) — Article · Topics: Architecture · Swift · SwiftUI
  **NeKI brief:** Collects practical SwiftUI architecture lessons around state, boundaries, and maintainability. Useful for reviewing ownership and dependency confusion in a view hierarchy before introducing another abstraction.
- [Generally Useful Prompts](https://david-smith.org/blog/2026/03/20/generally-useful-prompts) — Article · Topics: AI Development · Developer Tools · Testing
  **NeKI brief:** Discusses Generally Useful Prompts, extracting concrete engineering practices and trade-offs that Apple-platform developers can apply when evaluating this workflow.
- [Swift Algorithms - Apple’s Hidden Collection And Sequence APIs You Should Be Using](https://www.sagarunagar.com/blog/swift-algorithms-complete-guide) — Article · Topics: Swift
  **NeKI brief:** Explains Apple’s Hidden Collection and Sequence APIs You Should Be Using, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Review Your Own AI-Generated Code](https://www.scottberrevoets.com/2026/03/20/review-your-own-ai-generated-code) — Article · Topics: AI Development
  **NeKI brief:** Discusses Review your own AI-generated code, extracting concrete engineering practices and trade-offs that Apple-platform developers can apply when evaluating this workflow.
- [iOS App Launch Process: From Tap To First Frame](https://livsycode.com/uikit/ios-app-launch-process-from-tap-to-first-frame) — Article · Topics: Performance · UIKit
  **NeKI brief:** Traces iOS app launch from tap to first frame. Useful for locating startup work across process, scene, and rendering phases instead of treating launch time as one opaque metric.
- [Swift Concurrency Explained With Matt Massicotte](https://www.youtube.com/watch?v=cUu0M5ewpPM) — Video · Topics: Concurrency · Swift
  **NeKI brief:** Reviews Swift Concurrency Explained With Matt Massicotte. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Remote Control](https://code.claude.com/docs/en/remote-control) — Article · Topics: AI Development
  **NeKI brief:** Documents Claude Code Remote Control. Useful for evaluating how a local coding session can be reached remotely, including the explicit trust and session-boundary decisions such a workflow requires.
- [scheduled Cowork sessions](https://claude.com/product/cowork) — Article · Topics: AI Development
  **NeKI brief:** Describes scheduled Cowork sessions. Useful for assessing unattended agent workflows and deciding which tasks require explicit approval, bounded permissions, and later human review.
- [shutting down some side products](https://techcrunch.com/2026/03/24/openais-sora-was-the-creepiest-app-on-your-phone-now-its-shutting-down) — Article · Topics: AI Development
  **NeKI brief:** Reviews shutting down some side products. Useful as a focused reference for evaluating the described workflow or technology, while validating current platform behavior and project-specific constraints against primary documentation.

## [Issue 258](https://thosewhoswift.substack.com/p/those-who-swift-issue-258)

- Published: `2026-03-18`

**Topics:** App Distribution & Store Operations · Graphics, Media & Games · Objective-C & Cocoa · Swift · SwiftUI · Xcode

**Sections:** Those Who Swift · Those Who Swift - Issue 258 · Weekly note ✏️

**Selected links:**
- [Apple Doesn’t Show SwiftData iCloud Sync Status — So Let’s Build One](https://azamsharp.com/2026/03/16/swiftdata-icloud-sync-status.html) — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** Azam shows how to build a simple sync status monitor for SwiftData, giving users meaningful feedback on what's happening behind the scenes while their data syncs with iCloud.
- [Over-Extended Types On The Overuse Of Swift Extensions](https://pastey.github.io/blog/2026-02-15-extensions) — Article · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Examines Over-Extended Types On The Overuse Of Swift Extensions, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Expanding Animations In SwiftUI Lists](https://nerdyak.tech/development/2026/03/16/expand-animation-in-SwiftUI-List.html) — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **NeKI brief:** Diagnoses janky expand and collapse animations inside SwiftUI List and documents the identity and transaction choices that improve them. Useful when animating variable-height rows without breaking list diffing or scroll performance.
- [Build A Searchable, Sortable SwiftUI List With An Index Scrubber](https://www.youtube.com/watch?v=sUZ6agowSew) — Video · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **NeKI brief:** Turns a large SwiftUI list into a searchable, dynamically sortable browser, then adds a Contacts-style section index and draggable scrubber. Useful for coordinating section identifiers with programmatic scrolling and live drag feedback.
- [Working With String Catalogs In iOS Projects](https://tanaschita.com/ios-string-catalogs-in-practice) — Article · Topics: Localization · Xcode
  **NeKI brief:** Explains adopting String Catalogs for localized iOS content and managing translations in Xcode. Use it when migrating string resources, preserving localization keys, and checking plural or variation coverage before release.
- [How To Fix Xcode Source Editor Extensions That Don’t Appear In The Editor Menu](https://adincebic.com/2026/03/15/how-to-fix-xcode-source.html) — Article · Topics: Cross-Platform & Web · Xcode
  **NeKI brief:** Diagnoses Xcode source editor extensions that do not appear in the editor menu. Useful for checking extension targets, host integration, and activation assumptions systematically before treating a missing command as an editor or signing mystery.
- [Fix iTerm2 Microphone Permission For Claude Code Voice Mode](https://mokacoding.com/blog/how-to-claude-code-voice-mode-iterm-permission) — Article · Topics: Security & Privacy · Swift
  **NeKI brief:** Diagnoses iTerm2 microphone permission for Claude Code voice mode. Useful for tracing macOS permission, host-app, and tool integration boundaries in a concrete workflow.
- [SwiftUI Under The Hood: What’s Really Happening When You Update View](https://www.youtube.com/watch?v=_zmQnn7Ki1E&t=28s) — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Reviews SwiftUI Under The Hood: What’s Really Happening When You Update View. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Copy-On-Write In Swift: Semantics, Misconceptions, And A Custom Implementation](https://livsycode.com/swift/copy-on-write-in-swift-semantics-misconceptions-and-a-custom-implementation) — Article · Topics: Swift
  **NeKI brief:** Explains Swift copy-on-write semantics and a custom implementation. Useful for reasoning about value performance, uniqueness checks, and the difference between apparent copies and actual storage duplication.
- [Swift Some Vs Any: Understanding Opaque Types And Existential Types](https://www.sagarunagar.com/blog/swift-some-vs-any-opaque-existential-types) — Article · Topics: Objective-C & Cocoa · Swift
  **NeKI brief:** Reviews Swift Some Vs Any: Understanding Opaque Types And Existential Types. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [SGConf iOS Videos Are Now Available](https://www.youtube.com/@iOSConfSG/videos) — Video · Topics: Developer Community & Business · Graphics, Media & Games
  **NeKI brief:** Reviews SGConf iOS Videos Are Now Available. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [investing in junior roles](https://www.ibm.com/think/news/entry-level-roles-get-reset-ai) — Article · Topics: AI Development
  **NeKI brief:** Reviews investing in junior roles. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.

## [Issue 257](https://thosewhoswift.substack.com/p/those-who-swift-issue-257)

- Published: `2026-03-11`

**Topics:** Combine & Reactive Programming · Core Data · Graphics, Media & Games · Security & Privacy · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 257 · Weekly note ✏️

**Selected links:**
- [Swift At Scale: Building The TelemetryDeck Analytics Service](https://www.swift.org/blog/building-privacy-first-analytics-with-swift) — Article · Topics: Foundation & Data Formats · Security & Privacy · Swift
  **NeKI brief:** Describes building a privacy-first analytics service in Swift and the engineering choices behind it. Follow it when evaluating telemetry architecture, data minimization, and server-side Swift trade-offs without treating the service design as an app recipe.
- [Get Rid Of Your SwiftGen Dependency](https://appleboy.tech/articles/get-rid-of-your-swiftgen-dependency) — Article · Topics: Localization · Swift · Xcode
  **NeKI brief:** Examines Get Rid Of Your SwiftGen Dependency, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Creating Overlays On A Map In A SwiftUI App In iOS 26](https://www.createwithswift.com/creating-overlays-on-a-map-in-a-swiftui-app-in-ios-26) — Article · Topics: Maps & Location · Swift · SwiftUI
  **NeKI brief:** Shows placing custom overlays on a SwiftUI Map in iOS 26. Follow it when map annotations need richer layout or interaction and you must keep geographic positioning separate from overlay view state.
- [CLAUDE.md for iOS Developers](https://www.youtube.com/watch?v=0UaqjKb3QHM&t=108s) — Video · Topics: AI Development · Architecture · Graphics, Media & Games
  **NeKI brief:** Builds a project-root CLAUDE.md for Swift, SwiftUI, and Xcode agents, covering architecture, build, test, and style instructions plus nested or shared configurations. Useful for comparing repository guidance loaded automatically by coding agents.
- [What AI Coding Costs You](https://tomwojcik.com/posts/2026-02-15/finding-the-right-amount-of-ai) — Article · Topics: AI Development · Testing
  **NeKI brief:** Discusses What AI coding costs you in a public developer resource. Use it to compare the author's concrete workflow and trade-offs with your project constraints, and verify any platform-specific claims against current primary documentation.
- [How My Software Engineering Workflow Has Changed In The Past Year](https://swiftrocks.com/how-my-software-engineering-workflow-has-changed-in-the-past-year) — Article · Topics: AI Development · Swift
  **NeKI brief:** Reflects on changes in a software-engineering workflow over a year. Useful for evaluating process adaptations and automation while keeping empirical results separate from general productivity claims.
- [Why I'm Still Thinking About Core Data In 2026](https://fatbobman.com/en/posts/why-i-am-still-thinking-about-core-data-in-2026) — Article · Topics: Concurrency · Core Data · Persistence & Synchronisation
  **NeKI brief:** Frames Core Data's continuing value against its growing mismatch with Swift concurrency, type safety, and modern model expression. It is a useful requirements analysis for modernization efforts that must preserve existing stores.
- [MVVM and the Cost of Carrying Old Patterns Forward](https://azamsharp.com/2026/03/04/mvvm-and-cost-of-old-patterns.html) — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **NeKI brief:** Azam explores how continuing to apply the MVVM pattern in SwiftUI can add unnecessary complexity and overhead, arguing that developers should rethink older architectural habits and instead leverage SwiftUI’s built-in state management and simpler design…
- [Speed Hacks for iOS Builds](https://bitrise.io/whitepapers/level-up-your-ios-game-tips-for-speeding-up-your-continuous-integration) — Article · Topics: Graphics, Media & Games
  **NeKI brief:** Discusses Save Time on Every Build and Test Run in a public developer resource. Use it to compare the author's concrete workflow and trade-offs with your project constraints, and verify any platform-specific claims against current primary documentation.

## [Issue 256](https://thosewhoswift.substack.com/p/those-who-swift-issue-256)

- Published: `2026-03-06`

**Topics:** Architecture · Security & Privacy · Swift · Swift Package Manager · SwiftUI · UIKit

**Sections:** Those Who Swift · Those Who Swift - Issue 256 · Weekly note ✏️

**Selected links:**
- [Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [All In on Interface Builder: 10 Years Later](https://www.scottberrevoets.com/2026/03/02/all-in-on-interface-builder-10-years-later) — Article · Topics: Code Quality · Swift · UIKit
  **NeKI brief:** Reviews All In on Interface Builder: 10 Years Later. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Developers Are Safe… Thanks to Corporate Red Tape](https://azamsharp.com/2026/02/26/developers-are-safe.html) — Article · Topics: AI Development · Architecture · Cross-Platform & Web
  **NeKI brief:** Discusses how corporate process and red tape affect developer safety. Useful as organizational context for evaluating engineering controls and decision friction, not as an API reference.
- [Building a Reusable Network Manager in Swift](https://www.youtube.com/watch?v=zEzIxdA8zLQ) — Video · Topics: Concurrency · Networking · Swift
  **NeKI brief:** Refactors view-specific URLSession code into a generic async NetworkManager with HTTP validation, typed failures, dictionary and array decoding, and caller-configured date strategies. Useful for keeping decoding flexibility outside the shared transport layer.
- [Geometry in SwiftUI Explained](https://www.sagarunagar.com/blog/geometry-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Surveys GeometryReader, GeometryProxy, and onGeometryChange through practical SwiftUI layout examples. Useful for choosing the least-coupled measurement tool when adaptive components need size or position information without destabilizing layout.
- [NSCache in Swift](https://livsycode.com/best-practices/nscache-in-swift-a-practical-guide) — Article · Topics: Performance · Swift
  **NeKI brief:** Artem practical guide to using NSCache in Swift, explaining how it works, when it’s preferable to dictionaries for in-memory caching, and how to use it safely to improve performance.
- [Juice It Up With UIKit Dynamics](https://whackylabs.com/swift/ios/uikit/dynamics/2026/03/02/juice-it-up-with-uikit-dynamics) — Tutorial · Topics: Swift · UIKit
  **NeKI brief:** Explores UIKit Dynamics for iOS interfaces. Useful for evaluating physics-based interaction and understanding how dynamic behaviors affect layout, gesture handling, and user feedback.
- [Staff Engineering in Mobile Teams: Myth vs Reality](https://www.youtube.com/watch?v=x5wug2V1244) — Video · Topics: Developer Community & Business · Swift
  **NeKI brief:** Reviews Staff Engineering in Mobile Teams: Myth vs Reality. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [iOS Backend Security Series: Request Signing & Quantum-Safe TLS](https://fractal-dev.com/blog/ios-backend-security-part-1-request-signing-quantum-tls?lang=en) — Article · Topics: Security & Privacy
  **NeKI brief:** Explains request signing and quantum-safe TLS for an iOS backend. Useful for reviewing authentication, transport, and migration assumptions in client-server security design.
- [Automating Mac App Screenshots](https://www.amyworrall.com/blog/automating-mac-app-screenshots) — Article · Topics: App Distribution & Store Operations
  **NeKI brief:** Examines Automating Mac app screenshots — Amy Worrall. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [publicly stated](https://www.bbc.com/news/articles/cvg3vlzzkqeo) — Article · Topics: AI Development
  **NeKI brief:** Reviews publicly stated. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [top of the AI category](https://www.theguardian.com/technology/2026/mar/02/claude-anthropic-ai-pentagon) — Article · Topics: AI Development
  **NeKI brief:** Reviews top of the AI category. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Announcing Swift 6.2.4](https://forums.swift.org/t/announcing-swift-6-2-4/85050) — Article · Topics: Swift
  **NeKI brief:** Announces Swift 6.2.4. Useful for tracking a concrete toolchain release and planning compiler, language-mode, and compatibility checks before upgrading a project.
- [Importing Memory into Claude](https://claude.com/import-memory) — Article · Topics: Objective-C & Cocoa
  **NeKI brief:** Describes importing persistent memory into Claude. Useful for evaluating retained context while separating durable preferences from task-specific evidence and security-sensitive data.
- [Time Machine](https://support.apple.com/en-us/104984) — Article
  **NeKI brief:** Reviews Time Machine. Useful as a focused reference for evaluating the described workflow or technology, while validating current platform behavior and project-specific constraints against primary documentation.
- [Using Voice Mode in Claude](https://support.claude.com/en/articles/11101966-using-voice-mode) — Article
  **NeKI brief:** Reviews Using Voice Mode in Claude. Useful as a focused reference for evaluating the described workflow or technology, while validating current platform behavior and project-specific constraints against primary documentation.

## [Issue 255](https://thosewhoswift.substack.com/p/those-who-swift-issue-255)

- Published: `2026-02-25`

**Topics:** Concurrency · Maps & Location · Persistence & Synchronisation · Swift · SwiftUI · Testing

**Sections:** Those Who Swift · Those Who Swift - Issue 255 · Weekly note ✏️

**Selected links:**
- [Why Your @Observable Class init Runs Multiple Times in SwiftUI?](https://livsycode.com/swiftui/why-your-observable-class-init-runs-multiple-times-in-swiftui) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Artem explains why a SwiftUI @Observable class’s initializer can run multiple times, how SwiftUI recreates view structs and re-evaluates default @State values, and how to avoid unintended repeated work.
- [Testing Database Migrations](https://tanaschita.com/testing-database-migrations) — Article · Topics: Persistence & Synchronisation · Personal Essays · Testing
  **NeKI brief:** Presents a database-migration testing workflow that verifies schema changes against realistic stores. Use it to catch destructive transformations, ordering mistakes, and data-loss regressions before shipping a new persistence version.
- [Creating Maps in SwiftUI Apps With MapKit](https://www.createwithswift.com/creating-maps-in-swiftui-apps-with-mapkit) — Tutorial · Topics: Maps & Location · Swift · SwiftUI
  **NeKI brief:** Builds a MapKit-backed SwiftUI map with regions and content. Follow it when moving from delegate-driven maps to state-driven annotations, selection, and camera updates in a modern SwiftUI screen.
- [Reports have already identified](https://www.nytimes.com/2026/02/23/technology/anthropic-chinese-startups-distillation.html?unlocked_article_code=1.OlA.K6da.1rb5xxt2Us9Q&smid=url-share) — Article · Topics: AI Development · Cross-Platform & Web
  **NeKI brief:** Reviews Reports have already identified. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Testing Event Streams](https://www.massicotte.org/blog/testing-event-stream) — Article · Topics: Concurrency · Testing
  **NeKI brief:** Explains Testing with Event Streams, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Static vs Dynamic Dispatch in Swift](https://www.sagarunagar.com/blog/static-vs-dynamic-dispatch-swift) — Article · Topics: Performance · Swift
  **NeKI brief:** Examines Static vs Dynamic Dispatch in Swift, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [The 4-Step Process to Create SwiftUI Animations](https://www.swiftdifferently.com/blog/swiftui/swiftui-animation-with-example) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Explains The 4-Step Process I Use to Create SwiftUI Animations, focusing on the underlying Swift or Apple-platform mechanism and the implementation trade-offs relevant to production code.
- [Claude Code Brought My App Back From the Dead](https://chriswu.com/posts/ai/museumshuffleai) — Article · Topics: AI Development
  **NeKI brief:** Describes rebuilding an app with Claude Code. Useful as an agent-workflow case study for understanding automated changes, review boundaries, and the risks of trusting generated code without runtime validation.
- [Swift System Metrics 1.0 Released](https://www.swift.org/blog/swift-system-metrics-1.0-released) — Article · Topics: Product Design · Swift
  **NeKI brief:** Announces Swift System Metrics 1.0. Useful for collecting process and system measurements in Swift while keeping metric semantics and platform availability explicit.
- [AI Job Loss Isn’t the Scariest Part](https://dewaniahmed.substack.com/p/ai-job-loss-isnt-the-scariest-part) — Article · Topics: AI Development
  **NeKI brief:** Discusses the implications of AI-related job loss. Useful as technology-industry context, not as Apple-platform implementation guidance.

## [Issue 254](https://thosewhoswift.substack.com/p/those-who-swift-issue-254)

- Published: `2026-02-18`

**Topics:** AI Development · Graphics, Media & Games · Persistence & Synchronisation · Swift · SwiftData · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 254 · Weekly note ✏️

**Selected links:**
- [Tracking Token Usage in Foundation Models](https://artemnovichkov.com/blog/tracking-token-usage-in-foundation-models) — Article · Topics: AI Development · Foundation & Data Formats · Performance
  **NeKI brief:** Artem explains how to measure the tokens Foundation Models consume for instructions, prompts, tools, and full session transcripts, helping you understand context limits and optimize prompt design.
- [SwiftUI Foundations: Build Great Apps Q&A](https://antongubarenko.substack.com/p/swiftui-foundations-build-great-apps) — Article · Topics: Foundation & Data Formats · Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI Foundations: Build Great Apps Q&A, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [How to Migrate to @Observable Without Breaking Your App](https://swiftandmemes.com/how-to-migrate-to-observable-without-breaking-your-app) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Examines How to Migrate to @Observable Without Breaking Your App, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Taking First Steps Into Metal Shaders](https://www.createwithswift.com/taking-first-steps-into-metal-shaders) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Introduces Metal shader integration from a SwiftUI perspective, including the boundary between view modifiers and GPU functions. Follow it when prototyping shader effects and evaluating parameter flow, availability, and fallback behavior.
- [Sharing SwiftData Content Between Users](https://www.youtube.com/watch?v=t9FRldfZ8vc) — Video · Topics: Swift · SwiftData · SwiftUI
  **NeKI brief:** Exports selected SwiftData relationships as a custom file through UIActivityViewController, then imports them with onOpenURL and security-scoped access. The merge logic reconnects related models while preventing duplicates.
- [Building a Toast Component in SwiftUI](https://livsycode.com/swiftui/building-a-toast-component-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Implements a toast component in SwiftUI. Useful for evaluating transient presentation state, timing, accessibility, and overlay placement without coupling feedback to a single view.
- [Isolate SwiftUI Animations to Specific Attributes](https://nilcoalescing.com/blog/IsolateSwiftUIAnimationsToSpecificAttributes) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows how to scope SwiftUI animation to selected attributes rather than every state change in a view update. Use it when unrelated layout or content changes animate accidentally and make interaction feel unstable.
- [If You’re Not Versioning Your SwiftData Schema, You’re Gambling](https://azamsharp.com/2026/02/14/if-you-are-not-versioning-your-swiftdata-schema.html) — Article · Topics: App Distribution & Store Operations · Swift · SwiftData
  **NeKI brief:** Azam explains why schema versioning in SwiftData is essential once your app stores real user data and shows how to define VersionedSchema, implement custom migrations, and evolve models.
- [has joined the OpenAI team](https://steipete.me/posts/2026/openclaw) — Article · Topics: AI Development
  **NeKI brief:** Presents now part of OpenAI, congrats Peter!, with practical context for Apple-platform developers evaluating the technique, workflow, or engineering decision described on the page.
- [stating that much of its code is now written by LLMs](https://techcrunch.com/2026/02/12/spotify-says-its-best-developers-havent-written-a-line-of-code-since-december-thanks-to-ai) — Article · Topics: AI Development
  **NeKI brief:** Reviews stating that much of its code is now written by LLMs. Useful as a focused reference for evaluating the described workflow or technology, while validating current platform behavior and project-specific constraints against primary documentation.
- [Copy-on-Write in Swift Explained](https://www.sagarunagar.com/blog/copy-on-write-swift) — Article · Topics: Performance · Swift
  **NeKI brief:** Explains copy-on-write in Swift. Useful for reasoning about value semantics, storage sharing, and when mutations trigger allocation or copying.
- [Opus 4.6 Vending Bench](https://andonlabs.com/blog/opus-4-6-vending-bench) — Article · Topics: Personal Essays · Testing
  **NeKI brief:** Reports on Opus 4.6 through a Vending Bench evaluation. Useful as comparative evidence for agent capability and cost, while separating benchmark behavior from production reliability claims.

## [Issue 253](https://thosewhoswift.substack.com/p/those-who-swift-issue-253)

- Published: `2026-02-12`

**Topics:** AI Development · App Distribution & Store Operations · Architecture · Swift · SwiftUI · Xcode

**Sections:** Those Who Swift · Those Who Swift - Issue 253 · Weekly note ✏️

**Selected links:**
- [Container-Based Dependency Injection](https://livsycode.com/best-practices/container-based-dependency-injection) — Article · Topics: Architecture · Dependency Injection · Developer Career & Practice
  **NeKI brief:** Presents container-based dependency injection in Swift and the trade-offs of centralized resolution. Use it when comparing composition strategies, keeping dependencies explicit, and preventing a container from becoming hidden global state.
- [SwiftUI Coordinators](https://tanaschita.com/swiftui-coordinators) — Article · Topics: Navigation & Deep Linking · Swift · SwiftUI
  **NeKI brief:** Uses DataScannerViewController to show how UIViewControllerRepresentable.Coordinator receives UIKit delegate callbacks and sends results back to SwiftUI, making the coordinator boundary concrete for delegate-driven integrations.
- [Measure App Launch Time in iOS](https://swiftdevjournal.com/posts/measure-app-launch-time) — Article · Topics: Performance · Swift · Xcode
  **NeKI brief:** Explains ways to measure iOS app launch time and interpret the resulting timings. Follow it when establishing a baseline, separating cold and warm launches, and connecting signposts or metrics to user-visible startup work.
- [Agentic Coding in Xcode 26.3 with Claude Code and Codex](https://www.swiftjectivec.com/agentic-coding-codex-claude-code-in-xcode) — Article · Topics: AI Development · Swift · Xcode
  **NeKI brief:** Examines Agentic Coding in Xcode 26.3 with Claude Code and Codex, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Agentic Coding in Xcode](https://swiftwithmajid.com/2026/02/10/agentic-coding-in-xcode) — Article · Topics: AI Development · Swift · Xcode
  **NeKI brief:** Details configuring Xcode 26.3’s agentic coding support and practical habits for delegating Apple-platform work. Follow it when establishing project context, reviewing generated diffs, and keeping Xcode’s agent actions inside an auditable workflow.
- [SwiftUI Foundations: Build great apps with SwiftUI](https://www.youtube.com/watch?v=Z3vloOtZLkQ) — Video · Topics: Foundation & Data Formats · Swift · SwiftUI
  **NeKI brief:** Reviews SwiftUI Foundations: Build great apps with SwiftUI. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Xcode 26.3 + Claude Agent: Model Swapping, MCP, Skills, and Adaptive Configuration](https://fatbobman.com/en/posts/xcode-263-claude) — Article · Topics: AI Development · Xcode
  **NeKI brief:** Experiments with Claude inside Xcode 26.3 through model substitution, injected MCP tools, shared skill symlinks, environment setup, and adaptive CLAUDE.md guidance. The article distinguishes supported integration from brittle configuration techniques.
- [Sharing SwiftData Between Users](https://www.youtube.com/watch?v=TPGn2pJjfis) — Video · Topics: Swift · SwiftData
  **NeKI brief:** Reviews Sharing SwiftData Between Users. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Adding an Open Recent Menu in a macOS App](https://swiftdevjournal.com/posts/open-recent-menu) — Article · Topics: Swift
  **NeKI brief:** Adds an Open Recent menu to a SwiftUI app, wiring recent document state into platform menu commands. Useful for macOS document workflows that need persistence, discoverable actions, and correct scene-level ownership.
- [Dev Workspaces](https://iosdev.tools/blog/dev-workspaces-natalia-panferova) — Article · Topics: Developer Community & Business
  **NeKI brief:** Presents Welcome to "Dev Workspaces"! - Natalia Panferova as an Apple-platform development resource. Use the profile to understand its concrete role, then check the linked project for current capabilities and maintenance status.

## [Issue 252](https://thosewhoswift.substack.com/p/those-who-swift-issue-252)

- Published: `2026-02-04`

**Topics:** AI Development · Apple Platform Ecosystem · Objective-C & Cocoa · Product Design · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 252 · Weekly note ✏️

**Selected links:**
- [Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [The Secret to Buttery Smooth SwiftUI](https://www.swiftdifferently.com/blog/swiftui/swiftui-performance-article) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Explores practical causes of sluggish SwiftUI rendering and techniques for reducing unnecessary work. Useful as a performance checklist before profiling view identity, expensive body computations, and state-driven update frequency with Instruments.
- [From Objective-C to Swift 6: What We Gained](https://slicker.me/swift/swift-evolution.html) — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **NeKI brief:** Summarizes the evolution from Objective-C to Swift 6. Useful for historical context when reviewing language migration decisions and the capabilities gained across modern Swift releases.
- [Mastering DatePicker, MultiDatePicker, and ColorPicker in SwiftUI](https://www.youtube.com/watch?v=O540BJGGpYw&t=2s) — Video · Topics: Persistence & Synchronisation · Swift · SwiftUI
  **NeKI brief:** Compares SwiftUI DatePicker, MultiDatePicker, and ColorPicker configurations, including ranges, optional-date bindings, persistence-friendly colors, and a UIColorPickerViewController bridge. Useful for understanding where native SwiftUI controls still need UIKit support.
- [Tiered Caching in Swift](https://kylebrowning.com/posts/tiered-caching-in-swift) — Article · Topics: Performance · Swift
  **NeKI brief:** Presents a tiered caching approach in Swift across faster and slower storage layers. Use it when designing cache lookup and invalidation policy, keeping source-of-truth ownership, freshness, serialization, and memory pressure behavior explicit.
- [Designing Swift Errors for an SDK](https://nonstrict.eu/blog/2026/designing-swift-errors-for-an-sdk) — Article · Topics: Developer Tools · Swift
  **NeKI brief:** This article covers designing stable, expressive error APIs for Swift SDKs. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [SwiftUI Weather App Copy Cat With WeatherKit](https://medium.com/@itsuki.enjoy/swiftui-weather-app-copy-cat-with-weather-kit-6d3dfafbd1e4) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI Weather App Copy Cat With WeatherKit, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [A WhatsApp-Style Top Banner for iOS Using UIWindow](https://livsycode.com/swiftui/a-whatsapp-style-top-banner-for-ios-using-uiwindow) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a WhatsApp-style top banner for iOS using UIWindow. Useful for evaluating overlay ownership, window-level presentation, and lifecycle behavior across scenes.
- [a major shift in AI leadership](https://www.theguardian.com/technology/2025/dec/01/apple-ai-chief-john-giannandrea-steps-down) — Article · Topics: AI Development · App Intents & System Surfaces · Apple Platform Ecosystem
  **NeKI brief:** Reviews a major shift in AI leadership. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [How Apple Hooks Fifty Thousand Methods](https://www.youtube.com/watch?v=SuQGQ1vh9k0&t=1s) — Video · Topics: Graphics, Media & Games · Objective-C & Cocoa · Swift
  **NeKI brief:** Reviews How Apple Hooks Fifty Thousand Methods. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Objectively Better, Observably Trickier](https://open.substack.com/pub/captainswiftui/p/objectively-better-observably-trickier) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Discusses observable state in SwiftUI. Useful for reviewing observation ownership and the trade-offs between improved ergonomics and harder-to-see behavior.
- [Branding With AI Superpowers for Indie Creators](https://www.createwithswift.com/branding-with-ai-superpowers-for-indie-creators) — Article · Topics: AI Development · Combine & Reactive Programming · Product Design
  **NeKI brief:** Explores how indie creators can use AI tools to shape a product brand, from visual direction through reusable assets and messaging. Useful for evaluating an AI-assisted branding workflow while retaining human decisions about audience, tone, and consistency.
- [joining Apple’s Design Team](https://www.theverge.com/tech/869926/apple-hires-sebastiaan-de-with-design-team-halide-lux) — Article · Topics: Product Design
  **NeKI brief:** Reviews joining Apple’s Design Team. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Print Design Mindset to App Design Mindset](https://twocentstudios.com/2026/01/29/print-design-mindset) — Article · Topics: Developer Tools
  **NeKI brief:** Applies print-design principles to app design. Useful for reviewing hierarchy, spacing, and composition when translating editorial visual ideas into interactive mobile interfaces.

## [Issue 251](https://thosewhoswift.substack.com/p/those-who-swift-issue-251)

- Published: `2026-01-28`

**Topics:** Combine & Reactive Programming · Concurrency · Developer Community & Business · Liquid Glass · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 251 · Weekly note ✏️

**Selected links:**
- [SwiftUI Alerting with NSAlert](https://medium.com/@itsuki.enjoy/swiftui-alerting-with-nsalert-21bdc3a8e650) — Article · Topics: Developer Community & Business · Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI Alerting with NSAlert, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Swift Actors: Common Pitfalls and How to Avoid Them](https://www.fractal-dev.com/blog/swift-actors-pitfalls?lang=en) — Article · Topics: Concurrency · Foundation & Data Formats · Swift
  **NeKI brief:** Catalogues common Swift actor pitfalls, including reentrancy and isolation misunderstandings. Use it when reviewing actor-based designs, pairing each warning with compiler diagnostics, tests, and a clear model of which state is actually protected.
- [Understanding Memory in iOS](https://anubhav52.gumroad.com/l/ios-memory) — Tutorial · Topics: Developer Career & Practice · Developer Community & Business · Developer Tools
  **NeKI brief:** Offers an iOS memory guide. Useful for reviewing allocation, lifetime, and profiling concepts when investigating memory pressure in shipped apps.
- [Liquid Glass Toast in SwiftUI](https://writetodisk.com/liquid-glass-toast) — Tutorial · Topics: Liquid Glass · Swift · SwiftUI
  **NeKI brief:** Demonstrates a Liquid Glass toast-style notification in SwiftUI. Follow it for transient feedback experiments, but verify timing, safe-area placement, VoiceOver announcements, reduced motion, and whether an existing system affordance is more appropriate.
- [Combine Operators Cheat Sheet](https://tanaschita.com/combine-operators-cheatsheet) — Article · Topics: Combine & Reactive Programming · Swift
  **NeKI brief:** Maps common Combine operators to transformations, filtering, combination, and scheduling behavior. Follow it when refactoring a publisher pipeline and needing to choose an operator by demand semantics rather than memorized names.
- [App-Wide Theming in SwiftUI](https://www.sagarunagar.com/blog/app-wide-theming-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Sagar shows how to implement app-wide theming in SwiftUI by defining centralized color and style systems, using custom environment keys and extensions so your UI can adapt easily to different themes with consistency.
- [Reverse Masking in SwiftUI Using Blend Modes](https://livsycode.com/swiftui/reverse-masking-in-swiftui-using-blend-modes) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates reverse masking in SwiftUI with blend modes. Follow it for cutout or spotlight effects, separating compositing behavior from layout and checking rendering cost, color-space assumptions, and accessibility alternatives.
- [Sharing Content Among Apps Using AppEntity and Transferable Protocol](https://www.createwithswift.com/sharing-content-among-apps-using-appentity-and-transferable-protocol) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Combines AppEntity and Transferable to expose app content across system sharing surfaces. Use it when designing typed representations that can serve both App Intents discovery and drag, drop, or share operations.
- [rolling out changes to App Store search ads](https://www.macrumors.com/2026/01/23/more-app-store-ads-coming-soon) — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem · Objective-C & Cocoa
  **NeKI brief:** Reviews rolling out changes to App Store search ads. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Solving the View Model Problem (Part 1)](https://talk.objc.io/episodes/S01E476-solving-the-view-model-problem-part-1) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Examines the view-model problem in SwiftUI. Useful for reviewing state ownership and deciding when a view model clarifies behavior versus adding an unnecessary indirection layer.
- [Improving Usability of C Libraries in Swift](https://www.swift.org/blog/improving-usability-of-c-libraries-in-swift) — Article · Topics: Swift
  **NeKI brief:** Describes improvements to C-library usability in Swift. Useful for understanding interop ergonomics, imported APIs, and the migration work needed when wrapping systems code.
- [Highlighting Code Blocks in Markdown with SwiftSyntax](https://artemnovichkov.com/blog/highlighting-code-blocks-in-markdown-with-swiftsyntax) — Article · Topics: Swift
  **NeKI brief:** Demonstrates rendering Markdown in SwiftUI. Useful for choosing a rendering pipeline, handling attributed content, and deciding where links and styling should remain controlled by the app.
- [the Windows Group](https://www.swift.org/blog/announcing-windows-workgroup) — Article · Topics: Cross-Platform & Web · Swift
  **NeKI brief:** Introduces the Swift Windows workgroup. Useful for tracking cross-platform coordination and understanding how platform support influences package portability and contributor workflows.
- [Download the free report (PDF)](https://bitrise.io/insights) — Article
  **NeKI brief:** Offers a free CI report. Useful as market context for build-pipeline decisions, not as implementation guidance.
- [announced a major shift](https://skip.dev/blog/skip-is-free) — Article
  **NeKI brief:** Announces Skip as free and open source, enabling shared Swift and SwiftUI code to target additional platforms through translation. Useful for evaluating cross-platform reach, with platform-specific behavior still requiring verification.

## [Issue 250](https://thosewhoswift.substack.com/p/those-who-swift-issue-250)

- Published: `2026-01-21`

**Topics:** AI Development · Concurrency · Cross-Platform & Web · Objective-C & Cocoa · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 250 · Weekly note ✏️

**Selected links:**
- [Creating and Introducing AsyncSharedStream](https://medium.com/the-swift-cooperative/creating-and-introducing-asyncsharedstream-3e9185317a5a) — Article · Topics: Combine & Reactive Programming · Concurrency · Swift
  **NeKI brief:** Introduces an AsyncSharedStream abstraction for sharing asynchronous events among consumers. Follow it when evaluating fan-out stream design, cancellation, buffering, and termination semantics instead of assuming AsyncStream alone defines the desired policy.
- [The Shift: Using AI as a Developer Advocate and Engineer](https://www.swiftjectivec.com/the-shift-using-ai-as-a-developer-advocate-and-engineer) — Article · Topics: AI Development · Developer Community & Business · Swift
  **NeKI brief:** Reviews The Shift: Using AI as a Developer Advocate and Engineer. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Modern Concurrency and Legacy Code](https://www.swiftdifferently.com/blog/swift/concurrency/modern-concurrency-and-legacy-code) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Discusses integrating modern Swift concurrency with legacy callback or synchronization code. Use it when planning incremental migration, marking isolation boundaries, and preventing accidental blocking or duplicated ownership during the transition.
- [Creating a Paging ScrollView in SwiftUI](https://www.swiftdifferently.com/blog/swiftui/creating-paging-scrollView) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Creates a paging ScrollView in SwiftUI. Useful for coordinating scroll position, gesture behavior, and page snapping when the built-in container does not meet the interaction contract.
- [Foundation Models Prompting Guide](https://livsycode.com/best-practices/foundation-models-prompting-guide) — Article · Topics: AI Development · Foundation & Data Formats
  **NeKI brief:** Provides practical prompting guidance for Apple's Foundation Models. Use it when shaping instructions, output constraints, and context boundaries for on-device generation, then validate behavior across models, locales, and failure cases.
- [Crafting Document-Based Apps in SwiftUI](https://www.createwithswift.com/crafting-document-based-apps-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a document-based SwiftUI app around file-backed document types and scene integration. Use it when routing document lifecycle, autosave, import/export, and editing state through Apple's document architecture.
- [CocoaPods announced a staged move toward read-only mode](https://blog.cocoapods.org/CocoaPods-Specs-Repo) — Article · Topics: AI Development · Objective-C & Cocoa · Swift Package Manager
  **NeKI brief:** Announces the CocoaPods Specs repository move toward read-only operation. Useful for assessing dependency-resolution and supply-chain implications in projects that still rely on CocoaPods.
- [Mastering Switch Statements in Swift](https://www.youtube.com/watch?v=84HoS9W2tpw) — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Reviews Mastering Switch Statements in Swift. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Surviving tvOS Development](https://fatbobman.com/en/posts/surviving-tvos) — Article · Topics: Performance
  **NeKI brief:** Documents a media player's tvOS-specific focus behavior, storage limits, SwiftUI workarounds, AVPlayer tuning, and synchronization strategy. It is useful for identifying platform constraints that an enlarged-iPad mental model misses.
- [Emptiness in SwiftUI](https://captainswiftui.substack.com/p/emptiness-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Danny explores how SwiftUI represents and handles emptiness in UI examining types like EmptyView, EmptyModifier, and ContentUnavailableView, when to use them, and how they help you express absent or unavailable content.
- [Skip Is Now Free and Open Source](https://skip.tools/blog/skip-is-free) — Article · Topics: AI Development
  **NeKI brief:** Announces Skip becoming free and open source. Useful for evaluating a cross-platform Swift development path and inspecting the trade-offs between shared code and native platform behavior.
- [Why Do iOS Timers Stop When You Scroll?](https://www.youtube.com/watch?v=Uso8T5xBidk) — Video · Topics: Graphics, Media & Games
  **NeKI brief:** Reviews Why Do iOS Timers Stop When You Scroll?. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [ASCII Sketch](https://files.littlebird.com.au/ascii-sketch.html) — Article · Topics: Cross-Platform & Web
  **NeKI brief:** Provides an interactive ASCII sketching tool. Useful for quick text-based diagrams and lightweight planning when a visual model is needed without introducing a full design application.

## [Issue 249](https://thosewhoswift.substack.com/p/those-who-swift-issue-249)

- Published: `2026-01-14`

**Topics:** AI Development · App Intents & System Surfaces · Graphics, Media & Games · Objective-C & Cocoa · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 249 · Weekly note ✏️

**Selected links:**
- [Running Swift on Microcontrollers](https://fatbobman.com/en/posts/running-swift-on-mcu) — Article · Topics: Graphics, Media & Games · Personal Essays · Swift
  **NeKI brief:** Traces seven years of bringing Swift to microcontrollers through MadMachine, including toolchain evolution and the case for memory-safe embedded code. It supplies historical constraints and practical evidence beyond Apple's newer official MCU support.
- [Swift Programming Guide](https://github.com/peterfriese/swift-book) — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Provides Peter Friese’s Swift book materials and examples as a public reference for learning and teaching core Swift concepts. Use it for structured study, not as version-specific API authority.
- [MVVM and Reducer Pattern in Swift](https://www.fractal-dev.com/blog/mvvm-and-reducer-pattern?lang=en) — Article · Topics: Objective-C & Cocoa · Swift · Testing
  **NeKI brief:** Examines MVVM and Reducer Pattern in Swift, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [SwiftUI: Report Device Activity Visually](https://medium.com/@itsuki.enjoy/swiftui-report-device-activity-graphically-visually-73f4d76f5039) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI: Report Device Activity Visually, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Initializing Observable Classes](https://www.youtube.com/watch?v=z0GD03x3gc4&t=1184s) — Video · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates how SwiftUI initializes observable reference types as ordinary properties, state, deferred task-created values, parameterized instances, and environment values. The examples reveal when view updates or multiple scenes recreate versus preserve models.
- [Natalia Panferova](https://nilcoalescing.com/blog/DefiningCustomStringInterpolationBehaviorInSwift) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows extending Swift string interpolation so domain types can control formatting directly inside literals. Use it when designing readable, type-directed output while keeping conversion logic centralized instead of scattering formatter calls through UI code.
- [Understanding Gesture Hierarchy in SwiftUI](https://www.createwithswift.com/understanding-gesture-hierarchy) — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **NeKI brief:** Explains SwiftUI gesture priority and how parent and child recognizers compete for touches. Useful when nested controls stop receiving input after adding a container-level gesture.
- [Rendering Markdown in SwiftUI](https://artemnovichkov.com/blog/rendering-markdown-in-swiftui) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Artem shows how to display Markdown content in SwiftUI using Apple’s Markdown support from basic rich text formatting to handling links, lists, and custom styles.
- [Xcode File Templates for iOS Development](https://www.sagarunagar.com/blog/xcode-file-templates-ios-development) — Article · Topics: Xcode
  **NeKI brief:** Reviews Xcode File Templates for iOS Development. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Detecting Text in Images With the Vision Framework](https://danielsaidi.com/blog/2026/01/10/detecting-text-in-images-with-the-vision-framework) — Article · Topics: Graphics, Media & Games
  **NeKI brief:** Uses Vision to detect text in images. Useful for mapping image preprocessing, recognition requests, and result handling into a testable pipeline rather than treating OCR as a single opaque call.
- [Apple Chooses Google Gemini for Siri AI](https://www.theverge.com/ai-artificial-intelligence/860989/apple-google-gemini-siri-ai-deal-what-it-means) — Article · Topics: AI Development · App Intents & System Surfaces
  **NeKI brief:** Reviews Apple Chooses Google Gemini for Siri AI. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Anthropic Expands AI Tools for Healthcare & Life Sciences](https://www.anthropic.com/news/healthcare-life-sciences?_bhlid=38bb3f9c085605c8e8d60092d5eb7912ac47b036) — Article · Topics: AI Development · Objective-C & Cocoa
  **NeKI brief:** Reviews Anthropic Expands AI Tools for Healthcare & Life Sciences. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [The Anatomy of Strong Teams in the Age of AI](https://livsycode.com/best-practices/the-anatomy-of-strong-teams-in-the-age-of-ai) — Article · Topics: AI Development
  **NeKI brief:** Discusses strong teams in the age of AI. Useful for reviewing ownership, communication, and quality practices when automation changes how mobile teams collaborate.
- [Register now!](https://www.vpdae.com/redirect/60xe9o2rwdxcm82mm81ic1zrvln) — Article
  **NeKI brief:** Reviews Register now!. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.

## [Issue 248](https://thosewhoswift.substack.com/p/those-who-swift-issue-248)

- Published: `2026-01-08`

**Topics:** AI Development · Developer Community & Business · Graphics, Media & Games · Swift · SwiftUI · Testing

**Sections:** Those Who Swift · Those Who Swift - Issue 248 · Weekly note ✏️

**Selected links:**
- [Sidebar Selection in SwiftUI](https://swiftdevjournal.com/posts/sidebar-selection) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Examines Sidebar Selection in SwiftUI, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Adaptive Sheet Presentation in SwiftUI](https://alexanderweiss.dev/blog/2025-12-30-adaptive-sheet-presentation-in-swiftui) — Article · Topics: Swift · SwiftUI · Testing
  **NeKI brief:** Examines Adaptive Sheet Presentation in SwiftUI, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Mobile Engineers, You’re All Full-Stack](https://newsletter.mobileengineer.io/p/mobile-engineers-youre-all-full-stack?r=g891u&triedRedirect=true) — Article · Topics: Code Quality · Networking · Persistence & Synchronisation
  **NeKI brief:** Examines Mobile Engineers, You’re All Full-Stack, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Intercepting SwiftUI Sheet Dismissal](https://livsycode.com/swiftui/intercepting-swiftui-sheet-dismissal) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Artem shows how to intercept and control sheet dismissal in SwiftUI to detect when a presented sheet is being dismissed, letting you run custom logic or block the dismissal when needed.
- [The Age of Micro-Entrepreneurs](https://merowing.info/posts/the-age-of-micro-entrepreneurs) — Article · Topics: Developer Community & Business · Developer Tools
  **NeKI brief:** Reflects on micro-entrepreneurship and software work. Useful as product and engineering context for evaluating scope, maintenance, and the trade-offs of independent development.
- [Mastering Preview Traits in SwiftUI](https://www.youtube.com/watch?v=zrqFczU1iFg) — Video · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Explains SwiftUI Preview Traits. Useful for structuring preview configurations and checking how representative states improve UI development and review.
- [Replay - Recording and Inspecting App Sessions](https://nshipster.com/replay) — Article · Topics: Objective-C & Cocoa
  **NeKI brief:** Presents Replay, which records HTTP exchanges as HAR files and replays them through URL loading hooks during Swift Testing. The approach keeps networking tests realistic without live servers, while the sensitive-data section makes fixture sanitization part of the design.
- [Discovering iOS Memory Leaks IV: Detecting via Unit Tests](https://www.amanjeet.me/discovering-ios-memory-leaks-iv-detecting-via-unit-tests) — Article · Topics: Testing
  **NeKI brief:** Shows detecting iOS memory leaks through unit tests. Useful for turning leak detection into repeatable verification and catching ownership regressions before they surface during manual profiling.
- [Microsoft renaming Office 365 to the Copilot app](https://support.microsoft.com/en-us/office/the-microsoft-365-app-transition-to-the-microsoft-365-copilot-app-22eac811-08d6-4df3-92dd-77f193e354a5) — Article · Topics: AI Development · Product Design
  **NeKI brief:** Reviews Microsoft renaming Office 365 to the Copilot app. Useful as a focused reference for evaluating the described workflow or technology, while validating current platform behavior and project-specific constraints against primary documentation.
- [iOSKonf26 - iOS Conference in the Balkans](https://www.ioskonf.mk/tickets) — Article · Topics: Developer Community & Business
  **NeKI brief:** Reviews iOSKonf26 - iOS Conference in the Balkans. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.

## [Issue 247](https://thosewhoswift.substack.com/p/those-who-swift-issue-247)

- Published: `2026-01-01`

**Topics:** App Distribution & Store Operations · Architecture · Concurrency · Cross-Platform & Web · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 247 · Weekly note ✏️

**Selected links:**
- [Approachable Concurrency](https://github.com/swiftlang/swift-evolution/blob/main/visions/approachable-concurrency.md) — Source repository · Topics: Concurrency · Developer Tools · Swift
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for the vision document. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Explicit Dependency Injection Best Practices](https://livsycode.com/best-practices/explicit-dependency-injection) — Article · Topics: Architecture · Dependency Injection · Swift
  **NeKI brief:** Explains explicit dependency injection in Swift and why construction-time wiring improves testability. Use it when removing hidden singletons, defining feature boundaries, and keeping production composition separate from previews and test fixtures.
- [Override Color Scheme](https://antongubarenko.substack.com/p/swift-bits-override-color-scheme) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Examines Override Color Scheme, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [SwiftUI Zoom Navigation Transitions](https://www.sagarunagar.com/blog/swiftui-zoom-navigation-transitions) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI Zoom Navigation Transitions, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Introducing Jujutsu VCS](https://swiftwithmajid.com/2025/10/15/introducing-jujutsu-vcs) — Article · Topics: Developer Tools · Swift
  **NeKI brief:** Introduces Jujutsu's change-oriented version-control model and its relationship to Git repositories. Follow it when evaluating workflows for stacked changes, mutable history, and review-friendly experimentation in Swift projects.
- [StoreKit Subscriptions: Understanding Monetization Models](https://azamsharp.com/2025/12/26/storekit-subscriptions-understanding-monetization-models.html) — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **NeKI brief:** Explains StoreKit subscription monetization models. Useful for separating product configuration, eligibility, entitlement state, and paywall presentation when designing subscription flows.
- [F*** Approachable Swift Concurrency](https://fuckingapproachableswiftconcurrency.com/en) — Article · Topics: Concurrency · Swift
  **NeKI brief:** This article covers Swift concurrency through an approachable learning guide. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Swift coming to Android](https://www.swift.org/blog/nightly-swift-sdk-for-android) — Tutorial · Topics: Cross-Platform & Web · Developer Community & Business · Swift
  **NeKI brief:** We can't wait to see what scary things you will Create with Swift tonight! 🎃👻
- [The Swift Predicate Error](https://woodys-findings.com/posts/the-swift-predicate-error) — Article · Topics: Swift
  **NeKI brief:** Explains a Swift Predicate error and its likely type or expression boundary. Useful for debugging SwiftData or predicate construction when compiler diagnostics obscure the actual mismatch.
- [Manus Joins Meta for Next Era of Innovation](https://manus.im/blog/manus-joins-meta-for-next-era-of-innovation) — Article · Topics: AI Development
  **NeKI brief:** Reports Manus joining Meta. Useful as industry context, not as implementation guidance for Apple-platform development.

## [Issue 246](https://thosewhoswift.substack.com/p/those-who-swift-issue-246)

- Published: `2025-12-24`

**Topics:** App Distribution & Store Operations · App Services & Extensions · CI/CD & Automation · Cross-Platform & Web · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 246 · Weekly note ✏️

**Selected links:**
- [Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [Exploring the Swift SDK for Android](https://www.swift.org/blog/exploring-the-swift-sdk-for-android) — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **NeKI brief:** Explores the Swift SDK for Android and its implications for cross-platform Swift development. Use it to understand the emerging toolchain and interoperability story, then verify supported packages, APIs, and production readiness before committing to it.
- [SwiftUI Live Activity Broadcast Push Notifications](https://medium.com/@itsuki.enjoy/swiftui-live-activity-broadcast-push-notifications-1fcf4418f87b) — Article · Topics: App Services & Extensions · Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI Live Activity Broadcast Push Notifications, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Stretchable Header in SwiftUI for Vertical & Horizontal ScrollView](https://livsycode.com/swiftui/stretchable-header-in-swiftui-for-vertical-and-horizontal-scrollview) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Artem explains how to build a stretchable header in SwiftUI that enlarges or shrinks based on scroll position, whether in a vertical or horizontal ScrollView, using geometry readers and view offset tracking.
- [Implementing Consumable In-App Purchases With StoreKit 2](https://www.createwithswift.com/implementing-consumable-in-app-purchases-with-storekit-2) — Article · Topics: App Distribution & Store Operations · Swift
  **NeKI brief:** Walks through StoreKit 2 consumable purchases, transaction handling, and entitlement updates. Use it when implementing one-time consumables and ensuring verified transactions are finished only after app-side delivery succeeds.
- [Adding Custom HTTP Headers to WebView in SwiftUI](https://www.youtube.com/watch?v=bOFTLU3e5Ew) — Video · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a reusable iOS 26 SwiftUI WebView wrapper that injects custom HTTP headers for authenticated content. The walkthrough compares default requests, header configuration, and the component boundary around URL and header state.
- [Swift Concurrency](https://www.swift.org/blog/swift-6.2-released) — Article · Topics: Concurrency · Product Design · Swift
  **NeKI brief:** Swift 6.2 is here with improvements that make coding smoother and faster. It delivers improved performance, faster build times, enhanced tools, and early WebAssembly support, making Swift easier and more reliable for developers.
- [Why Child State Won’t Update From Parent in SwiftUI](https://fatbobman.com/en/snippet/why-child-state-won-not-update-from-parent-in-swiftui) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Explains why a child view's @State does not automatically follow later parent changes after initialization. Useful for distinguishing owned local state from bindings and selecting the correct data-flow fix instead of forcing refreshes.
- [Pragmatic Backend APIs For Mobile Apps](https://newsletter.mobileengineer.io/p/pragmatic-backend-apis-for-mobile?r=g891u&triedRedirect=true) — Article · Topics: Product Design
  **NeKI brief:** Discusses pragmatic backend APIs for mobile apps. Useful for reviewing API shape, failure handling, and client-server boundaries before coupling an iOS client to backend assumptions.
- [Understanding the Responder Chain in iOS](https://dimasw.com/blog/2025/12/21/responder-chain) — Article · Topics: Personal Essays · UIKit
  **NeKI brief:** Explains the iOS responder chain and how events travel through UIKit objects. Useful for debugging action routing and choosing the right ownership point for input handling.
- [moved on to Meta](https://gizmodo.com/alan-dye-leaving-apple-for-meta-liquid-glass-visionos-2000695284) — Article · Topics: Spatial Computing
  **NeKI brief:** Reports on Apple design leadership and Liquid Glass. Useful for high-level ecosystem context, while technical UI decisions require direct platform documentation.
- [forced overnight on iOS 16–18 devices](https://lapcatsoftware.com/articles/2025/12/4.html) — Article · Topics: Cross-Platform & Web
  **NeKI brief:** Examines forced overnight behavior on iOS 16–18 devices. Useful for understanding platform lifecycle and update constraints when diagnosing behavior that appears outside normal foreground app execution.
- [You Are a Frameworks Engineer at Big Tech Corp](https://twocentstudios.com/2025/12/19/you-are-a-frameworks-engineer-at-big-tech-corp) — Article
  **NeKI brief:** Uses a frameworks-engineer scenario to discuss Swift development. Useful for thinking through API design, platform ownership, and the constraints of maintaining a framework used by other teams.

## [Issue 245](https://thosewhoswift.substack.com/p/those-who-swift-issue-245)

- Published: `2025-12-17`

**Topics:** AI Development · App Distribution & Store Operations · Concurrency · Performance · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 245 · Weekly note ✏️

**Selected links:**
- [SwiftUI: Share Wi-Fi Network Credentials With Paired Accessories](https://levelup.gitconnected.com/swiftui-share-wi-fi-network-credentials-with-paired-accessories-30004a4bf8f9) — Article · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI: Share Wi-Fi Network Credentials With Paired Accessories, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [SwiftUI Navigation Pain](https://elegantchaos.com/2025/12/12/navigation-pain.html) — Article · Topics: Navigation & Deep Linking · Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI Navigation Pain, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Non-Sendable-First Design](https://www.massicotte.org/blog/non-sendable-first-design) — Article · Topics: Concurrency · Objective-C & Cocoa · Swift
  **NeKI brief:** Matt argues for designing Swift code around non-Sendable types by default, introducing Sendable and actors only when crossing isolation boundaries to keep concurrency simpler and more intentional.
- [Understanding Scenes for Your macOS App](https://www.createwithswift.com/understanding-scenes-for-your-macos-app) — Article · Topics: macOS & AppKit · Swift · SwiftUI
  **NeKI brief:** Explains macOS SwiftUI scenes and their role in app windows, settings, menu commands, and lifecycle. Use it when decomposing a desktop app beyond one WindowGroup and assigning each surface its proper scene type.
- [Mastering SwiftUI — Free Guide](https://psimas.gumroad.com/l/swiftui?layout=discover&recommended_by=search&_gl=1%2A10g751b%2A_ga%2AODYxNDkzMDQzLjE3NjU2NDU4NjM.%2A_ga_6LJN6D94N6%2AczE3NjU2NDU4NjIkbzEkZzAkdDE3NjU2NDU4NjIkajYwJGwwJGgw) — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Examines Mastering SwiftUI — Free Guide, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Smarter Lists, Labels, and Dictionary Grouping in SwiftUI](https://www.youtube.com/watch?v=PBMqJgtznn4) — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Reviews Smarter Lists, Labels, and Dictionary Grouping in SwiftUI. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Swift Protocols as Existential Types vs. Generic Constraints](https://www.youtube.com/watch?v=-e8Ey6oTI24&t=320s) — Video · Topics: Graphics, Media & Games · Objective-C & Cocoa · Swift
  **NeKI brief:** Reviews Swift Protocols as Existential Types vs. Generic Constraints. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Eight Years with CloudKit](https://fatbobman.com/en/posts/my-eight-years-with-cloudkit) — Article · Topics: Performance · Persistence & Synchronisation
  **NeKI brief:** Examines Eight Years with CloudKit, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [The Power of Ethics in Mobile Design](https://www.createwithswift.com/the-power-of-ethics-in-mobile-design) — Article · Topics: Security & Privacy · Swift
  **NeKI brief:** Examines the ethical influence mobile designers have when shaping behavior, expectations, and trust. Use it to evaluate interaction choices beyond usability and consider how product decisions affect people in everyday contexts.
- [SwiftUI Group Still(?) Considered Harmful](https://twocentstudios.com/2025/12/12/swiftui-group-still-considered-harmful) — Article · Topics: Code Quality · Swift · SwiftUI
  **NeKI brief:** Explains SwiftUI Group Still(?) Considered Harmful, connecting the underlying Apple-platform mechanism to implementation choices and practical trade-offs that Swift developers can evaluate.

## [Issue 244](https://thosewhoswift.substack.com/p/those-who-swift-issue-244)

- Published: `2025-12-11`

**Topics:** AI Development · Concurrency · Foundation & Data Formats · Product Design · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 244 · Weekly note ✏️

**Selected links:**
- [Journey to Swift 6 and Strict Concurrency](https://calcopilot.app/blog/posts/swift-6-and-strict-concurrency) — Article · Topics: AI Development · Concurrency · Swift
  **NeKI brief:** Examines Journey to Swift 6 and Strict Concurrency, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [SwiftUI: Supporting Apple Pay](https://medium.com/@itsuki.enjoy/swiftui-supporting-apple-pay-bbd61fc08d5c) — Article · Topics: Security & Privacy · Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI: Supporting Apple Pay, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [What to Fix in AI-Generated Swift Code](https://www.hackingwithswift.com/articles/281/what-to-fix-in-ai-generated-swift-code) — Article · Topics: AI Development · Swift
  **NeKI brief:** Lists recurring defects in AI-written Swift and suggests concrete replacements, including unsafe assumptions around state, concurrency, and framework behavior. Follow it as a review checklist before accepting generated code into an app.
- [Monitoring App Performance with MetricKit](https://swiftwithmajid.com/2025/12/09/monitoring-app-performance-with-metrickit) — Article · Topics: Performance · Swift
  **NeKI brief:** Uses MetricKit diagnostics to move beyond the aggregate metrics in Xcode Organizer and build more detailed monitoring for crashes, hangs, launches, memory, energy, and terminations.
- [watchOS Development Pitfalls and Practical Tips](https://fatbobman.com/en/posts/watchos-development-pitfalls-and-practical-tips) — Article · Topics: App Services & Extensions · Performance
  **NeKI brief:** Collects production lessons from two watch apps on phone-watch synchronization, mutual launching, abnormal restart recovery, leaks, and battery use. It highlights lifecycle and resource constraints that are difficult to expose in simple watchOS samples.
- [SwiftUI Charts Interactivity — Part 2](https://antongubarenko.substack.com/p/swiftui-charts-interactivity-part-1ed) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Shows interactive SwiftUI Charts techniques. Useful for connecting selection and gestures to chart data while keeping visual feedback and state updates understandable.
- [SwiftUI Book — Big Mountain Studio](https://www.bigmountainstudio.com/free-swiftui-book) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI View Picture Book (FREE), emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Agentic AI Foundation](https://www.linuxfoundation.org/press/linux-foundation-announces-the-formation-of-the-agentic-ai-foundation) — Article · Topics: AI Development · Foundation & Data Formats · Product Design
  **NeKI brief:** Announces the Agentic AI Foundation. Useful for tracking ecosystem governance and interoperability efforts around agent tooling, while separating foundation announcements from concrete APIs.
- [What Settings Should You Use for Swift Concurrency?](https://www.massicotte.org/blog/what-settings) — Article · Topics: Concurrency · Performance · Swift
  **NeKI brief:** Asks which settings to use for Swift concurrency. Useful for auditing compiler and language-mode choices during migration and matching diagnostics to the project’s intended safety level.
- [Finishing the Rich Notes App in SwiftUI](https://www.youtube.com/watch?v=UUvgm9-yltE) — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Reviews Finishing the Rich Notes App in SwiftUI. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Designing With People: Creating Applications for Reality](https://www.createwithswift.com/designing-with-people-creating-applications-for-reality) — Article · Topics: Swift
  **NeKI brief:** Explains why applications should be designed with their communities and real-world circumstances in mind. Use it to ground product decisions in people’s needs rather than treating interface design as an isolated visual exercise.
- [Devstral 2 & Mistral Vibe CLI Released](https://mistral.ai/news/devstral-2-vibe-cli) — Article · Topics: AI Development
  **NeKI brief:** Announces Devstral 2 and Mistral Vibe CLI. Useful for tracking developer-focused model tooling and considering local workflow, capability, and integration constraints.

## [Issue 243](https://thosewhoswift.substack.com/p/those-who-swift-issue-243)

- Published: `2025-12-10`

**Topics:** Cross-Platform & Web · Graphics, Media & Games · Objective-C & Cocoa · Performance · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 243 · Weekly note ✏️

**Selected links:**
- [Initializing Observable Classes Within the SwiftUI Hierarchy](https://nilcoalescing.com/blog/InitializingObservableClassesWithinTheSwiftUIHierarchy) — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **NeKI brief:** Compares ownership patterns for creating @Observable reference types inside SwiftUI, including state storage and dependency injection. Useful for preventing model recreation when view identity changes.
- [Organizing SwiftUI Views with TabContent and TabContentBuilder](https://livsycode.com/swiftui/organizing-swiftui-views-with-tabcontent-and-tabcontentbuilder) — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **NeKI brief:** Artem explains how to organize a SwiftUI project by using a custom @TabContentBuilder to cleanly structure and manage tab-based navigation/components making your code more modular and easier to maintain.
- [Teaching AI to Read Xcode Builds](https://tuist.dev/blog/2025/11/27/teaching-ai-to-read-xcode-builds) — Article · Topics: AI Development · Dependency Injection · Xcode
  **NeKI brief:** Presents Teaching AI to Read Xcode Builds, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Vectorizing Images With LLMs — Image Search & Semantic Matching](https://robkerr.com/vectorizing-images-with-llms) — Article · Topics: AI Development · Objective-C & Cocoa · Persistence & Synchronisation
  **NeKI brief:** Explains vectorizing images with LLMs for semantic search. Useful for designing embedding pipelines, similarity retrieval, and the evaluation needed before using visual search in a product.
- [SwiftUI Charts Interactivity — Part 1](https://antongubarenko.substack.com/p/swiftui-charts-interactivity-part) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI Charts Interactivity — Part 1, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Swift SDK for Android, Shipathon Winners & SwiftUI Scroll Performance](https://www.youtube.com/watch?v=YCRvVfDGQuY) — Video · Topics: Cross-Platform & Web · Performance · Swift
  **NeKI brief:** Reviews Swift SDK for Android, Shipathon Winners & SwiftUI Scroll Performance. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [What’s in a Button?](https://belkadan.com/blog/2025/11/Whats-in-a-Button) — Article · Topics: Accessibility · Hardware & Devices
  **NeKI brief:** Explores implementation details behind a button. Useful for connecting Swift language and UI behavior at a low level when debugging seemingly simple control interactions.
- [Understanding the Transferable Protocol in Swift](https://www.createwithswift.com/understanding-the-transferable-protocol-in-swift) — Article · Topics: Swift
  **NeKI brief:** Explains Transferable representations and type-specific export or import formats for system sharing. Useful when designing drag, drop, paste, or share flows that support more than one data representation.

## [Issue 242](https://thosewhoswift.substack.com/p/those-who-swift-issue-242)

- Published: `2025-11-26`

**Topics:** App Distribution & Store Operations · Cross-Platform & Web · Graphics, Media & Games · Macros & Metaprogramming · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 242 · Weekly note ✏️

**Selected links:**
- [Building Better SwiftUI Modifiers with onGeometryChange](https://dimillian.medium.com/beyond-geometryreader-building-better-swiftui-modifiers-with-ongeometrychange-ac976e5c9107) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Examines Building Better SwiftUI Modifiers with onGeometryChange, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Swift Macros From 0 to Hero](https://levelup.gitconnected.com/swift-macros-from-0-to-hero-0-01-2ff3eac8571a) — Tutorial · Topics: Developer Tools · Macros & Metaprogramming · Swift
  **NeKI brief:** Examines Swift Macros From 0 to Hero, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Tuist: Build Smart Before You Build Fast](https://tuist.dev/blog/2025/11/17/smart-before-fast) — Article · Topics: Developer Career & Practice · Testing
  **NeKI brief:** Presents Build Smart Before You Build Fast, with practical context for Apple-platform developers evaluating the technique, workflow, or engineering decision described on the page.
- [Rich Text Editing in SwiftUI Mastering Attributed Strings in iOS 26](https://www.youtube.com/watch?v=-hKpuysa6PM) — Video · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a Notes-style SwiftUI rich-text editor with iOS 26 AttributedString transformations, formatting controls, alignment, color, and reusable toolbar components. The walkthrough also shows how selection state drives formatting-button feedback.
- [Automatic Property Observation in UIKit with @Observable](https://nilcoalescing.com/blog/AutomaticPropertyObservationInUIKitWithObservable) — Article · Topics: Observation & State Management · Swift · UIKit
  **NeKI brief:** Shows applying @Observable-style automatic property tracking outside SwiftUI, including UIKit. Use it when an imperative UI needs targeted change observation without manually maintaining a broad notification mechanism.
- [From iOS to Android: A Candid Look at My Real-World Journey into Dual-Platform Development](https://fatbobman.com/en/posts/from-ios-to-android) — Article · Topics: Cross-Platform & Web
  **NeKI brief:** Reports the practical costs of extending an iOS product to Android, including feature parity, store rules, monetization, and China-specific distribution. Use it to frame platform expansion as an operational decision, not only a UI rewrite.
- [Designing Humanist Data Visualization for Mobile](https://www.createwithswift.com/designing-humanist-data-visualization-for-mobile) — Article · Topics: Accessibility · Swift
  **NeKI brief:** Explores human-centered mobile data visualization aligned with users’ needs and goals. Use it when choosing visual encodings, hierarchy, and interaction patterns that help people understand data instead of merely displaying it.
- [Introducing Claude Opus 4.5](https://www.anthropic.com/news/claude-opus-4-5) — Article · Topics: AI Development · Testing
  **NeKI brief:** Reviews Introducing Claude Opus 4.5. Useful as a focused reference for evaluating the described workflow or technology, while validating current platform behavior and project-specific constraints against primary documentation.
- [but this one is truly exceptional](https://www.whitehouse.gov/presidential-actions/2025/11/launching-the-genesis-mission) — Article
  **NeKI brief:** Reviews but this one is truly exceptional. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.

## [Issue 241](https://thosewhoswift.substack.com/p/those-who-swift-issue-241)

- Published: `2025-11-20`

**Topics:** App Distribution & Store Operations · Architecture · Liquid Glass · Objective-C & Cocoa · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 241 · Weekly note ✏️

**Selected links:**
- [Singletons with Swift Concurrency](https://www.massicotte.org/singletons) — Article · Topics: Concurrency · Developer Career & Practice · Swift
  **NeKI brief:** Explains Singletons with Swift Concurrency, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [How to Build Scalable White-Label iOS Apps: From Multi-Target to Modular Architecture](https://swiftandmemes.com/how-to-build-scalable-white-label-ios-apps-from-multi-target-to-modular-architecture) — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **NeKI brief:** Explains a white-label iOS architecture that evolves from multi-target projects toward modular components. Use it when separating brand configuration from shared features and assessing build, test, and release trade-offs.
- [Grow on iOS 26: Liquid Glass Adaptation in UIKit + SwiftUI Hybrid Architecture](https://fatbobman.com/en/posts/grow-on-ios26) — Article · Topics: Liquid Glass · Swift · SwiftUI
  **NeKI brief:** Documents Grow's iOS 26 Liquid Glass migration across UIKit and SwiftUI, including navigation refactors, sheet behavior, bar-button sizing, and CABackdropLayer side effects. Follow it for production integration pitfalls beyond sample code.
- [Task Identity in SwiftUI](https://chris.eidhof.nl/post/swiftui-task-identity) — Article · Topics: Dependency Injection · Swift · SwiftUI
  **NeKI brief:** Connects SwiftUI view identity and dependency tracking to the lifetime and restart behavior of tasks. Use it when asynchronous work appears to run with stale inputs or at unexpected times.
- [Generating Images in Swift Using Image Playground](https://swiftwithmajid.com/2025/11/11/generating-images-in-swift-using-image-playground) — Article · Topics: Swift
  **NeKI brief:** Shows generating images through Image Playground from Swift. Use it when designing the app-to-system creation flow, including prompt context, user choice, and availability handling around Apple Intelligence features.
- [Building Peer-to-Peer Sessions: Advertising and Browsing Devices](https://www.createwithswift.com/building-peer-to-peer-sessions-advertising-and-browsing-devices) — Tutorial · Topics: Swift
  **NeKI brief:** Builds peer-to-peer discovery by advertising and browsing nearby devices. Use it when a local collaboration feature needs session establishment without central infrastructure, while designing identity, invitations, and disconnect handling.
- [Autoclosures in Swift](https://www.youtube.com/watch?v=Ktmai_FxJoQ) — Video · Topics: Swift
  **NeKI brief:** Reviews Autoclosures in Swift. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Designing the New Marketing Site at Tuist](https://tuist.dev/blog/2025/11/03/website-redesign) — Article · Topics: Architecture
  **NeKI brief:** Describes Tuist’s website redesign. Useful for examining design-system decisions, content structure, and the engineering trade-offs behind a technical product’s public interface.
- [Embedded Swift Improvements Coming in Swift 6.3](https://www.swift.org/blog/embedded-swift-improvements-coming-in-swift-6.3) — Article · Topics: Swift
  **NeKI brief:** Examines Embedded Swift Improvements Coming in Swift 6.3Embedded Swift is a subset of Swift that’s designed for low… in the context of Combine & Reactive Programming and Foundation & Data Formats. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Weekly note ✏️](https://blog.cloudflare.com/18-november-2025-outage) — Article
  **NeKI brief:** Documents a major Cloudflare outage and its operational causes. Useful for incident-analysis practice, dependency-risk review, and designing failure handling for networked Apple-platform services.

## [Issue 240](https://thosewhoswift.substack.com/p/those-who-swift-issue-240)

- Published: `2025-11-12`

**Topics:** AI Development · CI/CD & Automation · Concurrency · Cross-Platform & Web · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 240 · Weekly note ✏️

**Selected links:**
- [How to Build a Modern Async/Await Location Manager in Swift](https://www.vbutko.com/articles/swift-async-await-location-manager) — Article · Topics: Concurrency · Developer Career & Practice · Swift
  **NeKI brief:** Examines How to Build a Modern Async/Await Location Manager in Swift, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Building Closed-Source Binaries With GitHub Actions](https://danielsaidi.com/blog/2025/11/09/building-closed-source-binaries-with-github-actions) — Article · Topics: Developer Tools · Swift · Swift Package Manager
  **NeKI brief:** Describes building closed-source binaries with GitHub Actions. Useful for designing reproducible distribution pipelines while keeping source private and making signing, artifacts, and release inputs explicit.
- [GSoC 2025 Showcase: Extending Swift-Java Interoperability](https://www.swift.org/blog/gsoc-2025-showcase-swift-java) — Article · Topics: Cross-Platform & Web · Developer Community & Business · Swift
  **NeKI brief:** Showcases Swift-Java interoperability work from GSoC. Useful for assessing cross-language integration patterns and the practical boundaries of Swift tooling beyond Apple platforms.
- [Introducing Temporal Swift SDK: Building Durable Workflows](https://www.swift.org/blog/swift-temporal-sdk) — Article · Topics: Concurrency · Macros & Metaprogramming · Swift
  **NeKI brief:** Introduces a Temporal SDK for Swift and explains how Swift code can define durable workflows. Follow it when assessing workflow orchestration, persistence, retries, and deployment boundaries for server-side or long-running Swift services.
- [Creating Ornaments in visionOS](https://www.createwithswift.com/creating-ornaments-in-visionos) — Tutorial · Topics: Spatial Computing · Swift · SwiftUI
  **NeKI brief:** Introduces ornaments in visionOS and shows how they provide persistent controls around a volumetric or immersive experience. Use it when placing secondary actions spatially without obscuring content or treating visionOS surfaces like ordinary iOS toolbars.
- [Using SwiftUI Foundation Models Transcripts to build a Chatbot](https://www.youtube.com/watch?v=cyOqYbWpQzU) — Video · Topics: AI Development · Foundation & Data Formats · Swift
  **NeKI brief:** Builds an on-device travel chatbot from a Foundation Models LanguageModelSession transcript, rendering user and model messages with thinking, scrolling, availability, guardrail, and error states. Useful for connecting session history to SwiftUI presentation.
- [SwiftUI Discardable Slider](https://open.substack.com/pub/antongubarenko/p/swiftui-discardable-slider) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI Discardable Slider, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Smoothly Switching Between Layouts in SwiftUI with AnyLayout](https://livsycode.com/swiftui/smoothly-switching-between-layouts-in-swiftui-with-anylayout) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Artem demonstrates how to use AnyLayout in SwiftUI to toggle between different layout containers with animation while preserving view identity and enabling smooth transitions across layout changes.
- [Creative Coding: Randomness and Noise](https://www.createwithswift.com/creative-coding-randomness-and-noise) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Uses deterministic randomness and noise functions to generate creative Swift visuals. Useful for procedural backgrounds and experiments where repeatable seeds matter more than hand-authored coordinates.
- [Tracking Workouts With HealthKit in iOS Apps](https://www.createwithswift.com/tracking-workouts-with-healthkit-in-ios-apps) — Article · Topics: Health Apps · Swift
  **NeKI brief:** Shows reading and recording workout data through HealthKit. Follow it when designing authorization, quantity queries, background updates, and privacy-aware presentation of fitness information.
- [Meet the new Swift Android SDK with Joannis Orlandos](https://www.youtube.com/watch?v=IfqdY9nuWTo) — Video · Topics: Cross-Platform & Web · Swift
  **NeKI brief:** Reviews Meet the new Swift Android SDK with Joannis Orlandos. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Say What You See — Google Arts & Culture Experiment](https://artsandculture.google.com/experiment/say-what-you-see/jwG3m7wQShZngw) — Article · Topics: AI Development
  **NeKI brief:** Provides an interactive visual experiment. Useful for exploring multimodal interaction ideas, but it is not a conventional Apple-platform technical reference.

## [Issue 239](https://thosewhoswift.substack.com/p/those-who-swift-issue-239)

- Published: `2025-11-05`

**Topics:** AI Development · App Distribution & Store Operations · Concurrency · Objective-C & Cocoa · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 239 · Weekly note ✏️

**Selected links:**
- [Organizing SwiftUI Views With ToolbarContent and ToolbarContentBuilder](https://livsycode.com/swiftui/organizing-swiftui-views-with-toolbarcontent-and-toolbarcontentbuilder) — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **NeKI brief:** Artem explains how to clean up and modularize toolbar code, making your toolbar items reusable, easier to reason about, and better aligned with view architecture.
- [Guided Generation with Foundation Models in Swift](https://www.youtube.com/watch?v=kBwwztRY1FQ) — Video · Topics: AI Development · Foundation & Data Formats · Swift
  **NeKI brief:** Uses Foundation Models @Generable and @Guide macros for structured workout and title responses, including partial streaming and guardrail errors. Useful for comparing schema-guided output with parsing unconstrained model text.
- [Swift Concurrency Part 2](https://www.nsvasilev.com/posts/swift-concurrency-part-2) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Examines Swift Concurrency Part 2, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Building a Custom Markdown Formatter in Swift: The Journey and Why Unit Tests Matter](https://medium.com/@majidboudaoud/building-a-custom-markdown-formatter-in-swift-the-journey-and-why-unit-tests-matter-d47a80a4847f) — Article · Topics: Swift · Testing
  **NeKI brief:** Examines Building a Custom Markdown Formatter in Swift: The Journey and Why Unit Tests Matter, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Making Apps More Personal with Language Discovery](https://www.createwithswift.com/making-apps-more-personal-with-language-discovery) — Article · Topics: Product Design · Swift
  **NeKI brief:** Shows how Language Discovery can reflect users’ languages and cultural contexts in an app experience. Use it when planning localization-aware personalization that goes beyond selecting a display language.
- [Playing With Sheet (on iOS)](https://captainswiftui.substack.com/p/playing-with-sheet-on-ios) — Article · Topics: Product Design · Swift · SwiftUI
  **NeKI brief:** Experiments with iOS sheet presentation behavior. Useful for comparing detents, dismissal, and interaction constraints before building modal flows around assumptions from one device size.
- [Combine Annotations and Swift Concurrency](https://www.massicotte.org/combine-annotations) — Article · Topics: Combine & Reactive Programming · Concurrency · Swift
  **NeKI brief:** Explains The Problem With Combine Annotations, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Optimize Your App’s Speed & Efficiency: Q&A](https://antongubarenko.substack.com/p/optimize-your-apps-speed-and-efficiency) — Article · Topics: Developer Career & Practice · Graphics, Media & Games · Performance
  **NeKI brief:** Answers practical questions about improving app speed and efficiency. Useful for turning broad performance concerns into measurable work across launch, rendering, networking, and resource usage.
- [iOS26, SwiftUI and Accessibility](https://www.youtube.com/watch?v=CEZbwcv60MA&t=5s) — Video · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Reviews iOS26, SwiftUI and Accessibility. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Introducing Cursor 2.0 and Composer](https://cursor.com/blog/2-0) — Article · Topics: Personal Essays
  **NeKI brief:** Introduces Cursor 2.0 and Composer. Useful for evaluating agent-assisted code editing, multi-file context, and review boundaries before incorporating an AI editor into a production workflow.
- [ChatGPT in Xcode 26: There’s a Hidden Prompt!](https://youtu.be/e75mdQL-I8o) — Video · Topics: Xcode
  **NeKI brief:** Demonstrates ChatGPT integration in Xcode 26. Useful for examining AI-assisted editor workflows while keeping generated changes subject to repository review and platform verification.
- [Linear Algebra Chapter 2: The Dot Product](https://www.ducktyped.org/p/linear-algebra-chapter-2-the-dot?trk=feed_main-feed-card_feed-article-content) — Article
  **NeKI brief:** Explains the dot product in linear algebra. Useful for understanding similarity and projection calculations before implementing graphics, search, or machine-learning algorithms.

## [Issue 238](https://thosewhoswift.substack.com/p/those-who-swift-issue-238)

- Published: `2025-10-29`

**Topics:** AI Development · Concurrency · Cross-Platform & Web · Graphics, Media & Games · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 238 · Weekly note ✏️

**Selected links:**
- [Announcing the Swift SDK for Android](https://www.swift.org/blog/nightly-swift-sdk-for-android) — Article · Topics: Cross-Platform & Web · Swift · Swift Package Manager
  **NeKI brief:** We can't wait to see what scary things you will Create with Swift tonight! 🎃👻
- [Power-Up SwiftUI Form Validation with Key Paths](https://danielsaidi.com/blog/2025/10/24/power-up-swiftui-form-validation-with-key-paths) — Article · Topics: Security & Privacy · Swift · SwiftUI
  **NeKI brief:** Examines Power-Up SwiftUI Form Validation with Key Paths, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Foundation Models Framework in Swift Getting Started with On Device AI](https://www.youtube.com/watch?v=p17HrjVQKOQ) — Video · Topics: AI Development · Foundation & Data Formats · Swift
  **NeKI brief:** Reviews Foundation Models Framework in Swift Getting Started with On Device AI. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Free iOS eBook: Build faster. Ship with confidence.](https://bitrise.io/whitepapers/level-up-your-ios-game-tips-for-speeding-up-your-continuous-integration) — Article · Topics: CI/CD & Automation · Graphics, Media & Games
  **NeKI brief:** Discusses Save Time on Every Build and Test Run in a public developer resource. Use it to compare the author's concrete workflow and trade-offs with your project constraints, and verify any platform-specific claims against current primary documentation.
- [Concurrency Step-by-Step: Conforming to Protocols](https://www.massicotte.org/step-by-step-conforming-to-protocols) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Matt offers a walkthrough in organizing protocol requirements and extensions especially under concurrency by explaining how and when to isolate protocol conformances, solve isolation mismatches and apply proven best practices for robust, actor-aware code.
- [SwiftUI Custom URL Schemes](https://useyourloaf.com/blog/swiftui-custom-url-schemes) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Explains registering and handling custom URL schemes in SwiftUI. Use it when routing external links into navigation state and deciding how to validate, authenticate, and fall back from malformed deep links.
- [AI Agents Comparison from iOS Developer Perspective](https://brightinventions.pl/blog/ai-agents-comparison-from-ios-dev-perspective) — Article · Topics: AI Development · Developer Tools
  **NeKI brief:** Compares AI agents from an iOS developer perspective. Useful for assessing where agents help with coding workflows and where review, context, and platform verification remain necessary.
- [Exploring Widgets: Crafting Glanceable Experiences](https://www.createwithswift.com/exploring-widgets-crafting-glanceable-experiences) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explores WidgetKit timelines and glanceable design constraints for SwiftUI widgets. Follow it when deciding what data can be rendered from a snapshot and how refresh policy affects freshness and battery use.
- [Building iOS Apps Without Xcode, Using Cursor, Claude Code](https://www.youtube.com/watch?v=V7TNvf3fWTw) — Video · Topics: AI Development · Xcode
  **NeKI brief:** Reviews Building iOS Apps Without Xcode, Using Cursor, Claude Code. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Ten Years of Being an Indie Developer](https://ikennd.ac/blog/2025/10/ten-years-of-being-indie) — Article · Topics: Developer Career & Practice · Personal Essays
  **NeKI brief:** Reflects on ten years as an indie developer. Useful for engineering and product context around maintenance, scope, and the long-term cost of shipping a small app.
- [Manus 1.5 Released](https://manus.im/blog/manus-1.5-release) — Article
  **NeKI brief:** Announces a Manus product release. Useful for tracking agent-product capabilities while separating vendor claims from measured engineering behavior.

## [Issue 237](https://thosewhoswift.substack.com/p/those-who-swift-issue-237)

- Published: `2025-10-22`

**Topics:** AI Development · Combine & Reactive Programming · Concurrency · Developer Community & Business · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 237 · Weekly note ✏️

**Selected links:**
- [Crafting Interactive Tiles in SwiftUI](https://uvolchyk.me/blog/crafting-interactive-tiles-in-swiftui) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Examines Crafting Interactive Tiles in SwiftUI, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Generative AI for Beginners – Microsoft GitHub Course](https://github.com/microsoft/generative-ai-for-beginners) — Source repository · Topics: AI Development · Developer Community & Business · Developer Tools
  **NeKI brief:** Offers a practical course on generative AI concepts. Useful for engineers building AI-enabled features who need a structured path through models, prompting, evaluation, and application integration.
- [SwiftUI Custom Progress Bar With Masking](https://livsycode.com/swiftui/swiftui-custom-progress-bar-with-masking) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates a custom SwiftUI progress bar built with masking. Follow it for branded progress visuals, separating measured progress from drawing, animation, and accessibility values so the control remains meaningful without the decoration.
- [The Fast Engineer Trap](https://digitalbunker.dev/the-fast-engineer-trap) — Article · Topics: Developer Tools · Testing
  **NeKI brief:** Examines the fast-engineer trap and its costs. Useful for reflecting on delivery incentives, sustainable engineering practice, and where speed can conceal quality or maintenance risk.
- [Getting Started With Multipeer Connectivity in Swift](https://www.createwithswift.com/getting-started-with-multipeer-connectivity-in-swift) — Article · Topics: Foundation & Data Formats · Swift
  **NeKI brief:** Walks through discovering nearby peers and exchanging data with Multipeer Connectivity in Swift. Useful for prototyping local collaboration, device-to-device transfer, or shared experiences while reasoning about sessions, invitations, connectivity changes, and transport limitations.
- [Combine Subjects vs AsyncStream in Swift](https://tanaschita.com/swift-combine-subjects-vs-asyncstream) — Article · Topics: Combine & Reactive Programming · Concurrency · Swift
  **NeKI brief:** Compares Combine subjects with `AsyncStream`, contrasting multicasting and operator ecosystems with Swift Concurrency's cancellation-aware async iteration. Follow it when migrating event pipelines and deciding whether a stream needs replay, multiple consumers, or structured concurrency.
- [Handle Out-of-Scope Expertise Collaboration](https://open.substack.com/pub/swiftdiscovery/p/indie-app-devs-6?r=21t43r&showWelcomeOnShare=false) — Article · Topics: Swift
  **NeKI brief:** Examines Handle Out-of-Scope Expertise Collaboration, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Adding dSYMs from a Closed-Source Swift SDK to an App](https://danielsaidi.com/blog/2025/10/19/adding-dsyms-from-a-closed-source-sdk-to-your-app) — Article · Topics: Swift
  **NeKI brief:** Explains adding dSYM files from a closed-source SDK to an app. Useful for restoring symbolication and actionable crash diagnostics when vendor binaries otherwise leave production stack traces opaque.
- [Singletons and Swift Concurrency: Rethinking Global Mutable State](https://www.massicotte.org/singletons) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains Singletons with Swift Concurrency, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Introducing ChatGPT Atlas](https://www.youtube.com/watch?v=8UWKxJbjriY) — Video · Topics: AI Development · Cross-Platform & Web
  **NeKI brief:** Reviews Introducing ChatGPT Atlas. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Unlock more sales with multiple payment methods](https://developer.paddle.com/concepts/sell/hosted-checkout-mobile-apps) — Article · Topics: Developer Community & Business
  **NeKI brief:** Describes Paddle hosted checkout flows for selling through mobile apps. Use it to understand payment-page integration, handoff, and return handling before implementing a compliant purchase experience.
- [Don’t Make This Mistake With a TaskGroup](https://www.swiftwithvincent.com/blog/dont-make-this-mistake-with-a-taskgroup) — Article · Topics: Swift
  **NeKI brief:** Explains Don't make this mistake with a TaskGroup, focusing on the underlying Swift or Apple-platform mechanism and the implementation trade-offs relevant to production code.

## [Issue 236](https://thosewhoswift.substack.com/p/those-who-swift-issue-236)

- Published: `2025-10-15`

**Topics:** CI/CD & Automation · Concurrency · Developer Community & Business · Swift · SwiftUI · Testing

**Sections:** Those Who Swift · Those Who Swift - Issue 236 · Weekly note ✏️

**Selected links:**
- [Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [Image Caching in SwiftUI](https://www.createwithswift.com/image-caching-in-swiftui) — Article · Topics: Concurrency · Swift · SwiftUI
  **NeKI brief:** Demonstrates image caching for SwiftUI content to avoid repeated downloads and decoding. Follow it when designing cache keys, memory/disk policy, and loading states for remote image-heavy screens.
- [SwiftUI Concentric Rectangle & Concentric Corners in iOS 26](https://www.youtube.com/watch?v=VFnidjiH750) — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Explores SwiftUI's ConcentricRectangle and concentric-corner clipping APIs through per-corner radii, container-aware shapes, sheets, popovers, and tiled images. Useful for understanding how nested geometry can preserve visually consistent corners.
- [7 Custom Progress Indicators for SwiftUI](https://medium.com/@himalimarasinghe/7-custom-progress-indicators-for-swiftui-with-code-c8c877b9c82d) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines 7 Custom Progress Indicators, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [SwiftLeeds – Questions & Answers](https://danielsaidi.com/blog/2025/10/11/swiftleeds-questions-and-answers) — Article · Topics: Developer Career & Practice · Swift
  **NeKI brief:** Collects questions and answers from SwiftLeeds. Useful for community perspectives on current Swift and Apple-platform practice, while treating individual recommendations as context to validate in a project.
- [SwiftUI: Auto-Applying Glass Styles](https://tanaschita.com/swiftui-glass-auto-apply) — Article · Topics: Liquid Glass · Swift · SwiftUI
  **NeKI brief:** Explains when SwiftUI automatically applies Liquid Glass and when explicit modifiers are required. Useful for diagnosing inconsistent material appearance across containers and platform contexts.
- [Purchase here.](https://a.co/d/eTPTooh) — Tutorial · Topics: Concurrency · Developer Community & Business · Testing
  **NeKI brief:** Routes to a purchase page rather than technical reading. Useful only as a commercial lead, not as a knowledge-index source.
- [Building for Love: Creating Authentic Connections](https://www.createwithswift.com/building-for-love-creating-authentic-connections) — Article · Topics: Swift
  **NeKI brief:** Discusses product design that builds authentic connections by focusing on user emotions and intentional choices. Use it when evaluating whether an experience communicates purpose and trust rather than optimizing only for engagement.
- [Show Icons Only in SwiftUI Swipe Actions on iOS 26](https://nilcoalescing.com/blog/ShowIconsOnlyInSwiftUISwipeActionsOnIOS26) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows how iOS 26 SwiftUI swipe actions can present icons without visible button titles. Use it to create compact row actions while checking discoverability, accessibility labels, destructive styling, and whether the reduced affordance remains understandable.
- [Beyond QA: Mobile Testing Strategies](https://mobilesystemdesign.substack.com/p/beyond-qa-mobile-testing-strategies) — Article · Topics: CI/CD & Automation · Testing
  **NeKI brief:** Discusses mobile testing strategies beyond conventional QA. Useful for combining exploratory, automated, and production-signal approaches when assessing confidence in an iOS release.
- [Friends 🤝](https://substack.com/profile/13130783-david-grigoryan) — Article · Topics: Performance · Swift
  **NeKI brief:** Reviews Friends 🤝. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [iPhone 17 Screen Sizes](https://useyourloaf.com/blog/iphone-17-screen-sizes) — Article
  **NeKI brief:** Summarizes the 2025 iPhone 17 screen sizes and their display differences. Use it when checking layout assumptions, preview coverage, and responsive constraints for devices introduced with that generation.

## [Issue 235](https://thosewhoswift.substack.com/p/those-who-swift-issue-235)

- Published: `2025-10-08`

**Topics:** Foundation & Data Formats · Liquid Glass · Performance · Swift · SwiftUI · Testing

**Sections:** Those Who Swift · Those Who Swift - Issue 235 · Weekly note ✏️

**Selected links:**
- [iOS 26: Foundation Model Framework - Code-Along Q&A](https://antongubarenko.substack.com/p/ios-26-foundation-model-framework-f6d) — Article · Topics: AI Development · Foundation & Data Formats · Testing
  **NeKI brief:** Examines iOS 26: Foundation Model Framework - Code-Along Q&A, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Programmatic Navigation in SwiftUI](https://www.createwithswift.com/programmatic-navigation-with-navigation-destination-in-swiftui) — Article · Topics: Navigation & Deep Linking · Swift · SwiftUI
  **NeKI brief:** Uses navigationDestination for state-driven SwiftUI navigation. Use it when routing should be expressed through typed destinations and path state instead of imperative pushes scattered across child views.
- [Adopting Liquid Glass: Experiences and Pitfalls](https://juniperphoton.substack.com/p/adopting-liquid-glass-experiences) — Article · Topics: Liquid Glass · Testing
  **NeKI brief:** Examines Adopting Liquid Glass: Experiences and Pitfalls, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Creating Custom Controls in SwiftUI: Learnable, Memorable, Accessible](https://www.swiftjectivec.com/creating-custom-controls-swiftui-learnable-memorable-accessibile) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Jordan provides guidance and best practices for building custom user interface controls in SwiftUI, with a strong focus on making them easy to learn, visually memorable and highly accessible.
- [Introducing Swift Profile Recorder](https://www.swift.org/blog/swift-profile-recorder) — Article · Topics: Performance · Swift · Swift Package Manager
  **NeKI brief:** Introduces Swift Profile Recorder for capturing runtime profiling data from Swift applications. Useful for collecting reproducible performance evidence in environments where full Instruments sessions are impractical.
- [How to Use OptionSet in Swift](https://www.vbutko.com/articles/how-to-use-optionset-in-swift) — Article · Topics: Swift
  **NeKI brief:** Reviews How to Use OptionSet in Swift. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Why a custom ViewModifier is often useless! (in SwiftUI)](https://www.youtube.com/watch?v=ATYmQxJglxE) — Video · Topics: Swift · SwiftUI
  **NeKI brief:** Reviews Why a custom ViewModifier is often useless! (in SwiftUI). Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [See Everything. Fix Anything. Stay Ahead of Bugs!](https://bugfender.com/try-bugfender) — Article
  **NeKI brief:** Bugfender’s page presents its mobile logging and crash-debugging service for collecting device-side diagnostics. Follow it for a concrete observability workflow, while treating the vendor’s feature and pricing claims as contextual.
- [An Illustrated Introduction to Linear Algebra](https://www.ducktyped.org/p/an-illustrated-introduction-to-linear) — Article
  **NeKI brief:** Introduces linear algebra with illustrated explanations. Useful for building intuition about vectors and transformations that underpin graphics, embeddings, and data-processing code.

## [Issue 234](https://thosewhoswift.substack.com/p/those-who-swift-issue-234)

- Published: `2025-10-01`

**Topics:** AI Development · Concurrency · Foundation & Data Formats · Swift · SwiftUI · Xcode

**Sections:** Those Who Swift · Those Who Swift - Issue 234 · Weekly note ✏️

**Selected links:**
- [SwiftUI: Eliminating Navigation Registration](https://medium.com/the-swift-cooperative/swiftui-eliminating-navigation-registration-7339691c2887) — Article · Topics: Navigation & Deep Linking · Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI: Eliminating Navigation Registration, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [AsyncSequence for Real-Time APIs](https://medium.com/@wesleymatlock/asyncsequence-for-real-time-apis-from-legacy-polling-to-swift-6-elegance-c2b8139c21e0) — Article · Topics: Combine & Reactive Programming · Concurrency · Swift
  **NeKI brief:** Examines AsyncSequence for Real-Time APIs, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Foundation Models Profiling with Xcode Instruments](https://artemnovichkov.com/blog/foundation-models-profiling-with-xcode-instruments) — Article · Topics: AI Development · Foundation & Data Formats · Performance
  **NeKI brief:** Artem shows how to profile and optimize Foundation Models performance using Xcode Instruments, tracking response time, token usage and tool calls to help developers improve performance on real devices.
- [An Apple Intelligence-Style Glow Effect in SwiftUI](https://livsycode.com/swiftui/an-apple-intelligence-style-glow-effect-in-swiftui) — Tutorial · Topics: AI Development · Swift · SwiftUI
  **NeKI brief:** Artem demonstrates how to create an “Apple Intelligence” style glow effect in SwiftUI by applying visual effects (like blurs and overlays) to achieve a glowing UI appearance.
- [What is Approachable Concurrency in Xcode 26?](https://www.youtube.com/watch?v=-YPXrXD6sqE) — Video · Topics: Concurrency · Swift · Xcode
  **NeKI brief:** Reviews What is Approachable Concurrency in Xcode 26?. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Free iOS eBook: Build faster. Ship with confidence.](https://bitrise.io/whitepapers/level-up-your-ios-game-tips-for-speeding-up-your-continuous-integration) — Article · Topics: CI/CD & Automation · Graphics, Media & Games
  **NeKI brief:** Discusses Save Time on Every Build and Test Run in a public developer resource. Use it to compare the author's concrete workflow and trade-offs with your project constraints, and verify any platform-specific claims against current primary documentation.
- [Implementing Drag-and-Drop With The SwiftUI Modifiers](https://www.createwithswift.com/implementing-drag-and-drop-with-the-swiftui-modifiers) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows SwiftUI drag-and-drop using the framework's transfer modifiers. Follow it when connecting draggable representations to drop destinations and keeping data conversion, validation, and visual feedback explicit.
- [Structuring Universal Links in iOS](https://tanaschita.com/swiftui-navigation-universal-links-architecture) — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **NeKI brief:** Structures universal-link handling around SwiftUI navigation state. Use it when parsing an incoming URL, restoring a scene, and selecting a nested destination must work consistently on cold launch and while running.
- [Claude Sonnet 4.5 Released](https://www.anthropic.com/news/claude-sonnet-4-5) — Article · Topics: AI Development · Developer Tools
  **NeKI brief:** Reviews Claude Sonnet 4.5 Released. Useful as a focused reference for evaluating the described workflow or technology, while validating current platform behavior and project-specific constraints against primary documentation.
- [Introducing Swift Configuration](https://forums.swift.org/t/introducing-swift-configuration/82368) — Article · Topics: Swift
  **NeKI brief:** Introduces Swift Configuration. Useful for evaluating configuration management in Swift projects and separating build-time inputs from application runtime behavior.

## [Issue 233](https://thosewhoswift.substack.com/p/those-who-swift-issue-233)

- Published: `2025-09-24`

**Topics:** Architecture · Localization · Objective-C & Cocoa · Swift · SwiftUI · Testing

**Sections:** Those Who Swift · Those Who Swift - Issue 233 · Weekly note ✏️

**Selected links:**
- [Localization Troubles With Swift PM](https://www.scottberrevoets.com/2025/09/19/localization-troubles-with-swift-pm) — Article · Topics: Localization · Swift · Swift Package Manager
  **NeKI brief:** Examines Localization Troubles With Swift PM, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Create Interactive Snippet Shortcut Using App Intents](https://www.swiftjectivec.com/create-interactive-snippet-shortcut-in-appintents) — Article · Topics: App Intents & System Surfaces · Architecture · Dependency Injection
  **NeKI brief:** Jordan shows how to build an interactive SwiftUI snippet powered by App Intents to create a responsive counter view with buttons, manage state with dependencies, and see how App Intents can add dynamic shortcuts to your app.
- [The TCA Playbook: Debugging Large Reducers Without Losing Your Mind](https://medium.com/@wesleymatlock/the-tca-playbook-debugging-large-reducers-without-losing-your-mind-e8813c9c6eda) — Article · Topics: Composable Architecture · Developer Tools · Performance
  **NeKI brief:** Examines The TCA Playbook: Debugging Large Reducers Without Losing Your Mind, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Is MVVM a bad architecture for SwiftUI?](https://www.youtube.com/watch?v=KY4jvbrlzMM) — Video · Topics: Architecture · Objective-C & Cocoa · Swift
  **NeKI brief:** Questions MVVM's fit with SwiftUI, traces why it became popular, and separates framework habits from broader architectural goals before giving a personal recommendation. Useful when evaluating state ownership and maintainability.
- [How To Use [weak self] In Swift Concurrency Tasks](https://www.donnywals.com/how-to-use-weak-self-in-swift-concurrency-tasks) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Explains how weak self interacts with Swift concurrency tasks and object lifetime. Use it to choose capture strategies deliberately, avoiding retain cycles without accidentally discarding work that should complete.
- [Getting Started With The Contacts Framework](https://www.createwithswift.com/getting-started-with-the-contacts-framework) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Introduces access to user contacts from SwiftUI applications. Use it to plan authorization, fetching, and presentation boundaries while keeping contact data handling explicit and privacy-conscious.
- [Meet Vapor for VS Code](https://blog.vapor.codes/posts/vapor-for-vscode) — Article · Topics: Swift
  **NeKI brief:** Introduces Vapor tooling for Visual Studio Code. Useful for evaluating editor-based server-side Swift workflows and the boundary between language support and framework tooling.
- [Launch your app’s website, paywall, and checkout in minutes](https://www.paddle.com/web-monetization-kit) — Article · Topics: Testing
  **NeKI brief:** Reviews Launch your app’s website, paywall, and checkout in minutes. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Hidden Gems in the Swift Argument Parser - Part II](https://swifttoolkit.dev/posts/argument-parser-gems-2) — Article · Topics: Swift
  **NeKI brief:** Examines Build your command-line tools in Swift in the context of Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.

## [Issue 232](https://thosewhoswift.substack.com/p/those-who-swift-issue-232)

- Published: `2025-09-17`

**Topics:** App Services & Extensions · Objective-C & Cocoa · Observation & State Management · Swift · SwiftUI · Testing

**Sections:** Those Who Swift · Those Who Swift - Issue 232 · Weekly note ✏️

**Selected links:**
- [Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [SwiftUI Redraw System In Depth](https://medium.com/@matgnt/swiftui-redraw-system-in-depth-attributes-recomputation-diffing-and-observation-66b469fdcada) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Presents a concrete implementation of SwiftUI Redraw System In Depth. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.
- [Swift Protocol Oriented Design: Build a Pluggable Data Source](https://blog.stackademic.com/swift-protocol-oriented-design-build-a-pluggable-data-source-57e7937312aa) — Article · Topics: Objective-C & Cocoa · Swift · Testing
  **NeKI brief:** Examines Swift Protocol Oriented Design: Build a Pluggable Data Source, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [The Northern Stars of Liquid Glass](https://captainswiftui.substack.com/p/the-northern-stars-of-liquid-glass) — Article · Topics: Liquid Glass · Objective-C & Cocoa · Swift
  **NeKI brief:** Danny breaks down Apple’s three core Liquid Glass principles (Hierarchy, Harmony and Consistency) showing how they guide layering, rhythm and predictability in modern SwiftUI apps and how to apply them in real-world designs.
- [How To Manage View Lifecycle Events In SwiftUI](https://tanaschita.com/swiftui-view-lifecycle-events) — Article · Topics: Concurrency · Swift · SwiftUI
  **NeKI brief:** Explains SwiftUI lifecycle callbacks such as task, onAppear, and onDisappear and their execution behavior. Follow it when attaching loading or cleanup work without accidentally duplicating effects across view identity changes.
- [We Need to Talk About Observation](https://jaredsinclair.com/2025/09/10/observation.html) — Article · Topics: Cross-Platform & Web · Developer Career & Practice · Observation & State Management
  **NeKI brief:** Explains We Need to Talk About Observation, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Developer Mode Guide — OpenAI Platform](https://platform.openai.com/docs/guides/developer-mode) — Article · Topics: AI Development · Developer Tools · Security & Privacy
  **NeKI brief:** Documents OpenAI Platform developer mode. Useful for understanding tool and environment configuration in agent workflows, with credentials and execution permissions treated as explicit boundaries.
- [Feature Flags in Swift](https://swiftwithmajid.com/2025/09/16/feature-flags-in-swift) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows modeling feature flags in Swift and routing conditional behavior through a centralized configuration. Use it when controlling staged releases while keeping flag evaluation testable and avoiding scattered compile-time or global checks.
- [Swift 6.2 Released](https://www.swift.org/blog/swift-6.2-released) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Swift 6.2 is here with improvements that make coding smoother and faster. It delivers improved performance, faster build times, enhanced tools, and early WebAssembly support, making Swift easier and more reliable for developers.
- [SwiftUI’s New Glassy Controls – Toolbars & Modal Sheets](https://www.youtube.com/watch?v=IiLDbrtBsn0&t=1053s) — Video · Topics: Liquid Glass · Swift · SwiftUI
  **NeKI brief:** Reviews SwiftUI’s New Glassy Controls – Toolbars & Modal Sheets. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Turn Your Photos Into Miniature Magic With Nano Banana](https://peterfriese.dev/blog/2025/gemini-nano-banana-ios) — Article · Topics: AI Development
  **NeKI brief:** Demonstrates integrating Gemini's Nano Banana image generation into an iOS app to transform photos into miniature scenes. Useful for evaluating an image-generation feature end to end, including prompt construction, media handling, latency, and product safeguards.
- [Big O](https://samwho.dev/big-o) — Article · Topics: Objective-C & Cocoa
  **NeKI brief:** Explains Big O notation and algorithmic growth. Useful for comparing performance trade-offs and communicating complexity before choosing an implementation or data structure.
- [Understanding Live Activities: Visual Micro-Storytelling](https://www.createwithswift.com/understanding-live-activities-visual-micro-storytelling) — Article · Topics: App Services & Extensions · Swift
  **NeKI brief:** Explains Live Activities as a visual storytelling surface driven by timely state updates. Useful for designing concise lock-screen and Dynamic Island experiences without treating them as miniature full screens.

## [Issue 231](https://thosewhoswift.substack.com/p/those-who-swift-issue-231)

- Published: `2025-09-10`

**Topics:** AI Development · Concurrency · Graphics, Media & Games · Liquid Glass · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 231 · Weekly note ✏️

**Selected links:**
- [Liquid Glass Sheets with NavigationStack & Form](https://nilcoalescing.com/blog/LiquidGlassSheetsWithNavigationStackAndForm) — Article · Topics: Liquid Glass · Swift · SwiftUI
  **NeKI brief:** Explains composing Liquid Glass sheets with NavigationStack and Form, including presentation structure and styling boundaries. Follow it when migrating modal editing flows to iOS 26 while keeping navigation titles, controls, and form content legible.
- [Using MainActor.assumeIsolated to Solve Legacy API Compatibility Issues with Swift 6](https://weekly.fatbobman.com/p/fatbobmans-swift-weekly-0101?publication_id=843693&post_id=173061745&isFreemail=true&r=21t43r&triedRedirect=true) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Examines Using MainActor.assumeIsolated to Solve Legacy API Compatibility Issues with Swift 6, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Exploring Concentricity in SwiftUI](https://www.createwithswift.com/exploring-concentricity-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explores SwiftUI concentric geometry and how nested rounded surfaces align with the system's corner treatment. Useful for custom iOS 26 cards and containers that should feel native under Liquid Glass.
- [SwiftUI’s New Glassy Controls – Toggles, Sliders & Menus](https://www.youtube.com/watch?v=-9QxBHmcQpI) — Video · Topics: Swift · SwiftUI
  **NeKI brief:** Reviews SwiftUI’s New Glassy Controls – Toggles, Sliders & Menus. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [LLM Interactive Guide](https://bbycroft.net/llm) — Article · Topics: AI Development
  **NeKI brief:** This article covers a visual, comprehensive introduction to large language models. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [SwiftUI: Text Color & Concatenation](https://antongubarenko.substack.com/p/swiftui-text-color-and-concatenation) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents SwiftUI: Text Color & Concatenation, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [When Should You Use an Actor?](https://www.massicotte.org/actors) — Article · Topics: Concurrency
  **NeKI brief:** Matt explores when actors are the right tool in Swift, explaining their unique isolation domain capabilities, why this protection mechanism matters for concurrent programming and outlining the specific conditions that make them the optimal choice.
- [See Everything. Fix Anything. Stay Ahead of Bugs!](https://bugfender.com/try-bugfender) — Article
  **NeKI brief:** Bugfender’s page presents its mobile logging and crash-debugging service for collecting device-side diagnostics. Follow it for a concrete observability workflow, while treating the vendor’s feature and pricing claims as contextual.
- [Backup Disks You Can Use With Time Machine Update](https://support.apple.com/en-gb/102423?cid=mc-ols-TimeMachine-article_102423-Settings-04282025) — Article
  **NeKI brief:** Reviews Backup Disks You Can Use With Time Machine Update. Useful as a focused reference for evaluating the described workflow or technology, while validating current platform behavior and project-specific constraints against primary documentation.

## [Issue 230](https://thosewhoswift.substack.com/p/those-who-swift-issue-230)

- Published: `2025-09-03`

**Topics:** CI/CD & Automation · Concurrency · Foundation & Data Formats · Swift · Swift Package Manager · Testing

**Sections:** Those Who Swift · Those Who Swift - Issue 230 · Weekly note ✏️

**Selected links:**
- [Forget about Ruby and Fastlane installation issues!](https://github.com/codemagic-ci-cd/cli-tools) — Source repository · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [The Great Shift in Apple Development](https://captainswiftui.substack.com/p/the-great-shift-in-apple-development) — Article · Topics: Architecture · Swift · SwiftUI
  **NeKI brief:** Examines The Great Shift in Apple Development, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Treating Warnings as Errors in Swift Packages](https://useyourloaf.com/blog/treating-warnings-as-errors-in-swift-packages) — Article · Topics: Code Quality · Swift · Swift Package Manager
  **NeKI brief:** Configures Swift Package builds to treat warnings as errors. Use it to keep library quality gates strict, while staging adoption so existing warnings do not block unrelated migration work.
- [Switching SPM Dependencies Between Versioned and Local Development](https://tanaschita.com/spm-quick-tip-on-switching-to-local-dev) — Article · Topics: Dependency Injection · Swift · Swift Package Manager
  **NeKI brief:** Shows how to switch a Swift Package dependency between a versioned remote requirement and a local checkout during development. Use it to test package changes quickly while preserving a clean, reproducible dependency declaration for collaborators and CI.
- [Swift progres: UIKit iOS 26, FoundationModels API and SPM traits](https://www.youtube.com/watch?v=Ew101hvrWJk) — Video · Topics: AI Development · Foundation & Data Formats · UIKit
  **NeKI brief:** Surveys Swift ecosystem changes around SwiftPM package traits, Foundation Models, UIKit in iOS 26, and proposed stat types for Swift System. Use the linked proposals and documentation to verify each evolving feature.
- [What’s New in Swift 6.2 (Beyond Concurrency Updates)](https://www.youtube.com/watch?v=0hI_4OWN31o) — Video · Topics: Concurrency · Swift
  **NeKI brief:** Reviews What’s New in Swift 6.2 (Beyond Concurrency Updates). Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Building a Design System at Genius Scan](https://www.swiftbysundell.com/articles/building-a-design-system-at-genius-scan) — Article · Topics: Swift
  **NeKI brief:** Describes building a shared design system with reusable components, tokens, and constraints at Genius Scan. Useful for connecting SwiftUI component reuse to product consistency and team-scale maintenance.
- [Get Your Indie App Noticed and Featured by Journalists](https://open.substack.com/pub/swiftdiscovery/p/indie-app-devs-3) — Article · Topics: Swift
  **NeKI brief:** This Swift Discovery article discusses independent app development and the tools or practices surrounding it. Use it for practitioner perspective and idea generation, not as authoritative guidance on current Apple APIs or store policy.
- [Design as Brand: The Power of Choice and Belief](https://www.createwithswift.com/design-as-brand-the-power-of-choice-and-belief) — Article · Topics: Product Design · Swift
  **NeKI brief:** Shows how brand choices and messages can be communicated through application design. Use it to align visual language, interaction details, and product beliefs into a coherent user-facing identity.
- [The Psychology of Fixing Bugs](https://lapcatsoftware.com/articles/2025/8/8.html) — Article · Topics: Cross-Platform & Web · Security & Privacy
  **NeKI brief:** Examines the psychology of fixing bugs. Useful for recognizing diagnostic bias and improving debugging habits instead of jumping to the first plausible code change.

## [Issue 229](https://thosewhoswift.substack.com/p/those-who-swift-issue-229)

- Published: `2025-08-27`

**Topics:** Architecture · Foundation & Data Formats · Graphics, Media & Games · Objective-C & Cocoa · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 229 · Weekly note ✏️

**Selected links:**
- [FoundationModels: Tool Calling for an Assistant App](https://destiner.io/blog/post/foundation-models-tool-calling-search-app) — Article · Topics: AI Development · Foundation & Data Formats · Objective-C & Cocoa
  **NeKI brief:** Applies Foundation Models tool calling to an assistant-style search app. Useful for examining tool schemas, model-controlled actions, and the validation boundary before executing search operations.
- [Custom Animations with Timing Curves in SwiftUI: Make Your UI Rock](https://medium.com/@wesleymatlock/custom-animations-with-phaseanimator-e5134891e0b7) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines Custom Animations with Timing Curves in SwiftUI: Make Your UI Rock, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [ChatGPT in Xcode 26: is it as good as Cursor or Claude Code?](https://www.youtube.com/watch?v=BCUjW0TkaUY) — Video · Topics: AI Development · Xcode
  **NeKI brief:** Compares Xcode 26's integrated ChatGPT workflow with Cursor and Claude Code from an iOS developer's perspective. Use it to identify editor-integration trade-offs and limitations rather than as a definitive tool ranking.
- [High-Level Anatomy of a Camera Capturing Session](https://mfaani.com/posts/ios/swiftui-camera-learnings) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Examines High-Level Anatomy of a Camera Capturing Session, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [What your app’s MVP needs to have?](https://swiftdiscovery.substack.com/p/indie-app-devs-2) — Article · Topics: Swift
  **NeKI brief:** Examines What your app’s MVP needs to have?, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [An Illustrated Guide to OAuth](https://www.ducktyped.org/p/an-illustrated-guide-to-oauth) — Article · Topics: Security & Privacy
  **NeKI brief:** Shows custom guardrails for Foundation Models generation. Useful for constraining model output and adding application-level checks around on-device AI features.
- [Setting Alarms for Calendar Events](https://www.createwithswift.com/setting-alarms-for-calendar-events) — Article · Topics: Swift
  **NeKI brief:** Demonstrates adding an alarm that notifies users before a calendar event starts. Use it when modeling event reminders and deciding how notification timing should be represented and edited.
- [iOS Personal VPN and Network Extensions: A Developer’s Guide](https://antongubarenko.substack.com/p/ios-personal-vpn-and-network-extensions) — Article
  **NeKI brief:** Explains personal VPN and Network Extension development on iOS. Useful for mapping entitlement, provider, and lifecycle constraints before implementing traffic routing or tunnel configuration.
- [Scaling your mobile app? Join Paddle Web Revenue Labs](https://www.paddle.com/events/web-revenue-labs-2025) — Article
  **NeKI brief:** This Paddle event page promotes Web Revenue Labs for mobile-app monetization. It is event marketing rather than technical reading and should normally be excluded from the knowledge index.
- [UITabAccessory Backward Compatibility](https://furbo.org/2025/08/21/uitabaccessory-backward-compatibility) — Article
  **NeKI brief:** Discusses UITabAccessory backward compatibility. Useful for planning availability fallbacks when adopting newer UIKit tab-bar APIs across supported iOS versions.

## [Issue 228](https://thosewhoswift.substack.com/p/those-who-swift-issue-228)

- Published: `2025-08-20`

**Topics:** AI Development · Concurrency · Foundation & Data Formats · Persistence & Synchronisation · Swift · SwiftData

**Sections:** Those Who Swift · Those Who Swift - Issue 228 · Weekly note ✏️

**Selected links:**
- [How to Work with SwiftData in the Background in Swift 6](https://www.natashatherobot.com/p/swiftdata-background-swift-6) — Article · Topics: AI Development · Swift · SwiftData
  **NeKI brief:** Explains How to Work with SwiftData in the Background in Swift 6, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Make Foundation Models Deterministic: Greedy Decoding in Swift](https://www.youtube.com/watch?v=Q6x3VeGlqwg) — Video · Topics: AI Development · Foundation & Data Formats · Swift
  **NeKI brief:** Configures Apple's Foundation Models GenerationOptions for greedy decoding so identical inputs produce more repeatable output. Useful for debugging and tests that need reduced sampling variance while recognizing model behavior is not universally deterministic.
- [Swift Sendable: A Practical Guide to Safer Concurrency](https://medium.com/@himalimarasinghe/swift-sendable-a-practical-guide-to-safer-concurrency-88826e44fd6c) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Examines Swift Sendable: A Practical Guide to Safer Concurrency, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Hidden Gems in the Swift Argument Parser – Part I](https://swifttoolkit.dev/posts/argument-parser-gems) — Article · Topics: Developer Tools · Swift
  **NeKI brief:** Examines Hidden Gems in the Swift Argument Parser – Part I, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Getting Access to the User’s Calendar](https://www.createwithswift.com/getting-access-to-the-users-calendar) — Tutorial · Topics: Swift
  **NeKI brief:** Explains requesting access to and interacting with a user’s calendar and reminder data. Use it to separate authorization, EventKit queries, and data presentation in a SwiftUI feature.
- [Remote’s Global Life-Work Balance Index 2025](https://remote.com/resources/research/global-life-work-balance-index) — Article · Topics: Concurrency · Objective-C & Cocoa
  **NeKI brief:** Presents a global work-life balance index. Useful as organizational context, not as a technical Apple-platform source.
- [Inspect & Optimize Image Decoding Timing in iOS](https://juniperphoton.substack.com/p/inspect-and-optimize-image-decoding) — Article · Topics: Graphics, Media & Games · Performance
  **NeKI brief:** Measures image-decoding timing in iOS. Useful for locating decoding work on the critical path and deciding whether image format, sizing, caching, or scheduling changes will improve responsiveness.
- [Nonisolated Functions Become Nonsending by Default in Swift 6.2](https://docs.swift.org/compiler/documentation/diagnostics/nonisolated-nonsending-by-default) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Documents Swift 6.2’s change making nonisolated functions nonsending by default. Useful for auditing concurrency diagnostics and understanding which isolation or sending annotations must change during migration.
- [Liquid Glass. Why?](https://furbo.org/2025/08/17/liquid-glass-why) — Article · Topics: Liquid Glass
  **NeKI brief:** Explores why Liquid Glass matters in Apple-platform UI. Useful for evaluating visual-system changes in terms of hierarchy, interaction, and platform behavior rather than decoration alone.
- [See Everything. Fix Anything. Stay Ahead of Bugs!](https://bugfender.com/try-bugfender) — Article
  **NeKI brief:** Bugfender’s page presents its mobile logging and crash-debugging service for collecting device-side diagnostics. Follow it for a concrete observability workflow, while treating the vendor’s feature and pricing claims as contextual.
- [How We Approach Releases at Vapor](https://blog.vapor.codes/posts/how-we-do-vapor-releases) — Article
  **NeKI brief:** Describes the Vapor project’s release workflow. Useful for comparing release automation, compatibility communication, and maintenance expectations in server-side Swift ecosystems.

## [Issue 227](https://thosewhoswift.substack.com/p/those-who-swift-issue-227)

- Published: `2025-08-13`

**Topics:** App Intents & System Surfaces · Concurrency · Graphics, Media & Games · Navigation & Deep Linking · Objective-C & Cocoa · Swift

**Sections:** Those Who Swift · Those Who Swift - Issue 227 · Weekly note ✏️

**Selected links:**
- [Core Spotlight Integration for Spotlight & In-App Search](https://nilcoalescing.com/blog/CoreSpotlightIntegration) — Article · Topics: App Intents & System Surfaces · Cross-Platform & Web · Objective-C & Cocoa
  **NeKI brief:** Shows using a shared Core Spotlight index to expose app content to system Spotlight and internal search. Useful for designing one indexing pipeline with searchable attributes, stable identifiers, updates, and deletion handling across both search surfaces.
- [Tuist’s AI Whitepaper](https://tuist.dev/blog/2025/08/11/tuist-ai-whitepaper) — Article · Topics: AI Development · Swift · Testing
  **NeKI brief:** Examines Tuist’s AI Whitepaper, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Creating Core Image Metal Shader Library in a Swift Package Plugin](https://juniperphoton.substack.com/p/creating-core-image-metal-shader) — Article · Topics: Graphics, Media & Games · Swift · Swift Package Manager
  **NeKI brief:** Examines Creating Core Image Metal Shader Library in a Swift Package Plugin, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [NavigationStack Deep Linking in Large SwiftUI Apps](https://medium.com/@wesleymatlock/%EF%B8%8F-navigationstack-deep-linking-in-large-swiftui-apps-439a1ce77337) — Article · Topics: Navigation & Deep Linking · Swift · SwiftUI
  **NeKI brief:** Examines NavigationStack Deep Linking in Large SwiftUI Apps, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Vibe check your code](https://coderabbit.link/ios-dt) — Article · Topics: AI Development · Code Quality
  **NeKI brief:** Introduces CodeRabbit’s AI-assisted code review tooling for iOS development. Use it to assess IDE review workflows, automated findings, and the boundary between generated suggestions and human approval.
- [Designing Custom AlarmKit Interfaces in SwiftUI](https://www.createwithswift.com/designing-custom-alarmkit-interfaces-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows how to create personalized alarm interfaces with AlarmKit and SwiftUI. Use it when building alarm configuration or status screens that need system integration with a custom presentation.
- [How to Build iOS Apps with Cursor and Claude Code](https://www.youtube.com/watch?v=OgWbnJ3romI) — Video · Topics: AI Development · Graphics, Media & Games
  **NeKI brief:** Reviews How to Build iOS Apps with Cursor and Claude Code. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Exploring the Foundation Models Framework](https://www.createwithswift.com/exploring-the-foundation-models-framework) — Article · Topics: AI Development · Foundation & Data Formats · Swift
  **NeKI brief:** Introduces Apple's Foundation Models framework and its on-device language-model capabilities. Useful for mapping model sessions, availability, and structured generation before integrating AI into an app.
- [Assembler for Swift Developers — Part 2](https://arturgruchala.com/assembler-for-swift-developers-part-2) — Article · Topics: Swift · Systems Programming
  **NeKI brief:** Introduces assembler concepts for Swift developers in a second practical installment. Useful for relating low-level instructions to compiler output and performance investigation without treating assembly as a substitute for measurement.
- [3 Swift Concurrency Challenges from the Last 2 Weeks](https://twocentstudios.com/2025/08/12/3-swift-concurrency-challenges-from-the-last-2-weeks) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Presents practical Swift concurrency challenges. Useful for testing isolation, cancellation, and task structure against realistic code rather than relying on simplified examples.

## [Issue 225](https://thosewhoswift.substack.com/p/those-who-swift-issue-225)

- Published: `2025-08-07`

**Topics:** App Distribution & Store Operations · Graphics, Media & Games · Objective-C & Cocoa · Security & Privacy · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 225 · Weekly note ✏️

**Selected links:**
- [What Is a Mobile Platform Engineer](https://mobilesystemdesign.substack.com/p/what-is-a-mobile-platform-engineer) — Article · Topics: Architecture · CI/CD & Automation · Performance
  **NeKI brief:** Examines What Is a Mobile Platform Engineer, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [SwiftUI Search Enhancements in iOS and iPadOS 26](https://nilcoalescing.com/blog/SwiftUISearchEnhancementsIniOSAndiPadOS26) — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **NeKI brief:** Shows iOS and iPadOS 26 SwiftUI search enhancements for placement, suggestions, and presentation. Useful for modernizing search flows without rebuilding the search field and toolbar integration.
- [Liskov Substitution Principle: Writing Trustworthy Swift Code](https://swiftandmemes.com/liskov-substitution-principle-lsp-in-ios-how-to-write-trustworthy-code) — Article · Topics: Swift
  **NeKI brief:** Explains the Liskov Substitution Principle with iOS examples. Useful for reviewing protocol and type hierarchies where substitutability affects testability, extension, and behavioral correctness.
- [Assembler for Swift Developers](https://arturgruchala.com/assembler-for-swift-developers) — Article · Topics: Swift · Systems Programming
  **NeKI brief:** This article covers assembly-language concepts explained for Swift developers. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [iOS 26: SpeechAnalyzer Guide](https://antongubarenko.substack.com/p/ios-26-speechanalyzer-guide) — Article
  **NeKI brief:** Guides SpeechAnalyzer integration in iOS 26. Useful for understanding the framework’s transcription pipeline and identifying the device, audio-session, and availability assumptions an implementation must verify.
- [See Everything. Fix Anything. Stay Ahead of Bugs!](https://bugfender.com/try-bugfender) — Article · Topics: Swift
  **NeKI brief:** Bugfender’s page presents its mobile logging and crash-debugging service for collecting device-side diagnostics. Follow it for a concrete observability workflow, while treating the vendor’s feature and pricing claims as contextual.
- [Uncertain: Modeling GPS Accuracy](https://nshipster.com/uncertainty) — Article · Topics: Swift
  **NeKI brief:** Uses uncertainty as a modeling problem for noisy sensors, locations, and user behavior rather than forcing false precision into scalar values. It is useful when designing APIs that must carry confidence or probabilistic outcomes explicitly.
- [Beyond Mouse & Keyboard: Blender on iPad](https://code.blender.org/2025/07/beyond-mouse-keyboard) — Tutorial · Topics: Hardware & Devices
  **NeKI brief:** Blender is working on a version for iPadOS with the goal of bringing its full power to a wider audience making 3D technology accessible for everyone. This shift is crucial especially for the visionOS platform where the best experiences are made of amazing 3D…

## [Issue 226](https://thosewhoswift.substack.com/p/those-who-swift-issue-226)

- Published: `2025-08-06`

**Topics:** AI Development · Concurrency · Foundation & Data Formats · Liquid Glass · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 226 · Weekly note ✏️

**Selected links:**
- [Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [Using Foundation Models Framework to Stream from External LLM Providers](https://www.natashatherobot.com/p/foundationmodels-streaming-external-llm) — Article · Topics: AI Development · Foundation & Data Formats · Xcode
  **NeKI brief:** Examines Using Foundation Models Framework to Stream from External LLM Providers, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Swift Concurrency: Part 1](https://www.nsvasilev.com/posts/swift-concurrency-part-1) — Article · Topics: Concurrency · Foundation & Data Formats · Swift
  **NeKI brief:** Examines Swift Concurrency: Part 1, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Define Scroll Edge Effect Style for a ScrollView in Liquid Glass](https://www.createwithswift.com/define-the-scroll-edge-effect-style-of-a-scroll-view-for-liquid-glass) — Article · Topics: Liquid Glass · Swift
  **NeKI brief:** Configures scroll-edge effects for Liquid Glass scroll views. Use it when content transitions into system material need deliberate visual treatment rather than inheriting an unsuitable default.
- [Sendable, sending, and Nonsending Explained](https://fatbobman.com/en/posts/sendable-sending-nonsending) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Compares Sendable, sending, and nonsending boundaries in Swift concurrency. Use it when designing APIs that transfer values across isolation domains and need precise ownership or compiler-checking semantics.
- [Swift Observations AsyncSequence for State Changes](https://useyourloaf.com/blog/swift-observations-asyncsequence-for-state-changes) — Article · Topics: Combine & Reactive Programming · Concurrency · Swift
  **NeKI brief:** Connects Swift Observation state changes to AsyncSequence consumption. Use it when a task should react to model updates without Combine, while defining lifetime and cancellation ownership.
- [SharingGRDB Public Beta](https://www.pointfree.co/blog/posts/181-a-swiftdata-alternative-with-sqlite-cloudkit-public-beta) — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** Announces a SQLite and CloudKit synchronization alternative to SwiftData. Use it to investigate relational persistence and sync options, then verify API maturity and operational trade-offs before adoption.
- [gpt-oss by OpenAI](https://github.com/openai/gpt-oss) — Source repository · Topics: AI Development · Developer Tools · Performance
  **NeKI brief:** Publishes OpenAI’s open-weight GPT models and related artifacts. Useful for inspecting model distribution and runtime integration details while keeping deployment, hardware, and licensing assumptions explicit.
- [AI Use Cases](https://github.com/Engineer1999/A-Curated-List-of-ML-System-Design-Case-Studies) — Source repository · Topics: AI Development · Architecture · Developer Tools
  **NeKI brief:** Collects machine-learning system-design case studies. Useful for broadening architecture review vocabulary around data, models, serving, and operational trade-offs.
- [Building for Hate: Designing for Deception](https://www.createwithswift.com/building-for-hate-designing-for-deception) — Article · Topics: Swift
  **NeKI brief:** Distinguishes persuasive interface design from manipulative deception and examines the consequences. Use it as a review prompt for dark-pattern risks in onboarding, permissions, monetization, and retention flows.
- [Understanding Swift’s @available Attribute](https://tanaschita.com/swift-available-attribute) — Article · Topics: Swift
  **NeKI brief:** Explains Swift's @available attribute for marking APIs by platform, version, deprecation, or obsolescence. Useful when evolving libraries across OS releases and writing availability annotations that communicate migration paths without accidentally hiding supported code.
- [Liquid Glass - 5 Things You MUST Know Before Implementing](https://www.youtube.com/watch?v=aF2qt5WfprM) — Video · Topics: Liquid Glass
  **NeKI brief:** Reviews Liquid Glass - 5 Things You MUST Know Before Implementing. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Qwen-Image](https://huggingface.co/Qwen/Qwen-Image) — Article · Topics: Graphics, Media & Games
  **NeKI brief:** Presents Qwen-Image and its model artifacts. Useful for evaluating image-generation capabilities and deployment constraints while keeping benchmark results separate from app-level product decisions.

## [Issue 224](https://thosewhoswift.substack.com/p/those-who-swift-issue-224)

- Published: `2025-07-24`

**Topics:** AI Development · Concurrency · Swift · Swift Package Manager · SwiftUI · Testing

**Sections:** Those Who Swift · Those Who Swift - Issue 224 · Weekly note ✏️

**Selected links:**
- [Approachable Concurrency in Swift Packages](https://useyourloaf.com/blog/approachable-concurrency-in-swift-packages) — Article · Topics: Concurrency · Swift · Swift Package Manager
  **NeKI brief:** Applies approachable concurrency settings to Swift packages and explains how target configuration changes diagnostics. Useful for aligning library and application migration plans.
- [Enable Horizontal and Vertical Scrolling with ScrollView](https://www.createwithswift.com/enable-horizontal-and-vertical-scrolling-with-scrollview) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Shows configuring ScrollView for both horizontal and vertical content. Follow it when building bidirectional canvases or nested scrolling layouts and needing explicit axis, sizing, and gesture decisions.
- [The Last UIKit Developer](https://dimillian.medium.com/the-last-uikit-developer-079f59e835d4) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Examines The Last UIKit Developer, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Giving Claude Code Eyes to See Your SwiftUI Views](https://twocentstudios.com/2025/07/13/giving-claude-code-eyes-to-see-your-swiftui-views) — Article · Topics: Swift · SwiftUI · Testing
  **NeKI brief:** Chriss shows a method to enhance Claude Code’s AI-assisted SwiftUI development by letting the model visually verify and iteratively refine its view-generated code based on image comparisons.
- [Mastering Forms in SwiftUI: Sliders and Steppers](https://www.createwithswift.com/mastering-forms-in-swiftui-sliders-and-steppers) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds SwiftUI forms with Slider and Stepper controls, showing how values, labels, ranges, and formatting work together. Use it when creating adjustable settings screens that need clear feedback, sensible bounds, and accessible control descriptions.
- [How to Obfuscate API Keys in Your Swift Apps Step by Step with ConfidentialKit](https://www.youtube.com/watch?v=FfXK0IrX0p0) — Video · Topics: Swift · SwiftUI
  **NeKI brief:** Reviews How to Obfuscate API Keys in Your Swift Apps Step by Step with ConfidentialKit. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Presenting Liquid Glass Sheets in SwiftUI](https://nilcoalescing.com/blog/PresentingLiquidGlassSheetsInSwiftUI) — Article · Topics: Liquid Glass · Swift · SwiftUI
  **NeKI brief:** Demonstrates presenting sheets that participate in iOS 26 Liquid Glass styling and detents. Useful for adopting system material behavior while keeping modal content and dismissal state explicit.
- [A Peek into Debugging Process](https://www.polpiella.dev/how-i-fix-bugs-in-my-apps) — Article · Topics: Developer Tools
  **NeKI brief:** Describes an evidence-first bug-fixing workflow that captures reproduction, narrows the failing path, and adds regression coverage. Useful as a practical debugging process rather than a framework recipe.
- [Let vs Var for Struct Properties in Swift](https://www.swiftbysundell.com/articles/let-vs-var-for-swift-struct-properties) — Article · Topics: Swift
  **NeKI brief:** Examines let versus var properties in Swift structs and how immutability affects mutation and API design. Useful for choosing value semantics deliberately in models and view state.
- [Scaling your mobile app? Join Paddle Web Revenue Labs](https://www.paddle.com/events/web-revenue-labs-2025) — Article
  **NeKI brief:** This Paddle event page promotes Web Revenue Labs for mobile-app monetization. It is event marketing rather than technical reading and should normally be excluded from the knowledge index.

## [Issue 223](https://thosewhoswift.substack.com/p/those-who-swift-issue-223)

- Published: `2025-07-16`

**Topics:** AI Development · App Distribution & Store Operations · macOS & AppKit · Macros & Metaprogramming · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 223 · Weekly note ✏️

**Selected links:**
- [Creating and Customizing the Menu Bar of a SwiftUI App](https://www.createwithswift.com/creating-and-customizing-the-menu-bar-of-a-swiftui-app) — Article · Topics: macOS & AppKit · Swift · SwiftUI
  **NeKI brief:** Explains creating and customizing a SwiftUI menu bar for iPadOS and macOS. Use it when deciding menu structure, commands, and platform-specific navigation behavior for a multi-platform app.
- [Swift Macros in the Wild: Building Reusable SwiftUI Views with @expression](https://medium.com/%40wesleymatlock/swift-macros-in-the-wild-building-reusable-swiftui-views-with-expression-99a321b54693) — Article · Topics: Macros & Metaprogramming · Swift · SwiftUI
  **NeKI brief:** Examines Swift Macros in the Wild: Building Reusable SwiftUI Views with @expression, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Supporting Reduced Motion Accessibility in iOS](https://tanaschita.com/ios-accessibility-reduced-motion) — Article · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Shows responding to the system Reduced Motion preference in iOS, with SwiftUI-oriented implementation guidance. Follow it when animations communicate state but must be simplified or removed for motion-sensitive users.
- [FoundationModels: Basic Prompting for an iOS Reader App](https://destiner.io/blog/post/foundation-models-basic-prompting-ios-reader-app) — Article · Topics: AI Development · Foundation & Data Formats · Security & Privacy
  **NeKI brief:** Introduces basic Foundation Models prompting in an iOS reader app. Useful for connecting on-device model requests to app context, prompt design, and user-visible failure handling.
- [Two Practical Ways to Use matchedGeometryEffect() in SwiftUI](https://www.youtube.com/watch?v=i87zOQubYoI) — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Reviews Two Practical Ways to Use matchedGeometryEffect() in SwiftUI. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Handling WebView Navigation in SwiftUI](https://www.artemnovichkov.com/blog/handling-webview-navigation-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Handles WKWebView navigation callbacks inside a SwiftUI wrapper, including coordinator delegation and policy decisions. Useful for exposing web navigation state without leaking UIKit controller details into feature views.
- [Introducing Kiro: Agentic IDE for Spec‑Driven Development](https://kiro.dev/blog/introducing-kiro) — Article · Topics: AI Development · Product Design
  **NeKI brief:** Introduces Kiro as a spec-driven agentic IDE. Useful for evaluating requirements-first development, generated changes, and the review boundaries needed around AI-assisted coding.
- [Swift’s Measurement API — From Miles to Meters and Beyond](https://www.youtube.com/watch?v=tXbYO5MGjYU) — Video · Topics: Graphics, Media & Games · Swift
  **NeKI brief:** Reviews Swift’s Measurement API — From Miles to Meters and Beyond. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Windowing on iPadOS (Or How I Learned to Love the Backlog Bomb)](https://captainswiftui.substack.com/p/windowing-on-ipados-or-how-i-learned) — Article · Topics: macOS & AppKit · Swift · SwiftUI
  **NeKI brief:** Danny explores the new iPadOS 26 windowing system showing how to implement resizable, interactive windows in SwiftUI, use environment actions like openWindow and pushWindow, and set custom placements.
- [Everything but the Code](https://www.hackingwithswift.com/store/everything-but-the-code) — Article · Topics: Swift
  **NeKI brief:** Reviews Everything but the Code. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Grok 4 & Grok 4 Heavy Launch](https://x.ai/news/grok-4) — Article · Topics: AI Development · Performance
  **NeKI brief:** Announces Grok 4 and Grok 4 Heavy. Useful for model-release context and capability comparison, with production suitability requiring independent evaluation.
- [CalcGPT.io](https://github.com/Calvin-LL/CalcGPT.io) — Source repository · Topics: AI Development · Developer Tools
  **NeKI brief:** Provides a small SwiftUI app for exploring calculator behavior. Useful for inspecting a concrete Apple-platform codebase and evaluating how UI state, calculation logic, and project structure are organized.
- [Icon Composer Notes](https://www.virtualsanity.com/202507/icon-composer-notes) — Article · Topics: Apple Platform Ecosystem
  **NeKI brief:** Reviews Icon Composer Notes. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.

## [Issue 222](https://thosewhoswift.substack.com/p/those-who-swift-issue-222)

- Published: `2025-07-10`

**Topics:** AI Development · Code Quality · Concurrency · Swift · SwiftUI · Testing

**Sections:** Those Who Swift · Those Who Swift - Issue 222 · Weekly note ✏️

**Selected links:**
- [CodeRabbit’s Free AI Code Reviews in your IDE—VS Code, Cursor, Windsurf](https://coderabbit.link/ios-dt) — Article · Topics: AI Development · Code Quality · Developer Tools
  **NeKI brief:** Introduces CodeRabbit’s AI-assisted code review tooling for iOS development. Use it to assess IDE review workflows, automated findings, and the boundary between generated suggestions and human approval.
- [Using WebKit to Load Web Content in SwiftUI](https://www.artemnovichkov.com/blog/using-webkit-to-load-web-content-in-swiftui) — Article · Topics: Concurrency · Swift · SwiftUI
  **NeKI brief:** Artem explores the new WebView and WebPage APIs demonstrating how to integrate web views, handle loading states, and save content as snapshots, all with SwiftUI.
- [Setting Default Actor Isolation in Xcode 26](https://www.donnywals.com/what-is-approachable-concurrency-in-xcode-26) — Article · Topics: Concurrency · Developer Career & Practice · Xcode
  **NeKI brief:** Explains Xcode 26's approachable concurrency settings and how default actor isolation changes migration ergonomics. Useful when staging strict concurrency adoption without immediately annotating every legacy declaration.
- [Adapting Search to the Liquid Glass Design System](https://www.createwithswift.com/adapting-search-to-the-liquid-glass-design-system) — Article · Topics: Liquid Glass · Objective-C & Cocoa · Swift
  **NeKI brief:** Explores search behavior within Apple’s Liquid Glass design system in SwiftUI. Use it to adapt search placement, styling, and interaction while preserving the system’s visual hierarchy.
- [Grouping Elements Within a Glass Effect Container in SwiftUI](https://www.createwithswift.com/grouping-elements-within-a-glass-effect-container-in-swiftui) — Tutorial · Topics: Liquid Glass · Swift · SwiftUI
  **NeKI brief:** Shows how to group SwiftUI views inside a glass effect container so related controls share a coherent Liquid Glass surface. Useful for designing hierarchy and spacing while avoiding a collection of visually competing individual glass elements.
- [How to Add Custom Guardrails to Apple’s FoundationModels Generation](https://www.natashatherobot.com/p/add-custom-guardrails-foundationmodels) — Article · Topics: AI Development · Foundation & Data Formats
  **NeKI brief:** Uses cosine similarity and Accelerate for RAG in Swift. Useful for connecting vector math, embedding search, and performance considerations in an Apple-platform retrieval pipeline.
- [Introducing the Animatable Macro in SwiftUI](https://swiftwithmajid.com/2025/07/08/introducing-animatable-macro-in-swiftui) — Article · Topics: Macros & Metaprogramming · Swift · SwiftUI
  **NeKI brief:** Explains SwiftUI's @Animatable macro as a way to synthesize animatable-data handling for custom views. Use it when complex values should interpolate correctly without maintaining a fragile manual AnimatableData implementation.
- [An Open‑Source SDK for Finding Dead Code](https://blog.sentry.io/an-open-source-sdk-for-finding-dead-code) — Article · Topics: Cross-Platform & Web
  **NeKI brief:** Examines How Duolingo deleted 1% of their code using this Open Source tool in the context of Apple-platform engineering. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Watch here.](https://www.youtube.com/watch?v=dCSf9nR6SOQ) — Video · Topics: Swift · SwiftUI
  **NeKI brief:** Reviews Watch here.. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.

## [Issue 221](https://thosewhoswift.substack.com/p/those-who-swift-issue-221)

- Published: `2025-07-02`

**Topics:** AI Development · Cross-Platform & Web · Developer Tools · Foundation & Data Formats · Liquid Glass · Swift

**Sections:** Those Who Swift · Those Who Swift - Issue 221 · Weekly note ✏️

**Selected links:**
- [Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [Getting Started with Apple's Foundation Models](https://www.artemnovichkov.com/blog/getting-started-with-apple-foundation-models) — Article · Topics: AI Development · Foundation & Data Formats · Swift
  **NeKI brief:** Artem walks through using Apple’s new on-device Foundation Models framework to integrate Apple Intelligence’s LLMs into SwiftUI apps.
- [Supporting Dynamic Type Accessibility in iOS](https://tanaschita.com/ios-accessibility-dynamic-type) — Article · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Covers Dynamic Type support in SwiftUI, including scalable text and layout testing at accessibility sizes. Follow it when fixed frames or custom typography undermine the user's selected reading scale.
- [Copilot Open Source AI Editor: First Milestone](https://code.visualstudio.com/blogs/2025/06/30/openSourceAIEditorFirstMilestone) — Article · Topics: AI Development · Developer Community & Business · Developer Tools
  **NeKI brief:** Describes an early milestone of an open-source AI editor based on VS Code. Useful for comparing editor extensibility, agent integration, and the operational trade-offs of adopting an evolving toolchain.
- [Android Apps in Swift: Getting Started with Skip](https://www.youtube.com/watch?v=AWRPubyQ9V8) — Video · Topics: Cross-Platform & Web · Graphics, Media & Games · Swift
  **NeKI brief:** Reviews Android Apps in Swift: Getting Started with Skip. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Decoding Swift Types That Require Additional Data](https://www.swiftbysundell.com/articles/decoding-swift-types-that-require-additional-data) — Article · Topics: Foundation & Data Formats · Swift
  **NeKI brief:** Shows how CodableWithConfiguration injects required data while decoding Swift types, without optionals or decoding-only wrapper types. Use it for configuration-dependent models whose inputs are unavailable in the encoded payload.
- [Meet the Inspector View in SwiftUI](https://serialcoder.dev/text-tutorials/swiftui/meet-the-inspector-view-in-swiftui) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Examines Meet the Inspector View in SwiftUI, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [NotificationCenter.Message: A New Concurrency-Safe Notification Experience in Swift 6.2](https://fatbobman.com/en/posts/notificationcentermessage-a-new-concurrency-safe-notification-experience-in-swift-62) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Introduces Swift 6.2’s concurrency-safe NotificationCenter.Message APIs for typed notifications. Use it to replace loosely typed broadcasts and make notification payloads, isolation, and observer handling explicit.
- [Announcing the Android Workgroup](https://forums.swift.org/t/announcing-the-android-workgroup/80666) — Article · Topics: Cross-Platform & Web · Swift · Testing
  **NeKI brief:** Introduces the Swift Android workgroup. Useful for following Swift’s cross-platform coordination and understanding how ecosystem work affects Android support and package authors.
- [Why Liquid Glass Is Making Cross‑Platform Developers Rethink Flutter](https://ohmyswift.com/blog/2025/06/28/why-liquid-glass-is-making-developers-rethink-flutter) — Article · Topics: Cross-Platform & Web · Liquid Glass · Swift
  **NeKI brief:** Explains Why Liquid Glass Is Making Developers Rethink Flutter, connecting the underlying Apple-platform mechanism to implementation choices and practical trade-offs that Swift developers can evaluate.
- [Grouping Liquid Glass Components Using glassEffectUnion](https://www.donnywals.com/grouping-liquid-glass-components-using-glasseffectunion-on-ios-26) — Article · Topics: Liquid Glass
  **NeKI brief:** Explains glassEffectUnion for combining multiple Liquid Glass components into one connected visual shape on iOS 26. Follow it when grouped controls should read as a single surface while retaining separate layout, interaction, and accessibility semantics.
- [GitProbe](https://github.com/git-probe/gitprobe) — Source repository · Topics: Developer Tools
  **NeKI brief:** GitProbe changes a GitHub URL into an LLM-friendly codebase view, emphasizing structure discovery before code inspection. Useful for agent-assisted repository orientation when a full clone or broad file dump is unnecessary.
- [Machine Learning Q and AI](https://sebastianraschka.com/books/ml-q-and-ai) — Article · Topics: AI Development
  **NeKI brief:** Reviews Machine Learning Q and AI. Useful as a focused reference for evaluating the described workflow or technology, while validating current platform behavior and project-specific constraints against primary documentation.

## [Issue 220](https://thosewhoswift.substack.com/p/those-who-swift-issue-220)

- Published: `2025-06-25`

**Topics:** Concurrency · Developer Community & Business · Objective-C & Cocoa · Swift · Swift Package Manager · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 220 · Weekly note ✏️

**Selected links:**
- [Reverse‑Engineering Xcode’s Coding Intelligence Prompt](https://peterfriese.dev/blog/2025/reveng-xcode-coding-intelligence) — Article · Topics: AI Development · Objective-C & Cocoa · Xcode
  **NeKI brief:** Inspects Xcode's Coding Intelligence prompt to show how project context and instructions shape generated code. The reverse-engineering perspective helps teams reason about agent inputs and reproducibility while avoiding assumptions about undocumented internals.
- [Rewriting a 12 Year Old Objective-C iOS App with Claude Code](https://twocentstudios.com/2025/06/22/vinylogue-swift-rewrite) — Article · Topics: Objective-C & Cocoa · Performance · Swift
  **NeKI brief:** Examines Rewriting a 12 Year Old Objective-C iOS App with Claude Code, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Create a Swift Package from Your SwiftUI Project](https://www.youtube.com/watch?v=_KYc2wJVIDE) — Video · Topics: Swift · Swift Package Manager · SwiftUI
  **NeKI brief:** Converts an SF Symbol picker from a SwiftUI project into a reusable multiplatform Swift package. The walkthrough covers access control, platform differences, GitHub publication, version tags, and consuming package updates.
- [See how it works](https://www.revenuecat.com/docs/tools/paywalls-v2) — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **NeKI brief:** Documents RevenueCat Paywalls 2 tooling for configuring and presenting subscription paywalls. Use it to inspect templates, purchase flows, and customization boundaries before integrating monetization into an app.
- [Overlapping Views in SwiftUI with zIndex](https://serialcoder.dev/text-tutorials/swiftui/overlapping-views-in-swiftui-with-zindex) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates overlapping SwiftUI views with zIndex and stack composition. Useful for cards, badges, and layered controls where rendering order and hit testing must stay predictable.
- [The Evolution of Mobile CI: Navigating the Shift to Infrastructure‑as‑a‑Service](https://tuist.dev/blog/2025/06/18/mobile-ci) — Article · Topics: CI/CD & Automation · Developer Tools
  **NeKI brief:** Describes the evolution of mobile CI toward infrastructure services. Useful for comparing reproducibility, scaling, and operational ownership when designing an iOS build pipeline.
- [Exploring a New Visual Language: Liquid Glass](https://www.createwithswift.com/exploring-a-new-visual-language-liquid-glass) — Article · Topics: Apple Platform Ecosystem · Liquid Glass · Swift
  **NeKI brief:** Explores Liquid Glass as a new Apple visual language. Use it when evaluating material, hierarchy, and interaction changes before adapting an existing interface to the system design.
- [What Is @concurrent in Swift 6.2?](https://www.donnywals.com/what-is-concurrent-in-swift-6-2) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Introduces the @concurrent attribute in Swift 6.2 and its relationship to actor isolation and explicitly concurrent execution. Use it when reviewing performance-sensitive code and deciding where opt-in parallel work is safe without weakening data-race guarantees.
- [Memory Efficiency in iOS: Reducing footprint and beyond](https://open.substack.com/pub/antongubarenko/p/memory-efficiency-in-ios-reducing?r=21t43r&showWelcomeOnShare=false) — Article · Topics: Architecture · Objective-C & Cocoa
  **NeKI brief:** Examines memory efficiency in iOS. Useful for connecting allocation, object lifetime, and workload measurement to practical footprint reduction rather than optimizing by guesswork.
- [SwiftUI Map Breaks UINavigationBarAppearance](https://www.neilmacy.co.uk/blog/swiftui-map-breaks-uinavigationbarappearance) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Diagnoses SwiftUI Map interaction with UINavigationBarAppearance. Useful for identifying framework ownership conflicts and designing appearance configuration that remains stable across container transitions.

## [Issue 219](https://thosewhoswift.substack.com/p/those-who-swift-issue-219)

- Published: `2025-06-19`

**Topics:** Apple Platform Ecosystem · Graphics, Media & Games · Liquid Glass · Swift · SwiftUI · Xcode

**Sections:** Those Who Swift · Those Who Swift - Issue 219 · Weekly note ✏️

**Selected links:**
- [What’s New in SwiftUI After WWDC25](https://swiftwithmajid.com/2025/06/10/what-is-new-in-swiftui-after-wwdc25) — Article · Topics: Apple Platform Ecosystem · Swift · SwiftUI
  **NeKI brief:** Summarizes post-WWDC 2025 SwiftUI changes in one implementation-oriented overview. Use it to triage adoption opportunities across layout, rendering, and system integration before following specific APIs into primary documentation.
- [WebView Is Finally Coming to SwiftUI](https://danielsaidi.com/blog/2025/06/10/webview-is-finally-coming-to-swiftui) — Article · Topics: Swift · Swift Package Manager · SwiftUI
  **NeKI brief:** Discusses the emerging native SwiftUI web-view direction and its implications for replacing representable wrappers. Useful for migration planning, while verifying availability and behavior against the target SDK.
- [Bringing On‑Device AI to Your App Using Apple’s Foundation Models](https://dimillian.medium.com/bringing-on-device-ai-to-your-app-using-apples-foundation-models-8a1df297eeaa) — Article · Topics: AI Development · Foundation & Data Formats · Swift
  **NeKI brief:** Discusses Bringing On-Device AI to your app: Using Apple's Foundation Models in a public developer resource. Use it to compare the author's concrete workflow and trade-offs with your project constraints, and verify any platform-specific claims against current primary documentation.
- [See how it works](https://www.revenuecat.com/docs/tools/paywalls-v2) — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **NeKI brief:** Documents RevenueCat Paywalls 2 tooling for configuring and presenting subscription paywalls. Use it to inspect templates, purchase flows, and customization boundaries before integrating monetization into an app.
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
- [Manus – AI Video Generation is Now Live](https://manus.im/app) — Article · Topics: AI Development · Graphics, Media & Games
  **NeKI brief:** Introduces Manus as an AI video-generation product. Useful for product capability context, not as a technical Apple-platform source.
- [WWDC25: Highlights as an iOS Developer](https://www.youtube.com/watch?v=__RoIeqfrSY) — Video · Topics: Apple Platform Ecosystem · Objective-C & Cocoa
  **NeKI brief:** Reviews WWDC25: Highlights as an iOS Developer. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.

## [Issue 217](https://thosewhoswift.substack.com/p/those-who-swift-issue-217)

- Published: `2025-06-18`

**Topics:** App Intents & System Surfaces · Apple Platform Ecosystem · Graphics, Media & Games · Security & Privacy · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 217 · Weekly note ✏️

**Selected links:**
- [Quick Guide on Toolbars in SwiftUI](https://tanaschita.com/swiftui-toolbars-guide) — Article · Topics: Hardware & Devices · Swift · SwiftUI
  **NeKI brief:** Surveys SwiftUI toolbar placement, roles, and item composition across platforms. Useful for avoiding platform-specific placement surprises and keeping actions discoverable in navigation bars.
- [Integrating App Intents with Control Action](https://www.createwithswift.com/integrating-app-intents-with-control-action) — Article · Topics: App Intents & System Surfaces · Swift · SwiftUI
  **NeKI brief:** Shows how to expose an app operation through App Intents and Control Action for system surfaces. Use it when connecting an app's domain action to Control Center or other integrations while keeping intent parameters, authorization, and state updates explicit.
- [See how it works](https://www.revenuecat.com/docs/tools/paywalls-v2) — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **NeKI brief:** Documents RevenueCat Paywalls 2 tooling for configuring and presenting subscription paywalls. Use it to inspect templates, purchase flows, and customization boundaries before integrating monetization into an app.
- [Tips and Tricks for When Using SwiftUI’s ViewBuilder](https://www.swiftbysundell.com/articles/swiftui-viewbuilder-tips-and-tricks) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Collects ViewBuilder techniques for conditional composition, custom containers, and readable APIs. Useful when designing result-builder-based components without hiding state or type constraints.
- [The Future of Design in an AI-Driven World](https://www.createwithswift.com/the-future-of-design-in-an-ai-driven-world) — Article · Topics: AI Development · Swift
  **NeKI brief:** Discusses how AI changes product and interface design responsibilities, including generated output, iteration speed, and human judgment. Useful as a strategic prompt when defining an AI-assisted design process that protects usability, authorship, and coherent product intent.
- [Swift at Apple: Migrating the Password Monitoring Service from Java](https://www.swift.org/blog/swift-at-apple-migrating-the-password-monitoring-service-from-java) — Article · Topics: Performance · Security & Privacy · Swift
  **NeKI brief:** Describes Apple's migration of a password-monitoring service from Java to Swift, including server-side concurrency and operational considerations. Useful as a production case study for Swift beyond client applications.
- [Task Closure Lifecycle in Swift Explained (vs Regular Closures)](https://www.youtube.com/watch?v=_0r7VL69l7I) — Video · Topics: Concurrency · Graphics, Media & Games · Swift
  **NeKI brief:** Reviews Task Closure Lifecycle in Swift Explained (vs Regular Closures). Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Bandit - Online Security (or Not) Game](https://overthewire.org/wargames/bandit/bandit0.html) — Article · Topics: Cross-Platform & Web · Graphics, Media & Games · Security & Privacy
  **NeKI brief:** Provides the Bandit security wargame. Useful for learning command-line security concepts through progressive exercises, while keeping its intentionally vulnerable environment separate from production systems.
- [Unique Values in Swift: Removing Duplicates from an Array](https://www.avanderlee.com/swift/unique-values-removing-duplicates-array) — Article · Topics: Swift
  **NeKI brief:** Compares duplicate removal by Set conversion with order-preserving approaches, including their performance and Hashable requirements. The trade-off matters when uniqueness must be retained without silently changing collection order.
- [Art of the State](https://www.scottberrevoets.com/2025/06/02/art-of-the-state) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Reviews Art of the State. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Bezel for Mac](https://nonstrict.eu/bezel) — Article · Topics: Spatial Computing
  **NeKI brief:** Profiles Bezel, a macOS utility for displaying iOS device frames around screenshots and recordings. It is useful when preparing device-specific visuals for App Store listings, documentation, or review material.

## [Issue 195](https://thosewhoswift.substack.com/p/those-who-swift-issue-195)

- Published: `2025-06-18`

**Topics:** Developer Community & Business · Spatial Computing · Swift · SwiftUI · Testing · Xcode

**Sections:** Those Who Swift · Those Who Swift - Issue 195 · Swift Around the Web

**Selected links:**
- [Getting started with UI Testing for SwiftUI](https://tanaschita.com/testing-ui-swiftui-xctest-framework) — Article · Topics: Swift · SwiftUI · Testing
  **NeKI brief:** Demonstrates UI testing SwiftUI applications with XCTest, including accessibility-driven queries and interaction assertions. Useful for testing user-visible behavior without coupling tests to implementation details.
- [Essential xcodebuild Commands for iOS Developers](https://medium.com/@awasthi027.ashish/essential-xcodebuild-commands-for-ios-developers-9ff101783ce2) — Article · Topics: CI/CD & Automation · Objective-C & Cocoa · Xcode
  **NeKI brief:** Examines Essential xcodebuild Commands for iOS Developers, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Learn Swift with Easy-to-Follow Code Examples](https://www.avanderlee.com/swift/swift-tutorials-learn-swift-code-examples) — Tutorial · Topics: Concurrency · Swift · Testing
  **NeKI brief:** Organizes Swift learning around language fundamentals, testing, concurrency, and UI examples, linking concepts to progressively larger exercises. The index is useful for routing a learner to the next missing prerequisite rather than repeating beginner material.
- [Adjust the intensity of colors in SwiftUI views](https://nilcoalescing.com/blog/AdjustTheIntensityOfColorsInSwiftUIViews) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Adjusts SwiftUI color intensity with platform-aware rendering controls. Use it when a design needs subtle emphasis changes without replacing semantic colors with fixed, inaccessible values.
- [Exploring AI: Cosine Similarity for RAG using Accelerate and Swift](https://www.rudrank.com/exploring-ai-cosine-similarity-rag-accelerate-swift) — Article · Topics: AI Development · Swift
  **NeKI brief:** Uses cosine similarity and Accelerate for RAG in Swift. Useful for connecting vector math, embedding search, and performance considerations in an Apple-platform retrieval pipeline.
- [Why Certain View Modifiers in Swift 6 Cannot Use the @State Property](https://fatbobman.com/en/posts/why-certain-view-modifiers-in-swift-6-cannot-usethe-state-property) — Article · Topics: Concurrency · Swift · SwiftUI
  **NeKI brief:** Explains why Swift 6’s stricter concurrency and MainActor rules reject @State in some SwiftUI view modifiers. Use it to align modifier isolation and resolve issues in alignmentGuide or scrollTransition code.
- [Reading and displaying Genmoji in non-rich text formatted data context](https://www.createwithswift.com/reading-and-displaying-genmoji-in-non-rich-text-formatted-data-context) — Article · Topics: Swift
  **NeKI brief:** Shows how to read and display generated emoji in contexts that do not support rich text. Use it when preserving Genmoji content across plain strings, storage, and custom rendering.
- [Finding unused code with Periphery](https://adamwulf.me/2024/12/finding-unused-code-with-periphery) — Article · Topics: Swift
  **NeKI brief:** Presents Finding unused code with Periphery, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [iOS Technical Interview Guide](https://datafoxsoftware.gumroad.com/l/iostechinterviewsample) — Article · Topics: Swift
  **NeKI brief:** Offers a paid iOS interview guide. Useful as career material, but not as a primary technical reading source for the index.
- [Creating a SwiftUI text view with tappable links](https://danielsaidi.com/blog/2024/12/18/creating-a-swiftui-text-view-with-tappable-links) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Presents Creating a SwiftUI text view with tappable links, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [What’s new for enterprise in visionOS 2](https://support.apple.com/en-us/121160) — Article
  **NeKI brief:** Reviews What’s new for enterprise in visionOS 2. Useful as a focused reference for evaluating the described workflow or technology, while validating current platform behavior and project-specific constraints against primary documentation.

## [Issue 218](https://thosewhoswift.substack.com/p/those-who-swift-issue-218)

- Published: `2025-06-11`

**Topics:** AI Development · App Distribution & Store Operations · Apple Platform Ecosystem · Hardware & Devices · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 218 · Weekly note ✏️

**Selected links:**
- [Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [Using AI and Cursor to Localize Xcode String Catalogs](https://danielsaidi.com/blog/2025/06/08/using-ai-and-cursor-to-localize-xcode-string-catalogs) — Article · Topics: AI Development · Localization · Xcode
  **NeKI brief:** Examines Using AI and Cursor to Localize Xcode String Catalogs, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [SwiftUI Keyboard Toolbar Buttons](https://tanaschita.com/swiftui-keyboard-buttons) — Article · Topics: Hardware & Devices · Swift · SwiftUI
  **NeKI brief:** Explains adding keyboard toolbar buttons to SwiftUI input flows and coordinating focus with dismissal or navigation actions. Use it when forms need explicit keyboard controls that behave consistently across fields, platforms, and accessibility interaction modes.
- [Sharing Content in SwiftUI with ShareLink](https://serialcoder.dev/text-tutorials/swiftui/sharing-content-in-swiftui-with-sharelink) — Tutorial · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Examines Sharing Content in SwiftUI with ShareLink, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [How to Make Zoom Transition Animation in iOS 18](https://onmyway133.com/posts/how-to-make-zoom-transition-animation-in-ios-18) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines How to Make Zoom Transition Animation in iOS 18, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [The Prompt Engineering Playbook for Developers](https://addyo.substack.com/p/the-prompt-engineering-playbook-for) — Article · Topics: AI Development
  **NeKI brief:** Presents a prompt-engineering playbook for developers. Useful for structuring coding-agent requests, separating context from constraints, and evaluating generated changes instead of treating prompts as informal instructions.
- [What It’s Like Attending WWDC25 at Apple Park](https://www.youtube.com/watch?v=66W2-H1xxnY) — Video · Topics: Apple Platform Ecosystem · Personal Essays
  **NeKI brief:** Reviews What It’s Like Attending WWDC25 at Apple Park. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Get Paid While You Sleep](https://www.tiagohenriques.dev/blog/get-paid-while-you-sleep) — Article
  **NeKI brief:** Reviews Get Paid While You Sleep. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Creating Animation Annotations for Custom SF Symbols](https://www.createwithswift.com/creating-animation-annotations-for-custom-sf-symbols) — Article · Topics: Swift
  **NeKI brief:** Explains adding animation annotations to custom SF Symbols. Use it when extending symbol assets with motion while keeping the animation metadata compatible with the SF Symbols toolchain.

## [Issue 216](https://thosewhoswift.substack.com/p/those-who-swift-issue-216)

- Published: `2025-05-28`

**Topics:** Accessibility · Architecture · Graphics, Media & Games · Swift · SwiftUI · Xcode

**Sections:** Those Who Swift · Those Who Swift - Issue 216 · Weekly note ✏️

**Selected links:**
- [Creating Xcode Source Editor Extensions](https://www.createwithswift.com/creating-xcode-source-editor-extensions) — Tutorial · Topics: Swift · SwiftUI · Xcode
  **NeKI brief:** Walks through developing and distributing Xcode source editor extensions. Use it to add focused editor automation and understand the packaging, command, and distribution requirements.
- [See how it works](https://www.revenuecat.com/docs/tools/paywalls-v2) — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **NeKI brief:** Documents RevenueCat Paywalls 2 tooling for configuring and presenting subscription paywalls. Use it to inspect templates, purchase flows, and customization boundaries before integrating monetization into an app.
- [Understanding SwiftUI’s ViewThatFits Container](https://tanaschita.com/swiftui-viewthatfits-container) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains how ViewThatFits selects the first SwiftUI view that fits available space. Use it to build adaptive layouts that gracefully switch between alternative compositions at different widths.
- [Creating Shapes Using Path in the SwiftUI Canvas View](https://www.createwithswift.com/creating-shapes-using-path-in-the-swiftui-canvas-view) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates drawing custom shapes with Path inside SwiftUI Canvas. Follow it when rendering vector geometry efficiently or building bespoke illustrations, while separating coordinate calculations, styling, and drawing state from the surrounding view hierarchy.
- [Microapps Architecture in Swift: Scaling](https://swiftwithmajid.com/2025/05/27/microapps-architecture-in-swift-scaling) — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **NeKI brief:** Discusses scaling a Swift microapps architecture through modular feature boundaries. Use it when a growing app needs independently developed flows without turning every module dependency into global coupling.
- [Making Your iOS App More Accessible with Dynamic Type](https://codakuma.com/dynamic-type) — Article · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Demonstrates Dynamic Type accessibility in an iOS app. Useful for testing text scaling, layout resilience, and readable control composition instead of treating accessibility as a final font-size adjustment.
- [SwiftUI Youtube Web Player](https://www.youtube.com/watch?v=eBjzQ1NCXQ4) — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Reviews SwiftUI Youtube Web Player. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Building a Dev Tool](https://dasdom.dev/building-a-dev-tool) — Article · Topics: Hardware & Devices
  **NeKI brief:** Builds a development tool and discusses its implementation path. Useful as a focused example for evaluating tooling UX, local workflows, and the boundary between an app feature and a developer utility.
- [Reading Piped Input in Swift Executables](https://swifttoolkit.dev/posts/pipe) — Tutorial · Topics: Swift
  **NeKI brief:** Explains reading piped input in Swift executables. Useful for building command-line tools that compose with Unix pipelines while keeping argument parsing, streaming, and termination behavior explicit.
- [Forming an Opinion on SwiftUI Forms](https://captainswiftui.substack.com/p/forming-an-opinion-on-swiftui-forms) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Discusses design opinions and trade-offs around SwiftUI Forms. Useful for reviewing form structure, platform behavior, and when default controls should be adapted or replaced.
- [Google AI Studio’s new Gen Media](https://aistudio.google.com/gen-media) — Article · Topics: AI Development · Graphics, Media & Games
  **NeKI brief:** Introduces Google AI Studio’s generative-media capability. Useful for assessing AI asset workflows and their product boundaries before integrating generated media into an application.
- [Complexity Part 7: Organisation](https://dmtopolog.com/complexity-7-organisation) — Article
  **NeKI brief:** Examines organizational sources of complexity. Useful for relating team structure, ownership, and communication paths to the maintenance behavior of a software system.

## [Issue 215](https://thosewhoswift.substack.com/p/those-who-swift-issue-215)

- Published: `2025-05-21`

**Topics:** App Distribution & Store Operations · Architecture · Graphics, Media & Games · Swift · SwiftUI · Testing

**Sections:** Those Who Swift · Those Who Swift - Issue 215 · Weekly note ✏️

**Selected links:**
- [Ultimate Guide to Dependency Injection for Modular iOS Apps](https://swiftandmemes.com/ultimate-guide-to-dependency-injection-for-modular-ios-apps) — Article · Topics: Architecture · Dependency Injection · Swift
  **NeKI brief:** Discusses Dependency Injection for Modular iOS Apps in a public developer resource. Use it to compare the author's concrete workflow and trade-offs with your project constraints, and verify any platform-specific claims against current primary documentation.
- [Change a Map Viewpoint with MapKit](https://www.createwithswift.com/change-a-map-viewpoint-with-mapkit) — Tutorial · Topics: Graphics, Media & Games · Maps & Location · Swift
  **NeKI brief:** Shows changing a MapKit map viewpoint programmatically in SwiftUI, including camera positioning and state-driven updates. Useful for fitting maps to a selection or route while keeping user interaction and app-driven camera changes coordinated.
- [Should You Use Network Connectivity Checks in Swift?](https://www.donnywals.com/should-you-use-network-connectivity-checks-in-swift) — Article · Topics: Product Design · Swift
  **NeKI brief:** Examines whether explicit network connectivity checks are useful in Swift apps. Use it to distinguish reachability hints from actual request outcomes and avoid blocking networking on unreliable preflight state.
- [Getting Started with Unit Testing for iOS Development in Swift](https://www.youtube.com/watch?v=CsuUwdoVwyw) — Video · Topics: Swift · Testing
  **NeKI brief:** Introduces unit testing in an Xcode 16 sample app, then strengthens the tests with edge cases, clearer naming, and less brittle assertions. Useful for seeing how an initial test evolves toward maintainable behavioral coverage.
- [Watch here.](https://youtu.be/CsuUwdoVwyw) — Video · Topics: Swift · Testing
  **NeKI brief:** Introduces unit testing in an Xcode 16 sample app, then strengthens the tests with edge cases, clearer naming, and less brittle assertions. Useful for seeing how an initial test evolves toward maintainable behavioral coverage.
- [The Evolution of Native Engineering at Tripadvisor: Part 1](https://medium.com/tripadvisor/the-evolution-of-native-engineering-at-tripadvisor-part-1-577cc0e36ec8) — Article · Topics: Architecture · Composable Architecture · Objective-C & Cocoa
  **NeKI brief:** Traces Tripadvisor's evolution of native mobile engineering and organizational architecture. Useful as large-team context for evaluating ownership, platform investment, and migration strategy alongside SwiftUI-specific decisions.
- [How to set up analytics for iOS in Swift](https://go.posthog.com/tws-may22) — Article · Topics: Swift
  **NeKI brief:** Explains setting up analytics for iOS in Swift. Useful for reviewing event instrumentation, lifecycle placement, and the distinction between product metrics and diagnostic logging.
- [Exploring Creative Coding with Swift and SwiftUI](https://www.createwithswift.com/exploring-creative-coding-with-swift-and-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explores creative coding with Swift and SwiftUI through layered computational art techniques. Use it to connect declarative view composition with procedural visuals and interactive experimentation.
- [Complexity Part 6: Human Nature](https://dmtopolog.com/complexity-6-human-nature) — Article
  **NeKI brief:** Connects human behavior with software complexity. Useful for recognizing organizational and cognitive constraints that technical structure alone cannot eliminate.

## [Issue 214](https://thosewhoswift.substack.com/p/those-who-swift-issue-214)

- Published: `2025-05-15`

**Topics:** AI Development · App Intents & System Surfaces · Security & Privacy · Swift · SwiftUI · Testing

**Sections:** Those Who Swift · Those Who Swift - Issue 214 · Weekly note ✏️

**Selected links:**
- [Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [Using Model Context Protocol in iOS Apps](https://www.artemnovichkov.com/blog/using-model-context-protocol-in-ios-apps) — Article · Topics: AI Development · Swift · SwiftUI
  **NeKI brief:** Artem continues exploring the Model Context Protocol (MCP) to facilitate interaction between AI models and external tools or data sources, this time showing how to access HealthKit data through the Claude API.
- [Building a Serial Task Executor in Swift](https://iosdevlibrary.com/building-a-serial-task-executor-in-swift) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Builds a serial task executor in Swift for ordering asynchronous work. Use it when a feature needs one-at-a-time execution, checking cancellation, failure propagation, fairness, and actor isolation instead of relying on incidental task ordering.
- [Customizing an App Intent](https://www.createwithswift.com/customizing-an-app-intent) — Article · Topics: App Intents & System Surfaces · Swift
  **NeKI brief:** Shows how to customize App Intents with parameters and dialogs in SwiftUI apps. Use it when exposing app actions to system surfaces while keeping user input and confirmation meaningful.
- [A Tale of Two Custom Container APIs](https://open.substack.com/pub/captainswiftui/p/a-tale-of-two-custom-container-apis) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines A Tale of Two Custom Container APIs, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Using Core Motion Within a SwiftUI Application](https://www.createwithswift.com/using-core-motion-within-a-swiftui-application) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Introduces using Core Motion data from a SwiftUI application, including manager ownership and publishing sensor updates. Use it when building motion-aware interfaces and deciding how to handle permissions, update cadence, lifecycle, and main-thread UI delivery.
- [Complexity #5: Interfaces](https://dmtopolog.com/complexity-5-interfaces) — Article · Topics: Swift
  **NeKI brief:** Explains interfaces as a boundary in complex systems. Useful for reviewing contracts, dependencies, and change propagation across modules or services.
- [What's New in Swift 6.2](https://www.hackingwithswift.com/articles/277/whats-new-in-swift-6-2) — Article · Topics: Swift · Testing
  **NeKI brief:** Summarizes Swift 6.2 additions and concurrency ergonomics, highlighting practical changes for existing projects. Useful for planning an incremental toolchain update and targeted experiments.
- [A Privacy Mechanism That Backfired](https://rambo.codes/posts/2025-05-12-a-privacy-mechanism-that-backfired) — Article · Topics: Security & Privacy
  **NeKI brief:** Analyzes a privacy mechanism that backfired. Useful for reviewing threat models, user expectations, and the gap between intended protection and observable system behavior.
- [Apple’s Widget Backdoor](https://www.youtube.com/watch?v=NdJ_y1c_j_I) — Video
  **NeKI brief:** Reviews Apple’s Widget Backdoor. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.

## [Issue 213](https://thosewhoswift.substack.com/p/those-who-swift-issue-213)

- Published: `2025-05-07`

**Topics:** App Services & Extensions · Dependency Injection · Graphics, Media & Games · Swift · Swift Package Manager · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 213 · Weekly note ✏️

**Selected links:**
- [SwiftUI: How to Use Custom Fonts, Colours, and Images in a Swift Package](https://dev.jeremygale.com/swiftui-how-to-use-custom-fonts-colours-and-images-in-a-swift-package) — Article · Topics: Swift · Swift Package Manager · SwiftUI
  **NeKI brief:** Examines SwiftUI: How to Use Custom Fonts, Colours, and Images in a Swift Package, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Synthesizing Text into Speech in SwiftUI](https://www.createwithswift.com/synthesizing-text-into-speech) — Tutorial · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Demonstrates turning text input into spoken audio with AVFoundation in SwiftUI. Use it to design speech synthesis flows that separate text state, utterance configuration, and playback control.
- [Implementing Live Activities in a SwiftUI App](https://www.createwithswift.com/implementing-live-activities-in-a-swiftui-app) — Tutorial · Topics: App Services & Extensions · Swift · SwiftUI
  **NeKI brief:** Walks through implementing Live Activities in a SwiftUI app, from ActivityKit attributes and updates to the visible presentation. Useful for time-sensitive progress or status features that must coordinate app state, push or local updates, and lifecycle expiration.
- [Adding Dependencies to Binary Swift Packages](https://danielsaidi.com/blog/2025/05/02/adding-dependencies-to-binary-swift-packages) — Article · Topics: Dependency Injection · Swift · Swift Package Manager
  **NeKI brief:** Presents Adding dependencies to binary Swift packages, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Product for Engineers: Helping engineers flex their product muscles](https://go.posthog.com/tws-may8) — Article · Topics: Objective-C & Cocoa
  **NeKI brief:** Promotes product-engineering content. Useful as a discovery lead, but the landing page itself is not a focused technical article.
- [Demystifying Picture in Picture on iOS](https://www.artemnovichkov.com/blog/demystifying-picture-in-picture-on-ios) — Article · Topics: Graphics, Media & Games
  **NeKI brief:** Artem provides a practical guide for implementing Picture in Picture (PiP) functionality in iOS apps from setting up a camera feed using UIKit and AVFoundation, configuring the capture session, and enabling PiP mode.
- [SwiftUI View Model Ownership](https://chris.eidhof.nl/post/swiftui-view-model) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Investigates ownership and initialization of a view model created by a SwiftUI view, including the traps around init and state storage. Use it when deciding how a view should create and retain reference-model state.
- [Ten Years Older: Voice Takes Over](https://byla.lt/posts/ten-years-older-voice-takes-over) — Tutorial · Topics: AI Development · Developer Community & Business
  **NeKI brief:** Reflects on voice interaction taking over an older application experience. Useful for considering migration, accessibility, and interaction-design trade-offs in voice-oriented products.
- [Build Your First Apple Multiplatform App](https://www.youtube.com/watch?v=SQmbABVS9d0) — Video
  **NeKI brief:** Reviews Build Your First Apple Multiplatform App. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [What's New in Swift 6.1](https://www.hackingwithswift.com/articles/276/whats-new-in-swift-6-1) — Article · Topics: Swift
  **NeKI brief:** Summarizes Swift 6.1 language and concurrency additions with migration context. Useful as a release index before evaluating compiler diagnostics and standard-library changes in an existing codebase.
- [Why Some Mac Apps Launch Slowly: A Follow-Up](https://lapcatsoftware.com/articles/2025/5/1.html) — Article · Topics: Cross-Platform & Web
  **NeKI brief:** Investigates slow Mac app launch behavior. Useful for separating startup work, system factors, and application initialization when diagnosing launch performance outside iOS.
- [Clippy is Back!](https://felixrieseberg.github.io/clippy) — Article · Topics: Developer Tools
  **NeKI brief:** Clippy is a macOS clipboard manager from Felix Rieseberg. Follow it for a concrete local clipboard-history workflow and compare its retention and privacy behavior with other clipboard utilities.
- [Complexity Part 4: Abstractions](https://dmtopolog.com/complexity-4-abstraction) — Article
  **NeKI brief:** Discusses abstraction as a complexity-management tool. Useful for deciding when an abstraction clarifies a stable concept and when it merely hides changing details.

## [Issue 212](https://thosewhoswift.substack.com/p/those-who-swift-issue-212)

- Published: `2025-04-30`

**Topics:** Developer Community & Business · Developer Tools · Performance · Swift · SwiftUI · Testing

**Sections:** Those Who Swift · Those Who Swift - Issue 212 · Weekly note ✏️

**Selected links:**
- [Using equatable() to Avoid the NavigationLink Pre-Build Pitfall](https://fatbobman.com/en/posts/using-equatable-to-avoid-the-navigationlink-pre-build-pitfall) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Explains how NavigationLink can pre-build destination views and how equatable() can limit unnecessary work. Use it when diagnosing navigation performance and stabilizing expensive destination construction.
- [How to profile a SwiftUI app's performance?](https://www.youtube.com/watch?v=Dyh-ymg-qAo) — Video · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Profiles a SwiftUI app with Instruments to locate unexpected body reevaluations and slow code. The walkthrough covers collecting a representative trace, interpreting redraw behavior, and distinguishing measured bottlenecks from assumptions.
- [SwiftUI Label and Button Style View Modifiers](https://useyourloaf.com/blog/swiftui-label-and-button-style-view-modifiers) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows convenient SwiftUI extensions around Label and Button styles. Use it to centralize repeated control styling without duplicating modifier chains across feature views.
- [Code-talker](https://github.com/HarishChandran3304/TTG) — Source repository · Topics: AI Development · Developer Tools
  **NeKI brief:** Provides a code-talker project repository. Useful for inspecting an implementation directly and evaluating how speech or code presentation is structured in an Apple-platform tool.
- [How a Single Line of Code Could Brick Your iPhone](https://rambo.codes/posts/2025-04-24-how-a-single-line-of-code-could-brick-your-iphone) — Article · Topics: Security & Privacy
  **NeKI brief:** Presents How a Single Line Of Code Could Brick Your iPhone, with practical context for Apple-platform developers evaluating the technique, workflow, or engineering decision described on the page.
- [Keep Downloading with a Background Session](https://williamboles.com/keep-downloading-with-a-background-session) — Article · Topics: Networking
  **NeKI brief:** Explains continuing downloads with a background URLSession. Useful for designing resilient transfers that survive suspension and reconnect correctly through delegate-driven lifecycle events.
- [Swift Design Patterns: Adapter](https://tanaschita.com/swift-design-patterns-adapter) — Article · Topics: Swift
  **NeKI brief:** Demonstrates the Adapter pattern in Swift for integrating third-party or legacy APIs behind clean interfaces. Use it to isolate incompatible contracts and keep application code testable.
- [Make a View Scrollable Only When Needed](https://www.youtube.com/watch?v=KxU1UKEfYH0) — Video · Topics: Testing
  **NeKI brief:** Reviews Make a View Scrollable Only When Needed. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [The Underground Wrapper Scene](https://captainswiftui.substack.com/p/the-underground-wrapper-scene) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Danny explores lesser-known SwiftUI property wrappers beyond the commonly used @State, @Binding, and @ObservedObject, sharing some of his favorites.
- [Qwen3 Release](https://qwenlm.github.io/blog/qwen3) — Article · Topics: Developer Tools · Testing
  **NeKI brief:** Introduces Qwen3. Useful for comparing model capabilities and deployment options while separating release claims from measured behavior in a target application.
- [Complexity Part 3: Problem–Solution Mismatch](https://dmtopolog.com/complexity-3-problem-solution-mismatch) — Article
  **NeKI brief:** Examines mismatches between problems and proposed solutions. Useful for checking whether architecture addresses the actual constraint instead of adding machinery around an incorrectly framed problem.

## [Issue 211](https://thosewhoswift.substack.com/p/those-who-swift-issue-211)

- Published: `2025-04-24`

**Topics:** Concurrency · Core Data · Persistence & Synchronisation · Swift · SwiftUI · Testing

**Sections:** Those Who Swift · Those Who Swift - Issue 211 · Weekly note ✏️

**Selected links:**
- [Is There A Better AsyncButton?](https://captainswiftui.substack.com/p/is-there-a-better-asyncbutton?triedRedirect=true) — Article · Topics: Concurrency · Swift · SwiftUI
  **NeKI brief:** Compares AsyncButton designs for loading, cancellation, and repeated taps in SwiftUI. Useful when standardizing asynchronous action controls and deciding which state transitions belong in the button versus its caller.
- [Why Your SwiftUI App Is Slower Than You Think](https://medium.com/@wesleymatlock/why-your-swiftui-app-is-slower-than-you-think-c3e9bb46174b) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI rendering and scrolling costs behind Why Your SwiftUI App Is Slower Than You Think. Use it to identify identity, layout, and update-frequency risks before measuring regressions with Instruments on representative devices.
- [Building Type-Safe, High-Performance SwiftData/Core Data Models](https://fatbobman.com/en/posts/building-typesafe-highperformance-swiftdata-core-data-models) — Article · Topics: Performance · Persistence & Synchronisation · Swift
  **NeKI brief:** Explores type-safe, high-performance model design across SwiftData and Core Data, with attention to schema choices and query behavior. Use it when shaping a persistence layer that balances compile-time clarity, migration needs, and runtime performance.
- [Swift Testing Challenge: Can You Refactor This?](https://www.mobiledevdiary.com/posts/swift-testing-challange-can-you-refactor-this) — Article · Topics: Concurrency · Swift · Testing
  **NeKI brief:** Examines Swift Testing Challenge: Can You Refactor This?, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Reading Data from HealthKit in a SwiftUI App](https://www.createwithswift.com/reading-data-from-healthkit-in-a-swiftui-app) — Article · Topics: Health Apps · Swift · SwiftUI
  **NeKI brief:** Introduces reading Health app data from a SwiftUI application. Use it to plan HealthKit authorization, query boundaries, and privacy-sensitive presentation of health records.
- [Ensure Visual Accessibility: Supporting Reduced Motion Preferences in SwiftUI](https://www.createwithswift.com/ensure-visual-accessibility-supporting-reduced-motion-preferences-in-swiftui) — Article · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Demonstrates reading the system Reduce Motion preference in SwiftUI and conditionally simplifying or removing animations. The decision preserves state changes while avoiding motion that can trigger discomfort for some users.
- [How SwiftUI Tracks UI Changes With @Observable (Behind the Scenes)](https://www.youtube.com/watch?v=nw3dnrik9vQ) — Video · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Reviews How SwiftUI Tracks UI Changes With @Observable (Behind the Scenes). Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Swift Actors: What Are They For? Basics](https://blog.egesucu.com.tr/swift-actors-what-are-they-for-fd40b4264d9a) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Examines Swift Actors: What Are They For? Basics, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Apple Rebrands Search Ads as Apple Ads](https://searchengineland.com/apple-search-ads-apple-ads-454356) — Article · Topics: App Distribution & Store Operations · Developer Tools · Objective-C & Cocoa
  **NeKI brief:** Reports Apple’s rebranding of Search Ads. Useful for App Store acquisition context, while current campaign behavior requires official documentation.
- [Advice to My Younger Self](https://www.mobilesystemdesign.com/blog/advice-to-younger-self) — Article
  **NeKI brief:** Presents Advice to My Younger Self, with practical context for Apple-platform developers evaluating the technique, workflow, or engineering decision described on the page.
- [UIApplication Delegate Deprecation Coming in iOS 19 SDK](https://lapcatsoftware.com/articles/2025/4/5.html) — Article · Topics: Cross-Platform & Web
  **NeKI brief:** Discusses UIApplication delegate deprecation in the iOS 19 SDK. Useful for planning lifecycle migrations and identifying compatibility boundaries before removing established delegate-based integration.
- [Krea AI Stage Updated](https://www.krea.ai/stage) — Article · Topics: AI Development
  **NeKI brief:** Reviews Krea AI Stage Updated. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Internet OS for Enthusiasts](https://github.com/heyPuter/puter) — Source repository · Topics: Developer Tools
  **NeKI brief:** Provides the Puter internet-OS project source. Useful for examining a browser-oriented application architecture and its integration boundaries instead of relying only on a product overview.

## [Issue 210](https://thosewhoswift.substack.com/p/those-who-swift-issue-210)

- Published: `2025-04-16`

**Topics:** App Intents & System Surfaces · macOS & AppKit · Performance · Persistence & Synchronisation · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 210 · Weekly Note ✏️

**Selected links:**
- [SwiftUI NavigationPath with TabView](https://tanaschita.com/swiftui-navigation-path-with-tabview) — Article · Topics: Navigation & Deep Linking · Swift · SwiftUI
  **NeKI brief:** Uses NavigationPath with TabView to preserve typed navigation state per tab. Use it when deep links and tab switching must restore the correct nested destination.
- [A Guide to the SwiftUI @Environment](https://www.devfright.com/a-guide-to-the-swiftui-environment) — Article · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Provides a practical tour of SwiftUI environment lookup and propagation. Useful for deciding which dependencies should be injected implicitly, how overrides work in previews, and where explicit parameters improve clarity.
- [Using Instruments to Profile a SwiftUI App](https://www.donnywals.com/using-instruments-to-profile-a-swiftui-app) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Profiles a SwiftUI app with Instruments to connect view updates and runtime cost to measured workloads. Useful for replacing assumptions about rendering performance with trace evidence.
- [Make Your App Content Show on Spotlight](https://www.createwithswift.com/make-your-app-content-show-on-spotlight) — Article · Topics: App Intents & System Surfaces · Objective-C & Cocoa · Swift
  **NeKI brief:** Shows how to index app content so it appears in Spotlight, using Apple system search integration and searchable identifiers. Follow it when exposing meaningful records beyond the app while planning updates, deletion, privacy, and deep-link behavior.
- [Crafting Effective SwiftUI ViewModifiers](https://www.youtube.com/watch?v=XU7wdjPCXLw) — Video · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **NeKI brief:** Reviews Crafting Effective SwiftUI ViewModifiers. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Using Swift’s](https://www.swiftbysundell.com/articles/using-defer-within-async-and-throwing-contexts) — Article · Topics: Concurrency · Core Data · Swift
  **NeKI brief:** Explains defer cleanup across async suspension and thrown errors. Use it when file handles, transactions, or temporary state must release reliably without duplicating cleanup paths.
- [Ways to Customize Text Color in SwiftUI](https://nilcoalescing.com/blog/ForegroundColorStyleAndTintInSwiftUI) — Article · Topics: Objective-C & Cocoa · Swift · SwiftUI
  **NeKI brief:** Compares SwiftUI's `foregroundStyle`, `foregroundColor`, `tint`, AttributedString attributes, and text-rendering options. Use it when choosing between semantic hierarchy, control accenting, gradients, and advanced per-run text styling.
- [Complexity Part 1: Low-Level Decisions in Code](https://dmtopolog.com/complexity-1-decisions-in-code) — Article · Topics: Code Quality
  **NeKI brief:** Explores low-level decisions as a source of software complexity. Useful for reviewing how local implementation choices accumulate into system-wide maintenance cost.
- [How to Set up Mobile Session Replay on iOS](https://go.posthog.com/tws-apr17) — Article
  **NeKI brief:** Introduces mobile session replay on iOS. Useful for evaluating user-interaction diagnostics, privacy boundaries, and instrumentation required to reproduce production UI problems.
- [DolphinGemma](https://www.youtube.com/watch?v=T8GdEVVvXyE) — Video
  **NeKI brief:** Reviews DolphinGemma. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.

## [Issue 209](https://thosewhoswift.substack.com/p/those-who-swift-issue-209)

- Published: `2025-04-09`

**Topics:** Concurrency · Hardware & Devices · Persistence & Synchronisation · Swift · SwiftUI · Testing

**Sections:** Those Who Swift · Those Who Swift - Issue 209 · Weekly note ✏️

**Selected links:**
- [Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [Mastering Data Tracking and Notifications in Core Data and SwiftData](https://itnext.io/mastering-data-tracking-and-notifications-in-core-data-and-swiftdata-a21921ebfa9d?source=rss-b8c3000741------2) — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** Examines Mastering Data Tracking and Notifications in Core Data and SwiftData, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Working With The task Modifier In SwiftUI](https://serialcoder.dev/text-tutorials/swiftui/working-with-the-task-modifier-in-swiftui) — Tutorial · Topics: Concurrency · Swift · SwiftUI
  **NeKI brief:** Examines Working With The task Modifier In SwiftUI, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [SwiftUI Keyboard Shortcut Scope](https://useyourloaf.com/blog/swiftui-keyboard-shortcut-scope) — Article · Topics: Hardware & Devices · Swift · SwiftUI
  **NeKI brief:** Configures keyboard shortcut scope in SwiftUI so commands apply only within the intended scene or view hierarchy. Useful for avoiding global shortcuts that conflict across windows or editing contexts.
- [Testing Remote iOS Push Notifications in a Simulator with simctl](https://tanaschita.com/testing-remote-push-notifications-in-ios-simulator) — Article · Topics: App Services & Extensions · Testing · Xcode
  **NeKI brief:** Explains testing remote push notifications in the iOS Simulator with simctl, including preparing payloads and delivering them locally. Useful for repeatable notification QA without waiting on a production provider, while still separating simulator limits from device behavior.
- [SwiftUI - Scratch to Reveal animation - Xcode 16](https://www.youtube.com/watch?v=6h3udYETzDU) — Video · Topics: Swift · SwiftUI · Xcode
  **NeKI brief:** Builds a scratch-to-reveal SwiftUI effect from a mask, Canvas drawing, drag gesture, fading logic, and overlay controls. Useful for understanding how gesture paths can progressively mutate a visual reveal mask.
- [Server-Side Swift… Served From The Client-Side](https://captainswiftui.substack.com/p/server-side-swift-served-from-the) — Article · Topics: Concurrency · Swift · SwiftUI
  **NeKI brief:** Explores serving server-side Swift concepts from a client-side Swift perspective. Useful for understanding where shared language helps and where deployment, networking, and runtime boundaries remain distinct.
- [Say Goodbye to dismiss: A State-Driven Path to More Maintainable SwiftUI](https://fatbobman.com/en/posts/say-goodbye-to-dismiss) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Reframes SwiftUI dismissal as state-driven navigation. Use it when child views imperatively dismiss themselves and ownership of presentation state becomes hard to test or reason about.
- [How to Inspect .ipa Files and Secure Your iOS App from Common Mistakes](https://www.artemnovichkov.com/blog/how-to-inspect-ipa-files) — Article · Topics: Security & Privacy
  **NeKI brief:** In this original article, Artem provides a comprehensive guide on examining the contents of iOS application packages (.ipa files) and highlights common security pitfalls to avoid.
- [How to plan a migration to Swift 6?](https://www.youtube.com/watch?v=YNBkp8L_j5M) — Video · Topics: Swift
  **NeKI brief:** Reviews How to plan a migration to Swift 6?. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Create Flexible Interfaces in SwiftUI](https://www.createwithswift.com/create-flexible-interfaces-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds flexible SwiftUI interfaces that adapt to available space and content. Use it when a layout must remain usable across devices without branching into separate fixed-size view trees.
- [Complexity 0: Introduction](https://dmtopolog.com/complexity-0-introduction) — Article · Topics: Architecture · Objective-C & Cocoa
  **NeKI brief:** Introduces a series on software complexity. Useful for establishing shared vocabulary before diagnosing complexity in a codebase or assuming abstraction alone will reduce it.
- [What’s New in Swift 6.1: TaskGroup Updates, Member Import Visibility & More](https://www.youtube.com/watch?v=rW3dKjQJOBY&t=425s) — Video · Topics: Graphics, Media & Games · Swift
  **NeKI brief:** Reviews What’s New in Swift 6.1: TaskGroup Updates, Member Import Visibility & More. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Structuring Spacing for Scalable Mobile UIs](https://www.mobilesystemdesign.com/blog/design-system-spacing) — Article
  **NeKI brief:** Discusses spacing tokens and rhythm as foundations of a mobile design system. Useful for translating visual rules into reusable SwiftUI layout constants instead of accumulating screen-specific padding values.
- [Learn B-trees and Database Indexes](https://planetscale.com/blog/btrees-and-database-indexes) — Article · Topics: Persistence & Synchronisation
  **NeKI brief:** Explains B-trees and database indexes. Useful for reasoning about lookup complexity, storage layout, and query performance when selecting or diagnosing persistence structures.
- [Llama 4](https://www.llama.com/docs/overview) — Article
  **NeKI brief:** Documents the Llama 4 model family. Useful for comparing model capabilities and deployment options, with suitability requiring independent evaluation on the target workload.

## [Issue 208](https://thosewhoswift.substack.com/p/those-who-swift-issue-208)

- Published: `2025-04-02`

**Topics:** Combine & Reactive Programming · Concurrency · Graphics, Media & Games · Objective-C & Cocoa · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 208 · Weekly note ✏️

**Selected links:**
- [Modern URL Construction in Swift](https://www.swiftbysundell.com/articles/modern-url-construction-in-swift) — Article · Topics: Foundation & Data Formats · Macros & Metaprogramming · Swift
  **NeKI brief:** Builds URLs with modern Foundation components rather than string concatenation. Use it when paths, query items, and percent encoding must remain correct under optional or user-provided values.
- [Swift 6.1 Release](https://www.swift.org/blog/swift-6.1-released) — Article · Topics: Concurrency · Objective-C & Cocoa · Swift
  **NeKI brief:** The community has already shared some excellent insights. If you’re looking to dive deeper, we highly recommend checking out this video by Vincent!
- [Building a Dependency Injection Framework](https://tanaschita.com/dependency-injection-building-lightweight-container) — Article · Topics: Architecture · Dependency Injection · Swift
  **NeKI brief:** Builds a lightweight dependency-injection container in Swift and discusses registration and resolution. Use it to evaluate a small explicit composition mechanism for app services, especially when replacing hidden singletons without introducing a framework-sized abstraction.
- [Detecting Barcodes on an Image with the Vision Framework](https://www.createwithswift.com/detecting-barcodes-on-an-image-with-the-vision-framework) — Article · Topics: Graphics, Media & Games · Objective-C & Cocoa · Swift
  **NeKI brief:** Shows how Vision’s barcode detection API identifies barcodes in images. Use it when implementing image-based scanning and deciding how detection results map into app actions.
- [SwiftUI Grid, LazyVGrid, LazyHGrid Explained with Code Examples](https://www.avanderlee.com/swiftui/grid-lazyvgrid-lazyhgrid-gridviews) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Compares Grid, LazyVGrid, and LazyHGrid layout behavior, column definitions, and lazy rendering. The article helps select a grid based on content size and scrolling direction rather than treating the APIs as interchangeable.
- [Introducing swiftly 1.0](https://www.swift.org/blog/introducing-swiftly_10) — Article · Topics: Developer Career & Practice · Foundation & Data Formats · Swift
  **NeKI brief:** This technical resource covers Swiftly 1.0 as a Swift toolchain manager. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [SwiftUI Craftsmanship: State Management](https://captainswiftui.substack.com/p/swiftui-craftsmanship-state-management) — Article · Topics: Developer Career & Practice · Swift · SwiftUI
  **NeKI brief:** Examines state-management craftsmanship in SwiftUI. Useful for checking ownership, data flow, and observable boundaries before a view hierarchy accumulates implicit dependencies.
- [Does AsyncStream Replace Combine? No.](https://levelup.gitconnected.com/does-asyncstream-replace-combine-a4fc091a8175) — Article · Topics: Combine & Reactive Programming · Concurrency · Developer Tools
  **NeKI brief:** This article covers the boundary between AsyncStream and Combine. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Terminus](https://web.mit.edu/mprat/Public/web/Terminus/Web/main.html) — Article · Topics: Cross-Platform & Web · Developer Tools · Graphics, Media & Games
  **NeKI brief:** Reviews Terminus. Useful as a focused reference for evaluating the described workflow or technology, while validating current platform behavior and project-specific constraints against primary documentation.
- [The first newsletter for product engineers](https://go.posthog.com/tws-mar27) — Article · Topics: Objective-C & Cocoa
  **NeKI brief:** Promotes a product-engineering newsletter. Useful only as a discovery lead; specific implementation claims should be followed to their original technical source.
- [GameShell](https://www.clockworkpi.com/gameshell) — Article · Topics: Developer Tools · Graphics, Media & Games
  **NeKI brief:** Reviews GameShell. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Krea.AI 3D-models Generation](https://www.krea.ai/3d) — Article · Topics: AI Development
  **NeKI brief:** Reviews Krea.AI 3D-models Generation. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.

## [Issue 207](https://thosewhoswift.substack.com/p/those-who-swift-issue-207)

- Published: `2025-03-28`

**Topics:** Concurrency · Developer Tools · Graphics, Media & Games · Performance · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 207 · Weekly note ✏️

**Selected links:**
- [Detecting Body Poses in a Live Video Feed](https://www.createwithswift.com/detecting-body-poses-in-a-live-video-feed) — Tutorial · Topics: Foundation & Data Formats · Graphics, Media & Games · Swift
  **NeKI brief:** Detects body poses from a live video feed with Vision. Use it when real-time camera analysis needs a clear pipeline from captured frames through inference to UI updates.
- [Tracking Down Memory Leaks with Instruments](https://www.youtube.com/watch?v=j8y-LtRV4hM) — Video · Topics: Graphics, Media & Games · Performance · Xcode
  **NeKI brief:** Reproduces an older-iPad crash, enables Malloc Stack Logging, and uses Instruments' Leaks template to trace per-stroke Metal texture allocation. Reusing the texture resolves the memory growth and provides a concrete profiling workflow.
- [Using Proxyman to Intercept and Simulate iPhone App Network Requests](https://fatbobman.com/en/posts/using-proxyman-to-intercept-and-simulate-iphone-app-network-requests) — Article · Topics: Developer Tools · Security & Privacy
  **NeKI brief:** Shows using Proxyman to capture HTTPS traffic, install certificates, map local responses, and mock APIs. Use it to reproduce network scenarios without changing a production server.
- [SwiftUI TabView: Explained with Code Examples](https://www.avanderlee.com/swiftui/tabview-tabbed-views) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains TabView selection, tab items, styles, and state restoration for multi-section SwiftUI apps. The examples are useful for keeping navigation state explicit while adapting presentation across platforms.
- [Modal Presentation Background and Color Scheme in SwiftUI](https://nilcoalescing.com/blog/ModalPresentationBackgroundAndColorSchemeInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows custom backgrounds and explicit color-scheme control for SwiftUI sheets, popovers, and full-screen covers. Use it when modal presentation needs consistent appearance across light and dark environments.
- [ModelActor is Just Weird](https://www.massicotte.org/model-actor) — Article · Topics: Concurrency · Swift · SwiftData
  **NeKI brief:** In this article, Matt shows his journey in understanding how the ModelActor protocol and how Swift Data deals with concurrency in the system.
- [Awaiting Multiple Async Tasks in Swift](https://swiftwithmajid.com/2025/03/24/awaiting-multiple-async-tasks-in-swift) — Article · Topics: Concurrency · Personal Essays · Swift
  **NeKI brief:** Explains Swift async let for concurrently starting multiple child tasks and awaiting their results. Use it when parallel work has fixed structure and needs clear cancellation and error propagation.
- [Adapting Images and Symbols to Dynamic Type Sizes in SwiftUI](https://nilcoalescing.com/blog/AdaptingImagesAndSymbolsToDynamicTypeSizesInSwiftUI) — Article · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Uses Dynamic Type size information to adapt image and symbol sizing alongside text, rather than letting decorative controls become visually disproportionate. The approach is useful when auditing compact layouts at accessibility sizes.
- [The Simple Life(cycle) of a SwiftUI View in 2025](https://captainswiftui.substack.com/p/the-simple-lifecycle-of-a-swiftui) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Danny dives deep into the revisited SwiftUI View Lifecycle, explaining how views behave, update, and clean up in modern SwiftUI.
- [How We Used LLMs to Help Us Find the Perfect Piece of Land for Our Future Home](https://krausefx.com//blog/how-we-used-llms-to-help-us-find-the-perfect-piece-of-land-for-our-future-home) — Article · Topics: AI Development · Objective-C & Cocoa
  **NeKI brief:** Describes using LLMs to search for a property. Useful as an automation case study for tool orchestration and human review boundaries.

## [Issue 206](https://thosewhoswift.substack.com/p/those-who-swift-issue-206)

- Published: `2025-03-19`

**Topics:** AI Development · Core Data · Persistence & Synchronisation · Swift · SwiftData · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 206 · Weekly note ✏️

**Selected links:**
- [Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [SwiftUI: Connect Two Points with Straight Line Segments + Rounded Corners](https://levelup.gitconnected.com/swiftui-connect-two-points-with-straight-line-segments-rounded-corners-dbbad5f27ab4) — Article · Topics: Combine & Reactive Programming · Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI: Connect Two Points with Straight Line Segments + Rounded Corners, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Custom Environment Values in SwiftUI](https://nilcoalescing.com/blog/CustomEnvironmentValuesInSwiftUI) — Article · Topics: Macros & Metaprogramming · Swift · SwiftUI
  **NeKI brief:** Compares the pre-Xcode 16 pattern for defining SwiftUI environment keys with the @Entry macro, then shows how values flow through a view hierarchy.
- [Identifying individual sounds in an audio file](https://www.createwithswift.com/identifying-individual-sounds-in-an-audio-file) — Tutorial · Topics: Swift · SwiftUI
  **NeKI brief:** Identifies individual sounds in audio with Apple's analysis frameworks. Use it when an app must classify or segment recorded media and route time-ranged results into a user-facing workflow.
- [Placing UI Components Within the Safe Area Inset](https://www.createwithswift.com/placing-ui-components-within-the-safe-area-inset) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Uses safeAreaInset to place persistent controls while reserving layout space for content. Useful for bottom actions that should avoid overlap with scrolling content and system regions.
- [Building a MCP Server in Swift](https://adamwulf.me/2025/03/building-a-mcp-server-in-swift) — Article · Topics: AI Development · Swift
  **NeKI brief:** Describes Building a MCP Server in Swift, focusing on practical tool integration and workflow trade-offs. Use it to evaluate reproducibility, trust boundaries, and debugging steps before adopting the approach in an Xcode project.
- [SwiftUI's editMode Environment](https://alexanderweiss.dev/blog/2025-03-16-swiftui-reacting-to-edit-mode) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains SwiftUI’s editMode environment and how views observe editing state. Useful for implementing list editing behavior while keeping state propagation explicit and testable.
- [10 Years of Swift: A decade in review](https://www.youtube.com/watch?v=cHiU-n6fZQ8) — Video · Topics: Graphics, Media & Games · Swift
  **NeKI brief:** Reviews 10 Years of Swift: A decade in review. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Kotlin Multiplatform Documentation](https://kotlinlang.org/docs/multiplatform.html) — Article · Topics: Cross-Platform & Web
  **NeKI brief:** Documents Kotlin Multiplatform and its shared-code model. Useful for comparing cross-platform sharing boundaries with native UI and platform integration requirements in an Apple-platform project.
- [Understanding Existentials and Primary Associated Types in Swift](https://tanaschita.com/swift-existentials) — Article · Topics: Swift
  **NeKI brief:** Explains existentials and primary associated types for protocols with associated types. Use it to choose between existential storage and generic constraints while keeping collections flexible and type-safe.

## [Issue 205](https://thosewhoswift.substack.com/p/those-who-swift-issue-205)

- Published: `2025-03-12`

**Topics:** CI/CD & Automation · Graphics, Media & Games · Persistence & Synchronisation · Swift · SwiftUI · Testing

**Sections:** Those Who Swift · Those Who Swift - Issue 205 · Weekly note ✏️

**Selected links:**
- [Stream’s Swift SDK](https://getstream.io/chat/sdk/ios) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Documents Stream’s iOS chat SDK for adding messaging experiences. Use it to assess ready-made conversation UI, client integration, and customization boundaries before building chat infrastructure yourself.
- [pre-built UI components](https://getstream.io/chat/ui-kit) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Stream's Chat UI Kit supplies prebuilt messaging interface components for iOS. Assess its customization, accessibility, state ownership, and service coupling before choosing it over an in-house chat surface.
- [UserDefaults and Observation in SwiftUI: How to Achieve Precise Responsiveness](https://itnext.io/userdefaults-and-observation-in-swiftui-how-to-achieve-precise-responsiveness-2bd8bda1568e) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Examines UserDefaults and Observation in SwiftUI: How to Achieve Precise Responsiveness, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Animatable Auto-Sized-To-Fit SwiftUI Sheet](https://clive819.github.io/posts/animatable-auto-sized-to-fit-swiftui-sheet) — Article · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** Shows an animatable auto-sized SwiftUI sheet. Useful for coordinating measured content, animation, and presentation state when a sheet should fit changing content without hard-coded detents.
- [Key Considerations Before Using SwiftData](https://fatbobman.com/en/posts/key-considerations-before-using-swiftdata) — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **NeKI brief:** Evaluates SwiftData's practical limits before adoption. Use it when deciding whether its model, migration, query, or synchronization behavior fits a production persistence requirement.
- [Swift Testing Completion Handlers](https://useyourloaf.com/blog/swift-testing-completion-handlers) — Article · Topics: Concurrency · Swift · Testing
  **NeKI brief:** Uses a Core Data persistent-store example to replace XCTest expectations with Swift Testing’s async confirmation, explaining how to await completion-handler callbacks without blocking the test thread.
- [Picker in SwiftUI Explained with Code Examples](https://www.avanderlee.com/swiftui/picker-styles-color) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Demonstrates Picker bindings and style choices such as menu, segmented, wheel, and navigation-link presentations. It connects control style to platform context and option count instead of only changing appearance.
- [Customizing Modal Presentation Background and Color Scheme in SwiftUI](https://nilcoalescing.com/blog/ModalPresentationBackgroundAndColorSchemeInSwiftUI) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows custom backgrounds and explicit color-scheme control for SwiftUI sheets, popovers, and full-screen covers. Use it when modal presentation needs consistent appearance across light and dark environments.
- [Scalable Continuous Integration for iOS | Swift Heroes Talk](https://www.youtube.com/watch?v=gy5ZHcDj4tE) — Video · Topics: CI/CD & Automation · Swift
  **NeKI brief:** Reviews Scalable Continuous Integration for iOS | Swift Heroes Talk. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Rendering Pixel Art with SwiftUI](https://twocentstudios.com/2025/03/10/pixel-art-swift-ui) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Chris explores how to display pixel art crisply in SwiftUI, ensuring sharp edges without unwanted blurring for game assets but also for low-resolution graphics.
- [Start Building with Stream](https://getstream.io/chat/trial) — Article · Topics: Swift
  **NeKI brief:** Explores Free In-App Messaging SDK & UI Kits for iOS/Swift, focusing on stream chat is the easiest way to add messaging to. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.

## [Issue 204](https://thosewhoswift.substack.com/p/those-who-swift-issue-204)

- Published: `2025-03-05`

**Topics:** Graphics, Media & Games · macOS & AppKit · Performance · Swift · SwiftUI · Testing

**Sections:** Those Who Swift · Those Who Swift - Issue 204 · Weekly note ✏️

**Selected links:**
- [Stream’s Swift SDK](https://getstream.io/chat/sdk/ios) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Documents Stream’s iOS chat SDK for adding messaging experiences. Use it to assess ready-made conversation UI, client integration, and customization boundaries before building chat infrastructure yourself.
- [pre-built UI components](https://getstream.io/chat/ui-kit) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Stream's Chat UI Kit supplies prebuilt messaging interface components for iOS. Assess its customization, accessibility, state ownership, and service coupling before choosing it over an in-house chat surface.
- [Simple Modularization Setup for a New App](https://www.manu.show/2025-02-27-simple-modularization-setup) — Article · Topics: Architecture · Swift · Swift Package Manager
  **NeKI brief:** Examines Simple Modularization Setup for a New App, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Custom Lazy List in SwiftUI with Better Performance](https://nilcoalescing.com/blog/CustomLazyListInSwiftUI) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Constructs a custom lazy list to control virtualization and layout beyond List's built-in behavior. Useful when custom scrolling visuals or cell composition require more control than standard list styles provide.
- [SwiftUI Performance - How to use UIKit](https://swiftwithmajid.com/2025/03/04/swiftui-performance-how-to-use-uikit) — Article · Topics: Performance · Swift · SwiftUI
  **NeKI brief:** Explains selectively replacing expensive SwiftUI portions with UIKit when profiling identifies a real rendering bottleneck. Useful as a measured interoperability fallback rather than a default architectural preference.
- [Creating macOS Menu Bar App in SwiftUI](https://clive819.github.io/posts/creating-macos-menu-bar-app-in-swiftui) — Article · Topics: macOS & AppKit · Swift · SwiftUI
  **NeKI brief:** Builds a macOS menu-bar app with SwiftUI. Useful for understanding menu-bar lifecycle, scene configuration, and the platform-specific constraints that differ from a regular windowed app.
- [Detect Focused Window on macOS](https://nilcoalescing.com/blog/DetectFocusedWindowOnMacOS) — Article · Topics: Product Design · Swift · SwiftUI
  **NeKI brief:** Demonstrates detecting macOS window focus with SwiftUI’s appearsActive environment value. Use it to update controls or visuals when a scene becomes active or inactive.
- [Adapting Widgets for Tint Mode and Dark Mode in SwiftUI](https://www.createwithswift.com/adapting-widgets-for-tint-mode-and-dark-mode-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explores widget rendering modes for tint and dark-mode device settings in SwiftUI. Use it to keep widget imagery legible and intentional across system appearance configurations.
- [Detecting Face Landmarks with the Vision Framework](https://www.createwithswift.com/detecting-face-landmarks-with-the-vision-framework) — Article · Topics: Graphics, Media & Games · Swift
  **NeKI brief:** Explains using Vision to detect facial landmarks in images. Use it when mapping eyes, brows, or other features into analysis or camera experiences while handling detection failure.
- [Start Building with Stream](https://getstream.io/chat/trial) — Article · Topics: Swift
  **NeKI brief:** Explores Free In-App Messaging SDK & UI Kits for iOS/Swift, focusing on stream chat is the easiest way to add messaging to. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Safer Swift: How ~Copyable Prevents Hidden Bugs](https://arturgruchala.com/safer-swift-how-copyable-prevents-hidden-bugs) — Article · Topics: Swift
  **NeKI brief:** Explains Safer Swift: How ~Copyable Prevents Hidden Bugs, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Notification Action Buttons with Images in iOS](https://nilcoalescing.com/blog/NotificationActionButtonsWithImages) — Article · Topics: Testing
  **NeKI brief:** Shows adding icons to actionable push-notification buttons with UNNotificationActionIcon. Use it to make notification actions more recognizable while checking platform and asset requirements.
- [MIT Introduction to Deep Learning | 6.S191](https://www.youtube.com/watch?v=alfdI7S6wCY) — Video · Topics: Developer Community & Business · Foundation & Data Formats
  **NeKI brief:** Reviews MIT Introduction to Deep Learning | 6.S191. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.

## [Issue 203](https://thosewhoswift.substack.com/p/those-who-swift-issue-203)

- Published: `2025-02-26`

**Topics:** App Services & Extensions · Developer Community & Business · Maps & Location · Swift · SwiftUI · Testing

**Sections:** Those Who Swift · Those Who Swift - Issue 203 · Weekly note ✏️

**Selected links:**
- [Implementing Look Around with MapKit in SwiftUI](https://www.createwithswift.com/implementing-look-around-with-mapkit-in-swiftui) — Article · Topics: Maps & Location · Swift · SwiftUI
  **NeKI brief:** Demonstrates integrating MapKit Look Around into SwiftUI to present street-level previews for a location. Useful for place-detail experiences that need availability checks, asynchronous scene loading, and graceful fallback when imagery is unavailable.
- [SwiftUI Fundamentals: a deeper look into the framework](https://books.nilcoalescing.com/swiftui-fundamentals) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI Fundamentals: a deeper look into the framework, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Faking Value Semantics with Custom FormatStyles](https://khanlou.com/2025/02/faking-value-semantics-with-custom-formatstyles) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Examines Faking Value Semantics with Custom FormatStyles, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Mastering Images in SwiftUI – Assets, Bundles, Remote URLs & Effects](https://www.youtube.com/watch?v=KnuKc9eICM4) — Video · Topics: Swift · SwiftUI
  **NeKI brief:** Reviews Mastering Images in SwiftUI – Assets, Bundles, Remote URLs & Effects. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Music Recognition with ShazamKit](https://www.artemnovichkov.com/blog/music-recognition-with-shazam-kit) — Article
  **NeKI brief:** Artem shows how to integrate ShazamKit into iOS apps, explaining the setup process, microphone permissions, and implementation of music recognition using SHManagedSession and SHLibrary, along with practical SwiftUI examples for displaying recognized songs.
- [Imperative, Functional, Functional Reactive: Do you know the difference?](https://www.mobiledevdiary.com/posts/imperative-functional-frp) — Article
  **NeKI brief:** Contrasts imperative, functional, and reactive programming. Useful for choosing a style deliberately and explaining how state, transformations, and side effects shape an Apple-platform design.
- [Tapping on Stack Views](https://useyourloaf.com/blog/tapping-on-stack-views) — Article
  **NeKI brief:** Explains why tapping empty space in a SwiftUI stack may not trigger a gesture and how contentShape changes hit testing. Useful for reliable row and card interactions.

## [Issue 202](https://thosewhoswift.substack.com/p/those-who-swift-issue-202)

- Published: `2025-02-19`

**Topics:** App Distribution & Store Operations · Concurrency · Personal Essays · Swift · SwiftUI · Testing

**Sections:** Those Who Swift · Those Who Swift - Issue 202 · Weekly note ✏️

**Selected links:**
- [Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — Source repository · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [Yielding and Debouncing in Swift Concurrency](https://swiftwithmajid.com/2025/02/18/yielding-and-debouncing-in-swift-concurrency) — Article · Topics: Concurrency · Personal Essays · Swift
  **NeKI brief:** Explains yielding and debouncing techniques with Swift concurrency, showing how tasks can cooperate and suppress redundant work. Follow it for search, input, or event pipelines where cancellation, scheduling fairness, and latest-value behavior must be explicit.
- [Enable Multi-Finger Tap Gestures in SwiftUI](https://fatbobman.medium.com/enable-multi-finger-tap-gestures-in-swiftui-2dbfdc5c759c) — Article · Topics: Swift · SwiftUI · UIKit
  **NeKI brief:** Examines Enable Multi-Finger Tap Gestures in SwiftUI, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Adjust the Intensity of Colors in SwiftUI Views](https://nilcoalescing.com/blog/AdjustTheIntensityOfColorsInSwiftUIViews) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Adjusts SwiftUI color intensity with platform-aware rendering controls. Use it when a design needs subtle emphasis changes without replacing semantic colors with fixed, inaccessible values.
- [How to use SceneDelegate in SwiftUI](https://tanaschita.com/swiftui-scenedelegate) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Bridges scene lifecycle behavior into SwiftUI through a scene delegate integration. Useful when an application still needs UIKit lifecycle hooks for notifications, deep links, or window coordination.
- [NSAttributedString: Formatting Rich Text](https://www.swiftyplace.com/blog/nsattributedstring-swift) — Article · Topics: Foundation & Data Formats · Swift
  **NeKI brief:** Explains NSAttributedString formatting in Swift. Useful for constructing rich text while keeping attributes, ranges, and UIKit or SwiftUI rendering boundaries explicit.
- [Introducing gRPC Swift 2](https://www.swift.org/blog/grpc-swift-2) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Introduces gRPC Swift 2. Useful for evaluating generated client/server boundaries, transport choices, and compatibility when adopting gRPC in a Swift service or app.
- [Creating CarPlay apps within a SwiftUI app lifecycle](https://www.createwithswift.com/creating-carplay-apps-within-a-swiftui-app-lifecyle) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains integrating a CarPlay scene into a SwiftUI application's lifecycle and scene configuration. Useful when the phone UI and vehicle experience share models but require distinct connection boundaries.
- [Enabling Interaction with Table View in SwiftUI](https://www.createwithswift.com/enabling-interaction-with-table-view-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows how to enable interaction with table-style content in SwiftUI, bridging row selection or actions into state. Use it when a table needs predictable interaction semantics and you must account for platform differences, identity, and accessibility.
- [Ollama: Running LLMs Locally on Your Mac](https://nshipster.com/ollama) — Article · Topics: AI Development · Objective-C & Cocoa · Personal Essays
  **NeKI brief:** Shows how Ollama runs local language models on a Mac and exposes them to developer workflows without sending prompts to a hosted service. The trade-off is a concrete starting point for evaluating privacy, hardware, and model-quality constraints.
- [Animated Side Menu in SwiftUI](https://www.youtube.com/watch?v=d-2-vuFipVg) — Video · Topics: Swift · SwiftUI
  **NeKI brief:** Reviews Animated Side Menu in SwiftUI. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Extracting structured data from PDFs using Gemini 2.0 and Genkit](https://peterfriese.dev/blog/2025/gemini-genkit-pdf-structured-data) — Article
  **NeKI brief:** Demonstrates extracting structured data from PDFs with Gemini 2.0 and Genkit. Useful for assessing document-ingestion workflows, schema validation, and error handling before integrating model-produced fields into an app's trusted domain model.

## [Issue 201](https://thosewhoswift.substack.com/p/those-who-swift-issue-201)

- Published: `2025-02-12`

**Topics:** Graphics, Media & Games · Localization · Security & Privacy · Swift · SwiftUI · Testing

**Sections:** Those Who Swift · Those Who Swift - Issue 201 · Weekly note ✏️

**Selected links:**
- [Stream’s Swift SDK](https://getstream.io/chat/sdk/ios) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Documents Stream’s iOS chat SDK for adding messaging experiences. Use it to assess ready-made conversation UI, client integration, and customization boundaries before building chat infrastructure yourself.
- [pre-built UI components](https://getstream.io/chat/ui-kit) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Stream's Chat UI Kit supplies prebuilt messaging interface components for iOS. Assess its customization, accessibility, state ownership, and service coupling before choosing it over an in-house chat surface.
- [VS Code extension for Swift update](https://www.swift.org/blog/vscode-swift-2) — Article · Topics: Developer Tools · Swift · Swift Package Manager
  **NeKI brief:** Introduces updates to the VS Code extension for Swift. Follow it when comparing editor workflows, language-server capabilities, and debugging support outside Xcode, while checking the extension and toolchain versions required by a project.
- [Parameterized Tests in Swift: Reducing Boilerplate Code](https://www.avanderlee.com/swift-testing/parameterized-tests-reducing-boilerplate-code) — Article · Topics: Swift · Testing
  **NeKI brief:** Shows how Swift Testing parameterization turns repeated assertions into one @Test with arguments, including custom types and combinations, so edge cases can be expanded without duplicating test functions.
- [Mastering Task Groups in Swift](https://swiftwithmajid.com/2025/02/11/task-cancellation-in-swift-concurrency) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Demonstrates cooperative task cancellation in Swift, including checking cancellation and stopping asynchronous work promptly. Useful for preventing stale network or search results from continuing after a view disappears.
- [Displaying Tabular Data in SwiftUI Using Table View](https://www.createwithswift.com/displaying-tabular-data-in-swiftui-using-table-view) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Introduces SwiftUI Table for representing tabular data. Use it when presenting columns and rows on supported Apple platforms, while considering platform-specific behavior and data identity.
- [SwiftUI Navigation: View If Needed](https://www.joshholtz.com/blog/2025/02/08/swiftui-navigation-view-if-needed) — Article · Topics: CI/CD & Automation · Swift · SwiftUI
  **NeKI brief:** Discusses SwiftUI navigation behavior and when a view is needed. Useful for reviewing navigation structure and avoiding accidental destination creation or state lifetime problems.
- [Start Building with Stream](https://getstream.io/chat/trial) — Article · Topics: Swift
  **NeKI brief:** Explores Free In-App Messaging SDK & UI Kits for iOS/Swift, focusing on stream chat is the easiest way to add messaging to. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Protocols vs Inheritance](https://www.youtube.com/watch?v=i4ItliWjEzk) — Video · Topics: Code Quality · Swift
  **NeKI brief:** Reviews Protocols vs Inheritance. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Personal Component Library](https://mireabot.substack.com/p/how-i-created-a-personal-component) — Article
  **NeKI brief:** Builds a personal component library. Useful for examining reusable SwiftUI design-system structure, component boundaries, and the maintenance cost of shared UI abstractions.

## [Issue 200](https://thosewhoswift.substack.com/p/those-who-swift-issue-200)

- Published: `2025-02-05`

**Topics:** Developer Community & Business · Graphics, Media & Games · Maps & Location · Swift · SwiftUI · Xcode

**Sections:** Those Who Swift · Those Who Swift - Issue 200 · Weekly note ✏️

**Selected links:**
- [Stream’s Swift SDK](https://getstream.io/chat/sdk/ios) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Documents Stream’s iOS chat SDK for adding messaging experiences. Use it to assess ready-made conversation UI, client integration, and customization boundaries before building chat infrastructure yourself.
- [pre-built UI components](https://getstream.io/chat/ui-kit) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Stream's Chat UI Kit supplies prebuilt messaging interface components for iOS. Assess its customization, accessibility, state ownership, and service coupling before choosing it over an in-house chat surface.
- [SwiftUI Image Playground](https://www.youtube.com/watch?v=fjtWpQGs5lU) — Video · Topics: AI Development · Swift · SwiftUI
  **NeKI brief:** Integrates Image Playground into SwiftUI so users can generate images from concepts or an existing source image. The walkthrough covers availability requirements, presentation, generated-image handling, and fallback-aware application structure.
- [Xcode 16: new features to know](https://www.youtube.com/watch?v=Ow0hU6bhiwo) — Video · Topics: Developer Tools · Graphics, Media & Games · Xcode
  **NeKI brief:** Reviews Xcode 16: new features to know. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Drawing Maps with Swift Charts](https://www.artemnovichkov.com/blog/drawing-maps-with-swift-charts) — Article · Topics: Maps & Location · Swift
  **NeKI brief:** Artem shows how developers merge location-based data with the Swift Chart framework to create insightful data visualizations.
- [The Next Chapter in Swift Build Technologies](https://www.swift.org/blog/the-next-chapter-in-swift-build-technologies) — Article · Topics: Performance · Swift
  **NeKI brief:** This commitment led Apple to open-sourcing Swift Build, a build engine that offers a comprehensive set of build rules for constructing Swift projects.
- [SwiftUI Preferences in Swift 6](https://peterfriese.dev/blog/2025/swiftui-preferences-swift6) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Explains SwiftUI Preferences as an upward data channel from child views to ancestors, with Swift 6 examples. It is useful for designing reusable components that report measurements or actions without tight parent-child coupling.
- [Start Building with Stream](https://getstream.io/chat/trial) — Article · Topics: Swift
  **NeKI brief:** Explores Free In-App Messaging SDK & UI Kits for iOS/Swift, focusing on stream chat is the easiest way to add messaging to. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Capture UUID Values with Regex](https://nilcoalescing.com/blog/CaptureUUIDValuesWithRegex) — Article · Topics: Swift
  **NeKI brief:** Uses Swift RegexBuilder to extract and validate UUID values with reusable typed components. Use it when parsing identifiers from user input or untrusted text without ad-hoc string operations.
- [Using SF Symbols in iOS](https://tanaschita.com/ios-sf-symbols) — Article
  **NeKI brief:** Covers SF Symbols in SwiftUI and UIKit, including layers, rendering modes, scaling, and color customization. Use it to keep iconography consistent and adaptable across interfaces.
- [Joining a List of Strings in Swift](https://www.polpiella.dev/join-list-of-strings) — Article · Topics: Swift
  **NeKI brief:** Explains using ListFormatter or formatted instead of joined for natural, localized lists of strings. Use it when composing human-readable sentences that must respect locale grammar and punctuation.

## [Issue 199](https://thosewhoswift.substack.com/p/those-who-swift-issue-199)

- Published: `2025-01-30`

**Topics:** Graphics, Media & Games · Navigation & Deep Linking · Persistence & Synchronisation · Swift · SwiftUI · Testing

**Sections:** Those Who Swift · Those Who Swift - Issue 199 · Weekly note ✏️

**Selected links:**
- [Filtering SwiftData Models Using Enum](https://azamsharp.com/2025/01/23/filtering-swiftdata-models-using-enum.html) — Article · Topics: Cross-Platform & Web · Swift · SwiftData
  **NeKI brief:** Azam explains how to filter SwiftData models using enum values, overcoming query limitations with raw values, while providing code examples and highlighting enums’ benefits.
- [Customizing NavigationStack Title in SwiftUI](https://tanaschita.com/switui-navigationstack-customize-title) — Article · Topics: Navigation & Deep Linking · Swift · SwiftUI
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
- [Task Management in Swift: A 3-Part Series](https://junebash.bearblog.dev/task-management-in-swift-part-1-the-problem) — Article · Topics: Developer Career & Practice · Developer Tools · Swift
  **NeKI brief:** Introduces a Swift task-management series and its motivating problem. Useful for examining how requirements, state, and scheduling concerns are decomposed before implementation.
- [Manual View Orientation Control](https://www.youtube.com/watch?v=9dyOYuv9p2Y) — Video · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Reviews Manual View Orientation Control. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [MapKit + Metal Shaders + H3 (Uber Hex System) + SwiftUI](https://javios.gumroad.com/l/zlnde) — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **NeKI brief:** Combines MapKit, Metal shaders, H3, and SwiftUI in a mapping example. Useful for evaluating geographic visualization architecture and the boundary between map data, GPU effects, and SwiftUI presentation.
- [Download HERE.](https://donnywals.gumroad.com/l/practical-bundle) — Article · Topics: Developer Community & Business
  **NeKI brief:** Routes to a commercial course bundle. Useful as a product lead only, not as technical knowledge-index reading.

## [Issue 198](https://thosewhoswift.substack.com/p/those-who-swift-issue-198)

- Published: `2025-01-23`

**Topics:** Architecture · Macros & Metaprogramming · Objective-C & Cocoa · Swift · SwiftUI · Testing

**Sections:** Those Who Swift · Those Who Swift - Issue 198 · Weekly note ✏️

**Selected links:**
- [SwiftData CRUD Operations with ModelActor](https://brightdigit.com/tutorials/swiftdata-crud-operations-modelactor) — Tutorial · Topics: Concurrency · Swift · SwiftData
  **NeKI brief:** Examines SwiftData CRUD Operations with ModelActor, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Replacing EnvironmentKit with the new SwiftUI Entry macro](https://danielsaidi.com/blog/2025/01/11/replacing-environmentkit-with-the-entry-macro) — Article · Topics: Macros & Metaprogramming · Swift · SwiftUI
  **NeKI brief:** Examines Replacing EnvironmentKit with the new SwiftUI Entry macro, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [SwiftUI View Picture Book (FREE)](https://www.bigmountainstudio.com/free-swiftui-book) — Article · Topics: Accessibility · Swift · SwiftUI
  **NeKI brief:** Examines SwiftUI View Picture Book (FREE), emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Launch at Login Setting](https://nilcoalescing.com/blog/LaunchAtLoginSetting) — Article · Topics: Developer Career & Practice · Swift
  **NeKI brief:** Demonstrates registering a macOS app as a login item with SMAppService. Use it to implement an explicit launch-at-login setting while keeping user control and system preferences aligned.
- [SwiftUI Action Menu](https://peterfriese.dev/blog/2025/swiftui-action-menu) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Builds a reusable SwiftUI action menu with a view builder and sheet presentation, turning a one-off menu into a component with an explicit content contract. Follow it for composition patterns, not as a substitute for platform menu guidance.
- [Introduction to Non-Copyable types in Swift](https://www.youtube.com/watch?v=ydbcczlMEkA) — Video · Topics: Developer Career & Practice · Swift
  **NeKI brief:** Reviews Introduction to Non-Copyable types in Swift. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Integrating Live Activity and Dynamic Island in iOS](https://canopas.com/integrating-live-activity-and-dynamic-island-in-i-os-a-complete-guide) — Article · Topics: App Services & Extensions
  **NeKI brief:** In this first part of a two articles series, Radhika covers in detail the essentials of Live Activities and Dynamic Island showing the setting up, updating, and ending process of an activity.
- [The Synchronisation Framework](https://blog.jacobstechtavern.com/p/the-synchronisation-framework) — Article · Topics: Architecture · Objective-C & Cocoa
  **NeKI brief:** Use Swift Synchronization primitives such as Mutex and atomics for tightly scoped synchronous shared-state access, and compare them with actors based on isolation, suspension, and contention needs. Keep critical sections small, document invariants, and avoid mixing low-level synchronization casually with async workflows.

## [Issue 197](https://thosewhoswift.substack.com/p/those-who-swift-issue-197)

- Published: `2025-01-17`

**Topics:** Apple Platform Ecosystem · Concurrency · Graphics, Media & Games · Security & Privacy · Swift · SwiftUI

**Sections:** Those Who Swift · Those Who Swift - Issue 197 · Weekly note ✏️

**Selected links:**
- [Using withObservationTracking to monitor changes in @Observable properties outside SwiftUI views](https://www.polpiella.dev/observable-outside-of-a-view) — Article · Topics: Observation & State Management · Swift · SwiftUI
  **NeKI brief:** Uses withObservationTracking to observe @Observable changes outside SwiftUI views. Use it when an imperative coordinator or service needs dependency-aware callbacks without adopting Combine.
- [Handle plurals in SwiftUI Text views with inflection](https://nilcoalescing.com/blog/HandlePluralsInSwiftUITextViewsWithInflection) — Article · Topics: Foundation & Data Formats · Swift · SwiftUI
  **NeKI brief:** Uses SwiftUI text inflection to select plural forms from localized strings. Useful for grammatical counts that must adapt to locale without embedding English-only singular/plural conditionals.
- [How to hide private information](https://www.swiftwithvincent.com/blog/how-to-hide-private-information) — Article · Topics: Security & Privacy · Swift · SwiftUI
  **NeKI brief:** Examines How to hide private information, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Controlling keyboard events with keys and phases](https://www.createwithswift.com/controlling-keyboard-events-with-keys-and-phases) — Article · Topics: Hardware & Devices · Swift · SwiftUI
  **NeKI brief:** Shows handling keyboard events in SwiftUI through key values and event phases. Follow it when desktop or iPad hardware-keyboard interactions need predictable shortcuts, focus behavior, and propagation control without coupling input handling to a single view.
- [How to use cryptographic hash functions in CryptoKit for iOS security](https://tanaschita.com/swift-hash-functions) — Article · Topics: Security & Privacy · Swift
  **NeKI brief:** Uses CryptoKit hash functions for integrity and security-related fingerprints. Use it when comparing data or deriving stable digests, while distinguishing hashing from reversible encryption.
- [Migrating from the Outside in](https://www.massicotte.org/outside-in-migration) — Article · Topics: Concurrency · Personal Essays · Swift
  **NeKI brief:** Explores an outside-in migration approach. Useful for planning incremental architectural change from user-facing behavior inward while keeping intermediate states testable and shippable.
- [Solving “Main actor-isolated property can not be referenced from a Sendable closure” in Swift](https://www.donnywals.com/solving-main-actor-isolated-property-can-not-be-referenced-from-a-sendable-closure-in-swift) — Article · Topics: Concurrency · Swift
  **NeKI brief:** Diagnoses the compiler error caused by accessing main-actor-isolated state from a Sendable closure and presents isolation-aware fixes. Use it when migrating Swift concurrency code, choosing capture strategies, and preserving actor boundaries rather than silencing diagnostics.
- [Exploring Tab View Styles in SwiftUI](https://www.createwithswift.com/exploring-tab-view-styles-in-swiftui) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Compares SwiftUI TabView styles and their platform-specific behavior. Useful for choosing a tab presentation that matches navigation semantics instead of treating styles as purely cosmetic.
- [Apple WWDC YouTube videos update](https://www.youtube.com/@AppleDeveloper/videos) — Video · Topics: Apple Platform Ecosystem · Graphics, Media & Games
  **NeKI brief:** Reviews Apple WWDC YouTube videos update. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Creating custom SF Symbols using the SF Symbols app](https://peterfriese.dev/blog/2025/custom-sf-symbols) — Tutorial
  **NeKI brief:** Creates custom SF Symbols-style artwork and integrates it with SwiftUI symbol effects. Useful when system symbols lack a domain icon, while preserving consistent scaling and state animation.

## [Issue 196](https://thosewhoswift.substack.com/p/those-who-swift-issue-196)

- Published: `2025-01-09`

**Topics:** Foundation & Data Formats · Graphics, Media & Games · Swift · SwiftUI · Testing · Xcode

**Sections:** Those Who Swift · Those Who Swift - Issue 196 · Weekly note ✏️

**Selected links:**
- [Adopting Swift 6 across the app codebase](https://swiftwithmajid.com/2025/01/07/adopting-swift6-across-the-app-codebase) — Article · Topics: Concurrency · Security & Privacy · Swift
  **NeKI brief:** Describes a staged approach to adopting Swift 6 across an existing app, including strict concurrency diagnostics and incremental remediation. Useful for planning migration work by ownership boundary, measuring warning debt, and keeping delivery possible during the transition.
- [Swift Parameterized Testing](https://useyourloaf.com/blog/swift-parameterized-testing) — Article · Topics: Combine & Reactive Programming · Swift · Testing
  **NeKI brief:** Demonstrates Swift Testing’s @Test arguments with single values, Cartesian products, and zip-based pairing, showing how the Test Navigator reports each case and where the two-argument limit shapes test data design.
- [Enhance UI/UX with the confirmation dialog component](https://www.createwithswift.com/enhance-ui-ux-with-the-confirmation-dialog-component) — Article · Topics: Product Design · Swift · SwiftUI
  **NeKI brief:** Explains using SwiftUI confirmation dialogs for action choices. Use it to present destructive or consequential options with clear labels and a predictable dismissal path.
- [Creating tiny utility apps with SwiftUI Previews](https://danielsaidi.com/blog/2025/01/04/creating-tiny-utility-apps-with-swiftui-previews-copy) — Article · Topics: Hardware & Devices · Swift · SwiftUI
  **NeKI brief:** Examines Creating tiny utility apps with SwiftUI Previews, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [OpenHands](https://github.com/All-Hands-AI/OpenHands) — Source repository · Topics: AI Development · Developer Tools · Personal Essays
  **NeKI brief:** Provides the OpenHands agent platform source repository. Useful for inspecting implementation, deployment, and extensibility details directly rather than relying only on product descriptions.
- [iOSDevKit - Cheat Sheets, Posters & Infographics](https://ishtiakahmed.gumroad.com/l/iOSDevKit) — Article · Topics: Swift · SwiftUI · Xcode
  **NeKI brief:** Examines iOSDevKit - Cheat Sheets, Posters & Infographics, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Understanding opaque types and protocols with associatedtype in Swift](https://tanaschita.com/swift-opaque-types-protocols-associatedtype) — Article · Topics: Code Quality · Swift
  **NeKI brief:** Shows how opaque some types work with protocols that have associated types. Use it to hide concrete implementations while preserving compiler-checked relationships between returned values and protocols.
- [Codable conformance for Swift enums](https://nilcoalescing.com/blog/CodableConformanceForSwiftEnums) — Article · Topics: Foundation & Data Formats · Swift
  **NeKI brief:** Explains synthesized and custom Codable conformance for Swift enums, including manual implementations for complex cases. Use it when serialized representations need compatibility beyond automatic coding keys.
- [Xcode 16's Buildable Folders](https://blog.makwanbk.com/how-one-new-xcode-feature-helped-my-work-project-eliminate-66k-lines-of-code) — Article · Topics: Developer Career & Practice · Xcode
  **NeKI brief:** Makwan highlights how Xcode 16’s buildable folders helped streamline the author’s team project while exploring its impact and trade-offs.
- [Testing Background Uploads in iOS](https://adamwulf.me/2025/01/testing-background-uploads-in-ios) — Article · Topics: Networking · Testing
  **NeKI brief:** Tests background uploads in iOS, focusing on execution constraints and reliable completion. Useful when validating upload behavior that must survive suspension rather than assuming foreground networking semantics.
- [Markdown links can do what?](https://jacobzivandesign.com/technology/links_in_swiftui_markdown_do_what) — Article · Topics: Swift · SwiftUI
  **NeKI brief:** Shows how SwiftUI Markdown links can trigger application actions by combining custom URL schemes with OpenURLAction instead of opening a web page. Use the technique when inline text needs accessible, link-like commands with explicit routing.
