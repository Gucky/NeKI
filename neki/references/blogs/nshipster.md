# NSHipster

Third-party source index. It provides source attribution and routing metadata, not republished article content. Verify article conclusions independently before applying them.

- Archive: [https://nshipster.com/](https://nshipster.com/)
- Last collected: `2026-07-22T13:28:18Z`
- Indexed entries: **182**

- [Replay - NSHipster](https://nshipster.com/replay) — 2025-12-31T00:00:00-08:00
  **NeKI brief:** Presents Replay, which records HTTP exchanges as HAR files and replays them through URL loading hooks during Swift Testing. The approach keeps networking tests realistic without live servers, while the sensitive-data section makes fixture sanitization part of the design.
- [Manim - NSHipster](https://nshipster.com/manim) — 2025-10-01T00:00:00-07:00
  **NeKI brief:** Introduces Manim as a tool for generating mathematical animations from code. Useful for developers creating explanatory visualizations, while keeping its Python-oriented workflow separate from app runtime code.
- [@isolated(any) - NSHipster](https://nshipster.com/isolated-any) — 2025-08-04T00:00:00-07:00
  **NeKI brief:** Explains Swift's isolated(any) function parameter for accepting closures whose actor isolation is inferred at the call site. The examples clarify how it can preserve isolation while designing reusable asynchronous APIs.
- [Uncertain⟨T⟩ - NSHipster](https://nshipster.com/uncertainty) — 2025-07-25T00:00:00-07:00
  **NeKI brief:** Uses uncertainty as a modeling problem for noisy sensors, locations, and user behavior rather than forcing false precision into scalar values. It is useful when designing APIs that must carry confidence or probabilistic outcomes explicitly.
- [Model Context Protocol (MCP) - NSHipster](https://nshipster.com/model-context-protocol) — 2025-03-07T00:00:00-08:00
  **NeKI brief:** Introduces Model Context Protocol as a standardized way for AI clients to discover tools and context providers, analogous to LSP's role for language tooling. Follow it for architectural vocabulary, then verify security and capability details against current protocol documentation.
- [Ollama - NSHipster](https://nshipster.com/ollama) — 2025-02-14T00:00:00-08:00
  **NeKI brief:** Shows how Ollama runs local language models on a Mac and exposes them to developer workflows without sending prompts to a hosted service. The trade-off is a concrete starting point for evaluating privacy, hardware, and model-quality constraints.
- [op run - NSHipster](https://nshipster.com/1password-cli) — 2025-01-01T00:00:00-08:00
  **NeKI brief:** The 1Password CLI can materialize secrets at command time, keeping credentials out of committed .env files. The useful workflow is wiring `op run` into development scripts while preserving reproducible configuration for teammates and CI.
- [As We May Code - NSHipster](https://nshipster.com/as-we-may-code) — 2020-07-07T00:00:00-07:00
  **NeKI brief:** The essay treats source code as material for analysis, not only execution, and points toward tools that raise code into understandable structure. It is useful context when evaluating syntax-aware refactoring or documentation workflows.
- [WWDC 2020 - NSHipster](https://nshipster.com/wwdc-2020) — 2020-06-26T00:00:00-07:00
  **NeKI brief:** This WWDC20 survey highlights platform APIs and development themes from that release. Use it as historical orientation for legacy code, checking current SDK documentation and availability before adopting any described approach.
- [Cross-Pollination - NSHipster](https://nshipster.com/cross-pollination) — 2020-04-22T00:00:00-07:00
  **NeKI brief:** This essay connects SwiftUI and Combine to ideas familiar from React and Elm, then examines how function builders and Objective-C generics crossed ecosystem boundaries. Follow it as design context, not as API documentation.
- [Contact Tracing - NSHipster](https://nshipster.com/contact-tracing) — 2020-04-13T00:00:00-07:00
  **NeKI brief:** The Apple-Google exposure-notification design keeps contact events as rotating identifiers and performs matching on-device, reducing central knowledge of users. The article is a historical trade-off study in privacy, Bluetooth limits, and public-health utility.
- [Swift Logging - NSHipster](https://nshipster.com/swift-log) — 2020-03-26T00:00:00-07:00
  **NeKI brief:** Introduces SwiftLog's backend-independent logging API and shows how applications select a concrete logger implementation at runtime. It is useful for separating instrumentation call sites from deployment-specific sinks and log-level policy.
- [Xcode Build Configuration Files - NSHipster](https://nshipster.com/xcconfig) — 2020-02-27T00:00:00-08:00
  **NeKI brief:** Explains Xcode configuration files as a way to separate build settings from project files. Use it to route environment-specific values, shared target settings, and CI overrides into reviewable text configuration.
- [Static and Dynamic Callable Types in Swift - NSHipster](https://nshipster.com/callable) — 2020-02-12T00:00:00-08:00
  **NeKI brief:** Explores Swift's `callAsFunction` feature for making type instances callable. Follow it when designing DSL-like APIs or function objects, while weighing discoverability, overload ambiguity, and whether call syntax hides important domain intent.
- [RawRepresentable - NSHipster](https://nshipster.com/rawrepresentable) — 2020-01-29T00:00:00-08:00
  **NeKI brief:** RawRepresentable is more than a convenience initializer: it lets a domain type keep a typed API while defining a stable serialized boundary. The article weighs that conversion contract against losing information when raw values are invalid.
- [@ - NSHipster](https://nshipster.com/at-compiler-directives) — 2020-01-06T00:00:00-08:00
  **NeKI brief:** Objective-C's `@` directives mark language and runtime boundaries, from declarations to literals and synchronization constructs. Mapping those forms explains which behavior the compiler lowers and which semantics remain in the Objective-C runtime.
- [Objective-C Direct Methods - NSHipster](https://nshipster.com/direct) — 2019-12-16T00:00:00-08:00
  **NeKI brief:** Explains Objective-C direct methods and their dispatch or visibility implications. Follow it when maintaining mixed Objective-C/Swift code and choosing whether a method should bypass dynamic dispatch for correctness or performance.
- [Swift API Availability - NSHipster](https://nshipster.com/available) — 2019-12-10T00:00:00-08:00
  **NeKI brief:** Swift availability annotations make deployment constraints executable documentation: declarations can be gated by OS version, introduced, deprecated, or obsoleted. The article is useful when designing fallbacks instead of scattering runtime version checks through call sites.
- [bless - NSHipster](https://nshipster.com/bless) — 2019-11-25T00:00:00-08:00
  **NeKI brief:** The bless command manages bootable macOS volumes from the command line. It is a specialized systems reference, useful for deployment or recovery tooling where startup-disk changes require explicit privileges and verification.
- [KeyValuePairs - NSHipster](https://nshipster.com/keyvaluepairs) — 2019-11-19T00:00:00-08:00
  **NeKI brief:** KeyValuePairs preserves insertion order and duplicate keys, unlike Dictionary, making it suitable for argument lists and ordered configuration rather than lookup. The distinction prevents accidentally promising uniqueness when an API needs call-site order.
- [Secret Management on iOS - NSHipster](https://nshipster.com/secrets) — 2019-11-12T00:00:00-08:00
  **NeKI brief:** Discusses managing secrets in iOS projects and the risks of embedding credentials in app binaries. Use it to route Keychain, build configuration, and server-mediated secret handling decisions.
- [Message-ID and Mail.app Deep Linking on iOS and macOS - NSHipster](https://nshipster.com/message-id) — 2019-11-04T00:00:00-08:00
  **NeKI brief:** Mail message identifiers provide a deep-link target across iOS and macOS, but privacy changes can hide the address needed to construct one. The article traces the handoff and the onboarding trade-off between direct linking and user permission.
- [Device Identifiers and Fingerprinting on iOS - NSHipster](https://nshipster.com/device-identifiers) — 2019-10-31T00:00:00-07:00
  **NeKI brief:** iOS identifier choices differ in scope, reset behavior, and user consent, so a stable value is never a neutral analytics shortcut. The article compares device and vendor identifiers with fingerprinting risks and App Store policy constraints.
- [MetricKit - NSHipster](https://nshipster.com/metrickit) — 2019-10-21T00:00:00-07:00
  **NeKI brief:** Explains MetricKit's deferred, aggregated performance and diagnostic payloads, contrasting them with interactive profiling. Follow it when designing production telemetry that must respect device privacy and the framework's delivery cadence.
- [SwiftUI Previews on macOS Catalina and Xcode 11 - NSHipster](https://nshipster.com/swiftui-previews) — 2019-10-14T00:00:00-07:00
  **NeKI brief:** Explains SwiftUI previews as a fast way to inspect views under alternate environments and data states. Use that workflow to include accessibility sizes and appearances in visual checks before running full UI tests.
- [iOS 13 - NSHipster](https://nshipster.com/ios-13) — 2019-09-23T00:00:00-07:00
  **NeKI brief:** This iOS 13 tour surfaces lesser-known APIs including LinkPresentation, on-device speech recognition, WebSocket tasks, background tasks, content-type annotations and storyboard creators. Use it to identify legacy adoption points, then verify current availability and replacements.
- [Apple Push Notification Device Tokens - NSHipster](https://nshipster.com/apns-device-tokens) — 2019-09-16T00:00:00-07:00
  **NeKI brief:** Explains APNs device-token registration and the lifecycle of token values. Follow it when designing push-token upload, refresh handling, and server association without assuming a token is permanent per installation.
- [Dark Mode on iOS 13 - NSHipster](https://nshipster.com/dark-mode) — 2019-09-02T00:00:00-07:00
  **NeKI brief:** Dark Mode adoption spans asset colors, semantic system colors, and trait-driven UI updates; hard-coded RGB values bypass that adaptation. The migration guidance keeps contrast and appearance changes coherent across UIKit views.
- [Identifiable - NSHipster](https://nshipster.com/identifiable) — 2019-08-26T00:00:00-07:00
  **NeKI brief:** `Identifiable` separates an entity's stable identity from its mutable presentation, enabling SwiftUI to diff collections without equating full values. The article clarifies when an ID must persist and when a transient identity causes replacement animations.
- [macOS Accessibility Keyboard - NSHipster](https://nshipster.com/accessibility-keyboard) — 2019-08-12T00:00:00-07:00
  **NeKI brief:** Examines macOS Accessibility Keyboard as an alternative input model rather than a device-specific novelty. The perspective is useful when testing keyboard-driven interaction and questioning assumptions that touch or pointer input is always available.
- [Formatter - NSHipster](https://nshipster.com/formatter) — 2019-07-15T00:00:00-07:00
  **NeKI brief:** Foundation formatters centralize locale-sensitive parsing and presentation, but each formatter encodes different calendar, numeric, or user-preference assumptions. The catalogue helps choose an explicit formatter instead of hand-built strings that silently break for other locales.
- [CAEmitterLayer - NSHipster](https://nshipster.com/caemitterlayer) — 2019-07-08T00:00:00-07:00
  **NeKI brief:** CAEmitterLayer models particles as a hierarchy of cells with independent birth rate, lifetime, velocity, and color ranges. The confetti example shows how Core Animation can keep continuous effects off the main layout path while exposing tuning trade-offs.
- [UIStackView - NSHipster](https://nshipster.com/uistackview) — 2019-07-01T00:00:00-07:00
  **NeKI brief:** UIStackView composes arranged subviews while delegating distribution, alignment, spacing, and hiding behavior to a layout container. The article highlights when those constraints replace hand-tuned Auto Layout and where explicit constraints remain necessary.
- [Swift Property Wrappers - NSHipster](https://nshipster.com/propertywrapper) — 2019-06-24T00:00:00-07:00
  **NeKI brief:** Explains property wrappers as a mechanism for transforming storage access and exposing projected values. Use it when designing reusable state or validation behavior and deciding which mutation and projection semantics belong in the wrapper.
- [WWDC 2019 - NSHipster](https://nshipster.com/wwdc-2019) — 2019-06-12T00:00:00-07:00
  **NeKI brief:** Provides an NSHipster guide to WWDC 2019 topics and sessions. Use it as a dated navigation aid for platform history, checking any API details against current documentation.
- [Swift Code Formatters - NSHipster](https://nshipster.com/swift-format) — 2019-05-20T00:00:00-07:00
  **NeKI brief:** Swift formatting is an integration decision, not merely an editor preference: a formatter can enforce one representation in review and automation while limiting local style freedom. The article compares the proposal's scope with existing lint and formatting workflows.
- [Image Resizing Techniques - NSHipster](https://nshipster.com/image-resizing) — 2019-05-06T00:00:00-07:00
  **NeKI brief:** Image resizing choices differ by interpolation quality, memory cost, and whether work happens during decoding or display. The article compares Core Graphics and UIKit paths so a pipeline can resize once at the right boundary instead of repeatedly on the main thread.
- [Optional, throws, Result, async/await - NSHipster](https://nshipster.com/optional-throws-result-async-await) — 2019-04-29T00:00:00-07:00
  **NeKI brief:** Compares Optional, throws, Result, and async/await as different failure and control-flow representations. Follow it when choosing an API contract that communicates recoverability, sequencing, and error ownership clearly.
- [CoreGraphics Geometry Primitives - NSHipster](https://nshipster.com/cggeometry) — 2019-04-22T00:00:00-07:00
  **NeKI brief:** Core Graphics geometry types make coordinate-space conversion and rectangle arithmetic explicit, reducing ad-hoc tuple math. The article is useful when choosing value semantics for points, sizes, transforms, and intersection logic in rendering code.
- [Guided Access - NSHipster](https://nshipster.com/guided-access) — 2019-04-15T00:00:00-07:00
  **NeKI brief:** Explains Guided Access as a system feature for restricting an iOS device to one app and controlling interaction. Follow it when designing kiosk, classroom, or focused-use scenarios with explicit exit and capability boundaries.
- [UITableViewHeaderFooterView - NSHipster](https://nshipster.com/uitableviewheaderfooterview) — 2019-04-08T00:00:00-07:00
  **NeKI brief:** UITableViewHeaderFooterView participates in the same reuse model as cells, so expensive header setup belongs in registration and configuration rather than every layout pass. Reuse identifiers and content updates remain separate responsibilities.
- [XcodeKit and Xcode Source Editor Extensions - NSHipster](https://nshipster.com/xcode-source-extensions) — 2019-03-25T00:00:00-07:00
  **NeKI brief:** Introduces Xcode Source Editor Extensions for commands that read or transform selected source text. Use it when automating editor workflows and deciding how command input, output, and completion should be handled.
- [LocalizedError, RecoverableError, CustomNSError - NSHipster](https://nshipster.com/swift-foundation-error-protocols) — 2019-03-18T00:00:00-07:00
  **NeKI brief:** Compares LocalizedError, RecoverableError, and CustomNSError for presenting and bridging failures. Use it when designing error types that need user-facing recovery guidance, NSError compatibility, or localized diagnostics.
- [MapKit JS - NSHipster](https://nshipster.com/mapkit-js) — 2019-03-11T00:00:00-07:00
  **NeKI brief:** MapKit JS moves Apple's map rendering and search model into web clients, with token configuration and browser lifecycle replacing native delegates. The article highlights the integration trade-off between shared map capabilities and web-specific authentication and performance.
- [JavaScriptCore - NSHipster](https://nshipster.com/javascriptcore) — 2019-02-25T00:00:00-08:00
  **NeKI brief:** JavaScriptCore embeds a JavaScript context inside a native process, exposing values and callbacks across the language boundary. The article surfaces ownership, exception handling, and sandbox considerations that make scripting powerful but difficult to isolate.
- [API Pollution in Swift Modules - NSHipster](https://nshipster.com/swift-api-pollution) — 2019-02-18T00:00:00-08:00
  **NeKI brief:** Importing a Swift module can leak names and extensions into clients, creating accidental API surface and ambiguous overloads. The article uses access control and import design to contain those dependencies rather than treating every import as harmless.
- [Regular Expressions in Swift - NSHipster](https://nshipster.com/swift-regular-expressions) — 2019-02-11T00:00:00-08:00
  **NeKI brief:** Swift regular-expression APIs turn pattern matching into typed construction and capture extraction rather than opaque stringly-typed calls. The article helps decide when a regex is maintainable and when a parser gives clearer validation and diagnostics.
- [ExpressibleByStringInterpolation - NSHipster](https://nshipster.com/expressiblebystringinterpolation) — 2019-02-04T00:00:00-08:00
  **NeKI brief:** ExpressibleByStringInterpolation lets a type define how embedded values are converted and escaped, keeping formatting policy in the destination type. The design improves call-site ergonomics but requires careful overloads to avoid ambiguous or lossy interpolation.
- [TextOutputStream - NSHipster](https://nshipster.com/textoutputstream) — 2019-01-21T00:00:00-08:00
  **NeKI brief:** Explains TextOutputStream as a protocol for routing textual output into custom destinations. Use it when diagnostics, serialization, or command-line output should target buffers or domain sinks without hard-coding print calls.
- [swift-sh - NSHipster](https://nshipster.com/swift-sh) — 2019-01-14T00:00:00-08:00
  **NeKI brief:** Covers Swift shell scripting and the practical boundary between Swift code and command-line process execution. Follow it when building developer utilities that need typed logic without adopting a full executable application structure.
- [Swift Import Declarations - NSHipster](https://nshipster.com/import) — 2019-01-07T00:00:00-08:00
  **NeKI brief:** Swift import declarations control which module names and symbols enter a file, and qualified imports can limit accidental API exposure. The article is useful when reducing namespace collisions and making dependency boundaries visible to reviewers.
- [Bundles and Packages - NSHipster](https://nshipster.com/bundles-and-packages) — 2018-12-17T00:00:00-08:00
  **NeKI brief:** Bundles package resources and metadata alongside executable code, while Swift packages provide a source and dependency boundary for distribution. The comparison clarifies which mechanism an app should use for runtime resources versus reusable libraries.
- [macOS Character Viewer - NSHipster](https://nshipster.com/character-viewer) — 2018-12-10T00:00:00-08:00
  **NeKI brief:** macOS Character Viewer exposes emoji, symbols and Unicode input independently of an app’s custom UI. The article is useful for understanding system text-entry tools and avoiding unnecessary custom character pickers.
- [Swift Program Distribution with Homebrew - NSHipster](https://nshipster.com/homebrew) — 2018-12-03T00:00:00-08:00
  **NeKI brief:** Homebrew packages Swift command-line tools with versioned formulas and repeatable installation, extending distribution beyond the App Store. The workflow highlights release artifacts, executable paths, and the maintenance cost of supporting a package manager.
- [simctl - NSHipster](https://nshipster.com/simctl) — 2018-11-26T00:00:00-08:00
  **NeKI brief:** Maps simctl's command-line controls to simulator workflows such as booting devices, installing apps, and collecting logs. It is a practical reference for repeatable automation outside Xcode's graphical controls.
- [Swift Development with Visual Studio Code - NSHipster](https://nshipster.com/vscode) — 2018-11-19T00:00:00-08:00
  **NeKI brief:** Explores using Visual Studio Code for Swift development and the tooling integration required outside Xcode. Use it when evaluating language-server, build, and debugging workflows for package-based Swift projects.
- [CustomPlaygroundDisplayConvertible - NSHipster](https://nshipster.com/customplaygrounddisplayconvertible) — 2018-11-12T00:00:00-08:00
  **NeKI brief:** CustomPlaygroundDisplayConvertible lets a value expose a structured, human-oriented representation in Playground results without changing its runtime semantics. The hook is valuable for diagnostics, but display code should not become a hidden serialization contract.
- [Language Server Protocol - NSHipster](https://nshipster.com/language-server-protocol) — 2018-11-05T00:00:00-08:00
  **NeKI brief:** Introduces the Language Server Protocol as a standard boundary between editors and language tooling. Use it to understand how Swift code completion, diagnostics, and navigation can be shared across editor clients.
- [Void - NSHipster](https://nshipster.com/void) — 2018-10-31T00:00:00-07:00
  **NeKI brief:** Swift's `Void` is an alias for the empty tuple, which explains why functions returning no meaningful value still participate in generic result types. The detail matters when modeling callbacks, tuples, and overloads without inventing sentinel data.
- [SwiftSyntax - NSHipster](https://nshipster.com/swiftsyntax) — 2018-10-22T00:00:00-07:00
  **NeKI brief:** SwiftSyntax represents Swift source as a typed syntax tree, allowing transformations to preserve trivia and structure instead of manipulating strings. The article is a routing lead for refactoring tools, formatters, and compiler-plugin workflows.
- [numericCast(_:) - NSHipster](https://nshipster.com/numericcast) — 2018-10-15T00:00:00-07:00
  **NeKI brief:** `numericCast` performs checked conversion between binary integer types and traps when the destination cannot represent the value. It makes conversion intent explicit, contrasting with truncating casts that can silently corrupt identifiers or counts.
- [TimeInterval, Date, and DateInterval - NSHipster](https://nshipster.com/timeinterval-date-dateinterval) — 2018-10-08T00:00:00-07:00
  **NeKI brief:** Date represents an instant, TimeInterval measures elapsed seconds, and DateInterval describes a bounded range; conflating them causes timezone and duration bugs. The article supplies a vocabulary for choosing the correct temporal abstraction at each API boundary.
- [macOS Dynamic Desktop - NSHipster](https://nshipster.com/macos-dynamic-desktop) — 2018-10-01T00:00:00-07:00
  **NeKI brief:** Explains macOS Dynamic Desktop image metadata and the time-aware asset format behind it. Use it when working with appearance- or time-dependent desktop imagery and separating system integration from ordinary image loading.
- [UIFieldBehavior - NSHipster](https://nshipster.com/uifieldbehavior) — 2018-09-24T00:00:00-07:00
  **NeKI brief:** UIFieldBehavior configures how UIKit's dynamic system applies forces to views, turning a field into a reusable physics influence rather than hand-updating positions. The mechanism is useful for prototyping motion while leaving collision and performance trade-offs explicit.
- [iOS 12 - NSHipster](https://nshipster.com/ios-12) — 2018-09-17T00:00:00-07:00
  **NeKI brief:** Provides a version-scoped overview of iOS 12 APIs and platform behavior. Follow it for legacy maintenance or deployment-target migration, not as current guidance without checking modern SDK replacements.
- [CMMotionActivity - NSHipster](https://nshipster.com/cmmotionactivity) — 2018-09-10T00:00:00-07:00
  **NeKI brief:** Explains CMMotionActivity classification updates, authorization, and confidence values. Use it when building motion-aware features and deciding how uncertain activity classifications should affect app behavior or UI.
- [NSDataAsset - NSHipster](https://nshipster.com/nsdataasset) — 2018-08-26T00:00:00-07:00
  **NeKI brief:** Shows packaging binary data in asset catalogs with NSDataAsset and loading it by name. Follow it when bundling configuration, certificates, or other data resources while keeping target membership and lookup explicit.
- [Swift Property Observers - NSHipster](https://nshipster.com/swift-property-observers) — 2018-08-20T00:00:00-07:00
  **NeKI brief:** Swift property observers run around stored-value changes, making them suitable for local invariants and side effects tied to assignment. They do not replace computed properties or mutation methods when validation must prevent an invalid value.
- [Hashable / Hasher - NSHipster](https://nshipster.com/hashable) — 2018-08-13T00:00:00-07:00
  **NeKI brief:** Hashable and Hasher explain how equality and hashing cooperate for dictionary and set membership. Follow this reference when designing value types, especially where mutable fields or custom equality could invalidate collection invariants.
- [NLLanguageRecognizer - NSHipster](https://nshipster.com/nllanguagerecognizer) — 2018-08-06T00:00:00-07:00
  **NeKI brief:** Explores NLLanguageRecognizer for identifying the language of text, alongside neighboring Natural Language and speech-related APIs. Use it when routing multilingual input or deciding which lightweight Apple NLP capability fits a text-processing step.
- [Never - NSHipster](https://nshipster.com/never) — 2018-07-30T00:00:00-07:00
  **NeKI brief:** Explains Swift's Never type and how it represents impossible return paths. Use it when modeling non-returning functions, exhaustive control flow, and APIs that terminate or always throw.
- [Password Rules / UITextInputPasswordRules - NSHipster](https://nshipster.com/uitextinputpasswordrules) — 2018-07-23T00:00:00-07:00
  **NeKI brief:** UITextInputPasswordRules declares password-generation requirements for system AutoFill. Follow it to align app constraints with the credential provider, avoiding custom validation that conflicts with generated strong passwords.
- [Bug Reporting - NSHipster](https://nshipster.com/bug-reporting) — 2018-07-16T00:00:00-07:00
  **NeKI brief:** Effective bug reports capture reproduction steps, environment, expected behavior and evidence. Follow this workflow to turn a vague failure into an actionable engineering artifact without prematurely diagnosing the cause.
- [Swift GYB - NSHipster](https://nshipster.com/swift-gyb) — 2018-07-09T00:00:00-07:00
  **NeKI brief:** Explains Swift's GYB template tool for generating repetitive source code. Use it when evaluating code-generation maintenance, build integration, and the trade-off against hand-written abstractions.
- [UITextChecker - NSHipster](https://nshipster.com/uitextchecker) — 2016-04-25T00:00:00-07:00
  **NeKI brief:** UITextChecker provides spelling and correction services using the system lexicon. The article is useful for language-aware input assistance, while keeping automatic replacement separate from user-approved text changes.
- [guard & defer - NSHipster](https://nshipster.com/guard-and-defer) — 2015-10-05T00:00:00-07:00
  **NeKI brief:** The guard and defer pairing makes preconditions and cleanup visible at the edges of a Swift scope. It is useful for reducing nested control flow while ensuring resources and state are restored on every exit path.
- [UIKeyCommand - NSHipster](https://nshipster.com/uikeycommand) — 2015-07-27T00:00:00-07:00
  **NeKI brief:** UIKeyCommand maps hardware keyboard shortcuts to responder-chain actions on iOS. Follow it to add discoverable command behavior while ensuring shortcuts coexist with focus, menus and accessibility interactions.
- [CloudKit - NSHipster](https://nshipster.com/cloudkit) — 2015-06-29T00:00:00-07:00
  **NeKI brief:** NSHipster’s CloudKit overview frames containers, records and iCloud-backed synchronization as distinct concerns. Follow it for historical API context and schema thinking before mapping a legacy design onto current CloudKit tooling.
- [iOS 9 - NSHipster](https://nshipster.com/ios9) — 2015-06-22T00:00:00-07:00
  **NeKI brief:** This iOS 9 API tour covers string transformation, single-shot location requests, Swiftified Cocoa names, formatter additions and CloudKit. Use it to understand legacy API choices, checking current framework documentation and deprecation status before implementation.
- [Mirror / CustomReflectable / CustomLeafReflectable - NSHipster](https://nshipster.com/mirror) — 2015-06-01T00:00:00-07:00
  **NeKI brief:** Mirror and CustomReflectable inspect Swift values at runtime for debugging and diagnostics. Follow it when presentation or tooling needs structural inspection, but do not treat reflected layout as a stable serialization contract.
- [XCPlayground - NSHipster](https://nshipster.com/xcplayground) — 2015-05-11T00:00:00-07:00
  **NeKI brief:** XCPlayground supports interactive exploration of Swift code and visual results. Use it to isolate a language or framework experiment, keeping production behavior covered by normal tests rather than relying on playground state.
- [Swift Documentation - NSHipster](https://nshipster.com/swift-documentation) — 2015-05-05T00:00:00-07:00
  **NeKI brief:** Swift documentation comments can turn API intent, parameters and examples into navigable developer reference. Use precise DocC-style documentation for public contracts, keeping comments synchronized with behavior instead of narrating obvious code.
- [Unmanaged - NSHipster](https://nshipster.com/unmanaged) — 2015-04-13T00:00:00-07:00
  **NeKI brief:** Unmanaged exposes Core Foundation and Objective-C ownership when Swift cannot infer lifetime rules. Use it only at interop boundaries, balancing retained and unretained transfers exactly to avoid leaks and use-after-free errors.
- [Quick Look Debugging - NSHipster](https://nshipster.com/quick-look-debugging) — 2015-03-30T00:00:00-07:00
  **NeKI brief:** Quick Look can render selected values directly in Xcode's debugger for faster inspection. Use custom representations for complex domain objects, ensuring debug helpers do not mutate state or hide the underlying value.
- [NSCalendar Additions - NSHipster](https://nshipster.com/nscalendar-additions) — 2015-03-16T00:00:00-07:00
  **NeKI brief:** Calendar arithmetic must account for locale, calendar system and daylight-saving transitions rather than adding fixed seconds. Use component-based calculations and explicit calendars when deriving user-visible dates or recurring schedules.
- [NSScanner - NSHipster](https://nshipster.com/nsscanner) — 2015-03-02T00:00:00-08:00
  **NeKI brief:** NSScanner consumes structured text incrementally using configurable character sets and locales. Use it for legacy Foundation parsing, validating every scan result and considering Swift string indexing for new type-safe parsers.
- [IBInspectable / IBDesignable - NSHipster](https://nshipster.com/ibinspectable-ibdesignable) — 2015-02-02T00:00:00-08:00
  **NeKI brief:** IBInspectable and IBDesignable expose custom view configuration and previews in Interface Builder. Use them to shorten UIKit iteration, keeping inspectable properties simple because design-time rendering has a different runtime environment.
- [Swift & the Objective-C Runtime - NSHipster](https://nshipster.com/swift-objc-runtime) — 2015-01-26T00:00:00-08:00
  **NeKI brief:** Swift interoperates with the Objective-C runtime through dynamic dispatch, selectors and NSObject conventions. Use runtime features only where Cocoa integration requires them, retaining Swift-native types and static dispatch elsewhere.
- [NSUndoManager - NSHipster](https://nshipster.com/nsundomanager) — 2014-12-15T00:00:00-08:00
  **NeKI brief:** UndoManager groups reversible user operations into commands that can be undone and redone. Use explicit grouping around meaningful edits, defining inverse operations carefully so undo restores a valid model state.
- [Pay - NSHipster](https://nshipster.com/apple-pay) — 2014-12-08T00:00:00-08:00
  **NeKI brief:** Apple Pay delegates payment authorization to system UI and tokenized payment data. Use it to reduce handling of sensitive card information, implementing merchant validation, server-side processing and clear cancellation states correctly.
- [WatchKit - NSHipster](https://nshipster.com/watchkit) — 2014-12-01T00:00:00-08:00
  **NeKI brief:** WatchKit introduced watch-specific UI, lifecycle and communication patterns distinct from an iPhone app. Use this historical guide when reading legacy watch code, preferring current watchOS architecture guidance for new development.
- [UIPrintInteractionController - NSHipster](https://nshipster.com/uiprintinteractioncontroller) — 2014-11-17T00:00:00-08:00
  **NeKI brief:** UIPrintInteractionController presents platform printing UI for documents, images and formatters. Use it to delegate printer selection and job configuration to iOS, supplying correctly sized printable content and completion handling.
- [Core Location in iOS 8 - NSHipster](https://nshipster.com/core-location-in-ios-8) — 2014-11-10T00:00:00-08:00
  **NeKI brief:** Core Location authorization and background behavior changed substantially in iOS 8. Use this as legacy context, but implement current permission descriptions, accuracy choices and authorization flows from up-to-date documentation.
- [UISplitViewController - NSHipster](https://nshipster.com/uisplitviewcontroller) — 2014-11-03T00:00:00-08:00
  **NeKI brief:** UISplitViewController coordinates primary and detail content across compact and regular layouts. Use it to express content hierarchy adaptively, letting the system collapse and expand rather than manually maintaining parallel navigation stacks.
- [CMDeviceMotion - NSHipster](https://nshipster.com/cmdevicemotion) — 2014-10-28T00:00:00-07:00
  **NeKI brief:** CMDeviceMotion delivers fused accelerometer, gyroscope and magnetometer data for motion-aware features. Use appropriate update intervals and reference frames, stopping updates promptly to avoid battery cost and misleading sensor assumptions.
- [Inter-Process Communication - NSHipster](https://nshipster.com/inter-process-communication) — 2014-10-17T00:00:00-07:00
  **NeKI brief:** Inter-process communication on Apple platforms crosses explicit boundaries such as extensions, services and URL schemes. Use the narrowest supported mechanism, validate all received data and never assume the other process is trusted.
- [Swift System Version Checking - NSHipster](https://nshipster.com/swift-system-version-checking) — 2014-10-06T00:00:00-07:00
  **NeKI brief:** Availability checks let one source base adopt newer APIs while retaining older deployment targets. Use language-supported availability conditions and fallbacks close together, avoiding manual version-string comparisons that miss platform nuance.
- [UIAlertController - NSHipster](https://nshipster.com/uialertcontroller) — 2014-09-30T00:00:00-07:00
  **NeKI brief:** UIAlertController presents alerts and action sheets with platform-consistent behavior and accessibility. Use it for short decisions or input, assigning destructive actions accurately and avoiding it as a substitute for a full workflow.
- [Equatable and Comparable - NSHipster](https://nshipster.com/equatable-and-comparable) — 2014-09-22T00:00:00-07:00
  **NeKI brief:** Equatable defines value equality and Comparable adds a consistent ordering relation. Use both only when the semantics are stable and transitive, ensuring ordering and equality do not disagree for values used in sets or sorting.
- [OptionSet - NSHipster](https://nshipster.com/optionset) — 2014-09-08T00:00:00-07:00
  **NeKI brief:** OptionSet represents combinable flags with a type-safe Swift interface over bit patterns. Use it for independent capabilities that may coexist, avoiding enums when callers must select more than one case.
- [Swift Default Protocol Implementations - NSHipster](https://nshipster.com/swift-default-protocol-implementations) — 2014-09-02T00:00:00-07:00
  **NeKI brief:** Protocol extensions provide shared default behavior while letting conforming types override selected requirements. Use defaults to reduce repetition, but understand static versus dynamic dispatch so specialized behavior is actually invoked as intended.
- [WKWebView - NSHipster](https://nshipster.com/wkwebview) — 2014-08-24T00:00:00-07:00
  **NeKI brief:** Explains WKWebView configuration, navigation, and JavaScript interaction in modern iOS apps. Follow it when embedding web content and deciding which process, security, and message-passing boundaries the native layer owns.
- [Swift Literals - NSHipster](https://nshipster.com/swift-literals) — 2014-08-18T00:00:00-07:00
  **NeKI brief:** Swift literal protocols allow custom types to be initialized with concise literal syntax. Use them when literals clearly map to a stable domain concept, avoiding convenience syntax that hides validation or surprising defaults.
- [Swift Operators - NSHipster](https://nshipster.com/swift-operators) — 2014-08-11T00:00:00-07:00
  **NeKI brief:** Custom Swift operators can make domain expressions concise, but also introduce unfamiliar parsing and semantics. Use them only for well-known algebraic operations, providing documented precedence and named alternatives where clarity matters.
- [XCTestCase /XCTestExpectation / measureBlock() - NSHipster](https://nshipster.com/xctestcase) — 2014-07-21T00:00:00-07:00
  **NeKI brief:** XCTestCase organizes setup, assertions, expectations and performance measurement around isolated test scenarios. Use expectations for asynchronous completion and deterministic fixtures, keeping tests focused on behavior instead of implementation timing.
- [NSOperation - NSHipster](https://nshipster.com/nsoperation) — 2014-07-14T00:00:00-07:00
  **NeKI brief:** Operation models a cancellable unit of work with dependencies and execution state. Use it when scheduling needs more structure than a queue closure, implementing KVO-compliant state transitions correctly for asynchronous subclasses.
- [iOS 8 - NSHipster](https://nshipster.com/ios8) — 2014-06-09T00:00:00-07:00
  **NeKI brief:** This iOS 8 API tour examines LocalAuthentication, WKWebView, NSQualityOfService, HealthKit statistics, motion data and Foundation formatter additions. Use it to decode legacy code paths, verifying modern availability and privacy requirements before reuse.
- [CocoaPods - NSHipster](https://nshipster.com/cocoapods) — 2014-05-26T00:00:00-07:00
  **NeKI brief:** CocoaPods resolves and integrates third-party dependencies into Xcode projects. Use declared versions and reproducible lockfiles for legacy projects, assessing package-manager migration separately from routine feature work.
- [Benchmarking - NSHipster](https://nshipster.com/benchmarking) — 2014-05-19T00:00:00-07:00
  **NeKI brief:** A useful benchmark controls compiler mode, inputs, warm-up and repetition before comparing implementations. Use it to answer one performance question at a time, corroborating measurements with profiling when a change affects architecture.
- [IBAction / IBOutlet / IBOutletCollection - NSHipster](https://nshipster.com/ibaction-iboutlet-iboutletcollection) — 2014-05-05T00:00:00-07:00
  **NeKI brief:** IBAction and IBOutlet connect Interface Builder objects to UIKit code through runtime wiring. Use typed, minimal outlets and actions, validating connections during refactors so storyboard identifiers do not become hidden failure points.
- [MKGeodesicPolyline - NSHipster](https://nshipster.com/mkgeodesicpolyline) — 2014-04-28T00:00:00-07:00
  **NeKI brief:** MKGeodesicPolyline draws a curved route that follows the earth's surface between coordinates. Use it for long-distance map visualization, choosing a different overlay when users need road routing or locally accurate paths.
- [UIActivityViewController - NSHipster](https://nshipster.com/uiactivityviewcontroller) — 2014-04-21T00:00:00-07:00
  **NeKI brief:** UIActivityViewController offers system and extension-provided sharing actions for supplied items. Use it to avoid hand-built share menus, excluding unsuitable activity types only when product requirements genuinely demand it.
- [Xcode Plugins - NSHipster](https://nshipster.com/xcode-plugins) — 2014-04-14T00:00:00-07:00
  **NeKI brief:** Xcode plug-ins historically extended the IDE through unsupported loading mechanisms. Use this only as legacy context; prefer supported extensions, Source Editor commands and external tooling for maintainable modern workflows.
- [Configuration Profiles - NSHipster](https://nshipster.com/configuration-profiles) — 2014-04-07T00:00:00-07:00
  **NeKI brief:** Explains iOS configuration profiles as a managed distribution mechanism for settings and restrictions. Useful for enterprise deployments where device configuration must be explicit, reviewable, and separate from app code.
- [AVSpeechSynthesizer - NSHipster](https://nshipster.com/avspeechsynthesizer) — 2014-03-31T00:00:00-07:00
  **NeKI brief:** Introduces AVSpeechSynthesizer for spoken output using system voices and utterances. Useful for accessibility or guided experiences where speech configuration should remain distinct from presentation state.
- [NSURL /NSURLComponents - NSHipster](https://nshipster.com/nsurl) — 2014-03-24T00:00:00-07:00
  **NeKI brief:** Explains URL parsing and construction with NSURL and NSURLComponents. Useful for keeping scheme, host, path, and query manipulation structured instead of assembling fragile URL strings.
- [Dictionary Services - NSHipster](https://nshipster.com/dictionary-services) — 2014-03-10T00:00:00-07:00
  **NeKI brief:** Dictionary Services can look up definitions and related linguistic information in macOS. Use it for optional user-facing reference features, handling unavailable dictionaries and keeping lookup results separate from authoritative app data.
- [Temporary Files - NSHipster](https://nshipster.com/temporary-files) — 2014-03-03T00:00:00-08:00
  **NeKI brief:** Discusses temporary-file lifetimes and cleanup in Cocoa applications. Useful for designing short-lived export, download, or transformation workflows without confusing cacheable artifacts with durable user data.
- [Namespacing - NSHipster](https://nshipster.com/namespacing) — 2014-02-24T00:00:00-08:00
  **NeKI brief:** Namespacing prevents unrelated types and symbols from colliding as a codebase grows. Use modules, nested types and clear prefixes at Objective-C boundaries, avoiding artificial namespaces that obscure ownership.
- [Method Swizzling - NSHipster](https://nshipster.com/method-swizzling) — 2014-02-17T00:00:00-08:00
  **NeKI brief:** Method swizzling replaces Objective-C method implementations at runtime and can alter framework behavior globally. Use it only as a tightly tested last resort, accounting for inheritance, thread safety and future OS changes.
- [Associated Objects - NSHipster](https://nshipster.com/associated-objects) — 2014-02-10T00:00:00-08:00
  **NeKI brief:** Explains Objective-C associated objects and their runtime storage semantics. Useful historical context for legacy extensions, while making the hidden ownership and keying risks explicit before adoption.
- [MKTileOverlay,MKMapSnapshotter &MKDirections - NSHipster](https://nshipster.com/mktileoverlay-mkmapsnapshotter-mkdirections) — 2014-02-03T00:00:00-08:00
  **NeKI brief:** MapKit overlays, snapshots and directions APIs support custom map rendering and route visualization. Use the service appropriate to the feature, respecting network latency, cache policy and attribution requirements in the UI.
- [Extended File Attributes - NSHipster](https://nshipster.com/extended-file-attributes) — 2014-01-20T00:00:00-08:00
  **NeKI brief:** Extended attributes attach metadata to filesystem items outside their visible contents. The article is useful for understanding Finder tags and quarantine-like data, while preserving attributes intentionally during file copy and export workflows.
- [NSRange - NSHipster](https://nshipster.com/nsrange) — 2014-01-13T00:00:00-08:00
  **NeKI brief:** NSRange represents UTF-16-based locations used by many Foundation APIs. Follow it when bridging Swift String indices to Objective-C interfaces, where Unicode grapheme boundaries make integer offsets unsafe.
- [UIApplicationDelegate launchOptions - NSHipster](https://nshipster.com/launch-options) — 2013-12-16T00:00:00-08:00
  **NeKI brief:** Application launch options expose the cause of an iOS app startup, such as a notification or URL. The guide is useful for routing at the lifecycle boundary before scene-based APIs take over navigation responsibility.
- [Multipeer Connectivity - NSHipster](https://nshipster.com/multipeer-connectivity) — 2013-12-09T00:00:00-08:00
  **NeKI brief:** Multipeer Connectivity discovers nearby peers and exchanges data over local transports. Follow it to model invitations, sessions and unreliable proximity, rather than assuming cloud-style connectivity or identity guarantees.
- [NSNotification &NSNotificationCenter - NSHipster](https://nshipster.com/nsnotification-and-nsnotificationcenter) — 2013-12-02T00:00:00-08:00
  **NeKI brief:** NotificationCenter broadcasts decoupled events without direct object references. The article is useful for system-wide signals, while emphasizing observer lifetime and avoiding notifications as an untraceable substitute for ownership.
- [FileManager - NSHipster](https://nshipster.com/filemanager) — 2013-11-18T00:00:00-08:00
  **NeKI brief:** FileManager handles file creation, moves, copies and directory traversal through URL-based APIs. Follow it when implementing storage features, with sandbox locations, coordination and errors treated as part of the design.
- [Launch Arguments & Environment Variables - NSHipster](https://nshipster.com/launch-arguments-and-environment-variables) — 2013-10-21T00:00:00-07:00
  **NeKI brief:** Launch arguments and environment variables configure Xcode test and debug runs without code changes. Follow it to inject deterministic feature flags or fixtures, keeping production defaults and secrets out of schemes.
- [NSError - NSHipster](https://nshipster.com/nserror) — 2013-10-14T00:00:00-07:00
  **NeKI brief:** NSError carries domain, code and userInfo context across Objective-C APIs. The article is useful when bridging to Swift Error, preserving recoverable information instead of flattening failures into display strings.
- [Key-Value Observing - NSHipster](https://nshipster.com/key-value-observing) — 2013-10-07T00:00:00-07:00
  **NeKI brief:** Key-Value Observing reports dynamic property changes from Objective-C-compatible objects. Follow it for legacy Cocoa integration, but manage observer lifetime and prefer typed observation mechanisms for new Swift code.
- [Xcode Key Bindings & Gestures - NSHipster](https://nshipster.com/xcode-key-bindings-and-gestures) — 2013-09-30T00:00:00-07:00
  **NeKI brief:** Xcode key bindings and gestures can reduce repetitive editing friction. Use team-neutral conventions for shared instructions and keep personalized shortcuts documented only when they affect reproducible project workflows.
- [iOS 7 - NSHipster](https://nshipster.com/ios7) — 2013-09-23T00:00:00-07:00
  **NeKI brief:** This iOS 7 API tour covers Base64 data encoding, URL components, NSProgress, metadata capture, Safari Reading List, speech synthesis and distance formatting. Use it as legacy context while replacing obsolete patterns with current frameworks.
- [Network Link Conditioner - NSHipster](https://nshipster.com/network-link-conditioner) — 2013-09-09T00:00:00-07:00
  **NeKI brief:** Network Link Conditioner simulates bandwidth, latency and packet loss on Apple platforms. Follow it to test failure and loading states under realistic conditions instead of assuming simulator or office Wi-Fi behavior.
- [Xcode Snippets - NSHipster](https://nshipster.com/xcode-snippets) — 2013-09-02T00:00:00-07:00
  **NeKI brief:** Xcode snippets package recurring code patterns for quick editor insertion. Use them for personal boilerplate with placeholders, keeping project-wide patterns in templates or generators where version control and review are possible.
- [Equality - NSHipster](https://nshipster.com/equality) — 2013-08-26T00:00:00-07:00
  **NeKI brief:** Examines equality as a domain-modeling decision rather than a trivial operator choice. Useful for defining identity and value comparison consistently before collections, caches, and diffing rely on it.
- [NSHashTable & NSMapTable - NSHipster](https://nshipster.com/nshashtable-and-nsmaptable) — 2013-08-19T00:00:00-07:00
  **NeKI brief:** NSHashTable and NSMapTable provide Foundation collections with weak references and custom memory behavior. Use them for Objective-C interoperability or weak registries, choosing ownership semantics deliberately and pruning nil entries.
- [rand(3) / random(3) / arc4random(3) / et al. - NSHipster](https://nshipster.com/random) — 2013-08-12T00:00:00-07:00
  **NeKI brief:** Compares C and Objective-C random-number facilities and their pitfalls. Useful historical context when replacing weak or biased random generation with APIs appropriate to simulation or security needs.
- [Objective-C Documentation - NSHipster](https://nshipster.com/objective-c-documentation) — 2013-08-05T00:00:00-07:00
  **NeKI brief:** Objective-C documentation conventions make selectors, ownership and nullability understandable to Swift and Objective-C callers. Use precise parameter and return descriptions, maintaining them as contracts rather than historical commentary.
- [UIMenuController - NSHipster](https://nshipster.com/uimenucontroller) — 2013-07-22T00:00:00-07:00
  **NeKI brief:** UIMenuController is a legacy UIKit API for text-selection and contextual edit actions. Use it only when maintaining older code; adopt current menu and command APIs for new context-menu behavior.
- [NSPredicate - NSHipster](https://nshipster.com/nspredicate) — 2013-07-15T00:00:00-07:00
  **NeKI brief:** Explains NSPredicate's query syntax for filtering and fetching collections. Useful for expressing selection declaratively while keeping predicate-format construction, validation, and data-store semantics visible.
- [NSExpression - NSHipster](https://nshipster.com/nsexpression) — 2013-07-08T00:00:00-07:00
  **NeKI brief:** NSExpression evaluates key-path and operator expressions used by predicates and aggregations. Use it only with trusted, constrained inputs, since opaque expression strings make validation and debugging harder than typed transformations.
- [NSFastEnumeration / NSEnumerator - NSHipster](https://nshipster.com/enumerators) — 2013-07-01T00:00:00-07:00
  **NeKI brief:** Foundation enumeration APIs traverse collections with explicit iterator state. Use Swift's for-in and Sequence abstractions in new code, keeping enumerators for Cocoa interop or when a legacy API exposes them directly.
- [NSUUID /CFUUIDRef /UIDevice -uniqueIdentifier /-identifierForVendor - NSHipster](https://nshipster.com/uuid-udid-unique-identifier) — 2013-06-24T00:00:00-07:00
  **NeKI brief:** UUID values provide app-generated identifiers without exposing a device-wide stable identifier. Use them for object identity and installation-scoped records, respecting platform privacy rules and never rebuilding deprecated device tracking.
- [Object Subscripting - NSHipster](https://nshipster.com/object-subscripting) — 2013-06-17T00:00:00-07:00
  **NeKI brief:** Objective-C object subscripting maps bracket syntax to keyed or indexed accessor methods. Use it for concise collection access in legacy code, preserving nil and bounds behavior that callers can reason about.
- [NSDataDetector - NSHipster](https://nshipster.com/nsdatadetector) — 2013-06-02T00:00:00-07:00
  **NeKI brief:** Introduces NSDataDetector for recognizing dates, addresses, links, and similar content in text. Useful for enriching user-entered content with system parsing rather than maintaining brittle regular-expression sets.
- [Unit Testing - NSHipster](https://nshipster.com/unit-testing) — 2013-05-27T00:00:00-07:00
  **NeKI brief:** Unit tests verify small behavior units with controlled dependencies and deterministic inputs. Use them to protect decisions and edge cases, distinguishing them from integration tests that exercise actual framework or network boundaries.
- [NSCoding / NSKeyedArchiver - NSHipster](https://nshipster.com/nscoding) — 2013-05-13T00:00:00-07:00
  **NeKI brief:** Explains NSCoding and keyed archiving for reconstructing persisted object graphs. Useful historical context when maintaining archive-based storage or planning a deliberate migration to a modern persistence format.
- [MKLocalSearch - NSHipster](https://nshipster.com/mklocalsearch) — 2013-04-29T00:00:00-07:00
  **NeKI brief:** MKLocalSearch queries MapKit's local place index for user-entered search terms. Use debouncing, cancellation and result presentation that distinguishes search suggestions from authoritative navigation or address validation.
- [NSSecureCoding - NSHipster](https://nshipster.com/nssecurecoding) — 2013-04-15T00:00:00-07:00
  **NeKI brief:** Covers NSSecureCoding's class validation during keyed unarchiving. Useful for treating archived input as untrusted and restricting the types that can re-enter an application's object graph.
- [BOOL / bool / Boolean / NSCFBoolean - NSHipster](https://nshipster.com/bool) — 2013-04-08T00:00:00-07:00
  **NeKI brief:** Boolean bridging spans C, Objective-C and Swift representations with different historical types and conventions. Use Swift Bool at application boundaries, converting explicitly when a C or Objective-C API requires another form.
- [iCloud - NSHipster](https://nshipster.com/icloud) — 2013-04-01T00:00:00-07:00
  **NeKI brief:** iCloud services synchronize selected app data through distinct APIs with different conflict and availability behavior. Use the service that matches the data model, designing offline states and merge policy rather than assuming instant consistency.
- [Search Kit - NSHipster](https://nshipster.com/search-kit) — 2013-03-25T00:00:00-07:00
  **NeKI brief:** Search Kit is a legacy macOS text-indexing API for local search. Use it as maintenance context only, evaluating supported modern indexing or Core Spotlight APIs for new searchable content.
- [C Storage Classes - NSHipster](https://nshipster.com/c-storage-classes) — 2013-03-18T00:00:00-07:00
  **NeKI brief:** C storage classes control linkage, duration and visibility of variables and functions. Use them when reading or bridging C code, keeping Swift-facing interfaces narrow so C lifetime rules do not leak widely.
- [UIAppearance - NSHipster](https://nshipster.com/uiappearance) — 2013-03-11T00:00:00-07:00
  **NeKI brief:** UIAppearance applies default UIKit styling through appearance proxies before views are displayed. Use it for broad consistent theming, testing containment and lifecycle behavior rather than expecting it to override every instance property.
- [NSAssertionHandler - NSHipster](https://nshipster.com/nsassertionhandler) — 2013-02-25T00:00:00-08:00
  **NeKI brief:** Assertion handling surfaces programmer-contract violations during development. Use assertions for impossible states and diagnostics, never for recoverable user or network errors that require a production fallback.
- [NSURLCache - NSHipster](https://nshipster.com/nsurlcache) — 2013-02-11T00:00:00-08:00
  **NeKI brief:** URLCache stores HTTP responses according to cache policy and headers. Use it to reduce repeat network work, validating cache-control behavior and privacy expectations before persisting authenticated or sensitive responses.
- [Type Encodings - NSHipster](https://nshipster.com/type-encodings) — 2013-02-04T00:00:00-08:00
  **NeKI brief:** Explains Objective-C type-encoding strings as compact runtime metadata for method signatures, properties, and invocation. Use it when bridging reflection or generated interfaces, while treating the legacy syntax as version-sensitive implementation detail.
- [NSValue - NSHipster](https://nshipster.com/nsvalue) — 2013-01-28T00:00:00-08:00
  **NeKI brief:** Shows how NSValue boxes scalars, structs, and geometry for Objective-C collections and APIs. Follow it when auditing mixed Swift/Objective-C boundaries, choosing Codable or native Swift values where modern code can avoid boxing.
- [NSLocalizedString - NSHipster](https://nshipster.com/nslocalizedstring) — 2013-01-21T00:00:00-08:00
  **NeKI brief:** Explains NSLocalizedString lookup through string tables, bundle context, and developer comments. Use it to review localization keys and fallback behavior in older UIKit code, then compare with current String Catalog workflows.
- [__attribute__ - NSHipster](https://nshipster.com/__attribute__) — 2013-01-14T00:00:00-08:00
  **NeKI brief:** Surveys Clang __attribute__ annotations that influence diagnostics, availability, ownership, and API import behavior. Follow it when maintaining Objective-C headers or generated Swift interfaces, verifying each annotation against the active compiler and SDK.
- [nil / Nil / NULL / NSNull - NSHipster](https://nshipster.com/nil) — 2013-01-07T00:00:00-08:00
  **NeKI brief:** Distinguishes nil, Nil, NULL, and NSNull across Objective-C pointers, class references, C values, and collection placeholders. Use it to diagnose mixed-language nullability bugs instead of treating every empty value as interchangeable.
- [instancetype - NSHipster](https://nshipster.com/instancetype) — 2012-12-10T00:00:00-08:00
  **NeKI brief:** Explains Objective-C instancetype return typing so initializers and factory methods preserve the dynamic receiver type. Follow it when auditing legacy APIs imported into Swift, where generic self-types and availability still affect call-site safety.
- [KVC Collection Operators - NSHipster](https://nshipster.com/kvc-collection-operators) — 2012-12-03T00:00:00-08:00
  **NeKI brief:** Uses Key-Value Coding collection operators to aggregate, filter, and transform object properties without manual loops. Treat it as legacy Objective-C machinery and verify key paths, nil handling, and Swift alternatives before reuse.
- [NSOrderedSet - NSHipster](https://nshipster.com/nsorderedset) — 2012-11-26T00:00:00-08:00
  **NeKI brief:** Explains NSOrderedSet as a unique collection with stable ordering, distinct from NSSet and NSArray semantics. Use it when mapping Core Data or Objective-C models, checking equality, ordering, and Swift collection conversions.
- [NS_ENUM & NS_OPTIONS - NSHipster](https://nshipster.com/ns_enum-ns_options) — 2012-11-19T00:00:00-08:00
  **NeKI brief:** Shows how NS_ENUM and NS_OPTIONS encode typed enumerations and bitmask flags in Objective-C headers. Follow it when designing interoperable APIs, preserving option composition and ensuring Swift imports the intended names and raw values.
- [ValueTransformer - NSHipster](https://nshipster.com/valuetransformer) — 2012-11-12T00:00:00-08:00
  **NeKI brief:** Describes ValueTransformer as a boundary for converting model values to persisted or transport representations. Use it when maintaining Core Data transformations, checking registration, reversibility, and compatibility with modern Codable or transformable attributes.
- [NSURLProtocol - NSHipster](https://nshipster.com/nsurlprotocol) — 2012-11-05T00:00:00-08:00
  **NeKI brief:** Explains NSURLProtocol as an interception point in Foundation's URL loading system. Useful for controlled request stubbing, custom schemes, or diagnostics where global interception behavior must be bounded carefully.
- [UILocalizedIndexedCollation - NSHipster](https://nshipster.com/uilocalizedindexedcollation) — 2012-10-29T00:00:00-07:00
  **NeKI brief:** Uses UILocalizedIndexedCollation to build locale-aware section indexes for large table views. Follow it when supporting legacy contact or catalog screens, verifying collation titles, section ordering, and modern list alternatives.
- [NSLinguisticTagger - NSHipster](https://nshipster.com/nslinguistictagger) — 2012-10-22T00:00:00-07:00
  **NeKI brief:** Explains NSLinguisticTagger APIs for tokenization, language identification, lexical classes, and sentence boundaries. Use it for legacy text-analysis pipelines, validating locale support and replacing deprecated behavior with current Natural Language APIs where appropriate.
- [AddressBookUI - NSHipster](https://nshipster.com/addressbookui) — 2012-10-15T00:00:00-07:00
  **NeKI brief:** Covers AddressBookUI controllers for displaying, selecting, editing, and creating contacts. Follow it only when maintaining legacy contact flows; modern implementations should compare Contacts framework authorization and picker APIs.
- [#pragma - NSHipster](https://nshipster.com/pragma) — 2012-10-01T00:00:00-07:00
  **NeKI brief:** Shows how #pragma directives communicate compiler-specific intent, diagnostics, and organization in Objective-C. Use it when interpreting legacy headers, distinguishing actionable warnings from editor-only grouping, and checking portability across compilers.
- [UICollectionView - NSHipster](https://nshipster.com/uicollectionview) — 2012-09-24T00:00:00-07:00
  **NeKI brief:** Introduces UICollectionView layout, data-source, and reusable-cell primitives for grid and custom collection interfaces. Follow it when maintaining UIKit screens, then verify modern diffable data sources, compositional layouts, and cell registration choices.
- [CharacterSet - NSHipster](https://nshipster.com/characterset) — 2012-09-17T00:00:00-07:00
  **NeKI brief:** Explains CharacterSet as a Unicode scalar set used for trimming, filtering, and searching strings, not a collection of Swift Character values. Use it to avoid grapheme/scalar confusion in text-processing code.
- [UIAccessibility - NSHipster](https://nshipster.com/uiaccessibility) — 2012-09-10T00:00:00-07:00
  **NeKI brief:** Surveys UIKit's UIAccessibility model, including element properties and notifications that shape VoiceOver interaction. Follow it as a conceptual map when custom UIKit views need explicit semantic exposure beyond Interface Builder labels.
- [Locale - NSHipster](https://nshipster.com/locale) — 2012-09-03T00:00:00-07:00
  **NeKI brief:** Explains Locale as the runtime context for language, region, and user preferences rather than a formatting constant. Its accessibility value is ensuring spoken labels and displayed values respect the user's locale assumptions.
- [CFBag - NSHipster](https://nshipster.com/cfbag) — 2012-08-27T00:00:00-07:00
  **NeKI brief:** Describes CFBag as an unordered Core Foundation collection that permits duplicate values. Follow it when interoperating with C APIs, checking callback ownership and equality semantics before choosing a native Swift collection.
- [CFStringTransform - NSHipster](https://nshipster.com/cfstringtransform) — 2012-08-06T00:00:00-07:00
  **NeKI brief:** Uses CFStringTransform for locale-aware transliteration and string transformations through mutable CFString values. Follow it for legacy text normalization, verifying transform identifiers and Unicode behavior against current Foundation APIs.
- [DateComponents - NSHipster](https://nshipster.com/datecomponents) — 2012-07-31T00:00:00-07:00
  **NeKI brief:** Explains DateComponents as context-dependent calendar fields rather than a complete instant. Use it to review date construction and matching, keeping calendar, time zone, and missing-component semantics explicit.
- [NSSortDescriptor - NSHipster](https://nshipster.com/nssortdescriptor) — 2012-07-24T00:00:00-07:00
  **NeKI brief:** Uses NSSortDescriptor to describe property- or selector-based ordering for Cocoa collections and persistence queries. Follow it when maintaining Objective-C/Core Data sorting, checking key paths and stable ordering before Swift sort closures.
- [NSCache - NSHipster](https://nshipster.com/nscache) — 2012-07-14T00:00:00-07:00
  **NeKI brief:** NSCache provides memory-sensitive object caching with automatic eviction behavior. The guide is useful for avoiding unbounded dictionaries, while treating cached values as disposable and retaining a correct source of truth.
- [NSIndexSet - NSHipster](https://nshipster.com/nsindexset) — 2012-07-07T00:00:00-07:00
  **NeKI brief:** Explains NSIndexSet as a sorted set of non-contiguous integer indexes, useful for batch selection and range operations. Follow it in legacy UIKit data-source code, verifying mutation and index validity across updates.
