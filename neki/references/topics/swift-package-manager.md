# Swift Package Manager

Third-party reading leads collected from NeKI sources. The links may be useful perspectives, but are not vetted recommendations or authoritative API guidance. NeKI publishes routing metadata, not the linked articles' text.

**Scope:** Swift packages, manifests, plugins, dependency resolution, and package distribution.

- Last collected: `2026-08-27T19:22:09Z`
- Indexed links shown: **317**

## Direct-source reading

- [Swift Package Manager for iOS | Kodeco](https://www.kodeco.com/7242045-swift-package-manager-for-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** A practical SwiftPM tour covers creating, updating, and consuming local or remote packages, clarifying the dependency workflow for an iOS project.
- [Sharing and Editing Swift Packages With Swift Package Manager | Kodeco](https://www.kodeco.com/4167538-sharing-and-editing-swift-packages-with-swift-package-manager) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Shares and edits Swift packages through Swift Package Manager workflows. Useful for maintaining local package development without losing the dependency graph and reproducibility of package-based integration.
- [Swift Package Manager: Creating a Swift Package | Kodeco](https://www.kodeco.com/4047936-swift-package-manager-creating-a-swift-package) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Creates a Swift package with manifest, targets, tests, and dependencies. Useful for establishing a reusable module boundary that can build and test independently of an app project.
- [Moving From Cocoapods to Swift Package Manager | Kodeco](https://www.kodeco.com/3949145-moving-from-cocoapods-to-swift-package-manager) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Migrates dependencies from CocoaPods to Swift Package Manager and addresses project integration changes. Useful for planning the boundary between package declaration, Xcode project settings, and reproducible dependency resolution.
- [Multi-Language Support with Localization in iOS | Kodeco](https://www.kodeco.com/20755921-multi-language-support-with-localization-in-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Builds multi-language support through localized resources and runtime-aware presentation. Useful for designing localization as data and formatting infrastructure rather than a late translation pass over hard-coded user interface strings.
- [An Introduction to Swift Package Manager | Kodeco](https://www.kodeco.com/1993018-an-introduction-to-swift-package-manager) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Swift Package Manager is introduced through a small Swift project and dependency workflow. It is useful for understanding package manifests, targets and products before modularizing an app or migrating away from older dependency managers.
- [Introduction to Open Source Swift on Linux | Kodeco](https://www.kodeco.com/1448-introduction-to-open-source-swift-on-linux) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Installs Swift on Linux through a virtual machine, compiles a program, and uses the Swift Package Manager. Useful historical context for understanding what server-side Swift portability requires outside Apple's development toolchain.
- [Getting Started with Server-Side Swift with Vapor 4 | Kodeco](https://www.kodeco.com/11555468-getting-started-with-server-side-swift-with-vapor-4) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** A Vapor 4 starter builds a first server-side Swift application and exposes the framework’s routing and request lifecycle. It is useful for assessing code sharing with iOS while keeping deployment, persistence and server security as separate concerns.
- [Nuke Tutorial for iOS: Getting Started | Kodeco](https://www.kodeco.com/11070743-nuke-tutorial-for-ios-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Configures Nuke's image pipeline, caching, memory observation, request options, and Combine publisher integration. Useful for deciding where remote-image loading should centralize cancellation, cache policy, and decoding instead of scattering URLSession work through views.
- [David Okun: How To Build a SwiftUI Framework | Kodeco](https://www.kodeco.com/10528084-david-okun-how-to-build-a-swiftui-framework) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This talk follows a SwiftUI component from reusable code to distribution through SwiftPM, CocoaPods, and Carthage, making packaging trade-offs visible.
- [“Trait-ifying” our libraries to reduce transitive dependencies](https://www.pointfree.co/blog/posts/216-trait-ifying-our-libraries-to-reduce-transitive-dependencies) — Point-Free · article catalogue
  **Published:** `2026-06-24T00:00:00Z`
  **NeKI brief:** Applies SwiftPM traits to make optional library features opt-in, using SwiftNavigation as the test case. Follow it when reducing transitive dependencies while weighing package configuration complexity against smaller builds.
- [HealthKit Data Generator: Swift Package for Generating Realistic HealthKit Data - iOS Dev Tools](https://iosdev.tools/blog/healthkit-data-generator) — iOS Dev Tools Blog · article catalogue
  **Published:** `2026-03-16T12:10:00+00:00`
  **NeKI brief:** Profiles HealthKit Data Generator as swift Package for Generating Realistic HealthKit Data. Use it when evaluating whether this tool or package fits an Apple-platform development, testing, or delivery workflow.
- [Hard Deprecations and Soft Landings with SwiftPM Traits](https://www.pointfree.co/blog/posts/203-hard-deprecations-and-soft-landings-with-swiftpm-traits) — Point-Free · article catalogue
  **Published:** `2026-03-16T00:00:00Z`
  **NeKI brief:** SwiftPM traits can keep a deprecated feature available as an opt-in while the default product removes its dependency, creating a soft migration before a hard break. The pattern balances source compatibility against leaner builds.
- [GradientEditor: An Open-Source Swift Package for Editing Gradients - iOS Dev Tools](https://iosdev.tools/blog/gradienteditor) — iOS Dev Tools Blog · article catalogue
  **Published:** `2026-02-23T13:00:00+00:00`
  **NeKI brief:** Profiles GradientEditor as an Open-Source Swift Package for Editing Gradients. Use it when evaluating whether this tool or package fits an Apple-platform development, testing, or delivery workflow.
- [When To Kill A Project](https://blog.jacobstechtavern.com/p/when-to-kill-a-project) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2025-11-20T16:01:51.473Z`
  **NeKI brief:** Discusses signals and decision criteria for ending an app project when its costs, risks, or opportunity trade-offs no longer make sense. Useful as a product-engineering reflection before continuing sunk-cost work or reallocating a small team.
- [Build performance analysis for speeding up Xcode builds - SwiftLee](https://www.avanderlee.com/optimization/analysing-build-performance-xcode) — Antoine van der Lee articles · article catalogue
  **Published:** `2025-10-27T10:32:43+00:00`
  **NeKI brief:** Uses Xcode's build reports and timing data to identify slow compilation, then narrows work to expensive files, type checking, and dependency structure. The workflow turns an otherwise vague 'build is slow' complaint into measurable candidates.
- [Why Swift Migration Tooling Matters](https://www.avanderlee.com/concurrency/swift-migration-tooling-upcoming-swift-features) — Antoine van der Lee articles · article catalogue
  **Published:** `2025-10-14T07:26:08+00:00`
  **NeKI brief:** Explains how Swift migration tooling previews upcoming language changes and surfaces source edits needed for adoption. It is useful for planning incremental compiler migrations while distinguishing mechanical fixes from semantic concurrency decisions.
- [Treating Warnings As Errors In Swift Packages](https://useyourloaf.com/blog/treating-warnings-as-errors-in-swift-packages) — Use Your Loaf · article catalogue
  **Published:** `2025-09-01T12:02:15+01:00`
  **NeKI brief:** Configures Swift Package builds to treat warnings as errors. Use it to keep library quality gates strict, while staging adoption so existing warnings do not block unrelated migration work.
- [Approachable Concurrency in Swift Packages](https://useyourloaf.com/blog/approachable-concurrency-in-swift-packages) — Use Your Loaf · article catalogue
  **Published:** `2025-07-21T10:14:20+01:00`
  **NeKI brief:** Applies approachable concurrency settings to Swift packages and explains how target configuration changes diagnostics. Useful for aligning library and application migration plans.
- [SyntaxKit: More Friendly SwiftSyntax API - iOS Dev Tools](https://iosdev.tools/blog/syntaxkit) — iOS Dev Tools Blog · article catalogue
  **Published:** `2025-07-18T15:20:05+00:00`
  **NeKI brief:** Profiles SyntaxKit as more Friendly SwiftSyntax API. Use it when evaluating whether this tool or package fits an Apple-platform development, testing, or delivery workflow.
- [OAuthKit: OAuth 2.0, the Swift Way - iOS Dev Tools](https://iosdev.tools/blog/oauthkit) — iOS Dev Tools Blog · article catalogue
  **Published:** `2025-07-18T15:08:19+00:00`
  **NeKI brief:** Profiles OAuthKit as oAuth 2.0, the Swift Way. Use it when evaluating whether this tool or package fits an Apple-platform development, testing, or delivery workflow.
- [MoPromoteKit: Modern and Beautiful Way to Promote Your Apps - iOS Dev Tools](https://iosdev.tools/blog/mopromotekit) — iOS Dev Tools Blog · article catalogue
  **Published:** `2025-07-18T15:01:54+00:00`
  **NeKI brief:** Profiles MoPromoteKit as modern and Beautiful Way to Promote Your Apps. Use it when evaluating whether this tool or package fits an Apple-platform development, testing, or delivery workflow.
- [ChessKit: Swift, Strong, and Smart Chess Logic - iOS Dev Tools](https://iosdev.tools/blog/chesskit) — iOS Dev Tools Blog · article catalogue
  **Published:** `2025-07-18T14:44:38+00:00`
  **NeKI brief:** Profiles ChessKit as swift, Strong, and Smart Chess Logic. Use it when evaluating whether this tool or package fits an Apple-platform development, testing, or delivery workflow.
- [What is Approachable Concurrency in Xcode 26? – Donny Wals](https://www.donnywals.com/what-is-approachable-concurrency-in-xcode-26) — Donny Wals · article catalogue
  **Published:** `2025-07-09T11:00:33+00:00`
  **NeKI brief:** Explains Xcode 26's approachable concurrency settings and how default actor isolation changes migration ergonomics. Useful when staging strict concurrency adoption without immediately annotating every legacy declaration.
- [Sparkle: Distribution apps in- and out of the Mac App Store - SwiftLee](https://www.avanderlee.com/xcode/sparkle-distribution-apps-in-and-out-of-the-mac-app-store) — Antoine van der Lee articles · article catalogue
  **Published:** `2025-06-30T09:43:46+00:00`
  **NeKI brief:** Explains integrating Sparkle updates for macOS apps while retaining Mac App Store distribution, including signing and channel differences. It helps choose an update architecture that respects each distribution path’s constraints.
- [Documenting your code with DocC | Swift with Majid](https://swiftwithmajid.com/2025/04/01/documenting-your-code-with-docc) — Swift with Majid · article catalogue
  **Published:** `2025-04-01T00:00:00+00:00`
  **NeKI brief:** Uses DocC to document modular Swift packages, where separate targets need navigable symbols and tutorials. The workflow turns documentation into a distributable module artifact, making API contracts discoverable instead of relying on repository context.
- [Setting the Swift Language mode for an SPM Package – Donny Wals](https://www.donnywals.com/setting-the-swift-language-mode-for-an-spm-package) — Donny Wals · article catalogue
  **Published:** `2024-08-21T17:59:32+00:00`
  **NeKI brief:** An SPM package's tools version and swiftLanguageModes determine which compiler rules apply, allowing staged Swift 6 adoption but risking inconsistent settings across package targets.
- [Techniques for Automatic Merging of String Catalogs in Multi-Package Monorepos](https://fatbobman.com/en/posts/merging-swift-string-catalogs-in-a-multi-package-monorepo) — Fatbobman · article catalogue
  **Published:** `2024-07-12T00:12:00.000Z`
  **NeKI brief:** A build-phase script gathers String Catalogs emitted by package targets and merges them into the app catalog automatically. This keeps package-local localization ownership while producing one App Store-facing resource without manual synchronization.
- [Swift Package Manager framework creation in Xcode - SwiftLee](https://www.avanderlee.com/swift/creating-swift-package-manager-framework) — Antoine van der Lee articles · article catalogue
  **Published:** `2024-06-04T08:10:16+00:00`
  **NeKI brief:** Creates a Swift package in Xcode and covers Package.swift configuration, platform requirements, dependencies, and local development-package workflows.
- [Building a Swift package using the Swift 6 language mode](https://www.polpiella.dev/swift-6-language-mode) — Pol Piella · article catalogue
  **Published:** `2024-05-15T00:00:00.000Z`
  **NeKI brief:** Enabling Swift 6 language mode in a package means selecting a development toolchain and surfacing strict concurrency diagnostics during builds. The article presents this as an incremental migration gate, not a one-line compiler-version upgrade.
- [Using @Environment in SwiftUI to link Swift Package dependencies - SwiftLee](https://www.avanderlee.com/swiftui/environment-property-wrapper) — Antoine van der Lee articles · article catalogue
  **Published:** `2024-04-23T11:23:35+00:00`
  **NeKI brief:** Shows injecting shared values through SwiftUI's Environment, including defining custom EnvironmentKey values in a Swift package. Useful for keeping package views configurable without hard-coding app-level dependencies.
- [Multi-platform Swift Package releases with GitHub Actions](https://www.polpiella.dev/multi-platform-swift-package-releases-with-github-actions) — Pol Piella · article catalogue
  **Published:** `2024-03-27T00:00:00.000Z`
  **NeKI brief:** A tag-triggered GitHub Actions workflow can build and publish a Swift package for several platforms from one release definition. Matrix jobs improve coverage, while artifact naming and signing credentials must remain deterministic.
- [Third-party libraries acknowledgments using a Settings bundle](https://www.avanderlee.com/workflow/third-party-libraries-acknowledgments-swift-packages) — Antoine van der Lee articles · article catalogue
  **Published:** `2024-02-27T10:05:22+00:00`
  **NeKI brief:** Builds a Settings bundle acknowledgement screen from Swift Package dependencies, turning package metadata into user-visible credits. Useful for satisfying attribution requirements while keeping acknowledgements aligned with dependency changes.
- [Discovering Swift Async Algorithms package | Swift with Majid](https://swiftwithmajid.com/2024/02/26/discovering-swift-async-algorithms-package) — Swift with Majid · article catalogue
  **Published:** `2024-02-26T00:00:00+00:00`
  **NeKI brief:** Surveys Swift Async Algorithms operators for composing streams such as debounce, merge, and throttle. The package can replace bespoke task plumbing, but cancellation and backpressure semantics still need to match the product's event flow.
- [Discovering Swift Collections package | Swift with Majid](https://swiftwithmajid.com/2024/02/19/discovering-swift-collections-package) — Swift with Majid · article catalogue
  **Published:** `2024-02-19T00:00:00+00:00`
  **NeKI brief:** Introduces Swift Collections types that provide specialized semantics beyond Array and Dictionary. Choosing a structure for its access pattern can improve clarity and performance, while adding a package dependency should be justified by real usage.
- [Enable upcoming Swift features](https://www.polpiella.dev/enable-upcoming-swift-features-in-spm) — Pol Piella · article catalogue
  **Published:** `2023-12-13T00:00:00.000Z`
  **NeKI brief:** SwiftPM can opt into upcoming language features through compiler settings, allowing a package to test migration work before a feature becomes default. The trade-off is pinning toolchains and documenting which targets share the experimental mode.
- [How to import Swift macros without using Swift Package Manager](https://www.polpiella.dev/binary-swift-macros) — Pol Piella · article catalogue
  **Published:** `2023-11-29T00:00:00.000Z`
  **NeKI brief:** Builds binary Swift macros and discusses packaging compiler plugins for consumers. Useful when distributing macro implementations without exposing source, while accounting for toolchain and platform compatibility.
- [Using Swift SDKs to cross-compile Swift packages to Linux](https://www.polpiella.dev/swift-sdks) — Pol Piella · article catalogue
  **Published:** `2023-11-24T00:00:00.000Z`
  **NeKI brief:** Explains using Swift SDKs to cross-compile packages for Linux and other targets. Use it when separating SDK availability from compiler compatibility in a multi-platform Swift package pipeline.
- [Building and testing Swift packages on Windows using GitHub Actions](https://www.polpiella.dev/running-swift-on-widnows-with-gha) — Pol Piella · article catalogue
  **Published:** `2023-11-01T00:00:00.000Z`
  **NeKI brief:** GitHub Actions can exercise a Swift package on Windows, exposing filesystem, Foundation, and path assumptions hidden by macOS CI. A matrix job turns portability into a repeatable test rather than a late release surprise.
- [Adding an Info.plist file to a Swift executable](https://www.polpiella.dev/info-plist-swift-cli) — Pol Piella · article catalogue
  **Published:** `2023-10-11T00:00:00.000Z`
  **NeKI brief:** Shows a Swift command-line tool reading and modifying Info.plist data. Useful for build and release automation that needs typed manipulation instead of brittle shell text substitutions.
- [Swift on Linux CI/CD using swiftly](https://www.polpiella.dev/setting-up-swift-on-linux-ci-cd-using-swiftly) — Pol Piella · article catalogue
  **Published:** `2023-09-13T00:00:00.000Z`
  **NeKI brief:** Swiftly pins and installs a chosen Swift toolchain on Linux runners before SwiftPM builds execute. This makes CI versions reproducible and exposes portability failures independently from the developer's local Xcode installation.
- [Strict Concurrency Checking in Swift Packages](https://useyourloaf.com/blog/strict-concurrency-checking-in-swift-packages) — Use Your Loaf · article catalogue
  **Published:** `2023-09-11T10:55:50+01:00`
  **NeKI brief:** Shows how Swift Package targets can set Swift concurrency checking to minimal, targeted, or complete, and why package manifests need explicit unsafe Swift settings. It provides a staged route toward Swift 6 diagnostics instead of forcing an all-at-once migration.
- [Load custom fonts into your app using Swift Package Plugins](https://www.polpiella.dev/load-custom-fonts-with-no-code-using-swift-package-plugins) — Pol Piella · article catalogue
  **Published:** `2023-07-05T00:00:00.000Z`
  **NeKI brief:** Swift Package plugins and code generation automate bundling custom fonts into an app. Follow it to keep resource registration reproducible, while checking plugin sandboxing and build-time versus runtime responsibilities.
- [Version-specific Package.swift files](https://www.polpiella.dev/version-specific-package-manifests) — Pol Piella · article catalogue
  **Published:** `2023-06-14T00:00:00.000Z`
  **NeKI brief:** Version-specific Package.swift manifests let a package expose different configurations to different Swift toolchains. Follow it for compatibility planning, keeping divergence minimal so package behavior remains understandable across versions.
- [Private Swift packages on CI/CD](https://www.polpiella.dev/private-swift-packages-on-ci-cd) — Pol Piella · article catalogue
  **Published:** `2023-05-24T00:00:00.000Z`
  **NeKI brief:** Private Swift packages in CI require authenticated dependency resolution outside a developer’s local keychain. Follow it to scope tokens and SSH credentials narrowly, keeping package access reproducible for automation.
- [Creating a SwiftUI App to generate Text Completions with GPT-3.5 through the OpenAI API](https://www.createwithswift.com/creating-a-swiftui-app-to-generate-text-completions-with-gpt-3-5-through-the-openai-api) — Create with Swift · article catalogue
  **Published:** `2023-05-23T08:50:54.000Z`
  **NeKI brief:** Builds a simple SwiftUI client for GPT-3.5 text completions through an OpenAI package and SPM. Useful as an historical example of separating API setup, a test interface, and generated-text presentation before designing a production AI feature.
- [How to avoid a big refactor with the @_exported attribute](https://www.polpiella.dev/how-we-avoided-a-big-refactor-with-the-exported-attribute) — Pol Piella · article catalogue
  **Published:** `2023-05-17T00:00:00.000Z`
  **NeKI brief:** The underscored @_exported attribute re-exports a module to soften an import migration. Follow it as a temporary compatibility tool, recognizing that underscored language features can change and hide dependencies.
- [Creating a Swift Package: Quick Start Gotchas | Swiftjective-C](https://swiftjectivec.com/Creating-an-iOS-Swift-Package-with-Git-Quickstart-Guide) — Swiftjective-C · article catalogue
  **Published:** `2023-05-11T00:00:00-05:00`
  **NeKI brief:** Highlights Swift Package creation gotchas around Git layout and package targets, helping a new module remain consumable by Xcode projects instead of becoming a repository-shaped source dump.
- [Creating a SwiftUI App to generate images with Dall-E through the OpenAI API](https://www.createwithswift.com/creating-a-swiftui-app-to-generate-images-with-dall-e-through-the-openai-api) — Create with Swift · article catalogue
  **Published:** `2023-03-07T14:03:20.000Z`
  **NeKI brief:** Builds a SwiftUI image-generation experiment using DALL-E through an OpenAI package. Useful for tracing the path from package integration to a small testing UI, while recognizing that authentication, cost, safety, and response handling need production-specific design.
- [Coming in Swift 5.9: Network requests in Swift package plugins](https://www.polpiella.dev/network-requests-in-swift-package-plugins) — Pol Piella · article catalogue
  **Published:** `2023-02-22T00:00:00.000Z`
  **NeKI brief:** Swift 5.9 package plugins can perform network requests under explicit build-tool constraints. Follow it to understand capability declarations and reproducibility risks before making a build depend on remote data.
- [Safely pinning SPM dependencies to exact versions](https://www.polpiella.dev/safely-pinning-spm-depedencies-to-exact-versions) — Pol Piella · article catalogue
  **Published:** `2023-02-15T00:00:00.000Z`
  **NeKI brief:** Exact Swift Package dependency pins make builds reproducible and reviewable. The article is useful for weighing update control against security freshness, especially when lockfile changes need deliberate dependency review.
- [Creating a SwiftUI App to interact with the OpenAI ChatGPT API](https://www.createwithswift.com/building-a-swiftui-app-to-interact-with-the-openai-chatgpt-api) — Create with Swift · article catalogue
  **Published:** `2023-02-14T09:44:19.000Z`
  **NeKI brief:** Builds a small SwiftUI client around a Swift OpenAI package and a test interface for ChatGPT requests. Follow it to trace request-to-view-state wiring, while replacing exposed-key patterns with a secure service boundary.
- [Adding and Removing Swift Package dependencies in Xcode | Sarunw](https://sarunw.com/posts/managing-swift-package-in-xcode) — Sarunw · article catalogue
  **Published:** `2023-02-02`
  **NeKI brief:** Adds and removes Swift Package dependencies in Xcode, emphasizing package identity and target linkage so dependency changes remain reviewable.
- [Swift Package String Localization](https://useyourloaf.com/blog/swift-package-string-localization) — Use Your Loaf · article catalogue
  **Published:** `2023-01-23T13:30:13+00:00`
  **NeKI brief:** Recaps Swift Package localization requirements: use Swift tools 5.3 or newer, declare defaultLocalization, add each language’s .lproj resources under the target, and load keys from Bundle.module. Mixed app/package locales may require CFBundleAllowMixedLocalizations.
- [Making a serverless Swift function with Fastly and Upstash](https://www.polpiella.dev/making-a-serverless-swift-function-with-fastly-and-upstash) — Pol Piella · article catalogue
  **Published:** `2023-01-18T00:00:00.000Z`
  **NeKI brief:** Builds a serverless Swift function backed by Fastly and Upstash services. Use it to evaluate edge execution, external state, and deployment boundaries when a small API does not need a long-lived server.
- [Collecting GitHub Action workflow metrics using Swift](https://www.polpiella.dev/collecting-gihub-actions-workflow-metrics-with-swift) — Pol Piella · article catalogue
  **Published:** `2022-11-30T00:00:00.000Z`
  **NeKI brief:** A Swift command-line tool can collect GitHub Actions metrics through asynchronous API requests. Use pagination, rate-limit handling and stable aggregation, keeping the reporting tool independent of any individual workflow's success.
- [Binary Targets in Swift Package Manager - SwiftLee](https://www.avanderlee.com/swift/binary-targets-swift-package-manager) — Antoine van der Lee articles · article catalogue
  **Published:** `2022-11-15T09:37:59+00:00`
  **NeKI brief:** Configures binary targets in Swift Package Manager using artifacts or XCFrameworks, including checksum and distribution concerns. Useful for shipping prebuilt proprietary code while understanding portability and cache trade-offs.
- [Platform specific code in Swift Packages](https://www.polpiella.dev/platform-specific-code-in-swift-packages) — Pol Piella · article catalogue
  **Published:** `2022-10-06T00:00:00.000Z`
  **NeKI brief:** Organizes platform-specific code in Swift packages. Use it when one package supports Apple platforms or Linux without leaking unavailable APIs into shared targets.
- [Enabling Concurrency warnings in Xcode 16 – Donny Wals](https://www.donnywals.com/enabling-concurrency-warnings-in-xcode) — Donny Wals · article catalogue
  **Published:** `2022-09-13T12:09:36+00:00`
  **NeKI brief:** Concurrency warnings can be enabled before adopting Swift 6 mode, creating a staged inventory of isolation work without immediately blocking every build.
- [Sourcery Swift Package command plugin](https://www.polpiella.dev/sourcery-swift-package-command-plugin) — Pol Piella · article catalogue
  **Published:** `2022-08-31T00:00:00.000Z`
  **NeKI brief:** Integrates Sourcery generation as a Swift Package command plugin. Use it when repeatable code generation should run through SwiftPM rather than custom shell instructions.
- [My new Swift Package: ReadingTime](https://www.polpiella.dev/my-new-swift-package-reading-time) — Pol Piella · article catalogue
  **Published:** `2022-08-17T00:00:00.000Z`
  **NeKI brief:** This package case study derives reading-time metadata from text and publishes it as a reusable Swift dependency. It is useful for seeing how a small focused API, tests and package metadata form a distributable unit.
- [Advances in Swift Package Manager's dependency access control](https://www.polpiella.dev/advances-in-swift-package-access-control) — Pol Piella · article catalogue
  **Published:** `2022-08-03T00:00:00.000Z`
  **NeKI brief:** Swift Package Manager access-control changes refine which declarations cross target boundaries. The article is useful for modular API design, where package visibility should expose capabilities without leaking implementation types.
- [Code generation using Swift Package Plugins](https://www.polpiella.dev/code-generation-using-swift-package-plugins) — Pol Piella · article catalogue
  **Published:** `2022-07-05T00:00:00.000Z`
  **NeKI brief:** A Swift package plugin can inspect package inputs and generate source before compilation. Use deterministic output and declared inputs, keeping generated APIs reviewable and avoiding plugins that hide essential build-time dependencies.
- [Monospace Digits](https://useyourloaf.com/blog/monospace-digits) — Use Your Loaf · article catalogue
  **Published:** `2022-05-09T12:56:11+01:00`
  **NeKI brief:** Uses typography features for tabular or countdown numbers whose changing glyph widths would otherwise shift surrounding layout. Monospaced digits trade proportional aesthetics for stable alignment in metrics and timers.
- [Binary targets in modern Swift packages](https://www.polpiella.dev/binary-targets-in-modern-swift-packages) — Pol Piella · article catalogue
  **Published:** `2022-05-07T00:00:00.000Z`
  **NeKI brief:** Binary targets distribute prebuilt artifacts through Swift Package Manager instead of compiling their source. Use checksums, clear platform slices and versioned artifacts, evaluating debugging and transitive dependency trade-offs before adoption.
- [Using the Swift Package Manager command plugin for Swift-DocC](https://www.createwithswift.com/using-the-swift-package-manager-command-plugin-for-swift-docc) — Create with Swift · article catalogue
  **Published:** `2022-03-18T15:34:00.000Z`
  **NeKI brief:** Demonstrates using a Swift Package Manager command plugin to generate Swift-DocC documentation. Keep plugin inputs deterministic and make generated documentation a reviewable build artifact.
- [How to modularize existing iOS projects using Swift Package | Sarunw](https://sarunw.com/posts/how-to-modularize-existing-ios-projects-using-swift-package) — Sarunw · article catalogue
  **Published:** `2022-03-17`
  **NeKI brief:** Extract an existing iOS feature into a Swift Package by moving files, adding the package target, reconnecting it to the app, and tightening access levels. The access audit is essential: module boundaries expose every accidental reliance on internal symbols.
- [Using the Mapbox SDK for iOS with Xcode Cloud](https://www.createwithswift.com/using-the-mapbox-sdk-for-ios-with-xcode-cloud) — Create with Swift · article catalogue
  **Published:** `2022-02-17T13:47:20.000Z`
  **NeKI brief:** Explains configuring the Mapbox iOS SDK in Xcode Cloud, including credentials and build settings. Keep tokens out of logs and make hosted-runner configuration reproducible.
- [Embedding a dylib in a Swift Package](https://www.polpiella.dev/embedding-a-dylib-in-a-swift-package) — Pol Piella · article catalogue
  **Published:** `2022-02-12T00:00:00.000Z`
  **NeKI brief:** Embeds a dynamic library in a Swift package. Use it when distributing binary dependencies and needing explicit packaging, runtime loading, and platform compatibility handling.
- [An early look at Swift extensible build tools](https://www.polpiella.dev/an-early-look-at-swift-extensible-build-tools) — Pol Piella · article catalogue
  **Published:** `2022-01-22T00:00:00.000Z`
  **NeKI brief:** Examines Swift extensible build tools. Use it when package builds need custom generation or validation steps that integrate with SwiftPM rather than opaque external scripts.
- [Microapps architecture in Swift. Feature modules. | Swift with Majid](https://swiftwithmajid.com/2022/01/19/microapps-architecture-in-swift-feature-modules) — Swift with Majid · article catalogue
  **Published:** `2022-01-19T00:00:00+00:00`
  **NeKI brief:** Splits a large Swift app into feature modules with explicit dependencies, improving build isolation and ownership. Module boundaries should follow stable domain seams rather than mirroring every screen one-for-one.
- [Combined Swift packages | Swift by Sundell](https://www.swiftbysundell.com/tips/swift-packages-containing-both-a-command-line-tool-and-a-library) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Combines a command-line tool and library in one Swift package, separating executable and library targets while sharing source infrastructure.
- [Swift playgrounds tips and tricks | Swift by Sundell](https://www.swiftbysundell.com/articles/swift-playgrounds-tips-tricks) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Uses Swift playgrounds for small experiments, visual output, and API exploration without an app target. Playgrounds shorten feedback loops, while project integration and concurrency behavior still need real-target verification.
- [Managing dependencies using the Swift Package Manager | Swift by Sundell](https://www.swiftbysundell.com/articles/managing-dependencies-using-the-swift-package-manager) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Uses Swift Package Manager to declare and resolve dependencies through manifests and version requirements. Pinning and update policy should balance reproducibility, security, and maintenance.
- [Building a command line tool using the Swift Package Manager | Swift by Sundell](https://www.swiftbysundell.com/articles/building-a-command-line-tool-using-the-swift-package-manager) — Swift by Sundell · article catalogue
  **Published:** `2021-10-30`
  **NeKI brief:** Structure a Swift command-line tool as an executable target plus reusable library code, then define the entry point, arguments, dependencies, and installation path through Swift Package Manager. This separation keeps command parsing from consuming application logic.
- [Testing Core Data In A Swift Package](https://useyourloaf.com/blog/testing-core-data-in-a-swift-package) — Use Your Loaf · article catalogue
  **Published:** `2021-07-12T10:16:08+01:00`
  **NeKI brief:** Sets up an isolated Core Data test stack inside a Swift Package, keeping persistence tests independent from the application target. In-memory stores speed tests, but schema and migration coverage still need dedicated fixtures.
- [App architecture basics in SwiftUI Part 3: Module-separated layers | Cocoa with Love](https://www.cocoawithlove.com/blog/app-submodules.html) — Cocoa with Love · article catalogue
  **Published:** `2021-02-12`
  **NeKI brief:** The third architecture step isolates SwiftUI layers into modules, making dependency direction explicit before choosing patterns; the cost is extra package boundaries and integration work.
- [Xcode 12.5 Playground Access To App Types](https://useyourloaf.com/blog/xcode-12.5-playground-access-to-app-types) — Use Your Loaf · article catalogue
  **Published:** `2021-02-08T13:59:21+00:00`
  **NeKI brief:** Explains how Xcode 12.5 playgrounds can import types from an app target for focused experiments. The workflow accelerates prototyping, but target build settings and access control still constrain what the playground can reach.
- [Using Swift Packages in Playgrounds](https://useyourloaf.com/blog/using-swift-packages-in-playgrounds) — Use Your Loaf · article catalogue
  **Published:** `2020-10-12T16:06:57+01:00`
  **NeKI brief:** Adds Swift Package dependencies to playgrounds, useful for isolated experiments while preserving package version and module-resolution constraints during iteration.
- [Add resources to Swift packages](https://useyourloaf.com/blog/add-resources-to-swift-packages) — Use Your Loaf · article catalogue
  **Published:** `2020-07-20T10:09:29+01:00`
  **NeKI brief:** Adds resources to Swift packages and accesses them through Bundle.module. Use it when a library ships assets, localized strings, or fixtures without assuming an app bundle.
- [How to remove Cocoapods from your project | Sarunw](https://sarunw.com/posts/how-to-remove-cocoapods-from-your-project) — Sarunw · article catalogue
  **Published:** `2020-03-06`
  **NeKI brief:** Remove CocoaPods integration by deintegrating the Xcode project and deleting generated Pods, lockfile, workspace, and no-longer-needed Podfile artifacts. Reopen the project rather than the workspace, then replace dependencies deliberately so stale build settings and linked frameworks are not retained.
- [Creating a command line tool using the Swift Package Manager - SwiftLee](https://www.avanderlee.com/swift/command-line-tool-package-manager) — Antoine van der Lee articles · article catalogue
  **Published:** `2020-03-03T08:00:00+00:00`
  **NeKI brief:** Creates a Swift Package Manager executable target, defines its manifest, and runs it from the command line. The workflow is a compact template for Swift developer utilities.
- [Testing Swift packages on Linux using Docker – Ole Begemann](https://oleb.net/2020/swift-docker-linux) — Ole Begemann · article catalogue
  **Published:** `2020-02-02T18:44:07Z`
  **NeKI brief:** Running SwiftPM tests in a Linux Docker image catches platform assumptions before deployment and gives CI a repeatable toolchain. The workflow trades container setup time for an environment that differs meaningfully from a Mac host.
- [Automatic test discovery in Swift on Linux – Ole Begemann](https://oleb.net/2020/swift-test-discovery) — Ole Begemann · article catalogue
  **Published:** `2020-02-02T18:43:03Z`
  **NeKI brief:** SwiftPM's Linux test discovery is not enabled by default for older Swift toolchains, so packages need generated discovery or an explicit configuration step. The article identifies the portability gap that can make tests appear missing in CI.
- [Editing A Swift Package](https://useyourloaf.com/blog/editing-a-swift-package) — Use Your Loaf · article catalogue
  **Published:** `2019-08-19T09:57:45+01:00`
  **NeKI brief:** Explains editing a Swift package locally while an app consumes it, supporting rapid dependency development. Use it when switching between package checkout and resolved dependency without losing reproducible project configuration.
- [Creating Swift Packages in Xcode](https://useyourloaf.com/blog/creating-swift-packages-in-xcode) — Use Your Loaf · article catalogue
  **Published:** `2019-08-12T12:21:28+01:00`
  **NeKI brief:** Creates a Swift Package in Xcode with targets and tests, establishing a modular build boundary. Package resources and access control must be configured explicitly when code moves out of the app target.
- [Xcode Source Control Accounts](https://useyourloaf.com/blog/xcode-source-control-accounts) — Use Your Loaf · article catalogue
  **Published:** `2019-08-05T10:45:41+01:00`
  **NeKI brief:** Configures Xcode source-control accounts and authentication so repository operations use the intended identity. Keep credentials scoped and verify the selected account before pushing to avoid silently attributing work incorrectly.
- [How to import a C library in Swift using the Swift Package Manager – Ole Begemann](https://oleb.net/blog/2017/12/importing-c-library-into-swift) — Ole Begemann · article catalogue
  **Published:** `2017-12-18T21:18:00Z`
  **NeKI brief:** Importing a C library into Swift requires a module map or SwiftPM system-library target that describes headers and linker settings. The setup makes interoperability repeatable, while platform-specific paths remain a packaging concern.
- [Swift Package Manager macOS deployment target override – Ole Begemann](https://oleb.net/blog/2017/04/swift-3-1-package-manager-deployment-target) — Ole Begemann · article catalogue
  **Published:** `2017-04-07T16:54:49Z`
  **NeKI brief:** SwiftPM deployment-target overrides let package clients select a compatible macOS minimum when the package manifest's default is too broad. The fix separates library declaration from product deployment policy.
- [How to test a Swift package on Linux using Docker – Ole Begemann](https://oleb.net/blog/2017/03/testing-swift-packages-on-linux) — Ole Begemann · article catalogue
  **Published:** `2017-03-31T12:03:32Z`
  **NeKI brief:** Testing Swift packages on Linux in Docker isolates the toolchain and filesystem from the developer Mac. The repeatable setup catches portability assumptions while adding an image-maintenance cost to CI.
- [Loading Resources From A Framework](https://useyourloaf.com/blog/loading-resources-from-a-framework) — Use Your Loaf · article catalogue
  **Published:** `2017-03-27T10:23:16+01:00`
  **NeKI brief:** Loads images and other assets from a framework bundle rather than assuming Bundle.main. This is essential for modular code, while tests and previews require the same bundle-resolution logic.
- [Using 'swift package fetch' in an Xcode project | Cocoa with Love](https://www.cocoawithlove.com/blog/package-manager-fetch.html) — Cocoa with Love · article catalogue
  **Published:** `2017-01-30`
  **NeKI brief:** Explains wiring Swift Package Manager dependency fetching into an Xcode build before native integration existed, exposing the build-phase and dependency-ordering concerns involved. Follow it for historical build-system trade-offs and CI diagnosis.
- [GitHub for mac](https://useyourloaf.com/blog/github-for-mac) — Use Your Loaf · article catalogue
  **Published:** `2011-06-23T21:54:00+00:00`
  **NeKI brief:** Discusses a graphical Git client workflow for repository tasks. UI tools can aid discovery, but users still need to understand branch state, conflicts, and remote effects.
- [Git Cheat Sheet](https://useyourloaf.com/blog/git-cheat-sheet) — Use Your Loaf · article catalogue
  **Published:** `2010-05-29T15:10:00+00:00`
  **NeKI brief:** Collects practical Git setup, commit, branch, remote, and inspection commands. Use it for workflow orientation, then verify command semantics and repository policy against current Git documentation before applying them.
- [Switching Swift Package Manager dependencies between versioned and local development](https://tanaschita.com/spm-quick-tip-on-switching-to-local-dev) — Tanaschita · article catalogue
  **NeKI brief:** Shows how to switch a Swift Package dependency between a versioned remote requirement and a local checkout during development. Use it to test package changes quickly while preserving a clean, reproducible dependency declaration for collaborators and CI.
- [Get started with Swift Package Manager for iOS](https://tanaschita.com/spm-overview) — Tanaschita · article catalogue
  **NeKI brief:** Swift Package Manager concepts are explained through package manifests, targets and products. Follow it when modularizing an iOS project, especially to distinguish dependency declaration from the API surface a package exports.
- [How to add public libraries as Swift Packages to an iOS project](https://tanaschita.com/spm-add-public-packages) — Tanaschita · article catalogue
  **NeKI brief:** Adding a remote Swift package through Xcode covers version requirements and dependency updates. The guide is useful for reviewing reproducibility and supply-chain boundaries before accepting a package into an app target.
- [How to add local Swift Packages to an iOS project](https://tanaschita.com/spm-add-local-packages) — Tanaschita · article catalogue
  **NeKI brief:** Local Swift packages provide a modular dependency boundary during development. Follow it to iterate on shared code without publishing, while keeping target membership and resource ownership explicit.
- [Getting started with Apollo iOS for GraphQL in Swift](https://tanaschita.com/graphql-apollo-for-ios) — Tanaschita · article catalogue
  **NeKI brief:** Apollo iOS generates Swift models and operations from a GraphQL schema and integrates through Swift Package Manager. Follow it to assess generated-code benefits against cache invalidation and schema evolution costs.

## Newsletter and related leads

- [DynamicNotch: Building Polished Notch and Screen-Edge Interactions for macOS](https://l.fatbobman.com/w0150-7) — Fatbobman’s Swift Weekly · Issue 150 — Article · Topics: Swift · Swift Package Manager · SwiftUI
  **Published:** `2026-08-24T12:03:48.210Z`
  **NeKI brief:** Offers a macOS Swift package for notch-aware SwiftUI surfaces and AppKit-backed floating edge windows. It centralizes clipping, hit testing, safe-area and multi-display geometry, placement, and compact-notch reservations while leaving product state and interaction policy to the host app.
- [July digest](https://www.swift.org/blog/whats-new-in-swift-july-2026?ref=ioscodereview.com) — iOS Code Review · Issue 84 — Article · Topics: Concurrency · Objective-C & Cocoa · Swift
  **Published:** `2026-08-20T05:35:08.000Z`
  **NeKI brief:** Summarizes July activity across Swift releases, evolution, tooling and community workgroups, providing a routing overview rather than a single API tutorial.
- [Active ReviewSE-0545SwiftPM Build Performance Debugging Options](https://github.com/apple/swift-evolution/blob/main/proposals/0545-build-debugging-options.md) — SwiftLee Weekly · Issue 337 — Source repository · Topics: Developer Tools · Performance · Swift
  **Published:** `2026-08-18T14:06:21.000Z`
  **NeKI brief:** Proposes SwiftPM flags for Trace Event output and task backtraces across build-running commands. The generated timing, dependency, and optional stack data is intended to diagnose parallelism, invalidation, and clean or incremental build bottlenecks.
- [ConsentBus](https://github.com/divyaravitech/ConsentBus) — iOS Dev Tools · iOS Dev Tools: ConsentBus, FoundationModelsKit, Agent Island — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2026-08-06T16:00:49.980Z`
  **NeKI brief:** Implements serialized consent propagation across SDK adapters with signed receipts and a hash-chained audit ledger; most bundled vendor adapters are currently documented stubs rather than live integrations.
- [Introducing ListKit: An Open-Source Library for SwiftUI Lists](https://danielsaidi.com/blog/2026/06/08/introducing-listkit) — Those Who Swift · Issue 278 — Article · Topics: Architecture · Swift Package Manager · SwiftUI
  **Published:** `2026-08-05T20:00:46.292Z`
  **NeKI brief:** Introduces ListKit as a focused extraction from SwiftUIKit, with reusable SwiftUI list utilities, adaptive action groups, shelf layouts, and list-specific modifiers. The smaller package illustrates trading a broad convenience monolith for narrower dependencies.
- [Foundation Models Utilities](https://livsycode.com/swift/foundation-models-utilities?ref=createwithswift.com) — Create with Swift · Issue 117 — Article · Topics: AI Development · Swift · Swift Package Manager
  **Published:** `2026-07-24T15:00:34.000Z`
  **NeKI brief:** Surveys Apple's experimental Foundation Models Utilities package: hosted Chat Completions models, transcript dropping, rolling windows, summarisation, and runtime-loaded skills. It also makes the context-loss and platform-version trade-offs explicit before these patterns stabilise.
- [MistKit](https://github.com/brightdigit/MistKit) — iOS Dev Tools · iOS Dev Tools: MistKit, Swift Scribe, cmux - iOS Dev Tools — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2026-07-16T16:45:11.086Z`
  **NeKI brief:** MistKit packages CloudKit Web Services access for server-side Swift and command-line tools, separating backend automation from Apple's client frameworks. Useful when a service needs CloudKit data without running inside an iOS app.
- [TourKit](https://github.com/rampatra/TourKit) — iOS Dev Tools · iOS Dev Tools: TourKit, MockingKit, MemoryMap — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2026-07-09T16:30:20.398Z`
  **NeKI brief:** TourKit implements Apple-style onboarding tours for Mac and iPhone apps, providing guided highlights over application UI. Useful when a product needs contextual feature discovery instead of a sequence of static introduction screens.
- [Active ReviewSE-0534Opt-in exact matching for version identifiers with build metadata](https://github.com/apple/swift-evolution/blob/main/proposals/0534-swiftpm-exact-literal-version-matching.md) — SwiftLee Weekly · Issue 330 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2026-06-30T14:07:37.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0534Opt-in exact matching for version identifiers with build metadata. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [issue 751](https://iosdevweekly.netlify.app/issues/751) — iOS Dev Weekly · Issue 756 — Article · Topics: Developer Community & Business · Swift · Swift Package Manager
  **Published:** `26th June 2026`
  **NeKI brief:** Examines For long-time readers of iOS Dev Weekly, Dave Verwer’s announcement in issue 751 that he would be handing over the reins of the newsletter while continuing his community work on Swift Package Index (SPI) now feels especi Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Lucide Swift](https://github.com/ajaxjiang96/lucide-swift) — iOS Dev Tools · iOS Dev Tools: Reef, CodeIsland, Lucide Swift — Source repository · Topics: Developer Tools · Graphics, Media & Games · Swift
  **Published:** `2026-06-25T18:30:48.034Z`
  **NeKI brief:** Lucide Swift provides Swift-compatible Lucide icon assets and rendering helpers. Follow its repository for concrete symbol integration and customization patterns, while checking licensing, generated assets, and supported UI frameworks.
- [MLX Swift LM](https://github.com/ml-explore/mlx-swift-lm) — iOS Dev Tools · iOS Dev Tools: Promptberry, SolidLikeARock, MLX Swift LM — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2026-06-11T16:01:47.008Z`
  **NeKI brief:** MLX Swift LM provides Swift APIs for running machine-learning language models on Apple platforms. Follow its source for concrete model loading and inference workflows, while checking memory, hardware, and model-format requirements.
- [SwiftINI](https://github.com/jaywcjlove/SwiftINI) — iOS Dev Tools · iOS Dev Tools: Simtime, Sparkle 2, SwiftINI - iOS Dev Tools — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2026-06-04T17:01:58.905Z`
  **NeKI brief:** SwiftINI parses and serializes INI configuration files in Swift, providing a small format-specific layer instead of treating configuration as untyped text. Useful for command-line tools or legacy settings that need round-tripping.
- [GQLSwift](https://github.com/BaherTamer/GQLSwift) — iOS Dev Tools · iOS Dev Tools: GQLSwift, ScreenPlace, BuildWatch — Source repository · Topics: Developer Tools · Swift
  **Published:** `2026-05-28T16:31:04.346Z`
  **NeKI brief:** GQLSwift is a GitHub Swift library for GraphQL-related application code. Follow its source and README for concrete query or model-generation integration points, while checking supported GraphQL and Swift versions before adoption.
- [VibeChard](https://github.com/Maples7/VibeChard) — Fatbobman’s Swift Weekly · Issue 136 — Source repository · Topics: AI Development · Developer Tools · Xcode
  **Published:** `2026-05-18T12:01:58.375Z`
  **NeKI brief:** VibeChard addresses parallel Xcode-agent builds colliding in DerivedData, module caches, SwiftPM caches, and Simulator state. Use it when concurrent automation needs isolated build environments rather than simply increasing worker count.
- [SwiftSafeUI](https://github.com/BaherTamer/SwiftSafeUI) — iOS Dev Tools · iOS Dev Tools: SwiftSafeUI, Northstar, Ezscreenshots — Source repository · Topics: Developer Career & Practice · Developer Tools · Swift
  **Published:** `2026-05-14T16:15:24.123Z`
  **NeKI brief:** SwiftSafeUI wraps deprecated SwiftUI APIs behind compatibility-aware modifiers, views, and environment values. The repository demonstrates how to centralize availability branching so newer OS APIs are selected automatically while older deployment targets keep working.
- [Saying goodbye to CocoaPods: SwiftPM will soon be the default in Flutter!](https://blog.flutter.dev/saying-goodbye-to-cocoapods-swift-package-manager-is-soon-the-default-in-flutter-645a92714a57) — iOS Dev Weekly · Issue 749 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `1st May 2026`
  **NeKI brief:** Does this deserve a “Finally” comment? It’s good to see it happen, regardless. That CocoaPods read-only trunk deadline will come around sooner than we think. As far as I can tell, React Native still currently requires pod, but it appears that they are also…
- [AcceptedSE-0511SwiftPM Add Target Plugin Command](https://github.com/apple/swift-evolution/blob/main/proposals/0511-swiftpm-add-target-plugin.md) — SwiftLee Weekly · Issue 321 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2026-04-28T14:07:22.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0511SwiftPM Add Target Plugin Command. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [What’s New In Swift: March 2026 Edition](https://www.swift.org/blog/whats-new-in-swift-march-2026) — Those Who Swift · Issue 260 — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **Published:** `2026-04-01`
  **NeKI brief:** Summarizes Swift changes released or highlighted in March 2026. Use it to locate language and tooling updates relevant to a project, then read the linked proposals and release notes before changing source or compiler settings.
- [AcceptedSE-0501HTML Coverage Report](https://github.com/apple/swift-evolution/blob/main/proposals/0501-swiftpm-html-coverage-report.md) — SwiftLee Weekly · Issue 315 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `2026-03-17T15:01:49.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0501HTML Coverage Report. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Swift 6.3 Released](https://www.swift.org/blog/swift-6.3-released) — iOS Dev Weekly · Issue 746 — Article · Topics: Swift · Testing
  **Published:** `13th March 2026`
  **NeKI brief:** Announces Swift 6.3 and summarizes the language, package, and tooling changes in that release. Use it to identify migration candidates, then consult the release notes and proposal links for exact compiler behavior and availability.
- [Swift Build](https://docs.swift.org/swiftpm/documentation/packagemanagerdocs/swiftbuildpreview) — iOS Dev Weekly · Issue 746 — Article · Topics: Swift · Swift Package Manager · Testing
  **Published:** `13th March 2026`
  **NeKI brief:** Presents swift build for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [AcceptedSE-0509Software Bill of Materials (SBOM) Generation for Swift Package Manager](https://github.com/apple/swift-evolution/blob/main/proposals/0509-swift-sboms-via-swiftpm.md) — SwiftLee Weekly · Issue 313 — Source repository · Topics: App Distribution & Store Operations · Swift · Swift Package Manager
  **Published:** `2026-03-03T15:11:29.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0509Software Bill of Materials (SBOM) Generation for Swift Package Manager. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [release announcement](https://forums.swift.org/t/grdb-v7-10-0-android-linux-windows-and-sqlcipher-swiftpm/84754) — Fatbobman’s Swift Weekly · Issue 124 — Article · Topics: Cross-Platform & Web · Product Design · Swift
  **Published:** `2026-02-23T12:03:12.462Z`
  **NeKI brief:** GRDB 7.10's release discussion covers Android, Linux, Windows, and SQLCipher packaging, including current SwiftPM trait limitations. Use it when planning cross-platform SQLite support and checking which dependencies Xcode still downloads unnecessarily.
- [Active ReviewSE-0509Software Bill of Materials (SBOM) Generation for Swift Package Manager](https://github.com/apple/swift-evolution/blob/main/proposals/0509-swift-sboms.md) — SwiftLee Weekly · Issue 309 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2026-02-03T15:08:20.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0509Software Bill of Materials (SBOM) Generation for Swift Package Manager. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [InAppPurchaseKit](https://github.com/adamfootdev/InAppPurchaseKit) — iOS Dev Tools · iOS Dev Tools: Bullseye, Commander, InAppPurchaseKit — Source repository · Topics: App Distribution & Store Operations · Apple Platform Ecosystem · Developer Tools
  **Published:** `2026-01-29T21:12:37.433Z`
  **NeKI brief:** InAppPurchaseKit packages common in-app-purchase workflows for Swift applications. Follow its source for concrete product loading, entitlement, and transaction abstractions, then verify StoreKit version assumptions separately.
- [HealthKit Data Generator](https://github.com/aminbenarieb/healthkit-data-generator) — iOS Dev Tools · iOS Dev Tools: MachScope, SwiftFindRefs, HealthKit Data Generator — Source repository · Topics: AI Development · Developer Tools · Testing
  **Published:** `2026-01-22T20:01:38.499Z`
  **NeKI brief:** HealthKit Data Generator creates configurable, realistic HealthKit samples for iOS development and tests, including natural-language-assisted profiles. Useful for exercising charts and analytics without manually producing device health records.
- [CocoaPods announced a staged move toward read-only mode](https://blog.cocoapods.org/CocoaPods-Specs-Repo) — Those Who Swift · Issue 250 — Article · Topics: AI Development · Objective-C & Cocoa · Swift Package Manager
  **Published:** `2026-01-21`
  **NeKI brief:** Announces the CocoaPods Specs repository move toward read-only operation. Useful for assessing dependency-resolution and supply-chain implications in projects that still rely on CocoaPods.
- [AcceptedSE-0500Improving package creation with custom templates: SwiftPM Template Initialization](https://github.com/apple/swift-evolution/blob/main/proposals/0500-package-manager-templates.md) — SwiftLee Weekly · Issue 307 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2026-01-20T15:10:47.000Z`
  **NeKI brief:** Records AcceptedSE-0500Improving package creation with custom templates: SwiftPM Template Initialization, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Swift Package Index package list](https://github.com/SwiftPackageIndex/PackageList/blob/main/packages.json) — iOS Dev Weekly · Issue 739 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `16th January 2026`
  **NeKI brief:** The Swift Package Index repository file contains the public package catalogue data used to index Swift packages.
- [Swift Modules and Code/Assets Duplication](https://pfandrade.me/blog/swift-modules-and-codeassets-duplication) — SwiftLee Weekly · Issue 306 — Article · Topics: Swift · Swift Package Manager
  **Published:** `2026-01-13T15:06:45.000Z`
  **NeKI brief:** Presents Swift Modules and Code/Assets Duplication, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Swift Package Manager Mirrors for Local Development](https://kunat.dev/notes/spm-package-mirroring) — iOS Dev Weekly · Issue 738 — Article · Topics: Swift · Swift Package Manager · Testing
  **Published:** `9th January 2026`
  **NeKI brief:** Presents Swift Package Manager Mirrors for Local Development, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Versioned Package.swift Files](https://www.massicotte.org/blog/package-swift) — iOS Dev Weekly · Issue 738 — Article · Topics: Swift · Swift Package Manager
  **Published:** `9th January 2026`
  **NeKI brief:** Presents Versioned Package.swift Files, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [🤖 How to use the Subprocess Swift Package to run commands from Swift](https://swiftdevjournal.com/posts/subprocess) — iOS CI Newsletter · Issue 84 — Article · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-12-31T00:00:00.000Z`
  **NeKI brief:** Walks through how to use the Subprocess Swift Package to run commands from Swift, with practical context for Developer Tools and Swift. Use it when implementing the workflow, while checking current tool and platform versions before copying the setup.
- [Mark Szymczyk](https://mastodon.world/@swiftdevjournal) — iOS CI Newsletter · Issue 84 — Article · Topics: Swift · Swift Package Manager
  **Published:** `2025-12-31T00:00:00.000Z`
  **NeKI brief:** Mark shows how to use instrument to profile your app, spot views with high update frequency and investigate the roots of unnecessary re-renders.
- [ThreadCommissionerKit](https://github.com/phil-margetson/ThreadCommissionerKit) — iOS Dev Tools · iOS Dev Tools: Price Localize App, Swift AI SDK, ThreadCommissionerKit — Source repository · Topics: Concurrency · Developer Tools · Swift
  **Published:** `2025-12-11T17:45:25.072Z`
  **NeKI brief:** ThreadCommissionerKit provides Swift support for Thread or connected-device workflows. Follow its source for concrete commissioning, network, and device-state APIs, while verifying hardware and platform requirements.
- [Improving Swift Package Scripts with GitHub Actions workflows](https://danielsaidi.com/blog/2025/11/26/improving-swift-package-scripts-with-github-action-workflows) — SwiftLee Weekly · Issue 300 — Article · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-12-02T15:13:04.000Z`
  **NeKI brief:** Examines A list of ready-to-use GitHub Actions workflows for Swift Packages in the context of Developer Tools and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Building Closed-Source Binaries With GitHub Actions](https://danielsaidi.com/blog/2025/11/09/building-closed-source-binaries-with-github-actions) — Those Who Swift · Issue 240 — Article · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-11-12`
  **NeKI brief:** Describes building closed-source binaries with GitHub Actions. Useful for designing reproducible distribution pipelines while keeping source private and making signing, artifacts, and release inputs explicit.
- [AnyLanguageModel](https://github.com/mattt/AnyLanguageModel) — iOS Dev Tools · iOS Dev Tools: Clash X, AnyLanguageModel, HealthKit Data Generator — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **Published:** `2025-11-06T22:32:54.905Z`
  **NeKI brief:** AnyLanguageModel mirrors Apple's Foundation Models API while allowing alternative language-model providers, presenting a compatible abstraction for application code. Useful for testing provider substitution and keeping model integration behind a stable Swift interface.
- [Announcing the Swift SDK for Android](https://www.swift.org/blog/nightly-swift-sdk-for-android) — Those Who Swift · Issue 238 — Article · Topics: Cross-Platform & Web · Swift · Swift Package Manager
  **Published:** `2025-10-29`
  **NeKI brief:** We can't wait to see what scary things you will Create with Swift tonight! 🎃👻
- [Now you can test Xcode apps and Swift packages in Zed](https://luxmentis.org/blog/test-xcode-apps-in-zed) — iOS Dev Weekly · Issue 731 — Article · Topics: Swift · Testing · Xcode
  **Published:** `17th October 2025`
  **NeKI brief:** Presents now you can test xcode apps and swift packages in zed for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Introducing Swift Profile Recorder](https://www.swift.org/blog/swift-profile-recorder) — Those Who Swift · Issue 235 — Article · Topics: Performance · Swift · Swift Package Manager
  **Published:** `2025-10-08`
  **NeKI brief:** Introduces Swift Profile Recorder for capturing runtime profiling data from Swift applications. Useful for collecting reproducible performance evidence in environments where full Instruments sessions are impractical.
- [All about Swift Package Manager Traits](https://theswiftdev.com/2025/all-about-swift-package-manager-traits) — iOS Dev Weekly · Issue 729 — Article · Topics: AI Development · Swift · Swift Package Manager
  **Published:** `3rd October 2025`
  **NeKI brief:** Presents All about Swift Package Manager Traits, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Package Traits](https://github.com/swiftlang/swift-evolution/blob/main/proposals/0450-swiftpm-package-traits.md) — iOS Dev Weekly · Issue 729 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `3rd October 2025`
  **NeKI brief:** Defines Swift Package Manager package traits for expressing optional dependency features. Study the proposal when designing modular packages, then verify accepted syntax and toolchain support before adopting it.
- [Accessing Swift Package Manager dependency versions at runtime](https://annema.me/blog/accessing-swift-package-manager-dependency-versions-at-runtime) — SwiftLee Weekly · Issue 291 — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **Published:** `2025-09-30T13:58:29.000Z`
  **NeKI brief:** This article solves runtime dependency-version display by copying Package.resolved during the build and parsing it in the app. It explains why a cross-platform Xcode run-script approach can collide with code signing and offers a practical debug-screen alternative.
- [Things Cloud](https://www.swift.org/blog/how-swifts-server-support-powers-things-cloud) — iOS Dev Weekly · Issue 728 — Article · Topics: Security & Privacy · Swift · Swift Package Manager
  **Published:** `26th September 2025`
  **NeKI brief:** Explains How Swift's server support powers Things Cloud, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Apple’s internal password monitoring service](https://www.swift.org/blog/swift-at-apple-migrating-the-password-monitoring-service-from-java) — iOS Dev Weekly · Issue 728 — Article · Topics: Security & Privacy · Swift · Swift Package Manager
  **Published:** `26th September 2025`
  **NeKI brief:** Describes Apple's migration of a password-monitoring service from Java to Swift, including server-side concurrency and operational considerations. Useful as a production case study for Swift beyond client applications.
- [Swift Package Index](https://github.com/SwiftPackageIndex/SwiftPackageIndex-Server) — iOS Dev Weekly · Issue 728 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `26th September 2025`
  **NeKI brief:** Examines open-source, focusing on georgios recommends the point-free swift-snapshot-testing which we also use to test the rendered html output from the…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Localization Troubles With Swift PM](https://www.scottberrevoets.com/2025/09/19/localization-troubles-with-swift-pm) — Those Who Swift · Issue 233 — Article · Topics: Localization · Swift · Swift Package Manager
  **Published:** `2025-09-24`
  **NeKI brief:** Examines Localization Troubles With Swift PM, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [ImplementedSE-0482Binary Static Library Dependencies](https://github.com/apple/swift-evolution/blob/main/proposals/0482-swiftpm-static-library-binary-target-non-apple-platforms.md) — SwiftLee Weekly · Issue 290 — Source repository · Topics: Dependency Injection · Developer Tools · Swift
  **Published:** `2025-09-23T14:09:24.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0482Binary Static Library Dependencies. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Swift-Build GitHub Action](https://l.fatbobman.com/w0102-07) — Fatbobman’s Swift Weekly · Issue 102 — Article · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-09-15T12:03:30.479Z`
  **NeKI brief:** Provides a GitHub Action for building and testing Swift packages across platforms. Follow it when setting up matrix-based package validation and comparing CI workflows for Linux, macOS, and other supported targets.
- [detailed introduction](https://brightdigit.com/tutorials/swift-build) — Fatbobman’s Swift Weekly · Issue 102 — Tutorial · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-09-15T12:03:30.479Z`
  **NeKI brief:** Explains using the swift-build GitHub Action to run Swift Package Manager builds and tests on macOS and Linux. Use it as a compact cross-platform CI starting point before adding caching, matrices, or release artifacts.
- [🤖 How to generate GitHub Actions workflows automatically](https://elegantchaos.com/2025/08/28/action-builder.html) — iOS CI Newsletter · Issue 74 — Article · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `2025-09-10T00:00:00.000Z`
  **NeKI brief:** Walks through how to generate GitHub Actions workflows automatically, with practical context for Cross-Platform & Web and Developer Tools. Use it when implementing the workflow, while checking current tool and platform versions before copying the setup.
- [Mercato](https://github.com/tikhop/Mercato) — iOS Dev Tools · iOS Dev Tools: ch.at, Mercato, Dependencies — Source repository · Topics: App Distribution & Store Operations · Developer Career & Practice · Developer Tools
  **Published:** `2025-08-14T19:53:26.103Z`
  **NeKI brief:** Mercato wraps StoreKit 2 for subscriptions and in-app purchases across Apple platforms, aiming to reduce repetitive transaction plumbing. Useful for comparing a focused purchase abstraction with direct StoreKit state and entitlement management.
- [Creating Core Image Metal Shader Library in a Swift Package Plugin](https://juniperphoton.substack.com/p/creating-core-image-metal-shader) — Those Who Swift · Issue 227 — Article · Topics: Graphics, Media & Games · Swift · Swift Package Manager
  **Published:** `2025-08-13`
  **NeKI brief:** Examines Creating Core Image Metal Shader Library in a Swift Package Plugin, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [ImplementedSE-0480Warning Control Settings for SwiftPM](https://github.com/apple/swift-evolution/blob/main/proposals/0480-swiftpm-warning-control.md) — SwiftLee Weekly · Issue 284 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-08-12T18:01:44.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0480Warning Control Settings for SwiftPM. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [FreeTypeFramework](https://github.com/EvgenijLutz/FreeTypeFramework) — iOS Dev Tools · iOS Dev Tools: FreeTypeFramework, IGListKit, Horoscope — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-07-31T18:12:59.226Z`
  **NeKI brief:** FreeTypeFramework packages the FreeType font engine for Apple-platform projects, making font parsing and rasterization available through a reusable framework. The repository is a useful starting point when system font APIs do not cover a custom rendering pipeline.
- [📦 How to set up a Swift Package registry](https://albertodebortoli.com/2025/06/06/how-to-setup-a-swift-package-registry-in-artifactory) — iOS CI Newsletter · Issue 71 — Article · Topics: Concurrency · Swift · Swift Package Manager
  **Published:** `2025-06-30T00:00:00.000Z`
  **NeKI brief:** Walks through how to set up a Swift Package registry, with practical context for Concurrency and Swift. Use it when implementing the workflow, while checking current tool and platform versions before copying the setup.
- [MoPromoteKit](https://github.com/mkhasson97/MoPromoteKit) — iOS Dev Tools · iOS Dev Tools: Create Custom Symbols, MoPromoteKit, SyntaxKit — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2025-06-26T19:24:23.404Z`
  **NeKI brief:** MoPromoteKit provides promotion or marketing integration for mobile applications. Follow its repository for concrete API and campaign workflows, while verifying supported providers, privacy, and maintenance before adoption.
- [SyntaxKit](https://github.com/brightdigit/SyntaxKit) — iOS Dev Tools · iOS Dev Tools: Create Custom Symbols, MoPromoteKit, SyntaxKit — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-06-26T19:24:23.404Z`
  **NeKI brief:** SyntaxKit provides syntax-related parsing or presentation components for Swift. Follow its source and examples for concrete tokenization and highlighting behavior, while checking grammar coverage and performance for the intended editor or viewer.
- [Create a Swift Package from Your SwiftUI Project](https://www.youtube.com/watch?v=_KYc2wJVIDE) — Those Who Swift · Issue 220 — Video · Topics: Swift · Swift Package Manager · SwiftUI
  **Published:** `2025-06-25`
  **NeKI brief:** Converts an SF Symbol picker from a SwiftUI project into a reusable multiplatform Swift package. The walkthrough covers access control, platform differences, GitHub publication, version tags, and consuming package updates.
- [ChessKit](https://github.com/chesskit-app/chesskit-swift) — iOS Dev Tools · iOS Dev Tools: App Store Screenshot Tester, Iconed, ChessKit, — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-06-19T14:20:14.930Z`
  **NeKI brief:** ChessKit provides Swift models or UI components for chess applications. Follow its source for concrete board, move, and game-state representations, while verifying its package API and performance for the intended use.
- [WebView Is Finally Coming to SwiftUI](https://danielsaidi.com/blog/2025/06/10/webview-is-finally-coming-to-swiftui) — Those Who Swift · Issue 219 — Article · Topics: Swift · Swift Package Manager · SwiftUI
  **Published:** `2025-06-19`
  **NeKI brief:** Discusses the emerging native SwiftUI web-view direction and its implications for replacing representable wrappers. Useful for migration planning, while verifying availability and behavior against the target SDK.
- [OAuthKit](https://github.com/codefiesta/OAuthKit) — iOS Dev Tools · iOS Dev Tools: AI Git Narrator, OAuthKit, FlipKit — Source repository · Topics: Architecture · Combine & Reactive Programming · Swift
  **Published:** `2025-06-12T19:41:45.540Z`
  **NeKI brief:** OAuthKit provides an observable Swift framework for OAuth 2.0 authorization flows, centralizing state and callback handling. Useful for comparing a reusable authentication boundary with endpoint-specific browser-session code.
- [🧪 Xtool: A cross-platform Xcode replacement](https://forums.swift.org/t/xtool-cross-platform-xcode-replacement-build-ios-apps-on-linux-and-more/79803) — iOS CI Newsletter · Issue 68 — Article · Topics: Cross-Platform & Web · Swift · Xcode
  **Published:** `2025-05-18T00:00:00.000Z`
  **NeKI brief:** Presents xtool: cross-platform xcode replacement for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [MYCloudKit](https://github.com/mufasaYC/MYCloudKit) — iOS Dev Tools · iOS Dev Tools: MYCloudKit, SwiftUX, Deploy Path — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-05-15T18:46:45.755Z`
  **NeKI brief:** MYCloudKit provides Swift abstractions around CloudKit data or synchronization. Follow its source for concrete record, container, and sync behavior, then compare its conflict and error model with the application architecture.
- [Adding Dependencies to Binary Swift Packages](https://danielsaidi.com/blog/2025/05/02/adding-dependencies-to-binary-swift-packages) — Those Who Swift · Issue 213 — Article · Topics: Dependency Injection · Swift · Swift Package Manager
  **Published:** `2025-05-07`
  **NeKI brief:** Presents Adding dependencies to binary Swift packages, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [SwiftUI: How to Use Custom Fonts, Colours, and Images in a Swift Package](https://dev.jeremygale.com/swiftui-how-to-use-custom-fonts-colours-and-images-in-a-swift-package) — Those Who Swift · Issue 213 — Article · Topics: Swift · Swift Package Manager · SwiftUI
  **Published:** `2025-05-07`
  **NeKI brief:** Examines SwiftUI: How to Use Custom Fonts, Colours, and Images in a Swift Package, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Creating MCP Servers in Swift](https://www.artemnovichkov.com/blog/creating-mcp-servers-in-swift) — iOS Dev Weekly · Issue 708 — Article · Topics: AI Development · Swift · Swift Package Manager
  **Published:** `18th April 2025`
  **NeKI brief:** Artem explains how to create an MCP server (Model Context Protocol) that can be used to connect LLMs model with the tools that we use everyday using the Swift programming language.
- [Model Context Protocol (MCP)](https://www.anthropic.com/news/model-context-protocol) — iOS Dev Weekly · Issue 708 — Article · Topics: AI Development · Swift · Swift Package Manager
  **Published:** `18th April 2025`
  **NeKI brief:** Discusses Model Context Protocol in a public developer resource. Use it to compare the author's concrete workflow and trade-offs with your project constraints, and verify any platform-specific claims against current primary documentation.
- [FormattedListKit](https://github.com/chiahsien/FormattedListKit) — iOS Dev Tools · iOS Dev Tools: FormattedListKit, Libraried, Pressdeck — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-04-17T13:23:18.210Z`
  **NeKI brief:** FormattedListKit provides formatted list components for SwiftUI or UIKit. Follow its source for concrete row layout, formatting, and interaction patterns, then check accessibility and platform compatibility before adoption.
- [easy-frame](https://github.com/alschmut/EasyFrameCommand) — iOS Dev Tools · iOS Dev Tools: easy-frame, Sweetpad, StoreKitHelper — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Swift
  **Published:** `2025-04-11T07:56:27.598Z`
  **NeKI brief:** EasyFrameCommand is a Swift CLI that creates framed App Store screenshots from custom SwiftUI layouts. Useful for repeatable marketing-image generation that keeps device framing in source-controlled code instead of manual editing.
- [Supercharging SwiftUI Text with Dynamic Content Styling](https://danielsaidi.com/blog/2025/04/08/supercharging-swiftui-text-with-dynamic-content-styling) — iOS Dev Weekly · Issue 707 — Article · Topics: Swift · Swift Package Manager · SwiftUI
  **Published:** `11th April 2025`
  **NeKI brief:** Presents Supercharging SwiftUI Text with Dynamic Content Styling, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Documenting your code with DocC](https://swiftwithmajid.com/2025/04/01/documenting-your-code-with-docc?ref=createwithswift.com) — Create with Swift · Issue 55 — Article · Topics: Accessibility · Swift · Xcode
  **Published:** `2025-04-04T15:49:40.000Z`
  **NeKI brief:** Uses DocC to document modular Swift packages, where separate targets need navigable symbols and tutorials. The workflow turns documentation into a distributable module artifact, making API contracts discoverable instead of relying on repository context.
- [Swift 6.1 Released](https://www.swift.org/blog/swift-6.1-released) — iOS Dev Weekly · Issue 706 — Article · Topics: Concurrency · Objective-C & Cocoa · Swift
  **Published:** `4th April 2025`
  **NeKI brief:** The community has already shared some excellent insights. If you’re looking to dive deeper, we highly recommend checking out this video by Vincent!
- [📦 FREE Webinar: CI/CD for Swift Packages](https://streamyard.com/watch/62AzM2xGJ2hB) — iOS CI Newsletter · Issue 64 — Article · Topics: CI/CD & Automation · Swift · Swift Package Manager
  **Published:** `2025-03-23T00:00:00.000Z`
  **NeKI brief:** Examines FREE Webinar: CI/CD for Swift Packages in the context of CI/CD & Automation and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Simple Modularization Setup for a New App](https://www.manu.show/2025-02-27-simple-modularization-setup) — Those Who Swift · Issue 204 — Article · Topics: Architecture · Swift · Swift Package Manager
  **Published:** `2025-03-05`
  **NeKI brief:** Examines Simple Modularization Setup for a New App, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Mint](https://github.com/yonaskolb/Mint) — iOS Dev Tools · iOS Dev Tools: Starview, Mint, Giffy - iOS Dev Tools — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-02-13T18:15:48.650Z`
  **NeKI brief:** Mint installs and runs Swift Package Manager command-line tools at project-pinned versions. Use it to make generators, linters, and other developer executables reproducible without committing their binaries or relying on globally installed versions.
- [VS Code extension for Swift update](https://www.swift.org/blog/vscode-swift-2) — Those Who Swift · Issue 201 — Article · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-02-12`
  **NeKI brief:** Introduces updates to the VS Code extension for Swift. Follow it when comparing editor workflows, language-server capabilities, and debugging support outside Xcode, while checking the extension and toolchain versions required by a project.
- [ImplementedSE-0450Package traits](https://github.com/apple/swift-evolution/blob/main/proposals/0450-swiftpm-package-traits.md) — SwiftLee Weekly · Issue 258 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-02-11T15:02:09.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0450Package traits. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [GitHub - swiftlang/swift-build: A high-level build system based on llbuild, used by Xcode, Swift Playground, and the Swift Package ManagerA high-level build system based on llbuild, used by Xcode, Swift Playground, and the Swift Package Manager - swiftlang/swift-buildGitHubswiftlang](https://github.com/swiftlang/swift-build?ref=createwithswift.com) — Create with Swift · Issue 47 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-02-07T16:00:24.000Z`
  **NeKI brief:** This commitment led Apple to open-sourcing Swift Build, a build engine that offers a comprehensive set of build rules for constructing Swift projects.
- [Swift Build](https://github.com/swiftlang/swift-build) — Fatbobman’s Swift Weekly · Issue 69 — Source repository · Topics: Swift · Swift Package Manager · Xcode
  **Published:** `2025-02-03T12:01:11.391Z`
  **NeKI brief:** This commitment led Apple to open-sourcing Swift Build, a build engine that offers a comprehensive set of build rules for constructing Swift projects.
- [llbuild](https://github.com/swiftlang/swift-llbuild) — Fatbobman’s Swift Weekly · Issue 69 — Source repository · Topics: Swift · Swift Package Manager · Xcode
  **Published:** `2025-02-03T12:01:11.391Z`
  **NeKI brief:** llbuild is the lower-level build-system engine used by Swift tooling. Use it to inspect dependency scheduling and incremental compilation foundations, while keeping its implementation role distinct from the higher-level Swift Build repository.
- [Swift Everywhere: Bringing Swift Packages to Android](https://skip.tools/blog/android-native-swift-packages) — iOS Dev Weekly · Issue 697 — Article · Topics: Cross-Platform & Web · Swift · Testing
  **Published:** `31st January 2025`
  **NeKI brief:** Presents swift everywhere: bringing swift packages to android for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [📦 The Tuist Swift Package Manager Registry](https://tuist.dev/blog/2025/01/22/announcing-tuist-registry) — iOS CI Newsletter · Issue 60 — Article · Topics: Apple Platform Ecosystem · Swift · Swift Package Manager
  **Published:** `2025-01-28T00:00:00.000Z`
  **NeKI brief:** Examines The Tuist Swift Package Manager Registry in the context of Apple Platform Ecosystem and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Package Registry](https://github.com/swiftlang/swift-package-manager/blob/main/Documentation/PackageRegistry/PackageRegistryUsage.md) — iOS CI Newsletter · Issue 60 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-01-28T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for Package Registry, relevant to Developer Tools and Swift. Inspect its implementation, open issues, and release state before adopting the approach.
- [SE-0292](https://forums.swift.org/t/se-0292-package-registry-service/42623) — Fatbobman’s Swift Weekly · Issue 68 — Article · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `2025-01-27T01:05:46.208Z`
  **NeKI brief:** SE-0292 defines a package-registry protocol and service model for SwiftPM dependencies. Follow it when designing package distribution, authentication, and version-resolution infrastructure beyond Git URL fetching.
- [partnership with GitHub](https://github.blog/news-insights/product-news/github-package-registry-will-support-swift-packages) — iOS Dev Weekly · Issue 696 — Article · Topics: Developer Tools · Swift · Xcode
  **Published:** `24th January 2025`
  **NeKI brief:** Presents partnership with github for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [JFrog](https://jfrog.com/integrations/swift-repository) — iOS Dev Weekly · Issue 696 — Article · Topics: Developer Tools · Swift · Xcode
  **Published:** `24th January 2025`
  **NeKI brief:** Presents jfrog for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Cloudsmith](https://cloudsmith.com/product/formats/swift) — iOS Dev Weekly · Issue 696 — Article · Topics: Developer Tools · Swift · Xcode
  **Published:** `24th January 2025`
  **NeKI brief:** Presents cloudsmith for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Swift Bundler](https://github.com/stackotter/swift-bundler) — iOS Dev Tools · iOS Dev Tools: Swift Bundler, Swift for Visual Studio Code, iOS-uploader — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-01-16T21:51:40.196Z`
  **NeKI brief:** Swift Bundler wraps package creation, building, running, and testing in a single cross-platform workflow, with templates and Xcode integration. It helps compare a package-centric toolchain with manually maintained project and distribution scripts.
- [Active ReviewSE-0455SwiftPM @testable build setting](https://github.com/apple/swift-evolution/blob/main/proposals/0455-swiftpm-testable-build-setting.md) — SwiftLee Weekly · Issue 254 — Source repository · Topics: Objective-C & Cocoa · Swift · Testing
  **Published:** `2025-01-14T14:03:25.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0455SwiftPM @testable build setting. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [⛓️‍💥 Automatically check if a new version of your Swift Package introduces breaking changes](https://www.adyen.com/knowledge-hub/swift-api-diff) — iOS CI Newsletter · Issue 59 — Article · Topics: Swift · Swift Package Manager
  **Published:** `2025-01-13T00:00:00.000Z`
  **NeKI brief:** Presents preventing accidental api breaks for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Xcode Library customization with SPM plugin](https://www.artemnovichkov.com/blog/xcode-library-customization-with-spm-plugin?ref=createwithswift.com) — Create with Swift · Issue 41 — Article · Topics: Swift · Swift Package Manager · Xcode
  **Published:** `2024-12-20T16:00:23.000Z`
  **NeKI brief:** Artem explains how to customize the Xcode Library by using a Swift Package Manager demonstrating how to automate the discovery and addition of reusable UI components, such as views and modifiers, to the library.
- [appstoreconnect-swift-sdk](https://github.com/AvdLee/appstoreconnect-swift-sdk) — iOS CI Newsletter · Issue 56 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Swift
  **Published:** `2024-12-02T00:00:00.000Z`
  **NeKI brief:** Examines this project, focusing on the app store connect api is available and documented! straight away, antoine van der lee jumped into action and started…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [⏭️ Bumping a Swift Package’s version using Fastlane](https://nowham.dev/posts/fastlane-version-bump) — iOS CI Newsletter · Issue 55 — Article · Topics: CI/CD & Automation · Swift · Swift Package Manager
  **Published:** `2024-11-17T00:00:00.000Z`
  **NeKI brief:** Examines Bumping a Swift Package’s version using Fastlane in the context of CI/CD & Automation and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Xcode stops fetching Swift packages](https://danielsaidi.com/blog/2024/11/04/xcode-stops-fetching-swift-packages) — iOS Dev Weekly · Issue 686 — Article · Topics: Swift · Swift Package Manager · Xcode
  **Published:** `8th November 2024`
  **NeKI brief:** Presents xcode stops fetching swift packages for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Test Linux compatibility for Swift packages](https://www.fline.dev/test-your-swift-packages-linux-compatibility-on-mac) — iOS Dev Weekly · Issue 684 — Article · Topics: Product Design · Swift · Testing
  **Published:** `25th October 2024`
  **NeKI brief:** Presents test linux compatibility for swift packages for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [📦 How to edit Swift Packages from the command line](https://www.andrea-scuderi.com/blog/edit-swift-package-from-command-line) — iOS CI Newsletter · Issue 52 — Article · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2024-10-06T00:00:00.000Z`
  **NeKI brief:** Walks through how to edit Swift Packages from the command line, with practical context for Developer Tools and Swift. Use it when implementing the workflow, while checking current tool and platform versions before copying the setup.
- [The Future of Vapor](https://blog.vapor.codes/posts/the-future-of-vapor) — iOS Dev Weekly · Issue 677 — Article · Topics: Swift · Swift Package Manager
  **Published:** `6th September 2024`
  **NeKI brief:** Presents the future of vapor for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Extending SwiftPM Metadata](https://alejandromp.com/development/blog/swift-package-manager-dependency-owners) — iOS Dev Weekly · Issue 677 — Article · Topics: Dependency Injection · Swift
  **Published:** `6th September 2024`
  **NeKI brief:** Presents extending swiftpm metadata for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [📦 Define ownership of Swift Package Manager dependencies](https://alejandromp.com/blog/swift-package-manager-dependency-owners) — iOS CI Newsletter · Issue 49 — Article · Topics: Dependency Injection · Swift · Swift Package Manager
  **Published:** `2024-08-25T00:00:00.000Z`
  **NeKI brief:** Examines Define ownership of Swift Package Manager dependencies in the context of Dependency Injection and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Plotting a Path to a Package Ecosystem without Data Race Errors](https://www.swift.org/blog/ready-for-swift-6) — iOS Dev Weekly · Issue 668 — Article · Topics: Swift · Swift Package Manager · Testing
  **Published:** `5th July 2024`
  **NeKI brief:** Presents plotting a path to a package ecosystem without data race errors for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Swift Package Manager framework creation in Xcode](https://www.avanderlee.com/swift/creating-swift-package-manager-framework?ref=createwithswift.com) — Create with Swift · Issue 16 — Article · Topics: Swift · Swift Package Manager · Xcode
  **Published:** `2024-06-07T15:00:34.000Z`
  **NeKI brief:** Creates a Swift package in Xcode and covers Package.swift configuration, platform requirements, dependencies, and local development-package workflows.
- [@_spi or How to develop better APIs in Swift](https://varanios.com/articles/spi-or-how-to-develop-better-apis-in-swift) — iOS Dev Weekly · Issue 662 — Article · Topics: Code Quality · Swift · Swift Package Manager
  **Published:** `24th May 2024`
  **NeKI brief:** Explains Swift’s @_spi boundary for exposing experimental or specialist API to selected clients without making it generally public. Useful for library authors weighing staged API development against the maintenance risk of relying on an underscored language feature.
- [Swift Package Indexing](https://podcasts.apple.com/us/podcast/43-now-im-worried-our-metrics-arent-correct-with/id1654567329?i=1000653584114) — iOS CI Newsletter · Issue 42 — Podcast · Topics: Developer Community & Business · Swift · Swift Package Manager
  **Published:** `2024-05-19T00:00:00.000Z`
  **NeKI brief:** Examines Swift Package Indexing in the context of Developer Community & Business and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [15th of March, the Swift language team created the release branch for Swift 6](https://forums.swift.org/t/swift-6-0-release-process/70220) — iOS CI Newsletter · Issue 42 — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **Published:** `2024-05-19T00:00:00.000Z`
  **NeKI brief:** post. This link is retained as a technical reading lead for Apple-platform development.
- [making snapshots from this branch regularly available for download](https://www.swift.org/download) — iOS CI Newsletter · Issue 42 — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **Published:** `2024-05-19T00:00:00.000Z`
  **NeKI brief:** Examines making snapshots from this branch regularly available for download in the context of Objective-C & Cocoa and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🐌 Why does fetching SPM packages take so long?](https://ahmdyasser.medium.com/why-fetching-packages-using-swift-package-manger-takes-too-much-time-138982a0fba5) — iOS CI Newsletter · Issue 42 — Article · Topics: Swift · Swift Package Manager
  **Published:** `2024-05-19T00:00:00.000Z`
  **NeKI brief:** Examines Why does fetching SPM packages take so long? in the context of Swift and Swift Package Manager. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [How to use custom fonts and images in a Swift Package](https://dev.jeremygale.com/swiftui-how-to-use-custom-fonts-and-images-in-a-swift-package) — SwiftUI Weekly · SwiftUI Weekly - Issue #186 — Article · Topics: Swift · Swift Package Manager · SwiftUI
  **Published:** `2024-05-15T12:55:37.453Z`
  **NeKI brief:** Explains bundling custom fonts and images in a Swift package for SwiftUI. Useful for reusable modules that must load resources through their package bundle reliably.
- [password manager](https://github.com/DelMonteAJ/CryptOh.swiftpm) — iOS Dev Weekly · Issue 658 — Source repository · Topics: Developer Tools · Security & Privacy · Spatial Computing
  **Published:** `26th April 2024`
  **NeKI brief:** Their apps are impressive, too, with AJ creating a password manager using CryptoKit and Dezmond making a mountain biking companion app using ARKit.
- [new Benchmarks Swift Package](https://github.com/ordo-one/package-benchmark) — iOS CI Newsletter · Issue 38 — Source repository · Topics: Performance · Swift · Swift Package Manager
  **Published:** `2024-03-24T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for new Benchmarks Swift Package, relevant to Performance and Swift. Inspect its implementation, open issues, and release state before adopting the approach.
- [Swift 6.0 Release Process](https://forums.swift.org/t/70220) — iOS Dev Weekly · Issue 649 — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **Published:** `23rd February 2024`
  **NeKI brief:** Examines Swift 6.0 Release Process This post describes the release process, and estimated schedule for Swift 6.0. Snapshots of Swift 6.0 Downloadable snapshots of the Swift 6.0 release bran. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Nominations for the Swift.org Community Showcase Packages Page](https://forums.swift.org/t/nominations-for-the-packages-community-showcase-on-swift-org/68168) — iOS Dev Weekly · Issue 646 — Article · Topics: Developer Community & Business · Swift · Swift Package Manager
  **Published:** `2nd February 2024`
  **NeKI brief:** For me, the most exciting part of this page is the Community Showcase, which we will update monthly with community-nominated packages. The first showcase highlights some packages recently discussed on Swift-related podcasts, but the doors are open for…
- [Community Showcase](https://www.swift.org/packages/showcase.html) — iOS Dev Weekly · Issue 646 — Article · Topics: Cross-Platform & Web · Developer Community & Business · Swift
  **Published:** `2nd February 2024`
  **NeKI brief:** For me, the most exciting part of this page is the Community Showcase, which we will update monthly with community-nominated packages. The first showcase highlights some packages recently discussed on Swift-related podcasts, but the doors are open for…
- [The Swift Package Index lives on the island of Swiftoria](https://anvaka.github.io/map-of-github) — iOS Dev Weekly · Issue 641 — Article · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `29th December 2023`
  **NeKI brief:** Presents the swift package index lives on the island of swiftoria for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [the Swift Package Index received support from Apple](https://www.swift.org/blog/swift-package-index-developer-spotlight) — iOS Dev Weekly · Issue 640 — Article · Topics: App Intents & System Surfaces · Swift · Swift Package Manager
  **Published:** `15th December 2023`
  **NeKI brief:** Explores this blog post, focusing on you may have already seen the latest post on the. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [new macro-based open-source proof of concept Swift package](https://github.com/apple/swift-testing) — iOS CI Newsletter · Issue 29 — Source repository · Topics: Macros & Metaprogramming · Swift · Testing
  **Published:** `2023-11-19T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for new macro-based open-source proof of concept Swift package, relevant to Macros & Metaprogramming and Swift. Inspect its implementation, open issues, and release state before adopting the approach.
- [Swift Mentorship Program](https://www.swift.org/mentorship) — iOS Dev Weekly · Issue 635 — Article · Topics: Swift · Swift Package Manager
  **Published:** `10th November 2023`
  **NeKI brief:** Examines Swift is a general-purpose programming language built using a modern approach to safety, performance, and software design patterns. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [On-Crash Backtraces in Swift](https://www.swift.org/blog/swift-5.9-backtraces) — iOS Dev Weekly · Issue 635 — Podcast · Topics: Developer Community & Business · Product Design · Swift
  **Published:** `10th November 2023`
  **NeKI brief:** Presents on-crash backtraces in swift for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [creating a command line tool](https://www.swift.org/getting-started/cli-swiftpm) — iOS Dev Weekly · Issue 634 — Article · Topics: Developer Tools · Personal Essays · Swift
  **Published:** `3rd November 2023`
  **NeKI brief:** Uses SwiftPM’s executable-package workflow to build a command-line tool, providing a concrete starting point for scripts and developer utilities written in Swift.
- [we added](https://www.swift.org/blog/packages-page) — iOS Dev Weekly · Issue 634 — Article · Topics: Swift · Swift Package Manager
  **Published:** `3rd November 2023`
  **NeKI brief:** Then, yesterday, we added a new Packages page that showcases a selection of packages from across the Swift package ecosystem.
- [Packages page](https://www.swift.org/packages) — iOS Dev Weekly · Issue 634 — Article · Topics: Swift · Swift Package Manager
  **Published:** `3rd November 2023`
  **NeKI brief:** Then, yesterday, we added a new Packages page that showcases a selection of packages from across the Swift package ecosystem.
- [Breadcrumbs](https://github.com/icanzilb/Breadcrumbs) — iOS Dev Weekly · Issue 633 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `27th October 2023`
  **NeKI brief:** Presents breadcrumbs for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [📦 Swift Package template](https://github.com/mattmassicotte/PackageTemplate) — iOS CI Newsletter · Issue 25 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2023-09-24T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for Swift Package template, relevant to Developer Tools and Swift. Inspect its implementation, open issues, and release state before adopting the approach.
- [ExampleKit](https://forums.swift.org/t/in-app-libraries-for-swift-playgrounds-on-ipad/67241) — iOS Dev Weekly · Issue 627 — Article · Topics: Swift · Swift Package Manager · Xcode
  **Published:** `15th September 2023`
  **NeKI brief:** Presents examplekit for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [project](https://github.com/toph42/ExampleKit) — iOS Dev Weekly · Issue 627 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `15th September 2023`
  **NeKI brief:** Provides the ExampleKit source for embedding Swift libraries in iPad Swift Playgrounds; inspect its package layout when sharing reusable code with playground-based clients.
- [Introducing ObservableConverter](https://lickability.com/blog/introducing-observableconverter) — iOS Dev Weekly · Issue 624 — Article · Topics: Macros & Metaprogramming · Swift
  **Published:** `25th August 2023`
  **NeKI brief:** Explores Introducing ObservableConverter, focusing on apple has a well-written guide and some sample code for migrating from the observable object protocol to the new observable macro, but. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [and yet…](https://github.com/apple/swift-argument-parser/blob/8f4d2753f0e4778c76d5f05ad16c74f707390531/Package.swift) — iOS Dev Weekly · Issue 623 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `18th August 2023`
  **NeKI brief:** The Swift Argument Parser repository file defines the package manifest and its publicly readable package configuration.
- [Xcode Search Scopes](https://xcode.tips/search-scopes) — iOS Dev Weekly · Issue 621 — Article · Topics: Objective-C & Cocoa · Swift · Xcode
  **Published:** `4th August 2023`
  **NeKI brief:** Explores Xcode Search Scopes, focusing on i’m a fan of the xcode feature in this latest. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [🧰 How to create a binary framework from a Swift Package](https://blog.eidinger.info/why-is-it-so-damn-difficult-to-create-a-binary-framework-for-your-swift-package) — iOS CI Newsletter · Issue 21 — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **Published:** `2023-07-31T00:00:00.000Z`
  **NeKI brief:** Walks through how to create a binary framework from a Swift Package, with practical context for Objective-C & Cocoa and Swift. Use it when implementing the workflow, while checking current tool and platform versions before copying the setup.
- [☁️ Xcode Cloud: Using swift packages that require authentication](https://blog.eidinger.info/using-swift-packages-with-authentication-in-xcode-cloud) — iOS CI Newsletter · Issue 20 — Article · Topics: Swift · Swift Package Manager · Xcode
  **Published:** `2023-07-16T00:00:00.000Z`
  **NeKI brief:** Examines Xcode Cloud: Using swift packages that require authentication in the context of Swift and Swift Package Manager. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [an article last year](https://blog.eidinger.info/xcode-133-supports-spm-binary-dependency-in-private-github-release) — iOS CI Newsletter · Issue 20 — Article · Topics: Developer Tools · Objective-C & Cocoa · Xcode
  **Published:** `2023-07-16T00:00:00.000Z`
  **NeKI brief:** Examines an article last year in the context of Developer Tools and Objective-C & Cocoa. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Apple’s Argument Parser](https://github.com/apple/swift-argument-parser) — iOS CI Newsletter · Issue 19 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2023-07-02T00:00:00.000Z`
  **NeKI brief:** swift-argument-parser declares command-line options, arguments, subcommands, validation, and help in typed Swift definitions. Use it when a developer tool needs discoverable CLI behavior without manually parsing argv or maintaining usage text separately.
- [📦 This GitHub Action helps you keep SPM dependencies up to date!](https://github.com/MarcoEidinger/swift-package-dependencies-check) — iOS CI Newsletter · Issue 19 — Source repository · Topics: Dependency Injection · Developer Tools · Objective-C & Cocoa
  **Published:** `2023-07-02T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for This GitHub Action helps you keep SPM dependencies up to date!, relevant to Dependency Injection and Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [GitHub Dependency Graph, Dependabot Alerts, and Advisory Database now support Swift advisories](https://github.blog/changelog/2023-06-19-dependency-graph-dependabot-alerts-and-advisory-database-now-support-swift-advisories) — iOS Dev Weekly · Issue 615 — Article · Topics: Developer Tools · Persistence & Synchronisation · Swift
  **Published:** `23rd June 2023`
  **NeKI brief:** Explores GitHub Dependency Graph, Dependabot Alerts, and Advisory Database now support Swift advisories, focusing on if you have worked with other languages, you’ve likely come. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Introspect for SwiftUI - Unleashing the Power of UIKit and AppKit in SwiftUI](https://github.com/intitni/CopilotForXcode) — iOS Dev Tools · 🔨 Swift Power Unleashed & More AI — Source repository · Topics: Swift · SwiftUI · UIKit
  **Published:** `2023-06-08T13:48:24.016Z`
  **NeKI brief:** Describes Copilot for Xcode, focusing on practical tool integration and workflow trade-offs. Use it to evaluate reproducibility, trust boundaries, and debugging steps before adopting the approach in an Xcode project.
- [Swift 5.8 Released](https://www.swift.org/blog/swift-5.8-released) — iOS Dev Weekly · Issue 603 — Article · Topics: Apple Platform Ecosystem · Swift · Swift Package Manager
  **Published:** `31st March 2023`
  **NeKI brief:** Presents a concrete implementation of Swift 5.8 Released!. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.
- [Xcode Header Template for Swift PackagesIf you use Swift Package, there are 2 pesky problems whenever you create a new file.@samwize](https://samwize.com/2023/02/28/xcode-header-template-for-swift-packages?ref=ioscodereview.com) — iOS Code Review · Issue 44 — Article · Topics: Swift · Swift Package Manager · Xcode
  **Published:** `2023-03-02T12:48:03.000Z`
  **NeKI brief:** Examines Xcode Header Template for Swift PackagesIf you use Swift Package, there are 2 pesky problems whenever you… in the context of Swift and Swift Package Manager. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Swift package resolution and data usage](https://christiantietze.de/posts/2023/01/xcode-requires-data-connection-for-swift-package-resolution) — iOS CI Newsletter · Issue 8 — Article · Topics: Swift · Swift Package Manager · Xcode
  **Published:** `2023-01-29T00:00:00.000Z`
  **NeKI brief:** Examines Swift package resolution and data usage in the context of Swift and Swift Package Manager. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Utilizing Makefiles for Swift projects](https://theswiftdev.com/utilizing-makefiles-for-swift-projects) — iOS Dev Weekly · Issue 592 — Article · Topics: Swift · Swift Package Manager
  **Published:** `13th January 2023`
  **NeKI brief:** Like Tibor Bödecs, we’re big fans of a Makefile over at the Swift Package Index, as we have 35 tasks defined in ours. 😳 Context sensitive-shortcuts are great, and the possibilities are limitless! 👍
- [defined in ours](https://github.com/SwiftPackageIndex/SwiftPackageIndex-Server/blob/main/Makefile) — iOS Dev Weekly · Issue 592 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `13th January 2023`
  **NeKI brief:** Explains defined in ours, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [Soto and Swift Build Plugin experiments](https://soto.codes/2022/12/build-plugin-experiments.html) — iOS Dev Weekly · Issue 588 — Article · Topics: Cross-Platform & Web · Swift · Swift Package Manager
  **Published:** `9th December 2022`
  **NeKI brief:** Explores Soto and Swift Build Plugin experiments, focusing on code generation during a swift package build process is a. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Setting up a build tool plugin for a Swift package](https://augmentedcode.io/2022/11/28/setting-up-a-build-tool-plugin-for-a-swift-package) — iOS Dev Weekly · Issue 588 — Article · Topics: Swift · Swift Package Manager
  **Published:** `9th December 2022`
  **NeKI brief:** Explores Setting up a build tool plugin for a Swift package, focusing on talking of build plugins, toomas vahter has written up how he approached building one. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Binary Targets in Swift Package Manager](https://www.avanderlee.com/optimization/binary-targets-swift-package-manager) — iOS CI Newsletter · Issue 3 — Article · Topics: Performance · Swift · Swift Package Manager
  **Published:** `2022-11-20T00:00:00.000Z`
  **NeKI brief:** Examines Binary Targets in Swift Package Manager in the context of Performance and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [swift-danger](https://github.com/danger/swift) — iOS CI Newsletter · Issue 3 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2022-11-20T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for swift-danger, relevant to Developer Tools and Swift. Inspect its implementation, open issues, and release state before adopting the approach.
- [how pre-building it as a binary can certainly help improve performance](https://github.com/danger/swift/issues/476) — iOS CI Newsletter · Issue 3 — Source repository · Topics: Performance · Swift · Swift Package Manager
  **Published:** `2022-11-20T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for how pre-building it as a binary can certainly help improve performance, relevant to Performance and Swift. Inspect its implementation, open issues, and release state before adopting the approach.
- [Swift Snippets](https://forums.swift.org/t/swift-snippets/51947/1) — iOS Dev Weekly · Issue 585 — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **Published:** `18th November 2022`
  **NeKI brief:** Explores Swift Snippets, focusing on like marco eidinger, i was also reminded of the swift snippets feature in swift package manager as i read the post on. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [integration with DocC](https://github.com/apple/swift-evolution/blob/main/proposals/0356-swift-snippets.md) — iOS Dev Weekly · Issue 585 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `18th November 2022`
  **NeKI brief:** Explores integration with DocC, focusing on the article discusses don’t link to swift evolution proposals often,. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [1](https://github.com/SwiftPackageIndex/UpdateImages) — iOS Dev Weekly · Issue 581 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `21st October 2022`
  **NeKI brief:** That’s changed recently, and it’s primarily down to one Swift package, swift-argument-parser. I built two small command line tools for some behind-the-scenes work on the Swift Package Index recently (1, 2) and used argument parser for both.
- [2](https://github.com/SwiftPackageIndex/UpdateCommunitySponsors) — iOS Dev Weekly · Issue 581 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `21st October 2022`
  **NeKI brief:** Examines That’s changed recently, and it’s primarily down to one Swift package, swift-argument-parser. I built two small command line tools for some behind-the-scenes work on the Swift Package Index recently (1, 2) and used argum Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [latest article](https://artandscienceofcoding.com/science/kmm-for-ios-engineers) — iOS Dev Weekly · Issue 577 — Article · Topics: Swift · Swift Package Manager · Testing
  **Published:** `23rd September 2022`
  **NeKI brief:** Explores latest article, focusing on the article discusses had an email from derek lee this week informing me about his latest article on getting started with kotlin. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Kotlin Multiplatform](https://kotlinlang.org/docs/multiplatform.html) — iOS Dev Weekly · Issue 577 — Article · Topics: Cross-Platform & Web · Swift · Swift Package Manager
  **Published:** `23rd September 2022`
  **NeKI brief:** Documents Kotlin Multiplatform and its shared-code model. Useful for comparing cross-platform sharing boundaries with native UI and platform integration requirements in an Apple-platform project.
- [The Lighter Swift Codegen for SQLite3](https://www.alwaysrightinstitute.com//lighter) — iOS Dev Weekly · Issue 572 — Article · Topics: Developer Tools · Persistence & Synchronisation · Swift
  **Published:** `19th August 2022`
  **NeKI brief:** Explores The Lighter Swift Codegen for SQLite3, focusing on there’s a lot going on in this post from helge. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Autocompletion for SPM Commands](https://blog.eidinger.info/autocompletion-for-swift-package-manager-commands) — iOS Dev Weekly · Issue 571 — Article · Topics: Objective-C & Cocoa · Swift
  **Published:** `12th August 2022`
  **NeKI brief:** Explores Autocompletion for SPM Commands, focusing on here’s a helpful post from marco eidinger on how to. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [SwiftUI: Packaging Views](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyJnY9UnVGQ05FZjRQN0UiLCJwb3N0X2lkIjoiZmM1Y2I3MDEtMzdkNy00YTFjLWI1ZmUtMGY3NjAzYzcxNDVmIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6ImNhNWVmMDA2LWIzZWMtNDcyZi1iNDgxLTIyMzdlYjE4NmZjNyIsImlhdCI6MTY3NDA2MjU1Ny45ODUsImlzcyI6Im9yY2hpZCJ9.AFv-2mqF3eMA1R73dQIGybln7ZQiPjXYo6Lnf1zbyHE) — SwiftUI Weekly · SwiftUI Weekly - Issue #111 — Article · Topics: Swift · Swift Package Manager · SwiftUI
  **Published:** `2022-08-01T20:26:06.000Z`
  **NeKI brief:** Demonstrates packaging SwiftUI views into a reusable Swift Package. Use the project structure and target boundaries to decide what views, resources, and platform availability contracts should be exported from a shared UI module.
- [Swift Package Plugins and Xcode 14](https://blog.eidinger.info/xcode-integration-of-swift-package-plugins-in-xcode-14) — iOS Dev Weekly · Issue 563 — Tutorial · Topics: Swift · Swift Package Manager · Xcode
  **Published:** `17th June 2022`
  **NeKI brief:** Explores Swift Package Plugins and Xcode 14, focusing on the article discusses wasn’t expecting apple to turn around and. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Beginner’s guide to Swift package manager command plugins](https://theswiftdev.com/beginners-guide-to-swift-package-manager-command-plugins) — iOS Dev Weekly · Issue 559 — Article · Topics: Swift · Swift Package Manager
  **Published:** `20th May 2022`
  **NeKI brief:** Explores Beginner’s guide to Swift package manager command plugins, focusing on the plugin system introduced with the 5.6 release of swiftpm. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Building multi-platform documentation with DocC](https://danielsaidi.com/blog/2022/04/27/building-multi-platform-documentation-with-docc) — iOS Dev Weekly · Issue 557 — Article · Topics: Swift · Swift Package Manager
  **Published:** `6th May 2022`
  **NeKI brief:** Explores Building multi-platform documentation with DocC, focusing on we’re working on something related to docc over on the. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [major release](https://github.com/mapbox/mapbox-navigation-native-ios/commit/b648000b9f5d10df5c4401cd4732c30f122af4b9) — iOS Dev Weekly · Issue 555 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `22nd April 2022`
  **NeKI brief:** Examines Contribute to mapbox/mapbox-navigation-native-ios development by creating an account on GitHub. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Swift Bundler v2](https://forums.swift.org/t/swift-bundler-create-macos-apps-with-swiftpm-instead-of-xcodeprojs/56790) — iOS Dev Weekly · Issue 555 — Article · Topics: Swift · Swift Package Manager · Xcode
  **Published:** `22nd April 2022`
  **NeKI brief:** Explores Swift Bundler v2, focusing on talking of doing a great job at informing people of. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [SPI benchmark tool](https://github.com/SwiftPackageIndex/spi-benchmark) — iOS Dev Weekly · Issue 549 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `11th March 2022`
  **NeKI brief:** Explores SPI benchmark tool, focusing on what began as an experiment to test how fast our. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Hosting your Swift Library Docs on Github Pages](https://rhonabwy.com/2022/01/28/hosting-your-swift-library-docs-on-github-pages) — iOS Dev Weekly · Issue 544 — Article · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `4th February 2022`
  **NeKI brief:** Explores Hosting your Swift Library Docs on Github Pages, focusing on there’s so much good stuff in this post from joseph. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [swift-docc-plugin](https://github.com/apple/swift-docc-plugin) — iOS Dev Weekly · Issue 544 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `4th February 2022`
  **NeKI brief:** Explores swift-docc-plugin, focusing on there’s so much good stuff in this post from joseph heck. he begins by talking about the upcoming plugin changes to the. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [external build tools](https://github.com/apple/swift-evolution/blob/main/proposals/0303-swiftpm-extensible-build-tools.md) — iOS Dev Weekly · Issue 543 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `28th January 2022`
  **NeKI brief:** Examines SE-0303 – Package Manager Extensible Build Tools, focusing on so, i was delighted to come across se-0303 – package manager extensible build tools, currently in review. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [#1228](https://github.com/SwiftPackageIndex/SwiftPackageIndex-Server/issues/1228) — iOS Dev Weekly · Issue 535 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `26th November 2021`
  **NeKI brief:** That experience permanently aligned me with Russ’s thinking, and I now err on the side of caution when releasing features. For example, there are two enhancements to search in the Swift Package Index (#1228 and #1320 specifically) in progress right now…
- [#1320](https://github.com/SwiftPackageIndex/SwiftPackageIndex-Server/issues/1320) — iOS Dev Weekly · Issue 535 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `26th November 2021`
  **NeKI brief:** Examines We’re so close to this feature! @finestructure and I chatted through the last couple of bits this morning and here’s a list: Search should return multiple matches for authors from. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Adding DocC to an existing swift package](https://rhonabwy.com/2021/11/24/adding-docc-to-an-existing-swift-package) — iOS Dev Weekly · Issue 535 — Article · Topics: Swift · Swift Package Manager
  **Published:** `26th November 2021`
  **NeKI brief:** Examines During WWDC 21, Apple announced that they would be open sourcing documentation tooling (DocC) that’s used to build and provide documentation within Apple. At the tail end of. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [SimulatorStatusMagic](https://github.com/shinydevelopment/SimulatorStatusMagic) — iOS Dev Weekly · Issue 533 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `12th November 2021`
  **NeKI brief:** Provides the Simulator Status Magic source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [new README](https://github.com/SwiftPackageIndex/SwiftPackageIndex-Server/blob/main/README.md) — iOS Dev Weekly · Issue 533 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `12th November 2021`
  **NeKI brief:** The project README gives the high-level orientation for the Swift Package Index server codebase and its contribution surface. Use it before inspecting implementation details to understand the repository’s purpose, major components, and expected local development entry points.
- [guide to setting up for local development](https://github.com/SwiftPackageIndex/SwiftPackageIndex-Server/blob/main/LOCAL_DEVELOPMENT_SETUP.md) — iOS Dev Weekly · Issue 533 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `12th November 2021`
  **NeKI brief:** Documents the local-development setup for the Swift Package Index server, making its environment and workflow inspectable without inference. Useful as a concrete example of onboarding documentation for a nontrivial Swift service with repository-specific tooling and dependencies.
- [set of discussion forums](https://github.com/SwiftPackageIndex/SwiftPackageIndex-Server/discussions) — iOS Dev Weekly · Issue 533 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `12th November 2021`
  **NeKI brief:** So, this week, I did some re-organisation on the Swift Package Index project to get us into a better place to welcome all contributions from the smallest idea or bug report to complete pull requests. There’s a new README, an updated guide to setting up for…
- [Swift Playgrounds App Projects](https://skyaaron.com/posts/swiftpm-app-projects) — iOS Dev Weekly · Issue 533 — Article · Topics: Swift · Swift Package Manager
  **Published:** `12th November 2021`
  **NeKI brief:** I briefly mentioned the new playground format a couple of weeks ago, but Aaron Sky digs into it in detail with this post. We still need Swift Playgrounds 4 to have the complete picture, but it can’t be far away now.
- [SwiftLint for Swift Packages](https://blog.timac.org/2021/1003-swiftlint-for-swift-packages) — iOS Dev Weekly · Issue 528 — Article · Topics: Swift · Swift Package Manager
  **Published:** `8th October 2021`
  **NeKI brief:** Explains integrating SwiftLint with Swift packages despite the absence of an ordinary Xcode build phase. Useful for teams that want consistent style enforcement across app targets and SwiftPM modules without silently leaving package code uncovered.
- [SwiftUI Tools with SwiftPM](http://www.alwaysrightinstitute.com//tows) — iOS Dev Weekly · Issue 522 — Article · Topics: Swift · SwiftUI · Xcode
  **Published:** `27th August 2021`
  **NeKI brief:** Explores SwiftUI Tools with SwiftPM, focusing on can you write a swiftui app without an xcode project? helge heß has a go. Follow it to assess the approach, its trade-offs, and where it fits in a current Swift or Apple-platform project.
- [Setup SwiftUI App with Firebase SPM](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD9mZWF0dXJlPXlvdXR1LmJlJnV0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXImdj1sLWlOMGtZX2JtZyIsInBvc3RfaWQiOiI5ODU0MmZlMy05ZTlmLTRmZjgtOTljMC00NDg3NTczYmQ2NDIiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiZTBkMTY3OTItMWZmNS00YTIxLTk4NGMtNGU5NDE4YjlhMzllIiwiaWF0IjoxNjc0MDYyNjc3LjAxLCJpc3MiOiJvcmNoaWQifQ.WIHfKf395U66uMHaK5JZw1hIXIbu9ISyoHi28IKOEX4) — SwiftUI Weekly · SwiftUI Weekly - Issue #63 — Tutorial · Topics: Swift · Swift Package Manager · SwiftUI
  **Published:** `2021-06-14T22:35:11.000Z`
  **NeKI brief:** Shows wiring a SwiftUI app to Firebase through Swift Package Manager. Follow it for the package integration and initialization boundaries, then verify current Firebase setup requirements before shipping.
- [SwiftPM Library](https://daveverwer.com/blog/launching-the-swiftpm-library) — iOS Dev Weekly · Issue 503 — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **Published:** `16th April 2021`
  **NeKI brief:** Explores SwiftPM Library, focusing on the original idea for building a package search engine popped into my head around two years before the launch of the index. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Introducing Swift Collections](https://swift.org/blog/swift-collections) — iOS Dev Weekly · Issue 502 — Article · Topics: Swift · Swift Package Manager · Testing
  **Published:** `9th April 2021`
  **NeKI brief:** Explores Introducing Swift Collections, focusing on have you ever wished for an ordered dictionary? me too!. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [pure-swift-ui](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2dpdGh1Yi5jb20vQ29kZVNsaWNpbmcvcHVyZS1zd2lmdC11aT91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6IjQ3ODZiYWMwLTg1ZWYtNGQzZS04OGE4LTBkZjljZjlkZDliOSIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiJlZmJjMWZmYS1kNTNlLTRiMzQtODdjNi05MjQxNjIzMGVhNmUiLCJpYXQiOjE2NzQwNjI2NzguMjIzLCJpc3MiOiJvcmNoaWQifQ.9fhNu0spGUh4kFzTo_hmUMgdLB4CGkHrWfnx16glS2Q) — SwiftUI Weekly · SwiftUI Weekly - Issue #53 — Article · Topics: Swift · Swift Package Manager · SwiftUI
  **Published:** `2021-04-05T15:38:12.000Z`
  **NeKI brief:** Provides a pure-SwiftUI component implementation and accompanying source to study. Use it as a code reference for composing reusable primitives without UIKit dependencies, while checking its historical API assumptions.
- [in review](https://forums.swift.org/t/45106) — iOS Dev Weekly · Issue 497 — Article · Topics: Swift · Swift Package Manager
  **Published:** `5th March 2021`
  **NeKI brief:** Examines in review, focusing on so, i was delighted to come across se-0303 – package manager extensible build tools, currently in review. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Distributing closed-source frameworks with SPM](https://danielsaidi.com/blog/2021/02/15/distributing-closed-source-frameworks-with-spm) — iOS Dev Weekly · Issue 496 — Article · Topics: Hardware & Devices · Swift · Swift Package Manager
  **Published:** `26th February 2021`
  **NeKI brief:** Covers Distributing closed-source frameworks with SPM, focusing on Swift tooling and build integration. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [Build a news app in SwiftUI 2.0 (Combine, API, MVVM & Swift Package Manager)](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyJnY9TTJwc1gtSndIZEUiLCJwb3N0X2lkIjoiZmI3YTliMDItOWZiMi00MWJkLTlhNGUtMzRjY2JjMzIzZjQxIiwicHVibGljYXRpb25faWQiOiI3OTQ4ZWE2NS1jYjZlLTRjZDUtOTcyYy0zMWY4YzZkNmNkYTQiLCJ2aXNpdF90b2tlbiI6IjA4NWFhZTc4LWY0ZGQtNDk1NS04MDA2LTQyZmIwYzcxMmNhNCIsImlhdCI6MTY3NDA2MjY3OC40MTksImlzcyI6Im9yY2hpZCJ9.9_MYRo5QPnk2BAP2P8aD_71Ckd92WPNekkK-uesvp78) — SwiftUI Weekly · SwiftUI Weekly - Issue #47 — Tutorial · Topics: Swift · Swift Package Manager · SwiftUI
  **Published:** `2021-02-23T19:43:19.000Z`
  **NeKI brief:** Builds a SwiftUI 2 news app using Combine, an API, MVVM, and Swift Package Manager. Use it to inspect boundaries among networking, view models, dependency packaging, and list presentation.
- [Community Survey Results](https://iosdevsurvey.com/2019) — iOS Dev Weekly · Issue 487 — Article · Topics: Developer Community & Business · Swift · Swift Package Manager
  **Published:** `18th December 2020`
  **NeKI brief:** Examines Community Survey Results, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [swift-snapshot-testing](https://github.com/pointfreeco/swift-snapshot-testing) — iOS Dev Weekly · Issue 486 — Source repository · Topics: Cross-Platform & Web · Swift · Testing
  **Published:** `11th December 2020`
  **NeKI brief:** SnapshotTesting can launch UI tests with a specified content-size category, making large accessibility sizes reproducible in image assertions. Follow it to catch Dynamic Type layout regressions that ordinary interaction tests may miss.
- [Arena 1.0](https://finestructure.co/blog/2020/10/29/arena-100) — iOS Dev Weekly · Issue 480 — Article · Topics: Swift · Swift Package Manager · Xcode
  **Published:** `30th October 2020`
  **NeKI brief:** Examines Arena 1.0, offering practical guidance on Swift Package Manager integration. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [here are the raw results](https://iosdevweekly.typeform.com/report/zIF06B/pKBSSNpfGxUiMPGo) — iOS Dev Weekly · Issue 457 — Article · Topics: Developer Community & Business · Swift · Swift Package Manager
  **Published:** `22nd May 2020`
  **NeKI brief:** Last week’s “one question” Swift Package Manager survey wasn’t on the same scale as the full community survey, but it was a nice update on how people feel about the SPM. As promised, here are the raw results. Thanks for taking the time to fill in the survey!
- [~35% of personal projects](https://iosdevsurvey.com/2019/12-dependency-management) — iOS Dev Weekly · Issue 456 — Article · Topics: Developer Career & Practice · Developer Community & Business · Swift Package Manager
  **Published:** `15th May 2020`
  **NeKI brief:** Explains ~35% of personal projects, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [swift-outdated](https://github.com/kiliankoe/swift-outdated) — iOS Dev Weekly · Issue 449 — Source repository · Topics: Dependency Injection · Swift · Swift Package Manager
  **Published:** `27th March 2020`
  **NeKI brief:** Examines swift-outdated, focusing on if you’re using the swift package manager, then kilian koe has a helpful little tool to quickly let you know if you’ve…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Manage automation tasks using Swift Package Manager](https://www.lordcodes.com/articles/manage-automation-tasks-using-spm) — iOS Dev Weekly · Issue 447 — Article · Topics: Swift · Swift Package Manager · Xcode
  **Published:** `13th March 2020`
  **NeKI brief:** Examines Manage automation tasks using Swift Package Manager, offering practical guidance on Swift Package Manager integration. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Another issue with SwiftPM Xcode integration](https://www.jessesquires.com/blog/another-issue-with-swiftpm-xcode-integration) — iOS Dev Weekly · Issue 446 — Article · Topics: Swift · Swift Package Manager · Xcode
  **Published:** `6th March 2020`
  **NeKI brief:** Examines Another issue with SwiftPM Xcode integration, offering practical guidance on Swift Package Manager integration. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Swift Package Continuous Integration Guide](https://learningswift.brightdigit.com/swift-package-continuous-integration-guide) — iOS Dev Weekly · Issue 446 — Article · Topics: CI/CD & Automation · Swift · Swift Package Manager
  **Published:** `6th March 2020`
  **NeKI brief:** Examines Swift Package Continuous Integration Guide, offering practical guidance on Swift Package Manager integration. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Arena](https://finestructure.co/blog/2020/3/3/arena-explore-spm-packages-with-ease) — iOS Dev Weekly · Issue 446 — Article · Topics: Swift · Swift Package Manager · Xcode
  **Published:** `6th March 2020`
  **NeKI brief:** Examines Arena, offering practical guidance on Swift Package Manager integration. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [My experience replacing CocoaPods with SwiftPM](https://www.jessesquires.com/blog/replacing-cocoapods-with-swiftpm) — iOS Dev Weekly · Issue 445 — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **Published:** `28th February 2020`
  **NeKI brief:** Examines My experience replacing CocoaPods with SwiftPM, offering practical guidance on Swift Package Manager integration. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [CocoaPods 1.9 Beta](http://blog.cocoapods.org/CocoaPods-1.9.0-beta) — iOS Dev Weekly · Issue 435 — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **Published:** `20th December 2019`
  **NeKI brief:** Examines CocoaPods 1.9 Beta, offering practical guidance on Swift Package Manager integration. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [The SPMUtility module from the Swift Package Manager](https://rderik.com/blog/command-line-argument-parsing-using-swift-package-manager-s) — iOS Dev Weekly · Issue 431 — Article · Topics: Swift · Swift Package Manager
  **Published:** `22nd November 2019`
  **NeKI brief:** Did you know that there was a full-featured command-line tool options parser hiding inside the SPM source? Derik Ramirez did! This looks like a worthy successor to ddcli which I’ve used several times over the years to make command-line tools.
- [SwiftPM Catalog](https://zeezide.com/en/products/swiftpmcatalog) — iOS Dev Weekly · Issue 430 — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **Published:** `15th November 2019`
  **NeKI brief:** Examines SwiftPM Catalog, offering practical guidance on Swift Package Manager integration. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [manually curated packages](https://github.com/ZeeZide/SwiftPMCatalog/blob/develop/catalog-info.json) — iOS Dev Weekly · Issue 430 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `15th November 2019`
  **NeKI brief:** Explains manually curated packages, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [Package Resources Proposal for the Swift Package Manager](https://forums.swift.org/t/draft-proposal-package-resources/29941) — iOS Dev Weekly · Issue 427 — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **Published:** `25th October 2019`
  **NeKI brief:** Explains Package Resources Proposal for the Swift Package Manager, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [SwiftLibrary](https://github.com/kiliankoe/SwiftLibrary) — iOS Dev Weekly · Issue 425 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Swift
  **Published:** `11th October 2019`
  **NeKI brief:** Examines SwiftLibrary, focusing on first of all, swiftlibrary from kilian koeltzsch – a command-line search tool built on top of the swiftpm library api. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [package source list](https://github.com/daveverwer/SwiftPMLibrary) — iOS Dev Weekly · Issue 425 — Source repository · Topics: Dependency Injection · Developer Tools · Swift
  **Published:** `11th October 2019`
  **NeKI brief:** Examines package source list, focusing on then, the swift dependency graph from adam fowler – a wonderful visualisation of package dependencies that doesn’t use…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [pull requests](https://github.com/daveverwer/SwiftPMLibrary/pulls?q=is%3Apr+is%3Aclosed) — iOS Dev Weekly · Issue 425 — Source repository · Topics: Developer Tools · Swift
  **Published:** `11th October 2019`
  **NeKI brief:** Examines The canonical list of repositories indexed by the Swift Package Index - Pull requests · SwiftPackageIndex/PackageList. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [merged this huge one](https://github.com/daveverwer/SwiftPMLibrary/pull/104) — iOS Dev Weekly · Issue 425 — Source repository · Topics: Developer Tools · Swift
  **Published:** `11th October 2019`
  **NeKI brief:** Plenty of people have also been submitting pull requests to add their packages, and I recently merged this huge one from Kyle Newsome which brought the total number of packages being indexed to over 3,400! 🚀
- [Swift Package Manager combinations](https://jamesdempsey.net/2019/09/12/xcode-11-and-swift-package-manager-combinations) — iOS Dev Weekly · Issue 421 — Article · Topics: Swift · Swift Package Manager · Xcode
  **Published:** `13th September 2019`
  **NeKI brief:** Examines Swift Package Manager combinations, offering practical guidance on Swift Package Manager integration. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [simple, but useful script](https://github.com/StatusQuo/spmready) — iOS Dev Weekly · Issue 421 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `13th September 2019`
  **NeKI brief:** Examines Talking of the Swift Package Manager, Basti Humann has written a simple, but useful script which will take any project with a Podfile and check whether each pod has support for SPM. 👍 Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [feature requests Trello board](https://trello.com/b/VjXFmAoL/swiftpm-library) — iOS Dev Weekly · Issue 416 — Article · Topics: Swift · Swift Package Manager
  **Published:** `9th August 2019`
  **NeKI brief:** Collects Swift Package Manager library ideas and feature requests in a public board. Useful for spotting package-management needs and community pain points, while treating board cards as proposals rather than maintained technical documentation.
- [A first look at Xcode 11’s Swift Package Manager integration](https://wwdcbysundell.com/2019/xcode-swiftpm-first-look) — iOS Dev Weekly · Issue 407 — Article · Topics: Swift · Swift Package Manager · Xcode
  **Published:** `7th June 2019`
  **NeKI brief:** Examines A first look at Xcode 11's Swift Package Manager integration, offering practical guidance on Swift Package Manager integration. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [It’s time to use Swift Package Manager](http://artsy.github.io/blog/2019/01/05/its-time-to-use-spm) — iOS Dev Weekly · Issue 386 — Article · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `11th January 2019`
  **NeKI brief:** Covers It's time to use Swift Package Manager, focusing on Swift tooling and build integration. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [SwiftLint](https://github.com/realm/SwiftLint) — iOS Dev Weekly · Issue 386 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `11th January 2019`
  **NeKI brief:** Presents a concrete implementation of SwiftLint. Use it to compare API choices, state and layout trade-offs, and testing implications before adapting the pattern to a production Apple-platform codebase.
- [SwiftFormat](https://github.com/nicklockwood/SwiftFormat) — iOS Dev Weekly · Issue 386 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `11th January 2019`
  **NeKI brief:** SwiftFormat offers configurable source-formatting rules and a mature command-line workflow. Follow it when comparing formatter policy, rule customization, and repository integration against Apple's swift-format rather than treating formatting as purely cosmetic.
- [Danger](https://github.com/danger/danger) — iOS Dev Weekly · Issue 386 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `11th January 2019`
  **NeKI brief:** Provides the source and change history for Danger, relevant to CI/CD & Automation and Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [Sourcery](https://github.com/krzysztofzablocki/Sourcery) — iOS Dev Weekly · Issue 386 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `11th January 2019`
  **NeKI brief:** Sourcery parses Swift source with templates to generate repetitive implementations such as mocks, equality, or Codable support. Use it when generated boilerplate has stable conventions and the templates can be reviewed as part of source control.
- [Swift REPL Support for Swift Packages](https://swift.org/blog/swiftpm-repl-support) — iOS Dev Weekly · Issue 373 — Article · Topics: Swift · Swift Package Manager
  **Published:** `12th October 2018`
  **NeKI brief:** Examines The swift run command has a new --repl option which launches the Swift REPL with support for importing library targets of a package. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [What’s New in Swift 3.1?](https://www.raywenderlich.com/156352/whats-new-in-swift-3-1) — iOS Dev Weekly · Issue 294 — Article · Topics: Swift · Swift Package Manager · Xcode
  **Published:** `31st March 2017`
  **NeKI brief:** Explores What’s New in Swift 3.1? in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Package.swift Manual](http://blog.krzyzanowskim.com/2016/08/09/package-swift-manual) — iOS Dev Weekly · Issue 264 — Article · Topics: Objective-C & Cocoa · Swift · Swift Package Manager
  **Published:** `18th August 2016`
  **NeKI brief:** Examines Here is documentation for SPM manifest file Package.swift. I couldn't find a list of possible configuration values for Package.swift, so I created one, for future reference. I. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [SPM documentation](https://github.com/apple/swift-package-manager/tree/master/Documentation) — iOS Dev Weekly · Issue 264 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `18th August 2016`
  **NeKI brief:** The page covers “SPM documentation” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Statistics on SwiftPM package usage](https://github.com/czechboy0/swiftpm-packages-statistics) — iOS Dev Weekly · Issue 251 — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `20th May 2016`
  **NeKI brief:** It’s early days for stats like these as the Swift package manager is not yet officially released. However this list of the most popular packages and package authors is going to be something to watch as the package manager gets more adoption. Thanks to Honza…
- [best practices document document](https://github.com/Sedlacek-Solutions/SFSymbolKit/blob/main/BEST_PRACTICES.md) — Not only Swift · Issue 80 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **NeKI brief:** This source repository covers best practices for using type-safe SF Symbols in SwiftUI. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Livestream: Building a Second Brain app - Swift Packages 📦](https://www.youtube.com/watch?v=ACad_6YSMgw) — Not only Swift · Issue 77 — Video · Topics: Swift · Swift Package Manager
  **NeKI brief:** Refactors a growing SwiftUI second-brain application from one Xcode project into multiple Swift packages. The live session is useful for observing practical module boundaries, package configuration, and maintainability trade-offs.
