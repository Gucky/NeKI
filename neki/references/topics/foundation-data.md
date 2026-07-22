# Foundation & Data Formats

Third-party reading leads collected from NeKI sources. The links may be useful perspectives, but are not vetted recommendations or authoritative API guidance. NeKI publishes routing metadata, not the linked articles' text.

**Scope:** Foundation APIs, dates, text, Unicode, serialization, and data formats.

- Last collected: `2026-07-22T21:56:49Z`
- Indexed links shown: **116**

## Direct-source reading

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
  **NeKI brief:** Foundation Measurement combines a numeric value with a Unit, enabling conversion at API boundaries instead of manual scale factors. The article explains when runtime unit flexibility outweighs a static type-level encoding.
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
  **NeKI brief:** updateConstraints is the right hook for changing constraint definitions, while layout passes should not continually recreate them. The article maps Auto Layout work to lifecycle phases and prevents feedback-loop performance issues.
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
  **NeKI brief:** Keep mobile apps current through regular, scoped releases that combine platform compatibility work, defect fixes, and dependency maintenance. Frequent updates constrain technical debt and make urgent fixes smaller, safer, and easier to validate than long-delayed catch-up projects.

## Newsletter and related leads

- [Foundation Models Is Now a Hybrid Platform — and Picking the Tier Is the New Design Decision](https://www.wesleymatlock.com/foundation-models-hybrid-platform) — Those Who Swift · Issue 276 — Article · Topics: AI Development · Foundation & Data Formats · Navigation & Deep Linking
  **Published:** `2026-07-22T20:01:13.378Z`
  **NeKI brief:** Frames model-tier selection as a feature-level architectural decision, with session creation and graceful fallback kept behind a focused boundary. Useful when designing a Foundation Models feature that may choose on-device, cloud, or frontier capability paths.
- [Apple Foundation Models in iOS 27: The Complete Builder Guide](https://chatforest.com/builders-log/apple-foundation-models-ios-27-on-device-llm-api-builder-guide) — Those Who Swift · Issue 276 — Article · Topics: AI Development · Foundation & Data Formats
  **Published:** `2026-07-22T20:01:13.378Z`
  **NeKI brief:** Maps an on-device Foundation Models stack from model capability through app logic, tool calls, availability, and optional fine-tuning. Follow it when scoping a local AI feature, while validating beta hardware, privacy, and storage constraints independently.
- [Foundation Models in iOS 27: Tool-Calling Control](https://blakecrosley.com/blog/foundation-models-tool-calling-ios-27) — Those Who Swift · Issue 275 — Article · Topics: AI Development · Foundation & Data Formats · Objective-C & Cocoa
  **Published:** `2026-07-15`
  **NeKI brief:** Shows how tool calling and local OCR or barcode capabilities can fit into Foundation Models workflows.
- [WWDC 2026 Developer Tools: Xcode 27, Swift, Foundation Models](https://andrew.ooo/answers/wwdc-2026-developer-tools-xcode-swift-foundation-models-june-2026) — Those Who Swift · Issue 275 — Article · Topics: Apple Platform Ecosystem · Foundation & Data Formats · Swift
  **Published:** `2026-07-15`
  **NeKI brief:** Surveys the WWDC 2026 developer-tool changes across Xcode, Swift, and Foundation Models. Use it as a release-oriented map of new workflows, then verify specific APIs, deployment requirements, and availability in Apple's current documentation.
- [ZMarkupParser](https://github.com/ZhgChgLi/ZMarkupParser) — iOS Dev Tools · iOS Dev Tools: Footprint, ZMarkupParser, Lettera — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `2026-06-18T16:02:35.381Z`
  **NeKI brief:** A pure-Swift HTML-to-NSAttributedString parser that repairs malformed markup, supports custom tags and styles, and can render, strip, or select content. Its thread-safe implementation and performance report make it a concrete alternative to Foundation HTML parsing.
- [Testing Foundation Models: Code That Won’t Give The Same Answer Twice](https://www.wesleymatlock.com/testing-on-device-ai-swift-testing) — Those Who Swift · Issue 271 — Article · Topics: AI Development · Foundation & Data Formats · Testing
  **Published:** `2026-06-18`
  **NeKI brief:** Discusses testing nondeterministic Foundation Models output with Swift Testing. Use it when designing assertions for on-device AI, focusing on stable structure, bounded behavior, and controlled inputs instead of brittle exact-text comparisons.
- [Using Claude With Apple Foundation Models](https://artemnovichkov.com/blog/using-claude-with-apple-foundation-models) — Those Who Swift · Issue 271 — Article · Topics: AI Development · Foundation & Data Formats
  **Published:** `2026-06-18`
  **NeKI brief:** Explores combining Claude with Apple Foundation Models in an Apple-platform workflow. Use it when comparing cloud-model assistance with on-device generation, especially around handoff boundaries, privacy, and feature availability.
- [Whats new in SwiftUI in iOS 27](https://onmyway133.com/posts/whats-new-in-swiftui-in-ios-27) — iOS Dev Weekly · Issue 754 — Article · Topics: Foundation & Data Formats · Swift · SwiftUI
  **Published:** `12th June 2026`
  **NeKI brief:** Presents whats new in swiftui in ios 27 for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Modern Swift Library Architecture](https://coenttb.com/en/blog/4-1-the-swift-package) — Fatbobman’s Swift Weekly · Issue 132 — Article · Topics: Architecture · Foundation & Data Formats · Swift
  **Published:** `2026-04-20T12:03:00.641Z`
  **NeKI brief:** Describes a layered Swift package ecosystem spanning primitives, standards, and foundations. Use it to study package-boundary design and dependency layering when a growing library family needs more than one monolithic module.
- [Top 10 Developer Tools Apple Introduced At WWDC25](https://fline.dev/blog/top-10-developer-tools-apple-introduced-at-wwdc25) — Those Who Swift · Issue 260 — Article · Topics: AI Development · Apple Platform Ecosystem · Foundation & Data Formats
  **Published:** `2026-04-01`
  **NeKI brief:** Examines Top 10 Developer Tools Apple Introduced At WWDC25, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Conduit](https://github.com/christopherkarani/Conduit) — Fatbobman’s Swift Weekly · Issue 129 — Source repository · Topics: AI Development · Developer Career & Practice · Developer Tools
  **Published:** `2026-03-30T12:03:55.935Z`
  **NeKI brief:** Conduit is a unified SDK for working with multiple LLM providers. Use it when an application needs provider substitution behind one interface, while keeping model-specific capabilities and cost differences visible to callers.
- [Colony](https://github.com/christopherkarani/Colony) — Fatbobman’s Swift Weekly · Issue 129 — Source repository · Topics: AI Development · Developer Career & Practice · Developer Tools
  **Published:** `2026-03-30T12:03:55.935Z`
  **NeKI brief:** Colony is an agent runtime built around Apple Foundation Models. Use it to explore agent orchestration on-device, especially where tool execution, memory, and model-session lifecycle need a framework-level boundary.
- [Apple Foundation Models In Practice: Building On-Device AI Features In Swift](https://medium.com/@wesleymatlock/apple-foundation-models-in-practice-building-on-device-ai-features-in-swift-b6243976af4f) — Those Who Swift · Issue 259 — Article · Topics: AI Development · Foundation & Data Formats · Swift
  **Published:** `2026-03-26`
  **NeKI brief:** Examines Apple Foundation Models In Practice: Building On-Device AI Features In Swift, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Swift At Scale: Building The TelemetryDeck Analytics Service](https://www.swift.org/blog/building-privacy-first-analytics-with-swift) — Those Who Swift · Issue 257 — Article · Topics: Foundation & Data Formats · Security & Privacy · Swift
  **Published:** `2026-03-11`
  **NeKI brief:** Describes building a privacy-first analytics service in Swift and the engineering choices behind it. Follow it when evaluating telemetry architecture, data minimization, and server-side Swift trade-offs without treating the service design as an app recipe.
- [SwiftUI Foundations Q&A: Build Great Apps with SwiftUI](https://antongubarenko.substack.com/p/swiftui-foundations-build-great-apps) — iOS Dev Weekly · Issue 744 — Article · Topics: Foundation & Data Formats · Swift · SwiftUI
  **Published:** `27th February 2026`
  **NeKI brief:** Examines SwiftUI Foundations: Build Great Apps Q&A, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Tracking token usage in Foundation Models](https://artemnovichkov.com/blog/tracking-token-usage-in-foundation-models) — iOS Dev Weekly · Issue 744 — Article · Topics: AI Development · Foundation & Data Formats
  **Published:** `27th February 2026`
  **NeKI brief:** Presents Tracking token usage in Foundation Models, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Measuring Core Data and SwiftData](https://yaacoub.github.io/articles/swift-tip/measuring-core-data-and-swiftdata) — iOS Dev Weekly · Issue 744 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `27th February 2026`
  **NeKI brief:** Presents measuring core data and swiftdata for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Swift Actors: Common Pitfalls and How to Avoid Them](https://www.fractal-dev.com/blog/swift-actors-pitfalls?lang=en) — Those Who Swift · Issue 251 — Article · Topics: Concurrency · Foundation & Data Formats · Swift
  **Published:** `2026-01-28`
  **NeKI brief:** Catalogues common Swift actor pitfalls, including reentrancy and isolation misunderstandings. Use it when reviewing actor-based designs, pairing each warning with compiler diagnostics, tests, and a clear model of which state is actually protected.
- [Foundation Models Prompting Guide](https://livsycode.com/best-practices/foundation-models-prompting-guide) — Those Who Swift · Issue 250 — Article · Topics: AI Development · Foundation & Data Formats
  **Published:** `2026-01-21`
  **NeKI brief:** Provides practical prompting guidance for Apple's Foundation Models. Use it when shaping instructions, output constraints, and context boundaries for on-device generation, then validate behavior across models, locales, and failure cases.
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
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [How SwiftData Represents AttributedString in Core Data Storage](https://medium.com/@djalex566/how-swiftdata-represents-attributedstring-in-core-data-storage-69036a4f166a) — SwiftLee Weekly · Issue 299 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `2025-11-25T15:16:48.000Z`
  **NeKI brief:** Explains How SwiftData Represents AttributedString in Core Data Storage, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Using SwiftUI Foundation Models Transcripts to build a Chatbot](https://www.youtube.com/watch?v=cyOqYbWpQzU) — Those Who Swift · Issue 240 — Video · Topics: AI Development · Foundation & Data Formats · Swift
  **Published:** `2025-11-12`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [AnyLanguageModel](https://github.com/mattt/AnyLanguageModel) — iOS Dev Tools · iOS Dev Tools: Clash X, AnyLanguageModel, HealthKit Data Generator — Source repository · Topics: AI Development · Developer Tools · Foundation & Data Formats
  **Published:** `2025-11-06T22:32:54.905Z`
  **NeKI brief:** AnyLanguageModel mirrors Apple's Foundation Models API while allowing alternative language-model providers, presenting a compatible abstraction for application code. Useful for testing provider substitution and keeping model integration behind a stable Swift interface.
- [Guided Generation with Foundation Models in Swift](https://www.youtube.com/watch?v=kBwwztRY1FQ) — Those Who Swift · Issue 239 — Video · Topics: AI Development · Foundation & Data Formats · Swift
  **Published:** `2025-11-05`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Optimize your app's speed and efficiency](https://www.youtube.com/watch?v=yXAQTIKR8fk) — SwiftLee Weekly · Issue 296 — Video · Topics: AI Development · Foundation & Data Formats · Performance
  **Published:** `2025-11-04T08:02:52.000Z`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Tunable, physics-driven motion primitives for SwiftUI](https://github.com/roberthein/kinetics) — SwiftUI Weekly · SwiftUI Weekly - Issue #223 — Source repository · Topics: Concurrency · Swift · SwiftUI
  **Published:** `2025-10-20T15:15:23.773Z`
  **NeKI brief:** Provides tunable, physics-driven motion primitives for SwiftUI, including configurable springs and dynamics. Useful for experimenting with reusable interactive animations while inspecting API ergonomics, cancellation, and performance in real screens.
- [Foundation Models profiling with Xcode Instruments](https://artemnovichkov.com/blog/foundation-models-profiling-with-xcode-instruments) — iOS Dev Weekly · Issue 731 — Article · Topics: Foundation & Data Formats · Performance · Xcode
  **Published:** `17th October 2025`
  **NeKI brief:** Examines Foundation Models Profiling with Xcode Instruments, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [iOS 26: Foundation Model Framework - Code-Along Q&A](https://antongubarenko.substack.com/p/ios-26-foundation-model-framework-f6d) — Those Who Swift · Issue 235 — Article · Topics: AI Development · Foundation & Data Formats · Testing
  **Published:** `2025-10-08`
  **NeKI brief:** Examines iOS 26: Foundation Model Framework - Code-Along Q&A, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [TranscriptDebugMenu](https://github.com/artemnovichkov/TranscriptDebugMenu) — Fatbobman’s Swift Weekly · Issue 105 — Source repository · Topics: AI Development · Foundation & Data Formats · Performance
  **Published:** `2025-10-06T12:03:37.161Z`
  **NeKI brief:** TranscriptDebugMenu is a debug surface for inspecting Foundation Models conversations and related app state. Use it alongside Xcode Instruments when testing session prewarming, tool calls, and model-output performance in development builds.
- [Exploring AI for iOS Development](https://academy.rudrank.com/product/ai) — iOS Dev Weekly · Issue 727 — Article · Topics: AI Development · Foundation & Data Formats · Testing
  **Published:** `19th September 2025`
  **NeKI brief:** Presents exploring ai for ios development for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Swift progres: UIKit iOS 26, FoundationModels API and SPM traits](https://www.youtube.com/watch?v=Ew101hvrWJk) — Those Who Swift · Issue 230 — Video · Topics: AI Development · Foundation & Data Formats · UIKit
  **Published:** `2025-09-03`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Make Foundation Models Deterministic: Greedy Decoding in Swift](https://www.youtube.com/watch?v=Q6x3VeGlqwg) — Those Who Swift · Issue 228 — Video · Topics: AI Development · Foundation & Data Formats · Swift
  **Published:** `2025-08-20`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
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
- [Getting Started with Apple's Foundation Models](https://www.artemnovichkov.com/blog/getting-started-with-apple-foundation-models) — Those Who Swift · Issue 221 — Article · Topics: AI Development · Foundation & Data Formats · Swift
  **Published:** `2025-07-02`
  **NeKI brief:** Examines Getting Started with Apple's Foundation Models, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [A Swift Developer’s Guide to Prompt Engineering with Apple’s](https://www.natashatherobot.com/p/swift-prompt-engineering-apples-foundationmodels) — SwiftLee Weekly · Issue 278 — Article · Topics: Foundation & Data Formats · Swift
  **Published:** `2025-07-01T14:14:53.000Z`
  **NeKI brief:** Explains A Swift Developer’s Guide to Prompt Engineering with Apple’s, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
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
  **NeKI brief:** The second part of a Foundation Models series focuses on available tool-related capabilities. Use it to connect high-level model generation with app actions, then verify current tool-calling contracts in official framework documentation.
- [Introducing swiftly 1.0](https://www.swift.org/blog/introducing-swiftly_10) — Those Who Swift · Issue 208 — Article · Topics: Developer Career & Practice · Foundation & Data Formats · Swift
  **Published:** `2025-04-02`
  **NeKI brief:** This technical resource covers Swiftly 1.0 as a Swift toolchain manager. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [ZIP Foundation](https://github.com/weichsel/ZIPFoundation) — iOS Dev Tools · iOS Dev Tools: Diagnostics, ZIP Foundation, WebKit — Source repository · Topics: Developer Tools · Foundation & Data Formats · Objective-C & Cocoa
  **Published:** `2025-02-06T17:32:00.627Z`
  **NeKI brief:** Provides the public source repository for ZIP Foundation. Inspect its implementation, examples, and issue history to evaluate integration boundaries and maintenance trade-offs before depending on it in an Apple-platform project.
- [SwiftUI Navigation using the Router Pattern](https://tiagohenriques.vercel.app/blog/swiftui-navigation-router-pattern) — SwiftUI Weekly · SwiftUI Weekly - Issue #206 — Article · Topics: Foundation & Data Formats · Swift · SwiftUI
  **Published:** `2025-01-13T09:29:54.892Z`
  **NeKI brief:** Implements a router pattern for SwiftUI navigation with centralized route decisions. Useful for making deep links, modal presentation, and navigation tests deterministic while keeping views focused on rendering.
- [MongoKitten](https://github.com/orlandos-nl/MongoKitten) — Fatbobman’s Swift Weekly · Issue 65 — Source repository · Topics: Developer Tools · Foundation & Data Formats · Swift
  **Published:** `2025-01-06T12:02:39.656Z`
  **NeKI brief:** MongoKitten provides a pure-Swift MongoDB driver built on SwiftNIO. Follow it when evaluating asynchronous document-database access, connection lifecycle, and how a Swift server maps BSON operations into application models.
- [Morphology](https://lickability.com/blog/morphology-in-swift) — iOS Dev Weekly · Issue 678 — Article · Topics: Foundation & Data Formats · Swift
  **Published:** `13th September 2024`
  **NeKI brief:** Presents morphology for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [An Xcode Detective Story](https://www.emergetools.com/blog/posts/the-memory-leak-an-xcode-detective-story) — iOS Dev Weekly · Issue 678 — Article · Topics: Foundation & Data Formats · Xcode
  **Published:** `13th September 2024`
  **NeKI brief:** Presents an xcode detective story for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [SwiftUI can be a bit... eager](https://www.attributedstrings.com/swiftui-can-be-a-bit-eager) — SwiftUI Weekly · SwiftUI Weekly - Issue #193 — Article · Topics: Foundation & Data Formats · Swift · SwiftUI
  **Published:** `2024-07-08T08:54:13.719Z`
  **NeKI brief:** Investigates cases where SwiftUI evaluates views or work eagerly. Useful for diagnosing unexpected initialization, expensive computations, and lifecycle assumptions in declarative hierarchies.
- [Tuist](https://tuist.io/) — iOS Dev Tools · iOS Dev Tools: Pricetag, Tuist, Snapshots — Article · Topics: Architecture · Developer Tools · Foundation & Data Formats
  **Published:** `2024-06-27T16:03:43.649Z`
  **NeKI brief:** Tuist provides project generation and automation for Xcode-based applications. Evaluate it when scaling modular projects, balancing reproducibility and abstraction against Xcode project complexity.
- [Converting Codable Models To CSV](https://digitalbunker.dev/converting-codable-models-to-csv?issue=029) — Fatbobman’s Swift Weekly · Issue 29 — Article · Topics: Developer Tools · Foundation & Data Formats · Swift
  **Published:** `2024-04-29T12:02:14.611Z`
  **NeKI brief:** Shows mapping Codable models into CSV rows, including the column-order and value-conversion decisions serialization requires. Follow it when exporting Swift domain data for reports or interoperability rather than JSON APIs.
- [Dispatching to the Main thread with MainActor in Swift](https://www.donnywals.com/dispatching-to-the-main-thread-with-mainactor-in-swift?issue=029) — Fatbobman’s Swift Weekly · Issue 29 — Article · Topics: Concurrency · Foundation & Data Formats · Swift
  **Published:** `2024-04-29T12:02:14.611Z`
  **NeKI brief:** MainActor isolation expresses UI-thread ownership in the type system, replacing ad hoc dispatch calls while making asynchronous hops and actor boundaries explicit.
- [The Absolute Minimum Every Software Developer Must Know About Unicode in 2023 (Still No Excuses!)](https://tonsky.me/blog/unicode) — Fatbobman’s Swift Weekly · Issue 5 — Article · Topics: Foundation & Data Formats · Swift · SwiftData
  **Published:** `2023-11-06T22:30:15.675Z`
  **NeKI brief:** Explains Unicode fundamentals and common misconceptions that still cause text-processing bugs. Use it when reviewing Swift string handling, normalization, grapheme boundaries, and serialization across user-visible content and external systems.
- [2023 年每个软件开发者都必须知道的关于 Unicode 的最基本的知识（仍然不准找借口！）](https://blog.xinshijiededa.men/unicode) — Fatbobman’s Swift Weekly · Issue 5 — Article · Topics: Foundation & Data Formats · Swift · SwiftData
  **Published:** `2023-11-06T22:30:15.675Z`
  **NeKI brief:** Provides a Chinese-language treatment of Unicode basics and the pitfalls of assuming characters map directly to bytes or code points. Follow it as complementary reading when internationalized Swift text behavior needs careful validation.
- [Interoperability: Swift’s Super Power](https://speakinginswift.substack.com/p/interoperability-swifts-super-power) — Fatbobman’s Swift Weekly · Issue 2 — Article · Topics: Foundation & Data Formats · Swift · Xcode
  **Published:** `2023-10-16T22:30:04.937Z`
  **NeKI brief:** A Speaking in Swift essay explores interoperability as one of Swift's defining strengths. Follow it for community perspective on bridging and adoption, then verify compiler, ABI, and framework specifics independently.
- [The Future of Foundation](https://www.swift.org/blog/future-of-foundation) — iOS Dev Weekly · Issue 589 — Article · Topics: Foundation & Data Formats · Swift
  **Published:** `16th December 2022`
  **NeKI brief:** Explores The Future of Foundation, focusing on the last thing i was expecting as we wind down. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [The SwiftUI Layout Protocol - Part 2](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3N3aWZ0dWktbGFiLmNvbS9sYXlvdXQtcHJvdG9jb2wtcGFydC0yLz91dG1fY2FtcGFpZ249JTIwU3dpZnRVSSUyMFdlZWtseSZ1dG1fbWVkaXVtPWVtYWlsJnV0bV9zb3VyY2U9UmV2dWUlMjBuZXdzbGV0dGVyIiwicG9zdF9pZCI6ImYyZTA5NDQxLWI0OWQtNDY2Ni1iZGY0LWNhMDE1ZWNmYTdiMSIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiJlYzNhYzhhNC01YThhLTQzZGUtYmY3OC1jMGViNTNmMWZlZjUiLCJpYXQiOjE2NzQwNjI1NTguMDk2LCJpc3MiOiJvcmNoaWQifQ._glPwaca1iVFJwupEeTdogDJhpWE9AaEf-Mko6Z_onA) — SwiftUI Weekly · SwiftUI Weekly - Issue #114 — Article · Topics: Foundation & Data Formats · Swift · SwiftUI
  **Published:** `2022-09-13T16:37:55.000Z`
  **NeKI brief:** Continues custom SwiftUI Layout implementation techniques. Use it when caching, placement, and subview proposals need deliberate control for performance.
- [on the Swift Forums](https://forums.swift.org/t/deepcodable-encode-and-decode-deeply-nested-data-into-flat-swift-objects/59136) — iOS Dev Weekly · Issue 568 — Article · Topics: Foundation & Data Formats · Swift
  **Published:** `22nd July 2022`
  **NeKI brief:** Explores on the Swift Forums, focusing on he wrote more about it on the swift forums if you want more context. Follow it to assess the approach, its trade-offs, and where it fits in a current Swift or Apple-platform project.
- [MVC for SwiftUI with Boutique](https://build.ms/2022/06/22/model-view-controller-store) — iOS Dev Weekly · Issue 564 — Article · Topics: Foundation & Data Formats · Swift · SwiftUI
  **Published:** `24th June 2022`
  **NeKI brief:** Explores MVC for SwiftUI with Boutique, focusing on this is a really long blog post from joe fabisevich,. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Displaying mathematical fractions](https://coderexmachina.medium.com/displaying-mathematical-fractions-in-swiftui-6a4dd625d842) — iOS Dev Weekly · Issue 533 — Tutorial · Topics: Developer Community & Business · Foundation & Data Formats · Swift
  **Published:** `12th November 2021`
  **NeKI brief:** Explores displaying mathematical fractions that lack a matching Unicode glyph in SwiftUI. A focused typography and layout reference for educational, scientific, or recipe interfaces where a plain slash is not visually adequate.
- [AutomaticSettings](https://github.com/krzysztofzablocki/AutomaticSettings) — iOS Dev Weekly · Issue 489 — Source repository · Topics: Developer Tools · Foundation & Data Formats · Graphics, Media & Games
  **Published:** `8th January 2021`
  **NeKI brief:** Examines AutomaticSettings, focusing on this new library from krzysztof zabłocki is interesting. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Sourcery](https://github.com/krzysztofzablocki/Sourcery) — iOS Dev Weekly · Issue 489 — Source repository · Topics: Developer Tools · Foundation & Data Formats · Graphics, Media & Games
  **Published:** `8th January 2021`
  **NeKI brief:** Sourcery parses Swift source with templates to generate repetitive implementations such as mocks, equality, or Codable support. Use it when generated boilerplate has stable conventions and the templates can be reviewed as part of source control.
- [Parsing Tricky JSON With Codable in Swift](https://www.andyibanez.com/posts/parsing-tricky-json-codable-swift) — iOS Dev Weekly · Issue 480 — Article · Topics: Foundation & Data Formats · Swift
  **Published:** `30th October 2020`
  **NeKI brief:** Examines Parsing Tricky JSON With Codable in Swift, offering practical guidance on data modeling and persistence trade-offs. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Save Custom Codable Types in AppStorage or SceneStorage](https://lostmoa.com/blog/SaveCustomCodableTypesInAppStorageOrSceneStorage) — iOS Dev Weekly · Issue 472 — Article · Topics: Foundation & Data Formats · Swift · SwiftUI
  **Published:** `4th September 2020`
  **NeKI brief:** Examines Save Custom Codable Types in AppStorage or SceneStorage, offering practical guidance on data modeling and persistence trade-offs. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [DefaultCodable](https://github.com/gonzalezreal/DefaultCodable) — iOS Dev Weekly · Issue 443 — Source repository · Topics: Developer Tools · Foundation & Data Formats
  **Published:** `14th February 2020`
  **NeKI brief:** Examines DefaultCodable, focusing on the author’s note that like this µpackage idea from guille gonzalez. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Caching in Swift](https://www.swiftbysundell.com/posts/caching-in-swift) — iOS Dev Weekly · Issue 419 — Article · Topics: Foundation & Data Formats · Performance · Swift
  **Published:** `30th August 2019`
  **NeKI brief:** Examines Caching in Swift, offering practical guidance on networking and asynchronous reliability. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [NSAttributedStringBuilder](https://github.com/ethanhuang13/NSAttributedStringBuilder) — iOS Dev Weekly · Issue 412 — Source repository · Topics: Developer Tools · Swift · SwiftUI
  **Published:** `12th July 2019`
  **NeKI brief:** Examines NSAttributedStringBuilder, focusing on swiftui makes the construction of views and ui easy. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Path.swift](https://github.com/mxcl/Path.swift) — iOS Dev Weekly · Issue 388 — Source repository · Topics: Developer Tools · Foundation & Data Formats · Swift
  **Published:** `25th January 2019`
  **NeKI brief:** Examines Path.swift, focusing on the url/path manipulation methods in foundation have always been powerful, but also very verbose so this new wrapper…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
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
- [Guitar](https://github.com/ArtSabintsev/Guitar) — iOS Dev Weekly · Issue 290 — Source repository · Topics: Developer Tools · Foundation & Data Formats · Swift
  **Published:** `3rd March 2017`
  **NeKI brief:** Examines Guitar, focusing on ever found the string class … lacking? arthur sabintsev has put together an extension library which already includes…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [The Death of Cocoa](http://nshipster.com/the-death-of-cocoa) — iOS Dev Weekly · Issue 179 — Article · Topics: Foundation & Data Formats · Objective-C & Cocoa · Swift
  **Published:** `2nd January 2015`
  **NeKI brief:** Explains The Death of Cocoa with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Strings in Swift](http://oleb.net/blog/2014/07/swift-strings) — iOS Dev Weekly · Issue 153 — Article · Topics: Foundation & Data Formats · Swift
  **Published:** `4th July 2014`
  **NeKI brief:** Swift strings represent Unicode text rather than random-access byte arrays, making character traversal and slicing semantics explicit. The article explains why correctness across grapheme clusters requires different algorithms.
- [NSURLProtocol](http://www.raywenderlich.com/59982/nsurlprotocol-tutorial) — iOS Dev Weekly · Issue 135 — Tutorial · Topics: Foundation & Data Formats · Networking
  **Published:** `28th February 2014`
  **NeKI brief:** Explains NSURLProtocol with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [NSString and Unicode](http://www.objc.io/issue-9/unicode.html) — iOS Dev Weekly · Issue 133 — Article · Topics: Cross-Platform & Web · Foundation & Data Formats · Testing
  **Published:** `14th February 2014`
  **NeKI brief:** Explains NSString and Unicode with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Slash](https://github.com/chrisdevereux/Slash) — iOS Dev Weekly · Issue 73 — Source repository · Topics: Developer Tools · Product Design
  **Published:** `21st December 2012`
  **NeKI brief:** Provides the Slash source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
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
