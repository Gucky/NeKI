# Code Quality

Third-party reading leads collected from NeKI sources. The links may be useful perspectives, but are not vetted recommendations or authoritative API guidance. NeKI publishes routing metadata, not the linked articles' text.

**Scope:** Maintainability, API design, correctness, code review, and engineering quality.

- Last collected: `2026-07-22T21:56:49Z`
- Indexed links shown: **22**

## Direct-source reading

- [The 7 Deadly Sins of Cargo Culting](https://blog.jacobstechtavern.com/p/the-7-deadly-sins-of-cargo-culting) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2026-04-14T15:03:03.506Z`
  **NeKI brief:** Adopt an iOS pattern only after understanding its data ownership, lifecycle, concurrency, and failure assumptions. Replace copied architectural rituals with a concrete problem statement and observable success criteria, so abstractions remain justified when the codebase or platform changes.
- [Writing code that makes mistakes harder – Donny Wals](https://www.donnywals.com/writing-code-that-makes-mistakes-harder) — Donny Wals · article catalogue
  **Published:** `2024-01-25T11:07:01+00:00`
  **NeKI brief:** Making invalid states difficult to represent uses types, narrow APIs, and validation to move likely mistakes from runtime behavior into construction-time constraints.
- [Loose coupling and the law of Demeter – Donny Wals](https://www.donnywals.com/loose-coupling-and-the-law-of-demeter) — Donny Wals · article catalogue
  **Published:** `2019-12-17T08:30:33+00:00`
  **NeKI brief:** Loose coupling limits each component's knowledge of collaborators, reducing change propagation while avoiding abstraction layers that hide simple dependencies.
- [Mental models in API design – Ole Begemann](https://oleb.net/blog/2017/07/mental-models-in-api-design) — Ole Begemann · article catalogue
  **Published:** `2017-07-31T13:22:00Z`
  **NeKI brief:** Discusses API design through the mental models users form from names, ownership, and behavior. Use it when reviewing Swift interfaces for discoverability and avoiding abstractions whose surface semantics contradict their implementation.
- [On NSURLConnection API Design – Ole Begemann](https://oleb.net/blog/2013/07/nsurlconnection-api-design) — Ole Begemann · article catalogue
  **Published:** `2013-07-08T21:48:00Z`
  **NeKI brief:** Explains why NSURLConnection's browser-oriented delegate design differs from typical web-service needs, providing historical context when migrating legacy networking code to modern URLSession abstractions.
- [Making Some Changes](https://useyourloaf.com/blog/making-some-changes) — Use Your Loaf · article catalogue
  **Published:** `2012-05-25T16:22:00+00:00`
  **NeKI brief:** Discusses making incremental project changes as a maintenance practice. Small, testable edits clarify intent and lower rollback risk, especially around older platform configuration.

## Newsletter and related leads

- [Understanding Inout Parameters In Swift - How They Work And When To Use Them](https://www.sagarunagar.com/blog/swift-inout-parameters) — Those Who Swift · Issue 264 — Article · Topics: Code Quality · Performance · Swift
  **Published:** `2026-04-29`
  **NeKI brief:** Explains Swift inout parameters, including exclusivity and mutation semantics. Follow it when reviewing APIs that borrow mutable storage, especially where escaping closures, overlapping accesses, or value-copy expectations can make a seemingly simple call unsafe.
- [SwiftUI Custom Popover](https://livsycode.com/swiftui/swiftui-custom-popover) — Those Who Swift · Issue 261 — Article · Topics: Code Quality · Swift · SwiftUI
  **Published:** `2026-04-08`
  **NeKI brief:** Demonstrates building a custom popover in SwiftUI when system presentation is too constrained. Follow it when evaluating geometry, dismissal, hit testing, and accessibility requirements, and prefer system popovers where their behavior is sufficient.
- [Mobile Engineers, You’re All Full-Stack](https://newsletter.mobileengineer.io/p/mobile-engineers-youre-all-full-stack?r=g891u&triedRedirect=true) — Those Who Swift · Issue 248 — Article · Topics: Code Quality · Networking · Persistence & Synchronisation
  **Published:** `2026-01-08`
  **NeKI brief:** Examines Mobile Engineers, You’re All Full-Stack, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Explicit Dependency Injection Best Practices](https://livsycode.com/best-practices/explicit-dependency-injection) — Those Who Swift · Issue 247 — Article · Topics: Architecture · Dependency Injection · Swift
  **Published:** `2026-01-01`
  **NeKI brief:** Explains explicit dependency injection in Swift and why construction-time wiring improves testability. Use it when removing hidden singletons, defining feature boundaries, and keeping production composition separate from previews and test fixtures.
- [CodeRabbit’s Free AI Code Reviews in your IDE—VS Code, Cursor, Windsurf](https://coderabbit.link/ios-dt) — iOS Dev Tools · iOS Dev Tools: Netrofit, MacPacker, GradientEditor — Article · Topics: AI Development · Code Quality · Developer Tools
  **Published:** `2025-10-30T18:15:32.319Z`
  **NeKI brief:** Introduces CodeRabbit’s AI-assisted code review tooling for iOS development. Use it to assess IDE review workflows, automated findings, and the boundary between generated suggestions and human approval.
- [Netrofit](https://github.com/winddpan/Netrofit) — iOS Dev Tools · iOS Dev Tools: Netrofit, MacPacker, GradientEditor — Source repository · Topics: Code Quality · Developer Tools · Swift
  **Published:** `2025-10-30T18:15:32.319Z`
  **NeKI brief:** Netrofit builds a Retrofit-like networking layer for Swift, using declarative endpoint definitions to reduce repeated request construction and response decoding. The source helps assess how far protocol-based API descriptions can simplify a typed client without hiding transport details.
- [Swift Testing Challenge: Can You Refactor This?](https://www.mobiledevdiary.com/posts/swift-testing-challange-can-you-refactor-this) — Those Who Swift · Issue 211 — Article · Topics: Concurrency · Swift · Testing
  **Published:** `2025-04-24`
  **NeKI brief:** Examines Swift Testing Challenge: Can You Refactor This?, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Issues with ScenePhase and using AppDelegate adaptors](https://www.jessesquires.com/blog/2024/06/29/swiftui-scene-phase) — iOS Dev Weekly · Issue 671 — Article · Topics: Code Quality · Swift · SwiftUI
  **Published:** `26th July 2024`
  **NeKI brief:** Explains SwiftUI scenePhase transitions and how applications respond to active, inactive, and background states. Useful for pausing work, refreshing data, and handling lifecycle changes at the scene boundary.
- [@_spi or How to develop better APIs in Swift](https://varanios.com/articles/spi-or-how-to-develop-better-apis-in-swift) — iOS Dev Weekly · Issue 662 — Article · Topics: Code Quality · Swift · Swift Package Manager
  **Published:** `24th May 2024`
  **NeKI brief:** Explains Swift’s @_spi boundary for exposing experimental or specialist API to selected clients without making it generally public. Useful for library authors weighing staged API development against the maintenance risk of relying on an underscored language feature.
- [Become an iOS Developer with Udacity](https://www.udacity.com/course/ios-developer-nanodegree--nd003?coupon=iosdevweekly) — iOS Dev Weekly · Issue 350 — Tutorial · Topics: App Distribution & Store Operations · Code Quality · Developer Career & Practice
  **Published:** `4th May 2018`
  **NeKI brief:** Examines Become an iOS Developer with Udacity, focusing on enroll in udacity’s ios developer nanodegree program today. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Swift API Design Guidelines](https://swift.org/documentation/api-design-guidelines) — iOS Dev Weekly · Issue 266 — Article · Topics: Apple Platform Ecosystem · Code Quality · Swift
  **Published:** `2nd September 2016`
  **NeKI brief:** Examines API guidelines, focusing on ash furrow with a great article on the flexibility swift has around naming. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [On NSURLConnection API Design](http://oleb.net/blog/2013/07/nsurlconnection-api-design) — iOS Dev Weekly · Issue 102 — Article · Topics: Code Quality
  **Published:** `12th July 2013`
  **NeKI brief:** Explains why NSURLConnection's browser-oriented delegate design differs from typical web-service needs, providing historical context when migrating legacy networking code to modern URLSession abstractions.
- [Build Doom3 on MacOSX with Xcode 4](http://fabiensanglard.net/doom3_macosx/index.php) — iOS Dev Weekly · Issue 18 — Article · Topics: Code Quality · macOS & AppKit · Xcode
  **Published:** `2nd December 2011`
  **NeKI brief:** Explains Build Doom3 on MacOSX with Xcode 4 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [Writing good agents.md files](https://www.philschmid.de/writing-good-agents) — Not only Swift · Issue 95 — Article · Topics: Architecture · Code Quality · Objective-C & Cocoa
  **NeKI brief:** This article covers writing effective AGENTS.md instruction files. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [A SwiftUI agent skill for better code reviews](https://github.com/AvdLee/SwiftUI-Agent-Skill) — Not only Swift · Issue 91 — Source repository · Topics: Code Quality · Swift · SwiftUI
  **NeKI brief:** Describes A SwiftUI agent skill for better code reviews, focusing on practical tool integration and workflow trade-offs. Use it to evaluate reproducibility, trust boundaries, and debugging steps before adopting the approach in an Xcode project.
- [Function calling: The missing piece for agentic apps](https://www.youtube.com/watch?v=d69KP1iFg5E) — Not only Swift · Issue 91 — Video · Topics: AI Development · Swift · SwiftUI
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
