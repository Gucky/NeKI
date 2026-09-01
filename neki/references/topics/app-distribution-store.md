# App Distribution & Store Operations

Third-party reading leads collected from NeKI sources. The links may be useful perspectives, but are not vetted recommendations or authoritative API guidance. NeKI publishes routing metadata, not the linked articles' text.

**Scope:** App Store delivery, TestFlight, StoreKit commerce, signing, review, releases, and monetisation workflows.

- Last collected: `2026-09-01T10:14:10Z`
- Indexed links shown: **615**

## Direct-source reading

- [How to fix "The frame rate of your app video preview is too high" error | Sarunw](https://sarunw.com/posts/how-to-fix-the-frame-rate-of-your-app-video-preview-is-too-high) — Sarunw · article catalogue
  **Published:** `2026-08-24`
  **NeKI brief:** Explains why 60 fps or variable-frame-rate screen recordings can be rejected and supplies an ffmpeg conversion to a constant 30 fps stream. Useful with the companion checks for exact dimensions, audio presence, duration, and supported encoding.
- [How to fix app preview wrong resolution error in App Store Connect | Sarunw](https://sarunw.com/posts/how-to-fix-app-preview-wrong-resolution) — Sarunw · article catalogue
  **Published:** `2026-08-24`
  **NeKI brief:** Lists the required per-slot preview pixel sizes and explains why raw device recordings fail. Gives an ffmpeg scaling and padding workflow so conversion targets the selected App Store Connect slot instead of merely matching an aspect ratio.
- [How to fix app preview video that is too long or too short | Sarunw](https://sarunw.com/posts/how-to-fix-app-preview-too-long-or-too-short) — Sarunw · article catalogue
  **Published:** `2026-08-24`
  **NeKI brief:** Shows how to calculate and trim previews to the 15–30-second App Store Connect window with QuickTime or ffmpeg, preserving an otherwise valid export. Treat duration as an independent validation constraint, not a substitute for format or device checks.
- [How to fix app preview stuck on "Processing" in App Store Connect | Sarunw](https://sarunw.com/posts/how-to-fix-app-preview-stuck-processing-app-store-connect) — Sarunw · article catalogue
  **Published:** `2026-08-24`
  **NeKI brief:** Provides a diagnostic order for previews that upload but remain Processing: exact device dimensions, constant 30 fps or lower, audio, 15–30 second duration, accepted codec/container, then browser or Apple-side causes. Includes ffprobe inspection.
- [How to fix "Your app preview contains unsupported or corrupted audio" error | Sarunw](https://sarunw.com/posts/how-to-fix-app-preview-contains-unsupported-or-corrupted-audio) — Sarunw · article catalogue
  **Published:** `2026-08-24`
  **NeKI brief:** Explains that Simulator recordings often have no audio stream although App Store Connect requires one. Provides ffmpeg steps to add a silent audio track, separating this validation failure from codec, duration, resolution, and upload problems.
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
- [Appbot: World-class Review & Ratings Monitoring - iOS Dev Tools](https://iosdev.tools/blog/appbot) — iOS Dev Tools Blog · article catalogue
  **Published:** `2026-02-27T10:31:33+00:00`
  **NeKI brief:** Profiles Appbot as world-class Review & Ratings Monitoring. Use it when evaluating whether this tool or package fits an Apple-platform development, testing, or delivery workflow.
- [AppScreens: Fast, Localized App Store Screenshots - iOS Dev Tools](https://iosdev.tools/blog/appscreens) — iOS Dev Tools Blog · article catalogue
  **Published:** `2026-02-15T20:00:00+00:00`
  **NeKI brief:** Profiles AppScreens as fast, Localized App Store Screenshots. Use it when evaluating whether this tool or package fits an Apple-platform development, testing, or delivery workflow.
- [How to design an SDK to handle $10bn in transactions](https://blog.jacobstechtavern.com/p/revenuecat-sdk) — Jacob’s Tech Tavern · newsletter edition
  **Published:** `2026-01-12T16:01:24.245Z`
  **NeKI brief:** Explains SDK design under high transaction volume through resilient networking, idempotency, caching, observability, and compatibility boundaries, showing how a client library protects product flows while backend systems absorb scale and failure.
- [Escaping the Mac App Store - Building a Distribution and Sales System for Indie Apps from Scratch](https://fatbobman.com/en/posts/zipic-2-selling-and-distribution) — Fatbobman · article catalogue
  **Published:** `2025-12-22T14:11:00.000Z`
  **NeKI brief:** Builds an independent macOS distribution stack around DMG packaging, Sparkle updates, licensing, payments, and key delivery. The walkthrough exposes operational trade-offs hidden by the Mac App Store's integrated sales model.
- [Paddle: Unify Your SaaS Billing Stack - iOS Dev Tools](https://iosdev.tools/blog/paddle) — iOS Dev Tools Blog · article catalogue
  **Published:** `2025-11-04T05:30:35+00:00`
  **NeKI brief:** Profiles Paddle as unify Your SaaS Billing Stack. Use it when evaluating whether this tool or package fits an Apple-platform development, testing, or delivery workflow.
- [Picasso: Professional App Store Screenshots in Minutes - iOS Dev Tools](https://iosdev.tools/blog/picasso) — iOS Dev Tools Blog · article catalogue
  **Published:** `2025-11-04T03:05:00+00:00`
  **NeKI brief:** Profiles Picasso as professional App Store Screenshots in Minutes. Use it when evaluating whether this tool or package fits an Apple-platform development, testing, or delivery workflow.
- [Iconed: Beautiful Icons With Zero Hassle - iOS Dev Tools](https://iosdev.tools/blog/iconed) — iOS Dev Tools Blog · article catalogue
  **Published:** `2025-07-18T14:56:42+00:00`
  **NeKI brief:** Profiles Iconed as beautiful Icons With Zero Hassle. Use it when evaluating whether this tool or package fits an Apple-platform development, testing, or delivery workflow.
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
- [Understanding code signing and provisioning in iOS](https://tanaschita.com/ios-code-signing-provisioning) — Tanaschita · article catalogue
  **NeKI brief:** Code signing and provisioning connect certificates, profiles, entitlements, and bundle identifiers. The guide is useful for diagnosing build and distribution failures by separating identity, capability, and installation concerns.
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
  **NeKI brief:** Examines how frequent app updates can sustain competitiveness. Follow it for concrete release, feedback, and iteration strategy, while treating business claims as contextual rather than technical guidance.
- [Modern Login Items](https://martiancraft.com/blog/2015/01/login-items) — MartianCraft · article catalogue
  **NeKI brief:** A Mac login helper must follow App Store rules, honor a user preference, and be packaged with the main app correctly. Treat launch-at-login as an opt-in lifecycle feature, including its helper-installation and update behavior in the design.

## Newsletter and related leads

- [Mac App Direct Distribution, DMG Signing & Notarization Guide](https://l.fatbobman.com/w0151-05) — Fatbobman’s Swift Weekly · Issue 151 — Article · Topics: App Distribution & Store Operations
  **Published:** `2026-08-31T12:01:53.025Z`
  **NeKI brief:** Walks through direct macOS distribution with Developer ID signing, DMG creation, notarization, stapling, and Gatekeeper validation. Use it as a release-process checklist while verifying current Apple requirements.
- [asc-cli](https://github.com/tddworks/asc-cli) — iOS Dev Tools · iOS Dev Tools: JoltPhysics, asc-cli, Xtend — Source repository · Topics: AI Development · App Distribution & Store Operations · Developer Tools
  **Published:** `2026-08-27T20:30:45.555Z`
  **NeKI brief:** Provides a command-line interface for App Store Connect workflows such as builds, TestFlight, releases, subscriptions, and screenshots. Treat its structured output as an automation integration point while protecting credentials and release authority.
- [AIUsage](https://github.com/sylearn/AIUsage) — iOS Dev Tools · iOS Dev Tools: JoltPhysics, asc-cli, Xtend — Source repository · Topics: AI Development · App Distribution & Store Operations · Developer Tools
  **Published:** `2026-08-27T20:30:45.555Z`
  **NeKI brief:** Provides a dashboard for tracking AI subscriptions, quotas, and costs. Evaluate credential handling and data exposure before connecting personal or team accounts.
- [More Incredible Tales of App Store Curation](https://lapcatsoftware.com/articles/2026/8/9.html) — Those Who Swift · Issue 281 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `2026-08-26T20:38:31.643Z`
  **NeKI brief:** Examines Apple App Store curation through concrete examples of review and editorial treatment. It provides product and distribution context for developers whose release strategy depends on App Store visibility, rather than describing an implementation technique.
- [Appllama](https://appllama.io/) — iOS Dev Tools · iOS Dev Tools: Appllama, KSCrash, Reely — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `2026-08-20T16:31:57.620Z`
  **NeKI brief:** Lets teams inspect onboarding, paywall, and other UI flows from top-grossing iOS apps through a large screen library. Use it for product and UX research while treating observed competitor behaviour as context, not a product prescription.
- [urgent question](https://mjtsai.com/blog/2026/08/14/tabcontrol-scam-and-the-app-review-queue) — Fatbobman’s Swift Weekly · Issue 149 — Article · Topics: App Distribution & Store Operations
  **Published:** `2026-08-17T12:03:38.576Z`
  **NeKI brief:** Documents a Mac App Store extension whose imagery, ratings, reviews, and behavior show multiple fraud signals, then connects the example to review-queue pressure. It provides concrete evidence for judging whether per-submission review catches repeat abuse.
- [From XCUITest to Promo Video](https://l.fatbobman.com/w0149-04) — Fatbobman’s Swift Weekly · Issue 149 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games · Testing
  **Published:** `2026-08-17T12:03:38.576Z`
  **NeKI brief:** Treats screenshots and promo videos as reproducible build artifacts: launch into exact SwiftUI state, drive capture with XCUITest, compose with Remotion, and bind inputs through manifests and hashes. It exposes where automation paid off.
- [StoreSync](https://apps.apple.com/us/app/storesync-metadata-manager/id6775701704?mt=12) — iOS Dev Tools · iOS Dev Tools: Simple Simulator Manager, StoreSync, JsonXmlEditor — Article · Topics: App Distribution & Store Operations · Developer Career & Practice · Persistence & Synchronisation
  **Published:** `2026-08-13T16:30:38.104Z`
  **NeKI brief:** Manages App Store Connect metadata, localizations, diffs, keyword tracking, and competitor research from a native macOS client. API keys stay in Keychain while requests go directly to Apple, clarifying its privacy and workflow model.
- [NoMac](https://nomac.app/) — iOS Dev Tools · iOS Dev Tools: Simple Simulator Manager, StoreSync, JsonXmlEditor — Article · Topics: AI Development · App Distribution & Store Operations · Testing
  **Published:** `2026-08-13T16:30:38.104Z`
  **NeKI brief:** Offers an agent-oriented cloud pipeline that creates signed iOS builds, installs them on a phone, sends them to TestFlight, and submits to the App Store. Its model avoids local Xcode and certificate handling.
- [Understanding code signing and provisioning in iOS](https://tanaschita.com/ios-code-signing-provisioning?ref=createwithswift.com) — Create with Swift · Issue 118 — Article · Topics: App Distribution & Store Operations · Performance · Security & Privacy
  **Published:** `2026-08-01T15:00:04.000Z`
  **NeKI brief:** Code signing and provisioning connect certificates, profiles, entitlements, and bundle identifiers. The guide is useful for diagnosing build and distribution failures by separating identity, capability, and installation concerns.
- [❓ New Age Rating Declaration Questions in App Store Connect](https://helm-app.com/changelog/helm-ios-feedback) — iOS CI Newsletter · Issue 91 — Article · Topics: App Distribution & Store Operations
  **Published:** `2026-07-28T00:00:00.000Z`
  **NeKI brief:** Examines New Age Rating Declaration Questions in App Store Connect in the context of App Distribution & Store Operations. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Apple just improved TestFlight for users with a lot of beta apps](https://9to5mac.com/2026/07/21/apple-just-improved-testflight-for-users-with-a-lot-of-beta-apps) — iOS Dev Weekly · Issue 760 — Article · Topics: App Distribution & Store Operations
  **Published:** `24th July 2026`
  **NeKI brief:** Records TestFlight 4.3's new app search on iPhone and Mac and an apparent expansion of previously tested apps. Useful as release context for beta-heavy workflows, not as an implementation or API reference.
- [getting nowhere with Apple](https://lapcatsoftware.com/articles/2026/7/6.html) — Fatbobman’s Swift Weekly · Issue 145 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `2026-07-20T12:01:22.890Z`
  **NeKI brief:** Diagnoses an App Store Connect login loop by comparing request cookies and finding a missing `dc` session cookie. Follow it for a focused example of browser-level debugging when server behavior contradicts apparent authentication state.
- [An Indie Playbook for the WWDC26 App Store Changes](https://3nsofts.com/guides/app-store/app-store-wwdc26-monetization-indie-playbook) — iOS Dev Weekly · Issue 759 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem
  **Published:** `17th July 2026`
  **NeKI brief:** Examines WWDC26 App Store changes through an indie developer lens, connecting policy updates to pricing, subscriptions, and release planning. Useful for product decisions, but verify current Apple commerce rules before implementation.
- [☁️ How to set a custom build number for your builds in Xcode Cloud](https://antongubarenko.substack.com/p/swift-bits-xcode-cloud-build-number) — iOS CI Newsletter · Issue 90 — Article · Topics: Swift · Testing · Xcode
  **Published:** `2026-07-06T00:00:00.000Z`
  **NeKI brief:** Walks through how to set a custom build number for your builds in Xcode Cloud, with practical context for Swift and Testing. Use it when implementing the workflow, while checking current tool and platform versions before copying the setup.
- [iOS 27 SDK: 3 Major Requirements That Might Break Your App](https://blog.makwanbk.com/ios-27-sdk-3-major-requirements-that-migh-break-your-app?ref=createwithswift.com) — Create with Swift · Issue 114 — Article · Topics: App Distribution & Store Operations · Liquid Glass · Swift
  **Published:** `2026-07-04T15:00:32.000Z`
  **NeKI brief:** Makwan highlights three iOS 27 SDK requirements that could break older apps or block App Store submission: UIScene support, the new launch screen requirement, and the end of the Liquid Glass compatibility opt-out.
- [Joe](https://macaw.social/@mergesort) — iOS Dev Weekly · Issue 757 — Article · Topics: App Distribution & Store Operations · Swift
  **Published:** `3rd July 2026`
  **NeKI brief:** Joe starts with the challenges he hit while using a coding agent to solve a year-old subscription bug, then makes a practical case for better app logging. Broadcast is the result: a Swift logging library shaped around the idea that agents are far more useful…
- [Apple App Store Scraper](https://apify.com/maximedupre/apple-app-store-scraper) — iOS Dev Tools · iOS Dev Tools: Apple App Store Scraper, SideScreen, SiteKit — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `2026-07-02T19:03:32.109Z`
  **NeKI brief:** Apify's Apple App Store Scraper extracts app metadata, ratings, reviews, rankings, and related store information into structured datasets. Use it for repeatable App Store research, while respecting platform terms and rate limits.
- [OpenUsage](https://github.com/robinebers/openusage) — iOS Dev Tools · iOS Dev Tools: Apple App Store Scraper, SideScreen, SiteKit — Source repository · Topics: AI Development · App Distribution & Store Operations · Developer Tools
  **Published:** `2026-07-02T19:03:32.109Z`
  **NeKI brief:** OpenUsage presents subscription and usage information in an open-source desktop utility, helping users see where recurring services are being consumed. Useful as a reference for local usage aggregation and transparent cost awareness.
- [Helm 2.3: WWDC & Helm CLI](https://helm-app.com/changelog/helm-2-3-helm-cli) — SwiftLee Weekly · Issue 329 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem
  **Published:** `2026-06-23T14:07:47.000Z`
  **NeKI brief:** Examines Automate your App Store Connect workflows with Helm’s new CLI! in the context of App Distribution & Store Operations and Apple Platform Ecosystem. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [❓ WWDC26: App Store Connect Group Lab](https://www.youtube.com/watch?v=QPWPgSjg9Kc) — iOS CI Newsletter · Issue 89 — Video · Topics: App Distribution & Store Operations · Apple Platform Ecosystem
  **Published:** `2026-06-17T00:00:00.000Z`
  **NeKI brief:** Records WWDC26: App Store Connect Group Lab as a visual walkthrough relevant to App Distribution & Store Operations and Apple Platform Ecosystem. Use it to inspect the demonstrated workflow, then verify version-specific details with current primary sources.
- [Tokens4Breakfast](https://www.tokens4breakfast.app/) — iOS Dev Tools · iOS Dev Tools: Simtime, Sparkle 2, SwiftINI — Article · Topics: AI Development · App Distribution & Store Operations · Swift
  **Published:** `2026-06-04T17:01:58.905Z`
  **NeKI brief:** Tokens4Breakfast presents a developer or AI-oriented product workflow. Follow it for concrete token or usage-management behavior, while verifying service integrations, limits, and privacy before adoption.
- [TongueType](https://tonguetype.app/) — iOS Dev Tools · iOS Dev Tools: GQLSwift, ScreenPlace, BuildWatch — Article · Topics: AI Development · App Distribution & Store Operations · Personal Essays
  **Published:** `2026-05-28T16:31:04.346Z`
  **NeKI brief:** TongueType is a text or typing utility for macOS. Follow its page for concrete input and productivity interactions, while requiring additional technical evidence before treating it as developer guidance.
- [W.W.D.C. 2026: The Pregame Quiz](https://www.swiftjectivec.com/wwdc-2026-the-pregame-quiz) — Those Who Swift · Issue 268 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `2026-05-27`
  **NeKI brief:** Presents W.W.D.C. 2026: The Pregame Quiz, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Tracking App Store Purchases With Server Notifications](https://azamsharp.com/2026/05/16/storekit2-app-store-server-notifications.html) — Those Who Swift · Issue 267 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `2026-05-21`
  **NeKI brief:** Explains App Store server notifications for tracking subscription purchases. Useful for separating server-confirmed transaction state from client presentation and for designing entitlement updates that survive missed app launches.
- [Northstar](https://www.gonorthstar.io/) — iOS Dev Tools · iOS Dev Tools: SwiftSafeUI, Northstar, Ezscreenshots — Article · Topics: App Distribution & Store Operations
  **Published:** `2026-05-14T16:15:24.123Z`
  **NeKI brief:** Northstar combines App Store keyword opportunity scores, competitor metadata and review tracking, App Store Connect synchronization, and an MCP server for LLM-assisted optimization. It is useful when researching an auditable alternative to ad-hoc ASO spreadsheets.
- [Ezscreenshots](https://ezscreenshots.com/) — iOS Dev Tools · iOS Dev Tools: SwiftSafeUI, Northstar, Ezscreenshots — Article · Topics: App Distribution & Store Operations
  **Published:** `2026-05-14T16:15:24.123Z`
  **NeKI brief:** EzScreenshots provides a workflow for producing screenshots for app stores or product communication. Follow it for concrete promotional-asset composition, while treating conversion claims as vendor marketing.
- [Codemagic CLI tools](https://github.com/codemagic-ci-cd/cli-tools) — iOS Dev Tools · iOS Dev Tools: AscBuddy, TourKit, Hokusai — Source repository · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **Published:** `2026-05-07T16:16:37.368Z`
  **NeKI brief:** Codemagic CLI tools collect utilities for iOS and Android build automation, code signing, and deployment. Useful for inspecting reusable CI primitives before writing bespoke scripts around archives, provisioning, or store uploads.
- [AscBuddy](https://ascbuddy.com/) — iOS Dev Tools · iOS Dev Tools: AscBuddy, TourKit, Hokusai — Article · Topics: App Distribution & Store Operations · Localization
  **Published:** `2026-05-07T16:16:37.368Z`
  **NeKI brief:** AscBuddy positions itself as an App Store Connect workflow tool for optimizing, launching, and growing apps. Follow it for a concrete release-and-growth workflow, while separating its product claims from Apple’s own documentation.
- [CLI](https://www.rocketsim.app/docs/features/agentic-development/rocketsim-cli) — SwiftLee Weekly · Issue 322 — Article · Topics: AI Development · Testing
  **Published:** `2026-05-05T14:09:40.000Z`
  **NeKI brief:** Explains CLI, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Agent Skill](https://www.rocketsim.app/docs/features/agentic-development/agent-skill) — SwiftLee Weekly · Issue 322 — Article · Topics: AI Development · Testing
  **Published:** `2026-05-05T14:09:40.000Z`
  **NeKI brief:** Documents Agent Skill, focusing on an iOS Simulator workflow and the concrete debugging or testing decisions it enables for Apple-platform development.
- [join the TestFlight](https://testflight.apple.com/join/gW6FgtZP) — SwiftLee Weekly · Issue 322 — Article · Topics: App Distribution & Store Operations · Security & Privacy · Testing
  **Published:** `2026-05-05T14:09:40.000Z`
  **NeKI brief:** Links to join the TestFlight, a concrete TestFlight distribution page for evaluating the referenced iOS build anonymously.
- [RocketSim for Teams](https://www.rocketsim.app/for-teams) — SwiftLee Weekly · Issue 322 — Article · Topics: App Distribution & Store Operations · Security & Privacy · Testing
  **Published:** `2026-05-05T14:09:40.000Z`
  **NeKI brief:** Documents RocketSim for Teams, focusing on an iOS Simulator workflow and the concrete debugging or testing decisions it enables for Apple-platform development.
- [Tyndale](https://github.com/ogrodev/tyndale) — iOS Dev Tools · iOS Dev Tools: KIF, AeroSpace, FineTune — Source repository · Topics: AI Development · App Distribution & Store Operations · Developer Tools
  **Published:** `2026-05-01T08:18:29.566Z`
  **NeKI brief:** Tyndale is a Swift or Apple-platform developer project. Follow its README and source to inspect the concrete workflow and API surface, then verify supported platforms and maintenance before adoption.
- [creating a feed to allow the site to index them](https://swiftgrounds.dev/publish) — iOS Dev Weekly · Issue 749 — Article · Topics: App Distribution & Store Operations · Developer Community & Business · Swift
  **Published:** `1st May 2026`
  **NeKI brief:** Playgrounds remain one of the best on-ramps into Swift, and a discovery layer for community-made content is exactly what’s been missing since Apple removed the subscriptions functionality. So, if you run a blog or otherwise produce educational content for…
- [Cut App Store Fees on Every Subscription You Sell](https://web2wave.com/) — iOS Dev Tools · iOS Dev Tools: Yotei, Pica, Revyl — Article · Topics: App Distribution & Store Operations
  **Published:** `2026-04-23T16:32:50.159Z`
  **NeKI brief:** Web2Wave promotes a service for reducing App Store fees on subscriptions. It is commercial monetization guidance rather than technical implementation reading and should normally be excluded from the knowledge index.
- [See Where Your App Ranks in the App Store](https://bitrise.io/resources/tools/app-navigator) — iOS Dev Tools · iOS Dev Tools: SwiftZilla, Room Service, Pica — Article · Topics: App Distribution & Store Operations
  **Published:** `2026-04-16T16:01:26.478Z`
  **NeKI brief:** Bitrise App Navigator benchmarks an app’s App Store position and related competitive signals. Follow it for a concrete mobile-growth measurement workflow, while treating ranking data as time-sensitive commercial analytics.
- [restricting third-party access tools like OpenClaw](https://www.theverge.com/ai-artificial-intelligence/907074/anthropic-openclaw-claude-subscription-ban) — Those Who Swift · Issue 262 — Article · Topics: AI Development · App Distribution & Store Operations
  **Published:** `2026-04-15`
  **NeKI brief:** Reviews restricting third-party access tools like OpenClaw. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Silkwave Voice](https://www.silkwave.ai/silkwave-voice) — iOS Dev Tools · iOS Dev Tools: Audio-mcp, Remodex, Pippin — Podcast · Topics: AI Development · App Distribution & Store Operations · Developer Community & Business
  **Published:** `2026-04-09T17:01:21.324Z`
  **NeKI brief:** Silkwave Voice provides voice generation or speech-processing functionality. Follow it for concrete audio-generation and integration workflows, while checking model, licensing, privacy, and export constraints.
- [iOS Agent Skills, App Store Connect CLI, Foundation Models Tokens & More](https://www.youtube.com/watch?v=VU-NiioUpxg&t=237s) — Those Who Swift · Issue 260 — Video · Topics: AI Development · App Distribution & Store Operations · Foundation & Data Formats
  **Published:** `2026-04-01`
  **NeKI brief:** Reviews iOS Agent Skills, App Store Connect CLI, Foundation Models Tokens & More. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [MacRumors](https://www.macrumors.com/2026/03/26/apple-swift-student-challenge-winners-2026?ref=ioscodereview.com) — iOS Code Review · Issue 76 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games · Swift
  **Published:** `2026-03-30T18:21:46.000Z`
  **NeKI brief:** Examines MacRumors in the context of App Distribution & Store Operations and Graphics, Media & Games. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Join the TestFlight](https://testflight.apple.com/join/emGszFpq) — SwiftLee Weekly · Issue 316 — Article · Topics: App Distribution & Store Operations · Developer Community & Business · Testing
  **Published:** `2026-03-24T15:03:10.000Z`
  **NeKI brief:** Links to Join the TestFlight, a concrete TestFlight distribution page for evaluating the referenced iOS build anonymously.
- [web2wave](https://www.web2wave.com/) — iOS Dev Tools · iOS Dev Tools: web2wave, CoreDataBrowser, DataStoreKit — Article · Topics: App Distribution & Store Operations · Testing
  **Published:** `2026-03-19T17:30:50.047Z`
  **NeKI brief:** Web2Wave promotes services for mobile-app subscription monetization. It is commercial growth material rather than technical implementation reading and should normally be excluded from the knowledge index.
- [DataStoreKit](https://github.com/asymbas/datastorekit) — iOS Dev Tools · iOS Dev Tools: web2wave, CoreDataBrowser, DataStoreKit — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Persistence & Synchronisation
  **Published:** `2026-03-19T17:30:50.047Z`
  **NeKI brief:** DataStoreKit provides Swift persistence abstractions for storing application data. Follow its source and tests for concrete serialization, caching, and lifecycle semantics, then compare them with the project’s existing persistence layer.
- [How iOS apps actually make money](https://www.revenuecat.com/state-of-subscription-apps) — SwiftLee Weekly · Issue 315 — Article · Topics: App Distribution & Store Operations
  **Published:** `2026-03-17T15:01:49.000Z`
  **NeKI brief:** Explains How iOS apps actually make money, connecting the underlying Apple-platform mechanism to implementation choices and practical trade-offs that Swift developers can evaluate.
- [ASC CLI](https://github.com/rudrankriyam/App-Store-Connect-CLI) — Fatbobman’s Swift Weekly · Issue 127 — Source repository · Topics: AI Development · App Distribution & Store Operations · Developer Tools
  **Published:** `2026-03-16T12:04:00.245Z`
  **NeKI brief:** App-Store-Connect-CLI automates App Store Connect tasks from the command line, including subscription-related setup. Use it to replace repetitive portal configuration with reviewable scripts, while treating credentials and destructive commands carefully.
- [Automating Mac App Screenshots](https://www.amyworrall.com/blog/automating-mac-app-screenshots) — Those Who Swift · Issue 256 — Article · Topics: App Distribution & Store Operations
  **Published:** `2026-03-06`
  **NeKI brief:** Examines Automating Mac app screenshots — Amy Worrall. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [AcceptedSE-0509Software Bill of Materials (SBOM) Generation for Swift Package Manager](https://github.com/apple/swift-evolution/blob/main/proposals/0509-swift-sboms-via-swiftpm.md) — SwiftLee Weekly · Issue 313 — Source repository · Topics: App Distribution & Store Operations · Swift · Swift Package Manager
  **Published:** `2026-03-03T15:11:29.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0509Software Bill of Materials (SBOM) Generation for Swift Package Manager. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0515Allow `reduce` to produce noncopyable results](https://github.com/apple/swift-evolution/blob/main/proposals/0515-noncopyable-reduce.md) — SwiftLee Weekly · Issue 313 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Swift
  **Published:** `2026-03-03T15:11:29.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0515Allow `reduce` to produce noncopyable results. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Active ReviewSE-0516Borrowing Sequence](https://github.com/apple/swift-evolution/blob/main/proposals/0516-borrowing-sequence.md) — SwiftLee Weekly · Issue 313 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Swift
  **Published:** `2026-03-03T15:11:29.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for Active ReviewSE-0516`Iterable`. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Release white-label apps with a single click](https://www.runway.team/use-case/white-label) — SwiftLee Weekly · Issue 312 — Article · Topics: App Distribution & Store Operations
  **Published:** `2026-02-24T15:08:55.000Z`
  **NeKI brief:** Discusses Release white-label apps with a single click, providing concrete engineering context that Apple-platform developers can use when evaluating the referenced workflow.
- [If You’re Not Versioning Your SwiftData Schema, You’re Gambling](https://azamsharp.com/2026/02/14/if-you-are-not-versioning-your-swiftdata-schema.html) — Those Who Swift · Issue 254 — Article · Topics: App Distribution & Store Operations · Swift · SwiftData
  **Published:** `2026-02-18`
  **NeKI brief:** Azam explains why schema versioning in SwiftData is essential once your app stores real user data and shows how to define VersionedSchema, implement custom migrations, and evolve models.
- [Understanding Apple’s Retention Messaging API](https://www.revenuecat.com/blog/engineering/apple-retention-messaging-api) — iOS Dev Weekly · Issue 742 — Article · Topics: App Distribution & Store Operations · Combine & Reactive Programming
  **Published:** `6th February 2026`
  **NeKI brief:** Explains Apple’s Retention Messaging API and how subscription apps can communicate with lapsed customers. Useful for connecting retention features with entitlement-aware messaging and lifecycle decisions.
- [Paywalls that work on the web as well](https://www.revenuecat.com/blog/company/paywalls-on-the-web) — iOS Dev Weekly · Issue 741 — Article · Topics: App Distribution & Store Operations
  **Published:** `30th January 2026`
  **NeKI brief:** RevenueCat Paywalls now work on the web — meaning the same paywalls you design for iOS can now render in the browser. With Web Purchase Links and the Web SDK (Purchases.js), you can reuse your existing paywall layouts and experiments, manage subscription…
- [InAppPurchaseKit](https://github.com/adamfootdev/InAppPurchaseKit) — iOS Dev Tools · iOS Dev Tools: Bullseye, Commander, InAppPurchaseKit — Source repository · Topics: App Distribution & Store Operations · Apple Platform Ecosystem · Developer Tools
  **Published:** `2026-01-29T21:12:37.433Z`
  **NeKI brief:** InAppPurchaseKit packages common in-app-purchase workflows for Swift applications. Follow its source for concrete product loading, entitlement, and transaction abstractions, then verify StoreKit version assumptions separately.
- [rolling out changes to App Store search ads](https://www.macrumors.com/2026/01/23/more-app-store-ads-coming-soon) — Those Who Swift · Issue 251 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem · Objective-C & Cocoa
  **Published:** `2026-01-28`
  **NeKI brief:** Reviews rolling out changes to App Store search ads. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Struggling to Market Your iOS or Android App? Try Affiliate Marketing](https://insertaffiliate.com/) — iOS Dev Tools · iOS Dev Tools: MachScope, SwiftFindRefs, HealthKit Data Generator — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `2026-01-22T20:01:38.499Z`
  **NeKI brief:** This page promotes affiliate marketing as a way to market iOS or Android applications. It is commercial growth guidance rather than technical implementation reading, so use it only as business context.
- [The complete guide to high-converting paywalls](https://www.revenuecat.com/blog/growth/paywalls-study-guide) — iOS Dev Weekly · Issue 739 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `16th January 2026`
  **NeKI brief:** What actually makes a paywall convert? We analyzed real-world subscription data and design patterns to break down what works, what doesn’t, and why. This study guide pulls together research, examples, and practical takeaways to help you design paywalls that…
- [Slaven Radic](https://www.threads.com/@slaven) — iOS Dev Weekly · Issue 739 — Article · Topics: App Distribution & Store Operations
  **Published:** `16th January 2026`
  **NeKI brief:** I enjoyed this post from Slaven Radic on marketing his Finalist app. He talks about the other aspects of success that can come from advertising on personal sites run by influential people. The kind of results that App Store or Facebook Ads could never deliver.
- [WWDC Index](https://nonstrict.eu/wwdcindex) — iOS Dev Weekly · Issue 739 — Article · Topics: Apple Platform Ecosystem · Graphics, Media & Games · Testing
  **Published:** `16th January 2026`
  **NeKI brief:** This technical resource covers a searchable index of WWDC material. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [my YouTube series on this app](https://youtube.com/playlist?list=PLg4qABgFp_nRYMtGFdXz8sUeXb2IDxdPL&si=Imqah2BEAj-b-WAM) — SwiftLee Weekly · Issue 306 — Video · Topics: App Distribution & Store Operations · Graphics, Media & Games · Testing
  **Published:** `2026-01-13T15:06:45.000Z`
  **NeKI brief:** Documents building and launching an open-source app toward $10K monthly recurring revenue, including releases, App Store review, crashes, growth, pricing, and technical decisions. Useful for connecting product milestones with implementation trade-offs.
- [RevenueCat Paywalls: Build & iterate subscription flows faster](https://www.revenuecat.com/blog/engineering/paywalls-changelog) — iOS Dev Weekly · Issue 738 — Article · Topics: App Distribution & Store Operations
  **Published:** `9th January 2026`
  **NeKI brief:** The RevenueCat engineering article describes its paywall tooling and changelog, focusing on building and iterating subscription flows.
- [StoreKit Subscriptions: Understanding Monetization Models](https://azamsharp.com/2025/12/26/storekit-subscriptions-understanding-monetization-models.html) — Those Who Swift · Issue 247 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `2026-01-01`
  **NeKI brief:** Explains StoreKit subscription monetization models. Useful for separating product configuration, eligibility, entitlement state, and paywall presentation when designing subscription flows.
- [🪝 How the new App Store Connect webhooks can power your automations](https://en.zhgchg.li/posts/zrealm-dev/app-store-connect-api-webhook-automate-ci-cd-workflows-seamlessly-7c0974856393) — iOS CI Newsletter · Issue 84 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem
  **Published:** `2025-12-31T00:00:00.000Z`
  **NeKI brief:** Examines How the new App Store Connect webhooks can power your automations in the context of App Distribution & Store Operations and Apple Platform Ecosystem. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Apple tightens App Review Guidelines to crack down on copycat apps](https://9to5mac.com/2025/11/13/apple-tightens-app-review-guidelines-to-crack-down-on-copycat-apps) — iOS Dev Weekly · Issue 737 — Article · Topics: App Distribution & Store Operations
  **Published:** `19th December 2025`
  **NeKI brief:** Discusses Apple's new App Review Guidelines crack down on copycat apps, extracting concrete engineering practices and trade-offs that Apple-platform developers can apply when evaluating this workflow.
- [Price Localize App](https://pricelocalize.com/) — iOS Dev Tools · iOS Dev Tools: Price Localize App, Swift AI SDK, ThreadCommissionerKit — Article · Topics: App Distribution & Store Operations
  **Published:** `2025-12-11T17:45:25.072Z`
  **NeKI brief:** Price Localize helps localize or compare application prices across storefronts. Follow it for concrete regional pricing workflows, while verifying current App Store policies and data freshness.
- [VibeProxy](https://github.com/automazeio/vibeproxy) — iOS Dev Tools · iOS Dev Tools: Price Localize App, Swift AI SDK, ThreadCommissionerKit — Source repository · Topics: App Distribution & Store Operations · Developer Tools · macOS & AppKit
  **Published:** `2025-12-11T17:45:25.072Z`
  **NeKI brief:** VibeProxy presents a proxy-oriented developer tool. Follow its source and README for concrete traffic-routing or integration behavior, while verifying protocol support, credentials, and security implications before use.
- [Endel](https://endel.io/) — iOS Dev Tools · iOS Dev Tools: Price Localize App, Swift AI SDK, ThreadCommissionerKit — Article · Topics: App Distribution & Store Operations · macOS & AppKit
  **Published:** `2025-12-11T17:45:25.072Z`
  **NeKI brief:** Endel describes adaptive soundscapes intended to support focus, relaxation, and sleep. Follow it only as a concrete productivity-app example; it is not a technical Apple-platform resource.
- [demo projects](https://github.com/zhangqifan/Insights) — Fatbobman’s Swift Weekly · Issue 111 — Source repository · Topics: App Distribution & Store Operations · Architecture · Liquid Glass
  **Published:** `2025-11-17T12:02:46.781Z`
  **NeKI brief:** Insights contains demo projects for applying Liquid Glass design to a production health app. Use it to inspect concrete adaptations of translucent materials, hierarchy, and interaction rather than treating WWDC design guidance as abstract theory.
- [Proven with 3D printing](https://matthewcassinelli.com/apple-logos-actually-3d-renderings-app-icons) — iOS Dev Weekly · Issue 735 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `14th November 2025`
  **NeKI brief:** Did you know both the App Store and Shortcuts logos are actually made up of 3D icons? Proven with 3D printing. 🖨️
- [Subscription Day](https://appps.od.ua/subscription-day) — iOS Dev Tools · iOS Dev Tools: PostgresNIO, SwiftDisc, SM3 — Article · Topics: App Distribution & Store Operations · macOS & AppKit
  **Published:** `2025-11-13T17:02:43.035Z`
  **NeKI brief:** Subscription Day tracks recurring subscriptions on macOS and presents their renewal schedule. Follow it for a concrete utility pattern around calendar-linked reminders, recurring payment visibility, and lightweight personal data management.
- [iOS Conf SG](https://www.iosconf.sg/) — iOS Dev Tools · iOS Dev Tools: PostgresNIO, SwiftDisc, SM3 — Article · Topics: App Distribution & Store Operations
  **Published:** `2025-11-13T17:02:43.035Z`
  **NeKI brief:** iOS Conf SG is an Apple-platform developer conference page. It is event promotion rather than technical reading and should normally be excluded from the knowledge index.
- [ARCtic Conference](https://arcticonference.com/) — iOS Dev Tools · iOS Dev Tools: PostgresNIO, SwiftDisc, SM3 — Article · Topics: App Distribution & Store Operations · Developer Community & Business · Objective-C & Cocoa
  **Published:** `2025-11-13T17:02:43.035Z`
  **NeKI brief:** ARCtic Conference is an Apple-platform developer event covering iOS, visionOS, iPadOS, macOS, and watchOS. This page is an event listing rather than technical reading and should normally remain excluded from the knowledge index.
- [Apple launching a web-based version of the App Store](https://9to5mac.com/2025/11/03/apple-launches-rich-new-web-interface-for-the-app-store) — iOS Dev Weekly · Issue 734 — Article · Topics: App Distribution & Store Operations
  **Published:** `7th November 2025`
  **NeKI brief:** Reports a richer web interface for the App Store and the implications for discovering app information outside the native client. Useful current-product context, with behavior and availability verified independently before relying on it.
- [🤩 Improvements to review submissions in App Store Connect](https://9to5mac.com/2025/10/29/apple-adds-new-app-store-submission-and-marketing-features-will-phase-out-promo-codes-in-2026) — iOS CI Newsletter · Issue 79 — Tutorial · Topics: App Distribution & Store Operations · Developer Community & Business
  **Published:** `2025-11-02T00:00:00.000Z`
  **NeKI brief:** Examines Improvements to review submissions in App Store Connect in the context of App Distribution & Store Operations and Developer Community & Business. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [UK designates Apple and Google as having ‘strategic market status’ opening door for more regulation](https://techcrunch.com/2025/10/22/u-k-designates-apple-and-google-as-having-strategic-market-status-opening-door-for-more-regulation) — iOS Dev Weekly · Issue 732 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `24th October 2025`
  **NeKI brief:** Sarah Perez reports on the UK Competition and Markets Authority’s (CMA) ruling, which starts the process of defining new rules and regulations for iOS, Android, their app stores, and browsers. There will be no immediate changes, as the regulatory process…
- [UK Competition and Markets Authority](https://www.gov.uk/government/organisations/competition-and-markets-authority) — iOS Dev Weekly · Issue 732 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `24th October 2025`
  **NeKI brief:** Sarah Perez reports on the UK Competition and Markets Authority’s (CMA) ruling, which starts the process of defining new rules and regulations for iOS, Android, their app stores, and browsers. There will be no immediate changes, as the regulatory process…
- [Evolving AltStore PAL](https://rileytestut.com/blog/2025/10/07/evolving-altstore-pal) — iOS Dev Weekly · Issue 730 — Article · Topics: App Distribution & Store Operations · Testing
  **Published:** `10th October 2025`
  **NeKI brief:** It’s been a while since I mentioned AltStore PAL, the (currently) EU-exclusive third-party app store developed by Riley Testut and Shane Gill and funded by Epic. This week saw them post an update covering their progress so far and some of their plans for the…
- [funded by Epic](https://www.theverge.com/2024/8/14/24220623/altstore-pal-third-party-app-store-drops-subscription-epic-grant) — iOS Dev Weekly · Issue 730 — Article · Topics: App Distribution & Store Operations · Testing
  **Published:** `10th October 2025`
  **NeKI brief:** The article reports AltStore PAL's third-party app-store developments, including its subscription change and Epic funding.
- [App Store Optimization: Real-world Best Practices](https://l.fatbobman.com/w0104-06) — Fatbobman’s Swift Weekly · Issue 104 — Article · Topics: App Distribution & Store Operations
  **Published:** `2025-09-29T12:00:38.726Z`
  **NeKI brief:** Collects App Store Optimization practices for improving an app’s visibility and acquisition. Follow it when connecting store metadata, screenshots, and positioning to release planning without confusing marketing signals with product quality.
- [Feature Flags in Swift](https://l.fatbobman.com/w0103-03) — Fatbobman’s Swift Weekly · Issue 103 — Article · Topics: Combine & Reactive Programming · Swift · Testing
  **Published:** `2025-09-22T12:03:29.428Z`
  **NeKI brief:** Shows how Swift feature flags can vary behavior across Debug, TestFlight, and App Store configurations. Follow it when designing compile-time or runtime switches that keep release behavior explicit and testable.
- [Ship better paywalls faster with RevenueCat’s native, customizable Paywall Builder](https://www.revenuecat.com/docs/tools/paywalls-v2) — iOS Dev Weekly · Issue 726 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `12th September 2025`
  **NeKI brief:** Documents RevenueCat Paywalls 2 tooling for configuring and presenting subscription paywalls. Use it to inspect templates, purchase flows, and customization boundaries before integrating monetization into an app.
- [join the TestFlight here](https://testflight.apple.com/join/jNkgt4mf) — SwiftLee Weekly · Issue 288 — Article · Topics: App Distribution & Store Operations · Testing
  **Published:** `2025-09-09T18:49:30.000Z`
  **NeKI brief:** Links to join the TestFlight here, a concrete TestFlight distribution page for evaluating the referenced iOS build anonymously.
- [Radar](https://apps.apple.com/us/app/radar-app-keyword-optimization/id6748053217) — iOS Dev Tools · iOS Dev Tools: IQListKit, Radar, HapticPlayer — Article · Topics: App Distribution & Store Operations
  **Published:** `2025-09-04T15:31:16.101Z`
  **NeKI brief:** Radar combines App Store keyword tools, market insights, and current store data for app publishers. Use it to explore a concrete ASO research workflow involving competitor tracking and metadata decisions, not runtime engineering.
- [Discover TestFlight apps on Indie App Catalog](https://indieappcatalog.com/news/discover-testflight-apps) — iOS Dev Weekly · Issue 723 — Article · Topics: App Distribution & Store Operations · Testing
  **Published:** `22nd August 2025`
  **NeKI brief:** Examines You can now find and share TestFlight invites right on Indie App Catalog. Browse app betas, submit your own invite links, and see live availability so you don’t. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Designerants](https://www.designerants.com/) — iOS Dev Tools · iOS Dev Tools: ch.at, Mercato, Dependencies — Article · Topics: App Distribution & Store Operations
  **Published:** `2025-08-14T19:53:26.103Z`
  **NeKI brief:** Designerants is a design-oriented resource or product page. Follow it for concrete interface and visual-design context, while requiring further technical evidence before treating it as implementation guidance.
- [App Growth Academy](https://appgrowthacademy.com/) — iOS Dev Tools · iOS Dev Tools: ch.at, Mercato, Dependencies — Article · Topics: App Distribution & Store Operations
  **Published:** `2025-08-14T19:53:26.103Z`
  **NeKI brief:** App Growth Academy presents practical guidance on paywalls, App Store optimization, advertising, acquisition, and mobile monetization. Use it as a business-oriented community perspective when assessing how product and revenue choices affect an app.
- [Mercato](https://github.com/tikhop/Mercato) — iOS Dev Tools · iOS Dev Tools: ch.at, Mercato, Dependencies — Source repository · Topics: App Distribution & Store Operations · Developer Career & Practice · Developer Tools
  **Published:** `2025-08-14T19:53:26.103Z`
  **NeKI brief:** Mercato wraps StoreKit 2 for subscriptions and in-app purchases across Apple platforms, aiming to reduce repetitive transaction plumbing. Useful for comparing a focused purchase abstraction with direct StoreKit state and entitlement management.
- [Giselle Katics](https://gkatics.github.io/giKatics) — iOS Dev Weekly · Issue 720 — Article · Topics: App Distribution & Store Operations · Developer Tools · Testing
  **Published:** `1st August 2025`
  **NeKI brief:** But could there be more metadata on App Store pages in the future? I felt inspired to write this after reading Giselle Katics‘ latest article, “Building for hate: Designing for deception”. The whole article is worth a read, but this piece stood out to me:
- [iOS 26 Public Beta](https://sixcolors.com/post/2025/07/first-look-ios-26-public-beta) — iOS Dev Weekly · Issue 719 — Article · Topics: App Distribution & Store Operations · Testing
  **Published:** `25th July 2025`
  **NeKI brief:** Examines Six Colors by Jason Snell, Dan Moren and friends. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Picasso](https://getpicasso.com/) — iOS Dev Tools · iOS Dev Tools: Picasso, YoutubeTranscript, Applite — Article · Topics: App Distribution & Store Operations
  **Published:** `2025-07-17T18:57:30.320Z`
  **NeKI brief:** Picasso provides a workflow for composing app screenshots and promotional visuals. Follow it for a concrete storefront-asset tool, while treating claims about downloads or conversion as commercial context.
- [🏷️ Uploading your app to TestFlight using GitHub Actions](https://nowham.dev/posts/github_actions_testflight) — iOS CI Newsletter · Issue 72 — Article · Topics: App Distribution & Store Operations · Developer Tools · Testing
  **Published:** `2025-07-14T00:00:00.000Z`
  **NeKI brief:** Examines Uploading your app to TestFlight using GitHub Actions in the context of App Distribution & Store Operations and Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🧪 How to run Unit Tests on CI/CD](https://nowham.dev/posts/github_actions_unit_tests) — iOS CI Newsletter · Issue 71 — Article · Topics: CI/CD & Automation · Developer Tools · Testing
  **Published:** `2025-06-30T00:00:00.000Z`
  **NeKI brief:** Walks through how to run Unit Tests on CI/CD, with practical context for CI/CD & Automation and Developer Tools. Use it when implementing the workflow, while checking current tool and platform versions before copying the setup.
- [read all about it inside the documentation](https://docs.rocketsim.app/features/hzQMSrSga7BGWvxdNVdwYs/simulator-camera-support/58tQ5jvevLNSnyUEA7VgAv) — SwiftLee Weekly · Issue 277 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `2025-06-24T14:09:23.000Z`
  **NeKI brief:** Presents RocketSim's documentation, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [App Store SEO Algorithm Change](https://appfigures.com/resources/guides/app-store-algorithm-update-2025) — iOS Dev Weekly · Issue 714 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `13th June 2025`
  **NeKI brief:** Examines We reverse engineered a BIG change to the App Store that. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Get Paid While You Sleep](https://www.tiagohenriques.dev/blog/get-paid-while-you-sleep) — Those Who Swift · Issue 218 — Article
  **Published:** `2025-06-11`
  **NeKI brief:** Reviews Get Paid While You Sleep. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [StoreKit Examples - GitHub Repo](https://github.com/jordibruin/StoreKit-Examples) — SwiftLee Weekly · Issue 273 — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **Published:** `2025-05-27T14:08:19.000Z`
  **NeKI brief:** Points to StoreKit Examples - GitHub Repo, an open-source implementation or issue with concrete code and discussion that can inform Apple-platform development decisions.
- [App Review-safe Swift implementation](https://github.com/sebjvidal/_UIContextMenuAccessoryView-Demo) — Fatbobman’s Swift Weekly · Issue 84 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Swift
  **Published:** `2025-05-19T12:00:44.196Z`
  **NeKI brief:** Demonstrates an App Review-safe Swift approach to context-menu accessory UI inspired by Messages. Use it to understand the public-API boundary and avoid shipping private UIKit techniques that merely reproduce system visuals.
- [Sway](https://testflight.apple.com/join/dmAf4kmN) — iOS Dev Weekly · Issue 712 — Article · Topics: App Distribution & Store Operations · Testing
  **Published:** `16th May 2025`
  **NeKI brief:** Examines Using TestFlight is a great way to help developers test beta versions of their apps. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Mela](https://9to5mac.com/2025/05/01/apple-app-store-guidelines-external-links?ref=createwithswift.com) — Create with Swift · Issue 59 — Article · Topics: App Distribution & Store Operations · Swift
  **Published:** `2025-05-02T15:00:54.000Z`
  **NeKI brief:** In response to this update, major developers are already making adjustments to their apps and prominent players are sharing resources or updating their guides to allow users to purchase or subscribe to content outside of the App Store in the US storefront.
- [GrowASO](https://www.growaso.com/) — iOS Dev Tools · iOS Dev Tools: GrowASO, XcodeBuild MCP, Compot — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `2025-05-01T14:50:23.226Z`
  **NeKI brief:** GrowASO provides App Store Optimization and growth tooling. Follow it for concrete keyword, listing, and performance-analysis workflows, while treating market data as time-sensitive commercial context.
- [Apple Rebrands Search Ads as Apple Ads](https://searchengineland.com/apple-search-ads-apple-ads-454356) — Those Who Swift · Issue 211 — Article · Topics: App Distribution & Store Operations · Developer Tools · Objective-C & Cocoa
  **Published:** `2025-04-24`
  **NeKI brief:** Reports Apple’s rebranding of Search Ads. Useful for App Store acquisition context, while current campaign behavior requires official documentation.
- [🍎 Can your AI Assistant help you with App Store Connect issues?](https://github.com/JoshuaRileyDev/app-store-connect-mcp-server) — iOS CI Newsletter · Issue 66 — Source repository · Topics: AI Development · App Distribution & Store Operations · Developer Tools
  **Published:** `2025-04-20T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for Can your AI Assistant help you with App Store Connect issues?, relevant to AI Development and App Distribution & Store Operations. Inspect its implementation, open issues, and release state before adopting the approach.
- [top App Store earnings](https://appfigures.com/resources/insights/20250411?f=3) — iOS Dev Weekly · Issue 708 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `18th April 2025`
  **NeKI brief:** Examines March is officially behind us and that means it. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Pressdeck](https://pressdeck.io/) — iOS Dev Tools · iOS Dev Tools: FormattedListKit, Libraried, Pressdeck — Article · Topics: AI Development · App Distribution & Store Operations
  **Published:** `2025-04-17T13:23:18.210Z`
  **NeKI brief:** Pressdeck provides a workflow for creating or distributing app press materials. Follow it for concrete product-communication and asset-management behavior, while treating promotional claims as commercial context.
- [easy-frame](https://github.com/alschmut/EasyFrameCommand) — iOS Dev Tools · iOS Dev Tools: easy-frame, Sweetpad, StoreKitHelper — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Swift
  **Published:** `2025-04-11T07:56:27.598Z`
  **NeKI brief:** EasyFrameCommand is a Swift CLI that creates framed App Store screenshots from custom SwiftUI layouts. Useful for repeatable marketing-image generation that keeps device framing in source-controlled code instead of manual editing.
- [StoreKitHelper](https://github.com/jaywcjlove/StoreKitHelper) — iOS Dev Tools · iOS Dev Tools: easy-frame, Sweetpad, StoreKitHelper — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Swift
  **Published:** `2025-04-11T07:56:27.598Z`
  **NeKI brief:** StoreKitHelper wraps StoreKit 2 for SwiftUI in a lightweight package, reducing repeated purchase and entitlement plumbing. Useful for comparing a small declarative helper with direct StoreKit transaction observation and product loading.
- [🚀 How to automate App Store screenshot generation for macOS apps](https://www.jessesquires.com/blog/2025/03/24/automate-perfect-mac-screenshots) — iOS CI Newsletter · Issue 65 — Article · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Community & Business
  **Published:** `2025-04-06T00:00:00.000Z`
  **NeKI brief:** Walks through how to automate App Store screenshot generation for macOS apps, with practical context for App Distribution & Store Operations and CI/CD & Automation. Use it when implementing the workflow, while checking current tool and platform versions before copying the setup.
- [ASO.dev](https://aso.dev/) — iOS Dev Tools · iOS Dev Tools: WinWinKit, ASO.dev, NeoBrutalism — Article · Topics: App Distribution & Store Operations
  **Published:** `2025-04-03T14:55:54.485Z`
  **NeKI brief:** ASO.dev combines App Store Optimization tools with metadata editing for iOS apps. Follow it for a concrete workflow around preparing and comparing store listing text and keywords.
- [RevenueFlo](https://revenueflo.com/) — iOS Dev Tools · iOS Dev Tools: RevenueFlo, ChatLayout, HandySwift — Article · Topics: App Distribution & Store Operations
  **Published:** `2025-03-27T21:08:09.510Z`
  **NeKI brief:** RevenueFlo presents a revenue or subscription analytics workflow for applications. Follow it for concrete monetization reporting ideas, while treating its commercial metrics and recommendations as vendor-specific context.
- [Dock](https://dock-app.com/) — iOS Dev Tools · iOS Dev Tools: Dock, Clippets, ReviewKit — Article · Topics: App Distribution & Store Operations · Developer Career & Practice
  **Published:** `2025-03-20T17:08:58.928Z`
  **NeKI brief:** Dock is a macOS utility that augments or reorganizes the system Dock experience. Follow it for a concrete example of extending desktop navigation, while checking its compatibility and scope on current macOS versions.
- [ReviewKit](https://github.com/FlineDev/ReviewKit) — iOS Dev Tools · iOS Dev Tools: Dock, Clippets, ReviewKit — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **Published:** `2025-03-20T17:08:58.928Z`
  **NeKI brief:** ReviewKit records positive user events and requests an App Store review only when configurable satisfaction criteria are met; events expire after a default window. It is a concrete pattern for making review prompts contextual instead of firing on arbitrary launches.
- [Are subscription trials dead in South Korea? by Rik Haandrikman](https://www.revenuecat.com/blog/growth/south-korea-subscription-rules-2025) — iOS Dev Weekly · Issue 703 — Article · Topics: App Distribution & Store Operations
  **Published:** `14th March 2025`
  **NeKI brief:** Examines Get an in-depth look at South Korea’s new subscription regulations and learn proven strategies for compliance. Includes real RevenueCat trial data, official guidelines from Apple &. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Statused](https://statused.com/) — iOS Dev Tools · iOS Dev Tools: Statused, Compot, FreemiumKit — Article · Topics: App Distribution & Store Operations
  **Published:** `2025-03-06T18:01:47.698Z`
  **NeKI brief:** Statused presents a status-monitoring or status-page workflow. Follow it for concrete incident visibility and notification patterns, while verifying service integrations and operational limits.
- [appstoreconnect-swift-sdk](https://github.com/AvdLee/appstoreconnect-swift-sdk) — iOS CI Newsletter · Issue 62 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Swift
  **Published:** `2025-02-23T00:00:00.000Z`
  **NeKI brief:** Examines this project, focusing on the app store connect api is available and documented! straight away, antoine van der lee jumped into action and started…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Check for new ASC API versions automatically:](https://github.com/AvdLee/appstoreconnect-swift-sdk/blob/master/.github/workflows/sync_asc_api.yml) — iOS CI Newsletter · Issue 62 — Source repository · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **Published:** `2025-02-23T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for Check for new ASC API versions automatically, relevant to App Distribution & Store Operations and CI/CD & Automation. Inspect its implementation, open issues, and release state before adopting the approach.
- [Test on all available platforms:](https://github.com/AvdLee/appstoreconnect-swift-sdk/blob/master/.github/workflows/ci.yml) — iOS CI Newsletter · Issue 62 — Source repository · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **Published:** `2025-02-23T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for Test on all available platforms, relevant to App Distribution & Store Operations and CI/CD & Automation. Inspect its implementation, open issues, and release state before adopting the approach.
- [this](https://www.gamedeveloper.com/business/steam-suddenly-banned-in-vietnam) — iOS Dev Weekly · Issue 699 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `14th February 2025`
  **NeKI brief:** Examines Valve. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Starview](https://indiegoodies.com/starview) — iOS Dev Tools · iOS Dev Tools: Starview, Mint, Giffy — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `2025-02-13T18:15:48.650Z`
  **NeKI brief:** Starview is a developer-oriented utility or product page. Follow it for the concrete workflow it presents, while verifying supported platforms, implementation details, and maintenance before treating it as technical reading.
- [this great conference talk from GodotCon](https://youtu.be/irVRaTj0SGU) — iOS Dev Weekly · Issue 697 — Video · Topics: Developer Community & Business · Graphics, Media & Games · Testing
  **Published:** `31st January 2025`
  **NeKI brief:** Examines Bringing Godot to the iPad has been a fabulous and fun adventure.In this talk I will discuss both the technical challenges imposed by the platform as well as. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [iOS-uploader](https://github.com/simonnilsson/ios-uploader) — iOS Dev Tools · iOS Dev Tools: Swift Bundler, Swift for Visual Studio Code, iOS-uploader — Source repository · Topics: App Distribution & Store Operations · Cross-Platform & Web · Developer Tools
  **Published:** `2025-01-16T21:51:40.196Z`
  **NeKI brief:** A cross-platform command-line uploader for App Store Connect that accepts familiar altool-style arguments and can upload multiple apps concurrently. Its prebuilt binaries and npm installation make it relevant when CI must publish from Windows, Linux, or macOS.
- [iPhone Apps 101 - SwiftUI App Development Course](https://paulsolt.teachable.com/p/iphoneapps101?affcode=1123_hyqyixcy) — SwiftLee Weekly · Issue 254 — Tutorial · Topics: Developer Community & Business · Swift · SwiftUI
  **Published:** `2025-01-14T14:03:25.000Z`
  **NeKI brief:** Introduces iPhone Apps 101 - SwiftUI App Development Course as a developer resource or service relevant to Swift and Apple-platform work. Use it to assess the stated workflow or offering, checking scope, pricing, access requirements, and technical fit before relying on it.
- [Add paywalls in one line of code](https://www.revenuecat.com/docs/tools/paywalls) — iOS Dev Weekly · Issue 693 — Article · Topics: App Distribution & Store Operations · Testing
  **Published:** `3rd January 2025`
  **NeKI brief:** Explains how RevenueCat’s paywall tools let an app configure and present subscription purchase UI with minimal code. Use it to evaluate hosted paywall workflows, entitlement integration, localization, and experimentation requirements before adopting the service.
- [webhooks](https://www.revenuecat.com/docs/integrations/webhooks) — SwiftLee Weekly · Issue 251 — Article · Topics: App Distribution & Store Operations
  **Published:** `2024-12-23T10:34:05.000Z`
  **NeKI brief:** Discusses webhooks, extracting concrete product or engineering practices that help independent Apple-platform developers make informed delivery decisions.
- [How to change your app's business model from paid to freemium using StoreKit](https://www.polpiella.dev/paid-app-to-freemium?ref=createwithswift.com) — Create with Swift · Issue 40 — Article · Topics: App Distribution & Store Operations · Swift
  **Published:** `2024-12-13T16:30:39.000Z`
  **NeKI brief:** Shows changing an app's business model from paid upfront to freemium using StoreKit's AppTransaction API. Follow it when planning migration logic and entitlement checks, then verify transaction semantics, customer communication, and App Store policy requirements.
- [Bagbutik](https://github.com/MortenGregersen/Bagbutik) — iOS Dev Tools · iOS Dev Tools: Wormholy, Bagbutik, Kintsugi — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Swift
  **Published:** `2024-12-12T14:42:27.564Z`
  **NeKI brief:** Provides the source and change history for Bagbutik, relevant to App Distribution & Store Operations and Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [AcceptedSE-0451Raw identifiers](https://github.com/apple/swift-evolution/blob/main/proposals/0451-escaped-identifiers.md) — SwiftLee Weekly · Issue 249 — Source repository · Topics: Developer Tools · Swift
  **Published:** `2024-12-10T13:47:59.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0451Raw identifiers. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [🚀 How to generate authentication tokens for the App Store Connect API using Swift](https://bootstragram.com/blog/jwt-tokens-app-store-connect-api-swift) — iOS CI Newsletter · Issue 56 — Article · Topics: App Distribution & Store Operations · Swift
  **Published:** `2024-12-02T00:00:00.000Z`
  **NeKI brief:** Walks through how to generate authentication tokens for the App Store Connect API using Swift, with practical context for App Distribution & Store Operations and Swift. Use it when implementing the workflow, while checking current tool and platform versions before copying the setup.
- [StatusBuddy](https://github.com/insidegui/StatusBuddy) — iOS Dev Tools · iOS Dev Tools: CoreData Studio, Swift Crypto, StatusBuddy — Source repository · Topics: App Distribution & Store Operations · Developer Tools · macOS & AppKit
  **Published:** `2024-11-28T18:43:21.075Z`
  **NeKI brief:** StatusBuddy monitors or presents macOS system status from a focused utility. Follow its source for concrete status-item and system-integration patterns, while checking current macOS APIs and resource usage.
- [App Store Nominations](https://helm-app.com/changelog/helm-1-4-app-store-nominations-rocketsim) — SwiftLee Weekly · Issue 246 — Article · Topics: App Distribution & Store Operations
  **Published:** `2024-11-19T12:58:52.000Z`
  **NeKI brief:** Discusses App Store Nominations, extracting concrete engineering practices and trade-offs that Apple-platform developers can apply when evaluating this workflow.
- [fastlane match](https://docs.fastlane.tools/actions/match) — iOS CI Newsletter · Issue 55 — Article · Topics: App Distribution & Store Operations · CI/CD & Automation
  **Published:** `2024-11-17T00:00:00.000Z`
  **NeKI brief:** Examines fastlane match in the context of App Distribution & Store Operations and CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Custom Views in UIMenu](https://sebvidal.com/blog/custom-views-in-uimenu?ref=createwithswift.com) — Create with Swift · Issue 34 — Article · Topics: App Distribution & Store Operations · Swift
  **Published:** `2024-11-01T19:30:40.000Z`
  **NeKI brief:** Seb discusses how to use private APIs in UIMenu on iOS, providing code examples for creating interactive custom menu elements and headers. Even if using these undocumented APIs in apps can lead to App Store rejections, this article remains an interesting read.
- [App development on iPad](https://mutatingfunc.github.io/blog/2024-10-12-app-development-on-ipad) — iOS Dev Weekly · Issue 684 — Article · Topics: Developer Tools · Testing
  **Published:** `25th October 2024`
  **NeKI brief:** Presents app development on ipad for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [🚀 A new version of the App Store Connect API is live!](https://github.com/AvdLee/appstoreconnect-swift-sdk/releases/tag/3.5.0) — iOS CI Newsletter · Issue 52 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Swift
  **Published:** `2024-10-06T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for A new version of the App Store Connect API is live!, relevant to App Distribution & Store Operations and Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [Screenshot Master](https://screenshot-master.app/) — iOS Dev Tools · iOS Dev Tools: Screenshot Master, L10nGenie, App Launchpad — Article · Topics: App Distribution & Store Operations
  **Published:** `2024-09-26T13:30:55.613Z`
  **NeKI brief:** Screenshot Master provides tooling for capturing or preparing screenshots. Follow it for concrete image-capture and annotation workflows, while checking output formats and suitability for App Store assets.
- [App Launchpad](https://theapplaunchpad.com/) — iOS Dev Tools · iOS Dev Tools: Screenshot Master, L10nGenie, App Launchpad — Article · Topics: App Distribution & Store Operations
  **Published:** `2024-09-26T13:30:55.613Z`
  **NeKI brief:** App Launchpad presents a service or workflow for launching mobile applications. Follow it for concrete release and marketing process ideas, while treating promotional claims as commercial context.
- [Apple’s App Store terms are still not compliant with the DMA](https://theplatformlaw.blog/2024/09/05/ten-reasons-why-apples-app-store-terms-are-still-not-compliant-with-the-dma) — iOS Dev Weekly · Issue 678 — Article · Topics: App Distribution & Store Operations
  **Published:** `13th September 2024`
  **NeKI brief:** I have no idea if this is true or not, but it sounds like Apple’s hassles with the DMA are far from over. No surprise there, and I expect this to drag on for years.
- [the tragic story](https://www.youtube.com/watch?v=_ueiYhLwwBc) — iOS Dev Weekly · Issue 676 — Video · Topics: AI Development · App Distribution & Store Operations
  **Published:** `30th August 2024`
  **NeKI brief:** Investigates an exposed OpenAI API key that generated a $2,500 bill, covering discovery, architecture, mitigation, and user impact. Useful as a security case study for moving secrets behind a validating server-side proxy.
- [☁️ How to set up Xcode Cloud on your project](https://darrylbayliss.net/getting-setup-with-xcode-cloud) — iOS CI Newsletter · Issue 49 — Article · Topics: App Distribution & Store Operations · CI/CD & Automation · Xcode
  **Published:** `2024-08-25T00:00:00.000Z`
  **NeKI brief:** Walks through how to set up Xcode Cloud on your project, with practical context for App Distribution & Store Operations and CI/CD & Automation. Use it when implementing the workflow, while checking current tool and platform versions before copying the setup.
- [almost](https://en.wikipedia.org/wiki/I_Am_Rich) — iOS Dev Weekly · Issue 673 — Article · Topics: App Distribution & Store Operations
  **Published:** `9th August 2024`
  **NeKI brief:** Examines I Am Rich - Wikipedia. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Looking for an App Center Alternative?](https://bitrise.io/resources/compare/app-center) — iOS Dev Weekly · Issue 672 — Article · Topics: App Distribution & Store Operations · Developer Career & Practice · Testing
  **Published:** `2nd August 2024`
  **NeKI brief:** Bitrise Release Management supports App Store and Google Play releases. Soon, it will also assist you with internal test distribution. Enjoy an automated, transparent, unified solution for managing store releases and test distribution. Use it with Bitrise CI…
- [🏃 Why you need CI/CD as an Indie Dev](https://www.rudrank.com/exploring-indie-life-reducing-friction-by-ci-cd) — iOS CI Newsletter · Issue 47 — Article · Topics: App Distribution & Store Operations · CI/CD & Automation
  **Published:** `2024-07-28T00:00:00.000Z`
  **NeKI brief:** Examines Why you need CI/CD as an Indie Dev in the context of App Distribution & Store Operations and CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Astro](https://tryastro.app/) — iOS Dev Tools · iOS Dev Tools: SemanticDiff, Usage, Astro — Article · Topics: App Distribution & Store Operations
  **Published:** `2024-07-18T14:40:09.750Z`
  **NeKI brief:** Astro is a macOS utility or developer product page. Follow it for the concrete workflow and integration surface described there, while requiring current documentation before adoption.
- [State of in-app subscriptions 2024](https://adapty.io/reports/state-of-in-app-subscriptions-2024) — SwiftUI Weekly · SwiftUI Weekly - Issue #193 — Article · Topics: App Distribution & Store Operations · Swift · SwiftUI
  **Published:** `2024-07-08T08:54:13.719Z`
  **NeKI brief:** Collects current subscription-market benchmarks and growth metrics for mobile apps. Useful for framing pricing, conversion, retention, and monetization decisions with industry data rather than app-level intuition alone.
- [Our App Store screenshot nightmare is (almost) over](https://www.jessesquires.com/blog/2024/07/04/app-store-screenshot-changes) — iOS Dev Weekly · Issue 668 — Article · Topics: App Distribution & Store Operations
  **Published:** `5th July 2024`
  **NeKI brief:** Examines I previously wrote about how the requirements for screenshots on the App Store have become increasingly burdensome over the years. It is truly a nightmare. B. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [📖 A guide to the App Store Connect API](https://www.runway.team/blog/a-hitchhikers-guide-to-the-app-store-connect-api) — iOS CI Newsletter · Issue 45 — Article · Topics: App Distribution & Store Operations · CI/CD & Automation
  **Published:** `2024-07-01T00:00:00.000Z`
  **NeKI brief:** Examines A guide to the App Store Connect API in the context of App Distribution & Store Operations and CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Appfigures - Actionable insights for data-driven mobile growth](https://appfigures.com/) — iOS Dev Tools · iOS Dev Tools: Pricetag, Tuist, Snapshots — Article · Topics: App Distribution & Store Operations
  **Published:** `2024-06-27T16:03:43.649Z`
  **NeKI brief:** Appfigures combines App Store intelligence, ASO tools, and analytics for mobile publishers. Follow it when evaluating data sources for store-performance decisions, keyword research, and growth reporting rather than app-runtime implementation.
- [Pricetag](https://macpricetag.com/) — iOS Dev Tools · iOS Dev Tools: Pricetag, Tuist, Snapshots — Article · Topics: App Distribution & Store Operations
  **Published:** `2024-06-27T16:03:43.649Z`
  **NeKI brief:** Pricetag presents a macOS utility for tracking or displaying app pricing. Follow it for concrete price-monitoring behavior, while verifying data sources and update cadence before relying on it.
- [Helm](https://helm-app.com/) — iOS Dev Tools · iOS Dev Tools: Helm, AudioKit, Lottie — Article · Topics: App Distribution & Store Operations
  **Published:** `2024-06-20T13:30:58.118Z`
  **NeKI brief:** Discusses Helm in a public developer resource. Use it to compare the author's concrete workflow and trade-offs with your project constraints, and verify any platform-specific claims against current primary documentation.
- [💨 Automating manual tasks when creating a version on App Store Connect](https://www.runway.team/blog/apply-promotional-text-and-whats-new-notes-to-new-versions-in-swift-using-the-app-store-connect-api) — iOS CI Newsletter · Issue 44 — Article · Topics: App Distribution & Store Operations · Swift
  **Published:** `2024-06-16T00:00:00.000Z`
  **NeKI brief:** Examines Automating manual tasks when creating a version on App Store Connect in the context of App Distribution & Store Operations and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Hidde van der Ploeg](https://mastodon.design/@hidde) — iOS Dev Weekly · Issue 665 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem
  **Published:** `14th June 2024`
  **NeKI brief:** What a handy page full of example 3D models Apple has provided everyone! Thanks so much to Hidde van der Ploeg for pointing it out!
- [老司机技术](https://github.com/SwiftOldDriver/iOS-Weekly) — Fatbobman’s Swift Weekly · Issue 35 — Source repository · Topics: App Distribution & Store Operations · Apple Platform Ecosystem · Developer Tools
  **Published:** `2024-06-11T12:03:15.731Z`
  **NeKI brief:** Indexes Chinese iOS development reading and project links in a repository-friendly format. Use it as a discovery route for community material, then verify each linked source independently before relying on it.
- [scheduled GitHub actions workflow that checks if a new version of the App Store Connect API’s Open API spec is available](https://github.com/MortenGregersen/Bagbutik/blob/10.3.0/.github/workflows/check-for-new-spec.yml) — iOS CI Newsletter · Issue 43 — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **Published:** `2024-06-02T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for scheduled GitHub actions workflow that checks if a new version of the App Store Connect API’s Open API spec is…, relevant to App Distribution & Store Operations and Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [Screenshot Studio](https://appstorescreenshotstudio.com/) — iOS Dev Tools · iOS Dev Tools: Screenshot Studio, Moya, SkeletonView — Article · Topics: App Distribution & Store Operations
  **Published:** `2024-05-23T13:40:50.650Z`
  **NeKI brief:** Screenshot Studio provides an App Store screenshot-generation workflow for arranging promotional device imagery. Follow it for a concrete storefront-asset production tool, while treating its conversion claims as vendor marketing.
- [AppDab](https://appdab.app/) — iOS Dev Tools · iOS Dev Tools: AppDab, MessageKit, Stats — Article · Topics: App Distribution & Store Operations · Performance · Security & Privacy
  **Published:** `2024-05-16T13:45:55.601Z`
  **NeKI brief:** AppDab is a native App Store Connect client for shipping beta builds, updating screenshots, and submitting apps for review. Its page is a concrete lead for automating recurring distribution tasks outside the web dashboard.
- [Incorrect payments for App Store bundle purchases](https://lapcatsoftware.com/articles/2024/5/2.html) — iOS Dev Weekly · Issue 660 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `10th May 2024`
  **NeKI brief:** Discusses Incorrect payments for App Store bundle purchases, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [🚨 Upcoming App Store Connect upload requirements](https://pol.link/xcode-15-requirements) — iOS CI Newsletter · Issue 40 — Article · Topics: App Distribution & Store Operations · Xcode
  **Published:** `2024-04-21T00:00:00.000Z`
  **NeKI brief:** Examines Upcoming App Store Connect upload requirements in the context of App Distribution & Store Operations and Xcode. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Get started with StoreKit 2 for iOS](https://tanaschita.com/20231002-storekit-2-overview?ref=createwithswift.com) — Create with Swift · Issue 9 — Article · Topics: App Distribution & Store Operations · Swift
  **Published:** `2024-04-19T15:00:58.000Z`
  **NeKI brief:** StoreKit 2 product loading and purchases are introduced through async APIs and verified transactions. Follow it to separate entitlement state from paywall UI and to keep verification on the trusted path.
- [Apple creates all the apps](https://christiantietze.de/posts/2024/03/confuse-app-dev-with-platform) — iOS Dev Weekly · Issue 657 — Article · Topics: App Distribution & Store Operations
  **Published:** `19th April 2024`
  **NeKI brief:** Similarly, subscribing to a Patreon feels different than purchasing on the App Store. Patreon gives people a feeling of supporting a human rather than a faceless corporation, and most people feel better about that. It certainly wouldn’t feel like Apple…
- [ten years](https://rileytestut.com/blog/2024/02/19/happy-10-birthday-gba4ios) — iOS Dev Weekly · Issue 657 — Article · Topics: App Distribution & Store Operations · Security & Privacy · Testing
  **Published:** `19th April 2024`
  **NeKI brief:** Examines 10 years ago today, I released GBA4iOS — a passion project my friend Paul Thorsen and I built during our senior year of high school. I’ve reflected many times over the impact GBA4i. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Prevent Mac App Store Rating Windows from Appearing in the Background](https://furnacecreek.org/blog/2024-04-14-how-to-prevent-background-mac-app-store-rating-windows) — iOS Dev Weekly · Issue 657 — Article · Topics: App Distribution & Store Operations
  **Published:** `19th April 2024`
  **NeKI brief:** I always wondered why this happened! Thanks so much to David Sorel for figuring it out and writing it up!
- [App Store Subscriptions and Family Sharing](https://furbo.org/2024/03/29/app-store-subscriptions-and-family-sharing) — iOS Dev Weekly · Issue 655 — Article · Topics: App Distribution & Store Operations
  **Published:** `5th April 2024`
  **NeKI brief:** Examines Handling family shared in-app subscriptions in the context of App Distribution & Store Operations. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Handling family shared in-app subscriptions](https://furbo.org/2024/03/29/app-store-subscriptions-and-family-sharing?ref=ioscodereview.com) — iOS Code Review · Issue 67 — Article · Topics: App Distribution & Store Operations
  **Published:** `2024-04-03T12:22:37.000Z`
  **NeKI brief:** Examines Handling family shared in-app subscriptions in the context of App Distribution & Store Operations. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [cost in 0024](https://9to5mac.com/2024/03/25/airtag-firmware-error) — iOS Dev Weekly · Issue 654 — Article · Topics: App Distribution & Store Operations
  **Published:** `29th March 2024`
  **NeKI brief:** cost in 0024. This link is retained as a technical reading lead for Apple-platform development.
- [RevenueCat’s attempted definition](https://www.revenuecat.com/blog/growth/am-i-a-trader-and-other-existential-questions-for-developers) — iOS Dev Weekly · Issue 653 — Article · Topics: App Distribution & Store Operations
  **Published:** `22nd March 2024`
  **NeKI brief:** Examines Making sense of App Store Connect's latest change from Apple's DSA compliance. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Visual Studio App Center Retirement](https://learn.microsoft.com/en-us/appcenter/retirement) — iOS Dev Weekly · Issue 653 — Article · Topics: Testing
  **Published:** `22nd March 2024`
  **NeKI brief:** Examines Visual Studio App Center is scheduled for retirement. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [providing support for tracking expenses on Apple payment services](https://techcrunch.com/2024/03/06/apple-releases-a-new-api-to-fetch-transactions-from-apple-card-and-apple-cash?guccounter=2&ref=createwithswift.com) — Create with Swift · Issue 4 — Article · Topics: App Distribution & Store Operations · Swift
  **Published:** `2024-03-15T16:00:42.000Z`
  **NeKI brief:** Also, did you notice that Apple has been releasing updates in many of their services, APIs and technologies this month? From providing support for tracking expenses on Apple payment services with FinanceKit to updates to App Store Connect and also news about…
- [updates to App Store Connect](https://9to5mac.com/2024/03/05/apple-rolls-out-new-analytics-data-for-developers-through-app-store-connect?ref=createwithswift.com) — Create with Swift · Issue 4 — Article · Topics: App Distribution & Store Operations · Swift
  **Published:** `2024-03-15T16:00:42.000Z`
  **NeKI brief:** Also, did you notice that Apple has been releasing updates in many of their services, APIs and technologies this month? From providing support for tracking expenses on Apple payment services with FinanceKit to updates to App Store Connect and also news about…
- [news about the next generation of CarPlay](https://www.macrumors.com/2024/03/13/apple-next-generation-carplay-recap?ref=createwithswift.com) — Create with Swift · Issue 4 — Article · Topics: App Distribution & Store Operations · Swift
  **Published:** `2024-03-15T16:00:42.000Z`
  **NeKI brief:** Also, did you notice that Apple has been releasing updates in many of their services, APIs and technologies this month? From providing support for tracking expenses on Apple payment services with FinanceKit to updates to App Store Connect and also news about…
- [RevenueCat](https://www.revenuecat.com/) — iOS Dev Tools · iOS Dev tools: Play, PullRequest, Sonar — Article · Topics: App Distribution & Store Operations
  **Published:** `2024-03-14T16:08:26.033Z`
  **NeKI brief:** RevenueCat presents a subscription platform for mobile apps, covering purchase infrastructure, entitlement management, and revenue analytics. Use it as a product and integration overview when evaluating recurring monetization, then verify SDK behavior and App Store policy requirements in current documentation.
- [RevenueCat's SDK](https://www.revenuecat.com/docs) — iOS Dev Tools · iOS Dev tools: Play, PullRequest, Sonar — Article · Topics: App Distribution & Store Operations
  **Published:** `2024-03-14T16:08:26.033Z`
  **NeKI brief:** RevenueCat's SDK documentation describes configuring products, purchases, entitlements, and customer subscription state in an app. Follow it when prototyping StoreKit-backed subscriptions, while checking platform versions, receipt behavior, and current App Store rules before shipping.
- [appstoreconnect-swift-sdk](http://github.com/AvdLee/appstoreconnect-swift-sdk) — iOS CI Newsletter · Issue 37 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Swift
  **Published:** `2024-03-10T00:00:00.000Z`
  **NeKI brief:** Examines this project, focusing on the app store connect api is available and documented! straight away, antoine van der lee jumped into action and started…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [I updated this week to include all new changes](https://github.com/AvdLee/appstoreconnect-swift-sdk/pull/262) — iOS CI Newsletter · Issue 37 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Swift
  **Published:** `2024-03-10T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for I updated this week to include all new changes, relevant to App Distribution & Store Operations and Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [Picasso](https://apps.apple.com/us/app/picasso-app-screenshot-tool/id6472062986?platform=mac) — iOS Dev Tools · iOS Dev tools: Picasso, Tasks, Animock — Article · Topics: App Distribution & Store Operations
  **Published:** `2024-03-07T14:52:58.597Z`
  **NeKI brief:** Picasso generates polished App Store screenshots from app captures across iPhone, iPad, and Mac. Its page is a concrete lead for automating promotional-asset composition and presenting product UI consistently across storefront formats.
- [🤩 An unofficial App Store Connect status page](https://www.runway.team/is-app-store-connect-down) — iOS CI Newsletter · Issue 36 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem
  **Published:** `2024-02-25T00:00:00.000Z`
  **NeKI brief:** Examines An unofficial App Store Connect status page in the context of App Distribution & Store Operations and Apple Platform Ecosystem. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🛠 Sponsor - RevenueCat](https://macmenubar.com/) — iOS Dev Tools · iOS Dev tools: Haptics, CodeEdit, Pastepal — Article · Topics: App Distribution & Store Operations
  **Published:** `2024-02-22T14:00:50.078Z`
  **NeKI brief:** This page is a Porkbun sponsor promotion for discounted developer domains. It is advertising rather than technical reading and should normally be excluded from the knowledge index.
- [StoreKit 2 Tutorial with Swift UI](https://superwall.com/blog/make-a-swiftui-app-with-in-app-purchases-and-subscriptions-using-storekit-2) — SwiftUI Weekly · SwiftUI Weekly - Issue #176 — Tutorial · Topics: App Distribution & Store Operations · Swift · SwiftUI
  **Published:** `2024-02-12T08:54:16.360Z`
  **NeKI brief:** Explains With Swift and the new Observation framework, setting up subscriptions for your iOS app is easier than ever. We'll show you how from beginning to end. Useful when implementing this SwiftUI concern and comparing the page's concrete API and layout choices with the requirements of a production interface.
- [Mobile releases are a silent killer, but not with Runway](https://www.runway.team/blog/why-mobile-releases-are-a-silent-killer) — iOS Dev Weekly · Issue 646 — Article · Topics: App Distribution & Store Operations
  **Published:** `2nd February 2024`
  **NeKI brief:** Bouncing back and forth between tools, chasing down marketing for copy and stakeholders for sign-offs, clicking around gingerly in App Store Connect… productivity, happiness, and general sanity suffer. Learn what makes mobile releases a silent killer and how…
- [visionOS App Roundup](https://vision.rodeo/app-roundup-1) — iOS Dev Weekly · Issue 646 — Article · Topics: App Distribution & Store Operations
  **Published:** `2nd February 2024`
  **NeKI brief:** The article rounds up visionOS applications and discusses concrete examples of software available for Apple's spatial-computing platform.
- [Google document with more than 230 apps listed](https://docs.google.com/spreadsheets/d/1Kbkm_jPdgV2qwhoRFIufCass8u2k-h4Xxuj0r7tXYZo/edit?pli=1) — iOS Dev Weekly · Issue 646 — Article · Topics: App Distribution & Store Operations
  **Published:** `2nd February 2024`
  **NeKI brief:** The publicly readable spreadsheet contains a curated list of more than 230 apps, serving as a concrete reference catalogue for developers.
- [excellent summary of the announcement and reactions](https://mjtsai.com/blog/2024/01/18/storekit-purchase-link-entitlement-for-united-states) — iOS Dev Weekly · Issue 644 — Article · Topics: App Distribution & Store Operations
  **Published:** `19th January 2024`
  **NeKI brief:** Presents excellent summary of the announcement and reactions, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [📝 Platform-specific release notes with Xcode Cloud](https://www.finnvoorhees.com/words/platform-specific-release-notes-with-xcode-cloud) — iOS CI Newsletter · Issue 33 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem · Xcode
  **Published:** `2024-01-14T00:00:00.000Z`
  **NeKI brief:** Summarises Platform-specific release notes with Xcode Cloud for App Distribution & Store Operations and Apple Platform Ecosystem. Use it to identify the relevant changes and follow its primary links before relying on version-sensitive details.
- [Add paywalls in one line of code](https://www.revenuecat.com/docs/paywalls) — iOS Dev Weekly · Issue 640 — Article · Topics: App Distribution & Store Operations · Testing
  **Published:** `15th December 2023`
  **NeKI brief:** RevenueCat documentation for configuring and presenting in-app paywalls through its SDK and dashboard tooling. Use it when evaluating a subscription implementation, validating entitlement flow choices, or integrating RevenueCat's paywall APIs into an Apple-platform app.
- [How to ask the user to leave an App Store review](https://www.youtube.com/watch?v=RUWGjeDCkN8) — SwiftUI Weekly · SwiftUI Weekly - Issue #170 — Video · Topics: App Distribution & Store Operations · Graphics, Media & Games · Objective-C & Cocoa
  **Published:** `2023-12-11T13:23:19.560Z`
  **NeKI brief:** Shows how to request App Store ratings from an app and frame the timing around user experience. Useful for integrating review prompts deliberately while keeping eligibility, frequency, and platform presentation behavior under app control.
- [Get started for free 🚀](https://keyboardkit.com/pro?ref=ioscodereview.com) — iOS Code Review · Issue 60 — Article · Topics: App Distribution & Store Operations · Developer Career & Practice · Hardware & Devices
  **Published:** `2023-11-23T12:38:53.000Z`
  **NeKI brief:** Examines Get started for free 🚀 in the context of App Distribution & Store Operations and Developer Career & Practice. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [EmojiKit](https://kankoda.com/emojikit?ref=ioscodereview.com) — iOS Code Review · Issue 60 — Article · Topics: App Distribution & Store Operations · Developer Career & Practice
  **Published:** `2023-11-23T12:38:53.000Z`
  **NeKI brief:** Examines EmojiKit in the context of App Distribution & Store Operations and Developer Career & Practice. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [LicenseKit](https://kankoda.com/licensekit?ref=ioscodereview.com) — iOS Code Review · Issue 60 — Article · Topics: App Distribution & Store Operations · Developer Career & Practice
  **Published:** `2023-11-23T12:38:53.000Z`
  **NeKI brief:** Examines LicenseKit in the context of App Distribution & Store Operations and Developer Career & Practice. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [PEP 730 – Adding iOS as a supported platform](https://peps.python.org/pep-0730) — Fatbobman’s Swift Weekly · Issue 6 — Article · Topics: App Distribution & Store Operations · Architecture · Objective-C & Cocoa
  **Published:** `2023-11-13T22:20:44.462Z`
  **NeKI brief:** PEP 730 proposes adding iOS as a supported Python platform and outlines packaging and runtime considerations. Follow it when evaluating Python components in an iOS toolchain, distinguishing language support from native framework and App Store constraints.
- [ASO](https://aso.2stable.com/) — iOS Dev Tools · 🔨 ASO, ToDoBar, EffectsLibrary — Article · Topics: App Distribution & Store Operations
  **Published:** `2023-11-09T14:17:10.440Z`
  **NeKI brief:** ASO by 2Stable presents app and game App Store Optimization tools. Use it as a concrete metadata-research lead for store visibility, not as a source of normative Apple platform behavior.
- [Swift, meet WinRT](https://speakinginswift.substack.com/p/swift-meet-winrt) — Fatbobman’s Swift Weekly · Issue 5 — Article · Topics: App Distribution & Store Operations · Swift
  **Published:** `2023-11-06T22:30:15.675Z`
  **NeKI brief:** Introduces Swift interoperation with Windows Runtime and the ABI concerns behind projecting WinRT APIs. Use it to understand cross-platform binding work and the boundary between generated Swift interfaces and platform-specific runtime contracts.
- [Creating Shortcuts with App Intents](https://www.kodeco.com/40950083-creating-shortcuts-with-app-intents) — Fatbobman’s Swift Weekly · Issue 5 — Article · Topics: App Distribution & Store Operations · App Intents & System Surfaces · Combine & Reactive Programming
  **Published:** `2023-11-06T22:30:15.675Z`
  **NeKI brief:** Explains creating Shortcuts actions with App Intents and connecting typed app operations to system automation. Use it when exposing discoverable actions while checking entity modeling, parameter resolution, availability, and privacy boundaries.
- [On Launching your Indie App: Part 1](https://www.swiftjectivec.com/on-launching-your-indie-app) — Fatbobman’s Swift Weekly · Issue 3 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games · Swift
  **Published:** `2023-10-23T22:30:20.902Z`
  **NeKI brief:** Reflects on launching an independent app, including product scope, marketing, and release realities. Use it as practitioner context when planning an indie product beyond implementation alone.
- [Debugging Your Way to App Store Success With Instabug](https://www.instabug.com/product/app-ratings-reviews) — iOS Dev Weekly · Issue 632 — Article · Topics: App Distribution & Store Operations · Developer Tools
  **Published:** `20th October 2023`
  **NeKI brief:** Examines Luciq Platform | One SDK. Every signal. Every agent.. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Minify ASO](https://apps.apple.com/us/app/minify-aso-duplicate-keywords/id1660632226) — iOS Dev Tools · 🔨 Introducing Bezel, Minify ASO, LaunchBuddy — Article · Topics: App Distribution & Store Operations
  **Published:** `2023-10-19T14:30:17.945Z`
  **NeKI brief:** MinifyASO removes duplicate keywords, stop words, and plural suffixes to make App Store Optimization terms fit more efficiently. Follow it for a concrete metadata-cleanup workflow, while treating keyword advice as marketing context rather than Apple Search Ads guidance.
- [Quinn “The Eskimo!”](https://toot.community/@justkwin) — iOS Dev Weekly · Issue 631 — Article · Topics: App Distribution & Store Operations · Developer Community & Business
  **Published:** `13th October 2023`
  **NeKI brief:** In one way, this article by Nikita Zhuk contains some valuable advice on whether you should subclass URLCache. In another, it’s a reminder of the amazing work that Quinn and other DTS team members and Apple employees do on the developer forums. It’s easy to…
- [Statused](https://statused.com/?=iosdevtools) — iOS Dev Tools · Introducing RemafoX, Statused, I18n Studio — Article · Topics: App Distribution & Store Operations · Testing
  **Published:** `2023-09-21T12:20:19.663Z`
  **NeKI brief:** This Statused URL is the same status-monitoring resource with a newsletter query parameter. Follow the canonical page for concrete incident-visibility behavior; the query variant adds no separate technical content.
- [AspirinShot](https://github.com/goodwhale/AspirinShot) — iOS Dev Tools · Introducing iOS Security Suite, AspirinShot, Arkana — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Swift
  **Published:** `2023-09-14T12:30:13.346Z`
  **NeKI brief:** AspirinShot is a GitHub project for capturing or processing screenshots. Follow its README and source for concrete image-capture and output behavior, while checking supported platforms and automation constraints.
- [✅ Get ASC app status updates on Slack](https://www.roger.ml/p/launching-statused) — iOS CI Newsletter · Issue 24 — Article · Topics: App Distribution & Store Operations · CI/CD & Automation
  **Published:** `2023-09-10T00:00:00.000Z`
  **NeKI brief:** Examines Get ASC app status updates on Slack in the context of App Distribution & Store Operations and CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [🧰 SDKs and Xcode’s version management](https://alexanderweiss.dev/blog/2023-07-04-appstore-connect-manage-app-version-and-build-number) — iOS CI Newsletter · Issue 20 — Article · Topics: App Distribution & Store Operations · Developer Career & Practice · Xcode
  **Published:** `2023-07-16T00:00:00.000Z`
  **NeKI brief:** Examines Beware of Xcode's automatic version management in the context of App Distribution & Store Operations and Developer Career & Practice. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [highlight this PR](https://github.com/fastlane/fastlane/pull/20956) — iOS CI Newsletter · Issue 20 — Source repository · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **Published:** `2023-07-16T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for highlight this PR, relevant to App Distribution & Store Operations and CI/CD & Automation. Inspect its implementation, open issues, and release state before adopting the approach.
- [Beware of Xcode's automatic version management](https://alexanderweiss.dev/blog/2023-07-04-appstore-connect-manage-app-version-and-build-number?ref=ioscodereview.com) — iOS Code Review · Issue 52 — Article · Topics: App Distribution & Store Operations · Developer Career & Practice · Xcode
  **Published:** `2023-07-06T18:35:01.000Z`
  **NeKI brief:** Examines Beware of Xcode's automatic version management in the context of App Distribution & Store Operations and Developer Career & Practice. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [In-app purchase updates from WWDC](https://www.revenuecat.com/blog/engineering/wwdc2023-highlights) — iOS Dev Weekly · Issue 615 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `23rd June 2023`
  **NeKI brief:** Examines RevenueCat developer advocate Charlie Chapman shares his first impressions from WWDC 2023, focusing on subscriptions, monetisations, and more. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [📱 Comparing build distribution services](https://www.runway.team/blog/comparing-the-top-pre-production-and-beta-app-distribution-tools) — iOS CI Newsletter · Issue 18 — Article · Topics: Testing
  **Published:** `2023-06-18T00:00:00.000Z`
  **NeKI brief:** Examines Comparing build distribution services in the context of Testing. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [available for free on the WWDCNotes site](https://www.wwdcnotes.com/notes/wwdc23/10117) — iOS CI Newsletter · Issue 17 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem
  **Published:** `2023-06-11T00:00:00.000Z`
  **NeKI brief:** Summarises available for free on the WWDCNotes site for App Distribution & Store Operations and Apple Platform Ecosystem. Use it to identify the relevant changes and follow its primary links before relying on version-sensitive details.
- [Glassfy](https://eu1.hubs.ly/H01-5vC0) — SwiftUI Weekly · SwiftUI Weekly - Issue #144 — Article · Topics: App Distribution & Store Operations · Developer Career & Practice · Swift
  **Published:** `2023-05-29T23:10:25.571Z`
  **NeKI brief:** Links to Glassfy's service for managing in-app purchases, paywalls, and backend subscription work. Useful as a product integration lead when comparing hosted monetization infrastructure, SDK coverage, and vendor dependency against StoreKit-first designs.
- [Your WWDC Insurance Policy](https://www.revenuecat.com/docs/migrating-existing-subscriptions) — iOS Dev Weekly · Issue 607 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem
  **Published:** `28th April 2023`
  **NeKI brief:** Examines Importing existing purchase data to RevenueCat can be done server-side, or client-side. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [YOLO (You Only Launch Once)](https://chriswu.com/posts/appstore/yolo) — iOS Dev Weekly · Issue 607 — Article · Topics: App Distribution & Store Operations
  **Published:** `28th April 2023`
  **NeKI brief:** It’s easy to forget about app preorders when you’re getting everything in line for a new app launch, but as Chris Wu shows in this launch postmortem, they can give you hundreds of downloads on day one as an indie developer. That’s a great head start over…
- [Phased Releases](https://dev.shoppingukapp.com/2023/04/12/phased-releases.html) — iOS Dev Weekly · Issue 605 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `14th April 2023`
  **NeKI brief:** Examines Dip your toe in the water. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Live App Store & TestFlight review times from Runway](https://www.runway.team/appreviewtimes) — iOS Dev Weekly · Issue 604 — Article · Topics: App Distribution & Store Operations · Testing
  **Published:** `7th April 2023`
  **NeKI brief:** Explores Live App Store & TestFlight review times from Runway, focusing on get a pulse check on current average review times, beta. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [App Store Quirks](https://github.com/tramlinehq/store-quirks) — iOS Dev Weekly · Issue 602 — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **Published:** `24th March 2023`
  **NeKI brief:** The GitHub repository documents App Store quirks and edge cases that developers may encounter when shipping applications.
- [version 1.3.0](https://github.com/RobotsAndPencils/xcodes/releases/tag/1.3.0) — iOS CI Newsletter · Issue 11 — Source repository · Topics: App Distribution & Store Operations · CI/CD & Automation · Xcode
  **Published:** `2023-03-12T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for version 1.3.0, relevant to App Distribution & Store Operations and CI/CD & Automation. Inspect its implementation, open issues, and release state before adopting the approach.
- [Wonderous: Build Wonders with Flutter](https://flutter.gskinner.com/wonderous) — iOS Dev Weekly · Issue 598 — Article · Topics: Accessibility · App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `24th February 2023`
  **NeKI brief:** Explores Wonderous: Build Wonders with Flutter, focusing on wonderous is an open-source ios app built with flutter. it. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Flutter](https://flutter.dev/multi-platform/mobile) — iOS Dev Weekly · Issue 598 — Article · Topics: Accessibility · App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `24th February 2023`
  **NeKI brief:** Explores Flutter, focusing on wonderous is an open-source ios app built with flutter. it features award-winning ux design and best practices for performance and accessibility. see. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [State of Subscription Apps 2023](https://www.revenuecat.com/state-of-subscription-apps-2023) — iOS Dev Weekly · Issue 596 — Article · Topics: App Distribution & Store Operations
  **Published:** `10th February 2023`
  **NeKI brief:** RevenueCat’s annual report shares aggregated data from over 22,000 subscription apps. See how you stack up against the competition and improve your app business with actionable insights, never-before-seen benchmarks, and tips from industry experts.
- [30,000 lines of SwiftUI in production later: We love it but you know there was going to be a “but”](https://blog.timing.is/swiftui-production-experience-problems-solutions-performance-tips) — SwiftUI Weekly · SwiftUI Weekly - Issue #129 — Article · Topics: App Distribution & Store Operations · Swift · SwiftUI
  **Published:** `2023-01-30T11:20:24.661Z`
  **NeKI brief:** Reports production SwiftUI performance problems and the remedies used to diagnose them. Useful as a field-tested checklist for investigating rendering cost, navigation behavior, and architectural friction beyond small sample projects.
- [Code signing and XCFrameworks](https://mtldoc.com/swift/2022/12/23/xcframework-code-signing) — iOS CI Newsletter · Issue 6 — Article · Topics: App Distribution & Store Operations · Swift · Systems Programming
  **Published:** `2023-01-01T00:00:00.000Z`
  **NeKI brief:** Examines Code signing and XCFrameworks in the context of App Distribution & Store Operations and Swift. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Code signing and provisioning explained](https://tanaschita.com/20221212-code-signing-and-provisioning-for-ios) — iOS CI Newsletter · Issue 5 — Article · Topics: App Distribution & Store Operations
  **Published:** `2022-12-18T00:00:00.000Z`
  **NeKI brief:** Code signing and provisioning connect certificates, profiles, entitlements and bundle identifiers. The guide is useful for diagnosing build and distribution failures by separating identity, capability and installation concerns.
- [Working around simctrl not working on iOS 16 simulators](https://www.jessesquires.com/blog/2022/12/14/simctrl-status_bar-broken) — iOS Dev Weekly · Issue 589 — Article · Topics: App Distribution & Store Operations
  **Published:** `16th December 2022`
  **NeKI brief:** Examines Xcode 11 shipped with simctl status_bar, a tool to override the status bar values in the simulator so you can take perfect screenshots. I’ve written about th. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [iOS In-App Subscription Tutorial with StoreKit 2 and Swift](https://www.revenuecat.com/blog/engineering/ios-in-app-subscription-tutorial-with-storekit-2-and-swift) — iOS Dev Weekly · Issue 589 — Tutorial · Topics: App Distribution & Store Operations · Swift
  **Published:** `16th December 2022`
  **NeKI brief:** There are several things to mention about this StoreKit post from Josh Holtz. First, it’s on the RevenueCat blog but it doesn’t use their service. It covers implementing StoreKit subscriptions using only Apple’s APIs. Secondly, it’s comprehensive, with over…
- [companion GitHub repository](https://github.com/RevenueCat/storekit2-demo-app) — iOS Dev Weekly · Issue 589 — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **Published:** `16th December 2022`
  **NeKI brief:** There are several things to mention about this StoreKit post from Josh Holtz. First, it’s on the RevenueCat blog but it doesn’t use their service. It covers implementing StoreKit subscriptions using only Apple’s APIs. Secondly, it’s comprehensive, with over…
- [Walk the Line: iOS Account Deletion](https://steamclock.com/blog/2022/12/ios-account-deletion) — iOS Dev Weekly · Issue 589 — Article · Topics: App Distribution & Store Operations · Testing
  **Published:** `16th December 2022`
  **NeKI brief:** I enjoyed every word of this post from Nick Wilkinson on the new account deletion rule and how tricky it is for both developers and the App Store review team. During the latest “Ask Apple” event, he put some questions to the review team, then kindly took the…
- [launch blog post](https://trycombine.com/posts/datatile-for-simulator-public-beta-on-testflight-now) — iOS Dev Weekly · Issue 587 — Article · Topics: App Distribution & Store Operations · Combine & Reactive Programming · Developer Tools
  **Published:** `2nd December 2022`
  **NeKI brief:** Explores launch blog post, focusing on the article discusses don’t know about you, but i still. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Fixing code signing issues on Xcode 14](https://blog.codemagic.io/code-signing-issues-in-xcode-14-and-how-to-fix-them) — iOS CI Newsletter · Issue 3 — Article · Topics: App Distribution & Store Operations · Xcode
  **Published:** `2022-11-20T00:00:00.000Z`
  **NeKI brief:** Examines Fixing code signing issues on Xcode 14 in the context of App Distribution & Store Operations and Xcode. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Making App Store Connect better](https://lapcatsoftware.com/articles/crappstoreconnect2.html) — iOS CI Newsletter · Issue 3 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `2022-11-20T00:00:00.000Z`
  **NeKI brief:** Examines Making App Store Connect better in the context of App Distribution & Store Operations and Cross-Platform & Web. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [a pretty neat browser extension](https://github.com/lapcat/AppStoreConnect) — iOS CI Newsletter · Issue 3 — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **Published:** `2022-11-20T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for a pretty neat browser extension, relevant to App Distribution & Store Operations and Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [Morflax Mockup Builder](https://studio.morflax.com/things) — iOS Dev Weekly · Issue 585 — Article · Topics: App Distribution & Store Operations
  **Published:** `18th November 2022`
  **NeKI brief:** I’ve linked to several tools to help create App Store screenshots over the years. Some are downloadable apps, and some are web-based. Some work in 2D, and some let you position device mockups in 3D. This one has a feature I’ve not seen before, 3D device…
- [How to regenerate Xcode managed provisioning profiles](https://lapcatsoftware.com/articles/provisioning.html) — iOS CI Newsletter · Issue 2 — Article · Topics: App Distribution & Store Operations · Performance · Xcode
  **Published:** `2022-11-06T00:00:00.000Z`
  **NeKI brief:** Walks through how to regenerate Xcode managed provisioning profiles, with practical context for App Distribution & Store Operations and Performance. Use it when implementing the workflow, while checking current tool and platform versions before copying the setup.
- [uproar or quick course correction](https://www.macrumors.com/2022/10/26/app-store-gambling-ads-complaints) — iOS Dev Weekly · Issue 583 — Tutorial · Topics: App Distribution & Store Operations · Developer Community & Business · Objective-C & Cocoa
  **Published:** `4th November 2022`
  **NeKI brief:** Discusses uproar or quick course correction, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [full diff](http://www.appstorereviewguidelineshistory.com/articles/2022-10-25) — iOS Dev Weekly · Issue 582 — Article · Topics: App Distribution & Store Operations
  **Published:** `28th October 2022`
  **NeKI brief:** Examines App Review clarification, new harmful content rule and info about Matter and selling NFTs - App Store Review Guidelines History. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Update fastlane on your CI! 🚀](https://github.com/fastlane/fastlane/releases/tag/2.210.0) — iOS CI Newsletter · Issue 1 — Source repository · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **Published:** `2022-10-23T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for Update fastlane on your CI! 🚀, relevant to App Distribution & Store Operations and CI/CD & Automation. Inspect its implementation, open issues, and release state before adopting the approach.
- [deliver](https://docs.fastlane.tools/actions/deliver) — iOS CI Newsletter · Issue 1 — Article · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **Published:** `2022-10-23T00:00:00.000Z`
  **NeKI brief:** Examines deliver in the context of App Distribution & Store Operations and CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [pilot](http://docs.fastlane.tools/actions/pilot) — iOS CI Newsletter · Issue 1 — Article · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **Published:** `2022-10-23T00:00:00.000Z`
  **NeKI brief:** Examines pilot in the context of App Distribution & Store Operations and CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [iTMSTransporter command line tool](https://github.com/fastlane/fastlane/issues/20371) — iOS CI Newsletter · Issue 1 — Source repository · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **Published:** `2022-10-23T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for iTMSTransporter command line tool, relevant to App Distribution & Store Operations and CI/CD & Automation. Inspect its implementation, open issues, and release state before adopting the approach.
- [Mac App Store and investing engineering time](https://blog.kaleidoscope.app/2022/09/07/mac-app-store-and-investing-engineering-time) — iOS Dev Weekly · Issue 576 — Article · Topics: App Distribution & Store Operations
  **Published:** `16th September 2022`
  **NeKI brief:** Examines Today I’d like to share some insight in what I consider a mistake I made in investing our engineering time. Running a business is hard, and there aren’t always perfect solutions or. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [iOS App Security: Is it really better than Android?](https://www.guardsquare.com/is-ios-app-security-really-better-than-android) — iOS Dev Weekly · Issue 574 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web · Security & Privacy
  **Published:** `2nd September 2022`
  **NeKI brief:** Examines Is iOS really more secure than Android? Here’s what you need to know about iOS mobile app security. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [How to get featured on the App Store](https://nemecek.be/blog/169/how-to-get-featured-on-the-app-store) — iOS Dev Weekly · Issue 573 — Article · Topics: App Distribution & Store Operations
  **Published:** `26th August 2022`
  **NeKI brief:** There was one point that came up over and over in this set of short interviews by Filip Němeček talking about submitting your app for consideration by the App Store editorial team:
- [Does Apple Keep its Commission After You Refund a Purchase?](https://www.revenuecat.com/blog/does-apple-keep-its-commission) — iOS Dev Weekly · Issue 572 — Article · Topics: App Distribution & Store Operations
  **Published:** `19th August 2022`
  **NeKI brief:** Examines Here’s an interesting question that seems to resurface periodically: What happens to Apple’s commission after a user gets a refund for an in-app purchase?. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [An Open Source Implementation of Code Signing and Notarization](https://gregoryszorc.com/blog/2022/08/08/achieving-a-completely-open-source-implementation-of-apple-code-signing-and-notarization) — iOS Dev Weekly · Issue 571 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem · Developer Community & Business
  **Published:** `12th August 2022`
  **NeKI brief:** The page covers “An Open Source Implementation of Code Signing and Notarization” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [PyOxidizer](https://github.com/indygreg/PyOxidizer) — iOS Dev Weekly · Issue 571 — Source repository · Topics: App Distribution & Store Operations · Apple Platform Ecosystem · Developer Community & Business
  **Published:** `12th August 2022`
  **NeKI brief:** It wasn’t a huge announcement from this year’s WWDC, but the Notary API was a big deal for some sections of this community. Here’s Gregory Szorc talking about Robin Lambertz’s pull request to PyOxidizer that allows code signing and notarization from Linux. 👍
- [App Store SEO Shenanigans](https://daringfireball.net/2022/08/dropbox_cloud_photo_storage) — iOS Dev Weekly · Issue 571 — Article · Topics: App Distribution & Store Operations
  **Published:** `12th August 2022`
  **NeKI brief:** Examines The App Store should *discourage* SEO nonsense like keyword spamming, not reward it. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Requesting App Store reviews in SwiftUI](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL25pbGNvYWxlc2NpbmcuY29tL2Jsb2cvUmVxdWVzdGluZ0FwcFN0b3JlUmV2aWV3c0luU3dpZnRVSS8_dXRtX2NhbXBhaWduPSUyMFN3aWZ0VUklMjBXZWVrbHkmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPVJldnVlJTIwbmV3c2xldHRlciIsInBvc3RfaWQiOiJlOGMyZGIwMC05Y2NjLTRkOWItYmI5Ni1kMWU2MDU3NjFhOTciLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiY2E4YjI1ODQtMmEzYy00OWQ1LThlNzktNTM1NjdlNDI1OTY2IiwiaWF0IjoxNjc0MDYyNTU4Ljg3MywiaXNzIjoib3JjaGlkIn0.gpPrkF9rQIPK1vqfb0AZ1jFSBMP_sLOCzneScAJ-voM) — SwiftUI Weekly · SwiftUI Weekly - Issue #107 — Article · Topics: App Distribution & Store Operations · Swift · SwiftUI
  **Published:** `2022-06-21T10:41:22.000Z`
  **NeKI brief:** Shows how to trigger App Store review requests from SwiftUI while respecting the system-controlled presentation. Useful for choosing a meaningful in-app moment and avoiding repeated or disruptive prompts.
- [fastlane](https://docs.fastlane.tools/getting-started/ios/screenshots) — iOS Dev Weekly · Issue 562 — Article · Topics: App Distribution & Store Operations · CI/CD & Automation
  **Published:** `10th June 2022`
  **NeKI brief:** Examines a tool like fastlane in the context of CI/CD & Automation. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [When to remove your iOS app from the App Store](https://benoitpasquier.com/remove-ios-app-from-app-store) — iOS Dev Weekly · Issue 558 — Article · Topics: App Distribution & Store Operations
  **Published:** `13th May 2022`
  **NeKI brief:** This post from Benoit Pasquier is honest, humble, and refreshing to read. He talks about the realities of working on multiple projects and might give you a new perspective on some of your apps or side projects.
- [Are alternative app stores worth it?](https://www.apptamin.com/blog/are-alternative-app-stores-worth-it) — iOS Dev Weekly · Issue 557 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `6th May 2022`
  **NeKI brief:** Examines With the looming DMA and Open Markets Acts that aim to open the app markets to alternative app stores, their time to shine may be just around the corner. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [in-App Purchases in Swift Playgrounds on the iPad](https://www.cephalopod.studio/blog/making-money-by-developing-apps-on-ipads-swift-playgrounds-the-code-part-) — iOS Dev Weekly · Issue 555 — Article · Topics: App Distribution & Store Operations · Swift
  **Published:** `22nd April 2022`
  **NeKI brief:** I love that Matt Waller is really digging into creating apps with Swift Playgrounds on iPad. In this post, he tackles IAPs.
- [read this post](https://tidbits.com/2022/04/08/apples-app-store-stubbornness-may-be-ioss-greatest-security-vulnerability) — iOS Dev Weekly · Issue 554 — Article · Topics: App Distribution & Store Operations · Security & Privacy · Testing
  **Published:** `15th April 2022`
  **NeKI brief:** Examines Apple’s App Store helped make iPads and iPhones the most secure consumer-focused computers ever created. But Apple’s opaque policy enforcement and payment restrictions are now moti. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [spoke publicly at the IAPP Summit](https://youtu.be/Dq0fcmmzfog?t=855) — iOS Dev Weekly · Issue 554 — Video · Topics: App Distribution & Store Operations · Security & Privacy
  **Published:** `15th April 2022`
  **NeKI brief:** Tim Cook also spoke publicly at the IAPP Summit this week about privacy, the iOS platform, and the App Store. If you didn’t catch it, you won’t be surprised to hear that he is also very much in favour of keeping things the way they are now, with the App…
- [we’ve had confirmation from Apple](https://techcrunch.com/2022/04/05/apple-pilot-tests-feature-that-allows-developers-to-automatically-charge-users-for-subscription-price-increases) — iOS Dev Weekly · Issue 553 — Article · Topics: App Distribution & Store Operations · Testing
  **Published:** `8th April 2022`
  **NeKI brief:** Last week, the custom, automated subscription change people saw in Disney+ was surrounded by speculation. This week, we’ve had confirmation from Apple via Sarah Perez at TechCrunch:
- [code generation run via a GitHub Action](https://github.com/MortenGregersen/Bagbutik/actions/workflows/check-for-new-spec.yml) — iOS Dev Weekly · Issue 551 — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **Published:** `25th March 2022`
  **NeKI brief:** This new package from Morten Gregersen is worth a look for two reasons. First, it’s an API client library for the App Store Connect API, and that’s always useful. However, what makes it unique is that it’s powered by code generation run via a GitHub Action…
- [Should you use App Bundles for upgrade pricing?](https://blog.kaleidoscope.app/2022/03/11/app-bundles) — iOS Dev Weekly · Issue 549 — Article · Topics: App Distribution & Store Operations · Personal Essays
  **Published:** `11th March 2022`
  **NeKI brief:** Discusses Should you use App Bundles for upgrade pricing?, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [The App Store has a ‘Too Big To Fail’ problem](https://mobiledevmemo.com/app-store-too-big-to-fail) — iOS Dev Weekly · Issue 546 — Article · Topics: App Distribution & Store Operations
  **Published:** `18th February 2022`
  **NeKI brief:** Examines The App Store has a 'Too Big To Fail' problem. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [watchOS App Store](https://support.apple.com/en-gb/HT204784) — iOS Dev Weekly · Issue 543 — Article · Topics: App Distribution & Store Operations
  **Published:** `28th January 2022`
  **NeKI brief:** First, this is a cool distribution technology, but if 3rd party watch faces ever become a thing, they won’t roll out like this. We already have a watchOS App Store.
- [The 3 best business models for a consumer company](https://www.mronge.com/the-3-best-business-models-for-a-consumer-company) — iOS Dev Weekly · Issue 543 — Article · Topics: App Distribution & Store Operations
  **Published:** `28th January 2022`
  **NeKI brief:** Presents The 3 best business models for a consumer company, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [GitHub - russell-archer/StoreHelper](https://github.com/russell-archer/StoreHelper?ref=ioscodereview.com) — iOS Code Review · Issue 14 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Testing
  **Published:** `2022-01-13T12:22:06.000Z`
  **NeKI brief:** Provides the source and change history for GitHub - russell-archer/StoreHelper, relevant to Developer Tools and Objective-C & Cocoa. Inspect its implementation, open issues, and release state before adopting the approach.
- [GitHub - russell-archer/IAPDemo](https://github.com/russell-archer/IAPDemo?ref=ioscodereview.com) — iOS Code Review · Issue 14 — Source repository · Topics: Developer Tools · Objective-C & Cocoa · Testing
  **Published:** `2022-01-13T12:22:06.000Z`
  **NeKI brief:** Provides the source and change history for GitHub - russell-archer/IAPDemo, relevant to Developer Tools and Objective-C & Cocoa. Inspect its implementation, open issues, and release state before adopting the approach.
- [Xcodes](https://github.com/RobotsAndPencils/XcodesApp) — iOS Dev Weekly · Issue 538 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Xcode
  **Published:** `17th December 2021`
  **NeKI brief:** Explores Xcodes.app, focusing on the last time i mentioned xcodes, i was still using xcinfo. that changed recently with some fantastic improvements to xcodes.app. especially in. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [What apps are we missing out on?](https://www.revenuecat.com/blog/what-apps-are-we-missing-out-on) — iOS Dev Weekly · Issue 536 — Article · Topics: App Distribution & Store Operations
  **Published:** `3rd December 2021`
  **NeKI brief:** Examines One of the biggest downsides of in-app purchase (IAP) restrictions is that many apps simply never get created. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [how not to screw up switching your app to subscriptions](https://www.mronge.com/how-not-to-screw-up-when-switching-your-app-to-subscriptions) — iOS Dev Weekly · Issue 534 — Article · Topics: App Distribution & Store Operations
  **Published:** `19th November 2021`
  **NeKI brief:** I’m writing about this now for two reasons. First, Matt Ronge wrote a fantastic post telling you how not to screw up switching your app to subscriptions. The best thing about this article is how simple the three points are. Apple should open this post every…
- [How to solve any iOS crash](https://swiftrocks.com/how-to-solve-any-ios-crash-ever) — iOS Dev Weekly · Issue 532 — Article · Topics: App Distribution & Store Operations · Swift
  **Published:** `5th November 2021`
  **NeKI brief:** I’d add one last item to this great list of tips from Bruno Rocha on how to find crashes in your app. Make sure you’re on the exact revision of code that you submitted to the App Store. Even trivial changes you’ve made since the build you submitted can make…
- [Evolving our business model to address developer needs](https://android-developers.googleblog.com/2021/10/evolving-business-model.html) — iOS Dev Weekly · Issue 530 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `22nd October 2021`
  **NeKI brief:** Examines Android Developers Blog: Evolving our business model to address developer needs. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [announced in March](https://android-developers.googleblog.com/2021/03/boosting-dev-success.html) — iOS Dev Weekly · Issue 530 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `22nd October 2021`
  **NeKI brief:** Examines Android Developers Blog: Boosting developer success on Google Play. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Paddle’s “In-App Purchase” system](https://paddle.com/platform/in-app-purchase) — iOS Dev Weekly · Issue 528 — Article · Topics: App Distribution & Store Operations
  **Published:** `8th October 2021`
  **NeKI brief:** Describes Paddle’s in-app-purchase platform and its positioning around payment, subscription, and tax workflows. Useful for comparing monetization infrastructure options, while verifying platform capabilities and App Store policy requirements independently.
- [Automating App Store Screenshots](https://lickability.com/blog/automating-app-store-screenshots-with-fastlane-and-swiftui) — iOS Dev Weekly · Issue 519 — Article · Topics: App Distribution & Store Operations · CI/CD & Automation · Localization
  **Published:** `6th August 2021`
  **NeKI brief:** Whenever I mention using fastlane’s snapshot tool for App Store screenshots, I justify it by saying it’ll save you time if you have “ten screenshots for every device type in different localisations”. In reality, even if you have just two screenshots in one…
- [remove it from the App Store](https://www.macrumors.com/2021/07/22/apple-to-pill-idos-2-emulator-from-app-store) — iOS Dev Weekly · Issue 518 — Podcast · Topics: App Distribution & Store Operations · Developer Community & Business
  **Published:** `30th July 2021`
  **NeKI brief:** Examines iDOS 2, an app designed to allow users to play classic DOS games, will soon be pulled from the App Store, the app's creator said today. According to iDOS developer Chaoji Li,. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [this article from the Panic blog](https://panic.com/blog/the-future-of-code-editor) — iOS Dev Weekly · Issue 518 — Article · Topics: App Distribution & Store Operations
  **Published:** `30th July 2021`
  **NeKI brief:** I’ve also had this article from the Panic blog in my saved links for a while. It’s the story of why their editor, Nova, won’t come to iPad as they initially said it would. Predictably, it’s also due to the same App Store rules.
- [Getting the Most out of Custom Product Pages in the New App Store](https://appfigures.com/resources/guides/custom-product-pages-ios-15) — iOS Dev Weekly · Issue 513 — Article · Topics: App Distribution & Store Operations · Testing
  **Published:** `25th June 2021`
  **NeKI brief:** Examines The art of landing page optimization is (finally) coming to the App Store. Here. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [What’s New in iOS 15 for App Store Optimization](https://appfigures.com/resources/guides/ios15-aso-updates) — iOS Dev Weekly · Issue 512 — Article · Topics: App Distribution & Store Operations · Testing
  **Published:** `18th June 2021`
  **NeKI brief:** Examines The latest release of iOS bundles great features for developers that when used correctly can easily get more downloads. Here. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [App Store Review Guidelines Updates for WWDC 2021](http://www.appstorereviewguidelineshistory.com/articles/2021-06-07-wwdc-2021) — iOS Dev Weekly · Issue 511 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem
  **Published:** `11th June 2021`
  **NeKI brief:** Examines WWDC 2021 - App Store Review Guidelines History. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Getting Started with Combine](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS93YXRjaD9mZWF0dXJlPXlvdXR1LmJlJnV0bV9jYW1wYWlnbj0lMjBTd2lmdFVJJTIwV2Vla2x5JnV0bV9tZWRpdW09ZW1haWwmdXRtX3NvdXJjZT1SZXZ1ZSUyMG5ld3NsZXR0ZXImdj1YMm0wZjJOb0IxMCIsInBvc3RfaWQiOiI3NzBkNzMwYy05ZmNkLTRlOTItYWVjNi01YTJjOGM5YjcwZjgiLCJwdWJsaWNhdGlvbl9pZCI6Ijc5NDhlYTY1LWNiNmUtNGNkNS05NzJjLTMxZjhjNmQ2Y2RhNCIsInZpc2l0X3Rva2VuIjoiYjIzMDBmZWMtNDg2NC00YTRjLWIzM2UtN2JiZDlmNTcwMjUwIiwiaWF0IjoxNjc0MDYyNjc4LjI0MiwiaXNzIjoib3JjaGlkIn0.yG7_Fvr4s6AVhNrkvo-hVvyg2Qj5YZhIkX4eTkhsyG4) — SwiftUI Weekly · SwiftUI Weekly - Issue #56 — Tutorial · Topics: App Distribution & Store Operations · Combine & Reactive Programming · Graphics, Media & Games
  **Published:** `2021-04-26T20:19:20.000Z`
  **NeKI brief:** Introduces Combine publishers, subscribers, and operators through practical examples. Follow it when maintaining pre-concurrency SwiftUI code or bridging publisher pipelines into newer async/await boundaries.
- [iOS App Distribution & Best Practices](https://www.raywenderlich.com/books/ios-app-distribution-best-practices) — iOS Dev Weekly · Issue 504 — Article · Topics: App Distribution & Store Operations · Xcode
  **Published:** `23rd April 2021`
  **NeKI brief:** Examines Learn how to sign up for Apple Developer Program, generate the various certificates needed, configure your app and submit an app to the App Store for approval, both manually and th. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Creating a licensing system for paid apps in Swift](https://swiftrocks.com/creating-a-license-system-for-paid-apps-in-swift) — iOS Dev Weekly · Issue 502 — Article · Topics: App Distribution & Store Operations · Swift
  **Published:** `9th April 2021`
  **NeKI brief:** Explores Creating a licensing system for paid apps in Swift, focusing on unlike with ios, you have a choice of how you’d. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [A guide to distributing macOS apps outside of the App Store](https://rambo.codes/posts/2021-01-08-distributing-mac-apps-outside-the-app-store) — iOS Dev Weekly · Issue 490 — Article · Topics: App Distribution & Store Operations
  **Published:** `15th January 2021`
  **NeKI brief:** Examines Gui Rambo writes about his coding and reverse engineering adventures. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Xcode 12.3 is available on the Mac App Store](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL2FwcHMuYXBwbGUuY29tL2F6L2FwcC94Y29kZS9pZDQ5Nzc5OTgzNT9tdD0xMiZ1dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6ImUwZDA3MDRlLWU3MDItNGQzOC05YjcxLWYxNmMzODc4NGI1ZSIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiI0ODRkOGEwZi02ZTM1LTQ2ODgtOWJlYy04OTdmYWY5M2I5N2MiLCJpYXQiOjE2NzQwNjI2NzkuNzA4LCJpc3MiOiJvcmNoaWQifQ.Rnp31Lwoh2tW1CP8rFSLWGLLC-3eQlf-aop4b01WMPw) — SwiftUI Weekly · SwiftUI Weekly - Issue #39 — Article · Topics: App Distribution & Store Operations · Swift · Xcode
  **Published:** `2020-12-15T13:53:41.000Z`
  **NeKI brief:** Links to the Xcode 12.3 Mac App Store release from the historical issue. Use it only as release-history context when investigating SDK-era behavior, not as a current installation recommendation.
- [no idea](https://github.com/fastlane/fastlane/graphs/contributors) — iOS Dev Weekly · Issue 484 — Source repository · Topics: App Distribution & Store Operations · App Intents & System Surfaces · CI/CD & Automation
  **Published:** `27th November 2020`
  **NeKI brief:** Presents no idea, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [post the 85%/15% subscriptions revenue split](https://www.revenuecat.com/blog/about-that-85-percent) — iOS Dev Weekly · Issue 480 — Article · Topics: App Distribution & Store Operations · Combine & Reactive Programming
  **Published:** `30th October 2020`
  **NeKI brief:** Presents post the 85%/15% subscriptions revenue split, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Managing Version Numbers with Fastlane](https://benscheirman.com/2020/10/managing-version-numbers-with-fastlane) — iOS Dev Weekly · Issue 479 — Article · Topics: App Distribution & Store Operations · CI/CD & Automation
  **Published:** `23rd October 2020`
  **NeKI brief:** Choosing how to increment your app’s version number is one thing, but remembering all the steps to get a release out of the door is another! How many times have you forgotten to increment the version number before an App Store Connect upload? Or maybe you…
- [Thoughts on the App Store](http://rileytestut.com/blog/2020/10/14/thoughts-on-app-store) — iOS Dev Weekly · Issue 478 — Article · Topics: App Distribution & Store Operations · Testing
  **Published:** `16th October 2020`
  **NeKI brief:** Discusses Thoughts on the App Store, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [App Store Reviews Should be Stricter](https://tirania.org/blog/archive/2020/Sep-24.html) — iOS Dev Weekly · Issue 475 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `25th September 2020`
  **NeKI brief:** This is a very interesting post by Miguel de Icaza talking about the benefits of having a trusted App Store. He argues for some rule amendments, as well as several changes to the purchasing UI and App Store listing pages.
- [In-App Purchase Rules](https://marco.org/2020/09/11/app-review-changes) — iOS Dev Weekly · Issue 474 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `18th September 2020`
  **NeKI brief:** Discusses In-App Purchase Rules, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [Why you should charge more for your app subscriptions](https://mronge.com/why-you-should-charge-more-for-your-app-subscriptions) — iOS Dev Weekly · Issue 474 — Article · Topics: App Distribution & Store Operations
  **Published:** `18th September 2020`
  **NeKI brief:** Examines The conventional wisdom for app subscriptions is to price affordably, like $1.99/month, and hopefully attract lots of subscribers at a low price. Then by having low pricing, fewer. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Subscription or no subscription? That is not the question](https://ia.net/topics/subscription-or-no-subscription) — iOS Dev Weekly · Issue 470 — Article · Topics: App Distribution & Store Operations
  **Published:** `21st August 2020`
  **NeKI brief:** If you are selling apps, you need to read this post from the iA Writer team. It’s a long post on a complex subject, but it’s worth reading every word.
- [defended the “Hey.com” decision](https://techcrunch.com/2020/06/18/interview-apples-schiller-says-position-on-hey-app-is-unchanged-and-no-rules-changes-are-imminent) — iOS Dev Weekly · Issue 469 — Article · Topics: App Distribution & Store Operations
  **Published:** `14th August 2020`
  **NeKI brief:** Covers defended the "Hey.com" decision, focusing on Swift and Apple-platform engineering practice. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [more details](https://ibuildmyideas.substack.com/p/i-build-my-ideas-9-080920) — iOS Dev Weekly · Issue 469 — Article · Topics: App Distribution & Store Operations · Testing
  **Published:** `14th August 2020`
  **NeKI brief:** Examines Building Airport: The TestFlight App Store from idea to app. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Improving fairness and viability of the App Store for developers](https://aplus.rs/2020/improving-fairness-viability-app-store) — iOS Dev Weekly · Issue 467 — Article · Topics: App Distribution & Store Operations
  **Published:** `31st July 2020`
  **NeKI brief:** Examines Improving fairness and viability of the App Store for developers · aplus.rs. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Price Testing for Subscription Apps](https://www.revenuecat.com/blog/price-testing-for-subscription-apps) — iOS Dev Weekly · Issue 467 — Article · Topics: App Distribution & Store Operations · Persistence & Synchronisation · Testing
  **Published:** `31st July 2020`
  **NeKI brief:** Covers Price Testing for Subscription Apps, focusing on testing, diagnostics, and feedback quality. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [especially](https://github.com/facebook/facebook-ios-sdk/issues/1431) — iOS Dev Weekly · Issue 464 — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **Published:** `10th July 2020`
  **NeKI brief:** Explains especially, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [great](https://github.com/facebook/facebook-ios-sdk/issues/1430) — iOS Dev Weekly · Issue 464 — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **Published:** `10th July 2020`
  **NeKI brief:** Every day is a great day to remove (or advocate for the removal of) the Facebook SDK from your apps, but today is an especially… great… day… 🙄 How many times will Facebook get away with causing half the apps in the App Store to crash on startup? I linked to…
- [day](https://github.com/facebook/facebook-ios-sdk/issues/1427) — iOS Dev Weekly · Issue 464 — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **Published:** `10th July 2020`
  **NeKI brief:** The Facebook iOS SDK issue page records a public developer issue and its discussion about SDK behavior and integration.
- [this post by Gui Rambo](https://rambo.codes/posts/2020-05-07-the-big-facebook-crash) — iOS Dev Weekly · Issue 464 — Article · Topics: App Distribution & Store Operations
  **Published:** `10th July 2020`
  **NeKI brief:** Analyzes the 2020 Facebook crash and how third-party SDK dependencies can amplify failure across apps. Useful for dependency-risk reviews, especially when deciding which external components deserve isolation, monitoring, or rapid removal paths.
- [StoreKit Testing in Xcode](https://www.revenuecat.com/blog/storekit-testing-in-xcode) — iOS Dev Weekly · Issue 463 — Article · Topics: App Distribution & Store Operations · Testing · Xcode
  **Published:** `3rd July 2020`
  **NeKI brief:** Examines StoreKit Testing in Xcode, focusing on the building, debugging, and testing of storekit code is always stressful. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [short video showing how it works](https://www.youtube.com/watch?v=LGCcIsCDGkU) — iOS Dev Weekly · Issue 460 — Video · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `12th June 2020`
  **NeKI brief:** There are plenty of apps (both native, and web) that’ll help you dress up your app’s screenshots for your App Store listing, but not many that’ll do the same for your preview video. The best way to get up to speed here is to watch this short video showing…
- [You know StoreKit, but you don’t want to do StoreKit](https://docs.revenuecat.com/docs) — iOS Dev Weekly · Issue 458 — Article · Topics: App Distribution & Store Operations · Testing
  **Published:** `29th May 2020`
  **NeKI brief:** Examines You know StoreKit, but you don't want to do StoreKit, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [reducing their 30% cut](https://iosdevsurvey.com/2019/14-the-app-store) — iOS Dev Weekly · Issue 451 — Article · Topics: App Distribution & Store Operations
  **Published:** `10th April 2020`
  **NeKI brief:** I received a few emails after my comments last week on the Amazon App Store deal. Mainly, I heard that people didn’t think that the experimentation I was hoping for was as critical as Apple simply reducing their 30% cut.
- [The Ultimate Guide to iOS Subscription Testing](https://www.revenuecat.com/blog/the-ultimate-guide-to-subscription-testing-on-ios) — iOS Dev Weekly · Issue 451 — Article · Topics: App Distribution & Store Operations · Testing
  **Published:** `10th April 2020`
  **NeKI brief:** Examines This guide to iOS testing will help you find and fix bugs so you don't lose money due to issues in your subscription code. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Mac App Store in a nutshell](https://lapcatsoftware.com/articles/nutshell.html) — iOS Dev Weekly · Issue 449 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `27th March 2020`
  **NeKI brief:** Examines Mac App Store in a nutshell. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Dealing with Apple’s App Review](https://appmanager.io/blog/tips-and-tricks/dealing-with-apples-app-review) — iOS Dev Weekly · Issue 447 — Article · Topics: App Distribution & Store Operations
  **Published:** `13th March 2020`
  **NeKI brief:** Examines Transporter Lab – We make mobile better. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [How does your app fare if the App Store is down?](https://www.revenuecat.com/blog/post-mortem-2020-01-24-app-store-outage) — iOS Dev Weekly · Issue 441 — Article · Topics: App Distribution & Store Operations
  **Published:** `31st January 2020`
  **NeKI brief:** “But the App Store never goes down!” I hear you say. Well, it happened last week. Specifically, the verifyReceipt API endpoint was unavailable for about 5 hours. It was so bad that the light even went yellow on the status page, which by all accounts means…
- [changing the rules on how subscriptions work](https://www.theverge.com/2019/11/1/20943286/apple-tv-plus-free-trial-one-year-new-devices-cancel-auto-renew-how-to) — iOS Dev Weekly · Issue 434 — Article · Topics: App Distribution & Store Operations
  **Published:** `13th December 2019`
  **NeKI brief:** So it’s especially frustrating to see Apple not playing by the same rules as the rest of us have to. Like buttons that say “Start Reading” and look like they are part of an on-boarding UI, when they actually start recurring subscriptions. Or changing the…
- [NativeConnect](https://nativeconnect.app/blog/official-launch) — iOS Dev Weekly · Issue 433 — Article · Topics: App Distribution & Store Operations
  **Published:** `6th December 2019`
  **NeKI brief:** Vadim Shpakovski on the launch of his native iTunes Connect client. If you’re managing multiple apps and especially if you’re managing with multiple App Store accounts, this is going to deliver some huge time savings. The free version can also do plenty, so…
- [Faster way to download and install Xcode](https://blog.kulman.sk/faster-way-to-download-and-install-xcode) — iOS Dev Weekly · Issue 431 — Article · Topics: App Distribution & Store Operations · Xcode
  **Published:** `22nd November 2019`
  **NeKI brief:** Presents Faster way to download and install Xcode, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [How to build a UICollectionView like the App Store](https://www.youtube.com/watch?v=SR7DtcT61tA) — iOS Dev Weekly · Issue 426 — Video · Topics: App Distribution & Store Operations · Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `18th October 2019`
  **NeKI brief:** Paul Hudson doing a video that isn’t about SwiftUI? Oh yes! This is a fantastic guide to the new collection view APIs introduced at this year’s WWDC. If you haven’t looked at the changes yet, this is a great way to catch up.
- [open source](https://github.com/rileytestut/AltStore) — iOS Dev Weekly · Issue 423 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Testing
  **Published:** `27th September 2019`
  **NeKI brief:** Examines AltStore is an alternative app store for non-jailbroken iOS devices. - altstoreio/AltStore. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [App Store Today on the web, in full... Almost](https://9to5mac.com/2019/08/15/app-store-today-web-browser) — iOS Dev Weekly · Issue 417 — Article · Topics: App Distribution & Store Operations
  **Published:** `16th August 2019`
  **NeKI brief:** The article reports on viewing the App Store Today editorial experience on the web and describes the limitations of that implementation.
- [Finch](https://github.com/namolnad/Finch) — iOS Dev Weekly · Issue 417 — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **Published:** `16th August 2019`
  **NeKI brief:** Finch is a Swift or Apple-platform developer project. Follow its README and source to inspect the concrete API and workflow it provides, then verify maintenance and platform assumptions before adoption.
- [How to get noticed by Apple](https://appfollow.io/ru/blog/how-to-gear-up-for-ios-13-to-get-noticed-by-apple) — iOS Dev Weekly · Issue 417 — Article · Topics: App Distribution & Store Operations
  **Published:** `16th August 2019`
  **NeKI brief:** Examines In September, Apple traditionally refreshes its operating system. We have asked app developers to share how they. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [imperfect status bars](https://xkcd.com/1373) — iOS Dev Weekly · Issue 413 — Article · Topics: App Distribution & Store Operations
  **Published:** `19th July 2019`
  **NeKI brief:** Examines xkcd: Screenshot. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [shut down App Review Times](https://daveverwer.com/blog/saying-goodbye-to-app-review-times) — iOS Dev Weekly · Issue 412 — Article · Topics: App Distribution & Store Operations
  **Published:** `12th July 2019`
  **NeKI brief:** Discusses used to run, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [ASO Keyword Optimization in Practice](https://asostack.com/aso-keyword-optimization-in-practice-part-2-504ccc15b531) — iOS Dev Weekly · Issue 411 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `5th July 2019`
  **NeKI brief:** Examines Now that you’ve had the time to develop your keyword backlog through researching and setting the relevancy in ASO Keyword Optimization in Practice: Part 1, we will be moving on to. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [proposal](https://screentimeapi.com/screen-time-api) — iOS Dev Weekly · Issue 406 — Article · Topics: App Distribution & Store Operations
  **Published:** `31st May 2019`
  **NeKI brief:** The page presents a Screen Time API proposal and describes the intended interface for accessing screen-time information.
- [Migrating a paid app to be free with In-App Purchases](https://fluffy.es/migrate-paid-app-to-iap) — iOS Dev Weekly · Issue 406 — Article · Topics: App Distribution & Store Operations
  **Published:** `31st May 2019`
  **NeKI brief:** Examines Axel Kee with a good explanation of the techniques needed to transition users from a paid-up-front app to a free app with in-app purchases. This is never going to be a trivial thing to do, but if you’ve made the decision Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Intentional Subscriptions](https://david-smith.org/blog/2019/05/28/intentional-subscriptions) — iOS Dev Weekly · Issue 406 — Article · Topics: App Distribution & Store Operations
  **Published:** `31st May 2019`
  **NeKI brief:** The article discusses designing intentional subscription experiences and making recurring purchases understandable and valuable to users.
- [Senator Hawley announces bill banning loot boxes, pay-to-win mechanics](https://arstechnica.com/gaming/2019/05/senator-hawley-announces-bill-banning-loot-boxes-pay-to-win-mechanics) — iOS Dev Weekly · Issue 403 — Tutorial · Topics: App Distribution & Store Operations · Developer Community & Business · Graphics, Media & Games
  **Published:** `10th May 2019`
  **NeKI brief:** Examines Game developers shouldn’t be allowed to monetize addiction," Mo. Republican says. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Free weekend at raywenderlich.com](https://www.raywenderlich.com/3068730-free-weekend-at-raywenderlich-com-until-sunday-may-5) — iOS Dev Weekly · Issue 402 — Tutorial · Topics: App Distribution & Store Operations · Developer Community & Business · Graphics, Media & Games
  **Published:** `3rd May 2019`
  **NeKI brief:** Presents Free weekend at raywenderlich.com, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Swift talk episodes](https://talk.objc.io/collections/markdown-playgrounds) — iOS Dev Weekly · Issue 400 — Article · Topics: App Distribution & Store Operations · Swift
  **Published:** `19th April 2019`
  **NeKI brief:** The associated Swift talk episodes are also worth watching if you’re interested in how they built this, or if you’re curious about AppKit development. The first one is free, the rest need a subscription.
- [Just How Impactful is Being Featured on the App Store?](https://asostack.com/just-how-impactful-is-being-featured-on-the-app-store-cb2185fb2e32) — iOS Dev Weekly · Issue 396 — Article · Topics: App Distribution & Store Operations
  **Published:** `22nd March 2019`
  **NeKI brief:** Examines In addition to carrying out keyword optimization, apps can boost their visibility on the App Store by being featured. Having your app promoted on the Today, Games or Apps tabs can. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Nintendo Asks Mobile Developers to Curb Microtransactions](https://variety.com/2019/gaming/news/nintendo-mobile-microtransactions-1203156557) — iOS Dev Weekly · Issue 394 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `8th March 2019`
  **NeKI brief:** Reports Nintendo’s approach to mobile-game monetization and its request to curb aggressive microtransactions. Useful product context for discussing revenue design and user trust, not as an implementation guide.
- [Constraints](https://blog.curtisherbert.com/slopes-diaries) — iOS Dev Weekly · Issue 392 — Article · Topics: App Distribution & Store Operations
  **Published:** `22nd February 2019`
  **NeKI brief:** The Slopes diary entry discusses constraints encountered while building the application and records practical engineering decisions.
- [Ending my fastlane chapter](https://krausefx.com/blog/ending-my-fastlane-chapter) — iOS Dev Weekly · Issue 391 — Article · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Community & Business
  **Published:** `15th February 2019`
  **NeKI brief:** The page covers “Ending my fastlane chapter” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [US iPhone users spent, on average, $79 on apps last year, up 36% from 2017](https://techcrunch.com/2019/02/11/us-iphone-users-spent-79-last-year-up-36-from-2017) — iOS Dev Weekly · Issue 391 — Article · Topics: App Distribution & Store Operations
  **Published:** `15th February 2019`
  **NeKI brief:** Examines Apple's push to get developers to build subscription-based apps is now having a notable impact on App Store revenues. According to a new report from. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [ABI Stability for Swift](https://swift.org/blog/abi-stability-and-more) — iOS Dev Weekly · Issue 390 — Article · Topics: App Distribution & Store Operations · Swift
  **Published:** `8th February 2019`
  **NeKI brief:** Explains Swift’s ABI-stability milestone and related distribution implications for runtimes, frameworks, and binary compatibility. Useful historical context for understanding why newer Swift libraries can ship without bundling a language runtime in the same way.
- [Phased vs Regular Update Adoption Rates](https://david-smith.org/blog/2019/01/22/phased-vs-regular-update-adoption-rates) — iOS Dev Weekly · Issue 388 — Article · Topics: App Distribution & Store Operations
  **Published:** `25th January 2019`
  **NeKI brief:** Presents Phased vs Regular Update Adoption Rates, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [In-App Purchases: Receipt Validation Tutorial](https://www.raywenderlich.com/9257-iap-receipt-validation) — iOS Dev Weekly · Issue 386 — Tutorial · Topics: App Distribution & Store Operations
  **Published:** `11th January 2019`
  **NeKI brief:** Apple are pushing IAPs and subscriptions are the future of making money on the App Store. I think we’re all on the same page there. It did strike me while reading this though, that this could be much simpler. 😂
- [read this](http://racecondition.software/blog/more-reviews) — iOS Dev Weekly · Issue 386 — Article · Topics: App Distribution & Store Operations
  **Published:** `11th January 2019`
  **NeKI brief:** Examines We need to be slightly cautious with this data as I couldn’t find much information about who participated in it, and people who would take the time to fill in a survey about their App Store purchasing habits certainly sk Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Netflix Pulling Out of iTunes Billing for New Users](https://daringfireball.net/2019/01/netflix_itunes_billing) — iOS Dev Weekly · Issue 385 — Article · Topics: App Distribution & Store Operations
  **Published:** `4th January 2019`
  **NeKI brief:** Examines Apple can make the rules — it’s their platform. But it’s just wrong that one of the rules is that apps aren’t allowed to explain the rules to users. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [promoting Carpool Karaoke and Apple Music](https://www.macrumors.com/2018/12/18/apple-unsolicited-notifications) — iOS Dev Weekly · Issue 383 — Article · Topics: App Distribution & Store Operations
  **Published:** `21st December 2018`
  **NeKI brief:** Examines Apple has recently been sending out unsolicited notifications to iOS users, promoting Carpool Karaoke episodes and the availability of Apple Music on Amazon Echo devices. Multiple. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Apple Changes App Store Rules to Allow Users to Gift In-App Purchases](https://www.macrumors.com/2018/12/19/app-store-in-app-purchase-gifting) — iOS Dev Weekly · Issue 383 — Article · Topics: App Distribution & Store Operations
  **Published:** `21st December 2018`
  **NeKI brief:** Examines Apple today made a tweak to its App Store Review Guidelines, allowing developers to implement a new feature that will let iOS users purchase in-app content as a gift. Right now, iO. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Automate your library releases with Fastlane](https://mar.codes/2018-11-14/Automate-open-source-libraries-releases-with-fastlane) — iOS Dev Weekly · Issue 381 — Article · Topics: App Distribution & Store Operations · CI/CD & Automation · Objective-C & Cocoa
  **Published:** `7th December 2018`
  **NeKI brief:** It’s easy to forget that fastlane can automate much more than code signing and App Store releases. What about using it to release new versions of open source libraries you maintain to CocoaPods? Marcos Griselli shows us how.
- [exist](https://culturedcode.com/things) — iOS Dev Weekly · Issue 380 — Article · Topics: App Distribution & Store Operations
  **Published:** `30th November 2018`
  **NeKI brief:** Things is a polished task-management app for Mac, iPhone, and iPad, organized around planning, projects, and daily actions. Use it as a product reference when evaluating information hierarchy, cross-device workflows, and the interaction quality expected from native productivity software.
- [though](https://contrast.co/weather-up) — iOS Dev Weekly · Issue 380 — Article · Topics: App Distribution & Store Operations
  **Published:** `30th November 2018`
  **NeKI brief:** Examines Contrast | Weather Up. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Transmit 5 on the Mac App Store](https://panic.com/blog/transmit-5-on-the-mac-app-store) — iOS Dev Weekly · Issue 379 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem
  **Published:** `23rd November 2018`
  **NeKI brief:** Examines Panic Blog » Transmit 5 on the Mac App Store. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [The iOS App Store is No Longer Listing All In-App Purchases](https://www.tekrevue.com/ios-app-store-no-in-app-purchases) — iOS Dev Weekly · Issue 376 — Article · Topics: App Distribution & Store Operations
  **Published:** `2nd November 2018`
  **NeKI brief:** Examines The Best of Tech, Daily. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Sneaky subscriptions are plaguing the App Store](https://techcrunch.com/2018/10/15/sneaky-subscriptions-are-plaguing-the-app-store) — iOS Dev Weekly · Issue 374 — Article · Topics: App Distribution & Store Operations
  **Published:** `19th October 2018`
  **NeKI brief:** Examines Subscriptions have turned into a booming business for app developers, accounting for $10.6 billion in consumer spend on the App Store in 2017, and are. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [the acquisition](https://techcrunch.com/2014/02/21/rumor-testflight-owner-burstly-is-being-acquired-by-apple) — iOS Dev Weekly · Issue 371 — Article · Topics: App Distribution & Store Operations · Testing
  **Published:** `28th September 2018`
  **NeKI brief:** Discusses the acquisition, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [Surviving the App Store](https://github.com/amirrajan/survivingtheappstore) — iOS Dev Weekly · Issue 367 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Graphics, Media & Games
  **Published:** `31st August 2018`
  **NeKI brief:** Examines My book on getting to the #1 Spot in the App Store. Buy my games to support me. - amirrajan/survivingtheappstore. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Ryan Cash](https://github.com/amirrajan/survivingtheappstore/blob/master/manuscript/altos-adventure-interview.md) — iOS Dev Weekly · Issue 367 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Graphics, Media & Games
  **Published:** `31st August 2018`
  **NeKI brief:** The page covers “Ryan Cash” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Sam Barlow](https://github.com/amirrajan/survivingtheappstore/blob/master/manuscript/her-story-interview.md) — iOS Dev Weekly · Issue 367 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Graphics, Media & Games
  **Published:** `31st August 2018`
  **NeKI brief:** Examines My book on getting to the #1 Spot in the App Store. Buy my games to support me. - survivingtheappstore/manuscript/her-story-interview.md at master · amirrajan/survivingtheappstore. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Shaun Musgrave](https://github.com/amirrajan/survivingtheappstore/blob/master/manuscript/touch-arcade-interview.md) — iOS Dev Weekly · Issue 367 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Graphics, Media & Games
  **Published:** `31st August 2018`
  **NeKI brief:** This free ebook from Amir Rajan looks great. The first few chapters go through some tips and techniques for running an App Store game business, but then the book switches into transcripts of interviews with popular iOS game developers and others in the…
- [Adobe XD](https://www.adobe.com/products/xd.html) — iOS Dev Weekly · Issue 365 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `17th August 2018`
  **NeKI brief:** Examines Adobe XD Help. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [being removed](https://www.macstories.net/news/apple-announces-apps-and-in-app-purchases-will-be-removed-from-its-affiliate-program-october-1st) — iOS Dev Weekly · Issue 363 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `3rd August 2018`
  **NeKI brief:** The article reports Apple's announcement that apps and in-app purchases would be removed from its affiliate programme and explains the change for developers and publishers.
- [Apple’s App Store revenue nearly double that of Google Play](https://techcrunch.com/2018/07/16/apples-app-store-revenue-nearly-double-that-of-google-play-in-first-half-of-2018) — iOS Dev Weekly · Issue 361 — Article · Topics: App Distribution & Store Operations
  **Published:** `20th July 2018`
  **NeKI brief:** Examines Apple's App Store continues to outpace Google Play on revenue. In the first half of the year, the App Store generated nearly double the revenue of Google. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [not only the App Store](https://512pixels.net/2018/07/mobilemes-legacy) — iOS Dev Weekly · Issue 360 — Article · Topics: App Distribution & Store Operations
  **Published:** `13th July 2018`
  **NeKI brief:** A retrospective marking MobileMe's legacy alongside the App Store's tenth anniversary. It provides historical perspective on Apple's cloud-service evolution.
- [Distribute your iOS apps to beta testers faster with auto-provisioning](https://blogs.msdn.microsoft.com/vsappcenter/announcing-auto-provisioning-build-and-distribute-apps-faster) — iOS Dev Weekly · Issue 360 — Article · Topics: App Distribution & Store Operations · Testing
  **Published:** `13th July 2018`
  **NeKI brief:** Get your iOS apps in the hands of your testers faster with the new auto-provisioning capability in App Center. We’ve added this capability into the install portal, so you can automate the distribution process, enable testers, and team members to install the…
- [App Store Review Guidelines – Changes from WWDC 2018](http://www.appstorereviewguidelineshistory.com/articles/2018-06-04-wwdc2018) — iOS Dev Weekly · Issue 357 — Tutorial · Topics: App Distribution & Store Operations · Apple Platform Ecosystem · Developer Community & Business
  **Published:** `22nd June 2018`
  **NeKI brief:** Examines Changes after WWDC 2018 - App Store Review Guidelines History. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [App Store Guidelines](https://gist.github.com/hongrich/260fc8c36aaed3f2a63c0612ba9fc910/revisions) — iOS Dev Weekly · Issue 355 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Spatial Computing
  **Published:** `8th June 2018`
  **NeKI brief:** Examines App Store Guidelines, focusing on but dave, what about all the other stuff from this week? what about the new app store guidelines, the swift 5 delay,…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current.
- [Swift 5 delay](https://github.com/apple/swift-evolution/commit/de7727f7dcf7bbfdea6763a87f4c8c534f27406e) — iOS Dev Weekly · Issue 355 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Swift
  **Published:** `8th June 2018`
  **NeKI brief:** Examines Swift 5 delay, focusing on but dave, what about all the other stuff from this week? what about the new app store guidelines, the swift 5 delay,…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current.
- [Apple Silently Launched Creative Testing in App Store Search Ads](https://asostack.com/apple-secretly-launched-creative-testing-in-app-store-search-ads-761a9f7b8abb) — iOS Dev Weekly · Issue 354 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa · Testing
  **Published:** `1st June 2018`
  **NeKI brief:** Examines Mobile marketers and developers can as of now test different Apple Search Ads assets in the App Store. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [iOS apps should be inside a network sandbox](https://krausefx.com//blog/ios-app-network-sandboxing) — iOS Dev Weekly · Issue 353 — Article · Topics: App Distribution & Store Operations · Security & Privacy
  **Published:** `25th May 2018`
  **NeKI brief:** Examines Background. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Build Incrementation Techniques for iOS Apps](http://shashikantjagtap.net/build-incrementation-techniques-for-ios-release-train) — iOS Dev Weekly · Issue 353 — Article · Topics: App Distribution & Store Operations · CI/CD & Automation
  **Published:** `25th May 2018`
  **NeKI brief:** Presents build-incrementation techniques for an iOS release train. Follow it for concrete versioning and CI release workflow ideas, while checking current Xcode and App Store requirements.
- [A new Microsoft Store revenue share is coming](https://blogs.windows.com/buildingapps/2018/05/07/a-new-microsoft-store-revenue-share-is-coming) — iOS Dev Weekly · Issue 351 — Article · Topics: App Distribution & Store Operations
  **Published:** `11th May 2018`
  **NeKI brief:** Discusses A new Microsoft Store revenue share is coming, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [Become an iOS Developer with Udacity](https://www.udacity.com/course/ios-developer-nanodegree--nd003?coupon=iosdevweekly) — iOS Dev Weekly · Issue 350 — Tutorial · Topics: App Distribution & Store Operations · Code Quality · Developer Career & Practice
  **Published:** `4th May 2018`
  **NeKI brief:** Examines Become an iOS Developer with Udacity, focusing on enroll in udacity’s ios developer nanodegree program today. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [How Ulysses pulled off a controversial pivot to subscription](https://blog.chartmogul.com/how-ulysses-pulled-off-a-controversial-pivot-to-subscription) — iOS Dev Weekly · Issue 349 — Podcast · Topics: App Distribution & Store Operations · Developer Community & Business
  **Published:** `27th April 2018`
  **NeKI brief:** Examines Ulysses co-founder Max Seelemann explains how the writing app. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [ShineUpdater: Enterprise app updates](https://github.com/EightyThreeCreative/ShineUpdater) — iOS Dev Weekly · Issue 347 — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **Published:** `13th April 2018`
  **NeKI brief:** The GitHub repository provides ShineUpdater, a library for distributing enterprise application updates on Apple platforms.
- [App Store Subscriptions And You](http://ikennd.ac/blog/2018/04/app-store-subscriptions-and-you) — iOS Dev Weekly · Issue 347 — Article · Topics: App Distribution & Store Operations
  **Published:** `13th April 2018`
  **NeKI brief:** Daniel Kennett with advice on getting the copy and structure of your In-App Purchase screens in order, especially if you’re dealing with subscriptions. There’s some great advice around a couple of edge cases here like for example, what happens if the user…
- [MerchantKit](https://github.com/benjaminmayo/merchantkit) — iOS Dev Weekly · Issue 346 — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **Published:** `6th April 2018`
  **NeKI brief:** Presents MerchantKit, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Nope. You can’t mine cryptocurrency as a form of payment...](https://www.macrumors.com/2018/03/13/cryptocurrency-mining-app-pulled-mac-app-store) — iOS Dev Weekly · Issue 344 — Article · Topics: App Distribution & Store Operations
  **Published:** `23rd March 2018`
  **NeKI brief:** Examines Yesterday, it was discovered that a Mac App Store app called Calendar 2 had implemented a cryptocurrency mining feature that users could elect to use to unlock in-app features rath. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Background Currency Mining as a Payment Method?](https://arstechnica.com/information-technology/2018/03/theres-a-currency-miner-in-the-mac-app-store-and-apple-seems-ok-with-it) — iOS Dev Weekly · Issue 343 — Article · Topics: App Distribution & Store Operations
  **Published:** `16th March 2018`
  **NeKI brief:** Examines Popular Calendar 2 app mines Monero by default, but at least it discloses it. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [ProvisionQL](https://github.com/ealeksandrov/ProvisionQL) — iOS Dev Weekly · Issue 340 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Performance
  **Published:** `23rd February 2018`
  **NeKI brief:** Examines Quick Look plugin for mobile apps and provisioning profiles - ealeksandrov/ProvisionQL. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [iA Writer](https://ia.net/writer) — iOS Dev Weekly · Issue 339 — Article · Topics: App Distribution & Store Operations · Developer Community & Business
  **Published:** `16th February 2018`
  **NeKI brief:** Great facts and figures from the folks at iA Writer on various experiments they did with their App Store listings. Specifically, this post is about how your sales could be affected by increasing your blogging activity. Fascinating.
- [“Getting Featured” Numbers](https://blog.curtisherbert.com/slopes-diaries-23-featuring-numbers) — iOS Dev Weekly · Issue 337 — Article · Topics: App Distribution & Store Operations
  **Published:** `2nd February 2018`
  **NeKI brief:** Presents “Getting Featured” Numbers, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [The iOS Economy, Updated](http://www.asymco.com/2018/01/08/the-ios-economy-updated) — iOS Dev Weekly · Issue 335 — Article · Topics: App Distribution & Store Operations
  **Published:** `19th January 2018`
  **NeKI brief:** Examines In its latest update on the App Store Apple reported that iOS developers earned $26.5 billion in 2017. A year ago the figure was $20 billion. The growth rate is then about 33%. The. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Apple Updates and Expands App Store Review Guidelines](https://www.macstories.net/news/apple-updates-and-expands-app-store-review-guidelines-to-address-pre-orders-loot-boxes-vpns-and-more) — iOS Dev Weekly · Issue 333 — Article · Topics: App Distribution & Store Operations
  **Published:** `5th January 2018`
  **NeKI brief:** Discusses Apple Updates and Expands App Store Review Guidelines, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [App Store Guidelines on Templated Apps Relaxed Slightly](https://www.macrumors.com/2017/12/20/app-store-guidelines-updated-template-apps) — iOS Dev Weekly · Issue 332 — Article · Topics: App Distribution & Store Operations
  **Published:** `22nd December 2017`
  **NeKI brief:** Examines App Store Guidelines on Templated Apps Relaxed Slightly, focusing on after last week’s news where the review guidelines were changed to disallow templated apps, there has been a slight…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details.
- [templated apps](https://techcrunch.com/2017/12/08/apples-widened-ban-on-templated-apps-is-wiping-small-businesses-from-the-app-store) — iOS Dev Weekly · Issue 331 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem
  **Published:** `15th December 2017`
  **NeKI brief:** Discusses templated apps, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [Introductory Pricing for Subscription Apps in iOS 11.2](https://9to5mac.com/2017/11/06/ios-11-2-intro-pricing-subscriptions-app-store) — iOS Dev Weekly · Issue 326 — Article · Topics: App Distribution & Store Operations
  **Published:** `10th November 2017`
  **NeKI brief:** The article explains introductory pricing for subscription apps introduced with iOS 11.2 and its implications for App Store developers.
- [WhatsNew](https://github.com/BalestraPatrick/WhatsNew) — iOS Dev Weekly · Issue 325 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Testing
  **Published:** `3rd November 2017`
  **NeKI brief:** Examines WhatsNew, focusing on almost nobody reads app update information in the app store anymore, so how do you let your users know about what’s new…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [The new iOS 11 App Store and the impact on your conversion rate](https://asostack.com/the-new-ios-11-app-store-and-the-impact-on-your-conversion-rate-2743773debdb) — iOS Dev Weekly · Issue 325 — Article · Topics: App Distribution & Store Operations
  **Published:** `3rd November 2017`
  **NeKI brief:** Examines In this blog post, we will try to analyze how the App Store work by simulating users, searches, impressions and downloads for both iOS10 and iOS11. We will then study the final dis. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Cards](https://github.com/PaoloCuscela/Cards) — iOS Dev Weekly · Issue 324 — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **Published:** `27th October 2017`
  **NeKI brief:** Presents Cards, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [App Review and Device Requirement Discrepancies](https://pxlnv.com/linklog/app-review-device-requirements) — iOS Dev Weekly · Issue 322 — Article · Topics: App Distribution & Store Operations
  **Published:** `13th October 2017`
  **NeKI brief:** Great reminder from Nick Heer that it is our responsibility as developers to ensure that we correctly apply the correct device restrictions to our apps so that we don’t get people downloading our apps only to be disappointed when they don’t work. I also…
- [NSSpain 2017](https://vimeo.com/album/4786409) — iOS Dev Weekly · Issue 320 — Video · Topics: App Distribution & Store Operations · Developer Community & Business · Graphics, Media & Games
  **Published:** `29th September 2017`
  **NeKI brief:** The Vimeo showcase collects publicly viewable NSSpain 2017 conference recordings and exposes their session metadata.
- [Crafting Great Reverse-DNS Identifiers 🆔](https://littlebitesofcocoa.com/317-crafting-great-reverse-dns-identifiers) — iOS Dev Weekly · Issue 319 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `22nd September 2017`
  **NeKI brief:** Examines Apple platforms make heavy use of "reverse-DNS" identifiers. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [New report suggests app makers should charge more if they want people to buy subscriptions](https://www.theverge.com/2017/8/15/16147954/liftoff-report-apple-ios-android-app-subscriptions-conversion-rate-2017) — iOS Dev Weekly · Issue 314 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `18th August 2017`
  **NeKI brief:** There has been lots of discussion around in-app subscriptions again this week after Ulysses switched from pay-to-own to a subscription model. In this post, Lauren Goode looks at a Liftoff report which says that charging more actually reduces the cost per…
- [Creating and Assigning Certificates and Profiles](http://martiancraft.com/blog/2017/07/demystifying-provisioning-part2) — iOS Dev Weekly · Issue 312 — Article · Topics: App Distribution & Store Operations · Performance · Security & Privacy
  **Published:** `4th August 2017`
  **NeKI brief:** In part two of his two-part series, Cory Bohon covers in detail the process of creating and assigning certificates and signing an app. If you’re new to iOS development or want a recap of the basics, also check out part one! 😃
- [part one](http://martiancraft.com/blog/2017/05/demystifying-ios-provisioning-part1) — iOS Dev Weekly · Issue 312 — Article · Topics: App Distribution & Store Operations · Security & Privacy
  **Published:** `4th August 2017`
  **NeKI brief:** Examines In part two of his two-part series, Cory Bohon covers in detail the process of creating and assigning certificates and signing an app. If you’re new to iOS development or want a recap of the basics, also check out part o Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Cracking the code behind Apple’s App Store promo card design](http://blog.equinux.com/2017/07/cracking-the-code-behind-apples-app-store-promo-card-design) — iOS Dev Weekly · Issue 311 — Article · Topics: App Distribution & Store Operations · Developer Community & Business · Graphics, Media & Games
  **Published:** `28th July 2017`
  **NeKI brief:** A wonderful set of videos from the ADD conference which was held last month in the beautiful city of Barcelona.
- [Manual Provisioning](http://martiancraft.com/blog/2017/07/manual-provisioning) — iOS Dev Weekly · Issue 310 — Article · Topics: App Distribution & Store Operations · Performance · Xcode
  **Published:** `21st July 2017`
  **NeKI brief:** Xcode 9 manual signing requires an explicit team, profile, and certificate selection, yet Xcode may still request missing certificates. Treat manual provisioning as a controlled configuration workflow and verify portal assets whenever signing behavior looks automatic.
- [Introducing fastlane precheck](https://fabric.io/blog/introducing-fastlane-precheck) — iOS Dev Weekly · Issue 307 — Article · Topics: App Distribution & Store Operations · CI/CD & Automation
  **Published:** `30th June 2017`
  **NeKI brief:** Ah fastlane, what would we do without it? 🎉 Precheck is a wonderful App Store metadata checker that’ll make sure you don’t fall foul of some of the the most common reasons for a first rejection. Looks great! ✅
- [Why App Preview Videos Are Vital in iOS 11](https://applaunchmap.com/2017/06/23/why-app-preview-videos-are-vital-in-ios-11) — iOS Dev Weekly · Issue 307 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `30th June 2017`
  **NeKI brief:** Examines Your guide to launching and updating iOS and Mac apps. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Want To be Happier at Work?](https://hired.com/join) — iOS Dev Weekly · Issue 307 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `30th June 2017`
  **NeKI brief:** Hired brings job offers to you, so you can stop wasting your time applying. Apply to 6,000+ companies at once on the platform. 🤖
- [In iOS 11, App Store editorial comes out of the shadows](https://sixcolors.com/post/2017/06/in-ios-11-app-store-editorial-comes-out-of-the-shadows) — iOS Dev Weekly · Issue 306 — Article · Topics: App Distribution & Store Operations · Developer Community & Business
  **Published:** `23rd June 2017`
  **NeKI brief:** Jason Snell talking about the biggest App Store news of the conference, the addition of editorial in the new design. This is by far the biggest change of the new redesign and I can’t wait to see what Apple choose to do with it.
- [App Store Review Guidelines changes from WWDC 2017](http://www.appstorereviewguidelineshistory.com/articles/2017-06-08-new-rules-following-wwdc-2017) — iOS Dev Weekly · Issue 304 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem
  **Published:** `9th June 2017`
  **NeKI brief:** Examines App Store Review Guidelines changes from WWDC 2017, focusing on what else did wwdc bring us? a huge set of changes to the app store review guidelines! 📖 along with some quite shocking…. Use it as a focused research reference for related Apple-platform work.
- [More Than Stickers: Exploring iMessage App Utilities](https://www.macstories.net/stories/more-than-stickers-exploring-imessage-app-utilities) — iOS Dev Weekly · Issue 303 — Article · Topics: App Distribution & Store Operations
  **Published:** `2nd June 2017`
  **NeKI brief:** I think we can all agree that the iMessage App Store has not been a huge success. Yes, stickers are popular (and I really didn’t think they would be), but app discovery and the usability of the platform leave a lot to be desired. However, it’s not all…
- [Dash Returns to the iOS App Store](https://blog.kapeli.com/dash-for-ios-back-on-the-app-store) — iOS Dev Weekly · Issue 302 — Article · Topics: App Distribution & Store Operations
  **Published:** `26th May 2017`
  **NeKI brief:** If you think back to October, Dash was removed due to alleged violations of the developer license agreement by an associated account. Apple did not change their decision, but the developer at Kapeli brought Dash back to the App Store using a personal account…
- [open-sourced](https://github.com/Kapeli/Dash-iOS) — iOS Dev Weekly · Issue 302 — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **Published:** `26th May 2017`
  **NeKI brief:** Examines If you think back to October, Dash was removed due to alleged violations of the developer license agreement by an associated account. Apple did not change their decision, but the developer at Kapeli brought Dash back to Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [App Launch Map](https://applaunchmap.com/blog) — iOS Dev Weekly · Issue 302 — Article · Topics: App Distribution & Store Operations
  **Published:** `26th May 2017`
  **NeKI brief:** Examines Your guide to launching and updating iOS and Mac apps. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [December](https://www.macrumors.com/2016/12/02/apple-app-store-us-pricing-regional-currencies) — iOS Dev Weekly · Issue 301 — Article · Topics: App Distribution & Store Operations
  **Published:** `19th May 2017`
  **NeKI brief:** It’s worth mentioning the iTunes Connect email we received yesterday. It looks like Apple will be converting pricing to local currencies for apps in more countries (they did a few back in December). While auto-renewable subscriptions won’t be affected in…
- [How Much I’ve Earned on the App Store 🤑](http://stephencoyle.net/appstore) — iOS Dev Weekly · Issue 301 — Article · Topics: App Distribution & Store Operations · Personal Essays
  **Published:** `19th May 2017`
  **NeKI brief:** Discusses How Much I’ve Earned on the App Store 🤑, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [Phil Schiller on App Store Upgrade Pricing](https://mjtsai.com/blog/2017/05/06/phil-schiller-on-app-store-upgrade-pricing) — iOS Dev Weekly · Issue 300 — Article · Topics: App Distribution & Store Operations
  **Published:** `12th May 2017`
  **NeKI brief:** App Store upgrade pricing has been on iOS developers’ wish-lists for a while, and it’s great to hear Schiller’s take on it. His arguments against it do make a lot of sense, especially now that subscription pricing is an option (it is worth noting that not…
- [How we increased app reviews by 12x](https://blog.dice.fm/how-we-increased-app-reviews-by-12x-9e79a2610521) — iOS Dev Weekly · Issue 299 — Article · Topics: App Distribution & Store Operations
  **Published:** `5th May 2017`
  **NeKI brief:** Now that developers can reply to reviews, all that’s left is getting some reviews to respond to! 😂 Reviews are not the easiest things to come by, and sometimes you need to give your users a small push in the right direction. Kieran Doyle points out two…
- [What is the value of iOS code signing?](https://krausefx.com/blog/the-developer-part-of-ios-code-signing-doesnt-add-any-security-to-anything) — iOS Dev Weekly · Issue 298 — Article · Topics: App Distribution & Store Operations · Security & Privacy · Testing
  **Published:** `28th April 2017`
  **NeKI brief:** Do we really need code signing today? Felix Krause argues that we don’t (with the exception of local development and AdHoc builds) and it’s hard to disagree. The code signing that you add has never been used for App Store builds and with TestFlight, it’s…
- [Developers can finally respond to App Store reviews](https://techcrunch.com/2017/03/28/developers-can-finally-respond-to-app-store-reviews-heres-how-it-works) — iOS Dev Weekly · Issue 294 — Article · Topics: App Distribution & Store Operations
  **Published:** `31st March 2017`
  **NeKI brief:** Examines With yesterday's release of iOS 10.3 and macOS 10.12.4, Apple has made a significant change to how its App Stores operate. At long last, developers now. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Indie Game Promotion Takes Over App Store](https://www.macstories.net/news/indie-game-promotion-takes-over-app-store) — iOS Dev Weekly · Issue 292 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `17th March 2017`
  **NeKI brief:** I was happy to see this promotion for independent game developers on the App Store recently. I’d love them give the same privilege to independent apps next!
- [Making More Outside The Mac App Store](https://weblog.rogueamoeba.com/2017/02/10/piezos-life-outside-the-app-store) — iOS Dev Weekly · Issue 287 — Article · Topics: App Distribution & Store Operations · Developer Community & Business
  **Published:** `13th February 2017`
  **NeKI brief:** There have been a few Interesting posts this week on making money without the MAS. First up is Paul Kafasis talking about sales figures after removing Piezo from the App Store. He also references Bogdan Popescu’s post on sales of Dash after it also left the…
- [Bogdan Popescu’s post](https://blog.kapeli.com/100-days-without-the-app-store) — iOS Dev Weekly · Issue 287 — Article · Topics: App Distribution & Store Operations · Developer Community & Business
  **Published:** `13th February 2017`
  **NeKI brief:** Discusses Bogdan Popescu’s post, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [70 Cents Put Me on the Mac App Store Charts](http://lapcatsoftware.com/articles/70cents.html) — iOS Dev Weekly · Issue 286 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `3rd February 2017`
  **NeKI brief:** This is an unbelievable story and just shows how top heavy the MAS has become. Is it time to call it a failure yet? I think it might be. Such a shame.
- [UK App Store prices to rise by >25%](https://9to5mac.com/2017/01/17/app-store-app-prices-to-rise-in-the-uk-by-25-following-brexit-exchange-rate-fluctuations) — iOS Dev Weekly · Issue 284 — Article · Topics: App Distribution & Store Operations
  **Published:** `20th January 2017`
  **NeKI brief:** Examines Apple is rising the prices for apps and in-app purchases in a few countries following changes to exchange rates and taxation policy,. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [All of 2016’s top mobile apps are owned by either Google or Facebook](https://medium.freecodecamp.com/all-of-2016s-top-mobile-apps-are-owned-by-either-google-or-facebook-a9c56d77a74b) — iOS Dev Weekly · Issue 282 — Article · Topics: App Distribution & Store Operations · Developer Community & Business
  **Published:** `6th January 2017`
  **NeKI brief:** The App Store may be breaking sales records, but where is all the money going? Quincy Larson with some analysis of the App Stores and what apps were most popular in 2016. The results are kinda shocking and while he stops short of declaring the App Stores…
- [Our Experience with App Store Search Ads](http://blog.supertop.co/post/153268162187/search-ads) — iOS Dev Weekly · Issue 277 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa · Testing
  **Published:** `18th November 2016`
  **NeKI brief:** Examines Apple started rolling out Search Ads on the U.S. App Store last month, offering developers and marketers an opportunity to promote their apps on the search screen of the iOS App St. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Senior Mobile Engineer, Credit Karma - San Francisco](https://www.creditkarma.com/careers) — iOS Dev Weekly · Issue 276 — Article · Topics: App Distribution & Store Operations · Developer Career & Practice
  **Published:** `11th November 2016`
  **NeKI brief:** 5 stars in the App Store, but our work has just begun. Come Join Us!
- [open source](https://github.com/hankinsoft/AppWage) — iOS Dev Weekly · Issue 275 — Source repository · Topics: App Distribution & Store Operations · Developer Community & Business · Developer Tools
  **Published:** `4th November 2016`
  **NeKI brief:** Examines Public issues tracker for AppWage app. Contribute to hankinsoft/AppWage development by creating an account on GitHub. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Dash](https://kapeli.com/dash) — iOS Dev Weekly · Issue 271 — Article · Topics: App Distribution & Store Operations
  **Published:** `7th October 2016`
  **NeKI brief:** The page documents Dash, the offline API documentation browser and code snippet manager, including its developer-oriented documentation workflow.
- [removed from the various App Stores](https://blog.kapeli.com/apple-removed-dash-from-the-app-store) — iOS Dev Weekly · Issue 271 — Article · Topics: App Distribution & Store Operations
  **Published:** `7th October 2016`
  **NeKI brief:** There’s been a lot of talk over the past couple of days around the fact that Dash has been removed from the various App Stores for allegedly manipulating its rating with fraudulent reviews.
- [post by Brent Simmons](http://inessential.com/2016/10/06/apples_judicial_system) — iOS Dev Weekly · Issue 271 — Article · Topics: App Distribution & Store Operations
  **Published:** `7th October 2016`
  **NeKI brief:** Will we ever find out what really happened? Probably not, but it’s a reminder who is in control of the App Store and how a single decision from someone inside Apple can potentially end your business. I think this post by Brent Simmons sums up how poor the…
- [Socking simians](http://www.allenpike.com/2016/socking-simians) — iOS Dev Weekly · Issue 271 — Article · Topics: App Distribution & Store Operations · Developer Community & Business
  **Published:** `7th October 2016`
  **NeKI brief:** Examines We buy some App Store Search Ads. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [iMessage App Store Already Tops 400 Apps and 1,250 Sticker Packs](https://sensortower.com/blog/imessage-app-store) — iOS Dev Weekly · Issue 270 — Article · Topics: App Distribution & Store Operations · Product Design
  **Published:** `30th September 2016`
  **NeKI brief:** Discusses iMessage App Store Already Tops 400 Apps and 1,250 Sticker Packs, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [The App Store Keyword Algorithm Update Takes Effect](http://incipia.co/post/mobile-app-marketing-industry-updates/the-app-store-keyword-algorithm-update-takes-effect) — iOS Dev Weekly · Issue 268 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `16th September 2016`
  **NeKI brief:** Explains The App Store Keyword Algorithm Update Takes Effect, focusing on the concrete iOS implementation technique and the trade-offs relevant to production applications.
- [The iMessage App Store: First Thoughts & Observations](http://www.futuretap.com/blog/the-imessage-app-store-first-thoughts-observations) — iOS Dev Weekly · Issue 268 — Article · Topics: App Distribution & Store Operations
  **Published:** `16th September 2016`
  **NeKI brief:** Ortwin Gentz with some commentary and stats from the iMessage app store. Obviously sticker packs dominate, and skew the numbers in terms of business models. But even so, paid up front is the most prevalent choice for apps too. I wonder how long that will…
- [Migrating Code Signing Configurations to Xcode 8](http://pewpewthespells.com/blog/migrating_code_signing.html) — iOS Dev Weekly · Issue 267 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web · Xcode
  **Published:** `9th September 2016`
  **NeKI brief:** Walks through iOS code signing, certificates, provisioning profiles, validation, and the migration from Xcode 7 signing methods to Xcode 8. Useful when supporting projects that combine automatic and manual signing across teams.
- [iOS Subscriptions Primer](https://blog.curtisherbert.com/ios-subscriptions-primer) — iOS Dev Weekly · Issue 267 — Article · Topics: App Distribution & Store Operations
  **Published:** `9th September 2016`
  **NeKI brief:** Shares implementation lessons from adding non-renewable and auto-renewable subscriptions, including StoreKit and receipt-validation concerns. Useful as a practical checklist for subscription flows, especially queue recovery and lifecycle edge cases.
- [Evolving App Store Business Models](https://david-smith.org/blog/2016/09/05/evolving-business-app-store-business-models) — iOS Dev Weekly · Issue 267 — Article · Topics: App Distribution & Store Operations
  **Published:** `9th September 2016`
  **NeKI brief:** Reviews how subscriptions, search ads, App Store cleanup, and metadata rules were changing the economics of independent iOS apps. Useful historical context for product decisions rather than a current pricing reference.
- [Official Swift Facebook SDK Beta](https://github.com/facebook/facebook-sdk-swift) — iOS Dev Weekly · Issue 260 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Swift
  **Published:** `22nd July 2016`
  **NeKI brief:** Explains Official Swift Facebook SDK Beta, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [Exploring the App Store’s Top Grossing Chart](https://www.macstories.net/stories/exploring-the-app-stores-top-grossing-chart) — iOS Dev Weekly · Issue 260 — Article · Topics: App Distribution & Store Operations
  **Published:** `22nd July 2016`
  **NeKI brief:** This is great analysis of the top grossing App Store charts by Graham Spencer. If you have ever doubted that freemium apps won the battle for the App Store, reading this will set you straight. There’s only 3 paid up front apps in the whole top 200. 😬
- [Code signing guides from fastlane](https://github.com/fastlane/fastlane/tree/master/fastlane/docs/Codesigning) — iOS Dev Weekly · Issue 258 — Source repository · Topics: App Distribution & Store Operations · CI/CD & Automation · Developer Tools
  **Published:** `8th July 2016`
  **NeKI brief:** Examines Code signing guides from fastlane, focusing on felix krause with a set of guides covering all things code signing. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Videos from Release Notes](https://releasenotes.tv/videos) — iOS Dev Weekly · Issue 257 — Article · Topics: App Distribution & Store Operations · Developer Community & Business · Graphics, Media & Games
  **Published:** `1st July 2016`
  **NeKI brief:** Examines Videos | Release Notes. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Release Notes](https://releasenotes.tv/conference) — iOS Dev Weekly · Issue 257 — Article · Topics: App Distribution & Store Operations · Developer Community & Business · Graphics, Media & Games
  **Published:** `1st July 2016`
  **NeKI brief:** Great set of videos from the Release Notes conference. Focused on the business side of the App Store rather than the technical, you’ll certainly find something to educate or inspire you here.
- [The New App Store](http://daringfireball.net/2016/06/the_new_app_store) — iOS Dev Weekly · Issue 254 — Article · Topics: App Distribution & Store Operations
  **Published:** `10th June 2016`
  **NeKI brief:** John Gruber with the best round up of the huge App Store changes which were announced on Wednesday. Subscription pricing is now available in all categories (although not for all apps). Faster app review is not a coincidence, and most apps will now be…
- [all apps](http://daringfireball.net/2016/06/app_store_subscription_uncertainty) — iOS Dev Weekly · Issue 254 — Article · Topics: App Distribution & Store Operations
  **Published:** `10th June 2016`
  **NeKI brief:** This article examines the uncertainty around App Store subscription behavior and Apple's evolving platform policies. It provides useful historical context for product and pricing decisions that depend on store rules rather than only on application code.
- [“Where’s the App for That?” – Fixing App Store Discovery](https://www.macstories.net/stories/wheres-the-app-for-that-fixing-app-store-discovery) — iOS Dev Weekly · Issue 254 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `10th June 2016`
  **NeKI brief:** Examines When the iPhone debuted in 2007, it was by no means a forgone conclusion that there would ever be an App Store. Steve Jobs reportedly resisted the idea over concerns that it would. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [How Apple is experimenting with tvOS top charts](http://blog.equinux.com/2016/05/apple-changes-apple-tv-os-top-charts-algorithm) — iOS Dev Weekly · Issue 253 — Article · Topics: App Distribution & Store Operations · Product Design · Testing
  **Published:** `3rd June 2016`
  **NeKI brief:** Examines It makes sense to do this kind of testing on the tvOS App Store as right now it’s smaller, and frankly less important than the main store. This seems like a very sensible change though. Along with the app review time cha Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [search problems](http://techcrunch.com/2016/05/05/apples-app-store-search-is-completely-broken-right-now) — iOS Dev Weekly · Issue 249 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa · Testing
  **Published:** `6th May 2016`
  **NeKI brief:** Analyzes problems with App Store search during an early period. Follow it for historical storefront and ranking context, while treating the reported behavior as version-specific.
- [tvOS at 6 Months: Where Are the Apps?](http://tidbits.com/article/16460) — iOS Dev Weekly · Issue 249 — Article · Topics: App Distribution & Store Operations
  **Published:** `6th May 2016`
  **NeKI brief:** Examines Six months in, the tvOS ecosystem feels a bit empty. “Take Control of Apple TV” author Josh Centers investigates to find out why. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Changes to the App Store review guidelines for CareKit and Apple Music](http://appstorereviewguidelineshistory.com/articles/2016-04-19-carekit-apple-music) — iOS Dev Weekly · Issue 247 — Article · Topics: App Distribution & Store Operations
  **Published:** `22nd April 2016`
  **NeKI brief:** Examines New Apple Music API section, CareKit and other updates - App Store Review Guidelines History. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [On paid App Store search results](https://marco.org/2016/04/21/paid-app-store-search) — iOS Dev Weekly · Issue 247 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `22nd April 2016`
  **NeKI brief:** Examines On paid App Store search results – Marco.org. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Paid Search for the App Store?](http://daringfireball.net/linked/2016/04/14/bloomberg-app-store-search) — iOS Dev Weekly · Issue 246 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `15th April 2016`
  **NeKI brief:** Examines Daring Fireball: Bloomberg: Apple Exploring Google-Like 'Paid Search' for App Store. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Masterclass: Code signing & Provisioning profiles](http://aplus.rs/2016/masterclass-code-signing) — iOS Dev Weekly · Issue 246 — Article · Topics: App Distribution & Store Operations · Performance
  **Published:** `15th April 2016`
  **NeKI brief:** Explains Masterclass Code signing Provisioning profiles with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Foldify](https://itunes.apple.com/gb/app/foldify-create-print-fold!/id1010882968?mt=8) — iOS Dev Weekly · Issue 243 — Article · Topics: App Distribution & Store Operations
  **Published:** `25th March 2016`
  **NeKI brief:** The App Store page publicly documents Foldify, including its product listing and app-store metadata.
- [Apple’s App Review Needs Big Improvements](https://www.macstories.net/stories/developers-apples-app-review-needs-big-improvements) — iOS Dev Weekly · Issue 240 — Article · Topics: App Distribution & Store Operations
  **Published:** `4th March 2016`
  **NeKI brief:** I touched on some of the problems with app review last week, but Graham Spencer published a much more comprehensive article a few days ago. Apparently the number one complaint was the speed of review, which I’m a little surprised about as it’s been quite…
- [animation engine](https://github.com/storehouse/Advance) — iOS Dev Weekly · Issue 240 — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **Published:** `4th March 2016`
  **NeKI brief:** The page covers “animation engine” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [presented one of two sets of functionality based on your location](http://researchcenter.paloaltonetworks.com/2016/02/pirated-ios-app-stores-client-successfully-evaded-apple-ios-code-review) — iOS Dev Weekly · Issue 239 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `26th February 2016`
  **NeKI brief:** Analyzes how iOS app-store piracy bypassed code review through location-dependent behavior. Follow it for concrete security and review-evasion lessons, while treating the historical incident as threat context.
- [App Store economics](https://marco.org/2016/02/01/parse-shutdown-neglected-apps) — iOS Dev Weekly · Issue 236 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `5th February 2016`
  **NeKI brief:** Discusses App Store economics, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [Fix Issue](https://vimeo.com/154148473) — iOS Dev Weekly · Issue 236 — Video · Topics: App Distribution & Store Operations · Graphics, Media & Games · Xcode
  **Published:** `5th February 2016`
  **NeKI brief:** Provides the linked Fix Issue video recording. Useful for following the original demonstration and speaker context, while treating it as supplementary material rather than maintained documentation.
- [Fixing the App Store purchasing problem](http://imore.com/fixing-app-store-purchasing-problem) — iOS Dev Weekly · Issue 232 — Article · Topics: App Distribution & Store Operations
  **Published:** `8th January 2016`
  **NeKI brief:** Rene Ritchie imagines a world where any iOS app can be bought from any device (including the web). I like the idea but my gut feeling is Apple have held back from this due to the potential confusion of purchasing apps for devices that the user doesn’t own…
- [Everything You Need To Know About the New Apple TV App Store](http://blog.appfigures.com/everything-you-need-to-know-about-the-new-apple-tv-app-store) — iOS Dev Weekly · Issue 228 — Article · Topics: App Distribution & Store Operations
  **Published:** `11th December 2015`
  **NeKI brief:** Examines App Store Optimization Guides and Mobile Industry news to help you grow your downloads. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [certainly causing problems](http://www.theverge.com/2015/11/19/9757516/ipad-pro-apps-pricing-ios-developers-opt-out) — iOS Dev Weekly · Issue 225 — Article · Topics: App Distribution & Store Operations
  **Published:** `20th November 2015`
  **NeKI brief:** Explains certainly causing problems with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [A Smarter Search Engine for the App Store](http://techcrunch.com/2015/11/13/app-store-search-just-got-smarter) — iOS Dev Weekly · Issue 225 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `20th November 2015`
  **NeKI brief:** Discusses A Smarter Search Engine for the App Store, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [XcodeGhost](http://researchcenter.paloaltonetworks.com/2015/09/novel-malware-xcodeghost-modifies-xcode-infects-apple-ios-apps-and-hits-app-store) — iOS Dev Weekly · Issue 217 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa · Xcode
  **Published:** `25th September 2015`
  **NeKI brief:** Explains XcodeGhost with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [source has also been uploaded to GitHub](https://github.com/XcodeGhostSource/XcodeGhost) — iOS Dev Weekly · Issue 217 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · Xcode
  **Published:** `25th September 2015`
  **NeKI brief:** The page covers “source has also been uploaded to GitHub” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Avoid the Feature](https://500ish.com/avoid-the-feature-f031a42e9e71) — iOS Dev Weekly · Issue 212 — Article · Topics: App Distribution & Store Operations
  **Published:** `21st August 2015`
  **NeKI brief:** M. G. Siegler questions whether a prominent App Store feature benefits a newly launched product, especially a v1 app. It is a cautionary product-distribution perspective on sudden attention and operational readiness.
- [iOS/Mac Developers at Itty Bitty Apps - Melbourne, Australia](http://www.ittybittyapps.com/workwithus) — iOS Dev Weekly · Issue 212 — Article · Topics: App Distribution & Store Operations
  **Published:** `21st August 2015`
  **NeKI brief:** Explains iOS/Mac Developers at Itty Bitty Apps - Melbourne, Australia, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [disabled again](http://9to5mac.com/2015/08/13/ios-9-testflight) — iOS Dev Weekly · Issue 211 — Article · Topics: App Distribution & Store Operations · Testing
  **Published:** `14th August 2015`
  **NeKI brief:** Explains disabled again, focusing on the concrete UIKit or iOS implementation technique and the trade-offs relevant to production apps.
- [watchOS 2 apps can now be uploaded and distributed to internal testers](http://www.macstories.net/news/apple-updates-testflight-app-with-support-for-ios-9-and-watchos-2-betas-app-thinning) — iOS Dev Weekly · Issue 210 — Article · Topics: App Distribution & Store Operations · Testing
  **Published:** `7th August 2015`
  **NeKI brief:** We’re probably 5-6 weeks out from a final iOS 9/watchOS 2 release and while we haven’t yet got TestFlight support for iOS 9, watchOS 2 apps can now be uploaded and distributed to internal testers. I’d expect to see full iOS 9 support added very shortly…
- [iOS Build Infrastructure at Square](https://corner.squareup.com/2015/07/ios-build-infrastructure.html) — iOS Dev Weekly · Issue 209 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `31st July 2015`
  **NeKI brief:** You just hit the play button, right? 😎 Interesting article from Michael Tauraso on how Square use Jenkins and other tools to get both their App Store and internal apps built and shipped.
- [Apple Disables App Store Reviews From Devices Running iOS 9](http://www.macrumors.com/2015/07/22/ios-9-beta-app-store-reviews-disabled) — iOS Dev Weekly · Issue 208 — Article · Topics: App Distribution & Store Operations · Personal Essays
  **Published:** `24th July 2015`
  **NeKI brief:** Wha-hey! I’m certain my comment last week had nothing to do with this but I’m really glad to see the change made. Feels like I should end this one with… Finally!
- [Pilot and Boarding](https://github.com/fastlane/pilot) — iOS Dev Weekly · Issue 208 — Source repository · Topics: CI/CD & Automation · Developer Tools · Testing
  **Published:** `24th July 2015`
  **NeKI brief:** Examines The best way to manage your TestFlight testers and builds from your terminal - fastlane-old/pilot. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Boarding](https://github.com/fastlane/boarding) — iOS Dev Weekly · Issue 208 — Source repository · Topics: CI/CD & Automation · Developer Tools · Testing
  **Published:** `24th July 2015`
  **NeKI brief:** Examines Instantly create a simple signup page for TestFlight beta testers - fastlane/boarding. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [thoughts on automation](https://krausefx.com/blog/letting-computers-do-the-hard-work) — iOS Dev Weekly · Issue 208 — Article · Topics: CI/CD & Automation · Testing
  **Published:** `24th July 2015`
  **NeKI brief:** The page covers “thoughts on automation” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Half-Assed](http://furbo.org/2015/07/22/half-assed) — iOS Dev Weekly · Issue 208 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games · Product Design
  **Published:** `24th July 2015`
  **NeKI brief:** Discusses Half-Assed, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [worth a read](http://bitsplitting.org/2015/07/23/six-in-one) — iOS Dev Weekly · Issue 208 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games · Product Design
  **Published:** `24th July 2015`
  **NeKI brief:** Examines Craig Hockenberry's "Half-Assed" calls out the disparity between Apple's Mac and iOS App Stores with respect to app analytics, limiting customer reviews from be. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [On Negative App Store Reviews During Betas of iOS and OS X](http://www.macstories.net/stories/on-negative-app-store-reviews-during-betas-of-ios-and-os-x) — iOS Dev Weekly · Issue 207 — Article · Topics: App Distribution & Store Operations
  **Published:** `17th July 2015`
  **NeKI brief:** The page covers “On Negative App Store Reviews During Betas of iOS and OS X” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Creating perfect App Store Screenshots](https://krausefx.com/blog/creating-perfect-app-store-screenshots-of-your-ios-app) — iOS Dev Weekly · Issue 206 — Article · Topics: App Distribution & Store Operations · Localization
  **Published:** `10th July 2015`
  **NeKI brief:** Felix Krause with a write up of the process of screenshot automation for the App Store. With multiple device resolutions, or if you do any kind of localisation, then you should be considering automation. This detailed guide will take you through how to get…
- [Sparkler](https://github.com/mackuba/sparkler) — iOS Dev Weekly · Issue 198 — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **Published:** `15th May 2015`
  **NeKI brief:** Presents Sparkler, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Sparkle](https://github.com/sparkle-project/Sparkle) — iOS Dev Weekly · Issue 198 — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **Published:** `15th May 2015`
  **NeKI brief:** Sparkle provides signed software-update delivery for macOS applications, including feed handling and installer integration. Useful for studying a mature update channel and the security responsibilities around release signatures and keys.
- [WatchScreenshotMagic](https://github.com/Imperiopolis/WatchScreenshotMagic) — iOS Dev Weekly · Issue 198 — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **Published:** `15th May 2015`
  **NeKI brief:** As you may remember, I’m a big fan of perfect status bars in App Store screenshots 😀 but until now there was no easy way to add one to a watch screenshot. Luckily this tool now exists and can remove the charging indicator, add the standard time of 10:09 and…
- [compiled and simulated](http://techcrunch.com/2015/04/29/microsoft-makes-it-easier-for-developers-to-bring-their-android-and-ios-apps-to-windows-10) — iOS Dev Weekly · Issue 196 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `1st May 2015`
  **NeKI brief:** Explains compiled and simulated, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [The Plying Game](http://www.macworld.com/article/2905352/the-plying-game-an-inside-look-at-the-voracious-and-insatiable-world-of-app-store-reviews.html) — iOS Dev Weekly · Issue 192 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web · Graphics, Media & Games
  **Published:** `3rd April 2015`
  **NeKI brief:** Examines Michael Simon with a look at the ups and downs (OK, mainly downs) of the rating and review system on the App Store. Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Regarding the App Store Revenue Split](http://blog.anylistapp.com/2015/02/open-letter-to-tim-cook-regarding-app-store-revenue-split) — iOS Dev Weekly · Issue 186 — Article · Topics: App Distribution & Store Operations
  **Published:** `20th February 2015`
  **NeKI brief:** This open letter discusses a proposed graduated App Store revenue split for smaller developers rather than an immediate standard commission. It provides historical context for the business constraints that shape independent iOS product planning.
- [App Developer Friends: Try TestFlight](http://blog.supertop.co/post/108759935377) — iOS Dev Weekly · Issue 182 — Article · Topics: Testing
  **Published:** `23rd January 2015`
  **NeKI brief:** Explains App Developer Friends: Try TestFlight, focusing on the concrete UIKit or iOS implementation technique and the trade-offs relevant to production apps.
- [A better App Store Pricing Matrix](http://www.equinux.com/us/appdevelopers/pricematrix.html) — iOS Dev Weekly · Issue 181 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web · Product Design
  **Published:** `16th January 2015`
  **NeKI brief:** The page presents an App Store pricing matrix for developers and explains the price-point structure used when setting application prices.
- [rollout was a bit rocky](http://www.todaysiphone.com/2015/01/european-app-store-price-changes-underway-things-arent-running-smoothly) — iOS Dev Weekly · Issue 180 — Article · Topics: App Distribution & Store Operations · Personal Essays
  **Published:** `9th January 2015`
  **NeKI brief:** So last night saw the adjustment to non-US App Store prices that was announced earlier this week. The new prices take into account the new VAT rules and various changes to adjust for fluctuating exchange rates. However, the rollout was a bit rocky with weird…
- [App Store and Digital Purchase Refunds](http://www.theverge.com/2014/12/30/7468573/apple-14-day-return-period-allowed-in-eu-countries) — iOS Dev Weekly · Issue 179 — Article · Topics: App Distribution & Store Operations · Developer Tools
  **Published:** `2nd January 2015`
  **NeKI brief:** As I understood it, the existing 90 day returns policy for apps didn’t ask very many questions before granting a refund so I’m not sure this news is as huge as the media is making it out to be. Regardless, in the EU there is now a blanket, no questions asked…
- [EU VAT Legislation and the App Store](http://oleb.net/blog/2014/07/eu-vat-changes-2015) — iOS Dev Weekly · Issue 177 — Article · Topics: App Distribution & Store Operations
  **Published:** `19th December 2014`
  **NeKI brief:** Explains EU VAT changes affecting software sales and app businesses. Follow it for historical commercial and compliance context, not for technical implementation guidance.
- [How Broken is Discovery on the App Store? This Broken.](http://gedblog.com/2014/12/15/how-broken-is-discovery-on-the-app-store-this-broken) — iOS Dev Weekly · Issue 177 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa · Product Design
  **Published:** `19th December 2014`
  **NeKI brief:** Examines How Broken is Discovery on the App Store? This Broken. | gedblog. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [not only about search, but app discovery](http://aplus.rs/2014/few-proposal-for-better-app-store) — iOS Dev Weekly · Issue 177 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa · Product Design
  **Published:** `19th December 2014`
  **NeKI brief:** Examines Few proposals for better App Store · aplus.rs. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [tough week for the App Store](http://mjtsai.com/blog/2014/12/09/out-of-touch) — iOS Dev Weekly · Issue 176 — Article · Topics: App Distribution & Store Operations
  **Published:** `12th December 2014`
  **NeKI brief:** Examines Michael Tsai - Blog - Out of Touch. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [PDFpen Paid Upgrade Path](http://tidbits.com/article/15277) — iOS Dev Weekly · Issue 176 — Article · Topics: App Distribution & Store Operations
  **Published:** `12th December 2014`
  **NeKI brief:** Explains the upgrade path for a paid Mac application distributed through the App Store. Follow it for concrete pricing and migration considerations, while treating the historical policy context as dated.
- [The Forgotten Shores of App Store Pricing](http://sixcolors.com/post/2014/11/the-forgotten-shores-of-app-store-pricing) — iOS Dev Weekly · Issue 173 — Article · Topics: App Distribution & Store Operations
  **Published:** `21st November 2014`
  **NeKI brief:** Discusses The Forgotten Shores of App Store Pricing, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [FrameIt](https://github.com/KrauseFx/frameit) — iOS Dev Weekly · Issue 172 — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **Published:** `14th November 2014`
  **NeKI brief:** Examines Quickly put your screenshots into the right device frames - fastlane-old/frameit. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [builds can also be uploaded with iTMSTransporter as well](https://devforums.apple.com/message/1049285) — iOS Dev Weekly · Issue 170 — Article · Topics: Testing
  **Published:** `31st October 2014`
  **NeKI brief:** Explains builds can also be uploaded with iTMSTransporter as well with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS.
- [FAQ](https://www.rollout.io/faq) — iOS Dev Weekly · Issue 170 — Article · Topics: App Distribution & Store Operations
  **Published:** `31st October 2014`
  **NeKI brief:** Presents FAQ, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [BBEdit is leaving the Mac App Store](http://sixcolors.com/post/2014/10/bbedit-at-max-q) — iOS Dev Weekly · Issue 168 — Article · Topics: App Distribution & Store Operations
  **Published:** `17th October 2014`
  **NeKI brief:** Discusses BBEdit is leaving the Mac App Store, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [Panic making the same decision with Coda](http://www.panic.com/blog/coda-2-5-and-the-mac-app-store) — iOS Dev Weekly · Issue 168 — Article · Topics: App Distribution & Store Operations
  **Published:** `17th October 2014`
  **NeKI brief:** With the announcement that BBEdit is leaving the Mac App Store at Çingleton last weekend and Panic making the same decision with Coda a few months ago it has to be time for another look at what could be improved. Milen Dzhumerov does the honours.
- [How “Complete My Bundle” Pricing Works](http://www.panic.com/blog/how-complete-my-bundle-pricing-works) — iOS Dev Weekly · Issue 168 — Article · Topics: App Distribution & Store Operations
  **Published:** `17th October 2014`
  **NeKI brief:** Examines After the launch of App Store Bundles with iOS 8, some developers started seeing some unusual pricing popping up as users went to use the feature. After some investigation, Cabel Sasser has all the details on exactly how Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [pulling of all HealthKit apps due to a bug](http://www.theguardian.com/technology/2014/sep/18/apple-healthkit-bug-ios-8) — iOS Dev Weekly · Issue 164 — Article · Topics: App Distribution & Store Operations · Health Apps
  **Published:** `19th September 2014`
  **NeKI brief:** Examines Health and fitness-tracking app updates pulled, with cure expected by the end of September. By <strong>Stuart Dredge</strong>. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [App Store Review Guidelines Updated to Consider New iOS 8 Features](http://www.macstories.net/news/app-store-review-guidelines-updated-to-consider-new-ios-8-features) — iOS Dev Weekly · Issue 162 — Article · Topics: App Distribution & Store Operations · Hardware & Devices
  **Published:** `5th September 2014`
  **NeKI brief:** Reports historical App Store review-guideline changes related to iOS 8 features. Useful for policy history and release-era context, not as a substitute for Apple’s current guidelines.
- [new iTunes Connect](http://www.macstories.net/news/apple-updates-itunes-connect-design-rolls-out-testflight-app) — iOS Dev Weekly · Issue 162 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games · Testing
  **Published:** `5th September 2014`
  **NeKI brief:** Discusses new iTunes Connect, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [App Store Longevity and Freshness](http://david-smith.org/blog/2014/08/04/app-store-longevity-and-freshness) — iOS Dev Weekly · Issue 158 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `8th August 2014`
  **NeKI brief:** Examines App Store Longevity and Freshness - David Smith, Independent iOS Developer. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Killer user onboarding starts with a story](http://insideintercom.io/killer-user-onboarding-starts-with-a-story) — iOS Dev Weekly · Issue 158 — Article · Topics: App Distribution & Store Operations
  **Published:** `8th August 2014`
  **NeKI brief:** So if making money is hard on the App Store, let’s learn how to do it properly. The first few minutes inside your app are absolutely critical in terms of ensuring a user launches your app again. In this article, Samuel Hulick takes a look at some of the…
- [Nobility of Effort](http://developingperspective.com/2014/07/30/192) — iOS Dev Weekly · Issue 157 — Article · Topics: App Distribution & Store Operations
  **Published:** `1st August 2014`
  **NeKI brief:** Examines #192: Nobility of Effort. July 30th, 2014 Download MP3 This past week has seen an explosion of writing and discussion about the business of making …. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Startup Launch from Google](http://www.loopinsight.com/2014/07/29/google-woos-select-developers-with-startup-launch) — iOS Dev Weekly · Issue 157 — Article · Topics: App Distribution & Store Operations
  **Published:** `1st August 2014`
  **NeKI brief:** Examines Google woos select developers with Startup Launch. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [A Deep Dive Into App Store Reviews Distribution](http://blog.appfigures.com/a-deep-dive-into-app-store-reviews-distribution) — iOS Dev Weekly · Issue 152 — Article · Topics: App Distribution & Store Operations
  **Published:** `27th June 2014`
  **NeKI brief:** Discusses A Deep Dive Into App Store Reviews Distribution, connecting the concrete app-design or distribution decision to practical considerations for Apple-platform developers.
- [Bitcoin back in the iOS App Store](http://www.loopinsight.com/2014/06/16/bitcoin-back-in-the-ios-app-store) — iOS Dev Weekly · Issue 151 — Article · Topics: App Distribution & Store Operations · Developer Community & Business
  **Published:** `20th June 2014`
  **NeKI brief:** Examines Bitcoin back in the iOS App Store. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [App Store Bundles as an Upgrade Path](https://michelf.ca/blog/2014/bundle-upgrade-path) — iOS Dev Weekly · Issue 151 — Article · Topics: App Distribution & Store Operations · Developer Community & Business
  **Published:** `20th June 2014`
  **NeKI brief:** Michel Fortin on using the new iOS 8 app bundles to hack some sort of upgrade pricing. It’s an interesting idea but I can see all sorts of confusion with this. From having to leave your old version on sale, to customers mistakenly buying the bundle without…
- [What Developers Should Know About Apple’s TestFlight](http://www.neglectedpotential.com/2014/06/testflight) — iOS Dev Weekly · Issue 150 — Article · Topics: App Distribution & Store Operations · Testing
  **Published:** `13th June 2014`
  **NeKI brief:** The article explains what developers should know about Apple's TestFlight beta-distribution service and its practical workflow.
- [Apple Expanding Curation To More European App Store Categories](http://www.macstories.net/news/apple-expanding-curation-to-more-european-app-store-categories) — iOS Dev Weekly · Issue 150 — Article · Topics: App Distribution & Store Operations
  **Published:** `13th June 2014`
  **NeKI brief:** Discusses Apple Expanding Curation To More European App Store Categories, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [Clarification on Beta App Review](http://oleb.net/blog/2014/06/testflight-beta-builds-app-review) — iOS Dev Weekly · Issue 149 — Article · Topics: App Distribution & Store Operations · Testing
  **Published:** `6th June 2014`
  **NeKI brief:** Ole Begemann (again!) on the new TestFlight service which is going to go live later in the year. Provisioning for beta has been a huge issue for a long time now and it looks like Apple have fixed the vast majority of complaints with these changes (along with…
- [Screenshot](http://xkcd.com/1373) — iOS Dev Weekly · Issue 148 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `30th May 2014`
  **NeKI brief:** Examines xkcd: Screenshot. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Possibility of Promo Codes for IAPs through App Store Code Program](http://9to5mac.com/2014/05/15/apple-opening-up-app-store-promo-codes-to-in-app-purchases) — iOS Dev Weekly · Issue 146 — Article · Topics: App Distribution & Store Operations
  **Published:** `16th May 2014`
  **NeKI brief:** Reports early signs that Apple might enable promo codes for in-app purchases, a limitation that had led developers to build redemption workarounds. Historical context for App Store promotion tooling.
- [Jack](http://apps.chbeer.de/jack) — iOS Dev Weekly · Issue 143 — Article · Topics: App Distribution & Store Operations
  **Published:** `25th April 2014`
  **NeKI brief:** Examines Compose and upload your iOS and/or OS X app. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [a year or so ago](http://www.theverge.com/2013/5/14/4329042/google-play-lets-all-developers-respond-to-user-reviews) — iOS Dev Weekly · Issue 143 — Article · Topics: App Distribution & Store Operations
  **Published:** `25th April 2014`
  **NeKI brief:** Google Play added the ability for developers to be able to respond to app reviews a year or so ago and now Microsoft are experimenting with the same functionality. From a quick look at the Google Play store this feature either isn’t very widely used, or the…
- [Towards a Better App Store](http://david-smith.org/blog/2014/04/16/towards-a-better-app-store) — iOS Dev Weekly · Issue 143 — Podcast · Topics: App Distribution & Store Operations · Developer Community & Business
  **Published:** `25th April 2014`
  **NeKI brief:** This article proposes ways the App Store could improve discovery and better connect users with suitable apps. It is useful for considering the interaction between search, curation, ranking, and the product decisions available to independent iOS developers.
- [1](http://developingperspective.com/2014/02/27/0) — iOS Dev Weekly · Issue 143 — Podcast · Topics: App Distribution & Store Operations · Developer Community & Business
  **Published:** `25th April 2014`
  **NeKI brief:** Examines #175: Towards a Better App Store: Part 1 February 27th, 2014 Download MP3 This begins a multi-part series on how I think we could move the App Store …. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [2](http://developingperspective.com/2014/03/06/176) — iOS Dev Weekly · Issue 143 — Podcast · Topics: App Distribution & Store Operations · Developer Community & Business
  **Published:** `25th April 2014`
  **NeKI brief:** Examines #176: Make it up in Volume March 6th, 2014 Download MP3 Towards a Better App Store: Part 2 Make it up in Volume This is Part 2 of an ongoing series …. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [3](http://developingperspective.com/2014/03/13/177) — iOS Dev Weekly · Issue 143 — Podcast · Topics: App Distribution & Store Operations · Developer Community & Business
  **Published:** `25th April 2014`
  **NeKI brief:** Discusses 3, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [4](http://developingperspective.com/2014/03/27/178) — iOS Dev Weekly · Issue 143 — Podcast · Topics: App Distribution & Store Operations · Developer Community & Business
  **Published:** `25th April 2014`
  **NeKI brief:** This article discusses a specific proposed direction for improving the App Store and the trade-offs it would create for developers and users. It is useful historical context for evaluating discovery and distribution outside implementation-level code concerns.
- [5](http://developingperspective.com/2014/04/11/180) — iOS Dev Weekly · Issue 143 — Podcast · Topics: App Distribution & Store Operations · Developer Community & Business
  **Published:** `25th April 2014`
  **NeKI brief:** David Smith has been detailing his thoughts on how to improve the App Store in a five part podcast (1, 2, 3, 4, 5) recently and now that the discussion on the podcast is wrapped up he has summarised his thoughts in this blog post. His conclusions are mainly…
- [Apple Claims Mogenerator’s Methods](http://rentzsch.tumblr.com/post/82453434093/apple-claims-mogenerators-methods) — iOS Dev Weekly · Issue 142 — Article · Topics: App Distribution & Store Operations
  **Published:** `18th April 2014`
  **NeKI brief:** Examines When generating class files to represent your data model's entities, mogenerator writes a few convenience class methods for you: + (id)insertInManagedObjectContext:(NSManagedO. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [New App Store Rules around Ad Identifier](http://techcrunch.com/2014/04/11/apple-developers-must-now-agree-to-ad-identifier-rules-or-risk-app-store-rejection) — iOS Dev Weekly · Issue 142 — Article · Topics: App Distribution & Store Operations
  **Published:** `18th April 2014`
  **NeKI brief:** This week Apple also added new screens to the iTunes Connect submission process when preparing an app for upload. You will be prompted to declare whether you are using the Advertising Identifier, explain why and finally make a declaration that you are not…
- [John Chaffee also talked at the same meeting about the Mac App Store](http://vimeo.com/91584758) — iOS Dev Weekly · Issue 141 — Video · Topics: App Distribution & Store Operations · Graphics, Media & Games · Xcode
  **Published:** `11th April 2014`
  **NeKI brief:** Ken Case talking at the Seattle Xcoders meeting from earlier this year about all aspects of upgrade pricing. The talk focuses on the Mac App Store specifically but much of it is relevant in a wider context of App Store pricing in general. John Chaffee also…
- [QuickTime Banned From Mac App Store](http://mjtsai.com/blog/2014/04/01/quicktime-banned-from-mac-app-store) — iOS Dev Weekly · Issue 140 — Article · Topics: App Distribution & Store Operations
  **Published:** `4th April 2014`
  **NeKI brief:** Examines Michael Tsai sums up the details of Drew McCormack’s recent rejection for using QTKit in an app. It seems really soon to start rejecting apps that use an API that was deprecated less than 6 months ago and this causes big Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [amazing work](http://techcrunch.com/2014/03/26/monument-valley-price-and-launch-date) — iOS Dev Weekly · Issue 139 — Tutorial · Topics: App Distribution & Store Operations · Developer Community & Business
  **Published:** `28th March 2014`
  **NeKI brief:** Examines Monument Valley, the much anticipated iPad and mobile game from London app & design studio ustwo (maker of the late lamented antisocial photo-sharing app Rando), will be launch. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Apple scoops up Burstly, owner of TestFlight](http://www.macworld.com/article/2099906/apple-scoops-up-burstly-owner-of-testflight-beta-testing-platform.html) — iOS Dev Weekly · Issue 135 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web · Testing
  **Published:** `28th February 2014`
  **NeKI brief:** The Macworld article reports Apple's acquisition of Burstly, the company behind the TestFlight beta-testing platform.
- [The Effective Way to Ask for an App Review](http://blog.supertop.co/post/77962740329/the-effective-way-to-ask-for-an-app-review) — iOS Dev Weekly · Issue 135 — Article · Topics: App Distribution & Store Operations
  **Published:** `28th February 2014`
  **NeKI brief:** John Gruber linked to the Threes update notes which suggested that nicely asking for a review in the release notes of your app would be a much more tolerable solution to the problem of getting ratings than an alert view. Oisin Prendiville and Padraig Kennedy…
- [iTunes Connect update to Sales and Trends](http://9to5mac.com/2014/02/17/itunes-connect-update-brings-modernized-look-sales-breakdowns-by-category-region-and-more) — iOS Dev Weekly · Issue 134 — Article · Topics: App Distribution & Store Operations · Developer Community & Business
  **Published:** `21st February 2014`
  **NeKI brief:** Reports Apple's overhaul of iTunes Connect Sales and Trends, adding clearer regional and category breakdowns to an area where developers had relied on third-party analytics. Historical App Store business tooling context.
- [Threes gives you cuteness where you least expect it](http://www.avclub.com/article/the-iphone-hit-threes-gives-you-cuteness-where-you-201293) — iOS Dev Weekly · Issue 134 — Tutorial · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `21st February 2014`
  **NeKI brief:** Examines The A.V. Club digs deep into film, TV, music, games, books and more. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Apple to refund $32.5m to parents whose kids made in-app purchases](http://bbc.co.uk/news/technology-25748292) — iOS Dev Weekly · Issue 129 — Article · Topics: App Distribution & Store Operations
  **Published:** `17th January 2014`
  **NeKI brief:** Interesting to note that this didn’t go to a court case but was settled. Looking back not just at this case but over the full history of the operating system I would imagine that Apple regret adding that 15 minute purchase permission time window as it has…
- [Apple’s App Store Rules on Data Collection and Privacy](http://oleb.net/blog/2013/12/app-store-rules-on-data-collection-and-privacy) — iOS Dev Weekly · Issue 128 — Article · Topics: App Distribution & Store Operations · Security & Privacy
  **Published:** `10th January 2014`
  **NeKI brief:** Examines If your app collects usage stats and sends them to your own servers or a third-party service, you should make sure to comply with Apple. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Silhouette](https://github.com/fraserhess/silhouette) — iOS Dev Weekly · Issue 127 — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **Published:** `3rd January 2014`
  **NeKI brief:** Examines Sparkle profiling for the Mac App Store. Contribute to fraserhess/silhouette development by creating an account on GitHub. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [My “Doom” 20th Anniversary Stories](http://blog.wilshipley.com/2013/12/my-doom-20th-anniversary-stories.html?m=1) — iOS Dev Weekly · Issue 125 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `20th December 2013`
  **NeKI brief:** Dan Counsell with an excellent article on optimising your app store listing for search and discoverability. This is a tricky subject which attracts lots of misinformation but Dan cuts through it all to give a clear and sensible set of tips on getting your…
- [Why I Don’t Recommend Auto-Renewable Subscriptions](http://www.marco.org/2013/12/02/auto-renewable-subscriptions) — iOS Dev Weekly · Issue 123 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `6th December 2013`
  **NeKI brief:** Marco Arment on the (non-technical) difficulties of Apple’s renewable subscription In-App Purchases. His solution? Just do it yourself, use a single non-renewable subscription and then prompt the user again when it expires. From a purely consumer…
- [To Annotate App Store Screenshots or Not](http://iphoneincubator.com/blog/app-store/to-annotate-app-store-screenshots-or-not) — iOS Dev Weekly · Issue 122 — Article · Topics: App Distribution & Store Operations
  **Published:** `29th November 2013`
  **NeKI brief:** Examines To Annotate App Store Screenshots or Not » The App Business Blog. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Video Trailers Debut On The App Store With ‘Clumsy Ninja’](http://www.macstories.net/news/video-trailers-debut-on-the-app-store-with-clumsy-ninja) — iOS Dev Weekly · Issue 121 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `22nd November 2013`
  **NeKI brief:** Looks like it’s a special case and is only enabled for this one app right now but Apple have to be looking to roll this out for everyone in the future. This is a huge deal for App Store listings.
- [Five Years in the App Store](http://david-smith.org/blog/2013/11/08/five-years-in-the-app-store) — iOS Dev Weekly · Issue 120 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `15th November 2013`
  **NeKI brief:** This retrospective reflects on five years of building and selling apps through the App Store. It offers an experienced independent-developer perspective on product iteration, platform dependence, and the long-term business realities behind iOS software.
- [A Quick Look plug-in for Provisioning](http://furbo.org/2013/11/02/a-quick-look-plug-in-for-provisioning) — iOS Dev Weekly · Issue 119 — Article · Topics: App Distribution & Store Operations
  **Published:** `8th November 2013`
  **NeKI brief:** Shows a Quick Look plug-in for inspecting provisioning profiles, making signing metadata easier to examine outside Xcode. Useful for diagnosing provisioning mismatches and understanding what information is embedded in a profile.
- [Apple Advertising System Apps and Features in App Store Search Results](http://www.macstories.net/news/apple-advertising-system-apps-and-features-in-app-store-search-results) — iOS Dev Weekly · Issue 118 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `1st November 2013`
  **NeKI brief:** Seems like there has been a small update to searching on the App Store this week with Apple’s bundled apps now showing up for common search terms. It seems obvious to those of us who use iOS every day as developers that these apps exist but just last week I…
- [Customizing the Navigation and Status Bar in iOS 7](http://www.appcoda.com/customize-navigation-status-bar-ios-7) — iOS Dev Weekly · Issue 118 — Article · Topics: App Distribution & Store Operations
  **Published:** `1st November 2013`
  **NeKI brief:** Explains Customizing the Navigation and Status Bar in iOS 7 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS.
- [Apportable](http://www.youtube.com/watch?v=dSkhtd6L8RM) — iOS Dev Weekly · Issue 117 — Video · Topics: App Services & Extensions · Core Data · Cross-Platform & Web
  **Published:** `25th October 2013`
  **NeKI brief:** Demonstrates compiling an Objective-C iOS game for Android with Apportable and SpriteBuilder, including platform-framework mapping. Treat it as historical cross-platform tooling context rather than a current deployment recommendation.
- [Mac App Store Receipts and Mavericks](http://furbo.org/2013/10/21/mac-app-store-receipts-and-mavericks) — iOS Dev Weekly · Issue 117 — Article · Topics: App Distribution & Store Operations
  **Published:** `25th October 2013`
  **NeKI brief:** This post investigates Mac App Store receipt behavior around Mavericks and the validation assumptions developers had to make at the time. It offers historical context for designing entitlement and receipt checks that tolerate platform-version differences.
- [Code Signing and Mavericks](http://furbo.org/2013/10/17/code-signing-and-mavericks) — iOS Dev Weekly · Issue 116 — Article · Topics: App Distribution & Store Operations
  **Published:** `18th October 2013`
  **NeKI brief:** Explains Code Signing and Mavericks with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [An Interesting iOS App Store Upgrade Example](http://www.macdrifter.com/2013/10/an-interesting-ios-app-store-upgrade-example.html) — iOS Dev Weekly · Issue 116 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `18th October 2013`
  **NeKI brief:** Examines An Interesting iOS App Store Upgrade Example - Macdrifter. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Real World Price Dynamics](http://developingperspective.com/2013/09/27/app-store-pricing) — iOS Dev Weekly · Issue 114 — Article · Topics: App Distribution & Store Operations
  **Published:** `4th October 2013`
  **NeKI brief:** Discusses Real World Price Dynamics, connecting the concrete app-design or distribution decision to practical considerations for Apple-platform developers.
- [UK’s Office of Fair Trading releases report into children’s apps](http://appsplayground.com/2013/09/25/uks-office-fair-trading-releases-report-childrens-apps) — iOS Dev Weekly · Issue 113 — Article · Topics: App Distribution & Store Operations
  **Published:** `27th September 2013`
  **NeKI brief:** Examines Earlier this year, the UK. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Clearly We Have a Problem](http://512pixels.net/2013/09/clearly-we-have-a-problem) — iOS Dev Weekly · Issue 113 — Article · Topics: App Distribution & Store Operations · Testing
  **Published:** `27th September 2013`
  **NeKI brief:** Stephen Hackett examines the fallout from Clear's upgrade and pricing transition, including the difficulty of sustaining an App Store business across new app versions. It is historical product-business context for paid-upgrade decisions.
- [RMStore](https://github.com/robotmedia/RMStore) — iOS Dev Weekly · Issue 111 — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **Published:** `13th September 2013`
  **NeKI brief:** Provides the RMStore source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [OmniKeyMaster: Upgrade Pricing for Mac App Store Customers](http://www.omnigroup.com/blog/entry/omnikeymaster-upgrade-pricing-for-mac-app-store-customers) — iOS Dev Weekly · Issue 109 — Article · Topics: App Distribution & Store Operations
  **Published:** `30th August 2013`
  **NeKI brief:** Examines The most disappointing thing to me about this article is the entire premise of the article is based around moving people off the Mac App Store. I love the convenience and licensing terms of the Mac App Store so much, I w Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [A very mild defense of in-app purchases](http://verynicewebsite.net/2013/08/a-very-mild-defense-of-in-app-purchases) — iOS Dev Weekly · Issue 108 — Article · Topics: App Distribution & Store Operations
  **Published:** `23rd August 2013`
  **NeKI brief:** The article presents a considered defense of in-app purchases and discusses their role in mobile-app product and business design.
- [New App Store Review Guidelines](http://www.macrumors.com/2013/08/14/apple-releases-new-app-store-review-guidelines-with-updated-info-kids-apps-gambling-app-rules) — iOS Dev Weekly · Issue 107 — Article · Topics: App Distribution & Store Operations
  **Published:** `16th August 2013`
  **NeKI brief:** Explains New App Store Review Guidelines with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Searching the Curatorium](http://www.allenpike.com/2013/searching-the-curatorium) — iOS Dev Weekly · Issue 105 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `2nd August 2013`
  **NeKI brief:** Examines We search Twitter on the App Store. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [iOS Blur](https://github.com/JagCesar/iOS-blur) — iOS Dev Weekly · Issue 105 — Source repository · Topics: App Distribution & Store Operations · Developer Tools · UIKit
  **Published:** `2nd August 2013`
  **NeKI brief:** Provides the iOS Blur source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Honest In-App Purchases](http://david-smith.org/blog/2013/07/23/honest-consumable-in-app-purchases) — iOS Dev Weekly · Issue 104 — Article · Topics: App Distribution & Store Operations
  **Published:** `26th July 2013`
  **NeKI brief:** Explains how consumable in-app purchases can be made honest by separating entitlement, purchase state, and restoration. Follow it for concrete StoreKit product and transaction reasoning, while checking current StoreKit APIs.
- [Apple’s Answer on Upgrade Pricing](http://david-smith.org/blog/2013/07/16/apples-answer-on-upgrade-pricing) — iOS Dev Weekly · Issue 103 — Article · Topics: App Distribution & Store Operations
  **Published:** `19th July 2013`
  **NeKI brief:** Examines Apple's Answer on Upgrade Pricing - David Smith, Independent iOS Developer. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Get rid of the App Store charts](http://iphoneincubator.com/blog/app-store/john-august-get-rid-of-the-app-store-charts) — iOS Dev Weekly · Issue 98 — Tutorial · Topics: App Distribution & Store Operations · Developer Community & Business
  **Published:** `14th June 2013`
  **NeKI brief:** One disappointment with iOS 7 (so far, it could change of course) was that the App Store is largely untouched from iOS 6. These posts by John August and Nick Dalton have some interesting suggestions, I especially like Nick’s idea to base a chart on long term…
- [Overview of iOS Crash Reporting Tools](http://www.raywenderlich.com/33669/overview-of-ios-crash-reporting-tools-part-1) — iOS Dev Weekly · Issue 95 — Article · Topics: Testing
  **Published:** `24th May 2013`
  **NeKI brief:** Examines Learn how crash reporting works on iOS, how to automatically get and diagnose crash logs, and which crash reporting tool is best for you. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [In-App Purchase Education](http://www.pocketgamer.biz/r/PG.Biz/App+Store/news.asp?c=50444) — iOS Dev Weekly · Issue 92 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `3rd May 2013`
  **NeKI brief:** Discusses In-App Purchase Education, connecting the concrete app-design or engineering decision to practical considerations for Apple-platform developers.
- [The market for paid iOS apps isn’t dead](http://www.marco.org/2013/04/19/paid-app-market) — iOS Dev Weekly · Issue 91 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `26th April 2013`
  **NeKI brief:** In what might be the conclusion to the App Store pricing discussion that we have seen over the last few weeks Marco Arment says what I was trying hint at in my comments last week in a much more eloquent way. His last sentence sums it all up for me, “The bar…
- [Understanding App Store Pricing](http://jury.me/blog/2013/3/31/understanding-app-store-pricing-part-1) — iOS Dev Weekly · Issue 88 — Article · Topics: App Distribution & Store Operations · Developer Community & Business
  **Published:** `5th April 2013`
  **NeKI brief:** Examines At Çingleton and NSConference this year I spoke at length about App Store pricing and offered an analysis of the trends, problems, concerns,. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [So long, break-even](http://www.asymco.com/2013/03/22/so-long-break-even) — iOS Dev Weekly · Issue 87 — Article · Topics: App Distribution & Store Operations
  **Published:** `29th March 2013`
  **NeKI brief:** Examines The following is another excerpt from a report titled "iTunes Business Review" which will soon be available for purchase through the Asymco Store. If you are interested i. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [App Store Economics](http://casualconnect.org/lectures/business/app-store-economics-bertrand-schmitt) — iOS Dev Weekly · Issue 84 — Article · Topics: App Distribution & Store Operations
  **Published:** `8th March 2013`
  **NeKI brief:** Bertrand Schmitt, CEO of App Annie speaking last year on the economics of the App Store. I missed this when it was first published but the extensive data they have collected means that this is a must watch and still very relevant today.
- [Nope](http://www.loopinsight.com/2013/02/13/apples-rumored-tv-related-event-in-march) — iOS Dev Weekly · Issue 81 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `15th February 2013`
  **NeKI brief:** Examines Apple’s rumored TV-related event in March. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Google Play Store Adds Ability For Developers to Reply to Comments](http://www.droid-life.com/2013/01/09/google-adds-ability-for-all-developers-to-reply-to-comments-in-play-store) — iOS Dev Weekly · Issue 76 — Article · Topics: App Distribution & Store Operations
  **Published:** `11th January 2013`
  **NeKI brief:** Presents Google Play Store Adds Ability For Developers to Reply to Comments, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [Mac App Store: Year Two](http://www.macstories.net/stories/mac-app-store-year-two) — iOS Dev Weekly · Issue 76 — Article · Topics: App Distribution & Store Operations
  **Published:** `11th January 2013`
  **NeKI brief:** Examines It doesn’t seem like two years since the Mac App Store debuted and to mark the anniversary Federico Viticci has written a comprehensive retrospective on the story so far. Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [SyncSpace](http://infinitekind.com/syncspace) — iOS Dev Weekly · Issue 73 — Article · Topics: App Distribution & Store Operations
  **Published:** `21st December 2012`
  **NeKI brief:** Examines SyncSpace provides a shared drawing space that can be sketched on by multiple collaborators at any time over the net, on your iPhone, iPad, and Android!. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Coda and Sandboxing](http://www.panic.com/blog/2012/12/coda-and-sandboxing) — iOS Dev Weekly · Issue 72 — Article · Topics: App Distribution & Store Operations · Performance · Security & Privacy
  **Published:** `14th December 2012`
  **NeKI brief:** Explains Coda and Sandboxing with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Saturday Soapbox: It just worked?](http://www.eurogamer.net/articles/2012-11-23-saturday-soapbox-it-just-worked) — iOS Dev Weekly · Issue 70 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `30th November 2012`
  **NeKI brief:** The page covers “Saturday Soapbox: It just worked?” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Rampant Abuse of Push Notifications Is Ruining Them For All Developers](http://blog.anylistapp.com/2012/11/push-notifications) — iOS Dev Weekly · Issue 68 — Article · Topics: App Distribution & Store Operations · App Services & Extensions
  **Published:** `16th November 2012`
  **NeKI brief:** This article argues that promotional misuse of push notifications damages trust and conflicts with platform review expectations. It provides a useful product boundary for deciding when a notification communicates user value versus functioning as direct marketing.
- [EU App Store Pricing](http://penguinlovesmusic.de/2012/10/26/a-brief-note-on-pricing) — iOS Dev Weekly · Issue 66 — Article · Topics: App Distribution & Store Operations
  **Published:** `2nd November 2012`
  **NeKI brief:** This happened last week but just in case you missed it Apple have adjusted the prices of the App Store tiers again to reflect the changing currency rates around the world. This article by Joerg Schwieder takes a look at what changed in the reshuffle.
- [How to Choose Keywords for the App Store](http://mentalfaculty.tumblr.com/post/34476925606/how-to-choose-keywords-for-the-app-store) — iOS Dev Weekly · Issue 66 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `2nd November 2012`
  **NeKI brief:** Explains How to Choose Keywords for the App Store with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [Developers stymied by Mac App Store approval delays](http://www.macworld.com/article/2011430/developers-stymied-by-mac-app-store-approval-delays.html) — iOS Dev Weekly · Issue 63 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `12th October 2012`
  **NeKI brief:** So we hit the news a little this week with several stories about the steadily increasing Mac App Store review times triggered by data from our review times site. I have always been a defender of the App Store review processes and so I am really sad to see…
- [Shenzhen](https://github.com/mattt/shenzhen) — iOS Dev Weekly · Issue 62 — Source repository · Topics: Developer Tools · Testing
  **Published:** `5th October 2012`
  **NeKI brief:** Provides the Shenzhen source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [New Apple Developer Guideline Bans Apps That Promote Other Apps](http://daringfireball.net/linked/2012/10/01/app-store-promotion) — iOS Dev Weekly · Issue 62 — Article · Topics: App Distribution & Store Operations
  **Published:** `5th October 2012`
  **NeKI brief:** John Gruber and TechCrunch on a new App Store guideline which bans linking to other apps. Like John, I really can’t see much about this which was causing problems. Strange.
- [Everything that’s wrong with the App Store in iOS 6](http://www.lightwoodgames.com/blog/2012/09/everything-thats-wrong-with-the-app-store-in-ios-6) — iOS Dev Weekly · Issue 61 — Article · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `28th September 2012`
  **NeKI brief:** Chris Newman on the new App Store in iOS 6 which really do make apps more difficult to discover. I was pleasantly surprised when I first used the iOS 6 store during the beta (ooh, new shiny) but the flaws quickly became apparent. I really hope there are some…
- [CargoBay](https://github.com/mattt/CargoBay) — iOS Dev Weekly · Issue 59 — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **Published:** `14th September 2012`
  **NeKI brief:** The page covers “CargoBay” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Beware of the Sorrell: Gambling For Kids: A How To Guide](http://www.bewareofthesorrell.com/2012/09/gambling-for-kids-how-to-guide.html) — iOS Dev Weekly · Issue 59 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web · Developer Tools
  **Published:** `14th September 2012`
  **NeKI brief:** Examines It’s easy to think that the questionable tactic of targeting digital goods and In-App purchases at kids is a new phenomenon but Mark Sorrell reminds us that this has been going on for a long time and that maybe what we n Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [A Flaw in Apple’s In-App Purchase System Enables 30K Illegal Sales](http://thenextweb.com/apple/2012/07/13/how-a-flaw-in-apples-in-app-purchase-process-enabled-more-than-30000-illegal-virtual-transactions) — iOS Dev Weekly · Issue 51 — Article · Topics: App Distribution & Store Operations · Developer Community & Business
  **Published:** `20th July 2012`
  **NeKI brief:** Describes a flaw in an in-app purchase process that enabled unauthorized virtual transactions. Follow it for concrete payment-security and abuse lessons, while checking modern StoreKit protections independently.
- [On AppStore Search Ranking Algorithms](http://creativealgorithms.com/blog/content/appstore-search-ranking-algorithms) — iOS Dev Weekly · Issue 48 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `29th June 2012`
  **NeKI brief:** This article discusses App Store search-ranking algorithms and optimization factors. Follow it for historical discovery and metadata context, while treating rankings and platform behavior as time-sensitive.
- [It’s time for Apple to allow developers to respond to App Store reviews](http://thenextweb.com/apple/2012/06/22/its-time-for-apple-to-allow-developers-to-respond-to-app-store-reviews) — iOS Dev Weekly · Issue 48 — Article · Topics: App Distribution & Store Operations
  **Published:** `29th June 2012`
  **NeKI brief:** This is a tricky problem but I am not sure allowing public responses from developers is the right solution as the last thing we want for App Store reviews to degenerate into public arguments. However as the article mentions, if there were a way to have a…
- [7,073 Users Can Be Wrong](http://rogueamoeba.com/utm/2012/06/06/7073-users-can-be-wrong) — iOS Dev Weekly · Issue 45 — Article · Topics: App Distribution & Store Operations
  **Published:** `8th June 2012`
  **NeKI brief:** Reflects on why user counts and ratings can mislead product decisions, using a concrete customer-feedback experience. Useful as a reminder to combine quantitative signals with direct evidence about actual user problems.
- [Let’s Have Some Fun with the Preliminary Schedule for WWDC 2012](http://daringfireball.net/2012/05/reading_way_too_much_into_wwdc_schedule) — iOS Dev Weekly · Issue 44 — Article · Topics: App Distribution & Store Operations · Apple Platform Ecosystem · Developer Community & Business
  **Published:** `1st June 2012`
  **NeKI brief:** Examines As much as I want to see an App Store for the Apple TV (and I really do), I am not sure I really believe it will happen now and those TBA sessions on the schedule are always less exciting than the rumours when the confer Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Apple Has Removed Airfoil Speakers Touch From The iOS App Store](http://rogueamoeba.com/utm/2012/05/24/apple-has-removed-airfoil-speakers-touch-from-the-ios-app-store) — iOS Dev Weekly · Issue 43 — Article · Topics: App Distribution & Store Operations
  **Published:** `25th May 2012`
  **NeKI brief:** Explains Apple Has Removed Airfoil Speakers Touch From The iOS App Store, focusing on the concrete iOS or Swift implementation technique and the trade-offs relevant to production applications.
- [SCOtutor for ScreenFlow](http://www.screencastsonline.com/appstore) — iOS Dev Weekly · Issue 43 — Tutorial · Topics: App Distribution & Store Operations · Graphics, Media & Games
  **Published:** `25th May 2012`
  **NeKI brief:** Explains SCOtutor for ScreenFlow with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Four Years of App Store](http://www.macstories.net/stories/four-years-of-app-store-developers-weigh-in-on-search-discovery-and-curation) — iOS Dev Weekly · Issue 43 — Article · Topics: App Distribution & Store Operations · Objective-C & Cocoa
  **Published:** `25th May 2012`
  **NeKI brief:** Examines "The App Store is a grand slam, with a staggering 10 million applications downloaded in just three days". That's how Apple co-founder and late CEO Steve Jobs saluted. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Paid Upgrades and the Mac App Store](http://www.mentalfaculty.com/mentalfaculty/Blog/Entries/2012/3/28_Paid_Upgrades_and_the_Mac_App_Store.html) — iOS Dev Weekly · Issue 35 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `30th March 2012`
  **NeKI brief:** The page covers “Paid Upgrades and the Mac App Store” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [iPhone app Clear sells 350k downloads in nine days on the App Store](http://guardian.co.uk/technology/appsblog/2012/feb/23/iphone-app-clear-350k-sales) — iOS Dev Weekly · Issue 30 — Article · Topics: App Distribution & Store Operations · Developer Community & Business
  **Published:** `24th February 2012`
  **NeKI brief:** Stunning numbers. Who says that you shouldn’t try and compete in a crowded market place like todo list apps?
- [Apple Kicks Chart Topping Fakes Out Of App Store](http://techcrunch.com/2012/02/03/app-store-fakes) — iOS Dev Weekly · Issue 28 — Article · Topics: App Distribution & Store Operations
  **Published:** `10th February 2012`
  **NeKI brief:** Examines Temple Jump, Tiny Birds, Numbers With Friends. These are not the apps you love. They're fakes designed to scam you out of $1.99 when you go to buy Temple Run, Tiny Wings, or W. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [iTunes Connect App Status Flowchart](http://useyourloaf.com/blog/2011/8/29/itunes-connect-app-status-update.html) — iOS Dev Weekly · Issue 5 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `2nd September 2011`
  **NeKI brief:** Examines Almost a year ago I created a flowchart to try and make sense of the various states an app can go through during the iOS App Store submission process. There have been some recent c. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Greenlight: Pre-submission compliance scanner for the Apple App Store](https://github.com/RevylAI/greenlight) — Not only Swift · Issue 96 — Source repository · Topics: AI Development · App Distribution & Store Operations · Developer Tools
  **NeKI brief:** This source repository covers Apple App Store pre-submission compliance scanning. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [App Store Connect CLI Skills](https://github.com/rudrankriyam/app-store-connect-cli-skills) — Not only Swift · Issue 96 — Source repository · Topics: App Distribution & Store Operations · Developer Tools
  **NeKI brief:** This source repository covers skills for automating App Store Connect through the asc CLI. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Google Play Developer CLI](https://github.com/dl-alexandre/Google-Play-Developer-CLI) — Not only Swift · Issue 96 — Source repository · Topics: AI Development · App Distribution & Store Operations · Developer Tools
  **NeKI brief:** This source repository covers an AI-agent-friendly Google Play command-line workflow. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
