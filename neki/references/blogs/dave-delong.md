# Dave DeLong

Third-party source index. It provides source attribution and routing metadata, not republished article content. Verify article conclusions independently before applying them.

- Archive: [https://davedelong.com/blog/archive/](https://davedelong.com/blog/archive/)
- Last collected: `2026-07-22T21:58:56Z`
- Indexed entries: **55**

- [Handy git customizations | Dave DeLong](https://davedelong.com/blog/2023/03/04/handy-git-customizations)
  **Published:** `2023-03-04T00:00:00+00:00`
  **Topics:** Developer Community & Business
  **NeKI brief:** Git aliases and configuration can make destructive commands clearer and history easier to inspect, but shared teams need portable conventions rather than private shell magic.
- [Adventures in Advent of Code | Dave DeLong](https://davedelong.com/blog/2022/12/03/adventures-in-advent-of-code)
  **Published:** `2022-12-03T00:00:00+00:00`
  **Topics:** Swift
  **NeKI brief:** Advent of Code is used as deliberate practice for rarely exercised skills, providing low-stakes feedback on algorithms without pretending puzzle performance predicts production design.
- [My First App | Dave DeLong](https://davedelong.com/blog/2022/08/31/my-first-app)
  **Published:** `2022-08-31T00:00:00+00:00`
  **Topics:** Personal Essays
  **NeKI brief:** A retrospective on a first app traces how early experimentation with web and graphics shaped later engineering instincts, useful as context rather than a prescriptive workflow.
- [Conditional Compilation, Part 4: Deployment Targets | Dave DeLong](https://davedelong.com/blog/2022/05/15/conditional-compilation-part-4-deployment-targets)
  **Published:** `2022-05-15T00:00:00+00:00`
  **Topics:** Swift
  **NeKI brief:** Deployment-target checks can be centralized through conditional compilation helpers, reducing scattered availability branches while preserving separate code paths for older SDKs.
- [Simplifying Backwards Compatibility in Swift | Dave DeLong](https://davedelong.com/blog/2021/10/09/simplifying-backwards-compatibility-in-swift)
  **Published:** `2021-10-09T00:00:00+00:00`
  **Topics:** Swift
  **NeKI brief:** Shows a compatibility wrapper pattern that centralizes availability checks and exposes one stable API to callers. Useful when supporting older OS releases without scattering #available branches through SwiftUI views.
- [Core Data and SwiftUI | Dave DeLong](https://davedelong.com/blog/2021/04/03/core-data-and-swiftui)
  **Published:** `2021-04-03T00:00:00+00:00`
  **Topics:** Core Data · Persistence & Synchronisation · Swift · SwiftUI
  **NeKI brief:** Connects Core Data with SwiftUI state updates. Use it when fetched objects, context changes, and view identity need coordination in a persistence-backed interface.
- [Custom Property Wrappers for SwiftUI | Dave DeLong](https://davedelong.com/blog/2021/04/02/custom-property-wrappers-for-swiftui)
  **Published:** `2021-04-02T00:00:00+00:00`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Explores custom property wrappers tailored to SwiftUI state and dependencies. Use it when a repeated access pattern deserves a declarative wrapper, while keeping ownership and update behavior explicit.
- [Exploiting String Interpolation For Fun And For Profit | Dave DeLong](https://davedelong.com/blog/2021/03/04/exploiting-string-interpolation-for-fun-and-for-profit)
  **Published:** `2021-03-04T00:00:00+00:00`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Custom String.StringInterpolation hooks can encode domain-specific formatting at the call site, improving readability while making interpolation behavior less obvious to generic logging consumers.
- [HTTP in Swift, Part 18: Wrapping Up | Dave DeLong](https://davedelong.com/blog/2020/10/03/http-in-swift-part-18-wrapping-up)
  **Published:** `2020-10-03T00:00:00+00:00`
  **Topics:** Swift
  **NeKI brief:** The HTTP series finishes with a composable request-to-response pipeline, showing how loaders keep policy independent; the architecture scales through composition but requires lifecycle discipline.
- [HTTP in Swift, Part 17: Brain Dump | Dave DeLong](https://davedelong.com/blog/2020/10/03/http-in-swift-part-17-brain-dump)
  **Published:** `2020-10-03T00:00:00+00:00`
  **Topics:** Architecture · Swift
  **NeKI brief:** The HTTP loader architecture is stress-tested against additional loader ideas, emphasizing reusable policy seams while acknowledging that not every feature deserves a dedicated type.
- [HTTP in Swift, Part 16: Composite Loaders | Dave DeLong](https://davedelong.com/blog/2020/08/05/http-in-swift-part-16-composite-loaders)
  **Published:** `2020-08-05T00:00:00+00:00`
  **Topics:** Swift
  **NeKI brief:** A composite loader groups authentication or other policies behind one HTTPLoader, allowing chains to grow without callers knowing each step; debugging must then expose inner-loader boundaries.
- [HTTP in Swift, Part 15: OAuth | Dave DeLong](https://davedelong.com/blog/2020/08/03/http-in-swift-part-15-oauth)
  **Published:** `2020-08-03T00:00:00+00:00`
  **Topics:** Swift
  **NeKI brief:** OAuth becomes a loader-driven state machine that refreshes tokens and retries authorization, keeping credentials out of request code while making asynchronous failure paths explicit.
- [HTTP in Swift, Part 14: OAuth Setup | Dave DeLong](https://davedelong.com/blog/2020/07/28/http-in-swift-part-14-oauth-setup)
  **Published:** `2020-07-28T00:00:00+00:00`
  **Topics:** Swift
  **NeKI brief:** OAuth setup models token presence, login, and refresh as explicit states before integrating the flow, preventing authentication code from becoming scattered request-side conditionals.
- [HTTP in Swift, Part 13: Basic Authentication | Dave DeLong](https://davedelong.com/blog/2020/07/27/http-in-swift-part-13-basic-authentication)
  **Published:** `2020-07-27T00:00:00+00:00`
  **Topics:** Swift
  **NeKI brief:** Basic authentication is implemented as an HTTP loader that injects credentials at the boundary, keeping endpoint models clean while requiring secure credential ownership.
- [HTTP in Swift, Part 12: Retrying | Dave DeLong](https://davedelong.com/blog/2020/07/23/http-in-swift-part-12-retrying)
  **Published:** `2020-07-23T00:00:00+00:00`
  **Topics:** Networking · Swift
  **NeKI brief:** Retries are modeled as a loader policy rather than embedded in endpoints, so response suitability and retry limits stay configurable; careless policies can amplify server load.
- [HTTP in Swift, Part 11: Throttling | Dave DeLong](https://davedelong.com/blog/2020/07/20/http-in-swift-part-11-throttling)
  **Published:** `2020-07-20T00:00:00+00:00`
  **Topics:** Swift
  **NeKI brief:** A throttling loader serializes request admission to prevent timer-driven traffic spikes, trading throughput and latency for a predictable server request rate.
- [HTTP in Swift, Part 10: Cancellation | Dave DeLong](https://davedelong.com/blog/2020/07/19/http-in-swift-part-10-cancellation)
  **Published:** `2020-07-19T00:00:00+00:00`
  **Topics:** Networking · Swift
  **NeKI brief:** Cancellation is propagated through the loader chain so in-flight work can stop without changing request construction; every loader must honor that signal or cancellation becomes partial.
- [HTTP in Swift, Part 9: Resetting | Dave DeLong](https://davedelong.com/blog/2020/07/12/http-in-swift-part-9-resetting)
  **Published:** `2020-07-12T00:00:00+00:00`
  **Topics:** Swift
  **NeKI brief:** Resetting a loader chain gives long-lived networking components a defined way to discard transient state, but reset semantics must be coordinated with requests already in flight.
- [HTTP in Swift, Part 8: Request Options | Dave DeLong](https://davedelong.com/blog/2020/07/09/http-in-swift-part-8-request-options)
  **Published:** `2020-07-09T00:00:00+00:00`
  **Topics:** Swift · SwiftUI
  **NeKI brief:** Request options travel alongside HTTP requests through the chain, letting individual loaders opt into behavior without global flags; option ownership must remain unambiguous.
- [HTTP in Swift, Part 7: Dynamically Modifying Requests | Dave DeLong](https://davedelong.com/blog/2020/07/05/http-in-swift-part-7-dynamically-modifying-requests)
  **Published:** `2020-07-05T00:00:00+00:00`
  **Topics:** Swift
  **NeKI brief:** A loader can rewrite requests immediately before execution, enabling headers and URLs to reflect current state without rebuilding callers; mutation order remains observable behavior.
- [HTTP in Swift, Part 6: Chaining Loaders | Dave DeLong](https://davedelong.com/blog/2020/07/04/http-in-swift-part-6-chaining-loaders)
  **Published:** `2020-07-04T00:00:00+00:00`
  **Topics:** Swift
  **NeKI brief:** Chaining loaders turns cross-cutting HTTP behavior into ordered decorators, enabling authentication and caching to compose; order becomes a correctness constraint rather than an implementation detail.
- [HTTP in Swift, Part 5: Testing and Mocking | Dave DeLong](https://davedelong.com/blog/2020/07/03/http-in-swift-part-5-testing-and-mocking)
  **Published:** `2020-07-03T00:00:00+00:00`
  **Topics:** Swift · Testing
  **NeKI brief:** Mock loaders make request pipelines testable without network access, allowing assertions on composition and failure handling while preserving the same loading interface as production.
- [HTTP in Swift, Part 4: Loading Requests | Dave DeLong](https://davedelong.com/blog/2020/07/02/http-in-swift-part-4-loading-requests)
  **Published:** `2020-07-02T00:00:00+00:00`
  **Topics:** Swift
  **NeKI brief:** The first concrete loader turns a request/response model into asynchronous transport, establishing the seam where retries, authentication, and test doubles can later compose.
- [HTTP in Swift, Part 3: Request Bodies | Dave DeLong](https://davedelong.com/blog/2020/06/30/http-in-swift-part-3-request-bodies)
  **Published:** `2020-06-30T00:00:00+00:00`
  **Topics:** Swift
  **NeKI brief:** Request bodies become typed values rather than ad hoc byte construction, clarifying serialization ownership and making malformed payload handling visible at the HTTP boundary.
- [HTTP in Swift, Part 2: Basic Structures | Dave DeLong](https://davedelong.com/blog/2020/06/28/http-in-swift-part-2-basic-structures)
  **Published:** `2020-06-28T00:00:00+00:00`
  **Topics:** Swift
  **NeKI brief:** HTTP request and response structs capture method, URL, headers, and body as value types, giving later loaders stable data to transform without shared mutable state.
- [HTTP in Swift, Part 1: An Intro to HTTP | Dave DeLong](https://davedelong.com/blog/2020/06/27/http-in-swift-part-1)
  **Published:** `2020-06-27T00:00:00+00:00`
  **Topics:** Swift
  **NeKI brief:** Introduces HTTP concepts through Swift types and request construction. Use it when networking code needs a clearer model of methods, headers, status, and transport boundaries.
- [The Missing Accessory | Dave DeLong](https://davedelong.com/blog/2020/06/15/the-missing-accessory)
  **Published:** `2020-06-15T00:00:00+00:00`
  **Topics:** Personal Essays
  **NeKI brief:** The missing accessory essay uses a concrete workflow gap to show how small tooling friction compounds over time, making the case for automating repeated setup work.
- [Anything worth doing… | Dave DeLong](https://davedelong.com/blog/2020/06/14/anything-worth-doing)
  **Published:** `2020-06-14T00:00:00+00:00`
  **Topics:** Personal Essays
  **NeKI brief:** A Swift XML-RPC bridge lets a native editor manage Jekyll source files while preserving static-site output. Typed Codable request types expose only the authoring operations the publishing workflow needs, trading simplicity for custom protocol maintenance.
- [Introducing Time | Dave DeLong](https://davedelong.com/blog/2020/02/29/introducing-time)
  **Published:** `2020-02-29T00:00:00+00:00`
  **Topics:** Developer Community & Business
  **NeKI brief:** Introduces a value-oriented Time abstraction for representing and manipulating temporal values. Follow it when date calculations need testable semantics and should not depend directly on wall-clock APIs or Foundation's mutable formatters.
- [Conditional Compilation, Part 3: App Extensions | Dave DeLong](https://davedelong.com/blog/2019/04/09/conditional-compilation-part-3)
  **Published:** `2019-04-09T00:00:00+00:00`
  **Topics:** Xcode
  **NeKI brief:** Shows conditional compilation strategies for app extensions and target-specific code. Follow it when sharing Swift sources across application and extension targets without leaking unavailable APIs into a build.
- [Silencing Specific Build Warnings | Dave DeLong](https://davedelong.com/blog/2018/12/15/silencing-specific-build-warnings)
  **Published:** `2018-12-15T00:00:00+00:00`
  **Topics:** Xcode
  **NeKI brief:** Selective warning suppression documents an intentional exception without hiding unrelated diagnostics, preserving compiler feedback while containing noisy third-party or generated-code warnings.
- [Building a Cross-Platform Framework | Dave DeLong](https://davedelong.com/blog/2018/11/15/building-a-crossplatform-framework)
  **Published:** `2018-11-15T00:00:00+00:00`
  **Topics:** SwiftUI
  **NeKI brief:** A cross-platform framework succeeds by isolating shared policy from platform adapters, keeping common tests useful while accepting conditional implementations at the edges.
- [Conditional Compilation, Part 2: Including and Excluding Source Files | Dave DeLong](https://davedelong.com/blog/2018/07/25/conditional-compilation-in-swift-part-2)
  **Published:** `2018-07-25T00:00:00+00:00`
  **Topics:** Architecture · Swift
  **NeKI brief:** Continues conditional-compilation techniques using active compilation conditions and target configuration. Use it when refining cross-platform source boundaries without confusing compile-time and runtime availability.
- [Conditional Compilation, Part 1: Precise Feature Flags | Dave DeLong](https://davedelong.com/blog/2018/07/25/conditional-compilation-in-swift-part-1)
  **Published:** `2018-07-25T00:00:00+00:00`
  **Topics:** Swift
  **NeKI brief:** Introduces Swift conditional compilation for platform, architecture, and build-flag differences. Use it to isolate source variations while keeping feature selection explicit and testable.
- [The Laws of Core Data | Dave DeLong](https://davedelong.com/blog/2018/05/09/the-laws-of-core-data)
  **Published:** `2018-05-09T00:00:00+00:00`
  **Topics:** Core Data · Persistence & Synchronisation
  **NeKI brief:** Core Data laws frame managed objects as context-bound lifecycles rather than ordinary models, clarifying why thread confinement and save ordering are correctness constraints.
- [Deriving a New Formula | Dave DeLong](https://davedelong.com/blog/2018/05/01/deriving-a-new-formula)
  **Published:** `2018-05-01T00:00:00+00:00`
  **Topics:** Swift
  **NeKI brief:** Deriving a formula from first principles turns an opaque result into testable assumptions, a reminder to validate intermediate invariants before optimizing implementation.
- [A Better MVC, Part 5: An Evolution | Dave DeLong](https://davedelong.com/blog/2018/04/24/a-better-mvc-part-5-an-evolution)
  **Published:** `2018-04-24T00:00:00+00:00`
  **Topics:** Navigation & Deep Linking
  **NeKI brief:** Evolves an MVC architecture after earlier encapsulation work. Use it when reviewing how feature boundaries and collaborations can change incrementally without a wholesale rewrite.
- [Presentation Nerves | Dave DeLong](https://davedelong.com/blog/2018/04/23/presentation-nerves)
  **Published:** `2018-04-23T00:00:00+00:00`
  **Topics:** Developer Career & Practice
  **NeKI brief:** Presentation anxiety is reduced through rehearsal and controllable preparation, treating speaking as an engineering process with observable failure modes.
- [Yet Another New Blogging Engine | Dave DeLong](https://davedelong.com/blog/2018/04/21/yet-another-new-blog)
  **Published:** `2018-04-21T00:00:00+00:00`
  **Topics:** Cross-Platform & Web
  **NeKI brief:** After a compromised dynamic blog, the article moves to Jekyll static generation so published pages avoid per-request application execution. It treats deployment, search, and authoring ergonomics as separate operational concerns.
- [Apple Networking Feedback | Dave DeLong](https://davedelong.com/blog/2018/03/02/apple-networking-feedback)
  **Published:** `2018-03-02T00:00:00+00:00`
  **Topics:** Networking
  **NeKI brief:** Presents developer feedback on Apple's networking APIs and their ergonomics. Use it as historical API-design discussion when comparing URLSession abstractions and current networking guidance.
- [Swift Protocols Wishlist | Dave DeLong](https://davedelong.com/blog/2018/02/08/swift-protocols-wishlist)
  **Published:** `2018-02-08T00:00:00+00:00`
  **Topics:** Swift
  **NeKI brief:** This speculative protocol-design essay examines heterogeneous arrays, manual type erasers and class-cluster-like protocol interfaces. Use it to understand the trade-offs behind erased associated types, not as guidance for shipped Swift language features.
- [The 2018c Timezone Database Update | Dave DeLong](https://davedelong.com/blog/2018/01/31/the-2018c-timezone-database-update)
  **Published:** `2018-01-31T00:00:00+00:00`
  **Topics:** Persistence & Synchronisation
  **NeKI brief:** Time-zone database updates can change historical and future civil-time interpretation without application code changes. Use explicit time-zone data and regression cases around affected regions, avoiding assumptions that UTC offsets are permanent.
- [Simplifying Swift framework development | Dave DeLong](https://davedelong.com/blog/2018/01/19/simplifying-swift-framework-development)
  **Published:** `2018-01-19T00:00:00+00:00`
  **Topics:** Swift
  **NeKI brief:** Discusses simplifying framework development through module boundaries, packaging, and dependency choices. Use it when turning shared app code into a reusable Swift framework without importing accidental application assumptions.
- [Reading your own entitlements | Dave DeLong](https://davedelong.com/blog/2018/01/10/reading-your-own-entitlements)
  **Published:** `2018-01-10T00:00:00+00:00`
  **Topics:** Developer Community & Business
  **NeKI brief:** Explains reading an app's entitlements at runtime to inspect enabled capabilities. Use it for diagnostics and feature gating, while keeping entitlement checks separate from server authorization decisions.
- [Misusing enums | Dave DeLong](https://davedelong.com/blog/2017/12/07/misusing-enums)
  **Published:** `2017-12-07T00:00:00+00:00`
  **Topics:** Swift
  **NeKI brief:** Enums express a closed state space and become misleading when used to imitate open behavior or identity-heavy objects. Use the critique to reassess type choice, keeping associated values and exhaustive switching aligned with domain reality.
- [Level up your debugging skills | Dave DeLong](https://davedelong.com/blog/2017/11/29/level-up-your-debugging-skills)
  **Published:** `2017-11-29T00:00:00+00:00`
  **Topics:** Testing
  **NeKI brief:** Effective debugging begins by forming falsifiable hypotheses and narrowing the system with observable evidence. Use reproducible cases, logs and breakpoints to test assumptions, resisting broad speculative changes that obscure the original failure.
- [A Better MVC, Part 4: Future Directions | Dave DeLong](https://davedelong.com/blog/2017/11/06/a-better-mvc-part-4-future-directions)
  **Published:** `2017-11-06T00:00:00+00:00`
  **Topics:** Architecture
  **NeKI brief:** Discusses next architectural steps after improving MVC boundaries. Use it when a refactor needs a migration direction rather than introducing a replacement framework all at once.
- [A Better MVC, Part 3: Fixing Massive View Controller | Dave DeLong](https://davedelong.com/blog/2017/11/06/a-better-mvc-part-3-fixing-massive-view-controller)
  **Published:** `2017-11-06T00:00:00+00:00`
  **Topics:** SwiftUI
  **NeKI brief:** Breaks up a massive view controller into focused collaborators. Use it when routing, presentation, state, and business logic have accumulated in one untestable UIKit class.
- [A Better MVC, Part 2: Fixing Encapsulation | Dave DeLong](https://davedelong.com/blog/2017/11/06/a-better-mvc-part-2-fixing-encapsulation)
  **Published:** `2017-11-06T00:00:00+00:00`
  **Topics:** Architecture
  **NeKI brief:** Addresses MVC encapsulation by reducing inappropriate knowledge between components. Use it when view controllers expose internal state or coordination details that make changes ripple across a feature.
- [A Better MVC, Part 1: The Problems | Dave DeLong](https://davedelong.com/blog/2017/11/06/a-better-mvc-part-1-the-problems)
  **Published:** `2017-11-06T00:00:00+00:00`
  **Topics:** Architecture · Swift
  **NeKI brief:** Identifies structural problems in conventional Cocoa MVC, especially controller responsibility and testability. Follow it as the diagnostic starting point before evaluating alternative boundaries for state, presentation, and navigation.
- [iOS Feature Wish: Contact Provider Extensions | Dave DeLong](https://davedelong.com/blog/2017/11/01/ios-feature-wish-contact-provider-extensions)
  **Published:** `2017-11-01T00:00:00+00:00`
  **Topics:** UIKit
  **NeKI brief:** This feature request describes a missing extension point for third-party contact data. Treat it as product-design analysis rather than an implementable API, checking current Contacts framework capabilities before designing an integration.
- [Intercalation | Dave DeLong](https://davedelong.com/blog/2016/02/29/intercalation)
  **Published:** `2016-02-29T00:00:00+00:00`
  **Topics:** Swift
  **NeKI brief:** Calendar intercalation explains why civil calendars need leap days and other corrections to track astronomical cycles. Use it as conceptual background when modeling dates, delegating real calculations to Calendar and time-zone libraries.
- [Edit distance and edit steps | Dave DeLong](https://davedelong.com/blog/2015/12/01/edit-distance-and-edit-steps)
  **Published:** `2015-12-01T00:00:00+00:00`
  **Topics:** App Intents & System Surfaces
  **NeKI brief:** Edit distance quantifies how many insertions, deletions and replacements transform one sequence into another. Use it for fuzzy matching with a defined cost model, measuring performance before applying it to large user-facing datasets.
- [Incrementing Build Numbers in Xcode | Dave DeLong](https://davedelong.com/blog/2015/02/08/incrementing-build-numbers-in-xcode)
  **Published:** `2015-02-08T00:00:00+00:00`
  **Topics:** Xcode
  **NeKI brief:** This Xcode build-number workflow automates monotonically increasing version metadata. Follow it for legacy project maintenance, keeping versioning policy in build settings or CI rather than manually editing each release.
- [An Observation on Objective-C | Dave DeLong](https://davedelong.com/blog/2013/08/16/an-observation-on-objective-c)
  **Published:** `2013-08-16T00:00:00+00:00`
  **Topics:** Objective-C & Cocoa
  **NeKI brief:** This archived Objective-C observation preserves historical language context. Use it only when interpreting legacy Cocoa code, validating any interoperability or runtime conclusion against the current Objective-C and Swift toolchains.
