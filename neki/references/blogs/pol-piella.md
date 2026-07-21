# Pol Piella

Third-party source index. It provides source attribution and routing metadata, not republished article content. Verify article conclusions independently before applying them.

- Archive: [https://www.polpiella.dev/posts](https://www.polpiella.dev/posts)
- Last collected: `2026-07-22T13:00:02Z`
- Indexed entries: **125**

- [Using Cursor in Xcode 27](https://www.polpiella.dev/cursor-xcode-27) — 2026-06-26T00:00:00.000Z
  **NeKI brief:** Explains installing Cursor’s agent CLI, registering it through Xcode 27’s ACP support, and selecting it for new conversations. Follow it when comparing external agent choice with Xcode’s remembered conversation-agent state.
- [How to install Xcode 26's Metal Toolchain on CI/CD](https://www.polpiella.dev/metal-toolchain-ci-cd) — 2025-09-30T00:00:00.000Z
  **NeKI brief:** Shows provisioning Xcode's Metal toolchain in CI/CD. Use it when a project compiles Metal shaders or GPU code outside a developer machine and a runner must install the matching components reproducibly.
- [A Peek into My Debugging Process (With Real Examples)](https://www.polpiella.dev/how-i-fix-bugs-in-my-apps) — 2025-07-22T00:00:00.000Z
  **NeKI brief:** Describes an evidence-first bug-fixing workflow that captures reproduction, narrows the failing path, and adds regression coverage. Useful as a practical debugging process rather than a framework recipe.
- [How to combine lists of Strings into natural and localized sentences in Swift](https://www.polpiella.dev/join-list-of-strings) — 2025-02-02T00:00:00.000Z
  **NeKI brief:** Explains using ListFormatter or formatted instead of joined for natural, localized lists of strings. Use it when composing human-readable sentences that must respect locale grammar and punctuation.
- [How to check if a modifier key is pressed when clicking on a menu bar item in macOS apps](https://www.polpiella.dev/menu-bar-modifier-key) — 2025-01-19T00:00:00.000Z
  **NeKI brief:** AppKit exposes modifier flags on a menu-bar click, while SwiftUI supplies the menu-bar scene and content. Combining both lets an app offer alternate commands without duplicating menu items or relying on a fragile global key monitor.
- [Using withObservationTracking to monitor changes in @Observable properties outside SwiftUI views](https://www.polpiella.dev/observable-outside-of-a-view) — 2025-01-11T00:00:00.000Z
  **NeKI brief:** Uses withObservationTracking to observe @Observable changes outside SwiftUI views. Use it when an imperative coordinator or service needs dependency-aware callbacks without adopting Combine.
- [How to keep your macOS app's menu bar item running after quitting the app](https://www.polpiella.dev/keep-menu-bar-running-after-quitting-app) — 2024-12-31T00:00:00.000Z
  **NeKI brief:** Explains keeping a macOS menu-bar utility available after closing ordinary windows. Use it when separating an app's activation policy, status item, and termination behavior.
- [How to change your app's business model from paid to freemium using StoreKit](https://www.polpiella.dev/paid-app-to-freemium) — 2024-12-06T00:00:00.000Z
  **NeKI brief:** Shows changing an app's business model from paid upfront to freemium using StoreKit's AppTransaction API. Follow it when planning migration logic and entitlement checks, then verify transaction semantics, customer communication, and App Store policy requirements.
- [How to create and upload high-quality App Store assets with RocketSim and Helm](https://www.polpiella.dev/creating-and-uploading-app-store-assets) — 2024-11-20T00:00:00.000Z
  **NeKI brief:** Demonstrates creating App Store screenshots and previews with RocketSim and uploading assets through Helm. Useful for making release marketing repeatable, while reviewing device coverage, localization, metadata accuracy, and App Store Connect validation before submission.
- [Automate GitHub Tasks with GitHub CLI in Actions Workflows: A Step-by-Step Guide](https://www.polpiella.dev/how-to-use-the-github-cli-from-github-actions-workflows) — 2024-11-14T00:00:00.000Z
  **NeKI brief:** GitHub CLI commands in Actions can create and update issues or pull requests using the workflow token, making repository automation reproducible. The setup must scope permissions explicitly so convenience does not become an over-privileged CI credential.
- [Automate Apple app code signing using fastlane match](https://www.polpiella.dev/automate-code-signing-with-fastlane-match) — 2024-11-08T00:00:00.000Z
  **NeKI brief:** fastlane match stores signing certificates and provisioning profiles in a shared encrypted repository, allowing local and CI builds to resolve the same identities. The operational trade-off is central secret management and disciplined repository access.
- [How to automatically update build and version numbers in your app using Fastlane](https://www.polpiella.dev/bump-numbers-ci-cd) — 2024-10-30T00:00:00.000Z
  **NeKI brief:** Fastlane can derive and write build and version numbers during CI, keeping App Store submissions monotonically identifiable without manual Xcode edits. The workflow separates marketing-version policy from automated build increments.
- [How to expedite an app review on the App Store](https://www.polpiella.dev/expedited-app-reviews) — 2024-10-23T00:00:00.000Z
  **NeKI brief:** Explains Apple's expedited App Review process and the circumstances in which a developer can request faster review. Use it as operational guidance for urgent fixes, while documenting impact clearly and treating approval as discretionary rather than guaranteed.
- [How to install the same version of Ruby and Fastlane locally and on CI/CD](https://www.polpiella.dev/install-ruby-and-gems-on-ci-cd) — 2024-10-17T00:00:00.000Z
  **NeKI brief:** Pinning Ruby and gem versions locally and in GitHub Actions removes a hidden source of Fastlane drift. The workflow makes the toolchain reproducible by sharing version files and installing dependencies before signing or release steps.
- [How to listen for property changes in an @Observable class using AsyncStreams](https://www.polpiella.dev/observable-property-changes) — 2024-10-10T00:00:00.000Z
  **NeKI brief:** AsyncStream can bridge Observation changes into an async consumer, replacing ObservableObject publishers while preserving cancellation and backpressure decisions. The comparison clarifies when a stream should be scoped to a task and when direct observation is simpler.
- [How to run Swift Data and Core Data operations in the background and share models across concurrency contexts](https://www.polpiella.dev/core-data-swift-data-concurrency) — 2024-10-04T00:00:00.000Z
  **NeKI brief:** Core Data and SwiftData models are context-bound, so background work must pass IDs or values rather than share managed objects across threads. The article builds a stack around that boundary to prevent races and context violations.
- [How to build a Safari extension with SwiftUI](https://www.polpiella.dev/safari-extensions-swiftui) — 2024-09-25T00:00:00.000Z
  **NeKI brief:** Builds a Safari extension with SwiftUI and the Safari extension APIs, covering message exchange between content and host contexts. Useful for keeping extension UI declarative while respecting process boundaries.
- [How to pass Bindings to views in SwiftUI's NavigationDestination modifier](https://www.polpiella.dev/binding-navigation) — 2024-09-16T00:00:00.000Z
  **NeKI brief:** Passing a Binding through `navigationDestination` requires making the destination's identity and mutable source explicit. The alternatives show how to avoid stale copies while keeping navigation data-driven and compatible with SwiftUI's value semantics.
- [How to make ZStack content fully scrollable in a SwiftUI ScrollView](https://www.polpiella.dev/scrollable-zstack) — 2024-08-28T00:00:00.000Z
  **NeKI brief:** A ZStack with offset children can report a smaller layout size than its visually displaced content, so ScrollView stops too early. Measuring the union of child bounds restores scrolling while preserving the overlap effect.
- [How to use EditorConfig files in Xcode](https://www.polpiella.dev/xcode-editor-config) — 2024-08-22T00:00:00.000Z
  **NeKI brief:** Configures Xcode editor behavior and project-level preferences for a consistent development environment. Useful for reducing setup drift across a team without encoding personal choices in application source.
- [Developer guide to Swift AWS Lambdas](https://www.polpiella.dev/developer-guide-to-swift-aws-lambdas) — 2024-08-15T00:00:00.000Z
  **NeKI brief:** Builds Swift AWS Lambda handlers and discusses deployment, event decoding, and runtime constraints. Useful for evaluating serverless Swift while separating cloud lifecycle concerns from application UI code.
- [How to automatically detect memory leaks on CI/CD using UI tests](https://www.polpiella.dev/automatically-detect-memory-leaks-using-ui-tests) — 2024-08-07T00:00:00.000Z
  **NeKI brief:** Uses XCTMemoryMetric with xcodebuild’s enablePerformanceTestsDiagnostics flag to emit memory graphs for failed UI tests on physical devices, providing a CI-oriented workflow for detecting regressions without simulator-only evidence.
- [How to programmatically parse the contents of an XCResult bundle](https://www.polpiella.dev/parse-contents-of-xcresult-files) — 2024-08-01T00:00:00.000Z
  **NeKI brief:** Shows how to inspect XCResult bundles programmatically, using Apple’s xcresulttool output to extract test names, durations, statuses, attachments, and logs for post-processing in CI pipelines.
- [How to get the checksum of a file in Swift](https://www.polpiella.dev/get-checksum) — 2024-07-25T00:00:00.000Z
  **NeKI brief:** A cross-platform Swift checksum helper streams file bytes into a cryptographic hash instead of loading the whole file into memory. The design keeps verification bounded for large artifacts while making algorithm choice an explicit interoperability decision.
- [How to use recursive functions in Swift](https://www.polpiella.dev/how-to-use-recursive-functions-in-swift) — 2024-07-19T00:00:00.000Z
  **NeKI brief:** Recursive Swift functions need a well-defined base case and a measure that moves toward it; otherwise stack depth becomes the failure mode. The examples clarify when recursion expresses a tree naturally and when iteration is safer.
- [Check if your app has a newer version on the App Store using Swift](https://www.polpiella.dev/newer-version-lookup) — 2024-07-11T00:00:00.000Z
  **NeKI brief:** Checking the App Store for a newer version compares the store's semantic version against the installed bundle version, then turns that result into an optional user prompt. The workflow must tolerate network failure and avoid interrupting normal launches.
- [Show and hide SwiftUI inspectors with an identifiable item](https://www.polpiella.dev/swiftui-inspector-modifier) — 2024-07-03T00:00:00.000Z
  **NeKI brief:** An identifiable item can drive SwiftUI inspector presentation when the stock modifier only exposes limited Boolean-style control. The custom modifier ties inspector content to stable identity, avoiding stale panels during rapid selection changes.
- [Free, on-device translations with the Swift Translation API](https://www.polpiella.dev/swift-translation-api) — 2024-06-19T00:00:00.000Z
  **NeKI brief:** Uses Apple's translation APIs from Swift to request and present translated content. Useful for designing language workflows that handle availability, user consent, and asynchronous translation results explicitly.
- [Getting started with Swift Testing](https://www.polpiella.dev/swift-testing) — 2024-06-12T00:00:00.000Z
  **NeKI brief:** Introduces Swift Testing in the Swift 6 toolchain, then maps representative XCTest cases to the macro-based test and expectation APIs.
- [How to create a SwiftUI floating window in macOS 15](https://www.polpiella.dev/creating-a-floating-window-using-swiftui-in-macos-15) — 2024-06-11T00:00:00.000Z
  **NeKI brief:** A macOS SwiftUI floating window combines scene configuration with AppKit window-level controls to stay movable, resizable, and above other windows. The implementation highlights the boundary where pure SwiftUI ends and NSWindow behavior becomes necessary.
- [Removing components from a Date in Swift](https://www.polpiella.dev/removing-information-from-a-date-in-swift) — 2024-05-30T00:00:00.000Z
  **NeKI brief:** Calendar and DateComponents can rebuild a Date while removing selected components, but timezone and calendar semantics remain part of the result. The article avoids brittle timestamp arithmetic and makes the intended civil-time transformation explicit.
- [How to build segmented circular progress views in SwiftUI with Swift Charts](https://www.polpiella.dev/swiftui-charts-progress-views) — 2024-05-22T00:00:00.000Z
  **NeKI brief:** Builds progress visualizations with Swift Charts and SwiftUI, mapping task values into marks and labels. Useful for dashboards where progress needs accessible, data-driven presentation.
- [Building a Swift package using the Swift 6 language mode](https://www.polpiella.dev/swift-6-language-mode) — 2024-05-15T00:00:00.000Z
  **NeKI brief:** Enabling Swift 6 language mode in a package means selecting a development toolchain and surfacing strict concurrency diagnostics during builds. The article presents this as an incremental migration gate, not a one-line compiler-version upgrade.
- [How to profile your app's performance and Main Thread usage with Instruments and os_signposts](https://www.polpiella.dev/time-profiler-instruments) — 2024-05-08T00:00:00.000Z
  **NeKI brief:** Instruments Time Profiler paired with `os_signpost` links user-visible hangs to measured main-thread spans. The workflow separates sampling evidence from optimization guesses and helps verify that a change moves work off the critical path.
- [Safely unwrap optional values in SwiftUI bindings](https://www.polpiella.dev/safely-unwrap-optional-value-in-swiftui-binding) — 2024-05-01T00:00:00.000Z
  **NeKI brief:** SwiftUI's Binding initializer can project an optional model value into a non-optional control only while the source exists. The pattern keeps editing code simple, but the view must define what happens when the optional becomes nil.
- [Creating an App Store Connect-like picker for macOS with SwiftUI](https://www.polpiella.dev/app-store-connect-like-picker-with-swiftui) — 2024-04-27T00:00:00.000Z
  **NeKI brief:** A macOS picker can combine Menu, Button, hover state, and overlays to reproduce App Store Connect-style selection without a custom AppKit control. The composition keeps interaction declarative while making pointer affordances explicit.
- [Swift 6: Access level on import statements](https://www.polpiella.dev/swift-6-import-access-level) — 2024-04-17T00:00:00.000Z
  **NeKI brief:** Explains Swift 6 import access levels and how they constrain symbols brought into a file. Useful for tightening module boundaries and understanding compiler errors during language-version migration.
- [Use Swift to recursively search for content in a directory's files with Glob patterns and Regular Expressions](https://www.polpiella.dev/recursive-search-glob-and-regex) — 2024-04-11T00:00:00.000Z
  **NeKI brief:** Combining glob matching for candidate files with regular expressions for content search creates a two-stage filter that avoids scanning irrelevant paths. The Swift implementation is a reusable diagnostic workflow for source trees and generated artifacts.
- [Master the reduce operator in Swift and make your code more performant](https://www.polpiella.dev/mastering-the-reduce-operator-in-swift) — 2024-04-03T00:00:00.000Z
  **NeKI brief:** `reduce` folds a sequence into one value, so accumulator shape and initial value determine both correctness and allocation behavior. The examples distinguish expressive aggregation from cases where `map` or a dedicated loop communicates intent better.
- [Multi-platform Swift Package releases with GitHub Actions](https://www.polpiella.dev/multi-platform-swift-package-releases-with-github-actions) — 2024-03-27T00:00:00.000Z
  **NeKI brief:** A tag-triggered GitHub Actions workflow can build and publish a Swift package for several platforms from one release definition. Matrix jobs improve coverage, while artifact naming and signing credentials must remain deterministic.
- [Generate and read analytics reports from the App Store Connect API](https://www.polpiella.dev/analytics-reports-api-app-store-connect) — 2024-03-20T00:00:00.000Z
  **NeKI brief:** App Store Connect analytics reports are generated asynchronously through an API request, then downloaded and parsed after processing completes. The workflow separates report job polling from data ingestion and treats schema changes as a compatibility concern.
- [Core Data staged migrations](https://www.polpiella.dev/staged-migrations) — 2024-03-15T00:00:00.000Z
  **NeKI brief:** Core Data staged migrations split a model change into explicit mapping steps managed by `NSStagedMigrationManager`. This makes complex schema evolution testable and reviewable, while requiring each intermediate model and mapping to remain supported.
- [How to generate Swift interfaces from Pkl configuration files using SPM plugins](https://www.polpiella.dev/how-to-generate-swift-interfaces-from-pkl-files-with-spm-plugins) — 2024-03-06T00:00:00.000Z
  **NeKI brief:** An SPM build-tool plugin can transform Pkl configuration models into Swift interfaces during the build, keeping generated types aligned with configuration schemas. The trade-off is adding a toolchain dependency and making generation failures part of compilation.
- [Validate your XCTest utilities and extensions with unit tests](https://www.polpiella.dev/validate-your-xctest-utilities-with-unit-tests) — 2024-02-29T00:00:00.000Z
  **NeKI brief:** Testing XCTest helpers like production code catches incorrect expectations around asynchronous fulfillment, failure messages, and cleanup. The article turns test infrastructure into a maintained API rather than trusting it implicitly in every suite.
- [Custom Core Data migrations](https://www.polpiella.dev/custom-core-data-migrations) — 2024-02-21T00:00:00.000Z
  **NeKI brief:** Custom Core Data migrations provide a mapping policy for transformations that lightweight inference cannot express. The design keeps legacy data readable while requiring explicit tests for each source-to-destination field conversion.
- [Automating app releases for multiple platforms with Xcode Cloud](https://www.polpiella.dev/cross-platform-app-releases-with-xcode-cloud) — 2024-02-14T00:00:00.000Z
  **NeKI brief:** Xcode Cloud workflows can build and distribute multiple platform targets from shared actions, with environment variables and signing settings kept per product. The setup reduces manual release drift but requires explicit artifact and credential separation.
- [Setting up SharePlay on an iOS app](https://www.polpiella.dev/setting-up-shareplay-on-an-ios-app-from-scratch) — 2024-02-07T00:00:00.000Z
  **NeKI brief:** SharePlay coordinates a group session through GroupActivities, where an activity declares metadata and participants join through system UI. The implementation must separate session lifecycle from app content so interruptions and late joins remain recoverable.
- [Generating beautiful open-graph images dynamically](https://www.polpiella.dev/generating-beautiful-open-graph-images-dynamically) — 2024-01-24T00:00:00.000Z
  **NeKI brief:** Dynamic Open Graph generation combines serverless functions with Satori and resvg to produce social preview images. Follow it to understand the rendering pipeline and deployment boundary rather than generating assets manually for every page.
- [Image to image local Stable Diffusion pipelines with ControlNet in Swift](https://www.polpiella.dev/image-to-image-local-stable-diffusion-pipelines-with-controlnet-and-core-ml) — 2024-01-17T00:00:00.000Z
  **NeKI brief:** A local ControlNet pipeline combines an input image with conditioning data before Core ML inference, trading server privacy for device memory and compute limits. The article is useful for mapping model conversion, preprocessing, and latency as one deployment workflow.
- [How to use Stable Diffusion models in a Swift app](https://www.polpiella.dev/stable-diffusion-swift-apps) — 2024-01-03T00:00:00.000Z
  **NeKI brief:** Running Stable Diffusion in a Swift app requires loading a converted Core ML model, preparing tensors in its expected layout, and decoding generated output. The pipeline keeps inference on-device but makes model size and thermal cost application concerns.
- [How to get the most played Apple Music songs and albums using Swift](https://www.polpiella.dev/most-played-apple-music) — 2023-12-20T00:00:00.000Z
  **NeKI brief:** MusicKit queries a user's authorized library and derives most-played tracks from returned metadata rather than a private analytics endpoint. The workflow must handle authorization, pagination, and missing play-count fields without promising complete history.
- [Enable upcoming Swift features](https://www.polpiella.dev/enable-upcoming-swift-features-in-spm) — 2023-12-13T00:00:00.000Z
  **NeKI brief:** SwiftPM can opt into upcoming language features through compiler settings, allowing a package to test migration work before a feature becomes default. The trade-off is pinning toolchains and documenting which targets share the experimental mode.
- [Distributing a Swift Macro using CocoaPods](https://www.polpiella.dev/cocoapods-swift-macros) — 2023-12-06T00:00:00.000Z
  **NeKI brief:** Details distributing a Swift macro through CocoaPods, including packaging constraints for compiler plugins. Use it when a macro package must support consumers outside SwiftPM and the distribution model changes build integration.
- [How to import Swift macros without using Swift Package Manager](https://www.polpiella.dev/binary-swift-macros) — 2023-11-29T00:00:00.000Z
  **NeKI brief:** Builds binary Swift macros and discusses packaging compiler plugins for consumers. Useful when distributing macro implementations without exposing source, while accounting for toolchain and platform compatibility.
- [Using Swift SDKs to cross-compile Swift packages to Linux](https://www.polpiella.dev/swift-sdks) — 2023-11-24T00:00:00.000Z
  **NeKI brief:** Explains using Swift SDKs to cross-compile packages for Linux and other targets. Use it when separating SDK availability from compiler compatibility in a multi-platform Swift package pipeline.
- [Migrating a Core Data store to an App Group shared container](https://www.polpiella.dev/core-data-migration-app-group) — 2023-11-15T00:00:00.000Z
  **NeKI brief:** Moving a Core Data store into an App Group container combines a filesystem relocation with model loading and coordinated migration. The sequence must preserve the old store until a successful copy and open have been verified.
- [Building and testing Swift packages on Windows using GitHub Actions](https://www.polpiella.dev/running-swift-on-widnows-with-gha) — 2023-11-01T00:00:00.000Z
  **NeKI brief:** GitHub Actions can exercise a Swift package on Windows, exposing filesystem, Foundation, and path assumptions hidden by macOS CI. A matrix job turns portability into a repeatable test rather than a late release surprise.
- [Launching a SwiftUI view from the terminal](https://www.polpiella.dev/launching-a-swiftui-view-from-the-terminal) — 2023-10-18T00:00:00.000Z
  **NeKI brief:** A SwiftUI view launched from a terminal can use a small executable target or preview harness to iterate without the full app lifecycle. The technique is useful for isolated rendering checks, while dependency injection remains necessary for realistic state.
- [Adding an Info.plist file to a Swift executable](https://www.polpiella.dev/info-plist-swift-cli) — 2023-10-11T00:00:00.000Z
  **NeKI brief:** Shows a Swift command-line tool reading and modifying Info.plist data. Useful for build and release automation that needs typed manipulation instead of brittle shell text substitutions.
- [Using Core Data and Swift Data side by side](https://www.polpiella.dev/core-data-and-swift-data) — 2023-10-05T00:00:00.000Z
  **NeKI brief:** Compares running Core Data and SwiftData side by side, focusing on model and persistence boundaries during migration. Follow it when incrementally adopting SwiftData without rewriting an established store all at once.
- [MusicKit and App Clips](https://www.polpiella.dev/musickit-and-app-clips) — 2023-09-27T00:00:00.000Z
  **NeKI brief:** MusicKit in an App Clip must respect both App Clip size and authorization constraints, so the feature should request only the catalog data needed for the immediate task. The integration highlights capability and entitlement boundaries.
- [How to create an App Clip for your app](https://www.polpiella.dev/create-app-clips) — 2023-09-20T00:00:00.000Z
  **NeKI brief:** An App Clip packages a focused invocation path with associated domains and an App Clip target, then hands off to the full app when installed. The workflow makes size, entitlement, and shared-data boundaries part of feature design.
- [Swift on Linux CI/CD using swiftly](https://www.polpiella.dev/setting-up-swift-on-linux-ci-cd-using-swiftly) — 2023-09-13T00:00:00.000Z
  **NeKI brief:** Swiftly pins and installs a chosen Swift toolchain on Linux runners before SwiftPM builds execute. This makes CI versions reproducible and exposes portability failures independently from the developer's local Xcode installation.
- [Xcode 15: Automated accessibility audits](https://www.polpiella.dev/xcode-15-automated-accessibility-audits) — 2023-08-30T00:00:00.000Z
  **NeKI brief:** Shows enabling Xcode 15 accessibility audits in UI tests to detect missing labels, clipped text, contrast failures, and Dynamic Type gaps. It turns an interactive audit into repeatable regression coverage during the UI test flow.
- [Named capture groups in Swift regular expressions](https://www.polpiella.dev/named-capture-groups-in-swift-regular-expressions) — 2023-08-23T00:00:00.000Z
  **NeKI brief:** Named capture groups make Swift regular-expression results addressable by semantic labels instead of numeric offsets. The article is useful for maintainable parsing, especially when patterns evolve and positional indexes become fragile.
- [Building a searchable map with SwiftUI and MapKit](https://www.polpiella.dev/mapkit-and-swiftui-searchable-map) — 2023-08-16T00:00:00.000Z
  **NeKI brief:** Builds a searchable map component with MapKit and SwiftUI's iOS 17 APIs, connecting query results to map annotations. Useful for prototyping location search while evaluating state flow, selection, and map camera updates.
- [Delightful SwiftUI image drag & drop for a macOS app](https://www.polpiella.dev/qreate-drag-and-drop) — 2023-08-09T00:00:00.000Z
  **NeKI brief:** Implements native image drag-and-drop for a macOS SwiftUI app, handling dropped data and integrating it into an editing workflow. Useful when designing desktop interactions that accept Finder assets without custom pasteboard plumbing.
- [Scheduled Swift AWS lambdas](https://www.polpiella.dev/scheduled-swift-aws-lambdas) — 2023-08-02T00:00:00.000Z
  **NeKI brief:** Scheduled Swift Lambdas use CloudWatch events to run work independently of user requests. Follow it to model idempotent recurring jobs, with time zones, failures and permissions handled by the deployment configuration.
- [How to show the app icon and version in a SwiftUI view](https://www.polpiella.dev/show-app-icon-and-version-in-a-swiftui-view) — 2023-07-26T00:00:00.000Z
  **NeKI brief:** Shows how to display an app's icon and version metadata inside a SwiftUI view. Useful for About, diagnostics, and tester-facing screens that need to identify build variants without duplicating configuration values.
- [Load custom fonts into your app using Swift Package Plugins](https://www.polpiella.dev/load-custom-fonts-with-no-code-using-swift-package-plugins) — 2023-07-05T00:00:00.000Z
  **NeKI brief:** Swift Package plugins and code generation automate bundling custom fonts into an app. Follow it to keep resource registration reproducible, while checking plugin sandboxing and build-time versus runtime responsibilities.
- [Configuring SwiftData in a SwiftUI app](https://www.polpiella.dev/configuring-swiftdata-in-a-swiftui-app) — 2023-06-28T00:00:00.000Z
  **NeKI brief:** Walks through configuring SwiftData in a SwiftUI application, including container setup and model access. Useful for establishing persistence boundaries and avoiding accidental model-container creation in previews or tests.
- [Understanding mergeable libraries](https://www.polpiella.dev/understanding-mergeable-libraries) — 2023-06-21T00:00:00.000Z
  **NeKI brief:** Mergeable libraries change how Xcode can combine framework code into an app binary. The article is useful for evaluating launch and distribution trade-offs, while checking binary size and debugging implications per target.
- [Version-specific Package.swift files](https://www.polpiella.dev/version-specific-package-manifests) — 2023-06-14T00:00:00.000Z
  **NeKI brief:** Version-specific Package.swift manifests let a package expose different configurations to different Swift toolchains. Follow it for compatibility planning, keeping divergence minimal so package behavior remains understandable across versions.
- [Xcode Cloud: Generating and translating TestFlight test notes automatically](https://www.polpiella.dev/setting-testflight-test-notes-for-xcode-cloud-builds) — 2023-06-09T00:00:00.000Z
  **NeKI brief:** Xcode Cloud automation generates localized TestFlight test notes through build metadata and APIs. It is useful for treating release communication as pipeline output, with authentication and locale mapping kept outside app code.
- [Automatic deployment of Swift AWS lambdas on CI/CD](https://www.polpiella.dev/automatic-deployment-of-swift-aws-lambdas-on-ci-cd) — 2023-05-31T00:00:00.000Z
  **NeKI brief:** GitHub Actions and the AWS CLI deploy Swift Lambda code after changes reach the main branch. Follow it to inspect artifact packaging, credentials and rollback boundaries before making deployment fully automatic.
- [Private Swift packages on CI/CD](https://www.polpiella.dev/private-swift-packages-on-ci-cd) — 2023-05-24T00:00:00.000Z
  **NeKI brief:** Private Swift packages in CI require authenticated dependency resolution outside a developer’s local keychain. Follow it to scope tokens and SSH credentials narrowly, keeping package access reproducible for automation.
- [How to avoid a big refactor with the @_exported attribute](https://www.polpiella.dev/how-we-avoided-a-big-refactor-with-the-exported-attribute) — 2023-05-17T00:00:00.000Z
  **NeKI brief:** The underscored @_exported attribute re-exports a module to soften an import migration. Follow it as a temporary compatibility tool, recognizing that underscored language features can change and hide dependencies.
- [How to launch a macOS SwiftUI app from a Safari extension](https://www.polpiella.dev/how-to-launch-an-app-from-a-safari-extension) — 2023-05-10T00:00:00.000Z
  **NeKI brief:** A Safari extension communicates with a macOS SwiftUI app to trigger native actions. The guide is useful for defining extension-to-app boundaries, including user activation and secure message validation.
- [Export SwiftUI views as images in macOS](https://www.polpiella.dev/how-to-save-swiftui-views-as-images-in-macos) — 2023-05-03T00:00:00.000Z
  **NeKI brief:** Shows exporting SwiftUI views as images on macOS, using a QR-code editing workflow as the concrete case. Useful for implementing reliable snapshot export while separating rendering configuration from file-writing concerns.
- [GitHub Actions workflows side effects](https://www.polpiella.dev/github-action-workflows-side-effects) — 2023-04-26T00:00:00.000Z
  **NeKI brief:** Workflow-completion events can trigger dependent GitHub Actions jobs without coupling every concern to one pipeline. Use webhook filtering and idempotent handlers, guarding against loops, duplicate delivery and unintended write-side effects.
- [Scheduling app releases with Xcode Cloud](https://www.polpiella.dev/scheduling-app-releases-with-xcode-cloud) — 2023-04-19T00:00:00.000Z
  **NeKI brief:** Xcode Cloud scheduling coordinates release builds with App Store delivery windows. The guide is useful for separating build readiness from release approval, so automation does not bypass human checks for production distribution.
- [Deploying beta versions of your app to TestFlight and AppCenter using Xcode Cloud](https://www.polpiella.dev/how-to-deploy-beta-versions-of-your-app-to-testflight-and-appcenter-with-xcode-cloud) — 2023-04-12T00:00:00.000Z
  **NeKI brief:** This Xcode Cloud workflow distributes beta builds to TestFlight and App Center from one pipeline. Follow it to compare destination credentials, artifact handling and tester feedback loops without coupling them to source code.
- [Automating Swift command line tool releases with GitHub Actions](https://www.polpiella.dev/automating-swift-package-releases-with-github-actions) — 2023-04-05T00:00:00.000Z
  **NeKI brief:** Demonstrates automating Swift package releases with GitHub Actions, including tagging and publishing steps. Use it when making package distribution repeatable and keeping release credentials and versioning inside CI boundaries.
- [Collecting Xcode Cloud metrics using webhooks](https://www.polpiella.dev/xcode-cloud-webhooks) — 2023-03-29T00:00:00.000Z
  **NeKI brief:** Xcode Cloud webhooks can send build events to an external metrics collector. Use signed, idempotent ingestion with a durable event model, separating reporting failures from the CI workflow's actual build result.
- [Making macOS SwiftUI text views editable on click](https://www.polpiella.dev/swiftui-editable-list-text-items) — 2023-03-22T00:00:00.000Z
  **NeKI brief:** A macOS SwiftUI list item can transition from read-only text to a focused editor after an explicit interaction. Use separate display and editing states, preserving keyboard navigation, cancellation and selection behavior.
- [GitHub webhooks 🤝 Xcode Cloud](https://www.polpiella.dev/github-webhooks-and-xcode-cloud) — 2023-03-15T00:00:00.000Z
  **NeKI brief:** A GitHub webhook can initiate an Xcode Cloud build from a qualifying pull-request comment. Use authenticated event validation and narrowly defined trigger syntax, so comments cannot accidentally become a deployment control channel.
- [How to make an interactive picker for a Swift command-line tool](https://www.polpiella.dev/how-to-make-an-interactive-picker-for-a-swift-command-line-tool) — 2023-03-08T00:00:00.000Z
  **NeKI brief:** An interactive Swift CLI picker handles user input and terminal rendering without a GUI target. It is useful for developer tooling, where cancellation, invalid input and exit status form part of the command’s contract.
- [Managing multiple Xcode versions on CI using Fastlane](https://www.polpiella.dev/managing-xcode-installs-using-fastlane) — 2023-03-01T00:00:00.000Z
  **NeKI brief:** Fastlane can select the Xcode version used by CI before invoking build actions. Use an explicit version policy and image verification, keeping toolchain upgrades separate from ordinary application changes for reproducible builds.
- [Coming in Swift 5.9: Network requests in Swift package plugins](https://www.polpiella.dev/network-requests-in-swift-package-plugins) — 2023-02-22T00:00:00.000Z
  **NeKI brief:** Swift 5.9 package plugins can perform network requests under explicit build-tool constraints. Follow it to understand capability declarations and reproducibility risks before making a build depend on remote data.
- [Safely pinning SPM dependencies to exact versions](https://www.polpiella.dev/safely-pinning-spm-depedencies-to-exact-versions) — 2023-02-15T00:00:00.000Z
  **NeKI brief:** Exact Swift Package dependency pins make builds reproducible and reviewable. The article is useful for weighing update control against security freshness, especially when lockfile changes need deliberate dependency review.
- [Using App Store Connect API to trigger Xcode Cloud workflows](https://www.polpiella.dev/using-app-store-connect-api-to-trigger-xcode-cloud-workflows) — 2023-02-08T00:00:00.000Z
  **NeKI brief:** The App Store Connect API can start Xcode Cloud workflows programmatically. Use short-lived, least-privilege credentials and explicit workflow identifiers, treating API-triggered runs as auditable automation rather than hidden side effects.
- [Changing orientation for a single screen in SwiftUI](https://www.polpiella.dev/changing-orientation-for-a-single-screen-in-swiftui) — 2023-02-01T00:00:00.000Z
  **NeKI brief:** Presents a per-screen orientation approach for SwiftUI that bridges into UIKit, changing the supported interface orientations while a particular screen is active and restoring the app-wide policy afterward. Useful for flows such as media or camera interfaces.
- [Scheduling tweets with GitHub Actions and Swift](https://www.polpiella.dev/scheduling-tweets-with-github-actions-and-swift) — 2023-01-25T00:00:00.000Z
  **NeKI brief:** A Swift command scheduled by GitHub Actions automates social posting on a cron-like trigger. Follow it to see secret handling, time-zone assumptions and idempotency concerns in a small operational workflow.
- [Making a serverless Swift function with Fastly and Upstash](https://www.polpiella.dev/making-a-serverless-swift-function-with-fastly-and-upstash) — 2023-01-18T00:00:00.000Z
  **NeKI brief:** Builds a serverless Swift function backed by Fastly and Upstash services. Use it to evaluate edge execution, external state, and deployment boundaries when a small API does not need a long-lived server.
- [Fastlane and App Store Connect API keys](https://www.polpiella.dev/fastlane-appstore-connect-api-and-github-actions) — 2023-01-11T00:00:00.000Z
  **NeKI brief:** App Store Connect API keys let Fastlane and GitHub Actions authenticate without an interactive Apple ID session. Use encrypted, scoped credentials and rotation, ensuring CI logs never expose issuer, key ID or private key material.
- [Xcode Cloud scripts: Fastlane and Cocoapods](https://www.polpiella.dev/xcode-cloud-scripts-fastlane-and-cocoapods) — 2023-01-04T00:00:00.000Z
  **NeKI brief:** Xcode Cloud CI scripts can install tools such as Fastlane and CocoaPods before build phases. Use pinned versions and deterministic setup, keeping scripts resilient to hosted-image changes and safe to rerun.
- [Managing multiple versions of Swift locally](https://www.polpiella.dev/managing-multiple-swift-versions-locally) — 2022-12-21T00:00:00.000Z
  **NeKI brief:** Explains installing and switching among multiple Swift toolchains and development snapshots on one machine. Use it when reproducing compiler-version behavior, testing migration paths, or isolating package failures from the active Xcode toolchain.
- [Configuring UI tests with launch arguments](https://www.polpiella.dev/configuring-ui-tests-with-launch-arguments) — 2022-12-14T00:00:00.000Z
  **NeKI brief:** Launch arguments let UI tests set deterministic app configuration before the process starts. Use them to disable network-dependent behavior or seed states, keeping production-only code paths protected from test configuration leaks.
- [Swift async/await in AWS lambdas](https://www.polpiella.dev/swift-async-await-in-aws-lambdas) — 2022-12-07T00:00:00.000Z
  **NeKI brief:** Swift's async Lambda runtime allows handlers to await network and storage work naturally. Use cancellation-aware async boundaries and propagate failures to the platform, avoiding blocking bridges that defeat concurrency benefits.
- [Collecting GitHub Action workflow metrics using Swift](https://www.polpiella.dev/collecting-gihub-actions-workflow-metrics-with-swift) — 2022-11-30T00:00:00.000Z
  **NeKI brief:** A Swift command-line tool can collect GitHub Actions metrics through asynchronous API requests. Use pagination, rate-limit handling and stable aggregation, keeping the reporting tool independent of any individual workflow's success.
- [Testing your release pipeline using Fastlane](https://www.polpiella.dev/testing-your-release-pipeline-using-fastlane) — 2022-11-19T00:00:00.000Z
  **NeKI brief:** Fastlane is used to test release automation before production distribution. Follow it to exercise signing, metadata and artifact steps in a controlled lane, where pipeline failures become repeatable test cases.
- [A menu bar only macOS app using AppKit](https://www.polpiella.dev/a-menu-bar-only-macos-app-using-appkit) — 2022-10-26T00:00:00.000Z
  **NeKI brief:** A menu-bar-only macOS app manages an NSStatusItem without a conventional main window. Use explicit lifecycle and activation choices, ensuring settings, quit behavior and accessibility remain discoverable to users.
- [Platform specific code in Swift Packages](https://www.polpiella.dev/platform-specific-code-in-swift-packages) — 2022-10-06T00:00:00.000Z
  **NeKI brief:** Organizes platform-specific code in Swift packages. Use it when one package supports Apple platforms or Linux without leaking unavailable APIs into shared targets.
- [Handling multiple git SSH keys](https://www.polpiella.dev/handling-multiple-git-ssh-keys) — 2022-09-27T00:00:00.000Z
  **NeKI brief:** Multiple Git SSH keys are selected through host aliases and explicit configuration. The guide is useful for separating personal and work identities, while keeping private key material outside repositories and build logs.
- [Sourcery Swift Package command plugin](https://www.polpiella.dev/sourcery-swift-package-command-plugin) — 2022-08-31T00:00:00.000Z
  **NeKI brief:** Integrates Sourcery generation as a Swift Package command plugin. Use it when repeatable code generation should run through SwiftPM rather than custom shell instructions.
- [My new Swift Package: ReadingTime](https://www.polpiella.dev/my-new-swift-package-reading-time) — 2022-08-17T00:00:00.000Z
  **NeKI brief:** This package case study derives reading-time metadata from text and publishes it as a reusable Swift dependency. It is useful for seeing how a small focused API, tests and package metadata form a distributable unit.
- [From NSRegularExpression to SwiftRegex](https://www.polpiella.dev/from-nsregular-expression-to-swift-regex) — 2022-08-11T00:00:00.000Z
  **NeKI brief:** Migrating from NSRegularExpression to SwiftRegex replaces stringly typed matches with Swift-native pattern composition. Follow it to evaluate readability and compile-time checking while preserving behavior for existing capture and replacement logic.
- [Advances in Swift Package Manager's dependency access control](https://www.polpiella.dev/advances-in-swift-package-access-control) — 2022-08-03T00:00:00.000Z
  **NeKI brief:** Swift Package Manager access-control changes refine which declarations cross target boundaries. The article is useful for modular API design, where package visibility should expose capabilities without leaking implementation types.
- [Localising a modularised application](https://www.polpiella.dev/modularised-app-localisation) — 2022-07-27T00:00:00.000Z
  **NeKI brief:** Localization in a modular app needs each module's resources and lookup boundaries to be explicit. Use shared terminology where appropriate and test every target's bundle resolution, avoiding silent fallback to untranslated strings.
- [Code generation using Swift Package Plugins](https://www.polpiella.dev/code-generation-using-swift-package-plugins) — 2022-07-05T00:00:00.000Z
  **NeKI brief:** A Swift package plugin can inspect package inputs and generate source before compilation. Use deterministic output and declared inputs, keeping generated APIs reviewable and avoiding plugins that hide essential build-time dependencies.
- [Scripting in Swift: Git Hooks](https://www.polpiella.dev/scripting-in-swift-git-hooks) — 2022-05-14T00:00:00.000Z
  **NeKI brief:** Swift scripts can run as Git hooks to enforce repository checks before commits or pushes. Follow it to build typed tooling, while keeping hook installation explicit so contributors are not surprised by local automation.
- [Binary targets in modern Swift packages](https://www.polpiella.dev/binary-targets-in-modern-swift-packages) — 2022-05-07T00:00:00.000Z
  **NeKI brief:** Binary targets distribute prebuilt artifacts through Swift Package Manager instead of compiling their source. Use checksums, clear platform slices and versioned artifacts, evaluating debugging and transitive dependency trade-offs before adoption.
- [Building layouts with accessibility in mind - Part 2](https://www.polpiella.dev/building-layouts-with-accessibility-in-mind-part-2) — 2022-03-31T00:00:00.000Z
  **NeKI brief:** Continues an accessible UIKit layout by addressing content-size changes and remaining sizing issues after the initial stack-based design. Follow it when self-sizing alone still leaves controls clipped or visually reordered.
- [Building layouts with accessibility in mind - Part 1](https://www.polpiella.dev/building-layouts-with-accessibility-in-mind-part-1) — 2022-03-15T00:00:00.000Z
  **NeKI brief:** Builds a UIKit layout with self-sizing stack views so labels and buttons respond to user content-size preferences. It is useful as a baseline for replacing fixed frames with constraints that survive Dynamic Type growth.
- [Embedding a dylib in a Swift Package](https://www.polpiella.dev/embedding-a-dylib-in-a-swift-package) — 2022-02-12T00:00:00.000Z
  **NeKI brief:** Embeds a dynamic library in a Swift package. Use it when distributing binary dependencies and needing explicit packaging, runtime loading, and platform compatibility handling.
- [An early look at Swift extensible build tools](https://www.polpiella.dev/an-early-look-at-swift-extensible-build-tools) — 2022-01-22T00:00:00.000Z
  **NeKI brief:** Examines Swift extensible build tools. Use it when package builds need custom generation or validation steps that integrate with SwiftPM rather than opaque external scripts.
- [Asserting errors from throwing functions](https://www.polpiella.dev/asserting-errors-from-throwing-functions) — 2022-01-16T00:00:00.000Z
  **NeKI brief:** This testing technique verifies that a throwing Swift function fails with the expected error. It is useful for precise negative-path tests, avoiding broad catches that pass while the wrong failure reaches the assertion.
- [Cancelling unnecessary GitHub actions automatically](https://www.polpiella.dev/cancelling-unnecessary-github-actions-automatically) — 2021-11-26T00:00:00.000Z
  **NeKI brief:** A GitHub Actions workflow cancels superseded runs when newer commits make them obsolete. Follow it to reduce queue time and cost, while ensuring release or deployment jobs are not cancelled mid-critical operation.
- [Custom key decoding strategies in Swift](https://www.polpiella.dev/custom-key-decoding-strategies-in-swift) — 2021-11-03T00:00:00.000Z
  **NeKI brief:** Custom Codable key strategies normalize irregular JSON naming while keeping Swift properties idiomatic. Follow it when APIs mix conventions, but scope the strategy narrowly so unrelated payloads do not decode unexpectedly.
- [Using Property Wrappers to avoid code repetition](https://www.polpiella.dev/avoiding-code-repetition-with-property-wrappers) — 2021-08-25T00:00:00.000Z
  **NeKI brief:** Property wrappers can centralize repeated storage or transformation behavior behind a property declaration. Use them for a coherent cross-cutting rule, avoiding wrappers that conceal dependencies or make state updates harder to trace.
- [Hiding implementation details using the adapter pattern in Swift](https://www.polpiella.dev/hide-implementation-details-using-the-adapter-pattern) — 2021-08-01T00:00:00.000Z
  **NeKI brief:** An adapter presents an app-owned interface over an external implementation. Follow it to reduce coupling and make tests easier, while resisting adapters that only rename every method without adding a boundary.
- [How I use GitHub Actions to update my GitHub profile](https://www.polpiella.dev/updating-your-profile-readme-with-github-actions) — 2021-07-15T00:00:00.000Z
  **NeKI brief:** GitHub Actions updates generated profile content through a scheduled workflow. The article is useful for automation design, where idempotent writes, token scope and generated-versus-handwritten sections must be explicit.
- [Testing dates consistently](https://www.polpiella.dev/testing-dates-consistently) — 2021-07-02T00:00:00.000Z
  **NeKI brief:** Date tests become deterministic by controlling clocks, calendars and time zones instead of comparing wall-clock values. The article is useful for eliminating locale-dependent failures from serialization and scheduling tests.
- [Clean Architecture: A Feature Flag Manager](https://www.polpiella.dev/clean-architecture-a-feature-flag-provider) — 2021-05-14T00:00:00.000Z
  **NeKI brief:** A feature-flag provider hides remote or local flag retrieval behind an application-owned interface. Use it to keep business behavior testable and rollout policy replaceable, defining defaults for unavailable or malformed flag data.
- [Using .switchToLatest()](https://www.polpiella.dev/the-power-of-the-switchtolatest-operator) — 2021-04-28T00:00:00.000Z
  **NeKI brief:** Combine switchToLatest cancels older inner publishers when a newer one arrives. Follow it for search or request pipelines where only the latest intent should win and stale responses must not update state.
