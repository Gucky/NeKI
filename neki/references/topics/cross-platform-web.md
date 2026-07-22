# Cross-Platform & Web

Third-party reading leads collected from NeKI sources. The links may be useful perspectives, but are not vetted recommendations or authoritative API guidance. NeKI publishes routing metadata, not the linked articles' text.

**Scope:** Cross-platform, Android, Flutter, web, and interoperability work adjacent to Apple-platform development.

- Last collected: `2026-07-22T21:56:49Z`
- Indexed links shown: **264**

## Direct-source reading

- [From iOS to Android - A Candid Look at My Real-World Journey into Dual-Platform Development](https://fatbobman.com/en/posts/from-ios-to-android) — Fatbobman · article catalogue
  **Published:** `2025-11-26T14:12:00.000Z`
  **NeKI brief:** Reports the practical costs of extending an iOS product to Android, including feature parity, store rules, monetization, and China-specific distribution. Use it to frame platform expansion as an operational decision, not only a UI rewrite.
- [Generating beautiful open-graph images dynamically](https://www.polpiella.dev/generating-beautiful-open-graph-images-dynamically) — Pol Piella · article catalogue
  **Published:** `2024-01-24T00:00:00.000Z`
  **NeKI brief:** Dynamic Open Graph generation combines serverless functions with Satori and resvg to produce social preview images. Follow it to understand the rendering pipeline and deployment boundary rather than generating assets manually for every page.
- [How to manage Safe Area insets in Flutter | Sarunw](https://sarunw.com/posts/flutter-safe-area) — Sarunw · article catalogue
  **Published:** `2023-01-25`
  **NeKI brief:** Safe-area insets describe where system UI can obscure Flutter content, so padding should derive from the framework's inset value rather than fixed device constants. This keeps layouts resilient across notches and system bars.
- [Linking to text fragments in web pages – Ole Begemann](https://oleb.net/2020/text-fragments) — Ole Begemann · article catalogue
  **Published:** `2020-06-21T21:07:03Z`
  **NeKI brief:** Text-fragment URLs encode a phrase that compatible browsers can highlight on arrival, improving deep links into long documents. The article explains the browser and markup limitations that make this useful for navigation but unsuitable as a guaranteed cross-client contract.
- [Yet Another New Blogging Engine | Dave DeLong](https://davedelong.com/blog/2018/04/21/yet-another-new-blog) — Dave DeLong · article catalogue
  **Published:** `2018-04-21T00:00:00+00:00`
  **NeKI brief:** After a compromised dynamic blog, the article moves to Jekyll static generation so published pages avoid per-request application execution. It treats deployment, search, and authoring ergonomics as separate operational concerns.
- [Apple has launched Safari Technology Preview (and that’s great news). – Donny Wals](https://www.donnywals.com/apple-has-launched-safari-technology-preview-and-thats-great-news) — Donny Wals · article catalogue
  **Published:** `2016-03-31T11:27:24+00:00`
  **NeKI brief:** Safari Technology Preview gives web developers an early testing channel for engine changes, helping detect compatibility issues before they reach stable Safari.
- [Build a simple web scraper with node.js – Donny Wals](https://www.donnywals.com/build-a-simple-web-scraper-with-node-js) — Donny Wals · article catalogue
  **Published:** `2016-02-29T15:17:37+00:00`
  **NeKI brief:** A simple Node scraper turns remote HTML into structured data, but selectors, rate limits, and source permission boundaries must be treated as fragile dependencies.
- [How I migrated from Apache to Nginx – Donny Wals](https://www.donnywals.com/how-i-migrated-from-apache-to-nginx) — Donny Wals · article catalogue
  **Published:** `2015-09-05T14:41:30+00:00`
  **NeKI brief:** Migrating web servers changes routing, process, and configuration assumptions, so staged verification and rollback planning matter more than benchmark claims.
- [Is it Immoral to not Block Ads? – Ole Begemann](https://oleb.net/blog/2015/08/is-it-immoral-to-not-block-ads) — Ole Begemann · article catalogue
  **Published:** `2015-08-04T22:47:00Z`
  **NeKI brief:** Advertising-blocking decisions combine product ethics, publisher incentives, privacy, and user control rather than a purely technical toggle. The essay is useful context when an app's network policy affects third-party content.
- [Icon fonts vs. svg icons – Donny Wals](https://www.donnywals.com/icon-fonts-vs-svg-icons) — Donny Wals · article catalogue
  **Published:** `2015-04-16T18:43:14+00:00`
  **NeKI brief:** Icon fonts and SVGs have different scaling, accessibility, rendering, and asset-pipeline trade-offs, so a UI system should choose intentionally rather than follow legacy habits.
- [Using Flexbox in the real world – Donny Wals](https://www.donnywals.com/using-flexbox-in-the-real-world) — Donny Wals · article catalogue
  **Published:** `2015-04-01T19:04:56+00:00`
  **NeKI brief:** Flexbox distributes items along one axis with alignment rules, simplifying responsive layouts while requiring clear understanding of shrink, grow, and basis interactions.
- [Service workers are awesome – Donny Wals](https://www.donnywals.com/service-workers-are-awesome) — Donny Wals · article catalogue
  **Published:** `2015-03-29T15:18:57+00:00`
  **NeKI brief:** Service workers intercept web requests for offline caching and background behavior, but update lifecycle and stale-content strategy must be designed deliberately.
- [Filling in the blanks with calc() – Donny Wals](https://www.donnywals.com/filling-in-the-blanks-with-calc) — Donny Wals · article catalogue
  **Published:** `2015-03-28T16:48:30+00:00`
  **NeKI brief:** CSS calc() combines units within one computed value, allowing responsive sizing rules without scattering hard-coded pixel arithmetic across multiple breakpoint declarations.
- [Three simple ways to start a local webserver – Donny Wals](https://www.donnywals.com/three-simple-ways-to-start-a-local-webserver) — Donny Wals · article catalogue
  **Published:** `2015-03-20T07:39:19+00:00`
  **NeKI brief:** A local web server reproduces HTTP behavior that opening files cannot, enabling routing, asset, and fetch testing with an appropriately simple tool.
- [Don’t depend on javascript to render your page. – Donny Wals](https://www.donnywals.com/dont-depend-on-javascript-to-render-your-page) — Donny Wals · article catalogue
  **Published:** `2015-03-14T10:55:12+00:00`
  **NeKI brief:** Progressive rendering keeps essential content available before JavaScript succeeds, reducing blank-screen risk for slow, blocked, or failing scripts.
- [Automagically load your Gulp plugins – Donny Wals](https://www.donnywals.com/automagically-load-your-gulp-plugins) — Donny Wals · article catalogue
  **Published:** `2015-03-11T06:45:54+00:00`
  **NeKI brief:** Automatic Gulp plugin loading reduces repetitive imports, but explicit dependencies can be clearer when build behavior must be easy to audit.
- [Stop writing vendor prefixes, autoprefixer does that for you – Donny Wals](https://www.donnywals.com/stop-writing-vendor-prefixes-autoprefixer-does-that) — Donny Wals · article catalogue
  **Published:** `2015-03-10T09:13:56+00:00`
  **NeKI brief:** Autoprefixer derives browser-specific CSS prefixes from target support data, keeping authored styles clean while making the browser matrix an explicit build input.
- [You should start using Browsersync today. – Donny Wals](https://www.donnywals.com/you-should-start-using-browsersync-today) — Donny Wals · article catalogue
  **Published:** `2015-03-08T13:35:54+00:00`
  **NeKI brief:** BrowserSync synchronizes reloads and interactions across test browsers, shortening responsive-development feedback loops while remaining a local workflow tool.
- [How to prevent Gulp from crashing all the time – Donny Wals](https://www.donnywals.com/how-to-prevent-gulp-from-crashing-all-the-time) — Donny Wals · article catalogue
  **Published:** `2015-03-03T12:00:43+00:00`
  **NeKI brief:** Build-stream error handling keeps Gulp watch tasks alive after an asset compilation failure, exposing the error without forcing a manual restart.
- [Getting started with Gulp – Donny Wals](https://www.donnywals.com/getting-started-with-gulp) — Donny Wals · article catalogue
  **Published:** `2015-02-15T13:22:00+00:00`
  **NeKI brief:** Gulp organizes repeatable asset and development tasks as streams, but teams should keep the toolchain proportional to the project's actual build needs.
- [Understanding HTML5 srcset – Donny Wals](https://www.donnywals.com/understanding-html5-srcset) — Donny Wals · article catalogue
  **Published:** `2015-02-08T10:59:36+00:00`
  **NeKI brief:** srcset lets browsers select an image resource appropriate to display density and layout width, reducing unnecessary downloads when responsive candidates are well defined.
- [Avoid thinking in pixels – Donny Wals](https://www.donnywals.com/avoid-thinking-in-pixels) — Donny Wals · article catalogue
  **Published:** `2014-12-15T20:08:29+00:00`
  **NeKI brief:** Responsive CSS should express layout with relative dimensions and content-led breakpoints instead of copying a fixed pixel canvas, so the design adapts across screen densities and widths.
- [Sharing cookies between subdomains – Donny Wals](https://www.donnywals.com/sharing-cookies-between-subdomains) — Donny Wals · article catalogue
  **Published:** `2014-11-20T10:03:45+00:00`
  **NeKI brief:** Cookie sharing across subdomains depends on domain, path, security, and same-site attributes, so authentication behavior should be tested in the actual browser environment.
- [New Site Design, Now Proudly Serving Static HTML – Ole Begemann](https://oleb.net/blog/2011/02/new-site-design-now-proudly-serving-static-html) — Ole Begemann · article catalogue
  **Published:** `2011-02-27T22:50:00Z`
  **NeKI brief:** Describes a static-site publishing pipeline: author Markdown with metadata, compile and preview locally, commit to Git, then deploy generated output with rsync. The exact Nanoc/TextMate stack is historical, but the separation of source, build, preview, and deployment remains clear.
- [My Wish: Syntax Additions to Objective-C for Object Literals – Ole Begemann](https://oleb.net/blog/2010/12/syntax-additions-for-object-literals-to-objective-c) — Ole Begemann · article catalogue
  **Published:** `2010-12-22T11:07:00Z`
  **NeKI brief:** Motivates Objective-C number, array, and dictionary literals by mapping concise syntax to their verbose factory-method equivalents, including Core Animation configuration. It provides useful historical context for reading legacy code that predates the literal syntax later adopted by the language.
- [Animating the Drawing of a CGPath With CAShapeLayer – Ole Begemann](https://oleb.net/blog/2010/12/animating-drawing-of-cgpath-with-cashapelayer) — Ole Begemann · article catalogue
  **Published:** `2010-12-18T17:57:00Z`
  **NeKI brief:** Animates CAShapeLayer strokeEnd from zero to one to reveal a CGPath progressively, then synchronizes a keyframe-animated pen layer along the same path. The technique also connects text glyph paths to Core Text when the drawn path originates from typography.
- [Method Names in Objective-C – Ole Begemann](https://oleb.net/blog/2010/12/method-names-in-objective-c) — Ole Begemann · article catalogue
  **Published:** `2010-12-17T14:56:00Z`
  **NeKI brief:** Explains that every keyword segment is part of an Objective-C selector and demonstrates that unlabeled later parameters are legal but harmful. Use it as a concise rationale for descriptive selector pieces when maintaining Objective-C APIs alongside modern Swift interfaces.
- [How to Debug an App That Was Launched by Push Notification or URL Handler – Ole Begemann](https://oleb.net/blog/2010/05/how-to-debug-app-launched-by-remote-event) — Ole Begemann · article catalogue
  **Published:** `2010-05-06T21:17:00Z`
  **NeKI brief:** Shows two launch-debugging strategies for URL handlers and push events: inspect persistent logs when no debugger is attached, or configure the debugger to wait for the next process launch and stop at lifecycle breakpoints. Update the historical Xcode UI steps for current tooling.
- [OBGradientView: A Simple UIView Wrapper for CAGradientLayer – Ole Begemann](https://oleb.net/blog/2010/04/obgradientview-a-simple-uiview-wrapper-for-cagradientlayer) — Ole Begemann · article catalogue
  **Published:** `2010-04-20T13:15:00Z`
  **NeKI brief:** Wraps CAGradientLayer in an OBGradientView UIView subclass, forwarding gradient properties while accepting UIColor arrays. The UIKit wrapper makes gradients autoresizable with ordinary view layout, avoiding manual layer management when a gradient should behave like a view background.
- [Porting RRGlossCausticShader to the iPhone – Ole Begemann](https://oleb.net/blog/2010/02/porting-rrglosscausticshader-to-the-iphone) — Ole Begemann · article catalogue
  **Published:** `2010-02-28T18:02:00Z`
  **NeKI brief:** Porting a Core Graphics effect from AppKit to UIKit isolates platform color and graphics types behind a small adapter, so the rendering algorithm survives while platform-specific APIs stay at the boundary.
- [Mutable Properties of Immutable Objects – Ole Begemann](https://oleb.net/blog/2009/11/mutable-properties-of-immutable-objects) — Ole Begemann · article catalogue
  **Published:** `2009-11-30T21:30:00Z`
  **NeKI brief:** An immutable Objective-C object must not expose mutable backing collections: publish an immutable view or copy while retaining internal mutation, otherwise callers can silently violate invariants and thread-safety assumptions.
- [OBShapedButton: Non-Rectangular Buttons on the iPhone – Ole Begemann](https://oleb.net/blog/2009/10/obshapedbutton-non-rectangular-buttons-on-the-iphone) — Ole Begemann · article catalogue
  **Published:** `2009-10-17T16:53:00Z`
  **NeKI brief:** Nonrectangular button rendering is not enough for accurate interaction: hit testing must reject transparent image pixels so the control's touch target matches its visible shape. Reassess accessibility and performance with modern UIKit APIs.
- [The Music Player Framework in iPhone SDK 3.0 – Ole Begemann](https://oleb.net/blog/2009/07/the-music-player-framework-in-the-iphone-sdk) — Ole Begemann · article catalogue
  **Published:** `2009-07-13T13:53:00Z`
  **NeKI brief:** MediaPlayer separates application and system music-player behavior, then uses playback notifications and a media-picker delegate to keep UI state synchronized with library selection. Treat the APIs as historical context and recheck current privacy requirements.

## Newsletter and related leads

- [SwiftCon Returns to Berlin This October](https://www.nextappcon.com/swiftcon) — Those Who Swift · Issue 276 — Article · Topics: Cross-Platform & Web · Developer Community & Business · Swift
  **Published:** `2026-07-22T20:01:13.378Z`
  **NeKI brief:** SwiftCon's call for speakers seeks production-focused Swift and iOS talks, including SwiftUI, architecture, performance, and testing. Follow the event page to assess the community's current themes or submit a concrete engineering case study.
- [getting nowhere with Apple](https://lapcatsoftware.com/articles/2026/7/6.html) — Fatbobman’s Swift Weekly · Issue 145 — Article · Topics: App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `2026-07-20T12:01:22.890Z`
  **NeKI brief:** Diagnoses an App Store Connect login loop by comparing request cookies and finding a missing `dc` session cookie. Follow it for a focused example of browser-level debugging when server behavior contradicts apparent authentication state.
- [ZMarkupParser](https://github.com/ZhgChgLi/ZMarkupParser) — iOS Dev Tools · iOS Dev Tools: Footprint, ZMarkupParser, Lettera — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `2026-06-18T16:02:35.381Z`
  **NeKI brief:** A pure-Swift HTML-to-NSAttributedString parser that repairs malformed markup, supports custom tags and styles, and can render, strip, or select content. Its thread-safe implementation and performance report make it a concrete alternative to Foundation HTML parsing.
- [What’s New In SwiftData For iOS 27](https://azamsharp.com/2026/06/12/whats-new-in-swiftdata.html) — Those Who Swift · Issue 271 — Article · Topics: Cross-Platform & Web · Swift · SwiftData
  **Published:** `2026-06-18`
  **NeKI brief:** Summarizes SwiftData changes for iOS 27. Use it to identify migration and feature candidates for a persistence layer, then verify model, query, and availability details against current Apple documentation.
- [Building a Custom Data Store in SwiftData](https://azamsharp.com/2026/05/26/building-a-custom-data-store-in-swiftdata.html) — iOS Dev Weekly · Issue 752 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `29th May 2026`
  **NeKI brief:** Walks through implementing a custom SwiftData store and the integration points needed to replace default persistence; useful when evaluating storage backends and their lifecycle trade-offs.
- [Hot Reloading a Bazel-Based iOS App with InjectionNext](https://adincebic.com/2026/05/17/hot-reloading-a-bazelbased-ios.html) — iOS Dev Weekly · Issue 751 — Article · Topics: Cross-Platform & Web · Systems Programming · Testing
  **Published:** `22nd May 2026`
  **NeKI brief:** Presents hot reloading a bazel-based ios app with injectionnext for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [WatchLink](https://github.com/tareksabry1337/WatchLink) — Fatbobman’s Swift Weekly · Issue 135 — Source repository · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `2026-05-11T12:02:41.178Z`
  **NeKI brief:** WatchLink explores Watch connectivity over ordinary network protocols, allowing the peer to be an iPhone, Android device, or other IP endpoint. Use it when a watch feature should not depend on a proprietary phone-pairing transport.
- [official setup guides for editors built on top of it](https://www.swift.org/documentation/articles/getting-started-with-cursor-swift.html) — iOS Dev Weekly · Issue 747 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `10th April 2026`
  **NeKI brief:** Presents official setup guides for editors built on top of it for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Android](https://www.swift.org/blog/nightly-swift-sdk-for-android) — iOS Dev Weekly · Issue 747 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `10th April 2026`
  **NeKI brief:** Announces nightly Swift SDK builds for Android. Follow it when experimenting with Swift on Android and tracking toolchain progress, keeping nightly instability, package compatibility, and deployment support explicit in evaluation notes.
- [Wasm](https://www.swift.org/blog/swift-6.2-released) — iOS Dev Weekly · Issue 747 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `10th April 2026`
  **NeKI brief:** Swift 6.2's release announcement provides the authoritative overview of language and toolchain changes. Use it to plan adoption boundaries and match compiler behavior to the released version.
- [Expanding Animations in SwiftUI Lists](https://nerdyak.tech/development/2026/03/16/expand-animation-in-SwiftUI-List.html) — SwiftUI Weekly · SwiftUI Weekly - Issue #231 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2026-04-06T15:12:39.552Z`
  **NeKI brief:** Diagnoses janky expand and collapse animations inside SwiftUI List and documents the identity and transaction choices that improve them. Useful when animating variable-height rows without breaking list diffing or scroll performance.
- [Swift 6.3 Released](https://www.swift.org/blog/swift-6.3-released) — Those Who Swift · Issue 259 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `2026-03-26`
  **NeKI brief:** Announces Swift 6.3 and summarizes the language, package, and tooling changes in that release. Use it to identify migration candidates, then consult the release notes and proposal links for exact compiler behavior and availability.
- [Apple Doesn’t Show SwiftData iCloud Sync Status — So Let’s Build One](https://azamsharp.com/2026/03/16/swiftdata-icloud-sync-status.html) — Those Who Swift · Issue 258 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `2026-03-18`
  **NeKI brief:** Examines Apple Doesn’t Show SwiftData iCloud Sync Status — So Let’s Build One, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [AcceptedSE-0501HTML Coverage Report](https://github.com/apple/swift-evolution/blob/main/proposals/0501-swiftpm-html-coverage-report.md) — SwiftLee Weekly · Issue 315 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `2026-03-17T15:01:49.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for AcceptedSE-0501HTML Coverage Report. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Borrowing from Kotlin/Android to Architect Scalable iOS Apps in SwiftUI](https://www.infoq.com/articles/kotlin-scalable-swiftui-patterns) — SwiftUI Weekly · SwiftUI Weekly - Issue #230 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2026-03-09T13:33:31.501Z`
  **NeKI brief:** Translates scalable architecture ideas from Kotlin and Android into SwiftUI patterns, with emphasis on boundaries and composition. Useful for comparing cross-platform architectural trade-offs before adopting abstractions in a growing iOS codebase.
- [vChewing Input Method](https://vchewing.github.io/README.html) — Fatbobman’s Swift Weekly · Issue 126 — Article · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `2026-03-09T12:02:58.691Z`
  **NeKI brief:** vChewing documents a Chinese input method built for Apple platforms, including its user-facing behavior and project context. Follow it as a case study in text-input engineering, not as a general Swift UI tutorial.
- [release announcement](https://forums.swift.org/t/grdb-v7-10-0-android-linux-windows-and-sqlcipher-swiftpm/84754) — Fatbobman’s Swift Weekly · Issue 124 — Article · Topics: Cross-Platform & Web · Product Design · Swift
  **Published:** `2026-02-23T12:03:12.462Z`
  **NeKI brief:** GRDB 7.10's release discussion covers Android, Linux, Windows, and SQLCipher packaging, including current SwiftPM trait limitations. Use it when planning cross-platform SQLite support and checking which dependencies Xcode still downloads unnecessarily.
- [Exploring the Swift SDK for Android](https://www.swift.org/blog/exploring-the-swift-sdk-for-android) — Those Who Swift · Issue 246 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `2025-12-24`
  **NeKI brief:** Explores the Swift SDK for Android and its implications for cross-platform Swift development. Use it to understand the emerging toolchain and interoperability story, then verify supported packages, APIs, and production readiness before committing to it.
- [SwiftUI Navigation Pain](https://elegantchaos.com/2025/12/12/navigation-pain.html) — Those Who Swift · Issue 245 — Article · Topics: Navigation & Deep Linking · Swift · SwiftUI
  **Published:** `2025-12-17`
  **NeKI brief:** Examines SwiftUI Navigation Pain, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Dev Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) — Fatbobman’s Swift Weekly · Issue 109 — Article · Topics: Apple Platform Ecosystem · Cross-Platform & Web · Swift
  **Published:** `2025-11-03T12:02:55.598Z`
  **NeKI brief:** Provides the Swift language extension for Visual Studio Code. Follow it when setting up language-server completion, diagnostics, and package workflows outside Xcode, while validating debugger and SDK limitations separately.
- [The Swift Android Setup I Always Wanted](https://dev.to/swiftstream/the-swift-android-setup-i-always-wanted-285d) — Fatbobman’s Swift Weekly · Issue 109 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `2025-11-03T12:02:55.598Z`
  **NeKI brief:** Describes a Swift-on-Android setup combining Swift Stream IDE, swift-android-sdk, and JNIKit to build native libraries. Use it when evaluating Android targets that retain Swift source but require NDK and Java interop boundaries.
- [Android Workgroup](https://www.swift.org/android-workgroup) — iOS Dev Weekly · Issue 733 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `31st October 2025`
  **NeKI brief:** Documents the Swift Android Workgroup's effort to improve Swift tooling and runtime support on Android. Useful for tracking cross-platform language infrastructure beyond Apple's deployment targets.
- [was originally called a “Community Workgroup”](https://forums.swift.org/t/swift-on-android-working-group/77780) — iOS Dev Weekly · Issue 733 — Article · Topics: Cross-Platform & Web · Developer Community & Business · Swift
  **Published:** `31st October 2025`
  **NeKI brief:** Tracks the Swift on Android working group's scope and coordination. Use it to distinguish language/runtime portability from UIKit availability when assessing a shared Swift codebase for Android targets.
- [Getting Started guide](https://www.swift.org/documentation/articles/swift-sdk-for-android-getting-started.html) — iOS Dev Weekly · Issue 733 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `31st October 2025`
  **NeKI brief:** Presents getting started guide for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [repository full of example code](https://github.com/swiftlang/swift-android-examples) — iOS Dev Weekly · Issue 733 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `31st October 2025`
  **NeKI brief:** Presents repository full of example code for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [porting to the Android platform](https://github.com/OpenSwiftUIProject/OpenSwiftUI/issues?q=is%3Aissue+label%3A%22platform%3A+Android%22) — Fatbobman’s Swift Weekly · Issue 108 — Source repository · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2025-10-27T12:02:17.397Z`
  **NeKI brief:** This OpenSwiftUI issue view tracks Android-platform work and compatibility questions in an open-source SwiftUI reimplementation. Follow it to assess cross-platform progress and limitations, not as evidence about Apple's private SwiftUI implementation.
- [Now you can test Xcode apps and Swift packages in Zed](https://luxmentis.org/blog/test-xcode-apps-in-zed) — iOS Dev Weekly · Issue 731 — Article · Topics: Swift · Testing · Xcode
  **Published:** `17th October 2025`
  **NeKI brief:** Presents now you can test xcode apps and swift packages in zed for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Caveat Emptor](https://elegantchaos.com/2025/10/17/caveat-emptor.html) — iOS Dev Weekly · Issue 731 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `17th October 2025`
  **NeKI brief:** Reflects on unfinished and experimental open-source work, and the judgement needed before adopting it. A useful counterweight to feature-driven evaluation when a dependency looks promising but its maintenance, polish, and production readiness remain uncertain.
- [Introducing Swift Profile Recorder: Identifying Performance Bottlenecks in Production](https://www.swift.org/blog/swift-profile-recorder) — Fatbobman’s Swift Weekly · Issue 106 — Article · Topics: Cross-Platform & Web · Performance · Swift
  **Published:** `2025-10-13T12:03:32.126Z`
  **NeKI brief:** Introduces Swift Profile Recorder for capturing runtime profiling data from Swift applications. Useful for collecting reproducible performance evidence in environments where full Instruments sessions are impractical.
- [React-native-enriched](https://github.com/software-mansion-labs/react-native-enriched) — iOS Dev Tools · iOS Dev Tools: React-native-enriched, Darling, Aidoku — Source repository · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `2025-10-02T19:15:22.078Z`
  **NeKI brief:** react-native-enriched exposes a native rich-text editor to React Native with synchronous styling, HTML parsing, and live style detection. Its New Architecture constraint and native text-input design are useful when evaluating editor performance and platform integration boundaries.
- [We Need to Talk About Observation](https://jaredsinclair.com/2025/09/10/observation.html) — Those Who Swift · Issue 232 — Article · Topics: Cross-Platform & Web · Developer Career & Practice · Observation & State Management
  **Published:** `2025-09-17`
  **NeKI brief:** Explains We Need to Talk About Observation, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [JNIKit](https://github.com/swifdroid/jni-kit) — Fatbobman’s Swift Weekly · Issue 102 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `2025-09-15T12:03:30.479Z`
  **NeKI brief:** JNIKit provides Swift-friendly bindings for Android JNI interaction. Use it when a Swift Android library must call Java or Kotlin APIs, keeping conversion and reference-lifetime rules isolated from application code.
- [detailed introduction](https://brightdigit.com/tutorials/swift-build) — Fatbobman’s Swift Weekly · Issue 102 — Tutorial · Topics: Developer Tools · Swift · Swift Package Manager
  **Published:** `2025-09-15T12:03:30.479Z`
  **NeKI brief:** Explains using the swift-build GitHub Action to run Swift Package Manager builds and tests on macOS and Linux. Use it as a compact cross-platform CI starting point before adding caching, matrices, or release artifacts.
- [Subprocess](https://github.com/swiftlang/swift-subprocess) — iOS Dev Tools · iOS Dev Tools: Subprocess, ReerJSON, Haptic Video Sync — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `2025-09-11T20:39:49.146Z`
  **NeKI brief:** swift-subprocess modernizes launching and interacting with child processes through Swift concurrency. Use it for scripts and tools that need structured stdin, stdout, cancellation, and exit-status handling beyond Foundation's older Process API.
- [ch.at](https://github.com/Deep-ai-inc/ch.at) — iOS Dev Tools · iOS Dev Tools: ch.at, Mercato, Dependencies — Source repository · Topics: AI Development · Developer Tools · Security & Privacy
  **Published:** `2025-08-14T19:53:26.103Z`
  **NeKI brief:** ch.at is an open-source chat application project from Deep AI Inc. Use the repository to inspect conversational UI, networking, and model-integration patterns, while treating its architecture as an example rather than a production security baseline.
- [Writing a macOS Finder "action" Extension with Swift 6 Concurrency](https://cmsj.net/2025/05/23/finder-action-swift6.html) — Fatbobman’s Swift Weekly · Issue 94 — Article · Topics: Concurrency · Cross-Platform & Web · Swift
  **Published:** `2025-07-21T12:02:54.857Z`
  **NeKI brief:** Shows a macOS Finder action extension that bridges synchronous system callbacks into Swift 6 concurrency. Use it when adapting callback-based extension points while preserving correct actor isolation and completion timing.
- [Chris Jones](https://cmsj.net/author/chris-jones.html) — Fatbobman’s Swift Weekly · Issue 94 — Article · Topics: Concurrency · Cross-Platform & Web · Swift
  **Published:** `2025-07-21T12:02:54.857Z`
  **NeKI brief:** Provides contextual background on Chris Jones, useful for understanding the surrounding product, policy, or ecosystem issue before drawing technical or business conclusions.
- [How to use Google Gemini in Xcode 26 beta](https://zottmann.org/2025/06/13/how-to-use-google-gemini.html) — iOS Dev Weekly · Issue 717 — Article · Topics: AI Development · Cross-Platform & Web · Xcode
  **Published:** `11th July 2025`
  **NeKI brief:** Explains using Google Gemini from a developer workflow, including request setup and practical integration considerations. Use it to compare hosted-model tooling, then verify current authentication, quotas, and data-handling terms.
- [Using WebKit to Load Web Content in SwiftUI](https://www.artemnovichkov.com/blog/using-webkit-to-load-web-content-in-swiftui) — Those Who Swift · Issue 222 — Article · Topics: Concurrency · Swift · SwiftUI
  **Published:** `2025-07-10`
  **NeKI brief:** Integrates WebKit content loading with SwiftUI through UIViewRepresentable and a coordinator. Useful for controlled web content, navigation state, and lifecycle handling in hybrid screens.
- [Discussion on Flutter’s Support for Liquid Glass](https://github.com/flutter/flutter/issues/170310) — Fatbobman’s Swift Weekly · Issue 88 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Liquid Glass
  **Published:** `2025-06-12T02:52:10.753Z`
  **NeKI brief:** This Flutter issue discusses support for Apple's Liquid Glass redesign and related platform integration concerns. Follow the thread for cross-platform implementation constraints and status, not as a guarantee of shipped Flutter behavior.
- [Xtool: Cross-platform Xcode replacement](https://forums.swift.org/t/xtool-cross-platform-xcode-replacement-build-ios-apps-on-linux-and-more/79803) — iOS Dev Weekly · Issue 712 — Article · Topics: Cross-Platform & Web · Product Design · Xcode
  **Published:** `16th May 2025`
  **NeKI brief:** Presents xtool: cross-platform xcode replacement for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Regular Expressions in Swift](https://www.iro.umontreal.ca/~lapalme/RegexInSwift/index.html) — iOS Dev Weekly · Issue 711 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `9th May 2025`
  **NeKI brief:** Presents regular expressions in swift for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [DataScout](https://data-scout.pages.dev/) — iOS Dev Tools · iOS Dev Tools: AppsMan, ErrorKit, DataScout — Article · Topics: Core Data · Cross-Platform & Web · Persistence & Synchronisation
  **Published:** `2025-04-24T13:08:49.536Z`
  **NeKI brief:** Data Scout is a data-exploration project presented as a developer product. Inspect its concrete workflow when comparing small utility apps, data presentation choices, and the cost of maintaining a focused independent product.
- [ImplementedSE-0470Global-actor isolated conformances](https://github.com/apple/swift-evolution/blob/main/proposals/0470-isolated-conformances.md) — SwiftLee Weekly · Issue 268 — Source repository · Topics: Concurrency · Cross-Platform & Web · Swift
  **Published:** `2025-04-22T13:40:18.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0470Global-actor isolated conformances. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Returned For RevisionSE-0472Starting tasks synchronously from caller context](https://github.com/apple/swift-evolution/blob/main/proposals/0472-task-start-synchronously-on-caller-context.md) — SwiftLee Weekly · Issue 268 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `2025-04-22T13:40:18.000Z`
  **NeKI brief:** Provides the linked Swift or Apple-platform source repository for ImplementedSE-0472Starting tasks synchronously from caller context. Use it to inspect proposal details, implementation code, or release changes directly, while checking compatibility and maintenance status before adopting it.
- [Swiftdata Architecture Patterns And PracticesBlog about iOS development and musings on technologyAzamSharpMohammad Azam](https://azamsharp.com/2025/03/28/swiftdata-architecture-patterns-and-practices.html?ref=createwithswift.com) — Create with Swift · Issue 55 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2025-04-04T15:49:40.000Z`
  **NeKI brief:** Explains Swiftdata Architecture Patterns And Practices, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [Swiftdata Architecture Patterns And Practices](https://azamsharp.com/2025/03/28/swiftdata-architecture-patterns-and-practices.html) — SwiftLee Weekly · Issue 265 — Article · Topics: Architecture · Objective-C & Cocoa · Swift
  **Published:** `2025-04-01T14:13:42.000Z`
  **NeKI brief:** Explains Swiftdata Architecture Patterns And Practices, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [SwiftSoup](https://github.com/scinfu/SwiftSoup) — iOS Dev Tools · iOS Dev Tools: TranslateKit, SwiftSoup, InjectionIII — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `2025-02-20T19:09:31.201Z`
  **NeKI brief:** SwiftSoup ports jsoup-style HTML parsing to Swift, including DOM traversal, CSS selectors, sanitization, and WHATWG HTML5 parsing. Use it when extracting or transforming untrusted real-world markup without building a custom tokenizer.
- [ViewList](https://github.com/OpenSwiftUIProject/OpenSwiftUI/tree/main/Sources/OpenSwiftUICore/View/Input) — Fatbobman’s Swift Weekly · Issue 71 — Source repository · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2025-02-17T23:25:21.639Z`
  **NeKI brief:** Points directly into OpenSwiftUI's input-related view sources rather than its repository root. Use it to inspect how an open implementation models input plumbing when debugging or comparing SwiftUI behavior.
- [OpenGraph](https://github.com/OpenSwiftUIProject/OpenGraph) — Fatbobman’s Swift Weekly · Issue 71 — Source repository · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2025-02-17T23:25:21.639Z`
  **NeKI brief:** OpenGraph is an OpenSwiftUI-adjacent graph implementation to study alongside view construction and dependency propagation. Follow it when investigating how declarative UI state can be represented and traversed outside Apple's closed framework.
- [Sharing GRDB](https://github.com/pointfreeco/sharing-grdb) — Fatbobman’s Swift Weekly · Issue 71 — Source repository · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2025-02-17T23:25:21.639Z`
  **NeKI brief:** SharingGRDB combines shared observable state with GRDB-backed SQLite persistence. Use it when SwiftUI features need low deployment targets and direct SQL control, noting that it does not provide mature cross-device synchronization.
- [Navigation View If Needed](https://www.joshholtz.com/blog/2025/02/08/swiftui-navigation-view-if-needed.html) — iOS Dev Weekly · Issue 699 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `14th February 2025`
  **NeKI brief:** Presents SwiftUI - Navigation View If Needed, focusing on an implementation idea, workflow, or trade-off for Swift and Apple-platform development. Use it to investigate the stated topic and compare its approach with the current SDK, toolchain, and project constraints.
- [The Next Chapter in Swift Build TechnologiesSwift continues to grow in popularity as a cross-platform language supporting a wide variety of use cases, with support on a variety of embedded devices, form factors that encompass wearables to server, and a wide variety of operating systems. As Swift expands, there’s value in investing in matching cross-platform build tools that provide a powerful, consistent, and flexible experience across the ecosystem.Swift.orgApple Inc.](https://www.swift.org/blog/the-next-chapter-in-swift-build-technologies?ref=createwithswift.com) — Create with Swift · Issue 47 — Article · Topics: Concurrency · Cross-Platform & Web · Swift
  **Published:** `2025-02-07T16:00:24.000Z`
  **NeKI brief:** Discusses the direction of Swift build technologies and tooling. Use it for ecosystem context when planning build-system work, but keep implementation decisions grounded in the current Swift Package Manager and Xcode documentation.
- [Filtering SwiftData Models Using Enum](https://azamsharp.com/2025/01/23/filtering-swiftdata-models-using-enum.html?ref=createwithswift.com) — Create with Swift · Issue 46 — Article · Topics: Cross-Platform & Web · Swift · SwiftData
  **Published:** `2025-01-31T16:30:58.000Z`
  **NeKI brief:** Examines Filtering SwiftData Models Using Enum, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [Swift Everywhere: Bringing Swift Packages to Android](https://skip.tools/blog/android-native-swift-packages) — iOS Dev Weekly · Issue 697 — Article · Topics: Cross-Platform & Web · Swift · Testing
  **Published:** `31st January 2025`
  **NeKI brief:** Presents swift everywhere: bringing swift packages to android for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Filtering SwiftData Models Using Enum](https://azamsharp.com/2025/01/23/filtering-swiftdata-models-using-enum.html) — Those Who Swift · Issue 199 — Article · Topics: Cross-Platform & Web · Swift · SwiftData
  **Published:** `2025-01-30`
  **NeKI brief:** Examines Filtering SwiftData Models Using Enum, emphasizing practical implementation choices and trade-offs. Use it as a focused starting point for this topic, then verify API availability, platform constraints, and production implications in current project documentation.
- [iOS-uploader](https://github.com/simonnilsson/ios-uploader) — iOS Dev Tools · iOS Dev Tools: Swift Bundler, Swift for Visual Studio Code, iOS-uploader — Source repository · Topics: App Distribution & Store Operations · Cross-Platform & Web · Developer Tools
  **Published:** `2025-01-16T21:51:40.196Z`
  **NeKI brief:** A cross-platform command-line uploader for App Store Connect that accepts familiar altool-style arguments and can upload multiple apps concurrently. Its prebuilt binaries and npm installation make it relevant when CI must publish from Windows, Linux, or macOS.
- [The latest research results announced by Professor Chen Gang's team in China](https://www.stdaily.com/web/gdxw/2024-11/29/content_266525.html) — Fatbobman’s Swift Weekly · Issue 63 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Testing
  **Published:** `2024-12-23T12:01:34.355Z`
  **NeKI brief:** Provides contextual background on The latest research results announced by Professor Chen Gang's team in China, useful for understanding the surrounding product, policy, or ecosystem issue before drawing technical or business conclusions.
- [Deep Dive into Environment in SwiftUI](https://azamsharp.com/2024/11/18/deep-dive-into-environment-in-swiftui.html?ref=createwithswift.com) — Create with Swift · Issue 37 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2024-11-22T16:00:12.000Z`
  **NeKI brief:** Explains SwiftUI environment propagation, custom keys, and dependency lookup. Useful for deciding which shared services belong in environment values versus explicit initializer parameters.
- [Deep Dive into Environment in SwiftUI](https://azamsharp.com/2024/11/18/deep-dive-into-environment-in-swiftui.html) — SwiftUI Weekly · SwiftUI Weekly - Issue #203 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2024-11-19T05:45:58.937Z`
  **NeKI brief:** Explains SwiftUI environment propagation, custom keys, and dependency lookup. Useful for deciding which shared services belong in environment values versus explicit initializer parameters.
- [Guide to app architecture](https://developer.android.com/topic/architecture) — iOS Dev Weekly · Issue 685 — Article · Topics: Architecture · Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `1st November 2024`
  **NeKI brief:** Presents guide to app architecture for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [learning pathway](https://developer.android.com/courses/pathways/android-architecture) — iOS Dev Weekly · Issue 685 — Tutorial · Topics: Architecture · Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `1st November 2024`
  **NeKI brief:** Presents learning pathway for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Modular Navigation in SwiftUI: A Comprehensive Guide](https://ericsspace.com/articles/modular-navigation-in-swiftui-a-comprehensive-guide) — SwiftUI Weekly · SwiftUI Weekly - Issue #201 — Article · Topics: Architecture · Swift · SwiftUI
  **Published:** `2024-10-21T14:26:23.455Z`
  **NeKI brief:** Presents a modular navigation architecture for SwiftUI with separated route and feature concerns. Useful when deep links and navigation flows outgrow a single view's path handling.
- [Introduction to Communication Patterns in SwiftUI](https://azamsharp.com/2024/09/22/introduction-to-communication-patterns-in-swiftui.html) — SwiftUI Weekly · SwiftUI Weekly - Issue #200 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2024-09-30T17:14:55.385Z`
  **NeKI brief:** Compares communication patterns between SwiftUI views, including bindings, callbacks, and shared state. Useful for choosing data-flow direction while keeping feature interfaces testable.
- [Introduction to Communication Patterns in SwiftUI](https://azamsharp.com/2024/09/22/introduction-to-communication-patterns-in-swiftui.html?ref=createwithswift.com) — Create with Swift · Issue 29 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2024-09-27T15:10:02.000Z`
  **NeKI brief:** Compares communication patterns between SwiftUI views, including bindings, callbacks, and shared state. Useful for choosing data-flow direction while keeping feature interfaces testable.
- [Cross-Platform macOS/Windows Application Developed Using Swift 6](https://forums.swift.org/t/example-of-a-cross-platform-macos-windows-application-developed-using-swift-6/74591) — iOS Dev Weekly · Issue 679 — Article · Topics: AI Development · Cross-Platform & Web · Swift
  **Published:** `20th September 2024`
  **NeKI brief:** Presents cross-platform macos/windows application developed using swift 6 for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [available on GitHub](https://github.com/fbarbat/fellmonger) — iOS Dev Weekly · Issue 679 — Source repository · Topics: AI Development · Developer Tools · Swift
  **Published:** `20th September 2024`
  **NeKI brief:** Presents available on github for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Do your builds include SwiftUI Previews and Preview Content?](https://jaredsinclair.com/2024/05/20/preview-content.html) — iOS Dev Weekly · Issue 662 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `24th May 2024`
  **NeKI brief:** Investigates whether SwiftUI previews and preview content are excluded from App Store builds, rather than assuming development assets vanish automatically. Follow it when checking release artifacts, build settings, and the shipping consequences of preview-only code or resources.
- [Android Studio getting AI-powered code assistance](https://io.google/2024/explore/9986e95b-c506-40f1-b233-54f7e7092fdb) — iOS Dev Weekly · Issue 661 — Article · Topics: AI Development · Cross-Platform & Web
  **Published:** `17th May 2024`
  **NeKI brief:** Presents android studio getting ai-powered code assistance for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Dice Challenge in three front-end mobile frameworks](https://medium.com/@jpmtech/dice-challenge-in-swiftui-a26c82ac1367) — iOS Dev Weekly · Issue 660 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `10th May 2024`
  **NeKI brief:** Presents dice challenge in three front-end mobile frameworks for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Swift Server Workgroup](https://www.swift.org/sswg) — Fatbobman’s Swift Weekly · Issue 26 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `2024-04-08T22:00:36.243Z`
  **NeKI brief:** The Swift Server Workgroup coordinates ecosystem efforts for server-side Swift. Use it to discover supported libraries and governance context, not as an implementation reference.
- [Swift for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=sswg.swift-lang) — Fatbobman’s Swift Weekly · Issue 26 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `2024-04-08T22:00:36.243Z`
  **NeKI brief:** Provides the Swift language extension for Visual Studio Code. Follow it when setting up language-server completion, diagnostics, and package workflows outside Xcode, while validating debugger and SDK limitations separately.
- [Skip](https://skip.tools/) — iOS Dev Tools · iOS Dev Tools: Skip, AppLayouts, Firefoo — Article · Topics: Cross-Platform & Web · Xcode
  **Published:** `2024-03-21T14:02:34.735Z`
  **NeKI brief:** Skip is an Xcode plugin that translates a shared iOS app codebase for Android delivery. Use it when evaluating a cross-platform workflow that retains Swift and Xcode, while validating platform-specific UI and API boundaries.
- [官网](https://letsvisionos24.swiftgg.team/cn/index.html) — Fatbobman’s Swift Weekly · Issue 17 — Article · Topics: Cross-Platform & Web · Spatial Computing · Swift
  **Published:** `2024-01-29T22:00:15.485Z`
  **NeKI brief:** Uses 官网 as a practical reference for Apple-platform development, surfacing implementation constraints and workflow trade-offs worth checking before applying the idea in production code.
- [Testing network calls using URLProtocol](https://arturgruchala.com/testing-network-calls-using) — Fatbobman’s Swift Weekly · Issue 11 — Article · Topics: Cross-Platform & Web · Swift · Testing
  **Published:** `2023-12-18T22:00:30.856Z`
  **NeKI brief:** Uses URLProtocol interception to test network calls without a live server. Follow it when isolating request construction, response decoding, and error handling in deterministic XCTest cases.
- [AsyncStream in the real world](https://damian.fyi/swift/2023/12/03/asyncstream-in-the-real-world-wrapping-an-apple-photos-callback.html) — iOS Dev Weekly · Issue 639 — Article · Topics: Concurrency · Cross-Platform & Web · Swift
  **Published:** `8th December 2023`
  **NeKI brief:** Presents asyncstream in the real world for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Know your tools](https://khorbushko.github.io/article/2023/11/26/Know-your-tools.html) — Fatbobman’s Swift Weekly · Issue 9 — Article · Topics: Observation & State Management · Swift · SwiftUI
  **Published:** `2023-12-03T22:00:35.768Z`
  **NeKI brief:** Surveys the everyday tools and diagnostics that support Swift development and debugging. Use it as a checklist for improving feedback loops around builds, source inspection, runtime logs, and repeatable project maintenance.
- [Gestures in SwiftUI and Jetpack Compose](https://medium.com/@jpmtech/gestures-in-swiftui-c355b2b89d48) — iOS Dev Weekly · Issue 638 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `1st December 2023`
  **NeKI brief:** Presents gestures in swiftui and jetpack compose for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [this article shows the same gestures implemented with Jetpack Compose](https://medium.com/@jpmtech/gestures-in-jetpack-compose-b838d49ddd25) — iOS Dev Weekly · Issue 638 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `1st December 2023`
  **NeKI brief:** Presents this article shows the same gestures implemented with jetpack compose for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Swift JSON/Model Library Research](https://juejin.cn/post/7303741790674731045) — Fatbobman’s Swift Weekly · Issue 8 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `2023-11-27T22:10:19.997Z`
  **NeKI brief:** Researches Swift JSON and model libraries, comparing approaches to decoding, mapping, and model generation. Use it as an ecosystem survey before selecting a serialization dependency, then verify maintenance, performance, and API compatibility directly.
- [The Complete Guide to JSON Web Tokens (JWT) Authentication in iOS](https://azamsharp.com/2023/11/07/complete-guide-jwt-authentication.html) — Fatbobman’s Swift Weekly · Issue 6 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2023-11-13T22:20:44.462Z`
  **NeKI brief:** Walks through JWT authentication concepts and an iOS client integration path. Use it to review token storage, request authorization, refresh handling, and expiry failure modes before shipping a networked app.
- [Configuring VSCode](https://www.bryanbraun.com/2023/08/10/things-i-wish-someone-would-have-told-me-about-configuring-vscode) — iOS Dev Weekly · Issue 631 — Article · Topics: Cross-Platform & Web · Developer Tools · Xcode
  **Published:** `13th October 2023`
  **NeKI brief:** Presents configuring vscode for Apple-platform developers, highlighting the implementation approach and practical trade-offs. Use it as a focused starting point, then verify APIs, versions, and operational constraints against your project and current documentation.
- [Xcode Search Scopes](https://xcode.tips/search-scopes) — iOS Dev Weekly · Issue 621 — Article · Topics: Objective-C & Cocoa · Swift · Xcode
  **Published:** `4th August 2023`
  **NeKI brief:** Explores Xcode Search Scopes, focusing on i’m a fan of the xcode feature in this latest. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [The Ultimate Guide to Building SwiftData Applications](https://azamsharp.com/2023/07/04/the-ultimate-swift-data-guide.html) — SwiftUI Weekly · SwiftUI Weekly - Issue #151 — Article · Topics: Persistence & Synchronisation · Swift · SwiftData
  **Published:** `2023-07-17T21:13:35.306Z`
  **NeKI brief:** Provides a broad SwiftData walkthrough covering model declaration, persistence, and cloud-sync-oriented concepts introduced at WWDC 2023. Useful for mapping Core Data requirements to SwiftData before committing to a migration or new model layer.
- [React Native Vision Camera - Capture the World Differently](https://github.com/daltoniam/Starscream) — iOS Dev Tools · 🔨 Real-time Rendering & Stunning Imagery — Source repository · Topics: Cross-Platform & Web · Developer Tools · Graphics, Media & Games
  **Published:** `2023-07-13T13:51:39.780Z`
  **NeKI brief:** Starscream is a Swift WebSocket client implementing RFC 6455 with TLS, compression, and non-blocking callbacks. Use it when an app needs persistent bidirectional messaging and you must model connection lifecycle, reconnects, and message framing.
- [Improving multiplatform SwiftUI code](https://www.jessesquires.com/blog/2023/03/23/improve-multiplatform-swiftui-code) — iOS Dev Weekly · Issue 602 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `24th March 2023`
  **NeKI brief:** Explores Improving multiplatform SwiftUI code, focusing on the article discusses liked the simple solution that jesse squires. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Building Large Scale Apps with SwiftUI](http://azamsharp.com/2023/02/28/building-large-scale-apps-swiftui.html) — iOS Dev Weekly · Issue 601 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `17th March 2023`
  **NeKI brief:** Explores Building Large Scale Apps with SwiftUI, focusing on i’m not going to try to summarise this post from. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Wonderous: Build Wonders with Flutter](https://flutter.gskinner.com/wonderous) — iOS Dev Weekly · Issue 598 — Article · Topics: Accessibility · App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `24th February 2023`
  **NeKI brief:** Explores Wonderous: Build Wonders with Flutter, focusing on wonderous is an open-source ios app built with flutter. it. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Flutter](https://flutter.dev/multi-platform/mobile) — iOS Dev Weekly · Issue 598 — Article · Topics: Accessibility · App Distribution & Store Operations · Cross-Platform & Web
  **Published:** `24th February 2023`
  **NeKI brief:** Explores Flutter, focusing on wonderous is an open-source ios app built with flutter. it features award-winning ux design and best practices for performance and accessibility. see. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [30,000 lines of SwiftUI in production later: We love it but you know there was going to be a “but”](https://blog.timing.is/swiftui-production-experience-problems-solutions-performance-tips) — SwiftUI Weekly · SwiftUI Weekly - Issue #129 — Article · Topics: App Distribution & Store Operations · Swift · SwiftUI
  **Published:** `2023-01-30T11:20:24.661Z`
  **NeKI brief:** Reports production SwiftUI performance problems and the remedies used to diagnose them. Useful as a field-tested checklist for investigating rendering cost, navigation behavior, and architectural friction beyond small sample projects.
- [Container Pattern in SwiftUI](https://azamsharp.com/2023/01/24/introduction-to-container-pattern.html) — SwiftUI Weekly · SwiftUI Weekly - Issue #129 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2023-01-30T11:20:24.661Z`
  **NeKI brief:** Introduces the SwiftUI container pattern for separating screen composition from data-loading and coordination responsibilities. Useful when extracting feature-level dependencies without turning view bodies into implicit service locators.
- [Soto and Swift Build Plugin experiments](https://soto.codes/2022/12/build-plugin-experiments.html) — iOS Dev Weekly · Issue 588 — Article · Topics: Cross-Platform & Web · Swift · Swift Package Manager
  **Published:** `9th December 2022`
  **NeKI brief:** Explores Soto and Swift Build Plugin experiments, focusing on code generation during a swift package build process is a. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Women Who Code Mobile Summit 2022](https://www.youtube.com/playlist?list=PLVcEZG2JPVhf_iA733UhMxPS0H8iCoouj) — iOS Dev Weekly · Issue 580 — Video · Topics: Cross-Platform & Web · Graphics, Media & Games · Swift
  **Published:** `14th October 2022`
  **NeKI brief:** Uses State, Binding, ObservableObject, StateObject, and EnvironmentObject in practical SwiftUI data-flow examples. Follow it to compare ownership and propagation choices when a view hierarchy has multiple sources of mutable state.
- [Sharing cross-platform code in SwiftUI apps](https://www.jessesquires.com/blog/2022/08/19/sharing-code-in-swiftui-apps) — iOS Dev Weekly · Issue 574 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `2nd September 2022`
  **NeKI brief:** Explores Sharing cross-platform code in SwiftUI apps, focusing on there’s no doubt that swiftui makes cross-platform¹ development easier, but. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [View Is The View Model](https://azamsharp.com/2022/07/21/view-is-the-view-model.html) — iOS Dev Weekly · Issue 569 — Article · Topics: Architecture · Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `29th July 2022`
  **NeKI brief:** Explores View Is The View Model, focusing on do you need view models if you’re working with swiftui?. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Multiline TextField in SwiftUI](https://otbivnoe.ru/2022/07/10/Finally-Multiline-TextField-in-SwiftUI.html) — iOS Dev Weekly · Issue 567 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `15th July 2022`
  **NeKI brief:** Explores Multiline TextField in SwiftUI, focusing on the article discusses have seen so many different implementations of. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [vscode-swift](https://github.com/swift-server/vscode-swift) — iOS Dev Weekly · Issue 559 — Source repository · Topics: Developer Tools · Swift
  **Published:** `20th May 2022`
  **NeKI brief:** Explores vscode-swift, focusing on if you had told me five years ago that in 2022, writing swift in a javascript-based text editor from microsoft called visual. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Injection](http://johnholdsworth.com/injection.html) — iOS Dev Weekly · Issue 553 — Article · Topics: Cross-Platform & Web · Testing
  **Published:** `8th April 2022`
  **NeKI brief:** Explores Injection II, the App in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [An Approach for Migrating From Objective-C to Swift](https://www.steveonstuff.com/2022/01/13/migrating-from-objc-to-swift.html) — iOS Dev Weekly · Issue 541 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `14th January 2022`
  **NeKI brief:** Explores An Approach for Migrating From Objective-C to Swift, focusing on moving a codebase of any reasonable size from objective-c to. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Logarithmic Volume Control](https://dcordero.me/posts/logarithmic_volume_control.html) — iOS Dev Weekly · Issue 530 — Article · Topics: Cross-Platform & Web
  **Published:** `22nd October 2021`
  **NeKI brief:** Explores Logarithmic Volume Control, focusing on if you had asked me whether i’d ever link to. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Keeping WWDC videos and sample code current](https://dimsumthinking.com/Blog/2021/08/30-KeepingCurrent.html) — iOS Dev Weekly · Issue 523 — Article · Topics: Apple Platform Ecosystem · Concurrency · Cross-Platform & Web
  **Published:** `3rd September 2021`
  **NeKI brief:** Explores Keeping WWDC videos and sample code current, focusing on here’s another advantage of not having on-stage presentations at wwdc.. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Circular Gestures with the 2nd Gen Siri Remote](https://dcordero.me/posts/capture_circular_gestures_on_siri_remote_2nd_generation.html) — iOS Dev Weekly · Issue 523 — Article · Topics: App Intents & System Surfaces · Cross-Platform & Web
  **Published:** `3rd September 2021`
  **NeKI brief:** Explores Circular Gestures with the 2nd Gen Siri Remote, focusing on it’s been a while since i saw anyone write about. Follow it to assess the approach and trade-offs before applying it in a current Swift or Apple-platform project.
- [Spokestack - AutoML tools that put custom voice into software](https://flight.beehiiv.net/v2/clicks/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1cmwiOiJodHRwczovL3d3dy5zcG9rZXN0YWNrLmlvLz91dG1fY2FtcGFpZ249bWFrZXJfbGF1bmNoX1BBSUQmdXRtX21lZGl1bT1lbWFpbCZ1dG1fc291cmNlPXN3aWZ0dWlfd2Vla2x5IiwicG9zdF9pZCI6Ijk4NTQyZmUzLTllOWYtNGZmOC05OWMwLTQ0ODc1NzNiZDY0MiIsInB1YmxpY2F0aW9uX2lkIjoiNzk0OGVhNjUtY2I2ZS00Y2Q1LTk3MmMtMzFmOGM2ZDZjZGE0IiwidmlzaXRfdG9rZW4iOiJlMGQxNjc5Mi0xZmY1LTRhMjEtOTg0Yy00ZTk0MThiOWEzOWUiLCJpYXQiOjE2NzQwNjI2NzcuMDEsImlzcyI6Im9yY2hpZCJ9.atUK69hH2ROd-1KMu7E8qDPRvdFtWbAB5xcDUbJ8hiU) — SwiftUI Weekly · SwiftUI Weekly - Issue #63 — Article · Topics: AI Development · App Intents & System Surfaces · Cross-Platform & Web
  **Published:** `2021-06-14T22:35:11.000Z`
  **NeKI brief:** Presents Spokestack tools for adding custom voice interfaces and models to software. Use it as a discovery lead when evaluating speech-triggered features, model training workflow, and service dependencies.
- [JavaScriptCore and Swift](https://www.andyibanez.com/posts/javascriptcore-and-swift) — iOS Dev Weekly · Issue 503 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `16th April 2021`
  **NeKI brief:** Explores JavaScriptCore and Swift, focusing on like most people, i have mixed feelings about javascript. Follow it to assess the approach, its trade-offs, and where it fits in a current Swift or Apple-platform project.
- [Inspecting SwiftUI views](https://fivestars.blog/swiftui/inspecting-views.html) — iOS Dev Weekly · Issue 500 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `26th March 2021`
  **NeKI brief:** Examines Inspecting SwiftUI views, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Setting up a multi-platform SwiftUI project](https://blog.scottlogic.com/2021/03/04/Multiplatform-SwiftUI.html) — iOS Dev Weekly · Issue 499 — Article · Topics: Swift · SwiftUI · Xcode
  **Published:** `19th March 2021`
  **NeKI brief:** Covers Setting up a multi-platform SwiftUI project, focusing on Apple UI composition and interaction design. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [Core Store](https://dimsumthinking.com/Blog/2021/03/04-CoreStore.html) — iOS Dev Weekly · Issue 497 — Article · Topics: Combine & Reactive Programming · Core Data · Persistence & Synchronisation
  **Published:** `5th March 2021`
  **NeKI brief:** Examines Core Store, focusing on core data works well with new technologies like swiftui and combine, but does it feel at home with them? it does not. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Hummingbird](https://opticalaberration.com/2021/02/hummingbird.html) — iOS Dev Weekly · Issue 496 — Article · Topics: Architecture · Cross-Platform & Web · Swift
  **Published:** `26th February 2021`
  **NeKI brief:** Examines Hummingbird, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [which scissor emojis could actually cut paper](https://wh0.github.io/2020/01/02/scissors.html) — iOS Dev Weekly · Issue 488 — Article · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `1st January 2021`
  **NeKI brief:** Covers which scissor emojis could actually cut paper, focusing on Swift and Apple-platform engineering practice. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [swift-snapshot-testing](https://github.com/pointfreeco/swift-snapshot-testing) — iOS Dev Weekly · Issue 486 — Source repository · Topics: Cross-Platform & Web · Swift · Testing
  **Published:** `11th December 2020`
  **NeKI brief:** SnapshotTesting can launch UI tests with a specified content-size category, making large accessibility sizes reproducible in image assertions. Follow it to catch Dynamic Type layout regressions that ordinary interaction tests may miss.
- [open-source](https://github.com/SwiftPackageIndex/SwiftPackageIndex-Server) — iOS Dev Weekly · Issue 486 — Source repository · Topics: Swift · Swift Package Manager · Testing
  **Published:** `11th December 2020`
  **NeKI brief:** Examines open-source, focusing on georgios recommends the point-free swift-snapshot-testing which we also use to test the rendered html output from the…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Adaptive SwiftUI views](https://fivestars.blog/swiftui/adaptive-swiftui-views.html) — iOS Dev Weekly · Issue 480 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `30th October 2020`
  **NeKI brief:** Examines Adaptive SwiftUI views, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Mastering transitions in SwiftUI](https://nerdyak.tech/development/2020/10/12/transitions-in-swiftui.html) — iOS Dev Weekly · Issue 478 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `16th October 2020`
  **NeKI brief:** Examines Mastering transitions in SwiftUI, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Label](https://fivestars.blog/swiftui/label.html) — iOS Dev Weekly · Issue 475 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `25th September 2020`
  **NeKI brief:** Examines Label, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Conditional view modifiers](https://fivestars.blog/swiftui/conditional-modifiers.html) — iOS Dev Weekly · Issue 472 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `4th September 2020`
  **NeKI brief:** Examines Conditional view modifiers, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Flexible layouts in SwiftUI](https://fivestars.blog/swiftui/flexible-swiftui.html) — iOS Dev Weekly · Issue 470 — Tutorial · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `21st August 2020`
  **NeKI brief:** Covers Flexible layouts in SwiftUI, focusing on Apple UI composition and interaction design. Use the examples to compare implementation choices, assess edge cases, and plan verification in a production codebase; confirm current SDK support before adopting this historical guidance.
- [XCSSET Malware Infects Xcode Projects](https://blog.trendmicro.com/trendlabs-security-intelligence/xcsset-mac-malware-infects-xcode-projects-performs-uxss-attack-on-safari-other-browsers-leverages-zero-day-exploits) — iOS Dev Weekly · Issue 469 — Article · Topics: Cross-Platform & Web · Developer Tools · Xcode
  **Published:** `14th August 2020`
  **NeKI brief:** Examines XCSSET Malware Infects Xcode Projects, offering practical guidance on Xcode tooling and development workflow. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [full report](https://documents.trendmicro.com/assets/pdf/XCSSET_Technical_Brief.pdf) — iOS Dev Weekly · Issue 469 — Article · Topics: Cross-Platform & Web · Developer Tools · Xcode
  **Published:** `14th August 2020`
  **NeKI brief:** Details Trend Micro's XCSSET technical findings, including malicious Xcode-project behavior and attack vectors. Use the report to review supply-chain defenses and CI isolation, while checking its historical threat context before acting.
- [Sharing layout information in SwiftUI](https://fivestars.blog/swiftui/swiftui-share-layout-information.html) — iOS Dev Weekly · Issue 469 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `14th August 2020`
  **NeKI brief:** Examines Sharing layout information in SwiftUI, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Building a Multi-platform App with SwiftUI](https://heartbeat.fritz.ai/building-a-multi-platform-app-with-swiftui-5336bce94689) — iOS Dev Weekly · Issue 468 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `7th August 2020`
  **NeKI brief:** Examines Building a Multi-platform App with SwiftUI, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Creating custom .redacted effects](https://fivestars.blog/code/redacted-custom-effects.html) — iOS Dev Weekly · Issue 467 — Tutorial · Topics: Cross-Platform & Web · Developer Community & Business · Swift
  **Published:** `31st July 2020`
  **NeKI brief:** Examines Creating custom .redacted effects, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Double-Edged Sword](https://mohsen.dev/2020/06/21/swiftui-double-edged-sword.html) — iOS Dev Weekly · Issue 462 — Article · Topics: Architecture · Swift · SwiftUI
  **Published:** `26th June 2020`
  **NeKI brief:** Examines Double-Edged Sword, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [TikTok logo-ish effect in SwiftUI](https://nerdyak.tech/development/2020/06/12/create-tiktok-logo-effect-in-swiftui.html) — iOS Dev Weekly · Issue 461 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `19th June 2020`
  **NeKI brief:** Examines TikTok logo-ish effect in SwiftUI, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Loca Studio – a native Mac app to xcloc like a pro](https://www.cunningo.com/locastudio/index.html) — iOS Dev Weekly · Issue 451 — Article · Topics: Cross-Platform & Web · Xcode
  **Published:** `10th April 2020`
  **NeKI brief:** Examines Loca Studio – a native Mac app to xcloc like a pro, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [A Look Into ArgumentParser](https://www.fivestars.blog/code/a-look-into-argument-parser.html) — iOS Dev Weekly · Issue 448 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `20th March 2020`
  **NeKI brief:** Examines A Look Into ArgumentParser, offering practical guidance on Swift Package Manager integration. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [the ultimate guide to Swift executables](https://www.fivestars.blog//code/ultimate-guide-swift-executables.html) — iOS Dev Weekly · Issue 448 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `20th March 2020`
  **NeKI brief:** Examines the ultimate guide to Swift executables, offering practical guidance on Swift Package Manager integration. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Xcode’s Find Navigator & Search Scopes](https://patrickbalestra.com/blog/2020/02/09/xcode-find-navigator.html) — iOS Dev Weekly · Issue 443 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Xcode
  **Published:** `14th February 2020`
  **NeKI brief:** Examines Xcode's Find Navigator & Search Scopes, offering practical guidance on Xcode tooling and development workflow. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Animating complex shapes in SwiftUI](https://nerdyak.tech/development/2020/01/12/animating-complex-shapes-in-swiftui.html) — iOS Dev Weekly · Issue 439 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `17th January 2020`
  **NeKI brief:** Examines Animating complex shapes in SwiftUI, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Using Type Erasure to Build a Dependency Injecting Routing Framework](https://swiftrocks.com/using-type-erasure-to-build-a-dependency-injector-in-swift.html) — iOS Dev Weekly · Issue 437 — Article · Topics: Architecture · Dependency Injection · Swift
  **Published:** `3rd January 2020`
  **NeKI brief:** Examines Using Type Erasure to Build a Dependency Injecting Routing Framework, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Custom controls in SwiftUI](https://izakpavel.github.io/development/2019/11/28/creating-custom-views-in-swiftui.html) — iOS Dev Weekly · Issue 434 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `13th December 2019`
  **NeKI brief:** Examines Custom controls in SwiftUI, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Injecting and changing code on the fly with LLDB](https://swiftrocks.com/using-lldb-manually-xcode-console-tricks.html) — iOS Dev Weekly · Issue 416 — Article · Topics: Cross-Platform & Web · Dependency Injection · Swift
  **Published:** `9th August 2019`
  **NeKI brief:** Examines Injecting and changing code on the fly with LLDB, offering practical guidance on Xcode tooling and development workflow. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [One small change for Xcode, one giant leap for productivity](http://mohsen.dev/2019/05/19/one-small-change-for-xcode-one-giant-leap-for-productivity.html) — iOS Dev Weekly · Issue 409 — Article · Topics: Cross-Platform & Web · Personal Essays · Xcode
  **Published:** `21st June 2019`
  **NeKI brief:** Examines One small change for Xcode, one giant leap for productivity, offering practical guidance on Xcode tooling and development workflow. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Declarative iOS layout with Panda](http://blog.bellebcooper.com/ios-layout-with-panda.html) — iOS Dev Weekly · Issue 407 — Article · Topics: Cross-Platform & Web · Swift · SwiftUI
  **Published:** `7th June 2019`
  **NeKI brief:** Examines Declarative iOS layout with Panda, offering practical guidance on SwiftUI composition and layout behavior. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Understanding the iOS Responder Chain](https://swiftrocks.com/understanding-the-ios-responder-chain.html) — iOS Dev Weekly · Issue 394 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `8th March 2019`
  **NeKI brief:** Examines Understanding the iOS Responder Chain, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Measuring iOS scroll performance is tough](http://thisiskyle.me/posts/measuring-ios-scroll-performance-is-tough-use-this-to-make-it-simple-and-automated.html) — iOS Dev Weekly · Issue 380 — Article · Topics: Cross-Platform & Web · Performance · Testing
  **Published:** `30th November 2018`
  **NeKI brief:** Examines Measuring iOS scroll performance is tough, offering practical guidance on Swift engineering practice. Apply its examples to compare choices and spot edge cases, then verify historical SDK assumptions before production use.
- [Improving Your Build Time in Xcode 10](https://patrickbalestra.com/blog/2018/08/27/improving-your-build-time-in-xcode-10.html) — iOS Dev Weekly · Issue 367 — Article · Topics: Apple Platform Ecosystem · Cross-Platform & Web · Xcode
  **Published:** `31st August 2018`
  **NeKI brief:** Explores Improving Your Build Time in Xcode 10 in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Getting Started with Flutter](https://www.raywenderlich.com/188257/getting-started-with-flutter) — iOS Dev Weekly · Issue 343 — Article · Topics: Cross-Platform & Web
  **Published:** `16th March 2018`
  **NeKI brief:** Examines Getting Started with Flutter, focusing on the author’s note that came across flutter a few weeks ago but hadn’t had a chance to check it out. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [this article](https://www.bloomberg.com/news/articles/2017-12-20/apple-is-said-to-have-plan-to-combine-iphone-ipad-and-mac-apps) — iOS Dev Weekly · Issue 332 — Article · Topics: Combine & Reactive Programming · Cross-Platform & Web
  **Published:** `22nd December 2017`
  **NeKI brief:** Reports the historical proposal to unify iPhone, iPad, and Mac app distribution or development. Use it as platform-strategy context when assessing multiplatform architecture, while treating predictions as historical and checking the current Apple deployment model.
- [documentation](https://help.apple.com/xcode/mac/9.0/index.html?localePath=en.lproj) — iOS Dev Weekly · Issue 311 — Article · Topics: Cross-Platform & Web · Xcode
  **Published:** `28th July 2017`
  **NeKI brief:** Examines documentation, focusing on for as long as i can remember, it has been possible to customise the new file templates in xcode but it has always been…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current.
- [Why Core ML will not work for your app (most likely)](http://alexsosn.github.io/ml/2017/06/09/Core-ML-will-not-Work-for-Your-App.html) — iOS Dev Weekly · Issue 307 — Article · Topics: AI Development · Cross-Platform & Web · Developer Tools
  **Published:** `30th June 2017`
  **NeKI brief:** Explores Why Core ML will not work for your app (most likely) in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [Apple Open-Sourcing the Swift Toolchain](https://lists.swift.org/pipermail/swift-dev/Week-of-Mon-20170605/004751.html) — iOS Dev Weekly · Issue 305 — Article · Topics: Concurrency · Cross-Platform & Web · Swift
  **Published:** `16th June 2017`
  **NeKI brief:** Examines Apple Open-Sourcing the Swift Toolchain, focusing on ted kremenek lays out apple’s plans to open-source parts of the swift toolchain, including the new refactoring engine. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [SwiftKotlin: A tool to convert Swift code to Kotlin](https://github.com/angelolloqui/SwiftKotlin) — iOS Dev Weekly · Issue 303 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `2nd June 2017`
  **NeKI brief:** Examines SwiftKotlin, focusing on tool for converting swift code to kotlin. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Swift 3 migration post mortem](https://mozilla-mobile.github.io/ios/firefox/swift/core/2017/02/22/migrating-to-swift-3.0.html) — iOS Dev Weekly · Issue 289 — Article · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `24th February 2017`
  **NeKI brief:** Explores Swift 3 migration post mortem in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [list of goals](https://lists.swift.org/pipermail/swift-evolution/Week-of-Mon-20160725/025676.html) — iOS Dev Weekly · Issue 284 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `20th January 2017`
  **NeKI brief:** Examines list of goals, focusing on this document appeared last night in the swift repository and it contains a huge amount of information about the plans…. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Perfect code is an illusion](https://8thlight.com/blog/daniel-irvine/2016/11/11/perfect-code-is-an-illusion.html) — iOS Dev Weekly · Issue 277 — Article · Topics: Cross-Platform & Web
  **Published:** `18th November 2016`
  **NeKI brief:** Daniel Irvine argues that pursuing perfect code obscures the iterative and contextual nature of software work. It is a craft perspective for balancing refinement against delivery.
- [How to Deploy Vapor Apps to Heroku](https://www.twilio.com/blog/2016/11/how-to-deploy-vapor-apps-to-heroku.html) — iOS Dev Weekly · Issue 275 — Article · Topics: Cross-Platform & Web · Personal Essays · Swift
  **Published:** `4th November 2016`
  **NeKI brief:** Explores How to Deploy Vapor Apps to Heroku in an Apple-platform development context, highlighting practical techniques, design decisions, or trade-offs. Use it as historical community guidance, then validate implementation details, security considerations, and current SDK behavior before applying it.
- [action](https://github.com/apple/swift/pull/1442) — iOS Dev Weekly · Issue 272 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `14th October 2016`
  **NeKI brief:** Provides the pull request source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [post on swift-dev](https://lists.swift.org/pipermail/swift-dev/Week-of-Mon-20160725/002520.html) — iOS Dev Weekly · Issue 261 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `29th July 2016`
  **NeKI brief:** Examines post on swift-dev, focusing on jesse squires with some advice on how to approach converting your code, or in this case open source libraries, to swift 3. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current.
- [Why we put an app in the Android Play Store using Swift](https://medium.com/@ephemer/why-we-put-an-app-in-the-android-play-store-using-swift-96ac87c88dfc) — iOS Dev Weekly · Issue 259 — Article · Topics: Cross-Platform & Web · Performance · Swift
  **Published:** `15th July 2016`
  **NeKI brief:** Examines Why we put an app in the Android Play Store using Swift, focusing on can you include swift code in your android app? yes, you can. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [how they did it](https://medium.com/@ephemer/how-we-put-an-app-in-the-android-play-store-using-swift-67bd99573e3c) — iOS Dev Weekly · Issue 259 — Article · Topics: Cross-Platform & Web · Performance · Swift
  **Published:** `15th July 2016`
  **NeKI brief:** Examines how they did it, focusing on can you include swift code in your android app? yes, you can. Use it as a focused research reference for related Apple-platform work, and verify version-specific details against current documentation.
- [Render: Swift and UIKit a la React](https://github.com/alexdrone/Render) — iOS Dev Weekly · Issue 252 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Swift
  **Published:** `27th May 2016`
  **NeKI brief:** Examines Render: Swift and UIKit a la React, focusing on if you like the concept of your ui being purely a function of your app’s state, but are not quite ready to go all in on…. Use it as a focused research reference for related.
- [Creating Swift Frameworks for iOS, watchOS, and tvOS](http://basememara.com/creating-cross-platform-swift-frameworks-ios-watchos-tvos-via-carthage-cocoapods) — iOS Dev Weekly · Issue 243 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `25th March 2016`
  **NeKI brief:** Explains Creating Swift Frameworks for iOS watchOS and tvOS with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [Partial functions in Swift, Part 1: Avoidance](http://cocoawithlove.com/blog/2016/01/25/partial-functions-part-one-avoidance.html) — iOS Dev Weekly · Issue 235 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `29th January 2016`
  **NeKI brief:** Explains Partial functions in Swift Part 1 Avoidance with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [Feature Toggles](http://martinfowler.com/articles/feature-toggles.html) — iOS Dev Weekly · Issue 234 — Tutorial · Topics: Cross-Platform & Web · Developer Community & Business · Testing
  **Published:** `22nd January 2016`
  **NeKI brief:** Explains Feature Toggles with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Managing Xcode](http://pewpewthespells.com/blog/managing_xcode.html) — iOS Dev Weekly · Issue 215 — Article · Topics: Cross-Platform & Web · Dependency Injection · Xcode
  **Published:** `11th September 2015`
  **NeKI brief:** Explains Managing Xcode with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [guide to xcconfig files](http://pewpewthespells.com/blog/xcconfig_guide.html) — iOS Dev Weekly · Issue 215 — Article · Topics: Cross-Platform & Web · Dependency Injection · Xcode
  **Published:** `11th September 2015`
  **NeKI brief:** Explains The Unofficial Guide to xcconfig files with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Protocols - My Current Recommendations](http://owensd.io/2015/08/06/protocols.html) — iOS Dev Weekly · Issue 211 — Tutorial · Topics: Cross-Platform & Web · Developer Community & Business · Swift
  **Published:** `14th August 2015`
  **NeKI brief:** Explains Protocols My Current Recommendations with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Address Sanitizer](https://mikeash.com/pyblog/friday-qa-2015-07-03-address-sanitizer.html) — iOS Dev Weekly · Issue 206 — Article · Topics: Apple Platform Ecosystem · Cross-Platform & Web · Developer Tools
  **Published:** `10th July 2015`
  **NeKI brief:** Explains Address Sanitizer with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Finally, true native iOS to Android code conversion at your fingertips](https://www.myappconverter.com/campaign/iosdevweekly) — iOS Dev Weekly · Issue 197 — Article · Topics: Cross-Platform & Web
  **Published:** `8th May 2015`
  **NeKI brief:** Describes a commercial Objective-C-to-Swift conversion service and its claimed migration workflow. Treat it as historical tooling context and evaluate generated-code quality, framework coverage, and licensing before considering automated migration for a production app.
- [A First Look at ReactiveCocoa 3.0](http://blog.scottlogic.com/2015/04/24/first-look-reactive-cocoa-3.html) — iOS Dev Weekly · Issue 195 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Swift
  **Published:** `24th April 2015`
  **NeKI brief:** Explains A First Look at ReactiveCocoa 3.0 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [iOS Charts](https://github.com/danielgindi/ios-charts) — iOS Dev Weekly · Issue 192 — Source repository · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `3rd April 2015`
  **NeKI brief:** Provides the iOS Charts source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart) — iOS Dev Weekly · Issue 192 — Source repository · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `3rd April 2015`
  **NeKI brief:** Provides the MPAndroidChart source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [available publicly](https://github.com/facebook/react-native) — iOS Dev Weekly · Issue 191 — Source repository · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `27th March 2015`
  **NeKI brief:** Provides the available publicly source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Implementing React.js in Swift](http://blog.scottlogic.com/2015/03/05/reactjs-in-swift.html) — iOS Dev Weekly · Issue 188 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `6th March 2015`
  **NeKI brief:** Explains Implementing React.js in Swift with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [SwiftMoment](https://github.com/akosma/SwiftMoment) — iOS Dev Weekly · Issue 186 — Source repository · Topics: Developer Tools · Swift
  **Published:** `20th February 2015`
  **NeKI brief:** Provides the SwiftMoment source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [TIOBE](http://www.tiobe.com/index.php/content/paperinfo/tpci/index.html) — iOS Dev Weekly · Issue 181 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `16th January 2015`
  **NeKI brief:** Explains TIOBE with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Debugging: A Case Study](http://www.objc.io/issue-19/debugging-case-study.html) — iOS Dev Weekly · Issue 176 — Article · Topics: Cross-Platform & Web · Developer Tools · Testing
  **Published:** `12th December 2014`
  **NeKI brief:** Explains Debugging A Case Study with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Continuous Integration With Xcode Server](http://useyourloaf.com/blog/2014/11/02/continuous-integration-with-xcode-server.html) — iOS Dev Weekly · Issue 171 — Article · Topics: CI/CD & Automation · Cross-Platform & Web · Xcode
  **Published:** `7th November 2014`
  **NeKI brief:** A historical Xcode Server CI setup guide showing how bots, integrations, and signing fit together. It is useful for understanding the pre-Xcode-Cloud workflow and its operational constraints.
- [Friday Q&A: Interesting Swift Features](https://mikeash.com/pyblog/friday-qa-2014-06-20-interesting-swift-features.html) — iOS Dev Weekly · Issue 152 — Article · Topics: Cross-Platform & Web · Swift
  **Published:** `27th June 2014`
  **NeKI brief:** Explains Friday Q A Interesting Swift Features with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Mobile Designer at MailChimp](http://mailchimp.theresumator.com/apply/4Jnpzz/DesignerMobile-Apps-Team.html) — iOS Dev Weekly · Issue 146 — Article · Topics: Cross-Platform & Web · Xcode
  **Published:** `16th May 2014`
  **NeKI brief:** Explains Mobile Designer at MailChimp with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Running Custom Clang Analyzer Builds](http://useyourloaf.com/blog/2014/04/16/running-custom-clang-analyzer-builds.html) — iOS Dev Weekly · Issue 142 — Article · Topics: Cross-Platform & Web · Personal Essays
  **Published:** `18th April 2014`
  **NeKI brief:** Explains Running Custom Clang Analyzer Builds with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Quick Look on UIViews](http://useyourloaf.com/blog/2014/03/12/xcode-debugger-quick-look.html) — iOS Dev Weekly · Issue 137 — Article · Topics: Cross-Platform & Web · Developer Tools · Xcode
  **Published:** `14th March 2014`
  **NeKI brief:** Explains Quick Look on UIViews with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Learn by Doing with Code School](https://www.codeschool.com/paths/ios) — iOS Dev Weekly · Issue 134 — Tutorial · Topics: Cross-Platform & Web · Developer Community & Business · Developer Tools
  **Published:** `21st February 2014`
  **NeKI brief:** Explains Learn by Doing with Code School with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [NSString and Unicode](http://www.objc.io/issue-9/unicode.html) — iOS Dev Weekly · Issue 133 — Article · Topics: Cross-Platform & Web · Foundation & Data Formats · Testing
  **Published:** `14th February 2014`
  **NeKI brief:** Explains NSString and Unicode with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Podlife](http://davander.com/podlife.html) — iOS Dev Weekly · Issue 121 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `22nd November 2013`
  **NeKI brief:** Explains Podlife with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [The Build Process](http://www.objc.io/issue-6/build-process.html) — iOS Dev Weekly · Issue 120 — Article · Topics: Cross-Platform & Web · Testing · Xcode
  **Published:** `15th November 2013`
  **NeKI brief:** Explains The Build Process with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Apportable](http://www.youtube.com/watch?v=dSkhtd6L8RM) — iOS Dev Weekly · Issue 117 — Video · Topics: App Services & Extensions · Core Data · Cross-Platform & Web
  **Published:** `25th October 2013`
  **NeKI brief:** Builds a SwiftUI showcase view that highlights new app features for users. Useful for designing first-run or release-note presentations with reusable paging, emphasis, and dismissal behavior.
- [Friday Q&A: Why Registers Are Fast and RAM Is Slow](http://www.mikeash.com/pyblog/friday-qa-2013-10-11-why-registers-are-fast-and-ram-is-slow.html) — iOS Dev Weekly · Issue 116 — Article · Topics: Cross-Platform & Web
  **Published:** `18th October 2013`
  **NeKI brief:** Registers, caches, and RAM have radically different latency and bandwidth characteristics, so data locality shapes performance more than isolated instruction counts. This helps interpret profiling results.
- [Handlebars for Objective-C](https://github.com/fotonauts/handlebars-objc) — iOS Dev Weekly · Issue 116 — Source repository · Topics: Developer Tools · Objective-C & Cocoa
  **Published:** `18th October 2013`
  **NeKI brief:** Provides the Handlebars for Objective-C source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Non-pointer isa](http://www.sealiesoftware.com/blog/archive/2013/09/24/objc_explain_Non-pointer_isa.html) — iOS Dev Weekly · Issue 113 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `27th September 2013`
  **NeKI brief:** Explains Non-pointer isa with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [LLDB-QuickLook](https://github.com/ryanolsonk/LLDB-QuickLook) — iOS Dev Weekly · Issue 112 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Xcode
  **Published:** `20th September 2013`
  **NeKI brief:** Provides the LLDB-QuickLook source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [IGHTMLQuery](https://github.com/siuying/IGHTMLQuery) — iOS Dev Weekly · Issue 108 — Source repository · Topics: Cross-Platform & Web · Developer Tools · Testing
  **Published:** `23rd August 2013`
  **NeKI brief:** Provides the IGHTMLQuery source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Callbacks as our Generations’ Go To Statement](http://tirania.org/blog/archive/2013/Aug-15.html) — iOS Dev Weekly · Issue 107 — Article · Topics: Concurrency · Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `16th August 2013`
  **NeKI brief:** Explains Callbacks as our Generations’ Go To Statement with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [DB5](http://inessential.com/2013/06/27/open_source_db5) — iOS Dev Weekly · Issue 100 — Article · Topics: Cross-Platform & Web
  **Published:** `28th June 2013`
  **NeKI brief:** Explains DB5 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [UIRefreshControl Fun and Games](http://useyourloaf.com/blog/2013/06/18/uirefreshcontrol-fun-and-games.html) — iOS Dev Weekly · Issue 99 — Article · Topics: Cross-Platform & Web · Graphics, Media & Games
  **Published:** `21st June 2013`
  **NeKI brief:** Explains UIRefreshControl Fun and Games with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Sound Debugging](http://qnoid.com/2013/06/08/Sound-Debugging.html) — iOS Dev Weekly · Issue 98 — Article · Topics: Cross-Platform & Web · Developer Tools · Xcode
  **Published:** `14th June 2013`
  **NeKI brief:** Explains Sound Debugging with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Subliminal](https://github.com/inkling/Subliminal) — iOS Dev Weekly · Issue 98 — Source repository · Topics: Cross-Platform & Web · Objective-C & Cocoa · Testing
  **Published:** `14th June 2013`
  **NeKI brief:** Provides the Subliminal source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [Apple’s new Objective-C to Javascript Bridge](http://www.steamclock.com/blog/2013/05/apple-objective-c-javascript-bridge) — iOS Dev Weekly · Issue 94 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Systems Programming
  **Published:** `17th May 2013`
  **NeKI brief:** Explains Apple’s new Objective-C to Javascript Bridge with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Proper Use of Asserts](http://www.mikeash.com/pyblog/friday-qa-2013-05-03-proper-use-of-asserts.html) — iOS Dev Weekly · Issue 93 — Article · Topics: Cross-Platform & Web
  **Published:** `10th May 2013`
  **NeKI brief:** Assertions document programmer invariants and fail early in development, while recoverable user or network errors need normal control flow. The article helps keep diagnostic checks from becoming production error handling.
- [We Need A Standard Layered Image Format](http://shapeof.com/archives/2013/4/we_need_a_standard_layered_image_format.html) — iOS Dev Weekly · Issue 92 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `3rd May 2013`
  **NeKI brief:** Explains We Need A Standard Layered Image Format with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [Learn the ropes of Mobile Services with Brent Simmons](http://www.windowsazure.com/en-us/develop/mobile/ios?WT.mc_id=azuregb_us_display_mirluna_2) — iOS Dev Weekly · Issue 87 — Article · Topics: App Services & Extensions
  **Published:** `29th March 2013`
  **NeKI brief:** Explains Learn the ropes of Mobile Services with Brent Simmons with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS.
- [Xcode 4.6 Recommended Build Settings](http://useyourloaf.com/blog/2013/03/03/xcode-4-dot-6-recommended-build-settings.html) — iOS Dev Weekly · Issue 84 — Article · Topics: Cross-Platform & Web · Xcode
  **Published:** `8th March 2013`
  **NeKI brief:** Explains Xcode 4.6 Recommended Build Settings with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [The Case Against Xcode Plugins](http://www.edgecasesshow.com/032-the-case-against-xcode-plugins.html) — iOS Dev Weekly · Issue 77 — Podcast · Topics: Cross-Platform & Web · Developer Community & Business · Xcode
  **Published:** `18th January 2013`
  **NeKI brief:** Explains The Case Against Xcode Plugins with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Halving size of iPad app with ImageOptim+ImageAlpha](http://imageoptim.com/tweetbot.html) — iOS Dev Weekly · Issue 76 — Article · Topics: Cross-Platform & Web · Developer Tools · Xcode
  **Published:** `11th January 2013`
  **NeKI brief:** Explains Halving size of iPad app with ImageOptim+ImageAlpha with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [Friday Q&A: Objective-C Pitfalls](http://www.mikeash.com/pyblog/friday-qa-2012-12-14-objective-c-pitfalls.html) — iOS Dev Weekly · Issue 73 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `21st December 2012`
  **NeKI brief:** Objective-C pitfalls often arise from dynamic dispatch, nil messaging, ownership conventions, and type erasure interacting unexpectedly. The review is useful for locating boundaries where static Swift assumptions do not apply.
- [Let’s Build objc_msgSend](http://www.mikeash.com/pyblog/friday-qa-2012-11-16-lets-build-objc_msgsend.html) — iOS Dev Weekly · Issue 69 — Article · Topics: Cross-Platform & Web
  **Published:** `23rd November 2012`
  **NeKI brief:** Rebuilding objc_msgSend exposes selector lookup, receiver dispatch, and calling-convention constraints at the Objective-C runtime boundary. The experiment explains why dynamic messaging cannot be replaced with an arbitrary function pointer.
- [Chaos Testing With UI AutoMonkey](http://cocoamanifest.net/articles/2012/11/chaos-testing-with-ui-automonkey.html) — iOS Dev Weekly · Issue 66 — Article · Topics: Cross-Platform & Web · Developer Tools · Testing
  **Published:** `2nd November 2012`
  **NeKI brief:** Explains Chaos Testing With UI AutoMonkey with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Implementing Smart App Banners](http://david-smith.org/blog/2012/09/20/implementing-smart-app-banners) — iOS Dev Weekly · Issue 61 — Article · Topics: Apple Platform Ecosystem · Cross-Platform & Web
  **Published:** `28th September 2012`
  **NeKI brief:** Explains Implementing Smart App Banners with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [The White House App released as Open Sorce](https://github.com/WhiteHouse/wh-app-ios) — iOS Dev Weekly · Issue 58 — Source repository · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `7th September 2012`
  **NeKI brief:** Provides the The White House App released as Open Sorce source repository, showing the implementation surface and project structure behind the featured idea. Use it to inspect concrete APIs, integration boundaries, and maintenance trade-offs before adapting the historical code to a current Apple-platform project.
- [PonyDebugger: Remote Debugging Tools for Native iOS Apps](http://corner.squareup.com/2012/08/ponydebugger-remote-debugging.html) — iOS Dev Weekly · Issue 57 — Article · Topics: Cross-Platform & Web · Developer Tools
  **Published:** `31st August 2012`
  **NeKI brief:** Explains PonyDebugger Remote Debugging Tools for Native iOS Apps with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [Stop Xcode Automatic Termination](http://useyourloaf.com/blog/2012/08/13/xcode-automatic-termination.html) — iOS Dev Weekly · Issue 55 — Article · Topics: Cross-Platform & Web · Xcode
  **Published:** `17th August 2012`
  **NeKI brief:** Explains Stop Xcode Automatic Termination with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [0xced: Prepare your apps for the new iPhone](http://0xced.blogspot.co.at/2012/08/prepare-your-apps-for-new-iphone.html) — iOS Dev Weekly · Issue 54 — Article · Topics: Cross-Platform & Web
  **Published:** `10th August 2012`
  **NeKI brief:** Documents preparing an iOS app for a new iPhone screen size through adaptable layouts and asset handling. Use it as historical Auto Layout migration context, not current device-specific implementation guidance.
- [Automatic Property Synthesis with Xcode 4.4](http://useyourloaf.com/blog/2012/08/01/property-synthesis-with-xcode-4-dot-4.html) — iOS Dev Weekly · Issue 53 — Article · Topics: Cross-Platform & Web · Xcode
  **Published:** `3rd August 2012`
  **NeKI brief:** Explains Automatic Property Synthesis with Xcode 4.4 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Finding relevant WWDC videos](http://www.escortmissions.com/blog/2012/7/22/finding-relevant-wwdc-videos.html) — iOS Dev Weekly · Issue 52 — Article · Topics: App Intents & System Surfaces · Apple Platform Ecosystem · Graphics, Media & Games
  **Published:** `27th July 2012`
  **NeKI brief:** Explains Finding relevant WWDC videos with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Friday Q&A: Objective-C Literals](http://www.mikeash.com/pyblog/friday-qa-2012-06-22-objective-c-literals.html) — iOS Dev Weekly · Issue 48 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `29th June 2012`
  **NeKI brief:** Objective-C literals provide concise syntax for boxed numbers, arrays, dictionaries, and subscripting while retaining runtime collection semantics. The overview helps spot where literal convenience masks mutability or nullability concerns.
- [Shell Apps and Silver Bullets](http://sandofsky.com/blog/shell-apps.html) — iOS Dev Weekly · Issue 41 — Article · Topics: Cross-Platform & Web
  **Published:** `11th May 2012`
  **NeKI brief:** Explains Shell Apps and Silver Bullets with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Friday Q&A: Nib Memory Management](http://mikeash.com/pyblog/friday-qa-2012-04-13-nib-memory-management.html) — iOS Dev Weekly · Issue 38 — Article · Topics: Cross-Platform & Web · Developer Career & Practice
  **Published:** `20th April 2012`
  **NeKI brief:** Explains Friday Q A Nib Memory Management with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Introducing PLWeakCompatibility](http://www.mikeash.com/pyblog/introducing-plweakcompatibility.html) — iOS Dev Weekly · Issue 36 — Article · Topics: Cross-Platform & Web
  **Published:** `6th April 2012`
  **NeKI brief:** PLWeakCompatibility backports weak-reference behavior for runtimes without native support, relying on runtime hooks and careful lifecycle handling. It is valuable historical context for mixed deployment targets and compatibility shims.
- [Objective-C Literals](http://clang.llvm.org/docs/ObjectiveCLiterals.html) — iOS Dev Weekly · Issue 34 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa · Systems Programming
  **Published:** `23rd March 2012`
  **NeKI brief:** Explains Objective-C Literals with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Key-Value Observing Done Right: Take 2](http://www.mikeash.com/pyblog/friday-qa-2012-03-02-key-value-observing-done-right-take-2.html) — iOS Dev Weekly · Issue 32 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `9th March 2012`
  **NeKI brief:** Explains Key-Value Observing Done Right Take 2 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Git branch management with Xcode](http://useyourloaf.com/blog/2012/2/29/git-branch-management-with-xcode.html) — iOS Dev Weekly · Issue 31 — Article · Topics: Developer Career & Practice · Developer Tools · Xcode
  **Published:** `2nd March 2012`
  **NeKI brief:** Explains Git branch management with Xcode with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Introducing SocketRocket](http://corner.squareup.com/2012/02/socketrocket-websockets.html) — iOS Dev Weekly · Issue 28 — Article · Topics: Cross-Platform & Web · Networking
  **Published:** `10th February 2012`
  **NeKI brief:** Explains Introducing SocketRocket with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Core Data Queries Using Expressions](http://useyourloaf.com/blog/2012/1/19/core-data-queries-using-expressions.html) — iOS Dev Weekly · Issue 26 — Article · Topics: Core Data · Cross-Platform & Web · Persistence & Synchronisation
  **Published:** `27th January 2012`
  **NeKI brief:** Explains Core Data Queries Using Expressions with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [UIStoryboard Power Drill](http://jleeiii.blogspot.com/2012/01/uistoryboard-power-drill.html) — iOS Dev Weekly · Issue 26 — Article · Topics: Cross-Platform & Web
  **Published:** `27th January 2012`
  **NeKI brief:** Explains UIStoryboard Power Drill with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [UIAlertView changes in iOS 5](http://useyourloaf.com/blog/2011/12/14/uialertview-changes-in-ios-5.html) — iOS Dev Weekly · Issue 20 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `16th December 2011`
  **NeKI brief:** Explains UIAlertView changes in iOS 5 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [LLVM 3.0 Release Notes](http://llvm.org/releases/3.0/docs/ReleaseNotes.html) — iOS Dev Weekly · Issue 19 — Article · Topics: Cross-Platform & Web · Systems Programming · Xcode
  **Published:** `9th December 2011`
  **NeKI brief:** Explains LLVM 3.0 Release Notes with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Simple iOS 5 UI Design Tutorial Using Storyboard in XCode 4](http://kurrytran.blogspot.com/2011/07/simple-ios-5-tutorial-using-storyboard.html) — iOS Dev Weekly · Issue 18 — Tutorial · Topics: Cross-Platform & Web · Xcode
  **Published:** `2nd December 2011`
  **NeKI brief:** Explains Simple iOS 5 UI Design Tutorial Using Storyboard in XCode 4 with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a.
- [Settings Radio Group Element](http://useyourloaf.com/blog/2011/11/1/settings-radio-group-element.html) — iOS Dev Weekly · Issue 14 — Article · Topics: Cross-Platform & Web
  **Published:** `4th November 2011`
  **NeKI brief:** Explains Settings Radio Group Element with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Sync preference data with iCloud](http://useyourloaf.com/blog/2011/10/24/sync-preference-data-with-icloud.html) — iOS Dev Weekly · Issue 13 — Article · Topics: Cross-Platform & Web
  **Published:** `28th October 2011`
  **NeKI brief:** Explains Sync preference data with iCloud with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Using Regular Expressions Part 2 - the Cocoa Connection](http://www.escortmissions.com/blog/2011/10/15/using-regular-expressions-part-2-the-cocoa-connection.html) — iOS Dev Weekly · Issue 12 — Article · Topics: Cross-Platform & Web · Objective-C & Cocoa
  **Published:** `21st October 2011`
  **NeKI brief:** Explains Using Regular Expressions Part 2 the Cocoa Connection with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [Mobile Usability Update](http://www.useit.com/alertbox/mobile-usability.html) — iOS Dev Weekly · Issue 9 — Article · Topics: Cross-Platform & Web
  **Published:** `30th September 2011`
  **NeKI brief:** Explains Mobile Usability Update with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Xcode 4 DerivedData and cleaning the build directory](http://useyourloaf.com/blog/2011/9/14/xcode-4-deriveddata-and-cleaning-the-build-directory.html) — iOS Dev Weekly · Issue 8 — Article · Topics: Cross-Platform & Web · Xcode
  **Published:** `23rd September 2011`
  **NeKI brief:** Explains Xcode 4 DerivedData and cleaning the build directory with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev.
- [Let’s Build Reference Counting](http://www.mikeash.com/pyblog/friday-qa-2011-09-16-lets-build-reference-counting.html) — iOS Dev Weekly · Issue 8 — Article · Topics: Cross-Platform & Web
  **Published:** `23rd September 2011`
  **NeKI brief:** Explains Let’s Build Reference Counting with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Friday Q&A: Let’s Build NSAutoreleasePool](http://www.mikeash.com/pyblog/friday-qa-2011-09-02-lets-build-nsautoreleasepool.html) — iOS Dev Weekly · Issue 6 — Article · Topics: Cross-Platform & Web
  **Published:** `9th September 2011`
  **NeKI brief:** Explains Friday Q A Let’s Build NSAutoreleasePool with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly reference.
- [Friday Q&A: Namespaced Constants and Functions](http://www.mikeash.com/pyblog/friday-qa-2011-08-19-namespaced-constants-and-functions.html) — iOS Dev Weekly · Issue 4 — Article · Topics: Cross-Platform & Web
  **Published:** `26th August 2011`
  **NeKI brief:** Explains Friday Q A Namespaced Constants and Functions with a concrete Apple-platform development perspective and examples. Use it to understand the linked technique, workflow, or design trade-off, then verify API availability and assumptions against current SDK documentation because this is a historical iOS Dev Weekly.
- [MCP is dead. Long live the CLI](https://ejholmes.github.io/2026/02/28/mcp-is-dead-long-live-the-cli.html) — Not only Swift · Issue 95 — Article · Topics: AI Development · Cross-Platform & Web · Developer Tools
  **NeKI brief:** This article covers the case for durable command-line interfaces over MCP-only tooling. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Apple Docs MCP](https://github.com/kimsungwhee/apple-docs-mcp) — Not only Swift · Issue 94 — Source repository · Topics: AI Development · Developer Tools · Swift
  **NeKI brief:** This source repository covers an MCP server for searching Apple developer documentation. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [A Software Library with No Code](https://www.dbreunig.com/2026/01/08/a-software-library-with-no-code.html) — Not only Swift · Issue 92 — Article · Topics: Cross-Platform & Web
  **NeKI brief:** This article covers software libraries that contain no implementation code. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Why We've Tried to Replace Developers Every Decade Since 1969](https://www.caimito.net/en/blog/2025/12/07/the-recurring-dream-of-replacing-developers.html) — Not only Swift · Issue 90 — Article · Topics: Cross-Platform & Web
  **NeKI brief:** This article covers historical attempts to automate away software developers. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [radial menu](https://bigmedium.com/ideas/radial-menus-for-touch-ui.html) — Not only Swift · Issue 85 — Article · Topics: Cross-Platform & Web · Liquid Glass · Swift
  **NeKI brief:** This article covers radial menus as a touch-interface pattern. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
- [Introducing Swiftly 1.0](https://www.swift.org/blog/introducing-swiftly_10) — Not only Swift · Issue 78 — Article · Topics: Cross-Platform & Web · Developer Tools · Swift
  **NeKI brief:** This technical resource covers Swiftly 1.0 as a Swift toolchain manager. It gives iOS and Swift developers a concrete starting point to assess the workflow, implementation boundaries, operational trade-offs, and project fit before adopting it.
