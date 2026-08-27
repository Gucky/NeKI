# Foundation & Data Formats

Third-party reading leads collected from NeKI sources. The links may be useful perspectives, but are not vetted recommendations or authoritative API guidance. NeKI publishes routing metadata, not the linked articles' text.

**Scope:** Foundation APIs, dates, text, Unicode, serialization, and data formats.

- Last collected: `2026-08-27T19:22:09Z`
- Indexed links shown: **204**

## Direct-source reading

- [Type-safe JSON and JSONB in StructuredQueries](https://www.pointfree.co/blog/posts/220-type-safe-json-and-jsonb-in-structuredqueries) — Point-Free · article catalogue
  **Published:** `2026-08-03T00:00:00Z`
  **NeKI brief:** Introduces StructuredQueries 0.35 support for SQLite JSON and JSONB columns, key-path-based extraction and mutation, and json_each collection queries. The examples show where binary storage improves efficiency while preserving compile-time schema checks.
- [Pattern matching on error codes – Ole Begemann](https://oleb.net/2023/catch-error-code) — Ole Begemann · article catalogue
  **Published:** `2023-02-27T19:32:22Z`
  **NeKI brief:** Foundation overloads `~=` so a `catch` clause can pattern-match an error's code without downcasting every case manually. The technique keeps recovery branches declarative while requiring care when domains expose overlapping or unstable codes.
- [AttributedString’s Codable format and what it has to do with Unicode – Ole Begemann](https://oleb.net/2022/attributedstring-codable) — Ole Begemann · article catalogue
  **Published:** `2022-04-27T13:28:03Z`
  **NeKI brief:** Explains AttributedString's Codable representation and Unicode implications. Use it when storing rich text and needing stable serialization across grapheme clusters and attributes.
- [Splitting a JSON object into an enum and an associated object with Codable – Donny Wals](https://www.donnywals.com/splitting-a-json-object-into-an-enum-and-an-associated-object-with-codable) — Donny Wals · article catalogue
  **Published:** `2021-04-05T18:33:21+00:00`
  **NeKI brief:** Decoding a discriminator into an enum plus associated payload models variant JSON safely, avoiding optional-field soup while requiring explicit unknown-case policy.
- [How to change a UICollectionViewListCell’s separator inset – Donny Wals](https://www.donnywals.com/how-to-change-a-uicollectionviewlistcells-separator-inset) — Donny Wals · article catalogue
  **Published:** `2020-06-25T17:08:10+00:00`
  **NeKI brief:** List-cell separator insets are configured through the collection-list appearance APIs, keeping alignment consistent with custom content margins and layout direction.
- [Sanitizing GPX files for public sharing – Ole Begemann](https://oleb.net/2020/sanitizing-gpx) — Ole Begemann · article catalogue
  **Published:** `2020-06-22T14:01:32Z`
  **NeKI brief:** GPX files can contain timestamps, device metadata, and precise locations beyond the route a user intends to share. An XmlStarlet filtering pass removes those fields before publication, trading convenience for a reproducible privacy boundary.
- [Scheduling daily notifications on iOS using Calendar and DateComponents](https://www.donnywals.com/scheduling-daily-notifications-on-ios-using-calendar-and-datecomponents) — Donny Wals · article catalogue
  **Published:** `2019-12-12T07:45:26+00:00`
  **NeKI brief:** Calendar notification triggers model recurring local delivery through date components, but authorization, timezone, and missed-trigger behavior need product decisions.
- [Formatter - NSHipster](https://nshipster.com/formatter) — NSHipster · article catalogue
  **Published:** `2019-07-15T00:00:00-07:00`
  **NeKI brief:** Foundation formatters centralize locale-sensitive parsing and presentation, but each formatter encodes different calendar, numeric, or user-preference assumptions. The catalogue helps choose an explicit formatter instead of hand-built strings that silently break for other locales.
- [A script to save the last backup date in SuperDuper – Ole Begemann](https://oleb.net/blog/2018/01/superduper-last-backup-timestamp) — Ole Begemann · article catalogue
  **Published:** `2018-01-31T18:37:00Z`
  **NeKI brief:** Recording a backup timestamp in a small file gives scripts a durable handoff without parsing SuperDuper's UI. The workflow is intentionally simple, but consumers must define clock format and failure behavior for automation to remain reliable.
- [Why String.CharacterView is not a MutableCollection – Ole Begemann](https://oleb.net/blog/2017/02/why-is-string-characterview-not-a-mutablecollection) — Ole Begemann · article catalogue
  **Published:** `2017-02-07T14:48:44Z`
  **NeKI brief:** String.CharacterView cannot safely provide arbitrary mutation because grapheme clusters can change width and boundaries when characters are replaced. The explanation clarifies why collection protocols encode semantic guarantees, not just methods.
- [Measurements and Units in Foundation – Ole Begemann](https://oleb.net/blog/2016/07/measurements-and-units) — Ole Begemann · article catalogue
  **Published:** `2016-07-28T18:11:00Z`
  **NeKI brief:** Examines An introduction to the new measurements and units family of types in Foundation in iOS 10 and macOS 10.12. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Apple has launched Safari Technology Preview (and that’s great news). – Donny Wals](https://www.donnywals.com/apple-has-launched-safari-technology-preview-and-thats-great-news) — Donny Wals · article catalogue
  **Published:** `2016-03-31T11:27:24+00:00`
  **NeKI brief:** Safari Technology Preview gives web developers an early testing channel for engine changes, helping detect compatibility issues before they reach stable Safari.
- [Build a simple web scraper with node.js – Donny Wals](https://www.donnywals.com/build-a-simple-web-scraper-with-node-js) — Donny Wals · article catalogue
  **Published:** `2016-02-29T15:17:37+00:00`
  **NeKI brief:** A simple Node scraper turns remote HTML into structured data, but selectors, rate limits, and source permission boundaries must be treated as fragile dependencies.
- [ICU Text Transforms in Foundation – Ole Begemann](https://oleb.net/blog/2016/01/icu-text-transforms) — Ole Begemann · article catalogue
  **Published:** `2016-01-31T20:59:00Z`
  **NeKI brief:** Foundation's ICU text transforms can transliterate, normalize, or transform scripts using locale-aware rules instead of ad-hoc character replacement. The article warns that transformation is a linguistic policy, not neutral cleanup.
- [How to Use updateConstraints – Ole Begemann](https://oleb.net/blog/2015/08/how-to-use-updateconstraints) — Ole Begemann · article catalogue
  **Published:** `2015-08-31T21:53:00Z`
  **NeKI brief:** Presents How to Use updateConstraints, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [One for the Unicode Nerds – Ole Begemann](https://oleb.net/blog/2014/06/one-for-the-unicode-nerds) — Ole Begemann · article catalogue
  **Published:** `2014-06-27T12:46:00Z`
  **NeKI brief:** Unicode details such as normalization and scalar equivalence affect text comparison beyond visible glyphs. The article is useful when input validation or search must be correct across scripts.
- [There is a Bug in the NSFetchedResultsControllerDelegate Documentation – Ole Begemann](https://oleb.net/blog/2013/02/nsfetchedresultscontroller-documentation-bug) — Ole Begemann · article catalogue
  **Published:** `2013-02-27T16:24:00Z`
  **NeKI brief:** Identifies a NSFetchedResultsController delegate documentation error around table updates, illustrating why insertion, deletion, move, and reload handling must follow the controller's actual index-path contract.
- [Tutorial: How to Sort and Group UITableView by Date – Ole Begemann](https://oleb.net/blog/2011/12/tutorial-how-to-sort-and-group-uitableview-by-date) — Ole Begemann · article catalogue
  **Published:** `2011-12-02T17:40:00Z`
  **NeKI brief:** Groups table-view records by calendar date after normalizing timestamps with an explicit calendar and time zone, separating sort keys from localized section-title presentation.
- [Date and Time Handling in Cocoa Cheat Sheet – Ole Begemann](https://oleb.net/blog/2011/11/date-and-time-in-cocoa-cheat-sheet) — Ole Begemann · article catalogue
  **Published:** `2011-11-23T18:00:00Z`
  **NeKI brief:** Collects Cocoa date and time API distinctions, useful for checking formatter, calendar, time-zone, and locale responsibilities before treating a Date as a user-facing value.
- [Working with Date and Time in Cocoa (Part 2) – Ole Begemann](https://oleb.net/blog/2011/11/working-with-date-and-time-in-cocoa-part-2) — Ole Begemann · article catalogue
  **Published:** `2011-11-22T21:58:00Z`
  **NeKI brief:** Continues Cocoa date handling with calendar calculations and formatter choices, stressing that human calendar concepts require explicit locale, calendar, and time-zone context.
- [How to Debug an App That Was Launched by Push Notification or URL Handler – Ole Begemann](https://oleb.net/blog/2010/05/how-to-debug-app-launched-by-remote-event) — Ole Begemann · article catalogue
  **Published:** `2010-05-06T21:17:00Z`
  **NeKI brief:** Shows two launch-debugging strategies for URL handlers and push events: inspect persistent logs when no debugger is attached, or configure the debugger to wait for the next process launch and stop at lifecycle breakpoints. Update the historical Xcode UI steps for current tooling.
- [How We Safeguard Against Remote Job Applicant Fraud](https://martiancraft.com/blog/2025/05/how-we-safeguard-against-remote-job-applicant-fraud) — MartianCraft · article catalogue
  **NeKI brief:** Remote applicant fraud defenses combine identity verification, interview signals, and process controls rather than trusting a single screening step. The article is useful for designing hiring workflows that protect engineering teams.
- [Dealing with Dates](https://martiancraft.com/blog/2018/05/dealing-with-dates) — MartianCraft · article catalogue
  **NeKI brief:** Date bugs arise when an instant, calendar date, locale, and time zone are conflated. The guide uses Foundation's calendar and formatter APIs to make those boundaries explicit, a useful diagnostic checklist for scheduling and display failures.
- [Introduction to HEIF Image File Format](https://martiancraft.com/blog/2017/10/HEIF-image-file-format) — MartianCraft · article catalogue
  **NeKI brief:** HEIF combines more efficient image compression with containers that can preserve richer image data than older formats. Apple platform support changes an app's import/export decisions: account for compatibility fallbacks before treating the new default as universally shareable.
- [Staying Competitive with App Updates](https://martiancraft.com/blog/2017/04/app-updates) — MartianCraft · article catalogue
  **NeKI brief:** Examines how frequent app updates can sustain competitiveness. Follow it for concrete release, feedback, and iteration strategy, while treating business claims as contextual rather than technical guidance.

## Newsletter and related leads

- [NSTextTable in Swift](https://livsycode.com/uikit/nstexttable-in-swift) — Those Who Swift · Issue 281 — Article · Topics: Swift · UIKit
  **Published:** `2026-08-26T20:38:31.643Z`
  **NeKI brief:** Introduces NSTextTable and NSTextTableBlock in UIKit for creating tables inside NSAttributedString, now available to iOS developers in the iOS 27 SDK. It distinguishes rich-text tables from UITableView and shows when the text model is the appropriate layout layer.
- [FoundationModelsKit](https://github.com/divyaravitech/FoundationModelsKit) — iOS Dev Tools · iOS Dev Tools: ConsentBus, FoundationModelsKit, Agent Island — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **Published:** `2026-08-06T16:00:49.980Z`
  **NeKI brief:** Provides protocol-based model routing, actor-isolated conversation compaction, evaluation hooks and regional availability for mixing on-device, private-cloud and third-party model implementations.
- [how he used AI to make MessagePack decoding about 20% faster](https://pfandrade.me/blog/message-packable?ref=ioscodereview.com) — iOS Code Review · Issue 83 — Article · Topics: AI Development · Foundation & Data Formats · Performance · Swift
  **Published:** `2026-08-06T06:44:37.000Z`
  **NeKI brief:** Describes using Codex to integrate Swift Binary Parsing into a MessagePack decoder, then independently validating nearly 20% faster decoding and more than 60% fewer allocations. It is a human-in-the-loop optimization workflow grounded in Instruments and reproducible benchmarks.
- [Bridging Gemini Video with Foundation Models and CustomSegment](https://rudrank.com/exploring-foundation-models-bridging-gemini-video-with-customsegment) — Those Who Swift · Issue 277 — Article · Topics: AI Development · Foundation & Data Formats · Graphics, Media & Games
  **Published:** `2026-07-29T20:01:55.196Z`
  **NeKI brief:** Bridges unsupported video input through a custom Transcript segment and LanguageModelExecutor that delegates analysis to Gemini. The layered verification is useful when extending Foundation Models-style sessions beyond the on-device model’s native modalities.
- [Foundation Models Is Now a Hybrid Platform — and Picking the Tier Is the New Design Decision](https://www.wesleymatlock.com/foundation-models-hybrid-platform) — Those Who Swift · Issue 276 — Article · Topics: AI Development · Foundation & Data Formats · Navigation & Deep Linking
  **Published:** `2026-07-22T20:01:13.378Z`
  **NeKI brief:** Frames model-tier selection as a feature-level architectural decision, with session creation and graceful fallback kept behind a focused boundary. Useful when designing a Foundation Models feature that may choose on-device, cloud, or frontier capability paths.
- [Apple Foundation Models in iOS 27: The Complete Builder Guide](https://chatforest.com/builders-log/apple-foundation-models-ios-27-on-device-llm-api-builder-guide) — Those Who Swift · Issue 276 — Article · Topics: AI Development · Foundation & Data Formats
  **Published:** `2026-07-22T20:01:13.378Z`
  **NeKI brief:** Maps an on-device Foundation Models stack from model capability through app logic, tool calls, availability, and optional fine-tuning. Follow it when scoping a local AI feature, while validating beta hardware, privacy, and storage constraints independently.
- [FoundationModelsKit](https://divyaravidev.substack.com/p/introducing-foundationmodelskit-production) — Those Who Swift · Issue 275 — Article · Topics: AI Development · Foundation & Data Formats · Swift
  **Published:** `2026-07-15`
  **NeKI brief:** Introduces FoundationModelsKit for production-oriented use. Useful for evaluating a wrapper around Apple’s model APIs while keeping availability, model behavior, and app-level safeguards explicit.
- [Foundation Models in iOS 27: Tool-Calling Control](https://blakecrosley.com/blog/foundation-models-tool-calling-ios-27) — Those Who Swift · Issue 275 — Article · Topics: AI Development · Foundation & Data Formats · Objective-C & Cocoa
  **Published:** `2026-07-15`
  **NeKI brief:** Shows how tool calling and local OCR or barcode capabilities can fit into Foundation Models workflows.
- [WWDC 2026 Developer Tools: Xcode 27, Swift, Foundation Models](https://andrew.ooo/answers/wwdc-2026-developer-tools-xcode-swift-foundation-models-june-2026) — Those Who Swift · Issue 275 — Article · Topics: Apple Platform Ecosystem · Foundation & Data Formats · Swift
  **Published:** `2026-07-15`
  **NeKI brief:** Surveys the WWDC 2026 developer-tool changes across Xcode, Swift, and Foundation Models. Use it as a release-oriented map of new workflows, then verify specific APIs, deployment requirements, and availability in Apple's current documentation.
- [Getting Started with Apple’s Foundation Models](https://artemnovichkov.com/blog/getting-started-with-apple-foundation-models) — Those Who Swift · Issue 275 — Article · Topics: AI Development · Foundation & Data Formats
  **Published:** `2026-07-15`
  **NeKI brief:** Demonstrates rendering Markdown in SwiftUI. Useful for choosing a rendering pipeline, handling attributed content, and deciding where links and styling should remain controlled by the app.
- [ZMarkupParser](https://github.com/ZhgChgLi/ZMarkupParser) — iOS Dev Tools · iOS Dev Tools: Footprint, ZMarkupParser, Lettera — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `2026-06-18T16:02:35.381Z`
  **NeKI brief:** A pure-Swift HTML-to-NSAttributedString parser that repairs malformed markup, supports custom tags and styles, and can render, strip, or select content. Its thread-safe implementation and performance report make it a concrete alternative to Foundation HTML parsing.
- [Testing Foundation Models: Code That Won’t Give The Same Answer Twice](https://www.wesleymatlock.com/testing-on-device-ai-swift-testing) — Those Who Swift · Issue 271 — Article · Topics: AI Development · Foundation & Data Formats · Testing
  **Published:** `2026-06-18`
  **NeKI brief:** Discusses testing nondeterministic Foundation Models output with Swift Testing. Use it when designing assertions for on-device AI, focusing on stable structure, bounded behavior, and controlled inputs instead of brittle exact-text comparisons.
- [WWDC26 Group Labs: The Real Story Isn’t Foundation Models. It’s Evaluation.](https://divyaravidev.substack.com/p/wwdc26-group-labs-the-real-story) — Those Who Swift · Issue 271 — Article · Topics: AI Development · Apple Platform Ecosystem · Foundation & Data Formats
  **Published:** `2026-06-18`
  **NeKI brief:** Reports on WWDC26 group labs and evaluation around Foundation Models. Useful for understanding model assessment as an engineering concern rather than relying on demo quality alone.
- [Using Claude With Apple Foundation Models](https://artemnovichkov.com/blog/using-claude-with-apple-foundation-models) — Those Who Swift · Issue 271 — Article · Topics: AI Development · Foundation & Data Formats
  **Published:** `2026-06-18`
  **NeKI brief:** Artem shows how Claude can be used into Apple’s Foundation Models framework on iOS 27, using the same LanguageModelSessionAPI to switch between on-device models and Claude.
- [Foundation Models can now swap providers](https://www.techtimes.com/articles/318039/20260609/wwdc-2026-developer-tools-foundation-models-now-swaps-ai-providers-without-code-changes.htm?ref=ioscodereview.com) — iOS Code Review · Issue 80 — Article · Topics: AI Development · Foundation & Data Formats · Xcode
  **Published:** `2026-06-15T17:08:20.000Z`
  **NeKI brief:** Examines Foundation Models can now swap providers in the context of AI Development and Foundation & Data Formats. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Whats new in SwiftUI in iOS 27](https://onmyway133.com/posts/whats-new-in-swiftui-in-ios-27) — iOS Dev Weekly · Issue 754 — Article · Topics: Foundation & Data Formats · Swift · SwiftUI
  **Published:** `12th June 2026`
  **NeKI brief:** Presents whats new in swiftui in ios 27 for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Michael Tsai](https://mjtsai.com/blog/2026/06/03/wwdc-2026-wish-lists) — iOS Dev Weekly · Issue 753 — Article · Topics: AI Development · Apple Platform Ecosystem · Developer Community & Business
  **Published:** `5th June 2026`
  **NeKI brief:** Examines Michael Tsai - Blog - WWDC 2026 Wish Lists. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Apple’s Hidden AI: Unlock Foundation Models on Your Mac with Apfel](https://www.youtube.com/watch?v=KlCqHP32c8M) — Those Who Swift · Issue 269 — Video · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **Published:** `2026-06-04`
  **NeKI brief:** Reviews Apple’s Hidden AI: Unlock Foundation Models on Your Mac with Apfel. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [MacRumors + 2](https://www.macrumors.com/2026/05/18/apple-design-award-finalists-2026?ref=ioscodereview.com) — iOS Code Review · Issue 79 — Article · Topics: Architecture · Composable Architecture · Testing
  **Published:** `2026-06-01T16:27:14.000Z`
  **NeKI brief:** Examines MacRumors + 2 in the context of Architecture and Composable Architecture. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Swift Student Challenge winners](https://9to5mac.com/2026/05/07/apple-highlights-four-swift-student-challenge-apps-ahead-of-wwdc-2026?ref=ioscodereview.com) — iOS Code Review · Issue 78 — Article · Topics: AI Development · Apple Platform Ecosystem · Swift
  **Published:** `2026-05-16T17:59:28.000Z`
  **NeKI brief:** Examines Swift Student Challenge winners in the context of AI Development and Apple Platform Ecosystem. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Apple Foundation Models With Mohammad Azam](https://www.youtube.com/watch?v=UeZfiKBHUCs&list=PL2iZPZus2bhSl3CDE_vs2851UMgix285u) — Those Who Swift · Issue 265 — Video · Topics: AI Development · Foundation & Data Formats · Objective-C & Cocoa
  **Published:** `2026-05-06`
  **NeKI brief:** Reviews Apple Foundation Models With Mohammad Azam. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Modern Swift Library Architecture](https://coenttb.com/en/blog/4-1-the-swift-package) — Fatbobman’s Swift Weekly · Issue 132 — Article · Topics: Architecture · Foundation & Data Formats · Swift
  **Published:** `2026-04-20T12:03:00.641Z`
  **NeKI brief:** Describes a layered Swift package ecosystem spanning primitives, standards, and foundations. Use it to study package-boundary design and dependency layering when a growing library family needs more than one monolithic module.
- [InfoWorld](https://www.infoworld.com/article/4157422/swift-for-visual-studio-code-comes-to-open-vsx-registry.html?ref=ioscodereview.com) — iOS Code Review · Issue 77 — Article · Topics: Cross-Platform & Web · Foundation & Data Formats · Swift
  **Published:** `2026-04-15T16:20:56.000Z`
  **NeKI brief:** Examines InfoWorld in the context of Cross-Platform & Web and Foundation & Data Formats. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [started as a small point in a long list of Visual Studio announcements](https://devblogs.microsoft.com/visualstudio/build-2015-news-visual-studio-code-visual-studio-2015-rc-team-foundation-server-2015-rc-visual-studio-2013-update-5) — iOS Dev Weekly · Issue 747 — Article · Topics: Foundation & Data Formats
  **Published:** `10th April 2026`
  **NeKI brief:** The page covers “started as a small point in a long list of Visual Studio announcements” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [Challenges with Ancient Dates in Apple SDKs](https://casualprogrammer.com/blog/2026/03-27-old-dates-in-apple-sdks.html) — iOS Dev Weekly · Issue 747 — Article · Topics: Cross-Platform & Web · Foundation & Data Formats
  **Published:** `10th April 2026`
  **NeKI brief:** What a lovely story of some extremely obscure date bugs from Aaron Trickey. Did you know that Foundation’s date arithmetic breaks before 4713 BC? Or that UIDatePicker won’t go further back than 1 AD? If you’ve ever needed convincing that working with dates…
- [Top 10 Developer Tools Apple Introduced At WWDC25](https://fline.dev/blog/top-10-developer-tools-apple-introduced-at-wwdc25) — Those Who Swift · Issue 260 — Article · Topics: AI Development · Apple Platform Ecosystem · Foundation & Data Formats
  **Published:** `2026-04-01`
  **NeKI brief:** Examines Top 10 Developer Tools Apple Introduced At WWDC25, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [iOS Agent Skills, App Store Connect CLI, Foundation Models Tokens & More](https://www.youtube.com/watch?v=VU-NiioUpxg&t=237s) — Those Who Swift · Issue 260 — Video · Topics: AI Development · App Distribution & Store Operations · Foundation & Data Formats
  **Published:** `2026-04-01`
  **NeKI brief:** Reviews iOS Agent Skills, App Store Connect CLI, Foundation Models Tokens & More. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Embedded Swift Improvements Coming in Swift 6.3Embedded Swift is a subset of Swift that’s designed for low resource usage, making it capable of running on constrained environments like microcontrollers. Using a special compilation mode, Embedded Swift produces significantly smaller binaries than regular Swift. While a subset of the full language, the vast majority of the Swift language works exactly the same in Embedded Swift. Additional information is described in the Embedded Swift vision document.Swift.orgApple Inc.](https://www.swift.org/blog/embedded-swift-improvements-coming-in-swift-6.3?ref=ioscodereview.com) — iOS Code Review · Issue 76 — Article · Topics: Combine & Reactive Programming · Foundation & Data Formats · Swift
  **Published:** `2026-03-30T18:21:46.000Z`
  **NeKI brief:** Examines Embedded Swift Improvements Coming in Swift 6.3Embedded Swift is a subset of Swift that’s designed for low… in the context of Combine & Reactive Programming and Foundation & Data Formats. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Conduit](https://github.com/christopherkarani/Conduit) — Fatbobman’s Swift Weekly · Issue 129 — Source repository · Topics: AI Development · Developer Career & Practice · Developer Tools
  **Published:** `2026-03-30T12:03:55.935Z`
  **NeKI brief:** Conduit is a unified SDK for working with multiple LLM providers. Use it when an application needs provider substitution behind one interface, while keeping model-specific capabilities and cost differences visible to callers.
- [Colony](https://github.com/christopherkarani/Colony) — Fatbobman’s Swift Weekly · Issue 129 — Source repository · Topics: AI Development · Developer Career & Practice · Developer Tools
  **Published:** `2026-03-30T12:03:55.935Z`
  **NeKI brief:** Colony is an agent runtime built around Apple Foundation Models. Use it to explore agent orchestration on-device, especially where tool execution, memory, and model-session lifecycle need a framework-level boundary.
- [Apple Foundation Models In Practice: Building On-Device AI Features In Swift](https://medium.com/@wesleymatlock/apple-foundation-models-in-practice-building-on-device-ai-features-in-swift-b6243976af4f) — Those Who Swift · Issue 259 — Article · Topics: AI Development · Foundation & Data Formats · Swift
  **Published:** `2026-03-26`
  **NeKI brief:** Examines Apple Foundation Models In Practice: Building On-Device AI Features In Swift, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [ImplementedSE-0489Improve `EncodingError` and `DecodingError`'s printed descriptions](https://github.com/apple/swift-evolution/blob/main/proposals/0489-codable-error-printing.md) — SwiftLee Weekly · Issue 315 — Source repository · Topics: Developer Tools · Foundation & Data Formats · Swift
  **Published:** `2026-03-17T15:01:49.000Z`
  **NeKI brief:** Records ImplementedSE-0489Improve `EncodingError` and `DecodingError`'s printed descriptions, clarifying the proposed Swift language or standard-library mechanism and the compatibility implications developers should consider.
- [Swift At Scale: Building The TelemetryDeck Analytics Service](https://www.swift.org/blog/building-privacy-first-analytics-with-swift) — Those Who Swift · Issue 257 — Article · Topics: Foundation & Data Formats · Security & Privacy · Swift
  **Published:** `2026-03-11`
  **NeKI brief:** Describes building a privacy-first analytics service in Swift and the engineering choices behind it. Follow it when evaluating telemetry architecture, data minimization, and server-side Swift trade-offs without treating the service design as an app recipe.
- [SwiftUI Foundations Q&A: Build Great Apps with SwiftUI](https://antongubarenko.substack.com/p/swiftui-foundations-build-great-apps) — iOS Dev Weekly · Issue 744 — Article · Topics: Foundation & Data Formats · Swift · SwiftUI
  **Published:** `27th February 2026`
  **NeKI brief:** Examines SwiftUI Foundations: Build Great Apps Q&A, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Tracking token usage in Foundation Models](https://artemnovichkov.com/blog/tracking-token-usage-in-foundation-models) — iOS Dev Weekly · Issue 744 — Article · Topics: AI Development · Foundation & Data Formats
  **Published:** `27th February 2026`
  **NeKI brief:** Artem explains how to measure the tokens Foundation Models consume for instructions, prompts, tools, and full session transcripts, helping you understand context limits and optimize prompt design.
- [Measuring Core Data and SwiftData](https://yaacoub.github.io/articles/swift-tip/measuring-core-data-and-swiftdata) — iOS Dev Weekly · Issue 744 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `27th February 2026`
  **NeKI brief:** Presents measuring core data and swiftdata for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [SwiftUI Foundations: Build great apps with SwiftUI](https://www.youtube.com/watch?v=Z3vloOtZLkQ) — Those Who Swift · Issue 253 — Video · Topics: Foundation & Data Formats · Swift · SwiftUI
  **Published:** `2026-02-12`
  **NeKI brief:** Reviews SwiftUI Foundations: Build great apps with SwiftUI. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Swift Actors: Common Pitfalls and How to Avoid Them](https://www.fractal-dev.com/blog/swift-actors-pitfalls?lang=en) — Those Who Swift · Issue 251 — Article · Topics: Concurrency · Foundation & Data Formats · Swift
  **Published:** `2026-01-28`
  **NeKI brief:** Catalogues common Swift actor pitfalls, including reentrancy and isolation misunderstandings. Use it when reviewing actor-based designs, pairing each warning with compiler diagnostics, tests, and a clear model of which state is actually protected.
- [Foundation Models Prompting Guide](https://livsycode.com/best-practices/foundation-models-prompting-guide) — Those Who Swift · Issue 250 — Article · Topics: AI Development · Foundation & Data Formats
  **Published:** `2026-01-21`
  **NeKI brief:** Provides practical prompting guidance for Apple's Foundation Models. Use it when shaping instructions, output constraints, and context boundaries for on-device generation, then validate behavior across models, locales, and failure cases.
- [Rendering Markdown in SwiftUI](https://artemnovichkov.com/blog/rendering-markdown-in-swiftui) — Those Who Swift · Issue 249 — Article · Topics: Graphics, Media & Games · Swift · SwiftUI
  **Published:** `2026-01-14`
  **NeKI brief:** Artem shows how to display Markdown content in SwiftUI using Apple’s Markdown support from basic rich text formatting to handling links, lists, and custom styles.
- [Agentic AI Foundation](https://www.linuxfoundation.org/press/linux-foundation-announces-the-formation-of-the-agentic-ai-foundation) — Those Who Swift · Issue 244 — Article · Topics: AI Development · Foundation & Data Formats · Product Design
  **Published:** `2025-12-11`
  **NeKI brief:** Announces the Agentic AI Foundation. Useful for tracking ecosystem governance and interoperability efforts around agent tooling, while separating foundation announcements from concrete APIs.
- [MarkdownView](https://github.com/LiYanan2004/MarkdownView) — Fatbobman’s Swift Weekly · Issue 114 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2025-12-08T12:00:58.751Z`
  **NeKI brief:** MarkdownView renders richer Markdown in SwiftUI, including mixed text and image layouts, selectable content, and interaction hooks. Use it when AttributedString's built-in Markdown support is too limited for a document-reading surface.
- [RichText](https://github.com/LiYanan2004/RichText) — Fatbobman’s Swift Weekly · Issue 114 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `2025-12-08T12:00:58.751Z`
  **NeKI brief:** RichText supplies interactive, styled rich-text components for SwiftUI beyond ordinary Text rendering. Use it when links, mixed media, selection, or fine-grained text actions need an explicit view-layer solution.
- [Swon](https://github.com/keeshux/swon) — iOS Dev Tools · iOS Dev Tools: ObjectBox, RIB, Swon — Source repository · Topics: Developer Tools · Foundation & Data Formats · Macros & Metaprogramming
  **Published:** `2025-12-04T17:28:54.311Z`
  **NeKI brief:** SWON uses Swift macros to generate JSON initializers for value types without Codable or Foundation, backed by cJSON and targeting Apple, Linux, Windows, and embedded environments. It is useful when minimizing runtime and framework dependencies in data parsing.
- [Rich Text Editing in SwiftUI Mastering Attributed Strings in iOS 26](https://www.youtube.com/watch?v=-hKpuysa6PM) — Those Who Swift · Issue 242 — Video · Topics: Swift · SwiftUI
  **Published:** `2025-11-26`
  **NeKI brief:** Builds a Notes-style SwiftUI rich-text editor with iOS 26 AttributedString transformations, formatting controls, alignment, color, and reusable toolbar components. The walkthrough also shows how selection state drives formatting-button feedback.
- [Using SwiftUI Foundation Models Transcripts to build a Chatbot](https://www.youtube.com/watch?v=cyOqYbWpQzU) — Those Who Swift · Issue 240 — Video · Topics: AI Development · Foundation & Data Formats · Swift
  **Published:** `2025-11-12`
  **NeKI brief:** Builds an on-device travel chatbot from a Foundation Models LanguageModelSession transcript, rendering user and model messages with thinking, scrolling, availability, guardrail, and error states. Useful for connecting session history to SwiftUI presentation.
- [AnyLanguageModel](https://github.com/mattt/AnyLanguageModel) — iOS Dev Tools · iOS Dev Tools: Clash X, AnyLanguageModel, HealthKit Data Generator — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **Published:** `2025-11-06T22:32:54.905Z`
  **NeKI brief:** AnyLanguageModel mirrors Apple's Foundation Models API while allowing alternative language-model providers, presenting a compatible abstraction for application code. Useful for testing provider substitution and keeping model integration behind a stable Swift interface.
- [Guided Generation with Foundation Models in Swift](https://www.youtube.com/watch?v=kBwwztRY1FQ) — Those Who Swift · Issue 239 — Video · Topics: AI Development · Foundation & Data Formats · Swift
  **Published:** `2025-11-05`
  **NeKI brief:** Uses Foundation Models @Generable and @Guide macros for structured workout and title responses, including partial streaming and guardrail errors. Useful for comparing schema-guided output with parsing unconstrained model text.
- [Optimize your app's speed and efficiency](https://www.youtube.com/watch?v=yXAQTIKR8fk) — SwiftLee Weekly · Issue 296 — Video · Topics: AI Development · Foundation & Data Formats · Performance
  **Published:** `2025-11-04T08:02:52.000Z`
  **NeKI brief:** Summarizes a Meet with Apple performance session spanning power use, Foundation Models response latency, SwiftUI responsiveness, and Snap's diagnostic tools. Useful as a map of optimization areas before consulting the corresponding primary guidance.
- [Foundation Models Framework in Swift Getting Started with On Device AI](https://www.youtube.com/watch?v=p17HrjVQKOQ) — Those Who Swift · Issue 238 — Video · Topics: AI Development · Foundation & Data Formats · Swift
  **Published:** `2025-10-29`
  **NeKI brief:** Reviews Foundation Models Framework in Swift Getting Started with On Device AI. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [Tunable, physics-driven motion primitives for SwiftUI](https://github.com/roberthein/kinetics) — SwiftUI Weekly · SwiftUI Weekly - Issue #223 — Source repository · Topics: Concurrency · Swift · SwiftUI
  **Published:** `2025-10-20T15:15:23.773Z`
  **NeKI brief:** Kinetics is an Apple-platform project related to motion or animation behavior. Follow its source for concrete timing, physics, or interaction techniques, while verifying framework and performance assumptions.
- [Advanced Codable](https://nothingtocommitworkingtreeclean.com/advanced_codable.html) — iOS Dev Weekly · Issue 731 — Article · Topics: Cross-Platform & Web · Foundation & Data Formats · Testing
  **Published:** `17th October 2025`
  **NeKI brief:** There’s a nice set of Codable tips and tricks in Alan Kantz-Durand’s latest post. I especially liked the idea of a Maybe:
- [Foundation Models profiling with Xcode Instruments](https://artemnovichkov.com/blog/foundation-models-profiling-with-xcode-instruments) — iOS Dev Weekly · Issue 731 — Article · Topics: Foundation & Data Formats · Performance · Xcode
  **Published:** `17th October 2025`
  **NeKI brief:** Artem shows how to profile and optimize Foundation Models performance using Xcode Instruments, tracking response time, token usage and tool calls to help developers improve performance on real devices.
- [iOS 26: Foundation Model Framework - Code-Along Q&A](https://l.fatbobman.com/w0106-03) — Fatbobman’s Swift Weekly · Issue 106 — Article · Topics: Foundation & Data Formats
  **Published:** `2025-10-13T12:03:32.126Z`
  **NeKI brief:** Presents a code-along introduction to the iOS 26 Foundation Models framework. Follow it when mapping model APIs to a concrete app workflow and identifying which platform assumptions need testing on supported devices and SDKs.
- [Foundation Models Playgrounds](https://l.fatbobman.com/w0106-08) — Fatbobman’s Swift Weekly · Issue 106 — Article · Topics: AI Development · Foundation & Data Formats
  **Published:** `2025-10-13T12:03:32.126Z`
  **NeKI brief:** Collects playground examples for Apple’s Foundation Models framework. Follow it when quickly exploring model APIs and isolating sample behavior before integrating the framework into a production feature.
- [iOS 26: Foundation Model Framework - Code-Along Q&A](https://antongubarenko.substack.com/p/ios-26-foundation-model-framework-f6d) — Those Who Swift · Issue 235 — Article · Topics: AI Development · Foundation & Data Formats · Testing
  **Published:** `2025-10-08`
  **NeKI brief:** Examines iOS 26: Foundation Model Framework - Code-Along Q&A, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Foundation Models Profiling with Xcode Instruments](https://l.fatbobman.com/w0105-05) — Fatbobman’s Swift Weekly · Issue 105 — Article · Topics: AI Development · Foundation & Data Formats · Performance
  **Published:** `2025-10-06T12:03:37.161Z`
  **NeKI brief:** Shows how to profile and optimize Foundation Models performance with Xcode Instruments. Follow it when measuring model latency, resource use, and bottlenecks instead of tuning an on-device AI feature from subjective responsiveness alone.
- [TranscriptDebugMenu](https://github.com/artemnovichkov/TranscriptDebugMenu) — Fatbobman’s Swift Weekly · Issue 105 — Source repository · Topics: AI Development · Foundation & Data Formats · Performance
  **Published:** `2025-10-06T12:03:37.161Z`
  **NeKI brief:** TranscriptDebugMenu is a debug surface for inspecting Foundation Models conversations and related app state. Use it alongside Xcode Instruments when testing session prewarming, tool calls, and model-output performance in development builds.
- [Exploring AI for iOS Development](https://academy.rudrank.com/product/ai) — iOS Dev Weekly · Issue 727 — Article · Topics: AI Development · Foundation & Data Formats · Testing
  **Published:** `19th September 2025`
  **NeKI brief:** Presents exploring ai for ios development for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Swift progres: UIKit iOS 26, FoundationModels API and SPM traits](https://www.youtube.com/watch?v=Ew101hvrWJk) — Those Who Swift · Issue 230 — Video · Topics: AI Development · Foundation & Data Formats · UIKit
  **Published:** `2025-09-03`
  **NeKI brief:** Surveys Swift ecosystem changes around SwiftPM package traits, Foundation Models, UIKit in iOS 26, and proposed stat types for Swift System. Use the linked proposals and documentation to verify each evolving feature.
- [FoundationModels: Tool Calling for an Assistant App](https://destiner.io/blog/post/foundation-models-tool-calling-search-app) — Those Who Swift · Issue 229 — Article · Topics: AI Development · Foundation & Data Formats · Objective-C & Cocoa
  **Published:** `2025-08-27`
  **NeKI brief:** Applies Foundation Models tool calling to an assistant-style search app. Useful for examining tool schemas, model-controlled actions, and the validation boundary before executing search operations.
- [Make Foundation Models Deterministic: Greedy Decoding in Swift](https://www.youtube.com/watch?v=Q6x3VeGlqwg) — Those Who Swift · Issue 228 — Video · Topics: AI Development · Foundation & Data Formats · Swift
  **Published:** `2025-08-20`
  **NeKI brief:** Configures Apple's Foundation Models GenerationOptions for greedy decoding so identical inputs produce more repeatable output. Useful for debugging and tests that need reduced sampling variance while recognizing model behavior is not universally deterministic.
- [SwiftAgent](https://forums.swift.org/t/swiftagent-a-swift-native-agent-sdk-inspired-by-foundationmodels-and-using-its-tools/81634) — iOS Dev Weekly · Issue 722 — Article · Topics: AI Development · Foundation & Data Formats · Swift
  **Published:** `15th August 2025`
  **NeKI brief:** Presents swiftagent for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Using Foundation Models Framework to Stream from External LLM Providers](https://www.natashatherobot.com/p/foundationmodels-streaming-external-llm) — Those Who Swift · Issue 226 — Article · Topics: AI Development · Foundation & Data Formats · Xcode
  **Published:** `2025-08-06`
  **NeKI brief:** Examines Using Foundation Models Framework to Stream from External LLM Providers, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Swift Concurrency: Part 1](https://www.nsvasilev.com/posts/swift-concurrency-part-1) — Those Who Swift · Issue 226 — Article · Topics: Concurrency · Foundation & Data Formats · Swift
  **Published:** `2025-08-06`
  **NeKI brief:** Examines Swift Concurrency: Part 1, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Horoscope](https://github.com/artemnovichkov/horoscope) — iOS Dev Tools · iOS Dev Tools: FreeTypeFramework, IGListKit, Horoscope — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **Published:** `2025-07-31T18:12:59.226Z`
  **NeKI brief:** Horoscope generates developer-oriented output with Apple's Foundation Models, making it a compact example of on-device model integration. Useful for inspecting prompt-to-result plumbing and the availability assumptions of current Apple AI APIs.
- [native version](https://projects.blender.org/blender/blender/issues/142346) — Fatbobman’s Swift Weekly · Issue 95 — Article · Topics: Foundation & Data Formats
  **Published:** `2025-07-28T12:02:57.187Z`
  **NeKI brief:** Provides contextual background on native version, useful for understanding the surrounding product, policy, or ecosystem issue before drawing technical or business conclusions.
- [Foundation Models Framework Example](https://github.com/rudrankriyam/Foundation-Models-Framework-Example) — iOS Dev Weekly · Issue 719 — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **Published:** `25th July 2025`
  **NeKI brief:** This source repository covers a practical lab for building, testing, and evaluating Apple Foundation Models apps. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [little experiment](https://github.com/daveverwer/FoundationModelComparison?tab=readme-ov-file) — iOS Dev Weekly · Issue 719 — Source repository · Topics: Developer Tools · Foundation & Data Formats
  **Published:** `25th July 2025`
  **NeKI brief:** The GitHub repository documents a small experiment comparing Foundation model behavior, with publicly readable README and source context.
- [FoundationModels: Basic Prompting for an iOS Reader App](https://destiner.io/blog/post/foundation-models-basic-prompting-ios-reader-app) — Those Who Swift · Issue 223 — Article · Topics: AI Development · Foundation & Data Formats · Security & Privacy
  **Published:** `2025-07-16`
  **NeKI brief:** Introduces basic Foundation Models prompting in an iOS reader app. Useful for connecting on-device model requests to app context, prompt design, and user-visible failure handling.
- [Open Source Summit](https://events.linuxfoundation.org/open-source-summit-north-america) — iOS Dev Weekly · Issue 717 — Article · Topics: Foundation & Data Formats · Graphics, Media & Games · Personal Essays
  **Published:** `11th July 2025`
  **NeKI brief:** The Linux Foundation page describes the Open Source Summit North America event and its programme for open-source developers and maintainers.
- [How to Add Custom Guardrails to Apple’s FoundationModels Generation](https://www.natashatherobot.com/p/add-custom-guardrails-foundationmodels) — Those Who Swift · Issue 222 — Article · Topics: AI Development · Foundation & Data Formats
  **Published:** `2025-07-10`
  **NeKI brief:** Uses cosine similarity and Accelerate for RAG in Swift. Useful for connecting vector math, embedding search, and performance considerations in an Apple-platform retrieval pipeline.
- [Announcing the Android Workgroup](https://forums.swift.org/t/announcing-the-android-workgroup/80666) — Those Who Swift · Issue 221 — Article · Topics: Cross-Platform & Web · Swift · Testing
  **Published:** `2025-07-02`
  **NeKI brief:** Introduces the Swift Android workgroup. Useful for following Swift’s cross-platform coordination and understanding how ecosystem work affects Android support and package authors.
- [Getting Started with Apple's Foundation Models](https://www.artemnovichkov.com/blog/getting-started-with-apple-foundation-models) — Those Who Swift · Issue 221 — Article · Topics: AI Development · Foundation & Data Formats · Swift
  **Published:** `2025-07-02`
  **NeKI brief:** Artem walks through using Apple’s new on-device Foundation Models framework to integrate Apple Intelligence’s LLMs into SwiftUI apps.
- [A Swift Developer’s Guide to Prompt Engineering with Apple’s](https://www.natashatherobot.com/p/swift-prompt-engineering-apples-foundationmodels) — SwiftLee Weekly · Issue 278 — Article · Topics: Foundation & Data Formats · Swift
  **Published:** `2025-07-01T14:14:53.000Z`
  **NeKI brief:** Explains A Swift Developer’s Guide to Prompt Engineering with Apple’s, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Apple’s On-Device Foundation Model Is Here.. But Is It Any Good?](https://ronnierocha.dev/blog/wwdc-2025-apples-on-device-foundation-model-is-here-but-is-it-any-good) — iOS Dev Weekly · Issue 716 — Article · Topics: AI Development · Apple Platform Ecosystem · Foundation & Data Formats
  **Published:** `27th June 2025`
  **NeKI brief:** Apple’s On-Device Foundation Model Is Here.. But Is It Any Good?. This link is retained as a technical reading lead for Apple-platform development.
- [These 4 code snippets won WWDC](https://justin.searls.co/posts/these-4-code-snippets-won-wwdc) — iOS Dev Weekly · Issue 715 — Article · Topics: AI Development · Apple Platform Ecosystem · Foundation & Data Formats
  **Published:** `20th June 2025`
  **NeKI brief:** Examines WWDC 2025 delivered on the one thing I was hoping to see from WWDC 2024: free, unlimited invocation of Apple's on-device language models by developers. It may…. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Don‘t Liquid Glass All the Things](https://david-smith.org/blog/2025/06/17/design-dary-liquid-glass-everything) — iOS Dev Weekly · Issue 715 — Article · Topics: AI Development · Apple Platform Ecosystem · Foundation & Data Formats
  **Published:** `20th June 2025`
  **NeKI brief:** Argues for deliberate adoption of Liquid Glass rather than applying it indiscriminately across an interface. It offers a design-review perspective for separating places where the new material improves hierarchy from places where it distracts or weakens clarity.
- [Bringing On‑Device AI to Your App Using Apple’s Foundation Models](https://dimillian.medium.com/bringing-on-device-ai-to-your-app-using-apples-foundation-models-8a1df297eeaa) — Those Who Swift · Issue 219 — Article · Topics: AI Development · Foundation & Data Formats · Swift
  **Published:** `2025-06-19`
  **NeKI brief:** Discusses Bringing On-Device AI to your app: Using Apple's Foundation Models in a public developer resource. Use it to compare the author's concrete workflow and trade-offs with your project constraints, and verify any platform-specific claims against current primary documentation.
- [Updates to Apple’s On-Device and Server Foundation Language Models](https://machinelearning.apple.com/research/apple-foundation-models-2025-updates) — Fatbobman’s Swift Weekly · Issue 88 — Article · Topics: Foundation & Data Formats · Objective-C & Cocoa
  **Published:** `2025-06-12T02:52:10.753Z`
  **NeKI brief:** Apple's research update describes the Foundation Models family and 2025 model changes. Use it for technical model context and capability boundaries, while relying on platform documentation for app-facing APIs and availability.
- [parts here](https://alexanderlogan.co.uk/blog/wwdc25/02-apple-intelligence-tools) — Fatbobman’s Swift Weekly · Issue 88 — Article · Topics: AI Development · Apple Platform Ecosystem · Foundation & Data Formats
  **Published:** `2025-06-12T02:52:10.753Z`
  **NeKI brief:** Alex explains how developers can enhance on-device large language models with custom Swift tools letting their apps invoke system APIs or services (like HealthKit or network calls) and feed the real results back into the AI for richer responses.
- [Demystifying Picture in Picture on iOSA deep dive into using PiP mode.Artem Novichkov](https://www.artemnovichkov.com/blog/demystifying-picture-in-picture-on-ios?ref=createwithswift.com) — Create with Swift · Issue 60 — Article · Topics: Foundation & Data Formats · Graphics, Media & Games · Swift
  **Published:** `2025-05-09T15:30:59.000Z`
  **NeKI brief:** Artem provides a practical guide for implementing Picture in Picture (PiP) functionality in iOS apps from setting up a camera feed using UIKit and AVFoundation, configuring the capture session, and enabling PiP mode.
- [FormattedListKit](https://github.com/chiahsien/FormattedListKit) — iOS Dev Tools · iOS Dev Tools: FormattedListKit, Libraried, Pressdeck — Source repository · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-04-17T13:23:18.210Z`
  **NeKI brief:** FormattedListKit provides formatted list components for SwiftUI or UIKit. Follow its source for concrete row layout, formatting, and interaction patterns, then check accessibility and platform compatibility before adoption.
- [Introducing swiftly 1.0](https://www.swift.org/blog/introducing-swiftly_10) — Those Who Swift · Issue 208 — Article · Topics: Developer Career & Practice · Foundation & Data Formats · Swift
  **Published:** `2025-04-02`
  **NeKI brief:** This technical resource covers Swiftly 1.0 as a Swift toolchain manager. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [MIT Introduction to Deep Learning | 6.S191](https://www.youtube.com/watch?v=alfdI7S6wCY) — Those Who Swift · Issue 204 — Video · Topics: Developer Community & Business · Foundation & Data Formats
  **Published:** `2025-03-05`
  **NeKI brief:** Reviews MIT Introduction to Deep Learning | 6.S191. Useful for evaluating the described Apple-platform or software-engineering topic, with current behavior and project-specific constraints verified against primary documentation.
- [NSAttributedString: Formatting Rich Text](https://www.swiftyplace.com/blog/nsattributedstring-swift) — Those Who Swift · Issue 202 — Article · Topics: Foundation & Data Formats · Swift
  **Published:** `2025-02-19`
  **NeKI brief:** Explains NSAttributedString formatting in Swift. Useful for constructing rich text while keeping attributes, ranges, and UIKit or SwiftUI rendering boundaries explicit.
- [ZIP Foundation](https://github.com/weichsel/ZIPFoundation) — iOS Dev Tools · iOS Dev Tools: Diagnostics, ZIP Foundation, WebKit — Source repository · Topics: Developer Tools · Foundation & Data Formats · Objective-C & Cocoa
  **Published:** `2025-02-06T17:32:00.627Z`
  **NeKI brief:** Provides the public source repository for ZIP Foundation. Inspect its implementation, examples, and issue history to evaluate integration boundaries and maintenance trade-offs before depending on it in an Apple-platform project.
- [WebKit](https://github.com/WebKit/WebKit) — iOS Dev Tools · iOS Dev Tools: Diagnostics, ZIP Foundation, WebKit — Source repository · Topics: Developer Tools · Foundation & Data Formats · Product Design
  **Published:** `2025-02-06T17:32:00.627Z`
  **NeKI brief:** WebKit is Apple’s open-source browser engine and framework implementation. Follow the repository for concrete engine architecture and platform behavior, but use current Apple documentation for supported public APIs and guarantees.
- [SwiftUI Navigation using the Router Pattern](https://tiagohenriques.vercel.app/blog/swiftui-navigation-router-pattern) — SwiftUI Weekly · SwiftUI Weekly - Issue #206 — Article · Topics: Foundation & Data Formats · Swift · SwiftUI
  **Published:** `2025-01-13T09:29:54.892Z`
  **NeKI brief:** Implements a router pattern for SwiftUI navigation with centralized route decisions. Useful for making deep links, modal presentation, and navigation tests deterministic while keeping views focused on rendering.
- [MongoKitten](https://github.com/orlandos-nl/MongoKitten) — Fatbobman’s Swift Weekly · Issue 65 — Source repository · Topics: Developer Tools · Foundation & Data Formats · Swift
  **Published:** `2025-01-06T12:02:39.656Z`
  **NeKI brief:** MongoKitten provides a pure-Swift MongoDB driver built on SwiftNIO. Follow it when evaluating asynchronous document-database access, connection lifecycle, and how a Swift server maps BSON operations into application models.
- [AVAudioEffectNode: Painless low level audio effects](https://orjpap.github.io/swift/low-level/audio/avfoundation/2024/09/19/avAudioEffectNode.html) — iOS Dev Weekly · Issue 680 — Article · Topics: Cross-Platform & Web · Developer Tools · Foundation & Data Formats
  **Published:** `30th September 2024`
  **NeKI brief:** Examines In a previous post, I covered two AVFoundation nodes that can generate sound or tap into the output of an existing node. If you experiment with them, you'll quickly realize:. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Reality Distortion](https://lmnt.me/blog/reality-distortion.html) — iOS Dev Weekly · Issue 680 — Article · Topics: Cross-Platform & Web · Foundation & Data Formats
  **Published:** `30th September 2024`
  **NeKI brief:** Examines Reality Distortion. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Morphology](https://lickability.com/blog/morphology-in-swift) — iOS Dev Weekly · Issue 678 — Article · Topics: Foundation & Data Formats · Swift
  **Published:** `13th September 2024`
  **NeKI brief:** Presents morphology for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [An Xcode Detective Story](https://www.emergetools.com/blog/posts/the-memory-leak-an-xcode-detective-story) — iOS Dev Weekly · Issue 678 — Article · Topics: Foundation & Data Formats · Xcode
  **Published:** `13th September 2024`
  **NeKI brief:** Jacob describes how he tracked down a memory leak that caused a double navigation bug in an iOS app providing a detailed breakdown of the bug and the process he went through to resolve it.
- [SwiftUI can be a bit... eager](https://www.attributedstrings.com/swiftui-can-be-a-bit-eager) — SwiftUI Weekly · SwiftUI Weekly - Issue #193 — Article · Topics: Foundation & Data Formats · Swift · SwiftUI
  **Published:** `2024-07-08T08:54:13.719Z`
  **NeKI brief:** Investigates cases where SwiftUI evaluates views or work eagerly. Useful for diagnosing unexpected initialization, expensive computations, and lifecycle assumptions in declarative hierarchies.
- [Tuist](https://tuist.io/) — iOS Dev Tools · iOS Dev Tools: Pricetag, Tuist, Snapshots — Article · Topics: Architecture · Developer Tools · Foundation & Data Formats
  **Published:** `2024-06-27T16:03:43.649Z`
  **NeKI brief:** Tuist provides project generation and automation for Xcode-based applications. Evaluate it when scaling modular projects, balancing reproducibility and abstraction against Xcode project complexity.
- [and others](https://machinelearning.apple.com/research/introducing-apple-foundation-models) — iOS Dev Weekly · Issue 665 — Article · Topics: Foundation & Data Formats · Objective-C & Cocoa · Security & Privacy
  **Published:** `14th June 2024`
  **NeKI brief:** We are constantly challenged to give up aspects of privacy with each cookie permission click-through and every pundit saying that privacy is dead. Apple’s first job is to show that it doesn’t need to be that way. Once that’s done, it must prove that Apple…
- [Compiler Technology vs Wrapper Solutions: Making the right foundational choice for mobile app protection (Webinar)](https://www.vpdae.com/redirect/3y4htre9r3p0xowgtwu1doba748) — iOS Dev Tools · iOS Dev Tools: Screenshot Studio, Moya, SkeletonView — Article · Topics: Foundation & Data Formats
  **Published:** `2024-05-23T13:40:50.650Z`
  **NeKI brief:** This webinar discusses compiler technology versus wrapper solutions for mobile app protection. Follow it for concrete security trade-offs if the material is accessible, while distinguishing the event promotion from independent technical evidence.
- [Converting Codable Models To CSV](https://digitalbunker.dev/converting-codable-models-to-csv?issue=029) — Fatbobman’s Swift Weekly · Issue 29 — Article · Topics: Developer Tools · Foundation & Data Formats · Swift
  **Published:** `2024-04-29T12:02:14.611Z`
  **NeKI brief:** Shows mapping Codable models into CSV rows, including the column-order and value-conversion decisions serialization requires. Follow it when exporting Swift domain data for reports or interoperability rather than JSON APIs.
- [Dispatching to the Main thread with MainActor in Swift](https://www.donnywals.com/dispatching-to-the-main-thread-with-mainactor-in-swift?issue=029) — Fatbobman’s Swift Weekly · Issue 29 — Article · Topics: Concurrency · Foundation & Data Formats · Swift
  **Published:** `2024-04-29T12:02:14.611Z`
  **NeKI brief:** Compares dispatching work to the main actor with older main-queue patterns in Swift concurrency. Use it to clarify isolation boundaries and diagnostics, then adapt the examples to the project's strict-concurrency settings.
- [EditKit](https://apps.apple.com/us/app/editkit-pro/id1659984546) — iOS Dev Tools · iOS Dev tools: EditKit, Copilot for Xcode, PhoneNumberKit — Article · Topics: Foundation & Data Formats · Swift · SwiftUI
  **Published:** `2024-04-11T14:16:07.847Z`
  **NeKI brief:** EditKit Pro is an Xcode editor extension offering utilities such as formatting and Codable-model generation. Its page is a concrete lead for extending the editor to remove repetitive source-writing tasks.
- [AnandaModel](https://github.com/nixzhu/Ananda) — iOS Dev Tools · iOS Dev tools: Ducky Model Editor, LocalizApp, Brewer X — Source repository · Topics: Developer Tools · Foundation & Data Formats · Swift
  **Published:** `2024-03-28T15:43:54.859Z`
  **NeKI brief:** AnandaModel generates or represents Swift models from structured data. Follow its source for concrete Codable or model-generation behavior, while checking output compatibility and maintenance before integrating it.
- [Reading and Writing Spatial Video with AVFoundation](https://www.finnvoorhees.com/words/reading-and-writing-spatial-video-with-avfoundation) — iOS Dev Weekly · Issue 643 — Article · Topics: Foundation & Data Formats · Graphics, Media & Games
  **Published:** `12th January 2024`
  **NeKI brief:** What does MV-HEVC mean to you? I hadn’t heard of it, either, until I read this great post from Finn Voorhees on the additions to AVFoundation that allow reading and writing of spatial video files.
- [MV-HEVC](http://hevc.info/mvhevc) — iOS Dev Weekly · Issue 643 — Article · Topics: Foundation & Data Formats · Graphics, Media & Games
  **Published:** `12th January 2024`
  **NeKI brief:** Examines HEVC Multiview Extension (MV-HEVC) resources. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Swift strings look identical but aren’t](https://damian.fyi/swift/2023/11/13/swift-strings-look-identical-but-aren't.html) — iOS Dev Weekly · Issue 636 — Article · Topics: Cross-Platform & Web · Foundation & Data Formats · Swift
  **Published:** `17th November 2023`
  **NeKI brief:** The page covers “Swift strings look identical but aren’t” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [The Absolute Minimum Every Software Developer Must Know About Unicode in 2023 (Still No Excuses!)](https://tonsky.me/blog/unicode) — Fatbobman’s Swift Weekly · Issue 5 — Article · Topics: Foundation & Data Formats · Swift · SwiftData
  **Published:** `2023-11-06T22:30:15.675Z`
  **NeKI brief:** Explains Unicode fundamentals and common misconceptions that still cause text-processing bugs. Use it when reviewing Swift string handling, normalization, grapheme boundaries, and serialization across user-visible content and external systems.
- [2023 年每个软件开发者都必须知道的关于 Unicode 的最基本的知识（仍然不准找借口！）](https://blog.xinshijiededa.men/unicode) — Fatbobman’s Swift Weekly · Issue 5 — Article · Topics: Foundation & Data Formats · Swift · SwiftData
  **Published:** `2023-11-06T22:30:15.675Z`
  **NeKI brief:** Provides a Chinese-language treatment of Unicode basics and the pitfalls of assuming characters map directly to bytes or code points. Follow it as complementary reading when internationalized Swift text behavior needs careful validation.
- [🎉 Fastlane officially moves to the Mobile Native Foundation](https://github.com/MobileNativeFoundation/discussions/discussions/194) — iOS CI Newsletter · Issue 28 — Source repository · Topics: CI/CD & Automation · Developer Tools · Foundation & Data Formats
  **Published:** `2023-11-05T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for Fastlane might be moving to Mobile Native Foundation!, relevant to CI/CD & Automation and Developer Tools. Inspect its implementation, open issues, and release state before adopting the approach.
- [Interoperability: Swift’s Super Power](https://speakinginswift.substack.com/p/interoperability-swifts-super-power) — Fatbobman’s Swift Weekly · Issue 2 — Article · Topics: Foundation & Data Formats · Swift · Xcode
  **Published:** `2023-10-16T22:30:04.937Z`
  **NeKI brief:** A Speaking in Swift essay explores interoperability as one of Swift's defining strengths. Follow it for community perspective on bridging and adoption, then verify compiler, ABI, and framework specifics independently.
- [Foundation Package Preview Now Available](https://www.swift.org/blog/foundation-preview-now-available) — iOS Dev Weekly · Issue 607 — Article · Topics: Foundation & Data Formats · Swift
  **Published:** `28th April 2023`
  **NeKI brief:** Examines I’m pleased to announce that a preview of the future of Foundation is now available on GitHub!. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [thanks for the help, Adam](https://mastodon.scot/@opticalaberration/109797428008332504) — iOS Dev Weekly · Issue 595 — Article · Topics: Foundation & Data Formats · Swift
  **Published:** `3rd February 2023`
  **NeKI brief:** The public Mastodon status contains a readable post thanking Adam for help and preserves the linked social discussion context.
- [Cloud Native Computing Foundation](https://www.cncf.io/projects) — iOS Dev Weekly · Issue 595 — Article · Topics: Foundation & Data Formats · Swift
  **Published:** `3rd February 2023`
  **NeKI brief:** Examines Graduated and incubating projects are considered stable and are used successfully in production environments. View metrics of CNCF projects moving through the…. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [MarkCodable reports](https://trycombine.com/posts/using-markcodable-to-generate-reports) — iOS CI Newsletter · Issue 5 — Article · Topics: Combine & Reactive Programming · Developer Tools · Foundation & Data Formats
  **Published:** `2022-12-18T00:00:00.000Z`
  **NeKI brief:** Examines MarkCodable reports in the context of Combine & Reactive Programming and Developer Tools. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [MarkCodable](https://github.com/MarkCodable/MarkCodable) — iOS CI Newsletter · Issue 5 — Source repository · Topics: Developer Tools · Foundation & Data Formats
  **Published:** `2022-12-18T00:00:00.000Z`
  **NeKI brief:** Provides the source and change history for MarkCodable, relevant to Developer Tools and Foundation & Data Formats. Inspect its implementation, open issues, and release state before adopting the approach.
- [The Future of Foundation](https://www.swift.org/blog/future-of-foundation) — iOS Dev Weekly · Issue 589 — Article · Topics: Foundation & Data Formats · Swift
  **Published:** `16th December 2022`
  **NeKI brief:** Explores The Future of Foundation, focusing on the last thing i was expecting as we wind down. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [The SwiftUI Layout Protocol - Part 2](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3N3aWZ0dWktbGFiLmNvbS9sYXlvdXQtcHJvdG9jb2wtcGFydC0yLz91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6ImYyZTA5NDQxLWI0OWQtNDY2Ni1iZGY0LWNhMDE1ZWNmYTdiMSIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiJlYzNhYzhhNC01YThhLTQzZGUtYmY3OC1jMGViNTNmMWZlZjUiLCJpYXQiOjE2NzQwNjI1NTguMDk2LCJpc3MiOiJvcmNoaWQifQ._glPwaca1iVFJwupEeTdogDJhpWE9AaEf-Mko6Z_onA) — SwiftUI Weekly · SwiftUI Weekly - Issue #114 — Article · Topics: Foundation & Data Formats · Swift · SwiftUI
  **Published:** `2022-09-13T16:37:55.000Z`
  **NeKI brief:** Continues custom SwiftUI Layout implementation techniques. Use it when caching, placement, and subview proposals need deliberate control for performance.
- [Introducing MarkCodable](https://trycombine.com/posts/introducing-markcodable) — iOS Dev Weekly · Issue 575 — Article · Topics: Combine & Reactive Programming · Foundation & Data Formats · Persistence & Synchronisation
  **Published:** `9th September 2022`
  **NeKI brief:** Introduces MarkCodable as a Markdown-backed alternative for Codable data, aimed at small tools where files should remain easy to inspect, parse, and edit by hand. Useful when JSON readability is part of the workflow.
- [the Difference library](https://github.com/krzysztofzablocki/Difference?ref=ioscodereview.com) — iOS Code Review · Issue 28 — Source repository · Topics: Developer Tools · Foundation & Data Formats · Testing
  **Published:** `2022-07-28T11:12:02.000Z`
  **NeKI brief:** Provides the source and change history for the Difference library, relevant to Developer Tools and Foundation & Data Formats. Inspect its implementation, open issues, and release state before adopting the approach.
- [How to test custom Codable initializer | Danijela's blog](https://danijelavrzan.com/posts/2022/07/how-to-test-custom-codable?ref=ioscodereview.com) — iOS Code Review · Issue 28 — Article · Topics: Foundation & Data Formats · Testing
  **Published:** `2022-07-28T11:12:02.000Z`
  **NeKI brief:** Walks through how to test custom Codable initializer | Danijela's blog, with practical context for Foundation & Data Formats and Testing. Use it when implementing the workflow, while checking current tool and platform versions before copying the setup.
- [on the Swift Forums](https://forums.swift.org/t/deepcodable-encode-and-decode-deeply-nested-data-into-flat-swift-objects/59136) — iOS Dev Weekly · Issue 568 — Article · Topics: Foundation & Data Formats · Swift
  **Published:** `22nd July 2022`
  **NeKI brief:** Explores on the Swift Forums, focusing on he wrote more about it on the swift forums if you want more context. Follow it to assess the approach, its trade-offs, and where it fits in a current Swift or Apple-platform project.
- [MVC for SwiftUI with Boutique](https://build.ms/2022/06/22/model-view-controller-store) — iOS Dev Weekly · Issue 564 — Article · Topics: Foundation & Data Formats · Swift · SwiftUI
  **Published:** `24th June 2022`
  **NeKI brief:** Explores MVC for SwiftUI with Boutique, focusing on this is a really long blog post from joe fabisevich,. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [CodableFirebase](https://github.com/alickbass/CodableFirebase?ref=ioscodereview.com) — iOS Code Review · Issue 21 — Source repository · Topics: Developer Tools · Foundation & Data Formats
  **Published:** `2022-04-21T11:21:14.000Z`
  **NeKI brief:** Provides the source and change history for CodableFirebase, relevant to Developer Tools and Foundation & Data Formats. Inspect its implementation, open issues, and release state before adopting the approach.
- [comprehensive guide](https://peterfriese.dev/posts/firestore-codable-the-comprehensive-guide?ref=ioscodereview.com) — iOS Code Review · Issue 21 — Article · Topics: Foundation & Data Formats
  **Published:** `2022-04-21T11:21:14.000Z`
  **NeKI brief:** Examines comprehensive guide in the context of Foundation & Data Formats. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [this document on ICU System Time Zones](https://unicode-org.github.io/icu/userguide/datetime) — iOS Dev Weekly · Issue 545 — Article · Topics: Developer Tools · Foundation & Data Formats
  **Published:** `11th February 2022`
  **NeKI brief:** Presents this document on ICU System Time Zones, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [the official Unicode documentation](http://unicode.org/reports/tr35/tr35-31/tr35-dates.html?ref=ioscodereview.com) — iOS Code Review · Issue 14 — Article · Topics: Cross-Platform & Web · Foundation & Data Formats · Testing
  **Published:** `2022-01-13T12:22:06.000Z`
  **NeKI brief:** Examines the official Unicode documentation in the context of Cross-Platform & Web and Foundation & Data Formats. Use it to understand the linked technique or tool, then validate its assumptions against the current project and primary documentation.
- [Displaying mathematical fractions](https://coderexmachina.medium.com/displaying-mathematical-fractions-in-swiftui-6a4dd625d842) — iOS Dev Weekly · Issue 533 — Tutorial · Topics: Developer Community & Business · Foundation & Data Formats · Swift
  **Published:** `12th November 2021`
  **NeKI brief:** Explores displaying mathematical fractions that lack a matching Unicode glyph in SwiftUI. A focused typography and layout reference for educational, scientific, or recipe interfaces where a plain slash is not visually adequate.
- [New approach to formatters in iOS 15](https://nemecek.be/blog/106/new-approach-to-formatters-in-ios-15) — iOS Dev Weekly · Issue 512 — Article · Topics: Foundation & Data Formats
  **Published:** `18th June 2021`
  **NeKI brief:** Examines Personal site of Filip Němeček with blog, selected projects, apps and more. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [discussion forums](https://github.com/MobileNativeFoundation/discussions/discussions) — iOS Dev Weekly · Issue 497 — Source repository · Topics: Developer Tools · Foundation & Data Formats
  **Published:** `5th March 2021`
  **NeKI brief:** There are plenty of individuals and small teams writing about their iOS development experiences, but it’s a little rarer for people to discuss the issues and challenges facing larger teams publicly. The project’s primary focus for today seems to be the…
- [AutomaticSettings](https://github.com/krzysztofzablocki/AutomaticSettings) — iOS Dev Weekly · Issue 489 — Source repository · Topics: Developer Tools · Foundation & Data Formats · Graphics, Media & Games
  **Published:** `8th January 2021`
  **NeKI brief:** Examines AutomaticSettings, focusing on this new library from krzysztof zabłocki is interesting. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Sourcery](https://github.com/krzysztofzablocki/Sourcery) — iOS Dev Weekly · Issue 489 — Source repository · Topics: Developer Tools · Foundation & Data Formats · Graphics, Media & Games
  **Published:** `8th January 2021`
  **NeKI brief:** Sourcery parses Swift source with templates to generate repetitive implementations such as mocks, equality, or Codable support. Use it when generated boilerplate has stable conventions and the templates can be reviewed as part of source control.
- [intro video](https://www.youtube.com/watch?v=MTY9m2--tiA) — iOS Dev Weekly · Issue 489 — Video · Topics: Foundation & Data Formats · Graphics, Media & Games · Swift
  **Published:** `8th January 2021`
  **NeKI brief:** Provides the linked introductory technical video referenced by the issue. Useful as audiovisual context for the surrounding topic, while any API or implementation claims should be verified against primary documentation.
- [Parsing Tricky JSON With Codable in Swift](https://www.andyibanez.com/posts/parsing-tricky-json-codable-swift) — iOS Dev Weekly · Issue 480 — Article · Topics: Foundation & Data Formats · Swift
  **Published:** `30th October 2020`
  **NeKI brief:** Examines Parsing Tricky JSON With Codable in Swift, offering practical guidance on data modeling and persistence trade-offs. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Save Custom Codable Types in AppStorage or SceneStorage](https://lostmoa.com/blog/SaveCustomCodableTypesInAppStorageOrSceneStorage) — iOS Dev Weekly · Issue 472 — Article · Topics: Foundation & Data Formats · Swift · SwiftUI
  **Published:** `4th September 2020`
  **NeKI brief:** Examines Save Custom Codable Types in AppStorage or SceneStorage, offering practical guidance on data modeling and persistence trade-offs. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [ResilientDecoding](https://github.com/airbnb/ResilientDecoding) — iOS Dev Weekly · Issue 452 — Source repository · Topics: Developer Tools · Foundation & Data Formats
  **Published:** `17th April 2020`
  **NeKI brief:** Presents ResilientDecoding, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [MarkdownAttributedString](https://github.com/chockenberry/MarkdownAttributedString) — iOS Dev Weekly · Issue 445 — Source repository · Topics: Developer Tools
  **Published:** `28th February 2020`
  **NeKI brief:** The page covers “MarkdownAttributedString” for Apple-platform development or software practice. Follow it for the concrete subject and examples presented there, while verifying version-sensitive details and implementation assumptions against current primary documentation.
- [DefaultCodable](https://github.com/gonzalezreal/DefaultCodable) — iOS Dev Weekly · Issue 443 — Source repository · Topics: Developer Tools · Foundation & Data Formats
  **Published:** `14th February 2020`
  **NeKI brief:** Examines DefaultCodable, focusing on the author’s note that like this µpackage idea from guille gonzalez. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Caching in Swift](https://www.swiftbysundell.com/posts/caching-in-swift) — iOS Dev Weekly · Issue 419 — Article · Topics: Foundation & Data Formats · Performance · Swift
  **Published:** `30th August 2019`
  **NeKI brief:** Examines Caching in Swift, offering practical guidance on networking and asynchronous reliability. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [ZippyJSON](https://github.com/michaeleisel/ZippyJSON) — iOS Dev Weekly · Issue 419 — Source repository · Topics: Developer Tools · Foundation & Data Formats · Performance
  **Published:** `30th August 2019`
  **NeKI brief:** NSJSONSerialization is probably fast enough for 99% of cases, and I’d recommend using it whenever possible. However, if you’re often parsing a lot of JSON then the performance wins in this library from Michael Eisel might be what you need.
- [NSAttributedStringBuilder](https://github.com/ethanhuang13/NSAttributedStringBuilder) — iOS Dev Weekly · Issue 412 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `12th July 2019`
  **NeKI brief:** Examines NSAttributedStringBuilder, focusing on swiftui makes the construction of views and ui easy. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [BinaryCodable](https://github.com/jverkoey/BinaryCodable) — iOS Dev Weekly · Issue 392 — Source repository · Topics: Developer Tools · Foundation & Data Formats
  **Published:** `22nd February 2019`
  **NeKI brief:** Examines Swift Codable-like interfaces for binary representations. - jverkoey/BinaryCodable. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Path.swift](https://github.com/mxcl/Path.swift) — iOS Dev Weekly · Issue 388 — Source repository · Topics: Developer Tools · Foundation & Data Formats · Swift
  **Published:** `25th January 2019`
  **NeKI brief:** Examines Path.swift, focusing on the url/path manipulation methods in foundation have always been powerful, but also very verbose so this new wrapper…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Fun with Unicode in Swift](https://tworingsoft.com/blog/2018/12/10/fun-with-unicode-in-swift.html) — iOS Dev Weekly · Issue 382 — Article · Topics: Cross-Platform & Web · Foundation & Data Formats · Swift
  **Published:** `14th December 2018`
  **NeKI brief:** Examines Looking at some ways to write tricky Swift code using Unicode. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [How to Extend LLDB to Provide a Better Debugging Experience](https://pspdfkit.com/blog/2018/how-to-extend-lldb-to-provide-a-better-debugging-experience) — iOS Dev Weekly · Issue 373 — Article · Topics: Developer Tools · Foundation & Data Formats
  **Published:** `12th October 2018`
  **NeKI brief:** The article explains how to extend LLDB with custom tooling to improve debugging workflows for developers.
- [The Big List of Naughty Strings](https://github.com/minimaxir/big-list-of-naughty-strings) — iOS Dev Weekly · Issue 341 — Source repository · Topics: Developer Tools · Foundation & Data Formats · Testing
  **Published:** `2nd March 2018`
  **NeKI brief:** Examines So the latest Unicode crash bug was fixed recently, and obviously Apple are going to take care of these on an operating system level. But do you test your apps with anything that’s not standard? Maybe you should give thi Useful for understanding the concrete implementation trade-offs in this Apple-platform topic before applying the technique to a production codebase.
- [Serialization - Speed and Size](https://holtwick.de/blog/serialization) — iOS Dev Weekly · Issue 339 — Tutorial · Topics: Developer Community & Business · Foundation & Data Formats · Objective-C & Cocoa
  **Published:** `16th February 2018`
  **NeKI brief:** Walks through Serialization - Speed and Size with practical Apple-platform examples. Use it to understand the underlying workflow, identify assumptions and trade-offs, and adapt the ideas carefully while checking API availability and behavior against current SDK documentation.
- [quicktype](https://github.com/quicktype/quicktype-xcode) — iOS Dev Weekly · Issue 333 — Source repository · Topics: Developer Tools · Swift · Xcode
  **Published:** `5th January 2018`
  **NeKI brief:** Examines quicktype, focusing on this xcode extension created by david siegel takes in raw json and spits out swift structs to represent the data. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Chronology](https://github.com/davedelong/Chronology) — iOS Dev Weekly · Issue 328 — Source repository · Topics: Developer Tools · Foundation & Data Formats · Swift
  **Published:** `24th November 2017`
  **NeKI brief:** Examines Chronology, focusing on former apple software engineer and developer evangelist dave delong is taking on the challenge of creating a swifty date…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Introducing Kitura 2.0](https://developer.ibm.com/swift/2017/10/30/kitura-20) — iOS Dev Weekly · Issue 327 — Article · Topics: Foundation & Data Formats · Navigation & Deep Linking · Swift
  **Published:** `17th November 2017`
  **NeKI brief:** Explores Introducing Kitura 2.0 in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [codable routing](https://developer.ibm.com/swift/2017/10/30/codable-routing) — iOS Dev Weekly · Issue 327 — Article · Topics: Foundation & Data Formats · Navigation & Deep Linking · Swift
  **Published:** `17th November 2017`
  **NeKI brief:** The linked IBM Developer material concerns Codable routing in Swift and provides openly readable developer documentation, although the original URL now lands on a broader technology page.
- [Codable Dates](https://littlebitesofcocoa.com/316-codable-dates) — iOS Dev Weekly · Issue 315 — Article · Topics: Foundation & Data Formats · Objective-C & Cocoa · Swift
  **Published:** `25th August 2017`
  **NeKI brief:** Examines In Bite 315 (https://littlebitesofcocoa.com/315) we started looking at the new Codable protocol in Swift 4. Today we'll learn how to work with Date types when encoding and deco. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Disk](https://github.com/saoudrizwan/Disk) — iOS Dev Weekly · Issue 314 — Source repository · Topics: Developer Tools · Foundation & Data Formats
  **Published:** `18th August 2017`
  **NeKI brief:** Now that JSON encoding/decoding is a solved problem let’s move the solution up the chain a bit? Disk is a new library from Saoud Rizwan which takes anything that can be stored with Codable, as well as images and other binary data and persists it to the ……
- [Guitar](https://github.com/ArtSabintsev/Guitar) — iOS Dev Weekly · Issue 290 — Source repository · Topics: Developer Tools · Foundation & Data Formats · Swift
  **Published:** `3rd March 2017`
  **NeKI brief:** Examines Guitar, focusing on ever found the string class … lacking? arthur sabintsev has put together an extension library which already includes…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Measurements and Units in Foundation](http://oleb.net/blog/2016/07/measurements-and-units) — iOS Dev Weekly · Issue 261 — Article · Topics: Foundation & Data Formats
  **Published:** `29th July 2016`
  **NeKI brief:** Examines An introduction to the new measurements and units family of types in Foundation in iOS 10 and macOS 10.12. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [TextAttributes: An easier way to compose attributed strings](https://github.com/delba/TextAttributes) — iOS Dev Weekly · Issue 246 — Source repository · Topics: Developer Tools
  **Published:** `15th April 2016`
  **NeKI brief:** Presents TextAttributes: An easier way to compose attributed strings, providing concrete engineering context that Apple-platform developers can use when evaluating the described technique or workflow.
- [notable pull requests](https://github.com/apple/swift-corelibs-foundation/pull/54) — iOS Dev Weekly · Issue 228 — Source repository · Topics: Developer Tools · Foundation & Data Formats · Swift
  **Published:** `11th December 2015`
  **NeKI brief:** Examines The Foundation Project, providing core utilities, internationalization, and OS independence - NSJSONSerialization JSONObjectWithData: implementation by argon · Pull Request #54 · s. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Swift Foundation](https://github.com/apple/swift-corelibs-foundation) — iOS Dev Weekly · Issue 227 — Source repository · Topics: Developer Tools · Foundation & Data Formats · Swift
  **Published:** `4th December 2015`
  **NeKI brief:** The final huge piece of news that accompanied yesterday’s release was that there is a Swift implementation of Foundation in progress and they are aiming for parity with Obj-C Foundation for the release of Swift 3. The goals of this are mainly focused around…
- [Response to recent security concerns in AFNetworking](https://gist.github.com/AlamofireSoftwareFoundation/f784f18f949b95ab733a) — iOS Dev Weekly · Issue 196 — Source repository · Topics: Developer Tools · Networking · Security & Privacy
  **Published:** `1st May 2015`
  **NeKI brief:** The gist contains a public response to security concerns in AFNetworking, documenting the maintainers' technical position and remediation context.
- [The Death of Cocoa](http://nshipster.com/the-death-of-cocoa) — iOS Dev Weekly · Issue 179 — Article · Topics: Foundation & Data Formats · Objective-C & Cocoa · Swift
  **Published:** `2nd January 2015`
  **NeKI brief:** Explains The Death of Cocoa with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Strings in Swift](http://oleb.net/blog/2014/07/swift-strings) — iOS Dev Weekly · Issue 153 — Article · Topics: Foundation & Data Formats · Swift
  **Published:** `4th July 2014`
  **NeKI brief:** Swift strings represent Unicode text rather than random-access byte arrays, making character traversal and slicing semantics explicit. The article explains why correctness across grapheme clusters requires different algorithms.
- [Joris Kluivers has us covered](http://joris.kluivers.nl/blog/2014/04/08/the-builder-pattern-in-objective-c-foundation) — iOS Dev Weekly · Issue 141 — Article · Topics: Foundation & Data Formats · Objective-C & Cocoa
  **Published:** `11th April 2014`
  **NeKI brief:** Examines In a recent blog post Klaas Pieter Annema wrote about using the builder pattern in Objective-C. Inspired by his post I created two categories that …. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [NSURLProtocol](http://www.raywenderlich.com/59982/nsurlprotocol-tutorial) — iOS Dev Weekly · Issue 135 — Tutorial · Topics: Foundation & Data Formats · Networking
  **Published:** `28th February 2014`
  **NeKI brief:** Explains NSURLProtocol with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [NSString and Unicode](http://www.objc.io/issue-9/unicode.html) — iOS Dev Weekly · Issue 133 — Article · Topics: Cross-Platform & Web · Foundation & Data Formats · Testing
  **Published:** `14th February 2014`
  **NeKI brief:** Explains NSString and Unicode with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Glimpse](https://github.com/wess/Glimpse) — iOS Dev Weekly · Issue 87 — Source repository · Topics: Developer Tools · Foundation & Data Formats · Graphics, Media & Games
  **Published:** `29th March 2013`
  **NeKI brief:** Examines UIView recording library. Contribute to wess/Glimpse development by creating an account on GitHub. Follow it when evaluating the implementation choices, constraints, or workflow described on this page in an Apple-platform project.
- [Slash](https://github.com/chrisdevereux/Slash) — iOS Dev Weekly · Issue 73 — Source repository · Topics: Developer Tools · Product Design
  **Published:** `21st December 2012`
  **NeKI brief:** Provides the Slash source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Date and Time Handling in Cocoa Cheat Sheet](http://oleb.net/blog/2011/11/date-and-time-in-cocoa-cheat-sheet) — iOS Dev Weekly · Issue 17 — Article · Topics: Foundation & Data Formats · Objective-C & Cocoa
  **Published:** `25th November 2011`
  **NeKI brief:** Collects Cocoa date and time API distinctions, useful for checking formatter, calendar, time-zone, and locale responsibilities before treating a Date as a user-facing value.
- [Apple Foundation Models: Hybrid AI with Dynamic Profiles](https://go.peterfriese.dev/what-i-am-working-on-hybrid-ai-apple-foundation-models-gemini?s=web&t=ext) — Not only Swift · Issue 101 — Article · Topics: AI Development · Foundation & Data Formats · Performance
  **NeKI brief:** Demonstrates a LanguageModelSession.DynamicProfile router that measures prompt token requirements before choosing the on-device system model or Firebase Gemini. It includes a fallback path and illustrates keeping one session API while varying provider, context capacity, and inference cost.
- [Play](https://youtube.com/watch?v=qx5QWrKhxM8) — Not only Swift · Issue 98 — Video · Topics: AI Development · Apple Platform Ecosystem · Foundation & Data Formats
  **NeKI brief:** Demonstrates a Firebase bridge that makes Gemini models available through Apple’s Foundation Models-style API. Use it to compare a cloud-model fallback with on-device sessions while keeping authentication, privacy, latency, and API compatibility explicit.
- [Claude](https://github.com/anthropics/ClaudeForFoundationModels) — Not only Swift · Issue 98 — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **NeKI brief:** Provides an adapter that exposes Claude through APIs shaped like Apple’s Foundation Models framework. Use the source to compare provider substitution and compatibility boundaries while accounting separately for cloud authentication, data transfer, latency, and cost.
- [Google](https://firebase.blog/posts/2026/06/apple-foundation-models-gemini) — Not only Swift · Issue 98 — Article · Topics: AI Development · Foundation & Data Formats
  **NeKI brief:** Shows how Firebase can route Gemini through an interface compatible with Apple’s Foundation Models framework. It is useful for designing a cloud fallback, provided privacy, authentication, offline behavior, and model-capability differences remain explicit.
- [Foundation Models framework utilities](https://github.com/apple/foundation-models-utilities) — Not only Swift · Issue 98 — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **NeKI brief:** Apple’s experimental utilities repository collects emerging patterns for Foundation Models applications. Use it to inspect concrete helpers and examples, while treating the package as exploratory material whose APIs and production guarantees may still change.
- [Perspective-Server: OpenAI-compatible API for Apple Foundation Models](https://github.com/Techopolis/Perspective-Server) — Not only Swift · Issue 95 — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **NeKI brief:** This source repository covers exposing Apple Foundation Models through an OpenAI-compatible local API. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Firebase AI Logic](https://firebase.google.com/products/firebase-ai-logic) — Not only Swift · Issue 87 — Article · Topics: AI Development · Foundation & Data Formats
  **NeKI brief:** Discusses Firebase AI Logic in a public developer resource. Use it to compare the author's concrete workflow and trade-offs with your project constraints, and verify any platform-specific claims against current primary documentation.
- [facade pattern](https://en.wikipedia.org/wiki/Facade_pattern) — Not only Swift · Issue 87 — Article · Topics: AI Development · Foundation & Data Formats
  **NeKI brief:** This reference entry covers the Facade design pattern and its interface boundary. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Foundation Models Playgrounds: Comprehensive Examples for Apple's AI Framework](https://github.com/IvanCampos/Foundation-Models-Playgrounds) — Not only Swift · Issue 85 — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **NeKI brief:** This source repository covers Foundation Models Framework examples for Apple-platform development. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [17 Xcode Hacks Every iOS Developer Should Know in 2025](https://swift-pal.com/17-xcode-hacks-every-ios-developer-should-know-in-2025-1f0edb5119b8) — Not only Swift · Issue 85 — Article · Topics: AI Development · Swift · Xcode
  **NeKI brief:** Describes 17 Xcode Hacks Every iOS Developer Should Know in 2025, focusing on practical tool integration and workflow trade-offs. Use it to evaluate reproducibility, trust boundaries, and debugging steps before adopting the approach in an Xcode project.
- [Olleh: Ollama-compatible CLI for Apple's Foundation Models](https://github.com/loopwork/olleh) — Not only Swift · Issue 83 — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **NeKI brief:** This source repository covers an Ollama-compatible command-line interface for Apple Foundation Models. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [example with your Genkit flows](https://genkit.dev/docs/plugins/ollama) — Not only Swift · Issue 83 — Article · Topics: AI Development · Foundation & Data Formats
  **NeKI brief:** This technical resource covers connecting local Ollama models to Genkit flows. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [An OpenAI-compatible server for Apple's Foundation Models](https://github.com/gety-ai/apple-on-device-openai) — Not only Swift · Issue 83 — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **NeKI brief:** This source repository covers serving Apple on-device models through an OpenAI-compatible API. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Ice Cubes](https://github.com/Dimillian/IceCubesApp) — Not only Swift · Issue 83 — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **NeKI brief:** Provides the public source repository for Ice Cubes. Inspect its implementation, examples, and issue history to evaluate integration boundaries and maintenance trade-offs before depending on it in an Apple-platform project.
