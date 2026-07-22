# App Distribution & Store Operations

Third-party reading leads collected from NeKI sources. The links may be useful perspectives, but are not vetted recommendations or authoritative API guidance. NeKI publishes routing metadata, not the linked articles' text.

**Scope:** App Store delivery, TestFlight, StoreKit commerce, signing, review, releases, and monetisation workflows.

- Last collected: `2026-07-22T21:56:49Z`
- Indexed links shown: **127**

## Direct-source reading

- [Introductory Pricing for iOS: Getting Started | Kodeco](https://www.kodeco.com/9307-introductory-pricing-for-ios-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The StoreKit tutorial adds an introductory offer to an existing auto-renewable subscription, walking through product configuration and purchase-flow decisions that must agree between App Store Connect and code.
- [Requesting App Ratings and Reviews Tutorial for iOS | Kodeco](https://www.kodeco.com/9009-requesting-app-ratings-and-reviews-tutorial-for-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** This walkthrough places SKStoreReviewController in an app-rating flow and discusses the surrounding API choices for requesting reviews from users.
- [Push Notifications Tutorial for iOS: Rich Push Notifications | Kodeco](https://www.kodeco.com/8277640-push-notifications-tutorial-for-ios-rich-push-notifications) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Builds rich notifications around a service extension: authenticate the provider, alter payload content, download attachments, and share files safely with the extension. Useful when a plain alert must become a media-bearing or server-customized notification.
- [Reproducing Popular iOS Controls Part 3: App Store & Maps | Kodeco](https://www.kodeco.com/6389-reproducing-popular-ios-controls-part-3-app-store-maps) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Recreates App Store and Maps-inspired controls as a focused implementation exercise. Useful for studying how a recognizable interaction can be decomposed into view structure, gestures, and animation decisions rather than copied as a monolithic visual effect.
- [iOS 10: Capturing Photo Thumbnails | Kodeco](https://www.kodeco.com/4999-ios-10-capturing-photo-thumbnails) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Captures and prepares photo thumbnails for a camera-driven interface. Useful for separating a fast preview-sized representation from full-resolution capture work that would otherwise block interaction or consume unnecessary memory.
- [iOS 10: Introducing UIPreviewInteraction | Kodeco](https://www.kodeco.com/4992-ios-10-introducing-uipreviewinteraction) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Explains UIKit preview interactions for revealing content with pressure-sensitive input. Useful as historical context for the interaction lifecycle and preview presentation concepts later expressed through newer contextual interaction APIs.
- [iOS 10: Manipulating Push Notifications with Service Extensions | Kodeco](https://www.kodeco.com/4976-ios-10-manipulating-push-notifications-with-service-extensions) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Uses a notification service extension to alter a remote notification before delivery. Useful for designing time-bounded enrichment such as attachment download while preserving a fallback alert if extension processing fails.
- [Beginning Storyboards in iOS 5 Part 2 | Kodeco](https://www.kodeco.com/3003-beginning-storyboards-in-ios-5-part-2) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Storyboard navigation and scene wiring are extended in this legacy UIKit tutorial. It is useful for maintaining older projects by making serialized segues and outlet ownership explicit before replacing them with programmatic navigation.
- [Beginning Turn-Based Gaming with iOS 5 Part 2 | Kodeco](https://www.kodeco.com/2998-beginning-turn-based-gaming-with-ios-5-part-2) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The turn-based gaming continuation models turn submission and match progression through Game Center. It helps expose asynchronous game-state transitions that should remain separate from the local board’s rendering and input rules.
- [Beginning iCloud in iOS 5 Tutorial Part 2 | Kodeco](https://www.kodeco.com/2995-beginning-icloud-in-ios-5-tutorial-part-2) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** The iCloud continuation handles synchronizing app values and reacting to remote changes. It is legacy material, useful for migration analysis where notification ordering and conflict assumptions need to be replaced with modern CloudKit semantics.
- [Beginning Twitter in iOS 5 Tutorial | Kodeco](https://www.kodeco.com/2994-beginning-twitter-in-ios-5-tutorial) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** A Twitter integration demonstrates OAuth-era login and timeline requests from an iOS app. Follow it only for legacy maintenance; the important boundary remains keeping tokens and server credentials out of client-owned UI code.
- [In-App Purchases in iOS 6 Tutorial: Consumables and Receipt Validation | Kodeco](https://www.kodeco.com/2812-in-app-purchases-in-ios-6-tutorial-consumables-and-receipt-validation) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Implements a consumable purchase flow and compares receipt validation with a no-server approach. Useful historical context for distinguishing StoreKit transaction handling from the separate trust decision of where and how purchase verification occurs.
- [Local Receipt Validation in iOS | Kodeco](https://www.kodeco.com/23523765-local-receipt-validation-in-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Validates StoreKit receipts locally and examines the information a receipt encodes. Useful for understanding the cryptographic and product-state boundary before choosing between device-side checks and a backend verification service.
- [Custom Thumbnails and Previews with Quick Look on iOS | Kodeco](https://www.kodeco.com/19636179-custom-thumbnails-and-previews-with-quick-look-on-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Quick Look extensions provide custom previews and thumbnails for app-owned file types. Follow it to understand the extension process boundary and identifier registration, where rendering capability is constrained independently of the main app UI.
- [Firebase Remote Config Tutorial for iOS | Kodeco](https://www.kodeco.com/17323848-firebase-remote-config-tutorial-for-ios) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Firebase Remote Config changes app behavior without an App Store submission by fetching server-managed values. The trade-off is operational control versus determinism: cache defaults and version configurations so offline or stale fetches remain safe.
- [Sending Push Notifications With Vapor | Kodeco](https://www.kodeco.com/11238593-sending-push-notifications-with-vapor) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Shows a Vapor server sending APNs push notifications to registered devices. It is useful for tracing device-token storage, payload construction, and delivery failures, while keeping notification triggering separate from the iOS app’s presentation policy.
- [QuickLook Previews for iOS: Getting Started | Kodeco](https://www.kodeco.com/10447506-quicklook-previews-for-ios-getting-started) — Kodeco / Ray Wenderlich archive · article catalogue
  **Published:** `2026-07-17`
  **NeKI brief:** Uses QLPreviewController and QLPreviewItem to preview files, provide thumbnails, customize zoom transitions, and enable PDF editing. Useful for adopting a system document viewer when building and maintaining a bespoke preview screen would add little product value.
- [How to design an SDK to handle $10bn in transactions](https://blog.jacobstechtavern.com/p/revenuecat-sdk) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2026-01-12T16:01:24.245Z`
  **NeKI brief:** Explains SDK design under high transaction volume through resilient networking, idempotency, caching, observability, and compatibility boundaries, showing how a client library protects product flows while backend systems absorb scale and failure.
- [How to change your app's business model from paid to freemium using StoreKit](https://www.polpiella.dev/paid-app-to-freemium) — Pol Piella · article catalogue
  **Published:** `2024-12-06T00:00:00.000Z`
  **NeKI brief:** Shows changing an app's business model from paid upfront to freemium using StoreKit's AppTransaction API. Follow it when planning migration logic and entitlement checks, then verify transaction semantics, customer communication, and App Store policy requirements.
- [How to create and upload high-quality App Store assets with RocketSim and Helm](https://www.polpiella.dev/creating-and-uploading-app-store-assets) — Pol Piella · article catalogue
  **Published:** `2024-11-20T00:00:00.000Z`
  **NeKI brief:** Demonstrates creating App Store screenshots and previews with RocketSim and uploading assets through Helm. Useful for making release marketing repeatable, while reviewing device coverage, localization, metadata accuracy, and App Store Connect validation before submission.
- [How to expedite an app review on the App Store](https://www.polpiella.dev/expedited-app-reviews) — Pol Piella · article catalogue
  **Published:** `2024-10-23T00:00:00.000Z`
  **NeKI brief:** Explains Apple's expedited App Review process and the circumstances in which a developer can request faster review. Use it as operational guidance for urgent fixes, while documenting impact clearly and treating approval as discretionary rather than guaranteed.
- [How to (consistently) get 4.8* App Ratings](https://blog.jacobstechtavern.com/p/how-to-consistently-get-48-app-ratings-3be) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2024-05-06T16:15:23.738Z`
  **NeKI brief:** Shows how to time StoreKit review requests around a user's proven wow moment, with SwiftUI and UIKit examples, rather than prompting indiscriminately. Use it to connect a review prompt to completed value while preserving a low-friction experience and measuring ratings as a product outcome.
- [Building a backend-driven paywall with RevenueCat – Donny Wals](https://www.donnywals.com/building-a-backend-driven-paywall-with-revenuecat) — Donny Wals · article catalogue
  **Published:** `2024-04-04T17:30:56+00:00`
  **NeKI brief:** A backend-driven paywall separates entitlement presentation from a fixed client release, but remote configuration needs validation, fallback behavior, and clear experiment ownership.
- [Fastlane and App Store Connect API keys](https://www.polpiella.dev/fastlane-appstore-connect-api-and-github-actions) — Pol Piella · article catalogue
  **Published:** `2023-01-11T00:00:00.000Z`
  **NeKI brief:** App Store Connect API keys let Fastlane and GitHub Actions authenticate without an interactive Apple ID session. Use encrypted, scoped credentials and rotation, ensuring CI logs never expose issuer, key ID or private key material.
- [Optimizing Your Application’s Reviews – Donny Wals](https://www.donnywals.com/optimizing-your-applications-reviews) — Donny Wals · article catalogue
  **Published:** `2019-10-14T07:00:03+00:00`
  **NeKI brief:** Review prompts should follow meaningful user success and system rate limits, balancing feedback requests with an experience that does not interrupt routine work.
- [Checking Code Signing and Sandboxing Status in Code – Ole Begemann](https://oleb.net/blog/2012/02/checking-code-signing-and-sandboxing-status-in-code) — Ole Begemann · article catalogue
  **Published:** `2012-02-22T17:55:00Z`
  **NeKI brief:** Inspects signing and sandbox state at runtime for diagnostic builds, helping distinguish entitlement configuration failures from ordinary application logic errors.
- [The App Launch Sequence on iOS – Ole Begemann](https://oleb.net/blog/2011/06/app-launch-sequence-ios) — Ole Begemann · article catalogue
  **Published:** `2011-06-27T21:10:00Z`
  **NeKI brief:** Traces iOS application launch callbacks and nib loading order so startup work is placed after required dependencies exist and before UI assumptions cause lifecycle bugs.
- [How to implemet a free trial period for StoreKit 2 subscriptions in iOS](https://tanaschita.com/20231113-subscriptions-introductory-offers) — Tanaschita · article catalogue
  **NeKI brief:** StoreKit 2 introductory offers apply eligibility and offer configuration to subscription purchases. The guide is useful for separating App Store product metadata from local UI, while treating eligibility as server-verified state.
- [Get started with StoreKit 2 for iOS](https://tanaschita.com/20231002-storekit-2-overview) — Tanaschita · article catalogue
  **NeKI brief:** StoreKit 2 product loading and purchases are introduced through async APIs and verified transactions. Follow it to separate entitlement state from paywall UI and to keep verification on the trusted path.
- [Authorizing App Store Connect API requests](https://tanaschita.com/20221226-authorizing-app-store-connect-api-requests) — Tanaschita · article catalogue
  **NeKI brief:** App Store Connect API authorization combines an API key with a signed JWT. Follow it to understand issuer, audience and expiration claims, while keeping the private key in a protected automation environment.
- [Secrets to a Successful App Launch: Marketing, Monetization, and Beyond](https://martiancraft.com/blog/2025/12/secrets-to-a-successful-app-launch) — MartianCraft · article catalogue
  **NeKI brief:** Launch preparation is framed as coordinated QA, analytics, and operational readiness, emphasizing cross-functional sequencing over a final-day checklist.
- [Big Agencies vs. Boutique Firms: What You’re Really Paying For in App Development](https://martiancraft.com/blog/2025/08/big-agencies-vs-boutiquefirms) — MartianCraft · article catalogue
  **NeKI brief:** Agency-size trade-offs are compared through specialization, communication, and delivery overhead, helping teams choose vendors against project constraints rather than reputation alone.
- [The Art of App Store Optimization](https://martiancraft.com/blog/2024/07/the-art-of-app-store-optimization) — MartianCraft · article catalogue
  **NeKI brief:** App Store optimization combines search metadata, screenshots, positioning, and measured conversion rather than a single keyword trick. The article is useful for connecting product experiments to store analytics and release cadence.
- [Using Link Presentation in iOS development to make visually-rich links](https://martiancraft.com/blog/2021/02/using-link-presentation) — MartianCraft · article catalogue
  **NeKI brief:** LinkPresentation fetches metadata through redirects and supplies rich previews for URLs, replacing hand-built title and image scraping. The article is a useful integration reference for asynchronous metadata loading and fallback UI.
- [The top reasons apps get rejected on the App Store](https://martiancraft.com/blog/2017/12/app-rejection) — MartianCraft · article catalogue
  **NeKI brief:** App Store rejection causes are mapped to review policy and implementation details, from privacy declarations to unsupported behavior. Follow it as a pre-submission diagnostic checklist, while verifying current rules separately.
- [Staying Competitive with App Updates](https://martiancraft.com/blog/2017/04/app-updates) — MartianCraft · article catalogue
  **NeKI brief:** Keep mobile apps current through regular, scoped releases that combine platform compatibility work, defect fixes, and dependency maintenance. Frequent updates constrain technical debt and make urgent fixes smaller, safer, and easier to validate than long-delayed catch-up projects.
- [Modern Login Items](https://martiancraft.com/blog/2015/01/login-items) — MartianCraft · article catalogue
  **NeKI brief:** A Mac login helper must follow App Store rules, honor a user preference, and be packaged with the main app correctly. Treat launch-at-login as an opt-in lifecycle feature, including its helper-installation and update behavior in the design.

## Newsletter and related leads

- [getting nowhere with Apple](https://lapcatsoftware.com/articles/2026/7/6.html) — Fatbobman’s Swift Weekly · Issue 145 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `2026-07-20T12:01:22.890Z`
  **NeKI brief:** Diagnoses an App Store Connect login loop by comparing request cookies and finding a missing `dc` session cookie. Follow it for a focused example of browser-level debugging when server behavior contradicts apparent authentication state.
- [An Indie Playbook for the WWDC26 App Store Changes](https://3nsofts.com/guides/app-store/app-store-wwdc26-monetization-indie-playbook) — iOS Dev Weekly · Issue 759 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem
  **Published:** `17th July 2026`
  **NeKI brief:** Examines WWDC26 App Store changes through an indie developer lens, connecting policy updates to pricing, subscriptions, and release planning. Useful for product decisions, but verify current Apple commerce rules before implementation.
- [iOS 27 SDK: 3 Major Requirements That Might Break Your App](https://blog.makwanbk.com/ios-27-sdk-3-major-requirements-that-migh-break-your-app?ref=createwithswift.com) — Create with Swift · Issue 114 — Article · Topics: App Distribution & Store Operations · Liquid Glass · Swift
  **Published:** `2026-07-04T15:00:32.000Z`
  **NeKI brief:** Summarizes three iOS 27 SDK requirements that may surface during an upgrade. Use it as a migration checklist for build and runtime audits, then verify each requirement against Apple's release documentation.
- [Apple App Store Scraper](https://apify.com/maximedupre/apple-app-store-scraper) — iOS Dev Tools · iOS Dev Tools: Apple App Store Scraper, SideScreen, SiteKit — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `2026-07-02T19:03:32.109Z`
  **NeKI brief:** Apify's Apple App Store Scraper extracts app metadata, ratings, reviews, rankings, and related store information into structured datasets. Use it for repeatable App Store research, while respecting platform terms and rate limits.
- [OpenUsage](https://github.com/robinebers/openusage) — iOS Dev Tools · iOS Dev Tools: Apple App Store Scraper, SideScreen, SiteKit — Source repository · Topics: AI Development · App Distribution & Store Operations · Developer Tools
  **Published:** `2026-07-02T19:03:32.109Z`
  **NeKI brief:** OpenUsage presents subscription and usage information in an open-source desktop utility, helping users see where recurring services are being consumed. Useful as a reference for local usage aggregation and transparent cost awareness.
- [W.W.D.C. 2026: The Pregame Quiz](https://www.swiftjectivec.com/wwdc-2026-the-pregame-quiz) — Those Who Swift · Issue 268 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `2026-05-27`
  **NeKI brief:** Presents W.W.D.C. 2026: The Pregame Quiz, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Northstar](https://www.gonorthstar.io/) — iOS Dev Tools · iOS Dev Tools: SwiftSafeUI, Northstar, Ezscreenshots — Article · Topics: App Distribution & Store Operations
  **Published:** `2026-05-14T16:15:24.123Z`
  **NeKI brief:** Northstar combines App Store keyword opportunity scores, competitor metadata and review tracking, App Store Connect synchronization, and an MCP server for LLM-assisted optimization. It is useful when researching an auditable alternative to ad-hoc ASO spreadsheets.
- [Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — iOS Dev Tools · iOS Dev Tools: AscBuddy, TourKit, Hokusai — Source repository · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **Published:** `2026-05-07T16:16:37.368Z`
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [CLI](https://www.rocketsim.app/docs/features/agentic-development/rocketsim-cli) — SwiftLee Weekly · Issue 322 — Article · Topics: AI Development · Testing
  **Published:** `2026-05-05T14:09:40.000Z`
  **NeKI brief:** Explains CLI, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [ASC CLI](https://github.com/rudrankriyam/App-Store-Connect-CLI) — Fatbobman’s Swift Weekly · Issue 127 — Source repository · Topics: AI Development · App Distribution & Store Operations · Developer Tools
  **Published:** `2026-03-16T12:04:00.245Z`
  **NeKI brief:** App-Store-Connect-CLI automates App Store Connect tasks from the command line, including subscription-related setup. Use it to replace repetitive portal configuration with reviewable scripts, while treating credentials and destructive commands carefully.
- [AcceptedSE-0509Software Bill of Materials (SBOM) Generation for Swift Package Manager](https://github.com/apple/swift-evolution/blob/main/proposals/0509-swift-sboms-via-swiftpm.md) — SwiftLee Weekly · Issue 313 — Source repository · Topics: App Distribution & Store Operations · Swift · Swift Package Manager
  **Published:** `2026-03-03T15:11:29.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0509Software Bill of Materials (SBOM) Generation for Swift Package Manager. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0515Allow `reduce` to produce noncopyable results](https://github.com/apple/swift-evolution/blob/main/proposals/0515-noncopyable-reduce.md) — SwiftLee Weekly · Issue 313 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Swift
  **Published:** `2026-03-03T15:11:29.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0515Allow `reduce` to produce noncopyable results. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0516Borrowing Sequence](https://github.com/apple/swift-evolution/blob/main/proposals/0516-borrowing-sequence.md) — SwiftLee Weekly · Issue 313 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Swift
  **Published:** `2026-03-03T15:11:29.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0516`Iterable`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [WWDC Index](https://nonstrict.eu/wwdcindex) — iOS Dev Weekly · Issue 739 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Testing
  **Published:** `16th January 2026`
  **NeKI brief:** This technical resource covers a searchable index of WWDC material. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [my YouTube series on this app](https://youtube.com/playlist?list=PLg4qABgFp_nRYMtGFdXz8sUeXb2IDxdPL&si=Imqah2BEAj-b-WAM) — SwiftLee Weekly · Issue 306 — Video · Topics: App Distribution & Store Operations · Graphics, Media & Games · Testing
  **Published:** `2026-01-13T15:06:45.000Z`
  **NeKI brief:** Provides a SwiftUI learning course playlist covering navigation and related interface patterns. Use it as a structured route through implementations, checking each example against current APIs before adopting its presentation or state-management techniques.
- [demo projects](https://github.com/zhangqifan/Insights) — Fatbobman’s Swift Weekly · Issue 111 — Source repository · Topics: App Distribution & Store Operations · Architecture · Liquid Glass
  **Published:** `2025-11-17T12:02:46.781Z`
  **NeKI brief:** Insights contains demo projects for applying Liquid Glass design to a production health app. Use it to inspect concrete adaptations of translucent materials, hierarchy, and interaction rather than treating WWDC design guidance as abstract theory.
- [Ship better paywalls faster with RevenueCat’s native, customizable Paywall Builder](https://www.revenuecat.com/docs/tools/paywalls-v2) — iOS Dev Weekly · Issue 726 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `12th September 2025`
  **NeKI brief:** Documents RevenueCat Paywalls 2 tooling for configuring and presenting subscription paywalls. Use it to inspect templates, purchase flows, and customization boundaries before integrating monetization into an app.
- [Mercato](https://github.com/tikhop/Mercato) — iOS Dev Tools · iOS Dev Tools: ch.at, Mercato, Dependencies — Source repository · Topics: App Distribution & Store Operations · Developer Career & Practice · Developer Tools
  **Published:** `2025-08-14T19:53:26.103Z`
  **NeKI brief:** Mercato wraps StoreKit 2 for subscriptions and in-app purchases across Apple platforms, aiming to reduce repetitive transaction plumbing. Useful for comparing a focused purchase abstraction with direct StoreKit state and entitlement management.
- [read all about it inside the documentation](https://docs.rocketsim.app/features/hzQMSrSga7BGWvxdNVdwYs/simulator-camera-support/58tQ5jvevLNSnyUEA7VgAv) — SwiftLee Weekly · Issue 277 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `2025-06-24T14:09:23.000Z`
  **NeKI brief:** Presents RocketSim's documentation, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [App Review-safe Swift implementation](https://github.com/sebjvidal/_UIContextMenuAccessoryView-Demo) — Fatbobman’s Swift Weekly · Issue 84 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Swift
  **Published:** `2025-05-19T12:00:44.196Z`
  **NeKI brief:** Demonstrates an App Review-safe Swift approach to context-menu accessory UI inspired by Messages. Use it to understand the public-API boundary and avoid shipping private UIKit techniques that merely reproduce system visuals.
- [easy-frame](https://github.com/alschmut/EasyFrameCommand) — iOS Dev Tools · iOS Dev Tools: easy-frame, Sweetpad, StoreKitHelper — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Swift
  **Published:** `2025-04-11T07:56:27.598Z`
  **NeKI brief:** EasyFrameCommand is a Swift CLI that creates framed App Store screenshots from custom SwiftUI layouts. Useful for repeatable marketing-image generation that keeps device framing in source-controlled code instead of manual editing.
- [StoreKitHelper](https://github.com/jaywcjlove/StoreKitHelper) — iOS Dev Tools · iOS Dev Tools: easy-frame, Sweetpad, StoreKitHelper — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Swift
  **Published:** `2025-04-11T07:56:27.598Z`
  **NeKI brief:** StoreKitHelper wraps StoreKit 2 for SwiftUI in a lightweight package, reducing repeated purchase and entitlement plumbing. Useful for comparing a small declarative helper with direct StoreKit transaction observation and product loading.
- [ReviewKit](https://github.com/FlineDev/ReviewKit) — iOS Dev Tools · iOS Dev Tools: Dock, Clippets, ReviewKit — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **Published:** `2025-03-20T17:08:58.928Z`
  **NeKI brief:** ReviewKit records positive user events and requests an App Store review only when configurable satisfaction criteria are met; events expire after a default window. It is a concrete pattern for making review prompts contextual instead of firing on arbitrary launches.
- [iOS-uploader](https://github.com/simonnilsson/ios-uploader) — iOS Dev Tools · iOS Dev Tools: Swift Bundler, Swift for Visual Studio Code, iOS-uploader — Source repository · Topics: App Distribution & Store Operations · Cross-Platform & Web · Developer Tools
  **Published:** `2025-01-16T21:51:40.196Z`
  **NeKI brief:** A cross-platform command-line uploader for App Store Connect that accepts familiar altool-style arguments and can upload multiple apps concurrently. Its prebuilt binaries and npm installation make it relevant when CI must publish from Windows, Linux, or macOS.
- [iPhone Apps 101 - SwiftUI App Development Course](https://paulsolt.teachable.com/p/iphoneapps101?affcode=1123_hyqyixcy) — SwiftLee Weekly · Issue 254 — Tutorial · Topics: Developer Community & Business · Swift · SwiftUI
  **Published:** `2025-01-14T14:03:25.000Z`
  **NeKI brief:** Introduces iPhone Apps 101 - SwiftUI App Development Course as a developer resource or service relevant to Swift and Apple-platform work. Use it to assess the stated workflow or offering, checking scope, pricing, access requirements, and technical fit before relying on it.
- [Add paywalls in one line of code](https://www.revenuecat.com/docs/tools/paywalls) — iOS Dev Weekly · Issue 693 — Article · Topics: App Distribution & Store Operations · Testing
  **Published:** `3rd January 2025`
  **NeKI brief:** Explains how RevenueCat’s paywall tools let an app configure and present subscription purchase UI with minimal code. Use it to evaluate hosted paywall workflows, entitlement integration, localization, and experimentation requirements before adopting the service.
- [How to change your app's business model from paid to freemium using StoreKit](https://www.polpiella.dev/paid-app-to-freemium?ref=createwithswift.com) — Create with Swift · Issue 40 — Article · Topics: App Distribution & Store Operations · Swift
  **Published:** `2024-12-13T16:30:39.000Z`
  **NeKI brief:** Shows changing an app's business model from paid upfront to freemium using StoreKit's AppTransaction API. Follow it when planning migration logic and entitlement checks, then verify transaction semantics, customer communication, and App Store policy requirements.
- [AcceptedSE-0451Raw identifiers](https://github.com/apple/swift-evolution/blob/main/proposals/0451-escaped-identifiers.md) — SwiftLee Weekly · Issue 249 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2024-12-10T13:47:59.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0451Raw identifiers. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [App development on iPad](https://mutatingfunc.github.io/blog/2024-10-12-app-development-on-ipad) — iOS Dev Weekly · Issue 684 — Article · Topics: Developer Tools · Testing
  **Published:** `25th October 2024`
  **NeKI brief:** Presents app development on ipad for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [the tragic story](https://www.youtube.com/watch?v=_ueiYhLwwBc) — iOS Dev Weekly · Issue 676 — Video · Topics: AI Development · App Distribution & Store Operations
  **Published:** `30th August 2024`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Helm](https://helm-app.com/) — iOS Dev Tools · iOS Dev Tools: Helm, AudioKit, Lottie — Article · Topics: App Distribution & Store Operations
  **Published:** `2024-06-20T13:30:58.118Z`
  **NeKI brief:** Discusses Helm in a public developer resource. Use it to compare the author's concrete workflow and trade-offs with your project constraints, and verify any platform-specific claims against current primary documentation.
- [老司机技术](https://github.com/SwiftOldDriver/iOS-Weekly) — Fatbobman’s Swift Weekly · Issue 35 — Source repository · Topics: App Distribution & Store Operations · Apple Platform Ecosystem · Developer Tools
  **Published:** `2024-06-11T12:03:15.731Z`
  **NeKI brief:** Indexes Chinese iOS development reading and project links in a repository-friendly format. Use it as a discovery route for community material, then verify each linked source independently before relying on it.
- [Get started with StoreKit 2 for iOS](https://tanaschita.com/20231002-storekit-2-overview?ref=createwithswift.com) — Create with Swift · Issue 9 — Article · Topics: App Distribution & Store Operations · Swift
  **Published:** `2024-04-19T15:00:58.000Z`
  **NeKI brief:** StoreKit 2 product loading and purchases are introduced through async APIs and verified transactions. Follow it to separate entitlement state from paywall UI and to keep verification on the trusted path.
- [RevenueCat](https://www.revenuecat.com/) — iOS Dev Tools · iOS Dev tools: Play, PullRequest, Sonar — Article · Topics: App Distribution & Store Operations
  **Published:** `2024-03-14T16:08:26.033Z`
  **NeKI brief:** RevenueCat presents a subscription platform for mobile apps, covering purchase infrastructure, entitlement management, and revenue analytics. Use it as a product and integration overview when evaluating recurring monetization, then verify SDK behavior and App Store policy requirements in current documentation.
- [RevenueCat's SDK](https://www.revenuecat.com/docs) — iOS Dev Tools · iOS Dev tools: Play, PullRequest, Sonar — Article · Topics: App Distribution & Store Operations
  **Published:** `2024-03-14T16:08:26.033Z`
  **NeKI brief:** RevenueCat's SDK documentation describes configuring products, purchases, entitlements, and customer subscription state in an app. Follow it when prototyping StoreKit-backed subscriptions, while checking platform versions, receipt behavior, and current App Store rules before shipping.
- [Add paywalls in one line of code](https://www.revenuecat.com/docs/paywalls) — iOS Dev Weekly · Issue 640 — Article · Topics: App Distribution & Store Operations · Testing
  **Published:** `15th December 2023`
  **NeKI brief:** RevenueCat documentation for configuring and presenting in-app paywalls through its SDK and dashboard tooling. Use it when evaluating a subscription implementation, validating entitlement flow choices, or integrating RevenueCat's paywall APIs into an Apple-platform app.
- [How to ask the user to leave an App Store review](https://www.youtube.com/watch?v=RUWGjeDCkN8) — SwiftUI Weekly · SwiftUI Weekly - Issue #170 — Video · Topics: App Distribution & Store Operations · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `2023-12-11T13:23:19.560Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [PEP 730 – Adding iOS as a supported platform](https://peps.python.org/pep-0730) — Fatbobman’s Swift Weekly · Issue 6 — Article · Topics: App Distribution & Store Operations · Architecture · Objective-C & Cocoa
  **Published:** `2023-11-13T22:20:44.462Z`
  **NeKI brief:** PEP 730 proposes adding iOS as a supported Python platform and outlines packaging and runtime considerations. Follow it when evaluating Python components in an iOS toolchain, distinguishing language support from native framework and App Store constraints.
- [Swift, meet WinRT](https://speakinginswift.substack.com/p/swift-meet-winrt) — Fatbobman’s Swift Weekly · Issue 5 — Article · Topics: App Distribution & Store Operations · Swift
  **Published:** `2023-11-06T22:30:15.675Z`
  **NeKI brief:** Introduces Swift interoperation with Windows Runtime and the ABI concerns behind projecting WinRT APIs. Use it to understand cross-platform binding work and the boundary between generated Swift interfaces and platform-specific runtime contracts.
- [Creating Shortcuts with App Intents](https://www.kodeco.com/40950083-creating-shortcuts-with-app-intents) — Fatbobman’s Swift Weekly · Issue 5 — Article · Topics: App Distribution & Store Operations · App Intents & System Surfaces · Combine & Reactive Programming
  **Published:** `2023-11-06T22:30:15.675Z`
  **NeKI brief:** Explains creating Shortcuts actions with App Intents and connecting typed app operations to system automation. Use it when exposing discoverable actions while checking entity modeling, parameter resolution, availability, and privacy boundaries.
- [On Launching your Indie App: Part 1](https://www.swiftjectivec.com/on-launching-your-indie-app) — Fatbobman’s Swift Weekly · Issue 3 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games · Swift
  **Published:** `2023-10-23T22:30:20.902Z`
  **NeKI brief:** Reflects on launching an independent app, including product scope, marketing, and release realities. Use it as practitioner context when planning an indie product beyond implementation alone.
- [Glassfy](https://eu1.hubs.ly/H01-5vC0) — SwiftUI Weekly · SwiftUI Weekly - Issue #144 — Article · Topics: App Distribution & Store Operations · Developer Career & Practice · Swift
  **Published:** `2023-05-29T23:10:25.571Z`
  **NeKI brief:** Links to Glassfy's service for managing in-app purchases, paywalls, and backend subscription work. Useful as a product integration lead when comparing hosted monetization infrastructure, SDK coverage, and vendor dependency against StoreKit-first designs.
- [Live App Store & TestFlight review times from Runway](https://www.runway.team/appreviewtimes) — iOS Dev Weekly · Issue 604 — Article · Topics: App Distribution & Store Operations · Testing
  **Published:** `7th April 2023`
  **NeKI brief:** Explores Live App Store & TestFlight review times from Runway, focusing on get a pulse check on current average review times, beta. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Wonderous: Build Wonders with Flutter](https://flutter.gskinner.com/wonderous) — iOS Dev Weekly · Issue 598 — Article · Topics: Accessibility · App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `24th February 2023`
  **NeKI brief:** Explores Wonderous: Build Wonders with Flutter, focusing on wonderous is an open-source ios app built with flutter. it. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Flutter](https://flutter.dev/multi-platform/mobile) — iOS Dev Weekly · Issue 598 — Article · Topics: Accessibility · App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `24th February 2023`
  **NeKI brief:** Explores Flutter, focusing on wonderous is an open-source ios app built with flutter. it features award-winning ux design and best practices for performance and accessibility. see. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [30,000 lines of SwiftUI in production later: We love it but you know there was going to be a “but”](https://blog.timing.is/swiftui-production-experience-problems-solutions-performance-tips) — SwiftUI Weekly · SwiftUI Weekly - Issue #129 — Article · Topics: App Distribution & Store Operations · Swift · SwiftUI
  **Published:** `2023-01-30T11:20:24.661Z`
  **NeKI brief:** Reports production SwiftUI performance problems and the remedies used to diagnose them. Useful as a field-tested checklist for investigating rendering cost, navigation behavior, and architectural friction beyond small sample projects.
- [launch blog post](https://trycombine.com/posts/datatile-for-simulator-public-beta-on-testflight-now) — iOS Dev Weekly · Issue 587 — Article · Topics: App Distribution & Store Operations · Combine & Reactive Programming · Developer Tools
  **Published:** `2nd December 2022`
  **NeKI brief:** Explores launch blog post, focusing on the article discusses don’t know about you, but i still. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Requesting App Store reviews in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL25pbGNvYWxlc2NpbmcuY29tL2Jsb2cvUmVxdWVzdGluZ0FwcFN0b3JlUmV2aWV3c0luU3dpZnRVSS8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiJlOGMyZGIwMC05Y2NjLTRkOWItYmI5Ni1kMWU2MDU3NjFhOTciLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiY2E4YjI1ODQtMmEzYy00OWQ1LThlNzktNTM1NjdlNDI1OTY2IiwiaWF0IjoxNjc0MDYyNTU4Ljg3MywiaXNzIjoib3JjaGlkIn0.gpPrkF9rQIPK1vqfb0AZ1jFSBMP_sLOCzneScAJ-voM) — SwiftUI Weekly · SwiftUI Weekly - Issue #107 — Article · Topics: App Distribution & Store Operations · Swift · SwiftUI
  **Published:** `2022-06-21T10:41:22.000Z`
  **NeKI brief:** Shows how to trigger App Store review requests from SwiftUI while respecting the system-controlled presentation. Useful for choosing a meaningful in-app moment and avoiding repeated or disruptive prompts.
- [Xcodes](https://github.com/RobotsAndPencils/XcodesApp) — iOS Dev Weekly · Issue 538 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Xcode
  **Published:** `17th December 2021`
  **NeKI brief:** Explores Xcodes.app, focusing on the last time i mentioned xcodes, i was still using xcinfo. that changed recently with some fantastic improvements to xcodes.app. especially in. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Getting Started with Combine](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD9mZWF0dXJlPXlvdXR1LmJlJnV0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXImdj1YMm0wZjJOb0IxMCIsInBvc3RfaWQiOiI3NzBkNzMwYy05ZmNkLTRlOTItYWVjNi01YTJjOGM5YjcwZjgiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiYjIzMDBmZWMtNDg2NC00YTRjLWIzM2UtN2JiZDlmNTcwMjUwIiwiaWF0IjoxNjc0MDYyNjc4LjI0MiwiaXNzIjoib3JjaGlkIn0.yG7_Fvr4s6AVhNrkvo-hVvyg2Qj5YZhIkX4eTkhsyG4) — SwiftUI Weekly · SwiftUI Weekly - Issue #56 — Tutorial · Topics: App Distribution & Store Operations · Combine & Reactive Programming · Graphics, Media & Games
  **Published:** `2021-04-26T20:19:20.000Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Creating a licensing system for paid apps in Swift](https://swiftrocks.com/creating-a-license-system-for-paid-apps-in-swift) — iOS Dev Weekly · Issue 502 — Article · Topics: App Distribution & Store Operations · Swift
  **Published:** `9th April 2021`
  **NeKI brief:** Explores Creating a licensing system for paid apps in Swift, focusing on unlike with ios, you have a choice of how you’d. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Xcode 12.3 is available on the Mac App Store](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2FwcHMuYXBwbGUuY29tL2F6L2FwcC94Y29kZS9pZDQ5Nzc5OTgzNT9tdD0xMiZ1dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6ImUwZDA3MDRlLWU3MDItNGQzOC05YjcxLWYxNmMzODc4NGI1ZSIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiI0ODRkOGEwZi02ZTM1LTQ2ODgtOWJlYy04OTdmYWY5M2I5N2MiLCJpYXQiOjE2NzQwNjI2NzkuNzA4LCJpc3MiOiJvcmNoaWQifQ.Rnp31Lwoh2tW1CP8rFSLWGLLC-3eQlf-aop4b01WMPw) — SwiftUI Weekly · SwiftUI Weekly - Issue #39 — Article · Topics: App Distribution & Store Operations · Swift · Xcode
  **Published:** `2020-12-15T13:53:41.000Z`
  **NeKI brief:** Links to the Xcode 12.3 Mac App Store release from the historical issue. Use it only as release-history context when investigating SDK-era behavior, not as a current installation recommendation.
- [defended the “Hey.com” decision](https://techcrunch.com/2020/06/18/interview-apples-schiller-says-position-on-hey-app-is-unchanged-and-no-rules-changes-are-imminent) — iOS Dev Weekly · Issue 469 — Article · Topics: App Distribution & Store Operations
  **Published:** `14th August 2020`
  **NeKI brief:** Covers defended the "Hey.com" decision, focusing on Swift and Apple-platform engineering practice. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [Price Testing for Subscription Apps](https://www.revenuecat.com/blog/price-testing-for-subscription-apps) — iOS Dev Weekly · Issue 467 — Article · Topics: App Distribution & Store Operations · Persistence & Synchronisation · Testing
  **Published:** `31st July 2020`
  **NeKI brief:** Covers Price Testing for Subscription Apps, focusing on testing, diagnostics, and feedback quality. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [StoreKit Testing in Xcode](https://www.revenuecat.com/blog/storekit-testing-in-xcode) — iOS Dev Weekly · Issue 463 — Article · Topics: App Distribution & Store Operations · Testing · Xcode
  **Published:** `3rd July 2020`
  **NeKI brief:** Examines StoreKit Testing in Xcode, focusing on the building, debugging, and testing of storekit code is always stressful. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [You know StoreKit, but you don’t want to do StoreKit](https://docs.revenuecat.com/docs) — iOS Dev Weekly · Issue 458 — Article · Topics: App Distribution & Store Operations · Testing
  **Published:** `29th May 2020`
  **NeKI brief:** Examines You know StoreKit, but you don't want to do StoreKit, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [exist](https://culturedcode.com/things) — iOS Dev Weekly · Issue 380 — Article · Topics: App Distribution & Store Operations
  **Published:** `30th November 2018`
  **NeKI brief:** Things is a polished task-management app for Mac, iPhone, and iPad, organized around planning, projects, and daily actions. Use it as a product reference when evaluating information hierarchy, cross-device workflows, and the interaction quality expected from native productivity software.
- [this project](https://github.com/AvdLee/appstoreconnect-swift-sdk) — iOS Dev Weekly · Issue 377 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Swift
  **Published:** `9th November 2018`
  **NeKI brief:** Examines this project, focusing on the app store connect api is available and documented! straight away, antoine van der lee jumped into action and started…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [not only the App Store](https://512pixels.net/2018/07/mobilemes-legacy) — iOS Dev Weekly · Issue 360 — Article · Topics: App Distribution & Store Operations
  **Published:** `13th July 2018`
  **NeKI brief:** A retrospective marking MobileMe's legacy alongside the App Store's tenth anniversary. It provides historical perspective on Apple's cloud-service evolution.
- [App Store Guidelines](https://gist.github.com/hongrich/260fc8c36aaed3f2a63c0612ba9fc910/revisions) — iOS Dev Weekly · Issue 355 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Spatial Computing
  **Published:** `8th June 2018`
  **NeKI brief:** Examines App Store Guidelines, focusing on but dave, what about all the other stuff from this week? what about the new app store guidelines, the swift 5 delay,…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current.
- [Swift 5 delay](https://github.com/apple/swift-evolution/commit/de7727f7dcf7bbfdea6763a87f4c8c534f27406e) — iOS Dev Weekly · Issue 355 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Swift
  **Published:** `8th June 2018`
  **NeKI brief:** Examines Swift 5 delay, focusing on but dave, what about all the other stuff from this week? what about the new app store guidelines, the swift 5 delay,…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current.
- [Become an iOS Developer with Udacity](https://www.udacity.com/course/ios-developer-nanodegree--nd003?coupon=iosdevweekly) — iOS Dev Weekly · Issue 350 — Tutorial · Topics: App Distribution & Store Operations · Code Quality · Developer Career & Practice
  **Published:** `4th May 2018`
  **NeKI brief:** Examines Become an iOS Developer with Udacity, focusing on enroll in udacity’s ios developer nanodegree program today. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [App Store Guidelines on Templated Apps Relaxed Slightly](https://www.macrumors.com/2017/12/20/app-store-guidelines-updated-template-apps) — iOS Dev Weekly · Issue 332 — Article · Topics: App Distribution & Store Operations
  **Published:** `22nd December 2017`
  **NeKI brief:** Examines App Store Guidelines on Templated Apps Relaxed Slightly, focusing on after last week’s news where the review guidelines were changed to disallow templated apps, there has been a slight…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details.
- [WhatsNew](https://github.com/BalestraPatrick/WhatsNew) — iOS Dev Weekly · Issue 325 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Testing
  **Published:** `3rd November 2017`
  **NeKI brief:** Examines WhatsNew, focusing on almost nobody reads app update information in the app store anymore, so how do you let your users know about what’s new…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Manual Provisioning](http://martiancraft.com/blog/2017/07/manual-provisioning) — iOS Dev Weekly · Issue 310 — Article · Topics: App Distribution & Store Operations · Performance · Xcode
  **Published:** `21st July 2017`
  **NeKI brief:** Xcode 9 manual signing requires an explicit team, profile, and certificate selection, yet Xcode may still request missing certificates. Treat manual provisioning as a controlled configuration workflow and verify portal assets whenever signing behavior looks automatic.
- [App Store Review Guidelines changes from WWDC 2017](http://www.appstorereviewguidelineshistory.com/articles/2017-06-08-new-rules-following-wwdc-2017) — iOS Dev Weekly · Issue 304 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem
  **Published:** `9th June 2017`
  **NeKI brief:** Examines App Store Review Guidelines changes from WWDC 2017, focusing on what else did wwdc bring us? a huge set of changes to the app store review guidelines! 📖 along with some quite shocking…. Use it as a focused research reference for related Apple-platform work.
- [Dash](https://kapeli.com/dash) — iOS Dev Weekly · Issue 271 — Article · Topics: App Distribution & Store Operations
  **Published:** `7th October 2016`
  **NeKI brief:** Dash is a macOS documentation browser with offline docsets and API search. Use it when evaluating local documentation workflows and the trade-off between bundled references and live web search.
- [Code signing guides from fastlane](https://github.com/fastlane/fastlane/tree/master/fastlane/docs/Codesigning) — iOS Dev Weekly · Issue 258 — Source repository · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **Published:** `8th July 2016`
  **NeKI brief:** Examines Code signing guides from fastlane, focusing on felix krause with a set of guides covering all things code signing. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Masterclass: Code signing & Provisioning profiles](http://aplus.rs/2016/masterclass-code-signing) — iOS Dev Weekly · Issue 246 — Article · Topics: App Distribution & Store Operations · Performance
  **Published:** `15th April 2016`
  **NeKI brief:** Explains Masterclass Code signing Provisioning profiles with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [certainly causing problems](http://www.theverge.com/2015/11/19/9757516/ipad-pro-apps-pricing-ios-developers-opt-out) — iOS Dev Weekly · Issue 225 — Article · Topics: App Distribution & Store Operations
  **Published:** `20th November 2015`
  **NeKI brief:** Explains certainly causing problems with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [XcodeGhost](http://researchcenter.paloaltonetworks.com/2015/09/novel-malware-xcodeghost-modifies-xcode-infects-apple-ios-apps-and-hits-app-store) — iOS Dev Weekly · Issue 217 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa · Xcode
  **Published:** `25th September 2015`
  **NeKI brief:** Explains XcodeGhost with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Avoid the Feature](https://500ish.com/avoid-the-feature-f031a42e9e71) — iOS Dev Weekly · Issue 212 — Article · Topics: App Distribution & Store Operations
  **Published:** `21st August 2015`
  **NeKI brief:** M. G. Siegler questions whether a prominent App Store feature benefits a newly launched product, especially a v1 app. It is a cautionary product-distribution perspective on sudden attention and operational readiness.
- [Sparkle](https://github.com/sparkle-project/Sparkle) — iOS Dev Weekly · Issue 198 — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **Published:** `15th May 2015`
  **NeKI brief:** Sparkle provides signed software-update delivery for macOS applications, including feed handling and installer integration. Useful for studying a mature update channel and the security responsibilities around release signatures and keys.
- [builds can also be uploaded with iTMSTransporter as well](https://devforums.apple.com/message/1049285) — iOS Dev Weekly · Issue 170 — Article · Topics: Testing
  **Published:** `31st October 2014`
  **NeKI brief:** Explains builds can also be uploaded with iTMSTransporter as well with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS.
- [Possibility of Promo Codes for IAPs through App Store Code Program](http://9to5mac.com/2014/05/15/apple-opening-up-app-store-promo-codes-to-in-app-purchases) — iOS Dev Weekly · Issue 146 — Article · Topics: App Distribution & Store Operations
  **Published:** `16th May 2014`
  **NeKI brief:** Reports early signs that Apple might enable promo codes for in-app purchases, a limitation that had led developers to build redemption workarounds. Historical context for App Store promotion tooling.
- [iTunes Connect update to Sales and Trends](http://9to5mac.com/2014/02/17/itunes-connect-update-brings-modernized-look-sales-breakdowns-by-category-region-and-more) — iOS Dev Weekly · Issue 134 — Article · Topics: App Distribution & Store Operations · Developer Community & Business
  **Published:** `21st February 2014`
  **NeKI brief:** Reports Apple's overhaul of iTunes Connect Sales and Trends, adding clearer regional and category breakdowns to an area where developers had relied on third-party analytics. Historical App Store business tooling context.
- [Customizing the Navigation and Status Bar in iOS 7](http://www.appcoda.com/customize-navigation-status-bar-ios-7) — iOS Dev Weekly · Issue 118 — Article · Topics: App Distribution & Store Operations
  **Published:** `1st November 2013`
  **NeKI brief:** Explains Customizing the Navigation and Status Bar in iOS 7 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS.
- [Apportable](http://www.youtube.com/watch?v=dSkhtd6L8RM) — iOS Dev Weekly · Issue 117 — Video · Topics: App Services & Extensions · Core Data · Cross-Platform & Web
  **Published:** `25th October 2013`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Code Signing and Mavericks](http://furbo.org/2013/10/17/code-signing-and-mavericks) — iOS Dev Weekly · Issue 116 — Article · Topics: App Distribution & Store Operations
  **Published:** `18th October 2013`
  **NeKI brief:** Explains Code Signing and Mavericks with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Clearly We Have a Problem](http://512pixels.net/2013/09/clearly-we-have-a-problem) — iOS Dev Weekly · Issue 113 — Article · Topics: App Distribution & Store Operations · Testing
  **Published:** `27th September 2013`
  **NeKI brief:** Stephen Hackett examines the fallout from Clear's upgrade and pricing transition, including the difficulty of sustaining an App Store business across new app versions. It is historical product-business context for paid-upgrade decisions.
- [RMStore](https://github.com/robotmedia/RMStore) — iOS Dev Weekly · Issue 111 — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **Published:** `13th September 2013`
  **NeKI brief:** Provides the RMStore source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [New App Store Review Guidelines](http://www.macrumors.com/2013/08/14/apple-releases-new-app-store-review-guidelines-with-updated-info-kids-apps-gambling-app-rules) — iOS Dev Weekly · Issue 107 — Article · Topics: App Distribution & Store Operations
  **Published:** `16th August 2013`
  **NeKI brief:** Explains New App Store Review Guidelines with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [iOS Blur](https://github.com/JagCesar/iOS-blur) — iOS Dev Weekly · Issue 105 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · UIKit
  **Published:** `2nd August 2013`
  **NeKI brief:** Provides the iOS Blur source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Coda and Sandboxing](http://www.panic.com/blog/2012/12/coda-and-sandboxing) — iOS Dev Weekly · Issue 72 — Article · Topics: App Distribution & Store Operations · Performance · Security & Privacy
  **Published:** `14th December 2012`
  **NeKI brief:** Explains Coda and Sandboxing with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [How to Choose Keywords for the App Store](http://mentalfaculty.tumblr.com/post/34476925606/how-to-choose-keywords-for-the-app-store) — iOS Dev Weekly · Issue 66 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `2nd November 2012`
  **NeKI brief:** Explains How to Choose Keywords for the App Store with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [Shenzhen](https://github.com/mattt/shenzhen) — iOS Dev Weekly · Issue 62 — Source repository · Topics: Developer Tools · Testing
  **Published:** `5th October 2012`
  **NeKI brief:** Provides the Shenzhen source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [SCOtutor for ScreenFlow](http://www.screencastsonline.com/appstore) — iOS Dev Weekly · Issue 43 — Tutorial · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `25th May 2012`
  **NeKI brief:** Explains SCOtutor for ScreenFlow with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Greenlight: Pre-submission compliance scanner for the Apple App Store](https://github.com/RevylAI/greenlight) — Not only Swift · Issue 96 — Source repository · Topics: AI Development · App Distribution & Store Operations · Developer Tools
  **NeKI brief:** This source repository covers Apple App Store pre-submission compliance scanning. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [App Store Connect CLI Skills](https://github.com/rudrankriyam/app-store-connect-cli-skills) — Not only Swift · Issue 96 — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **NeKI brief:** This source repository covers skills for automating App Store Connect through the asc CLI. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Google Play Developer CLI](https://github.com/dl-alexandre/Google-Play-Developer-CLI) — Not only Swift · Issue 96 — Source repository · Topics: AI Development · App Distribution & Store Operations · Developer Tools
  **NeKI brief:** This source repository covers an AI-agent-friendly Google Play command-line workflow. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
